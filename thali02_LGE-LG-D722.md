#### Test 797510156960f45_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-11 07:24:26.152   290   350 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-11 07:24:27.174  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:27.174  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-11 07:24:27.174  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-11 07:24:27.453  6373  6373 D AndroidRuntime: 
08-11 07:24:27.453  6373  6373 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-11 07:24:27.464  6373  6373 D AndroidRuntime: CheckJNI is OFF
08-11 07:24:27.758  6373  6373 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-11 07:24:27.782   857  1638 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 07:24:27.840   857  1638 D ActivityManager: setTaskToReturnTo : TaskRecord{6e81ea5 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 07:24:27.843   857  1638 D ActivityManager: setTaskToReturnTo : TaskRecord{6e81ea5 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 07:24:27.860   857  1638 D WindowStateEx: AppWindowTokenEx init.. 
08-11 07:24:27.870   857  1050 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-11 07:24:27.890  1875  1875 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-11 07:24:27.892   857  1050 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-11 07:24:27.896   857  1638 D InputDispatcher: Focus left window: Window{219a2332 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-11 07:24:27.897  6373  6373 D AndroidRuntime: Shutting down VM
08-11 07:24:27.903   857  1050 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-11 07:24:27.904   857  1050 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-11 07:24:27.930   857  1050 D SplitWindow: check instance of lgWin Window{32c7d5d u0 Starting com.test.thalitest}
08-11 07:24:27.962   857  1975 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6392 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-11 07:24:27.988  1875  1875 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-11 07:24:28.044  1875  1875 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-11 07:24:28.053   857  2170 I WindowStateAnimator: Starting window displayed
08-11 07:24:28.060   857  1048 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-11 07:24:28.065   857  1048 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-11 07:24:28.069   857  1048 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-11 07:24:28.069   857  1048 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-11 07:24:28.069   857  1048 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-11 07:24:28.072   857  1048 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1dff2d9f,  pkg=WindowManager.LayoutParams
08-11 07:24:28.073   857  1048 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-11 07:24:28.076  1370  1370 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-11 07:24:28.078  1370  1370 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-11 07:24:28.078  1370  1370 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-11 07:24:28.078  1370  1370 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-11 07:24:28.084  1958  1958 I HotwordDetector: Closing mic
08-11 07:24:28.103  1958  2474 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@3700ec37
08-11 07:24:28.103  1958  2474 V AudioRecord: stop()
08-11 07:24:28.103  1958  2474 D AudioRecord: AudioRecord->stop()
,08-11 07:24:28.108   271   271 V AudioFlinger: RecordHandle::stop()
08-11 07:24:28.108   271   271 V AudioFlinger: RecordThread::stop
08-11 07:24:28.127   271   271 V AudioFlinger: Record stopped OK
08-11 07:24:28.130   271   271 V AudioPolicyManager: stopInput() input 17
08-11 07:24:28.132   271   271 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
08-11 07:24:28.133   271   271 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
08-11 07:24:28.133   271  1060 V AudioPolicyService: AudioCommandThread() waking up
08-11 07:24:28.133   271  1060 V AudioPolicyService: AudioCommandThread() processing release audio patch
08-11 07:24:28.133   271  1060 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
08-11 07:24:28.133   271  1060 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
08-11 07:24:28.133   271  1060 V AudioFlinger: ThreadBase::setParameters() routing=0
08-11 07:24:28.136   271  2497 D audio_hw_primary: in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
08-11 07:24:28.174   857  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2356fb15 type 2 when 120000 com.google.android.gms} when 120000
08-11 07:24:28.177  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:28.177  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-11 07:24:28.177  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-11 07:24:28.178   271  2497 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
08-11 07:24:28.178   271  2497 V audio_hw_primary: disable_audio_route: enter: usecase(7)
08-11 07:24:28.178   271  2497 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
08-11 07:24:28.178   271  2497 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-11 07:24:28.181   271  2497 V audio_hw_primary: disable_audio_route: exit
08-11 07:24:28.181   271  2497 E audio_hw_primary: disable_snd_device: enter 144
08-11 07:24:28.181   271  2497 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
08-11 07:24:28.181   271  2497 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
08-11 07:24:28.184   271  2497 V audio_hw_primary: stop_input_stream: exit: status(0)
08-11 07:24:28.184   271  2497 V audio_hw_primary: in_standby: exit:  status(0)
08-11 07:24:28.185   271  2497 V AudioFlinger: RecordThread: loop stopping
08-11 07:24:28.185   271  1060 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-11 07:24:28.185   271  2497 V AudioFlinger: RecordThread: loop starting
08-11 07:24:28.185   271  2497 V AudioFlinger: processConfigEvents_l() remaining events 1
08-11 07:24:28.186   271  2497 V AudioFlinger: processConfigEvents_l() DONE thread 0xb4393000
08-11 07:24:28.186   271  2497 V AudioFlinger: RecordThread: loop stopping
08-11 07:24:28.186   271  1060 V AudioPolicyService: AudioCommandThread() going to sleep
08-11 07:24:28.186   271   271 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
08-11 07:24:28.186   271   271 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
08-11 07:24:28.186   271   271 V AudioPolicyService: AudioCommandThread() adding update audio patch list
08-11 07:24:28.186   271   271 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
08-11 07:24:28.186   271  1061 V AudioPolicyService: AudioCommandThread() waking up
08-11 07:24:28.186   271  1061 V AudioPolicyService: AudioCommandThread() processing update audio patch list
08-11 07:24:28.187   271  1061 V AudioPolicyService: AudioCommandThread() going to sleep
08-11 07:24:28.188   271   271 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
08-11 07:24:28.188   271   271 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
08-11 07:24:28.188   271  1060 V AudioPolicyService: AudioCommandThread() waking up
08-11 07:24:28.188   271  1060 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
08-11 07:24:28.188   271  1060 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 271
08-11 07:24:28.188   271  1060 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
08-11 07:24:28.188   271  1060 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-11 07:24:28.188   271  2497 V AudioFlinger: RecordThread: loop starting
08-11 07:24:28.189   271  2497 V AudioFlinger: processConfigEvents_l() remaining events 1
08-11 07:24:28.189   271  2497 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
08-11 07:24:28.190   271  2497 V audio_hw_primary: in_set_parameters: exit: status(0)
08-11 07:24:28.190   271  2497 V AudioFlinger: processConfigEvents_l() DONE thread 0xb4393000
08-11 07:24:28.190   271  2497 V AudioFlinger: RecordThread: loop stopping
08-11 07:24:28.190   271  1060 V AudioPolicyService: AudioCommandThread() going to sleep
08-11 07:24:28.201  1958  2474 V AudioRecord: stop()
08-11 07:24:28.202  1958  2474 V AudioRecord: stop()
08-11 07:24:28.202  1958  2474 V AudioRecord: stop()
08-11 07:24:28.204   271  2673 V AudioFlinger: RecordHandle::stop()
08-11 07:24:28.204   271  2673 V AudioFlinger: RecordThread::stop
08-11 07:24:28.204   271  2673 V AudioPolicyManager: releaseInput() 17
08-11 07:24:28.204   271  2673 V AudioPolicyManager: closeInput(17)
08-11 07:24:28.204   271  2673 V AudioFlinger: closeInput() 17
08-11 07:24:28.204   271  2673 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-11 07:24:28.204  1370  2338 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-11 07:24:28.204  1749  1764 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-11 07:24:28.204   271  2673 V AudioFlinger: ThreadBase::exit
08-11 07:24:28.205  2039  2060 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-11 07:24:28.205   271  2497 V AudioFlinger: RecordThread: loop starting
08-11 07:24:28.205   271  1356 V AudioFlinger: releasing 16 from 1958 for -1
08-11 07:24:28.205   271  1356 V AudioFlinger:  decremented refcount to 0
08-11 07:24:28.205   271  1356 V AudioFlinger: purging stale effects
08-11 07:24:28.205  2867  3964 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-11 07:24:28.205  3154  3173 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-11 07:24:28.206   271  2497 V AudioFlinger: RecordThread 0xb4393000 exiting
08-11 07:24:28.206   857  1873 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-11 07:24:28.206   271  2673 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb4036520)
08-11 07:24:28.206   271  2673 D audio_hw_primary: in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
08-11 07:24:28.206   271  2673 V audio_hw_primary: in_standby: exit:  status(0)
08-11 07:24:28.207  1958  6363 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-11 07:24:28.207   271  2673 V AudioPolicyService: AudioCommandThread() adding update audio port list
08-11 07:24:28.207   271  2673 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
08-11 07:24:28.207   271  1061 V AudioPolicyService: AudioCommandThread() waking up
08-11 07:24:28.207   271  1061 V AudioPolicyService: AudioCommandThread() processing update audio port list
08-11 07:24:28.207   271  1061 V AudioPolicyService: AudioCommandThread() going to sleep
08-11 07:24:28.207   271  2673 V AudioPolicyManager: releaseInput() exit
08-11 07:24:28.207   271  2673 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
08-11 07:24:28.207   271  2673 V AudioFlinger: removeClient_l() pid 1958, calling pid 271
08-11 07:24:28.210  1958  2488 I HotwordRecognitionRnr: Stopping hotword detection.
08-11 07:24:28.214  1958  2493 I HotwordRecognitionRnr: Hotword detection finished
08-11 07:24:28.220  6392  6392 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-11 07:24:28.348  6392  6392 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-11 07:24:28.423  6392  6392 I LibraryLoader: Time to load native libraries: 11 ms (timestamps 5816-5827)
08-11 07:24:28.423  6392  6392 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 07:24:28.457  6392  6392 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {723b878}
08-11 07:24:28.459  6392  6392 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 07:24:28.463  6392  6392 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 07:24:28.478  6392  6392 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-11 07:24:28.480  6392  6392 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 07:24:28.486  6392  6392 E SysUtils: ApplicationContext is null in ApplicationStatus
08-11 07:24:28.590  6392  6392 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-11 07:24:28.598  6392  6392 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 07:24:28.598  6392  6392 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 07:24:28.601  6392  6392 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 07:24:28.601  6392  6392 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 07:24:28.601  6392  6392 I Adreno-EGL: Build Date: 03/02/15 Mon
08-11 07:24:28.601  6392  6392 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-11 07:24:28.601  6392  6392 I Adreno-EGL: Remote Branch: 
08-11 07:24:28.601  6392  6392 I Adreno-EGL: Local Patches: 
08-11 07:24:28.601  6392  6392 I Adreno-EGL: Reconstruct Branch: 
08-11 07:24:28.692   271  1298 V AudioPolicyService: registerClient() client 0xb40278c0, uid 10030
08-11 07:24:28.706   857  1049 D BluetoothManagerService: Message: 20
08-11 07:24:28.706   857  1049 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fda882:true
08-11 07:24:28.713  2039  3725 D BluetoothAdapterService(711651254): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a0193bc
08-11 07:24:28.846  6392  6392 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 07:24:28.858  6392  6392 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-11 07:24:28.865  6392  6392 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-11 07:24:28.869  6392  6392 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-11 07:24:28.869  6392  6392 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-11 07:24:28.884  6392  6392 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-11 07:24:28.896  6392  6392 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 07:24:28.896  6392  6392 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-11 07:24:28.951  6392  6392 I Activity: Activity.onPostResume() called 
,08-11 07:24:28.958  6392  6454 D OpenGLRenderer: Render dirty regions requested: true
08-11 07:24:28.958  6392  6454 I OpenGLRenderer: Initialized EGL, version 1.4
08-11 07:24:28.964  6392  6454 D OpenGLRenderer: Enabling debug mode 0
,08-11 07:24:28.981  6392  6392 D Atlas   : Validating map...
,08-11 07:24:28.986   857  2063 D SplitWindow: check instance of lgWin Window{df53632 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 07:24:29.001  6392  6441 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-11 07:24:29.033   857  2063 D InputDispatcher: Focus entered window: Window{df53632 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 07:24:29.102   857  1050 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s175ms
08-11 07:24:29.103   857  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2c9827a u0 com.test.thalitest/.MainActivity t259} time:126507
,08-11 07:24:29.104   857  1819 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-11 07:24:29.122  6392  6392 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2c818ef2 time:126527
,08-11 07:24:29.174  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:29.175  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-11 07:24:29.175  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-11 07:24:29.276  6392  6392 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6392
,08-11 07:24:29.691  1801  1801 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-11 07:24:29.694  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-11 07:24:29.694  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-11 07:24:29.698  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-11 07:24:29.698  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
08-11 07:24:29.725  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
08-11 07:24:29.726  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-11 07:24:29.726  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
08-11 07:24:29.727  1801  1988 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-11 07:24:29.727  1801  1988 D LEDHandler: Battery Level Remaining: 100%
08-11 07:24:29.727  1801  1988 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,08-11 07:24:29.728  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-11 07:24:29.729  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-11 07:24:29.732  2039  3500 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-11 07:24:29.735   857  1312 D WifiController: battery changed pluggedType: 2
08-11 07:24:29.737   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 07:24:29.737   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 07:24:29.737  6289  6289 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-11 07:24:29.738  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-11 07:24:29.744   475   475 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-11 07:24:29.991  6392  6392 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 07:24:30.191  6392  6457 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426130176
,08-11 07:24:30.212  6392  6457 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 07:24:30.212  6392  6457 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 07:24:30.212  6392  6457 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 07:24:30.212  6392  6457 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 07:24:30.212  6392  6457 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-11 07:24:30.212  6392  6457 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@185bda97 added. We now have 1 listener(s)
08-11 07:24:30.220   857  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 07:24:30.224  6392  6457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,08-11 07:24:30.228  6392  6457 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-11 07:24:30.229  6392  6457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 07:24:30.230  6392  6457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 07:24:30.237  6392  6457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 07:24:30.237  6392  6457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 07:24:30.237  6392  6457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 07:24:30.237  6392  6457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-11 07:24:30.237  6392  6457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 07:24:30.237  6392  6457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 07:24:30.237  6392  6457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 07:24:30.237  6392  6457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 07:24:30.237  6392  6457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 07:24:30.237  6392  6457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 07:24:30.237  6392  6457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 07:24:30.237  6392  6457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 07:24:30.237  6392  6457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 07:24:30.237  6392  6457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 07:24:30.237  6392  6457 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@103798a2 added. We now have 1 listener(s)
08-11 07:24:30.238  6392  6457 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 07:24:30.250  6392  6457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 07:24:30.250  6392  6457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-11 07:24:30.253  6392  6457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 07:24:30.254  6392  6457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 07:24:30.254  6392  6457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-11 07:24:30.260  6392  6457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 07:24:30.260   857  1818 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 07:24:30.261  6392  6457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-11 07:24:30.271  2039  3677 D BluetoothAdapterService(711651254): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a0193bc
,08-11 07:24:30.276  6392  6457 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-11 07:24:30.276  6392  6457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 07:24:30.276  6392  6457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 07:24:30.276  6392  6457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 07:24:30.276  6392  6457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 07:24:30.276  6392  6457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 07:24:30.276  6392  6457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 07:24:30.276  6392  6457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 07:24:30.276  6392  6457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 07:24:30.276  6392  6457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 07:24:30.276  6392  6457 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 07:24:30.279  6392  6392 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 07:24:30.282  6392  6392 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 07:24:30.286  6392  6457 I io.jxcore.node.LifeCycleMonitor: start: OK
08-11 07:24:30.320  6392  6392 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 07:24:30.443  6392  6406 I art     : CheckpointMarkThreadRoots callback created = 0xb06b7320
,08-11 07:24:30.473  6392  6406 I art     : CheckpointMarkThreadRoots callback created = 0xb06b72f0
,08-11 07:24:31.157   290   350 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 07:24:31.179  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:31.179  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-11 07:24:31.179  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-11 07:24:31.432  6392  6481 W jxcore-log: Initializing JXcore engine
,08-11 07:24:31.433  6392  6481 W jxcore-log: JXcore engine is ready
08-11 07:24:31.541  6481  6481 W Thread-754: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8450]" dev="sockfs" ino=8450 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-11 07:24:31.541  6481  6481 W Thread-754: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-11 07:24:31.541  6481  6481 W Thread-754: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5751]" dev="sockfs" ino=5751 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-11 07:24:31.551  6481  6481 W Thread-754: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-11 07:24:31.551  6481  6481 W Thread-754: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-11 07:24:31.551  6481  6481 W Thread-754: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[30840]" dev="sockfs" ino=30840 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-11 07:24:31.583  6392  6481 W jxcore-log: Starting JXcore engine
,08-11 07:24:31.753  6392  6481 W jxcore-log: Platform android
08-11 07:24:31.753  6392  6481 W jxcore-log: 
08-11 07:24:31.753  6392  6481 W jxcore-log: Process ARCH arm
08-11 07:24:31.753  6392  6481 W jxcore-log: 
,08-11 07:24:32.074  6392  6481 I jxcore-log: JXcore Cordova bridge is ready!
08-11 07:24:32.074  6392  6481 I jxcore-log: 
08-11 07:24:32.074  6392  6481 W jxcore-log: JXcore engine is started
,08-11 07:24:32.079  6392  6457 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-11 07:24:32.080  6392  6392 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-11 07:24:32.181  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:32.181  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-11 07:24:32.181  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-11 07:24:33.131   857  1284 V AlarmManager: RTC_WAKEUP set : Alarm{25c5e0ad type 0 when 1470893073128 com.google.android.googlequicksearchbox} when 1470893073128
,08-11 07:24:34.183  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:34.183  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-11 07:24:34.183  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-11 07:24:34.450   857  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{12838fe2 type 2 when 131849 com.google.android.gms} when 131849
,08-11 07:24:34.484  1731  1731 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-11 07:24:34.687  3379  3688 D NetworkUsageDbReporter: Started reporting usage
,08-11 07:24:34.722  1731  1731 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-11 07:24:34.783  3379  3688 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 33655
08-11 07:24:34.783  3379  3688 D NetworkUsageDbReporter: keeping row: 1457
08-11 07:24:34.784  3379  3688 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 2211
08-11 07:24:34.784  3379  3688 D NetworkUsageDbReporter: keeping row: 1456
08-11 07:24:34.784  3379  3688 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 11386
08-11 07:24:34.784  3379  3688 D NetworkUsageDbReporter: keeping row: 1459
08-11 07:24:34.784  3379  3688 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 2292
08-11 07:24:34.784  3379  3688 D NetworkUsageDbReporter: keeping row: 1455
08-11 07:24:34.784  3379  3688 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 11975
08-11 07:24:34.784  3379  3688 D NetworkUsageDbReporter: keeping row: 1454
08-11 07:24:34.784  3379  3688 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1991
08-11 07:24:34.784  3379  3688 D NetworkUsageDbReporter: keeping row: 1453
08-11 07:24:34.784  3379  3688 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 14683
08-11 07:24:34.784  3379  3688 D NetworkUsageDbReporter: keeping row: 1452
08-11 07:24:34.784  3379  3688 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 4108
08-11 07:24:34.784  3379  3688 D NetworkUsageDbReporter: keeping row: 1451
08-11 07:24:34.784  3379  3688 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 158958
08-11 07:24:34.784  3379  3688 D NetworkUsageDbReporter: keeping row: 1450
08-11 07:24:34.785  3379  3688 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 22104
08-11 07:24:34.785  3379  3688 D NetworkUsageDbReporter: keeping row: 1444
08-11 07:24:34.785  3379  3688 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 5649
08-11 07:24:34.785  3379  3688 D NetworkUsageDbReporter: keeping row: 1443
08-11 07:24:34.785  3379  3688 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 14735
08-11 07:24:34.785  3379  3688 D NetworkUsageDbReporter: keeping row: 1449
,08-11 07:24:34.788  3379  3688 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 15957
08-11 07:24:34.788  3379  3688 D NetworkUsageDbReporter: keeping row: 1458
08-11 07:24:34.788  3379  3688 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 54187
08-11 07:24:34.788  3379  3688 D NetworkUsageDbReporter: keeping row: 1445
08-11 07:24:34.788  3379  3688 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 411173
08-11 07:24:34.788  3379  3688 D NetworkUsageDbReporter: keeping row: 1442
08-11 07:24:34.811  3379  3688 D NetworkUsageDbReporter: Finished reporting usage.
,08-11 07:24:34.863  3379  6532 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-11 07:24:34.864  3379  6532 D SchedPeriodicTask: Scheduled AdAttestation task.
08-11 07:24:35.185  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:35.185  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-11 07:24:35.185  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-11 07:24:35.532   857  1019 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 07:24:35.532   857  1019 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 07:24:35.532   857  1019 D sensors_hal_Time: tsOffsetIs: Apps: 132936329069; DSPS: 4454442; Offset : -3007045454
,08-11 07:24:36.162   290   350 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 07:24:36.915   857  1874 I ActivityManager: Process com.google.android.apps.docs (pid 6240) has died
,08-11 07:24:37.189  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:37.189  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-11 07:24:37.189  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-11 07:24:39.191  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,08-11 07:24:39.192  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-11 07:24:39.192  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-11 07:24:40.196  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:40.196  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-11 07:24:40.196  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-11 07:24:41.167   290   350 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 07:24:41.196  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:41.197  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-11 07:24:41.197  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-11 07:24:42.666  2867  2867 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,08-11 07:24:42.675  2867  2867 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
08-11 07:24:43.200  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:43.200  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-11 07:24:43.200  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-11 07:24:44.202  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:44.202  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-11 07:24:44.202  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-11 07:24:45.204  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:45.204  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-11 07:24:45.204  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-11 07:24:46.172   290   350 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-11 07:24:48.208  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:48.209  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-11 07:24:48.209  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-11 07:24:48.808   857  1052 I PowerManagerService: ALS enabled for SRE
08-11 07:24:48.808   857  1052 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26212 ms ago)
,08-11 07:24:48.837   857  1345 D qdlights: set_light_backlight: 252
,08-11 07:24:48.849   857  1345 D qdlights: set_light_backlight: 249
,08-11 07:24:48.866   857  1345 D qdlights: set_light_backlight: 246
,08-11 07:24:48.883   857  1345 D qdlights: set_light_backlight: 242
,08-11 07:24:48.900   857  1345 D qdlights: set_light_backlight: 239
,08-11 07:24:48.916   857  1345 D qdlights: set_light_backlight: 236
,08-11 07:24:48.933   857  1345 D qdlights: set_light_backlight: 232
,08-11 07:24:48.950   857  1345 D qdlights: set_light_backlight: 229
,08-11 07:24:48.966   857  1345 D qdlights: set_light_backlight: 226
,08-11 07:24:48.983   857  1345 D qdlights: set_light_backlight: 222
,08-11 07:24:49.000   857  1345 D qdlights: set_light_backlight: 219
,08-11 07:24:49.016   857  1345 D qdlights: set_light_backlight: 216
,08-11 07:24:49.033   857  1345 D qdlights: set_light_backlight: 212
,08-11 07:24:49.050   857  1345 D qdlights: set_light_backlight: 209
,08-11 07:24:49.066   857  1345 D qdlights: set_light_backlight: 206
,08-11 07:24:49.083   857  1345 D qdlights: set_light_backlight: 202
,08-11 07:24:49.100   857  1345 D qdlights: set_light_backlight: 199
,08-11 07:24:49.116   857  1345 D qdlights: set_light_backlight: 196
,08-11 07:24:49.133   857  1345 D qdlights: set_light_backlight: 192
,08-11 07:24:49.150   857  1345 D qdlights: set_light_backlight: 189
,08-11 07:24:49.166   857  1345 D qdlights: set_light_backlight: 186
,08-11 07:24:49.183   857  1345 D qdlights: set_light_backlight: 182
,08-11 07:24:49.200   857  1345 D qdlights: set_light_backlight: 179
,08-11 07:24:49.211  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:49.211  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-11 07:24:49.211  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-11 07:24:49.226   857  1345 D qdlights: set_light_backlight: 176
,08-11 07:24:49.233   857  1345 D qdlights: set_light_backlight: 172
08-11 07:24:49.250   857  1345 D qdlights: set_light_backlight: 169
,08-11 07:24:49.266   857  1345 D qdlights: set_light_backlight: 166
,08-11 07:24:49.283   857  1345 D qdlights: set_light_backlight: 162
,08-11 07:24:49.300   857  1345 D qdlights: set_light_backlight: 159
,08-11 07:24:49.316   857  1345 D qdlights: set_light_backlight: 156
,08-11 07:24:49.333   857  1345 D qdlights: set_light_backlight: 152
,08-11 07:24:49.350   857  1345 D qdlights: set_light_backlight: 149
,08-11 07:24:49.366   857  1345 D qdlights: set_light_backlight: 146
,08-11 07:24:49.383   857  1345 D qdlights: set_light_backlight: 142
,08-11 07:24:49.400   857  1345 D qdlights: set_light_backlight: 139
,08-11 07:24:49.416   857  1345 D qdlights: set_light_backlight: 136
,08-11 07:24:49.433   857  1345 D qdlights: set_light_backlight: 132
,08-11 07:24:49.449   857  1345 D qdlights: set_light_backlight: 129
,08-11 07:24:49.466   857  1345 D qdlights: set_light_backlight: 126
,08-11 07:24:49.483   857  1345 D qdlights: set_light_backlight: 122
,08-11 07:24:49.499   857  1345 D qdlights: set_light_backlight: 119
,08-11 07:24:49.516   857  1345 D qdlights: set_light_backlight: 116
,08-11 07:24:49.533   857  1345 D qdlights: set_light_backlight: 112
,08-11 07:24:49.550   857  1345 D qdlights: set_light_backlight: 109
,08-11 07:24:49.566   857  1345 D qdlights: set_light_backlight: 106
,08-11 07:24:49.583   857  1345 D qdlights: set_light_backlight: 102
,08-11 07:24:49.600   857  1345 D qdlights: set_light_backlight: 99
,08-11 07:24:49.616   857  1345 D qdlights: set_light_backlight: 96
,08-11 07:24:49.633   857  1345 D qdlights: set_light_backlight: 92
,08-11 07:24:49.650   857  1345 D qdlights: set_light_backlight: 89
,08-11 07:24:49.666   857  1345 D qdlights: set_light_backlight: 86
,08-11 07:24:49.683   857  1345 D qdlights: set_light_backlight: 82
,08-11 07:24:49.700   857  1345 D qdlights: set_light_backlight: 79
,08-11 07:24:49.716   857  1345 D qdlights: set_light_backlight: 76
,08-11 07:24:49.733   857  1345 D qdlights: set_light_backlight: 72
,08-11 07:24:49.750   857  1345 D qdlights: set_light_backlight: 69
,08-11 07:24:49.766   857  1345 D qdlights: set_light_backlight: 66
,08-11 07:24:49.783   857  1345 D qdlights: set_light_backlight: 62
,08-11 07:24:49.800   857  1345 D qdlights: set_light_backlight: 59
,08-11 07:24:49.816   857  1345 D qdlights: set_light_backlight: 56
,08-11 07:24:49.833   857  1345 D qdlights: set_light_backlight: 52
,08-11 07:24:49.850   857  1345 D qdlights: set_light_backlight: 49
,08-11 07:24:49.866   857  1345 D qdlights: set_light_backlight: 46
,08-11 07:24:49.883   857  1345 D qdlights: set_light_backlight: 42
,08-11 07:24:49.900   857  1345 D qdlights: set_light_backlight: 39
,08-11 07:24:49.916   857  1345 D qdlights: set_light_backlight: 36
,08-11 07:24:49.933   857  1345 D qdlights: set_light_backlight: 32
,08-11 07:24:49.950   857  1345 D qdlights: set_light_backlight: 29
,08-11 07:24:49.966   857  1345 D qdlights: set_light_backlight: 26
,08-11 07:24:49.983   857  1345 D qdlights: set_light_backlight: 22
,08-11 07:24:50.000   857  1345 D qdlights: set_light_backlight: 19
,08-11 07:24:50.016   857  1345 D qdlights: set_light_backlight: 16
,08-11 07:24:50.033   857  1345 D qdlights: set_light_backlight: 12
,08-11 07:24:50.050   857  1345 D qdlights: set_light_backlight: 10
,08-11 07:24:50.213  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:50.213  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-11 07:24:50.214  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-11 07:24:51.177   290   350 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-11 07:24:52.217  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:52.218  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-11 07:24:52.218  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-11 07:24:53.219  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:53.219  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-11 07:24:53.219  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-11 07:24:55.223  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:55.223  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-11 07:24:55.223  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-11 07:24:55.532   857  1019 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 07:24:55.533   857  1019 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 07:24:55.533   857  1019 D sensors_hal_Time: tsOffsetIs: Apps: 152937128020; DSPS: 5109828; Offset : -3007040038
,08-11 07:24:55.795   857  1052 I PowerManagerService: ALS enabled for SRE
08-11 07:24:55.795   857  1052 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33200 ms ago)
,08-11 07:24:55.799   857  1052 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
08-11 07:24:55.808   857  1052 I PowerManagerService: ALS enabled for SRE
,08-11 07:24:55.808   857  1052 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33213 ms ago)
08-11 07:24:55.813   857  1052 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
08-11 07:24:55.816   857  1052 I PowerManagerService: Sleeping (uid 1000)...
08-11 07:24:55.816   857  1052 D LPWGController: [updateScreenState] screen on = false
08-11 07:24:55.819   857  1052 D LPWGController: disable proximity sensor
08-11 07:24:55.819   857  1052 D LPWGController: enable proximity sensor
08-11 07:24:55.828   857  1052 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@39cd4f1d] by com.android.server.power.ProximitySensorListener.enable():120
08-11 07:24:55.834   857  1052 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
08-11 07:24:55.834   857  1052 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
08-11 07:24:55.834   857  1052 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
08-11 07:24:55.834   857  1052 I sensors_hal_Ctx: activate: handle is 48, enable
08-11 07:24:55.834   857  1052 V sensors_hal_Ctx: activate sensors is 1400000000000
08-11 07:24:55.834   857  1052 D sensors_hal_Thresh: enable: handle=48
08-11 07:24:55.834   857  1052 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
08-11 07:24:55.835   857  1052 D sensors_hal_Util: waitForResponse: timeout=1000
,08-11 07:24:55.839   857  1020 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
08-11 07:24:55.839   857  1020 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
08-11 07:24:55.839   857  1052 D sensors_hal_Thresh: enable: Received response: 0
08-11 07:24:55.840   857  1052 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33244 ms ago)
08-11 07:24:55.851   857  1052 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 07:24:55.851   857  1052 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 07:24:55.851   857  1052 I Adreno-EGL: Build Date: 03/02/15 Mon
08-11 07:24:55.851   857  1052 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-11 07:24:55.851   857  1052 I Adreno-EGL: Remote Branch: 
08-11 07:24:55.851   857  1052 I Adreno-EGL: Local Patches: 
08-11 07:24:55.851   857  1052 I Adreno-EGL: Reconstruct Branch: 
,08-11 07:24:55.885   245  1346 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1041 us)
,08-11 07:24:56.067   424   999 I Sensors : sns_pwr.c(273):acquiring wakelock
,08-11 07:24:56.069   857  1020 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
08-11 07:24:56.070   857  1020 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
08-11 07:24:56.070   857  1020 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
08-11 07:24:56.070   857  1020 D sensors_hal_Thresh: processInd: handle 48, count=1
08-11 07:24:56.070   857  1020 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
08-11 07:24:56.070   857  1020 I sensors_hal_Thresh: processInd : proximity state changed - FAR
08-11 07:24:56.070   857  1054 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
08-11 07:24:56.070   857  1054 D sensors_hal_Ctx: poll: count: 256
08-11 07:24:56.070   857  1054 I sensors_hal_Ctx: poll: released wakelock sensor_ind
08-11 07:24:56.070   857  1054 D sensors_hal_Util: waitForResponse: timeout=0
08-11 07:24:56.077   857  1052 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
08-11 07:24:56.077   857  1052 I LPWGController: current mode = 1  value = 1 1
08-11 07:24:56.078   857  1052 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
08-11 07:24:56.173   857  1052 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,08-11 07:24:56.182   290   350 I ThermalEngine: Sensor:pa_therm0:31000 mC
08-11 07:24:56.226  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-11 07:24:56.226  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-11 07:24:56.226  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-11 07:24:56.419   857  1345 D qdlights: set_light_backlight: 0
,08-11 07:24:56.438   857  1052 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,08-11 07:24:56.440   857  1052 I sensors_hal_Ctx: activate: handle is 46, disable
08-11 07:24:56.440   857  1052 V sensors_hal_Ctx: activate sensors is 1000000000000
08-11 07:24:56.440   857  1052 D sensors_hal_LP2: enable: handle=46
08-11 07:24:56.440   857  1052 D sensors_hal_LP2: enable: Disabling sensor handle=46
08-11 07:24:56.440   857  1052 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
08-11 07:24:56.443   245   245 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
08-11 07:24:56.443   245   245 D qdhwcomposer: hwc_blank: Blanking display: 0
08-11 07:24:56.447   857  1050 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
08-11 07:24:56.448   857   857 V ActivityManager: Display changed displayId=0
,08-11 07:24:56.485   857  1044 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
08-11 07:24:56.485   857  1044 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,08-11 07:24:56.503  1749  1749 D DSDPConnection: Display #0 changed.
,08-11 07:24:56.618   245   245 D qdhwcomposer: hwc_blank: Done blanking display: 0
08-11 07:24:56.618   857  1345 D SurfaceControl: Excessive delay in setPowerMode(): 175ms
,08-11 07:24:56.620   245   678 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
08-11 07:24:56.620   857  1345 I QCOM PowerHAL: Got set_interactive hint
,08-11 07:24:56.630  6392  6392 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-11 07:24:56.638  6392  6392 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
08-11 07:24:56.641  1370  1921 D KeyguardViewMediator: onScreenTurnedOff(3)
08-11 07:24:56.646  1328  1343 D SmartCoverViewMediator: onScreenTurnedOff(3)
08-11 07:24:56.654  1328  1343 D SmartCoverViewMediator: notifyScreenOffLocked
,08-11 07:24:56.659  1328  1328 D SmartCoverViewMediator: handleNotifyScreenOFF
08-11 07:24:56.660  1370  1921 D KeyguardViewMediator: notifyScreenOffLocked
,08-11 07:24:56.675  6392  6392 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5d43f8e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@33467467, 16908290=android.view.AbsSavedState$1@33467467}, android:focusedViewId=100}]}]
08-11 07:24:56.675  6392  6392 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-11 07:24:56.675  6392  6392 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-11 07:24:56.675  6392  6392 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-11 07:24:56.688  1370  1921 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
08-11 07:24:56.689  1370  1370 D KeyguardViewMediator: handleNotifyScreenOff
,08-11 07:24:56.719  1370  1370 D ScreenTurnOffBySensor: unregisterProximitySensor
,08-11 07:24:56.720   857   857 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
08-11 07:24:56.731   271  2673 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 857
08-11 07:24:56.732   271  2673 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-11 07:24:56.732   271  2673 V voice   : voice_set_parameters: enter: screen_state=on
08-11 07:24:56.734   271  2673 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
,08-11 07:24:56.734   271  2673 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-11 07:24:56.734   271  2673 V voice   : voice_set_parameters: exit with code(0)
08-11 07:24:56.734   271  2673 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
08-11 07:24:56.734   271  2673 V msm8974_platform: platform_set_parameters: enter: screen_state=on
08-11 07:24:56.735   271  2673 V msm8974_platform: platform_set_parameters: exit with code(0)
08-11 07:24:56.735   271  2673 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-11 07:24:56.735   271  2673 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
08-11 07:24:56.736   271  2673 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-11 07:24:56.736   271  2673 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-11 07:24:56.739  1370  1370 D StatusBarWindowView: onScreenTurnedOff why = 3
08-11 07:24:56.740   857  1306 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
08-11 07:24:56.744  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
08-11 07:24:56.746  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
,08-11 07:24:57.303   857   975 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,08-11 07:24:57.310  1837  1837 I QCNEJ   : |CORE| sendScreenState: state:true
08-11 07:24:57.318  1801  1988 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
,08-11 07:24:57.320  1801  1988 D LEDService: stopPatternFlashing()
08-11 07:24:57.321  1801  1988 D qdlights: set_light_notifications: 0,0,0,0,3
08-11 07:24:57.323  1801  1988 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-11 07:24:57.323  1801  1988 D qdlights: set_light_notifications: 0,0,0,0,3
08-11 07:24:57.325  1801  1988 I LEDService: updateLightsLocked : turn off led
08-11 07:24:57.325  1801  1988 D qdlights: set_light_notifications: 0,0,0,0,3
08-11 07:24:57.337  1801  1988 D LEDHandler: RESTART MSG
,08-11 07:24:57.362   857  1818 D SplitWindow: check instance of lgWin Window{2c6f6360 u0 SearchPanel}
,08-11 07:24:57.380   857   874 D InputDispatcher: Window went away: Window{328d20f7 u0 SearchPanel}
,08-11 07:24:57.384  1370  1370 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
08-11 07:24:57.403  1370  1370 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,08-11 07:24:57.408  1801  1801 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
08-11 07:24:57.410  1801  1801 D Cliptray Service: lockStatus = 0
08-11 07:24:57.416  1783  1783 D LNfcService: action : android.intent.action.SCREEN_ON
,08-11 07:24:57.425  1783  6569 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
08-11 07:24:57.425  1783  6569 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
08-11 07:24:57.426  1783  6569 D LNfcService: isRequireNfcCRouting() return true
08-11 07:24:57.426  1783  6569 D LNfcService: isHCERoutingtoHost() return : true
08-11 07:24:57.426  1783  6569 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-11 07:24:57.426  1783  6569 D NfcService: mEnableLPD: true
08-11 07:24:57.426  1783  6569 D NfcService: mEnableReader: false
08-11 07:24:57.426  1783  6569 D NfcService: mEnableHostRouting: true
08-11 07:24:57.426  1783  6569 D NfcService: newParams.techmask= mTechMask: default
08-11 07:24:57.426  1783  6569 D NfcService: mEnableLPD: true
08-11 07:24:57.426  1783  6569 D NfcService: mEnableReader: false
08-11 07:24:57.426  1783  6569 D NfcService: mEnableHostRouting: true
08-11 07:24:57.426  1783  6569 D NfcService: screenState= 3
08-11 07:24:57.426  1783  6569 D NfcService: Discovery configuration equal, not updating.
08-11 07:24:57.429   857   857 D Ulp_jni : JNI:system_update. Event-0
,08-11 07:24:57.468  1749  1749 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
08-11 07:24:57.489   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 07:24:57.489   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 07:24:57.490   857   857 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
,08-11 07:24:57.495  2849  2849 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 7:24:57
08-11 07:24:57.497  2849  2849 D WeatherService: 2 : ACTION screen on
08-11 07:24:57.499  2849  2849 D WeatherService: 2 : shouldTimeTickRegistered : false
08-11 07:24:57.516  2849  2849 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-11 07:24:57.516  2849  2849 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 7:24:57
,08-11 07:24:57.528  4125  4125 D AppCleanupService: android.intent.action.SCREEN_ON
,08-11 07:24:57.558   271  1298 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 857
08-11 07:24:57.558   271  1298 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-11 07:24:57.558   271  1298 V voice   : voice_set_parameters: enter: screen_state=off
08-11 07:24:57.558   271  1298 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
08-11 07:24:57.558   271  1298 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-11 07:24:57.558   271  1298 V voice   : voice_set_parameters: exit with code(0)
08-11 07:24:57.558   271  1298 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
08-11 07:24:57.558   271  1298 V msm8974_platform: platform_set_parameters: enter: screen_state=off
08-11 07:24:57.558   271  1298 V msm8974_platform: platform_set_parameters: exit with code(0)
08-11 07:24:57.558   271  1298 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-11 07:24:57.558   271  1298 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-11 07:24:57.558   271  1298 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-11 07:24:57.560   857  1312 D WifiController: CMD_SCREEN_OFF 
08-11 07:24:57.560   857  1312 D WifiController: shouldWifiStayAwake TRUE
08-11 07:24:57.567  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
,08-11 07:24:57.567   424   437 I Sensors : sns_pwr.c(301):releasing wakelock
08-11 07:24:57.568   857   975 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
08-11 07:24:57.576  1837  1837 I QCNEJ   : |CORE| sendScreenState: state:false
08-11 07:24:57.578  1801  1988 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
08-11 07:24:57.578  1801  1988 D LEDService: stopPatternFlashing()
08-11 07:24:57.578  1801  1988 D qdlights: set_light_notifications: 0,0,0,0,3
,08-11 07:24:57.580  1801  1988 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-11 07:24:57.580  1801  1988 D qdlights: set_light_notifications: 0,0,0,0,3
08-11 07:24:57.582  1801  1988 I LEDService: updateLightsLocked : turn on led
08-11 07:24:57.582  1801  1988 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
08-11 07:24:57.582  1801  1988 E LEDService: Can't handle this request of patternId:0
08-11 07:24:57.582  1801  1988 D LEDHandler: RESTART MSG
08-11 07:24:57.587  1801  1801 D VolumeVibrator: clear
08-11 07:24:57.594  1801  1801 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
08-11 07:24:57.595  1783  1783 D LNfcService: action : android.intent.action.SCREEN_OFF
,08-11 07:24:57.606  1783  2203 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
08-11 07:24:57.621  1875  1875 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,08-11 07:24:57.632  1749  1749 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
08-11 07:24:57.638   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 07:24:57.638   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 07:24:57.638   857   857 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
08-11 07:24:57.640  2849  2849 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 7:24:57
08-11 07:24:57.640  2849  2849 D WeatherService: 2 : ACTION screen off
08-11 07:24:57.642  2849  2849 D WeatherService: 2 : TimeTick Receiver Unregister
08-11 07:24:57.642  2849  2849 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 7:24:57
08-11 07:24:57.646  4125  4125 D AppCleanupService: android.intent.action.SCREEN_OFF
08-11 07:24:57.651  4125  6582 D AppCleanupService: AppUsageStatsSaveTask
,08-11 07:24:57.694  1783  2586 E NxpNfcJni: getReconnectState = 0x0
,08-11 07:24:57.700  1783  2203 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-11 07:24:57.700  1783  2203 D LCardEmulationManager: getDefaultRoute
08-11 07:24:57.700  1783  2203 D LNfcService: isRequireNfcCRouting() return true
08-11 07:24:57.700  1783  2203 D LNfcService: isHCERoutingtoHost() return : true
08-11 07:24:57.700  1783  2203 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-11 07:24:57.700  1783  2203 D NfcService: mEnableLPD: true
08-11 07:24:57.700  1783  2203 D NfcService: mEnableReader: false
08-11 07:24:57.700  1783  2203 D NfcService: mEnableHostRouting: true
08-11 07:24:57.700  1783  2203 D NfcService: newParams.techmask= mTechMask: 0
08-11 07:24:57.700  1783  2203 D NfcService: mEnableLPD: true
08-11 07:24:57.700  1783  2203 D NfcService: mEnableReader: false
08-11 07:24:57.700  1783  2203 D NfcService: mEnableHostRouting: true
08-11 07:24:57.700  1783  2203 D NfcService: screenState= 1
08-11 07:24:57.755  1783  2586 E NxpNfcJni: getReconnectState = 0x0
,08-11 07:24:58.131  6392  6481 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 07:24:58.131  6392  6481 I jxcore-log: 
,08-11 07:24:58.135  6392  6481 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 07:24:58.135  6392  6481 I jxcore-log: 
08-11 07:24:58.143  2039  3677 D BluetoothAdapterService(711651254): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a0193bc
08-11 07:24:58.144  6392  6481 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 07:24:58.144  6392  6481 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 07:24:58.144  6392  6481 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 07:24:58.144  6392  6481 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 07:24:58.144  6392  6481 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 07:24:58.144  6392  6481 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 07:24:58.144  6392  6481 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 07:24:58.144  6392  6481 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 07:24:58.145  2039  3725 D BluetoothAdapterService(711651254): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a0193bc
08-11 07:24:58.146  6392  6481 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 07:24:58.148  6392  6481 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 07:24:58.148  6392  6481 I jxcore-log: 
08-11 07:24:58.150  6392  6481 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 07:24:58.150  6392  6481 I jxcore-log: 
08-11 07:24:58.695  6392  6481 I jxcore-log: Unit Test app is loaded
08-11 07:24:58.695  6392  6481 I jxcore-log: 
,08-11 07:24:58.710  6392  6392 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-11 07:24:58.711  6392  6481 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 07:24:58.711  6392  6481 I jxcore-log: 
08-11 07:24:58.722  6392  6481 I jxcore-log: My device name is: LGE-LG-D722
08-11 07:24:58.722  6392  6481 I jxcore-log: 
,08-11 07:25:00.055  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-11 07:25:00.055  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
08-11 07:25:00.055  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,08-11 07:25:00.058  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
08-11 07:25:00.058  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
08-11 07:25:00.059  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
08-11 07:25:00.059  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
08-11 07:25:01.187   290   350 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-11 07:25:01.666   857  1284 D PowerManagerServiceEx: acquireWakeLockInternal: lock=599842714, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,08-11 07:25:01.669   857  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{17f4c019 type 2 when 159066 com.android.systemui} when 159066
08-11 07:25:01.675  1370  1370 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,08-11 07:25:01.692  1749  2552 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
08-11 07:25:01.697  1749  2552 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-11 07:25:01.697  1749  2552 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-11 07:25:01.701  1749  2552 V TelecomServiceImpl: getCallState : 0
,08-11 07:25:01.705  1749  1764 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
08-11 07:25:01.705  1749  1764 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-11 07:25:01.705  1749  1764 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-11 07:25:01.706  1370  1370 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
08-11 07:25:01.707  1370  1370 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,08-11 07:25:01.721   857   857 D PowerManagerServiceEx: releaseWakeLockInternal: lock=599842714 [*alarm*], flags=0x0
08-11 07:25:02.619  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-11 07:25:02.619  6392  6481 I jxcore-log: 
,08-11 07:25:03.602  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-11 07:25:03.602  6392  6481 I jxcore-log: 
,08-11 07:25:03.639  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-11 07:25:03.639  6392  6481 I jxcore-log: 
,08-11 07:25:05.813  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-11 07:25:05.813  6392  6481 I jxcore-log: 
,08-11 07:25:06.165  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-11 07:25:06.165  6392  6481 I jxcore-log: 
,08-11 07:25:06.173  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-11 07:25:06.173  6392  6481 I jxcore-log: 
08-11 07:25:06.181  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-11 07:25:06.181  6392  6481 I jxcore-log: 
,08-11 07:25:06.196   290   350 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-11 07:25:06.207  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-11 07:25:06.207  6392  6481 I jxcore-log: 
,08-11 07:25:06.214  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-11 07:25:06.214  6392  6481 I jxcore-log: 
08-11 07:25:07.280  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-11 07:25:07.280  6392  6481 I jxcore-log: 
,08-11 07:25:07.300  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-11 07:25:07.300  6392  6481 I jxcore-log: 
,08-11 07:25:07.317  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-11 07:25:07.317  6392  6481 I jxcore-log: 
,08-11 07:25:07.330  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-11 07:25:07.330  6392  6481 I jxcore-log: 
08-11 07:25:07.417  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-11 07:25:07.417  6392  6481 I jxcore-log: 
,08-11 07:25:07.523  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-11 07:25:07.523  6392  6481 I jxcore-log: 
,08-11 07:25:07.537  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-11 07:25:07.537  6392  6481 I jxcore-log: 
,08-11 07:25:07.832  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-11 07:25:07.832  6392  6481 I jxcore-log: 
,08-11 07:25:07.874  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-11 07:25:07.874  6392  6481 I jxcore-log: 
,08-11 07:25:07.882  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-11 07:25:07.882  6392  6481 I jxcore-log: 
08-11 07:25:07.890  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-11 07:25:07.890  6392  6481 I jxcore-log: 
,08-11 07:25:07.918  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-11 07:25:07.918  6392  6481 I jxcore-log: 
,08-11 07:25:08.051  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-11 07:25:08.051  6392  6481 I jxcore-log: 
,08-11 07:25:08.072  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-11 07:25:08.072  6392  6481 I jxcore-log: 
,08-11 07:25:08.119  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-11 07:25:08.119  6392  6481 I jxcore-log: 
,08-11 07:25:08.141  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-11 07:25:08.141  6392  6481 I jxcore-log: 
,08-11 07:25:08.169  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-11 07:25:08.169  6392  6481 I jxcore-log: 
,08-11 07:25:08.227  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-11 07:25:08.227  6392  6481 I jxcore-log: 
08-11 07:25:08.234  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-11 07:25:08.234  6392  6481 I jxcore-log: 
,08-11 07:25:08.552  6392  6481 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-11 07:25:08.552  6392  6481 I jxcore-log: 
,08-11 07:25:08.564  2039  2067 D BluetoothAdapterService(711651254): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a0193bc
08-11 07:25:08.568  6392  6481 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,08-11 07:25:08.574  6392  6481 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-11 07:25:08.574  6392  6481 I jxcore-log: 
08-11 07:25:11.200   290   350 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-11 07:25:15.533   857  1019 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 07:25:15.533   857  1019 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 07:25:15.533   857  1019 D sensors_hal_Time: tsOffsetIs: Apps: 172938012908; DSPS: 5765217; Offset : -3007039743
,08-11 07:25:16.205   290   350 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-11 07:25:16.217  3379  4339 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-11 07:25:20.038  1731  4371 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-11 07:25:21.209   290   350 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 07:25:26.214   290   350 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 07:25:27.661   857  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{321398de type 2 when 185058 com.google.android.gms} when 185058
,08-11 07:25:28.109   857  1638 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6618 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,08-11 07:25:28.194  6618  6618 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-11 07:25:28.196  6618  6618 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-11 07:25:28.252  1731  1748 I art     : Explicit concurrent mark sweep GC freed 61024(3MB) AllocSpace objects, 20(320KB) LOS objects, 39% free, 14MB/24MB, paused 1.725ms total 134.815ms
,08-11 07:25:28.270  6618  6618 I MultiDex: VM with version 2.1.0 has multidex support
08-11 07:25:28.270  6618  6618 I MultiDex: install
08-11 07:25:28.270  6618  6618 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-11 07:25:28.351  6618  6618 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-11 07:25:28.437  6618  6618 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-11 07:25:28.438  6618  6618 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e49a01c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-11 07:25:28.439  6618  6618 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-11 07:25:28.442  6618  6618 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
08-11 07:25:28.443  6618  6618 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
08-11 07:25:28.456  6618  6618 D ChimeraCfgMgr: Reading stored module config
,08-11 07:25:28.596  1731  1731 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=20e36d40-8403-43c3-aa63-5971dab14688
08-11 07:25:28.601  6618  6618 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
08-11 07:25:28.601  6618  6618 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
08-11 07:25:28.671  6618  6651 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-11 07:25:28.805   857  1873 I art     : Explicit concurrent mark sweep GC freed 75102(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 2.146ms total 210.157ms
,08-11 07:25:28.828  6618  6636 I art     : CheckpointMarkThreadRoots callback created = 0xb042d340
,08-11 07:25:28.854  6618  6636 I art     : CheckpointMarkThreadRoots callback created = 0xb042d320
,08-11 07:25:28.859  1731  1731 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-11 07:25:28.861  1731  1731 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-11 07:25:28.877   271  1298 D WVCdm   : Instantiating CDM.
,08-11 07:25:28.878   271  1356 I WVCdm   : CdmEngine::OpenSession
,08-11 07:25:28.878   271  1356 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
08-11 07:25:28.924  1731  2518 W GCoreFlp: No location to return for getLastLocation()
,08-11 07:25:28.928   271  1356 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
08-11 07:25:28.929   271  1356 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
08-11 07:25:28.929   271  1356 W WVCdm   : L1 library not specified. Falling Back to L3
,08-11 07:25:28.972  1731  2459 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-11 07:25:28.984  1731  2383 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
08-11 07:25:28.999  6618  6638 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-11 07:25:28.999  6618  6638 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-11 07:25:29.001  6618  6638 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-11 07:25:29.001  6618  6638 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-11 07:25:29.001   267  1013 E BandwidthController: [LG DATA] No such appUid: 10006
08-11 07:25:29.001   267  1013 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-11 07:25:29.002   267  6669 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-11 07:25:29.002   267  6669 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-11 07:25:29.002   267  6669 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-11 07:25:29.002   267  6669 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-11 07:25:29.003   267  6669 D libc-netbsd: res_queryN name = xxxxx succeed
08-11 07:25:29.003  6618  6638 I System.out: propertyValue:false
08-11 07:25:29.023   271  1356 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-11 07:25:29.024   271  2673 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-11 07:25:29.024   271  2673 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-11 07:25:29.024   271  2673 I WVCdm   : CdmEngine::GenerateKeyRequest
08-11 07:25:29.031   271  2673 D WVCdm   : PrepareKeyRequest: nonce=716057835
08-11 07:25:29.036  3379  6611 D UdcContextInitService: registered all accounts: true
,08-11 07:25:29.075  6618  6638 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-11 07:25:29.075  6618  6638 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-11 07:25:29.852  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-11 07:25:29.852  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-11 07:25:29.852  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-11 07:25:29.852  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
08-11 07:25:29.853  1801  1801 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-11 07:25:29.891  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
08-11 07:25:29.891  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-11 07:25:29.892  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-11 07:25:29.892  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-11 07:25:29.892  2039  3500 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-11 07:25:29.893  1801  1988 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-11 07:25:29.893  1801  1988 D LEDHandler: Battery Level Remaining: 100%
08-11 07:25:29.893  1801  1988 D LEDHandler: Battery Temp: 282, mChargingStatus=5, mChargingStop=false
08-11 07:25:29.893  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
08-11 07:25:29.894   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 07:25:29.894   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 07:25:29.894   857  1312 D WifiController: battery changed pluggedType: 2
08-11 07:25:29.898  6289  6289 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-11 07:25:29.902  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-11 07:25:29.910   475   475 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-11 07:25:30.158  6674  6674 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=41 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-11 07:25:30.253  6674  6674 I dex2oat : dex2oat took 91.544ms (threads: 4)
,08-11 07:25:30.271  6618  6638 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 07:25:30.271  6618  6638 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 07:25:30.271  6618  6638 I Adreno-EGL: Build Date: 03/02/15 Mon
08-11 07:25:30.271  6618  6638 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-11 07:25:30.271  6618  6638 I Adreno-EGL: Remote Branch: 
08-11 07:25:30.271  6618  6638 I Adreno-EGL: Local Patches: 
08-11 07:25:30.271  6618  6638 I Adreno-EGL: Reconstruct Branch: 
,08-11 07:25:30.418  6618  6638 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 07:25:30.418  6618  6638 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 07:25:30.418  6618  6638 I Adreno-EGL: Build Date: 03/02/15 Mon
08-11 07:25:30.418  6618  6638 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-11 07:25:30.418  6618  6638 I Adreno-EGL: Remote Branch: 
08-11 07:25:30.418  6618  6638 I Adreno-EGL: Local Patches: 
08-11 07:25:30.418  6618  6638 I Adreno-EGL: Reconstruct Branch: 
,08-11 07:25:30.435   857  1789 I ActivityManager: Process com.android.contacts (pid 6067) has died
,08-11 07:25:30.472  6618  6638 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 07:25:30.472  6618  6638 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 07:25:30.472  6618  6638 I Adreno-EGL: Build Date: 03/02/15 Mon
08-11 07:25:30.472  6618  6638 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-11 07:25:30.472  6618  6638 I Adreno-EGL: Remote Branch: 
08-11 07:25:30.472  6618  6638 I Adreno-EGL: Local Patches: 
08-11 07:25:30.472  6618  6638 I Adreno-EGL: Reconstruct Branch: 
,08-11 07:25:30.577  1731  6615 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,08-11 07:25:30.577  1731  6615 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-11 07:25:30.579  1731  6615 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-11 07:25:30.579  1731  6615 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-11 07:25:30.579   267  1013 E BandwidthController: [LG DATA] No such appUid: 10006
08-11 07:25:30.579   267  1013 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-11 07:25:30.580   267  6690 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-11 07:25:30.580   267  6690 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-11 07:25:30.580   267  6690 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-11 07:25:30.580   267  6690 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-11 07:25:30.580   267  6690 D libc-netbsd: res_queryN name = xxxxx succeed
08-11 07:25:30.581  1731  6615 I System.out: propertyValue:false
08-11 07:25:30.650  1731  6615 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-11 07:25:30.650  1731  6615 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-11 07:25:30.863  1731  2383 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-11 07:25:30.889  1731  2383 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-11 07:25:30.910  1731  2383 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-11 07:25:29.090+0200, stopTime=2016-08-11 07:25:30.901+0200, duration=1811ms
,08-11 07:25:30.931  1731  6695 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,08-11 07:25:30.933  1731  6695 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-11 07:25:30.934  1731  6695 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-11 07:25:30.934  1731  6695 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-11 07:25:30.934   267  1013 E BandwidthController: [LG DATA] No such appUid: 10006
08-11 07:25:30.934   267  1013 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-11 07:25:30.935   267  6707 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-11 07:25:30.935   267  6707 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-11 07:25:30.935   267  6707 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-11 07:25:30.935   267  6707 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-11 07:25:30.935   267  6707 D libc-netbsd: res_queryN name = xxxxx succeed
08-11 07:25:30.936  1731  6695 I System.out: propertyValue:false
,08-11 07:25:30.996  3129  4783 I art     : Explicit concurrent mark sweep GC freed 1334(45KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.360ms total 37.708ms
,08-11 07:25:31.202   271  1298 I WVCdm   : CdmEngine::CloseSession
,08-11 07:25:31.206   271  1298 I WVCdm   : L3 Terminate.
08-11 07:25:31.219   290   350 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 07:25:31.303  1731  2383 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-11 07:25:31.485  1731  6720 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-11 07:25:31.487  1731  6714 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-11 07:25:31.513  1731  6720 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-11 07:25:31.514  1731  6714 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-11 07:25:31.539  1731  6720 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-11 07:25:31.541  1731  6714 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-11 07:25:31.541  1731  6714 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
08-11 07:25:31.545  1731  6714 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
08-11 07:25:31.576   857  1789 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-11 07:25:31.614  1731  6714 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,08-11 07:25:31.615  1731  6714 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-11 07:25:31.615  1731  6714 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-11 07:25:31.615  1731  6714 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-11 07:25:31.615   267  1013 E BandwidthController: [LG DATA] No such appUid: 10006
08-11 07:25:31.616   267  1013 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-11 07:25:31.616   267  6721 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-11 07:25:31.616   267  6721 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-11 07:25:31.616   267  6721 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-11 07:25:31.617   267  6721 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-11 07:25:31.617   267  6721 D libc-netbsd: res_queryN name = xxxxx succeed
08-11 07:25:31.617  1731  6714 I System.out: propertyValue:false
,08-11 07:25:31.971  1731  6714 I art     : Explicit concurrent mark sweep GC freed 44312(2MB) AllocSpace objects, 12(213KB) LOS objects, 40% free, 15MB/25MB, paused 1.757ms total 100.099ms
,08-11 07:25:32.018   857  1818 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-11 07:25:32.207   857  1874 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-11 07:25:32.462   857   875 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-11 07:25:32.701   857  1874 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-11 07:25:32.920   857  2170 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-11 07:25:33.098   857  2063 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-11 07:25:33.223  1731  2383 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-11 07:25:35.537   857  1019 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 07:25:35.537   857  1019 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 07:25:35.537   857  1019 D sensors_hal_Time: tsOffsetIs: Apps: 192941681442; DSPS: 6420697; Offset : -3007034178
,08-11 07:25:36.224   290   350 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 07:25:41.228   290   350 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 07:25:46.233   290   350 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 07:25:51.238   290   350 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 07:25:55.538   857  1019 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 07:25:55.538   857  1019 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 07:25:55.538   857  1019 D sensors_hal_Time: tsOffsetIs: Apps: 212942366800; DSPS: 7076080; Offset : -3007050021
,08-11 07:25:56.242   290   350 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 07:26:00.038  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-11 07:26:00.038  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
08-11 07:26:00.038  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,08-11 07:26:00.042  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
08-11 07:26:00.042  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
08-11 07:26:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
08-11 07:26:00.044  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
08-11 07:26:01.247   290   350 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 07:26:06.251   290   350 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 07:26:10.010   857  1284 D PowerManagerServiceEx: acquireWakeLockInternal: lock=599842714, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,08-11 07:26:10.014   857  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{35677020 type 2 when 219026 android} when 219026
08-11 07:26:10.154   857   857 D PowerManagerServiceEx: releaseWakeLockInternal: lock=599842714 [*alarm*], flags=0x0
,08-11 07:26:11.256   290   350 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 07:26:15.538   857  1019 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 07:26:15.538   857  1019 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 07:26:15.538   857  1019 D sensors_hal_Time: tsOffsetIs: Apps: 232943053615; DSPS: 7731462; Offset : -3007036364
,08-11 07:26:16.260   290   350 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 07:26:21.265   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:26:26.270   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:26:30.015  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-11 07:26:30.015  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-11 07:26:30.015  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-11 07:26:30.016  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-11 07:26:30.017   475   475 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-11 07:26:30.019  1801  1801 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-11 07:26:30.063  2039  3500 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-11 07:26:30.066  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
08-11 07:26:30.066  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-11 07:26:30.066  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
08-11 07:26:30.068  1801  1988 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-11 07:26:30.068  1801  1988 D LEDHandler: Battery Level Remaining: 100%
08-11 07:26:30.068  1801  1988 D LEDHandler: Battery Temp: 278, mChargingStatus=5, mChargingStop=false
08-11 07:26:30.069  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-11 07:26:30.069  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-11 07:26:30.072  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-11 07:26:30.075   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 07:26:30.075   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 07:26:30.079   857  1312 D WifiController: battery changed pluggedType: 2
08-11 07:26:30.080  6289  6289 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-11 07:26:31.274   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:26:35.539   857  1019 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 07:26:35.539   857  1019 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 07:26:35.539   857  1019 D sensors_hal_Time: tsOffsetIs: Apps: 252943909075; DSPS: 8386850; Offset : -3007033599
,08-11 07:26:36.279   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:26:41.283   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:26:46.288   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:26:51.292   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:26:55.540   857  1019 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 07:26:55.540   857  1019 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 07:26:55.540   857  1019 D sensors_hal_Time: tsOffsetIs: Apps: 272944679277; DSPS: 9042236; Offset : -3007057167
,08-11 07:26:56.297   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:27:00.039  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-11 07:27:00.039  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
08-11 07:27:00.039  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,08-11 07:27:00.043  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
08-11 07:27:00.043  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
08-11 07:27:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
08-11 07:27:00.045  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
08-11 07:27:01.302   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:27:06.306   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:27:11.311   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:27:15.541   857  1019 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 07:27:15.541   857  1019 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 07:27:15.541   857  1019 D sensors_hal_Time: tsOffsetIs: Apps: 292945341404; DSPS: 9697617; Offset : -3007035804
,08-11 07:27:16.315   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:27:21.320   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:27:26.324   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:27:30.174   475   475 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-11 07:27:30.177  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-11 07:27:30.184  1801  1801 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-11 07:27:30.184  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-11 07:27:30.184  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-11 07:27:30.184  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
08-11 07:27:30.217  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
08-11 07:27:30.217  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-11 07:27:30.218  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
,08-11 07:27:30.221  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-11 07:27:30.221  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-11 07:27:30.222  1801  1988 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-11 07:27:30.222  1801  1988 D LEDHandler: Battery Level Remaining: 100%
08-11 07:27:30.222  1801  1988 D LEDHandler: Battery Temp: 276, mChargingStatus=5, mChargingStop=false
08-11 07:27:30.223  2039  3500 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-11 07:27:30.225  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-11 07:27:30.228   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 07:27:30.228   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 07:27:30.229   857  1312 D WifiController: battery changed pluggedType: 2
08-11 07:27:30.231  6289  6289 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-11 07:27:31.329   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:27:35.541   857  1019 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 07:27:35.541   857  1019 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 07:27:35.542   857  1019 D sensors_hal_Time: tsOffsetIs: Apps: 312946105875; DSPS: 10353002; Offset : -3007034220
,08-11 07:27:36.333   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:27:41.338   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:27:46.343   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:27:51.347   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:27:55.542   857  1019 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 07:27:55.542   857  1019 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 07:27:55.542   857  1019 D sensors_hal_Time: tsOffsetIs: Apps: 332946722170; DSPS: 11008383; Offset : -3007059029
,08-11 07:27:56.352   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:28:00.038  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-11 07:28:00.038  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
08-11 07:28:00.038  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,08-11 07:28:00.043  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
08-11 07:28:00.043  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
08-11 07:28:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
08-11 07:28:00.045  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
08-11 07:28:01.356   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:28:04.931   857  3203 I LocationManagerService: remove 2671527d
08-11 07:28:04.932   857  3203 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-11 07:28:04.932   857  3203 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-11 07:28:04.932   857  3203 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-11 07:28:04.932   857  3203 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-11 07:28:04.933   857  3203 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-11 07:28:06.361   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:28:11.365   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:28:15.543   857  1019 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 07:28:15.543   857  1019 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 07:28:15.543   857  1019 D sensors_hal_Time: tsOffsetIs: Apps: 352947459506; DSPS: 11663767; Offset : -3007054116
,08-11 07:28:16.370   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:28:21.375   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:28:26.379   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:28:30.344  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-11 07:28:30.344  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-11 07:28:30.349  1801  1801 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-11 07:28:30.350  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-11 07:28:30.350  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
08-11 07:28:30.352   475   475 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-11 07:28:30.388  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
08-11 07:28:30.388  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-11 07:28:30.388  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,08-11 07:28:30.391  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-11 07:28:30.391  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-11 07:28:30.392  1801  1988 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-11 07:28:30.392  1801  1988 D LEDHandler: Battery Level Remaining: 100%
08-11 07:28:30.392  1801  1988 D LEDHandler: Battery Temp: 275, mChargingStatus=5, mChargingStop=false
08-11 07:28:30.394  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-11 07:28:30.396  2039  3500 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-11 07:28:30.401   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 07:28:30.401   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 07:28:30.404   857  1312 D WifiController: battery changed pluggedType: 2
08-11 07:28:30.405  6289  6289 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-11 07:28:31.384   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 07:28:35.486  6392  6481 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-11 07:28:35.486  6392  6481 I jxcore-log: 
,08-11 07:28:35.543   857  1019 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 07:28:35.544   857  1019 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 07:28:35.544   857  1019 D sensors_hal_Time: tsOffsetIs: Apps: 372948169446; DSPS: 12319150; Offset : -3007045532
,08-11 07:28:36.061  6785  6785 D AndroidRuntime: 
08-11 07:28:36.061  6785  6785 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-11 07:28:36.070  6785  6785 D AndroidRuntime: CheckJNI is OFF
08-11 07:28:36.325  6785  6785 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 07:28:36.380   857   992 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,08-11 07:28:36.384   857   992 I ActivityManager: Killing 6392:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
08-11 07:28:36.388   290   350 I ThermalEngine: Sensor:pa_therm0:29000 mC
08-11 07:28:36.452   857  2063 I WindowState: WIN DEATH: Window{df53632 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 07:28:36.463   857  2063 D InputDispatcher: Focus left window: Window{df53632 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 07:28:36.463   857  2063 D InputDispatcher: Window went away: Window{df53632 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 07:28:36.472   857  1057 W PackageSettings: Skipping PackageSetting{123636d2 com.example.hello/10317} due to missing metadata
,08-11 07:28:36.597   857   992 I ActivityManager:   Force finishing activity ActivityRecord{2c9827a u0 com.test.thalitest/.MainActivity t259}
,08-11 07:28:36.609   857   857 V ActivityManager: Display changed displayId=0
,08-11 07:28:36.613  1749  1749 D DSDPConnection: Display #0 changed.
08-11 07:28:36.633   857  1975 W ActivityManager: Spurious death for ProcessRecord{19f4add9 6392:com.test.thalitest/u0a30}, curProc for 6392: null
,08-11 07:28:36.640   857  1057 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
,08-11 07:28:36.710  1370  1370 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-11 07:28:36.716  1837  1837 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
08-11 07:28:36.721   857  1287 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-11 07:28:36.725  1875  1875 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
08-11 07:28:36.725  1731  2459 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-11 07:28:36.726  1958  1958 I art     : Explicit concurrent mark sweep GC freed 3033(267KB) AllocSpace objects, 2(47KB) LOS objects, 39% free, 12MB/20MB, paused 2.659ms total 80.282ms
,08-11 07:28:36.738  3653  3653 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-11 07:28:36.740  3653  3653 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-11 07:28:36.740  3653  3653 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-11 07:28:36.740  3653  3653 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-11 07:28:36.740  3653  3653 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 07:28:36.740  3653  3653 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 07:28:36.740  3653  3653 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 07:28:36.740  3653  3653 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-11 07:28:36.740  3653  3653 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 07:28:36.740  3653  3653 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 07:28:36.741  3653  3653 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-11 07:28:36.741  3653  3653 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,08-11 07:28:36.766  1875  1875 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,08-11 07:28:36.781   857   992 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6812 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-11 07:28:36.808  3379  3379 I art     : Explicit concurrent mark sweep GC freed 17805(1084KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 16MB/22MB, paused 1.145ms total 163.629ms
,08-11 07:28:36.844  1370  1370 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-11 07:28:36.883  1370  1501 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 07:28:36.883  1370  1501 D KeyguardModel: createShortcutInfo...
08-11 07:28:36.884  1875  1875 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-11 07:28:36.887  1875  1875 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-11 07:28:36.887  1875  1875 I Activity: Activity.onPostResume() called 
08-11 07:28:36.906  1370  1501 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 07:28:36.906  1370  1501 D KeyguardModel: createShortcutInfo...
,08-11 07:28:36.908  1370  1501 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 07:28:36.909  1370  1501 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 07:28:36.911  1875  1875 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-11 07:28:36.914  1370  1501 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 07:28:36.914  1370  1501 D KeyguardModel: createShortcutInfo...
,08-11 07:28:36.927  1370  1501 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 07:28:36.927  1370  1501 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 07:28:36.930  1370  1501 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 07:28:36.930  1370  1501 D KeyguardModel: createShortcutInfo...
08-11 07:28:36.932  1370  1501 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 07:28:36.932  1370  1501 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-11 07:28:36.934  1370  1501 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 07:28:36.934  1370  1501 D KeyguardModel: createShortcutInfo...
08-11 07:28:36.940  1875  6831 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,08-11 07:28:36.947   857  1048 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-11 07:28:36.948   857  1048 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-11 07:28:36.948   857  1048 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-11 07:28:36.948   857  1048 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-11 07:28:36.948   857  1048 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-11 07:28:36.948   857  1048 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1dff2d9f,  pkg=WindowManager.LayoutParams
08-11 07:28:36.948   857  1048 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-11 07:28:36.951   857  1357 D InputDispatcher: Focus entered window: Window{219a2332 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-11 07:28:36.951  1370  1370 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-11 07:28:36.952  1370  1370 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-11 07:28:36.953   857   857 I art     : Explicit concurrent mark sweep GC freed 28733(1747KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 8.668ms total 264.579ms
08-11 07:28:36.953  1370  1370 D KeyguardModel: handleShortcutListChanged...
08-11 07:28:36.953  1370  1370 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-11 07:28:36.954   857  1057 I art     : WaitForGcToComplete blocked for 105.332ms for cause Explicit
08-11 07:28:36.954  1370  1370 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-11 07:28:36.954  1370  1370 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-11 07:28:36.954  1370  1370 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-11 07:28:36.968  1370  1501 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 07:28:36.968  1370  1501 D KeyguardModel: createShortcutInfo...
,08-11 07:28:36.974  1875  1875 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 07:28:36.975  1783  1798 I art     : Background sticky concurrent mark sweep GC freed 85269(4MB) AllocSpace objects, 0(0B) LOS objects, 35% free, 9MB/14MB, paused 7.038ms total 77.325ms
08-11 07:28:36.975  1875  1875 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 07:28:36.976  1875  1875 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-11 07:28:36.986  6812  6812 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-11 07:28:36.990  6812  6812 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 07:28:36.992  1875  1875 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-11 07:28:36.994  1370  1501 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 07:28:36.994  1370  1501 D KeyguardModel: createShortcutInfo...
08-11 07:28:36.996  1370  1501 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 07:28:36.996  1370  1501 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 07:28:36.997  1370  1501 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 07:28:36.997  1370  1501 D KeyguardModel: createShortcutInfo...
08-11 07:28:36.999  1370  1501 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 07:28:36.999  1370  1501 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-11 07:28:37.001  1875  1875 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-11 07:28:37.003  1875  1875 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-11 07:28:37.004  1370  1501 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 07:28:37.004  1370  1501 D KeyguardModel: createShortcutInfo...
08-11 07:28:37.004  6812  6812 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-11 07:28:37.006  1370  1501 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 07:28:37.006  1370  1501 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-11 07:28:37.008  1370  1501 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 07:28:37.008  1370  1501 D KeyguardModel: createShortcutInfo...
08-11 07:28:37.015  1370  1370 D KeyguardModel: handleShortcutListChanged...
,08-11 07:28:37.049   857   857 D administrator: Handling package changes for user 0
,08-11 07:28:37.081   857  1638 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-11 07:28:37.082   857  1638 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6392 uid 10030
08-11 07:28:37.129  1875  1875 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-11 07:28:37.138  1875  1875 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@12ce3526 time:374542
,08-11 07:28:37.153   857  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2512be58 u0 com.lge.launcher2/.Launcher t258} time:374558
08-11 07:28:37.165  1628  1628 E b       : Unable to connect to the editor to retrieve text... will retry later
,08-11 07:28:37.191  1875  1875 I art     : Explicit concurrent mark sweep GC freed 4417(248KB) AllocSpace objects, 4(645KB) LOS objects, 39% free, 15MB/25MB, paused 1.106ms total 52.343ms
08-11 07:28:37.191  1875  1875 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-11 07:28:37.271   857   857 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-11 07:28:37.271   857   857 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-11 07:28:37.274   857   857 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-11 07:28:37.301   857  1347 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
08-11 07:28:37.301   857  1057 I art     : Explicit concurrent mark sweep GC freed 13194(1658KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 4.972ms total 345.385ms
,08-11 07:28:37.336  6812  6812 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-11 07:28:37.355  6812  6812 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,08-11 07:28:37.409  6785  6785 D AndroidRuntime: Shutting down VM
,08-11 07:28:37.432  1783  1783 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-11 07:28:37.433  1783  1783 D LCardEmulationManager: getDefaultRoute
,08-11 07:28:37.485   857   975 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-11 07:28:37.627  6812  6812 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-11 07:28:37.639   857   975 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-11 07:28:37.664   857  2170 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6841 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-11 07:28:37.709   857  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6860 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-11 07:28:37.711  1875  1875 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-11 07:28:37.803   857  1873 I ActivityManager: Killing 6212:com.lge.eula/1000 (adj 15): empty #11
,08-11 07:28:37.820  6841  6841 I AppUp4:AppBoxCP: onCreate
,08-11 07:28:37.823  6841  6841 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-11 07:28:37.831  6841  6841 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-11 07:28:37.832  6841  6841 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
08-11 07:28:37.833  6841  6841 E AndroidRuntime: FATAL EXCEPTION: main
08-11 07:28:37.833  6841  6841 E AndroidRuntime: Process: com.lge.appbox.client, PID: 6841
08-11 07:28:37.833  6841  6841 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
08-11 07:28:37.833  6841  6841 E AndroidRuntime: 	... 11 more
08-11 07:28:37.836   857  1899 W libprocessgroup: failed to open /acct/uid_1000/pid_6212/cgroup.procs: No such file or directory

```
