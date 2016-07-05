#### Test 757892681403989_thali01_LGE-LG-D722 Logs


```
--------- beginning of main
07-05 12:00:00.307  1948  1948 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,07-05 12:00:01.782  5740  5740 D AndroidRuntime: 
07-05 12:00:01.782  5740  5740 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 12:00:01.786  5740  5740 D AndroidRuntime: CheckJNI is OFF
07-05 12:00:02.018  5740  5740 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-05 12:00:02.039   964  1971 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-05 12:00:02.096   964  1971 D ActivityManager: setTaskToReturnTo : TaskRecord{3deb6ac0 #241 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-05 12:00:02.096   964  1971 D ActivityManager: setTaskToReturnTo : TaskRecord{3deb6ac0 #241 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-05 12:00:02.115   964  1971 D WindowStateEx: AppWindowTokenEx init.. 
07-05 12:00:02.128   964  1056 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-05 12:00:02.144   964  1971 D InputDispatcher: Focus left window: Window{378c3f63 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
07-05 12:00:02.146  5740  5740 D AndroidRuntime: Shutting down VM
07-05 12:00:02.150   964  1056 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-05 12:00:02.168   964  1056 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-05 12:00:02.168   964  1056 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-05 12:00:02.169  1948  1948 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
07-05 12:00:02.208   964  1056 D SplitWindow: check instance of lgWin Window{233d1d8 u0 Starting com.test.thalitest}
07-05 12:00:02.254   964  1879 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5759 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 12:00:02.282  1948  1948 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
,07-05 12:00:02.344  1948  1948 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
07-05 12:00:02.366   964  2178 I WindowStateAnimator: Starting window displayed
07-05 12:00:02.374   964  1054 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
07-05 12:00:02.376   964  1054 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
07-05 12:00:02.380   964  1054 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
07-05 12:00:02.380   964  1054 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
07-05 12:00:02.380   964  1054 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 12:00:02.380   964  1054 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@fab6dbc,  pkg=WindowManager.LayoutParams
07-05 12:00:02.380   964  1054 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
07-05 12:00:02.385  1371  1371 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
07-05 12:00:02.387  1371  1371 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
07-05 12:00:02.387  1371  1371 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
07-05 12:00:02.387  1371  1371 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
07-05 12:00:02.408  2031  2031 I HotwordDetector: Closing mic
07-05 12:00:02.419  2031  2508 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@11bf3d17
07-05 12:00:02.419  2031  2508 V AudioRecord: stop()
07-05 12:00:02.419  2031  2508 D AudioRecord: AudioRecord->stop()
07-05 12:00:02.420   281   281 V AudioFlinger: RecordHandle::stop()
07-05 12:00:02.420   281   281 V AudioFlinger: RecordThread::stop
07-05 12:00:02.421   281   281 V AudioFlinger: Record stopped OK
07-05 12:00:02.423   281   281 V AudioPolicyManager: stopInput() input 17
07-05 12:00:02.425   281   281 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
07-05 12:00:02.425   281   281 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
07-05 12:00:02.425   281  1066 V AudioPolicyService: AudioCommandThread() waking up
07-05 12:00:02.425   281  1066 V AudioPolicyService: AudioCommandThread() processing release audio patch
07-05 12:00:02.425   281  1066 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
07-05 12:00:02.426   281  1066 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
07-05 12:00:02.426   281  1066 V AudioFlinger: ThreadBase::setParameters() routing=0
07-05 12:00:02.426   281  1066 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
07-05 12:00:02.426   281  2514 V AudioFlinger: processConfigEvents_l() remaining events 1
07-05 12:00:02.427   281  2514 V AudioFlinger: processConfigEvents_l() DONE thread 0xb43ad000
07-05 12:00:02.432   281  2514 D audio_hw_primary: in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
07-05 12:00:02.480   281  2514 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
07-05 12:00:02.480   281  2514 V audio_hw_primary: disable_audio_route: enter: usecase(7)
07-05 12:00:02.480   281  2514 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
07-05 12:00:02.480   281  2514 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-05 12:00:02.482   281  2514 V audio_hw_primary: disable_audio_route: exit
07-05 12:00:02.482   281  2514 E audio_hw_primary: disable_snd_device: enter 144
07-05 12:00:02.482   281  2514 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
07-05 12:00:02.482   281  2514 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
07-05 12:00:02.486   281  2514 V audio_hw_primary: stop_input_stream: exit: status(0)
07-05 12:00:02.486   281  2514 V audio_hw_primary: in_standby: exit:  status(0)
07-05 12:00:02.487   281  2514 V AudioFlinger: RecordThread: loop stopping
07-05 12:00:02.487   281  1066 V AudioPolicyService: AudioCommandThread() going to sleep
07-05 12:00:02.487   281   281 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
07-05 12:00:02.487   281   281 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
07-05 12:00:02.487   281   281 V AudioPolicyService: AudioCommandThread() adding update audio patch list
07-05 12:00:02.487   281   281 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
07-05 12:00:02.487   281  1067 V AudioPolicyService: AudioCommandThread() waking up
07-05 12:00:02.487   281  1067 V AudioPolicyService: AudioCommandThread() processing update audio patch list
07-05 12:00:02.488   281  1067 V AudioPolicyService: AudioCommandThread() going to sleep
07-05 12:00:02.489   281   281 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
07-05 12:00:02.489   281   281 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
07-05 12:00:02.489   281  1066 V AudioPolicyService: AudioCommandThread() waking up
07-05 12:00:02.489   281  1066 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
07-05 12:00:02.489   281  1066 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 281
07-05 12:00:02.489   281  1066 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
07-05 12:00:02.489   281  1066 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
07-05 12:00:02.489   281  2514 V AudioFlinger: RecordThread: loop starting
07-05 12:00:02.489   281  2514 V AudioFlinger: processConfigEvents_l() remaining events 1
07-05 12:00:02.489   281  2514 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
07-05 12:00:02.490   281  2514 V audio_hw_primary: in_set_parameters: exit: status(0)
07-05 12:00:02.490   281  2514 V AudioFlinger: processConfigEvents_l() DONE thread 0xb43ad000
07-05 12:00:02.490   281  2514 V AudioFlinger: RecordThread: loop stopping
07-05 12:00:02.490   281  1066 V AudioPolicyService: AudioCommandThread() going to sleep
07-05 12:00:02.493  2031  2508 V AudioRecord: stop()
07-05 12:00:02.494  2031  2508 V AudioRecord: stop()
07-05 12:00:02.494  2031  2508 V AudioRecord: stop()
07-05 12:00:02.494  5759  5759 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-05 12:00:02.497   281  1373 V AudioFlinger: RecordHandle::stop()
07-05 12:00:02.497   281  1373 V AudioFlinger: RecordThread::stop
07-05 12:00:02.497   281  1302 V AudioFlinger: releasing 16 from 2031 for -1
07-05 12:00:02.497   281  1373 V AudioPolicyManager: releaseInput() 17
07-05 12:00:02.497   281  1302 V AudioFlinger:  decremented refcount to 0
07-05 12:00:02.497   281  1302 V AudioFlinger: purging stale effects
07-05 12:00:02.497   281  1373 V AudioPolicyManager: closeInput(17)
07-05 12:00:02.497   281  1373 V AudioFlinger: closeInput() 17
07-05 12:00:02.497   281  1373 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 12:00:02.497   964   983 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 12:00:02.497   281  1373 V AudioFlinger: ThreadBase::exit
07-05 12:00:02.497  1371  2010 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 12:00:02.498  1770  1793 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 12:00:02.498   281  2514 V AudioFlinger: RecordThread: loop starting
07-05 12:00:02.498   281  2514 V AudioFlinger: RecordThread 0xb43ad000 exiting
07-05 12:00:02.498  2031  2046 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 12:00:02.499   281  1373 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb4036520)
07-05 12:00:02.499  2073  3074 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 12:00:02.499   281  1373 D audio_hw_primary: in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
07-05 12:00:02.499   281  1373 V audio_hw_primary: in_standby: exit:  status(0)
07-05 12:00:02.499  3115  3130 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 12:00:02.499  2056  2072 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 12:00:02.499   281  1373 V AudioPolicyService: AudioCommandThread() adding update audio port list
07-05 12:00:02.500   281  1373 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
07-05 12:00:02.500   281  1373 V AudioPolicyManager: releaseInput() exit
07-05 12:00:02.500   281  1067 V AudioPolicyService: AudioCommandThread() waking up
07-05 12:00:02.500   281  1067 V AudioPolicyService: AudioCommandThread() processing update audio port list
07-05 12:00:02.500   281  1373 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
07-05 12:00:02.500   281  1373 V AudioFlinger: removeClient_l() pid 2031, calling pid 281
07-05 12:00:02.500   281  1067 V AudioPolicyService: AudioCommandThread() going to sleep
07-05 12:00:02.503  2031  2510 I HotwordRecognitionRnr: Stopping hotword detection.
07-05 12:00:02.509  2031  2511 I HotwordRecognitionRnr: Hotword detection finished
07-05 12:00:02.633  5759  5759 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
07-05 12:00:02.704  5759  5759 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 1313-1323)
07-05 12:00:02.704  5759  5759 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:00:02.732  5759  5759 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3c8426b5}
07-05 12:00:02.733  5759  5759 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:00:02.738  5759  5759 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 12:00:02.756  5759  5759 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 12:00:02.758  5759  5759 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:00:02.768  5759  5759 E SysUtils: ApplicationContext is null in ApplicationStatus
07-05 12:00:02.837  5759  5796 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
07-05 12:00:02.864  5759  5759 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-05 12:00:02.873  5759  5759 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 12:00:02.873  5759  5759 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 12:00:02.876  5759  5759 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-05 12:00:02.876  5759  5759 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-05 12:00:02.876  5759  5759 I Adreno-EGL: Build Date: 03/02/15 Mon
07-05 12:00:02.876  5759  5759 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-05 12:00:02.876  5759  5759 I Adreno-EGL: Remote Branch: 
07-05 12:00:02.876  5759  5759 I Adreno-EGL: Local Patches: 
07-05 12:00:02.876  5759  5759 I Adreno-EGL: Reconstruct Branch: 
07-05 12:00:03.005   281   281 V AudioPolicyService: registerClient() client 0xb551c640, uid 10030
07-05 12:00:03.028   964  1055 D BluetoothManagerService: Message: 20
07-05 12:00:03.028   964  1055 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2aef46ab:true
07-05 12:00:03.049  2056  3319 D BluetoothAdapterService(232970427): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@24491d69
,07-05 12:00:03.181  5759  5759 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:00:03.195  5759  5759 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-05 12:00:03.205  5759  5759 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-05 12:00:03.208  5759  5759 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-05 12:00:03.208  5759  5759 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-05 12:00:03.224  5759  5759 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
07-05 12:00:03.233  5759  5759 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:00:03.233  5759  5759 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:00:03.302  5759  5759 I Activity: Activity.onPostResume() called 
07-05 12:00:03.309  5759  5821 D OpenGLRenderer: Render dirty regions requested: true
07-05 12:00:03.309  5759  5821 I OpenGLRenderer: Initialized EGL, version 1.4
07-05 12:00:03.315  5759  5821 D OpenGLRenderer: Enabling debug mode 0
07-05 12:00:03.333  5759  5759 D Atlas   : Validating map...
07-05 12:00:03.338   964   985 D SplitWindow: check instance of lgWin Window{833309b u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 12:00:03.350  5759  5805 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-05 12:00:03.383   964   985 D InputDispatcher: Focus entered window: Window{833309b u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 12:00:03.456   964  1298 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
07-05 12:00:03.472   964  1056 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s257ms
07-05 12:00:03.474   964  1056 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{284323f9 u0 com.test.thalitest/.MainActivity t241} time:152093
07-05 12:00:03.476  5759  5759 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2343c287 time:152097
07-05 12:00:03.611  5759  5759 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5759
07-05 12:00:03.824   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:00:03.824   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,07-05 12:00:03.824   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 152444867497; DSPS: 5093784; Offset : -3010937685
07-05 12:00:04.108   964  1058 I PowerManagerService: ALS enabled for SRE
07-05 12:00:04.108   964  1058 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (32729 ms ago)
,07-05 12:00:04.115   964  1058 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
07-05 12:00:04.119   964  1058 I PowerManagerService: ALS enabled for SRE
07-05 12:00:04.119   964  1058 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (32740 ms ago)
,07-05 12:00:04.125   964  1058 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
07-05 12:00:04.131   964  1058 I PowerManagerService: Sleeping (uid 1000)...
07-05 12:00:04.131   964  1058 D LPWGController: [updateScreenState] screen on = false
,07-05 12:00:04.133   964  1058 D LPWGController: disable proximity sensor
07-05 12:00:04.133   964  1058 D LPWGController: enable proximity sensor
07-05 12:00:04.139   964  1058 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@203c3e4] by com.android.server.power.ProximitySensorListener.enable():120
07-05 12:00:04.142   964  1058 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
07-05 12:00:04.142   964  1058 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
07-05 12:00:04.142   964  1058 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
07-05 12:00:04.142   964  1058 I sensors_hal_Ctx: activate: handle is 48, enable
07-05 12:00:04.142   964  1058 V sensors_hal_Ctx: activate sensors is 1400000000000
07-05 12:00:04.142   964  1058 D sensors_hal_Thresh: enable: handle=48
07-05 12:00:04.142   964  1058 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
07-05 12:00:04.142   964  1058 D sensors_hal_Util: waitForResponse: timeout=1000
07-05 12:00:04.146   964  1001 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
07-05 12:00:04.146   964  1001 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
07-05 12:00:04.146   964  1058 D sensors_hal_Thresh: enable: Received response: 0
07-05 12:00:04.146   964  1058 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (32767 ms ago)
,07-05 12:00:04.166   964  1058 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-05 12:00:04.166   964  1058 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-05 12:00:04.166   964  1058 I Adreno-EGL: Build Date: 03/02/15 Mon
07-05 12:00:04.166   964  1058 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-05 12:00:04.166   964  1058 I Adreno-EGL: Remote Branch: 
07-05 12:00:04.166   964  1058 I Adreno-EGL: Local Patches: 
07-05 12:00:04.166   964  1058 I Adreno-EGL: Reconstruct Branch: 
,07-05 12:00:04.186   247   270 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1105 us)
,07-05 12:00:04.350  5759  5759 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 12:00:04.374   416   945 I Sensors : sns_pwr.c(273):acquiring wakelock
07-05 12:00:04.374   964  1001 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,07-05 12:00:04.378   964  1001 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
07-05 12:00:04.378   964  1001 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
07-05 12:00:04.378   964  1001 D sensors_hal_Thresh: processInd: handle 48, count=1
07-05 12:00:04.379   964  1001 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
07-05 12:00:04.379   964  1001 I sensors_hal_Thresh: processInd : proximity state changed - FAR
07-05 12:00:04.379   964  1046 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
07-05 12:00:04.379   964  1046 D sensors_hal_Ctx: poll: count: 256
07-05 12:00:04.379   964  1046 I sensors_hal_Ctx: poll: released wakelock sensor_ind
07-05 12:00:04.379   964  1046 D sensors_hal_Util: waitForResponse: timeout=0
07-05 12:00:04.380   964  1058 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
07-05 12:00:04.382   964  1058 I LPWGController: current mode = 1  value = 1 1
07-05 12:00:04.383   964  1058 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
07-05 12:00:04.439  5759  5759 I chromium: [INFO:CONSOLE(90)] "Uncaught SyntaxError: Unexpected token function", source: file:///android_asset/www/js/thali_main.js (90)
,07-05 12:00:04.482   964  1058 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,07-05 12:00:04.507  5759  5824 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426135808
,07-05 12:00:04.524  5759  5824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 12:00:04.524  5759  5824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 12:00:04.524  5759  5824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 12:00:04.524  5759  5824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 12:00:04.524  5759  5824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-05 12:00:04.524  5759  5824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dabc38 added. We now have 1 listener(s)
07-05 12:00:04.527   964  1298 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-05 12:00:04.534  5759  5824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
07-05 12:00:04.536  5759  5824 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
,07-05 12:00:04.537  5759  5824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 12:00:04.538  5759  5824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-05 12:00:04.543  5759  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 12:00:04.543  5759  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 12:00:04.543  5759  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 12:00:04.543  5759  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
07-05 12:00:04.543  5759  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 12:00:04.543  5759  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 12:00:04.543  5759  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 12:00:04.543  5759  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 12:00:04.543  5759  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 12:00:04.543  5759  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 12:00:04.543  5759  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 12:00:04.543  5759  5824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5b77 added. We now have 1 listener(s)
07-05 12:00:04.544  5759  5824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-05 12:00:04.562  2056  2071 D BluetoothAdapterService(232970427): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@24491d69
,07-05 12:00:04.563  5759  5824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-05 12:00:04.571  5759  5824 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-05 12:00:04.571  5759  5824 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-05 12:00:04.574  5759  5824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-05 12:00:04.574   964  1878 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-05 12:00:04.575  5759  5824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
07-05 12:00:04.586  2056  2071 D BluetoothAdapterService(232970427): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@24491d69
,07-05 12:00:04.587  5759  5824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 12:00:04.587  5759  5824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 12:00:04.587  5759  5824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 12:00:04.587  5759  5824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-05 12:00:04.587  5759  5824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 12:00:04.587  5759  5824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 12:00:04.587  5759  5824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 12:00:04.587  5759  5824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-05 12:00:04.587  5759  5824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 12:00:04.587  5759  5824 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 12:00:04.588  5759  5824 I io.jxcore.node.LifeCycleMonitor: start: OK
07-05 12:00:04.612  5759  5759 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 12:00:04.719   964  1349 D qdlights: set_light_backlight: 0
,07-05 12:00:04.722   964  1058 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
07-05 12:00:04.722   964  1058 I sensors_hal_Ctx: activate: handle is 46, disable
07-05 12:00:04.722   964  1058 V sensors_hal_Ctx: activate sensors is 1000000000000
07-05 12:00:04.722   964  1058 D sensors_hal_LP2: enable: handle=46
07-05 12:00:04.723   964  1058 D sensors_hal_LP2: enable: Disabling sensor handle=46
07-05 12:00:04.723   964  1058 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
07-05 12:00:04.727   964  1056 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
07-05 12:00:04.727   964   964 V ActivityManager: Display changed displayId=0
07-05 12:00:04.733   247   247 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
07-05 12:00:04.733   247   247 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-05 12:00:04.753  1770  1770 D DSDPConnection: Display #0 changed.
,07-05 12:00:04.759  5759  5773 I art     : CheckpointMarkThreadRoots callback created = 0xb065b270
07-05 12:00:04.780   964  1027 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
07-05 12:00:04.780   964  1027 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,07-05 12:00:04.801  5759  5773 I art     : CheckpointMarkThreadRoots callback created = 0xb065b240
,07-05 12:00:04.917   247   247 D qdhwcomposer: hwc_blank: Done blanking display: 0
07-05 12:00:04.917   964  1349 D SurfaceControl: Excessive delay in setPowerMode(): 192ms
,07-05 12:00:04.918   247   672 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
07-05 12:00:04.918   964  1349 I QCOM PowerHAL: Got set_interactive hint
07-05 12:00:04.926  1371  1399 D KeyguardViewMediator: onScreenTurnedOff(3)
07-05 12:00:04.926  5759  5759 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-05 12:00:04.927  5759  5759 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-05 12:00:04.934  1332  1348 D SmartCoverViewMediator: onScreenTurnedOff(3)
07-05 12:00:04.937  1371  1399 D KeyguardViewMediator: notifyScreenOffLocked
07-05 12:00:04.944  1332  1348 D SmartCoverViewMediator: notifyScreenOffLocked
07-05 12:00:04.945  1332  1332 D SmartCoverViewMediator: handleNotifyScreenOFF
,07-05 12:00:04.958  5759  5759 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@95a433 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@12fd8278, 16908290=android.view.AbsSavedState$1@12fd8278}, android:focusedViewId=100}]}]
07-05 12:00:04.958  5759  5759 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-05 12:00:04.959  5759  5759 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-05 12:00:04.959  5759  5759 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-05 12:00:04.961  1371  1399 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
07-05 12:00:04.961  1371  1371 D KeyguardViewMediator: handleNotifyScreenOff
07-05 12:00:04.967  1371  1371 D ScreenTurnOffBySensor: unregisterProximitySensor
07-05 12:00:04.974  1371  1371 D StatusBarWindowView: onScreenTurnedOff why = 3
,07-05 12:00:05.000   964   964 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
,07-05 12:00:05.003   281  1302 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 964
07-05 12:00:05.003   281  1302 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-05 12:00:05.003   281  1302 V voice   : voice_set_parameters: enter: screen_state=on
07-05 12:00:05.003   281  1302 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
07-05 12:00:05.003   281  1302 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-05 12:00:05.003   281  1302 V voice   : voice_set_parameters: exit with code(0)
07-05 12:00:05.003   281  1302 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
07-05 12:00:05.003   281  1302 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-05 12:00:05.003   281  1302 V msm8974_platform: platform_set_parameters: exit with code(0)
07-05 12:00:05.003   281  1302 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-05 12:00:05.003   281  1302 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
07-05 12:00:05.003   281  1302 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
07-05 12:00:05.003   281  1302 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-05 12:00:05.006  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:00:05.009  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
07-05 12:00:05.012   964  1034 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
07-05 12:00:05.023   295   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:00:05.041   964  2011 D SplitWindow: check instance of lgWin Window{278c0368 u0 SearchPanel}
,07-05 12:00:05.049  1909  1909 I QCNEJ   : |CORE| sendScreenState: state:true
07-05 12:00:05.059   964  1878 D InputDispatcher: Window went away: Window{27ff99a4 u0 SearchPanel}
,07-05 12:00:05.062  1371  1371 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
07-05 12:00:05.080  1371  1371 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,07-05 12:00:05.085  1870  2048 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
07-05 12:00:05.085  1870  2048 D LEDService: stopPatternFlashing()
,07-05 12:00:05.086  1870  2048 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 12:00:05.088  1870  2048 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-05 12:00:05.088  1870  2048 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 12:00:05.089  1870  2048 I LEDService: updateLightsLocked : turn off led
07-05 12:00:05.089  1870  2048 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 12:00:05.090  1870  1870 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
07-05 12:00:05.090  1870  1870 D Cliptray Service: lockStatus = 0
07-05 12:00:05.092  1870  2048 D LEDHandler: RESTART MSG
,07-05 12:00:05.093  1840  1840 D LNfcService: action : android.intent.action.SCREEN_ON
07-05 12:00:05.098  1840  5850 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
07-05 12:00:05.099  1840  5850 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
07-05 12:00:05.099  1840  5850 D LNfcService: isRequireNfcCRouting() return true
07-05 12:00:05.099  1840  5850 D LNfcService: isHCERoutingtoHost() return : true
07-05 12:00:05.099  1840  5850 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
07-05 12:00:05.099  1840  5850 D NfcService: mEnableLPD: true
07-05 12:00:05.099  1840  5850 D NfcService: mEnableReader: false
07-05 12:00:05.099  1840  5850 D NfcService: mEnableHostRouting: true
07-05 12:00:05.100  1840  5850 D NfcService: newParams.techmask= mTechMask: default
07-05 12:00:05.100  1840  5850 D NfcService: mEnableLPD: true
07-05 12:00:05.100  1840  5850 D NfcService: mEnableReader: false
07-05 12:00:05.100  1840  5850 D NfcService: mEnableHostRouting: true
07-05 12:00:05.100  1840  5850 D NfcService: screenState= 3
07-05 12:00:05.100  1840  5850 D NfcService: Discovery configuration equal, not updating.
07-05 12:00:05.113   964   964 D Ulp_jni : JNI:system_update. Event-0
,07-05 12:00:05.137  1770  1770 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,07-05 12:00:05.161  2811  2811 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:0:5
,07-05 12:00:05.162  2811  2811 D WeatherService: 2 : ACTION screen on
07-05 12:00:05.164  2811  2811 D WeatherService: 2 : shouldTimeTickRegistered : false
07-05 12:00:05.169  2811  2811 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-05 12:00:05.169  2811  2811 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:0:5
07-05 12:00:05.177  3955  3955 D AppCleanupService: android.intent.action.SCREEN_ON
,07-05 12:00:05.205   281  1373 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 964
07-05 12:00:05.205   281  1373 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
07-05 12:00:05.205   281  1373 V voice   : voice_set_parameters: enter: screen_state=off
07-05 12:00:05.205   281  1373 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
07-05 12:00:05.205   281  1373 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-05 12:00:05.205   281  1373 V voice   : voice_set_parameters: exit with code(0)
07-05 12:00:05.205   281  1373 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
07-05 12:00:05.205   281  1373 V msm8974_platform: platform_set_parameters: enter: screen_state=off
07-05 12:00:05.205   281  1373 V msm8974_platform: platform_set_parameters: exit with code(0)
07-05 12:00:05.205   281  1373 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-05 12:00:05.205   281  1373 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
07-05 12:00:05.205   281  1373 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-05 12:00:05.207   964  1316 D WifiController: CMD_SCREEN_OFF 
07-05 12:00:05.207   964  1316 D WifiController: shouldWifiStayAwake TRUE
07-05 12:00:05.212  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
,07-05 12:00:05.214   964  1034 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
07-05 12:00:05.220  1909  1909 I QCNEJ   : |CORE| sendScreenState: state:false
07-05 12:00:05.221  1870  2048 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
07-05 12:00:05.221  1870  2048 D LEDService: stopPatternFlashing()
07-05 12:00:05.221  1870  2048 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 12:00:05.222  1870  2048 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-05 12:00:05.223  1870  2048 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 12:00:05.224  1870  1870 D VolumeVibrator: clear
,07-05 12:00:05.225  1870  2048 I LEDService: updateLightsLocked : turn on led
07-05 12:00:05.225  1870  2048 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
07-05 12:00:05.226  1870  2048 E LEDService: Can't handle this request of patternId:0
07-05 12:00:05.226  1870  2048 D LEDHandler: RESTART MSG
07-05 12:00:05.226  1870  1870 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
07-05 12:00:05.227  1840  1840 D LNfcService: action : android.intent.action.SCREEN_OFF
07-05 12:00:05.230  1840  2201 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
07-05 12:00:05.239  1948  1948 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,07-05 12:00:05.251  1770  1770 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
07-05 12:00:05.256  2811  2811 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:0:5
07-05 12:00:05.256  2811  2811 D WeatherService: 2 : ACTION screen off
07-05 12:00:05.257  2811  2811 D WeatherService: 2 : TimeTick Receiver Unregister
07-05 12:00:05.257  2811  2811 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:0:5
,07-05 12:00:05.260  3955  3955 D AppCleanupService: android.intent.action.SCREEN_OFF
07-05 12:00:05.264  3955  5853 D AppCleanupService: AppUsageStatsSaveTask
07-05 12:00:05.326  1840  2604 E NxpNfcJni: getReconnectState = 0x0
,07-05 12:00:05.328  1840  2201 D LCardEmulationManager: getHceAppCount hostAppNum : 0
07-05 12:00:05.329  1840  2201 D LCardEmulationManager: getDefaultRoute
07-05 12:00:05.329  1840  2201 D LNfcService: isRequireNfcCRouting() return true
07-05 12:00:05.329  1840  2201 D LNfcService: isHCERoutingtoHost() return : true
07-05 12:00:05.329  1840  2201 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
07-05 12:00:05.329  1840  2201 D NfcService: mEnableLPD: true
07-05 12:00:05.329  1840  2201 D NfcService: mEnableReader: false
07-05 12:00:05.329  1840  2201 D NfcService: mEnableHostRouting: true
07-05 12:00:05.329  1840  2201 D NfcService: newParams.techmask= mTechMask: 0
07-05 12:00:05.329  1840  2201 D NfcService: mEnableLPD: true
07-05 12:00:05.329  1840  2201 D NfcService: mEnableReader: false
07-05 12:00:05.329  1840  2201 D NfcService: mEnableHostRouting: true
07-05 12:00:05.329  1840  2201 D NfcService: screenState= 1
07-05 12:00:05.352  1840  2604 E NxpNfcJni: getReconnectState = 0x0
,07-05 12:00:05.416  5759  5849 W jxcore-log: Initializing JXcore engine
07-05 12:00:05.416  5759  5849 W jxcore-log: JXcore engine is ready
,07-05 12:00:05.472  5849  5849 W Thread-664: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5525]" dev="sockfs" ino=5525 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-05 12:00:05.472  5849  5849 W Thread-664: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-05 12:00:05.472  5849  5849 W Thread-664: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5690]" dev="sockfs" ino=5690 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-05 12:00:05.472  5849  5849 W Thread-664: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
07-05 12:00:05.472  5849  5849 W Thread-664: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
07-05 12:00:05.472  5849  5849 W Thread-664: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[27161]" dev="sockfs" ino=27161 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-05 12:00:05.501  5759  5849 W jxcore-log: Starting JXcore engine
,07-05 12:00:05.630  5759  5849 W jxcore-log: Platform android
07-05 12:00:05.630  5759  5849 W jxcore-log: 
07-05 12:00:05.630  5759  5849 W jxcore-log: Process ARCH arm
07-05 12:00:05.630  5759  5849 W jxcore-log: 
,07-05 12:00:05.874   416   432 I Sensors : sns_pwr.c(301):releasing wakelock
,07-05 12:00:05.892  5759  5849 I jxcore-log: JXcore Cordova bridge is ready!
07-05 12:00:05.892  5759  5849 I jxcore-log: 
,07-05 12:00:05.892  5759  5849 W jxcore-log: JXcore engine is started
07-05 12:00:09.948  1371  1371 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,07-05 12:00:09.953   964  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{a175381 type 2 when 158561 com.android.systemui} when 158561
,07-05 12:00:09.969  1770  2330 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
07-05 12:00:09.973  1770  2330 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-05 12:00:09.973  1770  2330 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-05 12:00:09.978  1770  2330 V TelecomServiceImpl: getCallState : 0
,07-05 12:00:09.982  1770  1793 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
07-05 12:00:09.982  1770  1793 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-05 12:00:09.982  1770  1793 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-05 12:00:09.983  1371  1371 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
07-05 12:00:09.985  1371  1371 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
07-05 12:00:10.027   295   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:00:13.592  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,07-05 12:00:13.594  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:00:13.595  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:00:13.595  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:00:13.596  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:00:13.610   471   471 D charger_monitor: init target 500000
,07-05 12:00:13.615   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:00:13.648  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:00:13.651  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:00:13.651  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:00:13.653  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:00:13.653  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:00:13.653  1870  2048 D LEDHandler: Battery Temp: 307, mChargingStatus=5, mChargingStop=false
07-05 12:00:13.654  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 307
07-05 12:00:13.654  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:00:13.655  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 307
07-05 12:00:13.657  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:00:13.660   964  1316 D WifiController: battery changed pluggedType: 2
,07-05 12:00:13.663  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:00:13.704  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:00:13.707  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 307
07-05 12:00:13.707  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:00:13.707  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 307
07-05 12:00:13.708  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:00:13.709  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:00:13.710  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:00:13.710  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:00:13.710  1870  2048 D LEDHandler: Battery Temp: 307, mChargingStatus=5, mChargingStop=false
07-05 12:00:13.712  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:00:13.714   964  1316 D WifiController: battery changed pluggedType: 2
07-05 12:00:13.715  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:00:15.033   295   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:00:20.039   295   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:00:20.672   964  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3e260c26 type 2 when 169284 com.google.android.gms} when 169284
,07-05 12:00:20.693  2353  5861 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:00:20.693  2353  5861 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:00:20.693  2353  5861 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:00:20.693  2353  5861 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-05 12:00:20.698   277  1040 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:00:20.699   277  1040 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:00:20.700   277  5863 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 12:00:20.700   277  5863 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:00:20.701   277  5863 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 12:00:20.703   964  1053 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,07-05 12:00:20.922  2353  4758 I art     : Explicit concurrent mark sweep GC freed 51922(2MB) AllocSpace objects, 15(240KB) LOS objects, 40% free, 14MB/23MB, paused 2.138ms total 152.059ms
,07-05 12:00:23.826   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:00:23.826   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:00:23.826   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 172446351292; DSPS: 5749192; Offset : -3010918499
,07-05 12:00:25.044   295   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:00:27.149  2353  4214 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 12:00:30.050   295   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:00:31.135   964  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{33d6c4b2 type 2 when 179744 com.google.android.gms} when 179744
,07-05 12:00:31.139   964  1748 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:00:31.139   964  1748 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:00:31.142   964  1748 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:00:31.142   964  1748 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:00:31.143   277  1040 E BandwidthController: [LG DATA] No such appUid: 1000
07-05 12:00:31.144   277  1040 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-05 12:00:31.147   277  5882 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 12:00:31.147   277  5882 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:00:31.148   277  5882 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
,07-05 12:00:31.151   964  1053 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-05 12:00:35.056   295   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:00:35.270   964  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{160c2c03 type 2 when 183881 com.google.android.gms} when 183881
,07-05 12:00:38.645   471   471 D charger_monitor: init target 500000
,07-05 12:00:38.650   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:00:38.658  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:00:38.658  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:00:38.659  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:00:38.659  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 12:00:38.661  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:00:38.701  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:00:38.701  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,07-05 12:00:38.704  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:00:38.704  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:00:38.704  1870  2048 D LEDHandler: Battery Temp: 307, mChargingStatus=5, mChargingStop=false
07-05 12:00:38.705  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 307
07-05 12:00:38.705  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:00:38.705  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 307
07-05 12:00:38.707  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:00:38.708  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:00:38.711   964  1316 D WifiController: battery changed pluggedType: 2
07-05 12:00:38.711  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:00:40.062   295   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:00:43.827   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:00:43.827   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:00:43.827   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 192447834044; DSPS: 6404601; Offset : -3010931186
,07-05 12:00:45.068   295   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:00:50.074   295   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:00:53.939  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,07-05 12:00:53.941  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:00:53.941  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:00:53.941  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:00:53.941  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:00:53.974   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 12:00:54.007  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,07-05 12:00:54.008  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:00:54.008  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:00:54.012  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:00:54.012  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:00:54.014   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:00:54.059  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:00:54.059  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,07-05 12:00:54.062  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 307
07-05 12:00:54.062  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:00:54.066  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:00:54.066  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:00:54.066  1870  2048 D LEDHandler: Battery Temp: 307, mChargingStatus=5, mChargingStop=false
07-05 12:00:54.067  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:00:54.067  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 307
07-05 12:00:54.069  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:00:54.072   964  1316 D WifiController: battery changed pluggedType: 2
,07-05 12:00:54.076  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:00:54.129  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:00:54.132  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 307
07-05 12:00:54.132  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:00:54.132  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 307
07-05 12:00:54.133  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:00:54.133  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:00:54.134  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:00:54.134  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:00:54.134  1870  2048 D LEDHandler: Battery Temp: 307, mChargingStatus=5, mChargingStop=false
07-05 12:00:54.137  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:00:54.139   964  1316 D WifiController: battery changed pluggedType: 2
07-05 12:00:54.140  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:00:55.080   295   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:00:56.019  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,07-05 12:00:56.021  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:00:56.021  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:00:56.021  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:00:56.021   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:00:56.022  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:00:56.061  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:00:56.064  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 306
07-05 12:00:56.065  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:00:56.065  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 306
07-05 12:00:56.066  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:00:56.066  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:00:56.067  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:00:56.067  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:00:56.067  1870  2048 D LEDHandler: Battery Temp: 306, mChargingStatus=5, mChargingStop=false
07-05 12:00:56.070  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:00:56.072   964  1316 D WifiController: battery changed pluggedType: 2
07-05 12:00:56.072  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:01:00.043  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:01:00.043  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:01:00.043  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:01:00.047  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:01:00.048  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:01:00.048  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:01:00.050  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:01:00.086   295   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:01:01.146   964  1287 D PowerManagerServiceEx: acquireWakeLockInternal: lock=573145046, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,07-05 12:01:01.159   964  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{25e9d780 type 2 when 209760 com.google.android.gms} when 209760
,07-05 12:01:01.175   964   964 D PowerManagerServiceEx: releaseWakeLockInternal: lock=573145046 [*alarm*], flags=0x0
,07-05 12:01:01.771  2353  2353 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=fdaac833-3e6a-4075-82dc-bc4b12445280
,07-05 12:01:01.792  2353  2353 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:01:01.793  2353  2353 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:01:01.893  2353  2688 W GCoreFlp: No location to return for getLastLocation()
,07-05 12:01:01.941  5409  5902 D UdcContextInitService: registered all accounts: true
,07-05 12:01:01.974  5409  5902 I GAv4-SVC: Google Analytics 9.2.56 is starting up.
,07-05 12:01:02.119   964  2178 I art     : Explicit concurrent mark sweep GC freed 48786(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/34MB, paused 2.269ms total 170.469ms
,07-05 12:01:02.120  2353  2662 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-05 12:01:02.137  2353  2624 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-05 12:01:02.197  2353  2624 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-05 12:01:02.236  2353  2624 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,07-05 12:01:03.829   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:01:03.829   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,07-05 12:01:03.829   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 212449497475; DSPS: 7060015; Offset : -3010917215
07-05 12:01:04.258  2353  2624 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-05 12:01:04.260  2353  2624 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
07-05 12:01:04.337   964  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{d871f3f type 2 when 212951 android} when 212951
,07-05 12:01:05.092   295   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:01:10.098   295   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:01:15.103   295   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:01:20.109   295   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:01:23.831   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:01:23.831   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:01:23.831   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 232451785071; DSPS: 7715451; Offset : -3010947394
,07-05 12:01:25.115   295   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:01:30.121   295   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:01:35.128   295   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:01:38.813  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:01:38.813  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:01:38.813  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:01:38.813  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 12:01:38.816  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:01:38.817   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:01:38.866  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:01:38.870  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:01:38.870  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:01:38.871  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:01:38.871  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:01:38.871  1870  2048 D LEDHandler: Battery Temp: 305, mChargingStatus=5, mChargingStop=false
07-05 12:01:38.872  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 305
07-05 12:01:38.872  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:01:38.872  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 305
07-05 12:01:38.875  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:01:38.878   964  1316 D WifiController: battery changed pluggedType: 2
,07-05 12:01:38.882  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:01:40.134   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:01:43.832   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:01:43.832   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:01:43.832   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 252452506053; DSPS: 8370834; Offset : -3010928211
,07-05 12:01:45.139   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:01:50.145   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:01:55.151   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:02:00.045  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:02:00.045  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:02:00.045  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:02:00.048  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:02:00.048  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:02:00.050  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:02:00.050  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:02:00.156   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:02:03.834   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:02:03.834   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:02:03.834   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 272454784796; DSPS: 9026269; Offset : -3010938313
,07-05 12:02:05.162   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:02:10.171   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:02:10.791   964  1748 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:02:10.792   964  1748 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:02:10.792   964  1748 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:02:10.792   964  1748 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-05 12:02:10.801   964  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{17c7b00c type 2 when 279403 com.google.android.gms} when 279403
07-05 12:02:10.802   277  1040 E BandwidthController: [LG DATA] No such appUid: 1000
07-05 12:02:10.802   277  1040 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-05 12:02:10.806   277  5946 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 12:02:10.806   277  5946 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:02:10.806   277  5946 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
,07-05 12:02:10.809   964  1053 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-05 12:02:10.817  2353  5945 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:02:10.817  2353  5945 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:02:10.818  2353  5945 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:02:10.818  2353  5945 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:02:10.818   277  1040 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:02:10.818   277  1040 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,07-05 12:02:10.825   277  5947 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 12:02:10.826   277  5947 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:02:10.826   277  5947 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 12:02:10.827   964  1053 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,07-05 12:02:15.177   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:02:20.182   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:02:23.836   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:02:23.837   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:02:23.837   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 292457059579; DSPS: 9681703; Offset : -3010921857
,07-05 12:02:25.188   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:02:30.194   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:02:35.200   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:02:38.969   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 12:02:38.971  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:02:38.974  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:02:38.974  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:02:38.974  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:02:38.975  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:02:39.010  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:02:39.013  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:02:39.014  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:02:39.014  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:02:39.014  1870  2048 D LEDHandler: Battery Temp: 303, mChargingStatus=5, mChargingStop=false
07-05 12:02:39.015  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 303
07-05 12:02:39.015  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:02:39.015  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 303
07-05 12:02:39.018  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:02:39.019  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:02:39.023   964  1316 D WifiController: battery changed pluggedType: 2
,07-05 12:02:39.027  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:02:40.205   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:02:43.839   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:02:43.839   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:02:43.839   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 312459470249; DSPS: 10337142; Offset : -3010921892
,07-05 12:02:45.211   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:02:50.217   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:02:55.222   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:03:00.039  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:03:00.040  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:03:00.040  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:03:00.043  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:03:00.043  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:03:00.044  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:03:00.045  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:03:00.229   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:03:03.841   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:03:03.841   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:03:03.841   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 332461753836; DSPS: 10992577; Offset : -3010929312
,07-05 12:03:05.235   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:03:10.241   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:03:13.661   964  3190 I LocationManagerService: remove 1eddf31e
,07-05 12:03:13.666   964  3190 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
07-05 12:03:13.666   964  3190 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-05 12:03:13.666   964  3190 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-05 12:03:13.667   964  3190 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
07-05 12:03:13.667   964  3190 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,07-05 12:03:15.247   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:03:20.253   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:03:23.843   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:03:23.843   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:03:23.843   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 352463651172; DSPS: 11647999; Offset : -3010922113
,07-05 12:03:25.259   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:03:30.265   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:03:35.270   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:03:36.534  2353  2353 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:03:36.550  2353  2353 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:03:36.553  2353  2353 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:03:36.598   964   985 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:03:36.626  4895  4932 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:03:36.626  4895  4932 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:03:36.628  4895  4932 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:03:36.629  4895  4932 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:03:36.629   277  1040 E BandwidthController: [LG DATA] No such appUid: 10036
07-05 12:03:36.629   277  1040 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
07-05 12:03:36.629   277  5967 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 12:03:36.630   277  5967 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:03:36.630   277  5967 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 12:03:36.631   964  1053 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-05 12:03:39.138   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 12:03:39.141  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:03:39.147  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:03:39.148  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:03:39.148  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:03:39.148  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:03:39.185  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:03:39.190  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:03:39.190  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:03:39.190  1870  2048 D LEDHandler: Battery Temp: 301, mChargingStatus=5, mChargingStop=false
07-05 12:03:39.190  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:03:39.190  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:03:39.191  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 301
07-05 12:03:39.191  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:03:39.192  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 301
07-05 12:03:39.194  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:03:39.198   964  1316 D WifiController: battery changed pluggedType: 2
,07-05 12:03:39.201  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:03:40.276   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:03:43.845   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:03:43.845   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:03:43.845   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 372465925851; DSPS: 12303434; Offset : -3010936303
,07-05 12:03:45.282   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:03:50.287   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:03:55.293   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:04:00.039  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:04:00.040  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:04:00.040  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:04:00.043  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:04:00.043  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:04:00.044  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:04:00.045  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:04:00.299   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:04:03.848   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:04:03.848   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:04:03.848   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 392468194594; DSPS: 12958868; Offset : -3010925757
,07-05 12:04:05.305   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:04:10.310   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:04:15.317   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:04:20.323   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:04:23.850   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:04:23.850   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:04:23.850   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 412470470002; DSPS: 13614303; Offset : -3010939245
,07-05 12:04:25.329   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:04:30.335   295   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:04:35.341   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:04:39.290   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 12:04:39.292  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:04:39.299  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:04:39.299  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:04:39.299  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:04:39.299  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:04:39.337  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:04:39.341  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:04:39.341  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:04:39.342  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:04:39.342  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:04:39.342  1870  2048 D LEDHandler: Battery Temp: 300, mChargingStatus=5, mChargingStop=false
07-05 12:04:39.343  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
07-05 12:04:39.343  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:04:39.343  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
07-05 12:04:39.346  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:04:39.350   964  1316 D WifiController: battery changed pluggedType: 2
,07-05 12:04:39.354  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:04:40.347   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:04:43.852   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:04:43.852   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:04:43.852   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 432472744423; DSPS: 14269737; Offset : -3010923126
,07-05 12:04:45.353   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:04:50.359   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:04:55.364   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:05:00.039  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:05:00.039  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:05:00.039  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:05:00.043  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:05:00.043  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:05:00.044  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:05:00.044  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:05:00.371   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:05:03.854   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:05:03.854   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:05:03.855   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 452475024466; DSPS: 14925172; Offset : -3010931876
,07-05 12:05:05.376   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:05:10.382   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:05:15.388   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:05:20.393   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:05:23.857   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:05:23.857   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:05:23.857   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 472477398521; DSPS: 15580610; Offset : -3010938114
,07-05 12:05:25.399   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:05:30.405   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:05:35.411   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:05:39.454   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 12:05:39.462  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:05:39.463  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:05:39.464  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:05:39.464  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:05:39.464  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:05:39.501  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:05:39.501  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,07-05 12:05:39.504  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 299
07-05 12:05:39.504  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:05:39.505  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 299
07-05 12:05:39.508  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:05:39.508  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:05:39.508  1870  2048 D LEDHandler: Battery Temp: 299, mChargingStatus=5, mChargingStop=false
07-05 12:05:39.509  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:05:39.513   964  1316 D WifiController: battery changed pluggedType: 2
,07-05 12:05:39.516  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:05:39.517  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:05:40.417   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:05:43.859   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:05:43.859   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:05:43.859   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 492479665805; DSPS: 16236044; Offset : -3010929286
,07-05 12:05:45.423   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:05:50.429   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:05:50.990   964  1287 D PowerManagerServiceEx: acquireWakeLockInternal: lock=573145046, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,07-05 12:05:50.999   964  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{7f28fd3 type 2 when 499604 com.google.android.gms} when 499604
07-05 12:05:51.016   964   964 D PowerManagerServiceEx: releaseWakeLockInternal: lock=573145046 [*alarm*], flags=0x0
,07-05 12:05:51.021  2353  5994 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:05:51.021  2353  5994 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:05:51.021  2353  5994 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:05:51.021  2353  5994 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:05:51.022   277  1040 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:05:51.022   277  1040 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:05:51.025   277  5996 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 12:05:51.025   277  5996 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:05:51.027   277  5996 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 12:05:51.028   964  1053 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,07-05 12:05:55.435   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:06:00.039  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:06:00.039  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:06:00.039  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:06:00.043  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:06:00.044  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:06:00.044  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:06:00.045  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:06:00.441   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:06:03.861   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:06:03.861   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:06:03.862   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 512481981527; DSPS: 16891480; Offset : -3010932951
,07-05 12:06:05.447   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:06:10.452   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:06:15.458   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:06:20.464   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:06:23.864   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:06:23.864   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:06:23.864   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 532484261363; DSPS: 17546915; Offset : -3010941830
,07-05 12:06:25.470   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:06:30.476   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:06:35.482   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:06:39.611  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:06:39.611  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:06:39.611  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:06:39.611  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 12:06:39.613   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:06:39.619  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:06:39.659  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:06:39.662  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:06:39.662  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:06:39.664  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:06:39.664  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:06:39.664  1870  2048 D LEDHandler: Battery Temp: 298, mChargingStatus=5, mChargingStop=false
07-05 12:06:39.665  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
07-05 12:06:39.666  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:06:39.666  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
07-05 12:06:39.668  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:06:39.673   964  1316 D WifiController: battery changed pluggedType: 2
,07-05 12:06:39.676  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:06:40.488   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:06:43.866   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:06:43.866   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:06:43.866   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 552486540157; DSPS: 18202349; Offset : -3010921259
,07-05 12:06:45.494   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:06:50.500   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:06:55.506   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:07:00.043  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:07:00.044  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:07:00.044  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:07:00.047  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:07:00.047  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:07:00.048  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:07:00.049  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:07:00.512   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:07:03.867   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:07:03.868   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:07:03.868   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 572488052597; DSPS: 18857759; Offset : -3010934827
,07-05 12:07:05.518   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:07:10.524   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:07:15.530   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:07:20.536   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:07:23.870   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:07:23.870   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:07:23.870   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 592490653059; DSPS: 19513204; Offset : -3010928074
,07-05 12:07:25.542   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:07:30.548   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:07:35.554   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:07:39.769   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 12:07:39.772  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:07:39.772  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:07:39.772  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:07:39.772  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:07:39.773  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:07:39.814  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:07:39.817  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:07:39.817  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:07:39.818  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:07:39.818  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:07:39.818  1870  2048 D LEDHandler: Battery Temp: 297, mChargingStatus=5, mChargingStop=false
07-05 12:07:39.820  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
07-05 12:07:39.821  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:07:39.821  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
07-05 12:07:39.823  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:07:39.827   964  1316 D WifiController: battery changed pluggedType: 2
,07-05 12:07:39.831  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:07:40.560   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:07:43.872   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:07:43.872   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:07:43.872   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 612492272478; DSPS: 20168617; Offset : -3010926528
,07-05 12:07:45.565   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:07:50.571   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:07:53.572   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 12:07:53.575  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:07:53.576  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:07:53.578  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:07:53.578  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:07:53.579  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:07:53.641  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:07:53.641  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,07-05 12:07:53.644  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
07-05 12:07:53.644  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:07:53.645  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
07-05 12:07:53.646  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:07:53.646  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:07:53.646  1870  2048 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
07-05 12:07:53.647  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:07:53.648  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:07:53.652   964  1316 D WifiController: battery changed pluggedType: 2
07-05 12:07:53.654  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-05 12:07:55.578   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:08:00.041  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:08:00.041  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:08:00.041  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:08:00.045  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:08:00.045  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:08:00.045  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:08:00.046  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:08:00.584   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:08:03.873   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:08:03.873   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:08:03.873   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 632493890961; DSPS: 20824030; Offset : -3010925217
,07-05 12:08:05.590   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:08:10.596   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:08:15.602   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:08:20.607   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:08:23.875   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:08:23.875   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:08:23.875   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 652495679754; DSPS: 21479449; Offset : -3010936987
,07-05 12:08:25.614   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:08:30.620   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:08:35.626   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:08:36.674  2353  2353 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:08:36.688  2353  2353 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:08:36.691  2353  2353 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:08:36.733   964  1380 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:08:36.740  4895  4932 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:08:36.741  4895  4932 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:08:36.741  4895  4932 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:08:36.741  4895  4932 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:08:36.742   277  1040 E BandwidthController: [LG DATA] No such appUid: 10036
07-05 12:08:36.742   277  1040 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
07-05 12:08:36.749   277  6028 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 12:08:36.749   277  6028 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:08:36.750   277  6028 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
,07-05 12:08:36.753   964  1053 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-05 12:08:39.930   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 12:08:39.932  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:08:39.939  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:08:39.939  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:08:39.939  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:08:39.939  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:08:40.632   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:08:43.877   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:08:43.878   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:08:43.878   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 672498063757; DSPS: 22134887; Offset : -3010933642
,07-05 12:08:45.638   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:08:50.644   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:08:55.650   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:09:00.042  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:09:00.042  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:09:00.042  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:09:00.046  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:09:00.046  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:09:00.047  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:09:00.048  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:09:00.637   964  1287 D PowerManagerServiceEx: acquireWakeLockInternal: lock=573145046, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,07-05 12:09:00.645   964  1287 V AlarmManager: RTC_WAKEUP set : Alarm{36574ee6 type 0 when 1467713340635 com.google.android.gms} when 1467713340635
07-05 12:09:00.655   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:09:00.821   964   964 D PowerManagerServiceEx: releaseWakeLockInternal: lock=573145046 [*alarm*], flags=0x0
,07-05 12:09:00.880  5409  6046 I EventLogChimeraService: Aggregate from 1467711540541 (log), 1467711540541 (data)
,07-05 12:09:01.162  5409  6048 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-05 12:09:01.197  5409  6048 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-05 12:09:03.880   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:09:03.880   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:09:03.880   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 692500774949; DSPS: 22790336; Offset : -3010937967
,07-05 12:09:05.659   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:09:10.665   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:09:15.673   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:09:20.679   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:09:23.881   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:09:23.881   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:09:23.881   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 712501709524; DSPS: 23445726; Offset : -3010919050
,07-05 12:09:25.685   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:09:30.691   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:09:35.697   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:09:40.089   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 12:09:40.093  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:09:40.093  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:09:40.093  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:09:40.093  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:09:40.093  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:09:40.136  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:09:40.139  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
07-05 12:09:40.139  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:09:40.139  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
07-05 12:09:40.141  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:09:40.141  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:09:40.142  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:09:40.142  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:09:40.142  1870  2048 D LEDHandler: Battery Temp: 295, mChargingStatus=5, mChargingStop=false
07-05 12:09:40.144  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:09:40.148   964  1316 D WifiController: battery changed pluggedType: 2
,07-05 12:09:40.152  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:09:40.702   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:09:43.883   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:09:43.883   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:09:43.883   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 732503307745; DSPS: 24101139; Offset : -3010938547
,07-05 12:09:45.708   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:09:50.714   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:09:55.720   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:10:00.042  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:10:00.042  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:10:00.042  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:10:00.046  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:10:00.046  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:10:00.047  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:10:00.047  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:10:00.726   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:10:03.885   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:10:03.885   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:10:03.885   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 752505573467; DSPS: 24756573; Offset : -3010930943
,07-05 12:10:05.731   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:10:10.738   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:10:15.744   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:10:20.750   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:10:23.887   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:10:23.887   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:10:23.887   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 772507947990; DSPS: 25412011; Offset : -3010936817
,07-05 12:10:25.756   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:10:30.762   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:10:35.768   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:10:40.250  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:10:40.250  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:10:40.250  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:10:40.250  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 12:10:40.254   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:10:40.254  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:10:40.295  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:10:40.298  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:10:40.298  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:10:40.300  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:10:40.300  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:10:40.300  1870  2048 D LEDHandler: Battery Temp: 295, mChargingStatus=5, mChargingStop=false
07-05 12:10:40.300  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
07-05 12:10:40.301  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:10:40.301  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
07-05 12:10:40.303  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:10:40.308   964  1316 D WifiController: battery changed pluggedType: 2
,07-05 12:10:40.311  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:10:40.775   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:10:43.888   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:10:43.888   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:10:43.888   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 792508881263; DSPS: 26067401; Offset : -3010918968
,07-05 12:10:45.781   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:10:50.787   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:10:55.793   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:11:00.042  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:11:00.042  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:11:00.043  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:11:00.046  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:11:00.046  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:11:00.047  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:11:00.048  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:11:00.798   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:11:03.891   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:11:03.891   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:11:03.891   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 812511152662; DSPS: 26722836; Offset : -3010936544
,07-05 12:11:05.805   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:11:10.810   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:11:15.816   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:11:20.822   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:11:23.892   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:11:23.892   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:11:23.892   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 832512662759; DSPS: 27378245; Offset : -3010921677
,07-05 12:11:25.829   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:11:30.835   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:11:35.841   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:11:40.412  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,07-05 12:11:40.415  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:11:40.416  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:11:40.416  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:11:40.416  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:11:40.417   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:11:40.846   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:11:43.894   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:11:43.894   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:11:43.895   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 852514982127; DSPS: 28033681; Offset : -3010921853
,07-05 12:11:45.852   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:11:50.859   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:11:55.864   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:12:00.039  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:12:00.039  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:12:00.039  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:12:00.043  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:12:00.043  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:12:00.044  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:12:00.045  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:12:00.870   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:12:03.896   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:12:03.896   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:12:03.896   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 872516488733; DSPS: 28689091; Offset : -3010940892
,07-05 12:12:05.875   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:12:10.882   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:12:15.888   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:12:20.893   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:12:23.898   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:12:23.898   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:12:23.898   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 892518868934; DSPS: 29344529; Offset : -3010941557
,07-05 12:12:25.899   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:12:30.905   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:12:35.910   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:12:40.570   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 12:12:40.578  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:12:40.579  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:12:40.579  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:12:40.580  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:12:40.580  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:12:40.616  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:12:40.620  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:12:40.620  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:12:40.621  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:12:40.621  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:12:40.621  1870  2048 D LEDHandler: Battery Temp: 294, mChargingStatus=5, mChargingStop=false
07-05 12:12:40.622  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
07-05 12:12:40.622  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:12:40.622  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
07-05 12:12:40.625  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:12:40.629   964  1316 D WifiController: battery changed pluggedType: 2
,07-05 12:12:40.633  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:12:40.916   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:12:43.901   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:12:43.901   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:12:43.901   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 912521702832; DSPS: 29999982; Offset : -3010945429
,07-05 12:12:45.923   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:12:50.929   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:12:55.935   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:13:00.040  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:13:00.040  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:13:00.040  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:13:00.044  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:13:00.044  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:13:00.044  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:13:00.045  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:13:00.940   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:13:03.904   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:13:03.904   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:13:03.904   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 932524087982; DSPS: 30655420; Offset : -3010940858
,07-05 12:13:05.947   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:13:10.952   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:13:11.354   964  1287 D PowerManagerServiceEx: acquireWakeLockInternal: lock=573145046, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,07-05 12:13:11.362   964  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{16fffeca type 2 when 939968 com.google.android.gms} when 939968
07-05 12:13:11.378   964   964 D PowerManagerServiceEx: releaseWakeLockInternal: lock=573145046 [*alarm*], flags=0x0
,07-05 12:13:11.391  2353  6103 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:13:11.392  2353  6103 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:13:11.392  2353  6103 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:13:11.392  2353  6103 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-05 12:13:11.395   277  1040 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:13:11.395   277  1040 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:13:11.397   277  6104 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 12:13:11.397   277  6104 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:13:11.399   277  6104 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 12:13:11.400   964  1053 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,07-05 12:13:15.958   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:13:16.979   964  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{24dd383b type 2 when 945590 com.android.bluetooth} when 945590
,07-05 12:13:17.018  2056  3419 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
07-05 12:13:17.018  2056  3419 W bt-smp  : Plain text(LSB ~ MSB) = bc 73 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
,07-05 12:13:17.020  2056  3419 W bt-smp  : Encrypted text(LSB ~ MSB) = cc 97 8d a9 f9 d6 db b5 f3 bb 59 e9 80 72 68 5c 
07-05 12:13:17.021  2056  3419 W bt-btm  : Stopping oneshot timer
07-05 12:13:20.963   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:13:23.906   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:13:23.906   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:13:23.906   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 952526363077; DSPS: 31310854; Offset : -3010923778
,07-05 12:13:25.969   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:13:30.975   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:13:35.981   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:13:36.799  2353  2353 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:13:36.820  2353  2353 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:13:36.823  2353  2353 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:13:36.865   964  1879 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:13:36.872  4895  4932 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:13:36.872  4895  4932 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:13:36.872  4895  4932 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:13:36.872  4895  4932 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:13:36.873   277  1040 E BandwidthController: [LG DATA] No such appUid: 10036
07-05 12:13:36.873   277  1040 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
07-05 12:13:36.879   277  6109 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 12:13:36.879   277  6109 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:13:36.880   277  6109 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
,07-05 12:13:36.883   964  1053 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-05 12:13:40.729   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 12:13:40.732  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:13:40.733  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:13:40.733  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:13:40.733  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:13:40.734  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:13:40.778  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:13:40.781  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:13:40.782  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:13:40.783  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:13:40.783  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:13:40.783  1870  2048 D LEDHandler: Battery Temp: 294, mChargingStatus=5, mChargingStop=false
07-05 12:13:40.784  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
07-05 12:13:40.784  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:13:40.784  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
07-05 12:13:40.787  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:13:40.791   964  1316 D WifiController: battery changed pluggedType: 2
,07-05 12:13:40.794  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:13:40.986   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:13:43.908   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:13:43.908   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:13:43.908   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 972528792549; DSPS: 31966294; Offset : -3010935816
,07-05 12:13:45.992   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:13:50.998   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:13:56.004   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:14:00.039  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:14:00.039  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:14:00.039  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:14:00.043  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:14:00.043  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:14:00.044  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:14:00.045  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:14:01.010   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:14:03.910   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:14:03.910   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:14:03.910   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 992530742750; DSPS: 32621718; Offset : -3010938479
,07-05 12:14:06.016   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:14:11.022   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:14:16.028   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:14:21.034   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:14:23.912   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:14:23.912   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:14:23.912   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1012532253941; DSPS: 33277127; Offset : -3010922781
,07-05 12:14:26.039   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:14:31.045   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:14:36.050   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:14:40.889   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 12:14:40.893  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:14:40.893  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:14:40.893  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:14:40.893  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:14:40.893  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:14:41.056   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:14:43.914   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:14:43.914   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:14:43.914   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1032534563620; DSPS: 33932563; Offset : -3010932827
,07-05 12:14:46.062   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:14:51.068   295   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 12:14:56.074   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:15:00.041  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:15:00.041  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:15:00.041  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:15:00.045  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:15:00.045  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:15:00.046  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:15:00.046  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:15:01.080   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:15:03.915   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:15:03.915   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:15:03.915   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1052535453873; DSPS: 34587952; Offset : -3010927428
,07-05 12:15:06.086   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:15:11.091   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:15:16.097   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:15:21.104   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:15:23.917   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:15:23.917   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:15:23.917   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1072537830949; DSPS: 35243390; Offset : -3010930645
,07-05 12:15:26.110   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:15:31.115   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:15:36.121   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:15:41.050   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 12:15:41.053  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:15:41.053  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:15:41.054  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:15:41.054  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:15:41.054  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:15:41.093  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:15:41.096  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:15:41.096  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:15:41.098  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:15:41.098  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:15:41.098  1870  2048 D LEDHandler: Battery Temp: 293, mChargingStatus=5, mChargingStop=false
07-05 12:15:41.099  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
07-05 12:15:41.099  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:15:41.100  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
07-05 12:15:41.101  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:15:41.105   964  1316 D WifiController: battery changed pluggedType: 2
,07-05 12:15:41.109  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:15:41.128   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:15:43.920   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:15:43.920   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:15:43.920   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1092540546097; DSPS: 35898839; Offset : -3010931276
,07-05 12:15:46.132   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:15:51.138   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:15:56.144   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:16:00.042  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:16:00.042  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:16:00.042  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:16:00.046  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:16:00.046  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:16:00.047  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:16:00.048  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:16:01.149   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:16:03.921   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:16:03.921   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:16:03.922   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1112542020882; DSPS: 36554247; Offset : -3010921595
,07-05 12:16:06.155   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:16:11.161   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:16:16.168   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:16:21.179   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:16:23.923   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:16:23.923   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:16:23.923   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1132543909624; DSPS: 37209669; Offset : -3010924942
,07-05 12:16:26.185   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:16:31.190   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:16:36.196   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:16:41.201   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:16:41.210  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:16:41.210  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:16:41.210  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:16:41.210  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:16:41.211  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:16:41.212   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:16:43.925   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:16:43.925   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:16:43.926   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1152546004512; DSPS: 37865098; Offset : -3010935741
,07-05 12:16:46.206   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:16:51.212   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:16:56.218   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:17:00.038  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:17:00.038  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:17:00.038  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:17:00.043  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:17:00.043  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:17:00.044  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:17:00.044  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:17:01.224   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:17:03.928   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:17:03.928   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:17:03.928   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1172548274764; DSPS: 38520532; Offset : -3010923999
,07-05 12:17:06.230   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:17:11.236   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:17:16.242   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:17:21.248   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:17:23.930   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:17:23.930   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:17:23.930   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1192550547622; DSPS: 39175967; Offset : -3010939985
,07-05 12:17:26.254   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:17:31.260   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:17:36.266   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:17:41.272   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:17:41.372  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,07-05 12:17:41.375  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:17:41.376  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:17:41.376  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:17:41.376  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:17:41.376   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:17:41.415  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:17:41.420  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:17:41.420  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:17:41.420  1870  2048 D LEDHandler: Battery Temp: 292, mChargingStatus=5, mChargingStop=false
07-05 12:17:41.420  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:17:41.420  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:17:41.421  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
07-05 12:17:41.421  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:17:41.422  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
07-05 12:17:41.424  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:17:41.428   964  1316 D WifiController: battery changed pluggedType: 2
,07-05 12:17:41.432  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:17:43.932   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:17:43.932   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:17:43.932   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1212552819854; DSPS: 39831401; Offset : -3010925872
,07-05 12:17:46.278   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:17:51.284   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:17:55.730   964  1034 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 12:17:56.290   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:18:00.041  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:18:00.041  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:18:00.041  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:18:00.045  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:18:00.045  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:18:00.046  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:18:00.046  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:18:01.295   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:18:03.934   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:18:03.934   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:18:03.934   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1232554435055; DSPS: 40486814; Offset : -3010928154
,07-05 12:18:06.301   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:18:11.307   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:18:16.313   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:18:21.319   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:18:23.935   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:18:23.935   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:18:23.935   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1252555561714; DSPS: 41142211; Offset : -3010930411
,07-05 12:18:26.325   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:18:31.330   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:18:36.336   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:18:36.923  2353  2353 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:18:36.940  2353  2353 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:18:36.943  2353  2353 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:18:36.985   964  2271 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:18:36.992  4895  4932 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:18:36.992  4895  4932 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:18:36.992  4895  4932 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:18:36.992  4895  4932 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:18:36.993   277  1040 E BandwidthController: [LG DATA] No such appUid: 10036
07-05 12:18:36.993   277  1040 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
07-05 12:18:36.999   277  6158 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 12:18:36.999   277  6158 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:18:37.000   277  6158 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
,07-05 12:18:37.004   964  1053 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-05 12:18:41.342   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:18:41.530   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 12:18:41.532  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:18:41.532  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:18:41.533  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:18:41.539  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:18:41.539  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:18:43.937   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:18:43.937   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:18:43.937   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1272557825507; DSPS: 41797645; Offset : -3010925076
,07-05 12:18:46.348   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:18:51.354   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:18:56.360   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:19:00.044  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:19:00.044  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:19:00.044  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:19:00.048  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:19:00.048  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:19:00.049  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:19:00.050  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:19:01.366   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:19:03.940   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:19:03.940   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:19:03.940   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1292560136907; DSPS: 42453081; Offset : -3010933038
,07-05 12:19:06.372   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:19:11.378   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:19:16.384   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:19:21.390   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:19:23.941   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:19:23.941   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:19:23.941   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1312561257420; DSPS: 43108478; Offset : -3010941492
,07-05 12:19:26.395   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:19:31.401   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:19:36.407   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:19:41.414   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:19:41.690   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 12:19:41.698  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:19:41.698  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:19:41.699  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:19:41.699  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:19:41.699  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:19:43.943   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:19:43.943   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:19:43.943   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1332562990225; DSPS: 43763894; Offset : -3010918115
,07-05 12:19:46.420   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:19:51.426   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:19:56.431   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:20:00.041  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:20:00.041  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:20:00.041  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:20:00.045  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:20:00.045  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:20:00.046  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:20:00.047  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:20:01.437   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:20:03.944   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:20:03.944   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:20:03.944   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1352564487040; DSPS: 44419304; Offset : -3010946866
,07-05 12:20:06.442   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:20:11.449   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:20:16.455   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:20:21.461   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:20:23.946   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:20:23.946   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:20:23.946   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1372566877032; DSPS: 45074742; Offset : -3010937298
,07-05 12:20:26.466   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:20:31.473   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:20:36.479   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:20:41.484   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:20:41.849   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 12:20:41.852  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:20:41.852  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:20:41.852  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:20:41.853  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:20:41.859  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:20:41.896  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:20:41.900  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:20:41.900  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:20:41.901  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:20:41.901  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:20:41.901  1870  2048 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
07-05 12:20:41.902  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
07-05 12:20:41.902  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:20:41.902  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
07-05 12:20:41.905  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:20:41.909   964  1316 D WifiController: battery changed pluggedType: 2
,07-05 12:20:41.912  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:20:43.948   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:20:43.948   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:20:43.948   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1392568636608; DSPS: 45730159; Offset : -3010917223
,07-05 12:20:46.490   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:20:51.496   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:20:56.502   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:21:00.047  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:21:00.047  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:21:00.047  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:21:00.051  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:21:00.051  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:21:00.052  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:21:00.053  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:21:01.508   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:21:03.950   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:21:03.950   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:21:03.950   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1412570708788; DSPS: 46385588; Offset : -3010950626
,07-05 12:21:06.514   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:21:11.520   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:21:16.526   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:21:21.532   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:21:23.953   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:21:23.953   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:21:23.953   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1432573092478; DSPS: 47041026; Offset : -3010947541
,07-05 12:21:26.538   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:21:31.544   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:21:36.550   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:21:41.556   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:21:42.007   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 12:21:42.010  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:21:42.010  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:21:42.010  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:21:42.010  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:21:42.011  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:21:43.954   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:21:43.954   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:21:43.955   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1452574980960; DSPS: 47696447; Offset : -3010920606
,07-05 12:21:46.562   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:21:51.567   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:21:56.573   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:22:00.039  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:22:00.039  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:22:00.040  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:22:00.044  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:22:00.044  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:22:00.045  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:22:00.045  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:22:01.579   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:22:03.957   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:22:03.957   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:22:03.957   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1472577244025; DSPS: 48351882; Offset : -3010946228
,07-05 12:22:06.585   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:22:11.591   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:22:16.597   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:22:21.603   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:22:23.959   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:22:23.960   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:22:23.960   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1492579617507; DSPS: 49007319; Offset : -3010922210
,07-05 12:22:26.609   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:22:31.615   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:22:36.621   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:22:41.627   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:22:42.169   471   471 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 12:22:42.172  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:22:42.172  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:22:42.178  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:22:42.178  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:22:42.179  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:22:42.228  2056  3356 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:22:42.232  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:22:42.232  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:22:42.233  1870  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:22:42.233  1870  2048 D LEDHandler: Battery Level Remaining: 100%
07-05 12:22:42.233  1870  2048 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
07-05 12:22:42.234  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
07-05 12:22:42.234  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:22:42.234  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
07-05 12:22:42.240   964  1316 D WifiController: battery changed pluggedType: 2
,07-05 12:22:42.244  5569  5569 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:22:42.244  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:22:43.962   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:22:43.962   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:22:43.962   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1512582008334; DSPS: 49662758; Offset : -3010942791
,07-05 12:22:46.633   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:22:51.639   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:22:56.645   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:23:00.043  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:23:00.044  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:23:00.044  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:23:00.048  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:23:00.048  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:23:00.049  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:23:00.050  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:23:01.651   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:23:03.964   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:23:03.964   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:23:03.964   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1532584278846; DSPS: 50318192; Offset : -3010930451
,07-05 12:23:06.657   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:23:11.663   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:23:16.669   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:23:21.675   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:23:23.966   964   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:23:23.966   964   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:23:23.966   964   998 D sensors_hal_Time: tsOffsetIs: Apps: 1552586537485; DSPS: 50973626; Offset : -3010930164
,07-05 12:23:26.684   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-05 12:23:31.690   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,TIME-OUT KILL (timeout was 1401000ms),07-05 12:23:35.565  6205  6205 D AndroidRuntime: 
07-05 12:23:35.565  6205  6205 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 12:23:35.577  6205  6205 D AndroidRuntime: CheckJNI is OFF
07-05 12:23:35.976  6205  6205 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-05 12:23:36.044   964  1036 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
07-05 12:23:36.058   964  1036 I ActivityManager: Killing 5759:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
07-05 12:23:36.117   964  1900 I WindowState: WIN DEATH: Window{833309b u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 12:23:36.128   964  1900 D InputDispatcher: Focus left window: Window{833309b u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 12:23:36.128   964  1900 D InputDispatcher: Window went away: Window{833309b u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 12:23:36.184   964  1036 I ActivityManager:   Force finishing activity ActivityRecord{284323f9 u0 com.test.thalitest/.MainActivity t241}
07-05 12:23:36.231   964  1063 W PackageSettings: Skipping PackageSetting{9764294 com.example.hello/10317} due to missing metadata
07-05 12:23:36.267   964   964 V ActivityManager: Display changed displayId=0
07-05 12:23:36.275  1770  1770 D DSDPConnection: Display #0 changed.
07-05 12:23:36.286   964  1947 W ActivityManager: Spurious death for ProcessRecord{32014734 5759:com.test.thalitest/u0a30}, curProc for 5759: null
07-05 12:23:36.299   964  1063 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
07-05 12:23:36.362  1948  1948 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
07-05 12:23:36.376  2031  2031 I art     : Explicit concurrent mark sweep GC freed 1973(120KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 12MB/20MB, paused 1.414ms total 72.731ms
07-05 12:23:36.380  1371  1371 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
07-05 12:23:36.386  2353  2662 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-05 12:23:36.391   964  1289 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-05 12:23:36.391  3470  3470 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-05 12:23:36.394  1948  1948 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
07-05 12:23:36.394  1909  1909 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
07-05 12:23:36.399  3470  3470 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-05 12:23:36.399  3470  3470 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
07-05 12:23:36.399  3470  3470 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
07-05 12:23:36.399  3470  3470 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 12:23:36.399  3470  3470 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 12:23:36.399  3470  3470 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-05 12:23:36.399  3470  3470 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
07-05 12:23:36.399  3470  3470 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:23:36.400  3470  3470 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:23:36.400  3470  3470 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
07-05 12:23:36.401  3470  3470 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
07-05 12:23:36.430  5409  5409 I art     : Explicit concurrent mark sweep GC freed 21480(1437KB) AllocSpace objects, 11(176KB) LOS objects, 25% free, 14MB/19MB, paused 1.004ms total 124.136ms
07-05 12:23:36.439   964  1036 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6236 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
07-05 12:23:36.478  1371  1371 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
07-05 12:23:36.481  1948  1948 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
07-05 12:23:36.482  1948  1948 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
07-05 12:23:36.482  1948  1948 I Activity: Activity.onPostResume() called 
07-05 12:23:36.492   964  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:23:36.492   964  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:23:36.492   964  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:23:36.492   964  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:23:36.493  1948  1948 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
07-05 12:23:36.493   277  1040 E BandwidthController: [LG DATA] No such appUid: 1000
07-05 12:23:36.493   277  1040 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-05 12:23:36.494   277  6252 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 12:23:36.495   277  6252 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:23:36.495   277  6252 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 12:23:36.496   964  1053 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-05 12:23:36.513   964  1054 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
07-05 12:23:36.514   964  1054 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
07-05 12:23:36.517   964  1054 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
07-05 12:23:36.517   964  1054 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
07-05 12:23:36.517   964  1054 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 12:23:36.517   964  1054 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@fab6dbc,  pkg=WindowManager.LayoutParams
07-05 12:23:36.517   964  1054 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
07-05 12:23:36.519  1948  6254 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
07-05 12:23:36.521   964   983 D InputDispatcher: Focus entered window: Window{378c3f63 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
07-05 12:23:36.544  1948  1948 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-05 12:23:36.549  1948  1948 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-05 12:23:36.550  1948  1948 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
07-05 12:23:36.552  1371  1371 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
07-05 12:23:36.552  1371  1371 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
07-05 12:23:36.553  1371  1371 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
07-05 12:23:36.553  1371  1371 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
07-05 12:23:36.553  1371  1371 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
07-05 12:23:36.553  1371  1371 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
07-05 12:23:36.554  1948  1948 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
07-05 12:23:36.562  1948  1948 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
07-05 12:23:36.564  1948  1948 I PhoneWindow: [setNavigationBarColor] color=0x 0
07-05 12:23:36.567   964   983 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
07-05 12:23:36.568   964   983 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5759 uid 10030
07-05 12:23:36.600  6236  6236 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 12:23:36.601  6236  6236 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-05 12:23:36.604  6236  6236 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-05 12:23:36.628  1371  1507 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-05 12:23:36.628  1371  1507 D KeyguardModel: createShortcutInfo...
07-05 12:23:36.632  1948  1948 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2502f5c8 time:1565252
07-05 12:23:36.632  1371  1507 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-05 12:23:36.632  1371  1507 D KeyguardModel: createShortcutInfo...
07-05 12:23:36.634  1371  1507 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 12:23:36.637  1371  1507 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-05 12:23:36.638  1371  1507 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-05 12:23:36.638  1371  1507 D KeyguardModel: createShortcutInfo...
07-05 12:23:36.641  1371  1507 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 12:23:36.642  1371  1507 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-05 12:23:36.644   964  1056 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{37a67b8 u0 com.lge.launcher2/.Launcher t240} time:1565264
07-05 12:23:36.647   964   964 I art     : Explicit concurrent mark sweep GC freed 43342(3MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/35MB, paused 20.235ms total 309.520ms
07-05 12:23:36.648  1371  1507 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-05 12:23:36.648  1371  1507 D KeyguardModel: createShortcutInfo...
07-05 12:23:36.653  1371  1507 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 12:23:36.653  1371  1507 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-05 12:23:36.659   964  1063 I art     : WaitForGcToComplete blocked for 204.699ms for cause Explicit
07-05 12:23:36.663  1371  1507 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-05 12:23:36.664  1371  1507 D KeyguardModel: createShortcutInfo...
07-05 12:23:36.685  1948  1948 I art     : Explicit concurrent mark sweep GC freed 4076(233KB) AllocSpace objects, 4(645KB) LOS objects, 39% free, 15MB/25MB, paused 1.379ms total 52.622ms
07-05 12:23:36.690  1371  1371 D KeyguardModel: handleShortcutListChanged...
07-05 12:23:36.694   295   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
07-05 12:23:36.695  1371  1507 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-05 12:23:36.696  1371  1507 D KeyguardModel: createShortcutInfo...
07-05 12:23:36.700  1371  1507 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-05 12:23:36.700  1371  1507 D KeyguardModel: createShortcutInfo...
07-05 12:23:36.701  1371  1507 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 12:23:36.701  1371  1507 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-05 12:23:36.703  1371  1507 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-05 12:23:36.703  1371  1507 D KeyguardModel: createShortcutInfo...
07-05 12:23:36.705  1371  1507 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 12:23:36.705  1371  1507 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-05 12:23:36.707  1371  1507 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-05 12:23:36.707  1371  1507 D KeyguardModel: createShortcutInfo...
07-05 12:23:36.708  1371  1507 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 12:23:36.708  1371  1507 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-05 12:23:36.710  1371  1507 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-05 12:23:36.710  1371  1507 D KeyguardModel: createShortcutInfo...
07-05 12:23:36.717   964   964 D administrator: Handling package changes for user 0
07-05 12:23:36.720  1371  1371 D KeyguardModel: handleShortcutListChanged...
07-05 12:23:36.769  1948  1948 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
07-05 12:23:36.776  1627  1627 E b       : Unable to connect to the editor to retrieve text... will retry later
07-05 12:23:36.784  1948  1948 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
07-05 12:23:36.877  6236  6236 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
07-05 12:23:36.904  6236  6236 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
07-05 12:23:36.925   964  1063 I art     : Explicit concurrent mark sweep GC freed 10210(1034KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 3.933ms total 262.303ms
07-05 12:23:37.038  1840  1840 D LCardEmulationManager: getHceAppCount hostAppNum : 0
07-05 12:23:37.038  1840  1840 D LCardEmulationManager: getDefaultRoute
07-05 12:23:37.080   964   964 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
07-05 12:23:37.080   964  1034 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 12:23:37.080   964   964 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-05 12:23:37.083  6205  6205 D AndroidRuntime: Shutting down VM
07-05 12:23:37.087   964   964 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-05 12:23:37.102   964  1350 D TaskPersister: removeObsoleteFile: deleting file=241_task.xml
07-05 12:23:37.130  2353  2353 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:23:37.175  6236  6236 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
07-05 12:23:37.199   964  1034 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
07-05 12:23:37.223   964  1298 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6264 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
07-05 12:23:37.224   964  1298 I ActivityManager: Killing 5392:com.lge.eula/1000 (adj 15): empty #11
07-05 12:23:37.229  2353  2375 I art     : Explicit concurrent mark sweep GC freed 39380(2MB) AllocSpace objects, 17(272KB) LOS objects, 39% free, 14MB/24MB, paused 1.277ms total 89.203ms
07-05 12:23:37.260   964   985 W libprocessgroup: failed to open /acct/uid_1000/pid_5392/cgroup.procs: No such file or directory
07-05 12:23:37.265  1948  1948 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
07-05 12:23:37.267  2353  2353 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:23:37.268  2353  2353 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:23:37.306   964  2011 I NotificationManager: android: cancelAsUser(2) by android
07-05 12:23:37.322  6264  6264 I AppUp4:AppBoxCP: onCreate
07-05 12:23:37.323  6264  6264 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
07-05 12:23:37.331  6264  6264 I AppUp4:DB:  setFingerPrint start
07-05 12:23:37.332  6264  6264 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
07-05 12:23:37.337  6264  6264 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
07-05 12:23:37.338  6264  6264 I AppUp4:DB:  SDK version = 21
07-05 12:23:37.338  6264  6264 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-05 12:23:37.352   964  1063 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6284 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
07-05 12:23:37.353  6264  6264 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-05 12:23:37.361  4895  4932 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:23:37.361  4895  4932 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:23:37.362  4895  4932 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:23:37.362  4895  4932 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:23:37.362   277  1040 E BandwidthController: [LG DATA] No such appUid: 10036
07-05 12:23:37.362   277  1040 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
07-05 12:23:37.362   277  6295 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 12:23:37.363   277  6295 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:23:37.363   277  6295 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 12:23:37.364   964  1053 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-05 12:23:37.440  6264  6264 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
07-05 12:23:37.490   964   983 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6306 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
07-05 12:23:37.491   964   983 I ActivityManager: Killing 5464:com.google.android.apps.docs/u0a58 (adj 15): empty #11
07-05 12:23:37.516   313   313 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 379us total 23.046ms
07-05 12:23:37.541   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 21.865ms
07-05 12:23:37.565   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 22.158ms

```
