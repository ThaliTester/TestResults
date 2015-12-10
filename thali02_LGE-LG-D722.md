#### Test 50650278b86327b_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:10:53.268 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/libc-netbsd( 6236): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6236): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6236): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6236): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  268): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
,I/System.out( 6236): propertyValue:false
E/PlayEventLogger( 6236): Status 503 without retry-after header
--------- beginning of system
I/ActivityManager(  964): Killing 6156:com.android.gallery3d/u0a23 (adj 15): empty #11
I/ActivityManager(  964): Killing 5817:com.google.android.talk/u0a61 (adj 15): empty #12
I/ThermalEngine(  286): Sensor:pa_therm0:33000 mC
W/libprocessgroup(  964): failed to open /acct/uid_10023/pid_6156/cgroup.procs: No such file or directory
W/libprocessgroup(  964): failed to open /acct/uid_10061/pid_5817/cgroup.procs: No such file or directory
D/AndroidRuntime( 6466): 
D/AndroidRuntime( 6466): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6466): CheckJNI is OFF
I/GAV2    ( 6311): Thread[GAThread,5,main]: No campaign data found.
D/AndroidRuntime( 6466): Calling main entry com.android.commands.am.Am
I/ActivityManager(  964): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  964): setTaskToReturnTo : TaskRecord{1c37030d #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  964): setTaskToReturnTo : TaskRecord{1c37030d #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  964): AppWindowTokenEx init.. 
D/ContextHelper(  964): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  964): Focus left window: Window{1f2cdfb1 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6466): Shutting down VM
D/SplitWindow(  964): check instance of lgWin Window{3bd67f2f u0 Starting com.test.thalitest}
I/ActivityManager(  964): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6483 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/HotwordDetector( 1942): Closing mic
I/MicrophoneInputStream( 1942): mic_close com.google.android.apps.gsa.speech.audio.u@1fffe817
V/AudioRecord( 1942): stop()
D/AudioRecord( 1942): AudioRecord->stop()
V/AudioFlinger(  273): RecordHandle::stop()
V/AudioFlinger(  273): RecordThread::stop
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
V/AudioFlinger(  273): Record stopped OK
V/AudioPolicyManager(  273): stopInput() input 17
V/AudioPolicyService(  273): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  273): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  273): AudioCommandThread() waking up
V/AudioPolicyService(  273): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  273): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  273): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  273): ThreadBase::setParameters() routing=0
V/AudioFlinger(  273): sendConfigEvent_l() num events 1 event 2
I/WindowStateAnimator(  964): Starting window displayed
V/AudioFlinger(  273): processConfigEvents_l() remaining events 1
V/AudioFlinger(  273): processConfigEvents_l() DONE thread 0xb384a000
D/audio_hw_primary(  273): in_standby: enter: stream (0xb546dde0) usecase(7: audio-record)
I/SystemUI[Framework](  964): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  964): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  964): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  964): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  964): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3fe33132,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  964): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1371): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1371):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1371): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1371): draw background and invalidate : color = a000000
D/BarTransitions( 1371): draw background and invalidate : color = b0b0b0b
V/audio_hw_primary(  273): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  273): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  273): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  273): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  273): disable_audio_route: exit
E/audio_hw_primary(  273): disable_snd_device: enter 144
D/hardware_info(  273): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  273): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  273): stop_input_stream: exit: status(0)
V/audio_hw_primary(  273): in_standby: exit:  status(0)
V/AudioFlinger(  273): RecordThread: loop stopping
V/AudioPolicyService(  273): AudioCommandThread() going to sleep
V/AudioPolicyManager(  273): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  273): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  273): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  273): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  273): AudioCommandThread() waking up
V/AudioPolicyService(  273): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  273): AudioCommandThread() going to sleep
,V/AudioPolicyService(  273): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  273): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  273): AudioCommandThread() waking up
V/AudioPolicyService(  273): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  273): setParameters(): io 17, keyvalue hotword_active=0, calling pid 273
V/AudioFlinger(  273): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  273): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  273): RecordThread: loop starting
V/AudioFlinger(  273): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  273): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  273): in_set_parameters: exit: status(0)
V/AudioFlinger(  273): processConfigEvents_l() DONE thread 0xb384a000
V/AudioFlinger(  273): RecordThread: loop stopping
V/AudioPolicyService(  273): AudioCommandThread() going to sleep
V/AudioRecord( 1942): stop()
V/AudioRecord( 1942): stop()
,V/AudioRecord( 1942): stop()
V/AudioFlinger(  273): RecordHandle::stop()
V/AudioFlinger(  273): RecordThread::stop
V/AudioFlinger(  273): releasing 16 from 1942 for -1
V/AudioFlinger(  273):  decremented refcount to 0
V/AudioPolicyManager(  273): releaseInput() 17
V/AudioFlinger(  273): purging stale effects
V/AudioPolicyManager(  273): closeInput(17)
V/AudioFlinger(  273): closeInput() 17
V/AudioSystem(  273): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  273): ThreadBase::exit
V/AudioFlinger(  273): RecordThread: loop starting
V/AudioSystem( 3169): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1371): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  964): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  273): RecordThread 0xb384a000 exiting
V/AudioSystem( 1751): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  273): adev_close_input_stream: enter:stream_handle(0xb546dde0)
V/AudioSystem( 2687): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  273): in_standby: enter: stream (0xb546dde0) usecase(7: audio-record)
V/audio_hw_primary(  273): in_standby: exit:  status(0)
V/AudioPolicyService(  273): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  273): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  273): releaseInput() exit
V/AudioPolicyService(  273): AudioCommandThread() waking up
V/AudioFlinger(  273): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  273): AudioCommandThread() processing update audio port list
V/AudioFlinger(  273): removeClient_l() pid 1942, calling pid 273
V/AudioPolicyService(  273): AudioCommandThread() going to sleep
V/AudioSystem( 1942): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1996): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 1942): Stopping hotword detection.
I/HotwordRecognitionRnr( 1942): Hotword detection finished
,D/ContextHelper( 6483): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6483): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6483): Time to load native libraries: 18 ms (timestamps 9951-9969)
I/LibraryLoader( 6483): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6483): Binding Chromium to main looper Looper (main, tid 1) {647963e}
,I/LibraryLoader( 6483): Expected native library version number "",actual native library version number ""
I/chromium( 6483): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6483): Initializing chromium process, singleProcess=true
,W/art     ( 6483): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6483): ApplicationContext is null in ApplicationStatus
W/chromium( 6483): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6483): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6483): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6483): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6483): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6483): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6483): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6483): Remote Branch: 
I/Adreno-EGL( 6483): Local Patches: 
I/Adreno-EGL( 6483): Reconstruct Branch: 
,V/AudioPolicyService(  273): registerClient() client 0xb57eb760, uid 10316
,D/BluetoothManagerService(  964): Message: 20
D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19808079:true
D/BluetoothAdapterService(774035530)( 1996): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1b0362f0
,W/art     ( 6483): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6483): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6483): CordovaWebView is running on device made by: LGE
,W/art     ( 6483): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6483): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 6483): Activity.onPostResume() called 
,D/OpenGLRenderer( 6483): Render dirty regions requested: true
I/OpenGLRenderer( 6483): Initialized EGL, version 1.4
D/OpenGLRenderer( 6483): Enabling debug mode 0
,D/Atlas   ( 6483): Validating map...
,D/SplitWindow(  964): check instance of lgWin Window{3dc579e9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6483): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/InputDispatcher(  964): Focus entered window: Window{3dc579e9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  964): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  964): Displayed com.test.thalitest/.MainActivity: +1s26ms
I/Timeline(  964): Timeline: Activity_windows_visible id: ActivityRecord{2f6872c2 u0 com.test.thalitest/.MainActivity t220} time:100562
I/Timeline( 6483): Timeline: Activity_idle id: android.os.BinderProxy@3a3caa25 time:100575
,W/BindingManager( 6483): Cannot call determinedVisibility() - never saw a connection for the pid: 6483
,D/JsMessageQueue( 6483): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  964): Killing 6175:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10018/pid_6175/cgroup.procs: No such file or directory
,D/jxcore_app_log( 6483): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622908928
D/JX-Cordova( 6483): jxcore cordova android initializing
,D/CAR.SERVICE( 6397): mConnectedToCar = false, abort
,E/ActivityThread( 6397): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2a51fb67 that was originally bound here
E/ActivityThread( 6397): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2a51fb67 that was originally bound here
E/ActivityThread( 6397): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6397): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6397): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6397): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6397): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6397): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6397): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6397): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6397): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6397): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6397): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6397): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6397): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6397): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6397): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6397): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6397): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6397): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6397): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6397): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6397): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6397): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6397): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/ActivityThread( 6397): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@101cb0fe that was originally bound here
E/ActivityThread( 6397): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@101cb0fe that was originally bound here
E/ActivityThread( 6397): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6397): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6397): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6397): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6397): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6397): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6397): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6397): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6397): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6397): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6397): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6397): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6397): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6397): 	at android.app.ActivityThread.acce,ss$1900(ActivityThread.java:155)
E/ActivityThread( 6397): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6397): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6397): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6397): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6397): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6397): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6397): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6397): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  964): Unbind failed: could not find connection for android.os.BinderProxy@2de97d21
,I/art     ( 6483): CheckpointMarkThreadRoots callback created = 0x9f6c8360
,I/art     ( 6483): CheckpointMarkThreadRoots callback created = 0x9f6c8330
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/jxcore-log( 6483): Initializing JXcore engine
,W/jxcore-log( 6483): JXcore engine is ready
W/jxcore-log( 6483): Starting JXcore engine
,W/.test.thalitest( 6483): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7370]" dev="sockfs" ino=7370 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6483): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 6483): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8745]" dev="sockfs" ino=8745 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6483): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6483): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6483): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[30795]" dev="sockfs" ino=30795 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 6483): Platform android
W/jxcore-log( 6483): 
,W/jxcore-log( 6483): Process ARCH arm
W/jxcore-log( 6483): 
I/ThermalEngine(  286): Sensor:pa_therm0:33000 mC
,I/rmt_storage(  266): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  266): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  266): wakelock acquired: 1, error no: 42
,I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  266): 
I/rmt_storage(  266): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/jxcore-log( 6483): JXcore Cordova bridge is ready!
I/jxcore-log( 6483): 
W/jxcore-log( 6483): JXcore engine is started
,I/chromium( 6483): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 6483): Skipped 185 frames!  The application may be doing too much work on its main thread.
V/AlarmManager(  964): RTC_WAKEUP set : Alarm{ec84307 type 0 when 1449756659724 com.google.android.googlequicksearchbox} when 1449756659724
,D/PowerManagerServiceEx(  964): acquireWakeLockInternal: lock=357792421, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,D/WeatherService( 2665): 2 : TimeTick Intent has been received, Time(hour:min:sec) 15:11:0
D/WeatherService( 2665): 2 : TimeTick Intent And Screen On
D/WeatherService( 2665): 2 : SDK version : 21
W/ActivityManager(  964): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2665): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2665): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2665): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2665): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 2665): 2 : This is isUpdating : false
D/WeatherService( 2665): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2665): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2665): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2665): 2 : Fixed theme : optimus
I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
D/WeatherReflect( 2665): 2 : Map key string is -2
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/lim     ( 2665): 2 : time = 15:11
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/WeatherReflect( 2665): Model Name : LG-D722
D/WeatherTheme( 2665): 2 : Different view - status_min_formatted : 10 != 11
D/WeatherTheme( 2665): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2665): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2665): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2665): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2665): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2665): currentPackage=com.lge.sizechangable.weather.theme.optimus
,D/Weather4x2_optimus( 2665): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2665): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2665): forecast size is 0
,D/Theme   ( 2665): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2665): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2665): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2665): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2665): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2665): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2665): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2665): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2665): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2665): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2665): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2665): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2665): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2665): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2665): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2665): url is : null
D/Theme   ( 2665): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2665): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2665): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2665): 2 : update view, appWidgetId: 2
D/WeatherService( 2665): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 15:11:0
D/PowerManagerServiceEx(  964): releaseWakeLockInternal: lock=357792421 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,W/SQLiteConnectionPool( 2270): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ActivityManager(  964): Process com.lge.qremote (pid 5762) has died
,D/UEI.SmartControl( 5605): Service.onUnbind: IControl
D/UEI.SmartControl( 5605): Service.onDestroy
D/UEI.SmartControl( 5605): Shutdown IRRCPlayer... 
W/irrc_jni( 5605): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5605): ~IrrcClient ++ 
D/irrcClient( 5605): ~IrrcClient -- 
W/irrc_jni( 5605): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5605): Blaster closed
D/UEI.SmartControl( 5605): Blaster closed
D/UEI.SmartControl( 5605): Shut down QS...
D/UEI.SmartControl( 5605): Stopped file observer...
I/UEI.SmartControl( 5605): QS lib stop result = true
D/UEI.SmartControl( 5605): QS shutdown complete
I/jxcore-log( 6483): Toggling radios to true
I/jxcore-log( 6483): 
,D/BluetoothAdapter( 6483): enable(): BT is already enabled..!
D/WifiServiceImplEx(  964): setWifiEnabled: true pid=6483, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  964): setWifiEnabled: true pid=6483, uid=10316
,D/WifiServiceImplEx(  964): disconnect pid=6483, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  964): reconnect pid=6483, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6483): Radios toggled
I/jxcore-log( 6483): 
D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6483): Got Device Bluetooth address: F8:95:C7:87:85:54
I/jxcore-log( 6483): 
,I/jxcore-log( 6483): Perf Test app loaded loaded
I/jxcore-log( 6483): 
I/jxcore-log( 6483): check test folder
I/jxcore-log( 6483): 
I/jxcore-log( 6483): found test : ./testFindPeers.js
I/jxcore-log( 6483): 
,I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2720): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2720): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  964): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  964): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log( 6483): found test : ./testSendData.js
I/jxcore-log( 6483): 
D/WfdsMonitor( 1798): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/LGWifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  964): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  268): Clearing all IP addresses on wlan0
I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 7
,I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 7
,D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/NativeCrypto( 1732): Read error: ssl=0xaaf3ca00: I/O error during system call, Connection timed out
D/WifiHS20(  964): hidePasspointNotification off =false
,D/ConnectivityService(  964): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:01.557 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  964): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
V/NativeCrypto( 1732): SSL shutdown failed: ssl=0xaaf3ca00: I/O error during system call, Broken pipe
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
,D/ConnectivityService(  964): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,I/ActivityManager(  964): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6610 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/WifiStateMachine(  964): Start Disconnecting Watchdog 1
,D/WifiHS20(  964): hidePasspointNotification off =false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  964): ValidatedState{ when=-6ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  964): DefaultState{ when=-14ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGWifiP2pService(  964): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  964): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  964): Forcing reevaluation
I/wpa_supplicant( 2720): wlan0: CTRL-EVENT-SCAN-STARTED 
D/CommandListener(  268): Clearing all IP addresses on wlan0
,D/ConnectivityService(  964): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  964): disableDataServiceNotify
D/WifiHS20(  964): hidePasspointNotification off =false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/DSQN    (  964): stop dsqn bin
D/ConnectivityService(  964): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  964):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  964):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  964): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  964):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  964): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Nat464Xlat(  964): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/DhcpStateMachine(  964): StoppedState
D/DhcpStateMachine(  964): StoppedState{ when=-53ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  964): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  964): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  964): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  964): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  964): MasterInitialState.processMessage what=3
V/NetworkPolicy(  964): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  964): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy(  964): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  964): MasterInitialState.processMessage what=3
D/ConnectivityService(  964): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  964): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  964): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  964): Removing idletimer
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524292
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:01.707 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityManager.CallbackHandler( 2270): CM callback handler got msg 524292
W/Settings(  964): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:01.717 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,W/QCNEJ   ( 1839): |CORE| No family connected
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/TelephonyNetworkFactory-1( 1751): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  964): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = -1
D/TelephonyNetworkFactory-1( 1751):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1798): isInternetCheckAvailable return false
D/WifiServiceExtension( 1798): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  964): ValidatedState{ when=-29ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  964): DefaultState{ when=-29ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
I/chromium( 6483): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  964): Disconnected - quitting
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/WifiNetworkAgent(  964): NetworkAgent: NetworkAgent channel lost
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
,D/WifiHS20(  964): hidePasspointNotification off =false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:01.751 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:01.756 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WIFI    (  964): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  964):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt(  964): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  964): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt(  964): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  964): setSupplicantStateSCANNING
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
,W/ResourcesManager( 6610): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6610): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6610): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6610): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6610): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/ActivityManager(  964): Process com.google.android.apps.plus (pid 6211) has died
,I/IndexDatabaseHelper( 6610): Using schema version: 115
,I/IndexDatabaseHelper( 6610): Index is fine
I/ActivityManager(  964): Process com.uei.lg.quicksetsdk.lite (pid 5605) has died
,V/WiFiOffLoadBroadcast( 6610): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/ActivityManager(  964): Process com.lge.lockscreensettings (pid 6194) has died
,D/WiFiOffLoadBroadcast( 6610): MCCMNC not supported: null
I/ActivityManager(  964): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6638 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6638): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6638): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6638): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  964): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6658 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager(  964): Process com.google.android.gm (pid 6311) has died
,W/ResourcesManager( 6658): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  964): Message: 20
D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10b3af59:true
,D/BluetoothAdapterService(774035530)( 1996): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1b0362f0
D/BluetoothAdapterService(774035530)( 1996): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1b0362f0
V/WiFiOffLoadBroadcast( 6610): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6610): MCCMNC not supported: null
I/PCSuite ( 6638): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6638): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6638): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6610): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6610): MCCMNC not supported: null
I/PCSuite ( 6638): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6638): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6638): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6678 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6678): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2720): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/LocSvc_java(  964): onReceive
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:02.815 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:02.819 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  964): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  964): setSupplicantStateASSOCIATING
I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 4
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/wpa_supplicant( 2720): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiServerServiceExt(  964): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  964): setSupplicantStateASSOCIATED
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  964): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  964): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:02.867 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:02.868 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/wpa_supplicant( 2720): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2720): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiServerServiceExt(  964): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt(  964): setSupplicantStateGROUP_HANDSHAKE
I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 4
I/WifiServiceExtension(  964): setVHTCapabilityType  : false
I/WifiServerServiceExt(  964): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  964): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  964): setSecurityType  : 2
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:02.925 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  964): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  964): Got NetworkAgent Messenger
D/ConnectivityService(  964): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  964): NetworkAgent connected
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:02.928 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/WifiServiceExtension( 1798): isInternetCheckAvailable return false
E/WifiConfigStore(  964): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/Babel_SMS( 6678): MmsConfig: mnc/mcc: 0/0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/Babel_SMS( 6678): MmsConfig.loadMmsSettings
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/Babel_SMS( 6678): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6678): MmsConfig.loadFromDatabase
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
,E/WifiConfigStore(  964): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  268): Setting iface cfg
E/WifiStateMachine(  964): Start Dhcp Watchdog 2
D/DhcpStateMachine(  964): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  964): WaitBeforeStartState
D/ConnectivityService(  964): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/Babel_SMS( 6678): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6678): MmsConfig.loadFromResources
E/Babel_SMS( 6678): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6678): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6678): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6678): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6678): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 6678): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6678): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6678): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6678): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6678): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6678): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6678): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6678): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6678): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6678): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6678): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6678): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6678): found sensor: Motion Accel, handle=46
W/Settings( 6678): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6678): startup - clean
,E/WifiStateMachine(  964): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  964): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@376012d9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  964): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@376012d9 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  964): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  964): DHCP Start wake lock is acquired.
D/CommandListener(  268): Setting iface cfg
I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  268): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  964): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  964): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  964): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  964): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  964): setSupplicantStateCOMPLETED
D/ConnectivityService(  964): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  964): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  964): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  964): ignoring duplicate network state non-change
I/art     ( 6678): CheckpointMarkThreadRoots callback created = 0xaaf45720
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1798): isInternetCheckAvailable return false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:03.071 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:03.073 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  964): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  964): Adding iface wlan0 to network 101
D/WifiServiceExtension( 1798): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/WifiHS20(  964): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  964): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = true, mWifiLevel = 2
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:03.09 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  964): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:03.096 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService(  964): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  964): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  964): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  268): netlink response contains error (File exists)
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = true, mWifiLevel = 2
D/ConnectivityService(  964): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  964): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  964): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
,D/ConnectivityService(  964): Setting Dns servers for network 101 to [/192.168.1.1]
,D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/Nat464Xlat(  964): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  964): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  964): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  964): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  964):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  964):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  964):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  964):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/Babel   ( 6678): deleted: false for 0
D/ConnectivityService(  964):     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  964): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  964): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  964): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  964):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  964):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  964): currentScore = 0, newScore = 20
D/ConnectivityService(  964):    accepting network in place of null
D/ConnectivityService(  964): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  964): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  964):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1751): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1751):   my score=50, my filter=[ Transports: CE,LLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  964): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  964): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  964): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  964): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  964): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  964): [e] list.add(nai) empty : false size: 1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  964): [LWD] Start DNSResolver start to wait
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  964): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  964): [LWD] wait 500ms before dns check
D/ConnectivityService(  964): validation of new default Network = false
D/ConnectivityService(  964): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  964): enableDataServiceNotify 
D/DSQN    (  964): start dsqn bin
V/NetworkPolicy(  964): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService(  964): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  964):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  964):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  964): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  964):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  964): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 2270): CM callback handler got msg 524290
,D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/art     ( 6678): CheckpointMarkThreadRoots callback created = 0xaaf45700
,I/DSQN    ( 6721): DSQN samuel.seo ver 141203
E/DSQN    ( 6721): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6721): created command queue thread
I/DSQN    ( 6721): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6721): Interface wlan0 netmask 255.255.255.0 0xc0a80186
V/WiFiOffLoadBroadcast( 6610): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6610): MCCMNC not supported: null
I/PCSuite ( 6638): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6638): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6638): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6610): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6610): MCCMNC not supported: null
W/AudioCapabilities( 6678): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6678): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6678): Unsupported mime audio/g726
W/AudioCapabilities( 6678): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6678): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6678): Unsupported mime video/mjpg
W/VideoCapabilities( 6678): Unsupported mime video/theora
W/AudioCapabilities( 6678): Unsupported mime audio/evrc
,W/AudioCapabilities( 6678): Unsupported mime audio/qcelp
W/VideoCapabilities( 6678): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6678): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6678): Unsupported mime audio/qcelp
W/AudioCapabilities( 6678): Unsupported mime audio/evrc
,D/DhcpStateMachine(  964): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  964): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  964): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/VideoCapabilities( 6678): Unsupported mime video/mp4v-esdp
,I/dhcpcd  ( 6725): version 5.5.6 starting
E/dhcpcd  ( 6725): get_duid: Read-only file system
I/VideoCapabilities( 6678): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6678): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  964): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6729 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6678): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6678): Unrecognized profile 2130706433 for video/avc
V/LGMDMManager( 6658): Create singleton instance
I/dhcpcd  ( 6725): wlan0: rebinding lease of 192.168.1.134
,W/VideoCapabilities( 6678): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6678): onServiceConnected
W/Babel   ( 6678): Attempted to change video mute state without an active call.
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{2cee14f5 type 2 when 108356 com.google.android.gms} when 108356
,I/AudioManager( 6658): getMode name:com.lge.qremote
V/WiFiOffLoadBroadcast( 6610): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6610): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6610): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/UEI.SmartControl( 6729): Quickset Services start...
I/UEI.SmartControl( 6729): Manufacture = LGE
,D/UEI.SmartControl( 6729): File observer start...
E/UEI.SmartControl( 6729): IR Port is disabled: false
D/UEI.SmartControl( 6729): Starting file observer...
D/UEI.SmartControl( 6729): Extracting JNI libs...
D/UEI.SmartControl( 6729): --- this system supports 32-bit or 64-bit only
D/WiFiOffLoadBroadcast( 6610): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6610): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 28529(1689KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 13MB/22MB, paused 2.034ms total 90.453ms
,D/WiFiOffLoadBroadcast( 6610): MCCMNC not supported: null
I/NotificationManager( 6678): com.google.android.talk: cancel(10436) by com.google.android.talk
V/WiFiOffLoadBroadcast( 6610): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6610): MCCMNC not supported: null
D/UEI.SmartControl( 6729): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6729): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6729): --- Extracting JNI libs: libqs_armeabi-v7a.zip
V/WiFiOffLoadBroadcast( 6610): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6610): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6610): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6610): MCCMNC not supported: null
I/UEI.SmartControl( 6729): --- Selecting new region: 2
I/UEI.SmartControl( 6729): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6729): Platform has CIR...
D/UEI.SmartControl( 6729): NO CIR support, need to check package...
I/UEI.SmartControl( 6729): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6729): QS Service created
V/WiFiOffLoadBroadcast( 6610): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6610): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6610): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6610): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6610): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/UEI.SmartControl( 6729): QS start get config
D/WiFiOffLoadBroadcast( 6610): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6610): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6610): MCCMNC not supported: null
I/PCSuite ( 6638): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6638): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6610): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6610): MCCMNC not supported: null
I/PCSuite ( 6638): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6638): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  268): App 10006 tries DNS query. Accept family:0 protocol:0
D/UEI.SmartControl( 6729): Loading JNI Libs...
,D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/UEI.SmartControl( 6729):  configuring local db...
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  964): [LWD] DNSResolver start dns
D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  268): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out(  964): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  964): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  964): Checking http://clients3.google.com/generate_204 on "NG700"
,D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6721): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6721): restart monitoring
D/LGDataListener(  268): argv[0]=dsqncommand
D/LGDataListener(  268): argv[1]=wlan0
D/LGDataListener(  268): argv[2]=1
,D/LGDataListener(  268): notifyDSQN DSQN STARTMONITOR wlan0 1
,I/DSQN    ( 6721): dsqn report finish
D/DSQN    (  964): DSQM DsqnNotification wlan0  1
D/DSQN    (  964): start to monitor internet connection
I/ThermalEngine(  286): Sensor:pa_therm0:33000 mC
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  964): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 14:11:03 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449756663714], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449756663693]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  964): Don't send network conditions - lacking user consent.
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiServiceExtension( 1798): isInternetCheckAvailable return false
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  964): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  964): Validated
D/ConnectivityService(  964): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  964): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  964):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  964):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  964):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  964):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  964):     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
D/ConnectivityService(  964): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  964): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  964):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  964):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiDataContinuityService(  964): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  964): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  964):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  964): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 2270): CM callback handler got msg 524290
I/WifiServerServiceExt(  964): set CMD_CAPTIVE_CHECK_COMPLETED
D/ConnectivityService(  964): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524290
D/ConnectivityService(  964): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1751): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory-1( 1751):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WIFI    (  964): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  964):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/UEI.SmartControl( 6729):  ---- Has DB8: true
,D/UEI.SmartControl( 6729): QS start statue = true Error code = 0
D/UEI.SmartControl( 6729): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6729): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6729): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6729): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6729): IrrcClient ++ 
D/irrcClient( 6729): getIrrcService ++ 
D/irrcClient( 6729): getIrrcService -- 
D/irrcClient( 6729): IrrcClient -- 
W/irrc_jni( 6729): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6729): Services init done
,D/UEI.SmartControl( 6729): QS Service init finished
I/UEI.SmartControl( 6729): Device manager: loading config....
,D/UEI.SmartControl( 6729): QS Service version name: 0.1.73
D/UEI.SmartControl( 6729): QS Service version code: 1073
D/UEI.SmartControl( 6729): Service requested: Control
D/UEI.SmartControl( 6729): Config is loaded...
,D/UEI.SmartControl( 6729): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6729):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6729): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6729): -----IControl: 11
D/UEI.SmartControl( 6729): Internal service binding...
D/UEI.SmartControl( 6729): Caller: com.lge.qremote
D/UEI.SmartControl( 6729): ------------ IControl registerCallback...
I/UEI.SmartControl( 6729): Registering callback...
D/UEI.SmartControl( 6729): -----IControl: 19
D/UEI.SmartControl( 6729): Caller: com.lge.qremote
,I/UEI.SmartControl( 6729): Registering Services Ready callback...
I/UEI.SmartControl( 6729): Notify client services are ready...
D/UEI.SmartControl( 6729): -----IControl: 8
D/UEI.SmartControl( 6729): Caller: com.lge.qremote
I/AudioManager( 6658): getMode name:com.lge.qremote
,I/AudioManager( 6658): getMode name:com.lge.qremote
,I/AudioManager( 6658): getMode name:com.lge.qremote
,I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  964): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  964): identical MTU - not setting
D/Nat464Xlat(  964): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  964): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  964):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  964):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:04.067 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  964): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  964):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524295
D/ConnectivityService(  964): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  964): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  964): enableDataServiceNotify 
D/ConnectivityManager.CallbackHandler( 2270): CM callback handler got msg 524295
D/DSQN    (  964): start dsqn bin
D/DSQN    (  964): dsqn is running restart
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/DSQN    ( 6763): DSQN samuel.seo ver 141203
E/DSQN    ( 6763): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6763): created command queue thread
I/DSQN    ( 6763): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6763): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/ConnectivityService(  964): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/dhcpcd  ( 6725): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 6725): wlan0: leased 192.168.1.134 for 86400 seconds
D/ConnectivityService(  964): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/ConnectivityService(  964): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  964): onReceive
D/LocSvc_java(  964): got connectivity action
D/LocSvc_java(  964): broadcast - no network connections
,D/LocSvc_java(  964): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  964): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,I/ActivityManager(  964): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6783 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  964): RTC_WAKEUP set : Alarm{105cc1d7 type 0 when 1449756663141 com.google.android.gms} when 1449756663141
,D/GpsLocationProvider(  964): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/ProcessCpuTracker(  964): Skipping unknown process pid 6784
,D/LocSvc_java(  964): onReceive
D/LocSvc_java(  964): got connectivity action
D/LocSvc_java(  964): broadcast - no network connections
D/LocSvc_java(  964): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  964): Sending msg: 4 arg1:0 arg2:1
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,I/NotificationManager( 1942): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/MusicStore( 6783): Database version: 120
D/GpsLocationProvider(  964): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  964): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  964): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  964): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  964): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  964): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  964): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  964): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  964): RunningState
I/art     (  964): Explicit concurrent mark sweep GC freed 78745(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.486ms total 289.425ms
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6783): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6783): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6783): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6783): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6783): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6783): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6783): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6783): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3586f16b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6783): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6783): GMSCore installation verified
I/ConfigStore( 6783): Config Database version: 1
,I/MediaRouter( 6783): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6783): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6783): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6783): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  964): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6841 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:05.976 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/GHttpClientFactory( 6783): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6783): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  964): Killing 6353:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/ResourcesManager( 6841): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6841): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6841): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
V/WifiInternetCheck(  964): Single check msg out of sync, ignoring.
,W/libprocessgroup(  964): failed to open /acct/uid_10014/pid_6353/cgroup.procs: No such file or directory
,I/NotificationManager( 6783): com.google.android.music: cancel(1061) by com.google.android.music
I/ActivityManager(  964): Process com.android.vending (pid 6236) has died
D/ConnectivityService(  964): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  964): onReceive
D/LocSvc_java(  964): got connectivity action
D/LocSvc_java(  964): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  964): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  964): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.conn.CONNECTIVITY_CHANGE at null
I/NetworkMonitor( 6783): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider(  964): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/LGEmail ( 6841): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6841): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/BluetoothAdapterService(774035530)( 1996): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1b0362f0
,I/jxcore-log( 6483): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 6483): 
,D/eas_req ( 6841): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  964): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6883 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 21.094ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.796ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 20.580ms
,I/HubEmail( 6841): JNI_OnLoad()
I/HubEmail( 6841): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6841): registerNatives()
I/HubEmail( 6841): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6841): registerNativeMethods()
I/HubEmail( 6841): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 6841): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6841): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6883): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6883): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6883): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/ActivityManager(  964): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6901 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  964): RTC_WAKEUP set : Alarm{336a6bee type 0 when 1449756666640 com.android.vending} when 1449756666640
W/ContextImpl( 6883): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6883): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6883): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager(  964): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6921 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/LGDMClient( 6883): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6883): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6883): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6883): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6883): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6883): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6883): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6883): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  964): Killing 6397:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10006/pid_6397/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6921): onCreate
,W/AppUp4:DB( 6921):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6921):  setFingerPrint start
I/AppUp4:DB( 6921):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6921):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6921):  SDK version = 0
I/AppUp4:DB( 6921):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6921): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6921): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 6921): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6921): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6921): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6921): onReceive
I/AppUp4:CustModeStarterReceiver( 6921): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6921): Context : android.app.ReceiverRestrictedContext@2e360c9f
,D/AppUp4:CustFacade( 6921): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6921): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6921): begin check event
I/AppUp4:CustModeStarterReceiver( 6921): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6921): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/Finsky  ( 6901): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/AppUp4:CustModeStarterReceiver( 6921): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6921): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6921): handleAsyncCustNotification do not startCustService
I/LgeMiscReceiver( 3169): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3169): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3169): networkInfo.isConnected() = false
,I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6962 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/Finsky  ( 6901): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/PhoneMonitor( 6962): Register our PhoneStateListener
W/Settings( 6901): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6901): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6901): com.android.vending: cancel(-1050172287) by com.android.vending
D/MobileConnectivityChangeReceiver( 6962): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6962): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  964): Killing 6610:com.android.settings/1000 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_1000/pid_6610/cgroup.procs: No such file or directory
,V/DownloadManager( 3217): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3217): created cursor android.database.sqlite.SQLiteCursor@1bbb1950 on behalf of 6901
,D/PhoneMonitor( 6962): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/CheckinService( 2270): Checkin interval check for package: unspecified last checkin: 1449756633209 min interval config: 0 actual interval: 34087
V/TelephonyAutoProfiling( 6962): [loadFeatureFromXml] *** start feature loading from xml
,D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
V/DownloadManager( 3217): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
E/BandwidthController(  268): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  268): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/TelephonyAutoProfiling( 6962): [parse] Load xml
V/DownloadManager( 3217): DownloadService onCreate
I/NotificationManager( 3217): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3217): in removeSpuriousFiles
V/TelephonyAutoProfiling( 6962): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6962): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3217): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3217): created cursor android.database.sqlite.SQLiteCursor@34405749 on behalf of 3217
D/Ads     ( 6901): Skipping gmscore version check
I/DownloadManager( 3217): in trimDatabase
V/DownloadManager( 3217): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3217): created cursor android.database.sqlite.SQLiteCursor@2573984e on behalf of 3217
,D/PhoneMonitor( 6962): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
,I/System.out(  964): propertyValue:false
D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  268): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out(  964): propertyValue:false
I/ActivityManager(  964): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7007 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3217): DownloadService onStartCommand
I/DSQN    ( 6763): first global connection report this to start monitoring at DSQM.
I/CheckinService( 2270): Checking schedule, now: 1449756667356 next: 1449756663141
I/CheckinService( 2270): active receiver: enabled
I/DSQN    ( 6763): restart monitoring
D/LGDataListener(  268): argv[0]=dsqncommand
D/LGDataListener(  268): argv[1]=wlan0
D/LGDataListener(  268): argv[2]=1
D/LGDataListener(  268): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6763): dsqn report finish
D/DSQN    (  964): DSQM DsqnNotification wlan0  1
D/DSQN    (  964): start to monitor internet connection
V/DownloadManager( 3217): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3217): created cursor android.database.sqlite.SQLiteCursor@23ae1f05 on behalf of 3217
V/WifiInternetCheck(  964): isHttpConnectionAvailable - We got a valid response : 204
I/CheckinService( 2270): Preparing to send checkin request
I/EventLogService( 2270): Accumulating logs since 1449756626254
,D/Finsky  ( 6901): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6901): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 6901): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6901): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/CheckinRequestBuilder( 2270): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 2270): Failed to find provider info for com.google.android.wearable.settings
V/DownloadManager( 3217): DownloadService onDestroy
D/WeatherAncestor( 2665): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:7
,I/ActivityManager(  964): Killing 6638:com.lge.sync/1000 (adj 15): empty #11
D/UpdateThreadPoolManager( 2665): 2 : This is isUpdating : false
D/WeatherAncestor( 2665): connectivity changed - connection : true
D/Weather_cast( 2665): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2665): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:7
D/WeatherService( 2665): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup(  964): failed to open /acct/uid_1000/pid_6638/cgroup.procs: No such file or directory
,W/ActivityManager(  964): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2665): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2665): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2665): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7034 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 6901): [850] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6901): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/libc-netbsd( 6678): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6678): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6678): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6678): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  268): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out( 6678): propertyValue:false
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Babel   ( 6678): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  964): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7054 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  964): Killing 6729:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 6658): android.os.DeadObjectException
,W/System.err( 6658): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6658): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6658): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6658): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6658): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6658): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6658): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6658): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6658): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6658): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
,W/System.err( 6658): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6658): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6658): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6658): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6658): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6658): android.os.DeadObjectException
W/System.err( 6658): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6658): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6658): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6658): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6658): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6658): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6658): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6658): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6658): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6658): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6658): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6658): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6658): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6658): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6658): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  964): failed to open /acct/uid_10089/pid_6729/cgroup.procs: No such file or directory
W/ActivityManager(  964): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,W/ResourcesManager( 7054): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7054): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  964): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7072 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MultiDex( 7054): VM with version 2.1.0 has multidex support
I/MultiDex( 7054): install
I/MultiDex( 7054): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  964): Process com.google.android.music:main (pid 6783) has died
,V/JNIHelp ( 7054): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7034): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7034): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,D/UEI.SmartControl( 7072): Quickset Services start...
I/UEI.SmartControl( 7072): Manufacture = LGE
D/UEI.SmartControl( 7072): File observer start...
E/UEI.SmartControl( 7072): IR Port is disabled: false
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
D/UEI.SmartControl( 7072): Starting file observer...
D/UEI.SmartControl( 7072): Extracting JNI libs...
W/ContextImpl( 7034): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
D/UEI.SmartControl( 7072): --- this system supports 32-bit or 64-bit only
I/GAv4    ( 7034): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7034):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7034):   adb logcat -s GAv4
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7034): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7034): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/UEI.SmartControl( 7072): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7072): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7072): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,W/ActivityThread( 7054): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7054): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1bbb1950: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7054): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7054): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7054): com.google.android.gms: cancel(39789) by com.google.android.gms
I/UEI.SmartControl( 7072): --- Selecting new region: 2
,I/UEI.SmartControl( 7072): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7072): Platform has CIR...
D/UEI.SmartControl( 7072): NO CIR support, need to check package...
I/UEI.SmartControl( 7072): Model: LG-D722 uses JNI
W/GAv4    ( 7034): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
D/UEI.SmartControl( 7072): QS Service created
W/GAv4    ( 7034): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/UEI.SmartControl( 7072): QS start get config
,I/art     ( 7054): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7054): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/UEI.SmartControl( 7072): Loading JNI Libs...
,D/UEI.SmartControl( 7072):  configuring local db...
I/ActivityManager(  964): Process com.lge.email (pid 6841) has died
,D/NativeLibraryUtils( 7054): Install completed successfully. count=14 extracted=0
,D/UEI.SmartControl( 7072):  ---- Has DB8: true
,I/art     (  964): Explicit concurrent mark sweep GC freed 30436(1607KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 3.167ms total 161.966ms
D/UEI.SmartControl( 7072): QS start statue = true Error code = 0
D/UEI.SmartControl( 7072): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7072): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7072): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7072): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7072): IrrcClient ++ 
D/irrcClient( 7072): getIrrcService ++ 
,D/WVCdm   (  273): Instantiating CDM.
I/WVCdm   (  273): CdmEngine::OpenSession
I/WVCdm   (  273): Level3 Library Dec 11 2014 16:13:16
D/irrcClient( 7072): getIrrcService -- 
D/irrcClient( 7072): IrrcClient -- 
W/irrc_jni( 7072): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7072): Services init done
,I/UEI.SmartControl( 7072): Device manager: loading config....
D/UEI.SmartControl( 7072): QS Service init finished
D/UEI.SmartControl( 7072): Config is loaded...
D/UEI.SmartControl( 7072): QS Service version name: 0.1.73
D/UEI.SmartControl( 7072): QS Service version code: 1073
D/UEI.SmartControl( 7072): Service requested: Control
,D/UEI.SmartControl( 7072): -----IControl: 11
D/UEI.SmartControl( 7072): Internal service binding...
D/UEI.SmartControl( 7072): Caller: com.lge.qremote
D/UEI.SmartControl( 7072): ------------ IControl registerCallback...
I/UEI.SmartControl( 7072): Registering callback...
D/UEI.SmartControl( 7072): -----IControl: 19
W/WVCdm   (  273): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  273): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  273): L1 library not specified. Falling Back to L3
D/UEI.SmartControl( 7072): Caller: com.lge.qremote
I/UEI.SmartControl( 7072): Registering Services Ready callback...
I/UEI.SmartControl( 7072): Notify client services are ready...
D/UEI.SmartControl( 7072): -----IControl: 8
D/UEI.SmartControl( 7072): Caller: com.lge.qremote
D/UEI.SmartControl( 7072):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7072): Notify AllClients services are ready: 0
,I/ThermalEngine(  286): Sensor:pa_therm0:33000 mC
I/WebViewFactory( 7034): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/WVCdm   (  273): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  273): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  273): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  273): CdmEngine::GenerateKeyRequest
D/WVCdm   (  273): PrepareKeyRequest: nonce=4292899791
I/LibraryLoader( 7034): Time to load native libraries: 2 ms (timestamps 3741-3743)
I/LibraryLoader( 7034): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7034): Binding Chromium to main looper Looper (main, tid 1) {1aaf7680}
I/LibraryLoader( 7034): Expected native library version number "",actual native library version number ""
I/chromium( 7034): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7034): Initializing chromium process, singleProcess=true
,W/art     ( 7034): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7034): ApplicationContext is null in ApplicationStatus
W/chromium( 7034): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7034): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7034): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7034): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7034): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7034): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7034): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7034): Remote Branch: 
I/Adreno-EGL( 7034): Local Patches: 
I/Adreno-EGL( 7034): Reconstruct Branch: 
V/AudioPolicyService(  273): registerClient() client 0xb40274e0, uid 10079
,W/AudioManagerAndroid( 7034): Requires BLUETOOTH permission
I/NSApplication( 7034): Starting up...
,I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7145 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 7054): CheckpointMarkThreadRoots callback created = 0xb002d620
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/art     ( 7054): CheckpointMarkThreadRoots callback created = 0xb002d600
,I/ActivityManager(  964): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7164 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  964): Killing 6658:com.lge.qremote/u0a106 (adj 15): empty #11
I/dex2oat ( 7170): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  964): failed to open /acct/uid_10106/pid_6658/cgroup.procs: No such file or directory
,W/ResourcesManager( 7164): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/dex2oat ( 7170): dex2oat took 120.160ms (threads: 4)
,I/Adreno-EGL( 7054): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7054): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7054): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7054): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7054): Remote Branch: 
I/Adreno-EGL( 7054): Local Patches: 
I/Adreno-EGL( 7054): Reconstruct Branch: 
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 114718354649; DSPS: 3851313; Offset : -2823053600
,I/ActivityManager(  964): Killing 6883:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/Adreno-EGL( 7054): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7054): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7054): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7054): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7054): Remote Branch: 
I/Adreno-EGL( 7054): Local Patches: 
I/Adreno-EGL( 7054): Reconstruct Branch: 
,I/Adreno-EGL( 7054): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7054): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7054): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7054): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7054): Remote Branch: 
I/Adreno-EGL( 7054): Local Patches: 
I/Adreno-EGL( 7054): Reconstruct Branch: 
,W/libprocessgroup(  964): failed to open /acct/uid_1000/pid_6883/cgroup.procs: No such file or directory
,I/WVCdm   (  273): CdmEngine::OpenSession
,I/ActivityManager(  964): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7199 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7199): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7199): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7199): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7199): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7199): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7199): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7199): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7199): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7199): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3586f16b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7199): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7199): GMSCore installation verified
,I/ConfigStore( 7199): Config Database version: 1
,I/MediaRouter( 7199): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7199): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7199): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7199): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  964): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7230 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 23.599ms
,I/GHttpClientFactory( 7199): Using our fixed implementation of GMSCore's GoogleHttpClient
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.934ms
,I/GoogleURLConnFactory( 7199): Using platform SSLCertificateSocketFactory
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 21.409ms
I/ActivityManager(  964): Killing 6921:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 7230): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7230): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7230): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/WVCdm   (  273): CdmEngine::CloseSession
,W/libprocessgroup(  964): failed to open /acct/uid_10011/pid_6921/cgroup.procs: No such file or directory
,I/NotificationManager( 7199): com.google.android.music: cancel(1061) by com.google.android.music
I/WVCdm   (  273): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  273): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  273): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  273): CdmEngine::GenerateKeyRequest
D/WVCdm   (  273): PrepareKeyRequest: nonce=407804758
I/LGEmail ( 7230): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7230): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/eas_req ( 7230): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/AlarmManager(  964): RTC_WAKEUP set : Alarm{20929046 type 0 when 1449756671130 com.google.android.googlequicksearchbox} when 1449756671130
,I/ActivityManager(  964): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7258 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7230): JNI_OnLoad()
I/HubEmail( 7230): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7230): registerNatives()
I/HubEmail( 7230): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7230): registerNativeMethods()
I/HubEmail( 7230): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7230): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  964): Killing 6962:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10038/pid_6962/cgroup.procs: No such file or directory
,W/Settings( 7230): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7258): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7258): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7258): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7258): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7258): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7258): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7258): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7258): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  964): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7282 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7258): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7258): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7258): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7258): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7258): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7258): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  964): Killing 7007:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  964): failed to open /acct/uid_10051/pid_7007/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7282): onCreate
,W/AppUp4:DB( 7282):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7282):  setFingerPrint start
I/AppUp4:DB( 7282):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7282):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7282):  SDK version = 0
I/AppUp4:DB( 7282):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7282): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7282): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7282): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7282): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7282): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7282): onReceive
I/AppUp4:CustModeStarterReceiver( 7282): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 7282): Context : android.app.ReceiverRestrictedContext@2e360c9f
D/AppUp4:CustFacade( 7282): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7282): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7282): begin check event
I/AppUp4:CustModeStarterReceiver( 7282): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7282): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 7282): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7282): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7282): handleAsyncCustNotification do not startCustService
I/ActivityManager(  964): Killing 6901:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  964): failed to open /acct/uid_10036/pid_6901/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3169): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3169): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3169): networkInfo.isConnected() = false
I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7301 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7301): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7301): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7301): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  964): Killing 6678:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  964): failed to open /acct/uid_10061/pid_6678/cgroup.procs: No such file or directory
,V/DownloadManager( 3217): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3217): DownloadService onCreate
I/NotificationManager( 3217): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3217): in removeSpuriousFiles
,V/DownloadManager( 3217): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3217): created cursor android.database.sqlite.SQLiteCursor@2558c268 on behalf of 3217
I/DownloadManager( 3217): in trimDatabase
V/DownloadManager( 3217): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3217): created cursor android.database.sqlite.SQLiteCursor@3676a681 on behalf of 3217
I/ActivityManager(  964): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7326 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/CheckinService( 2270): Checkin interval check for package: unspecified last checkin: 1449756633209 min interval config: 0 actual interval: 39006
V/DownloadManager( 3217): DownloadService onStartCommand
,V/DownloadManager( 3217): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3217): created cursor android.database.sqlite.SQLiteCursor@2a51fb67 on behalf of 3217
,D/PhoneMonitor( 7301): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7301): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7301): [parse] Load xml
V/TelephonyAutoProfiling( 7301): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7301): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7301): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3217): DownloadService onDestroy
I/ActivityManager(  964): Killing 7034:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10079/pid_7034/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2665): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:12
D/UpdateThreadPoolManager( 2665): 2 : This is isUpdating : false
D/WeatherAncestor( 2665): connectivity changed - connection : true
D/Weather_cast( 2665): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2665): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:12
,D/WeatherService( 2665): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7357 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  964): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2665): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2665): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2665): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7357): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/WVCdm   (  273): CdmEngine::CloseSession
I/WVCdm   (  273): L3 Terminate.
I/Babel_SMS( 7357): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7357): MmsConfig.loadMmsSettings
,I/MusicWidget( 2617): mDelayedStopHandler : unbind
I/Babel_SMS( 7357): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7357): MmsConfig.loadFromDatabase
I/MusicBrowser( 2687): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2687): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2687): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,D/MusicBrowser( 2687): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2687): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2687): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2687): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2687): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,E/Babel_SMS( 7357): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7357): MmsConfig.loadFromResources
I/MediaFocusControl(  964):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3a3caa25com.lge.music.MediaPlaybackService$6@549e7fa
E/Babel_SMS( 7357): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7357): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/MusicBrowser( 2687): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2687): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@15f8d3bb
,I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2687): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2687): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
,D/SensorManager( 7357): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7357): found sensor: LGE Magnetometer Sensor, handle=10
I/MusicBrowser( 2687): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
D/SensorManager( 7357): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7357): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7357): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7357): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7357): found sensor: LGE Rotation Vector Sensor, handle=36
I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/SensorManager( 7357): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7357): found sensor: LGE Step Counter Sensor, handle=44
I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/SensorManager( 7357): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7357): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7357): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7357): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7357): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7357): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7357): found sensor: Motion Accel, handle=46
I/MusicBrowser( 2687): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2687): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2687): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2687): reset
,V/MediaPlayer[Native]( 2687): setListener
V/MediaPlayer[Native]( 2687): disconnect
V/MediaPlayer[Native]( 2687): destructor
V/AudioFlinger(  273): releasing 19 from 2687 for -1
V/AudioFlinger(  273):  decremented refcount to 0
V/AudioFlinger(  273): purging stale effects
,V/MediaPlayer[Native]( 2687): disconnect
D/MusicBrowser( 2687): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2687): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2687): [SmartShareManagerClient] smartshare client enabled
,W/Settings( 7357): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/MusicBrowser( 2687): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2687): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2687): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2687): [SmartShareManagerClient] unregisterListener: 713171371
W/SmartShareClient( 2687): [SmartShareManagerClient] unregisterListener invalid listener: 713171371
I/Babel_Crash( 7357): startup - clean
I/SmartShareClient( 2687): [SmartShareManagerClient] terminate service: 2687/MediaPlaybackService/611243769
E/HomeCloudIF( 2687): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2687): [SmartShareManagerClient] unbindService context:android.app.Application@34eca008
V/CloudHub( 2687): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2687): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2687): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2687): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2687): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/Babel   ( 7357): deleted: false for 0
I/CloudHub( 2687): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29993
I/art     ( 7357): CheckpointMarkThreadRoots callback created = 0xb002d8e0
,I/art     ( 7357): CheckpointMarkThreadRoots callback created = 0xb002d8c0
,I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7392 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  964): Killing 7072:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10089/pid_7072/cgroup.procs: No such file or directory
,W/AudioCapabilities( 7357): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7357): Unsupported mime audio/adpcm
W/AudioCapabilities( 7357): Unsupported mime audio/g726
W/AudioCapabilities( 7357): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7357): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7357): Unsupported mime video/mjpg
,W/VideoCapabilities( 7357): Unsupported mime video/theora
W/AudioCapabilities( 7357): Unsupported mime audio/evrc
,W/AudioCapabilities( 7357): Unsupported mime audio/qcelp
W/VideoCapabilities( 7357): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7357): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7357): Unsupported mime audio/qcelp
W/AudioCapabilities( 7357): Unsupported mime audio/evrc
W/VideoCapabilities( 7357): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7357): Unsupported profile 4 for video/mp4v-es
,I/ThermalEngine(  286): Sensor:pa_therm0:33000 mC
W/VideoCapabilities( 7357): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7357): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7357): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7357): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7357): onServiceConnected
W/Babel   ( 7357): Attempted to change video mute state without an active call.
I/NotificationManager( 7357): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7357): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7357): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7357): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7357): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  268): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out( 7357): propertyValue:false
I/Babel   ( 7357): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  964): Killing 7145:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  964): failed to open /acct/uid_10048/pid_7145/cgroup.procs: No such file or directory
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7392): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7392): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7392): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7392): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7392): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7392):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7392):   adb logcat -s GAv4
W/GAv4    ( 7392): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7392): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7392): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7392): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7392): Time to load native libraries: 5 ms (timestamps 9279-9284)
I/LibraryLoader( 7392): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7392): Binding Chromium to main looper Looper (main, tid 1) {1aaf7680}
I/LibraryLoader( 7392): Expected native library version number "",actual native library version number ""
I/chromium( 7392): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7392): Initializing chromium process, singleProcess=true
W/art     ( 7392): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7392): ApplicationContext is null in ApplicationStatus
W/chromium( 7392): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7392): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7392): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7392): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7392): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7392): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7392): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7392): Remote Branch: 
I/Adreno-EGL( 7392): Local Patches: 
I/Adreno-EGL( 7392): Reconstruct Branch: 
I/art     (  964): Explicit concurrent mark sweep GC freed 16568(797KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.015ms total 166.044ms
,V/AudioPolicyService(  273): registerClient() client 0xb4027060, uid 10079
,W/AudioManagerAndroid( 7392): Requires BLUETOOTH permission
I/NSApplication( 7392): Starting up...
,I/CheckinRequestBuilder( 2270): Classify the device as Phone.
I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7471 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  964): Killing 7164:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10086/pid_7164/cgroup.procs: No such file or directory
,D/libc-netbsd( 2270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 2270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  268): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
,I/System.out( 2270): propertyValue:false
D/libc-netbsd( 2270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 2270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  964): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7493 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  964): Killing 7199:com.google.android.music:main/u0a81 (adj 15): empty #11
D/libc-netbsd( 2270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 2270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/libprocessgroup(  964): failed to open /acct/uid_10081/pid_7199/cgroup.procs: No such file or directory
,I/CheckinTask( 2270): Sending checkin request (9905 bytes)
W/ResourcesManager( 7493): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  964): Killing 7230:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10021/pid_7230/cgroup.procs: No such file or directory
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-52 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:15.018 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/CheckinService( 2270): Checkin interval check for package: unspecified last checkin: 1449756633209 min interval config: 0 actual interval: 41821
,I/ActivityManager(  964): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7523 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinRequestBuilder( 2270): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 2270): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 6259): Explicit concurrent mark sweep GC freed 1714(73KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 388us total 48.068ms
,I/MusicStore( 7523): Database version: 120
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7523): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/CheckinRequestBuilder( 2270): Classify the device as Phone.
,I/CheckinTask( 2270): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2270): Checking schedule, now: 1449756675355 next: 1450283924351
I/CheckinService( 2270): active receiver: disabled
,I/CheckinService( 2270): Checking schedule, now: 1449756675398 next: 1450283924351
I/CheckinService( 2270): active receiver: disabled
,D/CheckinService( 2270): Recording last checkin time for package unspecified as 1449756675409
,I/ActivityManager(  964): Killing 7258:com.lge.lgdmsclient/1000 (adj 15): empty #11
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7523): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7523): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/libprocessgroup(  964): failed to open /acct/uid_1000/pid_7258/cgroup.procs: No such file or directory
,W/ResourcesManager( 7523): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7523): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7523): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7523): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7523): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3586f16b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7523): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7523): GMSCore installation verified
I/ConfigStore( 7523): Config Database version: 1
,I/MediaRouter( 7523): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7523): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7523): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  964): Killing 7282:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10011/pid_7282/cgroup.procs: No such file or directory
,I/NetworkMonitor( 7523): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  964): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7563 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7523): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7523): Using platform SSLCertificateSocketFactory
I/ActivityManager(  964): Killing 7301:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/ResourcesManager( 7563): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7563): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7563): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  964): failed to open /acct/uid_10038/pid_7301/cgroup.procs: No such file or directory
,I/LGEmail ( 7563): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/NotificationManager( 7523): com.google.android.music: cancel(1061) by com.google.android.music
D/LGEmail ( 7563): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{3e220b4 type 2 when 121056 android} when 121056
,D/eas_req ( 7563): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  964): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7595 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7563): JNI_OnLoad()
I/HubEmail( 7563): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7563): registerNatives()
I/HubEmail( 7563): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7563): registerNativeMethods()
I/HubEmail( 7563): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7563): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  964): Killing 7326:com.lge.drmservice/u0a51 (adj 15): empty #11
I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 476us total 26.845ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 23.733ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.385ms
,W/libprocessgroup(  964): failed to open /acct/uid_10051/pid_7326/cgroup.procs: No such file or directory
W/Settings( 7563): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7595): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7595): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7595): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7595): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7595): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7595): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7595): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7595): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  964): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7623 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7595): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7595): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7595): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7595): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7595): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7595): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  964): Killing 2687:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  273): 2687 died, releasing its sessions
V/AudioFlinger(  273):  pid 1751 @ 0
V/AudioFlinger(  273):  pid 3169 @ 1
V/AudioFlinger(  273):  pid 3169 @ 2
,W/libprocessgroup(  964): failed to open /acct/uid_10028/pid_2687/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7623): onCreate
,W/AppUp4:DB( 7623):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7623):  setFingerPrint start
I/AppUp4:DB( 7623):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7623):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7623):  SDK version = 0
I/AppUp4:DB( 7623):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7623): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7623): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7623): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7623): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7623): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7623): onReceive
I/AppUp4:CustModeStarterReceiver( 7623): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7623): Context : android.app.ReceiverRestrictedContext@2e360c9f
,D/AppUp4:CustFacade( 7623): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7623): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7623): begin check event
I/AppUp4:CustModeStarterReceiver( 7623): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7623): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7623): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7623): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 7623): handleAsyncCustNotification do not startCustService
I/ActivityManager(  964): Killing 7357:com.google.android.talk/u0a61 (adj 15): empty #11
I/LgeMiscReceiver( 3169): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3169): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3169): networkInfo.isConnected() = true
W/libprocessgroup(  964): failed to open /acct/uid_10061/pid_7357/cgroup.procs: No such file or directory
D/PhoneState( 3169): setPdpRejectCasuse : false
I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7642 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7642): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7642): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7642): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  964): Killing 7392:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
D/PhoneMonitor( 7642): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7642): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7642): [parse] Load xml
,V/TelephonyAutoProfiling( 7642): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7642): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 7642): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,W/libprocessgroup(  964): failed to open /acct/uid_10079/pid_7392/cgroup.procs: No such file or directory
V/DownloadManager( 3217): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3217): DownloadService onCreate
I/NotificationManager( 3217): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3217): in removeSpuriousFiles
V/DownloadManager( 3217): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3217): created cursor android.database.sqlite.SQLiteCursor@25e629bd on behalf of 3217
I/DownloadManager( 3217): in trimDatabase
V/DownloadManager( 3217): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3217): created cursor android.database.sqlite.SQLiteCursor@37f8e703 on behalf of 3217
,I/ActivityManager(  964): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7667 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3217): DownloadService onStartCommand
I/CheckinService( 2270): Checkin interval check for package: unspecified last checkin: 1449756675409 min interval config: 0 actual interval: 1482
V/DownloadManager( 3217): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3217): created cursor android.database.sqlite.SQLiteCursor@39d0a4b9 on behalf of 3217
,I/CheckinService( 2270): Checking schedule, now: 1449756676921 next: 1449756705351
I/CheckinService( 2270): active receiver: disabled
V/DownloadManager( 3217): DownloadService onDestroy
,I/ActivityManager(  964): Killing 7471:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10048/pid_7471/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2665): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:17
D/UpdateThreadPoolManager( 2665): 2 : This is isUpdating : false
D/WeatherAncestor( 2665): connectivity changed - connection : true
D/Weather_cast( 2665): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2665): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:17
D/WeatherService( 2665): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7695 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  964): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2665): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2665): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2665): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7695): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ProcessCpuTracker(  964): Skipping unknown process pid 7689
,W/ProcessCpuTracker(  964): Skipping unknown process pid 7692
,I/[SystemUI]QPairHandler( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
I/art     ( 7695): CheckpointMarkThreadRoots callback created = 0xb002d380
,I/art     ( 7695): CheckpointMarkThreadRoots callback created = 0xb002d350
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/art     (  964): Explicit concurrent mark sweep GC freed 16734(849KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.862ms total 246.387ms
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  964): Handling package changes for user 0
,I/Babel_SMS( 7695): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7695): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7695): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/Babel_SMS( 7695): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7695): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7695): MmsConfig.loadFromResources
E/Babel_SMS( 7695): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7695): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7695): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7695): found sensor: LGE Magnetometer Sensor, handle=10
,D/SensorManager( 7695): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7695): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7695): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7695): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7695): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7695): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7695): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7695): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7695): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7695): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7695): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7695): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7695): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7695): found sensor: Motion Accel, handle=46
W/Settings( 7695): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7695): startup - clean
I/Babel   ( 7695): deleted: false for 0
,I/NotificationService(  964): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  964): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  964): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7732 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/BackupManagerService(  964): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  964): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/AudioCapabilities( 7695): Unsupported mime audio/x-lg-flac
V/BackupManagerService(  964): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@ad0e096
W/AudioCapabilities( 7695): Unsupported mime audio/adpcm
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
W/AudioCapabilities( 7695): Unsupported mime audio/g726
W/AudioCapabilities( 7695): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 7695): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7695): Unsupported mime video/mjpg
W/ResourcesManager(  964): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/VideoCapabilities( 7695): Unsupported mime video/theora
W/AudioCapabilities( 7695): Unsupported mime audio/evrc
W/AudioCapabilities( 7695): Unsupported mime audio/qcelp
W/VideoCapabilities( 7695): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7695): Unsupported mime audio/amr-wb-plus
I/ActivityManager(  964): Process com.google.android.music:main (pid 7523) has died
W/AudioCapabilities( 7695): Unsupported mime audio/qcelp
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:18.066 DNS addrs= 192.168.1.1, 0.0.0.0, 
W/AudioCapabilities( 7695): Unsupported mime audio/evrc
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/VideoCapabilities( 7695): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7695): Unsupported profile 4 for video/mp4v-es
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourceType(  964): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/VideoCapabilities( 7695): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7695): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7695): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7695): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7695): onServiceConnected
W/Babel   ( 7695): Attempted to change video mute state without an active call.
I/NotificationManager( 7695): com.google.android.talk: cancel(10436) by com.google.android.talk
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7732): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
D/libc-netbsd( 7695): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7695): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7695): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7695): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  268): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out( 7695): propertyValue:false
I/GAv4    ( 7732): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7732):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7732):   adb logcat -s GAv4
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7732): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7732): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/GAv4    ( 7732): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7732): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/Babel   ( 7695): connection state changed from UNKNOWN to CONNECTED
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/GAv4    ( 7732): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7732): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/LocationProviderProxy(  964): applying state to connected service
,I/WebViewFactory( 7732): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7732): Time to load native libraries: 2 ms (timestamps 3446-3448)
I/LibraryLoader( 7732): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7732): Binding Chromium to main looper Looper (main, tid 1) {1aaf7680}
I/LibraryLoader( 7732): Expected native library version number "",actual native library version number ""
I/chromium( 7732): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7732): Initializing chromium process, singleProcess=true
,W/art     ( 7732): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7732): ApplicationContext is null in ApplicationStatus
W/chromium( 7732): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7732): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7732): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7732): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7732): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7732): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7732): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7732): Remote Branch: 
I/Adreno-EGL( 7732): Local Patches: 
I/Adreno-EGL( 7732): Reconstruct Branch: 
V/AudioPolicyService(  273): registerClient() client 0xb40271c0, uid 10079
,W/AudioManagerAndroid( 7732): Requires BLUETOOTH permission
I/NSApplication( 7732): Starting up...
,I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7799 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  964): Killing 7493:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/ThermalEngine(  286): Sensor:pa_therm0:33000 mC
,W/libprocessgroup(  964): failed to open /acct/uid_10086/pid_7493/cgroup.procs: No such file or directory
,I/ActivityManager(  964): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7822 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  964): Killing 7563:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  964): failed to open /acct/uid_10021/pid_7563/cgroup.procs: No such file or directory
,W/ResourcesManager( 7822): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  964): Killing 7595:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_1000/pid_7595/cgroup.procs: No such file or directory
,D/WearableService( 1732): callingUid 10006, callindPid: 1732
,D/LocationInitializer( 2270): Restart initialization of location
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
E/MDM     ( 1732): [153] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/ActivityManager(  964): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7854 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,W/ResourcesManager( 7854): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  964): Message: 20
D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19a76a48:true
,D/BluetoothAdapterService(774035530)( 1996): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1b0362f0
D/BluetoothAdapterService(774035530)( 1996): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1b0362f0
W/ContextImpl( 3585): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager(  964): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7887 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7854): Create singleton instance
,D/UEI.SmartControl( 7887): Quickset Services start...
,I/AudioManager( 7854): getMode name:com.lge.qremote
I/UEI.SmartControl( 7887): Manufacture = LGE
D/UEI.SmartControl( 7887): File observer start...
E/UEI.SmartControl( 7887): IR Port is disabled: false
D/UEI.SmartControl( 7887): Starting file observer...
D/UEI.SmartControl( 7887): Extracting JNI libs...
D/UEI.SmartControl( 7887): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7887): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7887): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 7887): --- Extracting JNI libs: libqs_armeabi-v7a.zip
V/SetupWizard( 7642): Connected to Gservices successfully
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/UEI.SmartControl( 7887): --- Selecting new region: 2
I/UEI.SmartControl( 7887): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7887): Platform has CIR...
D/UEI.SmartControl( 7887): NO CIR support, need to check package...
I/UEI.SmartControl( 7887): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7887): QS Service created
I/AppUp4:CustModeStarterReceiver( 7623): onReceive
I/AppUp4:CustModeStarterReceiver( 7623): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7623): Context : android.app.ReceiverRestrictedContext@2e360c9f
D/AppUp4:CustFacade( 7623): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7623): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7623): begin check event
I/AppUp4:CustModeStarterReceiver( 7623): Event For Nothing, skip.
E/UEI.SmartControl( 7887): QS start get config
D/UEI.SmartControl( 7887): Loading JNI Libs...
,D/UEI.SmartControl( 7887):  configuring local db...
I/ActivityManager(  964): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7914 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/NotificationManager( 7695): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7695): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7695): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7695): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 7914): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7914): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7914): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/System  ( 7695): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7695): Installed default security provider GmsCore_OpenSSL
I/AppConfig( 7914): Total System Memory = 906309632
,I/GalleryUtils( 7914): Application Heap = 96 MB
,I/AppConfig( 7914): App Tier : NOT_DEF
D/SystemHelper( 7914): region [EU], country [EU], operator [OPEN], sub-operator []
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/UEI.SmartControl( 7887):  ---- Has DB8: true
,D/UEI.SmartControl( 7887): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7887): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7887): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7887): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7887): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7887): IrrcClient ++ 
D/irrcClient( 7887): getIrrcService ++ 
D/irrcClient( 7887): getIrrcService -- 
D/irrcClient( 7887): IrrcClient -- 
W/irrc_jni( 7887): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7887): Services init done
,I/ActivityManager(  964): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7936 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/UEI.SmartControl( 7887): Device manager: loading config....
I/art     (  301): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 22.208ms
,D/UEI.SmartControl( 7887): QS Service init finished
D/UEI.SmartControl( 7887): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7887): QS Service version code: 1073
D/UEI.SmartControl( 7887): Config is loaded...
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 21.805ms
D/UEI.SmartControl( 7887): Service requested: Control
,D/UEI.SmartControl( 7887): Internal service binding...
D/UEI.SmartControl( 7887): -----IControl: 11
D/UEI.SmartControl( 7887): Caller: com.lge.qremote
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 21.054ms
D/UEI.SmartControl( 7887): ------------ IControl registerCallback...
,I/UEI.SmartControl( 7887): Registering callback...
D/UEI.SmartControl( 7887): -----IControl: 19
D/UEI.SmartControl( 7887): Caller: com.lge.qremote
I/UEI.SmartControl( 7887): Registering Services Ready callback...
I/UEI.SmartControl( 7887): Notify client services are ready...
D/UEI.SmartControl( 7887): -----IControl: 8
,D/UEI.SmartControl( 7887): Caller: com.lge.qremote
I/ActivityManager(  964): Killing 7667:com.lge.drmservice/u0a51 (adj 15): empty #11
D/UEI.SmartControl( 7887):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7887): Notify AllClients services are ready: 0
W/ResourcesManager( 7936): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7936): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7936): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7936): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7936): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  964): failed to open /acct/uid_10051/pid_7667/cgroup.procs: No such file or directory
,I/SystemConfig( 7936): BUILD Country: EU
I/SystemConfig( 7936): BUILD Operator: OPEN
,I/ActivityManager(  964): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7964 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  964): Killing 7732:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10079/pid_7732/cgroup.procs: No such file or directory
,I/SystemConfig( 7936): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7936): existFile = false
I/SystemConfig( 7936): canReadFile = false
,I/SystemConfig( 7936): systemFeature RCS result false
D/SystemConfig( 7936): refreshRcsSupport() :false
I/LockScreenSettings( 7964): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7964): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7964): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7964): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7964): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7964): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/UpdateIcingCorporaServi( 1942): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  964): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7985 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  964): Killing 7799:com.android.chrome/u0a48 (adj 15): empty #11
,I/art     ( 7822): CheckpointMarkThreadRoots callback created = 0xb002d5f0
,I/UpdateIcingCorporaServi( 1942): UpdateCorporaTask done [took 111 ms] updated apps [took 111 ms] 
,I/art     ( 7822): CheckpointMarkThreadRoots callback created = 0xb002d5d0
,W/libprocessgroup(  964): failed to open /acct/uid_10048/pid_7799/cgroup.procs: No such file or directory
D/Finsky  ( 7985): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/Finsky  ( 7985): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7985): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7985): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7985): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3217): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3217): created cursor android.database.sqlite.SQLiteCursor@3c98f05f on behalf of 7985
D/Ads     ( 7985): Skipping gmscore version check
,D/Finsky  ( 7985): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7985): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 7985): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7985): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/art     (  964): Explicit concurrent mark sweep GC freed 28466(1371KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.194ms total 157.588ms
,I/ActivityManager(  964): Killing 7054:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  964): failed to open /acct/uid_10006/pid_7054/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 2270): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/AudioManager( 7854): getMode name:com.lge.qremote
I/PackageBroadcastService( 2270): Null package name or gms related package.  Ignoreing.
I/AudioManager( 7854): getMode name:com.lge.qremote
,I/Icing   ( 2270): updateResources: need to parse f{com.google.android.gms}
,I/AudioManager( 7854): getMode name:com.lge.qremote
,I/AudioManager( 7854): getMode name:com.lge.qremote
,D/charger_monitor(  490): init target 500000
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
,D/charger_monitor(  490): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 300, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,I/Icing   ( 2270): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 2270): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ThermalEngine(  286): Sensor:pa_therm0:33000 mC
,I/ActivityManager(  964): Killing 7642:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10038/pid_7642/cgroup.procs: No such file or directory
,I/ActivityManager(  964): Killing 7623:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10011/pid_7623/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7887): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  286): Sensor:pa_therm0:33000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 134719164641; DSPS: 4506700; Offset : -2823068416
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  286): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  286): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  286): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  964): ALS enabled for SRE
D/PowerManagerServiceEx(  964): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29445 ms ago)
,D/qdlights(  964): set_light_backlight: 253
,D/qdlights(  964): set_light_backlight: 250
,D/qdlights(  964): set_light_backlight: 246
,D/qdlights(  964): set_light_backlight: 243
,D/qdlights(  964): set_light_backlight: 240
,D/qdlights(  964): set_light_backlight: 237
,D/qdlights(  964): set_light_backlight: 233
,D/qdlights(  964): set_light_backlight: 230
,D/qdlights(  964): set_light_backlight: 227
,D/qdlights(  964): set_light_backlight: 223
,D/qdlights(  964): set_light_backlight: 220
,D/qdlights(  964): set_light_backlight: 217
,D/qdlights(  964): set_light_backlight: 213
,D/qdlights(  964): set_light_backlight: 210
,D/qdlights(  964): set_light_backlight: 207
,D/qdlights(  964): set_light_backlight: 203
,D/qdlights(  964): set_light_backlight: 200
,D/qdlights(  964): set_light_backlight: 197
,D/qdlights(  964): set_light_backlight: 193
,D/qdlights(  964): set_light_backlight: 190
,D/qdlights(  964): set_light_backlight: 187
,D/qdlights(  964): set_light_backlight: 183
,D/qdlights(  964): set_light_backlight: 180
,D/qdlights(  964): set_light_backlight: 177
,D/qdlights(  964): set_light_backlight: 173
,D/qdlights(  964): set_light_backlight: 170
,D/qdlights(  964): set_light_backlight: 167
,D/qdlights(  964): set_light_backlight: 163
,D/qdlights(  964): set_light_backlight: 160
,D/qdlights(  964): set_light_backlight: 157
,D/qdlights(  964): set_light_backlight: 153
,D/qdlights(  964): set_light_backlight: 150
,D/qdlights(  964): set_light_backlight: 147
,D/qdlights(  964): set_light_backlight: 143
,D/qdlights(  964): set_light_backlight: 140
,D/qdlights(  964): set_light_backlight: 137
,D/qdlights(  964): set_light_backlight: 133
,D/qdlights(  964): set_light_backlight: 130
,D/qdlights(  964): set_light_backlight: 127
,D/qdlights(  964): set_light_backlight: 123
,D/qdlights(  964): set_light_backlight: 120
,D/qdlights(  964): set_light_backlight: 117
,D/qdlights(  964): set_light_backlight: 113
,D/qdlights(  964): set_light_backlight: 110
,D/qdlights(  964): set_light_backlight: 107
,D/qdlights(  964): set_light_backlight: 103
,D/qdlights(  964): set_light_backlight: 100
,D/qdlights(  964): set_light_backlight: 97
,D/qdlights(  964): set_light_backlight: 93
,D/qdlights(  964): set_light_backlight: 90
,D/qdlights(  964): set_light_backlight: 87
,D/qdlights(  964): set_light_backlight: 83
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{209249f9 type 2 when 140125 com.google.android.gms} when 140125
V/AlarmManager(  964): RTC_WAKEUP set : Alarm{20698d3e type 0 when 1449756705351 com.google.android.gms} when 1449756705351
D/qdlights(  964): set_light_backlight: 80
,D/qdlights(  964): set_light_backlight: 77
,D/qdlights(  964): set_light_backlight: 73
,I/CheckinService( 2270): Checkin interval check for package: unspecified last checkin: 1449756675409 min interval config: 0 actual interval: 29995
D/qdlights(  964): set_light_backlight: 70
,I/CheckinService( 2270): Checking schedule, now: 1449756705419 next: 1449756705351
I/CheckinService( 2270): active receiver: enabled
,D/qdlights(  964): set_light_backlight: 67
I/CheckinService( 2270): Preparing to send checkin request
I/EventLogService( 2270): Accumulating logs since 1449756667418
D/qdlights(  964): set_light_backlight: 63
,D/qdlights(  964): set_light_backlight: 60
,D/qdlights(  964): set_light_backlight: 57
,I/CheckinRequestBuilder( 2270): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 2270): Failed to find provider info for com.google.android.wearable.settings
D/qdlights(  964): set_light_backlight: 53
,D/qdlights(  964): set_light_backlight: 50
,D/qdlights(  964): set_light_backlight: 47
,D/qdlights(  964): set_light_backlight: 43
,I/ActivityManager(  964): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=8104 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/qdlights(  964): set_light_backlight: 40
D/qdlights(  964): set_light_backlight: 37
,D/qdlights(  964): set_light_backlight: 33
,D/qdlights(  964): set_light_backlight: 30
D/qdlights(  964): set_light_backlight: 27
,D/qdlights(  964): set_light_backlight: 23
,D/qdlights(  964): set_light_backlight: 20
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/qdlights(  964): set_light_backlight: 17
D/qdlights(  964): set_light_backlight: 13
,D/qdlights(  964): set_light_backlight: 10
,I/ActivityManager(  964): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8123 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 8104): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8104): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8104): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 8123): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8123): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/System  ( 8104): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8104): Installed default security provider GmsCore_OpenSSL
I/MultiDex( 8123): VM with version 2.1.0 has multidex support
I/MultiDex( 8123): install
I/MultiDex( 8123): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8123): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8123): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8123): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1bbb1950: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8123): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 8123): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 8123): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,E/MDM     ( 1732): [104] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 2270): Restart initialization of location
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,I/art     ( 8123): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8123): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8104): CheckpointMarkThreadRoots callback created = 0xb002da30
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/art     ( 8104): CheckpointMarkThreadRoots callback created = 0xb4958de0
,E/YouTube MDX( 8104): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
W/ResourcesManager( 8104): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8104): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/libc-netbsd( 8104): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8104): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/NativeLibraryUtils( 8123): Install completed successfully. count=14 extracted=0
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8104): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,D/WVCdm   (  273): Instantiating CDM.
,I/WVCdm   (  273): CdmEngine::OpenSession
I/WVCdm   (  273): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  273): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  273): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  273): L1 library not specified. Falling Back to L3
I/dex2oat ( 8171): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads382618169.jar --oat-fd=34 --oat-location=/data/data/com.google.android.youtube/cache/ads382618169.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/WVCdm   (  273): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  273): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  273): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  273): CdmEngine::GenerateKeyRequest
D/WVCdm   (  273): PrepareKeyRequest: nonce=4133227097
,I/dex2oat ( 8171): dex2oat took 115.609ms (threads: 4)
,I/NotificationManager( 8104): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8104): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8104): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8104): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 8104): Found 10006
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8104): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/art     ( 8123): CheckpointMarkThreadRoots callback created = 0xb00d3ec0
,I/art     ( 8123): CheckpointMarkThreadRoots callback created = 0xb00d3ea0
,I/art     ( 8123): Background partial concurrent mark sweep GC freed 16945(1009KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 10MB/17MB, paused 5.262ms total 71.839ms
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 8104): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,D/libc-netbsd( 8104): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8104): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 8104): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8104): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  268): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
,I/System.out( 8104): propertyValue:false
D/libc-netbsd( 8104): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8104): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/VacuumService( 1732): Vacuum at: now=1449756707057 tag=VacuumService
,D/libc-netbsd( 8104): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 8104): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/dex2oat ( 8220): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8220): dex2oat took 63.227ms (threads: 4)
,I/Adreno-EGL( 8123): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8123): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 8123): Build Date: 03/02/15 Mon
I/Adreno-EGL( 8123): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 8123): Remote Branch: 
I/Adreno-EGL( 8123): Local Patches: 
I/Adreno-EGL( 8123): Reconstruct Branch: 
,I/Adreno-EGL( 8123): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8123): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 8123): Build Date: 03/02/15 Mon
I/Adreno-EGL( 8123): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 8123): Remote Branch: 
I/Adreno-EGL( 8123): Local Patches: 
I/Adreno-EGL( 8123): Reconstruct Branch: 
,I/Adreno-EGL( 8123): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8123): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 8123): Build Date: 03/02/15 Mon
I/Adreno-EGL( 8123): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 8123): Remote Branch: 
I/Adreno-EGL( 8123): Local Patches: 
I/Adreno-EGL( 8123): Reconstruct Branch: 
D/libc-netbsd( 8104): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8104): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 8104): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8104): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  268): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
,I/System.out( 8104): propertyValue:false
D/libc-netbsd( 8104): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8104): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/WVCdm   (  273): CdmEngine::OpenSession
,D/libc-netbsd( 8104): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8104): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/PhenotypeConfigurator( 1732): Scheduling Phenotype for one-off execution 2303 seconds from now (1449756708105)
,D/GetConfigurationSnapshotOperation( 1732): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1732): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1732): Using platform SSLCertificateSocketFactory
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:48.196 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  268): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
,I/System.out( 1732): propertyValue:false
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/WVCdm   (  273): CdmEngine::CloseSession
,I/WVCdm   (  273): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  273): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  273): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  273): CdmEngine::GenerateKeyRequest
D/WVCdm   (  273): PrepareKeyRequest: nonce=3812717284
I/ThermalEngine(  286): Sensor:pa_therm0:33000 mC
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 154719937862; DSPS: 5162085; Offset : -2823058083
,I/WVCdm   (  273): CdmEngine::CloseSession
,I/WVCdm   (  273): L3 Terminate.
,I/CheckinRequestBuilder( 2270): Classify the device as Phone.
,D/libc-netbsd( 2270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 2270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  268): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out( 2270): propertyValue:false
D/libc-netbsd( 2270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 2270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 2270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:51.203 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinTask( 2270): Sending checkin request (9904 bytes)
I/PowerManagerService(  964): ALS enabled for SRE
D/PowerManagerServiceEx(  964): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36446 ms ago)
,I/PowerManagerService(  964): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  964): ALS enabled for SRE
D/PowerManagerServiceEx(  964): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36474 ms ago)
W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  964): Sleeping (uid 1000)...
D/LPWGController(  964): [updateScreenState] screen on = false
D/LPWGController(  964): disable proximity sensor
,D/LPWGController(  964): enable proximity sensor
I/SensorManager(  964): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@35645ba] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  964): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  964): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  964): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  964): activate: handle is 48, enable
,V/sensors_hal_Ctx(  964): activate sensors is 1400000000000
D/sensors_hal_Thresh(  964): enable: handle=48
I/sensors_hal_SAM(  964): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  964): waitForResponse: timeout=1000
V/sensors_hal_SAM(  964): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  964): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
,D/sensors_hal_Thresh(  964): enable: Received response: 0
D/PowerManagerServiceEx(  964): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36552 ms ago)
I/Adreno-EGL(  964): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  964): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  964): Build Date: 03/02/15 Mon
I/Adreno-EGL(  964): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  964): Remote Branch: 
I/Adreno-EGL(  964): Local Patches: 
I/Adreno-EGL(  964): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (977 us)
,I/CheckinRequestBuilder( 2270): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 2270): Failed to find provider info for com.google.android.wearable.settings
,I/Sensors (  429): sns_pwr.c(273):acquiring wakelock
V/sensors_hal_SAM(  964): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,I/sensors_hal_SAM(  964): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  964): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  964): processInd: handle 48, count=1
V/sensors_hal_Thresh(  964): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  964): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  964): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  964): poll: count: 256
I/sensors_hal_Ctx(  964): poll: released wakelock sensor_ind
D/sensors_hal_Util(  964): waitForResponse: timeout=0
D/LPWGController(  964): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  964): current mode = 1  value = 1 1
I/LPWGController(  964): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  964): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/art     (  964): Explicit concurrent mark sweep GC freed 39624(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/34MB, paused 2.318ms total 181.217ms
,I/CheckinRequestBuilder( 2270): Classify the device as Phone.
,I/CheckinTask( 2270): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2270): Checking schedule, now: 1449756712071 next: 1450283961062
I/CheckinService( 2270): active receiver: disabled
,D/CheckinService( 2270): Recording last checkin time for package unspecified as 1449756712104
,D/qdlights(  964): set_light_backlight: 0
,I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8280 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/SensorManager(  964): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  964): activate: handle is 46, disable
V/sensors_hal_Ctx(  964): activate sensors is 1000000000000
D/sensors_hal_LP2(  964): enable: handle=46
D/sensors_hal_LP2(  964): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  964): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
I/ActivityManager(  964): Killing 7914:com.android.gallery3d/u0a23 (adj 15): empty #11
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
I/DisplayManagerService(  964): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  964): Display changed displayId=0
V/sensors_hal_SAM(  964): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  964): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,I/ActivityManager(  964): Killing 7695:com.google.android.talk/u0a61 (adj 15): empty #12
,D/DSDPConnection( 1751): Display #0 changed.
W/libprocessgroup(  964): failed to open /acct/uid_10023/pid_7914/cgroup.procs: No such file or directory
,W/libprocessgroup(  964): failed to open /acct/uid_10061/pid_7695/cgroup.procs: No such file or directory
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
D/SurfaceControl(  964): Excessive delay in setPowerMode(): 172ms
,I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  964): Got set_interactive hint
D/KeyguardViewMediator( 1371): onScreenTurnedOff(3)
,D/PhoneMonitor( 8280): Register our PhoneStateListener
D/SmartCoverViewMediator( 1330): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1371): notifyScreenOffLocked
D/SmartCoverViewMediator( 1330): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1330): handleNotifyScreenOFF
D/WifiServerServiceExt(  964): sendKtScanInterval  mRtspPlay : false
,D/KeyguardViewMediator( 1371): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1371): handleNotifyScreenOff
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 15:11:52.416 DNS addrs= 192.168.1.1, 0.0.0.0, 
V/SetupWizard( 8280): Connected to Gservices successfully
,V/AudioFlinger(  273): setParameters(): io 0, keyvalue screen_state=on, calling pid 964
D/audio_hw_primary(  273): adev_set_parameters: enter: screen_state=on
,V/voice   (  273): voice_set_parameters: enter: screen_state=on
V/compress_voip(  273): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  273): voice_extn_compress_voip_set_parameters: exit
V/voice   (  273): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  273): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  273): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  273): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  273): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  273): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  273): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  273): adev_set_parameters: exit with code(0)
I/WifiServerServiceExt(  964): set CMD_KT_SCAN_INTERVAL
D/ScreenTurnOffBySensor( 1371): unregisterProximitySensor
I/ActivityManager(  964): Killing 7936:com.android.contacts/u0a18 (adj 15): empty #11
,D/StatusBarWindowView( 1371): onScreenTurnedOff why = 3
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PhoneMonitor( 8280): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 8280): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 8280): [parse] Load xml
V/TelephonyAutoProfiling( 8280): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 8280): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 8280): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
W/libprocessgroup(  964): failed to open /acct/uid_10018/pid_7936/cgroup.procs: No such file or directory
,D/GpsLocationProvider(  964): receive broadcast intent, action: android.intent.action.SCREEN_ON
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1839): |CORE| sendScreenState: state:true
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/LEDService( 1798): getCurrentHighestLGLedRecord() start. size = 1
,D/LNfcService( 1785): action : android.intent.action.SCREEN_ON
D/LEDService( 1798): stopPatternFlashing()
I/Cliptray Service( 1798): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1798): lockStatus = 0
D/NfcServiceNXP( 1785): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1785): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1785): isRequireNfcCRouting() return true
D/LNfcService( 1785): isHCERoutingtoHost() return : true
D/NfcService( 1785): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): newParams.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): screenState= 3
D/NfcService( 1785): Discovery configuration equal, not updating.
I/LEDService( 1798): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
I/LEDService( 1798): updateLightsLocked : turn off led
D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
,D/LEDHandler( 1798): RESTART MSG
D/SplitWindow(  964): check instance of lgWin Window{17eee699 u0 SearchPanel}
,D/InputDispatcher(  964): Window went away: Window{3945f876 u0 SearchPanel}
,I/[SystemUI]Clock( 1371): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1371): time changed, timezoneChanged : false
,D/Ulp_jni (  964): JNI:system_update. Event-0
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2665): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:11:52
,D/WeatherService( 2665): 2 : ACTION screen on
D/WeatherService( 2665): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2665): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherService( 2665): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:11:52
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_ON
D/AppCleanupService( 4174): android.intent.action.SCREEN_ON
,V/AudioFlinger(  273): setParameters(): io 0, keyvalue screen_state=off, calling pid 964
D/audio_hw_primary(  273): adev_set_parameters: enter: screen_state=off
V/voice   (  273): voice_set_parameters: enter: screen_state=off
V/compress_voip(  273): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  273): voice_extn_compress_voip_set_parameters: exit
V/voice   (  273): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  273): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  273): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  273): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  273): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  273): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  273): adev_set_parameters: exit with code(0)
D/WifiController(  964): CMD_SCREEN_OFF 
D/WifiController(  964): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  964): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:false
,I/LEDService( 1798): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1798): stopPatternFlashing()
D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
I/LEDService( 1798): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1798): clear
D/LNfcService( 1785): action : android.intent.action.SCREEN_OFF
I/Cliptray Service( 1798): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1798): updateLightsLocked : turn on led
E/LEDService( 1798): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1798): Can't handle this request of patternId:0
D/LEDHandler( 1798): RESTART MSG
D/NfcServiceNXP( 1785): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1877): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
D/WeatherService( 2665): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:11:52
D/WeatherService( 2665): 2 : ACTION screen off
,D/WeatherService( 2665): 2 : TimeTick Receiver Unregister
D/WeatherService( 2665): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:11:52
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_OFF
D/AppCleanupService( 4174): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4174): AppUsageStatsSaveTask
,E/NxpNfcJni( 1785): getReconnectState = 0x0
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
D/LNfcService( 1785): isRequireNfcCRouting() return true
D/LNfcService( 1785): isHCERoutingtoHost() return : true
D/NfcService( 1785): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): newParams.techmask= mTechMask: 0
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): screenState= 1
E/NxpNfcJni( 1785): getReconnectState = 0x0
,I/Sensors (  429): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  286): Sensor:pa_therm0:33000 mC
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8335 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 8335): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/administrator(  964): Handling package changes for user 0
,I/ActivityManager(  964): Process com.google.android.apps.plus (pid 7822) has died
,I/NotificationService(  964): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  964): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  964): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  964): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  964): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  964): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2cbd48f7
,I/Babel_SMS( 8335): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8335): MmsConfig.loadMmsSettings
W/ResourcesManager(  964): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Babel_SMS( 8335): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 8335): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8335): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8335): MmsConfig.loadFromResources
E/Babel_SMS( 8335): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8335): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 8335): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 8335): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 8335): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 8335): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 8335): found sensor: LGE Gravity Sensor, handle=29
,D/SensorManager( 8335): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 8335): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 8335): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 8335): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 8335): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 8335): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 8335): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 8335): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 8335): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 8335): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 8335): found sensor: Motion Accel, handle=46
,W/ResourceType(  964): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/Settings( 8335): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     ( 8335): CheckpointMarkThreadRoots callback created = 0xb002d8c0
,I/Babel_Crash( 8335): startup - clean
I/art     ( 8335): CheckpointMarkThreadRoots callback created = 0xb002d8a0
,I/Babel   ( 8335): deleted: false for 0
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/AudioCapabilities( 8335): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 8335): Unsupported mime audio/adpcm
W/AudioCapabilities( 8335): Unsupported mime audio/g726
W/AudioCapabilities( 8335): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 8335): Unsupported mime audio/wma-voice
W/VideoCapabilities( 8335): Unsupported mime video/mjpg
,W/VideoCapabilities( 8335): Unsupported mime video/theora
,I/ActivityManager(  964): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8382 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/LocationProviderProxy(  964): applying state to connected service
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 77582(4MB) AllocSpace objects, 35(560KB) LOS objects, 39% free, 14MB/24MB, paused 1.620ms total 138.260ms
,W/AudioCapabilities( 8335): Unsupported mime audio/evrc
,W/AudioCapabilities( 8335): Unsupported mime audio/qcelp
W/VideoCapabilities( 8335): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 8335): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 8335): Unsupported mime audio/qcelp
,W/AudioCapabilities( 8335): Unsupported mime audio/evrc
I/AppUp4:AppBoxCP( 8382): onCreate
W/AppUp4:DB( 8382):  [AppBoxDatabaseHelper] construct
,W/VideoCapabilities( 8335): Unsupported mime video/mp4v-esdp
,I/AppUp4:DB( 8382):  setFingerPrint start
I/AppUp4:DB( 8382):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 8382):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8382):  SDK version = 0
I/AppUp4:DB( 8382):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8382): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 8382): onReceive
I/AppUp4:CustModeStarterReceiver( 8382): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 8382): Context : android.app.ReceiverRestrictedContext@337a09c0
D/AppUp4:CustFacade( 8382): isCustomizationCompleted : false
I/VideoCapabilities( 8335): Unsupported profile 4 for video/mp4v-es
D/AppUp4:CustFacade( 8382): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 8382): begin check event
I/AppUp4:CustModeStarterReceiver( 8382): Event For Nothing, skip.
W/VideoCapabilities( 8335): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8335): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8335): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8335): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  964): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8401 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 8401): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8401): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8401): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/NotificationManager( 8335): com.google.android.talk: cancel(8) by com.google.android.talk
,I/vclib   ( 8335): onServiceConnected
W/Babel   ( 8335): Attempted to change video mute state without an active call.
W/ResourcesManager( 8335): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8335): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppConfig( 8401): Total System Memory = 906309632
,I/GalleryUtils( 8401): Application Heap = 96 MB
V/JNIHelp ( 8335): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AppConfig( 8401): App Tier : NOT_DEF
D/SystemHelper( 8401): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  964): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8423 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  964): Killing 7964:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/System  ( 8335): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8335): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  964): failed to open /acct/uid_10069/pid_7964/cgroup.procs: No such file or directory
,I/NotificationManager( 8335): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 8423): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8423): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8423): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 8423): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 8423): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 8423): BUILD Country: EU
I/SystemConfig( 8423): BUILD Operator: OPEN
,I/ActivityManager(  964): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8444 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  964): Killing 7985:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10036/pid_7985/cgroup.procs: No such file or directory
,I/SystemConfig( 8423): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 8423): existFile = false
I/SystemConfig( 8423): canReadFile = false
I/SystemConfig( 8423): systemFeature RCS result false
D/SystemConfig( 8423): refreshRcsSupport() :false
I/LockScreenSettings( 8444): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 8444): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 8444): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 8444): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 8444): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 8444): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,W/ProcessCpuTracker(  964): Skipping unknown process pid 8373
W/ProcessCpuTracker(  964): Skipping unknown process pid 8376
I/ActivityManager(  964): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8464 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  964): Killing 7887:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 23.699ms
,W/System.err( 7854): android.os.DeadObjectException
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.677ms
,W/System.err( 7854): 	at android.os.BinderProxy.transactNative(Native Method)
,W/System.err( 7854): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7854): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7854): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7854): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7854): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7854): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7854): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7854): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7854): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7854): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7854): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7854): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7854): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7854): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7854): android.os.DeadObjectException
W/System.err( 7854): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7854): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7854): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7854): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7854): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7854): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7854): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7854): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7854): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7854): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7854): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7854): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7854): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7854): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7854): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 30.907ms
,W/libprocessgroup(  964): failed to open /acct/uid_10089/pid_7887/cgroup.procs: No such file or directory
,W/ActivityManager(  964): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
W/ResourcesManager( 8464): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  964): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=8482 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{22536d63 type 2 when 162365 com.android.systemui} when 162365
D/UEI.SmartControl( 8482): Quickset Services start...
,I/UEI.SmartControl( 8482): Manufacture = LGE
D/UEI.SmartControl( 8482): File observer start...
E/UEI.SmartControl( 8482): IR Port is disabled: false
,D/UEI.SmartControl( 8482): Starting file observer...
D/UEI.SmartControl( 8482): Extracting JNI libs...
D/UEI.SmartControl( 8482): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 8482): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 8482): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8482): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 8482): --- Selecting new region: 2
I/UEI.SmartControl( 8482): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 8482): Platform has CIR...
D/UEI.SmartControl( 8482): NO CIR support, need to check package...
I/UEI.SmartControl( 8482): Model: LG-D722 uses JNI
D/UEI.SmartControl( 8482): QS Service created
I/UpdateIcingCorporaServi( 1942): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,E/UEI.SmartControl( 8482): QS start get config
,I/UpdateIcingCorporaServi( 1942): UpdateCorporaTask done [took 46 ms] updated apps [took 46 ms] 
,I/ActivityManager(  964): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8508 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  964): Killing 7854:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 8482): Loading JNI Libs...
,D/UEI.SmartControl( 8482):  configuring local db...
W/libprocessgroup(  964): failed to open /acct/uid_10106/pid_7854/cgroup.procs: No such file or directory
,D/Finsky  ( 8508): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 8482):  ---- Has DB8: true
D/UEI.SmartControl( 8482): QS start statue = true Error code = 0
,D/UEI.SmartControl( 8482): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 8482): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 8482): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 8482): IRRCPlayer_nativeInit ++ 
D/irrcClient( 8482): IrrcClient ++ 
D/irrcClient( 8482): getIrrcService ++ 
,D/irrcClient( 8482): getIrrcService -- 
D/irrcClient( 8482): IrrcClient -- 
W/irrc_jni( 8482): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 8482): Services init done
I/UEI.SmartControl( 8482): Device manager: loading config....
D/UEI.SmartControl( 8482): QS Service init finished
D/UEI.SmartControl( 8482): QS Service version name: 0.1.73
,D/UEI.SmartControl( 8482): QS Service version code: 1073
D/UEI.SmartControl( 8482): Service requested: Control
D/UEI.SmartControl( 8482): Config is loaded...
,D/UEI.SmartControl( 8482): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 8482): Service.onUnbind: IControl
D/UEI.SmartControl( 8482): Service.onDestroy
,D/UEI.SmartControl( 8482): Shutdown IRRCPlayer... 
D/UEI.SmartControl( 8482):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 8482): Notify AllClients services are ready: 0
W/irrc_jni( 8482): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 8482): ~IrrcClient ++ 
D/irrcClient( 8482): ~IrrcClient -- 
W/irrc_jni( 8482): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 8482): Blaster closed
D/UEI.SmartControl( 8482): Blaster closed
,D/UEI.SmartControl( 8482): Shut down QS...
,D/UEI.SmartControl( 8482): Stopped file observer...
I/UEI.SmartControl( 8482): QS lib stop result = true
D/UEI.SmartControl( 8482): QS shutdown complete
D/UEI.SmartControl( 8482): QS Service created
E/UEI.SmartControl( 8482): QS start get config
,D/UEI.SmartControl( 8482):  configuring local db...
D/Finsky  ( 8508): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8508): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8508): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 8508): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3217): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3217): created cursor android.database.sqlite.SQLiteCursor@2ed57aac on behalf of 8508
D/Finsky  ( 8508): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8508): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8508): Skipping gmscore version check
I/ActivityManager(  964): Killing 8104:com.google.android.youtube/u0a100 (adj 15): empty #11
D/UEI.SmartControl( 8482):  ---- Has DB8: true
,D/UEI.SmartControl( 8482): QS start statue = true Error code = 0
D/UEI.SmartControl( 8482): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 8482): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 8482): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 8482): IRRCPlayer_nativeInit ++ 
D/irrcClient( 8482): IrrcClient ++ 
D/irrcClient( 8482): getIrrcService ++ 
D/irrcClient( 8482): getIrrcService -- 
D/irrcClient( 8482): IrrcClient -- 
W/irrc_jni( 8482): IRRCPlayer_nativeInit -- 
W/libprocessgroup(  964): failed to open /acct/uid_10100/pid_8104/cgroup.procs: No such file or directory
D/UEI.SmartControl( 8482): Services init done
I/UEI.SmartControl( 8482): Device manager: loading config....
,D/Finsky  ( 8508): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 2270): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/UEI.SmartControl( 8482): Config is loaded...
D/UEI.SmartControl( 8482): QS Service init finished
D/UEI.SmartControl( 8482): QS Service version name: 0.1.73
D/UEI.SmartControl( 8482): QS Service version code: 1073
D/UEI.SmartControl( 8482): Service requested: Control
D/KeyguardViewMediator( 1371): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,I/PackageBroadcastService( 2270): Null package name or gms related package.  Ignoreing.
E/ActivityThread( 8482): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@2e22d84a that was originally bound here
E/ActivityThread( 8482): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@2e22d84a that was originally bound here
E/ActivityThread( 8482): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 8482): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 8482): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 8482): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 8482): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 8482): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 8482): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 8482): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 8482): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 8482): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 8482): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 8482): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 8482): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 8482): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 8482): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 8482): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 8482): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 8482): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,D/UEI.SmartControl( 8482):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 8482): Notify AllClients services are ready: 0
,D/Finsky  ( 8508): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 2270): updateResources: need to parse f{com.google.android.gms}
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
,V/TelecomServiceImpl( 1751): getCallState : 0
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
,D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1371): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1371): doKeyguard: not showing because lockscreen is off
,I/art     (  964): Explicit concurrent mark sweep GC freed 39337(1987KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/35MB, paused 2.247ms total 180.949ms
,D/UEI.SmartControl( 8482): Internal service binding...
I/ThermalEngine(  286): Sensor:pa_therm0:33000 mC
,D/UEI.SmartControl( 8482): Internal timer expired: 2
,W/System.err( 8482): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@2e22d84a
W/System.err( 8482): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 8482): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 8482): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 8482): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 8482): 	at com.uei.control.Service.a(Unknown Source)
W/System.err( 8482): 	at com.uei.control.l.run(Unknown Source)
W/System.err( 8482): 	at java.util.Timer$TimerImpl.run(Timer.java:284)
E/UEI.SmartControl( 8482): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@2e22d84a
I/Icing   ( 2270): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 2270): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  964): Killing 8280:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10038/pid_8280/cgroup.procs: No such file or directory
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ActivityManager(  964): Killing 8123:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10006/pid_8123/cgroup.procs: No such file or directory
,E/UEI.SmartControl( 8482): file observer is disposed!
,D/UEI.SmartControl( 8482): Internal timer expired: 3
,D/UEI.SmartControl( 8482): Service.onUnbind: IControl
D/UEI.SmartControl( 8482): Service.onDestroy
W/System.err( 8482): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@d56f097
W/System.err( 8482): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 8482): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 8482): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 8482): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 8482): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 8482): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 8482): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 8482): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 8482): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8482): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 8482): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 8482): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8482): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8482): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 8482): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 8482): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@d56f097
D/UEI.SmartControl( 8482): Shutdown IRRCPlayer... 
W/irrc_jni( 8482): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 8482): ~IrrcClient ++ 
D/irrcClient( 8482): ~IrrcClient -- 
W/irrc_jni( 8482): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 8482): Blaster closed
D/UEI.SmartControl( 8482): Blaster closed
D/UEI.SmartControl( 8482): Shut down QS...
I/UEI.SmartControl( 8482): QS lib stop result = true
D/UEI.SmartControl( 8482): QS shutdown complete
I/ThermalEngine(  286): Sensor:pa_therm0:33000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:33000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 174721581397; DSPS: 5817499; Offset : -2823062028
,I/ThermalEngine(  286): Sensor:pa_therm0:33000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:32000 mC
,D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 299, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 299
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 299
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
D/PowerManagerServiceEx(  964): acquireWakeLockInternal: lock=357792421, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{ed5c9a7 type 2 when 187780 com.google.android.gms} when 187780
D/PowerManagerServiceEx(  964): releaseWakeLockInternal: lock=357792421 [*alarm*], flags=0x0
,I/ThermalEngine(  286): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{12a1ee54 type 2 when 192261 android} when 192261
,I/ThermalEngine(  286): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 194722257483; DSPS: 6472881; Offset : -2823057251
,I/ClearcutLoggerApiImpl( 1732): disconnect managed GoogleApiClient
,I/ThermalEngine(  286): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 214722922006; DSPS: 7128263; Offset : -2823064323
,I/ThermalEngine(  286): Sensor:pa_therm0:32000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  286): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 234723591999; DSPS: 7783645; Offset : -2823065821
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 254724277824; DSPS: 8439028; Offset : -2823083620
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 274725023963; DSPS: 9094412; Offset : -2823068104
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 294725703903; DSPS: 9749794; Offset : -2823059239
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 294, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 314726469989; DSPS: 10405179; Offset : -2823056457
,I/jxcore-log( 6483): Connected to the server!
I/jxcore-log( 6483): 
,I/chromium( 6483): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 334727219356; DSPS: 11060564; Offset : -2823070134
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 294, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/PowerManagerServiceEx(  964): acquireWakeLockInternal: lock=357792421, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,I/ActivityManager(  964): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8604 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 8604): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8604): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@337a09c0
D/PowerManagerServiceEx(  964): releaseWakeLockInternal: lock=357792421 [*alarm*], flags=0x0
I/ActivityManager(  964): Killing 8382:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  964): failed to open /acct/uid_10011/pid_8382/cgroup.procs: No such file or directory
,I/LocationManagerService(  964): remove 31e4cd39
D/LocationManagerService(  964): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  964): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  964): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  964): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 354727936328; DSPS: 11715947; Offset : -2823055091
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 374728787153; DSPS: 12371335; Offset : -2823058473
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 394729471000; DSPS: 13026718; Offset : -2823076817
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 414730515680; DSPS: 13682112; Offset : -2823069423
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 434731287913; DSPS: 14337497; Offset : -2823060129
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 454732034832; DSPS: 14992882; Offset : -2823076383
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 474732691855; DSPS: 15648263; Offset : -2823060178
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 494733445285; DSPS: 16303648; Offset : -2823069556
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 514734248611; DSPS: 16959034; Offset : -2823059740
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 534734910895; DSPS: 17614416; Offset : -2823068791
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 554735580835; DSPS: 18269798; Offset : -2823070236
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 574736331921; DSPS: 18925183; Offset : -2823082221
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 594736988318; DSPS: 19580564; Offset : -2823066849
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 614737835135; DSPS: 20235952; Offset : -2823074524
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 634738572523; DSPS: 20891336; Offset : -2823069636
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 654739325693; DSPS: 21546721; Offset : -2823078989
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 674740028758; DSPS: 22202104; Offset : -2823078167
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 694740674948; DSPS: 22857485; Offset : -2823072429
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 714741427129; DSPS: 23512870; Offset : -2823083370
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 734742286235; DSPS: 24168258; Offset : -2823078783
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 754743042061; DSPS: 24823642; Offset : -2823055483
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 774743793616; DSPS: 25479027; Offset : -2823066632
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 794744464233; DSPS: 26134409; Offset : -2823067324
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 814745103965; DSPS: 26789790; Offset : -2823068670
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 834745846353; DSPS: 27445174; Offset : -2823058495
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 854746661866; DSPS: 28100561; Offset : -2823067138
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 874747393734; DSPS: 28755945; Offset : -2823067901
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 894748057997; DSPS: 29411327; Offset : -2823074843
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 914748834864; DSPS: 30066712; Offset : -2823061097
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 934749578971; DSPS: 30722097; Offset : -2823079617
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  964): acquireWakeLockInternal: lock=357792421, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{2e8841fd type 2 when 952982 com.android.bluetooth} when 952982
D/PowerManagerServiceEx(  964): releaseWakeLockInternal: lock=357792421 [*alarm*], flags=0x0
,W/bt-smp  ( 1996): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1996): Plain text(LSB ~ MSB) = 26 cb 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1996): Encrypted text(LSB ~ MSB) = 0e 96 d1 82 a2 4a 97 cf 0c 5b 7a 04 4e 36 3d bf 
W/bt-btm  ( 1996): Stopping oneshot timer
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 954750667297; DSPS: 31377492; Offset : -2823059380
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 974751430103; DSPS: 32032877; Offset : -2823060035
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 994752231032; DSPS: 32688264; Offset : -2823082585
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/PowerManagerServiceEx(  964): acquireWakeLockInternal: lock=357792421, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{1acd5ef2 type 2 when 1008895 com.google.android.gms} when 1008895
D/PowerManagerServiceEx(  964): releaseWakeLockInternal: lock=357792421 [*alarm*], flags=0x0
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1014752998368; DSPS: 33343648; Offset : -2823047463
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1034753752267; DSPS: 33999033; Offset : -2823056893
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1054754416426; DSPS: 34654415; Offset : -2823064252
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1074755262251; DSPS: 35309803; Offset : -2823072867
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1094756026671; DSPS: 35965188; Offset : -2823070814
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1114756755413; DSPS: 36620572; Offset : -2823075041
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1134757431185; DSPS: 37275954; Offset : -2823070394
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1154758191491; DSPS: 37931339; Offset : -2823073237
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1174758937994; DSPS: 38586723; Offset : -2823059156
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1194759600643; DSPS: 39242105; Offset : -2823067659
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1214760567511; DSPS: 39897497; Offset : -2823077562
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/UsageStatsService(  964): User[0] Flushing usage stats to disk
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1234761314742; DSPS: 40552881; Offset : -2823062831
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1254762109891; DSPS: 41208267; Offset : -2823061139
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1274763395404; DSPS: 41863669; Offset : -2823057494
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1294764056125; DSPS: 42519051; Offset : -2823067509
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1314764891483; DSPS: 43174438; Offset : -2823056516
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1334765656579; DSPS: 43829823; Offset : -2823055245
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1354766418499; DSPS: 44485208; Offset : -2823055639
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1374767074116; DSPS: 45140590; Offset : -2823071018
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1394767748691; DSPS: 45795972; Offset : -2823067726
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1414768491340; DSPS: 46451356; Offset : -2823057941
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1434769248155; DSPS: 47106741; Offset : -2823063832
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1454770313929; DSPS: 47762136; Offset : -2823066719
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1474770743714; DSPS: 48417510; Offset : -2823063789
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1494771402508; DSPS: 49072892; Offset : -2823076357
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1514772069219; DSPS: 49728274; Offset : -2823081137
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1534772909524; DSPS: 50383661; Offset : -2823064963
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1554773683735; DSPS: 51039046; Offset : -2823053612
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1574774543467; DSPS: 51694435; Offset : -2823079021
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1594775300699; DSPS: 52349820; Offset : -2823084234
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1614775969962; DSPS: 53005201; Offset : -2823056152
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1634776745111; DSPS: 53660587; Offset : -2823074382
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1654777511613; DSPS: 54315972; Offset : -2823070872
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1674778260927; DSPS: 54971357; Offset : -2823084340
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1694778935296; DSPS: 55626739; Offset : -2823081489
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1714779574819; DSPS: 56282120; Offset : -2823083277
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1734780277729; DSPS: 56937503; Offset : -2823081751
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1754781036471; DSPS: 57592887; Offset : -2823056264
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1774781694693; DSPS: 58248269; Offset : -2823068387
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1794782441456; DSPS: 58903654; Offset : -2823084538
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1996): Disconnected process message: 10, size: 0
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1814783203948; DSPS: 59559038; Offset : -2823054805
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1834783957742; DSPS: 60214423; Offset : -2823063874
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  964): acquireWakeLockInternal: lock=357792421, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{16599bc0 type 2 when 1853120 com.android.bluetooth} when 1853120
,W/bt-smp  ( 1996): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1996): Plain text(LSB ~ MSB) = ed ac 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1996): Encrypted text(LSB ~ MSB) = 8b 18 4d bb 9c 63 dd 06 09 79 91 21 1d 28 1d cb 
W/bt-btm  ( 1996): Stopping oneshot timer
I/ProcessStatsService(  964): Prepared write state in 18ms
,I/ProcessStatsService(  964): Prepared write state in 17ms
,I/DigitalAppWidgetProvider( 8604): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,I/ProcessStatsService(  964): Prepared write state in 10ms
,V/DigitalAppWidgetProvider( 8604): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@337a09c0
D/PowerManagerServiceEx(  964): releaseWakeLockInternal: lock=357792421 [*alarm*], flags=0x0
I/ProcessStatsService(  964): Pruning old procstats: /data/system/procstats/state-2015-12-09-22-24-57.bin
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1854784726381; DSPS: 60869808; Offset : -2823057809
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1874785395123; DSPS: 61525190; Offset : -2823061027
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1894786154907; DSPS: 62180575; Offset : -2823064130
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  964): acquireWakeLockInternal: lock=357792421, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{81c00f9 type 2 when 1909061 com.google.android.gms} when 1909061
D/PowerManagerServiceEx(  964): releaseWakeLockInternal: lock=357792421 [*alarm*], flags=0x0
,V/AlarmManager(  964): RTC_WAKEUP set : Alarm{35ce783e type 0 when 1449758403773 com.google.android.gms} when 1449758403773
,I/EventLogService( 2270): Aggregate from 1449756705447 (log), 1449756603697 (data)
,D/LocationManagerService(  964): getAllProviders()=[passive, gps, network]
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10006
,D/DnsProxyListener(  268): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
,I/System.out( 1732): propertyValue:false
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  964): android: cancelAsUser(2) by android
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8885): 
D/AndroidRuntime( 8885): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8885): CheckJNI is OFF
I/ThermalEngine(  286): Sensor:pa_therm0:28000 mC
D/AndroidRuntime( 8885): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  964): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  964): Killing 6483:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  964): WIN DEATH: Window{3dc579e9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  964): Focus left window: Window{3dc579e9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  964): Window went away: Window{3dc579e9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  964): Skipping PackageSetting{73979a3 com.example.hello/10030} due to missing metadata
I/ActivityManager(  964):   Force finishing activity ActivityRecord{2f6872c2 u0 com.test.thalitest/.MainActivity t220}
V/ActivityManager(  964): Display changed displayId=0
D/DSDPConnection( 1751): Display #0 changed.
W/ActivityManager(  964): Spurious death for ProcessRecord{7aaf01c 6483:com.test.thalitest/u0a316}, curProc for 6483: null
I/ActivityManager(  964): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  964):   Force finishing activity ActivityRecord{2f6872c2 u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  964): Duplicate finish request for ActivityRecord{2f6872c2 u0 com.test.thalitest/.MainActivity t220 f}
I/[LGHome]EVENT( 1877): [Launcher.java:5203:onStart()]onStart
D/KeyguardModel( 1371): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
I/[LGHome]EVENT( 1877): [Launcher.java:776:onResume()]onResume
I/art     ( 1942): Explicit concurrent mark sweep GC freed 15796(1017KB) AllocSpace objects, 4(95KB) LOS objects, 40% free, 11MB/19MB, paused 1.637ms total 122.611ms
I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
W/System.err( 3585): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3585): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3585): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3585): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3585): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3585): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3585): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3585): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3585): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3585): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3585): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3585): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  964): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8933 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/art     ( 2270): Explicit concurrent mark sweep GC freed 20068(1183KB) AllocSpace objects, 5(80KB) LOS objects, 25% free, 14MB/19MB, paused 1.041ms total 175.437ms
I/[LGHome]EVENT( 1877): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1371): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1371): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1877): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1877): [Launcher.java:929:onResume()]onResume end
I/Activity( 1877): Activity.onPostResume() called 
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1371): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1371): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1371): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1877): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1877): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourcesManager( 8933): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8933): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8933): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1371): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/art     (  964): Explicit concurrent mark sweep GC freed 45052(2MB) AllocSpace objects, 10(307KB) LOS objects, 33% free, 23MB/35MB, paused 3.366ms total 281.915ms
D/KeyguardModel( 1371): handleShortcutListChanged...
I/art     (  964): WaitForGcToComplete blocked for 246.880ms for cause Explicit
D/KeyguardModel( 1371): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1371): createShortcutInfo...
D/KeyguardModel( 1371): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1371): createShortcutInfo...
I/SystemUI[Framework](  964): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1371): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/InputDispatcher(  964): Focus entered window: Window{1f2cdfb1 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1371): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1371): createShortcutInfo...
W/PhoneWindowManagerEx(  964): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  964): setLGSystemUiVisibility(0x0)
D/KeyguardModel( 1371): handleShortcutListChanged...
D/StatusBarManagerServiceEx(  964): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  964): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3fe33132,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  964): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  964): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  964): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  964): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  964): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  964): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3fe33132,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  964): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/administrator(  964): Handling package changes for user 0
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1877): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  964): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  964): Got RemoteException sending setActive(false) notification to pid 6483 uid 10316
I/LGEmail ( 8933): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 8933): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/NotificationService(  964): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  964): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  964): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  964): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1371): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1371):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1371): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/Timeline(  964): Timeline: Activity_windows_visible id: ActivityRecord{36d48c37 u0 com.lge.launcher2/.Launcher t219} time:1911425
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/IInputConnectionWrapper( 1877): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
E/b       ( 1611): Unable to connect to the editor to retrieve text... will retry later
I/art     (  964): Explicit concurrent mark sweep GC freed 8466(477KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.743ms total 323.220ms
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1877): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
D/AndroidRuntime( 8885): Shutting down VM
W/ResourcesManager(  964): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
I/PackageChangeReceiver( 8933): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
W/ResourceType(  964): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager(  964): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8963 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  964): Killing 8401:com.android.gallery3d/u0a23 (adj 15): empty #11
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
W/libprocessgroup(  964): failed to open /acct/uid_10023/pid_8401/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 8963): onCreate
W/AppUp4:DB( 8963):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 8963):  setFingerPrint start
I/AppUp4:DB( 8963):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/AppUp4:DB( 8963):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8963):  SDK version = 0
I/AppUp4:DB( 8963):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8963): AppBoxApplication onCreate()
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
D/AppUp4:PreloadHelper( 8963): added Exclude : com.test.thalitest
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  964): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8985 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  964): Killing 8335:com.google.android.talk/u0a61 (adj 15): empty #11
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  964): failed to open /acct/uid_10061/pid_8335/cgroup.procs: No such file or directory
I/Timeline( 1877): Timeline: Activity_idle id: android.os.BinderProxy@33b83e5 time:1912018
E/SharedPreferencesImpl( 1877): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
I/art     ( 1877): Explicit concurrent mark sweep GC freed 28131(1528KB) AllocSpace objects, 19(2MB) LOS objects, 40% free, 15MB/25MB, paused 1.178ms total 56.335ms

```
