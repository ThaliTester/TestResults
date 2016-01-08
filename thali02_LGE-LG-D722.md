#### Test 50242285ae22b3b_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.879ms
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 21.610ms
--------- beginning of system
W/ResourcesManager( 4211): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/AlarmManager(  951): ELAPSED_WAKEUP set : Alarm{218cae99 type 2 when 54437 com.android.providers.calendar} when 54437
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/Babel_SMS( 4211): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4211): MmsConfig.loadMmsSettings
I/Babel_SMS( 4211): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4211): MmsConfig.loadFromDatabase
E/Babel_SMS( 4211): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4211): MmsConfig.loadFromResources
E/Babel_SMS( 4211): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4211): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/AndroidRuntime( 4233): 
D/AndroidRuntime( 4233): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4233): CheckJNI is OFF
D/SensorManager( 4211): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4211): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4211): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 4211): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4211): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4211): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4211): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4211): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4211): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4211): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4211): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4211): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4211): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4211): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4211): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4211): found sensor: Motion Accel, handle=46
I/art     ( 4211): CheckpointMarkThreadRoots callback created = 0xb042d880
W/Settings( 4211): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     ( 4211): CheckpointMarkThreadRoots callback created = 0xb042d860
I/Babel_Crash( 4211): startup - clean
W/art     ( 4211): Suspending all threads took: 10.414ms
I/Babel   ( 4211): deleted: false for 0
D/AndroidRuntime( 4233): Calling main entry com.android.commands.am.Am
I/ActivityManager(  951): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/art     ( 1747): Explicit concurrent mark sweep GC freed 19269(1429KB) AllocSpace objects, 26(416KB) LOS objects, 40% free, 12MB/21MB, paused 1.558ms total 89.356ms
W/AudioCapabilities( 4211): Unsupported mime audio/x-lg-flac
D/ActivityManager(  951): setTaskToReturnTo : TaskRecord{2f2cdd3 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
W/AudioCapabilities( 4211): Unsupported mime audio/adpcm
W/AudioCapabilities( 4211): Unsupported mime audio/g726
D/ActivityManager(  951): setTaskToReturnTo : TaskRecord{2f2cdd3 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
W/AudioCapabilities( 4211): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4211): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4211): Unsupported mime video/mjpg
D/WindowStateEx(  951): AppWindowTokenEx init.. 
D/ContextHelper(  951): convertTheme. context->name=com.example.hello themeResourceId=16973833
W/VideoCapabilities( 4211): Unsupported mime video/theora
D/InputDispatcher(  951): Focus left window: Window{200e78c7 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 4233): Shutting down VM
I/[LGHome]EVENT( 1891): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  951): check instance of lgWin Window{2e9003c5 u0 Starting com.example.hello}
I/ActivityManager(  951): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4265 uid=10317 gids={50317, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/AudioCapabilities( 4211): Unsupported mime audio/evrc
W/AudioCapabilities( 4211): Unsupported mime audio/qcelp
I/[LGHome]EVENT( 1891): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
W/VideoCapabilities( 4211): Unrecognized profile 2130706433 for video/avc
I/HotwordDetector( 1978): Closing mic
I/MicrophoneInputStream( 1978): mic_close com.google.android.apps.gsa.speech.audio.u@7f66aa3
V/AudioRecord( 1978): stop()
D/AudioRecord( 1978): AudioRecord->stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioFlinger(  282): Record stopped OK
V/AudioPolicyManager(  282): stopInput() input 17
V/AudioPolicyService(  282): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  282): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  282): ThreadBase::setParameters() routing=0
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb383f000
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
W/AudioCapabilities( 4211): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 4211): Unsupported mime audio/qcelp
W/AudioCapabilities( 4211): Unsupported mime audio/evrc
I/[LGHome]EVENT( 1891): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  951): Starting window displayed
V/audio_hw_primary(  282): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  282): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  282): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  282): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  282): disable_audio_route: exit
E/audio_hw_primary(  282): disable_snd_device: enter 144
D/hardware_info(  282): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  282): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  282): stop_input_stream: exit: status(0)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  282): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  282): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  282): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  282): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  282): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  282): setParameters(): io 17, keyvalue hotword_active=0, calling pid 282
V/AudioFlinger(  282): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb383f000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioRecord( 1978): stop()
I/SystemUI[Framework](  951): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
W/PhoneWindowManagerEx(  951): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  951): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  951): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  951): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@354121b7,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  951): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1385): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
V/AudioRecord( 1978): stop()
V/AudioRecord( 1978): stop()
I/[SystemUI]NavigationThemeResource( 1385): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1385):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1385): , Keyguard show=false, IME shown=false, Panel expanded=false
V/AudioFlinger(  282): releasing 16 from 1978 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioPolicyManager(  282): releaseInput() 17
V/AudioPolicyManager(  282): closeInput(17)
V/AudioFlinger(  282): closeInput() 17
V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1978): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): ThreadBase::exit
V/AudioSystem( 2063): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  951): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioSystem( 1385): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1765): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2679): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3160): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread 0xb383f000 exiting
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
D/BarTransitions( 1385): draw background and invalidate : color = 8000000
W/VideoCapabilities( 4211): Unsupported mime video/mp4v-esdp
D/BarTransitions( 1385): draw background and invalidate : color = b0b0b0b
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
,V/AudioFlinger(  282): removeClient_l() pid 1978, calling pid 282
I/HotwordRecognitionRnr( 1978): Stopping hotword detection.
I/HotwordRecognitionRnr( 1978): Hotword detection finished
D/ContextHelper( 4265): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/VideoCapabilities( 4211): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 4211): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4211): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4211): Unrecognized profile 2130706433 for video/avc
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/VideoCapabilities( 4211): Unrecognized profile 2130706433 for video/avc
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/WebViewFactory( 4265): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/vclib   ( 4211): onServiceConnected
W/Babel   ( 4211): Attempted to change video mute state without an active call.
I/NotificationManager( 4211): com.google.android.talk: cancel(10436) by com.google.android.talk
I/ActivityManager(  951): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4292 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  951): Killing 2276:com.google.android.gms/u0a6 (adj 15): empty #11
I/LibraryLoader( 4265): Time to load native libraries: 2 ms (timestamps 5629-5631)
I/LibraryLoader( 4265): Expected native library version number "",actual native library version number ""
D/ConnectivityService(  951): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1dad1c3)
D/ConnectivityService(  951): dumpNetworkRequest
D/ConnectivityService(  951):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  951):     Requests:
D/ConnectivityService(  951):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  951):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  951):         NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  951):     Lingered:
D/ConnectivityService(  951): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  951): sending notification RELEASED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  951): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/WebViewChromiumFactoryProvider( 4265): Binding Chromium to main looper Looper (main, tid 1) {8bb67fa}
I/LibraryLoader( 4265): Expected native library version number "",actual native library version number ""
I/chromium( 4265): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4265): Initializing chromium process, singleProcess=true
W/art     ( 4265): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4265): ApplicationContext is null in ApplicationStatus
W/libprocessgroup(  951): failed to open /acct/uid_10006/pid_2276/cgroup.procs: No such file or directory
I/NotificationManager( 1978): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
W/chromium( 4265): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4265): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4265): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4265): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4265): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4265): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4265): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4265): Remote Branch: 
I/Adreno-EGL( 4265): Local Patches: 
I/Adreno-EGL( 4265): Reconstruct Branch: 
I/WebViewFactory( 1978): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 1978): Time to load native libraries: 6 ms (timestamps 5829-5835)
I/LibraryLoader( 1978): Expected native library version number "",actual native library version number ""
W/art     ( 1978): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  282): registerClient() client 0xb40277e0, uid 10317
D/BluetoothManagerService(  951): Message: 20
D/BluetoothManagerService(  951): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2583b1b3:true
D/BluetoothAdapterService(1061685702)( 2063): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1da6664c
D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out( 1747): propertyValue:false
W/art     ( 1978): Attempt to remove local handle scope entry from IRT, ignoring
,D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  277): [LG DATA] No such appUid: 10042
D/DnsProxyListener(  277): App 10042 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
W/ResourcesManager( 4292): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,D/libc-netbsd(  277): res_queryN name = xxxxx succeed
W/ResourcesManager( 4292): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/art     ( 4265): Attempt to remove local handle scope entry from IRT, ignoring
D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/AwContents( 4265): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4265): CordovaWebView is running on device made by: LGE
,W/art     ( 4265): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4265): Attempt to remove local handle scope entry from IRT, ignoring
V/JNIHelp ( 4292): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Activity( 4265): Activity.onPostResume() called 
,D/OpenGLRenderer( 4265): Render dirty regions requested: true
I/OpenGLRenderer( 4265): Initialized EGL, version 1.4
D/OpenGLRenderer( 4265): Enabling debug mode 0
,D/Atlas   ( 4265): Validating map...
,D/SplitWindow(  951): check instance of lgWin Window{1c26cbb8 u0 com.example.hello/com.example.hello.MainActivity}
W/chromium( 4265): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/InputDispatcher(  951): Focus entered window: Window{1c26cbb8 u0 com.example.hello/com.example.hello.MainActivity}
,W/System  ( 4292): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4292): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 1747): COMPAT: Multi user not supported
,W/InputMethodManagerService(  951): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  951): Displayed com.example.hello/.MainActivity: +1s229ms
I/Timeline(  951): Timeline: Activity_windows_visible id: ActivityRecord{4a1d10 u0 com.example.hello/.MainActivity t220} time:56399
I/NotificationManager(  951): android: cancelAsUser(2) by android
,I/Timeline( 4265): Timeline: Activity_idle id: android.os.BinderProxy@4e25711 time:56416
I/NotificationManager( 1747): com.google.android.gms: cancel(0) by com.google.android.gms
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/art     ( 4292): Suspending all threads took: 8.523ms
,W/BindingManager( 4265): Cannot call determinedVisibility() - never saw a connection for the pid: 4265
,I/chromium( 4265): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/art     ( 4292): CheckpointMarkThreadRoots callback created = 0xb042dc20
,I/ActivityManager(  951): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=4375 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     ( 4292): CheckpointMarkThreadRoots callback created = 0xb042dc10
E/YouTube MDX( 4292): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,W/art     ( 4292): Suspending all threads took: 9.853ms
D/JsMessageQueue( 4265): Set native->JS mode to OnlineEventsBridgeMode
,W/ResourcesManager( 4292): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4292): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/libc-netbsd( 4292): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4292): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/AndroidProtocolHandler( 4265): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/ResourcesManager( 4375): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4375): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4292): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/MultiDex( 4375): VM with version 2.1.0 has multidex support
I/MultiDex( 4375): install
I/MultiDex( 4375): VM has multidex support, MultiDex support library is disabled.
,I/dex2oat ( 4403): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-902619158.jar --oat-fd=40 --oat-location=/data/data/com.google.android.youtube/cache/ads-902619158.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4403): dex2oat took 106.162ms (threads: 4)
,I/QCNEJ   ( 1854): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1854): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 14:50:40.393 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/JNIHelp ( 4375): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 4375): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4375): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c5e4b12: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4375): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 4375): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 4375): com.google.android.gms: cancel(39789) by com.google.android.gms
I/NotificationManager( 4292): com.google.android.youtube: cancel(2) by com.google.android.youtube
,D/jxcore_app_log( 4265): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1618835968
D/JX-Cordova( 4265): jxcore cordova android initializing
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4292): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4292): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4292): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 4292): Found 10006
,W/jxcore-log( 4265): Initializing JXcore engine
W/jxcore-log( 4265): JXcore engine is ready
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4292): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
D/NativeLibraryUtils( 4375): Install completed successfully. count=14 extracted=0
,W/Thread-466( 4427): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6558]" dev="sockfs" ino=6558 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-466( 4427): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-466( 4427): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7482]" dev="sockfs" ino=7482 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-466( 4427): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-466( 4427): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-466( 4427): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[20821]" dev="sockfs" ino=20821 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 4265): Starting JXcore engine
,D/libc-netbsd( 4292): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4292): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4292): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4292): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  277): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out( 4292): propertyValue:false
D/libc-netbsd( 4292): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4292): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/google-breakpad( 4462): -----BEGIN BREAKPAD MICRODUMP-----
W/google-breakpad( 4462): O A arm 04 armv7l 3.4.0+ #1 SMP PREEMPT Mon Apr 13 18:54:53 KST 2015
W/google-breakpad( 4462): S 0 98C87DF0 98C87000 00003000
I/ActivityManager(  951): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4463 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/google-breakpad( 4462): S 98C87000 090000000077A49FFC70C8987870C898A070C8988870C8985070C8989077C898000000007870C898A877C89801000000000000009077C8986470C89838AA01998840A99FB854A99F808CAB9F9077C898000000007870C898A877C898010000001471C8985C1A01990077A49FFC70C898D470C89801000000E874C898400000000053EEAA208B849800000000C085AE9FE874C8984000000000000000202A2A990000000000000000000000000000000001000000E08603991A000000170000001B0000000800000040B3909808000000F079C898000000007071C8980500000030948598E874C89800000000040000004471C898782E2A994091B29F30948598A877C89801000000010000000077A49F08000000000000009077C898309485980077A49FE874C8987071C898208B8498309485981894859800000000F874C8986C71C898E02F2A990C77A49FBC71C898A471C8980077A49FE874C898BC71C898B471C898E874C8989C71C898F49536993094859818DA7499908EC898E6FFFFFF
W/google-breakpad( 4462): S 98C87180 0C77A49FBC71C898000000000100000008DEF0B60077A49F2C72C898C0C93699D471C89800A50199000000000000000000000000189485989077C898B090829800359298040000000100C898000000003491B29FE071C89800C82C9C0100000030C32C9C01000000207DC898000000001876C8983491B29F0077A49F020000001891B29F9D4198816472C898000000000077A49F60DB759901000000E874C898FFFFFF00F874C898FC72C89804DA369900000000FFFFFF0001000000000000000000000001000000B876C8980000000000359298606685982030C599050000000077A49F2430C599A472C898507502990000000000000000000000000077A49F010000002430C599A472C8987C7028990077A49F01000000010000002430C599D472C89870C528998840A99FB854A99F808CAB9F00000000DC72C8980077A49F309485980077A49F208B849800359298FC72C89834092A991075C898E874C898F874C8980077A49F60DB75990100000000000000010000009473C898307F2A99
W/google-breakpad( 4462): S 98C87300 1075C898FFFFFF0001000000000000000077A49FF874C8989473C898549D2A996473C89808DEF0B6705E2399585E239901000000309485984C73C8986C73C8980077A49FD473C89810C08298B854A99F808CAB9F01D8937D0000000070238598D474C89860DB7599E073C8989D41988160DB75990077A49FE874C898F874C898208B84980077A49F60DB7599585E23991C74C89814FC2A99705E2399010000001075C8980100000000000000F874C898F874C898D873C898705E23993500000001000000208B849800000000F874C89810C082980000000000000000F073C8980100000060DB7599000000004091B29F80FF8298760000016876C8980077A49F1075C898FD9AB79F0077A49F01000000FD9AB79FF874C8989475C898D01B3499010000001075C898000000001090B29F7890B29FA090B29F9091B29F4091B29F0191B29FC890B29F6874C89800000000000000000077A49F350000000000A49F0000C898F46368992C75C89808DEF0B680FF829800818498408C849800000000
,W/google-breakpad( 4462): S 98C87480 00000000020000000000000000000000020000000077A49F6876C89801000000B876C898FFFFFFFFDC74C898683F09990077A49F11000000000000006876C8986876C8980E0000000077A49FA090B29F9091B29F003592980000000082FFFFFF0000000082FFFFFF208B84980E0000006876C8980077A49F00359298A090B29F0C75C8983C2700996876C8982894DE460A00000081FFFFFF097BB69F0077A49FC08CA99F7076C8986475C8980077A49F808CAB9FF47DC89800000000000000000000000000000000D075C89801000000C079C898400000000053EEAA308D8498000000004005C799C079C8984000000000000000202A2A99D075C8989875C8982090849880FF82989D41988101000000BC75C89898983499000000006876C8980040A99F08DEF0B601000000000000004876C8980500000030948598C079C89800000000040000001C76C898782E2A9928FF74990100000080FF8298C875C898000000000077A49F08000000000000001500000002000000FFFFFF00C079C898
W/google-breakpad( 4462): S 98C87600 4876C898308D8498309485981894859800000000D079C8984476C898E02F2A99F03CA79F00000000000000000077A49FC079C8989476C8988C76C898C079C8987476C898F49536993094859818DA74998091C898E6FFFFFF0C77A49F9476C898000000000100000008DEF0B60077A49F0477C898C0C936990077A49F8876C89800000000000000001883C898189485980077A49FB0908298003592980400000001008498F571EBB60000000015000000000000001077C8980077A49F00E49B9F1200000000040000587EC89808DEF0B60077A49F00C09B9F040000009D4198810077C898000000000077A49F60DB759901000000C079C898FFFFFF00D079C898D477C89804DA369900000000FFFFFF0001000000000000000000000001000000050000000000000000000000000000000077A49F4077C89800000000000000000000000008DEF0B6000000000000000000000000000000000077A49F0077A49F01000000010000006066859800359298E879C89800359298AC77C898BCC42899
W/google-breakpad( 4462): S 98C87780 8840A99FB854A99F808CAB9F00000000300D73990077A49F309485980077A49F308D849800359298D477C89834092A99E879C898C079C898D079C8980077A49F60DB75990100000000000000010000006C78C898307F2A99E879C898FFFFFF0001000000000000000077A49FD079C8986C78C898549D2A99D87F8F9F08DEF0B6705E2399585E23990077A49F309485982478C8980000000000000000AC78C89810C0829800000000E87F8F9F010000000000000070238598AC79C89860DB7599B878C8989D41988160DB75990077A49FC079C898D079C898308D84980077A49F60DB7599585E2399F478C89814FC2A99705E239901000000E879C8980100000000000000D079C898D079C898B078C898705E23993500000001000000308D849800000000D079C89810C082980000000000000000C878C8980100000060DB7599105868990700000080FF8298760000010178C8980077A49FE879C898FD9AB79F0077A49F01000000FD9AB79FD079C8986C7AC898D01B349901000000E879C898
W/google-breakpad( 4462): S 98C87900 00000000000000001879C8980000000000000000000000000100000000000000B01C73999D419881208B849888FFFFFF35000000D8D026996879C898F4636899047AC89808DEF0B680FF829800818498C08D84980000000000000000020000000000000000000000C813B99F010000000004000008000000000000000800000090C0C699000000800000008000000000A079C8980000000000010000000000000100000000000000B879C898003592980000000082FFFFFF0000000082FFFFFF308D8498010000001A00000017000000003592980800000040B3909808000000F079C898000000000A00000081FFFFFF1C000000000000000001000000000000017AC8980077A49F808CAB9FCC82C89800000000000000000000000000000000A87AC8982014B99F039BB79FE013B99FE013B99F00000000547AC898A089129980FF82989D4198810077A49F0077A49FA87AC898707AC8982090849880FF82989D41988101000000947AC8989898349900000000000000000077A49F08DEF0B6
W/google-breakpad( 4462): S 98C87A80 010000000077A49FC813B99FA07AC8981C7EC898B09A3499A87AC89800000000C813B99F0000000028FF74990100000080FF8298A07AC8980000000000000000560000000077A49F000000000000000000000100000100000000000000000000000000000000000000000000000000000101000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001000001000000000000000000000000000000000000000001000100000101010000000000000000000000000000
W/google-breakpad( 4462): S 98C87C00 000000000000000000000000,0000000000000000000000000000000060918498000000000100000001000000000000000000000000000000000000000077A49F9C7DC89860DB7599A87CC898987CC8980077A49F9C7DC898E47CC89878A42A990000000000000000000000000000000000000000C07DC898C07DC898A07CC8989C7CC89800000000000000000000000020D0829838A2829820D082980000000000000000987EC89820D08298987CC8989C7DC898000000000000000000000000000000000077A49FC813B99F000000000077A49F010000000000000088FFFFFF5C7EC898D01B3499C013B99F00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000B8000000000000000077A49FF4636899F47DC89808DEF0B6003B85980000000000000000E0D08298000000000200000000000000000000000077A49FCC40A99F00000000A877C8980180959FC0F18498000000000000000020B882989D419881
W/google-breakpad( 4462): S 98C87D80 AC7DC898547EC8980077A49F03000000CC7DC8980070A99F003B8598301B91980000000082FFFFFF0000000082FFFFFF40B082980040A99FC813B99F01000000609184980077A49FC0F1849800000000000000000000000003000000AA0000006B0000006E41010000000000207EC898687EC89800000000687EC8984C7EC898387EC89800000000848EC898F0B34399407EC89800000000347EC89884D12699000000000000000008DEF0B600000000BC81C898349B34990077A49F0077A49FC813B99F01000000801D8598003B85980077A49F00000000B812B99FC812B99F010000002F00F0B60010000008DEF0B6001000000077A49F6013B99F907EC8980C82C898B09A349902000000000000006013B99F0000000028FF749901000000003B8598907EC898000000000000008000000000000000000000000000000000020000006177C8980001289CFFFFFFFF00000000000000000E0000000080A99FEC7EC898007EC898000000E00600000000000000010000000883C89840000000
W/google-breakpad( 4462): S 98C87F00 0053EEAA40B982980C0000000004C7990883C898400000000C000000202A2A990084C89801000000D096289C6800000000000000000000000000000000000000507FC89800000000100000006880C898607FC89800000000F07FC89811000000A09385980883C8980000000010000000C47FC898C47FC8980077A49FB89385980000000000000000AE0100000077A49F080000000800000014000000B89385980077A49F0883C898F07FC89840B98298B8938598A0938598000000000483C898EC7FC898E02F2A990C77A49F3C80C898260200000077A49F0883C8983C80C8983480C8980883C8981C80C898F4953699B893859818DA74992085C898E6FFFFFF0C77A49F3C80C898300000005480C8984480C898F891B29FAC80C898EE1DB19F908DC898108BC89800000000000000002C0000004480C898E090C898CC40A99F5480C89878390A99188BC898188BC8980481C89828A0B29F8C80C89874790399000000007031A79F808CAB9F04000000D41DB19F60DB75990077A49F00000000
W/google-breakpad( 4462): S 98C88080 E8347BC10040A99FE480C898D0870399C480C8987031A79F010000000883C898E073BF9FE8347BC1D41DB19F00D39198040000000000000001000000B16CF6EE188BC898308BC89804000000D41DB19F60DB7599000000000200000044D7FFFF2C81C89810A40A99188BC898188BC898D89FB29FEE1DB19FD89FB29F000000002C81C898101F0199E046BF9F10A0B29F188BC89838A0B29F2902000038A0B29F00000000D890C8987C81C898FC9A01990077A49F00000000E851CC8D5481C8989C81C89801000000308BC898E090C8980000000000000000E046BF9F188BC89811000000308BC8981A02000001000000889FB29F188BC898AC81C89800A50199FFFFFFFF008EC898308BC89827000000188BC898188BC8989882C898308BC89801000000889FB29F5C82C898E0A70199788BC898188BC898188BC8982094B29FC8000000943A6899383A689900000000308BC898383A6899383A6899943A689974000000FC81C8980900000001000000308BC898E090C8980100000044D7FFFF
W/google-breakpad( 4462): S 98C88200 4C82C898188BC89813000000308BC898C80000009082C898E090C898F893B29FF893B29F70DE9198188BC898000000005C82C89800B2009900000000188BC898000000009882C898308BC8989C82C898F089C898000000000100000050D39198C0E68398000000007082C898803E8598C0E6839826D99B9F0400000000020000F089C8988800000000000000B09FB29FAC82C898AC82C89800020000505C6899F089C89800000000CC82C898B8300999B09FB29F01000000F089C898880000000077A49F00000000EC82C898345E0999F089C898B09FB29F60DB75990077A49FD89FB29F260100007483C89844760999F089C8982BD99B9FF089C898F089C898105868990A000000A8010000350000003483C8983483C898F089C89860AF8B9F35000000F089C898B8AF8B9F0077A49F7483C89830D99B9F00000000F089C898F089C8983E000000000000000077A49F6C83C8986C83C89800000000F089C89800000000000000009483C898FC3A09999483C8986CF60999F089C898F089C898
W/google-breakpad( 4462): S 98C88380 10A0B29F60DB75990077A49F020000001C84C89860760999F089C8980CD99B9F0400000000020000F089C89817D99B9F03000000F089C898F089C89856000000560000000077A49FE483C89822D99B9F03000000F089C898F089C898560000005600000031D99B9F08000000F089C89837000000370000000077A49F020000001C84C8981C84C898F089C8983700000088000000450000004C84C898983E0999F089C8980000000060DB759988000000450000000077A49FF089C89801000000408AC898FFFFFFFF7C84C898683F0999E8AF8B9F110000009C84C898F089C898F089C898100000000077A49F02000000000000000077A49FA484C89832D99B9F00000000F089C898F089C898020000003A00000000000000BC84C898BC84C89800000000F089C898609FB29F3A00000010586899020000004485C898408409990200000001000000408AC898FFFFFFFF0485C898683F0999D8AF8B9F000000002485C898F089C898F089C898030000000077A49F01000000000000000077A49F
W/google-breakpad( 4462): S 98C88500 2C85C89804D99B9F0000000035D99B9F01000000F089C898F089C8983800000000000000FFFFFFFF4485C8984485C898E89EB29FF089C8980077A49F000000008C85C89810E409990100000001000000408AC898589DB29F8C85C898683F09993A000000000000008C85C898F089C89860A0B29F60DB75990000000060A0B29F0C0100000077A49F1486C898887B0999609FB29F0BD99B9F01000000F089C89860000000510000000000000057000000CC85C898CC85C898F089C898600000000077A49F000000001486C89868DC0999EC85C898A83F0999C8FFFFFF36D99B9F05000000F089C89888A0B29F510000000000000060A0B29F1486C8981486C898F089C89888A0B29F60DB7599000000009C86C898F47609990000000057000000AC86C89860760999F089C8984486C89801000000F089C8987486C8980077A49F6486C8986486C898010000007486C898F089C898AC92B29F0077A49F00000000D4FFFFFFD8D89B9FB85C6899F089C898D300000051000000B7000000F089C898
W/google-breakpad( 4462): S 98C88680 309DB29FF089C898309DB29F00000000B0A0B29FEE0000002487C898EC6B0999010000000077A49FC486C89864C00999089DB29FB7000000D3D89B9F000000004C87C89844780999F089C898010000000400C89800000000000000004C87C89800000000F3000000FFFFFFFFFFFFFFFF00E49B9FF089C898F089C89807000000B0A0B29FF089C8980077A49FF089C8980077A49F00000000B0A0B29FEED89B9F9487C898A4A009990000000000000000010000004C87C898F089C898600000000077A49F000000009487C8980100089900000000000000005088C89800000000EE000000FFFFFFFFFFFFFFFF12000000F887C898F089C898B0A0B29F60DB75990000000000000000B20000000077A49F1C88C8987474099900000000F0220A99C031929830150A99C03192980077A49F010000001090B29F7890B29FA090B29FB0A0B29F309DB29F88A0B29F60A0B29F609FB29F38A0B29F10A0B29FB09FB29F9894B29F0000B29F000068991090B29F944A68995090B29F8D00000047000000
W/google-breakpad( 4462): S 98C88800 3488C898983E0999A090B29F0000000060DB75998D000000470000000077A49FF089C89801000000408AC8980077A49F6488C898683F09990077A49F1100000000000000F089C898F089C8981D0000000077A49FA090B29FC890B29F0077A49F8C88C898A83F0999FFFFFFFF602FB39FE889C8982D000000F089C8980077A49F2B020000000000009488C898C088C898F089C898D046A5E5002EC3990040A99F092EC3990077A49FC08CA99FF889C898EC88C898EC88C898B8A8C5018B2FC399092EC399C701000006000000F089C89800000000F089C89801000000F089C89801000000F889C8982C89C89898432E99EC5FF1B601000000EC5FF1B61F0000004A0000009900000060DB7599F089C8980077A49F3890B29F60DB7599308BC8984C40A99F188BC898F089C898010000003890B29F08DEF0B65489C898CD2BEBB6108EC898EC5C0A990080A99F188BC8986489C8989C6200994091C8980077A49F2C91C898C8E108999C89C89800000000944A6899010000007E05000002000000
W/google-breakpad( 4462): S 98C88980 1090B29FA889C8981090B29FA089C89860338498C0E6839890E48298803E8598A04C73990000000008798F9F0000000000000000B9000000000000007E0500001800000001000100000100000001000000000000000000000000000000000000000000000000000000000000000000003890B29F00000000803E859800E49B9F0077A49F108AC89800000000000000000077A49F208AC8980077A49F288AC89800000000000000000000000070040000000000007E0500000000000000D89B9F0077A49F00D89B9F38010000000400000077A49F00C09B9F0077A49F00E49B9F49000000000400001E00000071040000370100009A0500002D000000108BC898408AC898188BC898944A6899000000000000000000000000000000000077A49F7E05000000000000090000000000000000000000C08AC8980077A49FC88AC89800000000000000000000000000000000010000008092B29F00000000000000000077A49F503FA79F01000000010000000077A49F008BC8980077A49F403FA79F
W/google-breakpad( 4462): S 98C88B00 010000000100000005006099020000001F00609902000000300D73995097C898FDFFFFFF0C77A49F0077A49FCC40A99F0077A49F408BC8982000000080000000000000001C000000250000002A0000003D000000480000005700000098000000C800000008010000190100001B0100001C01000025010000450100004F010000650100006C0100008C0100008E0100008F0100009001000091010000920100009301000094010000AD010000E3010000FE0100002C0200002E020000FFFFFFFFF4010000150200002B020000320200003F0200006C0200006E0200006F0200007D0200007F02000080020000A2020000A5020000A6020000D0020000F3020000010300001F03000020030000440300005603000067030000690300006B0300006C030000780300007B030000FFFFFFFF0077A49F348EC898481B769960DB75993C8EC89801000000EC8CC8984C852A99705E23995100000060E368990000000000000000408EC898848CC8985005359910C1C6990100000008DEF0B660E36899
W/google-breakpad( 4462): S 98C88C80 705E239980868598B48CC898000000000000000082FFFFFF018DC898008DC898F83473995097C898E6FFFFFF0C77A49F518DC898848CC898808CC898948DC8983C8DC8989D419881808CAB9F51000000D88DC898508EC898348EC898000000003C8EC89801000000848DC898A8E62A9980868598000000005100000010C082980000000024DA7499408DAB9F00010000D89FF0B6000000000000000000000000985FF1B6007D15000084C5990B34EEB6000000000077A49F70040000010000007E0500001C000000A089C8983E00000010000000290200002A020000988DC898B0D1919800002440100000003A000000030000002A0200002B020000408EC8980000000000000000000000003B0000000E0000002C0200002D02000082FFFFFF0000000000000000000000003C0000000E0000002E0200002F0200000040A69FB0D191980000F03F000000000000000003000000000000009C050000A2FAB09FEC1DB19FE81DB19F9019B19FEE1DB19FEE1DB19F08798F9F0000000000000000
W/google-breakpad( 4462): S 98C88E00 0077A49F007D959F04000000400000004500720072006F0072003A00200059006F00750020006D006100790020006E006F0074002000680061007600650020006100200072006500610064002000610000000000000000000000010000010000000000000000000008DEF0B6000000000077A49F1CB34399908EC898000000000C92C898349B34990000000000000000C812B99F0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000100000100000000000000000000000000000000000000000100010000010101000000000000
W/google-breakpad( 4462): S 98C88F80 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001000000010000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000010000000101000100000000000100010001000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000077A49F00000000188BC898000000000090B29F1090B29F8092B29F0000000000000000000000004C40A99F01D082980077A49FCC40A99F789BB29F308BC8980190C898904484980000000000000000
W/google-breakpad( 4462): S 98C89100 0077A49F9D4198818491C898DC91C8980077A49F030000005491C8980070A99F803E85980080A99F9C91C8981CB3269900000000585E23998491C8980040A99F904484988840A99F803E85980077A49F90448498000000000000000000000000600000000501000030020000F7E05200905B2E05F7EFE5520077A49FC492C8980C92C89878A42A990000000078D1749960DB7599C093C8980C92C898E892C898E892C898C891C898C491C8987C047599904484988840A99F70E08298D0D9839870E0829808AE3399FC91C8980077A49F000000005012B99F1012B99F80C1BE9FF010B99F7C92C8980077A49F9D4198810077A49F88FFFFFF0000000088FFFFFFE092C89860DB75998493C898905E3499C012B99F0093C8980000000000000000000000000000000000000000000000000000000000000000D08F8398000000003700000000000000B80000000000000000000000F46368991C93C89808DEF0B6803E8598F08D8498208E8498E0E18398000000000022919800000000803E8598
W/google-breakpad( 4462): S 98C89280 000000000000000000000000000000003816B99F3016B99F00000000F110B99F0000000000000000F110B99F0000000000000000E0A2829840B0829840B082980077A49F50D29198F08A849888FFFFFF0000000082FFFFFF40B0829800000000C812B99F0000000070E0829881FDEDB60077A49FCC40A99F00000000408DC89828FF749901000000803E8598E092C8980000000000419881000000000077A49F808CAB9F0000000000000000000000000000000000000000C093C898C812B99F1B2EC3995012B99F1010B99F000000006C93C898A089129980F682989D4198810077A49F0077A49FC093C8988893C898C0E6839880F682980000000008798F9FAC93C8988C9834990000000008DEF0B60010000008DEF0B6001000000077A49F8097C898B893C8983497C898B09A349930AD83980077A49F8097C8980100000028FF74990100000080F68298B893C898000000000000000000000000000000000000000000000000010100000000000000000000000000000000000000000000
W/google-breakpad( 4462): S 98C89400 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000077A49F0077A49F1095C8989495C898300575990495C89890FC36990077A49FE896C8981C95C898703D3799E896C89840B082980100000000000000C80375999495C8982C10B99F300575993495C89864C533990000000000F6829840B08298D896C8983495C8980077A49F0077A49F010000002010B99F00000000AC96C898D01B34990000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000F4636899
W/google-breakpad( 4462): S 98C89580 4496C89808DEF0B600F682980000000000000000C0E68398000000000200000000000000000000000000000000000000000000000000000000000000000000010000000101000100000000000100010001000000000000000000000000000000000000000000000000000000000000000000000082FFFFFF0000000082FFFFFF000000000000000000000000000000000000000000000000000000000000009F0077A49F000000008890C898008E819F0090B29F1090B29F4490B29F000000009887C8980077A49F808CAB9F0000000000000000000000000000000000000000D896C8986010B99F4F2EA69F2010B99F2010B99F000000009496C898A089129900F682989D4198810077A49F0077A49FD896C898B096C8980000000000F682989D41988101000000D496C8989898349900000000DC97C8980898C89800F682986497C8980077A49FD896C8984097C8982497C89894A3349918FF74990000000000F682980100000040B0829888FFFFFF40B08298000000008897C898042D4699
W/google-breakpad( 4462): S 98C89700 6E6100006497C8988897C8980077A49F8097C8989D41988108798F9F08DEF0B67097C8980077A49F2098C898E897C898DC97C898649F34990001000040B0829840B0829840B082988097C8980100000000000000F6FFFFFF0C77A49FFCCC23990077A49F7097C8980300000008000000C0E6839888FFFFFF40B0829888FFFFFF70E0829888FFFFFFC0E6839888FFFFFFA897C898A497C89800000000A897C898CC97C8982C5C46990000000082FFFFFF0077A49F9D419881000000000077A49F3098C8982098C8982898C8981C98C89882FFFFFF00798F9F0C98C898D0D1239900798F9F2898C89840B0829888FFFFFF88FFFFFFB898C89801000000C898C8983898C898000000006C98C898706346992898C898000000000000000040B08298C0E6839888FFFFFF0000000082FFFFFF0100000000798F9F0000000082FFFFFF0077A49F00000000A898C898D898C898F498C8988898C8981899C898C898C8981099C898B898C8985499C898A4204499B898C89888AC7FB455000000A898C898
W/google-breakpad( 4462): S 98C89880 9898C8987099C898C0E6839888FFFFFF0077A49F00000000C0E6839888FFFFFF0077A49F0000000040B0829888FFFFFF0077A49F0000000070E0829888FFFFFF0077A49F000000001C9CA59FB0FD7F992337000000F0F7AA00F0AD9F6E6100006E61000001DEF0B60000000000F47BB40077A49FF8788F9F070000000000000001EC7BB40000000000F47BB40077A49F0100000094EC7BB40000000082FFFFFF00000000000100000077A49F00004300000055006099C8987099C898F8F21B760031EF128034F41200F0F7AA203CFD128C99C898B46F4399000000007B03000070E0829888FFFFFF0077A49F0000000070E0829888FFFFFF0077A49F00000000D0F35F99E068949F9C99C8982C5943997B030000603BFD12000000000D518FB078FA1B760000000001000000E02BEE1200000000603BFD12F8F21B760031EF128034F412203CFD12000000007B3A8FB0F8F21B76E02BEE12403CFD12C0A8F812C8F51B76E030EF12403CFD1210B1EF1200F0F7AA403BFD1200000000FC980000
W/google-breakpad( 4462): S 98C89A00 60E0F3124031EF12E02BEE12E030EF12FC90EF12C8F51B76E030EF12E02BEE12E02BEE120069E51200000000A5438FB0C8F51B76E02BEE12E030EF12CF9659B4C8F51B760069E512449AC89800000000549AC89838F41B76D033C51238F41B76D033C512A0F6C612E02BEE12093D8FB038F41B760069E51278031C76CDFC8DB078031C76E02BEE12D033C512A0F6C6129830A0707891A59FFFFFFFFF000000000000000000CBED120069E512807FDE1238C99B7038CB9B70000000002138537438C99B70FFFFFFFFF1DF0000000000000069E512807FDE12A030EF128338537438CB9B70000000004D280000F78D9374A813A0706013A07000CBED126013A070807FDE12A030EF12A030EF12258A93746013A070807FDE1228CF9B70A030EF120069E512A91000004D280000894153746030EF12000000004080EF120000000000000000A030EF1200CBED122FF28DB00000000058041C7600CBED12A030EF120069E51200000000A89BC89853F38DB058041C76886D7FB46810D6B500000000
W/google-breakpad( 4462): S 98C89B80 0000000000000000959BC898A09BC898489CC898C89BC898E09BC898398359B40000000000CBED1258041C7684F0F7AA00F0F7AA58041C76609CC8983DC66DB4489CC8983BA88CB0040000003BA88CB0489CC89808DEF0B60B0000006BF7EEB60000000000000000000000000000000000000000FFFFFFFFF89BC8989D4198812C9CC89800CBA09F00000000489CC898309CC898209DC898409DC89800CBED123BA88CB049A071B4489CC8983BA88CB000F0F7AAF92BEBB6746F727308DEF0B6010000000A00000000000000000000003BA88CB00100000004000000609CC89800CBED129D419881000000009D419881000000009D419881A49CC8986B9DC89808DEF0B6B89DC898109DC898E4CF7FB4409DC898218774B4E4CF7FB4A021EF12000000009FEE78B461642D34619DC8980000000000F0F7AA80D17FB4109DC898E4CF7FB4209DC89804FDFFFFF30673B400000000000000000000000000000000000000000000000040BB7FB408DEF0B6388283B4189DC898E0F47BB4ACED7BB4
W/google-breakpad( 4462): S 98C89D00 FCCF7FB4E0F47BB494EC7BB4A8EC7BB40100000000005500000000000000550000F0F7AA00CBA09F80C287B400F0F7AA43000000550000000000000000000000000043007800000008D6829F859CEBB6FFFFFFFF000000000000000000000000145468726561642D343636009D419881FFFFFFFF00D6829F40D6829F00D6829F7800000008D6829F08D6829F056AEBB6B09DC898256AEBB6056AEBB608D6829F056AEBB6154AEBB6B09DC89800000000B09DC89800D6829F1600000000000000000000009D419881000000003091A59F50768F9F40768F9F48768F9F000000000000000000000000000000000000000000000000000000000000000000F0F7AA00000000000000000000000080BF839F70CBA09F0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000CBA09FEC69A39F4C40A99F0000000000000000E4477F990000000000000000
W/google-breakpad( 4462): S 98C89E80 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 4462): C 0600004000000000000000000000000000000000687EC898287EC8980077A49F287EC89800000000647EC898C093C8980C7EC898A0DB7599F07DC89808434699F845EBB630000D600000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 4462): M B6F2F000 00000000 00002000 8734159D8182F72B5360108998F669D60 app_process32
W/google-breakpad( 4462): M 98C8A000 00000000 00AE1000 10FB4E5C3E6238990CCE2CA03AC6B3420 libjxcore.so
W/google-breakpad( 4462): M 9E54D000 00000000 0000A000 92434EED1D88531F6F531210F620E1D70 libqservice.so
W/google-breakpad( 4462): M 9E557000 00000000 00008000 73BEACFB34F012C578F2CBCFA3A714560 libqdutils.so
W/google-breakpad( 4462): M 9E55F000 00000000 00005000 878BE07CFBE9CD8D1D67C45CE007A7BA0 libmemalloc.so
W/google-breakpad( 4462): M 9E564000 00000000 00005000 52A6412D61E6C42CA6A57FF38AD4FC0C0 gralloc.msm8226.so
W/google-breakpad( 4462): M 9FD2A000 00000000 00469000 F4AB4C6F6CCEC72B081FA92634F9DF360 libsc-a3xx.so
W/google-breakpad( 4462): M A1B3A000 00000000 01AE1000 488126E5C3F082244EC0664CC97A94320 libwebviewchromium.so
W/google-breakpad( 4462): M A7F3A000 00000000 00003000 9334D9805B275A75829ECC69380A5D2E0 libwebviewchromium_loader.so
W/google-breakpad( 4462): M A7F3D000 00000000 00003000 8FF5949AE957364C270D0F448DAD4FE20 libjnigraphics.so
W/google-breakpad( 4462): M A7F40000 00000000 00008000 F5D3384E9BEEEDF600C2C4D02CB7146A0 libcompiler_rt.so
W/google-breakpad( 4462): M A7F48000 00000000 00010000 E4CEF5EDFBB5994F920E12960C27E0BC0 libandroid.so
W/google-breakpad( 4462): M A7F58000 00000000 0013B000 9C07A5706C6FD8E13025C6918642A80F0 libGLESv2_adreno.so
W/google-breakpad( 4462): M A8094000 00000000 00034000 CF692CC2042CC03999A6210A4668E2EF0 libGLESv1_CM_adreno.so
W/google-breakpad( 4462): M A80C8000 00000000 00027000 E48344CD23F82BA0E7B940BC32BBBECF0 libgsl.so
W/google-breakpad( 4462): M A80F0000 00000000 00004000 EB49C798524706CBF3372BB9DFBB92C20 libadreno_utils.so
W/google-breakpad( 4462): M A80F5000 00000000 00029000 C29A639A4AEAC88466F1ACCA732D030E0 libEGL_adreno.so
W/google-breakpad( 4462): M A9559000 00000000 00018000 AF017574A7821CB2261DD3AD8E68B8110 libjavacrypto.so
W/google-breakpad( 4462): M A9571000 00000000 00004000 B472CADC2448C211F1E320D88D27B5420 libemoji.so
W/google-breakpad( 4462): M A9575000 00000000 00009000 0D2F47D82DA4058B87D201CB8CFCC0BA0 librs_jni.so
W/google-breakpad( 4462): M A957E000 00000000 00006000 11185286066C9E9FCD6823AD5566C0A10 libaudioeffect_jni.so
W/google-breakpad( 4462): M A9584000 00000000 00004000 CDA9BA072D4DECC71C5E63467275E7EE0 libsoundpool.so
W/google-breakpad( 4462): M A9588000 00000000 00004000 82A278A7E21B4A314D9BE16CAA239F060 liblg_parser_qcp.so
W/google-breakpad( 4462): M A958C000 00000000 00006000 668D1570CE3FD1F09D9FEB0BE8EF85AC0 liblg_parser_ogm.so
W/google-breakpad( 4462): M A9592000 00000000 00014000 10C26557F124644418D3776ACB0060640 liblg_parser_mkv.so
W/google-breakpad( 4462): M A95A6000 00000000 00007000 382E4730DF55A022477523CBB8FCC9710 liblg_parser_flv.so
W/google-breakpad( 4462): M A95AD000 00000000 00004000 F4B87DC6C74B91E84FE7777B3E5906010 liblg_parser_dts.so
W/google-breakpad( 4462): M A95B1000 00000000 0000C000 8E274BF3A141EC3CE5429E0CE1FA30CB0 liblg_parser_avi.so
W/google-breakpad( 4462): M A95BD000 00000000 0000B000 F063E5B8FB9C577438EDFB5611B924190 liblg_parser_asf.so
W/google-breakpad( 4462): M A95C8000 00000000 00004000 128196E62A9943A933F1E1195A96BE220 liblg_parser_ac3.so
I/NotificationManager( 4292): com.google.android.youtube: cancel(10436) by com.google.android.youtube
W/google-breakpad( 4462): M A95CC000 00000000 0000D000 1A3AE0BAE05AA19C0E70341D14A70F6F0 libLGCodecParserUtils.so
,W/google-breakpad( 4462): M A95D9000 00000000 00052000 873911679066EA28A04C3C2D929030F30 libLGParserOSAL.so
W/google-breakpad( 4462): M A962B000 00000000 00004000 3FA8B89358F6F38194ED11741859BF530 libjhead_jni.so
W/google-breakpad( 4462): M A962F000 00000000 0000E000 D791A978CC1F875366C3FDE9B33194060 libstagefright_amrnb_common.so
W/google-breakpad( 4462): M A963D000 00000000 0001A000 F596626166534B070F7B57DA85DCA86F0 libvorbisidec.so
W/google-breakpad( 4462): M A9657000 00000000 00009000 2C13DEB1B6771414DD42E8EFCE50D0250 libstreamingpolicy.so
W/google-breakpad( 4462): M A9660000 00000000 00004000 9D3A1EEE172AFB35E2663261B36F7D400 libstagefright_yuv.so
W/google-breakpad( 4462): M A9664000 00000000 00005000 21A9B2A67B28A953FC06D733BC7BDD8C0 libstagefright_timedtext_xsub.so
W/google-breakpad( 4462): M A9669000 00000000 00006000 C2198A2C485ADBA7ED8DEB50EAE941270 libstagefright_timedtext_ccparser.so
I/ActivityManager(  951): Killing 4003:com.lge.lgfota.permission/1000 (adj 15): empty #11
W/google-breakpad( 4462): M A966F000 00000000 0001D000 C14A741B903F5EA74CA7E1D7804F51960 libstagefright_omx.so
W/google-breakpad( 4462): M A968C000 00000000 00007000 741CD0CBF5589F8EDBD02FD7023550580 libstagefright_avc_common.so
W/google-breakpad( 4462): M A9693000 00000000 0003A000 E5C670B735242BF581AAFAC97791DAAD0 libopus.so
W/google-breakpad( 4462): M A96CD000 00000000 00013000 AA0E6577B8B0FA7B315600FCEE36A0D20 liblgetars.so
W/google-breakpad( 4462): M A96E4000 00000000 00006000 AC1D7BAE26791BE91E8BCCB199F3926F0 liblgresampler.so
W/google-breakpad( 4462): M A96EA000 00000000 00005000 3959C688C8EDD647686EDC0D8FBE83110 liblgaudioutils.so
W/google-breakpad( 4462): M A96EF000 00000000 00159000 AA53BE7B94973C966CB182C74E81276B0 libstagefright.so
W/google-breakpad( 4462): M A9AEB000 00000000 00015000 A600837AA56318B462C907F827B457BF0 libmtp.so
W/google-breakpad( 4462): M A9B00000 00000000 0026B000 5F714815D0836D204C046E173AC47EC80 libWVStreamControlAPI_L3.so
W/google-breakpad( 4462): M A9D75000 00000000 0003C000 260D535C70B24A059C3DD13D265601400 libmedia_jni.so
W/google-breakpad( 4462): M AB000000 00000000 00003000 E11DA546CE9E08D1D647E8E1135DAD810 libstagefright_enc_common.so
W/google-breakpad( 4462): M AB003000 00000000 0000B000 C23E765DA7EFD456B11A4B772CB778400 libjhead.so
W/google-breakpad( 4462): M AB00F000 00000000 0002C000 6CAAD8BCF7E07793A73B8EA9B43AED5A0 libexif.so
W/google-breakpad( 4462): M AB03B000 00000000 00014000 E9EE77C3D7D433365516A96B8AE34C790 libbrunch.so
W/google-breakpad( 4462): M B00DE000 00000000 00003000 9A115484806571313C641963FDAA69670 memtrack.msm8226.so
W/google-breakpad( 4462): M B0808000 00000000 0000C000 FE1E23D2159CFD295F34996A111FBB9C0 eglsubAndroid.so
W/google-breakpad( 4462): M B0882000 00000000 00004000 F786FA54B1844430370450775E3839AD0 libwebviewchromium_plat_support.so
W/google-breakpad( 4462): M B1BF1000 00000000 00037000 EC4386CA92978B743AE8C0612A7128C50 libjavacore.so
W/google-breakpad( 4462): M B44F7000 00000000 00305000 3865F1A96E2B21A6EF7A30BC26CCB5FB0 libart.so
W/google-breakpad( 4462): M B5070000 00000000 0001B000 195B37B83D4254C8B330DB89973D654E0 libdrmframework.so
W/google-breakpad( 4462): M B508C000 00000000 00008000 FE09F5ADF996273125BF471219C782630 libdrmframework_jni.so
,W/google-breakpad( 4462): M B51E4000 00000000 00015000 4BA2AE649C0515F58E3A4F2EB156187B0 liblgalmond.so
W/google-breakpad( 4462): M B51F9000 00000000 00008000 DAEE33DE0444DFA19A5E9977EBC34B020 libbacktrace_libc++.so
W/google-breakpad( 4462): M B5201000 00000000 00003000 6B5B53D0A10F826CC9EA2F6B88D39AF70 libcnefeatureconfig.so
W/google-breakpad( 4462): M B5205000 00000000 00006000 5E93EF95A5A6222B4237CBEE5C5B19E20 libvendorconn.so
W/google-breakpad( 4462): M B522B000 00000000 00004000 C88FD942703CD0910236DC719AB36EF90 libusbhost.so
W/google-breakpad( 4462): M B522F000 00000000 0003F000 1790A63C93B25AD9646160FED94627920 libssl.so
W/google-breakpad( 4462): M B526E000 00000000 000A5000 69EC663D7D4956711E46CB4333B4108F0 libsqlite.so
W/google-breakpad( 4462): M B5314000 00000000 0000E000 FEEFBB918616C9664F948E273A3A03EF0 libsoundtrigger.so
W/google-breakpad( 4462): M B5322000 00000000 00012000 1ED726B29E92DEC8EA3197FAED4636470 libpcre.so
W/google-breakpad( 4462): M B5334000 00000000 0000E000 13E86CFFF130F842512F9D3ABB556C130 libselinux.so
W/google-breakpad( 4462): M B5342000 00000000 00004000 4E6C8C876BA563C3C4B0B3BA562093920 libprocessgroup.so
W/google-breakpad( 4462): M B5346000 00000000 00446000 83C530EBE395DB5C15F9E1A6BAF1B5740 libpdfium.so
W/google-breakpad( 4462): M B5791000 00000000 00004000 85B80322D25FA10BD1709D3D8388041B0 libnetd_client.so
W/google-breakpad( 4462): M B5795000 00000000 00007000 35A908439919BC6B6EC3A246DB0E113B0 libnativehelper.so
W/google-breakpad( 4462): M B579C000 00000000 00004000 A1943995D03FC1F74711D0AD5F15EE960 libnativebridge.so
W/google-breakpad( 4462): M B57A0000 00000000 0000C000 34DA5C5BEFD3D3F076439D28B2EAF3600 libminikin.so
,W/google-breakpad( 4462): M B57AC000 00000000 00003000 CCA8BE0D07D24523C8D02FEE5F724EA70 libmemtrack.so
W/google-breakpad( 4462): M B57AF000 00000000 00005000 EA3D9827398AB1CB4C13D1DAC7AFBF1C0 libpowermanager.so
W/google-breakpad( 4462): M B57B4000 00000000 00015000 71C5EA36B4CE20563A0F4197D42051670 libstagefright_foundation.so
W/google-breakpad( 4462): M B57C9000 00000000 0001C000 8E02720480177F53B812AD30BF3B72FE0 liblgdrm_client.so
W/google-breakpad( 4462): M B57E5000 00000000 00051000 6EBD71CB63633C219CC3F7A97D7B4D4C0 libsonivox.so
W/google-breakpad( 4462): M B583B000 00000000 0000F000 E2DD6FCC6A85AF2204C3DD01BB5505510 libcommon_time_client.so
W/google-breakpad( 4462): M B584A000 00000000 00009000 424F91688903AE89C61A0EB2A38B884D0 libnbaio.so
W/google-breakpad( 4462): M B5853000 00000000 0000A000 E6B9F397F004151EE0822D0D830AED170 libmedia_ex.so
W/google-breakpad( 4462): M B585D000 00000000 00005000 8D1366FBF8CAA032568C227712A97EBD0 libaudioparameter.so
,W/google-breakpad( 4462): M B5862000 00000000 000A9000 DF1D7256F5401E97FE39C599F9715B640 libmedia.so
W/google-breakpad( 4462): M B590B000 00000000 00038000 197D8529D4736FFC8810A5DDA9D7156D0 libinputflinger.so
W/google-breakpad( 4462): M B5943000 00000000 0001A000 735B646A98ED5D627CC62B715BD4B1620 libinput.so
W/google-breakpad( 4462): M B595D000 00000000 0000D000 3B926F72AB1625BE0AA7CC84C738C6300 libimg_utils.so
W/google-breakpad( 4462): M B596A000 00000000 00032000 D435EDF7E2D4110BD215491B6CA7DE530 libjpeg.so
W/google-breakpad( 4462): M B599C000 00000000 00217000 374493F0DB82EA4D2AB745426F743D7A0 libskia.so
W/google-breakpad( 4462): M B5BB8000 00000000 0001D000 F3531430C4158F283074D67E96C8BF8A0 libRScpp.so
W/google-breakpad( 4462): M B5BD5000 00000000 00027000 C5EBDF6A74A96860BB6F19C1F1ED08630 libpng.so
W/google-breakpad( 4462): M B5BFD000 00000000 00059000 6560F3B8013A04F7702E4BAB5517CBE70 libft2.so
W/google-breakpad( 4462): M B5C57000 00000000 0003C000 D8C3B36FFB6405BD96DF26E4A38E9D650 libbcinfo.so
W/google-breakpad( 4462): M B5C93000 00000000 00022000 3643CDB5E2CDDEB334E22440918105D90 libbcc.so
W/google-breakpad( 4462): M B5CD5000 00000000 0008C000 D6B6ED19D5C038412B6368CDFE93E9BC0 libc++.so
W/google-breakpad( 4462): M B5D63000 00000000 008FE000 9D223F97F870A7BB5C0C7F343FC560520 libLLVM.so
W/google-breakpad( 4462): M B6668000 00000000 00036000 8D00E81452132FAD38D6349483E6CC280 libRS.so
D/libc-netbsd( 4292): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
W/google-breakpad( 4462): M B669E000 00000000 0004B000 3C83FBB58F791A75238BD95B8B13E5DD0 libhwui.so
D/libc-netbsd( 4292): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/google-breakpad( 4462): M B66E9000 00000000 00107000 1944C4996C0BFD0F27EA043677EA49130 libicuuc.so
W/google-breakpad( 4462): M B67F4000 00000000 00006000 E3AE8BE37EE0B813F539936AB3929DEB0 libgabi++.so
W/google-breakpad( 4462): M B67FA000 00000000 00158000 23F1A0622B97B553871971130E2981050 libicui18n.so
,W/google-breakpad( 4462): M B6952000 00000000 00048000 CA4E26A13A874289F1CB754FE9FB7A460 libharfbuzz_ng.so
W/google-breakpad( 4462): M B699A000 00000000 00004000 B651006496AD564110C796F66C5EC9ED0 libwpa_client.so
W/google-breakpad( 4462): M B699E000 00000000 00006000 556B05513729F48DF69FD5DB6DD5CB9D0 libvolumevibratorcallback.so
W/google-breakpad( 4462): M B69A4000 00000000 00008000 9FFBEDF3FF9D0412BDBF868A026D91830 libnetutils.so
W/google-breakpad( 4462): M B69AC000 00000000 00004000 5E6F8FB1ABE22FE37DC1C9388C0D5E900 libatd_corelib.so
W/google-breakpad( 4462): M B69B1000 00000000 00004000 9418454BA0CA62D7606521089D87E7390 liblgftmitem.so
W/google-breakpad( 4462): M B69B5000 00000000 0000D000 7B8A520D37C56AF1CC8A5DFA92D2167D0 libhardware_legacy.so
W/google-breakpad( 4462): M B69C4000 00000000 00017000 BE487D5116BB4AF53060EBDC4CBCBED50 libexpat.so
W/google-breakpad( 4462): M B69DB000 00000000 000F6000 D1DA18C438A3963600072992BE32C7860 libcrypto.so
W/google-breakpad( 4462): M B6AD3000 00000000 00003000 74BDE58D9533C5E7870D0EAFB9264B590 libhardware.so
W/google-breakpad( 4462): M B6AD6000 00000000 0000C000 5AD01CC08B692452BC590DF63D5B4E600 libui.so
W/google-breakpad( 4462): M B6AE2000 00000000 00003000 2D9083CB8C22C02E1412DA13B1CA43AE0 libsync.so
W/google-breakpad( 4462): M B6AE5000 00000000 0004C000 40C0951EA1AF4EC38ECC93FCCD42FEEB0 libgui.so
W/google-breakpad( 4462): M B6B31000 00000000 00008000 D8696C0232AD725A04A607DFFA2662E60 libcamera_metadata.so
W/google-breakpad( 4462): M B6B39000 00000000 00038000 CA16E558D8AD694A3AEFE3B867BE72A70 libcamera_client.so
,W/google-breakpad( 4462): M B6B71000 00000000 00006000 AC1D7BAE26791BE91E8BCCB199F3926F0 libspeexresampler.so
W/google-breakpad( 4462): M B6B77000 00000000 00006000 C51E7E210A0C2DA7F15A919C8BBA52D80 libaudioutils.so
W/google-breakpad( 4462): M B6B7D000 00000000 0001A000 03AD8D1D4E22A7AE9B066E9786DBB3AE0 libz.so
W/google-breakpad( 4462): M B6B97000 00000000 0002D000 AF8C341C5F1A54BA6A750748ED080D760 libbinder.so
W/google-breakpad( 4462): M B6BC4000 00000000 00026000 0C7AD2A1D846111DE3F1A3B54696FE350 libandroidfw.so
W/google-breakpad( 4462): M B6BEA000 00000000 0000B000 E2F67EE50006FD0ED1482E1463C5CCFF0 libGLESv2.so
W/google-breakpad( 4462): M B6BF5000 00000000 00007000 EFE6ADDAF48E0BCED48FF0E60558C2F60 libGLESv1_CM.so
W/google-breakpad( 4462): M B6BFC000 00000000 00004000 DE56AF21D1810CB9F5D59132F2B573690 libETC1.so
W/google-breakpad( 4462): M B6C00000 00000000 00004000 7A80CF6FADF6A3E8B908CC78ED49A6960 libunwind-ptrace.so
W/google-breakpad( 4462): M B6C04000 00000000 0000E000 EF89B10946BDF6079AAF789F56192FDA0 libunwind.so
W/google-breakpad( 4462): M B6C58000 00000000 00007000 3874D35A672DF926049632908E3F44990 libgccdemangle.so
W/google-breakpad( 4462): M B6C60000 00000000 00008000 565879110C8919C1B793CFC4047A2B9B0 libbacktrace.so
W/google-breakpad( 4462): M B6C6A000 00000000 00016000 4999DE1B8A8F74002F98E921D65D73630 libutils.so
W/google-breakpad( 4462): M B6C80000 00000000 00036000 2F64392B3DB465278C2FAAA9AB95765E0 libstlport.so
W/google-breakpad( 4462): M B6CB7000 00000000 0006C000 B2EFA1538A963AE403143D427627808B0 libGLES_trace.so
W/google-breakpad( 4462): M B6D23000 00000000 00068000 93C54B2B4728113204066F4718CD48FE0 libEGL.so
,W/google-breakpad( 4462): M B6D8E000 00000000 000DE000 ED75B1C7941402A7B8C23AD0A51F1ECD0 libandroid_runtime.so
W/google-breakpad( 4462): M B6E6D000 00000000 0000D000 9CE14A143CF7D3AB3E49F82BB9BA4BAC0 libcutils.so
W/google-breakpad( 4462): M B6E7A000 00000000 00004000 D1AC53E65CCF0819F62D0CBCB34992B60 libNimsWrap.so
W/google-breakpad( 4462): M B6E7E000 00000000 00004000 DFD777ACF34CBD2037A5FC4C5DDFC1430 libstdc++.so
W/google-breakpad( 4462): M B6E82000 00000000 00018000 112087314C147BE2E520A4B6ABA86D970 libm.so
W/google-breakpad( 4462): M B6E9B000 00000000 00007000 58CFB8EDDD133B5B179573415F8D2C080 liblog.so
,W/google-breakpad( 4462): M B6EA3000 00000000 0006A000 C67B6C03267EEB81C242CEB6FC0613BA0 libc.so
,W/google-breakpad( 4462): M B6F17000 00000000 00003000 D773C773634B82249E887ECBC5D28C900 libsigchain.so
W/google-breakpad( 4462): M B6F1F000 00000000 0000F000 F2B363F00698D9E565DA027016EC453C0 linker
W/google-breakpad( 4462): -----END BREAKPAD MICRODUMP-----
W/google-breakpad( 4265): ### ### ### ### ### ### ### ### ### ### ### ### ###
W/google-breakpad( 4265): Chrome build fingerprint:
W/google-breakpad( 4265): 0.0.1
W/google-breakpad( 4265): 18
W/google-breakpad( 4265): 873fd9bc-5759-4679-9dc5-2d671bd0c1b7
W/google-breakpad( 4265): ### ### ### ### ### ### ### ### ### ### ### ### ###
E/chromium( 4265): ### WebView Version 44.0.2403.90 (code 240309000)
--------- beginning of crash
F/libc    ( 4265): Fatal signal 11 (SIGSEGV), code 1, fault addr 0x0 in tid 4427 (Thread-466)
,I/ActivityManager(  951): Killing 3985:com.lge.gnss.airtest/u0a54 (adj 15): empty #12
I/DEBUG   (  278): [2016-01-08 14:50:41.247]
,W/NativeCrashListener(  951): Couldn't find ProcessRecord for pid 1530015793
I/DEBUG   (  278): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
E/DEBUG   (  278): AM write failure (32 / Broken pipe)
I/DEBUG   (  278): Build fingerprint: 'lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys'
I/DEBUG   (  278): Revision: '6'
I/DEBUG   (  278): ABI: 'arm'
I/DEBUG   (  278): pid: 4265, tid: 4427, name: Thread-466  >>> com.example.hello <<<
I/DEBUG   (  278): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
W/libprocessgroup(  951): failed to open /acct/uid_1000/pid_4003/cgroup.procs: No such file or directory
W/libprocessgroup(  951): failed to open /acct/uid_10054/pid_3985/cgroup.procs: No such file or directory
,I/DEBUG   (  278):     r0 00000000  r1 00000000  r2 00000000  r3 00000000
I/DEBUG   (  278):     r4 98c87e68  r5 98c87e28  r6 9fa47700  r7 98c87e28
I/DEBUG   (  278):     r8 00000000  r9 98c87e64  sl 98c893c0  fp 98c87e0c
I/DEBUG   (  278):     ip 9975dba0  sp 98c87df0  lr 99464308  pc b6eb45f8  cpsr 600d0030
I/DEBUG   (  278): 
I/DEBUG   (  278): backtrace:
I/DEBUG   (  278):     #00 pc 000115f8  /system/lib/libc.so (strlen+83)
,I/DEBUG   (  278):     #01 pc 007da304  /data/app/com.example.hello-1/lib/arm/libjxcore.so (MozJS::String::FromUTF8(JSContext*, char const*, int)+40)
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/art     (  951): Explicit concurrent mark sweep GC freed 24326(1216KB) AllocSpace objects, 3(237KB) LOS objects, 33% free, 23MB/34MB, paused 3.447ms total 175.165ms
,W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 4463): getAccountsCursor
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 4463): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  951): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,E/Gmail   ( 4463): Error finding the version of the Email provider.....
E/Gmail   ( 4463): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4463): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4463): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4463): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4463): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4463): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4463): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4463): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4463): We do not support migrating this version of the Email provider.
I/Gmail   ( 4463): Observing account changes for notifications
W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4463): getAccountsCursor
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  951): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4511 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 4463): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@24d11d14 that was originally bound here
E/ActivityThread( 4463): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@24d11d14 that was originally bound here
E/ActivityThread( 4463): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4463): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4463): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4463): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4463): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4463): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4463): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4463): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4463): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4463): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4463): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4463): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4463): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4463): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4463): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4463): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  951): Unbind failed: could not find connection for android.os.BinderProxy@385d3e9a
,V/[BNRBootReceiver]( 4511): boot receiver action = android.intent.action.BOOT_COMPLETED
,V/[BNRBootReceiver]( 4511): set property sys.lge.bnrd = 1
V/[BNRBootReceiver]( 4511): End of BootComplted IF
V/[BNRBootReceiver]( 4511): Boot Receiver Return
V/[BNRBootCompletedThread]( 4511): run
W/linker  ( 4530): /system/bin/bnrd has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/bnrd    ( 4530): BNRD > wait starting [4530-3058102400] <
E/bnrd    ( 4530): /data/data/.bnr_fifo_req
I/Gmail   ( 4463): notifyAccountChanged
,V/[BNRBootCompletedThread]( 4511): End of BNRProcess
I/Gmail   ( 4463): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/[BNRBootCompletedThread]( 4511): End of BNRViaWifiProcess
I/ActivityManager(  951): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4536 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  951): Killing 4091:com.android.providers.calendar/u0a14 (adj 15): empty #11
V/[BNRBootCompletedThread]( 4511): End of SpriteProcess
V/[BNRBootCompletedThread]( 4511): exit
I/Gmail   ( 4463): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4463): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4463): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/libprocessgroup(  951): failed to open /acct/uid_10014/pid_4091/cgroup.procs: No such file or directory
,I/ActivityManager(  951): Killing 4073:com.lge.hiddenmenu/1000 (adj 15): empty #11
,I/DEBUG   (  278): 
I/DEBUG   (  278): Tombstone written to: /data/tombstones/tombstone_04
I/BootReceiver(  951): Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
,I/WindowState(  951): WIN DEATH: Window{1c26cbb8 u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  951): Focus left window: Window{1c26cbb8 u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  951): Window went away: Window{1c26cbb8 u0 com.example.hello/com.example.hello.MainActivity}
W/libprocessgroup(  951): failed to open /acct/uid_1000/pid_4073/cgroup.procs: No such file or directory
,D/PowerService( 1817): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1385): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1385): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1385): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1385): On Skip Timer : true
I/Zygote  (  310): Process 4265 exited due to signal (11)
,I/ActivityManager(  951): Process com.example.hello (pid 4265) has died
,W/ActivityManager(  951): Force removing ActivityRecord{4a1d10 u0 com.example.hello/.MainActivity t220}: app died, no saved state
I/[LGHome]EVENT( 1891): [Launcher.java:5203:onStart()]onStart
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4463): getAccountsCursor
I/[LGHome]EVENT( 1891): [Launcher.java:776:onResume()]onResume
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4463): getAccountsCursor
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[LGHome]LGActivityUtil( 1891): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1891): [Launcher.java:929:onResume()]onResume end
I/Activity( 1891): Activity.onPostResume() called 
I/SystemUI[Framework](  951): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,D/PhoneStatusBar( 1385): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
W/PhoneWindowManagerEx(  951): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  951): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  951): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  951): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@354121b7,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  951): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/[LGHome]LGWallpaperInfo( 1891): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1891): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/InputDispatcher(  951): Focus entered window: Window{200e78c7 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 1891): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1891): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  951): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  951): Got RemoteException sending setActive(false) notification to pid 4265 uid 10317
,I/HotwordRecognitionRnr( 1978): Starting hotword detection.
,I/MicrophoneInputStream( 1978): mic_starting com.google.android.apps.gsa.speech.audio.u@307eae1d
V/AudioRecord( 1978): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 1978): set(): mSessionId 23
V/AudioPolicyManager(  282): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 23, flags 0
V/AudioPolicyManager(  282): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  282): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  282): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb4036520)
V/audio_hw_primary(  282): adev_open_input_stream: exit
V/AudioFlinger(  282): openInput_l() openInputStream returned input 0xb4036520, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  282): openInput_l() created record thread: ID 24 thread 0xb42a4000
V/AudioSystem(  282): ioConfigChanged() event 3, ioHandle 24
I/AudioFlinger(  282): AudioFlinger's thread 0xb42a4000 ready to run
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioSystem( 1765): ioConfigChanged() event 3, ioHandle 24
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioSystem(  951): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 1385): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 2063): ioConfigChanged() event 3, ioHandle 24
,V/AudioSystem( 1978): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 2679): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 3160): ioConfigChanged() event 3, ioHandle 24
V/AudioFlinger(  282): openRecord() lSessionId: 23 input 24
V/AudioFlinger(  282): getOrphanEffectChain_l session 23 index -2
V/AudioFlinger(  282): acquiring 23 from 1978, for -1
V/AudioFlinger(  282):  added new entry for 23
V/AudioRecord( 1978): start, sync event 0 trigger session 0
V/AudioRecord( 1978): mAudioRecord->start()
V/AudioFlinger(  282): RecordHandle::start()
V/AudioFlinger(  282): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  282): startInput() module primary->input primary(24)
V/AudioPolicyManager(  282): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  282): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  282): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  282): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  282): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  282): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing create audio patch
,V/AudioFlinger::PatchPanel(  282): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  282): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  282): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb42a4000
V/AudioFlinger::PatchPanel(  282): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  282): createAudioPatch() added new patch handle 25 halHandle 0
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): setInputDevice() createAudioPatch returned 0 patchHandle 25
V/AudioPolicyManager(  282): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  282): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  282): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  282): AudioCommandThread() adding set parameter string hotword_active=1, io 24 ,delay 0
V/AudioPolicyService(  282): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing set parameters string hotword_active=1, io 24
V/AudioFlinger(  282): setParameters(): io 24, keyvalue hotword_active=1, calling pid 282
V/AudioFlinger(  282): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
I/Timeline( 1891): Timeline: Activity_idle id: android.os.BinderProxy@32d93ff8 time:59298
I/SystemUI[Framework](  951): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  951): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  951): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  951): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PhoneStatusBar( 1385): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/SystemUI[Framework](  951): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@354121b7,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  951): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1385): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1385):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1385): , Keyguard show=false, IME shown=false, Panel expanded=false
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb42a4000
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): AudioPolicyManager::startInput() input source = 1999
D/BarTransitions( 1385): draw background and invalidate : color = ed000000
I/MicrophoneInputStream( 1978): mic_started com.google.android.apps.gsa.speech.audio.u@307eae1d
V/msm8974_platform(  282): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  282): start_input_stream: enter: stream(0xb4036520)usecase(7: audio-record)
V/voice   (  282): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(,  282): start_input_stream: usecase(7)
D/BarTransitions( 1385): draw background and invalidate : color = eae1e1e1
,E/audio_hw_primary(  282): select_devices: enter and usecase(7)
V/msm8974_platform(  282): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  282): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  282): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  282): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  282): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  282): enable_snd_device: enter  144
D/hardware_info(  282): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  282): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  282): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  282): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  282): ACDB -> send_adm_topology
D/ACDB-LOADER(  282): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  282): ACDB -> send_asm_topology
D/ACDB-LOADER(  282): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  282): ACDB -> send_audtable
D/ACDB-LOADER(  282): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  282): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  282): ACDB -> send_audvoltable
D/ACDB-LOADER(  282): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  282): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  282): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  282): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  282): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  282): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  282): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  282): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  282): enable_audio_route: exit
D/audio_hw_primary(  282): select_devices: done
V/audio_hw_primary(  282): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
V/audio_hw_primary(  282): start_input_stream: exit
,D/Finsky  ( 4536): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/HotwordWorker( 1978): onReady
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  951): Waited long enough for: ServiceRecord{2cd376f0 u0 com.android.mms/.service.SwitchedService}
,I/Timeline(  951): Timeline: Activity_windows_visible id: ActivityRecord{26649b59 u0 com.lge.launcher2/.Launcher t219} time:59548
D/Finsky  ( 4536): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 4536): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4536): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 4536): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Volley  ( 4536): [483] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 4536): [476] DiskBasedCache.clear: Cache cleared.
D/Ads     ( 4536): Skipping gmscore version check
V/DownloadManager( 3188): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,D/Finsky  ( 4536): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4536): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3188): created cursor android.database.sqlite.SQLiteCursor@1ba66b5a on behalf of 4536
D/Finsky  ( 4536): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4536): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/FileApkUtils( 4375): Spent 83ms computing apk sha1.
,D/FileApkUtils( 4375): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 4375): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-ca8b2a9144773fc3650c54ed299f2d4558171b12@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
D/DexOptUtils( 4375): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 4375): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
D/ChimeraCfgMgr( 4375): Reading stored module config
,W/InstanceID/Rpc( 4375): Found 10006
,D/GmsModuleFndr( 4375): Beginning GMS chimera module scan
D/ChimeraCfgMgr( 4375): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/BootCompletedReceiver( 4375): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 4375): Got an BootCompleted event.
D/BootCompletedReceiver( 4375): Will NOT schedule AdAttestation signal task because it's disabled.
,D/GmsModuleFndr( 4375): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 4375): Beginning module configuration check
,D/ChimeraCfgMgr( 4375): Module APKs unchanged, check complete
D/GCM     ( 4375): COMPAT: Multi user not supported
I/art     ( 4375): CheckpointMarkThreadRoots callback created = 0xb042d260
,I/GCoreUlr( 4375): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/art     ( 4375): CheckpointMarkThreadRoots callback created = 0xaaeea350
,I/CheckinService( 4375): Checkin interval check for package: unspecified last checkin: 1452248357147 min interval config: 0 actual interval: 12686391
I/art     ( 4023): Explicit concurrent mark sweep GC freed 8707(442KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.188ms total 54.893ms
,W/art     ( 4375): Suspending all threads took: 65.852ms
,I/CheckinService( 4375): Disabling old GoogleServicesFramework version
,D/SystemUpdateService( 4375): onCreate
,D/SystemUpdateService( 4375): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/AuthZen ( 4375): Handling intent: android.intent.action.BOOT_COMPLETED
I/SystemUpdateService( 4375): cancelUpdate (empty URL)
I/SystemUpdateService( 4375): active receiver: disabled
,I/NotificationManager( 4375): com.google.android.gms: cancel(2130838165) by com.google.android.gms
,I/NotificationManager( 4375): com.google.android.gms: cancel(2130838166) by com.google.android.gms
D/AuthZenEventHandler( 4375): Handling event: android.intent.action.BOOT_COMPLETED
W/BaseAppContext( 4375): Using Auth Proxy for data requests.
,I/CheckinService( 4375): Checking schedule, now: 1452261043847 next: 1452775606064
I/CheckinService( 4375): active receiver: disabled
E/BaseAppContext( 4375): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/art     ( 1747): Explicit concurrent mark sweep GC freed 15288(896KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 13MB/22MB, paused 1.818ms total 83.433ms
I/art     ( 4023): Explicit concurrent mark sweep GC freed 2799(112KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.864ms total 37.075ms
,D/GCM     ( 1747): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/GCoreUlr( 1747): DispatchingService.onCreate()
D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
I/AuthZen ( 4375): Fetching signing key...
,D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out( 1747): propertyValue:false
I/AuthZen ( 4375): Signing key fetched successfully!
I/art     ( 4375): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 4375): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/BaseAppContext( 4375): Using Auth Proxy for data requests.
D/SystemUpdateService( 4375): onDestroy
D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/a       ( 4375): Opening database auth.proximity.permit_store...
I/GCoreUlr( 1747): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/AuthZenTransactionCache( 4375): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 4375): Clearing transaction cache
W/Auth    ( 1747): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/NotificationManager( 4375): com.google.android.gms: cancel(10436) by com.google.android.gms
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1747): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/GCM     ( 1747): GCM config loaded
,I/art     (  951): Explicit concurrent mark sweep GC freed 26536(1335KB) AllocSpace objects, 14(945KB) LOS objects, 33% free, 23MB/34MB, paused 2.504ms total 165.345ms
,W/GCoreFlp( 1747): No location to return for getLastLocation()
W/FusedLocationProvider( 1747): location=null
I/GCoreUlr( 1747): Unbound from all location providers
,I/GCoreUlr( 1747): Place inference reporting - stopped
W/GCoreFlp( 1747): No location to return for getLastLocation()
W/FusedLocationProvider( 1747): location=null
I/GCoreUlr( 1747): DispatchingService.onDestroy()
,I/GCoreUlr( 1747): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1747): Unbound from all location providers
I/GCoreUlr( 1747): Place inference reporting - stopped
D/PersistentNotificationBroadcastReceiver( 1747): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  951): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=4654 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/NotificationManager(  951): android: cancelAsUser(-591465577) by android
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1891): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1891): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]NumberBadge.LGBroadCastBadge( 1891): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
W/ResourcesManager( 4654): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[LGHome]NumberBadge.LGBroadCastBadge( 1891): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
I/NotificationManager(  951): android: cancelAsUser(-1816247584) by android
W/OpenGLRenderer( 1891): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
W/OpenGLRenderer( 1891): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/ActivityManager(  951): Killing 4110:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  951): failed to open /acct/uid_10069/pid_4110/cgroup.procs: No such file or directory
,E/App     ( 4654): [App][onCreate()] 4.40.23
,W/ActivityManager(  951): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
,V/AlarmManager(  951): RTC_WAKEUP set : Alarm{3b4263f1 type 0 when 1451915418757 com.android.providers.contacts} when 1451915418757
V/AlarmManager(  951): ELAPSED_WAKEUP set : Alarm{331e2bd6 type 2 when 55045 com.google.android.talk} when 55045
V/AlarmManager(  951): RTC_WAKEUP set : Alarm{1b06cd44 type 0 when 1452261044704 com.google.android.gms} when 1452261044704
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/iu.UploadsManager( 4375): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,D/AccountManager( 4654): setSyncFrequency
,I/iu.UploadsManager( 4375): End new media; added: 0, uploading: 0, time: 44 ms
W/ContextImpl( 4654): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.qmemoplus.ui.editor.reminder.ReminderMaker.onReceive:14 android.app.ActivityThread.handleReceiver:2663 
,D/ReminderService( 4654): [onHandleIntent] action : com.lge.qmemoplus.action.SET_REMINDERS
D/LocationReminderManager( 4654): [connect] Request location client connection.
W/ContextImpl( 4654): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.google.android.gms.internal.he.a:-1 com.google.android.gms.internal.hc.connect:-1 com.google.android.gms.location.LocationClient.connect:-1 
,I/ActivityManager(  951): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=4687 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  951): Killing 4129:com.lge.springcleaning/1000 (adj 15): empty #11
,D/LocationReminderManager( 4654): location cilent is connected.
,D/LocationReminderManager( 4654): [removeAllReminders]
,W/libprocessgroup(  951): failed to open /acct/uid_1000/pid_4129/cgroup.procs: No such file or directory
,W/GeofencerStateMachine( 1747): Ignoring removeGeofence because network location is disabled.
D/LocationReminderManager( 4654): [removeAllReminders] statusCode : 1000
D/LocationReminderManager( 4654): [removeAllReminders] Failed to remove reminder
,W/GCoreFlp( 1747): No location to return for getLastLocation()
W/GCoreFlp( 1747): No location to return for getLastLocation()
,D/LGDMClient( 4687): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
D/LGDMClient( 4687): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4687): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4687): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
D/LGDMClient( 4687): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
,D/LGDMClient( 4687): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 4687): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  951): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4715 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
W/ContextImpl( 4687): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4687): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 4687): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4687): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 4687): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 4687): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  951): Killing 4163:com.google.android.configupdater/u0a3 (adj 15): empty #11
W/libprocessgroup(  951): failed to open /acct/uid_10003/pid_4163/cgroup.procs: No such file or directory
,W/ResourcesManager( 4715): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  951): Message: 20
D/BluetoothManagerService(  951): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2dece599:true
,D/BluetoothAdapterService(1061685702)( 2063): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1da6664c
D/BluetoothAdapterService(1061685702)( 2063): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1da6664c
I/ActivityManager(  951): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4737 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 4715): Create singleton instance
,D/UEI.SmartControl( 4737): Quickset Services start...
,I/UEI.SmartControl( 4737): Manufacture = LGE
D/UEI.SmartControl( 4737): File observer start...
,E/UEI.SmartControl( 4737): IR Port is disabled: false
D/UEI.SmartControl( 4737): Starting file observer...
D/UEI.SmartControl( 4737): Extracting JNI libs...
D/UEI.SmartControl( 4737): --- this system supports 32-bit or 64-bit only
I/AudioManager( 4715): getMode name:com.lge.qremote
,V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
I/AudioManager( 4715): getMode name:com.lge.qremote
,V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) },
,V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
D/UEI.SmartControl( 4737): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 4737): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4737): --- Extracting JNI libs: libqs_armeabi-v7a.zip
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
I/UEI.SmartControl( 4737): --- Selecting new region: 2
I/UEI.SmartControl( 4737): -- Running on KitKat(19) and above! JNI will be used.
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/UEI.SmartControl( 4737): Platform has CIR...
D/UEI.SmartControl( 4737): NO CIR support, need to check package...
,V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
I/UEI.SmartControl( 4737): Model: LG-D722 uses JNI
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
D/UEI.SmartControl( 4737): QS Service created
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3160): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3160): ANY_DATA_STATE event received: DISCONNECTED
,D/LGDMClient( 4687): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
D/LGDMClient( 4687): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4687): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4687): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 4687): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 4687): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4687): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
E/UEI.SmartControl( 4737): QS start get config
D/UEI.SmartControl( 4737): Loading JNI Libs...
,I/ActivityManager(  951): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=4772 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
D/UEI.SmartControl( 4737):  configuring local db...
W/ContextImpl( 4687): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.305ms
,E/LGDMClient( 4687): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 4687): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4687): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 4687): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 4687): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 24.031ms
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.220ms
,W/ResourcesManager( 4772): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4772): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 4772): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4772): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 4772): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 4772): Using schema version: 115
,I/IndexDatabaseHelper( 4772): Index is fine
,D/UEI.SmartControl( 4737):  ---- Has DB8: true
,D/UEI.SmartControl( 4737): QS start statue = true Error code = 0
D/UEI.SmartControl( 4737): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4737): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
V/WiFiOffLoadBroadcast( 4772): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/UEI.SmartControl( 4737): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 4737): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 4737): IrrcClient ++ 
D/irrcClient( 4737): getIrrcService ++ 
D/irrcClient( 4737): getIrrcService -- 
D/irrcClient( 4737): IrrcClient -- 
W/irrc_jni( 4737): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 4737): Services init done
I/UEI.SmartControl( 4737): Device manager: loading config....
D/UEI.SmartControl( 4737): QS Service init finished
D/UEI.SmartControl( 4737): QS Service version name: 0.1.73
D/UEI.SmartControl( 4737): QS Service version code: 1073
D/UEI.SmartControl( 4737): Config is loaded...
,D/UEI.SmartControl( 4737): Service requested: Control
D/UEI.SmartControl( 4737): Internal service binding...
D/UEI.SmartControl( 4737): -----IControl: 11
D/UEI.SmartControl( 4737): Caller: com.lge.qremote
D/UEI.SmartControl( 4737): ------------ IControl registerCallback...
I/UEI.SmartControl( 4737): Registering callback...
D/UEI.SmartControl( 4737): -----IControl: 19
D/UEI.SmartControl( 4737): Caller: com.lge.qremote
I/UEI.SmartControl( 4737): Registering Services Ready callback...
I/UEI.SmartControl( 4737): Notify client services are ready...
,D/UEI.SmartControl( 4737): -----IControl: 8
D/UEI.SmartControl( 4737): Caller: com.lge.qremote
D/WiFiOffLoadBroadcast( 4772): MCCMNC not supported: null
D/UEI.SmartControl( 4737):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 4737): Notify AllClients services are ready: 0
,I/ActivityManager(  951): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4794 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  951): Killing 4193:com.lge.eula/1000 (adj 15): empty #11
W/libprocessgroup(  951): failed to open /acct/uid_1000/pid_4193/cgroup.procs: No such file or directory
,I/ActivityManager(  951): Killing 4292:com.google.android.youtube/u0a100 (adj 15): empty #11
I/ActivityManager(  951): Killing 4211:com.google.android.talk/u0a61 (adj 15): empty #12
,D/PCSuite ( 4794): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/libprocessgroup(  951): failed to open /acct/uid_10100/pid_4292/cgroup.procs: No such file or directory
,W/libprocessgroup(  951): failed to open /acct/uid_10061/pid_4211/cgroup.procs: No such file or directory
D/UsbSettingsReceiver( 4772): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 4772): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 4772): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 4772): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 4772): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 4772): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 4772): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 4772): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 4772): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 4772): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 4772): [AUTORUN] onReceive() : TetherState Changed=wlan0
,D/UsbSettingsControl( 4772): [AUTORUN] setTetherStatus() : status=false
V/WiFiOffLoadBroadcast( 4772): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WiFiOffLoadBroadcast( 4772): MCCMNC not supported: null
D/PCSuite ( 4794): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDMClient( 4687): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,D/LGDMClient( 4687): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4687): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4687): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/WiFiOffLoadBroadcast( 4772): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 4772): MCCMNC not supported: null
D/LGDMClient( 4687): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 4687): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4687): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4687): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/ContextImpl( 4687): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4687): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 4687): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4687): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 4687): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
I/PCSuite ( 4794): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/LGDMClient( 4687): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
D/PCSuite ( 4794): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4794): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/[BNRBootReceiver]( 4511): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 4511): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,V/[BNRBootReceiver]( 4511): Boot Receiver Return
I/AudioManager( 4715): getMode name:com.lge.qremote
V/WiFiOffLoadBroadcast( 4772): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4772): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4772): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 4772): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 4772): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 4772): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4772): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4772): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4772): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4772): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4772): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4772): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4772): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4772): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4772): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4772): MCCMNC not supported: null
I/AudioManager( 4715): getMode name:com.lge.qremote
,V/WiFiOffLoadBroadcast( 4772): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 4772): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4772): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4772): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4772): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4772): MCCMNC not supported: null
I/PCSuite ( 4794): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/PCSuite ( 4794): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 4772): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4772): MCCMNC not supported: null
I/PCSuite ( 4794): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 4794): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  951): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4829 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  951): Killing 4463:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  951): failed to open /acct/uid_10053/pid_4463/cgroup.procs: No such file or directory
,W/ResourcesManager( 4829): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4829): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4829): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LGEmail ( 4829): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 4829): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ActivityManager(  951): Waited long enough for: ServiceRecord{2b464af4 u0 com.lge.mlt/.MltMonitorService}
,I/PackageChangeReceiver( 4829): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  951): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4853 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  951): Killing 4536:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  951): failed to open /acct/uid_10036/pid_4536/cgroup.procs: No such file or directory
I/ActivityManager(  951): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4873 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  951): Killing 4375:com.google.android.gms/u0a6 (adj 15): empty #11
,W/libprocessgroup(  951): failed to open /acct/uid_10006/pid_4375/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 4873): onCreate
,W/AppUp4:DB( 4873):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 4873):  setFingerPrint start
I/AppUp4:DB( 4873):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 4873):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4873):  SDK version = 0
I/AppUp4:DB( 4873):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 4873): AppBoxApplication onCreate()
I/ActivityManager(  951): Killing 4654:com.lge.qmemoplus/1000 (adj 15): empty #11
,W/libprocessgroup(  951): failed to open /acct/uid_1000/pid_4654/cgroup.procs: No such file or directory
,I/ActivityManager(  951): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4890 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 4890): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4890): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4890): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/AppConfig( 4890): Total System Memory = 906309632
,I/GalleryUtils( 4890): Application Heap = 96 MB
I/AppConfig( 4890): App Tier : NOT_DEF
D/SystemHelper( 4890): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  951): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=4909 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  951): Killing 4687:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  951): failed to open /acct/uid_1000/pid_4687/cgroup.procs: No such file or directory
,W/ResourcesManager( 4909): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4909): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4909): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 4909): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 4909): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 4909): BUILD Country: EU
I/SystemConfig( 4909): BUILD Operator: OPEN
,I/SystemConfig( 4909): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 4909): existFile = false
,I/SystemConfig( 4909): canReadFile = false
I/SystemConfig( 4909): systemFeature RCS result false
D/SystemConfig( 4909): refreshRcsSupport() :false
I/ActivityManager(  951): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=4928 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  951): Killing 4511:com.lge.bnr/1000 (adj 15): empty #11
W/libprocessgroup(  951): failed to open /acct/uid_1000/pid_4511/cgroup.procs: No such file or directory
,I/LockScreenSettings( 4928): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 4928): New app installed broadcast received ..
,I/LockScreenSettings( 4928): Number of installed packages  1
,I/ActivityManager(  951): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=4945 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  951): Killing 4772:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  951): failed to open /acct/uid_1000/pid_4772/cgroup.procs: No such file or directory
,I/art     (  951): Explicit concurrent mark sweep GC freed 18505(884KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.495ms total 144.215ms
,D/EulaProviderUpdateObserver( 4945): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 4945): uri : package:com.example.hello
,I/ActivityManager(  951): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4962 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  951): Killing 4737:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 4715): android.os.DeadObjectException
,W/System.err( 4715): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4715): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4715): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 4715): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 4715): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4715): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4715): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4715): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4715): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4715): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4715): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4715): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4715): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4715): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4715): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 4715): android.os.DeadObjectException
W/System.err( 4715): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4715): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4715): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 4715): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 4715): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4715): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4715): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4715): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4715): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4715): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4715): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4715): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4715): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4715): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4715): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  951): failed to open /acct/uid_10089/pid_4737/cgroup.procs: No such file or directory
,W/ActivityManager(  951): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  951): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4980 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 4980): Quickset Services start...
,I/UEI.SmartControl( 4980): Manufacture = LGE
D/UEI.SmartControl( 4980): File observer start...
E/UEI.SmartControl( 4980): IR Port is disabled: false
D/UEI.SmartControl( 4980): Starting file observer...
D/UEI.SmartControl( 4980): Extracting JNI libs...
D/UEI.SmartControl( 4980): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 4980): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 4980): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4980): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 4980): --- Selecting new region: 2
,I/UEI.SmartControl( 4980): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 4980): Platform has CIR...
D/UEI.SmartControl( 4980): NO CIR support, need to check package...
I/UEI.SmartControl( 4980): Model: LG-D722 uses JNI
D/UEI.SmartControl( 4980): QS Service created
E/UEI.SmartControl( 4980): QS start get config
,D/UEI.SmartControl( 4980): Loading JNI Libs...
,D/UEI.SmartControl( 4980):  configuring local db...
I/ActivityManager(  951): Waited long enough for: ServiceRecord{1bb0b4bd u0 com.android.calendar/.alerts.InitAlarmsService}
,D/UEI.SmartControl( 4980):  ---- Has DB8: true
,D/UEI.SmartControl( 4980): QS start statue = true Error code = 0
D/UEI.SmartControl( 4980): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4980): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4980): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 4980): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4980): IrrcClient ++ 
D/irrcClient( 4980): getIrrcService ++ 
,D/irrcClient( 4980): getIrrcService -- 
D/irrcClient( 4980): IrrcClient -- 
W/irrc_jni( 4980): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 4980): Services init done
I/UEI.SmartControl( 4980): Device manager: loading config....
,D/UEI.SmartControl( 4980): QS Service init finished
D/UEI.SmartControl( 4980): Config is loaded...
,D/UEI.SmartControl( 4980): QS Service version name: 0.1.73
D/UEI.SmartControl( 4980): QS Service version code: 1073
,D/UEI.SmartControl( 4980): Service requested: Control
D/UEI.SmartControl( 4980):  ----- QS SDK is ready!!!
I/ActivityManager(  951): Killing 4794:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 4980): -----IControl: 11
D/UEI.SmartControl( 4980): Caller: com.lge.qremote
D/UEI.SmartControl( 4980): ------------ IControl registerCallback...
I/UEI.SmartControl( 4980): Registering callback...
I/UEI.SmartControl( 4980): Notify AllClients services are ready: 0
D/UEI.SmartControl( 4980): -----IControl: 19
D/UEI.SmartControl( 4980): Caller: com.lge.qremote
I/UEI.SmartControl( 4980): Registering Services Ready callback...
,I/UEI.SmartControl( 4980): Notify client services are ready...
D/UEI.SmartControl( 4980): -----IControl: 8
D/UEI.SmartControl( 4980): Caller: com.lge.qremote
W/libprocessgroup(  951): failed to open /acct/uid_1000/pid_4794/cgroup.procs: No such file or directory
D/UEI.SmartControl( 4980): Internal service binding...
,I/GAv4    ( 4962): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4962):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4962):   adb logcat -s GAv4
,W/GAv4    ( 4962): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4962): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4962): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 4962): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4962): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 4962): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4962): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  951): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5031 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  951): Killing 4715:com.lge.qremote/u0a106 (adj 15): empty #11
I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 22.716ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 22.146ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.656ms
,I/QCNEJ   ( 1854): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1854): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 14:50:49.551 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  951): failed to open /acct/uid_10106/pid_4715/cgroup.procs: No such file or directory
I/art     ( 4962): CheckpointMarkThreadRoots callback created = 0xaaef0240
,W/ResourcesManager( 5031): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/JNIHelp ( 4962): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 4962): CheckpointMarkThreadRoots callback created = 0xb050ea40
,W/System  ( 4962): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4962): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  951): Killing 4829:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  951): failed to open /acct/uid_10021/pid_4829/cgroup.procs: No such file or directory
,I/ActivityManager(  951): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5064 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/UpdateIcingCorporaServi( 1978): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/[BNRAppListMgrReceiver]( 5064): android.intent.action.PACKAGE_ADDED : com.example.hello
,I/ActivityManager(  951): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5085 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  951): Killing 4853:com.google.android.partnersetup/u0a9 (adj 15): empty #11
D/charger_monitor(  491): init target 500000
,I/UpdateIcingCorporaServi( 1978): UpdateCorporaTask done [took 163 ms] updated apps [took 163 ms] 
,W/libprocessgroup(  951): failed to open /acct/uid_10009/pid_4853/cgroup.procs: No such file or directory
,D/PowerService( 1817): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1385): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1385): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1385): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1385): On Skip Timer : true
D/charger_monitor(  491): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1854): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1854): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1385): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1385): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1385): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
D/HeadsetStateMachine( 2063): Disconnected process message: 10, size: 0
D/LEDHandler( 1817): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1817): Battery Level Remaining: 100%
D/LEDHandler( 1817): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
,I/[SystemUI]BatterySaverHandler( 1385): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  951): battery changed pluggedType: 2
W/Settings(  951): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  951): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1385): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1817): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1385): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1385): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1385): On Skip Timer : true
D/Finsky  ( 5085): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5085): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5085): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5085): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5085): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3188): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3188): created cursor android.database.sqlite.SQLiteCursor@1c2d518b on behalf of 5085
I/NotificationManager( 5085): com.android.vending: cancel(-602347385) by com.android.vending
,D/Finsky  ( 5085): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5085): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5085): Skipping gmscore version check
I/ActivityManager(  951): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5137 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/Finsky  ( 5085): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5085): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
,D/Finsky  ( 5085): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  951): Killing 4873:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/ResourcesManager( 5137): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5137): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  951): failed to open /acct/uid_10011/pid_4873/cgroup.procs: No such file or directory
,I/MultiDex( 5137): VM with version 2.1.0 has multidex support
I/MultiDex( 5137): install
I/MultiDex( 5137): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5137): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5137): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5137): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c5e4b12: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5137): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5137): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5137): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 5137): Reading stored module config
,D/PackageBroadcastService( 5137): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
D/ChimeraCfgMgr( 5137): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5137): Loading module APK com.google.android.play.games
,D/NativeLibraryUtils( 5137): Install completed successfully. count=14 extracted=0
,I/art     ( 5137): CheckpointMarkThreadRoots callback created = 0xaaee7d80
,I/art     ( 5137): CheckpointMarkThreadRoots callback created = 0xaaee7d60
,D/ChimeraCfgMgr( 5137): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5137): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 5137): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 5137): Submit a task: k
,D/ChimeraCfgMgr( 5137): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 5137): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 5137): Processing package: com.example.hello
,D/GassUtils( 5137): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
D/k       ( 5137): Found info for package com.example.hello in db.
,I/Icing   ( 5137): Storage manager: low false usage 1.73MB avail 2.40GB capacity 4.06GB
I/ActivityManager(  951): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5189 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,W/BaseAppContext( 5137): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 5137): cleanUpNonGplusAccounts done.
I/art     ( 5137): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5137): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/ResourcesManager( 5189): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/Icing   ( 5137): Array storage bad crc 2159224471 vs 3129975703
,E/Icing   ( 5137): Array storage bad crc 1693463767 vs 2902800
E/BaseAppContext( 5137): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,E/Icing   ( 5137): Array storage bad crc 770614030 vs 117162139
E/Icing   ( 5137): Trie mmap suffix failed
W/BaseAppContext( 5137): Using Auth Proxy for data requests.
,D/BluetoothManagerService(  951): Message: 20
D/BluetoothManagerService(  951): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a2fd30b:true
,D/BluetoothAdapterService(1061685702)( 2063): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1da6664c
D/BluetoothAdapterService(1061685702)( 2063): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1da6664c
W/Icing   ( 5137): Docstore bad crc 0x858afbd5 vs 0x1664348f
,I/ActivityManager(  951): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5218 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/BaseAppContext( 5137): Using Auth Proxy for data requests.
,E/Icing   ( 5137): Array storage bad crc 3273046437 vs 0
,E/Icing   ( 5137): Trie mmap node failed
W/BaseAppContext( 5137): Using Auth Proxy for data requests.
W/BaseAppContext( 5137): Using Auth Proxy for data requests.
W/BaseAppContext( 5137): Using Auth Proxy for data requests.
,W/BaseAppContext( 5137): Using Auth Proxy for data requests.
,I/ActivityManager(  951): Waited long enough for: ServiceRecord{313c8c74 u0 com.lge.springcleaning/.service.AppCleanupService}
,I/MusicStore( 5218): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5218): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/Icing   ( 5137): updateResources: need to parse f{com.google.android.gms}
,I/art     ( 4023): Explicit concurrent mark sweep GC freed 2843(112KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 422us total 25.725ms
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5218): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5218): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 5218): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5218): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5218): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Icing   ( 5137): Internal init done: storage state 0
,I/NotificationManager( 5137): com.google.android.gms: cancel(10436) by com.google.android.gms
,W/ActivityThread( 5218): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5218): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@21b08237: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5218): Installed default security provider GmsCore_OpenSSL
,D/ChimeraCfgMgr( 5137): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5137): Module APK com.google.android.play.games already loaded
D/AndroidMusic( 5218): GMSCore installation verified
I/ConfigStore( 5218): Config Database version: 1
,I/Icing   ( 5137): 22 corpora need re-polling
,I/Icing   ( 5137): Post-init done
,I/art     (  951): Explicit concurrent mark sweep GC freed 21719(1077KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 1.723ms total 136.323ms
,I/Icing   ( 5137): Indexing 1612944C7007A012B1C904336C8580EC6DBD4F91 from com.google.android.music
,I/MediaRouter( 5218): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5218): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 5218): type=WIFI subType= reason=null isConnected=true
,I/Icing   ( 5137): Indexing done 1612944C7007A012B1C904336C8580EC6DBD4F91
,I/Icing   ( 5137): Indexing 1F53EECCEBEB5877C2973BC154C132777EB605A6 from com.google.android.apps.books
W/ActivityManager(  951): Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{311bbff7 5137:com.google.android.gms/u0a6} (pid=5137, uid=10006) that is not exported from uid 10046
E/Icing   ( 5137): Cursor call threw an exception: Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{311bbff7 5137:com.google.android.gms/u0a6} (pid=5137, uid=10006) that is not exported from uid 10046
I/Icing   ( 5137): Indexing done 1F53EECCEBEB5877C2973BC154C132777EB605A6
E/Icing   ( 5137): Aborting indexing of corpus volumes__id
I/Icing   ( 5137): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/NetworkMonitor( 5218): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  951): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=5265 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/GHttpClientFactory( 5218): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5218): Using platform SSLCertificateSocketFactory
I/art     ( 5218): CheckpointMarkThreadRoots callback created = 0xb042d3a0
,W/ResourcesManager( 5265): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5265): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5265): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  951): Killing 4890:com.android.gallery3d/u0a23 (adj 15): empty #11
,I/art     ( 5218): CheckpointMarkThreadRoots callback created = 0xb042d370
W/libprocessgroup(  951): failed to open /acct/uid_10023/pid_4890/cgroup.procs: No such file or directory
,I/NotificationManager( 5218): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 5265): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
W/art     ( 5137): Suspending all threads took: 7.365ms
D/LGEmail ( 5265): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/Icing   ( 5137): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 5137): Indexing B2F716F68058802BDD4E913C0921699984AB1871 from com.google.android.videos
,I/ActivityManager(  951): Start proc com.google.android.videos for content provider com.google.android.videos/.search.IcingContentProvider: pid=5293 uid=10099 gids={50099, 9997, 3003, 1028, 1015, 3002} abi=armeabi
,D/eas_req ( 5265): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,W/ResourcesManager( 5293): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
I/ActivityManager(  951): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5313 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 5265): JNI_OnLoad()
I/HubEmail( 5265): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5265): registerNatives()
I/HubEmail( 5265): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5265): registerNativeMethods()
I/HubEmail( 5265): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 5265): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  951): Killing 4909:com.android.contacts/u0a18 (adj 15): empty #11
,W/Settings( 5265): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/libprocessgroup(  951): failed to open /acct/uid_10018/pid_4909/cgroup.procs: No such file or directory
D/LGDMClient( 5313): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 5313): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 5313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 5313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 5313): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 5313): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 5313): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 5313): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  951): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=5339 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ContextImpl( 5313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 5313): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 5313): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 5313): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 5313): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 5313): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/AppUp4:AppBoxCP( 5339): onCreate
,W/AppUp4:DB( 5339):  [AppBoxDatabaseHelper] construct
I/[LGHome]EVENT( 1891): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/AppUp4:DB( 5339):  setFingerPrint start
I/AppUp4:DB( 5339):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/QCNEJ   ( 1854): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[LGHome]LGPlusHomeDBManager( 1891): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1891): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[SystemUI]QPairHandler( 1385): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  951): Reconfiguring input devices.  changes=0x00000010
I/AppUp4:DB( 5339):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5339):  SDK version = 0
I/AppUp4:DB( 5339):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5339): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 5339): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 5339): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QSlideListController( 1385): onReceive = android.intent.action.PACKAGE_CHANGED
I/NetworkStateForAutoUpdateMonitor( 5339): [onReceive] connect :true
W/[SystemUI]QSlideLoader( 1385): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,I/NetworkStateForAutoUpdateMonitor( 5339): [onReceive] request level :IDLE....
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1385): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/AppUp4:CustModeStarterReceiver( 5339): onReceive
I/AppUp4:CustModeStarterReceiver( 5339): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 5339): Context : android.app.ReceiverRestrictedContext@36d5a1ab
D/AppUp4:CustFacade( 5339): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 5339): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5339): begin check event
I/AppUp4:CustModeStarterReceiver( 5339): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 5339): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
I/art     ( 1800): CheckpointMarkThreadRoots callback created = 0xb042d2f0
D/AppUp4:CustModeStarterReceiver( 5339): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 5339): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 5339): handleAsyncCustNotification do not startCustService
I/ActivityManager(  951): Killing 4928:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/art     ( 1800): CheckpointMarkThreadRoots callback created = 0xb042d7e0
D/administrator(  951): Handling package changes for user 0
,I/art     ( 1891): Background sticky concurrent mark sweep GC freed 33786(1823KB) AllocSpace objects, 10(844KB) LOS objects, 10% free, 23MB/25MB, paused 39.344ms total 102.906ms
W/libprocessgroup(  951): failed to open /acct/uid_10069/pid_4928/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3160): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3160): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3160): networkInfo.isConnected() = true
,D/PhoneState( 3160): setPdpRejectCasuse : false
,I/ActivityManager(  951): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5377 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/NotificationService(  951): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  951): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  951): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  951): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourcesManager(  951): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/BackupManagerService(  951): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  951): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3636faf1
D/UEI.SmartControl( 4980): Internal timer expired: 1
,D/UEI.SmartControl( 4980): Service.onUnbind: IControl
D/UEI.SmartControl( 4980): Service.onDestroy
D/UEI.SmartControl( 4980): Shutdown IRRCPlayer... 
,W/irrc_jni( 4980): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 4980): ~IrrcClient ++ 
D/irrcClient( 4980): ~IrrcClient -- 
W/irrc_jni( 4980): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 4980): Blaster closed
,D/UEI.SmartControl( 4980): Blaster closed
D/UEI.SmartControl( 4980): Shut down QS...
D/UEI.SmartControl( 4980): Stopped file observer...
I/UEI.SmartControl( 4980): QS lib stop result = true
D/UEI.SmartControl( 4980): QS shutdown complete
I/ActivityManager(  951): Killing 4945:com.lge.eula/1000 (adj 15): empty #11
,D/PhoneMonitor( 5377): Register our PhoneStateListener
,W/ResourceType(  951): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/libprocessgroup(  951): failed to open /acct/uid_1000/pid_4945/cgroup.procs: No such file or directory
,D/LCardEmulationManager( 1800): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1800): getDefaultRoute
D/MobileConnectivityChangeReceiver( 5377): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5377): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  951): Killing 4980:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
V/DownloadManager( 3188): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneMonitor( 5377): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 5377): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5377): [parse] Load xml
V/TelephonyAutoProfiling( 5377): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5377): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/ActivityManager(  951): Killing 4962:com.google.android.apps.docs/u0a58 (adj 15): empty #12
,D/PhoneMonitor( 5377): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  951): failed to open /acct/uid_10089/pid_4980/cgroup.procs: No such file or directory
,V/DownloadManager( 3188): DownloadService onCreate
W/libprocessgroup(  951): failed to open /acct/uid_10058/pid_4962/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1891): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/DownloadManager( 3188): in removeSpuriousFiles
V/DownloadManager( 3188): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3188): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3188): created cursor android.database.sqlite.SQLiteCursor@2bcfe326 on behalf of 3188
I/DownloadManager( 3188): in trimDatabase
V/DownloadManager( 3188): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3188): created cursor android.database.sqlite.SQLiteCursor@24d11d14 on behalf of 3188
I/Icing   ( 5137): Indexing done B2F716F68058802BDD4E913C0921699984AB1871
I/Icing   ( 5137): Indexing FC5805F301A6400196925772B79FE617968B1409 from com.google.android.videos
,I/ActivityManager(  951): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5403 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3188): DownloadService onStartCommand
V/DownloadManager( 3188): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3188): created cursor android.database.sqlite.SQLiteCursor@7c70bb2 on behalf of 3188
I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 308us total 24.967ms
,I/GCoreNlp( 1747): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 21.641ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 22.551ms
I/Icing   ( 5137): Indexing done FC5805F301A6400196925772B79FE617968B1409
,I/CheckinService( 5137): Checkin interval check for package: unspecified last checkin: 1452248357147 min interval config: 0 actual interval: 12697291
I/Icing   ( 5137): Indexing 568CE8700B788EF0A23FB149BDEF8EE9F7A56DE9 from com.google.android.gms
W/PlayMovies( 5293): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 5293): 
,I/CheckinService( 5137): Disabling old GoogleServicesFramework version
,D/DrmBroadcastReceiver( 5403): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 5403): 1  network is available. Sync DRM Time with NTP
D/WeatherAncestor( 2669): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:50:54
V/DrmService( 5403): Service onCreate
D/DrmService( 5403): Received new request = 2
V/DownloadManager( 3188): DownloadService onDestroy
D/UpdateThreadPoolManager( 2669): 2 : This is isUpdating : false
,W/PlayMovies( 5293): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 5293): 
I/DrmSntpClient( 5403): Start Sync process
D/DrmSntpClient( 5403): Server : 0
D/WeatherAncestor( 2669): connectivity changed - connection : true
D/Weather_cast( 2669): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2669): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:50:54
D/WeatherService( 2669): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd( 5403): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5403): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5403): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5403): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  277): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
I/Icing   ( 5137): Indexing done 568CE8700B788EF0A23FB149BDEF8EE9F7A56DE9
I/Icing   ( 5137): Indexing 261F31C44790DA98645222D6E4244392E5409193 from com.google.android.gms
,I/Icing   ( 5137): Indexing done 261F31C44790DA98645222D6E4244392E5409193
I/Icing   ( 5137): Indexing AC7CA1348821615DDDE9D587591668A8B8E68A6F from com.google.android.googlequicksearchbox
I/ActivityManager(  951): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5434 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/LocationProviderProxy(  951): applying state to connected service
W/ActivityManager(  951): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2669): 2 : Utils getTopActivity com.lge.launcher2 / true
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 5403): propertyValue:false
D/WeatherService( 2669): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2669): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/PlayMovies( 5293): PersistentCache.cleanup:94 Cache is below limit, no need to shrink: [size=0, limit=5242880]
D/PlayMovies( 5293): 
I/CheckinService( 5137): Checking schedule, now: 1452261054584 next: 1452248387064
I/CheckinService( 5137): active receiver: enabled
,I/LGDrmClient( 5403): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  287): eDRM_SetDRMTime +++
I/LGDRM   (  287): [DRM] SET TIME : YR=2016, MON=1, DAY=8
,I/LGDRM   (  287): [DRM] SET TIME : HR=13, MIN=50, SEC=53
W/AudioCapabilities( 5293): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5293): Unsupported mime audio/adpcm
,W/AudioCapabilities( 5293): Unsupported mime audio/g726
I/CheckinService( 5137): Preparing to send checkin request
V/ILGDrmService(  287): eDRM_SetDRMTime ---
I/DrmSntpClient( 5403): Synched
W/AudioCapabilities( 5293): Unsupported mime audio/x-ms-wma
D/DrmService( 5403): Completed !! request = 2
D/DrmService( 5403): Request count = 0
W/AudioCapabilities( 5293): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 5293): Unsupported mime video/mjpg
V/DrmService( 5403): Service onDestroy
D/Finsky  ( 5085): [559] SignatureUtils.faultInOtherSignatures: Will not allow first-party apps signed by test keys
D/Finsky  ( 5085): [559] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.videos
W/VideoCapabilities( 5293): Unsupported mime video/theora
,I/EventLogService( 5137): Accumulating logs since 1452259905427
I/Icing   ( 5137): Indexing done AC7CA1348821615DDDE9D587591668A8B8E68A6F
I/Icing   ( 5137): Indexing 83A00FDEBC70CD82044D41C3D8A6BD97ECE0C652 from com.google.android.googlequicksearchbox
,D/PlayMovies( 5293): TransferService.onCreate:60 creating transfer service
D/PlayMovies( 5293): 
W/ResourcesManager( 5434): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/AudioCapabilities( 5293): Unsupported mime audio/evrc
,W/AudioCapabilities( 5293): Unsupported mime audio/qcelp
W/VideoCapabilities( 5293): Unrecognized profile 2130706433 for video/avc
I/Icing   ( 5137): Indexing done 83A00FDEBC70CD82044D41C3D8A6BD97ECE0C652
I/Icing   ( 5137): Indexing 736B0110C483B1C6D43A79F22BB0C3E0A2D6B16D from com.google.android.gm
W/AudioCapabilities( 5293): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5293): Unsupported mime audio/qcelp
W/AudioCapabilities( 5293): Unsupported mime audio/evrc
W/VideoCapabilities( 5293): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5293): Unsupported profile 4 for video/mp4v-es
,I/ActivityManager(  951): Start proc com.google.android.gm for content provider com.google.android.gm/.provider.SearchQuery$Provider: pid=5457 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/WVCdm   (  282): Instantiating CDM.
,I/WVCdm   (  282): CdmEngine::QueryStatus
I/WVCdm   (  282): Level3 Library Dec 11 2014 16:13:16
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.videos/files/Movies/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5293): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.videos/files/Movies
W/WVCdm   (  282): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  282): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  282): L1 library not specified. Falling Back to L3
I/WVCdm   (  282): L3 Terminate.
I/CheckinRequestBuilder( 5137): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  951): Killing 5031:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  951): failed to open /acct/uid_10086/pid_5031/cgroup.procs: No such file or directory
E/ActivityThread( 5137): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 4023): Explicit concurrent mark sweep GC freed 1593(56KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 379us total 28.742ms
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Babel_SMS( 5434): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5434): MmsConfig.loadMmsSettings
,W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Babel_SMS( 5434): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5434): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5434): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5434): MmsConfig.loadFromResources
,E/Babel_SMS( 5434): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5434): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Gmail   ( 5457): getAccountsCursor
,I/art     (  951): Explicit concurrent mark sweep GC freed 21175(1142KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.474ms total 159.347ms
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SensorManager( 5434): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5434): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5434): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5434): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5434): found sensor: LGE Gravity Sensor, handle=29
,D/SensorManager( 5434): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5434): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5434): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5434): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5434): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5434): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5434): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5434): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5434): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5434): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5434): found sensor: Motion Accel, handle=46
I/Icing   ( 5137): Indexing done 736B0110C483B1C6D43A79F22BB0C3E0A2D6B16D
I/Icing   ( 5137): Indexing 59716A40DEE00805E4208F1709FD830CA906A723 from com.google.android.music
,W/GAV2    ( 5457): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/art     ( 5434): CheckpointMarkThreadRoots callback created = 0xb042d870
W/Settings( 5434): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5434): startup - clean
I/art     ( 5434): CheckpointMarkThreadRoots callback created = 0xb042d850
W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Icing   ( 5137): Indexing done 59716A40DEE00805E4208F1709FD830CA906A723
I/Icing   ( 5137): Not indexing corpus from package com.android.chrome as it has never connected
E/Icing   ( 5137): Aborting indexing of corpus omnibox
I/Icing   ( 5137): Indexing 24AE284E02EC07BD7845C2A57E58BAA08F2A03E3 from com.google.android.gms
I/Gmail   ( 5457): getAccountsCursor
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Gmail   ( 5457): Error finding the version of the Email provider.....
E/Gmail   ( 5457): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5457): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5457): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5457): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5457): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5457): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5457): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5457): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5457): We do not support migrating this version of the Email provider.
I/Icing   ( 5137): Indexing done 24AE284E02EC07BD7845C2A57E58BAA08F2A03E3
I/Icing   ( 5137): Indexing F200CD067697391E5BA8387C554D1EADCF480F28 from com.google.android.gms
,I/Babel   ( 5434): deleted: false for 0
,W/ActivityManager(  951): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5457): Observing account changes for notifications
,W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Icing   ( 5137): Indexing done F200CD067697391E5BA8387C554D1EADCF480F28
I/Icing   ( 5137): Indexing 8E811E0C18BDD106917E39D7CA94D72D22D4A1B5 from com.google.android.music
I/ActivityManager(  951): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5508 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  951): Killing 5064:com.lge.bnr/1000 (adj 15): empty #11
,W/AudioCapabilities( 5434): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5434): Unsupported mime audio/adpcm
W/AudioCapabilities( 5434): Unsupported mime audio/g726
,W/AudioCapabilities( 5434): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5434): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5434): Unsupported mime video/mjpg
W/VideoCapabilities( 5434): Unsupported mime video/theora
W/AudioCapabilities( 5434): Unsupported mime audio/evrc
,W/AudioCapabilities( 5434): Unsupported mime audio/qcelp
W/VideoCapabilities( 5434): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5434): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5434): Unsupported mime audio/qcelp
,I/Gmail   ( 5457): notifyAccountChanged
W/AudioCapabilities( 5434): Unsupported mime audio/evrc
,I/Gmail   ( 5457): getAccountsCursor
I/Gmail   ( 5457): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5457): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/VideoCapabilities( 5434): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5434): Unsupported profile 4 for video/mp4v-es
,W/libprocessgroup(  951): failed to open /acct/uid_1000/pid_5064/cgroup.procs: No such file or directory
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/QCNEJ   ( 1854): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1854): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 14:50:55.591 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/Gmail   ( 5457): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/VideoCapabilities( 5434): Unrecognized profile 2130706433 for video/avc
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Gmail   ( 5457): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/VideoCapabilities( 5434): Unrecognized profile 2130706433 for video/avc
,I/Icing   ( 5137): Indexing done 8E811E0C18BDD106917E39D7CA94D72D22D4A1B5
I/Icing   ( 5137): Indexing 98E736199A4D0A3DAA0BBDB44355DD80A1943A96 from com.google.android.googlequicksearchbox
W/VideoCapabilities( 5434): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5434): Unrecognized profile 2130706433 for video/avc
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/vclib   ( 5434): onServiceConnected
W/Babel   ( 5434): Attempted to change video mute state without an active call.
I/NotificationManager( 5434): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 5434): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5434): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5434): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5434): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  277): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out( 5434): propertyValue:false
I/Icing   ( 5137): Indexing done 98E736199A4D0A3DAA0BBDB44355DD80A1943A96
,I/Icing   ( 5137): Indexing 0A5267A505F47CB39AEB664724AACA2991DAA8A8 from com.google.android.googlequicksearchbox
I/Icing   ( 5137): Indexing done 0A5267A505F47CB39AEB664724AACA2991DAA8A8
,I/Icing   ( 5137): Indexing 47A5FE9A32182B9012C8EBBEC9FB6699B7BD9AC4 from com.google.android.googlequicksearchbox
I/Babel   ( 5434): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  951): Killing 5218:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  951): failed to open /acct/uid_10081/pid_5218/cgroup.procs: No such file or directory
,D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 1747): propertyValue:false
I/Gmail   ( 5457): getAccountsCursor
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Icing   ( 5137): Indexing done 47A5FE9A32182B9012C8EBBEC9FB6699B7BD9AC4
I/Icing   ( 5137): Indexing BC9EFFA8FB4EBD74F2B7898FFA6492656D342420 from com.google.android.music
I/ActivityManager(  951): Start proc com.google.android.music:main for content provider com.google.android.music/.icing.IcingContentProvider: pid=5538 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5508): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5508): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5508): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5508): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 5508): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5508):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5508):   adb logcat -s GAv4
,W/GAv4    ( 5508): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5508): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5508): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/NotificationManager(  951): android: cancelAsUser(2) by android
,I/NotificationManager( 1747): com.google.android.gms: cancel(0) by com.google.android.gms
,I/MusicStore( 5538): Database version: 120
,I/ActivityManager(  951): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5580 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5538): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 5580): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5580): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/WebViewFactory( 5508): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5508): Time to load native libraries: 2 ms (timestamps 3148-3150)
,I/LibraryLoader( 5508): Expected native library version number "",actual native library version number ""
I/MultiDex( 5580): VM with version 2.1.0 has multidex support
I/MultiDex( 5580): install
I/MultiDex( 5580): VM has multidex support, MultiDex support library is disabled.
V/WebViewChromiumFactoryProvider( 5508): Binding Chromium to main looper Looper (main, tid 1) {7b866dc}
I/LibraryLoader( 5508): Expected native library version number "",actual native library version number ""
,I/chromium( 5508): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,V/JNIHelp ( 5580): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/BrowserStartupController( 5508): Initializing chromium process, singleProcess=true
W/art     ( 5508): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5508): ApplicationContext is null in ApplicationStatus
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5538): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5538): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 5538): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5538): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ActivityThread( 5580): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5580): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3aaafaac: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5580): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5580): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5580): com.google.android.gms: cancel(39789) by com.google.android.gms
W/chromium( 5508): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5508): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5508): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
I/Adreno-EGL( 5508): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5508): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5508): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5508): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5508): Remote Branch: 
I/Adreno-EGL( 5508): Local Patches: 
I/Adreno-EGL( 5508): Reconstruct Branch: 
D/sensors_hal_Time(  951): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  951): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  951): tsOffsetIs: Apps: 73306584351; DSPS: 2500844; Offset : -3023241049
,V/JNIHelp ( 5538): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/art     ( 5580): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5580): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/ActivityThread( 5538): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5538): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2864950d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5538): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5538): GMSCore installation verified
I/Icing   ( 5137): Indexing done BC9EFFA8FB4EBD74F2B7898FFA6492656D342420
I/Icing   ( 5137): Indexing D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E from com.google.android.gm
,V/AudioPolicyService(  282): registerClient() client 0xb4027800, uid 10079
I/ConfigStore( 5538): Config Database version: 1
W/AudioManagerAndroid( 5508): Requires BLUETOOTH permission
I/NSApplication( 5508): Starting up...
D/WVCdm   (  282): Instantiating CDM.
,I/WVCdm   (  282): CdmEngine::OpenSession
I/WVCdm   (  282): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  282): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  282): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  282): L1 library not specified. Falling Back to L3
,I/Icing   ( 5137): Indexing done D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E
I/Icing   ( 5137): Indexing B7CDD2A0D3DB11D9F7572112AFD71A44FC4A5839 from com.google.android.gms
I/ActivityManager(  951): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5630 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 5137): Indexing done B7CDD2A0D3DB11D9F7572112AFD71A44FC4A5839
I/Icing   ( 5137): Indexing 67F95B901D405C76FD2CE1ACA2CB152B1EA2BD15 from com.google.android.googlequicksearchbox
D/NativeLibraryUtils( 5580): Install completed successfully. count=14 extracted=0
I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/WVCdm   (  282): PrepareKeyRequest: nonce=2119747892
I/GoogleURLConnFactory( 5580): Using platform SSLCertificateSocketFactory
,D/libc-netbsd( 5580): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5580): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5580): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5580): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 5580): propertyValue:false
I/Icing   ( 5137): Indexing done 67F95B901D405C76FD2CE1ACA2CB152B1EA2BD15
,I/Icing   ( 5137): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/Icing   ( 5137): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/Icing   ( 5137): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/MediaRouter( 5538): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 5538): type=WIFI subType= reason=null isConnected=true
,D/libc-netbsd( 5580): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5580): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5580): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5580): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  951): Killing 5265:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  951): failed to open /acct/uid_10021/pid_5265/cgroup.procs: No such file or directory
,I/NetworkMonitor( 5538): type=WIFI subType= reason=null isConnected=true
I/art     ( 5580): CheckpointMarkThreadRoots callback created = 0xb04cced0
,I/art     ( 5580): CheckpointMarkThreadRoots callback created = 0xb04ccec0
,I/art     (  951): Explicit concurrent mark sweep GC freed 16839(975KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 1.764ms total 144.753ms
,I/GHttpClientFactory( 5538): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 5538): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  951): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5657 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  951): Killing 5339:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/ActivityManager(  951): Killing 5313:com.lge.lgdmsclient/1000 (adj 15): empty #12
,I/NotificationManager( 5538): com.google.android.music: cancel(1061) by com.google.android.music
W/libprocessgroup(  951): failed to open /acct/uid_10011/pid_5339/cgroup.procs: No such file or directory
W/libprocessgroup(  951): failed to open /acct/uid_1000/pid_5313/cgroup.procs: No such file or directory
W/ResourcesManager( 5657): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  951): Killing 5377:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/dex2oat ( 5683): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  951): failed to open /acct/uid_10038/pid_5377/cgroup.procs: No such file or directory
I/dex2oat ( 5683): dex2oat took 94.784ms (threads: 4)
,I/Adreno-EGL( 5580): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5580): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5580): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5580): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5580): Remote Branch: 
I/Adreno-EGL( 5580): Local Patches: 
I/Adreno-EGL( 5580): Reconstruct Branch: 
,I/iu.SyncManager( 5137): SYNC; picasa accounts
,D/NetworkLogImpl( 5137): Loaded NetworkSpeedPredictor
I/iu.Environment( 5137): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 5137): num queued entries: 0
I/iu.UploadsManager( 5137): num updated entries: 0
I/iu.SyncManager( 5137): NEXT; no task
,I/ActivityManager(  951): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=5699 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
V/SmsReceiverService( 3160): onStart: #1 mResultCode: -1 = Activity.RESULT_OK
D/MmsConfig( 3160): isNotAllowedSms: currentUser:0
D/MmsConfig( 3160): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3160): isUserMode:false
D/SmsReceiverService( 3160): handleMessage isUserMode:false
,V/SmsReceiverService( 3160): handleMessage action: com.android.mms.transaction.SEND_MESSAGE error: 0
,D/SmsReceiverService( 3160): [LGE] handleSendMessage Send messages in queue
,I/Adreno-EGL( 5580): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5580): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5580): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5580): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5580): Remote Branch: 
I/Adreno-EGL( 5580): Local Patches: 
I/Adreno-EGL( 5580): Reconstruct Branch: 
,I/Adreno-EGL( 5580): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5580): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5580): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5580): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5580): Remote Branch: 
I/Adreno-EGL( 5580): Local Patches: 
I/Adreno-EGL( 5580): Reconstruct Branch: 
,I/DigitalAppWidgetProvider( 5699): onReceive: android.intent.action.ALARM_CHANGED
,I/ActivityManager(  951): Killing 5403:com.lge.drmservice/u0a51 (adj 15): empty #11
,I/WVCdm   (  282): CdmEngine::OpenSession
,W/libprocessgroup(  951): failed to open /acct/uid_10051/pid_5403/cgroup.procs: No such file or directory
D/WeatherAncestor( 2669): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:50:58
,D/UpdateThreadPoolManager( 2669): 2 : This is isUpdating : false
I/QCNEJ   ( 1854): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1854): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 14:50:58.604 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/Weather_cast( 2669): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2669): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:50:58
D/WeatherService( 2669): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ActivityManager(  951): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2669): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2669): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2669): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/[LGHome]LGNumberBadgeReceiver( 1891): [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = lge.intent.action.UNREAD_MESSAGES
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1891): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1891): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1891): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1891): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
I/ActivityManager(  951): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=5724 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,W/ResourcesManager( 5724): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5724): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5724): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5724): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5724): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 5724): Using schema version: 115
,I/IndexDatabaseHelper( 5724): Index is fine
D/UsbSettingsReceiver( 5724): [AUTORUN] onReceive() : action = android.hardware.usb.action.USB_STATE
D/UsbSettingsReceiver( 5724): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 5724): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5724): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5724): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsReceiver( 5724): [AUTORUN] onReceive() : getDefaultFunction = ptp_only
,D/UsbSettingsReceiver( 5724): [AUTORUN] onReceive() : USB_FUNCTION_CDROM_STORAGE = false
D/UsbSettingsReceiver( 5724): [AUTORUN] onReceive() : mDirectAutorun = true
D/UsbSettingsReceiver( 5724): [AUTORUN] onReceive() : mActivityUsbModeChange = false
D/UsbSettingsReceiver( 5724): [AUTORUN] onReceive() : mActivityFinish = false
D/UsbSettingsReceiver( 5724): [AUTORUN] onReceive() : ===== USB Configured =====
D/UsbSettingsControl( 5724): [AUTORUN] setUsbConnected() : connected=true
D/UsbSettingsReceiver( 5724): [AUTORUN] onReceive() : checkQmicm = ptp_only,adb
D/UsbSettingsReceiver( 5724): [AUTORUN] : topPackageName=com.lge.launcher2
D/UsbSettingsReceiver( 5724): [AUTORUN] : topClassName=com.lge.launcher2.Launcher
D/UsbSettingsReceiver( 5724): [AUTORUN] Not exist com.android.LGSetupWizard
D/UsbSettingsReceiver( 5724): [AUTORUN] setUsbConnect() : mUsbSettingsRun = false
D/UsbSettingsReceiver( 5724): [AUTORUN] startUsbSettings() : deviceProvisioned=1
,I/ActivityManager(  951): Killing 5293:com.google.android.videos/u0a99 (adj 15): empty #11
I/WVCdm   (  282): CdmEngine::CloseSession
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  951): failed to open /acct/uid_10099/pid_5293/cgroup.procs: No such file or directory
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/WVCdm   (  282): PrepareKeyRequest: nonce=1245628186
I/ActivityManager(  951): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5747 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/MtpService( 3188): updating state; isCurrentUser=true, mMtpLocked=false
,I/PCSuite ( 5747): [StartReceiver]USB CONNECTED ver UsbManger : ptp_only
I/PCSuite ( 5747): [StartReceiver]isUsbPCSuiteMode : false
,D/PCSuite ( 5747): [StartReceiver][checkEUTStatus] eutStatus = 
D/PCSuite ( 5747): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5747): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  951): Killing 5085:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  951): failed to open /acct/uid_10036/pid_5085/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2669): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:50:59
D/UpdateThreadPoolManager( 2669): 2 : This is isUpdating : false
D/WeatherAncestor( 2669): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:50:59
D/WeatherService( 2669): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,W/ActivityManager(  951): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2669): 2 : Utils getTopActivity com.lge.launcher2 / true
V/UserPresentBroadcastReceiver( 1747): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/WeatherService( 2669): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2669): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2669): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2669): 2 : This is isUpdating : false
,D/WeatherService( 2669): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2669): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2669): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2669): 2 : Fixed theme : optimus
D/WeatherReflect( 2669): 2 : Map key string is -2
,D/lim     ( 2669): 2 : time = 14:50
I/WeatherReflect( 2669): Model Name : LG-D722
D/WeatherTheme( 2669): 2 : exactly same view!
D/WeatherTheme( 2669): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
W/ActivityManager(  951): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2669): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2669): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2669): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/LGMDMManager( 5189): Create singleton instance
,I/DigitalAppWidgetProvider( 5699): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2669): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:50:59
D/UpdateThreadPoolManager( 2669): 2 : This is isUpdating : false
D/Weather_cast( 2669): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2669): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:50:59
D/WeatherService( 2669): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
,W/ActivityManager(  951): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2669): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2669): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2669): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/AlertReceiver( 3835): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
D/AlertService( 3835): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 3835): [updateWidgets] 
,D/MonthWidgetProvider( 3835): [onReceive]
D/CalendarWidgetProvider( 3835): [onReceive]
D/CalendarWidgetProvider( 3835): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 3835): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 3835): [onReceive]
D/CalendarWidgetProvider( 3835): [onReceive]
D/CalendarWidgetProvider( 3835): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 3835): [onCreate] mContext.getPackageName() = com.android.calendar
D/CalendarWeatherReceiver( 3835): Get action=com.lge.calendar.action.WEATHER_SERVICE_START
,I/[SystemUI]SafeModeBroadcastReceiver( 1385): onReceive = com.lge.statusbar.bootcompleted
,I/ActivityManager(  951): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.DamagedFileRemover: pid=5782 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 310us total 21.495ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.958ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.080ms
,E/stst    ( 5782): DamagedFileRemover media scanning start or checking
,D/ToneMappingReceiver( 5699): Enter doAlarmRingToneUriMapping()
D/ToneMappingReceiver( 5699): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
,D/CommonUtil( 5699): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5699): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5699): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5699): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5699): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5699): Alarm Success count is 0
D/ToneMappingReceiver( 5699): Timer Success count is 0
I/ActivityManager(  951): Killing 5434:com.google.android.talk/u0a61 (adj 15): empty #11
I/[SystemUI]TimeTickManager( 1385): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1385): called onTimeUpdated()
I/[SystemUI]Clock( 1385): called onTimeUpdated()
I/LgeClockWidgetControlView( 1385): called onTimeUpdated()
I/[SystemUI]DateView( 1385): called onTimeUpdated()
I/[SystemUI]DateView( 1385): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1385): handleTimeUpdate
W/libprocessgroup(  951): failed to open /acct/uid_10061/pid_5434/cgroup.procs: No such file or directory
,I/MediaScannerReceiver( 3835): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///system/media
I/InitNotificationRingtoneService( 3835): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3835): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
D/WeatherService( 2669): 2 : TimeTick Intent has been received, Time(hour:min:sec) 14:51:0
D/WeatherService( 2669): 2 : TimeTick Intent And Screen On
D/WeatherService( 2669): 2 : SDK version : 21
W/ActivityManager(  951): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2669): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2669): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2669): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2669): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2669): 2 : This is isUpdating : false
D/WeatherService( 2669): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2669): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2669): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2669): 2 : Fixed theme : optimus
E/stst    ( 5782): DamagedFileRemover media scanning finished
D/WeatherReflect( 2669): 2 : Map key string is -2
D/lim     ( 2669): 2 : time = 14:51
I/WeatherReflect( 2669): Model Name : LG-D722
D/WeatherTheme( 2669): 2 : Different view - status_min_formatted : 50 != 51
D/WeatherTheme( 2669): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2669): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2669): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2669): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[SystemUI]TimeTickManager( 1385): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1385): called onTimeUpdated()
I/[SystemUI]Clock( 1385): called onTimeUpdated()
I/LgeClockWidgetControlView( 1385): called onTimeUpdated()
I/[SystemUI]DateView( 1385): called onTimeUpdated()
I/[SystemUI]DateView( 1385): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1385): handleTimeUpdate
I/AlertUtils( 3835): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/com.lge.bnr.receiver.DamagedFileRemover( 5782): android.intent.action.MEDIA_SCANNER_FINISHED
,D/Weather4x2_optimus( 2669): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2669): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2669): forecast size is 0
D/Theme   ( 2669): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2669): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2669): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2669): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2669): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2669): strTheme: com.lge.launcher2.theme.optimus
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
D/Theme   ( 2669): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2669): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2669): url is : null
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
D/Theme   ( 2669): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2669): 2 : update view, appWidgetId: 2
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,D/WeatherService( 2669): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 14:51:0
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3835): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
E/stst    ( 5782): DamagedFileRemover media scanning start or checking
D/ToneMappingReceiver( 5699): Enter doAlarmRingToneUriMapping()
I/AlertUtils( 3835): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3835): End InitializeAlertRingtoneService.onHandleIntent
,D/ToneMappingReceiver( 5699): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5699): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5699): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5699): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5699): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5699): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5699): Alarm Success count is 0
D/ToneMappingReceiver( 5699): Timer Success count is 0
I/MediaScannerReceiver( 3835): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
I/art     ( 5538): CheckpointMarkThreadRoots callback created = 0xb042d530
I/InitNotificationRingtoneService( 3835): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 3835): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
E/stst    ( 5782): DamagedFileRemover media scanning finished
I/com.lge.bnr.receiver.DamagedFileRemover( 5782): android.intent.action.MEDIA_SCANNER_FINISHED
,I/AlertUtils( 3835): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/art     ( 5538): CheckpointMarkThreadRoots callback created = 0xb042d500
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1891): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/ActivityManager(  951): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5816 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 3835): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3835): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 3835): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3835): End InitializeAlertRingtoneService.onHandleIntent
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1891): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/GAv4-SVC( 5137): Google Analytics 8.4.89 is starting up.
I/GAV2    ( 5457): Thread[GAThread,5,main]: No campaign data found.
W/ResourcesManager( 5816): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5816): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2d05f069
,D/CalendarProvider2( 5816): [getOrCreateCalendarAlarmManager]
,I/art     ( 3188): Explicit concurrent mark sweep GC freed 6066(389KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/10MB, paused 418us total 38.992ms
I/CalendarProvider2( 5816): Created com.android.providers.calendar.CalendarAlarmManager@8bb67fa(com.android.providers.calendar.CalendarProvider2@2d05f069)
D/CalendarProviderBroadcastReceiver( 5816): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5816): [IntentService] WakeLock acquire, start IntentSerivce
,D/CalendarProvider2( 5816): CalendarProviderIntentService.onCreate()
V/AlarmManager(  951): ELAPSED_WAKEUP set : Alarm{3325a5d9 type 2 when 77185 android} when 77185
D/CalendarProvider2( 5816): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5816): [getOrCreateCalendarAlarmManager]
,D/WearableService( 1747): callingUid 10006, callindPid: 1747
E/MDM     ( 1747): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5137): Restart initialization of location
,D/AuthorizationBluetoothService( 1747): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1747): com.google.android.gms: cancel(0) by com.google.android.gms
D/CalendarProvider2( 5816): [IntentService] Release Lock
,D/CalendarProvider2( 5816): CalendarProviderIntentService.onDestroy()
D/WeatherAncestor( 2669): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 14:51:0
,W/GCoreFlp( 1747): No location to return for getLastLocation()
,W/FusedLocationProvider( 1747): location=null
D/UpdateThreadPoolManager( 2669): 2 : This is isUpdating : false
,D/WeatherService( 2669): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2669): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 2669): 2 : shouldTimeTickRegistered().........
,D/WeatherAncestor( 2669): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 14:51:0
D/WeatherService( 2669): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
W/ActivityManager(  951): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2669): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2669): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2669): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2669): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 2669): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2669): 2 : This is isUpdating : false
D/WeatherService( 2669): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2669): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2669): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2669): 2 : Fixed theme : optimus
D/WeatherReflect( 2669): 2 : Map key string is -2
,D/lim     ( 2669): 2 : time = 14:51
I/WeatherReflect( 2669): Model Name : LG-D722
D/WeatherTheme( 2669): 2 : exactly same view!
D/WeatherTheme( 2669): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
W/ActivityManager(  951): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2669): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2669): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2669): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
W/GCoreFlp( 1747): No location to return for getLastLocation()
,W/FusedLocationProvider( 1747): location=null
V/DownloadManager( 3188): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,W/InstanceID/Rpc( 5137): Found 10006
,I/art     (  951): Explicit concurrent mark sweep GC freed 16190(759KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 3.779ms total 234.824ms
,V/DownloadManager( 3188): created cursor android.database.sqlite.SQLiteCursor@c2cf680 on behalf of 5137
W/IcingInternalCorpora( 5137): getNumBytesRead when not calculated.
,I/MediaStoreImporter( 5538): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  951): Killing 5508:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  951): failed to open /acct/uid_10079/pid_5508/cgroup.procs: No such file or directory
,V/DownloadManager( 3188): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3188): created cursor android.database.sqlite.SQLiteCursor@94024b9 on behalf of 5137
V/DownloadManager( 3188): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3188): created cursor android.database.sqlite.SQLiteCursor@1b9630fe on behalf of 5137
I/ActivityManager(  951): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5859 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/WVCdm   (  282): CdmEngine::CloseSession
,I/WVCdm   (  282): L3 Terminate.
D/PhoneMonitor( 5859): Register our PhoneStateListener
,I/ActivityManager(  951): Killing 5630:com.android.chrome/u0a48 (adj 15): empty #11
,D/PhoneMonitor( 5859): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5859): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5859): [parse] Load xml
V/TelephonyAutoProfiling( 5859): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5859): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5859): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  951): failed to open /acct/uid_10048/pid_5630/cgroup.procs: No such file or directory
,I/CheckinService( 5137): Checkin interval check for package: unspecified last checkin: 1452248357147 min interval config: 0 actual interval: 12704384
,D/GCM     ( 1747): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/CheckinRequestBuilder( 5137): Classify the device as Phone.
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ActivityManager(  951): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5883 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/QCNEJ   ( 1854): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1854): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 14:51:01.619 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/libc-netbsd( 5137): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5137): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5137): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5137): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 5137): propertyValue:false
W/ResourcesManager( 5883): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/libc-netbsd( 5137): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5137): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5137): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5137): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5137): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5137): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5137): Sending checkin request (9896 bytes)
,I/Babel_SMS( 5883): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5883): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5883): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5883): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5883): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5883): MmsConfig.loadFromResources
E/Babel_SMS( 5883): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5883): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5883): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5883): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5883): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 5883): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5883): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5883): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5883): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5883): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5883): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5883): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5883): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5883): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5883): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5883): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5883): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5883): found sensor: Motion Accel, handle=46
W/Settings( 5883): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5883): startup - clean
,I/art     ( 5883): CheckpointMarkThreadRoots callback created = 0xb042d8b0
,I/Babel   ( 5883): deleted: false for 0
,I/art     ( 5883): CheckpointMarkThreadRoots callback created = 0xb042d880
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/art     ( 5883): Suspending all threads took: 10.902ms
,W/AudioCapabilities( 5883): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5883): Unsupported mime audio/adpcm
W/AudioCapabilities( 5883): Unsupported mime audio/g726
W/AudioCapabilities( 5883): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5883): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 5883): Unsupported mime video/mjpg
W/VideoCapabilities( 5883): Unsupported mime video/theora
W/AudioCapabilities( 5883): Unsupported mime audio/evrc
,W/AudioCapabilities( 5883): Unsupported mime audio/qcelp
W/VideoCapabilities( 5883): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5883): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5883): Unsupported mime audio/qcelp
W/AudioCapabilities( 5883): Unsupported mime audio/evrc
W/VideoCapabilities( 5883): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5883): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5883): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5883): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5883): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5883): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5883): onServiceConnected
W/Babel   ( 5883): Attempted to change video mute state without an active call.
,I/NotificationManager( 5883): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/CheckinRequestBuilder( 5137): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5137): Failed to find provider info for com.google.android.wearable.settings
W/ResourcesManager( 5883): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5883): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  951): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5923 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AudioManager( 5189): getMode name:com.lge.qremote
V/JNIHelp ( 5883): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AudioManager( 5189): getMode name:com.lge.qremote
,I/AudioManager( 5189): getMode name:com.lge.qremote
,I/AudioManager( 5189): getMode name:com.lge.qremote
,I/AudioManager( 5189): getMode name:com.lge.qremote
D/UEI.SmartControl( 5923): Quickset Services start...
,I/AudioManager( 5189): getMode name:com.lge.qremote
I/UEI.SmartControl( 5923): Manufacture = LGE
D/UEI.SmartControl( 5923): File observer start...
E/UEI.SmartControl( 5923): IR Port is disabled: false
D/UEI.SmartControl( 5923): Starting file observer...
D/UEI.SmartControl( 5923): Extracting JNI libs...
D/UEI.SmartControl( 5923): --- this system supports 32-bit or 64-bit only
,W/System  ( 5883): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5883): Installed default security provider GmsCore_OpenSSL
E/MDM     ( 1747): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5137): Restart initialization of location
D/AuthorizationBluetoothService( 1747): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1747): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 5189): getMode name:com.lge.qremote
,W/GCoreFlp( 1747): No location to return for getLastLocation()
W/FusedLocationProvider( 1747): location=null
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 5883): com.google.android.talk: cancel(8) by com.google.android.talk
,I/ActivityManager(  951): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5951 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/CheckinRequestBuilder( 5137): Classify the device as Phone.
,I/CheckinTask( 5137): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5137): Checking schedule, now: 1452261062812 next: 1452788311807
I/CheckinService( 5137): active receiver: disabled
,I/CheckinService( 5137): Checking schedule, now: 1452261062855 next: 1452788311807
I/CheckinService( 5137): active receiver: disabled
,I/AppUp4:AppBoxCP( 5951): onCreate
W/AppUp4:DB( 5951):  [AppBoxDatabaseHelper] construct
D/CheckinService( 5137): Recording last checkin time for package unspecified as 1452261062865
,I/AppUp4:DB( 5951):  setFingerPrint start
I/AppUp4:DB( 5951):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5951):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5951):  SDK version = 0
I/AppUp4:DB( 5951):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5951): AppBoxApplication onCreate()
D/UEI.SmartControl( 5923): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5923): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5923): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/AppUp4:CustModeStarterReceiver( 5951): onReceive
I/AppUp4:CustModeStarterReceiver( 5951): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5951): Context : android.app.ReceiverRestrictedContext@3c093e1c
D/AppUp4:CustFacade( 5951): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5951): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5951): begin check event
I/AppUp4:CustModeStarterReceiver( 5951): Event For Nothing, skip.
I/ActivityManager(  951): Killing 5657:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/UEI.SmartControl( 5923): --- Selecting new region: 2
I/UEI.SmartControl( 5923): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5923): Platform has CIR...
D/UEI.SmartControl( 5923): NO CIR support, need to check package...
I/UEI.SmartControl( 5923): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5923): QS Service created
W/libprocessgroup(  951): failed to open /acct/uid_10086/pid_5657/cgroup.procs: No such file or directory
,E/UEI.SmartControl( 5923): QS start get config
,I/ActivityManager(  951): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5973 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/UEI.SmartControl( 5923): Loading JNI Libs...
,D/UEI.SmartControl( 5923):  configuring local db...
,W/ResourcesManager( 5973): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5973): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5973): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5923):  ---- Has DB8: true
,D/UEI.SmartControl( 5923): QS start statue = true Error code = 0
D/UEI.SmartControl( 5923): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5923): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5923): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5923): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5923): IrrcClient ++ 
D/irrcClient( 5923): getIrrcService ++ 
D/irrcClient( 5923): getIrrcService -- 
D/irrcClient( 5923): IrrcClient -- 
W/irrc_jni( 5923): IRRCPlayer_nativeInit -- 
,I/AppConfig( 5973): Total System Memory = 906309632
D/UEI.SmartControl( 5923): Services init done
I/UEI.SmartControl( 5923): Device manager: loading config....
I/GalleryUtils( 5973): Application Heap = 96 MB
D/UEI.SmartControl( 5923): QS Service init finished
D/UEI.SmartControl( 5923): QS Service version name: 0.1.73
,D/UEI.SmartControl( 5923): QS Service version code: 1073
I/AppConfig( 5973): App Tier : NOT_DEF
D/UEI.SmartControl( 5923): Service requested: Control
D/UEI.SmartControl( 5923): Config is loaded...
D/SystemHelper( 5973): region [EU], country [EU], operator [OPEN], sub-operator []
D/UEI.SmartControl( 5923):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5923): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 5923): Request IControl service: devices are loaded...
D/UEI.SmartControl( 5923): Internal service binding...
D/UEI.SmartControl( 5923): -----IControl: 11
,D/UEI.SmartControl( 5923): Caller: com.lge.qremote
D/UEI.SmartControl( 5923): ------------ IControl registerCallback...
I/UEI.SmartControl( 5923): Registering callback...
D/UEI.SmartControl( 5923): -----IControl: 19
D/UEI.SmartControl( 5923): Caller: com.lge.qremote
I/UEI.SmartControl( 5923): Registering Services Ready callback...
I/UEI.SmartControl( 5923): Notify client services are ready...
D/UEI.SmartControl( 5923): -----IControl: 8
D/UEI.SmartControl( 5923): Caller: com.lge.qremote
I/ActivityManager(  951): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6001 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  951): Killing 5724:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  951): failed to open /acct/uid_1000/pid_5724/cgroup.procs: No such file or directory
,I/ActivityManager(  951): Killing 5699:com.lge.clock/u0a10 (adj 15): empty #11
I/ActivityManager(  951): Killing 5747:com.lge.sync/1000 (adj 15): empty #12
,W/libprocessgroup(  951): failed to open /acct/uid_10010/pid_5699/cgroup.procs: No such file or directory
W/libprocessgroup(  951): failed to open /acct/uid_1000/pid_5747/cgroup.procs: No such file or directory
W/ResourcesManager( 6001): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6001): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6001): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6001): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6001): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 6001): BUILD Country: EU
I/SystemConfig( 6001): BUILD Operator: OPEN
,I/SystemConfig( 6001): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 6001): existFile = false
I/SystemConfig( 6001): canReadFile = false
I/SystemConfig( 6001): systemFeature RCS result false
D/SystemConfig( 6001): refreshRcsSupport() :false
I/ActivityManager(  951): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6020 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  951): Killing 5538:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  951): failed to open /acct/uid_10081/pid_5538/cgroup.procs: No such file or directory
,I/LockScreenSettings( 6020): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6020): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6020): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6020): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6020): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6020): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  951): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6037 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  951): Killing 5782:com.lge.bnr/1000 (adj 15): empty #11
,W/libprocessgroup(  951): failed to open /acct/uid_1000/pid_5782/cgroup.procs: No such file or directory
,W/ResourcesManager( 6037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/InitAlarmsService( 3835): Clearing and rescheduling alarms.
,D/CalendarProvider2( 5816): Scheduling check of next Alarm
D/CalendarProvider2( 5816): SCHEDULE_ALARM_REMOVE
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/UpdateIcingCorporaServi( 1978): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  951): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6063 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1978): UpdateCorporaTask done [took 64 ms] updated apps [took 64 ms] 
,D/Finsky  ( 6063): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6063): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6063): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/QCNEJ   ( 1854): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1854): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 14:51:04.645 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/AlertService( 3835): Beginning updateAlertNotification
W/Settings( 6063): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/NotificationManager( 6063): com.android.vending: cancel(-1050172287) by com.android.vending
,I/[SystemUI]QPairHandler( 1385): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1891): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1891): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1891): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[SystemUI]QSlideListController( 1385): onReceive = android.intent.action.PACKAGE_CHANGED
I/QCNEJ   ( 1854): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  951): Reconfiguring input devices.  changes=0x00000010
W/[SystemUI]QSlideLoader( 1385): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1385): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
D/AlertService( 3835): No fired or scheduled alerts
,I/NotificationManager( 3835): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3835): com.android.calendar: cancel(1) by com.android.calendar
,I/NotificationManager( 3835): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3835): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3835): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3835): com.android.calendar: cancel(5) by com.android.calendar
D/administrator(  951): Handling package changes for user 0
I/NotificationManager( 3835): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3835): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3835): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3835): com.android.calendar: cancel(9) by com.android.calendar
,I/NotificationManager( 3835): com.android.calendar: cancel(10) by com.android.calendar
,I/NotificationManager( 3835): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3835): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3835): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3835): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3835): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3835): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3835): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3835): com.android.calendar: cancel(18) by com.android.calendar
V/DownloadManager( 3188): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3835): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3835): com.android.calendar: cancel(20) by com.android.calendar
,I/NotificationService(  951): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  951): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  951): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  951): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  951): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  951): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@30a7b2c9
,W/ResourcesManager(  951): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  951): Explicit concurrent mark sweep GC freed 29600(1451KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.600ms total 203.371ms
,V/DownloadManager( 3188): created cursor android.database.sqlite.SQLiteCursor@2454705f on behalf of 6063
D/AlertService( 3835): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 3835): No events found starting within 1 week.
D/Finsky  ( 6063): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6063): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 6063): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 6063): Skipping gmscore version check
,I/CalendarProvider2( 5816): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5816): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  951): Killing 5457:com.google.android.gm/u0a53 (adj 15): empty #11
D/Finsky  ( 6063): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ResourceType(  951): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/libprocessgroup(  951): failed to open /acct/uid_10053/pid_5457/cgroup.procs: No such file or directory
I/ActivityManager(  951): Killing 3835:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  951): failed to open /acct/uid_10013/pid_3835/cgroup.procs: No such file or directory
,D/LCardEmulationManager( 1800): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1800): getDefaultRoute
I/[LGHome]EVENT( 1891): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/ActivityManager(  951): Killing 5859:com.google.android.setupwizard/u0a38 (adj 15): empty #11
D/PackageBroadcastService( 5137): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
W/libprocessgroup(  951): failed to open /acct/uid_10038/pid_5859/cgroup.procs: No such file or directory
,I/PackageBroadcastService( 5137): Null package name or gms related package.  Ignoreing.
I/GCoreNlp( 1747): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  951): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6133 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 30.891ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 21.489ms
,I/Icing   ( 5137): updateResources: need to parse f{com.google.android.gms}
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 358us total 22.252ms
,D/LocationProviderProxy(  951): applying state to connected service
,D/KeyguardUpdateMonitor( 1385): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1385): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1385): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/PowerService( 1817): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1385): On Skip Timer : true
D/charger_monitor(  491): init target 500000
I/art     ( 5137): Explicit concurrent mark sweep GC freed 29998(2038KB) AllocSpace objects, 28(448KB) LOS objects, 39% free, 13MB/22MB, paused 5.093ms total 111.026ms
,D/KeyguardUpdateMonitor( 1385): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1385): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1385): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
D/LEDHandler( 1817): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1817): Battery Level Remaining: 100%
D/LEDHandler( 1817): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
W/Settings(  951): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  951): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  951): battery changed pluggedType: 2
I/QCNEJ   ( 1854): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1854): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2063): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1385): onReceive = android.intent.action.BATTERY_CHANGED
D/charger_monitor(  491): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/LEDHandler( 1817): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1817): Battery Level Remaining: 100%
D/LEDHandler( 1817): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2063): Disconnected process message: 10, size: 0
W/Settings(  951): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  951): battery changed pluggedType: 2
W/Settings(  951): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1854): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1854): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1385): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1385): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1385): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1385): onReceive = android.intent.action.BATTERY_CHANGED
W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,V/AlarmManager(  951): RTC_WAKEUP set : Alarm{3371ee60 type 0 when 1452261065607 com.android.vending} when 1452261065607
,I/art     ( 1747): Explicit concurrent mark sweep GC freed 39006(2MB) AllocSpace objects, 23(368KB) LOS objects, 39% free, 13MB/22MB, paused 1.357ms total 99.300ms
,I/Gmail   ( 6133): getAccountsCursor
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6133): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6133): Error finding the version of the Email provider.....
E/Gmail   ( 6133): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6133): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6133): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6133): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6133): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6133): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6133): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6133): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6133): We do not support migrating this version of the Email provider.
,E/MDM     ( 1747): [105] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager(  951): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/LocationInitializer( 5137): Restart initialization of location
I/Gmail   ( 6133): getAccountsCursor
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/AuthorizationBluetoothService( 1747): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/Gmail   ( 6133): Observing account changes for notifications
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1747): com.google.android.gms: cancel(0) by com.google.android.gms
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AudioManager( 5189): getMode name:com.lge.qremote
W/GCoreFlp( 1747): No location to return for getLastLocation()
W/FusedLocationProvider( 1747): location=null
D/Finsky  ( 6063): [730] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6063): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  951): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=6190 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  951): Killing 5951:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/Gmail   ( 6133): notifyAccountChanged
,I/Gmail   ( 6133): getAccountsCursor
I/Gmail   ( 6133): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6133): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6133): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6133): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/libprocessgroup(  951): failed to open /acct/uid_10011/pid_5951/cgroup.procs: No such file or directory
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MusicStore( 6190): Database version: 120
,I/Gmail   ( 6133): getAccountsCursor
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6190): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6190): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6190): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6190): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6190): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6190): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6190): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6190): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@21b08237: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6190): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6190): GMSCore installation verified
,I/ConfigStore( 6190): Config Database version: 1
,I/art     ( 4023): Explicit concurrent mark sweep GC freed 2971(116KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 399us total 34.477ms
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/MediaRouter( 6190): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 6190): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  951): Killing 5973:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  951): failed to open /acct/uid_10023/pid_5973/cgroup.procs: No such file or directory
,I/Icing   ( 5137): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/art     ( 6190): CheckpointMarkThreadRoots callback created = 0xb042d3f0
,I/NetworkMonitor( 6190): type=WIFI subType= reason=null isConnected=true
,I/art     ( 6190): CheckpointMarkThreadRoots callback created = 0xb042d3c0
,I/Icing   ( 5137): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/art     (  951): Explicit concurrent mark sweep GC freed 20036(1008KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.507ms total 185.489ms
,I/ActivityManager(  951): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6243 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/MusicLeanback( 6190): Stop autocaching.
I/MusicLeanback( 6190): Stop autocaching.
,I/MusicLeanback( 6190): Stop autocaching.
,I/GHttpClientFactory( 6190): Using our fixed implementation of GMSCore's GoogleHttpClient
I/MusicLeanback( 6190): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6190): Stop autocaching.
I/GoogleURLConnFactory( 6190): Using platform SSLCertificateSocketFactory
,D/PhoneMonitor( 6243): Register our PhoneStateListener
,V/SetupWizard( 6243): Connected to Gservices successfully
,I/ActivityManager(  951): Killing 6001:com.android.contacts/u0a18 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/PhoneMonitor( 6243): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6243): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6243): [parse] Load xml
,V/TelephonyAutoProfiling( 6243): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6243): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6243): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  951): failed to open /acct/uid_10018/pid_6001/cgroup.procs: No such file or directory
,I/NotificationManager( 6190): com.google.android.music: cancel(1061) by com.google.android.music
I/AudioManager( 5189): getMode name:com.lge.qremote
,D/GCM     ( 1747): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/GmsUtils( 6190): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6190): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/ActivityManager(  951): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6272 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  951): Killing 6020:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/NotificationManager( 5883): com.google.android.talk: cancel(8) by com.google.android.talk
W/libprocessgroup(  951): failed to open /acct/uid_10069/pid_6020/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6272): onCreate
W/AppUp4:DB( 6272):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6272):  setFingerPrint start
I/AppUp4:DB( 6272):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6272):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6272):  SDK version = 0
,I/AppUp4:DB( 6272):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6272): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6272): onReceive
I/AppUp4:CustModeStarterReceiver( 6272): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6272): Context : android.app.ReceiverRestrictedContext@3c093e1c
D/AppUp4:CustFacade( 6272): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6272): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6272): begin check event
I/AppUp4:CustModeStarterReceiver( 6272): Event For Nothing, skip.
I/ActivityManager(  951): Killing 5816:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  951): failed to open /acct/uid_10014/pid_5816/cgroup.procs: No such file or directory
,I/ActivityManager(  951): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6295 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 6295): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6295): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6295): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 6295): Total System Memory = 906309632
I/GalleryUtils( 6295): Application Heap = 96 MB
I/AppConfig( 6295): App Tier : NOT_DEF
,D/SystemHelper( 6295): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  951): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6317 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  951): Killing 6037:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  951): failed to open /acct/uid_10086/pid_6037/cgroup.procs: No such file or directory
,W/ResourcesManager( 6317): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6317): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6317): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6317): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,W/ResourcesManager( 6317): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/QCNEJ   ( 1854): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1854): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 14:51:07.658 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/SystemConfig( 6317): BUILD Country: EU
,I/SystemConfig( 6317): BUILD Operator: OPEN
I/ActivityManager(  951): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6336 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  951): Killing 6063:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  951): failed to open /acct/uid_10036/pid_6063/cgroup.procs: No such file or directory
,I/SystemConfig( 6317): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6317): existFile = false
I/SystemConfig( 6317): canReadFile = false
I/SystemConfig( 6317): systemFeature RCS result false
D/SystemConfig( 6317): refreshRcsSupport() :false
I/LockScreenSettings( 6336): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6336): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 6336): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6336): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6336): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6336): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  951): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6353 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  951): Killing 6133:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  951): failed to open /acct/uid_10053/pid_6133/cgroup.procs: No such file or directory
,W/ResourcesManager( 6353): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1978): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1978): UpdateCorporaTask done [took 39 ms] updated apps [took 39 ms] 
,I/ActivityManager(  951): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6378 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UEI.SmartControl( 5923): Internal timer expired: 1
,I/ActivityManager(  951): Killing 5580:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  951): failed to open /acct/uid_10006/pid_5580/cgroup.procs: No such file or directory
D/Finsky  ( 6378): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6378): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6378): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6378): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6378): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3188): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3188): created cursor android.database.sqlite.SQLiteCursor@3aaafaac on behalf of 6378
D/Finsky  ( 6378): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6378): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 6378): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 6378): Skipping gmscore version check
D/PackageBroadcastService( 5137): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 6378): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  951): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6427 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 5137): Null package name or gms related package.  Ignoreing.
I/Icing   ( 5137): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  951): Killing 6190:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  951): failed to open /acct/uid_10081/pid_6190/cgroup.procs: No such file or directory
W/ResourcesManager( 6427): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6427): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6427): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6427): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@125cdb8f, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3c093e1c, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@6842a25, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@8bb67fa, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@36d5a1ab, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@257a2008, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@38f243a1, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3f4809c6, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@39caad87, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@199534b4, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@11ce78dd, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@15aafc52, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@c1a9b23, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@22aae820, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3e3ec5d9, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3fd88b9e, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3f1c67f, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@1da6664c, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@3dcce695, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2abdc3aa, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3e64b9b, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@28f99b38, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@4e25711, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@330c7076, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@37d40677, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@164932e4, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@b04534d, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@3cc71e02, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3789313, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@ad89950, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@cfd749, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@378d184e, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@3ecf4d6f, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3ab5fa7c, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@29b59f05, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1ba66b5a, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1c2d518b, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2aa64268, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@15762681, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2bcfe326, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@141d7b67, lg_preferences_recent,_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@24d11d14,
D/GeneralPreferenceUtils( 6427): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6427): [init]
,I/Config  ( 6427): LGCalendar ver.4.40.17
I/Config  ( 6427): start check model
I/Config  ( 6427): start check native_ca
I/Config  ( 6427): Config Operator=OPEN, Country=EU
D/Config  ( 6427): [setDefaultValuesToPref]
D/Config  ( 6427): [parseProfiles]
D/ProfilesParser( 6427): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6427): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6427): [updateProfiletoCountryInfo]
D/GeneralPreference( 6427): [checkAndMigrateOldPreference]
,D/AlertReceiver( 6427): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/InitNotificationRingtoneService( 6427): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6427): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/AlertUtils( 6427): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6427): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6427): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6427): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6427): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6427): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6427): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
V/AlarmManager(  951): ELAPSED_WAKEUP set : Alarm{3a1e719d type 2 when 85746 com.android.providers.calendar} when 85746
I/AlertUtils( 6427): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6427): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6427): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6427): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6427): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6427): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6427): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6427): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6427): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6427): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,I/AlertUtils( 6427): set default noti to content://media/internal/audio/media/38
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/InitNotificationRingtoneService( 6427): End InitializeAlertRingtoneService.onHandleIntent
,W/HolidayIntentService( 6427): onHandleIntent
,D/HolidayDataLoader( 6427): readJsonAsset : holiday.json
D/AlertService( 6427): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6427): [updateWidgets] 
D/MonthWidgetProvider( 6427): [onReceive]
D/CalendarWidgetProvider( 6427): [onReceive]
D/CalendarWidgetProvider( 6427): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6427): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WeekWidgetProvider( 6427): [onReceive]
D/CalendarWidgetProvider( 6427): [onReceive]
D/CalendarWidgetProvider( 6427): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6427): [onCreate] mContext.getPackageName() = com.android.calendar
I/ActivityManager(  951): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6456 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/HolidayIntentService( 6427): onHandleIntent:holiday data empty
,W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6456): getAccountsCursor
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6456): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/Gmail   ( 6456): Error finding the version of the Email provider.....
E/Gmail   ( 6456): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6456): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6456): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6456): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6456): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6456): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6456): We do not support migrating this version of the Email provider.
,W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/AudioManager( 5189): getMode name:com.lge.qremote
,I/AudioManager( 5189): getMode name:com.lge.qremote
,I/AudioManager( 5189): getMode name:com.lge.qremote
I/AudioManager( 5189): getMode name:com.lge.qremote
W/ActivityManager(  951): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 6456): Observing account changes for notifications
,I/art     (  951): Explicit concurrent mark sweep GC freed 20110(952KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.374ms total 180.977ms
I/ActivityManager(  951): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6498 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  951): Killing 6243:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 21.947ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 21.312ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.906ms
,W/ActivityManager(  951): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/libprocessgroup(  951): failed to open /acct/uid_10038/pid_6243/cgroup.procs: No such file or directory
I/Gmail   ( 6456): getAccountsCursor
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6498): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CalendarProvider2( 6498): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2d05f069
,D/CalendarProvider2( 6498): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6498): Created com.android.providers.calendar.CalendarAlarmManager@8bb67fa(com.android.providers.calendar.CalendarProvider2@2d05f069)
D/CalendarProviderBroadcastReceiver( 6498): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6498): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6498): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6498): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6498): [getOrCreateCalendarAlarmManager]
D/CalendarProvider2( 6498): [IntentService] Release Lock
,D/CalendarProvider2( 6498): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  951): Killing 6272:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/Gmail   ( 6456): notifyAccountChanged
,W/libprocessgroup(  951): failed to open /acct/uid_10011/pid_6272/cgroup.procs: No such file or directory
I/Gmail   ( 6456): getAccountsCursor
I/Gmail   ( 6456): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6456): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6456): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6456): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6456): getAccountsCursor
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 5137): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5137): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  951): Killing 6295:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  951): failed to open /acct/uid_10023/pid_6295/cgroup.procs: No such file or directory
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ActivityManager(  951): Killing 5883:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  951): failed to open /acct/uid_10061/pid_5883/cgroup.procs: No such file or directory
,W/art     ( 6336): Suspending all threads took: 6.625ms
,V/AlarmManager(  951): RTC_WAKEUP set : Alarm{2554aeb1 type 0 when 1452261072952 com.android.vending} when 1452261072952
,D/Finsky  ( 6378): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  951): android: cancelAsUser(2) by android
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/libc-netbsd( 6378): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6378): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6378): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6378): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 6378): propertyValue:false
D/libc-netbsd( 6378): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6378): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6378): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6378): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/art     ( 6378): Suspending all threads took: 6.185ms
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  951): android: cancelAsUser(2) by android
,I/qtaguid ( 6378): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6378): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6378): untagSocket(41) failed with errno -22
D/Finsky  ( 6378): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  951): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6551 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  951): android: cancelAsUser(2) by android
,W/ResourcesManager( 6551): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6551): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6551): VM with version 2.1.0 has multidex support
I/MultiDex( 6551): install
I/MultiDex( 6551): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6551): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 6378): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6378): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6378): untagSocket(41) failed with errno -22
W/ActivityThread( 6551): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6551): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3aaafaac: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6551): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6551): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6551): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1747): callingUid 10006, callindPid: 1747
,E/MDM     ( 1747): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1747): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1747): com.google.android.gms: cancel(0) by com.google.android.gms
D/LocationInitializer( 5137): Restart initialization of location
D/ChimeraCfgMgr( 6551): Reading stored module config
,W/GCoreFlp( 1747): No location to return for getLastLocation()
W/FusedLocationProvider( 1747): location=null
,D/ChimeraCfgMgr( 6551): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/CAR.SERVICE( 6551): Connecting to CarCallService...
,D/NativeLibraryUtils( 6551): Install completed successfully. count=14 extracted=0
,I/art     ( 6551): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6551): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6378): CheckpointMarkThreadRoots callback created = 0xb056f2f0
D/CAR.SERVICE( 6551): com.google.android.projection.gearhead isn't installed.
,D/AlertService( 6427): Beginning updateAlertNotification
D/CAR.TEL.Service( 6551): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6551): Creating a new PhoneAdapter instance
W/ActivityManager(  951): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6551): setListener: com.google.android.gms.car.dn@15a716b
W/ActivityManager(  951): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6551): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6551): Starting CarCallService with initial phone null
I/art     ( 6378): CheckpointMarkThreadRoots callback created = 0xb056f2d0
D/AlertService( 6427): No fired or scheduled alerts
I/NotificationManager( 6427): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6427): com.android.calendar: cancel(1) by com.android.calendar
,I/NotificationManager( 6427): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6427): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6427): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6427): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6427): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6427): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6427): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6427): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6427): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6427): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6427): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6427): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6427): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6427): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6427): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6427): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6427): com.android.calendar: cancel(18) by com.android.calendar
,I/NotificationManager( 6551): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6427): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6427): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6427): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 6427): No events found starting within 1 week.
,D/CAR.SERVICE( 6551): Package validated; name: com.android.vending
,I/NotificationManager( 6378): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6378): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/GAV2    ( 6456): Thread[GAThread,5,main]: No campaign data found.
,I/CheckinService( 5137): Done disabling old GoogleServicesFramework version
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  951): android: cancelAsUser(2) by android
,I/qtaguid ( 6378): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6378): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6378): untagSocket(41) failed with errno -22
,W/ResourcesManager( 6378): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6378): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6378): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6378): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  951): RTC_WAKEUP set : Alarm{3fa291fb type 0 when 1452261075123 com.android.vending} when 1452261075123
D/DeviceConnectionService( 1747): client connected with version: 8296000
,D/Finsky  ( 6378): [784] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  951): android: cancelAsUser(2) by android
,D/Finsky  ( 6378): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6378): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/libc-netbsd( 6378): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6378): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6378): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6378): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out( 6378): propertyValue:false
I/ActivityManager(  951): Killing 6317:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  951): failed to open /acct/uid_10018/pid_6317/cgroup.procs: No such file or directory
,D/sensors_hal_Time(  951): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  951): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  951): tsOffsetIs: Apps: 93307391843; DSPS: 3156230; Offset : -3023227406
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  951): Killing 6336:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  951): failed to open /acct/uid_10069/pid_6336/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/CAR.SERVICE( 6551): mConnectedToCar = false, abort
,E/ActivityThread( 6551): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@dd516f3 that was originally bound here
E/ActivityThread( 6551): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@dd516f3 that was originally bound here
E/ActivityThread( 6551): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6551): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6551): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6551): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6551): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6551): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6551): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6551): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6551): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6551): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6551): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6551): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6551): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6551): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6551): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6551): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6551): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6551): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6551): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6551): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6551): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6551): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6551): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6551): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3b969eba that was originally bound here
E/ActivityThread( 6551): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3b969eba that was originally bound here
E/ActivityThread( 6551): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6551): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6551): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6551): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6551): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6551): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6551): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6551): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6551): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6551): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6551): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6551): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6551): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6551): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6551): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6551): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6551): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6551): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6551): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6551): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6551): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6551): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  951): Unbind failed: could not find connection for android.os.BinderProxy@3547cc30
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/SQLiteConnectionPool( 5137): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/rmt_storage(  275): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  275): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  275): wakelock acquired: 1, error no: 42
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  275): 
,I/rmt_storage(  275): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  951): RTC_WAKEUP set : Alarm{3583b62e type 0 when 1452261089515 com.android.vending} when 1452261089515
,W/ContextImpl( 3633): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 6378): [775] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6378): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/MusicWidget( 2633): mDelayedStopHandler : unbind
,I/MusicBrowser( 2679): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2679): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2679): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2679): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2679): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2679): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2679): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2679): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  951):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@4e25711com.lge.music.MediaPlaybackService$6@330c7076
,D/MusicBrowser( 2679): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2679): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2679): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2679): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2679): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@39caad87
,I/MusicBrowser( 2679): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2679): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2679): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2679): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2679): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2679): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2679): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2679): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2679): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2679): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2679): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2679): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2679): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2679): reset
,V/MediaPlayer[Native]( 2679): setListener
,V/MediaPlayer[Native]( 2679): disconnect
V/MediaPlayer[Native]( 2679): destructor
V/AudioFlinger(  282): releasing 19 from 2679 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/MediaPlayer[Native]( 2679): disconnect
D/MusicBrowser( 2679): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2679): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2679): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2679): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2679): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2679): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2679): [SmartShareManagerClient] unregisterListener: 936642167
W/SmartShareClient( 2679): [SmartShareManagerClient] unregisterListener invalid listener: 936642167
I/SmartShareClient( 2679): [SmartShareManagerClient] terminate service: 2679/MediaPlaybackService/109324837
E/HomeCloudIF( 2679): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2679): [SmartShareManagerClient] unbindService context:android.app.Application@164932e4
V/CloudHub( 2679): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2679): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2679): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2679): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2679): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  951): Killing 6353:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/CloudHub( 2679): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29988
,W/libprocessgroup(  951): failed to open /acct/uid_10086/pid_6353/cgroup.procs: No such file or directory
,D/sensors_hal_Time(  951): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  951): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  951): tsOffsetIs: Apps: 113308905585; DSPS: 3811640; Offset : -3023241340
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/CloudHub( 2679): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19954
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/charger_monitor(  491): init target 500000
,D/KeyguardUpdateMonitor( 1385): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1817): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1385): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1385): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1385): On Skip Timer : true
D/HeadsetStateMachine( 2063): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1385): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/QCNEJ   ( 1854): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1854): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1817): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1817): Battery Level Remaining: 100%
D/LEDHandler( 1817): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1385): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1385): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/[SystemUI]BatterySaverHandler( 1385): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  951): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  951): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  951): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  951): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  951): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  951): tsOffsetIs: Apps: 133311660422; DSPS: 4467090; Offset : -3023231235
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/PowerManagerServiceEx(  951): acquireWakeLockInternal: lock=2803151, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=951
,D/WeatherService( 2669): 2 : TimeTick Intent has been received, Time(hour:min:sec) 14:52:0
D/WeatherService( 2669): 2 : TimeTick Intent And Screen On
D/WeatherService( 2669): 2 : SDK version : 21
W/ActivityManager(  951): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2669): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2669): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2669): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2669): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2669): 2 : This is isUpdating : false
D/WeatherService( 2669): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2669): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2669): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2669): 2 : Fixed theme : optimus
D/WeatherReflect( 2669): 2 : Map key string is -2
,D/lim     ( 2669): 2 : time = 14:52
I/WeatherReflect( 2669): Model Name : LG-D722
D/WeatherTheme( 2669): 2 : Different view - status_min_formatted : 51 != 52
D/WeatherTheme( 2669): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2669): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
I/[SystemUI]TimeTickManager( 1385): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1385): called onTimeUpdated()
I/[SystemUI]Clock( 1385): called onTimeUpdated()
I/LgeClockWidgetControlView( 1385): called onTimeUpdated()
I/[SystemUI]DateView( 1385): called onTimeUpdated()
I/[SystemUI]DateView( 1385): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1385): handleTimeUpdate
D/Theme   ( 2669): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2669): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2669): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
,D/Weather4x2_optimus( 2669): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2669): forecast size is 0
D/Theme   ( 2669): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2669): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2669): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2669): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2669): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2669): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2669): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2669): url is : null
D/Theme   ( 2669): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2669): 2 : update view, appWidgetId: 2
D/WeatherService( 2669): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 14:52:0
,D/PowerManagerServiceEx(  951): releaseWakeLockInternal: lock=2803151 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1891): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1891): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/CloudHub( 2679): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2679): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  951): ALS enabled for SRE
D/PowerManagerServiceEx(  951): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (27245 ms ago)
,D/qdlights(  951): set_light_backlight: 254
,D/qdlights(  951): set_light_backlight: 251
,D/qdlights(  951): set_light_backlight: 248
,D/qdlights(  951): set_light_backlight: 244
,D/qdlights(  951): set_light_backlight: 241
,D/qdlights(  951): set_light_backlight: 238
,D/qdlights(  951): set_light_backlight: 234
,D/qdlights(  951): set_light_backlight: 231
,D/qdlights(  951): set_light_backlight: 228
,D/qdlights(  951): set_light_backlight: 224
,D/qdlights(  951): set_light_backlight: 221
,D/qdlights(  951): set_light_backlight: 218
,D/qdlights(  951): set_light_backlight: 214
,D/qdlights(  951): set_light_backlight: 211
,D/qdlights(  951): set_light_backlight: 208
,D/qdlights(  951): set_light_backlight: 204
,D/qdlights(  951): set_light_backlight: 201
,D/qdlights(  951): set_light_backlight: 198
,D/qdlights(  951): set_light_backlight: 194
,D/qdlights(  951): set_light_backlight: 191
,D/qdlights(  951): set_light_backlight: 188
,D/qdlights(  951): set_light_backlight: 184
,D/qdlights(  951): set_light_backlight: 181
,D/qdlights(  951): set_light_backlight: 178
,D/qdlights(  951): set_light_backlight: 174
,D/qdlights(  951): set_light_backlight: 171
,D/qdlights(  951): set_light_backlight: 168
,D/qdlights(  951): set_light_backlight: 164
,D/qdlights(  951): set_light_backlight: 161
,D/qdlights(  951): set_light_backlight: 158
,D/qdlights(  951): set_light_backlight: 154
,D/qdlights(  951): set_light_backlight: 151
,D/qdlights(  951): set_light_backlight: 148
,D/qdlights(  951): set_light_backlight: 144
,D/qdlights(  951): set_light_backlight: 141
,D/qdlights(  951): set_light_backlight: 138
,D/qdlights(  951): set_light_backlight: 134
,D/qdlights(  951): set_light_backlight: 131
,D/qdlights(  951): set_light_backlight: 128
,D/qdlights(  951): set_light_backlight: 124
,D/qdlights(  951): set_light_backlight: 121
,D/qdlights(  951): set_light_backlight: 118
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,D/qdlights(  951): set_light_backlight: 114
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdlights(  951): set_light_backlight: 111
,D/qdlights(  951): set_light_backlight: 108
,D/qdlights(  951): set_light_backlight: 104
,D/qdlights(  951): set_light_backlight: 101
,D/qdlights(  951): set_light_backlight: 98
,D/qdlights(  951): set_light_backlight: 94
,D/qdlights(  951): set_light_backlight: 91
,D/qdlights(  951): set_light_backlight: 88
,D/qdlights(  951): set_light_backlight: 84
,D/qdlights(  951): set_light_backlight: 81
,D/qdlights(  951): set_light_backlight: 78
,D/qdlights(  951): set_light_backlight: 74
,D/qdlights(  951): set_light_backlight: 71
,D/qdlights(  951): set_light_backlight: 68
,D/qdlights(  951): set_light_backlight: 64
,D/qdlights(  951): set_light_backlight: 61
,D/qdlights(  951): set_light_backlight: 58
,D/qdlights(  951): set_light_backlight: 54
,D/qdlights(  951): set_light_backlight: 51
,D/qdlights(  951): set_light_backlight: 48
,D/qdlights(  951): set_light_backlight: 44
,D/qdlights(  951): set_light_backlight: 41
,D/qdlights(  951): set_light_backlight: 38
,D/qdlights(  951): set_light_backlight: 34
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
D/qdlights(  951): set_light_backlight: 31
,D/qdlights(  951): set_light_backlight: 28
,D/qdlights(  951): set_light_backlight: 24
,D/qdlights(  951): set_light_backlight: 21
,D/qdlights(  951): set_light_backlight: 18
,D/qdlights(  951): set_light_backlight: 14
,D/qdlights(  951): set_light_backlight: 11
,D/qdlights(  951): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  951): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  951): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  951): tsOffsetIs: Apps: 153313159841; DSPS: 5122499; Offset : -3023226943
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  951): ALS enabled for SRE
D/PowerManagerServiceEx(  951): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (34236 ms ago)
I/PowerManagerService(  951): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  951): ALS enabled for SRE
,D/PowerManagerServiceEx(  951): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (34253 ms ago)
W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  951): Sleeping (uid 1000)...
D/LPWGController(  951): [updateScreenState] screen on = false
D/LPWGController(  951): disable proximity sensor
D/LPWGController(  951): enable proximity sensor
,I/SensorManager(  951): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@27957b5c] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  951): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  951): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  951): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  951): activate: handle is 48, enable
V/sensors_hal_Ctx(  951): activate sensors is 1400000000000
D/sensors_hal_Thresh(  951): enable: handle=48
I/sensors_hal_SAM(  951): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  951): waitForResponse: timeout=1000
V/sensors_hal_SAM(  951): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  951): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  951): enable: Received response: 0
D/PowerManagerServiceEx(  951): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (34288 ms ago)
I/Adreno-EGL(  951): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  951): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  951): Build Date: 03/02/15 Mon
I/Adreno-EGL(  951): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  951): Remote Branch: 
I/Adreno-EGL(  951): Local Patches: 
I/Adreno-EGL(  951): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (157 us)
,I/Sensors (  427): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  951): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  951): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  951): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  951): processInd: handle 48, count=1
V/sensors_hal_Thresh(  951): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  951): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  951): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  951): poll: count: 256
I/sensors_hal_Ctx(  951): poll: released wakelock sensor_ind
D/sensors_hal_Util(  951): waitForResponse: timeout=0
D/LPWGController(  951): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  951): current mode = 1  value = 1 1
I/LPWGController(  951): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
,I/LPWGController(  951): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  951): set_light_backlight: 0
,I/SensorManager(  951): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  951): activate: handle is 46, disable
V/sensors_hal_Ctx(  951): activate sensors is 1000000000000
D/sensors_hal_LP2(  951): enable: handle=46
D/sensors_hal_LP2(  951): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  951): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
V/sensors_hal_SAM(  951): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  951): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
I/DisplayManagerService(  951): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  951): Display changed displayId=0
,D/DSDPConnection( 1765): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  951): Excessive delay in setPowerMode(): 178ms
I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  951): Got set_interactive hint
D/KeyguardViewMediator( 1385): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1344): onScreenTurnedOff(3)
I/[LGHome]EVENT( 1891): [Launcher.java:986:onPause()]onPause
,D/KeyguardViewMediator( 1385): notifyScreenOffLocked
D/KeyguardViewMediator( 1385): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1385): handleNotifyScreenOff
D/SmartCoverViewMediator( 1344): notifyScreenOffLocked
D/SmartCoverViewMediator( 1344): handleNotifyScreenOFF
I/[LGHome]EVENT( 1891): [Launcher.java:5214:onStop()]onStop
,D/WifiServerServiceExt(  951): sendKtScanInterval  mRtspPlay : false
,I/WifiServerServiceExt(  951): set CMD_KT_SCAN_INTERVAL
V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=on, calling pid 951
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
V/voice   (  282): voice_set_parameters: enter: screen_state=on
I/HotwordDetector( 1978): Closing mic
I/MicrophoneInputStream( 1978): mic_close com.google.android.apps.gsa.speech.audio.u@307eae1d
V/AudioRecord( 1978): stop()
D/AudioRecord( 1978): AudioRecord->stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: exit
V/voice   (  282): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  282): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  282): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  282): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  282): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  282): adev_set_parameters: exit with code(0)
D/ScreenTurnOffBySensor( 1385): unregisterProximitySensor
V/AudioFlinger(  282): Record stopped OK
,V/AudioPolicyManager(  282): stopInput() input 24
V/AudioPolicyService(  282): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  282): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch handle 25
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  282): ThreadBase::setParameters() routing=0
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb42a4000
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
D/StatusBarWindowView( 1385): onScreenTurnedOff why = 3
D/KeyguardUpdateMonitor( 1385): handleTimeUpdate
,V/audio_hw_primary(  282): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  282): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  282): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  282): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  282): disable_audio_route: exit
,E/audio_hw_primary(  282): disable_snd_device: enter 144
D/hardware_info(  282): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  282): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  282): stop_input_stream: exit: status(0)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioFlinger(  282): RecordThread: loop stopping
,V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  282): removeAudioPatch() handle 20 af handle 25
V/AudioPolicyService(  282): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  282): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyService(  282): AudioCommandThread() adding set parameter string hotword_active=0, io 24 ,delay 0
V/AudioPolicyService(  282): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing set parameters string hotword_active=0, io 24
V/AudioFlinger(  282): setParameters(): io 24, keyvalue hotword_active=0, calling pid 282
V/AudioFlinger(  282): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb42a4000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioRecord( 1978): stop()
V/AudioRecord( 1978): stop()
V/AudioRecord( 1978): stop()
V/AudioFlinger(  282): releasing 23 from 1978 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioPolicyManager(  282): releaseInput() 24
V/AudioPolicyManager(  282): closeInput(24)
V/AudioFlinger(  282): closeInput() 24
V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 24
V/AudioFlinger(  282): ThreadBase::exit
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): RecordThread 0xb42a4000 exiting
I/HotwordRecognitionRnr( 1978): Hotword detection finished
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioSystem( 1385): ioConfigChanged() event 4, ioHandle 24
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioFlinger(  282): removeClient_l() pid 1978, calling pid 282
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioSystem( 1765): ioConfigChanged() event 4, ioHandle 24
I/HotwordRecognitionRnr( 1978): Stopping hotword detection.
V/AudioSystem( 2063): ioConfigChanged() event 4, ioHandle 24
V/AudioSystem(  951): ioConfigChanged() event 4, ioHandle 24
V/AudioSystem( 2679): ioConfigChanged() event 4, ioHandle 24
V/AudioSystem( 1978): ioConfigChanged() event 4, ioHandle 24
V/AudioSystem( 3160): ioConfigChanged() event 4, ioHandle 24
,D/GpsLocationProvider(  951): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1385): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1854): |CORE| sendScreenState: state:true
I/LEDService( 1817): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1817): stopPatternFlashing()
D/qdlights( 1817): set_light_notifications: 0,0,0,0,3
I/LEDService( 1817): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1817): set_light_notifications: 0,0,0,0,3
I/LEDService( 1817): updateLightsLocked : turn off led
D/qdlights( 1817): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1817): RESTART MSG
,D/SplitWindow(  951): check instance of lgWin Window{2637efeb u0 SearchPanel}
,I/Cliptray Service( 1817): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/Cliptray Service( 1817): lockStatus = 0
D/LNfcService( 1800): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1800): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1800): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1800): isRequireNfcCRouting() return true
D/LNfcService( 1800): isHCERoutingtoHost() return : true
D/NfcService( 1800): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1800): mEnableLPD: true
D/NfcService( 1800): mEnableReader: false
D/NfcService( 1800): mEnableHostRouting: true
D/NfcService( 1800): newParams.techmask= mTechMask: default
D/NfcService( 1800): mEnableLPD: true
D/NfcService( 1800): mEnableReader: false
D/NfcService( 1800): mEnableHostRouting: true
D/NfcService( 1800): screenState= 3
D/NfcService( 1800): Discovery configuration equal, not updating.
,D/InputDispatcher(  951): Window went away: Window{90225b6 u0 SearchPanel}
I/[SystemUI]Clock( 1385): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1385): time changed, timezoneChanged : false
,D/Ulp_jni (  951): JNI:system_update. Event-0
,V/PhoneApp( 1765): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2669): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:52:19
D/WeatherService( 2669): 2 : ACTION screen on
D/WeatherService( 2669): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2669): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2669): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:52:19
,W/Settings(  951): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  951): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  951): ACTION_SCREEN_ON
D/AppCleanupService( 4146): android.intent.action.SCREEN_ON
,V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=off, calling pid 951
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=off
V/voice   (  282): voice_set_parameters: enter: screen_state=off
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: exit
V/voice   (  282): voice_set_parameters: exit with code(0)
,V/msm8974_platform_lge(  282): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  282): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  282): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  282): adev_set_parameters: exit with code(0)
D/WifiController(  951): CMD_SCREEN_OFF 
D/WifiController(  951): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  951): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1385): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1854): |CORE| sendScreenState: state:false
,I/LEDService( 1817): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1817): stopPatternFlashing()
D/qdlights( 1817): set_light_notifications: 0,0,0,0,3
,I/LEDService( 1817): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1817): set_light_notifications: 0,0,0,0,3
I/LEDService( 1817): updateLightsLocked : turn on led
E/LEDService( 1817): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1817): Can't handle this request of patternId:0
D/LEDHandler( 1817): RESTART MSG
D/VolumeVibrator( 1817): clear
I/Cliptray Service( 1817): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/LNfcService( 1800): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1800): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1891): [Launcher.java:1711:onReceive()]Screen Off
,W/ActivityManager(  951): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
,I/Sensors (  427): sns_pwr.c(301):releasing wakelock
,V/PhoneApp( 1765): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
D/WeatherService( 2669): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:52:19
D/WeatherService( 2669): 2 : ACTION screen off
D/WeatherService( 2669): 2 : TimeTick Receiver Unregister
D/WeatherService( 2669): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:52:19
W/Settings(  951): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  951): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  951): ACTION_SCREEN_OFF
D/AppCleanupService( 4146): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4146): AppUsageStatsSaveTask
E/NxpNfcJni( 1800): getReconnectState = 0x0
,D/LCardEmulationManager( 1800): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1800): getDefaultRoute
D/LNfcService( 1800): isRequireNfcCRouting() return true
D/LNfcService( 1800): isHCERoutingtoHost() return : true
D/NfcService( 1800): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1800): mEnableLPD: true
D/NfcService( 1800): mEnableReader: false
D/NfcService( 1800): mEnableHostRouting: true
D/NfcService( 1800): newParams.techmask= mTechMask: 0
D/NfcService( 1800): mEnableLPD: true
D/NfcService( 1800): mEnableReader: false
D/NfcService( 1800): mEnableHostRouting: true
D/NfcService( 1800): screenState= 1
E/NxpNfcJni( 1800): getReconnectState = 0x0
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  951): ELAPSED_WAKEUP set : Alarm{bacf148 type 2 when 160117 com.android.systemui} when 160117
,D/KeyguardViewMediator( 1385): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1765): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1765): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1765): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1765): getCallState : 0
,D/PhoneUtils( 1765): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1765): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1765): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1385): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1385): doKeyguard: not showing because lockscreen is off
D/charger_monitor(  491): init target 500000
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1817): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1385): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1385): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1385): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1385): On Skip Timer : true
D/HeadsetStateMachine( 2063): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1854): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1854): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1385): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1385): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1385): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
D/LEDHandler( 1817): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1817): Battery Level Remaining: 100%
D/LEDHandler( 1817): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1385): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  951): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  951): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  951): battery changed pluggedType: 2
D/HeadsetStateMachine( 2063): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1385): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1385): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1385): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
I/QCNEJ   ( 1854): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1854): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1817): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1817): Battery Level Remaining: 100%
D/LEDHandler( 1817): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1385): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  951): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  951): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  951): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  951): ELAPSED_WAKEUP set : Alarm{fd6dbe1 type 2 when 137548 com.google.android.gms} when 137548
V/AlarmManager(  951): ELAPSED_WAKEUP set : Alarm{26805d06 type 2 when 165386 android} when 165386
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1747): Vacuum at: now=1452261148984 tag=VacuumService
,I/art     (  951): Explicit concurrent mark sweep GC freed 44578(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 1.863ms total 162.481ms
,I/PhenotypeConfigurator( 1747): Scheduling Phenotype for one-off execution 8241 seconds from now (1452261149550)
,D/GetConfigurationSnapshotOperation( 1747): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1747): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1747): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  951): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 1747): propertyValue:false
,D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  951): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1747): Explicit concurrent mark sweep GC freed 89104(5MB) AllocSpace objects, 35(583KB) LOS objects, 39% free, 15MB/25MB, paused 2.789ms total 160.140ms
,D/LocationManagerService(  951): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  951): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  951): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  951): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  951): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  951): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  951): tsOffsetIs: Apps: 173315092902; DSPS: 5777923; Offset : -3023247267
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  951): ELAPSED_WAKEUP set : Alarm{3444aa9a type 2 when 186020 com.google.android.gms} when 186020
,D/charger_monitor(  491): init target 500000
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1385): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1385): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1385): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1385): On Skip Timer : true
D/PowerService( 1817): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2063): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1385): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1385): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1385): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
I/QCNEJ   ( 1854): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1854): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1817): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1817): Battery Level Remaining: 100%
D/LEDHandler( 1817): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
W/Settings(  951): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  951): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  951): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1385): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  951): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  951): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  951): tsOffsetIs: Apps: 193317380744; DSPS: 6433358; Offset : -3023248270
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ClearcutLoggerApiImpl( 1747): disconnect managed GoogleApiClient
,I/[SystemUI]TimeTickManager( 1385): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1385): called onTimeUpdated()
I/[SystemUI]Clock( 1385): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1385): called onTimeUpdated()
I/[SystemUI]DateView( 1385): called onTimeUpdated()
I/[SystemUI]DateView( 1385): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1385): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  951): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  951): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  951): tsOffsetIs: Apps: 213319598434; DSPS: 7088794; Offset : -3023349681
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,TIME-OUT KILL (timeout was 150000ms),D/AndroidRuntime( 6769): 
D/AndroidRuntime( 6769): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6769): CheckJNI is OFF
D/AndroidRuntime( 6769): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  951): Force stopping com.example.hello appid=10317 user=-1: uninstall pkg
W/PackageSettings(  951): Skipping PackageSetting{a49efc com.test.thalitest/10316} due to missing metadata
I/ActivityManager(  951): Force stopping com.example.hello appid=10317 user=0: pkg removed
I/art     ( 1891): Explicit concurrent mark sweep GC freed 12637(675KB) AllocSpace objects, 8(7MB) LOS objects, 39% free, 15MB/26MB, paused 1.519ms total 86.523ms
D/KeyguardModel( 1385): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1891): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1891): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1891): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/InputReader(  951): Reconfiguring input devices.  changes=0x00000010
I/art     ( 5137): Explicit concurrent mark sweep GC freed 3510(200KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 13MB/17MB, paused 1.039ms total 109.639ms
W/GeofencerStateMachine( 1747): Ignoring removeGeofence because network location is disabled.
I/QCNEJ   ( 1854): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/System.err( 3633): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 3633): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3633): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3633): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3633): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3633): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3633): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3633): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3633): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3633): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3633): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3633): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/art     ( 1978): Explicit concurrent mark sweep GC freed 24310(1743KB) AllocSpace objects, 1(625KB) LOS objects, 39% free, 12MB/21MB, paused 6.657ms total 129.901ms
I/ActivityManager(  951): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6798 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  951): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=6813 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/art     (  951): Explicit concurrent mark sweep GC freed 20193(1303KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.372ms total 260.187ms
I/art     (  951): WaitForGcToComplete blocked for 25.826ms for cause Explicit
I/[SystemUI]QSlideListController( 1385): onReceive = android.intent.action.PACKAGE_REMOVED
D/administrator(  951): Handling package changes for user 0
W/ResourcesManager( 6798): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6798): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6798): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LockScreenSettings( 6813): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/KeyguardModel( 1385): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1385): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1385): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1385): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1385): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1385): createShortcutInfo...
W/ResourceType( 1385): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1385): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/NotificationService(  951): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  951): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/KeyguardModel( 1385): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1385): createShortcutInfo...
W/ResourceType( 1385): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1385): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/JobSchedulerService(  951): Receieved: android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1385): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1385): createShortcutInfo...
W/ResourceType( 1385): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1385): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1385): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1385): createShortcutInfo...
D/TaskPersister(  951): removeObsoleteFile: deleting file=220_task.xml
D/KeyguardModel( 1385): handleShortcutListChanged...
D/KeyguardModel( 1385): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1385): createShortcutInfo...
D/KeyguardModel( 1385): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1385): createShortcutInfo...
W/ResourceType( 1385): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1385): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1385): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1385): createShortcutInfo...
W/ResourceType( 1385): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1385): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1385): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1385): createShortcutInfo...
W/ResourceType( 1385): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1385): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1385): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1385): createShortcutInfo...
I/ActivityManager(  951): Killing 6427:com.android.calendar/u0a13 (adj 15): empty #11
D/KeyguardModel( 1385): handleShortcutListChanged...
W/libprocessgroup(  951): failed to open /acct/uid_10013/pid_6427/cgroup.procs: No such file or directory
I/LGEmail ( 6798): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/art     (  951): Explicit concurrent mark sweep GC freed 4764(250KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 7.494ms total 277.162ms
D/LGEmail ( 6798): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/AndroidRuntime( 6769): Shutting down VM
I/PackageChangeReceiver( 6798): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager(  951): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6839 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  951): Killing 5923:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 5189): android.os.DeadObjectException
W/System.err( 5189): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5189): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5189): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5189): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5189): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5189): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5189): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5189): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5189): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5189): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5189): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5189): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5189): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5189): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5189): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5189): android.os.DeadObjectException
W/System.err( 5189): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5189): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5189): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5189): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5189): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5189): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5189): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5189): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5189): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5189): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5189): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5189): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5189): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5189): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5189): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/ResourcesManager(  951): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType(  951): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/libprocessgroup(  951): failed to open /acct/uid_10089/pid_5923/cgroup.procs: No such file or directory
W/ActivityManager(  951): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
D/LCardEmulationManager( 1800): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1800): getDefaultRoute
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
I/AppUp4:AppBoxCP( 6839): onCreate
W/AppUp4:DB( 6839):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6839):  setFingerPrint start
I/AppUp4:DB( 6839):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/ActivityManager(  951): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6862 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AppUp4:DB( 6839):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6839):  SDK version = 0
I/AppUp4:DB( 6839):  beforefinger == newfinger no write in DB
I/[LGHome]EVENT( 1891): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/AppUp4:AppBoxApplication( 6839): AppBoxApplication onCreate()
E/SQLiteLog( 6839): (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
E/SQLiteDatabase( 6839): Error inserting package=com.example.hello
E/SQLiteDatabase( 6839): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 6839): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6839): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:790)
E/SQLiteDatabase( 6839): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 6839): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6839): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1581)
E/SQLiteDatabase( 6839): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1451)
E/SQLiteDatabase( 6839): 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
E/SQLiteDatabase( 6839): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 6839): 	at android.content.ContentResolver.insert(ContentResolver.java:1267)
E/SQLiteDatabase( 6839): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
E/SQLiteDatabase( 6839): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
E/SQLiteDatabase( 6839): 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
E/SQLiteDatabase( 6839): 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
E/SQLiteDatabase( 6839): 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
E/SQLiteDatabase( 6839): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/SQLiteDatabase( 6839): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/SQLiteDatabase( 6839): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/SQLiteDatabase( 6839): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6839): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6839): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 6839): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6839): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6839): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 6839): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6862): Failed while opening the log file.
E/UEI.SmartControl( 6862): java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.lite/app_log/app.log: open failed: EROFS (Read-only file system)
E/UEI.SmartControl( 6862): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/UEI.SmartControl( 6862): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/UEI.SmartControl( 6862): 	at java.io.FileWriter.<init>(FileWriter.java:58)
E/UEI.SmartControl( 6862): 	at com.uei.f.c.a(Unknown Source)
E/UEI.SmartControl( 6862): 	at com.uei.f.c.a(Unknown Source)
E/UEI.SmartControl( 6862): 	at com.uei.f.c.<init>(Unknown Source)
E/UEI.SmartControl( 6862): 	at com.uei.f.c.a(Unknown Source)
E/UEI.SmartControl( 6862): 	at com.uei.control.core.QSApp.onCreate(Unknown Source)
E/UEI.SmartControl( 6862): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1011)
E/UEI.SmartControl( 6862): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4657)
E/UEI.SmartControl( 6862): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/UEI.SmartControl( 6862): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/UEI.SmartControl( 6862): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UEI.SmartControl( 6862): 	at android.os.Looper.loop(Looper.java:135)
E/UEI.SmartControl( 6862): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/UEI.SmartControl( 6862): 	at java.lang.reflect.Method.invoke(Native Method)
E/UEI.SmartControl( 6862): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/UEI.SmartControl( 6862): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/UEI.SmartControl( 6862): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6862): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/UEI.SmartControl( 6862): 	at libcore.io.Posix.open(Native Method)
E/UEI.SmartControl( 6862): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/UEI.SmartControl( 6862): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/UEI.SmartControl( 6862): 	... 18 more
D/UEI.SmartControl( 6862): Quickset Services start...
I/UEI.SmartControl( 6862): Manufacture = LGE
D/UEI.SmartControl( 6862): File observer start...

```
