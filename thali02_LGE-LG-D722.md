#### Test 61703351ed386f4_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
E/PhoneInterfaceManager( 1782): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
E/USB_UICC(  292): Timeout! No signal received. Retry num = 30
E/USB_UICC(  292): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  292): usb_uicc_init_qmi failed ! 
I/USB_UICC(  292): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  292): usb_uicc_cleanup, Issuing QMI deinit ... 
,--------- beginning of system
I/ActivityManager(  853): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3042 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  853): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=3061 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  853): Killing 2251:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 25.574ms
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 22.052ms
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 23.175ms
D/AndroidRuntime( 3059): 
D/AndroidRuntime( 3059): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3059): CheckJNI is OFF
W/libprocessgroup(  853): failed to open /acct/uid_10079/pid_2251/cgroup.procs: No such file or directory
I/ActivityManager(  853): Killing 2437:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10069/pid_2437/cgroup.procs: No such file or directory
D/LGDMClient( 3061): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.SIM_STATE_CHANGED
D/LGDMClient( 3061): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3061): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:86 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
E/LGDMClient( 3061): [DmServiceProcessor.java] [onHandleIntent()] : [153] : Received SIM_STATE_CHANGED
I/ActivityManager(  853): Start proc com.lge.appbox.client:SingleBinaryService for broadcast com.lge.appbox.client/com.lge.appbox.singlebinary.SimChangeReceiver: pid=3097 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/AndroidRuntime( 3059): Calling main entry com.android.commands.am.Am
V/AudioFlinger(  281): thread 0xb56eb000 type 0 TID 1293 going to sleep
I/ActivityManager(  853): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/AudioFlinger(  281): thread 0xb5651000 type 0 TID 1292 going to sleep
V/AudioFlinger(  281): thread 0xb5735000 type 0 TID 1295 going to sleep
D/ActivityManager(  853): setTaskToReturnTo : TaskRecord{1f0dd102 #224 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  853): setTaskToReturnTo : TaskRecord{1f0dd102 #224 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  853): AppWindowTokenEx init.. 
D/ContextHelper(  853): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/InputDispatcher(  853): Focus left window: Window{17cf33bd u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 1907): [Launcher.java:986:onPause()]onPause
D/AndroidRuntime( 3059): Shutting down VM
D/SplitWindow(  853): check instance of lgWin Window{2c4f157c u0 Starting com.example.hello}
I/ActivityManager(  853): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3116 uid=10317 gids={50317, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1907): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1907): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1970): Closing mic
I/MicrophoneInputStream( 1970): mic_close com.google.android.apps.gsa.speech.audio.u@35254745
V/AudioRecord( 1970): stop()
D/AudioRecord( 1970): AudioRecord->stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioFlinger(  281): Record stopped OK
V/AudioPolicyManager(  281): stopInput() input 17
V/AudioPolicyService(  281): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  281): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  281): ThreadBase::setParameters() routing=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3855000
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
I/WindowStateAnimator(  853): Starting window displayed
I/SystemUI[Framework](  853): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
W/PhoneWindowManagerEx(  853): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  853): setLGSystemUiVisibility(0x0)
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
D/StatusBarManagerServiceEx(  853): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@38ca66c8,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1369): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1369):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1369): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1369): draw background and invalidate : color = 5000000
D/BarTransitions( 1369): draw background and invalidate : color = 5040404
V/audio_hw_primary(  281): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  281): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  281): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  281): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  281): disable_audio_route: exit
E/audio_hw_primary(  281): disable_snd_device: enter 144
D/hardware_info(  281): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  281): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  281): stop_input_stream: exit: status(0)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyManager(  281): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  281): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  281): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  281): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  281): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  281): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  281): setParameters(): io 17, keyvalue hotword_active=0, calling pid 281
V/AudioFlinger(  281): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  281): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  281): in_set_parameters: exit: status(0)
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3855000
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioRecord( 1970): stop()
V/AudioRecord( 1970): stop()
V/AudioRecord( 1970): stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioPolicyManager(  281): releaseInput() 17
V/AudioPolicyManager(  281): closeInput(17)
V/AudioFlinger(  281): closeInput() 17
V/AudioSystem(  281): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): ThreadBase::exit
V/AudioSystem( 1970): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioSystem( 1369): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): RecordThread 0xb3855000 exiting
V/AudioSystem(  853): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2748): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1782): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  281): adev_close_input_stream: enter:stream_handle(0xb546e420)
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioPolicyService(  281): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  281): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  281): releaseInput() exit
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioFlinger(  281): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  281): AudioCommandThread() processing update audio port list
V/AudioFlinger(  281): removeClient_l() pid 1970, calling pid 281
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioFlinger(  281): releasing 16 from 1970 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
I/HotwordRecognitionRnr( 1970): Hotword detection finished
I/HotwordRecognitionRnr( 1970): Stopping hotword detection.
D/ContextHelper( 3116): convertTheme. context->name=com.example.hello themeResourceId=16973833
,D/AppUp4:AppBoxApplication( 3097): AppBoxApplication onCreate()
,D/AppUp4:SingleBinary( 3097): /cust/OPEN_EU/config/app-enabled-conf.json is selected!!
,D/AppUp4:SingleBinary( 3097):  Starting isFingerChanged 
I/WebViewFactory( 3116): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/ActivityManager(  853): Start proc com.lge.appbox.client for content provider com.lge.appbox.client/com.lge.appbox.databases.AppBoxContentProvider: pid=3139 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/LibraryLoader( 3116): Time to load native libraries: 9 ms (timestamps 3335-3344)
I/LibraryLoader( 3116): Expected native library version number "",actual native library version number ""
I/AppUp4:AppBoxCP( 3139): onCreate
,W/AppUp4:DB( 3139):  [AppBoxDatabaseHelper] construct
V/WebViewChromiumFactoryProvider( 3116): Binding Chromium to main looper Looper (main, tid 1) {208cd236}
I/LibraryLoader( 3116): Expected native library version number "",actual native library version number ""
I/chromium( 3116): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/AppUp4:DB( 3139):  setFingerPrint start
,I/AppUp4:DB( 3139):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 3139):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 3139):  SDK version = 0
I/AppUp4:DB( 3139):  beforefinger == newfinger no write in DB
I/BrowserStartupController( 3116): Initializing chromium process, singleProcess=true
D/AppUp4:AppBoxApplication( 3139): AppBoxApplication onCreate()
W/art     ( 3116): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3116): ApplicationContext is null in ApplicationStatus
D/AppUp4:SingleBinary( 3097):  The value of isFingerChanged null
D/AppUp4:SingleBinary( 3097): Device : jagnm
,D/AppUp4:SingleBinary( 3097): SIM state : ABSENT
W/chromium( 3116): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
D/AppUp4:NTCodeSingleBinary( 3097): Starting isFingerChanged 
W/chromium( 3116): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,D/AppUp4:NTCodeSingleBinary( 3097): The value of isFingerChanged lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
D/AppUp4:SingleBinary( 3097): Device : jagnm
D/AppUp4:SingleBinary( 3097): Config file is not exist - nothing
I/ActivityManager(  853): Killing 1925:com.android.printspooler/u0a87 (adj 15): empty #11
E/libEGL  ( 3116): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3116): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3116): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3116): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 3116): Build Date: 03/02/15 Mon
I/Adreno-EGL( 3116): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 3116): Remote Branch: 
I/Adreno-EGL( 3116): Local Patches: 
I/Adreno-EGL( 3116): Reconstruct Branch: 
W/libprocessgroup(  853): failed to open /acct/uid_10087/pid_1925/cgroup.procs: No such file or directory
,D/AppUp4:CustSimReflector( 3139): SimReflector getInstance.
I/AppUp4:CustSimReflector( 3139): sSimClass is invoked by TelephonyManager
I/AppUp4:CustSimReflector( 3139): sSubscriptionClass is invoked by SubscriptionManager
I/AppUp4:CustSimReflector( 3139): sSimInstance : android.telephony.TelephonyManager@30b136f8
I/AppUp4:CustSimReflector( 3139): sIsMultiSimEnabled : false
I/AppUp4:CustSimReflector( 3139): sSIMCount : 1
W/AppUp4:CustSimStateReceiver( 3139): onReceive ss : ABSENT
,W/AppUp4:CustSimStateReceiver( 3139): Invalid cust ss : ABSENT
V/AudioPolicyService(  281): registerClient() client 0xb4027880, uid 10317
D/BluetoothManagerService(  853): Message: 20
D/BluetoothManagerService(  853): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1213d3fe:true
,D/BluetoothAdapter( 3116): 810409427: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  853): Start proc com.android.browser for broadcast com.android.browser/com.lge.browser.settings.BrowserSettingReceiver: pid=3174 uid=10012 gids={50012, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 2395:com.android.settings/1000 (adj 15): empty #11
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_2395/cgroup.procs: No such file or directory
W/ResourcesManager( 3174): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.android.browser/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3174): Failed to ensure directory: /storage/external_SD/Android/data/com.android.browser/files
V/browser ( 3174): Browser.onCreate: this=com.android.browser.Browser@360427d1
W/art     ( 3116): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3116): onDetachedFromWindow called when already detached. Ignoring
I/LibraryLoader( 3174): Loading: sweskia
D/SystemWebViewEngine( 3116): CordovaWebView is running on device made by: LGE
W/art     ( 3116): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3116): Attempt to remove local handle scope entry from IRT, ignoring
I/LibraryLoader( 3174): Loading: lgewebviewchromium
D/SimInfo ( 3174): FlexData mcc/mnc is null 
D/BRS_AUTOPROP( 3174): getOperatorConfig bookmarkOption : DEFAULT
I/BRS_AUTOPROP( 3174): Profile name :profiles/Browser_DEFAULT_EU_OPEN.xml
I/AUTOPROP( 3174): [UI4.1] Search [profiles/Browser_DEFAULT_EU_OPEN.xml]
I/BRS_AUTOPROP( 3174): readProfile() START [depth] 3[type]=2
I/BRS_AUTOPROP( 3174): [READ_ONLY]=0
I/BRS_AUTOPROP( 3174): readProfile() END [depth] 2[type]=3
I/AUTOPROP( 3174): [FIND] Common profile
I/AUTOPROP( 3174): parsing Score [currentScore] =0[parsingScore] = -1[candidateSocre] = -1
I/AUTOPROP( 3174): Duration of Profile parsing = 34
D/BRS_AUTOPROP( 3174): getOperatorConfig bookmarkOption : DEFAULT
I/BRS_AUTOPROP( 3174): getDefaultProfileName = profiles/Browser_DEFAULT_EU_OPEN.xml
I/AUTOPROP( 3174): [UI4.1] Search [profiles/Browser_DEFAULT_EU_OPEN.xml]
I/BRS_AUTOPROP( 3174): readProfile() START [depth] 3[type]=2
I/BRS_AUTOPROP( 3174): [READ_ONLY]=0
I/BRS_AUTOPROP( 3174): readProfile() END [depth] 2[type]=3
I/AUTOPROP( 3174): [FIND] Common profile
I/Activity( 3116): Activity.onPostResume() called 
D/OpenGLRenderer( 3116): Render dirty regions requested: true
I/OpenGLRenderer( 3116): Initialized EGL, version 1.4
D/OpenGLRenderer( 3116): Enabling debug mode 0
I/AUTOPROP( 3174): parsing Score [currentScore] =0[parsingScore] = -1[candidateSocre] = -1
I/AUTOPROP( 3174): Duration of Profile parsing = 25
D/Atlas   ( 3116): Validating map...
D/SplitWindow(  853): check instance of lgWin Window{3330564f u0 com.example.hello/com.example.hello.MainActivity}
W/chromium( 3116): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/InputDispatcher(  853): Focus entered window: Window{3330564f u0 com.example.hello/com.example.hello.MainActivity}
W/InputMethodManagerService(  853): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/ActivityManager(  853): Displayed com.example.hello/.MainActivity: +1s129ms
I/Timeline(  853): Timeline: Activity_windows_visible id: ActivityRecord{181cca13 u0 com.example.hello/.MainActivity t224} time:44110
I/Timeline( 3116): Timeline: Activity_idle id: android.os.BinderProxy@cd6b972 time:44118
,I/LibraryLoader( 3174): Time to load native libraries: 338 ms (timestamps 1550-1888)
,I/LibraryLoader( 3174): Expected native library version number "",actual native library version number ""
I/BrowserSettingReceiver( 3174): [SIM EVENT]ACTION_SIM_STATE_CHANGED simID :0 state :ABSENT
I/ActivityManager(  853): Killing 2837:android.process.media/u0a19 (adj 15): empty #11
W/BindingManager( 3116): Cannot call determinedVisibility() - never saw a connection for the pid: 3116
,I/chromium( 3116): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/ActivityManager(  853): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3209 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 3002} abi=armeabi-v7a
W/libprocessgroup(  853): failed to open /acct/uid_10019/pid_2837/cgroup.procs: No such file or directory
,W/ResourcesManager( 3209): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3209): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,D/JsMessageQueue( 3116): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 3116): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/ConversationSkinProvider( 3209): skin provider oncreate
,I/JoynPreferenceProvider( 3209): joyn preference provider oncreate
E/ActivityThread( 3209): Failed to find provider info for com.lge.ims.rcs
,E/ActivityThread( 3209): Failed to find provider info for com.lge.ims.rcs
E/[MMS]   ( 3209): MmsSettings: [LGE] MmsSettings.initializeMmsSettings()
,E/[MMS]   ( 3209): MmsSettings: [LGE]loadXMLSettings() ++++++++++ >> Load default:false
I/[MMS]   ( 3209): MmsSettings: [LGE]loadXMLSettings() SIM(current) information
I/[MMS]   ( 3209): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 3209): MmsSettings: [LGE]loadXMLSettings() [Build] Country:EU, Operator:OPEN
D/[MMS]   ( 3209): MmsSettings: find mms_config.xml data file => name = 2131034124
D/jxcore_app_log( 3116): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426131456
,W/jxcore-log( 3116): Initializing JXcore engine
W/jxcore-log( 3116): JXcore engine is ready
,D/MmsSettings( 3209): value of dtmf from frw noti = 80, 65, cmas = 90, 60
E/[MMS]   ( 3209): MmsSettings: [LGE]loadXMLSettings(): Check current items.
D/[MMS]   ( 3209): MmsSettings: [LGE]---------------------------------------->
D/[MMS]   ( 3209): MmsSettings: [LGE]   sms_dr = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   cb_on = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   sms_concat = [5]
D/[MMS]   ( 3209): MmsSettings: [LGE]   sms_char = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_dr_r = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_dr_a = [1]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_rr_r = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_rr_a = [1]
D/[MMS]   ( 3209): MmsSettings: [LGE]   auto_retr = [1]
D/[MMS]   ( 3209): MmsSettings: [LGE]   auto_retr_r = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_priority = [1]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_validity = [6]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_creation = [2]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_size = [300]
D/[MMS]   ( 3209): MmsSettings: [LGE]   slide_dur = [5]
D/[MMS]   ( 3209): MmsSettings: [LGE]   recv_adv = [1]
D/[MMS]   ( 3209): MmsSettings: [LGE]   push_on = [1]
D/[MMS]   ( 3209): MmsSettings: [LGE]   del_old = [1]
D/[MMS]   ( 3209): MmsSettings: [LGE]   sms_limit = [500]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_limit = [50]
D/[MMS]   ( 3209): MmsSettings: [LGE]   max_editor_num = [2000]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_slide_num = [10]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_recipient_num = [20]
D/[MMS]   ( 3209): MmsSettings: [LGE]   attachement_storage = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   send_msg_enter_key = [1]
D/[MMS]   ( 3209): MmsSettings: [LGE]   spam_setting = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   anonymous_spam_setting = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_recipient_length = [64]
D/[MMS]   ( 3209): MmsSettings: [LGE]   sms_recipient_length = [20]
D/[MMS]   ( 3209): MmsSettings: [LGE]   recv_adv_invisible = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_creation_invisible = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_dr_r_invisible = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_dr_a_invisible = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_rr_r_invisible = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_rr_a_invisible = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   auto_retr_r_invisible = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_validity_invisible = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_priority_invisible = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   sms_char_invisible = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   sms_dr_invisible = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   sms_validity_invisible = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   discard_visible = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_pending_in_wifi_use = [1]
D/[MMS]   ( 3209): MmsSettings: [LGE]   attach_location = [1]
D/[MMS]   ( 3209): MmsSettings: [LGE]   custom_extract_ui = [1]
D/[MMS]   ( 3209): MmsSettings: [LGE]   msg_list_data_seperator = [1]
D/[MMS]   ( 3209): MmsSettings: [LGE]   animation_effect = [1]
D/[MMS]   ( 3209): MmsSettings: [LGE]   inline_msg_item = [1]
D/[MMS]   ( 3209): MmsSettings: [LGE]   display_as_slide_layout = [1]
D/[MMS]   ( 3209): MmsSettings: [LGE]   one_bubble = [1]
D/[MMS]   ( 3209): MmsSettings: [LGE]   hide_sync_header_update = [1]
D/[MMS]   ( 3209): MmsSettings: [LGE]   recipient_cc_bcc = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   ciq_on = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_enabled_when_data_disabled = [1]
D/[MMS]   ( 3209): MmsSettings: [LGE]   two_finger_flick = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   kr_skt_feature_set = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   kr_kt_feature_set = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   kr_lgu_feature_set = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   docomo_message_setting = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   docomo_sim_card_set = [0],
D/[MMS]   ( 3209): MmsSettings: [LGE]   docomo_nexti_phonebook_set = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   docomo_function_validity_period = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   docomo_led_button_blink = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   docomo_dtmf_setting = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   china_feature_set = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   media_resolution_restrict_off = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   attachment_save_in_slidesheow = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_max_video_resolution = [320x240]
D/[MMS]   ( 3209): MmsSettings: [LGE]   email_over_sms = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   email_over_sms_gateway_num = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   addr_len_check = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   message_poster = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   sticky_note = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   wificalling_feature_set = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   online_album = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   online_album_dest_num = [000]
D/[MMS]   ( 3209): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   voice_mail = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   smsc_readonly = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   latin_america_fdn_check = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   sms_sent_time_mode = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   fdn_gprs_check = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   reply_to_virtual_smsc = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   save_to_draft = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_signature = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   mms_callback = [0]
D/[MMS]   ( 3209): MmsSettings: [LGE]   message_counters_key = [0]
E/[MMS]   ( 3209): MmsSettings: [LGE]loadXMLSettings(): Check prefMmsConfig.
,I/[MMS]   ( 3209): MmsSettings: [LGE]loadXMLSettings() Phone(saved) information
I/[MMS]   ( 3209): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 3209): MmsSettings: [LGE]loadXMLSettings(): SIM is NOT changed!!!
E/[MMS]   ( 3209): MmsSettings: [LGE]loadXMLSettings(): SIM is not ready!!!
I/MmsHiddenPrefProvider( 1782): MmsHiddenConfig DB Updated
,I/MmsHiddenPrefProvider( 1782): MmsHiddenConfig DB Updated
D/MmsConfig( 3209): [LGE] setForceSmsGsmAlphabet_SystemProperties.set: 0
W/Thread-251( 3230): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5119]" dev="sockfs" ino=5119 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-251( 3230): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-251( 3230): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5924]" dev="sockfs" ino=5924 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-251( 3230): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-251( 3230): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-251( 3230): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[15149]" dev="sockfs" ino=15149 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,I/[MMS]   ( 3209): MmsConfig: [LGE]getUaString=LG-D722 LG-Android-MMS-V4.0/1.2
,W/jxcore-log( 3116): Starting JXcore engine
V/SettingsProvider(  853): call_put(system:android.msg.mms.useragent=LG-D722 LG-Android-MMS-V4.0/1.2) for 0 calling package = com.android.mms
,W/BackupManagerService(  853): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
I/LGDrmClient( 3209): _DRM_ServiceGet() : Bind lgdrm service
,D/LGDRM   (  287): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
D/LGDRM   (  287): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
I/DrmWrapper( 3209): isDrmV1 =true
V/DrmWrapper( 3209): isDrmV2 =false
D/MmsConfig( 3209): [LGE] isSupportUAProfileRandomPath : false
,V/SettingsProvider(  853): call_put(system:android.msg.mms.uaprofile=http://gsm.lge.com/html/gsm/D722-M3-D1.xml) for 0 calling package = com.android.mms
W/BackupManagerService(  853): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
V/SettingsProvider(  853): call_put(system:android.msg.mms.max.size=300) for 0 calling package = com.android.mms
,W/BackupManagerService(  853): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
V/SettingsProvider(  853): call_put(system:android.msg.attachment.max.size=302080) for 0 calling package = com.android.mms
W/BackupManagerService(  853): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
,V/SettingsProvider(  853): call_put(system:android.msg.recipient.max.size=20) for 0 calling package = com.android.mms
W/BackupManagerService(  853): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
,V/SettingsProvider(  853): call_put(system:android.msg.vobject.max.size=10) for 0 calling package = com.android.mms
W/BackupManagerService(  853): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
V/SettingsProvider(  853): call_put(system:android.msg.camera.max.video.resolution=320x240) for 0 calling package = com.android.mms
,W/BackupManagerService(  853): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
V/SettingsProvider(  853): call_put(system:android.msg.package.distinction=unifiedmessage) for 0 calling package = com.android.mms
W/BackupManagerService(  853): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
,V/SettingsProvider(  853): call_put(system:android.msg.old.message.delete=true) for 0 calling package = com.android.mms
W/BackupManagerService(  853): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
V/SettingsProvider(  853): call_put(system:android.msg.sms.max.count=500) for 0 calling package = com.android.mms
,W/BackupManagerService(  853): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
V/SettingsProvider(  853): call_put(system:android.msg.mms.max.count=50) for 0 calling package = com.android.mms
,W/BackupManagerService(  853): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
,W/jxcore-log( 3116): Platform android
W/jxcore-log( 3116): 
W/jxcore-log( 3116): Process ARCH arm
W/jxcore-log( 3116): 
,I/ActivityManager(  853): Start proc android.process.media for service com.android.providers.media/.MediaScannerService: pid=3233 uid=10019 gids={50019, 9997, 2001, 3003, 1028, 1015, 3007, 4002, 1024, 1023} abi=armeabi
,V/MmsConfig( 3209): [isMmsEnabledWhenDataDisabled]value=1
V/MmsConfigStaticVar( 3209): [setMmsEnabledWhenDataDisabled]enabled=true
,I/jxcore-log( 3116): JXcore Cordova bridge is ready!
I/jxcore-log( 3116): 
W/jxcore-log( 3116): JXcore engine is started
V/MmsConfigStaticVar( 3209): [setMmsEnabledWhenDataRoamingDisabled]enabled=false
D/CmasFeatures( 3209): [init]CMAS features are initialized for US country. Returning.
,V/Contact ( 3209): Contact init()_Create new insatnce
,E/jxcore-log( 3116): >> LGE-LG-D722
E/jxcore-log( 3116): 
,I/jxcore-log( 3116): Total memory 906309632
I/jxcore-log( 3116): 
I/jxcore-log( 3116): Free memory 25505792
I/jxcore-log( 3116): 
I/jxcore-log( 3116): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3116): 
I/jxcore-log( 3116): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3116): 
I/jxcore-log( 3116): userPath [ 'www', 'www' ]
I/jxcore-log( 3116): 
,I/jxcore-log( 3116): Size 720 1196
I/jxcore-log( 3116): 
I/jxcore-log( 3116): Screen Brightness 255
I/jxcore-log( 3116): 
E/jxcore-log( 3116): Dummy Error Log.
E/jxcore-log( 3116): 
,V/ToneGenerator( 3209): ToneGenerator constructor: streamType=8, volume=0.133352
,V/AudioPolicyService(  281): registerClient() client 0xb4027380, uid 10027
V/AudioPolicyManager(  281): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  281): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  281): getOutput() returns output 2
V/AudioFlinger(  281): registerClient() client 0xb4033340, pid 3209
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  281): thread 0xb5651000 type 0 TID 1292 waking up
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
V/AudioSystem(  281): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  281): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb5651000
V/AudioSystem( 1369): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1369): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  853): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  853): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1782): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1782): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1970): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1970): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2748): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2748): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  281): thread 0xb56eb000 type 0 TID 1293 waking up
V/AudioFlinger(  281): thread 0xb5735000 type 0 TID 1295 waking up
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
V/AudioFlinger(  281): PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
V/AudioSystem(  281): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  281): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3209): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3209): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb56eb000
V/AudioSystem(  281): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  281): ioConfigChanged() opening already existing output! 6
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb5735000
V/AudioSystem( 3209): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3209): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem( 3209): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 3209): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/ToneGenerator( 3209): Create Track: 0xb4907180
V/AudioTrack( 3209): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 3209): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
V/AudioSystem(  853): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  853): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  853): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  853): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1369): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1369): ioConfigChanged() opening already existing output! 4
I/AudioFlinger(  281): isAudioPlaybackHookOn() false
V/AudioSystem( 1369): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1369): ioConfigChanged() opening already existing output! 6
D/AudioTrack( 3209): TrackOffload: ,AudioTrack Offload disabled by property, returning false
V/AudioSystem( 1782): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1782): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1782): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1782): ioConfigChanged() opening already existing output! 6
V/AudioPolicyManager(  281): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  281): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  281): AudioPolicyManagerEx: getOutputForDevice
V/AudioSystem( 1970): ioConfigChanged() event 0, ioHandle 4
V/AudioPolicyManagerEx(  281): getOutput() returns output 2
V/AudioSystem( 1970): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1970): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1970): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2748): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2748): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2748): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2748): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 3209): getLatency() output 2, latency 50
V/AudioSystem( 3209): getFrameCount() output 2, frameCount 960
V/AudioTrack( 3209): createTrack_l() output 2 afLatency 50
V/AudioTrack( 3209): Create normal PCM 0x1 Track
V/AudioFlinger(  281): createTrack() lSessionId: 20
V/AudioFlinger(  281): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 1
V/AudioTrack( 3209): Flags here  0x4 
V/AudioTrack( 3209): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  281): acquiring 20 from 3209, for 3209
V/AudioFlinger(  281):  added new entry for 20
V/ToneGenerator( 3209): ToneGenerator INIT OK, time: 45446
V/ToneGenerator( 3209): ToneGenerator constructor: streamType=8, volume=0.316228
V/AudioPolicyManager(  281): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  281): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  281): getOutput() returns output 2
V/ToneGenerator( 3209): Create Track: 0xb4908080
V/AudioTrack( 3209): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 3209): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
I/AudioFlinger(  281): isAudioPlaybackHookOn() false
D/AudioTrack( 3209): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioPolicyManager(  281): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  281): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  281): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  281): getOutput() returns output 2
V/AudioSystem( 3209): getLatency() output 2, latency 50
V/AudioSystem( 3209): getFrameCount() output 2, frameCount 960
V/AudioTrack( 3209): createTrack_l() output 2 afLatency 50
V/AudioTrack( 3209): Create normal PCM 0x1 Track
V/AudioFlinger(  281): createTrack() lSessionId: 21
V/AudioFlinger(  281): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioFlinger(  281): sendConfigEvent_l() num events 2 event 1
V/AudioTrack( 3209): Flags here  0x4 
V/AudioTrack( 3209): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  281): acquiring 21 from 3209, for 3209
V/AudioFlinger(  281):  added new entry for 21
V/ToneGenerator( 3209): ToneGenerator INIT OK, time: 45448
V/AudioFlinger(  281): processConfigEvents_l() remaining events 2
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb5651000
I/MessagingNotification( 3209): registerLEDObserver
I/MessagingNotification( 3209): registerLEDObserver REGISTER
I/MmsHiddenPrefProvider( 3209): MmsHiddenConfig.init()
I/MmsHiddenPrefProvider( 3209): MmsHiddenConfig.loadHiddenPrefSettings
,I/SELinux ( 3233): SELinux: Loaded file_contexts from /file_contexts
E/SELinux ( 3233): SELinux:  Could not open /data/system/packages.list:  Permission denied.
W/SELinux ( 3233): SELinux:  Could not look up information for package com.android.providers.downloads, cannot restorecon cache.
E/SELinux ( 3233): SELinux: Could not set context for /data/data/com.android.providers.downloads/cache:  Permission denied
D/CountryDetector(  853): The first listener is added
,E/ActivityThread( 3209): Failed to find provider info for com.lge.ims.provider.uc
I/LOG_TAG ( 3209): registerContactDBChangeObserver
,D/LGMediaProvider( 3233): [MediaScanner] sExternalSDPath : /storage/external_SD
V/LGMediaProvider( 3233): Attached volume: internal
,V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.SIM_STATE_CHANGED flg=0x20000010 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): [LGE Remove Code] INTENT_VALUE_ICC_ABSENT received
I/MmsApp  ( 3209): handleBootCompleted
,D/LocationManagerService(  853): getProviders()=[passive]
D/LocationManagerService(  853): request 386a0409 passive Request[POWER_NONE passive fastest=0] from android(1000)
D/LocationManagerService(  853): provider request: passive ProviderRequest[ON interval=0]
I/SmsReceiverService( 3209): smsBootCompleted
,I/ActivityManager(  853): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=3267 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/SwitchedService( 3209): Mms SwitchedService ACTION_USER_SWITCHED registerReceiver
,V/LGMediaProvider( 3233): Attached volume: external
I/MmsSystemEventReceiver( 3209): mmsBootComplete
V/DownloadManager( 3233): DownloadService onCreate
,D/MmsConfig( 3209): MediaScanner - scannerConnected
I/DownloadManager( 3233): in removeSpuriousFiles
V/DownloadManager( 3233): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3233): created cursor android.database.sqlite.SQLiteCursor@c30009 on behalf of 3233
I/NotificationManager( 3233): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3233): in trimDatabase
V/DownloadManager( 3233): DownloadService onStartCommand
W/ResourcesManager( 3209): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/DownloadManager( 3233): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3233): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3233): created cursor android.database.sqlite.SQLiteCursor@3e9293c5 on behalf of 3233
,V/DownloadManager( 3233): created cursor android.database.sqlite.SQLiteCursor@1ccd211a on behalf of 3233
D/MmsConfig( 3209): getUserModeNotAllowedSms:sUserModeNotAllowedSms:false
D/MmsConfig( 3209): isNotAllowedSms: currentUser:0
D/MmsConfig( 3209): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3209): isUserMode:false
W/ResourcesManager( 3267): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3267): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 3267): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 3267): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 3267): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,V/LEDService( 1834): stopInternal(), pkg=com.android.mms, id=123
,D/MessagingNotification( 3209): disalbleEmotionalLED id= 123
I/NotificationManager( 3209): com.android.mms: cancel(123) by com.android.mms
V/LEDService( 1834): stopInternal(), pkg=com.android.mms, id=946
D/MessagingNotification( 3209): disalbleEmotionalLED id= 946
I/NotificationManager( 3209): com.android.mms: cancel(946) by com.android.mms
D/MessagingNotification( 3209): unread_count:0, thread_count:0, thread_id:-100
D/MessagingNotification( 3209): toLockscreenWithUnreadMsgCnt - count = 0
,V/DownloadManager( 3233): DownloadService onDestroy
,I/IndexDatabaseHelper( 3267): Using schema version: 115
,I/IndexDatabaseHelper( 3267): Index is fine
I/ActivityManager(  853): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=3290 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,E/LGDMClient( 3061): [DmServiceProcessor.java] [isNeededToRegenerate()] : [195] : SIM information is not readed right. so reconfig is needed regardless SIM serial number
,I/LGDMClient( 3061): [DmCAConfigParser.java] [getInstance()] : [73] : DmsCAConfigParser sInstance null
I/jxcore-log( 3116): getBuffer is called!!!!
I/jxcore-log( 3116): 
,I/LockScreenSettings( 3290): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,D/LGDMClient( 3061): [DmPhoneSpecificInfo.java] [getPhoneSpecificInfo()] : [204] : Current MultiSimEnabled is false
,D/QuickCoverActivity( 3209): lockscreensettings ret = true
I/ActivityManager(  853): Killing 2532:com.lge.qremote/u0a106 (adj 15): empty #11
D/LGDMClient( 3061): [DmPhoneSpecificInfo.java] [getPhoneSpecificInfo()] : [239] : getPhoneSpecificInfo: sim mccmnc(),spn(),gid(null),imsi(null)
I/LGDMClient( 3061): [DmCAConfigParser.java] [parse()] : [108] : parse
D/LGDMClient( 3061): [DmCAConfigParser.java] [setDefaultProfile()] : [490] : setDefaultProfile
D/LGDMClient( 3061): [DmCAConfigParser.java] [setDefaultProfile()] : [493] : filename : fota_dm_settings.xml
D/LGDMClient( 3061): [DmCAConfigParser.java] [setDefaultProfile()] : [506] : [UI4.1] Search [fota_dm_settings.xml]
D/LGDMClient( 3061): [DmCAConfigParser.java] [parse()] : [134] : [UI4.1] Search [fota_dm_settings.xml]
,V/WiFiOffLoadBroadcast( 3267): WiFiOffLoadBroadcast: android.intent.action.SIM_STATE_CHANGED
,V/WiFiOffLoadBroadcast( 3267): Sim absent, removing wifis
,D/WiFiOffLoadUpdatePriority( 3267): remove : truetruefalse
D/WiFiOffLoadUpdatePriority( 3267): remove2
V/WiFiOffLoadSharedPrefsUtils( 3267): save wifi state
V/WiFiOffLoadSharedPrefsUtils( 3267): save remove
,W/libprocessgroup(  853): failed to open /acct/uid_10106/pid_2532/cgroup.procs: No such file or directory
I/MessagingNotification( 3209): repeat count :0
,D/SmartCoverUpdateMonitor( 1330): received broadcast lge.intent.action.UNREAD_MESSAGES
I/NfcP2pLinkManager( 1816): LLCP deactivated.
I/NfcP2pLinkManager( 1816): Duplicate onLlcpDectivated()
I/ActivityManager(  853): Killing 2888:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
D/KeyguardModel( 1369): mReceiver, received action: lge.intent.action.UNREAD_MESSAGES, sendingUserId:0
I/QuickCircle( 1330): onReceive :Intent { act=lge.intent.action.UNREAD_MESSAGES flg=0x10 (has extras) }, sComponents:[com.coremobility.app.vnotes.CM_VnoteInbox, com.android.contacts.activities.DialtactsActivity, com.android.contacts.DialtactsRecentCallsEntryActivity, com.lge.vvm.authmanager.VvmAuthManagerActivity, com.lge.email.ui.setupwizard.Welcome, com.skt.prod.dialer.activities.main.MainActivity, com.android.mms.ui.ConversationList, com.lge.message.ui.ConversationList, com.lge.message.activity.MainMenuActivity, com.skt.skaf.A000Z00040.A000Z00040, com.lge.updatecenter.UpdateCenterPrfActivity]
,D/KeyguardModel( 1369): putNotificationIntoList Number: 0 Id: 1 UserId: 0
I/art     (  853): Explicit concurrent mark sweep GC freed 18986(983KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/33MB, paused 5.454ms total 154.260ms
D/UsbSettingsReceiver( 3267): [AUTORUN] onReceive() : action = android.intent.action.SIM_STATE_CHANGED
D/UsbSettingsReceiver( 3267): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3267): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 3267): [AUTORUN] persist.sys.usb.config = ptp_only,adb
W/libprocessgroup(  853): failed to open /acct/uid_10089/pid_2888/cgroup.procs: No such file or directory
,D/UsbSettingsReceiver( 3267): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/SmartCoverUpdateMonitor( 1330): MSG_BIGNOTI_XXX
D/UsbSettingsReceiver( 3267): android.intent.action.SIM_STATE_CHANGED
D/UsbSettingsReceiver( 3267): Target OperatorOPEN
,D/UsbSettingsReceiver( 3267): Target CountryEU
D/UsbSettingsReceiver( 3267): stateExtraABSENT
,D/UsbSettingsReceiver( 3267): INTENT_VALUE_ICC_IMSIIMSI
D/StoreModeReceiver( 3267): intent.getAction() : android.intent.action.SIM_STATE_CHANGED
D/StoreModeReceiver( 3267): sim state :ABSENT
D/StoreModeReceiver( 3267): Back LED don't supported.
V/SettingsProvider(  853): call_put(system:emotional_led_back_led=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  853): call_put(system:emotional_led_back_incoming_call=0) for 0 calling package = com.android.settings
I/ActivityManager(  853): Killing 2983:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #11
,V/SettingsProvider(  853): call_put(system:emotional_led_back_alarm=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  853): call_put(system:emotional_led_back_missed_call=0) for 0 calling package = com.android.settings
V/SettingsProvider(  853): call_put(system:emotional_led_back_missed_messages=0) for 0 calling package = com.android.settings
,W/libprocessgroup(  853): failed to open /acct/uid_10016/pid_2983/cgroup.procs: No such file or directory
D/MessagingNotification( 3209): observerLED
V/SettingsProvider(  853): call_put(system:emotional_led_back_missed_emails=0) for 0 calling package = com.android.settings
D/MessagingNotification( 3209): observerLED LED ON
,D/MmsConfig( 3209): getUserModeNotAllowedSms:sUserModeNotAllowedSms:false
D/MmsConfig( 3209): isNotAllowedSms: currentUser:0
D/MmsConfig( 3209): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3209): isUserMode:false
D/MessagingNotification( 3209): unreadMessageHandler
V/SettingsProvider(  853): call_put(system:emotional_led_back_calendar_noti=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  853): call_put(system:emotional_led_back_voice_recording=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  853): call_put(system:emotional_led_back_camera_timer_noti=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  853): call_put(system:emotional_led_back_camera_face_detecting_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  853): call_put(system:notification_light_pulse_back=0) for 0 calling package = com.android.settings
,D/StoreModeReceiver( 3267): SystemProperty Default brightness value [0-255] : 143
,D/StoreModeReceiver( 3267): Default brightness[0-255] : 143
I/LEDService( 1834): getCurrentHighestLGLedRecord() start. size = 1
V/LEDService( 1834): startInternal : pkg=batteryinfo, recordId=0 : LGLedRecord{15eaf75d flags=0 patternId=0 color=0 priority=-1 recordId=0 pkg=batteryinfo infinite=true mExceptional=false mNativeNotification=false whichLedPlay=1 patternFilePath=null}
I/LEDService( 1834): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1834): set_light_notifications: 0,0,0,0,3
,I/LEDService( 1834): updateLightsLocked : turn off led
D/qdlights( 1834): set_light_notifications: 0,0,0,0,3
W/ResourcesManager( 3267): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/StoreModeReceiver( 3267): Default Screen off timeout value : 30000
D/StoreModeReceiver( 3267): SystemProperty Default brightness Mode value[true/false] : false
D/StoreModeReceiver( 3267): BRIGHTNESS_MODE - 0
D/StoreModeReceiver( 3267): Default brightness Mode [0/1] : 0
D/StoreModeReceiver( 3267): Default NIGHT_MODE : 0
D/StoreModeReceiver( 3267): Set MaxBrightness : 255
E/PhoneInterfaceManager( 1782): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/StoreModeReceiver( 3267): getPhoneNumber is empty
,D/SettingBootReceiver( 3267): onReceive
D/SettingBootReceiver( 3267): [Extra] : ABSENT == 'LOADED' ??
,I/DualIMSIApnProfileReceiver( 3267): intentName == android.intent.action.SIM_STATE_CHANGED
I/DualIMSIApnProfileReceiver( 3267): IMSI not available :: return 
I/ActivityManager(  853): Killing 3005:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10021/pid_3005/cgroup.procs: No such file or directory
,I/ActivityManager(  853): Start proc com.android.contacts for broadcast com.android.contacts/com.lge.contacts.sim.SimPhonebookStateReceiver: pid=3316 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 3316): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3316): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 3316): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 3316): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 3316): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 3316): BUILD Country: EU
I/SystemConfig( 3316): BUILD Operator: OPEN
,W/SIMContacts( 3316): SimPhonebookStateReceiver|onReceive: ACTION_SIM_STATE_CHANGED
,D/SIMContacts( 3316): SimConfig|ENABLE_MULTI_SIM_MODE : false
D/SIMContacts( 3316): SimConfig|Slot count : 1
W/SIMContacts( 3316): SimPhonebookStateReceiver|PhoneCount = 1
D/PhoneInterfaceManager( 1782): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
,I/SystemConfig( 3316): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 3316): existFile = false
I/SystemConfig( 3316): canReadFile = false
I/SystemConfig( 3316): systemFeature RCS result false
D/SystemConfig( 3316): refreshRcsSupport() :false
W/SIMContacts( 3316): SimPhonebookStateReceiver|SIM slot is empty... start clear sim contact
D/SIMContacts( 3316): SimPhonebookManager||clearSimContacts:BEGIN : 0
,D/SIMContacts( 3316): CancelableTaskScheduler|| task={com.lge.contacts.sim.ClearSimContactsTask@3952700d} is registered
V/SIMContacts( 3316): CancelableTaskScheduler|requestStartLocked {com.lge.contacts.sim.ClearSimContactsTask@3952700d}
D/SIMContacts( 3316): SimPhonebookManager||clearSimContacts:END
D/SIMContacts( 3316): CancelableTaskScheduler|start background task {20}
D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=386788903, flags=0x20000001, tag="CancelableTaskScheduler", ws=null, historyTag=null, uid=10018, pid=3316
D/SettingsProviderInitializer(  853): [Extra] : ABSENT == 'LOADED' ??
,V/LGSC    ( 2807): [105] 501
V/LGSC    ( 1782): [101] 102, action=android.intent.action.SIM_STATE_CHANGED, iccState=ABSENT
I/Contacts_Profile( 3316): support PRI : true
I/Contacts_Profile( 3316): setDefault : phone
I/ActivityManager(  853): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.wcdma_only.log_service.FactorySIMReceiver: pid=3342 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3042:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10009/pid_3042/cgroup.procs: No such file or directory
,I/ValidateNoPeople(  853): mEvictionCount: 0
,I/LOG_TAG ( 3209): sendMessageToComposeMessageActivy + null
W/ActivityManager(  853): Unable to start service Intent { act=com.lge.ime.intent.ANDROID_CONTACT_DB_UPDATED pkg=com.lge.ime } U=0: not found
W/ResourcesManager( 3342): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 3342): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=386788903 [CancelableTaskScheduler], flags=0x0
D/SIMContacts( 3316): CancelableTaskScheduler|background task is finished {20}, time=155.498542 msec
V/LogService( 3342): FactorySIMReceiver.operatorNumeric : 
V/LogService( 3342): FactorySIMReceiver.factory.enable : 0
V/LogService( 3342): FactorySIMReceiver.factory.enable : 
,I/ActivityManager(  853): Start proc com.android.providers.partnerbookmarks for broadcast com.android.providers.partnerbookmarks/com.lge.provider.BookmarksProviderReceiver: pid=3365 uid=10071 gids={50071, 9997} abi=armeabi-v7a
I/ActivityManager(  853): Killing 1738:com.android.defcontainer/u0a4 (adj 15): empty #11
I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 21.744ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.851ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.591ms
,W/libprocessgroup(  853): failed to open /acct/uid_10004/pid_1738/cgroup.procs: No such file or directory
,D/AccountTypeManager( 3316): Registering 1 extension packages
,E/ExternalAccountType( 3316): Unsupported attribute readOnly
,D/AccountTypeManager( 3316): Registering extension package account type=com.google, dataSet=plus, packageName=com.google.android.apps.plus
,I/SIMContacts( 3316): SimPhonebookManager|[0]SIM loading status : false
I/AccountTypeManager( 3316): Loaded meta-data for 4 account types, 3 accounts in 60ms(wall) 35ms(cpu)
D/AccountTypeManager( 3316): Registering 1 extension packages
,E/ExternalAccountType( 3316): Unsupported attribute readOnly
,D/PARTNER_SimInfo( 3365): FlexData mcc/mnc is null 
D/AccountTypeManager( 3316): Registering extension package account type=com.google, dataSet=plus, packageName=com.google.android.apps.plus
I/SIMContacts( 3316): SimPhonebookManager|[0]SIM loading status : false
I/AccountTypeManager( 3316): Loaded meta-data for 4 account types, 3 accounts in 22ms(wall) 11ms(cpu)
I/BookmarksProviderReceiver( 3365): BookmarksProviderReceiver onReceive = [ android.intent.action.SIM_STATE_CHANGED ]
I/BookmarksProviderReceiver( 3365): SIM_STATE_CHANGED event stateExtra : [ ABSENT ]
,E/PARTNER_SimInfo( 3365): setSimState:NOT_READY
I/ActivityManager(  853): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=3384 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  853): Killing 3061:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_3061/cgroup.procs: No such file or directory
,D/SIMObserver( 3384): action:android.intent.action.SIM_STATE_CHANGED
,D/SIMObserver( 3384): state : ABSENT
D/EULA::SimManager( 3384): SimManager getInstance.
I/EULA::SimManager( 3384): TelephonyManager will be used!
I/EULA::SimManager( 3384): SubscriptionManager will be used!
I/EULA::SimManager( 3384): sSimInstance : android.telephony.TelephonyManager@807896a
,I/EULA::SimManager( 3384): sIsMultiSimEnabled : false
I/EULA::SimManager( 3384): sSIMCount : 1
I/EULA::SimManager( 3384): TelephonyManager will be used!
I/EULA::SimManager( 3384): SubscriptionManager will be used!
I/EULA::SimManager( 3384): sSimInstance : android.telephony.TelephonyManager@807896a
I/EULA::SimManager( 3384): sIsMultiSimEnabled : false
I/EULA::SimManager( 3384): sSIMCount : 1
,D/SIMObserver( 3384): simState : 1
I/LicenseContentProvider( 3384): start selecting data
D/EULA::SimManager( 3384): SimManager getInstance.
I/EULA::SimManager( 3384): TelephonyManager will be used!
I/EULA::SimManager( 3384): SubscriptionManager will be used!
I/EULA::SimManager( 3384): sSimInstance : android.telephony.TelephonyManager@807896a
I/EULA::SimManager( 3384): sIsMultiSimEnabled : false
I/EULA::SimManager( 3384): sSIMCount : 1
D/SIMObserver( 3384): simInfo1
D/FotaManager( 3384): Fingerprint is same, do nothing
,D/FotaManager( 3384): enable_notification_eula_flag : 1
D/SIMObserver( 3384): EULA has not been agreed, we need to show it on notification bar
W/FotaManager( 3384): topActivity.getClassName() : com.example.hello.MainActivity
D/FotaManager( 3384): baseActivity : com.example.hello / com.example.hello.MainActivity
V/NotificationService(  853): enqueueNotificationInternal: pkg=com.lge.eula id=262082 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ZenLog  (  853): intercepted: 0|com.lge.eula|262082|null|1000,none
V/NotificationService(  853): pkg=com.lge.eula canInterrupt=false intercept=true
I/NotificationServiceEx(  853): LED remove() : mLights=0|com.lge.eula|262082|null|1000
D/NotificationServiceEx(  853): updateLightListLocked :r=0|com.lge.eula|262082|null|1000, action=2
D/NotificationServiceEx(  853): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/ActivityManager(  853): Killing 3097:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
D/SmartCoverUpdateMonitor( 1330): onNotificationPosted() : StatusBarNotification(pkg=com.lge.eula user=UserHandle{0} id=262082 tag=null score=0 key=0|com.lge.eula|262082|null|1000: Notification(pri=0 contentView=com.lge.eula/0x1090079 vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE))
D/SmartCoverUpdateMonitor( 1330): addNotification() qcn.getKey() : 0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1330): addNotification() : 0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1330): filterAndSort()
,W/libprocessgroup(  853): failed to open /acct/uid_10011/pid_3097/cgroup.procs: No such file or directory
,D/LgeQuickCoverNotificationData( 1330): isNotificationForCurrentUser : true
D/LgeQuickCoverNotificationData( 1330): isNotificationForCurrentUser : true
D/LgeQuickCoverNotificationData( 1330): showAll2
D/LgeQuickCoverNotificationData( 1330): showAll() Key : 0|com.lge.eula|262082|null|1000 , GroupKey : 0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1330): showAll() Key : 0|com.android.systemui|2130839020|null|10025 , GroupKey : 0|com.android.systemui|2130839020|null|10025
D/WearableService( 1763): callingUid 10006, callindPid: 1763
,E/MDM     ( 1763): [111] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1763): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 2311): Restart initialization of location
,V/GLSActivity( 1763): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1763): com.google.android.gms: cancel(0) by com.google.android.gms
,I/[SystemUI]PhoneStatusBar( 1369): updateMediaMetaData(false): mMediaMetadata = null
,D/WeatherAncestor( 2742): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 8:53:55
D/UpdateThreadPoolManager( 2742): 2 : This is isUpdating : false
,D/WeatherAncestor( 2742): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 8:53:55
D/WeatherService( 2742): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2742): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2742): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2742): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2742): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2742): 2 : This is isUpdating : false
D/WeatherService( 2742): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2742): 2 : buildUpdate, appWidgetId: 2
,W/GCoreFlp( 1763): No location to return for getLastLocation()
W/FusedLocationProvider( 1763): location=null
D/WeatherTheme( 2742): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2742): 2 : Fixed theme : optimus
D/WeatherReflect( 2742): 2 : Map key string is -2
,D/lim     ( 2742): 2 : time = 08:53
I/WeatherReflect( 2742): Model Name : LG-D722
D/WeatherTheme( 2742): 2 : exactly same view!
D/WeatherTheme( 2742): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2742): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2742): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2742): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/UserPresentBroadcastReceiver( 1763): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/SmartCoverUpdateMonitor( 1330): received broadcast android.intent.action.BOOT_COMPLETED
,I/[SystemUI]BOOT( 1369): SystemUIService, BOOT_COMPLETED received
I/SystemUIService( 1369): com.lge.systemui.LGSystemUI@2eefed10.onBootCompleted(), mBootCompleted: true
I/SystemUIService( 1369): com.android.systemui.keyguard.KeyguardViewMediator@7aed71f.onBootCompleted(), mBootCompleted: true
I/SystemUIService( 1369): com.android.systemui.recent.Recents@29926807.onBootCompleted(), mBootCompleted: true
I/SystemUIService( 1369): com.android.systemui.volume.VolumeUI@14f437a6.onBootCompleted(), mBootCompleted: true
I/SystemUIService( 1369): com.android.systemui.statusbar.SystemBars@188cc594.onBootCompleted(), mBootCompleted: true
I/SystemUIService( 1369): com.android.systemui.usb.LGStorageNotification@41c2832.onBootCompleted(), mBootCompleted: true
I/SystemUIService( 1369): com.lge.power.LGPowerUI@1423332c.onBootCompleted(), mBootCompleted: true
I/SystemUIService( 1369): com.android.systemui.media.RingtonePlayer@c9c61f5.onBootCompleted(), mBootCompleted: true
I/[SystemUI]LGStorageNotification( 1369): connected=false
,I/RecoverySystem(  853): No recovery log file
,I/ActivityManager(  853): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=3426 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/BootReceiver(  853): Copying audit failures to DropBox
,I/BootReceiver(  853): Checking for fsck errors
D/LauncherStateReceiver2( 3316): .activities.CallLogSearchResolverActivity enable(1)/disable(2) : 2
,D/LauncherStateReceiver2( 3316): .DialtactsRecentCallsEntryActivity enable(1)/disable(2) : 2
D/LauncherStateReceiver2( 3316): .alias.SpeedDialListActivity enable(1)/disable(2) : 2
,I/WifiServerServiceExt(  853): ACTION_BOOT_COMPLETED
,V/TelephonyAutoProfiling( 1782): [getValue] PROFILE key : VMS, value : null, phoneId : 0
D/ConnectivityService(  853): Got NetworkFactory Messenger for WIFI
D/ConnectivityService(  853): NetworkFactory connected
,D/WIFI    (  853): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/WIFI    (  853):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/AudioPolicyManager(  281): setDeviceConnectionState() device: 4, state 0, address 
D/CHFeatures( 3316): serviceContry: EU
W/AudioPolicyManager(  281): setDeviceConnectionState() device not connected: 4
D/CHFeatures( 3316): serviceProvider: OPEN
D/CHFeatures( 3316): serviceCountryIndex: 2
D/CHFeatures( 3316): serviceProviderIndex: 4
V/AudioPolicyManager(  281): setDeviceConnectionState() device: 8, state 0, address 
W/AudioPolicyManager(  281): setDeviceConnectionState() device not connected: 8
,D/LGSDEncService( 1834): action=android.intent.action.BOOT_COMPLETED
I/QCNEJ   ( 1870): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/LGSDEncService( 1834): MediaExceptionType=BDMB/MID/EC3/OGV/JPEG/WEBM/QCP/JPS/RA/MXMF/JPG/WAV/RV/PNG/M3U8/WPL/3GP/3GPP/OTA/SMF/AMR/MP4/BMP/OGG/MKV/TP/DCI/M4V/WMV/WEBP/3GPP2/DTS/ADTS/MPO/OGA/RMVB/OGM/3G2/3GA/MKA/MPD/TS/MP2/FLAC/MPGA/JPE/RM/M2TS/PLS/MIDI/WBMP/RAM/ASF/MPG/RTX/K3G/IMY/AWB/MPEG/AC3/F4V/DIVX/XMF/FLV/MP3/RTTTL/AVI/GIF/AAC/M3U/M4A/SKM/WMA/MTS/DMB/
D/LGBluetoothAPIService( 1834): [BTUI] onReceive action : android.intent.action.BOOT_COMPLETED
D/        ( 1834): android_net_LGSDEnc_sysCallMediaExt:33:: propertyVal = (379), extList = (BDMB/MID/EC3/OGV/JPEG/WEBM/QCP/JPS/RA/MXMF/JPG/WAV/RV/PNG/M3U8/WPL/3GP/3GPP/OTA/SMF/AMR/MP4/BMP/OGG/MKV/TP/DCI/M4V/WMV/WEBP/3GPP2/DTS/ADTS/MPO/OGA/RMVB/OGM/3G2/3GA/MKA/MPD/TS/MP2/FLAC/MPGA/JPE/RM/M2TS/PLS/MIDI/WBMP/RAM/ASF/MPG/RTX/K3G/IMY/AWB/MPEG/AC3/F4V/DIVX/XMF/FLV/MP3/RTTTL/AVI/GIF/AAC/M3U/M4A/SKM/WMA/MTS/DMB/) 
D/LGBluetoothFeatureConfig( 1834): isSupportPan() :  mTargetOp=OPEN
D/LGBluetoothFeatureConfig( 1834):  get() - isFeatureLoaded : false
D/        ( 1834): android_net_LGSDEnc_sysCallMediaProperty:61:: propertyVal = (378), enable=(0) rc=(1)
I/LGSDEncService( 1834): BOOT_BroadcastReceiver Media SystemCall :: getMediaProperty = 0
D/LGSDEncService( 1834): Initializing Encryption start
,I/NotificationManager(  853): android: cancelAsUser(17039631) by android
V/WifiSapService( 1834): WifiSapService [ACTION_BOOT_COMPLETED]
E/DefaultVoicemailNotifier( 3316): No voicemails to notify about: clear the notification.
,I/NotificationManager( 3316): com.android.contacts: cancel(1) by com.android.contacts
I/LogService_Receiver( 3342): getAction is : android.intent.action.BOOT_COMPLETED
E/LogService_Receiver( 3342): Log Enable Check Value :0
E/LogService_Receiver( 3342): Log Enable Check Value :0
E/LogService_Receiver( 3342): Log Enable Check Value :0
E/LogService_Receiver( 3342): Log Enable Check Value :0
E/LogService_Receiver( 3342): Log Enable Check Value :0
E/LogService_Receiver( 3342): Log Enable Check Value :0
I/ActivityManager(  853): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3453 uid=10008 gids={50008, 9997} abi=armeabi-v7a
,V/OneTimeInitializerReceiver( 3453): OneTimeInitializerReceiver.onReceive
,V/OneTimeService( 3453): OneTimeService.onHandleIntent
I/art     ( 2035): Explicit concurrent mark sweep GC freed 2578(99KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.056ms total 33.375ms
,I/ActivityManager(  853): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=3473 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3139:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10011/pid_3139/cgroup.procs: No such file or directory
,I/Scheduler( 1763): Use legacy PeriodicScheduler
D/CellBroadcastReceiverApp( 3473): CellBroadcastReceiverApp, onCreate()
,D/MultiSimWrapper( 3473): [MessageUtils] isTripleSimEnabled=false
D/MultiSimWrapper( 3473): [isMultiSimEnabled] = false
D/MultiSimWrapper( 3473): [MessageUtils] isTripleSimEnabled=false
D/CellBroadcastReceiver( 3473): startInit() started. iccLoaded=false init_complete=false
,W/InstanceID/Rpc( 1763): Found 10006
,D/CommonUtil( 3473): spn is empty. use default value as ""
D/CommonUtil( 3473): getRuntimeImsiCode[]
,D/CommonUtil( 3473): spn is empty. use default value as ""
D/CommonUtil( 3473): getRuntimeImsiCode[]
D/CommonUtil( 3473): simOperator =
D/CommonUtil( 3473): getRuntimeMccCode[0]
D/CellBroadcastReceiver( 3473): single sim : imsiCode= MccCode=0
E/CellBroadcastReceiver( 3473): IMSI value is NOT available yet. DO NOT PROCESS NEXT STEP.
D/CellBroadcastReceiver( 3473): onReceive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
D/CellBroadcastReceiver( 3473): ACTION_BOOT_COMPLETED received.
D/CellBroadcastAlertService( 3473): myUid on onStartCommand() =0
D/CellBroadcastAlertService( 3473): [MmsConfig] isSupportEmotionalLED=true
,V/AudioFlinger(  281): thread 0xb5735000 type 0 TID 1295 going to sleep
,V/AudioFlinger(  281): thread 0xb5651000 type 0 TID 1292 going to sleep
V/AudioFlinger(  281): thread 0xb56eb000 type 0 TID 1293 going to sleep
I/ActivityManager(  853): Start proc com.lge.email for broadcast com.lge.email/.ui.widget.EmailWidgetProvider: pid=3496 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/CellBroadcastAlertService( 3473): [CB] getEmotionalLEDEffectEnabled= true
I/CellBroadcastAlertService( 3473): startEmotionalLedService 
I/CellBroadcastAlertService( 3473): registerLEDObserver
I/CellBroadcastAlertService( 3473): registerLEDObserver REGISTER
D/CellBroadcastAlertService( 3473): make mBroadcastDb
,D/CellBroadcastAlertService( 3473): after ACTION_BOOT_COMPLETED cursor, Db closed!!
,I/ActivityManager(  853): Killing 3174:com.android.browser/u0a12 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10012/pid_3174/cgroup.procs: No such file or directory
W/ResourcesManager( 3496): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3496): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 3496): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/LGEmail ( 3496): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 3496): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ActivityManager(  853): Start proc com.lge.mlt for broadcast com.lge.mlt/.MptOnBootReceiver: pid=3521 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  853): Killing 3290:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10069/pid_3290/cgroup.procs: No such file or directory
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.mlt.MptOnBootReceiver.onReceive:107 android.app.ActivityThread.handleReceiver:2663 
,I/ActivityManager(  853): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3538 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,E/MPT MptOnPowerWatcher( 3521): MptOnPowerWatcher
E/dbFlushManager( 3521): Handler is not ready.
E/dbFlushManager( 3521): It's going to sleep routine until the message handler is generated.
,E/MPT MptOnPowerWatcher( 3521): startListen
,I/ActivityManager(  853): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=3574 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 3574): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/RlzPingService( 3538): Setting next ping for 1458201237196
,D/CalendarProvider2( 3574): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2c2f2b55
D/CalendarProvider2( 3574): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 3574): Created com.android.providers.calendar.CalendarAlarmManager@208cd236(com.android.providers.calendar.CalendarProvider2@2c2f2b55)
D/CalendarReceiver( 3574): [onReceive] intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.calendar/.CalendarReceiver (has extras) }
D/CalendarReceiver( 3574): [onReceive] WakeLock new : CalendarReceiver_Provider, ReferenceCounted = true
,I/art     (  853): Explicit concurrent mark sweep GC freed 24034(1251KB) AllocSpace objects, 6(144KB) LOS objects, 33% free, 22MB/33MB, paused 2.379ms total 164.052ms
,D/CalendarReceiver( 3574): [onReceive] WakeLock acquire : CalendarReceiver_Provider
D/CalendarReceiver( 3574): [onReceive] android.intent.action.BOOT_COMPLETED
D/CalendarProvider2( 3574): Scheduling check of next Alarm
I/ActivityManager(  853): Killing 3267:com.android.settings/1000 (adj 15): empty #11
,D/CalendarProvider2( 3574): SCHEDULE_ALARM_REMOVE
W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_3267/cgroup.procs: No such file or directory
,D/CalendarReceiver( 3574): [onReceive] WakeLock release : CalendarReceiver_Provider
,I/ActivityManager(  853): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.receiver.DmReceiver: pid=3601 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/LAlarm  (  853): Service started flags 0 startId 3
,W/ContextImpl( 3601): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmNotiService.bootCompleted:575 com.lge.lgdmsclient.receiver.DmReceiver.onReceive:94 
,E/LGDMClient( 3601): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 3601): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 3601): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_BOOTUP_COMPLETE
D/LGDMClient( 3601): [DmUtil.java] [removeSilenceBootFile()] : [894] : Try to remove a Silence file
,D/LGDMClient( 3601): [DmNotiService.java] [actionSystemBootComplete()] : [459] : CHECK_AUTO_UPDATE_PROCESS : 0 Call removeSilenceBootFile() 
I/LGDMClient( 3601): [DmNotiService.java] [actionSystemBootComplete()] : [467] : DM Service on boot completed
D/LGDMClient( 3601): [DmClientController.java] [startService()] : [400] : startService(), DownloadService will be started in order to follow the start of DmClientController
W/ContextImpl( 3601): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.controller.DmClientController.startService:404 com.lge.lgdmsclient.dmclient.controller.DmClientController.getInstance:345 com.lge.lgdmsclient.service.DmNotiService.actionSystemBootComplete:474 
,I/ActivityManager(  853): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=3623 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/LGDMClient( 3601): [DmAgent.java] [<init>()] : [164] : DmAgent is started -> DmConstants.DMAgentState.mDmaState = 0
I/LGDMClient( 3601): [DmCAConfigParser.java] [getInstance()] : [73] : DmsCAConfigParser sInstance null
,D/LGDMClient( 3601): [DmClientController.java] [run()] : [178] : LooperSTART
,D/LGDMClient( 3601): [DmPhoneSpecificInfo.java] [getPhoneSpecificInfo()] : [204] : Current MultiSimEnabled is false
,D/LGDMClient( 3601): [DmPhoneSpecificInfo.java] [getPhoneSpecificInfo()] : [239] : getPhoneSpecificInfo: sim mccmnc(),spn(),gid(null),imsi(null)
I/LGDMClient( 3601): [DmCAConfigParser.java] [parse()] : [108] : parse
D/LGDMClient( 3601): [DmCAConfigParser.java] [setDefaultProfile()] : [490] : setDefaultProfile
D/LGDMClient( 3601): [DmCAConfigParser.java] [setDefaultProfile()] : [493] : filename : fota_dm_settings.xml
D/LGDMClient( 3601): [DmCAConfigParser.java] [setDefaultProfile()] : [506] : [UI4.1] Search [fota_dm_settings.xml]
,D/LGDMClient( 3601): [DmCAConfigParser.java] [parse()] : [134] : [UI4.1] Search [fota_dm_settings.xml]
D/LGDMClient( 3601): [DmAgentUtil.java] [setAutoAgentSchedule()] : [117] : IN setAutoAgentSchedule()
,D/LGDMClient( 3601): [DmAgentUtil.java] [setAutoAgentSchedule()] : [126] :  cursor != null setAutoAgentSchedule()
,D/LGDMClient( 3601): [DmAgentUtil.java] [setAutoAgentSchedule()] : [167] : SET ALARM setAutoAgentSchedule() = 20160317T212428
D/LGDMClient( 3601): [DmAgentUtil.java] [setAutoAgentSchedule()] : [185] : OUT setAutoAgentSchedule()
D/LGDMClient( 3601): [DmAgent.java] [checkPostponed()] : [2062] : DMAGentState is: DmConstants.DMAgentState.mDmaState = 0
V/LGDMClient( 3601): [DmClientController.java] [handleMessage()] : [181] : DmClientController: run() - msg.what=31
D/LGDMClient( 3601): [DmAgent.java] [processRestartHandler()] : [1241] : DMAGentState is: DmConstants.DMAgentState.mDmaState = 0
E/LGDMClient( 3601): [DmDownloadService.java] [onCreate()] : [56] : DmDownloadService.onCreate()
D/LGDMClient( 3601): [DmDownloadService.java] [onStartCommand()] : [92] : DmDownloadService.onStartCommand()
D/LGDMClient( 3601): [DmDownloadService.java] [handleStart()] : [103] : DmDownloadService  intend : Intent { cmp=com.lge.lgdmsclient/.service.DmDownloadService }
,E/[LGE_FOTA] ( 3601): FOTA JNI_OnLoad
E/[LGE_FOTA] ( 3601):  FOTAJNI_GetUAResult in
E/[LGE_FOTA] ( 3601): FOTAFS_Open /cache/fota/usd.dat, 0, handle : 1c
,E/[LGE_FOTA] ( 3601): enUpdateState                : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.enState             : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgOffset[0]     : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgSize[0]       : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgOffset[1]     : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgSize[1]       : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgOffset[2]     : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgSize[2]       : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgOffset[3]     : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgSize[3]       : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgOffset[4]     : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgSize[4]       : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgOffset[5]     : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgSize[5]       : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgOffset[6]     : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgSize[6]       : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgOffset[7]     : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgSize[7]       : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgOffset[8]     : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgSize[8]       : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgOffset[9]     : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgSize[9]       : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgOffset[10]     : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgSize[10]       : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgOffset[11]     : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgSize[11]       : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgOffset[12]     : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgSize[12]       : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgOffset[13]     : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgSize[13]       : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgOffset[14]     : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgSize[14]       : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgOffset[15]     : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiPkgSize[15]       : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiCurrSection       : 0x00000000
E/[LGE_FOTA] ( 3601): stFWInfo.uiResult            : 0x00000000
E/[LGE_FOTA] ( 3601): stFSInfo.enState             : 0x00000000
E/[LGE_FOTA] ( 3601): stFSInfo.uiFilePackageOffset : 0xa0ac37d4
E/[LGE_FOTA] ( 3601): stFSInfo.uiFilePackageSize   : 0xa0ac37f4
E/[LGE_FOTA] ( 3601): stFSInfo.uiResult            : 0x00000000
E/[LGE_FOTA] ( 3601): stPkgInfo.enPackageType      : 0x00000000
E/[LGE_FOTA] ( 3601): stPkgInfo.uiSize             : 0x00000000
E/[LGE_FOTA] ( 3601): stPkgInfo.uiWrittenAddr      : 0x00000000
E/[LGE_FOTA] ( 3601): stPkgInfo.uiWrittenSize      : 0x00000000
E/[LGE_FOTA] ( 3601): stPkgInfo.szPackagePath      : 
E/[LGE_FOTA] ( 3601): stCommand.enCommand	 		: 0x00000000
E/[LGE_FOTA] ( 3601): uiBackupBufferAddr			: 0x00000000
E/[LGE_FOTA] ( 3601): uiLanguage					: 0x00000000
E/[LGE_FOTA] ( 3601): stDebug.uiResetCount			: 0x00000000
E/[LGE_FOTA] ( 3601): stDebug.uiRetryCount			: 0x00000000
E/[LGE_FOTA] ( 3601): FOTAFS_Close 1c
E/[LGE_FOTA] ( 3601): FOTAJNI_GetConvertedUAResult : 450
E/[LGE_FOTA] ( 3601): FOTAJNI_GetUAResult : 450
D/LGDMClient( 3601): [SwUpdate.java] [getSwUpdateStatus()] : [244] : Software update result:450
D/LGDMClient( 3601): [DmAgent.java] [restartIdleSession()] : [1084] : skymymy is: iSwUpdateStatus = 450, isUpgradedByLGUP() = false
D/LGDMClient( 3601): [DmAgent.java] [clearContext()] : [1774] : [Enter] clearContext
D/ALBootInit( 3623): ====action==>android.intent.action.BOOT_COMPLETED
D/ALBootInit( 3623): Alarm ALBootInit: BOOT_COMPLETED
I/LGDMClient( 3601): [DmAgent.java] [setState()] : [1875] : Setting Agent State and State is : DmConstants.DMAgentState.mDmaState = 0
D/LGDMClient( 3601): [DmAgent.java] [clearContext()] : [1791] : [Exit] clearContext
V/LGDMClient( 3601): [DmClientController.java] [handleMessage()] : [181] : DmClientController: run() - msg.what=33
D/LGDMClient( 3601): [DmClientController.java] [stopService()] : [408] : stopDownloadService(), DownloadService will be stopped in order to follow the end of DmClientController
W/ContextImpl( 3601): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 com.lge.lgdmsclient.dmclient.controller.DmClientController.stopService:412 com.lge.lgdmsclient.dmclient.controller.DmClientController.clearController:383 com.lge.lgdmsclient.dmclient.controller.DmClientController.access$200:68 
D/LGDMClient( 3601): [DmDownloadService.java] [onDestroy()] : [117] : DmDownloadService.onDestroy()
I/ALProvider( 3623): delete where======= time <= 1457596437753  and  aindex > 0
I/ActivityManager(  853): Killing 3365:com.android.providers.partnerbookmarks/u0a71 (adj 15): empty #11
D/Alarms  ( 3623):  --- disableExpiredAlarms!!! isBooting : true
,D/Alarms  ( 3623): count ===>0
D/Alarms  ( 3623): snoozeActivating scount==>0
D/Alarms  ( 3623): [setNextAlert] start
D/Alarms  ( 3623): [setNextAlert] (1)
,D/Alarms  ( 3623):  minTime  = 0
D/Alarms  ( 3623):  -- OK multi -- 0
E/jeny.kim( 3623): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 3623): [setNextAlert]setNextAlert temp_AlarmLinkText + 
W/libprocessgroup(  853): failed to open /acct/uid_10071/pid_3365/cgroup.procs: No such file or directory
I/CommonUtil( 3623): BUILD Operator: OPEN
,D/Alarms  ( 3623): broadcastToWidgetProvider : false
D/Alarms  ( 3623): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider(  853): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,W/BackupManagerService(  853): dataChanged but no participant pkg='com.android.providers.settings' uid=10010
D/CommonUtil( 3623): Enter deleteUnnecessaryToneItem() enter excepted tone uri value is null, preferparent value is  ALARM
,D/CommonUtil( 3623): deleteUnnecessaryToneItem() -> Alarm Surviv Count is 0
D/CommonUtil( 3623): Exit deleteUnnecessaryToneItem()
I/CommonUtil( 3623): BUILD Country: EU
,I/TimerReceiver( 3623): onReceiveIntent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.lge.clock/.timer.TimerReceiver (has extras) }
D/TimerReceiver( 3623): onReceive() : android.intent.action.BOOT_COMPLETED
I/TimerReceiver( 3623): setTimerDone
D/TimerObj( 3623): --------------------- getTimersFromSharedPrefs
V/TimerObj( 3623): --------------------- timers list is empty
I/ActivityManager(  853): Start proc com.lge.appbox.client:SingleBinaryService for broadcast com.lge.appbox.client/com.lge.appbox.singlebinary.SimChangeReceiver: pid=3657 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3384:com.lge.eula/1000 (adj 15): empty #11
I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 22.414ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 20.562ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 22.586ms
,W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_3384/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 3657): AppBoxApplication onCreate()
,D/AppUp4:SingleBinary( 3657): /cust/OPEN_EU/config/app-enabled-conf.json is selected!!
,D/AppUp4:SingleBinary( 3657):  Starting isFingerChanged 
I/ActivityManager(  853): Start proc com.lge.appbox.client for content provider com.lge.appbox.client/com.lge.appbox.databases.AppBoxContentProvider: pid=3677 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  853): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService(  853): Message: 2
,D/WifiServiceImplEx(  853): setWifiEnabled: false pid=3116, uid=10317, package= com.example.hello, App Lable : HelloWorld
D/WifiService(  853): setWifiEnabled: false pid=3116, uid=10317
I/jxcore-log( 3116): ****TEST TOOK:  5070  ms ****
I/jxcore-log( 3116): 
I/jxcore-log( 3116): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3116): 
I/AppUp4:AppBoxCP( 3677): onCreate
,W/AppUp4:DB( 3677):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 3677):  setFingerPrint start
I/AppUp4:DB( 3677):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 3677):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 3677):  SDK version = 0
I/AppUp4:DB( 3677):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 3677): AppBoxApplication onCreate()
D/AppUp4:SingleBinary( 3657):  The value of isFingerChanged null
,D/AppUp4:SingleBinary( 3657): Device : jagnm
D/AppUp4:SingleBinary( 3657): First Boot - ignore boot completed
D/AppUp4:NTCodeSingleBinary( 3657): Starting isFingerChanged 
D/AppUp4:NTCodeSingleBinary( 3657): The value of isFingerChanged lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,D/AppUp4:SingleBinary( 3657): Device : jagnm
D/AppUp4:SingleBinary( 3657): Config file is not exist - nothing
I/ActivityManager(  853): Killing 3316:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10018/pid_3316/cgroup.procs: No such file or directory
,I/AppUp4:SDKReflector( 3677): +myUserId : 0
D/AppUp4:BootUpPollingReceiver( 3677): onReceive on user ID : 0
V/AppUp4:FotaPlusService( 3677):  isFotaPlusTriedOnce : true
D/AppUp4:BootUpPollingReceiver( 3677): Starting getSdkVersion 
D/AppUp4:BootUpPollingReceiver( 3677): SDK version is : 0
,D/AppUp4:BootUpPollingReceiver( 3677): currentSdkVersion : 0
D/AppUp4:BootUpPollingReceiver( 3677): isSdkVersionChanged : true
V/AppUp4:FotaPlusService( 3677):  setFotaPlusCompleted : false
D/AppUp4:BootUpPollingReceiver( 3677): isFotaPlusNeeded : true
D/AppUp4:BootUpPollingReceiver( 3677): Fota Plus already tried once, show notification
,V/NotificationService(  853): enqueueNotificationInternal: pkg=com.lge.appbox.client id=22319582 notification=Notification(pri=0 contentView=null vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE)
D/ZenLog  (  853): intercepted: 0|com.lge.appbox.client|22319582|null|10011,none
V/NotificationService(  853): pkg=com.lge.appbox.client canInterrupt=false intercept=true
I/NotificationServiceEx(  853): LED remove() : mLights=0|com.lge.appbox.client|22319582|null|10011
D/NotificationServiceEx(  853): updateLightListLocked :r=0|com.lge.appbox.client|22319582|null|10011, action=2
D/NotificationServiceEx(  853): notification=Notification(pri=0 contentView=null vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE)
D/AppUp4:BootUpPollingReceiver( 3677): isFotaPlusRunning after : true
D/AppUp4:BootUpPollingReceiver( 3677):  installPreloadedValuePackIfNeeded 
D/AppUp4:BootUpPollingReceiver( 3677):  file is : /system/apps/bootup
D/AppUp4:BootUpPollingReceiver( 3677): file false
D/AppUp4:BootUpPollingReceiver( 3677): [BootUpPollingReceiver] No preload installation.
,D/SmartCoverUpdateMonitor( 1330): onNotificationPosted() : StatusBarNotification(pkg=com.lge.appbox.client user=UserHandle{0} id=22319582 tag=null score=0 key=0|com.lge.appbox.client|22319582|null|10011: Notification(pri=0 contentView=com.lge.appbox.client/0x1090079 vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE))
D/SmartCoverUpdateMonitor( 1330): onNotificationPosted() !qcn.isEnableToShowNotification()
D/AppUp4:dwnld( 3677): [removeAllIncompletedDownload] ... 
,V/AppUp4:BootUpPollingReceiver( 3677): [BootUpPollingReceiver] start bootup Polling.
,I/[SystemUI]PhoneStatusBar( 1369): updateMediaMetaData(false): mMediaMetadata = null
,D/AppUp4  ( 3677): getUpdatePollingPeriod
,D/AppUp4  ( 3677): getUpdatePollingPeriod
,D/AppUp4:BackgroundPollingService ( 3677): register polling alarm when : 2016/03/10 21:37:46
D/AppUp4:LightWeightPollingService ( 3677):  [buildRemotePollingIntent]
D/AppUp4:LightWeightPollingService ( 3677): This means remote config is N, so skip it
,I/ActivityManager(  853): Killing 3426:com.android.keychain/1000 (adj 15): empty #11
I/CalendarProvider2( 3574): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3574): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_3426/cgroup.procs: No such file or directory
I/ActivityManager(  853): Killing 3342:com.lge.hiddenmenu/1000 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_3342/cgroup.procs: No such file or directory
,D/AndroidRuntime( 3697): 
D/AndroidRuntime( 3697): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3697): CheckJNI is OFF
,I/ActivityManager(  853): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3707 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/MmsConfig( 3209): isNotAllowedSms: currentUser:0
D/MmsConfig( 3209): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3209): isUserMode:false
D/SmsReceiverService( 3209): handleMessage isUserMode:false
W/ResourcesManager( 3209): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/SmsReceiverService( 3209): handleMessage action: android.intent.action.BOOT_COMPLETED error: 0
W/ResourcesManager( 3707): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 3707): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 3707): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 3707): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@290ffe5b, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@30b136f8, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@360427d1, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@208cd236, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@fc62537, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@163ecaa4, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@3952700d, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3d4bdbc2, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@304dddd3, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2eefed10, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@c30009, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@cfff20e, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@98e842f, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@294eca3c, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3e9293c5, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1ccd211a, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3789344b, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@305c4e28, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@120da741, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@360c34e6, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@b34ca27, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@1c3c24d4, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@28cc767d, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@cd6b972, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@419e1c3, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1a0ba40, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@37aefd79, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@b52fabe, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@7aed71f, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@bf73a6c, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@798f835, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@5c004ca, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@3273c63b, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@e539158, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@11ede2b1, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@2341a396, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1ece8b17, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@371c6b04, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@28ccf8ed, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@76c6322, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3da6c1b3, lg_preferences_recent_time,zones=com.android.calendar.adaptation.PreferenceKey$KeyData@12773370, lg_p
,D/GeneralPreferenceUtils( 3707): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 3707): [init]
I/Config  ( 3707): LGCalendar ver.4.40.17
I/Config  ( 3707): start check model
I/Config  ( 3707): start check native_ca
I/Config  ( 3707): Config Operator=OPEN, Country=EU
D/Config  ( 3707): [setDefaultValuesToPref]
D/Config  ( 3707): [parseProfiles]
D/ProfilesParser( 3707): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 3707): [debug_displayParseInfos] profile.operator = null
D/Config  ( 3707): [updateProfiletoCountryInfo]
,D/GeneralPreference( 3707): [checkAndMigrateOldPreference]
D/AlertReceiver( 3707): onReceive: a=android.intent.action.BOOT_COMPLETED Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.calendar/.alerts.AlertReceiver (has extras) }
,I/InitNotificationRingtoneService( 3707): Start InitializeAlertRingtoneService.onHandleIntent
,I/ActivityManager(  853): Start proc com.android.settings for broadcast com.android.settings/.lockscreen.LockSettingsReceiver: pid=3738 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/AlertUtils( 3707): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
D/AndroidRuntime( 3697): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  853): Force stopping com.example.hello appid=10317 user=-1: uninstall pkg
I/ActivityManager(  853): Killing 3116:com.example.hello/u0a317 (adj 0): stop com.example.hello
,W/ResourcesManager( 3738): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3738): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 3738): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 3738): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 3738): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/WindowState(  853): WIN DEATH: Window{3330564f u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  853): Focus left window: Window{3330564f u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  853): Window went away: Window{3330564f u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings(  853): Skipping PackageSetting{9693531 com.test.thalitest/10316} due to missing metadata
,I/IndexDatabaseHelper( 3738): Using schema version: 115
,I/IndexDatabaseHelper( 3738): Index is fine
W/HolidayIntentService( 3707): onHandleIntent
W/ActivityManager(  853): Force removing ActivityRecord{181cca13 u0 com.example.hello/.MainActivity t224}: app died, no saved state
,D/HolidayDataLoader( 3707): readJsonAsset : holiday.json
D/AlertService( 3707): 0 Action = android.intent.action.BOOT_COMPLETED
W/ActivityManager(  853): Spurious death for ProcessRecord{b78a43e 3116:com.example.hello/u0a317}, curProc for 3116: null
I/ActivityManager(  853): Force stopping com.example.hello appid=10317 user=0: pkg removed
,D/AlertService( 3707): [Widget]com.android.calendar.widget.CalendarAppWidgetProvider enabled
D/Feature ( 3707): MemoryLevel - 5:NOT_DEF:Not UI4.2 LOS
D/AlertService( 3707): [Widget]com.android.calendar.widget.MonthWidgetProvider enabled
D/AlertService( 3707): [Widget]com.android.calendar.widget.WeekWidgetProvider enabled
I/[LGHome]EVENT( 1907): [Launcher.java:5203:onStart()]onStart
,D/KeyguardModel( 1369): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1763): Ignoring removeGeofence because network location is disabled.
W/System.err( 3521): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,I/QCNEJ   ( 1870): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[LGHome]EVENT( 1907): [Launcher.java:776:onResume()]onResume
W/System.err( 3521): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3521): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3521): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3521): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3521): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3521): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3521): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3521): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3521): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,I/InputReader(  853): Reconfiguring input devices.  changes=0x00000010
D/administrator(  853): Handling package changes for user 0
,I/ActivityManager(  853): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=3766 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
D/AlertService( 3707): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/AlertUtils( 3707): [getCalendarNotiSoundURIFromCursor] getCount()= 21
E/HolidayIntentService( 3707): onHandleIntent:holiday data empty
,I/[SystemUI]QSlideListController( 1369): onReceive = android.intent.action.PACKAGE_REMOVED
,I/[LGHome]LGActivityUtil( 1907): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1907): [Launcher.java:929:onResume()]onResume end
I/Activity( 1907): Activity.onPostResume() called 
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1369): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1369): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,W/[LGHome]LGWallpaperInfo( 1907): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1907): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/SystemUI[Framework](  853): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  853): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  853): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  853): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@38ca66c8,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  853): Focus entered window: Window{17cf33bd u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 1907): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/NotificationService(  853): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  853): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1907): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1907): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/JobSchedulerService(  853): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 1907): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1907): [setNavigationBarColor] color=0x 0
I/art     ( 1816): CheckpointMarkThreadRoots callback created = 0xaaf02c00
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
,D/TaskPersister(  853): removeObsoleteFile: deleting file=224_task.xml
I/AlertUtils( 3707): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3707): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
D/AlarmScheduler( 3707): No events found starting within 1 week.
D/UsbSettingsReceiver( 3738): [AUTORUN] onReceive() : action = android.intent.action.BOOT_COMPLETED
D/UsbSettingsReceiver( 3738): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3738): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 3738): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/art     ( 1816): CheckpointMarkThreadRoots callback created = 0xaaf491c0
,W/InputMethodManagerService(  853): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/AlertUtils( 3707): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/LockScreenSettings( 3766): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
W/InputMethodManagerService(  853): Got RemoteException sending setActive(false) notification to pid 3116 uid 10317
D/UsbSettingsReceiver( 3738): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,I/AlertUtils( 3707): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3707): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
D/KeyguardModel( 1369): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1369): createShortcutInfo...
,D/KeyguardModel( 1369): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
I/AlertUtils( 3707): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
W/PackageManager( 1369): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1369): createShortcutInfo...
I/AlertUtils( 3707): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3707): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
W/ResourcesManager( 1369): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
I/HotwordRecognitionRnr( 1970): Starting hotword detection.
D/UsbSettingsControl( 3738): [AUTORUN] setTetherStatus() : status=false
W/PackageManager( 1369): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/UsbSettingsReceiver( 3738): [AUTORUN] onReceive() : android.intent.action.BOOT_COMPLETED
D/UsbSettingsReceiver( 3738): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3738): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 3738): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/MicrophoneInputStream( 1970): mic_starting com.google.android.apps.gsa.speech.audio.u@3c7b5e9f
V/AudioRecord( 1970): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 1970): set(): mSessionId 22
D/KeyguardModel( 1369): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1369): createShortcutInfo...
V/AudioPolicyManager(  281): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
V/AudioPolicyManager(  281): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  281): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  281): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546dd40)
V/audio_hw_primary(  281): adev_open_input_stream: exit
V/AudioFlinger(  281): openInput_l() openInputStream returned input 0xb546dd40, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  281): openInput_l() created record thread: ID 23 thread 0xb3855000
V/AudioSystem(  281): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1369): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem(  853): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1970): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 2748): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1782): ioConfigChanged() event 3, ioHandle 23
,I/AudioFlinger(  281): AudioFlinger's thread 0xb3855000 ready to run
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
W/ResourcesManager( 1369): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1369): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1369): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
V/AudioPolicyService(  281): AudioCommandThread() adding update audio port list
V/AudioSystem( 3209): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  281): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioFlinger(  281): openRecord() lSessionId: 22 input 23
D/StoreModeReceiver( 3738): intent.getAction() : android.intent.action.BOOT_COMPLETED
D/StoreModeReceiver( 3738): sim state :null
D/StoreModeReceiver( 3738): Back LED don't supported.
I/AlertUtils( 3707): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioFlinger(  281): RecordThread: loop stopping
I/Timeline( 1907): Timeline: Activity_idle id: android.os.BinderProxy@188cc594 time:51731
V/AudioFlinger(  281): getOrphanEffectChain_l session 22 index -2
,I/SystemUI[Framework](  853): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
W/PhoneWindowManagerEx(  853): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  853): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  853): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@38ca66c8,  pkg=WindowManager.LayoutParams
I/[SystemUI]NavigationThemeResource( 1369): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1369):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1369): , Keyguard show=false, IME shown=false, Panel expanded=false
I/SystemUI[Framework](  853): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/AudioFlinger(  281): acquiring 22 from 1970, for -1
V/AudioFlinger(  281):  added new entry for 22
V/AudioRecord( 1970): start, sync event 0 trigger session 0
V/AudioRecord( 1970): mAudioRecord->start()
V/AudioFlinger(  281): RecordHandle::start()
V/AudioFlinger(  281): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  281): startInput() module primary->input primary(23)
V/AudioPolicyManager(  281): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  281): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  281): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  281): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  281): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  281): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  281): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  281): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  281): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  281): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  281): in_set_parameters: exit: status(0)
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3855000
V/AudioFlinger::PatchPanel(  281): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  281): createAudioPatch() added new patch handle 24 halHandle 0
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyManager(  281): setInputDevice() createAudioPatch returned 0 patchHandle 24
V/AudioPolicyManager(  281): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  281): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  281): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyService(  281): AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
V/AudioPolicyService(  281): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing set parameters string hotword_active=1, io 23
V/AudioFlinger(  281): setParameters(): io 23, keyvalue hotword_active=1, calling pid 281
V/AudioFlinger(  281): ThreadBase::setParameters() hotword_a,ctive=1
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
I/AlertUtils( 3707): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
D/BarTransitions( 1369): draw background and invalidate : color = f6000000
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/BarTransitions( 1369): draw background and invalidate : color = f2e8e8e8
I/AlertUtils( 3707): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  281): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  281): in_set_parameters: exit: status(0)
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3855000
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyManager(  281): AudioPolicyManager::startInput() input source = 1999
D/KeyguardModel( 1369): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1369): createShortcutInfo...
I/MicrophoneInputStream( 1970): mic_started com.google.android.apps.gsa.speech.audio.u@3c7b5e9f
V/msm8974_platform(  281): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  281): start_input_stream: enter: stream(0xb546dd40)usecase(7: audio-record)
V/voice   (  281): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  281): start_input_stream: usecase(7)
E/audio_hw_primary(  281): select_devices: enter and usecase(7)
V/msm8974_platform(  281): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  281): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  281): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  281): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  281): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  281): enable_snd_device: enter  144
D/hardware_info(  281): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  281): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  281): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  281): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  281): ACDB -> send_adm_topology
D/ACDB-LOADER(  281): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  281): ACDB -> send_asm_topology
D/ACDB-LOADER(  281): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  281): ACDB -> send_audtable
D/ACDB-LOADER(  281): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  281): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  281): ACDB -> send_audvoltable
D/ACDB-LOADER(  281): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  281): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  281): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  281): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  281): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  281): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  281): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  281): enable_audio_route: apply mixer and update path: audio-record
,V/audio_hw_primary(  281): enable_audio_route: exit
D/audio_hw_primary(  281): select_devices: done
V/audio_hw_primary(  281): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
D/KeyguardModel( 1369): handleShortcutListChanged...
I/AlertUtils( 3707): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
V/SettingsProvider(  853): call_put(system:emotional_led_back_led=0) for 0 calling package = com.android.settings
D/KeyguardModel( 1369): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1369): createShortcutInfo...
V/audio_hw_primary(  281): start_input_stream: exit
V/SettingsProvider(  853): call_put(system:emotional_led_back_incoming_call=0) for 0 calling package = com.android.settings
V/SettingsProvider(  853): call_put(system:emotional_led_back_alarm=0) for 0 calling package = com.android.settings
D/KeyguardModel( 1369): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1369): createShortcutInfo...
V/SettingsProvider(  853): call_put(system:emotional_led_back_missed_call=0) for 0 calling package = com.android.settings
V/SettingsProvider(  853): call_put(system:emotional_led_back_missed_messages=0) for 0 calling package = com.android.settings
,W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1369): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1369): createShortcutInfo...
V/SettingsProvider(  853): call_put(system:emotional_led_back_missed_emails=0) for 0 calling package = com.android.settings
V/SettingsProvider(  853): call_put(system:emotional_led_back_calendar_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  853): call_put(system:emotional_led_back_voice_recording=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  853): call_put(system:emotional_led_back_camera_timer_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  853): call_put(system:emotional_led_back_camera_face_detecting_noti=0) for 0 calling package = com.android.settings
I/AlertUtils( 3707): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
V/SettingsProvider(  853): call_put(system:notification_light_pulse_back=0) for 0 calling package = com.android.settings
I/ActivityManager(  853): Killing 3453:com.google.android.onetimeinitializer/u0a8 (adj 15): empty #11
,I/AlertUtils( 3707): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
D/StoreModeReceiver( 3738): SystemProperty Default brightness value [0-255] : 143
D/StoreModeReceiver( 3738): Default brightness[0-255] : 143
I/AlertUtils( 3707): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
W/ResourcesManager( 3738): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/StoreModeReceiver( 3738): Default Screen off timeout value : 30000
D/StoreModeReceiver( 3738): SystemProperty Default brightness Mode value[true/false] : false
I/AlertUtils( 3707): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
D/StoreModeReceiver( 3738): BRIGHTNESS_MODE - 0
D/StoreModeReceiver( 3738): Default brightness Mode [0/1] : 0
D/StoreModeReceiver( 3738): Default NIGHT_MODE : 0
D/StoreModeReceiver( 3738): Set MaxBrightness : 255
E/PhoneInterfaceManager( 1782): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/StoreModeReceiver( 3738): getPhoneNumber is empty
D/StoreModeReceiver( 3738): go to StoreModeCheck()
D/StoreModeReceiver( 3738): isStoremode not null
,D/PhoneInterfaceManager( 1782): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
V/SettingsProvider(  853): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
,D/StoreModeReceiver( 3738): product_name : jagnm_global_com
D/StoreModeReceiver( 3738): Store mode start!
V/SettingsProvider(  853): call_put(system:shop_mode=1) for 0 calling package = com.android.settings
V/SettingsProvider(  853): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
I/PowerManagerService(  853): ALS enabled for SRE
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=120000 (in 68138 ms)
D/StoreModeReceiver( 3738): setBrightness() : NoMultiALC=255
W/ContextImpl( 3738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.StoreModeReceiver.sendBroadcast:500 com.android.settings.StoreModeReceiver.setMode:473 
I/HotwordWorker( 1970): onReady
,D/KeyguardModel( 1369): handleShortcutListChanged...
W/libprocessgroup(  853): failed to open /acct/uid_10008/pid_3453/cgroup.procs: No such file or directory
I/AlertUtils( 3707): set default noti to content://media/internal/audio/media/38
,V/SettingsProvider(  853): call_put(system:screen_brightness_mode=0) for 0 calling package = com.android.settings
I/InitNotificationRingtoneService( 3707): End InitializeAlertRingtoneService.onHandleIntent
D/SettingsProvider(  853): Set screen_off_timeout in entry value : 120000
V/SettingsProvider(  853): call_put(system:screen_off_timeout=120000) for 0 calling package = com.android.settings
V/SettingsProvider(  853): call_put(system:screen_brightness=255) for 0 calling package = com.android.settings
,V/SettingsProvider(  853): call_put(system:check_night_mode=0) for 0 calling package = com.android.settings
,D/SettingBootReceiver( 3738): onReceive
D/SettingBootReceiver( 3738): Boot Completed intent received, action=android.intent.action.BOOT_COMPLETED
I/ActivityManager(  853): Killing 3473:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #11
W/ResourcesManager(  853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/SettingBootReceiver( 3738): setStyle()
D/SettingBootReceiver( 3738): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 3738): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 3738): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 3738): SettingStyle=1
D/SettingBootReceiver( 3738): setAccountMenu()
,D/TAG     ( 3738): setKidsMode
D/TAG     ( 3738): mIsOwner, setKidsMode
D/SettingBootReceiver( 3738): setAccountMenu()
I/art     (  853): Explicit concurrent mark sweep GC freed 20649(1289KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/34MB, paused 3.383ms total 448.236ms
D/YSY     ( 3738): not support Quiet mode notification
D/AndroidRuntime( 3697): Shutting down VM
,W/libprocessgroup(  853): failed to open /acct/uid_10016/pid_3473/cgroup.procs: No such file or directory
I/[SystemUI]LGBootReceiver( 1369): onReceive = android.intent.action.BOOT_COMPLETED
I/Timeline(  853): Timeline: Activity_windows_visible id: ActivityRecord{bb90760 u0 com.lge.launcher2/.Launcher t223} time:52023
,I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.statusbar.bootcompleted
I/[SystemUI]PhoneStatusBar( 1369): got ACTION_STICKY_BOOT_COMPLETED
I/BOOT    ( 1369): got ACTION_STICKY_BOOT_COMPLETED
V/SettingsProvider(  853): call_put(system:gentle_vibration_status=1) for 0 calling package = com.android.settings
,V/SettingsProvider(  853): call_put(system:smart_ringtone=0) for 0 calling package = com.android.settings
,I/ActivityManager(  853): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3796 uid=10111 gids={50111, 9997, 1028, 3003} abi=armeabi-v7a
W/ResourceType(  853): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,D/SettingBootReceiver( 3738): timezoneID is null
I/SettingBootReceiver( 3738): disable au
I/TAG     ( 3738): disable WirelessSettingsActivity
D/LCardEmulationManager( 1816): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1816): getDefaultRoute
I/[LGHome]EVENT( 1907): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/TAG     ( 3738): disable SKTPhoneMode
,D/SettingBootReceiver( 3738): [Nightmode] Enter receiver
,D/SettingBootReceiver( 3738): [Nightmode] BOOT_COMPLETED
D/NightModeInfo( 3738): [Nightmode] setNightNodeTabSettings
D/NightModeInfo( 3738): [Nightmode] getAlreadyNightModeDB() : 0
D/NightModeInfo( 3738): [Nightmode] getUserBrightnessChange() : 0
D/NightModeInfo( 3738): [Nightmode] getUserBrightnessChangeNoNight() : 0
V/SettingsProvider(  853): call_put(system:already_night_mode=0) for 0 calling package = com.android.settings
V/SettingsProvider(  853): call_put(system:user_change_brightness=0) for 0 calling package = com.android.settings
V/SettingsProvider(  853): call_put(system:user_change_brightness_no_night=0) for 0 calling package = com.android.settings
V/SettingsProvider(  853): call_put(system:night_mode_enabled=0) for 0 calling package = com.android.settings
D/NightModeInfo( 3738): [Nightmode] setTabNightCheck : 0
,V/SettingsProvider(  853): call_put(system:save_tab_night_check=0) for 0 calling package = com.android.settings
I/ActivityManager(  853): Killing 3496:com.lge.email/u0a21 (adj 15): empty #11
D/NightModeInfo( 3738): [Nightmode] cancelPendingIntent
W/libprocessgroup(  853): failed to open /acct/uid_10021/pid_3496/cgroup.procs: No such file or directory
,V/DownloadManager( 3233): Received broadcast intent for android.intent.action.BOOT_COMPLETED
D/NightModeInfo( 3738): [Nightmode] requestPendingIntent
D/NightModeInfo( 3738): [Nightmode] setAlarmStart~!!~!!~!!
V/DownloadManager( 3233): DownloadService onCreate
D/NightModeInfo( 3738): [Nightmode] currentHour > 6
D/NightModeInfo( 3738): [Nightmode] currentHour > 6
I/DownloadManager( 3233): in removeSpuriousFiles
I/NightModeInfo( 3738): JW getStartTime201603110000
D/NightModeInfo( 3738): [Nightmode] setAlarmEnd~!!~!!~!!
V/DownloadManager( 3233): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/NightModeInfo( 3738): [Nightmode] currentHour > 6
V/DownloadManager( 3233): created cursor android.database.sqlite.SQLiteCursor@b34ca27 on behalf of 3233
I/NotificationManager( 3233): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/NightModeInfo( 3738): [Nightmode] currentHour > 6
I/NightModeInfo( 3738): JW getEndTime201603110600
D/NightModeInfo( 3738): [Nightmode] currentHour > 6
I/NightModeInfo( 3738): getStartTime201603110000
I/DownloadManager( 3233): in trimDatabase
D/NightModeInfo( 3738): [Nightmode] currentHour > 6
V/DownloadManager( 3233): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/NightModeInfo( 3738): getEndTime201603110600
V/DownloadManager( 3233): created cursor android.database.sqlite.SQLiteCursor@1c3c24d4 on behalf of 3233
D/jw      ( 3738): Only VZW Supported end return
,V/DownloadManager( 3233): DownloadService onStartCommand
V/DownloadManager( 3233): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/MediaScannerReceiver( 3233): [MediaScanner] ACTION_BOOT_COMPLETED scan INTERNAL_VOLUME, EXTERNAL_VOLUME
V/DownloadManager( 3233): created cursor android.database.sqlite.SQLiteCursor@419e1c3 on behalf of 3233
D/MediaScannerService( 3233): [MediaScanner] start scanning volume internal: [/system/media, /oem/media, /cust/OPEN_EU/media]
V/LGMediaProvider( 3233): insertInternal: content://media/none/media_scanner, initValues=volume=internal
,D/MediaScannerService( 3233): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///system/media
D/MtpService( 3233): updating state; isCurrentUser=true, mMtpLocked=false
I/MusicBrowser( 2748): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///system/media flg=0x10 }}
D/MtpService( 3233): addStorageLocked 65537 /storage/emulated/0
D/WiseScreenService( 1852): [OnBootReceiver.java:24:onReceive()] iKeepScreenOn: 0
I/MusicBrowser( 2748): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
,D/WiseScreenService( 1852): [OnBootReceiver.java:28:onReceive()] iSmartVideo: 0
D/MusicBrowser( 2748): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
E/MtpStorageEx( 3233): setAccessCapability false
W/ContextImpl( 1852): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.lge.keepscreenon.OnBootReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
D/MtpService( 3233): updating state; isCurrentUser=true, mMtpLocked=false
D/MediaScannerEx( 3233): [MediaScanner] scanDirectories()[0] = /system/media
D/MediaScannerEx( 3233): [MediaScanner] scanDirectories()[1] = /oem/media
D/MediaScannerEx( 3233): [MediaScanner] scanDirectories()[2] = /cust/OPEN_EU/media
,I/art     ( 3233): Thread[1,tid=3233,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
E/MediaProfilesEx-JNI( 3233): register_com_lge_media_MediaProfilesEx
E/MediaRecorderEx-JNI( 3233): register_com_lge_media_MediaRecorderEx
D/AudioSystemEx( 3233): register_com_lge_media_LGAudioSystem
,E/SurfaceControlEx( 3233): register_com_lge_view_SurfaceControlEx
I/art     ( 3233): Thread[1,tid=3233,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/LGMtpDatabaseJNI( 3233): register_android_mtp_LGMtpDatabase
I/ActivityManager(  853): Start proc com.lge.voicerecorder for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver: pid=3821 uid=10034 gids={50034, 9997, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
D/LGMtpServerJNI( 3233): register_android_mtp_LGMtpServer
I/art     ( 3233): Thread[1,tid=3233,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
E/MediaPlayerEx-jni( 3233): register_com_lge_view_MediaPlayerEx
I/art     ( 3233): Thread[1,tid=3233,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/        ( 3233): register_com_lge_emoji_EmojiUtil
E/LGMtpDatabaseJNI( 3233): android_mtp_LGMtpDatabase_setup
,D/MtpService( 3233): starting MTP server in PTP mode
D/LGMtpServer( 3233): LGMtpServer
D/LGMtpServerJNI( 3233): android_mtp_LGMtpServer_setup
,D/WeatherService( 2742): 2 : TimeTick Intent has been received, Time(hour:min:sec) 8:54:0
D/WeatherService( 2742): 2 : TimeTick Intent And Screen On
D/WeatherService( 2742): 2 : SDK version : 21
W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2742): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2742): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2742): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2742): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2742): 2 : This is isUpdating : false
D/WeatherService( 2742): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2742): 2 : buildUpdate, appWidgetId: 2
D/MtpService( 3233): addStorageLocked 65537 /storage/emulated/0
E/MtpStorageEx( 3233): setAccessCapability false
,D/WeatherTheme( 2742): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2742): 2 : Fixed theme : optimus
D/MtpServerEx( 3233): ANR FIX - addStorage!
D/LGMtpServerJNI( 3233): android_mtp_LGMtpServer_run
D/WeatherReflect( 2742): 2 : Map key string is -2
V/DownloadManager( 3233): DownloadService onDestroy
D/lim     ( 2742): 2 : time = 08:54
I/WeatherReflect( 2742): Model Name : LG-D722
D/WeatherTheme( 2742): 2 : Different view - status_min_formatted : 53 != 54
D/WeatherTheme( 2742): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2742): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2742): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2742): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2742): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2742): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
,I/[SystemUI]Clock( 1369): called onTimeUpdated()
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
,I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
E/SQLiteLog( 3521): (3850) statement aborts at 11: [INSERT INTO t010(f004,f002,f003) VALUES (?,?,?)] disk I/O error
V/MediaScannerClient( 3233): [MediaScanner]setLocale: = en_US
D/Weather4x2_optimus( 2742): [[[[[[Theme package!!]]]]]] RemoteViews are created 2

```
