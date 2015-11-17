#### Test 503880196ac79ce_thali02_LGE-LG-D722 Logs


```--------- beginning of main
11-17 18:30:36.863  4940  4966 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,11-17 18:30:36.872  3932  3932 I GAv4-SVC: Google Analytics 8.3.01 is starting up.
11-17 18:30:37.234   291   352 I ThermalEngine: Sensor:pa_therm0:34000 mC
11-17 18:30:37.247  5201  5201 D AndroidRuntime: 
11-17 18:30:37.247  5201  5201 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
11-17 18:30:37.255  5201  5201 D AndroidRuntime: CheckJNI is OFF
11-17 18:30:37.566  5201  5201 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-17 18:30:37.583   965  2107 I ActivityManager: START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
11-17 18:30:37.630   965  2107 D ActivityManager: setTaskToReturnTo : TaskRecord{379fad3f #217 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
11-17 18:30:37.631   965  2107 D ActivityManager: setTaskToReturnTo : TaskRecord{379fad3f #217 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
11-17 18:30:37.647   965  2107 D WindowStateEx: AppWindowTokenEx init.. 
11-17 18:30:37.658   965  1053 D ContextHelper: convertTheme. context->name=com.example.hello themeResourceId=16973833
11-17 18:30:37.674  1874  1874 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
11-17 18:30:37.697   965  2107 D InputDispatcher: Focus left window: Window{7b57bba u0 com.lge.launcher2/com.lge.launcher2.Launcher}
11-17 18:30:37.699  5201  5201 D AndroidRuntime: Shutting down VM
11-17 18:30:37.705   965  1053 D SplitWindow: check instance of lgWin Window{2f7307d1 u0 Starting com.example.hello}
11-17 18:30:37.759   965  1880 I ActivityManager: Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5216 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
11-17 18:30:37.804  1874  1874 I [LGHome]EVENT: [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
11-17 18:30:37.859  1874  1874 I [LGHome]EVENT: [Launcher.java:5214:onStop()]onStop
11-17 18:30:37.865  1936  1936 I HotwordDetector: Closing mic
11-17 18:30:37.874  1936  2520 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@38f6a729
11-17 18:30:37.874  1936  2520 V AudioRecord: stop()
11-17 18:30:37.874  1936  2520 D AudioRecord: AudioRecord->stop()
11-17 18:30:37.877   277  1322 V AudioFlinger: RecordHandle::stop()
11-17 18:30:37.877   277  1322 V AudioFlinger: RecordThread::stop
11-17 18:30:37.882   277  1322 V AudioFlinger: Record stopped OK
11-17 18:30:37.885   277  1322 V AudioPolicyManager: stopInput() input 17
11-17 18:30:37.886   277  1322 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
11-17 18:30:37.887   277  1322 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
11-17 18:30:37.887   277  1066 V AudioPolicyService: AudioCommandThread() waking up
11-17 18:30:37.887   277  1066 V AudioPolicyService: AudioCommandThread() processing release audio patch
11-17 18:30:37.887   277  1066 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
11-17 18:30:37.887   277  1066 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
11-17 18:30:37.888   277  1066 V AudioFlinger: ThreadBase::setParameters() routing=0
11-17 18:30:37.889   277  2553 D audio_hw_primary: in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
11-17 18:30:37.892   965  2107 I WindowStateAnimator: Starting window displayed
11-17 18:30:37.903   965  1051 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
11-17 18:30:37.911  1372  1372 D PhoneStatusBar: setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
11-17 18:30:37.914   965  1051 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
11-17 18:30:37.914   965  1051 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
11-17 18:30:37.915   965  1051 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:30:37.915   965  1051 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@24dea6f7,  pkg=WindowManager.LayoutParams
11-17 18:30:37.915   965  1051 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
11-17 18:30:37.916  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
11-17 18:30:37.916  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
11-17 18:30:37.916  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
11-17 18:30:37.931  1372  1372 D BarTransitions: draw background and invalidate : color = 18000000
,11-17 18:30:37.934   277  2553 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
11-17 18:30:37.934   277  2553 V audio_hw_primary: disable_audio_route: enter: usecase(7)
11-17 18:30:37.934   277  2553 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
11-17 18:30:37.934   277  2553 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-17 18:30:37.934  1372  1372 D BarTransitions: draw background and invalidate : color = 19181818
11-17 18:30:37.935   277  2553 V audio_hw_primary: disable_audio_route: exit
11-17 18:30:37.936   277  2553 E audio_hw_primary: disable_snd_device: enter 144
11-17 18:30:37.936   277  2553 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
11-17 18:30:37.936   277  2553 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
11-17 18:30:37.940   277  2553 V audio_hw_primary: stop_input_stream: exit: status(0)
11-17 18:30:37.940   277  2553 V audio_hw_primary: in_standby: exit:  status(0)
11-17 18:30:37.940   277  2553 V AudioFlinger: RecordThread: loop stopping
11-17 18:30:37.941   277  1066 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
11-17 18:30:37.941   277  2553 V AudioFlinger: RecordThread: loop starting
11-17 18:30:37.941   277  2553 V AudioFlinger: processConfigEvents_l() remaining events 1
11-17 18:30:37.942   277  2553 V AudioFlinger: processConfigEvents_l() DONE thread 0xb4170000
11-17 18:30:37.942   277  2553 V AudioFlinger: RecordThread: loop stopping
11-17 18:30:37.942   277  1066 V AudioPolicyService: AudioCommandThread() going to sleep
11-17 18:30:37.942   277  1322 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
11-17 18:30:37.942   277  1322 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
11-17 18:30:37.942   277  1322 V AudioPolicyService: AudioCommandThread() adding update audio patch list
11-17 18:30:37.943   277  1322 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
11-17 18:30:37.944   277  1322 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
11-17 18:30:37.944   277  1322 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
11-17 18:30:37.944   277  1066 V AudioPolicyService: AudioCommandThread() waking up
11-17 18:30:37.944   277  1066 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
11-17 18:30:37.944   277  1066 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 277
11-17 18:30:37.944   277  1066 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
11-17 18:30:37.944   277  1066 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
11-17 18:30:37.944   277  2553 V AudioFlinger: RecordThread: loop starting
11-17 18:30:37.945   277  1067 V AudioPolicyService: AudioCommandThread() waking up
11-17 18:30:37.945   277  1067 V AudioPolicyService: AudioCommandThread() processing update audio patch list
11-17 18:30:37.945   277  1067 V AudioPolicyService: AudioCommandThread() going to sleep
11-17 18:30:37.946   277  2553 V AudioFlinger: processConfigEvents_l() remaining events 1
11-17 18:30:37.946   277  2553 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
11-17 18:30:37.946   277  2553 V audio_hw_primary: in_set_parameters: exit: status(0)
11-17 18:30:37.946   277  2553 V AudioFlinger: processConfigEvents_l() DONE thread 0xb4170000
11-17 18:30:37.946   277  2553 V AudioFlinger: RecordThread: loop stopping
11-17 18:30:37.946   277  1066 V AudioPolicyService: AudioCommandThread() going to sleep
11-17 18:30:37.953  1936  2520 V AudioRecord: stop()
11-17 18:30:37.955  1936  2520 V AudioRecord: stop()
11-17 18:30:37.955  1936  2520 V AudioRecord: stop()
11-17 18:30:37.962   277   277 V AudioFlinger: releasing 16 from 1936 for -1
11-17 18:30:37.962   277   277 V AudioFlinger:  decremented refcount to 0
11-17 18:30:37.962   277   277 V AudioFlinger: purging stale effects
11-17 18:30:37.962   277   277 V AudioFlinger: RecordHandle::stop()
11-17 18:30:37.962   277   277 V AudioFlinger: RecordThread::stop
11-17 18:30:37.962   277   277 V AudioPolicyManager: releaseInput() 17
11-17 18:30:37.962   277   277 V AudioPolicyManager: closeInput(17)
11-17 18:30:37.962   277   277 V AudioFlinger: closeInput() 17
11-17 18:30:37.964   277   277 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
11-17 18:30:37.964   277   277 V AudioFlinger: ThreadBase::exit
11-17 18:30:37.964   277  2553 V AudioFlinger: RecordThread: loop starting
11-17 18:30:37.964  3097  3112 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
11-17 18:30:37.964  1372  1905 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
11-17 18:30:37.964  2650  2671 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
11-17 18:30:37.964   277  2553 V AudioFlinger: RecordThread 0xb4170000 exiting
11-17 18:30:37.965   965  1825 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
11-17 18:30:37.965  1748  2620 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
11-17 18:30:37.965   277   277 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb4036520)
11-17 18:30:37.965   277   277 D audio_hw_primary: in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
11-17 18:30:37.965   277   277 V audio_hw_primary: in_standby: exit:  status(0)
11-17 18:30:37.965   277   277 V AudioPolicyService: AudioCommandThread() adding update audio port list
11-17 18:30:37.965   277   277 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
11-17 18:30:37.965   277   277 V AudioPolicyManager: releaseInput() exit
11-17 18:30:37.965   277   277 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
11-17 18:30:37.965   277   277 V AudioFlinger: removeClient_l() pid 1936, calling pid 277
11-17 18:30:37.966   277  1067 V AudioPolicyService: AudioCommandThread() waking up
11-17 18:30:37.966   277  1067 V AudioPolicyService: AudioCommandThread() processing update audio port list
11-17 18:30:37.966   277  1067 V AudioPolicyService: AudioCommandThread() going to sleep
11-17 18:30:37.966  1936  5233 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
11-17 18:30:38.005  5216  5216 D ContextHelper: convertTheme. context->name=com.example.hello themeResourceId=16973833
11-17 18:30:38.011  1936  2548 I HotwordRecognitionRnr: Hotword detection finished
11-17 18:30:38.014  1936  2543 I HotwordRecognitionRnr: Stopping hotword detection.
11-17 18:30:38.131  5216  5216 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
11-17 18:30:38.202  5216  5216 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4565-4567)
11-17 18:30:38.203  5216  5216 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:30:38.230  5216  5216 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {34a0bf71}
11-17 18:30:38.232  5216  5216 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:30:38.232  5216  5216 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-17 18:30:38.247  5216  5216 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-17 18:30:38.250  5216  5216 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:30:38.251  5216  5216 E SysUtils: ApplicationContext is null in ApplicationStatus
11-17 18:30:38.286  5216  5252 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
11-17 18:30:38.301  5216  5216 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
11-17 18:30:38.312  5216  5216 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-17 18:30:38.312  5216  5216 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-17 18:30:38.315  5216  5216 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
11-17 18:30:38.315  5216  5216 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
11-17 18:30:38.315  5216  5216 I Adreno-EGL: Build Date: 03/02/15 Mon
11-17 18:30:38.315  5216  5216 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
11-17 18:30:38.315  5216  5216 I Adreno-EGL: Remote Branch: 
11-17 18:30:38.315  5216  5216 I Adreno-EGL: Local Patches: 
11-17 18:30:38.315  5216  5216 I Adreno-EGL: Reconstruct Branch: 
11-17 18:30:38.391   965  1782 I ActivityManager: Killing 4975:com.google.android.talk/u0a61 (adj 15): empty #11
11-17 18:30:38.452   277  1303 V AudioPolicyService: registerClient() client 0xb3adf300, uid 10030
11-17 18:30:38.456   965  2325 W libprocessgroup: failed to open /acct/uid_10061/pid_4975/cgroup.procs: No such file or directory
11-17 18:30:38.458   965  1052 D BluetoothManagerService: Message: 20
11-17 18:30:38.458   965  1052 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d2de009:true
11-17 18:30:38.462  5216  5263 D BluetoothAdapter: 594509508: getState() :  mService = null. Returning STATE_OFF
11-17 18:30:38.659  5216  5216 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:30:38.675  5216  5216 W AwContents: onDetachedFromWindow called when already detached. Ignoring
11-17 18:30:38.698  5216  5216 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
11-17 18:30:38.706  5216  5216 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:30:38.706  5216  5216 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:30:38.768  5216  5216 I Activity: Activity.onPostResume() called 
11-17 18:30:38.777  5216  5274 D OpenGLRenderer: Render dirty regions requested: true
11-17 18:30:38.777  5216  5274 I OpenGLRenderer: Initialized EGL, version 1.4
11-17 18:30:38.782  5216  5274 D OpenGLRenderer: Enabling debug mode 0
11-17 18:30:38.801  5216  5216 D Atlas   : Validating map...
11-17 18:30:38.806   965  1921 D SplitWindow: check instance of lgWin Window{53fa63b u0 com.example.hello/com.example.hello.MainActivity}
11-17 18:30:38.814  5216  5261 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
11-17 18:30:38.842   965  1921 D InputDispatcher: Focus entered window: Window{53fa63b u0 com.example.hello/com.example.hello.MainActivity}
11-17 18:30:38.898   965   983 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
11-17 18:30:38.910   965  1053 I ActivityManager: Displayed com.example.hello/.MainActivity: +1s203ms
11-17 18:30:38.910   965  1053 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1380260c u0 com.example.hello/.MainActivity t217} time:75275
11-17 18:30:38.915  5216  5216 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@37fa901d time:75279
11-17 18:30:39.059  5216  5216 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5216
11-17 18:30:39.105  5216  5216 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
11-17 18:30:39.231  5216  5216 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
11-17 18:30:39.264  5216  5279 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
,11-17 18:30:39.723  5216  5277 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426106880
11-17 18:30:39.724  5216  5277 D JX-Cordova: jxcore cordova android initializing
,11-17 18:30:39.822  5216  5216 W jxcore-log: Initializing JXcore engine
11-17 18:30:39.822  5216  5216 W jxcore-log: JXcore engine is ready
,11-17 18:30:39.829  5216  5216 W jxcore-log: Starting JXcore engine
11-17 18:30:39.927  5216  5216 W m.example.hello: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5020]" dev="sockfs" ino=5020 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-17 18:30:39.927  5216  5216 W m.example.hello: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-17 18:30:39.927  5216  5216 W m.example.hello: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5088]" dev="sockfs" ino=5088 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-17 18:30:39.927  5216  5216 W m.example.hello: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
11-17 18:30:39.927  5216  5216 W m.example.hello: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
11-17 18:30:39.927  5216  5216 W m.example.hello: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[23824]" dev="sockfs" ino=23824 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-17 18:30:40.111  5216  5216 W jxcore-log: Platform android
11-17 18:30:40.111  5216  5216 W jxcore-log: 
,11-17 18:30:40.111  5216  5216 W jxcore-log: Process ARCH arm
11-17 18:30:40.111  5216  5216 W jxcore-log: 
11-17 18:30:40.175  5216  5216 I jxcore-log: JXcore Cordova bridge is ready!
11-17 18:30:40.175  5216  5216 I jxcore-log: 
11-17 18:30:40.175  5216  5216 W jxcore-log: JXcore engine is started
,11-17 18:30:40.224  5216  5216 E jxcore-log: >> LGE-LG-D722
11-17 18:30:40.224  5216  5216 E jxcore-log: 
,11-17 18:30:40.226  5216  5216 I jxcore-log: Total memory 906309632
11-17 18:30:40.226  5216  5216 I jxcore-log: 
11-17 18:30:40.227  5216  5216 I jxcore-log: Free memory 23453696
11-17 18:30:40.227  5216  5216 I jxcore-log: 
11-17 18:30:40.227  5216  5216 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:30:40.227  5216  5216 I jxcore-log: 
11-17 18:30:40.227  5216  5216 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:30:40.227  5216  5216 I jxcore-log: 
11-17 18:30:40.234  5216  5216 I jxcore-log: userPath [ 'www' ]
11-17 18:30:40.234  5216  5216 I jxcore-log: 
11-17 18:30:40.236  5216  5216 I jxcore-log: Size 720 1196
11-17 18:30:40.236  5216  5216 I jxcore-log: 
11-17 18:30:40.237  5216  5216 I jxcore-log: Screen Brightness 255
11-17 18:30:40.237  5216  5216 I jxcore-log: 
11-17 18:30:40.238  5216  5216 E jxcore-log: Dummy Error Log.
11-17 18:30:40.238  5216  5216 E jxcore-log: 
,11-17 18:30:40.758  5216  5216 I jxcore-log: getBuffer is called!!!!
11-17 18:30:40.758  5216  5216 I jxcore-log: 
,11-17 18:30:40.985  3551  3605 D InitAlarmsService: Clearing and rescheduling alarms.
,11-17 18:30:41.029   965  1347 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5292 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,11-17 18:30:41.177  5292  5292 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,11-17 18:30:41.210  5292  5292 D CalendarProvider2: [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2732962c
,11-17 18:30:41.227  5292  5292 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
,11-17 18:30:41.233  5292  5292 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@34a0bf71(com.android.providers.calendar.CalendarProvider2@2732962c)
11-17 18:30:41.240  5292  5309 D CalendarProvider2: Scheduling check of next Alarm
,11-17 18:30:41.244  5292  5309 D CalendarProvider2: SCHEDULE_ALARM_REMOVE
11-17 18:30:41.252   965   984 I ActivityManager: Killing 3551:com.android.calendar/u0a13 (adj 15): empty #11
,11-17 18:30:41.295   965  1921 W libprocessgroup: failed to open /acct/uid_10013/pid_3551/cgroup.procs: No such file or directory
,11-17 18:30:42.238   291   352 I ThermalEngine: Sensor:pa_therm0:34000 mC
,11-17 18:30:42.254  5292  5292 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,11-17 18:30:42.261  5292  5292 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
11-17 18:30:42.313   965  1045 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5333 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,11-17 18:30:42.318   965  1825 I ActivityManager: Killing 5060:com.lge.appbox.client/u0a11 (adj 15): empty #11
11-17 18:30:42.356   965  1358 W libprocessgroup: failed to open /acct/uid_10011/pid_5060/cgroup.procs: No such file or directory
,11-17 18:30:42.398  5333  5333 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,11-17 18:30:42.454  5333  5333 D CalendarApplication: CalendarApplication.onCreate()
,11-17 18:30:42.466  5333  5333 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
,11-17 18:30:42.467  5333  5333 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@35ca268a, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@178ca4fb, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3648e918, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@34a0bf71, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@252c2156, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@247695d7, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@236f7ec4, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1eb0e1ad, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2ee0fce2, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@3ba4b873, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3147c330, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@26eba9, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@1a16052e, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@8868cf, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@291de25c, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@bd99965, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2181463a, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@324cc2eb, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@3ad4c848, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@114f66e1, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@32d8c06, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@db2a2c7, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2f9220f4, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@37fa901d, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@1066292, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@30aca463, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@1b2a5860, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@32351119, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@1e2415de, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1bbb23bf, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@384c9a8c, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@23fca5d5, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@24d7b1ea, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@2d083cdb, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@1b6ed378, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@396eca51, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@17702b6, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3143cbb7, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2879af24, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2904ba8d, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3de89442, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$Key,Data@263f6c5
11-17 18:30:42.471  5333  5333 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
11-17 18:30:42.476  5333  5333 D Config  : [init]
,11-17 18:30:42.477  5333  5333 I Config  : LGCalendar ver.4.40.17
11-17 18:30:42.477  5333  5333 I Config  : start check model
11-17 18:30:42.478  5333  5333 I Config  : start check native_ca
11-17 18:30:42.480  5333  5333 I Config  : Config Operator=OPEN, Country=EU
11-17 18:30:42.481  5333  5333 D Config  : [setDefaultValuesToPref]
11-17 18:30:42.481  5333  5333 D Config  : [parseProfiles]
11-17 18:30:42.484  5333  5333 D ProfilesParser: [debug_displayParseInfos] profile.country = null
11-17 18:30:42.484  5333  5333 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
11-17 18:30:42.484  5333  5333 D Config  : [updateProfiletoCountryInfo]
11-17 18:30:42.485  5333  5333 D GeneralPreference: [checkAndMigrateOldPreference]
11-17 18:30:42.498  5333  5333 D AlertReceiver: onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,11-17 18:30:42.506  5333  5362 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
11-17 18:30:42.508  5333  5362 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
11-17 18:30:42.523  5333  5362 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,11-17 18:30:42.528  5333  5362 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
11-17 18:30:42.531  5333  5362 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
11-17 18:30:42.534  5333  5362 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
11-17 18:30:42.538  5333  5362 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,11-17 18:30:42.541  5333  5362 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
11-17 18:30:42.544  5333  5362 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
11-17 18:30:42.547  5333  5362 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
11-17 18:30:42.550  5333  5362 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,11-17 18:30:42.621  5333  5364 W HolidayIntentService: onHandleIntent
,11-17 18:30:42.623  5333  5364 D HolidayDataLoader: readJsonAsset : holiday.json
11-17 18:30:42.644  5333  5365 D AlertService: 0 Action = android.intent.action.PROVIDER_CHANGED
,11-17 18:30:42.681  5333  5364 E HolidayIntentService: onHandleIntent:holiday data empty
,11-17 18:30:42.683   965  2325 I art     : Explicit concurrent mark sweep GC freed 13060(650KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 1.545ms total 129.969ms
11-17 18:30:42.688  5333  5362 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
11-17 18:30:42.688  5333  5333 E AgendaWidgetManager: [updateWidgets] 
11-17 18:30:42.692  5333  5333 D MonthWidgetProvider: [onReceive]
11-17 18:30:42.692  5333  5333 D CalendarWidgetProvider: [onReceive]
11-17 18:30:42.692  5333  5362 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,11-17 18:30:42.692  5333  5333 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
11-17 18:30:42.695  5333  5333 D CalendarTypeController: [onCreate] mContext.getPackageName() = com.android.calendar
11-17 18:30:42.697  5333  5362 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
11-17 18:30:42.698  5333  5333 D WeekWidgetProvider: [onReceive]
11-17 18:30:42.698  5333  5333 D CalendarWidgetProvider: [onReceive]
11-17 18:30:42.698  5333  5333 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
11-17 18:30:42.700  5333  5333 D CalendarTypeController: [onCreate] mContext.getPackageName() = com.android.calendar
11-17 18:30:42.702  5333  5362 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
11-17 18:30:42.704  5333  5362 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,11-17 18:30:42.708  5333  5362 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
11-17 18:30:42.711  5333  5362 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
11-17 18:30:42.711  5333  5362 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
11-17 18:30:42.713  5333  5362 I AlertUtils: set default noti to content://media/internal/audio/media/38
11-17 18:30:42.717  5333  5362 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
,11-17 18:30:45.260   965  1782 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,11-17 18:30:45.264   965  1782 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
11-17 18:30:45.264   965  1052 D BluetoothManagerService: Message: 2
11-17 18:30:45.306   965  1807 D WifiServiceImplEx: setWifiEnabled: false pid=5216, uid=10030, package= com.example.hello, App Lable : HelloWorld
,11-17 18:30:45.314   965  1807 D WifiService: setWifiEnabled: false pid=5216, uid=10030
11-17 18:30:45.315  5216  5216 I jxcore-log: ****TEST TOOK:  5097  ms ****
11-17 18:30:45.315  5216  5216 I jxcore-log: 
11-17 18:30:45.316  5216  5216 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:30:45.316  5216  5216 I jxcore-log: 
11-17 18:30:46.247   965  1285 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3b744807 type 2 when 82597 com.android.providers.calendar} when 82597
,11-17 18:30:46.248  5292  5292 D CalendarProviderBroadcastReceiver: Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
11-17 18:30:46.248  5292  5292 D CalendarProviderBroadcastReceiver: [IntentService] WakeLock acquire, start IntentSerivce
11-17 18:30:46.257  5292  5292 D CalendarProvider2: CalendarProviderIntentService.onCreate()
11-17 18:30:46.258  5292  5383 D CalendarProvider2: Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
11-17 18:30:46.259  5292  5383 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
,11-17 18:30:46.304  5292  5383 D CalendarProvider2: [IntentService] Release Lock
,11-17 18:30:46.307  5292  5292 D CalendarProvider2: CalendarProviderIntentService.onDestroy()
11-17 18:30:46.363   965  1285 V AlarmManager: RTC_WAKEUP set : Alarm{8b38d2 type 0 when 1447781446353 com.android.vending} when 1447781446353
,11-17 18:30:46.507  5384  5384 D AndroidRuntime: 
11-17 18:30:46.507  5384  5384 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
11-17 18:30:46.507  4898  4937 D Finsky  : [560] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-17 18:30:46.508  4898  4898 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
11-17 18:30:46.511  5384  5384 D AndroidRuntime: CheckJNI is OFF
11-17 18:30:46.712  5384  5384 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-17 18:30:46.764   965  1045 I ActivityManager: Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
,11-17 18:30:46.766   965  1045 I ActivityManager: Killing 5216:com.example.hello/u0a30 (adj 0): stop com.example.hello
11-17 18:30:46.792   965  1825 I WindowState: WIN DEATH: Window{53fa63b u0 com.example.hello/com.example.hello.MainActivity}
,11-17 18:30:46.797   965  1825 D InputDispatcher: Focus left window: Window{53fa63b u0 com.example.hello/com.example.hello.MainActivity}
11-17 18:30:46.797   965  1825 D InputDispatcher: Window went away: Window{53fa63b u0 com.example.hello/com.example.hello.MainActivity}
,11-17 18:30:46.834   965  1061 W PackageSettings: Skipping PackageSetting{2da0665e com.test.thalitest/10316} due to missing metadata
,11-17 18:30:46.878   965  1045 W ActivityManager: Force removing ActivityRecord{1380260c u0 com.example.hello/.MainActivity t217}: app died, no saved state
,11-17 18:30:46.890   965  1921 W ActivityManager: Spurious death for ProcessRecord{2b035da3 5216:com.example.hello/u0a30}, curProc for 5216: null
,11-17 18:30:46.893   965  1061 I ActivityManager: Force stopping com.example.hello appid=10030 user=0: pkg removed
11-17 18:30:46.921  1874  1874 I [LGHome]EVENT: [Launcher.java:5203:onStart()]onStart
,11-17 18:30:46.926  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
11-17 18:30:46.948   965  1287 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-17 18:30:46.951  1837  1837 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
11-17 18:30:46.961  1730  2377 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-17 18:30:46.972  1874  1874 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,11-17 18:30:46.991  3381  3381 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,11-17 18:30:46.991  3381  3381 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
11-17 18:30:46.991  3381  3381 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
11-17 18:30:46.991  3381  3381 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
11-17 18:30:46.991  3381  3381 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 18:30:46.991  3381  3381 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:30:46.991  3381  3381 W System.err: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:30:46.991  3381  3381 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
11-17 18:30:46.991  3381  3381 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:30:46.991  3381  3381 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:30:46.991  3381  3381 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
11-17 18:30:46.992  3381  3381 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
11-17 18:30:46.995   965  1045 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5408 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
11-17 18:30:47.036  1372  1372 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,11-17 18:30:47.041   965   965 D administrator: Handling package changes for user 0
11-17 18:30:47.044  1874  1874 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
11-17 18:30:47.045  1874  1874 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
11-17 18:30:47.045  1874  1874 I Activity: Activity.onPostResume() called 
11-17 18:30:47.050  1372  1505 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
11-17 18:30:47.050  1372  1505 D KeyguardModel: createShortcutInfo...
,11-17 18:30:47.057  1372  1505 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
11-17 18:30:47.057  1372  1505 D KeyguardModel: createShortcutInfo...
11-17 18:30:47.058  1372  1505 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:30:47.061   965  1051 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
11-17 18:30:47.061  1372  1505 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
11-17 18:30:47.061   965  1051 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
11-17 18:30:47.061   965  1051 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
11-17 18:30:47.062   965  1051 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:30:47.062   965  1051 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@24dea6f7,  pkg=WindowManager.LayoutParams
11-17 18:30:47.062   965  1051 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,11-17 18:30:47.063  1372  1505 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
11-17 18:30:47.063  1372  1505 D KeyguardModel: createShortcutInfo...
11-17 18:30:47.065  1372  1505 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:30:47.065  1372  1505 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
11-17 18:30:47.066  1372  1505 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
11-17 18:30:47.066  1372  1505 D KeyguardModel: createShortcutInfo...
11-17 18:30:47.068  1372  1505 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:30:47.068  1372  1505 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
11-17 18:30:47.070  1372  1505 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
11-17 18:30:47.070  1372  1505 D KeyguardModel: createShortcutInfo...
11-17 18:30:47.072  1874  5425 W [LGHome]LGWallpaperInfo: [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
11-17 18:30:47.072  1874  5425 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
11-17 18:30:47.077   965  2107 D InputDispatcher: Focus entered window: Window{7b57bba u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,11-17 18:30:47.082  1372  1372 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
11-17 18:30:47.083  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
11-17 18:30:47.085  1372  1372 D KeyguardModel: handleShortcutListChanged...
11-17 18:30:47.098  1874  1874 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,11-17 18:30:47.098  1874  1874 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
11-17 18:30:47.099  1874  1874 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
11-17 18:30:47.102  1874  1874 I [LGHome]EVENT: [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
11-17 18:30:47.103  1874  1874 I PhoneWindow: [setNavigationBarColor] color=0x 0
11-17 18:30:47.116  1372  1505 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
11-17 18:30:47.116  1372  1505 D KeyguardModel: createShortcutInfo...
,11-17 18:30:47.120  1372  1505 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
11-17 18:30:47.120  1372  1505 D KeyguardModel: createShortcutInfo...
11-17 18:30:47.121  1372  1505 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:30:47.121  1372  1505 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
11-17 18:30:47.123  1372  1505 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
11-17 18:30:47.123  1372  1505 D KeyguardModel: createShortcutInfo...
11-17 18:30:47.124  1372  1505 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:30:47.124  1372  1505 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
11-17 18:30:47.126  1372  1505 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
11-17 18:30:47.126  1372  1505 D KeyguardModel: createShortcutInfo...
11-17 18:30:47.128  1372  1505 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:30:47.128  1372  1505 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
11-17 18:30:47.129  1372  1505 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
11-17 18:30:47.129  1372  1505 D KeyguardModel: createShortcutInfo...
,11-17 18:30:47.135  1372  1372 D KeyguardModel: handleShortcutListChanged...
11-17 18:30:47.148  5408  5408 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:30:47.148  5408  5408 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
11-17 18:30:47.149  5408  5408 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
11-17 18:30:47.151   965  2151 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,11-17 18:30:47.155   965  2151 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5216 uid 10030
11-17 18:30:47.213  1874  1874 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@25abee87 time:83578
,11-17 18:30:47.217   965  1051 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
11-17 18:30:47.224   965  1051 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
11-17 18:30:47.225   965  1051 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
11-17 18:30:47.225   965  1051 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:30:47.225   965  1051 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@24dea6f7,  pkg=WindowManager.LayoutParams
11-17 18:30:47.225   965  1051 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
11-17 18:30:47.233  1936  5430 I HotwordRecognitionRnr: Starting hotword detection.
,11-17 18:30:47.238  1936  5431 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@29e2ee09
11-17 18:30:47.239  1936  5431 V AudioRecord: set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
11-17 18:30:47.239  1936  5431 V AudioRecord: set(): mSessionId 22
11-17 18:30:47.240   277  1322 V AudioPolicyManager: getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
11-17 18:30:47.240   277  1322 V AudioPolicyManager: getDeviceForInputSource()input source 1999, device 80000004
11-17 18:30:47.240   277  1322 V AudioPolicyManager: isPlaybackThread 0,isRecordThread 1
11-17 18:30:47.240   277  1322 D audio_hw_primary: adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546e1a0)
11-17 18:30:47.240   277  1322 V audio_hw_primary: adev_open_input_stream: exit
11-17 18:30:47.240   277  1322 V AudioFlinger: openInput_l() openInputStream returned input 0xb546e1a0, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
11-17 18:30:47.241   277  1322 V AudioFlinger: openInput_l() created record thread: ID 23 thread 0xb3a8a000
11-17 18:30:47.241   277  1322 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
11-17 18:30:47.241  1372  1905 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
11-17 18:30:47.242   277  1322 V AudioPolicyService: AudioCommandThread() adding update audio port list
11-17 18:30:47.242  3097  3113 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
11-17 18:30:47.242   277  1322 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
11-17 18:30:47.242   277  1067 V AudioPolicyService: AudioCommandThread() waking up
11-17 18:30:47.242   277  1067 V AudioPolicyService: AudioCommandThread() processing update audio port list
11-17 18:30:47.242   965  1630 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
11-17 18:30:47.242  1936  1961 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
11-17 18:30:47.242   277  1067 V AudioPolicyService: AudioCommandThread() going to sleep
11-17 18:30:47.242  1748  2738 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
11-17 18:30:47.243   277   277 V AudioFlinger: openRecord() lSessionId: 22 input 23
11-17 18:30:47.243  2650  2671 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
11-17 18:30:47.243   291   352 I ThermalEngine: Sensor:pa_therm0:34000 mC
11-17 18:30:47.244   277   277 V AudioFlinger: getOrphanEffectChain_l session 22 index -2
,11-17 18:30:47.245   277   277 V AudioFlinger: acquiring 22 from 1936, for -1
11-17 18:30:47.245   277   277 V AudioFlinger:  added new entry for 22
11-17 18:30:47.247  1936  5431 V AudioRecord: start, sync event 0 trigger session 0
11-17 18:30:47.247  1936  5431 V AudioRecord: mAudioRecord->start()
11-17 18:30:47.247   277  1322 V AudioFlinger: RecordHandle::start()
11-17 18:30:47.247   277  1322 V AudioFlinger: RecordThread::start event 0, triggerSession 0
11-17 18:30:47.247   277  1322 V AudioPolicyManager: startInput() module primary->input primary(23)
11-17 18:30:47.247   277  1322 V AudioPolicyManager: getDeviceForInputSource()input source 1999, device 80000004
11-17 18:30:47.247   277  1322 V AudioPolicyManager: getNewInputDevice() selected device 80000004
11-17 18:30:47.247   277  1322 V AudioPolicyManager: DeviceVector::refreshTypes() mDeviceTypes 80000004
11-17 18:30:47.247   277  1322 V AudioPolicyManager: DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
11-17 18:30:47.247   277  1322 V AudioPolicyService: AudioCommandThread() adding create patch delay 0
11-17 18:30:47.247   277  1322 V AudioPolicyService: inserting command: 7 at index 0, num commands 0
11-17 18:30:47.248   277  1066 V AudioPolicyService: AudioCommandThread() waking up
11-17 18:30:47.248   277  1066 V AudioPolicyService: AudioCommandThread() processing create audio patch
11-17 18:30:47.248   277  5433 I AudioFlinger: AudioFlinger's thread 0xb3a8a000 ready to run
11-17 18:30:47.248   277  1066 V AudioFlinger::PatchPanel: createAudioPatch() num_sources 1 num_sinks 1 handle 0
11-17 18:30:47.248   277  5433 D audio_hw_primary: in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
11-17 18:30:47.248   277  5433 V audio_hw_primary: in_standby: exit:  status(0)
11-17 18:30:47.248   277  1066 V AudioFlinger::PatchPanel: createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
11-17 18:30:47.248   277  1066 V AudioFlinger: ThreadBase::setParameters() input_source=6;routing=-2147483644
11-17 18:30:47.248   277  1066 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
11-17 18:30:47.250   965   965 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
11-17 18:30:47.250   965   965 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
11-17 18:30:47.252   965   965 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
11-17 18:30:47.259   277  5433 V AudioFlinger: processConfigEvents_l() remaining events 1
11-17 18:30:47.259   277  5433 D audio_hw_primary: in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
11-17 18:30:47.259   277  5433 V audio_hw_primary: in_set_parameters: exit: status(0)
11-17 18:30:47.259   277  5433 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3a8a000
11-17 18:30:47.259   277  1066 V AudioFlinger::PatchPanel: createAudioPatch() status 0
11-17 18:30:47.259   277  1066 V AudioFlinger::PatchPanel: createAudioPatch() added new patch handle 24 halHandle 0
11-17 18:30:47.259   277  1066 V AudioPolicyService: AudioCommandThread() going to sleep
11-17 18:30:47.259   277  1322 V AudioPolicyManager: setInputDevice() createAudioPatch returned 0 patchHandle 24
11-17 18:30:47.259   277  1322 V AudioPolicyManager: addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
11-17 18:30:47.259   277  1322 V AudioPolicyService: AudioCommandThread() adding update audio patch list
11-17 18:30:47.259   277  1322 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
,11-17 18:30:47.259   277  1322 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
11-17 18:30:47.259   277  1322 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
11-17 18:30:47.259   277  1067 V AudioPolicyService: AudioCommandThread() waking up
11-17 18:30:47.259   277  1067 V AudioPolicyService: AudioCommandThread() processing update audio patch list
11-17 18:30:47.259   277  1066 V AudioPolicyService: AudioCommandThread() waking up
11-17 18:30:47.259   277  1066 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=1, io 23
11-17 18:30:47.259   277  1066 V AudioFlinger: setParameters(): io 23, keyvalue hotword_active=1, calling pid 277
11-17 18:30:47.259   277  1066 V AudioFlinger: ThreadBase::setParameters() hotword_active=1
11-17 18:30:47.259   277  1066 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
11-17 18:30:47.259   277  1067 V AudioPolicyService: AudioCommandThread() going to sleep
11-17 18:30:47.267   965  1349 D TaskPersister: removeObsoleteFile: deleting file=217_task.xml
11-17 18:30:47.268  1372  1372 D PhoneStatusBar: setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
11-17 18:30:47.269  1372  1372 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
11-17 18:30:47.269   277  5433 V AudioFlinger: processConfigEvents_l() remaining events 1
11-17 18:30:47.269   277  5433 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=1
11-17 18:30:47.269   277  5433 V audio_hw_primary: in_set_parameters: exit: status(0)
11-17 18:30:47.269   277  5433 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3a8a000
,11-17 18:30:47.269   277  1066 V AudioPolicyService: AudioCommandThread() going to sleep
11-17 18:30:47.269   277  1322 V AudioPolicyManager: AudioPolicyManager::startInput() input source = 1999
11-17 18:30:47.270  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
11-17 18:30:47.270  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
11-17 18:30:47.270  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
11-17 18:30:47.273  1936  5431 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@29e2ee09
11-17 18:30:47.275  1372  1372 D BarTransitions: draw background and invalidate : color = f7000000
11-17 18:30:47.279   277  5433 V msm8974_platform: platform_update_usecase_from_source: input source :6
11-17 18:30:47.279   277  5433 D audio_hw_primary: start_input_stream: enter: stream(0xb546e1a0)usecase(7: audio-record)
11-17 18:30:47.279   277  5433 V voice   : voice_check_and_set_incall_rec_usecase: voice call not active
11-17 18:30:47.279   277  5433 V audio_hw_primary: start_input_stream: usecase(7)
11-17 18:30:47.279   277  5433 E audio_hw_primary: select_devices: enter and usecase(7)
11-17 18:30:47.279  1372  1372 D BarTransitions: draw background and invalidate : color = f2e8e8e8
11-17 18:30:47.279   277  5433 V msm8974_platform: platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
11-17 18:30:47.279   277  5433 V msm8974_platform: platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
11-17 18:30:47.279   277  5433 V msm8974_platform_lge: LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
11-17 18:30:47.279   277  5433 V audio_hw_lge_primary: LGE_exeption_scenario: enter and out: 0, in: 144
11-17 18:30:47.279   277  5433 D audio_hw_primary: select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
11-17 18:30:47.279   277  5433 E audio_hw_primary: enable_snd_device: enter  144
11-17 18:30:47.279   277  5433 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
11-17 18:30:47.280   277  5433 V audio_hw_primary: enable_snd_device: snd_device(144: lg-vr-handset-mic)
11-17 18:30:47.280   277  5433 V msm8974_platform_lge: LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
11-17 18:30:47.280   277  5433 D ACDB-LOADER: ACDB -> send_audio_cal, acdb_id = 65, path =  1
11-17 18:30:47.280   277  5433 D ACDB-LOADER: ACDB -> send_adm_topology
11-17 18:30:47.280   277  5433 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
11-17 18:30:47.282   277  5433 D ACDB-LOADER: ACDB -> send_asm_topology
11-17 18:30:47.282   277  5433 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
11-17 18:30:47.282   277  5433 D ACDB-LOADER: ACDB -> send_audtable
11-17 18:30:47.282   277  5433 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
11-17 18:30:47.282   277  5433 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_CAL
11-17 18:30:47.282   277  5433 D ACDB-LOADER: ACDB -> send_audvoltable
11-17 18:30:47.282   277  5433 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
11-17 18:30:47.282   277  5433 D         : Failed to fetch the lookup information of the device 00000041 
11-17 18:30:47.282   277  5433 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
11-17 18:30:47.282   277  5433 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
11-17 18:30:47.282   277  5433 D ACDB-LOADER: ACDB -> AUDIO_SET_AFE_CAL
,11-17 18:30:47.288   277  5433 V audio_hw_primary: enable_audio_route: enter: usecase(7)
11-17 18:30:47.288   277  5433 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
11-17 18:30:47.288   277  5433 V audio_hw_primary: enable_audio_route: apply mixer and update path: audio-record
11-17 18:30:47.288   277  5433 V audio_hw_primary: enable_audio_route: exit
11-17 18:30:47.288   277  5433 D audio_hw_primary: select_devices: done
11-17 18:30:47.288   277  5433 V audio_hw_primary: start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
11-17 18:30:47.293   277  5433 V audio_hw_primary: start_input_stream: exit
11-17 18:30:47.364   965  1061 I art     : Explicit concurrent mark sweep GC freed 15833(1082KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 5.151ms total 361.823ms
,11-17 18:30:47.400  1936  1936 I HotwordWorker: onReady
,11-17 18:30:47.405  5408  5408 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
11-17 18:30:47.421  5408  5408 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,11-17 18:30:47.456  5384  5384 D AndroidRuntime: Shutting down VM
,11-17 18:30:47.479   965  1053 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1bb2c168 u0 com.lge.launcher2/.Launcher t216} time:83843
,11-17 18:30:47.529   965  1044 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,11-17 18:30:47.589   965  1044 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,11-17 18:30:47.603  1874  1874 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,11-17 18:30:47.617  1784  1784 D LCardEmulationManager: getHceAppCount hostAppNum : 0
11-17 18:30:47.617  1784  1784 D LCardEmulationManager: getDefaultRoute
,11-17 18:30:47.647  5408  5408 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,11-17 18:30:47.678  5333  5365 D AlertService: Beginning updateAlertNotification
,11-17 18:30:47.697   965  1358 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5439 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
11-17 18:30:47.699   965  1358 I ActivityManager: Killing 5082:com.android.gallery3d/u0a23 (adj 15): empty #11
,11-17 18:30:47.726   307   307 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 348us total 26.850ms
,11-17 18:30:47.752   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 519us total 24.974ms
,11-17 18:30:47.777   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 346us total 23.969ms
,11-17 18:30:47.797   965  1630 W libprocessgroup: failed to open /acct/uid_10023/pid_5082/cgroup.procs: No such file or directory
,11-17 18:30:47.807  5333  5365 D AlertService: No fired or scheduled alerts
11-17 18:30:47.808  5333  5365 I NotificationManager: com.android.calendar: cancel(0) by com.android.calendar
11-17 18:30:47.809  5333  5365 I NotificationManager: com.android.calendar: cancel(1) by com.android.calendar
,11-17 18:30:47.809  5333  5365 I NotificationManager: com.android.calendar: cancel(2) by com.android.calendar
11-17 18:30:47.809  5333  5365 I NotificationManager: com.android.calendar: cancel(3) by com.android.calendar
11-17 18:30:47.810  5333  5365 I NotificationManager: com.android.calendar: cancel(4) by com.android.calendar
11-17 18:30:47.810  5333  5365 I NotificationManager: com.android.calendar: cancel(5) by com.android.calendar
11-17 18:30:47.811  5333  5365 I NotificationManager: com.android.calendar: cancel(6) by com.android.calendar
11-17 18:30:47.812  5333  5365 I NotificationManager: com.android.calendar: cancel(7) by com.android.calendar
11-17 18:30:47.812  5333  5365 I NotificationManager: com.android.calendar: cancel(8) by com.android.calendar
11-17 18:30:47.813  5333  5365 I NotificationManager: com.android.calendar: cancel(9) by com.android.calendar
11-17 18:30:47.813  5333  5365 I NotificationManager: com.android.calendar: cancel(10) by com.android.calendar
11-17 18:30:47.814  5333  5365 I NotificationManager: com.android.calendar: cancel(11) by com.android.calendar
11-17 18:30:47.814  5333  5365 I NotificationManager: com.android.calendar: cancel(12) by com.android.calendar
11-17 18:30:47.816  5333  5365 I NotificationManager: com.android.calendar: cancel(13) by com.android.calendar
11-17 18:30:47.820  5333  5365 I NotificationManager: com.android.calendar: cancel(14) by com.android.calendar
,11-17 18:30:47.822  5333  5365 I NotificationManager: com.android.calendar: cancel(15) by com.android.calendar
11-17 18:30:47.823  5333  5365 I NotificationManager: com.android.calendar: cancel(16) by com.android.calendar
11-17 18:30:47.824  5333  5365 I NotificationManager: com.android.calendar: cancel(17) by com.android.calendar
11-17 18:30:47.824  5333  5365 I NotificationManager: com.android.calendar: cancel(18) by com.android.calendar
11-17 18:30:47.825  5333  5365 I NotificationManager: com.android.calendar: cancel(19) by com.android.calendar
11-17 18:30:47.825  5333  5365 I NotificationManager: com.android.calendar: cancel(20) by com.android.calendar
11-17 18:30:47.840  5439  5439 I AppUp4:AppBoxCP: onCreate
11-17 18:30:47.841  5439  5439 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,11-17 18:30:47.852  5439  5439 E SQLiteDatabase: Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
11-17 18:30:47.852  5439  5439 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
11-17 18:30:47.852  5439  5439 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-17 18:30:47.853  5439  5439 E AndroidRuntime: FATAL EXCEPTION: main
11-17 18:30:47.853  5439  5439 E AndroidRuntime: Process: com.lge.appbox.client, PID: 5439
11-17 18:30:47.853  5439  5439 E AndroidRuntime: j,ava.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
11-17 18:30:47.853  5439  5439 E AndroidRuntime: 	... 11 more
11-17 18:30:47.853  5333  5365 D AlertService: Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
11-17 18:30:47.871  5292  5309 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
11-17 18:30:47.879  5292  5309 E DatabaseUtils: Writing exception to parcel
11-17 18:30:47.879  5292  5309 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:30:47.879  5292  5309 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-17 18:30:47.879  5292  5309 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:563)
11-17 18:30:47.879  5292  5309 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
11-17 18:30:47.879  5292  5309 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
11-17 18:30:47.879  5292  5309 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:506)
11-17 18:30:47.879  5292  5309 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:417)
11-17 18:30:47.879  5292  5309 E DatabaseUtils: 	at com.android.providers.calendar.CalendarProvider2.acquireInstanceRange(CalendarProvider2.java:1418)
11-17 18:30:47.879  5292  5309 E DatabaseUtils: 	at com.android.providers.calendar.CalendarProvider2.handleInstanceQuery(CalendarProvider2.java:1146)
11-17 18:30:47.879  5292  5309 E DatabaseUtils: 	at com.android.providers.calendar.CalendarProvider2.queryInternal(CalendarProvider2.java:966)
11-17 18:30:47.879  5292  5309 E DatabaseUtils: 	at com.android.providers.calendar.CalendarProvider2.query(CalendarProvider2.java:865)
11-17 18:30:47.879  5292  5309 E DatabaseUtils: 	at android.content.ContentProvider.query(ContentProvider.java:984)
11-17 18:30:47.879  5292  5309 E DatabaseUtils: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
11-17 18:30:47.879  5292  5309 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
11-17 18:30:47.879  5292  5309 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:446)
,11-17 18:30:47.880   965  5459 E DropBoxManagerService: Can't write: system_app_crash
11-17 18:30:47.880   965  5459 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop104.tmp: open failed: EROFS (Read-only file system)
11-17 18:30:47.880   965  5459 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:30:47.880   965  5459 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:30:47.880   965  5459 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 18:30:47.880   965  5459 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-17 18:30:47.880   965  5459 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
11-17 18:30:47.880   965  5459 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12621)
11-17 18:30:47.880   965  5459 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:30:47.880   965  5459 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-17 18:30:47.880   965  5459 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:30:47.880   965  5459 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:30:47.880   965  5459 E DropBoxManagerService: 	... 5 more
11-17 18:30:47.881  5333  5365 E AndroidRuntime: FATAL EXCEPTION: AlertService
11-17 18:30:47.881  5333  5365 E AndroidRuntime: Process: com.android.calendar, PID: 5333
11-17 18:30:47.881  5333  5365 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:30:47.881  5333  5365 E AndroidRuntime: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
11-17 18:30:47.881  5333  5365 E AndroidRuntime: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
11-17 18:30:47.881  5333  5365 E AndroidRuntime: 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
11-17 18:30:47.881  5333  5365 E AndroidRuntime: 	at android.content.ContentResolver.query(ContentResolver.java:490)
11-17 18:30:47.881  5333  5365 E AndroidRuntime: 	at android.content.ContentResolver.query(ContentResolver.java:434)
11-17 18:30:47.881  5333  5365 E AndroidRuntime: 	at com.android.calendar.alerts.AlarmScheduler.queryUpcomingEvents(AlarmScheduler.java:168)
11-17 18:30:47.881  5333  5365 E AndroidRuntime: 	at com.android.calendar.alerts.AlarmScheduler.scheduleNextAlarm(AlarmScheduler.java:115)
11-17 18:30:47.881  5333  5365 E AndroidRuntime: 	at com.android.calendar.alerts.AlarmScheduler.scheduleNextAlarm(AlarmScheduler.java:106)
11-17 18:30:47.881  5333  5365 E AndroidRuntime: 	at com.android.calendar.alerts.AlertService.processMessage(AlertService.java:292)
11-17 18:30:47.881  5333  5365 E AndroidRuntime: 	at com.android.calendar.alerts.AlertService$ServiceHandler.handleMessage(AlertService.java:1202)
11-17 18:30:47.881  5333  5365 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:30:47.881  5333  5365 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:30:47.881  5333  5365 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:30:47.913   965  1045 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=5460 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
11-17 18:30:47.914   965  2107 I ActivityManager: Killing 5104:com.android.contacts/u0a18 (adj 15): empty #11
```
