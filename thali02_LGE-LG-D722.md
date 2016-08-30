#### Test 82642184cbac892_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-30 02:46:02.703  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 02:46:02.705  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 02:46:02.705  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-30 02:46:03.716  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 02:46:03.717  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 02:46:03.719  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
--------- beginning of system
08-30 02:46:03.771   862  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1a500060 type 2 when 120000 com.google.android.gms} when 120000
08-30 02:46:03.971  6600  6600 D AndroidRuntime: 
08-30 02:46:03.971  6600  6600 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 02:46:03.975  6600  6600 D AndroidRuntime: CheckJNI is OFF
08-30 02:46:04.029  2866  2866 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19952
08-30 02:46:04.123   862  3622 I art     : Explicit concurrent mark sweep GC freed 44724(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 3.071ms total 167.993ms
08-30 02:46:04.123   862  3622 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 02:46:04.127   862  1315 D ConnectivityService: dumpNetworkRequest
08-30 02:46:04.127   862  1315 D ConnectivityService:     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-30 02:46:04.127   862  1315 D ConnectivityService:     Requests:
08-30 02:46:04.128   862  1315 D ConnectivityService:         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 02:46:04.129   862  1315 D ConnectivityService:         NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 02:46:04.129   862  1315 D ConnectivityService:     Lingered:
08-30 02:46:04.129   862  1315 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
08-30 02:46:04.129   862  1315 D ConnectivityService: apparently satisfied.  currentScore=60
08-30 02:46:04.133   862  1315 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 02:46:04.134  5665  6607 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 02:46:04.198  5665  6626 W DriveInitializer: Background init thread started
08-30 02:46:04.207  6600  6600 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 02:46:04.227   243   312 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 02:46:04.227   243   312 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
08-30 02:46:04.227   243   312 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 02:46:04.229  5665  6626 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
08-30 02:46:04.230   862   883 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 02:46:04.279   862   883 D ActivityManager: setTaskToReturnTo : TaskRecord{263c84db #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 02:46:04.281   862   883 D ActivityManager: setTaskToReturnTo : TaskRecord{263c84db #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 02:46:04.304   862   883 D WindowStateEx: AppWindowTokenEx init.. 
08-30 02:46:04.317   862  1056 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-30 02:46:04.336   862  1056 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 02:46:04.349   862   883 D InputDispatcher: Focus left window: Window{327c24 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-30 02:46:04.351  1876  1876 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-30 02:46:04.354   862  1056 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 02:46:04.354   862  1056 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-30 02:46:04.354  6600  6600 D AndroidRuntime: Shutting down VM
08-30 02:46:04.393   862  1056 D SplitWindow: check instance of lgWin Window{38b4b453 u0 Starting com.test.thalitest}
08-30 02:46:04.439   862   883 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6629 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 02:46:04.457  1876  1876 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-30 02:46:04.511  1954  1954 I HotwordDetector: Closing mic
08-30 02:46:04.521  1876  1876 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-30 02:46:04.524  1954  2548 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@24c50cca
08-30 02:46:04.525  1954  2548 V AudioRecord: stop()
08-30 02:46:04.525  1954  2548 D AudioRecord: AudioRecord->stop()
08-30 02:46:04.526   282   282 V AudioFlinger: RecordHandle::stop()
08-30 02:46:04.526   282   282 V AudioFlinger: RecordThread::stop
08-30 02:46:04.539   862  1380 I WindowStateAnimator: Starting window displayed
08-30 02:46:04.542   282   282 V AudioFlinger: Record stopped OK
08-30 02:46:04.544   282   282 V AudioPolicyManager: stopInput() input 17
08-30 02:46:04.545   282   282 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
08-30 02:46:04.546   282   282 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
08-30 02:46:04.546   282  1062 V AudioPolicyService: AudioCommandThread() waking up
08-30 02:46:04.546   282  1062 V AudioPolicyService: AudioCommandThread() processing release audio patch
08-30 02:46:04.546   282  1062 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
08-30 02:46:04.546   282  1062 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
08-30 02:46:04.546   282  1062 V AudioFlinger: ThreadBase::setParameters() routing=0
08-30 02:46:04.546   282  1062 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-30 02:46:04.547   282  2571 V AudioFlinger: processConfigEvents_l() remaining events 1
08-30 02:46:04.548   282  2571 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3c5c000
08-30 02:46:04.548   862  1054 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-30 02:46:04.551   282  2571 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
,08-30 02:46:04.561   862  1054 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-30 02:46:04.564   862  1054 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-30 02:46:04.564   862  1054 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-30 02:46:04.564   862  1054 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-30 02:46:04.564   862  1054 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@23cb381c,  pkg=WindowManager.LayoutParams
08-30 02:46:04.565   862  1054 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-30 02:46:04.569  1374  1374 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-30 02:46:04.571  1374  1374 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-30 02:46:04.571  1374  1374 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-30 02:46:04.571  1374  1374 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-30 02:46:04.594   282  2571 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
08-30 02:46:04.594   282  2571 V audio_hw_primary: disable_audio_route: enter: usecase(7)
08-30 02:46:04.594   282  2571 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
08-30 02:46:04.594   282  2571 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 02:46:04.597   282  2571 V audio_hw_primary: disable_audio_route: exit
08-30 02:46:04.597   282  2571 E audio_hw_primary: disable_snd_device: enter 144
08-30 02:46:04.597   282  2571 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
08-30 02:46:04.597   282  2571 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
08-30 02:46:04.600   282  2571 V audio_hw_primary: stop_input_stream: exit: status(0)
08-30 02:46:04.600   282  2571 V audio_hw_primary: in_standby: exit:  status(0)
08-30 02:46:04.600   282  2571 V AudioFlinger: RecordThread: loop stopping
08-30 02:46:04.600   282  1062 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 02:46:04.600   282   282 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
08-30 02:46:04.600   282   282 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
08-30 02:46:04.600   282   282 V AudioPolicyService: AudioCommandThread() adding update audio patch list
08-30 02:46:04.600   282   282 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
08-30 02:46:04.601   282  1063 V AudioPolicyService: AudioCommandThread() waking up
08-30 02:46:04.601   282  1063 V AudioPolicyService: AudioCommandThread() processing update audio patch list
08-30 02:46:04.601   282  1063 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 02:46:04.601   282   282 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
08-30 02:46:04.601   282   282 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
08-30 02:46:04.602   282  1062 V AudioPolicyService: AudioCommandThread() waking up
08-30 02:46:04.602   282  1062 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
08-30 02:46:04.602   282  1062 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 282
08-30 02:46:04.602   282  1062 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
08-30 02:46:04.602   282  1062 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-30 02:46:04.602   282  2571 V AudioFlinger: RecordThread: loop starting
08-30 02:46:04.603   282  2571 V AudioFlinger: processConfigEvents_l() remaining events 1
08-30 02:46:04.603   282  2571 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
08-30 02:46:04.603   282  2571 V audio_hw_primary: in_set_parameters: exit: status(0)
08-30 02:46:04.603   282  2571 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3c5c000
08-30 02:46:04.603   282  2571 V AudioFlinger: RecordThread: loop stopping
08-30 02:46:04.604   282  1062 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 02:46:04.622  1954  2548 V AudioRecord: stop()
08-30 02:46:04.623  1954  2548 V AudioRecord: stop()
08-30 02:46:04.623  1954  2548 V AudioRecord: stop()
08-30 02:46:04.624  5665  6626 W DriveInitializer: Background init thread ended
08-30 02:46:04.624   282  1323 V AudioFlinger: RecordHandle::stop()
08-30 02:46:04.624   282  1323 V AudioFlinger: RecordThread::stop
08-30 02:46:04.624   282   282 V AudioFlinger: releasing 16 from 1954 for -1
08-30 02:46:04.624   282  1323 V AudioPolicyManager: releaseInput() 17
08-30 02:46:04.624   282   282 V AudioFlinger:  decremented refcount to 0
08-30 02:46:04.624   282  1323 V AudioPolicyManager: closeInput(17)
08-30 02:46:04.624   282   282 V AudioFlinger: purging stale effects
08-30 02:46:04.624   282  1323 V AudioFlinger: closeInput() 17
08-30 02:46:04.624   282  1323 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 02:46:04.624   282  1323 V AudioFlinger: ThreadBase::exit
08-30 02:46:04.625   282  2571 V AudioFlinger: RecordThread: loop starting
08-30 02:46:04.625   282  2571 V AudioFlinger: RecordThread 0xb3c5c000 exiting
08-30 02:46:04.625   862  1380 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 02:46:04.625   282  1323 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546dd40)
08-30 02:46:04.625   282  1323 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
08-30 02:46:04.625   282  1323 V audio_hw_primary: in_standby: exit:  status(0)
08-30 02:46:04.625   282  1323 V AudioPolicyService: AudioCommandThread() adding update audio port list
08-30 02:46:04.625   282  1323 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
08-30 02:46:04.625   282  1323 V AudioPolicyManager: releaseInput() exit
08-30 02:46:04.625   282  1063 V AudioPolicyService: AudioCommandThread() waking up
08-30 02:46:04.625   282  1063 V AudioPolicyService: AudioCommandThread() processing update audio port list
08-30 02:46:04.625   282  1323 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
08-30 02:46:04.626   282  1323 V AudioFlinger: removeClient_l() pid 1954, calling pid 282
08-30 02:46:04.626   282  1063 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 02:46:04.626  1749  3180 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 02:46:04.626  1374  3488 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 02:46:04.626  1954  1987 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 02:46:04.626  2056  3445 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 02:46:04.626  3139  3231 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 02:46:04.626  2866  2885 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 02:46:04.631  1954  2553 I HotwordRecognitionRnr: Stopping hotword detection.
08-30 02:46:04.635  1954  2562 I HotwordRecognitionRnr: Hotword detection finished
08-30 02:46:04.703  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 02:46:04.703  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 02:46:04.703  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-30 02:46:04.707  6629  6629 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-30 02:46:04.878  6629  6629 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-30 02:46:04.943  6629  6629 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1210-1213)
08-30 02:46:04.943  6629  6629 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 02:46:04.989  6629  6629 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {36cfafd}
08-30 02:46:04.991  6629  6629 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 02:46:04.993  6629  6629 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 02:46:05.021  6629  6629 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 02:46:05.022  6629  6629 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 02:46:05.023  6629  6629 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 02:46:05.039   862   996 W ProcessCpuTracker: Skipping unknown process pid 6609
08-30 02:46:05.043   862   996 W ProcessCpuTracker: Skipping unknown process pid 6612
08-30 02:46:05.048   862   996 W ProcessCpuTracker: Skipping unknown process pid 6651
08-30 02:46:05.049   862   996 W ProcessCpuTracker: Skipping unknown process pid 6652
08-30 02:46:05.049   862   996 W ProcessCpuTracker: Skipping unknown process pid 6654
08-30 02:46:05.050   862   996 W ProcessCpuTracker: Skipping unknown process pid 6657
08-30 02:46:05.050   862   996 W ProcessCpuTracker: Skipping unknown process pid 6659
08-30 02:46:05.054  6629  6629 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 02:46:05.060  6629  6629 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 02:46:05.060  6629  6629 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 02:46:05.061  6629  6629 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 02:46:05.061  6629  6629 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 02:46:05.061  6629  6629 I Adreno-EGL: Build Date: 03/02/15 Mon
08-30 02:46:05.061  6629  6629 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-30 02:46:05.061  6629  6629 I Adreno-EGL: Remote Branch: 
08-30 02:46:05.061  6629  6629 I Adreno-EGL: Local Patches: 
08-30 02:46:05.061  6629  6629 I Adreno-EGL: Reconstruct Branch: 
08-30 02:46:05.075  1374  1374 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
08-30 02:46:05.095   862  1289 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 02:46:05.095  1840  1840 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
08-30 02:46:05.145  1876  1876 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-30 02:46:05.148  1876  1876 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-30 02:46:05.149  1876  1876 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
08-30 02:46:05.149   862   996 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6676 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-30 02:46:05.157   862   862 D administrator: Handling package changes for user 0
08-30 02:46:05.169  1374  1374 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-30 02:46:05.183  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
08-30 02:46:05.184  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
08-30 02:46:05.184  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
08-30 02:46:05.184  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
08-30 02:46:05.184  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
08-30 02:46:05.184  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
08-30 02:46:05.184  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
08-30 02:46:05.184  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
08-30 02:46:05.184  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
08-30 02:46:05.184  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
08-30 02:46:05.184  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
08-30 02:46:05.184  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
08-30 02:46:05.185  1374  1374 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-30 02:46:05.201  1876  1876 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-30 02:46:05.209   282  1603 V AudioPolicyService: registerClient() client 0xb4145160, uid 10030
,08-30 02:46:05.228   862  1055 D BluetoothManagerService: Message: 20
08-30 02:46:05.228   862  1055 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@116e86d9:true
08-30 02:46:05.232  2056  2077 D BluetoothAdapterService(413481539): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ff3f31
08-30 02:46:05.274  6676  6676 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 02:46:05.359   862   862 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-30 02:46:05.359   862   862 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-30 02:46:05.360   862   862 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,08-30 02:46:05.364   862   862 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
08-30 02:46:05.373   862   862 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,08-30 02:46:05.376   862   862 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@28d1ed2d
08-30 02:46:05.400   862   995 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 02:46:05.456  6629  6629 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 02:46:05.479  6629  6629 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 02:46:05.490  6629  6629 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-30 02:46:05.496  6629  6629 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 02:46:05.497  6629  6629 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-30 02:46:05.501   862   995 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 02:46:05.513  6629  6629 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-30 02:46:05.523  6629  6629 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 02:46:05.523  6629  6629 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 02:46:05.552  1876  1876 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 02:46:05.564  1732  1732 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,08-30 02:46:05.585   862   995 D LocationProviderProxy: applying state to connected service
,08-30 02:46:05.607  6629  6629 I Activity: Activity.onPostResume() called 
,08-30 02:46:05.622  6629  6720 D OpenGLRenderer: Render dirty regions requested: true
08-30 02:46:05.623  6629  6720 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 02:46:05.632  6629  6720 D OpenGLRenderer: Enabling debug mode 0
08-30 02:46:05.651  6629  6629 D Atlas   : Validating map...
08-30 02:46:05.656   862  1926 D SplitWindow: check instance of lgWin Window{f64ea2f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 02:46:05.671  6629  6701 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 02:46:05.680  1786  1786 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-30 02:46:05.680  1786  1786 D LCardEmulationManager: getDefaultRoute
08-30 02:46:05.681  6676  6725 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-30 02:46:05.682  6676  6725 I Babel_SMS: MmsConfig.loadMmsSettings
08-30 02:46:05.695  6676  6725 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
08-30 02:46:05.696  6676  6725 I Babel_SMS: MmsConfig.loadFromDatabase
,08-30 02:46:05.712   862  1823 D InputDispatcher: Focus entered window: Window{f64ea2f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 02:46:05.758  6676  6725 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-30 02:46:05.758  6676  6725 I Babel_SMS: MmsConfig.loadFromResources
08-30 02:46:05.760  6676  6725 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
08-30 02:46:05.760  6676  6725 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
08-30 02:46:05.782   862  1839 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-30 02:46:05.793  6676  6676 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
08-30 02:46:05.793  6676  6676 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
08-30 02:46:05.793  6676  6676 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,08-30 02:46:05.793  6676  6676 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
08-30 02:46:05.793  6676  6676 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
08-30 02:46:05.793  6676  6676 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
08-30 02:46:05.793  6676  6676 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
08-30 02:46:05.793  6676  6676 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
08-30 02:46:05.793  6676  6676 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
08-30 02:46:05.793  6676  6676 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
08-30 02:46:05.793  6676  6676 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
08-30 02:46:05.793  6676  6676 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
08-30 02:46:05.794  6676  6676 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
08-30 02:46:05.794  6676  6676 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
08-30 02:46:05.794  6676  6676 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
08-30 02:46:05.794  6676  6676 D SensorManager: found sensor: Motion Accel, handle=46
08-30 02:46:05.799   862  1056 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s407ms
08-30 02:46:05.801   862  1056 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{14a17b78 u0 com.test.thalitest/.MainActivity t259} time:122070
08-30 02:46:05.816  6629  6629 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3303468f time:122087
,08-30 02:46:05.850  6676  6676 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 02:46:05.854  6676  6676 I Babel_Crash: startup - clean
08-30 02:46:05.881  6676  6699 I art     : CheckpointMarkThreadRoots callback created = 0xb042d860
,08-30 02:46:05.894  6676  6732 I Babel   : deleted: false for 0
,08-30 02:46:05.931  6629  6629 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6629
,08-30 02:46:05.934  6676  6699 I art     : CheckpointMarkThreadRoots callback created = 0xb042d840
08-30 02:46:05.955  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-30 02:46:05.955  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-30 02:46:05.955  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-30 02:46:05.960  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,08-30 02:46:05.960  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
08-30 02:46:05.965   481   481 D charger_monitor: init target 500000
08-30 02:46:06.018   481   481 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-30 02:46:06.026  1803  1975 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-30 02:46:06.026  1803  1975 D LEDHandler: Battery Level Remaining: 100%
08-30 02:46:06.026  1803  1975 D LEDHandler: Battery Temp: 300, mChargingStatus=5, mChargingStop=false
08-30 02:46:06.028  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
08-30 02:46:06.028  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-30 02:46:06.031  6424  6424 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 02:46:06.032  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
,08-30 02:46:06.037  2056  3526 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 02:46:06.047   862  1314 D WifiController: battery changed pluggedType: 2
08-30 02:46:06.048  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,08-30 02:46:06.048  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-30 02:46:06.059  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-30 02:46:06.067   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 02:46:06.067   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 02:46:06.070  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
08-30 02:46:06.070  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-30 02:46:06.070  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
08-30 02:46:06.072  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-30 02:46:06.072  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,08-30 02:46:06.073  1803  1975 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-30 02:46:06.073  1803  1975 D LEDHandler: Battery Level Remaining: 100%
08-30 02:46:06.073  1803  1975 D LEDHandler: Battery Temp: 298, mChargingStatus=5, mChargingStop=false
08-30 02:46:06.074  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-30 02:46:06.075  2056  3526 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 02:46:06.077  6424  6424 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 02:46:06.079   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 02:46:06.079   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 02:46:06.080   862  1314 D WifiController: battery changed pluggedType: 2
,08-30 02:46:06.140   862  1839 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6738 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-30 02:46:06.172  6676  6676 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,08-30 02:46:06.176  6676  6676 W AudioCapabilities: Unsupported mime audio/adpcm
08-30 02:46:06.183  6676  6676 W AudioCapabilities: Unsupported mime audio/g726
08-30 02:46:06.190  6676  6676 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-30 02:46:06.195  6629  6629 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-30 02:46:06.197  6676  6676 W AudioCapabilities: Unsupported mime audio/wma-voice
08-30 02:46:06.201  6676  6676 W VideoCapabilities: Unsupported mime video/mjpg
08-30 02:46:06.205  6676  6676 W VideoCapabilities: Unsupported mime video/theora
,08-30 02:46:06.289  6676  6676 W AudioCapabilities: Unsupported mime audio/evrc
08-30 02:46:06.290  6676  6676 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 02:46:06.293  6676  6676 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 02:46:06.323  6676  6676 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-30 02:46:06.325  6738  6738 I AppUp4:AppBoxCP: onCreate
08-30 02:46:06.326  6676  6676 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 02:46:06.330  6676  6676 W AudioCapabilities: Unsupported mime audio/evrc
08-30 02:46:06.335  6738  6738 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-30 02:46:06.352  6738  6738 I AppUp4:DB:  setFingerPrint start
,08-30 02:46:06.354  6738  6738 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
08-30 02:46:06.371  6676  6676 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-30 02:46:06.380  6738  6738 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
08-30 02:46:06.380  6738  6738 I AppUp4:DB:  SDK version = 21
08-30 02:46:06.380  6738  6738 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-30 02:46:06.383  6738  6738 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-30 02:46:06.402  6738  6738 I AppUp4:CustModeStarterReceiver: onReceive
08-30 02:46:06.403  6738  6738 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,08-30 02:46:06.406  6676  6676 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-30 02:46:06.406  6738  6738 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c16e3c1
08-30 02:46:06.406  6738  6738 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 02:46:06.415  6738  6738 D AppUp4:CustFacade: isSimDevice : true
08-30 02:46:06.416  6738  6738 D AppUp4:CustModeStarterReceiver: begin check event
,08-30 02:46:06.417  6676  6676 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 02:46:06.417  6738  6738 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-30 02:46:06.418   862  1818 I ActivityManager: Killing 6279:com.lge.eula/1000 (adj 15): empty #11
08-30 02:46:06.420  6676  6676 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 02:46:06.423  6676  6676 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 02:46:06.431  6676  6676 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 02:46:06.491   862  1322 W libprocessgroup: failed to open /acct/uid_1000/pid_6279/cgroup.procs: No such file or directory
,08-30 02:46:06.548   862  1818 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6759 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-30 02:46:06.572   306   306 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 405us total 24.313ms
,08-30 02:46:06.595   306   306 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 378us total 23.033ms
,08-30 02:46:06.619   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 314us total 22.691ms
,08-30 02:46:06.696  6676  6676 I vclib   : onServiceConnected
08-30 02:46:06.697  6676  6676 W Babel   : Attempted to change video mute state without an active call.
08-30 02:46:06.700  6676  6757 I NotificationManager: com.google.android.talk: cancel(8) by com.google.android.talk
08-30 02:46:06.700  6759  6759 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 02:46:06.701  6759  6759 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 02:46:06.701  6759  6759 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-30 02:46:06.709  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 02:46:06.709  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 02:46:06.709  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-30 02:46:06.749  6676  6676 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 02:46:06.750  6676  6676 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 02:46:06.779  6629  6731 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1631409920
,08-30 02:46:06.826  6629  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 02:46:06.826  6629  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 02:46:06.826  6629  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 02:46:06.826  6629  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 02:46:06.826  6629  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 02:46:06.826  6629  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfb4720 added. We now have 1 listener(s)
,08-30 02:46:06.840  6676  6676 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 02:46:06.853   862  1322 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 02:46:06.857  6629  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
08-30 02:46:06.860  6629  6731 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-30 02:46:06.861  6629  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 02:46:06.862  6629  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 02:46:06.888  6629  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 02:46:06.888  6629  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 02:46:06.888  6629  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 02:46:06.888  6629  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-30 02:46:06.888  6629  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 02:46:06.888  6629  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 02:46:06.888  6629  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 02:46:06.888  6629  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 02:46:06.888  6629  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 02:46:06.888  6629  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 02:46:06.888  6629  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 02:46:06.888  6629  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 02:46:06.888  6629  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 02:46:06.888  6629  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 02:46:06.889  6629  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c88f17f added. We now have 1 listener(s)
,08-30 02:46:06.891  6629  6731 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 02:46:06.911  6629  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 02:46:06.912  6629  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-30 02:46:06.912  6629  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 02:46:06.912  6629  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 02:46:06.912  6629  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 02:46:06.927  6629  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 02:46:06.928   862  1380 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 02:46:06.929  6629  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-30 02:46:06.946  2056  3445 D BluetoothAdapterService(413481539): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ff3f31
,08-30 02:46:06.952  6759  6759 I AppConfig: Total System Memory = 906309632
08-30 02:46:06.953  6629  6731 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 02:46:06.953  6629  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 02:46:06.953  6629  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 02:46:06.953  6629  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 02:46:06.953  6629  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 02:46:06.953  6629  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 02:46:06.953  6629  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 02:46:06.953  6629  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 02:46:06.953  6629  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 02:46:06.954  6629  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 02:46:06.954  6629  6731 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 02:46:06.958  6629  6731 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 02:46:06.961  6759  6759 I GalleryUtils: Application Heap = 96 MB
08-30 02:46:06.968  6759  6759 I AppConfig: App Tier : NOT_DEF
08-30 02:46:06.983  6759  6759 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-30 02:46:07.033  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 02:46:07.034  6676  6676 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-30 02:46:07.036  6676  6676 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-30 02:46:07.038  6629  6629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 02:46:07.042  6629  6629 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-30 02:46:07.055  6676  6676 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,08-30 02:46:07.102   862  3622 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6784 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-30 02:46:07.103   862  3622 I ActivityManager: Killing 6364:com.google.android.apps.docs/u0a58 (adj 15): empty #11
08-30 02:46:07.175   862  1818 W libprocessgroup: failed to open /acct/uid_10058/pid_6364/cgroup.procs: No such file or directory
,08-30 02:46:07.181  6629  6643 I art     : CheckpointMarkThreadRoots callback created = 0xb07ff330
08-30 02:46:07.196  6784  6784 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 02:46:07.196  6784  6784 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 02:46:07.196  6784  6784 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 02:46:07.197  6784  6784 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-30 02:46:07.197  6784  6784 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 02:46:07.217  6629  6643 I art     : CheckpointMarkThreadRoots callback created = 0xb07ff300
,08-30 02:46:07.261  6784  6784 I SystemConfig: BUILD Country: EU
08-30 02:46:07.261  6784  6784 I SystemConfig: BUILD Operator: OPEN
,08-30 02:46:07.345   294   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-30 02:46:07.382   862  1818 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6803 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
08-30 02:46:07.382   862  1818 I ActivityManager: Killing 6190:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,08-30 02:46:07.451   862  1361 W libprocessgroup: failed to open /acct/uid_10086/pid_6190/cgroup.procs: No such file or directory
,08-30 02:46:07.459  6784  6801 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-30 02:46:07.460  6784  6801 I SystemConfig: existFile = false
08-30 02:46:07.460  6784  6801 I SystemConfig: canReadFile = false
08-30 02:46:07.460  6784  6801 I SystemConfig: systemFeature RCS result false
08-30 02:46:07.460  6784  6801 D SystemConfig: refreshRcsSupport() :false
08-30 02:46:07.480  6803  6803 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-30 02:46:07.501  6803  6803 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-30 02:46:07.501  6803  6803 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-30 02:46:07.501  6803  6803 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-30 02:46:07.501  6803  6803 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 02:46:07.501  6803  6803 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,08-30 02:46:07.505   862  4232 I ActivityManager: Killing 6424:com.lge.bnr/1000 (adj 15): empty #11
08-30 02:46:07.561   862  1785 W libprocessgroup: failed to open /acct/uid_1000/pid_6424/cgroup.procs: No such file or directory
,08-30 02:46:07.576  5665  6824 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,08-30 02:46:07.588  5665  6824 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 02:46:07.588  5665  6824 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 02:46:07.614  5665  5735 I Icing   : updateResources: need to parse ozd{com.google.android.gms}
,08-30 02:46:07.652   862  1380 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6829 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-30 02:46:07.709  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,08-30 02:46:07.709  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 02:46:07.709  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-30 02:46:07.712  5665  6847 W IcingInternalCorpora: getNumBytesRead when not calculated.
08-30 02:46:07.727  6829  6829 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 02:46:08.002  6629  6781 W jxcore-log: Initializing JXcore engine
08-30 02:46:08.003  6629  6781 W jxcore-log: JXcore engine is ready
,08-30 02:46:08.114  6781  6781 W Thread-779: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7406]" dev="sockfs" ino=7406 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-30 02:46:08.114  6781  6781 W Thread-779: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 02:46:08.114  6781  6781 W Thread-779: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5860]" dev="sockfs" ino=5860 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-30 02:46:08.114  6781  6781 W Thread-779: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-30 02:46:08.114  6781  6781 W Thread-779: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-30 02:46:08.114  6781  6781 W Thread-779: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[31091]" dev="sockfs" ino=31091 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 02:46:08.148  6629  6781 W jxcore-log: Starting JXcore engine
,08-30 02:46:08.157   862   883 I art     : Explicit concurrent mark sweep GC freed 26174(1388KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.293ms total 179.140ms
08-30 02:46:08.163  1954  6860 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-30 02:46:08.201  1954  6860 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 39 ms] updated apps [took 39 ms] 
,08-30 02:46:08.313  6629  6781 W jxcore-log: Platform android
08-30 02:46:08.313  6629  6781 W jxcore-log: 
08-30 02:46:08.313  6629  6781 W jxcore-log: Process ARCH arm
08-30 02:46:08.313  6629  6781 W jxcore-log: 
,08-30 02:46:08.588  6629  6781 I jxcore-log: JXcore Cordova bridge is ready!
08-30 02:46:08.588  6629  6781 I jxcore-log: 
08-30 02:46:08.589  6629  6781 W jxcore-log: JXcore engine is started
,08-30 02:46:08.598  6629  6731 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-30 02:46:08.599  6629  6629 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-30 02:46:08.710  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 02:46:08.710  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 02:46:08.710  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-30 02:46:08.854  5665  5735 I Icing   : Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,08-30 02:46:08.899  5665  5735 I Icing   : Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,08-30 02:46:09.601   862  1287 V AlarmManager: RTC_WAKEUP set : Alarm{109d06f7 type 0 when 1472517969590 com.google.android.googlequicksearchbox} when 1472517969590
,08-30 02:46:10.715  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 02:46:10.715  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 02:46:10.715  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-30 02:46:10.826   481   481 D charger_monitor: init target 500000
,08-30 02:46:10.830  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-30 02:46:10.831  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-30 02:46:10.831  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-30 02:46:10.831  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
08-30 02:46:10.831  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-30 02:46:10.865  1803  1975 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-30 02:46:10.865  1803  1975 D LEDHandler: Battery Level Remaining: 100%
08-30 02:46:10.865  1803  1975 D LEDHandler: Battery Temp: 298, mChargingStatus=5, mChargingStop=false
08-30 02:46:10.866  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-30 02:46:10.866  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,08-30 02:46:10.868  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
08-30 02:46:10.868  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-30 02:46:10.869  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
08-30 02:46:10.869  2056  3526 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-30 02:46:10.870   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 02:46:10.870   862  1314 D WifiController: battery changed pluggedType: 2
08-30 02:46:10.870   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 02:46:10.872  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-30 02:46:10.878   481   481 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-30 02:46:11.716  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 02:46:11.717  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 02:46:11.717  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-30 02:46:12.106   862   880 I ActivityManager: Killing 2866:com.lge.music/u0a28 (adj 15): empty #11
,08-30 02:46:12.118   282  1603 V AudioFlinger: 2866 died, releasing its sessions
08-30 02:46:12.118   282  1603 V AudioFlinger:  pid 1749 @ 0
08-30 02:46:12.118   282  1603 V AudioFlinger:  pid 3139 @ 1
08-30 02:46:12.118   282  1603 V AudioFlinger:  pid 3139 @ 2
,08-30 02:46:12.160   862   883 W libprocessgroup: failed to open /acct/uid_10028/pid_2866/cgroup.procs: No such file or directory
,08-30 02:46:12.350   294   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-30 02:46:14.884  5665  6469 I CheckinService: Done disabling old GoogleServicesFramework version
,08-30 02:46:16.765   862  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-30 02:46:16.765   862  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-30 02:46:16.765   862  1011 D sensors_hal_Time: tsOffsetIs: Apps: 133035854276; DSPS: 4450810; Offset : -2800203710
,08-30 02:46:17.355   294   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-30 02:46:19.130   862  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{23111b93 type 2 when 135392 com.google.android.gms} when 135392
,08-30 02:46:19.161  1732  1732 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-30 02:46:19.414  1732  1732 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 02:46:19.433  5665  6915 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-30 02:46:19.433  5665  6915 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-30 02:46:19.466  5665  6914 W InstanceID/Rpc: Found 10006
,08-30 02:46:19.791  5665  5665 I art     : Explicit concurrent mark sweep GC freed 40143(2MB) AllocSpace objects, 16(259KB) LOS objects, 39% free, 15MB/25MB, paused 1.793ms total 129.069ms
,08-30 02:46:19.813   282  1603 D WVCdm   : Instantiating CDM.
,08-30 02:46:19.813   282   282 I WVCdm   : CdmEngine::OpenSession
08-30 02:46:19.813   282   282 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
08-30 02:46:19.855   282   282 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
08-30 02:46:19.855   282   282 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
08-30 02:46:19.855   282   282 W WVCdm   : L1 library not specified. Falling Back to L3
,08-30 02:46:19.899  6502  6533 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,08-30 02:46:19.901  6502  6533 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-30 02:46:19.904  6502  6533 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 02:46:19.904  6502  6533 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 02:46:19.905   278  1044 E BandwidthController: [LG DATA] No such appUid: 10006
08-30 02:46:19.905   278  1044 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-30 02:46:19.905   278  6932 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-30 02:46:19.905   278  6932 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 02:46:19.906   278  6932 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-30 02:46:19.906   278  6932 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-30 02:46:19.906   278  6932 D libc-netbsd: res_queryN name = xxxxx succeed
08-30 02:46:19.907  6502  6533 I System.out: propertyValue:false
08-30 02:46:19.944   282   282 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-30 02:46:19.944   282  1323 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-30 02:46:19.945   282  1323 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-30 02:46:19.945   282  1323 I WVCdm   : CdmEngine::GenerateKeyRequest
08-30 02:46:19.950   282  1323 D WVCdm   : PrepareKeyRequest: nonce=571443076
08-30 02:46:19.974  6502  6533 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 02:46:19.974  6502  6533 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-30 02:46:20.410  1732  1732 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=ac51d3e2-9a72-4e09-b89d-a20e0e57ad0c
,08-30 02:46:20.425  1732  1732 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-30 02:46:20.426  1732  1732 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 02:46:20.577  1732  2518 W GCoreFlp: No location to return for getLastLocation()
,08-30 02:46:20.708  1732  2518 I art     : Explicit concurrent mark sweep GC freed 51492(2MB) AllocSpace objects, 15(240KB) LOS objects, 39% free, 14MB/24MB, paused 2.237ms total 114.573ms
,08-30 02:46:20.733  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 02:46:20.733  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 02:46:20.733  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,08-30 02:46:20.758  5665  6924 D UdcContextInitService: registered all accounts: true
,08-30 02:46:20.760  1732  2504 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 02:46:20.785  1732  2396 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-30 02:46:20.926  6502  6533 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 02:46:20.926  6502  6533 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 02:46:20.926  6502  6533 I Adreno-EGL: Build Date: 03/02/15 Mon
08-30 02:46:20.926  6502  6533 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-30 02:46:20.926  6502  6533 I Adreno-EGL: Remote Branch: 
08-30 02:46:20.926  6502  6533 I Adreno-EGL: Local Patches: 
08-30 02:46:20.926  6502  6533 I Adreno-EGL: Reconstruct Branch: 
,08-30 02:46:20.993  6502  6533 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 02:46:20.993  6502  6533 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 02:46:20.993  6502  6533 I Adreno-EGL: Build Date: 03/02/15 Mon
08-30 02:46:20.993  6502  6533 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-30 02:46:20.993  6502  6533 I Adreno-EGL: Remote Branch: 
08-30 02:46:20.993  6502  6533 I Adreno-EGL: Local Patches: 
08-30 02:46:20.993  6502  6533 I Adreno-EGL: Reconstruct Branch: 
,08-30 02:46:21.048  6502  6533 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 02:46:21.048  6502  6533 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 02:46:21.048  6502  6533 I Adreno-EGL: Build Date: 03/02/15 Mon
08-30 02:46:21.048  6502  6533 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-30 02:46:21.048  6502  6533 I Adreno-EGL: Remote Branch: 
08-30 02:46:21.048  6502  6533 I Adreno-EGL: Local Patches: 
08-30 02:46:21.048  6502  6533 I Adreno-EGL: Reconstruct Branch: 
,08-30 02:46:21.079  1732  2396 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 02:46:21.079  1732  2396 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-30 02:46:21.079  1732  2396 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 02:46:21.079  1732  2396 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 02:46:21.080   278  1044 E BandwidthController: [LG DATA] No such appUid: 10006
08-30 02:46:21.080   278  1044 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-30 02:46:21.080   278  6940 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-30 02:46:21.080   278  6940 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 02:46:21.080   278  6940 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-30 02:46:21.081   278  6940 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-30 02:46:21.081   278  6940 D libc-netbsd: res_queryN name = xxxxx succeed
08-30 02:46:21.081  1732  2396 I System.out: propertyValue:false
,08-30 02:46:21.120  1732  6922 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 02:46:21.121  1732  6922 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-30 02:46:21.136  1732  2396 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 02:46:21.136  1732  2396 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-30 02:46:21.169  1732  6922 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,08-30 02:46:21.169  1732  6922 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-30 02:46:21.292   862  2064 I NotificationManager: android: cancelAsUser(2) by android
,08-30 02:46:21.317  1732  2396 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,08-30 02:46:21.387  1732  2396 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 02:46:21.392  1732  2396 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
08-30 02:46:21.449  1732  6942 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 02:46:21.449  1732  6942 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-30 02:46:21.449  1732  6942 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 02:46:21.449  1732  6942 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 02:46:21.450   278  1044 E BandwidthController: [LG DATA] No such appUid: 10006
08-30 02:46:21.450   278  1044 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,08-30 02:46:21.450   278  6947 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-30 02:46:21.450   278  6947 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 02:46:21.451   278  6947 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-30 02:46:21.451   278  6947 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,08-30 02:46:21.451   278  6947 D libc-netbsd: res_queryN name = xxxxx succeed
08-30 02:46:21.452  1732  6942 I System.out: propertyValue:false
08-30 02:46:21.753  1732  2396 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-30 02:46:21.950  1732  6950 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-30 02:46:21.951  1732  6948 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 02:46:21.985  1732  6950 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 02:46:21.986  1732  6948 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-30 02:46:22.011  1732  6950 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 02:46:22.013  1732  6948 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-30 02:46:22.013  1732  6948 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
08-30 02:46:22.034  1732  6948 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 02:46:22.079   862  1818 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 02:46:22.145  4031  5664 I art     : Explicit concurrent mark sweep GC freed 2538(96KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 895us total 26.815ms
,08-30 02:46:22.181  1732  6948 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 02:46:22.181  1732  6948 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-30 02:46:22.182  1732  6948 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 02:46:22.182  1732  6948 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 02:46:22.182   278  1044 E BandwidthController: [LG DATA] No such appUid: 10006
08-30 02:46:22.182   278  1044 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-30 02:46:22.183   278  6951 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-30 02:46:22.183   278  6951 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 02:46:22.184   278  6951 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-30 02:46:22.184   278  6951 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-30 02:46:22.184   278  6951 D libc-netbsd: res_queryN name = xxxxx succeed
08-30 02:46:22.184  1732  6948 I System.out: propertyValue:false
08-30 02:46:22.200   282  1603 I WVCdm   : CdmEngine::CloseSession
,08-30 02:46:22.204   282  1603 I WVCdm   : L3 Terminate.
08-30 02:46:22.360   294   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-30 02:46:22.531   862  1823 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 02:46:22.868   862  1380 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 02:46:23.110   862  1785 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 02:46:23.352   862  1839 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 02:46:23.572   862  2214 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 02:46:23.689  1732  2396 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-30 02:46:25.741  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 02:46:25.742  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-30 02:46:25.742  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-30 02:46:26.112   862  1823 I ActivityManager: Killing 6571:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,08-30 02:46:26.199   862  3622 W libprocessgroup: failed to open /acct/uid_10038/pid_6571/cgroup.procs: No such file or directory
,08-30 02:46:27.365   294   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-30 02:46:27.744  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,08-30 02:46:27.744  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 02:46:27.744  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-30 02:46:30.617   862  1058 I PowerManagerService: ALS enabled for SRE
,08-30 02:46:30.625   862  1058 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26891 ms ago)
08-30 02:46:30.687   862  1349 D qdlights: set_light_backlight: 253
,08-30 02:46:30.696   862  1349 D qdlights: set_light_backlight: 250
08-30 02:46:30.712   862  1349 D qdlights: set_light_backlight: 246
,08-30 02:46:30.729   862  1349 D qdlights: set_light_backlight: 243
,08-30 02:46:30.746   862  1349 D qdlights: set_light_backlight: 240
,08-30 02:46:30.762   862  1349 D qdlights: set_light_backlight: 236
,08-30 02:46:30.779   862  1349 D qdlights: set_light_backlight: 233
,08-30 02:46:30.796   862  1349 D qdlights: set_light_backlight: 230
,08-30 02:46:30.812   862  1349 D qdlights: set_light_backlight: 226
,08-30 02:46:30.829   862  1349 D qdlights: set_light_backlight: 223
,08-30 02:46:30.853   862  1349 D qdlights: set_light_backlight: 220
,08-30 02:46:30.862   862  1349 D qdlights: set_light_backlight: 216
08-30 02:46:30.879   862  1349 D qdlights: set_light_backlight: 213
,08-30 02:46:30.896   862  1349 D qdlights: set_light_backlight: 210
,08-30 02:46:30.912   862  1349 D qdlights: set_light_backlight: 206
,08-30 02:46:30.929   862  1349 D qdlights: set_light_backlight: 203
,08-30 02:46:30.946   862  1349 D qdlights: set_light_backlight: 200
,08-30 02:46:30.962   862  1349 D qdlights: set_light_backlight: 196
,08-30 02:46:30.979   862  1349 D qdlights: set_light_backlight: 193
,08-30 02:46:30.996   862  1349 D qdlights: set_light_backlight: 190
,08-30 02:46:31.012   862  1349 D qdlights: set_light_backlight: 186
,08-30 02:46:31.029   862  1349 D qdlights: set_light_backlight: 183
,08-30 02:46:31.046   862  1349 D qdlights: set_light_backlight: 180
,08-30 02:46:31.062   862  1349 D qdlights: set_light_backlight: 176
,08-30 02:46:31.079   862  1349 D qdlights: set_light_backlight: 173
,08-30 02:46:31.096   862  1349 D qdlights: set_light_backlight: 170
,08-30 02:46:31.112   862  1349 D qdlights: set_light_backlight: 166
,08-30 02:46:31.129   862  1349 D qdlights: set_light_backlight: 163
,08-30 02:46:31.146   862  1349 D qdlights: set_light_backlight: 160
,08-30 02:46:31.162   862  1349 D qdlights: set_light_backlight: 156
,08-30 02:46:31.179   862  1349 D qdlights: set_light_backlight: 153
08-30 02:46:31.196   862  1349 D qdlights: set_light_backlight: 150
,08-30 02:46:31.213   862  1349 D qdlights: set_light_backlight: 146
08-30 02:46:31.229   862  1349 D qdlights: set_light_backlight: 143
,08-30 02:46:31.246   862  1349 D qdlights: set_light_backlight: 140
08-30 02:46:31.263   862  1349 D qdlights: set_light_backlight: 136
,08-30 02:46:31.279   862  1349 D qdlights: set_light_backlight: 133
,08-30 02:46:31.296   862  1349 D qdlights: set_light_backlight: 130
,08-30 02:46:31.312   862  1349 D qdlights: set_light_backlight: 126
,08-30 02:46:31.329   862  1349 D qdlights: set_light_backlight: 123
,08-30 02:46:31.346   862  1349 D qdlights: set_light_backlight: 120
,08-30 02:46:31.362   862  1349 D qdlights: set_light_backlight: 116
,08-30 02:46:31.379   862  1349 D qdlights: set_light_backlight: 113
,08-30 02:46:31.396   862  1349 D qdlights: set_light_backlight: 110
,08-30 02:46:31.412   862  1349 D qdlights: set_light_backlight: 106
,08-30 02:46:31.429   862  1349 D qdlights: set_light_backlight: 103
,08-30 02:46:31.446   862  1349 D qdlights: set_light_backlight: 100
,08-30 02:46:31.462   862  1349 D qdlights: set_light_backlight: 96
,08-30 02:46:31.479   862  1349 D qdlights: set_light_backlight: 93
,08-30 02:46:31.496   862  1349 D qdlights: set_light_backlight: 90
,08-30 02:46:31.513   862  1349 D qdlights: set_light_backlight: 86
,08-30 02:46:31.529   862  1349 D qdlights: set_light_backlight: 83
,08-30 02:46:31.546   862  1349 D qdlights: set_light_backlight: 80
,08-30 02:46:31.562   862  1349 D qdlights: set_light_backlight: 76
,08-30 02:46:31.579   862  1349 D qdlights: set_light_backlight: 73
,08-30 02:46:31.596   862  1349 D qdlights: set_light_backlight: 70
,08-30 02:46:31.612   862  1349 D qdlights: set_light_backlight: 66
,08-30 02:46:31.629   862  1349 D qdlights: set_light_backlight: 63
,08-30 02:46:31.646   862  1349 D qdlights: set_light_backlight: 60
,08-30 02:46:31.662   862  1349 D qdlights: set_light_backlight: 56
,08-30 02:46:31.679   862  1349 D qdlights: set_light_backlight: 53
,08-30 02:46:31.696   862  1349 D qdlights: set_light_backlight: 50
,08-30 02:46:31.712   862  1349 D qdlights: set_light_backlight: 46
,08-30 02:46:31.729   862  1349 D qdlights: set_light_backlight: 43
,08-30 02:46:31.746   862  1349 D qdlights: set_light_backlight: 40
08-30 02:46:31.751  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 02:46:31.752  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 02:46:31.752  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-30 02:46:31.763   862  1349 D qdlights: set_light_backlight: 36
,08-30 02:46:31.779   862  1349 D qdlights: set_light_backlight: 33
,08-30 02:46:31.796   862  1349 D qdlights: set_light_backlight: 30
,08-30 02:46:31.812   862  1349 D qdlights: set_light_backlight: 26
,08-30 02:46:31.829   862  1349 D qdlights: set_light_backlight: 23
,08-30 02:46:31.846   862  1349 D qdlights: set_light_backlight: 20
,08-30 02:46:31.862   862  1349 D qdlights: set_light_backlight: 16
,08-30 02:46:31.879   862  1349 D qdlights: set_light_backlight: 13
,08-30 02:46:31.896   862  1349 D qdlights: set_light_backlight: 10
,08-30 02:46:31.908  6629  6781 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 02:46:31.908  6629  6781 I jxcore-log: 
,08-30 02:46:31.916  6629  6781 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 02:46:31.916  6629  6781 I jxcore-log: 
08-30 02:46:31.922  2056  2077 D BluetoothAdapterService(413481539): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ff3f31
,08-30 02:46:31.923  6629  6781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 02:46:31.923  6629  6781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 02:46:31.923  6629  6781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 02:46:31.923  6629  6781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 02:46:31.923  6629  6781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 02:46:31.923  6629  6781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 02:46:31.923  6629  6781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 02:46:31.923  6629  6781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 02:46:31.936  2056  2077 D BluetoothAdapterService(413481539): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ff3f31
,08-30 02:46:31.941  6629  6781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 02:46:31.946  6629  6781 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 02:46:31.946  6629  6781 I jxcore-log: 
08-30 02:46:31.949  6629  6781 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 02:46:31.949  6629  6781 I jxcore-log: 
,08-30 02:46:32.369   294   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-30 02:46:32.507  6629  6781 I jxcore-log: Running unit tests
08-30 02:46:32.507  6629  6781 I jxcore-log: 
,08-30 02:46:32.508  6629  6781 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 02:46:32.509  6629  6781 I jxcore-log: Failed to execute UT.
08-30 02:46:32.509  6629  6781 I jxcore-log: 
08-30 02:46:32.511  6629  6781 I jxcore-log: Unit Test app is loaded
08-30 02:46:32.511  6629  6781 I jxcore-log: 
08-30 02:46:32.529  6629  6781 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 02:46:32.529  6629  6781 I jxcore-log: 
,08-30 02:46:32.536  6629  6781 I jxcore-log: My device name is: LGE-LG-D722
08-30 02:46:32.536  6629  6781 I jxcore-log: 
08-30 02:46:32.539  6629  6781 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 02:46:32.539  6629  6781 I jxcore-log: 
08-30 02:46:32.556  6629  6629 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 02:46:32.754  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 02:46:32.754  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 02:46:32.754  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-30 02:46:36.513  6629  6781 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 02:46:36.513  6629  6781 I jxcore-log: 
,08-30 02:46:36.766   862  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-30 02:46:36.766   862  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-30 02:46:36.766   862  1011 D sensors_hal_Time: tsOffsetIs: Apps: 153036427756; DSPS: 5106189; Offset : -2800209830
,08-30 02:46:37.215  6629  6781 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 02:46:37.215  6629  6781 I jxcore-log: 
,08-30 02:46:37.251  6629  6781 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 02:46:37.251  6629  6781 I jxcore-log: 
,08-30 02:46:37.374   294   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-30 02:46:37.609   862  1058 I PowerManagerService: ALS enabled for SRE
,08-30 02:46:37.609   862  1058 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33880 ms ago)
,08-30 02:46:37.612   862  1058 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
08-30 02:46:37.628   862  1058 I PowerManagerService: ALS enabled for SRE
08-30 02:46:37.628   862  1058 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33899 ms ago)
,08-30 02:46:37.653   862  1058 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,08-30 02:46:37.661   862  1058 I PowerManagerService: Sleeping (uid 1000)...
08-30 02:46:37.661   862  1058 D LPWGController: [updateScreenState] screen on = false
08-30 02:46:37.675   862  1058 D LPWGController: disable proximity sensor
,08-30 02:46:37.679   862  1058 D LPWGController: enable proximity sensor
08-30 02:46:37.689   862  1058 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2bae02b7] by com.android.server.power.ProximitySensorListener.enable():120
,08-30 02:46:37.697   862  1058 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
08-30 02:46:37.697   862  1058 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
08-30 02:46:37.697   862  1058 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
08-30 02:46:37.697   862  1058 I sensors_hal_Ctx: activate: handle is 48, enable
08-30 02:46:37.698   862  1058 V sensors_hal_Ctx: activate sensors is 1400000000000
08-30 02:46:37.698   862  1058 D sensors_hal_Thresh: enable: handle=48
08-30 02:46:37.698   862  1058 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
08-30 02:46:37.698   862  1058 D sensors_hal_Util: waitForResponse: timeout=1000
08-30 02:46:37.703   862  1012 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
08-30 02:46:37.703   862  1012 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
,08-30 02:46:37.705   862  1058 D sensors_hal_Thresh: enable: Received response: 0
08-30 02:46:37.705   862  1058 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33976 ms ago)
08-30 02:46:37.730   862  1058 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 02:46:37.730   862  1058 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 02:46:37.730   862  1058 I Adreno-EGL: Build Date: 03/02/15 Mon
08-30 02:46:37.730   862  1058 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-30 02:46:37.730   862  1058 I Adreno-EGL: Remote Branch: 
08-30 02:46:37.730   862  1058 I Adreno-EGL: Local Patches: 
08-30 02:46:37.730   862  1058 I Adreno-EGL: Reconstruct Branch: 
,08-30 02:46:37.768   244   271 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1251 us)
,08-30 02:46:37.931   434   997 I Sensors : sns_pwr.c(273):acquiring wakelock
08-30 02:46:37.932   862  1012 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,08-30 02:46:37.933   862  1012 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
08-30 02:46:37.933   862  1012 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
08-30 02:46:37.934   862  1012 D sensors_hal_Thresh: processInd: handle 48, count=1
08-30 02:46:37.934   862  1012 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
08-30 02:46:37.934   862  1012 I sensors_hal_Thresh: processInd : proximity state changed - FAR
08-30 02:46:37.934   862  1050 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
08-30 02:46:37.934   862  1050 D sensors_hal_Ctx: poll: count: 256
08-30 02:46:37.934   862  1050 I sensors_hal_Ctx: poll: released wakelock sensor_ind
08-30 02:46:37.934   862  1050 D sensors_hal_Util: waitForResponse: timeout=0
08-30 02:46:37.940   862  1058 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
08-30 02:46:37.941   862  1058 I LPWGController: current mode = 1  value = 1 1
08-30 02:46:37.941   862  1058 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
08-30 02:46:38.039   862  1058 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,08-30 02:46:38.282   862  1349 D qdlights: set_light_backlight: 0
,08-30 02:46:38.301   862  1058 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,08-30 02:46:38.308   862  1058 I sensors_hal_Ctx: activate: handle is 46, disable
08-30 02:46:38.308   862  1058 V sensors_hal_Ctx: activate sensors is 1000000000000
08-30 02:46:38.308   862  1058 D sensors_hal_LP2: enable: handle=46
08-30 02:46:38.308   862  1058 D sensors_hal_LP2: enable: Disabling sensor handle=46
08-30 02:46:38.308   862  1058 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
08-30 02:46:38.311   244   244 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
08-30 02:46:38.311   244   244 D qdhwcomposer: hwc_blank: Blanking display: 0
08-30 02:46:38.319   862  1056 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,08-30 02:46:38.320   862   862 V ActivityManager: Display changed displayId=0
,08-30 02:46:38.379   862  1038 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
08-30 02:46:38.379   862  1038 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
08-30 02:46:38.404  1749  1749 D DSDPConnection: Display #0 changed.
,08-30 02:46:38.515   244   244 D qdhwcomposer: hwc_blank: Done blanking display: 0
08-30 02:46:38.515   862  1349 D SurfaceControl: Excessive delay in setPowerMode(): 204ms
,08-30 02:46:38.517   244   682 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
08-30 02:46:38.517   862  1349 I QCOM PowerHAL: Got set_interactive hint
08-30 02:46:38.527  6629  6629 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 02:46:38.527  6629  6629 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 02:46:38.536  1374  1401 D KeyguardViewMediator: onScreenTurnedOff(3)
08-30 02:46:38.542  1332  1347 D SmartCoverViewMediator: onScreenTurnedOff(3)
,08-30 02:46:38.553  1332  1347 D SmartCoverViewMediator: notifyScreenOffLocked
08-30 02:46:38.554  1374  1401 D KeyguardViewMediator: notifyScreenOffLocked
08-30 02:46:38.555  1332  1332 D SmartCoverViewMediator: handleNotifyScreenOFF
,08-30 02:46:38.569  6629  6629 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2101aebb Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@37f571e, 16908290=android.view.AbsSavedState$1@37f571e}, android:focusedViewId=100}]}]
08-30 02:46:38.569  6629  6629 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 02:46:38.570  6629  6629 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 02:46:38.570  6629  6629 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-30 02:46:38.577  1374  1401 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
08-30 02:46:38.577  1374  1374 D KeyguardViewMediator: handleNotifyScreenOff
08-30 02:46:38.596  1374  1374 D ScreenTurnOffBySensor: unregisterProximitySensor
,08-30 02:46:38.606  1374  1374 D StatusBarWindowView: onScreenTurnedOff why = 3
08-30 02:46:38.614  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,08-30 02:46:38.614  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 02:46:38.614  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-30 02:46:38.617   862   862 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
08-30 02:46:38.623   282  1323 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 862
08-30 02:46:38.624   282  1323 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-30 02:46:38.624   282  1323 V voice   : voice_set_parameters: enter: screen_state=on
08-30 02:46:38.625   282  1323 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
,08-30 02:46:38.625   282  1323 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 02:46:38.625   282  1323 V voice   : voice_set_parameters: exit with code(0)
08-30 02:46:38.625   282  1323 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
08-30 02:46:38.625   282  1323 V msm8974_platform: platform_set_parameters: enter: screen_state=on
08-30 02:46:38.627   282  1323 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 02:46:38.628   282  1323 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 02:46:38.628   282  1323 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
08-30 02:46:38.628   282  1323 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-30 02:46:38.628   282  1323 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 02:46:38.635  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-30 02:46:38.636  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
,08-30 02:46:38.638   862  1309 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
08-30 02:46:39.359   862   995 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,08-30 02:46:39.366  1840  1840 I QCNEJ   : |CORE| sendScreenState: state:true
08-30 02:46:39.376  1803  1975 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
,08-30 02:46:39.381  1803  1975 D LEDService: stopPatternFlashing()
08-30 02:46:39.384  1803  1975 D qdlights: set_light_notifications: 0,0,0,0,3
08-30 02:46:39.386  1803  1975 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-30 02:46:39.386  1803  1975 D qdlights: set_light_notifications: 0,0,0,0,3
08-30 02:46:39.388  1803  1975 I LEDService: updateLightsLocked : turn off led
,08-30 02:46:39.389  1803  1975 D qdlights: set_light_notifications: 0,0,0,0,3
08-30 02:46:39.393  1803  1975 D LEDHandler: RESTART MSG
08-30 02:46:39.424   862  1882 D SplitWindow: check instance of lgWin Window{26657742 u0 SearchPanel}
,08-30 02:46:39.431  1803  1803 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
08-30 02:46:39.431   434   444 I Sensors : sns_pwr.c(301):releasing wakelock
08-30 02:46:39.432  1803  1803 D Cliptray Service: lockStatus = 0
08-30 02:46:39.435  1786  1786 D LNfcService: action : android.intent.action.SCREEN_ON
08-30 02:46:39.441  1786  6997 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
08-30 02:46:39.441  1786  6997 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
08-30 02:46:39.441  1786  6997 D LNfcService: isRequireNfcCRouting() return true
,08-30 02:46:39.441  1786  6997 D LNfcService: isHCERoutingtoHost() return : true
08-30 02:46:39.441  1786  6997 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-30 02:46:39.441  1786  6997 D NfcService: mEnableLPD: true
08-30 02:46:39.441  1786  6997 D NfcService: mEnableReader: false
08-30 02:46:39.441  1786  6997 D NfcService: mEnableHostRouting: true
08-30 02:46:39.441  1786  6997 D NfcService: newParams.techmask= mTechMask: default
08-30 02:46:39.441  1786  6997 D NfcService: mEnableLPD: true
08-30 02:46:39.441  1786  6997 D NfcService: mEnableReader: false
08-30 02:46:39.441  1786  6997 D NfcService: mEnableHostRouting: true
08-30 02:46:39.441  1786  6997 D NfcService: screenState= 3
08-30 02:46:39.442  1786  6997 D NfcService: Discovery configuration equal, not updating.
08-30 02:46:39.455   862  1823 D InputDispatcher: Window went away: Window{14f40e16 u0 SearchPanel}
,08-30 02:46:39.459  1374  1374 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
08-30 02:46:39.490  1374  1374 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,08-30 02:46:39.508   862   862 D Ulp_jni : JNI:system_update. Event-0
,08-30 02:46:39.536  1749  1749 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,08-30 02:46:39.546   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 02:46:39.546   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 02:46:39.547   862   862 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
,08-30 02:46:39.552  2851  2851 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:46:39
,08-30 02:46:39.555  2851  2851 D WeatherService: 2 : ACTION screen on
08-30 02:46:39.557  2851  2851 D WeatherService: 2 : shouldTimeTickRegistered : false
08-30 02:46:39.567  2851  2851 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 02:46:39.567  2851  2851 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:46:39
,08-30 02:46:39.580  4143  4143 D AppCleanupService: android.intent.action.SCREEN_ON
,08-30 02:46:39.600  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,08-30 02:46:39.600  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-30 02:46:39.600  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-30 02:46:39.611   282  1603 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 862
08-30 02:46:39.611   282  1603 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-30 02:46:39.611   282  1603 V voice   : voice_set_parameters: enter: screen_state=off
08-30 02:46:39.611   282  1603 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
08-30 02:46:39.611   282  1603 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 02:46:39.611   282  1603 V voice   : voice_set_parameters: exit with code(0)
08-30 02:46:39.611   282  1603 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
08-30 02:46:39.611   282  1603 V msm8974_platform: platform_set_parameters: enter: screen_state=off
08-30 02:46:39.611   282  1603 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 02:46:39.611   282  1603 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 02:46:39.611   282  1603 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-30 02:46:39.611   282  1603 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 02:46:39.613   862  1314 D WifiController: CMD_SCREEN_OFF 
08-30 02:46:39.613   862  1314 D WifiController: shouldWifiStayAwake TRUE
,08-30 02:46:39.623  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
08-30 02:46:39.623   862   995 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
08-30 02:46:39.638  1840  1840 I QCNEJ   : |CORE| sendScreenState: state:false
,08-30 02:46:39.642  1803  1975 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
08-30 02:46:39.642  1803  1975 D LEDService: stopPatternFlashing()
08-30 02:46:39.642  1803  1975 D qdlights: set_light_notifications: 0,0,0,0,3
08-30 02:46:39.644  1803  1975 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-30 02:46:39.644  1803  1975 D qdlights: set_light_notifications: 0,0,0,0,3
08-30 02:46:39.646  1803  1975 I LEDService: updateLightsLocked : turn on led
08-30 02:46:39.646  1803  1975 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
08-30 02:46:39.647  1803  1975 E LEDService: Can't handle this request of patternId:0
08-30 02:46:39.647  1803  1975 D LEDHandler: RESTART MSG
08-30 02:46:39.751   862  1818 I ActivityManager: Process com.google.android.talk (pid 6676) has died
,08-30 02:46:39.755  1803  1803 D VolumeVibrator: clear
08-30 02:46:39.760  1803  1803 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
08-30 02:46:39.761  1786  1786 D LNfcService: action : android.intent.action.SCREEN_OFF
08-30 02:46:39.764  1786  2186 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
,08-30 02:46:39.799  1876  1876 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,08-30 02:46:39.813  1749  1749 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,08-30 02:46:39.819   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 02:46:39.819   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 02:46:39.819   862   862 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
08-30 02:46:39.820  2851  2851 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:46:39
08-30 02:46:39.820  2851  2851 D WeatherService: 2 : ACTION screen off
08-30 02:46:39.823  2851  2851 D WeatherService: 2 : TimeTick Receiver Unregister
,08-30 02:46:39.823  2851  2851 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:46:39
08-30 02:46:39.826  4143  4143 D AppCleanupService: android.intent.action.SCREEN_OFF
,08-30 02:46:39.829  4143  7006 D AppCleanupService: AppUsageStatsSaveTask
,08-30 02:46:39.867  1786  2658 E NxpNfcJni: getReconnectState = 0x0
,08-30 02:46:39.869  1786  2186 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-30 02:46:39.869  1786  2186 D LCardEmulationManager: getDefaultRoute
08-30 02:46:39.870  1786  2186 D LNfcService: isRequireNfcCRouting() return true
08-30 02:46:39.870  1786  2186 D LNfcService: isHCERoutingtoHost() return : true
08-30 02:46:39.870  1786  2186 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-30 02:46:39.870  1786  2186 D NfcService: mEnableLPD: true
08-30 02:46:39.870  1786  2186 D NfcService: mEnableReader: false
08-30 02:46:39.870  1786  2186 D NfcService: mEnableHostRouting: true
08-30 02:46:39.870  1786  2186 D NfcService: newParams.techmask= mTechMask: 0
08-30 02:46:39.870  1786  2186 D NfcService: mEnableLPD: true
08-30 02:46:39.870  1786  2186 D NfcService: mEnableReader: false
08-30 02:46:39.870  1786  2186 D NfcService: mEnableHostRouting: true
08-30 02:46:39.870  1786  2186 D NfcService: screenState= 1
08-30 02:46:39.929  1786  2658 E NxpNfcJni: getReconnectState = 0x0
,08-30 02:46:40.008  6629  6781 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 02:46:40.008  6629  6781 I jxcore-log: 
,08-30 02:46:40.375  6629  6781 I jxcore-log: ERROR runTests: 
08-30 02:46:40.375  6629  6781 I jxcore-log: 
08-30 02:46:40.379  6629  6781 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 02:46:40.379  6629  6781 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 02:46:40.380  6629  6781 I jxcore-log: WARN testUtils: logCallback not set!
08-30 02:46:40.380  6629  6781 I jxcore-log: 
08-30 02:46:40.395  6629  6781 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:46:40.395  6629  6781 I jxcore-log:     _functionName: 'loadFile',
08-30 02:46:40.395  6629  6781 I jxcore-log:     _lineNumber: '26',
08-30 02:46:40.395  6629  6781 I jxcore-log:     _columnNumber: '11',
08-30 02:46:40.395  6629  6781 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 02:46:40.395  6629  6781 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:46:40.395  6629  6781 I jxcore-log:     _functionName: '',
08-30 02:46:40.395  6629  6781 I jxcore-log:     _lineNumber: '38',
08-30 02:46:40.395  6629  6781 I jxcore-log:     _columnNumber: '7',
08-30 02:46:40.395  6629  6781 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 02:46:40.395  6629  6781 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:46:40.395  6629  6781 I jxcore-log:     _functionName: '',
08-30 02:46:40.395  6629  6781 I jxcore-log:     _lineNumber: '35',
08-30 02:46:40.395  6629  6781 I jxcore-log:     _columnNumber: '3',
08-30 02:46:40.395  6629  6781 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 02:46:40.395  6629  6781 I jxcore-log:   { _fileName: 'module.js',
08-30 02:46:40.395  6629  6781 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 02:46:40.395  6629  6781 I jxcore-log:     _lineNumber: '621',
08-30 02:46:40.395  6629  6781 I jxcore-log:     _columnNumber: '8',
08-30 02:46:40.395  6629  6781 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 02:46:40.395  6629  6781 I jxcore-log:   { _fileName: 'module.js',
08-30 02:46:40.395  6629  6781 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 02:46:40.395  6629  6781 I jxcore-log:     _lineNumber: '651',
08-30 02:46:40.395  6629  6781 I jxcore-log:     _columnNumber: '1',
08-30 02:46:40.395  6629  6781 I jxcore-log:    
,08-30 02:46:40.395  6629  6781 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 02:46:40.395  6629  6781 I jxcore-log: 
08-30 02:46:40.396  6629  6781 E jxcore-log: Error: 
08-30 02:46:40.396  6629  6781 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 02:46:40.396  6629  6781 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 02:46:40.396  6629  6781 E jxcore-log: 
08-30 02:46:42.378   294   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-30 02:46:42.731  7010  7010 D AndroidRuntime: 
08-30 02:46:42.731  7010  7010 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 02:46:42.741  7010  7010 D AndroidRuntime: CheckJNI is OFF
08-30 02:46:43.008  7010  7010 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 02:46:43.045   862   996 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,08-30 02:46:43.049   862   996 I ActivityManager: Killing 6629:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
08-30 02:46:43.103   862   880 I WindowState: WIN DEATH: Window{f64ea2f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 02:46:43.107   862   880 D InputDispatcher: Focus left window: Window{f64ea2f u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 02:46:43.107   862   880 D InputDispatcher: Window went away: Window{f64ea2f u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 02:46:43.140   862  1064 W PackageSettings: Skipping PackageSetting{1fc19eef com.example.hello/10317} due to missing metadata
,08-30 02:46:43.163   862   996 I ActivityManager:   Force finishing activity ActivityRecord{14a17b78 u0 com.test.thalitest/.MainActivity t259}
,08-30 02:46:43.191   862   862 V ActivityManager: Display changed displayId=0
,08-30 02:46:43.195  1749  1749 D DSDPConnection: Display #0 changed.
08-30 02:46:43.211   862  2214 W ActivityManager: Spurious death for ProcessRecord{2961353 6629:com.test.thalitest/u0a30}, curProc for 6629: null
08-30 02:46:43.211   862  1064 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
,08-30 02:46:43.214   862  1064 I ActivityManager:   Force finishing activity ActivityRecord{14a17b78 u0 com.test.thalitest/.MainActivity t259 f}
08-30 02:46:43.214   862  1064 W ActivityManager: Duplicate finish request for ActivityRecord{14a17b78 u0 com.test.thalitest/.MainActivity t259 f}
,08-30 02:46:43.280  1876  1876 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
08-30 02:46:43.283  1374  1374 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-30 02:46:43.300  1732  2504 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 02:46:43.308  1876  1876 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
08-30 02:46:43.312  3661  3661 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 02:46:43.316  3661  3661 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 02:46:43.316  3661  3661 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 02:46:43.316  3661  3661 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-30 02:46:43.316  3661  3661 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 02:46:43.316  3661  3661 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 02:46:43.316  3661  3661 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 02:46:43.316  3661  3661 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-30 02:46:43.316  3661  3661 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:46:43.316  3661  3661 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:46:43.316  3661  3661 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-30 02:46:43.316  3661  3661 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,08-30 02:46:43.321  5665  5665 I art     : Explicit concurrent mark sweep GC freed 349(13KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/20MB, paused 926us total 104.464ms
08-30 02:46:43.323  1840  1840 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
08-30 02:46:43.328  1954  1954 I art     : Explicit concurrent mark sweep GC freed 2964(150KB) AllocSpace objects, 1(23KB) LOS objects, 39% free, 12MB/21MB, paused 2.358ms total 107.047ms
08-30 02:46:43.335   862  1289 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 02:46:43.364   862   996 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7035 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 02:46:43.403  1876  1876 I [LGHome]EVENT: [LauncherModel.java:1358:startLoader()]startLoader isLaunching=true
,08-30 02:46:43.404  1876  2006 I [LGHome]Launcher.Model: [LauncherModel.java:1475:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-30 02:46:43.405  1374  1374 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-30 02:46:43.436  1876  1876 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-30 02:46:43.437  1876  1876 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-30 02:46:43.438  1876  1876 I Activity: Activity.onPostResume() called 
,08-30 02:46:43.447  1374  1509 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 02:46:43.447  1374  1509 D KeyguardModel: createShortcutInfo...
08-30 02:46:43.448  1876  1876 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-30 02:46:43.451  1374  1509 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 02:46:43.451  1374  1509 D KeyguardModel: createShortcutInfo...
,08-30 02:46:43.457  1374  1509 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 02:46:43.465  1876  7053 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,08-30 02:46:43.467  1374  1509 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 02:46:43.469  1374  1509 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 02:46:43.469  1374  1509 D KeyguardModel: createShortcutInfo...
08-30 02:46:43.471  1374  1509 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 02:46:43.471  1374  1509 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 02:46:43.472  1374  1509 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 02:46:43.472  1374  1509 D KeyguardModel: createShortcutInfo...
08-30 02:46:43.474  1374  1509 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 02:46:43.474  1374  1509 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 02:46:43.476  1374  1509 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 02:46:43.476  1374  1509 D KeyguardModel: createShortcutInfo...
08-30 02:46:43.477  1374  1374 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-30 02:46:43.477  1374  1374 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-30 02:46:43.477   862  1054 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
,08-30 02:46:43.478   862  1054 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-30 02:46:43.478   862  1054 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-30 02:46:43.478  1374  1374 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-30 02:46:43.478   862  1054 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-30 02:46:43.479  1374  1374 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-30 02:46:43.479  1374  1374 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-30 02:46:43.479  1374  1374 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-30 02:46:43.479   862  1054 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-30 02:46:43.479   862  1054 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@23cb381c,  pkg=WindowManager.LayoutParams
08-30 02:46:43.479   862  1054 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-30 02:46:43.487  1374  1374 D KeyguardModel: handleShortcutListChanged...
08-30 02:46:43.490   862   880 D InputDispatcher: Focus entered window: Window{327c24 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,08-30 02:46:43.503  1374  1509 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 02:46:43.503  1374  1509 D KeyguardModel: createShortcutInfo...
08-30 02:46:43.506  1374  1509 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
,08-30 02:46:43.506  1374  1509 D KeyguardModel: createShortcutInfo...
08-30 02:46:43.507  1876  1876 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 02:46:43.508  1876  1876 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 02:46:43.508  1876  1876 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-30 02:46:43.537  7035  7035 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 02:46:43.537  7035  7035 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 02:46:43.538  7035  7035 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 02:46:43.538  1374  1509 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 02:46:43.539  1374  1509 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-30 02:46:43.539  1876  1876 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-30 02:46:43.543  1374  1509 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 02:46:43.543  1374  1509 D KeyguardModel: createShortcutInfo...
08-30 02:46:43.545  1374  1509 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 02:46:43.545  1374  1509 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 02:46:43.546  1374  1509 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 02:46:43.546  1374  1509 D KeyguardModel: createShortcutInfo...
08-30 02:46:43.547  1876  1876 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-30 02:46:43.550  1876  1876 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-30 02:46:43.560  1374  1509 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 02:46:43.561  1374  1509 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-30 02:46:43.573   862  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{350eac9a type 2 when 159828 com.android.systemui} when 159828
08-30 02:46:43.574  1374  1509 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 02:46:43.574  1374  1509 D KeyguardModel: createShortcutInfo...
,08-30 02:46:43.580  1374  1374 D KeyguardModel: handleShortcutListChanged...
08-30 02:46:43.597   862   862 I art     : Explicit concurrent mark sweep GC freed 59538(3MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 24MB/36MB, paused 6.879ms total 343.965ms
08-30 02:46:43.597   862  1064 I art     : WaitForGcToComplete blocked for 192.808ms for cause Explicit
,08-30 02:46:43.627   862  1882 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-30 02:46:43.628   862  1882 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6629 uid 10030
08-30 02:46:43.665  1876  1876 I [LGHome]Launcher.Model: [LauncherModel.java:2270:run()] LauncherModel bind current page shortcut
,08-30 02:46:43.678  1876  1876 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-30 02:46:43.689   862  1056 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{a9d5d70 u0 com.lge.launcher2/.Launcher t258} time:159959
,08-30 02:46:43.705  1876  1876 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,08-30 02:46:43.710  1876  1876 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,08-30 02:46:43.713  1876  1876 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-30 02:46:43.716   862   862 D administrator: Handling package changes for user 0
08-30 02:46:43.717  1876  1876 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-30 02:46:43.751  1876  1876 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,08-30 02:46:43.797  1876  1876 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-30 02:46:43.798  1876  1876 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
,08-30 02:46:43.798  1876  1876 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-30 02:46:43.843  1876  1876 W Resources: Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
08-30 02:46:43.846  1876  1876 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
08-30 02:46:43.847  1876  1876 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
08-30 02:46:43.848  1876  1876 W Resources: Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
08-30 02:46:43.852  1876  1876 W Resources: Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
,08-30 02:46:43.862  1876  1876 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
08-30 02:46:43.863  1876  1876 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
08-30 02:46:43.867  1876  1876 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
,08-30 02:46:43.869  1876  1876 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
08-30 02:46:43.869  7035  7035 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-30 02:46:43.870  1876  1876 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
08-30 02:46:43.883  1876  1876 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,08-30 02:46:43.892  7035  7035 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
08-30 02:46:43.894  1876  1876 W Resources: Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,08-30 02:46:43.927   862  1064 I art     : Explicit concurrent mark sweep GC freed 9645(1109KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 7.880ms total 329.683ms
,08-30 02:46:43.950  1786  1786 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-30 02:46:43.950  1786  1786 D LCardEmulationManager: getDefaultRoute
,08-30 02:46:44.019  1876  1876 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
08-30 02:46:44.021  7010  7010 D AndroidRuntime: Shutting down VM
,08-30 02:46:44.074   862  1064 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7058 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-30 02:46:44.094   862   995 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 02:46:44.108  1876  1876 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-30 02:46:44.108  1876  1876 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
,08-30 02:46:44.109   862   862 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 02:46:44.109   862   862 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 02:46:44.109  1876  1876 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
08-30 02:46:44.110  1876  1876 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-30 02:46:44.111   862   862 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 02:46:44.118   862  1352 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
08-30 02:46:44.124  1876  1876 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,08-30 02:46:44.127  1876  1876 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-30 02:46:44.127  1876  1876 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-30 02:46:44.130  1876  1876 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-30 02:46:44.132  1876  1876 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
08-30 02:46:44.134  1876  1876 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-30 02:46:44.136  1876  1876 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
08-30 02:46:44.137  1627  1627 E b       : Unable to connect to the editor to retrieve text... will retry later
08-30 02:46:44.138  1876  1876 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
08-30 02:46:44.145  1876  2173 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-30 02:46:44.145  1876  2173 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-30 02:46:44.148  1876  1876 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-30 02:46:44.148  1876  1876 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-30 02:46:44.201   862   995 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-30 02:46:44.210  1876  1876 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
08-30 02:46:44.237  7035  7035 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-30 02:46:44.244  1876  1876 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-30 02:46:44.244  1876  1876 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-30 02:46:44.244  1876  1876 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
08-30 02:46:44.245  1876  1876 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 02:46:44.246  1876  1876 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-30 02:46:44.290  1876  1876 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@260dd1f3 time:160560
,08-30 02:46:44.313  6738  6738 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-30 02:46:44.339  1876  1876 I art     : Explicit concurrent mark sweep GC freed 21974(1212KB) AllocSpace objects, 18(2MB) LOS objects, 39% free, 15MB/25MB, paused 822us total 47.876ms
,08-30 02:46:44.358   862   883 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7082 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,08-30 02:46:44.358   862   883 I ActivityManager: Killing 6759:com.android.gallery3d/u0a23 (adj 15): empty #11
08-30 02:46:44.389   862  1322 W libprocessgroup: failed to open /acct/uid_10023/pid_6759/cgroup.procs: No such file or directory

```
