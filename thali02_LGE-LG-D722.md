#### Test 549702617e2936d_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
I/ActivityManager(  840): Killing 5949:com.google.android.talk/u0a61 (adj 15): empty #11
,I/ActivityManager(  840): Killing 6171:com.android.calendar/u0a13 (adj 15): empty #12
W/libprocessgroup(  840): failed to open /acct/uid_10061/pid_5949/cgroup.procs: No such file or directory
W/libprocessgroup(  840): failed to open /acct/uid_10013/pid_6171/cgroup.procs: No such file or directory
--------- beginning of main
D/AndroidRuntime( 6371): 
D/AndroidRuntime( 6371): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6371): CheckJNI is OFF
D/AndroidRuntime( 6371): Calling main entry com.android.commands.am.Am
I/ActivityManager(  840): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  840): setTaskToReturnTo : TaskRecord{36538972 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  840): setTaskToReturnTo : TaskRecord{36538972 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  840): AppWindowTokenEx init.. 
D/ContextHelper(  840): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1875): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  840): Focus left window: Window{2c946bdd u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6371): Shutting down VM
D/SplitWindow(  840): check instance of lgWin Window{110d8a6c u0 Starting com.test.thalitest}
I/ActivityManager(  840): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6385 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1875): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1875): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  840): Starting window displayed
I/SystemUI[Framework](  840): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1367): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  840): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  840): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  840): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  840): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@38ad064d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  840): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1367): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1367):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1367): , Keyguard show=false, IME shown=false, Panel expanded=false
I/HotwordDetector( 1933): Closing mic
D/BarTransitions( 1367): draw background and invalidate : color = 1a000000
D/BarTransitions( 1367): draw background and invalidate : color = 1e1d1d1d
,I/MicrophoneInputStream( 1933): mic_close com.google.android.apps.gsa.speech.audio.u@c86321d
V/AudioRecord( 1933): stop()
D/AudioRecord( 1933): AudioRecord->stop()
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
V/AudioFlinger(  283): Record stopped OK
V/AudioPolicyManager(  283): stopInput() input 17
V/AudioPolicyService(  283): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  283): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  283): ThreadBase::setParameters() routing=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb39ef000
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  283): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  283): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  283): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  283): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  283): disable_audio_route: exit
E/audio_hw_primary(  283): disable_snd_device: enter 144
D/hardware_info(  283): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  283): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  283): stop_input_stream: exit: status(0)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyManager(  283): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  283): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  283): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  283): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyService(  283): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  283): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  283): setParameters(): io 17, keyvalue hotword_active=0, calling pid 283
V/AudioFlinger(  283): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  283): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  283): in_set_parameters: exit: status(0)
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb39ef000
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioRecord( 1933): stop()
V/AudioRecord( 1933): stop()
V/AudioRecord( 1933): stop()
V/AudioFlinger(  283): releasing 16 from 1933 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
V/AudioPolicyManager(  283): releaseInput() 17
V/AudioPolicyManager(  283): closeInput(17)
V/AudioFlinger(  283): closeInput() 17
V/AudioSystem(  283): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  840): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): ThreadBase::exit
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioSystem( 1367): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3141): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): RecordThread 0xb39ef000 exiting
V/AudioSystem( 2032): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1750): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  283): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioPolicyService(  283): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  283): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  283): releaseInput() exit
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio port list
V/AudioFlinger(  283): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  283): removeClient_l() pid 1933, calling pid 283
V/AudioSystem( 2764): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioSystem( 1933): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 1933): Stopping hotword detection.
I/HotwordRecognitionRnr( 1933): Hotword detection finished
D/ContextHelper( 6385): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6385): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6385): Time to load native libraries: 2 ms (timestamps 8119-8121)
I/LibraryLoader( 6385): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6385): Binding Chromium to main looper Looper (main, tid 1) {fe607e5}
I/LibraryLoader( 6385): Expected native library version number "",actual native library version number ""
I/chromium( 6385): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6385): Initializing chromium process, singleProcess=true
W/art     ( 6385): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6385): ApplicationContext is null in ApplicationStatus
I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
W/chromium( 6385): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6385): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6385): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6385): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6385): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6385): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6385): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6385): Remote Branch: 
I/Adreno-EGL( 6385): Local Patches: 
I/Adreno-EGL( 6385): Reconstruct Branch: 
V/AudioPolicyService(  283): registerClient() client 0xb39a4d40, uid 10316
D/BluetoothManagerService(  840): Message: 20
D/BluetoothManagerService(  840): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f1f5f6e:true
D/BluetoothAdapterService(401882465)( 2032): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@26b4ee3f
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/art     ( 6385): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6385): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6385): CordovaWebView is running on device made by: LGE
,W/art     ( 6385): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6385): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 6385): Activity.onPostResume() called 
,D/OpenGLRenderer( 6385): Render dirty regions requested: true
I/OpenGLRenderer( 6385): Initialized EGL, version 1.4
D/OpenGLRenderer( 6385): Enabling debug mode 0
,D/Atlas   ( 6385): Validating map...
,D/SplitWindow(  840): check instance of lgWin Window{3a58801e u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6385): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/InputDispatcher(  840): Focus entered window: Window{3a58801e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  840): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  840): Displayed com.test.thalitest/.MainActivity: +1s93ms
I/Timeline(  840): Timeline: Activity_windows_visible id: ActivityRecord{159e71c3 u0 com.test.thalitest/.MainActivity t220} time:98758
I/Timeline( 6385): Timeline: Activity_idle id: android.os.BinderProxy@146813f8 time:98769
,W/BindingManager( 6385): Cannot call determinedVisibility() - never saw a connection for the pid: 6385
,D/JsMessageQueue( 6385): Set native->JS mode to OnlineEventsBridgeMode
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:33.314 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/jxcore_app_log( 6385): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622833664
D/JX-Cordova( 6385): jxcore cordova android initializing
,I/art     ( 6385): CheckpointMarkThreadRoots callback created = 0x9f4f1c60
,I/art     ( 6385): CheckpointMarkThreadRoots callback created = 0x9f4f1c30
,I/ActivityManager(  840): Killing 6037:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  840): failed to open /acct/uid_10018/pid_6037/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 6317): mConnectedToCar = false, abort
,E/ActivityThread( 6317): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3682d822 that was originally bound here
E/ActivityThread( 6317): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3682d822 that was originally bound here
E/ActivityThread( 6317): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6317): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6317): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6317): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6317): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6317): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6317): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6317): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6317): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6317): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6317): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6317): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6317): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6317): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6317): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6317): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6317): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6317): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6317): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6317): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6317): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6317): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6317): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6317): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1058a1a5 that was originally bound here
E/ActivityThread( 6317): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1058a1a5 that was originally bound here
E/ActivityThread( 6317): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6317): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6317): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6317): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6317): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6317): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6317): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6317): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6317): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6317): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6317): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6317): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6317): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6317): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6317): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6317): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6317): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6317): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6317): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6317): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6317): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6317): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/ActivityManager(  840): Unbind failed: could not find connection for android.os.BinderProxy@60674f6
W/jxcore-log( 6385): Initializing JXcore engine
,W/jxcore-log( 6385): JXcore engine is ready
W/jxcore-log( 6385): Starting JXcore engine
,W/.test.thalitest( 6385): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7438]" dev="sockfs" ino=7438 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6385): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6385): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6402]" dev="sockfs" ino=6402 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6385): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6385): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6385): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[29800]" dev="sockfs" ino=29800 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 6385): Platform android
W/jxcore-log( 6385): 
,W/jxcore-log( 6385): Process ARCH arm
W/jxcore-log( 6385): 
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:36.336 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/jxcore-log( 6385): JXcore Cordova bridge is ready!
I/jxcore-log( 6385): 
W/jxcore-log( 6385): JXcore engine is started
,I/chromium( 6385): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 6385): Skipped 194 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 6385): Toggling radios to true
I/jxcore-log( 6385): 
,D/BluetoothAdapter( 6385): enable(): BT is already enabled..!
D/WifiServiceImplEx(  840): setWifiEnabled: true pid=6385, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  840): setWifiEnabled: true pid=6385, uid=10316
D/WifiServiceImplEx(  840): disconnect pid=6385, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  840): reconnect pid=6385, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6385): Radios toggled
I/jxcore-log( 6385): 
I/jxcore-log( 6385): My device name is: LGE-LG-D722
I/jxcore-log( 6385): 
V/AlarmManager(  840): RTC_WAKEUP set : Alarm{1e8a0b64 type 0 when 1452525637159 com.google.android.googlequicksearchbox} when 1452525637159
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2653): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2653): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  840): WifiStateMachine: Leaving Connected state
D/WfdsMonitor( 1801): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,E/WifiConfigStore(  840): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LGWifiP2pService(  840): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  840): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  840): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  279): Clearing all IP addresses on wlan0
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1731): Read error: ssl=0xaaf40800: I/O error during system call, Connection timed out
,V/NativeCrypto( 1731): SSL shutdown failed: ssl=0xaaf40800: I/O error during system call, Broken pipe
D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 7
D/ConnectivityService(  840): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/WifiHS20(  840): hidePasspointNotification off =false
W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  840): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:37.294 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,D/ConnectivityService(  840): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/ConnectivityService(  840): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  840): ValidatedState{ when=-4ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  840): DefaultState{ when=-27ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  840): Forcing reevaluation
I/ActivityManager(  840): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6498 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,E/WifiStateMachine(  840): Start Disconnecting Watchdog 1
D/WifiHS20(  840): hidePasspointNotification off =false
W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/wpa_supplicant( 2653): wlan0: CTRL-EVENT-SCAN-STARTED 
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  840): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  840): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  840): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:37.382 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
D/CommandListener(  279): Clearing all IP addresses on wlan0
,D/ConnectivityService(  840): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  840): disableDataServiceNotify
D/WifiHS20(  840): hidePasspointNotification off =false
D/DSQN    (  840): stop dsqn bin
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:37.404 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  840): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiNetworkAgent(  840): NetworkAgent: NetworkAgent channel lost
,I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  840): hidePasspointNotification off =false
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:37.413 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiOffDelayIfNotUsed(  840): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:37.416 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiOffDelayIfNotUsed(  840): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/ConnectivityService(  840): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/WifiServerServiceExt(  840): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  840): setSupplicantStateDISCONNECTED
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  840):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  840):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt(  840): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  840): setSupplicantStateSCANNING
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWi,fiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  840): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
D/Nat464Xlat(  840): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  840): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  840): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  840): Disconnected - quitting
D/CSLegacyTypeTracker(  840): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  840): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1367): CM callback handler got msg 524292
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  840): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  840): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  840): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  840): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  840): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  840): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
D/WIFI    (  840): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  840):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/QCNEJ   ( 1838): |CORE| No family connected
D/Tethering(  840): MasterInitialState.processMessage what=3
V/NetworkPolicy(  840): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy(  840): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  840): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1838): |CORE| No family connected
I/QCNEJ   ( 1838): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/NetworkManagementService(  840): Removing idletimer
D/TelephonyNetworkFactory-1( 1750): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/QCNEJ   ( 1838): |CORE| sendDefaultNwMsg: default = -1
I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,W/Settings(  840): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  840): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/DhcpStateMachine(  840): StoppedState
D/DhcpStateMachine(  840): StoppedState{ when=-109ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/rmt_storage(  277): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  277): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  277): wakelock acquired: 1, error no: 42
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
D/TelephonyIcons( 1367): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1367): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/TelephonyIcons( 1367): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1367): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  277): 
I/rmt_storage(  277): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
W/ResourcesManager( 6498): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6498): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6498): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6498): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6498): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/ActivityManager(  840): Process com.google.android.gm (pid 6088) has died
,I/IndexDatabaseHelper( 6498): Using schema version: 115
,I/IndexDatabaseHelper( 6498): Index is fine
I/ActivityManager(  840): Process com.google.android.apps.plus (pid 5703) has died
,V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
I/ActivityManager(  840): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6524 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  840): Process com.lge.lockscreensettings (pid 6059) has died
,I/PCSuite ( 6524): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6524): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6524): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  840): Process com.android.providers.calendar (pid 6264) has died
,V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
I/PCSuite ( 6524): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6524): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6524): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  840): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6546 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6546): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/wpa_supplicant( 2653): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
D/LocSvc_java(  840): onReceive
,W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:38.541 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 2653): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
D/WifiOffDelayIfNotUsed(  840): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  840): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt(  840): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  840): setSupplicantStateASSOCIATING
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:38.547 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  840): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  840): setSupplicantStateASSOCIATED
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  840): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:38.571 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  840): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  840): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  840): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:38.575 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/wpa_supplicant( 2653): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2653): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiServerServiceExt(  840): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  840): setSupplicantStateGROUP_HANDSHAKE
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
I/WifiServiceExtension(  840): setVHTCapabilityType  : false
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
,I/ActivityManager(  840): Process com.google.android.gms:car (pid 6317) has died
,I/WifiServerServiceExt(  840): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  840): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  840): setSecurityType  : 2
W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  840): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:38.75 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:38.753 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  840): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
D/ConnectivityService(  840): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  840): Got NetworkAgent Messenger
D/ConnectivityService(  840): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  840): NetworkAgent connected
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
E/WifiConfigStore(  840): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Babel_SMS( 6546): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6546): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6546): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6546): MmsConfig.loadFromDatabase
E/WifiConfigStore(  840): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  279): Setting iface cfg
E/WifiStateMachine(  840): Start Dhcp Watchdog 2
D/DhcpStateMachine(  840): StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  840): WaitBeforeStartState
D/ConnectivityService(  840): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/WifiServerServiceExt(  840): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  840): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  840): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  840): setSupplicantStateCOMPLETED
,E/Babel_SMS( 6546): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6546): MmsConfig.loadFromResources
E/Babel_SMS( 6546): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6546): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6546): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6546): found sensor: LGE Magnetometer Sensor, handle=10
,D/SensorManager( 6546): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6546): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6546): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6546): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6546): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6546): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6546): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6546): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6546): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6546): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6546): found sensor: LGE Tilt Detector Sensor, handle=55
,D/SensorManager( 6546): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6546): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6546): found sensor: Motion Accel, handle=46
E/WifiStateMachine(  840): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  840): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  840): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LGWifiP2pService(  840): InactiveState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1fd63c7b target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  840): P2pEnabledState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1fd63c7b target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  840): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  840): DHCP Start wake lock is acquired.
D/CommandListener(  279): Setting iface cfg
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  279): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  840): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/ConnectivityService(  840): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  840): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  840): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  840): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  840): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  840): ignoring duplicate network state non-change
I/art     ( 6546): CheckpointMarkThreadRoots callback created = 0xaaf41550
,I/art     ( 6546): CheckpointMarkThreadRoots callback created = 0xaaf41520
,I/art     (  840): Explicit concurrent mark sweep GC freed 49550(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.795ms total 222.639ms
,E/WifiStateMachine(  840): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  840): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  840): Adding iface wlan0 to network 101
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  840): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:39.102 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
D/DhcpStateMachine(  840): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  840): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  840): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  840): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:39.112 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  840): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:39.121 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
E/ConnectivityService(  840): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  840): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  840): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  279): netlink response contains error (File exists)
D/ConnectivityService(  840): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/dhcpcd  ( 6581): version 5.5.6 starting
D/ConnectivityService(  840): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  840): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  840): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/dhcpcd  ( 6581): get_duid: Read-only file system
,W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  840): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  840): [PASSPOINT] passpointNotification: hs20AP list is checked
D/Nat464Xlat(  840): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  840): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  840): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService(  840): rematching NetworkAgentInfo [WIFI () - 101]
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService(  840):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiOffDelayIfNotUsed(  840): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService(  840):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  840):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  840):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  840):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  840): currentScore = 0, newScore = 20
D/ConnectivityService(  840):    accepting network in place of null
D/ConnectivityService(  840): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  840): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  840): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  840): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI    (  840): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  840):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/ConnectivityService(  840): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  840): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  840): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  840): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  840): [e] list.add(nai) empty : false size: 1
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:39.154 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  840): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory-1( 1750): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  840): validation of new default Network = false
D/ConnectivityService(  840): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  840): enableDataServiceNotify 
D/DSQN    (  840): start dsqn bin
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnecte,d mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  840): [LWD] Start DNSResolver start to wait
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/Tethering(  840): MasterInitialState.processMessage what=3
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  840): [LWD] wait 500ms before dns check
W/QCNEJ   ( 1838): |CORE| No family connected
I/QCNEJ   ( 1838): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1838): |CORE| sendDefaultNwMsg: default = 1
I/DSQN    ( 6585): DSQN samuel.seo ver 141203
E/DSQN    ( 6585): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6585): created command queue thread
I/DSQN    ( 6585): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6585): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,D/ConnectivityService(  840): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  840):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  840):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkPolicy(  840): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService(  840): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1367): CM callback handler got msg 524290
D/TelephonyIcons( 1367): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1367): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,W/Settings( 6546): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/dhcpcd  ( 6581): wlan0: rebinding lease of 192.168.1.134
I/Babel_Crash( 6546): startup - clean
I/Babel   ( 6546): deleted: false for 0
,V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
W/AudioCapabilities( 6546): Unsupported mime audio/x-lg-flac
I/PCSuite ( 6524): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6524): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6524): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6546): Unsupported mime audio/adpcm
W/AudioCapabilities( 6546): Unsupported mime audio/g726
W/AudioCapabilities( 6546): Unsupported mime audio/x-ms-wma
V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/AudioCapabilities( 6546): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6546): Unsupported mime video/mjpg
D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
W/VideoCapabilities( 6546): Unsupported mime video/theora
I/PCSuite ( 6524): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6524): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6524): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/dhcpcd  ( 6581): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
W/AudioCapabilities( 6546): Unsupported mime audio/evrc
W/AudioCapabilities( 6546): Unsupported mime audio/qcelp
,V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,W/VideoCapabilities( 6546): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6498): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6546): Unsupported mime audio/amr-wb-plus
D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
W/AudioCapabilities( 6546): Unsupported mime audio/qcelp
,I/dhcpcd  ( 6581): wlan0: leased 192.168.1.134 for 86400 seconds
V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
W/AudioCapabilities( 6546): Unsupported mime audio/evrc
,V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/VideoCapabilities( 6546): Unsupported mime video/mp4v-esdp
D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
I/VideoCapabilities( 6546): Unsupported profile 4 for video/mp4v-es
,V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/VideoCapabilities( 6546): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
W/VideoCapabilities( 6546): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6546): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6546): Unrecognized profile 2130706433 for video/avc
,I/PCSuite ( 6524): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6524): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/vclib   ( 6546): onServiceConnected
W/Babel   ( 6546): Attempted to change video mute state without an active call.
V/WiFiOffLoadBroadcast( 6498): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/NotificationManager( 6546): com.google.android.talk: cancel(10436) by com.google.android.talk
D/WiFiOffLoadBroadcast( 6498): MCCMNC not supported: null
I/PCSuite ( 6524): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6524): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  840): [LWD] DNSResolver start dns
D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  840): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  840): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  840): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  840): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  840): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  840): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  840): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  840): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  840): RunningState
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out(  840): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  840): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  840): Checking http://clients3.google.com/generate_204 on "NG700"
,D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6585): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6585): restart monitoring
D/LGDataListener(  279): argv[0]=dsqncommand
D/LGDataListener(  279): argv[1]=wlan0
D/LGDataListener(  279): argv[2]=1
D/LGDataListener(  279): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6585): dsqn report finish
D/DSQN    (  840): DSQM DsqnNotification wlan0  1
D/DSQN    (  840): start to monitor internet connection
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  840): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 15:20:39 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452525639766], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452525639750]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  840): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  840): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  840): Validated
D/ConnectivityService(  840): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  840): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  840):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  840):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  840):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  840): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  840): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  840):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  840):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  840): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  840): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1367): CM callback handler got msg 524290
D/ConnectivityService(  840): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiDataContinuityService(  840): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/TelephonyNetworkFactory-1( 1750): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  840): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  840):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/WifiServerServiceExt(  840): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyIcons( 1367): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1367): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  840): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  840): identical MTU - not setting
D/Nat464Xlat(  840): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  840): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  840):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  840):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  840): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1367): CM callback handler got msg 524295
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  840): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  840): enableDataServiceNotify 
D/DSQN    (  840): start dsqn bin
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:39.949 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/DSQN    (  840): dsqn is running restart
,I/DSQN    ( 6621): DSQN samuel.seo ver 141203
,E/DSQN    ( 6621): DSQN sock connect success to lgdatalistenerd
,I/DSQN    ( 6621): created command queue thread
I/DSQN    ( 6621): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6621): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  840): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  840): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  840): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  840): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  840): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  840): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6627 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LocSvc_java(  840): onReceive
D/LocSvc_java(  840): got connectivity action
D/LocSvc_java(  840): broadcast - no network connections
D/LocSvc_java(  840): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  840): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  840): onReceive
D/LocSvc_java(  840): got connectivity action
D/LocSvc_java(  840): broadcast - no network connections
D/LocSvc_java(  840): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  840): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  840): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  840): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  840): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  840): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  840): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  840): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  840): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  840): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/MusicStore( 6627): Database version: 120
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6627): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6627): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6627): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6627): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6627): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6627): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6627): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6627): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@269a49f6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6627): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6627): GMSCore installation verified
,I/ConfigStore( 6627): Config Database version: 1
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/MediaRouter( 6627): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6627): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6627): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6627): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  840): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6669 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 22.479ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.330ms
,I/GHttpClientFactory( 6627): Using our fixed implementation of GMSCore's GoogleHttpClient
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 20.578ms
,I/GoogleURLConnFactory( 6627): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6669): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6669): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6669): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/NotificationManager( 6627): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6669): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6669): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6669): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  840): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6692 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:41.873 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/HubEmail( 6669): JNI_OnLoad()
I/HubEmail( 6669): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6669): registerNatives()
I/HubEmail( 6669): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6669): registerNativeMethods()
I/HubEmail( 6669): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6669): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6669): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6692): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6692): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6692): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6692): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6692): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6692): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 6692): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6692): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  840): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6715 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ContextImpl( 6692): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6692): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6692): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6692): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6692): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6692): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  840): Killing 5818:com.android.vending/u0a36 (adj 15): empty #11
V/WifiInternetCheck(  840): Single check msg out of sync, ignoring.
,I/AppUp4:AppBoxCP( 6715): onCreate
W/AppUp4:DB( 6715):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6715):  setFingerPrint start
I/AppUp4:DB( 6715):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6715):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6715):  SDK version = 0
I/AppUp4:DB( 6715):  beforefinger == newfinger no write in DB
D/ConnectivityService(  840): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup(  840): failed to open /acct/uid_10036/pid_5818/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6715): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6715): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6715): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6715): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6715): [onReceive] request level :IDLE....
D/LocSvc_java(  840): onReceive
D/LocSvc_java(  840): got connectivity action
D/LocSvc_java(  840): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  840): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  840): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  840): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  840): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  840): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  840): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6627): type=WIFI subType= reason=null isConnected=true
I/AppUp4:CustModeStarterReceiver( 6715): onReceive
I/AppUp4:CustModeStarterReceiver( 6715): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6715): Context : android.app.ReceiverRestrictedContext@1b7752ba
,D/AppUp4:CustFacade( 6715): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6715): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6715): begin check event
I/AppUp4:CustModeStarterReceiver( 6715): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6715): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6715): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6715): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6715): handleAsyncCustNotification do not startCustService
I/ActivityManager(  840): Killing 6546:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  840): failed to open /acct/uid_10061/pid_6546/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3141): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3141): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3141): networkInfo.isConnected() = false
I/ActivityManager(  840): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6743 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,D/PhoneMonitor( 6743): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6743): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6743): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  840): Killing 6498:com.android.settings/1000 (adj 15): empty #11
D/PhoneMonitor( 6743): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6743): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6743): [parse] Load xml
V/TelephonyAutoProfiling( 6743): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6743): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6743): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  840): failed to open /acct/uid_1000/pid_6498/cgroup.procs: No such file or directory
,V/DownloadManager( 3254): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3254): DownloadService onCreate
I/CheckinService( 4346): Checkin interval check for package: unspecified last checkin: 1452525614168 min interval config: 0 actual interval: 28591
I/DownloadManager( 3254): in removeSpuriousFiles
I/NotificationManager( 3254): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3254): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3254): created cursor android.database.sqlite.SQLiteCursor@c46781f on behalf of 3254
I/DownloadManager( 3254): in trimDatabase
V/DownloadManager( 3254): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3254): created cursor android.database.sqlite.SQLiteCursor@3994c76c on behalf of 3254
I/ActivityManager(  840): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6769 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3254): DownloadService onStartCommand
I/CheckinService( 4346): Checking schedule, now: 1452525642802 next: 1452525644136
I/CheckinService( 4346): active receiver: disabled
V/DownloadManager( 3254): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3254): created cursor android.database.sqlite.SQLiteCursor@3c30d9ca on behalf of 3254
,V/DownloadManager( 3254): DownloadService onDestroy
,I/ActivityManager(  840): Killing 5720:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 5923): android.os.DeadObjectException
,W/System.err( 5923): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5923): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5923): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5923): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5923): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5923): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5923): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5923): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5923): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5923): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5923): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5923): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5923): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5923): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5923): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5923): android.os.DeadObjectException
W/System.err( 5923): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5923): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5923): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5923): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5923): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5923): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5923): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5923): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5923): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5923): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5923): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5923): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5923): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5923): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5923): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  840): failed to open /acct/uid_10089/pid_5720/cgroup.procs: No such file or directory
W/ActivityManager(  840): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
D/WeatherAncestor( 2728): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:20:43
,I/ActivityManager(  840): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6789 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UpdateThreadPoolManager( 2728): 2 : This is isUpdating : false
D/WeatherAncestor( 2728): connectivity changed - connection : true
D/Weather_cast( 2728): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2728): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:20:43
D/WeatherService( 2728): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  840): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6811 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  840): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2728): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2728): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2728): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
,W/ResourcesManager( 6811): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out(  840): propertyValue:false
D/UEI.SmartControl( 6789): Quickset Services start...
D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  840): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  840): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
I/UEI.SmartControl( 6789): Manufacture = LGE
D/UEI.SmartControl( 6789): File observer start...
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out(  840): propertyValue:false
,E/UEI.SmartControl( 6789): IR Port is disabled: false
D/UEI.SmartControl( 6789): Starting file observer...
D/UEI.SmartControl( 6789): Extracting JNI libs...
D/UEI.SmartControl( 6789): --- this system supports 32-bit or 64-bit only
I/DSQN    ( 6621): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6621): restart monitoring
,D/LGDataListener(  279): argv[0]=dsqncommand
D/LGDataListener(  279): argv[1]=wlan0
D/LGDataListener(  279): argv[2]=1
D/LGDataListener(  279): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6621): dsqn report finish
D/DSQN    (  840): DSQM DsqnNotification wlan0  1
D/DSQN    (  840): start to monitor internet connection
V/WifiInternetCheck(  840): isHttpConnectionAvailable - We got a valid response : 204
,D/UEI.SmartControl( 6789): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6789): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6789): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6789): --- Selecting new region: 2
,I/UEI.SmartControl( 6789): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6789): Platform has CIR...
D/UEI.SmartControl( 6789): NO CIR support, need to check package...
I/UEI.SmartControl( 6789): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6789): QS Service created
E/UEI.SmartControl( 6789): QS start get config
,D/UEI.SmartControl( 6789): Loading JNI Libs...
D/UEI.SmartControl( 6789):  configuring local db...
,I/Babel_SMS( 6811): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6811): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6811): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6811): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6811): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6811): MmsConfig.loadFromResources
E/Babel_SMS( 6811): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6811): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6811): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6811): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6811): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6811): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6811): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6811): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6811): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6811): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6811): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6811): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6811): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6811): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6811): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6811): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6811): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6811): found sensor: Motion Accel, handle=46
,W/art     ( 6811): Suspending all threads took: 11.031ms
,I/art     ( 6811): CheckpointMarkThreadRoots callback created = 0xb042d800
,W/Settings( 6811): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6811): startup - clean
I/art     ( 6811): CheckpointMarkThreadRoots callback created = 0xb042d7e0
,I/Babel   ( 6811): deleted: false for 0
,D/UEI.SmartControl( 6789):  ---- Has DB8: true
D/UEI.SmartControl( 6789): QS start statue = true Error code = 0
D/UEI.SmartControl( 6789): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6789): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6789): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6789): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6789): IrrcClient ++ 
D/irrcClient( 6789): getIrrcService ++ 
D/irrcClient( 6789): getIrrcService -- 
D/irrcClient( 6789): IrrcClient -- 
W/irrc_jni( 6789): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6789): Services init done
,I/UEI.SmartControl( 6789): Device manager: loading config....
,D/UEI.SmartControl( 6789): Config is loaded...
I/ActivityManager(  840): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6852 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6789): QS Service init finished
D/UEI.SmartControl( 6789):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6789): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6789): QS Service version name: 0.1.73
D/UEI.SmartControl( 6789): QS Service version code: 1073
D/UEI.SmartControl( 6789): Service requested: Control
,I/ActivityManager(  840): Killing 6524:com.lge.sync/1000 (adj 15): empty #11
W/AudioCapabilities( 6811): Unsupported mime audio/x-lg-flac
D/UEI.SmartControl( 6789): -----IControl: 11
W/AudioCapabilities( 6811): Unsupported mime audio/adpcm
,D/UEI.SmartControl( 6789): Caller: com.lge.qremote
W/AudioCapabilities( 6811): Unsupported mime audio/g726
D/UEI.SmartControl( 6789): ------------ IControl registerCallback...
I/UEI.SmartControl( 6789): Registering callback...
D/UEI.SmartControl( 6789): -----IControl: 19
W/AudioCapabilities( 6811): Unsupported mime audio/x-ms-wma
D/UEI.SmartControl( 6789): Caller: com.lge.qremote
I/UEI.SmartControl( 6789): Registering Services Ready callback...
W/AudioCapabilities( 6811): Unsupported mime audio/wma-voice
I/UEI.SmartControl( 6789): Notify client services are ready...
W/VideoCapabilities( 6811): Unsupported mime video/mjpg
,D/UEI.SmartControl( 6789): -----IControl: 8
D/UEI.SmartControl( 6789): Caller: com.lge.qremote
W/VideoCapabilities( 6811): Unsupported mime video/theora
W/AudioCapabilities( 6811): Unsupported mime audio/evrc
,W/AudioCapabilities( 6811): Unsupported mime audio/qcelp
W/VideoCapabilities( 6811): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6811): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6811): Unsupported mime audio/qcelp
W/AudioCapabilities( 6811): Unsupported mime audio/evrc
,W/VideoCapabilities( 6811): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6811): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6811): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6811): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6811): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6811): Unrecognized profile 2130706433 for video/avc
W/libprocessgroup(  840): failed to open /acct/uid_1000/pid_6524/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6789): Internal service binding...
,I/vclib   ( 6811): onServiceConnected
W/Babel   ( 6811): Attempted to change video mute state without an active call.
I/NotificationManager( 6811): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6811): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6811): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6811): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6811): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  279): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 6811): propertyValue:false
I/Babel   ( 6811): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  840): Process com.google.android.music:main (pid 6627) has died
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6852): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6852): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6852): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6852): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6852): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6852):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6852):   adb logcat -s GAv4
W/GAv4    ( 6852): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6852): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6852): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
V/AlarmManager(  840): RTC_WAKEUP set : Alarm{1eb6538b type 0 when 1452525644136 com.google.android.gms} when 1452525644136
,I/ActivityManager(  840): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6884 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  840): RTC_WAKEUP set : Alarm{9981c68 type 0 when 1452525644572 com.android.vending} when 1452525644572
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:44.845 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/Finsky  ( 6884): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/WebViewFactory( 6852): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6852): Time to load native libraries: 2 ms (timestamps 844-846)
I/LibraryLoader( 6852): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6852): Binding Chromium to main looper Looper (main, tid 1) {3b03a70f}
I/LibraryLoader( 6852): Expected native library version number "",actual native library version number ""
I/chromium( 6852): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6852): Initializing chromium process, singleProcess=true
W/art     ( 6852): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6852): ApplicationContext is null in ApplicationStatus
W/chromium( 6852): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6852): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6852): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6852): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6852): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6852): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6852): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6852): Remote Branch: 
I/Adreno-EGL( 6852): Local Patches: 
I/Adreno-EGL( 6852): Reconstruct Branch: 
D/Finsky  ( 6884): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6884): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6884): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6884): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3254): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,I/NSApplication( 6852): Starting up...
V/AudioPolicyService(  283): registerClient() client 0xb39a4ec0, uid 10079
W/AudioManagerAndroid( 6852): Requires BLUETOOTH permission
I/ActivityManager(  840): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6959 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  840): Explicit concurrent mark sweep GC freed 57708(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.407ms total 162ms
V/DownloadManager( 3254): created cursor android.database.sqlite.SQLiteCursor@cbcee58 on behalf of 6884
,D/Ads     ( 6884): Skipping gmscore version check
,D/Finsky  ( 6884): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6884): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 6884): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  840): Killing 5923:com.lge.qremote/u0a106 (adj 15): empty #11
,D/Finsky  ( 6884): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
W/libprocessgroup(  840): failed to open /acct/uid_10106/pid_5923/cgroup.procs: No such file or directory
,D/Finsky  ( 6884): [830] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6884): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  840): Killing 6669:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  840): failed to open /acct/uid_10021/pid_6669/cgroup.procs: No such file or directory
,I/ActivityManager(  840): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6986 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  840): Killing 6692:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  840): failed to open /acct/uid_1000/pid_6692/cgroup.procs: No such file or directory
,W/ResourcesManager( 6986): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  840): Killing 6715:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  840): failed to open /acct/uid_10011/pid_6715/cgroup.procs: No such file or directory
,I/ActivityManager(  840): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7010 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 21.621ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 32.950ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 313us total 20.763ms
,I/MusicStore( 7010): Database version: 120
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7010): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7010): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7010): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
V/AlarmManager(  840): ELAPSED_WAKEUP set : Alarm{182a99f8 type 2 when 112661 com.google.android.gms} when 112661
,W/ResourcesManager( 7010): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7010): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7010): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7010): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7010): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@269a49f6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7010): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7010): GMSCore installation verified
,I/ConfigStore( 7010): Config Database version: 1
,I/MediaRouter( 7010): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7010): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7010): type=WIFI subType= reason=null isConnected=true
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/NetworkMonitor( 7010): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  840): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7042 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/AlarmManager(  840): RTC_WAKEUP set : Alarm{37ec553b type 0 when 1452525647388 com.google.android.googlequicksearchbox} when 1452525647388
W/ResourcesManager( 7042): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7042): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7042): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7010): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 7010): Using platform SSLCertificateSocketFactory
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  840): Killing 6743:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  840): failed to open /acct/uid_10038/pid_6743/cgroup.procs: No such file or directory
,I/NotificationManager( 7010): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7042): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7042): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7042): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  840): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7082 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:47.901 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/sensors_hal_Time(  840): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  840): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  840): tsOffsetIs: Apps: 113712589545; DSPS: 3823690; Offset : -2990507242
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/ActivityManager(  840): Process com.google.android.apps.magazines (pid 6852) has died
I/HubEmail( 7042): JNI_OnLoad()
I/HubEmail( 7042): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7042): registerNatives()
I/HubEmail( 7042): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7042): registerNativeMethods()
I/HubEmail( 7042): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 7042): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 7042): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 7082): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7082): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7082): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7082): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7082): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7082): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7082): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7082): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  840): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7108 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7082): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7082): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7082): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7082): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7082): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 7082): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  840): Killing 6769:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  840): failed to open /acct/uid_10051/pid_6769/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7108): onCreate
,W/AppUp4:DB( 7108):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7108):  setFingerPrint start
I/AppUp4:DB( 7108):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7108):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7108):  SDK version = 0
I/AppUp4:DB( 7108):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7108): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7108): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7108): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7108): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7108): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7108): onReceive
I/AppUp4:CustModeStarterReceiver( 7108): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7108): Context : android.app.ReceiverRestrictedContext@1b7752ba
D/AppUp4:CustFacade( 7108): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7108): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7108): begin check event
I/AppUp4:CustModeStarterReceiver( 7108): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7108): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7108): call method handleAsyncCustNotification.
,D/AppUp4:CustModeStarterReceiver( 7108): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7108): handleAsyncCustNotification do not startCustService
I/ActivityManager(  840): Killing 6789:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  840): failed to open /acct/uid_10089/pid_6789/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3141): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3141): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3141): networkInfo.isConnected() = false
I/ActivityManager(  840): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7131 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7131): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7131): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7131): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  840): Killing 6811:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 7131): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  840): failed to open /acct/uid_10061/pid_6811/cgroup.procs: No such file or directory
,V/DownloadManager( 3254): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/TelephonyAutoProfiling( 7131): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7131): [parse] Load xml
V/DownloadManager( 3254): DownloadService onCreate
,V/TelephonyAutoProfiling( 7131): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7131): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/DownloadManager( 3254): in removeSpuriousFiles
I/NotificationManager( 3254): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/CheckinService( 4346): Checkin interval check for package: unspecified last checkin: 1452525614168 min interval config: 0 actual interval: 35047
,V/DownloadManager( 3254): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/PhoneMonitor( 7131): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3254): created cursor android.database.sqlite.SQLiteCursor@2d207bb1 on behalf of 3254
I/DownloadManager( 3254): in trimDatabase
V/DownloadManager( 3254): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3254): created cursor android.database.sqlite.SQLiteCursor@8994c17 on behalf of 3254
I/ActivityManager(  840): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7160 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3254): DownloadService onStartCommand
I/CheckinService( 4346): Checking schedule, now: 1452525649255 next: 1452525644136
I/CheckinService( 4346): active receiver: enabled
V/DownloadManager( 3254): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3254): created cursor android.database.sqlite.SQLiteCursor@271021ed on behalf of 3254
,I/CheckinService( 4346): Preparing to send checkin request
I/EventLogService( 4346): Accumulating logs since 1452525606266
,V/DownloadManager( 3254): DownloadService onDestroy
,D/WeatherAncestor( 2728): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:20:49
,D/UpdateThreadPoolManager( 2728): 2 : This is isUpdating : false
D/WeatherAncestor( 2728): connectivity changed - connection : true
D/Weather_cast( 2728): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2728): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:20:49
D/WeatherService( 2728): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/CheckinRequestBuilder( 4346): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  840): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7183 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  840): getTasks: caller 10074 does not hold GET_TASKS; limiting output
E/ActivityThread( 4346): Failed to find provider info for com.google.android.wearable.settings
,D/Weather.Utils( 2728): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2728): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2728): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7183): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  840): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7201 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/Babel_SMS( 7183): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7183): MmsConfig.loadMmsSettings
W/ResourcesManager( 7201): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7201): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Babel_SMS( 7183): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7183): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7183): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7183): MmsConfig.loadFromResources
E/Babel_SMS( 7183): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7183): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 7183): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7183): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7183): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7183): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7183): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7183): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7183): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7183): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7183): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7183): found sensor: LGE Significant Motion Detector Sensor, handle=47
,D/SensorManager( 7183): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7183): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7183): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7183): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7183): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7183): found sensor: Motion Accel, handle=46
I/art     ( 7183): CheckpointMarkThreadRoots callback created = 0xb042d7f0
,I/MultiDex( 7201): VM with version 2.1.0 has multidex support
I/MultiDex( 7201): install
I/MultiDex( 7201): VM has multidex support, MultiDex support library is disabled.
I/art     ( 7183): CheckpointMarkThreadRoots callback created = 0xb042d7d0
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/art     (  840): Explicit concurrent mark sweep GC freed 15034(746KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.067ms total 160.778ms
,V/JNIHelp ( 7201): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/Settings( 7183): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7183): startup - clean
I/Babel   ( 7183): deleted: false for 0
W/ActivityThread( 7201): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7201): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c46781f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7201): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  840): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7230 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NotificationManager( 7201): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 7201): com.google.android.gms: cancel(39789) by com.google.android.gms
W/AudioCapabilities( 7183): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7183): Unsupported mime audio/adpcm
W/AudioCapabilities( 7183): Unsupported mime audio/g726
,W/AudioCapabilities( 7183): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7183): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7183): Unsupported mime video/mjpg
,W/VideoCapabilities( 7183): Unsupported mime video/theora
W/AudioCapabilities( 7183): Unsupported mime audio/evrc
,W/AudioCapabilities( 7183): Unsupported mime audio/qcelp
W/VideoCapabilities( 7183): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7183): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7183): Unsupported mime audio/qcelp
W/AudioCapabilities( 7183): Unsupported mime audio/evrc
W/VideoCapabilities( 7183): Unsupported mime video/mp4v-esdp
,I/art     ( 7201): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7201): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/VideoCapabilities( 7183): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 7183): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7183): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7183): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7183): Unrecognized profile 2130706433 for video/avc
I/jxcore-log( 6385): Test app app.js loaded
I/jxcore-log( 6385): 
I/ActivityManager(  840): Process com.android.vending (pid 6884) has died
,I/vclib   ( 7183): onServiceConnected
W/Babel   ( 7183): Attempted to change video mute state without an active call.
,I/chromium( 6385): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/NotificationManager( 7183): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 7183): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7183): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7183): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7183): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  279): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 7183): propertyValue:false
I/Babel   ( 7183): connection state changed from UNKNOWN to CONNECTED
,D/NativeLibraryUtils( 7201): Install completed successfully. count=14 extracted=0
,I/MusicWidget( 2687): mDelayedStopHandler : unbind
I/MusicBrowser( 2764): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2764): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2764): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2764): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2764): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2764): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2764): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2764): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:20:50.91 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/MediaFocusControl(  840):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@12142f5bcom.lge.music.MediaPlaybackService$6@146813f8
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/MusicBrowser( 2764): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2764): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@37b7e086
I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2764): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2764): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2764): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2764): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2764): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2764): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2764): reset
V/MediaPlayer[Native]( 2764): setListener
V/MediaPlayer[Native]( 2764): disconnect
,V/MediaPlayer[Native]( 2764): destructor
V/AudioFlinger(  283): releasing 19 from 2764 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
V/MediaPlayer[Native]( 2764): disconnect
D/MusicBrowser( 2764): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
D/WVCdm   (  283): Instantiating CDM.
,I/WVCdm   (  283): CdmEngine::OpenSession
I/WVCdm   (  283): Level3 Library Dec 11 2014 16:13:16
I/SmartShareClient( 2764): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2764): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2764): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2764): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2764): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2764): [SmartShareManagerClient] unregisterListener: 271990993
W/SmartShareClient( 2764): [SmartShareManagerClient] unregisterListener invalid listener: 271990993
I/SmartShareClient( 2764): [SmartShareManagerClient] terminate service: 2764/MediaPlaybackService/99941084
E/HomeCloudIF( 2764): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2764): [SmartShareManagerClient] unbindService context:android.app.Application@217f7736
V/CloudHub( 2764): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2764): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2764): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2764): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2764): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7230): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/ActivityManager(  840): Killing 6959:com.android.chrome/u0a48 (adj 15): empty #11
W/WVCdm   (  283): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  283): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  283): L1 library not specified. Falling Back to L3
I/CloudHub( 2764): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29991
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7230): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7230): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7230):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7230):   adb logcat -s GAv4
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7230): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7230): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
D/WVCdm   (  283): PrepareKeyRequest: nonce=3496856274
W/libprocessgroup(  840): failed to open /acct/uid_10048/pid_6959/cgroup.procs: No such file or directory
,W/GAv4    ( 7230): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7230): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/GAv4    ( 7230): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7230): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/dex2oat ( 7275): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/LibraryLoader( 7230): Time to load native libraries: 2 ms (timestamps 7326-7328)
,I/LibraryLoader( 7230): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7230): Binding Chromium to main looper Looper (main, tid 1) {3b03a70f}
I/LibraryLoader( 7230): Expected native library version number "",actual native library version number ""
I/chromium( 7230): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7230): Initializing chromium process, singleProcess=true
,W/art     ( 7230): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7230): ApplicationContext is null in ApplicationStatus
W/chromium( 7230): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7230): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7230): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7230): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7230): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7230): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7230): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7230): Remote Branch: 
I/Adreno-EGL( 7230): Local Patches: 
I/Adreno-EGL( 7230): Reconstruct Branch: 
I/dex2oat ( 7275): dex2oat took 154.931ms (threads: 4)
,I/art     ( 7201): CheckpointMarkThreadRoots callback created = 0xb0448e40
I/Adreno-EGL( 7201): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7201): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7201): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7201): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7201): Remote Branch: 
I/Adreno-EGL( 7201): Local Patches: 
I/Adreno-EGL( 7201): Reconstruct Branch: 
,I/art     ( 7201): CheckpointMarkThreadRoots callback created = 0xb0448e30
,V/AudioPolicyService(  283): registerClient() client 0xb39a4dc0, uid 10079
,W/AudioManagerAndroid( 7230): Requires BLUETOOTH permission
I/NSApplication( 7230): Starting up...
,I/ActivityManager(  840): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7300 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  840): Killing 6986:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  840): failed to open /acct/uid_10086/pid_6986/cgroup.procs: No such file or directory
,I/ActivityManager(  840): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7322 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  840): Killing 7010:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  840): failed to open /acct/uid_10081/pid_7010/cgroup.procs: No such file or directory
,W/ResourcesManager( 7322): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  840): Killing 7042:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  840): failed to open /acct/uid_10021/pid_7042/cgroup.procs: No such file or directory
,I/WVCdm   (  283): CdmEngine::OpenSession
,I/ActivityManager(  840): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7354 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 24.264ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.204ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 20.469ms
,I/MusicStore( 7354): Database version: 120
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7354): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7354): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7354): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,W/ResourcesManager( 7354): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7354): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7354): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/WVCdm   (  283): CdmEngine::CloseSession
I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
D/WVCdm   (  283): PrepareKeyRequest: nonce=3682520701
W/ActivityThread( 7354): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7354): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@269a49f6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7354): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7354): GMSCore installation verified
I/ConfigStore( 7354): Config Database version: 1
,I/art     ( 5770): Explicit concurrent mark sweep GC freed 1693(60KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 394us total 42.134ms
,I/MediaRouter( 7354): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7354): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7354): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7354): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  840): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7386 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7354): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7354): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 7386): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7386): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7386): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  840): Killing 7082:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  840): failed to open /acct/uid_1000/pid_7082/cgroup.procs: No such file or directory
,I/NotificationManager( 7354): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7386): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7386): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7386): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  840): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7416 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/HubEmail( 7386): JNI_OnLoad()
I/HubEmail( 7386): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7386): registerNatives()
I/HubEmail( 7386): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7386): registerNativeMethods()
I/HubEmail( 7386): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7386): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  840): Killing 7108:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  840): failed to open /acct/uid_10011/pid_7108/cgroup.procs: No such file or directory
,W/Settings( 7386): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7416): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7416): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7416): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7416): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7416): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7416): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7416): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7416): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  840): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7440 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7416): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7416): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7416): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7416): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7416): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7416): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  840): Killing 7131:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  840): failed to open /acct/uid_10038/pid_7131/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 7440): onCreate
,W/AppUp4:DB( 7440):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7440):  setFingerPrint start
I/AppUp4:DB( 7440):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7440):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7440):  SDK version = 0
I/AppUp4:DB( 7440):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7440): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7440): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7440): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7440): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7440): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7440): onReceive
I/AppUp4:CustModeStarterReceiver( 7440): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 7440): Context : android.app.ReceiverRestrictedContext@1b7752ba
D/AppUp4:CustFacade( 7440): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7440): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7440): begin check event
I/AppUp4:CustModeStarterReceiver( 7440): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7440): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7440): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7440): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7440): handleAsyncCustNotification do not startCustService
I/ActivityManager(  840): Killing 7160:com.lge.drmservice/u0a51 (adj 15): empty #11
I/LgeMiscReceiver( 3141): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3141): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3141): networkInfo.isConnected() = true
W/libprocessgroup(  840): failed to open /acct/uid_10051/pid_7160/cgroup.procs: No such file or directory
,D/PhoneState( 3141): setPdpRejectCasuse : false
I/ActivityManager(  840): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7459 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7459): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7459): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7459): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  840): Killing 7183:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 7459): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7459): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7459): [parse] Load xml
V/TelephonyAutoProfiling( 7459): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7459): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 7459): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,W/libprocessgroup(  840): failed to open /acct/uid_10061/pid_7183/cgroup.procs: No such file or directory
,V/DownloadManager( 3254): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3254): DownloadService onCreate
I/DownloadManager( 3254): in removeSpuriousFiles
,I/NotificationManager( 3254): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3254): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3254): created cursor android.database.sqlite.SQLiteCursor@1fdc92b3 on behalf of 3254
I/DownloadManager( 3254): in trimDatabase
V/DownloadManager( 3254): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3254): created cursor android.database.sqlite.SQLiteCursor@10d9efe9 on behalf of 3254
,I/ActivityManager(  840): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7481 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3254): DownloadService onStartCommand
I/CheckinService( 4346): Checkin interval check for package: unspecified last checkin: 1452525614168 min interval config: 0 actual interval: 40973
,V/DownloadManager( 3254): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3254): created cursor android.database.sqlite.SQLiteCursor@3b03a70f on behalf of 3254
,V/DownloadManager( 3254): DownloadService onDestroy
,I/ActivityManager(  840): Killing 7230:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,I/WVCdm   (  283): CdmEngine::CloseSession
,I/WVCdm   (  283): L3 Terminate.
I/Adreno-EGL( 7201): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7201): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7201): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7201): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7201): Remote Branch: 
I/Adreno-EGL( 7201): Local Patches: 
I/Adreno-EGL( 7201): Reconstruct Branch: 
I/Adreno-EGL( 7201): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7201): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7201): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7201): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7201): Remote Branch: 
I/Adreno-EGL( 7201): Local Patches: 
I/Adreno-EGL( 7201): Reconstruct Branch: 
,D/WeatherAncestor( 2728): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:20:55
W/libprocessgroup(  840): failed to open /acct/uid_10079/pid_7230/cgroup.procs: No such file or directory
,D/UpdateThreadPoolManager( 2728): 2 : This is isUpdating : false
D/WeatherAncestor( 2728): connectivity changed - connection : true
D/Weather_cast( 2728): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2728): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:20:55
D/WeatherService( 2728): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  840): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7502 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  840): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2728): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2728): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2728): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/CheckinRequestBuilder( 4346): Classify the device as Phone.
,W/ResourcesManager( 7502): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/libc-netbsd( 4346): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4346): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4346): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4346): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 4346): propertyValue:false
D/libc-netbsd( 4346): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4346): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4346): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4346): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4346): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4346): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4346): Sending checkin request (9785 bytes)
,I/Babel_SMS( 7502): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7502): MmsConfig.loadMmsSettings
,I/art     (  840): Explicit concurrent mark sweep GC freed 17288(834KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.886ms total 148.351ms
,I/Babel_SMS( 7502): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7502): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7502): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7502): MmsConfig.loadFromResources
E/Babel_SMS( 7502): canonicalizeMccMnc: invalid mccmnc nullnull
I/art     ( 7502): CheckpointMarkThreadRoots callback created = 0xaaf23f20
,I/Babel_SMS( 7502): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7502): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7502): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7502): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 7502): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7502): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7502): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7502): found sensor: LGE Rotation Vector Sensor, handle=36
,D/SensorManager( 7502): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7502): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7502): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7502): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7502): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7502): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7502): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7502): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7502): found sensor: Motion Accel, handle=46
I/art     ( 7502): CheckpointMarkThreadRoots callback created = 0xaaf23f10
,W/Settings( 7502): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7502): startup - clean
I/Babel   ( 7502): deleted: false for 0
,I/ActivityManager(  840): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7542 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7502): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7502): Unsupported mime audio/adpcm
W/AudioCapabilities( 7502): Unsupported mime audio/g726
W/AudioCapabilities( 7502): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7502): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7502): Unsupported mime video/mjpg
W/VideoCapabilities( 7502): Unsupported mime video/theora
,W/AudioCapabilities( 7502): Unsupported mime audio/evrc
W/AudioCapabilities( 7502): Unsupported mime audio/qcelp
W/VideoCapabilities( 7502): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7502): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7502): Unsupported mime audio/qcelp
W/AudioCapabilities( 7502): Unsupported mime audio/evrc
W/VideoCapabilities( 7502): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7502): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7502): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7502): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7502): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7502): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7502): onServiceConnected
,W/Babel   ( 7502): Attempted to change video mute state without an active call.
I/NotificationManager( 7502): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7502): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7502): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7502): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7502): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  279): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 7502): propertyValue:false
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7542): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/CheckinRequestBuilder( 4346): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4346): Failed to find provider info for com.google.android.wearable.settings
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7542): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7542): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7542):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7542):   adb logcat -s GAv4
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
I/Babel   ( 7502): connection state changed from UNKNOWN to CONNECTED
W/ContextImpl( 7542): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7542): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7542): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  840): Killing 2764:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  283): 2764 died, releasing its sessions
V/AudioFlinger(  283):  pid 1750 @ 0
,V/AudioFlinger(  283):  pid 3141 @ 1
V/AudioFlinger(  283):  pid 3141 @ 2
W/GAv4    ( 7542): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7542): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/libprocessgroup(  840): failed to open /acct/uid_10028/pid_2764/cgroup.procs: No such file or directory
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4346): Classify the device as Phone.
,I/CheckinTask( 4346): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4346): Checking schedule, now: 1452525656657 next: 1453052905649
I/CheckinService( 4346): active receiver: disabled
,I/CheckinService( 4346): Checking schedule, now: 1452525656688 next: 1453052905649
,I/CheckinService( 4346): active receiver: disabled
,D/CheckinService( 4346): Recording last checkin time for package unspecified as 1452525656697
I/ActivityManager(  840): Killing 7300:com.android.chrome/u0a48 (adj 15): empty #11
,I/WebViewFactory( 7542): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/libprocessgroup(  840): failed to open /acct/uid_10048/pid_7300/cgroup.procs: No such file or directory
,I/LibraryLoader( 7542): Time to load native libraries: 3 ms (timestamps 2631-2634)
I/LibraryLoader( 7542): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7542): Binding Chromium to main looper Looper (main, tid 1) {3b03a70f}
I/LibraryLoader( 7542): Expected native library version number "",actual native library version number ""
I/chromium( 7542): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7542): Initializing chromium process, singleProcess=true
,W/art     ( 7542): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7542): ApplicationContext is null in ApplicationStatus
W/chromium( 7542): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7542): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7542): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7542): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7542): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7542): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7542): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7542): Remote Branch: 
I/Adreno-EGL( 7542): Local Patches: 
I/Adreno-EGL( 7542): Reconstruct Branch: 
V/AudioPolicyService(  283): registerClient() client 0xb39a4ce0, uid 10079
,I/NSApplication( 7542): Starting up...
W/AudioManagerAndroid( 7542): Requires BLUETOOTH permission
I/ActivityManager(  840): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7612 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  840): Killing 7354:com.google.android.music:main/u0a81 (adj 15): empty #11
I/ActivityManager(  840): Killing 7322:com.google.android.apps.plus/u0a86 (adj 15): empty #12
,W/libprocessgroup(  840): failed to open /acct/uid_10081/pid_7354/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_10086/pid_7322/cgroup.procs: No such file or directory
I/ActivityManager(  840): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7636 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  840): Killing 7386:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  840): failed to open /acct/uid_10021/pid_7386/cgroup.procs: No such file or directory
,W/ResourcesManager( 7636): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  840): Killing 7416:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  840): failed to open /acct/uid_1000/pid_7416/cgroup.procs: No such file or directory
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  840): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7663 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7663): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  840): Message: 20
D/BluetoothManagerService(  840): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38e3ff72:true
,D/BluetoothAdapterService(401882465)( 2032): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@26b4ee3f
D/BluetoothAdapterService(401882465)( 2032): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@26b4ee3f
,I/ActivityManager(  840): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7682 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 23.076ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 20.377ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 20.486ms
,V/LGMDMManager( 7663): Create singleton instance
D/UEI.SmartControl( 7682): Quickset Services start...
,I/UEI.SmartControl( 7682): Manufacture = LGE
D/UEI.SmartControl( 7682): File observer start...
E/UEI.SmartControl( 7682): IR Port is disabled: false
D/UEI.SmartControl( 7682): Starting file observer...
D/UEI.SmartControl( 7682): Extracting JNI libs...
D/UEI.SmartControl( 7682): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7663): getMode name:com.lge.qremote
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
I/CheckinService( 4346): Checkin interval check for package: unspecified last checkin: 1452525656697 min interval config: 0 actual interval: 1460
I/CheckinService( 4346): Checking schedule, now: 1452525658170 next: 1453052905649
I/CheckinService( 4346): active receiver: disabled
,D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 1731): propertyValue:false
D/WearableService( 1731): callingUid 10006, callindPid: 1731
D/UEI.SmartControl( 7682): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7682): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7682): --- Extracting JNI libs: libqs_armeabi-v7a.zip
E/MDM     ( 1731): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 4346): Restart initialization of location
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/ContextImpl( 3728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/UEI.SmartControl( 7682): --- Selecting new region: 2
I/UEI.SmartControl( 7682): -- Running on KitKat(19) and above! JNI will be used.
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/UEI.SmartControl( 7682): Platform has CIR...
D/UEI.SmartControl( 7682): NO CIR support, need to check package...
I/UEI.SmartControl( 7682): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7682): QS Service created
E/UEI.SmartControl( 7682): QS start get config
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/UEI.SmartControl( 7682): Loading JNI Libs...
,I/art     ( 1731): Explicit concurrent mark sweep GC freed 33515(2MB) AllocSpace objects, 16(256KB) LOS objects, 40% free, 13MB/22MB, paused 1.905ms total 118.693ms
D/UEI.SmartControl( 7682):  configuring local db...
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  840): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=7729 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
,I/MusicStore( 7729): Database version: 120
,D/UEI.SmartControl( 7682):  ---- Has DB8: true
,D/UEI.SmartControl( 7682): QS start statue = true Error code = 0
D/UEI.SmartControl( 7682): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7682): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7682): IRRCDataComm has AudioManager!!!!.
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/irrc_jni( 7682): IRRCPlayer_nativeInit ++ 
W/ContextImpl( 7729): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/irrcClient( 7682): IrrcClient ++ 
D/irrcClient( 7682): getIrrcService ++ 
D/irrcClient( 7682): getIrrcService -- 
D/irrcClient( 7682): IrrcClient -- 
W/irrc_jni( 7682): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7682): Services init done
,I/UEI.SmartControl( 7682): Device manager: loading config....
D/UEI.SmartControl( 7682): QS Service init finished
D/UEI.SmartControl( 7682): QS Service version name: 0.1.73
D/UEI.SmartControl( 7682): QS Service version code: 1073
D/UEI.SmartControl( 7682): Service requested: Control
D/UEI.SmartControl( 7682): Config is loaded...
D/UEI.SmartControl( 7682):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 7682): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7682): Internal service binding...
I/UEI.SmartControl( 7682): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7682): -----IControl: 11
D/UEI.SmartControl( 7682): Caller: com.lge.qremote
D/UEI.SmartControl( 7682): ------------ IControl registerCallback...
I/UEI.SmartControl( 7682): Registering callback...
D/UEI.SmartControl( 7682): -----IControl: 19
D/UEI.SmartControl( 7682): Caller: com.lge.qremote
I/UEI.SmartControl( 7682): Registering Services Ready callback...
I/UEI.SmartControl( 7682): Notify client services are ready...
,D/UEI.SmartControl( 7682): -----IControl: 8
D/UEI.SmartControl( 7682): Caller: com.lge.qremote
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7729): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7729): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7729): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7729): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7729): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7729): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7729): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@269a49f6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7729): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7729): GMSCore installation verified
I/ConfigStore( 7729): Config Database version: 1
,I/MediaRouter( 7729): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 7729): type=WIFI subType= reason=null isConnected=true
,I/art     ( 7729): CheckpointMarkThreadRoots callback created = 0xb042d390
,I/NetworkMonitor( 7729): type=WIFI subType= reason=null isConnected=true
,I/art     ( 7729): CheckpointMarkThreadRoots callback created = 0xb042d350
,I/art     (  840): Explicit concurrent mark sweep GC freed 15013(755KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.549ms total 172.054ms
,I/ActivityManager(  840): Process com.google.android.apps.magazines (pid 7542) has died
,I/[SystemUI]QPairHandler( 1367): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1367): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1367): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1367): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/InputReader(  840): Reconfiguring input devices.  changes=0x00000010
,V/SetupWizard( 7459): Connected to Gservices successfully
I/MusicLeanback( 7729): Stop autocaching.
I/MusicLeanback( 7729): Stop autocaching.
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/MusicLeanback( 7729): Stop autocaching.
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/AudioManager( 7663): getMode name:com.lge.qremote
,I/GHttpClientFactory( 7729): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 7729): Using platform SSLCertificateSocketFactory
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/MusicLeanback( 7729): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 7729): Stop autocaching.
D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/administrator(  840): Handling package changes for user 0
,I/NotificationManager( 7729): com.google.android.music: cancel(1061) by com.google.android.music
,E/GmsUtils( 7729): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7729): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/AudioManager( 7663): getMode name:com.lge.qremote
,I/AppUp4:CustModeStarterReceiver( 7440): onReceive
I/AppUp4:CustModeStarterReceiver( 7440): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7440): Context : android.app.ReceiverRestrictedContext@1b7752ba
D/AppUp4:CustFacade( 7440): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7440): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7440): begin check event
I/AppUp4:CustModeStarterReceiver( 7440): Event For Nothing, skip.
W/ResourcesManager( 7502): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7502): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  840): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7794 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ActivityManager(  840): Process com.google.android.apps.plus (pid 7636) has died
,I/NotificationManager( 7502): com.google.android.talk: cancel(8) by com.google.android.talk
I/NotificationService(  840): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  840): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  840): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/ResourcesManager( 7794): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7794): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7794): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/BackupManagerService(  840): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  840): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  840): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@28e0e7fa
V/JNIHelp ( 7502): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1785): getDefaultRoute
W/ResourcesManager(  840): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PowerManagerServiceEx(  840): acquireWakeLockInternal: lock=1031127969, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=840
D/WeatherService( 2728): 2 : TimeTick Intent has been received, Time(hour:min:sec) 16:21:0
,D/WeatherService( 2728): 2 : TimeTick Intent And Screen On
D/WeatherService( 2728): 2 : SDK version : 21
W/ActivityManager(  840): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2728): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2728): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2728): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2728): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2728): 2 : This is isUpdating : false
D/WeatherService( 2728): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2728): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2728): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2728): 2 : Fixed theme : optimus
D/WeatherReflect( 2728): 2 : Map key string is -2
,W/System  ( 7502): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7502): Installed default security provider GmsCore_OpenSSL
D/lim     ( 2728): 2 : time = 16:21
,I/[SystemUI]TimeTickManager( 1367): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1367): called onTimeUpdated()
I/WeatherReflect( 2728): Model Name : LG-D722
D/WeatherTheme( 2728): 2 : Different view - status_min_formatted : 20 != 21
D/WeatherTheme( 2728): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2728): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2728): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2728): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[SystemUI]Clock( 1367): called onTimeUpdated()
I/LgeClockWidgetControlView( 1367): called onTimeUpdated()
,I/[SystemUI]DateView( 1367): called onTimeUpdated()
I/[SystemUI]DateView( 1367): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1367): handleTimeUpdate
D/Weather4x2_optimus( 2728): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2728): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2728): forecast size is 0
,D/Theme   ( 2728): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2728): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2728): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2728): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2728): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2728): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2728): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2728): url is : null
D/Theme   ( 2728): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2728): 2 : update view, appWidgetId: 2
D/WeatherService( 2728): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 16:21:0
,D/PowerManagerServiceEx(  840): releaseWakeLockInternal: lock=1031127969 [*alarm*], flags=0x0
I/ActivityManager(  840): Process com.android.chrome (pid 7612) has died
,I/AppConfig( 7794): Total System Memory = 906309632
,I/GalleryUtils( 7794): Application Heap = 96 MB
I/AppConfig( 7794): App Tier : NOT_DEF
W/ResourceType(  840): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/SystemHelper( 7794): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  840): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7815 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/GCoreNlp( 1731): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  840): applying state to connected service
,W/ResourcesManager( 7815): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7815): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7815): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7815): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7815): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/SystemConfig( 7815): BUILD Country: EU
,I/SystemConfig( 7815): BUILD Operator: OPEN
,I/ActivityManager(  840): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7838 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7815): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7815): existFile = false
I/SystemConfig( 7815): canReadFile = false
I/SystemConfig( 7815): systemFeature RCS result false
D/SystemConfig( 7815): refreshRcsSupport() :false
,I/LockScreenSettings( 7838): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7838): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7838): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7838): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7838): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7838): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  840): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7863 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  840): Killing 7481:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  840): failed to open /acct/uid_10051/pid_7481/cgroup.procs: No such file or directory
,W/ResourcesManager( 7863): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1933): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  840): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7891 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  840): Killing 7729:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1933): UpdateCorporaTask done [took 108 ms] updated apps [took 108 ms] 
,W/libprocessgroup(  840): failed to open /acct/uid_10081/pid_7729/cgroup.procs: No such file or directory
,V/AlarmManager(  840): ELAPSED_WAKEUP set : Alarm{25929bd type 2 when 127024 com.google.android.gms} when 127024
,D/charger_monitor(  491): init target 500000
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1367): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1367): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1367): On Skip Timer : true
D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1367): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2032): Disconnected process message: 10, size: 0
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1367): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
D/WifiController(  840): battery changed pluggedType: 2
W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]BatterySaverHandler( 1367): onReceive = android.intent.action.BATTERY_CHANGED
D/charger_monitor(  491): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/Finsky  ( 7891): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7891): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7891): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7891): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7891): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3254): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3254): created cursor android.database.sqlite.SQLiteCursor@1058a1a5 on behalf of 7891
D/Finsky  ( 7891): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7891): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7891): Skipping gmscore version check
D/Finsky  ( 7891): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/AudioManager( 7663): getMode name:com.lge.qremote
,D/PackageBroadcastService( 4346): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/Finsky  ( 7891): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/PackageBroadcastService( 4346): Null package name or gms related package.  Ignoreing.
I/Icing   ( 4346): updateResources: need to parse f{com.google.android.gms}
,I/AudioManager( 7663): getMode name:com.lge.qremote
,I/AudioManager( 7663): getMode name:com.lge.qremote
I/AudioManager( 7663): getMode name:com.lge.qremote
I/ActivityManager(  840): Killing 7459:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  840): failed to open /acct/uid_10038/pid_7459/cgroup.procs: No such file or directory
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/Icing   ( 4346): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4346): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  840): Killing 7440:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  840): failed to open /acct/uid_10011/pid_7440/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7682): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  840): Killing 7502:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  840): failed to open /acct/uid_10061/pid_7502/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:21:05.978 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  840): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  840): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  840): tsOffsetIs: Apps: 133713288443; DSPS: 4479073; Offset : -2990510275
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:21:08.991 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:21:12.023 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/AlarmManager(  840): ELAPSED_WAKEUP set : Alarm{4dc96f3 type 2 when 140547 com.google.android.gms} when 140547
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:21:15.035 DNS addrs= 192.168.1.1, 0.0.0.0, 
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/VacuumService( 1731): Vacuum at: now=1452525675058 tag=VacuumService
,I/art     (  840): Explicit concurrent mark sweep GC freed 37750(1790KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.487ms total 179.669ms
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:21:21.07 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/PowerManagerService(  840): ALS enabled for SRE
D/PowerManagerServiceEx(  840): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (27057 ms ago)
,D/qdlights(  840): set_light_backlight: 253
,D/qdlights(  840): set_light_backlight: 250
D/qdlights(  840): set_light_backlight: 246
,D/qdlights(  840): set_light_backlight: 243
,D/qdlights(  840): set_light_backlight: 240
,D/qdlights(  840): set_light_backlight: 236
,D/qdlights(  840): set_light_backlight: 233
,D/qdlights(  840): set_light_backlight: 230
,D/qdlights(  840): set_light_backlight: 226
,D/qdlights(  840): set_light_backlight: 223
,D/qdlights(  840): set_light_backlight: 220
,D/qdlights(  840): set_light_backlight: 216
,D/qdlights(  840): set_light_backlight: 213
,D/qdlights(  840): set_light_backlight: 210
,D/qdlights(  840): set_light_backlight: 206
,D/qdlights(  840): set_light_backlight: 203
,D/qdlights(  840): set_light_backlight: 200
,D/qdlights(  840): set_light_backlight: 196
,D/qdlights(  840): set_light_backlight: 193
,D/qdlights(  840): set_light_backlight: 190
,D/qdlights(  840): set_light_backlight: 186
,D/qdlights(  840): set_light_backlight: 183
,D/qdlights(  840): set_light_backlight: 180
,D/qdlights(  840): set_light_backlight: 176
,D/qdlights(  840): set_light_backlight: 173
,D/qdlights(  840): set_light_backlight: 170
,D/qdlights(  840): set_light_backlight: 166
,D/qdlights(  840): set_light_backlight: 163
,D/qdlights(  840): set_light_backlight: 160
,D/qdlights(  840): set_light_backlight: 156
,D/qdlights(  840): set_light_backlight: 153
,D/qdlights(  840): set_light_backlight: 150
,D/qdlights(  840): set_light_backlight: 146
,D/qdlights(  840): set_light_backlight: 143
,D/qdlights(  840): set_light_backlight: 140
,D/qdlights(  840): set_light_backlight: 136
,D/qdlights(  840): set_light_backlight: 133
,D/qdlights(  840): set_light_backlight: 130
,D/qdlights(  840): set_light_backlight: 126
,D/qdlights(  840): set_light_backlight: 123
,D/qdlights(  840): set_light_backlight: 120
,D/qdlights(  840): set_light_backlight: 116
,D/qdlights(  840): set_light_backlight: 113
,D/qdlights(  840): set_light_backlight: 110
,D/qdlights(  840): set_light_backlight: 106
,D/qdlights(  840): set_light_backlight: 103
,D/qdlights(  840): set_light_backlight: 100
,D/qdlights(  840): set_light_backlight: 96
,D/qdlights(  840): set_light_backlight: 93
,D/qdlights(  840): set_light_backlight: 90
,D/qdlights(  840): set_light_backlight: 86
,D/qdlights(  840): set_light_backlight: 83
,D/qdlights(  840): set_light_backlight: 80
,D/qdlights(  840): set_light_backlight: 76
,D/qdlights(  840): set_light_backlight: 73
,D/qdlights(  840): set_light_backlight: 70
,D/qdlights(  840): set_light_backlight: 66
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  840): set_light_backlight: 63
,D/qdlights(  840): set_light_backlight: 60
,D/qdlights(  840): set_light_backlight: 56
,D/qdlights(  840): set_light_backlight: 53
,D/qdlights(  840): set_light_backlight: 50
,D/qdlights(  840): set_light_backlight: 46
,D/qdlights(  840): set_light_backlight: 43
,D/qdlights(  840): set_light_backlight: 40
,D/qdlights(  840): set_light_backlight: 36
,D/qdlights(  840): set_light_backlight: 33
,D/qdlights(  840): set_light_backlight: 30
,D/qdlights(  840): set_light_backlight: 26
,D/qdlights(  840): set_light_backlight: 23
,D/qdlights(  840): set_light_backlight: 20
,D/qdlights(  840): set_light_backlight: 16
,D/qdlights(  840): set_light_backlight: 13
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
D/qdlights(  840): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:21:24.087 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  840): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  840): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  840): tsOffsetIs: Apps: 153714044686; DSPS: 5134458; Offset : -2990516684
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  840): ALS enabled for SRE
D/PowerManagerServiceEx(  840): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (34053 ms ago)
I/PowerManagerService(  840): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  840): ALS enabled for SRE
D/PowerManagerServiceEx(  840): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (34066 ms ago)
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  840): Sleeping (uid 1000)...
D/LPWGController(  840): [updateScreenState] screen on = false
D/LPWGController(  840): disable proximity sensor
,D/LPWGController(  840): enable proximity sensor
I/SensorManager(  840): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@1b494c8] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  840): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  840): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  840): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  840): activate: handle is 48, enable
,V/sensors_hal_Ctx(  840): activate sensors is 1400000000000
D/sensors_hal_Thresh(  840): enable: handle=48
I/sensors_hal_SAM(  840): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  840): waitForResponse: timeout=1000
V/sensors_hal_SAM(  840): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  840): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  840): enable: Received response: 0
D/PowerManagerServiceEx(  840): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (34114 ms ago)
I/Adreno-EGL(  840): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  840): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  840): Build Date: 03/02/15 Mon
I/Adreno-EGL(  840): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  840): Remote Branch: 
I/Adreno-EGL(  840): Local Patches: 
I/Adreno-EGL(  840): Reconstruct Branch: 
,D/PermissionCache(  248): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (223 us)
,I/Sensors (  433): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  840): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,I/sensors_hal_SAM(  840): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  840): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  840): processInd: handle 48, count=1
V/sensors_hal_Thresh(  840): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  840): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  840): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  840): poll: count: 256
I/sensors_hal_Ctx(  840): poll: released wakelock sensor_ind
D/sensors_hal_Util(  840): waitForResponse: timeout=0
D/LPWGController(  840): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  840): current mode = 1  value = 1 1
I/LPWGController(  840): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  840): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  840): set_light_backlight: 0
,I/SensorManager(  840): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  840): activate: handle is 46, disable
V/sensors_hal_Ctx(  840): activate sensors is 1000000000000
D/sensors_hal_LP2(  840): enable: handle=46
D/sensors_hal_LP2(  840): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  840): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  248): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  248): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  840): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/sensors_hal_SAM(  840): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  840): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
V/ActivityManager(  840): Display changed displayId=0
,D/DSDPConnection( 1750): Display #0 changed.
,D/qdhwcomposer(  248): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  840): Excessive delay in setPowerMode(): 230ms
,I/qdhwcomposer(  248): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  840): Got set_interactive hint
D/KeyguardViewMediator( 1367): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1330): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1367): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1330): notifyScreenOffLocked
D/SmartCoverViewMediator( 1330): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1367): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1367): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1367): unregisterProximitySensor
,D/StatusBarWindowView( 1367): onScreenTurnedOff why = 3
,D/WifiServerServiceExt(  840): sendKtScanInterval  mRtspPlay : false
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=on, calling pid 840
,I/WifiServerServiceExt(  840): set CMD_KT_SCAN_INTERVAL
D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: enter: screen_state=on
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: exit
V/voice   (  283): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  283): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  283): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  283): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  283): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  283): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1367): handleTimeUpdate
,I/Sensors (  433): sns_pwr.c(301):releasing wakelock
,D/GpsLocationProvider(  840): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1367): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1838): |CORE| sendScreenState: state:true
I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1801): stopPatternFlashing()
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): updateLightsLocked : turn off led
,D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1801): RESTART MSG
D/SplitWindow(  840): check instance of lgWin Window{1e9c3947 u0 SearchPanel}
,I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/Cliptray Service( 1801): lockStatus = 0
D/InputDispatcher(  840): Window went away: Window{e51a75a u0 SearchPanel}
,I/[SystemUI]Clock( 1367): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1367): time changed, timezoneChanged : false
,D/LNfcService( 1785): action : android.intent.action.SCREEN_ON
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
,D/Ulp_jni (  840): JNI:system_update. Event-0
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  840): ACTION_SCREEN_ON
,D/WeatherService( 2728): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:21:30
D/WeatherService( 2728): 2 : ACTION screen on
D/WeatherService( 2728): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2728): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2728): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:21:30
,D/AppCleanupService( 4203): android.intent.action.SCREEN_ON
,V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=off, calling pid 840
D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=off
,V/voice   (  283): voice_set_parameters: enter: screen_state=off
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: exit
V/voice   (  283): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  283): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  283): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  283): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  283): adev_set_parameters: exit with code(0)
D/WifiController(  840): CMD_SCREEN_OFF 
D/WifiController(  840): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  840): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1367): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1838): |CORE| sendScreenState: state:false
,I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1801): stopPatternFlashing()
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1801): clear
I/LEDService( 1801): updateLightsLocked : turn on led
E/LEDService( 1801): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1801): Can't handle this request of patternId:0
D/LEDHandler( 1801): RESTART MSG
I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1785): action : android.intent.action.SCREEN_OFF
,D/NfcServiceNXP( 1785): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1875): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  840): ACTION_SCREEN_OFF
D/WeatherService( 2728): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:21:30
D/WeatherService( 2728): 2 : ACTION screen off
D/WeatherService( 2728): 2 : TimeTick Receiver Unregister
D/WeatherService( 2728): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:21:30
D/AppCleanupService( 4203): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4203): AppUsageStatsSaveTask
E/NxpNfcJni( 1785): getReconnectState = 0x0
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1785): getDefaultRoute
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
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1367): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  840): ELAPSED_WAKEUP set : Alarm{35e23574 type 2 when 160016 com.android.systemui} when 160016
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1750): getCallState : 0
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1367): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1367): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  840): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  840): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  840): tsOffsetIs: Apps: 173714826761; DSPS: 5789843; Offset : -2990497913
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1367): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1367): called onTimeUpdated()
I/[SystemUI]Clock( 1367): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1367): called onTimeUpdated()
I/[SystemUI]DateView( 1367): called onTimeUpdated()
I/[SystemUI]DateView( 1367): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1367): handleTimeUpdate
D/PowerManagerServiceEx(  840): acquireWakeLockInternal: lock=1031127969, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=840
,V/AlarmManager(  840): ELAPSED_WAKEUP set : Alarm{29524a9d type 2 when 186188 com.google.android.gms} when 186188
,D/PowerManagerServiceEx(  840): releaseWakeLockInternal: lock=1031127969 [*alarm*], flags=0x0
,I/ClearcutLoggerApiImpl( 1731): disconnect managed GoogleApiClient
,I/PhenotypeConfigurator( 1731): Scheduling Phenotype for one-off execution 10374 seconds from now (1452525720729)
,D/GetConfigurationSnapshotOperation( 1731): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1731): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1731): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  840): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 1731): propertyValue:false
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/charger_monitor(  491): init target 500000
I/[SystemUI]LGPowerUI( 1367): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1367): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1367): On Skip Timer : true
D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1367): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1367): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/[SystemUI]BatterySaverHandler( 1367): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2032): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  840): battery changed pluggedType: 2
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LocationManagerService(  840): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  840): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  840): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  840): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  840): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  840): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  840): tsOffsetIs: Apps: 193715587483; DSPS: 6445228; Offset : -2990500000
,V/AlarmManager(  840): ELAPSED_WAKEUP set : Alarm{3f00150d type 2 when 194833 android} when 194833
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  840): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  840): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  840): tsOffsetIs: Apps: 213716354819; DSPS: 7100613; Offset : -2990495135
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  840): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  840): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  840): tsOffsetIs: Apps: 233717031686; DSPS: 7755995; Offset : -2990490488
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1367): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1367): called onTimeUpdated()
I/[SystemUI]Clock( 1367): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1367): called onTimeUpdated()
I/[SystemUI]DateView( 1367): called onTimeUpdated()
I/[SystemUI]DateView( 1367): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1367): handleTimeUpdate
D/charger_monitor(  491): init target 500000
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1367): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1367): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1367): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2032): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1367): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1367): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1367): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  840): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  840): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  840): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  840): tsOffsetIs: Apps: 253717707981; DSPS: 8411378; Offset : -2990515602
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  840): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  840): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  840): tsOffsetIs: Apps: 273718382192; DSPS: 9066760; Offset : -2990512517
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  840): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  840): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  840): tsOffsetIs: Apps: 293719054423; DSPS: 9722142; Offset : -2990511908
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1367): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1367): called onTimeUpdated()
I/[SystemUI]Clock( 1367): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1367): called onTimeUpdated()
I/[SystemUI]DateView( 1367): called onTimeUpdated()
I/[SystemUI]DateView( 1367): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1367): handleTimeUpdate
D/charger_monitor(  491): init target 500000
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1367): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1367): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1367): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2032): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1367): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1367): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1367): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  840): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  840): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  840): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  840): tsOffsetIs: Apps: 313719807124; DSPS: 10377526; Offset : -2990491499
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1367): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1367): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1367): On Skip Timer : true
D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1367): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1367): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1367): On Skip Timer : true
D/HeadsetStateMachine( 2032): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1367): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1367): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/[SystemUI]BatterySaverHandler( 1367): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  840): battery changed pluggedType: 2
D/HeadsetStateMachine( 2032): Disconnected process message: 10, size: 0
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1367): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1367): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/[SystemUI]BatterySaverHandler( 1367): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  840): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  840): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  840): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  840): tsOffsetIs: Apps: 333720772117; DSPS: 11032918; Offset : -2990503302
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1367): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1367): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1367): On Skip Timer : true
D/HeadsetStateMachine( 2032): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1367): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1367): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/[SystemUI]BatterySaverHandler( 1367): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  840): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  840): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  840): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6385): --= Surplus to requirements =--
I/jxcore-log( 6385): 
I/jxcore-log( 6385): ****TEST TOOK:  ms ****
I/jxcore-log( 6385): 
I/jxcore-log( 6385): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6385): 
,D/AndroidRuntime( 8135): 
D/AndroidRuntime( 8135): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8135): CheckJNI is OFF
,D/AndroidRuntime( 8135): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  840): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  840): Killing 6385:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  840): WIN DEATH: Window{3a58801e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  840): Focus left window: Window{3a58801e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  840): Window went away: Window{3a58801e u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  840): Skipping PackageSetting{1826a78e com.example.hello/10317} due to missing metadata
,I/ActivityManager(  840):   Force finishing activity ActivityRecord{159e71c3 u0 com.test.thalitest/.MainActivity t220}
,V/ActivityManager(  840): Display changed displayId=0
D/DSDPConnection( 1750): Display #0 changed.
,W/ActivityManager(  840): Spurious death for ProcessRecord{2e811cc2 6385:com.test.thalitest/u0a316}, curProc for 6385: null
,I/ActivityManager(  840): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,I/ActivityManager(  840):   Force finishing activity ActivityRecord{159e71c3 u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  840): Duplicate finish request for ActivityRecord{159e71c3 u0 com.test.thalitest/.MainActivity t220 f}
,I/[LGHome]EVENT( 1875): [Launcher.java:5203:onStart()]onStart
,I/art     ( 1933): Explicit concurrent mark sweep GC freed 10412(685KB) AllocSpace objects, 3(72KB) LOS objects, 40% free, 12MB/21MB, paused 1.721ms total 82.121ms
D/KeyguardModel( 1367): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/art     ( 4346): Explicit concurrent mark sweep GC freed 4304(222KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 14MB/18MB, paused 1.703ms total 103.251ms
I/InputReader(  840): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]EVENT( 1875): [Launcher.java:776:onResume()]onResume
,W/System.err( 3728): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/GeofencerStateMachine( 1731): Ignoring removeGeofence because network location is disabled.
,W/System.err( 3728): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3728): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3728): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3728): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3728): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3728): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3728): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3728): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3728): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3728): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3728): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  840): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8165 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/art     (  840): Explicit concurrent mark sweep GC freed 44336(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/34MB, paused 2.708ms total 181.457ms
I/[SystemUI]QSlideListController( 1367): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1367): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
I/art     (  840): WaitForGcToComplete blocked for 172.925ms for cause Explicit
D/KeyguardModel( 1367): createShortcutInfo...
D/KeyguardModel( 1367): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1367): createShortcutInfo...
,W/ResourceType( 1367): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1367): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]LGActivityUtil( 1875): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1367): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1367): createShortcutInfo...
,I/[LGHome]EVENT( 1875): [Launcher.java:929:onResume()]onResume end
I/Activity( 1875): Activity.onPostResume() called 
W/ResourceType( 1367): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1367): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1367): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1367): createShortcutInfo...
,W/ResourceType( 1367): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1367): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1367): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1367): createShortcutInfo...
I/[LGHome]EVENT( 1875): [Launcher.java:986:onPause()]onPause
W/ResourcesManager( 8165): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8165): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8165): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/[LGHome]LGWallpaperInfo( 1875): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1875): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1367): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1367): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/KeyguardModel( 1367): handleShortcutListChanged...
D/KeyguardModel( 1367): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1367): createShortcutInfo...
D/KeyguardModel( 1367): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1367): createShortcutInfo...
,W/ResourceType( 1367): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1367): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1367): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1367): createShortcutInfo...
I/SystemUI[Framework](  840): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/ResourceType( 1367): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1367): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1367): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1367): createShortcutInfo...
W/ResourceType( 1367): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1367): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,W/PhoneWindowManagerEx(  840): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  840): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  840): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  840): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@38ad064d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  840): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  840): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  840): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  840): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  840): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  840): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@38ad064d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  840): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1367): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1367): createShortcutInfo...
D/InputDispatcher(  840): Focus entered window: Window{2c946bdd u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1367): handleShortcutListChanged...
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1875): [Launcher.java:5214:onStop()]onStop
,I/[LGHome]EVENT( 1875): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1875): [setNavigationBarColor] color=0x 0
,D/administrator(  840): Handling package changes for user 0
I/art     (  840): Explicit concurrent mark sweep GC freed 3437(182KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.966ms total 243.814ms
,I/LGEmail ( 8165): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8165): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/AndroidRuntime( 8135): Shutting down VM
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
,W/InputMethodManagerService(  840): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  840): Got RemoteException sending setActive(false) notification to pid 6385 uid 10316
,I/NotificationService(  840): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  840): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
D/JobSchedulerService(  840): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/TaskPersister(  840): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1367): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1367): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1367): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1367):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1367): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/PackageChangeReceiver( 8165): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
W/IInputConnectionWrapper( 1875): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/b       ( 1624): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1875): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1875): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/ActivityManager(  840): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8191 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  840): Killing 7794:com.android.gallery3d/u0a23 (adj 15): empty #11
,I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/libprocessgroup(  840): failed to open /acct/uid_10023/pid_7794/cgroup.procs: No such file or directory
,I/Timeline(  840): Timeline: Activity_windows_visible id: ActivityRecord{35729dad u0 com.lge.launcher2/.Launcher t219} time:342165
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/AppUp4:AppBoxCP( 8191): onCreate
W/AppUp4:DB( 8191):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 8191):  setFingerPrint start
I/AppUp4:DB( 8191):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 8191):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8191):  SDK version = 0
I/AppUp4:DB( 8191):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8191): AppBoxApplication onCreate()
W/ResourcesManager(  840): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AppUp4:PreloadHelper( 8191): added Exclude : com.test.thalitest
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/ActivityManager(  840): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8214 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  840): Killing 7815:com.android.contacts/u0a18 (adj 15): empty #11
W/ResourceType(  840): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)

```
