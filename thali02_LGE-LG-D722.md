#### Test 83243049e1001da_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-30 12:37:40.838  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-30 12:37:41.384  2869  2869 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19951
08-30 12:37:41.409  6542  6542 D AndroidRuntime: 
08-30 12:37:41.409  6542  6542 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 12:37:41.413  6542  6542 D AndroidRuntime: CheckJNI is OFF
--------- beginning of system
08-30 12:37:41.573   834  1282 V AlarmManager: ELAPSED_WAKEUP set : Alarm{f519fb9 type 2 when 120000 com.google.android.gms} when 120000
08-30 12:37:41.681  6542  6542 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 12:37:41.696   834  2034 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 12:37:41.765   834  2034 D ActivityManager: setTaskToReturnTo : TaskRecord{26818ffe #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 12:37:41.767   834  2034 D ActivityManager: setTaskToReturnTo : TaskRecord{26818ffe #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 12:37:41.791   834  2034 D WindowStateEx: AppWindowTokenEx init.. 
08-30 12:37:41.809   834   931 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-30 12:37:41.831   834   931 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 12:37:41.837  1947  1947 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-30 12:37:41.837  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 12:37:41.837  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 12:37:41.837  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-30 12:37:41.840   834  2034 D InputDispatcher: Focus left window: Window{1d9f9f4d u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-30 12:37:41.842  6542  6542 D AndroidRuntime: Shutting down VM
08-30 12:37:41.851   834   931 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 12:37:41.852   834   931 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-30 12:37:41.870   834   931 D SplitWindow: check instance of lgWin Window{1085a0d6 u0 Starting com.test.thalitest}
08-30 12:37:41.921   834  1946 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6562 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 12:37:41.946  1947  1947 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-30 12:37:41.994  1947  1947 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-30 12:37:42.016   834   855 I WindowStateAnimator: Starting window displayed
08-30 12:37:42.021   834   929 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-30 12:37:42.024   834   929 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-30 12:37:42.027   834   929 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-30 12:37:42.027   834   929 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-30 12:37:42.027   834   929 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-30 12:37:42.028   834   929 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@33a8d210,  pkg=WindowManager.LayoutParams
08-30 12:37:42.030   834   929 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-30 12:37:42.033  1375  1375 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-30 12:37:42.035  1375  1375 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-30 12:37:42.035  1375  1375 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-30 12:37:42.035  1375  1375 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-30 12:37:42.055  2026  2026 I HotwordDetector: Closing mic
,08-30 12:37:42.069  2026  2562 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@35f2a3e
08-30 12:37:42.070  2026  2562 V AudioRecord: stop()
08-30 12:37:42.070  2026  2562 D AudioRecord: AudioRecord->stop()
08-30 12:37:42.071   284  1584 V AudioFlinger: RecordHandle::stop()
08-30 12:37:42.071   284  1584 V AudioFlinger: RecordThread::stop
08-30 12:37:42.086   284  1584 V AudioFlinger: Record stopped OK
08-30 12:37:42.088   284  1584 V AudioPolicyManager: stopInput() input 17
08-30 12:37:42.090   284  1584 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
08-30 12:37:42.090   284  1584 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
08-30 12:37:42.090   284  1057 V AudioPolicyService: AudioCommandThread() waking up
08-30 12:37:42.090   284  1057 V AudioPolicyService: AudioCommandThread() processing release audio patch
08-30 12:37:42.090   284  1057 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
08-30 12:37:42.090   284  1057 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
08-30 12:37:42.090   284  1057 V AudioFlinger: ThreadBase::setParameters() routing=0
08-30 12:37:42.090   284  1057 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-30 12:37:42.091   284  2595 V AudioFlinger: processConfigEvents_l() remaining events 1
08-30 12:37:42.091   284  2595 V AudioFlinger: processConfigEvents_l() DONE thread 0xb39ef000
08-30 12:37:42.095   284  2595 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
08-30 12:37:42.147   284  2595 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
08-30 12:37:42.147   284  2595 V audio_hw_primary: disable_audio_route: enter: usecase(7)
08-30 12:37:42.147   284  2595 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
08-30 12:37:42.147   284  2595 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 12:37:42.150   284  2595 V audio_hw_primary: disable_audio_route: exit
08-30 12:37:42.150   284  2595 E audio_hw_primary: disable_snd_device: enter 144
08-30 12:37:42.150   284  2595 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
08-30 12:37:42.150   284  2595 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
08-30 12:37:42.155   284  2595 V audio_hw_primary: stop_input_stream: exit: status(0)
08-30 12:37:42.155   284  2595 V audio_hw_primary: in_standby: exit:  status(0)
08-30 12:37:42.155   284  2595 V AudioFlinger: RecordThread: loop stopping
08-30 12:37:42.156   284  1584 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
08-30 12:37:42.156   284  1584 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
08-30 12:37:42.156   284  1584 V AudioPolicyService: AudioCommandThread() adding update audio patch list
08-30 12:37:42.156   284  1584 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
08-30 12:37:42.156   284  1057 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 12:37:42.156   284  1058 V AudioPolicyService: AudioCommandThread() waking up
08-30 12:37:42.156   284  1058 V AudioPolicyService: AudioCommandThread() processing update audio patch list
08-30 12:37:42.156   284  1058 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 12:37:42.157   284  1584 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
08-30 12:37:42.157   284  1584 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
08-30 12:37:42.157   284  1057 V AudioPolicyService: AudioCommandThread() waking up
08-30 12:37:42.157   284  1057 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
08-30 12:37:42.157   284  1057 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 284
08-30 12:37:42.158   284  1057 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
08-30 12:37:42.158   284  1057 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-30 12:37:42.158   284  2595 V AudioFlinger: RecordThread: loop starting
08-30 12:37:42.158   284  2595 V AudioFlinger: processConfigEvents_l() remaining events 1
08-30 12:37:42.158   284  2595 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
08-30 12:37:42.158   284  2595 V audio_hw_primary: in_set_parameters: exit: status(0)
08-30 12:37:42.158   284  2595 V AudioFlinger: processConfigEvents_l() DONE thread 0xb39ef000
08-30 12:37:42.158   284  2595 V AudioFlinger: RecordThread: loop stopping
08-30 12:37:42.159   284  1057 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 12:37:42.164  2026  2562 V AudioRecord: stop()
08-30 12:37:42.164  2026  2562 V AudioRecord: stop()
08-30 12:37:42.164  2026  2562 V AudioRecord: stop()
08-30 12:37:42.165   284  1583 V AudioFlinger: RecordHandle::stop()
08-30 12:37:42.165   284  1583 V AudioFlinger: RecordThread::stop
08-30 12:37:42.165   284  1583 V AudioPolicyManager: releaseInput() 17
08-30 12:37:42.165   284  1583 V AudioPolicyManager: closeInput(17)
08-30 12:37:42.166   284  1583 V AudioFlinger: closeInput() 17
08-30 12:37:42.166   284  1583 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 12:37:42.166   834  1291 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 12:37:42.166   284  1583 V AudioFlinger: ThreadBase::exit
08-30 12:37:42.166   284  2595 V AudioFlinger: RecordThread: loop starting
08-30 12:37:42.166  1375  2011 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 12:37:42.166  3148  3167 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 12:37:42.166  2061  2083 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 12:37:42.167  1776  1802 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 12:37:42.167   284  2595 V AudioFlinger: RecordThread 0xb39ef000 exiting
08-30 12:37:42.167   284  1583 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546dd40)
08-30 12:37:42.167   284  1583 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
08-30 12:37:42.167   284  1583 V audio_hw_primary: in_standby: exit:  status(0)
08-30 12:37:42.167   284  1583 V AudioPolicyService: AudioCommandThread() adding update audio port list
08-30 12:37:42.168   284  1583 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
08-30 12:37:42.168  2026  2051 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 12:37:42.168   284  1583 V AudioPolicyManager: releaseInput() exit
08-30 12:37:42.168  2869  2885 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 12:37:42.168   284  1058 V AudioPolicyService: AudioCommandThread() waking up
08-30 12:37:42.168   284  1058 V AudioPolicyService: AudioCommandThread() processing update audio port list
08-30 12:37:42.168   284  1583 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
08-30 12:37:42.168   284  1583 V AudioFlinger: removeClient_l() pid 2026, calling pid 284
08-30 12:37:42.168   284  1058 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 12:37:42.169   284  1584 V AudioFlinger: releasing 16 from 2026 for -1
08-30 12:37:42.169   284  1584 V AudioFlinger:  decremented refcount to 0
08-30 12:37:42.169   284  1584 V AudioFlinger: purging stale effects
08-30 12:37:42.169  6562  6562 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-30 12:37:42.177  2026  2581 I HotwordRecognitionRnr: Stopping hotword detection.
08-30 12:37:42.183  2026  2584 I HotwordRecognitionRnr: Hotword detection finished
08-30 12:37:42.298  6562  6562 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-30 12:37:42.356  6562  6562 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 789-791)
08-30 12:37:42.356  6562  6562 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:37:42.398  6562  6562 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {22313c27}
08-30 12:37:42.401  6562  6562 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:37:42.411  6562  6562 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 12:37:42.433  6562  6562 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 12:37:42.434  6562  6562 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 12:37:42.442  6562  6562 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 12:37:42.535  6562  6562 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 12:37:42.544  6562  6562 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 12:37:42.544  6562  6562 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 12:37:42.545  6562  6562 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:37:42.545  6562  6562 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:37:42.545  6562  6562 I Adreno-EGL: Build Date: 03/02/15 Mon
08-30 12:37:42.545  6562  6562 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-30 12:37:42.545  6562  6562 I Adreno-EGL: Remote Branch: 
08-30 12:37:42.545  6562  6562 I Adreno-EGL: Local Patches: 
08-30 12:37:42.545  6562  6562 I Adreno-EGL: Reconstruct Branch: 
08-30 12:37:42.634   284   284 V AudioPolicyService: registerClient() client 0xb3809c00, uid 10030
08-30 12:37:42.665   834   930 D BluetoothManagerService: Message: 20
08-30 12:37:42.665   834   930 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25f79461:true
,08-30 12:37:42.676  2061  2076 D BluetoothAdapterService(384514173): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2425983b
08-30 12:37:42.792  6562  6562 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 12:37:42.807  6562  6562 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 12:37:42.818  6562  6562 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 12:37:42.824  6562  6562 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 12:37:42.824  6562  6562 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-30 12:37:42.839  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 12:37:42.839  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 12:37:42.839  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-30 12:37:42.841  6562  6562 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-30 12:37:42.849  6562  6562 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 12:37:42.849  6562  6562 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 12:37:42.920  6562  6562 I Activity: Activity.onPostResume() called 
,08-30 12:37:42.929  6562  6629 D OpenGLRenderer: Render dirty regions requested: true
08-30 12:37:42.929  6562  6629 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 12:37:42.938  6562  6629 D OpenGLRenderer: Enabling debug mode 0
,08-30 12:37:42.961  6562  6562 D Atlas   : Validating map...
,08-30 12:37:42.970   834  1889 D SplitWindow: check instance of lgWin Window{3d3d57d1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 12:37:42.980  6562  6610 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 12:37:43.023   834  1912 D InputDispatcher: Focus entered window: Window{3d3d57d1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 12:37:43.093   834   855 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-30 12:37:43.093   834   931 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s219ms
08-30 12:37:43.093   834   931 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3b7de35f u0 com.test.thalitest/.MainActivity t259} time:121529
08-30 12:37:43.121  6562  6562 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@25298e9 time:121557
,08-30 12:37:43.151  1375  1375 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 12:37:43.160  1947  1947 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-30 12:37:43.161  1947  1947 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-30 12:37:43.161  1947  1947 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
08-30 12:37:43.171   834  1284 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 12:37:43.186   834   834 D administrator: Handling package changes for user 0
08-30 12:37:43.200  1909  1909 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,08-30 12:37:43.206   834   882 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6636 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-30 12:37:43.221  1375  1375 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 12:37:43.250  1947  1947 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,08-30 12:37:43.271  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
08-30 12:37:43.271  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
08-30 12:37:43.271  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
08-30 12:37:43.271  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
08-30 12:37:43.271  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
08-30 12:37:43.271  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
08-30 12:37:43.271  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
08-30 12:37:43.272  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
08-30 12:37:43.272  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
08-30 12:37:43.272  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
08-30 12:37:43.272  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
08-30 12:37:43.272  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
08-30 12:37:43.272  1375  1375 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-30 12:37:43.306  6562  6562 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6562
,08-30 12:37:43.384  6636  6636 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 12:37:43.426  1850  1868 I art     : Background sticky concurrent mark sweep GC freed 90490(5MB) AllocSpace objects, 0(0B) LOS objects, 34% free, 9MB/14MB, paused 5.373ms total 57.794ms
,08-30 12:37:43.457   834   834 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-30 12:37:43.461   834   834 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-30 12:37:43.461   834   834 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
08-30 12:37:43.465   834   834 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
08-30 12:37:43.483   834   834 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,08-30 12:37:43.485   834   834 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@29c9a1cd
08-30 12:37:43.640   834   880 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 12:37:43.767  1850  1850 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-30 12:37:43.767  1850  1850 D LCardEmulationManager: getDefaultRoute
,08-30 12:37:43.835   834   880 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-30 12:37:43.910  6636  6674 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-30 12:37:43.910  6636  6674 I Babel_SMS: MmsConfig.loadMmsSettings
,08-30 12:37:43.949  1947  1947 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-30 12:37:43.962  6636  6674 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
08-30 12:37:43.962  6636  6674 I Babel_SMS: MmsConfig.loadFromDatabase
,08-30 12:37:43.969  1748  1748 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
08-30 12:37:44.001   834   880 D LocationProviderProxy: applying state to connected service
,08-30 12:37:44.035  6562  6562 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 12:37:44.107  6636  6674 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-30 12:37:44.107  6636  6674 I Babel_SMS: MmsConfig.loadFromResources
08-30 12:37:44.109  6636  6674 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
08-30 12:37:44.110  6636  6674 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,08-30 12:37:44.121  1748  4409 I art     : Explicit concurrent mark sweep GC freed 33518(2MB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 14MB/23MB, paused 1.878ms total 115.161ms
08-30 12:37:44.137  6636  6636 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
08-30 12:37:44.137  6636  6636 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
08-30 12:37:44.137  6636  6636 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
08-30 12:37:44.137  6636  6636 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
08-30 12:37:44.137  6636  6636 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
,08-30 12:37:44.137  6636  6636 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
08-30 12:37:44.137  6636  6636 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
08-30 12:37:44.138  6636  6636 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
08-30 12:37:44.138  6636  6636 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
08-30 12:37:44.138  6636  6636 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
08-30 12:37:44.138  6636  6636 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
08-30 12:37:44.138  6636  6636 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
08-30 12:37:44.138  6636  6636 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
08-30 12:37:44.138  6636  6636 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
08-30 12:37:44.138  6636  6636 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
08-30 12:37:44.138  6636  6636 D SensorManager: found sensor: Motion Accel, handle=46
08-30 12:37:44.201  6636  6661 I art     : CheckpointMarkThreadRoots callback created = 0xb042d870
,08-30 12:37:44.253  6636  6661 I art     : CheckpointMarkThreadRoots callback created = 0xb042d860
,08-30 12:37:44.271  6636  6636 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 12:37:44.277  6636  6636 I Babel_Crash: startup - clean
08-30 12:37:44.304  6562  6635 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635609344
,08-30 12:37:44.327  6562  6635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 12:37:44.327  6562  6635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 12:37:44.327  6562  6635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 12:37:44.327  6562  6635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 12:37:44.327  6562  6635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 12:37:44.327  6562  6635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@be172d2 added. We now have 1 listener(s)
08-30 12:37:44.339   834  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 12:37:44.345  6562  6635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
08-30 12:37:44.345  6636  6679 I Babel   : deleted: false for 0
08-30 12:37:44.346  6562  6635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-30 12:37:44.349  6562  6635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:37:44.349  6562  6635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:37:44.359  6562  6635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 12:37:44.359  6562  6635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 12:37:44.359  6562  6635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 12:37:44.359  6562  6635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-30 12:37:44.359  6562  6635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 12:37:44.359  6562  6635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 12:37:44.359  6562  6635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 12:37:44.359  6562  6635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 12:37:44.359  6562  6635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 12:37:44.359  6562  6635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 12:37:44.359  6562  6635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 12:37:44.359  6562  6635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 12:37:44.359  6562  6635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 12:37:44.359  6562  6635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 12:37:44.360  6562  6635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e468e59 added. We now have 1 listener(s)
08-30 12:37:44.360  6562  6635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:37:44.396  6562  6635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:37:44.396  6562  6635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-30 12:37:44.396  6562  6635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 12:37:44.397  6562  6635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 12:37:44.397  6562  6635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 12:37:44.406  6562  6635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:37:44.407   834  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:37:44.408  6562  6635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
,08-30 12:37:44.419  2061  3508 D BluetoothAdapterService(384514173): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2425983b
08-30 12:37:44.422  6562  6635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 12:37:44.423  6562  6635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:37:44.423  6562  6635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:37:44.423  6562  6635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:37:44.423  6562  6635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:37:44.423  6562  6635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:37:44.423  6562  6635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:37:44.423  6562  6635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:37:44.423  6562  6635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:37:44.423  6562  6635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 12:37:44.423  6562  6635 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:37:44.424  6562  6635 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 12:37:44.426  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:37:44.429  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:37:44.471  6562  6562 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 12:37:44.493   834  1973 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6684 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-30 12:37:44.517   310   310 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 24.495ms
,08-30 12:37:44.540   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 21.351ms
,08-30 12:37:44.562   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.131ms
,08-30 12:37:44.577  6636  6636 W AudioCapabilities: Unsupported mime audio/x-lg-flac
08-30 12:37:44.578  6636  6636 W AudioCapabilities: Unsupported mime audio/adpcm
08-30 12:37:44.583  6636  6636 W AudioCapabilities: Unsupported mime audio/g726
,08-30 12:37:44.601  6636  6636 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-30 12:37:44.602  6636  6636 W AudioCapabilities: Unsupported mime audio/wma-voice
08-30 12:37:44.603  6636  6636 W VideoCapabilities: Unsupported mime video/mjpg
08-30 12:37:44.606  6562  6576 I art     : CheckpointMarkThreadRoots callback created = 0xb07fd370
08-30 12:37:44.610  6636  6636 W VideoCapabilities: Unsupported mime video/theora
08-30 12:37:44.650  6562  6576 I art     : CheckpointMarkThreadRoots callback created = 0xb07fd340
,08-30 12:37:44.661  6684  6684 I AppUp4:AppBoxCP: onCreate
08-30 12:37:44.662  6636  6636 W AudioCapabilities: Unsupported mime audio/evrc
08-30 12:37:44.666  6684  6684 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-30 12:37:44.671  6636  6636 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 12:37:44.674  6636  6636 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 12:37:44.679  6684  6684 I AppUp4:DB:  setFingerPrint start
08-30 12:37:44.680  6684  6684 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
,08-30 12:37:44.684  6636  6636 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-30 12:37:44.685  6636  6636 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 12:37:44.686  6636  6636 W AudioCapabilities: Unsupported mime audio/evrc
08-30 12:37:44.688  6684  6684 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
08-30 12:37:44.688  6684  6684 I AppUp4:DB:  SDK version = 21
08-30 12:37:44.688  6684  6684 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-30 12:37:44.690  6684  6684 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-30 12:37:44.699  6684  6684 I AppUp4:CustModeStarterReceiver: onReceive
08-30 12:37:44.699  6684  6684 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,08-30 12:37:44.700  6636  6636 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-30 12:37:44.702  6684  6684 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3742864b
08-30 12:37:44.702  6684  6684 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 12:37:44.710  6684  6684 D AppUp4:CustFacade: isSimDevice : true
08-30 12:37:44.712  6684  6684 D AppUp4:CustModeStarterReceiver: begin check event
08-30 12:37:44.712  6684  6684 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-30 12:37:44.714   834  1889 I ActivityManager: Killing 6272:com.lge.eula/1000 (adj 15): empty #11
08-30 12:37:44.729  6636  6636 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 12:37:44.737  6636  6636 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 12:37:44.739  6636  6636 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 12:37:44.742  6636  6636 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 12:37:44.748  6636  6636 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 12:37:44.789   834  2034 W libprocessgroup: failed to open /acct/uid_1000/pid_6272/cgroup.procs: No such file or directory
,08-30 12:37:44.836   834  1384 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6705 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-30 12:37:44.881  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,08-30 12:37:44.881  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 12:37:44.881  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-30 12:37:44.925  6636  6661 W art     : Suspending all threads took: 6.285ms
08-30 12:37:44.933  6705  6705 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 12:37:44.933  6705  6705 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 12:37:44.933  6705  6705 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 12:37:44.952  6636  6636 I vclib   : onServiceConnected
08-30 12:37:44.953  6636  6636 W Babel   : Attempted to change video mute state without an active call.
,08-30 12:37:44.966  6636  6703 I NotificationManager: com.google.android.talk: cancel(8) by com.google.android.talk
08-30 12:37:44.982   834  2021 I art     : Explicit concurrent mark sweep GC freed 59539(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/35MB, paused 4.840ms total 225.550ms
,08-30 12:37:44.992  6636  6636 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 12:37:44.992  6636  6636 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-30 12:37:45.077  6636  6636 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 12:37:45.134  6705  6705 I AppConfig: Total System Memory = 906309632
,08-30 12:37:45.146  6705  6705 I GalleryUtils: Application Heap = 96 MB
08-30 12:37:45.150  6705  6705 I AppConfig: App Tier : NOT_DEF
,08-30 12:37:45.157  6705  6705 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-30 12:37:45.159  6636  6636 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-30 12:37:45.160  6636  6636 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-30 12:37:45.171  6636  6636 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,08-30 12:37:45.201   296   354 I ThermalEngine: Sensor:pa_therm0:37000 mC
,08-30 12:37:45.235   834  1291 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6726 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-30 12:37:45.237   834  1291 I ActivityManager: Killing 6348:com.google.android.apps.docs/u0a58 (adj 15): empty #11
08-30 12:37:45.305   834  2009 W libprocessgroup: failed to open /acct/uid_10058/pid_6348/cgroup.procs: No such file or directory
,08-30 12:37:45.323  6726  6726 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:37:45.323  6726  6726 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:37:45.323  6726  6726 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-30 12:37:45.325  6726  6726 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-30 12:37:45.325  6726  6726 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 12:37:45.463  6562  6683 W jxcore-log: Initializing JXcore engine
,08-30 12:37:45.464  6562  6683 W jxcore-log: JXcore engine is ready
08-30 12:37:45.509  6726  6726 I SystemConfig: BUILD Country: EU
08-30 12:37:45.509  6726  6726 I SystemConfig: BUILD Operator: OPEN
,08-30 12:37:45.590  6683  6683 W Thread-784: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8336]" dev="sockfs" ino=8336 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-30 12:37:45.590  6683  6683 W Thread-784: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 12:37:45.590  6683  6683 W Thread-784: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6067]" dev="sockfs" ino=6067 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-30 12:37:45.590  6683  6683 W Thread-784: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-30 12:37:45.600  6683  6683 W Thread-784: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-30 12:37:45.600  6683  6683 W Thread-784: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[30141]" dev="sockfs" ino=30141 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-30 12:37:45.629  6562  6683 W jxcore-log: Starting JXcore engine
,08-30 12:37:45.699   834  1973 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6753 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,08-30 12:37:45.701   834  1973 I ActivityManager: Killing 6185:com.google.android.apps.plus/u0a86 (adj 15): empty #11
08-30 12:37:45.796  6562  6683 W jxcore-log: Platform android
08-30 12:37:45.796  6562  6683 W jxcore-log: 
,08-30 12:37:45.797  6562  6683 W jxcore-log: Process ARCH arm
08-30 12:37:45.797  6562  6683 W jxcore-log: 
08-30 12:37:45.816   834  1912 W libprocessgroup: failed to open /acct/uid_10086/pid_6185/cgroup.procs: No such file or directory
,08-30 12:37:45.831  6726  6750 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,08-30 12:37:45.831  6726  6750 I SystemConfig: existFile = false
08-30 12:37:45.831  6726  6750 I SystemConfig: canReadFile = false
08-30 12:37:45.832  6726  6750 I SystemConfig: systemFeature RCS result false
08-30 12:37:45.832  6726  6750 D SystemConfig: refreshRcsSupport() :false
,08-30 12:37:45.846  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 12:37:45.846  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-30 12:37:45.846  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-30 12:37:45.868  6753  6753 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-30 12:37:45.901  6753  6753 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-30 12:37:45.901  6753  6753 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-30 12:37:45.901  6753  6753 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-30 12:37:45.901  6753  6753 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 12:37:45.901  6753  6753 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-30 12:37:45.903   834  1973 I ActivityManager: Killing 6400:com.lge.bnr/1000 (adj 15): empty #11
,08-30 12:37:45.996   834  1834 W libprocessgroup: failed to open /acct/uid_1000/pid_6400/cgroup.procs: No such file or directory
,08-30 12:37:46.010  3424  6771 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,08-30 12:37:46.019  3424  6771 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 12:37:46.020  3424  6771 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 12:37:46.040  3424  3780 I Icing   : updateResources: need to parse ozd{com.google.android.gms}
,08-30 12:37:46.089   834   855 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6776 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-30 12:37:46.106   284   284 V AudioFlinger: 2869 died, releasing its sessions
08-30 12:37:46.106   284   284 V AudioFlinger:  pid 1776 @ 0
08-30 12:37:46.106   284   284 V AudioFlinger:  pid 3148 @ 1
08-30 12:37:46.106   284   284 V AudioFlinger:  pid 3148 @ 2
,08-30 12:37:46.142  6562  6683 I jxcore-log: JXcore Cordova bridge is ready!
08-30 12:37:46.142  6562  6683 I jxcore-log: 
,08-30 12:37:46.142  6562  6683 W jxcore-log: JXcore engine is started
08-30 12:37:46.146  6562  6635 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-30 12:37:46.150   834   857 I ActivityManager: Process com.lge.music (pid 2869) has died
08-30 12:37:46.151  6562  6562 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 12:37:46.178  6776  6776 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 12:37:46.191  3424  6793 W IcingInternalCorpora: getNumBytesRead when not calculated.
,08-30 12:37:46.452   834  1834 I ActivityManager: Process com.google.android.gms.unstable (pid 6458) has died
,08-30 12:37:46.481  2026  6803 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-30 12:37:46.532  2026  6803 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 51 ms] updated apps [took 51 ms] 
,08-30 12:37:47.095   834  1282 V AlarmManager: RTC_WAKEUP set : Alarm{22220e9f type 0 when 1472553467090 com.google.android.googlequicksearchbox} when 1472553467090
,08-30 12:37:47.233  3424  3780 I Icing   : Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,08-30 12:37:47.281  3424  3780 I Icing   : Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,08-30 12:37:47.850  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 12:37:47.850  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 12:37:47.850  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-30 12:37:48.661   477   477 D charger_monitor: init target 500000
,08-30 12:37:48.664  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-30 12:37:48.665  1375  1375 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-30 12:37:48.665  1375  1375 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-30 12:37:48.665  1375  1375 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-30 12:37:48.666  1375  1375 I [SystemUI]LGPowerUI: On Skip Timer : true
08-30 12:37:48.695  1375  1375 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 338
08-30 12:37:48.695  1375  1375 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-30 12:37:48.695  1375  1375 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 338
,08-30 12:37:48.699  1873  2049 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-30 12:37:48.699  1873  2049 D LEDHandler: Battery Level Remaining: 100%
08-30 12:37:48.699  1873  2049 D LEDHandler: Battery Temp: 338, mChargingStatus=5, mChargingStop=false
08-30 12:37:48.699  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-30 12:37:48.701  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-30 12:37:48.704   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:37:48.704   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:37:48.704   834  1312 D WifiController: battery changed pluggedType: 2
08-30 12:37:48.706  2061  3510 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 12:37:48.713   477   477 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-30 12:37:48.735  1375  1375 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-30 12:37:49.850  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 12:37:49.850  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 12:37:49.850  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,08-30 12:37:50.206   296   354 I ThermalEngine: Sensor:pa_therm0:37000 mC
,08-30 12:37:50.853  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,08-30 12:37:50.853  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 12:37:50.853  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-30 12:37:54.147   834  1025 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-30 12:37:54.147   834  1025 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-30 12:37:54.147   834  1025 D sensors_hal_Time: tsOffsetIs: Apps: 132582040423; DSPS: 4443176; Offset : -3015167362
,08-30 12:37:55.211   296   354 I ThermalEngine: Sensor:pa_therm0:37000 mC
,08-30 12:37:55.320   834  1282 V AlarmManager: ELAPSED_WAKEUP set : Alarm{29a2f5bb type 2 when 133751 com.google.android.gms} when 133751
,08-30 12:37:55.345  1748  1748 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-30 12:37:55.549  3424  6852 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-30 12:37:55.550  3424  6852 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-30 12:37:55.560  1748  1748 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-30 12:37:55.860  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 12:37:55.860  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 12:37:55.860  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-30 12:37:56.057   834  1291 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6858 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,08-30 12:37:56.156  6858  6858 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 12:37:56.156  6858  6858 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 12:37:56.210  6858  6858 I MultiDex: VM with version 2.1.0 has multidex support
08-30 12:37:56.210  6858  6858 I MultiDex: install
08-30 12:37:56.210  6858  6858 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 12:37:56.275  6858  6858 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 12:37:56.344  6858  6858 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-30 12:37:56.345  6858  6858 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e9bd01b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-30 12:37:56.346  6858  6858 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-30 12:37:56.347  6858  6858 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
08-30 12:37:56.348  6858  6858 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
08-30 12:37:56.358  6858  6858 D ChimeraCfgMgr: Reading stored module config
,08-30 12:37:56.478  6858  6872 W art     : Suspending all threads took: 9.075ms
,08-30 12:37:56.487  6858  6858 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
08-30 12:37:56.487  6858  6858 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
08-30 12:37:56.505  6858  6872 I art     : Background sticky concurrent mark sweep GC freed 20348(1008KB) AllocSpace objects, 3(133KB) LOS objects, 5% free, 10MB/11MB, paused 15.355ms total 94.938ms
,08-30 12:37:56.512  1748  1748 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=aad3ec82-7f28-468e-bc75-08f9b2259c99
08-30 12:37:56.541  1748  1748 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 12:37:56.545  1748  1748 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 12:37:56.623  6858  6883 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
08-30 12:37:56.624   834  1973 I ActivityManager: Process com.google.android.setupwizard (pid 6513) has died
,08-30 12:37:56.645  6858  6872 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3d0
,08-30 12:37:56.670  6858  6872 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3b0
,08-30 12:37:56.687   284  1299 D WVCdm   : Instantiating CDM.
,08-30 12:37:56.689   284  1583 I WVCdm   : CdmEngine::OpenSession
08-30 12:37:56.689   284  1583 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
08-30 12:37:56.728   284  1583 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
08-30 12:37:56.728   284  1583 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
08-30 12:37:56.728   284  1583 W WVCdm   : L1 library not specified. Falling Back to L3
,08-30 12:37:56.781  1748  2489 W GCoreFlp: No location to return for getLastLocation()
,08-30 12:37:56.831  6858  6874 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 12:37:56.831  6858  6874 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-30 12:37:56.831   284  1583 I WVCdm   : CdmEngine::QueryKeyControlInfo
08-30 12:37:56.832  6858  6874 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 12:37:56.832  6858  6874 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,08-30 12:37:56.833   278  1010 E BandwidthController: [LG DATA] No such appUid: 10006
08-30 12:37:56.833   278  1010 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-30 12:37:56.833   284  1584 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-30 12:37:56.833   284  1584 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-30 12:37:56.833   284  1584 I WVCdm   : CdmEngine::GenerateKeyRequest
08-30 12:37:56.833   278  6892 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-30 12:37:56.833   278  6892 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 12:37:56.834   278  6892 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-30 12:37:56.834   278  6892 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-30 12:37:56.841   284  1584 D WVCdm   : PrepareKeyRequest: nonce=3311506550
08-30 12:37:56.843  3424  6854 D UdcContextInitService: registered all accounts: true
08-30 12:37:56.845  1748  2466 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 12:37:56.858  1748  2343 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
08-30 12:37:56.862  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 12:37:56.863  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 12:37:56.863  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
08-30 12:37:56.866   278  6892 D libc-netbsd: res_queryN name = xxxxx succeed
08-30 12:37:56.867  6858  6874 I System.out: propertyValue:false
08-30 12:37:56.938  6858  6874 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 12:37:56.938  6858  6874 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-30 12:37:57.024   834  1946 I ActivityManager: Process com.lge.appbox.client (pid 6684) has died
,08-30 12:37:57.207   834  1384 I art     : Explicit concurrent mark sweep GC freed 30034(1637KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.601ms total 178.614ms
,08-30 12:37:57.280  1748  2343 I art     : Explicit concurrent mark sweep GC freed 50066(2MB) AllocSpace objects, 20(320KB) LOS objects, 39% free, 14MB/24MB, paused 1.771ms total 138.507ms
,08-30 12:37:57.709  6894  6894 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=41 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 12:37:57.754   834  1946 I ActivityManager: Process com.google.android.talk (pid 6636) has died
,08-30 12:37:57.831  6894  6894 I dex2oat : dex2oat took 111.994ms (threads: 4)
,08-30 12:37:57.846  6858  6874 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:37:57.846  6858  6874 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:37:57.846  6858  6874 I Adreno-EGL: Build Date: 03/02/15 Mon
08-30 12:37:57.846  6858  6874 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-30 12:37:57.846  6858  6874 I Adreno-EGL: Remote Branch: 
08-30 12:37:57.846  6858  6874 I Adreno-EGL: Local Patches: 
08-30 12:37:57.846  6858  6874 I Adreno-EGL: Reconstruct Branch: 
,08-30 12:37:58.042  6858  6874 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:37:58.042  6858  6874 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:37:58.042  6858  6874 I Adreno-EGL: Build Date: 03/02/15 Mon
08-30 12:37:58.042  6858  6874 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-30 12:37:58.042  6858  6874 I Adreno-EGL: Remote Branch: 
08-30 12:37:58.042  6858  6874 I Adreno-EGL: Local Patches: 
08-30 12:37:58.042  6858  6874 I Adreno-EGL: Reconstruct Branch: 
,08-30 12:37:58.098  6858  6874 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:37:58.098  6858  6874 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:37:58.098  6858  6874 I Adreno-EGL: Build Date: 03/02/15 Mon
08-30 12:37:58.098  6858  6874 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-30 12:37:58.098  6858  6874 I Adreno-EGL: Remote Branch: 
08-30 12:37:58.098  6858  6874 I Adreno-EGL: Local Patches: 
08-30 12:37:58.098  6858  6874 I Adreno-EGL: Reconstruct Branch: 
,08-30 12:37:58.563  1748  6856 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 12:37:58.563  1748  6856 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-30 12:37:58.563  1748  6856 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 12:37:58.563  1748  6856 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,08-30 12:37:58.564   278  1010 E BandwidthController: [LG DATA] No such appUid: 10006
08-30 12:37:58.564   278  1010 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-30 12:37:58.564   278  6918 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-30 12:37:58.565   278  6918 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 12:37:58.565   278  6918 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-30 12:37:58.565   278  6918 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-30 12:37:58.565   278  6918 D libc-netbsd: res_queryN name = xxxxx succeed
,08-30 12:37:58.566  1748  6856 I System.out: propertyValue:false
08-30 12:37:58.609  1748  6856 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 12:37:58.609  1748  6856 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-30 12:37:58.791  1748  2343 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 12:37:58.800  1748  2343 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
08-30 12:37:58.806  1748  2343 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-30 12:37:57.116+0200, stopTime=2016-08-30 12:37:58.802+0200, duration=1686ms
,08-30 12:37:58.864  1748  6923 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 12:37:58.865  1748  6923 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-30 12:37:58.865  1748  6923 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 12:37:58.865  1748  6923 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 12:37:58.865   278  1010 E BandwidthController: [LG DATA] No such appUid: 10006
08-30 12:37:58.865   278  1010 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,08-30 12:37:58.865   278  6925 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-30 12:37:58.865   278  6925 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 12:37:58.866   278  6925 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-30 12:37:58.866   278  6925 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-30 12:37:58.866   278  6925 D libc-netbsd: res_queryN name = xxxxx succeed
08-30 12:37:58.868  1748  6923 I System.out: propertyValue:false
08-30 12:37:58.884  4049  4241 I art     : Explicit concurrent mark sweep GC freed 1972(70KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.429ms total 40.282ms
,08-30 12:37:59.013   284   284 I WVCdm   : CdmEngine::CloseSession
,08-30 12:37:59.018   284   284 I WVCdm   : L3 Terminate.
08-30 12:37:59.278  1748  2343 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-30 12:37:59.432  1748  6933 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-30 12:37:59.433  1748  6931 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 12:37:59.454  1748  6933 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-30 12:37:59.454  1748  6931 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 12:37:59.474  1748  6933 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-30 12:37:59.474  1748  6931 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-30 12:37:59.474  1748  6931 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-30 12:37:59.478  1748  6931 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
08-30 12:37:59.519   834  2034 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 12:37:59.558  1748  6931 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,08-30 12:37:59.559  1748  6931 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-30 12:37:59.559  1748  6931 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 12:37:59.559  1748  6931 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 12:37:59.559   278  1010 E BandwidthController: [LG DATA] No such appUid: 10006
08-30 12:37:59.559   278  1010 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-30 12:37:59.559   278  6934 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-30 12:37:59.559   278  6934 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 12:37:59.560   278  6934 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-30 12:37:59.560   278  6934 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-30 12:37:59.561   278  6934 D libc-netbsd: res_queryN name = xxxxx succeed
08-30 12:37:59.562  1748  6931 I System.out: propertyValue:false
08-30 12:37:59.922   834  1291 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 12:38:00.001   834  1282 D PowerManagerServiceEx: acquireWakeLockInternal: lock=246621169, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=834
,08-30 12:38:00.010  2851  2851 D WeatherService: 2 : TimeTick Intent has been received, Time(hour:min:sec) 12:38:0
08-30 12:38:00.010  2851  2851 D WeatherService: 2 : TimeTick Intent And Screen On
08-30 12:38:00.011  2851  2851 D WeatherService: 2 : SDK version : 21
08-30 12:38:00.012   834  1872 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
08-30 12:38:00.012  2851  2851 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
08-30 12:38:00.013  2851  2851 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
08-30 12:38:00.013  2851  2851 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
08-30 12:38:00.013  2851  2851 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
,08-30 12:38:00.016  2851  2851 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 12:38:00.016  2851  2851 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
08-30 12:38:00.016  2851  2851 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
08-30 12:38:00.017  2851  2851 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
08-30 12:38:00.017  2851  2851 D WeatherTheme: 2 : Fixed theme : optimus
08-30 12:38:00.030  2851  2851 D WeatherReflect: 2 : Map key string is -2
,08-30 12:38:00.034  2851  2851 D lim     : 2 : time = 12:38
08-30 12:38:00.036  1375  1375 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-30 12:38:00.036  1375  1375 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 12:38:00.038  2851  2851 I WeatherReflect: Model Name : LG-D722
08-30 12:38:00.038  2851  2851 D WeatherTheme: 2 : Different view - status_min_formatted : 37 != 38
08-30 12:38:00.038  2851  2851 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
08-30 12:38:00.039  2851  2851 D WeatherReflect: 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
08-30 12:38:00.040  2851  2851 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-30 12:38:00.040  2851  2851 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-30 12:38:00.040  2851  2851 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-30 12:38:00.040  2851  2851 D Weather4x2_optimus: currentPackage=com.lge.sizechangable.weather.theme.optimus
08-30 12:38:00.052  1375  1375 I [SystemUI]Clock: called onTimeUpdated()
,08-30 12:38:00.056  1375  1375 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 12:38:00.057  1375  1375 I [SystemUI]DateView: called onTimeUpdated()
08-30 12:38:00.058  1375  1375 I [SystemUI]DateView: called onTimeUpdated()
08-30 12:38:00.059  1375  1375 D KeyguardUpdateMonitor: handleTimeUpdate
08-30 12:38:00.098  2851  2851 D Weather4x2_optimus: [[[[[[Theme package!!]]]]]] RemoteViews are created 2
08-30 12:38:00.098  2851  2851 D Weather4x2_optimus: widgetType = 1, orientation = 1
08-30 12:38:00.098  2851  2851 D Weather4x2_optimus: forecast size is 0
08-30 12:38:00.098  2851  2851 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-30 12:38:00.098  2851  2851 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-30 12:38:00.098  2851  2851 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-30 12:38:00.099  2851  2851 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-30 12:38:00.099  2851  2851 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-30 12:38:00.099  2851  2851 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-30 12:38:00.099  2851  2851 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-30 12:38:00.099  2851  2851 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-30 12:38:00.099  2851  2851 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-30 12:38:00.099  2851  2851 I Theme_WeatherAncestor_optimus: WEATHER_CP_ACCU : 
08-30 12:38:00.099  2851  2851 I Theme_WeatherAncestor_optimus: weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
08-30 12:38:00.099  2851  2851 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-30 12:38:00.099  2851  2851 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-30 12:38:00.099  2851  2851 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,08-30 12:38:00.099  2851  2851 D Theme_WeatherAncestor_optimus: setTouchIntent, appWidgetId: 2
08-30 12:38:00.102  2851  2851 D Theme_WeatherAncestor_optimus: url is : null
,08-30 12:38:00.106  2851  2851 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-30 12:38:00.106  2851  2851 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-30 12:38:00.106  2851  2851 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-30 12:38:00.107  2851  2851 D WeatherAncestor: 2 : update view, appWidgetId: 2
08-30 12:38:00.120  2851  2851 D WeatherService: 2 : TimeTick Intent has been processed, Time(hour:min:sec) 12:38:0
,08-30 12:38:00.132   834   834 D PowerManagerServiceEx: releaseWakeLockInternal: lock=246621169 [*alarm*], flags=0x0
,08-30 12:38:00.209   834  2009 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 12:38:00.216   296   354 I ThermalEngine: Sensor:pa_therm0:37000 mC
08-30 12:38:00.274  1947  1947 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,08-30 12:38:00.354  1947  1947 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-30 12:38:00.439   834  2034 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 12:38:00.662   834   855 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 12:38:00.900   834  1942 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 12:38:01.215   834  1872 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 12:38:01.231  1748  2343 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-30 12:38:02.873  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,08-30 12:38:02.873  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 12:38:02.873  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-30 12:38:03.755  1375  1375 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-30 12:38:03.755  1375  1375 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-30 12:38:03.755  1375  1375 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-30 12:38:03.755  1375  1375 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-30 12:38:03.757   477   477 D charger_monitor: init target 500000
08-30 12:38:03.757  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-30 12:38:03.809   477   477 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-30 12:38:03.823  1375  1375 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 339
08-30 12:38:03.823  1375  1375 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-30 12:38:03.823  1375  1375 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 339
,08-30 12:38:03.825  1873  2049 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-30 12:38:03.825  1873  2049 D LEDHandler: Battery Level Remaining: 100%
08-30 12:38:03.825  1873  2049 D LEDHandler: Battery Temp: 339, mChargingStatus=5, mChargingStop=false
08-30 12:38:03.826  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-30 12:38:03.826  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-30 12:38:03.828  1375  1375 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-30 12:38:03.829  2061  3510 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 12:38:03.831   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:38:03.831   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:38:03.831   834  1312 D WifiController: battery changed pluggedType: 2
08-30 12:38:03.874  1375  1375 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 339
08-30 12:38:03.874  1375  1375 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-30 12:38:03.875  1375  1375 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 339
,08-30 12:38:03.876  1873  2049 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-30 12:38:03.876  1873  2049 D LEDHandler: Battery Level Remaining: 100%
08-30 12:38:03.876  1873  2049 D LEDHandler: Battery Temp: 339, mChargingStatus=5, mChargingStop=false
08-30 12:38:03.879  2061  3510 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 12:38:03.880  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-30 12:38:03.880  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-30 12:38:03.882  1375  1375 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-30 12:38:03.883   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:38:03.883   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:38:03.883   834  1312 D WifiController: battery changed pluggedType: 2
08-30 12:38:05.221   296   354 I ThermalEngine: Sensor:pa_therm0:37000 mC
,08-30 12:38:07.438   834  1016 I PowerManagerService: ALS enabled for SRE
,08-30 12:38:07.447   834  1016 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (25880 ms ago)
08-30 12:38:07.512   834  1345 D qdlights: set_light_backlight: 252
,08-30 12:38:07.522   834  1345 D qdlights: set_light_backlight: 248
08-30 12:38:07.538   834  1345 D qdlights: set_light_backlight: 245
,08-30 12:38:07.555   834  1345 D qdlights: set_light_backlight: 242
,08-30 12:38:07.572   834  1345 D qdlights: set_light_backlight: 238
,08-30 12:38:07.588   834  1345 D qdlights: set_light_backlight: 235
,08-30 12:38:07.605   834  1345 D qdlights: set_light_backlight: 232
,08-30 12:38:07.622   834  1345 D qdlights: set_light_backlight: 228
,08-30 12:38:07.638   834  1345 D qdlights: set_light_backlight: 225
,08-30 12:38:07.655   834  1345 D qdlights: set_light_backlight: 222
,08-30 12:38:07.672   834  1345 D qdlights: set_light_backlight: 218
,08-30 12:38:07.688   834  1345 D qdlights: set_light_backlight: 215
,08-30 12:38:07.705   834  1345 D qdlights: set_light_backlight: 212
,08-30 12:38:07.722   834  1345 D qdlights: set_light_backlight: 208
,08-30 12:38:07.738   834  1345 D qdlights: set_light_backlight: 205
,08-30 12:38:07.755   834  1345 D qdlights: set_light_backlight: 202
,08-30 12:38:07.772   834  1345 D qdlights: set_light_backlight: 198
,08-30 12:38:07.788   834  1345 D qdlights: set_light_backlight: 195
,08-30 12:38:07.805   834  1345 D qdlights: set_light_backlight: 192
,08-30 12:38:07.822   834  1345 D qdlights: set_light_backlight: 188
,08-30 12:38:07.838   834  1345 D qdlights: set_light_backlight: 185
,08-30 12:38:07.855   834  1345 D qdlights: set_light_backlight: 182
,08-30 12:38:07.872   834  1345 D qdlights: set_light_backlight: 178
,08-30 12:38:07.880  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 12:38:07.880  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 12:38:07.880  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
08-30 12:38:07.890   834  1345 D qdlights: set_light_backlight: 175
,08-30 12:38:07.907   834  1345 D qdlights: set_light_backlight: 172
,08-30 12:38:07.922   834  1345 D qdlights: set_light_backlight: 168
,08-30 12:38:07.938   834  1345 D qdlights: set_light_backlight: 165
,08-30 12:38:07.955   834  1345 D qdlights: set_light_backlight: 162
,08-30 12:38:07.972   834  1345 D qdlights: set_light_backlight: 158
,08-30 12:38:07.988   834  1345 D qdlights: set_light_backlight: 155
,08-30 12:38:08.005   834  1345 D qdlights: set_light_backlight: 152
,08-30 12:38:08.022   834  1345 D qdlights: set_light_backlight: 148
,08-30 12:38:08.038   834  1345 D qdlights: set_light_backlight: 145
,08-30 12:38:08.055   834  1345 D qdlights: set_light_backlight: 142
,08-30 12:38:08.072   834  1345 D qdlights: set_light_backlight: 138
,08-30 12:38:08.088   834  1345 D qdlights: set_light_backlight: 135
,08-30 12:38:08.105   834  1345 D qdlights: set_light_backlight: 132
,08-30 12:38:08.122   834  1345 D qdlights: set_light_backlight: 128
,08-30 12:38:08.138   834  1345 D qdlights: set_light_backlight: 125
,08-30 12:38:08.155   834  1345 D qdlights: set_light_backlight: 122
,08-30 12:38:08.172   834  1345 D qdlights: set_light_backlight: 118
,08-30 12:38:08.188   834  1345 D qdlights: set_light_backlight: 115
,08-30 12:38:08.205   834  1345 D qdlights: set_light_backlight: 112
,08-30 12:38:08.222   834  1345 D qdlights: set_light_backlight: 108
,08-30 12:38:08.238   834  1345 D qdlights: set_light_backlight: 105
,08-30 12:38:08.255   834  1345 D qdlights: set_light_backlight: 102
,08-30 12:38:08.272   834  1345 D qdlights: set_light_backlight: 98
,08-30 12:38:08.288   834  1345 D qdlights: set_light_backlight: 95
,08-30 12:38:08.305   834  1345 D qdlights: set_light_backlight: 92
,08-30 12:38:08.322   834  1345 D qdlights: set_light_backlight: 88
,08-30 12:38:08.338   834  1345 D qdlights: set_light_backlight: 85
,08-30 12:38:08.355   834  1345 D qdlights: set_light_backlight: 82
,08-30 12:38:08.372   834  1345 D qdlights: set_light_backlight: 78
,08-30 12:38:08.388   834  1345 D qdlights: set_light_backlight: 75
,08-30 12:38:08.405   834  1345 D qdlights: set_light_backlight: 72
,08-30 12:38:08.422   834  1345 D qdlights: set_light_backlight: 68
,08-30 12:38:08.438   834  1345 D qdlights: set_light_backlight: 65
,08-30 12:38:08.455   834  1345 D qdlights: set_light_backlight: 62
,08-30 12:38:08.472   834  1345 D qdlights: set_light_backlight: 58
,08-30 12:38:08.488   834  1345 D qdlights: set_light_backlight: 55
,08-30 12:38:08.505   834  1345 D qdlights: set_light_backlight: 52
,08-30 12:38:08.522   834  1345 D qdlights: set_light_backlight: 48
,08-30 12:38:08.538   834  1345 D qdlights: set_light_backlight: 45
,08-30 12:38:08.555   834  1345 D qdlights: set_light_backlight: 42
,08-30 12:38:08.571   834  1345 D qdlights: set_light_backlight: 38
,08-30 12:38:08.588   834  1345 D qdlights: set_light_backlight: 35
,08-30 12:38:08.605   834  1345 D qdlights: set_light_backlight: 32
,08-30 12:38:08.622   834  1345 D qdlights: set_light_backlight: 28
08-30 12:38:08.638   834  1345 D qdlights: set_light_backlight: 25
,08-30 12:38:08.655   834  1345 D qdlights: set_light_backlight: 22
08-30 12:38:08.672   834  1345 D qdlights: set_light_backlight: 18
,08-30 12:38:08.688   834  1345 D qdlights: set_light_backlight: 15
,08-30 12:38:08.705   834  1345 D qdlights: set_light_backlight: 12
08-30 12:38:08.722   834  1345 D qdlights: set_light_backlight: 10
,08-30 12:38:09.883  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,08-30 12:38:09.883  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-30 12:38:09.883  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-30 12:38:10.161  6562  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 12:38:10.161  6562  6683 I jxcore-log: 
,08-30 12:38:10.173  6562  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 12:38:10.173  6562  6683 I jxcore-log: 
,08-30 12:38:10.177  2061  2076 D BluetoothAdapterService(384514173): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2425983b
08-30 12:38:10.178  6562  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:38:10.178  6562  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:38:10.178  6562  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:38:10.178  6562  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:38:10.178  6562  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:38:10.178  6562  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:38:10.178  6562  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:38:10.178  6562  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:38:10.189  2061  2076 D BluetoothAdapterService(384514173): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2425983b
,08-30 12:38:10.201  6562  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:38:10.205  6562  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 12:38:10.205  6562  6683 I jxcore-log: 
08-30 12:38:10.208  6562  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 12:38:10.208  6562  6683 I jxcore-log: 
08-30 12:38:10.225   296   354 I ThermalEngine: Sensor:pa_therm0:37000 mC
,08-30 12:38:10.782  6562  6683 I jxcore-log: Running unit tests
08-30 12:38:10.782  6562  6683 I jxcore-log: 
08-30 12:38:10.783  6562  6683 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 12:38:10.783  6562  6683 I jxcore-log: Failed to execute UT.
08-30 12:38:10.783  6562  6683 I jxcore-log: 
,08-30 12:38:10.786  6562  6683 I jxcore-log: Unit Test app is loaded
08-30 12:38:10.786  6562  6683 I jxcore-log: 
08-30 12:38:10.794  6562  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:38:10.794  6562  6683 I jxcore-log: 
08-30 12:38:10.799  6562  6683 I jxcore-log: My device name is: LGE-LG-D722
08-30 12:38:10.799  6562  6683 I jxcore-log: 
,08-30 12:38:10.801  6562  6683 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 12:38:10.801  6562  6683 I jxcore-log: 
08-30 12:38:10.827  6562  6562 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 12:38:11.887  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,08-30 12:38:11.887  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 12:38:11.887  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
08-30 12:38:12.889  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 12:38:12.889  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 12:38:12.889  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-30 12:38:14.147   834  1025 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-30 12:38:14.147   834  1025 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-30 12:38:14.147   834  1025 D sensors_hal_Time: tsOffsetIs: Apps: 152582699998; DSPS: 5098558; Offset : -3015178860
,08-30 12:38:14.440   834  1016 I PowerManagerService: ALS enabled for SRE
,08-30 12:38:14.441   834  1016 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (32876 ms ago)
,08-30 12:38:14.444   834  1016 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
08-30 12:38:14.459   834  1016 I PowerManagerService: ALS enabled for SRE
,08-30 12:38:14.459   834  1016 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (32895 ms ago)
08-30 12:38:14.476   834  1016 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,08-30 12:38:14.482   834  1016 I PowerManagerService: Sleeping (uid 1000)...
08-30 12:38:14.482   834  1016 D LPWGController: [updateScreenState] screen on = false
08-30 12:38:14.491   834  1016 D LPWGController: disable proximity sensor
08-30 12:38:14.491   834  1016 D LPWGController: enable proximity sensor
,08-30 12:38:14.511   834  1016 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3f76ce57] by com.android.server.power.ProximitySensorListener.enable():120
,08-30 12:38:14.523   834  1016 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
08-30 12:38:14.523   834  1016 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
08-30 12:38:14.523   834  1016 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
08-30 12:38:14.523   834  1016 I sensors_hal_Ctx: activate: handle is 48, enable
,08-30 12:38:14.525   834  1016 V sensors_hal_Ctx: activate sensors is 1400000000000
08-30 12:38:14.525   834  1016 D sensors_hal_Thresh: enable: handle=48
08-30 12:38:14.525   834  1016 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
08-30 12:38:14.525   834  1016 D sensors_hal_Util: waitForResponse: timeout=1000
08-30 12:38:14.532   834  1026 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
08-30 12:38:14.532   834  1026 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
08-30 12:38:14.532   834  1016 D sensors_hal_Thresh: enable: Received response: 0
08-30 12:38:14.532   834  1016 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (32968 ms ago)
08-30 12:38:14.558   834  1016 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:38:14.558   834  1016 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:38:14.558   834  1016 I Adreno-EGL: Build Date: 03/02/15 Mon
08-30 12:38:14.558   834  1016 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-30 12:38:14.558   834  1016 I Adreno-EGL: Remote Branch: 
08-30 12:38:14.558   834  1016 I Adreno-EGL: Local Patches: 
08-30 12:38:14.558   834  1016 I Adreno-EGL: Reconstruct Branch: 
,08-30 12:38:14.591   244  1287 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1064 us)
,08-30 12:38:14.760   430  1017 I Sensors : sns_pwr.c(273):acquiring wakelock
,08-30 12:38:14.761   834  1026 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
08-30 12:38:14.762   834  1026 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
08-30 12:38:14.762   834  1026 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
08-30 12:38:14.762   834  1026 D sensors_hal_Thresh: processInd: handle 48, count=1
08-30 12:38:14.762   834  1026 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
08-30 12:38:14.762   834  1026 I sensors_hal_Thresh: processInd : proximity state changed - FAR
08-30 12:38:14.762   834  1054 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
08-30 12:38:14.762   834  1054 D sensors_hal_Ctx: poll: count: 256
08-30 12:38:14.762   834  1054 I sensors_hal_Ctx: poll: released wakelock sensor_ind
08-30 12:38:14.762   834  1054 D sensors_hal_Util: waitForResponse: timeout=0
,08-30 12:38:14.763   834  1016 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
08-30 12:38:14.763   834  1016 I LPWGController: current mode = 1  value = 1 1
08-30 12:38:14.765   834  1016 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
08-30 12:38:14.865   834  1016 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,08-30 12:38:15.058  6562  6683 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 12:38:15.058  6562  6683 I jxcore-log: 
,08-30 12:38:15.107   834  1345 D qdlights: set_light_backlight: 0
,08-30 12:38:15.123   834  1016 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,08-30 12:38:15.129   834  1016 I sensors_hal_Ctx: activate: handle is 46, disable
08-30 12:38:15.129   834  1016 V sensors_hal_Ctx: activate sensors is 1000000000000
08-30 12:38:15.129   834  1016 D sensors_hal_LP2: enable: handle=46
08-30 12:38:15.129   834  1016 D sensors_hal_LP2: enable: Disabling sensor handle=46
08-30 12:38:15.129   834  1016 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
08-30 12:38:15.132   244   244 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
08-30 12:38:15.132   244   244 D qdhwcomposer: hwc_blank: Blanking display: 0
08-30 12:38:15.139   834   931 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,08-30 12:38:15.139   834   834 V ActivityManager: Display changed displayId=0
08-30 12:38:15.165   834  1049 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
08-30 12:38:15.165   834  1049 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,08-30 12:38:15.209  1776  1776 D DSDPConnection: Display #0 changed.
,08-30 12:38:15.230   296   354 I ThermalEngine: Sensor:pa_therm0:37000 mC
,08-30 12:38:15.307   244   244 D qdhwcomposer: hwc_blank: Done blanking display: 0
08-30 12:38:15.308   834  1345 D SurfaceControl: Excessive delay in setPowerMode(): 176ms
,08-30 12:38:15.308   244   678 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
08-30 12:38:15.310   834  1345 I QCOM PowerHAL: Got set_interactive hint
08-30 12:38:15.322  6562  6562 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 12:38:15.322  6562  6562 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 12:38:15.325  1375  1408 D KeyguardViewMediator: onScreenTurnedOff(3)
08-30 12:38:15.333  1328  1343 D SmartCoverViewMediator: onScreenTurnedOff(3)
08-30 12:38:15.342  1375  1408 D KeyguardViewMediator: notifyScreenOffLocked
,08-30 12:38:15.346  1328  1343 D SmartCoverViewMediator: notifyScreenOffLocked
08-30 12:38:15.350  1328  1328 D SmartCoverViewMediator: handleNotifyScreenOFF
08-30 12:38:15.375  6562  6562 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3e8dfa35 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@25032320, 16908290=android.view.AbsSavedState$1@25032320}, android:focusedViewId=100}]}]
08-30 12:38:15.375  6562  6562 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 12:38:15.375  6562  6562 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 12:38:15.375  6562  6562 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 12:38:15.381  1375  1408 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
08-30 12:38:15.382  1375  1375 D KeyguardViewMediator: handleNotifyScreenOff
08-30 12:38:15.410  1375  1375 D ScreenTurnOffBySensor: unregisterProximitySensor
,08-30 12:38:15.428  1375  1375 D StatusBarWindowView: onScreenTurnedOff why = 3
,08-30 12:38:15.432   834   834 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
08-30 12:38:15.436   834  1307 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
08-30 12:38:15.439   284  1584 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 834
08-30 12:38:15.440   284  1584 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-30 12:38:15.440   284  1584 V voice   : voice_set_parameters: enter: screen_state=on
,08-30 12:38:15.442   284  1584 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
08-30 12:38:15.442   284  1584 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 12:38:15.442   284  1584 V voice   : voice_set_parameters: exit with code(0)
08-30 12:38:15.442   284  1584 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
08-30 12:38:15.442   284  1584 V msm8974_platform: platform_set_parameters: enter: screen_state=on
08-30 12:38:15.442   284  1584 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 12:38:15.442   284  1584 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 12:38:15.442   284  1584 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
08-30 12:38:15.442   284  1584 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-30 12:38:15.442   284  1584 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 12:38:15.446  1375  1375 D KeyguardUpdateMonitor: handleTimeUpdate
08-30 12:38:15.447  1375  1375 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
08-30 12:38:15.939  6562  6683 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 12:38:15.939  6562  6683 I jxcore-log: 
,08-30 12:38:15.981  6562  6683 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 12:38:15.981  6562  6683 I jxcore-log: 
,08-30 12:38:16.036   834   880 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,08-30 12:38:16.071   834  1384 D SplitWindow: check instance of lgWin Window{606ef62 u0 SearchPanel}
,08-30 12:38:16.089  1909  1909 I QCNEJ   : |CORE| sendScreenState: state:true
,08-30 12:38:16.100  1873  2049 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
08-30 12:38:16.103  1873  2049 D LEDService: stopPatternFlashing()
,08-30 12:38:16.104  1873  2049 D qdlights: set_light_notifications: 0,0,0,0,3
08-30 12:38:16.106  1873  2049 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-30 12:38:16.106  1873  2049 D qdlights: set_light_notifications: 0,0,0,0,3
08-30 12:38:16.107  1873  2049 I LEDService: updateLightsLocked : turn off led
08-30 12:38:16.107  1873  2049 D qdlights: set_light_notifications: 0,0,0,0,3
08-30 12:38:16.108   834  1973 D InputDispatcher: Window went away: Window{bfd76af u0 SearchPanel}
08-30 12:38:16.110  1873  2049 D LEDHandler: RESTART MSG
08-30 12:38:16.110  1375  1375 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
08-30 12:38:16.129  1375  1375 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,08-30 12:38:16.136  1873  1873 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
08-30 12:38:16.137  1873  1873 D Cliptray Service: lockStatus = 0
08-30 12:38:16.139  1850  1850 D LNfcService: action : android.intent.action.SCREEN_ON
08-30 12:38:16.158  1850  6987 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
08-30 12:38:16.158  1850  6987 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
08-30 12:38:16.158  1850  6987 D LNfcService: isRequireNfcCRouting() return true
08-30 12:38:16.158  1850  6987 D LNfcService: isHCERoutingtoHost() return : true
08-30 12:38:16.158  1850  6987 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-30 12:38:16.158  1850  6987 D NfcService: mEnableLPD: true
08-30 12:38:16.158  1850  6987 D NfcService: mEnableReader: false
08-30 12:38:16.158  1850  6987 D NfcService: mEnableHostRouting: true
08-30 12:38:16.158  1850  6987 D NfcService: newParams.techmask= mTechMask: default
08-30 12:38:16.158  1850  6987 D NfcService: mEnableLPD: true
08-30 12:38:16.158  1850  6987 D NfcService: mEnableReader: false
08-30 12:38:16.158  1850  6987 D NfcService: mEnableHostRouting: true
08-30 12:38:16.158  1850  6987 D NfcService: screenState= 3
08-30 12:38:16.158  1850  6987 D NfcService: Discovery configuration equal, not updating.
,08-30 12:38:16.168   834   834 D Ulp_jni : JNI:system_update. Event-0
,08-30 12:38:16.195  1776  1776 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
08-30 12:38:16.203   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:38:16.203   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:38:16.203   834   834 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
,08-30 12:38:16.207  2851  2851 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:38:16
08-30 12:38:16.209  2851  2851 D WeatherService: 2 : ACTION screen on
08-30 12:38:16.211  2851  2851 D WeatherService: 2 : shouldTimeTickRegistered : false
08-30 12:38:16.216  2851  2851 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 12:38:16.216  2851  2851 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:38:16
,08-30 12:38:16.225  4171  4171 D AppCleanupService: android.intent.action.SCREEN_ON
,08-30 12:38:16.247   284   284 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 834
08-30 12:38:16.247   284   284 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-30 12:38:16.247   284   284 V voice   : voice_set_parameters: enter: screen_state=off
08-30 12:38:16.247   284   284 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
08-30 12:38:16.247   284   284 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 12:38:16.247   284   284 V voice   : voice_set_parameters: exit with code(0)
08-30 12:38:16.248   284   284 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
08-30 12:38:16.248   284   284 V msm8974_platform: platform_set_parameters: enter: screen_state=off
08-30 12:38:16.248   284   284 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 12:38:16.248   284   284 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 12:38:16.248   284   284 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-30 12:38:16.248   284   284 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 12:38:16.249   834  1312 D WifiController: CMD_SCREEN_OFF 
08-30 12:38:16.249   834  1312 D WifiController: shouldWifiStayAwake TRUE
08-30 12:38:16.253  1375  1375 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
,08-30 12:38:16.254   834   880 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,08-30 12:38:16.260   430   441 I Sensors : sns_pwr.c(301):releasing wakelock
08-30 12:38:16.289  1909  1909 I QCNEJ   : |CORE| sendScreenState: state:false
,08-30 12:38:16.291  1873  2049 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
08-30 12:38:16.291  1873  2049 D LEDService: stopPatternFlashing()
08-30 12:38:16.291  1873  2049 D qdlights: set_light_notifications: 0,0,0,0,3
08-30 12:38:16.292  1873  1873 D VolumeVibrator: clear
08-30 12:38:16.293  1873  2049 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-30 12:38:16.293  1873  2049 D qdlights: set_light_notifications: 0,0,0,0,3
08-30 12:38:16.295  1873  2049 I LEDService: updateLightsLocked : turn on led
08-30 12:38:16.295  1873  2049 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
08-30 12:38:16.296  1873  2049 E LEDService: Can't handle this request of patternId:0
08-30 12:38:16.296  1873  2049 D LEDHandler: RESTART MSG
08-30 12:38:16.354   834  1889 I ActivityManager: Process com.android.contacts (pid 6726) has died
,08-30 12:38:16.356  1873  1873 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
08-30 12:38:16.357  1850  1850 D LNfcService: action : android.intent.action.SCREEN_OFF
08-30 12:38:16.360  1850  2175 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
08-30 12:38:16.375  1947  1947 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,08-30 12:38:16.388  1776  1776 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,08-30 12:38:16.391   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 12:38:16.391   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:38:16.391   834   834 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
08-30 12:38:16.393  2851  2851 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:38:16
08-30 12:38:16.393  2851  2851 D WeatherService: 2 : ACTION screen off
08-30 12:38:16.395  2851  2851 D WeatherService: 2 : TimeTick Receiver Unregister
08-30 12:38:16.395  2851  2851 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:38:16
08-30 12:38:16.398  4171  4171 D AppCleanupService: android.intent.action.SCREEN_OFF
08-30 12:38:16.401  4171  6992 D AppCleanupService: AppUsageStatsSaveTask
,08-30 12:38:16.465  1850  2689 E NxpNfcJni: getReconnectState = 0x0
,08-30 12:38:16.546   834  1973 I ActivityManager: Process com.android.gallery3d (pid 6705) has died
,08-30 12:38:16.548  1850  2175 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-30 12:38:16.548  1850  2175 D LCardEmulationManager: getDefaultRoute
08-30 12:38:16.548  1850  2175 D LNfcService: isRequireNfcCRouting() return true
08-30 12:38:16.549  1850  2175 D LNfcService: isHCERoutingtoHost() return : true
08-30 12:38:16.549  1850  2175 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-30 12:38:16.549  1850  2175 D NfcService: mEnableLPD: true
08-30 12:38:16.549  1850  2175 D NfcService: mEnableReader: false
08-30 12:38:16.549  1850  2175 D NfcService: mEnableHostRouting: true
08-30 12:38:16.549  1850  2175 D NfcService: newParams.techmask= mTechMask: 0
08-30 12:38:16.549  1850  2175 D NfcService: mEnableLPD: true
08-30 12:38:16.549  1850  2175 D NfcService: mEnableReader: false
08-30 12:38:16.549  1850  2175 D NfcService: mEnableHostRouting: true
08-30 12:38:16.549  1850  2175 D NfcService: screenState= 1
08-30 12:38:16.579  1850  2689 E NxpNfcJni: getReconnectState = 0x0
,08-30 12:38:18.456  6562  6683 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 12:38:18.456  6562  6683 I jxcore-log: 
,08-30 12:38:18.849  6562  6683 I jxcore-log: ERROR runTests: 
08-30 12:38:18.849  6562  6683 I jxcore-log: 
,08-30 12:38:18.852  6562  6683 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 12:38:18.852  6562  6683 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
08-30 12:38:18.853  6562  6683 I jxcore-log: WARN testUtils: logCallback not set!
08-30 12:38:18.853  6562  6683 I jxcore-log: 
08-30 12:38:18.868  6562  6683 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:38:18.868  6562  6683 I jxcore-log:     _functionName: 'loadFile',
08-30 12:38:18.868  6562  6683 I jxcore-log:     _lineNumber: '26',
08-30 12:38:18.868  6562  6683 I jxcore-log:     _columnNumber: '11',
08-30 12:38:18.868  6562  6683 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 12:38:18.868  6562  6683 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:38:18.868  6562  6683 I jxcore-log:     _functionName: '',
08-30 12:38:18.868  6562  6683 I jxcore-log:     _lineNumber: '38',
08-30 12:38:18.868  6562  6683 I jxcore-log:     _columnNumber: '7',
08-30 12:38:18.868  6562  6683 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 12:38:18.868  6562  6683 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:38:18.868  6562  6683 I jxcore-log:     _functionName: '',
08-30 12:38:18.868  6562  6683 I jxcore-log:     _lineNumber: '35',
08-30 12:38:18.868  6562  6683 I jxcore-log:     _columnNumber: '3',
08-30 12:38:18.868  6562  6683 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 12:38:18.868  6562  6683 I jxcore-log:   { _fileName: 'module.js',
08-30 12:38:18.868  6562  6683 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 12:38:18.868  6562  6683 I jxcore-log:     _lineNumber: '621',
08-30 12:38:18.868  6562  6683 I jxcore-log:     _columnNumber: '8',
08-30 12:38:18.868  6562  6683 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 12:38:18.868  6562  6683 I jxcore-log:   { _fileName: 'module.js',
08-30 12:38:18.868  6562  6683 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 12:38:18.868  6562  6683 I jxcore-log:     _lineNumber: '651',
08-30 12:38:18.868  6562  6683 I jxcore-log:     _columnNumber: '1',
08-30 12:38:18.868  6562  6683 I jxcore-log:    
,08-30 12:38:18.868  6562  6683 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 12:38:18.868  6562  6683 I jxcore-log: 
08-30 12:38:18.869  6562  6683 E jxcore-log: Error: 
08-30 12:38:18.869  6562  6683 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 12:38:18.869  6562  6683 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 12:38:18.869  6562  6683 E jxcore-log: 
08-30 12:38:20.234   296   354 I ThermalEngine: Sensor:pa_therm0:37000 mC
,08-30 12:38:20.353  1375  1375 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,08-30 12:38:20.362   834  1282 V AlarmManager: ELAPSED_WAKEUP set : Alarm{35aff8f3 type 2 when 158784 com.android.systemui} when 158784
,08-30 12:38:20.392  1776  1804 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
08-30 12:38:20.424  1776  1804 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-30 12:38:20.424  1776  1804 D PhoneUtils: getPhoneCount() sPhoneCount = 1
,08-30 12:38:20.430  1776  1804 V TelecomServiceImpl: getCallState : 0
08-30 12:38:20.434  1776  2322 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
08-30 12:38:20.434  1776  2322 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-30 12:38:20.434  1776  2322 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-30 12:38:20.440  1375  1375 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
,08-30 12:38:20.443  1375  1375 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
08-30 12:38:20.797  6999  6999 D AndroidRuntime: 
08-30 12:38:20.797  6999  6999 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 12:38:20.802  6999  6999 D AndroidRuntime: CheckJNI is OFF
,08-30 12:38:21.040  6999  6999 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 12:38:21.068   834   882 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,08-30 12:38:21.072   834   882 I ActivityManager: Killing 6562:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
08-30 12:38:21.125   834   857 I WindowState: WIN DEATH: Window{3d3d57d1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 12:38:21.130   834   857 D InputDispatcher: Focus left window: Window{3d3d57d1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 12:38:21.130   834   857 D InputDispatcher: Window went away: Window{3d3d57d1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 12:38:21.176   834  1059 W PackageSettings: Skipping PackageSetting{fcd2249 com.example.hello/10317} due to missing metadata
,08-30 12:38:21.218   834   882 I ActivityManager:   Force finishing activity ActivityRecord{3b7de35f u0 com.test.thalitest/.MainActivity t259}
08-30 12:38:21.230   834   834 V ActivityManager: Display changed displayId=0
,08-30 12:38:21.235  1776  1776 D DSDPConnection: Display #0 changed.
08-30 12:38:21.250   834  1898 W ActivityManager: Spurious death for ProcessRecord{38b939b0 6562:com.test.thalitest/u0a30}, curProc for 6562: null
,08-30 12:38:21.252   834  1059 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
08-30 12:38:21.254   834  1059 I ActivityManager:   Force finishing activity ActivityRecord{3b7de35f u0 com.test.thalitest/.MainActivity t259 f}
08-30 12:38:21.254   834  1059 W ActivityManager: Duplicate finish request for ActivityRecord{3b7de35f u0 com.test.thalitest/.MainActivity t259 f}
,08-30 12:38:21.327  1947  1947 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
08-30 12:38:21.329  1375  1375 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-30 12:38:21.338  1909  1909 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,08-30 12:38:21.342  2026  2026 I art     : Explicit concurrent mark sweep GC freed 2404(241KB) AllocSpace objects, 2(47KB) LOS objects, 40% free, 12MB/21MB, paused 8.215ms total 83.475ms
08-30 12:38:21.345  1748  2466 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 12:38:21.345   834  1284 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 12:38:21.349  1947  1947 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
08-30 12:38:21.361  3675  3675 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-30 12:38:21.364  3424  3424 I art     : Explicit concurrent mark sweep GC freed 2993(147KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 16MB/21MB, paused 1.043ms total 102.283ms
08-30 12:38:21.365  3675  3675 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 12:38:21.365  3675  3675 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 12:38:21.365  3675  3675 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-30 12:38:21.366  3675  3675 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:38:21.366  3675  3675 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:38:21.366  3675  3675 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:38:21.366  3675  3675 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-30 12:38:21.366  3675  3675 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:38:21.366  3675  3675 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:38:21.366  3675  3675 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-30 12:38:21.366  3675  3675 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-30 12:38:21.406   834   882 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7030 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 12:38:21.453  1947  1947 I [LGHome]EVENT: [LauncherModel.java:1358:startLoader()]startLoader isLaunching=true
,08-30 12:38:21.455  1947  2055 I [LGHome]Launcher.Model: [LauncherModel.java:1475:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-30 12:38:21.463  1375  1514 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 12:38:21.463  1375  1514 D KeyguardModel: createShortcutInfo...
08-30 12:38:21.465  1375  1375 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-30 12:38:21.467  1947  1947 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-30 12:38:21.468  1375  1514 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 12:38:21.468  1375  1514 D KeyguardModel: createShortcutInfo...
,08-30 12:38:21.473  1375  1514 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:38:21.478  1375  1514 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 12:38:21.480  1375  1514 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 12:38:21.480  1375  1514 D KeyguardModel: createShortcutInfo...
08-30 12:38:21.482  1375  1514 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:38:21.482  1375  1514 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-30 12:38:21.498  1947  1947 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-30 12:38:21.498  1947  1947 I Activity: Activity.onPostResume() called 
,08-30 12:38:21.507  1375  1514 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 12:38:21.507  1375  1514 D KeyguardModel: createShortcutInfo...
08-30 12:38:21.523  1947  1947 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
,08-30 12:38:21.526  1375  1514 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:38:21.526  1375  1514 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 12:38:21.529  1375  1514 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 12:38:21.529  1375  1514 D KeyguardModel: createShortcutInfo...
08-30 12:38:21.544  1947  7049 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,08-30 12:38:21.555   834   834 I art     : Explicit concurrent mark sweep GC freed 38828(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 13.065ms total 269.104ms
08-30 12:38:21.556   834  1059 I art     : WaitForGcToComplete blocked for 72.553ms for cause Explicit
,08-30 12:38:21.577  1375  1375 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-30 12:38:21.577  1375  1375 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-30 12:38:21.579  1375  1375 D KeyguardModel: handleShortcutListChanged...
08-30 12:38:21.583   834   929 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-30 12:38:21.585   834   929 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-30 12:38:21.585  1375  1375 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-30 12:38:21.585   834   929 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-30 12:38:21.585  1375  1375 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-30 12:38:21.585  1375  1375 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-30 12:38:21.585  1375  1375 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-30 12:38:21.585   834   929 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-30 12:38:21.585   834   929 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-30 12:38:21.585   834   929 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@33a8d210,  pkg=WindowManager.LayoutParams
08-30 12:38:21.585   834   929 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-30 12:38:21.587   834   857 D InputDispatcher: Focus entered window: Window{1d9f9f4d u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-30 12:38:21.598  1375  1514 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 12:38:21.599  1375  1514 D KeyguardModel: createShortcutInfo...
08-30 12:38:21.601  1375  1514 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 12:38:21.601  1375  1514 D KeyguardModel: createShortcutInfo...
,08-30 12:38:21.602  7030  7030 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 12:38:21.603  7030  7030 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:38:21.605  1947  1947 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 12:38:21.606  1947  1947 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 12:38:21.606  1947  1947 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-30 12:38:21.606  7030  7030 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 12:38:21.610  1375  1514 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:38:21.610  1375  1514 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 12:38:21.613  1375  1514 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 12:38:21.614  1375  1514 D KeyguardModel: createShortcutInfo...
,08-30 12:38:21.616  1375  1514 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:38:21.616  1375  1514 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 12:38:21.617  1947  1947 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-30 12:38:21.618  1375  1514 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 12:38:21.618  1375  1514 D KeyguardModel: createShortcutInfo...
08-30 12:38:21.619  1375  1514 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:38:21.619  1375  1514 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 12:38:21.620  1375  1514 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 12:38:21.620  1375  1514 D KeyguardModel: createShortcutInfo...
08-30 12:38:21.621  1947  1947 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-30 12:38:21.621  1947  1947 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-30 12:38:21.624   834  1889 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-30 12:38:21.625   834  1889 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6562 uid 10030
08-30 12:38:21.627  1375  1375 D KeyguardModel: handleShortcutListChanged...
,08-30 12:38:21.657   834   834 D administrator: Handling package changes for user 0
,08-30 12:38:21.699  1947  1947 I [LGHome]Launcher.Model: [LauncherModel.java:2270:run()] LauncherModel bind current page shortcut
,08-30 12:38:21.705  1947  1947 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-30 12:38:21.724   834   931 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{83163d9 u0 com.lge.launcher2/.Launcher t258} time:160160
,08-30 12:38:21.746  1947  1947 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,08-30 12:38:21.750  1947  1947 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-30 12:38:21.752  1947  1947 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-30 12:38:21.754  1947  1947 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-30 12:38:21.792  1947  1947 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,08-30 12:38:21.814   834   834 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 12:38:21.814   834   834 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-30 12:38:21.817   834   834 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 12:38:21.823   834  1347 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
08-30 12:38:21.850  1947  1947 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-30 12:38:21.851  1947  1947 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
08-30 12:38:21.851  1947  1947 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,08-30 12:38:21.890  7030  7030 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 12:38:21.900  1947  1947 W Resources: Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
08-30 12:38:21.904  1947  1947 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
08-30 12:38:21.904  1947  1947 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
08-30 12:38:21.905  1947  1947 W Resources: Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
08-30 12:38:21.907   834  1059 I art     : Explicit concurrent mark sweep GC freed 12196(1392KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.483ms total 350.333ms
08-30 12:38:21.909  1947  1947 W Resources: Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
,08-30 12:38:21.920  1947  1947 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
08-30 12:38:21.921  1947  1947 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
08-30 12:38:21.923  1947  1947 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
08-30 12:38:21.924  1947  1947 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
08-30 12:38:21.924  1947  1947 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
,08-30 12:38:21.930  7030  7030 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
08-30 12:38:21.932  1850  1850 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-30 12:38:21.932  1850  1850 D LCardEmulationManager: getDefaultRoute
08-30 12:38:21.934  1947  1947 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
08-30 12:38:21.943  1947  1947 W Resources: Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,08-30 12:38:21.982  6999  6999 D AndroidRuntime: Shutting down VM
,08-30 12:38:21.994   834   880 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 12:38:22.037   834  1059 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7053 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-30 12:38:22.064  1947  1947 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,08-30 12:38:22.127   834   880 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-30 12:38:22.161  1947  1947 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-30 12:38:22.162  1947  1947 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
,08-30 12:38:22.163  1947  1947 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
,08-30 12:38:22.163  1947  1947 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-30 12:38:22.169  7030  7030 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-30 12:38:22.176  1947  1947 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,08-30 12:38:22.177  1947  1947 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-30 12:38:22.179  1947  1947 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 12:38:22.180  1947  1947 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-30 12:38:22.181  1947  2154 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-30 12:38:22.181  1624  1624 E b       : Unable to connect to the editor to retrieve text... will retry later
08-30 12:38:22.181  1947  2154 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-30 12:38:22.185  1947  1947 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-30 12:38:22.187  1947  1947 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
08-30 12:38:22.188  1947  1947 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-30 12:38:22.190  1947  1947 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
08-30 12:38:22.191  1947  1947 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
,08-30 12:38:22.202  1947  1947 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
08-30 12:38:22.202  1947  1947 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-30 12:38:22.202  1947  1947 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-30 12:38:22.223   834   857 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7075 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-30 12:38:22.258  1947  1947 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,08-30 12:38:22.281  1947  1947 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-30 12:38:22.282  1947  1947 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-30 12:38:22.282  1947  1947 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-30 12:38:22.338  7075  7075 I AppUp4:AppBoxCP: onCreate
,08-30 12:38:22.347  7075  7075 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-30 12:38:22.355  1947  2136 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
,08-30 12:38:22.357  1947  1947 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@c841be2 time:160793
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-30 12:38:22.360  7075  7075 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-30 12:38:22.361  7075  7075 D AndroidRuntime: Shutting down VM
--------- beginning of crash
08-30 12:38:22.362  7075  7075 E AndroidRuntime: FATAL EXCEPTION: main
08-30 12:38:22.362  7075  7,075 E AndroidRuntime: Process: com.lge.appbox.client, PID: 7075
08-30 12:38:22.362  7075  7075 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
08-30 12:38:22.362  7075  7075 E AndroidRuntime: 	... 11 more
,08-30 12:38:22.378   834  7094 E DropBoxManagerService: Can't write: system_app_crash
08-30 12:38:22.378   834  7094 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-30 12:38:22.378   834  7094 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:38:22.378   834  7094 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:38:22.378   834  7094 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 12:38:22.378   834  7094 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 12:38:22.378   834  7094 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-30 12:38:22.378   834  7094 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12621)
08-30 12:38:22.378   834  7094 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:38:22.378   834  7094 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 12:38:22.378   834  7094 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:38:22.378   834  7094 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:38:22.378   834  7094 E DropBoxManagerService: 	... 5 more
08-30 12:38:22.410  1947  1947 I art     : Explicit concurrent mark sweep GC freed 26150(1429KB) AllocSpace objects, 15(2MB) LOS objects, 40% free, 15MB/25MB, paused 989us total 49.579ms

```
