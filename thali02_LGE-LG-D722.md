#### Test 558877588826def_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/UEI.SmartControl( 6284): --- Selecting new region: 2
I/UEI.SmartControl( 6284): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6284): Platform has CIR...
D/UEI.SmartControl( 6284): NO CIR support, need to check package...
I/UEI.SmartControl( 6284): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6284): QS Service created
--------- beginning of system
W/ActivityManager(  948): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/UEI.SmartControl( 6284): QS start get config
I/Gmail   ( 6267): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 6284): Loading JNI Libs...
D/UEI.SmartControl( 6284):  configuring local db...
W/GAV2    ( 6267): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
I/art     (  948): Explicit concurrent mark sweep GC freed 21321(1025KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.382ms total 198.143ms
W/ActivityManager(  948): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  948): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  948): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6267): Observing account changes for notifications
E/Gmail   ( 6267): Error finding the version of the Email provider.....
E/Gmail   ( 6267): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6267): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6267): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6267): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6267): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6267): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6267): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6267): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6267): We do not support migrating this version of the Email provider.
I/Gmail   ( 6267): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 6284):  ---- Has DB8: true
I/AudioManager( 5199): getMode name:com.lge.qremote
I/AudioManager( 5199): getMode name:com.lge.qremote
D/UEI.SmartControl( 6284): QS start statue = true Error code = 0
D/UEI.SmartControl( 6284): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6284): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6284): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6284): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6284): IrrcClient ++ 
D/irrcClient( 6284): getIrrcService ++ 
D/irrcClient( 6284): getIrrcService -- 
D/irrcClient( 6284): IrrcClient -- 
W/irrc_jni( 6284): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6284): Services init done
I/UEI.SmartControl( 6284): Device manager: loading config....
D/UEI.SmartControl( 6284): Config is loaded...
I/ActivityManager(  948): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6349 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UEI.SmartControl( 6284): QS Service init finished
D/UEI.SmartControl( 6284):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6284): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6284): QS Service version name: 0.1.73
D/UEI.SmartControl( 6284): QS Service version code: 1073
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 6284): Service requested: Control
D/UEI.SmartControl( 6284): -----IControl: 11
I/ActivityManager(  948): Killing 6061:com.google.android.setupwizard/u0a38 (adj 15): empty #11
D/UEI.SmartControl( 6284): Caller: com.lge.qremote
D/UEI.SmartControl( 6284): ------------ IControl registerCallback...
I/UEI.SmartControl( 6284): Registering callback...
D/UEI.SmartControl( 6284): -----IControl: 19
D/UEI.SmartControl( 6284): Caller: com.lge.qremote
I/UEI.SmartControl( 6284): Registering Services Ready callback...
I/UEI.SmartControl( 6284): Notify client services are ready...
D/UEI.SmartControl( 6284): -----IControl: 8
D/UEI.SmartControl( 6284): Caller: com.lge.qremote
W/libprocessgroup(  948): failed to open /acct/uid_10038/pid_6061/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6284): Internal service binding...
W/ResourcesManager( 6349): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/AndroidRuntime( 6331): 
D/AndroidRuntime( 6331): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6331): CheckJNI is OFF
I/Gmail   ( 6267): notifyAccountChanged
I/Gmail   ( 6267): getAccountsCursor
I/Gmail   ( 6267): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CalendarProvider2( 6349): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@39702dfc
I/Gmail   ( 6267): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6267): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/CalendarProvider2( 6349): [getOrCreateCalendarAlarmManager]
I/Gmail   ( 6267): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/CalendarProvider2( 6349): Created com.android.providers.calendar.CalendarAlarmManager@9d06c01(com.android.providers.calendar.CalendarProvider2@39702dfc)
D/CalendarProviderBroadcastReceiver( 6349): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6349): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6349): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6349): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6349): [getOrCreateCalendarAlarmManager]
I/AudioManager( 5199): getMode name:com.lge.qremote
I/AudioManager( 5199): getMode name:com.lge.qremote
I/AudioManager( 5199): getMode name:com.lge.qremote
I/Gmail   ( 6267): getAccountsCursor
D/CalendarProvider2( 6349): [IntentService] Release Lock
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CalendarProvider2( 6349): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  948): Killing 6123:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  948): failed to open /acct/uid_10011/pid_6123/cgroup.procs: No such file or directory
D/AndroidRuntime( 6331): Calling main entry com.android.commands.am.Am
I/ActivityManager(  948): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  948): setTaskToReturnTo : TaskRecord{b17fb63 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  948): setTaskToReturnTo : TaskRecord{b17fb63 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
I/Icing   ( 4290): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
D/WindowStateEx(  948): AppWindowTokenEx init.. 
D/ContextHelper(  948): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  948): Focus left window: Window{2cc1d03c u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6331): Shutting down VM
I/[LGHome]EVENT( 1881): [Launcher.java:986:onPause()]onPause
I/Icing   ( 4290): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/ActivityManager(  948): Killing 6146:com.android.gallery3d/u0a23 (adj 15): empty #11
D/SplitWindow(  948): check instance of lgWin Window{14f544d5 u0 Starting com.test.thalitest}
W/libprocessgroup(  948): failed to open /acct/uid_10023/pid_6146/cgroup.procs: No such file or directory
I/ActivityManager(  948): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6396 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1881): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1943): Closing mic
I/[LGHome]EVENT( 1881): [Launcher.java:5214:onStop()]onStop
I/MicrophoneInputStream( 1943): mic_close com.google.android.apps.gsa.speech.audio.u@39adfe
V/AudioRecord( 1943): stop()
D/AudioRecord( 1943): AudioRecord->stop()
V/AudioFlinger(  286): RecordHandle::stop()
V/AudioFlinger(  286): RecordThread::stop
I/WindowStateAnimator(  948): Starting window displayed
I/SystemUI[Framework](  948): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
V/AudioFlinger(  286): Record stopped OK
W/PhoneWindowManagerEx(  948): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  948): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  948): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  948): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@35e9461e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  948): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/AudioPolicyManager(  286): stopInput() input 17
V/AudioPolicyService(  286): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  286): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  286): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  286): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  286): ThreadBase::setParameters() routing=0
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 2
,V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb3c28000
D/audio_hw_primary(  286): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1374): draw background and invalidate : color = 10000000
D/BarTransitions( 1374): draw background and invalidate : color = c0c0c0c
V/audio_hw_primary(  286): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  286): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  286): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  286): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  286): disable_audio_route: exit
E/audio_hw_primary(  286): disable_snd_device: enter 144
D/hardware_info(  286): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  286): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  286): stop_input_stream: exit: status(0)
V/audio_hw_primary(  286): in_standby: exit:  status(0)
V/AudioFlinger(  286): RecordThread: loop stopping
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyManager(  286): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  286): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  286): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  286): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyService(  286): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  286): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  286): setParameters(): io 17, keyvalue hotword_active=0, calling pid 286
V/AudioFlinger(  286): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  286): RecordThread: loop starting
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  286): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  286): in_set_parameters: exit: status(0)
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb3c28000
V/AudioFlinger(  286): RecordThread: loop stopping
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioRecord( 1943): stop()
V/AudioRecord( 1943): stop()
V/AudioRecord( 1943): stop()
V/AudioFlinger(  286): RecordHandle::stop()
V/AudioFlinger(  286): RecordThread::stop
V/AudioPolicyManager(  286): releaseInput() 17
V/AudioPolicyManager(  286): closeInput(17)
V/AudioFlinger(  286): closeInput() 17
V/AudioSystem(  286): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  948): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  286): ThreadBase::exit
V/AudioSystem( 1374): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2110): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  286): RecordThread: loop starting
V/AudioSystem( 3215): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1753): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1943): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2007): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  286): RecordThread 0xb3c28000 exiting
V/AudioFlinger(  286): releasing 16 from 1943 for -1
D/audio_hw_primary(  286): adev_close_input_stream: enter:stream_handle(0xb546dd40)
V/AudioFlinger(  286):  decremented refcount to 0
D/audio_hw_primary(  286): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/AudioFlinger(  286): purging stale effects
V/audio_hw_primary(  286): in_standby: exit:  status(0)
V/AudioPolicyService(  286): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  286): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyManager(  286): releaseInput() exit
V/AudioFlinger(  286): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  286): removeClient_l() pid 1943, calling pid 286
I/HotwordRecognitionRnr( 1943): Hotword detection finished
I/HotwordRecognitionRnr( 1943): Stopping hotword detection.
D/sensors_hal_Time(  948): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  948): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  948): tsOffsetIs: Apps: 94915238042; DSPS: 3208714; Offset : -3008516064
D/ContextHelper( 6396): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
W/ActivityManager(  948): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager(  948): RTC_WAKEUP set : Alarm{351f72b7 type 0 when 1452515789703 com.android.providers.contacts} when 1452515789703
V/AlarmManager(  948): ELAPSED_WAKEUP set : Alarm{23e1ca24 type 2 when 60568 com.google.android.talk} when 60568
V/AlarmManager(  948): RTC_WAKEUP set : Alarm{9ae8353 type 0 when 1452688649586 com.android.vending} when 1452688649586
D/Finsky  ( 6226): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
I/WebViewFactory( 6396): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  948): android: cancelAsUser(2) by android
I/LibraryLoader( 6396): Time to load native libraries: 7 ms (timestamps 5092-5099)
I/LibraryLoader( 6396): Expected native library version number "",actual native library version number ""
D/libc-netbsd( 6226): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6226): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/WebViewChromiumFactoryProvider( 6396): Binding Chromium to main looper Looper (main, tid 1) {9d06c01}
D/libc-netbsd( 6226): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6226): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  282): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  282): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out( 6226): propertyValue:false
D/libc-netbsd( 6226): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6226): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/LibraryLoader( 6396): Expected native library version number "",actual native library version number ""
I/chromium( 6396): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6396): Initializing chromium process, singleProcess=true
W/art     ( 6396): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6396): ApplicationContext is null in ApplicationStatus
W/chromium( 6396): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6396): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6396): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6396): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6396): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6396): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6396): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6396): Remote Branch: 
I/Adreno-EGL( 6396): Local Patches: 
I/Adreno-EGL( 6396): Reconstruct Branch: 
V/AudioPolicyService(  286): registerClient() client 0xb4027080, uid 10316
D/libc-netbsd( 6226): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6226): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/BluetoothAdapterService(416728893)( 2007): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69f7cfb
D/BluetoothManagerService(  948): Message: 20
D/BluetoothManagerService(  948): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@134eb49f:true
,W/art     ( 6396): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6396): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6396): CordovaWebView is running on device made by: LGE
,W/art     ( 6396): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6396): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 6396): Activity.onPostResume() called 
,I/QCNEJ   ( 1843): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:30.247 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/OpenGLRenderer( 6396): Render dirty regions requested: true
I/OpenGLRenderer( 6396): Initialized EGL, version 1.4
D/OpenGLRenderer( 6396): Enabling debug mode 0
,D/Atlas   ( 6396): Validating map...
,D/SplitWindow(  948): check instance of lgWin Window{1cd4038f u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6396): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  948): Focus entered window: Window{1cd4038f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  948): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  948): Displayed com.test.thalitest/.MainActivity: +1s197ms
I/Timeline(  948): Timeline: Activity_windows_visible id: ActivityRecord{19606360 u0 com.test.thalitest/.MainActivity t222} time:95828
,I/Timeline( 6396): Timeline: Activity_idle id: android.os.BinderProxy@3facf6c4 time:95846
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  948): android: cancelAsUser(2) by android
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/qtaguid ( 6226): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6226): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6226): untagSocket(41) failed with errno -22
,W/BindingManager( 6396): Cannot call determinedVisibility() - never saw a connection for the pid: 6396
,D/Finsky  ( 6226): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
I/ActivityManager(  948): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6483 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  948): android: cancelAsUser(2) by android
,W/ResourcesManager( 6483): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6483): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/AlertService( 6090): Beginning updateAlertNotification
,D/AlertService( 6090): No fired or scheduled alerts
I/NotificationManager( 6090): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 6090): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6090): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6090): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6090): com.android.calendar: cancel(4) by com.android.calendar
I/MultiDex( 6483): VM with version 2.1.0 has multidex support
I/MultiDex( 6483): install
I/MultiDex( 6483): VM has multidex support, MultiDex support library is disabled.
I/NotificationManager( 6090): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6090): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6090): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6090): com.android.calendar: cancel(8) by com.android.calendar
,I/NotificationManager( 6090): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6090): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6090): com.android.calendar: cancel(11) by com.android.calendar
,I/NotificationManager( 6090): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6090): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6090): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6090): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6090): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6090): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6090): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6090): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6090): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6090): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 6090): No events found starting within 1 week.
,V/JNIHelp ( 6483): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 6226): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6226): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6226): untagSocket(41) failed with errno -22
,W/ActivityThread( 6483): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6483): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e6714db: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6483): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6483): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6483): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1733): callingUid 10006, callindPid: 1733
,D/LocationInitializer( 4290): Restart initialization of location
E/MDM     ( 1733): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
D/ChimeraCfgMgr( 6483): Reading stored module config
,W/GCoreFlp( 1733): No location to return for getLastLocation()
,W/FusedLocationProvider( 1733): location=null
D/ChimeraCfgMgr( 6483): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/JsMessageQueue( 6396): Set native->JS mode to OnlineEventsBridgeMode
,D/NativeLibraryUtils( 6483): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6483): Connecting to CarCallService...
,I/art     ( 6483): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6483): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/jxcore_app_log( 6396): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622858240
D/JX-Cordova( 6396): jxcore cordova android initializing
,I/art     ( 6226): CheckpointMarkThreadRoots callback created = 0xb042dae0
,D/CAR.SERVICE( 6483): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 6483): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6483): Creating a new PhoneAdapter instance
W/ActivityManager(  948): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,I/art     ( 6226): CheckpointMarkThreadRoots callback created = 0xb042daa0
D/CAR.TEL.PhoneAdapter( 6483): setListener: com.google.android.gms.car.dn@13f03d66
W/ActivityManager(  948): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6483): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6483): Starting CarCallService with initial phone null
,I/art     ( 6396): CheckpointMarkThreadRoots callback created = 0x9b1a24b0
D/CAR.SERVICE( 6483): Package validated; name: com.android.vending
,I/art     ( 6396): CheckpointMarkThreadRoots callback created = 0x9b1a2480
I/NotificationManager( 6483): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6226): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6226): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/art     (  948): Explicit concurrent mark sweep GC freed 14516(684KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.056ms total 176.924ms
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  948): android: cancelAsUser(2) by android
,I/qtaguid ( 6226): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6226): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6226): untagSocket(41) failed with errno -22
,W/PackageSettings(  948): Skipping PackageSetting{265836ba com.example.hello/10317} due to missing metadata
,W/ResourcesManager( 6226): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6226): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6226): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6226): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  948): RTC_WAKEUP set : Alarm{14bf29d6 type 0 when 1452688653211 com.android.vending} when 1452688653211
I/ActivityManager(  948): Process com.android.calendar (pid 6090) has died
,D/DeviceConnectionService( 1733): client connected with version: 8296000
D/Finsky  ( 6226): [765] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6226): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6226): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/NotificationManager(  948): android: cancelAsUser(2) by android
I/GAV2    ( 6267): Thread[GAThread,5,main]: No campaign data found.
,D/libc-netbsd( 6226): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6226): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6226): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6226): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  282): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  282): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  948): Process com.android.contacts (pid 6165) has died
,D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out( 6226): propertyValue:false
D/UEI.SmartControl( 6284): Internal timer expired: 1
,W/jxcore-log( 6396): Initializing JXcore engine
,W/jxcore-log( 6396): JXcore engine is ready
W/jxcore-log( 6396): Starting JXcore engine
,W/.test.thalitest( 6396): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6363]" dev="sockfs" ino=6363 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6396): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6396): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5812]" dev="sockfs" ino=5812 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6396): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6396): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6396): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[29531]" dev="sockfs" ino=29531 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 6396): Platform android
W/jxcore-log( 6396): 
W/jxcore-log( 6396): Process ARCH arm
W/jxcore-log( 6396): 
,I/ActivityManager(  948): Process com.google.android.apps.plus (pid 6201) has died
,V/AlarmManager(  948): RTC_WAKEUP set : Alarm{168ae161 type 0 when 1452688654414 com.google.android.googlequicksearchbox} when 1452688654414
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/jxcore-log( 6396): JXcore Cordova bridge is ready!
I/jxcore-log( 6396): 
,W/jxcore-log( 6396): JXcore engine is started
I/chromium( 6396): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 6396): Toggling radios to true
I/jxcore-log( 6396): 
,D/BluetoothAdapter( 6396): enable(): BT is already enabled..!
D/WifiServiceImplEx(  948): setWifiEnabled: true pid=6396, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  948): setWifiEnabled: true pid=6396, uid=10316
D/WifiServiceImplEx(  948): disconnect pid=6396, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  948): reconnect pid=6396, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 6396): Radios toggled
I/jxcore-log( 6396): 
I/jxcore-log( 6396): My device name is: LGE-LG-D722
I/jxcore-log( 6396): 
I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2779): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2779): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  948): WifiStateMachine: Leaving Connected state
D/WfdsMonitor( 1806): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,E/WifiConfigStore(  948): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LGWifiP2pService(  948): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  948): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  948): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  282): Clearing all IP addresses on wlan0
,I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/NativeCrypto( 1733): Read error: ssl=0xaaedee00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1733): SSL shutdown failed: ssl=0xaaedee00: I/O error during system call, Broken pipe
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  948): hidePasspointNotification off =false
W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  948): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  948): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  948): ignoring duplicate network state non-change
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:35.224 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/ConnectivityService(  948): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/ConnectivityService(  948): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  948): ValidatedState{ when=-2ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  948): DefaultState{ when=-17ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  948): Forcing reevaluation
I/ActivityManager(  948): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6565 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,E/WifiStateMachine(  948): Start Disconnecting Watchdog 1
I/wpa_supplicant( 2779): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiHS20(  948): hidePasspointNotification off =false
W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGWifiP2pService(  948): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  948): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  948): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:35.322 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/CommandListener(  282): Clearing all IP addresses on wlan0
D/ConnectivityService(  948): Default network via Wi-Fi disconnect. stop DSQN
,D/DSQN    (  948): disableDataServiceNotify
D/WifiHS20(  948): hidePasspointNotification off =false
W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  948): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/DSQN    (  948): stop dsqn bin
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:35.345 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
,D/WifiNetworkAgent(  948): NetworkAgent: NetworkAgent channel lost
D/WifiHS20(  948): hidePasspointNotification off =false
,W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  948): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:35.369 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  948): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:35.375 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/DhcpStateMachine(  948): StoppedState
D/DhcpStateMachine(  948): StoppedState{ when=-60ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  948): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/ConnectivityService(  948):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  948):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiServerServiceExt(  948): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  948): setSupplicantStateDISCONNECTED
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
,D/ConnectivityService(  948): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  948): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  948): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  948): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  948): Disconnected - quitting
D/WifiServerServiceExt(  948): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  948): setSupplicantStateSCANNING
D/CSLegacyTypeTracker(  948): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  948): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  948): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/Tethering(  948): MasterInitialState.processMessage what=3
D/ConnectivityService(  948): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
W/QCNEJ   ( 1843): |CORE| No family connected
V/NetworkPolicy(  948): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  948): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  948): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  948): MasterInitialState.processMessage what=3
D/ConnectivityService(  948): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  948): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  948): [LG_RESTRICTED] !!!isConnected  type  :1
D/WIFI    (  948): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkManagementService(  948): Removing idletimer
D/WIFI    (  948):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/QCNEJ   ( 1843): |CORE| No family connected
I/QCNEJ   ( 1843): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1843): |CORE| sendDefaultNwMsg: default = -1
D/TelephonyNetworkFactory-1( 1753): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/Settings(  948): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/ResourcesManager( 6565): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 6565): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6565): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6565): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6565): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/IndexDatabaseHelper( 6565): Using schema version: 115
,I/IndexDatabaseHelper( 6565): Index is fine
V/WiFiOffLoadBroadcast( 6565): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6565): MCCMNC not supported: null
I/ActivityManager(  948): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6595 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 22.186ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 22.110ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 24.270ms
,I/PCSuite ( 6595): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6595): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6595): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6565): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6565): MCCMNC not supported: null
I/PCSuite ( 6595): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6595): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6595): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6565): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6565): MCCMNC not supported: null
I/PCSuite ( 6595): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6595): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6595): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6565): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6565): MCCMNC not supported: null
,I/PCSuite ( 6595): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6595): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6595): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6565): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6565): MCCMNC not supported: null
I/ActivityManager(  948): Killing 6184:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  948): failed to open /acct/uid_10069/pid_6184/cgroup.procs: No such file or directory
,I/ActivityManager(  948): Killing 6349:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 4
,W/libprocessgroup(  948): failed to open /acct/uid_10014/pid_6349/cgroup.procs: No such file or directory
I/wpa_supplicant( 2779): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/LocSvc_java(  948): onReceive
,W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  948): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:36.484 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
,I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  948): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:36.494 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/WifiServerServiceExt(  948): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  948): setSupplicantStateASSOCIATING
,V/WiFiOffLoadBroadcast( 6565): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
I/wpa_supplicant( 2779): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  948): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  948): setSupplicantStateASSOCIATED
,D/WiFiOffLoadBroadcast( 6565): Not supported operator for automatic switch
,V/WiFiOffLoadBroadcast( 6565): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6565): MCCMNC not supported: null
W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  948): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:36.552 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:36.559 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  948): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  948): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  948): setSupplicantStateFOUR_WAY_HANDSHAKE
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/wpa_supplicant( 2779): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 2779): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 4
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
V/WiFiOffLoadBroadcast( 6565): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServiceExtension(  948): setVHTCapabilityType  : false
,D/WiFiOffLoadBroadcast( 6565): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6565): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6565): MCCMNC not supported: null
I/WifiServerServiceExt(  948): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  948): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  948): setSecurityType  : 2
,V/WiFiOffLoadBroadcast( 6565): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6565): MCCMNC not supported: null
,I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  948): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:36.634 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  948): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:36.638 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
V/WiFiOffLoadBroadcast( 6565): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  948): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  948): Got NetworkAgent Messenger
D/ConnectivityService(  948): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  948): NetworkAgent connected
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
E/WifiConfigStore(  948): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WiFiOffLoadBroadcast( 6565): MCCMNC not supported: null
E/WifiConfigStore(  948): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,V/WiFiOffLoadBroadcast( 6565): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6565): MCCMNC not supported: null
I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  282): Setting iface cfg
D/DhcpStateMachine(  948): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  948): WaitBeforeStartState
E/WifiStateMachine(  948): Start Dhcp Watchdog 2
D/WifiServerServiceExt(  948): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  948): setSupplicantStateGROUP_HANDSHAKE
I/QCNEJ   ( 1843): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-57 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:36.694 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  948): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  948): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  948): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  948): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@34f87619 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  948): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@34f87619 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  948): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  948): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  948): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/CommandListener(  282): Setting iface cfg
I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  282): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  948): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  948): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  948): setSupplicantStateCOMPLETED
D/ConnectivityService(  948): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  948): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  948): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  948): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  948): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  948): ignoring duplicate network state non-change
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  948): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:36.811 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  948): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:36.818 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
V/WiFiOffLoadBroadcast( 6565): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  948): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  948): Adding iface wlan0 to network 101
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  948): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  948): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:36.825 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 2
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiHS20(  948): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:36.838 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WiFiOffLoadBroadcast( 6565): MCCMNC not supported: null
,E/ConnectivityService(  948): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  948): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  948): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  282): netlink response contains error (File exists)
D/ConnectivityService(  948): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiOffDelayIfNotUsed(  948): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService(  948): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  948): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  948): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/Nat464Xlat(  948): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  948): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  948): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  948): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  948):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  948):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  948): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  948): Connected
D/ConnectivityService(  948):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  948):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  948): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  948):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  948): currentScore = 0, newScore = 20
D/ConnectivityService(  948):    accepting network in place of null
D/ConnectivityService(  948): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 2
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  948): [LWD] Start DNSResolver start to wait
,D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/WifiStateMachine(  948): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  948): [LWD] wait 500ms before dns check
E/ConnectivityService(  948): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  948): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  948): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/Tethering(  948): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1843): |CORE| No family connected
I/QCNEJ   ( 1843): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1843): |CORE| sendDefaultNwMsg: default = 1
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  948): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  948): [e] list.add(nai) empty : false size: 1
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/ConnectivityService(  948): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps,]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/ConnectivityService(  948): validation of new default Network = false
D/ConnectivityService(  948): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  948): enableDataServiceNotify 
D/DSQN    (  948): start dsqn bin
D/WIFI    (  948): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  948):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  948): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService(  948): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  948):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  948):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  948): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
I/DSQN    ( 6643): DSQN samuel.seo ver 141203
E/DSQN    ( 6643): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6643): created command queue thread
I/DSQN    ( 6643): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6643): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
,D/CAR.SERVICE( 6483): mConnectedToCar = false, abort
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
V/WiFiOffLoadBroadcast( 6565): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/WiFiOffLoadBroadcast( 6565): MCCMNC not supported: null
E/ActivityThread( 6483): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@20bd6a8e that was originally bound here
E/ActivityThread( 6483): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@20bd6a8e that was originally bound here
E/ActivityThread( 6483): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6483): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6483): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6483): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6483): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6483): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6483): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6483): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6483): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6483): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6483): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6483): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6483): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6483): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6483): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6483): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6483): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6483): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6483): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6483): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6483): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6483): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.,run(ZygoteInit.java:908)
E/ActivityThread( 6483): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
V/WiFiOffLoadBroadcast( 6565): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/ActivityThread( 6483): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@155281c1 that was originally bound here
E/ActivityThread( 6483): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@155281c1 that was originally bound here
E/ActivityThread( 6483): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6483): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6483): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6483): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6483): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6483): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6483): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6483): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6483): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6483): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6483): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6483): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6483): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6483): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6483): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6483): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6483): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6483): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6483): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6483): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6483): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6483): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  948): Unbind failed: could not find connection for android.os.BinderProxy@3bde4d1
D/WiFiOffLoadBroadcast( 6565): MCCMNC not supported: null
I/PCSuite ( 6595): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6595): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6565): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6565): MCCMNC not supported: null
I/PCSuite ( 6595): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6595): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/DhcpStateMachine(  948): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  948): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  948): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6646): version 5.5.6 starting
,E/dhcpcd  ( 6646): get_duid: Read-only file system
I/dhcpcd  ( 6646): wlan0: rebinding lease of 192.168.1.134
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  948): [LWD] DNSResolver start dns
D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  282): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  282): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  282): res_queryN name = xxxxx succeed
,I/System.out(  948): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  948): [LWD] DNSResolver end dns
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  948): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6643): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6643): restart monitoring
D/LGDataListener(  282): argv[0]=dsqncommand
D/LGDataListener(  282): argv[1]=wlan0
D/LGDataListener(  282): argv[2]=1
D/LGDataListener(  282): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6643): dsqn report finish
,D/DSQN    (  948): DSQM DsqnNotification wlan0  1
D/DSQN    (  948): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  948): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 13 Jan 2016 12:37:37 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452688657469], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452688657439]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  948): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  948): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  948): Validated
D/ConnectivityService(  948): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  948): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  948):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  948):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  948):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  948): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  948): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  948):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  948):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  948): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  948): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiDataContinuityService(  948): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  948): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1753): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
I/WifiServerServiceExt(  948): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  948): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  948):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/rmt_storage(  277): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  277): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  277): wakelock acquired: 1, error no: 42
,I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  277): 
I/rmt_storage(  277): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  948): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  948): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  948): identical MTU - not setting
D/Nat464Xlat(  948): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  948): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  948):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  948):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  948): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524295
D/ConnectivityService(  948): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  948): enableDataServiceNotify 
D/DSQN    (  948): start dsqn bin
I/QCNEJ   ( 1843): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:37.916 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/DSQN    (  948): dsqn is running restart
,I/DSQN    ( 6662): DSQN samuel.seo ver 141203
E/DSQN    ( 6662): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6662): created command queue thread
I/DSQN    ( 6662): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6662): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,I/dhcpcd  ( 6646): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
D/ConnectivityService(  948): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  948): onReceive
D/LocSvc_java(  948): got connectivity action
D/ConnectivityService(  948): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  948): broadcast - no network connections
D/LocSvc_java(  948): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  948): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  948): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  948): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  948): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  948): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  948): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/dhcpcd  ( 6646): wlan0: leased 192.168.1.134 for 86400 seconds
I/ActivityManager(  948): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6677 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LocSvc_java(  948): onReceive
D/LocSvc_java(  948): got connectivity action
D/LocSvc_java(  948): broadcast - no network connections
D/LocSvc_java(  948): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  948): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  948): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  948): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  948): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  948): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  948): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  948): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  948): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  948): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  948): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  948): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  948): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  948): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  948): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  948): RunningState
I/MusicStore( 6677): Database version: 120
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6677): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6677): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6677): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6677): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6677): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6677): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  948): Process com.google.android.gms:car (pid 6483) has died
,W/ActivityThread( 6677): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6677): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@282d93a2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6677): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6677): GMSCore installation verified
I/ConfigStore( 6677): Config Database version: 1
,I/MediaRouter( 6677): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6677): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6677): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6677): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  948): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6735 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6677): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6677): Using platform SSLCertificateSocketFactory
I/QCNEJ   ( 1843): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:39.713 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ResourcesManager( 6735): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6735): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6735): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/NotificationManager( 6677): com.google.android.music: cancel(1061) by com.google.android.music
V/WifiInternetCheck(  948): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  948): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  948): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  948): onReceive
D/LocSvc_java(  948): got connectivity action
D/LocSvc_java(  948): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  948): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  948): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  948): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  948): ignore wifi update if we are not in OPENING or CLOSING
I/NetworkMonitor( 6677): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider(  948): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/LGEmail ( 6735): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6735): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6735): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  948): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6767 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6735): JNI_OnLoad()
I/HubEmail( 6735): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6735): registerNatives()
I/HubEmail( 6735): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6735): registerNativeMethods()
I/HubEmail( 6735): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 6735): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  948): Killing 6267:com.google.android.gm/u0a53 (adj 15): empty #11
W/Settings( 6735): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  948): Process com.android.vending (pid 6226) has died
,W/libprocessgroup(  948): failed to open /acct/uid_10053/pid_6267/cgroup.procs: No such file or directory
D/LGDMClient( 6767): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6767): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6767): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6767): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6767): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6767): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6767): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6767): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  948): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6801 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6767): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6767): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6767): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6767): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6767): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6767): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/AppUp4:AppBoxCP( 6801): onCreate
W/AppUp4:DB( 6801):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6801):  setFingerPrint start
I/AppUp4:DB( 6801):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6801):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6801):  SDK version = 0
I/AppUp4:DB( 6801):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6801): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6801): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6801): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6801): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6801): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6801): onReceive
I/AppUp4:CustModeStarterReceiver( 6801): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6801): Context : android.app.ReceiverRestrictedContext@386c7aa6
D/AppUp4:CustFacade( 6801): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6801): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6801): begin check event
I/AppUp4:CustModeStarterReceiver( 6801): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6801): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6801): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6801): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6801): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  948): Killing 5718:com.google.android.talk/u0a61 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  948): failed to open /acct/uid_10061/pid_5718/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3215): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3215): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3215): networkInfo.isConnected() = false
I/ActivityManager(  948): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6823 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  282): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  282): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out(  948): propertyValue:false
,D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  948): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  948): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  282): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  282): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out(  948): propertyValue:false
D/PhoneMonitor( 6823): Register our PhoneStateListener
,I/DSQN    ( 6662): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6662): restart monitoring
,D/LGDataListener(  282): argv[0]=dsqncommand
D/LGDataListener(  282): argv[1]=wlan0
D/LGDataListener(  282): argv[2]=1
D/LGDataListener(  282): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6662): dsqn report finish
D/DSQN    (  948): DSQM DsqnNotification wlan0  1
D/DSQN    (  948): start to monitor internet connection
D/MobileConnectivityChangeReceiver( 6823): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6823): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  948): Killing 6565:com.android.settings/1000 (adj 15): empty #11
,D/PhoneMonitor( 6823): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6823): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6823): [parse] Load xml
V/WifiInternetCheck(  948): isHttpConnectionAvailable - We got a valid response : 204
,V/TelephonyAutoProfiling( 6823): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6823): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6823): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  948): failed to open /acct/uid_1000/pid_6565/cgroup.procs: No such file or directory
,I/CheckinService( 4290): Checkin interval check for package: unspecified last checkin: 1452688634331 min interval config: 0 actual interval: 26980
,V/DownloadManager( 3306): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3306): DownloadService onCreate
I/NotificationManager( 3306): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3306): in removeSpuriousFiles
V/DownloadManager( 3306): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3306): created cursor android.database.sqlite.SQLiteCursor@2e6714db on behalf of 3306
I/DownloadManager( 3306): in trimDatabase
V/DownloadManager( 3306): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3306): created cursor android.database.sqlite.SQLiteCursor@26a0cb78 on behalf of 3306
I/ActivityManager(  948): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6850 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3306): DownloadService onStartCommand
,V/DownloadManager( 3306): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3306): created cursor android.database.sqlite.SQLiteCursor@1825bab6 on behalf of 3306
,V/DownloadManager( 3306): DownloadService onDestroy
,I/CheckinService( 4290): Checking schedule, now: 1452688661496 next: 1452688664283
I/CheckinService( 4290): active receiver: disabled
,D/WeatherAncestor( 2758): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:37:41
,I/ActivityManager(  948): Killing 6284:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 5199): android.os.DeadObjectException
,W/System.err( 5199): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5199): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5199): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5199): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5199): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5199): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5199): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5199): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5199): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5199): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5199): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5199): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5199): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5199): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5199): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5199): android.os.DeadObjectException
W/System.err( 5199): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5199): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5199): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5199): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5199): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5199): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5199): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5199): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5199): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5199): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5199): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5199): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5199): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5199): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5199): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  948): failed to open /acct/uid_10089/pid_6284/cgroup.procs: No such file or directory
W/ActivityManager(  948): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,D/UpdateThreadPoolManager( 2758): 2 : This is isUpdating : false
D/WeatherAncestor( 2758): connectivity changed - connection : true
D/Weather_cast( 2758): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2758): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:37:41
D/WeatherService( 2758): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  948): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6875 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  948): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2758): 2 : Utils getTopActivity com.lge.launcher2 / true
I/ActivityManager(  948): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6884 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WeatherService( 2758): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2758): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/UEI.SmartControl( 6884): Quickset Services start...
,I/UEI.SmartControl( 6884): Manufacture = LGE
D/UEI.SmartControl( 6884): File observer start...
E/UEI.SmartControl( 6884): IR Port is disabled: false
D/UEI.SmartControl( 6884): Starting file observer...
D/UEI.SmartControl( 6884): Extracting JNI libs...
W/ResourcesManager( 6875): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6884): --- this system supports 32-bit or 64-bit only
,D/UEI.SmartControl( 6884): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6884): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6884): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6884): --- Selecting new region: 2
I/UEI.SmartControl( 6884): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6884): Platform has CIR...
D/UEI.SmartControl( 6884): NO CIR support, need to check package...
I/UEI.SmartControl( 6884): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6884): QS Service created
E/UEI.SmartControl( 6884): QS start get config
,I/Babel_SMS( 6875): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6875): MmsConfig.loadMmsSettings
I/Babel_SMS( 6875): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6875): MmsConfig.loadFromDatabase
,D/UEI.SmartControl( 6884): Loading JNI Libs...
,D/UEI.SmartControl( 6884):  configuring local db...
,E/Babel_SMS( 6875): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6875): MmsConfig.loadFromResources
E/Babel_SMS( 6875): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6875): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6875): CheckpointMarkThreadRoots callback created = 0xaaf20eb0
,D/SensorManager( 6875): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6875): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6875): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6875): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6875): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6875): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6875): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6875): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6875): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6875): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6875): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6875): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6875): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6875): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6875): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6875): found sensor: Motion Accel, handle=46
,I/art     ( 6875): CheckpointMarkThreadRoots callback created = 0xaaf20ea0
,I/ActivityManager(  948): Process com.google.android.music:main (pid 6677) has died
,W/Settings( 6875): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6875): startup - clean
I/Babel   ( 6875): deleted: false for 0
,D/UEI.SmartControl( 6884):  ---- Has DB8: true
,D/UEI.SmartControl( 6884): QS start statue = true Error code = 0
D/UEI.SmartControl( 6884): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6884): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6884): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6884): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6884): IrrcClient ++ 
D/irrcClient( 6884): getIrrcService ++ 
D/irrcClient( 6884): getIrrcService -- 
D/irrcClient( 6884): IrrcClient -- 
W/irrc_jni( 6884): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6884): Services init done
,I/UEI.SmartControl( 6884): Device manager: loading config....
D/UEI.SmartControl( 6884): Config is loaded...
D/UEI.SmartControl( 6884): QS Service init finished
D/UEI.SmartControl( 6884): QS Service version name: 0.1.73
D/UEI.SmartControl( 6884): QS Service version code: 1073
D/UEI.SmartControl( 6884): Service requested: Control
,D/UEI.SmartControl( 6884): -----IControl: 11
D/UEI.SmartControl( 6884): Internal service binding...
D/UEI.SmartControl( 6884): Caller: com.lge.qremote
D/UEI.SmartControl( 6884): ------------ IControl registerCallback...
I/UEI.SmartControl( 6884): Registering callback...
D/UEI.SmartControl( 6884): -----IControl: 19
D/UEI.SmartControl( 6884): Caller: com.lge.qremote
I/UEI.SmartControl( 6884): Registering Services Ready callback...
D/UEI.SmartControl( 6884):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6884): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6884): -----IControl: 8
D/UEI.SmartControl( 6884): Caller: com.lge.qremote
I/art     (  948): Explicit concurrent mark sweep GC freed 83196(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 3.179ms total 204.147ms
,I/ActivityManager(  948): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6938 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6875): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6875): Unsupported mime audio/adpcm
W/AudioCapabilities( 6875): Unsupported mime audio/g726
W/AudioCapabilities( 6875): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6875): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6875): Unsupported mime video/mjpg
W/VideoCapabilities( 6875): Unsupported mime video/theora
,W/AudioCapabilities( 6875): Unsupported mime audio/evrc
W/AudioCapabilities( 6875): Unsupported mime audio/qcelp
W/VideoCapabilities( 6875): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6875): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6875): Unsupported mime audio/qcelp
W/AudioCapabilities( 6875): Unsupported mime audio/evrc
W/VideoCapabilities( 6875): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6875): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6875): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6875): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6875): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6875): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6875): onServiceConnected
W/Babel   ( 6875): Attempted to change video mute state without an active call.
,I/NotificationManager( 6875): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6875): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6875): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6875): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6875): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  282): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  282): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out( 6875): propertyValue:false
I/Babel   ( 6875): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  948): Killing 6595:com.lge.sync/1000 (adj 15): empty #11
I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,W/libprocessgroup(  948): failed to open /acct/uid_1000/pid_6595/cgroup.procs: No such file or directory
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6938): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6938): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6938): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6938):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6938):   adb logcat -s GAv4
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6938): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6938): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6938): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6938): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6938): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6938): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6938): Time to load native libraries: 3 ms (timestamps 9241-9244)
,I/LibraryLoader( 6938): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6938): Binding Chromium to main looper Looper (main, tid 1) {3e12eacb}
I/LibraryLoader( 6938): Expected native library version number "",actual native library version number ""
I/chromium( 6938): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6938): Initializing chromium process, singleProcess=true
W/art     ( 6938): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6938): ApplicationContext is null in ApplicationStatus
,W/chromium( 6938): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6938): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6938): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6938): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6938): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6938): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6938): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6938): Remote Branch: 
I/Adreno-EGL( 6938): Local Patches: 
I/Adreno-EGL( 6938): Reconstruct Branch: 
V/AudioPolicyService(  286): registerClient() client 0xb57e7460, uid 10079
,W/AudioManagerAndroid( 6938): Requires BLUETOOTH permission
I/NSApplication( 6938): Starting up...
,I/ActivityManager(  948): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7001 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  948): Killing 5199:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  948): failed to open /acct/uid_10106/pid_5199/cgroup.procs: No such file or directory
,I/ActivityManager(  948): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7021 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  948): Killing 6735:com.lge.email/u0a21 (adj 15): empty #11
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 23.253ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.978ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.612ms
,W/libprocessgroup(  948): failed to open /acct/uid_10021/pid_6735/cgroup.procs: No such file or directory
,W/ResourcesManager( 7021): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  948): RTC_WAKEUP set : Alarm{109348cb type 0 when 1452688664283 com.google.android.gms} when 1452688664283
,V/AlarmManager(  948): RTC_WAKEUP set : Alarm{20850fc1 type 0 when 1452688664883 com.google.android.googlequicksearchbox} when 1452688664883
I/ActivityManager(  948): Killing 6767:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  948): failed to open /acct/uid_1000/pid_6767/cgroup.procs: No such file or directory
,I/ActivityManager(  948): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7053 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  948): ELAPSED_WAKEUP set : Alarm{13bab366 type 2 when 110575 com.google.android.gms} when 110575
,I/MusicStore( 7053): Database version: 120
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7053): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7053): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7053): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7053): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7053): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7053): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7053): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7053): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@282d93a2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7053): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7053): GMSCore installation verified
I/ConfigStore( 7053): Config Database version: 1
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/MediaRouter( 7053): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7053): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7053): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7053): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  948): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7095 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7053): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7053): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  948): Killing 6801:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 7095): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7095): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7095): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/libprocessgroup(  948): failed to open /acct/uid_10011/pid_6801/cgroup.procs: No such file or directory
,I/NotificationManager( 7053): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7095): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7095): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7095): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  948): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7121 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7095): JNI_OnLoad()
I/HubEmail( 7095): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7095): registerNatives()
I/HubEmail( 7095): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7095): registerNativeMethods()
I/HubEmail( 7095): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7095): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  948): Killing 6823:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  948): failed to open /acct/uid_10038/pid_6823/cgroup.procs: No such file or directory
W/Settings( 7095): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 7121): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7121): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7121): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7121): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/ActivityManager(  948): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7139 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/LGDMClient( 7121): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7121): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7121): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7121): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 7121): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 7121): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7121): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7121): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7121): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7121): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  948): Killing 6850:com.lge.drmservice/u0a51 (adj 15): empty #11
I/AppUp4:AppBoxCP( 7139): onCreate
,W/AppUp4:DB( 7139):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7139):  setFingerPrint start
I/AppUp4:DB( 7139):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7139):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7139):  SDK version = 0
I/AppUp4:DB( 7139):  beforefinger == newfinger no write in DB
,W/libprocessgroup(  948): failed to open /acct/uid_10051/pid_6850/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 7139): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7139): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7139): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7139): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7139): [onReceive] request level :IDLE....
I/ActivityManager(  948): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7171 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  948): RTC_WAKEUP set : Alarm{8892e03 type 0 when 1452688667215 com.android.vending} when 1452688667215
,I/AppUp4:CustModeStarterReceiver( 7139): onReceive
I/AppUp4:CustModeStarterReceiver( 7139): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 7139): Context : android.app.ReceiverRestrictedContext@386c7aa6
D/AppUp4:CustFacade( 7139): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7139): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7139): begin check event
,I/AppUp4:CustModeStarterReceiver( 7139): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7139): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7139): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7139): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7139): handleAsyncCustNotification do not startCustService
I/ActivityManager(  948): Killing 6884:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  948): failed to open /acct/uid_10089/pid_6884/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3215): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3215): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3215): networkInfo.isConnected() = false
,I/ActivityManager(  948): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7196 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/Finsky  ( 7171): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/PhoneMonitor( 7196): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7196): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7196): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 4290): Checkin interval check for package: unspecified last checkin: 1452688634331 min interval config: 0 actual interval: 33756
V/DownloadManager( 3306): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,I/CheckinService( 4290): Checking schedule, now: 1452688668106 next: 1452688664283
I/CheckinService( 4290): active receiver: enabled
V/DownloadManager( 3306): DownloadService onCreate
,I/NotificationManager( 3306): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/PhoneMonitor( 7196): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/DownloadManager( 3306): in removeSpuriousFiles
V/TelephonyAutoProfiling( 7196): [loadFeatureFromXml] *** start feature loading from xml
,V/DownloadManager( 3306): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3306): created cursor android.database.sqlite.SQLiteCursor@d32724 on behalf of 3306
I/DownloadManager( 3306): in trimDatabase
V/DownloadManager( 3306): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3306): created cursor android.database.sqlite.SQLiteCursor@19acd28d on behalf of 3306
D/TelephonyAutoProfiling( 7196): [parse] Load xml
,V/TelephonyAutoProfiling( 7196): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7196): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/ActivityManager(  948): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7238 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/CheckinService( 4290): Preparing to send checkin request
,I/EventLogService( 4290): Accumulating logs since 1452688626627
,V/DownloadManager( 3306): DownloadService onStartCommand
V/DownloadManager( 3306): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/PhoneMonitor( 7196): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3306): created cursor android.database.sqlite.SQLiteCursor@7ad9190 on behalf of 3306
D/Finsky  ( 7171): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/WeatherAncestor( 2758): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:37:48
,W/Settings( 7171): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/UpdateThreadPoolManager( 2758): 2 : This is isUpdating : false
D/WeatherAncestor( 2758): connectivity changed - connection : true
W/Settings( 7171): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/Weather_cast( 2758): 2 : isUpdateNeedForAlarm : no city return false
I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
D/WeatherAncestor( 2758): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:37:48
D/WeatherService( 2758): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/NotificationManager( 7171): com.android.vending: cancel(-1050172287) by com.android.vending
,W/ActivityManager(  948): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2758): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2758): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2758): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,V/MusicLeanback( 7053): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/LGDMClient( 7121): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7121): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7121): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 7121): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/Ads     ( 7171): Skipping gmscore version check
D/Finsky  ( 7171): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7171): [1] Libraries$2.run: Finished loading 1 libraries.
,I/jxcore-log( 6396): Test app app.js loaded
I/jxcore-log( 6396): 
,I/chromium( 6396): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/art     (  948): Explicit concurrent mark sweep GC freed 24701(1309KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 5.362ms total 208.805ms
,D/LGDMClient( 7121): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
W/Settings( 7095): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LGDMClient( 7121): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NetworkStateForAutoUpdateMonitor( 7139): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7139): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7121): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7121): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/NetworkStateForAutoUpdateMonitor( 7139): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7139): [onReceive] request level :IDLE....
V/DownloadManager( 3306): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3306): DownloadService onDestroy
V/DownloadManager( 3306): created cursor android.database.sqlite.SQLiteCursor@20bd6a8e on behalf of 7171
,I/AppUp4:CustModeStarterReceiver( 7139): onReceive
I/AppUp4:CustModeStarterReceiver( 7139): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7139): Context : android.app.ReceiverRestrictedContext@386c7aa6
D/AppUp4:CustFacade( 7139): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7139): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7139): begin check event
W/ContextImpl( 7121): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
I/AppUp4:CustModeStarterReceiver( 7139): Event For GoodConnectivity, noConnectivity : false, but skip! 
E/LGDMClient( 7121): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7121): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7121): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 7121): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
I/LgeMiscReceiver( 3215): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3215): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3215): networkInfo.isConnected() = true
D/PhoneState( 3215): setPdpRejectCasuse : false
D/LGDMClient( 7121): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/CheckinRequestBuilder( 4290): Checkin reason type: 8 attempt count: 1
,D/MobileConnectivityChangeReceiver( 7196): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7196): onReceive CONNECTIVITY_CHANGE networkType=1
D/Finsky  ( 7171): [1] GmsCoreHelper.cleanupNlp: result=false type=4
V/DownloadManager( 3306): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3306): DownloadService onCreate
,E/ActivityThread( 4290): Failed to find provider info for com.google.android.wearable.settings
I/ActivityManager(  948): Killing 7238:com.lge.drmservice/u0a51 (adj 15): empty #11
I/DownloadManager( 3306): in removeSpuriousFiles
V/DownloadManager( 3306): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3306): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3306): created cursor android.database.sqlite.SQLiteCursor@3d8236bc on behalf of 3306
,I/DownloadManager( 3306): in trimDatabase
V/DownloadManager( 3306): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3306): created cursor android.database.sqlite.SQLiteCursor@2e86c645 on behalf of 3306
D/Finsky  ( 7171): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Finsky  ( 7171): [870] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,W/BroadcastQueue(  948): Exception when sending broadcast to ComponentInfo{com.lge.drmservice/com.lge.drmservice.DrmBroadcastReceiver}
W/BroadcastQueue(  948): android.os.DeadObjectException
W/BroadcastQueue(  948): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue(  948): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue(  948): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
W/BroadcastQueue(  948): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:270)
W/BroadcastQueue(  948): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1002)
W/BroadcastQueue(  948): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16810)
W/BroadcastQueue(  948): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:473)
W/BroadcastQueue(  948): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2625)
W/BroadcastQueue(  948): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:457)
W/BroadcastQueue(  948): 	at android.os.Binder.execTransact(Binder.java:446)
W/libprocessgroup(  948): failed to open /acct/uid_10051/pid_7238/cgroup.procs: No such file or directory
I/ActivityManager(  948): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7281 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3306): DownloadService onStartCommand
W/ActivityManager(  948): Spurious death for ProcessRecord{2aa1efe0 7281:com.lge.drmservice/u0a51}, curProc for 7238: null
D/Finsky  ( 7171): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/QCNEJ   ( 1843): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
V/DownloadManager( 3306): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:37:48.796 DNS addrs= 192.168.1.1, 0.0.0.0, 
,V/DownloadManager( 3306): created cursor android.database.sqlite.SQLiteCursor@3e12eacb on behalf of 3306
I/ActivityManager(  948): Killing 6875:com.google.android.talk/u0a61 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  948): failed to open /acct/uid_10061/pid_6875/cgroup.procs: No such file or directory
,V/DownloadManager( 3306): DownloadService onDestroy
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  948): Killing 6938:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  948): failed to open /acct/uid_10079/pid_6938/cgroup.procs: No such file or directory
D/WeatherAncestor( 2758): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:37:48
,D/UpdateThreadPoolManager( 2758): 2 : This is isUpdating : false
D/WeatherAncestor( 2758): connectivity changed - connection : true
D/Weather_cast( 2758): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2758): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:37:48
D/WeatherService( 2758): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  948): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7298 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  948): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2758): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2758): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2758): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 7298): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  948): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7315 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 7315): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7315): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Babel_SMS( 7298): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7298): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7298): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7298): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7298): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7298): MmsConfig.loadFromResources
E/Babel_SMS( 7298): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7298): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/MultiDex( 7315): VM with version 2.1.0 has multidex support
I/MultiDex( 7315): install
I/MultiDex( 7315): VM has multidex support, MultiDex support library is disabled.
,D/SensorManager( 7298): found sensor: LGE Accelerometer Sensor, handle=0
,V/JNIHelp ( 7315): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/SensorManager( 7298): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7298): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7298): found sensor: LGE Proximity Sensor, handle=48
D/sensors_hal_Time(  948): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  948): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  948): tsOffsetIs: Apps: 114916143086; DSPS: 3864103; Offset : -3008496186
D/SensorManager( 7298): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7298): found sensor: LGE Linear Acceleration Sensor, handle=30
,D/SensorManager( 7298): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7298): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7298): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7298): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7298): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7298): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7298): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7298): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7298): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7298): found sensor: Motion Accel, handle=46
I/art     ( 7298): CheckpointMarkThreadRoots callback created = 0xb042d880
,W/Settings( 7298): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7298): startup - clean
,I/Babel   ( 7298): deleted: false for 0
,I/art     ( 7298): CheckpointMarkThreadRoots callback created = 0xb042d860
W/ActivityThread( 7315): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7315): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e6714db: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7315): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7315): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7315): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 7315): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7315): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/ActivityManager(  948): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7354 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 23.342ms
,W/AudioCapabilities( 7298): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7298): Unsupported mime audio/adpcm
W/AudioCapabilities( 7298): Unsupported mime audio/g726
W/AudioCapabilities( 7298): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7298): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7298): Unsupported mime video/mjpg
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 22.572ms
W/VideoCapabilities( 7298): Unsupported mime video/theora
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 28.655ms
,W/AudioCapabilities( 7298): Unsupported mime audio/evrc
,W/AudioCapabilities( 7298): Unsupported mime audio/qcelp
W/VideoCapabilities( 7298): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7298): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7298): Unsupported mime audio/qcelp
W/AudioCapabilities( 7298): Unsupported mime audio/evrc
W/VideoCapabilities( 7298): Unsupported mime video/mp4v-esdp
D/NativeLibraryUtils( 7315): Install completed successfully. count=14 extracted=0
,I/VideoCapabilities( 7298): Unsupported profile 4 for video/mp4v-es
,D/WVCdm   (  286): Instantiating CDM.
I/WVCdm   (  286): CdmEngine::OpenSession
I/WVCdm   (  286): Level3 Library Dec 11 2014 16:13:16
W/VideoCapabilities( 7298): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7298): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7298): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7298): Unrecognized profile 2130706433 for video/avc
,W/WVCdm   (  286): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  286): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  286): L1 library not specified. Falling Back to L3
I/vclib   ( 7298): onServiceConnected
W/Babel   ( 7298): Attempted to change video mute state without an active call.
,I/NotificationManager( 7298): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 7298): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7298): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7298): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7298): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  282): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  282): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  282): res_queryN name = xxxxx succeed
,I/System.out( 7298): propertyValue:false
I/WVCdm   (  286): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  286): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  286): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  286): CdmEngine::GenerateKeyRequest
D/WVCdm   (  286): PrepareKeyRequest: nonce=4031395426
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7354): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/Babel   ( 7298): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  948): Killing 7001:com.android.chrome/u0a48 (adj 15): empty #11
I/GAv4    ( 7354): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7354):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7354):   adb logcat -s GAv4
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7354): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7354): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7354): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/libprocessgroup(  948): failed to open /acct/uid_10048/pid_7001/cgroup.procs: No such file or directory
,W/GAv4    ( 7354): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/art     ( 7315): CheckpointMarkThreadRoots callback created = 0xb042d410
,W/GAv4    ( 7354): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
I/art     ( 7315): CheckpointMarkThreadRoots callback created = 0xb042d400
W/GAv4    ( 7354): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat ( 7385): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7385): dex2oat took 110.950ms (threads: 4)
,I/Adreno-EGL( 7315): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7315): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7315): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7315): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7315): Remote Branch: 
I/Adreno-EGL( 7315): Local Patches: 
I/Adreno-EGL( 7315): Reconstruct Branch: 
,I/WebViewFactory( 7354): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/Adreno-EGL( 7315): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7315): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7315): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7315): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7315): Remote Branch: 
I/Adreno-EGL( 7315): Local Patches: 
I/Adreno-EGL( 7315): Reconstruct Branch: 
,I/ActivityManager(  948): Process com.google.android.music:main (pid 7053) has died
,I/LibraryLoader( 7354): Time to load native libraries: 2 ms (timestamps 6263-6265)
I/LibraryLoader( 7354): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7354): Binding Chromium to main looper Looper (main, tid 1) {3e12eacb}
I/LibraryLoader( 7354): Expected native library version number "",actual native library version number ""
I/chromium( 7354): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7354): Initializing chromium process, singleProcess=true
W/art     ( 7354): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7354): ApplicationContext is null in ApplicationStatus
,W/chromium( 7354): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7354): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7354): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7354): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7354): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7354): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7354): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7354): Remote Branch: 
I/Adreno-EGL( 7354): Local Patches: 
I/Adreno-EGL( 7354): Reconstruct Branch: 
V/AudioPolicyService(  286): registerClient() client 0xb551c720, uid 10079
,W/AudioManagerAndroid( 7354): Requires BLUETOOTH permission
I/NSApplication( 7354): Starting up...
,I/Adreno-EGL( 7315): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7315): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7315): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7315): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7315): Remote Branch: 
I/Adreno-EGL( 7315): Local Patches: 
I/Adreno-EGL( 7315): Reconstruct Branch: 
,I/WVCdm   (  286): CdmEngine::OpenSession
,I/ActivityManager(  948): Process com.lge.email (pid 7095) has died
,I/ActivityManager(  948): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7425 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  948): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7447 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7447): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  948): Message: 20
D/BluetoothManagerService(  948): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32ce5cd2:true
,D/BluetoothAdapterService(416728893)( 2007): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69f7cfb
D/BluetoothAdapterService(416728893)( 2007): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69f7cfb
I/ActivityManager(  948): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7468 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7447): Create singleton instance
,W/art     ( 7121): Suspending all threads took: 6.711ms
D/UEI.SmartControl( 7468): Quickset Services start...
,I/UEI.SmartControl( 7468): Manufacture = LGE
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/UEI.SmartControl( 7468): File observer start...
E/UEI.SmartControl( 7468): IR Port is disabled: false
D/UEI.SmartControl( 7468): Starting file observer...
D/UEI.SmartControl( 7468): Extracting JNI libs...
D/UEI.SmartControl( 7468): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7447): getMode name:com.lge.qremote
,I/CheckinService( 4290): Checkin interval check for package: unspecified last checkin: 1452688634331 min interval config: 0 actual interval: 37609
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  282): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  282): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
W/ContextImpl( 3682): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
E/MDM     ( 1733): [133] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  948): Process com.android.vending (pid 7171) has died
D/LocationInitializer( 4290): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/WVCdm   (  286): CdmEngine::CloseSession
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
I/AudioManager( 7447): getMode name:com.lge.qremote
D/UEI.SmartControl( 7468): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7468): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7468): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/WVCdm   (  286): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  286): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  286): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  286): CdmEngine::GenerateKeyRequest
D/WVCdm   (  286): PrepareKeyRequest: nonce=848802713
,I/UEI.SmartControl( 7468): --- Selecting new region: 2
I/UEI.SmartControl( 7468): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7468): Platform has CIR...
,D/UEI.SmartControl( 7468): NO CIR support, need to check package...
I/UEI.SmartControl( 7468): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7468): QS Service created
,E/UEI.SmartControl( 7468): QS start get config
,I/MusicWidget( 2707): mDelayedStopHandler : unbind
,D/UEI.SmartControl( 7468): Loading JNI Libs...
D/UEI.SmartControl( 7468):  configuring local db...
I/MusicBrowser( 2110): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2110): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
,I/MusicBrowser( 2110): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2110): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2110): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2110): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2110): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2110): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  948):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3facf6c4com.lge.music.MediaPlaybackService$6@2f6cf9ad
,D/MusicBrowser( 2110): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2110): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2110): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2110): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2110): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@1a559b32
I/MusicBrowser( 2110): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2110): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2110): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2110): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2110): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2110): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2110): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2110): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2110): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2110): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2110): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2110): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2110): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2110): reset
V/MediaPlayer[Native]( 2110): setListener
V/MediaPlayer[Native]( 2110): disconnect
V/MediaPlayer[Native]( 2110): destructor
,V/AudioFlinger(  286): releasing 19 from 2110 for -1
V/AudioFlinger(  286):  decremented refcount to 0
V/AudioFlinger(  286): purging stale effects
V/MediaPlayer[Native]( 2110): disconnect
D/MusicBrowser( 2110): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2110): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2110): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2110): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2110): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2110): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2110): [SmartShareManagerClient] unregisterListener: 776418530
W/SmartShareClient( 2110): [SmartShareManagerClient] unregisterListener invalid listener: 776418530
I/SmartShareClient( 2110): [SmartShareManagerClient] terminate service: 2110/MediaPlaybackService/697314792
E/HomeCloudIF( 2110): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2110): [SmartShareManagerClient] unbindService context:android.app.Application@1fe4bb30
V/CloudHub( 2110): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2110): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2110): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2110): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2110): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/CloudHub( 2110): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29992
D/UEI.SmartControl( 7468):  ---- Has DB8: true
,D/UEI.SmartControl( 7468): QS start statue = true Error code = 0
D/UEI.SmartControl( 7468): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7468): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7468): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7468): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7468): IrrcClient ++ 
D/irrcClient( 7468): getIrrcService ++ 
D/irrcClient( 7468): getIrrcService -- 
,D/irrcClient( 7468): IrrcClient -- 
W/irrc_jni( 7468): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7468): Services init done
I/UEI.SmartControl( 7468): Device manager: loading config....
D/UEI.SmartControl( 7468): QS Service init finished
D/UEI.SmartControl( 7468): QS Service version name: 0.1.73
D/UEI.SmartControl( 7468): QS Service version code: 1073
,D/UEI.SmartControl( 7468): Service requested: Control
D/UEI.SmartControl( 7468): Config is loaded...
D/UEI.SmartControl( 7468):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7468): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7468): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7468): Internal service binding...
D/UEI.SmartControl( 7468): -----IControl: 11
D/UEI.SmartControl( 7468): Caller: com.lge.qremote
D/UEI.SmartControl( 7468): ------------ IControl registerCallback...
I/UEI.SmartControl( 7468): Registering callback...
D/UEI.SmartControl( 7468): -----IControl: 19
D/UEI.SmartControl( 7468): Caller: com.lge.qremote
I/UEI.SmartControl( 7468): Registering Services Ready callback...
I/UEI.SmartControl( 7468): Notify client services are ready...
D/UEI.SmartControl( 7468): -----IControl: 8
,D/UEI.SmartControl( 7468): Caller: com.lge.qremote
I/AudioManager( 7447): getMode name:com.lge.qremote
,I/ActivityManager(  948): Killing 7121:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/ActivityManager(  948): Killing 7139:com.lge.appbox.client/u0a11 (adj 15): empty #12
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  948): failed to open /acct/uid_1000/pid_7121/cgroup.procs: No such file or directory
,W/libprocessgroup(  948): failed to open /acct/uid_10011/pid_7139/cgroup.procs: No such file or directory
I/AudioManager( 7447): getMode name:com.lge.qremote
,I/AudioManager( 7447): getMode name:com.lge.qremote
V/AlarmManager(  948): ELAPSED_WAKEUP set : Alarm{51120ce type 2 when 118353 com.google.android.gms} when 118353
,I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/WVCdm   (  286): CdmEngine::CloseSession
,I/WVCdm   (  286): L3 Terminate.
,I/art     ( 4028): Explicit concurrent mark sweep GC freed 2602(103KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.234ms total 44.405ms
,I/art     ( 7021): CheckpointMarkThreadRoots callback created = 0xb042d400
,I/art     ( 7021): CheckpointMarkThreadRoots callback created = 0xb042d3f0
I/CheckinRequestBuilder( 4290): Classify the device as Phone.
,D/libc-netbsd( 4290): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4290): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4290): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4290): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  282): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  282): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out( 4290): propertyValue:false
,D/libc-netbsd( 4290): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4290): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4290): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4290): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4290): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4290): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4290): Sending checkin request (9798 bytes)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinRequestBuilder( 4290): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4290): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  948): Explicit concurrent mark sweep GC freed 19024(867KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 1.967ms total 161.726ms
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4290): Classify the device as Phone.
,I/CheckinTask( 4290): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4290): Checking schedule, now: 1452688675706 next: 1453215924702
I/CheckinService( 4290): active receiver: disabled
,I/CheckinService( 4290): Checking schedule, now: 1452688675771 next: 1453215924702
I/CheckinService( 4290): active receiver: disabled
,D/CheckinService( 4290): Recording last checkin time for package unspecified as 1452688675782
,V/SetupWizard( 7196): Connected to Gservices successfully
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  948): Killing 7354:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,I/ActivityManager(  948): Killing 7281:com.lge.drmservice/u0a51 (adj 15): empty #12
,W/libprocessgroup(  948): failed to open /acct/uid_10079/pid_7354/cgroup.procs: No such file or directory
,W/libprocessgroup(  948): failed to open /acct/uid_10051/pid_7281/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7468): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1843): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  948): Reconfiguring input devices.  changes=0x00000010
,W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
,W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1881): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
I/[LGHome]LGPlusHomeDBManager( 1881): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1881): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/administrator(  948): Handling package changes for user 0
,I/ActivityManager(  948): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7564 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationManager( 7298): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 7298): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7298): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 7564): onCreate
,W/AppUp4:DB( 7564):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7564):  setFingerPrint start
,I/AppUp4:DB( 7564):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,V/JNIHelp ( 7298): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AppUp4:DB( 7564):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7564):  SDK version = 0
I/AppUp4:DB( 7564):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7564): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 7564): onReceive
I/AppUp4:CustModeStarterReceiver( 7564): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7564): Context : android.app.ReceiverRestrictedContext@1925bb0b
D/AppUp4:CustFacade( 7564): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7564): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7564): begin check event
I/AppUp4:CustModeStarterReceiver( 7564): Event For Nothing, skip.
W/System  ( 7298): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7298): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  948): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7586 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/NotificationService(  948): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  948): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  948): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  948): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  948): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  948): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@147e4fec
,D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1789): getDefaultRoute
,W/ResourcesManager( 7586): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7586): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7586): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourcesManager(  948): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  948): Process com.google.android.apps.plus (pid 7021) has died
,I/AppConfig( 7586): Total System Memory = 906309632
,I/GalleryUtils( 7586): Application Heap = 96 MB
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/AppConfig( 7586): App Tier : NOT_DEF
,D/SystemHelper( 7586): region [EU], country [EU], operator [OPEN], sub-operator []
W/ResourceType(  948): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  948): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7610 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/[LGHome]EVENT( 1881): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  948): applying state to connected service
,W/ResourcesManager( 7610): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7610): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7610): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7610): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7610): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7610): BUILD Country: EU
,I/SystemConfig( 7610): BUILD Operator: OPEN
I/ActivityManager(  948): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7630 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  948): Killing 7425:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  948): failed to open /acct/uid_10048/pid_7425/cgroup.procs: No such file or directory
,I/SystemConfig( 7610): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7610): existFile = false
I/SystemConfig( 7610): canReadFile = false
I/SystemConfig( 7610): systemFeature RCS result false
D/SystemConfig( 7610): refreshRcsSupport() :false
I/LockScreenSettings( 7630): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7630): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7630): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7630): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7630): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7630): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  948): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7650 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  948): Killing 2110:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  286): 2110 died, releasing its sessions
,V/AudioFlinger(  286):  pid 1753 @ 0
V/AudioFlinger(  286):  pid 3215 @ 1
V/AudioFlinger(  286):  pid 3215 @ 2
W/libprocessgroup(  948): failed to open /acct/uid_10028/pid_2110/cgroup.procs: No such file or directory
,W/ResourcesManager( 7650): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1943): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  948): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7676 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  948): Killing 7196:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1943): UpdateCorporaTask done [took 108 ms] updated apps [took 108 ms] 
,W/libprocessgroup(  948): failed to open /acct/uid_10038/pid_7196/cgroup.procs: No such file or directory
D/PowerManagerServiceEx(  948): acquireWakeLockInternal: lock=203411062, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=948
,D/WeatherService( 2758): 2 : TimeTick Intent has been received, Time(hour:min:sec) 13:38:0
D/WeatherService( 2758): 2 : TimeTick Intent And Screen On
D/WeatherService( 2758): 2 : SDK version : 21
W/ActivityManager(  948): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2758): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2758): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2758): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2758): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2758): 2 : This is isUpdating : false
D/WeatherService( 2758): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2758): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2758): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2758): 2 : Fixed theme : optimus
D/WeatherReflect( 2758): 2 : Map key string is -2
,D/lim     ( 2758): 2 : time = 13:38
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/WeatherReflect( 2758): Model Name : LG-D722
D/WeatherTheme( 2758): 2 : Different view - status_min_formatted : 37 != 38
D/WeatherTheme( 2758): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
D/WeatherReflect( 2758): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2758): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2758): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2758): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2758): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[SystemUI]Clock( 1374): called onTimeUpdated()
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
,D/Weather4x2_optimus( 2758): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2758): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2758): forecast size is 0
D/Theme   ( 2758): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2758): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2758): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2758): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2758): EnableTheme(home): com.lge.launcher2.theme.optimus
,D/Theme   ( 2758): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2758): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2758): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2758): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2758): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2758): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2758): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2758): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2758): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2758): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2758): url is : null
D/Theme   ( 2758): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2758): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2758): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2758): 2 : update view, appWidgetId: 2
D/WeatherService( 2758): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 13:38:0
,D/PowerManagerServiceEx(  948): releaseWakeLockInternal: lock=203411062 [*alarm*], flags=0x0
,I/ActivityManager(  948): Process com.google.android.gms (pid 4290) has died
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1881): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,D/Finsky  ( 7676): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1881): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,D/Finsky  ( 7676): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7676): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7676): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7676): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3306): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3306): created cursor android.database.sqlite.SQLiteCursor@155281c1 on behalf of 7676
D/Ads     ( 7676): Skipping gmscore version check
,D/Finsky  ( 7676): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7676): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 7676): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  948): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=7721 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/Finsky  ( 7676): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ResourcesManager( 7721): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7721): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7721): VM with version 2.1.0 has multidex support
I/MultiDex( 7721): install
I/MultiDex( 7721): VM has multidex support, MultiDex support library is disabled.
,I/QCNEJ   ( 1843): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:38:00.83 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/JNIHelp ( 7721): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7721): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7721): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e64a7f9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7721): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7721): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7721): com.google.android.gms: cancel(39789) by com.google.android.gms
D/PackageBroadcastService( 7721): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
,E/MDM     ( 1733): [147] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/PackageBroadcastService( 7721): Null package name or gms related package.  Ignoreing.
,D/LocationInitializer( 7721): Restart initialization of location
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,I/art     ( 7721): Background sticky concurrent mark sweep GC freed 25921(1326KB) AllocSpace objects, 4(64KB) LOS objects, 10% free, 10MB/11MB, paused 6.364ms total 81.153ms
,D/NativeLibraryUtils( 7721): Install completed successfully. count=14 extracted=0
,I/art     ( 7721): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7721): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/Icing   ( 7721): Storage manager: low false usage 1.73MB avail 2.36GB capacity 4.06GB
,I/art     ( 7721): CheckpointMarkThreadRoots callback created = 0xaae7b6b0
,I/art     ( 7721): CheckpointMarkThreadRoots callback created = 0xaae47e20
,I/art     ( 7721): Background partial concurrent mark sweep GC freed 4156(557KB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 10MB/17MB, paused 5.653ms total 85.648ms
,I/art     (  948): Explicit concurrent mark sweep GC freed 29821(1498KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.022ms total 168.075ms
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,W/IcingInternalCorpora( 7721): getNumBytesRead when not calculated.
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1843): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1843): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/charger_monitor(  479): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  948): battery changed pluggedType: 2
D/HeadsetStateMachine( 2007): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/Icing   ( 7721): updateResources: need to parse f{com.google.android.gms}
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Icing   ( 7721): Internal init done: storage state 0
,I/NotificationManager( 7721): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/Icing   ( 7721): Post-init done
,I/Icing   ( 7721): updateResources: need to parse f{com.google.android.gms}
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Icing   ( 7721): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 7721): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 7721): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  948): Killing 7315:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  948): failed to open /acct/uid_10006/pid_7315/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  948): Killing 7468:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7447): android.os.DeadObjectException
,W/System.err( 7447): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7447): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7447): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7447): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7447): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7447): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7447): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7447): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7447): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7447): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7447): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7447): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7447): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7447): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7447): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7447): android.os.DeadObjectException
W/System.err( 7447): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7447): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7447): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7447): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7447): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7447): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7447): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7447): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7447): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7447): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7447): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7447): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7447): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7447): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7447): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  948): failed to open /acct/uid_10089/pid_7468/cgroup.procs: No such file or directory
,W/ActivityManager(  948): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  948): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7796 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 452us total 41.010ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 27.097ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 344us total 21.096ms
D/UEI.SmartControl( 7796): Quickset Services start...
,I/UEI.SmartControl( 7796): Manufacture = LGE
,D/UEI.SmartControl( 7796): File observer start...
E/UEI.SmartControl( 7796): IR Port is disabled: false
D/UEI.SmartControl( 7796): Starting file observer...
D/UEI.SmartControl( 7796): Extracting JNI libs...
D/UEI.SmartControl( 7796): --- this system supports 32-bit or 64-bit only
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/UEI.SmartControl( 7796): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7796): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7796): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7796): --- Selecting new region: 2
,I/UEI.SmartControl( 7796): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7796): Platform has CIR...
D/UEI.SmartControl( 7796): NO CIR support, need to check package...
I/UEI.SmartControl( 7796): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7796): QS Service created
E/UEI.SmartControl( 7796): QS start get config
,D/UEI.SmartControl( 7796): Loading JNI Libs...
,D/UEI.SmartControl( 7796):  configuring local db...
D/UEI.SmartControl( 7796):  ---- Has DB8: true
,D/UEI.SmartControl( 7796): QS start statue = true Error code = 0
D/UEI.SmartControl( 7796): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7796): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 7796): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7796): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7796): IrrcClient ++ 
D/irrcClient( 7796): getIrrcService ++ 
D/irrcClient( 7796): getIrrcService -- 
,D/irrcClient( 7796): IrrcClient -- 
W/irrc_jni( 7796): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7796): Services init done
I/UEI.SmartControl( 7796): Device manager: loading config....
D/UEI.SmartControl( 7796): QS Service init finished
D/UEI.SmartControl( 7796): QS Service version name: 0.1.73
D/UEI.SmartControl( 7796): QS Service version code: 1073
,D/UEI.SmartControl( 7796): Config is loaded...
D/UEI.SmartControl( 7796): Service requested: Control
D/UEI.SmartControl( 7796): -----IControl: 11
I/ActivityManager(  948): Killing 7447:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7796): Caller: com.lge.qremote
D/UEI.SmartControl( 7796): ------------ IControl registerCallback...
I/UEI.SmartControl( 7796): Registering callback...
W/libprocessgroup(  948): failed to open /acct/uid_10106/pid_7447/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7796): Internal service binding...
,D/UEI.SmartControl( 7796):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7796): Notify AllClients services are ready: 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  948): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  948): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  948): tsOffsetIs: Apps: 134917062662; DSPS: 4519494; Offset : -3008521431
,D/UEI.SmartControl( 7796): Internal timer expired: 1
,D/UEI.SmartControl( 7796): Service.onUnbind: IControl
D/UEI.SmartControl( 7796): Service.onDestroy
W/System.err( 7796): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@18d6c73d
W/System.err( 7796): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7796): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7796): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7796): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7796): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7796): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7796): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7796): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7796): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7796): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7796): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7796): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7796): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7796): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7796): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7796): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@18d6c73d
D/UEI.SmartControl( 7796): Shutdown IRRCPlayer... 
,W/irrc_jni( 7796): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7796): ~IrrcClient ++ 
D/irrcClient( 7796): ~IrrcClient -- 
W/irrc_jni( 7796): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7796): Blaster closed
D/UEI.SmartControl( 7796): Blaster closed
D/UEI.SmartControl( 7796): Shut down QS...
,D/UEI.SmartControl( 7796): Stopped file observer...
I/UEI.SmartControl( 7796): QS lib stop result = true
D/UEI.SmartControl( 7796): QS shutdown complete
I/QCNEJ   ( 1843): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:38:12.89 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1843): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:38:15.918 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  948): ELAPSED_WAKEUP set : Alarm{10d48429 type 2 when 145054 com.google.android.gms} when 145054
,I/ActivityManager(  948): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=7854 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/ResourcesManager( 7854): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7854): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7854): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7854): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7854): Installed default security provider GmsCore_OpenSSL
W/art     ( 7854): Suspending all threads took: 6.392ms
,W/ResourcesManager( 7854): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7854): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 7854): CheckpointMarkThreadRoots callback created = 0xaaf3f640
,E/YouTube MDX( 7854): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc-netbsd( 7854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 7854): CheckpointMarkThreadRoots callback created = 0xb4958de0
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7854): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/dex2oat ( 7892): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads248752085.jar --oat-fd=31 --oat-location=/data/data/com.google.android.youtube/cache/ads248752085.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7892): dex2oat took 118.800ms (threads: 4)
,I/NotificationManager( 7854): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7854): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7854): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7854): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 7854): Found 10006
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
,W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7854): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/libc-netbsd( 7854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  282): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  282): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
D/PerfProfileCollectorService( 7721): User is not opt-in to Usage & Diagnostics.
D/PerfProfileCollectorService( 7721): removeStateFiles() called
D/PerfProfileCollectorService( 7721): User is not opt-in to Usage & Diagnostics.
,D/libc-netbsd(  282): res_queryN name = xxxxx succeed
,I/System.out( 7854): propertyValue:false
D/libc-netbsd( 7854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/art     ( 1733): Explicit concurrent mark sweep GC freed 39554(2MB) AllocSpace objects, 22(352KB) LOS objects, 40% free, 14MB/23MB, paused 3.974ms total 123.861ms
,I/NotificationManager( 7854): com.google.android.youtube: cancel(10436) by com.google.android.youtube
D/libc-netbsd( 7854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  282): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  282): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out( 7854): propertyValue:false
D/libc-netbsd( 7854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  948): Killing 7298:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  948): failed to open /acct/uid_10061/pid_7298/cgroup.procs: No such file or directory
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1733): Vacuum at: now=1452688701852 tag=VacuumService
W/InstanceID/Rpc( 7721): Found 10006
,I/QCNEJ   ( 1843): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:38:21.941 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/PhenotypeConfigurator( 1733): Scheduling Phenotype for one-off execution 13280 seconds from now (1452688702205)
,D/GetConfigurationSnapshotOperation( 1733): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1733): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  948): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  282): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  282): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/PowerManagerService(  948): ALS enabled for SRE
D/PowerManagerServiceEx(  948): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28134 ms ago)
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/qdlights(  948): set_light_backlight: 252
,D/qdlights(  948): set_light_backlight: 249
D/qdlights(  948): set_light_backlight: 245
,D/qdlights(  948): set_light_backlight: 242
,D/qdlights(  948): set_light_backlight: 239
,D/qdlights(  948): set_light_backlight: 235
,D/qdlights(  948): set_light_backlight: 232
,D/qdlights(  948): set_light_backlight: 229
,D/qdlights(  948): set_light_backlight: 225
,D/qdlights(  948): set_light_backlight: 222
,D/qdlights(  948): set_light_backlight: 219
,D/qdlights(  948): set_light_backlight: 215
,D/qdlights(  948): set_light_backlight: 212
,D/qdlights(  948): set_light_backlight: 209
,D/qdlights(  948): set_light_backlight: 205
,D/qdlights(  948): set_light_backlight: 202
,D/qdlights(  948): set_light_backlight: 199
,D/qdlights(  948): set_light_backlight: 195
,D/qdlights(  948): set_light_backlight: 192
,D/qdlights(  948): set_light_backlight: 189
,D/qdlights(  948): set_light_backlight: 185
,D/qdlights(  948): set_light_backlight: 182
,D/qdlights(  948): set_light_backlight: 179
,D/qdlights(  948): set_light_backlight: 175
,D/qdlights(  948): set_light_backlight: 172
,D/qdlights(  948): set_light_backlight: 169
,D/LocationManagerService(  948): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/qdlights(  948): set_light_backlight: 165
,D/qdlights(  948): set_light_backlight: 162
,D/qdlights(  948): set_light_backlight: 159
,D/qdlights(  948): set_light_backlight: 155
,D/qdlights(  948): set_light_backlight: 152
,D/qdlights(  948): set_light_backlight: 149
,D/qdlights(  948): set_light_backlight: 145
,D/qdlights(  948): set_light_backlight: 142
,D/qdlights(  948): set_light_backlight: 139
,I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
D/qdlights(  948): set_light_backlight: 135
,D/qdlights(  948): set_light_backlight: 132
,D/qdlights(  948): set_light_backlight: 129
,D/qdlights(  948): set_light_backlight: 125
,D/qdlights(  948): set_light_backlight: 122
,D/qdlights(  948): set_light_backlight: 119
,D/qdlights(  948): set_light_backlight: 115
,D/qdlights(  948): set_light_backlight: 112
,D/qdlights(  948): set_light_backlight: 109
,D/qdlights(  948): set_light_backlight: 105
,D/qdlights(  948): set_light_backlight: 102
,D/qdlights(  948): set_light_backlight: 99
,D/qdlights(  948): set_light_backlight: 95
,D/qdlights(  948): set_light_backlight: 92
,D/qdlights(  948): set_light_backlight: 89
,D/qdlights(  948): set_light_backlight: 85
,D/qdlights(  948): set_light_backlight: 82
,D/qdlights(  948): set_light_backlight: 79
,D/LocationManagerService(  948): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/qdlights(  948): set_light_backlight: 75
,D/qdlights(  948): set_light_backlight: 72
,D/qdlights(  948): set_light_backlight: 69
,D/qdlights(  948): set_light_backlight: 65
,D/qdlights(  948): set_light_backlight: 62
,D/qdlights(  948): set_light_backlight: 59
,D/LocationManagerService(  948): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/qdlights(  948): set_light_backlight: 55
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/qdlights(  948): set_light_backlight: 52
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/qdlights(  948): set_light_backlight: 49
,D/qdlights(  948): set_light_backlight: 45
,D/qdlights(  948): set_light_backlight: 42
,D/qdlights(  948): set_light_backlight: 39
,D/qdlights(  948): set_light_backlight: 35
,D/qdlights(  948): set_light_backlight: 32
,D/qdlights(  948): set_light_backlight: 29
,D/qdlights(  948): set_light_backlight: 25
,D/qdlights(  948): set_light_backlight: 22
,D/qdlights(  948): set_light_backlight: 19
,D/LocationManagerService(  948): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/qdlights(  948): set_light_backlight: 15
,D/qdlights(  948): set_light_backlight: 12
,D/qdlights(  948): set_light_backlight: 10
,D/LocationManagerService(  948): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  948): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  948): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  948): tsOffsetIs: Apps: 154917943279; DSPS: 5174882; Offset : -3008496008
,I/PowerManagerService(  948): ALS enabled for SRE
D/PowerManagerServiceEx(  948): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35122 ms ago)
I/PowerManagerService(  948): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  948): ALS enabled for SRE
D/PowerManagerServiceEx(  948): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35134 ms ago)
W/ContextImpl(  948): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  948): Sleeping (uid 1000)...
D/LPWGController(  948): [updateScreenState] screen on = false
D/LPWGController(  948): disable proximity sensor
D/LPWGController(  948): enable proximity sensor
I/SensorManager(  948): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@24a272b] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  948): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  948): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  948): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  948): activate: handle is 48, enable
V/sensors_hal_Ctx(  948): activate sensors is 1400000000000
D/sensors_hal_Thresh(  948): enable: handle=48
I/sensors_hal_SAM(  948): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  948): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  948): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  948): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  948): enable: Received response: 0
D/PowerManagerServiceEx(  948): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35171 ms ago)
I/Adreno-EGL(  948): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  948): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  948): Build Date: 03/02/15 Mon
I/Adreno-EGL(  948): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  948): Remote Branch: 
I/Adreno-EGL(  948): Local Patches: 
I/Adreno-EGL(  948): Reconstruct Branch: 
,D/PermissionCache(  248): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (971 us)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/Sensors (  433): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  948): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  948): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
,D/sensors_hal_Thresh(  948): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  948): processInd: handle 48, count=1
V/sensors_hal_Thresh(  948): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  948): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  948): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  948): poll: count: 256
I/sensors_hal_Ctx(  948): poll: released wakelock sensor_ind
D/sensors_hal_Util(  948): waitForResponse: timeout=0
D/LPWGController(  948): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  948): current mode = 1  value = 1 1
I/LPWGController(  948): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/ActivityManager(  948): Process com.android.contacts (pid 7610) has died
,I/LPWGController(  948): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  948): set_light_backlight: 0
,I/SensorManager(  948): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  948): activate: handle is 46, disable
V/sensors_hal_Ctx(  948): activate sensors is 1000000000000
D/sensors_hal_LP2(  948): enable: handle=46
D/sensors_hal_LP2(  948): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  948): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  248): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  248): hwc_blank: Blanking display: 0
I/DisplayManagerService(  948): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  948): Display changed displayId=0
V/sensors_hal_SAM(  948): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
,D/sensors_hal_LP2(  948): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1753): Display #0 changed.
,D/qdhwcomposer(  248): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  948): Excessive delay in setPowerMode(): 187ms
I/qdhwcomposer(  248): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  948): Got set_interactive hint
D/KeyguardViewMediator( 1374): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1333): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1333): notifyScreenOffLocked
D/SmartCoverViewMediator( 1333): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1374): notifyScreenOffLocked
,D/KeyguardViewMediator( 1374): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1374): handleNotifyScreenOff
,D/WifiServerServiceExt(  948): sendKtScanInterval  mRtspPlay : false
,I/QCNEJ   ( 1843): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 13:38:30.65 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ScreenTurnOffBySensor( 1374): unregisterProximitySensor
D/StatusBarWindowView( 1374): onScreenTurnedOff why = 3
I/WifiServerServiceExt(  948): set CMD_KT_SCAN_INTERVAL
,V/AudioFlinger(  286): setParameters(): io 0, keyvalue screen_state=on, calling pid 948
D/audio_hw_primary(  286): adev_set_parameters: enter: screen_state=on
V/voice   (  286): voice_set_parameters: enter: screen_state=on
V/compress_voip(  286): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  286): voice_extn_compress_voip_set_parameters: exit
V/voice   (  286): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  286): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  286): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  286): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  286): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  286): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  286): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  286): adev_set_parameters: exit with code(0)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/GpsLocationProvider(  948): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1843): |CORE| sendScreenState: state:true
I/ActivityManager(  948): Process com.android.gallery3d (pid 7586) has died
,I/LEDService( 1806): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1806): stopPatternFlashing()
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
,I/LEDService( 1806): getCurrentHighestLGLedRecord : size = 1
,D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): updateLightsLocked : turn off led
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1806): RESTART MSG
D/SplitWindow(  948): check instance of lgWin Window{1a346d46 u0 SearchPanel}
,I/Cliptray Service( 1806): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/Cliptray Service( 1806): lockStatus = 0
D/InputDispatcher(  948): Window went away: Window{192d2010 u0 SearchPanel}
,I/[SystemUI]Clock( 1374): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1374): time changed, timezoneChanged : false
,D/LNfcService( 1789): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1789): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1789): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1789): isRequireNfcCRouting() return true
D/LNfcService( 1789): isHCERoutingtoHost() return : true
D/NfcService( 1789): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1789): mEnableLPD: true
D/NfcService( 1789): mEnableReader: false
D/NfcService( 1789): mEnableHostRouting: true
D/NfcService( 1789): newParams.techmask= mTechMask: default
D/NfcService( 1789): mEnableLPD: true
D/NfcService( 1789): mEnableReader: false
D/NfcService( 1789): mEnableHostRouting: true
D/NfcService( 1789): screenState= 3
D/NfcService( 1789): Discovery configuration equal, not updating.
,D/Ulp_jni (  948): JNI:system_update. Event-0
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2758): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:38:30
,D/WeatherService( 2758): 2 : ACTION screen on
D/WeatherService( 2758): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2758): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2758): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:38:30
W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  948): ACTION_SCREEN_ON
,D/AppCleanupService( 4146): android.intent.action.SCREEN_ON
,V/AudioFlinger(  286): setParameters(): io 0, keyvalue screen_state=off, calling pid 948
,D/audio_hw_primary(  286): adev_set_parameters: enter: screen_state=off
V/voice   (  286): voice_set_parameters: enter: screen_state=off
V/compress_voip(  286): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  286): voice_extn_compress_voip_set_parameters: exit
V/voice   (  286): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  286): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  286): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  286): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  286): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  286): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  286): adev_set_parameters: exit with code(0)
I/ActivityManager(  948): Process com.lge.appbox.client (pid 7564) has died
,D/WifiController(  948): CMD_SCREEN_OFF 
D/WifiController(  948): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  948): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1843): |CORE| sendScreenState: state:false
,I/LEDService( 1806): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1806): stopPatternFlashing()
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1806): clear
I/LEDService( 1806): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): updateLightsLocked : turn on led
E/LEDService( 1806): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1806): Can't handle this request of patternId:0
D/LEDHandler( 1806): RESTART MSG
I/Cliptray Service( 1806): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1789): action : android.intent.action.SCREEN_OFF
,D/NfcServiceNXP( 1789): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1881): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2758): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:38:31
D/WeatherService( 2758): 2 : ACTION screen off
D/WeatherService( 2758): 2 : TimeTick Receiver Unregister
,D/WeatherService( 2758): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:38:31
W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  948): ACTION_SCREEN_OFF
D/AppCleanupService( 4146): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4146): AppUsageStatsSaveTask
,E/NxpNfcJni( 1789): getReconnectState = 0x0
,D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1789): getDefaultRoute
D/LNfcService( 1789): isRequireNfcCRouting() return true
D/LNfcService( 1789): isHCERoutingtoHost() return : true
D/NfcService( 1789): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1789): mEnableLPD: true
D/NfcService( 1789): mEnableReader: false
D/NfcService( 1789): mEnableHostRouting: true
D/NfcService( 1789): newParams.techmask= mTechMask: 0
D/NfcService( 1789): mEnableLPD: true
D/NfcService( 1789): mEnableReader: false
D/NfcService( 1789): mEnableHostRouting: true
D/NfcService( 1789): screenState= 1
E/NxpNfcJni( 1789): getReconnectState = 0x0
,I/Sensors (  433): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  948): ELAPSED_WAKEUP set : Alarm{2bc20b07 type 2 when 161028 com.android.systemui} when 161028
,D/KeyguardViewMediator( 1374): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1753): getCallState : 0
,D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1374): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1374): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  948): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  948): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  948): tsOffsetIs: Apps: 174918620928; DSPS: 5830265; Offset : -3008519144
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/PowerManagerServiceEx(  948): acquireWakeLockInternal: lock=203411062, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=948
,V/AlarmManager(  948): ELAPSED_WAKEUP set : Alarm{f650434 type 2 when 186485 com.google.android.gms} when 186485
D/PowerManagerServiceEx(  948): releaseWakeLockInternal: lock=203411062 [*alarm*], flags=0x0
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 2007): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1843): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1843): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  948): battery changed pluggedType: 2
I/ClearcutLoggerApiImpl( 1733): disconnect managed GoogleApiClient
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  948): ELAPSED_WAKEUP set : Alarm{982d25d type 2 when 190154 android} when 190154
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  948): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  948): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  948): tsOffsetIs: Apps: 194919291441; DSPS: 6485647; Offset : -3008520513
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  948): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  948): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  948): tsOffsetIs: Apps: 214920357059; DSPS: 7141041; Offset : -3008492102
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  948): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  948): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  948): tsOffsetIs: Apps: 234921197259; DSPS: 7796429; Offset : -3008507332
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 2007): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/QCNEJ   ( 1843): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1843): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  948): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  948): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  948): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  948): tsOffsetIs: Apps: 254921960012; DSPS: 8451814; Offset : -3008506241
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  948): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  948): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  948): tsOffsetIs: Apps: 274922669744; DSPS: 9107197; Offset : -3008498649
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  948): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  948): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  948): tsOffsetIs: Apps: 294923337757; DSPS: 9762579; Offset : -3008502179
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1843): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1843): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
D/HeadsetStateMachine( 2007): Disconnected process message: 10, size: 0
W/Settings(  948): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  948): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  948): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  948): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  948): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  948): tsOffsetIs: Apps: 314924104989; DSPS: 10417964; Offset : -3008497626
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6396): --= Surplus to requirements =--
I/jxcore-log( 6396): 
I/jxcore-log( 6396): ****TEST TOOK:  ms ****
I/jxcore-log( 6396): 
I/jxcore-log( 6396): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6396): 
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/AndroidRuntime( 8065): 
D/AndroidRuntime( 8065): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8065): CheckJNI is OFF
D/AndroidRuntime( 8065): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  948): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  948): Killing 6396:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,W/PackageSettings(  948): Skipping PackageSetting{265836ba com.example.hello/10317} due to missing metadata
I/WindowState(  948): WIN DEATH: Window{1cd4038f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  948): Focus left window: Window{1cd4038f u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  948): Window went away: Window{1cd4038f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  948):   Force finishing activity ActivityRecord{19606360 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  948): Display changed displayId=0
,D/DSDPConnection( 1753): Display #0 changed.
W/ActivityManager(  948): Spurious death for ProcessRecord{39ba17d2 6396:com.test.thalitest/u0a316}, curProc for 6396: null
,I/ActivityManager(  948): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/[LGHome]EVENT( 1881): [Launcher.java:5203:onStart()]onStart
,I/[LGHome]EVENT( 1881): [Launcher.java:776:onResume()]onResume
,D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader(  948): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1843): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
,I/ActivityManager(  948): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8092 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1881): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/art     ( 1943): Explicit concurrent mark sweep GC freed 9900(551KB) AllocSpace objects, 3(71KB) LOS objects, 39% free, 12MB/21MB, paused 3.277ms total 145.094ms
I/[LGHome]Launcher.Model( 1881): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
W/System.err( 3682): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 3682): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3682): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3682): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3682): 	at android.os.Handler.handleCallback(Handler.java:739)
,W/System.err( 3682): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3682): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3682): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3682): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3682): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3682): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3682): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[LGHome]LGActivityUtil( 1881): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_REMOVED
,I/[LGHome]EVENT( 1881): [Launcher.java:929:onResume()]onResume end
I/Activity( 1881): Activity.onPostResume() called 
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
I/[LGHome]EVENT( 1881): [Launcher.java:986:onPause()]onPause
,W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
,W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
,I/art     (  948): Explicit concurrent mark sweep GC freed 57920(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 9.729ms total 278.889ms
W/[LGHome]LGWallpaperInfo( 1881): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1881): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/art     (  948): WaitForGcToComplete blocked for 66.471ms for cause Explicit
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1374): handleShortcutListChanged...
,W/ResourcesManager( 8092): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8092): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8092): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemUI[Framework](  948): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  948): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  948): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  948): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  948): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@35e9461e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  948): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  948): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/PhoneWindowManagerEx(  948): Call!!!getLGSystemUiVisibility. =0x0
,D/StatusBarManagerServiceEx(  948): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  948): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  948): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@35e9461e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  948): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  948): Focus entered window: Window{2cc1d03c u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 1881): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1881): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1881): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[LGHome]EVENT( 1881): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): handleShortcutListChanged...
,I/[LGHome]EVENT( 1881): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1881): [setNavigationBarColor] color=0x 0
D/administrator(  948): Handling package changes for user 0
,I/art     (  948): Explicit concurrent mark sweep GC freed 6460(394KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.275ms total 263.184ms
,I/LGEmail ( 8092): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8092): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/AndroidRuntime( 8065): Shutting down VM
,W/InputMethodManagerService(  948): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  948): Got RemoteException sending setActive(false) notification to pid 6396 uid 10316
D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1789): getDefaultRoute
,I/[LGHome]Launcher.Model( 1881): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/Timeline(  948): Timeline: Activity_windows_visible id: ActivityRecord{531017c u0 com.lge.launcher2/.Launcher t221} time:325804
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,W/IInputConnectionWrapper( 1881): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1881): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/b       ( 1605): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1881): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1881): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/NotificationService(  948): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  948): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  948): Receieved: android.intent.action.PACKAGE_REMOVED
,D/PhoneStatusBar( 1374): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
D/TaskPersister(  948): removeObsoleteFile: deleting file=222_task.xml
,I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1881): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1881): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
,W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,I/PackageChangeReceiver( 8092): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,W/ResourcesManager(  948): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  948): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8129 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1881): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created

```
