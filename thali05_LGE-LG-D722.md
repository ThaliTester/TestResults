#### Test 794266509fa1f7f_thali05_LGE-LG-D722 Logs


```
--------- beginning of main
08-05 02:10:09.262  6931  6947 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-05 02:10:09.831  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 02:10:09.831  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 02:10:09.831  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
08-05 02:10:10.005  6978  6978 D AndroidRuntime: 
08-05 02:10:10.005  6978  6978 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-05 02:10:10.012  6978  6978 D AndroidRuntime: CheckJNI is OFF
08-05 02:10:10.235  6978  6978 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-05 02:10:10.258   946  1898 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-05 02:10:10.313   946  1898 D ActivityManager: setTaskToReturnTo : TaskRecord{1998f75 #255 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 02:10:10.313   946  1898 D ActivityManager: setTaskToReturnTo : TaskRecord{1998f75 #255 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 02:10:10.331   946  1898 D WindowStateEx: AppWindowTokenEx init.. 
08-05 02:10:10.341   946  1054 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-05 02:10:10.359   946  1898 D InputDispatcher: Focus left window: Window{d2c9b7f u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-05 02:10:10.362  6978  6978 D AndroidRuntime: Shutting down VM
08-05 02:10:10.369   946  1054 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-05 02:10:10.370  1949  1949 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-05 02:10:10.388   946  1054 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-05 02:10:10.388   946  1054 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-05 02:10:10.407   946  1054 D SplitWindow: check instance of lgWin Window{38e1382d u0 Starting com.test.thalitest}
08-05 02:10:10.434   946  1955 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6999 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-05 02:10:10.486  1949  1949 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-05 02:10:10.494  6998  6998 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=41 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-05 02:10:10.516  1949  1949 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-05 02:10:10.550   946  1349 I WindowStateAnimator: Starting window displayed
08-05 02:10:10.560   946  1043 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-05 02:10:10.567   946  1043 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
,08-05 02:10:10.573  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-05 02:10:10.578   946  1043 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-05 02:10:10.578   946  1043 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-05 02:10:10.578   946  1043 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-05 02:10:10.580  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-05 02:10:10.580  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-05 02:10:10.580  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-05 02:10:10.581   946  1043 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@35189eae,  pkg=WindowManager.LayoutParams
08-05 02:10:10.581   946  1043 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-05 02:10:10.621  6998  6998 I dex2oat : dex2oat took 122.480ms (threads: 4)
08-05 02:10:10.633  2029  2029 I HotwordDetector: Closing mic
08-05 02:10:10.643  2029  2591 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@24430f59
08-05 02:10:10.643  2029  2591 V AudioRecord: stop()
08-05 02:10:10.644  2029  2591 D AudioRecord: AudioRecord->stop()
08-05 02:10:10.646   282  2486 V AudioFlinger: RecordHandle::stop()
08-05 02:10:10.646   282  2486 V AudioFlinger: RecordThread::stop
08-05 02:10:10.648  6931  6947 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 02:10:10.648  6931  6947 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 02:10:10.648  6931  6947 I Adreno-EGL: Build Date: 03/02/15 Mon
08-05 02:10:10.648  6931  6947 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-05 02:10:10.648  6931  6947 I Adreno-EGL: Remote Branch: 
08-05 02:10:10.648  6931  6947 I Adreno-EGL: Local Patches: 
08-05 02:10:10.648  6931  6947 I Adreno-EGL: Reconstruct Branch: 
08-05 02:10:10.656   282  2486 V AudioFlinger: Record stopped OK
08-05 02:10:10.657   282  2486 V AudioPolicyManager: stopInput() input 17
08-05 02:10:10.657   282  2486 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
08-05 02:10:10.657   282  2486 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
08-05 02:10:10.657   282  1057 V AudioPolicyService: AudioCommandThread() waking up
08-05 02:10:10.658   282  1057 V AudioPolicyService: AudioCommandThread() processing release audio patch
08-05 02:10:10.658   282  1057 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
08-05 02:10:10.658   282  1057 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
08-05 02:10:10.658   282  1057 V AudioFlinger: ThreadBase::setParameters() routing=0
08-05 02:10:10.658   282  1057 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-05 02:10:10.661   282  2623 V AudioFlinger: processConfigEvents_l() remaining events 1
08-05 02:10:10.661   282  2623 V AudioFlinger: processConfigEvents_l() DONE thread 0xb42b8000
08-05 02:10:10.664   282  2623 D audio_hw_primary: in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
08-05 02:10:10.685  6999  6999 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-05 02:10:10.706   282  2623 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
08-05 02:10:10.706   282  2623 V audio_hw_primary: disable_audio_route: enter: usecase(7)
08-05 02:10:10.706   282  2623 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
08-05 02:10:10.706   282  2623 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-05 02:10:10.709   282  2623 V audio_hw_primary: disable_audio_route: exit
08-05 02:10:10.709   282  2623 E audio_hw_primary: disable_snd_device: enter 144
08-05 02:10:10.709   282  2623 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
08-05 02:10:10.710   282  2623 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
08-05 02:10:10.713   282  2623 V audio_hw_primary: stop_input_stream: exit: status(0)
08-05 02:10:10.713   282  2623 V audio_hw_primary: in_standby: exit:  status(0)
08-05 02:10:10.713   282  2623 V AudioFlinger: RecordThread: loop stopping
08-05 02:10:10.713   282  1057 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 02:10:10.713   282  2486 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
08-05 02:10:10.713   282  2486 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
08-05 02:10:10.714   282  2486 V AudioPolicyService: AudioCommandThread() adding update audio patch list
08-05 02:10:10.714   282  2486 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
08-05 02:10:10.714   282  1058 V AudioPolicyService: AudioCommandThread() waking up
08-05 02:10:10.714   282  1058 V AudioPolicyService: AudioCommandThread() processing update audio patch list
08-05 02:10:10.714   282  1058 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 02:10:10.716   282  2486 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
08-05 02:10:10.717   282  2486 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
08-05 02:10:10.717   282  1057 V AudioPolicyService: AudioCommandThread() waking up
08-05 02:10:10.717   282  1057 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
08-05 02:10:10.717   282  1057 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 282
08-05 02:10:10.717   282  1057 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
08-05 02:10:10.717   282  1057 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-05 02:10:10.718   282  2623 V AudioFlinger: RecordThread: loop starting
08-05 02:10:10.718   282  2623 V AudioFlinger: processConfigEvents_l() remaining events 1
08-05 02:10:10.718   282  2623 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
08-05 02:10:10.718   282  2623 V audio_hw_primary: in_set_parameters: exit: status(0)
08-05 02:10:10.718   282  2623 V AudioFlinger: processConfigEvents_l() DONE thread 0xb42b8000
08-05 02:10:10.718   282  2623 V AudioFlinger: RecordThread: loop stopping
08-05 02:10:10.719   282  1057 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 02:10:10.724  2029  2591 V AudioRecord: stop()
08-05 02:10:10.724  2029  2591 V AudioRecord: stop()
08-05 02:10:10.724  2029  2591 V AudioRecord: stop()
08-05 02:10:10.732   282  1321 V AudioFlinger: RecordHandle::stop()
08-05 02:10:10.732   282  1321 V AudioFlinger: RecordThread::stop
08-05 02:10:10.732   282  1321 V AudioPolicyManager: releaseInput() 17
08-05 02:10:10.732   282  1321 V AudioPolicyManager: closeInput(17)
08-05 02:10:10.732   282  1321 V AudioFlinger: closeInput() 17
08-05 02:10:10.732   282  1321 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-05 02:10:10.732   946  1885 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-05 02:10:10.732   282  1321 V AudioFlinger: ThreadBase::exit
08-05 02:10:10.732  1802  2677 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-05 02:10:10.732  2029  2052 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-05 02:10:10.732  2078  3488 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-05 02:10:10.733  3160  3175 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-05 02:10:10.733  1372  1403 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-05 02:10:10.733   282   282 V AudioFlinger: releasing 16 from 2029 for -1
08-05 02:10:10.733   282   282 V AudioFlinger:  decremented refcount to 0
08-05 02:10:10.733   282   282 V AudioFlinger: purging stale effects
08-05 02:10:10.733   282  2623 V AudioFlinger: RecordThread: loop starting
08-05 02:10:10.733   282  2623 V AudioFlinger: RecordThread 0xb42b8000 exiting
08-05 02:10:10.734   282  1321 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb4036520)
08-05 02:10:10.734   282  1321 D audio_hw_primary: in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
08-05 02:10:10.734   282  1321 V audio_hw_primary: in_standby: exit:  status(0)
08-05 02:10:10.735   282  1321 V AudioPolicyService: AudioCommandThread() adding update audio port list
08-05 02:10:10.735   282  1321 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
08-05 02:10:10.735   282  1058 V AudioPolicyService: AudioCommandThread() waking up
08-05 02:10:10.735   282  1058 V AudioPolicyService: AudioCommandThread() processing update audio port list
08-05 02:10:10.735   282  1058 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 02:10:10.736   282  1321 V AudioPolicyManager: releaseInput() exit
08-05 02:10:10.736   282  1321 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
08-05 02:10:10.736   282  1321 V AudioFlinger: removeClient_l() pid 2029, calling pid 282
08-05 02:10:10.745  2029  2606 I HotwordRecognitionRnr: Stopping hotword detection.
08-05 02:10:10.751  2029  2615 I HotwordRecognitionRnr: Hotword detection finished
08-05 02:10:10.831  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 02:10:10.831  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 02:10:10.831  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-05 02:10:10.844   946   982 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-05 02:10:10.844   946   982 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-05 02:10:10.844   946   982 D sensors_hal_Time: tsOffsetIs: Apps: 133048418598; DSPS: 4450907; Offset : -2790104071
08-05 02:10:10.844  6999  6999 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-05 02:10:10.917  6999  6999 I LibraryLoader: Time to load native libraries: 12 ms (timestamps 3109-3121)
08-05 02:10:10.918  6999  6999 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 02:10:10.928  6931  6947 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 02:10:10.928  6931  6947 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 02:10:10.928  6931  6947 I Adreno-EGL: Build Date: 03/02/15 Mon
08-05 02:10:10.928  6931  6947 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-05 02:10:10.928  6931  6947 I Adreno-EGL: Remote Branch: 
08-05 02:10:10.928  6931  6947 I Adreno-EGL: Local Patches: 
08-05 02:10:10.928  6931  6947 I Adreno-EGL: Reconstruct Branch: 
08-05 02:10:10.973  6999  6999 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c38cb87}
08-05 02:10:10.974  6999  6999 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 02:10:10.979  6999  6999 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 02:10:10.995  6999  6999 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-05 02:10:10.998  6999  6999 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 02:10:10.999  6931  6947 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 02:10:10.999  6931  6947 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 02:10:10.999  6931  6947 I Adreno-EGL: Build Date: 03/02/15 Mon
08-05 02:10:10.999  6931  6947 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-05 02:10:10.999  6931  6947 I Adreno-EGL: Remote Branch: 
08-05 02:10:10.999  6931  6947 I Adreno-EGL: Local Patches: 
08-05 02:10:10.999  6931  6947 I Adreno-EGL: Reconstruct Branch: 
08-05 02:10:11.003  6999  6999 E SysUtils: ApplicationContext is null in ApplicationStatus
08-05 02:10:11.084  6999  6999 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-05 02:10:11.093  6999  6999 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-05 02:10:11.093  6999  6999 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-05 02:10:11.093  6999  6999 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 02:10:11.093  6999  6999 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 02:10:11.093  6999  6999 I Adreno-EGL: Build Date: 03/02/15 Mon
08-05 02:10:11.093  6999  6999 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-05 02:10:11.093  6999  6999 I Adreno-EGL: Remote Branch: 
08-05 02:10:11.093  6999  6999 I Adreno-EGL: Local Patches: 
08-05 02:10:11.093  6999  6999 I Adreno-EGL: Reconstruct Branch: 
08-05 02:10:11.110   295   341 I ThermalEngine: Sensor:pa_therm0:33000 mC
08-05 02:10:11.123  1772  6929 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-05 02:10:11.123  1772  6929 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-05 02:10:11.123  1772  6929 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-05 02:10:11.124  1772  6929 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-05 02:10:11.124   277  1047 E BandwidthController: [LG DATA] No such appUid: 10006
08-05 02:10:11.124   277  1047 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-05 02:10:11.124   277  7039 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-05 02:10:11.124   277  7039 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-05 02:10:11.125   277  7039 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-05 02:10:11.125   277  7039 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-05 02:10:11.127   277  7039 D libc-netbsd: res_queryN name = xxxxx succeed
08-05 02:10:11.127  1772  6929 I System.out: propertyValue:false
08-05 02:10:11.161   282  2486 V AudioPolicyService: registerClient() client 0xb551cde0, uid 10030
08-05 02:10:11.176   946  1053 D BluetoothManagerService: Message: 20
08-05 02:10:11.178   946  1053 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18d45712:true
08-05 02:10:11.180  2078  2094 D BluetoothAdapterService(721733341): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a9a099b
08-05 02:10:11.221  1772  6929 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-05 02:10:11.222  1772  6929 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-05 02:10:11.308  6999  6999 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 02:10:11.321  6999  6999 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-05 02:10:11.326  6999  6999 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-05 02:10:11.330  6999  6999 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-05 02:10:11.330  6999  6999 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-05 02:10:11.343  6999  6999 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-05 02:10:11.351  6999  6999 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 02:10:11.351  6999  6999 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 02:10:11.407  6999  6999 I Activity: Activity.onPostResume() called 
08-05 02:10:11.419  6999  7058 D OpenGLRenderer: Render dirty regions requested: true
08-05 02:10:11.419  6999  7058 I OpenGLRenderer: Initialized EGL, version 1.4
08-05 02:10:11.429  6999  7058 D OpenGLRenderer: Enabling debug mode 0
08-05 02:10:11.469  6999  6999 D Atlas   : Validating map...
08-05 02:10:11.478   946  2676 D SplitWindow: check instance of lgWin Window{295ca8c2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 02:10:11.488  6440  6597 I art     : Explicit concurrent mark sweep GC freed 1842(69KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 2.710ms total 36.776ms
08-05 02:10:11.489  6999  7045 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-05 02:10:11.512  1772  2363 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
08-05 02:10:11.516  1772  2363 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
08-05 02:10:11.520   946  1856 D InputDispatcher: Focus entered window: Window{295ca8c2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 02:10:11.530  1772  2363 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-05 02:10:09.120+0200, stopTime=2016-08-05 02:10:11.525+0200, duration=2405ms
08-05 02:10:11.538  1772  7060 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-05 02:10:11.538  1772  7060 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-05 02:10:11.539  1772  7060 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-05 02:10:11.539  1772  7060 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-05 02:10:11.539   277  1047 E BandwidthController: [LG DATA] No such appUid: 10006
08-05 02:10:11.539   277  1047 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-05 02:10:11.539   277  7065 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-05 02:10:11.539   277  7065 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-05 02:10:11.540   277  7065 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-05 02:10:11.540   277  7065 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-05 02:10:11.540   277  7065 D libc-netbsd: res_queryN name = xxxxx succeed
08-05 02:10:11.541  1772  7060 I System.out: propertyValue:false
08-05 02:10:11.558   282  2486 I WVCdm   : CdmEngine::CloseSession
08-05 02:10:11.566   282  2486 I WVCdm   : L3 Terminate.
08-05 02:10:11.589   946  1928 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-05 02:10:11.609   946  1054 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s210ms
08-05 02:10:11.610   946  1054 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2195eb0a u0 com.test.thalitest/.MainActivity t255} time:133814
08-05 02:10:11.615  6999  6999 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@ec48549 time:133819
08-05 02:10:11.669  6999  6999 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6999
08-05 02:10:11.832  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,08-05 02:10:11.832  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 02:10:11.832  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
08-05 02:10:12.030  1772  2363 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-05 02:10:12.276  1772  7087 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-05 02:10:12.277  1772  7077 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-05 02:10:12.297  1772  7087 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-05 02:10:12.298  1772  7077 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-05 02:10:12.323  1772  7087 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-05 02:10:12.324  1772  7077 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-05 02:10:12.324  1772  7077 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
08-05 02:10:12.346  1772  7077 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-05 02:10:12.391   946  1927 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-05 02:10:12.465  6999  6999 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-05 02:10:12.496  1772  7077 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-05 02:10:12.496  1772  7077 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-05 02:10:12.496  1772  7077 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-05 02:10:12.496  1772  7077 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-05 02:10:12.496   277  1047 E BandwidthController: [LG DATA] No such appUid: 10006
08-05 02:10:12.496   277  1047 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-05 02:10:12.497   277  7091 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-05 02:10:12.497   277  7091 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,08-05 02:10:12.497   277  7091 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,08-05 02:10:12.497   277  7091 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-05 02:10:12.497   277  7091 D libc-netbsd: res_queryN name = xxxxx succeed
08-05 02:10:12.498  1772  7077 I System.out: propertyValue:false
08-05 02:10:12.594  6999  7070 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426121984
,08-05 02:10:12.602  6999  7070 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 02:10:12.602  6999  7070 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 02:10:12.602  6999  7070 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 02:10:12.602  6999  7070 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 02:10:12.602  6999  7070 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-05 02:10:12.602  6999  7070 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d41b2 added. We now have 1 listener(s)
08-05 02:10:12.606   946  1349 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 02:10:12.613  6999  7070 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,08-05 02:10:12.615  6999  7070 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-05 02:10:12.616  6999  7070 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 02:10:12.616  6999  7070 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 02:10:12.622  6999  7070 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 02:10:12.622  6999  7070 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 02:10:12.622  6999  7070 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 02:10:12.622  6999  7070 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-05 02:10:12.622  6999  7070 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 02:10:12.622  6999  7070 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 02:10:12.622  6999  7070 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 02:10:12.622  6999  7070 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 02:10:12.622  6999  7070 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 02:10:12.622  6999  7070 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 02:10:12.622  6999  7070 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 02:10:12.622  6999  7070 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 02:10:12.622  6999  7070 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 02:10:12.622  6999  7070 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-05 02:10:12.622  6999  7070 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cbc52b9 added. We now have 1 listener(s)
08-05 02:10:12.622  6999  7070 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 02:10:12.636  6999  7070 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 02:10:12.637  6999  7070 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-05 02:10:12.638  6999  7070 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-05 02:10:12.638  6999  7070 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-05 02:10:12.638  6999  7070 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-05 02:10:12.643  6999  7070 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 02:10:12.643   946  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 02:10:12.644  6999  7070 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-05 02:10:12.661  2078  2095 D BluetoothAdapterService(721733341): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a9a099b
,08-05 02:10:12.661  6999  7070 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 02:10:12.662  6999  7070 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 02:10:12.662  6999  7070 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 02:10:12.662  6999  7070 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 02:10:12.662  6999  7070 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 02:10:12.662  6999  7070 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 02:10:12.662  6999  7070 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 02:10:12.662  6999  7070 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 02:10:12.662  6999  7070 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 02:10:12.662  6999  7070 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-05 02:10:12.662  6999  7070 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 02:10:12.664  6999  6999 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 02:10:12.665  6999  6999 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 02:10:12.665  6999  7070 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 02:10:12.695  6999  6999 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-05 02:10:12.812   946  2188 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-05 02:10:12.851  6999  7015 I art     : CheckpointMarkThreadRoots callback created = 0x996a14b0
,08-05 02:10:12.881  6999  7015 I art     : CheckpointMarkThreadRoots callback created = 0x996a1480
,08-05 02:10:13.181   946  1928 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-05 02:10:13.448   946   963 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-05 02:10:13.670  6999  7094 W jxcore-log: Initializing JXcore engine
08-05 02:10:13.670  6999  7094 W jxcore-log: JXcore engine is ready
,08-05 02:10:13.745   946   965 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-05 02:10:13.768  7094  7094 W Thread-835: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7929]" dev="sockfs" ino=7929 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-05 02:10:13.768  7094  7094 W Thread-835: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-05 02:10:13.768  7094  7094 W Thread-835: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5827]" dev="sockfs" ino=5827 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-05 02:10:13.768  7094  7094 W Thread-835: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-05 02:10:13.768  7094  7094 W Thread-835: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-05 02:10:13.768  7094  7094 W Thread-835: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[30905]" dev="sockfs" ino=30905 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-05 02:10:13.795  6999  7094 W jxcore-log: Starting JXcore engine
,08-05 02:10:13.882  1772  2363 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-05 02:10:13.933  6999  7094 W jxcore-log: Platform android
08-05 02:10:13.933  6999  7094 W jxcore-log: 
,08-05 02:10:13.933  6999  7094 W jxcore-log: Process ARCH arm
08-05 02:10:13.933  6999  7094 W jxcore-log: 
08-05 02:10:13.994   946  1898 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-05 02:10:14.222   946  1285 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2abff01f type 2 when 136418 android} when 136418
,08-05 02:10:14.248  6999  7094 I jxcore-log: JXcore Cordova bridge is ready!
08-05 02:10:14.248  6999  7094 I jxcore-log: 
,08-05 02:10:14.248  6999  7094 W jxcore-log: JXcore engine is started
08-05 02:10:14.252  6999  7070 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-05 02:10:14.255  6999  6999 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-05 02:10:15.275   946   963 I ActivityManager: Process com.google.android.apps.docs (pid 6471) has died
,08-05 02:10:15.672   946  1285 V AlarmManager: RTC_WAKEUP set : Alarm{4a63935 type 0 when 1470355815665 com.google.android.googlequicksearchbox} when 1470355815665
,08-05 02:10:15.838  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 02:10:15.839  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 02:10:15.839  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-05 02:10:16.114   295   341 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-05 02:10:16.841  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 02:10:16.841  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 02:10:16.841  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-05 02:10:18.035   946  1656 I ActivityManager: Process com.google.android.videos (pid 6689) has died
,08-05 02:10:18.846  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 02:10:18.846  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 02:10:18.846  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-05 02:10:19.848  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 02:10:19.848  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 02:10:19.848  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-05 02:10:20.928  1772  3749 I art     : Explicit concurrent mark sweep GC freed 39433(2MB) AllocSpace objects, 24(382KB) LOS objects, 39% free, 14MB/24MB, paused 1.422ms total 90.575ms
,08-05 02:10:21.119   295   341 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-05 02:10:21.850  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 02:10:21.850  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 02:10:21.850  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-05 02:10:23.854  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 02:10:23.854  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 02:10:23.854  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-05 02:10:24.183   946  1059 I PowerManagerService: ALS enabled for SRE
08-05 02:10:24.184   946  1059 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26388 ms ago)
,08-05 02:10:24.223   946  1350 D qdlights: set_light_backlight: 252
,08-05 02:10:24.237   946  1350 D qdlights: set_light_backlight: 248
,08-05 02:10:24.254   946  1350 D qdlights: set_light_backlight: 245
08-05 02:10:24.270   946  1350 D qdlights: set_light_backlight: 242
,08-05 02:10:24.287   946  1350 D qdlights: set_light_backlight: 238
,08-05 02:10:24.304   946  1350 D qdlights: set_light_backlight: 235
,08-05 02:10:24.320   946  1350 D qdlights: set_light_backlight: 232
,08-05 02:10:24.337   946  1350 D qdlights: set_light_backlight: 228
,08-05 02:10:24.354   946  1350 D qdlights: set_light_backlight: 225
,08-05 02:10:24.370   946  1350 D qdlights: set_light_backlight: 222
,08-05 02:10:24.387   946  1350 D qdlights: set_light_backlight: 218
,08-05 02:10:24.404   946  1350 D qdlights: set_light_backlight: 215
,08-05 02:10:24.420   946  1350 D qdlights: set_light_backlight: 212
,08-05 02:10:24.437   946  1350 D qdlights: set_light_backlight: 208
,08-05 02:10:24.454   946  1350 D qdlights: set_light_backlight: 205
,08-05 02:10:24.470   946  1350 D qdlights: set_light_backlight: 202
,08-05 02:10:24.487   946  1350 D qdlights: set_light_backlight: 198
,08-05 02:10:24.504   946  1350 D qdlights: set_light_backlight: 195
,08-05 02:10:24.520   946  1350 D qdlights: set_light_backlight: 192
,08-05 02:10:24.537   946  1350 D qdlights: set_light_backlight: 188
,08-05 02:10:24.554   946  1350 D qdlights: set_light_backlight: 185
,08-05 02:10:24.570   946  1350 D qdlights: set_light_backlight: 182
,08-05 02:10:24.587   946  1350 D qdlights: set_light_backlight: 178
,08-05 02:10:24.604   946  1350 D qdlights: set_light_backlight: 175
,08-05 02:10:24.620   946  1350 D qdlights: set_light_backlight: 172
,08-05 02:10:24.637   946  1350 D qdlights: set_light_backlight: 168
,08-05 02:10:24.654   946  1350 D qdlights: set_light_backlight: 165
,08-05 02:10:24.670   946  1350 D qdlights: set_light_backlight: 162
,08-05 02:10:24.687   946  1350 D qdlights: set_light_backlight: 158
,08-05 02:10:24.704   946  1350 D qdlights: set_light_backlight: 155
,08-05 02:10:24.720   946  1350 D qdlights: set_light_backlight: 152
,08-05 02:10:24.737   946  1350 D qdlights: set_light_backlight: 148
,08-05 02:10:24.754   946  1350 D qdlights: set_light_backlight: 145
,08-05 02:10:24.770   946  1350 D qdlights: set_light_backlight: 142
,08-05 02:10:24.787   946  1350 D qdlights: set_light_backlight: 138
,08-05 02:10:24.804   946  1350 D qdlights: set_light_backlight: 135
,08-05 02:10:24.820   946  1350 D qdlights: set_light_backlight: 132
,08-05 02:10:24.837   946  1350 D qdlights: set_light_backlight: 128
,08-05 02:10:24.854   946  1350 D qdlights: set_light_backlight: 125
,08-05 02:10:24.858  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 02:10:24.858  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 02:10:24.858  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-05 02:10:24.870   946  1350 D qdlights: set_light_backlight: 122
,08-05 02:10:24.889   946  1350 D qdlights: set_light_backlight: 118
,08-05 02:10:24.903   946  1350 D qdlights: set_light_backlight: 115
,08-05 02:10:24.920   946  1350 D qdlights: set_light_backlight: 112
,08-05 02:10:24.937   946  1350 D qdlights: set_light_backlight: 108
,08-05 02:10:24.954   946  1350 D qdlights: set_light_backlight: 105
,08-05 02:10:24.970   946  1350 D qdlights: set_light_backlight: 102
,08-05 02:10:24.987   946  1350 D qdlights: set_light_backlight: 98
,08-05 02:10:25.004   946  1350 D qdlights: set_light_backlight: 95
,08-05 02:10:25.020   946  1350 D qdlights: set_light_backlight: 92
,08-05 02:10:25.037   946  1350 D qdlights: set_light_backlight: 88
,08-05 02:10:25.054   946  1350 D qdlights: set_light_backlight: 85
,08-05 02:10:25.070   946  1350 D qdlights: set_light_backlight: 82
,08-05 02:10:25.087   946  1350 D qdlights: set_light_backlight: 78
,08-05 02:10:25.104   946  1350 D qdlights: set_light_backlight: 75
,08-05 02:10:25.120   946  1350 D qdlights: set_light_backlight: 72
,08-05 02:10:25.137   946  1350 D qdlights: set_light_backlight: 68
,08-05 02:10:25.154   946  1350 D qdlights: set_light_backlight: 65
,08-05 02:10:25.170   946  1350 D qdlights: set_light_backlight: 62
,08-05 02:10:25.187   946  1350 D qdlights: set_light_backlight: 58
,08-05 02:10:25.204   946  1350 D qdlights: set_light_backlight: 55
,08-05 02:10:25.220   946  1350 D qdlights: set_light_backlight: 52
,08-05 02:10:25.237   946  1350 D qdlights: set_light_backlight: 48
,08-05 02:10:25.254   946  1350 D qdlights: set_light_backlight: 45
,08-05 02:10:25.270   946  1350 D qdlights: set_light_backlight: 42
,08-05 02:10:25.287   946  1350 D qdlights: set_light_backlight: 38
,08-05 02:10:25.304   946  1350 D qdlights: set_light_backlight: 35
,08-05 02:10:25.320   946  1350 D qdlights: set_light_backlight: 32
,08-05 02:10:25.337   946  1350 D qdlights: set_light_backlight: 28
,08-05 02:10:25.354   946  1350 D qdlights: set_light_backlight: 25
,08-05 02:10:25.370   946  1350 D qdlights: set_light_backlight: 22
,08-05 02:10:25.387   946  1350 D qdlights: set_light_backlight: 18
,08-05 02:10:25.404   946  1350 D qdlights: set_light_backlight: 15
,08-05 02:10:25.420   946  1350 D qdlights: set_light_backlight: 12
,08-05 02:10:25.437   946  1350 D qdlights: set_light_backlight: 10
,08-05 02:10:25.860  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 02:10:25.860  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 02:10:25.860  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-05 02:10:26.124   295   341 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-05 02:10:27.863  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 02:10:27.863  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-05 02:10:27.863  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-05 02:10:28.865  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 02:10:28.865  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 02:10:28.865  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-05 02:10:30.845   946   982 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-05 02:10:30.845   946   982 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-05 02:10:30.845   946   982 D sensors_hal_Time: tsOffsetIs: Apps: 153049068330; DSPS: 5106287; Offset : -2790064717
,08-05 02:10:30.869  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 02:10:30.869  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 02:10:30.869  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-05 02:10:31.129   295   341 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-05 02:10:31.185   946  1059 I PowerManagerService: ALS enabled for SRE
08-05 02:10:31.186   946  1059 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33390 ms ago)
,08-05 02:10:31.189   946  1059 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
08-05 02:10:31.199   946  1059 I PowerManagerService: ALS enabled for SRE
,08-05 02:10:31.201   946  1059 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33405 ms ago)
08-05 02:10:31.207   946  1059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
08-05 02:10:31.213   946  1059 I PowerManagerService: Sleeping (uid 1000)...
08-05 02:10:31.213   946  1059 D LPWGController: [updateScreenState] screen on = false
,08-05 02:10:31.217   946  1059 D LPWGController: disable proximity sensor
08-05 02:10:31.217   946  1059 D LPWGController: enable proximity sensor
08-05 02:10:31.228   946  1059 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@390e33b1] by com.android.server.power.ProximitySensorListener.enable():120
,08-05 02:10:31.234   946  1059 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
08-05 02:10:31.234   946  1059 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
08-05 02:10:31.234   946  1059 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
08-05 02:10:31.234   946  1059 I sensors_hal_Ctx: activate: handle is 48, enable
08-05 02:10:31.234   946  1059 V sensors_hal_Ctx: activate sensors is 1400000000000
08-05 02:10:31.234   946  1059 D sensors_hal_Thresh: enable: handle=48
08-05 02:10:31.234   946  1059 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
08-05 02:10:31.234   946  1059 D sensors_hal_Util: waitForResponse: timeout=1000
08-05 02:10:31.239   946   983 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
08-05 02:10:31.239   946   983 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
08-05 02:10:31.239   946  1059 D sensors_hal_Thresh: enable: Received response: 0
08-05 02:10:31.240   946  1059 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33444 ms ago)
08-05 02:10:31.256   946  1059 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 02:10:31.256   946  1059 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 02:10:31.256   946  1059 I Adreno-EGL: Build Date: 03/02/15 Mon
08-05 02:10:31.256   946  1059 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-05 02:10:31.256   946  1059 I Adreno-EGL: Remote Branch: 
08-05 02:10:31.256   946  1059 I Adreno-EGL: Local Patches: 
08-05 02:10:31.256   946  1059 I Adreno-EGL: Reconstruct Branch: 
,08-05 02:10:31.284   245  2373 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1443 us)
,08-05 02:10:31.467   440   968 I Sensors : sns_pwr.c(273):acquiring wakelock
,08-05 02:10:31.469   946   983 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
08-05 02:10:31.471   946   983 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
08-05 02:10:31.471   946   983 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
08-05 02:10:31.471   946   983 D sensors_hal_Thresh: processInd: handle 48, count=1
08-05 02:10:31.471   946   983 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
08-05 02:10:31.471   946   983 I sensors_hal_Thresh: processInd : proximity state changed - NEAR
08-05 02:10:31.471   946  1020 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:0.000000 y:-0.000007 z:0.000000
08-05 02:10:31.471   946  1020 D sensors_hal_Ctx: poll: count: 256
08-05 02:10:31.472   946  1020 I sensors_hal_Ctx: poll: released wakelock sensor_ind
08-05 02:10:31.472   946  1020 D sensors_hal_Util: waitForResponse: timeout=0
08-05 02:10:31.473   946  1059 D LPWGController: proximity onSensorChanged : proximity = 0, mSensorCovered=false, isFar=false
08-05 02:10:31.474   946  1059 I LPWGController: current mode = 0  value = 1 0
08-05 02:10:31.474   946  1059 I LPWGController: [setLPWGmode2] current mode = 0  value = 9 0 1 0 0
08-05 02:10:31.573   946  1059 I LPWGController: [setLPWGmode2] current mode = 0  value = 9 0 0 0 0
,08-05 02:10:31.810   946  1350 D qdlights: set_light_backlight: 0
,08-05 02:10:31.827   946  1059 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,08-05 02:10:31.832   946  1059 I sensors_hal_Ctx: activate: handle is 46, disable
08-05 02:10:31.832   946  1059 V sensors_hal_Ctx: activate sensors is 1000000000000
08-05 02:10:31.832   946  1059 D sensors_hal_LP2: enable: handle=46
08-05 02:10:31.832   946  1059 D sensors_hal_LP2: enable: Disabling sensor handle=46
08-05 02:10:31.832   946  1059 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
08-05 02:10:31.834   245   245 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
08-05 02:10:31.834   245   245 D qdhwcomposer: hwc_blank: Blanking display: 0
08-05 02:10:31.838   946  1054 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
08-05 02:10:31.839   946   946 V ActivityManager: Display changed displayId=0
,08-05 02:10:31.872  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-05 02:10:31.872  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-05 02:10:31.872  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-05 02:10:31.897  1802  1802 D DSDPConnection: Display #0 changed.
,08-05 02:10:31.926   946  1010 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
08-05 02:10:31.926   946  1010 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
08-05 02:10:32.072   245   245 D qdhwcomposer: hwc_blank: Done blanking display: 0
,08-05 02:10:32.074   245   564 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
08-05 02:10:32.074   946  1350 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
08-05 02:10:32.075   946  1350 I QCOM PowerHAL: Got set_interactive hint
08-05 02:10:32.089  6999  6999 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-05 02:10:32.094  6999  6999 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-05 02:10:32.098  1372  1996 D KeyguardViewMediator: onScreenTurnedOff(3)
08-05 02:10:32.103  1332  1347 D SmartCoverViewMediator: onScreenTurnedOff(3)
08-05 02:10:32.113  1332  1347 D SmartCoverViewMediator: notifyScreenOffLocked
,08-05 02:10:32.116  1332  1332 D SmartCoverViewMediator: handleNotifyScreenOFF
08-05 02:10:32.116  1372  1996 D KeyguardViewMediator: notifyScreenOffLocked
08-05 02:10:32.119  6999  6999 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@21bef495 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3f7fca0d, 16908290=android.view.AbsSavedState$1@3f7fca0d}, android:focusedViewId=100}]}]
08-05 02:10:32.119  6999  6999 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-05 02:10:32.121  6999  6999 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-05 02:10:32.121  6999  6999 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-05 02:10:32.140  1372  1996 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
08-05 02:10:32.140  1372  1372 D KeyguardViewMediator: handleNotifyScreenOff
,08-05 02:10:32.164  1372  1372 D ScreenTurnOffBySensor: unregisterProximitySensor
,08-05 02:10:32.166   946   946 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
08-05 02:10:32.178   282  1295 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 946
,08-05 02:10:32.179   282  1295 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-05 02:10:32.179   282  1295 V voice   : voice_set_parameters: enter: screen_state=on
08-05 02:10:32.181   282  1295 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
08-05 02:10:32.181   282  1295 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-05 02:10:32.181   282  1295 V voice   : voice_set_parameters: exit with code(0)
08-05 02:10:32.181   282  1295 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
08-05 02:10:32.181   282  1295 V msm8974_platform: platform_set_parameters: enter: screen_state=on
08-05 02:10:32.182   282  1295 V msm8974_platform: platform_set_parameters: exit with code(0)
08-05 02:10:32.182   282  1295 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-05 02:10:32.182   282  1295 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
08-05 02:10:32.182   282  1295 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-05 02:10:32.182   282  1295 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-05 02:10:32.182  1372  1372 D StatusBarWindowView: onScreenTurnedOff why = 3
08-05 02:10:32.185   946  1308 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
08-05 02:10:32.189  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 02:10:32.191  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
,08-05 02:10:32.715   946  1016 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,08-05 02:10:32.756   946  1656 D SplitWindow: check instance of lgWin Window{2971b004 u0 SearchPanel}
,08-05 02:10:32.764  1910  1910 I QCNEJ   : |CORE| sendScreenState: state:true
08-05 02:10:32.770  1874  2044 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
08-05 02:10:32.772  1874  2044 D LEDService: stopPatternFlashing()
,08-05 02:10:32.774  1874  2044 D qdlights: set_light_notifications: 0,0,0,0,3
08-05 02:10:32.777  1874  2044 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-05 02:10:32.777  1874  2044 D qdlights: set_light_notifications: 0,0,0,0,3
08-05 02:10:32.779  1874  2044 I LEDService: updateLightsLocked : turn off led
08-05 02:10:32.779  1874  2044 D qdlights: set_light_notifications: 0,0,0,0,3
08-05 02:10:32.779   946  1993 D InputDispatcher: Window went away: Window{26e16191 u0 SearchPanel}
08-05 02:10:32.781  1372  1372 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
08-05 02:10:32.784  1874  2044 D LEDHandler: RESTART MSG
,08-05 02:10:32.800  1372  1372 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,08-05 02:10:32.812  1874  1874 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,08-05 02:10:32.814  1874  1874 D Cliptray Service: lockStatus = 0
08-05 02:10:32.817  1857  1857 D LNfcService: action : android.intent.action.SCREEN_ON
08-05 02:10:32.824  1857  7161 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
08-05 02:10:32.824  1857  7161 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
08-05 02:10:32.824  1857  7161 D LNfcService: isRequireNfcCRouting() return true
08-05 02:10:32.824  1857  7161 D LNfcService: isHCERoutingtoHost() return : true
08-05 02:10:32.825  1857  7161 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-05 02:10:32.825  1857  7161 D NfcService: mEnableLPD: true
08-05 02:10:32.825  1857  7161 D NfcService: mEnableReader: false
08-05 02:10:32.825  1857  7161 D NfcService: mEnableHostRouting: true
08-05 02:10:32.825  1857  7161 D NfcService: newParams.techmask= mTechMask: default
08-05 02:10:32.825  1857  7161 D NfcService: mEnableLPD: true
08-05 02:10:32.825  1857  7161 D NfcService: mEnableReader: false
08-05 02:10:32.825  1857  7161 D NfcService: mEnableHostRouting: true
08-05 02:10:32.825  1857  7161 D NfcService: screenState= 3
08-05 02:10:32.825  1857  7161 D NfcService: Discovery configuration equal, not updating.
,08-05 02:10:32.829   946   946 D Ulp_jni : JNI:system_update. Event-0
,08-05 02:10:32.879  1802  1802 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,08-05 02:10:32.892   946   946 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 02:10:32.892   946   946 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 02:10:32.893   946   946 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
,08-05 02:10:32.898  2862  2862 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:10:32
08-05 02:10:32.901  2862  2862 D WeatherService: 2 : ACTION screen on
,08-05 02:10:32.903  2862  2862 D WeatherService: 2 : shouldTimeTickRegistered : false
08-05 02:10:32.914  2862  2862 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 02:10:32.914  2862  2862 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:10:32
,08-05 02:10:32.925  4128  4128 D AppCleanupService: android.intent.action.SCREEN_ON
,08-05 02:10:32.954   282  2486 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 946
,08-05 02:10:32.955   282  2486 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-05 02:10:32.955   282  2486 V voice   : voice_set_parameters: enter: screen_state=off
08-05 02:10:32.955   282  2486 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
08-05 02:10:32.955   282  2486 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-05 02:10:32.955   282  2486 V voice   : voice_set_parameters: exit with code(0)
08-05 02:10:32.955   282  2486 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
08-05 02:10:32.955   282  2486 V msm8974_platform: platform_set_parameters: enter: screen_state=off
08-05 02:10:32.955   282  2486 V msm8974_platform: platform_set_parameters: exit with code(0)
08-05 02:10:32.955   282  2486 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-05 02:10:32.955   282  2486 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-05 02:10:32.955   282  2486 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-05 02:10:32.957   946  1313 D WifiController: CMD_SCREEN_OFF 
08-05 02:10:32.957   946  1313 D WifiController: shouldWifiStayAwake TRUE
08-05 02:10:32.962  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
08-05 02:10:32.963   946  1016 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
08-05 02:10:32.968   440   454 I Sensors : sns_pwr.c(301):releasing wakelock
,08-05 02:10:32.984  1910  1910 I QCNEJ   : |CORE| sendScreenState: state:false
08-05 02:10:32.985  1874  2044 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
08-05 02:10:32.985  1874  2044 D LEDService: stopPatternFlashing()
08-05 02:10:32.986  1874  2044 D qdlights: set_light_notifications: 0,0,0,0,3
08-05 02:10:32.986  1874  1874 D VolumeVibrator: clear
08-05 02:10:32.987  1874  2044 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-05 02:10:32.987  1874  2044 D qdlights: set_light_notifications: 0,0,0,0,3
,08-05 02:10:32.989  1874  1874 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
08-05 02:10:32.990  1874  2044 I LEDService: updateLightsLocked : turn on led
08-05 02:10:32.990  1857  1857 D LNfcService: action : android.intent.action.SCREEN_OFF
08-05 02:10:32.990  1874  2044 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
08-05 02:10:32.991  1874  2044 E LEDService: Can't handle this request of patternId:0
08-05 02:10:32.991  1874  2044 D LEDHandler: RESTART MSG
,08-05 02:10:33.000  1857  2173 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
08-05 02:10:33.013  1949  1949 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,08-05 02:10:33.030  1802  1802 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,08-05 02:10:33.034   946   946 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 02:10:33.034   946   946 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 02:10:33.034   946   946 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
08-05 02:10:33.036  2862  2862 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:10:33
08-05 02:10:33.036  2862  2862 D WeatherService: 2 : ACTION screen off
08-05 02:10:33.038  2862  2862 D WeatherService: 2 : TimeTick Receiver Unregister
08-05 02:10:33.039  2862  2862 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:10:33
08-05 02:10:33.041  4128  4128 D AppCleanupService: android.intent.action.SCREEN_OFF
08-05 02:10:33.044  4128  7169 D AppCleanupService: AppUsageStatsSaveTask
,08-05 02:10:33.088  1857  2666 E NxpNfcJni: getReconnectState = 0x0
,08-05 02:10:33.092  1857  2173 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-05 02:10:33.092  1857  2173 D LCardEmulationManager: getDefaultRoute
08-05 02:10:33.092  1857  2173 D LNfcService: isRequireNfcCRouting() return true
08-05 02:10:33.093  1857  2173 D LNfcService: isHCERoutingtoHost() return : true
08-05 02:10:33.093  1857  2173 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-05 02:10:33.093  1857  2173 D NfcService: mEnableLPD: true
08-05 02:10:33.093  1857  2173 D NfcService: mEnableReader: false
08-05 02:10:33.093  1857  2173 D NfcService: mEnableHostRouting: true
08-05 02:10:33.093  1857  2173 D NfcService: newParams.techmask= mTechMask: 0
08-05 02:10:33.093  1857  2173 D NfcService: mEnableLPD: true
08-05 02:10:33.093  1857  2173 D NfcService: mEnableReader: false
08-05 02:10:33.093  1857  2173 D NfcService: mEnableHostRouting: true
08-05 02:10:33.093  1857  2173 D NfcService: screenState= 1
08-05 02:10:33.150  1857  2666 E NxpNfcJni: getReconnectState = 0x0
,08-05 02:10:36.133   295   341 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-05 02:10:37.129   946  1285 V AlarmManager: ELAPSED_WAKEUP set : Alarm{302159ed type 2 when 159325 com.android.systemui} when 159325
,08-05 02:10:37.131  1372  1372 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
08-05 02:10:37.140  1802  1826 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
08-05 02:10:37.144  1802  1826 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-05 02:10:37.144  1802  1826 D PhoneUtils: getPhoneCount() sPhoneCount = 1
,08-05 02:10:37.147  1802  1826 V TelecomServiceImpl: getCallState : 0
08-05 02:10:37.148  1802  1827 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
08-05 02:10:37.148  1802  1827 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-05 02:10:37.148  1802  1827 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-05 02:10:37.149  1372  1372 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
08-05 02:10:37.150  1372  1372 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
08-05 02:10:40.319  6999  7094 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-05 02:10:40.319  6999  7094 I jxcore-log: 
,08-05 02:10:40.326  6999  7094 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-05 02:10:40.326  6999  7094 I jxcore-log: 
08-05 02:10:40.330  2078  3488 D BluetoothAdapterService(721733341): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a9a099b
,08-05 02:10:40.332  6999  7094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 02:10:40.332  6999  7094 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 02:10:40.332  6999  7094 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 02:10:40.332  6999  7094 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 02:10:40.332  6999  7094 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 02:10:40.332  6999  7094 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 02:10:40.332  6999  7094 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 02:10:40.332  6999  7094 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 02:10:40.333  2078  3488 D BluetoothAdapterService(721733341): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a9a099b
08-05 02:10:40.334  6999  7094 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 02:10:40.336  6999  7094 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-05 02:10:40.336  6999  7094 I jxcore-log: 
08-05 02:10:40.339  6999  7094 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-05 02:10:40.339  6999  7094 I jxcore-log: 
08-05 02:10:40.885  6999  7094 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-05 02:10:40.885  6999  7094 I jxcore-log: Failed to execute UT.
08-05 02:10:40.885  6999  7094 I jxcore-log: 
,08-05 02:10:40.885  6999  7094 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-05 02:10:40.885  6999  7094 I jxcore-log: 
,08-05 02:10:40.888  6999  7094 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 02:10:40.888  6999  7094 I jxcore-log: 
08-05 02:10:40.899  6999  6999 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-05 02:10:41.138   295   341 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-05 02:10:41.258  7174  7174 D AndroidRuntime: 
08-05 02:10:41.258  7174  7174 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-05 02:10:41.265  7174  7174 D AndroidRuntime: CheckJNI is OFF
08-05 02:10:41.594  7174  7174 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-05 02:10:41.651   946  1017 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
08-05 02:10:41.652   946  1017 I ActivityManager: Killing 6999:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
,08-05 02:10:41.711   946  2676 I WindowState: WIN DEATH: Window{295ca8c2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-05 02:10:41.717   946  2676 D InputDispatcher: Focus left window: Window{295ca8c2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 02:10:41.717   946  2676 D InputDispatcher: Window went away: Window{295ca8c2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 02:10:41.744   946  1067 W PackageSettings: Skipping PackageSetting{1038fea9 com.example.hello/10317} due to missing metadata
,08-05 02:10:41.796   946  1017 I ActivityManager:   Force finishing activity ActivityRecord{2195eb0a u0 com.test.thalitest/.MainActivity t255}
,08-05 02:10:41.812   946   946 V ActivityManager: Display changed displayId=0
,08-05 02:10:41.817  1802  1802 D DSDPConnection: Display #0 changed.
08-05 02:10:41.829   946  1638 W ActivityManager: Spurious death for ProcessRecord{21e7b022 6999:com.test.thalitest/u0a30}, curProc for 6999: null
,08-05 02:10:41.833   946  1067 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
08-05 02:10:41.839   946  1067 I ActivityManager:   Force finishing activity ActivityRecord{2195eb0a u0 com.test.thalitest/.MainActivity t255 f}
08-05 02:10:41.839   946  1067 W ActivityManager: Duplicate finish request for ActivityRecord{2195eb0a u0 com.test.thalitest/.MainActivity t255 f}
,08-05 02:10:41.913  2029  2029 I art     : Explicit concurrent mark sweep GC freed 3695(294KB) AllocSpace objects, 2(47KB) LOS objects, 40% free, 12MB/20MB, paused 7.070ms total 72.746ms
,08-05 02:10:41.966  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-05 02:10:41.974  6421  6421 I art     : Explicit concurrent mark sweep GC freed 1658(80KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/19MB, paused 995us total 130.657ms
08-05 02:10:41.980  3628  3628 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-05 02:10:41.983  1772  2394 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-05 02:10:41.984  3628  3628 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-05 02:10:41.984  3628  3628 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-05 02:10:41.984  3628  3628 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
,08-05 02:10:41.984  3628  3628 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 02:10:41.984  3628  3628 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 02:10:41.984  3628  3628 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 02:10:41.984  3628  3628 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-05 02:10:41.984  3628  3628 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 02:10:41.984  3628  3628 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 02:10:41.984  3628  3628 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-05 02:10:41.984  3628  3628 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-05 02:10:41.985   946  1287 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-05 02:10:41.986  1910  1910 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
08-05 02:10:42.041   946  1017 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7198 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-05 02:10:42.047  1949  1949 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
08-05 02:10:42.068  1949  1949 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,08-05 02:10:42.091   946  2676 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7204 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,08-05 02:10:42.117  1372  1372 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-05 02:10:42.176  1949  1949 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-05 02:10:42.185  1949  1949 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-05 02:10:42.185  1949  1949 I Activity: Activity.onPostResume() called 
08-05 02:10:42.194  1949  1949 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
,08-05 02:10:42.206   946   946 I art     : Explicit concurrent mark sweep GC freed 39799(2MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 23MB/35MB, paused 20.377ms total 285.694ms
,08-05 02:10:42.214   946  1043 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-05 02:10:42.215   946  1043 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,08-05 02:10:42.218   946  1043 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-05 02:10:42.218   946  1043 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-05 02:10:42.218   946  1067 I art     : WaitForGcToComplete blocked for 122.038ms for cause Explicit
08-05 02:10:42.218   946  1043 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-05 02:10:42.219  1949  7232 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,08-05 02:10:42.219   946  2016 D InputDispatcher: Focus entered window: Window{d2c9b7f u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-05 02:10:42.220   946  1043 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@35189eae,  pkg=WindowManager.LayoutParams
08-05 02:10:42.220   946  1043 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-05 02:10:42.228  7204  7204 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-05 02:10:42.229  1372  1372 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-05 02:10:42.229  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-05 02:10:42.229  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-05 02:10:42.229  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-05 02:10:42.229  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-05 02:10:42.229  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
,08-05 02:10:42.242  1949  1949 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-05 02:10:42.243  1949  1949 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-05 02:10:42.244  1949  1949 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-05 02:10:42.264  7198  7198 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 02:10:42.266  7198  7198 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 02:10:42.268  7198  7198 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 02:10:42.279  1949  1949 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
,08-05 02:10:42.292  1949  1949 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-05 02:10:42.294  1949  1949 I PhoneWindow: [setNavigationBarColor] color=0x 0
,08-05 02:10:42.309  1372  1494 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,08-05 02:10:42.309  1372  1494 D KeyguardModel: createShortcutInfo...
,08-05 02:10:42.314  1372  1494 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-05 02:10:42.314  1372  1494 D KeyguardModel: createShortcutInfo...
08-05 02:10:42.315  1372  1494 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 02:10:42.317  1372  1494 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-05 02:10:42.319  1372  1494 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 02:10:42.319  1372  1494 D KeyguardModel: createShortcutInfo...
08-05 02:10:42.320  1372  1494 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 02:10:42.320  1372  1494 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-05 02:10:42.322  1372  1494 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 02:10:42.322  1372  1494 D KeyguardModel: createShortcutInfo...
,08-05 02:10:42.323  1372  1494 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 02:10:42.323  1372  1494 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-05 02:10:42.325  1372  1494 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 02:10:42.325  1372  1494 D KeyguardModel: createShortcutInfo...
08-05 02:10:42.335   946   946 D administrator: Handling package changes for user 0
,08-05 02:10:42.342  1372  1372 D KeyguardModel: handleShortcutListChanged...
08-05 02:10:42.350  1372  1494 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-05 02:10:42.350  1372  1494 D KeyguardModel: createShortcutInfo...
,08-05 02:10:42.353  1372  1494 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-05 02:10:42.353  1372  1494 D KeyguardModel: createShortcutInfo...
08-05 02:10:42.354  1372  1494 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 02:10:42.355  1372  1494 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-05 02:10:42.356  1372  1494 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 02:10:42.356  1372  1494 D KeyguardModel: createShortcutInfo...
08-05 02:10:42.358  1372  1494 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 02:10:42.358  1372  1494 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-05 02:10:42.360  1372  1494 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 02:10:42.360  1372  1494 D KeyguardModel: createShortcutInfo...
08-05 02:10:42.362  1372  1494 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 02:10:42.363  1372  1494 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-05 02:10:42.366  1372  1494 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 02:10:42.366  1372  1494 D KeyguardModel: createShortcutInfo...
08-05 02:10:42.374  1372  1372 D KeyguardModel: handleShortcutListChanged...
,08-05 02:10:42.416   946  1947 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-05 02:10:42.418   946  1947 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6999 uid 10030
,08-05 02:10:42.475  1949  1949 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-05 02:10:42.482  1949  1949 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3c48630d time:164687
08-05 02:10:42.486  1632  1632 E b       : Unable to connect to the editor to retrieve text... will retry later
,08-05 02:10:42.492   946  1054 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3986e839 u0 com.lge.launcher2/.Launcher t254} time:164696
08-05 02:10:42.510  7198  7198 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-05 02:10:42.522   946   946 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-05 02:10:42.522   946   946 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-05 02:10:42.524   946   946 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-05 02:10:42.528   946  1351 D TaskPersister: removeObsoleteFile: deleting file=255_task.xml
08-05 02:10:42.535  7198  7198 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,08-05 02:10:42.548  1949  1949 I art     : Explicit concurrent mark sweep GC freed 4447(249KB) AllocSpace objects, 4(645KB) LOS objects, 40% free, 15MB/25MB, paused 1.619ms total 64.207ms
08-05 02:10:42.548  1949  1949 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-05 02:10:42.580   946  1067 I art     : Explicit concurrent mark sweep GC freed 18423(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 7.346ms total 358.444ms
,08-05 02:10:42.715  1857  1857 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-05 02:10:42.715  1857  1857 D LCardEmulationManager: getDefaultRoute
,08-05 02:10:42.719  7174  7174 D AndroidRuntime: Shutting down VM
08-05 02:10:42.776   946  1067 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7240 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-05 02:10:42.796   305   305 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 22.409ms
,08-05 02:10:42.821   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 307us total 22.194ms
,08-05 02:10:42.823   946  1016 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 02:10:42.844   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 314us total 22.317ms
08-05 02:10:42.880   946  1928 I ActivityManager: Killing 6541:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,08-05 02:10:42.888  7198  7198 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-05 02:10:42.931   946  1016 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-05 02:10:42.944   946  1928 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7258 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-05 02:10:42.945   946  1928 I ActivityManager: Killing 6574:com.lge.bnr/1000 (adj 15): empty #11
08-05 02:10:42.968   946  1638 W libprocessgroup: failed to open /acct/uid_1000/pid_6574/cgroup.procs: No such file or directory
08-05 02:10:42.969  1949  1949 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-05 02:10:42.971   946  2676 W libprocessgroup: failed to open /acct/uid_10086/pid_6541/cgroup.procs: No such file or directory
,08-05 02:10:43.038  7258  7258 I AppUp4:AppBoxCP: onCreate
08-05 02:10:43.039  7258  7258 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-05 02:10:43.060  7258  7258 W FileUtils: Failed to chmod(/data/data/com.lge.appbox.client/databases/appbox.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
08-05 02:10:43.060  7258  7258 I AppUp4:DB:  setFingerPrint start
08-05 02:10:43.061  7258  7258 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
,08-05 02:10:43.070  7258  7258 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
08-05 02:10:43.070  7258  7258 I AppUp4:DB:  SDK version = 21
08-05 02:10:43.070  7258  7258 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-05 02:10:43.071  7258  7258 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-05 02:10:43.099  7258  7258 E SQLiteLog: (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error

```
