#### Test 79763830edacfaa_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-23 16:34:39.098  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:34:39.106  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
,08-23 16:34:40.713  6381  6381 D AndroidRuntime: 
08-23 16:34:40.713  6381  6381 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 16:34:40.717  6381  6381 D AndroidRuntime: CheckJNI is OFF
08-23 16:34:40.978  6381  6381 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 16:34:40.997   857  2153 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 16:34:41.055   857  2153 D ActivityManager: setTaskToReturnTo : TaskRecord{e66c4ae #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 16:34:41.056   857  2153 D ActivityManager: setTaskToReturnTo : TaskRecord{e66c4ae #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 16:34:41.082   857  2153 D WindowStateEx: AppWindowTokenEx init.. 
08-23 16:34:41.101   857  1051 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-23 16:34:41.104  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:34:41.105  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:34:41.105  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-23 16:34:41.117   857  1051 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-23 16:34:41.118  1875  1875 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-23 16:34:41.119   857  2153 D InputDispatcher: Focus left window: Window{22eb89ff u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-23 16:34:41.121  6381  6381 D AndroidRuntime: Shutting down VM
08-23 16:34:41.134   857  1051 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-23 16:34:41.134   857  1051 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-23 16:34:41.152   857  1051 D SplitWindow: check instance of lgWin Window{29e6bb86 u0 Starting com.test.thalitest}
08-23 16:34:41.191   857  2172 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6401 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 16:34:41.200  1875  1875 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-23 16:34:41.257  1875  1875 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-23 16:34:41.264  1962  1962 I HotwordDetector: Closing mic
08-23 16:34:41.270   857  1291 I WindowStateAnimator: Starting window displayed
08-23 16:34:41.278   857  1049 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-23 16:34:41.281  1962  2563 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@1094cb49
08-23 16:34:41.281  1962  2563 V AudioRecord: stop()
08-23 16:34:41.281  1962  2563 D AudioRecord: AudioRecord->stop()
08-23 16:34:41.283   280  1297 V AudioFlinger: RecordHandle::stop()
08-23 16:34:41.283   857  1049 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-23 16:34:41.283   280  1297 V AudioFlinger: RecordThread::stop
08-23 16:34:41.287   857  1049 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-23 16:34:41.287   857  1049 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-23 16:34:41.287   857  1049 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-23 16:34:41.287   857  1049 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@35377356,  pkg=WindowManager.LayoutParams
08-23 16:34:41.287   857  1049 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-23 16:34:41.288  1374  1374 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-23 16:34:41.290  1374  1374 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-23 16:34:41.290  1374  1374 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-23 16:34:41.290  1374  1374 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-23 16:34:41.292   280  1297 V AudioFlinger: Record stopped OK
08-23 16:34:41.294   280  1297 V AudioPolicyManager: stopInput() input 17
08-23 16:34:41.296   280  1297 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
08-23 16:34:41.296   280  1297 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
08-23 16:34:41.297   280  1060 V AudioPolicyService: AudioCommandThread() waking up
08-23 16:34:41.297   280  1060 V AudioPolicyService: AudioCommandThread() processing release audio patch
08-23 16:34:41.297   280  1060 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
08-23 16:34:41.297   280  1060 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
08-23 16:34:41.297   280  1060 V AudioFlinger: ThreadBase::setParameters() routing=0
08-23 16:34:41.297   280  1060 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-23 16:34:41.297   280  2581 V AudioFlinger: processConfigEvents_l() remaining events 1
08-23 16:34:41.298   280  2581 V AudioFlinger: processConfigEvents_l() DONE thread 0xb384f000
08-23 16:34:41.302   280  2581 D audio_hw_primary: in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
,08-23 16:34:41.349   280  2581 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
08-23 16:34:41.349   280  2581 V audio_hw_primary: disable_audio_route: enter: usecase(7)
08-23 16:34:41.349   280  2581 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
08-23 16:34:41.349   280  2581 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-23 16:34:41.351   280  2581 V audio_hw_primary: disable_audio_route: exit
08-23 16:34:41.351   280  2581 E audio_hw_primary: disable_snd_device: enter 144
08-23 16:34:41.351   280  2581 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
08-23 16:34:41.351   280  2581 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
08-23 16:34:41.354   280  2581 V audio_hw_primary: stop_input_stream: exit: status(0)
08-23 16:34:41.354   280  2581 V audio_hw_primary: in_standby: exit:  status(0)
08-23 16:34:41.354   280  2581 V AudioFlinger: RecordThread: loop stopping
08-23 16:34:41.354   280  1060 V AudioPolicyService: AudioCommandThread() going to sleep
08-23 16:34:41.354   280  1297 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
08-23 16:34:41.354   280  1297 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
08-23 16:34:41.354   280  1297 V AudioPolicyService: AudioCommandThread() adding update audio patch list
08-23 16:34:41.354   280  1297 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
08-23 16:34:41.354   280  1061 V AudioPolicyService: AudioCommandThread() waking up
08-23 16:34:41.354   280  1061 V AudioPolicyService: AudioCommandThread() processing update audio patch list
08-23 16:34:41.354   280  1061 V AudioPolicyService: AudioCommandThread() going to sleep
08-23 16:34:41.355   280  1297 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
08-23 16:34:41.355   280  1297 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
08-23 16:34:41.356   280  1060 V AudioPolicyService: AudioCommandThread() waking up
08-23 16:34:41.356   280  1060 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
08-23 16:34:41.356   280  1060 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 280
08-23 16:34:41.356   280  1060 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
08-23 16:34:41.356   280  1060 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-23 16:34:41.356   280  2581 V AudioFlinger: RecordThread: loop starting
08-23 16:34:41.356   280  2581 V AudioFlinger: processConfigEvents_l() remaining events 1
08-23 16:34:41.356   280  2581 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
08-23 16:34:41.356   280  2581 V audio_hw_primary: in_set_parameters: exit: status(0)
08-23 16:34:41.356   280  2581 V AudioFlinger: processConfigEvents_l() DONE thread 0xb384f000
08-23 16:34:41.356   280  2581 V AudioFlinger: RecordThread: loop stopping
08-23 16:34:41.356   280  1060 V AudioPolicyService: AudioCommandThread() going to sleep
08-23 16:34:41.361  1962  2563 V AudioRecord: stop()
08-23 16:34:41.362  1962  2563 V AudioRecord: stop()
08-23 16:34:41.362  1962  2563 V AudioRecord: stop()
08-23 16:34:41.364   280  1352 V AudioFlinger: RecordHandle::stop()
08-23 16:34:41.364   280   280 V AudioFlinger: releasing 16 from 1962 for -1
08-23 16:34:41.364   280  1352 V AudioFlinger: RecordThread::stop
08-23 16:34:41.364   280   280 V AudioFlinger:  decremented refcount to 0
08-23 16:34:41.364   280   280 V AudioFlinger: purging stale effects
08-23 16:34:41.364   280  1352 V AudioPolicyManager: releaseInput() 17
08-23 16:34:41.364   280  1352 V AudioPolicyManager: closeInput(17)
08-23 16:34:41.364   280  1352 V AudioFlinger: closeInput() 17
08-23 16:34:41.364   280  1352 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-23 16:34:41.364  1374  1401 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-23 16:34:41.364   280  1352 V AudioFlinger: ThreadBase::exit
08-23 16:34:41.364  1748  2332 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-23 16:34:41.364  1962  1987 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-23 16:34:41.365   857  1291 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-23 16:34:41.365  3166  3342 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-23 16:34:41.365  2890  2908 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-23 16:34:41.365   280  2581 V AudioFlinger: RecordThread: loop starting
08-23 16:34:41.365  2033  3812 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-23 16:34:41.365   280  2581 V AudioFlinger: RecordThread 0xb384f000 exiting
08-23 16:34:41.366   280  1352 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546e420)
08-23 16:34:41.366   280  1352 D audio_hw_primary: in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
08-23 16:34:41.366   280  1352 V audio_hw_primary: in_standby: exit:  status(0)
08-23 16:34:41.366   280  1352 V AudioPolicyService: AudioCommandThread() adding update audio port list
08-23 16:34:41.366   280  1352 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
08-23 16:34:41.366   280  1352 V AudioPolicyManager: releaseInput() exit
08-23 16:34:41.366   280  1061 V AudioPolicyService: AudioCommandThread() waking up
08-23 16:34:41.366   280  1061 V AudioPolicyService: AudioCommandThread() processing update audio port list
08-23 16:34:41.366   280  1352 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
08-23 16:34:41.366   280  1352 V AudioFlinger: removeClient_l() pid 1962, calling pid 280
08-23 16:34:41.367   280  1061 V AudioPolicyService: AudioCommandThread() going to sleep
08-23 16:34:41.372  1962  2575 I HotwordRecognitionRnr: Stopping hotword detection.
08-23 16:34:41.375  1962  2577 I HotwordRecognitionRnr: Hotword detection finished
08-23 16:34:41.402  6401  6401 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-23 16:34:41.500  6401  6401 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-23 16:34:41.554  6401  6401 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7771-7774)
08-23 16:34:41.555  6401  6401 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 16:34:41.591  6401  6401 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2215eef6}
08-23 16:34:41.592  6401  6401 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 16:34:41.594  6401  6401 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 16:34:41.608  6401  6401 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-23 16:34:41.611  6401  6401 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 16:34:41.612  6401  6401 E SysUtils: ApplicationContext is null in ApplicationStatus
08-23 16:34:41.637  6401  6401 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-23 16:34:41.644  6401  6401 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 16:34:41.644  6401  6401 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 16:34:41.645  6401  6401 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 16:34:41.645  6401  6401 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 16:34:41.645  6401  6401 I Adreno-EGL: Build Date: 03/02/15 Mon
08-23 16:34:41.645  6401  6401 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-23 16:34:41.645  6401  6401 I Adreno-EGL: Remote Branch: 
08-23 16:34:41.645  6401  6401 I Adreno-EGL: Local Patches: 
08-23 16:34:41.645  6401  6401 I Adreno-EGL: Reconstruct Branch: 
08-23 16:34:41.715   280  1297 V AudioPolicyService: registerClient() client 0xb384d800, uid 10030
08-23 16:34:41.742   857  1050 D BluetoothManagerService: Message: 20
08-23 16:34:41.742   857  1050 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e6367d1:true
08-23 16:34:41.750  2033  2054 D BluetoothAdapterService(608638308): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17afa1da
08-23 16:34:41.781  3345  6287 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-23 16:34:41.781  3345  6287 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-23 16:34:41.836  3345  6287 I CheckinTask: Sending checkin request (11345 bytes)
08-23 16:34:41.909  6401  6401 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 16:34:41.923  6401  6401 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-23 16:34:41.932  6401  6401 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-23 16:34:41.937  6401  6401 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-23 16:34:41.937  6401  6401 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-23 16:34:41.951  6401  6401 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-23 16:34:41.961  6401  6401 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 16:34:41.961  6401  6401 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 16:34:42.014  6401  6401 I Activity: Activity.onPostResume() called 
08-23 16:34:42.024  6401  6450 D OpenGLRenderer: Render dirty regions requested: true
08-23 16:34:42.024  6401  6450 I OpenGLRenderer: Initialized EGL, version 1.4
08-23 16:34:42.030  6401  6450 D OpenGLRenderer: Enabling debug mode 0
08-23 16:34:42.049  6401  6401 D Atlas   : Validating map...
08-23 16:34:42.054   857  1771 D SplitWindow: check instance of lgWin Window{bce741 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-23 16:34:42.065  6401  6437 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-23 16:34:42.103   857  1783 D InputDispatcher: Focus entered window: Window{bce741 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 16:34:42.106  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,08-23 16:34:42.106  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:34:42.106  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
08-23 16:34:42.163   857   886 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-23 16:34:42.177   857  1051 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s25ms
08-23 16:34:42.177   857  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3e42f24f u0 com.test.thalitest/.MainActivity t259} time:118397
,08-23 16:34:42.187  6401  6401 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@51e2100 time:118407
08-23 16:34:42.279  6401  6401 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6401
,08-23 16:34:42.334  3345  6287 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,08-23 16:34:42.339  3345  6287 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
08-23 16:34:42.421   293   348 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-23 16:34:42.476  6401  6401 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 16:34:42.498  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-23 16:34:42.499  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-23 16:34:42.544  3345  6287 I CheckinUtil: Classify the device as Phone.
,08-23 16:34:42.565  3345  6287 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
08-23 16:34:42.569  3345  6287 I CheckinChimeraService: Checking schedule, now: 1471962882569 next: 1472490131565
08-23 16:34:42.570  3345  6287 I CheckinChimeraService: active receiver: disabled
,08-23 16:34:42.598  3345  3345 D CheckinChimeraService: Recording last checkin time for package unspecified as 1471962882598
,08-23 16:34:42.651   857  1825 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6466 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,08-23 16:34:42.661   857  1825 I ActivityManager: Killing 6052:com.android.contacts/u0a18 (adj 15): empty #11
08-23 16:34:42.700   857  1825 I ActivityManager: Killing 6000:com.android.gallery3d/u0a23 (adj 15): empty #12
,08-23 16:34:42.738   857  5504 W libprocessgroup: failed to open /acct/uid_10018/pid_6052/cgroup.procs: No such file or directory
,08-23 16:34:42.742   857  1801 W libprocessgroup: failed to open /acct/uid_10023/pid_6000/cgroup.procs: No such file or directory
08-23 16:34:42.780  1875  1875 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-23 16:34:42.781  1875  1875 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-23 16:34:42.781  1875  1875 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,08-23 16:34:42.786  1374  1374 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
08-23 16:34:42.792  1374  1374 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-23 16:34:42.793   857  1286 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 16:34:42.798  1837  1837 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
08-23 16:34:42.811  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
08-23 16:34:42.811  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
08-23 16:34:42.811  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
08-23 16:34:42.811  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
08-23 16:34:42.811  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
08-23 16:34:42.812  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
08-23 16:34:42.812  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
08-23 16:34:42.812  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
08-23 16:34:42.812  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
08-23 16:34:42.812  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
08-23 16:34:42.812  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
08-23 16:34:42.812  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
08-23 16:34:42.812  1374  1374 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-23 16:34:42.827   857   857 D administrator: Handling package changes for user 0
,08-23 16:34:42.844  1875  1875 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,08-23 16:34:43.015  6466  6466 D PhoneMonitor: Register our PhoneStateListener
,08-23 16:34:43.061  6401  6453 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635611904
,08-23 16:34:43.067  6466  6466 V SetupWizard: Connected to Gservices successfully
08-23 16:34:43.070   857   857 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-23 16:34:43.070   857   857 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-23 16:34:43.070   857   857 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
08-23 16:34:43.077   857   857 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,08-23 16:34:43.083   857  1874 I ActivityManager: Killing 6077:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,08-23 16:34:43.096  6401  6453 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 16:34:43.096  6401  6453 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 16:34:43.096  6401  6453 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 16:34:43.096  6401  6453 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 16:34:43.096  6401  6453 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 16:34:43.096  6401  6453 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd02cad added. We now have 1 listener(s)
08-23 16:34:43.108  6466  6466 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-23 16:34:43.111  6466  6466 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-23 16:34:43.115  6466  6466 D TelephonyAutoProfiling: [parse] Load xml
08-23 16:34:43.120  6466  6466 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-23 16:34:43.121  6466  6466 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,08-23 16:34:43.131   857   990 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 16:34:43.136  6466  6466 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-23 16:34:43.142   857  1783 W libprocessgroup: failed to open /acct/uid_10069/pid_6077/cgroup.procs: No such file or directory
08-23 16:34:43.143   857  2172 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-23 16:34:43.149  6401  6453 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
08-23 16:34:43.152  6401  6453 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-23 16:34:43.153   857   857 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
08-23 16:34:43.153  6401  6453 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 16:34:43.153   857   857 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3919a2e
08-23 16:34:43.154  6401  6453 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 16:34:43.180  6401  6453 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 16:34:43.180  6401  6453 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 16:34:43.180  6401  6453 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 16:34:43.180  6401  6453 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-23 16:34:43.180  6401  6453 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 16:34:43.180  6401  6453 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 16:34:43.180  6401  6453 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 16:34:43.180  6401  6453 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 16:34:43.180  6401  6453 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 16:34:43.180  6401  6453 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 16:34:43.180  6401  6453 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 16:34:43.180  6401  6453 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 16:34:43.180  6401  6453 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 16:34:43.180  6401  6453 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 16:34:43.180  6401  6453 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@327bca30 added. We now have 1 listener(s)
08-23 16:34:43.181  6401  6453 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 16:34:43.199  6401  6453 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 16:34:43.200  6401  6453 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 16:34:43.202  6401  6453 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 16:34:43.202  6401  6453 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 16:34:43.202  6401  6453 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-23 16:34:43.223   857  1854 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6488 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-23 16:34:43.228  6401  6453 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 16:34:43.263   857  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-23 16:34:43.264  6401  6453 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-23 16:34:43.265  1730  4349 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-23 16:34:43.280  2033  2053 D BluetoothAdapterService(608638308): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17afa1da
08-23 16:34:43.282  6401  6453 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-23 16:34:43.282  6401  6453 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 16:34:43.282  6401  6453 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 16:34:43.282  6401  6453 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 16:34:43.282  6401  6453 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 16:34:43.282  6401  6453 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 16:34:43.282  6401  6453 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 16:34:43.282  6401  6453 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 16:34:43.282  6401  6453 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 16:34:43.282  6401  6453 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 16:34:43.282  6401  6453 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 16:34:43.288  6401  6453 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 16:34:43.294  6401  6401 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 16:34:43.298  6401  6401 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 16:34:43.334   857   990 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-23 16:34:43.342  6401  6401 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-23 16:34:43.369  6488  6488 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-23 16:34:43.372  1875  1875 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-23 16:34:43.394  1730  1730 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,08-23 16:34:43.400  1784  1784 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-23 16:34:43.400  1784  1784 D LCardEmulationManager: getDefaultRoute
08-23 16:34:43.436   857   990 D LocationProviderProxy: applying state to connected service
,08-23 16:34:43.491  6401  6415 I art     : Background sticky concurrent mark sweep GC freed 26809(1767KB) AllocSpace objects, 9(140KB) LOS objects, 3% free, 11MB/11MB, paused 7.166ms total 80.876ms
,08-23 16:34:43.514  6401  6415 I art     : CheckpointMarkThreadRoots callback created = 0xb03f3340
,08-23 16:34:43.548  6401  6415 I art     : CheckpointMarkThreadRoots callback created = 0xb03f3310
,08-23 16:34:43.680  2890  2890 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19964
08-23 16:34:43.680  6488  6511 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-23 16:34:43.682  6488  6511 I Babel_SMS: MmsConfig.loadMmsSettings
08-23 16:34:43.685  6488  6511 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
08-23 16:34:43.685  6488  6511 I Babel_SMS: MmsConfig.loadFromDatabase
,08-23 16:34:43.716  6488  6511 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-23 16:34:43.716  6488  6511 I Babel_SMS: MmsConfig.loadFromResources
08-23 16:34:43.718  6488  6511 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
08-23 16:34:43.718  6488  6511 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
08-23 16:34:43.757  6488  6488 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
08-23 16:34:43.757  6488  6488 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
08-23 16:34:43.757  6488  6488 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
08-23 16:34:43.757  6488  6488 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
08-23 16:34:43.757  6488  6488 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
08-23 16:34:43.757  6488  6488 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
,08-23 16:34:43.757  6488  6488 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
08-23 16:34:43.757  6488  6488 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
08-23 16:34:43.757  6488  6488 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
08-23 16:34:43.758  6488  6488 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
08-23 16:34:43.758  6488  6488 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
08-23 16:34:43.758  6488  6488 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
08-23 16:34:43.758  6488  6488 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
08-23 16:34:43.758  6488  6488 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
08-23 16:34:43.758  6488  6488 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
08-23 16:34:43.758  6488  6488 D SensorManager: found sensor: Motion Accel, handle=46
08-23 16:34:43.788   857  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{339b3a66 type 2 when 120000 com.google.android.gms} when 120000
,08-23 16:34:43.809  6488  6502 I art     : CheckpointMarkThreadRoots callback created = 0xaaf312c0
,08-23 16:34:43.825  6488  6488 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:34:43.848  6488  6488 I Babel_Crash: startup - clean
,08-23 16:34:43.878  6488  6502 I art     : CheckpointMarkThreadRoots callback created = 0xaaf312b0
,08-23 16:34:43.881  6488  6514 I Babel   : deleted: false for 0
08-23 16:34:43.947  6488  6488 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,08-23 16:34:43.949  6488  6488 W AudioCapabilities: Unsupported mime audio/adpcm
08-23 16:34:43.950  6488  6488 W AudioCapabilities: Unsupported mime audio/g726
08-23 16:34:43.957  6488  6488 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-23 16:34:43.959  6488  6488 W AudioCapabilities: Unsupported mime audio/wma-voice
,08-23 16:34:43.961  6488  6488 W VideoCapabilities: Unsupported mime video/mjpg
08-23 16:34:43.964  6488  6488 W VideoCapabilities: Unsupported mime video/theora
08-23 16:34:43.986   857  1825 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6516 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-23 16:34:44.043  6488  6488 W AudioCapabilities: Unsupported mime audio/evrc
,08-23 16:34:44.046  6488  6488 W AudioCapabilities: Unsupported mime audio/qcelp
08-23 16:34:44.047  6488  6488 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-23 16:34:44.056  6488  6488 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-23 16:34:44.060  6488  6488 W AudioCapabilities: Unsupported mime audio/qcelp
08-23 16:34:44.062  6488  6488 W AudioCapabilities: Unsupported mime audio/evrc
,08-23 16:34:44.111  6488  6488 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-23 16:34:44.151  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:34:44.151  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:34:44.151  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-23 16:34:44.159  6488  6488 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-23 16:34:44.178  6516  6516 I AppUp4:AppBoxCP: onCreate
,08-23 16:34:44.183  6488  6488 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-23 16:34:44.185  6488  6488 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-23 16:34:44.195  6488  6488 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-23 16:34:44.200  6516  6516 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-23 16:34:44.205  6488  6488 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-23 16:34:44.238  6516  6516 I AppUp4:DB:  setFingerPrint start
08-23 16:34:44.238  6516  6516 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
,08-23 16:34:44.255  6516  6516 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
08-23 16:34:44.256  6516  6516 I AppUp4:DB:  SDK version = 21
08-23 16:34:44.256  6516  6516 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-23 16:34:44.258  6516  6516 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-23 16:34:44.263   857  1994 I art     : Explicit concurrent mark sweep GC freed 55741(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/35MB, paused 2.266ms total 198.776ms
,08-23 16:34:44.293  6516  6516 I AppUp4:CustModeStarterReceiver: onReceive
08-23 16:34:44.293  6516  6516 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,08-23 16:34:44.307  6516  6516 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3eb45a2a
08-23 16:34:44.307  6516  6516 D AppUp4:CustFacade: isCustomizationCompleted : false
08-23 16:34:44.313  6516  6516 D AppUp4:CustFacade: isSimDevice : true
,08-23 16:34:44.314  6516  6516 D AppUp4:CustModeStarterReceiver: begin check event
08-23 16:34:44.314  6516  6516 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-23 16:34:44.316   857  1884 I ActivityManager: Killing 6177:com.lge.eula/1000 (adj 15): empty #11
08-23 16:34:44.332  6401  6505 W jxcore-log: Initializing JXcore engine
,08-23 16:34:44.334  6401  6505 W jxcore-log: JXcore engine is ready
08-23 16:34:44.391   857  2172 W libprocessgroup: failed to open /acct/uid_1000/pid_6177/cgroup.procs: No such file or directory
,08-23 16:34:44.421  6488  6488 I vclib   : onServiceConnected
,08-23 16:34:44.426  6488  6488 W Babel   : Attempted to change video mute state without an active call.
08-23 16:34:44.435  6488  6534 I NotificationManager: com.google.android.talk: cancel(8) by com.google.android.talk
,08-23 16:34:44.454  6505  6505 W Thread-774: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6307]" dev="sockfs" ino=6307 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-23 16:34:44.454  6505  6505 W Thread-774: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-23 16:34:44.454  6505  6505 W Thread-774: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7466]" dev="sockfs" ino=7466 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-23 16:34:44.454  6505  6505 W Thread-774: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-23 16:34:44.454  6505  6505 W Thread-774: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-23 16:34:44.454  6505  6505 W Thread-774: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[28260]" dev="sockfs" ino=28260 scontext=u:r:untrusted_app:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
08-23 16:34:44.470   857  1783 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6540 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-23 16:34:44.486   302   302 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 308us total 22.819ms
,08-23 16:34:44.507  6401  6505 W jxcore-log: Starting JXcore engine
,08-23 16:34:44.512  6488  6488 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-23 16:34:44.512  6488  6488 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-23 16:34:44.515   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 27.170ms
08-23 16:34:44.536   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 21.166ms
,08-23 16:34:44.599  6540  6540 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 16:34:44.599  6540  6540 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 16:34:44.599  6540  6540 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-23 16:34:44.601  6488  6488 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
08-23 16:34:44.689  6488  6488 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-23 16:34:44.690  6488  6488 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-23 16:34:44.705  6488  6488 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,08-23 16:34:44.720  6401  6505 W jxcore-log: Platform android
08-23 16:34:44.720  6401  6505 W jxcore-log: 
08-23 16:34:44.720  6401  6505 W jxcore-log: Process ARCH arm
08-23 16:34:44.720  6401  6505 W jxcore-log: 
,08-23 16:34:44.830   857  1862 I ActivityManager: Process com.google.android.apps.docs (pid 6199) has died
,08-23 16:34:44.837  6540  6540 I AppConfig: Total System Memory = 906309632
08-23 16:34:44.841  6540  6540 I GalleryUtils: Application Heap = 96 MB
,08-23 16:34:44.844  6540  6540 I AppConfig: App Tier : NOT_DEF
08-23 16:34:44.850  6540  6540 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-23 16:34:44.923   857  1783 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6560 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-23 16:34:44.996  6560  6560 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 16:34:44.996  6560  6560 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 16:34:44.996  6560  6560 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-23 16:34:44.997  6560  6560 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-23 16:34:44.997  6560  6560 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-23 16:34:45.000  6401  6505 I jxcore-log: JXcore Cordova bridge is ready!
08-23 16:34:45.000  6401  6505 I jxcore-log: 
08-23 16:34:45.001  6401  6505 W jxcore-log: JXcore engine is started
08-23 16:34:45.004  6401  6453 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-23 16:34:45.008  6401  6401 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-23 16:34:45.070  6560  6560 I SystemConfig: BUILD Country: EU
08-23 16:34:45.070  6560  6560 I SystemConfig: BUILD Operator: OPEN
,08-23 16:34:45.160  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:34:45.160  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:34:45.160  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
,08-23 16:34:45.182   857  1783 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6582 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
08-23 16:34:45.183   857  1783 I ActivityManager: Killing 6102:com.google.android.apps.plus/u0a86 (adj 15): empty #11
08-23 16:34:45.310   857  1884 I ActivityManager: Process com.android.vending (pid 5584) has died
,08-23 16:34:45.312   857  2153 W libprocessgroup: failed to open /acct/uid_10086/pid_6102/cgroup.procs: No such file or directory
08-23 16:34:45.320  6560  6580 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-23 16:34:45.320  6560  6580 I SystemConfig: existFile = false
08-23 16:34:45.321  6560  6580 I SystemConfig: canReadFile = false
08-23 16:34:45.321  6560  6580 I SystemConfig: systemFeature RCS result false
08-23 16:34:45.321  6560  6580 D SystemConfig: refreshRcsSupport() :false
08-23 16:34:45.344  6582  6582 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-23 16:34:45.365  6582  6582 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-23 16:34:45.365  6582  6582 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-23 16:34:45.365  6582  6582 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-23 16:34:45.365  6582  6582 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-23 16:34:45.365  6582  6582 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,08-23 16:34:45.381  3345  6600 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,08-23 16:34:45.422   857  1783 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6601 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 16:34:45.462  3345  6600 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-23 16:34:45.462  3345  6600 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,08-23 16:34:45.497  3345  3690 I Icing   : updateResources: need to parse ozd{com.google.android.gms}
,08-23 16:34:45.561  3345  6622 W IcingInternalCorpora: getNumBytesRead when not calculated.
,08-23 16:34:45.754  1730  3076 I art     : Explicit concurrent mark sweep GC freed 32636(2MB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 14MB/23MB, paused 1.564ms total 103.029ms
,08-23 16:34:45.953  6601  6601 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(225): No need to run daily hygiene.
,08-23 16:34:45.987  6601  6601 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-23 16:34:45.988  6601  6601 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-23 16:34:45.994  6601  6601 I NotificationManager: com.android.vending: cancel(-1050172287) by com.android.vending
08-23 16:34:46.018  6601  6601 I Finsky  : [1] com.google.android.finsky.utils.bp.a(177): Enabling bucket experiment: factor=2.000, zeroDelta=0ms, forceNetwork=false
,08-23 16:34:46.021  2712  5683 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is notificationclass=?; selectionArgs[0] is com.google.android.finsky.download.DownloadBroadcastReceiver; sort is null.
08-23 16:34:46.022  2712  5683 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1e374465 on behalf of 6601
08-23 16:34:46.050  6601  6601 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1265): Installer kick - no action, not running yet
,08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: com.google.android.gms signature not valid.  Found: 
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: MIIEQzCCAyugAwIBAgIJAMLgh0ZkSjCNMA0GCSqGSIb3DQEBBAUAMHQxCzAJBgNVBAYTAlVTMRMw
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: EQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29n
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: bGUgSW5jLjEQMA4GA1UECxMHQW5kcm9pZDEQMA4GA1UEAxMHQW5kcm9pZDAeFw0wODA4MjEyMzEz
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: MzRaFw0zNjAxMDcyMzEzMzRaMHQxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYw
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: FAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29nbGUgSW5jLjEQMA4GA1UECxMHQW5k
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: cm9pZDEQMA4GA1UEAxMHQW5kcm9pZDCCASAwDQYJKoZIhvcNAQEBBQADggENADCCAQgCggEBAKtW
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: LgDYO6IIrgqWbxJOKdoR8qtW0I9Y4sypEwPpt1TTcvZApxsdyxMJZ2JORland2qSGT2y5b+3JKke
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: dxiLDmpHpDsz2WCbdxgxRczfey5YZnTJ4VZbH0xqWVW/8lGmPav5xVwnIiJS6HXk+BVKZF+JcWjA
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: sb/GEuq/eFdpuzSqeYTcfi6idkyugwfYwXFU1+5fZKUaRKYCwkkFQVfcAs1fXA5V+++FGfvjJ/Cx
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: URaSxaBvGdGDhfXE28LWuT9ozCl5xw4Yq5OGazvV24mZVSoOO0yZ31j7kYvtwYK6NeADwbSxDdJE
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: qO4k//0zOHKrUiGYXtqw/A0LFFtqoZKFjnkCAQOjgdkwgdYwHQYDVR0OBBYEFMd9jMIhF1Ylmn/T
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: gt9r45jk14alMIGmBgNVHSMEgZ4wgZuAFMd9jMIhF1Ylmn/Tgt9r45jk14aloXikdjB0MQswCQYD
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: VQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNTW91bnRhaW4gVmlldzEUMBIG
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: A1UEChMLR29vZ2xlIEluYy4xEDAOBgNVBAsTB0FuZHJvaWQxEDAOBgNVBAMTB0FuZHJvaWSCCQDC
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: 4IdGZEowjTAMBgNVHRMEBTADAQH/MA0GCSqGSIb3DQEBBAUAA4IBAQBt0lLO74UwLDYKqs6Tm8/y
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: zKkEu116FmH4rkaymUIE0P9KaMftGlMexFlaYjzmB2OxZyl6euNXEsQH8gjwyxCUKRJNexBiGcCE
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: yj6z+a1fuHHvkiaai+KL8W1EyNmgjmyy8AW7P+LLlkR+ho5zEHatRbM/YAnqGcFh5iZBqpknHf1S
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: KMXFh4dd239FJ1jWYfbMDMy3NS5CTMQ2XFI1MvcyUTdZPErjQfTbQe3aDQsQcafEQPD+nqActifK
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: Z0Np0IS9L9kR/wbNvyz6ENwPiTrjV2KRkEjH78ZMcUQXg0L3BYHJ3lc69Vs5Ddf9uUGGMYldX3Wf
08-23 16:34:46.064  6601  6651 V GoogleSignatureVerifier: MBEmh/9iFBDAaTCK
,08-23 16:34:46.094  6601  6601 I Finsky  : [1] com.google.android.finsky.l.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
08-23 16:34:46.094  6601  6601 I Finsky  : [1] com.google.android.finsky.l.j.run(214): Finished loading 1 libraries.
,08-23 16:34:46.102  1730  1730 D WearableService: callingUid 10006, callindPid: 1730
,08-23 16:34:46.105  6601  6601 I Finsky  : [1] com.google.android.finsky.c.l.a(253): result=false type=4
08-23 16:34:46.142  6601  6601 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
08-23 16:34:46.143  6601  6601 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
,08-23 16:34:46.152  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:34:46.152  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:34:46.152  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
08-23 16:34:46.160   857  2172 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6656 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-23 16:34:46.163  6601  6601 I Finsky  : [1] com.google.android.finsky.services.bd.a(1075): Restore complete with 0 success and 0 failed.
,08-23 16:34:46.256  6656  6656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 16:34:46.319   857  1283 V AlarmManager: RTC_WAKEUP set : Alarm{eb6ca76 type 0 when 1471962886315 com.google.android.googlequicksearchbox} when 1471962886315
,08-23 16:34:46.533  1962  6685 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-23 16:34:46.548   857  1783 I ActivityManager: Killing 6261:com.lge.bnr/1000 (adj 15): empty #11
,08-23 16:34:46.583  1962  6685 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 49 ms] updated apps [took 49 ms] 
,08-23 16:34:46.700   857  1862 W libprocessgroup: failed to open /acct/uid_1000/pid_6261/cgroup.procs: No such file or directory
,08-23 16:34:46.777  3345  3690 I Icing   : Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,08-23 16:34:46.836  3345  3690 I Icing   : Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,08-23 16:34:47.155  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:34:47.155  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:34:47.155  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-23 16:34:47.426   293   348 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-23 16:34:48.156  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:34:48.157  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-23 16:34:48.157  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
08-23 16:34:49.758   857  1291 I ActivityManager: Killing 2890:com.lge.music/u0a28 (adj 15): empty #11
,08-23 16:34:49.780   280  1352 V AudioFlinger: 2890 died, releasing its sessions
08-23 16:34:49.781   280  1352 V AudioFlinger:  pid 1748 @ 0
08-23 16:34:49.781   280  1352 V AudioFlinger:  pid 3166 @ 1
08-23 16:34:49.781   280  1352 V AudioFlinger:  pid 3166 @ 2
,08-23 16:34:49.850   857  2172 W libprocessgroup: failed to open /acct/uid_10028/pid_2890/cgroup.procs: No such file or directory
,08-23 16:34:50.162  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:34:50.162  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:34:50.162  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-23 16:34:50.876   485   485 D charger_monitor: init target 500000
,08-23 16:34:50.886  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:34:50.887  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:34:50.887  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:34:50.887  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:34:50.887  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
08-23 16:34:50.911  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 315
08-23 16:34:50.911  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:34:50.911  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 315
,08-23 16:34:50.914  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:34:50.915  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:34:50.915  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:34:50.915  1802  1986 D LEDHandler: Battery Temp: 315, mChargingStatus=5, mChargingStop=false
08-23 16:34:50.915  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:34:50.916   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:34:50.916   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:34:50.917   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:34:50.920  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 16:34:50.928   485   485 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-23 16:34:50.958  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-23 16:34:51.163  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:34:51.164  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:34:51.164  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-23 16:34:52.165  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:34:52.165  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:34:52.165  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,08-23 16:34:52.431   293   348 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-23 16:34:53.167  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:34:53.167  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:34:53.167  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-23 16:34:55.171  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:34:55.171  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:34:55.171  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-23 16:34:56.175  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:34:56.175  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:34:56.175  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-23 16:34:56.935   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:34:56.935   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:34:56.936   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 133155482766; DSPS: 4462081; Offset : -3019897411
,08-23 16:34:57.174  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:34:57.174  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:34:57.175  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-23 16:34:57.264   857  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{28519949 type 2 when 133480 com.google.android.gms} when 133480
,08-23 16:34:57.293  1730  1730 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-23 16:34:57.436   293   348 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-23 16:34:57.518  3345  6722 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-23 16:34:57.519  3345  6722 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-23 16:34:57.534  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 16:34:57.902   280  1352 I WVCdm   : CdmEngine::OpenSession
08-23 16:34:57.902   280  1352 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
,08-23 16:34:57.942   280  1352 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-23 16:34:57.943   280  1352 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
08-23 16:34:57.943   280  1352 W WVCdm   : L1 library not specified. Falling Back to L3
08-23 16:34:57.982  6313  6328 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-23 16:34:57.983  6313  6328 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-23 16:34:57.984  6313  6328 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-23 16:34:57.985  6313  6328 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-23 16:34:57.985   276  1041 E BandwidthController: [LG DATA] No such appUid: 10006
08-23 16:34:57.985   276  1041 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,08-23 16:34:57.988   276  6734 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-23 16:34:57.988   276  6734 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-23 16:34:57.989   276  6734 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-23 16:34:57.989   276  6734 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-23 16:34:58.025   280  1352 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-23 16:34:58.026   276  6734 D libc-netbsd: res_queryN name = xxxxx succeed
08-23 16:34:58.028  6313  6328 I System.out: propertyValue:false
08-23 16:34:58.028   280  1297 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-23 16:34:58.028   280  1297 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-23 16:34:58.028   280  1297 I WVCdm   : CdmEngine::GenerateKeyRequest
08-23 16:34:58.034   280  1297 D WVCdm   : PrepareKeyRequest: nonce=996933736
08-23 16:34:58.086  6313  6328 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-23 16:34:58.086  6313  6328 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-23 16:34:58.177  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:34:58.177  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:34:58.177  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,08-23 16:34:58.263  1730  1730 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=c9eccd38-55d1-4ab0-bd9f-1951f20df148
,08-23 16:34:58.280  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 16:34:58.281  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-23 16:34:58.443  1730  2556 W GCoreFlp: No location to return for getLastLocation()
,08-23 16:34:58.625   857  1854 I art     : Explicit concurrent mark sweep GC freed 30629(1652KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 21.577ms total 178.982ms
,08-23 16:34:58.638  6313  6328 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 16:34:58.638  6313  6328 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 16:34:58.638  6313  6328 I Adreno-EGL: Build Date: 03/02/15 Mon
08-23 16:34:58.638  6313  6328 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-23 16:34:58.638  6313  6328 I Adreno-EGL: Remote Branch: 
08-23 16:34:58.638  6313  6328 I Adreno-EGL: Local Patches: 
08-23 16:34:58.638  6313  6328 I Adreno-EGL: Reconstruct Branch: 
,08-23 16:34:58.678  3345  6724 D UdcContextInitService: registered all accounts: true
,08-23 16:34:58.703  1730  2514 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 16:34:58.706  6313  6328 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 16:34:58.706  6313  6328 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 16:34:58.706  6313  6328 I Adreno-EGL: Build Date: 03/02/15 Mon
08-23 16:34:58.706  6313  6328 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-23 16:34:58.706  6313  6328 I Adreno-EGL: Remote Branch: 
08-23 16:34:58.706  6313  6328 I Adreno-EGL: Local Patches: 
08-23 16:34:58.706  6313  6328 I Adreno-EGL: Reconstruct Branch: 
08-23 16:34:58.730  1730  2386 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-23 16:34:58.813  6313  6328 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 16:34:58.813  6313  6328 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 16:34:58.813  6313  6328 I Adreno-EGL: Build Date: 03/02/15 Mon
08-23 16:34:58.813  6313  6328 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-23 16:34:58.813  6313  6328 I Adreno-EGL: Remote Branch: 
08-23 16:34:58.813  6313  6328 I Adreno-EGL: Local Patches: 
08-23 16:34:58.813  6313  6328 I Adreno-EGL: Reconstruct Branch: 
,08-23 16:34:59.260  1730  6727 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-23 16:34:59.261  1730  6727 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-23 16:34:59.261  1730  6727 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-23 16:34:59.261  1730  6727 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-23 16:34:59.261   276  1041 E BandwidthController: [LG DATA] No such appUid: 10006
08-23 16:34:59.261   276  1041 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-23 16:34:59.261   276  6742 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
,08-23 16:34:59.261   276  6742 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-23 16:34:59.262   276  6742 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-23 16:34:59.262   276  6742 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-23 16:34:59.262   276  6742 D libc-netbsd: res_queryN name = xxxxx succeed
08-23 16:34:59.263  1730  6727 I System.out: propertyValue:false
08-23 16:34:59.317  1730  6727 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-23 16:34:59.317  1730  6727 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-23 16:34:59.550  1730  6727 I art     : Explicit concurrent mark sweep GC freed 51338(2MB) AllocSpace objects, 15(240KB) LOS objects, 40% free, 14MB/24MB, paused 1.843ms total 104.590ms
,08-23 16:34:59.686  1730  2386 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-23 16:34:59.697  1730  2386 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
08-23 16:34:59.760  1730  6745 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-23 16:34:59.760  1730  6745 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-23 16:34:59.760  1730  6745 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-23 16:34:59.760  1730  6745 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-23 16:34:59.760   276  1041 E BandwidthController: [LG DATA] No such appUid: 10006
08-23 16:34:59.760   276  1041 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-23 16:34:59.761   276  6753 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-23 16:34:59.761   276  6753 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,08-23 16:34:59.761   276  6753 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-23 16:34:59.761   276  6753 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-23 16:34:59.762   276  6753 D libc-netbsd: res_queryN name = xxxxx succeed
08-23 16:34:59.763  1730  6745 I System.out: propertyValue:false
08-23 16:35:00.002   857  1283 D PowerManagerServiceEx: acquireWakeLockInternal: lock=721127928, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,08-23 16:35:00.016  2865  2865 D WeatherService: 2 : TimeTick Intent has been received, Time(hour:min:sec) 16:35:0
08-23 16:35:00.016  2865  2865 D WeatherService: 2 : TimeTick Intent And Screen On
08-23 16:35:00.016  2865  2865 D WeatherService: 2 : SDK version : 21
08-23 16:35:00.018   857  2153 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
08-23 16:35:00.018  2865  2865 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
08-23 16:35:00.019  2865  2865 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
08-23 16:35:00.019  2865  2865 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
08-23 16:35:00.019  2865  2865 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
,08-23 16:35:00.020  2865  2865 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-23 16:35:00.020  2865  2865 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
08-23 16:35:00.020  2865  2865 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
08-23 16:35:00.021  2865  2865 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
08-23 16:35:00.021  2865  2865 D WeatherTheme: 2 : Fixed theme : optimus
08-23 16:35:00.024  2865  2865 D WeatherReflect: 2 : Map key string is -2
08-23 16:35:00.040  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:35:00.040  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-23 16:35:00.044  2865  2865 D lim     : 2 : time = 16:35
08-23 16:35:00.058  2865  2865 I WeatherReflect: Model Name : LG-D722
,08-23 16:35:00.058  2865  2865 D WeatherTheme: 2 : Different view - status_min_formatted : 34 != 35
08-23 16:35:00.058  2865  2865 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
08-23 16:35:00.059  2865  2865 D WeatherReflect: 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
08-23 16:35:00.066  2865  2865 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-23 16:35:00.066  2865  2865 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-23 16:35:00.066  2865  2865 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-23 16:35:00.066  2865  2865 D Weather4x2_optimus: currentPackage=com.lge.sizechangable.weather.theme.optimus
08-23 16:35:00.074  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:35:00.077  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:35:00.079  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:35:00.080  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:35:00.081  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:35:00.142  2865  2865 D Weather4x2_optimus: [[[[[[Theme package!!]]]]]] RemoteViews are created 2
08-23 16:35:00.142  2865  2865 D Weather4x2_optimus: widgetType = 1, orientation = 1
08-23 16:35:00.142  2865  2865 D Weather4x2_optimus: forecast size is 0
,08-23 16:35:00.145  2865  2865 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-23 16:35:00.145  2865  2865 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-23 16:35:00.145  2865  2865 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-23 16:35:00.145  2865  2865 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-23 16:35:00.145  2865  2865 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-23 16:35:00.145  2865  2865 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-23 16:35:00.146  2865  2865 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-23 16:35:00.146  2865  2865 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-23 16:35:00.146  2865  2865 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-23 16:35:00.146  2865  2865 I Theme_WeatherAncestor_optimus: WEATHER_CP_ACCU : 
08-23 16:35:00.146  2865  2865 I Theme_WeatherAncestor_optimus: weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
08-23 16:35:00.146  2865  2865 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-23 16:35:00.146  2865  2865 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-23 16:35:00.146  2865  2865 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-23 16:35:00.146  2865  2865 D Theme_WeatherAncestor_optimus: setTouchIntent, appWidgetId: 2
08-23 16:35:00.150  2865  2865 D Theme_WeatherAncestor_optimus: url is : null
08-23 16:35:00.155  2865  2865 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-23 16:35:00.155  2865  2865 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-23 16:35:00.155  2865  2865 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-23 16:35:00.155  2865  2865 D WeatherAncestor: 2 : update view, appWidgetId: 2
08-23 16:35:00.159  2865  2865 D WeatherService: 2 : TimeTick Intent has been processed, Time(hour:min:sec) 16:35:0
,08-23 16:35:00.171   857   857 D PowerManagerServiceEx: releaseWakeLockInternal: lock=721127928 [*alarm*], flags=0x0
08-23 16:35:00.211  1730  2386 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-23 16:35:00.334  1875  1875 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,08-23 16:35:00.350   280   280 I WVCdm   : CdmEngine::CloseSession
,08-23 16:35:00.355   280   280 I WVCdm   : L3 Terminate.
08-23 16:35:00.420  1730  6766 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-23 16:35:00.421  1730  6761 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-23 16:35:00.442  1730  6766 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-23 16:35:00.442  1730  6761 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-23 16:35:00.455  1875  1875 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-23 16:35:00.464  1730  6766 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-23 16:35:00.465  1730  6761 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-23 16:35:00.465  1730  6761 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
08-23 16:35:00.470  1730  6761 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-23 16:35:00.521  4019  4037 I art     : Explicit concurrent mark sweep GC freed 2150(78KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.208ms total 27.246ms
,08-23 16:35:00.540   857   886 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 16:35:00.627  1730  6761 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-23 16:35:00.628  1730  6761 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-23 16:35:00.628  1730  6761 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-23 16:35:00.628  1730  6761 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-23 16:35:00.628   276  1041 E BandwidthController: [LG DATA] No such appUid: 10006
08-23 16:35:00.628   276  1041 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-23 16:35:00.629   276  6767 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-23 16:35:00.629   276  6767 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-23 16:35:00.629   276  6767 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-23 16:35:00.629   276  6767 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-23 16:35:00.629   276  6767 D libc-netbsd: res_queryN name = xxxxx succeed
08-23 16:35:00.631  1730  6761 I System.out: propertyValue:false
08-23 16:35:00.923   857  1884 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 16:35:01.215   857  1854 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 16:35:01.448   857  1884 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 16:35:01.676   857  1862 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 16:35:01.908  6401  6505 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 16:35:01.908  6401  6505 I jxcore-log: 
,08-23 16:35:01.920  6401  6505 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 16:35:01.920  6401  6505 I jxcore-log: 
08-23 16:35:01.932  2033  3812 D BluetoothAdapterService(608638308): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17afa1da
,08-23 16:35:01.933  6401  6505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 16:35:01.933  6401  6505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 16:35:01.933  6401  6505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 16:35:01.933  6401  6505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 16:35:01.933  6401  6505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 16:35:01.933  6401  6505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 16:35:01.933  6401  6505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 16:35:01.933  6401  6505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 16:35:01.944  2033  3812 D BluetoothAdapterService(608638308): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17afa1da
,08-23 16:35:01.957  6401  6505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 16:35:01.964  6401  6505 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 16:35:01.964  6401  6505 I jxcore-log: 
08-23 16:35:01.978  6401  6505 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 16:35:01.978  6401  6505 I jxcore-log: 
,08-23 16:35:02.044  1730  2386 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-23 16:35:02.440   293   348 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-23 16:35:02.828  6401  6505 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-23 16:35:02.829  6401  6505 I jxcore-log: Failed to execute UT.
08-23 16:35:02.829  6401  6505 I jxcore-log: 
08-23 16:35:02.831  6401  6505 I jxcore-log: Unit Test app is loaded
08-23 16:35:02.831  6401  6505 I jxcore-log: 
,08-23 16:35:02.839  6401  6505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 16:35:02.839  6401  6505 I jxcore-log: 
,08-23 16:35:02.849  6401  6505 I jxcore-log: My device name is: LGE-LG-D722
08-23 16:35:02.849  6401  6505 I jxcore-log: 
08-23 16:35:02.851  6401  6505 I jxcore-log: WARN testUtils: myNameCallback not set!
08-23 16:35:02.851  6401  6505 I jxcore-log: 
08-23 16:35:02.855  6401  6401 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-23 16:35:03.184  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:35:03.185  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:35:03.185  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-23 16:35:04.186  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:35:04.186  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:35:04.186  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-23 16:35:04.211   857  1825 I ActivityManager: Killing 6466:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,08-23 16:35:04.300   857   885 W libprocessgroup: failed to open /acct/uid_10038/pid_6466/cgroup.procs: No such file or directory
,08-23 16:35:05.188  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:35:05.189  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:35:05.189  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-23 16:35:05.972  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:35:05.972  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:35:05.973  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:35:05.973  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:35:05.975  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:35:05.992   485   485 D charger_monitor: init target 500000
,08-23 16:35:06.028  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 16:35:06.028  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:35:06.028  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:35:06.028  1802  1986 D LEDHandler: Battery Temp: 316, mChargingStatus=5, mChargingStop=false
,08-23 16:35:06.031  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 316
08-23 16:35:06.031  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:35:06.031  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 316
08-23 16:35:06.032  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:35:06.032  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:35:06.035  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:35:06.035   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:35:06.035   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:35:06.035   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:35:06.052   485   485 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-23 16:35:06.086  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 316
08-23 16:35:06.086  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:35:06.086  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 316
,08-23 16:35:06.087  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:35:06.087  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:35:06.088  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 16:35:06.088   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:35:06.089   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:35:06.089   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:35:06.089  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:35:06.089  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:35:06.089  1802  1986 D LEDHandler: Battery Temp: 316, mChargingStatus=5, mChargingStop=false
08-23 16:35:06.090  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:35:06.190  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:35:06.190  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:35:06.190  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-23 16:35:07.193  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:35:07.193  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:35:07.193  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-23 16:35:07.445   293   348 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-23 16:35:09.364  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-23 16:35:09.364  6401  6505 I jxcore-log: 
,08-23 16:35:10.196  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:35:10.196  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:35:10.196  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-23 16:35:10.317   857  1053 I PowerManagerService: ALS enabled for SRE
,08-23 16:35:10.319   857  1053 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26538 ms ago)
08-23 16:35:10.377   857  1346 D qdlights: set_light_backlight: 253
,08-23 16:35:10.386   857  1346 D qdlights: set_light_backlight: 250
08-23 16:35:10.403   857  1346 D qdlights: set_light_backlight: 246
,08-23 16:35:10.420   857  1346 D qdlights: set_light_backlight: 243
,08-23 16:35:10.436   857  1346 D qdlights: set_light_backlight: 240
,08-23 16:35:10.453   857  1346 D qdlights: set_light_backlight: 236
,08-23 16:35:10.470   857  1346 D qdlights: set_light_backlight: 233
,08-23 16:35:10.486   857  1346 D qdlights: set_light_backlight: 230
,08-23 16:35:10.503   857  1346 D qdlights: set_light_backlight: 226
,08-23 16:35:10.520   857  1346 D qdlights: set_light_backlight: 223
,08-23 16:35:10.536   857  1346 D qdlights: set_light_backlight: 220
,08-23 16:35:10.553   857  1346 D qdlights: set_light_backlight: 216
,08-23 16:35:10.570   857  1346 D qdlights: set_light_backlight: 213
,08-23 16:35:10.586   857  1346 D qdlights: set_light_backlight: 210
,08-23 16:35:10.603   857  1346 D qdlights: set_light_backlight: 206
,08-23 16:35:10.620   857  1346 D qdlights: set_light_backlight: 203
,08-23 16:35:10.636   857  1346 D qdlights: set_light_backlight: 200
,08-23 16:35:10.653   857  1346 D qdlights: set_light_backlight: 196
,08-23 16:35:10.670   857  1346 D qdlights: set_light_backlight: 193
,08-23 16:35:10.686   857  1346 D qdlights: set_light_backlight: 190
08-23 16:35:10.703   857  1346 D qdlights: set_light_backlight: 186
,08-23 16:35:10.720   857  1346 D qdlights: set_light_backlight: 183
,08-23 16:35:10.736   857  1346 D qdlights: set_light_backlight: 180
,08-23 16:35:10.753   857  1346 D qdlights: set_light_backlight: 176
,08-23 16:35:10.770   857  1346 D qdlights: set_light_backlight: 173
,08-23 16:35:10.786   857  1346 D qdlights: set_light_backlight: 170
,08-23 16:35:10.803   857  1346 D qdlights: set_light_backlight: 166
,08-23 16:35:10.820   857  1346 D qdlights: set_light_backlight: 163
,08-23 16:35:10.836   857  1346 D qdlights: set_light_backlight: 160
,08-23 16:35:10.853   857  1346 D qdlights: set_light_backlight: 156
,08-23 16:35:10.870   857  1346 D qdlights: set_light_backlight: 153
,08-23 16:35:10.886   857  1346 D qdlights: set_light_backlight: 150
,08-23 16:35:10.889  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-23 16:35:10.889  6401  6505 I jxcore-log: 
08-23 16:35:10.903   857  1346 D qdlights: set_light_backlight: 146
,08-23 16:35:10.920   857  1346 D qdlights: set_light_backlight: 143
,08-23 16:35:10.928  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-23 16:35:10.928  6401  6505 I jxcore-log: 
08-23 16:35:10.934  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-23 16:35:10.934  6401  6505 I jxcore-log: 
08-23 16:35:10.936   857  1346 D qdlights: set_light_backlight: 140
,08-23 16:35:10.953   857  1346 D qdlights: set_light_backlight: 136
,08-23 16:35:10.960  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-23 16:35:10.960  6401  6505 I jxcore-log: 
08-23 16:35:10.966  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-23 16:35:10.966  6401  6505 I jxcore-log: 
,08-23 16:35:10.971   857  1346 D qdlights: set_light_backlight: 133
08-23 16:35:10.986   857  1346 D qdlights: set_light_backlight: 130
,08-23 16:35:11.003   857  1346 D qdlights: set_light_backlight: 126
,08-23 16:35:11.020   857  1346 D qdlights: set_light_backlight: 123
,08-23 16:35:11.050   857  1346 D qdlights: set_light_backlight: 120
,08-23 16:35:11.053   857  1346 D qdlights: set_light_backlight: 116
08-23 16:35:11.070   857  1346 D qdlights: set_light_backlight: 113
,08-23 16:35:11.086   857  1346 D qdlights: set_light_backlight: 110
,08-23 16:35:11.103   857  1346 D qdlights: set_light_backlight: 106
,08-23 16:35:11.121   857  1346 D qdlights: set_light_backlight: 103
,08-23 16:35:11.136   857  1346 D qdlights: set_light_backlight: 100
,08-23 16:35:11.153   857  1346 D qdlights: set_light_backlight: 96
,08-23 16:35:11.170   857  1346 D qdlights: set_light_backlight: 93
,08-23 16:35:11.186   857  1346 D qdlights: set_light_backlight: 90
,08-23 16:35:11.198  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:35:11.198  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:35:11.198  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-23 16:35:11.203   857  1346 D qdlights: set_light_backlight: 86
08-23 16:35:11.220   857  1346 D qdlights: set_light_backlight: 83
,08-23 16:35:11.236   857  1346 D qdlights: set_light_backlight: 80
,08-23 16:35:11.253   857  1346 D qdlights: set_light_backlight: 76
,08-23 16:35:11.269   857  1346 D qdlights: set_light_backlight: 73
,08-23 16:35:11.286   857  1346 D qdlights: set_light_backlight: 70
,08-23 16:35:11.303   857  1346 D qdlights: set_light_backlight: 66
,08-23 16:35:11.319   857  1346 D qdlights: set_light_backlight: 63
,08-23 16:35:11.336   857  1346 D qdlights: set_light_backlight: 60
,08-23 16:35:11.353   857  1346 D qdlights: set_light_backlight: 56
,08-23 16:35:11.369   857  1346 D qdlights: set_light_backlight: 53
,08-23 16:35:11.386   857  1346 D qdlights: set_light_backlight: 50
,08-23 16:35:11.403   857  1346 D qdlights: set_light_backlight: 46
,08-23 16:35:11.419   857  1346 D qdlights: set_light_backlight: 43
,08-23 16:35:11.436   857  1346 D qdlights: set_light_backlight: 40
,08-23 16:35:11.453   857  1346 D qdlights: set_light_backlight: 36
,08-23 16:35:11.469   857  1346 D qdlights: set_light_backlight: 33
,08-23 16:35:11.486   857  1346 D qdlights: set_light_backlight: 30
,08-23 16:35:11.503   857  1346 D qdlights: set_light_backlight: 26
,08-23 16:35:11.519   857  1346 D qdlights: set_light_backlight: 23
,08-23 16:35:11.536   857  1346 D qdlights: set_light_backlight: 20
,08-23 16:35:11.553   857  1346 D qdlights: set_light_backlight: 16
,08-23 16:35:11.569   857  1346 D qdlights: set_light_backlight: 13
,08-23 16:35:11.587   857  1346 D qdlights: set_light_backlight: 10
,08-23 16:35:12.200  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:35:12.200  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:35:12.200  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-23 16:35:12.450   293   348 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-23 16:35:14.204  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,08-23 16:35:14.204  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:35:14.204  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-23 16:35:15.206  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:35:15.206  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-23 16:35:15.206  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-23 16:35:16.051  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-23 16:35:16.051  6401  6505 I jxcore-log: 
,08-23 16:35:16.069  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-23 16:35:16.069  6401  6505 I jxcore-log: 
,08-23 16:35:16.082  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-23 16:35:16.082  6401  6505 I jxcore-log: 
,08-23 16:35:16.330  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-23 16:35:16.330  6401  6505 I jxcore-log: 
,08-23 16:35:16.936   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:35:16.936   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:35:16.936   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 153156416821; DSPS: 5117471; Offset : -3019877242
,08-23 16:35:17.210  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:35:17.210  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-23 16:35:17.210  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-23 16:35:17.319   857  1053 I PowerManagerService: ALS enabled for SRE
08-23 16:35:17.319   857  1053 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33539 ms ago)
,08-23 16:35:17.323   857  1053 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
08-23 16:35:17.338   857  1053 I PowerManagerService: ALS enabled for SRE
08-23 16:35:17.338   857  1053 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33558 ms ago)
,08-23 16:35:17.350   857  1053 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,08-23 16:35:17.359   857  1053 I PowerManagerService: Sleeping (uid 1000)...
08-23 16:35:17.359   857  1053 D LPWGController: [updateScreenState] screen on = false
08-23 16:35:17.369   857  1053 D LPWGController: disable proximity sensor
08-23 16:35:17.369   857  1053 D LPWGController: enable proximity sensor
,08-23 16:35:17.389   857  1053 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@1baa7cd3] by com.android.server.power.ProximitySensorListener.enable():120
,08-23 16:35:17.399   857  1053 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
08-23 16:35:17.399   857  1053 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
08-23 16:35:17.399   857  1053 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
08-23 16:35:17.399   857  1053 I sensors_hal_Ctx: activate: handle is 48, enable
08-23 16:35:17.400   857  1053 V sensors_hal_Ctx: activate sensors is 1400000000000
08-23 16:35:17.400   857  1053 D sensors_hal_Thresh: enable: handle=48
08-23 16:35:17.400   857  1053 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
08-23 16:35:17.400   857  1053 D sensors_hal_Util: waitForResponse: timeout=1000
08-23 16:35:17.407   857   999 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
08-23 16:35:17.407   857   999 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
08-23 16:35:17.407   857  1053 D sensors_hal_Thresh: enable: Received response: 0
,08-23 16:35:17.407   857  1053 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33628 ms ago)
,08-23 16:35:17.440   857  1053 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 16:35:17.440   857  1053 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 16:35:17.440   857  1053 I Adreno-EGL: Build Date: 03/02/15 Mon
08-23 16:35:17.440   857  1053 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-23 16:35:17.440   857  1053 I Adreno-EGL: Remote Branch: 
08-23 16:35:17.440   857  1053 I Adreno-EGL: Local Patches: 
08-23 16:35:17.440   857  1053 I Adreno-EGL: Reconstruct Branch: 
,08-23 16:35:17.454   293   348 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-23 16:35:17.472   243  1348 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1413 us)
,08-23 16:35:17.635   420   983 I Sensors : sns_pwr.c(273):acquiring wakelock
,08-23 16:35:17.637   857   999 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
08-23 16:35:17.638   857   999 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
08-23 16:35:17.638   857   999 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
08-23 16:35:17.638   857   999 D sensors_hal_Thresh: processInd: handle 48, count=1
08-23 16:35:17.638   857   999 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
08-23 16:35:17.638   857   999 I sensors_hal_Thresh: processInd : proximity state changed - FAR
08-23 16:35:17.638   857  1035 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
08-23 16:35:17.638   857  1035 D sensors_hal_Ctx: poll: count: 256
08-23 16:35:17.638   857  1035 I sensors_hal_Ctx: poll: released wakelock sensor_ind
08-23 16:35:17.638   857  1035 D sensors_hal_Util: waitForResponse: timeout=0
08-23 16:35:17.642   857  1053 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
08-23 16:35:17.642   857  1053 I LPWGController: current mode = 1  value = 1 1
08-23 16:35:17.643   857  1053 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
08-23 16:35:17.746   857  1053 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,08-23 16:35:17.760   857  1801 I ActivityManager: Process com.google.android.talk (pid 6488) has died
,08-23 16:35:17.801  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-23 16:35:17.801  6401  6505 I jxcore-log: 
,08-23 16:35:18.006   857  1346 D qdlights: set_light_backlight: 0
,08-23 16:35:18.024   857  1053 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,08-23 16:35:18.030   857  1053 I sensors_hal_Ctx: activate: handle is 46, disable
08-23 16:35:18.030   857  1053 V sensors_hal_Ctx: activate sensors is 1000000000000
08-23 16:35:18.030   857  1053 D sensors_hal_LP2: enable: handle=46
08-23 16:35:18.030   857  1053 D sensors_hal_LP2: enable: Disabling sensor handle=46
08-23 16:35:18.030   857  1053 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
08-23 16:35:18.032   243   243 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
08-23 16:35:18.033   243   243 D qdhwcomposer: hwc_blank: Blanking display: 0
08-23 16:35:18.042   857  1051 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
08-23 16:35:18.043   857   857 V ActivityManager: Display changed displayId=0
,08-23 16:35:18.110  1748  1748 D DSDPConnection: Display #0 changed.
,08-23 16:35:18.150   857  1025 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
08-23 16:35:18.150   857  1025 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,08-23 16:35:18.211  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-23 16:35:18.211  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-23 16:35:18.211  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-23 16:35:18.222   243   243 D qdhwcomposer: hwc_blank: Done blanking display: 0
08-23 16:35:18.223   857  1346 D SurfaceControl: Excessive delay in setPowerMode(): 190ms
,08-23 16:35:18.224   243   689 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
08-23 16:35:18.227   857  1346 I QCOM PowerHAL: Got set_interactive hint
08-23 16:35:18.236  6401  6401 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-23 16:35:18.236  6401  6401 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
08-23 16:35:18.238  1374  2549 D KeyguardViewMediator: onScreenTurnedOff(3)
,08-23 16:35:18.248  1329  1344 D SmartCoverViewMediator: onScreenTurnedOff(3)
08-23 16:35:18.254  1374  2549 D KeyguardViewMediator: notifyScreenOffLocked
,08-23 16:35:18.256  1329  1344 D SmartCoverViewMediator: notifyScreenOffLocked
08-23 16:35:18.257  1329  1329 D SmartCoverViewMediator: handleNotifyScreenOFF
08-23 16:35:18.271  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-23 16:35:18.271  6401  6505 I jxcore-log: 
,08-23 16:35:18.275  6401  6401 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@393dacfc Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2c0a6964, 16908290=android.view.AbsSavedState$1@2c0a6964}, android:focusedViewId=100}]}]
08-23 16:35:18.275  6401  6401 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-23 16:35:18.276  6401  6401 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-23 16:35:18.276  6401  6401 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-23 16:35:18.279  1374  2549 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
08-23 16:35:18.280  1374  1374 D KeyguardViewMediator: handleNotifyScreenOff
08-23 16:35:18.286  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-23 16:35:18.286  6401  6505 I jxcore-log: 
,08-23 16:35:18.300  1374  1374 D ScreenTurnOffBySensor: unregisterProximitySensor
,08-23 16:35:18.317  1374  1374 D StatusBarWindowView: onScreenTurnedOff why = 3
,08-23 16:35:18.326   857   857 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
08-23 16:35:18.331   280  1297 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 857
,08-23 16:35:18.333   280  1297 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-23 16:35:18.333   280  1297 V voice   : voice_set_parameters: enter: screen_state=on
08-23 16:35:18.335   280  1297 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
08-23 16:35:18.335   280  1297 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-23 16:35:18.335   280  1297 V voice   : voice_set_parameters: exit with code(0)
08-23 16:35:18.335   280  1297 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
08-23 16:35:18.335   280  1297 V msm8974_platform: platform_set_parameters: enter: screen_state=on
08-23 16:35:18.335   280  1297 V msm8974_platform: platform_set_parameters: exit with code(0)
08-23 16:35:18.335   280  1297 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-23 16:35:18.336   280  1297 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
08-23 16:35:18.336   280  1297 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-23 16:35:18.336   280  1297 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-23 16:35:18.341  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:35:18.344   857  1306 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
,08-23 16:35:18.347  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
08-23 16:35:18.611  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-23 16:35:18.611  6401  6505 I jxcore-log: 
,08-23 16:35:18.646  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-23 16:35:18.646  6401  6505 I jxcore-log: 
,08-23 16:35:18.653   857   990 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
08-23 16:35:18.656  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-23 16:35:18.656  6401  6505 I jxcore-log: 
08-23 16:35:18.657  1837  1837 I QCNEJ   : |CORE| sendScreenState: state:true
08-23 16:35:18.667  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-23 16:35:18.667  6401  6505 I jxcore-log: 
08-23 16:35:18.668  1802  1986 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
,08-23 16:35:18.672  1802  1986 D LEDService: stopPatternFlashing()
08-23 16:35:18.675  1802  1986 D qdlights: set_light_notifications: 0,0,0,0,3
08-23 16:35:18.677  1802  1986 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-23 16:35:18.677  1802  1986 D qdlights: set_light_notifications: 0,0,0,0,3
08-23 16:35:18.679  1802  1986 I LEDService: updateLightsLocked : turn off led
08-23 16:35:18.679  1802  1986 D qdlights: set_light_notifications: 0,0,0,0,3
,08-23 16:35:18.683  1802  1986 D LEDHandler: RESTART MSG
08-23 16:35:18.698  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-23 16:35:18.698  6401  6505 I jxcore-log: 
,08-23 16:35:18.714   857  5504 D SplitWindow: check instance of lgWin Window{1d405d0e u0 SearchPanel}
,08-23 16:35:18.721  1802  1802 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
08-23 16:35:18.722  1802  1802 D Cliptray Service: lockStatus = 0
08-23 16:35:18.732   857  1874 D InputDispatcher: Window went away: Window{1f6c5028 u0 SearchPanel}
,08-23 16:35:18.735  1374  1374 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
08-23 16:35:18.743  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-23 16:35:18.743  6401  6505 I jxcore-log: 
08-23 16:35:18.754  1374  1374 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,08-23 16:35:18.761  1784  1784 D LNfcService: action : android.intent.action.SCREEN_ON
,08-23 16:35:18.772  1784  6810 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
08-23 16:35:18.772  1784  6810 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
08-23 16:35:18.772  1784  6810 D LNfcService: isRequireNfcCRouting() return true
08-23 16:35:18.772  1784  6810 D LNfcService: isHCERoutingtoHost() return : true
08-23 16:35:18.773  1784  6810 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-23 16:35:18.773  1784  6810 D NfcService: mEnableLPD: true
08-23 16:35:18.773  1784  6810 D NfcService: mEnableReader: false
08-23 16:35:18.773  1784  6810 D NfcService: mEnableHostRouting: true
08-23 16:35:18.773  1784  6810 D NfcService: newParams.techmask= mTechMask: default
08-23 16:35:18.773  1784  6810 D NfcService: mEnableLPD: true
08-23 16:35:18.773  1784  6810 D NfcService: mEnableReader: false
08-23 16:35:18.773  1784  6810 D NfcService: mEnableHostRouting: true
08-23 16:35:18.773  1784  6810 D NfcService: screenState= 3
08-23 16:35:18.773  1784  6810 D NfcService: Discovery configuration equal, not updating.
08-23 16:35:18.783   857   857 D Ulp_jni : JNI:system_update. Event-0
,08-23 16:35:18.813  1748  1748 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,08-23 16:35:18.826   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:35:18.826   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:35:18.826   857   857 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
,08-23 16:35:18.831  2865  2865 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:35:18
08-23 16:35:18.833  2865  2865 D WeatherService: 2 : ACTION screen on
08-23 16:35:18.835  2865  2865 D WeatherService: 2 : shouldTimeTickRegistered : false
08-23 16:35:18.841  2865  2865 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-23 16:35:18.841  2865  2865 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:35:18
,08-23 16:35:18.854  4143  4143 D AppCleanupService: android.intent.action.SCREEN_ON
,08-23 16:35:18.877   280   280 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 857
08-23 16:35:18.877   280   280 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-23 16:35:18.877   280   280 V voice   : voice_set_parameters: enter: screen_state=off
08-23 16:35:18.877   280   280 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
08-23 16:35:18.878   280   280 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-23 16:35:18.878   280   280 V voice   : voice_set_parameters: exit with code(0)
08-23 16:35:18.878   280   280 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
08-23 16:35:18.878   280   280 V msm8974_platform: platform_set_parameters: enter: screen_state=off
08-23 16:35:18.878   280   280 V msm8974_platform: platform_set_parameters: exit with code(0)
08-23 16:35:18.878   280   280 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-23 16:35:18.878   280   280 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-23 16:35:18.878   280   280 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-23 16:35:18.880   857  1314 D WifiController: CMD_SCREEN_OFF 
08-23 16:35:18.880   857  1314 D WifiController: shouldWifiStayAwake TRUE
08-23 16:35:18.882  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
08-23 16:35:18.883   857   990 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
08-23 16:35:18.917  1837  1837 I QCNEJ   : |CORE| sendScreenState: state:false
,08-23 16:35:18.921  1802  1986 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
08-23 16:35:18.921  1802  1802 D VolumeVibrator: clear
08-23 16:35:18.921  1802  1986 D LEDService: stopPatternFlashing()
08-23 16:35:18.921  1802  1986 D qdlights: set_light_notifications: 0,0,0,0,3
08-23 16:35:18.923  1802  1986 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-23 16:35:18.923  1802  1986 D qdlights: set_light_notifications: 0,0,0,0,3
08-23 16:35:18.925  1802  1986 I LEDService: updateLightsLocked : turn on led
08-23 16:35:18.925  1802  1986 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
08-23 16:35:18.925  1802  1986 E LEDService: Can't handle this request of patternId:0
08-23 16:35:18.925  1802  1986 D LEDHandler: RESTART MSG
08-23 16:35:18.926  1802  1802 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
08-23 16:35:18.927  1784  1784 D LNfcService: action : android.intent.action.SCREEN_OFF
08-23 16:35:18.930  1784  2218 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
,08-23 16:35:18.950  1875  1875 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,08-23 16:35:18.953  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-23 16:35:18.953  6401  6505 I jxcore-log: 
08-23 16:35:18.963  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-23 16:35:18.963  6401  6505 I jxcore-log: 
08-23 16:35:18.965  1748  1748 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,08-23 16:35:18.971   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:35:18.971   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:35:18.971   857   857 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
08-23 16:35:18.973  2865  2865 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:35:18
,08-23 16:35:18.973  2865  2865 D WeatherService: 2 : ACTION screen off
08-23 16:35:18.974  2865  2865 D WeatherService: 2 : TimeTick Receiver Unregister
08-23 16:35:18.975  2865  2865 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:35:18
08-23 16:35:18.978  4143  4143 D AppCleanupService: android.intent.action.SCREEN_OFF
08-23 16:35:18.981  4143  6813 D AppCleanupService: AppUsageStatsSaveTask
,08-23 16:35:19.024  6401  6505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-23 16:35:19.024  6401  6505 I jxcore-log: 
,08-23 16:35:19.038  2033  2053 D BluetoothAdapterService(608638308): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17afa1da
08-23 16:35:19.039  6401  6505 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
08-23 16:35:19.041  1784  2704 E NxpNfcJni: getReconnectState = 0x0
08-23 16:35:19.041  6401  6505 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-23 16:35:19.041  6401  6505 I jxcore-log: 
08-23 16:35:19.042  1784  2218 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-23 16:35:19.043  1784  2218 D LCardEmulationManager: getDefaultRoute
08-23 16:35:19.043  1784  2218 D LNfcService: isRequireNfcCRouting() return true
08-23 16:35:19.043  1784  2218 D LNfcService: isHCERoutingtoHost() return : true
08-23 16:35:19.043  1784  2218 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-23 16:35:19.043  1784  2218 D NfcService: mEnableLPD: true
08-23 16:35:19.043  1784  2218 D NfcService: mEnableReader: false
08-23 16:35:19.043  1784  2218 D NfcService: mEnableHostRouting: true
08-23 16:35:19.043  1784  2218 D NfcService: newParams.techmask= mTechMask: 0
08-23 16:35:19.043  1784  2218 D NfcService: mEnableLPD: true
08-23 16:35:19.043  1784  2218 D NfcService: mEnableReader: false
08-23 16:35:19.043  1784  2218 D NfcService: mEnableHostRouting: true
08-23 16:35:19.043  1784  2218 D NfcService: screenState= 1
08-23 16:35:19.104  1784  2704 E NxpNfcJni: getReconnectState = 0x0
,08-23 16:35:19.135   420   435 I Sensors : sns_pwr.c(301):releasing wakelock
,08-23 16:35:22.459   293   348 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-23 16:35:23.266  1374  1374 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,08-23 16:35:23.272   857  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1796132f type 2 when 159480 com.android.systemui} when 159480
,08-23 16:35:23.294  1748  1763 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
08-23 16:35:23.299  1748  1763 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-23 16:35:23.299  1748  1763 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-23 16:35:23.303  1748  1763 V TelecomServiceImpl: getCallState : 0
,08-23 16:35:23.308  1748  1764 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
08-23 16:35:23.308  1748  1764 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-23 16:35:23.308  1748  1764 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-23 16:35:23.311  1374  1374 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
08-23 16:35:23.311  1374  1374 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
08-23 16:35:27.463   293   348 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-23 16:35:32.468   293   348 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-23 16:35:36.937   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:35:36.937   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:35:36.937   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 173157143740; DSPS: 5772855; Offset : -3019882746
,08-23 16:35:37.477   293   348 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-23 16:35:37.763  3345  4358 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-23 16:35:42.481   293   348 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-23 16:35:45.978  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:35:45.978  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:35:45.978  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:35:45.978  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:35:45.986  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:35:45.990   485   485 D charger_monitor: init target 500000
,08-23 16:35:45.995   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:35:46.030  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:35:46.033  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 310
08-23 16:35:46.034  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:35:46.034  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:35:46.036  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:35:46.036  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:35:46.036  1802  1986 D LEDHandler: Battery Temp: 310, mChargingStatus=5, mChargingStop=false
08-23 16:35:46.037  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:35:46.037  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 310
08-23 16:35:46.040  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:35:46.043   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:35:46.043   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:35:46.047   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:35:46.090  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:35:46.093  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 311
08-23 16:35:46.093  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:35:46.093  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 311
08-23 16:35:46.094  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:35:46.094  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:35:46.095  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:35:46.095  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:35:46.095  1802  1986 D LEDHandler: Battery Temp: 311, mChargingStatus=5, mChargingStop=false
08-23 16:35:46.098  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:35:46.102   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:35:46.102   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:35:46.103   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:35:47.486   293   348 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-23 16:35:48.990   857  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{a18ad3c type 2 when 185203 com.google.android.gms} when 185203
,08-23 16:35:51.036   485   485 D charger_monitor: init target 500000
,08-23 16:35:51.041   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:35:51.048  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:35:51.048  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:35:51.048  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:35:51.048  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:35:51.051  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:35:51.090  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 311
,08-23 16:35:51.093  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:35:51.093  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 311
08-23 16:35:51.096  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:35:51.096  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:35:51.098  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:35:51.098  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:35:51.098  1802  1986 D LEDHandler: Battery Temp: 311, mChargingStatus=5, mChargingStop=false
08-23 16:35:51.102  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:35:51.104  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:35:51.110   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:35:51.110   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:35:51.110   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:35:52.490   293   348 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-23 16:35:56.938   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:35:56.938   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:35:56.938   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 193157733420; DSPS: 6428234; Offset : -3019873655
,08-23 16:35:57.495   293   348 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-23 16:36:00.074  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:36:00.074  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:36:00.074  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:36:00.079  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:36:00.079  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:36:00.080  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:36:00.081  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:36:02.499   293   348 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-23 16:36:07.504   293   348 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-23 16:36:12.509   293   348 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-23 16:36:16.938   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:36:16.938   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:36:16.938   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 213158509714; DSPS: 7083620; Offset : -3019890037
,08-23 16:36:17.513   293   348 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-23 16:36:22.518   293   348 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-23 16:36:27.522   293   348 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-23 16:36:31.135   857  1283 D PowerManagerServiceEx: acquireWakeLockInternal: lock=721127928, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,08-23 16:36:31.139   857  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{9b23ac5 type 2 when 213779 android} when 213779
08-23 16:36:31.273   857   857 D PowerManagerServiceEx: releaseWakeLockInternal: lock=721127928 [*alarm*], flags=0x0
,08-23 16:36:32.527   293   348 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-23 16:36:36.939   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:36:36.939   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:36:36.939   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 233159193301; DSPS: 7739002; Offset : -3019877602
,08-23 16:36:37.531   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:36:42.536   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:36:45.983  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:36:45.984  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:36:45.984  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:36:45.984  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:36:45.991  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:36:45.993   485   485 D charger_monitor: init target 500000
08-23 16:36:45.998   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-23 16:36:46.033  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 307
08-23 16:36:46.033  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:36:46.033  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 307
,08-23 16:36:46.037  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 16:36:46.037  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:36:46.037  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:36:46.039  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:36:46.039  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:36:46.039  1802  1986 D LEDHandler: Battery Temp: 307, mChargingStatus=5, mChargingStop=false
08-23 16:36:46.041  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:36:46.043   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:36:46.043   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:36:46.044   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:36:46.085  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:36:46.089  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:36:46.090  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:36:46.091  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:36:46.091  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:36:46.091  1802  1986 D LEDHandler: Battery Temp: 307, mChargingStatus=5, mChargingStop=false
08-23 16:36:46.091  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 307
08-23 16:36:46.091  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:36:46.091  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 307
08-23 16:36:46.094  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:36:46.097   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:36:46.097   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:36:46.100   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:36:47.541   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:36:51.217   485   485 D charger_monitor: init target 500000
,08-23 16:36:51.221  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:36:51.222   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:36:51.223  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:36:51.223  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:36:51.223  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:36:51.223  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
08-23 16:36:51.268  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:36:51.271  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 307
08-23 16:36:51.272  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:36:51.272  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:36:51.273  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:36:51.273  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:36:51.273  1802  1986 D LEDHandler: Battery Temp: 307, mChargingStatus=5, mChargingStop=false
08-23 16:36:51.275  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:36:51.275  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 307
08-23 16:36:51.279  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:36:51.281   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:36:51.281   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:36:51.284   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:36:52.545   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:36:56.940   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:36:56.940   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:36:56.940   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 253159879751; DSPS: 8394385; Offset : -3019893213
,08-23 16:36:57.550   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:37:00.040  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:37:00.040  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:37:00.040  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:37:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:37:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:37:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:37:00.046  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:37:01.704  1730  3490 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-23 16:37:02.554   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:37:07.559   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:37:12.563   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:37:16.941   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:37:16.941   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:37:16.941   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 273160910733; DSPS: 9049779; Offset : -3019900063
,08-23 16:37:17.568   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:37:22.573   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:37:27.577   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:37:32.582   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:37:36.942   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:37:36.942   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:37:36.942   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 293161670726; DSPS: 9705163; Offset : -3019872570
,08-23 16:37:37.586   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:37:42.591   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:37:47.595   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:37:51.356   485   485 D charger_monitor: init target 500000
,08-23 16:37:51.361   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:37:51.368  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:37:51.368  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:37:51.369  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:37:51.369  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:37:51.371  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:37:51.406  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:37:51.408  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 304
08-23 16:37:51.409  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:37:51.409  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:37:51.410  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:37:51.411  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:37:51.411  1802  1986 D LEDHandler: Battery Temp: 304, mChargingStatus=5, mChargingStop=false
08-23 16:37:51.412  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:37:51.412  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 304
08-23 16:37:51.414  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:37:51.418   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:37:51.418   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:37:51.421   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:37:52.600   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:37:56.942   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:37:56.942   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:37:56.942   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 313162360093; DSPS: 10360546; Offset : -3019884846
,08-23 16:37:57.604   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:38:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:38:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:38:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:38:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:38:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:38:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:38:00.045  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:38:02.609   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:38:07.614   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:38:12.618   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:38:16.943   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:38:16.943   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:38:16.943   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 333163102378; DSPS: 11015930; Offset : -3019875166
,08-23 16:38:17.623   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:38:22.627   293   348 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 16:38:26.367   857  3268 I LocationManagerService: remove 84781
,08-23 16:38:26.495   857  3268 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-23 16:38:26.495   857  3268 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 16:38:26.495   857  3268 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-23 16:38:26.495   857  3268 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-23 16:38:26.496   857  3268 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-23 16:38:27.632   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:38:32.636   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:38:36.944   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:38:36.944   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:38:36.944   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 353163792578; DSPS: 11671313; Offset : -3019886895
,08-23 16:38:37.641   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:38:42.646   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:38:47.650   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:38:51.520  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:38:51.520  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:38:51.520  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:38:51.520  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:38:51.523   485   485 D charger_monitor: init target 500000
08-23 16:38:51.527  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:38:51.530   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:38:51.564  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:38:51.567  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 302
08-23 16:38:51.567  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:38:51.567  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 302
08-23 16:38:51.569  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:38:51.569  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:38:51.570  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:38:51.570  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:38:51.570  1802  1986 D LEDHandler: Battery Temp: 302, mChargingStatus=5, mChargingStop=false
08-23 16:38:51.572  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:38:51.576   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:38:51.576   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:38:51.580   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:38:52.655   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:38:56.944   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:38:56.944   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:38:56.945   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 373164530903; DSPS: 12326697; Offset : -3019880785
,08-23 16:38:57.659   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:39:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:39:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:39:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:39:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:39:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:39:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:39:00.045  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:39:02.664   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:39:06.873   857  1283 D PowerManagerServiceEx: acquireWakeLockInternal: lock=721127928, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,08-23 16:39:06.881   857  1283 V AlarmManager: RTC_WAKEUP set : Alarm{28293c1a type 0 when 1471963146872 com.google.android.gms} when 1471963146872
08-23 16:39:06.911   857   857 D PowerManagerServiceEx: releaseWakeLockInternal: lock=721127928 [*alarm*], flags=0x0
,08-23 16:39:06.978  3345  6858 I EventLogChimeraService: Aggregate from 1471962872764 (log), 1471961346765 (data)
,08-23 16:39:07.145  3345  6877 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,08-23 16:39:07.669   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:39:12.674   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:39:16.946   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:39:16.946   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:39:16.946   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 393165804177; DSPS: 12982099; Offset : -3019888832
,08-23 16:39:17.678   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:39:22.683   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:39:27.687   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:39:32.692   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:39:36.946   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:39:36.946   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:39:36.946   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 413166473388; DSPS: 13637481; Offset : -3019891477
,08-23 16:39:37.697   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:39:42.701   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:39:45.950  6601  6645 I PlayCommon: [802] com.google.android.play.a.l.e(787): Preparing logs for uploading
,08-23 16:39:45.966  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 16:39:45.980  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 16:39:45.985  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-23 16:39:46.034   857  1854 I NotificationManager: android: cancelAsUser(2) by android
,08-23 16:39:46.041  6601  6645 I PlayCommon: [802] com.google.android.play.a.l.a(927): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
08-23 16:39:46.060  6601  6645 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-23 16:39:46.060  6601  6645 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-23 16:39:46.061  6601  6645 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-23 16:39:46.061  6601  6645 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-23 16:39:46.061   276  1041 E BandwidthController: [LG DATA] No such appUid: 10036
08-23 16:39:46.061   276  1041 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
,08-23 16:39:46.065   276  6900 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-23 16:39:46.065   276  6900 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-23 16:39:46.065   276  6900 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-23 16:39:46.070   276  6900 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-23 16:39:46.112   276  6900 D libc-netbsd: res_queryN name = xxxxx succeed
,08-23 16:39:46.118  6601  6645 I System.out: propertyValue:false
08-23 16:39:46.373  6601  6645 I PlayCommon: [802] com.google.android.play.a.l.a(1002): Successfully uploaded logs.
,08-23 16:39:47.706   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:39:51.674   485   485 D charger_monitor: init target 500000
,08-23 16:39:51.680   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:39:51.689  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:39:51.689  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:39:51.689  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:39:51.689  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:39:51.692  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:39:51.727  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:39:51.730  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
08-23 16:39:51.731  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:39:51.731  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:39:51.732  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:39:51.732  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:39:51.732  1802  1986 D LEDHandler: Battery Temp: 300, mChargingStatus=5, mChargingStop=false
08-23 16:39:51.734  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:39:51.734  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
08-23 16:39:51.736  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:39:51.740   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:39:51.740   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:39:51.744   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:39:52.710   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:39:56.947   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:39:56.947   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:39:56.947   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 433167066870; DSPS: 14292860; Offset : -3019877620
,08-23 16:39:57.715   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:40:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:40:00.040  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:40:00.040  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:40:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:40:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:40:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:40:00.046  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:40:02.719   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:40:07.724   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:40:12.729   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:40:16.948   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:40:16.948   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:40:16.948   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 453167769571; DSPS: 14948243; Offset : -3019877058
,08-23 16:40:17.733   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:40:22.738   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:40:27.742   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:40:32.747   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:40:36.948   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:40:36.948   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:40:36.948   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 473168508938; DSPS: 15603627; Offset : -3019869852
,08-23 16:40:37.752   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:40:42.756   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:40:47.761   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:40:51.843   485   485 D charger_monitor: init target 500000
,08-23 16:40:51.848   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:40:51.857  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:40:51.857  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:40:51.857  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:40:51.857  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:40:51.860  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:40:51.894  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:40:51.897  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 299
08-23 16:40:51.898  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:40:51.898  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:40:51.899  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:40:51.899  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:40:51.899  1802  1986 D LEDHandler: Battery Temp: 299, mChargingStatus=5, mChargingStop=false
08-23 16:40:51.901  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:40:51.901  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 299
08-23 16:40:51.903  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-23 16:40:51.907   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:40:51.907   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:40:51.911   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:40:52.765   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:40:56.949   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:40:56.949   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:40:56.949   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 493169195493; DSPS: 16259010; Offset : -3019885280
,08-23 16:40:57.770   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:41:00.040  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:41:00.040  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:41:00.040  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:41:00.045  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:41:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:41:00.046  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:41:00.046  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:41:02.774   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:41:07.779   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:41:12.783   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:41:16.950   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:41:16.950   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:41:16.950   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 513169896423; DSPS: 16914393; Offset : -3019886150
,08-23 16:41:17.788   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:41:22.793   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:41:27.797   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:41:32.802   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:41:36.951   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:41:36.951   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:41:36.951   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 533170862509; DSPS: 17569785; Offset : -3019896522
,08-23 16:41:37.806   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:41:42.811   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:41:47.815   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:41:51.994   485   485 D charger_monitor: init target 500000
,08-23 16:41:52.000   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:41:52.009  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:41:52.009  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:41:52.009  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:41:52.009  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:41:52.012  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:41:52.046  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:41:52.049  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
08-23 16:41:52.049  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:41:52.050  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:41:52.051  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:41:52.051  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:41:52.051  1802  1986 D LEDHandler: Battery Temp: 297, mChargingStatus=5, mChargingStop=false
08-23 16:41:52.052  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:41:52.052  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
08-23 16:41:52.054  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:41:52.058   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:41:52.058   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:41:52.062   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:41:52.820   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:41:56.951   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:41:56.952   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:41:56.952   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 553171658336; DSPS: 18225171; Offset : -3019894438
,08-23 16:41:57.825   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:42:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:42:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:42:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:42:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:42:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:42:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:42:00.045  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:42:02.829   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:42:05.940  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-23 16:42:05.945  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:42:05.945  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:42:05.945  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:42:05.945  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
08-23 16:42:05.954   485   485 D charger_monitor: init target 500000
,08-23 16:42:05.959   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:42:05.993  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:42:05.996  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
08-23 16:42:05.997  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:42:05.997  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
08-23 16:42:05.998  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:42:05.998  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:42:05.999  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:42:05.999  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:42:05.999  1802  1986 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
08-23 16:42:06.002  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:42:06.005   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:42:06.005   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:42:06.009   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:42:06.049  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:42:06.051  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
08-23 16:42:06.051  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:42:06.051  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
08-23 16:42:06.053  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:42:06.053  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:42:06.054   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:42:06.055   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:42:06.055   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:42:06.056  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:42:06.058  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:42:06.058  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:42:06.058  1802  1986 D LEDHandler: Battery Temp: 297, mChargingStatus=5, mChargingStop=false
08-23 16:42:07.834   293   348 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-23 16:42:12.838   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:42:16.952   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:42:16.952   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:42:16.952   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 573172342859; DSPS: 18880553; Offset : -3019881250
,08-23 16:42:17.843   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:42:22.848   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:42:27.852   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:42:32.861   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:42:36.953   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:42:36.953   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:42:36.953   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 593173096861; DSPS: 19535938; Offset : -3019889928
,08-23 16:42:37.868   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:42:42.873   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:42:47.877   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:42:52.157   485   485 D charger_monitor: init target 500000
,08-23 16:42:52.162   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:42:52.163  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:42:52.163  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:42:52.163  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:42:52.163  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
08-23 16:42:52.163  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:42:52.201  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
08-23 16:42:52.201  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:42:52.202  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
,08-23 16:42:52.205  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:42:52.205  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:42:52.206  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:42:52.206  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:42:52.206  1802  1986 D LEDHandler: Battery Temp: 295, mChargingStatus=5, mChargingStop=false
08-23 16:42:52.209  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 16:42:52.211  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:42:52.214   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:42:52.214   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:42:52.218   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:42:52.882   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:42:56.954   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:42:56.954   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:42:56.954   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 613173869510; DSPS: 20191323; Offset : -3019880478
,08-23 16:42:57.887   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:43:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:43:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-23 16:43:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
08-23 16:43:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:43:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:43:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:43:00.045  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:43:02.891   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:43:07.896   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:43:12.900   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:43:16.954   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:43:16.955   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:43:16.955   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 633174642523; DSPS: 20846709; Offset : -3019901105
,08-23 16:43:17.905   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:43:22.909   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:43:27.914   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:43:32.919   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:43:36.955   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:43:36.955   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:43:36.955   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 653175388817; DSPS: 21502093; Offset : -3019887259
,08-23 16:43:37.923   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:43:42.928   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:43:47.932   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:43:52.314   485   485 D charger_monitor: init target 500000
,08-23 16:43:52.319   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:43:52.329  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:43:52.329  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:43:52.329  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:43:52.329  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:43:52.332  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:43:52.366  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:43:52.369  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
08-23 16:43:52.369  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:43:52.370  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:43:52.371  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:43:52.371  1802  1986 D LEDHandler: Battery Temp: 295, mChargingStatus=5, mChargingStop=false
08-23 16:43:52.371  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:43:52.373  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:43:52.373  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
08-23 16:43:52.377   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:43:52.377   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:43:52.378   857  1314 D WifiController: battery changed pluggedType: 2
,08-23 16:43:52.385  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:43:52.937   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:43:56.956   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:43:56.956   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:43:56.956   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 673176075945; DSPS: 22157475; Offset : -3019871361
,08-23 16:43:57.941   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:44:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:44:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:44:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:44:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:44:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:44:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:44:00.045  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:44:02.946   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:44:07.951   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:44:12.955   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:44:16.957   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:44:16.957   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:44:16.957   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 693176846563; DSPS: 22812861; Offset : -3019893940
,08-23 16:44:17.966   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:44:22.971   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:44:27.975   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:44:32.980   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:44:36.957   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:44:36.957   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:44:36.957   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 713177522441; DSPS: 23468243; Offset : -3019891349
,08-23 16:44:37.984   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:44:42.989   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:44:47.008   857  1283 D PowerManagerServiceEx: acquireWakeLockInternal: lock=721127928, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,08-23 16:44:47.012   857  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{39b66e04 type 2 when 723224 android} when 723224
08-23 16:44:47.034   857   857 D PowerManagerServiceEx: releaseWakeLockInternal: lock=721127928 [*alarm*], flags=0x0
,08-23 16:44:47.994   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:44:52.474   485   485 D charger_monitor: init target 500000
,08-23 16:44:52.480   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:44:52.489  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:44:52.489  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:44:52.489  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:44:52.489  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:44:52.492  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:44:52.526  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:44:52.529  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
08-23 16:44:52.530  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:44:52.530  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:44:52.530  1802  1986 D LEDHandler: Battery Temp: 293, mChargingStatus=5, mChargingStop=false
08-23 16:44:52.531  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:44:52.531  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:44:52.533  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:44:52.533  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
08-23 16:44:52.535  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:44:52.537   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:44:52.537   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:44:52.538   857  1314 D WifiController: battery changed pluggedType: 2
,08-23 16:44:52.998   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:44:56.958   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:44:56.958   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:44:56.958   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 733178221131; DSPS: 24123626; Offset : -3019892949
,08-23 16:44:58.003   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:45:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:45:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:45:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:45:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:45:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:45:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:45:00.046  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:45:03.007   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:45:08.012   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:45:13.016   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:45:16.959   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:45:16.959   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:45:16.959   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 753178911383; DSPS: 24779008; Offset : -3019874084
,08-23 16:45:18.021   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:45:23.026   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:45:28.030   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:45:33.035   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:45:36.960   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:45:36.960   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:45:36.960   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 773179660282; DSPS: 25434393; Offset : -3019887994
,08-23 16:45:38.039   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:45:43.044   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:45:48.048   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:45:52.637   485   485 D charger_monitor: init target 500000
,08-23 16:45:52.642   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:45:52.643  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:45:52.643  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:45:52.643  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:45:52.643  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
08-23 16:45:52.644  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:45:52.681  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
08-23 16:45:52.681  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:45:52.682  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
,08-23 16:45:52.685  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:45:52.685  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:45:52.686  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:45:52.686  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:45:52.686  1802  1986 D LEDHandler: Battery Temp: 292, mChargingStatus=5, mChargingStop=false
08-23 16:45:52.689  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 16:45:52.691  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:45:52.693   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:45:52.693   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:45:52.694   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:45:53.053   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:45:56.960   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:45:56.960   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:45:56.960   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 793180427410; DSPS: 26089778; Offset : -3019883727
,08-23 16:45:58.058   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:46:00.040  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:46:00.040  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:46:00.040  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:46:00.045  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:46:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:46:00.046  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:46:00.046  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:46:03.064   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:46:08.069   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:46:13.073   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:46:16.961   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:46:16.961   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:46:16.961   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 813181129746; DSPS: 26745161; Offset : -3019883296
,08-23 16:46:18.078   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:46:23.082   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:46:28.087   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:46:33.092   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:46:36.962   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:46:36.962   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:46:36.962   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 833181881926; DSPS: 27400546; Offset : -3019894289
,08-23 16:46:38.096   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:46:43.101   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:46:48.105   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:46:52.794   485   485 D charger_monitor: init target 500000
,08-23 16:46:52.800   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:46:52.809  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:46:52.809  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:46:52.809  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:46:52.809  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:46:52.812  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:46:52.846  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:46:52.849  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
08-23 16:46:52.850  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:46:52.850  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:46:52.851  1802  1986 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
08-23 16:46:52.851  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:46:52.851  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:46:52.853  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:46:52.853  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
08-23 16:46:52.855  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:46:52.859   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:46:52.859   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:46:52.862   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:46:53.110   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:46:56.962   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:46:56.963   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:46:56.963   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 853182569054; DSPS: 28055928; Offset : -3019878783
,08-23 16:46:58.114   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:47:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:47:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:47:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:47:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:47:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:47:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:47:00.045  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:47:03.119   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:47:08.124   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:47:13.128   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:47:16.963   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:47:16.963   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:47:16.963   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 873183252484; DSPS: 28711311; Offset : -3019896762
,08-23 16:47:18.133   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:47:23.137   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:47:28.142   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:47:33.146   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:47:36.964   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:47:36.964   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:47:36.964   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 893184013518; DSPS: 29366696; Offset : -3019898746
,08-23 16:47:38.151   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:47:43.156   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:47:48.160   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:47:49.136  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-23 16:47:49.140  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:47:49.140  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:47:49.140  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:47:49.140  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
08-23 16:47:49.164   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-23 16:47:49.211   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-23 16:47:49.214  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:47:49.215  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:47:49.215  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:47:49.215  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:47:49.215  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
08-23 16:47:49.256  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
08-23 16:47:49.256  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:47:49.256  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
,08-23 16:47:49.264  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 16:47:49.265  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:47:49.265  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:47:49.266  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:47:49.266  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:47:49.266  1802  1986 D LEDHandler: Battery Temp: 292, mChargingStatus=5, mChargingStop=false
08-23 16:47:49.269  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-23 16:47:49.276   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:47:49.276   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:47:49.276   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:47:49.316  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:47:49.319  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
08-23 16:47:49.320  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:47:49.320  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:47:49.321  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:47:49.321  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:47:49.322  1802  1986 D LEDHandler: Battery Temp: 292, mChargingStatus=5, mChargingStop=false
08-23 16:47:49.323  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:47:49.323  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
08-23 16:47:49.325  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:47:49.329   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:47:49.329   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:47:49.332   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:47:51.177  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:47:51.177  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:47:51.177  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:47:51.177  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:47:51.180   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:47:51.181  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:47:51.234  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:47:51.237  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
08-23 16:47:51.238  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:47:51.238  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
08-23 16:47:51.239  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:47:51.239  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:47:51.240  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:47:51.240  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:47:51.240  1802  1986 D LEDHandler: Battery Temp: 292, mChargingStatus=5, mChargingStop=false
08-23 16:47:51.243  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:47:51.247   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:47:51.247   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:47:51.250   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:47:52.959   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-23 16:47:52.962  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:47:52.963  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:47:52.963  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:47:52.964  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:47:52.964  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
08-23 16:47:53.001  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
08-23 16:47:53.002  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:47:53.002  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
,08-23 16:47:53.005  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:47:53.005  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:47:53.007  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:47:53.007  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:47:53.007  1802  1986 D LEDHandler: Battery Temp: 292, mChargingStatus=5, mChargingStop=false
08-23 16:47:53.010  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 16:47:53.012   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:47:53.012   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:47:53.013   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:47:53.015  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-23 16:47:53.165   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:47:56.965   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:47:56.965   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:47:56.965   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 913184762989; DSPS: 30022080; Offset : -3019881593
,08-23 16:47:58.169   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:48:00.040  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:48:00.040  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:48:00.040  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:48:00.045  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:48:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:48:00.046  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:48:00.046  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:48:03.174   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:48:08.183   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:48:13.187   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:48:16.965   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:48:16.965   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:48:16.965   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 933185452149; DSPS: 30677463; Offset : -3019894285
,08-23 16:48:18.192   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:48:23.196   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:48:28.201   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:48:30.566   857  1283 D PowerManagerServiceEx: acquireWakeLockInternal: lock=721127928, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,08-23 16:48:30.572   857  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{34a3fed type 2 when 946782 com.android.bluetooth} when 946782
08-23 16:48:30.742  2033  3613 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
08-23 16:48:30.742  2033  3613 W bt-smp  : Plain text(LSB ~ MSB) = 23 f2 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-23 16:48:30.745  2033  3613 W bt-smp  : Encrypted text(LSB ~ MSB) = b1 01 73 6b e3 39 4d 2c 33 05 44 26 4c 82 3f 6c 
08-23 16:48:30.745  2033  3613 W bt-btm  : Stopping oneshot timer
08-23 16:48:30.803   857  1801 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6986 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-23 16:48:30.999  6986  6986 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-23 16:48:31.009  6986  6986 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3eb45a2a
08-23 16:48:31.010   857   857 D PowerManagerServiceEx: releaseWakeLockInternal: lock=721127928 [*alarm*], flags=0x0
08-23 16:48:33.206   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:48:36.966   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:48:36.966   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:48:36.966   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 953186155682; DSPS: 31332846; Offset : -3019892969
,08-23 16:48:38.210   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:48:43.215   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:48:48.219   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:48:53.119   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-23 16:48:53.123  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:48:53.124  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:48:53.124  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:48:53.124  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:48:53.124  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
08-23 16:48:53.164  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:48:53.167  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
08-23 16:48:53.168  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:48:53.168  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:48:53.169  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:48:53.170  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:48:53.170  1802  1986 D LEDHandler: Battery Temp: 290, mChargingStatus=5, mChargingStop=false
08-23 16:48:53.171  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:48:53.171  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
08-23 16:48:53.173  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:48:53.175   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:48:53.175   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:48:53.176   857  1314 D WifiController: battery changed pluggedType: 2
,08-23 16:48:53.224   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:48:56.967   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:48:56.967   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:48:56.967   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 973186917654; DSPS: 31988231; Offset : -3019893754
,08-23 16:48:58.229   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:49:00.040  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:49:00.040  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:49:00.040  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:49:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:49:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:49:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:49:00.046  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:49:03.233   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:49:08.238   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:49:13.242   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:49:16.967   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:49:16.968   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:49:16.968   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 993187600198; DSPS: 32643613; Offset : -3019884575
,08-23 16:49:18.247   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:49:23.251   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:49:28.256   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:49:33.261   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:49:36.968   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:49:36.968   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:49:36.968   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1013188369149; DSPS: 33298998; Offset : -3019876403
,08-23 16:49:38.265   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:49:43.270   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:49:48.274   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:49:53.279   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:49:53.284   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:49:53.285  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:49:53.285  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:49:53.286  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:49:53.286  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:49:53.286  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
08-23 16:49:53.320  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
08-23 16:49:53.321  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:49:53.321  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
,08-23 16:49:53.327  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 16:49:53.328  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:49:53.329  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:49:53.330  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:49:53.330  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:49:53.330  1802  1986 D LEDHandler: Battery Temp: 290, mChargingStatus=5, mChargingStop=false
08-23 16:49:53.332  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:49:53.334   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:49:53.334   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:49:53.337   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:49:56.969   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:49:56.969   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:49:56.969   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1033189137735; DSPS: 33954383; Offset : -3019870991
,08-23 16:49:58.283   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:50:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:50:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:50:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:50:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:50:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:50:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:50:00.046  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:50:03.288   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:50:08.293   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:50:13.297   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:50:16.970   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:50:16.970   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:50:16.970   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1053189827102; DSPS: 34609766; Offset : -3019883866
,08-23 16:50:18.302   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:50:23.306   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:50:28.311   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:50:33.315   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:50:36.971   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:50:36.971   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:50:36.971   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1073190796210; DSPS: 35265158; Offset : -3019891086
,08-23 16:50:38.320   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:50:43.325   293   348 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-23 16:50:48.329   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:50:53.334   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:50:53.440  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:50:53.440  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:50:53.440  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:50:53.440  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:50:53.442   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:50:53.443  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:50:53.481  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
08-23 16:50:53.481  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:50:53.482  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
,08-23 16:50:53.485  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:50:53.485  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:50:53.486  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:50:53.486  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:50:53.486  1802  1986 D LEDHandler: Battery Temp: 289, mChargingStatus=5, mChargingStop=false
08-23 16:50:53.489  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 16:50:53.490  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:50:53.492   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:50:53.492   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:50:53.493   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:50:56.971   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:50:56.971   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:50:56.972   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1093191544848; DSPS: 35920542; Offset : -3019875183
,08-23 16:50:58.338   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:51:00.040  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:51:00.040  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:51:00.041  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:51:00.045  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:51:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:51:00.046  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:51:00.047  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:51:03.343   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:51:08.347   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:51:13.354   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:51:16.972   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:51:16.972   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:51:16.972   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1113192236767; DSPS: 36575925; Offset : -3019884751
,08-23 16:51:18.359   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:51:23.363   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:51:28.368   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:51:33.372   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:51:36.973   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:51:36.973   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:51:36.973   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1133192987697; DSPS: 37231310; Offset : -3019896917
,08-23 16:51:38.377   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:51:43.381   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:51:48.386   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:51:53.391   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:51:53.599   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-23 16:51:53.602  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:51:53.603  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:51:53.609  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:51:53.609  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:51:53.609  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
08-23 16:51:53.641  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
08-23 16:51:53.641  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:51:53.641  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
,08-23 16:51:53.645  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:51:53.645  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:51:53.646  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:51:53.646  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:51:53.646  1802  1986 D LEDHandler: Battery Temp: 288, mChargingStatus=5, mChargingStop=false
08-23 16:51:53.649  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 16:51:53.651  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:51:53.655   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:51:53.655   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:51:53.658   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:51:56.974   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:51:56.974   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:51:56.974   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1153193745658; DSPS: 37886694; Offset : -3019871247
,08-23 16:51:58.395   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:52:00.040  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:52:00.040  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:52:00.040  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:52:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:52:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:52:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:52:00.046  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:52:03.400   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:52:08.404   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:52:13.409   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:52:16.974   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:52:16.974   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:52:16.974   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1173194430130; DSPS: 38542077; Offset : -3019888914
,08-23 16:52:18.413   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:52:23.418   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:52:28.422   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:52:33.427   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:52:36.975   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:52:36.975   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:52:36.975   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1193195176736; DSPS: 39197461; Offset : -3019874418
,08-23 16:52:38.432   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:52:43.436   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:52:48.441   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:52:53.445   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:52:53.760  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:52:53.760  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:52:53.760  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:52:53.760  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:52:53.762   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:52:53.764  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:52:56.976   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:52:56.976   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:52:56.976   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1213195942927; DSPS: 39852846; Offset : -3019871245
,08-23 16:52:58.454   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:53:00.040  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:53:00.040  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:53:00.040  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:53:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:53:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:53:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:53:00.046  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:53:03.459   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:53:08.321   857   990 I UsageStatsService: User[0] Flushing usage stats to disk
,08-23 16:53:08.463   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:53:13.468   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:53:16.977   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:53:16.977   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:53:16.977   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1233196614690; DSPS: 40508228; Offset : -3019870947
,08-23 16:53:18.472   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:53:23.477   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:53:28.482   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:53:33.486   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:53:36.977   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:53:36.977   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:53:36.977   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1253197379422; DSPS: 41163614; Offset : -3019899411
,08-23 16:53:38.491   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:53:43.495   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:53:48.500   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:53:53.504   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:53:53.919   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-23 16:53:53.928  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:53:53.929  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:53:53.929  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:53:53.929  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:53:53.929  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
08-23 16:53:53.963  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:53:53.967  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
08-23 16:53:53.967  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:53:53.967  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:53:53.969  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:53:53.969  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:53:53.969  1802  1986 D LEDHandler: Battery Temp: 287, mChargingStatus=5, mChargingStop=false
08-23 16:53:53.970  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:53:53.970  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
08-23 16:53:53.972  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:53:53.976   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:53:53.976   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:53:53.980   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:53:56.978   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:53:56.978   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:53:56.978   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1273198140821; DSPS: 41818998; Offset : -3019870694
,08-23 16:53:58.509   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:54:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:54:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:54:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:54:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:54:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:54:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:54:00.046  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:54:03.514   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:54:08.518   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:54:13.523   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:54:16.979   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:54:16.979   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:54:16.979   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1293198829667; DSPS: 42474381; Offset : -3019883596
,08-23 16:54:18.527   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:54:23.532   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:54:28.536   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:54:33.541   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:54:36.979   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:54:36.980   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:54:36.980   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1313199585441; DSPS: 43129766; Offset : -3019890813
,08-23 16:54:38.545   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:54:43.550   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:54:46.378  6601  6645 I PlayCommon: [802] com.google.android.play.a.l.e(787): Preparing logs for uploading
08-23 16:54:46.378  6601  6645 I PlayCommon: [802] com.google.android.play.a.l.e(789): No file ready to send
,08-23 16:54:48.555   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:54:53.559   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:54:54.080  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:54:54.080  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:54:54.080  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:54:54.080  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:54:54.082   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:54:54.084  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:54:54.124  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:54:54.127  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
08-23 16:54:54.128  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:54:54.128  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:54:54.129  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:54:54.129  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:54:54.129  1802  1986 D LEDHandler: Battery Temp: 286, mChargingStatus=5, mChargingStop=false
08-23 16:54:54.130  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:54:54.131  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
08-23 16:54:54.133  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:54:54.136   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:54:54.136   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:54:54.140   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:54:56.980   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:54:56.980   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:54:56.981   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1333200555798; DSPS: 43785158; Offset : -3019897046
,08-23 16:54:58.564   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:55:00.040  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:55:00.040  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:55:00.040  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:55:00.045  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:55:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:55:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:55:00.046  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:55:03.568   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:55:08.573   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:55:13.577   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:55:16.981   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:55:16.981   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:55:16.981   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1353201329228; DSPS: 44440543; Offset : -3019886684
,08-23 16:55:18.582   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:55:23.587   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:55:28.591   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:55:33.596   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:55:36.982   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:55:36.982   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:55:36.982   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1373202054741; DSPS: 45095927; Offset : -3019893723
,08-23 16:55:38.600   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:55:43.605   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:55:48.609   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:55:53.614   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:55:54.240   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-23 16:55:54.243  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:55:54.244  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:55:54.245  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:55:54.245  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:55:54.245  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
08-23 16:55:56.983   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:55:56.983   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:55:56.983   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1393202817285; DSPS: 45751312; Offset : -3019894015
,08-23 16:55:58.619   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:56:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:56:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:56:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:56:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:56:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:56:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:56:00.045  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:56:03.623   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:56:08.628   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:56:13.632   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:56:16.983   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:56:16.983   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:56:16.984   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1413203597122; DSPS: 46406697; Offset : -3019877065
,08-23 16:56:18.637   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:56:23.641   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:56:28.646   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:56:33.651   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:56:36.984   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:56:36.984   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:56:36.984   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1433204281749; DSPS: 47062080; Offset : -3019894891
,08-23 16:56:38.655   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:56:43.660   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:56:48.664   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:56:53.669   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:56:54.401   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-23 16:56:54.404  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:56:54.404  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:56:54.405  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:56:54.405  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:56:54.405  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
08-23 16:56:54.439  2033  3549 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:56:54.443  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
08-23 16:56:54.443  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:56:54.443  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
08-23 16:56:54.444  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-23 16:56:54.445  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-23 16:56:54.446  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 16:56:54.446  1802  1986 D LEDHandler: Battery Level Remaining: 100%
08-23 16:56:54.446  1802  1986 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
08-23 16:56:54.448  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 16:56:54.452   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 16:56:54.452   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 16:56:54.456   857  1314 D WifiController: battery changed pluggedType: 2
08-23 16:56:56.985   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:56:56.985   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:56:56.985   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1453204956637; DSPS: 47717462; Offset : -3019890841
,08-23 16:56:58.673   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:57:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:57:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:57:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:57:00.043  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:57:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:57:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:57:00.045  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:57:03.678   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:57:08.683   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:57:13.687   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:57:16.986   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:57:16.986   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:57:16.986   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1473205815380; DSPS: 48372850; Offset : -3019886539
,08-23 16:57:18.692   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:57:23.696   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:57:28.701   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:57:33.706   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:57:36.986   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:57:36.986   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:57:36.986   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1493206471778; DSPS: 49028231; Offset : -3019871115
,08-23 16:57:38.710   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:57:43.715   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:57:48.719   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:57:53.724   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:57:54.560  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-23 16:57:54.560  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 16:57:54.560  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-23 16:57:54.560  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 16:57:54.562   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-23 16:57:54.564  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-23 16:57:56.987   857   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-23 16:57:56.987   857   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-23 16:57:56.987   857   998 D sensors_hal_Time: tsOffsetIs: Apps: 1513207289062; DSPS: 49683618; Offset : -3019877571
,08-23 16:57:58.728   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:58:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 16:58:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 16:58:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-23 16:58:00.043  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 16:58:00.043  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:58:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-23 16:58:00.045  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 16:58:03.733   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-23 16:58:08.739   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
,TIME-OUT KILL (timeout was 1400000ms),08-23 16:58:12.703  7081  7081 D AndroidRuntime: 
08-23 16:58:12.703  7081  7081 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 16:58:12.734  7081  7081 D AndroidRuntime: CheckJNI is OFF
08-23 16:58:13.035  7081  7081 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-23 16:58:13.060   857  1783 I ActivityManager: Process com.android.contacts (pid 6560) has died
08-23 16:58:13.084   857   991 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
08-23 16:58:13.084   857   991 I ActivityManager: Killing 6401:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
08-23 16:58:13.148   857  1825 I WindowState: WIN DEATH: Window{bce741 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-23 16:58:13.153   857  1825 D InputDispatcher: Focus left window: Window{bce741 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-23 16:58:13.153   857  1825 D InputDispatcher: Window went away: Window{bce741 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-23 16:58:13.183   857  1064 W PackageSettings: Skipping PackageSetting{39960e99 com.example.hello/10317} due to missing metadata
08-23 16:58:13.296   857   991 I ActivityManager:   Force finishing activity ActivityRecord{3e42f24f u0 com.test.thalitest/.MainActivity t259}
08-23 16:58:13.307   857   857 V ActivityManager: Display changed displayId=0
08-23 16:58:13.313  1748  1748 D DSDPConnection: Display #0 changed.
08-23 16:58:13.330   857  2153 W ActivityManager: Spurious death for ProcessRecord{24659e22 6401:com.test.thalitest/u0a30}, curProc for 6401: null
08-23 16:58:13.330   857  1064 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
08-23 16:58:13.334   857  1064 I ActivityManager:   Force finishing activity ActivityRecord{3e42f24f u0 com.test.thalitest/.MainActivity t259 f}
08-23 16:58:13.334   857  1064 W ActivityManager: Duplicate finish request for ActivityRecord{3e42f24f u0 com.test.thalitest/.MainActivity t259 f}
08-23 16:58:13.409  1962  1962 I art     : Explicit concurrent mark sweep GC freed 9122(622KB) AllocSpace objects, 2(47KB) LOS objects, 39% free, 12MB/20MB, paused 1.913ms total 72.492ms
08-23 16:58:13.427  1374  1374 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-23 16:58:13.433  1875  1875 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
08-23 16:58:13.438  1837  1837 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
08-23 16:58:13.442  1730  2514 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-23 16:58:13.447   857  1286 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-23 16:58:13.449  3345  3345 I art     : Explicit concurrent mark sweep GC freed 4688(249KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 16MB/21MB, paused 1.120ms total 112.126ms
08-23 16:58:13.451  3664  3664 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-23 16:58:13.451  3664  3664 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-23 16:58:13.451  3664  3664 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-23 16:58:13.451  3664  3664 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-23 16:58:13.451  3664  3664 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 16:58:13.451  3664  3664 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 16:58:13.452  3664  3664 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 16:58:13.452  3664  3664 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-23 16:58:13.452  3664  3664 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 16:58:13.452  3664  3664 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 16:58:13.452  3664  3664 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-23 16:58:13.453  3664  3664 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-23 16:58:13.461  1875  1875 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
08-23 16:58:13.491   857   991 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7113 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-23 16:58:13.558  1875  1875 I [LGHome]EVENT: [LauncherModel.java:1358:startLoader()]startLoader isLaunching=true
08-23 16:58:13.559  1875  2030 I [LGHome]Launcher.Model: [LauncherModel.java:1475:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-23 16:58:13.582  1875  1875 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-23 16:58:13.584  1374  1374 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-23 16:58:13.585  1875  1875 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-23 16:58:13.585  1875  1875 I Activity: Activity.onPostResume() called 
08-23 16:58:13.604  1875  1875 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-23 16:58:13.628  1374  1506 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-23 16:58:13.628  1374  1506 D KeyguardModel: createShortcutInfo...
08-23 16:58:13.632  1374  1506 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 16:58:13.632  1374  1506 D KeyguardModel: createShortcutInfo...
08-23 16:58:13.632   857   857 I art     : Explicit concurrent mark sweep GC freed 67479(3MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 23MB/35MB, paused 13.058ms total 242.064ms
08-23 16:58:13.633   857  1064 I art     : WaitForGcToComplete blocked for 52.545ms for cause Explicit
08-23 16:58:13.636  1374  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 16:58:13.642  1374  1506 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-23 16:58:13.658  1875  7130 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
08-23 16:58:13.662  1374  1506 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 16:58:13.662  1374  1506 D KeyguardModel: createShortcutInfo...
08-23 16:58:13.663  1374  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 16:58:13.663   857  1049 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-23 16:58:13.663  1374  1506 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 16:58:13.664   857  1049 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-23 16:58:13.664   857  1049 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-23 16:58:13.664   857  1049 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-23 16:58:13.665   857  1049 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-23 16:58:13.665   857  1049 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@35377356,  pkg=WindowManager.LayoutParams
08-23 16:58:13.665   857  1049 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-23 16:58:13.666  1374  1506 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 16:58:13.666  1374  1506 D KeyguardModel: createShortcutInfo...
08-23 16:58:13.667  1374  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 16:58:13.667  1374  1506 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-23 16:58:13.669  1374  1506 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 16:58:13.669  1374  1506 D KeyguardModel: createShortcutInfo...
08-23 16:58:13.669   857  1801 D InputDispatcher: Focus entered window: Window{22eb89ff u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-23 16:58:13.688  7113  7113 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 16:58:13.689  7113  7113 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 16:58:13.690  7113  7113 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-23 16:58:13.690  1374  1374 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-23 16:58:13.690  1374  1374 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-23 16:58:13.690  1374  1374 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-23 16:58:13.690  1374  1374 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-23 16:58:13.690  1374  1374 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-23 16:58:13.690  1374  1374 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-23 16:58:13.691  1875  1875 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 16:58:13.692  1374  1374 D KeyguardModel: handleShortcutListChanged...
08-23 16:58:13.692  1875  1875 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 16:58:13.693  1875  1875 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-23 16:58:13.703  1875  1875 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-23 16:58:13.708  1374  1506 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-23 16:58:13.708  1374  1506 D KeyguardModel: createShortcutInfo...
08-23 16:58:13.710  1374  1506 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 16:58:13.710  1374  1506 D KeyguardModel: createShortcutInfo...
08-23 16:58:13.712  1374  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 16:58:13.712  1374  1506 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-23 16:58:13.713  1374  1506 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 16:58:13.713  1374  1506 D KeyguardModel: createShortcutInfo...
08-23 16:58:13.715  1875  1875 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-23 16:58:13.715  1374  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 16:58:13.715  1374  1506 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 16:58:13.716  1875  1875 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-23 16:58:13.720  1374  1506 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 16:58:13.720  1374  1506 D KeyguardModel: createShortcutInfo...
08-23 16:58:13.721   857  1862 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-23 16:58:13.721  1374  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 16:58:13.721  1374  1506 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-23 16:58:13.722   857  1862 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6401 uid 10030
08-23 16:58:13.723  1374  1506 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 16:58:13.723  1374  1506 D KeyguardModel: createShortcutInfo...
08-23 16:58:13.728  1374  1374 D KeyguardModel: handleShortcutListChanged...
08-23 16:58:13.744   293   348 I ThermalEngine: Sensor:pa_therm0:29000 mC
08-23 16:58:13.804  1875  1875 I [LGHome]Launcher.Model: [LauncherModel.java:2270:run()] LauncherModel bind current page shortcut
08-23 16:58:13.812  1875  1875 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-23 16:58:13.824   857  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{34142a57 u0 com.lge.launcher2/.Launcher t258} time:1530044
08-23 16:58:13.847  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-23 16:58:13.849  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-23 16:58:13.851  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-23 16:58:13.853  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-23 16:58:13.891   857   857 D administrator: Handling package changes for user 0
08-23 16:58:13.916  1875  1875 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-23 16:58:13.951  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-23 16:58:13.952  1875  1875 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
08-23 16:58:13.952  1875  1875 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-23 16:58:13.982  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
08-23 16:58:13.991  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
08-23 16:58:13.992  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
08-23 16:58:13.993  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
08-23 16:58:13.996  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
08-23 16:58:14.002  7113  7113 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-23 16:58:14.006  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
08-23 16:58:14.006  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
08-23 16:58:14.008  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
08-23 16:58:14.009  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
08-23 16:58:14.010  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
08-23 16:58:14.020  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
08-23 16:58:14.029  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
08-23 16:58:14.039   857  1064 I art     : Explicit concurrent mark sweep GC freed 11409(1376KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.861ms total 400.306ms
08-23 16:58:14.039  7113  7113 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
08-23 16:58:14.077  1784  1784 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-23 16:58:14.078  1784  1784 D LCardEmulationManager: getDefaultRoute
08-23 16:58:14.167  7081  7081 D AndroidRuntime: Shutting down VM
08-23 16:58:14.170  1875  1875 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
08-23 16:58:14.216   857  1064 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7136 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-23 16:58:14.226   857   857 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-23 16:58:14.226   857   857 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 16:58:14.227   857   857 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-23 16:58:14.233   857  1349 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
08-23 16:58:14.257  1875  1875 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-23 16:58:14.258  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
08-23 16:58:14.258  1875  1875 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
08-23 16:58:14.259  1875  1875 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-23 16:58:14.285  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-23 16:58:14.286  1875  1875 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-23 16:58:14.287  1875  1875 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-23 16:58:14.290  1622  1622 E b       : Unable to connect to the editor to retrieve text... will retry later
08-23 16:58:14.291  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-23 16:58:14.293  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
08-23 16:58:14.295  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-23 16:58:14.296  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
08-23 16:58:14.298  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
08-23 16:58:14.307  1875  2240 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-23 16:58:14.308  1875  2240 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-23 16:58:14.308  1875  1875 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
08-23 16:58:14.309  1875  1875 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-23 16:58:14.309  1875  1875 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-23 16:58:14.367  7113  7113 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-23 16:58:14.376  1875  1875 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
08-23 16:58:14.399  1875  1875 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-23 16:58:14.400  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-23 16:58:14.400  1875  1875 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-23 16:58:14.418  6516  6516 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-23 16:58:14.452  1875  1875 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3ff60054 time:1530672
08-23 16:58:14.465   857  1360 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7159 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
08-23 16:58:14.466   857  1360 I ActivityManager: Killing 6540:com.android.gallery3d/u0a23 (adj 15): empty #11
08-23 16:58:14.505  1875  1875 I art     : Explicit concurrent mark sweep GC freed 26103(1424KB) AllocSpace objects, 16(2MB) LOS objects, 39% free, 15MB/25MB, paused 1.446ms total 48.943ms
08-23 16:58:14.521   857  1862 W libprocessgroup: failed to open /acct/uid_10023/pid_6540/cgroup.procs: No such file or directory

```
