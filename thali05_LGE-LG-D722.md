#### Test 79426650eeb77ae_thali05_LGE-LG-D722 Logs


```
--------- beginning of main
08-05 01:29:16.465   290   352 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-05 01:29:17.335  6721  6721 D AndroidRuntime: 
08-05 01:29:17.335  6721  6721 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-05 01:29:17.345  6721  6721 D AndroidRuntime: CheckJNI is OFF
08-05 01:29:17.382  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 01:29:17.382  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 01:29:17.383  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-05 01:29:17.546  6721  6721 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-05 01:29:17.557   938  1726 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-05 01:29:17.643   938  1726 D ActivityManager: setTaskToReturnTo : TaskRecord{33e1a47a #255 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 01:29:17.644   938  1726 D ActivityManager: setTaskToReturnTo : TaskRecord{33e1a47a #255 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 01:29:17.673   938  1726 D WindowStateEx: AppWindowTokenEx init.. 
08-05 01:29:17.695   938  1043 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-05 01:29:17.710  1950  1950 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-05 01:29:17.716   938  1043 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-05 01:29:17.718   938  1726 D InputDispatcher: Focus left window: Window{19778492 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-05 01:29:17.719  6721  6721 D AndroidRuntime: Shutting down VM
08-05 01:29:17.737   938  1043 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-05 01:29:17.737   938  1043 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-05 01:29:17.752   938  1043 D SplitWindow: check instance of lgWin Window{2ecc48d2 u0 Starting com.test.thalitest}
08-05 01:29:17.772   938  1282 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6741 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-05 01:29:17.809  1950  1950 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-05 01:29:17.858  1950  1950 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-05 01:29:17.867   938  1922 I WindowStateAnimator: Starting window displayed
08-05 01:29:17.873   938  1041 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-05 01:29:17.878   938  1041 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-05 01:29:17.881   938  1041 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-05 01:29:17.881   938  1041 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-05 01:29:17.881   938  1041 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-05 01:29:17.881   938  1041 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1e578c0,  pkg=WindowManager.LayoutParams
08-05 01:29:17.881   938  1041 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-05 01:29:17.891  1368  1368 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-05 01:29:17.895  1368  1368 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-05 01:29:17.895  1368  1368 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-05 01:29:17.895  1368  1368 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-05 01:29:17.911  2034  2034 I HotwordDetector: Closing mic
08-05 01:29:17.915  2034  2372 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@31006e9d
08-05 01:29:17.915  2034  2372 V AudioRecord: stop()
08-05 01:29:17.915  2034  2372 D AudioRecord: AudioRecord->stop()
,08-05 01:29:17.918   275  1295 V AudioFlinger: RecordHandle::stop()
08-05 01:29:17.918   275  1295 V AudioFlinger: RecordThread::stop
08-05 01:29:17.935   275  1295 V AudioFlinger: Record stopped OK
08-05 01:29:17.936   275  1295 V AudioPolicyManager: stopInput() input 20
08-05 01:29:17.938   275  1295 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
08-05 01:29:17.938   275  1295 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
08-05 01:29:17.938   275  1062 V AudioPolicyService: AudioCommandThread() waking up
08-05 01:29:17.938   275  1062 V AudioPolicyService: AudioCommandThread() processing release audio patch
08-05 01:29:17.939   275  1062 V AudioFlinger::PatchPanel: releaseAudioPatch handle 21
08-05 01:29:17.939   275  1062 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
08-05 01:29:17.939   275  1062 V AudioFlinger: ThreadBase::setParameters() routing=0
08-05 01:29:17.939   275  1062 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-05 01:29:17.940   275  2638 V AudioFlinger: processConfigEvents_l() remaining events 1
08-05 01:29:17.940   275  2638 V AudioFlinger: processConfigEvents_l() DONE thread 0xb42a4000
08-05 01:29:17.942   275  2638 D audio_hw_primary: in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
08-05 01:29:17.962  6741  6741 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-05 01:29:17.983   275  2638 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
08-05 01:29:17.983   275  2638 V audio_hw_primary: disable_audio_route: enter: usecase(7)
08-05 01:29:17.983   275  2638 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
08-05 01:29:17.983   275  2638 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-05 01:29:17.985   275  2638 V audio_hw_primary: disable_audio_route: exit
08-05 01:29:17.985   275  2638 E audio_hw_primary: disable_snd_device: enter 144
08-05 01:29:17.985   275  2638 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
08-05 01:29:17.985   275  2638 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
08-05 01:29:17.988   275  2638 V audio_hw_primary: stop_input_stream: exit: status(0)
08-05 01:29:17.988   275  2638 V audio_hw_primary: in_standby: exit:  status(0)
08-05 01:29:17.988   275  2638 V AudioFlinger: RecordThread: loop stopping
08-05 01:29:17.988   275  1062 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 01:29:17.988   275  1295 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
08-05 01:29:17.989   275  1295 V AudioPolicyManager: removeAudioPatch() handle 20 af handle 21
08-05 01:29:17.989   275  1295 V AudioPolicyService: AudioCommandThread() adding update audio patch list
08-05 01:29:17.989   275  1295 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
08-05 01:29:17.989   275  1063 V AudioPolicyService: AudioCommandThread() waking up
08-05 01:29:17.989   275  1063 V AudioPolicyService: AudioCommandThread() processing update audio patch list
08-05 01:29:17.989   275  1063 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 01:29:17.990   275  1295 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 20 ,delay 0
08-05 01:29:17.990   275  1295 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
08-05 01:29:17.990   275  1062 V AudioPolicyService: AudioCommandThread() waking up
08-05 01:29:17.990   275  1062 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 20
08-05 01:29:17.990   275  1062 V AudioFlinger: setParameters(): io 20, keyvalue hotword_active=0, calling pid 275
08-05 01:29:17.990   275  1062 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
08-05 01:29:17.990   275  1062 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-05 01:29:17.991   275  2638 V AudioFlinger: RecordThread: loop starting
08-05 01:29:17.991   275  2638 V AudioFlinger: processConfigEvents_l() remaining events 1
08-05 01:29:17.991   275  2638 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
08-05 01:29:17.991   275  2638 V audio_hw_primary: in_set_parameters: exit: status(0)
08-05 01:29:17.991   275  2638 V AudioFlinger: processConfigEvents_l() DONE thread 0xb42a4000
08-05 01:29:17.991   275  2638 V AudioFlinger: RecordThread: loop stopping
08-05 01:29:17.991   275  1062 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 01:29:17.995  2034  2372 V AudioRecord: stop()
08-05 01:29:17.996  2034  2372 V AudioRecord: stop()
08-05 01:29:17.996  2034  2372 V AudioRecord: stop()
08-05 01:29:17.999   275  1355 V AudioFlinger: RecordHandle::stop()
08-05 01:29:17.999   275  1355 V AudioFlinger: RecordThread::stop
08-05 01:29:17.999   275  1295 V AudioFlinger: releasing 19 from 2034 for -1
08-05 01:29:17.999   275  1355 V AudioPolicyManager: releaseInput() 20
08-05 01:29:17.999   275  1295 V AudioFlinger:  decremented refcount to 0
08-05 01:29:17.999   275  1295 V AudioFlinger: purging stale effects
08-05 01:29:17.999   275  1355 V AudioPolicyManager: closeInput(20)
08-05 01:29:17.999   275  1355 V AudioFlinger: closeInput() 20
08-05 01:29:17.999   275  1355 V AudioSystem: ioConfigChanged() event 4, ioHandle 20
08-05 01:29:17.999   938  1922 V AudioSystem: ioConfigChanged() event 4, ioHandle 20
08-05 01:29:17.999   275  1355 V AudioFlinger: ThreadBase::exit
08-05 01:29:17.999  1368  2371 V AudioSystem: ioConfigChanged() event 4, ioHandle 20
08-05 01:29:17.999  3154  3170 V AudioSystem: ioConfigChanged() event 4, ioHandle 20
08-05 01:29:17.999  2034  2367 V AudioSystem: ioConfigChanged() event 4, ioHandle 20
08-05 01:29:17.999  1779  2314 V AudioSystem: ioConfigChanged() event 4, ioHandle 20
08-05 01:29:17.999  2081  3519 V AudioSystem: ioConfigChanged() event 4, ioHandle 20
08-05 01:29:18.000  2034  2375 I HotwordRecognitionRnr: Stopping hotword detection.
08-05 01:29:18.000   275  2638 V AudioFlinger: RecordThread: loop starting
08-05 01:29:18.000   275  2638 V AudioFlinger: RecordThread 0xb42a4000 exiting
08-05 01:29:18.000   275  1355 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb4036520)
08-05 01:29:18.000   275  1355 D audio_hw_primary: in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
08-05 01:29:18.000   275  1355 V audio_hw_primary: in_standby: exit:  status(0)
08-05 01:29:18.001   275  1355 V AudioPolicyService: AudioCommandThread() adding update audio port list
08-05 01:29:18.001   275  1355 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
08-05 01:29:18.001   275  1355 V AudioPolicyManager: releaseInput() exit
08-05 01:29:18.001   275  1355 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
08-05 01:29:18.001   275  1355 V AudioFlinger: removeClient_l() pid 2034, calling pid 275
08-05 01:29:18.001   275  1063 V AudioPolicyService: AudioCommandThread() waking up
08-05 01:29:18.002   275  1063 V AudioPolicyService: AudioCommandThread() processing update audio port list
08-05 01:29:18.002   275  1063 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 01:29:18.003  2034  2630 I HotwordRecognitionRnr: Hotword detection finished
08-05 01:29:18.064  6741  6741 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-05 01:29:18.125  6741  6741 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 5162-5168)
08-05 01:29:18.125  6741  6741 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 01:29:18.154  6741  6741 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3c357a30}
08-05 01:29:18.155  6741  6741 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 01:29:18.161  6741  6741 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 01:29:18.177  6741  6741 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-05 01:29:18.179  6741  6741 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 01:29:18.183  6741  6741 E SysUtils: ApplicationContext is null in ApplicationStatus
08-05 01:29:18.251  6741  6741 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-05 01:29:18.259  6741  6741 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-05 01:29:18.259  6741  6741 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-05 01:29:18.263  6741  6741 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 01:29:18.263  6741  6741 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 01:29:18.263  6741  6741 I Adreno-EGL: Build Date: 03/02/15 Mon
08-05 01:29:18.263  6741  6741 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-05 01:29:18.263  6741  6741 I Adreno-EGL: Remote Branch: 
08-05 01:29:18.263  6741  6741 I Adreno-EGL: Local Patches: 
08-05 01:29:18.263  6741  6741 I Adreno-EGL: Reconstruct Branch: 
08-05 01:29:18.382   275   275 V AudioPolicyService: registerClient() client 0xb57e7fe0, uid 10030
08-05 01:29:18.388  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 01:29:18.388  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 01:29:18.388  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-05 01:29:18.423   938  1042 D BluetoothManagerService: Message: 20
08-05 01:29:18.424   938  1042 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28a9a1cd:true
08-05 01:29:18.429  2081  2099 D BluetoothAdapterService(598479918): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@e6227f4
08-05 01:29:18.442   938  1018 W ProcessCpuTracker: Skipping unknown process pid 6763
08-05 01:29:18.442   938  1018 W ProcessCpuTracker: Skipping unknown process pid 6764
08-05 01:29:18.443   938  1018 W ProcessCpuTracker: Skipping unknown process pid 6767
08-05 01:29:18.443   938  1018 W ProcessCpuTracker: Skipping unknown process pid 6770
08-05 01:29:18.444   938  1018 W ProcessCpuTracker: Skipping unknown process pid 6778
08-05 01:29:18.548  6741  6741 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 01:29:18.563  6741  6741 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-05 01:29:18.571  6741  6741 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-05 01:29:18.575  6741  6741 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-05 01:29:18.575  6741  6741 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-05 01:29:18.590  6741  6741 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-05 01:29:18.598  6741  6741 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 01:29:18.598  6741  6741 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 01:29:18.645  6741  6741 I Activity: Activity.onPostResume() called 
,08-05 01:29:18.653  6741  6803 D OpenGLRenderer: Render dirty regions requested: true
08-05 01:29:18.653  6741  6803 I OpenGLRenderer: Initialized EGL, version 1.4
08-05 01:29:18.659  6741  6803 D OpenGLRenderer: Enabling debug mode 0
,08-05 01:29:18.675  6741  6741 D Atlas   : Validating map...
,08-05 01:29:18.679   938   964 D SplitWindow: check instance of lgWin Window{33983d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 01:29:18.686  6741  6786 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-05 01:29:18.726   938   964 D InputDispatcher: Focus entered window: Window{33983d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 01:29:18.793   938  2042 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-05 01:29:18.797   938  1043 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s63ms
08-05 01:29:18.797   938  1043 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{78c642b u0 com.test.thalitest/.MainActivity t255} time:135840
08-05 01:29:18.819  6741  6741 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@8bd70ea time:135863
08-05 01:29:18.901  6741  6741 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6741
08-05 01:29:19.099  6741  6741 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-05 01:29:19.479  6741  6810 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426119424
,08-05 01:29:19.490  6741  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 01:29:19.490  6741  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 01:29:19.490  6741  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 01:29:19.490  6741  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 01:29:19.490  6741  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-05 01:29:19.490  6741  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37ae5daf added. We now have 1 listener(s)
08-05 01:29:19.493   938  1726 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 01:29:19.496  6741  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,08-05 01:29:19.500  6741  6810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-05 01:29:19.503  6741  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 01:29:19.503  6741  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 01:29:19.509  6741  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 01:29:19.509  6741  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 01:29:19.509  6741  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 01:29:19.509  6741  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-05 01:29:19.509  6741  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 01:29:19.509  6741  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 01:29:19.509  6741  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 01:29:19.509  6741  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 01:29:19.509  6741  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 01:29:19.509  6741  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 01:29:19.509  6741  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 01:29:19.509  6741  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 01:29:19.509  6741  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 01:29:19.509  6741  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-05 01:29:19.509  6741  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@108be89a added. We now have 1 listener(s)
,08-05 01:29:19.511  6741  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 01:29:19.524  6741  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 01:29:19.524  6741  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-05 01:29:19.527  6741  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-05 01:29:19.527  6741  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-05 01:29:19.527  6741  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-05 01:29:19.531  6741  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 01:29:19.532   938  1922 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 01:29:19.532  6741  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-05 01:29:19.541  2081  2101 D BluetoothAdapterService(598479918): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@e6227f4
08-05 01:29:19.542  6741  6810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 01:29:19.542  6741  6810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 01:29:19.542  6741  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 01:29:19.542  6741  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 01:29:19.542  6741  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 01:29:19.542  6741  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 01:29:19.542  6741  6810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 01:29:19.542  6741  6810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 01:29:19.542  6741  6810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 01:29:19.542  6741  6810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-05 01:29:19.542  6741  6810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 01:29:19.543  6741  6810 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 01:29:19.702  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 01:29:19.706  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 01:29:19.711  6741  6741 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-05 01:29:19.744  6741  6755 I art     : CheckpointMarkThreadRoots callback created = 0xb06453f0
,08-05 01:29:19.786  6741  6755 I art     : CheckpointMarkThreadRoots callback created = 0xb06453b0
,08-05 01:29:20.388  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 01:29:20.388  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-05 01:29:20.388  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-05 01:29:20.515  6741  6829 W jxcore-log: Initializing JXcore engine
08-05 01:29:20.515  6741  6829 W jxcore-log: JXcore engine is ready
,08-05 01:29:20.573  6829  6829 W Thread-804: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7655]" dev="sockfs" ino=7655 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-05 01:29:20.573  6829  6829 W Thread-804: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-05 01:29:20.573  6829  6829 W Thread-804: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5800]" dev="sockfs" ino=5800 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-05 01:29:20.573  6829  6829 W Thread-804: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-05 01:29:20.573  6829  6829 W Thread-804: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-05 01:29:20.573  6829  6829 W Thread-804: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[29948]" dev="sockfs" ino=29948 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-05 01:29:20.599  6741  6829 W jxcore-log: Starting JXcore engine
,08-05 01:29:20.733  6741  6829 W jxcore-log: Platform android
08-05 01:29:20.733  6741  6829 W jxcore-log: 
08-05 01:29:20.734  6741  6829 W jxcore-log: Process ARCH arm
08-05 01:29:20.734  6741  6829 W jxcore-log: 
,08-05 01:29:21.051  6741  6829 I jxcore-log: JXcore Cordova bridge is ready!
08-05 01:29:21.051  6741  6829 I jxcore-log: 
08-05 01:29:21.051  6741  6829 W jxcore-log: JXcore engine is started
,08-05 01:29:21.058  6741  6810 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-05 01:29:21.060  6741  6741 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-05 01:29:21.390  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 01:29:21.390  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 01:29:21.390  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-05 01:29:21.469   290   352 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-05 01:29:22.932   938  1285 V AlarmManager: RTC_WAKEUP set : Alarm{13edabc4 type 0 when 1470353362926 com.google.android.googlequicksearchbox} when 1470353362926
,08-05 01:29:23.392  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 01:29:23.392  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-05 01:29:23.392  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-05 01:29:26.474   290   352 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-05 01:29:26.931  1912  1912 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,08-05 01:29:26.935  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 01:29:26.935  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 01:29:26.935  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-05 01:29:26.936  1912  1912 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.105 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-08-05 01:29:26.935 DNS addrs= 192.168.1.1, 0.0.0.0, 
08-05 01:29:27.399  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 01:29:27.399  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 01:29:27.399  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,08-05 01:29:29.401  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 01:29:29.402  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 01:29:29.402  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-05 01:29:29.560   938  1059 I PowerManagerService: ALS enabled for SRE
08-05 01:29:29.561   938  1059 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26604 ms ago)
,08-05 01:29:29.582   938  1345 D qdlights: set_light_backlight: 254
,08-05 01:29:29.593   938  1345 D qdlights: set_light_backlight: 251
08-05 01:29:29.616   938  1345 D qdlights: set_light_backlight: 248
,08-05 01:29:29.627   938  1345 D qdlights: set_light_backlight: 244
08-05 01:29:29.643   938  1345 D qdlights: set_light_backlight: 241
,08-05 01:29:29.660   938  1345 D qdlights: set_light_backlight: 238
,08-05 01:29:29.676   938  1345 D qdlights: set_light_backlight: 234
,08-05 01:29:29.693   938  1345 D qdlights: set_light_backlight: 231
,08-05 01:29:29.710   938  1345 D qdlights: set_light_backlight: 228
,08-05 01:29:29.726   938  1345 D qdlights: set_light_backlight: 224
,08-05 01:29:29.743   938  1345 D qdlights: set_light_backlight: 221
,08-05 01:29:29.760   938  1345 D qdlights: set_light_backlight: 218
,08-05 01:29:29.777   938  1345 D qdlights: set_light_backlight: 214
,08-05 01:29:29.793   938  1345 D qdlights: set_light_backlight: 211
,08-05 01:29:29.810   938  1345 D qdlights: set_light_backlight: 208
,08-05 01:29:29.827   938  1345 D qdlights: set_light_backlight: 204
,08-05 01:29:29.843   938  1345 D qdlights: set_light_backlight: 201
,08-05 01:29:29.860   938  1345 D qdlights: set_light_backlight: 198
,08-05 01:29:29.877   938  1345 D qdlights: set_light_backlight: 194
,08-05 01:29:29.893   938  1345 D qdlights: set_light_backlight: 191
,08-05 01:29:29.910   938  1345 D qdlights: set_light_backlight: 188
,08-05 01:29:29.926   938  1345 D qdlights: set_light_backlight: 184
,08-05 01:29:29.943   938  1345 D qdlights: set_light_backlight: 181
,08-05 01:29:29.951  1912  1912 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
08-05 01:29:29.954  1912  1912 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-52 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.105 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-08-05 01:29:29.954 DNS addrs= 192.168.1.1, 0.0.0.0, 
08-05 01:29:29.956  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 01:29:29.956  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 01:29:29.956  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-05 01:29:29.960   938  1345 D qdlights: set_light_backlight: 178
08-05 01:29:29.976   938  1345 D qdlights: set_light_backlight: 174
,08-05 01:29:29.993   938  1345 D qdlights: set_light_backlight: 171
08-05 01:29:30.010   938  1345 D qdlights: set_light_backlight: 168
,08-05 01:29:30.026   938  1345 D qdlights: set_light_backlight: 164
,08-05 01:29:30.043   938  1345 D qdlights: set_light_backlight: 161
,08-05 01:29:30.060   938  1345 D qdlights: set_light_backlight: 158
,08-05 01:29:30.076   938  1345 D qdlights: set_light_backlight: 154
,08-05 01:29:30.093   938  1345 D qdlights: set_light_backlight: 151
,08-05 01:29:30.110   938  1345 D qdlights: set_light_backlight: 148
,08-05 01:29:30.126   938  1345 D qdlights: set_light_backlight: 144
,08-05 01:29:30.143   938  1345 D qdlights: set_light_backlight: 141
,08-05 01:29:30.160   938  1345 D qdlights: set_light_backlight: 138
,08-05 01:29:30.177   938  1345 D qdlights: set_light_backlight: 134
,08-05 01:29:30.193   938  1345 D qdlights: set_light_backlight: 131
,08-05 01:29:30.210   938  1345 D qdlights: set_light_backlight: 128
,08-05 01:29:30.226   938  1345 D qdlights: set_light_backlight: 124
,08-05 01:29:30.243   938  1345 D qdlights: set_light_backlight: 121
,08-05 01:29:30.260   938  1345 D qdlights: set_light_backlight: 118
,08-05 01:29:30.276   938  1345 D qdlights: set_light_backlight: 114
,08-05 01:29:30.293   938  1345 D qdlights: set_light_backlight: 111
,08-05 01:29:30.310   938  1345 D qdlights: set_light_backlight: 108
,08-05 01:29:30.326   938  1345 D qdlights: set_light_backlight: 104
,08-05 01:29:30.343   938  1345 D qdlights: set_light_backlight: 101
,08-05 01:29:30.360   938  1345 D qdlights: set_light_backlight: 98
,08-05 01:29:30.376   938  1345 D qdlights: set_light_backlight: 94
,08-05 01:29:30.393   938  1345 D qdlights: set_light_backlight: 91
,08-05 01:29:30.408  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 01:29:30.408  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 01:29:30.408  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-05 01:29:30.410   938  1345 D qdlights: set_light_backlight: 88
08-05 01:29:30.428   938  1345 D qdlights: set_light_backlight: 84
,08-05 01:29:30.443   938  1345 D qdlights: set_light_backlight: 81
,08-05 01:29:30.460   938  1345 D qdlights: set_light_backlight: 78
,08-05 01:29:30.476   938  1345 D qdlights: set_light_backlight: 74
,08-05 01:29:30.493   938  1345 D qdlights: set_light_backlight: 71
,08-05 01:29:30.510   938  1345 D qdlights: set_light_backlight: 68
,08-05 01:29:30.526   938  1345 D qdlights: set_light_backlight: 64
,08-05 01:29:30.543   938  1345 D qdlights: set_light_backlight: 61
,08-05 01:29:30.560   938  1345 D qdlights: set_light_backlight: 58
,08-05 01:29:30.576   938  1345 D qdlights: set_light_backlight: 54
,08-05 01:29:30.593   938  1345 D qdlights: set_light_backlight: 51
,08-05 01:29:30.610   938  1345 D qdlights: set_light_backlight: 48
,08-05 01:29:30.626   938  1345 D qdlights: set_light_backlight: 44
,08-05 01:29:30.643   938  1345 D qdlights: set_light_backlight: 41
,08-05 01:29:30.660   938  1345 D qdlights: set_light_backlight: 38
,08-05 01:29:30.676   938  1345 D qdlights: set_light_backlight: 34
,08-05 01:29:30.693   938  1345 D qdlights: set_light_backlight: 31
,08-05 01:29:30.710   938  1345 D qdlights: set_light_backlight: 28
,08-05 01:29:30.726   938  1345 D qdlights: set_light_backlight: 24
,08-05 01:29:30.743   938  1345 D qdlights: set_light_backlight: 21
,08-05 01:29:30.760   938  1345 D qdlights: set_light_backlight: 18
,08-05 01:29:30.776   938  1345 D qdlights: set_light_backlight: 14
,08-05 01:29:30.793   938  1345 D qdlights: set_light_backlight: 11
,08-05 01:29:30.810   938  1345 D qdlights: set_light_backlight: 10
,08-05 01:29:31.478   290   352 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-05 01:29:32.410  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 01:29:32.411  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 01:29:32.411  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-05 01:29:33.413  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 01:29:33.413  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 01:29:33.413  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-05 01:29:35.417  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 01:29:35.417  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 01:29:35.417  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-05 01:29:36.029   938   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-05 01:29:36.029   938   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-05 01:29:36.029   938   981 D sensors_hal_Time: tsOffsetIs: Apps: 153072541405; DSPS: 5107433; Offset : -2806194605
,08-05 01:29:36.419  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 01:29:36.419  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 01:29:36.419  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-05 01:29:36.483   290   352 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-05 01:29:36.556   938  1059 I PowerManagerService: ALS enabled for SRE
08-05 01:29:36.556   938  1059 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33600 ms ago)
,08-05 01:29:36.557   938  1059 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
08-05 01:29:36.568   938  1059 I PowerManagerService: ALS enabled for SRE
,08-05 01:29:36.571   938  1059 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33614 ms ago)
08-05 01:29:36.575   938  1059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
08-05 01:29:36.580   938  1059 I PowerManagerService: Sleeping (uid 1000)...
08-05 01:29:36.580   938  1059 D LPWGController: [updateScreenState] screen on = false
,08-05 01:29:36.584   938  1059 D LPWGController: disable proximity sensor
08-05 01:29:36.586   938  1059 D LPWGController: enable proximity sensor
08-05 01:29:36.592   938  1059 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@ffbc030] by com.android.server.power.ProximitySensorListener.enable():120
,08-05 01:29:36.600   938  1059 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
08-05 01:29:36.600   938  1059 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
08-05 01:29:36.600   938  1059 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
08-05 01:29:36.600   938  1059 I sensors_hal_Ctx: activate: handle is 48, enable
08-05 01:29:36.600   938  1059 V sensors_hal_Ctx: activate sensors is 1400000000000
08-05 01:29:36.601   938  1059 D sensors_hal_Thresh: enable: handle=48
08-05 01:29:36.601   938  1059 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
08-05 01:29:36.601   938  1059 D sensors_hal_Util: waitForResponse: timeout=1000
08-05 01:29:36.605   938   982 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,08-05 01:29:36.605   938   982 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
08-05 01:29:36.606   938  1059 D sensors_hal_Thresh: enable: Received response: 0
08-05 01:29:36.606   938  1059 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33649 ms ago)
08-05 01:29:36.629   938  1059 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 01:29:36.629   938  1059 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 01:29:36.629   938  1059 I Adreno-EGL: Build Date: 03/02/15 Mon
08-05 01:29:36.629   938  1059 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-05 01:29:36.629   938  1059 I Adreno-EGL: Remote Branch: 
08-05 01:29:36.629   938  1059 I Adreno-EGL: Local Patches: 
08-05 01:29:36.629   938  1059 I Adreno-EGL: Reconstruct Branch: 
,08-05 01:29:36.676   245   282 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1084 us)
,08-05 01:29:36.834   427   968 I Sensors : sns_pwr.c(273):acquiring wakelock
08-05 01:29:36.834   938   982 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,08-05 01:29:36.836   938   982 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
08-05 01:29:36.836   938   982 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
08-05 01:29:36.836   938   982 D sensors_hal_Thresh: processInd: handle 48, count=1
08-05 01:29:36.836   938   982 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
08-05 01:29:36.836   938   982 I sensors_hal_Thresh: processInd : proximity state changed - NEAR
08-05 01:29:36.837   938  1020 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:0.000000 y:-0.000007 z:0.000000
08-05 01:29:36.837   938  1020 D sensors_hal_Ctx: poll: count: 256
08-05 01:29:36.837   938  1020 I sensors_hal_Ctx: poll: released wakelock sensor_ind
08-05 01:29:36.837   938  1020 D sensors_hal_Util: waitForResponse: timeout=0
08-05 01:29:36.839   938  1059 D LPWGController: proximity onSensorChanged : proximity = 0, mSensorCovered=false, isFar=false
08-05 01:29:36.839   938  1059 I LPWGController: current mode = 0  value = 1 0
08-05 01:29:36.840   938  1059 I LPWGController: [setLPWGmode2] current mode = 0  value = 9 0 1 0 0
08-05 01:29:36.938   938  1059 I LPWGController: [setLPWGmode2] current mode = 0  value = 9 0 0 0 0
,08-05 01:29:37.195   938  1345 D qdlights: set_light_backlight: 0
,08-05 01:29:37.213   938  1059 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,08-05 01:29:37.217   938  1059 I sensors_hal_Ctx: activate: handle is 46, disable
08-05 01:29:37.217   938  1059 V sensors_hal_Ctx: activate sensors is 1000000000000
08-05 01:29:37.217   938  1059 D sensors_hal_LP2: enable: handle=46
08-05 01:29:37.217   938  1059 D sensors_hal_LP2: enable: Disabling sensor handle=46
08-05 01:29:37.217   938  1059 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
08-05 01:29:37.219   245   245 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
08-05 01:29:37.220   245   245 D qdhwcomposer: hwc_blank: Blanking display: 0
08-05 01:29:37.224   938  1043 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
08-05 01:29:37.225   938   938 V ActivityManager: Display changed displayId=0
,08-05 01:29:37.276  1779  1779 D DSDPConnection: Display #0 changed.
,08-05 01:29:37.278   938  1008 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
08-05 01:29:37.278   938  1008 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,08-05 01:29:37.395   245   245 D qdhwcomposer: hwc_blank: Done blanking display: 0
08-05 01:29:37.396   245   601 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-05 01:29:37.397   938  1345 D SurfaceControl: Excessive delay in setPowerMode(): 176ms
08-05 01:29:37.398   938  1345 I QCOM PowerHAL: Got set_interactive hint
08-05 01:29:37.410  1368  2468 D KeyguardViewMediator: onScreenTurnedOff(3)
,08-05 01:29:37.416  6741  6741 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-05 01:29:37.418  6741  6741 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-05 01:29:37.428  1328  1344 D SmartCoverViewMediator: onScreenTurnedOff(3)
08-05 01:29:37.430  6741  6741 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@29967b06 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@16c86a9e, 16908290=android.view.AbsSavedState$1@16c86a9e}, android:focusedViewId=100}]}]
08-05 01:29:37.430  6741  6741 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-05 01:29:37.430  6741  6741 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-05 01:29:37.430  6741  6741 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-05 01:29:37.440  1328  1344 D SmartCoverViewMediator: notifyScreenOffLocked
,08-05 01:29:37.442  1368  2468 D KeyguardViewMediator: notifyScreenOffLocked
08-05 01:29:37.443  1328  1328 D SmartCoverViewMediator: handleNotifyScreenOFF
08-05 01:29:37.467  1368  2468 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
,08-05 01:29:37.468  1368  1368 D KeyguardViewMediator: handleNotifyScreenOff
08-05 01:29:37.506   938   938 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
,08-05 01:29:37.510   938  1307 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
08-05 01:29:37.512  1368  1368 D ScreenTurnOffBySensor: unregisterProximitySensor
08-05 01:29:37.513   275  1355 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 938
08-05 01:29:37.513   275  1355 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-05 01:29:37.513   275  1355 V voice   : voice_set_parameters: enter: screen_state=on
08-05 01:29:37.514   275  1355 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
08-05 01:29:37.514   275  1355 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-05 01:29:37.514   275  1355 V voice   : voice_set_parameters: exit with code(0)
08-05 01:29:37.515   275  1355 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
08-05 01:29:37.515   275  1355 V msm8974_platform: platform_set_parameters: enter: screen_state=on
08-05 01:29:37.515   275  1355 V msm8974_platform: platform_set_parameters: exit with code(0)
08-05 01:29:37.515   275  1355 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-05 01:29:37.515   275  1355 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
08-05 01:29:37.515   275  1355 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-05 01:29:37.515   275  1355 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-05 01:29:37.524  1368  1368 D StatusBarWindowView: onScreenTurnedOff why = 3
,08-05 01:29:37.529  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 01:29:37.531  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
08-05 01:29:37.831   938  1015 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,08-05 01:29:37.837  1912  1912 I QCNEJ   : |CORE| sendScreenState: state:true
08-05 01:29:37.881   938  2386 D SplitWindow: check instance of lgWin Window{2c9649cf u0 SearchPanel}
,08-05 01:29:37.892  1875  2046 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
08-05 01:29:37.894  1875  2046 D LEDService: stopPatternFlashing()
,08-05 01:29:37.896  1875  2046 D qdlights: set_light_notifications: 0,0,0,0,3
08-05 01:29:37.899  1875  2046 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-05 01:29:37.899  1875  2046 D qdlights: set_light_notifications: 0,0,0,0,3
08-05 01:29:37.900  1875  2046 I LEDService: updateLightsLocked : turn off led
08-05 01:29:37.900  1875  2046 D qdlights: set_light_notifications: 0,0,0,0,3
08-05 01:29:37.905  1875  2046 D LEDHandler: RESTART MSG
08-05 01:29:37.911   938  1282 D InputDispatcher: Window went away: Window{27035e6b u0 SearchPanel}
,08-05 01:29:37.916  1368  1368 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
08-05 01:29:37.935  1368  1368 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,08-05 01:29:37.944  1850  1850 D LNfcService: action : android.intent.action.SCREEN_ON
08-05 01:29:37.950  1875  1875 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,08-05 01:29:37.953  1875  1875 D Cliptray Service: lockStatus = 0
08-05 01:29:37.953  1850  6895 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
08-05 01:29:37.953  1850  6895 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
08-05 01:29:37.953  1850  6895 D LNfcService: isRequireNfcCRouting() return true
08-05 01:29:37.953  1850  6895 D LNfcService: isHCERoutingtoHost() return : true
08-05 01:29:37.953  1850  6895 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-05 01:29:37.953  1850  6895 D NfcService: mEnableLPD: true
08-05 01:29:37.953  1850  6895 D NfcService: mEnableReader: false
08-05 01:29:37.953  1850  6895 D NfcService: mEnableHostRouting: true
08-05 01:29:37.953  1850  6895 D NfcService: newParams.techmask= mTechMask: default
08-05 01:29:37.953  1850  6895 D NfcService: mEnableLPD: true
08-05 01:29:37.953  1850  6895 D NfcService: mEnableReader: false
08-05 01:29:37.953  1850  6895 D NfcService: mEnableHostRouting: true
08-05 01:29:37.953  1850  6895 D NfcService: screenState= 3
08-05 01:29:37.953  1850  6895 D NfcService: Discovery configuration equal, not updating.
08-05 01:29:37.967   938   938 D Ulp_jni : JNI:system_update. Event-0
,08-05 01:29:37.988  1779  1779 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
08-05 01:29:38.020   938   938 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 01:29:38.020   938   938 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 01:29:38.020   938   938 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
,08-05 01:29:38.025  2875  2875 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:29:38
,08-05 01:29:38.028  2875  2875 D WeatherService: 2 : ACTION screen on
08-05 01:29:38.029  2875  2875 D WeatherService: 2 : shouldTimeTickRegistered : false
08-05 01:29:38.034  2875  2875 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 01:29:38.034  2875  2875 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:29:38
08-05 01:29:38.046  4153  4153 D AppCleanupService: android.intent.action.SCREEN_ON
,08-05 01:29:38.082   275   275 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 938
08-05 01:29:38.082   275   275 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-05 01:29:38.082   275   275 V voice   : voice_set_parameters: enter: screen_state=off
08-05 01:29:38.082   275   275 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
08-05 01:29:38.082   275   275 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-05 01:29:38.082   275   275 V voice   : voice_set_parameters: exit with code(0)
08-05 01:29:38.082   275   275 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
08-05 01:29:38.082   275   275 V msm8974_platform: platform_set_parameters: enter: screen_state=off
08-05 01:29:38.082   275   275 V msm8974_platform: platform_set_parameters: exit with code(0)
08-05 01:29:38.082   275   275 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-05 01:29:38.082   275   275 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-05 01:29:38.082   275   275 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-05 01:29:38.084   938  1312 D WifiController: CMD_SCREEN_OFF 
08-05 01:29:38.084   938  1312 D WifiController: shouldWifiStayAwake TRUE
08-05 01:29:38.091  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
,08-05 01:29:38.091   938  1015 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,08-05 01:29:38.099  1912  1912 I QCNEJ   : |CORE| sendScreenState: state:false
,08-05 01:29:38.106  1875  2046 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
08-05 01:29:38.106  1875  2046 D LEDService: stopPatternFlashing()
08-05 01:29:38.106  1875  2046 D qdlights: set_light_notifications: 0,0,0,0,3
08-05 01:29:38.108  1875  2046 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-05 01:29:38.108  1875  2046 D qdlights: set_light_notifications: 0,0,0,0,3
08-05 01:29:38.109  1875  2046 I LEDService: updateLightsLocked : turn on led
08-05 01:29:38.110  1875  2046 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
08-05 01:29:38.110  1875  2046 E LEDService: Can't handle this request of patternId:0
08-05 01:29:38.110  1875  2046 D LEDHandler: RESTART MSG
08-05 01:29:38.111  1875  1875 D VolumeVibrator: clear
08-05 01:29:38.112  1850  1850 D LNfcService: action : android.intent.action.SCREEN_OFF
08-05 01:29:38.113  1875  1875 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
08-05 01:29:38.116  1850  2184 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
,08-05 01:29:38.140  1950  1950 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,08-05 01:29:38.153  1779  1779 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,08-05 01:29:38.163   938   938 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 01:29:38.163   938   938 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 01:29:38.163   938   938 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
08-05 01:29:38.165  2875  2875 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:29:38
08-05 01:29:38.165  2875  2875 D WeatherService: 2 : ACTION screen off
,08-05 01:29:38.167  2875  2875 D WeatherService: 2 : TimeTick Receiver Unregister
08-05 01:29:38.168  2875  2875 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:29:38
08-05 01:29:38.172  4153  4153 D AppCleanupService: android.intent.action.SCREEN_OFF
08-05 01:29:38.174  4153  6904 D AppCleanupService: AppUsageStatsSaveTask
,08-05 01:29:38.219  1850  2667 E NxpNfcJni: getReconnectState = 0x0
,08-05 01:29:38.222  1850  2184 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-05 01:29:38.222  1850  2184 D LCardEmulationManager: getDefaultRoute
08-05 01:29:38.223  1850  2184 D LNfcService: isRequireNfcCRouting() return true
08-05 01:29:38.223  1850  2184 D LNfcService: isHCERoutingtoHost() return : true
08-05 01:29:38.223  1850  2184 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-05 01:29:38.223  1850  2184 D NfcService: mEnableLPD: true
08-05 01:29:38.223  1850  2184 D NfcService: mEnableReader: false
08-05 01:29:38.223  1850  2184 D NfcService: mEnableHostRouting: true
08-05 01:29:38.223  1850  2184 D NfcService: newParams.techmask= mTechMask: 0
08-05 01:29:38.223  1850  2184 D NfcService: mEnableLPD: true
08-05 01:29:38.223  1850  2184 D NfcService: mEnableReader: false
08-05 01:29:38.223  1850  2184 D NfcService: mEnableHostRouting: true
08-05 01:29:38.223  1850  2184 D NfcService: screenState= 1
08-05 01:29:38.266  1850  2667 E NxpNfcJni: getReconnectState = 0x0
,08-05 01:29:38.334   427   444 I Sensors : sns_pwr.c(301):releasing wakelock
,08-05 01:29:41.490   290   352 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-05 01:29:42.460   938  1285 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2b94af5c type 2 when 159490 com.android.systemui} when 159490
,08-05 01:29:42.464  1368  1368 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,08-05 01:29:42.474  1779  2552 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
08-05 01:29:42.478  1779  2552 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-05 01:29:42.478  1779  2552 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-05 01:29:42.481  1779  2552 V TelecomServiceImpl: getCallState : 0
08-05 01:29:42.482  1779  2551 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
08-05 01:29:42.482  1779  2551 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-05 01:29:42.482  1779  2551 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-05 01:29:42.484  1368  1368 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
,08-05 01:29:42.485  1368  1368 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
08-05 01:29:42.715  6741  6829 E jxcore  : Error!: Cannot find module '../thalilogger'
08-05 01:29:42.715  6741  6829 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w._oldRes","_lineNumber":"802","_columnNumber":"9","_msg":"    at $w._oldRes@module.js:802:9"},{"_fileName":"module.js","_functionName":"$w._resolveFilename","_lineNumber":"1771","_columnNumber":"1","_msg":"    at $w._resolveFilename@module.js:1771:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"362","_columnNumber":"4","_msg":"    at $w._load@module.js:362:4"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js","_functionName":"","_lineNumber":"5","_columnNumber":"14","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"}]
,08-05 01:29:42.721  6741  6741 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "Cannot find module '../thalilogger'\nError: Cannot find module '../thalilogger'\n    at $w._oldRes@module.js:802:9\n    at $w._resolveFilename@module.js:1771:1\n    at $w._load@module.js:362:4\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"", source: file:///android_asset/www/js/thali_main.js (57)
08-05 01:29:42.721  6741  6741 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,08-05 01:29:42.729   938  1922 D InputDispatcher: Focus left window: Window{33983d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 01:29:42.733   938  1922 I ActivityManager: Killing 6324:com.android.gallery3d/u0a23 (adj 15): empty #11
08-05 01:29:42.750   938   964 W libprocessgroup: failed to open /acct/uid_10023/pid_6324/cgroup.procs: No such file or directory
,08-05 01:29:42.752  6741  6810 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 29ms. Plugin should use CordovaInterface.getThreadPool().
08-05 01:29:42.754  6741  6741 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-05 01:29:42.754  6741  6741 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-05 01:29:42.756  6741  6741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 01:29:42.756  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 01:29:42.757  6741  6741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 01:29:42.759  6741  6741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 01:29:42.762   938   938 V ActivityManager: Display changed displayId=0
08-05 01:29:42.763  6741  6741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37ae5daf removed from the list
08-05 01:29:42.763  6741  6741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 01:29:42.763  6741  6741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@108be89a removed from the list
08-05 01:29:42.763  6741  6741 D io.jxcore.node.ConnectivityMonitor: stop
08-05 01:29:42.763  6741  6741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-05 01:29:42.767  1779  1779 D DSDPConnection: Display #0 changed.
08-05 01:29:42.780  6741  6741 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-05 01:29:42.784  1950  1950 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
08-05 01:29:42.808  1950  1950 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,08-05 01:29:42.849  1950  1950 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-05 01:29:42.852  1950  1950 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-05 01:29:42.852  1950  1950 I Activity: Activity.onPostResume() called 
08-05 01:29:42.858  1950  1950 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-05 01:29:42.858   938  1922 D InputDispatcher: Window went away: Window{33983d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-05 01:29:42.867  2875  2875 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 1:29:42
08-05 01:29:42.873  1950  6926 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
08-05 01:29:42.874  2875  2875 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 01:29:42.876   938  1041 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
,08-05 01:29:42.876   938  1041 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-05 01:29:42.877  1368  1368 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-05 01:29:42.877  1368  1368 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-05 01:29:42.877  1368  1368 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-05 01:29:42.877  1368  1368 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-05 01:29:42.877   938  1041 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-05 01:29:42.877   938  1041 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-05 01:29:42.878   938  1041 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-05 01:29:42.878   938  1041 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1e578c0,  pkg=WindowManager.LayoutParams
08-05 01:29:42.878   938  1041 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-05 01:29:42.880   938  1882 D InputDispatcher: Focus entered window: Window{19778492 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-05 01:29:42.881  2875  2875 D WeatherService: 2 : shouldTimeTickRegistered : false
08-05 01:29:42.881  2875  2875 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 1:29:42
08-05 01:29:42.881  2875  2875 D WeatherService: 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
08-05 01:29:42.881  2875  2875 D WeatherService: 2 : shouldTimeTickRegistered : false
08-05 01:29:42.893  1950  1950 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-05 01:29:42.893  1950  1950 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,08-05 01:29:42.894  1950  1950 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-05 01:29:42.897   938  2177 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-05 01:29:42.899  6741  6741 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-05 01:29:42.942  1950  1950 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-05 01:29:42.942  1950  1950 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2af09f9e time:159986
,08-05 01:29:42.950  1628  1628 E b       : Unable to connect to the editor to retrieve text... will retry later
08-05 01:29:42.954  1950  1950 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
08-05 01:29:42.960   938  1043 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{44f281a u0 com.lge.launcher2/.Launcher t254} time:160004
,08-05 01:29:43.119  6915  6915 D AndroidRuntime: 
08-05 01:29:43.119  6915  6915 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-05 01:29:43.126  6915  6915 D AndroidRuntime: CheckJNI is OFF
,08-05 01:29:43.350  6915  6915 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-05 01:29:43.518   938   963 I art     : Explicit concurrent mark sweep GC freed 49131(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 2.084ms total 154.341ms
,08-05 01:29:43.537   938  1018 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,08-05 01:29:43.540   938  1018 I ActivityManager: Killing 6741:com.test.thalitest/u0a30 (adj 9): stop com.test.thalitest
08-05 01:29:43.629   938  1066 W PackageSettings: Skipping PackageSetting{1ed0c4ca com.example.hello/10317} due to missing metadata
,08-05 01:29:43.647   938  1949 W ActivityManager: Spurious death for ProcessRecord{226b6548 6741:com.test.thalitest/u0a30}, curProc for 6741: null
,08-05 01:29:43.680   938  1066 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
,08-05 01:29:43.726  1950  1950 I art     : Explicit concurrent mark sweep GC freed 2055(124KB) AllocSpace objects, 4(645KB) LOS objects, 40% free, 15MB/25MB, paused 1.391ms total 42.394ms
,08-05 01:29:43.752  2034  2034 I art     : Explicit concurrent mark sweep GC freed 2192(134KB) AllocSpace objects, 1(23KB) LOS objects, 39% free, 12MB/21MB, paused 4.112ms total 67.150ms
,08-05 01:29:43.767  1950  1950 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-05 01:29:43.767  1950  1950 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-05 01:29:43.768  1950  1950 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-05 01:29:43.770  1368  1368 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-05 01:29:43.786  1751  2412 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-05 01:29:43.788   938  1287 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-05 01:29:43.790  3674  3674 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-05 01:29:43.800  1912  1912 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,08-05 01:29:43.819  3674  3674 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-05 01:29:43.819  3674  3674 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-05 01:29:43.819  3674  3674 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-05 01:29:43.819  3674  3674 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 01:29:43.820  3674  3674 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 01:29:43.820  3674  3674 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 01:29:43.820  3674  3674 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-05 01:29:43.820  3674  3674 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 01:29:43.820  3674  3674 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 01:29:43.820  3674  3674 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-05 01:29:43.820  3674  3674 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,08-05 01:29:43.828   938  1018 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6958 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-05 01:29:43.838   938   938 D administrator: Handling package changes for user 0
,08-05 01:29:43.863  6399  6399 I art     : Explicit concurrent mark sweep GC freed 4383(237KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/18MB, paused 830us total 163.412ms
,08-05 01:29:43.873  1368  1368 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-05 01:29:43.875  1368  1507 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-05 01:29:43.875  1368  1507 D KeyguardModel: createShortcutInfo...
,08-05 01:29:43.878  1368  1507 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-05 01:29:43.878  1368  1507 D KeyguardModel: createShortcutInfo...
08-05 01:29:43.923  1368  1507 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 01:29:43.929  1368  1507 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-05 01:29:43.931  1368  1507 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 01:29:43.931  1368  1507 D KeyguardModel: createShortcutInfo...
08-05 01:29:43.940  1368  1507 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 01:29:43.940  1368  1507 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-05 01:29:43.942  1368  1507 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 01:29:43.942  1368  1507 D KeyguardModel: createShortcutInfo...
08-05 01:29:43.943  1368  1507 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 01:29:43.943  1368  1507 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-05 01:29:43.944  1368  1507 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 01:29:43.944  1368  1507 D KeyguardModel: createShortcutInfo...
08-05 01:29:43.959  6958  6958 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 01:29:43.959  6958  6958 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 01:29:43.960  6958  6958 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-05 01:29:43.981  1368  1368 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-05 01:29:43.981  1368  1368 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-05 01:29:43.984  1368  1368 D KeyguardModel: handleShortcutListChanged...
08-05 01:29:43.990  1368  1507 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-05 01:29:43.990  1368  1507 D KeyguardModel: createShortcutInfo...
08-05 01:29:43.992  1368  1507 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-05 01:29:43.992  1368  1507 D KeyguardModel: createShortcutInfo...
08-05 01:29:43.993  1368  1507 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 01:29:43.993  1368  1507 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-05 01:29:43.998  1368  1507 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 01:29:43.998  1368  1507 D KeyguardModel: createShortcutInfo...
,08-05 01:29:44.002  1368  1507 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 01:29:44.002  1368  1507 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-05 01:29:44.004  1368  1507 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 01:29:44.004  1368  1507 D KeyguardModel: createShortcutInfo...
08-05 01:29:44.005  1368  1507 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 01:29:44.005  1368  1507 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-05 01:29:44.010  1368  1507 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 01:29:44.010  1368  1507 D KeyguardModel: createShortcutInfo...
,08-05 01:29:44.016  1368  1368 D KeyguardModel: handleShortcutListChanged...
08-05 01:29:44.104   938   938 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-05 01:29:44.105   938   938 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-05 01:29:44.109   938   938 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-05 01:29:44.119   938  1346 D TaskPersister: removeObsoleteFile: deleting file=255_task.xml
,08-05 01:29:44.176   938  1066 I art     : Explicit concurrent mark sweep GC freed 25652(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.280ms total 304.286ms
,08-05 01:29:44.227  6958  6958 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-05 01:29:44.247  6958  6958 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,08-05 01:29:44.275  6915  6915 D AndroidRuntime: Shutting down VM
,08-05 01:29:44.325   938  1066 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6978 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-05 01:29:44.326  1850  1850 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-05 01:29:44.326  1850  1850 D LCardEmulationManager: getDefaultRoute
08-05 01:29:44.360   938  1015 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 01:29:44.426   938  1015 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-05 01:29:44.435  1950  1950 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-05 01:29:44.462  6958  6958 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-05 01:29:44.497   938  1878 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6999 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-05 01:29:44.498   938  1878 I ActivityManager: Killing 6346:com.android.contacts/u0a18 (adj 15): empty #11
08-05 01:29:44.527   938  1882 W libprocessgroup: failed to open /acct/uid_10018/pid_6346/cgroup.procs: No such file or directory
,08-05 01:29:44.595  6999  6999 I AppUp4:AppBoxCP: onCreate
,08-05 01:29:44.599  6999  6999 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-05 01:29:44.611  6999  6999 I AppUp4:DB:  setFingerPrint start
,08-05 01:29:44.611  6999  6999 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
08-05 01:29:44.623  6999  6999 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
08-05 01:29:44.623  6999  6999 I AppUp4:DB:  SDK version = 21
08-05 01:29:44.623  6999  6999 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-05 01:29:44.625  6999  6999 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-05 01:29:44.641  6999  6999 E SQLiteLog: (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
,08-05 01:29:44.649  6999  6999 E SQLiteDatabase: Error inserting package=com.test.thalitest
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:790)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1581)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1451)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1267)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-05 01:29:44.649  6999  6999 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,08-05 01:29:44.687   938  1882 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7024 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
08-05 01:29:44.688   938  1882 I ActivityManager: Killing 6382:com.lge.eula/1000 (adj 15): empty #11
08-05 01:29:44.727   938  2019 W libprocessgroup: failed to open /acct/uid_1000/pid_6382/cgroup.procs: No such file or directory

```
