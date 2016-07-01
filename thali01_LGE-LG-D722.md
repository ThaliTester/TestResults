#### Test 757892680c366d1_thali01_LGE-LG-D722 Logs


```
--------- beginning of main
07-01 12:08:19.879   968  1345 D qdlights: set_light_backlight: 10
,07-01 12:08:21.370  6669  6669 D AndroidRuntime: 
07-01 12:08:21.370  6669  6669 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-01 12:08:21.374  6669  6669 D AndroidRuntime: CheckJNI is OFF
07-01 12:08:21.607  6669  6669 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-01 12:08:21.628   968  1941 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-01 12:08:21.673   968  1941 D ActivityManager: setTaskToReturnTo : TaskRecord{3835fb1c #241 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-01 12:08:21.675   968  1941 D ActivityManager: setTaskToReturnTo : TaskRecord{3835fb1c #241 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-01 12:08:21.687   968  1941 D WindowStateEx: AppWindowTokenEx init.. 
07-01 12:08:21.698   968  1057 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-01 12:08:21.724  1873  1873 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
07-01 12:08:21.749   968  1057 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-01 12:08:21.753   968  1941 D InputDispatcher: Focus left window: Window{1bd153c4 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
07-01 12:08:21.754  6669  6669 D AndroidRuntime: Shutting down VM
07-01 12:08:21.764   968  1057 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-01 12:08:21.764   968  1057 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-01 12:08:21.793   968  1057 D SplitWindow: check instance of lgWin Window{3cfc91b4 u0 Starting com.test.thalitest}
07-01 12:08:21.832   968  1781 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6689 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-01 12:08:21.853  1873  1873 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
07-01 12:08:21.907  1873  1873 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
07-01 12:08:21.922   968  1344 I WindowStateAnimator: Starting window displayed
07-01 12:08:21.927   968  1055 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
07-01 12:08:21.928   968  1055 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
07-01 12:08:21.932   968  1055 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
07-01 12:08:21.932   968  1055 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
07-01 12:08:21.932   968  1055 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-01 12:08:21.933   968  1055 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@28626484,  pkg=WindowManager.LayoutParams
07-01 12:08:21.933   968  1055 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
07-01 12:08:21.943  1370  1370 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
07-01 12:08:21.944  1932  1932 I HotwordDetector: Closing mic
07-01 12:08:21.949  1932  2391 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@2e373871
07-01 12:08:21.949  1932  2391 V AudioRecord: stop()
07-01 12:08:21.949  1932  2391 D AudioRecord: AudioRecord->stop()
07-01 12:08:21.950  1370  1370 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
07-01 12:08:21.950  1370  1370 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
07-01 12:08:21.950  1370  1370 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
07-01 12:08:21.950   288   288 V AudioFlinger: RecordHandle::stop()
07-01 12:08:21.950   288   288 V AudioFlinger: RecordThread::stop
07-01 12:08:21.950   288   288 V AudioFlinger: Record stopped OK
07-01 12:08:21.953   288   288 V AudioPolicyManager: stopInput() input 17
07-01 12:08:21.955   288   288 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
07-01 12:08:21.955   288   288 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
07-01 12:08:21.955   288  1063 V AudioPolicyService: AudioCommandThread() waking up
07-01 12:08:21.955   288  1063 V AudioPolicyService: AudioCommandThread() processing release audio patch
07-01 12:08:21.955   288  1063 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
07-01 12:08:21.955   288  1063 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
07-01 12:08:21.955   288  1063 V AudioFlinger: ThreadBase::setParameters() routing=0
07-01 12:08:21.955   288  1063 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
,07-01 12:08:21.956   288  2488 V AudioFlinger: processConfigEvents_l() remaining events 1
07-01 12:08:21.956   288  2488 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3c5d000
07-01 12:08:21.959   288  2488 D audio_hw_primary: in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
07-01 12:08:22.002   288  2488 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
07-01 12:08:22.002   288  2488 V audio_hw_primary: disable_audio_route: enter: usecase(7)
07-01 12:08:22.002   288  2488 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
07-01 12:08:22.002   288  2488 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-01 12:08:22.004   288  2488 V audio_hw_primary: disable_audio_route: exit
07-01 12:08:22.004   288  2488 E audio_hw_primary: disable_snd_device: enter 144
07-01 12:08:22.005   288  2488 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
07-01 12:08:22.005   288  2488 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
07-01 12:08:22.007   288  2488 V audio_hw_primary: stop_input_stream: exit: status(0)
07-01 12:08:22.007   288  2488 V audio_hw_primary: in_standby: exit:  status(0)
07-01 12:08:22.007   288  2488 V AudioFlinger: RecordThread: loop stopping
07-01 12:08:22.008   288  1063 V AudioPolicyService: AudioCommandThread() going to sleep
07-01 12:08:22.008   288   288 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
07-01 12:08:22.008   288   288 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
07-01 12:08:22.008   288   288 V AudioPolicyService: AudioCommandThread() adding update audio patch list
07-01 12:08:22.008   288   288 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
07-01 12:08:22.008   288  1064 V AudioPolicyService: AudioCommandThread() waking up
07-01 12:08:22.008   288  1064 V AudioPolicyService: AudioCommandThread() processing update audio patch list
07-01 12:08:22.008   288  1064 V AudioPolicyService: AudioCommandThread() going to sleep
07-01 12:08:22.010   288   288 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
07-01 12:08:22.010   288   288 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
07-01 12:08:22.010   288  1063 V AudioPolicyService: AudioCommandThread() waking up
07-01 12:08:22.010   288  1063 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
07-01 12:08:22.010   288  1063 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 288
07-01 12:08:22.010   288  1063 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
07-01 12:08:22.010   288  1063 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
07-01 12:08:22.010   288  2488 V AudioFlinger: RecordThread: loop starting
07-01 12:08:22.010   288  2488 V AudioFlinger: processConfigEvents_l() remaining events 1
07-01 12:08:22.010   288  2488 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
07-01 12:08:22.010   288  2488 V audio_hw_primary: in_set_parameters: exit: status(0)
07-01 12:08:22.010   288  2488 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3c5d000
07-01 12:08:22.010   288  2488 V AudioFlinger: RecordThread: loop stopping
07-01 12:08:22.011   288  1063 V AudioPolicyService: AudioCommandThread() going to sleep
07-01 12:08:22.018  1932  2391 V AudioRecord: stop()
07-01 12:08:22.022  1932  2391 V AudioRecord: stop()
07-01 12:08:22.022  1932  2391 V AudioRecord: stop()
07-01 12:08:22.024   288  1297 V AudioFlinger: releasing 16 from 1932 for -1
07-01 12:08:22.024   288  1297 V AudioFlinger:  decremented refcount to 0
07-01 12:08:22.024   288  1297 V AudioFlinger: purging stale effects
07-01 12:08:22.024   288  1297 V AudioFlinger: RecordHandle::stop()
07-01 12:08:22.024   288  1297 V AudioFlinger: RecordThread::stop
07-01 12:08:22.024   288  1297 V AudioPolicyManager: releaseInput() 17
07-01 12:08:22.024   288  1297 V AudioPolicyManager: closeInput(17)
07-01 12:08:22.024   288  1297 V AudioFlinger: closeInput() 17
07-01 12:08:22.024   288  1297 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-01 12:08:22.025   288  1297 V AudioFlinger: ThreadBase::exit
07-01 12:08:22.025   288  2488 V AudioFlinger: RecordThread: loop starting
07-01 12:08:22.025   288  2488 V AudioFlinger: RecordThread 0xb3c5d000 exiting
07-01 12:08:22.025   288  1297 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546e240)
07-01 12:08:22.025   288  1297 D audio_hw_primary: in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
07-01 12:08:22.025   288  1297 V audio_hw_primary: in_standby: exit:  status(0)
07-01 12:08:22.025  3199  3215 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-01 12:08:22.025  2931  4102 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-01 12:08:22.025   288  1297 V AudioPolicyService: AudioCommandThread() adding update audio port list
07-01 12:08:22.025   968  1633 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-01 12:08:22.026   288  1297 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
07-01 12:08:22.026   288  1297 V AudioPolicyManager: releaseInput() exit
07-01 12:08:22.026  1997  2030 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-01 12:08:22.026   288  1064 V AudioPolicyService: AudioCommandThread() waking up
07-01 12:08:22.026   288  1064 V AudioPolicyService: AudioCommandThread() processing update audio port list
07-01 12:08:22.026   288  1297 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
07-01 12:08:22.026  1747  1762 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-01 12:08:22.026   288  1297 V AudioFlinger: removeClient_l() pid 1932, calling pid 288
07-01 12:08:22.026   288  1064 V AudioPolicyService: AudioCommandThread() going to sleep
07-01 12:08:22.026  1370  2477 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-01 12:08:22.026  1932  1955 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-01 12:08:22.027  1932  2418 I HotwordRecognitionRnr: Stopping hotword detection.
07-01 12:08:22.036  1932  2482 I HotwordRecognitionRnr: Hotword detection finished
07-01 12:08:22.074  6689  6689 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-01 12:08:22.185  6689  6689 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
07-01 12:08:22.250  6689  6689 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 1245-1254)
07-01 12:08:22.250  6689  6689 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 12:08:22.254  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-01 12:08:22.254  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-01 12:08:22.255  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
07-01 12:08:22.287  6689  6689 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2b5a4968}
07-01 12:08:22.288  6689  6689 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 12:08:22.294  6689  6689 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-01 12:08:22.312  6689  6689 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-01 12:08:22.315  6689  6689 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 12:08:22.319  6689  6689 E SysUtils: ApplicationContext is null in ApplicationStatus
07-01 12:08:22.400  6689  6689 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-01 12:08:22.411  6689  6689 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-01 12:08:22.411  6689  6689 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-01 12:08:22.412  6689  6689 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-01 12:08:22.412  6689  6689 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-01 12:08:22.412  6689  6689 I Adreno-EGL: Build Date: 03/02/15 Mon
07-01 12:08:22.412  6689  6689 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-01 12:08:22.412  6689  6689 I Adreno-EGL: Remote Branch: 
07-01 12:08:22.412  6689  6689 I Adreno-EGL: Local Patches: 
07-01 12:08:22.412  6689  6689 I Adreno-EGL: Reconstruct Branch: 
07-01 12:08:22.495   288   288 V AudioPolicyService: registerClient() client 0xb57ec260, uid 10030
07-01 12:08:22.519   968  1056 D BluetoothManagerService: Message: 20
07-01 12:08:22.519   968  1056 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a88f777:true
07-01 12:08:22.546  1997  2028 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
07-01 12:08:22.651  6689  6689 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 12:08:22.665  6689  6689 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-01 12:08:22.670  6689  6689 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-01 12:08:22.676  6689  6689 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-01 12:08:22.676  6689  6689 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-01 12:08:22.694  6689  6689 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-01 12:08:22.703  6689  6689 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 12:08:22.703  6689  6689 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 12:08:22.763  6689  6689 I Activity: Activity.onPostResume() called 
07-01 12:08:22.774  6689  6750 D OpenGLRenderer: Render dirty regions requested: true
07-01 12:08:22.774  6689  6750 I OpenGLRenderer: Initialized EGL, version 1.4
07-01 12:08:22.785  6689  6750 D OpenGLRenderer: Enabling debug mode 0
07-01 12:08:22.805  6689  6689 D Atlas   : Validating map...
07-01 12:08:22.810   968  1834 D SplitWindow: check instance of lgWin Window{a70ac67 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-01 12:08:22.823  6689  6732 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-01 12:08:22.859   968  1834 D InputDispatcher: Focus entered window: Window{a70ac67 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-01 12:08:22.919   968  1805 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
07-01 12:08:22.926   968  1057 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s159ms
07-01 12:08:22.926   968  1057 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3526a325 u0 com.test.thalitest/.MainActivity t241} time:151931
07-01 12:08:22.935  6689  6689 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@38c35462 time:151939
07-01 12:08:23.088  6689  6689 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6689
07-01 12:08:23.255  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,07-01 12:08:23.255  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-01 12:08:23.255  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
07-01 12:08:23.763  6689  6689 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-01 12:08:23.993  6689  6757 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635594496
,07-01 12:08:24.012  6689  6757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-01 12:08:24.012  6689  6757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-01 12:08:24.012  6689  6757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-01 12:08:24.012  6689  6757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-01 12:08:24.012  6689  6757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-01 12:08:24.012  6689  6757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@310f2c47 added. We now have 1 listener(s)
,07-01 12:08:24.018   968  1842 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 12:08:24.023  6689  6757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
07-01 12:08:24.025  6689  6757 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
07-01 12:08:24.026  6689  6757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-01 12:08:24.027  6689  6757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-01 12:08:24.046  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-01 12:08:24.046  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-01 12:08:24.046  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-01 12:08:24.046  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
07-01 12:08:24.046  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-01 12:08:24.046  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-01 12:08:24.046  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-01 12:08:24.046  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-01 12:08:24.046  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-01 12:08:24.046  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-01 12:08:24.046  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-01 12:08:24.046  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19ed9a12 added. We now have 1 listener(s)
,07-01 12:08:24.048  6689  6757 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 12:08:24.054  1997  3780 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
07-01 12:08:24.055  6689  6757 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-01 12:08:24.063  6689  6757 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-01 12:08:24.063  6689  6757 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-01 12:08:24.068  6689  6757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-01 12:08:24.068   968   985 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 12:08:24.069  6689  6757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
07-01 12:08:24.076  1997  3780 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
,07-01 12:08:24.077  6689  6757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 12:08:24.077  6689  6757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:24.077  6689  6757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:08:24.077  6689  6757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:08:24.077  6689  6757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:08:24.077  6689  6757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 12:08:24.077  6689  6757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 12:08:24.077  6689  6757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 12:08:24.077  6689  6757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-01 12:08:24.077  6689  6757 D io.jxcore.node.ConnectivityMonitor: start: OK
07-01 12:08:24.079  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:08:24.080  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:08:24.081  6689  6757 I io.jxcore.node.LifeCycleMonitor: start: OK
07-01 12:08:24.117  6689  6689 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-01 12:08:24.252  6689  6703 I art     : CheckpointMarkThreadRoots callback created = 0x9a285530
,07-01 12:08:24.299  6689  6703 I art     : CheckpointMarkThreadRoots callback created = 0x9a285500
,07-01 12:08:24.346   298   349 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-01 12:08:24.968  6689  6767 W jxcore-log: Initializing JXcore engine
,07-01 12:08:24.969  6689  6767 W jxcore-log: JXcore engine is ready
07-01 12:08:25.093  6767  6767 W Thread-799: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5633]" dev="sockfs" ino=5633 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-01 12:08:25.093  6767  6767 W Thread-799: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-01 12:08:25.093  6767  6767 W Thread-799: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8277]" dev="sockfs" ino=8277 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-01 12:08:25.093  6767  6767 W Thread-799: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
07-01 12:08:25.093  6767  6767 W Thread-799: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
07-01 12:08:25.093  6767  6767 W Thread-799: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[30666]" dev="sockfs" ino=30666 scontext=u:r:untrusted_app:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,07-01 12:08:25.122  6689  6767 W jxcore-log: Starting JXcore engine
,07-01 12:08:25.259  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,07-01 12:08:25.259  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-01 12:08:25.260  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
07-01 12:08:25.288  6689  6767 W jxcore-log: Platform android
07-01 12:08:25.288  6689  6767 W jxcore-log: 
07-01 12:08:25.289  6689  6767 W jxcore-log: Process ARCH arm
07-01 12:08:25.289  6689  6767 W jxcore-log: 
,07-01 12:08:25.360   968   999 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-01 12:08:25.360   968   999 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-01 12:08:25.360   968   999 D sensors_hal_Time: tsOffsetIs: Apps: 154364403227; DSPS: 5150163; Offset : -2811466110
,07-01 12:08:25.566  6689  6767 I jxcore-log: JXcore Cordova bridge is ready!
07-01 12:08:25.566  6689  6767 I jxcore-log: 
,07-01 12:08:25.567  6689  6767 W jxcore-log: JXcore engine is started
07-01 12:08:25.577  6689  6757 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-01 12:08:25.579  6689  6689 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
07-01 12:08:25.611   968  1059 I PowerManagerService: ALS enabled for SRE
07-01 12:08:25.611   968  1059 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (34616 ms ago)
,07-01 12:08:25.618   968  1059 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-01 12:08:25.634   968  1059 I PowerManagerService: ALS enabled for SRE
07-01 12:08:25.636   968  1059 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (34641 ms ago)
07-01 12:08:25.642   968  1059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,07-01 12:08:25.650   968  1059 I PowerManagerService: Sleeping (uid 1000)...
07-01 12:08:25.650   968  1059 D LPWGController: [updateScreenState] screen on = false
07-01 12:08:25.650   968  1059 D LPWGController: disable proximity sensor
07-01 12:08:25.651   968  1059 D LPWGController: enable proximity sensor
07-01 12:08:25.666   968  1059 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3b127af1] by com.android.server.power.ProximitySensorListener.enable():120
,07-01 12:08:25.673   968  1059 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
07-01 12:08:25.673   968  1059 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
07-01 12:08:25.673   968  1059 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
07-01 12:08:25.673   968  1059 I sensors_hal_Ctx: activate: handle is 48, enable
07-01 12:08:25.674   968  1059 V sensors_hal_Ctx: activate sensors is 1400000000000
07-01 12:08:25.674   968  1059 D sensors_hal_Thresh: enable: handle=48
07-01 12:08:25.674   968  1059 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
07-01 12:08:25.674   968  1059 D sensors_hal_Util: waitForResponse: timeout=1000
07-01 12:08:25.680   968  1000 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
07-01 12:08:25.680   968  1000 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
07-01 12:08:25.680   968  1059 D sensors_hal_Thresh: enable: Received response: 0
07-01 12:08:25.681   968  1059 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (34685 ms ago)
,07-01 12:08:25.692   968  1059 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-01 12:08:25.692   968  1059 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-01 12:08:25.692   968  1059 I Adreno-EGL: Build Date: 03/02/15 Mon
07-01 12:08:25.692   968  1059 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-01 12:08:25.692   968  1059 I Adreno-EGL: Remote Branch: 
07-01 12:08:25.692   968  1059 I Adreno-EGL: Local Patches: 
07-01 12:08:25.692   968  1059 I Adreno-EGL: Reconstruct Branch: 
,07-01 12:08:25.745   248   269 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1399 us)
,07-01 12:08:25.908   425   952 I Sensors : sns_pwr.c(273):acquiring wakelock
,07-01 12:08:25.910   968  1000 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
07-01 12:08:25.911   968  1000 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
07-01 12:08:25.911   968  1000 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
07-01 12:08:25.912   968  1000 D sensors_hal_Thresh: processInd: handle 48, count=1
07-01 12:08:25.912   968  1000 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
07-01 12:08:25.912   968  1000 I sensors_hal_Thresh: processInd : proximity state changed - FAR
07-01 12:08:25.912   968  1039 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
07-01 12:08:25.913   968  1039 D sensors_hal_Ctx: poll: count: 256
07-01 12:08:25.913   968  1039 I sensors_hal_Ctx: poll: released wakelock sensor_ind
07-01 12:08:25.913   968  1039 D sensors_hal_Util: waitForResponse: timeout=0
07-01 12:08:25.916   968  1059 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
07-01 12:08:25.916   968  1059 I LPWGController: current mode = 1  value = 1 1
07-01 12:08:25.920   968  1059 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
07-01 12:08:26.014   968  1059 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,07-01 12:08:26.261  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-01 12:08:26.261  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-01 12:08:26.262  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,07-01 12:08:26.265   968  1345 D qdlights: set_light_backlight: 0
07-01 12:08:26.296   968  1059 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,07-01 12:08:26.299   968  1059 I sensors_hal_Ctx: activate: handle is 46, disable
07-01 12:08:26.299   968  1059 V sensors_hal_Ctx: activate sensors is 1000000000000
07-01 12:08:26.299   968  1059 D sensors_hal_LP2: enable: handle=46
07-01 12:08:26.299   968  1059 D sensors_hal_LP2: enable: Disabling sensor handle=46
07-01 12:08:26.299   968  1059 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
07-01 12:08:26.306   248   248 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
07-01 12:08:26.306   248   248 D qdhwcomposer: hwc_blank: Blanking display: 0
07-01 12:08:26.310   968  1057 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
07-01 12:08:26.311   968   968 V ActivityManager: Display changed displayId=0
,07-01 12:08:26.356   968  1028 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
07-01 12:08:26.356   968  1028 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,07-01 12:08:26.387  1747  1747 D DSDPConnection: Display #0 changed.
07-01 12:08:26.475   968  1876 I ActivityManager: Process com.google.android.apps.docs (pid 6399) has died
,07-01 12:08:26.509   248   248 D qdhwcomposer: hwc_blank: Done blanking display: 0
07-01 12:08:26.510   968  1345 D SurfaceControl: Excessive delay in setPowerMode(): 203ms
,07-01 12:08:26.511   248   684 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
07-01 12:08:26.513   968  1345 I QCOM PowerHAL: Got set_interactive hint
07-01 12:08:26.538  1370  2477 D KeyguardViewMediator: onScreenTurnedOff(3)
,07-01 12:08:26.546  6689  6689 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-01 12:08:26.555  6689  6689 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-01 12:08:26.557  1327  1343 D SmartCoverViewMediator: onScreenTurnedOff(3)
07-01 12:08:26.564  1327  1343 D SmartCoverViewMediator: notifyScreenOffLocked
07-01 12:08:26.565  1327  1327 D SmartCoverViewMediator: handleNotifyScreenOFF
07-01 12:08:26.574  1370  2477 D KeyguardViewMediator: notifyScreenOffLocked
,07-01 12:08:26.591  6689  6689 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1a7feffe Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2182cb5d, 16908290=android.view.AbsSavedState$1@2182cb5d}, android:focusedViewId=100}]}]
07-01 12:08:26.591  6689  6689 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-01 12:08:26.591  6689  6689 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-01 12:08:26.591  6689  6689 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-01 12:08:26.598  1370  2477 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
07-01 12:08:26.599  1370  1370 D KeyguardViewMediator: handleNotifyScreenOff
,07-01 12:08:26.612  1370  1370 D ScreenTurnOffBySensor: unregisterProximitySensor
07-01 12:08:26.648  1370  1370 D StatusBarWindowView: onScreenTurnedOff why = 3
07-01 12:08:26.648   968   968 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
,07-01 12:08:26.666   288  2061 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 968
07-01 12:08:26.667   288  2061 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-01 12:08:26.667   288  2061 V voice   : voice_set_parameters: enter: screen_state=on
,07-01 12:08:26.669   288  2061 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
07-01 12:08:26.669   288  2061 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-01 12:08:26.669   288  2061 V voice   : voice_set_parameters: exit with code(0)
07-01 12:08:26.669   288  2061 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
07-01 12:08:26.669   288  2061 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-01 12:08:26.669   288  2061 V msm8974_platform: platform_set_parameters: exit with code(0)
07-01 12:08:26.670   288  2061 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-01 12:08:26.670   288  2061 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
07-01 12:08:26.670   288  2061 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
07-01 12:08:26.670   288  2061 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-01 12:08:26.674  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:08:26.675  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
07-01 12:08:26.677   968  1306 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
07-01 12:08:26.678   968  1034 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
07-01 12:08:26.684  1835  1835 I QCNEJ   : |CORE| sendScreenState: state:true
,07-01 12:08:26.691  1799  1957 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
07-01 12:08:26.693  1799  1957 D LEDService: stopPatternFlashing()
07-01 12:08:26.694  1799  1799 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
07-01 12:08:26.694  1799  1957 D qdlights: set_light_notifications: 0,0,0,0,3
07-01 12:08:26.696  1799  1957 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-01 12:08:26.696  1799  1957 D qdlights: set_light_notifications: 0,0,0,0,3
07-01 12:08:26.696  1799  1799 D Cliptray Service: lockStatus = 0
07-01 12:08:26.697  1799  1957 I LEDService: updateLightsLocked : turn off led
07-01 12:08:26.698  1799  1957 D qdlights: set_light_notifications: 0,0,0,0,3
,07-01 12:08:26.701  1799  1957 D LEDHandler: RESTART MSG
07-01 12:08:26.727   968  2163 D SplitWindow: check instance of lgWin Window{50b1044 u0 SearchPanel}
,07-01 12:08:26.733  1782  1782 D LNfcService: action : android.intent.action.SCREEN_ON
,07-01 12:08:26.739  1782  6778 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
07-01 12:08:26.739  1782  6778 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
07-01 12:08:26.739  1782  6778 D LNfcService: isRequireNfcCRouting() return true
07-01 12:08:26.739  1782  6778 D LNfcService: isHCERoutingtoHost() return : true
07-01 12:08:26.739  1782  6778 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
07-01 12:08:26.739  1782  6778 D NfcService: mEnableLPD: true
07-01 12:08:26.739  1782  6778 D NfcService: mEnableReader: false
07-01 12:08:26.739  1782  6778 D NfcService: mEnableHostRouting: true
07-01 12:08:26.739  1782  6778 D NfcService: newParams.techmask= mTechMask: default
07-01 12:08:26.739  1782  6778 D NfcService: mEnableLPD: true
07-01 12:08:26.739  1782  6778 D NfcService: mEnableReader: false
07-01 12:08:26.739  1782  6778 D NfcService: mEnableHostRouting: true
07-01 12:08:26.739  1782  6778 D NfcService: screenState= 3
07-01 12:08:26.739  1782  6778 D NfcService: Discovery configuration equal, not updating.
07-01 12:08:26.750   968  1842 D InputDispatcher: Window went away: Window{1be755d3 u0 SearchPanel}
,07-01 12:08:26.755  1370  1370 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
,07-01 12:08:26.766   968   968 D Ulp_jni : JNI:system_update. Event-0
,07-01 12:08:26.774  1370  1370 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,07-01 12:08:26.805  1747  1747 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,07-01 12:08:26.834   968   968 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:26.834   968   968 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:26.835   968   968 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
,07-01 12:08:26.839  2925  2925 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:8:26
07-01 12:08:26.841  2925  2925 D WeatherService: 2 : ACTION screen on
07-01 12:08:26.843  2925  2925 D WeatherService: 2 : shouldTimeTickRegistered : false
07-01 12:08:26.847  2925  2925 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-01 12:08:26.847  2925  2925 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:8:26
07-01 12:08:26.860  4264  4264 D AppCleanupService: android.intent.action.SCREEN_ON
,07-01 12:08:27.025   968  1842 I ActivityManager: Process com.google.android.apps.plus (pid 6298) has died
,07-01 12:08:27.033   968  1284 V AlarmManager: RTC_WAKEUP set : Alarm{2036aa62 type 0 when 1467367706980 com.google.android.googlequicksearchbox} when 1467367706980
07-01 12:08:27.085   968  1941 I ActivityManager: Process com.lge.lockscreensettings (pid 6274) has died
,07-01 12:08:27.092   288  2050 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 968
07-01 12:08:27.095   288  2050 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
07-01 12:08:27.095   288  2050 V voice   : voice_set_parameters: enter: screen_state=off
07-01 12:08:27.095   288  2050 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
07-01 12:08:27.095   288  2050 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-01 12:08:27.095   288  2050 V voice   : voice_set_parameters: exit with code(0)
07-01 12:08:27.096   288  2050 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
07-01 12:08:27.096   288  2050 V msm8974_platform: platform_set_parameters: enter: screen_state=off
07-01 12:08:27.096   288  2050 V msm8974_platform: platform_set_parameters: exit with code(0)
07-01 12:08:27.096   288  2050 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-01 12:08:27.096   288  2050 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
07-01 12:08:27.096   288  2050 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-01 12:08:27.097   968  1311 D WifiController: CMD_SCREEN_OFF 
07-01 12:08:27.098   968  1311 D WifiController: shouldWifiStayAwake TRUE
,07-01 12:08:27.103  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
07-01 12:08:27.104   968  1034 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
07-01 12:08:27.111  1835  1835 I QCNEJ   : |CORE| sendScreenState: state:false
,07-01 12:08:27.113  1799  1957 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
07-01 12:08:27.113  1799  1957 D LEDService: stopPatternFlashing()
07-01 12:08:27.113  1799  1957 D qdlights: set_light_notifications: 0,0,0,0,3
07-01 12:08:27.115  1799  1799 D VolumeVibrator: clear
07-01 12:08:27.117  1799  1799 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
07-01 12:08:27.118  1799  1957 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-01 12:08:27.118  1799  1957 D qdlights: set_light_notifications: 0,0,0,0,3
07-01 12:08:27.121  1782  1782 D LNfcService: action : android.intent.action.SCREEN_OFF
07-01 12:08:27.122  1799  1957 I LEDService: updateLightsLocked : turn on led
07-01 12:08:27.123  1799  1957 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
07-01 12:08:27.124  1799  1957 E LEDService: Can't handle this request of patternId:0
07-01 12:08:27.124  1799  1957 D LEDHandler: RESTART MSG
,07-01 12:08:27.127  1782  2224 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
07-01 12:08:27.142  1873  1873 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,07-01 12:08:27.156  1747  1747 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,07-01 12:08:27.162   968   968 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:27.162   968   968 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:27.162   968   968 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
07-01 12:08:27.164  2925  2925 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:8:27
07-01 12:08:27.164  2925  2925 D WeatherService: 2 : ACTION screen off
07-01 12:08:27.165  2925  2925 D WeatherService: 2 : TimeTick Receiver Unregister
07-01 12:08:27.166  2925  2925 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:8:27
07-01 12:08:27.169  4264  4264 D AppCleanupService: android.intent.action.SCREEN_OFF
,07-01 12:08:27.172  4264  6787 D AppCleanupService: AppUsageStatsSaveTask
07-01 12:08:27.211  1782  2682 E NxpNfcJni: getReconnectState = 0x0
,07-01 12:08:27.214  1782  2224 D LCardEmulationManager: getHceAppCount hostAppNum : 0
07-01 12:08:27.214  1782  2224 D LCardEmulationManager: getDefaultRoute
07-01 12:08:27.214  1782  2224 D LNfcService: isRequireNfcCRouting() return true
07-01 12:08:27.215  1782  2224 D LNfcService: isHCERoutingtoHost() return : true
07-01 12:08:27.215  1782  2224 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
07-01 12:08:27.215  1782  2224 D NfcService: mEnableLPD: true
07-01 12:08:27.215  1782  2224 D NfcService: mEnableReader: false
07-01 12:08:27.215  1782  2224 D NfcService: mEnableHostRouting: true
07-01 12:08:27.215  1782  2224 D NfcService: newParams.techmask= mTechMask: 0
07-01 12:08:27.215  1782  2224 D NfcService: mEnableLPD: true
07-01 12:08:27.215  1782  2224 D NfcService: mEnableReader: false
07-01 12:08:27.215  1782  2224 D NfcService: mEnableHostRouting: true
07-01 12:08:27.215  1782  2224 D NfcService: screenState= 1
07-01 12:08:27.259  1782  2682 E NxpNfcJni: getReconnectState = 0x0
,07-01 12:08:27.408   425   442 I Sensors : sns_pwr.c(301):releasing wakelock
,07-01 12:08:29.350   298   349 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-01 12:08:29.475   968   985 I ActivityManager: Process com.lge.eula (pid 6378) has died
,07-01 12:08:31.583   968  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{8fc97f3 type 2 when 160581 com.android.systemui} when 160581
,07-01 12:08:31.589  1370  1370 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,07-01 12:08:31.597  1747  2372 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
07-01 12:08:31.602  1747  2372 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-01 12:08:31.602  1747  2372 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-01 12:08:31.604  1747  2372 V TelecomServiceImpl: getCallState : 0
07-01 12:08:31.605  1747  1763 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
07-01 12:08:31.605  1747  1763 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-01 12:08:31.605  1747  1763 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-01 12:08:31.606  1370  1370 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
07-01 12:08:31.607  1370  1370 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,07-01 12:08:34.355   298   349 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-01 12:08:39.360   298   349 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-01 12:08:41.894  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-01 12:08:41.894  6689  6767 I jxcore-log: 
,07-01 12:08:41.898  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-01 12:08:41.898  6689  6767 I jxcore-log: 
07-01 12:08:41.905  1997  2030 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
07-01 12:08:41.905  6689  6767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 12:08:41.905  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:41.905  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:08:41.905  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:08:41.905  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:08:41.905  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 12:08:41.905  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 12:08:41.905  6689  6767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-01 12:08:41.906  1997  2030 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
07-01 12:08:41.909  6689  6767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-01 12:08:41.912  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-01 12:08:41.912  6689  6767 I jxcore-log: 
07-01 12:08:41.914  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-01 12:08:41.914  6689  6767 I jxcore-log: 
07-01 12:08:42.444  6689  6767 I jxcore-log: Unit Test app is loaded
07-01 12:08:42.444  6689  6767 I jxcore-log: 
,07-01 12:08:42.460  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-01 12:08:42.460  6689  6767 I jxcore-log: 
07-01 12:08:42.468  6689  6689 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-01 12:08:42.473  6689  6767 I jxcore-log: My device name is: LGE-LG-D722
07-01 12:08:42.473  6689  6767 I jxcore-log: 
07-01 12:08:42.631  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 12:08:42.632  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37055f64 added. We now have 2 listener(s)
07-01 12:08:42.632  6689  6757 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 12:08:42.634  1997  3780 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
07-01 12:08:42.636  1997  3780 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
,07-01 12:08:42.639  6689  6757 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:08:42.639  6689  6757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 12:08:42.639  6689  6757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:08:42.639  6689  6757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:08:42.639  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37055f64 removed from the list
07-01 12:08:42.641  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 12:08:42.641  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3bb245cd added. We now have 2 listener(s)
07-01 12:08:42.641  6689  6757 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 12:08:42.642  6689  6757 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:08:42.642  6689  6757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 12:08:42.642  6689  6757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:08:42.642  6689  6757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:08:42.642  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3bb245cd removed from the list
07-01 12:08:42.645  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 12:08:42.645  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5ba5e82 added. We now have 2 listener(s)
07-01 12:08:42.646  6689  6757 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 12:08:42.649   968  1344 D WifiServiceImplEx: setWifiEnabled: false pid=6689, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
07-01 12:08:42.649   968  1344 D WifiService: setWifiEnabled: false pid=6689, uid=10030
,07-01 12:08:42.671   968  1306 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-01 12:08:42.672   968  1834 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 12:08:42.675   968   968 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 12:08:42.681   968  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-01 12:08:42.682   968  1834 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2caecb0 mBinding = false
07-01 12:08:42.683   968   968 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 12:08:42.683   968   968 D Ulp_jni : JNI:system_update. Event-4
,07-01 12:08:42.701   968  1056 D BluetoothManagerService: Message: 2
07-01 12:08:42.701  1997  2030 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
07-01 12:08:42.702   968  1056 D BluetoothManagerService: Sending off request.
07-01 12:08:42.702  6689  6757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-01 12:08:42.704  1997  3780 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
07-01 12:08:42.705   968  1305 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:42.705   968  1305 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:42.706   968   968 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 12:08:42.706   968   968 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 12:08:42.706   968   968 D Ulp_jni : JNI:system_update. Event-4
07-01 12:08:42.707  6689  6757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 12:08:42.707  6689  6757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:42.707  6689  6757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:08:42.707  6689  6757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:08:42.707  6689  6757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:08:42.707  6689  6757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 12:08:42.707  6689  6757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 12:08:42.707  6689  6757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 12:08:42.710  1997  2028 D BluetoothAdapterService(802996774): disable() called...
07-01 12:08:42.711  1997  2030 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
,07-01 12:08:42.715  6689  6757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-01 12:08:42.716  1997  2028 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
07-01 12:08:42.718  6689  6757 D io.jxcore.node.ConnectivityMonitor: start: OK
07-01 12:08:42.719   968  2968 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:42.719  1997  2030 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
07-01 12:08:42.720  1997  2200 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-01 12:08:42.720  1997  2200 D BluetoothAdapterProperties: Setting state to 13
07-01 12:08:42.720  1997  2200 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-01 12:08:42.720  1997  2200 D BluetoothAdapterService(802996774): updateAdapterState() - Broadcasting state to 1 receivers.
07-01 12:08:42.723  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:08:42.723  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:42.723  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:08:42.723  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:08:42.723  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:08:42.723  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 12:08:42.723  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 12:08:42.723  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 12:08:42.723   282  1048 D CommandListener: Clearing all IP addresses on wlan0
,07-01 12:08:42.727   282  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 7
07-01 12:08:42.736  6689  6689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-01 12:08:42.738  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:08:42.746  1997  2200 D BluetoothAdapterProperties: onBluetoothDisable()
07-01 12:08:42.763   282  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 10
07-01 12:08:42.764   282  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 7
,07-01 12:08:42.770  1997  2028 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
07-01 12:08:42.771   968  1056 D BluetoothManagerService: Message: 60
07-01 12:08:42.771   968  1056 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-01 12:08:42.771   968  1056 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
07-01 12:08:42.774  1997  2200 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-01 12:08:42.776  1799  1799 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:42.776   968  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-01 12:08:42.776   968  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-01 12:08:42.777  1997  3780 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
,07-01 12:08:42.780  1997  3780 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
07-01 12:08:42.780  1997  2208 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
07-01 12:08:42.781  1997  1997 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:42.782  1997  1997 D BluetoothMapService: STATE_TURNING_OFF
07-01 12:08:42.784  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
07-01 12:08:42.784  1370  1370 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
07-01 12:08:42.795   968  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-01 12:08:42.796   968  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
07-01 12:08:42.801  1997  1997 V BluetoothMapService: Handler(): got msg=4
07-01 12:08:42.802  1997  1997 D BluetoothMapService: MAP Service closeService in
07-01 12:08:42.802  1997  1997 D BluetoothMapMasInstance: MAP Service shutdown
07-01 12:08:42.803  2397  4501 V NativeCrypto: Read error: ssl=0xaaf58400: I/O error during system call, Connection timed out
,07-01 12:08:42.811  1997  3775 I bt-btif : BTA_JvDeleteRecord
07-01 12:08:42.815   968  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-01 12:08:42.815   968  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-01 12:08:42.815   968  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-01 12:08:42.815   968  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-01 12:08:42.820  2397  4501 V NativeCrypto: SSL shutdown failed: ssl=0xaaf58400: I/O error during system call, Broken pipe
,07-01 12:08:42.833   968  1035 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6805 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,07-01 12:08:42.836  1997  2208 D BluetoothAdapterProperties: Scan Mode:20
07-01 12:08:42.836  1997  2200 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-01 12:08:42.836  1997  2200 I bt-btif : BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
07-01 12:08:42.836  1997  2200 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
07-01 12:08:42.836  1997  2200 D bt-btif : btsock_ctrl_hci_cleanup(L202): poll handle:4
07-01 12:08:42.841  1997  3782 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-01 12:08:42.841  1997  3782 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-01 12:08:42.841  1997  3782 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-01 12:08:42.841  1997  3782 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-01 12:08:42.841  1997  3782 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-01 12:08:42.841  1997  3782 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-01 12:08:42.841  1997  3782 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-01 12:08:42.841  1997  3782 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
07-01 12:08:42.842  1997  1997 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-01 12:08:42.842  1997  1997 V BluetoothMapService: MAP Service closeService out
07-01 12:08:42.846  2397  4501 E GCM     : Wifi connection closed with errorCode 20
,07-01 12:08:42.848   968   968 D WifiHS20: hidePasspointNotification off =false
07-01 12:08:42.848   968   968 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:42.848   968   968 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:42.848   968   968 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-01 12:08:42.850   968   968 D WifiHS20: hidePasspointNotification off =false
07-01 12:08:42.850   968   968 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:42.850   968   968 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:42.851   968   968 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-01 12:08:42.851   968   968 D WifiScanningService: SCAN_AVAILABLE : 1
07-01 12:08:42.851   968   968 D RttService: SCAN_AVAILABLE : 1
07-01 12:08:42.851   968  1326 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:42.851   968  1325 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:42.863   968  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-01 12:08:42.863   968  1305 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:42.864   968  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:42.876   968  1305 D LGWifiP2pService: P2pDisablingState
07-01 12:08:42.876   968  1305 D LGWifiP2pService: P2pDisablingState{ when=-10ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:42.876   968  1305 D LGWifiP2pService: p2p socket connection lost
07-01 12:08:42.876   968  1305 D LGWifiP2pService: P2pDisabledState
,07-01 12:08:42.884   968  1305 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:42.884   968  1305 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:42.900  1997  3775 I bt-btif : BTA_JvRfcommStopServer
07-01 12:08:42.900  1997  2200 I bt-btif : BTA_JvDeleteRecord
07-01 12:08:42.900  1997  2200 I bt-btif : BTA_JvRfcommStopServer
,07-01 12:08:42.901  1997  2200 D IOP_DB_BT: db_close: nbr users 0
07-01 12:08:42.902  1997  2200 D IOP_DB_BT: db_close: free database
07-01 12:08:42.902  1835  1835 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,07-01 12:08:42.904  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:08:42.904  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:42.904  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:08:42.904  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:08:42.904  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:08:42.904  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:08:42.904  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:08:42.904  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 12:08:42.906  1799  1799 D WfdsService: WifiP2pState is changed : false
07-01 12:08:42.907  6689  6689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:08:42.909  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:08:42.909  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:42.909  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:08:42.909  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:08:42.909  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:08:42.909  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:08:42.909  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:08:42.909  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 12:08:42.909  6689  6689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:08:42.911   968  1842 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
07-01 12:08:42.913  1835  1835 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-01 12:08:42.903 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-01 12:08:42.914  1835  1835 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
07-01 12:08:42.914  1835  1835 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-01 12:08:42.914  1835  1835 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-01 12:08:42.914 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-01 12:08:42.914  1835  1835 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
07-01 12:08:42.915  1799  2114 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
,07-01 12:08:42.917  1799  2114 D WfdsJNI : doCommand: P2P_STOP_FIND
07-01 12:08:42.923  1799  2114 D WfdsService: Set the WFDS Monitor: false
07-01 12:08:42.925  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 12:08:42.925  1997  2200 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-01 12:08:42.925  1997  2200 D btif_config_util: enum_config(L300): in, key:Adapter, value:BluezMigrationDone
07-01 12:08:42.925  1997  2200 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
07-01 12:08:42.925  1997  2200 D btif_config_util: enum_config(L343): out, key:Adapter, value:BluezMigrationDone
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L300): in, key:Adapter, value:Address
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L343): out, key:Adapter, value:Address
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L344): out, value:f8:95:c7:87:85:54
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L300): in, key:Adapter, value:Name
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L343): out, key:Adapter, value:Name
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L344): out, value:G3s-1
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L344): out, value:��8�\�婓��n�ScanMode
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L300): in, key:Adapter, value:ScanMode
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L343): out, key:Adapter, value:ScanMode
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L344): out, value:x
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L344): out, value:s!WE�(E��00:0F:F6
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
07-01 12:08:42.926  1997  2200 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L344): out, value:BMW,Audi,Parrot,Car
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L344): out, value:00:0F:F6
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L344): out, value:�
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L344): out, value:HTC Desire 820
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
07-01 12:08:42.927  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L344): out, value:$
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L344): out, value:Galaxy S6-1
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.928  1997  2200 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L344): out, value:�
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L344): out, value:A5-1
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
07-01 12:08:42.929  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L344): out, value:#
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L344): out, value:Nexus 6
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
07-01 12:08:42.930  1997  2200 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L344): out, value:�
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L344): out, value:XT1072
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
,07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L344): out, value:a
07-01 12:08:42.931  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L344): out, value:S5-1
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Service
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Service, value type:string
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Service
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Manufacturer
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Manufacturer, value type:int
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Manufacturer
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpVer
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpVer, value type:int
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpVer
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpSubVer
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpSubVer, value type:int
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpSubVer
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L344): out, value:	a
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Name
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Name, value type:string
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Name
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L344): out, value:G4-1
07-01 12:08:42.932  1997  3783 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevClass
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevClass, value type:int
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevClass
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevType
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevType, value type:int
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevType
07-01 12:08:42.932  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:JustWorks
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:JustWorks, value type:int
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:JustWorks
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:GlobalTrust
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:GlobalTrust, value type:int
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:GlobalTrust
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Service
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Service, value type:string
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Service
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Manufacturer
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Manufacturer, value type:int
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Manufacturer
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpVer
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpVer, value type:int
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpVer
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpSubVer
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpSubVer, value type:int
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpSubVer
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L344): out, value:a
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Name
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Name, value type:string
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Name
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L344): out, value:Thali Test (Galaxy S5)
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevClass
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevClass, value type:int
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevClass
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevType
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevType, value type:int
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevType
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:JustWorks
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:JustWorks, value type:int
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:JustWorks
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:GlobalTrust
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:GlobalTrust, value type:int
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:GlobalTrust
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Service
07-01 12:08:42.933  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Service, value type:string
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Service
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Manufacturer
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Manufacturer, value type:int
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Manufacturer
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpVer
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpVer, value type:int
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpVer
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpSubVer
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpSubVer, value type:int
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpSubVer
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L344): out, value:�
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Name
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Name, value type:string
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Name
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L344): out, value:Thali Test (Galaxy A5)
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevClass
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevClass, value type:int
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevClass
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevType
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevType, value type:int
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevType
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:JustWorks
07-01 12:08:42.934  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:JustWorks, value type:int
07-01 12:08:42.935  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:JustWorks
07-01 12:08:42.935  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.935  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:GlobalTrust
07-01 12:08:42.935  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:GlobalTrust, value type:int
07-01 12:08:42.935  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:GlobalTrust
07-01 12:08:42.935  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.935  1997  2200 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Service
07-01 12:08:42.935  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Service, value type:string
07-01 12:08:42.935  1997  2200 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Service
07-01 12:08:42.935  1997  2200 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
07-01 12:08:42.935  1997  2200 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
07-01 12:08:42.935  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
07-01 12:08:42.935  1997  2200 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
07-01 12:08:42.935  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.935  1997  2200 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
07-01 12:08:42.935  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L344): out, value:�
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L344): out, value:Thali Test (Galaxy A3)
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:JustWorks, value type:int
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:GlobalTrust
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
07-01 12:08:42.936  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Manufacturer
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Manufacturer, value type:int
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpVer, value type:int
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpSubVer, value type:int
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L344): out, value:A
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Name
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L344): out, value:Thali Test's G2
07-01 12:08:42.937  1997  2200 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
07-01 12:08:42.938  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevClass, value type:int
07-01 12:08:42.938  1997  2200 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
07-01 12:08:42.938  1799  2846 D CtrlSupplicant: Received on exit socket, terminate
07-01 12:08:42.938  1799  2846 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-01 12:08:42.938  1997  2200 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:42.938  1997  2200 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
07-01 12:08:42.938  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
07-01 12:08:42.938  1997  2200 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevType
07-01 12:08:42.938  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.938  1997  2200 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:JustWorks
07-01 12:08:42.938  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
07-01 12:08:42.938  1997  2200 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
07-01 12:08:42.938  1799  2846 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-01 12:08:42.938  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.938  1997  2200 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
07-01 12:08:42.938  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:GlobalTrust, value type:int
07-01 12:08:42.938  1997  2200 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
07-01 12:08:42.938  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.938  1997  2200 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Service
07-01 12:08:42.938  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
07-01 12:08:42.938  1799  2846 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Manufacturer
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Manufacturer, value type:int
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpVer
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpVer, value type:int
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpVer
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpSubVer
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpSubVer, value type:int
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpSubVer
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L344): out, value:	a
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Name
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Name, value type:string
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Name
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L344): out, value:Note3-1
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevClass
07-01 12:08:42.939  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevClass, value type:int
07-01 12:08:42.940  1997  2200 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevClass
07-01 12:08:42.940  1997  2200 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:42.940  1997  2200 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevType
07-01 12:08:42.940  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevType, value type:int
07-01 12:08:42.940  1997  2200 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevType
07-01 12:08:42.940  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.940  1997  2200 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:JustWorks
07-01 12:08:42.940  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:JustWorks, value type:int
07-01 12:08:42.940  1997  2200 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:JustWorks
07-01 12:08:42.940  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.940  1997  2200 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:GlobalTrust
07-01 12:08:42.940  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:GlobalTrust, value type:int
07-01 12:08:42.940  1997  2200 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:GlobalTrust
07-01 12:08:42.942  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.942  1997  2200 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Service
07-01 12:08:42.942  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Service, value type:string
07-01 12:08:42.942  1997  2200 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Service
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:Manufacturer
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Manufacturer, value type:int
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:Manufacturer
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpVer
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpVer, value type:int
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpVer
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpSubVer
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpSubVer, value type:int
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpSubVer
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L344): out, value:�
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:Name
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Name, value type:string
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:Name
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L344): out, value:A3-1
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevClass
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevClass, value type:int
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevClass
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevType
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevType, value type:int
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevType
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:JustWorks
07-01 12:08:42.943  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:JustWorks, value type:int
07-01 12:08:42.944  1997  2200 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:JustWorks
07-01 12:08:42.944  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.944  1997  2200 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:GlobalTrust
07-01 12:08:42.944  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:GlobalTrust, value type:int
07-01 12:08:42.944  1997  2200 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:GlobalTrust
07-01 12:08:42.944  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.945  1997  2200 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Service
07-01 12:08:42.955  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:GlobalTrust, value type:int
07-01 12:08:42.956  1997  2200 D btif_config_util: enum_config(L343): out, key:58:2a:f7:ed:96:be, value:GlobalTrust
07-01 12:08:42.962  1997  2200 D btif_config_util: enum_config(L300): in, key:00:00:00:00:41:9e, value:DevType
07-01 12:08:42.962   282  1048 D CommandListener: Clearing all IP addresses on wlan0
07-01 12:08:42.962  1997  2200 D btif_config_util: enum_config(L343): out, key:00:00:00:00:41:9e, value:DevType
07-01 12:08:42.962  1997  2200 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:42.962  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:Name, value type:string
07-01 12:08:42.962  1997  2200 D btif_config_util: enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:Name
07-01 12:08:42.962  1997  2200 D btif_config_util: enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevClass
07-01 12:08:42.962  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevClass, value type:int
07-01 12:08:42.963  1997  2200 D btif_config_util: enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevClass
07-01 12:08:42.963  1997  2200 D btif_config_util: enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevType, value type:int
07-01 12:08:42.963   968  1312 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
07-01 12:08:42.964   968  1312 D DSQN    : disableDataServiceNotify
07-01 12:08:42.965  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-01 12:08:42.966  1799  1815 D WifiServiceExtension: isInternetCheckAvailable return false
07-01 12:08:42.966   968  1312 D DSQN    : stop dsqn bin
07-01 12:08:42.967  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-01 12:08:42.967  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-01 12:08:42.969  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-01 12:08:42.973  1835  1835 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-01 12:08:42.973  1835  1835 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-01 12:08:42.973 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-01 12:08:42.974  1835  1835 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
07-01 12:08:42.975   968   968 D WifiHS20: hidePasspointNotification off =false
07-01 12:08:42.976   968   968 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:42.976   968   968 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:42.976   968   968 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-01 12:08:42.979  1835  1835 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:08:42.979  1835  1835 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-01 12:08:42.979 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-01 12:08:42.979  1835  1835 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
07-01 12:08:42.982  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:08:42.982  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:42.982  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:08:42.982  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:08:42.982  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:08:42.982  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:08:42.982  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:08:42.982  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 12:08:42.982  6689  6689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:08:42.983   968   968 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-01 12:08:42.986  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:08:42.986  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:42.986  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:08:42.986  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:08:42.986  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:08:42.986  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:08:42.986  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:08:42.986  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 12:08:42.986  6689  6689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:08:42.990  1799  2114 D WfdsService: STATE : WfdsDisabledState - enter
07-01 12:08:42.990  1799  2114 D WfdsService: WFDS: Scanner is paused
07-01 12:08:42.993   968   968 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-01 12:08:42.993   968   968 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
07-01 12:08:42.996  1799  2114 D WfdsDiscoveryStore: Clear Discovery Method Map: ScanAlwaysMode false
07-01 12:08:42.997  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-01 12:08:42.997  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
07-01 12:08:42.997  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 12:08:43.001  1799  2109 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-01 12:08:43.009   968  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-01 12:08:43.009   968  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:08:43.010   968  2968 D DhcpStateMachine: StoppedState
07-01 12:08:43.011   968  2968 D DhcpStateMachine: StoppedState{ when=-113ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:43.012  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-01 12:08:43.012  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-01 12:08:43.013  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-01 12:08:43.013  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-01 12:08:43.013   968  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:08:43.013  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-01 12:08:43.013  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
07-01 12:08:43.013  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
07-01 12:08:43.016  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 12:08:43.018  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-01 12:08:43.018  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-01 12:08:43.018  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-01 12:08:43.019  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-01 12:08:43.019  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-01 12:08:43.019  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
07-01 12:08:43.021  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-01 12:08:43.021  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-01 12:08:43.021  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
07-01 12:08:43.021  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
07-01 12:08:43.022   968  1312 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:08:43.023   968  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:08:43.023  1370  1739 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-01 12:08:43.023   968  1312 D ConnectivityService: sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:08:43.023   968  1312 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
07-01 12:08:43.024   968  2965 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:43.024   968  2965 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:43.024   968  2965 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-01 12:08:43.025  3391  3745 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,07-01 12:08:43.027   968  1312 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.103/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
07-01 12:08:43.028   968  1312 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-01 12:08:43.029   968  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-01 12:08:43.029   968  1312 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-01 12:08:43.030   968  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-01 12:08:43.030  1835  1835 W QCNEJ   : |CORE| No family connected
07-01 12:08:43.032   968  1056 D Tethering: MasterInitialState.processMessage what=3
07-01 12:08:43.032   968  1303 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-01 12:08:43.033   968  1312 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-01 12:08:43.034   968  1312 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:08:43.034   968  1312 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:08:43.034   968  1312 D NetworkManagementService: Removing idletimer
07-01 12:08:43.036   968  1306 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:08:43.036  1835  1835 W QCNEJ   : |CORE| No family connected
07-01 12:08:43.036   968  1306 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 12:08:43.036  1835  1835 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
07-01 12:08:43.037   968  1303 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-01 12:08:43.037  1835  1835 I QCNEJ   : |CORE| sendDefaultNwMsg: default = -1
07-01 12:08:43.037   968  1056 D Tethering: MasterInitialState.processMessage what=3
,07-01 12:08:43.038   968  1312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:43.040  1747  1747 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:08:43.041   968  1312 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-01 12:08:43.045  1747  1747 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,07-01 12:08:43.062  1370  1370 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-01 12:08:43.070  1370  1370 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
,07-01 12:08:43.074  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-01 12:08:43.075  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-01 12:08:43.075  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
07-01 12:08:43.079  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-01 12:08:43.079  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-01 12:08:43.080  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
07-01 12:08:43.096   282  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
07-01 12:08:43.097   282  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 5
,07-01 12:08:43.098  2684  2684 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-01 12:08:43.099  2684  2684 I wpa_supplicant: monitor socket send errors count : 1
07-01 12:08:43.099  2684  2684 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1799-2\x00 that cannot receive messages
07-01 12:08:43.099   282  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 10
07-01 12:08:43.100   282  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 7
07-01 12:08:43.100   968  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-01 12:08:43.100   968  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-01 12:08:43.101  1370  1370 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,07-01 12:08:43.102  1370  1370 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
07-01 12:08:43.104  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-01 12:08:43.104  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-01 12:08:43.104  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
07-01 12:08:43.107  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-01 12:08:43.107  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-01 12:08:43.107  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
07-01 12:08:43.116  2684  2684 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-01 12:08:43.117  2684  2684 W wpa_supplicant: USIM:  scard_deinit function
,07-01 12:08:43.135   282  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
07-01 12:08:43.135   282  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
07-01 12:08:43.136   968  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-01 12:08:43.136   968  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-01 12:08:43.316   282  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,07-01 12:08:43.327   282  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 5
07-01 12:08:43.329  2684  2684 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-01 12:08:43.331   968  1056 D Tethering: InitialState.processMessage what=4
07-01 12:08:43.337   968  1056 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-01 12:08:43.338   968  1306 D WifiOffDelayIfNotUsed: stopMonitoring
07-01 12:08:43.338  1799  1799 D WfdsService: Supplicant Connection state is changed : false
07-01 12:08:43.339  1799  2114 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-01 12:08:43.339  1799  2114 D WfdsService: Set the WFDS Monitor: false
,07-01 12:08:43.339  1799  2114 D WfdsMonitor: WFDS Monitor is stopped
07-01 12:08:43.341  1835  1835 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
07-01 12:08:43.342  1835  1835 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-01 12:08:43.342 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-01 12:08:43.342  1835  1835 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
07-01 12:08:43.345   968   968 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-01 12:08:43.345   968  1310 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-01 12:08:43.345   968  1310 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-01 12:08:43.347  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:08:43.347  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:43.347  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:08:43.347  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:08:43.347  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:08:43.347  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:08:43.347  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:08:43.347  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:08:43.347  2397  2739 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:43.349  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-01 12:08:43.349  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-01 12:08:43.349  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
07-01 12:08:43.349  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
07-01 12:08:43.352  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:08:43.352  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:43.352  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:08:43.352  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:08:43.352  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:08:43.352  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:08:43.352  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:08:43.352  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 12:08:43.366  6805  6805 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 12:08:43.369  6805  6805 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
07-01 12:08:43.369  6805  6805 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-01 12:08:43.371  6805  6805 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-01 12:08:43.371  6805  6805 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-01 12:08:43.503  6805  6805 I IndexDatabaseHelper: Using schema version: 115
07-01 12:08:43.506  6805  6805 I IndexDatabaseHelper: Index is fine
,07-01 12:08:43.562   968  1381 I ActivityManager: Process com.android.vending (pid 5747) has died
,07-01 12:08:43.571  1747  1747 I PhoneApp: onTrimMemory: 10
07-01 12:08:43.571  1747  1747 I PhoneApp: trim memory
07-01 12:08:43.580  1932  1932 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,07-01 12:08:43.690  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-01 12:08:43.695  1997  1997 V BluetoothPbapReceiver: PbapReceiver onReceive 
,07-01 12:08:43.695  1997  1997 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:43.696  1997  1997 V BluetoothPbapReceiver: ***********state = 13
07-01 12:08:43.702  1997  1997 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,07-01 12:08:43.703  1997  1997 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:43.703  1997  1997 V BluetoothPbapService: state: 13
07-01 12:08:43.703  1997  1997 V BluetoothPbapService: Pbap Service closeService in
07-01 12:08:43.706  1997  1997 V BluetoothPbapService: successfully stopped pbap service
07-01 12:08:43.706  1997  1997 V BluetoothPbapService: Pbap Service closeService out
07-01 12:08:43.706  1997  1997 V BluetoothPbapService: Pbap Service onDestroy
07-01 12:08:43.706  1997  1997 V BluetoothPbapService: Pbap Service closeService in
07-01 12:08:43.706  1997  1997 V BluetoothPbapService: Pbap Service closeService out
07-01 12:08:43.706  1997  1997 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-01 12:08:43.718  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-01 12:08:43.722   968  1897 D WifiServiceImplEx: setWifiEnabled: true pid=6689, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
07-01 12:08:43.723   968  1897 D WifiService: setWifiEnabled: true pid=6689, uid=10030
,07-01 12:08:43.733   968  1306 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-01 12:08:43.734   968   968 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 12:08:43.734   968   968 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 12:08:43.734   968   968 D Ulp_jni : JNI:system_update. Event-4
07-01 12:08:43.734   968  1306 E WifiHW  : Wifi MAC Address = a0:39:f7:70:12:80
07-01 12:08:43.735   968  1306 E WifiHW  : wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
07-01 12:08:43.735   968  1306 E WifiHW  : band=b
07-01 12:08:43.735   968  1306 E WifiHW  : ": cur_etheraddr=a0:39:f7:70:12:80
07-01 12:08:43.736   282  1048 D SoftapController: Softap fwReload - Ok
07-01 12:08:43.737   968  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-01 12:08:43.737   968  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-01 12:08:43.738   282  1048 D CommandListener: Setting iface cfg
07-01 12:08:43.738   282  1048 D CommandListener: Trying to bring down wlan0
07-01 12:08:43.738   282  1048 D CommandListener: Clearing all IP addresses on wlan0
07-01 12:08:43.741   968  1306 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
07-01 12:08:43.745   968   968 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-01 12:08:43.747  1835  1835 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
07-01 12:08:43.747  1835  1835 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-01 12:08:43.747 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-01 12:08:43.748  1835  1835 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,07-01 12:08:43.749  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:08:43.752  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:08:43.753  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-01 12:08:43.753  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-01 12:08:43.753  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
07-01 12:08:43.753  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
07-01 12:08:43.754   968  1306 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-01 12:08:43.777  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:08:43.779  6835  6835 I wpa_supplicant: Successfully initialized wpa_supplicant
07-01 12:08:43.787   968  1056 D BluetoothManagerService: Message: 20
07-01 12:08:43.788   968  1056 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27d1126b:true
,07-01 12:08:43.799  1997  2030 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
07-01 12:08:43.803   968  1056 D BluetoothManagerService: Message: 30
,07-01 12:08:43.807   968  1056 D BluetoothManagerService: Message: 30
07-01 12:08:43.810  6805  6805 D LocalBluetoothProfileManager: Adding local MAP profile
07-01 12:08:43.812  6805  6805 D BluetoothMap: Create BluetoothMap proxy object
07-01 12:08:43.813   968  1056 D BluetoothManagerService: Message: 30
07-01 12:08:43.817   968  1056 D BluetoothManagerService: Message: 30
,07-01 12:08:43.819  6805  6805 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-01 12:08:43.822  6805  6805 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
07-01 12:08:43.830  6835  6835 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-01 12:08:43.830  6835  6835 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
07-01 12:08:43.856  6805  6805 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,07-01 12:08:43.859  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
07-01 12:08:43.868  6805  6805 D DockEventReceiver: finishStartingService: stopping service
,07-01 12:08:43.886  6805  6805 D BluetoothInputDevice: Proxy object connected
,07-01 12:08:43.889  6805  6805 D HidProfile: Bluetooth service connected
07-01 12:08:43.891  1997  3780 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
07-01 12:08:43.891  6805  6805 D BluetoothPan: BluetoothPAN Proxy object connected
07-01 12:08:43.892  6805  6805 D PanProfile: Bluetooth service connected
07-01 12:08:43.894  1997  2030 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
07-01 12:08:43.894  6805  6805 D BluetoothMap: Proxy object connected
07-01 12:08:43.894  6805  6805 D MapProfile: Bluetooth service connected
07-01 12:08:43.895  6805  6805 D BluetoothMap: getConnectedDevices()
07-01 12:08:43.895  1997  2028 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
07-01 12:08:43.895  6805  6805 D BluetoothMap: Bluetooth is Not enabled
07-01 12:08:43.895  6805  6805 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-01 12:08:43.897  6805  6805 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-01 12:08:43.898  6805  6805 I NotificationManager: com.android.settings: cancel(17301632) by com.android.settings
07-01 12:08:43.899  6805  6805 I NotificationManager: com.android.settings: cancel(-1000001) by com.android.settings
,07-01 12:08:43.899  6805  6805 I NotificationManager: com.android.settings: cancel(-1000011) by com.android.settings
07-01 12:08:43.900  6805  6805 I NotificationManager: com.android.settings: cancel(-1000021) by com.android.settings
07-01 12:08:43.900  6805  6805 I NotificationManager: com.android.settings: cancel(-1000031) by com.android.settings
07-01 12:08:43.901  6805  6805 I NotificationManager: com.android.settings: cancel(-1000041) by com.android.settings
07-01 12:08:43.929   968  2143 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6841 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,07-01 12:08:43.952  1997  3702 W bt_userial: select_read return size <=0:0, exiting userial_read_thread
,07-01 12:08:43.953  1997  3697 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 12:08:43.953  1997  3697 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 12:08:43.953  1997  3697 W bt-btif : ag scb idx 1 not allocated
07-01 12:08:43.953  1997  3697 E bt-btif : BTA AG is already disabled, ignoring ...
07-01 12:08:43.954  1997  3697 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 12:08:43.954  1997  3697 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 12:08:43.954  1997  3697 W bt-btif : ag scb idx 1 not allocated
07-01 12:08:43.954  1997  3697 E bt-btif : BTA AG is already disabled, ignoring ...
07-01 12:08:43.954  1997  3697 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-01 12:08:43.954  1997  3697 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-01 12:08:43.954  1997  3699 D bt_hwcfg: hw_epilog_process
07-01 12:08:43.954  1997  2208 I bt_userial_vendor: device fd = 67 close
07-01 12:08:43.967  1997  2208 E bt_vendor: [BTUI] Proto is enabled. Set Proto disable!!
,07-01 12:08:43.999  6805  6805 D BluetoothPermissionRequest: onReceive
,07-01 12:08:44.001  6805  6805 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-01 12:08:44.001  6805  6805 I NotificationManager: com.android.settings: cancel(17301632) by com.android.settings
,07-01 12:08:44.002  6805  6805 I NotificationManager: com.android.settings: cancel(-1000001) by com.android.settings
07-01 12:08:44.003  6805  6805 I NotificationManager: com.android.settings: cancel(-1000011) by com.android.settings
07-01 12:08:44.004  6805  6805 I NotificationManager: com.android.settings: cancel(-1000021) by com.android.settings
07-01 12:08:44.004  6805  6805 I NotificationManager: com.android.settings: cancel(-1000031) by com.android.settings
07-01 12:08:44.004  6805  6805 I NotificationManager: com.android.settings: cancel(-1000041) by com.android.settings
07-01 12:08:44.020  1997  1997 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
07-01 12:08:44.020  1997  1997 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
07-01 12:08:44.020  1997  1997 I NotificationManager: com.android.bluetooth: cancel(-1) by com.android.bluetooth
07-01 12:08:44.021  1997  1997 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,07-01 12:08:44.021  1997  1997 I NotificationManager: com.android.bluetooth: cancel(-1) by com.android.bluetooth
07-01 12:08:44.028  1997  1997 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-01 12:08:44.030  1997  1997 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:44.073  1997  2208 I GKI_LINUX: GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
,07-01 12:08:44.086   968  1344 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6860 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,07-01 12:08:44.129  1997  3697 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-01 12:08:44.130  1997  2208 I GKI_LINUX: GKI_destroy_task(): task [BTU] terminated
,07-01 12:08:44.132  1997  2208 I bt-btif : HAL bt_hal_cbacks->adapter_state_changed_cb
07-01 12:08:44.132  1997  2200 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-01 12:08:44.135  1997  2200 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.135  1997  2200 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-01 12:08:44.135  1997  2200 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.135  1997  2200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-01 12:08:44.145  1997  2200 D BtSettings.ProfileConfig: Unable to read settings
07-01 12:08:44.145  1997  2200 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-01 12:08:44.145  1997  2200 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
07-01 12:08:44.145  1997  2200 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
07-01 12:08:44.145  1997  2200 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
07-01 12:08:44.145  1997  2200 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
07-01 12:08:44.145  1997  2200 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
07-01 12:08:44.145  1997  2200 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
07-01 12:08:44.145  1997  2200 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
07-01 12:08:44.145  1997  2200 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
07-01 12:08:44.145  1997  2200 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:44.145  1997  2200 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
07-01 12:08:44.145  1997  2200 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 12:08:44.145  1997  2200 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
07-01 12:08:44.145  1997  2200 D BluetoothAdapterService(802996774): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
07-01 12:08:44.147  1997  2200 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.147  1997  2200 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-01 12:08:44.147  1997  2200 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.147  1997  2200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-01 12:08:44.147  1997  2200 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
07-01 12:08:44.147  1997  2200 D BluetoothAdapterService(802996774): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
07-01 12:08:44.148  1997  2200 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.148  1997  2200 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-01 12:08:44.148  1997  2200 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.148  1997  2200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 12:08:44.149  1997  2200 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-01 12:08:44.149  1997  2200 D BluetoothAdapterService(802996774): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
07-01 12:08:44.150  1997  2200 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.150  1997  2200 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-01 12:08:44.150  1997  2200 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.150  1997  2200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-01 12:08:44.151  1997  2200 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-01 12:08:44.151  1997  2200 D BluetoothAdapterService(802996774): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
07-01 12:08:44.152  1997  2200 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.152  1997  2200 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-01 12:08:44.152  1997  2200 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.152  1997  2200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-01 12:08:44.152  1997  2200 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-01 12:08:44.152  1997  2200 D BluetoothAdapterService(802996774): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
07-01 12:08:44.153  1997  2200 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.153  1997  2200 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
07-01 12:08:44.153  1997  2200 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.153  1997  2200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-01 12:08:44.154  1997  2200 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
07-01 12:08:44.154  1997  2200 D BluetoothAdapterService(802996774): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
07-01 12:08:44.155  1997  2200 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.155  1997  2200 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
07-01 12:08:44.155  1997  2200 D Blueto,othAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.155  1997  2200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 12:08:44.157  1997  2200 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
07-01 12:08:44.157  1997  2200 D BluetoothAdapterService(802996774): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
07-01 12:08:44.158  1997  2200 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.158  1997  2200 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
07-01 12:08:44.158  1997  2200 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.158  1997  2200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 12:08:44.159  1997  2200 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-01 12:08:44.159  1997  2200 D BluetoothAdapterService(802996774): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
07-01 12:08:44.160  1997  2200 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.160  1997  2200 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
07-01 12:08:44.160  1997  2200 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.160  1997  2200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
,07-01 12:08:44.161  1997  2200 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.ftp.FTPService
07-01 12:08:44.161  1997  2200 D BluetoothAdapterService(802996774): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
07-01 12:08:44.162  1997  2200 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.162  1997  2200 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
07-01 12:08:44.162  1997  2200 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:44.162  1997  2200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.162  1997  2200 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.opp.OppService
07-01 12:08:44.162  1997  2200 D BluetoothAdapterService(802996774): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
07-01 12:08:44.163  1997  2200 D BluetoothAdapterState: Stopping profile services that were post enabled
,07-01 12:08:44.165  1997  1997 D HeadsetService: Received stop request...Stopping profile...
07-01 12:08:44.172  1997  1997 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-01 12:08:44.172  1997  3609 D HeadsetStateMachine: Exit Disconnected: -1
07-01 12:08:44.173  1997  1997 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-01 12:08:44.174  1997  1997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fdcc226
07-01 12:08:44.179   968   968 D BluetoothHeadset: Proxy object disconnected
07-01 12:08:44.179   968   968 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-01 12:08:44.181  1747  1747 D BluetoothHeadset: Proxy object disconnected
07-01 12:08:44.182  1997  1997 D A2dpService: Received stop request...Stopping profile...
07-01 12:08:44.183  1747  1747 D BluetoothHeadset: Proxy object disconnected
07-01 12:08:44.184  1997  3623 D A2dpStateMachine: Exit Disconnected: -1
07-01 12:08:44.185  1747  1747 D BluetoothHeadset: Proxy object disconnected
07-01 12:08:44.199  1997  1997 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-01 12:08:44.199  1997  1997 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-01 12:08:44.199  1997  1997 D LGBluetoothPowerControlManager: [BTUI] terminate
07-01 12:08:44.200   968  1056 D BluetoothManagerService: Message: 31
07-01 12:08:44.201  1997  1997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fdcc226
,07-01 12:08:44.203   968   968 D BluetoothA2dp: Proxy object disconnected
07-01 12:08:44.203   968   968 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-01 12:08:44.204  1997  1997 D HidService: Received stop request...Stopping profile...
07-01 12:08:44.204  1997  1997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fdcc226
07-01 12:08:44.205  6805  6805 D BluetoothInputDevice: Proxy object disconnected
07-01 12:08:44.205  6805  6805 D HidProfile: Bluetooth service disconnected
07-01 12:08:44.206  1997  1997 D HealthService: Received stop request...Stopping profile...
07-01 12:08:44.206  1997  1997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fdcc226
07-01 12:08:44.208  1997  1997 D PanService: Received stop request...Stopping profile...
07-01 12:08:44.209  1997  1997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fdcc226
07-01 12:08:44.209  1997  1997 D BtGatt.DebugUtils: handleDebugAction() action=null
07-01 12:08:44.210  1997  1997 D BtGatt.GattService: Received stop request...Stopping profile...
07-01 12:08:44.211  6805  6805 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-01 12:08:44.211  6805  6805 D PanProfile: Bluetooth service disconnected
07-01 12:08:44.213  1997  1997 D BtGatt.GattService: stop()
07-01 12:08:44.213  1997  1997 D BtGatt.AdvertiseManager: advertise clients cleared
07-01 12:08:44.214  1997  1997 D LGBluetoothGattAdapter: [BTUI] LGBluetoothGattAdapter cleanup
07-01 12:08:44.214  1997  1997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fdcc226
,07-01 12:08:44.216  1997  1997 D BluetoothMapService: Received stop request...Stopping profile...
07-01 12:08:44.216  1997  1997 D BluetoothMapService: stop()
07-01 12:08:44.219  1997  1997 D BluetoothMapEmailAppObserver: deinitObservers()
07-01 12:08:44.219  1997  1997 D BluetoothMapEmailAppObserver: removeReceiver()
07-01 12:08:44.220  1997  1997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fdcc226
07-01 12:08:44.221  6805  6805 D BluetoothMap: Proxy object disconnected
07-01 12:08:44.221  1997  1997 D SapService: Received stop request...Stopping profile...
07-01 12:08:44.221  6805  6805 D MapProfile: Bluetooth service disconnected
07-01 12:08:44.221  1997  1997 D SapService: Stopping Bluetooth SapService
07-01 12:08:44.221  1997  1997 D LGBluetoothSapAdapter: [BTUI] LGBluetoothSapAdapter cleanup
07-01 12:08:44.221  1997  1997 D LGBluetoothSapManager: [BTUI] terminateSapManager
07-01 12:08:44.223  1997  1997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fdcc226
07-01 12:08:44.224  1747  1747 D LgeBluetoothSimManager: [BTUI] SAP_DISABLE_EVT
07-01 12:08:44.224  1997  1997 D **BluetoothFTPService: Received stop request...Stopping profile...
07-01 12:08:44.224  1997  1997 D **BluetoothFTPService: Stopping Bluetooth FTP Service
07-01 12:08:44.224  1997  1997 V BluetoothFTPServiceJni: closeFtpServerNative
07-01 12:08:44.225  1997  1997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fdcc226
07-01 12:08:44.226  1997  1997 D **OppService: Received stop request...Stopping profile...
07-01 12:08:44.226  1997  1997 D OppService: Stopping Bluetooth OppService
07-01 12:08:44.226  1997  1997 D OppService: cleanup OPP Service
07-01 12:08:44.226  1997  1997 W BluetoothOPPServiceJni: Cleaning up Bluetooth Opp Interface...
07-01 12:08:44.226  1997  1997 W BluetoothOPPServiceJni: Cleaning up Bluetooth OPP callback object
07-01 12:08:44.227  1997  1997 D OppService: remove callbacks and handler
07-01 12:08:44.228  1997  1997 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-01 12:08:44.228  1997  1997 D OppService: cleanup done
07-01 12:08:44.228  1997  1997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fdcc226
,07-01 12:08:44.230  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - Message: 1
07-01 12:08:44.230  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:44.232  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
07-01 12:08:44.232  1997  1997 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:44.232  1997  1997 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:44.232  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:44.232  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:44.234  1997  1997 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
07-01 12:08:44.234  1997  1997 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.234  1997  1997 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.234  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.236  6841  6841 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-01 12:08:44.237  1997  1997 D HeadsetStateMachine: Unbinding service...
07-01 12:08:44.238  1997  1997 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-01 12:08:44.238  1997  1997 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-01 12:08:44.238  1997  1997 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-01 12:08:44.238  1997  1997 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-01 12:08:44.238  1997  1997 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-01 12:08:44.238  1997  1997 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-01 12:08:44.238  1997  1997 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-01 12:08:44.238  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - Message: 1
07-01 12:08:44.239  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:44.239  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
07-01 12:08:44.239  1997  1997 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:44.239  1997  1997 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:44.239  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:44.239  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:44.239  1997  1997 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
,07-01 12:08:44.239  1997  1997 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.239  1997  1997 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.239  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.239  1997  1997 I BluetoothA2dpServiceJni: cleanupNative
07-01 12:08:44.239  1997  1997 I GKI_LINUX: GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
07-01 12:08:44.239  1997  3773 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-01 12:08:44.240  1997  1997 I GKI_LINUX: GKI_destroy_task(): task [A2DP-MEDIA] terminated
07-01 12:08:44.241  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - Message: 1
07-01 12:08:44.241  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:44.241  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
07-01 12:08:44.241  1997  1997 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:44.241  1997  1997 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:44.241  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:44.241  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:44.241  1997  1997 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
07-01 12:08:44.241  1997  1997 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.241  1997  1997 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.241  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.242  6860  6860 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-01 12:08:44.244  1997  1997 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-01 12:08:44.244  1997  1997 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-01 12:08:44.244  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - Message: 1
07-01 12:08:44.244  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:44.244  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
07-01 12:08:44.244  1997  1997 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:44.244  1997  1997 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:44.244  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:44.244  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:44.244  1997  1997 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
07-01 12:08:44.244  1997  1997 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.244  1997  1997 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.244  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.244  1997  1997 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-01 12:08:44.245  1997  1997 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-01 12,:08:44.245  1997  1997 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-01 12:08:44.245  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - Message: 1
07-01 12:08:44.245  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:44.245  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
07-01 12:08:44.245  1997  1997 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:44.245  1997  1997 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:44.245  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:44.246  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:44.246  1997  1997 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
07-01 12:08:44.246  1997  1997 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.246  1997  1997 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.246  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.246  1997  1997 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-01 12:08:44.246  1997  1997 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-01 12:08:44.247  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - Message: 1
07-01 12:08:44.247  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:44.247  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
07-01 12:08:44.247  1997  1997 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:44.247  1997  1997 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:44.247  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:44.247  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:44.247  1997  1997 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
07-01 12:08:44.247  1997  1997 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.247  1997  1997 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.247  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.247  1997  1997 V BluetoothMapService: Handler(): got msg=4
,07-01 12:08:44.247  1997  1997 D BluetoothMapService: MAP Service closeService in
07-01 12:08:44.247  1997  1997 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-01 12:08:44.247  1997  1997 V BluetoothMapService: MAP Service closeService out
07-01 12:08:44.247  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - Message: 1
07-01 12:08:44.247  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:44.247  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
07-01 12:08:44.247  1997  1997 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:44.247  1997  1997 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:44.247  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:44.247  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:44.248  1997  1997 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
07-01 12:08:44.248  1997  1997 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.248  1997  1997 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.248  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.248  1997  1997 D BluetoothMapService: cleanup()
,07-01 12:08:44.248  1997  1997 D BluetoothMapService: MAP Service closeService in
07-01 12:08:44.248  1997  1997 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-01 12:08:44.248  1997  1997 V BluetoothMapService: MAP Service closeService out
07-01 12:08:44.248  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - Message: 1
07-01 12:08:44.248  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:44.248  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
07-01 12:08:44.248  1997  1997 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:44.248  1997  1997 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:44.248  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:44.248  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:44.248  1997  1997 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
07-01 12:08:44.248  1997  1997 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
,07-01 12:08:44.248  1997  1997 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.248  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.249  1997  1997 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
07-01 12:08:44.249  1997  1997 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
07-01 12:08:44.249  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - Message: 1
07-01 12:08:44.249  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:44.249  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
07-01 12:08:44.249  1997  1997 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:44.249  1997  1997 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:44.249  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:44.249  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
,07-01 12:08:44.249  1997  1997 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
07-01 12:08:44.249  1997  1997 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.249  1997  1997 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.249  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.249  1997  1997 D BluetoothFTPService: cleanup FTP Service
07-01 12:08:44.249  1997  1997 V BluetoothFTPServiceJni: closeFtpServerNative
07-01 12:08:44.249  1997  1997 V BluetoothFTPServiceJni: cleanupNative
07-01 12:08:44.249  1997  1997 W BluetoothFTPServiceJni: Cleaning up Bluetooth FTP Server Interface...
,07-01 12:08:44.249  1997  1997 W BluetoothFTPServiceJni: Cleaning up Bluetooth FTP callback object
,07-01 12:08:44.249  1997  1997 D BluetoothFTPService: BluetoothFtpBinder.cleanup()
07-01 12:08:44.250  1997  1997 D BluetoothFTPService: cleanup done
07-01 12:08:44.250  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - Message: 1
07-01 12:08:44.250  1997  1997 D BluetoothAdapterService(802996774): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,07-01 12:08:44.250  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
07-01 12:08:44.250  1997  1997 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:44.250  1997  1997 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:44.250  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:44.250  1997  1997 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:44.250  1997  1997 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
07-01 12:08:44.250  1997  1997 D BluetoothAdapterService(802996774): onProfileServiceStateChange() - All profile services stopped...
07-01 12:08:44.250  1997  1997 D OppService: cleanup OPP Service
07-01 12:08:44.250  1997  1997 D OppService: remove callbacks and handler
07-01 12:08:44.250  1997  1997 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-01 12:08:44.250  1997  1997 D OppService: cleanup done
07-01 12:08:44.250  1997  2200 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-01 12:08:44.250  1997  2200 D BluetoothAdapterProperties: Setting state to 10
07-01 12:08:44.250  1997  2200 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-01 12:08:44.250  1997  2200 D BluetoothAdapterService(802996774): updateAdapterState() - Broadcasting state to 1 receivers.
07-01 12:08:44.251   968  1056 D BluetoothManagerService: Message: 60
07-01 12:08:44.251   968  1056 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-01 12:08:44.251   968  1056 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
07-01 12:08:44.251  1997  2200 I BluetoothAdapterState: Entering OffState
07-01 12:08:44.253  1747  1762 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 12:08:44.253  6805  6824 D BluetoothPbap: onBluetoothStateChange: up=false
07-01 12:08:44.255  6841  6841 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-01 12:08:44.255  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 12:08:44.256  6805  6827 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-01 12:08:44.258   968  1056 D BluetoothA2dp: onBluetoothStateChange: up=false
07-01 12:08:44.305   968  2163 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6880 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,07-01 12:08:44.365   298   349 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-01 12:08:44.370  1747  1763 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 12:08:44.374  6805  6824 D BluetoothMap: onBluetoothStateChange: up=false
07-01 12:08:44.376  6805  6827 D BluetoothPan: onBluetoothStateChange on: false
07-01 12:08:44.376   968  1056 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 12:08:44.377  1747  2366 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 12:08:44.378  2397  2397 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-01 12:08:44.380  1997  3780 D BluetoothAdapterService(802996774): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37051ac
07-01 12:08:44.382   968  1056 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-01 12:08:44.382   968  1056 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,07-01 12:08:44.388   968  1056 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-01 12:08:44.388   968  1056 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-01 12:08:44.389   968  1056 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2caecb0 mBinding = false
07-01 12:08:44.390   968  1056 D BluetoothManagerService: Sending unbind request.
07-01 12:08:44.391  1997  1997 D BluetoothAdapterService(802996774): onUnbind() - calling cleanup
07-01 12:08:44.391  1997  1997 D BluetoothAdapterService(802996774): cleanup()
07-01 12:08:44.400  1997  1997 D BluetoothAdapterService(802996774): cleanup() - Cleaning up adapter native
07-01 12:08:44.400  1997  1997 I bt-btif : btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
07-01 12:08:44.400  1997  1997 I GKI_LINUX: GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
,07-01 12:08:44.402  1997  2208 I bt-btif : HAL bt_hal_cbacks->thread_evt_cb
07-01 12:08:44.402  1997  2208 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-01 12:08:44.402  2397  2397 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-01 12:08:44.403  1997  1997 I GKI_LINUX: GKI_destroy_task(): task [BTIF] terminated
07-01 12:08:44.403  1997  1997 I GKI_LINUX: GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
07-01 12:08:44.403  1997  1997 I GKI_LINUX: GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
07-01 12:08:44.403  1997  1997 I GKI_LINUX: GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
07-01 12:08:44.403  1997  1997 I GKI_LINUX: GKI_exit_task 2 done
07-01 12:08:44.403  1997  1997 I GKI_LINUX: GKI_exit_task 1 done
07-01 12:08:44.403  1997  1997 I GKI_LINUX: GKI_exit_task 0 done
07-01 12:08:44.403  1997  1997 I BluetoothServiceJni: cleanupNative: return from cleanup
07-01 12:08:44.404  1997  1997 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-01 12:08:44.404  1997  1997 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-01 12:08:44.404   968  1056 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
07-01 12:08:44.405  1997  1997 D BluetoothAdapterService(802996774): cleanup() - Bluetooth process exited normally.
07-01 12:08:44.405  1997  1997 D BluetoothAdapterService(802996774): cleanup() done
07-01 12:08:44.407  1799  1799 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:44.410  1370  1370 D BluetoothAdapter: 285173946: getState() :  mService = null. Returning STATE_OFF
07-01 12:08:44.410  1370  1370 D BluetoothAdapter: 285173946: getState() :  mService = null. Returning STATE_OFF
07-01 12:08:44.410  6805  6805 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-01 12:08:44.411  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
07-01 12:08:44.411  1370  1370 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,07-01 12:08:44.413  2397  2739 D BluetoothAdapter: 854557652: getState() :  mService = null. Returning STATE_OFF
07-01 12:08:44.415  2397  2739 D BluetoothAdapter: 854557652: getState() :  mService = null. Returning STATE_OFF
07-01 12:08:44.416  1799  1988 D LGBluetoothAPIService: Message: 2
07-01 12:08:44.416  1997  1997 I art     : System.exit called, status: 0
07-01 12:08:44.416  1997  1997 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-01 12:08:44.417  1799  1988 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@a14800d mBinding = false
,07-01 12:08:44.418  1799  1988 D LGBluetoothAPIService: Sending unbind request.
07-01 12:08:44.425  6805  6805 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-01 12:08:44.425  6805  6805 D LGBluetoothEventManager: [BTUI] clear device connection state
07-01 12:08:44.427  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-01 12:08:44.436  6805  6805 D DockEventReceiver: finishStartingService: stopping service
,07-01 12:08:44.498  6880  6880 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-01 12:08:44.530   288  1297 V AudioFlinger: 1997 died, releasing its sessions
,07-01 12:08:44.532   288  1297 V AudioFlinger:  pid 1747 @ 0
07-01 12:08:44.532   288  1297 V AudioFlinger:  pid 3199 @ 1
07-01 12:08:44.532   288  1297 V AudioFlinger:  pid 3199 @ 2
07-01 12:08:44.534  6805  6805 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
07-01 12:08:44.535  1799  1799 D FMFRW_FmProxy: Fm Proxy object disconnected
07-01 12:08:44.585   968  2143 I ActivityManager: Process com.android.bluetooth (pid 1997) has died
07-01 12:08:44.586   968  2143 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
07-01 12:08:44.586   968  2143 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService in 11000ms
,07-01 12:08:44.604  6805  6805 D BluetoothPermissionRequest: onReceive
,07-01 12:08:44.608  6805  6805 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-01 12:08:44.609  6805  6805 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-01 12:08:44.646   968  1056 D BluetoothManagerService: Message: 20
07-01 12:08:44.646   968  1056 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3230224b:true
,07-01 12:08:44.660   968  2143 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6903 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1035, 4002, 1023} abi=armeabi-v7a
,07-01 12:08:44.704  6880  6880 D BluetoothAdapter: 802996774: getState() :  mService = null. Returning STATE_OFF
07-01 12:08:44.704  6880  6880 D BluetoothAdapter: 802996774: getState() :  mService = null. Returning STATE_OFF
,07-01 12:08:44.733   968  1834 D WifiServiceImplEx: setWifiEnabled: false pid=6689, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
,07-01 12:08:44.733   968  1834 D WifiService: setWifiEnabled: false pid=6689, uid=10030
,07-01 12:08:44.744   968   968 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 12:08:44.744   968   968 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 12:08:44.744   968   968 D Ulp_jni : JNI:system_update. Event-4
07-01 12:08:44.758  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-01 12:08:44.765  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-01 12:08:44.771  6841  6841 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-01 12:08:44.771  6841  6841 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-01 12:08:44.771  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 12:08:44.777  6903  6903 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
07-01 12:08:44.777  6903  6903 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-01 12:08:44.777  6903  6903 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-01 12:08:44.779  6903  6903 W ResourcesManager: Asset path '/system/framework/com.broadcom.fm.jar' does not exist or contains no resources.
07-01 12:08:44.788  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-01 12:08:44.796  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:08:44.801  6841  6841 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-01 12:08:44.801  6841  6841 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-01 12:08:44.801  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 12:08:44.804  6903  6903 D BluetoothAdapterApp: Loading JNI Library
,07-01 12:08:44.815  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:08:44.823  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:08:44.825  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 12:08:44.846  6903  6903 E BluetoothServiceJni: [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
07-01 12:08:44.852  6903  6903 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@15807249 Instance Count = 1
,07-01 12:08:44.868   282  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
07-01 12:08:44.869   282  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,07-01 12:08:44.885   968   985 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6924 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-01 12:08:44.887   968  1056 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-01 12:08:44.889  6903  6903 D BluetoothAdapterApp: onCreate
07-01 12:08:44.909  6903  6903 I LGBluetoothServiceJni: classInitNative: succeeds
07-01 12:08:44.911  6903  6903 D BtSettings.ProfileConfig: [BTUI] HeadsetServiceis supported
07-01 12:08:44.913  6903  6903 D BtSettings.ProfileConfig: Adding HeadsetService
,07-01 12:08:44.916  6903  6903 D BtSettings.ProfileConfig: [BTUI] A2dpServiceis supported
07-01 12:08:44.916  6903  6903 D BtSettings.ProfileConfig: Adding A2dpService
07-01 12:08:44.917  6903  6903 D BtSettings.ProfileConfig: [BTUI] HidServiceis supported
07-01 12:08:44.917  6903  6903 D BtSettings.ProfileConfig: Adding HidService
07-01 12:08:44.918  6903  6903 D BtSettings.ProfileConfig: [BTUI] HealthServiceis supported
07-01 12:08:44.918  6903  6903 D BtSettings.ProfileConfig: Adding HealthService
07-01 12:08:44.918  6903  6903 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-01 12:08:44.920  6903  6903 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-01 12:08:44.920  6903  6903 D BtSettings.ProfileConfig: [BTUI] PanServiceis supported
07-01 12:08:44.921  6903  6903 D BtSettings.ProfileConfig: Adding PanService
07-01 12:08:44.922  6903  6903 D BtSettings.ProfileConfig: [BTUI] GattServiceis supported
07-01 12:08:44.922  6903  6903 D BtSettings.ProfileConfig: Adding GattService
07-01 12:08:44.923  6903  6903 D BtSettings.ProfileConfig: [BTUI] BluetoothMapServiceis supported
07-01 12:08:44.923  6903  6903 D BtSettings.ProfileConfig: Adding BluetoothMapService
07-01 12:08:44.924  6903  6903 V LGBluetoothServiceAdapter: [BTUI] region:EU country:EU
07-01 12:08:44.924  6903  6903 D BtSettings.ProfileConfig: [BTUI] SapServiceis supported
07-01 12:08:44.925  6903  6903 D BtSettings.ProfileConfig: Adding SapService
,07-01 12:08:44.926  6903  6903 D BtSettings.ProfileConfig: [BTUI] FTPServiceis supported
07-01 12:08:44.926  6903  6903 D BtSettings.ProfileConfig: Adding FTPService
07-01 12:08:44.927  6903  6903 E BtSettings.ProfileConfig: [BTUI] HeadsetClientServiceis NOT supported
07-01 12:08:44.928  6903  6903 D BtSettings.ProfileConfig: [BTUI] OppServiceis supported
07-01 12:08:44.928  6903  6903 D BtSettings.ProfileConfig: Adding OppService
07-01 12:08:44.934  6903  6903 D BtSettings.ProfileConfig: deviceMode from shared preference   -1
07-01 12:08:44.934  6903  6903 D BtSettings.ProfileConfig: checkAndAdjustDeviceModeConfiguration deviceMode1
07-01 12:08:44.935  6903  6903 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: Unable to read settings
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.checkAndAdjustDeviceModeConfiguration(ProfileConfig.java:400)
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.init(ProfileConfig.java:550)
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: 	at com.lge.bluetooth.adapter.LGBluetoothProfileConfigAdapter.init(LGBluetoothProfileConfigAdapter.java:30)
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterApp.onCreate(AdapterApp.java:67)
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1011)
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4657)
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-01 12:08:44.939  6903  6903 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 12:08:44.940  6903  6903 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-01 12:08:44.940  6903  6903 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-01 12:08:44.940  6903  6903 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-01 12:08:44.941  6903  6903 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 12:08:44.941  6903  6903 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 12:08:44.942  6903  6903 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
07-01 12:08:44.942  6903  6903 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:44.945  6903  6903 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
07-01 12:08:44.953  6805  6805 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,07-01 12:08:44.974  6835  6835 E wpa_supplicant: USIM:  scard_init function
,07-01 12:08:44.976  6835  6835 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-01 12:08:44.978   282  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
07-01 12:08:44.979   282  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 9
07-01 12:08:44.980   968  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-01 12:08:44.980   282  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
07-01 12:08:44.980   968  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-01 12:08:44.988  6903  6903 I FmServiceJni: classInitNative: succeeds
,07-01 12:08:44.993  6903  6903 D FmService: FmReceiverServiceStub createdcom.broadcom.fm.fmreceiver.FmService$FmReceiverServiceStub@854ea05servicecom.broadcom.fm.fmreceiver.FmService@30535a5a
07-01 12:08:44.993  6903  6903 D FmNativehandler: start
07-01 12:08:44.995  6924  6924 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-01 12:08:44.996  6903  6903 D BluetoothRadioManager: [BTUI] getRadioManager()
07-01 12:08:44.999  6903  6903 D BluetoothRadioManager: [BTUI] BluetoothRadioManager()
07-01 12:08:45.002   968  1056 D BluetoothManagerService: Message: 20
07-01 12:08:45.002   968  1056 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6e400be:true
07-01 12:08:45.027  6903  6903 D BluetoothRadioManager: doBind: com.broadcom.bt.service.radiomanager.IBluetoothRadioManager
,07-01 12:08:45.031  6903  6903 V FmService: FM Service  onCreate
07-01 12:08:45.032  6903  6903 D FmService: Binding service...
07-01 12:08:45.033  1799  1799 D FMFRW_FmProxy: Fm proxy onServiceConnected() name = ComponentInfo{com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService}, service = android.os.BinderProxy@20ccabc2
07-01 12:08:45.074  6835  6835 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,07-01 12:08:45.088  6835  6835 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-01 12:08:45.093  6903  6903 D BluetoothAdapterService: Set JNI Library before classInit
07-01 12:08:45.094   968  1306 D WifiStateMachine: MAC Addr from driver = a0:39:f7:70:12:80
07-01 12:08:45.094   968  1306 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-01 12:08:45.096   968   968 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:45.097   968   968 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:45.097   968   968 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:45.097   968   968 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:45.097   968   968 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,07-01 12:08:45.100  1835  1835 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
07-01 12:08:45.100  1835  1835 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-01 12:08:45.1 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-01 12:08:45.100  1835  1835 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
07-01 12:08:45.104   968   968 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-01 12:08:45.105  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:08:45.105  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:45.105  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:08:45.105  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:08:45.105  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:08:45.105  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:08:45.105  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:08:45.105  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:08:45.105  6689  6689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:08:45.106   968  1310 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-01 12:08:45.106  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:08:45.106  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:45.106  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:08:45.106  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:08:45.106  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:08:45.106  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:08:45.106  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:08:45.106  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:08:45.106  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-01 12:08:45.106  6689  6689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:08:45.107  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-01 12:08:45.107  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-01 12:08:45.107  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
07-01 12:08:45.108  6903  6903 D BluetoothAdapterService(864710247): AdapterService() - REFCOUNT: CREATED. INSTANCE_COUNT1
07-01 12:08:45.108   968   968 E WifiServerServiceExt: sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
07-01 12:08:45.108  6903  6903 D BluetoothAdapterService(864710247): onCreate()
07-01 12:08:45.109  6903  6903 D BluetoothAd,apterState: make
,07-01 12:08:45.120  6903  6903 I bluedroid: init
07-01 12:08:45.121  6903  6945 I BluetoothAdapterState: Entering OffState
07-01 12:08:45.126  6903  6903 I bte_conf: Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-01 12:08:45.126  6903  6903 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-01 12:08:45.126  6903  6903 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-01 12:08:45.126  6903  6903 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-01 12:08:45.126  6903  6903 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-01 12:08:45.127  6903  6903 D bt-btif :  [BTUI] Load_abtddress
07-01 12:08:45.127  6903  6903 D BTIF_CORE: [BTUI] lge_wait_for_load_bluetooth_address : success!
07-01 12:08:45.127  6903  6903 D bt-btif : PERSIST_BDADDR_PROPERTY is  F8:95:C7:87:85:54
07-01 12:08:45.127  6903  6903 D bt-btif : Got prior random BDA F8:95:C7:87:85:54
07-01 12:08:45.127  6903  6903 I bluedroid: get_profile_interface socket
07-01 12:08:45.127  6903  6948 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-01 12:08:45.127  6903  6903 I bluedroid: get_profile_interface map_client
07-01 12:08:45.127  6903  6903 E BluetoothServiceJni: Error getting mapclient interface
07-01 12:08:45.127  6903  6948 D bt-btif : btif task starting
07-01 12:08:45.127  6903  6948 D bt-btif : btif_associate_evt: notify ASSOCIATE_JVM
07-01 12:08:45.127  6903  6948 I bt-btif : btif_get_adapter_property_evt_cb
07-01 12:08:45.127  6903  6903 I bt-btif : btif_get_adapter_property 2
07-01 12:08:45.127  6903  6903 I bt-btif : btif_get_adapter_property 1
07-01 12:08:45.133  6903  6903 D BluetoothAdapterService: getAdapterService() - Service not available
07-01 12:08:45.133  6903  6903 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-01 12:08:45.134  6903  6903 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-01 12:08:45.136  6903  6903 D BluetoothAdapterService(864710247): onBind()
07-01 12:08:45.138  6903  6948 I bt-btif : execute storage request event : 3
07-01 12:08:45.138  6903  6948 D bt-btif : btif_storage_get_adapter_property property->type:2 
07-01 12:08:45.138  6903  6948 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
07-01 12:08:45.138  6949  6949 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-01 12:08:45.138  6949  6949 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-01 12:08:45.138  6949  6949 I LGFTMITEM: [GET_FTM][id=8], offset=16384
07-01 12:08:45.139  6903  6948 D BluetoothAdapterProperties: Address is:F8:95:C7:87:85:54
07-01 12:08:45.139  6903  6948 I bt-btif : execute storage request event : 3
07-01 12:08:45.139  6903  6948 D bt-btif : btif_storage_get_adapter_property property->type:1 
07-01 12:08:45.139  6903  6948 D bt-btif : in, bd addr:, prop type:1, len:512
07-01 12:08:45.139  6903  6948 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
07-01 12:08:45.140  6949  6949 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : F8:95:C7:87:85:54
07-01 12:08:45.141   968   968 D BluetoothManagerService: Bluetooth Adapter name changed to G3s-1
07-01 12:08:45.141   968  1306 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-01 12:08:45.141   968   968 D BluetoothManagerService: Stored Bluetooth name: G3s-1
,07-01 12:08:45.143  6903  6903 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-01 12:08:45.143  6903  6903 D BluetoothRadioManager: onServiceConnected: connected to AdapterService com.android.bluetooth.btservice.AdapterService
07-01 12:08:45.144   968  1306 D WifiStateMachine: enableVerboseLogging : level 2
07-01 12:08:45.145  6903  6948 D BluetoothAdapterProperties: Name is: G3s-1
07-01 12:08:45.147  6903  6943 D BluetoothRadioManager: Message: 40
07-01 12:08:45.147  6903  6943 D BluetoothRadioManager: MESSAGE_RADIO_SERVICE_CONNECTED: 1
07-01 12:08:45.147  6903  6943 D BluetoothRadioManager:  Turning on BT modules Radio on = false
07-01 12:08:45.148  6903  6903 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:45.155  6949  6949 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => F8:95:C7:87:85:54
07-01 12:08:45.155  6949  6949 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
07-01 12:08:45.157  1799  1799 D WfdsService: Supplicant Connection state is changed : true
07-01 12:08:45.157   968  1306 D WifiStateMachine: Setting OUI to DA-A1-19
07-01 12:08:45.157  1799  2114 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-01 12:08:45.157  1799  2114 D WfdsService: Set the WFDS Monitor: true
07-01 12:08:45.157  1799  2114 D WfdsMonitor: WfdsMonitorThread create
,07-01 12:08:45.157  1799  2114 D WfdsMonitor: WFDS Monitor is created and started
,07-01 12:08:45.157  1799  2114 D WfdsService: WiFi: Supplicant connection re-established
07-01 12:08:45.158   968  1306 D WifiNative-HAL: Setting external_sim to 1
07-01 12:08:45.158   968  1306 I WifiNative-HAL: startHal
07-01 12:08:45.159  1799  6951 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-01 12:08:45.160  1799  6951 E CtrlSupplicant: Succeed to open control connection
07-01 12:08:45.160  1799  6951 E CtrlSupplicant: Succeed to open monitor connection
07-01 12:08:45.161  1799  6951 D WfdsMonitor: Supplicant connection established
07-01 12:08:45.161  1799  2114 D WfdsService: Connected to the supplicant for wfds
07-01 12:08:45.161  6860  6860 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
07-01 12:08:45.164   968  1306 D wifi    : setting scan oui 0x9dae7fa0
07-01 12:08:45.164   968  1306 D WifiHAL : Sending mac address OUI
07-01 12:08:45.164   968  1306 E WifiHAL : failed to set scanning mac OUI; result = -95
07-01 12:08:45.164   968  1306 D WifiStateMachine: Setting OUI to DA-A1-19
07-01 12:08:45.164   968  1306 I WifiNative-HAL: startHal
07-01 12:08:45.164   968  1306 D wifi    : setting scan oui 0x9dae7fa0
07-01 12:08:45.164   968  1306 D WifiHAL : Sending mac address OUI
07-01 12:08:45.164   968  1306 E WifiHAL : failed to set scanning mac OUI; result = -95
07-01 12:08:45.166  2397  2397 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-01 12:08:45.175  2397  6952 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-01 12:08:45.178  2397  2397 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-01 12:08:45.200   968  1305 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.203   968  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-01 12:08:45.203   968  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-01 12:08:45.203   282  1048 D CommandListener: Setting iface cfg
07-01 12:08:45.203   282  1048 D CommandListener: Trying to bring up p2p0
,07-01 12:08:45.204   968  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-01 12:08:45.204   968  1305 D LGWifiP2pService: P2pEnablingState
07-01 12:08:45.204   968  1305 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.204   968  1305 D LGWifiP2pService: P2p socket connection successful
07-01 12:08:45.204   968  1305 D LGWifiP2pService: P2pEnabledState
07-01 12:08:45.205   968  1305 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-01 12:08:45.205   968  1305 D LGWifiP2pService: before postfix = G3s-1
07-01 12:08:45.205   968  1305 D WifiServerServiceExt: postfix byte check : 5
07-01 12:08:45.205   968  1305 D LGWifiP2pService: after postfix = G3s-1
07-01 12:08:45.206   968   968 D WifiScanningService: SCAN_AVAILABLE : 3
07-01 12:08:45.206   968   968 D RttService: SCAN_AVAILABLE : 3
07-01 12:08:45.206   968  1325 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.206   968  1325 I WifiNative-HAL: startHal
07-01 12:08:45.207   968  1326 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.212   968  1325 D wifi    : getting scan capabilities on interface[0] = 0x9dae7fa0
07-01 12:08:45.212   968  1325 D WifiHAL : Creating message to get scan capablities; iface = 24
07-01 12:08:45.212   968  1325 D wifi    : failed to get capabilities : -95
07-01 12:08:45.212   968  1325 E WifiScanningService: could not get scan capabilities
07-01 12:08:45.213   968  1305 D WifiNative-HAL: p2pGetDeviceAddress
07-01 12:08:45.213   968  1305 D WifiNative-HAL: p2pGetDeviceAddress returning a2:39:f7:70:12:80
07-01 12:08:45.216  1799  1799 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-01 12:08:45.216  1799  1799 D WfdsService: Update P2p Interface State: 3
,07-01 12:08:45.217   968  1305 D LGWifiP2pService: DeviceAddress: a2:39:f7:70:12:80
,07-01 12:08:45.221   968   968 D WifiScanningService: SCAN_AVAILABLE : 1
07-01 12:08:45.221   968   968 D RttService: SCAN_AVAILABLE : 1
07-01 12:08:45.221   968  1325 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.221   968  1326 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.222   968  1306 E WifiStateMachine: Error! unhandled message{ when=-119ms what=132103 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.223   968  1306 E WifiStateMachine: Error! unhandled message{ when=-118ms what=132106 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.224   968  1306 E WifiStateMachine: Error! unhandled message{ when=-117ms what=132096 arg1=-100 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.226   968  1306 E WifiStateMachine: Error! unhandled message{ when=-118ms what=132156 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.227   968  1306 E WifiStateMachine: Error! unhandled message{ when=-84ms what=132104 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.242   968  1305 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-01 12:08:45.243   968  1305 D LGWifiP2pService: sending p2p connection changed broadcast
07-01 12:08:45.243   968  1305 D LGWifiP2pService: InactiveState
07-01 12:08:45.243   968  1305 D LGWifiP2pService: InactiveState{ when=-23ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.244   968  1305 D LGWifiP2pService: P2pEnabledState{ when=-23ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.244   968  1305 D LGWifiP2pService: P2pDisablingState
07-01 12:08:45.244   968  1305 D LGWifiP2pService: P2pDisablingState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.244   968  1305 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,07-01 12:08:45.248  3391  3848 D dur     : Opening database auth.proximity.permit_store...
07-01 12:08:45.249  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
07-01 12:08:45.250  2397  6952 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
07-01 12:08:45.251  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
07-01 12:08:45.252   968  1305 D LGWifiP2pService: P2pDisablingState{ when=-8ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.252   968  1305 D LGWifiP2pService: DefaultState{ when=-9ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.252  1799  1799 D WfdsService: WifiP2pState is changed : true
07-01 12:08:45.252  1799  1799 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-01 12:08:45.253  1799  2114 D WfdsService: Receive the WFDS_ENABLE Method
07-01 12:08:45.253  1799  2114 D WfdsService: Set the WFDS Monitor: true
07-01 12:08:45.253  1799  2114 D WfdsService: Connected to the supplicant for wfds
07-01 12:08:45.253  1799  1799 D WfdsService: isConnected: false
07-01 12:08:45.253  1799  1799 D WfdsService: WifiP2pState is changed : false
07-01 12:08:45.253   968  1305 D LGWifiP2pService: P2pDisablingState{ when=-10ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.253   968  1305 D LGWifiP2pService: p2p socket connection lost
07-01 12:08:45.253   968   968 E WifiServerServiceExt: No p2p device connected
07-01 12:08:45.253   968  1305 D LGWifiP2pService: P2pDisabledState
07-01 12:08:45.254   968  1305 D LGWifiP2pService: P2pDisabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.254   968  1305 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.254   968  1305 D LGWifiP2pService: P2pDisabledState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.254   968  1305 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:45.254  1799  1799 D WfdsService: GroupInfoAvailable: mGroupInfo is null
07-01 12:08:45.254  1799  2114 D WfdsJNI : doCommand: WFDS_SET TRUE
07-01 12:08:45.255  6835  6835 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-01 12:08:45.255  1799  2114 D WfdsJNI : doCommand: WFDS_CLEAR_PD_INFO
07-01 12:08:45.255  6835  6835 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
07-01 12:08:45.255   282  1048 D CommandListener: Clearing all IP addresses on wlan0
07-01 12:08:45.256  1799  2114 D WfdsJNI : wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
07-01 12:08:45.256  1799  2114 D WfdsService: selectPreferredScanChannel [6]
07-01 12:08:45.256  1799  2114 D WfdsService: STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
07-01 12:08:45.256  1799  2114 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-01 12:08:45.256  1799  2114 D WfdsJNI : doCommand: P2P_STOP_FIND
07-01 12:08:45.256  1799  2114 D WfdsService: Set the WFDS Monitor: false
07-01 12:08:45.257  1799  2114 D WfdsMonitor: WFDS Monitor is stopped
07-01 12:08:45.257  1799  2114 D WfdsService: STATE : WfdsDisabledState - enter
07-01 12:08:45.257  1799  2114 D WfdsService: WFDS: Scanner is paused
07-01 12:08:45.257  1799  2114 D WfdsDiscoveryStore: Clear Discovery Method Map: ScanAlwaysMode false
07-01 12:08:45.258  1799  2114 W WfdsService: DefaultState - msg [9441285] is not handled
07-01 12:08:45.258  1799  6951 D CtrlSupplicant: Received on exit socket, terminate
07-01 12:08:45.258  1799  6951 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-01 12:08:45.258  1799  6951 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-01 12:08:45.258  1799  6951 D WfdsMo,nitor: WfdsMonitorThread is received the interrupt - closing
07-01 12:08:45.258  1799  2109 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-01 12:08:45.259   968   968 D WifiHS20: hidePasspointNotification off =false
,07-01 12:08:45.259  1835  1835 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-01 12:08:45.261   968   968 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:45.261   968   968 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:45.261   968   968 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-01 12:08:45.262  1835  1835 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-01 12:08:45.26 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-01 12:08:45.262   968   968 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-01 12:08:45.262  1835  1835 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
07-01 12:08:45.262  1835  1835 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
07-01 12:08:45.263  1835  1835 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-01 12:08:45.263 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-01 12:08:45.263  1835  1835 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
07-01 12:08:45.263  1370  1370 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 12:08:45.263  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:08:45.263  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:45.263  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:08:45.263  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:08:45.263  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:08:45.263  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:08:45.263  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:08:45.263  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:08:45.263  6689  6689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:08:45.264  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:08:45.264  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:45.264  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:08:45.264  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:08:45.264  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:08:45.264  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:08:45.264  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:08:45.264  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:08:45.264  6689  6689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:08:45.266  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-01 12:08:45.266  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawab,le/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-01 12:08:45.266  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-01 12:08:45.266  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-01 12:08:45.266  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-01 12:08:45.266  1370  1370 I [SystemUI]QuickSettingsHandler: Remote
07-01 12:08:45.268  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-01 12:08:45.268  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-01 12:08:45.268  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
07-01 12:08:45.269  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
,07-01 12:08:45.361   968   999 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-01 12:08:45.361   968   999 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-01 12:08:45.361   968   999 D sensors_hal_Time: tsOffsetIs: Apps: 174365171084; DSPS: 5805549; Offset : -2811490800
,07-01 12:08:45.368  6924  6958 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-01 12:08:45.368  6924  6958 I Babel_SMS: MmsConfig.loadMmsSettings
07-01 12:08:45.372  6924  6958 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
07-01 12:08:45.372  6924  6958 I Babel_SMS: MmsConfig.loadFromDatabase
07-01 12:08:45.376   282  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
,07-01 12:08:45.376   282  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 5
07-01 12:08:45.377   282  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 10
07-01 12:08:45.377  6835  6835 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-01 12:08:45.377  6835  6835 I wpa_supplicant: monitor socket send errors count : 1
07-01 12:08:45.377  6835  6835 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1799-4\x00 that cannot receive messages
07-01 12:08:45.377   282  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 7
07-01 12:08:45.377  6835  6835 W wpa_supplicant: USIM:  scard_deinit function
07-01 12:08:45.387   968  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-01 12:08:45.387   968  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-01 12:08:45.403  6924  6958 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-01 12:08:45.403  6924  6958 I Babel_SMS: MmsConfig.loadFromResources
07-01 12:08:45.405  6924  6958 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-01 12:08:45.405   968  1054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-01 12:08:45.405   968  1054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-01 12:08:45.408  6924  6958 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
07-01 12:08:45.456   282  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,07-01 12:08:45.483   282  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 5
,07-01 12:08:45.484   968  1056 D Tethering: InitialState.processMessage what=4
07-01 12:08:45.484  6835  6835 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-01 12:08:45.485   968  1056 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-01 12:08:45.489  6924  6924 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
07-01 12:08:45.489  6924  6924 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
07-01 12:08:45.489  6924  6924 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
07-01 12:08:45.489  6924  6924 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
07-01 12:08:45.489  6924  6924 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
07-01 12:08:45.489  6924  6924 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
07-01 12:08:45.489  6924  6924 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
07-01 12:08:45.489  6924  6924 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
07-01 12:08:45.489  6924  6924 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
07-01 12:08:45.489  6924  6924 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
07-01 12:08:45.489  6924  6924 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
07-01 12:08:45.489  6924  6924 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
07-01 12:08:45.489  6924  6924 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
07-01 12:08:45.489  6924  6924 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
07-01 12:08:45.489  6924  6924 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
07-01 12:08:45.490  6924  6924 D SensorManager: found sensor: Motion Accel, handle=46
,07-01 12:08:45.532  6924  6924 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-01 12:08:45.535  6924  6924 I Babel_Crash: startup - clean
07-01 12:08:45.560  6924  6940 I art     : CheckpointMarkThreadRoots callback created = 0xafc2d480
,07-01 12:08:45.571  6924  6962 I Babel   : deleted: false for 0
07-01 12:08:45.589   968  1306 D WifiOffDelayIfNotUsed: stopMonitoring
,07-01 12:08:45.589  1799  1799 D WfdsService: Supplicant Connection state is changed : false
07-01 12:08:45.590  1799  2114 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-01 12:08:45.590  1799  2114 D WfdsService: Set the WFDS Monitor: false
07-01 12:08:45.590  1799  2114 D WfdsMonitor: WFDS Monitor is stopped
07-01 12:08:45.592   968   968 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-01 12:08:45.593  2397  2739 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:45.594   968  1310 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-01 12:08:45.594   968  1310 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-01 12:08:45.594  1835  1835 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
07-01 12:08:45.594  1835  1835 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-01 12:08:45.594 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-01 12:08:45.595  1835  1835 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
07-01 12:08:45.597  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:08:45.597  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-01 12:08:45.597  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-01 12:08:45.598  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
07-01 12:08:45.598  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
07-01 12:08:45.598  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:08:45.614  6924  6940 I art     : CheckpointMarkThreadRoots callback created = 0xafc2d460
,07-01 12:08:45.657  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-01 12:08:45.657  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-01 12:08:45.657  6805  6805 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-01 12:08:45.657  6805  6805 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-01 12:08:45.658  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,07-01 12:08:45.666  6924  6924 W AudioCapabilities: Unsupported mime audio/x-lg-flac
07-01 12:08:45.669  6924  6924 W AudioCapabilities: Unsupported mime audio/adpcm
07-01 12:08:45.670  6924  6924 W AudioCapabilities: Unsupported mime audio/g726
07-01 12:08:45.672  6924  6924 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-01 12:08:45.674  6924  6924 W AudioCapabilities: Unsupported mime audio/wma-voice
07-01 12:08:45.676  6924  6924 W VideoCapabilities: Unsupported mime video/mjpg
07-01 12:08:45.679  6924  6924 W VideoCapabilities: Unsupported mime video/theora
07-01 12:08:45.685  6805  6805 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-01 12:08:45.685  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-01 12:08:45.686  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-01 12:08:45.686  6805  6805 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-01 12:08:45.686  6805  6805 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-01 12:08:45.686  6805  6805 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,07-01 12:08:45.727  6924  6924 W AudioCapabilities: Unsupported mime audio/evrc
07-01 12:08:45.728  6924  6924 W AudioCapabilities: Unsupported mime audio/qcelp
,07-01 12:08:45.733  6924  6924 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-01 12:08:45.734   968  1897 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6966 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
07-01 12:08:45.826   968  3633 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-01 12:08:45.826   968  3633 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
07-01 12:08:45.835  6924  6924 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
07-01 12:08:45.837   968   968 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 12:08:45.837   968   968 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 12:08:45.838   968   968 D Ulp_jni : JNI:system_update. Event-4
,07-01 12:08:45.838   968  1056 D BluetoothManagerService: Message: 1
07-01 12:08:45.838   968  1056 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-01 12:08:45.840  6903  6903 D BluetoothAdapterService(864710247): onBind()
07-01 12:08:45.841   968   968 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-01 12:08:45.841   968  1056 D BluetoothManagerService: Message: 40
07-01 12:08:45.841   968  1056 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-01 12:08:45.842  6903  6921 I bluedroid: config_hci_snoop_log
07-01 12:08:45.844   968  1056 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-01 12:08:45.844   968  1056 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
07-01 12:08:45.844  6924  6924 W AudioCapabilities: Unsupported mime audio/qcelp
07-01 12:08:45.846  6924  6924 W AudioCapabilities: Unsupported mime audio/evrc
07-01 12:08:45.854  6903  6919 V LGMDMManagerInternal: Create singleton instance
,07-01 12:08:45.898  6924  6924 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-01 12:08:45.943  6924  6924 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-01 12:08:45.951  6903  6919 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:45.951  6903  6919 D BluetoothAdapterService(864710247): enable() - Enable called with quiet mode status =  false
07-01 12:08:45.951  6903  6945 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-01 12:08:45.951  6903  6945 D BluetoothAdapterProperties: Setting state to 11
07-01 12:08:45.951  6903  6945 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-01 12:08:45.952  6903  6945 D BluetoothAdapterService(864710247): updateAdapterState() - Broadcasting state to 1 receivers.
07-01 12:08:45.952   968  1056 D BluetoothManagerService: Message: 60
07-01 12:08:45.952   968  1056 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-01 12:08:45.952   968  1056 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-01 12:08:45.953  6903  6945 D BluetoothAdapterService(864710247): processStart()
07-01 12:08:45.953  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-01 12:08:45.953  1799  1799 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:45.954  6903  6945 D BtSettings.ProfileConfig: Unable to read settings
07-01 12:08:45.954  6903  6945 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-01 12:08:45.954  6903  6945 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
07-01 12:08:45.954  6903  6945 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
07-01 12:08:45.954  6903  6945 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
07-01 12:08:45.954  6903  6945 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
07-01 12:08:45.954  6903  6945 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
07-01 12:08:45.954  6903  6945 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
07-01 12:08:45.954  6903  6945 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
07-01 12:08:45.954  6903  6945 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:45.954  6903  6945 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
07-01 12:08:45.954  6903  6945 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:08:45.955  6903  6945 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-01 12:08:45.955  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-01 12:08:45.955  6903  6945 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-01 12:08:45.955  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 12:08:45.956  6903  6945 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
07-01 12:08:45.956  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-01 12:08:45.956  6903  6945 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
07-01 12:08:45.956  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-01 12:08:45.956  6903  6945 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
07-01 12:08:45.956  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-01 12:08:45.956  6805  6805 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-01 12:08:45.956  6903  6945 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
07-01 12:08:45.956  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 12:08:45.956  6903  6945 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
07-01 12:08:45.956  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 12:08:45.956  6903  6945 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,07-01 12:08:45.956  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
07-01 12:08:45.956  6903  6945 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
07-01 12:08:45.956  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:45.956  6903  6919 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:45.956  6903  6945 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
07-01 12:08:45.956  6903  6945 D BluetoothAdapterService(864710247): processStart() - Make Bond State Machine
07-01 12:08:45.957  6903  6945 D BluetoothBondStateMachine: make
07-01 12:08:45.957  6903  6921 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:45.959  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
07-01 12:08:45.959  1370  1370 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
07-01 12:08:45.960  6903  6945 D BluetoothAdapterService: setAdapterService() - set to: null
07-01 12:08:45.960  6903  6945 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:45.960  6903  6945 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-01 12:08:45.960  6903  6985 I BluetoothBondStateMachine: StableState(): Entering Off State
07-01 12:08:45.961  6924  6924 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-01 12:08:45.964  6924  6924 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-01 12:08:45.968  6903  6903 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-01 12:08:45.969  6903  6903 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:45.969  6903  6903 V BluetoothPbapReceiver: ***********state = 11
,07-01 12:08:45.972  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:45.972  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-01 12:08:45.972  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-01 12:08:45.973  6903  6945 D BtSettings.ProfileConfig: Unable to read settings
07-01 12:08:45.973  6903  6945 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-01 12:08:45.973  6903  6945 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
07-01 12:08:45.973  6903  6945 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
07-01 12:08:45.973  6903  6945 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
07-01 12:08:45.973  6903  6945 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
07-01 12:08:45.973  6903  6945 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
07-01 12:08:45.973  6903  6945 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
07-01 12:08:45.973  6903  6945 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
07-01 12:08:45.973  6903  6945 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
07-01 12:08:45.973  6903  6945 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:45.973  6903  6945 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
07-01 12:08:45.973  6903  6945 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:08:45.973  6903  6945 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
07-01 12:08:45.973  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
07-01 12:08:45.979  6924  6924 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-01 12:08:45.979  6903  6903 D HeadsetService: Received start request. Starting profile...
07-01 12:08:45.980  6805  6805 D BluetoothPermissionRequest: onReceive
07-01 12:08:45.980  6903  6903 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,07-01 12:08:45.982  6903  6903 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-01 12:08:45.983  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:45.983  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-01 12:08:45.983  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-01 12:08:45.983  6903  6945 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
07-01 12:08:45.983  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
07-01 12:08:45.983  6903  6903 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-01 12:08:45.984  6903  6903 D HeadsetStateMachine: make
07-01 12:08:45.990  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:45.990  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-01 12:08:45.990  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 12:08:45.990  6903  6945 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-01 12:08:45.990  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
07-01 12:08:45.996  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:45.996  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-01 12:08:45.996  6924  6924 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-01 12:08:45.996  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-01 12:08:45.996  6903  6945 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-01 12:08:45.996  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
,07-01 12:08:46.002  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:46.002  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-01 12:08:46.002  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-01 12:08:46.002  6903  6945 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-01 12:08:46.002  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
07-01 12:08:46.003  6966  6966 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 12:08:46.004  6966  6966 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-01 12:08:46.008  6924  6924 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:46.010  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:46.010  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
07-01 12:08:46.010  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-01 12:08:46.010  6903  6945 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
07-01 12:08:46.010  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
07-01 12:08:46.011  6924  6924 I vclib   : onServiceConnected
,07-01 12:08:46.012  6924  6924 W Babel   : Attempted to change video mute state without an active call.
07-01 12:08:46.024  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-01 12:08:46.065   968  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-01 12:08:46.074  6924  6924 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
07-01 12:08:46.226   968  1805 I art     : Explicit concurrent mark sweep GC freed 64956(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 2.112ms total 213.460ms
,07-01 12:08:46.230  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-01 12:08:46.231   968  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-01 12:08:46.232  6903  6903 D HeadsetStateMachine: max_hf_connections = 1
07-01 12:08:46.232  6903  6903 I bluedroid: get_profile_interface handsfree
07-01 12:08:46.232  6903  6903 I bt-btif : btif_hf_get_interface
07-01 12:08:46.232  6903  6903 I bt-btif : init
07-01 12:08:46.232  6903  6903 D bt-btif : max_hf_clients = 1
07-01 12:08:46.232  6903  6903 D bt-btif : btif_max_hf_clients = 1
07-01 12:08:46.232  6903  6903 D bt-btif : btif_enable_service: current services:0xa068b330
07-01 12:08:46.236  6903  6903 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-01 12:08:46.237   288  1351 V AudioPolicyService: registerClient() client 0xb4027080, uid 1002
07-01 12:08:46.238   288  1297 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
,07-01 12:08:46.240  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:46.240  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
07-01 12:08:46.240  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 12:08:46.240  6903  6945 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
07-01 12:08:46.240  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
07-01 12:08:46.240   288  1297 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-01 12:08:46.240   288  1297 V AudioPolicyManagerEx: getOutput() returns output 2
07-01 12:08:46.241   288  2050 V AudioFlinger: registerClient() client 0xb3c5c388, pid 6903
07-01 12:08:46.241   288  2050 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
07-01 12:08:46.241   288  2050 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
07-01 12:08:46.241   288  2050 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
07-01 12:08:46.241  6903  6903 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-01 12:08:46.242   288  1293 V AudioFlinger: thread 0xb5735000 type 0 TID 1293 waking up
07-01 12:08:46.242   288  1291 V AudioFlinger: thread 0xb56eb000 type 0 TID 1291 waking up
07-01 12:08:46.242   288  1288 V AudioFlinger: thread 0xb5651000 type 0 TID 1288 waking up
07-01 12:08:46.243   288  1288 V AudioFlinger: processConfigEvents_l() remaining events 1
07-01 12:08:46.243   288  1293 V AudioFlinger: processConfigEvents_l() remaining events 1
07-01 12:08:46.243   288  1293 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
07-01 12:08:46.243  6903  6903 V ToneGenerator: Create Track: 0xb4909480
07-01 12:08:46.243  6903  6903 V AudioTrack: set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-01 12:08:46.243  6903  6903 V AudioTrack: set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
07-01 12:08:46.243   288   288 I AudioFlinger: isAudioPlaybackHookOn() false
07-01 12:08:46.243   288  1288 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
07-01 12:08:46.243   288  1293 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-01 12:08:46.243   288  1293 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-01 12:08:46.244   288  1291 V AudioFlinger: processConfigEvents_l() remaining events 1
07-01 12:08:46.244   288  1291 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
07-01 12:08:46.245  6903  6903 D AudioTrack: TrackOffload: AudioTrack Offload disabled by property, returning false
07-01 12:08:46.246   288  1297 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-01 12:08:46.246   288  1297 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-01 12:08:46.246   288  1297 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-01 12:08:46.246   288  1297 V AudioPolicyManagerEx: getOutput() returns output 2
07-01 12:08:46.247  1932  1956 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-01 12:08:46.247   288  1293 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5735000
07-01 12:08:46.247   288  1288 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:08:46.247   288  1288 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 12:08:46.247  1932  1956 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-01 12:08:46.247   288  1288 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5651000
07-01 12:08:46.247   288  1291 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:08:46.247   288  1291 V Audio,System: ioConfigChanged() opening already existing output! 4
07-01 12:08:46.247   288  1291 V AudioFlinger: processConfigEvents_l() DONE thread 0xb56eb000
07-01 12:08:46.248   968  1897 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-01 12:08:46.248   968  1897 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-01 12:08:46.248  1932  1955 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:08:46.248  1932  1955 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 12:08:46.248   968  1897 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:08:46.248   968  1897 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 12:08:46.248  1932  1955 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:08:46.248  1932  1955 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 12:08:46.248   968  1897 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:08:46.248   968  1897 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 12:08:46.248  3199  3215 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-01 12:08:46.248  3199  3215 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-01 12:08:46.249   968  1034 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-01 12:08:46.249  6903  6903 V AudioSystem: getLatency() output 2, latency 50
07-01 12:08:46.249  6903  6903 V AudioSystem: getFrameCount() output 2, frameCount 960
07-01 12:08:46.249  6903  6903 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-01 12:08:46.249  6903  6903 V AudioTrack: createTrack_l() output 2 afLatency 50
07-01 12:08:46.249  6903  6903 V AudioTrack: Create normal PCM 0x1 Track
07-01 12:08:46.250   288  2061 V AudioFlinger: createTrack() lSessionId: 23
07-01 12:08:46.250   288  2061 V AudioFlinger: AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
07-01 12:08:46.250   288  2061 V AudioFlinger: sendConfigEvent_l() num events 1 event 1
,07-01 12:08:46.253  3199  3215 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:08:46.253  3199  3215 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 12:08:46.253  3199  3215 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:08:46.253  1370  2477 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-01 12:08:46.253  1370  2477 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-01 12:08:46.253  1370  2477 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:08:46.253  1370  2477 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 12:08:46.254  1747  2366 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-01 12:08:46.254  2931  4102 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-01 12:08:46.254  2931  4102 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-01 12:08:46.254  2931  4102 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:08:46.254  2931  4102 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 12:08:46.254  2931  4102 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:08:46.254  2931  4102 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 12:08:46.255  6903  6919 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-01 12:08:46.255  6903  6919 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
07-01 12:08:46.255  6903  6919 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:08:46.255  6903  6919 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-01 12:08:46.255  1747  2366 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-01 12:08:46.253  3199  3215 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 12:08:46.256  6903  6919 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:08:46.257  6903  6919 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-01 12:08:46.257   968   968 D LocSvc_java: onReceive
07-01 12:08:46.257  1747  2366 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:08:46.257   968   968 D LocSvc_java: got connectivity action
07-01 12:08:46.257  1747  2366 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 12:08:46.257  1747  2366 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:08:46.257  1747  2366 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 12:08:46.257  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
07-01 12:08:46.258  1370  2477 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:08:46.258  1370  2477 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 12:08:46.258   288  1288 V AudioFlinger: processConfigEvents_l() remaining events 1
07-01 12:08:46.259   288  1288 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5651000
07-01 12:08:46.260  6903  6903 V AudioTrack: Flags here  0x4 
07-01 12:08:46.260  6903  6903 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-01 12:08:46.261   968   968 D LocSvc_java: broadcast - no network connections
07-01 12:08:46.261   968   968 D LocSvc_java: Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
07-01 12:08:46.261   968   968 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-01 12:08:46.261   968   968 D LocSvc_java: onReceive
07-01 12:08:46.262   968   968 D LocSvc_java: got connectivity action
07-01 12:08:46.262   968   968 D LocSvc_java: broadcast - no network connections
07-01 12:08:46.262   968   968 D LocSvc_java: Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
07-01 12:08:46.262   968   968 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-01 12:08:46.262   968   968 D LocSvc_java: getAGpsConnectionInfo con,nType - 4
07-01 12:08:46.262   968   968 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-01 12:08:46.262   968   968 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-01 12:08:46.262   968   968 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-01 12:08:46.262   968   968 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-01 12:08:46.262   968   968 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,07-01 12:08:46.264   288  2061 V AudioFlinger: acquiring 23 from 6903, for 6903
07-01 12:08:46.264   288  2061 V AudioFlinger:  added new entry for 23
07-01 12:08:46.267  6903  6903 V ToneGenerator: ToneGenerator INIT OK, time: 175272
07-01 12:08:46.267  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:46.269  6903  6987 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-01 12:08:46.269  6903  6987 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-01 12:08:46.269  6903  6987 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-01 12:08:46.269  6903  6987 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-01 12:08:46.271  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:46.271  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:08:46.272   288  2050 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6903
07-01 12:08:46.272  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:08:46.273   288  2050 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-01 12:08:46.273   288  2050 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-01 12:08:46.273   288  2050 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-01 12:08:46.273   288  2050 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-01 12:08:46.273   288  2050 V voice   : voice_set_parameters: exit with code(0)
07-01 12:08:46.273   288  2050 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-01 12:08:46.273   288  2050 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-01 12:08:46.273   288  2050 V msm8974_platform: platform_set_parameters: exit with code(0)
07-01 12:08:46.273   288  2050 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-01 12:08:46.273   288  2050 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
07-01 12:08:46.273   288  2050 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-01 12:08:46.274  6903  6987 V ToneGenerator: ToneGenerator destructor
07-01 12:08:46.274  6903  6987 V ToneGenerator: stopTone
07-01 12:08:46.274  6903  6987 V ToneGenerator: Delete Track: 0xb4909480
07-01 12:08:46.274  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
,07-01 12:08:46.274  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
07-01 12:08:46.274  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 12:08:46.274  6903  6945 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-01 12:08:46.274  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
07-01 12:08:46.274  6903  6987 V AudioTrack: ~AudioTrack, releasing session id from 6903 on behalf of 6903
07-01 12:08:46.274   288   288 V AudioFlinger: remove track (4099) and delete from mixer
07-01 12:08:46.274   288  1297 V AudioFlinger: releasing 23 from 6903 for 6903
07-01 12:08:46.274   288   288 V AudioPolicyService: AudioCommandThread() adding release output 2
07-01 12:08:46.274   288  1297 V AudioFlinger:  decremented refcount to 0
07-01 12:08:46.274   288  1297 V AudioFlinger: purging stale effects
07-01 12:08:46.274   288   288 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-01 12:08:46.274   288   288 V AudioFlinger: PlaybackThread::Track destructor
07-01 12:08:46.274   288  1064 V AudioPolicyService: AudioCommandThread() waking up
07-01 12:08:46.274   288   288 V AudioFlinger: removeClient_l() pid 6903, calling pid 288
07-01 12:08:46.274   288  1064 V AudioPolicyService: AudioCommandThread() processing release output 2
07-01 12:08:46.274   288  1064 V AudioPolicyManager: releaseOutput() 2
07-01 12:08:46.274   288  1064 V AudioPolicyService: AudioCommandThread() going to sleep
07-01 12:08:46.276  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:08:46.278  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:08:46.281  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-01 12:08:46.284  6966  6989 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-01 12:08:46.286  6903  6903 D A2dpService: Received start request. Starting profile...
07-01 12:08:46.286  6903  6903 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-01 12:08:46.288  6903  6903 V Avrcp   : make
07-01 12:08:46.288  6903  6903 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-01 12:08:46.288  6903  6903 I bluedroid: get_profile_interface avrcp
07-01 12:08:46.288  6903  6903 I bt-btif : btif_rc_get_interface
07-01 12:08:46.288  6903  6903 I bt-btif : ## init ##
07-01 12:08:46.289  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:46.289  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
07-01 12:08:46.289  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
07-01 12:08:46.289  6903  6945 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.ftp.FTPService
07-01 12:08:46.289  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
07-01 12:08:46.290  6903  6903 I LGBluetoothAvrcpServiceJni: classInitNative: succeeds
07-01 12:08:46.290  6903  6903 I LGBluetoothAvrcpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-01 12:08:46.290  6903  6903 I LGBluetoothAvrcpServiceJni: initNative: succeeds
07-01 12:08:46.291  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
,07-01 12:08:46.297  6903  6903 I BluetoothAvrcpBrcmAdapterJni: classInitBrcmNative
07-01 12:08:46.300  6966  6990 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 12:08:46.300  6966  6990 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-01 12:08:46.302   968  1034 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-01 12:08:46.307  6903  6903 I BluetoothAvrcpBrcmAdapterJni: initBrcmNative
,07-01 12:08:46.309  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:46.309  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
07-01 12:08:46.309  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:46.309  6903  6945 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.opp.OppService
07-01 12:08:46.309  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
07-01 12:08:46.315  1932  1932 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
07-01 12:08:46.320  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:08:46.321  6903  6945 V LGMDMManager: Create singleton instance
,07-01 12:08:46.325   968  1034 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:08:46.335  6841  6841 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-01 12:08:46.335  6841  6841 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,07-01 12:08:46.336  6903  6945 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-01 12:08:46.335  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 12:08:46.338   968  1034 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:08:46.352  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:08:46.363  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:08:46.367  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-01 12:08:46.432   968  1861 V AudioService: updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
,07-01 12:08:46.435   968  1861 E AudioService: No RCC entry present to update
07-01 12:08:46.436  6903  6903 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-01 12:08:46.437  6903  6903 I BluetoothA2dpServiceJni: classInitNative
07-01 12:08:46.437  6903  6903 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-01 12:08:46.437  6903  6903 D A2dpStateMachine: make
07-01 12:08:46.439  6903  6903 I bluedroid: get_profile_interface a2dp
07-01 12:08:46.439  6903  6903 I bt-btif : btif_av_get_src_interface
07-01 12:08:46.439  6903  6903 I bt-btif : init
07-01 12:08:46.439  6903  6903 D bt-btif : btif_enable_service: current services:0xa068b330
07-01 12:08:46.441  6903  6903 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-01 12:08:46.441  6903  6903 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-01 12:08:46.442  6903  6903 D LGBluetoothPowerControlManager: [BTUI] getInstance
07-01 12:08:46.443  6903  6903 D LGBluetoothPowerControlManager: [BTUI] init
07-01 12:08:46.444  6903  6903 D LGBluetoothPowerControlManager: [BTUI] init : getProfileProxy
07-01 12:08:46.446   968  1056 D BluetoothManagerService: Message: 30
,07-01 12:08:46.515   968  1941 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6999 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-01 12:08:46.516  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
,07-01 12:08:46.516  6903  6997 D A2dpStateMachine: Enter Disconnected: -2
,07-01 12:08:46.517  6903  6903 I BluetoothHidServiceJni: classInitNative: succeeds
07-01 12:08:46.531  6880  6880 V LGMDMManager: Create singleton instance
,07-01 12:08:46.556  6903  6903 D HidService: Received start request. Starting profile...
07-01 12:08:46.556  6903  6903 I bluedroid: get_profile_interface hidhost
,07-01 12:08:46.559  6903  6903 I bt-btif : btif_hh_get_interface
07-01 12:08:46.559  6903  6903 I bt-btif : init
07-01 12:08:46.559  6903  6903 D bt-btif : btif_enable_service: current services:0xa068b330
07-01 12:08:46.559  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:46.561  6903  6903 I BluetoothHealthServiceJni: classInitNative: succeeds
07-01 12:08:46.563  6903  6903 D HealthService: Received start request. Starting profile...
07-01 12:08:46.564  6903  6903 I bluedroid: get_profile_interface health
07-01 12:08:46.565  6903  6903 I bt-btif : btif_hl_get_interface
07-01 12:08:46.565  6903  6903 I bt-btif : init
07-01 12:08:46.565  6903  6903 D bt-btif : Process name (droid.bluetooth)
07-01 12:08:46.565  6903  6903 D bt-btif : btif_hl_soc_thread_init
07-01 12:08:46.567  6903  6903 D bt-btif : create_thread: entered
07-01 12:08:46.567  6903  6903 D bt-btif : create_thread: thread created successfully
07-01 12:08:46.567  6903  7014 D bt-btif : entered btif_hl_select_thread
07-01 12:08:46.567  6903  7014 D bt-btif : btif_hl_select_wakeup_init
07-01 12:08:46.567  6903  7014 D bt-btif : btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
07-01 12:08:46.567  6903  7014 D bt-btif : max_s=55 
07-01 12:08:46.567  6903  7014 D bt-btif : set curr_set = org_set 
07-01 12:08:46.567  6903  6903 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-01 12:08:46.568  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:46.568  6903  6903 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-01 12:08:46.572  6903  6903 D PanService: Received start request. Starting profile...
07-01 12:08:46.572  6903  6903 D BluetoothPanServiceJni: initializeNative(L110): pan
07-01 12:08:46.572  6903  6903 I bluedroid: get_profile_interface pan
07-01 12:08:46.572  6903  6903 D bt-btif : stack_initialized = 0, btpan_cb.enabled:0
,07-01 12:08:46.595   968  1834 I ActivityManager: Process com.google.android.gms.unstable (pid 6562) has died
,07-01 12:08:46.599  6903  6903 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-01 12:08:46.599  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:46.601  6903  6903 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-01 12:08:46.607  6880  6880 I AudioManager: getMode name:com.lge.qremote
07-01 12:08:46.608  6903  6903 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-01 12:08:46.608  6903  6903 D BtGatt.GattService: Received start request. Starting profile...
07-01 12:08:46.608  6903  6903 D BtGatt.GattService: start()
07-01 12:08:46.609  6903  6903 I bluedroid: get_profile_interface gatt
07-01 12:08:46.609  6903  6903 D BtGatt.AdvertiseManager: advertise manager created
07-01 12:08:46.614  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-01 12:08:46.618  6903  6903 I LGBluetoothGattAdapter: [BTUI] getInstance : create [LGBluetoothGattAdapter]
07-01 12:08:46.618  6903  6903 D LGBluetoothGattAdapter: setGattService:  set to: null
07-01 12:08:46.618  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:46.618  6903  6903 D HeadsetStateMachine: Proxy object connected
07-01 12:08:46.620  6903  6903 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,07-01 12:08:46.625  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:46.625  6903  6903 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-01 12:08:46.626  6903  6903 V BluetoothMapService: BluetoothMapBinder()
07-01 12:08:46.627  6903  6903 D BluetoothMapService: Received start request. Starting profile...
07-01 12:08:46.627  6903  6903 D BluetoothMapService: start()
07-01 12:08:46.627  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:08:46.629  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 12:08:46.632  6903  6903 D BluetoothMapEmailSettingsLoader: Found 0 applications
,07-01 12:08:46.632  6903  6903 D BluetoothMapEmailAppObserver: createReceiver()
07-01 12:08:46.636  6903  6903 D BluetoothMapEmailAppObserver: initObservers()
07-01 12:08:46.636  6903  6903 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-01 12:08:46.646  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
,07-01 12:08:46.646  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:46.646  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:46.647  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
07-01 12:08:46.647  6903  6903 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:46.647  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:46.647  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:46.647  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:46.648  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-01 12:08:46.649  6966  6966 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 12:08:46.650  6966  6966 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-01 12:08:46.651  6903  6903 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-01 12:08:46.652  6903  6987 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-01 12:08:46.652  6903  6987 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-01 12:08:46.652  6903  6987 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-01 12:08:46.653  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-01 12:08:46.656  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-01 12:08:46.658  6903  6903 I BluetoothSAPServiceJni: classInitNative(L170): succeeds
,07-01 12:08:46.660  6903  6903 D SapService: Received start request. Starting profile...
07-01 12:08:46.660  6903  6903 D BluetoothSAPServiceJni: initializeNative(L175): sap
07-01 12:08:46.660  6903  6903 I bluedroid: get_profile_interface sap
07-01 12:08:46.660  6903  6903 I bt-btif : btif_sc_get_interface
07-01 12:08:46.660  6903  6903 I bt-btif : init
07-01 12:08:46.660  6903  6903 D bt-btif : btif_enable_service: current services:0xa068b330
07-01 12:08:46.660  6903  6903 I LGBluetoothSapAdapter: [BTUI] getInstance : create [LGBluetoothSapAdapter]
07-01 12:08:46.660  6903  6903 I LGBluetoothSapAdapter: [BTUI] Create LGBluetoothSapManager Instance
07-01 12:08:46.661  6903  6903 D LGBluetoothSapManager: [BTUI] initSapManager
07-01 12:08:46.663  1747  1747 D LgeBluetoothSimManager: [BTUI] SAP_ENABLE_EVT
07-01 12:08:46.665  6999  6999 D UEI.SmartControl: Quickset Services start...
07-01 12:08:46.666  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:46.669  6999  6999 I UEI.SmartControl: Manufacture = LGE
07-01 12:08:46.671  6999  6999 D UEI.SmartControl: File observer start...
07-01 12:08:46.672  6999  6999 E UEI.SmartControl: IR Port is disabled: false
07-01 12:08:46.672  6999  6999 D UEI.SmartControl: Starting file observer...
07-01 12:08:46.673  6999  6999 D UEI.SmartControl: Extracting JNI libs...
07-01 12:08:46.674  6999  6999 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,07-01 12:08:46.677  6903  6903 V BluetoothFTPServiceJni: classInitNative
07-01 12:08:46.678  6966  7023 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-01 12:08:46.678  6903  6903 I BluetoothFTPServiceJni: classInitNative(L271): succeeds
07-01 12:08:46.679  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:46.680  6903  6903 D BluetoothFTPService: BluetoothFtpBinder()
07-01 12:08:46.680  6903  6903 D **BluetoothFTPService: Received start request. Starting profile...
07-01 12:08:46.680  6903  6903 V BluetoothFTPService: FTP-Server Service start
07-01 12:08:46.680  6966  7024 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 12:08:46.681  6966  7024 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-01 12:08:46.683  6903  6903 D BluetoothFTPServiceJni: initFtpNativeDataNative(L275): FTP
07-01 12:08:46.683  6903  6903 I bluedroid: get_profile_interface ftp
07-01 12:08:46.683  6903  6903 I bt-btif : btif_fts_get_interface
07-01 12:08:46.683  6903  6903 I bt-btif : init
07-01 12:08:46.683  6903  6903 D bt-btif : btif_enable_service: current services:0xa068b330
07-01 12:08:46.683  6903  6903 D BluetoothFTPServiceJni: initFtpNativeDataNative(L317): FTP init done
07-01 12:08:46.683  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:46.683  6903  6903 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-01 12:08:46.683  6903  6903 E BluetoothOPPServiceJni: classInitNative
07-01 12:08:46.684  6903  6903 I BluetoothOPPServiceJni: classInitNative(L373): succeeds
07-01 12:08:46.684  6903  6903 V OppService: Opp initBinder
07-01 12:08:46.686  6903  6903 D **OppService: Received start request. Starting profile...
07-01 12:08:46.686  6903  6903 D OppService: Starting OppService 
,07-01 12:08:46.691  6903  6903 I NotificationManager: com.android.bluetooth: cancelAll by com.android.bluetooth
07-01 12:08:46.692  6903  6903 V BluetoothOppNotification: send message
07-01 12:08:46.697  6903  6903 D BluetoothOppPreference: Dumping Names:  
07-01 12:08:46.697  6903  6903 D BluetoothOppPreference: {}
07-01 12:08:46.697  6903  6903 D BluetoothOppPreference: Dumping Channels:  
07-01 12:08:46.698  6903  6903 D BluetoothOppPreference: {}
07-01 12:08:46.698  6903  6903 D OppService: Start()
07-01 12:08:46.699  6903  6903 W BluetoothOPPServiceJni: initOppNative
07-01 12:08:46.699  6903  6903 D BluetoothOPPServiceJni: initOppNative(L383): OPP
07-01 12:08:46.699  6903  6903 I bluedroid: get_profile_interface opp
07-01 12:08:46.699  6903  6903 I bt-btif : btif_op_get_interface
07-01 12:08:46.699  6903  6903 D BluetoothOPPServiceJni: initOppNative(L411): mOppCallbacksObj 1049854
07-01 12:08:46.699  6903  6903 D BluetoothOPPServiceJni: initOppNative(L413): calling OPP init
,07-01 12:08:46.701  6903  6903 I bt-btif : btif_opp_init
07-01 12:08:46.701  6903  6903 D bt-btif : btif_enable_service: current services:0xa068b330
07-01 12:08:46.701  6903  6903 D BluetoothOPPServiceJni: initOppNative(L429): OPC and OPS init Succesful
07-01 12:08:46.701  6903  6903 D BluetoothOPPServiceJni: initOppNative(L430): mOppCallbacksObj 1049854
07-01 12:08:46.702  6903  6903 V OppService: setOppService(): set to: com.broadcom.bt.service.opp.OppService@386a3c5
07-01 12:08:46.702  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:46.702  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:46.702  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:46.702  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
07-01 12:08:46.702  6903  6903 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:46.702  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:46.702  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:46.702  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:46.702  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-01 12:08:46.704  6444  6444 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-01 12:08:46.705  6444  6444 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
07-01 12:08:46.705  6903  6903 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-01 12:08:46.706  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:46.706  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:46.706  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
07-01 12:08:46.706  6903  6903 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:46.707  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:46.707  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:46.707  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:46.707  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-01 12:08:46.709  6903  6903 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-01 12:08:46.709  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:46.709  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:46.709  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
07-01 12:08:46.709  6903  6903 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:46.709  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:46.709  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:46.709  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:46.710  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-01 12:08:46.711  6903  7028 V OppService: pendingUpdate is :  true
,07-01 12:08:46.712  6903  7028 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-01 12:08:46.712  6903  6903 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-01 12:08:46.713  6903  6903 V PanService: [BTUI] SIM Extra State :ABSENT
07-01 12:08:46.715  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:46.715  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:46.715  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
07-01 12:08:46.715  6903  6903 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:46.715  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:46.715  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:46.715  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:46.716  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-01 12:08:46.718  6903  6903 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-01 12:08:46.719  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:46.719  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:46.719  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
07-01 12:08:46.719  6903  6903 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:46.719  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:46.719  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:46.719  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:46.719  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-01 12:08:46.720  6903  7028 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3cab9e28 on behalf of 
07-01 12:08:46.722  6903  6903 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-01 12:08:46.722  6903  7028 V BluetoothOppNotification: update too frequent, put in queue
07-01 12:08:46.722  6903  6903 V BluetoothMapService: Handler(): got msg=1
07-01 12:08:46.723  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:46.723  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:46.723  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
07-01 12:08:46.723  6903  6903 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:46.723  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:46.723  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:46.723  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:46.723  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-01 12:08:46.724  6903  7028 V OppService: pendingUpdate is :  false
07-01 12:08:46.724  6903  7028 E OppService: UpdateThread is Completed
,07-01 12:08:46.725  6903  7025 V OppService: Deleted complete outbound shares, number =  0
07-01 12:08:46.726  6903  6903 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-01 12:08:46.726  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:46.726  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:46.726  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
07-01 12:08:46.726  6903  6903 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:46.726  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:46.726  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:46.726  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:46.726  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-01 12:08:46.729  6903  7025 V OppService: Deleted complete inbound failed shares, number = 0
07-01 12:08:46.729  6903  7025 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-01 12:08:46.733  6903  7025 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a32b741 on behalf of 
07-01 12:08:46.733  6903  6903 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-01 12:08:46.733  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:46.733  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:46.733  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
07-01 12:08:46.733  6903  6903 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:46.733  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:46.733  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:46.733  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:46.734  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-01 12:08:46.736  6903  6903 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-01 12:08:46.736  6903  6903 V BluetoothOppNotification: new notify threadi!
,07-01 12:08:46.737  6903  6903 V BluetoothOppNotification: send delay message
07-01 12:08:46.737  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:46.737  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:46.737  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
07-01 12:08:46.737  6903  6903 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:46.737  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:46.737  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:46.737  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:46.737  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-01 12:08:46.737  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() - All profile services started.
07-01 12:08:46.737  6903  6903 D BluetoothA2dp: Proxy object connected
07-01 12:08:46.738  6903  6903 D LGBluetoothPowerControlManager: [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@18b404e6
07-01 12:08:46.739  6903  6903 V OppService: ContentObserver received notification
07-01 12:08:46.739  6903  6945 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-01 12:08:46.739  6903  6945 I bluedroid: enable
07-01 12:08:46.739  6903  6945 I bt-btif : BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
07-01 12:08:46.739  6903  6945 E bt-btu  : VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
07-01 12:08:46.740  6903  6903 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-01 12:08:46.740  6903  6903 V OppService: ContentObserver received notification
07-01 12:08:46.741  6903  7030 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-01 12:08:46.742  6903  7030 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e085a27 on behalf of 
07-01 12:08:46.743  6903  7030 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-01 12:08:46.743  6903  6903 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:46.744  6903  7030 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-01 12:08:46.744  6903  7032 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-01 12:08:46.744  6903  6945 I bt_hci_bdroid: init
07-01 12:08:46.744  6903  7032 I bt-btu  : btu_task pending for preload complete event
07-01 12:08:46.745  6903  6945 I bt_vendor: init
07-01 12:08:46.746  6903  6945 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-01 12:08:46.746  6903  6945 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-01 12:08:46.746  6903  7030 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@263074d4 on behalf of 
07-01 12:08:46.746  6860  6860 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
07-01 12:08:46.746  6903  6945 I bt-btif : libbt-hci init returns 0
07-01 12:08:46.747  6903  7030 V BluetoothOppNotification: outbound: succ-0  fail-0
07-01 12:08:46.747  6903  7030 I NotificationManager: com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
07-01 12:08:46.748  6903  7,030 V BluetoothOppNotification: outbound notification was removed.
07-01 12:08:46.748  6903  7030 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-01 12:08:46.750  6903  7030 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3632867d on behalf of 
07-01 12:08:46.750  2397  2397 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-01 12:08:46.750  6903  7030 V BluetoothOppNotification: inbound: succ-0  fail-0
07-01 12:08:46.751  6903  7030 I NotificationManager: com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
07-01 12:08:46.752  6903  7030 V BluetoothOppNotification: inbound notification was removed.
07-01 12:08:46.752  6903  7030 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-01 12:08:46.753  6903  7030 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a2b8972 on behalf of 
07-01 12:08:46.753  2397  2397 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-01 12:08:46.765  6903  7031 V OppService: pendingUpdate is :  true
07-01 12:08:46.765  6903  7031 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-01 12:08:46.767  6903  7031 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@89671c3 on behalf of 
07-01 12:08:46.768  6903  7031 V OppService: pendingUpdate is :  false
07-01 12:08:46.768  6903  7031 E OppService: UpdateThread is Completed
,07-01 12:08:46.769  6444  6444 V [BNRBootReceiver]: Boot Receiver Return
07-01 12:08:46.772  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-01 12:08:46.776  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:08:46.781  6841  6841 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-01 12:08:46.781  6841  6841 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-01 12:08:46.781  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-01 12:08:46.787  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:08:46.801  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:08:46.803  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 12:08:46.817  6966  6966 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 12:08:46.817  6966  6966 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-01 12:08:46.818  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,07-01 12:08:46.823  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-01 12:08:46.827  6805  6805 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-01 12:08:46.828  6966  7035 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-01 12:08:46.833  6903  7034 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
07-01 12:08:46.836  6805  6805 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:08:46.838   968   986 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 12:08:46.838   968   986 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@37402d8c mBinding = false
07-01 12:08:46.839  6841  6841 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-01 12:08:46.839  6841  6841 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-01 12:08:46.839  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 12:08:46.839  6903  7034 D bt_userial_vendor: userial_vendor_open():UART is setup
07-01 12:08:46.840  6903  7034 I bt_userial_vendor: device fd = 67 open
07-01 12:08:46.841  6966  7036 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 12:08:46.841  6966  7036 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-01 12:08:46.847   968  1056 D BluetoothManagerService: Message: 2
07-01 12:08:46.849   968   968 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 12:08:46.849   968   968 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 12:08:46.849   968   968 D Ulp_jni : JNI:system_update. Event-4
07-01 12:08:46.850  6903  6984 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:46.850  6903  7034 D bt_hwcfg: hw_config_cback opcode:0x0c03
07-01 12:08:46.850  6903  7034 D bt_hwcfg: hw_config_cback state=1
07-01 12:08:46.862   288  1297 V AudioFlinger: 2931 died, releasing its sessions
07-01 12:08:46.862   288  1297 V AudioFlinger:  pid 1747 @ 0
07-01 12:08:46.862   288  1297 V AudioFlinger:  pid 3199 @ 1
07-01 12:08:46.862   288  1297 V AudioFlinger:  pid 3199 @ 2
,07-01 12:08:46.876  6903  7034 D bt_hwcfg: hw_config_cback opcode:0x0c14
,07-01 12:08:46.876  6903  7034 D bt_hwcfg: hw_config_cback state=4
07-01 12:08:46.876  6903  7034 D bt_hwcfg: Chipset Name: BCM4334B0
07-01 12:08:46.876  6903  7034 D bt_hwcfg: Chipset BCM4334B0
07-01 12:08:46.876  6903  7034 D bt_hwcfg: Target name = [BCM4334B0]
07-01 12:08:46.877  6903  7034 I bt_hwcfg: Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
07-01 12:08:46.882  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc45
07-01 12:08:46.882  6903  7034 D bt_hwcfg: hw_config_cback state=2
07-01 12:08:46.887  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc18
07-01 12:08:46.887  6903  7034 D bt_hwcfg: hw_config_cback state=3
07-01 12:08:46.887  6903  7034 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-01 12:08:46.898   968  1941 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7039 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-01 12:08:46.911  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc2e
07-01 12:08:46.911  6903  7034 D bt_hwcfg: hw_config_cback state=5
07-01 12:08:46.955   968  1781 I ActivityManager: Process com.lge.music (pid 2931) has died
,07-01 12:08:46.965  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.965  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.966  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.966  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.967  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.967  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.968  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.968  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.969  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.969  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.970  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.970  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.970  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.971  6903  7034 D bt_hwcfg: hw_config_cback state=6
,07-01 12:08:46.971  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.971  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.972  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.972  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.973  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.973  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.974  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.974  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.975  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.975  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.976  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.976  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.977  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.977  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.978  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.978  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.979  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.979  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.980  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.980  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.981  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.981  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.982  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.982  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.983  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.983  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.984  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.984  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.985  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,07-01 12:08:46.985  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.986  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.986  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.987  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.987  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.989  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.989  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.990  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.990  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.991  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.991  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.992  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.992  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.993  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.993  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.993  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.994  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.995  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.995  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.996  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.996  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.996  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.997  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.997  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.997  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:46.999  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:46.999  6903  7034 D bt_hwcfg: hw_config_cback state=6
,07-01 12:08:47.001  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.001  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.002  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.002  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.003  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.003  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.004  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.004  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.004  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.004  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.005  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.005  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.006  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.006  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.007  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.007  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.007  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.007  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.008  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.008  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.008  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.008  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.009  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.009  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.011  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.011  6903  7034 D bt_hwcfg: hw_config_cback state=6
,07-01 12:08:47.013  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.013  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.013  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.013  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.014  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.014  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.014  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.014  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.015  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.015  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.016  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.016  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.016  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.017  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.017  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.017  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.018  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.018  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.019  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.019  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.020  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.020  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.021  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.021  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.022  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.022  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.023  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.023  6903  7034 D bt_hwcfg: hw_config_cback state=6
,07-01 12:08:47.024  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.024  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.025  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.025  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.026  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.026  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.027  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.027  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.027  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.027  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.028  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.028  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.029  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.029  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.029  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.029  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.030  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.030  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.031  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.031  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.031  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.031  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.032  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.032  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.033  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.033  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.034  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.034  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.035  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,07-01 12:08:47.035  6903  7034 D bt_hwcfg: hw_config_cback state=6
,07-01 12:08:47.036  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.036  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.037  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.037  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.038  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.038  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.039  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.039  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.039  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,07-01 12:08:47.039  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.040  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.040  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.040  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.040  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.041  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.041  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.042  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.042  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.043  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,07-01 12:08:47.043  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.043  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.043  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.044  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.044  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.045  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.045  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.047  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.047  6903  7034 D bt_hwcfg: hw_config_cback state=6
,07-01 12:08:47.048  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.048  6903  7034 D bt_hwcfg: hw_config_cback state=6
,07-01 12:08:47.049  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.049  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.049  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.049  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.050  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.050  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.050  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.050  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.051  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.051  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.051  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.051  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.052  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.052  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.053  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.053  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.054  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.054  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.055  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.055  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.056  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.056  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.057  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.057  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.058  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.058  6903  7034 D bt_hwcfg: hw_config_cback state=6
,07-01 12:08:47.060  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.061  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.061  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.061  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.062  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.062  6903  7034 D bt_hwcfg: hw_config_cback state=6
,07-01 12:08:47.063  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.063  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.064  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.064  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.065  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.065  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.066  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.066  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.067  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.067  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.068  6999  6999 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-01 12:08:47.068  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.068  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.069  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.069  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.070  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.070  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.070  6999  6999 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-01 12:08:47.071  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.071  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.071  6999  6999 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-01 12:08:47.072  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.072  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.073  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.073  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.073  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.074  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.074  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.074  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.075  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.075  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.076  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.076  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.077  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.077  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.078  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.078  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.078  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.078  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.079  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.079  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.080  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.080  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.081  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.081  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.083  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.083  6903  7034 D bt_hwcfg: hw_config_cback state=6
,07-01 12:08:47.084  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.084  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.084  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.084  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.085  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.085  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.086  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.086  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.087  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.087  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.088  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.088  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.089  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.089  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.090  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.090  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.091  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.091  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.092  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.092  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.093  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.093  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.095  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.095  6903  7034 D bt_hwcfg: hw_config_cback state=6
,07-01 12:08:47.095  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.095  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.096  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.096  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.098  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.098  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.099  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.099  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.099  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.099  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.100  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.100  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.101  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.101  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.102  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.102  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.103  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.103  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.104  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.104  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.105  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.105  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.107  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.107  6903  7034 D bt_hwcfg: hw_config_cback state=6
,07-01 12:08:47.109  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.109  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.110  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.110  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.111  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.111  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.112  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.112  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.113  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.113  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.113  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.113  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.114  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.114  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.115  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.115  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.116  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.116  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.117  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.117  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.119  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.119  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.120  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.120  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.121  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.121  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.122  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.122  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.122  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.123  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.123  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.123  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.124  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.124  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.124  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.125  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.125  6999  6999 I UEI.SmartControl: --- Selecting new region: 2
07-01 12:08:47.126  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.126  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.126  6999  6999 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
07-01 12:08:47.126  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.126  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.127  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.127  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.127  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.127  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.128  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.128  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.128  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.128  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.129  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.129  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.129  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.129  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.130  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.130  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.131  6999  6999 D UEI.SmartControl: Platform has CIR...
07-01 12:08:47.132  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.132  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.132  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.132  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.132  6999  6999 D UEI.SmartControl: NO CIR support, need to check package...
07-01 12:08:47.133  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.133  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.133  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.133  6903  7034 D bt_hwcfg: hw_config_cback state=6
,07-01 12:08:47.133  6999  6999 I UEI.SmartControl: Model: LG-D722 uses JNI
07-01 12:08:47.135  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.135  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.136  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.136  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.136  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.136  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.137  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.137  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.137  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.137  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.138  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.138  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.139  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.139  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.139  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.139  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.140  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.140  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.140  6999  6999 D UEI.SmartControl: QS Service created
07-01 12:08:47.141  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.141  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.141  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.141  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.142  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.142  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.144  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.144  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.144  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.144  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.145  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.145  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.146  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.146  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.147  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.147  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.148  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.148  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.149  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.149  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.150  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.150  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.151  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.151  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.152  6903  6919 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:47.152  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.152  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.153  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.153  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.154  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.154  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.155  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.155  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.155  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.155  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.156  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.156  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.156  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.156  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.157  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.157  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.158  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.158  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.159  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.159  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.160  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.160  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.160  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.160  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.161  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.161  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.162  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.162  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.163  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.163  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.164  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.164  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.164  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.164  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.165  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.165  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.166  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.166  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.167  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.167  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.168  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.168  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.169  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.169  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.170  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.170  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.171  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.171  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.172  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.172  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.173  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.173  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.174  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.174  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.175  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.175  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.176  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.176  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.176  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.176  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.177  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.177  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.178  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.178  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.179  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.179  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.180  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.180  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.181  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.181  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.182   968   986 I ActivityManager: Process com.google.android.talk (pid 6924) has died
07-01 12:08:47.182  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.182  6903  7034 D bt_hwcfg: hw_config_cback state=6
,07-01 12:08:47.183  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.183  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.184  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.184  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.184  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.185  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.185  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.185  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.186  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.186  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.187  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.187  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.187  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.187  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.188  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.188  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.188  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.188  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.189  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.189  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.190  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.190  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.191  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.191  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.192  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.192  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.193  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.193  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.194  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.194  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.195  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.195  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.196  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.196  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.197  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.197  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.198  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.198  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.199  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.199  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.200  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.200  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.201  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.201  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.202  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.202  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.203  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.203  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.204  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.204  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.205  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.205  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.206  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.206  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.207  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.207  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.208  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.208  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.208  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.209  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.209  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.209  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.210  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.210  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.210  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.210  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.211  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.211  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.212  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.212  6999  6999 E UEI.SmartControl: QS start get config
07-01 12:08:47.212  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.213  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.213  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.214  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.214  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.215  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.215  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.216  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.216  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.217  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.217  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.218  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.218  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.219  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.219  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.219  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.219  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.220  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.220  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.220  7039  7039 I MusicStore: Database version: 120
07-01 12:08:47.221  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.221  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.222  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.222  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.222  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.222  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.223  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.223  6903  7034 D bt_hwcfg: hw_config_cback state=6
,07-01 12:08:47.224  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.224  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.225  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.225  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.226  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.226  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.227  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.227  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.228  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.228  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.228  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.228  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.229  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.229  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.229  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.230  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.230  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.230  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.231  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.231  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.231  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.232  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.232  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.232  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.233  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.233  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.234  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.234  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.235  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.235  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.236  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.236  6903  7034 D bt_hwcfg: hw_config_cback state=6
,07-01 12:08:47.236  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.236  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.237  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.237  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.238  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.238  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.239  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.239  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.240  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.240  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.241  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.241  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.242  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.242  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.243  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.243  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.244  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.244  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.245  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.245  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.245  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.245  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.246  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.246  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.247  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.247  6903  7034 D bt_hwcfg: hw_config_cback state=6
,07-01 12:08:47.248  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.249  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.250  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.250  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.251  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.251  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.252  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.252  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.253  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.253  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.253  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.253  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.253  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.253  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.254  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.254  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.254  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.254  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.254  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.255  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.255  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.255  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.256  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.256  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.256  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.256  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.256  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.256  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.257  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.257  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.257  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.257  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.257  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.257  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.258  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.258  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.258  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.258  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.258  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.259  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.259  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.259  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.259  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.259  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.260  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.260  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.260  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.260  6903  7034 D bt_hwcfg: hw_config_cback state=6
,07-01 12:08:47.260  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.260  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.261  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.261  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.261  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.261  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.261  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.261  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.262  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.262  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.262  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.262  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.263  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.263  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.263  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.263  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.263  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.264  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.264  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.264  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.265  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.265  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.265  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.265  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.265  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.265  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.266  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.266  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.266  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.266  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.267  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-01 12:08:47.267  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.267  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc4e
07-01 12:08:47.267  6903  7034 D bt_hwcfg: hw_config_cback state=6
07-01 12:08:47.268  6999  6999 D UEI.SmartControl: Loading JNI Libs...
07-01 12:08:47.270  6999  6999 D UEI.SmartControl:  configuring local db...
07-01 12:08:47.328   247   316 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-01 12:08:47.329   247   316 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-01 12:08:47.329   247   316 W Vold    : Returning OperationFailed - no handler for errno 0
,07-01 12:08:47.338  7039  7039 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
07-01 12:08:47.367  6903  7034 I bt_hwcfg: bt vendor lib: set UART baud 115200
07-01 12:08:47.367  6903  7034 D bt_hwcfg: Settlement delay -- 100 ms
07-01 12:08:47.368  6903  7034 I bt_hwcfg: Setting fw settlement delay to 100 
,07-01 12:08:47.453  6903  6984 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
,07-01 12:08:47.472   247   316 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-01 12:08:47.472   247   316 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-01 12:08:47.472   247   316 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 12:08:47.472  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc45
07-01 12:08:47.472  6903  7034 D bt_hwcfg: hw_config_cback state=2
07-01 12:08:47.474  7039  7039 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,07-01 12:08:47.477   247   316 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-01 12:08:47.477   247   316 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,07-01 12:08:47.477   247   316 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 12:08:47.477  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc18
07-01 12:08:47.477  6903  7034 D bt_hwcfg: hw_config_cback state=7
07-01 12:08:47.477  6903  7034 I bt_hwcfg: bt vendor lib: set UART baud 4000000
07-01 12:08:47.478  6903  7034 I bt_hwcfg: Setting local bd addr to F8:95:C7:87:85:54
07-01 12:08:47.478  7039  7039 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
07-01 12:08:47.500  6903  7034 D bt_hwcfg: hw_config_cback opcode:0xfc01
07-01 12:08:47.500  6903  7034 D bt_hwcfg: hw_config_cback state=8
07-01 12:08:47.500  6903  7034 I bt_hwcfg: vendor lib fwcfg completed
07-01 12:08:47.500  6903  7034 I bt-btif : HC preload_cb 0 [0:SUCCESS 1:FAIL]
07-01 12:08:47.501  6903  7032 I bt-btu  : btu_task received preload complete event
,07-01 12:08:47.504  6999  6999 D UEI.SmartControl:  ---- Has DB8: true
07-01 12:08:47.512  6903  7032 I         : BTE_InitTraceLevels -- TRC_HCI,2
07-01 12:08:47.512  6903  7032 I         : BTE_InitTraceLevels -- TRC_L2CAP,2
07-01 12:08:47.512  6903  7032 I         : BTE_InitTraceLevels -- TRC_RFCOMM,2
07-01 12:08:47.512  6903  7032 I         : BTE_InitTraceLevels -- TRC_OBEX,2
07-01 12:08:47.512  6903  7032 I         : BTE_InitTraceLevels -- TRC_AVCT,2
07-01 12:08:47.512  6903  7032 I         : BTE_InitTraceLevels -- TRC_AVDT,2
07-01 12:08:47.512  6903  7032 I         : BTE_InitTraceLevels -- TRC_AVRC,2
,07-01 12:08:47.512  6903  7032 I         : BTE_InitTraceLevels -- TRC_AVDT_SCB,2
07-01 12:08:47.512  6903  7032 I         : BTE_InitTraceLevels -- TRC_A2D,2
07-01 12:08:47.512  6903  7032 I         : BTE_InitTraceLevels -- TRC_BNEP,2
07-01 12:08:47.512  6903  7032 I         : BTE_InitTraceLevels -- TRC_BTM,2
07-01 12:08:47.512  6903  7032 I         : BTE_InitTraceLevels -- TRC_GAP,2
07-01 12:08:47.512  6999  6999 D UEI.SmartControl: QS start statue = true Error code = 0
07-01 12:08:47.512  6903  7032 I         : BTE_InitTraceLevels -- TRC_PAN,2
07-01 12:08:47.512  6903  7032 I         : BTE_InitTraceLevels -- TRC_SAP,2
07-01 12:08:47.513  6903  7032 I         : BTE_InitTraceLevels -- TRC_SDP,2
07-01 12:08:47.513  6903  7032 I         : BTE_InitTraceLevels -- TRC_GATT,2
07-01 12:08:47.513  6903  7032 I         : BTE_InitTraceLevels -- TRC_SMP,2
07-01 12:08:47.513  6903  7032 I         : BTE_InitTraceLevels -- TRC_BTAPP,3
07-01 12:08:47.513  6903  7032 I         : BTE_InitTraceLevels -- TRC_BTIF,3
07-01 12:08:47.513  6903  7032 I         : BTE_InitTraceLevels -- TRC_PROTOCOL,0
07-01 12:08:47.514  6999  6999 D UEI.SmartControl: QS version = v2.7.11.1_RC1
,07-01 12:08:47.518  6999  6999 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
07-01 12:08:47.524  6999  6999 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
07-01 12:08:47.560  6999  6999 W irrc_jni: IRRCPlayer_nativeInit ++ 
07-01 12:08:47.560  6999  6999 D irrcClient: IrrcClient ++ 
07-01 12:08:47.560  6999  6999 D irrcClient: getIrrcService ++ 
07-01 12:08:47.561  6999  6999 D irrcClient: getIrrcService -- 
,07-01 12:08:47.561  6999  6999 D irrcClient: IrrcClient -- 
07-01 12:08:47.561  6999  6999 W irrc_jni: IRRCPlayer_nativeInit -- 
07-01 12:08:47.568  6999  6999 D UEI.SmartControl: Services init done
07-01 12:08:47.569  6999  7064 I UEI.SmartControl: Device manager: loading config....
07-01 12:08:47.573  6999  6999 D UEI.SmartControl: QS Service init finished
,07-01 12:08:47.576  6999  6999 D UEI.SmartControl: QS Service version name: 0.1.73
07-01 12:08:47.577  6999  6999 D UEI.SmartControl: QS Service version code: 1073
07-01 12:08:47.578  6999  7064 D UEI.SmartControl: Config is loaded...
07-01 12:08:47.579  6999  6999 D UEI.SmartControl: Service requested: Control
07-01 12:08:47.583  6999  6999 D UEI.SmartControl: Internal service binding...
07-01 12:08:47.585  6999  7016 D UEI.SmartControl: -----IControl: 11
07-01 12:08:47.586  6999  7016 D UEI.SmartControl: Caller: com.lge.qremote
,07-01 12:08:47.589  6999  7016 D UEI.SmartControl: ------------ IControl registerCallback...
07-01 12:08:47.590  6999  7016 I UEI.SmartControl: Registering callback...
07-01 12:08:47.592  6999  7018 D UEI.SmartControl: -----IControl: 19
07-01 12:08:47.593  6999  7018 D UEI.SmartControl: Caller: com.lge.qremote
07-01 12:08:47.593  6999  7018 I UEI.SmartControl: Registering Services Ready callback...
07-01 12:08:47.594  6999  7018 I UEI.SmartControl: Notify client services are ready...
07-01 12:08:47.596  6999  7016 D UEI.SmartControl: -----IControl: 8
07-01 12:08:47.597  6999  7016 D UEI.SmartControl: Caller: com.lge.qremote
07-01 12:08:47.618  6999  7063 D UEI.SmartControl:  ----- QS SDK is ready!!!
07-01 12:08:47.619  6999  7063 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-01 12:08:47.625  7039  7039 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-01 12:08:47.625  7039  7039 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-01 12:08:47.661  6903  7032 E bt-btif : bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
,07-01 12:08:47.663  6903  7066 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-01 12:08:47.663  6903  6948 E bt-btif : warning : media task started media_task_refcnt 1 
07-01 12:08:47.664  6903  7066 D BT_PROF_AUDIO: created moving average (N=100)
,07-01 12:08:47.664  6903  7066 D BT_PROF_AUDIO: reset rate average
07-01 12:08:47.664  6903  7066 W bt-btif : overflow 0, enter 0, exit 0
07-01 12:08:47.669  6903  6948 E bt-btif : Calling BTA_HhEnable
07-01 12:08:47.669  6903  6948 E bt-btif : btif_storage_get_adapter_property service_mask:0x1201c8
07-01 12:08:47.670  6903  6948 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
07-01 12:08:47.670  6903  6948 D BluetoothAdapterProperties: Address is:F8:95:C7:87:85:54
07-01 12:08:47.670  6903  7032 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
07-01 12:08:47.670  6903  7032 W bt-smp  : Plain text(LSB ~ MSB) = ec 84 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-01 12:08:47.670  6903  7032 W bt-smp  : Encrypted text(LSB ~ MSB) = e9 2a 01 5b 6c 66 36 1a 3d bc b5 55 5d 28 6f 89 
07-01 12:08:47.670  6903  7032 W bt-btm  : Stopping oneshot timer
07-01 12:08:47.671  6903  6948 D BluetoothAdapterProperties: Name is: G3s-1
07-01 12:08:47.671   968   968 D BluetoothManagerService: Bluetooth Adapter name changed to G3s-1
07-01 12:08:47.671   968   968 D BluetoothManagerService: Stored Bluetooth name: G3s-1
07-01 12:08:47.672  6903  6948 D BluetoothAdapterProperties: Scan Mode:20
07-01 12:08:47.672  6903  6948 D BluetoothAdapterProperties: Discoverable Timeout:120
07-01 12:08:47.673  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:08:47.673  6903  6948 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,07-01 12:08:47.673  6903  6948 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
07-01 12:08:47.674  6903  6948 E bt-btif : btif_sock_init: !radio_req && !rfc_init
07-01 12:08:47.674  6903  6948 I bt-btif : BTA_JvEnable
07-01 12:08:47.674  6903  6948 E bt-btif : btsock_vendor_hci_init: !vhci_init
07-01 12:08:47.674  6903  6948 D bt-btif : btsock_ctrl_hci_init(L191): poll handle:6
07-01 12:08:47.675  6903  6948 D bt-btif : init_hci_slots(L136): in
07-01 12:08:47.675  6903  6948 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
07-01 12:08:47.676  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:08:47.701  6903  7034 D bt_h4   : vendor lib postload completed
,07-01 12:08:47.720  6903  6948 D IOP_DB_BT: db_open: db_open : handle 2691258332l, read 11046 bytes onto local cache
07-01 12:08:47.720  6903  6948 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,07-01 12:08:47.720  6903  6948 D IOP_DB_BT: db_query: result 1
,07-01 12:08:47.720  6903  6948 I         : iop_db_open: iop_db_open status 0
07-01 12:08:47.720  6903  6948 E bt-btif : btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
,07-01 12:08:47.720  6903  6948 D bt-btif : btsock_ctrl_hci_init(L191): poll handle:6
07-01 12:08:47.721  6903  7032 I bt-btif : bta_pan_co_init
07-01 12:08:47.738  6903  6903 V BluetoothOppNotification: new notify threadi!
07-01 12:08:47.738  6903  6903 V BluetoothOppNotification: send delay message
07-01 12:08:47.740  6903  7072 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,07-01 12:08:47.741  6903  7072 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e8a0a40 on behalf of 
07-01 12:08:47.741  6903  7072 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-01 12:08:47.742  6903  7072 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-01 12:08:47.743  6903  7072 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d660d79 on behalf of 
07-01 12:08:47.743  6903  7072 V BluetoothOppNotification: outbound: succ-0  fail-0
07-01 12:08:47.744  6903  7072 I NotificationManager: com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
07-01 12:08:47.744  6903  7072 V BluetoothOppNotification: outbound notification was removed.
07-01 12:08:47.745  6903  7072 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-01 12:08:47.745  6903  7072 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@124cabe on behalf of 
07-01 12:08:47.746  6903  7072 V BluetoothOppNotification: inbound: succ-0  fail-0
07-01 12:08:47.747  6903  7072 I NotificationManager: com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
07-01 12:08:47.747  6903  7072 V BluetoothOppNotification: inbound notification was removed.
07-01 12:08:47.747  6903  7072 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-01 12:08:47.748  6903  7072 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f64671f on behalf of 
07-01 12:08:47.756  6903  6984 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
,07-01 12:08:47.761  6903  6948 D bte_conf: Device ID record 1 : primary
07-01 12:08:47.761  6903  6948 D bte_conf:   vendorId            = 00c4
07-01 12:08:47.761  6903  6948 D bte_conf:   vendorIdSource      = 0001
07-01 12:08:47.761  6903  6948 D bte_conf:   product             = 13a1
07-01 12:08:47.761  6903  6948 D bte_conf:   version             = 1000
07-01 12:08:47.761  6903  6948 D bte_conf:   clientExecutableURL = 
07-01 12:08:47.761  6903  6948 D bte_conf:   serviceDescription  = 
07-01 12:08:47.761  6903  6948 D bte_conf:   documentationURL    = 
07-01 12:08:47.761  6903  6948 D bte_conf: bte_load_did_conf no section named DID2.
07-01 12:08:47.762  6903  6948 I bt-btif : HAL bt_hal_cbacks->adapter_state_changed_cb
07-01 12:08:47.762  6903  6948 E bt-btif : btif_hf_upstreams_evt: wrong handle = 12346 
07-01 12:08:47.762  6903  6948 I bt-btif : HAL bt_op_callbacks->opc_state_cb
07-01 12:08:47.762  6903  6948 D BluetoothOPPServiceJni: opc_state_cb(L140):  opc_state_cb state:0
07-01 12:08:47.762  6903  6945 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-01 12:08:47.762  6903  6945 D BluetoothAdapterProperties: ScanMode =  20
07-01 12:08:47.762  6903  6945 D BluetoothAdapterProperties: State =  11
07-01 12:08:47.763  6903  6945 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-01 12:08:47.763  6903  6945 D BluetoothAdapterProperties: Setting state to 12
07-01 12:08:47.763  6903  6945 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-01 12:08:47.763  6903  6945 D BluetoothAdapterService(864710247): updateAdapterState() - Broadcasting state to 1 receivers.
07-01 12:08:47.764  6903  6945 I BluetoothAdapterState: Entering On State
07-01 12:08:47.764  6903  6945 I BluetoothAdapterState: Entering On State from state = 11
07-01 12:08:47.764  6903  6945 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:47.764  6903  6945 D BluetoothAdapterService(864710247): isQuetModeEnabled() - Enabled = false
07-01 12:08:47.764  6903  6945 D BluetoothAdapterService(864710247): autoConnect() - Initiate auto connection on BT on...
07-01 12:08:47.765  6903  6945 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-01 12:08:47.765   968  2143 I ActivityManager: Process com.lge.qremote (pid 6880) has died
07-01 12:08:47.765  6903  6945 D LGBluetoothServiceAdapter: [BTUI] OnState
07-01 12:08:47.766  6903  6945 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3s-1
07-01 12:08:47.766  6903  6945 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3s-1
07-01 12:08:47.767  6903  6948 D OppService: onOpcStateChange()
07-01 12:08:47.767  6903  6945 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:47.767  6903  6948 I bt-btif : HAL bt_op_callbacks->ops_state_cb
07-01 12:08:47.767  6903  6945 D BluetoothAdapterService(864710247): isQuetModeEnabled() - Enabled = false
07-01 12:08:47.767  6903  6948 D BluetoothOPPServiceJni: ops_state_cb(L223):  ops_state_cb state:0
07-01 12:08:47.767  6903  6948 D OppService: onOpsStateChange() :0
07-01 12:08:47.767  6903  6948 I bt-btif : HAL bt_fts_callbacks->operation_cmpl_cb
07-01 12:08:47.767  6903  6948 D BluetoothFTPServiceJni: operation_cmpl_callback(L192):  oper:3 status:0
07-01 12:08:47.768  6903  6903 D OppService: Recieved MESSAGE_OPC_ENABLE
07-01 12:08:47.768  6903  6945 D BluetoothAdapterService(864710247): autoConnect() - Initiate auto connection on BT on...
07-01 12:08:47.768  6903  6945 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-01 12:08:47.768  6903  6948 I BluetoothFTPService: onFtpServerEnabled: /storage
07-01 12:08:47.769  6903  6948 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-01 12:08:47.769  6903  6903 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-01 12:08:47.769  6903  ,6948 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
07-01 12:08:47.769  6903  6903 D OppService: Recieved MESSAGE_OPS_ENABLE
07-01 12:08:47.771  6903  6948 D BluetoothAdapterProperties: Scan Mode:21
07-01 12:08:47.771  6903  6948 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
07-01 12:08:47.771  6903  6948 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-01 12:08:47.777  6903  6984 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:47.777  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:08:47.777  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:47.777  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:08:47.777  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:08:47.777  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:08:47.777  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:08:47.777  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:08:47.777  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:08:47.778  6903  6984 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:47.779  6689  6689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:08:47.781  6903  6921 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:47.781  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:08:47.781  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:47.781  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:08:47.781  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:08:47.781  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:08:47.781  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:08:47.781  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:08:47.781  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:08:47.782  6903  6921 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:47.783  6689  6689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:08:47.833  7039  7039 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-01 12:08:47.850  6689  6757 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:08:47.850  6689  6757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-01 12:08:47.880   968  1305 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:47.880   968  1305 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,07-01 12:08:47.936  7039  7039 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-01 12:08:47.937  7039  7039 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@277d7396: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-01 12:08:47.938  7039  7039 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-01 12:08:47.939  7039  7039 D AndroidMusic: GMSCore installation verified
07-01 12:08:47.947  7039  7039 I ConfigStore: Config Database version: 1
,07-01 12:08:48.053  7039  7039 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,07-01 12:08:48.058  6903  6921 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:48.058   968  1056 D BluetoothManagerService: Sending off request.
07-01 12:08:48.059  6903  6919 D BluetoothAdapterService(864710247): disable() called...
07-01 12:08:48.059  6903  6919 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:48.059  6903  6945 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-01 12:08:48.059  6903  6945 D BluetoothAdapterProperties: Setting state to 13
,07-01 12:08:48.059  6903  6945 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-01 12:08:48.060  6903  6945 D BluetoothAdapterService(864710247): updateAdapterState() - Broadcasting state to 1 receivers.
07-01 12:08:48.060  6903  6945 D BluetoothAdapterProperties: onBluetoothDisable()
07-01 12:08:48.060  6903  6948 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
07-01 12:08:48.060  6903  6945 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-01 12:08:48.061  6903  6984 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:48.061  6903  6948 D BluetoothAdapterProperties: Scan Mode:20
07-01 12:08:48.061   968  1056 D BluetoothManagerService: Message: 60
07-01 12:08:48.061   968  1056 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-01 12:08:48.061   968  1056 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 10 receivers.
07-01 12:08:48.061  6903  6945 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-01 12:08:48.061  6903  6945 I bt-btif : BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
07-01 12:08:48.061  6903  6945 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
07-01 12:08:48.062  1747  2372 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 12:08:48.062  6903  6945 D bt-btif : btsock_ctrl_hci_cleanup(L202): poll handle:4
07-01 12:08:48.063  6903  6945 D IOP_DB_BT: db_close: nbr users 0
07-01 12:08:48.063  6903  6945 D IOP_DB_BT: db_close: free database
07-01 12:08:48.063  6903  7032 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-01 12:08:48.063  6903  6945 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L300): in, key:Adapter, value:BluezMigrationDone
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L343): out, key:Adapter, value:BluezMigrationDone
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L300): in, key:Adapter, value:Address
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L343): out, key:Adapter, value:Address
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L344): out, value:f8:95:c7:87:85:54
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L300): in, key:Adapter, value:Name
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L343): out, key:Adapter, value:Name
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L344): out, value:G3s-1
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value nam,e:LE_LOCAL_KEY_IRK, value type:binary
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
07-01 12:08:48.063  7039  7039 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L344): out, value:��8�\�婓��n�ScanMode
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L300): in, key:Adapter, value:ScanMode
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L343): out, key:Adapter, value:ScanMode
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L344): out, value:x
07-01 12:08:48.063  6903  6945 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER,
07-01 12:08:48.064  6903  6945 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
07-01 12:08:48.064  6903  6945 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
07-01 12:08:48.064  6903  6945 D btif_config_util: enum_config(L344): out, value:s!WE�(E��00:0F:F6
07-01 12:08:48.064  6903  6945 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
07-01 12:08:48.064  6903  6945 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
07-01 12:08:48.065  6903  6945 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
07-01 12:08:48.065  6903  6945 D btif_config_util: enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
07-01 12:08:48.065  6903  6945 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
,07-01 12:08:48.065  6903  6945 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
07-01 12:08:48.065  6903  6945 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
07-01 12:08:48.065  6903  6945 D btif_config_util: enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
07-01 12:08:48.065  6903  6945 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
07-01 12:08:48.065  6903  6945 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
,07-01 12:08:48.065  6903  6945 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
07-01 12:08:48.065  6903  7032 W bt-obex : Ignore event 10 in state 1
07-01 12:08:48.065  6903  6945 D btif_config_util: enum_config(L344): out, value:BMW,Audi,Parrot,Car,
07-01 12:08:48.065  6903  6945 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
07-01 12:08:48.065  6903  6945 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
07-01 12:08:48.065  6903  7032 W bt-obex : Ignore event 10 in state 1
07-01 12:08:48.065  6903  6945 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L344): out, value:00:0F:F6
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
07-01 12:08:48.066  6903  7032 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
07-01 12:08:48.066  6903  6948 E bt-btif : btif_hf_upstreams_evt: wrong handle = 8265 
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.066  6903  6948 I bt-btif : HAL bt_op_callbacks->ops_state_cb
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
07-01 12:08:48.066  6903  6948 D BluetoothOPPServiceJni: ops_state_cb(L223):  ops_state_cb state:3
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L344): out, value:�
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
07-01 12:08:48.066  6903  6948 D OppService: onOpsStateChange() :3
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L344): out, value:HTC Desire 820
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
,07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
,07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
,07-01 12:08:48.066  6903  6903 D OppService: Recieved MESSAGE_OPS_DISABLE
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
,07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L344): out, value:$
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
07-01 12:08:48.066  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L344): out, value:Galaxy S6-1
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
,07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
,07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
,07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
,07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L344): out, value:�
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
,07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L344): out, value:A5-1
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
,07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.067  6903  6945 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
,07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
,07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
,07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L344): out, value:#
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L344): out, value:Nexus 6
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
,07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
,07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
,07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
,07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
07-01 12:08:48.068  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L344): out, value:�
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
,07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L344): out, value:XT1072
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass,
,07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType,
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
,07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
,07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
07-01 12:08:48.069  6689  6689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:08:48.069  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:48.069  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:08:48.069  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:08:48.069  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:08:48.069  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:08:48.069  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:08:48.069  6689  6689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
,07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L344): out, value:a
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L344): out, value:S5-1
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
07-01 12:08:48.069  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
,07-01 12:08:48.070  6903  6945 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:JustWorks
07-01 12:08:48.070  6903  6945 D btif_config_util: enum_config(L344): out, value:a
07-01 12:08:48.072  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
07-01 12:08:48.072  6903  6945 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
07-01 12:08:48.072  6903  6945 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Manufacturer
07-01 12:08:48.072  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Manufacturer, value type:int
07-01 12:08:48.072  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
07-01 12:08:48.072  6903  6945 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
,07-01 12:08:48.072  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
07-01 12:08:48.072  6903  6945 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
07-01 12:08:48.072  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
07-01 12:08:48.072  6903  6945 D btif_config_util: enum_config(L344): out, value:A
07-01 12:08:48.072  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
07-01 12:08:48.072  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
07-01 12:08:48.072  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevClass, value type:int
,07-01 12:08:48.072  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
07-01 12:08:48.072  6903  6945 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
07-01 12:08:48.072  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevType
07-01 12:08:48.072  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.072  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
07-01 12:08:48.072  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:GlobalTrust, value type:int
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
,07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Service
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Manufacturer, value type:int
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpVer
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpVer
,07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpSubVer
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpSubVer
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L344): out, value:	a
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Name
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Name, value type:string
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevClass
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevClass
,07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevType
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevType
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:JustWorks
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:JustWorks
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.073  6805  6827 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:GlobalTrust, value type:int
,07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:GlobalTrust
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Service
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:Manufacturer
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:Manufacturer
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpVer
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpVer
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpSubVer, value type:int
,07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L344): out, value:�
07-01 12:08:48.073  6903  6945 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:Name
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Name, value type:string
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:Name
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevClass
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevType
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevType, value type:int
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L344): out, value:
,07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:JustWorks, value type:int
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:JustWorks
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:GlobalTrust
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:GlobalTrust
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:Service
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:Service
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
,07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpVer, value type:int
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpVer
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Name
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Name, value type:string
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L344): out, value:XT1039
,07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevType
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevType, value type:int
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevType
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:JustWorks
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:JustWorks, value type:int
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:JustWorks
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
,07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Service
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Service, value type:string
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
07-01 12:08:48.074  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Manufacturer
07-01 12:08:48.075  6903  6945 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpVer
07-01 12:08:48.075  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpVer
07-01 12:08:48.075  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.075  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpSubVer, value type:int
,07-01 12:08:48.075  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpSubVer
07-01 12:08:48.075  6903  6945 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Name
07-01 12:08:48.075  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Name
07-01 12:08:48.075  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevClass, value type:int
07-01 12:08:48.075  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevClass
07-01 12:08:48.075  6903  6945 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevType
07-01 12:08:48.075  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevType
07-01 12:08:48.075  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.075  6903  6945 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:JustWorks
,07-01 12:08:48.075  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:JustWorks
07-01 12:08:48.075  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.075  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:GlobalTrust, value type:int
07-01 12:08:48.075  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.075  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Service, value type:string
07-01 12:08:48.075  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Service
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Manufacturer
,07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Manufacturer, value type:int
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Manufacturer
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpVer
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpVer, value type:int
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpVer
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpSubVer
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpSubVer, value type:int
,07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpSubVer
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L344): out, value:�
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Name
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Name, value type:string
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Name
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L344): out, value:HTC One_M8
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevClass
,07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevClass, value type:int
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevClass
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevType
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevType, value type:int
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevType
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L344): out, value:
,07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Service
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Service, value type:string
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Service
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 00006675-7475-7265-6469-616c62756d70 fa87c0d0-afac-11de-8a39-0800200c9a66 ,
,07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:JustWorks
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:JustWorks, value type:int
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:JustWorks
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:GlobalTrust
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Manufacturer
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Manufacturer
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L344): out, value:
,07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpVer, value type:int
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpVer
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpSubVer
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpSubVer
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Name
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Name, value type:string
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L344): out, value:Note4-1
07-01 12:08:48.076  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevClass, value type:int
,07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevClass
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevType
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevType
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:JustWorks
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:JustWorks
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:GlobalTrust
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:GlobalTrust
,07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Service, value type:string
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Manufacturer, value type:int
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpVer, value type:int
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpVer
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpSubVer
,07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpSubVer, value type:int
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpSubVer
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L300): in, key:80:01:84:8a:b3:68, value:Name
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Name, value type:string
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevClass, value type:int
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevClass
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevType
,07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevType
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L300): in, key:80:01:84:8a:b3:68, value:JustWorks
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:JustWorks
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:GlobalTrust
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L300): in, key:80:01:84:8a:b3:68, value:Service
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Service, value type:string
,07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Manufacturer, value type:int
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L343): out, key:58:3f:54:73:64:c0, value:Manufacturer
07-01 12:08:48.077  6903  6945 D btif_config_util: enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpVer
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpVer
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpSubVer
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpSubVer
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L300): in, key:58:3f:54:73:64:c0, value:Name
,07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L343): out, key:58:3f:54:73:64:c0, value:Name
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevClass
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevClass, value type:int
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevType, value type:int
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevType
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L300): in, key:58:3f:54:73:64:c0, value:JustWorks
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:GlobalTrust, value type:int
,07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevClass
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevType
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevType
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:JustWorks, value type:int
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:GlobalTrust, value type:int
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:b1:66, value:GlobalTrust
,07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Service
07-01 12:08:48.078  6903  6945 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Service
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpVer, value type:int
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpVer
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpSubVer
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpSubVer
,07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Name
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Name
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevClass
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevType
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevType
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L300): in, key:90:e7:c4:f6:69:77, value:JustWorks
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L343): out, key:90:e7:c4:f6:69:77, value:JustWorks
,07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L300): in, key:90:e7:c4:f6:69:77, value:GlobalTrust
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:GlobalTrust, value type:int
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L343): out, key:90:e7:c4:f6:69:77, value:GlobalTrust
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Service
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Service
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Manufacturer
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L344): out, value:
,07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpVer
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpVer, value type:int
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpSubVer
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpSubVer, value type:int
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L344): out, value:A
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Name
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Name
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevClass, value type:int
07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L344): out, value:Z
,07-01 12:08:48.079  6903  6945 D btif_config_util: enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevType
07-01 12:08:48.080  6903  6945 D btif_config_util: enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevType
07-01 12:08:48.080  6903  6945 D btif_config_util: enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:JustWorks
07-01 12:08:48.080  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:GlobalTrust, value type:int
07-01 12:08:48.080  6903  6945 D btif_config_util: enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Service
07-01 12:08:48.080  6903  6945 D btif_config_util: enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Service
07-01 12:08:48.081  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.081  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Manufacturer, value type:int
07-01 12:08:48.081  6903  6945 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:Manufacturer
,07-01 12:08:48.081  6903  6945 D btif_config_util: enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpVer
07-01 12:08:48.081  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpVer, value type:int
07-01 12:08:48.081  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.081  6903  6945 D btif_config_util: enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpSubVer
07-01 12:08:48.081  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpSubVer, value type:int
07-01 12:08:48.081  6903  6945 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpSubVer
07-01 12:08:48.081  6903  6945 D btif_config_util: enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevClass
07-01 12:08:48.081  6903  6945 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevClass
,07-01 12:08:48.081  6903  6945 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:48.081  6903  6945 D btif_config_util: enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevType
07-01 12:08:48.081  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevType, value type:int
07-01 12:08:48.081  6903  6945 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevType
07-01 12:08:48.081  6903  6945 D btif_config_util: enum_config(L300): in, key:14:b4:84:21:3b:49, value:JustWorks
07-01 12:08:48.081  6903  6945 D btif_config_util: enum_config(L300): in, key:14:b4:84:21:3b:49, value:GlobalTrust
07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:GlobalTrust
07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L300): in, key:14:b4:84:21:3b:49, value:Service
,07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:Service
07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:58:1b:00:00:20:00, value name:DevType, value type:int
07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L343): out, key:58:1b:00:00:20:00, value:DevType
07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L300): in, key:00:00:00:00:08:00, value:DevClass
07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L343): out, key:00:00:00:00:08:00, value:DevClass
07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L300): in, key:00:00:00:00:08:00, value:DevType
,07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevType, value type:int
07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L343): out, key:00:00:00:00:08:00, value:DevType
07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L300): in, key:08:00:00:00:67:73, value:DevType
07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:08:00:00:00:67:73, value name:DevType, value type:int
07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Manufacturer, value type:int
07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.082  6903  6945 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpVer
,07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpVer, value type:int
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpVer
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpSubVer
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpSubVer, value type:int
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevType
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevType
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:JustWorks
,07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:JustWorks
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:GlobalTrust
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:GlobalTrust
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Manufacturer, value type:int
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L343): out, key:00:00:00:00:5a:ad, value:Manufacturer
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpVer
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpVer
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpSubVer
,07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpSubVer
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L344): out, value:�
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Name, value type:string
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L343): out, key:00:00:00:00:5a:ad, value:Name
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L344): out, value:A3-1
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevClass
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevClass, value type:int
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevClass
,07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L344): out, value:Z
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevType
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevType, value type:int
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevType
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L300): in, key:00:00:00:00:5a:ad, value:JustWorks
07-01 12:08:48.083  6903  6945 D btif_config_util: enum_config(L343): out, key:00:00:00:00:5a:ad, value:JustWorks
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L344): out, value:
,07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L300): in, key:00:00:00:00:5a:ad, value:GlobalTrust
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:GlobalTrust, value type:int
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L343): out, key:00:00:00:00:5a:ad, value:GlobalTrust
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L300): in, key:08:00:00:00:67:53, value:DevClass
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:08:00:00:00:67:53, value name:DevClass, value type:int
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:08:00:00:00:67:53, value name:DevType, value type:int
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:Name
,07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:Name, value type:string
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:Name
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevClass
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:DevClass
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L344): out, value:`��
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevType, value type:int
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevClass, value type:int,
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevClass
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L344): out, value:���
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L300): in, key:a0:01:c0:b4:bc:d6, value:DevType
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevType, value type:int
,07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevType
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L300): in, key:94:16:79:a0:e3:01, value:DevClass
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:94:16:79:a0:e3:01, value name:DevClass, value type:int
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevClass
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L300): in, key:94:16:79:a0:e3:01, value:DevType
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevType
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L300): in, key:00:00:00:00:41:9e, value:Name
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L343): out, key:00:00:00:00:41:9e, value:Name
,07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L344): out, value:4g�
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L300): in, key:00:00:00:00:41:9e, value:DevClass
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L343): out, key:00:00:00:00:41:9e, value:DevClass
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevType, value type:int
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:Name, value type:string
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:Name
07-01 12:08:48.084  6903  6945 D btif_config_util: enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevClass
,07-01 12:08:48.085  6903  6945 D btif_config_util: enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevClass
07-01 12:08:48.085  6903  6945 D btif_config_util: enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevType
07-01 12:08:48.085  6903  6945 D btif_config_util: enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevType, value type:int
07-01 12:08:48.085  6903  6945 D btif_config_util: enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevType
07-01 12:08:48.085  6903  6945 D btif_config_util: enum_config(L344): out, value:
07-01 12:08:48.093  1747  1763 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 12:08:48.095  6805  6824 D BluetoothMap: onBluetoothStateChange: up=true
07-01 12:08:48.097  6805  6827 D BluetoothPan: onBluetoothStateChange on: true
07-01 12:08:48.097  6805  6827 D BluetoothPan: onBluetoothStateChange call bindService
07-01 12:08:48.099   968  1056 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-01 12:08:48.100  1747  2366 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 12:08:48.100   968   968 D BluetoothA2dp: Proxy object connected
07-01 12:08:48.104   968  1056 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-01 12:08:48.104   968  1056 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-01 12:08:48.106  1799  1799 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:48.107  1799  1988 D LGBluetoothAPIService: Message: 1
07-01 12:08:48.107  1799  1988 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-01 12:08:48.107   968  1056 D BluetoothManagerService: Message: 60
,07-01 12:08:48.107   968  1056 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-01 12:08:48.107   968  1056 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
07-01 12:08:48.120  6903  6984 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:48.123  6903  7075 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:48.124  6903  6984 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:48.126  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
07-01 12:08:48.126  1370  1370 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,07-01 12:08:48.136  1747  1747 D BluetoothHeadset: Proxy object connected
07-01 12:08:48.136  1747  1747 D BluetoothHeadset: Proxy object connected
07-01 12:08:48.136  1747  1747 D BluetoothHeadset: Proxy object connected
07-01 12:08:48.138   968   968 D BluetoothHeadset: Proxy object connected
07-01 12:08:48.139  6903  6921 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:48.142   968  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2c80d87 type 2 when 177116 com.google.android.gms} when 177116
07-01 12:08:48.143  1799  1799 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:48.145  1799  1988 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,07-01 12:08:48.147  6903  6984 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:48.147   968   968 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-01 12:08:48.147   968  1056 D BluetoothManagerService: Message: 40
07-01 12:08:48.147   968  1056 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-01 12:08:48.149  6903  6903 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:48.149  6903  7075 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:48.151  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
07-01 12:08:48.151  1370  1370 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
07-01 12:08:48.157  6903  6903 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:48.157  6903  6903 D BluetoothMapService: STATE_ON
,07-01 12:08:48.164  6903  6903 D LGBluetoothAPIServer: [BTUI] onCreate()
07-01 12:08:48.164  6903  6903 D LGBluetoothAPIServer: [BTUI] onBind()
07-01 12:08:48.165  6903  6903 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:48.165  1799  1799 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-01 12:08:48.165  6903  6903 D BluetoothMapService: STATE_TURNING_OFF
07-01 12:08:48.168  1799  1988 D LGBluetoothAPIService: Message: 100
07-01 12:08:48.168  1799  1988 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-01 12:08:48.184  6903  6919 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
,07-01 12:08:48.185  6903  6984 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:48.186  6805  6805 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-01 12:08:48.188  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-01 12:08:48.191  6805  6805 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
07-01 12:08:48.191  6805  6805 D BluetoothMap: Proxy object connected
07-01 12:08:48.191  6805  6805 D MapProfile: Bluetooth service connected
07-01 12:08:48.191  6805  6805 D BluetoothMap: getConnectedDevices()
07-01 12:08:48.192  6903  7075 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:48.192  6805  6805 D BluetoothMap: Bluetooth is Not enabled
07-01 12:08:48.193  6805  6805 D BluetoothPan: BluetoothPAN Proxy object connected
07-01 12:08:48.193  6805  6805 D PanProfile: Bluetooth service connected
07-01 12:08:48.193  6903  6921 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:48.194  6805  6805 D BluetoothInputDevice: Proxy object connected
07-01 12:08:48.194  6805  6805 D HidProfile: Bluetooth service connected
07-01 12:08:48.195  6903  6919 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:48.198  6805  6805 D DockEventReceiver: finishStartingService: stopping service
,07-01 12:08:48.213  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:48.213  6903  6903 V BluetoothPbapService: Pbap Service onCreate
07-01 12:08:48.214  6903  6903 V BluetoothPbapService: Starting PBAP service
,07-01 12:08:48.216  6903  6903 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:48.217  6903  6903 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-01 12:08:48.218  6903  6903 V BluetoothPbapService: Pbap Service onBind
07-01 12:08:48.220  6903  6903 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:48.220  6903  6903 V BluetoothPbapService: state: 13
07-01 12:08:48.221  6903  6903 V BluetoothPbapService: Pbap Service closeService in
07-01 12:08:48.221  6805  6805 D BluetoothPbap: Proxy object connected
07-01 12:08:48.222  6805  6805 D PbapServerProfile: Bluetooth service connected
07-01 12:08:48.222  6903  6903 V BluetoothPbapService: successfully stopped pbap service
07-01 12:08:48.222  6903  6903 V BluetoothPbapService: Pbap Service closeService out
07-01 12:08:48.222  6903  6903 V BluetoothMapService: Handler(): got msg=4
07-01 12:08:48.222  6903  6903 D BluetoothMapService: MAP Service closeService in
07-01 12:08:48.222  6903  6903 D BluetoothMapMasInstance: MAP Service shutdown
07-01 12:08:48.222  6903  6903 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-01 12:08:48.223  6903  6903 V BluetoothMapService: MAP Service closeService out
07-01 12:08:48.223  6903  6903 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-01 12:08:48.223  6903  6903 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:48.223  6903  6903 V BluetoothPbapReceiver: ***********state = 12
07-01 12:08:48.225  6903  6903 V BluetoothPbapService: Pbap Service onDestroy
07-01 12:08:48.225  6903  6903 V BluetoothPbapService: Pbap Service closeService in
07-01 12:08:48.225  6903  6903 V BluetoothPbapService: Pbap Service closeService out
07-01 12:08:48.225  6903  6903 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-01 12:08:48.230  6805  6805 D BluetoothPbap: Proxy object disconnected
07-01 12:08:48.230  6805  6805 D PbapServerProfile: Bluetooth service disconnected
,07-01 12:08:48.235  7039  7053 I art     : CheckpointMarkThreadRoots callback created = 0xafc2d3f0
07-01 12:08:48.244  6805  6805 D BluetoothPermissionRequest: onReceive
,07-01 12:08:48.250  6805  6805 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,07-01 12:08:48.288  7039  7053 I art     : CheckpointMarkThreadRoots callback created = 0xafc2d3c0
,07-01 12:08:48.295   968  1861 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7082 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
07-01 12:08:48.317   309   309 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 22.541ms
,07-01 12:08:48.334  6903  6903 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,07-01 12:08:48.340   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 21.905ms
07-01 12:08:48.350  6903  6903 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,07-01 12:08:48.362   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 21.827ms
,07-01 12:08:48.366  6903  6903 V BluetoothSapReceiver: [BTUI] checkServiceStart
,07-01 12:08:48.368  6903  6903 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:48.377  2397  2397 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-01 12:08:48.384  7039  7039 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,07-01 12:08:48.392  2397  7103 D EasyUnlockInitService: Handling intent for initializer IntentService.
07-01 12:08:48.396  2397  2397 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-01 12:08:48.404  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-01 12:08:48.412  6903  6903 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-01 12:08:48.412  6903  6903 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:48.413  6903  6903 V BluetoothPbapReceiver: ***********state = 13
07-01 12:08:48.414  6903  6903 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
07-01 12:08:48.416  6805  6805 D DockEventReceiver: finishStartingService: stopping service
07-01 12:08:48.418  7039  7039 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
07-01 12:08:48.418  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:48.418  6903  6903 V BluetoothPbapService: Pbap Service onCreate
07-01 12:08:48.418  6903  6903 V BluetoothPbapService: Starting PBAP service
,07-01 12:08:48.419  6903  6903 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:48.419  6903  6903 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-01 12:08:48.419  6903  6903 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:48.419  6903  6903 V BluetoothPbapService: state: 13
07-01 12:08:48.419  6903  6903 V BluetoothPbapService: Pbap Service closeService in
07-01 12:08:48.422  6903  6903 V BluetoothPbapService: successfully stopped pbap service
07-01 12:08:48.422  6903  6903 V BluetoothPbapService: Pbap Service closeService out
07-01 12:08:48.422  6903  6903 V BluetoothPbapService: Pbap Service onDestroy
07-01 12:08:48.422  6903  6903 V BluetoothPbapService: Pbap Service closeService in
07-01 12:08:48.422  6903  6903 V BluetoothPbapService: Pbap Service closeService out
07-01 12:08:48.422  6903  6903 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-01 12:08:48.428  2397  7103 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
07-01 12:08:48.434  6805  6805 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-01 12:08:48.434  6805  6805 I NotificationManager: com.android.settings: cancel(17301632) by com.android.settings
,07-01 12:08:48.436  6805  6805 I NotificationManager: com.android.settings: cancel(-1000001) by com.android.settings
07-01 12:08:48.438  6805  6805 I NotificationManager: com.android.settings: cancel(-1000011) by com.android.settings
07-01 12:08:48.438  6805  6805 I NotificationManager: com.android.settings: cancel(-1000021) by com.android.settings
07-01 12:08:48.438  6805  6805 I NotificationManager: com.android.settings: cancel(-1000031) by com.android.settings
07-01 12:08:48.439  6805  6805 I NotificationManager: com.android.settings: cancel(-1000041) by com.android.settings
07-01 12:08:48.442  6805  6805 D BluetoothPermissionRequest: onReceive
07-01 12:08:48.442  6805  6805 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-01 12:08:48.442  6805  6805 I NotificationManager: com.android.settings: cancel(17301632) by com.android.settings
07-01 12:08:48.442  6805  6805 I NotificationManager: com.android.settings: cancel(-1000001) by com.android.settings
07-01 12:08:48.443  6805  6805 I NotificationManager: com.android.settings: cancel(-1000011) by com.android.settings
07-01 12:08:48.443  6805  6805 I NotificationManager: com.android.settings: cancel(-1000021) by com.android.settings
07-01 12:08:48.444  6805  6805 I NotificationManager: com.android.settings: cancel(-1000031) by com.android.settings
07-01 12:08:48.444  6805  6805 I NotificationManager: com.android.settings: cancel(-1000041) by com.android.settings
07-01 12:08:48.445  7082  7082 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 12:08:48.445  7082  7082 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-01 12:08:48.452  6903  6903 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
07-01 12:08:48.452  6903  6903 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
07-01 12:08:48.452  6903  6903 I NotificationManager: com.android.bluetooth: cancel(-1) by com.android.bluetooth
07-01 12:08:48.453  7082  7082 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-01 12:08:48.453  6903  6903 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
07-01 12:08:48.453  6903  6903 I NotificationManager: com.android.bluetooth: cancel(-1) by com.android.bluetooth
07-01 12:08:48.459  6903  6903 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-01 12:08:48.460  6903  6903 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:08:48.468  2397  2397 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-01 12:08:48.472  2397  2397 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-01 12:08:48.506  7039  7058 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
,07-01 12:08:48.753  7082  7082 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,07-01 12:08:48.780  7082  7082 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,07-01 12:08:48.851  6689  6757 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:08:48.851  6689  6757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 12:08:48.851  6689  6757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:08:48.851  6689  6757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:08:48.851  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5ba5e82 removed from the list
07-01 12:08:48.852  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 12:08:48.853  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c6b0dd0 added. We now have 2 listener(s)
07-01 12:08:48.853  6689  6757 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 12:08:48.857  6689  6757 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:08:48.857  6689  6757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 12:08:48.857  6689  6757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:08:48.857  6689  6757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:08:48.857  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c6b0dd0 removed from the list
07-01 12:08:48.858  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 12:08:48.858  6689  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36aa71c9 added. We now have 2 listener(s)
07-01 12:08:48.858  6689  6757 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 12:08:48.859   968   986 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 12:08:48.859   968   986 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@37402d8c mBinding = false
07-01 12:08:48.860   968  1056 D BluetoothManagerService: Message: 2
07-01 12:08:48.860   968  1056 D BluetoothManagerService: Sending off request.
07-01 12:08:48.860  6903  7075 D BluetoothAdapterService(864710247): disable() called...
07-01 12:08:48.860  6903  7075 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:48.861  6903  7075 D BluetoothAdapterService: disable() : BT State is not STATE_ON. Can't disable BT
07-01 12:08:48.861   968  1056 E BluetoothManagerService: IBluetooth.disable() returned false
07-01 12:08:48.864  6689  6757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:08:48.864   968  1344 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 12:08:48.864   968  1344 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@37402d8c mBinding = false
,07-01 12:08:48.872   968  1056 D BluetoothManagerService: Message: 1
,07-01 12:08:48.872   968  1056 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@37402d8c
07-01 12:08:48.875   968   968 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 12:08:48.875   968   968 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 12:08:48.875   968   968 D Ulp_jni : JNI:system_update. Event-4
07-01 12:08:48.876  6903  7075 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:48.876  6903  7075 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
07-01 12:08:48.876   968  1056 E BluetoothManagerService: IBluetooth.enable() returned false
,07-01 12:08:49.003  7082  7082 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-01 12:08:49.021  6966  6966 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,07-01 12:08:49.022  6966  6966 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-01 12:08:49.023  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-01 12:08:49.026  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-01 12:08:49.036  6966  7118 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-01 12:08:49.041  6966  7119 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-01 12:08:49.041  6966  7119 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-01 12:08:49.069  6903  7032 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 12:08:49.069  6903  7032 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 12:08:49.069  6903  7032 W bt-btif : ag scb idx 1 not allocated
07-01 12:08:49.069  6903  7032 E bt-btif : BTA AG is already disabled, ignoring ...
07-01 12:08:49.069  6903  7032 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 12:08:49.069  6903  7032 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 12:08:49.069  6903  7032 W bt-btif : ag scb idx 1 not allocated
07-01 12:08:49.069  6903  7032 E bt-btif : BTA AG is already disabled, ignoring ...
07-01 12:08:49.069  6903  7032 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-01 12:08:49.069  6903  7032 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-01 12:08:49.070  6903  7037 W bt_userial: select_read return size <=0:0, exiting userial_read_thread
07-01 12:08:49.070  6903  7034 D bt_hwcfg: hw_epilog_process
07-01 12:08:49.071  6903  6948 I bt_userial_vendor: device fd = 67 close
,07-01 12:08:49.080   968  3633 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7121 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
07-01 12:08:49.088  6903  6948 E bt_vendor: [BTUI] Proto is enabled. Set Proto disable!!
,07-01 12:08:49.175  7082  7082 I HubEmail: JNI_OnLoad()
,07-01 12:08:49.175  7082  7082 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-01 12:08:49.175  7082  7082 I HubEmail: registerNatives()
07-01 12:08:49.175  7082  7082 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-01 12:08:49.175  7082  7082 I HubEmail: registerNativeMethods()
07-01 12:08:49.175  7082  7082 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,07-01 12:08:49.176  7082  7082 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
07-01 12:08:49.182  7082  7138 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:49.194  6903  6948 I GKI_LINUX: GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 100, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
07-01 12:08:49.194  6903  7032 W bt-btu  : btu_check_timer_queues_emtpy(btu_cb): timer_queue.p_first: 0xa0785264, timer_queue.p_last: 0xa0785264, last_ticks: 0, p_first->p_cback: 0x0, p_first->event: 0x32, p_first->in_use: 1
07-01 12:08:49.194  6903  7032 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,07-01 12:08:49.195  6903  6948 I GKI_LINUX: GKI_destroy_task(): task [BTU] terminated
07-01 12:08:49.196  6903  6948 I bt-btif : HAL bt_hal_cbacks->adapter_state_changed_cb
07-01 12:08:49.196  6903  6945 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-01 12:08:49.196  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.196  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-01 12:08:49.196  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.196  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-01 12:08:49.197  6903  6945 D BtSettings.ProfileConfig: Unable to read settings
07-01 12:08:49.197  6903  6945 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-01 12:08:49.197  6903  6945 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
07-01 12:08:49.197  6903  6945 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
07-01 12:08:49.197  6903  6945 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
07-01 12:08:49.197  6903  6945 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
07-01 12:08:49.197  6903  6945 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
07-01 12:08:49.197  6903  6945 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
07-01 12:08:49.197  6903  6945 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
07-01 12:08:49.197  6903  6945 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
07-01 12:08:49.197  6903  6945 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:49.197  6903  6945 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
07-01 12:08:49.197  6903  6945 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:08:49.197  6903  6945 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
07-01 12:08:49.197  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
07-01 12:08:49.198  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.198  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-01 12:08:49.198  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.198  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-01 12:08:49.198  6903  6945 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
07-01 12:08:49.198  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
07-01 12:08:49.199  6903  6903 D HeadsetService: Received stop request...Stopping profile...
07-01 12:08:49.199  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.199  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-01 12:08:49.199  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.199  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 12:08:49.199  6903  6945 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-01 12:08:49.199  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
07-01 12:08:49.200  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.200  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-01 12:08:49.200  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.200  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-01 12:08:49.200  6903  6945 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.Hea,lthService
07-01 12:08:49.200  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
07-01 12:08:49.201  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.201  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-01 12:08:49.201  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.201  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-01 12:08:49.201  6903  6945 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-01 12:08:49.201  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
07-01 12:08:49.201  6903  6903 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-01 12:08:49.202  6903  6903 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-01 12:08:49.202  6903  6987 D HeadsetStateMachine: Exit Disconnected: -1
07-01 12:08:49.202  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:49.202   968   968 D BluetoothHeadset: Proxy object disconnected
07-01 12:08:49.202   968   968 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-01 12:08:49.203  1747  1747 D BluetoothHeadset: Proxy object disconnected
07-01 12:08:49.203  1747  1747 D BluetoothHeadset: Proxy object disconnected
07-01 12:08:49.203  1747  1747 D BluetoothHeadset: Proxy object disconnected
07-01 12:08:49.203  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.203  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
07-01 12:08:49.203  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.203  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-01 12:08:49.203  6903  6945 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
07-01 12:08:49.203  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
07-01 12:08:49.204  6903  6903 D A2dpService: Received stop request...Stopping profile...
07-01 12:08:49.204  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.204  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
07-01 12:08:49.204  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.204  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 12:08:49.204  6903  6997 D A2dpStateMachine: Exit Disconnected: -1
07-01 12:08:49.204  6903  6945 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
07-01 12:08:49.204  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
07-01 12:08:49.205  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.205  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
07-01 12:08:49.206  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.206  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 12:08:49.206  6903  6945 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-01 12:08:49.206  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService,
07-01 12:08:49.206  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.207  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
07-01 12:08:49.207  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.207  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
07-01 12:08:49.207  6903  6945 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.ftp.FTPService,
07-01 12:08:49.207  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
07-01 12:08:49.208  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.208  6903  6945 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
07-01 12:08:49.208  6903  6945 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-01 12:08:49.208  6903  6945 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.208  6903  6903 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
,07-01 12:08:49.208  6903  6945 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.opp.OppService
07-01 12:08:49.208  6903  6903 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-01 12:08:49.208  6903  6945 D BluetoothAdapterService(864710247): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
07-01 12:08:49.208  6903  6903 D LGBluetoothPowerControlManager: [BTUI] terminate
07-01 12:08:49.209   968  1056 D BluetoothManagerService: Message: 31
,07-01 12:08:49.210  6903  6945 D BluetoothAdapterState: Stopping profile services that were post enabled
07-01 12:08:49.210  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
,07-01 12:08:49.212   968   968 D BluetoothA2dp: Proxy object disconnected
07-01 12:08:49.212   968   968 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,07-01 12:08:49.213  6903  6903 D HidService: Received stop request...Stopping profile...
07-01 12:08:49.213  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:49.214  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:49.214  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:49.214  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
07-01 12:08:49.214  6903  6903 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:49.214  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:49.214  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:49.214  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:49.214  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
07-01 12:08:49.214  6903  6903 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.214  6903  6903 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.214  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.214  6805  6805 D BluetoothInputDevice: Proxy object disconnected
07-01 12:08:49.214  6805  6805 D HidProfile: Bluetooth service disconnected
07-01 12:08:49.215  6903  6903 D HealthService: Received stop request...Stopping profile...
07-01 12:08:49.217  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:49.219  6903  6903 D HeadsetStateMachine: Unbinding service...
07-01 12:08:49.219  6903  6903 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-01 12:08:49.219  6903  6903 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-01 12:08:49.220  6903  6903 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-01 12:08:49.220  6903  6903 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-01 12:08:49.220  6903  6903 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-01 12:08:49.220  6903  6903 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-01 12:08:49.220  6903  6903 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-01 12:08:49.221  6903  6903 D PanService: Received stop request...Stopping profile...
07-01 12:08:49.221  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:49.222  6903  6903 D BtGatt.DebugUtils: handleDebugAction() action=null
07-01 12:08:49.222  6805  6805 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-01 12:08:49.222  6805  6805 D PanProfile: Bluetooth service disconnected
07-01 12:08:49.223  6903  6903 D BtGatt.GattService: Received stop request...Stopping profile...
07-01 12:08:49.223  6903  6903 D BtGatt.GattService: stop()
07-01 12:08:49.223  6903  6903 D BtGatt.AdvertiseManager: advertise clients cleared
07-01 12:08:49.224  6903  6903 D LGBluetoothGattAdapter: [BTUI] LGBluetoothGattAdapter cleanup
07-01 12:08:49.224  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
,07-01 12:08:49.225  6903  6903 D BluetoothMapService: Received stop request...Stopping profile...
07-01 12:08:49.225  6903  6903 D BluetoothMapService: stop()
07-01 12:08:49.226  6903  6903 D BluetoothMapEmailAppObserver: deinitObservers()
07-01 12:08:49.226  6903  6903 D BluetoothMapEmailAppObserver: removeReceiver()
07-01 12:08:49.226  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:49.227  6805  6805 D BluetoothMap: Proxy object disconnected
07-01 12:08:49.227  6805  6805 D MapProfile: Bluetooth service disconnected
07-01 12:08:49.228  6903  6903 D SapService: Received stop request...Stopping profile...
07-01 12:08:49.228  6903  6903 D SapService: Stopping Bluetooth SapService
07-01 12:08:49.228  6903  6903 D LGBluetoothSapAdapter: [BTUI] LGBluetoothSapAdapter cleanup
07-01 12:08:49.228  6903  6903 D LGBluetoothSapManager: [BTUI] terminateSapManager
07-01 12:08:49.229  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:49.230  1747  1747 D LgeBluetoothSimManager: [BTUI] SAP_DISABLE_EVT
07-01 12:08:49.231  6903  6903 D **BluetoothFTPService: Received stop request...Stopping profile...
07-01 12:08:49.231  6903  6903 D **BluetoothFTPService: Stopping Bluetooth FTP Service
07-01 12:08:49.231  6903  6903 V BluetoothFTPServiceJni: closeFtpServerNative
07-01 12:08:49.231  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:49.232  6903  6903 D **OppService: Received stop request...Stopping profile...
07-01 12:08:49.232  6903  6903 D OppService: Stopping Bluetooth OppService
07-01 12:08:49.232  6903  6903 D OppService: cleanup OPP Service
07-01 12:08:49.232  6903  6903 W BluetoothOPPServiceJni: Cleaning up Bluetooth Opp Interface...
07-01 12:08:49.232  6903  6903 W BluetoothOPPServiceJni: Cleaning up Bluetooth OPP callback object
07-01 12:08:49.233  6903  6903 D OppService: remove callbacks and handler
07-01 12:08:49.233  6903  6903 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-01 12:08:49.233  6903  6903 D OppService: cleanup done
07-01 12:08:49.233  6903  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@338a6e67
07-01 12:08:49.234  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:49.234  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:49.234  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
07-01 12:08:49.234  6903  6903 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:49.234  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:49.234  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:49.234  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:49.234  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
07-01 12:08:49.235  6903  6903 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.235  6903  6903 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.235  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
,07-01 12:08:49.235  6903  6903 I BluetoothA2dpServiceJni: cleanupNative
07-01 12:08:49.235  6903  6903 I GKI_LINUX: GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
07-01 12:08:49.235  6903  7066 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-01 12:08:49.236  6903  6903 I GKI_LINUX: GKI_destroy_task(): task [A2DP-MEDIA] terminated
07-01 12:08:49.236  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:49.236  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:49.236  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
07-01 12:08:49.236  6903  6903 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:49.236  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:49.236  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:49.236  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:49.236  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
07-01 12:08:49.236  6903  6903 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.237  6903  6903 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.237  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.237  6903  6903 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-01 12:08:49.237  6903  6903 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-01 12:08:49.237  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:49.237  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:49.237  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
07-01 12:08:49.237  6903  6903 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:49.237  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:49.237  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:49.237  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:49.237  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
07-01 12:08:49.237  6903  6903 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.237  6903  6903 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.237  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.237  6903  6903 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-01 12:08:49.239  6903  6903 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-01 12:08:49.239  6903  6903 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-01 12:08:49.239  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:49.239  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:49.239  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
07-01 12:08:49.239  6903  6903 D BluetoothAdapterState: i,sTurningOnRadio()=false
07-01 12:08:49.239  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:49.239  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:49.239  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:49.239  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
07-01 12:08:49.239  6903  6903 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.240  6903  6903 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.240  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.240  6903  6903 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-01 12:08:49.240  6903  6903 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-01 12:08:49.241  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:49.241  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:49.241  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
07-01 12:08:49.241  6903  6903 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:49.241  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:49.241  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:49.241  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
,07-01 12:08:49.241  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
07-01 12:08:49.241  6903  6903 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
,07-01 12:08:49.241  6903  6903 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.241  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.241  6903  6903 V BluetoothMapService: Handler(): got msg=4
07-01 12:08:49.241  6903  6903 D BluetoothMapService: MAP Service closeService in
,07-01 12:08:49.241  6903  6903 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-01 12:08:49.241  6903  6903 V BluetoothMapService: MAP Service closeService out
07-01 12:08:49.242  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:49.242  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,07-01 12:08:49.242  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
07-01 12:08:49.242  6903  6903 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:49.242  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
,07-01 12:08:49.242  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:49.242  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:49.242  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
07-01 12:08:49.242  6903  6903 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.242  6903  6903 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.242  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService,
07-01 12:08:49.242  6903  6903 D BluetoothMapService: cleanup()
07-01 12:08:49.242  6903  6903 D BluetoothMapService: MAP Service closeService in
07-01 12:08:49.242  6903  6903 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-01 12:08:49.242  6903  6903 V BluetoothMapService: MAP Service closeService out
,07-01 12:08:49.242  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:49.242  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:49.242  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
07-01 12:08:49.242  6903  6903 D BluetoothAdapterState: isTurningOnRadio()=false
,07-01 12:08:49.242  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:49.242  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:49.242  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:49.242  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
07-01 12:08:49.243  6903  6903 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
,07-01 12:08:49.243  6903  6903 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.243  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.243  6903  6903 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
07-01 12:08:49.243  6903  6903 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
07-01 12:08:49.243  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:49.243  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,07-01 12:08:49.243  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
07-01 12:08:49.243  6903  6903 D BluetoothAdapterState: isTurningOnRadio()=false
07-01 12:08:49.243  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:49.243  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:49.243  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:49.243  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false,
07-01 12:08:49.243  6903  6903 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.243  6903  6903 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.243  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
07-01 12:08:49.243  6903  6903 D BluetoothFTPService: cleanup FTP Service
,07-01 12:08:49.243  6903  6903 V BluetoothFTPServiceJni: closeFtpServerNative
07-01 12:08:49.243  6903  6903 V BluetoothFTPServiceJni: cleanupNative
07-01 12:08:49.243  6903  6903 W BluetoothFTPServiceJni: Cleaning up Bluetooth FTP Server Interface...,
07-01 12:08:49.243  6903  6903 W BluetoothFTPServiceJni: Cleaning up Bluetooth FTP callback object
07-01 12:08:49.243  6903  6903 D BluetoothFTPService: BluetoothFtpBinder.cleanup()
07-01 12:08:49.244  6903  6903 D BluetoothFTPService: cleanup done
,07-01 12:08:49.244  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - Message: 1
07-01 12:08:49.244  6903  6903 D BluetoothAdapterService(864710247): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-01 12:08:49.244  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
07-01 12:08:49.244  6903  6903 D BluetoothAdapterState: isTurningOnRadio()=false
,07-01 12:08:49.244  6903  6903 D BluetoothAdapterState: isTurningOffRadio()=false
07-01 12:08:49.244  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-01 12:08:49.244  6903  6903 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-01 12:08:49.244  6903  6903 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
07-01 12:08:49.244  6903  6903 D BluetoothAdapterService(864710247): onProfileServiceStateChange() - All profile services stopped...
,07-01 12:08:49.244  6903  6903 D OppService: cleanup OPP Service
07-01 12:08:49.244  6903  6903 D OppService: remove callbacks and handler
07-01 12:08:49.244  6903  6903 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-01 12:08:49.244  6903  6903 D OppService: cleanup done
,07-01 12:08:49.244  6903  6945 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-01 12:08:49.244  6903  6945 D BluetoothAdapterProperties: Setting state to 10
07-01 12:08:49.244  6903  6945 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-01 12:08:49.244  6903  6945 D BluetoothAdapterService(864710247): updateAdapterState() - Broadcasting state to 1 receivers.
,07-01 12:08:49.245   968  1056 D BluetoothManagerService: Message: 60
07-01 12:08:49.245   968  1056 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-01 12:08:49.245   968  1056 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
07-01 12:08:49.245  6903  6945 I BluetoothAdapterState: Entering OffState
,07-01 12:08:49.245  1747  2372 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 12:08:49.246  6805  6824 D BluetoothPbap: onBluetoothStateChange: up=false
07-01 12:08:49.246  6805  6827 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-01 12:08:49.247   968  1056 D BluetoothA2dp: onBluetoothStateChange: up=false
07-01 12:08:49.247  1747  1762 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 12:08:49.247  6805  7077 D BluetoothMap: onBluetoothStateChange: up=false
07-01 12:08:49.248  6805  6824 D BluetoothPan: onBluetoothStateChange on: false
07-01 12:08:49.248   968  1056 D BluetoothHeadset: onBluetoothStateChange: up=false,
07-01 12:08:49.248  1747  1763 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 12:08:49.249   288  1288 V AudioFlinger: thread 0xb5651000 type 0 TID 1288 going to sleep
07-01 12:08:49.249   968  1056 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,07-01 12:08:49.251   288  1293 V AudioFlinger: thread 0xb5735000 type 0 TID 1293 going to sleep
07-01 12:08:49.252  6903  6921 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:49.253  1799  1799 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:49.254  1799  1988 D LGBluetoothAPIService: Message: 2
,07-01 12:08:49.254  1799  1988 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2d866dd3 mBinding = false
07-01 12:08:49.254  1799  1988 D LGBluetoothAPIService: Sending unbind request.
,07-01 12:08:49.255  6903  6921 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75,
07-01 12:08:49.255  6903  6919 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75,
07-01 12:08:49.255   288  1291 V AudioFlinger: thread 0xb56eb000 type 0 TID 1291 going to sleep
07-01 12:08:49.256  6805  6805 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-01 12:08:49.256  6805  6805 D LGBluetoothEventManager: [BTUI] clear device connection state
07-01 12:08:49.257  1370  1370 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null,
07-01 12:08:49.257  1370  1370 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
07-01 12:08:49.257  6805  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-01 12:08:49.261  6903  7075 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:49.262  6903  6903 D LGBluetoothAPIServer: [BTUI] onUnbind()
,07-01 12:08:49.262  6903  6903 D LGBluetoothAPIServer: [BTUI] cleanup() done
07-01 12:08:49.262  6903  6903 D LGBluetoothAPIServer: [BTUI] onDestroy()
07-01 12:08:49.265  6903  6903 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-01 12:08:49.265  6903  6903 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:08:49.265  6903  6903 V BluetoothPbapReceiver: ***********state = 10
07-01 12:08:49.266  6805  6805 D DockEventReceiver: finishStartingService: stopping service
,07-01 12:08:49.274  6805  6805 D BluetoothPermissionRequest: onReceive
,07-01 12:08:49.276  6805  6805 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-01 12:08:49.276  6805  6805 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-01 12:08:49.284  6903  6903 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-01 12:08:49.285  6903  6903 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:08:49.289  6860  6860 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
07-01 12:08:49.323  7121  7121 I AppUp4:AppBoxCP: onCreate
,07-01 12:08:49.326  7121  7121 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
07-01 12:08:49.335  7121  7121 I AppUp4:DB:  setFingerPrint start
07-01 12:08:49.336  7121  7121 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
,07-01 12:08:49.344  7121  7121 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
07-01 12:08:49.344  7121  7121 I AppUp4:DB:  SDK version = 21
07-01 12:08:49.345  7121  7121 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-01 12:08:49.346  7121  7121 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-01 12:08:49.351  7121  7121 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-01 12:08:49.351  7121  7121 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-01 12:08:49.353  7121  7121 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-01 12:08:49.353  7121  7121 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,07-01 12:08:49.359  7121  7121 I AppUp4:CustModeStarterReceiver: onReceive
07-01 12:08:49.359  7121  7121 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
07-01 12:08:49.363  7121  7121 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@34a1148b
07-01 12:08:49.363  7121  7121 D AppUp4:CustFacade: isCustomizationCompleted : false
,07-01 12:08:49.369  2397  2397 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-01 12:08:49.370   298   349 I ThermalEngine: Sensor:pa_therm0:33000 mC
07-01 12:08:49.371  7121  7121 D AppUp4:CustFacade: isSimDevice : true
07-01 12:08:49.375  7121  7121 D AppUp4:CustModeStarterReceiver: begin check event
07-01 12:08:49.376  7121  7121 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-01 12:08:49.377  7121  7121 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,07-01 12:08:49.378  2397  2397 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-01 12:08:49.380  7121  7141 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,07-01 12:08:49.380  2397  7145 D EasyUnlockInitService: Handling intent for initializer IntentService.
07-01 12:08:49.380  7121  7141 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
07-01 12:08:49.380  7121  7141 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
07-01 12:08:49.393  2397  7145 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-01 12:08:49.397  3199  3199 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,07-01 12:08:49.397  3199  3199 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-01 12:08:49.398  3199  3199 I LgeMiscReceiver: networkInfo.isConnected() = false
07-01 12:08:49.442   968  1861 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7146 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,07-01 12:08:49.602  7146  7146 D PhoneMonitor: Register our PhoneStateListener
,07-01 12:08:49.763   968  1861 I art     : Explicit concurrent mark sweep GC freed 43359(2024KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 1.939ms total 151.923ms
,07-01 12:08:49.783  7146  7146 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-01 12:08:49.784  7146  7146 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-01 12:08:49.786   968   985 I ActivityManager: Killing 6444:com.lge.bnr/1000 (adj 15): empty #11
,07-01 12:08:49.811  7146  7146 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
07-01 12:08:49.813  7146  7146 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
07-01 12:08:49.819  7146  7146 D TelephonyAutoProfiling: [parse] Load xml
,07-01 12:08:49.827  7146  7146 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
07-01 12:08:49.827  7146  7146 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,07-01 12:08:49.835  7146  7146 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
07-01 12:08:49.868   968  1633 W libprocessgroup: failed to open /acct/uid_1000/pid_6444/cgroup.procs: No such file or directory
,07-01 12:08:49.928   968  2163 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7170 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,07-01 12:08:50.026   968  1381 I ActivityManager: Killing 6999:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,07-01 12:08:50.246   968  1305 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:08:50.247   968  1305 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,07-01 12:08:50.269   968  1861 W libprocessgroup: failed to open /acct/uid_10089/pid_6999/cgroup.procs: No such file or directory
,07-01 12:08:50.281  2925  2925 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:8:50
07-01 12:08:50.285  2925  2925 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-01 12:08:50.285  2925  2925 D WeatherAncestor: connectivity changed - connection : true
07-01 12:08:50.285  2925  2925 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-01 12:08:50.285  2925  2925 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:8:50
,07-01 12:08:50.289  2925  2925 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
07-01 12:08:50.294  2925  2925 D WeatherService: 2 : shouldTimeTickRegistered : false
07-01 12:08:50.301  3391  3391 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-01 12:08:50.314  3391  5024 I iu.UploadsManager: num queued entries: 0
07-01 12:08:50.314  3391  5024 I iu.UploadsManager: num updated entries: 0
07-01 12:08:50.317  3391  5024 I iu.SyncManager: NEXT; no task
,07-01 12:08:50.367   968  1861 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7190 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-01 12:08:50.446  7190  7190 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-01 12:08:50.688  7190  7219 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,07-01 12:08:50.689  7190  7219 I Babel_SMS: MmsConfig.loadMmsSettings
07-01 12:08:50.691  7190  7219 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
07-01 12:08:50.691  7190  7219 I Babel_SMS: MmsConfig.loadFromDatabase
,07-01 12:08:50.726  7190  7219 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-01 12:08:50.726  7190  7219 I Babel_SMS: MmsConfig.loadFromResources
,07-01 12:08:50.732  7190  7219 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-01 12:08:50.733  7190  7219 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
07-01 12:08:50.784  7190  7190 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
07-01 12:08:50.784  7190  7190 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
07-01 12:08:50.784  7190  7190 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
07-01 12:08:50.784  7190  7190 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
07-01 12:08:50.785  7190  7190 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
07-01 12:08:50.785  7190  7190 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
07-01 12:08:50.785  7190  7190 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
07-01 12:08:50.785  7190  7190 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
07-01 12:08:50.785  7190  7190 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
07-01 12:08:50.785  7190  7190 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
07-01 12:08:50.785  7190  7190 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
07-01 12:08:50.785  7190  7190 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
07-01 12:08:50.785  7190  7190 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
07-01 12:08:50.785  7190  7190 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
07-01 12:08:50.785  7190  7190 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
07-01 12:08:50.787  7190  7190 D SensorManager: found sensor: Motion Accel, handle=46
,07-01 12:08:50.854  7190  7209 I art     : CheckpointMarkThreadRoots callback created = 0xafc54980
07-01 12:08:50.856  2397  4513 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-01 12:08:50.863  7190  7190 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:08:50.877  7190  7190 I Babel_Crash: startup - clean
07-01 12:08:50.908  7190  7222 I Babel   : deleted: false for 0
,07-01 12:08:50.916  7190  7209 I art     : CheckpointMarkThreadRoots callback created = 0xafc54970
07-01 12:08:51.034   968  1781 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7230 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 12:08:51.126  7190  7190 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,07-01 12:08:51.133  7190  7190 W AudioCapabilities: Unsupported mime audio/adpcm
07-01 12:08:51.144  7190  7190 W AudioCapabilities: Unsupported mime audio/g726
,07-01 12:08:51.151  7190  7190 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-01 12:08:51.152  7190  7190 W AudioCapabilities: Unsupported mime audio/wma-voice
07-01 12:08:51.154  7190  7190 W VideoCapabilities: Unsupported mime video/mjpg
07-01 12:08:51.170  7190  7190 W VideoCapabilities: Unsupported mime video/theora
,07-01 12:08:51.231  7190  7190 W AudioCapabilities: Unsupported mime audio/evrc
07-01 12:08:51.233  7190  7190 W AudioCapabilities: Unsupported mime audio/qcelp
07-01 12:08:51.234  7190  7190 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-01 12:08:51.242  7190  7190 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
07-01 12:08:51.243  7190  7190 W AudioCapabilities: Unsupported mime audio/qcelp
07-01 12:08:51.244  7190  7190 W AudioCapabilities: Unsupported mime audio/evrc
07-01 12:08:51.262  7190  7190 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-01 12:08:51.289  7190  7190 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-01 12:08:51.296  7190  7190 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-01 12:08:51.298  7190  7190 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-01 12:08:51.302  7190  7190 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-01 12:08:51.309  7190  7190 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-01 12:08:51.318  7190  7190 I vclib   : onServiceConnected
,07-01 12:08:51.319  7190  7190 W Babel   : Attempted to change video mute state without an active call.
07-01 12:08:51.325  7190  7247 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
07-01 12:08:51.332  7190  7190 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,07-01 12:08:51.336   968  1842 I ActivityManager: Killing 6841:com.lge.sync/1000 (adj 15): empty #11
,07-01 12:08:51.349  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-01 12:08:51.349  6689  6767 I jxcore-log: 
,07-01 12:08:51.418   968  2163 W libprocessgroup: failed to open /acct/uid_1000/pid_6841/cgroup.procs: No such file or directory
,07-01 12:08:51.538   247   316 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,07-01 12:08:51.538   247   316 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-01 12:08:51.538   247   316 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 12:08:51.541  7230  7251 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-01 12:08:51.547   247   316 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-01 12:08:51.547   247   316 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-01 12:08:51.547   247   316 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 12:08:51.547  7230  7251 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-01 12:08:51.558   247   316 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-01 12:08:51.558   247   316 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-01 12:08:51.558   247   316 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 12:08:51.559  7230  7255 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,07-01 12:08:51.561   247   316 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-01 12:08:51.561   247   316 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-01 12:08:51.561   247   316 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 12:08:51.562  7230  7255 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-01 12:08:51.568  7230  7230 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-01 12:08:51.568  7230  7230 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-01 12:08:51.568  7230  7230 I GAv4    :   adb logcat -s GAv4
07-01 12:08:51.587  7230  7230 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-01 12:08:51.621  7230  7230 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-01 12:08:51.628  7230  7257 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
07-01 12:08:51.929  7230  7230 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,07-01 12:08:51.978  7230  7230 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 981-983)
07-01 12:08:51.979  7230  7230 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-01 12:08:51.987  7230  7230 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2fbdc20e}
07-01 12:08:51.988  7230  7230 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 12:08:51.988  7230  7230 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-01 12:08:52.002  7230  7230 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-01 12:08:52.003  7230  7230 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 12:08:52.004  7230  7230 E SysUtils: ApplicationContext is null in ApplicationStatus
07-01 12:08:52.037  7230  7230 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-01 12:08:52.046  7230  7230 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-01 12:08:52.047  7230  7230 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-01 12:08:52.047  7230  7230 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-01 12:08:52.047  7230  7230 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-01 12:08:52.047  7230  7230 I Adreno-EGL: Build Date: 03/02/15 Mon
07-01 12:08:52.047  7230  7230 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-01 12:08:52.047  7230  7230 I Adreno-EGL: Remote Branch: 
07-01 12:08:52.047  7230  7230 I Adreno-EGL: Local Patches: 
07-01 12:08:52.047  7230  7230 I Adreno-EGL: Reconstruct Branch: 
,07-01 12:08:52.085  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-01 12:08:52.085  6689  6767 I jxcore-log: 
,07-01 12:08:52.127  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-01 12:08:52.127  6689  6767 I jxcore-log: 
,07-01 12:08:52.135  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-01 12:08:52.135  6689  6767 I jxcore-log: 
07-01 12:08:52.142   288  2050 V AudioPolicyService: registerClient() client 0xb57ec0c0, uid 10079
,07-01 12:08:52.149  7230  7285 W AudioManagerAndroid: Requires BLUETOOTH permission
07-01 12:08:52.153  7230  7230 I NSApplication: Starting up...
07-01 12:08:52.165  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-01 12:08:52.165  6689  6767 I jxcore-log: 
,07-01 12:08:52.172  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-01 12:08:52.172  6689  6767 I jxcore-log: 
07-01 12:08:52.209   968   985 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7290 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 12:08:52.212   968   985 I ActivityManager: Killing 7039:com.google.android.music:main/u0a81 (adj 15): empty #11
07-01 12:08:52.336   968  1861 W libprocessgroup: failed to open /acct/uid_10081/pid_7039/cgroup.procs: No such file or directory
,07-01 12:08:52.592   968  1897 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7309 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-01 12:08:52.595   968  1897 I ActivityManager: Killing 7082:com.lge.email/u0a21 (adj 15): empty #11
07-01 12:08:52.686   968   985 W libprocessgroup: failed to open /acct/uid_10021/pid_7082/cgroup.procs: No such file or directory
,07-01 12:08:52.743  7309  7309 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-01 12:08:53.054   968  1312 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,07-01 12:08:53.168   968  1633 I ActivityManager: Killing 6966:com.lge.lgdmsclient/1000 (adj 15): empty #11
,07-01 12:08:53.287   968  2143 W libprocessgroup: failed to open /acct/uid_1000/pid_6966/cgroup.procs: No such file or directory
,07-01 12:08:53.343   968   986 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7340 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 12:08:53.591  7340  7340 I MusicStore: Database version: 120
,07-01 12:08:53.645   247   316 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-01 12:08:53.645   247   316 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-01 12:08:53.645   247   316 W Vold    : Returning OperationFailed - no handler for errno 0
,07-01 12:08:53.646  7340  7340 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
07-01 12:08:53.754   247   316 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,07-01 12:08:53.754   247   316 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-01 12:08:53.754   247   316 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 12:08:53.754  7340  7340 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
07-01 12:08:53.757   247   316 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-01 12:08:53.757   247   316 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-01 12:08:53.757   247   316 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 12:08:53.757  7340  7340 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
07-01 12:08:53.784  7340  7340 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-01 12:08:53.784  7340  7340 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-01 12:08:53.848  7340  7340 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-01 12:08:54.004  7340  7340 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
07-01 12:08:54.004  7340  7340 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@277d7396: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-01 12:08:54.006  7340  7340 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-01 12:08:54.007  7340  7340 D AndroidMusic: GMSCore installation verified
07-01 12:08:54.015  7340  7340 I ConfigStore: Config Database version: 1
,07-01 12:08:54.068  7340  7354 I art     : CheckpointMarkThreadRoots callback created = 0xafc2d3f0
,07-01 12:08:54.097  7340  7354 I art     : CheckpointMarkThreadRoots callback created = 0xafc2d3d0
,07-01 12:08:54.142  7340  7340 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,07-01 12:08:54.150  7340  7340 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,07-01 12:08:54.224   968  1805 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7377 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-01 12:08:54.302  7340  7340 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,07-01 12:08:54.321  7340  7340 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-01 12:08:54.345  7377  7377 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 12:08:54.345  7377  7377 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-01 12:08:54.347  7377  7377 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-01 12:08:54.369   968  1344 I ActivityManager: Killing 6805:com.android.settings/1000 (adj 15): empty #11
,07-01 12:08:54.377   298   349 I ThermalEngine: Sensor:pa_therm0:33000 mC
07-01 12:08:54.476   968  2163 W libprocessgroup: failed to open /acct/uid_1000/pid_6805/cgroup.procs: No such file or directory
,07-01 12:08:54.484   968  1897 I ActivityManager: Killing 6860:com.lge.settings.easy/1000 (adj 15): empty #11
07-01 12:08:54.485  7340  7367 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
07-01 12:08:54.566   968  1805 W libprocessgroup: failed to open /acct/uid_1000/pid_6860/cgroup.procs: No such file or directory
,07-01 12:08:54.586  7377  7377 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,07-01 12:08:54.603  7377  7377 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,07-01 12:08:54.828  7377  7377 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-01 12:08:54.883   968  1897 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7413 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,07-01 12:08:54.958  7377  7377 I HubEmail: JNI_OnLoad()
07-01 12:08:54.958  7377  7377 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-01 12:08:54.958  7377  7377 I HubEmail: registerNatives()
07-01 12:08:54.958  7377  7377 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-01 12:08:54.958  7377  7377 I HubEmail: registerNativeMethods()
07-01 12:08:54.958  7377  7377 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-01 12:08:54.958  7377  7377 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
07-01 12:08:54.964   968  1876 I ActivityManager: Killing 7121:com.lge.appbox.client/u0a11 (adj 15): empty #11
,07-01 12:08:55.076   968  1344 W libprocessgroup: failed to open /acct/uid_10011/pid_7121/cgroup.procs: No such file or directory
,07-01 12:08:55.080  7413  7413 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-01 12:08:55.081  7413  7413 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-01 12:08:55.083  7413  7413 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-01 12:08:55.086  7413  7413 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-01 12:08:55.089  7377  7430 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-01 12:08:55.096  7413  7438 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-01 12:08:55.097  7413  7438 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-01 12:08:55.104  7413  7437 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-01 12:08:55.136   968  1805 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7441 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
07-01 12:08:55.159   309   309 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 21.184ms
,07-01 12:08:55.175   968  1876 I ActivityManager: Killing 7146:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,07-01 12:08:55.181   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 21.559ms
07-01 12:08:55.202   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 21.190ms
,07-01 12:08:55.299   968  1897 W libprocessgroup: failed to open /acct/uid_10038/pid_7146/cgroup.procs: No such file or directory
07-01 12:08:55.326  7441  7441 I AppUp4:AppBoxCP: onCreate
,07-01 12:08:55.327  7441  7441 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
07-01 12:08:55.337  7441  7441 I AppUp4:DB:  setFingerPrint start
07-01 12:08:55.337  7441  7441 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
07-01 12:08:55.344  7441  7441 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
07-01 12:08:55.344  7441  7441 I AppUp4:DB:  SDK version = 21
07-01 12:08:55.344  7441  7441 I AppUp4:DB:  beforefinger == newfinger no write in DB
,07-01 12:08:55.346  7441  7441 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-01 12:08:55.347  7441  7441 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-01 12:08:55.347  7441  7441 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-01 12:08:55.348  7441  7441 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-01 12:08:55.349  7441  7441 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-01 12:08:55.353  7441  7441 I AppUp4:CustModeStarterReceiver: onReceive
07-01 12:08:55.353  7441  7441 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
07-01 12:08:55.357  7441  7441 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@34a1148b
07-01 12:08:55.357  7441  7441 D AppUp4:CustFacade: isCustomizationCompleted : false
,07-01 12:08:55.363  7441  7441 D AppUp4:CustFacade: isSimDevice : true
07-01 12:08:55.364  7441  7441 D AppUp4:CustModeStarterReceiver: begin check event
07-01 12:08:55.364  7441  7441 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-01 12:08:55.364  7441  7441 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
07-01 12:08:55.365  7441  7458 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
07-01 12:08:55.365  7441  7458 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
07-01 12:08:55.365  7441  7458 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
07-01 12:08:55.367   968  1861 I ActivityManager: Killing 7170:com.lge.drmservice/u0a51 (adj 15): empty #11
07-01 12:08:55.507   968  1805 W libprocessgroup: failed to open /acct/uid_10051/pid_7170/cgroup.procs: No such file or directory
,07-01 12:08:55.509  3199  3199 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-01 12:08:55.509  3199  3199 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-01 12:08:55.509  3199  3199 I LgeMiscReceiver: networkInfo.isConnected() = false
,07-01 12:08:55.547   968  1941 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7461 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,07-01 12:08:55.668  7461  7461 D PhoneMonitor: Register our PhoneStateListener
,07-01 12:08:55.682  7461  7461 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-01 12:08:55.683  7461  7461 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,07-01 12:08:55.684   968  1633 I ActivityManager: Killing 7190:com.google.android.talk/u0a61 (adj 15): empty #11
,07-01 12:08:55.702  7461  7461 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
07-01 12:08:55.702  7461  7461 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
07-01 12:08:55.703  7461  7461 D TelephonyAutoProfiling: [parse] Load xml
07-01 12:08:55.706  7461  7461 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
07-01 12:08:55.706  7461  7461 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,07-01 12:08:55.712  7461  7461 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
07-01 12:08:55.837   968   985 W libprocessgroup: failed to open /acct/uid_10061/pid_7190/cgroup.procs: No such file or directory
,07-01 12:08:55.874   968  1633 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7480 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,07-01 12:08:55.955   968  1633 I ActivityManager: Killing 7230:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,07-01 12:08:55.991  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-01 12:08:55.991  6689  6767 I jxcore-log: 
,07-01 12:08:56.009  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-01 12:08:56.009  6689  6767 I jxcore-log: 
,07-01 12:08:56.022  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-01 12:08:56.022  6689  6767 I jxcore-log: 
,07-01 12:08:56.177   968  1897 W libprocessgroup: failed to open /acct/uid_10079/pid_7230/cgroup.procs: No such file or directory
,07-01 12:08:56.177  2925  2925 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:8:56
07-01 12:08:56.181  2925  2925 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-01 12:08:56.181  2925  2925 D WeatherAncestor: connectivity changed - connection : true
07-01 12:08:56.181  2925  2925 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-01 12:08:56.181  2925  2925 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:8:56
07-01 12:08:56.181  2925  2925 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
07-01 12:08:56.182  2925  2925 D WeatherService: 2 : shouldTimeTickRegistered : false
07-01 12:08:56.238   968   986 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7497 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-01 12:08:56.284  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-01 12:08:56.284  6689  6767 I jxcore-log: 
,07-01 12:08:56.332  7497  7497 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-01 12:08:56.434  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-01 12:08:56.434  6689  6767 I jxcore-log: 
,07-01 12:08:56.526  7497  7519 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-01 12:08:56.526  7497  7519 I Babel_SMS: MmsConfig.loadMmsSettings
,07-01 12:08:56.530  7497  7519 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
07-01 12:08:56.530  7497  7519 I Babel_SMS: MmsConfig.loadFromDatabase
07-01 12:08:56.536  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-01 12:08:56.536  6689  6767 I jxcore-log: 
07-01 12:08:56.548  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-01 12:08:56.548  6689  6767 I jxcore-log: 
07-01 12:08:56.562  7497  7519 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-01 12:08:56.562  7497  7519 I Babel_SMS: MmsConfig.loadFromResources
07-01 12:08:56.563  7497  7519 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-01 12:08:56.564  7497  7519 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,07-01 12:08:56.576  7497  7497 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
07-01 12:08:56.576  7497  7497 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
07-01 12:08:56.576  7497  7497 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
07-01 12:08:56.576  7497  7497 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
07-01 12:08:56.576  7497  7497 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
07-01 12:08:56.576  7497  7497 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
07-01 12:08:56.576  7497  7497 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
07-01 12:08:56.576  7497  7497 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
07-01 12:08:56.576  7497  7497 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
07-01 12:08:56.576  7497  7497 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
,07-01 12:08:56.576  7497  7497 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
07-01 12:08:56.576  7497  7497 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
07-01 12:08:56.576  7497  7497 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
07-01 12:08:56.576  7497  7497 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
07-01 12:08:56.576  7497  7497 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
07-01 12:08:56.576  7497  7497 D SensorManager: found sensor: Motion Accel, handle=46
07-01 12:08:56.600  7497  7497 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-01 12:08:56.605  7497  7497 I Babel_Crash: startup - clean
07-01 12:08:56.653  7497  7511 I art     : CheckpointMarkThreadRoots callback created = 0xaaf718e0
,07-01 12:08:56.660  7497  7526 I Babel   : deleted: false for 0
,07-01 12:08:56.688  7497  7511 I art     : CheckpointMarkThreadRoots callback created = 0xaaf718d0
07-01 12:08:56.715  7497  7511 W art     : Suspending all threads took: 7.363ms
,07-01 12:08:56.837   968  2143 I art     : Explicit concurrent mark sweep GC freed 20454(969KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 1.898ms total 158.637ms
,07-01 12:08:56.886   968  1834 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7529 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 12:08:56.936  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-01 12:08:56.936  6689  6767 I jxcore-log: 
,07-01 12:08:56.974  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-01 12:08:56.974  6689  6767 I jxcore-log: 
,07-01 12:08:56.982  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-01 12:08:56.982  6689  6767 I jxcore-log: 
,07-01 12:08:56.991  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-01 12:08:56.991  6689  6767 I jxcore-log: 
,07-01 12:08:57.011  7497  7497 W AudioCapabilities: Unsupported mime audio/x-lg-flac
07-01 12:08:57.012  7497  7497 W AudioCapabilities: Unsupported mime audio/adpcm
07-01 12:08:57.013  7497  7497 W AudioCapabilities: Unsupported mime audio/g726
07-01 12:08:57.014  7497  7497 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-01 12:08:57.015  7497  7497 W AudioCapabilities: Unsupported mime audio/wma-voice
,07-01 12:08:57.017  7497  7497 W VideoCapabilities: Unsupported mime video/mjpg
07-01 12:08:57.021  7497  7497 W VideoCapabilities: Unsupported mime video/theora
07-01 12:08:57.027  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-01 12:08:57.027  6689  6767 I jxcore-log: 
,07-01 12:08:57.053  7497  7497 W AudioCapabilities: Unsupported mime audio/evrc
,07-01 12:08:57.055  7497  7497 W AudioCapabilities: Unsupported mime audio/qcelp
07-01 12:08:57.056  7497  7497 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-01 12:08:57.066  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-01 12:08:57.066  6689  6767 I jxcore-log: 
,07-01 12:08:57.069  7497  7497 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
07-01 12:08:57.071  7497  7497 W AudioCapabilities: Unsupported mime audio/qcelp
07-01 12:08:57.072  7497  7497 W AudioCapabilities: Unsupported mime audio/evrc
07-01 12:08:57.085  7497  7497 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-01 12:08:57.114  7497  7497 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-01 12:08:57.122  7497  7497 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-01 12:08:57.124  7497  7497 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-01 12:08:57.129  7497  7497 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-01 12:08:57.134  7497  7497 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-01 12:08:57.143  7497  7497 I vclib   : onServiceConnected
,07-01 12:08:57.144  7497  7497 W Babel   : Attempted to change video mute state without an active call.
07-01 12:08:57.150  7497  7549 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
07-01 12:08:57.174   968  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2ad7b1bf type 2 when 186173 com.google.android.gms} when 186173
,07-01 12:08:57.179   247   316 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-01 12:08:57.179   247   316 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-01 12:08:57.179   247   316 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 12:08:57.179  7529  7553 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-01 12:08:57.182   247   316 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-01 12:08:57.183   247   316 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-01 12:08:57.183   247   316 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 12:08:57.183  7529  7553 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-01 12:08:57.196  7529  7529 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-01 12:08:57.196  7529  7529 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-01 12:08:57.196  7529  7529 I GAv4    :   adb logcat -s GAv4
,07-01 12:08:57.216   247   316 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-01 12:08:57.216   247   316 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-01 12:08:57.216   247   316 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 12:08:57.217  7529  7554 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-01 12:08:57.219   247   316 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-01 12:08:57.220   247   316 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,07-01 12:08:57.220   247   316 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 12:08:57.220  7529  7554 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-01 12:08:57.230  7529  7529 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
07-01 12:08:57.237  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-01 12:08:57.237  6689  6767 I jxcore-log: 
,07-01 12:08:57.245  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-01 12:08:57.245  6689  6767 I jxcore-log: 
07-01 12:08:57.270  7529  7529 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-01 12:08:57.279  7529  7560 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
07-01 12:08:57.293  6689  6767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-01 12:08:57.293  6689  6767 I jxcore-log: 
,07-01 12:08:57.305  2397  2558 I art     : Explicit concurrent mark sweep GC freed 57540(3MB) AllocSpace objects, 52(855KB) LOS objects, 40% free, 15MB/25MB, paused 1.965ms total 153.236ms
,07-01 12:08:57.317  6689  6767 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
07-01 12:08:57.323  6689  6767 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-01 12:08:57.323  6689  6767 I jxcore-log: 
07-01 12:08:57.325  7497  7497 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,07-01 12:08:57.337   968   986 I ActivityManager: Killing 7290:com.android.chrome/u0a48 (adj 15): empty #11
,07-01 12:08:57.397   968  1381 W libprocessgroup: failed to open /acct/uid_10048/pid_7290/cgroup.procs: No such file or directory
,07-01 12:08:57.419  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-01 12:08:57.419  6689  6767 I jxcore-log: 
07-01 12:08:57.420  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-01 12:08:57.420  6689  6767 I jxcore-log: 
07-01 12:08:57.421  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-01 12:08:57.421  6689  6767 I jxcore-log: 
07-01 12:08:57.422  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-01 12:08:57.422  6689  6767 I jxcore-log: 
07-01 12:08:57.425  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 12:08:57.425  6689  6767 I jxcore-log: 
07-01 12:08:57.427  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 12:08:57.427  6689  6767 I jxcore-log: 
,07-01 12:08:57.428  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-01 12:08:57.428  6689  6767 I jxcore-log: 
07-01 12:08:57.429  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-01 12:08:57.429  6689  6767 I jxcore-log: 
07-01 12:08:57.430  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 12:08:57.430  6689  6767 I jxcore-log: 
07-01 12:08:57.431  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 12:08:57.431  6689  6767 I jxcore-log: 
07-01 12:08:57.432  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-01 12:08:57.432  6689  6767 I jxcore-log: 
07-01 12:08:57.433  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-01 12:08:57.433  6689  6767 I jxcore-log: 
07-01 12:08:57.433  6689  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 12:08:57.433  6689  6767 I jxcore-log: 
07-01 12:08:57.547  7529  7529 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,07-01 12:08:57.577  7529  7529 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6579-6581)
,07-01 12:08:57.577  7529  7529 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-01 12:08:57.582  7529  7529 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2fbdc20e}
07-01 12:08:57.583  7529  7529 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 12:08:57.583  7529  7529 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-01 12:08:57.596  7529  7529 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-01 12:08:57.597  7529  7529 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 12:08:57.598  7529  7529 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-01 12:08:57.614  7529  7529 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-01 12:08:57.620  7529  7529 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-01 12:08:57.621  7529  7529 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-01 12:08:57.621  7529  7529 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-01 12:08:57.621  7529  7529 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-01 12:08:57.621  7529  7529 I Adreno-EGL: Build Date: 03/02/15 Mon
07-01 12:08:57.621  7529  7529 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-01 12:08:57.621  7529  7529 I Adreno-EGL: Remote Branch: 
07-01 12:08:57.621  7529  7529 I Adreno-EGL: Local Patches: 
07-01 12:08:57.621  7529  7529 I Adreno-EGL: Reconstruct Branch: 
07-01 12:08:57.678   288  1351 V AudioPolicyService: registerClient() client 0xb4027460, uid 10079
,07-01 12:08:57.679  7529  7593 W AudioManagerAndroid: Requires BLUETOOTH permission
07-01 12:08:57.689  7529  7529 I NSApplication: Starting up...
07-01 12:08:57.744   968   985 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7601 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 12:08:57.748   968   985 I ActivityManager: Killing 7309:com.google.android.apps.plus/u0a86 (adj 15): empty #11
07-01 12:08:57.796   968  1633 W libprocessgroup: failed to open /acct/uid_10086/pid_7309/cgroup.procs: No such file or directory
,07-01 12:08:57.920   968  1834 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7620 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
07-01 12:08:57.922   968  1834 I ActivityManager: Killing 7340:com.google.android.music:main/u0a81 (adj 15): empty #11
07-01 12:08:57.956   968  1381 W libprocessgroup: failed to open /acct/uid_10081/pid_7340/cgroup.procs: No such file or directory
,07-01 12:08:57.979  7620  7620 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-01 12:08:58.237   968   985 I ActivityManager: Killing 7377:com.lge.email/u0a21 (adj 15): empty #11
,07-01 12:08:58.253   483   483 D charger_monitor: init target 500000
,07-01 12:08:58.258   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-01 12:08:58.267   968   986 W libprocessgroup: failed to open /acct/uid_10021/pid_7377/cgroup.procs: No such file or directory
,07-01 12:08:58.271  1799  1799 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-01 12:08:58.274  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,07-01 12:08:58.276  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-01 12:08:58.280  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-01 12:08:58.280  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-01 12:08:58.324   968  1633 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7644 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,07-01 12:08:58.327  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 303
07-01 12:08:58.330  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-01 12:08:58.330  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 303
07-01 12:08:58.331   968  1311 D WifiController: battery changed pluggedType: 2
07-01 12:08:58.332  1835  1835 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-01 12:08:58.332  1799  1957 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-01 12:08:58.333  1799  1957 D LEDHandler: Battery Level Remaining: 100%
07-01 12:08:58.333  1799  1957 D LEDHandler: Battery Temp: 303, mChargingStatus=5, mChargingStop=false
07-01 12:08:58.334  1835  1835 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-01 12:08:58.340  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,07-01 12:08:58.388  7644  7644 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-01 12:08:58.458   968  1056 D BluetoothManagerService: Message: 20
07-01 12:08:58.458   968  1056 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bcae331:true
,07-01 12:08:58.465  6903  6919 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:58.466  6903  6984 D BluetoothAdapterService(864710247): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@6bd5e75
07-01 12:08:58.564   968  1897 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7662 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 12:08:58.599  7644  7644 V LGMDMManager: Create singleton instance
,07-01 12:08:58.649  7662  7662 D UEI.SmartControl: Quickset Services start...
,07-01 12:08:58.654  7662  7662 I UEI.SmartControl: Manufacture = LGE
07-01 12:08:58.657  7662  7662 D UEI.SmartControl: File observer start...
07-01 12:08:58.658  7662  7662 E UEI.SmartControl: IR Port is disabled: false
07-01 12:08:58.659  7662  7662 D UEI.SmartControl: Starting file observer...
07-01 12:08:58.659  7662  7662 D UEI.SmartControl: Extracting JNI libs...
07-01 12:08:58.660  7662  7662 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-01 12:08:58.698  7644  7644 I AudioManager: getMode name:com.lge.qremote
,07-01 12:08:58.735  7644  7644 I AudioManager: getMode name:com.lge.qremote
,07-01 12:08:58.741  2397  7681 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-01 12:08:58.742  2397  7681 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-01 12:08:58.746  2397  7681 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-01 12:08:58.746  2397  7681 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-01 12:08:58.748   282  1043 E BandwidthController: [LG DATA] No such appUid: 10006
07-01 12:08:58.748   282  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,07-01 12:08:58.749   282  7682 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-01 12:08:58.749   282  7682 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-01 12:08:58.752   282  7682 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-01 12:08:58.753   968  1054 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,07-01 12:08:58.849  7662  7662 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-01 12:08:58.850  7662  7662 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-01 12:08:58.850  7662  7662 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-01 12:08:58.886  7662  7662 I UEI.SmartControl: --- Selecting new region: 2
07-01 12:08:58.886  7662  7662 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
,07-01 12:08:58.891  7662  7662 D UEI.SmartControl: Platform has CIR...
07-01 12:08:58.893  7662  7662 D UEI.SmartControl: NO CIR support, need to check package...
07-01 12:08:58.893  7662  7662 I UEI.SmartControl: Model: LG-D722 uses JNI
07-01 12:08:58.896  7662  7662 D UEI.SmartControl: QS Service created
07-01 12:08:58.920  7662  7662 E UEI.SmartControl: QS start get config
,07-01 12:08:58.969  7662  7662 D UEI.SmartControl: Loading JNI Libs...
,07-01 12:08:58.972  7662  7662 D UEI.SmartControl:  configuring local db...
07-01 12:08:59.183  7662  7662 D UEI.SmartControl:  ---- Has DB8: true
,07-01 12:08:59.192  7662  7662 D UEI.SmartControl: QS start statue = true Error code = 0
07-01 12:08:59.193  7662  7662 D UEI.SmartControl: QS version = v2.7.11.1_RC1
07-01 12:08:59.194  7662  7662 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
07-01 12:08:59.197  7662  7662 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
,07-01 12:08:59.221  7662  7662 W irrc_jni: IRRCPlayer_nativeInit ++ 
07-01 12:08:59.222  7662  7662 D irrcClient: IrrcClient ++ 
,07-01 12:08:59.222  7662  7662 D irrcClient: getIrrcService ++ 
07-01 12:08:59.222  7662  7662 D irrcClient: getIrrcService -- 
07-01 12:08:59.222  7662  7662 D irrcClient: IrrcClient -- 
07-01 12:08:59.222  7662  7662 W irrc_jni: IRRCPlayer_nativeInit -- 
07-01 12:08:59.230  7662  7662 D UEI.SmartControl: Services init done
07-01 12:08:59.231  7662  7693 I UEI.SmartControl: Device manager: loading config....
07-01 12:08:59.234  7662  7662 D UEI.SmartControl: QS Service init finished
,07-01 12:08:59.238  7662  7662 D UEI.SmartControl: QS Service version name: 0.1.73
07-01 12:08:59.239  7662  7662 D UEI.SmartControl: QS Service version code: 1073
07-01 12:08:59.240  7662  7662 D UEI.SmartControl: Service requested: Control
07-01 12:08:59.241  7662  7693 D UEI.SmartControl: Config is loaded...
07-01 12:08:59.246  7662  7692 D UEI.SmartControl:  ----- QS SDK is ready!!!
07-01 12:08:59.247  7662  7692 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-01 12:08:59.259  7662  7662 D UEI.SmartControl: Request IControl service: devices are loaded...
,07-01 12:08:59.262  7662  7662 D UEI.SmartControl: Internal service binding...
07-01 12:08:59.263  7662  7677 D UEI.SmartControl: -----IControl: 11
07-01 12:08:59.265  7662  7677 D UEI.SmartControl: Caller: com.lge.qremote
07-01 12:08:59.265  7662  7677 D UEI.SmartControl: ------------ IControl registerCallback...
07-01 12:08:59.266  7662  7677 I UEI.SmartControl: Registering callback...
07-01 12:08:59.267  7662  7678 D UEI.SmartControl: -----IControl: 19
07-01 12:08:59.268  7662  7678 D UEI.SmartControl: Caller: com.lge.qremote
07-01 12:08:59.269  7662  7678 I UEI.SmartControl: Registering Services Ready callback...
07-01 12:08:59.269  7662  7678 I UEI.SmartControl: Notify client services are ready...
07-01 12:08:59.271  7662  7677 D UEI.SmartControl: -----IControl: 8
,07-01 12:08:59.272  7662  7677 D UEI.SmartControl: Caller: com.lge.qremote
07-01 12:08:59.277  7644  7644 I AudioManager: getMode name:com.lge.qremote
07-01 12:08:59.282   968  1876 I ActivityManager: Killing 7441:com.lge.appbox.client/u0a11 (adj 15): empty #11
07-01 12:08:59.315   968  1876 I ActivityManager: Killing 7413:com.lge.lgdmsclient/1000 (adj 15): empty #12
,07-01 12:08:59.336   968  1861 W libprocessgroup: failed to open /acct/uid_10011/pid_7441/cgroup.procs: No such file or directory
,07-01 12:08:59.338   968  1941 W libprocessgroup: failed to open /acct/uid_1000/pid_7413/cgroup.procs: No such file or directory
07-01 12:08:59.341  7644  7644 I AudioManager: getMode name:com.lge.qremote
07-01 12:08:59.359  7644  7644 I AudioManager: getMode name:com.lge.qremote
,07-01 12:08:59.382   298   349 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-01 12:09:00.048  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-01 12:09:00.048  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-01 12:09:00.060  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
07-01 12:09:00.064  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-01 12:09:00.064  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
,07-01 12:09:00.069  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:09:00.070  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:09:03.504  1799  1799 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,07-01 12:09:03.507  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-01 12:09:03.507  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-01 12:09:03.508  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-01 12:09:03.508  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-01 12:09:03.531   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-01 12:09:03.566   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-01 12:09:03.570  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-01 12:09:03.570  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-01 12:09:03.570  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-01 12:09:03.570  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-01 12:09:03.571  1799  1799 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-01 12:09:03.612  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 305
07-01 12:09:03.612  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-01 12:09:03.612  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 305
,07-01 12:09:03.620  1799  1957 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-01 12:09:03.620  1799  1957 D LEDHandler: Battery Level Remaining: 100%
07-01 12:09:03.620  1799  1957 D LEDHandler: Battery Temp: 305, mChargingStatus=5, mChargingStop=false
07-01 12:09:03.622  1835  1835 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-01 12:09:03.622  1835  1835 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-01 12:09:03.627   968  1311 D WifiController: battery changed pluggedType: 2
,07-01 12:09:03.632  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-01 12:09:04.257  7662  7694 D UEI.SmartControl: Internal timer expired: 1
,07-01 12:09:04.387   298   349 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-01 12:09:05.362   968   999 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-01 12:09:05.362   968   999 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-01 12:09:05.362   968   999 D sensors_hal_Time: tsOffsetIs: Apps: 194366064931; DSPS: 6460938; Offset : -2811482352
,07-01 12:09:05.542   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-01 12:09:05.544  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-01 12:09:05.551  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-01 12:09:05.551  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-01 12:09:05.551  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-01 12:09:05.552  1799  1799 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-01 12:09:05.584  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 305
07-01 12:09:05.584  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-01 12:09:05.584  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 305
,07-01 12:09:05.588  1835  1835 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-01 12:09:05.589  1799  1957 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-01 12:09:05.589  1799  1957 D LEDHandler: Battery Level Remaining: 100%
07-01 12:09:05.590  1799  1957 D LEDHandler: Battery Temp: 305, mChargingStatus=5, mChargingStop=false
07-01 12:09:05.590  1835  1835 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-01 12:09:05.596   968  1311 D WifiController: battery changed pluggedType: 2
07-01 12:09:05.597  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,07-01 12:09:09.079   968  1284 D PowerManagerServiceEx: acquireWakeLockInternal: lock=193988055, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=968
,07-01 12:09:09.088   968  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2fd4411c type 2 when 198078 com.google.android.gms} when 198078
07-01 12:09:09.112  2397  7701 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-01 12:09:09.112  2397  7701 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-01 12:09:09.116  2397  7701 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-01 12:09:09.116  2397  7701 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-01 12:09:09.116   282  1043 E BandwidthController: [LG DATA] No such appUid: 10006
07-01 12:09:09.116   282  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-01 12:09:09.118   282  7702 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-01 12:09:09.118   282  7702 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-01 12:09:09.119   282  7702 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-01 12:09:09.120   968  1054 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,07-01 12:09:09.133   968   968 D PowerManagerServiceEx: releaseWakeLockInternal: lock=193988055 [*alarm*], flags=0x0
07-01 12:09:09.391   298   349 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-01 12:09:14.396   298   349 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-01 12:09:19.400   298   349 I ThermalEngine: Sensor:pa_therm0:33000 mC

```
