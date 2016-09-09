#### Test 83627337ab51778_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
09-09 13:35:29.263  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-09 13:35:29.930  6430  6430 D AndroidRuntime: 
09-09 13:35:29.930  6430  6430 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 13:35:29.934  6430  6430 D AndroidRuntime: CheckJNI is OFF
09-09 13:35:30.129  6430  6430 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-09 13:35:30.148   957  1843 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 13:35:30.233   957  1843 D ActivityManager: setTaskToReturnTo : TaskRecord{bbb9c0e #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-09 13:35:30.235   957  1843 D ActivityManager: setTaskToReturnTo : TaskRecord{bbb9c0e #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-09 13:35:30.263  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:35:30.264  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:35:30.264  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:35:30.272   957  1843 D WindowStateEx: AppWindowTokenEx init.. 
09-09 13:35:30.281   957  1057 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-09 13:35:30.290  1875  1875 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
09-09 13:35:30.294   957  1057 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-09 13:35:30.297   957  1843 D InputDispatcher: Focus left window: Window{4564473 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
09-09 13:35:30.299  6430  6430 D AndroidRuntime: Shutting down VM
09-09 13:35:30.310   957  1057 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-09 13:35:30.310   957  1057 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-09 13:35:30.333   957  1057 D SplitWindow: check instance of lgWin Window{7531ee6 u0 Starting com.test.thalitest}
09-09 13:35:30.363  2883  2883 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19962
09-09 13:35:30.374   957  2125 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6450 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-09 13:35:30.399  1875  1875 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
09-09 13:35:30.451  1875  1875 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
09-09 13:35:30.466   957  1843 I WindowStateAnimator: Starting window displayed
09-09 13:35:30.473  1935  1935 I HotwordDetector: Closing mic
09-09 13:35:30.475   957  1055 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
09-09 13:35:30.480   957  1055 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
,09-09 13:35:30.485   957  1055 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
09-09 13:35:30.485   957  1055 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
09-09 13:35:30.485   957  1055 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-09 13:35:30.486  1370  1370 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
09-09 13:35:30.486   957  1055 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@123fde89,  pkg=WindowManager.LayoutParams
09-09 13:35:30.486   957  1055 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
09-09 13:35:30.490  1370  1370 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
09-09 13:35:30.490  1370  1370 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
09-09 13:35:30.490  1370  1370 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
09-09 13:35:30.542  1935  2563 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@72e403f
09-09 13:35:30.542  1935  2563 V AudioRecord: stop()
09-09 13:35:30.542  1935  2563 D AudioRecord: AudioRecord->stop()
09-09 13:35:30.542   285   285 V AudioFlinger: RecordHandle::stop()
09-09 13:35:30.542   285   285 V AudioFlinger: RecordThread::stop
09-09 13:35:30.561   285   285 V AudioFlinger: Record stopped OK
09-09 13:35:30.564   285   285 V AudioPolicyManager: stopInput() input 17
09-09 13:35:30.566   285   285 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
09-09 13:35:30.566   285   285 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
09-09 13:35:30.566   285  1064 V AudioPolicyService: AudioCommandThread() waking up
09-09 13:35:30.566   285  1064 V AudioPolicyService: AudioCommandThread() processing release audio patch
09-09 13:35:30.567   285  1064 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
09-09 13:35:30.567   285  1064 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
09-09 13:35:30.567   285  1064 V AudioFlinger: ThreadBase::setParameters() routing=0
09-09 13:35:30.570   285  2587 D audio_hw_primary: in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
09-09 13:35:30.596  6450  6450 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-09 13:35:30.602   957  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{d4d24be type 2 when 120000 com.google.android.gms} when 120000
09-09 13:35:30.613   285  2587 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
09-09 13:35:30.613   285  2587 V audio_hw_primary: disable_audio_route: enter: usecase(7)
09-09 13:35:30.613   285  2587 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
09-09 13:35:30.613   285  2587 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-09 13:35:30.616   285  2587 V audio_hw_primary: disable_audio_route: exit
09-09 13:35:30.616   285  2587 E audio_hw_primary: disable_snd_device: enter 144
09-09 13:35:30.616   285  2587 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
09-09 13:35:30.616   285  2587 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
09-09 13:35:30.619   285  2587 V audio_hw_primary: stop_input_stream: exit: status(0)
09-09 13:35:30.619   285  2587 V audio_hw_primary: in_standby: exit:  status(0)
09-09 13:35:30.619   285  2587 V AudioFlinger: RecordThread: loop stopping
09-09 13:35:30.620   285  1064 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
09-09 13:35:30.620   285  2587 V AudioFlinger: RecordThread: loop starting
09-09 13:35:30.620   285  2587 V AudioFlinger: processConfigEvents_l() remaining events 1
09-09 13:35:30.620   285  2587 V AudioFlinger: processConfigEvents_l() DONE thread 0xb39dd000
09-09 13:35:30.620   285  2587 V AudioFlinger: RecordThread: loop stopping
09-09 13:35:30.620   285  1064 V AudioPolicyService: AudioCommandThread() going to sleep
09-09 13:35:30.620   285   285 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
09-09 13:35:30.620   285   285 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
09-09 13:35:30.620   285   285 V AudioPolicyService: AudioCommandThread() adding update audio patch list
09-09 13:35:30.620   285   285 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
09-09 13:35:30.620   285  1065 V AudioPolicyService: AudioCommandThread() waking up
09-09 13:35:30.621   285  1065 V AudioPolicyService: AudioCommandThread() processing update audio patch list
09-09 13:35:30.621   285  1065 V AudioPolicyService: AudioCommandThread() going to sleep
09-09 13:35:30.622   285   285 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
09-09 13:35:30.622   285   285 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
09-09 13:35:30.623   285  1064 V AudioPolicyService: AudioCommandThread() waking up
09-09 13:35:30.623   285  1064 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
09-09 13:35:30.623   285  1064 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 285
09-09 13:35:30.623   285  1064 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
09-09 13:35:30.623   285  1064 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
09-09 13:35:30.623   285  2587 V AudioFlinger: RecordThread: loop starting
09-09 13:35:30.624   285  2587 V AudioFlinger: processConfigEvents_l() remaining events 1
09-09 13:35:30.624   285  2587 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
09-09 13:35:30.624   285  2587 V audio_hw_primary: in_set_parameters: exit: status(0)
09-09 13:35:30.624   285  2587 V AudioFlinger: processConfigEvents_l() DONE thread 0xb39dd000
09-09 13:35:30.624   285  2587 V AudioFlinger: RecordThread: loop stopping
09-09 13:35:30.624   285  1064 V AudioPolicyService: AudioCommandThread() going to sleep
09-09 13:35:30.626  1935  2563 V AudioRecord: stop()
09-09 13:35:30.627  1935  2563 V AudioRecord: stop()
09-09 13:35:30.627  1935  2563 V AudioRecord: stop()
09-09 13:35:30.628   285  1581 V AudioFlinger: RecordHandle::stop()
09-09 13:35:30.628   285  1581 V AudioFlinger: RecordThread::stop
09-09 13:35:30.628   285  1581 V AudioPolicyManager: releaseInput() 17
09-09 13:35:30.628   285  1581 V AudioPolicyManager: closeInput(17)
09-09 13:35:30.628   285  1581 V AudioFlinger: closeInput() 17
09-09 13:35:30.628   285  1581 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-09 13:35:30.628  1935  1953 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-09 13:35:30.628   285  1581 V AudioFlinger: ThreadBase::exit
09-09 13:35:30.628   285  2587 V AudioFlinger: RecordThread: loop starting
09-09 13:35:30.628  2883  2899 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-09 13:35:30.628   285  2587 V AudioFlinger: RecordThread 0xb39dd000 exiting
09-09 13:35:30.628   285  1581 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546e420)
09-09 13:35:30.628   285  1581 D audio_hw_primary: in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
09-09 13:35:30.629   285  1581 V audio_hw_primary: in_standby: exit:  status(0)
09-09 13:35:30.629  3187  3412 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-09 13:35:30.629   285  1581 V AudioPolicyService: AudioCommandThread() adding update audio port list
09-09 13:35:30.629   285  1581 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
09-09 13:35:30.629   285  1065 V AudioPolicyService: AudioCommandThread() waking up
09-09 13:35:30.629   285  1065 V AudioPolicyService: AudioCommandThread() processing update audio port list
09-09 13:35:30.629   285  1065 V AudioPolicyService: AudioCommandThread() going to sleep
09-09 13:35:30.629  1749  1765 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-09 13:35:30.629   285  1581 V AudioPolicyManager: releaseInput() exit
09-09 13:35:30.629   285  1581 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
09-09 13:35:30.630   285  1581 V AudioFlinger: removeClient_l() pid 1935, calling pid 285
09-09 13:35:30.630   957  1843 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-09 13:35:30.629  2050  3653 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-09 13:35:30.630  1370  2342 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-09 13:35:30.631   285   285 V AudioFlinger: releasing 16 from 1935 for -1
09-09 13:35:30.631   285   285 V AudioFlinger:  decremented refcount to 0
09-09 13:35:30.631   285   285 V AudioFlinger: purging stale effects
09-09 13:35:30.633  1935  2572 I HotwordRecognitionRnr: Stopping hotword detection.
09-09 13:35:30.637  1935  2578 I HotwordRecognitionRnr: Hotword detection finished
09-09 13:35:30.733  6450  6450 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
09-09 13:35:30.792  6450  6450 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 282-290)
09-09 13:35:30.792  6450  6450 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:35:30.825  6450  6450 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {292831f4}
09-09 13:35:30.826  6450  6450 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:35:30.830  6450  6450 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 13:35:30.846  6450  6450 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 13:35:30.848  6450  6450 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:35:30.852  6450  6450 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 13:35:30.928  6450  6450 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-09 13:35:30.940  6450  6450 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:35:30.940  6450  6450 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:35:30.942  6450  6450 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:35:30.942  6450  6450 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:35:30.942  6450  6450 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:35:30.942  6450  6450 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:35:30.942  6450  6450 I Adreno-EGL: Remote Branch: 
09-09 13:35:30.942  6450  6450 I Adreno-EGL: Local Patches: 
09-09 13:35:30.942  6450  6450 I Adreno-EGL: Reconstruct Branch: 
09-09 13:35:31.084   285  1584 V AudioPolicyService: registerClient() client 0xb39b6ea0, uid 10030
09-09 13:35:31.097   957  1056 D BluetoothManagerService: Message: 20
09-09 13:35:31.097   957  1056 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24f8ad17:true
09-09 13:35:31.129  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:35:31.236  6450  6450 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:35:31.250  6450  6450 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-09 13:35:31.261  6450  6450 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-09 13:35:31.267  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:35:31.267  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:35:31.268  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
09-09 13:35:31.270  6450  6450 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-09 13:35:31.270  6450  6450 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-09 13:35:31.293  6450  6450 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-09 13:35:31.303  6450  6450 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:35:31.303  6450  6450 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:35:31.355  6450  6450 I Activity: Activity.onPostResume() called 
,09-09 13:35:31.362  6450  6502 D OpenGLRenderer: Render dirty regions requested: true
09-09 13:35:31.362  6450  6502 I OpenGLRenderer: Initialized EGL, version 1.4
09-09 13:35:31.368  6450  6502 D OpenGLRenderer: Enabling debug mode 0
,09-09 13:35:31.379  6450  6450 D Atlas   : Validating map...
,09-09 13:35:31.383   957  1379 D SplitWindow: check instance of lgWin Window{7890a07 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 13:35:31.391  6450  6489 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-09 13:35:31.431   957  2062 D InputDispatcher: Focus entered window: Window{7890a07 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 13:35:31.496   957  1783 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,09-09 13:35:31.503   957  1057 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s172ms
,09-09 13:35:31.503   957  1057 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2941e62f u0 com.test.thalitest/.MainActivity t259} time:121001
09-09 13:35:31.523  6450  6450 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@ba17b8e time:121020
,09-09 13:35:31.640  6450  6450 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6450
,09-09 13:35:31.803  6450  6450 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 13:35:32.299  6450  6505 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635604224
,09-09 13:35:32.324  6450  6505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 13:35:32.324  6450  6505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 13:35:32.324  6450  6505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 13:35:32.324  6450  6505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 13:35:32.324  6450  6505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 13:35:32.324  6450  6505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14c89543 added. We now have 1 listener(s)
,09-09 13:35:32.334   957  1783 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:35:32.338  6450  6505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,09-09 13:35:32.340  6450  6505 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-09 13:35:32.342  6450  6505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:32.342  6450  6505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:32.348  6450  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 13:35:32.348  6450  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 13:35:32.348  6450  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 13:35:32.348  6450  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
09-09 13:35:32.348  6450  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 13:35:32.348  6450  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 13:35:32.348  6450  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 13:35:32.348  6450  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 13:35:32.348  6450  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 13:35:32.348  6450  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 13:35:32.348  6450  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 13:35:32.348  6450  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 13:35:32.348  6450  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 13:35:32.348  6450  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 13:35:32.348  6450  6505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@829e43e added. We now have 1 listener(s)
09-09 13:35:32.349  6450  6505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:35:32.372  6450  6505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:35:32.373  6450  6505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-09 13:35:32.376  6450  6505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 13:35:32.376  6450  6505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 13:35:32.376  6450  6505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-09 13:35:32.390  6450  6505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:32.391   957  1843 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 13:35:32.392  6450  6505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
09-09 13:35:32.410  2050  2072 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
,09-09 13:35:32.414  6450  6505 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-09 13:35:32.414  6450  6505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:32.414  6450  6505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:32.414  6450  6505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:32.414  6450  6505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:32.414  6450  6505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:32.414  6450  6505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:32.414  6450  6505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:32.414  6450  6505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:32.415  6450  6505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 13:35:32.415  6450  6505 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:35:32.417  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:32.419  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:32.419  6450  6505 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 13:35:32.453  6450  6450 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 13:35:32.585  6450  6464 I art     : CheckpointMarkThreadRoots callback created = 0x9ea67870
,09-09 13:35:32.619  6450  6464 I art     : CheckpointMarkThreadRoots callback created = 0x9ea67840
,09-09 13:35:33.270  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:35:33.270  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:35:33.270  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-09 13:35:33.282  6450  6534 W jxcore-log: Initializing JXcore engine
09-09 13:35:33.284  6450  6534 W jxcore-log: JXcore engine is ready
,09-09 13:35:33.399  6534  6534 W Thread-779: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6398]" dev="sockfs" ino=6398 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-09 13:35:33.399  6534  6534 W Thread-779: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-09 13:35:33.399  6534  6534 W Thread-779: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6573]" dev="sockfs" ino=6573 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-09 13:35:33.399  6534  6534 W Thread-779: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
09-09 13:35:33.399  6534  6534 W Thread-779: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
09-09 13:35:33.399  6534  6534 W Thread-779: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[30996]" dev="sockfs" ino=30996 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-09 13:35:33.425  6450  6534 W jxcore-log: Starting JXcore engine
,09-09 13:35:33.570  6450  6534 W jxcore-log: Platform android
09-09 13:35:33.570  6450  6534 W jxcore-log: 
09-09 13:35:33.570  6450  6534 W jxcore-log: Process ARCH arm
09-09 13:35:33.570  6450  6534 W jxcore-log: 
,09-09 13:35:33.857  6450  6534 I jxcore-log: JXcore Cordova bridge is ready!
09-09 13:35:33.857  6450  6534 I jxcore-log: 
09-09 13:35:33.857  6450  6534 W jxcore-log: JXcore engine is started
,09-09 13:35:33.864  6450  6505 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-09 13:35:33.866  6450  6450 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-09 13:35:34.171   296   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,09-09 13:35:34.272  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:35:34.272  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:35:34.272  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-09 13:35:35.569   957  1283 V AlarmManager: RTC_WAKEUP set : Alarm{30cd0ef6 type 0 when 1473420935543 com.google.android.googlequicksearchbox} when 1473420935543
,09-09 13:35:36.275  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:35:36.275  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:35:36.275  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-09 13:35:37.277  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:35:37.277  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:35:37.277  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-09 13:35:37.605   490   490 D charger_monitor: init target 500000
,09-09 13:35:37.609  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-09 13:35:37.610  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-09 13:35:37.611  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-09 13:35:37.611  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-09 13:35:37.611  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
09-09 13:35:37.633  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-09 13:35:37.633  1802  1986 D LEDHandler: Battery Level Remaining: 100%
09-09 13:35:37.633  1802  1986 D LEDHandler: Battery Temp: 321, mChargingStatus=5, mChargingStop=false
,09-09 13:35:37.635  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-09 13:35:37.635  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-09 13:35:37.637  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 321
09-09 13:35:37.637  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-09 13:35:37.637  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 321
09-09 13:35:37.638  2050  3591 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-09 13:35:37.643   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:37.643   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:37.643   957  1312 D WifiController: battery changed pluggedType: 2
09-09 13:35:37.644  6357  6357 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-09 13:35:37.646  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-09 13:35:37.657   490   490 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-09 13:35:39.002   957  1874 I ActivityManager: Process com.google.android.apps.docs (pid 6305) has died
,09-09 13:35:39.175   296   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,09-09 13:35:39.280  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:35:39.281  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:35:39.281  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-09 13:35:41.008   957  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1c332482 type 2 when 130492 com.google.android.gms} when 130492
,09-09 13:35:41.036  1730  1730 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-09 13:35:41.216  3365  6591 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
09-09 13:35:41.216  3365  6591 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-09 13:35:41.241  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:35:41.664   957   975 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6598 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,09-09 13:35:41.758  6598  6598 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 13:35:41.758  6598  6598 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 13:35:41.813  6598  6598 I MultiDex: VM with version 2.1.0 has multidex support
09-09 13:35:41.813  6598  6598 I MultiDex: install
09-09 13:35:41.813  6598  6598 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-09 13:35:41.832   957  1843 I ActivityManager: Process com.android.contacts (pid 6148) has died
,09-09 13:35:41.875  6598  6598 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 13:35:41.949  6598  6598 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-09 13:35:41.949  6598  6598 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2eb72ed8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-09 13:35:41.950  6598  6598 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-09 13:35:41.952  6598  6598 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
09-09 13:35:41.953  6598  6598 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
09-09 13:35:41.998  6598  6598 D ChimeraCfgMgr: Reading stored module config
,09-09 13:35:42.107  6598  6612 W art     : Suspending all threads took: 9.068ms
,09-09 13:35:42.119  6598  6612 I art     : Background sticky concurrent mark sweep GC freed 20247(1017KB) AllocSpace objects, 2(32KB) LOS objects, 6% free, 10MB/11MB, paused 15.133ms total 61.389ms
,09-09 13:35:42.178  6598  6598 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
09-09 13:35:42.178  6598  6598 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-09 13:35:42.200  6598  6612 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3b0
,09-09 13:35:42.204  1730  1748 I art     : Explicit concurrent mark sweep GC freed 53621(3MB) AllocSpace objects, 18(288KB) LOS objects, 40% free, 14MB/24MB, paused 1.913ms total 161.148ms
09-09 13:35:42.232  6598  6619 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
09-09 13:35:42.234  1730  1730 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=47fb36b1-53f6-4aeb-8cca-1d5e380349e3
,09-09 13:35:42.263  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:35:42.264  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-09 13:35:42.267  6598  6612 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3a0
09-09 13:35:42.290  6598  6612 I art     : Background partial concurrent mark sweep GC freed 1347(229KB) AllocSpace objects, 1(101KB) LOS objects, 39% free, 10MB/17MB, paused 11.334ms total 89.897ms
,09-09 13:35:42.350   285  1298 D WVCdm   : Instantiating CDM.
,09-09 13:35:42.353   285  1584 I WVCdm   : CdmEngine::OpenSession
09-09 13:35:42.353   285  1584 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
09-09 13:35:42.402   285  1584 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-09 13:35:42.402   285  1584 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
09-09 13:35:42.402   285  1584 W WVCdm   : L1 library not specified. Falling Back to L3
09-09 13:35:42.438  1730  2550 W GCoreFlp: No location to return for getLastLocation()
,09-09 13:35:42.450  6598  6613 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,09-09 13:35:42.450  6598  6613 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:35:42.451  6598  6613 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:35:42.452  6598  6613 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:35:42.452   281  1043 E BandwidthController: [LG DATA] No such appUid: 10006
09-09 13:35:42.452   281  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-09 13:35:42.453   281  6624 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
09-09 13:35:42.453   281  6624 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:35:42.453   281  6624 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
09-09 13:35:42.454   281  6624 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:35:42.498   281  6624 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:35:42.499  6598  6613 I System.out: propertyValue:false
,09-09 13:35:42.513   285  1584 I WVCdm   : CdmEngine::QueryKeyControlInfo
09-09 13:35:42.514  1730  2472 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 13:35:42.515   285  1581 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-09 13:35:42.515   285  1581 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-09 13:35:42.515   285  1581 I WVCdm   : CdmEngine::GenerateKeyRequest
09-09 13:35:42.518  3365  6594 D UdcContextInitService: registered all accounts: true
,09-09 13:35:42.523   285  1581 D WVCdm   : PrepareKeyRequest: nonce=1381203537
09-09 13:35:42.562  1730  4386 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-09 13:35:42.567  6598  6613 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:35:42.568  6598  6613 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:35:42.650   957   975 I art     : Explicit concurrent mark sweep GC freed 55379(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 6.343ms total 197.618ms
,09-09 13:35:43.288  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:35:43.288  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:35:43.288  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,09-09 13:35:43.408   957   989 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-09 13:35:43.408   957   989 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-09 13:35:43.408   957   989 D sensors_hal_Time: tsOffsetIs: Apps: 132906029902; DSPS: 4453431; Offset : -3014404110
,09-09 13:35:43.514  6631  6631 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-09 13:35:43.605  6631  6631 I dex2oat : dex2oat took 91.206ms (threads: 4)
,09-09 13:35:43.620  6598  6613 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:35:43.620  6598  6613 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:35:43.620  6598  6613 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:35:43.620  6598  6613 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:35:43.620  6598  6613 I Adreno-EGL: Remote Branch: 
09-09 13:35:43.620  6598  6613 I Adreno-EGL: Local Patches: 
09-09 13:35:43.620  6598  6613 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:35:43.745  6598  6613 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:35:43.745  6598  6613 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:35:43.745  6598  6613 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:35:43.745  6598  6613 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:35:43.745  6598  6613 I Adreno-EGL: Remote Branch: 
09-09 13:35:43.745  6598  6613 I Adreno-EGL: Local Patches: 
09-09 13:35:43.745  6598  6613 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:35:43.912  6598  6613 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:35:43.912  6598  6613 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:35:43.912  6598  6613 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:35:43.912  6598  6613 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:35:43.912  6598  6613 I Adreno-EGL: Remote Branch: 
09-09 13:35:43.912  6598  6613 I Adreno-EGL: Local Patches: 
09-09 13:35:43.912  6598  6613 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:35:44.086  1730  6596 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:35:44.086  1730  6596 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:35:44.086  1730  6596 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:35:44.086  1730  6596 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:35:44.086   281  1043 E BandwidthController: [LG DATA] No such appUid: 10006
09-09 13:35:44.086   281  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-09 13:35:44.087   281  6644 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
09-09 13:35:44.087   281  6644 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:35:44.087   281  6644 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,09-09 13:35:44.087   281  6644 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,09-09 13:35:44.087   281  6644 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:35:44.088  1730  6596 I System.out: propertyValue:false
09-09 13:35:44.141  1730  6596 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:35:44.141  1730  6596 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:35:44.180   296   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,09-09 13:35:44.366  1730  4386 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:35:44.376  1730  4386 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
09-09 13:35:44.387  1730  4386 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-09 13:35:42.710+0200, stopTime=2016-09-09 13:35:44.378+0200, duration=1668ms
,09-09 13:35:44.401  1730  6648 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:35:44.401  1730  6648 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:35:44.402  1730  6648 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:35:44.402  1730  6648 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:35:44.402   281  1043 E BandwidthController: [LG DATA] No such appUid: 10006
09-09 13:35:44.402   281  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-09 13:35:44.403   281  6651 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
09-09 13:35:44.403   281  6651 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:35:44.404   281  6651 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
09-09 13:35:44.404   281  6651 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:35:44.404   281  6651 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:35:44.405  1730  6648 I System.out: propertyValue:false
09-09 13:35:44.429  4061  4076 I art     : Explicit concurrent mark sweep GC freed 1317(44KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.068ms total 30.619ms
,09-09 13:35:44.612   957  1801 I ActivityManager: Process com.lge.lockscreensettings (pid 6177) has died
,09-09 13:35:44.752   285   285 I WVCdm   : CdmEngine::CloseSession
,09-09 13:35:44.757   285   285 I WVCdm   : L3 Terminate.
09-09 13:35:44.844  1730  4386 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-09 13:35:45.008  1730  6659 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-09 13:35:45.009  1730  6657 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
09-09 13:35:45.032  1730  6659 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-09 13:35:45.033  1730  6657 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
09-09 13:35:45.062  1730  6659 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-09 13:35:45.064  1730  6657 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
09-09 13:35:45.064  1730  6657 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
09-09 13:35:45.089  1730  6657 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:35:45.132   957  1293 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:35:45.216  1730  6657 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,09-09 13:35:45.216  1730  6657 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:35:45.216  1730  6657 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:35:45.216  1730  6657 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:35:45.217   281  1043 E BandwidthController: [LG DATA] No such appUid: 10006
09-09 13:35:45.217   281  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-09 13:35:45.217   281  6660 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
09-09 13:35:45.217   281  6660 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:35:45.218   281  6660 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
09-09 13:35:45.218   281  6660 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:35:45.218   281  6660 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:35:45.220  1730  6657 I System.out: propertyValue:false
09-09 13:35:45.482   957  1293 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:35:45.715   957  1901 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:35:45.963   957   974 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:35:46.189   957  1801 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:35:46.910  1730  4386 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,09-09 13:35:48.296  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:35:48.296  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:35:48.296  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-09 13:35:49.185   296   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,09-09 13:35:49.303  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:35:49.303  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:35:49.303  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,09-09 13:35:50.301  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:35:50.301  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:35:50.301  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-09 13:35:50.372  2883  2883 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,09-09 13:35:50.382  2883  2883 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
09-09 13:35:50.456  6450  6534 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 13:35:50.456  6450  6534 I jxcore-log: 
09-09 13:35:50.459  6450  6534 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 13:35:50.459  6450  6534 I jxcore-log: 
,09-09 13:35:50.468  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:35:50.469  6450  6534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:50.469  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:50.469  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:50.469  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:50.469  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:50.469  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:50.469  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:50.469  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:50.470  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:35:50.475  6450  6534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:50.480  6450  6534 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 13:35:50.480  6450  6534 I jxcore-log: 
09-09 13:35:50.483  6450  6534 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 13:35:50.483  6450  6534 I jxcore-log: 
09-09 13:35:51.317  6450  6534 I jxcore-log: Unit Test app is loaded
09-09 13:35:51.317  6450  6534 I jxcore-log: 
,09-09 13:35:51.332  6450  6534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:35:51.332  6450  6534 I jxcore-log: 
,09-09 13:35:51.344  6450  6450 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-09 13:35:51.347  6450  6534 D executeNativeTests: Running unit tests
09-09 13:35:51.351  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:51.351  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3361cf92 added. We now have 2 listener(s)
,09-09 13:35:51.351   957  1379 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:35:51.354  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-09 13:35:51.354  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:51.354  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:51.354  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:51.354  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad00d63 added. We now have 2 listener(s)
09-09 13:35:51.354  6450  6534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:35:51.355  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:35:51.357  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:51.360  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:35:51.360  6450  6534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:51.360  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:51.360  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:51.360  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:51.360  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:51.360  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:51.360  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:51.360  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:51.361  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:35:51.362  6450  6534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:51.362  6450  6534 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:51.363  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:51.366  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:52.308  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:35:52.308  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:35:52.308  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,09-09 13:35:52.724  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-09 13:35:52.724  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-09 13:35:52.724  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-09 13:35:52.724  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-09 13:35:52.727  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-09 13:35:52.744   490   490 D charger_monitor: init target 500000
,09-09 13:35:52.787  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 320
09-09 13:35:52.787  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-09 13:35:52.787  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 320
,09-09 13:35:52.792  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-09 13:35:52.793  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-09 13:35:52.794  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-09 13:35:52.794  1802  1986 D LEDHandler: Battery Level Remaining: 100%
09-09 13:35:52.794  1802  1986 D LEDHandler: Battery Temp: 320, mChargingStatus=5, mChargingStop=false
09-09 13:35:52.799  2050  3591 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-09 13:35:52.805   490   490 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-09 13:35:52.807   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:52.807   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:52.808   957  1312 D WifiController: battery changed pluggedType: 2
09-09 13:35:52.808  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-09 13:35:52.809  6357  6357 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-09 13:35:52.847  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 320
09-09 13:35:52.847  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-09 13:35:52.847  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 320
,09-09 13:35:52.851  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-09 13:35:52.851  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-09 13:35:52.858  2050  3591 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-09 13:35:52.860  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-09 13:35:52.864  1802  1986 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-09 13:35:52.864  1802  1986 D LEDHandler: Battery Level Remaining: 100%
09-09 13:35:52.865  1802  1986 D LEDHandler: Battery Temp: 320, mChargingStatus=5, mChargingStop=false
,09-09 13:35:52.867   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:52.867   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:52.867   957  1312 D WifiController: battery changed pluggedType: 2
09-09 13:35:52.868  6357  6357 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-09 13:35:53.310  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:35:53.311  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:35:53.311  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-09 13:35:54.189   296   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,09-09 13:35:55.316  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:35:55.316  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:35:55.316  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-09 13:35:56.327  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:35:56.327  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:35:56.327  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-09 13:35:56.720   957  1059 I PowerManagerService: ALS enabled for SRE
09-09 13:35:56.720   957  1059 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26218 ms ago)
,09-09 13:35:56.780   957  1345 D qdlights: set_light_backlight: 252
,09-09 13:35:56.783   957  1345 D qdlights: set_light_backlight: 249
09-09 13:35:56.799   957  1345 D qdlights: set_light_backlight: 246
09-09 13:35:56.815   957  1345 D qdlights: set_light_backlight: 242
,09-09 13:35:56.832   957  1345 D qdlights: set_light_backlight: 239
,09-09 13:35:56.848   957  1345 D qdlights: set_light_backlight: 236
,09-09 13:35:56.865   957  1345 D qdlights: set_light_backlight: 232
,09-09 13:35:56.882   957  1345 D qdlights: set_light_backlight: 229
,09-09 13:35:56.898   957  1345 D qdlights: set_light_backlight: 226
,09-09 13:35:56.914   957  1345 D qdlights: set_light_backlight: 222
,09-09 13:35:56.932   957  1345 D qdlights: set_light_backlight: 219
,09-09 13:35:56.948   957  1345 D qdlights: set_light_backlight: 216
,09-09 13:35:56.964   957  1345 D qdlights: set_light_backlight: 212
,09-09 13:35:56.982   957  1345 D qdlights: set_light_backlight: 209
,09-09 13:35:56.998   957  1345 D qdlights: set_light_backlight: 206
,09-09 13:35:57.015   957  1345 D qdlights: set_light_backlight: 202
,09-09 13:35:57.032   957  1345 D qdlights: set_light_backlight: 199
,09-09 13:35:57.048   957  1345 D qdlights: set_light_backlight: 196
,09-09 13:35:57.065   957  1345 D qdlights: set_light_backlight: 192
,09-09 13:35:57.082   957  1345 D qdlights: set_light_backlight: 189
,09-09 13:35:57.098   957  1345 D qdlights: set_light_backlight: 186
,09-09 13:35:57.115   957  1345 D qdlights: set_light_backlight: 182
,09-09 13:35:57.132   957  1345 D qdlights: set_light_backlight: 179
,09-09 13:35:57.148   957  1345 D qdlights: set_light_backlight: 176
,09-09 13:35:57.164   957  1345 D qdlights: set_light_backlight: 172
,09-09 13:35:57.182   957  1345 D qdlights: set_light_backlight: 169
,09-09 13:35:57.198   957  1345 D qdlights: set_light_backlight: 166
,09-09 13:35:57.215   957  1345 D qdlights: set_light_backlight: 162
,09-09 13:35:57.232   957  1345 D qdlights: set_light_backlight: 159
,09-09 13:35:57.248   957  1345 D qdlights: set_light_backlight: 156
,09-09 13:35:57.264   957  1345 D qdlights: set_light_backlight: 152
,09-09 13:35:57.282   957  1345 D qdlights: set_light_backlight: 149
,09-09 13:35:57.298   957  1345 D qdlights: set_light_backlight: 146
,09-09 13:35:57.315   957  1345 D qdlights: set_light_backlight: 142
,09-09 13:35:57.332   957  1345 D qdlights: set_light_backlight: 139
,09-09 13:35:57.348   957  1345 D qdlights: set_light_backlight: 136
,09-09 13:35:57.365   957  1345 D qdlights: set_light_backlight: 132
,09-09 13:35:57.382   957  1345 D qdlights: set_light_backlight: 129
,09-09 13:35:57.398   957  1345 D qdlights: set_light_backlight: 126
,09-09 13:35:57.415   957  1345 D qdlights: set_light_backlight: 122
,09-09 13:35:57.432   957  1345 D qdlights: set_light_backlight: 119
,09-09 13:35:57.448   957  1345 D qdlights: set_light_backlight: 116
,09-09 13:35:57.466   957  1345 D qdlights: set_light_backlight: 112
,09-09 13:35:57.481   957  1345 D qdlights: set_light_backlight: 109
,09-09 13:35:57.498   957  1345 D qdlights: set_light_backlight: 106
,09-09 13:35:57.515   957  1345 D qdlights: set_light_backlight: 102
,09-09 13:35:57.532   957  1345 D qdlights: set_light_backlight: 99
,09-09 13:35:57.548   957  1345 D qdlights: set_light_backlight: 96
,09-09 13:35:57.565   957  1345 D qdlights: set_light_backlight: 92
,09-09 13:35:57.581   957  1345 D qdlights: set_light_backlight: 89
,09-09 13:35:57.598   957  1345 D qdlights: set_light_backlight: 86
,09-09 13:35:57.615   957  1345 D qdlights: set_light_backlight: 82
,09-09 13:35:57.632   957  1345 D qdlights: set_light_backlight: 79
,09-09 13:35:57.648   957  1345 D qdlights: set_light_backlight: 76
,09-09 13:35:57.665   957  1345 D qdlights: set_light_backlight: 72
,09-09 13:35:57.682   957  1345 D qdlights: set_light_backlight: 69
,09-09 13:35:57.698   957  1345 D qdlights: set_light_backlight: 66
,09-09 13:35:57.715   957  1345 D qdlights: set_light_backlight: 62
,09-09 13:35:57.732   957  1345 D qdlights: set_light_backlight: 59
,09-09 13:35:57.748   957  1345 D qdlights: set_light_backlight: 56
,09-09 13:35:57.765   957  1345 D qdlights: set_light_backlight: 52
,09-09 13:35:57.782   957  1345 D qdlights: set_light_backlight: 49
,09-09 13:35:57.798   957  1345 D qdlights: set_light_backlight: 46
,09-09 13:35:57.818   957  1345 D qdlights: set_light_backlight: 42
,09-09 13:35:57.831   957  1345 D qdlights: set_light_backlight: 39
,09-09 13:35:57.848   957  1345 D qdlights: set_light_backlight: 36
,09-09 13:35:57.864   957  1345 D qdlights: set_light_backlight: 32
,09-09 13:35:57.882   957  1345 D qdlights: set_light_backlight: 29
,09-09 13:35:57.898   957  1345 D qdlights: set_light_backlight: 26
,09-09 13:35:57.915   957  1345 D qdlights: set_light_backlight: 22
,09-09 13:35:57.932   957  1345 D qdlights: set_light_backlight: 19
,09-09 13:35:57.948   957  1345 D qdlights: set_light_backlight: 16
,09-09 13:35:57.965   957  1345 D qdlights: set_light_backlight: 12
,09-09 13:35:57.983   957  1345 D qdlights: set_light_backlight: 10
,09-09 13:35:59.195   296   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,09-09 13:36:00.001   957  1283 D PowerManagerServiceEx: acquireWakeLockInternal: lock=849849482, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=957
,09-09 13:36:00.015  2866  2866 D WeatherService: 2 : TimeTick Intent has been received, Time(hour:min:sec) 13:36:0
,09-09 13:36:00.018  2866  2866 D WeatherService: 2 : TimeTick Intent And Screen On
09-09 13:36:00.018  2866  2866 D WeatherService: 2 : SDK version : 21
09-09 13:36:00.019   957  1819 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
09-09 13:36:00.020  2866  2866 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
09-09 13:36:00.021  2866  2866 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
09-09 13:36:00.021  2866  2866 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
09-09 13:36:00.021  2866  2866 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
09-09 13:36:00.023  2866  2866 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 13:36:00.023  2866  2866 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
09-09 13:36:00.023  2866  2866 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
09-09 13:36:00.024  2866  2866 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
09-09 13:36:00.024  2866  2866 D WeatherTheme: 2 : Fixed theme : optimus
09-09 13:36:00.046  2866  2866 D WeatherReflect: 2 : Map key string is -2
,09-09 13:36:00.052  2866  2866 D lim     : 2 : time = 13:36
09-09 13:36:00.059  2866  2866 I WeatherReflect: Model Name : LG-D722
09-09 13:36:00.059  2866  2866 D WeatherTheme: 2 : Different view - status_min_formatted : 35 != 36
09-09 13:36:00.059  2866  2866 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
09-09 13:36:00.061  2866  2866 D WeatherReflect: 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,09-09 13:36:00.072  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-09 13:36:00.072  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
09-09 13:36:00.074  2866  2866 D Theme   : strTheme: com.lge.launcher2.theme.optimus
09-09 13:36:00.074  2866  2866 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
09-09 13:36:00.074  2866  2866 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
09-09 13:36:00.074  2866  2866 D Weather4x2_optimus: currentPackage=com.lge.sizechangable.weather.theme.optimus
,09-09 13:36:00.091  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,09-09 13:36:00.094  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
09-09 13:36:00.099  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
09-09 13:36:00.100  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
09-09 13:36:00.101  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
09-09 13:36:00.141  2866  2866 D Weather4x2_optimus: [[[[[[Theme package!!]]]]]] RemoteViews are created 2
09-09 13:36:00.141  2866  2866 D Weather4x2_optimus: widgetType = 1, orientation = 1
09-09 13:36:00.141  2866  2866 D Weather4x2_optimus: forecast size is 0
,09-09 13:36:00.142  2866  2866 D Theme   : strTheme: com.lge.launcher2.theme.optimus
09-09 13:36:00.142  2866  2866 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
09-09 13:36:00.142  2866  2866 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
09-09 13:36:00.142  2866  2866 D Theme   : strTheme: com.lge.launcher2.theme.optimus
09-09 13:36:00.142  2866  2866 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
09-09 13:36:00.142  2866  2866 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
09-09 13:36:00.143  2866  2866 D Theme   : strTheme: com.lge.launcher2.theme.optimus
09-09 13:36:00.143  2866  2866 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
09-09 13:36:00.143  2866  2866 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
09-09 13:36:00.143  2866  2866 I Theme_WeatherAncestor_optimus: WEATHER_CP_ACCU : 
09-09 13:36:00.143  2866  2866 I Theme_WeatherAncestor_optimus: weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
09-09 13:36:00.143  2866  2866 D Theme   : strTheme: com.lge.launcher2.theme.optimus
09-09 13:36:00.143  2866  2866 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
09-09 13:36:00.143  2866  2866 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
09-09 13:36:00.143  2866  2866 D Theme_WeatherAncestor_optimus: setTouchIntent, appWidgetId: 2
09-09 13:36:00.144  2866  2866 D Theme_WeatherAncestor_optimus: url is : null
09-09 13:36:00.145  2866  2866 D Theme   : strTheme: com.lge.launcher2.theme.optimus
09-09 13:36:00.145  2866  2866 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
09-09 13:36:00.146  2866  2866 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
09-09 13:36:00.146  2866  2866 D WeatherAncestor: 2 : update view, appWidgetId: 2
09-09 13:36:00.148  2866  2866 D WeatherService: 2 : TimeTick Intent has been processed, Time(hour:min:sec) 13:36:0
09-09 13:36:00.158   957   957 D PowerManagerServiceEx: releaseWakeLockInternal: lock=849849482 [*alarm*], flags=0x0
,09-09 13:36:00.270  1875  1875 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,09-09 13:36:00.349  1875  1875 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,09-09 13:36:01.549  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:36:01.550  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 added. We now have 3 listener(s)
,09-09 13:36:01.551   957  1801 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:01.554  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-09 13:36:01.554  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:36:01.554  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:36:01.554  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:36:01.554  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e added. We now have 3 listener(s)
09-09 13:36:01.554  6450  6534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:36:01.554  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:36:01.557  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:01.559  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.559  6450  6534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:01.559  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:01.559  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:01.559  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:01.559  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:01.559  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:01.559  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:01.559  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:01.560  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.560  6450  6534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:01.561  6450  6534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:36:01.567  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:01.571  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:01.571  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.580  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:36:01.580  6450  6534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:36:01.581  6450  6534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:36:01.581  6450  6534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:36:01.588  6450  6534 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-09 13:36:01.588  6450  6534 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 13:36:01.588  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:36:01.588  6450  6534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:36:01.589  6450  6534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:36:01.589  6450  6534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:36:01.592  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.592  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.592  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:01.592  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:36:01.592  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 removed from the list
09-09 13:36:01.592  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.592  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e removed from the list
09-09 13:36:01.592  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.592  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:01.604  6450  6534 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-09 13:36:01.604  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.604  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.604  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.604  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 not in the list
09-09 13:36:01.604  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.604  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e not in the list
09-09 13:36:01.604  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.604  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.604  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:36:01.610  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:36:01.611  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:36:01.611  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:36:01.611  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
09-09 13:36:01.611  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:36:01.611  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:36:01.611  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:36:01.611  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:36:01.611  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-09 13:36:01.611  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.611  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.611  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 not in the list
09-09 13:36:01.611  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:36:01.611  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e not in the list
09-09 13:36:01.611  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.611  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.611  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.612  6450  6534 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false,
09-09 13:36:01.613  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:01.615  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.615  6450  6534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:01.615  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:01.615  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:01.615  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
09-09 13:36:01.615  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:01.615  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:01.615  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:01.615  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:01.616  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
,09-09 13:36:01.617  6450  6534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:01.617  6450  6534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:36:01.619  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:01.620  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:01.621  6450  6534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:36:01.621  6450  6534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:36:01.621  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:36:01.621  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:01.621  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:36:01.628  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:36:01.629   957  1293 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 13:36:01.638  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478,
09-09 13:36:01.639  2050  2072 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
,09-09 13:36:01.641  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
09-09 13:36:01.646  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.648  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 13:36:01.649  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
,09-09 13:36:01.651  6450  6534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-09 13:36:01.651  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:36:01.651  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:36:01.654  6450  6534 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:36:01.654  6450  6534 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:36:01.655  6450  6534 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-09 13:36:01.656  6450  6534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:36:01.656  6450  6534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:36:01.657  6450  6534 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 13:36:01.658  6450  6534 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-09 13:36:01.658  6450  6534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:36:01.658  6450  6534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:36:01.658  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:36:01.658  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:01.658  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:36:01.661  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.661  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:36:01.662  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:01.663  6450  6534 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-09 13:36:01.663  6450  6534 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:36:01.664  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.664  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.664  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:01.664  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 not in the list
09-09 13:36:01.664  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.664  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e not in the list
09-09 13:36:01.664  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.664  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.665  6450  6534 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 13:36:01.666  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:01.669  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.669  6450  6534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:01.669  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:01.669  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:01.669  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:01.669  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:01.669  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:01.669  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:01.669  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:01.670  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.670  6450  6534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:01.670  6450  6534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:36:01.672  6450  6534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:36:01.672  6450  6534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:36:01.672  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:36:01.672  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:01.672  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:36:01.672  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:01.674  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:01.676  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.676  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:36:01.677  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:01.678  6450  6534 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:36:01.678  6450  6534 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:36:01.678  6450  6534 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-09 13:36:01.678  6450  6534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:36:01.678  6450  6534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:36:01.682  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.682  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.682  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:01.682  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 not in the list
09-09 13:36:01.682  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.682  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e not in the list
09-09 13:36:01.682  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.682  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.683  6450  6534 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 13:36:01.683  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.683  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.683  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.683  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 not in the list
09-09 13:36:01.683  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.683  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e not in the list
09-09 13:36:01.683  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.683  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.684  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.684  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:36:01.685  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.685  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.,bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.685  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.685  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 not in the list
09-09 13:36:01.685  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.685  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e not in the list
09-09 13:36:01.685  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.685  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.685  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.685  6450  6534 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 13:36:01.686  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.686  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.686  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.686  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 not in the list
09-09 13:36:01.686  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.686  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e not in the list
09-09 13:36:01.686  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.686  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.686  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.686  6450  6534 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 13:36:01.686  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.686  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.686  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.687  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 not in the list
09-09 13:36:01.687  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.687  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e not in the list
09-09 13:36:01.687  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.687  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.687  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.687  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:36:01.689  6450  6534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:36:01.689  6450  6534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:36:01.689  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:36:01.689  6450  6534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:36:01.689  6450  6534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:36:01.689  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:36:01.689  6450  6534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:36:01.689  6450  6534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:36:01.689  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.689  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.689  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.689  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 not in the list
09-09 13:36:01.689  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.690  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e not in the list
09-09 13:36:01.690  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.690  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.690  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.690  6450  6534 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:36:01.690  6450  6534 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:36:01.691  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 13:36:01.695  6450  6534 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:36:01.695  6450  6534 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 13:36:01.695  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:36:01.695  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:36:01.695  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:36:01.695  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:36:01.695  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:36:01.695  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:36:01.695  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:36:01.695  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:36:01.695  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:36:01.695  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:36:01.695  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:36:01.695  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:36:01.695  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:36:01.695  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:36:01.695  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:36:01.695  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:36:01.696  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:36:01.696  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:36:01.696  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:36:01.696  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:36:01.696  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:36:01.696  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:36:01.696  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:36:01.696  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:36:01.696  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:36:01.696  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:36:01.696  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:36:01.696  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:36:01.696  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:36:01.696  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:36:01.696  6450  6534 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 13:36:01.696  6450  6534 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:36:01.696  6450  6534 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 13:36:01.696  6450  6534 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:36:01.696  6450  6534 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:36:01.696  6450  6534 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 13:36:01.696  6450  6534 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:36:01.697  6450  6534 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:36:01.697  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 13:36:01.704  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 13:36:01.705  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 13:36:01.705  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-09 13:36:01.711  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 13:36:01.711  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 13:36:01.712  6450  6534 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 13:36:01.713  6450  6534 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:36:01.713  6450  6534 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 13:36:01.714  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.714  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.714  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.714  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 13:36:01.715  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 not in the list
09-09 13:36:01.715  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.715  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e not in the list
09-09 13:36:01.715  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.715  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.715  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.716  6450  6534 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 13:36:01.716  6450  6718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 876)
09-09 13:36:01.717  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.717  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.717  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.717  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 not in the list
09-09 13:36:01.717  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.717  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e not in the list
09-09 13:36:01.717  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.717  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.717  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.718  6450  6534 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 13:36:01.718  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.719  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.719  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.719  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 not in the list
09-09 13:36:01.719  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.719  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e not in the list
09-09 13:36:01.719  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.719  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.719  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.719  6450  6534 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 13:36:01.719  6450  6534 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 13:36:01.720  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:36:01.720  6450  6534 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 13:36:01.720  6450  6534 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:36:01.720  6450  6534 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 13:36:01.720  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:36:01.720  6450  6534 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 13:36:01.720  6450  6534 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:36:01.720  6450  6534 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:36:01.720  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:36:01.720  6450  6534 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 13:36:01.720  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.720  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.720  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.720  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 not in the list
09-09 13:36:01.720  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.720  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e not in the list
09-09 13:36:01.720  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.720  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.720  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.721  6450  6534 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 13:36:01.729  6450  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 876
09-09 13:36:01.729  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:01.729  6450  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 876)
09-09 13:36:01.729  6450  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 876)
09-09 13:36:01.731  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.732  6450  6534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:01.732  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:01.732  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:01.732  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:01.732  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:01.732  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:01.732  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:01.732  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:01.733  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.733  6450  6534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:01.734  6450  6534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:36:01.735  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:01.738  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:01.738  6450  6534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:36:01.738  6450  6534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:36:01.738  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:36:01.738  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:01.738  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:36:01.741  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.742  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:36:01.742  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:01.744  6450  6534 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:36:01.744  6450  6534 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:36:01.744  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.744  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.744  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:01.744  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 not in the list
09-09 13:36:01.744  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.744  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e not in the list
09-09 13:36:01.744  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.744  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.749  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.749  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.749  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.749  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 not in the list
09-09 13:36:01.749  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.749  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e not in the list
09-09 13:36:01.749  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.749  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.749  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.753  6450  6534 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:36:01.754  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:01.755  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:36:01.756  6450  6534 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:36:01.756  6450  6534 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:36:01.757  6450  6450 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:36:01.757  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:36:01.757  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:36:01.758  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.758  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:36:01.758  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:36:01.759   957   975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:01.759  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:36:01.760  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.760  6450  6534 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:36:01.760  6450  6450 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:36:01.760  6450  6721 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:36:01.760  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 not in the list
09-09 13:36:01.761  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.761  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:36:01.761  6450  6534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:36:01.761  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:36:01.772  2050  2073 I bt-btif : BTA_JvCreateRecordByUser
09-09 13:36:01.772  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:36:01.773  2050  2072 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.776  6450  6534 D BluetoothLeScanner: could not find callback wrapper
09-09 13:36:01.776  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:36:01.776  6450  6534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:36:01.776  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.777  2050  3655 I bt-btif : BTA_JvRfcommStartServer
09-09 13:36:01.777  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.778  2050  2073 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=87 mFd=85
09-09 13:36:01.779  6450  6534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:36:01.779  6450  6450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:36:01.780  6450  6450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:36:01.780  6450  6450 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:36:01.780  2050  3789 I bt-btif : BTA_JvDeleteRecord
09-09 13:36:01.780  2050  3789 I bt-btif : BTA_JvRfcommStopServer
09-09 13:36:01.780  6450  6721 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:36:01.780  6450  6721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:36:01.781  6450  6721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:36:01.781  6450  6450 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:36:01.782  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e not in the list
09-09 13:36:01.782  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.782  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.782  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.783  6450  6534 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 13:36:01.783  6450  6534 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 13:36:01.783  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:36:01.783  6450  6534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:36:01.783  6450  6534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:36:01.784  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.784  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.784  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.784  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 not in the list
09-09 13:36:01.784  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.784  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e not in the list
09-09 13:36:01.784  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.784  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.784  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.788   957  1379 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:01.788   957  2062 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:01.789   957  1874 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:01.790  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.790  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.790  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.790  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 not in the list
09-09 13:36:01.790  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.790  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e not in the list
09-09 13:36:01.790  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.790  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.790  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.791  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.791  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.791  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.791  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de5c389 not in the list
09-09 13:36:01.791  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.791  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e2f8e not in the list
09-09 13:36:01.791  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.791  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.791  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.793  6450  6534 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 13:36:01.793  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:36:01.793  6450  6534 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 13:36:01.793  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:36:01.793  6450  6534 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 13:36:01.793  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:36:01.795  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:36:01.795  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 13:36:01.796  6450  6534 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 13:36:01.796  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:36:01.796  6450  6534 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 13:36:01.796  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:36:01.796  6450  6534 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 13:36:01.796  6450  6534 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 13:36:01.797  6450  6534 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 13:36:01.797  6450  6534 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 13:36:01.798  6450  6534 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 13:36:01.798  6450  6534 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 13:36:01.798  6450  6534 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 13:36:01.798  6450  6534 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 13:36:01.801  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:36:01.801  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37400e54 added. We now have 3 listener(s)
,09-09 13:36:01.806   957  2125 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:01.808  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-09 13:36:01.808  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:36:01.808  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:36:01.808  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:36:01.808  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@339be1fd added. We now have 3 listener(s)
09-09 13:36:01.808  6450  6534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:36:01.808  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:36:01.810  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:01.812  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.813  6450  6534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:01.813  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:01.813  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:01.813  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:01.813  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:01.813  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:01.813  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:01.813  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:36:01.818  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.818  6450  6534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:01.819  6450  6534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:36:01.820  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.820  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.820  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.820  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:01.820  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:36:01.820  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37400e54 removed from the list
09-09 13:36:01.820  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.820  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@339be1fd removed from the list
09-09 13:36:01.820  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.820  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.822  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:36:01.822  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7f943 added. We now have 3 listener(s)
09-09 13:36:01.822   957  1379 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:01.824  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:01.826  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-09 13:36:01.826  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:36:01.826  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:36:01.826  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:36:01.826  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36b9bbc0 added. We now have 3 listener(s)
09-09 13:36:01.826  6450  6534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:36:01.829  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:36:01.831  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:01.833  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.834  6450  6534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:01.834  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:01.834  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:01.834  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:01.834  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:01.834  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:01.834  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:01.834  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:01.834  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.835  6450  6534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:01.835  6450  6534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:36:01.835  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:01.835  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:01.835  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:01.835  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:36:01.835  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7f943 removed from the list
09-09 13:36:01.835  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:01.835  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36b9bbc0 removed from the list
09-09 13:36:01.836  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:01.836  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:01.836  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:01.838  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:36:01.838  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@107b983e added. We now have 3 listener(s)
09-09 13:36:01.838   957  1873 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:01.838  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:01.842  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-09 13:36:01.842  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:36:01.842  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:36:01.842  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:36:01.842  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2af6e69f added. We now have 3 listener(s)
09-09 13:36:01.842  6450  6534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:36:01.843  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:36:01.844  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:01.846  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.847  6450  6534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:01.847  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:01.847  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:01.847  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:01.847  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:01.847  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:01.847  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:01.847  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:01.848  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:01.849  6450  6534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:01.849  6450  6534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:36:01.850  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:01.853  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:01.860   957   974 D WifiServiceImplEx: setWifiEnabled: false pid=6450, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
09-09 13:36:01.866   957   974 D WifiService: setWifiEnabled: false pid=6450, uid=10030
,09-09 13:36:01.871  6450  6718 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-09 13:36:01.872  6450  6718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 876)
,09-09 13:36:01.897   957  1306 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 13:36:01.901   957   957 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-09 13:36:01.902   957  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:36:01.908   957   957 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,09-09 13:36:01.911   957   957 D Ulp_jni : JNI:system_update. Event-4
09-09 13:36:01.933   957  1305 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:36:01.934   957  1305 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:36:01.936   957  2846 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:01.949   281  1048 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:36:01.950   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 7
,09-09 13:36:01.970  1730  4398 V NativeCrypto: Read error: ssl=0xb049c600: I/O error during system call, Connection timed out
,09-09 13:36:01.973  1730  4398 V NativeCrypto: SSL shutdown failed: ssl=0xb049c600: I/O error during system call, Broken pipe
09-09 13:36:01.978   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 10
09-09 13:36:01.979   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 7
09-09 13:36:01.982   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,09-09 13:36:01.984   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:01.986  1730  4398 E GCM     : Wifi connection closed with errorCode 20
09-09 13:36:01.990   957  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 13:36:01.991   957  1873 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
09-09 13:36:01.992  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:01.993   957  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-09 13:36:01.996  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:36:02.002  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:01.999 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:02.004  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:02.004  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:02.004  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:02.005  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:02.005  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,09-09 13:36:02.009   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:02.010   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:02.012   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:02.012   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:02.014  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:02.014  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:02.027   957   957 D WifiHS20: hidePasspointNotification off =false
,09-09 13:36:02.029   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:02.029   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:02.029   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:36:02.031   957  2845 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:02.031   957  2845 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-34ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:02.031   957  2845 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-09 13:36:02.039  1802  1818 D WifiServiceExtension: isInternetCheckAvailable return false
09-09 13:36:02.058   957  1026 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6732 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-09 13:36:02.062   957   957 D WifiHS20: hidePasspointNotification off =false
09-09 13:36:02.063   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:02.063   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:02.063   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:36:02.067   957   957 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 13:36:02.067   957  1325 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:02.067   957  1305 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:02.067   957  1305 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:02.068   957   957 D RttService: SCAN_AVAILABLE : 1
09-09 13:36:02.068   957  1326 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:02.070   957  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-09 13:36:02.072   957  1305 D LGWifiP2pService: P2pDisablingState
09-09 13:36:02.075   957  1305 D LGWifiP2pService: P2pDisablingState{ when=-4ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:02.075   957  1305 D LGWifiP2pService: p2p socket connection lost
09-09 13:36:02.075   957  1305 D LGWifiP2pService: P2pDisabledState
09-09 13:36:02.076   957  1305 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:02.077   957  1305 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:02.086  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:02.086  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:02.086 DNS addrs= 0.0.0.0, 0.0.0.0, 
,09-09 13:36:02.086  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,09-09 13:36:02.090  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:02.093  1802  1802 D WfdsService: WifiP2pState is changed : false
09-09 13:36:02.094  1802  2113 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-09 13:36:02.095  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:02.096  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:02.096  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:02.096  1802  2113 D WfdsJNI : doCommand: P2P_STOP_FIND
09-09 13:36:02.096  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:02.096  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:02.096  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:02.096  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
09-09 13:36:02.100  1802  2113 D WfdsService: Set the WFDS Monitor: false
,09-09 13:36:02.104  1802  2113 D WfdsMonitor: WFDS Monitor is stopped
09-09 13:36:02.105  1802  2836 D CtrlSupplicant: Received on exit socket, terminate
,09-09 13:36:02.105  1802  2836 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-09 13:36:02.105  1802  2113 D WfdsService: STATE : WfdsDisabledState - enter
09-09 13:36:02.105  1802  2113 D WfdsService: WFDS: Scanner is paused
09-09 13:36:02.105  1802  2113 D WfdsDiscoveryStore: Clear Discovery Method Map: ScanAlwaysMode false
09-09 13:36:02.106   281  1048 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:36:02.106   957  1313 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-09 13:36:02.107   957  1313 D DSQN    : disableDataServiceNotify
09-09 13:36:02.108   957  1313 D DSQN    : stop dsqn bin
09-09 13:36:02.109   957   957 D WifiHS20: hidePasspointNotification off =false
09-09 13:36:02.110  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:02.110  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:02.110  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:02.11 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:02.110  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:36:02.111   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:02.111   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:02.111   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:36:02.115  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:36:02.115  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:02.115 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:02.115  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:36:02.115  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:02.115  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:02.116   957   957 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-09 13:36:02.116  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:02.116  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:02.116  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:02.116  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
,09-09 13:36:02.118   957   957 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:02.118   957   957 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-09 13:36:02.118  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:02.119  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:02.119  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:02.119  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-09 13:36:02.119  2050  2072 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:02.120  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:02.120  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:02.120  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:02.120  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:36:02.120  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:02.120  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:02.120  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:02.120  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:02.121  1802  2836 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-09 13:36:02.121  1802  2836 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-09 13:36:02.121  2050  2072 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:02.122  6450  6450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:02.123  1802  2111 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-09 13:36:02.125  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:02.125  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:02.125  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:02.125  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:02.125  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:36:02.125  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:02.125  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:02.125  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:02.125  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:02.126  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:02.127  6450  6450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, ,Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:36:02.131  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:02.132  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:02.132  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:02.132  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:02.132  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:36:02.132  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:02.132  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:02.132  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:02.132  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:02.133  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:02.134   957  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-09 13:36:02.134  6450  6450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:02.134   957  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:02.135   957  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:02.141   957  1313 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-09 13:36:02.142   957  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:02.142   957  1313 D ConnectivityService: sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:02.143   957  1313 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-09 13:36:02.143   957  2845 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:02.143   957  2845 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:02.144   957  2845 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-09 13:36:02.145  1370  1740 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 13:36:02.146  3365  3696 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 13:36:02.152   957  1313 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-09 13:36:02.154   957  1313 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-09 13:36:02.156   957  2846 D DhcpStateMachine: StoppedState
09-09 13:36:02.157   957  2846 D DhcpStateMachine: StoppedState{ when=-79ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:02.163   957  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:36:02.164   957  1304 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 13:36:02.165  1837  1837 W QCNEJ   : |CORE| No family connected
09-09 13:36:02.165   957  1313 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:02.165   957  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:36:02.166   957  1313 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:02.166   957  1313 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:02.166   957  1313 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:02.166   957  1056 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:36:02.167   957  1306 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:02.167   957  1306 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:36:02.169  1837  1837 W QCNEJ   : |CORE| No family connected
09-09 13:36:02.169  1837  1837 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
09-09 13:36:02.169   957  1304 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 13:36:02.169   957  1056 D Tethering: MasterInitialState.processMessage what=3
09-09 13:36:02.170  1837  1837 I QCNEJ   : |CORE| sendDefaultNwMsg: default = -1
09-09 13:36:02.171  1749  1749 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:02.172  1749  1749 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
09-09 13:36:02.173   957  1313 D NetworkManagementService: Removing idletimer
09-09 13:36:02.179   957  1313 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:36:02.181   957  1313 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-09 13:36:02.189  1370  1370 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:36:02.193  1370  1370 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
,09-09 13:36:02.195  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:02.195  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:02.195  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:02.197  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:02.198  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:02.198  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:02.209  1370  1370 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:36:02.210  1370  1370 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
,09-09 13:36:02.212  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:02.212  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:02.212  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:02.214  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:02.214  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:02.214  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:02.215   281  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
09-09 13:36:02.215   281  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 5
09-09 13:36:02.217  2696  2696 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-09 13:36:02.217   281  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 10
09-09 13:36:02.217  2696  2696 I wpa_supplicant: monitor socket send errors count : 1
09-09 13:36:02.217  2696  2696 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1802-2\x00 that cannot receive messages
09-09 13:36:02.217   281  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 7
09-09 13:36:02.218   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:02.218   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:02.228  2696  2696 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 13:36:02.229  2696  2696 W wpa_supplicant: USIM:  scard_deinit function
,09-09 13:36:02.243   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:02.243   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:36:02.243   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:02.243   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,09-09 13:36:02.281  6450  6450 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:36:02.292   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:36:02.302   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 5
,09-09 13:36:02.303  2696  2696 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-09 13:36:02.304   957  1056 D Tethering: InitialState.processMessage what=4
09-09 13:36:02.309   957  1056 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-09 13:36:02.346  6732  6732 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:36:02.347  6732  6732 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-09 13:36:02.347  6732  6732 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:36:02.351  6732  6732 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 13:36:02.351  6732  6732 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-09 13:36:02.386   957  1873 D WifiServiceImplEx: setWifiEnabled: true pid=6450, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
,09-09 13:36:02.388   957  1873 D WifiService: setWifiEnabled: true pid=6450, uid=10030
,09-09 13:36:02.401   957   957 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:36:02.401   957  1312 D WifiController: WifiController msg { when=-1ms what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 492ms
09-09 13:36:02.401   957   957 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:36:02.401   957   957 D Ulp_jni : JNI:system_update. Event-4
09-09 13:36:02.406   957  1306 D WifiOffDelayIfNotUsed: stopMonitoring
,09-09 13:36:02.406  1802  1802 D WfdsService: Supplicant Connection state is changed : false
09-09 13:36:02.407  1802  2113 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-09 13:36:02.407  1802  2113 D WfdsService: Set the WFDS Monitor: false
09-09 13:36:02.407  1802  2113 D WfdsMonitor: WFDS Monitor is stopped
09-09 13:36:02.409  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:36:02.409  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:02.409 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:02.409  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:36:02.411   957   957 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,09-09 13:36:02.411   957  1310 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-09 13:36:02.412   957  1310 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-09 13:36:02.412  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:02.412  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:02.412  1730  2588 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:02.412  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:02.412  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
,09-09 13:36:02.415  2050  2072 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:02.415  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:02.415  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:02.415  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:02.415  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:36:02.415  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:02.415  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:02.415  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:02.415  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:02.417  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:02.418  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:02.418  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:02.418  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:02.418  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:36:02.418  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:02.418  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:02.418  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:02.418  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:02.420  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:02.420  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:02.420  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:02.420  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:02.420  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:36:02.420  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:02.420  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:02.420  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:02.420  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:02.464  6732  6732 I IndexDatabaseHelper: Using schema version: 115
09-09 13:36:02.466  6732  6732 I IndexDatabaseHelper: Index is fine
,09-09 13:36:02.572   957  1801 I ActivityManager: Process com.google.android.apps.plus (pid 6205) has died
,09-09 13:36:02.608  6732  6732 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:02.644  6732  6732 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:36:02.706   957   975 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6763 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-09 13:36:02.730   310   310 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 23.787ms
,09-09 13:36:02.755   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 24.180ms
,09-09 13:36:02.783   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 27.461ms
09-09 13:36:02.847  6763  6763 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-09 13:36:02.851  6763  6763 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:36:02.851  6763  6763 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:02.898   957  1873 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6786 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-09 13:36:02.900   957  1312 D WifiController: DEFERRED_TOGGLE handled
09-09 13:36:02.901   957  1306 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-09 13:36:02.902   957  1306 E WifiHW  : Wifi MAC Address = a0:39:f7:70:12:80
09-09 13:36:02.902   957  1306 E WifiHW  : wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
09-09 13:36:02.902   957  1306 E WifiHW  : band=b
09-09 13:36:02.902   957  1306 E WifiHW  : ": cur_etheraddr=a0:39:f7:70:12:80
09-09 13:36:02.904   281  1048 D SoftapController: Softap fwReload - Ok
09-09 13:36:02.905   957  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:02.905   957  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:02.905   281  1048 D CommandListener: Setting iface cfg
09-09 13:36:02.905   281  1048 D CommandListener: Trying to bring down wlan0
09-09 13:36:02.906   281  1048 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:36:02.908   957  1306 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-09 13:36:02.913  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:36:02.913  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:02.913 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:02.913  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,09-09 13:36:02.917  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:02.918  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:02.918  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:02.918   957   957 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-09 13:36:02.918  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-09 13:36:02.921  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:02.922  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:02.923  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:02.923   957  1306 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-09 13:36:02.950  6796  6796 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 13:36:02.998  6786  6786 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 13:36:03.011  6796  6796 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 13:36:03.011  6796  6796 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-09 13:36:03.077   957  1056 D BluetoothManagerService: Message: 20
09-09 13:36:03.077   957  1056 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e818dc6:true
,09-09 13:36:03.083  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
,09-09 13:36:03.084  2050  2072 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:03.104  6732  6732 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:03.111  6732  6732 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:03.115  6763  6763 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-09 13:36:03.115  6763  6763 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:36:03.115  6763  6763 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:03.162   957  1783 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6813 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-09 13:36:03.223  6813  6813 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 13:36:03.292   285  1581 V AudioFlinger: 2883 died, releasing its sessions
,09-09 13:36:03.292   285  1581 V AudioFlinger:  pid 1749 @ 0
09-09 13:36:03.294   285  1581 V AudioFlinger:  pid 3187 @ 1
09-09 13:36:03.294   285  1581 V AudioFlinger:  pid 3187 @ 2
,09-09 13:36:03.332   957  1631 I ActivityManager: Process com.lge.music (pid 2883) has died
,09-09 13:36:03.411   957   989 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-09 13:36:03.411   957   989 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-09 13:36:03.411   957   989 D sensors_hal_Time: tsOffsetIs: Apps: 152907050832; DSPS: 5108824; Offset : -3014390702
,09-09 13:36:03.664  6813  6848 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-09 13:36:03.665  6813  6848 I Babel_SMS: MmsConfig.loadMmsSettings
,09-09 13:36:03.667  6813  6848 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-09 13:36:03.667  6813  6848 I Babel_SMS: MmsConfig.loadFromDatabase
,09-09 13:36:03.686  6813  6848 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-09 13:36:03.686  6813  6848 I Babel_SMS: MmsConfig.loadFromResources
09-09 13:36:03.688  6813  6848 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-09 13:36:03.688  6813  6848 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-09 13:36:03.711   957  1059 I PowerManagerService: ALS enabled for SRE
09-09 13:36:03.711   957  1059 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33209 ms ago)
09-09 13:36:03.711   957  1059 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-09 13:36:03.762   957  1059 I PowerManagerService: ALS enabled for SRE
09-09 13:36:03.762   957  1059 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33260 ms ago)
,09-09 13:36:03.777   957  1059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,09-09 13:36:03.781   957  1059 I PowerManagerService: Sleeping (uid 1000)...
09-09 13:36:03.781   957  1059 D LPWGController: [updateScreenState] screen on = false
09-09 13:36:03.794   957  1059 D LPWGController: disable proximity sensor
09-09 13:36:03.794   957  1059 D LPWGController: enable proximity sensor
,09-09 13:36:03.802   957  1059 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@242a59d9] by com.android.server.power.ProximitySensorListener.enable():120
09-09 13:36:03.808   957  1059 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
,09-09 13:36:03.808   957  1059 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
09-09 13:36:03.808   957  1059 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
09-09 13:36:03.809   957  1059 I sensors_hal_Ctx: activate: handle is 48, enable
09-09 13:36:03.809   957  1059 V sensors_hal_Ctx: activate sensors is 1400000000000
09-09 13:36:03.809   957  1059 D sensors_hal_Thresh: enable: handle=48
09-09 13:36:03.809   957  1059 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
09-09 13:36:03.809   957  1059 D sensors_hal_Util: waitForResponse: timeout=1000
09-09 13:36:03.814   957   990 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
09-09 13:36:03.814   957   990 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
09-09 13:36:03.814   957  1059 D sensors_hal_Thresh: enable: Received response: 0
09-09 13:36:03.816   957  1059 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33314 ms ago)
09-09 13:36:03.832   957  1059 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:36:03.832   957  1059 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:36:03.832   957  1059 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:36:03.832   957  1059 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:36:03.832   957  1059 I Adreno-EGL: Remote Branch: 
09-09 13:36:03.832   957  1059 I Adreno-EGL: Local Patches: 
09-09 13:36:03.832   957  1059 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:36:03.841  6813  6827 I art     : CheckpointMarkThreadRoots callback created = 0xb042d890
09-09 13:36:03.859   247  1912 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1121 us)
,09-09 13:36:03.887  6813  6827 I art     : CheckpointMarkThreadRoots callback created = 0xaae47db0
,09-09 13:36:03.902  6813  6813 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
09-09 13:36:03.902  6813  6813 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
09-09 13:36:03.902  6813  6813 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
09-09 13:36:03.902  6813  6813 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
09-09 13:36:03.903  6813  6813 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
09-09 13:36:03.903  6813  6813 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
09-09 13:36:03.903  6813  6813 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
09-09 13:36:03.903  6813  6813 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
09-09 13:36:03.903  6813  6813 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
09-09 13:36:03.903  6813  6813 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
09-09 13:36:03.903  6813  6813 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
09-09 13:36:03.903  6813  6813 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
09-09 13:36:03.903  6813  6813 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
09-09 13:36:03.903  6813  6813 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
09-09 13:36:03.903  6813  6813 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
09-09 13:36:03.903  6813  6813 D SensorManager: found sensor: Motion Accel, handle=46
,09-09 13:36:03.925   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:36:03.926   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,09-09 13:36:03.934   957  1056 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 13:36:03.977  6796  6796 E wpa_supplicant: USIM:  scard_init function
09-09 13:36:03.979  6796  6796 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 13:36:03.981   281  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
,09-09 13:36:03.982   281  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 9
09-09 13:36:03.984   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:03.984   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:03.986   281  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
09-09 13:36:03.992  6813  6813 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:03.995  6813  6813 I Babel_Crash: startup - clean
,09-09 13:36:04.042   421   949 I Sensors : sns_pwr.c(273):acquiring wakelock
09-09 13:36:04.042   957   990 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,09-09 13:36:04.044   957   990 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
09-09 13:36:04.044   957   990 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
09-09 13:36:04.044   957   990 D sensors_hal_Thresh: processInd: handle 48, count=1
09-09 13:36:04.044   957   990 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
09-09 13:36:04.044   957   990 I sensors_hal_Thresh: processInd : proximity state changed - FAR
09-09 13:36:04.044   957  1032 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
09-09 13:36:04.044   957  1032 D sensors_hal_Ctx: poll: count: 256
09-09 13:36:04.044   957  1032 I sensors_hal_Ctx: poll: released wakelock sensor_ind
09-09 13:36:04.044   957  1032 D sensors_hal_Util: waitForResponse: timeout=0
09-09 13:36:04.045   957  1059 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
09-09 13:36:04.046   957  1059 I LPWGController: current mode = 1  value = 1 1
09-09 13:36:04.046  6796  6796 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-09 13:36:04.047   957  1059 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
09-09 13:36:04.058  6796  6796 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-09 13:36:04.064   957  1306 D WifiStateMachine: MAC Addr from driver = a0:39:f7:70:12:80
09-09 13:36:04.064   957  1306 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-09 13:36:04.065   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:04.066  6813  6855 I Babel   : deleted: false for 0
09-09 13:36:04.066   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:04.066   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:04.066   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:04.066   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:36:04.070  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:36:04.071  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:04.07 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:04.071  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,09-09 13:36:04.075   957   957 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-09 13:36:04.075   957   957 E WifiServerServiceExt: sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
09-09 13:36:04.075   957  1310 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-09 13:36:04.078  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:04.078  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:04.078  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:04.078  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:04.079  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-09 13:36:04.079  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:04.079  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:04.079  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:04.079  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:04.079  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:04.079  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:04.079  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:04.079  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:04.080  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:04.081  6450  6450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:04.086  2050  2072 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
,09-09 13:36:04.086  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:04.086  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:04.086  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:04.086  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:04.086  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:04.086  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:04.086  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:04.086  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:04.088  2050  2072 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:04.090  6450  6450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:04.093  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:04.094  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:04.094  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:04.094  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:04.094  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:04.094  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:04.094  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:04.094  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:04.094  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:04.096  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:04.097  6450  6450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:04.101   957  1306 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-09 13:36:04.103   957  1306 D WifiStateMachine: enableVerboseLogging : level 2
,09-09 13:36:04.109   957  1306 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:36:04.109   957  1306 D WifiNative-HAL: Setting external_sim to 1
09-09 13:36:04.110  1802  1802 D WfdsService: Supplicant Connection state is changed : true
09-09 13:36:04.110   957  1306 I WifiNative-HAL: startHal
09-09 13:36:04.110   957  1306 D wifi    : setting scan oui 0x9d82d4c0
09-09 13:36:04.110  1802  2113 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-09 13:36:04.110   957  1306 D WifiHAL : Sending mac address OUI
09-09 13:36:04.110  1802  2113 D WfdsService: Set the WFDS Monitor: true
09-09 13:36:04.110  1802  2113 D WfdsMonitor: WfdsMonitorThread create
09-09 13:36:04.110   957  1306 E WifiHAL : failed to set scanning mac OUI; result = -95
09-09 13:36:04.110   957  1306 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:36:04.110   957  1306 I WifiNative-HAL: startHal
09-09 13:36:04.110   957  1306 D wifi    : setting scan oui 0x9d82d4c0
09-09 13:36:04.110   957  1306 D WifiHAL : Sending mac address OUI
09-09 13:36:04.110  1802  2113 D WfdsMonitor: WFDS Monitor is created and started
09-09 13:36:04.110   957  1306 E WifiHAL : failed to set scanning mac OUI; result = -95
09-09 13:36:04.110  1802  2113 D WfdsService: WiFi: Supplicant connection re-established
09-09 13:36:04.112  1802  6859 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-09 13:36:04.113  1802  6859 E CtrlSupplicant: Succeed to open control connection
09-09 13:36:04.113  1802  6859 E CtrlSupplicant: Succeed to open monitor connection
09-09 13:36:04.113  1802  6859 D WfdsMonitor: Supplicant connection established
09-09 13:36:04.116  1802  2113 D WfdsService: Connected to the supplicant for wfds
09-09 13:36:04.118   957  1305 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:04.119   957   957 D WifiScanningService: SCAN_AVAILABLE : 3
09-09 13:36:04.119   957   957 D RttService: SCAN_AVAILABLE : 3
09-09 13:36:04.120   957  1325 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:04.120   957  1325 I WifiNative-HAL: startHal
09-09 13:36:04.120   957  1325 D wifi    : getting scan capabilities on interface[0] = 0x9d82d4c0
09-09 13:36:04.120   957  1325 D WifiHAL : Creating message to get scan capablities; iface = 24
09-09 13:36:04.120   957  1326 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:04.120   957  1325 D wifi    : failed to get capabilities : -95
09-09 13:36:04.120   957  1325 E WifiScanningService: could not get scan capabilities
09-09 13:36:04.121   957  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:04.121   957  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:04.122   281  1048 D CommandListener: Setting iface cfg
09-09 13:36:04.122   281  1048 D CommandListener: Trying to bring up p2p0
,09-09 13:36:04.123   957  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 13:36:04.123   957  1305 D LGWifiP2pService: P2pEnablingState
09-09 13:36:04.123   957  1305 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:04.123   957  1305 D LGWifiP2pService: P2p socket connection successful
09-09 13:36:04.123   957  1305 D LGWifiP2pService: P2pEnabledState
09-09 13:36:04.124   957  1306 I WifiServerServiceExt: set CMD_ADD_DEFAULT_PROFILE
09-09 13:36:04.125   957  1305 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-09 13:36:04.125   957  1305 D LGWifiP2pService: before postfix = G3s-1
09-09 13:36:04.125   957  1305 D WifiServerServiceExt: postfix byte check : 5
09-09 13:36:04.125   957  1305 D LGWifiP2pService: after postfix = G3s-1
09-09 13:36:04.126   957  1306 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-09 13:36:04.126   957  1305 D WifiNative-HAL: p2pGetDeviceAddress
09-09 13:36:04.127   957  1305 D WifiNative-HAL: p2pGetDeviceAddress returning a2:39:f7:70:12:80
09-09 13:36:04.127   957  1305 D LGWifiP2pService: DeviceAddress: a2:39:f7:70:12:80
09-09 13:36:04.127  6796  6796 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-09 13:36:04.128  1802  1802 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-09 13:36:04.129  1802  1802 D WfdsService: Update P2p Interface State: 3
09-09 13:36:04.129   957  1306 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-09 13:36:04.133  6732  6732 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:04.142  6732  6732 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:36:04.146  6763  6763 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 13:36:04.146  6763  6763 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:36:04.146  6763  6763 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:36:04.151   957  1059 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
09-09 13:36:04.156  6732  6732 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:36:04.165  6796  6796 E wpa_supplicant: disconnect_rssi_lvl: -100
09-09 13:36:04.165   957  1305 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-09 13:36:04.166   957  1305 D LGWifiP2pService: sending p2p connection changed broadcast
09-09 13:36:04.166   957  1305 D LGWifiP2pService: InactiveState
09-09 13:36:04.166   957  1305 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:04.166   957  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:04.166   957  1305 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:36:04.166   957  1305 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:04.167   957  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:04.167   957  1305 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:04.168   957  1306 I WifiServerServiceExt: set CMD_SET_FRAMEWORK_AUTO_JOIN 0
09-09 13:36:04.168  6796  6796 E wpa_supplicant: wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
09-09 13:36:04.169  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
09-09 13:36:04.169  1802  1802 D WfdsService: WifiP2pState is changed : true
09-09 13:36:04.170  6813  6813 W AudioCapabilities: Unsupported mime audio/x-lg-flac
09-09 13:36:04.170   957   957 E WifiServerServiceExt: No p2p device connected
09-09 13:36:04.171  1802  2113 D WfdsService: Receive the WFDS_ENABLE Method
09-09 13:36:04.171  1802  2113 D WfdsService: Set the WFDS Monitor: true
09-09 13:36:04.171  1802  2113 D WfdsService: Connected to the supplicant for wfds
09-09 13:36:04.171  1802  2113 D WfdsJNI : doCommand: WFDS_SET TRUE
09-09 13:36:04.171  6796  6796 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-09 13:36:04.171  1802  2113 D WfdsJNI : doCommand: WFDS_CLEAR_PD_INFO
09-09 13:36:04.171  6796  6796 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
09-09 13:36:04.171  1802  1802 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-09 13:36:04.172   957  1306 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
09-09 13:36:04.172  1802  2113 D WfdsJNI : wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
09-09 13:36:04.172  1802  2113 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
09-09 13:36:04.173  1802  2113 D WfdsService: selectPreferredScanChannel [6]
09-09 13:36:04.173  1802  2113 D WfdsService: STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
09-09 13:36:04.174  1802  1802 D WfdsService: isConnected: false
09-09 13:36:04.174   957  1305 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:04.174   957  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:04.175   957  1305 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:36:04.175  1802  1802 D WfdsService: GroupInfoAvailable: mGroupInfo is null
09-09 13:36:04.175   957  1305 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:04.175   957  1305 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:04.175   957  1305 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:04.176  1802  2113 W WfdsService: DefaultState - msg [9441285] is not handled
09-09 13:36:04.176  6732  6732 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:04.179  6763  6763 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:04.184  6813  6813 W AudioCapabilities: Unsupported mime audio/adpcm
09-09 13:36:04.185  6813  6813 W AudioCapabilities: Unsupported mime audio/g726
,09-09 13:36:04.191  6796  6796 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 13:36:04.193  6813  6813 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-09 13:36:04.193  6796  6796 I wpa_supplicant: [LGE_PATCH]scan interval[0] = 2 sec.
09-09 13:36:04.194  1802  6859 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
09-09 13:36:04.195   957  1305 D LGWifiP2pService: InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:04.195   957  1305 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:04.195   957  1305 D LGWifiP2pService: DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:04.199  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:04.199  6813  6813 W AudioCapabilities: Unsupported mime audio/wma-voice
09-09 13:36:04.200  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:04.199 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:04.200   296   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,09-09 13:36:04.200  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:36:04.202  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:36:04.203   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:04.203   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:04.203   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 13:36:04.206  6813  6813 W VideoCapabilities: Unsupported mime video/mjpg
09-09 13:36:04.206  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:04.206  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:04.206  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:04.206  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:04.207  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:04.207  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:04.213  6732  6732 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 13:36:04.213  6732  6732 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 13:36:04.214  6732  6732 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 13:36:04.214  6732  6732 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-09 13:36:04.218  6732  6732 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-09 13:36:04.220  6813  6813 W VideoCapabilities: Unsupported mime video/theora
09-09 13:36:04.220  6796  6796 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-09 13:36:04.224   957   957 D LocSvc_java: onReceive
09-09 13:36:04.224   957   957 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:04.224   957   957 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 13:36:04.237  6732  6732 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 13:36:04.237  6732  6732 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-09 13:36:04.237  6732  6732 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 13:36:04.237  6732  6732 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 13:36:04.237  6732  6732 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 13:36:04.237  6732  6732 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
,09-09 13:36:04.240  6732  6732 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 13:36:04.244  6813  6813 W AudioCapabilities: Unsupported mime audio/evrc
09-09 13:36:04.245  6813  6813 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 13:36:04.246  6813  6813 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:36:04.252  6813  6813 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-09 13:36:04.253  6813  6813 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 13:36:04.254  6813  6813 W AudioCapabilities: Unsupported mime audio/evrc
09-09 13:36:04.270  6813  6813 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-09 13:36:04.291   957  1801 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6863 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-09 13:36:04.305  6813  6813 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 13:36:04.313  6813  6813 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:36:04.317  6813  6813 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:36:04.322  6813  6813 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:36:04.328  6813  6813 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:36:04.339  6813  6813 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:36:04.344  6813  6813 I vclib   : onServiceConnected
,09-09 13:36:04.344  6813  6813 W Babel   : Attempted to change video mute state without an active call.
09-09 13:36:04.355  6813  6813 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,09-09 13:36:04.416   957  1345 D qdlights: set_light_backlight: 0
,09-09 13:36:04.418  6863  6863 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:36:04.419  6863  6863 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:36:04.422  6450  6534 D BluetoothAdapter: enable(): BT is already enabled..!
09-09 13:36:04.423  6863  6863 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:36:04.429  6863  6863 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:36:04.429   957  1059 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
09-09 13:36:04.429   957  1059 I sensors_hal_Ctx: activate: handle is 46, disable
09-09 13:36:04.429   957  1059 V sensors_hal_Ctx: activate sensors is 1000000000000
09-09 13:36:04.429   957  1059 D sensors_hal_LP2: enable: handle=46
09-09 13:36:04.429   957  1059 D sensors_hal_LP2: enable: Disabling sensor handle=46
09-09 13:36:04.429   957  1059 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,09-09 13:36:04.435   957  1057 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
09-09 13:36:04.435   957   957 V ActivityManager: Display changed displayId=0
09-09 13:36:04.435   247   247 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
09-09 13:36:04.435   247   247 D qdhwcomposer: hwc_blank: Blanking display: 0
09-09 13:36:04.440  6732  6732 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:36:04.463   957  1015 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
09-09 13:36:04.463   957  1015 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
09-09 13:36:04.466  6732  6732 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:04.470  6763  6763 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-09 13:36:04.471  6763  6763 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:36:04.471  6763  6763 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:36:04.484  6863  6883 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,09-09 13:36:04.486  6863  6883 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:36:04.490  6732  6732 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:36:04.495  6863  6882 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:36:04.497  6732  6732 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:36:04.499  1749  1749 D DSDPConnection: Display #0 changed.
09-09 13:36:04.501  6763  6763 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:04.582   957   974 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@336d3a81)
,09-09 13:36:04.586   957  1313 D ConnectivityService: dumpNetworkRequest
09-09 13:36:04.586   957  1313 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:04.587   957  1313 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:04.589   957  1313 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:04.612   957  1819 I ActivityManager: Process com.google.android.gms (pid 3365) has died
,09-09 13:36:04.617   247   247 D qdhwcomposer: hwc_blank: Done blanking display: 0
,09-09 13:36:04.618   247   671 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
09-09 13:36:04.618   957  1345 D SurfaceControl: Excessive delay in setPowerMode(): 184ms
09-09 13:36:04.619   957  1345 I QCOM PowerHAL: Got set_interactive hint
,09-09 13:36:04.629  1370  3552 D KeyguardViewMediator: onScreenTurnedOff(3)
09-09 13:36:04.640  1327  1344 D SmartCoverViewMediator: onScreenTurnedOff(3)
,09-09 13:36:04.646  1370  3552 D KeyguardViewMediator: notifyScreenOffLocked
09-09 13:36:04.649  1327  1344 D SmartCoverViewMediator: notifyScreenOffLocked
09-09 13:36:04.650  1327  1327 D SmartCoverViewMediator: handleNotifyScreenOFF
09-09 13:36:04.661   957   974 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6887 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:04.675  6786  6786 V LGMDMManager: Create singleton instance
,09-09 13:36:04.702  6450  6450 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-09 13:36:04.704  6450  6450 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
09-09 13:36:04.708  6450  6450 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2c64caea Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@287a53b5, 16908290=android.view.AbsSavedState$1@287a53b5}, android:focusedViewId=100}]}]
09-09 13:36:04.708  6450  6450 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-09 13:36:04.711  6450  6450 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 13:36:04.711  6450  6450 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-09 13:36:04.713  1370  3552 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
09-09 13:36:04.713  1370  1370 D KeyguardViewMediator: handleNotifyScreenOff
09-09 13:36:04.722   957  1306 E WifiNative-wlan0: doBoolean: disable
09-09 13:36:04.723   957   957 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
,09-09 13:36:04.728   285  1298 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 957
09-09 13:36:04.729   285  1298 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-09 13:36:04.729   285  1298 V voice   : voice_set_parameters: enter: screen_state=on
09-09 13:36:04.731   285  1298 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
09-09 13:36:04.731   285  1298 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-09 13:36:04.731   285  1298 V voice   : voice_set_parameters: exit with code(0)
09-09 13:36:04.731   285  1298 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
09-09 13:36:04.731   285  1298 V msm8974_platform: platform_set_parameters: enter: screen_state=on
09-09 13:36:04.731   285  1298 V msm8974_platform: platform_set_parameters: exit with code(0)
09-09 13:36:04.731   285  1298 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-09 13:36:04.731   285  1298 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
09-09 13:36:04.731   285  1298 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
09-09 13:36:04.731   285  1298 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-09 13:36:04.732  1370  1370 D ScreenTurnOffBySensor: unregisterProximitySensor
09-09 13:36:04.736  1370  1370 D StatusBarWindowView: onScreenTurnedOff why = 3
,09-09 13:36:04.739  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
09-09 13:36:04.740   957  1306 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
09-09 13:36:04.743   957  1025 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
09-09 13:36:04.745  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
09-09 13:36:04.748  1837  1837 I QCNEJ   : |CORE| sendScreenState: state:true
,09-09 13:36:04.757  1802  1986 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
09-09 13:36:04.760  1802  1986 D LEDService: stopPatternFlashing()
,09-09 13:36:04.762  1802  1986 D qdlights: set_light_notifications: 0,0,0,0,3
,09-09 13:36:04.763  1802  1986 I LEDService: getCurrentHighestLGLedRecord : size = 1
09-09 13:36:04.763  1802  1986 D qdlights: set_light_notifications: 0,0,0,0,3
09-09 13:36:04.765  1802  1986 I LEDService: updateLightsLocked : turn off led
09-09 13:36:04.765  1802  1986 D qdlights: set_light_notifications: 0,0,0,0,3
09-09 13:36:04.767  1802  1986 D LEDHandler: RESTART MSG
09-09 13:36:04.784  6786  6786 I AudioManager: getMode name:com.lge.qremote
,09-09 13:36:04.795  6732  6732 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:36:04.801  6732  6732 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:04.803  6763  6763 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:04.804   957  1843 D SplitWindow: check instance of lgWin Window{1adb03 u0 SearchPanel}
09-09 13:36:04.811  1802  1802 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,09-09 13:36:04.813  6887  6887 D UEI.SmartControl: Quickset Services start...
09-09 13:36:04.815  1802  1802 D Cliptray Service: lockStatus = 0
09-09 13:36:04.817  6863  6863 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:36:04.817  6863  6863 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:36:04.818  1784  1784 D LNfcService: action : android.intent.action.SCREEN_ON
09-09 13:36:04.821  6863  6863 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:36:04.824  6863  6863 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,09-09 13:36:04.825  6887  6887 I UEI.SmartControl: Manufacture = LGE
09-09 13:36:04.828  6887  6887 D UEI.SmartControl: File observer start...
09-09 13:36:04.829  6887  6887 E UEI.SmartControl: IR Port is disabled: false
09-09 13:36:04.829  6887  6887 D UEI.SmartControl: Starting file observer...
09-09 13:36:04.829  6887  6887 D UEI.SmartControl: Extracting JNI libs...
09-09 13:36:04.832  6887  6887 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-09 13:36:04.833  1784  6904 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
09-09 13:36:04.833  1784  6904 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
09-09 13:36:04.833  1784  6904 D LNfcService: isRequireNfcCRouting() return true
09-09 13:36:04.833  1784  6904 D LNfcService: isHCERoutingtoHost() return : true
09-09 13:36:04.833  1784  6904 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
09-09 13:36:04.833  1784  6904 D NfcService: mEnableLPD: true
09-09 13:36:04.833  1784  6904 D NfcService: mEnableReader: false
09-09 13:36:04.833  1784  6904 D NfcService: mEnableHostRouting: true
09-09 13:36:04.833  1784  6904 D NfcService: newParams.techmask= mTechMask: default
09-09 13:36:04.833  1784  6904 D NfcService: mEnableLPD: true
09-09 13:36:04.833  1784  6904 D NfcService: mEnableReader: false
09-09 13:36:04.833  1784  6904 D NfcService: mEnableHostRouting: true
09-09 13:36:04.833  1784  6904 D NfcService: screenState= 3
09-09 13:36:04.833  1784  6904 D NfcService: Discovery configuration equal, not updating.
09-09 13:36:04.834   957   975 D InputDispatcher: Window went away: Window{3d7e9ca2 u0 SearchPanel}
09-09 13:36:04.835  6863  6906 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:36:04.837  1370  1370 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
,09-09 13:36:04.839  6863  6908 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,09-09 13:36:04.839  6863  6908 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:36:04.856  1370  1370 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,09-09 13:36:04.860   957   957 D Ulp_jni : JNI:system_update. Event-0
09-09 13:36:04.864  6357  6357 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 13:36:04.864  6357  6357 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-09 13:36:04.877  1749  1749 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,09-09 13:36:04.885  6357  6357 V [BNRBootReceiver]: Boot Receiver Return
,09-09 13:36:04.890  6732  6732 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:36:04.894  6732  6732 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:04.906  2866  2866 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:36:4
,09-09 13:36:04.908  2866  2866 D WeatherService: 2 : ACTION screen on
09-09 13:36:04.909  6732  6732 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-09 13:36:04.911  2866  2866 D WeatherService: 2 : shouldTimeTickRegistered : false
09-09 13:36:04.911  6732  6732 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-09 13:36:04.920  2866  2866 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 13:36:04.920  2866  2866 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:36:4
,09-09 13:36:04.928  4176  4176 D AppCleanupService: android.intent.action.SCREEN_ON
09-09 13:36:04.941   957  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{234e34fe type 2 when 154425 com.google.android.gms} when 154425
,09-09 13:36:04.945   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:36:04.945   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:04.945   957   957 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
09-09 13:36:04.951   285  1581 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 957
09-09 13:36:04.952   285  1581 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-09 13:36:04.952   285  1581 V voice   : voice_set_parameters: enter: screen_state=off
09-09 13:36:04.952   285  1581 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
09-09 13:36:04.952  1730  6910 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:04.952   285  1581 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-09 13:36:04.952   285  1581 V voice   : voice_set_parameters: exit with code(0)
09-09 13:36:04.952   285  1581 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
09-09 13:36:04.952   285  1581 V msm8974_platform: platform_set_parameters: enter: screen_state=off
09-09 13:36:04.952   285  1581 V msm8974_platform: platform_set_parameters: exit with code(0)
09-09 13:36:04.952  1730  6910 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:04.952   285  1581 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-09 13:36:04.952   285  1581 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
09-09 13:36:04.952   285  1581 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-09 13:36:04.953  1730  6910 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:04.953  1730  6910 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,09-09 13:36:04.954   281  1043 E BandwidthController: [LG DATA] No such appUid: 10006
09-09 13:36:04.954   281  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-09 13:36:04.954   281  6911 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
09-09 13:36:04.954   281  6911 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:04.955   281  6911 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
09-09 13:36:04.956   957  1054 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-09 13:36:04.961  1730  6912 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:04.962  1730  6912 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:04.962  1730  6912 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:04.963  1730  6912 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:04.963   281  1043 E BandwidthController: [LG DATA] No such appUid: 10006
09-09 13:36:04.963   281  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-09 13:36:04.963   281  6913 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
09-09 13:36:04.963   281  6913 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:04.964   281  6913 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
09-09 13:36:04.964   957  1054 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-09 13:36:04.967   957  1306 E WifiNative-wlan0: doBoolean: disable
09-09 13:36:04.969   957  1312 D WifiController: CMD_SCREEN_OFF 
09-09 13:36:04.969   957  1312 D WifiController: shouldWifiStayAwake TRUE
,09-09 13:36:04.971   957  1025 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
09-09 13:36:04.972  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
09-09 13:36:04.998  1837  1837 I QCNEJ   : |CORE| sendScreenState: state:false
,09-09 13:36:05.001  1802  1986 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
09-09 13:36:05.001  1802  1986 D LEDService: stopPatternFlashing()
09-09 13:36:05.001  1802  1986 D qdlights: set_light_notifications: 0,0,0,0,3
09-09 13:36:05.003  1802  1986 I LEDService: getCurrentHighestLGLedRecord : size = 1
09-09 13:36:05.003  1802  1986 D qdlights: set_light_notifications: 0,0,0,0,3
09-09 13:36:05.003  1802  1802 D VolumeVibrator: clear
09-09 13:36:05.005  1802  1986 I LEDService: updateLightsLocked : turn on led
09-09 13:36:05.005  1802  1986 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
09-09 13:36:05.006  1802  1986 E LEDService: Can't handle this request of patternId:0
09-09 13:36:05.006  1802  1986 D LEDHandler: RESTART MSG
09-09 13:36:05.009  1802  1802 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
09-09 13:36:05.010  1784  1784 D LNfcService: action : android.intent.action.SCREEN_OFF
,09-09 13:36:05.013  1784  2177 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
09-09 13:36:05.036  1875  1875 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,09-09 13:36:05.049  1749  1749 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,09-09 13:36:05.055  2866  2866 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:36:5
09-09 13:36:05.055  2866  2866 D WeatherService: 2 : ACTION screen off
09-09 13:36:05.057  2866  2866 D WeatherService: 2 : TimeTick Receiver Unregister
09-09 13:36:05.058  2866  2866 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:36:5
09-09 13:36:05.060  4176  4176 D AppCleanupService: android.intent.action.SCREEN_OFF
09-09 13:36:05.063  4176  6915 D AppCleanupService: AppUsageStatsSaveTask
,09-09 13:36:05.072   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.072   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.072   957   957 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
09-09 13:36:05.110  1784  2674 E NxpNfcJni: getReconnectState = 0x0
,09-09 13:36:05.113  1784  2177 D LCardEmulationManager: getHceAppCount hostAppNum : 0
09-09 13:36:05.113  1784  2177 D LCardEmulationManager: getDefaultRoute
09-09 13:36:05.113  1784  2177 D LNfcService: isRequireNfcCRouting() return true
09-09 13:36:05.113  1784  2177 D LNfcService: isHCERoutingtoHost() return : true
09-09 13:36:05.113  1784  2177 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
09-09 13:36:05.113  1784  2177 D NfcService: mEnableLPD: true
09-09 13:36:05.113  1784  2177 D NfcService: mEnableReader: false
09-09 13:36:05.113  1784  2177 D NfcService: mEnableHostRouting: true
09-09 13:36:05.113  1784  2177 D NfcService: newParams.techmask= mTechMask: 0
09-09 13:36:05.113  1784  2177 D NfcService: mEnableLPD: true
09-09 13:36:05.113  1784  2177 D NfcService: mEnableReader: false
09-09 13:36:05.113  1784  2177 D NfcService: mEnableHostRouting: true
09-09 13:36:05.114  1784  2177 D NfcService: screenState= 1
09-09 13:36:05.162   957  1293 I ActivityManager: Process com.google.android.gms.unstable (pid 6598) has died
,09-09 13:36:05.166   957  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:05.167   957  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:05.169  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
09-09 13:36:05.170   957  1025 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:05.172   281  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 6
09-09 13:36:05.173   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:05.173   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:05.174  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:05.176  1784  2674 E NxpNfcJni: getReconnectState = 0x0
,09-09 13:36:05.176   957   957 D LocSvc_java: onReceive
09-09 13:36:05.176   957   957 D LocSvc_java: got connectivity action
09-09 13:36:05.178  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:05.179  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:05.188   957   957 D LocSvc_java: broadcast - no network connections
09-09 13:36:05.188   957   957 D LocSvc_java: Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
09-09 13:36:05.188   957   957 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 13:36:05.189   957   957 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:36:05.189   957   957 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:36:05.189   957   957 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-09 13:36:05.219   957  1026 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6916 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:36:05.221   957   957 D LocSvc_java: onReceive
09-09 13:36:05.221   957   957 D LocSvc_java: got connectivity action
09-09 13:36:05.222   957   957 D LocSvc_java: broadcast - no network connections
09-09 13:36:05.222   957   957 D LocSvc_java: Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
09-09 13:36:05.222   957   957 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 13:36:05.222   957   957 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:36:05.222   957   957 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:36:05.222   957   957 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:36:05.223   957  1025 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:05.224   957  1025 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:05.226   957  1025 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 13:36:05.234  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
09-09 13:36:05.236  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:05.237  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:05.238  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:05.326  6796  6796 I wpa_supplicant: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2437 MHz)
,09-09 13:36:05.346  6887  6887 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,09-09 13:36:05.347  6887  6887 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-09 13:36:05.347  6887  6887 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-09 13:36:05.354   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:36:05.360   957   957 D LocSvc_java: onReceive
,09-09 13:36:05.363  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:05.364  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:05.364  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:05.364 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:05.364  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:36:05.365   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.365   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.365   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 13:36:05.366  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:05.367  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:05.367  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:05.367  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:05.367  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:05.367  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:05.367  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:05.368  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:05.368   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.368   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.368   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 13:36:05.370  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:05.37 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:05.370  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-09 13:36:05.371  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:05.371  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:05.371  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivi,tyIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:05.371   957   957 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:05.371   957   957 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-09 13:36:05.371  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:05.371  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:05.371  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:05.391  6887  6887 I UEI.SmartControl: --- Selecting new region: 2
09-09 13:36:05.391  6887  6887 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
,09-09 13:36:05.395  6887  6887 D UEI.SmartControl: Platform has CIR...
09-09 13:36:05.396  6887  6887 D UEI.SmartControl: NO CIR support, need to check package...
09-09 13:36:05.397  6887  6887 I UEI.SmartControl: Model: LG-D722 uses JNI
09-09 13:36:05.399  6887  6887 D UEI.SmartControl: QS Service created
09-09 13:36:05.421  6887  6887 E UEI.SmartControl: QS start get config
,09-09 13:36:05.423  6796  6796 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-09 13:36:05.424   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:36:05.424   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:36:05.424   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:36:05.426   957   957 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:05.426   957   957 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-09 13:36:05.431  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:05.431  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:05.431  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:05.431 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:05.431  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-09 13:36:05.432   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.432   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.432   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 13:36:05.433  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:05.434   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.434   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.434   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-09 13:36:05.434  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:05.434 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:05.434  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:05.434  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-09 13:36:05.435  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:05.435  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:05.435  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:05.435  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:05.435  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:05.435  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:36:05.436   957   957 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:05.436   957   957 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,09-09 13:36:05.439  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:05.439  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:05.439  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:05.439  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:05.440  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:05.440  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:05.448  6796  6796 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:36:05.448  6796  6796 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 13:36:05.449   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:36:05.450   957   957 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:05.450   957   957 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,09-09 13:36:05.457   957  1306 I WifiServiceExtension: setVHTCapabilityType  : false
09-09 13:36:05.480  6887  6887 D UEI.SmartControl: Loading JNI Libs...
,09-09 13:36:05.483   957  1306 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,09-09 13:36:05.484  6887  6887 D UEI.SmartControl:  configuring local db...
09-09 13:36:05.484   957  1306 I WifiServerServiceExt: setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
09-09 13:36:05.485   957  1306 I WifiServiceExtension: setSecurityType  : 2
09-09 13:36:05.485  6916  6916 I MusicStore: Database version: 120
09-09 13:36:05.542   421   439 I Sensors : sns_pwr.c(301):releasing wakelock
,09-09 13:36:05.623   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:05.624   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-09 13:36:05.624   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:36:05.631  6916  6916 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-09 13:36:05.650   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.650   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.650   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 13:36:05.650   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.650   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.650   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-09 13:36:05.653  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:36:05.654  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:05.655  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:05.655 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:05.655  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-09 13:36:05.655  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:05.656  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:05.656  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:05.656  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:05.656  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:05.656 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:05.656  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:05.656  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-09 13:36:05.656  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:05.656  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:05.656  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:05.657   957  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-09 13:36:05.659  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:05.659  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:05.660  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:05.660  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:05.660   957  1313 D ConnectivityService: Got NetworkAgent Messenger
09-09 13:36:05.660  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:05.660  1370  1370 I [Syste,mUI]QuickSettingsHandler: Remote
09-09 13:36:05.660   957  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 13:36:05.660   957  1313 D ConnectivityService: NetworkAgent connected
09-09 13:36:05.661  1802  2121 D WifiServiceExtension: isInternetCheckAvailable return false
09-09 13:36:05.661   957  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:36:05.685   957  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:36:05.699   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 9
,09-09 13:36:05.699   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,09-09 13:36:05.699   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:05.700   957  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:05.700   957  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:05.700   281  1048 D CommandListener: Setting iface cfg
09-09 13:36:05.707   957  6941 D DhcpStateMachine: StoppedState
09-09 13:36:05.707   957  1306 E WifiStateMachine: Start Dhcp Watchdog 2
09-09 13:36:05.707   957  6941 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:05.708   957  6941 D DhcpStateMachine: WaitBeforeStartState
09-09 13:36:05.714   957  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,09-09 13:36:05.736  6887  6887 D UEI.SmartControl:  ---- Has DB8: true
,09-09 13:36:05.743  6887  6887 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 13:36:05.744  6887  6887 D UEI.SmartControl: QS version = v2.7.11.1_RC1
09-09 13:36:05.745  6887  6887 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
09-09 13:36:05.751  6887  6887 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
,09-09 13:36:05.779  6887  6887 W irrc_jni: IRRCPlayer_nativeInit ++ 
09-09 13:36:05.779  6887  6887 D irrcClient: IrrcClient ++ 
,09-09 13:36:05.779  6887  6887 D irrcClient: getIrrcService ++ 
09-09 13:36:05.779  6887  6887 D irrcClient: getIrrcService -- 
09-09 13:36:05.779  6887  6887 D irrcClient: IrrcClient -- 
09-09 13:36:05.779  6887  6887 W irrc_jni: IRRCPlayer_nativeInit -- 
09-09 13:36:05.790   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:05.790   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-09 13:36:05.790   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:05.791  6916  6916 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-09 13:36:05.793   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:05.793   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,09-09 13:36:05.793   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:05.793  6916  6916 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-09 13:36:05.796  6887  6943 I UEI.SmartControl: Device manager: loading config....
09-09 13:36:05.796  6887  6887 D UEI.SmartControl: Services init done
09-09 13:36:05.800  6887  6887 D UEI.SmartControl: QS Service init finished
09-09 13:36:05.801  6887  6887 D UEI.SmartControl: QS Service version name: 0.1.73
09-09 13:36:05.802  6887  6887 D UEI.SmartControl: QS Service version code: 1073
09-09 13:36:05.803  6887  6887 D UEI.SmartControl: Service requested: Control
09-09 13:36:05.803   957  1306 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-09 13:36:05.803   957  1306 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 13:36:05.804   957  1305 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@35290736 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:05.804   957  1305 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@35290736 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:05.804   957  6941 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:05.804   957  6941 D DhcpStateMachine: DHCP Start wake lock is acquired.
,09-09 13:36:05.806  6887  6943 D UEI.SmartControl: Config is loaded...
09-09 13:36:05.807   957  1306 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 13:36:05.809   281  1048 D CommandListener: Setting iface cfg
09-09 13:36:05.809   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
09-09 13:36:05.810   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:05.810   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:05.811   281  1048 D CommandListener: Trying to bring up wlan0
09-09 13:36:05.813   957  1306 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-09 13:36:05.814   957   957 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:05.814   957   957 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 13:36:05.815   957   957 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:05.815   957   957 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 13:36:05.816   957  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 13:36:05.817   957  1305 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:36:05.817   957  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:05.828   957  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 13:36:05.828   957  1306 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 13:36:05.829   957  1313 D ConnectivityService: ignoring duplicate network state non-change
,09-09 13:36:05.831  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:05.833   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.833   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.833   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 13:36:05.833  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:05.834  1802  1818 D WifiServiceExtension: isInternetCheckAvailable return false
,09-09 13:36:05.835  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-127 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:05.835 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:36:05.835  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.109 ipV6Addr=
09-09 13:36:05.837  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:05.837  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:05.837  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:05.837  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:05.837  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:05.837  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:05.840  1802  1817 D WifiServiceExtension: isInternetCheckAvailable return false
09-09 13:36:05.840  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:05.840   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.840   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.841   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 13:36:05.841   957  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 13:36:05.842   957  1313 D ConnectivityService: Adding iface wlan0 to network 101
09-09 13:36:05.843  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:05.843  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:05.843  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:05.844  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:05.844  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:05.844  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:05.845  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 0
09-09 13:36:05.846  6887  6942 D UEI.SmartControl:  ----- QS SDK is ready!!!
09-09 13:36:05.847   957   957 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 13:36:05.847   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.847   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.847   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 13:36:05.847  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:05.848   957   957 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 13:36:05.848  6887  6942 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 13:36:05.848  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-127 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:05.848 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:36:05.849  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.109 ipV6Addr=
09-09 13:36:05.849  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:05.850  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-127 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:05.85 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:36:05.851  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.109 ipV6Addr=
09-09 13:36:05.851   957  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 13:36:05.851  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,09-09 13:36:05.853   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.853   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:05.853   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 13:36:05.853  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-127 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:05.853 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:36:05.854  6887  6887 D UEI.SmartControl: Request IControl service: devices are loaded...
09-09 13:36:05.854  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.109 ipV6Addr=
09-09 13:36:05.857  6887  6887 D UEI.SmartControl: Internal service binding...
09-09 13:36:05.857  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:36:05.858  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:05.859  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_1_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:05.864  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
,09-09 13:36:05.865  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:05.865  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:05.865  6887  6903 D UEI.SmartControl: -----IControl: 11
09-09 13:36:05.866  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 0
09-09 13:36:05.866  6887  6903 D UEI.SmartControl: Caller: com.lge.qremote
09-09 13:36:05.867  6887  6903 D UEI.SmartControl: ------------ IControl registerCallback...
09-09 13:36:05.868  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:36:05.868  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:05.868  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_1_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:05.868  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:05.868  6887  6903 I UEI.SmartControl: Registering callback...
09-09 13:36:05.868  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:05.868  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:05.870  6887  6902 D UEI.SmartControl: -----IControl: 19
09-09 13:36:05.871  6887  6902 D UEI.SmartControl: Caller: com.lge.qremote
09-09 13:36:05.871  6887  6902 I UEI.SmartControl: Registering Services Ready callback...
09-09 13:36:05.872  6887  6902 I UEI.SmartControl: Notify client services are ready...
09-09 13:36:05.876  6887  6903 D UEI.SmartControl: -----IControl: 8
,09-09 13:36:05.877  6887  6903 D UEI.SmartControl: Caller: com.lge.qremote
09-09 13:36:05.909   957  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 13:36:05.910   957  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-09 13:36:05.910   281  1048 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:36:05.910   281  1048 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:05.911   281  1048 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:36:05.911   281  1048 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:36:05.912   957  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-09 13:36:05.913   281  1048 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:36:05.913   281  1048 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:05.918   281  1048 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:36:05.918   281  1048 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:05.919   281  1048 E Netd    : netlink response contains error (File exists)
09-09 13:36:05.919   957  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-09 13:36:05.920   281  1048 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:36:05.920   281  1048 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:05.920   957  1313 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-09 13:36:05.920   957  1313 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-09 13:36:05.921   957  1313 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-09 13:36:05.921   957  1313 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,09-09 13:36:05.921   957  1313 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:05.921   281  1048 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
09-09 13:36:05.921   281  1048 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:05.925   957  1313 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 13:36:05.925   957  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 13:36:05.925   957  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-09 13:36:05.925   957  1313 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-09 13:36:05.925   957  1313 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:36:05.926   957  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:05.926   957  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:36:05.926   957  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:05.926   957  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-09 13:36:05.926   957  1313 D ConnectivityService: currentScore = 0, newScore = 20
09-09 13:36:05.926   957  1313 D ConnectivityService:    accepting network in place of null
09-09 13:36:05.926   957  1313 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:05.926   957  1306 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:05.927   957  1306 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:36:05.927  1749  1749 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:05.927  1749  1749 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
09-09 13:36:05.927   957  1313 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 13:36:05.927   957  1313 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 13:36:05.928   957  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:36:05.928   957  6939 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmH,andler }
09-09 13:36:05.928   957  6939 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-09 13:36:05.928   957  1313 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:05.928   957  1313 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-09 13:36:05.928   957  6939 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:05.928   957  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-09 13:36:05.929   957  1056 D Tethering: MasterInitialState.processMessage what=3
09-09 13:36:05.930   957  1313 D ConnectivityService: validation of new default Network = false
09-09 13:36:05.930   957  1313 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-09 13:36:05.930   957  1313 D DSQN    : enableDataServiceNotify 
09-09 13:36:05.930   957  1313 D DSQN    : start dsqn bin
09-09 13:36:05.931  1837  1837 W QCNEJ   : |CORE| No family connected
09-09 13:36:05.931  1837  1837 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
09-09 13:36:05.931  1837  1837 I QCNEJ   : |CORE| sendDefaultNwMsg: default = 1
09-09 13:36:05.936   957  6939 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] Start DNSResolver start to wait
,09-09 13:36:05.939   957  1304 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-09 13:36:05.941   957  6947 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wait 500ms before dns check
09-09 13:36:05.948  1370  1370 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:36:05.950  1370  1370 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
,09-09 13:36:05.951  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:36:05.951  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:05.951  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_1_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:05.953  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:36:05.954  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:05.954  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_1_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:05.970   957  1313 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-09 13:36:05.971   957  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:05.971   957  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:05.971   957  1313 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-09 13:36:05.972  1370  1740 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:36:05.973  6916  6916 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 13:36:05.974  6916  6916 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-09 13:36:05.981  6948  6948 I DSQN    : DSQN samuel.seo ver 141203
09-09 13:36:05.982  6948  6948 E DSQN    : DSQN sock connect success to lgdatalistenerd
09-09 13:36:05.982  6948  6948 I DSQN    : created command queue thread
09-09 13:36:05.982  6948  6948 I DSQN    : Interface wlan0 address 192.168.1.109 0xc0a8016d
09-09 13:36:05.982  6948  6948 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a8016d
,09-09 13:36:06.006   957  6941 D DhcpStateMachine: DHCPV4 request on wlan0
09-09 13:36:06.007   957  6941 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-09 13:36:06.007   957  6941 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-09 13:36:06.021  6951  6951 I dhcpcd  : version 5.5.6 starting
09-09 13:36:06.023  6951  6951 E dhcpcd  : get_duid: Read-only file system
,09-09 13:36:06.055  6916  6916 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 13:36:06.103  6951  6951 I dhcpcd  : wlan0: rebinding lease of 192.168.1.109
,09-09 13:36:06.138  6951  6951 I dhcpcd  : wlan0: acknowledged 192.168.1.109 from 192.168.1.1
,09-09 13:36:06.142  6951  6951 I dhcpcd  : wlan0: leased 192.168.1.109 for 172800 seconds
09-09 13:36:06.157  6916  6916 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-09 13:36:06.159  6916  6916 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5458c02: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-09 13:36:06.160  6916  6916 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-09 13:36:06.160  6916  6916 D AndroidMusic: GMSCore installation verified
09-09 13:36:06.169  6916  6916 I ConfigStore: Config Database version: 1
,09-09 13:36:06.287  6916  6916 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-09 13:36:06.297  6916  6916 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
09-09 13:36:06.308  6916  6916 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 13:36:06.410   957  6941 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:06.410   957  6941 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:06.410   957  6941 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:06.410   957  6941 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:06.410   957  6941 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:06.411   957  6941 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:06.411   957  6941 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:06.411   957  6941 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:06.411   957  6941 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-09 13:36:06.412   957  6941 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 4
09-09 13:36:06.412   957  6941 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,09-09 13:36:06.412   957  6941 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:06.412   957  6941 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:06.413   957  6941 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.109
09-09 13:36:06.413   957  6941 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-09 13:36:06.413   957  6941 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 13:36:06.413   957  6941 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-09 13:36:06.413   957  6941 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-09 13:36:06.413   957  6941 D DhcpStateMachine: RunningState
09-09 13:36:06.441   957  6947 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver start dns
,09-09 13:36:06.441   957  6947 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:06.441   957  6947 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:06.441   957  6947 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
09-09 13:36:06.442   957  6947 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:06.442   281  1043 E BandwidthController: [LG DATA] No such appUid: 1000
09-09 13:36:06.442   281  1043 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-09 13:36:06.444   281  6985 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
09-09 13:36:06.444   281  6985 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:06.444   281  6985 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
09-09 13:36:06.445   281  6985 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:36:06.491   281  6985 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:36:06.491   957  6947 I System.out: propertyValue:false
09-09 13:36:06.491   957  6947 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver end dns
,09-09 13:36:06.495   957  6939 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,09-09 13:36:06.501   957  6939 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:06.501   957  6939 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:06.525   957  2062 I art     : Explicit concurrent mark sweep GC freed 105719(5MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/35MB, paused 2.276ms total 188.315ms
,09-09 13:36:06.528  6948  6949 I DSQN    : first global connection report this to start monitoring at DSQM.
09-09 13:36:06.529  6948  6949 I DSQN    : restart monitoring
09-09 13:36:06.529  6948  6987 I DSQN    : dsqn report finish
09-09 13:36:06.529   281  1047 D LGDataListener: argv[0]=dsqncommand
09-09 13:36:06.529   281  1047 D LGDataListener: argv[1]=wlan0
09-09 13:36:06.529   281  1047 D LGDataListener: argv[2]=1
09-09 13:36:06.529   281  1047 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-09 13:36:06.529   957  1054 D DSQN    : DSQM DsqnNotification wlan0  1
09-09 13:36:06.529   957  1054 D DSQN    : start to monitor internet connection
09-09 13:36:06.546  6916  6916 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 13:36:06.559  6916  6930 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3f0
09-09 13:36:06.567   957  6939 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:36:06 GMT], X-Android-Received-Millis=[1473420966566], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473420966528]}
09-09 13:36:06.567   957  6939 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,09-09 13:36:06.569  1802  1817 D WifiServiceExtension: isInternetCheckAvailable return false
09-09 13:36:06.569   957  6939 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wifi && isInternetCheckAvailable is false
09-09 13:36:06.569   957  6939 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-09 13:36:06.570   957  1313 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-09 13:36:06.570   957  1313 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-09 13:36:06.570   957  1313 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:36:06.570   957  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:06.570   957  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:36:06.570   957  1313 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-09 13:36:06.570   957  1313 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-09 13:36:06.570   957  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:06.570   957  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:06.571   957  1313 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:06.571   957  1313 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:06.572  1749  1749 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:06.572  1370  1740 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:36:06.573  1749  1749 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
09-09 13:36:06.574   957  1306 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:06.574   957  1306 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:36:06.574   957  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 13:36:06.589   957  2125 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6992 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-09 13:36:06.593   957   957 D WifiDataContinuityService: sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
09-09 13:36:06.596   957  1306 I WifiServerServiceExt: set CMD_CAPTIVE_CHECK_COMPLETED
09-09 13:36:06.617  6916  6930 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3d0
,09-09 13:36:06.642  1370  1370 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:36:06.643  1370  1370 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
,09-09 13:36:06.650  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:36:06.650  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:06.650  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_1_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:06.652  6916  6916 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,09-09 13:36:06.656  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:36:06.656  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,09-09 13:36:06.656  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_1_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:06.669  6916  6916 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:36:06.715   957  1874 I ActivityManager: Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=7018 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,09-09 13:36:06.759  6992  6992 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:06.759  6992  6992 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 13:36:06.760  6992  6992 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 13:36:06.762   957  2062 I ActivityManager: Process com.android.vending (pid 5608) has died
09-09 13:36:06.789  7018  7018 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 13:36:06.789  7018  7018 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 13:36:06.860  7018  7018 I MultiDex: VM with version 2.1.0 has multidex support
09-09 13:36:06.860  7018  7018 I MultiDex: install
09-09 13:36:06.860  7018  7018 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-09 13:36:06.972   957  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 13:36:07.074  6992  6992 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-09 13:36:07.076   957  1305 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:07.076   957  1305 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:07.076   957  1305 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:07.094  6992  6992 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,09-09 13:36:07.110  7018  7018 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 13:36:07.187  7018  7018 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-09 13:36:07.188  7018  7018 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2a25e44c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-09 13:36:07.188  7018  7018 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-09 13:36:07.191  7018  7018 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
,09-09 13:36:07.202  7018  7018 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
,09-09 13:36:07.220   957  1379 I ActivityManager: Process com.lge.lgdmsclient (pid 6863) has died
,09-09 13:36:07.240  7018  7018 D ChimeraCfgMgr: Reading stored module config
,09-09 13:36:07.356  6916  6935 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
,09-09 13:36:07.426  6992  6992 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-09 13:36:07.446  7018  7047 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-09 13:36:07.492   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
,09-09 13:36:07.492   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:07.493   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:07.495   957  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-09 13:36:07.496   957  1313 D ConnectivityService: identical MTU - not setting
09-09 13:36:07.496   957  1313 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 13:36:07.496   957  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 13:36:07.496   957  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:07.496   957  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:07.496   957  1631 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7063 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
09-09 13:36:07.497   957  1313 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:07.498   957  1313 D ConnectivityService: Wi-Fi IP changed. Lp difference / No Route difference
09-09 13:36:07.498   957  1313 D DSQN    : enableDataServiceNotify 
09-09 13:36:07.498   957  1313 D DSQN    : start dsqn bin
09-09 13:36:07.502  1370  1740 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-09 13:36:07.512   957  1901 I ActivityManager: Process com.lge.bnr (pid 6357) has died
,09-09 13:36:07.519   957  1313 D DSQN    : dsqn is running restart
09-09 13:36:07.524  1837  1837 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
,09-09 13:36:07.525  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-127 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:07.524 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:36:07.536  7080  7080 I DSQN    : DSQN samuel.seo ver 141203
09-09 13:36:07.536  7080  7080 E DSQN    : DSQN sock connect success to lgdatalistenerd
09-09 13:36:07.537  7080  7080 I DSQN    : created command queue thread
09-09 13:36:07.537  7080  7080 I DSQN    : Interface wlan0 address 192.168.1.109 0xc0a8016d
09-09 13:36:07.537  7080  7080 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a8016d
,09-09 13:36:07.548  6992  6992 I HubEmail: JNI_OnLoad()
09-09 13:36:07.548  6992  6992 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:36:07.548  6992  6992 I HubEmail: registerNatives()
09-09 13:36:07.548  6992  6992 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:36:07.548  6992  6992 I HubEmail: registerNativeMethods()
09-09 13:36:07.548  6992  6992 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:36:07.548  6992  6992 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-09 13:36:07.554  6992  7083 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:07.591  7063  7063 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:07.591  7063  7063 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-09 13:36:07.598  7063  7063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:36:07.600  7063  7063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:36:07.607  7063  7085 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:07.609  7063  7085 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:36:07.613  7063  7084 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:36:07.616  7063  7084 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-09 13:36:07.647   957  2125 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7093 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-09 13:36:07.651  7063  7084 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:36:07.665  7063  7063 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,09-09 13:36:07.667  7063  7063 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
09-09 13:36:07.667  7063  7063 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:36:07.671  7063  7063 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:36:07.677  7063  7063 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,09-09 13:36:07.681   957  1819 I ActivityManager: Killing 6283:com.lge.eula/1000 (adj 15): empty #11
,09-09 13:36:07.707   957   974 W libprocessgroup: failed to open /acct/uid_1000/pid_6283/cgroup.procs: No such file or directory
09-09 13:36:07.762  7093  7093 I AppUp4:AppBoxCP: onCreate
,09-09 13:36:07.766  7093  7093 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-09 13:36:07.775  7093  7093 I AppUp4:DB:  setFingerPrint start
09-09 13:36:07.775  7093  7093 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
,09-09 13:36:07.786  7093  7093 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
09-09 13:36:07.786  7093  7093 I AppUp4:DB:  SDK version = 21
09-09 13:36:07.786  7093  7093 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-09 13:36:07.788  7093  7093 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-09 13:36:07.791  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 13:36:07.791  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:07.793  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 13:36:07.793  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 13:36:07.798  7093  7093 I AppUp4:CustModeStarterReceiver: onReceive
09-09 13:36:07.798  7093  7093 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:07.801  7093  7093 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@108257c7
09-09 13:36:07.801  7093  7093 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:36:07.808  7093  7093 D AppUp4:CustFacade: isSimDevice : true
09-09 13:36:07.809  7093  7093 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:36:07.809  7093  7093 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
,09-09 13:36:07.813  7093  7093 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,09-09 13:36:07.815  7093  7113 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-09 13:36:07.815  7093  7113 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-09 13:36:07.815  7093  7113 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-09 13:36:07.817   957  2125 I ActivityManager: Killing 6887:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
09-09 13:36:07.831  6786  6786 W System.err: android.os.DeadObjectException
,09-09 13:36:07.835  6786  6786 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 13:36:07.835  6786  6786 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 13:36:07.835  6786  6786 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-09 13:36:07.835  6786  6786 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
09-09 13:36:07.835  6786  6786 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
09-09 13:36:07.835  6786  6786 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
09-09 13:36:07.835  6786  6786 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:36:07.835  6786  6786 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:36:07.835  6786  6786 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:36:07.835  6786  6786 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
09-09 13:36:07.835  6786  6786 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:07.835  6786  6786 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:36:07.835  6786  6786 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
09-09 13:36:07.835  6786  6786 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
09-09 13:36:07.835  6786  6786 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-09 13:36:07.835  6786  6786 W System.err: android.os.DeadObjectException
09-09 13:36:07.836  6786  6786 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 13:36:07.836  6786  6786 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 13:36:07.836  6786  6786 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-09 13:36:07.836  6786  6786 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
09-09 13:36:07.836  6786  6786 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
09-09 13:36:07.836  6786  6786 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
09-09 13:36:07.836  6786  6786 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:36:07.836  6786  6786 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:36:07.836  6786  6786 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:36:07.836  6786  6786 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
09-09 13:36:07.836  6786  6786 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:07.836  6786  6786 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:36:07.836  6786  6786 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
09-09 13:36:07.836  6786  6786 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
09-09 13:36:07.836  6786  6786 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-09 13:36:07.874   957  1631 W libprocessgroup: failed to open /acct/uid_10089/pid_6887/cgroup.procs: No such file or directory
,09-09 13:36:07.874   957  1631 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
09-09 13:36:07.892  3187  3187 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 13:36:07.892  3187  3187 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:07.893  3187  3187 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-09 13:36:07.915   957  1293 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7116 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:07.959   957  1873 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7133 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,09-09 13:36:07.986   310   310 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 316us total 27.201ms
,09-09 13:36:08.011   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 22.494ms
09-09 13:36:08.035   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 22.089ms
,09-09 13:36:08.069  7116  7116 D UEI.SmartControl: Quickset Services start...
09-09 13:36:08.071  7116  7116 I UEI.SmartControl: Manufacture = LGE
,09-09 13:36:08.076  7116  7116 D UEI.SmartControl: File observer start...
09-09 13:36:08.077  7116  7116 E UEI.SmartControl: IR Port is disabled: false
09-09 13:36:08.077  7116  7116 D UEI.SmartControl: Starting file observer...
09-09 13:36:08.077  7116  7116 D UEI.SmartControl: Extracting JNI libs...
09-09 13:36:08.078  7116  7116 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-09 13:36:08.124  7133  7133 D PhoneMonitor: Register our PhoneStateListener
,09-09 13:36:08.130  7116  7116 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-09 13:36:08.131  7116  7116 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-09 13:36:08.131  7116  7116 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-09 13:36:08.141  7133  7133 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-09 13:36:08.144  7133  7133 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 13:36:08.145   957  1783 I ActivityManager: Killing 6763:com.lge.sync/1000 (adj 15): empty #11
09-09 13:36:08.168  7116  7116 I UEI.SmartControl: --- Selecting new region: 2
09-09 13:36:08.168  7116  7116 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
,09-09 13:36:08.171  7116  7116 D UEI.SmartControl: Platform has CIR...
09-09 13:36:08.173  7116  7116 D UEI.SmartControl: NO CIR support, need to check package...
09-09 13:36:08.173  7116  7116 I UEI.SmartControl: Model: LG-D722 uses JNI
09-09 13:36:08.176  7116  7116 D UEI.SmartControl: QS Service created
09-09 13:36:08.184   957  2125 W libprocessgroup: failed to open /acct/uid_1000/pid_6763/cgroup.procs: No such file or directory
,09-09 13:36:08.196  7018  7034 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3b0
,09-09 13:36:08.203  7133  7133 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-09 13:36:08.208  7133  7133 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-09 13:36:08.210  7133  7133 D TelephonyAutoProfiling: [parse] Load xml
,09-09 13:36:08.218  7116  7116 E UEI.SmartControl: QS start get config
09-09 13:36:08.220  3277  3277 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:08.229  7133  7133 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-09 13:36:08.230  7018  7034 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3a0
09-09 13:36:08.231  7133  7133 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
09-09 13:36:08.233  3277  3277 V DownloadManager: DownloadService onCreate
,09-09 13:36:08.238  7133  7133 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-09 13:36:08.250  3277  7160 I DownloadManager: in removeSpuriousFiles
09-09 13:36:08.250  3277  3277 I NotificationManager: com.android.providers.downloads: cancelAll by com.android.providers.downloads
09-09 13:36:08.256  3277  7160 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-09 13:36:08.257  3277  7160 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@26dc064a on behalf of 3277
,09-09 13:36:08.272  3277  7160 I DownloadManager: in trimDatabase
,09-09 13:36:08.272  3277  7160 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-09 13:36:08.278   957   975 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7163 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-09 13:36:08.305  7116  7116 D UEI.SmartControl: Loading JNI Libs...
09-09 13:36:08.307  7116  7116 D UEI.SmartControl:  configuring local db...
09-09 13:36:08.310  3277  3277 V DownloadManager: DownloadService onStartCommand
09-09 13:36:08.313  3277  7160 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@754f231 on behalf of 3277
,09-09 13:36:08.316  3277  7161 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-09 13:36:08.333  3277  7161 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3dc3d16 on behalf of 3277
,09-09 13:36:08.391  7018  7187 I CheckinService: Disabling old GoogleServicesFramework version
,09-09 13:36:08.405  3277  3277 V DownloadManager: DownloadService onDestroy
,09-09 13:36:08.453  2866  2866 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:8
,09-09 13:36:08.457  2866  2866 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 13:36:08.457  2866  2866 D WeatherAncestor: connectivity changed - connection : true
09-09 13:36:08.457  2866  2866 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 13:36:08.457  2866  2866 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:8
09-09 13:36:08.457  2866  2866 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:08.458  2866  2866 D WeatherService: 2 : shouldTimeTickRegistered : false
09-09 13:36:08.475  7018  7188 I CheckinChimeraService: Checking schedule, now: 1473420968475 next: 1473420911816
,09-09 13:36:08.480  7018  7188 I CheckinChimeraService: active receiver: enabled
,09-09 13:36:08.515  7018  7188 I CheckinChimeraService: Preparing to send checkin request
09-09 13:36:08.535  7018  7188 I EventLogChimeraService: Accumulating logs since 1473420871917
,09-09 13:36:08.574  7018  7192 I iu.SyncManager: SYNC; picasa accounts
,09-09 13:36:08.583  7116  7116 D UEI.SmartControl:  ---- Has DB8: true
09-09 13:36:08.588  7018  7018 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-09 13:36:08.591  7116  7116 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 13:36:08.592  7116  7116 D UEI.SmartControl: QS version = v2.7.11.1_RC1
09-09 13:36:08.593  7116  7116 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
09-09 13:36:08.597  7018  7018 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-09 13:36:08.600  7116  7116 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
,09-09 13:36:08.611  7116  7116 W irrc_jni: IRRCPlayer_nativeInit ++ 
09-09 13:36:08.611  7116  7116 D irrcClient: IrrcClient ++ 
09-09 13:36:08.611  7116  7116 D irrcClient: getIrrcService ++ 
09-09 13:36:08.611  7116  7116 D irrcClient: getIrrcService -- 
09-09 13:36:08.611  7116  7116 D irrcClient: IrrcClient -- 
09-09 13:36:08.611  7116  7116 W irrc_jni: IRRCPlayer_nativeInit -- 
,09-09 13:36:08.616  7018  7192 I iu.UploadsManager: num queued entries: 0
09-09 13:36:08.617  7018  7192 I iu.UploadsManager: num updated entries: 0
09-09 13:36:08.618  7116  7116 D UEI.SmartControl: Services init done
09-09 13:36:08.618  7018  7192 I iu.SyncManager: NEXT; no task
09-09 13:36:08.619  7116  7195 I UEI.SmartControl: Device manager: loading config....
09-09 13:36:08.621  7116  7116 D UEI.SmartControl: QS Service init finished
09-09 13:36:08.623  7116  7116 D UEI.SmartControl: QS Service version name: 0.1.73
09-09 13:36:08.623  7116  7116 D UEI.SmartControl: QS Service version code: 1073
09-09 13:36:08.625  7116  7116 D UEI.SmartControl: Service requested: Control
,09-09 13:36:08.625  7116  7195 D UEI.SmartControl: Config is loaded...
09-09 13:36:08.662  7116  7194 D UEI.SmartControl:  ----- QS SDK is ready!!!
09-09 13:36:08.663  7116  7194 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-09 13:36:08.672  7116  7116 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-09 13:36:08.673  7018  7193 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
09-09 13:36:08.713   957   974 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7201 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:08.723  7116  7132 D UEI.SmartControl: -----IControl: 11
09-09 13:36:08.725  7116  7132 D UEI.SmartControl: Caller: com.lge.qremote
09-09 13:36:08.725  7116  7116 D UEI.SmartControl: Internal service binding...
09-09 13:36:08.728  7116  7132 D UEI.SmartControl: ------------ IControl registerCallback...
,09-09 13:36:08.729  7116  7132 I UEI.SmartControl: Registering callback...
09-09 13:36:08.731  7116  7131 D UEI.SmartControl: -----IControl: 19
09-09 13:36:08.733  7116  7131 D UEI.SmartControl: Caller: com.lge.qremote
09-09 13:36:08.733  6813  7200 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:08.733  6813  7200 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:08.733  7116  7131 I UEI.SmartControl: Registering Services Ready callback...
09-09 13:36:08.734  6813  7200 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:08.734  6813  7200 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:08.734   281  1043 E BandwidthController: [LG DATA] No such appUid: 10061
09-09 13:36:08.734   281  1043 D DnsProxyListener: App 10061 tries DNS query. Accept family:0 protocol:0
09-09 13:36:08.734  7116  7131 I UEI.SmartControl: Notify client services are ready...
09-09 13:36:08.734   281  7215 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
09-09 13:36:08.734   281  7215 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:08.735   281  7215 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
09-09 13:36:08.735   281  7215 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:36:08.735   281  7215 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:36:08.736  7116  7207 D UEI.SmartControl: -----IControl: 8
09-09 13:36:08.736  6813  7200 I System.out: propertyValue:false
09-09 13:36:08.737  7116  7207 D UEI.SmartControl: Caller: com.lge.qremote
,09-09 13:36:08.770  7080  7081 I DSQN    : first global connection report this to start monitoring at DSQM.
09-09 13:36:08.770  7080  7081 I DSQN    : restart monitoring
,09-09 13:36:08.770   281  1047 D LGDataListener: argv[0]=dsqncommand
09-09 13:36:08.770   281  1047 D LGDataListener: argv[1]=wlan0
09-09 13:36:08.770   281  1047 D LGDataListener: argv[2]=1
09-09 13:36:08.770   281  1047 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-09 13:36:08.771  7080  7221 I DSQN    : dsqn report finish
09-09 13:36:08.771   957  1054 D DSQN    : DSQM DsqnNotification wlan0  1
09-09 13:36:08.771   957  1054 D DSQN    : start to monitor internet connection
09-09 13:36:08.801  6813  7200 I Babel   : connection state changed from UNKNOWN to CONNECTED
,09-09 13:36:08.807   957  1801 I ActivityManager: Killing 6786:com.lge.qremote/u0a106 (adj 15): empty #11
,09-09 13:36:08.848   957  1307 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-09 13:36:08.862   957  2125 W libprocessgroup: failed to open /acct/uid_10106/pid_6786/cgroup.procs: No such file or directory
,09-09 13:36:08.930   957  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:08.934   957  1025 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:08.934   957  1025 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:08.935   957   957 D LocSvc_java: onReceive
09-09 13:36:08.935   957   957 D LocSvc_java: got connectivity action
09-09 13:36:08.935   957   957 D LocSvc_java: Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
09-09 13:36:08.935   957   957 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-09 13:36:08.935   957   957 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:36:08.935   957   957 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:36:08.935   957   957 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:36:08.940  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
,09-09 13:36:08.947  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:08.947  6916  6916 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-09 13:36:08.948  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:08.948  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:08.948  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:08.948  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:08.948  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:08.948  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.948  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:08.948  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:08.950  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:08.950  6450  6450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.953  2050  2072 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:08.954  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:08.954  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:08.954  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:08.954  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:08.954  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:08.954  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.954  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:08.954  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:08.954  2050  2072 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:08.955  6450  6450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.957  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:08.958  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:08.958  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:08.958  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:08.958  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:08.958  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:08.958  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.958  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:08.958  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:36:08.959  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:08.959  6450  6450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.995  7018  7188 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,09-09 13:36:09.003  7018  7188 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
09-09 13:36:09.057   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:09.057   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 13:36:09.057   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:36:09.058  7201  7232 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-09 13:36:09.063   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:09.063   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:36:09.063   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:09.063  7201  7232 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 13:36:09.109   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:09.109   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 13:36:09.109   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:09.110  7201  7233 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-09 13:36:09.111  7201  7201 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 13:36:09.111  7201  7201 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 13:36:09.111  7201  7201 I GAv4    :   adb logcat -s GAv4
,09-09 13:36:09.114   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:09.114   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:36:09.114   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:09.115  7201  7233 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-09 13:36:09.195  7201  7201 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:36:09.205   296   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
09-09 13:36:09.222  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-09 13:36:09.224  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:36:09.226  7201  7201 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
09-09 13:36:09.237  7201  7237 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:36:09.331   957  1901 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7239 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,09-09 13:36:09.425  7239  7239 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 13:36:09.425  7239  7239 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 13:36:09.445  6450  6880 E io.jxcore.node.ConnectivityMonitorTest: BT state didn't change after 5s!
,09-09 13:36:09.450   957  1293 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:09.453   957  1293 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@5e4ec92 mBinding = false
09-09 13:36:09.465   957   957 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:36:09.465   957   957 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:36:09.465   957   957 D Ulp_jni : JNI:system_update. Event-4
,09-09 13:36:09.469   957  1056 D BluetoothManagerService: Message: 2
09-09 13:36:09.471  2050  2072 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:09.472  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:09.472  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:09.473   957  1056 D BluetoothManagerService: Sending off request.
09-09 13:36:09.478  2050  2073 D BluetoothAdapterService(667769746): disable() called...
,09-09 13:36:09.482  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:09.484  2050  2072 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:09.488  7239  7239 I MultiDex: VM with version 2.1.0 has multidex support
09-09 13:36:09.488  7239  7239 I MultiDex: install
09-09 13:36:09.488  2050  2178 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-09 13:36:09.488  7239  7239 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-09 13:36:09.489  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:09.489  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:09.489  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:09.489  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:36:09.489  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@107b983e removed from the list
09-09 13:36:09.489  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:09.490  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2af6e69f removed from the list
09-09 13:36:09.490  2050  2178 D BluetoothAdapterProperties: Setting state to 13
09-09 13:36:09.490  2050  2178 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 13:36:09.490  2050  2178 D BluetoothAdapterService(667769746): updateAdapterState() - Broadcasting state to 1 receivers.
09-09 13:36:09.490  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:09.492  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:09.492  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:09.502  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:36:09.502  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3494fa4a added. We now have 3 listener(s)
09-09 13:36:09.502   957  1843 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:09.505  2050  2178 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 13:36:09.506  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-09 13:36:09.506  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:36:09.506  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:36:09.506  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:36:09.506  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26ed4dbb added. We now have 3 listener(s)
09-09 13:36:09.506  6450  6534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:36:09.507  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:36:09.509  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:09.510  2050  2178 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-09 13:36:09.513  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:09.513  6450  6534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:09.513  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:09.513  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:09.513  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:09.513  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:09.513  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:09.513  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:09.513  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:09.514  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:09.514  6450  6534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:09.514  6450  6534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:36:09.516  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:09.516  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:09.516  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:09.516  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:36:09.516  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3494fa4a removed from the list
09-09 13:36:09.516  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:09.516  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26ed4dbb removed from the list
09-09 13:36:09.516  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:09.516  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:09.517  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:36:09.517  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32497631 added. We now have 3 listener(s)
09-09 13:36:09.518   957  1843 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:09.519  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:09.520  2050  2200 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
09-09 13:36:09.524  2050  2200 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:36:09.524  2050  2178 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-09 13:36:09.525  2050  2178 I bt-btif : BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
09-09 13:36:09.525  2050  2178 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-09 13:36:09.526  2050  2178 D bt-btif : b,tsock_ctrl_hci_cleanup(L202): poll handle:4
09-09 13:36:09.527  2050  2178 I bt-btif : BTA_JvDeleteRecord
09-09 13:36:09.527  2050  2178 I bt-btif : BTA_JvRfcommStopServer
09-09 13:36:09.527  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:09.527  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:09.527  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:09.527  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:09.527  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:09.527  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:09.527  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:09.527  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:09.527  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:09.527  2050  2178 I bt-btif : BTA_JvDeleteRecord
09-09 13:36:09.527  2050  2178 I bt-btif : BTA_JvRfcommStopServer
09-09 13:36:09.528  2050  3789 W bt-btif : invalid rfc slot id: 1
09-09 13:36:09.528  2050  3789 W bt-btif : invalid rfc slot id: 2
09-09 13:36:09.528  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:09.528  6450  6450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:09.529  2050  2178 D IOP_DB_BT: db_close: nbr users 0
09-09 13:36:09.529  2050  2178 D IOP_DB_BT: db_close: free database
,09-09 13:36:09.530  2050  2178 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-09 13:36:09.530  2050  2178 D btif_config_util: enum_config(L300): in, key:Adapter, value:BluezMigrationDone
09-09 13:36:09.530  2050  2178 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
09-09 13:36:09.530  2050  2178 D btif_config_util: enum_config(L343): out, key:Adapter, value:BluezMigrationDone
09-09 13:36:09.530  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.530  2050  2178 D btif_config_util: enum_config(L300): in, key:Adapter, value:Address
09-09 13:36:09.530  2050  2178 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
09-09 13:36:09.530  2050  2178 D btif_config_util: enum_config(L343): out, key:Adapter, value:Address
09-09 13:36:09.531  2050  2178 D btif_config_util: enum_config(L344): out, value:f8:95:c7:87:85:54
09-09 13:36:09.531  2050  2178 D btif_config_util: enum_config(L300): in, key:Adapter, value:Name
09-09 13:36:09.531  2050  2178 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
09-09 13:36:09.531  2050  2178 D btif_config_util: enum_config(L343): out, key:Adapter, value:Name
09-09 13:36:09.531  2050  2178 D btif_config_util: enum_config(L344): out, value:G3s-1
09-09 13:36:09.531  2050  2178 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
09-09 13:36:09.531  2050  2178 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
09-09 13:36:09.531  2050  2178 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
09-09 13:36:09.531  2050  2178 D btif_config_util: enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
09-09 13:36:09.531  2050  2178 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
09-09 13:36:09.531  2050  2178 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
09-09 13:36:09.531  2050  2178 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
09-09 13:36:09.531  2050  2178 D btif_config_util: enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
09-09 13:36:09.531  2050  2178 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
09-09 13:36:09.532  2050  2178 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
09-09 13:36:09.532  2050  2178 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
09-09 13:36:09.532  2050  2178 D btif_config_util: enum_config(L344): out, value:��8�\�婓��n�ScanMode
09-09 13:36:09.532  2050  2178 D btif_config_util: enum_config(L300): in, key:Adapter, value:ScanMode
09-09 13:36:09.532  2050  2178 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
09-09 13:36:09.532  2050  2178 D btif_config_util: enum_config(L343): out, key:Adapter, value:ScanMode
09-09 13:36:09.532  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.532  2050  2178 D btif_config_util: enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
09-09 13:36:09.532  2050  2178 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
09-09 13:36:09.532  2050  2178 D btif_config_util: enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
09-09 13:36:09.532  2050  2178 D btif_config_util: enum_config(L344): out, value:x
09-09 13:36:09.532  2050  2178 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
09-09 13:36:09.532  2050  2178 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
09-09 13:36:09.532  2050  3655 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1,000 ms
09-09 13:36:09.532  2050  2178 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
09-09 13:36:09.532  2050  2178 D btif_config_util: enum_config(L344): out, value:s!WE�(E��00:0F:F6
09-09 13:36:09.532  2050  2178 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
09-09 13:36:09.532  2050  2178 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
09-09 13:36:09.533  2050  2178 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
09-09 13:36:09.533  2050  2178 D btif_config_util: enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
09-09 13:36:09.533  2050  2178 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
09-09 13:36:09.533  2050  2178 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
09-09 13:36:09.533  2050  2178 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
09-09 13:36:09.533  2050  2178 D btif_config_util: enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
09-09 13:36:09.533  2050  2178 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
09-09 13:36:09.533  2050  2178 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
09-09 13:36:09.533  2050  2178 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
09-09 13:36:09.533  2050  2178 D btif_config_util: enum_config(L344): out, value:BMW,Audi,Parrot,Car
09-09 13:36:09.533  2050  2178 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
,09-09 13:36:09.533  2050  2178 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
09-09 13:36:09.535  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:09.536  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-09 13:36:09.536  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:36:09.536  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:36:09.536  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:36:09.536  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26307116 added. We now have 3 listener(s)
09-09 13:36:09.536  6450  6534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:36:09.537  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:36:09.538  2050  2178 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
09-09 13:36:09.538  2050  2178 D btif_config_util: enum_config(L344): out, value:00:0F:F6
09-09 13:36:09.538  2050  2178 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
09-09 13:36:09.538  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
09-09 13:36:09.538  2050  2178 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
09-09 13:36:09.538  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.538  2050  2178 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
09-09 13:36:09.538  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
,09-09 13:36:09.538  2050  2178 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
09-09 13:36:09.538  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L344): out, value:�
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L344): out, value:HTC Desire 820
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
,09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
09-09 13:36:09.539  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
09-09 13:36:09.539  2050  3655 W bt-obex : Ignore event 10 in state 1
09-09 13:36:09.539  2050  3655 W bt-obex : Ignore event 10 in state 1
09-09 13:36:09.540  2050  2200 E bt-btif : btif_hf_upstreams_evt: wrong handle = 27 
09-09 13:36:09.540  2050  2200 I bt-btif : HAL bt_op_callbacks->ops_state_cb
09-09 13:36:09.540  2050  2200 D BluetoothOPPServiceJni: ops_state_cb(L223):  ops_state_cb state:3
09-09 13:36:09.540  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:09.540  2050  3655 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 13:36:09.540  2050  2178 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
09-09 13:36:09.540  2050  2178 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-09 13:36:09.540  2050  2178 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
09-09 13:36:09.541  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09, 13:36:09.541  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:09.541  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:09.541  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:09.541  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:09.541  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:09.541  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:09.541  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L344): out, value:$
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L344): out, value:Galaxy S6-1
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
,09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
09-09 13:36:09.541  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
09-09 13:36:09.541  6450  6450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
09-09 13:36:09.541  2050  2200 D OppService: onOpsStateChange() :3
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
,09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L344): out, value:�
09-09 13:36:09.541  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L344): out, value:A5-1
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
,09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
09-09 13:36:09.542  2050  2050 D OppService: Recieved MESSAGE_OPS_DISABLE
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
,09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
,09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
,09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L344): out, value:#
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
,09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L344): out, value:Nexus 6
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
,09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.542  2050  2178 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
,09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
09-09 13:36:09.543  2050  2072 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer,
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
09-09 13:36:09.543   957  1056 D BluetoothManagerService: Message: 60
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L344): out, value:�
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L344): out, value:XT1072
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
09-09 13:36:09.543  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
09-09 13:36:09.543   957  1056 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13,
09-09 13:36:09.543   957  1056 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-09 13:36:09.545  2050  2178 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
09-09 13:36:09.545  2050  2178 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-09 13:36:09.545  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
09-09 13:36:09.545  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
09-09 13:36:09.545  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
09-09 13:36:09.545  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.545  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
09-09 13:36:09.545  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
09-09 13:36:09.545  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
09-09 13:36:09.545  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.545  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
09-09 13:36:09.545  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
09-09 13:36:09.545  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
09-09 13:36:09.545  2050  2178 D btif_config_util: enum_config(L344): out, value:a
09-09 13:36:09.545  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
09-09 13:36:09.545  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L344): out, value:S5-1
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
09,-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Service
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Service, value type:string
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Service
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Manufacturer
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Manufacturer, value type:int
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Manufacturer
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpVer
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpVer, value type:int
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpVer
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpSubVer
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpSubVer, value type:int
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpSubVer
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L344): out, value:	a
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Name
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Name, value type:string
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Name
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L344): out, value:G4-1
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevClass
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevClass, value type:int
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevClass
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevType
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevType, value type:int
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevType
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:JustWorks
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:JustWorks, value type:int
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:JustWorks
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:GlobalTrust
09-09 13:36:09.546  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:GlobalTrust, value type:int
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:GlobalTrust
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Service
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Service, value type:string
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Service
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Manufacturer
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Manufacturer, value type:int
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Manufacturer
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpVer
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpVer, value type:int
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpVer
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpSubVer
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpSubVer, value type:int
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpSubVer
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L344): out, value:a
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Name
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Name, value type:string
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Name
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L344): out, value:Thali Test (Galaxy S5)
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevClass
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevClass, value type:int
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevClass
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevType
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevType, value type:int
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevType
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:JustWorks
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:JustWorks, value type:int
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:JustWorks
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:GlobalTrust
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:GlobalTrust, value type:int
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:GlobalTrust
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Service
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Service, value type:string
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Service
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Manufacturer
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Manufacturer, value type:int
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Manufacturer
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpVer
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpVer, value type:int
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpVer
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpSubVer
09-09 13:36:09.547  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpSubVer, value type:int
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpSubVer
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L344): out, value:�
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Name
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Name, value type:string
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Name
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L344): out, value:Thali Test (Galaxy A5)
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevClass
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevClass, value type:int
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevClass
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevType
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevType, value type:int
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevType
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:JustWorks
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:JustWorks, value type:int
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:JustWorks
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:GlobalTrust
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:GlobalTrust, value type:int
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:GlobalTrust
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Service
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Service, value type:string
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Service
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
09-09 13:36:09.548  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L344): out, value:�
09-09 13:36:09.548  6450  6534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:09.548  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:09.548  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:09.548  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:09.548  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:09.548  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:09.548  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:09.548  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L344): out, value:Thali Test (Galaxy A3)
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:JustWorks, value type:int
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
09-09 13:36:09.548  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:GlobalTrust
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
09-09 13:36:09.549  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Manufacturer
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Manufacturer, value type:int
09-09 13:36:09.549  6450  6534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpVer, value type:int
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpSubVer, value type:int
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L344): out, value:A
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Name
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L344): out, value:Thali Test's G2
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevClass, value type:int
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevType
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:JustWorks
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:GlobalTrust, value type:int
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Service
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Manufacturer
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Manufacturer, value type:int
09-09 13:36:09.549  6450  6534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
09-09 13:36:09.549  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpSubVer, value type:int
09-09 13:36:09.550  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:GlobalTrust, value type:int
09-09 13:36:09.550  2050  2178 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:Name
09-09 13:36:09.550  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.551  2050  2178 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Name
09-09 13:36:09.551  2050  2178 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Service
09-09 13:36:09.551  2050  2178 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevClass
09-09 13:36:09.551  2050  2178 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Service
09-09 13:36:09.552  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevClass, value type:int
09-09 13:36:09.552  2050  2178 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevType
09-09 13:36:09.553  2050  2178 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:JustWorks
09-09 13:36:09.553  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpSubVer, value type:int
09-09 13:36:09.553  2050  2178 D btif_config_util: enum_config(L300): in, key:58:3f:54:73:64:c0, value:GlobalTrust
09-09 13:36:09.555  2050  2178 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Manufacturer
09-09 13:36:09.555  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.555  2050  2178 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpVer
09-09 13:36:09.555  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpVer, value type:int
09-09 13:36:09.556  2050  2178 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpVer
09-09 13:36:09.556  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.556  2050  2178 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpSubVer
09-09 13:36:09.556  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpSubVer, value type:int
09-09 13:36:09.556  2050  2178 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpSubVer
09-09 13:36:09.556  2050  2178 D btif_config_util: enum_config(L344): out, value:	a
09-09 13:36:09.556  2050  2178 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevType
09-09 13:36:09.556  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpVer, value type:int
09-09 13:36:09.556  2050  2178 D btif_config_util: enum_config(L343): out, key:90:e7:c4:f6:69:77, value:JustWorks
09-09 13:36:09.557  2050  2178 D btif_config_util: enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpSubVer
09-09 13:36:09.557  2050  2178 D btif_config_util: enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Service
09-09 13:36:09.557  2050  2178 D btif_config_util: enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpVer
09-09 13:36:09.558  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.558  2050  2178 D btif_config_util: enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpSubVer
09-09 13:36:09.558  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:JustWorks, value type:int
09-09 13:36:09.558  2050  2178 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpSubVer
09-09 13:36:09.559  2050  2178 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevClass, value type:int
09-09 13:36:09.559  2050  2178 D btif_config_util: enum_config(L343): out, key:00:00:00:00:41:0e, value:DevType
09-09 13:36:09.559  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.559  2050  2178 D btif_config_util: enum_config(L300): in, key:08:00:00:00:67:73, value:DevType
09-09 13:36:09.559  2050  2178 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:GlobalTrust
09-09 13:36:09.560  2050  2178 D btif_config_util: enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevClass
09-09 13:36:09.560  2050  2178 D btif_config_util: enum_config(L344): out, value:
09-09 13:36:09.560  2050  2178 D btif_config_util: enum_config(L300): in, key:08:00:00:00:67:53, value:DevClass
09-09 13:36:09.560  2050  2178 D btif_config_util: enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevClass
09-09 13:36:09.564  1802  1802 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:09.566  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:09.567  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:09.568  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:09.580  2050  2050 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:09.580  2050  2050 D BluetoothMapService: STATE_TURNING_OFF
09-09 13:36:09.581  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:09.585  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:09.589  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:09.590  2050  3796 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:36:09.592  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
09-09 13:36:09.592  2050  2050 V BluetoothMapService: Handler(): got msg=4
09-09 13:36:09.592  2050  2050 D BluetoothMapService: MAP Service closeService in
09-09 13:36:09.592  2050  2050 D BluetoothMapMasInstance: MAP Service shutdown
09-09 13:36:09.595   957  1379 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:09.595   957  1379 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@5e4ec92 mBinding = false
09-09 13:36:09.600   957  1056 D BluetoothManagerService: Message: 2
09-09 13:36:09.600   957  1056 D BluetoothManagerService: Sending off request.
09-09 13:36:09.602  1370  1370 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
09-09 13:36:09.605  2050  3653 D BluetoothAdapterService(667769746): disable() called...
09-09 13:36:09.613  6450  6534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:09.613  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:09.613  2050  3653 D BluetoothAdapterService: disable() : BT State is not STATE_ON. Can't disable BT
09-09 13:36:09.614   957  1056 E BluetoothManagerService: IBluetooth.disable() returned false
09-09 13:36:09.617   957  1379 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:09.618   957  1379 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@5e4ec92 mBinding = false
,09-09 13:36:09.619  2050  3794 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-09 13:36:09.619  2050  3794 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:36:09.619  2050  3794 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-09 13:36:09.619  2050  3794 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-09 13:36:09.619  2050  3794 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-09 13:36:09.619  2050  3794 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-09 13:36:09.619  2050  3794 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-09 13:36:09.619  2050  3794 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-09 13:36:09.624  2050  2050 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 13:36:09.624  2050  2050 V BluetoothMapService: MAP Service closeService out
09-09 13:36:09.639   957   957 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:36:09.640   957   957 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:36:09.640   957   957 D Ulp_jni : JNI:system_update. Event-4
09-09 13:36:09.641   957  1056 D BluetoothManagerService: Message: 1
09-09 13:36:09.641   957  1056 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@5e4ec92
09-09 13:36:09.643  6732  6732 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 13:36:09.651  2050  2050 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 13:36:09.651  2050  2050 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:09.651  2050  2050 V BluetoothPbapReceiver: ***********state = 13
09-09 13:36:09.656  2050  2050 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-09 13:36:09.658  2050  2050 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:09.658  2050  2050 V BluetoothPbapService: state: 13
09-09 13:36:09.658  2050  2050 V BluetoothPbapService: Pbap Service closeService in
09-09 13:36:09.658   957  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3a6b3edb type 2 when 159141 com.android.systemui} when 159141
09-09 13:36:09.658  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:09.658  2050  2073 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-09 13:36:09.659  2050  2050 V BluetoothPbapService: successfully stopped pbap service
09-09 13:36:09.659  2050  2050 V BluetoothPbapService: Pbap Service closeService out
09-09 13:36:09.660  2050  2050 V BluetoothPbapService: Pbap Service onDestroy
09-09 13:36:09.660  2050  2050 V BluetoothPbapService: Pbap Service closeService in
09-09 13:36:09.660  2050  2050 V BluetoothPbapService: Pbap Service closeService out
09-09 13:36:09.660  2050  2050 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-09 13:36:09.660   957  1056 E BluetoothManagerService: IBluetooth.enable() returned false
09-09 13:36:09.661   957  1056 D BluetoothManagerService: Message: 20
09-09 13:36:09.661   957  1056 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a3e9c51:true
09-09 13:36:09.663  7239  7239 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 13:36:09.743  7239  7239 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-09 13:36:09.744  7239  7239 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2eb72ed8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-09 13:36:09.745  7239  7239 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-09 13:36:09.746  7239  7239 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
09-09 13:36:09.746  7239  7239 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
09-09 13:36:09.756  7239  7239 D ChimeraCfgMgr: Reading stored module config
,09-09 13:36:09.806  1730  1730 I art     : Explicit concurrent mark sweep GC freed 47330(2MB) AllocSpace objects, 27(453KB) LOS objects, 39% free, 15MB/25MB, paused 1.411ms total 130.554ms
,09-09 13:36:09.860   957   974 I art     : Explicit concurrent mark sweep GC freed 29234(1438KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.569ms total 182.316ms
,09-09 13:36:09.868  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:09.879   957  1056 D BluetoothManagerService: Message: 30
,09-09 13:36:09.900   957  1056 D BluetoothManagerService: Message: 30
,09-09 13:36:09.903  6732  6732 D LocalBluetoothProfileManager: Adding local MAP profile
09-09 13:36:09.907  6732  6732 D BluetoothMap: Create BluetoothMap proxy object
09-09 13:36:09.908   957  1056 D BluetoothManagerService: Message: 30
09-09 13:36:09.912   957  1056 D BluetoothManagerService: Message: 30
,09-09 13:36:09.920  6732  6732 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-09 13:36:09.920  7239  7253 W art     : Suspending all threads took: 6.136ms
09-09 13:36:09.934  6732  6732 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,09-09 13:36:10.024  7201  7201 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,09-09 13:36:10.034   957  1026 W ProcessCpuTracker: Skipping unknown process pid 6916
09-09 13:36:10.035  7239  7282 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
09-09 13:36:10.047   957  1379 I ActivityManager: Process com.google.android.music:main (pid 6916) has died
09-09 13:36:10.048  7239  7239 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-09 13:36:10.048  7239  7239 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
09-09 13:36:10.051  6732  6732 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
09-09 13:36:10.055   957  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:10.055   957  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:10.056  6732  6732 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-09 13:36:10.059   957  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:10.059   957  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:10.059   281  1043 E BandwidthController: [LG DATA] No such appUid: 1000
09-09 13:36:10.059   281  1043 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-09 13:36:10.059   281  7291 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
09-09 13:36:10.059   281  7291 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:10.060   281  7291 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
09-09 13:36:10.060   281  7291 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,09-09 13:36:10.071  6732  6732 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:36:10.081  6732  6732 D BluetoothInputDevice: Proxy object connected
,09-09 13:36:10.087  6732  6732 D HidProfile: Bluetooth service connected
,09-09 13:36:10.089  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:10.089  6732  6732 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:36:10.094  6732  6732 D PanProfile: Bluetooth service connected
,09-09 13:36:10.096   281  7291 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:36:10.097  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:10.097   957  1307 I System.out: propertyValue:false
09-09 13:36:10.097  6732  6732 D BluetoothMap: Proxy object connected
09-09 13:36:10.098  6732  6732 D MapProfile: Bluetooth service connected
09-09 13:36:10.098  6732  6732 D BluetoothMap: getConnectedDevices()
09-09 13:36:10.099  2050  2072 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:10.099  6732  6732 D BluetoothMap: Bluetooth is Not enabled
09-09 13:36:10.099  6732  6732 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-09 13:36:10.100   957  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:10.101   957  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:10.101   957  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:10.101   957  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:10.101   281  1043 E BandwidthController: [LG DATA] No such appUid: 1000
09-09 13:36:10.101   281  1043 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-09 13:36:10.101   281  7296 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
09-09 13:36:10.101   281  7296 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:10.102   281  7296 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
09-09 13:36:10.102   281  7296 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:36:10.102   281  7296 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:36:10.102  6732  6732 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-09 13:36:10.103   957  1308 I System.out: propertyValue:false
09-09 13:36:10.104  6732  6732 I NotificationManager: com.android.settings: cancel(17301632) by com.android.settings
09-09 13:36:10.104  6732  6732 I NotificationManager: com.android.settings: cancel(-1000001) by com.android.settings
09-09 13:36:10.107  6732  6732 I NotificationManager: com.android.settings: cancel(-1000011) by com.android.settings
,09-09 13:36:10.107  6732  6732 I NotificationManager: com.android.settings: cancel(-1000021) by com.android.settings
09-09 13:36:10.108  6732  6732 I NotificationManager: com.android.settings: cancel(-1000031) by com.android.settings
09-09 13:36:10.109  6732  6732 I NotificationManager: com.android.settings: cancel(-1000041) by com.android.settings
,09-09 13:36:10.113  6732  6732 D BluetoothPermissionRequest: onReceive
09-09 13:36:10.116  6732  6732 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-09 13:36:10.116  6732  6732 I NotificationManager: com.android.settings: cancel(17301632) by com.android.settings
09-09 13:36:10.121  6732  6732 I NotificationManager: com.android.settings: cancel(-1000001) by com.android.settings
,09-09 13:36:10.123  6732  6732 I NotificationManager: com.android.settings: cancel(-1000011) by com.android.settings
09-09 13:36:10.124  6732  6732 I NotificationManager: com.android.settings: cancel(-1000021) by com.android.settings
09-09 13:36:10.124  6732  6732 I NotificationManager: com.android.settings: cancel(-1000031) by com.android.settings
09-09 13:36:10.125  6732  6732 I NotificationManager: com.android.settings: cancel(-1000041) by com.android.settings
09-09 13:36:10.133  7201  7201 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9627-9631)
09-09 13:36:10.133  7201  7201 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 13:36:10.140  2050  2050 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-09 13:36:10.140  2050  2050 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-09 13:36:10.140  2050  2050 I NotificationManager: com.android.bluetooth: cancel(-1) by com.android.bluetooth
09-09 13:36:10.143  2050  2050 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-09 13:36:10.143  2050  2050 I NotificationManager: com.android.bluetooth: cancel(-1) by com.android.bluetooth
09-09 13:36:10.148  7201  7201 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {293ffe08}
,09-09 13:36:10.149  7201  7201 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:36:10.149  7201  7201 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 13:36:10.151  2050  2050 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 13:36:10.155   285  1584 D WVCdm   : Instantiating CDM.
09-09 13:36:10.155   285  1581 I WVCdm   : CdmEngine::OpenSession
09-09 13:36:10.155   285  1581 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
09-09 13:36:10.156  2050  2050 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:10.168  7201  7201 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 13:36:10.169  7201  7201 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:36:10.171  7201  7201 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 13:36:10.178   957  1308 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
09-09 13:36:10.191   285  1581 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-09 13:36:10.193   285  1581 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
09-09 13:36:10.193   285  1581 W WVCdm   : L1 library not specified. Falling Back to L3
09-09 13:36:10.195  4061  4364 I art     : Explicit concurrent mark sweep GC freed 1771(66KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 957us total 49.700ms
09-09 13:36:10.201  7201  7201 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 13:36:10.206   957  1874 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7307 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
09-09 13:36:10.210  7201  7201 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:36:10.210  7201  7201 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:36:10.211  7201  7201 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:36:10.211  7201  7201 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:36:10.211  7201  7201 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:36:10.211  7201  7201 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:36:10.211  7201  7201 I Adreno-EGL: Remote Branch: 
09-09 13:36:10.211  7201  7201 I Adreno-EGL: Local Patches: 
09-09 13:36:10.211  7201  7201 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:36:10.262   285  1581 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-09 13:36:10.263   285   285 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-09 13:36:10.263   285   285 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-09 13:36:10.263   285   285 I WVCdm   : CdmEngine::GenerateKeyRequest
,09-09 13:36:10.270   285   285 D WVCdm   : PrepareKeyRequest: nonce=461306692
09-09 13:36:10.293  7239  7253 I art     : CheckpointMarkThreadRoots callback created = 0xb042d430
,09-09 13:36:10.321  7239  7253 I art     : CheckpointMarkThreadRoots callback created = 0xb042d410
,09-09 13:36:10.366  7307  7307 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 13:36:10.383   285  1584 V AudioPolicyService: registerClient() client 0xb39b6d20, uid 10079
,09-09 13:36:10.384  7201  7332 W AudioManagerAndroid: Requires BLUETOOTH permission
09-09 13:36:10.404  7201  7201 I NSApplication: Starting up...
,09-09 13:36:10.410  1730  1730 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-09 13:36:10.415  1730  1730 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-09 13:36:10.477   957  1819 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7337 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:10.478   957  1819 I ActivityManager: Killing 6992:com.lge.email/u0a21 (adj 15): empty #11
09-09 13:36:10.541  2050  3655 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:36:10.541  2050  3655 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:36:10.542  2050  3655 W bt-btif : ag scb idx 1 not allocated
09-09 13:36:10.542  2050  3655 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 13:36:10.542  2050  3655 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:36:10.542  2050  3655 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 13:36:10.542  2050  3655 W bt-btif : ag scb idx 1 not allocated
09-09 13:36:10.542  2050  3655 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 13:36:10.542  2050  3655 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 13:36:10.542  2050  3655 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 13:36:10.543  2050  3674 W bt_userial: select_read return size <=0:0, exiting userial_read_thread
09-09 13:36:10.543  2050  3657 D bt_hwcfg: hw_epilog_process
09-09 13:36:10.544  2050  2200 I bt_userial_vendor: device fd = 67 close
09-09 13:36:10.564  2050  2200 E bt_vendor: [BTUI] Proto is enabled. Set Proto disable!!
,09-09 13:36:10.613   957  1631 W libprocessgroup: failed to open /acct/uid_10021/pid_6992/cgroup.procs: No such file or directory
,09-09 13:36:10.669  2050  2200 I GKI_LINUX: GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
09-09 13:36:10.669  2050  3655 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-09 13:36:10.669  2050  2200 I GKI_LINUX: GKI_destroy_task(): task [BTU] terminated
,09-09 13:36:10.670  2050  2200 I bt-btif : HAL bt_hal_cbacks->adapter_state_changed_cb
,09-09 13:36:10.670  2050  2178 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-09 13:36:10.673  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:36:10.673  2050  2178 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 13:36:10.673  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:36:10.673  2050  2178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 13:36:10.711  2050  2178 D BtSettings.ProfileConfig: Unable to read settings
09-09 13:36:10.711  2050  2178 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-09 13:36:10.711  2050  2178 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
09-09 13:36:10.711  2050  2178 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
09-09 13:36:10.711  2050  2178 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
09-09 13:36:10.711  2050  2178 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
09-09 13:36:10.711  2050  2178 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
09-09 13:36:10.711  2050  2178 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
09-09 13:36:10.711  2050  2178 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
09-09 13:36:10.711  2050  2178 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
09-09 13:36:10.711  2050  2178 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:36:10.711  2050  2178 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:36:10.711  2050  2178 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 13:36:10.711  2050  2178 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-09 13:36:10.711  2050  2178 D BluetoothAdapterService(667769746): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
,09-09 13:36:10.712  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:36:10.712  2050  2178 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 13:36:10.712  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:36:10.712  2050  2178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 13:36:10.713  2050  2178 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-09 13:36:10.713  2050  2178 D BluetoothAdapterService(667769746): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
09-09 13:36:10.714  2050  2050 D HeadsetService: Received stop request...Stopping profile...
09-09 13:36:10.715  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:36:10.715  2050  2178 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-09 13:36:10.715  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:36:10.715  2050  2178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:36:10.715  2050  2178 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-09 13:36:10.715  2050  2178 D BluetoothAdapterService(667769746): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
09-09 13:36:10.716  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:36:10.716  2050  2178 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-09 13:36:10.716  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:36:10.716  2050  2178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 13:36:10.717  2050  2178 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-09 13:36:10.717  2050  2178 D BluetoothAdapterService(667769746): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
09-09 13:36:10.718  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
,09-09 13:36:10.718  2050  2178 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-09 13:36:10.718  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:36:10.718  2050  2178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 13:36:10.718  2050  2178 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-09 13:36:10.718  2050  2178 D BluetoothAdapterService(667769746): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
09-09 13:36:10.719  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:36:10.719  2050  2178 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-09 13:36:10.719  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:36:10.719  2050  2178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-09 13:36:10.720  2050  2178 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-09 13:36:10.720  2050  2178 D BluetoothAdapterService(667769746): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
09-09 13:36:10.721  2050  2050 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 13:36:10.722  2050  3591 D HeadsetStateMachine: Exit Disconnected: -1
09-09 13:36:10.722  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:36:10.722  2050  2178 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 13:36:10.722  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:36:10.722  2050  2178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:36:10.723  2050  2178 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-09 13:36:10.723  2050  2178 D BluetoothAdapterService(667769746): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
09-09 13:36:10.723  2050  2050 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 13:36:10.723  2050  2050 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27cd5b92
09-09 13:36:10.724  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:36:10.724  2050  2178 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-09 13:36:10.724  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:36:10.724  2050  2178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-09 13:36:10.726   957   957 D BluetoothHeadset: Proxy object disconnected
09-09 13:36:10.727  2050  2178 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-09 13:36:10.727  2050  2178 D BluetoothAdapterService(667769746): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
09-09 13:36:10.727  1749  1749 D BluetoothHeadset: Proxy object disconnected
09-09 13:36:10.728   957   957 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-09 13:36:10.729  2050  2050 D A2dpService: Received stop request...Stopping profile...
09-09 13:36:10.729  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:36:10.729  2050  2178 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
09-09 13:36:10.729  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:36:10.729  2050  2178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
09-09 13:36:10.730  2050  2178 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.ftp.FTPService
09-09 13:36:10.730  2050  2178 D BluetoothAdapterService(667769746): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
09-09 13:36:10.731  2050  3620 D A2dpStateMachine: Exit Disconnected: -1
09-09 13:36:10.731  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:36:10.731  2050  2178 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
09-09 13:36:10.731  2050  2178 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:36:10.731  2050  2178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.732  2050  2178 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.opp.OppService
09-09 13:36:10.732  2050  2178 D BluetoothAdapterService(667769746): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
09-09 13:36:10.733  2050  2178 D BluetoothAdapterState: Stopping profile services that were post enabled
09-09 13:36:10.733  1749  1749 D BluetoothHeadset: Proxy object disconnected
09-09 13:36:10.738  1749  1749 D BluetoothHeadset: Proxy object disconnected
09-09 13:36:10.744  2050  2050 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-09 13:36:10.744  2050  2050 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-09 13:36:10.745  2050  2050 D LGBluetoothPowerControlManager: [BTUI] terminate
09-09 13:36:10.747  2050  2050 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27cd5b92
09-09 13:36:10.748   957   957 D BluetoothA2dp: Proxy object disconnected
09-09 13:36:10.748   957   957 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-09 13:36:10.748   957  1056 D BluetoothManagerService: Message: 31
09-09 13:36:10.748  2050  2050 D HidService: Received stop request...Stopping profile...
09-09 13:36:10.748  2050  2050 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27cd5b92
09-09 13:36:10.749  2050  2050 D HealthService: Received stop request...Stopping profile...
09-09 13:36:10.750  2050  2050 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27cd5b92
09-09 13:36:10.750  6732  6732 D BluetoothInputDevice: Proxy object disconnected
09-09 13:36:10.750  6732  6732 D HidProfile: Bluetooth service disconnected
09-09 13:36:10.750  2050  2050 D PanService: Received stop request...Stopping profile...
09-09 13:36:10.751  2050  2050 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27cd5b92
09-09 13:36:10.751  6732  6732 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 13:36:10.752  6732  6732 D PanProfile: Bluetooth service disconnected
09-09 13:36:10.752  2050  2050 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 13:36:10.753  2050  2050 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 13:36:10.753  2050  2050 D BtGatt.GattService: stop()
09-09 13:36:10.753  2050  2050 D BtGatt.AdvertiseManager: advertise clients cleared
09-09 13:36:10.754  2050  2050 D LGBluetoothGattAdapter: [BTUI] LGBluetoothGattAdapter cleanup
09-09 13:36:10.754  2050  2050 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27cd5b92
09-09 13:36:10.754  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - Message: 1
09-09 13:36:10.754  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-09 13:36:10.754  2050  2050 D BluetoothAdapterService(667769746): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-09 13:36:10.754  2050  2050 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:36:10.754  2050  2050 D BluetoothAdapterState: isTurningOffRadio()=false
09-09 13:36:10.754  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:36:10.754  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-09 13:36:10.756  2050  2050 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
,09-09 13:36:10.756  2050  2050 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.756  2050  2050 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.756  2050  2050 D BluetoothAdapterService(667769746): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.758  2050  2050 D BluetoothMapService: Received stop request...Stopping profile...
09-09 13:36:10.758  2050  2050 D BluetoothMapService: stop()
09-09 13:36:10.759  2050  2050 D BluetoothMapEmailAppObserver: deinitObservers()
09-09 13:36:10.759  2050  2050 D BluetoothMapEmailAppObserver: removeReceiver()
09-09 13:36:10.760  2050  2050 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27cd5b92
09-09 13:36:10.761  6732  6732 D BluetoothMap: Proxy object disconnected
09-09 13:36:10.761  6732  6732 D MapProfile: Bluetooth service disconnected
09-09 13:36:10.764  2050  2050 D HeadsetStateMachine: Unbinding service...
09-09 13:36:10.765  2050  2050 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 13:36:10.765  2050  2050 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 13:36:10.765  2050  2050 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 13:36:10.765  2050  2050 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 13:36:10.766  2050  2050 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 13:36:10.766  2050  2050 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 13:36:10.766  2050  2050 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 13:36:10.766  2050  2050 D SapService: Received stop request...Stopping profile...
09-09 13:36:10.766  2050  2050 D SapService: Stopping Bluetooth SapService
09-09 13:36:10.766  2050  2050 D LGBluetoothSapAdapter: [BTUI] LGBluetoothSapAdapter cleanup
09-09 13:36:10.767  2050  2050 D LGBluetoothSapManager: [BTUI] terminateSapManager
09-09 13:36:10.768  2050  2050 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27cd5b92
,09-09 13:36:10.770  2050  2050 D **BluetoothFTPService: Received stop request...Stopping profile...
09-09 13:36:10.770  2050  2050 D **BluetoothFTPService: Stopping Bluetooth FTP Service
09-09 13:36:10.771  2050  2050 V BluetoothFTPServiceJni: closeFtpServerNative
09-09 13:36:10.771  2050  2050 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27cd5b92
09-09 13:36:10.772  1749  1749 D LgeBluetoothSimManager: [BTUI] SAP_DISABLE_EVT
09-09 13:36:10.773  2050  2050 D **OppService: Received stop request...Stopping profile...
09-09 13:36:10.773  2050  2050 D OppService: Stopping Bluetooth OppService
09-09 13:36:10.773  2050  2050 D OppService: cleanup OPP Service
09-09 13:36:10.773  2050  2050 W BluetoothOPPServiceJni: Cleaning up Bluetooth Opp Interface...
09-09 13:36:10.773  2050  2050 W BluetoothOPPServiceJni: Cleaning up Bluetooth OPP callback object
09-09 13:36:10.775  2050  2050 D OppService: remove callbacks and handler
09-09 13:36:10.775  2050  2050 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-09 13:36:10.775  2050  2050 D OppService: cleanup done
09-09 13:36:10.775  2050  2050 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27cd5b92
09-09 13:36:10.776  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - Message: 1
09-09 13:36:10.776  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-09 13:36:10.776  2050  2050 D BluetoothAdapterService(667769746): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-09 13:36:10.776  2050  2050 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:36:10.776  2050  2050 D BluetoothAdapterState: isTurningOffRadio()=false
09-09 13:36:10.776  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:36:10.776  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-09 13:36:10.776  2050  2050 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-09 13:36:10.777  2050  2050 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.777  2050  2050 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
,09-09 13:36:10.777  2050  2050 D BluetoothAdapterService(667769746): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.777  2050  2050 I BluetoothA2dpServiceJni: cleanupNative
09-09 13:36:10.777  2050  2050 I GKI_LINUX: GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
09-09 13:36:10.778  2050  3767 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-09 13:36:10.778  2050  2050 I GKI_LINUX: GKI_destroy_task(): task [A2DP-MEDIA] terminated
09-09 13:36:10.778  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - Message: 1
09-09 13:36:10.778  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-09 13:36:10.778  2050  2050 D BluetoothAdapterService(667769746): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-09 13:36:10.779  2050  2050 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:36:10.779  2050  2050 D BluetoothAdapterState: isTurningOffRadio()=false
09-09 13:36:10.779  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:36:10.779  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-09 13:36:10.779  2050  2050 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-09 13:36:10.779  2050  2050 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.779  2050  2050 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.779  2050  2050 D BluetoothAdapterService(667769746): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.781  2050  2050 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 13:36:10.781  2050  2050 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 13:36:10.781  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - Message: 1
09-09 13:36:10.781  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-09 13:36:10.781  2050  2050 D BluetoothAdapterService(667769746): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-09 13:36:10.781  2050  2050 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:36:10.781  2050  2050 D BluetoothAdapterState: isTurningOffRadio()=false
09-09 13:36:10.781  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:36:10.781  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-09 13:36:10.781  2050  2050 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-09 13:36:10.781  2050  2050 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.781  2050  2050 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.781  2050  2050 D BluetoothAdapterService(667769746): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.781  2050  2050 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 13:36:10.782  2050  2050 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 13:36:10.782  2050  2050 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 13:36:10.782  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - Message: 1
09-09 13:36:10.782  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-09 13:36:10.782  2050  2050 D BluetoothAdapterService(667769746),: onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-09 13:36:10.782  2050  2050 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:36:10.782  2050  2050 D BluetoothAdapterState: isTurningOffRadio()=false
,09-09 13:36:10.782  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:36:10.782  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-09 13:36:10.782  2050  2050 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-09 13:36:10.782  2050  2050 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.782  2050  2050 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.782  2050  2050 D BluetoothAdapterService(667769746): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.783  2050  2050 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 13:36:10.783  2050  2050 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 13:36:10.784  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - Message: 1
09-09 13:36:10.784  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-09 13:36:10.784  2050  2050 D BluetoothAdapterService(667769746): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
09-09 13:36:10.784  2050  2050 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:36:10.784  2050  2050 D BluetoothAdapterState: isTurningOffRadio()=false
09-09 13:36:10.784  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:36:10.784  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-09 13:36:10.784  2050  2050 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-09 13:36:10.784  2050  2050 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.784  2050  2050 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.784  2050  2050 D BluetoothAdapterService(667769746): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.784  2050  2050 V BluetoothMapService: Handler(): got msg=4
09-09 13:36:10.784  2050  2050 D BluetoothMapService: MAP Service closeService in
09-09 13:36:10.784  2050  2050 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 13:36:10.784  2050  2050 V BluetoothMapService: MAP Service closeService out
09-09 13:36:10.784  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - Message: 1
09-09 13:36:10.784  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-09 13:36:10.784  2050  2050 D BluetoothAdapterService(667769746): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-09 13:36:10.784  2050  2050 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:36:10.784  2050  2050 D BluetoothAdapterState: isTurningOffRadio()=false
09-09 13:36:10.784  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:36:10.784  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-09 13:36:10.784  2050  2050 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-09 13:36:10.784  2050  2050 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.784  2050  2050 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.784  2050  2050 D BluetoothAdapterService(667769746): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppSer,vice
09-09 13:36:10.785  2050  2050 D BluetoothMapService: cleanup()
09-09 13:36:10.785  2050  2050 D BluetoothMapService: MAP Service closeService in
09-09 13:36:10.785  2050  2050 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 13:36:10.785  2050  2050 V BluetoothMapService: MAP Service closeService out
09-09 13:36:10.785  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - Message: 1
09-09 13:36:10.785  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-09 13:36:10.785  2050  2050 D BluetoothAdapterService(667769746): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-09 13:36:10.785  2050  2050 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:36:10.785  2050  2050 D BluetoothAdapterState: isTurningOffRadio()=false
09-09 13:36:10.785  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:36:10.785  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-09 13:36:10.785  2050  2050 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-09 13:36:10.785  2050  2050 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.785  2050  2050 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.785  2050  2050 D BluetoothAdapterService(667769746): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.785  2050  2050 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
09-09 13:36:10.785  2050  2050 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
09-09 13:36:10.785  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - Message: 1
09-09 13:36:10.785  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-09 13:36:10.785  2050  2050 D BluetoothAdapterService(667769746): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
,09-09 13:36:10.785  2050  2050 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:36:10.785  2050  2050 D BluetoothAdapterState: isTurningOffRadio()=false
09-09 13:36:10.785  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:36:10.785  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-09 13:36:10.785  2050  2050 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-09 13:36:10.785  2050  2050 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.786  2050  2050 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
,09-09 13:36:10.786  2050  2050 D BluetoothAdapterService(667769746): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:36:10.786  2050  2050 D BluetoothFTPService: cleanup FTP Service
09-09 13:36:10.786  2050  2050 V BluetoothFTPServiceJni: closeFtpServerNative
09-09 13:36:10.786  2050  2050 V BluetoothFTPServiceJni: cleanupNative
09-09 13:36:10.786  2050  2050 W BluetoothFTPServiceJni: Cleaning up Bluetooth FTP Server Interface...
09-09 13:36:10.786  2050  2050 W BluetoothFTPServiceJni: Cleaning up Bluetooth FTP callback object
09-09 13:36:10.786  2050  2050 D BluetoothFTPService: BluetoothFtpBinder.cleanup()
09-09 13:36:10.786  2050  2050 D BluetoothFTPService: cleanup done,
09-09 13:36:10.786  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - Message: 1
09-09 13:36:10.786  2050  2050 D BluetoothAdapterService(667769746): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-09 13:36:10.786  2050  2050 D BluetoothAdapterService(667769746): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
,09-09 13:36:10.786  2050  2050 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:36:10.786  2050  2050 D BluetoothAdapterState: isTurningOffRadio()=false
09-09 13:36:10.786  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:36:10.786  2050  2050 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
,09-09 13:36:10.786  2050  2050 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-09 13:36:10.786  2050  2050 D BluetoothAdapterService(667769746): onProfileServiceStateChange() - All profile services stopped...
09-09 13:36:10.788  2050  2178 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-09 13:36:10.788  2050  2178 D BluetoothAdapterProperties: Setting state to 10,
09-09 13:36:10.788  2050  2178 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 13:36:10.788  2050  2178 D BluetoothAdapterService(667769746): updateAdapterState() - Broadcasting state to 1 receivers.
09-09 13:36:10.788   957  1056 D BluetoothManagerService: Message: 60
09-09 13:36:10.788   957  1056 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10,
09-09 13:36:10.789   957  1056 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-09 13:36:10.789  2050  2178 I BluetoothAdapterState: Entering OffState
09-09 13:36:10.789  2050  2050 D OppService: cleanup OPP Service
09-09 13:36:10.789  2050  2050 D OppService: remove callbacks and handler
,09-09 13:36:10.789  2050  2050 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-09 13:36:10.789  2050  2050 D OppService: cleanup done
09-09 13:36:10.789  1749  2979 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:36:10.790  6732  6755 D BluetoothMap: onBluetoothStateChange: up=false
,09-09 13:36:10.791  6732  6754 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 13:36:10.791  1749  1764 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:36:10.792  1749  2368 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:36:10.792   957  1056 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 13:36:10.792  6732  6755 D BluetoothPan: onBluetoothStateChange on: false
09-09 13:36:10.793   957  1056 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:36:10.793  6732  6754 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 13:36:10.793   957  1056 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,09-09 13:36:10.795  1802  1802 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:36:10.799  6732  6732 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true,
09-09 13:36:10.800  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:10.800  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:10.801  6732  6732 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-09 13:36:10.802  6732  6732 D LGBluetoothEventManager: [BTUI] clear device connection state
09-09 13:36:10.802  2050  2072 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:10.802  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:10.805  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:10.805  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
09-09 13:36:10.805  1370  1370 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
09-09 13:36:10.810  6732  6732 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 13:36:10.812  1802  2004 D LGBluetoothAPIService: Message: 2
09-09 13:36:10.812  1802  2004 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3156b669 mBinding = false
,09-09 13:36:10.818  1802  2004 D LGBluetoothAPIService: Sending unbind request.
09-09 13:36:10.819  2050  2050 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 13:36:10.819  2050  2050 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:10.819  2050  2050 V BluetoothPbapReceiver: ***********state = 10
09-09 13:36:10.820  6732  6732 D DockEventReceiver: finishStartingService: stopping service
09-09 13:36:10.820  2050  2050 D LGBluetoothAPIServer: [BTUI] onUnbind()
09-09 13:36:10.820  2050  2050 D LGBluetoothAPIServer: [BTUI] cleanup() done
09-09 13:36:10.820  2050  2050 D LGBluetoothAPIServer: [BTUI] onDestroy()
09-09 13:36:10.824  2050  2072 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:10.825  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
,09-09 13:36:10.830  6732  6732 D BluetoothPermissionRequest: onReceive
09-09 13:36:10.834  6732  6732 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-09 13:36:10.835  6732  6732 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-09 13:36:10.845   957  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3db0aea1 type 2 when 160329 com.google.android.gms} when 160329
,09-09 13:36:10.853  2050  2050 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 13:36:10.855  2050  2050 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:10.862  7307  7307 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
,09-09 13:36:10.866  1730  1730 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-09 13:36:10.876  1730  7361 D EasyUnlockInitService: Handling intent for initializer IntentService.
09-09 13:36:10.878  1730  1730 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-09 13:36:10.915  7018  7018 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
09-09 13:36:10.915  7018  7018 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-09 13:36:11.027   957  1901 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7367 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:11.062  7366  7366 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=37 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-09 13:36:11.102  7018  7377 D edo     : Opening database auth.proximity.permit_store...
,09-09 13:36:11.107  1730  7361 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
09-09 13:36:11.157  7366  7366 I dex2oat : dex2oat took 91.591ms (threads: 4)
,09-09 13:36:11.170  7239  7306 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:36:11.170  7239  7306 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:36:11.170  7239  7306 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:36:11.170  7239  7306 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:36:11.170  7239  7306 I Adreno-EGL: Remote Branch: 
09-09 13:36:11.170  7239  7306 I Adreno-EGL: Local Patches: 
09-09 13:36:11.170  7239  7306 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:36:11.315   285  1581 I WVCdm   : CdmEngine::OpenSession
,09-09 13:36:11.342   957  1801 I ActivityManager: Process com.uei.lg.quicksetsdk.lite (pid 7116) has died
,09-09 13:36:11.386  7367  7367 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:36:11.502   957  1901 I ActivityManager: Process com.lge.appbox.client (pid 7093) has died
,09-09 13:36:11.828   957  1293 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7403 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:11.902   957  1901 I ActivityManager: Process com.google.android.talk (pid 6813) has died
,09-09 13:36:11.992  7403  7403 I MusicStore: Database version: 120
,09-09 13:36:12.041   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:12.041   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,09-09 13:36:12.041   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:12.042  7403  7403 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-09 13:36:12.141   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:12.141   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,09-09 13:36:12.141   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:12.141  7403  7403 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-09 13:36:12.145   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:12.145   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-09 13:36:12.145   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:12.145  7403  7403 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-09 13:36:12.170  7403  7403 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 13:36:12.170  7403  7403 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 13:36:12.223  7403  7403 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 13:36:12.305  7403  7403 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-09 13:36:12.306  7403  7403 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5458c02: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-09 13:36:12.306  7403  7403 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-09 13:36:12.306  7403  7403 D AndroidMusic: GMSCore installation verified
,09-09 13:36:12.312  7403  7403 I ConfigStore: Config Database version: 1
,09-09 13:36:12.372  7403  7417 I art     : CheckpointMarkThreadRoots callback created = 0xaaf23290
,09-09 13:36:12.407  7403  7417 I art     : CheckpointMarkThreadRoots callback created = 0xaaf23270
,09-09 13:36:12.425  7403  7403 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-09 13:36:12.430  7403  7403 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
09-09 13:36:12.438  7403  7403 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 13:36:12.475  7403  7403 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 13:36:12.518   957  2125 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7446 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
09-09 13:36:12.550  7403  7403 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,09-09 13:36:12.566  7403  7403 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:36:12.617   285  1584 I WVCdm   : CdmEngine::CloseSession
,09-09 13:36:12.621  7403  7433 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
09-09 13:36:12.646  7446  7446 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:12.646  7446  7446 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:36:12.647  7446  7446 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-09 13:36:12.682   285  1581 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-09 13:36:12.684   285  1581 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-09 13:36:12.684   285  1581 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-09 13:36:12.684   285  1581 I WVCdm   : CdmEngine::GenerateKeyRequest
09-09 13:36:12.689   285  1581 D WVCdm   : PrepareKeyRequest: nonce=2974615087
09-09 13:36:12.726  7446  7446 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-09 13:36:12.743  7446  7446 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,09-09 13:36:13.082   957  2125 I ActivityManager: Process com.google.android.apps.magazines (pid 7201) has died
,09-09 13:36:13.149  7446  7446 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-09 13:36:13.169  7063  7063 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:13.169  7063  7063 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-09 13:36:13.171  7063  7063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:36:13.174  7063  7063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:36:13.210   957  1819 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7474 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-09 13:36:13.221  7063  7480 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:36:13.223  7063  7481 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:13.223  7063  7481 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:36:13.253  7063  7480 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,09-09 13:36:13.269  7063  7480 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,09-09 13:36:13.274  7063  7063 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
09-09 13:36:13.275  7063  7063 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
09-09 13:36:13.275  7063  7063 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:36:13.276  7063  7063 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:36:13.283  7063  7063 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,09-09 13:36:13.294  7446  7446 I HubEmail: JNI_OnLoad()
09-09 13:36:13.294  7446  7446 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:36:13.294  7446  7446 I HubEmail: registerNatives()
09-09 13:36:13.294  7446  7446 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:36:13.294  7446  7446 I HubEmail: registerNativeMethods()
09-09 13:36:13.294  7446  7446 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:36:13.294  7446  7446 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-09 13:36:13.299  7446  7503 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:36:13.315  7474  7474 I AppUp4:AppBoxCP: onCreate
09-09 13:36:13.316  7474  7474 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-09 13:36:13.324  7474  7474 I AppUp4:DB:  setFingerPrint start
09-09 13:36:13.325  7474  7474 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
09-09 13:36:13.331  7474  7474 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
09-09 13:36:13.331  7474  7474 I AppUp4:DB:  SDK version = 21
,09-09 13:36:13.331  7474  7474 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-09 13:36:13.333  7474  7474 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-09 13:36:13.334  7474  7474 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 13:36:13.335  7474  7474 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:13.336  7474  7474 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 13:36:13.336  7474  7474 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 13:36:13.340  7474  7474 I AppUp4:CustModeStarterReceiver: onReceive
09-09 13:36:13.340  7474  7474 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:13.343  7474  7474 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@108257c7
09-09 13:36:13.343  7474  7474 D AppUp4:CustFacade: isCustomizationCompleted : false
,09-09 13:36:13.349  7474  7474 D AppUp4:CustFacade: isSimDevice : true
09-09 13:36:13.350  7474  7474 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:36:13.350  7474  7474 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-09 13:36:13.351  7474  7474 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-09 13:36:13.351  7474  7504 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-09 13:36:13.351  7474  7504 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-09 13:36:13.351  7474  7504 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-09 13:36:13.352   957  1801 I ActivityManager: Killing 7133:com.google.android.setupwizard/u0a38 (adj 15): empty #11
09-09 13:36:13.523   957  2062 W libprocessgroup: failed to open /acct/uid_10038/pid_7133/cgroup.procs: No such file or directory
09-09 13:36:13.524  3187  3187 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 13:36:13.524  3187  3187 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:13.524  3187  3187 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-09 13:36:13.562   957  1873 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7507 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,09-09 13:36:13.697  7507  7507 D PhoneMonitor: Register our PhoneStateListener
,09-09 13:36:13.711  7507  7507 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-09 13:36:13.717  7507  7507 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 13:36:13.719   957  1379 I ActivityManager: Killing 7163:com.lge.drmservice/u0a51 (adj 15): empty #11
,09-09 13:36:13.750  7507  7507 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-09 13:36:13.750  7507  7507 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-09 13:36:13.750  7507  7507 D TelephonyAutoProfiling: [parse] Load xml
09-09 13:36:13.754  7507  7507 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-09 13:36:13.754  7507  7507 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,09-09 13:36:13.776  7507  7507 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-09 13:36:13.804   957  1874 W libprocessgroup: failed to open /acct/uid_10051/pid_7163/cgroup.procs: No such file or directory
,09-09 13:36:13.812  3277  3277 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:13.825  3277  3277 V DownloadManager: DownloadService onCreate
09-09 13:36:13.826  3277  7540 I DownloadManager: in removeSpuriousFiles
,09-09 13:36:13.828  3277  7540 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-09 13:36:13.829  3277  7540 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@39dc6084 on behalf of 3277
09-09 13:36:13.831  3277  7540 I DownloadManager: in trimDatabase
09-09 13:36:13.831  3277  7540 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-09 13:36:13.833  3277  3277 I NotificationManager: com.android.providers.downloads: cancelAll by com.android.providers.downloads
09-09 13:36:13.834  3277  7540 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3255806d on behalf of 3277
09-09 13:36:13.858   957  1783 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7546 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-09 13:36:13.860  3277  3277 V DownloadManager: DownloadService onStartCommand
09-09 13:36:13.881   310   310 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 21.759ms
09-09 13:36:13.883  3277  7541 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,09-09 13:36:13.885  3277  7541 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3d0100f0 on behalf of 3277
09-09 13:36:13.904   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 22.277ms
,09-09 13:36:13.926   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.464ms
,09-09 13:36:13.940   957  1283 V AlarmManager: RTC_WAKEUP set : Alarm{175f0009 type 0 when 1473420973936 com.google.android.googlequicksearchbox} when 1473420973936
,09-09 13:36:13.946  3277  3277 V DownloadManager: DownloadService onDestroy
09-09 13:36:13.952   957  1379 I ActivityManager: Killing 7337:com.android.chrome/u0a48 (adj 15): empty #11
,09-09 13:36:14.103   957  1874 W libprocessgroup: failed to open /acct/uid_10048/pid_7337/cgroup.procs: No such file or directory
,09-09 13:36:14.107  2866  2866 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:14
09-09 13:36:14.109  2866  2866 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 13:36:14.109  2866  2866 D WeatherAncestor: connectivity changed - connection : true
09-09 13:36:14.109  2866  2866 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 13:36:14.109  2866  2866 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:14
09-09 13:36:14.111  2866  2866 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:14.111  2866  2866 D WeatherService: 2 : shouldTimeTickRegistered : false
09-09 13:36:14.163   957  2125 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7567 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-09 13:36:14.209   296   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,09-09 13:36:14.338  7567  7567 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 13:36:14.646  7567  7605 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-09 13:36:14.646  7567  7605 I Babel_SMS: MmsConfig.loadMmsSettings
,09-09 13:36:14.660  6450  7280 E io.jxcore.node.ConnectivityMonitorTest: BT is not enabled after 5s!
09-09 13:36:14.663  6450  6534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:14.663  7567  7605 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-09 13:36:14.663  7567  7605 I Babel_SMS: MmsConfig.loadFromDatabase
,09-09 13:36:14.677  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:14.677  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:14.677  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:14.677  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:36:14.677  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32497631 removed from the list
09-09 13:36:14.677  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:14.677  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26307116 removed from the list
09-09 13:36:14.677  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:14.677  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:14.688  7567  7605 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-09 13:36:14.688  7567  7605 I Babel_SMS: MmsConfig.loadFromResources
09-09 13:36:14.689  7567  7605 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-09 13:36:14.690  7567  7605 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-09 13:36:14.693  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:36:14.693  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dadb484 added. We now have 3 listener(s)
09-09 13:36:14.693   957  1783 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:14.696  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-09 13:36:14.696  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:36:14.696  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:36:14.697  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:36:14.697  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@320e446d added. We now have 3 listener(s)
09-09 13:36:14.697  6450  6534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:36:14.697  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:36:14.702  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:14.704  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:14.704  6450  6534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:14.704  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:14.704  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:14.704  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:14.704  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:14.704  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:14.704  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:14.704  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:14.704  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:14.704  6450  6534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:14.704  6450  6534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:36:14.706  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:14.708   957  1901 D WifiServiceImplEx: setWifiEnabled: false pid=6450, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
09-09 13:36:14.708   957  1901 D WifiService: setWifiEnabled: false pid=6450, uid=10030
09-09 13:36:14.709  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:14.783   285   285 I WVCdm   : CdmEngine::CloseSession
,09-09 13:36:14.788   285   285 I WVCdm   : L3 Terminate.
,09-09 13:36:14.790   957  2125 I art     : Explicit concurrent mark sweep GC freed 24362(1141KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.679ms total 178.773ms
09-09 13:36:14.795   957   957 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:36:14.795   957   957 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:36:14.795   957   957 D Ulp_jni : JNI:system_update. Event-4
09-09 13:36:14.798   957  1306 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 13:36:14.798   957  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:36:14.798  7239  7306 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:36:14.798  7239  7306 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:36:14.798  7239  7306 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:36:14.798  7239  7306 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:36:14.798  7239  7306 I Adreno-EGL: Remote Branch: 
09-09 13:36:14.798  7239  7306 I Adreno-EGL: Local Patches: 
09-09 13:36:14.798  7239  7306 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:36:14.810   957  1305 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:14.811   957  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:14.822  7567  7584 I art     : CheckpointMarkThreadRoots callback created = 0xaaf21cc0
,09-09 13:36:14.826   281  1048 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:36:14.826   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 7
09-09 13:36:14.828   957  6941 D DhcpStateMachine: RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:14.854   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 10
09-09 13:36:14.854   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 7
,09-09 13:36:14.859   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:14.860   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:14.860   957  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 13:36:14.860   957  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-09 13:36:14.860   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:14.860   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:14.867  7239  7306 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:36:14.867  7239  7306 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:36:14.867  7239  7306 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:36:14.867  7239  7306 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:36:14.867  7239  7306 I Adreno-EGL: Remote Branch: 
09-09 13:36:14.867  7239  7306 I Adreno-EGL: Local Patches: 
09-09 13:36:14.867  7239  7306 I Adreno-EGL: Reconstruct Branch: 
09-09 13:36:14.867  7567  7567 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
09-09 13:36:14.868  7567  7567 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
09-09 13:36:14.868  7567  7567 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
09-09 13:36:14.868  7567  7567 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
09-09 13:36:14.868  7567  7567 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
09-09 13:36:14.868  7567  7567 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
09-09 13:36:14.868  7567  7567 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
09-09 13:36:14.868  7567  7567 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
09-09 13:36:14.868  7567  7567 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
09-09 13:36:14.868  7567  7567 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
09-09 13:36:14.868  7567  7567 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
09-09 13:36:14.868  7567  7567 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
09-09 13:36:14.868  7567  7567 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
09-09 13:36:14.868  7567  7567 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
09-09 13:36:14.868  7567  7567 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
09-09 13:36:14.868  7567  7567 D SensorManager: found sensor: Motion Accel, handle=46
,09-09 13:36:14.882   957  1874 I ActivityManager: Process com.google.android.apps.plus (pid 7367) has died
09-09 13:36:14.883   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:14.884   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:14.886   957  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 13:36:14.888   957  1305 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:14.888   957  1305 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:14.889   957  1305 D LGWifiP2pService: P2pDisablingState
09-09 13:36:14.889   957  1305 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:14.889   957  1305 D LGWifiP2pService: p2p socket connection lost
09-09 13:36:14.889   957  1305 D LGWifiP2pService: P2pDisabledState
,09-09 13:36:14.891   957   957 D WifiHS20: hidePasspointNotification off =false
09-09 13:36:14.898   957  1305 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:14.898   957  1305 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:14.902  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:36:14.904   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:14.904   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:14.904   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:36:14.904   957   957 D WifiHS20: hidePasspointNotification off =false
09-09 13:36:14.904   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:14.904   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:14.904   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:36:14.904   957   957 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 13:36:14.904   957   957 D RttService: SCAN_AVAILABLE : 1
09-09 13:36:14.905   957  1325 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:14.905   957  1326 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:14.906  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:14.907  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:14.907 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:14.909  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:36:14.910  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:14.910  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:14.91 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:14.910  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:36:14.921  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:14.921  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:14.921  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:14.923  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:14.923  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:14.923  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:14.924  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:36:14.928  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:14.929  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:14.929  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:14.929  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:14.929  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:14.929  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:14.929  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
09-09 13:36:14.930  7567  7584 I art     : CheckpointMarkThreadRoots callback created = 0xaae47db0
09-09 13:36:14.931  1802  1802 D WfdsService: WifiP2pState is changed : false
09-09 13:36:14.931  1802  2113 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-09 13:36:14.931  1802  2113 D WfdsJNI : doCommand: P2P_STOP_FIND
09-09 13:36:14.933   281  1048 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:36:14.934  1802  2113 D WfdsService: Set the WFDS Monitor: false
09-09 13:36:14.934   957  1313 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-09 13:36:14.934   957  1313 D DSQN    : disableDataServiceNotify
09-09 13:36:14.934   957  1313 D DSQN    : stop dsqn bin
09-09 13:36:14.935  1802  2113 D WfdsMonitor: WFDS Monitor is stopped
09-09 13:36:14.935  1802  2113 D WfdsService: STATE : WfdsDisabledState - enter
09-09 13:36:14.935  1802  2113 D WfdsService: WFDS: Scanner is paused
09-09 13:36:14.935  1802  6859 D CtrlSupplicant: Received on exit socket, terminate
09-09 13:36:14.935  1802  6859 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-09 13:36:14.936  1802  2113 D WfdsDiscoveryStore: Clear Discovery Method Map: ScanAlwaysMode false
09-09 13:36:14.937  1802  6859 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-09 13:36:14.937  1802  6859 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
,09-09 13:36:14.939  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:14.940  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:14.939 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:14.940  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:36:14.940   957   957 D WifiHS20: hidePasspointNotification off =false
09-09 13:36:14.941   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:14.941   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:14.941   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:36:14.941  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:36:14.942  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:14.942 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:14.942  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:36:14.944   957   957 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-09 13:36:14.944   957   957 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:14.944   957   957 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-09 13:36:14.945  1802  2111 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-09 13:36:14.945  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:14.947  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:14.947  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:14.947  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:14.947  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:14.947  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:36:14.947  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:14.947  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:14.947  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:14.947  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:14.947  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:14.948  6450  6450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:14.949  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:14.949  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09, 13:36:14.949  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:14.949  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:14.949  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:14.949  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:14.950  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:14.950  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:14.950  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:14.950  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:14.950  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:36:14.950  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:14.950  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:14.950  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:14.950  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:14.952  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:14.952  6450  6450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:36:14.956   957  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-09 13:36:14.956   957  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:14.956   957  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:14.957   957  1313 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:14.957   957  6939 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:14.957   957  6939 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:14.957   957  6939 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-09 13:36:14.959   957  1313 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-09 13:36:14.960  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:14.960  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:14.960  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:14.960   957  1313 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-09 13:36:14.960   957  1313 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 13:36:14.960   957  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:36:14.960  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-09 13:36:14.961  1370  1740 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 13:36:14.963  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:14.963  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:14.963  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:14.963  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:14.963  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:36:14.963  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:14.963  64,50  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:14.963  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:14.963  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:14.963   957  1304 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 13:36:14.964  1837  1837 W QCNEJ   : |CORE| No family connected
09-09 13:36:14.964  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:14.964  6450  6450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:14.965   957  1056 D Tethering: MasterInitialState.processMessage what=3
09-09 13:36:14.965   957  1313 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:14.966   957  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:36:14.966   957  1313 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:14.967   957  1304 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 13:36:14.968  1837  1837 W QCNEJ   : |CORE| No family connected
09-09 13:36:14.968  1837  1837 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
09-09 13:36:14.968   957  1056 D Tethering: MasterInitialState.processMessage what=3
09-09 13:36:14.968   957  1313 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:14.969   957  1313 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:14.969  1837  1837 I QCNEJ   : |CORE| sendDefaultNwMsg: default = -1
09-09 13:36:14.969  1749  1749 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:14.970  1749  1749 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
09-09 13:36:14.970   957  1306 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:14.970   957  1306 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:36:14.970   957  1313 D NetworkManagementService: Removing idletimer
09-09 13:36:14.970   957  1313 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:14.971   957  1313 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-09 13:36:14.985  1370  1370 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:36:14.986  1370  1370 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
09-09 13:36:14.991  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:14.991  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:14.991  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:14.993  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,09-09 13:36:14.993  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:14.993  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:15.007  7567  7567 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:15.009  1370  1370 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:36:15.010  1370  1370 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
,09-09 13:36:15.013  7567  7567 I Babel_Crash: startup - clean
09-09 13:36:15.013  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:15.013  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:15.013  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:15.015  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:15.015  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:15.015  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:15.055   957  6941 D DhcpStateMachine: StoppedState
09-09 13:36:15.055   957  6941 D DhcpStateMachine: StoppedState{ when=-135ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:36:15.056  7567  7617 I Babel   : deleted: false for 0
09-09 13:36:15.102   281  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
09-09 13:36:15.103   281  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 5
,09-09 13:36:15.104  6796  6796 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-09 13:36:15.104  6796  6796 I wpa_supplicant: monitor socket send errors count : 1
09-09 13:36:15.104  6796  6796 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1802-4\x00 that cannot receive messages
09-09 13:36:15.105   281  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 10
09-09 13:36:15.105   281  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 7
09-09 13:36:15.106   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:15.106   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:15.120  6796  6796 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 13:36:15.121  6796  6796 W wpa_supplicant: USIM:  scard_deinit function
09-09 13:36:15.131   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:36:15.131   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,09-09 13:36:15.132   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:15.132   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:15.171   957  1901 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7619 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:15.204  7567  7567 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,09-09 13:36:15.213  7567  7567 W AudioCapabilities: Unsupported mime audio/adpcm
09-09 13:36:15.214  7567  7567 W AudioCapabilities: Unsupported mime audio/g726
09-09 13:36:15.214  7567  7567 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-09 13:36:15.215  7567  7567 W AudioCapabilities: Unsupported mime audio/wma-voice
09-09 13:36:15.217  7567  7567 W VideoCapabilities: Unsupported mime video/mjpg
,09-09 13:36:15.223  7567  7567 W VideoCapabilities: Unsupported mime video/theora
,09-09 13:36:15.230  7018  7188 I CheckinUtil: Classify the device as Phone.
,09-09 13:36:15.262   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,09-09 13:36:15.270  7567  7567 W AudioCapabilities: Unsupported mime audio/evrc
09-09 13:36:15.272  7567  7567 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 13:36:15.273   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 5
09-09 13:36:15.274  7567  7567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:36:15.274  6796  6796 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-09 13:36:15.280   957  1056 D Tethering: InitialState.processMessage what=4
09-09 13:36:15.281   957  1056 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-09 13:36:15.283  7567  7567 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-09 13:36:15.284  7567  7567 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 13:36:15.285  7567  7567 W AudioCapabilities: Unsupported mime audio/evrc
09-09 13:36:15.304  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:15.304  6450  6534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:15.304  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:15.304  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:15.304  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:36:15.304  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:15.304  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:15.304  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:15.304  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:15.305  7567  7567 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-09 13:36:15.306   957  1801 D WifiServiceImplEx: setWifiEnabled: true pid=6450, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
09-09 13:36:15.306   957  1801 D WifiService: setWifiEnabled: true pid=6450, uid=10030
,09-09 13:36:15.320   957  1312 D WifiController: WifiController msg { when=-1ms what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 476ms
,09-09 13:36:15.320   957   957 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:36:15.320   957   957 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:36:15.320   957   957 D Ulp_jni : JNI:system_update. Event-4
09-09 13:36:15.328  7567  7567 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 13:36:15.338  7567  7567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:36:15.339  7567  7567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:36:15.343  7567  7567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:36:15.349  7567  7567 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:36:15.352  7018  7188 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:15.353  7018  7188 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:15.353  7018  7188 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:15.353  7018  7188 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:15.354   281  1043 E BandwidthController: [LG DATA] No such appUid: 10006
09-09 13:36:15.354   281  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-09 13:36:15.354   281  7641 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
09-09 13:36:15.354   281  7641 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:15.354   281  7641 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
09-09 13:36:15.355   957  1054 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-09 13:36:15.356  7018  7188 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-09 13:36:15.357  7567  7567 I vclib   : onServiceConnected
09-09 13:36:15.357  7567  7567 W Babel   : Attempted to change video mute state without an active call.
09-09 13:36:15.362  7567  7642 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-09 13:36:15.366  7018  7188 I CheckinChimeraService: Checking schedule, now: 1473420975366 next: 1473420985357
09-09 13:36:15.366  7018  7188 I CheckinChimeraService: active receiver: disabled
09-09 13:36:15.384   957  1306 D WifiOffDelayIfNotUsed: stopMonitoring
,09-09 13:36:15.386  1802  1802 D WfdsService: Supplicant Connection state is changed : false
09-09 13:36:15.386  1802  2113 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-09 13:36:15.386  1802  2113 D WfdsService: Set the WFDS Monitor: false
09-09 13:36:15.386  1802  2113 D WfdsMonitor: WFDS Monitor is stopped
09-09 13:36:15.387  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:36:15.387  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:15.387 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:15.387  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:36:15.390   957   957 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-09 13:36:15.390   957  1310 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-09 13:36:15.390   957  1310 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-09 13:36:15.391  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:15.391  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:15.391  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:15.391  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-09 13:36:15.391  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:15.392  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:15.392  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:15.392  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:15.392  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:36:15.392  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:15.392  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:15.392  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:15.392  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:15.394  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:15.394  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:15.394  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:15.394  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:15.394  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:36:15.394  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:15.394  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:15.394  6450  6450 V io.jxcore.n,ode.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:15.394  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:15.394  1730  2588 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:15.395  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:15.402  7567  7567 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:15.405  7567  7567 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
09-09 13:36:15.411  7018  7643 I CheckinChimeraService: Checking schedule, now: 1473420975411 next: 1473420985357
,09-09 13:36:15.411  7018  7643 I CheckinChimeraService: active receiver: disabled
,09-09 13:36:15.542   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:15.542   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 13:36:15.542   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:36:15.542  7619  7647 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-09 13:36:15.545   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:15.545   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:36:15.545   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:15.546  7619  7647 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 13:36:15.559   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:15.559   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 13:36:15.559   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:36:15.560  7619  7648 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-09 13:36:15.563   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:15.563   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:36:15.563   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:15.564  7619  7648 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 13:36:15.569  7619  7619 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 13:36:15.569  7619  7619 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 13:36:15.569  7619  7619 I GAv4    :   adb logcat -s GAv4
09-09 13:36:15.588  7619  7619 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:36:15.620  7619  7619 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:36:15.625  7619  7650 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:36:15.801   957  1312 D WifiController: DEFERRED_TOGGLE handled
09-09 13:36:15.802   957  1306 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-09 13:36:15.803   957  1306 E WifiHW  : Wifi MAC Address = a0:39:f7:70:12:80
09-09 13:36:15.803   957  1306 E WifiHW  : wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
09-09 13:36:15.803   957  1306 E WifiHW  : band=b
09-09 13:36:15.803   957  1306 E WifiHW  : ": cur_etheraddr=a0:39:f7:70:12:80
09-09 13:36:15.805   281  1048 D SoftapController: Softap fwReload - Ok
09-09 13:36:15.806   957  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:15.806   957  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:15.806   281  1048 D CommandListener: Setting iface cfg
09-09 13:36:15.807   281  1048 D CommandListener: Trying to bring down wlan0
09-09 13:36:15.807   281  1048 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:36:15.809   957  1306 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-09 13:36:15.813  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:36:15.813  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:15.813 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:15.813  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:36:15.815   957  1306 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-09 13:36:15.818   957   957 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-09 13:36:15.821  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:15.821  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:15.822  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:15.822  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:15.822  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-09 13:36:15.823  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:15.824  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:15.841  7667  7667 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 13:36:15.917  7667  7667 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 13:36:15.917  7667  7667 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-09 13:36:15.925  7619  7619 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
09-09 13:36:15.965  7619  7619 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5460-5463)
,09-09 13:36:15.965  7619  7619 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 13:36:15.972  7619  7619 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {daa95fa}
09-09 13:36:15.973  7619  7619 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:36:15.973  7619  7619 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 13:36:15.991  7619  7619 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 13:36:15.992  7619  7619 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:36:15.994  7619  7619 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 13:36:16.799   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,09-09 13:36:16.799   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:36:16.803   957  1056 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 13:36:16.818  7619  7619 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-09 13:36:16.823  7619  7619 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:36:16.823  7619  7619 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:36:16.824  7619  7619 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:36:16.824  7619  7619 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:36:16.824  7619  7619 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:36:16.824  7619  7619 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:36:16.824  7619  7619 I Adreno-EGL: Remote Branch: 
09-09 13:36:16.824  7619  7619 I Adreno-EGL: Local Patches: 
09-09 13:36:16.824  7619  7619 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:36:16.840  7667  7667 E wpa_supplicant: USIM:  scard_init function
,09-09 13:36:16.842  7667  7667 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 13:36:16.843   281  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
09-09 13:36:16.844   281  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 9
09-09 13:36:16.845   281  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
09-09 13:36:16.846   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:16.846   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:16.901  7667  7667 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-09 13:36:16.912   957  1306 D WifiStateMachine: MAC Addr from driver = a0:39:f7:70:12:80
09-09 13:36:16.912   957  1306 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-09 13:36:16.917   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:36:16.920  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:36:16.921  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:16.92 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:16.921  7667  7667 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-09 13:36:16.921  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:36:16.917   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:16.922   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:16.922   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:16.922   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:36:16.923   957   957 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-09 13:36:16.923   957   957 E WifiServerServiceExt: sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
09-09 13:36:16.923   957  1310 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-09 13:36:16.925  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:16.925  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:16.925  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:16.925  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:16.925  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:16.925  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:16.925  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:16.925  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:16.925  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:16.925  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:36:16.925  6450  6450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:16.926  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:16.926  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:16.926  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:16.926  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-09 13:36:16.928  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:16.928  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:16.928  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:16.928  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:16.928  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
09-09 13:36:16.928  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:16.928  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:16.928  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:16.928  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:16.931  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:36:16.933  6450  6450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:16.935  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:16.935  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:16.935  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:16.935  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:16.935  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:16.935  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:16.935  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:16.935  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:16.935  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:16.936  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:16.936  6450  6450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:16.958   957  1306 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-09 13:36:16.958   957  1306 D WifiStateMachine: enableVerboseLogging : level 2
,09-09 13:36:16.961   957  1306 D WifiStateMachine: Setting OUI to DA-A1-19
,09-09 13:36:16.962   957  1306 D WifiNative-HAL: Setting external_sim to 1
09-09 13:36:16.962   957  1306 I WifiNative-HAL: startHal
09-09 13:36:16.962  1802  1802 D WfdsService: Supplicant Connection state is changed : true
09-09 13:36:16.963  1802  2113 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-09 13:36:16.963  1802  2113 D WfdsService: Set the WFDS Monitor: true
09-09 13:36:16.963  1802  2113 D WfdsMonitor: WfdsMonitorThread create
09-09 13:36:16.963  1802  2113 D WfdsMonitor: WFDS Monitor is created and started
09-09 13:36:16.963  1802  2113 D WfdsService: WiFi: Supplicant connection re-established
09-09 13:36:16.964  7567  7567 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:16.964   957  1306 D wifi    : setting scan oui 0x9d82d4c0
,09-09 13:36:16.964   957  1306 D WifiHAL : Sending mac address OUI
09-09 13:36:16.965   957  1306 E WifiHAL : failed to set scanning mac OUI; result = -95
09-09 13:36:16.965   957  1306 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:36:16.965   957  1306 I WifiNative-HAL: startHal
09-09 13:36:16.965   957  1306 D wifi    : setting scan oui 0x9d82d4c0
09-09 13:36:16.965   957  1306 D WifiHAL : Sending mac address OUI
09-09 13:36:16.965   957  1306 E WifiHAL : failed to set scanning mac OUI; result = -95
09-09 13:36:16.965  1802  7689 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-09 13:36:16.966  1802  7689 E CtrlSupplicant: Succeed to open control connection
09-09 13:36:16.966  1802  7689 E CtrlSupplicant: Succeed to open monitor connection
09-09 13:36:16.967  1802  7689 D WfdsMonitor: Supplicant connection established
09-09 13:36:16.967  1802  2113 D WfdsService: Connected to the supplicant for wfds
09-09 13:36:16.977   285  1581 V AudioPolicyService: registerClient() client 0xb4027140, uid 10079
,09-09 13:36:16.985   957  1305 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:16.986   957   957 D WifiScanningService: SCAN_AVAILABLE : 3
09-09 13:36:16.986   957   957 D RttService: SCAN_AVAILABLE : 3
09-09 13:36:16.986   957  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:16.986   957  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:16.986   957  1325 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:16.986   957  1325 I WifiNative-HAL: startHal
09-09 13:36:16.986   957  1325 D wifi    : getting scan capabilities on interface[0] = 0x9d82d4c0
09-09 13:36:16.986   957  1325 D WifiHAL : Creating message to get scan capablities; iface = 24
09-09 13:36:16.986   281  1048 D CommandListener: Setting iface cfg
09-09 13:36:16.986   957  1325 D wifi    : failed to get capabilities : -95
09-09 13:36:16.986   281  1048 D CommandListener: Trying to bring up p2p0
09-09 13:36:16.986   957  1325 E WifiScanningService: could not get scan capabilities
09-09 13:36:16.987   957  1326 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:16.989   957  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 13:36:16.989   957  1305 D LGWifiP2pService: P2pEnablingState
09-09 13:36:16.989  7619  7619 I NSApplication: Starting up...
09-09 13:36:16.989   957  1305 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:16.989   957  1305 D LGWifiP2pService: P2p socket connection successful
09-09 13:36:16.989   957  1305 D LGWifiP2pService: P2pEnabledState
09-09 13:36:16.991   957  1305 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-09 13:36:16.991   957  1305 D LGWifiP2pService: before postfix = G3s-1
09-09 13:36:16.991   957  1305 D WifiServerServiceExt: postfix byte check : 5
09-09 13:36:16.991   957  1305 D LGWifiP2pService: after postfix = G3s-1
09-09 13:36:16.999   957  1306 I WifiServerServiceExt: set CMD_ADD_DEFAULT_PROFILE
,09-09 13:36:17.003   957  1305 D WifiNative-HAL: p2pGetDeviceAddress
09-09 13:36:17.003   957  1305 D WifiNative-HAL: p2pGetDeviceAddress returning a2:39:f7:70:12:80
09-09 13:36:17.003   957  1305 D LGWifiP2pService: DeviceAddress: a2:39:f7:70:12:80
09-09 13:36:17.010   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.010   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.010   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 13:36:17.012  1802  1802 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-09 13:36:17.012  1802  1802 D WfdsService: Update P2p Interface State: 3
09-09 13:36:17.012   957  1306 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,09-09 13:36:17.012  7619  7686 W AudioManagerAndroid: Requires BLUETOOTH permission
09-09 13:36:17.013  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:17.013  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:17.013 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:17.013  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:36:17.021  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:17.030  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:17.030  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:17.030  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:17.030  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:17.032  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:17.032  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:17.037  7667  7667 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,09-09 13:36:17.042   957  1305 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-09 13:36:17.047   957  1306 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-09 13:36:17.047  7667  7667 E wpa_supplicant: disconnect_rssi_lvl: -100
09-09 13:36:17.048   957  1306 I WifiServerServiceExt: set CMD_SET_FRAMEWORK_AUTO_JOIN 0
09-09 13:36:17.048  7667  7667 E wpa_supplicant: wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
09-09 13:36:17.050   957  1306 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
09-09 13:36:17.068  7667  7667 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,09-09 13:36:17.071  7667  7667 I wpa_supplicant: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2437 MHz)
,09-09 13:36:17.084   957  1379 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7702 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:17.093   957  1379 I ActivityManager: Killing 7403:com.google.android.music:main/u0a81 (adj 15): empty #11
09-09 13:36:17.122   957  1379 I ActivityManager: Killing 7307:com.lge.settings.easy/1000 (adj 15): empty #12
,09-09 13:36:17.152   957  1379 I ActivityManager: Killing 6732:com.android.settings/1000 (adj 15): empty #13
,09-09 13:36:17.165   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:36:17.165  7667  7667 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-09 13:36:17.165   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:36:17.165   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,09-09 13:36:17.183   957  1305 D LGWifiP2pService: sending p2p connection changed broadcast
,09-09 13:36:17.183   957  1305 D LGWifiP2pService: InactiveState
,09-09 13:36:17.183   957  1305 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.183   957  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.183   957  1305 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.183   957  1305 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.183   957  1783 W libprocessgroup: failed to open /acct/uid_1000/pid_7307/cgroup.procs: No such file or directory
09-09 13:36:17.183   957  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.183   957  1305 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.184   957   957 E WifiServerServiceExt: No p2p device connected
09-09 13:36:17.185   957   974 W libprocessgroup: failed to open /acct/uid_1000/pid_6732/cgroup.procs: No such file or directory
09-09 13:36:17.190   957  2125 W libprocessgroup: failed to open /acct/uid_10081/pid_7403/cgroup.procs: No such file or directory
09-09 13:36:17.191  7667  7667 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:36:17.192  7667  7667 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 13:36:17.192   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,09-09 13:36:17.201  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
09-09 13:36:17.201  1802  1802 D WfdsService: WifiP2pState is changed : true
,09-09 13:36:17.201  1802  1802 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-09 13:36:17.201  1802  1802 D WfdsService: isConnected: false
09-09 13:36:17.202  1802  2113 D WfdsService: Receive the WFDS_ENABLE Method
09-09 13:36:17.202  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:17.202   957  1305 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.202   957  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.202   957  1305 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.202   957  1305 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.202   957  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.202   957  1305 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.202  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:17.202 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:17.202  1802  2113 D WfdsService: Set the WFDS Monitor: true
09-09 13:36:17.202  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:36:17.202  1802  2113 D WfdsService: Connected to the supplicant for wfds
09-09 13:36:17.202  1802  2113 D WfdsJNI : doCommand: WFDS_SET TRUE
09-09 13:36:17.203  7667  7667 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-09 13:36:17.203  1802  2113 D WfdsJNI : doCommand: WFDS_CLEAR_PD_INFO
09-09 13:36:17.203  1802  1802 D WfdsService: GroupInfoAvailable: mGroupInfo is null
09-09 13:36:17.203  7667  7667 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
09-09 13:36:17.203  1802  2113 D WfdsJNI : wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
09-09 13:36:17.203  1802  2113 D WfdsService: selectPreferredScanChannel [6]
09-09 13:36:17.203  1802  2113 D WfdsService: STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
09-09 13:36:17.203  1802  2113 W WfdsService: DefaultState - msg [9441285] is not handled
09-09 13:36:17.204  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:17.205   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.205   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.205   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 13:36:17.205   957   957 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:17.205   957   957 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 13:36:17.207  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:17.207  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:17.207  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/,stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:17.207  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:17.207  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:17.207  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:17.209   957   957 D LocSvc_java: onReceive
,09-09 13:36:17.212  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:17.214  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:17.214   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.214   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.214   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 13:36:17.215  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:17.214 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:17.215  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-09 13:36:17.217  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:17.217  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:17.217  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:17.217  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:17.217  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:17.217  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:17.219  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:17.219  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:17.219  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:17.219 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:17.219  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-09 13:36:17.220   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.220   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.220   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 13:36:17.222  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,09-09 13:36:17.222  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:17.222  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:17.222  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:17.223  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:17.223  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:17.224  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:17.225  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:17.225 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:17.225  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,09-09 13:36:17.226  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:17.228   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.228   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.228   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-09 13:36:17.228   957   957 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:17.228   957   957 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 13:36:17.230  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:17.230  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:17.230  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:17.230  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:17.230  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:17.230  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:17.233   957  1306 I WifiServiceExtension: setVHTCapabilityType  : false
09-09 13:36:17.246   957  1306 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-09 13:36:17.246   957  1306 I WifiServerServiceExt: setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
09-09 13:36:17.246   957  1306 I WifiServiceExtension: setSecurityType  : 2
,09-09 13:36:17.275  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,09-09 13:36:17.275  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:17.275 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:17.276  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-09 13:36:17.276   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.276   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.276   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 13:36:17.277  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:17.278   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.278   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.278   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 13:36:17.278  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:17.278 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:17.278  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-09 13:36:17.278  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:17.281  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:17.281  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:17.281  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:17.281  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:17.282  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:17.282  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:17.282  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:17.283  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:17.284  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:17.284  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:17.284  1370  1370 I [SystemUI]QuickSettingsH,andler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:17.284  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:17.284  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:17.287   957  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,09-09 13:36:17.287   957  1313 D ConnectivityService: Got NetworkAgent Messenger
09-09 13:36:17.287   957  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 13:36:17.287   957  1313 D ConnectivityService: NetworkAgent connected
09-09 13:36:17.288  1802  1817 D WifiServiceExtension: isInternetCheckAvailable return false
09-09 13:36:17.288   957  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:36:17.309   957  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:36:17.328  6450  6534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:17.329  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:17.329  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:17.329  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:17.329  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:36:17.329  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dadb484 removed from the list
09-09 13:36:17.329  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:17.329  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@320e446d removed from the list
09-09 13:36:17.329  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:17.329  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:17.334   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 9
09-09 13:36:17.335   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:17.335   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:17.335   957  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:17.335   957  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:17.336   281  1048 D CommandListener: Setting iface cfg
09-09 13:36:17.341   957  1306 E WifiStateMachine: Start Dhcp Watchdog 3
09-09 13:36:17.341   957  7722 D DhcpStateMachine: StoppedState
09-09 13:36:17.341   957  7722 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.341   957  7722 D DhcpStateMachine: WaitBeforeStartState
,09-09 13:36:17.342   957   957 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:17.343   957   957 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-09 13:36:17.344   957   957 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:17.344   957   957 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-09 13:36:17.344   957   957 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:17.344   957   957 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-09 13:36:17.348  6450  7723 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-09 13:36:17.348  6450  7723 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-09 13:36:17.349  1837  1837 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
09-09 13:36:17.350  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-53 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:17.349 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:36:17.351  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:17.351  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:17.351  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:17.354   957  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,09-09 13:36:17.443   957  1873 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7727 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-09 13:36:17.444   957  1873 I ActivityManager: Killing 7446:com.lge.email/u0a21 (adj 15): empty #11
,09-09 13:36:17.445   957  1306 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-09 13:36:17.445   957  1306 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 13:36:17.445   957  1305 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1102bbc4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.445   957  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1102bbc4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.445   957  7722 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.445   957  7722 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-09 13:36:17.447   957  1306 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 13:36:17.447   281  1048 D CommandListener: Setting iface cfg
09-09 13:36:17.448   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
09-09 13:36:17.448   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:17.448   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:17.450   281  1048 D CommandListener: Trying to bring up wlan0
09-09 13:36:17.453   957  1306 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-09 13:36:17.483   957   957 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:17.483   957   957 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,09-09 13:36:17.488   957  1874 W libprocessgroup: failed to open /acct/uid_10021/pid_7446/cgroup.procs: No such file or directory
09-09 13:36:17.490   957   957 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:17.490   957   957 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 13:36:17.492   957  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 13:36:17.493   957  1305 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.493   957  1305 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.503   957  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,09-09 13:36:17.504   957  1306 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 13:36:17.504   957  1313 D ConnectivityService: ignoring duplicate network state non-change
09-09 13:36:17.506  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:17.507  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:17.508   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.508  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-53 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:17.507 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:36:17.508   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.508   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 13:36:17.508  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.109 ipV6Addr=
09-09 13:36:17.509  1802  2121 D WifiServiceExtension: isInternetCheckAvailable return false
09-09 13:36:17.511  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:17.512   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.512   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.512   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 13:36:17.513  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-53 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:17.513 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:36:17.513  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.109 ipV6Addr=
09-09 13:36:17.514   957  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 13:36:17.514  7727  7727 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:17.514  1802  1818 D WifiServiceExtension: isInternetCheckAvailable return false
,09-09 13:36:17.514   957  1313 D ConnectivityService: Adding iface wlan0 to network 102
,09-09 13:36:17.518   957   957 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 13:36:17.518  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:17.520  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:17.520  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:17.520  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:17.520  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:17.520   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.520   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.520   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 13:36:17.520  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:17.520  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:17.521  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:17.521 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:36:17.521  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:17.522  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.109 ipV6Addr=
09-09 13:36:17.523   957   957 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 13:36:17.524  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:36:17.526  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:17.525 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:36:17.526  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.109 ipV6Addr=
09-09 13:36:17.527   957   957 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.528   957   957 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:17.528   957   957 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 13:36:17.529   957  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 13:36:17.534  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:36:17.534  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:17.534  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:17.534  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:17.535  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:17.535  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:17.536  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 13:36:17.537  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:36:17.537  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:17.538  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:17.539  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:17.539  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:17.539  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:17.540  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 13:36:17.542   957  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 13:36:17.542   957  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-09 13:36:17.543   281  1048 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:36:17.543   281  1048 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:17.543   281  1048 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:36:17.543   281  1048 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:17.543  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:36:17.543  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:17.544  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui,:drawable/stat_sys_wifi_in
09-09 13:36:17.544   957  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-09 13:36:17.544  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:36:17.544   281  1048 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:36:17.544   281  1048 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:17.544  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:36:17.544  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:36:17.544   281  1048 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:36:17.544   281  1048 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:36:17.547   281  1048 E Netd    : netlink response contains error (File exists)
09-09 13:36:17.549   957  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-09 13:36:17.549   281  1048 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:36:17.549   281  1048 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:17.550   957  1313 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-09 13:36:17.550   957  1313 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-09 13:36:17.550   957  1313 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-09 13:36:17.550   957  1313 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:17.550   957  1313 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:17.551   281  1048 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
09-09 13:36:17.551   281  1048 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:17.551   957  1313 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 13:36:17.551   957  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 13:36:17.551   957  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-09 13:36:17.552   957  1313 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-09 13:36:17.552   957  7721 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.552   957  7721 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-09 13:36:17.552   957  7721 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:17.552   957  1313 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:36:17.552   957  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:17.552   957  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:36:17.552   957  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:17.552   957  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-09 13:36:17.553   957  1313 D ConnectivityService: currentScore = 0, newScore = 20
09-09 13:36:17.553   957  1313 D ConnectivityService:    accepting network in place of null
09-09 13:36:17.553   957  1313 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:17.553  1749  1749 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:17.553   957  1306 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:17.554   957  1306 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:36:17.554  1749  1749 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabi,lities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
09-09 13:36:17.558   957  1313 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 13:36:17.558   957  1313 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-09 13:36:17.558   957  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:36:17.561   957  1056 D Tethering: MasterInitialState.processMessage what=3
09-09 13:36:17.561  1837  1837 W QCNEJ   : |CORE| No family connected
09-09 13:36:17.561  1837  1837 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
09-09 13:36:17.562  1837  1837 I QCNEJ   : |CORE| sendDefaultNwMsg: default = 1
09-09 13:36:17.563   957  7721 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] Start DNSResolver start to wait
09-09 13:36:17.564   957  1313 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:17.564   957  1313 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-09 13:36:17.564   957  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-09 13:36:17.566   957  7749 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wait 500ms before dns check
09-09 13:36:17.567   957  1313 D ConnectivityService: validation of new default Network = false
09-09 13:36:17.567   957  1313 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-09 13:36:17.567   957  1313 D DSQN    : enableDataServiceNotify 
09-09 13:36:17.567   957  1313 D DSQN    : start dsqn bin
,09-09 13:36:17.580   957  1304 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-09 13:36:17.581   957  1313 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-09 13:36:17.581   957  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:17.581   957  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:17.581   957  1313 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:17.582  1370  1740 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:36:17.593  7750  7750 I DSQN    : DSQN samuel.seo ver 141203
09-09 13:36:17.593  7750  7750 E DSQN    : DSQN sock connect success to lgdatalistenerd
09-09 13:36:17.593  7750  7750 I DSQN    : created command queue thread
09-09 13:36:17.593  7750  7750 I DSQN    : Interface wlan0 address 192.168.1.109 0xc0a8016d
09-09 13:36:17.593  7750  7750 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a8016d
,09-09 13:36:17.598  1370  1370 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:36:17.599  1370  1370 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
09-09 13:36:17.600  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:36:17.600  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:17.601  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:17.602  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:36:17.602  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:17.602  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:17.603  7018  7751 I CheckinChimeraService: Checking schedule, now: 1473420977603 next: 1473420911816
09-09 13:36:17.603  7018  7751 I CheckinChimeraService: active receiver: enabled
,09-09 13:36:17.619  7018  7751 I CheckinChimeraService: Preparing to send checkin request
09-09 13:36:17.619  7018  7751 I EventLogChimeraService: Accumulating logs since 1473420968826
09-09 13:36:17.646   957  7722 D DhcpStateMachine: DHCPV4 request on wlan0
,09-09 13:36:17.647   957  7722 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-09 13:36:17.647   957  7722 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-09 13:36:17.659  7761  7761 I dhcpcd  : version 5.5.6 starting
,09-09 13:36:17.661  7761  7761 E dhcpcd  : get_duid: Read-only file system
,09-09 13:36:17.663  7018  7751 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
09-09 13:36:17.682  7018  7751 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,09-09 13:36:17.739  7761  7761 I dhcpcd  : wlan0: rebinding lease of 192.168.1.109
,09-09 13:36:17.771  7761  7761 I dhcpcd  : wlan0: acknowledged 192.168.1.109 from 192.168.1.1
,09-09 13:36:17.782  7761  7761 I dhcpcd  : wlan0: leased 192.168.1.109 for 172800 seconds
,09-09 13:36:17.802  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-09 13:36:17.803  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:36:17.852  6450  7778 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:17.852  6450  7778 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:17.853  6450  7778 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:17.853  6450  7778 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:17.853   281  1043 E BandwidthController: [LG DATA] No such appUid: 10030
09-09 13:36:17.853   281  1043 D DnsProxyListener: App 10030 tries DNS query. Accept family:0 protocol:0
09-09 13:36:17.853   281  7781 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-09 13:36:17.853   281  7781 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,09-09 13:36:17.854   281  7781 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:36:17.854   281  7781 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:17.854  6450  7778 I System.out: propertyValue:false
09-09 13:36:17.857  6450  7723 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-09 13:36:17.858  6450  7723 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:36:17.858  6450  7778 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-09 13:36:17.858  6450  7778 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:36:17.864  6450  7723 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:17.864  6450  7778 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:17.868  6450  7723 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:36:17.871  6450  7778 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:17.871  6450  7723 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-09 13:36:17.874  6450  7778 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-09 13:36:17.874  6450  7785 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 939, name: OutgoingSocketThread/Receiver)
09-09 13:36:17.875  6450  7784 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 937, name: OutgoingSocketThread/Sender)
09-09 13:36:17.876  6450  7785 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 939, thread name: OutgoingSocketThread/Receiver)
09-09 13:36:17.876  6450  7785 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:36:17.876  6450  7785 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 939, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-09 13:36:17.885  6450  7786 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 938, name: IncomingSocketThread/Sender)
,09-09 13:36:17.887  6450  7787 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 940, name: IncomingSocketThread/Receiver)
09-09 13:36:17.888  6450  7787 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 940, thread name: IncomingSocketThread/Receiver)
09-09 13:36:17.888  6450  7787 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:36:17.888  6450  7787 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 940, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-09 13:36:17.907   285  1581 I WVCdm   : CdmEngine::OpenSession
09-09 13:36:17.907   285  1581 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
,09-09 13:36:17.929   957  1379 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=7797 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-09 13:36:17.935   285  1581 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
09-09 13:36:17.935   285  1581 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
09-09 13:36:17.935   285  1581 W WVCdm   : L1 library not specified. Falling Back to L3
09-09 13:36:17.966   957  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:17.967   957  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:17.969   957   957 D LocSvc_java: onReceive
09-09 13:36:17.969   957   957 D LocSvc_java: got connectivity action
09-09 13:36:17.969   957   957 D LocSvc_java: broadcast - no network connections
09-09 13:36:17.969   957   957 D LocSvc_java: Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
09-09 13:36:17.969   957   957 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 13:36:17.969   957   957 D LocSvc_java: getAGpsConnectionInfo connType - 4
,09-09 13:36:17.969   957   957 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:36:17.969   957   957 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:36:17.971   957  1025 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:17.972  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
09-09 13:36:17.976   957   957 D LocSvc_java: onReceive
09-09 13:36:17.976   957   957 D LocSvc_java: got connectivity action
09-09 13:36:17.976   957   957 D LocSvc_java: broadcast - no network connections
09-09 13:36:17.976   957   957 D LocSvc_java: Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
09-09 13:36:17.976   957   957 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 13:36:17.978  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
09-09 13:36:17.990  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:17.990  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:17.990  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:17.990  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:17.990  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:17.990  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:17.990  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:17.990  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:17.990  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:36:17.992   957   957 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:36:17.992   957   957 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:36:17.992   957   957 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:36:17.998  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:17.998  6450  6450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:18.001  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:18.001  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:18.001  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:18.001  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:18.001  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:18.001  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:18.001  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:18.001  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:18.001  6450  6450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:18.002  6450  6450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:18.002  6450  6450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:18.002   957  1025 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:18.005  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:18.012  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:18.027   957  1025 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:18.027   957  1025 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:18.050   957  7722 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:18.050   957  7722 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:36:18.051   957  7722 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:18.051   957  7722 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:18.051   957  7722 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:18.051   957  7722 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:18.051   957  7722 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:18.052   957  7722 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:18.052   957  7722 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-09 13:36:18.054   957  7722 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 4
09-09 13:36:18.054   957  7722 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 13:36:18.055   957  7722 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:18.055   957  7722 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:18.055   957  7722 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.109
09-09 13:36:18.055   957  7722 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-09 13:36:18.055   957  7722 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 13:36:18.055   957  7722 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-09 13:36:18.055   957  7722 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-09 13:36:18.055   957  7722 D DhcpStateMachine: RunningState
09-09 13:36:18.059   285  1581 I WVCdm   : CdmEngine::QueryKeyControlInfo
09-09 13:36:18.059   285   285 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-09 13:36:18.060   285   285 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-09 13:36:18.060   285   285 I WVCdm   : CdmEngine::GenerateKeyRequest
09-09 13:36:18.065   285   285 D WVCdm   : PrepareKeyRequest: nonce=2998922132
,09-09 13:36:18.066   957  7749 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver start dns
09-09 13:36:18.066   957  7749 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:18.067   957  7749 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:18.067   957  7749 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=102; mark=0
09-09 13:36:18.067   957  7749 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:18.067   281  1043 E BandwidthController: [LG DATA] No such appUid: 1000
09-09 13:36:18.067   281  1043 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-09 13:36:18.067   281  7820 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=983142
09-09 13:36:18.068   281  7820 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:18.068   281  7820 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-09 13:36:18.068   281  7820 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:36:18.103   281  7820 D libc-netbsd: res_queryN name = xxxxx succeed
,09-09 13:36:18.104   957  7749 I System.out: propertyValue:false
09-09 13:36:18.104   957  7749 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver end dns
09-09 13:36:18.105   957  7721 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 13:36:18.108   957  7721 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:18.108   957  7721 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:18.136  7750  7752 I DSQN    : first global connection report this to start monitoring at DSQM.
09-09 13:36:18.136  7750  7752 I DSQN    : restart monitoring
,09-09 13:36:18.137   281  1047 D LGDataListener: argv[0]=dsqncommand
09-09 13:36:18.137   281  1047 D LGDataListener: argv[1]=wlan0
09-09 13:36:18.137   281  1047 D LGDataListener: argv[2]=1
09-09 13:36:18.137   281  1047 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-09 13:36:18.137  7750  7822 I DSQN    : dsqn report finish
09-09 13:36:18.137   957  1054 D DSQN    : DSQM DsqnNotification wlan0  1
09-09 13:36:18.137   957  1054 D DSQN    : start to monitor internet connection
09-09 13:36:18.161   957  7721 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:36:18 GMT], X-Android-Received-Millis=[1473420978161], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473420978137]}
,09-09 13:36:18.162   957  7721 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 13:36:18.163  1802  1818 D WifiServiceExtension: isInternetCheckAvailable return false
09-09 13:36:18.163   957  7721 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wifi && isInternetCheckAvailable is false
09-09 13:36:18.163   957  7721 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-09 13:36:18.164   957  1313 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-09 13:36:18.164   957  1313 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-09 13:36:18.164   957  1313 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:36:18.164   957  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:18.164   957  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:36:18.164   957  1313 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-09 13:36:18.164   957  1313 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-09 13:36:18.164   957  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:18.164   957  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:18.164   957   957 D WifiDataContinuityService: sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
09-09 13:36:18.165   957  1313 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:18.165   957  1313 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:18.165  1370  1740 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:36:18.165   957  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 13:36:18.166   957  1306 I WifiServerServiceExt: set CMD_CAPTIVE_CHECK_COMPLETED
09-09 13:36:18.166   957  1306 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:18.166  1749  1749 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:18.166   957  1306 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:36:18.167  1749  1749 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
09-09 13:36:18.180  1370  1370 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-09 13:36:18.181  1370  1370 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
09-09 13:36:18.182   281  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 6
09-09 13:36:18.182  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:36:18.182  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:18.183  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:18.183   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:18.183   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:18.184  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:36:18.184  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:18.185  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:36:18.244  7797  7797 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:36:18.244  7797  7797 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-09 13:36:18.244  7797  7797 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:36:18.245  7797  7797 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 13:36:18.245  7797  7797 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-09 13:36:18.322  7797  7797 I IndexDatabaseHelper: Using schema version: 115
09-09 13:36:18.325  7797  7797 I IndexDatabaseHelper: Index is fine
,09-09 13:36:18.356  6450  6534 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-09 13:36:18.357  6450  6534 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-09 13:36:18.358  6450  6534 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2c64caea Bundle[{}]
09-09 13:36:18.359  6450  6534 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 13:36:18.359  6450  6534 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-09 13:36:18.360  6450  6534 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-09 13:36:18.360  6450  6534 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 13:36:18.361  6450  6534 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-09 13:36:18.361  6450  6534 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 13:36:18.369  6450  7823 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-09 13:36:18.370  6450  7823 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-09 13:36:18.377  6450  7825 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:18.377  6450  7825 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:36:18.380  6450  7823 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-09 13:36:18.380  6450  7823 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:36:18.380  6450  7823 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:18.380  6450  7823 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:18.381  6450  7823 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-09 13:36:18.383  6450  7825 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-09 13:36:18.383  6450  7825 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:36:18.383  6450  7825 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:18.383  6450  7827 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 951, name: OutgoingSocketThread/Sender)
09-09 13:36:18.384  6450  7828 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 952, name: OutgoingSocketThread/Receiver)
09-09 13:36:18.384  6450  7825 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:18.385  6450  7825 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-09 13:36:18.386  6450  7828 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 952, thread name: OutgoingSocketThread/Receiver)
09-09 13:36:18.386  6450  7828 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:36:18.386  6450  7828 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 952, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-09 13:36:18.387  6450  7829 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 953, name: IncomingSocketThread/Sender)
09-09 13:36:18.389  6450  7830 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 954, name: IncomingSocketThread/Receiver)
09-09 13:36:18.390  6450  7830 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 954, thread name: IncomingSocketThread/Receiver)
09-09 13:36:18.390  6450  7830 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:36:18.390  6450  7830 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 954, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-09 13:36:18.409  7239  7254 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:36:18.409  7239  7254 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:36:18.409  7239  7254 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:36:18.409  7239  7254 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:36:18.409  7239  7254 I Adreno-EGL: Remote Branch: 
09-09 13:36:18.409  7239  7254 I Adreno-EGL: Local Patches: 
09-09 13:36:18.409  7239  7254 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:36:18.486   285  1581 I WVCdm   : CdmEngine::OpenSession
09-09 13:36:18.496  7797  7797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-09 13:36:18.525  7797  7797 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-09 13:36:18.542   957  1874 I ActivityManager: Process com.lge.appbox.client (pid 7474) has died
,09-09 13:36:18.545  7797  7797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:18.555  7797  7797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:18.582   957  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-09 13:36:18.611   957  1901 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7834 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-09 13:36:18.639   957  1286 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 13:36:18.678  1370  1370 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-09 13:36:18.688  1370  1370 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-09 13:36:18.693  1837  1837 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
09-09 13:36:18.715   957   957 D administrator: Handling package changes for user 0
,09-09 13:36:18.742   281  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
,09-09 13:36:18.743   957  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:18.743   957  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:18.746   957  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-09 13:36:18.746   957  1313 D ConnectivityService: identical MTU - not setting
09-09 13:36:18.746   957  1313 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 13:36:18.746   957  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 13:36:18.746   957  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:18.746   957  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:18.747   957  1313 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:18.747   957  1313 D ConnectivityService: Wi-Fi IP changed. Lp difference / No Route difference
09-09 13:36:18.747   957  1313 D DSQN    : enableDataServiceNotify 
09-09 13:36:18.747   957  1313 D DSQN    : start dsqn bin
09-09 13:36:18.748  1370  1740 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-09 13:36:18.749  1875  1875 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-09 13:36:18.774  1875  1875 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-09 13:36:18.779   957  1873 I ActivityManager: Process com.lge.lgdmsclient (pid 7063) has died
09-09 13:36:18.786   957  1313 D DSQN    : dsqn is running restart
09-09 13:36:18.792  1837  1837 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
,09-09 13:36:18.793  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:18.793 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:36:18.795  1370  1370 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
09-09 13:36:18.795  1370  1370 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
09-09 13:36:18.796  1875  1875 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
09-09 13:36:18.800  1370  1370 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
09-09 13:36:18.800  1370  1370 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
09-09 13:36:18.800  1370  1370 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
09-09 13:36:18.800  1370  1370 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
09-09 13:36:18.800  1370  1370 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
09-09 13:36:18.800  1370  1370 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
09-09 13:36:18.801  1370  1370 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
09-09 13:36:18.801  1370  1370 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
09-09 13:36:18.801  1370  1370 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
09-09 13:36:18.801  1370  1370 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
09-09 13:36:18.801  1370  1370 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-09 13:36:18.832  1875  1875 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,09-09 13:36:18.872  7851  7851 I DSQN    : DSQN samuel.seo ver 141203
09-09 13:36:18.872  7851  7851 E DSQN    : DSQN sock connect success to lgdatalistenerd
09-09 13:36:18.873  7851  7851 I DSQN    : created command queue thread
09-09 13:36:18.873  7851  7851 I DSQN    : Interface wlan0 address 192.168.1.109 0xc0a8016d
09-09 13:36:18.873  7851  7851 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a8016d
,09-09 13:36:18.882  6450  6534 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 963)
09-09 13:36:18.883  6450  6534 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-09 13:36:18.883  6450  6534 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 964)
09-09 13:36:18.885  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:36:18.885  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17d9b933 added. We now have 3 listener(s)
09-09 13:36:18.886   957   974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:18.888  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-09 13:36:18.888  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:36:18.888  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:36:18.889  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:36:18.889  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e9394f0 added. We now have 3 listener(s)
09-09 13:36:18.889  6450  6534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:36:18.890  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:36:18.903  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:36:18.906  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:18.906  6450  6534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:18.906  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:18.906  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:18.906  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:18.906  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:18.906  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:18.906  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:18.906  6450  6534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:18.907  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:18.907  6450  6534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:18.907  6450  6534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:36:18.908  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:18.909  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:18.909  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:18.909  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:18.909  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:36:18.909  6450  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17d9b933 removed from the list
09-09 13:36:18.909  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:18.909  6450  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e9394f0 removed from the list
09-09 13:36:18.909  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:18.913  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:18.913  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:18.913  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:18.914  6450  6534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:36:18.914  6450  6534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:36:18.914  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:36:18.914  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:36:18.914  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:36:18.992   957  1819 I ActivityManager: Process com.google.android.setupwizard (pid 7507) has died
,09-09 13:36:18.998  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-09 13:36:18.999  6450  6534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-09 13:36:19.000  6450  6534 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:36:19.000  6450  6450 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-09 13:36:19.041   957  2125 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7857 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-09 13:36:19.047   957   957 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-09 13:36:19.049   957   957 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-09 13:36:19.050   957   957 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
09-09 13:36:19.079   957   957 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,09-09 13:36:19.089   957  1025 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:36:19.105   957   957 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
09-09 13:36:19.106   957   957 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1cdf659e
,09-09 13:36:19.164  7857  7857 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 13:36:19.214   296   351 I ThermalEngine: Sensor:pa_therm0:35000 mC
,09-09 13:36:19.242   957  1025 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-09 13:36:19.268   957  1819 I ActivityManager: Process com.google.android.talk (pid 7567) has died
,09-09 13:36:19.307   957  1056 D BluetoothManagerService: Message: 20
09-09 13:36:19.307   957  1056 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a265949:true
,09-09 13:36:19.309  1875  1875 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-09 13:36:19.315  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:19.316  2050  2073 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:19.343  1730  1730 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,09-09 13:36:19.351  7797  7797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:36:19.356  7797  7797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:36:19.366   957  1025 D LocationProviderProxy: applying state to connected service
09-09 13:36:19.371  7797  7797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:19.377  7797  7797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:19.389  7797  7797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:19.393  7797  7797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:19.401  7797  7797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:19.405  7797  7797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:19.422  7797  7797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:19.425  7797  7797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:36:19.434  7797  7797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:36:19.437  7797  7797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:19.453  7797  7797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:19.458  7797  7797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:19.467  7797  7797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:19.471  7797  7797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:36:19.479  7834  7834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-09 13:36:19.483  7834  7834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:19.489  7797  7797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:19.494  7797  7797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:19.498  7834  7834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-09 13:36:19.499  7834  7834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:19.500  6450  6450 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-09 13:36:19.588   957  2125 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7878 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:19.605  7857  7857 V LGMDMManager: Create singleton instance
,09-09 13:36:19.686  7857  7857 I AudioManager: getMode name:com.lge.qremote
,09-09 13:36:19.692  7857  7857 I AudioManager: getMode name:com.lge.qremote
09-09 13:36:19.703  7878  7878 D UEI.SmartControl: Quickset Services start...
,09-09 13:36:19.707  7878  7878 I UEI.SmartControl: Manufacture = LGE
,09-09 13:36:19.709  7878  7878 D UEI.SmartControl: File observer start...
09-09 13:36:19.709  7878  7878 E UEI.SmartControl: IR Port is disabled: false
09-09 13:36:19.709  7878  7878 D UEI.SmartControl: Starting file observer...
09-09 13:36:19.709  7878  7878 D UEI.SmartControl: Extracting JNI libs...
09-09 13:36:19.710  7878  7878 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-09 13:36:19.747   957  1801 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7896 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:19.758  7878  7878 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-09 13:36:19.759  7878  7878 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-09 13:36:19.759  7878  7878 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-09 13:36:19.789  7878  7878 I UEI.SmartControl: --- Selecting new region: 2
,09-09 13:36:19.789  7878  7878 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
09-09 13:36:19.791  7878  7878 D UEI.SmartControl: Platform has CIR...
09-09 13:36:19.793  7878  7878 D UEI.SmartControl: NO CIR support, need to check package...
09-09 13:36:19.793  7878  7878 I UEI.SmartControl: Model: LG-D722 uses JNI
09-09 13:36:19.796  7878  7878 D UEI.SmartControl: QS Service created
09-09 13:36:19.829  7878  7878 E UEI.SmartControl: QS start get config
,09-09 13:36:19.881  7878  7878 D UEI.SmartControl: Loading JNI Libs...
,09-09 13:36:19.884  7878  7878 D UEI.SmartControl:  configuring local db...
09-09 13:36:19.892   957  1305 D LGWifiP2pService: InactiveState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:19.892   957  1305 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:19.892   957  1305 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:19.920  7896  7896 I MusicStore: Database version: 120
,09-09 13:36:19.970   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:19.970   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-09 13:36:19.970   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:36:19.970  7896  7896 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-09 13:36:20.084   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:20.084   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,09-09 13:36:20.084   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:36:20.084  7896  7896 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-09 13:36:20.093   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:20.093   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-09 13:36:20.093   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:20.094  7896  7896 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,09-09 13:36:20.104  7878  7878 D UEI.SmartControl:  ---- Has DB8: true
,09-09 13:36:20.111  7878  7878 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 13:36:20.112  7878  7878 D UEI.SmartControl: QS version = v2.7.11.1_RC1
09-09 13:36:20.113  7878  7878 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
09-09 13:36:20.122  7878  7878 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
,09-09 13:36:20.144  7878  7878 W irrc_jni: IRRCPlayer_nativeInit ++ 
,09-09 13:36:20.144  7878  7878 D irrcClient: IrrcClient ++ 
09-09 13:36:20.144  7878  7878 D irrcClient: getIrrcService ++ 
09-09 13:36:20.144  7878  7878 D irrcClient: getIrrcService -- 
09-09 13:36:20.144  7878  7878 D irrcClient: IrrcClient -- 
09-09 13:36:20.144  7878  7878 W irrc_jni: IRRCPlayer_nativeInit -- 
09-09 13:36:20.152  7878  7878 D UEI.SmartControl: Services init done
09-09 13:36:20.153  7878  7921 I UEI.SmartControl: Device manager: loading config....
09-09 13:36:20.157  7878  7921 D UEI.SmartControl: Config is loaded...
,09-09 13:36:20.182  7878  7920 D UEI.SmartControl:  ----- QS SDK is ready!!!
09-09 13:36:20.183  7878  7920 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-09 13:36:20.302   285  1584 I WVCdm   : CdmEngine::CloseSession
,09-09 13:36:20.328   957  1783 I art     : Explicit concurrent mark sweep GC freed 95918(4MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 2.444ms total 224.448ms
,09-09 13:36:20.341  7878  7878 D UEI.SmartControl: QS Service init finished
,09-09 13:36:20.344  7878  7878 D UEI.SmartControl: QS Service version name: 0.1.73
09-09 13:36:20.345  7878  7878 D UEI.SmartControl: QS Service version code: 1073
09-09 13:36:20.352  7878  7878 D UEI.SmartControl: Service requested: Control
09-09 13:36:20.355  7878  7878 D UEI.SmartControl: Internal service binding...
,09-09 13:36:20.360  7878  7893 D UEI.SmartControl: -----IControl: 11
09-09 13:36:20.361  7878  7893 D UEI.SmartControl: Caller: com.lge.qremote
09-09 13:36:20.365  7878  7893 D UEI.SmartControl: ------------ IControl registerCallback...
09-09 13:36:20.365  1837  1837 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
09-09 13:36:20.366  7878  7893 I UEI.SmartControl: Registering callback...
09-09 13:36:20.366  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:36:20.366 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:36:20.368  7878  7894 D UEI.SmartControl: -----IControl: 19
09-09 13:36:20.368  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:36:20.368  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:36:20.369  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-09 13:36:20.369  7878  7894 D UEI.SmartControl: Caller: com.lge.qremote
09-09 13:36:20.370  7878  7894 I UEI.SmartControl: Registering Services Ready callback...
09-09 13:36:20.370  7878  7894 I UEI.SmartControl: Notify client services are ready...
,09-09 13:36:20.374  7878  7893 D UEI.SmartControl: -----IControl: 8
09-09 13:36:20.375  7878  7893 D UEI.SmartControl: Caller: com.lge.qremote
09-09 13:36:20.379   285  1581 I WVCdm   : CdmEngine::QueryKeyControlInfo
09-09 13:36:20.379  7896  7896 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 13:36:20.381   285  1581 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-09 13:36:20.381   285  1581 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-09 13:36:20.381   285  1581 I WVCdm   : CdmEngine::GenerateKeyRequest
09-09 13:36:20.381  7896  7896 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-09 13:36:20.386   285  1581 D WVCdm   : PrepareKeyRequest: nonce=3652283642
,09-09 13:36:20.428  7896  7896 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 13:36:20.520   957  1307 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-09 13:36:20.525  7896  7896 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-09 13:36:20.525  7896  7896 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5458c02: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-09 13:36:20.526  7896  7896 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-09 13:36:20.526  7896  7896 D AndroidMusic: GMSCore installation verified
09-09 13:36:20.531  7896  7896 I ConfigStore: Config Database version: 1
,09-09 13:36:20.565   957  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:20.568  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
09-09 13:36:20.569   957   957 D LocSvc_java: onReceive
09-09 13:36:20.569   957   957 D LocSvc_java: got connectivity action
09-09 13:36:20.569   957   957 D LocSvc_java: Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
09-09 13:36:20.569   957   957 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-09 13:36:20.569   957   957 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:36:20.569   957   957 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:36:20.569   957   957 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:36:20.571  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:20.572   957  1025 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:20.582  6450  6450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:20.589   957  1025 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 13:36:20.630  7896  7910 I art     : CheckpointMarkThreadRoots callback created = 0xaaf231f0
,09-09 13:36:20.647  7896  7896 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-09 13:36:20.654  7896  7896 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
09-09 13:36:20.662  7896  7896 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 13:36:20.666  7896  7910 I art     : CheckpointMarkThreadRoots callback created = 0xaaf231d0
09-09 13:36:20.701  7896  7896 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 13:36:20.738   957  2125 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7929 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-09 13:36:20.781  7896  7896 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,09-09 13:36:20.786  7896  7896 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:36:20.829  7896  7915 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
,09-09 13:36:20.832  7929  7929 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:20.832  7929  7929 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:36:20.833  7929  7929 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 13:36:21.072   957  1379 I ActivityManager: Process com.google.android.apps.magazines (pid 7619) has died
,09-09 13:36:21.077  7929  7929 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
09-09 13:36:21.093  7929  7929 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,09-09 13:36:21.307  7929  7929 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-09 13:36:21.370   957  1873 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7955 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-09 13:36:21.394   310   310 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 24.211ms
,09-09 13:36:21.418   310   310 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.341ms
,09-09 13:36:21.443   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 383us total 23.509ms
,09-09 13:36:21.462  7929  7929 I HubEmail: JNI_OnLoad()
09-09 13:36:21.462  7929  7929 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:36:21.462  7929  7929 I HubEmail: registerNatives()
09-09 13:36:21.462  7929  7929 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:36:21.462  7929  7929 I HubEmail: registerNativeMethods()
09-09 13:36:21.462  7929  7929 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:36:21.463  7929  7929 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-09 13:36:21.474  7929  7972 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:21.518  7955  7955 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:21.518  7955  7955 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:36:21.521  7955  7955 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:36:21.524  7955  7955 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:36:21.541  7955  7974 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:21.544  7955  7974 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:36:21.556  7955  7973 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-09 13:36:21.563   957  1901 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7978 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-09 13:36:21.563  7955  7973 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-09 13:36:21.597  7955  7973 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,09-09 13:36:21.603  7955  7955 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
09-09 13:36:21.603  7955  7955 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
09-09 13:36:21.603  7955  7955 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:36:21.605  7955  7955 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:36:21.610  7955  7955 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,09-09 13:36:21.615   957  1901 I ActivityManager: Killing 7546:com.lge.drmservice/u0a51 (adj 15): empty #11
09-09 13:36:21.724   957  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:21.724   957  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:36:21.726   957  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:21.726   957  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:21.726   281  1043 E BandwidthController: [LG DATA] No such appUid: 1000
09-09 13:36:21.726   281  1043 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-09 13:36:21.727   281  8000 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-09 13:36:21.727   281  8000 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:21.727   281  8000 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-09 13:36:21.727   281  8000 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,09-09 13:36:21.786   957  2062 W libprocessgroup: failed to open /acct/uid_10051/pid_7546/cgroup.procs: No such file or directory
09-09 13:36:21.812  7978  7978 I AppUp4:AppBoxCP: onCreate
,09-09 13:36:21.813  7978  7978 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-09 13:36:21.822  7978  7978 I AppUp4:DB:  setFingerPrint start
09-09 13:36:21.823  7978  7978 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
,09-09 13:36:21.829  7978  7978 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
09-09 13:36:21.829  7978  7978 I AppUp4:DB:  SDK version = 21
09-09 13:36:21.829  7978  7978 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-09 13:36:21.830  7978  7978 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-09 13:36:21.832  7978  7978 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 13:36:21.832  7978  7978 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:21.833  7978  7978 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 13:36:21.834  7978  7978 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 13:36:21.837  7978  7978 I AppUp4:CustModeStarterReceiver: onReceive
09-09 13:36:21.837  7978  7978 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:21.843  7978  7978 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@108257c7
09-09 13:36:21.843  7978  7978 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:36:21.848  7978  7978 D AppUp4:CustFacade: isSimDevice : true
09-09 13:36:21.849  7978  7978 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:36:21.849  7978  7978 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-09 13:36:21.849  7978  7978 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-09 13:36:21.850  7978  8002 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-09 13:36:21.850  7978  8002 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-09 13:36:21.850  7978  8002 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,09-09 13:36:21.851   957  1783 I ActivityManager: Killing 7702:com.android.chrome/u0a48 (adj 15): empty #11
09-09 13:36:21.943   957  1379 W libprocessgroup: failed to open /acct/uid_10048/pid_7702/cgroup.procs: No such file or directory
09-09 13:36:21.944  3187  3187 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 13:36:21.944  3187  3187 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:21.945  3187  3187 I LgeMiscReceiver: networkInfo.isConnected() = true
,09-09 13:36:21.949  3187  3187 D PhoneState: setPdpRejectCasuse : false
09-09 13:36:21.983   957  1819 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8004 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,09-09 13:36:22.000  6450  6534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:36:22.000  6450  6534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 13:36:22.007  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:22.007  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:22.007  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:22.007  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17d9b933 not in the list
09-09 13:36:22.007  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:22.007  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:36:22.007  6450  6534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:36:22.007  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:36:22.007  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:36:22.063  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:22.064  6450  6534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:36:22.065  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e9394f0 not in the list
09-09 13:36:22.065  6450  6450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:36:22.065  6450  6450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:36:22.065  6450  6450 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:36:22.065  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:22.066  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:22.066  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:22.068  6450  6534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:36:22.073  6450  6534 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-09 13:36:22.073  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-09 13:36:22.074  6450  6534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:36:22.074  6450  6534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:36:22.074  6450  6534 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:36:22.074  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:22.077  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
,09-09 13:36:22.078  6450  6534 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
09-09 13:36:22.078  6450  6450 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
09-09 13:36:22.078  6450  6534 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the connection manager (Bluetooth connection listener)
09-09 13:36:22.080  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:36:22.080  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:22.080  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:36:22.082  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-09 13:36:22.083  6450  6534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-09 13:36:22.083  6450  6534 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:36:22.083  6450  6450 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-09 13:36:22.083  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:22.083  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:36:22.083  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:22.083  6450  6534 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
09-09 13:36:22.084  6450  6450 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:36:22.084  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17d9b933 not in the list
09-09 13:36:22.084  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:22.084  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:36:22.084  6450  6534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:36:22.084  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:36:22.084  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:36:22.084  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:22.086  6450  6534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:36:22.086  6450  6450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:36:22.086  6450  6450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:36:22.086  6450  6450 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:36:22.087  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e9394f0 not in the list
09-09 13:36:22.087  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 ,13:36:22.087  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:22.087  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:22.087  6450  6534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:36:22.087  6450  6534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:36:22.087  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:36:22.087  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:22.088  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:36:22.090  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,09-09 13:36:22.092  6450  6534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-09 13:36:22.092  6450  6534 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:36:22.093  6450  6450 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-09 13:36:22.095   281  8000 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:36:22.095   957  1307 I System.out: propertyValue:false
09-09 13:36:22.098   957  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:22.098   957  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:22.098   957  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:22.098   957  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:22.098   281  1043 E BandwidthController: [LG DATA] No such appUid: 1000
09-09 13:36:22.098   281  1043 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-09 13:36:22.098   281  8023 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-09 13:36:22.099   281  8023 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:22.099   281  8023 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-09 13:36:22.099   281  8023 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:36:22.099   281  8023 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:36:22.100   957  1308 I System.out: propertyValue:false
,09-09 13:36:22.124  7851  7852 I DSQN    : first global connection report this to start monitoring at DSQM.
,09-09 13:36:22.125  7851  7852 I DSQN    : restart monitoring
09-09 13:36:22.125   281  1047 D LGDataListener: argv[0]=dsqncommand
09-09 13:36:22.125   281  1047 D LGDataListener: argv[1]=wlan0
09-09 13:36:22.125   281  1047 D LGDataListener: argv[2]=1
09-09 13:36:22.125   281  1047 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-09 13:36:22.126   957  1054 D DSQN    : DSQM DsqnNotification wlan0  1
09-09 13:36:22.126   957  1054 D DSQN    : start to monitor internet connection
09-09 13:36:22.126  7851  8025 I DSQN    : dsqn report finish
09-09 13:36:22.162   957  1308 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,09-09 13:36:22.188  8004  8004 D PhoneMonitor: Register our PhoneStateListener
,09-09 13:36:22.202  8004  8004 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-09 13:36:22.203  8004  8004 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 13:36:22.206   957   975 I ActivityManager: Killing 7727:com.google.android.apps.plus/u0a86 (adj 15): empty #11
09-09 13:36:22.217  8004  8004 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,09-09 13:36:22.220  8004  8004 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-09 13:36:22.221  8004  8004 D TelephonyAutoProfiling: [parse] Load xml
09-09 13:36:22.224  8004  8004 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-09 13:36:22.224  8004  8004 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
09-09 13:36:22.230  8004  8004 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,09-09 13:36:22.303   957  1783 W libprocessgroup: failed to open /acct/uid_10086/pid_7727/cgroup.procs: No such file or directory
,09-09 13:36:22.304  3277  3277 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:22.307  3277  3277 V DownloadManager: DownloadService onCreate
09-09 13:36:22.310  3277  8028 I DownloadManager: in removeSpuriousFiles
09-09 13:36:22.311  3277  3277 I NotificationManager: com.android.providers.downloads: cancelAll by com.android.providers.downloads
09-09 13:36:22.312  3277  8028 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-09 13:36:22.313  3277  8028 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2bb5d8ee on behalf of 3277
09-09 13:36:22.315  3277  8028 I DownloadManager: in trimDatabase
09-09 13:36:22.316  3277  8028 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,09-09 13:36:22.317  3277  8028 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@88d3c1c on behalf of 3277
09-09 13:36:22.350   957   974 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8031 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-09 13:36:22.353  3277  3277 V DownloadManager: DownloadService onStartCommand
09-09 13:36:22.424  3277  8029 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,09-09 13:36:22.426  3277  8029 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@daa95fa on behalf of 3277
09-09 13:36:22.437   285  1298 I WVCdm   : CdmEngine::CloseSession
,09-09 13:36:22.442   285  1298 I WVCdm   : L3 Terminate.
09-09 13:36:22.450  7239  7254 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:36:22.450  7239  7254 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:36:22.450  7239  7254 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:36:22.450  7239  7254 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:36:22.450  7239  7254 I Adreno-EGL: Remote Branch: 
09-09 13:36:22.450  7239  7254 I Adreno-EGL: Local Patches: 
09-09 13:36:22.450  7239  7254 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:36:22.481  3277  3277 V DownloadManager: DownloadService onDestroy
,09-09 13:36:22.499   957  1873 I ActivityManager: Killing 7797:com.android.settings/1000 (adj 15): empty #11
,09-09 13:36:22.526  7239  7254 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:36:22.526  7239  7254 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:36:22.526  7239  7254 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:36:22.526  7239  7254 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:36:22.526  7239  7254 I Adreno-EGL: Remote Branch: 
09-09 13:36:22.526  7239  7254 I Adreno-EGL: Local Patches: 
09-09 13:36:22.526  7239  7254 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:36:22.593  6450  6450 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:36:22.595   957  1631 W libprocessgroup: failed to open /acct/uid_1000/pid_7797/cgroup.procs: No such file or directory
,09-09 13:36:22.598  2866  2866 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:22
09-09 13:36:22.599  2866  2866 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 13:36:22.599  2866  2866 D WeatherAncestor: connectivity changed - connection : true
09-09 13:36:22.600  2866  2866 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 13:36:22.600  2866  2866 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:22
09-09 13:36:22.600  2866  2866 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:22.600  2866  2866 D WeatherService: 2 : shouldTimeTickRegistered : false
,09-09 13:36:22.668   957  2125 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8049 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-09 13:36:22.697  7018  7751 I CheckinUtil: Classify the device as Phone.
,09-09 13:36:22.724  7018  7751 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:22.725  7018  7751 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:22.725  7018  7751 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,09-09 13:36:22.725  7018  7751 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:22.726   281  1043 E BandwidthController: [LG DATA] No such appUid: 10006
09-09 13:36:22.726   281  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-09 13:36:22.726   281  8069 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-09 13:36:22.726   281  8069 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:22.727   281  8069 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-09 13:36:22.727   281  8069 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:36:22.768   281  8069 D libc-netbsd: res_queryN name = xxxxx succeed
,09-09 13:36:22.769  7018  7751 I System.out: propertyValue:false
09-09 13:36:22.860  8049  8049 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 13:36:22.871  7018  7751 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:22.871  7018  7751 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:22.979  7018  7751 I CheckinTask: Sending checkin request (11383 bytes)
,09-09 13:36:23.091  8049  8081 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-09 13:36:23.091  8049  8081 I Babel_SMS: MmsConfig.loadMmsSettings
09-09 13:36:23.094  8049  8081 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-09 13:36:23.094  8049  8081 I Babel_SMS: MmsConfig.loadFromDatabase
,09-09 13:36:23.130  8049  8081 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-09 13:36:23.130  8049  8081 I Babel_SMS: MmsConfig.loadFromResources
09-09 13:36:23.133  8049  8081 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-09 13:36:23.134  8049  8081 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-09 13:36:23.187  8049  8049 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
09-09 13:36:23.187  8049  8049 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
09-09 13:36:23.187  8049  8049 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
09-09 13:36:23.187  8049  8049 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
09-09 13:36:23.187  8049  8049 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
09-09 13:36:23.187  8049  8049 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
09-09 13:36:23.188  8049  8049 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
09-09 13:36:23.188  8049  8049 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
09-09 13:36:23.188  8049  8049 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
09-09 13:36:23.188  8049  8049 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
09-09 13:36:23.188  8049  8049 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
09-09 13:36:23.188  8049  8049 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
09-09 13:36:23.188  8049  8049 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
09-09 13:36:23.188  8049  8049 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
09-09 13:36:23.188  8049  8049 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
09-09 13:36:23.188  8049  8049 D SensorManager: found sensor: Motion Accel, handle=46
,09-09 13:36:23.224  8049  8049 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:23.227  8049  8049 I Babel_Crash: startup - clean
,09-09 13:36:23.252  8049  8063 I art     : CheckpointMarkThreadRoots callback created = 0xb042d910
,09-09 13:36:23.286  8049  8088 I Babel   : deleted: false for 0
,09-09 13:36:23.296  8049  8063 I art     : CheckpointMarkThreadRoots callback created = 0xb042d900
,09-09 13:36:23.382   957  1819 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8095 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:36:23.410   957   989 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-09 13:36:23.410   957   989 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,09-09 13:36:23.410   957   989 D sensors_hal_Time: tsOffsetIs: Apps: 172907844106; DSPS: 5764210; Offset : -3014390781
09-09 13:36:23.439  8049  8049 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,09-09 13:36:23.445  8049  8049 W AudioCapabilities: Unsupported mime audio/adpcm
09-09 13:36:23.446  8049  8049 W AudioCapabilities: Unsupported mime audio/g726
09-09 13:36:23.447  7018  7751 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
09-09 13:36:23.447  8049  8049 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-09 13:36:23.449  8049  8049 W AudioCapabilities: Unsupported mime audio/wma-voice
09-09 13:36:23.449  7018  7751 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
09-09 13:36:23.450  8049  8049 W VideoCapabilities: Unsupported mime video/mjpg
09-09 13:36:23.454  8049  8049 W VideoCapabilities: Unsupported mime video/theora
,09-09 13:36:23.481  8049  8049 W AudioCapabilities: Unsupported mime audio/evrc
,09-09 13:36:23.482  8049  8049 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 13:36:23.497  8049  8049 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:36:23.506  8049  8049 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-09 13:36:23.510  8049  8049 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 13:36:23.512  4061  4273 I art     : Explicit concurrent mark sweep GC freed 3136(121KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 1.384ms total 37.112ms
09-09 13:36:23.513  8049  8049 W AudioCapabilities: Unsupported mime audio/evrc
,09-09 13:36:23.552  8049  8049 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-09 13:36:23.584  8049  8049 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 13:36:23.595  8049  8049 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:36:23.597  8049  8049 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:36:23.601  8049  8049 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:36:23.610  8049  8049 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:36:23.623  8049  8049 I vclib   : onServiceConnected
09-09 13:36:23.623  8049  8049 W Babel   : Attempted to change video mute state without an active call.
,09-09 13:36:23.631  8049  8121 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:23.631  8049  8121 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:23.632  8049  8121 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:23.632  8049  8121 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:23.632   281  1043 E BandwidthController: [LG DATA] No such appUid: 10061
09-09 13:36:23.632   281  1043 D DnsProxyListener: App 10061 tries DNS query. Accept family:0 protocol:0
09-09 13:36:23.633   281  8124 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-09 13:36:23.633   281  8124 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:23.633   281  8124 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-09 13:36:23.633   281  8124 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:36:23.633   281  8124 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:36:23.634  8049  8121 I System.out: propertyValue:false
09-09 13:36:23.636  8049  8049 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
09-09 13:36:23.645   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:23.645   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 13:36:23.645   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:36:23.647  8095  8122 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-09 13:36:23.651   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:23.651   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:36:23.651   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:23.651  8095  8122 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 13:36:23.652  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-09 13:36:23.653  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-09 13:36:23.663   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:23.663   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 13:36:23.663   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:23.664  8095  8125 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-09 13:36:23.668   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:23.668   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:36:23.668   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:23.669  8095  8125 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 13:36:23.675  8095  8095 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 13:36:23.675  8095  8095 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 13:36:23.675  8095  8095 I GAv4    :   adb logcat -s GAv4
09-09 13:36:23.695  8095  8095 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
09-09 13:36:23.695  8049  8121 I Babel   : connection state changed from UNKNOWN to CONNECTED
,09-09 13:36:23.700   957  1874 I ActivityManager: Killing 7834:com.lge.sync/1000 (adj 15): empty #11
,09-09 13:36:23.703  7018  7751 I CheckinUtil: Classify the device as Phone.
09-09 13:36:23.729  8095  8095 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:36:23.735  8095  8129 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
09-09 13:36:23.752   957  1379 W libprocessgroup: failed to open /acct/uid_1000/pid_7834/cgroup.procs: No such file or directory
,09-09 13:36:23.768  7018  7751 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,09-09 13:36:23.781  7018  7751 I CheckinChimeraService: Checking schedule, now: 1473420983781 next: 1473948232768
09-09 13:36:23.781  7018  7751 I CheckinChimeraService: active receiver: disabled
,09-09 13:36:23.817  7018  8131 I CheckinChimeraService: Checking schedule, now: 1473420983817 next: 1473948232768
,09-09 13:36:23.817  7018  8131 I CheckinChimeraService: active receiver: disabled
,09-09 13:36:23.827  7018  7018 D CheckinChimeraService: Recording last checkin time for package unspecified as 1473420983826
,09-09 13:36:23.853   957  1873 I ActivityManager: Killing 7857:com.lge.qremote/u0a106 (adj 15): empty #11
,09-09 13:36:23.882   957  1873 I ActivityManager: Killing 7878:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #12
,09-09 13:36:23.973   957  1901 W libprocessgroup: failed to open /acct/uid_10106/pid_7857/cgroup.procs: No such file or directory
09-09 13:36:23.975   957  1801 W libprocessgroup: failed to open /acct/uid_10089/pid_7878/cgroup.procs: No such file or directory
,09-09 13:36:24.141  8095  8095 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,09-09 13:36:24.179  8095  8095 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3675-3677)
09-09 13:36:24.180  8095  8095 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 13:36:24.188  8095  8095 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {293ffe08}
09-09 13:36:24.189  8095  8095 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:36:24.189  8095  8095 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 13:36:24.205  8095  8095 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 13:36:24.206  8095  8095 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:36:24.207  8095  8095 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 13:36:24.219   296   351 I ThermalEngine: Sensor:pa_therm0:36000 mC
09-09 13:36:24.229  8095  8095 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 13:36:24.237  8095  8095 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:36:24.237  8095  8095 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:36:24.238  8095  8095 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:36:24.238  8095  8095 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:36:24.238  8095  8095 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:36:24.238  8095  8095 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:36:24.238  8095  8095 I Adreno-EGL: Remote Branch: 
09-09 13:36:24.238  8095  8095 I Adreno-EGL: Local Patches: 
09-09 13:36:24.238  8095  8095 I Adreno-EGL: Reconstruct Branch: 
09-09 13:36:24.328   285  1581 V AudioPolicyService: registerClient() client 0xb4027160, uid 10079
,09-09 13:36:24.332  8095  8165 W AudioManagerAndroid: Requires BLUETOOTH permission
09-09 13:36:24.334  8095  8095 I NSApplication: Starting up...
09-09 13:36:24.387   957  1631 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8170 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:24.388   957  1631 I ActivityManager: Killing 7896:com.google.android.music:main/u0a81 (adj 15): empty #11
09-09 13:36:24.444   957  2125 W libprocessgroup: failed to open /acct/uid_10081/pid_7896/cgroup.procs: No such file or directory
,09-09 13:36:24.625   957   975 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8189 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:24.628   957   975 I ActivityManager: Killing 7929:com.lge.email/u0a21 (adj 15): empty #11
09-09 13:36:24.672   957   974 W libprocessgroup: failed to open /acct/uid_10021/pid_7929/cgroup.procs: No such file or directory
,09-09 13:36:24.846   957  2125 I art     : Explicit concurrent mark sweep GC freed 27810(1390KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.950ms total 167.763ms
,09-09 13:36:24.868  8189  8189 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:36:25.093  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:25.093  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:36:25.093  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:25.093  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17d9b933 not in the list
09-09 13:36:25.093  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:25.093  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:36:25.093  6450  6534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 13:36:25.093  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:36:25.093  6450  6534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:36:25.094  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:25.095  6450  6534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:36:25.096  6450  6450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:36:25.096  6450  6450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:36:25.096  6450  6450 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:36:25.096  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e9394f0 not in the list
09-09 13:36:25.096  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:25.096  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:25.096  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:25.098  6450  6534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:25.098  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:25.098  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:25.098  6450  6534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17d9b933 not in the list
09-09 13:36:25.098  6450  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:25.098  6450  6534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e9394f0 not in the list
09-09 13:36:25.098  6450  6534 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:25.098  6450  6534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:25.098  6450  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:25.101  6450  6534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 13:36:25.103  6450  6534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 13:36:25.105  6450  6534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 13:36:25.105  6450  6534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:36:25.105  6450  6534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: fa,lse - Stop operation: Should affect listening to advertisements only
,09-09 13:36:25.106  6450  6534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 13:36:25.122  6450  8211 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 982, name: My test thread name)
,09-09 13:36:25.138   957  1783 I ActivityManager: Killing 7955:com.lge.lgdmsclient/1000 (adj 15): empty #11
,09-09 13:36:25.223   957  1843 W libprocessgroup: failed to open /acct/uid_1000/pid_7955/cgroup.procs: No such file or directory
,09-09 13:36:25.243  1370  1370 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,09-09 13:36:25.261  1749  1765 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
09-09 13:36:25.266  1749  1765 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-09 13:36:25.266  1749  1765 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-09 13:36:25.272  1749  1765 V TelecomServiceImpl: getCallState : 0
,09-09 13:36:25.274  1749  2368 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
09-09 13:36:25.274  1749  2368 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-09 13:36:25.274  1749  2368 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-09 13:36:25.277  1370  1370 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
09-09 13:36:25.279  1370  1370 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
09-09 13:36:25.287  1730  8214 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:25.287  1730  8214 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:36:25.287  1730  8214 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:25.287  1730  8214 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:25.287   281  1043 E BandwidthController: [LG DATA] No such appUid: 10006
09-09 13:36:25.288   281  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,09-09 13:36:25.288   281  8215 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-09 13:36:25.289   281  8215 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:36:25.289   281  8215 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-09 13:36:25.289   281  8215 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:36:25.329   281  8215 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:36:25.330  1730  8214 I System.out: propertyValue:false
,09-09 13:36:25.333   957  2062 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=8216 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-09 13:36:25.392  8216  8216 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 13:36:25.407  1730  8214 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:36:25.407  1730  8214 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:36:25.453   957  1056 D BluetoothManagerService: Message: 20
09-09 13:36:25.454   957  1056 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3afc9a8c:true
,09-09 13:36:25.463  2050  2072 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:25.464  2050  3653 D BluetoothAdapterService(667769746): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27581478
09-09 13:36:25.511   957  1843 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=8240 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-09 13:36:25.575   957  1283 V AlarmManager: RTC_WAKEUP set : Alarm{1d5eca51 type 0 when 1473420985569 com.google.android.googlequicksearchbox} when 1473420985569
,09-09 13:36:25.597  6450  6450 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:36:25.785  8240  8240 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:25.786  8240  8240 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-09 13:36:25.786  8240  8240 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:36:25.787  8240  8240 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 13:36:25.787  8240  8240 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 13:36:25.870  8240  8240 I IndexDatabaseHelper: Using schema version: 115
,09-09 13:36:25.873  8240  8240 I IndexDatabaseHelper: Index is fine
09-09 13:36:26.028  8240  8240 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:26.069  8240  8240 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:26.122   957  1631 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8266 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-09 13:36:26.123   957  1631 I ActivityManager: Killing 7978:com.lge.appbox.client/u0a11 (adj 15): empty #11
09-09 13:36:26.147   957  1901 W libprocessgroup: failed to open /acct/uid_10011/pid_7978/cgroup.procs: No such file or directory
,09-09 13:36:26.228  8266  8266 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-09 13:36:26.233  8266  8266 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:36:26.233  8266  8266 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:26.235   957  1873 I ActivityManager: Killing 8004:com.google.android.setupwizard/u0a38 (adj 15): empty #11
09-09 13:36:26.254   957  1801 W libprocessgroup: failed to open /acct/uid_10038/pid_8004/cgroup.procs: No such file or directory
,09-09 13:36:26.272  8240  8240 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:26.277  8240  8240 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:26.282  8266  8266 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 13:36:26.282  8266  8266 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:36:26.282  8266  8266 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:26.288  8240  8240 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:26.293  8240  8240 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:26.297  8266  8266 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 13:36:26.297  8266  8266 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:36:26.297  8266  8266 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:26.303  8240  8240 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:36:26.307  8240  8240 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:26.310  8266  8266 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:26.323  8240  8240 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 13:36:26.323  8240  8240 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 13:36:26.323  8240  8240 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 13:36:26.323  8240  8240 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-09 13:36:26.326  8240  8240 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 13:36:26.342  8240  8240 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 13:36:26.342  8240  8240 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
,09-09 13:36:26.343  8240  8240 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 13:36:26.343  8240  8240 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 13:36:26.343  8240  8240 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 13:36:26.343  8240  8240 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-09 13:36:26.343  8240  8240 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 13:36:26.392   957  1843 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=8290 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-09 13:36:26.418   310   310 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 336us total 31.269ms
,09-09 13:36:26.446   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 317us total 25.939ms
,09-09 13:36:26.474   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 389us total 25.042ms
,09-09 13:36:26.479  8290  8290 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:36:26.480  8290  8290 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-09 13:36:26.483  8290  8290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:36:26.485  8290  8290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:36:26.494  8240  8240 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:36:26.498  8290  8312 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:36:26.502  8240  8240 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:26.504  8266  8266 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-09 13:36:26.505  8290  8312 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:36:26.505  8266  8266 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:36:26.505  8266  8266 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:26.505  8290  8311 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:36:26.509  8290  8311 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,09-09 13:36:26.522  8290  8311 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,09-09 13:36:26.526  8290  8290 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
09-09 13:36:26.527  8290  8290 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,09-09 13:36:26.528  8290  8290 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:36:26.530  8290  8290 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:36:26.534  8290  8290 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
09-09 13:36:26.576   957  1801 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8323 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,09-09 13:36:26.586   957  1801 I ActivityManager: Killing 8031:com.lge.drmservice/u0a51 (adj 15): empty #11
,09-09 13:36:26.622   957  1873 W libprocessgroup: failed to open /acct/uid_10051/pid_8031/cgroup.procs: No such file or directory
,09-09 13:36:26.684  8323  8323 D PhoneMonitor: Register our PhoneStateListener
,09-09 13:36:26.704  8323  8323 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-09 13:36:26.705  8323  8323 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-09 13:36:26.706  8323  8323 D TelephonyAutoProfiling: [parse] Load xml
,09-09 13:36:26.708  8323  8323 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-09 13:36:26.708  8323  8323 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
09-09 13:36:26.716  8323  8323 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,09-09 13:36:26.730  7018  7018 D GCM     : COMPAT: Enabling multi user even though supportsMultipleUsers=false
,09-09 13:36:26.740  7018  7018 D GCM     : COMPAT: Multi user ser=0 current=0
,09-09 13:36:26.751  1730  8344 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-09 13:36:26.762  7018  8345 I CheckinChimeraService: Checking schedule, now: 1473420986762 next: 1473421013768
09-09 13:36:26.762  7018  8345 I CheckinChimeraService: active receiver: disabled
,09-09 13:36:26.851  8240  8240 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:36:26.857  8240  8240 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:36:26.859  8266  8266 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:26.868  8240  8240 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:36:26.874  8240  8240 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:26.876  8266  8266 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:26.877   957  2062 I ActivityManager: Killing 8049:com.google.android.talk/u0a61 (adj 15): empty #11
,09-09 13:36:26.913   957  1801 W libprocessgroup: failed to open /acct/uid_10061/pid_8049/cgroup.procs: No such file or directory
,09-09 13:36:26.923  8290  8290 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:36:26.923  8290  8290 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:36:26.924  8290  8290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:36:26.926  8290  8290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,09-09 13:36:26.930  8240  8240 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:36:26.932  8290  8350 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:36:26.934  8290  8350 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-09 13:36:26.935  8290  8351 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:36:26.935  8290  8351 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:36:26.935  8240  8240 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:26.944  8290  8350 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,09-09 13:36:26.988   957  1631 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8352 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
09-09 13:36:27.003  8290  8290 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
09-09 13:36:27.003  8290  8290 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
09-09 13:36:27.003  8290  8290 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,09-09 13:36:27.005  8290  8290 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:36:27.008  8290  8290 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,09-09 13:36:27.121  6450  6534 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 982
09-09 13:36:27.121  6450  6534 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 982, name: My test thread name)
,09-09 13:36:27.124  6450  8369 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 983, name: My test thread name)
09-09 13:36:27.124  6450  8369 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 983, thread name: My test thread name)
09-09 13:36:27.124  6450  8369 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 983, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-09 13:36:27.125  6450  8211 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 982, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
09-09 13:36:27.125  8352  8352 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 13:36:27.125  8352  8352 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-09 13:36:27.126  6450  6534 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:27.130  6450  8370 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 987, name: My test thread name)
09-09 13:36:27.131  6450  8370 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 987, thread name: My test thread name): Test exception.
09-09 13:36:27.131  6450  8370 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 987, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-09 13:36:27.135  8352  8352 V [BNRBootReceiver]: Boot Receiver Return
09-09 13:36:27.136  8352  8352 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-09 13:36:27.138  8240  8240 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:36:27.141  6450  6534 E com.test.thalitest.ThaliTestRunner: testIsBluetoothEnabled(io.jxcore.node.ConnectivityMonitorTest)
09-09 13:36:27.141  6450  6534 E com.test.thalitest.ThaliTestRunner: Returns proper state of BT when switched on
09-09 13:36:27.141  6450  6534 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-09 13:36:27.141  6450  6534 E com.test.thalitest.ThaliTestRunner:      but: was <false>
09-09 13:36:27.142  8240  8240 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:27.148   957  1631 I ActivityManager: Killing 8095:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: Returns proper state of BT when switched on
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner:      but: was <false>
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testIsBluetoothEnabled(ConnectivityMonitorTest.java:325)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.Thali,TestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:74)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$1.Receiver(RegisterExecuteUT.java:26)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: testExecuteStopOperation(io.jxcore.node.StartStopOperationHandlerTest)
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: mDiscoveryManager1 state should be NOT_STARTED
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner: Expected: is <NOT_STARTED>
09-09 13:36:27.152  6450  6534 E com.test.thalitest.ThaliTestRunner:      but: was <WAITING_FOR_SERVICES_TO_BE_ENABLED>
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: mDiscoveryManager1 state should be NOT_STARTED
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: Expected: is <NOT_STARTED>
09-09 13:36:27.157  6450  6534 E com.t,est.thalitest.ThaliTestRunner:      but: was <WAITING_FOR_SERVICES_TO_BE_ENABLED>
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StartStopOperationHandlerTest.testExecuteStopOperation(StartStopOperationHandlerTest.java:203)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:74)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$1.Receiver(RegisterExecuteUT.java:26)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-09 13:36:27.157  6450  6534 E com.test.thalitest.ThaliTestRunner: testCheckCurrentOperationStatus(io.jxcore.node.StartStopOperationHandlerTest)
09-09 13:36:27.164  6450  6534 I jxcore-log: Failed to execute UT.
09-09 13:36:27.164  6450  6534 I jxcore-log: 
09-09 13:36:27.165  6450  6534 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
09-09 13:36:27.165  6450  6534 I jxcore-log: 
,--------- beginning of crash
09-09 13:36:27.167  6450  6534 E AndroidRuntime: FATAL EXCEPTION: Thread-779
09-09 13:36:27.167  6450  6534 E AndroidRuntime: Process: com.test.thalitest, PID: 6450
09-09 13:36:27.167  6450  6534 E AndroidRuntime: java.lang.NullPointerException: println needs a message
09-09 13:36:27.167  6450  6534 E AndroidRuntime: 	at android.util.Log.println_native(Native Method)
09-09 13:36:27.167  6450  6534 E AndroidRuntime: 	at android.util.Log.e(Log.java:232)
09-09 13:36:27.167  6450  6534 E AndroidRuntime: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:78)
09-09 13:36:27.167  6450  6534 E AndroidRuntime: 	at com.test.thalitest.RegisterExecuteUT$1.Receiver(RegisterExecuteUT.java:26)
09-09 13:36:27.167  6450  6534 E AndroidRuntime: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-09 13:36:27.167  6450  6534 E AndroidRuntime: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-09 13:36:27.167  6450  6534 E AndroidRuntime: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-09 13:36:27.167  6450  6534 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:36:27.167  6450  6534 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:36:27.167  6450  6534 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:36:27.167  6450  6534 E AndroidRuntime: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-09 13:36:27.255   957  2062 W libprocessgroup: failed to open /acct/uid_10079/pid_8095/cgroup.procs: No such file or directory
,09-09 13:36:27.259  8240  8240 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-09 13:36:27.261  8240  8240 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-09 13:36:27.263  8240  8240 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:27.267  8240  8240 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:27.284  8240  8240 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:27.290  8240  8240 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:27.300   957  2125 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
,09-09 13:36:27.306   957  2125 D InputDispatcher: Focus left window: Window{7890a07 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 13:36:27.315  6450  6534 I Process : Sending signal. PID: 6450 SIG: 9
,09-09 13:36:27.318   957  1379 I ActivityManager: Killing 8170:com.android.chrome/u0a48 (adj 15): empty #11
09-09 13:36:27.369   957  1801 I WindowState: WIN DEATH: Window{7890a07 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 13:36:27.380   957  1801 D InputDispatcher: Window went away: Window{7890a07 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 13:36:27.395   957   975 W libprocessgroup: failed to open /acct/uid_10048/pid_8170/cgroup.procs: No such file or directory
,09-09 13:36:27.411   957   957 V ActivityManager: Display changed displayId=0
09-09 13:36:27.412  1749  1749 D DSDPConnection: Display #0 changed.
,09-09 13:36:27.462   957  1293 I ActivityManager: Process com.test.thalitest (pid 6450) has died
,09-09 13:36:27.474  8240  8240 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:27.480  1875  1875 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
09-09 13:36:27.480  8240  8240 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:27.489  8240  8240 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:27.497  8240  8240 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:27.514  8240  8240 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:27.520  8240  8240 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:36:27.532  1875  1875 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,09-09 13:36:27.534  8240  8240 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:36:27.538  8240  8240 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:27.545  1875  1875 I [LGHome]EVENT: [LauncherModel.java:1358:startLoader()]startLoader isLaunching=true
09-09 13:36:27.554  1875  2010 I [LGHome]Launcher.Model: [LauncherModel.java:1475:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
09-09 13:36:27.554  8240  8240 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:27.559  8240  8240 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:27.560  1875  1875 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-09 13:36:27.563  1875  1875 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
09-09 13:36:27.565  1875  1875 I Activity: Activity.onPostResume() called 
,09-09 13:36:27.580  1875  1875 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
,09-09 13:36:27.580  8240  8240 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:36:27.585  8240  8240 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:27.590  8266  8266 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-09 13:36:27.595  1875  8383 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
09-09 13:36:27.597  8266  8266 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:27.604  8240  8240 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:27.609  8240  8240 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:27.614  8266  8266 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-09 13:36:27.615   957  1055 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
09-09 13:36:27.615  8266  8266 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:36:27.619   957  1055 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
09-09 13:36:27.619   957  1819 D InputDispatcher: Focus entered window: Window{4564473 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
09-09 13:36:27.622  1370  1370 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
09-09 13:36:27.623  1370  1370 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
09-09 13:36:27.623  1370  1370 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
09-09 13:36:27.623  1370  1370 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
09-09 13:36:27.627   957  1055 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
09-09 13:36:27.628   957  1055 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
09-09 13:36:27.628   957  1055 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-09 13:36:27.629   957  1055 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@123fde89,  pkg=WindowManager.LayoutParams
,09-09 13:36:27.629   957  1055 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
09-09 13:36:27.648  1875  1875 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
,09-09 13:36:27.669  1875  1875 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,09-09 13:36:27.672   957  1901 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8385 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:27.699  1875  1875 I PhoneWindow: [setNavigationBarColor] color=0x 0
,09-09 13:36:27.706   957   975 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,09-09 13:36:27.710   957   975 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6450 uid 10030
,09-09 13:36:27.742  8372  8372 D AndroidRuntime: 
09-09 13:36:27.742  8372  8372 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-09 13:36:27.755  8372  8372 D AndroidRuntime: CheckJNI is OFF
,09-09 13:36:27.800  1875  1875 I [LGHome]Launcher.Model: [LauncherModel.java:2270:run()] LauncherModel bind current page shortcut
,09-09 13:36:27.813  1875  1875 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-09 13:36:27.824   957  1057 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{12e0ad3 u0 com.lge.launcher2/.Launcher t258} time:177322
,09-09 13:36:27.836  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-09 13:36:27.838  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,09-09 13:36:27.841  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-09 13:36:27.844  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-09 13:36:27.848  8385  8385 I MusicStore: Database version: 120
09-09 13:36:27.893  1875  1875 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,09-09 13:36:27.906   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:27.906   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,09-09 13:36:27.906   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:27.907  8385  8385 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-09 13:36:27.956  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-09 13:36:27.956  1875  1875 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
09-09 13:36:27.957  1875  1875 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,09-09 13:36:27.991  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,09-09 13:36:27.996  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
09-09 13:36:27.996  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
09-09 13:36:27.997  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
09-09 13:36:28.001  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
09-09 13:36:28.009  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,09-09 13:36:28.009  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
09-09 13:36:28.013  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
09-09 13:36:28.014  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
09-09 13:36:28.015  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
09-09 13:36:28.025  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
09-09 13:36:28.038  1875  1875 W Resources: Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,09-09 13:36:28.054   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:28.054   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-09 13:36:28.054   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:28.055  8385  8385 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,09-09 13:36:28.058   246   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:28.058   246   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-09 13:36:28.058   246   331 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:28.058  8385  8385 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-09 13:36:28.088  8385  8385 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 13:36:28.089  8385  8385 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 13:36:28.103  8372  8372 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 13:36:28.136  8385  8385 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 13:36:28.169  1875  1875 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,09-09 13:36:28.202  8385  8385 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-09 13:36:28.203  8385  8385 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5458c02: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-09 13:36:28.205  8385  8385 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-09 13:36:28.205  8385  8385 D AndroidMusic: GMSCore installation verified
09-09 13:36:28.212  8385  8385 I ConfigStore: Config Database version: 1
09-09 13:36:28.213   957  1026 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
09-09 13:36:28.259  1875  1875 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-09 13:36:28.260  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
09-09 13:36:28.260  1875  1875 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
09-09 13:36:28.260  1875  1875 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,09-09 13:36:28.349   957  1062 W PackageSettings: Skipping PackageSetting{248f896e com.example.hello/10317} due to missing metadata
,09-09 13:36:28.383  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,09-09 13:36:28.385  1875  1875 I Choreographer: Skipped 33 frames!  The application may be doing too much work on its main thread.
09-09 13:36:28.386  1875  1875 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
09-09 13:36:28.387  1875  1875 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-09 13:36:28.389  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-09 13:36:28.391  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
09-09 13:36:28.393   957  1062 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
09-09 13:36:28.393  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,09-09 13:36:28.395  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
09-09 13:36:28.397  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
09-09 13:36:28.400  1623  1623 E b       : Unable to connect to the editor to retrieve text... will retry later
09-09 13:36:28.410  1875  1875 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-09 13:36:28.411  1370  1370 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-09 13:36:28.414  1875  1875 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-09 13:36:28.414  1875  1875 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
09-09 13:36:28.415  1875  1875 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-09 13:36:28.415  1875  1875 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-09 13:36:28.417  1730  2472 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 13:36:28.424  1837  1837 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,09-09 13:36:28.432   957  1286 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-09 13:36:28.432  1875  2207 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,09-09 13:36:28.433  1875  2207 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-09 13:36:28.462  3706  3706 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-09 13:36:28.462  3706  3706 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-09 13:36:28.462  3706  3706 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-09 13:36:28.463  3706  3706 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
09-09 13:36:28.463  3706  3706 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:36:28.463  3706  3706 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:36:28.463  3706  3706 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:36:28.463  3706  3706 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
09-09 13:36:28.463  3706  3706 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:28.463  3706  3706 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:36:28.463  3706  3706 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
09-09 13:36:28.463  3706  3706 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,09-09 13:36:28.480  1370  1370 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,09-09 13:36:28.486  1935  1935 I art     : Explicit concurrent mark sweep GC freed 4378(333KB) AllocSpace objects, 5(119KB) LOS objects, 40% free, 12MB/20MB, paused 1.588ms total 90.963ms
09-09 13:36:28.493  1875  1875 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,09-09 13:36:28.516  1875  1875 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-09 13:36:28.516  1875  1875 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-09 13:36:28.519  1875  1875 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,09-09 13:36:28.521  7018  7187 I CheckinService: Done disabling old GoogleServicesFramework version
,09-09 13:36:28.545   957   957 D administrator: Handling package changes for user 0
,09-09 13:36:28.559  1875  1875 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@5458c02 time:178057
,09-09 13:36:28.589  1370  1370 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,09-09 13:36:28.593  1370  1370 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-09 13:36:28.634   957  1874 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8428 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:28.644  1875  1875 I art     : Explicit concurrent mark sweep GC freed 26567(1446KB) AllocSpace objects, 18(2MB) LOS objects, 40% free, 15MB/25MB, paused 5.342ms total 75.952ms
,09-09 13:36:28.712  8385  8385 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-09 13:36:28.721  8385  8385 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
09-09 13:36:28.723  8385  8399 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3f0
,09-09 13:36:28.763  8385  8385 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 13:36:28.773  8428  8428 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
09-09 13:36:28.779  8385  8399 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3d0
,09-09 13:36:28.801  1370  1526 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-09 13:36:28.801  1370  1526 D KeyguardModel: createShortcutInfo...
09-09 13:36:28.802  1875  1875 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,09-09 13:36:28.805  1370  1526 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-09 13:36:28.805  1370  1526 D KeyguardModel: createShortcutInfo...
09-09 13:36:28.814  1370  1526 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:36:28.816  1370  1526 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-09 13:36:28.818  1370  1526 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:36:28.820  1370  1526 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-09 13:36:28.821  1370  1526 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-09 13:36:28.821  1370  1526 D KeyguardModel: createShortcutInfo...
09-09 13:36:28.835  1370  1526 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 13:36:28.838   957   957 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-09 13:36:28.838   957   957 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-09 13:36:28.839  1370  1526 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:36:28.839  1370  1526 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-09 13:36:28.845   957   957 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 13:36:28.853   957  1346 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
,09-09 13:36:28.856  1370  1526 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-09 13:36:28.856  1370  1526 D KeyguardModel: createShortcutInfo...
09-09 13:36:28.862  1370  1526 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:28.864  1370  1526 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 13:36:28.865  1370  1526 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-09 13:36:28.866  1370  1526 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:36:28.866  1370  1526 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,09-09 13:36:28.873  1370  1526 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-09 13:36:28.873  1370  1526 D KeyguardModel: createShortcutInfo...
09-09 13:36:28.879  8385  8385 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 13:36:28.896   957  1062 I art     : Explicit concurrent mark sweep GC freed 47368(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 24MB/36MB, paused 3.742ms total 413.032ms
,09-09 13:36:28.919   957  1901 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8447 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
09-09 13:36:28.922  1370  1370 D KeyguardModel: handleShortcutListChanged...
09-09 13:36:28.945  1370  1526 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,09-09 13:36:28.945  1370  1526 D KeyguardModel: createShortcutInfo...
09-09 13:36:28.951  1370  1526 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-09 13:36:28.951  1370  1526 D KeyguardModel: createShortcutInfo...
09-09 13:36:28.952  1370  1526 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:36:28.952  1370  1526 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-09 13:36:28.954  1370  1526 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-09 13:36:28.954  1370  1526 D KeyguardModel: createShortcutInfo...
09-09 13:36:28.956  1370  1526 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:36:28.957  1370  1526 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-09 13:36:28.958  1370  1526 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-09 13:36:28.958  1370  1526 D KeyguardModel: createShortcutInfo...
,09-09 13:36:28.960  1370  1526 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:36:28.960  1370  1526 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-09 13:36:28.963  1370  1526 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-09 13:36:28.963  1370  1526 D KeyguardModel: createShortcutInfo...
,09-09 13:36:28.980  8372  8372 D AndroidRuntime: Shutting down VM
09-09 13:36:28.985  8385  8385 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
09-09 13:36:28.990  1370  1370 D KeyguardModel: handleShortcutListChanged...
09-09 13:36:28.993  8385  8385 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:36:29.017  8447  8447 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:29.017  8447  8447 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 13:36:29.018  8447  8447 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 13:36:29.029   957  1843 I ActivityManager: Killing 8189:com.google.android.apps.plus/u0a86 (adj 15): empty #11
09-09 13:36:29.094   957  1819 W libprocessgroup: failed to open /acct/uid_10086/pid_8189/cgroup.procs: No such file or directory
,09-09 13:36:29.097  1784  1784 D LCardEmulationManager: getHceAppCount hostAppNum : 0
,09-09 13:36:29.097  1784  1784 D LCardEmulationManager: getDefaultRoute
09-09 13:36:29.098  8385  8404 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
09-09 13:36:29.099  8447  8447 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
09-09 13:36:29.109  8447  8447 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,09-09 13:36:29.151   957  1025 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:36:29.223   296   351 I ThermalEngine: Sensor:pa_therm0:36000 mC
09-09 13:36:29.228   957  1025 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-09 13:36:29.250   957  1062 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8470 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-09 13:36:29.253  1875  1875 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-09 13:36:29.278  8447  8447 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
09-09 13:36:29.291  8290  8290 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:29.292  8290  8290 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-09 13:36:29.294  8290  8290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:36:29.297  8290  8290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:36:29.301  8447  8447 I HubEmail: JNI_OnLoad()
09-09 13:36:29.301  8447  8447 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:36:29.302  8447  8447 I HubEmail: registerNatives()
09-09 13:36:29.302  8447  8447 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:36:29.302  8447  8447 I HubEmail: registerNativeMethods()
09-09 13:36:29.302  8447  8447 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:36:29.302  8447  8447 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-09 13:36:29.313  8290  8488 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:36:29.315  8290  8491 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:29.315  8290  8491 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:36:29.315  8290  8488 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,09-09 13:36:29.336   957  1631 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=8492 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-09 13:36:29.339  8447  8489 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:29.340  8290  8488 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:36:29.346  8290  8290 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
09-09 13:36:29.348  8290  8290 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,09-09 13:36:29.348  8290  8290 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:36:29.349   957  1874 I ActivityManager: Killing 8323:com.google.android.setupwizard/u0a38 (adj 15): empty #11
09-09 13:36:29.350  8290  8290 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:36:29.356  8290  8290 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
09-09 13:36:29.382   957  1873 W libprocessgroup: failed to open /acct/uid_10038/pid_8323/cgroup.procs: No such file or directory
,09-09 13:36:29.390   957  1801 I ActivityManager: Killing 7239:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
09-09 13:36:29.416  8492  8492 I AppUp4:AppBoxCP: onCreate
,09-09 13:36:29.417  8492  8492 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-09 13:36:29.426  8492  8492 W FileUtils: Failed to chmod(/data/data/com.lge.appbox.client/databases/appbox.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
09-09 13:36:29.426  8492  8492 I AppUp4:DB:  setFingerPrint start
09-09 13:36:29.427  8492  8492 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
09-09 13:36:29.432  8492  8492 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
09-09 13:36:29.432  8492  8492 I AppUp4:DB:  SDK version = 21
09-09 13:36:29.433  8492  8492 I AppUp4:DB:  beforefinger == newfinger no write in DB
,09-09 13:36:29.442   957  2125 W libprocessgroup: failed to open /acct/uid_10006/pid_7239/cgroup.procs: No such file or directory
09-09 13:36:29.444  8492  8492 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-09 13:36:29.445  8492  8492 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 13:36:29.445  8492  8492 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:29.447  8492  8492 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 13:36:29.447  8492  8492 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-09 13:36:29.451  8492  8492 I AppUp4:CustModeStarterReceiver: onReceive
09-09 13:36:29.451  8492  8492 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:29.455  8492  8492 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@108257c7
09-09 13:36:29.455  8492  8492 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:36:29.460  8492  8492 D AppUp4:CustFacade: isSimDevice : true

```
