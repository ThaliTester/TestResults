#### Test 78968685940d272_thali05_LGE-LG-D722 Logs


```
--------- beginning of main
07-27 09:39:21.561  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:39:21.561  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:21.562  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,--------- beginning of system
07-27 09:39:22.537   842  1287 V AlarmManager: RTC_WAKEUP set : Alarm{96b936 type 0 when 1469605159632 com.android.vending} when 1469605159632
07-27 09:39:22.545  5632  5697 I Finsky  : [675] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
07-27 09:39:22.562  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:39:22.562  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:22.562  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
07-27 09:39:22.602  6588  6588 D AndroidRuntime: 
07-27 09:39:22.602  6588  6588 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-27 09:39:22.609  6588  6588 D AndroidRuntime: CheckJNI is OFF
07-27 09:39:22.629  3711  6595 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
07-27 09:39:22.784  5632  5697 I Finsky  : [675] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
07-27 09:39:22.785  5632  5632 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
07-27 09:39:22.884  6588  6588 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-27 09:39:22.912   842  1065 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-27 09:39:22.985   842  1065 D ActivityManager: setTaskToReturnTo : TaskRecord{225f8037 #253 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-27 09:39:22.987   842  1065 D ActivityManager: setTaskToReturnTo : TaskRecord{225f8037 #253 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-27 09:39:23.010   842  1065 D WindowStateEx: AppWindowTokenEx init.. 
07-27 09:39:23.025   842  1039 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-27 09:39:23.046   842  1065 D InputDispatcher: Focus left window: Window{28eefb41 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
07-27 09:39:23.046  6588  6588 D AndroidRuntime: Shutting down VM
07-27 09:39:23.054   842  1039 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-27 09:39:23.071  1948  1948 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
07-27 09:39:23.085   842  1039 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-27 09:39:23.085   842  1039 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-27 09:39:23.106   842  1039 D SplitWindow: check instance of lgWin Window{14983f2f u0 Starting com.test.thalitest}
07-27 09:39:23.160   842  1947 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6628 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-27 09:39:23.174  1948  1948 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
07-27 09:39:23.224  1948  1948 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
07-27 09:39:23.233   842  1898 I WindowStateAnimator: Starting window displayed
07-27 09:39:23.240   842  1036 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
07-27 09:39:23.241   842  1036 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
07-27 09:39:23.245   842  1036 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
07-27 09:39:23.245   842  1036 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
07-27 09:39:23.245   842  1036 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-27 09:39:23.247   842  1036 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@fece82b,  pkg=WindowManager.LayoutParams
07-27 09:39:23.248   842  1036 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
07-27 09:39:23.253  1378  1378 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
07-27 09:39:23.255  1378  1378 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
07-27 09:39:23.255  1378  1378 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
07-27 09:39:23.255  1378  1378 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
07-27 09:39:23.265  2026  2026 I HotwordDetector: Closing mic
,07-27 09:39:23.277  2026  2561 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@1bee75ee
,07-27 09:39:23.277  2026  2561 V AudioRecord: stop()
07-27 09:39:23.277  2026  2561 D AudioRecord: AudioRecord->stop()
07-27 09:39:23.278   281  1301 V AudioFlinger: RecordHandle::stop()
07-27 09:39:23.279   281  1301 V AudioFlinger: RecordThread::stop
,07-27 09:39:23.284   281  1301 V AudioFlinger: Record stopped OK
07-27 09:39:23.285   281  1301 V AudioPolicyManager: stopInput() input 17
07-27 09:39:23.286   281  1301 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
07-27 09:39:23.286   281  1301 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
07-27 09:39:23.286   281  1067 V AudioPolicyService: AudioCommandThread() waking up
07-27 09:39:23.286   281  1067 V AudioPolicyService: AudioCommandThread() processing release audio patch
,07-27 09:39:23.287   281  1067 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
07-27 09:39:23.287   281  1067 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
07-27 09:39:23.287   281  1067 V AudioFlinger: ThreadBase::setParameters() routing=0
07-27 09:39:23.287   281  1067 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
07-27 09:39:23.288   281  2579 V AudioFlinger: processConfigEvents_l() remaining events 1
07-27 09:39:23.289   281  2579 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3824000
07-27 09:39:23.291   281  2579 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
,07-27 09:39:23.335   281  2579 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
07-27 09:39:23.335   281  2579 V audio_hw_primary: disable_audio_route: enter: usecase(7)
07-27 09:39:23.335   281  2579 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
,07-27 09:39:23.335   281  2579 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-27 09:39:23.337   281  2579 V audio_hw_primary: disable_audio_route: exit
07-27 09:39:23.337   281  2579 E audio_hw_primary: disable_snd_device: enter 144
07-27 09:39:23.337   281  2579 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
07-27 09:39:23.337   281  2579 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
07-27 09:39:23.341   281  2579 V audio_hw_primary: stop_input_stream: exit: status(0)
07-27 09:39:23.341   281  2579 V audio_hw_primary: in_standby: exit:  status(0)
07-27 09:39:23.341   281  2579 V AudioFlinger: RecordThread: loop stopping
07-27 09:39:23.342   281  1067 V AudioPolicyService: AudioCommandThread() going to sleep
07-27 09:39:23.342   281  1301 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
07-27 09:39:23.342   281  1301 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
07-27 09:39:23.342   281  1301 V AudioPolicyService: AudioCommandThread() adding update audio patch list
07-27 09:39:23.342   281  1301 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
07-27 09:39:23.342   281  1068 V AudioPolicyService: AudioCommandThread() waking up
,07-27 09:39:23.342   281  1068 V AudioPolicyService: AudioCommandThread() processing update audio patch list
07-27 09:39:23.343   281  1068 V AudioPolicyService: AudioCommandThread() going to sleep
07-27 09:39:23.343   281  1301 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
07-27 09:39:23.344   281  1301 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
07-27 09:39:23.344   281  1067 V AudioPolicyService: AudioCommandThread() waking up
07-27 09:39:23.344   281  1067 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
07-27 09:39:23.344   281  1067 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 281
07-27 09:39:23.344   281  1067 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
07-27 09:39:23.344   281  1067 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
07-27 09:39:23.344   281  2579 V AudioFlinger: RecordThread: loop starting
07-27 09:39:23.344   281  2579 V AudioFlinger: processConfigEvents_l() remaining events 1
07-27 09:39:23.344   281  2579 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
07-27 09:39:23.344   281  2579 V audio_hw_primary: in_set_parameters: exit: status(0)
07-27 09:39:23.344   281  2579 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3824000
07-27 09:39:23.344   281  2579 V AudioFlinger: RecordThread: loop stopping
07-27 09:39:23.344   281  1067 V AudioPolicyService: AudioCommandThread() going to sleep
07-27 09:39:23.346  6628  6628 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-27 09:39:23.347  2026  2561 V AudioRecord: stop()
07-27 09:39:23.347  2026  2561 V AudioRecord: stop()
07-27 09:39:23.347  2026  2561 V AudioRecord: stop()
,07-27 09:39:23.350   281   281 V AudioFlinger: RecordHandle::stop()
07-27 09:39:23.350   281   281 V AudioFlinger: RecordThread::stop
07-27 09:39:23.350   281   281 V AudioPolicyManager: releaseInput() 17
07-27 09:39:23.350   281   281 V AudioPolicyManager: closeInput(17)
07-27 09:39:23.350   281   281 V AudioFlinger: closeInput() 17
07-27 09:39:23.350   281   281 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-27 09:39:23.350   842  1935 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-27 09:39:23.350   281   281 V AudioFlinger: ThreadBase::exit
,07-27 09:39:23.350  1378  2352 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-27 09:39:23.350   281  2579 V AudioFlinger: RecordThread: loop starting
07-27 09:39:23.350  3144  3162 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-27 09:39:23.350   281  2579 V AudioFlinger: RecordThread 0xb3824000 exiting
07-27 09:39:23.351  1814  2683 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-27 09:39:23.351  2026  5985 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-27 09:39:23.351  2077  3487 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-27 09:39:23.351  2871  2886 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-27 09:39:23.352   281   281 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546dd40)
07-27 09:39:23.352   281   281 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
07-27 09:39:23.352   281   281 V audio_hw_primary: in_standby: exit:  status(0)
07-27 09:39:23.352   281   281 V AudioPolicyService: AudioCommandThread() adding update audio port list
07-27 09:39:23.352   281   281 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
07-27 09:39:23.352   281  1068 V AudioPolicyService: AudioCommandThread() waking up
07-27 09:39:23.352   281  1068 V AudioPolicyService: AudioCommandThread() processing update audio port list
07-27 09:39:23.352   281  1068 V AudioPolicyService: AudioCommandThread() going to sleep
07-27 09:39:23.353   281   281 V AudioPolicyManager: releaseInput() exit
07-27 09:39:23.353   281   281 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
,07-27 09:39:23.353   281   281 V AudioFlinger: removeClient_l() pid 2026, calling pid 281
07-27 09:39:23.353   281   281 V AudioFlinger: releasing 16 from 2026 for -1
07-27 09:39:23.353   281   281 V AudioFlinger:  decremented refcount to 0
07-27 09:39:23.353   281   281 V AudioFlinger: purging stale effects
07-27 09:39:23.362  2026  2569 I HotwordRecognitionRnr: Stopping hotword detection.
,07-27 09:39:23.367  2026  2572 I HotwordRecognitionRnr: Hotword detection finished
07-27 09:39:23.436  6628  6628 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,07-27 09:39:23.490   294   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,07-27 09:39:23.493  6628  6628 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 8678-8683)
07-27 09:39:23.494  6628  6628 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 09:39:23.517  6628  6628 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3e876be9}
,07-27 09:39:23.518  6628  6628 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 09:39:23.519  6628  6628 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 09:39:23.533  6628  6628 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-27 09:39:23.534  6628  6628 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 09:39:23.536  6628  6628 E SysUtils: ApplicationContext is null in ApplicationStatus
07-27 09:39:23.555  6628  6628 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-27 09:39:23.561  6628  6628 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 09:39:23.561  6628  6628 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 09:39:23.561  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:39:23.561  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:23.561  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
07-27 09:39:23.562  6628  6628 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 09:39:23.562  6628  6628 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 09:39:23.562  6628  6628 I Adreno-EGL: Build Date: 03/02/15 Mon
07-27 09:39:23.562  6628  6628 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-27 09:39:23.562  6628  6628 I Adreno-EGL: Remote Branch: 
07-27 09:39:23.562  6628  6628 I Adreno-EGL: Local Patches: 
07-27 09:39:23.562  6628  6628 I Adreno-EGL: Reconstruct Branch: 
07-27 09:39:23.636   281  1357 V AudioPolicyService: registerClient() client 0xb551c640, uid 10030
,07-27 09:39:23.673   842  1038 D BluetoothManagerService: Message: 20
07-27 09:39:23.673   842  1038 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26d281be:true
,07-27 09:39:23.690  2077  2095 D BluetoothAdapterService(197362447): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d3f1c5d
,07-27 09:39:23.729   842  1947 I ActivityManager: Start proc com.google.process.gapps for content provider com.google.android.gsf/.settings.GoogleSettingsProvider: pid=6673 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,07-27 09:39:23.854  6673  6673 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,07-27 09:39:23.895  6628  6628 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 09:39:23.909  6628  6628 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-27 09:39:23.914  6628  6628 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-27 09:39:23.917  6628  6628 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-27 09:39:23.917  6628  6628 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-27 09:39:23.930  6628  6628 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-27 09:39:23.942  6628  6628 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 09:39:23.942  6628  6628 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 09:39:23.977  6673  6673 I GoogleHttpClient: GMS http client unavailable, use old client
,07-27 09:39:24.008  6628  6628 I Activity: Activity.onPostResume() called 
,07-27 09:39:24.011  6673  6673 I GoogleHttpClient: GMS http client unavailable, use old client
07-27 09:39:24.017  6628  6702 D OpenGLRenderer: Render dirty regions requested: true
07-27 09:39:24.017  6628  6702 I OpenGLRenderer: Initialized EGL, version 1.4
07-27 09:39:24.025  6628  6702 D OpenGLRenderer: Enabling debug mode 0
,07-27 09:39:24.042  6628  6628 D Atlas   : Validating map...
,07-27 09:39:24.047   842  3636 D SplitWindow: check instance of lgWin Window{2d4a8ba5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 09:39:24.057  6628  6663 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-27 09:39:24.063   842   861 I ActivityManager: Killing 6478:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
07-27 09:39:24.130   842  1856 W libprocessgroup: failed to open /acct/uid_10069/pid_6478/cgroup.procs: No such file or directory
,07-27 09:39:24.152   842  2012 D InputDispatcher: Focus entered window: Window{2d4a8ba5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-27 09:39:24.215   842  1884 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,07-27 09:39:24.223   842  1039 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s100ms
07-27 09:39:24.224   842  1039 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1d4489a4 u0 com.test.thalitest/.MainActivity t253} time:109413
07-27 09:39:24.238  6628  6628 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@340a912a time:109428
,07-27 09:39:24.292  6628  6628 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6628
,07-27 09:39:25.010  6628  6628 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-27 09:39:25.051  2836  2836 I MusicWidget: mDelayedStopHandler : unbind
,07-27 09:39:25.075  2871  2871 I MusicBrowser: [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,07-27 09:39:25.077  2871  2871 I MusicBrowser: [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
07-27 09:39:25.077  2871  2871 I MusicBrowser: [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
07-27 09:39:25.079  2871  2871 D MusicBrowser: [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
07-27 09:39:25.079  2871  2871 D MusicBrowser: [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
07-27 09:39:25.079  2871  2871 D MusicBrowser: [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
07-27 09:39:25.083  2871  2871 I MusicBrowser: [MediaPlaybackService.java:2085:onDestroy()] oooooo 
07-27 09:39:25.083  2871  2871 I MusicBrowser: [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
07-27 09:39:25.094   842  1947 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@26d62159com.lge.music.MediaPlaybackService$6@2b2b811e
,07-27 09:39:25.098  2871  2871 D MusicBrowser: [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
07-27 09:39:25.101  2871  2871 I MusicBrowser: [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
07-27 09:39:25.102  2871  2871 I MusicBrowser: [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
07-27 09:39:25.103  2871  2871 I MusicBrowser: [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
07-27 09:39:25.106  2871  2871 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@c78f9c
,07-27 09:39:25.108  2871  2871 I MusicBrowser: [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
07-27 09:39:25.111  2871  2871 I MusicBrowser: [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
07-27 09:39:25.112  2871  2871 I MusicBrowser: [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
07-27 09:39:25.112  2871  2871 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
07-27 09:39:25.112  2871  2871 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
07-27 09:39:25.113  2871  2871 I MusicBrowser: [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
07-27 09:39:25.113  2871  2871 I MusicBrowser: [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
07-27 09:39:25.114  2871  2871 I MusicBrowser: [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
07-27 09:39:25.114  2871  2871 I MusicBrowser: [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
07-27 09:39:25.115  2871  2871 I MusicBrowser: [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
07-27 09:39:25.117  2871  2871 I MusicBrowser: [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,07-27 09:39:25.121  2871  2871 I MusicBrowser: [MediaPlaybackService.java:6745:release()] oooooo 
,07-27 09:39:25.123  2871  2871 I MusicBrowser: [MediaPlaybackService.java:6706:stop()] oooooo 
,07-27 09:39:25.125  2871  2871 I MediaPlayer[Native]: reset
07-27 09:39:25.138  2871  2871 V MediaPlayer[Native]: setListener
07-27 09:39:25.138  2871  2871 V MediaPlayer[Native]: disconnect
07-27 09:39:25.138  2871  2871 V MediaPlayer[Native]: destructor
07-27 09:39:25.140   281   281 V AudioFlinger: releasing 19 from 2871 for -1
07-27 09:39:25.140   281   281 V AudioFlinger:  decremented refcount to 0
07-27 09:39:25.140   281   281 V AudioFlinger: purging stale effects
07-27 09:39:25.141  2871  2871 V MediaPlayer[Native]: disconnect
,07-27 09:39:25.145  2871  2871 D MusicBrowser: [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
07-27 09:39:25.154  2871  2871 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305010
,07-27 09:39:25.154  2871  2871 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
07-27 09:39:25.156  2871  2871 I MusicBrowser: [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
07-27 09:39:25.156  2871  2871 I MusicBrowser: [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
07-27 09:39:25.157  2871  2871 V MusicBrowser: [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
07-27 09:39:25.157  2871  2871 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 504450559
07-27 09:39:25.157  2871  2871 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 504450559
07-27 09:39:25.158  2871  2871 I SmartShareClient: [SmartShareManagerClient] terminate service: 2871/MediaPlaybackService/103015458
07-27 09:39:25.161  2871  2871 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
07-27 09:39:25.161  2871  2871 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@255c17cc
07-27 09:39:25.172  2871  2871 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,07-27 09:39:25.174  2871  2871 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
07-27 09:39:25.175  2871  2871 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
07-27 09:39:25.175  2871  2871 I MusicBrowser: [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
07-27 09:39:25.176  2871  2871 D MusicBrowser: [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
07-27 09:39:25.178   842  3636 I ActivityManager: Killing 6495:com.google.android.apps.plus/u0a86 (adj 15): empty #11
07-27 09:39:25.178  2871  2871 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
07-27 09:39:25.208  6628  6706 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426134272
,07-27 09:39:25.211   842  1898 W libprocessgroup: failed to open /acct/uid_10086/pid_6495/cgroup.procs: No such file or directory
,07-27 09:39:25.217  6628  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 09:39:25.217  6628  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 09:39:25.217  6628  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 09:39:25.217  6628  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 09:39:25.217  6628  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-27 09:39:25.218  6628  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21fb0bfc added. We now have 1 listener(s)
07-27 09:39:25.221   842   861 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-27 09:39:25.227  6628  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
07-27 09:39:25.229  6628  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
07-27 09:39:25.229  6628  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 09:39:25.230  6628  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 09:39:25.234  6628  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 09:39:25.234  6628  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 09:39:25.234  6628  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 09:39:25.234  6628  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
07-27 09:39:25.234  6628  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 09:39:25.234  6628  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 09:39:25.234  6628  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 09:39:25.234  6628  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 09:39:25.234  6628  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 09:39:25.234  6628  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 09:39:25.234  6628  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-27 09:39:25.234  6628  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@245cb10b added. We now have 1 listener(s)
07-27 09:39:25.234  6628  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 09:39:25.249  2077  2094 D BluetoothAdapterService(197362447): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d3f1c5d
,07-27 09:39:25.250  6628  6706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,07-27 09:39:25.257  6628  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-27 09:39:25.257  6628  6706 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-27 09:39:25.261  6628  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 09:39:25.262   842  1935 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-27 09:39:25.263  6628  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
07-27 09:39:25.268  2077  2094 D BluetoothAdapterService(197362447): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d3f1c5d
07-27 09:39:25.269  6628  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 09:39:25.269  6628  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 09:39:25.269  6628  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 09:39:25.269  6628  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 09:39:25.269  6628  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 09:39:25.269  6628  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 09:39:25.269  6628  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 09:39:25.269  6628  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 09:39:25.270  6628  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-27 09:39:25.270  6628  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 09:39:25.271  6628  6628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 09:39:25.273  6628  6628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 09:39:25.273  6628  6706 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 09:39:25.302  6628  6628 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 09:39:25.497  6628  6642 I art     : CheckpointMarkThreadRoots callback created = 0xb07d8300
,07-27 09:39:25.525  6628  6642 I art     : CheckpointMarkThreadRoots callback created = 0xb07d82d0
,07-27 09:39:25.566  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:39:25.566  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:25.566  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,07-27 09:39:25.945  6628  6731 W jxcore-log: Initializing JXcore engine
,07-27 09:39:25.947  6628  6731 W jxcore-log: JXcore engine is ready
,07-27 09:39:26.080  6731  6731 W Thread-834: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6316]" dev="sockfs" ino=6316 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-27 09:39:26.080  6731  6731 W Thread-834: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-27 09:39:26.080  6731  6731 W Thread-834: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7822]" dev="sockfs" ino=7822 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-27 09:39:26.080  6731  6731 W Thread-834: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
07-27 09:39:26.080  6731  6731 W Thread-834: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
07-27 09:39:26.080  6731  6731 W Thread-834: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[31307]" dev="sockfs" ino=31307 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-27 09:39:26.121  6628  6731 W jxcore-log: Starting JXcore engine
,07-27 09:39:26.202   842  2036 I art     : Explicit concurrent mark sweep GC freed 23552(1143KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.617ms total 223.966ms
,07-27 09:39:26.292  6628  6731 W jxcore-log: Platform android
07-27 09:39:26.292  6628  6731 W jxcore-log: 
07-27 09:39:26.292  6628  6731 W jxcore-log: Process ARCH arm
07-27 09:39:26.292  6628  6731 W jxcore-log: 
,07-27 09:39:26.522  6628  6731 I jxcore-log: JXcore Cordova bridge is ready!
07-27 09:39:26.522  6628  6731 I jxcore-log: 
,07-27 09:39:26.523  6628  6731 W jxcore-log: JXcore engine is started
07-27 09:39:26.528  6628  6706 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-27 09:39:26.534  6628  6628 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 09:39:26.567  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:39:26.567  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:26.567  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,07-27 09:39:27.553   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:39:27.553   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:39:27.554   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 112743472410; DSPS: 3793388; Offset : -3029054971
,07-27 09:39:27.568  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:39:27.568  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:27.569  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
07-27 09:39:28.071   842  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{15ee4bff type 2 when 113253 android} when 113253
,07-27 09:39:28.299   842  1287 V AlarmManager: RTC_WAKEUP set : Alarm{1aea815 type 0 when 1469605168295 com.google.android.googlequicksearchbox} when 1469605168295
,07-27 09:39:28.494   294   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,07-27 09:39:29.572  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:39:29.572  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:29.572  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,07-27 09:39:30.360   842  1971 I ActivityManager: Process com.google.android.talk (pid 6364) has died
,07-27 09:39:30.574  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:39:30.574  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:30.574  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,07-27 09:39:32.578  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:39:32.578  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:32.578  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,07-27 09:39:33.502   294   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,07-27 09:39:34.581  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:39:34.581  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:34.581  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,07-27 09:39:34.823   842  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{fc38bf6 type 2 when 120000 com.google.android.gms} when 120000
,07-27 09:39:35.218  2871  2871 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19957
,07-27 09:39:35.583  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:39:35.583  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:35.583  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,07-27 09:39:36.585  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:39:36.585  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:36.585  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,07-27 09:39:38.506   294   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,07-27 09:39:41.912  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,07-27 09:39:41.914  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:39:41.914  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:39:41.917  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:39:41.917  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:39:41.920   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 09:39:41.951  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 318
07-27 09:39:41.951  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,07-27 09:39:41.957  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 318
07-27 09:39:41.960  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:39:41.963  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,07-27 09:39:41.967  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:39:41.976   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:39:41.979   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:39:41.979   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:39:41.990  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:39:41.990  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:39:41.990  1874  2043 D LEDHandler: Battery Temp: 318, mChargingStatus=5, mChargingStop=false
07-27 09:39:42.005  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:39:43.006  6628  6731 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 09:39:43.006  6628  6731 I jxcore-log: 
,07-27 09:39:43.010  6628  6731 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 09:39:43.010  6628  6731 I jxcore-log: 
07-27 09:39:43.015  2077  2095 D BluetoothAdapterService(197362447): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d3f1c5d
07-27 09:39:43.016  6628  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 09:39:43.016  6628  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 09:39:43.016  6628  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 09:39:43.016  6628  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 09:39:43.016  6628  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 09:39:43.016  6628  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 09:39:43.016  6628  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 09:39:43.016  6628  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 09:39:43.017  2077  2095 D BluetoothAdapterService(197362447): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d3f1c5d
07-27 09:39:43.018  6628  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 09:39:43.021  6628  6731 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 09:39:43.021  6628  6731 I jxcore-log: 
07-27 09:39:43.023  6628  6731 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 09:39:43.023  6628  6731 I jxcore-log: 
07-27 09:39:43.511   294   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,07-27 09:39:43.555  6628  6731 I jxcore-log: Unit Test app is loaded
07-27 09:39:43.555  6628  6731 I jxcore-log: 
,07-27 09:39:43.565  6628  6731 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 09:39:43.565  6628  6731 I jxcore-log: 
,07-27 09:39:43.570  6628  6731 I jxcore-log: My device name is: LGE-LG-D722
07-27 09:39:43.570  6628  6731 I jxcore-log: 
07-27 09:39:43.573  6628  6731 I jxcore-log: WARN testUtils: myNameCallback not set!
07-27 09:39:43.573  6628  6731 I jxcore-log: 
07-27 09:39:43.576  6628  6628 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-27 09:39:44.599  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:39:44.599  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:44.599  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,07-27 09:39:45.601  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:39:45.601  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:45.602  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,07-27 09:39:47.554   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:39:47.554   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:39:47.555   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 132744470475; DSPS: 4448781; Offset : -3029063153
,07-27 09:39:47.605  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:39:47.605  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:47.605  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,07-27 09:39:48.515   294   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,07-27 09:39:48.607  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:39:48.607  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:48.607  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,07-27 09:39:48.835   842  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{12bbbf7 type 2 when 134014 com.google.android.gms} when 134014
,07-27 09:39:48.854  1780  1780 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,07-27 09:39:49.077  3395  6784 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
07-27 09:39:49.077  3395  6784 D SchedPeriodicTask: Scheduled AdAttestation task.
,07-27 09:39:49.094  1780  1780 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:39:49.564   842  1065 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6788 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,07-27 09:39:49.681  6788  6788 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-27 09:39:49.682  6788  6788 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-27 09:39:49.734  6788  6788 I MultiDex: VM with version 2.1.0 has multidex support
07-27 09:39:49.734  6788  6788 I MultiDex: install
07-27 09:39:49.734  6788  6788 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-27 09:39:49.750  1780  3658 I art     : Explicit concurrent mark sweep GC freed 54315(3MB) AllocSpace objects, 20(320KB) LOS objects, 39% free, 14MB/24MB, paused 1.865ms total 127.999ms
,07-27 09:39:49.838  6788  6788 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-27 09:39:49.909  6788  6788 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
07-27 09:39:49.909  6788  6788 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16e60d3d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-27 09:39:49.910  6788  6788 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-27 09:39:49.912  6788  6788 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
07-27 09:39:49.912  6788  6788 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
07-27 09:39:49.926  6788  6788 D ChimeraCfgMgr: Reading stored module config
,07-27 09:39:50.025  6788  6802 I art     : Background sticky concurrent mark sweep GC freed 18989(920KB) AllocSpace objects, 2(32KB) LOS objects, 6% free, 10MB/11MB, paused 10.666ms total 68.779ms
,07-27 09:39:50.075  1780  1780 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=3d81bfd2-f24d-4c3c-bf7c-eecce181bbc7
,07-27 09:39:50.104  6788  6813 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-27 09:39:50.113  1780  1780 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-27 09:39:50.115  1780  1780 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-27 09:39:50.126  6788  6802 I art     : CheckpointMarkThreadRoots callback created = 0xb042d480
,07-27 09:39:50.138  6788  6788 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
07-27 09:39:50.139  6788  6788 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
,07-27 09:39:50.171  6788  6802 I art     : CheckpointMarkThreadRoots callback created = 0xb042d470
,07-27 09:39:50.195  6788  6802 I art     : Background partial concurrent mark sweep GC freed 1289(233KB) AllocSpace objects, 1(151KB) LOS objects, 39% free, 10MB/17MB, paused 5.258ms total 70.217ms
,07-27 09:39:50.238   281   281 D WVCdm   : Instantiating CDM.
,07-27 09:39:50.240   281  1616 I WVCdm   : CdmEngine::OpenSession
,07-27 09:39:50.240   281  1616 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
07-27 09:39:50.279   281  1616 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
07-27 09:39:50.279   281  1616 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
07-27 09:39:50.279   281  1616 W WVCdm   : L1 library not specified. Falling Back to L3
,07-27 09:39:50.300  1780  2518 W GCoreFlp: No location to return for getLastLocation()
,07-27 09:39:50.366  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-27 09:39:50.366  6628  6731 I jxcore-log: 
,07-27 09:39:50.369  6788  6803 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 09:39:50.369  6788  6803 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 09:39:50.371  3395  6785 D UdcContextInitService: registered all accounts: true
07-27 09:39:50.371  6788  6803 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 09:39:50.371  6788  6803 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 09:39:50.372   276  1052 E BandwidthController: [LG DATA] No such appUid: 10006
07-27 09:39:50.372   276  1052 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-27 09:39:50.373   276  6823 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 09:39:50.373   276  6823 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 09:39:50.373   276  6823 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 09:39:50.374   276  6823 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 09:39:50.374   276  6823 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 09:39:50.374  6788  6803 I System.out: propertyValue:false
07-27 09:39:50.376  1780  2457 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-27 09:39:50.391  1780  2360 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
07-27 09:39:50.393   281  1616 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-27 09:39:50.396   281  1301 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-27 09:39:50.396   281  1301 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
07-27 09:39:50.396   281  1301 I WVCdm   : CdmEngine::GenerateKeyRequest
07-27 09:39:50.402   281  1301 D WVCdm   : PrepareKeyRequest: nonce=419138908
,07-27 09:39:50.449  6788  6803 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 09:39:50.449  6788  6803 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-27 09:39:50.600   842  1389 I ActivityManager: Process com.google.android.gms:car (pid 6263) has died
,07-27 09:39:50.611  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:39:50.611  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:50.611  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,07-27 09:39:51.144  6828  6828 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,07-27 09:39:51.146  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-27 09:39:51.146  6628  6731 I jxcore-log: 
07-27 09:39:51.189  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-27 09:39:51.189  6628  6731 I jxcore-log: 
,07-27 09:39:51.196  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-27 09:39:51.196  6628  6731 I jxcore-log: 
07-27 09:39:51.240  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-27 09:39:51.240  6628  6731 I jxcore-log: 
07-27 09:39:51.246  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-27 09:39:51.246  6628  6731 I jxcore-log: 
,07-27 09:39:51.266  6828  6828 I dex2oat : dex2oat took 119.057ms (threads: 4)
,07-27 09:39:51.283  6788  6803 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 09:39:51.283  6788  6803 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 09:39:51.283  6788  6803 I Adreno-EGL: Build Date: 03/02/15 Mon
07-27 09:39:51.283  6788  6803 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-27 09:39:51.283  6788  6803 I Adreno-EGL: Remote Branch: 
07-27 09:39:51.283  6788  6803 I Adreno-EGL: Local Patches: 
07-27 09:39:51.283  6788  6803 I Adreno-EGL: Reconstruct Branch: 
07-27 09:39:51.389  6788  6803 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 09:39:51.389  6788  6803 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 09:39:51.389  6788  6803 I Adreno-EGL: Build Date: 03/02/15 Mon
07-27 09:39:51.389  6788  6803 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-27 09:39:51.389  6788  6803 I Adreno-EGL: Remote Branch: 
07-27 09:39:51.389  6788  6803 I Adreno-EGL: Local Patches: 
07-27 09:39:51.389  6788  6803 I Adreno-EGL: Reconstruct Branch: 
,07-27 09:39:51.763  6788  6803 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 09:39:51.763  6788  6803 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 09:39:51.763  6788  6803 I Adreno-EGL: Build Date: 03/02/15 Mon
07-27 09:39:51.763  6788  6803 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-27 09:39:51.763  6788  6803 I Adreno-EGL: Remote Branch: 
07-27 09:39:51.763  6788  6803 I Adreno-EGL: Local Patches: 
07-27 09:39:51.763  6788  6803 I Adreno-EGL: Reconstruct Branch: 
,07-27 09:39:51.830   842  1971 I ActivityManager: Process com.android.providers.calendar (pid 6323) has died
,07-27 09:39:51.953  1780  6786 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 09:39:51.953  1780  6786 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 09:39:51.954  1780  6786 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 09:39:51.954  1780  6786 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 09:39:51.955   276  1052 E BandwidthController: [LG DATA] No such appUid: 10006
07-27 09:39:51.955   276  1052 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-27 09:39:51.955   276  6843 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 09:39:51.955   276  6843 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 09:39:51.955   276  6843 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 09:39:51.956   276  6843 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 09:39:51.956   276  6843 D libc-netbsd: res_queryN name = xxxxx succeed
,07-27 09:39:51.956  1780  6786 I System.out: propertyValue:false
07-27 09:39:52.017  1780  6786 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 09:39:52.017  1780  6786 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-27 09:39:52.197  1780  2360 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-27 09:39:52.243  1780  2360 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,07-27 09:39:52.246  1780  2360 V BaseAppContext: GmsRequestQueue started.
07-27 09:39:52.266  1780  2360 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-07-27 09:39:50.649+0200, stopTime=2016-07-27 09:39:52.247+0200, duration=1598ms
,07-27 09:39:52.300  1780  6849 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 09:39:52.300  1780  6849 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 09:39:52.300  1780  6849 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 09:39:52.300  1780  6849 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 09:39:52.301   276  1052 E BandwidthController: [LG DATA] No such appUid: 10006
07-27 09:39:52.301   276  1052 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,07-27 09:39:52.310   276  6854 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 09:39:52.310   276  6854 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 09:39:52.310   276  6854 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 09:39:52.310   276  6854 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 09:39:52.310   276  6854 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 09:39:52.311  1780  6849 I System.out: propertyValue:false
,07-27 09:39:52.334  3395  3708 V UdcCtxListenerSrv: handle intent
,07-27 09:39:52.651  1780  2360 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,07-27 09:39:52.653   281   281 I WVCdm   : CdmEngine::CloseSession
07-27 09:39:52.658   281   281 I WVCdm   : L3 Terminate.
,07-27 09:39:52.719  6673  6816 I art     : Explicit concurrent mark sweep GC freed 1445(63KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 810us total 26.609ms
,07-27 09:39:52.824  1780  6859 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-27 09:39:52.824  1780  6857 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-27 09:39:52.846  1780  6860 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-27 09:39:52.847  1780  6857 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-27 09:39:52.867  1780  6860 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-27 09:39:52.867  1780  6857 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-27 09:39:52.868  1780  6857 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,07-27 09:39:52.888  1780  6857 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-27 09:39:52.945   842  3636 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 09:39:53.011  1780  6857 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 09:39:53.012  1780  6857 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 09:39:53.012  1780  6857 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 09:39:53.012  1780  6857 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 09:39:53.012   276  1052 E BandwidthController: [LG DATA] No such appUid: 10006
,07-27 09:39:53.012   276  1052 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,07-27 09:39:53.013   276  6865 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 09:39:53.014   276  6865 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 09:39:53.014   276  6865 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 09:39:53.015   276  6865 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 09:39:53.015   276  6865 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 09:39:53.015  1780  6857 I System.out: propertyValue:false
07-27 09:39:53.340   842  1389 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 09:39:53.520   294   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,07-27 09:39:53.607   842  1065 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 09:39:53.866   842  2035 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 09:39:54.071   842  1884 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 09:39:54.272   842   860 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 09:39:54.607  1780  2360 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,07-27 09:39:54.641  3395  3708 V UdcCtxListenerSrv: handle intent
,07-27 09:39:54.693  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-27 09:39:54.693  6628  6731 I jxcore-log: 
,07-27 09:39:54.714  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-27 09:39:54.714  6628  6731 I jxcore-log: 
,07-27 09:39:54.727  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-27 09:39:54.727  6628  6731 I jxcore-log: 
,07-27 09:39:54.969  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-27 09:39:54.969  6628  6731 I jxcore-log: 
,07-27 09:39:55.190  2871  2871 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,07-27 09:39:55.202  2871  2871 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,07-27 09:39:55.620  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:39:55.620  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:55.620  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,07-27 09:39:56.291  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-27 09:39:56.291  6628  6731 I jxcore-log: 
,07-27 09:39:56.378  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-27 09:39:56.378  6628  6731 I jxcore-log: 
,07-27 09:39:56.389  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-27 09:39:56.389  6628  6731 I jxcore-log: 
07-27 09:39:56.622  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:39:56.622  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:56.622  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,07-27 09:39:56.712  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-27 09:39:56.712  6628  6731 I jxcore-log: 
,07-27 09:39:56.745  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-27 09:39:56.745  6628  6731 I jxcore-log: 
,07-27 09:39:56.752  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-27 09:39:56.752  6628  6731 I jxcore-log: 
07-27 09:39:56.760  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-27 09:39:56.760  6628  6731 I jxcore-log: 
,07-27 09:39:56.784  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-27 09:39:56.784  6628  6731 I jxcore-log: 
,07-27 09:39:56.815  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-27 09:39:56.815  6628  6731 I jxcore-log: 
,07-27 09:39:56.953  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-27 09:39:56.953  6628  6731 I jxcore-log: 
,07-27 09:39:56.961  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-27 09:39:56.961  6628  6731 I jxcore-log: 
07-27 09:39:56.998  6628  6731 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-27 09:39:56.998  6628  6731 I jxcore-log: 
,07-27 09:39:57.012  2077  2095 D BluetoothAdapterService(197362447): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d3f1c5d
,07-27 09:39:57.013  6628  6731 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
07-27 09:39:57.017  6628  6731 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-27 09:39:57.017  6628  6731 I jxcore-log: 
07-27 09:39:57.625  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,07-27 09:39:57.625  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:39:57.625  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
07-27 09:39:58.525   294   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,07-27 09:40:00.000   842  1287 D PowerManagerServiceEx: acquireWakeLockInternal: lock=712628047, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=842
,07-27 09:40:00.005  2854  2854 D WeatherService: 2 : TimeTick Intent has been received, Time(hour:min:sec) 9:40:0
07-27 09:40:00.005  2854  2854 D WeatherService: 2 : TimeTick Intent And Screen On
07-27 09:40:00.005  2854  2854 D WeatherService: 2 : SDK version : 21
07-27 09:40:00.009   842  3636 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
07-27 09:40:00.010  2854  2854 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
07-27 09:40:00.010  2854  2854 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
07-27 09:40:00.010  2854  2854 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
07-27 09:40:00.010  2854  2854 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
07-27 09:40:00.011  2854  2854 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 09:40:00.011  2854  2854 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
07-27 09:40:00.012  2854  2854 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
07-27 09:40:00.013  2854  2854 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
07-27 09:40:00.013  2854  2854 D WeatherTheme: 2 : Fixed theme : optimus
,07-27 09:40:00.026  2854  2854 D WeatherReflect: 2 : Map key string is -2
,07-27 09:40:00.030  2854  2854 D lim     : 2 : time = 09:40
07-27 09:40:00.036  2854  2854 I WeatherReflect: Model Name : LG-D722
07-27 09:40:00.036  2854  2854 D WeatherTheme: 2 : Different view - status_min_formatted : 39 != 40
07-27 09:40:00.036  2854  2854 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
07-27 09:40:00.037  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:40:00.037  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:40:00.038  2854  2854 D WeatherReflect: 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
07-27 09:40:00.042  2854  2854 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-27 09:40:00.042  2854  2854 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-27 09:40:00.042  2854  2854 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-27 09:40:00.042  2854  2854 D Weather4x2_optimus: currentPackage=com.lge.sizechangable.weather.theme.optimus
,07-27 09:40:00.058  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:40:00.060  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:40:00.066  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:40:00.068  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:40:00.068  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:40:00.092  2854  2854 D Weather4x2_optimus: [[[[[[Theme package!!]]]]]] RemoteViews are created 2
07-27 09:40:00.092  2854  2854 D Weather4x2_optimus: widgetType = 1, orientation = 1
07-27 09:40:00.092  2854  2854 D Weather4x2_optimus: forecast size is 0
,07-27 09:40:00.097  2854  2854 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-27 09:40:00.098  2854  2854 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-27 09:40:00.098  2854  2854 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-27 09:40:00.098  2854  2854 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-27 09:40:00.098  2854  2854 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-27 09:40:00.098  2854  2854 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-27 09:40:00.099  2854  2854 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-27 09:40:00.099  2854  2854 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-27 09:40:00.099  2854  2854 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-27 09:40:00.099  2854  2854 I Theme_WeatherAncestor_optimus: WEATHER_CP_ACCU : 
,07-27 09:40:00.099  2854  2854 I Theme_WeatherAncestor_optimus: weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
07-27 09:40:00.099  2854  2854 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-27 09:40:00.099  2854  2854 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-27 09:40:00.099  2854  2854 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-27 09:40:00.099  2854  2854 D Theme_WeatherAncestor_optimus: setTouchIntent, appWidgetId: 2
07-27 09:40:00.100  2854  2854 D Theme_WeatherAncestor_optimus: url is : null
07-27 09:40:00.102  2854  2854 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-27 09:40:00.102  2854  2854 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-27 09:40:00.102  2854  2854 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-27 09:40:00.103  2854  2854 D WeatherAncestor: 2 : update view, appWidgetId: 2
,07-27 09:40:00.113  2854  2854 D WeatherService: 2 : TimeTick Intent has been processed, Time(hour:min:sec) 9:40:0
07-27 09:40:00.125   842   842 D PowerManagerServiceEx: releaseWakeLockInternal: lock=712628047 [*alarm*], flags=0x0
,07-27 09:40:00.238  1948  1948 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,07-27 09:40:00.321  1948  1948 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,07-27 09:40:00.631  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:40:00.631  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:40:00.631  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,07-27 09:40:00.882   842  1048 I PowerManagerService: ALS enabled for SRE
,07-27 09:40:00.886   842  1048 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26076 ms ago)
07-27 09:40:00.921   842  1350 D qdlights: set_light_backlight: 253
,07-27 09:40:00.934   842  1350 D qdlights: set_light_backlight: 250
,07-27 09:40:00.951   842  1350 D qdlights: set_light_backlight: 246
,07-27 09:40:00.967   842  1350 D qdlights: set_light_backlight: 243
,07-27 09:40:00.984   842  1350 D qdlights: set_light_backlight: 240
,07-27 09:40:01.001   842  1350 D qdlights: set_light_backlight: 236
,07-27 09:40:01.017   842  1350 D qdlights: set_light_backlight: 233
,07-27 09:40:01.034   842  1350 D qdlights: set_light_backlight: 230
,07-27 09:40:01.051   842  1350 D qdlights: set_light_backlight: 226
,07-27 09:40:01.067   842  1350 D qdlights: set_light_backlight: 223
,07-27 09:40:01.084   842  1350 D qdlights: set_light_backlight: 220
,07-27 09:40:01.101   842  1350 D qdlights: set_light_backlight: 216
,07-27 09:40:01.117   842  1350 D qdlights: set_light_backlight: 213
,07-27 09:40:01.134   842  1350 D qdlights: set_light_backlight: 210
,07-27 09:40:01.151   842  1350 D qdlights: set_light_backlight: 206
,07-27 09:40:01.167   842  1350 D qdlights: set_light_backlight: 203
,07-27 09:40:01.184   842  1350 D qdlights: set_light_backlight: 200
,07-27 09:40:01.201   842  1350 D qdlights: set_light_backlight: 196
,07-27 09:40:01.217   842  1350 D qdlights: set_light_backlight: 193
,07-27 09:40:01.234   842  1350 D qdlights: set_light_backlight: 190
,07-27 09:40:01.251   842  1350 D qdlights: set_light_backlight: 186
,07-27 09:40:01.267   842  1350 D qdlights: set_light_backlight: 183
,07-27 09:40:01.284   842  1350 D qdlights: set_light_backlight: 180
,07-27 09:40:01.301   842  1350 D qdlights: set_light_backlight: 176
,07-27 09:40:01.317   842  1350 D qdlights: set_light_backlight: 173
,07-27 09:40:01.334   842  1350 D qdlights: set_light_backlight: 170
,07-27 09:40:01.351   842  1350 D qdlights: set_light_backlight: 166
,07-27 09:40:01.367   842  1350 D qdlights: set_light_backlight: 163
,07-27 09:40:01.384   842  1350 D qdlights: set_light_backlight: 160
,07-27 09:40:01.401   842  1350 D qdlights: set_light_backlight: 156
,07-27 09:40:01.417   842  1350 D qdlights: set_light_backlight: 153
,07-27 09:40:01.434   842  1350 D qdlights: set_light_backlight: 150
,07-27 09:40:01.451   842  1350 D qdlights: set_light_backlight: 146
,07-27 09:40:01.467   842  1350 D qdlights: set_light_backlight: 143
,07-27 09:40:01.484   842  1350 D qdlights: set_light_backlight: 140
,07-27 09:40:01.501   842  1350 D qdlights: set_light_backlight: 136
,07-27 09:40:01.518   842  1350 D qdlights: set_light_backlight: 133
,07-27 09:40:01.534   842  1350 D qdlights: set_light_backlight: 130
,07-27 09:40:01.551   842  1350 D qdlights: set_light_backlight: 126
,07-27 09:40:01.567   842  1350 D qdlights: set_light_backlight: 123
,07-27 09:40:01.584   842  1350 D qdlights: set_light_backlight: 120
,07-27 09:40:01.601   842  1350 D qdlights: set_light_backlight: 116
,07-27 09:40:01.618   842  1350 D qdlights: set_light_backlight: 113
,07-27 09:40:01.632  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:40:01.632  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:40:01.632  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,07-27 09:40:01.636   842  1350 D qdlights: set_light_backlight: 110
07-27 09:40:01.652   842  1350 D qdlights: set_light_backlight: 106
,07-27 09:40:01.668   842  1350 D qdlights: set_light_backlight: 103
,07-27 09:40:01.684   842  1350 D qdlights: set_light_backlight: 100
,07-27 09:40:01.701   842  1350 D qdlights: set_light_backlight: 96
,07-27 09:40:01.717   842  1350 D qdlights: set_light_backlight: 93
,07-27 09:40:01.734   842  1350 D qdlights: set_light_backlight: 90
,07-27 09:40:01.751   842  1350 D qdlights: set_light_backlight: 86
,07-27 09:40:01.768   842  1350 D qdlights: set_light_backlight: 83
,07-27 09:40:01.784   842  1350 D qdlights: set_light_backlight: 80
,07-27 09:40:01.801   842  1350 D qdlights: set_light_backlight: 76
,07-27 09:40:01.817   842  1350 D qdlights: set_light_backlight: 73
07-27 09:40:01.834   842  1350 D qdlights: set_light_backlight: 70
,07-27 09:40:01.851   842  1350 D qdlights: set_light_backlight: 66
,07-27 09:40:01.867   842  1350 D qdlights: set_light_backlight: 63
,07-27 09:40:01.884   842  1350 D qdlights: set_light_backlight: 60
,07-27 09:40:01.901   842  1350 D qdlights: set_light_backlight: 56
,07-27 09:40:01.917   842  1350 D qdlights: set_light_backlight: 53
,07-27 09:40:01.934   842  1350 D qdlights: set_light_backlight: 50
,07-27 09:40:01.951   842  1350 D qdlights: set_light_backlight: 46
,07-27 09:40:01.968   842  1350 D qdlights: set_light_backlight: 43
,07-27 09:40:01.984   842  1350 D qdlights: set_light_backlight: 40
,07-27 09:40:02.001   842  1350 D qdlights: set_light_backlight: 36
,07-27 09:40:02.020   842  1350 D qdlights: set_light_backlight: 33
,07-27 09:40:02.039   842  1350 D qdlights: set_light_backlight: 30
,07-27 09:40:02.051   842  1350 D qdlights: set_light_backlight: 26
,07-27 09:40:02.068   842  1350 D qdlights: set_light_backlight: 23
,07-27 09:40:02.084   842  1350 D qdlights: set_light_backlight: 20
,07-27 09:40:02.101   842  1350 D qdlights: set_light_backlight: 16
,07-27 09:40:02.120   842  1350 D qdlights: set_light_backlight: 13
,07-27 09:40:02.135   842  1350 D qdlights: set_light_backlight: 10
,07-27 09:40:02.635  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:40:02.635  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:40:02.636  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,07-27 09:40:03.529   294   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,07-27 09:40:03.637  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:40:03.637  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:40:03.637  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,07-27 09:40:06.643  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:40:06.643  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:40:06.643  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,07-27 09:40:07.555   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:40:07.555   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:40:07.555   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 152745218176; DSPS: 5104166; Offset : -3029078860
,07-27 09:40:07.645  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 09:40:07.645  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 09:40:07.645  1378  1378 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,07-27 09:40:07.880   842  1048 I PowerManagerService: ALS enabled for SRE
07-27 09:40:07.880   842  1048 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33070 ms ago)
07-27 09:40:07.880   842  1048 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-27 09:40:07.896   842  1048 I PowerManagerService: ALS enabled for SRE
07-27 09:40:07.896   842  1048 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33086 ms ago)
,07-27 09:40:07.905   842  1048 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
07-27 09:40:07.909   842  1048 I PowerManagerService: Sleeping (uid 1000)...
07-27 09:40:07.909   842  1048 D LPWGController: [updateScreenState] screen on = false
,07-27 09:40:07.916   842  1048 D LPWGController: disable proximity sensor
07-27 09:40:07.916   842  1048 D LPWGController: enable proximity sensor
07-27 09:40:07.926   842  1048 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@8587042] by com.android.server.power.ProximitySensorListener.enable():120
,07-27 09:40:07.934   842  1048 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
07-27 09:40:07.934   842  1048 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
07-27 09:40:07.935   842  1048 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
07-27 09:40:07.935   842  1048 I sensors_hal_Ctx: activate: handle is 48, enable
07-27 09:40:07.935   842  1048 V sensors_hal_Ctx: activate sensors is 1400000000000
07-27 09:40:07.935   842  1048 D sensors_hal_Thresh: enable: handle=48
07-27 09:40:07.935   842  1048 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
07-27 09:40:07.936   842  1048 D sensors_hal_Util: waitForResponse: timeout=1000
07-27 09:40:07.941   842   988 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
07-27 09:40:07.941   842   988 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
,07-27 09:40:07.943   842  1048 D sensors_hal_Thresh: enable: Received response: 0
07-27 09:40:07.944   842  1048 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33134 ms ago)
07-27 09:40:07.969   842  1048 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 09:40:07.969   842  1048 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 09:40:07.969   842  1048 I Adreno-EGL: Build Date: 03/02/15 Mon
07-27 09:40:07.969   842  1048 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-27 09:40:07.969   842  1048 I Adreno-EGL: Remote Branch: 
07-27 09:40:07.969   842  1048 I Adreno-EGL: Local Patches: 
07-27 09:40:07.969   842  1048 I Adreno-EGL: Reconstruct Branch: 
,07-27 09:40:07.999   246   285 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1053 us)
,07-27 09:40:08.170   427   973 I Sensors : sns_pwr.c(273):acquiring wakelock
07-27 09:40:08.170   842   988 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,07-27 09:40:08.171   842   988 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
07-27 09:40:08.172   842   988 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
07-27 09:40:08.172   842   988 D sensors_hal_Thresh: processInd: handle 48, count=1
07-27 09:40:08.172   842   988 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
07-27 09:40:08.172   842   988 I sensors_hal_Thresh: processInd : proximity state changed - FAR
07-27 09:40:08.174   842  1022 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
07-27 09:40:08.174   842  1022 D sensors_hal_Ctx: poll: count: 256
07-27 09:40:08.175   842  1022 I sensors_hal_Ctx: poll: released wakelock sensor_ind
07-27 09:40:08.175   842  1022 D sensors_hal_Util: waitForResponse: timeout=0
07-27 09:40:08.177   842  1048 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
07-27 09:40:08.177   842  1048 I LPWGController: current mode = 1  value = 1 1
07-27 09:40:08.178   842  1048 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
07-27 09:40:08.277   842  1048 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,07-27 09:40:08.503   842  1350 D qdlights: set_light_backlight: 0
,07-27 09:40:08.524   842  1048 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,07-27 09:40:08.530   842  1048 I sensors_hal_Ctx: activate: handle is 46, disable
07-27 09:40:08.530   842  1048 V sensors_hal_Ctx: activate sensors is 1000000000000
07-27 09:40:08.530   842  1048 D sensors_hal_LP2: enable: handle=46
07-27 09:40:08.530   842  1048 D sensors_hal_LP2: enable: Disabling sensor handle=46
07-27 09:40:08.530   842  1048 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
07-27 09:40:08.534   246   246 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
07-27 09:40:08.534   246   246 D qdhwcomposer: hwc_blank: Blanking display: 0
07-27 09:40:08.534   294   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
07-27 09:40:08.543   842  1039 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
07-27 09:40:08.543   842   842 V ActivityManager: Display changed displayId=0
,07-27 09:40:08.591   842  1014 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
07-27 09:40:08.591   842  1014 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
07-27 09:40:08.612  1814  1814 D DSDPConnection: Display #0 changed.
,07-27 09:40:08.719   246   246 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-27 09:40:08.720   246   592 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
07-27 09:40:08.720   842  1350 D SurfaceControl: Excessive delay in setPowerMode(): 187ms
07-27 09:40:08.721   842  1350 I QCOM PowerHAL: Got set_interactive hint
,07-27 09:40:08.732  6628  6628 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-27 09:40:08.732  6628  6628 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-27 09:40:08.733  1378  1410 D KeyguardViewMediator: onScreenTurnedOff(3)
07-27 09:40:08.742  6628  6628 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1417cf46 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@c12e718, 16908290=android.view.AbsSavedState$1@c12e718}, android:focusedViewId=100}]}]
07-27 09:40:08.742  6628  6628 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-27 09:40:08.743  6628  6628 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-27 09:40:08.743  6628  6628 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-27 09:40:08.748  1333  3442 D SmartCoverViewMediator: onScreenTurnedOff(3)
,07-27 09:40:08.757  1333  3442 D SmartCoverViewMediator: notifyScreenOffLocked
07-27 09:40:08.757  1333  1333 D SmartCoverViewMediator: handleNotifyScreenOFF
07-27 09:40:08.764  1378  1410 D KeyguardViewMediator: notifyScreenOffLocked
,07-27 09:40:08.780  1378  1410 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
,07-27 09:40:08.781  1378  1378 D KeyguardViewMediator: handleNotifyScreenOff
07-27 09:40:08.796   842   842 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
07-27 09:40:08.801  1378  1378 D ScreenTurnOffBySensor: unregisterProximitySensor
,07-27 09:40:08.819   281  1301 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 842
,07-27 09:40:08.819   281  1301 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-27 09:40:08.819   281  1301 V voice   : voice_set_parameters: enter: screen_state=on
07-27 09:40:08.821   281  1301 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
07-27 09:40:08.821   281  1301 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-27 09:40:08.821   281  1301 V voice   : voice_set_parameters: exit with code(0)
07-27 09:40:08.821   281  1301 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
07-27 09:40:08.821   281  1301 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-27 09:40:08.821   281  1301 V msm8974_platform: platform_set_parameters: exit with code(0)
07-27 09:40:08.821   281  1301 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-27 09:40:08.821   281  1301 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
07-27 09:40:08.821   281  1301 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
07-27 09:40:08.822   281  1301 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-27 09:40:08.822   842  1309 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
07-27 09:40:08.823  1378  1378 D StatusBarWindowView: onScreenTurnedOff why = 3
07-27 09:40:08.831  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:40:08.831  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
,07-27 09:40:09.150   842   979 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,07-27 09:40:09.182   842  2012 D SplitWindow: check instance of lgWin Window{1035fe89 u0 SearchPanel}
,07-27 09:40:09.189  1910  1910 I QCNEJ   : |CORE| sendScreenState: state:true
07-27 09:40:09.196  1874  2043 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
,07-27 09:40:09.199  1874  2043 D LEDService: stopPatternFlashing()
07-27 09:40:09.200  1874  2043 D qdlights: set_light_notifications: 0,0,0,0,3
07-27 09:40:09.201  1874  2043 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-27 09:40:09.201  1874  2043 D qdlights: set_light_notifications: 0,0,0,0,3
07-27 09:40:09.203  1874  2043 I LEDService: updateLightsLocked : turn off led
07-27 09:40:09.203  1874  2043 D qdlights: set_light_notifications: 0,0,0,0,3
07-27 09:40:09.205  1874  2043 D LEDHandler: RESTART MSG
07-27 09:40:09.209   842  1641 D InputDispatcher: Window went away: Window{2c882dd9 u0 SearchPanel}
,07-27 09:40:09.213  1378  1378 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
07-27 09:40:09.231  1378  1378 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,07-27 09:40:09.236  1874  1874 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
07-27 09:40:09.237  1874  1874 D Cliptray Service: lockStatus = 0
07-27 09:40:09.240  1857  1857 D LNfcService: action : android.intent.action.SCREEN_ON
07-27 09:40:09.248  1857  6917 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
07-27 09:40:09.248  1857  6917 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
07-27 09:40:09.248  1857  6917 D LNfcService: isRequireNfcCRouting() return true
,07-27 09:40:09.248  1857  6917 D LNfcService: isHCERoutingtoHost() return : true
07-27 09:40:09.248  1857  6917 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
07-27 09:40:09.248  1857  6917 D NfcService: mEnableLPD: true
07-27 09:40:09.248  1857  6917 D NfcService: mEnableReader: false
07-27 09:40:09.248  1857  6917 D NfcService: mEnableHostRouting: true
07-27 09:40:09.248  1857  6917 D NfcService: newParams.techmask= mTechMask: default
07-27 09:40:09.248  1857  6917 D NfcService: mEnableLPD: true
07-27 09:40:09.248  1857  6917 D NfcService: mEnableReader: false
07-27 09:40:09.248  1857  6917 D NfcService: mEnableHostRouting: true
07-27 09:40:09.250  1857  6917 D NfcService: screenState= 3
07-27 09:40:09.250  1857  6917 D NfcService: Discovery configuration equal, not updating.
07-27 09:40:09.257   842   842 D Ulp_jni : JNI:system_update. Event-0
,07-27 09:40:09.281  1814  1814 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
07-27 09:40:09.289   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:40:09.289   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:40:09.289   842   842 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
07-27 09:40:09.293  2854  2854 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 9:40:9
07-27 09:40:09.295  2854  2854 D WeatherService: 2 : ACTION screen on
07-27 09:40:09.296  2854  2854 D WeatherService: 2 : shouldTimeTickRegistered : false
07-27 09:40:09.301  2854  2854 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-27 09:40:09.301  2854  2854 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 9:40:9
,07-27 09:40:09.308  4158  4158 D AppCleanupService: android.intent.action.SCREEN_ON
,07-27 09:40:09.330   281   281 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 842
07-27 09:40:09.330   281   281 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
07-27 09:40:09.330   281   281 V voice   : voice_set_parameters: enter: screen_state=off
07-27 09:40:09.331   281   281 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
07-27 09:40:09.331   281   281 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-27 09:40:09.331   281   281 V voice   : voice_set_parameters: exit with code(0)
07-27 09:40:09.331   281   281 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
07-27 09:40:09.331   281   281 V msm8974_platform: platform_set_parameters: enter: screen_state=off
07-27 09:40:09.331   281   281 V msm8974_platform: platform_set_parameters: exit with code(0)
07-27 09:40:09.331   281   281 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-27 09:40:09.331   281   281 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
07-27 09:40:09.331   281   281 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-27 09:40:09.332   842  1315 D WifiController: CMD_SCREEN_OFF 
07-27 09:40:09.332   842  1315 D WifiController: shouldWifiStayAwake TRUE
07-27 09:40:09.337  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
,07-27 09:40:09.340   842   979 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,07-27 09:40:09.379  1910  1910 I QCNEJ   : |CORE| sendScreenState: state:false
07-27 09:40:09.380  1874  2043 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
07-27 09:40:09.381  1874  2043 D LEDService: stopPatternFlashing()
07-27 09:40:09.381  1874  2043 D qdlights: set_light_notifications: 0,0,0,0,3
07-27 09:40:09.382  1874  2043 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-27 09:40:09.382  1874  2043 D qdlights: set_light_notifications: 0,0,0,0,3
07-27 09:40:09.382  1874  1874 D VolumeVibrator: clear
07-27 09:40:09.384  1874  1874 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
07-27 09:40:09.384  1874  2043 I LEDService: updateLightsLocked : turn on led
07-27 09:40:09.385  1857  1857 D LNfcService: action : android.intent.action.SCREEN_OFF
07-27 09:40:09.387  1874  2043 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
07-27 09:40:09.387  1874  2043 E LEDService: Can't handle this request of patternId:0
07-27 09:40:09.387  1874  2043 D LEDHandler: RESTART MSG
07-27 09:40:09.388  1857  2218 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
,07-27 09:40:09.405  1948  1948 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,07-27 09:40:09.418  1814  1814 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,07-27 09:40:09.421   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:40:09.422   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:40:09.422   842   842 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
07-27 09:40:09.423  2854  2854 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 9:40:9
07-27 09:40:09.423  2854  2854 D WeatherService: 2 : ACTION screen off
07-27 09:40:09.424  2854  2854 D WeatherService: 2 : TimeTick Receiver Unregister
07-27 09:40:09.425  2854  2854 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 9:40:9
07-27 09:40:09.428  4158  4158 D AppCleanupService: android.intent.action.SCREEN_OFF
07-27 09:40:09.432  4158  6920 D AppCleanupService: AppUsageStatsSaveTask
,07-27 09:40:09.483  1857  2702 E NxpNfcJni: getReconnectState = 0x0
,07-27 09:40:09.486  1857  2218 D LCardEmulationManager: getHceAppCount hostAppNum : 0
07-27 09:40:09.486  1857  2218 D LCardEmulationManager: getDefaultRoute
07-27 09:40:09.486  1857  2218 D LNfcService: isRequireNfcCRouting() return true
07-27 09:40:09.487  1857  2218 D LNfcService: isHCERoutingtoHost() return : true
07-27 09:40:09.487  1857  2218 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
07-27 09:40:09.487  1857  2218 D NfcService: mEnableLPD: true
07-27 09:40:09.487  1857  2218 D NfcService: mEnableReader: false
07-27 09:40:09.487  1857  2218 D NfcService: mEnableHostRouting: true
07-27 09:40:09.487  1857  2218 D NfcService: newParams.techmask= mTechMask: 0
07-27 09:40:09.487  1857  2218 D NfcService: mEnableLPD: true
07-27 09:40:09.487  1857  2218 D NfcService: mEnableReader: false
07-27 09:40:09.487  1857  2218 D NfcService: mEnableHostRouting: true
07-27 09:40:09.487  1857  2218 D NfcService: screenState= 1
07-27 09:40:09.531  1857  2702 E NxpNfcJni: getReconnectState = 0x0
,07-27 09:40:09.670   427   441 I Sensors : sns_pwr.c(301):releasing wakelock
,07-27 09:40:13.539   294   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,07-27 09:40:13.775  1378  1378 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,07-27 09:40:13.780   842  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1814e8e type 2 when 158956 com.android.systemui} when 158956
,07-27 09:40:13.799  1814  2675 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
07-27 09:40:13.804  1814  2675 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-27 09:40:13.804  1814  2675 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-27 09:40:13.808  1814  2675 V TelecomServiceImpl: getCallState : 0
,07-27 09:40:13.812  1814  1838 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
07-27 09:40:13.812  1814  1838 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-27 09:40:13.812  1814  1838 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-27 09:40:13.815  1378  1378 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
07-27 09:40:13.815  1378  1378 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
07-27 09:40:17.023  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:40:17.023  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:40:17.024  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:40:17.024  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 09:40:17.026  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:40:17.046   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:40:17.081  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:40:17.083  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 320
07-27 09:40:17.084  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:40:17.084  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:40:17.085  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:40:17.085  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:40:17.085  1874  2043 D LEDHandler: Battery Temp: 320, mChargingStatus=5, mChargingStop=false
07-27 09:40:17.087  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:40:17.087  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 320
07-27 09:40:17.089  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:40:17.093   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:40:17.093   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:40:17.096   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:40:17.152  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 320
07-27 09:40:17.152  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:40:17.152  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 320
07-27 09:40:17.152  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
,07-27 09:40:17.153  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:40:17.153  1874  2043 D LEDHandler: Battery Temp: 320, mChargingStatus=5, mChargingStop=false
07-27 09:40:17.153  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:40:17.153  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:40:17.154  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:40:17.156  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:40:17.158   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:40:17.158   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:40:17.158   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:40:18.543   294   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,07-27 09:40:23.548   294   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,07-27 09:40:27.556   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:40:27.556   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:40:27.556   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 172745955043; DSPS: 5759550; Offset : -3029074103
,07-27 09:40:28.552   294   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,07-27 09:40:33.097  1780  4374 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-27 09:40:33.566   294   351 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-27 09:40:37.010  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,07-27 09:40:37.014  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:40:37.014  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:40:37.015  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:40:37.015  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:40:37.028   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:40:37.061  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 319
07-27 09:40:37.061  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:40:37.061  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 319
,07-27 09:40:37.066  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:40:37.067  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:40:37.067  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:40:37.068  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:40:37.068  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:40:37.068  1874  2043 D LEDHandler: Battery Temp: 319, mChargingStatus=5, mChargingStop=false
07-27 09:40:37.070  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:40:37.074   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:40:37.074   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:40:37.076   842  1315 D WifiController: battery changed pluggedType: 2
,07-27 09:40:37.115  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 318
07-27 09:40:37.115  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:40:37.116  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 318
,07-27 09:40:37.124  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:40:37.124  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:40:37.124  1874  2043 D LEDHandler: Battery Temp: 318, mChargingStatus=5, mChargingStop=false
07-27 09:40:37.125  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:40:37.125  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:40:37.126  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:40:37.127  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,07-27 09:40:37.129   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:40:37.129   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:40:37.130   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:40:38.570   294   351 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-27 09:40:39.439   842  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{19d1e6af type 2 when 184618 com.google.android.gms} when 184618
,07-27 09:40:42.069   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:40:42.072  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:40:42.072  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:40:42.072  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:40:42.072  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:40:42.086  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,07-27 09:40:43.575   294   351 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-27 09:40:47.557   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:40:47.557   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:40:47.557   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 192746592222; DSPS: 6414931; Offset : -3029078027
,07-27 09:40:48.579   294   351 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-27 09:40:53.584   294   351 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-27 09:40:58.588   294   351 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-27 09:41:00.064  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:41:00.064  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:41:00.064  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:41:00.068  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:41:00.068  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:41:00.069  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:41:00.070  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:41:03.593   294   351 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-27 09:41:07.399  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,07-27 09:41:07.401  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:41:07.402  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:41:07.402  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:41:07.402  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:41:07.426   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:41:07.460   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:41:07.463  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:41:07.463  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:41:07.463  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:41:07.463  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:41:07.464  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:41:07.537  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:41:07.541  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:41:07.541  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:41:07.541  1874  2043 D LEDHandler: Battery Temp: 317, mChargingStatus=5, mChargingStop=false
07-27 09:41:07.541  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:41:07.541  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:41:07.543  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 317
07-27 09:41:07.544  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:41:07.544  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 317
07-27 09:41:07.546  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:41:07.547   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:41:07.548   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:41:07.548   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:41:07.558   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:41:07.558   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:41:07.558   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 212747727163; DSPS: 7070328; Offset : -3029072992
,07-27 09:41:07.587  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:41:07.590  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 317
07-27 09:41:07.591  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:41:07.591  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:41:07.592  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:41:07.592  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:41:07.592  1874  2043 D LEDHandler: Battery Temp: 317, mChargingStatus=5, mChargingStop=false
07-27 09:41:07.593  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:41:07.594  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 317
07-27 09:41:07.596  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:41:07.600   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:41:07.600   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:41:07.603   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:41:08.597   294   351 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-27 09:41:09.437   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:41:09.439  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:41:09.441  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:41:09.441  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:41:09.441  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:41:09.441  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:41:13.602   294   351 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-27 09:41:18.606   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:41:23.611   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:41:27.560   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:41:27.560   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:41:27.561   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 232750319135; DSPS: 7725773; Offset : -3029073998
,07-27 09:41:28.616   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:41:33.620   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:41:35.619   842  1287 D PowerManagerServiceEx: acquireWakeLockInternal: lock=712628047, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=842
,07-27 09:41:35.622   842  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{d02babc type 2 when 205239 android} when 205239
07-27 09:41:35.623   842  1287 V AlarmManager: RTC_WAKEUP set : Alarm{876fa45 type 0 when 1469605295617 com.google.android.gms} when 1469605295617
07-27 09:41:35.666   842   842 D PowerManagerServiceEx: releaseWakeLockInternal: lock=712628047 [*alarm*], flags=0x0
,07-27 09:41:35.977   842  1971 I art     : Explicit concurrent mark sweep GC freed 49792(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/35MB, paused 3.438ms total 284.498ms
,07-27 09:41:36.124  1780  1780 I art     : Explicit concurrent mark sweep GC freed 55301(3MB) AllocSpace objects, 25(421KB) LOS objects, 40% free, 15MB/25MB, paused 2.056ms total 134.729ms
,07-27 09:41:36.142  3395  6963 I EventLogChimeraService: Aggregate from 1469605118070 (log), 1469603495550 (data)
,07-27 09:41:36.252  3395  6983 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-27 09:41:38.625   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:41:42.230  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:41:42.230  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:41:42.230  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:41:42.230  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 09:41:42.232   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 09:41:42.233  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:41:42.274  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:41:42.277  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 315
07-27 09:41:42.277  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:41:42.277  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:41:42.278  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:41:42.278  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:41:42.279  1874  2043 D LEDHandler: Battery Temp: 315, mChargingStatus=5, mChargingStop=false
07-27 09:41:42.280  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:41:42.280  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 315
07-27 09:41:42.285   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:41:42.285   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:41:42.288   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:41:42.289  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:41:43.629   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:41:47.561   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:41:47.561   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:41:47.561   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 252751014440; DSPS: 8381156; Offset : -3029080884
,07-27 09:41:48.634   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:41:53.639   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:41:58.643   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:42:00.039  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:42:00.039  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:42:00.039  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:42:00.043  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:42:00.043  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:42:00.044  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:42:00.045  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:42:03.648   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:42:07.562   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:42:07.562   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:42:07.562   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 272751776515; DSPS: 9036541; Offset : -3029081878
,07-27 09:42:08.652   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:42:13.657   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:42:18.664   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:42:23.668   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:42:27.562   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:42:27.562   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:42:27.563   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 292752543487; DSPS: 9691926; Offset : -3029077715
,07-27 09:42:28.673   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:42:33.677   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:42:38.682   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:42:42.390   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:42:42.393  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:42:42.393  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:42:42.393  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:42:42.393  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:42:42.394  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:42:42.432  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 312
07-27 09:42:42.432  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:42:42.432  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 312
,07-27 09:42:42.435  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:42:42.435  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:42:42.436  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:42:42.436  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:42:42.436  1874  2043 D LEDHandler: Battery Temp: 312, mChargingStatus=5, mChargingStop=false
07-27 09:42:42.440  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:42:42.443   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:42:42.443   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:42:42.443   842  1315 D WifiController: battery changed pluggedType: 2
,07-27 09:42:42.445  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:42:43.687   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:42:47.563   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:42:47.563   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:42:47.563   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 312753236604; DSPS: 10347308; Offset : -3029056090
,07-27 09:42:48.691   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:42:53.696   294   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 09:42:58.700   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:43:00.039  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:43:00.039  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:43:00.039  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:43:00.043  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:43:00.043  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:43:00.044  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:43:00.044  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:43:03.705   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:43:07.564   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:43:07.564   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:43:07.564   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 332753983628; DSPS: 11002693; Offset : -3029071953
,07-27 09:43:08.710   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:43:13.714   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:43:17.679   842  3197 I LocationManagerService: remove 3e46b052
,07-27 09:43:17.793   842  3197 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
07-27 09:43:17.793   842  3197 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 09:43:17.793   842  3197 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-27 09:43:17.794   842  3197 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
07-27 09:43:17.794   842  3197 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,07-27 09:43:18.719   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:43:23.723   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:43:27.565   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:43:27.565   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:43:27.565   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 352754748984; DSPS: 11658078; Offset : -3029069510
,07-27 09:43:28.728   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:43:33.732   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:43:38.737   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:43:42.551  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,07-27 09:43:42.553  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:43:42.554  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:43:42.554  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:43:42.554  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:43:42.562   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 09:43:42.596  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:43:42.600  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:43:42.600  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:43:42.601  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:43:42.601  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:43:42.601  1874  2043 D LEDHandler: Battery Temp: 310, mChargingStatus=5, mChargingStop=false
07-27 09:43:42.603  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 310
07-27 09:43:42.603  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:43:42.603  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 310
07-27 09:43:42.605  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:43:42.609   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:43:42.609   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:43:42.612   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:43:43.742   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:43:47.565   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:43:47.565   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:43:47.565   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 372755437623; DSPS: 12313461; Offset : -3029082333
,07-27 09:43:48.746   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:43:53.751   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:43:54.503  5632  5681 I PlayCommon: [659] com.google.android.play.a.al.e(730): Preparing logs for uploading
07-27 09:43:54.503  5632  5681 I PlayCommon: [659] com.google.android.play.a.al.e(732): No file ready to send
,07-27 09:43:58.755   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:44:00.038  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:44:00.038  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:44:00.039  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:44:00.042  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:44:00.042  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:44:00.043  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:44:00.044  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:44:03.760   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:44:07.566   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:44:07.566   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:44:07.566   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 392756200323; DSPS: 12968846; Offset : -3029082625
,07-27 09:44:08.765   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:44:13.778   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:44:18.782   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:44:23.787   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:44:27.567   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:44:27.567   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:44:27.567   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 412756957035; DSPS: 13624230; Offset : -3029058595
,07-27 09:44:28.791   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:44:33.796   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:44:38.801   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:44:42.710   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:44:42.713  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:44:42.713  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:44:42.713  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:44:42.713  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:44:42.714  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:44:42.753  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:44:42.756  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 309
07-27 09:44:42.757  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:44:42.757  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:44:42.758  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:44:42.758  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:44:42.758  1874  2043 D LEDHandler: Battery Temp: 309, mChargingStatus=5, mChargingStop=false
07-27 09:44:42.759  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:44:42.760  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 309
07-27 09:44:42.762  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:44:42.765   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:44:42.765   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:44:42.768   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:44:43.805   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:44:47.002   842  1287 D PowerManagerServiceEx: acquireWakeLockInternal: lock=712628047, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=842
,07-27 09:44:47.005   842  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1b1e9bf9 type 2 when 432184 android} when 432184
07-27 09:44:47.029   842   842 D PowerManagerServiceEx: releaseWakeLockInternal: lock=712628047 [*alarm*], flags=0x0
,07-27 09:44:47.568   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:44:47.568   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:44:47.568   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 432757927860; DSPS: 14279622; Offset : -3029066052
,07-27 09:44:48.810   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:44:53.814   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:44:58.819   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:45:00.039  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:45:00.041  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:45:00.041  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
07-27 09:45:00.044  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:45:00.044  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:45:00.045  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:45:00.046  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:45:03.823   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:45:07.569   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:45:07.569   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:45:07.569   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 452758671342; DSPS: 14935007; Offset : -3029083868
,07-27 09:45:08.828   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:45:13.833   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:45:18.837   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:45:23.842   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:45:27.569   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:45:27.569   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:45:27.570   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 472759496595; DSPS: 15590394; Offset : -3029082616
,07-27 09:45:28.846   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:45:33.851   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:45:36.974  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:45:36.974  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:45:36.974  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,07-27 09:45:36.979  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:45:36.979  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:45:37.013   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:45:37.024  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:45:37.026  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 307
07-27 09:45:37.027  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:45:37.028  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:45:37.029  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:45:37.029  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:45:37.029  1874  2043 D LEDHandler: Battery Temp: 307, mChargingStatus=5, mChargingStop=false
07-27 09:45:37.030  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:45:37.031  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 307
07-27 09:45:37.033  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:45:37.037   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:45:37.037   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:45:37.039   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:45:38.855   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:45:42.884   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:45:42.887  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:45:42.888  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:45:42.893  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:45:42.894  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:45:42.894  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:45:43.860   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:45:47.570   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:45:47.570   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:45:47.571   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 492760480911; DSPS: 16245786; Offset : -3029074784
,07-27 09:45:48.865   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:45:53.869   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:45:58.874   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:46:00.040  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:46:00.040  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:46:00.040  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:46:00.044  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:46:00.044  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:46:00.045  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:46:00.045  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:46:03.878   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:46:07.571   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:46:07.571   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:46:07.571   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 512761248351; DSPS: 16901171; Offset : -3029070284
,07-27 09:46:08.883   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:46:13.887   294   351 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 09:46:18.892   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:46:23.897   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:46:27.572   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:46:27.572   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:46:27.572   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 532761982770; DSPS: 17556555; Offset : -3029068156
,07-27 09:46:28.901   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:46:33.906   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:46:38.910   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:46:43.029   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:46:43.038  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:46:43.038  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:46:43.039  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:46:43.039  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:46:43.039  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:46:43.071  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 305
07-27 09:46:43.071  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:46:43.071  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 305
,07-27 09:46:43.077  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:46:43.078  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:46:43.078  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:46:43.079  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:46:43.079  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:46:43.079  1874  2043 D LEDHandler: Battery Temp: 305, mChargingStatus=5, mChargingStop=false
07-27 09:46:43.081  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:46:43.085   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:46:43.085   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:46:43.088   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:46:43.915   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:46:47.573   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:46:47.573   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:46:47.573   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 552762683596; DSPS: 18211938; Offset : -3029069391
,07-27 09:46:48.920   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:46:53.924   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:46:58.929   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:47:00.039  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:47:00.039  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 09:47:00.041  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
07-27 09:47:00.043  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:47:00.043  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:47:00.044  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:47:00.045  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:47:03.933   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:47:07.573   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:47:07.573   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:47:07.573   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 572763352441; DSPS: 18867320; Offset : -3029071750
,07-27 09:47:08.938   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:47:13.943   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:47:18.947   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:47:23.952   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:47:27.574   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:47:27.574   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:47:27.574   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 592764098684; DSPS: 19522704; Offset : -3029057825
,07-27 09:47:28.956   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:47:33.961   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:47:38.965   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:47:43.190  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:47:43.190  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:47:43.190  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:47:43.190  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 09:47:43.192   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 09:47:43.193  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:47:43.970   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:47:47.575   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:47:47.575   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:47:47.575   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 612764849146; DSPS: 20178089; Offset : -3029070615
,07-27 09:47:48.974   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:47:53.979   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:47:58.984   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:48:00.039  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:48:00.041  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:48:00.041  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
07-27 09:48:00.043  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:48:00.043  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:48:00.044  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:48:00.045  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:48:03.988   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:48:07.576   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:48:07.576   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:48:07.576   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 632765534086; DSPS: 20833472; Offset : -3029087528
,07-27 09:48:08.993   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:48:13.997   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:48:19.002   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:48:24.006   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:48:27.576   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:48:27.576   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:48:27.576   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 652766299235; DSPS: 21488857; Offset : -3029085135
,07-27 09:48:29.011   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:48:34.016   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:48:39.020   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:48:43.350  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:48:43.350  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:48:43.350  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:48:43.350  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 09:48:43.352   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 09:48:43.353  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:48:43.392  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 304
07-27 09:48:43.392  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:48:43.392  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 304
,07-27 09:48:43.396  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:48:43.396  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:48:43.397  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:48:43.397  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:48:43.397  1874  2043 D LEDHandler: Battery Temp: 304, mChargingStatus=5, mChargingStop=false
07-27 09:48:43.398  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:48:43.400  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:48:43.403   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:48:43.404   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:48:43.406   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:48:44.025   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:48:47.577   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:48:47.577   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:48:47.577   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 672767063446; DSPS: 22144242; Offset : -3029083707
,07-27 09:48:49.029   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:48:54.034   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:48:59.039   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:49:00.041  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:49:00.041  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:49:00.041  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:49:00.045  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:49:00.045  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:49:00.046  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:49:00.046  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:49:04.043   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:49:07.578   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:49:07.578   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:49:07.578   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 692767831667; DSPS: 22799627; Offset : -3029078739
,07-27 09:49:09.048   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:49:14.057   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:49:19.061   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:49:24.066   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:49:27.579   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:49:27.579   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:49:27.579   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 712768582701; DSPS: 23455011; Offset : -3029059788
,07-27 09:49:29.070   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:49:34.075   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:49:39.080   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:49:43.509   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:49:43.517  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:49:43.518  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:49:43.518  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:49:43.519  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:49:43.519  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:49:43.551  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 302
07-27 09:49:43.552  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:49:43.552  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 302
,07-27 09:49:43.554  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:49:43.555  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:49:43.556  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:49:43.556  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:49:43.556  1874  2043 D LEDHandler: Battery Temp: 302, mChargingStatus=5, mChargingStop=false
07-27 09:49:43.559  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:49:43.561  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:49:43.564   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:49:43.564   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:49:43.567   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:49:44.084   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:49:47.579   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:49:47.579   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:49:47.579   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 732769279829; DSPS: 24110394; Offset : -3029064668
,07-27 09:49:49.089   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:49:54.093   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:49:59.098   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:50:00.038  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:50:00.038  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:50:00.038  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:50:00.042  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:50:00.042  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:50:00.043  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:50:00.043  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:50:04.103   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:50:07.580   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:50:07.580   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:50:07.580   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 752769980186; DSPS: 24765777; Offset : -3029066293
,07-27 09:50:09.107   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:50:14.112   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:50:19.116   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:50:24.121   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:50:27.581   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:50:27.581   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:50:27.581   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 772770741481; DSPS: 25421162; Offset : -3029067991
,07-27 09:50:29.126   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:50:34.130   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:50:39.135   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:50:43.669  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,07-27 09:50:43.672   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 09:50:43.678  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:50:43.678  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:50:43.678  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:50:43.679  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:50:43.711  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:50:43.714  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 301
07-27 09:50:43.714  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:50:43.714  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:50:43.716  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:50:43.716  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:50:43.716  1874  2043 D LEDHandler: Battery Temp: 301, mChargingStatus=5, mChargingStop=false
07-27 09:50:43.717  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:50:43.717  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 301
07-27 09:50:43.719  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:50:43.723   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:50:43.723   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:50:43.726   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:50:44.139   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:50:47.581   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:50:47.581   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:50:47.582   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 792771497359; DSPS: 26076547; Offset : -3029075286
,07-27 09:50:49.144   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:50:54.149   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:50:59.153   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:51:00.038  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:51:00.038  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:51:00.038  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:51:00.043  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:51:00.043  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:51:00.044  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:51:00.044  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:51:04.158   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:51:07.582   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:51:07.582   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:51:07.582   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 812772188757; DSPS: 26731930; Offset : -3029085819
,07-27 09:51:09.162   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:51:14.167   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:51:19.171   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:51:24.176   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:51:27.583   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:51:27.583   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:51:27.583   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 832772946197; DSPS: 27387314; Offset : -3029060565
,07-27 09:51:29.181   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:51:34.185   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:51:39.190   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:51:43.830  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:51:43.830  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:51:43.830  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:51:43.830  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 09:51:43.832   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 09:51:43.833  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:51:43.872  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
07-27 09:51:43.872  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:51:43.872  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
,07-27 09:51:43.874  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:51:43.874  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:51:43.876  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:51:43.876  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:51:43.876  1874  2043 D LEDHandler: Battery Temp: 300, mChargingStatus=5, mChargingStop=false
07-27 09:51:43.879  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:51:43.883   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:51:43.883   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:51:43.883   842  1315 D WifiController: battery changed pluggedType: 2
,07-27 09:51:43.886  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:51:44.194   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:51:47.584   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:51:47.584   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:51:47.584   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 852773709419; DSPS: 28042699; Offset : -3029060414
,07-27 09:51:49.199   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:51:54.204   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:51:59.208   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:52:00.039  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:52:00.039  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 09:52:00.042  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
07-27 09:52:00.044  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:52:00.044  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:52:00.045  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:52:00.045  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:52:04.213   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:52:07.584   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:52:07.584   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:52:07.584   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 872774388786; DSPS: 28698082; Offset : -3029082716
,07-27 09:52:09.217   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:52:14.222   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:52:19.226   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:52:24.231   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:52:27.585   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:52:27.585   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:52:27.585   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 892775132528; DSPS: 29353466; Offset : -3029071630
,07-27 09:52:29.235   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:52:34.240   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:52:39.245   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:52:43.989   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:52:43.994  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:52:43.995  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:52:43.995  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:52:43.995  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:52:43.995  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:52:44.029  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:52:44.032  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
07-27 09:52:44.034  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:52:44.034  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:52:44.035  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:52:44.035  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:52:44.035  1874  2043 D LEDHandler: Battery Temp: 300, mChargingStatus=5, mChargingStop=false
07-27 09:52:44.035  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:52:44.036  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
07-27 09:52:44.038  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:52:44.041   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:52:44.041   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:52:44.044   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:52:44.249   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:52:47.586   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:52:47.586   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:52:47.586   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 912775905490; DSPS: 30008851; Offset : -3029061608
,07-27 09:52:49.254   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:52:54.258   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:52:59.263   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:53:00.039  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:53:00.039  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:53:00.039  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:53:00.044  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:53:00.044  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:53:00.044  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:53:00.045  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:53:04.267   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:53:07.587   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:53:07.587   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:53:07.587   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 932776592096; DSPS: 30664234; Offset : -3029076985
,07-27 09:53:09.272   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:53:14.277   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:53:19.281   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:53:21.358   842  1287 D PowerManagerServiceEx: acquireWakeLockInternal: lock=712628047, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=842
,07-27 09:53:21.364   842  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3b24773e type 2 when 946540 com.android.bluetooth} when 946540
07-27 09:53:21.570  2077  3558 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
07-27 09:53:21.570  2077  3558 W bt-smp  : Plain text(LSB ~ MSB) = 85 ff 70 00 00 00 00 00 00 00 00 00 00 00 00 00 ,
,07-27 09:53:21.572  2077  3558 W bt-smp  : Encrypted text(LSB ~ MSB) = 02 d9 08 2f d2 a3 6b ba 8c 6d db 01 02 93 a1 bc 
07-27 09:53:21.572  2077  3558 W bt-btm  : Stopping oneshot timer
07-27 09:53:21.581   842  1927 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7096 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
07-27 09:53:21.616   309   309 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 467us total 36.467ms
,07-27 09:53:21.650   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 479us total 31.502ms
,07-27 09:53:21.685   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 409us total 32.909ms
,07-27 09:53:21.784  7096  7096 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,07-27 09:53:21.792  7096  7096 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@139ddded
07-27 09:53:21.795   842   842 D PowerManagerServiceEx: releaseWakeLockInternal: lock=712628047 [*alarm*], flags=0x0
,07-27 09:53:24.286   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:53:27.587   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:53:27.587   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:53:27.587   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 952777388495; DSPS: 31319620; Offset : -3029073965
,07-27 09:53:29.290   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:53:34.295   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:53:39.299   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:53:44.149   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:53:44.158  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:53:44.159  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:53:44.159  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:53:44.159  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:53:44.159  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:53:44.193  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:53:44.196  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 299
07-27 09:53:44.198  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:53:44.198  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:53:44.199  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:53:44.199  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:53:44.199  1874  2043 D LEDHandler: Battery Temp: 299, mChargingStatus=5, mChargingStop=false
07-27 09:53:44.200  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:53:44.200  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 299
07-27 09:53:44.202  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:53:44.206   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:53:44.206   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:53:44.209   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:53:44.304   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:53:47.588   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:53:47.588   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:53:47.588   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 972778179217; DSPS: 31975006; Offset : -3029076465
,07-27 09:53:49.309   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:53:54.313   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:53:59.318   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:54:00.040  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:54:00.040  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:54:00.040  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:54:00.044  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:54:00.044  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:54:00.045  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:54:00.045  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:54:04.322   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:54:07.589   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:54:07.589   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:54:07.589   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 992778870459; DSPS: 32630389; Offset : -3029087596
,07-27 09:54:07.630  5632  5681 I PlayCommon: [659] com.google.android.play.a.al.e(730): Preparing logs for uploading
07-27 09:54:07.630  5632  5681 I PlayCommon: [659] com.google.android.play.a.al.e(732): No file ready to send
,07-27 09:54:09.327   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:54:14.331   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:54:19.336   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:54:24.349   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:54:27.590   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:54:27.590   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:54:27.590   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1012779626649; DSPS: 33285773; Offset : -3029063776
,07-27 09:54:29.354   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:54:34.358   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:54:39.363   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:54:44.318   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:54:44.326  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:54:44.327  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:54:44.328  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:54:44.328  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:54:44.328  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:54:44.367   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:54:47.590   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:54:47.590   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:54:47.590   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1032780401590; DSPS: 33941159; Offset : -3029082188
,07-27 09:54:49.372   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:54:54.376   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:54:59.381   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:55:00.038  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:55:00.038  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:55:00.038  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:55:00.043  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:55:00.043  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:55:00.044  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:55:00.044  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:55:04.388   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:55:07.591   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:55:07.591   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:55:07.591   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1052781091426; DSPS: 34596541; Offset : -3029063635
,07-27 09:55:09.393   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:55:14.397   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:55:19.402   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:55:24.406   294   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 09:55:27.592   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:55:27.592   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:55:27.592   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1072781851315; DSPS: 35251926; Offset : -3029066841
,07-27 09:55:29.411   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:55:34.416   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:55:39.420   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:55:44.427   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:55:44.476  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:55:44.476  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:55:44.476  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:55:44.476  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 09:55:44.478   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 09:55:44.479  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:55:44.519  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:55:44.522  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
07-27 09:55:44.523  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:55:44.523  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:55:44.524  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:55:44.524  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:55:44.524  1874  2043 D LEDHandler: Battery Temp: 298, mChargingStatus=5, mChargingStop=false
07-27 09:55:44.526  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:55:44.526  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
07-27 09:55:44.528  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:55:44.531   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:55:44.531   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:55:44.534   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:55:47.593   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:55:47.593   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:55:47.593   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1092782619692; DSPS: 35907311; Offset : -3029061430
,07-27 09:55:49.432   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:55:54.436   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:55:59.441   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:56:00.039  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:56:00.041  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:56:00.042  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
07-27 09:56:00.044  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:56:00.044  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:56:00.045  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:56:00.045  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:56:04.445   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:56:07.593   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:56:07.593   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:56:07.593   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1112783311922; DSPS: 36562694; Offset : -3029070922
,07-27 09:56:09.452   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:56:14.457   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:56:19.461   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:56:24.466   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:56:27.594   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:56:27.594   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:56:27.594   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1132784073114; DSPS: 37218079; Offset : -3029072721
,07-27 09:56:29.470   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:56:34.475   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:56:39.480   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:56:44.484   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:56:44.629   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:56:44.638  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:56:44.638  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:56:44.639  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:56:44.639  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:56:44.639  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:56:44.670  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
,07-27 09:56:44.676  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:56:44.677  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:56:44.677  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:56:44.678  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:56:44.678  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:56:44.679  1874  2043 D LEDHandler: Battery Temp: 297, mChargingStatus=5, mChargingStop=false
07-27 09:56:44.679  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:56:44.679  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
07-27 09:56:44.681  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:56:44.685   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:56:44.685   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:56:44.688   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:56:47.595   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:56:47.595   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:56:47.595   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1152784825033; DSPS: 37873464; Offset : -3029084002
,07-27 09:56:49.489   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:56:54.493   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:56:59.498   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:57:00.040  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:57:00.040  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:57:00.040  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:57:00.044  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:57:00.044  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:57:00.045  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:57:00.046  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:57:04.502   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:57:07.596   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:57:07.596   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:57:07.596   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1172785519297; DSPS: 38528846; Offset : -3029060656
,07-27 09:57:09.507   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:57:14.512   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:57:19.516   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:57:24.521   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:57:27.596   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:57:27.596   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:57:27.596   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1192786277466; DSPS: 39184231; Offset : -3029065661
,07-27 09:57:29.525   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:57:34.530   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:57:39.534   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:57:44.539   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:57:44.788  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:57:44.789  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:57:44.789  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:57:44.789  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 09:57:44.800  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:57:44.800   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 09:57:47.597   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:57:47.597   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:57:47.597   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1212787020219; DSPS: 39839616; Offset : -3029085821
,07-27 09:57:49.543   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:57:54.548   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:57:56.973  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:57:56.973  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:57:56.973  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:57:56.973  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 09:57:56.975  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:57:56.991   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:57:57.025  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:57:57.027  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
07-27 09:57:57.028  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:57:57.028  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:57:57.029  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:57:57.029  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:57:57.029  1874  2043 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
07-27 09:57:57.031  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:57:57.031  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
07-27 09:57:57.033  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:57:57.037   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:57:57.037   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:57:57.040   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:57:57.075  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:57:57.078  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
07-27 09:57:57.079  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:57:57.079  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:57:57.080  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:57:57.080  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:57:57.080  1874  2043 D LEDHandler: Battery Temp: 297, mChargingStatus=5, mChargingStop=false
07-27 09:57:57.082  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:57:57.082  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
07-27 09:57:57.084  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:57:57.088   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:57:57.088   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:57:57.102   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:57:59.170   842   979 I UsageStatsService: User[0] Flushing usage stats to disk
,07-27 09:57:59.552   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:58:00.040  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:58:00.040  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:58:00.040  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:58:00.044  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:58:00.044  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:58:00.045  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:58:00.045  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:58:04.557   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:58:07.598   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:58:07.598   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:58:07.598   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1232787780836; DSPS: 40495000; Offset : -3029057547
,07-27 09:58:09.562   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:58:14.566   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:58:19.571   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:58:24.575   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:58:27.598   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:58:27.599   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:58:27.599   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1252788554422; DSPS: 41150386; Offset : -3029077367
,07-27 09:58:29.580   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:58:34.584   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:58:39.589   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:58:44.594   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:58:44.950  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:58:44.950  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:58:44.950  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:58:44.950  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 09:58:44.952   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 09:58:44.953  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:58:44.992  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
07-27 09:58:44.992  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:58:44.992  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
,07-27 09:58:44.994  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:58:44.995  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:58:44.996  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:58:44.996  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:58:44.996  1874  2043 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
07-27 09:58:44.999  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:58:45.003   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:58:45.003   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:58:45.004   842  1315 D WifiController: battery changed pluggedType: 2
,07-27 09:58:45.007  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:58:47.599   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:58:47.599   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:58:47.599   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1272789314571; DSPS: 41805771; Offset : -3029080392
,07-27 09:58:49.598   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:58:54.603   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:58:59.607   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:59:00.038  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:59:00.038  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:59:00.038  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:59:00.042  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:59:00.042  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:59:00.043  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:59:00.044  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:59:04.612   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:59:07.600   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:59:07.600   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:59:07.600   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1292790397636; DSPS: 42461166; Offset : -3029065520
,07-27 09:59:07.631  5632  5681 I PlayCommon: [659] com.google.android.play.a.al.e(730): Preparing logs for uploading
07-27 09:59:07.631  5632  5681 I PlayCommon: [659] com.google.android.play.a.al.e(732): No file ready to send
,07-27 09:59:09.616   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:59:14.621   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:59:19.626   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:59:24.630   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:59:27.601   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:59:27.601   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:59:27.601   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1312790767004; DSPS: 43116538; Offset : -3029062103
,07-27 09:59:29.635   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:59:34.639   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:59:39.644   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:59:44.648   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:59:45.109   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:59:45.118  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:59:45.118  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:59:45.119  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:59:45.119  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:59:45.119  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:59:45.150  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
,07-27 09:59:45.156  2077  3486 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:59:45.157  1910  1910 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:59:45.157  1910  1910 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:59:45.159  1874  2043 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:59:45.159  1874  2043 D LEDHandler: Battery Level Remaining: 100%
07-27 09:59:45.159  1874  2043 D LEDHandler: Battery Temp: 295, mChargingStatus=5, mChargingStop=false
07-27 09:59:45.159  1378  1378 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:59:45.159  1378  1378 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
07-27 09:59:45.161  1378  1378 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:59:45.165   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:59:45.165   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:59:45.168   842  1315 D WifiController: battery changed pluggedType: 2
07-27 09:59:47.601   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:59:47.601   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:59:47.602   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1332791531893; DSPS: 43771923; Offset : -3029060075
,07-27 09:59:49.653   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:59:54.658   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:59:59.662   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:00:00.039  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 10:00:00.039  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 10:00:00.039  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
,07-27 10:00:00.043  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 10:00:00.043  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 10:00:00.044  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 10:00:00.045  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 10:00:04.667   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:00:07.602   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 10:00:07.602   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 10:00:07.602   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1352792308343; DSPS: 44427309; Offset : -3029077108
,07-27 10:00:09.671   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:00:14.676   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:00:19.680   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:00:24.685   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:00:27.603   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 10:00:27.603   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 10:00:27.603   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1372792984012; DSPS: 45082691; Offset : -3029073086
,07-27 10:00:29.690   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:00:34.694   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:00:39.699   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:00:44.703   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:00:45.269   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 10:00:45.272  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 10:00:45.272  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 10:00:45.272  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 10:00:45.272  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 10:00:45.279  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 10:00:47.604   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 10:00:47.604   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 10:00:47.604   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1392793751348; DSPS: 45738076; Offset : -3029068586
,07-27 10:00:49.708   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:00:54.712   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:00:59.717   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:01:00.039  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 10:01:00.039  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 10:01:00.041  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
07-27 10:01:00.043  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 10:01:00.043  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 10:01:00.044  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 10:01:00.045  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 10:01:04.721   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:01:07.604   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 10:01:07.604   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 10:01:07.605   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1412794534049; DSPS: 46393462; Offset : -3029079237
,07-27 10:01:09.726   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:01:14.731   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:01:19.744   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:01:24.748   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:01:27.605   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 10:01:27.605   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 10:01:27.605   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1432795275864; DSPS: 47048846; Offset : -3029070183
,07-27 10:01:29.753   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:01:34.757   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:01:39.762   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:01:44.767   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:01:45.430  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 10:01:45.430  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 10:01:45.430  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 10:01:45.430  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 10:01:45.432   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 10:01:45.433  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 10:01:47.606   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 10:01:47.606   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 10:01:47.606   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1452796039919; DSPS: 47704231; Offset : -3029068650
,07-27 10:01:49.771   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:01:54.776   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:01:59.780   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:02:00.039  1378  1378 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 10:02:00.039  1378  1378 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 10:02:00.039  1378  1378 I [SystemUI]Clock: called onTimeUpdated()
,07-27 10:02:00.043  1378  1378 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 10:02:00.043  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 10:02:00.044  1378  1378 I [SystemUI]DateView: called onTimeUpdated()
07-27 10:02:00.045  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 10:02:04.785   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:02:07.607   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 10:02:07.607   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 10:02:07.607   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1472796814703; DSPS: 48359617; Offset : -3029087297
,07-27 10:02:09.790   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:02:14.794   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:02:19.799   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:02:24.814   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:02:27.608   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 10:02:27.608   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 10:02:27.608   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1492797581309; DSPS: 49015002; Offset : -3029083944
,07-27 10:02:29.818   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:02:34.823   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:02:39.827   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:02:44.832   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 10:02:45.590   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 10:02:45.594  1874  1874 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 10:02:45.595  1378  1378 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 10:02:45.595  1378  1378 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 10:02:45.595  1378  1378 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 10:02:45.595  1378  1378 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 10:02:47.608   842   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 10:02:47.608   842   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 10:02:47.608   842   987 D sensors_hal_Time: tsOffsetIs: Apps: 1512798350261; DSPS: 49670387; Offset : -3029077879
,07-27 10:02:49.837   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,TIME-OUT KILL (timeout was 1400000ms),07-27 10:02:53.965  7225  7225 D AndroidRuntime: 
07-27 10:02:53.965  7225  7225 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-27 10:02:53.976  7225  7225 D AndroidRuntime: CheckJNI is OFF
07-27 10:02:54.399  7225  7225 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-27 10:02:54.463   842   981 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
07-27 10:02:54.466   842   981 I ActivityManager: Killing 6628:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
07-27 10:02:54.525   842  1898 I WindowState: WIN DEATH: Window{2d4a8ba5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 10:02:54.536   842  1898 D InputDispatcher: Focus left window: Window{2d4a8ba5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 10:02:54.536   842  1898 D InputDispatcher: Window went away: Window{2d4a8ba5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 10:02:54.575   842  1064 W PackageSettings: Skipping PackageSetting{288eab98 com.example.hello/10317} due to missing metadata
07-27 10:02:54.593   842   981 I ActivityManager:   Force finishing activity ActivityRecord{1d4489a4 u0 com.test.thalitest/.MainActivity t253}
07-27 10:02:54.622   842   842 V ActivityManager: Display changed displayId=0
07-27 10:02:54.629  1814  1814 D DSDPConnection: Display #0 changed.
07-27 10:02:54.646   842   860 W ActivityManager: Spurious death for ProcessRecord{2cfd99f 6628:com.test.thalitest/u0a30}, curProc for 6628: null
07-27 10:02:54.649   842  1064 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
07-27 10:02:54.650   842  1064 I ActivityManager:   Force finishing activity ActivityRecord{1d4489a4 u0 com.test.thalitest/.MainActivity t253 f}
07-27 10:02:54.650   842  1064 W ActivityManager: Duplicate finish request for ActivityRecord{1d4489a4 u0 com.test.thalitest/.MainActivity t253 f}
07-27 10:02:54.721  2026  2026 I art     : Explicit concurrent mark sweep GC freed 3488(288KB) AllocSpace objects, 2(46KB) LOS objects, 39% free, 12MB/20MB, paused 5.671ms total 67.911ms
07-27 10:02:54.742  1948  1948 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
07-27 10:02:54.751  1378  1378 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
07-27 10:02:54.772  1780  2457 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-27 10:02:54.772  3711  3711 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-27 10:02:54.773  3711  3711 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-27 10:02:54.773  3711  3711 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
07-27 10:02:54.773  3711  3711 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
07-27 10:02:54.773  3711  3711 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 10:02:54.773  3711  3711 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 10:02:54.773  3711  3711 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 10:02:54.773  3711  3711 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
07-27 10:02:54.773  3711  3711 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 10:02:54.773  3711  3711 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 10:02:54.773  3711  3711 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
07-27 10:02:54.773  3711  3711 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
07-27 10:02:54.776   842  1290 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-27 10:02:54.780  1910  1910 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
07-27 10:02:54.793  1948  1948 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
07-27 10:02:54.817  3395  3395 I art     : Explicit concurrent mark sweep GC freed 19177(1184KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 16MB/22MB, paused 1.121ms total 155.797ms
07-27 10:02:54.829   842   981 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7257 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
07-27 10:02:54.842   294   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
07-27 10:02:54.878   842  1971 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7274 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
07-27 10:02:54.929  1948  1948 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
07-27 10:02:54.930  1378  1378 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
07-27 10:02:54.933  1948  1948 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
07-27 10:02:54.934  1948  1948 I Activity: Activity.onPostResume() called 
07-27 10:02:54.946  1948  1948 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
07-27 10:02:54.965  1948  7290 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
07-27 10:02:54.968   842   842 I art     : Explicit concurrent mark sweep GC freed 34568(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 9.530ms total 256.169ms
07-27 10:02:54.975   842  1064 I art     : WaitForGcToComplete blocked for 91.878ms for cause Explicit
07-27 10:02:54.991   842  1036 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
07-27 10:02:54.992   842  1036 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
07-27 10:02:54.992   842  1036 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
07-27 10:02:54.993   842  1036 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
07-27 10:02:54.993   842  1036 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-27 10:02:54.993   842  1036 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@fece82b,  pkg=WindowManager.LayoutParams
07-27 10:02:54.993   842  1036 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
07-27 10:02:54.995   842   861 D InputDispatcher: Focus entered window: Window{28eefb41 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
07-27 10:02:55.001  1378  1378 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
07-27 10:02:55.001  1378  1378 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
07-27 10:02:55.001  1378  1378 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
07-27 10:02:55.001  1378  1378 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
07-27 10:02:55.001  1378  1378 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
07-27 10:02:55.001  1378  1378 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
07-27 10:02:55.019  1948  1948 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-27 10:02:55.021  1948  1948 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-27 10:02:55.024  1948  1948 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
07-27 10:02:55.026  1948  1948 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
07-27 10:02:55.035  7257  7257 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 10:02:55.036  7257  7257 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 10:02:55.040  7257  7257 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-27 10:02:55.041  1948  1948 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
07-27 10:02:55.042  1948  1948 I PhoneWindow: [setNavigationBarColor] color=0x 0
07-27 10:02:55.045   842  1389 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
07-27 10:02:55.047   842  1389 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6628 uid 10030
07-27 10:02:55.090  7274  7274 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
07-27 10:02:55.117   842   842 D administrator: Handling package changes for user 0
07-27 10:02:55.129  1378  1531 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-27 10:02:55.129  1378  1531 D KeyguardModel: createShortcutInfo...
07-27 10:02:55.132  1378  1531 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-27 10:02:55.132  1378  1531 D KeyguardModel: createShortcutInfo...
07-27 10:02:55.135  1378  1531 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 10:02:55.139  1378  1531 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-27 10:02:55.147  1378  1531 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-27 10:02:55.147  1378  1531 D KeyguardModel: createShortcutInfo...
07-27 10:02:55.149  1378  1531 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 10:02:55.149  1378  1531 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-27 10:02:55.152  1948  1948 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
07-27 10:02:55.153  1378  1531 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-27 10:02:55.153  1378  1531 D KeyguardModel: createShortcutInfo...
07-27 10:02:55.156  1378  1531 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 10:02:55.156  1378  1531 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-27 10:02:55.158  1378  1531 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-27 10:02:55.158  1948  1948 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@c54708c time:1520348
07-27 10:02:55.158  1378  1531 D KeyguardModel: createShortcutInfo...
07-27 10:02:55.167   842  1039 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{18517768 u0 com.lge.launcher2/.Launcher t252} time:1520357
07-27 10:02:55.167  1378  1378 D KeyguardModel: handleShortcutListChanged...
07-27 10:02:55.176  1378  1531 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-27 10:02:55.177  1378  1531 D KeyguardModel: createShortcutInfo...
07-27 10:02:55.180  1378  1531 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-27 10:02:55.180  1378  1531 D KeyguardModel: createShortcutInfo...
07-27 10:02:55.182  1378  1531 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 10:02:55.182  1378  1531 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-27 10:02:55.184  1378  1531 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-27 10:02:55.184  1378  1531 D KeyguardModel: createShortcutInfo...
07-27 10:02:55.185  1378  1531 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 10:02:55.186  1378  1531 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-27 10:02:55.187  1378  1531 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-27 10:02:55.187  1378  1531 D KeyguardModel: createShortcutInfo...
07-27 10:02:55.188  1378  1531 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 10:02:55.189  1378  1531 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-27 10:02:55.190  1378  1531 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-27 10:02:55.190  1378  1531 D KeyguardModel: createShortcutInfo...
07-27 10:02:55.192  1635  1635 E b       : Unable to connect to the editor to retrieve text... will retry later
07-27 10:02:55.202  1378  1378 D KeyguardModel: handleShortcutListChanged...
07-27 10:02:55.204  1948  1948 I art     : Explicit concurrent mark sweep GC freed 8175(456KB) AllocSpace objects, 5(681KB) LOS objects, 39% free, 15MB/25MB, paused 1.263ms total 44.899ms
07-27 10:02:55.220  1948  1948 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
07-27 10:02:55.365   842  1064 I art     : Explicit concurrent mark sweep GC freed 13051(1928KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 4.460ms total 386.771ms
07-27 10:02:55.439  7257  7257 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
07-27 10:02:55.465  7257  7257 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
07-27 10:02:55.478  7225  7225 D AndroidRuntime: Shutting down VM
07-27 10:02:55.480  1857  1857 D LCardEmulationManager: getHceAppCount hostAppNum : 0
07-27 10:02:55.481  1857  1857 D LCardEmulationManager: getDefaultRoute
07-27 10:02:55.555   842   842 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
07-27 10:02:55.556   842   842 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-27 10:02:55.559   842   842 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-27 10:02:55.566   842  1351 D TaskPersister: removeObsoleteFile: deleting file=253_task.xml
07-27 10:02:55.692  7257  7257 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
07-27 10:02:55.729   842   861 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7299 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
07-27 10:02:55.730   842   861 I ActivityManager: Killing 6146:com.google.android.gm/u0a53 (adj 15): empty #11
07-27 10:02:55.827   842  1064 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7321 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
07-27 10:02:55.828   842  1971 W libprocessgroup: failed to open /acct/uid_10053/pid_6146/cgroup.procs: No such file or directory
07-27 10:02:55.927  7299  7299 I AppUp4:AppBoxCP: onCreate
07-27 10:02:55.931  7299  7299 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
07-27 10:02:55.932   842   861 I ActivityManager: Killing 6539:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
07-27 10:02:55.942  7299  7299 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
07-27 10:02:55.942  7299  7299 D AndroidRuntime: Shutting down VM
--------- beginning of crash
07-27 10:02:55.943  7299  7299 E AndroidRuntime: FATAL EXCEPTION: main
07-27 10:02:55.943  7299  7299 E AndroidRuntime: Process: com.lge.appbox.client, PID: 7299
07-27 10:02:55.943  7299  7299 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
07-27 10:02:55.943  7299  7299 E AndroidRuntime: 	... 11 more

```
