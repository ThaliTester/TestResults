#### Test 794266502283b5d_thali05_LGE-LG-D722 Logs


```
--------- beginning of main
08-04 11:12:50.660  6675  6690 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-04 11:12:51.029  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-04 11:12:51.029  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-04 11:12:51.029  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
08-04 11:12:51.129  6710  6710 D AndroidRuntime: 
08-04 11:12:51.129  6710  6710 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-04 11:12:51.133  6710  6710 D AndroidRuntime: CheckJNI is OFF
08-04 11:12:51.319  6710  6710 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-04 11:12:51.344   852   870 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-04 11:12:51.405   852   870 D ActivityManager: setTaskToReturnTo : TaskRecord{f9c5c5c #255 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-04 11:12:51.405   852   870 D ActivityManager: setTaskToReturnTo : TaskRecord{f9c5c5c #255 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-04 11:12:51.421   852   870 D WindowStateEx: AppWindowTokenEx init.. 
08-04 11:12:51.436   852  1055 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-04 11:12:51.452  1949  1949 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-04 11:12:51.453   852  1055 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-04 11:12:51.462   852   870 D InputDispatcher: Focus left window: Window{b6b496f u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-04 11:12:51.467  6710  6710 D AndroidRuntime: Shutting down VM
08-04 11:12:51.477   852  1055 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-04 11:12:51.477   852  1055 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-04 11:12:51.508  6730  6730 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-04 11:12:51.512   852  1055 D SplitWindow: check instance of lgWin Window{2425daf4 u0 Starting com.test.thalitest}
08-04 11:12:51.538   852  1972 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6734 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-04 11:12:51.582  1949  1949 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-04 11:12:51.630  6730  6730 I dex2oat : dex2oat took 115.390ms (threads: 4)
08-04 11:12:51.640  1949  1949 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-04 11:12:51.655  6675  6690 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 11:12:51.655  6675  6690 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 11:12:51.655  6675  6690 I Adreno-EGL: Build Date: 03/02/15 Mon
08-04 11:12:51.655  6675  6690 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-04 11:12:51.655  6675  6690 I Adreno-EGL: Remote Branch: 
08-04 11:12:51.655  6675  6690 I Adreno-EGL: Local Patches: 
08-04 11:12:51.655  6675  6690 I Adreno-EGL: Reconstruct Branch: 
08-04 11:12:51.663   852  1899 I WindowStateAnimator: Starting window displayed
08-04 11:12:51.670   852  1045 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
,08-04 11:12:51.675   852  1045 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-04 11:12:51.677   852  1045 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-04 11:12:51.678   852  1045 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-04 11:12:51.678   852  1045 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-04 11:12:51.678   852  1045 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1db341ae,  pkg=WindowManager.LayoutParams
08-04 11:12:51.678   852  1045 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-04 11:12:51.695  2026  2026 I HotwordDetector: Closing mic
08-04 11:12:51.706  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-04 11:12:51.709  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-04 11:12:51.709  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-04 11:12:51.709  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-04 11:12:51.717  2026  2580 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@21199018
08-04 11:12:51.718  2026  2580 V AudioRecord: stop()
08-04 11:12:51.718  2026  2580 D AudioRecord: AudioRecord->stop()
08-04 11:12:51.727   282  2818 V AudioFlinger: RecordHandle::stop()
08-04 11:12:51.727   282  2818 V AudioFlinger: RecordThread::stop
08-04 11:12:51.730   282  2818 V AudioFlinger: Record stopped OK
08-04 11:12:51.732   282  2818 V AudioPolicyManager: stopInput() input 17
08-04 11:12:51.732   282  2818 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
08-04 11:12:51.732   282  2818 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
08-04 11:12:51.732   282  1062 V AudioPolicyService: AudioCommandThread() waking up
08-04 11:12:51.732   282  1062 V AudioPolicyService: AudioCommandThread() processing release audio patch
08-04 11:12:51.732   282  1062 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
08-04 11:12:51.733   282  1062 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
08-04 11:12:51.733   282  1062 V AudioFlinger: ThreadBase::setParameters() routing=0
08-04 11:12:51.733   282  1062 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-04 11:12:51.735   282  2609 V AudioFlinger: processConfigEvents_l() remaining events 1
08-04 11:12:51.736   282  2609 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3848000
08-04 11:12:51.740   282  2609 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
08-04 11:12:51.780   282  2609 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
08-04 11:12:51.780   282  2609 V audio_hw_primary: disable_audio_route: enter: usecase(7)
08-04 11:12:51.780   282  2609 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
08-04 11:12:51.780   282  2609 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-04 11:12:51.783   282  2609 V audio_hw_primary: disable_audio_route: exit
08-04 11:12:51.783   282  2609 E audio_hw_primary: disable_snd_device: enter 144
08-04 11:12:51.783   282  2609 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
08-04 11:12:51.783   282  2609 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
08-04 11:12:51.785   282  2609 V audio_hw_primary: stop_input_stream: exit: status(0)
08-04 11:12:51.785   282  2609 V audio_hw_primary: in_standby: exit:  status(0)
08-04 11:12:51.785   282  2609 V AudioFlinger: RecordThread: loop stopping
08-04 11:12:51.785   282  1062 V AudioPolicyService: AudioCommandThread() going to sleep
08-04 11:12:51.786   282  2818 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
08-04 11:12:51.786   282  2818 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
08-04 11:12:51.786   282  2818 V AudioPolicyService: AudioCommandThread() adding update audio patch list
08-04 11:12:51.786   282  2818 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
08-04 11:12:51.786   282  1063 V AudioPolicyService: AudioCommandThread() waking up
08-04 11:12:51.786   282  1063 V AudioPolicyService: AudioCommandThread() processing update audio patch list
08-04 11:12:51.787   282  1063 V AudioPolicyService: AudioCommandThread() going to sleep
08-04 11:12:51.788   282  2818 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
08-04 11:12:51.788   282  2818 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
08-04 11:12:51.788   282  1062 V AudioPolicyService: AudioCommandThread() waking up
08-04 11:12:51.789   282  1062 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
08-04 11:12:51.789   282  1062 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 282
08-04 11:12:51.789   282  1062 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
08-04 11:12:51.789   282  1062 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-04 11:12:51.789   282  2609 V AudioFlinger: RecordThread: loop starting
08-04 11:12:51.789   282  2609 V AudioFlinger: processConfigEvents_l() remaining events 1
08-04 11:12:51.789   282  2609 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
08-04 11:12:51.789   282  2609 V audio_hw_primary: in_set_parameters: exit: status(0)
08-04 11:12:51.789   282  2609 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3848000
08-04 11:12:51.789   282  2609 V AudioFlinger: RecordThread: loop stopping
08-04 11:12:51.789   282  1062 V AudioPolicyService: AudioCommandThread() going to sleep
08-04 11:12:51.793  6734  6734 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-04 11:12:51.795   852   994 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-04 11:12:51.795   852   994 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-04 11:12:51.795   852   994 D sensors_hal_Time: tsOffsetIs: Apps: 132997279536; DSPS: 4456354; Offset : -3013393267
08-04 11:12:51.795  2026  2580 V AudioRecord: stop()
08-04 11:12:51.799  2026  2580 V AudioRecord: stop()
08-04 11:12:51.799  2026  2580 V AudioRecord: stop()
08-04 11:12:51.800   282  1297 V AudioFlinger: RecordHandle::stop()
08-04 11:12:51.800   282  1297 V AudioFlinger: RecordThread::stop
08-04 11:12:51.800   282  2818 V AudioFlinger: releasing 16 from 2026 for -1
08-04 11:12:51.800   282  2818 V AudioFlinger:  decremented refcount to 0
08-04 11:12:51.800   282  1297 V AudioPolicyManager: releaseInput() 17
08-04 11:12:51.800   282  2818 V AudioFlinger: purging stale effects
08-04 11:12:51.800   282  1297 V AudioPolicyManager: closeInput(17)
08-04 11:12:51.800   282  1297 V AudioFlinger: closeInput() 17
08-04 11:12:51.800   282  1297 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-04 11:12:51.801   282  1297 V AudioFlinger: ThreadBase::exit
08-04 11:12:51.801  2890  2913 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-04 11:12:51.801  2080  2102 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-04 11:12:51.801   282  2609 V AudioFlinger: RecordThread: loop starting
08-04 11:12:51.801  3173  3188 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-04 11:12:51.801   282  2609 V AudioFlinger: RecordThread 0xb3848000 exiting
08-04 11:12:51.801   852  1972 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-04 11:12:51.801   282  1297 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546dd40)
08-04 11:12:51.801   282  1297 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
08-04 11:12:51.801   282  1297 V audio_hw_primary: in_standby: exit:  status(0)
08-04 11:12:51.801  1789  1819 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-04 11:12:51.801   282  1297 V AudioPolicyService: AudioCommandThread() adding update audio port list
08-04 11:12:51.801   282  1297 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
08-04 11:12:51.801   282  1063 V AudioPolicyService: AudioCommandThread() waking up
08-04 11:12:51.801   282  1063 V AudioPolicyService: AudioCommandThread() processing update audio port list
08-04 11:12:51.802  1372  1833 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-04 11:12:51.802   282  1063 V AudioPolicyService: AudioCommandThread() going to sleep
08-04 11:12:51.802   282  1297 V AudioPolicyManager: releaseInput() exit
08-04 11:12:51.802   282  1297 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
08-04 11:12:51.802   282  1297 V AudioFlinger: removeClient_l() pid 2026, calling pid 282
08-04 11:12:51.802  2026  2048 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-04 11:12:51.807  2026  2586 I HotwordRecognitionRnr: Stopping hotword detection.
08-04 11:12:51.815  2026  2595 I HotwordRecognitionRnr: Hotword detection finished
08-04 11:12:51.900  6675  6690 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 11:12:51.900  6675  6690 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 11:12:51.900  6675  6690 I Adreno-EGL: Build Date: 03/02/15 Mon
08-04 11:12:51.900  6675  6690 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-04 11:12:51.900  6675  6690 I Adreno-EGL: Remote Branch: 
08-04 11:12:51.900  6675  6690 I Adreno-EGL: Local Patches: 
08-04 11:12:51.900  6675  6690 I Adreno-EGL: Reconstruct Branch: 
08-04 11:12:51.913  6734  6734 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-04 11:12:51.967  6675  6690 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 11:12:51.967  6675  6690 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 11:12:51.967  6675  6690 I Adreno-EGL: Build Date: 03/02/15 Mon
08-04 11:12:51.967  6675  6690 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-04 11:12:51.967  6675  6690 I Adreno-EGL: Remote Branch: 
08-04 11:12:51.967  6675  6690 I Adreno-EGL: Local Patches: 
08-04 11:12:51.967  6675  6690 I Adreno-EGL: Reconstruct Branch: 
08-04 11:12:51.973  6734  6734 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 3167-3176)
08-04 11:12:51.973  6734  6734 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 11:12:52.001  6734  6734 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a21e1b9}
08-04 11:12:52.002  6734  6734 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 11:12:52.006  6734  6734 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-04 11:12:52.021  6734  6734 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-04 11:12:52.023  6734  6734 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 11:12:52.030  6734  6734 E SysUtils: ApplicationContext is null in ApplicationStatus
08-04 11:12:52.031  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-04 11:12:52.031  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-04 11:12:52.031  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-04 11:12:52.106  6734  6734 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-04 11:12:52.115  6734  6734 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-04 11:12:52.115  6734  6734 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-04 11:12:52.116  6734  6734 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 11:12:52.116  6734  6734 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 11:12:52.116  6734  6734 I Adreno-EGL: Build Date: 03/02/15 Mon
08-04 11:12:52.116  6734  6734 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-04 11:12:52.116  6734  6734 I Adreno-EGL: Remote Branch: 
08-04 11:12:52.116  6734  6734 I Adreno-EGL: Local Patches: 
08-04 11:12:52.116  6734  6734 I Adreno-EGL: Reconstruct Branch: 
08-04 11:12:52.214   282   282 V AudioPolicyService: registerClient() client 0xb57e94e0, uid 10030
08-04 11:12:52.235   852  1054 D BluetoothManagerService: Message: 20
08-04 11:12:52.236   852  1054 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ca6adb7:true
08-04 11:12:52.249  2080  2099 D BluetoothAdapterService(647820639): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3456a92d
08-04 11:12:52.358  6734  6734 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 11:12:52.370  6734  6734 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-04 11:12:52.376  6734  6734 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-04 11:12:52.380  6734  6734 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-04 11:12:52.380  6734  6734 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-04 11:12:52.394  6734  6734 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-04 11:12:52.404  6734  6734 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 11:12:52.404  6734  6734 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 11:12:52.454  6734  6734 I Activity: Activity.onPostResume() called 
08-04 11:12:52.462  6734  6782 D OpenGLRenderer: Render dirty regions requested: true
08-04 11:12:52.462  6734  6782 I OpenGLRenderer: Initialized EGL, version 1.4
08-04 11:12:52.475  6734  6782 D OpenGLRenderer: Enabling debug mode 0
08-04 11:12:52.493  6734  6734 D Atlas   : Validating map...
08-04 11:12:52.500   852  1856 D SplitWindow: check instance of lgWin Window{2f8872a7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-04 11:12:52.502   297   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
08-04 11:12:52.513  6734  6769 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-04 11:12:52.541   852  1899 D InputDispatcher: Focus entered window: Window{2f8872a7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-04 11:12:52.600   852   870 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-04 11:12:52.611   852  1055 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s114ms
08-04 11:12:52.613   852  1055 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{14df8b65 u0 com.test.thalitest/.MainActivity t255} time:133814
08-04 11:12:52.621  6734  6734 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3945866b time:133825
08-04 11:12:52.681  1763  6669 I art     : Explicit concurrent mark sweep GC freed 52843(3MB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 14MB/23MB, paused 2.367ms total 135.745ms
08-04 11:12:52.695  1763  6669 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-04 11:12:52.696  1763  6669 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-04 11:12:52.696  1763  6669 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-04 11:12:52.696  1763  6669 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-04 11:12:52.697   278  1048 E BandwidthController: [LG DATA] No such appUid: 10006
08-04 11:12:52.697   278  1048 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-04 11:12:52.697   278  6787 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-04 11:12:52.697   278  6787 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-04 11:12:52.698   278  6787 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-04 11:12:52.698   278  6787 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-04 11:12:52.698   278  6787 D libc-netbsd: res_queryN name = xxxxx succeed
08-04 11:12:52.699  1763  6669 I System.out: propertyValue:false
08-04 11:12:52.771  6734  6734 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6734
08-04 11:12:52.784  1763  6669 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-04 11:12:52.784  1763  6669 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-04 11:12:52.979   282   282 I WVCdm   : CdmEngine::CloseSession
08-04 11:12:52.984   282   282 I WVCdm   : L3 Terminate.
08-04 11:12:53.033  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-04 11:12:53.034  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-04 11:12:53.034  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,08-04 11:12:53.563  6734  6734 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-04 11:12:53.652  1763  1763 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=a32fe40a-a9a9-461d-9ac9-cd9a30651293
,08-04 11:12:53.684  1763  1763 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-04 11:12:53.686  1763  1763 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-04 11:12:53.730  6734  6785 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426134272
,08-04 11:12:53.739  6734  6785 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-04 11:12:53.739  6734  6785 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-04 11:12:53.739  6734  6785 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-04 11:12:53.739  6734  6785 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-04 11:12:53.739  6734  6785 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-04 11:12:53.739  6734  6785 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@141c600c added. We now have 1 listener(s)
08-04 11:12:53.744   852  1856 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:12:53.748  6734  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,08-04 11:12:53.751  6734  6785 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
,08-04 11:12:53.752  6734  6785 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:12:53.752  6734  6785 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:12:53.758  6734  6785 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-04 11:12:53.758  6734  6785 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-04 11:12:53.758  6734  6785 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-04 11:12:53.758  6734  6785 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-04 11:12:53.758  6734  6785 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-04 11:12:53.758  6734  6785 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-04 11:12:53.758  6734  6785 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-04 11:12:53.758  6734  6785 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-04 11:12:53.758  6734  6785 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-04 11:12:53.758  6734  6785 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-04 11:12:53.758  6734  6785 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-04 11:12:53.758  6734  6785 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-04 11:12:53.758  6734  6785 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-04 11:12:53.758  6734  6785 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-04 11:12:53.758  6734  6785 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b78e05b added. We now have 1 listener(s)
08-04 11:12:53.758  6734  6785 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:12:53.783  6734  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 11:12:53.783  6734  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-04 11:12:53.783  6734  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-04 11:12:53.784  6734  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-04 11:12:53.784  6734  6785 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-04 11:12:53.791  6734  6785 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:12:53.792   852  2189 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:12:53.792  6734  6785 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-04 11:12:53.803  2080  2099 D BluetoothAdapterService(647820639): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3456a92d
,08-04 11:12:53.804  6734  6785 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-04 11:12:53.805  6734  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:12:53.805  6734  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:12:53.805  6734  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:12:53.805  6734  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:12:53.805  6734  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:12:53.805  6734  6785 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:12:53.805  6734  6785 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:12:53.805  6734  6785 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:12:53.805  6734  6785 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-04 11:12:53.805  6734  6785 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 11:12:53.807  6734  6785 I io.jxcore.node.LifeCycleMonitor: start: OK
08-04 11:12:53.808  6734  6734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:12:53.809  6734  6734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:12:53.847  6734  6734 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-04 11:12:53.866  1763  2589 W GCoreFlp: No location to return for getLastLocation()
,08-04 11:12:53.911  1763  2545 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-04 11:12:53.913  3447  6794 D UdcContextInitService: registered all accounts: true
08-04 11:12:53.934  1763  2421 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-04 11:12:53.998  6734  6751 I art     : CheckpointMarkThreadRoots callback created = 0xb06a63c0
,08-04 11:12:54.033  6734  6751 I art     : CheckpointMarkThreadRoots callback created = 0xb06a6380
,08-04 11:12:54.035  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-04 11:12:54.035  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-04 11:12:54.035  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-04 11:12:54.196  6472  6670 I art     : Explicit concurrent mark sweep GC freed 1894(82KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 752us total 28.533ms
,08-04 11:12:54.228  1763  2421 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-04 11:12:54.241  1763  2421 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-04 11:12:54.286  1763  6813 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-04 11:12:54.287  1763  6811 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-04 11:12:54.306  1763  6818 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-04 11:12:54.306  1763  6818 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-04 11:12:54.307  1763  6818 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-04 11:12:54.307  1763  6818 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,08-04 11:12:54.307   278  1048 E BandwidthController: [LG DATA] No such appUid: 10006
08-04 11:12:54.307   278  1048 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-04 11:12:54.307   278  6820 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-04 11:12:54.308   278  6820 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-04 11:12:54.308   278  6820 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-04 11:12:54.308   278  6820 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-04 11:12:54.308   278  6820 D libc-netbsd: res_queryN name = xxxxx succeed
08-04 11:12:54.310  1763  6818 I System.out: propertyValue:false
08-04 11:12:54.312  1763  6813 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-04 11:12:54.313  1763  6811 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-04 11:12:54.341  1763  6813 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-04 11:12:54.341  1763  6811 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-04 11:12:54.341  1763  6811 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-04 11:12:54.347  1763  6811 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-04 11:12:54.400   852  1947 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-04 11:12:54.489  1763  6811 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-04 11:12:54.489  1763  6811 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-04 11:12:54.489  1763  6811 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-04 11:12:54.489  1763  6811 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-04 11:12:54.489   278  1048 E BandwidthController: [LG DATA] No such appUid: 10006
08-04 11:12:54.489   278  1048 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,08-04 11:12:54.491   278  6821 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-04 11:12:54.491   278  6821 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-04 11:12:54.491   278  6821 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-04 11:12:54.492   278  6821 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-04 11:12:54.492   278  6821 D libc-netbsd: res_queryN name = xxxxx succeed
08-04 11:12:54.501  1763  6811 I System.out: propertyValue:false
,08-04 11:12:54.585   852  2025 I art     : Explicit concurrent mark sweep GC freed 29517(1447KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.197ms total 183.615ms
,08-04 11:12:54.760  1763  2421 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-04 11:12:54.819  6734  6809 W jxcore-log: Initializing JXcore engine
08-04 11:12:54.819  6734  6809 W jxcore-log: JXcore engine is ready
,08-04 11:12:54.884   852  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3e94a5a type 2 when 136073 android} when 136073
,08-04 11:12:54.898  1763  6811 I art     : Explicit concurrent mark sweep GC freed 49558(2MB) AllocSpace objects, 15(261KB) LOS objects, 40% free, 15MB/25MB, paused 1.930ms total 134.052ms
,08-04 11:12:54.894  6809  6809 W Thread-814: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8279]" dev="sockfs" ino=8279 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-04 11:12:54.894  6809  6809 W Thread-814: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-04 11:12:54.894  6809  6809 W Thread-814: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6529]" dev="sockfs" ino=6529 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-04 11:12:54.894  6809  6809 W Thread-814: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-04 11:12:54.894  6809  6809 W Thread-814: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-04 11:12:54.894  6809  6809 W Thread-814: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[30080]" dev="sockfs" ino=30080 scontext=u:r:untrusted_app:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
08-04 11:12:54.920  6734  6809 W jxcore-log: Starting JXcore engine
,08-04 11:12:54.953   852  1856 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-04 11:12:55.035  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-04 11:12:55.035  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-04 11:12:55.035  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,08-04 11:12:55.069  6734  6809 W jxcore-log: Platform android
08-04 11:12:55.069  6734  6809 W jxcore-log: 
,08-04 11:12:55.069  6734  6809 W jxcore-log: Process ARCH arm
08-04 11:12:55.069  6734  6809 W jxcore-log: 
08-04 11:12:55.187   852  1947 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-04 11:12:55.382  6734  6809 I jxcore-log: JXcore Cordova bridge is ready!
08-04 11:12:55.382  6734  6809 I jxcore-log: 
,08-04 11:12:55.382  6734  6809 W jxcore-log: JXcore engine is started
08-04 11:12:55.387  6734  6785 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-04 11:12:55.389  6734  6734 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-04 11:12:55.420   852  1911 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-04 11:12:55.639   852  1378 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-04 11:12:55.860   852  1889 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-04 11:12:56.644  1763  2421 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-04 11:12:56.768   852  1286 V AlarmManager: RTC_WAKEUP set : Alarm{639b968 type 0 when 1470301976751 com.google.android.googlequicksearchbox} when 1470301976751
,08-04 11:12:56.774   244   244 E lowmemorykiller: Error writing /proc/6448/oom_score_adj; errno=22
08-04 11:12:56.856   852   870 I ActivityManager: Process com.google.android.apps.docs (pid 6448) has died
,08-04 11:12:57.506   297   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-04 11:12:58.042  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-04 11:12:58.042  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-04 11:12:58.042  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-04 11:12:58.751   282   282 V AudioFlinger: 2890 died, releasing its sessions
08-04 11:12:58.751   282   282 V AudioFlinger:  pid 1789 @ 0
08-04 11:12:58.751   282   282 V AudioFlinger:  pid 3173 @ 1
08-04 11:12:58.752   282   282 V AudioFlinger:  pid 3173 @ 2
,08-04 11:12:58.816   852  2086 I ActivityManager: Process com.lge.music (pid 2890) has died
,08-04 11:12:59.876   852  1911 I ActivityManager: Process com.android.contacts (pid 6385) has died
,08-04 11:13:00.002   852  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=775928273, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=852
,08-04 11:13:00.010  2877  2877 D WeatherService: 2 : TimeTick Intent has been received, Time(hour:min:sec) 11:13:0
08-04 11:13:00.011  2877  2877 D WeatherService: 2 : TimeTick Intent And Screen On
08-04 11:13:00.011  2877  2877 D WeatherService: 2 : SDK version : 21
08-04 11:13:00.012   852   869 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
08-04 11:13:00.013  2877  2877 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
08-04 11:13:00.013  2877  2877 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
08-04 11:13:00.013  2877  2877 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
08-04 11:13:00.014  2877  2877 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
,08-04 11:13:00.017  2877  2877 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-04 11:13:00.017  2877  2877 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
08-04 11:13:00.017  2877  2877 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
08-04 11:13:00.018  2877  2877 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
08-04 11:13:00.018  2877  2877 D WeatherTheme: 2 : Fixed theme : optimus
08-04 11:13:00.030  2877  2877 D WeatherReflect: 2 : Map key string is -2
,08-04 11:13:00.047  2877  2877 D lim     : 2 : time = 11:13
08-04 11:13:00.048  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-04 11:13:00.048  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
08-04 11:13:00.058  2877  2877 I WeatherReflect: Model Name : LG-D722
08-04 11:13:00.058  2877  2877 D WeatherTheme: 2 : Different view - status_min_formatted : 12 != 13
08-04 11:13:00.058  2877  2877 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,08-04 11:13:00.062  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
08-04 11:13:00.065  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
08-04 11:13:00.065  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
08-04 11:13:00.077  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
,08-04 11:13:00.080  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
08-04 11:13:00.082  2877  2877 D WeatherReflect: 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
08-04 11:13:00.086  2877  2877 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-04 11:13:00.086  2877  2877 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-04 11:13:00.086  2877  2877 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-04 11:13:00.086  2877  2877 D Weather4x2_optimus: currentPackage=com.lge.sizechangable.weather.theme.optimus
08-04 11:13:00.150  2877  2877 D Weather4x2_optimus: [[[[[[Theme package!!]]]]]] RemoteViews are created 2
08-04 11:13:00.150  2877  2877 D Weather4x2_optimus: widgetType = 1, orientation = 1
08-04 11:13:00.150  2877  2877 D Weather4x2_optimus: forecast size is 0
08-04 11:13:00.150  2877  2877 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-04 11:13:00.150  2877  2877 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-04 11:13:00.150  2877  2877 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,08-04 11:13:00.151  2877  2877 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-04 11:13:00.151  2877  2877 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-04 11:13:00.151  2877  2877 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-04 11:13:00.151  2877  2877 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-04 11:13:00.151  2877  2877 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-04 11:13:00.151  2877  2877 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-04 11:13:00.151  2877  2877 I Theme_WeatherAncestor_optimus: WEATHER_CP_ACCU : 
08-04 11:13:00.151  2877  2877 I Theme_WeatherAncestor_optimus: weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
08-04 11:13:00.151  2877  2877 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-04 11:13:00.151  2877  2877 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-04 11:13:00.151  2877  2877 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-04 11:13:00.152  2877  2877 D Theme_WeatherAncestor_optimus: setTouchIntent, appWidgetId: 2
08-04 11:13:00.163  2877  2877 D Theme_WeatherAncestor_optimus: url is : null
08-04 11:13:00.165  2877  2877 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-04 11:13:00.165  2877  2877 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-04 11:13:00.165  2877  2877 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-04 11:13:00.166  2877  2877 D WeatherAncestor: 2 : update view, appWidgetId: 2
,08-04 11:13:00.171  2877  2877 D WeatherService: 2 : TimeTick Intent has been processed, Time(hour:min:sec) 11:13:0
08-04 11:13:00.236   852  1284 I ActivityManager: Process com.lge.lockscreensettings (pid 6406) has died
08-04 11:13:00.239   852   852 D PowerManagerServiceEx: releaseWakeLockInternal: lock=775928273 [*alarm*], flags=0x0
,08-04 11:13:00.353  1949  1949 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,08-04 11:13:00.437  1949  1949 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-04 11:13:00.456   852  1972 I ActivityManager: Process com.lge.eula (pid 6426) has died
,08-04 11:13:01.051  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-04 11:13:01.051  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-04 11:13:01.051  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-04 11:13:02.511   297   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-04 11:13:03.053  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-04 11:13:03.054  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-04 11:13:03.054  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-04 11:13:04.057  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-04 11:13:04.057  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-04 11:13:04.057  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-04 11:13:05.207   852  1057 I PowerManagerService: ALS enabled for SRE
,08-04 11:13:05.208   852  1057 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26412 ms ago)
08-04 11:13:05.243   852  1350 D qdlights: set_light_backlight: 251
,08-04 11:13:05.257   852  1350 D qdlights: set_light_backlight: 248
,08-04 11:13:05.274   852  1350 D qdlights: set_light_backlight: 245
,08-04 11:13:05.291   852  1350 D qdlights: set_light_backlight: 241
,08-04 11:13:05.307   852  1350 D qdlights: set_light_backlight: 238
,08-04 11:13:05.324   852  1350 D qdlights: set_light_backlight: 235
,08-04 11:13:05.341   852  1350 D qdlights: set_light_backlight: 231
,08-04 11:13:05.357   852  1350 D qdlights: set_light_backlight: 228
,08-04 11:13:05.374   852  1350 D qdlights: set_light_backlight: 225
,08-04 11:13:05.391   852  1350 D qdlights: set_light_backlight: 221
,08-04 11:13:05.407   852  1350 D qdlights: set_light_backlight: 218
,08-04 11:13:05.424   852  1350 D qdlights: set_light_backlight: 215
,08-04 11:13:05.441   852  1350 D qdlights: set_light_backlight: 211
,08-04 11:13:05.457   852  1350 D qdlights: set_light_backlight: 208
,08-04 11:13:05.474   852  1350 D qdlights: set_light_backlight: 205
,08-04 11:13:05.496   852  1350 D qdlights: set_light_backlight: 201
,08-04 11:13:05.508   852  1350 D qdlights: set_light_backlight: 198
08-04 11:13:05.524   852  1350 D qdlights: set_light_backlight: 195
,08-04 11:13:05.541   852  1350 D qdlights: set_light_backlight: 191
,08-04 11:13:05.558   852  1350 D qdlights: set_light_backlight: 188
,08-04 11:13:05.574   852  1350 D qdlights: set_light_backlight: 185
,08-04 11:13:05.591   852  1350 D qdlights: set_light_backlight: 181
,08-04 11:13:05.608   852  1350 D qdlights: set_light_backlight: 178
,08-04 11:13:05.624   852  1350 D qdlights: set_light_backlight: 175
,08-04 11:13:05.641   852  1350 D qdlights: set_light_backlight: 171
,08-04 11:13:05.657   852  1350 D qdlights: set_light_backlight: 168
,08-04 11:13:05.674   852  1350 D qdlights: set_light_backlight: 165
,08-04 11:13:05.691   852  1350 D qdlights: set_light_backlight: 161
,08-04 11:13:05.707   852  1350 D qdlights: set_light_backlight: 158
,08-04 11:13:05.724   852  1350 D qdlights: set_light_backlight: 155
,08-04 11:13:05.741   852  1350 D qdlights: set_light_backlight: 151
,08-04 11:13:05.757   852  1350 D qdlights: set_light_backlight: 148
,08-04 11:13:05.774   852  1350 D qdlights: set_light_backlight: 145
,08-04 11:13:05.791   852  1350 D qdlights: set_light_backlight: 141
,08-04 11:13:05.807   852  1350 D qdlights: set_light_backlight: 138
,08-04 11:13:05.824   852  1350 D qdlights: set_light_backlight: 135
,08-04 11:13:05.841   852  1350 D qdlights: set_light_backlight: 131
,08-04 11:13:05.857   852  1350 D qdlights: set_light_backlight: 128
,08-04 11:13:05.874   852  1350 D qdlights: set_light_backlight: 125
,08-04 11:13:05.891   852  1350 D qdlights: set_light_backlight: 121
,08-04 11:13:05.907   852  1350 D qdlights: set_light_backlight: 118
,08-04 11:13:05.924   852  1350 D qdlights: set_light_backlight: 115
,08-04 11:13:05.941   852  1350 D qdlights: set_light_backlight: 111
,08-04 11:13:05.957   852  1350 D qdlights: set_light_backlight: 108
,08-04 11:13:05.974   852  1350 D qdlights: set_light_backlight: 105
,08-04 11:13:05.991   852  1350 D qdlights: set_light_backlight: 101
,08-04 11:13:06.008   852  1350 D qdlights: set_light_backlight: 98
,08-04 11:13:06.024   852  1350 D qdlights: set_light_backlight: 95
,08-04 11:13:06.041   852  1350 D qdlights: set_light_backlight: 91
,08-04 11:13:06.059   852  1350 D qdlights: set_light_backlight: 88
,08-04 11:13:06.060  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-04 11:13:06.060  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-04 11:13:06.060  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-04 11:13:06.074   852  1350 D qdlights: set_light_backlight: 85
,08-04 11:13:06.092   852  1350 D qdlights: set_light_backlight: 81
,08-04 11:13:06.107   852  1350 D qdlights: set_light_backlight: 78
,08-04 11:13:06.124   852  1350 D qdlights: set_light_backlight: 75
,08-04 11:13:06.141   852  1350 D qdlights: set_light_backlight: 71
,08-04 11:13:06.157   852  1350 D qdlights: set_light_backlight: 68
,08-04 11:13:06.174   852  1350 D qdlights: set_light_backlight: 65
,08-04 11:13:06.191   852  1350 D qdlights: set_light_backlight: 61
,08-04 11:13:06.207   852  1350 D qdlights: set_light_backlight: 58
,08-04 11:13:06.224   852  1350 D qdlights: set_light_backlight: 55
,08-04 11:13:06.241   852  1350 D qdlights: set_light_backlight: 51
,08-04 11:13:06.262   852  1350 D qdlights: set_light_backlight: 48
,08-04 11:13:06.274   852  1350 D qdlights: set_light_backlight: 45
,08-04 11:13:06.291   852  1350 D qdlights: set_light_backlight: 41
,08-04 11:13:06.307   852  1350 D qdlights: set_light_backlight: 38
,08-04 11:13:06.324   852  1350 D qdlights: set_light_backlight: 35
,08-04 11:13:06.341   852  1350 D qdlights: set_light_backlight: 31
,08-04 11:13:06.357   852  1350 D qdlights: set_light_backlight: 28
,08-04 11:13:06.374   852  1350 D qdlights: set_light_backlight: 25
,08-04 11:13:06.391   852  1350 D qdlights: set_light_backlight: 21
,08-04 11:13:06.407   852  1350 D qdlights: set_light_backlight: 18
,08-04 11:13:06.424   852  1350 D qdlights: set_light_backlight: 15
,08-04 11:13:06.441   852  1350 D qdlights: set_light_backlight: 11
,08-04 11:13:06.458   852  1350 D qdlights: set_light_backlight: 10
,08-04 11:13:07.062  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-04 11:13:07.062  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-04 11:13:07.062  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-04 11:13:07.516   297   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-04 11:13:09.066  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-04 11:13:09.066  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-04 11:13:09.066  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-04 11:13:10.068  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-04 11:13:10.068  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-04 11:13:10.068  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-04 11:13:11.794   852   994 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-04 11:13:11.794   852   994 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-04 11:13:11.795   852   994 D sensors_hal_Time: tsOffsetIs: Apps: 152998004269; DSPS: 5111738; Offset : -3013399185
,08-04 11:13:12.073  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-04 11:13:12.074  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-04 11:13:12.074  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-04 11:13:12.207   852  1057 I PowerManagerService: ALS enabled for SRE
08-04 11:13:12.207   852  1057 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33410 ms ago)
,08-04 11:13:12.211   852  1057 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
08-04 11:13:12.220   852  1057 I PowerManagerService: ALS enabled for SRE
08-04 11:13:12.220   852  1057 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33424 ms ago)
,08-04 11:13:12.224   852  1057 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
08-04 11:13:12.226   852  1057 I PowerManagerService: Sleeping (uid 1000)...
08-04 11:13:12.226   852  1057 D LPWGController: [updateScreenState] screen on = false
08-04 11:13:12.230   852  1057 D LPWGController: disable proximity sensor
08-04 11:13:12.230   852  1057 D LPWGController: enable proximity sensor
08-04 11:13:12.240   852  1057 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@17f904bd] by com.android.server.power.ProximitySensorListener.enable():120
,08-04 11:13:12.245   852  1057 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
08-04 11:13:12.245   852  1057 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
08-04 11:13:12.245   852  1057 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
08-04 11:13:12.245   852  1057 I sensors_hal_Ctx: activate: handle is 48, enable
08-04 11:13:12.245   852  1057 V sensors_hal_Ctx: activate sensors is 1400000000000
08-04 11:13:12.245   852  1057 D sensors_hal_Thresh: enable: handle=48
08-04 11:13:12.245   852  1057 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
08-04 11:13:12.246   852  1057 D sensors_hal_Util: waitForResponse: timeout=1000
08-04 11:13:12.250   852   995 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
08-04 11:13:12.250   852   995 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
08-04 11:13:12.250   852  1057 D sensors_hal_Thresh: enable: Received response: 0
08-04 11:13:12.250   852  1057 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33454 ms ago)
08-04 11:13:12.259   852  1057 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 11:13:12.259   852  1057 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 11:13:12.259   852  1057 I Adreno-EGL: Build Date: 03/02/15 Mon
08-04 11:13:12.259   852  1057 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-04 11:13:12.259   852  1057 I Adreno-EGL: Remote Branch: 
08-04 11:13:12.259   852  1057 I Adreno-EGL: Local Patches: 
08-04 11:13:12.259   852  1057 I Adreno-EGL: Reconstruct Branch: 
,08-04 11:13:12.287   247   270 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1019 us)
,08-04 11:13:12.478   430   980 I Sensors : sns_pwr.c(273):acquiring wakelock
,08-04 11:13:12.480   852   995 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
08-04 11:13:12.481   852   995 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
08-04 11:13:12.481   852   995 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
08-04 11:13:12.481   852   995 D sensors_hal_Thresh: processInd: handle 48, count=1
08-04 11:13:12.481   852   995 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
08-04 11:13:12.481   852   995 I sensors_hal_Thresh: processInd : proximity state changed - NEAR
08-04 11:13:12.481   852  1029 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:0.000000 y:-0.000007 z:0.000000
08-04 11:13:12.482   852  1029 D sensors_hal_Ctx: poll: count: 256
08-04 11:13:12.482   852  1029 I sensors_hal_Ctx: poll: released wakelock sensor_ind
08-04 11:13:12.482   852  1029 D sensors_hal_Util: waitForResponse: timeout=0
08-04 11:13:12.485   852  1057 D LPWGController: proximity onSensorChanged : proximity = 0, mSensorCovered=false, isFar=false
08-04 11:13:12.485   852  1057 I LPWGController: current mode = 0  value = 1 0
08-04 11:13:12.486   852  1057 I LPWGController: [setLPWGmode2] current mode = 0  value = 9 0 1 0 0
08-04 11:13:12.521   297   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-04 11:13:12.581   852  1057 I LPWGController: [setLPWGmode2] current mode = 0  value = 9 0 0 0 0
,08-04 11:13:12.810   852  1350 D qdlights: set_light_backlight: 0
,08-04 11:13:12.830   852  1057 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,08-04 11:13:12.835   852  1057 I sensors_hal_Ctx: activate: handle is 46, disable
08-04 11:13:12.835   852  1057 V sensors_hal_Ctx: activate sensors is 1000000000000
08-04 11:13:12.835   852  1057 D sensors_hal_LP2: enable: handle=46
08-04 11:13:12.836   852  1057 D sensors_hal_LP2: enable: Disabling sensor handle=46
08-04 11:13:12.836   852  1057 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
08-04 11:13:12.838   247   247 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
08-04 11:13:12.838   247   247 D qdhwcomposer: hwc_blank: Blanking display: 0
08-04 11:13:12.847   852  1055 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
08-04 11:13:12.848   852   852 V ActivityManager: Display changed displayId=0
,08-04 11:13:12.898  1789  1789 D DSDPConnection: Display #0 changed.
,08-04 11:13:12.907   852  1021 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
08-04 11:13:12.907   852  1021 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,08-04 11:13:13.043   247   247 D qdhwcomposer: hwc_blank: Done blanking display: 0
08-04 11:13:13.043   852  1350 D SurfaceControl: Excessive delay in setPowerMode(): 205ms
08-04 11:13:13.044   247   691 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-04 11:13:13.046   852  1350 I QCOM PowerHAL: Got set_interactive hint
,08-04 11:13:13.057  6734  6734 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-04 11:13:13.060  6734  6734 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
08-04 11:13:13.064  1372  2573 D KeyguardViewMediator: onScreenTurnedOff(3)
08-04 11:13:13.072  1333  1348 D SmartCoverViewMediator: onScreenTurnedOff(3)
,08-04 11:13:13.079  1372  2573 D KeyguardViewMediator: notifyScreenOffLocked
08-04 11:13:13.089  1333  1348 D SmartCoverViewMediator: notifyScreenOffLocked
,08-04 11:13:13.091  1333  1333 D SmartCoverViewMediator: handleNotifyScreenOFF
08-04 11:13:13.107  6734  6734 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@251a3157 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1d21b70f, 16908290=android.view.AbsSavedState$1@1d21b70f}, android:focusedViewId=100}]}]
08-04 11:13:13.107  6734  6734 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-04 11:13:13.107  6734  6734 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-04 11:13:13.107  6734  6734 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-04 11:13:13.113  1372  2573 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
08-04 11:13:13.113  1372  1372 D KeyguardViewMediator: handleNotifyScreenOff
08-04 11:13:13.137  1372  1372 D ScreenTurnOffBySensor: unregisterProximitySensor
,08-04 11:13:13.142  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-04 11:13:13.142  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-04 11:13:13.142  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-04 11:13:13.146   852   852 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
08-04 11:13:13.150  1372  1372 D StatusBarWindowView: onScreenTurnedOff why = 3
,08-04 11:13:13.163   282  1324 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 852
08-04 11:13:13.164   282  1324 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-04 11:13:13.164   282  1324 V voice   : voice_set_parameters: enter: screen_state=on
08-04 11:13:13.166   282  1324 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
08-04 11:13:13.166   282  1324 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-04 11:13:13.166   282  1324 V voice   : voice_set_parameters: exit with code(0)
08-04 11:13:13.166   282  1324 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
08-04 11:13:13.166   282  1324 V msm8974_platform: platform_set_parameters: enter: screen_state=on
08-04 11:13:13.166   282  1324 V msm8974_platform: platform_set_parameters: exit with code(0)
08-04 11:13:13.166   282  1324 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-04 11:13:13.166   282  1324 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
08-04 11:13:13.166   282  1324 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-04 11:13:13.166   282  1324 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-04 11:13:13.171  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
08-04 11:13:13.173  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
08-04 11:13:13.175   852  1308 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
,08-04 11:13:13.622   852  1004 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,08-04 11:13:13.658   852  1857 D SplitWindow: check instance of lgWin Window{9d84d80 u0 SearchPanel}
,08-04 11:13:13.667  1912  1912 I QCNEJ   : |CORE| sendScreenState: state:true
08-04 11:13:13.673  1875  2049 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
,08-04 11:13:13.676  1875  2049 D LEDService: stopPatternFlashing()
08-04 11:13:13.676  1875  2049 D qdlights: set_light_notifications: 0,0,0,0,3
08-04 11:13:13.678  1875  2049 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-04 11:13:13.678  1875  2049 D qdlights: set_light_notifications: 0,0,0,0,3
08-04 11:13:13.679  1875  2049 I LEDService: updateLightsLocked : turn off led
08-04 11:13:13.679  1875  2049 D qdlights: set_light_notifications: 0,0,0,0,3
08-04 11:13:13.681   852   869 D InputDispatcher: Window went away: Window{28ccf483 u0 SearchPanel}
08-04 11:13:13.683  1372  1372 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
08-04 11:13:13.684  1875  2049 D LEDHandler: RESTART MSG
,08-04 11:13:13.703  1372  1372 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,08-04 11:13:13.711  1875  1875 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
08-04 11:13:13.713  1875  1875 D Cliptray Service: lockStatus = 0
08-04 11:13:13.716  1858  1858 D LNfcService: action : android.intent.action.SCREEN_ON
08-04 11:13:13.726  1858  6897 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
08-04 11:13:13.726  1858  6897 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
08-04 11:13:13.726  1858  6897 D LNfcService: isRequireNfcCRouting() return true
,08-04 11:13:13.727  1858  6897 D LNfcService: isHCERoutingtoHost() return : true
08-04 11:13:13.728  1858  6897 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-04 11:13:13.728  1858  6897 D NfcService: mEnableLPD: true
08-04 11:13:13.728  1858  6897 D NfcService: mEnableReader: false
08-04 11:13:13.728  1858  6897 D NfcService: mEnableHostRouting: true
08-04 11:13:13.728  1858  6897 D NfcService: newParams.techmask= mTechMask: default
08-04 11:13:13.728  1858  6897 D NfcService: mEnableLPD: true
08-04 11:13:13.728  1858  6897 D NfcService: mEnableReader: false
08-04 11:13:13.728  1858  6897 D NfcService: mEnableHostRouting: true
08-04 11:13:13.728  1858  6897 D NfcService: screenState= 3
08-04 11:13:13.728  1858  6897 D NfcService: Discovery configuration equal, not updating.
08-04 11:13:13.738   852   852 D Ulp_jni : JNI:system_update. Event-0
,08-04 11:13:13.762  1789  1789 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
08-04 11:13:13.773   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:13:13.773   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:13:13.773   852   852 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
,08-04 11:13:13.777  2877  2877 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:13:13
08-04 11:13:13.779  2877  2877 D WeatherService: 2 : ACTION screen on
08-04 11:13:13.781  2877  2877 D WeatherService: 2 : shouldTimeTickRegistered : false
08-04 11:13:13.786  2877  2877 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-04 11:13:13.786  2877  2877 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:13:13
,08-04 11:13:13.796  4173  4173 D AppCleanupService: android.intent.action.SCREEN_ON
,08-04 11:13:13.824   282   282 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 852
08-04 11:13:13.824   282   282 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-04 11:13:13.824   282   282 V voice   : voice_set_parameters: enter: screen_state=off
08-04 11:13:13.824   282   282 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
08-04 11:13:13.824   282   282 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-04 11:13:13.824   282   282 V voice   : voice_set_parameters: exit with code(0)
08-04 11:13:13.824   282   282 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
08-04 11:13:13.824   282   282 V msm8974_platform: platform_set_parameters: enter: screen_state=off
08-04 11:13:13.824   282   282 V msm8974_platform: platform_set_parameters: exit with code(0)
08-04 11:13:13.824   282   282 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-04 11:13:13.824   282   282 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-04 11:13:13.825   282   282 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-04 11:13:13.827   852  1314 D WifiController: CMD_SCREEN_OFF 
08-04 11:13:13.827   852  1314 D WifiController: shouldWifiStayAwake TRUE
,08-04 11:13:13.833  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
08-04 11:13:13.833   852  1004 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,08-04 11:13:13.862  1912  1912 I QCNEJ   : |CORE| sendScreenState: state:false
08-04 11:13:13.863  1875  2049 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
08-04 11:13:13.863  1875  2049 D LEDService: stopPatternFlashing()
,08-04 11:13:13.863  1875  2049 D qdlights: set_light_notifications: 0,0,0,0,3
08-04 11:13:13.865  1875  2049 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-04 11:13:13.865  1875  2049 D qdlights: set_light_notifications: 0,0,0,0,3
08-04 11:13:13.867  1875  1875 D VolumeVibrator: clear
08-04 11:13:13.867  1875  2049 I LEDService: updateLightsLocked : turn on led
08-04 11:13:13.867  1875  2049 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
08-04 11:13:13.868  1875  2049 E LEDService: Can't handle this request of patternId:0
08-04 11:13:13.868  1875  2049 D LEDHandler: RESTART MSG
08-04 11:13:13.868  1875  1875 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
08-04 11:13:13.869  1858  1858 D LNfcService: action : android.intent.action.SCREEN_OFF
08-04 11:13:13.876  1858  2162 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
,08-04 11:13:13.888  1949  1949 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
08-04 11:13:13.902  1789  1789 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,08-04 11:13:13.910   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:13:13.910   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:13:13.910   852   852 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
08-04 11:13:13.911  2877  2877 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 11:13:13
08-04 11:13:13.911  2877  2877 D WeatherService: 2 : ACTION screen off
08-04 11:13:13.913  2877  2877 D WeatherService: 2 : TimeTick Receiver Unregister
08-04 11:13:13.914  2877  2877 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 11:13:13
08-04 11:13:13.918  4173  4173 D AppCleanupService: android.intent.action.SCREEN_OFF
08-04 11:13:13.921  4173  6906 D AppCleanupService: AppUsageStatsSaveTask
,08-04 11:13:13.978   430   451 I Sensors : sns_pwr.c(301):releasing wakelock
,08-04 11:13:13.991  1858  2697 E NxpNfcJni: getReconnectState = 0x0
,08-04 11:13:13.994  1858  2162 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-04 11:13:13.994  1858  2162 D LCardEmulationManager: getDefaultRoute
08-04 11:13:13.995  1858  2162 D LNfcService: isRequireNfcCRouting() return true
08-04 11:13:13.995  1858  2162 D LNfcService: isHCERoutingtoHost() return : true
,08-04 11:13:13.995  1858  2162 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-04 11:13:13.995  1858  2162 D NfcService: mEnableLPD: true
08-04 11:13:13.995  1858  2162 D NfcService: mEnableReader: false
08-04 11:13:13.995  1858  2162 D NfcService: mEnableHostRouting: true
08-04 11:13:13.995  1858  2162 D NfcService: newParams.techmask= mTechMask: 0
08-04 11:13:13.995  1858  2162 D NfcService: mEnableLPD: true
08-04 11:13:13.995  1858  2162 D NfcService: mEnableReader: false
08-04 11:13:13.995  1858  2162 D NfcService: mEnableHostRouting: true
08-04 11:13:13.995  1858  2162 D NfcService: screenState= 1
08-04 11:13:14.017  1858  2697 E NxpNfcJni: getReconnectState = 0x0
,08-04 11:13:17.195  6734  6809 E jxcore  : Error!: Cannot find module '../thalilogger'
08-04 11:13:17.195  6734  6809 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w._oldRes","_lineNumber":"802","_columnNumber":"9","_msg":"    at $w._oldRes@module.js:802:9"},{"_fileName":"module.js","_functionName":"$w._resolveFilename","_lineNumber":"1771","_columnNumber":"1","_msg":"    at $w._resolveFilename@module.js:1771:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"362","_columnNumber":"4","_msg":"    at $w._load@module.js:362:4"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js","_functionName":"","_lineNumber":"5","_columnNumber":"14","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"}]
,08-04 11:13:17.202  6734  6734 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "Cannot find module '../thalilogger'\nError: Cannot find module '../thalilogger'\n    at $w._oldRes@module.js:802:9\n    at $w._resolveFilename@module.js:1771:1\n    at $w._load@module.js:362:4\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"", source: file:///android_asset/www/js/thali_main.js (57)
,08-04 11:13:17.202  6734  6734 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,08-04 11:13:17.210   852   869 D InputDispatcher: Focus left window: Window{2f8872a7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-04 11:13:17.220  6734  6734 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-04 11:13:17.220  6734  6734 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-04 11:13:17.222  6734  6734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:13:17.222  6734  6734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:13:17.223  6734  6734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:13:17.223  6734  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:13:17.223  6734  6734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@141c600c removed from the list
,08-04 11:13:17.223  6734  6734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:13:17.223  6734  6734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b78e05b removed from the list
08-04 11:13:17.223  6734  6734 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:13:17.223  6734  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-04 11:13:17.225  6734  6734 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-04 11:13:17.261   852  1857 D InputDispatcher: Window went away: Window{2f8872a7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-04 11:13:17.282   852   852 V ActivityManager: Display changed displayId=0
08-04 11:13:17.287  1789  1789 D DSDPConnection: Display #0 changed.
,08-04 11:13:17.316  1949  1949 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
,08-04 11:13:17.356  1949  1949 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,08-04 11:13:17.379  1949  1949 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-04 11:13:17.382  1949  1949 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-04 11:13:17.382  1949  1949 I Activity: Activity.onPostResume() called 
08-04 11:13:17.384  2877  2877 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 11:13:17
08-04 11:13:17.386  2877  2877 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-04 11:13:17.387  2877  2877 D WeatherService: 2 : shouldTimeTickRegistered : false
08-04 11:13:17.387  2877  2877 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 11:13:17
08-04 11:13:17.387  2877  2877 D WeatherService: 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
08-04 11:13:17.388  2877  2877 D WeatherService: 2 : shouldTimeTickRegistered : false
08-04 11:13:17.393  1949  1949 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
,08-04 11:13:17.406  1949  6922 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,08-04 11:13:17.414   852  1045 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-04 11:13:17.415   852  1045 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-04 11:13:17.415  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-04 11:13:17.415  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-04 11:13:17.415  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-04 11:13:17.415  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-04 11:13:17.416   852  1045 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-04 11:13:17.416   852  1045 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-04 11:13:17.416   852  1045 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-04 11:13:17.417   852  1045 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1db341ae,  pkg=WindowManager.LayoutParams
08-04 11:13:17.417   852  1045 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-04 11:13:17.418   852  1899 D InputDispatcher: Focus entered window: Window{b6b496f u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-04 11:13:17.438  1949  1949 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
,08-04 11:13:17.444  1949  1949 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-04 11:13:17.444  1949  1949 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-04 11:13:17.448   852  1378 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-04 11:13:17.470  6734  6734 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-04 11:13:17.503  1949  1949 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-04 11:13:17.504  1949  1949 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@9fe080f time:158708
08-04 11:13:17.511  1634  1634 E b       : Unable to connect to the editor to retrieve text... will retry later
08-04 11:13:17.515  1949  1949 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-04 11:13:17.524   852  1055 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{8b89db u0 com.lge.launcher2/.Launcher t254} time:158728
08-04 11:13:17.525   297   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
08-04 11:13:17.627  6910  6910 D AndroidRuntime: 
08-04 11:13:17.627  6910  6910 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-04 11:13:17.637  6910  6910 D AndroidRuntime: CheckJNI is OFF
08-04 11:13:17.877  6910  6910 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-04 11:13:17.917   852  1011 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
08-04 11:13:17.917   852  1011 I ActivityManager: Killing 6734:com.test.thalitest/u0a30 (adj 9): stop com.test.thalitest
,08-04 11:13:18.000   852  1068 W PackageSettings: Skipping PackageSetting{231764cb com.example.hello/10317} due to missing metadata
,08-04 11:13:18.029   852  2086 W ActivityManager: Spurious death for ProcessRecord{1d34c1ac 6734:com.test.thalitest/u0a30}, curProc for 6734: null
,08-04 11:13:18.040   852  1068 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
,08-04 11:13:18.087  1949  1949 I art     : Explicit concurrent mark sweep GC freed 7498(424KB) AllocSpace objects, 5(681KB) LOS objects, 39% free, 15MB/25MB, paused 1.573ms total 44.310ms
,08-04 11:13:18.125  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-04 11:13:18.129  2026  2026 I art     : Explicit concurrent mark sweep GC freed 2780(256KB) AllocSpace objects, 2(46KB) LOS objects, 40% free, 12MB/20MB, paused 1.771ms total 86.853ms
08-04 11:13:18.135  1949  1949 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-04 11:13:18.139  1949  1949 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-04 11:13:18.140  1949  1949 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-04 11:13:18.142   852  1289 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-04 11:13:18.153  1912  1912 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,08-04 11:13:18.158  1763  2545 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-04 11:13:18.164  3697  3697 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-04 11:13:18.170  3697  3697 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-04 11:13:18.170  3697  3697 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-04 11:13:18.170  3697  3697 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-04 11:13:18.170  3697  3697 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 11:13:18.170  3697  3697 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 11:13:18.170  3697  3697 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-04 11:13:18.170  3697  3697 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-04 11:13:18.170  3697  3697 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:13:18.170  3697  3697 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:13:18.171  3697  3697 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-04 11:13:18.171  3697  3697 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,08-04 11:13:18.215   852  1011 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6954 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-04 11:13:18.215   852  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1c87667b type 2 when 159282 com.android.systemui} when 159282
,08-04 11:13:18.220  3447  3447 I art     : Explicit concurrent mark sweep GC freed 16044(956KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 16MB/22MB, paused 1.102ms total 145.154ms
08-04 11:13:18.269   852  1947 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=6975 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,08-04 11:13:18.287  1372  1372 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-04 11:13:18.377  1372  1372 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-04 11:13:18.377  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-04 11:13:18.380  6975  6975 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-04 11:13:18.390   852   852 I art     : Explicit concurrent mark sweep GC freed 39474(2MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 24MB/36MB, paused 5.872ms total 272.903ms
,08-04 11:13:18.391   852  1068 I art     : WaitForGcToComplete blocked for 114.454ms for cause Explicit
08-04 11:13:18.421  1372  1512 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-04 11:13:18.421  1372  1512 D KeyguardModel: createShortcutInfo...
,08-04 11:13:18.424  6954  6954 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:13:18.425  6954  6954 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 11:13:18.426  6954  6954 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-04 11:13:18.433  1372  1512 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-04 11:13:18.433  1372  1512 D KeyguardModel: createShortcutInfo...
,08-04 11:13:18.435  1372  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 11:13:18.436  1372  1512 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-04 11:13:18.438  1372  1512 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-04 11:13:18.438  1372  1512 D KeyguardModel: createShortcutInfo...
08-04 11:13:18.440  1372  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 11:13:18.440  1372  1512 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-04 11:13:18.446  1372  1512 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-04 11:13:18.446  1372  1512 D KeyguardModel: createShortcutInfo...
,08-04 11:13:18.448  1372  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 11:13:18.448  1372  1512 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-04 11:13:18.449  1372  1512 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-04 11:13:18.449  1372  1512 D KeyguardModel: createShortcutInfo...
08-04 11:13:18.454  1372  1372 D KeyguardModel: handleShortcutListChanged...
08-04 11:13:18.458  1372  1512 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-04 11:13:18.458  1372  1512 D KeyguardModel: createShortcutInfo...
,08-04 11:13:18.461  1372  1512 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-04 11:13:18.461  1372  1512 D KeyguardModel: createShortcutInfo...
08-04 11:13:18.462  1372  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 11:13:18.463  1372  1512 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-04 11:13:18.464  1372  1512 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-04 11:13:18.464  1372  1512 D KeyguardModel: createShortcutInfo...
08-04 11:13:18.465  1372  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 11:13:18.465  1372  1512 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-04 11:13:18.467  1372  1512 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-04 11:13:18.467  1372  1512 D KeyguardModel: createShortcutInfo...
08-04 11:13:18.470  1372  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 11:13:18.471  1372  1512 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-04 11:13:18.473  1372  1512 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-04 11:13:18.473  1372  1512 D KeyguardModel: createShortcutInfo...
08-04 11:13:18.478  1372  1372 D KeyguardModel: handleShortcutListChanged...
08-04 11:13:18.518   852   852 D administrator: Handling package changes for user 0
,08-04 11:13:18.675  6954  6954 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-04 11:13:18.699   852  1068 I art     : Explicit concurrent mark sweep GC freed 12484(1889KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.961ms total 307.683ms
,08-04 11:13:18.707   852   852 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-04 11:13:18.708   852   852 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-04 11:13:18.711   852   852 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-04 11:13:18.717  6954  6954 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
08-04 11:13:18.720   852  1351 D TaskPersister: removeObsoleteFile: deleting file=255_task.xml
08-04 11:13:18.769   852  1004 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-04 11:13:18.788  1858  1858 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-04 11:13:18.788  1858  1858 D LCardEmulationManager: getDefaultRoute
,08-04 11:13:18.827  6910  6910 D AndroidRuntime: Shutting down VM
,08-04 11:13:18.864   852  1004 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-04 11:13:18.874   852  1068 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6997 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-04 11:13:18.887  1949  1949 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-04 11:13:18.942  6954  6954 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-04 11:13:18.987   852  1947 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7015 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-04 11:13:19.068  7015  7015 I AppUp4:AppBoxCP: onCreate
,08-04 11:13:19.070  7015  7015 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-04 11:13:19.078  7015  7015 I AppUp4:DB:  setFingerPrint start
08-04 11:13:19.079  7015  7015 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
08-04 11:13:19.085  7015  7015 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
,08-04 11:13:19.085  7015  7015 I AppUp4:DB:  SDK version = 21
08-04 11:13:19.085  7015  7015 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-04 11:13:19.087  7015  7015 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-04 11:13:19.190  7015  7015 E SQLiteLog: (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error

```
