#### Test 565307121a686b7_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
I/ActivityManager(  866): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6192 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  866): Killing 5959:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/libprocessgroup(  866): failed to open /acct/uid_10009/pid_5959/cgroup.procs: No such file or directory
W/ResourcesManager( 6192): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6192): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6192): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6192): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6192): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,--------- beginning of main
I/SystemConfig( 6192): BUILD Country: EU
I/SystemConfig( 6192): BUILD Operator: OPEN
I/ActivityManager(  866): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6216 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  866): Killing 5988:com.google.android.configupdater/u0a3 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/libprocessgroup(  866): failed to open /acct/uid_10003/pid_5988/cgroup.procs: No such file or directory
I/SystemConfig( 6192): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6192): existFile = false
I/SystemConfig( 6192): canReadFile = false
I/SystemConfig( 6192): systemFeature RCS result false
D/SystemConfig( 6192): refreshRcsSupport() :false
I/LockScreenSettings( 6216): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
D/LockScreenSettings( 6216): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6216): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6216): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6216): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6216): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  866): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6238 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  866): Killing 5772:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
D/sensors_hal_Time(  866): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  866): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  866): tsOffsetIs: Apps: 95010415280; DSPS: 3204758; Offset : -2793735530
W/System.err( 5108): android.os.DeadObjectException
W/System.err( 5108): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5108): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5108): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5108): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5108): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5108): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5108): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5108): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5108): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5108): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5108): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5108): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5108): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5108): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5108): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5108): android.os.DeadObjectException
W/System.err( 5108): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5108): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5108): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5108): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5108): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5108): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5108): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5108): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5108): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5108): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5108): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5108): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5108): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5108): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5108): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  866): failed to open /acct/uid_10089/pid_5772/cgroup.procs: No such file or directory
W/ActivityManager(  866): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
D/AndroidRuntime( 6212): 
D/AndroidRuntime( 6212): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/ResourcesManager( 6238): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/AndroidRuntime( 6212): CheckJNI is OFF
I/ActivityManager(  866): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6257 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/GAV2    ( 5921): Thread[GAThread,5,main]: No campaign data found.
D/UEI.SmartControl( 6257): Quickset Services start...
I/UEI.SmartControl( 6257): Manufacture = LGE
D/UEI.SmartControl( 6257): File observer start...
E/UEI.SmartControl( 6257): IR Port is disabled: false
D/UEI.SmartControl( 6257): Starting file observer...
D/UEI.SmartControl( 6257): Extracting JNI libs...
D/UEI.SmartControl( 6257): --- this system supports 32-bit or 64-bit only
I/ActivityManager(  866): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=6294 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  866): RTC_WAKEUP set : Alarm{15d2c2c7 type 0 when 1453241204335 com.android.vending} when 1453241204335
D/UEI.SmartControl( 6257): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6257): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6257): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6257): --- Selecting new region: 2
I/UEI.SmartControl( 6257): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6257): Platform has CIR...
D/UEI.SmartControl( 6257): NO CIR support, need to check package...
I/UEI.SmartControl( 6257): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6257): QS Service created
E/UEI.SmartControl( 6257): QS start get config
D/AndroidRuntime( 6212): Calling main entry com.android.commands.am.Am
I/ActivityManager(  866): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/UEI.SmartControl( 6257): Loading JNI Libs...
D/UEI.SmartControl( 6257):  configuring local db...
D/ActivityManager(  866): setTaskToReturnTo : TaskRecord{2067b01d #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  866): setTaskToReturnTo : TaskRecord{2067b01d #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  866): AppWindowTokenEx init.. 
D/ContextHelper(  866): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  866): Focus left window: Window{345da57d u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6212): Shutting down VM
D/SplitWindow(  866): check instance of lgWin Window{3ce3a8c u0 Starting com.test.thalitest}
I/ActivityManager(  866): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6322 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/Finsky  ( 6294): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1937): Closing mic
I/MicrophoneInputStream( 1937): mic_close com.google.android.apps.gsa.speech.audio.u@37154afe
V/AudioRecord( 1937): stop()
D/AudioRecord( 1937): AudioRecord->stop()
V/AudioFlinger(  285): RecordHandle::stop()
V/AudioFlinger(  285): RecordThread::stop
I/WindowStateAnimator(  866): Starting window displayed
I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 70 ms] updated apps [took 70 ms] 
I/SystemUI[Framework](  866): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  866): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  866): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  866): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  866): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@35d54b59,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  866): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/AudioFlinger(  285): Record stopped OK
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
V/AudioPolicyManager(  285): stopInput() input 17
V/AudioPolicyService(  285): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  285): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  285): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  285): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  285): ThreadBase::setParameters() routing=0
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb385e000
D/audio_hw_primary(  285): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1373): draw background and invalidate : color = e000000
D/BarTransitions( 1373): draw background and invalidate : color = b0b0b0b
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/audio_hw_primary(  285): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  285): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  285): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  285): disable_audio_route: reset and update mixer path: audio-record
,V/audio_hw_primary(  285): disable_audio_route: exit
E/audio_hw_primary(  285): disable_snd_device: enter 144
D/hardware_info(  285): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  285): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  285): stop_input_stream: exit: status(0)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioPolicyManager(  285): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  285): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  285): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  285): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioPolicyService(  285): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  285): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  285): setParameters(): io 17, keyvalue hotword_active=0, calling pid 285
V/AudioFlinger(  285): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  285): RecordThread: loop starting
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  285): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  285): in_set_parameters: exit: status(0)
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb385e000
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioRecord( 1937): stop()
V/AudioRecord( 1937): stop()
V/AudioRecord( 1937): stop()
V/AudioFlinger(  285): releasing 16 from 1937 for -1
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
V/AudioFlinger(  285): RecordHandle::stop()
V/AudioFlinger(  285): RecordThread::stop
V/AudioPolicyManager(  285): releaseInput() 17
V/AudioPolicyManager(  285): closeInput(17)
V/AudioFlinger(  285): closeInput() 17
V/AudioSystem(  285): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1741): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  285): ThreadBase::exit
V/AudioFlinger(  285): RecordThread: loop starting
V/AudioSystem( 2010): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  285): RecordThread 0xb385e000 exiting
D/audio_hw_primary(  285): adev_close_input_stream: enter:stream_handle(0xb546e420)
D/audio_hw_primary(  285): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioPolicyService(  285): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  285): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  285): releaseInput() exit
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioFlinger(  285): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  285): AudioCommandThread() processing update audio port list
V/AudioFlinger(  285): removeClient_l() pid 1937, calling pid 285
V/AudioSystem(  866): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioSystem( 3206): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1373): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1937): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1965): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 1937): Stopping hotword detection.
I/HotwordRecognitionRnr( 1937): Hotword detection finished
D/UEI.SmartControl( 6257):  ---- Has DB8: true
D/UEI.SmartControl( 6257): QS start statue = true Error code = 0
D/UEI.SmartControl( 6257): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6257): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6257): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6257): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6257): IrrcClient ++ 
D/irrcClient( 6257): getIrrcService ++ 
D/irrcClient( 6257): getIrrcService -- 
D/irrcClient( 6257): IrrcClient -- 
W/irrc_jni( 6257): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6257): Services init done
D/UEI.SmartControl( 6257): QS Service init finished
D/UEI.SmartControl( 6257): QS Service version name: 0.1.73
D/UEI.SmartControl( 6257): QS Service version code: 1073
I/UEI.SmartControl( 6257): Device manager: loading config....
D/UEI.SmartControl( 6257): Service requested: Control
D/UEI.SmartControl( 6257): Config is loaded...
D/ContextHelper( 6322): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/UEI.SmartControl( 6257):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6257): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6257): Request IControl service: devices are loaded...
I/ActivityManager(  866): Killing 5108:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  866): failed to open /acct/uid_10106/pid_5108/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6257): Internal service binding...
I/WebViewFactory( 6322): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/Finsky  ( 6294): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/LibraryLoader( 6322): Time to load native libraries: 2 ms (timestamps 6195-6197)
I/LibraryLoader( 6322): Expected native library version number "",actual native library version number ""
W/Settings( 6294): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6294): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6294): com.android.vending: cancel(-1050172287) by com.android.vending
V/WebViewChromiumFactoryProvider( 6322): Binding Chromium to main looper Looper (main, tid 1) {1ce2c983}
I/LibraryLoader( 6322): Expected native library version number "",actual native library version number ""
I/chromium( 6322): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
V/DownloadManager( 3181): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3181): created cursor android.database.sqlite.SQLiteCursor@370738d on behalf of 6294
I/BrowserStartupController( 6322): Initializing chromium process, singleProcess=true
W/art     ( 6322): Attempt to remove local handle scope entry from IRT, ignoring
D/Finsky  ( 6294): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
E/SysUtils( 6322): ApplicationContext is null in ApplicationStatus
D/Ads     ( 6294): Skipping gmscore version check
D/Finsky  ( 6294): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6294): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 6294): [1] GmsCoreHelper.cleanupNlp: result=false type=4
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PackageBroadcastService( 4257): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/Finsky  ( 6294): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
W/chromium( 6322): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6322): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6322): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6322): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6322): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6322): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6322): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6322): Remote Branch: 
I/Adreno-EGL( 6322): Local Patches: 
I/Adreno-EGL( 6322): Reconstruct Branch: 
I/ActivityManager(  866): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6374 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/PackageBroadcastService( 4257): Null package name or gms related package.  Ignoreing.
I/Icing   ( 4257): updateResources: need to parse f{com.google.android.gms}
I/NotificationManager(  866): android: cancelAsUser(2) by android
W/ResourcesManager( 6374): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/AudioPolicyService(  285): registerClient() client 0xb57e9780, uid 10316
D/BluetoothManagerService(  866): Message: 20
,D/BluetoothManagerService(  866): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c0969:true
D/BluetoothAdapterService(108952287)( 1965): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2d0c1aad
,D/BluetoothManagerService(  866): Message: 20
D/BluetoothManagerService(  866): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b07534c:true
D/BluetoothAdapterService(108952287)( 1965): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2d0c1aad
D/BluetoothAdapterService(108952287)( 1965): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2d0c1aad
D/libc-netbsd( 6294): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6294): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6294): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6294): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 6294): propertyValue:false
D/libc-netbsd( 6294): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6294): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/AudioManager( 6374): getMode name:com.lge.qremote
,I/AudioManager( 6374): getMode name:com.lge.qremote
,W/art     ( 6322): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 22034(1291KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 14MB/23MB, paused 1.829ms total 112.089ms
W/AwContents( 6322): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6322): CordovaWebView is running on device made by: LGE
,W/art     ( 6322): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6322): Attempt to remove local handle scope entry from IRT, ignoring
V/LGMDMManager( 6374): Create singleton instance
,D/libc-netbsd( 6294): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6294): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Activity( 6322): Activity.onPostResume() called 
D/OpenGLRenderer( 6322): Render dirty regions requested: true
I/OpenGLRenderer( 6322): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6322): Enabling debug mode 0
D/Atlas   ( 6322): Validating map...
,D/SplitWindow(  866): check instance of lgWin Window{356a3d4e u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6322): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/AudioManager( 6374): getMode name:com.lge.qremote
,D/UEI.SmartControl( 6257): -----IControl: 11
D/UEI.SmartControl( 6257): Caller: com.lge.qremote
D/UEI.SmartControl( 6257): ------------ IControl registerCallback...
I/UEI.SmartControl( 6257): Registering callback...
D/UEI.SmartControl( 6257): -----IControl: 19
,D/UEI.SmartControl( 6257): Caller: com.lge.qremote
I/UEI.SmartControl( 6257): Registering Services Ready callback...
I/UEI.SmartControl( 6257): Notify client services are ready...
,D/UEI.SmartControl( 6257): -----IControl: 8
D/UEI.SmartControl( 6257): Caller: com.lge.qremote
D/InputDispatcher(  866): Focus entered window: Window{356a3d4e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/AudioManager( 6374): getMode name:com.lge.qremote
I/ActivityManager(  866): Killing 6076:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  866): failed to open /acct/uid_10038/pid_6076/cgroup.procs: No such file or directory
,W/InputMethodManagerService(  866): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/AudioManager( 6374): getMode name:com.lge.qremote
I/ActivityManager(  866): Displayed com.test.thalitest/.MainActivity: +1s203ms
I/Timeline(  866): Timeline: Activity_windows_visible id: ActivityRecord{373d0292 u0 com.test.thalitest/.MainActivity t222} time:96906
,I/AudioManager( 6374): getMode name:com.lge.qremote
I/Timeline( 6322): Timeline: Activity_idle id: android.os.BinderProxy@6da9a2e time:96916
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  866): android: cancelAsUser(2) by android
,W/BindingManager( 6322): Cannot call determinedVisibility() - never saw a connection for the pid: 6322
,I/qtaguid ( 6294): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6294): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6294): untagSocket(41) failed with errno -22
D/Finsky  ( 6294): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/JsMessageQueue( 6322): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  866): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6427 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 22.785ms
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 27.115ms
I/NotificationManager(  866): android: cancelAsUser(2) by android
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 23.463ms
,W/ResourcesManager( 6427): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6427): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6427): VM with version 2.1.0 has multidex support
I/MultiDex( 6427): install
I/MultiDex( 6427): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6427): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 6294): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6294): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6294): untagSocket(41) failed with errno -22
,W/ActivityThread( 6427): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6427): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@370738d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6427): Installed default security provider GmsCore_OpenSSL
I/Icing   ( 4257): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/ActivityManager(  866): Process com.android.providers.calendar (pid 6127) has died
I/NotificationManager( 6427): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6427): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1734): callingUid 10006, callindPid: 1734
,D/ChimeraCfgMgr( 6427): Reading stored module config
E/MDM     ( 1734): [148] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ChimeraCfgMgr( 6427): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/Icing   ( 4257): Loaded CLD2 Version V2.0 - 20141016
D/LocationInitializer( 4257): Restart initialization of location
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
D/jxcore_app_log( 6322): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622836224
,W/GCoreFlp( 1734): No location to return for getLastLocation()
,W/FusedLocationProvider( 1734): location=null
I/Icing   ( 4257): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/chromium( 6322): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/CAR.SERVICE( 6427): Connecting to CarCallService...
,I/art     ( 6322): CheckpointMarkThreadRoots callback created = 0x9f6a35a0
I/art     ( 6427): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6427): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6322): CheckpointMarkThreadRoots callback created = 0x9f6a3570
D/CAR.SERVICE( 6427): com.google.android.projection.gearhead isn't installed.
,D/NativeLibraryUtils( 6427): Install completed successfully. count=14 extracted=0
,D/CAR.TEL.Service( 6427): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6427): Creating a new PhoneAdapter instance
W/ActivityManager(  866): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6427): setListener: com.google.android.gms.car.dn@1b3c93c0
W/ActivityManager(  866): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6427): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6427): Starting CarCallService with initial phone null
,I/art     ( 3986): Explicit concurrent mark sweep GC freed 3127(124KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 404us total 38.306ms
,I/NotificationManager( 6427): com.google.android.gms: cancel(10436) by com.google.android.gms
I/art     ( 6294): CheckpointMarkThreadRoots callback created = 0xb042d890
,I/art     ( 6294): CheckpointMarkThreadRoots callback created = 0xb042d850
,D/CAR.SERVICE( 6427): Package validated; name: com.android.vending
,I/NotificationManager( 6294): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6294): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/AlertService( 6097): Beginning updateAlertNotification
,I/ActivityManager(  866): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6461 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6461): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6461): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1e3b77a6
,I/ActivityManager(  866): Process com.android.contacts (pid 6192) has died
,D/CalendarProvider2( 6461): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6461): Created com.android.providers.calendar.CalendarAlarmManager@1ce2c983(com.android.providers.calendar.CalendarProvider2@1e3b77a6)
I/art     (  866): Explicit concurrent mark sweep GC freed 30451(1478KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 16.449ms total 191.896ms
,D/AlertService( 6097): No fired or scheduled alerts
,I/NotificationManager( 6097): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6097): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6097): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6097): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6097): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6097): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6097): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6097): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6097): com.android.calendar: cancel(8) by com.android.calendar
,I/NotificationManager( 6097): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6097): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6097): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6097): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6097): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6097): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6097): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6097): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6097): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6097): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6097): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6097): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6097): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ActivityManager(  866): Process com.android.gallery3d (pid 6168) has died
,D/AlarmScheduler( 6097): No events found starting within 1 week.
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  866): android: cancelAsUser(2) by android
,I/qtaguid ( 6294): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6294): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6294): untagSocket(41) failed with errno -22
,W/ResourcesManager( 6294): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6294): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6294): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6294): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  866): RTC_WAKEUP set : Alarm{a4a0e09 type 0 when 1453241208633 com.android.vending} when 1453241208633
,D/DeviceConnectionService( 1734): client connected with version: 8296000
,D/Finsky  ( 6294): [784] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6294): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 6294): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  866): android: cancelAsUser(2) by android
,D/libc-netbsd( 6294): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6294): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6294): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6294): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 6294): propertyValue:false
,I/ActivityManager(  866): Process com.google.android.talk (pid 5796) has died
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/jxcore-log( 6322): Initializing JXcore engine
,W/jxcore-log( 6322): JXcore engine is ready
I/ActivityManager(  866): Killing 6097:com.android.calendar/u0a13 (adj 15): empty #11
,W/Thread-781( 6452): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8209]" dev="sockfs" ino=8209 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-781( 6452): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-781( 6452): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5940]" dev="sockfs" ino=5940 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-781( 6452): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-781( 6452): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-781( 6452): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[30984]" dev="sockfs" ino=30984 scontext=u:r:untrusted_app:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 6322): Starting JXcore engine
,W/libprocessgroup(  866): failed to open /acct/uid_10013/pid_6097/cgroup.procs: No such file or directory
,W/jxcore-log( 6322): Platform android
W/jxcore-log( 6322): 
,W/jxcore-log( 6322): Process ARCH arm
W/jxcore-log( 6322): 
W/PackageSettings(  866): Skipping PackageSetting{38c6239d com.example.hello/10317} due to missing metadata
,I/ActivityManager(  866): Process com.google.android.gm (pid 5921) has died
,V/AlarmManager(  866): RTC_WAKEUP set : Alarm{39f4827 type 0 when 1453241209964 com.google.android.googlequicksearchbox} when 1453241209964
,D/UEI.SmartControl( 6257): Internal timer expired: 1
,I/jxcore-log( 6322): JXcore Cordova bridge is ready!
I/jxcore-log( 6322): 
,W/jxcore-log( 6322): JXcore engine is started
I/jxcore-log( 6322): Toggling radios to true
I/jxcore-log( 6322): 
,D/BluetoothAdapter( 6322): enable(): BT is already enabled..!
D/WifiServiceImplEx(  866): setWifiEnabled: true pid=6322, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  866): setWifiEnabled: true pid=6322, uid=10316
D/WifiServiceImplEx(  866): disconnect pid=6322, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  866): reconnect pid=6322, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6322): Radios toggled
I/jxcore-log( 6322): 
I/jxcore-log( 6322): My device name is: LGE-LG-D722
I/jxcore-log( 6322): 
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2740): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/wpa_supplicant( 2740): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
,E/WifiStateMachine(  866): WifiStateMachine: Leaving Connected state
D/WfdsMonitor( 1803): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiConfigStore(  866): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/LGWifiP2pService(  866): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  866): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  866): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  281): Clearing all IP addresses on wlan0
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 7
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 10
,D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 7
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,V/NativeCrypto( 1734): Read error: ssl=0xb0459400: I/O error during system call, Connection timed out
D/WifiHS20(  866): hidePasspointNotification off =false
D/ConnectivityService(  866): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  866): ignoring duplicate network state non-change
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  866): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  866): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-19 23:06:50.516 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
V/NativeCrypto( 1734): SSL shutdown failed: ssl=0xb0459400: I/O error during system call, Broken pipe
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
,I/ActivityManager(  866): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6533 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
E/WifiStateMachine(  866): Start Disconnecting Watchdog 1
D/WifiHS20(  866): hidePasspointNotification off =false
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  866): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  866): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  866): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2740): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-19 23:06:50.606 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/CommandListener(  281): Clearing all IP addresses on wlan0
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  866): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
D/WifiHS20(  866): hidePasspointNotification off =false
D/ConnectivityService(  866): Default network via Wi-Fi disconnect. stop DSQN
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  866): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-19 23:06:50.612 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/DSQN    (  866): disableDataServiceNotify
,D/DSQN    (  866): stop dsqn bin
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  866): ValidatedState{ when=-3ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  866): DefaultState{ when=-21ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  866): Forcing reevaluation
D/WifiNetworkAgent(  866): NetworkAgent: NetworkAgent channel lost
D/WifiHS20(  866): hidePasspointNotification off =false
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  866): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-19 23:06:50.637 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-19 23:06:50.639 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  866): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt(  866): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  866): setSupplicantStateDISCONNECTED
,D/ConnectivityService(  866): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  866):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  866):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/WifiServerServiceExt(  866): SUPPLICANT_STATE_CHANGED_ACTION
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/WifiServerServiceExt(  866): setSupplicantStateSCANNING
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/ConnectivityService(  866): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  866): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
,D/CSLegacyTypeTracker(  866): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  866): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  866): ValidatedState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  866): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  866): Disconnected - quitting
D/ConnectivityService(  866): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  866): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  866): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  866): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1839): |CORE| No family connected
V/NetworkPolicy(  866): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  866): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  866): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  866): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  866): MasterInitialState.processMessage what=3
D/WIFI    (  866): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  866):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  866): [LG_RESTRICTED] !!!isConnected  type  :1
,W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/TelephonyNetworkFactory-1( 1741): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1741):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = -1
D/NetworkManagementService(  866): Removing idletimer
W/Settings(  866): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/DhcpStateMachine(  866): StoppedState
D/DhcpStateMachine(  866): StoppedState{ when=-120ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ResourcesManager( 6533): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6533): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6533): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,W/ResourcesManager( 6533): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/ResourcesManager( 6533): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/IndexDatabaseHelper( 6533): Using schema version: 115
,I/IndexDatabaseHelper( 6533): Index is fine
V/WiFiOffLoadBroadcast( 6533): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6533): MCCMNC not supported: null
,I/ActivityManager(  866): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6556 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6556): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6556): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6556): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6533): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6533): MCCMNC not supported: null
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,I/PCSuite ( 6556): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6556): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6556): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/charger_monitor(  486): init target 500000
V/WiFiOffLoadBroadcast( 6533): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6533): MCCMNC not supported: null
I/PCSuite ( 6556): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6556): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6556): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/charger_monitor(  486): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ActivityManager(  866): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6579 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  866): Killing 6148:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  866): failed to open /acct/uid_10011/pid_6148/cgroup.procs: No such file or directory
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1965): Disconnected process message: 10, size: 0
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  866): battery changed pluggedType: 2
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  866): battery changed pluggedType: 2
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1965): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/ResourcesManager( 6579): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2740): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/Babel_SMS( 6579): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6579): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6579): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6579): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6579): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6579): MmsConfig.loadFromResources
E/Babel_SMS( 6579): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6579): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/LocSvc_java(  866): onReceive
,W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  866): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-19 23:06:51.743 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-19 23:06:51.75 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2740): wlan0: Associated with c0:ff:d4:d3:aa:48
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  866): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/WifiServerServiceExt(  866): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  866): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  866): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  866): setSupplicantStateASSOCIATED
,I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  866): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-19 23:06:51.789 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-19 23:06:51.792 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 2740): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  866): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/wpa_supplicant( 2740): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  866): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  866): setSupplicantStateFOUR_WAY_HANDSHAKE
,I/WifiServiceExtension(  866): setVHTCapabilityType  : false
I/WifiServerServiceExt(  866): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServerServiceExt(  866): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  866): setSecurityType  : 2
,W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  866): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  866): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-19 23:06:51.859 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-19 23:06:51.86 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/ConnectivityService(  866): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  866): Got NetworkAgent Messenger
D/ConnectivityService(  866): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  866): NetworkAgent connected
,D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
E/WifiConfigStore(  866): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  866): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  281): Setting iface cfg
,E/WifiStateMachine(  866): Start Dhcp Watchdog 2
D/DhcpStateMachine(  866): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  866): WaitBeforeStartState
D/WifiServerServiceExt(  866): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  866): setSupplicantStateGROUP_HANDSHAKE
,D/ConnectivityService(  866): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/SensorManager( 6579): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6579): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6579): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6579): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6579): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6579): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6579): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6579): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6579): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6579): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6579): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6579): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6579): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6579): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6579): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6579): found sensor: Motion Accel, handle=46
,I/art     ( 6579): CheckpointMarkThreadRoots callback created = 0xb042d810
,W/Settings( 6579): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6579): startup - clean
,I/art     ( 6579): CheckpointMarkThreadRoots callback created = 0xb042d7e0
,E/WifiStateMachine(  866): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  866): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  866): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@20879e73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  866): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@20879e73 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  866): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  866): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  866): DHCP Start wake lock is acquired.
,D/CommandListener(  281): Setting iface cfg
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  281): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  866): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  866): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  866): setSupplicantStateCOMPLETED
,I/Babel   ( 6579): deleted: false for 0
D/WifiServerServiceExt(  866): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  866): setSupplicantStateCOMPLETED
D/ConnectivityService(  866): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  866): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  866): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  866): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  866): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  866): ignoring duplicate network state non-change
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  866): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-19 23:06:52.035 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  866): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  866): Adding iface wlan0 to network 101
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  866): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-19 23:06:52.042 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  866): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:dr,awable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
E/WifiStateMachine(  866): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  866): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-19 23:06:52.056 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/WifiHS20(  866): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-19 23:06:52.067 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  866): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,E/ConnectivityService(  866): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  866): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  866): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  281): netlink response contains error (File exists)
D/ConnectivityService(  866): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/ConnectivityService(  866): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  866): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  866): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  866): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  866): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  866): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  866): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  866):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  866):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  866):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  866):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  866):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&,NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  866): currentScore = 0, newScore = 20
D/ConnectivityService(  866):    accepting network in place of null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  866): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  866): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  866): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  866): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1741): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  866): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1741):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WIFI    (  866):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  866): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  866): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  866): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  866): [LWD] Start DNSResolver start to wait
D/Tethering(  866): MasterInitialState.processMessage what=3
D/ConnectivityService(  866): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  866): [e] list.add(nai) empty : false size: 1
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  866): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  866): validation of new default Network = false
D/ConnectivityService(  866): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  866): enableDataServiceNotify 
D/DSQN    (  866): start dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  866): [LWD] wait 500ms before dns check
V/NetworkPolicy(  866): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService(  866): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  866):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  866):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  866): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/DSQN    ( 6617): DSQN samuel.seo ver 141203
E/DSQN    ( 6617): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6617): created command queue thread
I/DSQN    ( 6617): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6617): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
V/WiFiOffLoadBroadcast( 6533): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6533): MCCMNC not supported: null
W/AudioCapabilities( 6579): Unsupported mime audio/x-lg-flac
,I/PCSuite ( 6556): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6556): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6556): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6579): Unsupported mime audio/adpcm
W/AudioCapabilities( 6579): Unsupported mime audio/g726
V/WiFiOffLoadBroadcast( 6533): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6579): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6579): Unsupported mime audio/wma-voice
,D/WiFiOffLoadBroadcast( 6533): MCCMNC not supported: null
W/VideoCapabilities( 6579): Unsupported mime video/mjpg
W/VideoCapabilities( 6579): Unsupported mime video/theora
D/DhcpStateMachine(  866): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  866): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  866): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
V/WiFiOffLoadBroadcast( 6533): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6533): Not supported operator for automatic switch
I/dhcpcd  ( 6620): version 5.5.6 starting
V/WiFiOffLoadBroadcast( 6533): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/dhcpcd  ( 6620): get_duid: Read-only file system
D/WiFiOffLoadBroadcast( 6533): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6533): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6533): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6533): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6533): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6533): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6533): MCCMNC not supported: null
I/dhcpcd  ( 6620): wlan0: rebinding lease of 192.168.1.134
W/AudioCapabilities( 6579): Unsupported mime audio/evrc
W/AudioCapabilities( 6579): Unsupported mime audio/qcelp
,V/WiFiOffLoadBroadcast( 6533): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6533): MCCMNC not supported: null
W/VideoCapabilities( 6579): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6533): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6579): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6579): Unsupported mime audio/qcelp
D/WiFiOffLoadBroadcast( 6533): MCCMNC not supported: null
W/AudioCapabilities( 6579): Unsupported mime audio/evrc
V/WiFiOffLoadBroadcast( 6533): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6533): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6533): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6533): MCCMNC not supported: null
W/VideoCapabilities( 6579): Unsupported mime video/mp4v-esdp
,D/CAR.SERVICE( 6427): mConnectedToCar = false, abort
V/WiFiOffLoadBroadcast( 6533): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/rmt_storage(  274): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  274): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  274): wakelock acquired: 1, error no: 42
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,D/WiFiOffLoadBroadcast( 6533): MCCMNC not supported: null
E/ActivityThread( 6427): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@44c77a8 that was originally bound here
E/ActivityThread( 6427): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@44c77a8 that was originally bound here
E/ActivityThread( 6427): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6427): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6427): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6427): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6427): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6427): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6427): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6427): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6427): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6427): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6427): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6427): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6427): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6427): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6427): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6427): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6427): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6427): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6427): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6427): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6427): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6427): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6427): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/dhcpcd  ( 6620): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,E/ActivityThread( 6427): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1cbf3143 that was originally bound here
E/ActivityThread( 6427): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1cbf3143 that was originally bound here
E/ActivityThread( 6427): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6427): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6427): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6427): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6427): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6427): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6427): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6427): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6427): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6427): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6427): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6427): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6427): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6427): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6427): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6427): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6427): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6427): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6427): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6427): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6427): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6427): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  866): Unbind failed: could not find connection for android.os.BinderProxy@f424688
I/PCSuite ( 6556): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6556): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6533): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6533): MCCMNC not supported: null
I/VideoCapabilities( 6579): Unsupported profile 4 for video/mp4v-es
I/dhcpcd  ( 6620): wlan0: leased 192.168.1.134 for 86400 seconds
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
I/PCSuite ( 6556): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6556): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  866): Killing 6216:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/VideoCapabilities( 6579): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6579): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6579): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6579): Unrecognized profile 2130706433 for video/avc
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  274): 
I/rmt_storage(  274): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
W/libprocessgroup(  866): failed to open /acct/uid_10069/pid_6216/cgroup.procs: No such file or directory
,I/ActivityManager(  866): Killing 6238:com.google.android.apps.plus/u0a86 (adj 15): empty #11
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  866): [LWD] DNSResolver start dns
,D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out(  866): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  866): [LWD] DNSResolver end dns
W/libprocessgroup(  866): failed to open /acct/uid_10086/pid_6238/cgroup.procs: No such file or directory
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  866): Checking http://clients3.google.com/generate_204 on "NG700"
,D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/vclib   ( 6579): onServiceConnected
W/Babel   ( 6579): Attempted to change video mute state without an active call.
I/DSQN    ( 6617): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6617): restart monitoring
D/LGDataListener(  281): argv[0]=dsqncommand
D/LGDataListener(  281): argv[1]=wlan0
D/LGDataListener(  281): argv[2]=1
D/LGDataListener(  281): notifyDSQN DSQN STARTMONITOR wlan0 1
,I/DSQN    ( 6617): dsqn report finish
D/DSQN    (  866): DSQM DsqnNotification wlan0  1
D/DSQN    (  866): start to monitor internet connection
I/NotificationManager( 6579): com.google.android.talk: cancel(10436) by com.google.android.talk
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  866): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 19 Jan 2016 22:06:52 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453241212714], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453241212691]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  866): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  866): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  866): Validated
D/ConnectivityService(  866): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  866): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  866):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  866):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  866):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  866): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  866): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  866):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  866):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiDataContinuityService(  866): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  866): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  866): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  866): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1741): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1741):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/WifiServerServiceExt(  866): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  866): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  866):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  866): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  866): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  866): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  866): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  866): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  866): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  866): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  866): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  866): RunningState
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  866): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  866): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  866): identical MTU - not setting
D/Nat464Xlat(  866): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  866): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  866):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  866):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  866): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524295
,D/ConnectivityService(  866): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  866): enableDataServiceNotify 
D/DSQN    (  866): start dsqn bin
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-19 23:06:53.249 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/DSQN    (  866): dsqn is running restart
I/DSQN    ( 6657): DSQN samuel.seo ver 141203
E/DSQN    ( 6657): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6657): created command queue thread
I/DSQN    ( 6657): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6657): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,D/ConnectivityService(  866): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  866): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  866): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  866): onReceive
D/LocSvc_java(  866): got connectivity action
D/LocSvc_java(  866): broadcast - no network connections
D/LocSvc_java(  866): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  866): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  866): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  866): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  866): ignore wifi update if we are not in OPENING or CLOSING
,I/ActivityManager(  866): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6660 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LocSvc_java(  866): onReceive
D/LocSvc_java(  866): got connectivity action
D/LocSvc_java(  866): broadcast - no network connections
D/LocSvc_java(  866): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  866): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  866): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  866): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  866): ignore wifi update if we are not in OPENING or CLOSING
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  866): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  866): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  866): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/MusicStore( 6660): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6660): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6660): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6660): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6660): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6660): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6660): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6660): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6660): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b53681c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6660): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6660): GMSCore installation verified
,I/ConfigStore( 6660): Config Database version: 1
,I/MediaRouter( 6660): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6660): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6660): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  866): Process com.google.android.gms:car (pid 6427) has died
,I/NetworkMonitor( 6660): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  866): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6703 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6660): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-19 23:06:54.962 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/GoogleURLConnFactory( 6660): Using platform SSLCertificateSocketFactory
,V/WifiInternetCheck(  866): Single check msg out of sync, ignoring.
,E/lowmemorykiller(  243): Error writing /proc/6294/oom_score_adj; errno=22
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 6703): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6703): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6703): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/ConnectivityService(  866): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  866): Process com.android.vending (pid 6294) has died
,D/LocSvc_java(  866): onReceive
D/LocSvc_java(  866): got connectivity action
D/LocSvc_java(  866): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  866): Sending msg: 4 arg1:1 arg2:1
D/GpsLocationProvider(  866): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  866): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  866): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  866): ignore wifi update if we are not in OPENING or CLOSING
I/NetworkMonitor( 6660): type=WIFI subType= reason=null isConnected=true
,I/NotificationManager( 6660): com.google.android.music: cancel(1061) by com.google.android.music
D/GpsLocationProvider(  866): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  866): Process com.google.android.talk (pid 6579) has died
,I/LGEmail ( 6703): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6703): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6703): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  866): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6745 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6703): JNI_OnLoad()
I/HubEmail( 6703): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6703): registerNatives()
I/HubEmail( 6703): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6703): registerNativeMethods()
I/HubEmail( 6703): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 6703): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6703): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6745): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6745): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6745): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6745): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6745): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6745): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6745): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6745): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  866): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6772 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6745): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6745): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6745): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6745): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6745): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6745): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/AppUp4:AppBoxCP( 6772): onCreate
W/AppUp4:DB( 6772):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6772):  setFingerPrint start
I/AppUp4:DB( 6772):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6772):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6772):  SDK version = 0
I/AppUp4:DB( 6772):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6772): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6772): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6772): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6772): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6772): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6772): onReceive
I/AppUp4:CustModeStarterReceiver( 6772): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6772): Context : android.app.ReceiverRestrictedContext@447e700
,D/AppUp4:CustFacade( 6772): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6772): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6772): begin check event
I/AppUp4:CustModeStarterReceiver( 6772): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6772): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6772): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6772): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6772): handleAsyncCustNotification do not startCustService
I/ActivityManager(  866): Killing 6461:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  866): failed to open /acct/uid_10014/pid_6461/cgroup.procs: No such file or directory
,D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
I/LgeMiscReceiver( 3206): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3206): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3206): networkInfo.isConnected() = false
,I/ActivityManager(  866): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6792 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,V/AlarmManager(  866): ELAPSED_WAKEUP set : Alarm{2df5d2bf type 2 when 107441 com.google.android.gms} when 107441
,D/libc-netbsd(  281): res_queryN name = xxxxx succeed
,I/System.out(  866): propertyValue:false
D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  866): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  866): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/PhoneMonitor( 6792): Register our PhoneStateListener
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out(  866): propertyValue:false
,I/DSQN    ( 6657): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6657): restart monitoring
I/DSQN    ( 6657): dsqn report finish
D/LGDataListener(  281): argv[0]=dsqncommand
D/LGDataListener(  281): argv[1]=wlan0
D/LGDataListener(  281): argv[2]=1
D/LGDataListener(  281): notifyDSQN DSQN STARTMONITOR wlan0 1
,D/DSQN    (  866): DSQM DsqnNotification wlan0  1
D/DSQN    (  866): start to monitor internet connection
D/MobileConnectivityChangeReceiver( 6792): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6792): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  866): Killing 6533:com.android.settings/1000 (adj 15): empty #11
V/WifiInternetCheck(  866): isHttpConnectionAvailable - We got a valid response : 204
W/libprocessgroup(  866): failed to open /acct/uid_1000/pid_6533/cgroup.procs: No such file or directory
,V/DownloadManager( 3181): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3181): DownloadService onCreate
D/PhoneMonitor( 6792): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6792): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6792): [parse] Load xml
,V/TelephonyAutoProfiling( 6792): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6792): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/CheckinService( 4257): Checkin interval check for package: unspecified last checkin: 1453241190535 min interval config: 0 actual interval: 26106
I/DownloadManager( 3181): in removeSpuriousFiles
I/NotificationManager( 3181): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/PhoneMonitor( 6792): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,V/DownloadManager( 3181): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3181): created cursor android.database.sqlite.SQLiteCursor@26245942 on behalf of 3181
I/ActivityManager(  866): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6832 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/CheckinService( 4257): Checking schedule, now: 1453241216663 next: 1453241220433
I/CheckinService( 4257): active receiver: disabled
V/DownloadManager( 3181): DownloadService onStartCommand
I/DownloadManager( 3181): in trimDatabase
V/DownloadManager( 3181): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3181): created cursor android.database.sqlite.SQLiteCursor@257dbb89 on behalf of 3181
V/DownloadManager( 3181): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3181): created cursor android.database.sqlite.SQLiteCursor@1aa2c78e on behalf of 3181
,V/DownloadManager( 3181): DownloadService onDestroy
,I/ActivityManager(  866): Killing 6257:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 6374): android.os.DeadObjectException
,W/System.err( 6374): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6374): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6374): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6374): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6374): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6374): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6374): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6374): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6374): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6374): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6374): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6374): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6374): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6374): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6374): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6374): android.os.DeadObjectException
W/System.err( 6374): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6374): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6374): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6374): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6374): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6374): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6374): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6374): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6374): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6374): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6374): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6374): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6374): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6374): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6374): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
E/lowmemorykiller(  243): Error opening /proc/6257/oom_score_adj; errno=2
,D/WeatherAncestor( 2770): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:6:57
,W/ProcessCpuTracker(  866): Skipping unknown process pid 6817
W/ProcessCpuTracker(  866): Skipping unknown process pid 6820
W/ActivityManager(  866): Exception when unbinding service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  866): android.os.DeadObjectException
W/ActivityManager(  866): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  866): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  866): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
W/ActivityManager(  866): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1788)
W/ActivityManager(  866): 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:907)
W/ActivityManager(  866): 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15651)
W/ActivityManager(  866): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
W/ActivityManager(  866): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2625)
W/ActivityManager(  866): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:457)
W/ActivityManager(  866): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ActivityManager(  866): Exception when destroying service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  866): android.os.DeadObjectException
W/ActivityManager(  866): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  866): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  866): 	at android.app.ApplicationThreadProxy.scheduleStopService(ApplicationThreadNative.java:946)
W/ActivityManager(  866): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1693)
W/ActivityManager(  866): 	at com.android.server.am.ActiveServices.bringDownServiceIfNeededLocked(ActiveServices.java:1605)
W/ActivityManager(  866): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1805)
W/ActivityManager(  866): 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:907)
W/ActivityManager(  866): 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15651)
W/ActivityManager(  866): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
W/ActivityManager(  866): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2625)
W/ActivityManager(  866): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:457)
W/ActivityManager(  866): 	at android.os.Binder.execTransact(Binder.java:446)
W/libprocessgroup(  866): failed to open /acct/uid_10089/pid_6257/cgroup.procs: No such file or directory
D/UpdateThreadPoolManager( 2770): 2 : This is isUpdating : false
D/WeatherAncestor( 2770): connectivity changed - connection : true
D/Weather_cast( 2770): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2770): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:6:57
D/WeatherService( 2770): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  866): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6857 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 291us total 27.921ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.865ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 26.400ms
,I/ActivityManager(  866): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6883 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  866): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2770): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2770): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2770): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/art     (  866): Explicit concurrent mark sweep GC freed 86845(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.412ms total 185.209ms
,W/ResourcesManager( 6883): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6857): Quickset Services start...
I/UEI.SmartControl( 6857): Manufacture = LGE
,D/UEI.SmartControl( 6857): File observer start...
E/UEI.SmartControl( 6857): IR Port is disabled: false
D/UEI.SmartControl( 6857): Starting file observer...
D/UEI.SmartControl( 6857): Extracting JNI libs...
D/UEI.SmartControl( 6857): --- this system supports 32-bit or 64-bit only
,I/jxcore-log( 6322): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6322): 
,D/UEI.SmartControl( 6857): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6857): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6857): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/Babel_SMS( 6883): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6883): MmsConfig.loadMmsSettings
I/Babel_SMS( 6883): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6883): MmsConfig.loadFromDatabase
,I/UEI.SmartControl( 6857): --- Selecting new region: 2
I/UEI.SmartControl( 6857): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6857): Platform has CIR...
,D/UEI.SmartControl( 6857): NO CIR support, need to check package...
I/UEI.SmartControl( 6857): Model: LG-D722 uses JNI
E/Babel_SMS( 6883): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6883): MmsConfig.loadFromResources
D/UEI.SmartControl( 6857): QS Service created
E/Babel_SMS( 6883): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6883): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6883): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6883): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6883): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6883): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6883): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6883): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6883): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6883): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6883): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6883): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6883): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6883): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6883): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6883): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6883): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6883): found sensor: Motion Accel, handle=46
,I/art     ( 6883): CheckpointMarkThreadRoots callback created = 0xb042d810
,E/UEI.SmartControl( 6857): QS start get config
W/Settings( 6883): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6883): startup - clean
I/art     ( 6883): CheckpointMarkThreadRoots callback created = 0xb042d7f0
D/UEI.SmartControl( 6857): Loading JNI Libs...
D/UEI.SmartControl( 6857):  configuring local db...
,I/Babel   ( 6883): deleted: false for 0
I/ActivityManager(  866): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6930 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6883): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6883): Unsupported mime audio/adpcm
W/AudioCapabilities( 6883): Unsupported mime audio/g726
W/AudioCapabilities( 6883): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6883): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 6883): Unsupported mime video/mjpg
W/VideoCapabilities( 6883): Unsupported mime video/theora
,W/AudioCapabilities( 6883): Unsupported mime audio/evrc
W/AudioCapabilities( 6883): Unsupported mime audio/qcelp
W/VideoCapabilities( 6883): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6883): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6883): Unsupported mime audio/qcelp
W/AudioCapabilities( 6883): Unsupported mime audio/evrc
W/VideoCapabilities( 6883): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6883): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6883): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6883): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6883): Unrecognized profile 2130706433 for video/avc
D/UEI.SmartControl( 6857):  ---- Has DB8: true
,I/ActivityManager(  866): Process com.google.android.music:main (pid 6660) has died
D/UEI.SmartControl( 6857): QS start statue = true Error code = 0
W/VideoCapabilities( 6883): Unrecognized profile 2130706433 for video/avc
D/UEI.SmartControl( 6857): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6857): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 6857): IRRCDataComm has AudioManager!!!!.
I/vclib   ( 6883): onServiceConnected
W/Babel   ( 6883): Attempted to change video mute state without an active call.
,W/irrc_jni( 6857): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6857): IrrcClient ++ 
D/irrcClient( 6857): getIrrcService ++ 
D/irrcClient( 6857): getIrrcService -- 
D/irrcClient( 6857): IrrcClient -- 
W/irrc_jni( 6857): IRRCPlayer_nativeInit -- 
I/NotificationManager( 6883): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6883): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6883): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6883): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6883): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  281): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 6883): propertyValue:false
D/UEI.SmartControl( 6857): Services init done
I/UEI.SmartControl( 6857): Device manager: loading config....
D/UEI.SmartControl( 6857): QS Service init finished
,D/UEI.SmartControl( 6857): Config is loaded...
D/UEI.SmartControl( 6857): QS Service version name: 0.1.73
,D/UEI.SmartControl( 6857): QS Service version code: 1073
D/UEI.SmartControl( 6857): Service requested: Control
D/UEI.SmartControl( 6857): -----IControl: 11
D/UEI.SmartControl( 6857): Caller: com.lge.qremote
D/UEI.SmartControl( 6857): Internal service binding...
D/UEI.SmartControl( 6857): ------------ IControl registerCallback...
I/UEI.SmartControl( 6857): Registering callback...
D/UEI.SmartControl( 6857): -----IControl: 19
D/UEI.SmartControl( 6857): Caller: com.lge.qremote
I/UEI.SmartControl( 6857): Registering Services Ready callback...
D/UEI.SmartControl( 6857):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6857): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6857): -----IControl: 8
D/UEI.SmartControl( 6857): Caller: com.lge.qremote
I/Babel   ( 6883): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  866): Killing 6556:com.lge.sync/1000 (adj 15): empty #11
,W/libprocessgroup(  866): failed to open /acct/uid_1000/pid_6556/cgroup.procs: No such file or directory
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6930): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6930): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6930): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6930): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6930): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6930):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6930):   adb logcat -s GAv4
W/GAv4    ( 6930): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6930): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6930): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6930): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6930): Time to load native libraries: 3 ms (timestamps 145-148)
,I/LibraryLoader( 6930): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6930): Binding Chromium to main looper Looper (main, tid 1) {e3259fd}
I/LibraryLoader( 6930): Expected native library version number "",actual native library version number ""
I/chromium( 6930): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/jxcore-log( 6322): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6322): 
,I/BrowserStartupController( 6930): Initializing chromium process, singleProcess=true
I/jxcore-log( 6322): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6322): 
W/art     ( 6930): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6930): ApplicationContext is null in ApplicationStatus
W/chromium( 6930): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6930): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6930): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6930): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6930): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6930): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6930): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6930): Remote Branch: 
I/Adreno-EGL( 6930): Local Patches: 
I/Adreno-EGL( 6930): Reconstruct Branch: 
I/jxcore-log( 6322): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6322): 
,I/NSApplication( 6930): Starting up...
V/AudioPolicyService(  285): registerClient() client 0xb57e9660, uid 10079
,W/AudioManagerAndroid( 6930): Requires BLUETOOTH permission
I/jxcore-log( 6322): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6322): 
,I/jxcore-log( 6322): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6322): 
I/ActivityManager(  866): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6997 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  866): Killing 6374:com.lge.qremote/u0a106 (adj 15): empty #11
I/jxcore-log( 6322): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6322): 
W/libprocessgroup(  866): failed to open /acct/uid_10106/pid_6374/cgroup.procs: No such file or directory
,I/ActivityManager(  866): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7017 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  866): Killing 6703:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  866): failed to open /acct/uid_10021/pid_6703/cgroup.procs: No such file or directory
,W/ResourcesManager( 7017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/WeatherService( 2770): 2 : TimeTick Intent has been received, Time(hour:min:sec) 23:7:0
,D/WeatherService( 2770): 2 : TimeTick Intent And Screen On
D/WeatherService( 2770): 2 : SDK version : 21
W/ActivityManager(  866): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2770): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2770): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2770): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2770): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2770): 2 : This is isUpdating : false
D/WeatherService( 2770): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2770): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2770): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2770): 2 : Fixed theme : optimus
D/WeatherReflect( 2770): 2 : Map key string is -2
,D/lim     ( 2770): 2 : time = 23:07
I/WeatherReflect( 2770): Model Name : LG-D722
D/WeatherTheme( 2770): 2 : Different view - status_min_formatted : 06 != 07
D/WeatherTheme( 2770): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2770): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,D/Theme   ( 2770): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2770): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2770): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2770): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
,I/[SystemUI]Clock( 1373): called onTimeUpdated()
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
,I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/Weather4x2_optimus( 2770): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
,D/Weather4x2_optimus( 2770): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2770): forecast size is 0
D/Theme   ( 2770): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2770): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2770): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2770): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2770): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2770): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2770): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2770): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2770): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2770): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2770): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2770): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2770): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2770): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2770): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2770): url is : null
D/Theme   ( 2770): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2770): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2770): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2770): 2 : update view, appWidgetId: 2
D/WeatherService( 2770): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 23:7:0
V/AlarmManager(  866): RTC_WAKEUP set : Alarm{36bb13aa type 0 when 1453241220187 com.google.android.googlequicksearchbox} when 1453241220187
,I/ActivityManager(  866): Killing 6745:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,W/libprocessgroup(  866): failed to open /acct/uid_1000/pid_6745/cgroup.procs: No such file or directory
,I/jxcore-log( 6322): Test app app.js loaded
I/jxcore-log( 6322): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6322): setDiscoveryMode: Mode set to BLE
,I/chromium( 6322): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/jxcore-log( 6322): BLE advertisement is supported
I/jxcore-log( 6322): 
I/ActivityManager(  866): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7060 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7060): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7060): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7060): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7060): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7060): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7060): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/JNIHelp ( 7060): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  866): Process com.lge.appbox.client (pid 6772) has died
,W/ActivityThread( 7060): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7060): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b53681c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7060): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7060): GMSCore installation verified
I/ConfigStore( 7060): Config Database version: 1
,I/MediaRouter( 7060): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7060): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7060): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7060): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  866): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7094 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7060): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7060): Using platform SSLCertificateSocketFactory
,I/NotificationManager( 7060): com.google.android.music: cancel(1061) by com.google.android.music
,W/ResourcesManager( 7094): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7094): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7094): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LGEmail ( 7094): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7094): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7094): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  866): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7117 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7094): JNI_OnLoad()
I/HubEmail( 7094): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7094): registerNatives()
I/HubEmail( 7094): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7094): registerNativeMethods()
I/HubEmail( 7094): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7094): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  866): Killing 6792:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  866): failed to open /acct/uid_10038/pid_6792/cgroup.procs: No such file or directory
,W/Settings( 7094): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7117): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7117): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7117): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 7117): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7117): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7117): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7117): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7117): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  866): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7141 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  866): Process com.google.android.apps.magazines (pid 6930) has died
,W/ContextImpl( 7117): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 7117): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7117): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7117): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7117): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7117): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/AppUp4:AppBoxCP( 7141): onCreate
,W/AppUp4:DB( 7141):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7141):  setFingerPrint start
I/AppUp4:DB( 7141):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7141):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7141):  SDK version = 0
I/AppUp4:DB( 7141):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7141): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7141): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7141): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7141): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7141): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7141): onReceive
,I/AppUp4:CustModeStarterReceiver( 7141): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7141): Context : android.app.ReceiverRestrictedContext@447e700
D/AppUp4:CustFacade( 7141): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7141): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7141): begin check event
I/AppUp4:CustModeStarterReceiver( 7141): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7141): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
D/AppUp4:CustModeStarterReceiver( 7141): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7141): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7141): handleAsyncCustNotification do not startCustService
I/ActivityManager(  866): Killing 6832:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  866): failed to open /acct/uid_10051/pid_6832/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3206): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3206): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3206): networkInfo.isConnected() = false
I/ActivityManager(  866): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7160 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7160): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7160): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7160): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  866): Killing 6857:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  866): failed to open /acct/uid_10089/pid_6857/cgroup.procs: No such file or directory
,V/DownloadManager( 3181): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3181): DownloadService onCreate
,I/NotificationManager( 3181): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/PhoneMonitor( 7160): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/DownloadManager( 3181): in removeSpuriousFiles
,V/TelephonyAutoProfiling( 7160): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7160): [parse] Load xml
V/DownloadManager( 3181): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3181): created cursor android.database.sqlite.SQLiteCursor@36fd8745 on behalf of 3181
V/TelephonyAutoProfiling( 7160): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,I/ActivityManager(  866): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7183 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/TelephonyAutoProfiling( 7160): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3181): DownloadService onStartCommand
I/DownloadManager( 3181): in trimDatabase
V/DownloadManager( 3181): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3181): created cursor android.database.sqlite.SQLiteCursor@8e213cb on behalf of 3181
V/DownloadManager( 3181): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 4257): Checkin interval check for package: unspecified last checkin: 1453241190535 min interval config: 0 actual interval: 32297
V/DownloadManager( 3181): created cursor android.database.sqlite.SQLiteCursor@44c77a8 on behalf of 3181
D/PhoneMonitor( 7160): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/CheckinService( 4257): Checking schedule, now: 1453241222854 next: 1453241220433
I/CheckinService( 4257): active receiver: enabled
,I/CheckinService( 4257): Preparing to send checkin request
I/EventLogService( 4257): Accumulating logs since 1453241181603
V/DownloadManager( 3181): DownloadService onDestroy
V/AlarmManager(  866): RTC_WAKEUP set : Alarm{3ce44c41 type 0 when 1453241220433 com.google.android.gms} when 1453241220433
I/ActivityManager(  866): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7210 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  866): RTC_WAKEUP set : Alarm{37b675e6 type 0 when 1453241222897 com.android.vending} when 1453241222897
,I/art     (  310): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 21.424ms
,D/WeatherAncestor( 2770): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:7:2
D/UpdateThreadPoolManager( 2770): 2 : This is isUpdating : false
D/WeatherAncestor( 2770): connectivity changed - connection : true
D/Weather_cast( 2770): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2770): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:7:2
D/WeatherService( 2770): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 23.968ms
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.735ms
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/art     (  866): Explicit concurrent mark sweep GC freed 21794(1148KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.132ms total 175.329ms
,W/ActivityManager(  866): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2770): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2770): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2770): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  866): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7230 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 4257): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4257): Failed to find provider info for com.google.android.wearable.settings
,D/Finsky  ( 7210): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7230): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7230): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7230): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 7230): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7230):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7230):   adb logcat -s GAv4
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7230): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/ActivityManager(  866): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7269 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/GAv4    ( 7230): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/Finsky  ( 7210): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/GAv4    ( 7230): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7230): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/Settings( 7210): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7210): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7210): com.android.vending: cancel(-1050172287) by com.android.vending
W/ResourcesManager( 7269): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7269): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 7210): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7210): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7210): Skipping gmscore version check
V/DownloadManager( 3181): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3181): created cursor android.database.sqlite.SQLiteCursor@1f843a66 on behalf of 7210
D/Finsky  ( 7210): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/MultiDex( 7269): VM with version 2.1.0 has multidex support
,I/MultiDex( 7269): install
I/MultiDex( 7269): VM has multidex support, MultiDex support library is disabled.
D/Finsky  ( 7210): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/JNIHelp ( 7269): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7269): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7269): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@370738d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7269): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7269): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7269): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 7269): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7269): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/sensors_hal_Time(  866): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  866): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  866): tsOffsetIs: Apps: 115011258085; DSPS: 3860146; Offset : -2793745238
D/Finsky  ( 7210): [900] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 7210): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/WebViewFactory( 7230): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/LibraryLoader( 7230): Time to load native libraries: 2 ms (timestamps 5117-5119)
,I/LibraryLoader( 7230): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7230): Binding Chromium to main looper Looper (main, tid 1) {e3259fd}
I/LibraryLoader( 7230): Expected native library version number "",actual native library version number ""
I/chromium( 7230): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/NativeLibraryUtils( 7269): Install completed successfully. count=14 extracted=0
,I/BrowserStartupController( 7230): Initializing chromium process, singleProcess=true
W/art     ( 7230): Attempt to remove local handle scope entry from IRT, ignoring
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
D/WVCdm   (  285): Instantiating CDM.
,I/WVCdm   (  285): CdmEngine::OpenSession
I/WVCdm   (  285): Level3 Library Dec 11 2014 16:13:16
I/ActivityManager(  866): Process com.google.android.music:main (pid 7060) has died
,W/WVCdm   (  285): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  285): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  285): L1 library not specified. Falling Back to L3
I/NSApplication( 7230): Starting up...
,V/AudioPolicyService(  285): registerClient() client 0xb57e97a0, uid 10079
,W/AudioManagerAndroid( 7230): Requires BLUETOOTH permission
I/ActivityManager(  866): Killing 7094:com.lge.email/u0a21 (adj 15): empty #11
I/WVCdm   (  285): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  285): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  285): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  285): CdmEngine::GenerateKeyRequest
D/WVCdm   (  285): PrepareKeyRequest: nonce=2438432000
,I/ActivityManager(  866): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7343 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 7269): CheckpointMarkThreadRoots callback created = 0xaaf14440
,I/art     ( 7269): CheckpointMarkThreadRoots callback created = 0xaaf14430
,I/dex2oat ( 7360): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7360): dex2oat took 110.503ms (threads: 4)
,I/MusicStore( 7343): Database version: 120
I/Adreno-EGL( 7269): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7269): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7269): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7269): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7269): Remote Branch: 
I/Adreno-EGL( 7269): Local Patches: 
I/Adreno-EGL( 7269): Reconstruct Branch: 
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7343): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7343): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7343): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/art     ( 3986): Explicit concurrent mark sweep GC freed 1766(65KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 399us total 28.810ms
,W/ResourcesManager( 7343): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7343): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/WVCdm   (  285): CdmEngine::OpenSession
,V/JNIHelp ( 7343): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7343): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7343): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b53681c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7343): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7343): GMSCore installation verified
,I/ConfigStore( 7343): Config Database version: 1
,I/MediaRouter( 7343): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7343): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7343): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7343): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  866): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7381 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7343): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7343): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  866): Killing 7117:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/ResourcesManager( 7381): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7381): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7381): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  866): failed to open /acct/uid_1000/pid_7117/cgroup.procs: No such file or directory
,I/NotificationManager( 7343): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7381): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7381): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/eas_req ( 7381): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  866): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7414 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7381): JNI_OnLoad()
I/HubEmail( 7381): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7381): registerNatives()
I/HubEmail( 7381): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7381): registerNativeMethods()
I/HubEmail( 7381): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 7381): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  866): Killing 7141:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  866): failed to open /acct/uid_10011/pid_7141/cgroup.procs: No such file or directory
,W/Settings( 7381): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7414): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7414): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7414): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 7414): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7414): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7414): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 7414): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7414): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  866): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7437 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7414): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 7414): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7414): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7414): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7414): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7414): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  866): Killing 7160:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/WVCdm   (  285): CdmEngine::CloseSession
,W/libprocessgroup(  866): failed to open /acct/uid_10038/pid_7160/cgroup.procs: No such file or directory
I/WVCdm   (  285): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  285): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  285): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  285): CdmEngine::GenerateKeyRequest
D/WVCdm   (  285): PrepareKeyRequest: nonce=2399087885
I/AppUp4:AppBoxCP( 7437): onCreate
W/AppUp4:DB( 7437):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7437):  setFingerPrint start
I/AppUp4:DB( 7437):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7437):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7437):  SDK version = 0
I/AppUp4:DB( 7437):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7437): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7437): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7437): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7437): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7437): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7437): onReceive
I/AppUp4:CustModeStarterReceiver( 7437): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 7437): Context : android.app.ReceiverRestrictedContext@447e700
D/AppUp4:CustFacade( 7437): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7437): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7437): begin check event
,I/AppUp4:CustModeStarterReceiver( 7437): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7437): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7437): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7437): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7437): handleAsyncCustNotification do not startCustService
I/ActivityManager(  866): Killing 7183:com.lge.drmservice/u0a51 (adj 15): empty #11
I/MusicWidget( 2671): mDelayedStopHandler : unbind
,W/libprocessgroup(  866): failed to open /acct/uid_10051/pid_7183/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3206): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3206): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3206): networkInfo.isConnected() = true
D/PhoneState( 3206): setPdpRejectCasuse : false
I/MusicBrowser( 2010): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/ActivityManager(  866): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7459 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/MusicBrowser( 2010): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2010): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2010): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
,D/MusicBrowser( 2010): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2010): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2010): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2010): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  866):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@6da9a2ecom.lge.music.MediaPlaybackService$6@33a1d9cf
D/MusicBrowser( 2010): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2010): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@34c4732c
I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2010): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2010): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
,I/MusicBrowser( 2010): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2010): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2010): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2010): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2010): reset
V/MediaPlayer[Native]( 2010): setListener
V/MediaPlayer[Native]( 2010): disconnect
V/MediaPlayer[Native]( 2010): destructor
,V/AudioFlinger(  285): releasing 19 from 2010 for -1
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
V/MediaPlayer[Native]( 2010): disconnect
D/MusicBrowser( 2010): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2010): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2010): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2010): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2010): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2010): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2010): [SmartShareManagerClient] unregisterListener: 291569500
W/SmartShareClient( 2010): [SmartShareManagerClient] unregisterListener invalid listener: 291569500
I/SmartShareClient( 2010): [SmartShareManagerClient] terminate service: 2010/MediaPlaybackService/983001138
E/HomeCloudIF( 2010): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2010): [SmartShareManagerClient] unbindService context:android.app.Application@1142f265
V/CloudHub( 2010): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2010): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2010): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2010): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2010): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  866): Killing 6883:com.google.android.talk/u0a61 (adj 15): empty #11
I/CloudHub( 2010): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29994
D/PhoneMonitor( 7459): Register our PhoneStateListener
,W/libprocessgroup(  866): failed to open /acct/uid_10061/pid_6883/cgroup.procs: No such file or directory
,I/art     (  866): Explicit concurrent mark sweep GC freed 23872(1091KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.116ms total 167.187ms
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/MobileConnectivityChangeReceiver( 7459): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7459): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  866): Killing 7230:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,D/PhoneMonitor( 7459): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7459): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7459): [parse] Load xml
V/TelephonyAutoProfiling( 7459): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7459): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7459): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  866): failed to open /acct/uid_10079/pid_7230/cgroup.procs: No such file or directory
,V/DownloadManager( 3181): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3181): DownloadService onCreate
,I/NotificationManager( 3181): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3181): in removeSpuriousFiles
I/ActivityManager(  866): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7485 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3181): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/CheckinService( 4257): Checkin interval check for package: unspecified last checkin: 1453241190535 min interval config: 0 actual interval: 36959
V/DownloadManager( 3181): DownloadService onStartCommand
,V/DownloadManager( 3181): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3181): created cursor android.database.sqlite.SQLiteCursor@e3259fd on behalf of 3181
V/DownloadManager( 3181): created cursor android.database.sqlite.SQLiteCursor@398996f2 on behalf of 3181
,I/DownloadManager( 3181): in trimDatabase
V/DownloadManager( 3181): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3181): created cursor android.database.sqlite.SQLiteCursor@1cbf3143 on behalf of 3181
,I/ActivityManager(  866): Killing 7210:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  866): failed to open /acct/uid_10036/pid_7210/cgroup.procs: No such file or directory
D/WeatherAncestor( 2770): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:7:7
,D/UpdateThreadPoolManager( 2770): 2 : This is isUpdating : false
V/DownloadManager( 3181): DownloadService onDestroy
D/WeatherAncestor( 2770): connectivity changed - connection : true
D/Weather_cast( 2770): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2770): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:7:7
D/WeatherService( 2770): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  866): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7512 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  866): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2770): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2770): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2770): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7512): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7512): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7512): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7512): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7512): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7512): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7512): MmsConfig.loadFromResources
E/Babel_SMS( 7512): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7512): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/SensorManager( 7512): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7512): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7512): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7512): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7512): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7512): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7512): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7512): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7512): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7512): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7512): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7512): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7512): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7512): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7512): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7512): found sensor: Motion Accel, handle=46
,I/art     ( 7512): CheckpointMarkThreadRoots callback created = 0xb042d800
I/art     ( 7512): CheckpointMarkThreadRoots callback created = 0xb042d7e0
,W/Settings( 7512): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7512): startup - clean
I/Babel   ( 7512): deleted: false for 0
,I/ActivityManager(  866): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7546 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7512): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7512): Unsupported mime audio/adpcm
W/AudioCapabilities( 7512): Unsupported mime audio/g726
,W/AudioCapabilities( 7512): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7512): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7512): Unsupported mime video/mjpg
,W/VideoCapabilities( 7512): Unsupported mime video/theora
,W/AudioCapabilities( 7512): Unsupported mime audio/evrc
,W/AudioCapabilities( 7512): Unsupported mime audio/qcelp
W/VideoCapabilities( 7512): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7512): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7512): Unsupported mime audio/qcelp
W/AudioCapabilities( 7512): Unsupported mime audio/evrc
W/VideoCapabilities( 7512): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7512): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7512): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7512): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7512): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7512): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7512): onServiceConnected
W/Babel   ( 7512): Attempted to change video mute state without an active call.
I/NotificationManager( 7512): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7512): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7512): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7512): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7512): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  281): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 7512): propertyValue:false
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7546): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7546): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7546): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7546): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7546): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7546):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7546):   adb logcat -s GAv4
I/Babel   ( 7512): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  866): Killing 6997:com.android.chrome/u0a48 (adj 15): empty #11
I/WVCdm   (  285): CdmEngine::CloseSession
,I/WVCdm   (  285): L3 Terminate.
W/libprocessgroup(  866): failed to open /acct/uid_10048/pid_6997/cgroup.procs: No such file or directory
,W/GAv4    ( 7546): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7546): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7546): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 7546): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7546): Time to load native libraries: 2 ms (timestamps 9981-9983)
I/LibraryLoader( 7546): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7546): Binding Chromium to main looper Looper (main, tid 1) {e3259fd}
I/LibraryLoader( 7546): Expected native library version number "",actual native library version number ""
I/chromium( 7546): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7546): Initializing chromium process, singleProcess=true
W/art     ( 7546): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7546): ApplicationContext is null in ApplicationStatus
W/chromium( 7546): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7546): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7546): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7546): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7546): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7546): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7546): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7546): Remote Branch: 
I/Adreno-EGL( 7546): Local Patches: 
I/Adreno-EGL( 7546): Reconstruct Branch: 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AudioPolicyService(  285): registerClient() client 0xb57e9660, uid 10079
,I/NSApplication( 7546): Starting up...
W/AudioManagerAndroid( 7546): Requires BLUETOOTH permission
I/Adreno-EGL( 7269): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7269): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7269): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7269): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7269): Remote Branch: 
I/Adreno-EGL( 7269): Local Patches: 
I/Adreno-EGL( 7269): Reconstruct Branch: 
,I/ActivityManager(  866): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7614 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  866): Killing 7017:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 24.403ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.477ms
,I/Adreno-EGL( 7269): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7269): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7269): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7269): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7269): Remote Branch: 
I/Adreno-EGL( 7269): Local Patches: 
I/Adreno-EGL( 7269): Reconstruct Branch: 
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 25.228ms
W/libprocessgroup(  866): failed to open /acct/uid_10086/pid_7017/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 4257): Classify the device as Phone.
,D/libc-netbsd( 4257): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4257): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4257): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4257): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
,I/System.out( 4257): propertyValue:false
D/libc-netbsd( 4257): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4257): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  866): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7637 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  866): Killing 7343:com.google.android.music:main/u0a81 (adj 15): empty #11
,D/libc-netbsd( 4257): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4257): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4257): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4257): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4257): Sending checkin request (9786 bytes)
,W/libprocessgroup(  866): failed to open /acct/uid_10081/pid_7343/cgroup.procs: No such file or directory
,W/ResourcesManager( 7637): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  866): Killing 7381:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  866): failed to open /acct/uid_10021/pid_7381/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 4257): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4257): Failed to find provider info for com.google.android.wearable.settings
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 1734): propertyValue:false
,I/ActivityManager(  866): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7666 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ResourcesManager( 7666): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4257): Classify the device as Phone.
,I/CheckinTask( 4257): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4257): Checking schedule, now: 1453241230271 next: 1453768479264
I/CheckinService( 4257): active receiver: disabled
D/BluetoothManagerService(  866): Message: 20
D/BluetoothManagerService(  866): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ae596b2:true
,D/BluetoothAdapterService(108952287)( 1965): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2d0c1aad
,D/BluetoothAdapterService(108952287)( 1965): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2d0c1aad
I/CheckinService( 4257): Checking schedule, now: 1453241230310 next: 1453768479264
I/CheckinService( 4257): active receiver: disabled
,D/CheckinService( 4257): Recording last checkin time for package unspecified as 1453241230323
I/ActivityManager(  866): Killing 7437:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/ActivityManager(  866): Killing 7414:com.lge.lgdmsclient/1000 (adj 15): empty #12
,W/libprocessgroup(  866): failed to open /acct/uid_10011/pid_7437/cgroup.procs: No such file or directory
,I/ActivityManager(  866): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7695 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  866): failed to open /acct/uid_1000/pid_7414/cgroup.procs: No such file or directory
,V/LGMDMManager( 7666): Create singleton instance
,D/UEI.SmartControl( 7695): Quickset Services start...
,I/UEI.SmartControl( 7695): Manufacture = LGE
D/UEI.SmartControl( 7695): File observer start...
E/UEI.SmartControl( 7695): IR Port is disabled: false
D/UEI.SmartControl( 7695): Starting file observer...
D/UEI.SmartControl( 7695): Extracting JNI libs...
D/UEI.SmartControl( 7695): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7666): getMode name:com.lge.qremote
,I/CheckinService( 4257): Checkin interval check for package: unspecified last checkin: 1453241230323 min interval config: 0 actual interval: 268
,I/CheckinService( 4257): Checking schedule, now: 1453241230600 next: 1453768479264
I/CheckinService( 4257): active receiver: disabled
W/ContextImpl( 3638): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/WearableService( 1734): callingUid 10006, callindPid: 1734
D/LocationInitializer( 4257): Restart initialization of location
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1734): [105] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
,V/SetupWizard( 7459): Connected to Gservices successfully
,D/UEI.SmartControl( 7695): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7695): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 7695): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/AudioManager( 7666): getMode name:com.lge.qremote
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/UEI.SmartControl( 7695): --- Selecting new region: 2
,I/UEI.SmartControl( 7695): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7695): Platform has CIR...
D/UEI.SmartControl( 7695): NO CIR support, need to check package...
I/UEI.SmartControl( 7695): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7695): QS Service created
,E/UEI.SmartControl( 7695): QS start get config
,D/UEI.SmartControl( 7695): Loading JNI Libs...
,D/UEI.SmartControl( 7695):  configuring local db...
D/UEI.SmartControl( 7695):  ---- Has DB8: true
,D/UEI.SmartControl( 7695): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7695): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7695): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7695): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7695): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7695): IrrcClient ++ 
D/irrcClient( 7695): getIrrcService ++ 
,D/irrcClient( 7695): getIrrcService -- 
D/irrcClient( 7695): IrrcClient -- 
W/irrc_jni( 7695): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7695): Services init done
I/UEI.SmartControl( 7695): Device manager: loading config....
D/UEI.SmartControl( 7695): QS Service init finished
,D/UEI.SmartControl( 7695): QS Service version name: 0.1.73
D/UEI.SmartControl( 7695): QS Service version code: 1073
D/UEI.SmartControl( 7695): Service requested: Control
D/UEI.SmartControl( 7695): Config is loaded...
D/UEI.SmartControl( 7695): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7695): Internal service binding...
,D/UEI.SmartControl( 7695): -----IControl: 11
D/UEI.SmartControl( 7695): Caller: com.lge.qremote
D/UEI.SmartControl( 7695): ------------ IControl registerCallback...
I/UEI.SmartControl( 7695): Registering callback...
D/UEI.SmartControl( 7695): -----IControl: 19
D/UEI.SmartControl( 7695): Caller: com.lge.qremote
I/UEI.SmartControl( 7695): Registering Services Ready callback...
I/UEI.SmartControl( 7695): Notify client services are ready...
D/UEI.SmartControl( 7695): -----IControl: 8
D/UEI.SmartControl( 7695): Caller: com.lge.qremote
,I/AudioManager( 7666): getMode name:com.lge.qremote
D/UEI.SmartControl( 7695):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7695): Notify AllClients services are ready: 0
I/AudioManager( 7666): getMode name:com.lge.qremote
,I/art     (  866): Explicit concurrent mark sweep GC freed 19748(951KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.219ms total 149.700ms
,I/AudioManager( 7666): getMode name:com.lge.qremote
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  866): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/ActivityManager(  866): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7755 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/administrator(  866): Handling package changes for user 0
,W/ResourcesManager( 7512): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7512): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/AppUp4:AppBoxCP( 7755): onCreate
,W/AppUp4:DB( 7755):  [AppBoxDatabaseHelper] construct
I/NotificationManager( 7512): com.google.android.talk: cancel(8) by com.google.android.talk
I/AppUp4:DB( 7755):  setFingerPrint start
,I/AppUp4:DB( 7755):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7755):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7755):  SDK version = 0
I/AppUp4:DB( 7755):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7755): AppBoxApplication onCreate()
,V/JNIHelp ( 7512): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:CustModeStarterReceiver( 7755): onReceive
I/AppUp4:CustModeStarterReceiver( 7755): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7755): Context : android.app.ReceiverRestrictedContext@1efba83d
D/AppUp4:CustFacade( 7755): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7755): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7755): begin check event
I/AppUp4:CustModeStarterReceiver( 7755): Event For Nothing, skip.
W/System  ( 7512): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7512): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  866): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7789 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/NotificationService(  866): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  866): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  866): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  866): Process com.google.android.apps.magazines (pid 7546) has died
,I/BackupManagerService(  866): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
,V/BackupManagerService(  866): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  866): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3ac64934
W/ResourcesManager( 7789): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 7789): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7789): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager(  866): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  866): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/AppConfig( 7789): Total System Memory = 906309632
I/GalleryUtils( 7789): Application Heap = 96 MB
I/AppConfig( 7789): App Tier : NOT_DEF
,D/SystemHelper( 7789): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  866): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7811 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1734): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/LocationProviderProxy(  866): applying state to connected service
,W/ResourcesManager( 7811): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7811): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7811): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7811): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7811): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  866): Process com.google.android.apps.plus (pid 7637) has died
,I/SystemConfig( 7811): BUILD Country: EU
I/SystemConfig( 7811): BUILD Operator: OPEN
,I/ActivityManager(  866): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7835 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7811): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7811): existFile = false
I/SystemConfig( 7811): canReadFile = false
,I/SystemConfig( 7811): systemFeature RCS result false
D/SystemConfig( 7811): refreshRcsSupport() :false
,I/LockScreenSettings( 7835): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7835): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7835): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7835): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7835): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7835): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  866): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7852 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  866): Killing 2010:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  285): 2010 died, releasing its sessions
V/AudioFlinger(  285):  pid 1741 @ 0
V/AudioFlinger(  285):  pid 3206 @ 1
V/AudioFlinger(  285):  pid 3206 @ 2
,W/libprocessgroup(  866): failed to open /acct/uid_10028/pid_2010/cgroup.procs: No such file or directory
,I/ActivityManager(  866): Killing 7485:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  866): failed to open /acct/uid_10051/pid_7485/cgroup.procs: No such file or directory
W/ResourcesManager( 7852): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  866): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7877 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  866): Killing 7614:com.android.chrome/u0a48 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 90 ms] updated apps [took 90 ms] 
,W/libprocessgroup(  866): failed to open /acct/uid_10048/pid_7614/cgroup.procs: No such file or directory
D/Finsky  ( 7877): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7877): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7877): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7877): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7877): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3181): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3181): created cursor android.database.sqlite.SQLiteCursor@144f98f9 on behalf of 7877
D/Finsky  ( 7877): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7877): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 7877): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 7877): Skipping gmscore version check
,D/PackageBroadcastService( 4257): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4257): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7877): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  866): Killing 7459:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  866): failed to open /acct/uid_10038/pid_7459/cgroup.procs: No such file or directory
,I/Icing   ( 4257): updateResources: need to parse f{com.google.android.gms}
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/charger_monitor(  486): init target 500000
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/charger_monitor(  486): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1965): Disconnected process message: 10, size: 0
,W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  866): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,D/UEI.SmartControl( 7695): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Icing   ( 4257): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4257): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  866): Killing 7755:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  866): failed to open /acct/uid_10011/pid_7755/cgroup.procs: No such file or directory
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  866): Killing 7512:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  866): failed to open /acct/uid_10061/pid_7512/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  866): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  866): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  866): tsOffsetIs: Apps: 135011899066; DSPS: 4515527; Offset : -2793744867
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  866): ELAPSED_WAKEUP set : Alarm{1413c30 type 2 when 142009 com.google.android.gms} when 142009
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1734): Vacuum at: now=1453241251309 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/PowerManagerService(  866): ALS enabled for SRE
,D/PowerManagerServiceEx(  866): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29330 ms ago)
D/qdlights(  866): set_light_backlight: 254
,D/qdlights(  866): set_light_backlight: 251
,D/qdlights(  866): set_light_backlight: 247
,D/qdlights(  866): set_light_backlight: 244
,D/qdlights(  866): set_light_backlight: 241
,D/qdlights(  866): set_light_backlight: 237
,D/qdlights(  866): set_light_backlight: 234
,D/qdlights(  866): set_light_backlight: 231
,D/qdlights(  866): set_light_backlight: 227
,D/qdlights(  866): set_light_backlight: 224
,D/qdlights(  866): set_light_backlight: 221
,D/qdlights(  866): set_light_backlight: 217
,D/qdlights(  866): set_light_backlight: 214
,D/qdlights(  866): set_light_backlight: 211
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdlights(  866): set_light_backlight: 207
,D/qdlights(  866): set_light_backlight: 204
,D/qdlights(  866): set_light_backlight: 201
,D/qdlights(  866): set_light_backlight: 197
,D/qdlights(  866): set_light_backlight: 194
,D/qdlights(  866): set_light_backlight: 191
,D/qdlights(  866): set_light_backlight: 187
,D/qdlights(  866): set_light_backlight: 184
,D/qdlights(  866): set_light_backlight: 181
,D/qdlights(  866): set_light_backlight: 177
,D/qdlights(  866): set_light_backlight: 174
,D/qdlights(  866): set_light_backlight: 171
,D/qdlights(  866): set_light_backlight: 167
,D/qdlights(  866): set_light_backlight: 164
,D/qdlights(  866): set_light_backlight: 161
,D/qdlights(  866): set_light_backlight: 157
,D/qdlights(  866): set_light_backlight: 154
,D/qdlights(  866): set_light_backlight: 151
,D/qdlights(  866): set_light_backlight: 147
,D/qdlights(  866): set_light_backlight: 144
,D/qdlights(  866): set_light_backlight: 141
,D/qdlights(  866): set_light_backlight: 137
,D/qdlights(  866): set_light_backlight: 134
,D/qdlights(  866): set_light_backlight: 131
,D/qdlights(  866): set_light_backlight: 127
,D/qdlights(  866): set_light_backlight: 124
,D/qdlights(  866): set_light_backlight: 121
,D/qdlights(  866): set_light_backlight: 117
,D/qdlights(  866): set_light_backlight: 114
,D/qdlights(  866): set_light_backlight: 111
,D/qdlights(  866): set_light_backlight: 107
,D/qdlights(  866): set_light_backlight: 104
,D/qdlights(  866): set_light_backlight: 101
,D/qdlights(  866): set_light_backlight: 97
,D/qdlights(  866): set_light_backlight: 94
,D/qdlights(  866): set_light_backlight: 91
,D/qdlights(  866): set_light_backlight: 87
,D/qdlights(  866): set_light_backlight: 84
,D/qdlights(  866): set_light_backlight: 81
,D/qdlights(  866): set_light_backlight: 77
,D/qdlights(  866): set_light_backlight: 74
,D/qdlights(  866): set_light_backlight: 71
,D/qdlights(  866): set_light_backlight: 67
,D/qdlights(  866): set_light_backlight: 64
,D/qdlights(  866): set_light_backlight: 61
,D/qdlights(  866): set_light_backlight: 57
,D/qdlights(  866): set_light_backlight: 54
,D/qdlights(  866): set_light_backlight: 51
,D/qdlights(  866): set_light_backlight: 47
,D/qdlights(  866): set_light_backlight: 44
,D/qdlights(  866): set_light_backlight: 41
,D/qdlights(  866): set_light_backlight: 37
,D/qdlights(  866): set_light_backlight: 34
,D/qdlights(  866): set_light_backlight: 31
,D/qdlights(  866): set_light_backlight: 27
,D/qdlights(  866): set_light_backlight: 24
,D/qdlights(  866): set_light_backlight: 21
,D/qdlights(  866): set_light_backlight: 17
,D/qdlights(  866): set_light_backlight: 14
,D/qdlights(  866): set_light_backlight: 11
,D/qdlights(  866): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  866): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  866): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  866): tsOffsetIs: Apps: 155012641715; DSPS: 5170911; Offset : -2793734717
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  866): ALS enabled for SRE
D/PowerManagerServiceEx(  866): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36322 ms ago)
I/PowerManagerService(  866): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  866): ALS enabled for SRE
D/PowerManagerServiceEx(  866): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36334 ms ago)
W/ContextImpl(  866): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  866): Sleeping (uid 1000)...
D/LPWGController(  866): [updateScreenState] screen on = false
D/LPWGController(  866): disable proximity sensor
D/LPWGController(  866): enable proximity sensor
I/SensorManager(  866): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@29118be1] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  866): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  866): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  866): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  866): activate: handle is 48, enable
V/sensors_hal_Ctx(  866): activate sensors is 1400000000000
D/sensors_hal_Thresh(  866): enable: handle=48
I/sensors_hal_SAM(  866): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  866): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  866): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  866): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  866): enable: Received response: 0
D/PowerManagerServiceEx(  866): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36373 ms ago)
I/Adreno-EGL(  866): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  866): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  866): Build Date: 03/02/15 Mon
I/Adreno-EGL(  866): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  866): Remote Branch: 
I/Adreno-EGL(  866): Local Patches: 
I/Adreno-EGL(  866): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (670 us)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Sensors (  429): sns_pwr.c(273):acquiring wakelock
V/sensors_hal_SAM(  866): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  866): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  866): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  866): processInd: handle 48, count=1
V/sensors_hal_Thresh(  866): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  866): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  866): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  866): poll: count: 256
I/sensors_hal_Ctx(  866): poll: released wakelock sensor_ind
D/sensors_hal_Util(  866): waitForResponse: timeout=0
D/LPWGController(  866): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  866): current mode = 1  value = 1 1
I/LPWGController(  866): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
,I/LPWGController(  866): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  866): set_light_backlight: 0
,I/SensorManager(  866): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  866): activate: handle is 46, disable
,V/sensors_hal_Ctx(  866): activate sensors is 1000000000000
D/sensors_hal_LP2(  866): enable: handle=46
D/sensors_hal_LP2(  866): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  866): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  866): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/sensors_hal_SAM(  866): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  866): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
V/ActivityManager(  866): Display changed displayId=0
,D/DSDPConnection( 1741): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  866): Excessive delay in setPowerMode(): 217ms
I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  866): Got set_interactive hint
D/KeyguardViewMediator( 1373): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1373): notifyScreenOffLocked
,D/KeyguardViewMediator( 1373): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1373): handleNotifyScreenOff
D/SmartCoverViewMediator( 1331): onScreenTurnedOff(3)
,D/ScreenTurnOffBySensor( 1373): unregisterProximitySensor
D/SmartCoverViewMediator( 1331): notifyScreenOffLocked
D/SmartCoverViewMediator( 1331): handleNotifyScreenOFF
D/WifiServerServiceExt(  866): sendKtScanInterval  mRtspPlay : false
D/StatusBarWindowView( 1373): onScreenTurnedOff why = 3
,V/AudioFlinger(  285): setParameters(): io 0, keyvalue screen_state=on, calling pid 866
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=on
V/voice   (  285): voice_set_parameters: enter: screen_state=on
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: exit
V/voice   (  285): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  285): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  285): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  285): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  285): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  285): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  285): adev_set_parameters: exit with code(0)
I/WifiServerServiceExt(  866): set CMD_KT_SCAN_INTERVAL
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
,D/GpsLocationProvider(  866): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1839): |CORE| sendScreenState: state:true
I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1803): stopPatternFlashing()
D/Cliptray Service( 1803): lockStatus = 0
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1786): action : android.intent.action.SCREEN_ON
I/LEDService( 1803): updateLightsLocked : turn off led
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1803): RESTART MSG
,D/NfcServiceNXP( 1786): mScreenState : 3, mInProvisionMode : false
,D/NfcServiceNXP( 1786): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1786): isRequireNfcCRouting() return true
D/LNfcService( 1786): isHCERoutingtoHost() return : true
D/NfcService( 1786): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): newParams.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): screenState= 3
D/NfcService( 1786): Discovery configuration equal, not updating.
D/Ulp_jni (  866): JNI:system_update. Event-0
,D/SplitWindow(  866): check instance of lgWin Window{200249f4 u0 SearchPanel}
,D/InputDispatcher(  866): Window went away: Window{16ec28c3 u0 SearchPanel}
,I/[SystemUI]Clock( 1373): onReceive = android.intent.action.SCREEN_ON
I/Sensors (  429): sns_pwr.c(301):releasing wakelock
,I/LgeClockWidgetControlView( 1373): time changed, timezoneChanged : false
,V/PhoneApp( 1741): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2770): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 23:7:47
,D/WeatherService( 2770): 2 : ACTION screen on
D/WeatherService( 2770): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2770): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2770): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 23:7:47
,W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  866): ACTION_SCREEN_ON
D/AppCleanupService( 4098): android.intent.action.SCREEN_ON
,V/AudioFlinger(  285): setParameters(): io 0, keyvalue screen_state=off, calling pid 866
D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=off
V/voice   (  285): voice_set_parameters: enter: screen_state=off
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: exit
V/voice   (  285): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  285): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  285): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  285): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  285): adev_set_parameters: exit with code(0)
D/WifiController(  866): CMD_SCREEN_OFF 
D/WifiController(  866): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  866): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1839): |CORE| sendScreenState: state:false
,I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1803): clear
I/LEDService( 1803): updateLightsLocked : turn on led
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
E/LEDService( 1803): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1803): Can't handle this request of patternId:0
D/LEDHandler( 1803): RESTART MSG
D/LNfcService( 1786): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1786): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1877): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1741): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2770): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 23:7:47
D/WeatherService( 2770): 2 : ACTION screen off
D/WeatherService( 2770): 2 : TimeTick Receiver Unregister
D/WeatherService( 2770): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 23:7:47
,W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  866): ACTION_SCREEN_OFF
D/AppCleanupService( 4098): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4098): AppUsageStatsSaveTask
,E/NxpNfcJni( 1786): getReconnectState = 0x0
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
D/LNfcService( 1786): isRequireNfcCRouting() return true
D/LNfcService( 1786): isHCERoutingtoHost() return : true
D/NfcService( 1786): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): newParams.techmask= mTechMask: 0
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): screenState= 1
E/NxpNfcJni( 1786): getReconnectState = 0x0
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1373): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  866): ELAPSED_WAKEUP set : Alarm{3a3a051d type 2 when 162232 com.android.systemui} when 162232
,D/PhoneUtils( 1741): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1741): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1741): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1741): getCallState : 0
,D/PhoneUtils( 1741): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1741): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1741): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1373): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1373): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
,I/[SystemUI]Clock( 1373): called onTimeUpdated()
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  866): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  866): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  866): tsOffsetIs: Apps: 175013356968; DSPS: 5826295; Offset : -2793752017
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  486): init target 500000
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,D/HeadsetStateMachine( 1965): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  866): battery changed pluggedType: 2
D/PowerManagerServiceEx(  866): acquireWakeLockInternal: lock=162608018, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=866
,V/AlarmManager(  866): ELAPSED_WAKEUP set : Alarm{1315a163 type 2 when 188325 com.google.android.gms} when 188325
D/PowerManagerServiceEx(  866): releaseWakeLockInternal: lock=162608018 [*alarm*], flags=0x0
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/PhenotypeConfigurator( 1734): Scheduling Phenotype for one-off execution 10233 seconds from now (1453241297670)
,D/GetConfigurationSnapshotOperation( 1734): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1734): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1734): Using platform SSLCertificateSocketFactory
I/art     ( 1734): Explicit concurrent mark sweep GC freed 45121(2MB) AllocSpace objects, 35(560KB) LOS objects, 40% free, 14MB/23MB, paused 1.741ms total 114.566ms
,D/LocationManagerService(  866): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
,I/System.out( 1734): propertyValue:false
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  866): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  866): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  866): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     (  866): Explicit concurrent mark sweep GC freed 55653(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 2.549ms total 152.311ms
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  866): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  866): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  866): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/AlarmManager(  866): ELAPSED_WAKEUP set : Alarm{1761a953 type 2 when 191297 android} when 191297
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  866): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  866): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  866): tsOffsetIs: Apps: 195014120449; DSPS: 6481680; Offset : -2793751475
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  866): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  866): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  866): tsOffsetIs: Apps: 215014865598; DSPS: 7137064; Offset : -2793740831
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  866): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  866): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  866): tsOffsetIs: Apps: 235015532101; DSPS: 7792446; Offset : -2793744283
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  486): init target 500000
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1965): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  866): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1965): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  866): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  486): init target 500000
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1965): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  866): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  866): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  866): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  866): tsOffsetIs: Apps: 255016283760; DSPS: 8447831; Offset : -2793754547
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  866): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  866): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  866): tsOffsetIs: Apps: 275017031565; DSPS: 9103215; Offset : -2793739529
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  866): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  866): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  866): tsOffsetIs: Apps: 295017704057; DSPS: 9758597; Offset : -2793740480
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/HeadsetStateMachine( 1965): Disconnected process message: 10, size: 0
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  866): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1965): Disconnected process message: 10, size: 0
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  866): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1965): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  866): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1965): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  866): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1734): disconnect managed GoogleApiClient
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  866): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  866): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  866): tsOffsetIs: Apps: 315029176029; DSPS: 10414333; Offset : -2793740931
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1965): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  866): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  866): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  866): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6322): --= Surplus to requirements =--
I/jxcore-log( 6322): 
I/jxcore-log( 6322): ****TEST TOOK:  ms ****
I/jxcore-log( 6322): 
I/jxcore-log( 6322): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6322): 
,D/AndroidRuntime( 8097): 
D/AndroidRuntime( 8097): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8097): CheckJNI is OFF
,D/AndroidRuntime( 8097): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  866): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  866): Killing 6322:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
W/PackageSettings(  866): Skipping PackageSetting{38c6239d com.example.hello/10317} due to missing metadata
,I/WindowState(  866): WIN DEATH: Window{356a3d4e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  866): Focus left window: Window{356a3d4e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  866): Window went away: Window{356a3d4e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  866):   Force finishing activity ActivityRecord{373d0292 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  866): Display changed displayId=0
,D/DSDPConnection( 1741): Display #0 changed.
W/ActivityManager(  866): Spurious death for ProcessRecord{3f5e9290 6322:com.test.thalitest/u0a316}, curProc for 6322: null
,I/ActivityManager(  866): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  866):   Force finishing activity ActivityRecord{373d0292 u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  866): Duplicate finish request for ActivityRecord{373d0292 u0 com.test.thalitest/.MainActivity t222 f}
,I/art     ( 1937): Explicit concurrent mark sweep GC freed 9325(544KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 12MB/21MB, paused 2.261ms total 90.712ms
,I/art     ( 4257): Explicit concurrent mark sweep GC freed 4168(216KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 14MB/18MB, paused 834us total 97.647ms
,I/[LGHome]EVENT( 1877): [Launcher.java:5203:onStart()]onStart
D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,W/System.err( 3638): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,I/InputReader(  866): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1734): Ignoring removeGeofence because network location is disabled.
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/System.err( 3638): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3638): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3638): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3638): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3638): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3638): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3638): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3638): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3638): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3638): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3638): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[LGHome]EVENT( 1877): [Launcher.java:776:onResume()]onResume
,I/ActivityManager(  866): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8128 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1877): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
,I/[LGHome]EVENT( 1877): [Launcher.java:929:onResume()]onResume end
I/Activity( 1877): Activity.onPostResume() called 
D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
,W/ResourcesManager( 1373): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1373): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourcesManager( 1373): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/[LGHome]LGWallpaperInfo( 1877): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1877): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/art     (  866): Explicit concurrent mark sweep GC freed 20595(1564KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 3.356ms total 265.957ms
I/art     (  866): WaitForGcToComplete blocked for 215.793ms for cause Explicit
,W/ResourcesManager( 1373): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1373): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1373): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
I/SystemUI[Framework](  866): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/InputDispatcher(  866): Focus entered window: Window{345da57d u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PhoneWindowManagerEx(  866): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  866): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  866): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  866): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@35d54b59,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  866): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  866): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  866): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  866): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  866): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  866): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@35d54b59,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  866): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1373): handleShortcutListChanged...
,W/ResourcesManager( 8128): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8128): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8128): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/administrator(  866): Handling package changes for user 0
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
,I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1877): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
,W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
D/KeyguardModel( 1373): handleShortcutListChanged...
,I/NotificationService(  866): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  866): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  866): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
,D/TaskPersister(  866): removeObsoleteFile: deleting file=222_task.xml
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
W/InputMethodManagerService(  866): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  866): Got RemoteException sending setActive(false) notification to pid 6322 uid 10316
I/art     (  866): Explicit concurrent mark sweep GC freed 5947(340KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.059ms total 277.590ms
,I/LGEmail ( 8128): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/LGEmail ( 8128): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/Timeline(  866): Timeline: Activity_windows_visible id: ActivityRecord{659cfaa u0 com.lge.launcher2/.Launcher t221} time:333407
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,W/IInputConnectionWrapper( 1877): getTextBeforeCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1605): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,D/AndroidRuntime( 8097): Shutting down VM
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1877): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/ResourcesManager(  866): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,W/ResourceType(  866): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/PackageChangeReceiver( 8128): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ActivityManager(  866): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8157 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  866): Killing 7789:com.android.gallery3d/u0a23 (adj 15): empty #11
I/art     (  310): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 300us total 23.556ms
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/art     (  310): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 20.846ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 21.904ms
,W/libprocessgroup(  866): failed to open /acct/uid_10023/pid_7789/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 8157): onCreate
,W/AppUp4:DB( 8157):  [AppBoxDatabaseHelper] construct
E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/AppUp4:DB( 8157):  setFingerPrint start
I/AppUp4:DB( 8157):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 8157):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8157):  SDK version = 0
I/AppUp4:DB( 8157):  beforefinger == newfinger no write in DB
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/AppUp4:AppBoxApplication( 8157): AppBoxApplication onCreate()
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
E/SQLiteLog( 8157): (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
E/SQLiteDatabase( 8157): Error inserting package=com.test.thalitest
E/SQLiteDatabase( 8157): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 8157): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 8157): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:790)
E/SQLiteDatabase( 8157): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 8157): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 8157): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1581)
E/SQLiteDatabase( 8157): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1451)
E/SQLiteDatabase( 8157): 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
E/SQLiteDatabase( 8157): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 8157): 	at android.content.ContentResolver.insert(ContentResolver.java:1267)
E/SQLiteDatabase( 8157): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
E/SQLiteDatabase( 8157): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
E/SQLiteDatabase( 8157): 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
E/SQLiteDatabase( 8157): 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
E/SQLiteDatabase( 8157): 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
E/SQLiteDatabase( 8157): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/SQLiteDatabase( 8157): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/SQLiteDatabase( 8157): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/SQLiteDatabase( 8157): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8157): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8157): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 8157): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8157): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8157): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 8157): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  866): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8176 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  866): Killing 7811:com.android.contacts/u0a18 (adj 15): empty #11
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created

```
