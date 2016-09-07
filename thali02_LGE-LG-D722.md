#### Test 83627337381d561_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
09-07 11:37:03.759  1764  4432 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-07 11:37:04.462   292   359 I ThermalEngine: Sensor:pa_therm0:31000 mC
,09-07 11:37:04.817  6566  6566 D AndroidRuntime: 
09-07 11:37:04.817  6566  6566 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-07 11:37:04.822  6566  6566 D AndroidRuntime: CheckJNI is OFF
09-07 11:37:04.845  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 11:37:04.845  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:04.846  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
09-07 11:37:05.072  6566  6566 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-07 11:37:05.089   943  2015 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 11:37:05.151   943  2015 D ActivityManager: setTaskToReturnTo : TaskRecord{291f6f26 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 11:37:05.153   943  2015 D ActivityManager: setTaskToReturnTo : TaskRecord{291f6f26 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 11:37:05.176   943  2015 D WindowStateEx: AppWindowTokenEx init.. 
09-07 11:37:05.191   943  1053 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-07 11:37:05.208   943  1053 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-07 11:37:05.231   943  1053 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-07 11:37:05.231   943  1053 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-07 11:37:05.238   943  2015 D InputDispatcher: Focus left window: Window{d570433 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
09-07 11:37:05.241  1951  1951 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
09-07 11:37:05.241  6566  6566 D AndroidRuntime: Shutting down VM
09-07 11:37:05.255   943  1053 D SplitWindow: check instance of lgWin Window{29cb3cfe u0 Starting com.test.thalitest}
09-07 11:37:05.318   943  1974 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6586 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-07 11:37:05.342  1951  1951 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
09-07 11:37:05.390  1951  1951 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
09-07 11:37:05.396   943  2541 I WindowStateAnimator: Starting window displayed
09-07 11:37:05.402   943  1051 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
09-07 11:37:05.411   943  1051 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
09-07 11:37:05.414   943  1051 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
09-07 11:37:05.414   943  1051 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
09-07 11:37:05.415   943  1051 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-07 11:37:05.417   943  1051 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@7d2987b,  pkg=WindowManager.LayoutParams
09-07 11:37:05.417   943  1051 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
09-07 11:37:05.422  1377  1377 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
09-07 11:37:05.425  1377  1377 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
09-07 11:37:05.425  1377  1377 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
09-07 11:37:05.425  1377  1377 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
09-07 11:37:05.464  2028  2028 I HotwordDetector: Closing mic
09-07 11:37:05.475  2028  2570 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@1fd6ceeb
09-07 11:37:05.475  2028  2570 V AudioRecord: stop()
09-07 11:37:05.475  2028  2570 D AudioRecord: AudioRecord->stop()
09-07 11:37:05.475   282  1300 V AudioFlinger: RecordHandle::stop()
09-07 11:37:05.476   282  1300 V AudioFlinger: RecordThread::stop
09-07 11:37:05.480   282  1300 V AudioFlinger: Record stopped OK
09-07 11:37:05.482   282  1300 V AudioPolicyManager: stopInput() input 17
09-07 11:37:05.484   282  1300 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
09-07 11:37:05.484   282  1300 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
09-07 11:37:05.484   282  1067 V AudioPolicyService: AudioCommandThread() waking up
09-07 11:37:05.484   282  1067 V AudioPolicyService: AudioCommandThread() processing release audio patch
09-07 11:37:05.484   282  1067 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
09-07 11:37:05.485   282  1067 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
09-07 11:37:05.485   282  1067 V AudioFlinger: ThreadBase::setParameters() routing=0
09-07 11:37:05.485   282  1067 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
09-07 11:37:05.485   282  2591 V AudioFlinger: processConfigEvents_l() remaining events 1
09-07 11:37:05.485   282  2591 V AudioFlinger: processConfigEvents_l() DONE thread 0xb387f000
09-07 11:37:05.488   282  2591 D audio_hw_primary: in_standby: enter: stream (0xb546dde0) usecase(7: audio-record)
09-07 11:37:05.535   282  2591 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
09-07 11:37:05.535   282  2591 V audio_hw_primary: disable_audio_route: enter: usecase(7)
09-07 11:37:05.535   282  2591 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
09-07 11:37:05.535   282  2591 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-07 11:37:05.539   282  2591 V audio_hw_primary: disable_audio_route: exit
09-07 11:37:05.539   282  2591 E audio_hw_primary: disable_snd_device: enter 144
09-07 11:37:05.539   282  2591 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
09-07 11:37:05.539   282  2591 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
09-07 11:37:05.543   282  2591 V audio_hw_primary: stop_input_stream: exit: status(0)
09-07 11:37:05.543   282  2591 V audio_hw_primary: in_standby: exit:  status(0)
09-07 11:37:05.543   282  2591 V AudioFlinger: RecordThread: loop stopping
09-07 11:37:05.543   282  1067 V AudioPolicyService: AudioCommandThread() going to sleep
09-07 11:37:05.544   282  1300 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
09-07 11:37:05.544   282  1300 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
09-07 11:37:05.544   282  1300 V AudioPolicyService: AudioCommandThread() adding update audio patch list
09-07 11:37:05.544   282  1300 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
09-07 11:37:05.544   282  1068 V AudioPolicyService: AudioCommandThread() waking up
09-07 11:37:05.544   282  1068 V AudioPolicyService: AudioCommandThread() processing update audio patch list
09-07 11:37:05.544   282  1068 V AudioPolicyService: AudioCommandThread() going to sleep
09-07 11:37:05.548   282  1300 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
09-07 11:37:05.548   282  1300 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
09-07 11:37:05.548   282  1067 V AudioPolicyService: AudioCommandThread() waking up
09-07 11:37:05.548   282  1067 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
09-07 11:37:05.548   282  1067 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 282
09-07 11:37:05.548   282  1067 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
09-07 11:37:05.548   282  1067 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
09-07 11:37:05.548   282  2591 V AudioFlinger: RecordThread: loop starting
09-07 11:37:05.549   282  2591 V AudioFlinger: processConfigEvents_l() remaining events 1
09-07 11:37:05.549   282  2591 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
09-07 11:37:05.549   282  2591 V audio_hw_primary: in_set_parameters: exit: status(0)
09-07 11:37:05.549   282  2591 V AudioFlinger: processConfigEvents_l() DONE thread 0xb387f000
09-07 11:37:05.549   282  2591 V AudioFlinger: RecordThread: loop stopping
09-07 11:37:05.549   282  1067 V AudioPolicyService: AudioCommandThread() going to sleep
09-07 11:37:05.550  2028  2570 V AudioRecord: stop()
09-07 11:37:05.550  2028  2570 V AudioRecord: stop()
09-07 11:37:05.550  2028  2570 V AudioRecord: stop()
09-07 11:37:05.552   282   282 V AudioFlinger: releasing 16 from 2028 for -1
09-07 11:37:05.552   282   282 V AudioFlinger:  decremented refcount to 0
09-07 11:37:05.552   282   282 V AudioFlinger: purging stale effects
09-07 11:37:05.552   282   282 V AudioFlinger: RecordHandle::stop()
09-07 11:37:05.552   282   282 V AudioFlinger: RecordThread::stop
09-07 11:37:05.552   282   282 V AudioPolicyManager: releaseInput() 17
09-07 11:37:05.552   282   282 V AudioPolicyManager: closeInput(17)
09-07 11:37:05.552   282   282 V AudioFlinger: closeInput() 17
09-07 11:37:05.552   282   282 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-07 11:37:05.552  2028  2049 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-07 11:37:05.552   943  1919 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-07 11:37:05.552   282   282 V AudioFlinger: ThreadBase::exit
09-07 11:37:05.552  1377  2757 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-07 11:37:05.552  2079  2096 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-07 11:37:05.552  1793  1819 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-07 11:37:05.552  3162  3183 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-07 11:37:05.552  2889  2905 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-07 11:37:05.553   282  2591 V AudioFlinger: RecordThread: loop starting
09-07 11:37:05.553   282  2591 V AudioFlinger: RecordThread 0xb387f000 exiting
09-07 11:37:05.554   282   282 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546dde0)
09-07 11:37:05.554   282   282 D audio_hw_primary: in_standby: enter: stream (0xb546dde0) usecase(7: audio-record)
09-07 11:37:05.554   282   282 V audio_hw_primary: in_standby: exit:  status(0)
09-07 11:37:05.554   282   282 V AudioPolicyService: AudioCommandThread() adding update audio port list
09-07 11:37:05.554   282   282 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
09-07 11:37:05.554   282   282 V AudioPolicyManager: releaseInput() exit
09-07 11:37:05.554   282  1068 V AudioPolicyService: AudioCommandThread() waking up
09-07 11:37:05.554   282  1068 V AudioPolicyService: AudioCommandThread() processing update audio port list
09-07 11:37:05.554   282   282 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
09-07 11:37:05.554   282   282 V AudioFlinger: removeClient_l() pid 2028, calling pid 282
09-07 11:37:05.554   282  1068 V AudioPolicyService: AudioCommandThread() going to sleep
09-07 11:37:05.559  2028  2579 I HotwordRecognitionRnr: Stopping hotword detection.
09-07 11:37:05.568  1377  1377 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
09-07 11:37:05.568  1951  1951 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-07 11:37:05.573  1951  1951 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-07 11:37:05.573  1951  1951 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
09-07 11:37:05.574  2028  2588 I HotwordRecognitionRnr: Hotword detection finished
09-07 11:37:05.575  1913  1913 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
09-07 11:37:05.586   943  1289 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-07 11:37:05.586  1951  1951 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-07 11:37:05.608   943  1030 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6616 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-07 11:37:05.609   943   943 D administrator: Handling package changes for user 0
09-07 11:37:05.614  6586  6586 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-07 11:37:05.615  1377  1377 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-07 11:37:05.624  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
09-07 11:37:05.624  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
09-07 11:37:05.624  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
09-07 11:37:05.624  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
09-07 11:37:05.624  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
09-07 11:37:05.624  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
09-07 11:37:05.624  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
09-07 11:37:05.625  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
09-07 11:37:05.625  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
09-07 11:37:05.625  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
09-07 11:37:05.625  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
09-07 11:37:05.625  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
09-07 11:37:05.625  1377  1377 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-07 11:37:05.684  6616  6616 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-07 11:37:05.764  6586  6586 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
09-07 11:37:05.794   943   943 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-07 11:37:05.794   943   943 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-07 11:37:05.794   943   943 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
09-07 11:37:05.802   943   943 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
09-07 11:37:05.820   943   943 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
09-07 11:37:05.822   943   943 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@248d0417
09-07 11:37:05.846  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 11:37:05.847  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:05.847  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-07 11:37:05.856  6586  6586 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9913-9915)
09-07 11:37:05.857  6586  6586 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 11:37:05.888   943  1028 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 11:37:05.917  6586  6586 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3890d4f3}
09-07 11:37:05.918  6586  6586 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 11:37:05.919  6586  6586 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 11:37:05.949  6586  6586 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-07 11:37:05.950  6586  6586 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 11:37:05.952  6586  6586 E SysUtils: ApplicationContext is null in ApplicationStatus
09-07 11:37:05.954   943  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{217617a type 2 when 120000 com.google.android.gms} when 120000
09-07 11:37:05.985  6586  6586 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-07 11:37:05.992  6586  6586 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 11:37:05.992  6586  6586 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 11:37:05.993  6586  6586 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 11:37:05.993  6586  6586 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 11:37:05.993  6586  6586 I Adreno-EGL: Build Date: 03/02/15 Mon
09-07 11:37:05.993  6586  6586 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-07 11:37:05.993  6586  6586 I Adreno-EGL: Remote Branch: 
09-07 11:37:05.993  6586  6586 I Adreno-EGL: Local Patches: 
09-07 11:37:05.993  6586  6586 I Adreno-EGL: Reconstruct Branch: 
09-07 11:37:06.039   943  1028 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-07 11:37:06.083  1951  1951 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-07 11:37:06.100  1764  1764 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
09-07 11:37:06.118   282  1607 V AudioPolicyService: registerClient() client 0xb4027260, uid 10030
,09-07 11:37:06.122  6616  6647 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-07 11:37:06.123  6616  6647 I Babel_SMS: MmsConfig.loadMmsSettings
09-07 11:37:06.130   943  1052 D BluetoothManagerService: Message: 20
09-07 11:37:06.130   943  1052 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cae59f7:true
,09-07 11:37:06.137  2079  2096 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
09-07 11:37:06.144  6616  6647 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-07 11:37:06.144  6616  6647 I Babel_SMS: MmsConfig.loadFromDatabase
,09-07 11:37:06.194  6616  6647 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-07 11:37:06.194  6616  6647 I Babel_SMS: MmsConfig.loadFromResources
09-07 11:37:06.195  1852  1852 D LCardEmulationManager: getHceAppCount hostAppNum : 0
09-07 11:37:06.195  1852  1852 D LCardEmulationManager: getDefaultRoute
09-07 11:37:06.197  6616  6647 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-07 11:37:06.198  6616  6647 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-07 11:37:06.206   943  1028 D LocationProviderProxy: applying state to connected service
,09-07 11:37:06.217  6616  6616 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
09-07 11:37:06.217  6616  6616 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
,09-07 11:37:06.217  6616  6616 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
09-07 11:37:06.217  6616  6616 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
09-07 11:37:06.217  6616  6616 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
09-07 11:37:06.217  6616  6616 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
09-07 11:37:06.217  6616  6616 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
09-07 11:37:06.217  6616  6616 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
09-07 11:37:06.218  6616  6616 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
09-07 11:37:06.218  6616  6616 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
09-07 11:37:06.218  6616  6616 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
09-07 11:37:06.218  6616  6616 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
09-07 11:37:06.218  6616  6616 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
09-07 11:37:06.218  6616  6616 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
09-07 11:37:06.218  6616  6616 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
09-07 11:37:06.218  6616  6616 D SensorManager: found sensor: Motion Accel, handle=46
09-07 11:37:06.256  6616  6616 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 11:37:06.264  6616  6616 I Babel_Crash: startup - clean
09-07 11:37:06.281  2889  2889 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19955
,09-07 11:37:06.302  6616  6630 I art     : CheckpointMarkThreadRoots callback created = 0xb042d910
,09-07 11:37:06.315  6616  6661 I Babel   : deleted: false for 0
09-07 11:37:06.336  6616  6630 I art     : CheckpointMarkThreadRoots callback created = 0xb042d900
,09-07 11:37:06.358  6586  6586 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 11:37:06.377  6586  6586 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-07 11:37:06.388  6586  6586 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-07 11:37:06.392  6586  6586 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
,09-07 11:37:06.393  6586  6586 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-07 11:37:06.408  6616  6616 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,09-07 11:37:06.415  6586  6586 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
09-07 11:37:06.422  6616  6616 W AudioCapabilities: Unsupported mime audio/adpcm
,09-07 11:37:06.431  6616  6616 W AudioCapabilities: Unsupported mime audio/g726
09-07 11:37:06.432  6616  6616 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-07 11:37:06.433  6616  6616 W AudioCapabilities: Unsupported mime audio/wma-voice
,09-07 11:37:06.435  6616  6616 W VideoCapabilities: Unsupported mime video/mjpg
09-07 11:37:06.438  6616  6616 W VideoCapabilities: Unsupported mime video/theora
09-07 11:37:06.447   943  4928 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6664 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-07 11:37:06.450  6586  6586 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 11:37:06.450  6586  6586 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 11:37:06.497  6616  6616 W AudioCapabilities: Unsupported mime audio/evrc
,09-07 11:37:06.498  6616  6616 W AudioCapabilities: Unsupported mime audio/qcelp
09-07 11:37:06.500  6616  6616 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 11:37:06.519  6616  6616 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-07 11:37:06.520  6586  6586 I Activity: Activity.onPostResume() called 
09-07 11:37:06.522  6616  6616 W AudioCapabilities: Unsupported mime audio/qcelp
,09-07 11:37:06.525  6616  6616 W AudioCapabilities: Unsupported mime audio/evrc
09-07 11:37:06.532  6586  6685 D OpenGLRenderer: Render dirty regions requested: true
09-07 11:37:06.533  6586  6685 I OpenGLRenderer: Initialized EGL, version 1.4
,09-07 11:37:06.540  6616  6616 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-07 11:37:06.547  6586  6685 D OpenGLRenderer: Enabling debug mode 0
,09-07 11:37:06.558  6616  6616 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-07 11:37:06.573  6586  6586 D Atlas   : Validating map...
09-07 11:37:06.575  6616  6616 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-07 11:37:06.577  6616  6616 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 11:37:06.579  6664  6664 I AppUp4:AppBoxCP: onCreate
09-07 11:37:06.579   943  4928 D SplitWindow: check instance of lgWin Window{a8da530 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 11:37:06.584  6616  6616 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-07 11:37:06.586  6664  6664 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-07 11:37:06.592  6586  6651 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-07 11:37:06.600  6664  6664 I AppUp4:DB:  setFingerPrint start
09-07 11:37:06.600  6664  6664 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
,09-07 11:37:06.613  6664  6664 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
09-07 11:37:06.613  6664  6664 I AppUp4:DB:  SDK version = 21
09-07 11:37:06.613  6664  6664 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-07 11:37:06.615  6616  6616 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-07 11:37:06.621  6664  6664 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-07 11:37:06.631   943  1949 D InputDispatcher: Focus entered window: Window{a8da530 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 11:37:06.631  6664  6664 I AppUp4:CustModeStarterReceiver: onReceive
,09-07 11:37:06.632  6664  6664 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
09-07 11:37:06.646  6664  6664 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@22c1ea57
09-07 11:37:06.646  6664  6664 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 11:37:06.650  6664  6664 D AppUp4:CustFacade: isSimDevice : true
09-07 11:37:06.652  6664  6664 D AppUp4:CustModeStarterReceiver: begin check event
,09-07 11:37:06.652  6664  6664 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-07 11:37:06.654   943  1608 I ActivityManager: Killing 6188:com.google.android.apps.plus/u0a86 (adj 15): empty #11
09-07 11:37:06.701   943  1949 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,09-07 11:37:06.726  6586  6586 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1bd2fe55 time:120785
,09-07 11:37:06.738  6616  6630 W art     : Suspending all threads took: 5.251ms
,09-07 11:37:06.747   943  4928 W libprocessgroup: failed to open /acct/uid_10086/pid_6188/cgroup.procs: No such file or directory
09-07 11:37:06.805   943  1608 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6693 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-07 11:37:06.811   943  1053 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s525ms
09-07 11:37:06.812   943  1053 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{33a41767 u0 com.test.thalitest/.MainActivity t259} time:120870
09-07 11:37:06.814  6616  6616 I vclib   : onServiceConnected
09-07 11:37:06.814  6616  6616 W Babel   : Attempted to change video mute state without an active call.
09-07 11:37:06.841  6616  6686 I NotificationManager: com.google.android.talk: cancel(8) by com.google.android.talk
,09-07 11:37:06.850  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 11:37:06.850  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:06.850  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
09-07 11:37:06.873  6616  6616 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-07 11:37:06.873  6616  6616 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-07 11:37:06.873  6586  6586 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6586
,09-07 11:37:06.923  6693  6693 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 11:37:06.923  6693  6693 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-07 11:37:06.924  6693  6693 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,09-07 11:37:06.994  6616  6616 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-07 11:37:07.085  6586  6586 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 11:37:07.098  6616  6616 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-07 11:37:07.099  6616  6616 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-07 11:37:07.140  6616  6616 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,09-07 11:37:07.174  6693  6693 I AppConfig: Total System Memory = 906309632
,09-07 11:37:07.181  6693  6693 I GalleryUtils: Application Heap = 96 MB
09-07 11:37:07.186  6693  6693 I AppConfig: App Tier : NOT_DEF
,09-07 11:37:07.202  6693  6693 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,09-07 11:37:07.300   943  1895 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6719 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,09-07 11:37:07.301   943  1895 I ActivityManager: Killing 6345:com.lge.bnr/1000 (adj 15): empty #11
09-07 11:37:07.348   943  1608 W libprocessgroup: failed to open /acct/uid_1000/pid_6345/cgroup.procs: No such file or directory
,09-07 11:37:07.382  6719  6719 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 11:37:07.382  6719  6719 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 11:37:07.382  6719  6719 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,09-07 11:37:07.383  6719  6719 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-07 11:37:07.384  6719  6719 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-07 11:37:07.611   943  1974 I ActivityManager: Process com.android.vending (pid 5713) has died
,09-07 11:37:07.659  6719  6719 I SystemConfig: BUILD Country: EU
09-07 11:37:07.660  6719  6719 I SystemConfig: BUILD Operator: OPEN
,09-07 11:37:07.738  6586  6692 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635606784
,09-07 11:37:07.768  6586  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 11:37:07.768  6586  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 11:37:07.768  6586  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 11:37:07.768  6586  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 11:37:07.768  6586  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-07 11:37:07.769  6586  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@163190e added. We now have 1 listener(s)
09-07 11:37:07.791   943  1864 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6749 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,09-07 11:37:07.809   943  1949 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 11:37:07.815  6719  6746 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-07 11:37:07.815  6719  6746 I SystemConfig: existFile = false
09-07 11:37:07.815  6719  6746 I SystemConfig: canReadFile = false
09-07 11:37:07.815  6719  6746 I SystemConfig: systemFeature RCS result false
09-07 11:37:07.815  6719  6746 D SystemConfig: refreshRcsSupport() :false
09-07 11:37:07.820  6586  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
09-07 11:37:07.821  6586  6692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-07 11:37:07.822  6586  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 11:37:07.823  6586  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 11:37:07.831  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 11:37:07.831  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 11:37:07.831  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 11:37:07.831  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
09-07 11:37:07.831  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 11:37:07.831  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 11:37:07.831  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 11:37:07.831  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 11:37:07.831  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 11:37:07.831  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 11:37:07.831  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 11:37:07.831  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 11:37:07.831  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 11:37:07.831  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-07 11:37:07.831  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@245126c5 added. We now have 1 listener(s)
09-07 11:37:07.832  6586  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 11:37:07.854  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 11:37:07.855  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:07.855  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-07 11:37:07.860  6586  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 11:37:07.860  6586  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-07 11:37:07.861  6586  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-07 11:37:07.861  6586  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 11:37:07.861  6586  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-07 11:37:07.868  6586  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:07.868   943  2287 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 11:37:07.869  6586  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
09-07 11:37:07.884  2079  2096 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
,09-07 11:37:07.890  6586  6692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-07 11:37:07.891  6586  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:07.891  6586  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:07.891  6586  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 11:37:07.891  6586  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:07.891  6586  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:07.891  6586  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:07.891  6586  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:07.891  6586  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 11:37:07.891  6586  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 11:37:07.891  6586  6692 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 11:37:07.893  6586  6692 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 11:37:07.919  6749  6749 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-07 11:37:07.931  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:07.934  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:07.950  6586  6586 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 11:37:07.964  6749  6749 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-07 11:37:07.964  6749  6749 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-07 11:37:07.964  6749  6749 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-07 11:37:07.964  6749  6749 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-07 11:37:07.964  6749  6749 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-07 11:37:07.966   943  2541 I ActivityManager: Killing 6384:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,09-07 11:37:07.979  6363  6363 W System.err: android.os.DeadObjectException
,09-07 11:37:07.983  6363  6363 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-07 11:37:07.983  6363  6363 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-07 11:37:07.983  6363  6363 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-07 11:37:07.983  6363  6363 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
09-07 11:37:07.983  6363  6363 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
09-07 11:37:07.983  6363  6363 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
09-07 11:37:07.983  6363  6363 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 11:37:07.983  6363  6363 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 11:37:07.983  6363  6363 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 11:37:07.983  6363  6363 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
09-07 11:37:07.983  6363  6363 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 11:37:07.983  6363  6363 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 11:37:07.983  6363  6363 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
09-07 11:37:07.983  6363  6363 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
09-07 11:37:07.984  6363  6363 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-07 11:37:07.984  6363  6363 W System.err: android.os.DeadObjectException
09-07 11:37:07.984  6363  6363 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-07 11:37:07.984  6363  6363 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-07 11:37:07.984  6363  6363 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-07 11:37:07.984  6363  6363 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
09-07 11:37:07.984  6363  6363 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
09-07 11:37:07.984  6363  6363 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
09-07 11:37:07.984  6363  6363 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 11:37:07.984  6363  6363 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 11:37:07.984  6363  6363 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 11:37:07.984  6363  6363 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
09-07 11:37:07.984  6363  6363 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 11:37:07.984  6363  6363 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 11:37:07.984  6363  6363 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
09-07 11:37:07.984  6363  6363 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
09-07 11:37:07.984  6363  6363 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-07 11:37:08.068  6586  6600 I art     : CheckpointMarkThreadRoots callback created = 0x992a0330
,09-07 11:37:08.082   943  1950 W libprocessgroup: failed to open /acct/uid_10089/pid_6384/cgroup.procs: No such file or directory
09-07 11:37:08.083   943  1950 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,09-07 11:37:08.096  3472  6769 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,09-07 11:37:08.119  6586  6600 I art     : CheckpointMarkThreadRoots callback created = 0x992a0300
,09-07 11:37:08.138   943  2287 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6770 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 11:37:08.190   943  1949 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6786 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 11:37:08.215  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 11:37:08.218  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:37:08.220  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:37:08.220  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:37:08.220  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:37:08.233   479   479 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:37:08.241  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
09-07 11:37:08.241  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:37:08.242  3472  6769 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-07 11:37:08.242  3472  6769 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-07 11:37:08.245  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
09-07 11:37:08.247  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:37:08.247  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:37:08.247  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:37:08.247  1877  2048 D LEDHandler: Battery Temp: 289, mChargingStatus=5, mChargingStop=false
,09-07 11:37:08.249  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:37:08.252  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 11:37:08.264  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 11:37:08.266   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:37:08.268   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:37:08.268   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:37:08.274  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:37:08.274  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:37:08.274  1877  2048 D LEDHandler: Battery Temp: 290, mChargingStatus=5, mChargingStop=false
09-07 11:37:08.275   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:37:08.275   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:37:08.275   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:37:08.276  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 11:37:08.276  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
09-07 11:37:08.277  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:37:08.277  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
09-07 11:37:08.277  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:37:08.277  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,09-07 11:37:08.285  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:37:08.301  3472  3753 I Icing   : updateResources: need to parse ozd{com.google.android.gms}
,09-07 11:37:08.339  6770  6770 D UEI.SmartControl: Quickset Services start...
,09-07 11:37:08.360  6770  6770 I UEI.SmartControl: Manufacture = LGE
09-07 11:37:08.363  6770  6770 D UEI.SmartControl: File observer start...
,09-07 11:37:08.363  6770  6770 E UEI.SmartControl: IR Port is disabled: false
09-07 11:37:08.363  6770  6770 D UEI.SmartControl: Starting file observer...
09-07 11:37:08.363  6770  6770 D UEI.SmartControl: Extracting JNI libs...
09-07 11:37:08.364  6770  6770 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-07 11:37:08.373   943  2021 I art     : Explicit concurrent mark sweep GC freed 63775(3MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/35MB, paused 3.375ms total 221.618ms
09-07 11:37:08.422  3472  6808 W IcingInternalCorpora: getNumBytesRead when not calculated.
,09-07 11:37:08.429  6770  6770 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-07 11:37:08.430  6770  6770 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-07 11:37:08.431  6770  6770 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-07 11:37:08.473  6770  6770 I UEI.SmartControl: --- Selecting new region: 2
09-07 11:37:08.473  6770  6770 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
,09-07 11:37:08.476  6770  6770 D UEI.SmartControl: Platform has CIR...
09-07 11:37:08.481  6770  6770 D UEI.SmartControl: NO CIR support, need to check package...
09-07 11:37:08.482  6770  6770 I UEI.SmartControl: Model: LG-D722 uses JNI
09-07 11:37:08.484  6770  6770 D UEI.SmartControl: QS Service created
09-07 11:37:08.515  6770  6770 E UEI.SmartControl: QS start get config
,09-07 11:37:08.600  6770  6770 D UEI.SmartControl: Loading JNI Libs...
,09-07 11:37:08.603  6770  6770 D UEI.SmartControl:  configuring local db...
,09-07 11:37:08.824  6770  6770 D UEI.SmartControl:  ---- Has DB8: true
,09-07 11:37:08.833  6770  6770 D UEI.SmartControl: QS start statue = true Error code = 0
,09-07 11:37:08.834  6770  6770 D UEI.SmartControl: QS version = v2.7.11.1_RC1
09-07 11:37:08.835  6770  6770 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
09-07 11:37:08.838  6770  6770 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
09-07 11:37:08.851  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,09-07 11:37:08.852  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:08.852  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-07 11:37:08.857  6770  6770 W irrc_jni: IRRCPlayer_nativeInit ++ 
09-07 11:37:08.857  6770  6770 D irrcClient: IrrcClient ++ 
09-07 11:37:08.857  6770  6770 D irrcClient: getIrrcService ++ 
09-07 11:37:08.857  6770  6770 D irrcClient: getIrrcService -- 
09-07 11:37:08.857  6770  6770 D irrcClient: IrrcClient -- 
09-07 11:37:08.857  6770  6770 W irrc_jni: IRRCPlayer_nativeInit -- 
,09-07 11:37:08.874  6770  6770 D UEI.SmartControl: Services init done
09-07 11:37:08.878  6770  6828 I UEI.SmartControl: Device manager: loading config....
,09-07 11:37:08.880  6770  6770 D UEI.SmartControl: QS Service init finished
09-07 11:37:08.882  6770  6770 D UEI.SmartControl: QS Service version name: 0.1.73
09-07 11:37:08.884  6770  6770 D UEI.SmartControl: QS Service version code: 1073
09-07 11:37:08.885  6770  6770 D UEI.SmartControl: Service requested: Control
09-07 11:37:08.886  6770  6828 D UEI.SmartControl: Config is loaded...
09-07 11:37:08.933  6770  6827 D UEI.SmartControl:  ----- QS SDK is ready!!!
,09-07 11:37:08.934  6770  6770 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-07 11:37:08.936  6786  6786 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(225): No need to run daily hygiene.
09-07 11:37:08.936  6770  6827 I UEI.SmartControl: Notify AllClients services are ready: 0
09-07 11:37:08.941  6770  6792 D UEI.SmartControl: -----IControl: 11
09-07 11:37:08.942  6586  6767 W jxcore-log: Initializing JXcore engine
09-07 11:37:08.942  6770  6792 D UEI.SmartControl: Caller: com.lge.qremote
09-07 11:37:08.943  6586  6767 W jxcore-log: JXcore engine is ready
09-07 11:37:08.944  6770  6770 D UEI.SmartControl: Internal service binding...
09-07 11:37:08.944  6770  6792 D UEI.SmartControl: ------------ IControl registerCallback...
09-07 11:37:08.945  6770  6792 I UEI.SmartControl: Registering callback...
09-07 11:37:08.946  6770  6785 D UEI.SmartControl: -----IControl: 19
,09-07 11:37:08.947  6770  6785 D UEI.SmartControl: Caller: com.lge.qremote
09-07 11:37:08.948  6770  6785 I UEI.SmartControl: Registering Services Ready callback...
09-07 11:37:08.949  6770  6785 I UEI.SmartControl: Notify client services are ready...
09-07 11:37:08.951  6770  6792 D UEI.SmartControl: -----IControl: 8
09-07 11:37:08.952  6770  6792 D UEI.SmartControl: Caller: com.lge.qremote
09-07 11:37:08.969  6786  6786 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-07 11:37:08.970  6786  6786 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-07 11:37:08.977  6786  6786 I NotificationManager: com.android.vending: cancel(-1050172287) by com.android.vending
09-07 11:37:09.007  6786  6786 I Finsky  : [1] com.google.android.finsky.utils.bp.a(177): Enabling bucket experiment: factor=2.000, zeroDelta=0ms, forceNetwork=false
,09-07 11:37:09.041  2702  2826 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is notificationclass=?; selectionArgs[0] is com.google.android.finsky.download.DownloadBroadcastReceiver; sort is null.
09-07 11:37:09.042  2702  2826 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@cd3be6 on behalf of 6786
,09-07 11:37:09.061  6786  6786 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1265): Installer kick - no action, not running yet
09-07 11:37:09.081  6767  6767 W Thread-799: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5633]" dev="sockfs" ino=5633 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-07 11:37:09.081  6767  6767 W Thread-799: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-07 11:37:09.081  6767  6767 W Thread-799: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7883]" dev="sockfs" ino=7883 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-07 11:37:09.081  6767  6767 W Thread-799: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
09-07 11:37:09.081  6767  6767 W Thread-799: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
09-07 11:37:09.081  6767  6767 W Thread-799: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[29919]" dev="sockfs" ino=29919 scontext=u:r:untrusted_app:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-07 11:37:09.117  6586  6767 W jxcore-log: Starting JXcore engine
,09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: com.google.android.gms signature not valid.  Found: 
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: MIIEQzCCAyugAwIBAgIJAMLgh0ZkSjCNMA0GCSqGSIb3DQEBBAUAMHQxCzAJBgNVBAYTAlVTMRMw
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: EQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29n
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: bGUgSW5jLjEQMA4GA1UECxMHQW5kcm9pZDEQMA4GA1UEAxMHQW5kcm9pZDAeFw0wODA4MjEyMzEz
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: MzRaFw0zNjAxMDcyMzEzMzRaMHQxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYw
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: FAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29nbGUgSW5jLjEQMA4GA1UECxMHQW5k
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: cm9pZDEQMA4GA1UEAxMHQW5kcm9pZDCCASAwDQYJKoZIhvcNAQEBBQADggENADCCAQgCggEBAKtW
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: LgDYO6IIrgqWbxJOKdoR8qtW0I9Y4sypEwPpt1TTcvZApxsdyxMJZ2JORland2qSGT2y5b+3JKke
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: dxiLDmpHpDsz2WCbdxgxRczfey5YZnTJ4VZbH0xqWVW/8lGmPav5xVwnIiJS6HXk+BVKZF+JcWjA
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: sb/GEuq/eFdpuzSqeYTcfi6idkyugwfYwXFU1+5fZKUaRKYCwkkFQVfcAs1fXA5V+++FGfvjJ/Cx
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: URaSxaBvGdGDhfXE28LWuT9ozCl5xw4Yq5OGazvV24mZVSoOO0yZ31j7kYvtwYK6NeADwbSxDdJE
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: qO4k//0zOHKrUiGYXtqw/A0LFFtqoZKFjnkCAQOjgdkwgdYwHQYDVR0OBBYEFMd9jMIhF1Ylmn/T
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: gt9r45jk14alMIGmBgNVHSMEgZ4wgZuAFMd9jMIhF1Ylmn/Tgt9r45jk14aloXikdjB0MQswCQYD
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: VQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNTW91bnRhaW4gVmlldzEUMBIG
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: A1UEChMLR29vZ2xlIEluYy4xEDAOBgNVBAsTB0FuZHJvaWQxEDAOBgNVBAMTB0FuZHJvaWSCCQDC
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: 4IdGZEowjTAMBgNVHRMEBTADAQH/MA0GCSqGSIb3DQEBBAUAA4IBAQBt0lLO74UwLDYKqs6Tm8/y
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: zKkEu116FmH4rkaymUIE0P9KaMftGlMexFlaYjzmB2OxZyl6euNXEsQH8gjwyxCUKRJNexBiGcCE
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: yj6z+a1fuHHvkiaai+KL8W1EyNmgjmyy8AW7P+LLlkR+ho5zEHatRbM/YAnqGcFh5iZBqpknHf1S
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: KMXFh4dd239FJ1jWYfbMDMy3NS5CTMQ2XFI1MvcyUTdZPErjQfTbQe3aDQsQcafEQPD+nqActifK
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: Z0Np0IS9L9kR/wbNvyz6ENwPiTrjV2KRkEjH78ZMcUQXg0L3BYHJ3lc69Vs5Ddf9uUGGMYldX3Wf
09-07 11:37:09.128  6786  6837 V GoogleSignatureVerifier: MBEmh/9iFBDAaTCK
09-07 11:37:09.149  6786  6786 I Finsky  : [1] com.google.android.finsky.l.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
09-07 11:37:09.150  6786  6786 I Finsky  : [1] com.google.android.finsky.l.j.run(214): Finished loading 1 libraries.
,09-07 11:37:09.160  1764  1764 D WearableService: callingUid 10006, callindPid: 1764
09-07 11:37:09.166  6786  6786 I Finsky  : [1] com.google.android.finsky.c.l.a(253): result=false type=4
,09-07 11:37:09.198  6786  6786 I Finsky  : [1] com.google.android.finsky.services.bd.a(1075): Restore complete with 0 success and 0 failed.
,09-07 11:37:09.233   943   975 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6842 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-07 11:37:09.240  6786  6786 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
09-07 11:37:09.240  6786  6786 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
09-07 11:37:09.282   943  2015 I ActivityManager: Killing 6363:com.lge.qremote/u0a106 (adj 15): empty #11
,09-07 11:37:09.293  6586  6767 W jxcore-log: Platform android
09-07 11:37:09.293  6586  6767 W jxcore-log: 
,09-07 11:37:09.293  6586  6767 W jxcore-log: Process ARCH arm
09-07 11:37:09.293  6586  6767 W jxcore-log: 
,09-07 11:37:09.435   943  4928 W libprocessgroup: failed to open /acct/uid_10106/pid_6363/cgroup.procs: No such file or directory
09-07 11:37:09.451  6842  6842 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 11:37:09.467   292   359 I ThermalEngine: Sensor:pa_therm0:31000 mC
,09-07 11:37:09.573  6586  6767 I jxcore-log: JXcore Cordova bridge is ready!
09-07 11:37:09.573  6586  6767 I jxcore-log: 
09-07 11:37:09.573  6586  6767 W jxcore-log: JXcore engine is started
,09-07 11:37:09.582  6586  6692 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-07 11:37:09.588  6586  6586 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 11:37:09.603  3472  3753 I Icing   : Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,09-07 11:37:09.656  3472  3753 I Icing   : Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,09-07 11:37:09.761   943  1864 I ActivityManager: Process com.google.android.gms.unstable (pid 6445) has died
,09-07 11:37:09.769  2028  6870 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-07 11:37:09.821  2028  6870 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 52 ms] updated apps [took 51 ms] 
,09-07 11:37:09.822   943  4928 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6871 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-07 11:37:09.856  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 11:37:09.856  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:09.856  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-07 11:37:09.895  6871  6871 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-07 11:37:09.948   943  1052 D BluetoothManagerService: Message: 20
,09-07 11:37:09.948   943  1052 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33f5c68f:true
09-07 11:37:09.953  2079  2096 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
09-07 11:37:09.954  2079  2096 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
09-07 11:37:10.009  6871  6871 V LGMDMManager: Create singleton instance
,09-07 11:37:10.073  6871  6871 I AudioManager: getMode name:com.lge.qremote
,09-07 11:37:10.084  6770  6792 D UEI.SmartControl: -----IControl: 11
09-07 11:37:10.085  6770  6792 D UEI.SmartControl: Caller: com.lge.qremote
,09-07 11:37:10.085  6770  6792 D UEI.SmartControl: ------------ IControl registerCallback...
09-07 11:37:10.085  6770  6792 I UEI.SmartControl: Registering callback...
09-07 11:37:10.086  6770  6859 D UEI.SmartControl: -----IControl: 19
,09-07 11:37:10.088  6770  6859 D UEI.SmartControl: Caller: com.lge.qremote
09-07 11:37:10.088  6770  6859 I UEI.SmartControl: Registering Services Ready callback...
09-07 11:37:10.089  6770  6859 I UEI.SmartControl: Notify client services are ready...
09-07 11:37:10.091  6871  6871 I AudioManager: getMode name:com.lge.qremote
09-07 11:37:10.101  6770  6785 D UEI.SmartControl: -----IControl: 8
,09-07 11:37:10.103  6770  6785 D UEI.SmartControl: Caller: com.lge.qremote
09-07 11:37:10.109  6871  6871 I AudioManager: getMode name:com.lge.qremote
09-07 11:37:10.114   943  1864 I ActivityManager: Killing 2889:com.lge.music/u0a28 (adj 15): empty #11
,09-07 11:37:10.125   282  1322 V AudioFlinger: 2889 died, releasing its sessions
09-07 11:37:10.125   282  1322 V AudioFlinger:  pid 1793 @ 0
09-07 11:37:10.125   282  1322 V AudioFlinger:  pid 3162 @ 1
09-07 11:37:10.125   282  1322 V AudioFlinger:  pid 3162 @ 2
,09-07 11:37:10.201   943  1728 W libprocessgroup: failed to open /acct/uid_10028/pid_2889/cgroup.procs: No such file or directory
,09-07 11:37:10.206  6871  6871 I AudioManager: getMode name:com.lge.qremote
09-07 11:37:10.219  6871  6871 I AudioManager: getMode name:com.lge.qremote
,09-07 11:37:10.502   943  1287 V AlarmManager: RTC_WAKEUP set : Alarm{2235f887 type 0 when 1473241030498 com.google.android.googlequicksearchbox} when 1473241030498
,09-07 11:37:11.858  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 11:37:11.858  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:11.858  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-07 11:37:12.183   943  2541 I ActivityManager: Killing 6534:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,09-07 11:37:12.312   943  1949 W libprocessgroup: failed to open /acct/uid_10038/pid_6534/cgroup.procs: No such file or directory
,09-07 11:37:12.861  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 11:37:12.861  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:12.861  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-07 11:37:13.034  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:37:13.035  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:37:13.035  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:37:13.035  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 11:37:13.038  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 11:37:13.071  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
09-07 11:37:13.071  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:37:13.071  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
09-07 11:37:13.073  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:37:13.073  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,09-07 11:37:13.073   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:37:13.073   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:37:13.074   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:37:13.076  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:37:13.076  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:37:13.076  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:37:13.076  1877  2048 D LEDHandler: Battery Temp: 286, mChargingStatus=5, mChargingStop=false
09-07 11:37:13.076  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 11:37:13.090   479   479 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:37:13.911  6770  6829 D UEI.SmartControl: Internal timer expired: 1
,09-07 11:37:14.472   292   359 I ThermalEngine: Sensor:pa_therm0:31000 mC
,09-07 11:37:14.864  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 11:37:14.864  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:14.864  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-07 11:37:15.865  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 11:37:15.865  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:15.865  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-07 11:37:17.869  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 11:37:17.869  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:17.869  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-07 11:37:18.484   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:37:18.484   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:37:18.484   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 132543256620; DSPS: 4441723; Offset : -3012676755
,09-07 11:37:18.871  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 11:37:18.871  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:18.871  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-07 11:37:19.476   292   359 I ThermalEngine: Sensor:pa_therm0:31000 mC
,09-07 11:37:19.874  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 11:37:19.874  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:19.874  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-07 11:37:21.124   943  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{376f9623 type 2 when 135177 com.google.android.gms} when 135177
,09-07 11:37:21.158  1764  1764 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-07 11:37:21.373  1764  1764 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-07 11:37:21.381  3472  6930 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
09-07 11:37:21.381  3472  6930 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-07 11:37:21.850   943  1894 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6941 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
09-07 11:37:21.871   306   306 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 296us total 22.994ms
,09-07 11:37:21.896   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 278us total 23.449ms
,09-07 11:37:21.919   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 341us total 21.597ms
,09-07 11:37:21.963  6941  6941 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-07 11:37:21.964  6941  6941 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-07 11:37:22.019  6941  6941 I MultiDex: VM with version 2.1.0 has multidex support
09-07 11:37:22.019  6941  6941 I MultiDex: install
09-07 11:37:22.019  6941  6941 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-07 11:37:22.067  6941  6941 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-07 11:37:22.138  6941  6941 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-07 11:37:22.139  6941  6941 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1986c527: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-07 11:37:22.140  6941  6941 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-07 11:37:22.141  6941  6941 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
09-07 11:37:22.142  6941  6941 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
09-07 11:37:22.153  6941  6941 D ChimeraCfgMgr: Reading stored module config
,09-07 11:37:22.265  6941  6955 I art     : Background sticky concurrent mark sweep GC freed 20298(1023KB) AllocSpace objects, 3(133KB) LOS objects, 7% free, 10MB/11MB, paused 5.326ms total 79.877ms
,09-07 11:37:22.278  1764  1764 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=610efe9e-5b56-4ddf-beb3-d3db290780fa
09-07 11:37:22.324  6941  6941 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
09-07 11:37:22.324  6941  6941 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-07 11:37:22.332  6941  6965 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-07 11:37:22.341   943  1608 I ActivityManager: Process com.google.android.talk (pid 6616) has died
09-07 11:37:22.347  1764  1764 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-07 11:37:22.352  1764  1764 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-07 11:37:22.386  6941  6955 I art     : CheckpointMarkThreadRoots callback created = 0xb042d370
,09-07 11:37:22.427  6941  6955 I art     : CheckpointMarkThreadRoots callback created = 0xb042d360
09-07 11:37:22.428   282  1300 D WVCdm   : Instantiating CDM.
,09-07 11:37:22.435   282  1607 I WVCdm   : CdmEngine::OpenSession
,09-07 11:37:22.435   282  1607 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
09-07 11:37:22.454  6941  6955 I art     : Background partial concurrent mark sweep GC freed 1425(242KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/17MB, paused 11.321ms total 68.129ms
,09-07 11:37:22.476   282  1607 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-07 11:37:22.477   282  1607 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
09-07 11:37:22.477   282  1607 W WVCdm   : L1 library not specified. Falling Back to L3
,09-07 11:37:22.559   282  1607 I WVCdm   : CdmEngine::QueryKeyControlInfo
09-07 11:37:22.561   282  1322 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-07 11:37:22.561   282  1322 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-07 11:37:22.561   282  1322 I WVCdm   : CdmEngine::GenerateKeyRequest
09-07 11:37:22.566   282  1322 D WVCdm   : PrepareKeyRequest: nonce=1433729964
09-07 11:37:22.570  6941  6956 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-07 11:37:22.570  6941  6956 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-07 11:37:22.572  6941  6956 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,09-07 11:37:22.572  6941  6956 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-07 11:37:22.572   276  1043 E BandwidthController: [LG DATA] No such appUid: 10006
09-07 11:37:22.572   276  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-07 11:37:22.573   276  6973 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
09-07 11:37:22.573   276  6973 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-07 11:37:22.575   276  6973 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
09-07 11:37:22.575   276  6973 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-07 11:37:22.575   276  6973 D libc-netbsd: res_queryN name = xxxxx succeed
09-07 11:37:22.576  6941  6956 I System.out: propertyValue:false
09-07 11:37:22.650  6941  6956 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-07 11:37:22.650  6941  6956 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-07 11:37:22.671  1764  2373 I art     : Explicit concurrent mark sweep GC freed 51685(3MB) AllocSpace objects, 24(384KB) LOS objects, 40% free, 14MB/24MB, paused 3.088ms total 109.556ms
,09-07 11:37:22.724  1764  2422 W GCoreFlp: No location to return for getLastLocation()
,09-07 11:37:22.879  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 11:37:22.879  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:22.879  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,09-07 11:37:22.892   943  1919 I art     : Explicit concurrent mark sweep GC freed 31110(1679KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.628ms total 164.525ms
,09-07 11:37:22.949  1764  2386 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-07 11:37:22.959  3472  6936 D UdcContextInitService: registered all accounts: true
09-07 11:37:22.969  1764  2373 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-07 11:37:23.258  1764  2373 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-07 11:37:23.258  1764  2373 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-07 11:37:23.258  1764  2373 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-07 11:37:23.258  1764  2373 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-07 11:37:23.258   276  1043 E BandwidthController: [LG DATA] No such appUid: 10006
09-07 11:37:23.258   276  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,09-07 11:37:23.259   276  6976 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
,09-07 11:37:23.259   276  6976 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-07 11:37:23.259   276  6976 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
09-07 11:37:23.259   276  6976 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-07 11:37:23.259   276  6976 D libc-netbsd: res_queryN name = xxxxx succeed
09-07 11:37:23.262  1764  2373 I System.out: propertyValue:false
,09-07 11:37:23.323  1764  2373 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-07 11:37:23.323  1764  2373 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-07 11:37:23.373  6977  6977 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=41 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-07 11:37:23.463  6977  6977 I dex2oat : dex2oat took 89.884ms (threads: 4)
,09-07 11:37:23.492   943   975 I NotificationManager: android: cancelAsUser(2) by android
,09-07 11:37:23.508  1764  2373 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,09-07 11:37:23.511  6941  6956 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 11:37:23.511  6941  6956 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 11:37:23.511  6941  6956 I Adreno-EGL: Build Date: 03/02/15 Mon
09-07 11:37:23.511  6941  6956 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-07 11:37:23.511  6941  6956 I Adreno-EGL: Remote Branch: 
09-07 11:37:23.511  6941  6956 I Adreno-EGL: Local Patches: 
09-07 11:37:23.511  6941  6956 I Adreno-EGL: Reconstruct Branch: 
09-07 11:37:23.611   943  1608 I ActivityManager: Process com.android.gallery3d (pid 6693) has died
,09-07 11:37:23.847  6941  6956 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 11:37:23.847  6941  6956 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 11:37:23.847  6941  6956 I Adreno-EGL: Build Date: 03/02/15 Mon
09-07 11:37:23.847  6941  6956 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-07 11:37:23.847  6941  6956 I Adreno-EGL: Remote Branch: 
09-07 11:37:23.847  6941  6956 I Adreno-EGL: Local Patches: 
09-07 11:37:23.847  6941  6956 I Adreno-EGL: Reconstruct Branch: 
,09-07 11:37:23.904  6941  6956 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 11:37:23.904  6941  6956 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 11:37:23.904  6941  6956 I Adreno-EGL: Build Date: 03/02/15 Mon
09-07 11:37:23.904  6941  6956 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-07 11:37:23.904  6941  6956 I Adreno-EGL: Remote Branch: 
09-07 11:37:23.904  6941  6956 I Adreno-EGL: Local Patches: 
09-07 11:37:23.904  6941  6956 I Adreno-EGL: Reconstruct Branch: 
,09-07 11:37:24.191  1764  6938 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-07 11:37:24.191  1764  6938 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-07 11:37:24.253  1764  6938 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-07 11:37:24.253  1764  6938 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-07 11:37:24.460  1764  2373 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-07 11:37:24.469  1764  2373 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
09-07 11:37:24.474  1764  2373 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-07 11:37:23.091+0200, stopTime=2016-09-07 11:37:24.470+0200, duration=1379ms
,09-07 11:37:24.481   292   359 I ThermalEngine: Sensor:pa_therm0:31000 mC
09-07 11:37:24.521  1764  6990 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-07 11:37:24.521  1764  6990 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-07 11:37:24.521  1764  6990 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-07 11:37:24.521  1764  6990 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-07 11:37:24.522   276  1043 E BandwidthController: [LG DATA] No such appUid: 10006
09-07 11:37:24.522   276  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,09-07 11:37:24.523   276  6996 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
09-07 11:37:24.523   276  6996 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-07 11:37:24.524   276  6996 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
09-07 11:37:24.524   276  6996 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-07 11:37:24.524   276  6996 D libc-netbsd: res_queryN name = xxxxx succeed
09-07 11:37:24.525  1764  6990 I System.out: propertyValue:false
,09-07 11:37:24.604  5731  5747 I art     : Explicit concurrent mark sweep GC freed 2125(77KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 940us total 28.031ms
,09-07 11:37:24.800   282   282 I WVCdm   : CdmEngine::CloseSession
,09-07 11:37:24.804   282   282 I WVCdm   : L3 Terminate.
09-07 11:37:25.040  1764  2373 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-07 11:37:25.191  1764  7005 E CommitToConfigurationOperation: Malformed snapshot token (size): 
09-07 11:37:25.192  1764  7003 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-07 11:37:25.233  1764  7005 E CommitToConfigurationOperation: Malformed snapshot token (size): 
09-07 11:37:25.234  1764  7003 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-07 11:37:25.255  1764  7005 E CommitToConfigurationOperation: Malformed snapshot token (size): 
09-07 11:37:25.256  1764  7003 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-07 11:37:25.257  1764  7003 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-07 11:37:25.274  1764  7003 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-07 11:37:25.311   943  1350 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-07 11:37:25.392  1764  7003 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-07 11:37:25.392  1764  7003 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-07 11:37:25.392  1764  7003 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-07 11:37:25.392  1764  7003 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-07 11:37:25.392   276  1043 E BandwidthController: [LG DATA] No such appUid: 10006
09-07 11:37:25.392   276  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-07 11:37:25.393   276  7006 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
09-07 11:37:25.393   276  7006 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-07 11:37:25.393   276  7006 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
09-07 11:37:25.393   276  7006 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-07 11:37:25.393   276  7006 D libc-netbsd: res_queryN name = xxxxx succeed
09-07 11:37:25.394  1764  7003 I System.out: propertyValue:false
09-07 11:37:25.732   943  4928 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-07 11:37:25.955   943  1949 I NotificationManager: android: cancelAsUser(2) by android
,09-07 11:37:25.973  1764  7003 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,09-07 11:37:26.298   943  1974 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-07 11:37:26.409  6586  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 11:37:26.409  6586  6767 I jxcore-log: 
,09-07 11:37:26.419  6586  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 11:37:26.419  6586  6767 I jxcore-log: 
09-07 11:37:26.424  2079  2096 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
09-07 11:37:26.424  6586  6767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:26.424  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:26.424  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 11:37:26.424  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:26.424  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:26.424  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:26.424  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:26.424  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 11:37:26.434  2079  2095 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
09-07 11:37:26.441  6586  6767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 11:37:26.445  6586  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 11:37:26.445  6586  6767 I jxcore-log: 
09-07 11:37:26.448  6586  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 11:37:26.448  6586  6767 I jxcore-log: 
09-07 11:37:26.736   943   975 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-07 11:37:27.175  1764  2373 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,09-07 11:37:27.286  6586  6767 I jxcore-log: Unit Test app is loaded
09-07 11:37:27.286  6586  6767 I jxcore-log: 
,09-07 11:37:27.312  6586  6767 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:37:27.312  6586  6767 I jxcore-log: 
,09-07 11:37:27.322  6586  6586 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-07 11:37:27.325  6586  6767 D executeNativeTests: Running unit tests
,09-07 11:37:27.337   943  1895 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-07 11:37:27.507  6586  6767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 11:37:27.507  6586  6767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ece599 added. We now have 2 listener(s)
09-07 11:37:27.508   943  1608 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 11:37:27.510  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-07 11:37:27.510  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 11:37:27.510  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 11:37:27.510  6586  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 11:37:27.510  6586  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2128905e added. We now have 2 listener(s)
09-07 11:37:27.510  6586  6767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 11:37:27.511  6586  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 11:37:27.512  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:27.515  2079  2095 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
09-07 11:37:27.515  6586  6767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:27.515  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:27.515  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 11:37:27.515  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:27.515  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:27.515  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:27.515  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:27.515  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 11:37:27.516  2079  2096 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
09-07 11:37:27.517  6586  6767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:27.517  6586  6767 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 11:37:27.518  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:27.520  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:27.520  2079  2095 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
,09-07 11:37:27.528  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 11:37:27.530  6586  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 11:37:27.530  6586  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 11:37:27.536  6586  6767 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-07 11:37:27.536  6586  6767 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 11:37:27.536  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 11:37:27.536  6586  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 11:37:27.536  6586  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 11:37:27.541  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:27.541  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:27.541  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:37:27.542  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 11:37:27.542  6586  6767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ece599 removed from the list
09-07 11:37:27.542  6586  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:27.542  6586  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2128905e removed from the list
09-07 11:37:27.542  6586  6767 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:27.542  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:27.551  6586  6767 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-07 11:37:27.552  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:27.552  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:27.552  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:27.552  6586  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ece599 not in the list
09-07 11:37:27.552  6586  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:27.552  6586  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2128905e not in the list
09-07 11:37:27.552  6586  6767 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:27.552  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:27.552  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:27.558  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 11:37:27.558  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 11:37:27.558  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 11:37:27.558  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 11:37:27.558  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 11:37:27.558  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.Con,nectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 11:37:27.559  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:27.559  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 11:37:27.559  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:27.559  6586  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ece599 not in the list
09-07 11:37:27.559  6586  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:27.559  6586  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2128905e not in the list
09-07 11:37:27.559  6586  6767 D io.jxcore.node.ConnectivityMonitor: stop,
09-07 11:37:27.559  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:27.559  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:27.560  6586  6767 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 11:37:27.562  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:27.564  2079  2095 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
09-07 11:37:27.565  6586  6767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:27.565  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:27.565  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 11:37:27.565  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:27.565  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:27.565  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:27.565  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,09-07 11:37:27.565  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 11:37:27.566  2079  2096 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
,09-07 11:37:27.566  6586  6767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:27.567  6586  6767 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 11:37:27.568  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:27.569  6586  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 11:37:27.569  6586  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 11:37:27.569  6586  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 11:37:27.569  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:27.569  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 11:37:27.573  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:27.578  6586  6767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 11:37:27.578   943  4928 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 11:37:27.589  2079  2096 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
09-07 11:37:27.590  2079  2095 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
,09-07 11:37:27.593  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 11:37:27.601  2079  2095 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
,09-07 11:37:27.605  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 11:37:27.606  2079  2095 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
09-07 11:37:27.608  6586  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-07 11:37:27.609  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 11:37:27.610  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:37:27.611  6586  6767 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-07 11:37:27.612  6586  6767 I io.jxcore.node.ConnectionHelper: start: OK
09-07 11:37:27.783   943  1950 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-07 11:37:27.978   943  4928 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-07 11:37:28.171   943  1728 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-07 11:37:29.485   292   359 I ThermalEngine: Sensor:pa_therm0:32000 mC
,09-07 11:37:29.892  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 11:37:29.892  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:29.892  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-07 11:37:30.614  6586  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-07 11:37:30.614  6586  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-07 11:37:30.614  6586  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 11:37:31.894  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 11:37:31.894  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:31.894  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-07 11:37:31.913   943  1055 I PowerManagerService: ALS enabled for SRE
,09-07 11:37:31.920   943  1055 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (25979 ms ago)
09-07 11:37:31.986   943  1351 D qdlights: set_light_backlight: 253
,09-07 11:37:31.995   943  1351 D qdlights: set_light_backlight: 249
09-07 11:37:32.013   943  1351 D qdlights: set_light_backlight: 246
,09-07 11:37:32.029   943  1351 D qdlights: set_light_backlight: 243
,09-07 11:37:32.045   943  1351 D qdlights: set_light_backlight: 239
,09-07 11:37:32.062   943  1351 D qdlights: set_light_backlight: 236
,09-07 11:37:32.078   943  1351 D qdlights: set_light_backlight: 233
,09-07 11:37:32.095   943  1351 D qdlights: set_light_backlight: 229
,09-07 11:37:32.112   943  1351 D qdlights: set_light_backlight: 226
,09-07 11:37:32.128   943  1351 D qdlights: set_light_backlight: 223
,09-07 11:37:32.145   943  1351 D qdlights: set_light_backlight: 219
,09-07 11:37:32.162   943  1351 D qdlights: set_light_backlight: 216
,09-07 11:37:32.178   943  1351 D qdlights: set_light_backlight: 213
,09-07 11:37:32.195   943  1351 D qdlights: set_light_backlight: 209
,09-07 11:37:32.212   943  1351 D qdlights: set_light_backlight: 206
,09-07 11:37:32.228   943  1351 D qdlights: set_light_backlight: 203
,09-07 11:37:32.245   943  1351 D qdlights: set_light_backlight: 199
,09-07 11:37:32.262   943  1351 D qdlights: set_light_backlight: 196
,09-07 11:37:32.278   943  1351 D qdlights: set_light_backlight: 193
,09-07 11:37:32.295   943  1351 D qdlights: set_light_backlight: 189
,09-07 11:37:32.312   943  1351 D qdlights: set_light_backlight: 186
09-07 11:37:32.328   943  1351 D qdlights: set_light_backlight: 183
,09-07 11:37:32.345   943  1351 D qdlights: set_light_backlight: 179
,09-07 11:37:32.362   943  1351 D qdlights: set_light_backlight: 176
,09-07 11:37:32.378   943  1351 D qdlights: set_light_backlight: 173
,09-07 11:37:32.395   943  1351 D qdlights: set_light_backlight: 169
,09-07 11:37:32.412   943  1351 D qdlights: set_light_backlight: 166
,09-07 11:37:32.428   943  1351 D qdlights: set_light_backlight: 163
,09-07 11:37:32.445   943  1351 D qdlights: set_light_backlight: 159
,09-07 11:37:32.462   943  1351 D qdlights: set_light_backlight: 156
,09-07 11:37:32.478   943  1351 D qdlights: set_light_backlight: 153
,09-07 11:37:32.495   943  1351 D qdlights: set_light_backlight: 149
,09-07 11:37:32.512   943  1351 D qdlights: set_light_backlight: 146
,09-07 11:37:32.528   943  1351 D qdlights: set_light_backlight: 143
,09-07 11:37:32.545   943  1351 D qdlights: set_light_backlight: 139
,09-07 11:37:32.562   943  1351 D qdlights: set_light_backlight: 136
,09-07 11:37:32.578   943  1351 D qdlights: set_light_backlight: 133
,09-07 11:37:32.595   943  1351 D qdlights: set_light_backlight: 129
,09-07 11:37:32.612   943  1351 D qdlights: set_light_backlight: 126
,09-07 11:37:32.628   943  1351 D qdlights: set_light_backlight: 123
,09-07 11:37:32.645   943  1351 D qdlights: set_light_backlight: 119
,09-07 11:37:32.662   943  1351 D qdlights: set_light_backlight: 116
,09-07 11:37:32.678   943  1351 D qdlights: set_light_backlight: 113
,09-07 11:37:32.695   943  1351 D qdlights: set_light_backlight: 109
,09-07 11:37:32.712   943  1351 D qdlights: set_light_backlight: 106
,09-07 11:37:32.728   943  1351 D qdlights: set_light_backlight: 103
,09-07 11:37:32.745   943  1351 D qdlights: set_light_backlight: 99
,09-07 11:37:32.762   943  1351 D qdlights: set_light_backlight: 96
,09-07 11:37:32.778   943  1351 D qdlights: set_light_backlight: 93
,09-07 11:37:32.795   943  1351 D qdlights: set_light_backlight: 89
,09-07 11:37:32.812   943  1351 D qdlights: set_light_backlight: 86
,09-07 11:37:32.828   943  1351 D qdlights: set_light_backlight: 83
,09-07 11:37:32.845   943  1351 D qdlights: set_light_backlight: 79
,09-07 11:37:32.862   943  1351 D qdlights: set_light_backlight: 76
,09-07 11:37:32.878   943  1351 D qdlights: set_light_backlight: 73
,09-07 11:37:32.896   943  1351 D qdlights: set_light_backlight: 69
,09-07 11:37:32.906  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 11:37:32.906  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:32.906  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-07 11:37:32.917   943  1351 D qdlights: set_light_backlight: 66
,09-07 11:37:32.931   943  1351 D qdlights: set_light_backlight: 63
,09-07 11:37:32.945   943  1351 D qdlights: set_light_backlight: 59
,09-07 11:37:32.962   943  1351 D qdlights: set_light_backlight: 56
,09-07 11:37:32.978   943  1351 D qdlights: set_light_backlight: 53
,09-07 11:37:32.995   943  1351 D qdlights: set_light_backlight: 49
,09-07 11:37:33.012   943  1351 D qdlights: set_light_backlight: 46
,09-07 11:37:33.028   943  1351 D qdlights: set_light_backlight: 43
,09-07 11:37:33.046   943  1351 D qdlights: set_light_backlight: 39
,09-07 11:37:33.062   943  1351 D qdlights: set_light_backlight: 36
,09-07 11:37:33.078   943  1351 D qdlights: set_light_backlight: 33
,09-07 11:37:33.095   943  1351 D qdlights: set_light_backlight: 29
,09-07 11:37:33.112   943  1351 D qdlights: set_light_backlight: 26
,09-07 11:37:33.128   943  1351 D qdlights: set_light_backlight: 23
,09-07 11:37:33.145   943  1351 D qdlights: set_light_backlight: 19
,09-07 11:37:33.162   943  1351 D qdlights: set_light_backlight: 16
,09-07 11:37:33.178   943  1351 D qdlights: set_light_backlight: 13
,09-07 11:37:33.200   943  1351 D qdlights: set_light_backlight: 10
,09-07 11:37:33.619  6586  6767 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 11:37:33.619  6586  6767 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-07 11:37:33.619  6586  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 11:37:33.619  6586  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 11:37:33.619  6586  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 11:37:33.619  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:33.619  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 11:37:33.627  2079  2095 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
09-07 11:37:33.628  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 11:37:33.628  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:37:33.630  6586  6767 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 11:37:33.630  6586  6767 I io.jxcore.node.ConnectionHelper: start: OK
09-07 11:37:33.908  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 11:37:33.908  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:33.908  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-07 11:37:34.490   292   359 I ThermalEngine: Sensor:pa_therm0:31000 mC
,09-07 11:37:36.631  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:36.631  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:36.631  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:37:36.631  6586  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ece599 not in the list
09-07 11:37:36.631  6586  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:36.631  6586  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2128905e not in the list
09-07 11:37:36.631  6586  6767 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:36.631  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:36.636  6586  6767 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 11:37:36.638  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:36.641  2079  2095 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
09-07 11:37:36.642  6586  6767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:36.642  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:36.642  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 11:37:36.642  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:36.642  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:36.642  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:36.642  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:36.642  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 11:37:36.643  2079  2096 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
09-07 11:37:36.645  6586  6767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:36.645  6586  6767 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 11:37:36.649  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:36.651  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:36.651  6586  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 11:37:36.651  6586  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 11:37:36.651  6586  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 11:37:36.651  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:36.651  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 11:37:36.656  2079  2096 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
,09-07 11:37:36.659  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 11:37:36.660  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:37:36.661  6586  6767 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 11:37:36.662  6586  6767 I io.jxcore.node.ConnectionHelper: start: OK
09-07 11:37:37.916  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 11:37:37.916  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:37.916  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-07 11:37:38.488   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:37:38.488   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:37:38.488   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 152547073029; DSPS: 5097208; Offset : -3012674756
,09-07 11:37:38.917   943  1055 I PowerManagerService: ALS enabled for SRE
09-07 11:37:38.917   943  1055 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (32976 ms ago)
,09-07 11:37:38.924   943  1055 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-07 11:37:38.948   943  1055 I PowerManagerService: ALS enabled for SRE
,09-07 11:37:38.950   943  1055 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33009 ms ago)
09-07 11:37:38.975   943  1055 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,09-07 11:37:38.986   943  1055 I PowerManagerService: Sleeping (uid 1000)...
09-07 11:37:38.986   943  1055 D LPWGController: [updateScreenState] screen on = false
09-07 11:37:38.996   943  1055 D LPWGController: disable proximity sensor
,09-07 11:37:39.001   943  1055 D LPWGController: enable proximity sensor
09-07 11:37:39.037   943  1055 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@1939123c] by com.android.server.power.ProximitySensorListener.enable():120
,09-07 11:37:39.047   943  1055 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
09-07 11:37:39.047   943  1055 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
09-07 11:37:39.047   943  1055 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
09-07 11:37:39.047   943  1055 I sensors_hal_Ctx: activate: handle is 48, enable
09-07 11:37:39.048   943  1055 V sensors_hal_Ctx: activate sensors is 1400000000000
09-07 11:37:39.048   943  1055 D sensors_hal_Thresh: enable: handle=48
09-07 11:37:39.048   943  1055 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
,09-07 11:37:39.049   943  1055 D sensors_hal_Util: waitForResponse: timeout=1000
09-07 11:37:39.056   943   996 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
09-07 11:37:39.056   943   996 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
09-07 11:37:39.056   943  1055 D sensors_hal_Thresh: enable: Received response: 0
09-07 11:37:39.056   943  1055 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33115 ms ago)
09-07 11:37:39.083   943  1055 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 11:37:39.083   943  1055 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 11:37:39.083   943  1055 I Adreno-EGL: Build Date: 03/02/15 Mon
09-07 11:37:39.083   943  1055 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-07 11:37:39.083   943  1055 I Adreno-EGL: Remote Branch: 
09-07 11:37:39.083   943  1055 I Adreno-EGL: Local Patches: 
09-07 11:37:39.083   943  1055 I Adreno-EGL: Reconstruct Branch: 
,09-07 11:37:39.113   245   263 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1744 us)
,09-07 11:37:39.284   426   982 I Sensors : sns_pwr.c(273):acquiring wakelock
,09-07 11:37:39.286   943   996 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
09-07 11:37:39.288   943   996 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
09-07 11:37:39.288   943   996 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
09-07 11:37:39.288   943   996 D sensors_hal_Thresh: processInd: handle 48, count=1
09-07 11:37:39.288   943   996 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
09-07 11:37:39.288   943   996 I sensors_hal_Thresh: processInd : proximity state changed - FAR
09-07 11:37:39.288   943  1033 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
09-07 11:37:39.288   943  1033 D sensors_hal_Ctx: poll: count: 256
09-07 11:37:39.288   943  1033 I sensors_hal_Ctx: poll: released wakelock sensor_ind
09-07 11:37:39.288   943  1033 D sensors_hal_Util: waitForResponse: timeout=0
09-07 11:37:39.289   943  1055 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
09-07 11:37:39.290   943  1055 I LPWGController: current mode = 1  value = 1 1
09-07 11:37:39.292   943  1055 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
09-07 11:37:39.391   943  1055 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,09-07 11:37:39.495   292   359 I ThermalEngine: Sensor:pa_therm0:31000 mC
,09-07 11:37:39.631   943  1351 D qdlights: set_light_backlight: 0
,09-07 11:37:39.652   943  1055 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,09-07 11:37:39.659   943  1055 I sensors_hal_Ctx: activate: handle is 46, disable
09-07 11:37:39.659   943  1055 V sensors_hal_Ctx: activate sensors is 1000000000000
09-07 11:37:39.659   943  1055 D sensors_hal_LP2: enable: handle=46
09-07 11:37:39.659   943  1055 D sensors_hal_LP2: enable: Disabling sensor handle=46
09-07 11:37:39.659   943  1055 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
09-07 11:37:39.661   245   245 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
09-07 11:37:39.661   245   245 D qdhwcomposer: hwc_blank: Blanking display: 0
09-07 11:37:39.662  6586  6767 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-07 11:37:39.662  6586  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-07 11:37:39.662  6586  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 11:37:39.668   943  1053 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
09-07 11:37:39.670   943   943 V ActivityManager: Display changed displayId=0
,09-07 11:37:39.692   943  1022 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
09-07 11:37:39.692   943  1022 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,09-07 11:37:39.741  1793  1793 D DSDPConnection: Display #0 changed.
,09-07 11:37:39.897   245   245 D qdhwcomposer: hwc_blank: Done blanking display: 0
,09-07 11:37:39.899   245   679 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
09-07 11:37:39.899   943  1351 D SurfaceControl: Excessive delay in setPowerMode(): 238ms
09-07 11:37:39.900   943  1351 I QCOM PowerHAL: Got set_interactive hint
09-07 11:37:39.920  1377  1609 D KeyguardViewMediator: onScreenTurnedOff(3)
,09-07 11:37:39.923  6586  6586 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-07 11:37:39.923  6586  6586 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
09-07 11:37:39.941  1331  1348 D SmartCoverViewMediator: onScreenTurnedOff(3)
,09-07 11:37:39.951  6586  6586 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3c21a761 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@18bcaed1, 16908290=android.view.AbsSavedState$1@18bcaed1}, android:focusedViewId=100}]}]
09-07 11:37:39.952  6586  6586 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-07 11:37:39.952  6586  6586 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 11:37:39.952  6586  6586 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-07 11:37:39.956  1377  1609 D KeyguardViewMediator: notifyScreenOffLocked
,09-07 11:37:39.960  1331  1348 D SmartCoverViewMediator: notifyScreenOffLocked
,09-07 11:37:39.960  1331  1331 D SmartCoverViewMediator: handleNotifyScreenOFF
09-07 11:37:39.973  1377  1609 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
,09-07 11:37:39.975  1377  1377 D KeyguardViewMediator: handleNotifyScreenOff
09-07 11:37:40.000  1377  1377 D ScreenTurnOffBySensor: unregisterProximitySensor
,09-07 11:37:40.007  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 11:37:40.007  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 11:37:40.007  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
09-07 11:37:40.008   943   943 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
09-07 11:37:40.013  1377  1377 D StatusBarWindowView: onScreenTurnedOff why = 3
,09-07 11:37:40.016   282  1322 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 943
09-07 11:37:40.017   282  1322 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-07 11:37:40.017   282  1322 V voice   : voice_set_parameters: enter: screen_state=on
09-07 11:37:40.019   282  1322 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
09-07 11:37:40.019   282  1322 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-07 11:37:40.019   282  1322 V voice   : voice_set_parameters: exit with code(0)
09-07 11:37:40.019   282  1322 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
09-07 11:37:40.019   282  1322 V msm8974_platform: platform_set_parameters: enter: screen_state=on
09-07 11:37:40.019   282  1322 V msm8974_platform: platform_set_parameters: exit with code(0)
09-07 11:37:40.019   282  1322 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-07 11:37:40.019   282  1322 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
09-07 11:37:40.019   282  1322 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
09-07 11:37:40.019   282  1322 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-07 11:37:40.025  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 11:37:40.029  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
09-07 11:37:40.034   943  1309 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
09-07 11:37:40.678   943  1028 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,09-07 11:37:40.727   943  1949 D SplitWindow: check instance of lgWin Window{d0e1c4b u0 SearchPanel}
,09-07 11:37:40.735  1913  1913 I QCNEJ   : |CORE| sendScreenState: state:true
09-07 11:37:40.745  1877  2048 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
,09-07 11:37:40.747   943  1350 D InputDispatcher: Window went away: Window{3ab6d72c u0 SearchPanel}
09-07 11:37:40.750  1877  2048 D LEDService: stopPatternFlashing()
09-07 11:37:40.750  1377  1377 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
09-07 11:37:40.751  1877  2048 D qdlights: set_light_notifications: 0,0,0,0,3
09-07 11:37:40.752  1877  2048 I LEDService: getCurrentHighestLGLedRecord : size = 1
09-07 11:37:40.753  1877  2048 D qdlights: set_light_notifications: 0,0,0,0,3
09-07 11:37:40.754  1877  2048 I LEDService: updateLightsLocked : turn off led
09-07 11:37:40.754  1877  2048 D qdlights: set_light_notifications: 0,0,0,0,3
09-07 11:37:40.756  1877  2048 D LEDHandler: RESTART MSG
09-07 11:37:40.770  1377  1377 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,09-07 11:37:40.783  1877  1877 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,09-07 11:37:40.784   426   438 I Sensors : sns_pwr.c(301):releasing wakelock
09-07 11:37:40.785  1877  1877 D Cliptray Service: lockStatus = 0
09-07 11:37:40.788  1852  1852 D LNfcService: action : android.intent.action.SCREEN_ON
09-07 11:37:40.797  1852  7049 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
,09-07 11:37:40.798  1852  7049 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
09-07 11:37:40.798  1852  7049 D LNfcService: isRequireNfcCRouting() return true
09-07 11:37:40.798  1852  7049 D LNfcService: isHCERoutingtoHost() return : true
09-07 11:37:40.799  1852  7049 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
09-07 11:37:40.799  1852  7049 D NfcService: mEnableLPD: true
09-07 11:37:40.799  1852  7049 D NfcService: mEnableReader: false
09-07 11:37:40.799  1852  7049 D NfcService: mEnableHostRouting: true
09-07 11:37:40.799  1852  7049 D NfcService: newParams.techmask= mTechMask: default
09-07 11:37:40.799  1852  7049 D NfcService: mEnableLPD: true
09-07 11:37:40.799  1852  7049 D NfcService: mEnableReader: false
09-07 11:37:40.799  1852  7049 D NfcService: mEnableHostRouting: true
09-07 11:37:40.799  1852  7049 D NfcService: screenState= 3
09-07 11:37:40.799  1852  7049 D NfcService: Discovery configuration equal, not updating.
09-07 11:37:40.809   943   943 D Ulp_jni : JNI:system_update. Event-0
,09-07 11:37:40.846  1793  1793 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
09-07 11:37:40.855   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:37:40.855   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:37:40.856   943   943 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
,09-07 11:37:40.860  2871  2871 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:37:40
09-07 11:37:40.862  2871  2871 D WeatherService: 2 : ACTION screen on
09-07 11:37:40.864  2871  2871 D WeatherService: 2 : shouldTimeTickRegistered : false
09-07 11:37:40.874  2871  2871 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 11:37:40.874  2871  2871 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:37:40
,09-07 11:37:40.885  4245  4245 D AppCleanupService: android.intent.action.SCREEN_ON
,09-07 11:37:40.908   282   282 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 943
09-07 11:37:40.908   282   282 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-07 11:37:40.908   282   282 V voice   : voice_set_parameters: enter: screen_state=off
09-07 11:37:40.908   282   282 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
09-07 11:37:40.908   282   282 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-07 11:37:40.908   282   282 V voice   : voice_set_parameters: exit with code(0)
09-07 11:37:40.908   282   282 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
09-07 11:37:40.908   282   282 V msm8974_platform: platform_set_parameters: enter: screen_state=off
09-07 11:37:40.908   282   282 V msm8974_platform: platform_set_parameters: exit with code(0)
09-07 11:37:40.908   282   282 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-07 11:37:40.908   282   282 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
09-07 11:37:40.908   282   282 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-07 11:37:40.909   943  1314 D WifiController: CMD_SCREEN_OFF 
09-07 11:37:40.910   943  1314 D WifiController: shouldWifiStayAwake TRUE
09-07 11:37:40.915  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
,09-07 11:37:40.916   943  1028 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,09-07 11:37:40.943  1913  1913 I QCNEJ   : |CORE| sendScreenState: state:false
09-07 11:37:40.945  1877  2048 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
09-07 11:37:40.945  1877  2048 D LEDService: stopPatternFlashing()
09-07 11:37:40.945  1877  2048 D qdlights: set_light_notifications: 0,0,0,0,3
09-07 11:37:40.947  1877  2048 I LEDService: getCurrentHighestLGLedRecord : size = 1
09-07 11:37:40.947  1877  2048 D qdlights: set_light_notifications: 0,0,0,0,3
09-07 11:37:40.948  1877  1877 D VolumeVibrator: clear
09-07 11:37:40.949  1877  1877 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,09-07 11:37:40.950  1877  2048 I LEDService: updateLightsLocked : turn on led
09-07 11:37:40.951  1877  2048 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
09-07 11:37:40.951  1877  2048 E LEDService: Can't handle this request of patternId:0
09-07 11:37:40.951  1877  2048 D LEDHandler: RESTART MSG
09-07 11:37:40.951  1852  1852 D LNfcService: action : android.intent.action.SCREEN_OFF
,09-07 11:37:40.955  1852  2178 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
09-07 11:37:40.981  1951  1951 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,09-07 11:37:40.997  1793  1793 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,09-07 11:37:41.000   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:37:41.000   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:37:41.000   943   943 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
09-07 11:37:41.001  2871  2871 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 11:37:41
09-07 11:37:41.001  2871  2871 D WeatherService: 2 : ACTION screen off
09-07 11:37:41.003  2871  2871 D WeatherService: 2 : TimeTick Receiver Unregister
09-07 11:37:41.004  2871  2871 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 11:37:41
09-07 11:37:41.007  4245  4245 D AppCleanupService: android.intent.action.SCREEN_OFF
09-07 11:37:41.010  4245  7052 D AppCleanupService: AppUsageStatsSaveTask
,09-07 11:37:41.056  1852  2687 E NxpNfcJni: getReconnectState = 0x0
,09-07 11:37:41.059  1852  2178 D LCardEmulationManager: getHceAppCount hostAppNum : 0
09-07 11:37:41.059  1852  2178 D LCardEmulationManager: getDefaultRoute
09-07 11:37:41.060  1852  2178 D LNfcService: isRequireNfcCRouting() return true
09-07 11:37:41.060  1852  2178 D LNfcService: isHCERoutingtoHost() return : true
09-07 11:37:41.061  1852  2178 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
09-07 11:37:41.061  1852  2178 D NfcService: mEnableLPD: true
09-07 11:37:41.061  1852  2178 D NfcService: mEnableReader: false
09-07 11:37:41.061  1852  2178 D NfcService: mEnableHostRouting: true
09-07 11:37:41.061  1852  2178 D NfcService: newParams.techmask= mTechMask: 0
09-07 11:37:41.061  1852  2178 D NfcService: mEnableLPD: true
09-07 11:37:41.061  1852  2178 D NfcService: mEnableReader: false
09-07 11:37:41.061  1852  2178 D NfcService: mEnableHostRouting: true
09-07 11:37:41.061  1852  2178 D NfcService: screenState= 1
09-07 11:37:41.094  1852  2687 E NxpNfcJni: getReconnectState = 0x0
,09-07 11:37:41.101   943  1974 I ActivityManager: Process com.android.contacts (pid 6719) has died
09-07 11:37:42.667  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:42.667  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:42.667  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:37:42.667  6586  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ece599 not in the list
09-07 11:37:42.667  6586  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:42.668  6586  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2128905e not in the list
09-07 11:37:42.668  6586  6767 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:42.668  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:42.672  6586  6767 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-07 11:37:42.672  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:42.672  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:42.672  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:42.672  6586  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ece599 not in the list
09-07 11:37:42.672  6586  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:42.672  6586  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2128905e not in the list
09-07 11:37:42.672  6586  6767 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:42.672  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:42.672  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:42.673  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 11:37:42.673  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:42.673  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:42.673  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:42.674  6586  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ece599 not in the list
09-07 11:37:42.674  6586  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:42.674  6586  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2128905e not in the list
09-07 11:37:42.674  6586  6767 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:42.674  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:42.674  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:42.674  6586  6767 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-07 11:37:42.674  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:42.674  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:42.674  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:42.674  6586  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ece599 not in the list
09-07 11:37:42.675  6586  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:42.675  6586  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2128905e not in the list
09-07 11:37:42.675  6586  6767 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:42.675  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothMan,ager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:42.675  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:42.675  6586  6767 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 11:37:42.675  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:42.675  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:42.675  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:42.675  6586  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ece599 not in the list
09-07 11:37:42.675  6586  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:42.676  6586  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2128905e not in the list
09-07 11:37:42.676  6586  6767 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:42.676  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-07 11:37:42.676  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:42.676  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 11:37:42.679  6586  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 11:37:42.679  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 11:37:42.679  6586  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
09-07 11:37:42.679  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 11:37:42.679  6586  6767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 11:37:42.681  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:37:42.681  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:42.681  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:42.681  6586  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ece599 not in the list
09-07 11:37:42.681  6586  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 11:37:42.689  6586  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2128905e not in the list
09-07 11:37:42.689  6586  6767 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:42.689  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:42.689  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:42.690  6586  6767 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 11:37:42.690  6586  6767 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 11:37:42.690  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 11:37:42.694  6586  6767 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 11:37:42.694  6586  6767 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 11:37:42.694  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 11:37:42.694  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 11:37:42.694  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 11:37:42.694  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 11:37:42.695  6586  6767 D io.jxc,ore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 11:37:42.695  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 11:37:42.695  6586  6767 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-07 11:37:42.695  6586  6767 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 11:37:42.696  6586  6767 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,09-07 11:37:42.696  6586  6767 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 11:37:42.696  6586  6767 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 11:37:42.696  6586  6767 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 11:37:42.696  6586  6767 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 11:37:42.696  6586  6767 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 11:37:42.696  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-07 11:37:42.710  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-07 11:37:42.711  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 11:37:42.711  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-07 11:37:42.721  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 11:37:42.721  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 11:37:42.721  6586  6767 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 11:37:42.722  6586  6767 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 11:37:42.722  6586  6767 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 11:37:42.722  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:42.722  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:42.722  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:42.723  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 11:37:42.723  6586  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ece599 not in the list
09-07 11:37:42.723  6586  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:42.723  6586  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2128905e not in the list
09-07 11:37:42.723  6586  6767 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:42.723  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:42.723  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:42.724  6586  6767 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 11:37:42.724  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:42.724  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:42.724  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:42.724  6586  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ece599 not in the list
09-07 11:37:42.724  6586  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:42.724  6586  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2128905e not in the list
09-07 11:37:42.724  6586  6767 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:42.724  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:42.724  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:42.727  6586  7057 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 896
,09-07 11:37:42.731  6586  6767 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 11:37:42.732  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:42.732  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:42.732  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:42.732  6586  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ece599 not in the list
09-07 11:37:42.732  6586  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:42.732  6586  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2128905e not in the list
09-07 11:37:42.732  6586  6767 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:42.732  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:42.732  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:42.733  6586  6767 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 11:37:42.733  6586  6767 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 11:37:42.733  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 11:37:42.733  6586  6767 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 11:37:42.733  6586  6767 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 11:37:42.733  6586  6767 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 11:37:42.733  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 11:37:42.733  6586  6767 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 11:37:42.733  6586  6767 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 11:37:42.734  6586  6767 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 11:37:42.734  6586  6767 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 11:37:42.734  6586  6767 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 11:37:42.734  6586  6767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:42.734  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:42.734  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:42.734  6586  6767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ece599 not in the list
09-07 11:37:42.734  6586  6767 I org.thaliproject.p2p.b,tconnectorlib.DiscoveryManager: dispose
09-07 11:37:42.734  6586  6767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2128905e not in the list
09-07 11:37:42.734  6586  6767 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:42.734  6586  6767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:42.734  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:42.734  6586  6767 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 11:37:42.736  6586  7056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 896)
09-07 11:37:42.737  6586  7056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 896)
09-07 11:37:42.739  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:42.742  2079  2095 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
,09-07 11:37:42.746  6586  6767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:42.746  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:42.746  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 11:37:42.746  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:42.746  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:42.746  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:42.746  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:42.746  6586  6767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 11:37:42.747  2079  2096 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
09-07 11:37:42.747  6586  6767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:42.747  6586  6767 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 11:37:42.749  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:42.750  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:42.751  6586  6767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 11:37:42.751  6586  6767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 11:37:42.751  6586  6767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 11:37:42.751  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:42.751  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 11:37:42.755  2079  2096 D BluetoothAdapterService(253991977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29bc1747
,09-07 11:37:42.757  6586  6767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 11:37:42.757  6586  6767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:37:42.759  6586  6767 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 11:37:42.759  6586  6767 I io.jxcore.node.ConnectionHelper: start: OK
09-07 11:37:44.499   292   359 I ThermalEngine: Sensor:pa_therm0:31000 mC
,09-07 11:37:44.968  1377  1377 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,09-07 11:37:44.973   943  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{17a74172 type 2 when 159020 com.android.systemui} when 159020
,09-07 11:37:44.994  1793  2410 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
09-07 11:37:44.999  1793  2410 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-07 11:37:44.999  1793  2410 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-07 11:37:45.002  1793  2410 V TelecomServiceImpl: getCallState : 0
,09-07 11:37:45.007  1793  1820 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
09-07 11:37:45.007  1793  1820 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-07 11:37:45.007  1793  1820 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-07 11:37:45.009  1377  1377 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
09-07 11:37:45.010  1377  1377 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
09-07 11:37:49.506   292   359 I ThermalEngine: Sensor:pa_therm0:31000 mC
,09-07 11:37:54.512   292   359 I ThermalEngine: Sensor:pa_therm0:31000 mC
,09-07 11:37:58.490   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:37:58.490   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:37:58.490   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 172549326265; DSPS: 5752642; Offset : -3012680003
,09-07 11:37:59.518   292   359 I ThermalEngine: Sensor:pa_therm0:31000 mC
,09-07 11:38:00.071  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-07 11:38:00.071  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-07 11:38:00.071  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:38:00.076  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:38:00.077  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:38:00.077  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:38:00.078  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:38:00.079  3472  4426 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
09-07 11:38:04.524   292   359 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 11:38:08.155   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:38:08.161  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:38:08.162  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:38:08.162  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:38:08.162  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:38:08.162  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 11:38:08.225  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:38:08.226  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,09-07 11:38:08.229  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:38:08.229  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:38:08.229  1877  2048 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
09-07 11:38:08.230  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
09-07 11:38:08.230  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:38:08.230  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
09-07 11:38:08.233  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:38:08.234  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 11:38:08.238   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:38:08.238   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 11:38:08.241   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:38:08.279  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
09-07 11:38:08.279  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:38:08.279  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,09-07 11:38:08.283  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:38:08.283  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:38:08.285  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:38:08.285  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:38:08.285  1877  2048 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
09-07 11:38:08.285  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 11:38:08.287  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:38:08.290   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:38:08.290   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:38:08.291   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:38:09.530   292   359 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 11:38:11.017   943  1287 D PowerManagerServiceEx: acquireWakeLockInternal: lock=768354203, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=943
,09-07 11:38:11.023   943  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1853c9c3 type 2 when 185069 com.google.android.gms} when 185069
,09-07 11:38:11.062   943   943 D PowerManagerServiceEx: releaseWakeLockInternal: lock=768354203 [*alarm*], flags=0x0
,09-07 11:38:13.224   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:38:13.227  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 11:38:13.228  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:38:13.228  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:38:13.228  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:38:13.228  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:38:13.279  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
,09-07 11:38:13.283  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:38:13.283  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
09-07 11:38:13.285  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:38:13.285  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:38:13.287  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:38:13.288  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:38:13.288  1877  2048 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
09-07 11:38:13.291  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:38:13.293  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:38:13.297   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:38:13.297   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:38:13.297   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:38:14.536   292   359 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 11:38:16.593  1764  3497 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 11:38:18.493   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:38:18.493   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:38:18.493   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 192551538202; DSPS: 6408074; Offset : -3012665305
,09-07 11:38:19.543   292   359 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 11:38:24.549   292   359 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 11:38:29.555   292   359 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 11:38:34.561   292   359 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 11:38:38.495   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:38:38.495   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:38:38.495   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 212553832805; DSPS: 7063508; Offset : -3012629056
,09-07 11:38:39.567   292   359 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 11:38:44.574   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:38:49.580   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:38:53.633   943  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{32f88240 type 2 when 214346 android} when 214346
,09-07 11:38:54.586   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:38:58.497   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:38:58.497   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:38:58.497   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 232555948755; DSPS: 7718937; Offset : -3012618793
,09-07 11:38:59.592   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:39:00.080  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:39:00.080  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:39:00.080  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:39:00.085  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:39:00.085  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:39:00.085  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:39:00.086  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:39:04.598   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:39:09.604   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:39:13.364  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 11:39:13.367  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:39:13.367  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:39:13.367  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:39:13.367  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:39:13.377   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:39:13.428  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:39:13.428  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,09-07 11:39:13.432  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:39:13.433  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:39:13.433  1877  2048 D LEDHandler: Battery Temp: 279, mChargingStatus=5, mChargingStop=false
09-07 11:39:13.434  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
09-07 11:39:13.434  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:39:13.434  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
09-07 11:39:13.437   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:39:13.437   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:39:13.437   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:39:13.439  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 11:39:13.442  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 11:39:14.610   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:39:18.499   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:39:18.499   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:39:18.499   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 252558216794; DSPS: 8374376; Offset : -3012761616
,09-07 11:39:19.617   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:39:24.623   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:39:29.629   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:39:34.638   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:39:39.644   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:39:41.004   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:39:41.004   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:39:41.004   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 275063215566; DSPS: 9111816; Offset : -3012645501
,09-07 11:39:44.650   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:39:49.657   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:39:54.663   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:39:59.669   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:40:00.081  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:40:00.081  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:40:00.081  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:40:00.085  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:40:00.085  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:40:00.086  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:40:00.087  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:40:01.006   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:40:01.007   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:40:01.007   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 295065450568; DSPS: 9767251; Offset : -3012699316
,09-07 11:40:04.675   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:40:09.682   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:40:13.524  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:40:13.525  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:40:13.525  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:40:13.525  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 11:40:13.527  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 11:40:13.538   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:40:13.579  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:40:13.582  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:40:13.582  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:40:13.583  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:40:13.583  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:40:13.583  1877  2048 D LEDHandler: Battery Temp: 277, mChargingStatus=5, mChargingStop=false
09-07 11:40:13.585  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
09-07 11:40:13.585  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:40:13.585  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
09-07 11:40:13.587  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:40:13.591   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:40:13.591   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 11:40:13.594   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:40:14.688   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:40:16.009   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:40:16.009   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:40:16.009   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 310067599401; DSPS: 10258839; Offset : -3012625784
,09-07 11:40:19.694   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:40:24.700   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:40:29.707   292   359 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 11:40:31.011   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:40:31.011   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:40:31.011   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 325069886121; DSPS: 10750435; Offset : -3012658217
,09-07 11:40:34.713   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:40:39.719   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:40:44.725   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:40:47.554   943  3220 I LocationManagerService: remove 2c93d560
,09-07 11:40:47.678   943  3220 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
09-07 11:40:47.678   943  3220 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 11:40:47.678   943  3220 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
09-07 11:40:47.678   943  3220 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
09-07 11:40:47.679   943  3220 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,09-07 11:40:48.514   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:40:48.515   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:40:48.515   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 342573420295; DSPS: 11323991; Offset : -3012664395
,09-07 11:40:49.731   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:40:54.737   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:40:59.743   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:41:00.081  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:41:00.081  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:41:00.081  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:41:00.084  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:41:00.084  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:41:00.085  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:41:00.085  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:41:04.750   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:41:08.517   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:41:08.517   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:41:08.517   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 362575476710; DSPS: 11979419; Offset : -3012683123
,09-07 11:41:09.756   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:41:13.699  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:41:13.700  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:41:13.700  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:41:13.700  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 11:41:13.702  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 11:41:13.713   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:41:13.754  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:41:13.757  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:41:13.758  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:41:13.759  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:41:13.759  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:41:13.759  1877  2048 D LEDHandler: Battery Temp: 275, mChargingStatus=5, mChargingStop=false
09-07 11:41:13.760  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
09-07 11:41:13.761  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:41:13.761  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
09-07 11:41:13.763  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:41:13.766   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:41:13.766   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 11:41:13.770   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:41:14.762   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:41:19.768   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:41:24.774   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:41:28.519   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:41:28.519   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:41:28.519   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 382577830392; DSPS: 12634856; Offset : -3012679242
,09-07 11:41:29.780   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:41:34.786   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:41:39.792   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:41:44.798   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:41:48.521   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:41:48.521   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:41:48.521   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 402579892421; DSPS: 13290282; Offset : -3012631010
,09-07 11:41:49.805   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:41:54.811   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:41:59.817   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:42:00.001   943  1287 D PowerManagerServiceEx: acquireWakeLockInternal: lock=768354203, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=943
,09-07 11:42:00.023   943   943 D PowerManagerServiceEx: releaseWakeLockInternal: lock=768354203 [*alarm*], flags=0x0
,09-07 11:42:00.038  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:42:00.038  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:42:00.038  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:42:00.042  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:42:00.042  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:42:00.043  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:42:00.044  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:42:03.523   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:42:03.523   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:42:03.523   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 417582314556; DSPS: 13781882; Offset : -3012650541
,09-07 11:42:04.823   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:42:09.029  6786  6830 I PlayCommon: [827] com.google.android.play.a.l.e(787): Preparing logs for uploading
,09-07 11:42:09.049  1764  1764 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-07 11:42:09.060  1764  1764 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-07 11:42:09.061  1764  1764 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-07 11:42:09.107   943  2287 I NotificationManager: android: cancelAsUser(2) by android
,09-07 11:42:09.114  6786  6830 I PlayCommon: [827] com.google.android.play.a.l.a(927): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
09-07 11:42:09.137  6786  6830 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-07 11:42:09.137  6786  6830 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-07 11:42:09.138  6786  6830 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-07 11:42:09.138  6786  6830 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-07 11:42:09.138   276  1043 E BandwidthController: [LG DATA] No such appUid: 10036
09-07 11:42:09.138   276  1043 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
,09-07 11:42:09.139   276  7117 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
09-07 11:42:09.139   276  7117 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-07 11:42:09.139   276  7117 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
09-07 11:42:09.140   276  7117 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-07 11:42:09.206   276  7117 D libc-netbsd: res_queryN name = xxxxx succeed
09-07 11:42:09.206  6786  6830 I System.out: propertyValue:false
,09-07 11:42:09.501  6786  6830 I PlayCommon: [827] com.google.android.play.a.l.a(1002): Successfully uploaded logs.
,09-07 11:42:09.829   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:42:13.852  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 11:42:13.854   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-07 11:42:13.861  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:42:13.861  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:42:13.862  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:42:13.862  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:42:13.898  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:42:13.902  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:42:13.902  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:42:13.903  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:42:13.903  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:42:13.904  1877  2048 D LEDHandler: Battery Temp: 275, mChargingStatus=5, mChargingStop=false
09-07 11:42:13.905  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
09-07 11:42:13.905  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:42:13.906  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
09-07 11:42:13.908  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:42:13.912   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:42:13.912   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 11:42:13.915   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:42:14.836   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:42:19.842   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:42:21.027   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:42:21.027   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:42:21.027   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 435085607126; DSPS: 14355430; Offset : -3012653895
,09-07 11:42:24.848   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:42:29.854   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:42:34.860   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:42:39.866   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:42:41.029   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:42:41.029   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:42:41.029   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 455087862603; DSPS: 15010869; Offset : -3012809280
,09-07 11:42:44.872   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:42:49.878   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:42:54.884   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:42:56.031   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:42:56.031   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:42:56.031   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 470090150090; DSPS: 15502464; Offset : -3012810768
,09-07 11:42:59.890   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:43:00.080  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:43:00.080  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:43:00.080  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:43:00.085  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:43:00.085  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:43:00.086  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:43:00.087  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:43:04.896   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:43:08.108  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 11:43:08.110  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:43:08.110  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:43:08.110  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:43:08.110  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:43:08.121   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:43:08.190  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:43:08.197  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:43:08.197  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:43:08.198  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:43:08.198  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:43:08.198  1877  2048 D LEDHandler: Battery Temp: 274, mChargingStatus=5, mChargingStop=false
09-07 11:43:08.202   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:43:08.202   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:43:08.204   943  1314 D WifiController: battery changed pluggedType: 2
,09-07 11:43:08.206  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
09-07 11:43:08.206  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:43:08.207  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
09-07 11:43:08.209  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:43:08.244  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:43:08.247  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
09-07 11:43:08.248  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:43:08.248  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:43:08.249  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:43:08.249  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:43:08.249  1877  2048 D LEDHandler: Battery Temp: 274, mChargingStatus=5, mChargingStop=false
09-07 11:43:08.251  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:43:08.251  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
09-07 11:43:08.253  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:43:08.256   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:43:08.256   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 11:43:08.260   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:43:09.905   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:43:11.033   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:43:11.033   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:43:11.034   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 485092367433; DSPS: 15994052; Offset : -3012668464
,09-07 11:43:14.016  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,09-07 11:43:14.019   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-07 11:43:14.021  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:43:14.021  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:43:14.021  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:43:14.022  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 11:43:14.063  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
,09-07 11:43:14.066  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:43:14.066  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
09-07 11:43:14.068  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:43:14.069  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:43:14.071  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:43:14.071  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:43:14.071  1877  2048 D LEDHandler: Battery Temp: 273, mChargingStatus=5, mChargingStop=false
09-07 11:43:14.074  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:43:14.075  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:43:14.082   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:43:14.082   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:43:14.082   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:43:14.911   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:43:19.917   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:43:24.923   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:43:29.701  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,09-07 11:43:29.705  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:43:29.705  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:43:29.705  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:43:29.706  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 11:43:29.745   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:43:29.771  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,09-07 11:43:29.775  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:43:29.775  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:43:29.775  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:43:29.776  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 11:43:29.820   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:43:29.889  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
,09-07 11:43:29.893  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:43:29.893  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
09-07 11:43:29.895  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:43:29.896  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:43:29.898  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:43:29.898  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:43:29.898  1877  2048 D LEDHandler: Battery Temp: 275, mChargingStatus=5, mChargingStop=false
09-07 11:43:29.901  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 11:43:29.905  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 11:43:29.909   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:43:29.909   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:43:29.910   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:43:29.941   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:43:29.948  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 11:43:29.948  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:43:29.948  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:43:29.949  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:43:29.949  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:43:29.967   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:43:30.010  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:43:30.015  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:43:30.015  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:43:30.018  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:43:30.018  1877  2048 D LEDHandler: Battery Level Remaining: 100%
,09-07 11:43:30.018  1877  2048 D LEDHandler: Battery Temp: 275, mChargingStatus=5, mChargingStop=false
09-07 11:43:30.018  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
09-07 11:43:30.018  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:43:30.019  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
09-07 11:43:30.023  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 11:43:30.026   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:43:30.027   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:43:30.027   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:43:31.036   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:43:31.036   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:43:31.036   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 505094583523; DSPS: 16649485; Offset : -3012680262
,09-07 11:43:31.739  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:43:31.739  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:43:31.739  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:43:31.739  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 11:43:31.742  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 11:43:31.752   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:43:34.973   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:43:39.980   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:43:44.986   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:43:46.038   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:43:46.038   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:43:46.038   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 520096778343; DSPS: 17141079; Offset : -3012743820
,09-07 11:43:49.992   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:43:54.998   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:43:59.169   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:43:59.169   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:43:59.170   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 533228386921; DSPS: 17571377; Offset : -3012788126
,09-07 11:44:00.004   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:44:00.063  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:44:00.063  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:44:00.063  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:44:00.066  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:44:00.066  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:44:00.068  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:44:00.069  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:44:05.010   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:44:08.121  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 11:44:08.123  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:44:08.124  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:44:08.124  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:44:08.124  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:44:08.134   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:44:08.192  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:44:08.192  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,09-07 11:44:08.196  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:44:08.196  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:44:08.196  1877  2048 D LEDHandler: Battery Temp: 274, mChargingStatus=5, mChargingStop=false
09-07 11:44:08.198  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 11:44:08.202   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:44:08.202   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:44:08.202   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:44:08.203  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
09-07 11:44:08.203  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:44:08.203  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
09-07 11:44:08.205  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 11:44:08.244  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
09-07 11:44:08.244  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:44:08.244  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,09-07 11:44:08.248  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 11:44:08.249  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:44:08.249  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:44:08.250  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:44:08.250  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:44:08.250  1877  2048 D LEDHandler: Battery Temp: 273, mChargingStatus=5, mChargingStop=false
09-07 11:44:08.252  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:44:08.256   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:44:08.256   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:44:08.256   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:44:10.016   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:44:14.171  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,09-07 11:44:14.175   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-07 11:44:14.176  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:44:14.176  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:44:14.176  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:44:14.177  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 11:44:15.023   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:44:15.118   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:44:15.118   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:44:15.118   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 549176836141; DSPS: 18093971; Offset : -3012642155
,09-07 11:44:20.029   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:44:25.035   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:44:30.041   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:44:30.120   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:44:30.120   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:44:30.120   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 564179006032; DSPS: 18585563; Offset : -3012669295
,09-07 11:44:35.048   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:44:40.054   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:44:45.060   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:44:47.017   943  1287 D PowerManagerServiceEx: acquireWakeLockInternal: lock=768354203, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=943
09-07 11:44:47.018   943  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1163f317 type 2 when 581069 android} when 581069
,09-07 11:44:47.046   943   943 D PowerManagerServiceEx: releaseWakeLockInternal: lock=768354203 [*alarm*], flags=0x0
,09-07 11:44:47.624   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:44:47.624   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:44:47.624   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 581682650691; DSPS: 19159123; Offset : -3012686693
,09-07 11:44:50.066   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:44:55.072   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:45:00.047  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:45:00.047  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:45:00.047  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:45:00.052  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:45:00.052  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:45:00.053  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:45:00.053  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:45:00.080   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:45:02.626   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:45:02.626   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:45:02.626   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 596684466526; DSPS: 19650706; Offset : -3012793518
,09-07 11:45:05.087   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:45:10.093   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:45:14.324  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 11:45:14.327  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:45:14.327  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:45:14.327  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:45:14.327  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:45:14.337   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:45:14.378  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:45:14.381  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:45:14.382  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:45:14.383  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:45:14.383  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:45:14.383  1877  2048 D LEDHandler: Battery Temp: 272, mChargingStatus=5, mChargingStop=false
09-07 11:45:14.387   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:45:14.387   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:45:14.388   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:45:14.389  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
09-07 11:45:14.389  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:45:14.389  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
09-07 11:45:14.391  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 11:45:15.099   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:45:17.627   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:45:17.627   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:45:17.627   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 611686240728; DSPS: 20142292; Offset : -3013033710
,09-07 11:45:20.105   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:45:25.111   292   359 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 11:45:30.117   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:45:31.383   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:45:31.383   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:45:31.383   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 625441814361; DSPS: 20593024; Offset : -3012709023
,09-07 11:45:35.123   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:45:40.130   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:45:45.136   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:45:50.142   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:45:52.015   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:45:52.015   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:45:52.015   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 646073709167; DSPS: 21269086; Offset : -3012588912
,09-07 11:45:55.148   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:46:00.080  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:46:00.080  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:46:00.080  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:46:00.085  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:46:00.085  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:46:00.086  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:46:00.086  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:46:00.154   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:46:05.146   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:46:05.146   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:46:05.146   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 659205156625; DSPS: 21699379; Offset : -3012641984
,09-07 11:46:05.160   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:46:10.166   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:46:14.484  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:46:14.484  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:46:14.484  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:46:14.484  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 11:46:14.487  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 11:46:14.497   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:46:14.538  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:46:14.542  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:46:14.542  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:46:14.543  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:46:14.543  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:46:14.543  1877  2048 D LEDHandler: Battery Temp: 271, mChargingStatus=5, mChargingStop=false
09-07 11:46:14.545  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
09-07 11:46:14.545  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:46:14.545  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
09-07 11:46:14.547  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:46:14.550   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:46:14.550   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:46:14.552   943  1314 D WifiController: battery changed pluggedType: 2
,09-07 11:46:15.173   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:46:20.148   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:46:20.148   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:46:20.148   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 674207297457; DSPS: 22190972; Offset : -3012728648
,09-07 11:46:20.179   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:46:25.185   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:46:30.191   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:46:35.151   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:46:35.151   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:46:35.151   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 689209487506; DSPS: 22682563; Offset : -3012705164
,09-07 11:46:35.197   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:46:40.204   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:46:45.210   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:46:50.216   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:46:52.654   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:46:52.654   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:46:52.654   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 706712592155; DSPS: 23256108; Offset : -3012805095
,09-07 11:46:55.222   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:47:00.080  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:47:00.080  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:47:00.080  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:47:00.084  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:47:00.084  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:47:00.085  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:47:00.086  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:47:00.228   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:47:05.235   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:47:05.785   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:47:05.785   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:47:05.785   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 719844148055; DSPS: 23686401; Offset : -3012749440
,09-07 11:47:10.241   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:47:14.644  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 11:47:14.647  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:47:14.647  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:47:14.647  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:47:14.647  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:47:14.657   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:47:14.696  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:47:14.699  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:47:14.699  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:47:14.700  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:47:14.700  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:47:14.701  1877  2048 D LEDHandler: Battery Temp: 270, mChargingStatus=5, mChargingStop=false
09-07 11:47:14.705   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:47:14.705   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:47:14.706   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:47:14.706  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
09-07 11:47:14.706  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:47:14.707  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
09-07 11:47:14.709  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 11:47:15.247   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:47:20.253   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:47:20.787   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:47:20.787   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:47:20.788   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 734846411965; DSPS: 24177990; Offset : -3012591374
,09-07 11:47:25.259   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:47:30.266   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:47:35.272   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:47:40.278   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:47:43.292   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:47:43.292   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:47:43.292   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 757350797351; DSPS: 24915416; Offset : -3012661371
,09-07 11:47:45.284   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:47:50.290   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:47:55.296   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:47:58.294   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:47:58.294   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:47:58.294   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 772353106658; DSPS: 25407011; Offset : -3012641066
,09-07 11:48:00.079  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:48:00.079  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:48:00.080  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:48:00.084  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:48:00.084  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:48:00.085  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:48:00.085  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:48:00.303   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:48:05.309   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:48:10.315   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:48:14.806  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 11:48:14.808  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:48:14.808  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:48:14.808  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:48:14.808  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:48:14.819   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:48:15.321   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:48:15.797   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:48:15.797   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:48:15.797   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 789856027883; DSPS: 25980548; Offset : -3012679863
,09-07 11:48:20.327   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:48:25.333   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:48:30.340   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:48:35.348   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:48:35.800   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:48:35.800   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:48:35.800   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 809858550653; DSPS: 26635994; Offset : -3012781787
,09-07 11:48:40.354   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:48:45.360   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:48:50.367   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:48:55.373   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:48:58.304   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:48:58.304   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:48:58.304   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 832363025560; DSPS: 27373418; Offset : -3012701437
,09-07 11:49:00.080  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:49:00.080  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:49:00.080  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:49:00.084  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:49:00.084  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:49:00.085  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:49:00.086  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:49:00.379   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:49:05.385   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:49:10.391   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:49:14.964  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 11:49:14.967  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:49:14.967  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:49:14.967  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:49:14.967  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:49:14.977   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:49:15.397   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:49:18.306   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:49:18.306   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:49:18.306   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 852365227602; DSPS: 28028848; Offset : -3012635444
,09-07 11:49:20.404   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:49:25.410   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:49:30.416   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:49:35.423   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:49:38.309   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:49:38.309   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:49:38.309   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 872367636329; DSPS: 28684287; Offset : -3012637788
,09-07 11:49:40.429   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:49:45.435   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:49:50.441   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:49:53.311   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:49:53.311   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:49:53.311   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 887369686938; DSPS: 29175864; Offset : -3012326292
,09-07 11:49:55.447   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:50:00.079  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:50:00.079  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:50:00.079  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:50:00.085  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:50:00.085  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:50:00.086  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:50:00.087  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:50:00.453   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:50:05.460   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:50:10.466   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:50:14.566   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:50:14.566   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:50:14.566   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 908624958269; DSPS: 29872371; Offset : -3012762033
,09-07 11:50:15.124  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 11:50:15.127  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:50:15.127  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:50:15.127  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:50:15.127  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:50:15.137   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:50:15.178  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:50:15.181  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:50:15.182  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:50:15.183  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:50:15.183  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:50:15.183  1877  2048 D LEDHandler: Battery Temp: 269, mChargingStatus=5, mChargingStop=false
09-07 11:50:15.188   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:50:15.188   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:50:15.188   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:50:15.188  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
09-07 11:50:15.189  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:50:15.189  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
09-07 11:50:15.191  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 11:50:15.472   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:50:20.478   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:50:25.484   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:50:29.568   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:50:29.568   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:50:29.568   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 923626715902; DSPS: 30363954; Offset : -3012926954
,09-07 11:50:30.491   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:50:35.497   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:50:40.504   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:50:45.509   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:50:50.515   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:50:50.824   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:50:50.824   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:50:50.824   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 944883179398; DSPS: 31060484; Offset : -3012872280
,09-07 11:50:52.456   943  1287 D PowerManagerServiceEx: acquireWakeLockInternal: lock=768354203, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=943
,09-07 11:50:52.459   943  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3669b304 type 2 when 946509 com.android.bluetooth} when 946509
09-07 11:50:52.664  2079  3659 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
09-07 11:50:52.664  2079  3659 W bt-smp  : Plain text(LSB ~ MSB) = b4 90 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
,09-07 11:50:52.667  2079  3659 W bt-smp  : Encrypted text(LSB ~ MSB) = 1c 97 87 01 cb e1 0c 7a c7 89 a1 1d 1d 71 4d 90 
09-07 11:50:52.668  2079  3659 W bt-btm  : Stopping oneshot timer
09-07 11:50:52.729   943  4928 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7244 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,09-07 11:50:52.910  7244  7244 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,09-07 11:50:52.919  7244  7244 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@22c1ea57
09-07 11:50:52.923   943   943 D PowerManagerServiceEx: releaseWakeLockInternal: lock=768354203 [*alarm*], flags=0x0
09-07 11:50:55.520   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:51:00.042  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:51:00.042  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:51:00.042  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:51:00.047  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:51:00.047  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:51:00.048  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:51:00.048  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:51:00.526   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:51:05.533   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:51:10.539   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:51:13.328   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:51:13.328   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:51:13.328   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 967386826671; DSPS: 31797878; Offset : -3012704063
,09-07 11:51:15.284  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:51:15.284  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:51:15.284  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:51:15.284  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 11:51:15.287  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 11:51:15.298   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:51:15.545   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:51:20.551   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:51:25.558   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:51:28.330   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:51:28.330   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:51:28.331   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 982389379868; DSPS: 32289479; Offset : -3012622687
,09-07 11:51:30.564   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:51:35.570   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:51:40.576   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:51:42.086   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:51:42.086   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:51:42.086   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 996145283967; DSPS: 32740231; Offset : -3012577962
,09-07 11:51:45.582   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:51:50.589   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:51:55.595   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:51:56.635   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:51:56.635   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:51:56.635   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1010694103491; DSPS: 33216970; Offset : -3012678219
,09-07 11:52:00.079  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:52:00.079  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:52:00.080  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:52:00.085  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:52:00.085  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:52:00.085  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:52:00.086  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:52:00.601   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:52:05.607   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:52:10.613   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:52:11.637   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:52:11.637   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:52:11.637   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1025696326406; DSPS: 33708567; Offset : -3012805106
,09-07 11:52:15.445  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 11:52:15.447  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:52:15.447  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:52:15.448  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:52:15.448  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:52:15.458   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:52:15.499  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:52:15.503  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:52:15.503  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:52:15.504  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:52:15.504  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:52:15.504  1877  2048 D LEDHandler: Battery Temp: 268, mChargingStatus=5, mChargingStop=false
09-07 11:52:15.509   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:52:15.509   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:52:15.509   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:52:15.510  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
09-07 11:52:15.510  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:52:15.510  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
09-07 11:52:15.512  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 11:52:15.620   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:52:20.626   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:52:25.632   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:52:26.642   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:52:26.642   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:52:26.642   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1040700913546; DSPS: 34200235; Offset : -3012734541
,09-07 11:52:30.638   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:52:35.644   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:52:40.650   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:52:41.644   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:52:41.644   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:52:41.644   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1055702555753; DSPS: 34691806; Offset : -3012648601
,09-07 11:52:45.656   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:52:50.663   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:52:55.669   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:52:56.645   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:52:56.645   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:52:56.645   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1070704272612; DSPS: 35183382; Offset : -3012640883
,09-07 11:53:00.078  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:53:00.078  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:53:00.078  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:53:00.084  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:53:00.084  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:53:00.084  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:53:00.085  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:53:00.675   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:53:05.681   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:53:10.687   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:53:15.605  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 11:53:15.607  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:53:15.607  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:53:15.607  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:53:15.607  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:53:15.618   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:53:15.693   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:53:17.901   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:53:17.901   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:53:17.901   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1091959660514; DSPS: 35879881; Offset : -3012715237
,09-07 11:53:20.700   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:53:25.706   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:53:30.712   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:53:32.903   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:53:32.903   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:53:32.903   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1106961675844; DSPS: 36371476; Offset : -3012989089
,09-07 11:53:35.718   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:53:40.724   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:53:45.730   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:53:50.736   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:53:54.158   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:53:54.158   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:53:54.158   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1128217184595; DSPS: 37067967; Offset : -3012698714
,09-07 11:53:55.750   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:54:00.078  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:54:00.078  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:54:00.078  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:54:00.083  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:54:00.083  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:54:00.084  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:54:00.085  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:54:00.756   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:54:05.762   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:54:10.768   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:54:14.160   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:54:14.160   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:54:14.161   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1148219370385; DSPS: 37723399; Offset : -3012710216
,09-07 11:54:15.764  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 11:54:15.767  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:54:15.767  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:54:15.767  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:54:15.767  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:54:15.777   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:54:15.781   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-07 11:54:15.820  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:54:15.824  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:54:15.824  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:54:15.825  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:54:15.825  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:54:15.825  1877  2048 D LEDHandler: Battery Temp: 267, mChargingStatus=5, mChargingStop=false
09-07 11:54:15.829   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:54:15.829   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:54:15.830   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:54:15.831  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
09-07 11:54:15.831  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:54:15.831  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 267
09-07 11:54:15.833  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 11:54:20.783   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:54:25.789   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:54:30.796   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:54:34.163   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:54:34.163   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:54:34.163   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1168221912086; DSPS: 38378842; Offset : -3012701683
,09-07 11:54:35.802   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:54:40.808   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:54:45.814   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:54:50.821   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:54:54.165   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:54:54.165   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:54:54.165   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1188224191869; DSPS: 39034275; Offset : -3012649553
,09-07 11:54:55.827   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:55:00.078  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:55:00.078  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:55:00.079  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:55:00.084  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:55:00.084  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:55:00.085  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:55:00.085  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:55:00.833   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:55:05.839   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:55:10.845   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:55:14.167   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:55:14.168   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:55:14.168   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1208226449579; DSPS: 39689709; Offset : -3012650273
,09-07 11:55:15.852   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:55:15.924  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 11:55:15.926  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:55:15.927  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:55:15.927  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:55:15.927  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:55:15.937   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:55:20.858   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:55:25.864   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:55:30.340   943  1028 I UsageStatsService: User[0] Flushing usage stats to disk
,09-07 11:55:30.870   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:55:34.170   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:55:34.170   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:55:34.170   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1228228577988; DSPS: 40345136; Offset : -3012566308
,09-07 11:55:35.876   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:55:40.882   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:55:45.888   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:55:49.172   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:55:49.172   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:55:49.172   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1243231042907; DSPS: 40836746; Offset : -3012847969
,09-07 11:55:50.895   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:55:55.901   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:56:00.078  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:56:00.078  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:56:00.078  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:56:00.083  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:56:00.083  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:56:00.084  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:56:00.085  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:56:00.907   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:56:02.304   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:56:02.304   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:56:02.304   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1256362898135; DSPS: 41267045; Offset : -3012676274
,09-07 11:56:05.913   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:56:10.919   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:56:15.925   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:56:16.084  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 11:56:16.087  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:56:16.087  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:56:16.087  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:56:16.087  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:56:16.097   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:56:16.139  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:56:16.142  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:56:16.143  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:56:16.144  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:56:16.144  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:56:16.144  1877  2048 D LEDHandler: Battery Temp: 266, mChargingStatus=5, mChargingStop=false
09-07 11:56:16.149   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:56:16.149   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:56:16.149   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:56:16.150  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
09-07 11:56:16.150  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:56:16.150  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
09-07 11:56:16.152  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 11:56:17.306   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:56:17.306   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:56:17.306   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1271365077632; DSPS: 41758636; Offset : -3012663421
,09-07 11:56:20.931   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:56:25.937   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:56:30.943   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:56:35.949   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:56:37.308   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:56:37.308   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:56:37.308   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1291367262018; DSPS: 42414068; Offset : -3012676354
,09-07 11:56:40.955   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:56:45.962   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:56:50.968   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:56:55.974   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:56:57.310   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:56:57.310   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:56:57.310   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1311369065911; DSPS: 43069487; Offset : -3012672763
,09-07 11:57:00.078  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:57:00.078  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:57:00.078  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:57:00.083  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:57:00.083  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:57:00.084  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:57:00.085  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:57:00.980   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:57:05.986   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:57:09.607  6786  6830 I PlayCommon: [827] com.google.android.play.a.l.e(787): Preparing logs for uploading
09-07 11:57:09.608  6786  6830 I PlayCommon: [827] com.google.android.play.a.l.e(789): No file ready to send
,09-07 11:57:10.993   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:57:15.999   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:57:16.244  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:57:16.245  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:57:16.245  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:57:16.245  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 11:57:16.248  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 11:57:16.258   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:57:17.313   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:57:17.313   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:57:17.313   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1331371598957; DSPS: 43724930; Offset : -3012672702
,09-07 11:57:21.005   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:57:26.011   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:57:31.017   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:57:36.024   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:57:37.315   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:57:37.315   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:57:37.315   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1351373938429; DSPS: 44380366; Offset : -3012652618
,09-07 11:57:41.030   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:57:46.036   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:57:51.042   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:57:56.048   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:57:57.317   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:57:57.317   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:57:57.317   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1371376094366; DSPS: 45035795; Offset : -3012602628
,09-07 11:58:00.077  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:58:00.078  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:58:00.078  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:58:00.083  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:58:00.083  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:58:00.084  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:58:00.084  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:58:01.055   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:58:06.061   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:58:11.067   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:58:16.073   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:58:16.404  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 11:58:16.407  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:58:16.407  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:58:16.407  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:58:16.407  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:58:16.418   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:58:17.319   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
,09-07 11:58:17.319   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:58:17.319   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1391377888812; DSPS: 45691216; Offset : -3012669312
,09-07 11:58:21.079   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:58:26.085   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:58:31.091   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:58:36.098   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:58:37.322   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:58:37.322   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:58:37.322   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1411380510042; DSPS: 46346662; Offset : -3012672905
,09-07 11:58:41.104   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:58:46.110   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:58:51.116   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:58:56.122   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:58:57.324   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:58:57.324   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:58:57.324   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1431382669980; DSPS: 47002093; Offset : -3012679742
,09-07 11:59:00.078  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:59:00.078  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:59:00.078  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:59:00.083  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:59:00.083  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:59:00.084  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:59:00.085  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:59:01.128   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:59:06.134   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:59:11.141   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:59:16.147   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:59:16.565  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 11:59:16.567  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 11:59:16.567  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:59:16.567  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 11:59:16.568  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 11:59:16.579   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 11:59:16.620  2079  3564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 11:59:16.624  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 11:59:16.624  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 11:59:16.625  1877  2048 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:59:16.625  1877  2048 D LEDHandler: Battery Level Remaining: 100%
09-07 11:59:16.625  1877  2048 D LEDHandler: Battery Temp: 265, mChargingStatus=5, mChargingStop=false
09-07 11:59:16.630   943   943 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:59:16.630   943   943 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:59:16.631   943  1314 D WifiController: battery changed pluggedType: 2
09-07 11:59:16.631  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
09-07 11:59:16.631  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:59:16.631  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
09-07 11:59:16.633  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 11:59:17.326   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:59:17.326   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:59:17.326   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1451384870508; DSPS: 47657525; Offset : -3012676479
,09-07 11:59:21.153   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:59:26.159   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:59:31.165   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:59:36.171   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:59:37.328   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:59:37.328   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:59:37.328   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1471387133090; DSPS: 48312959; Offset : -3012672199
,09-07 11:59:41.177   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:59:46.183   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:59:51.190   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:59:56.196   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 11:59:57.335   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 11:59:57.335   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 11:59:57.336   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1491393694790; DSPS: 48968534; Offset : -3012671829
,09-07 12:00:00.078  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:00:00.078  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:00:00.078  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
,09-07 12:00:00.083  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:00:00.083  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:00:00.084  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:00:00.085  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:00:01.202   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 12:00:06.208   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 12:00:11.214   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 12:00:16.220   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 12:00:16.725  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 12:00:16.727  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 12:00:16.728  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 12:00:16.728  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 12:00:16.728  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 12:00:16.738   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 12:00:17.337   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 12:00:17.337   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 12:00:17.337   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1511395807657; DSPS: 49623967; Offset : -3012786589
,09-07 12:00:21.227   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 12:00:26.233   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 12:00:31.239   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 12:00:31.408   943   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 12:00:31.408   943   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 12:00:31.408   943   995 D sensors_hal_Time: tsOffsetIs: Apps: 1525466909800; DSPS: 50085037; Offset : -3012424325
,TIME-OUT KILL (timeout was 1400000ms),09-07 12:00:36.244   292   359 I ThermalEngine: Sensor:pa_therm0:27000 mC
09-07 12:00:36.801  7394  7394 D AndroidRuntime: 
09-07 12:00:36.801  7394  7394 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-07 12:00:36.806  7394  7394 D AndroidRuntime: CheckJNI is OFF
09-07 12:00:37.139  7394  7394 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-07 12:00:37.188   943  1030 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
09-07 12:00:37.188   943  1030 I ActivityManager: Killing 6586:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
09-07 12:00:37.240   943  2015 I WindowState: WIN DEATH: Window{a8da530 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 12:00:37.250   943  2015 D InputDispatcher: Focus left window: Window{a8da530 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 12:00:37.250   943  2015 D InputDispatcher: Window went away: Window{a8da530 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 12:00:37.280   943  1062 W PackageSettings: Skipping PackageSetting{24d775b5 com.example.hello/10317} due to missing metadata
09-07 12:00:37.400   943  1030 I ActivityManager:   Force finishing activity ActivityRecord{33a41767 u0 com.test.thalitest/.MainActivity t259}
09-07 12:00:37.414   943   943 V ActivityManager: Display changed displayId=0
09-07 12:00:37.418  1793  1793 D DSDPConnection: Display #0 changed.
09-07 12:00:37.432   943  1950 W ActivityManager: Spurious death for ProcessRecord{18a4a0ed 6586:com.test.thalitest/u0a30}, curProc for 6586: null
09-07 12:00:37.434   943  1062 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
09-07 12:00:37.435   943  1062 I ActivityManager:   Force finishing activity ActivityRecord{33a41767 u0 com.test.thalitest/.MainActivity t259 f}
09-07 12:00:37.435   943  1062 W ActivityManager: Duplicate finish request for ActivityRecord{33a41767 u0 com.test.thalitest/.MainActivity t259 f}
09-07 12:00:37.513  2028  2028 I art     : Explicit concurrent mark sweep GC freed 2927(259KB) AllocSpace objects, 1(23KB) LOS objects, 40% free, 12MB/21MB, paused 6.620ms total 71.423ms
09-07 12:00:37.536  1377  1377 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-07 12:00:37.556  1913  1913 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
09-07 12:00:37.564  3761  3761 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-07 12:00:37.566  1951  1951 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
09-07 12:00:37.576  1764  2386 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-07 12:00:37.587   943  1289 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-07 12:00:37.597  3472  3472 I art     : Explicit concurrent mark sweep GC freed 3149(152KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 16MB/21MB, paused 1.027ms total 144.219ms
09-07 12:00:37.599   943  1030 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7426 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
09-07 12:00:37.628  1951  1951 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
09-07 12:00:37.632  3761  3761 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-07 12:00:37.634  3761  3761 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-07 12:00:37.637  1951  1951 I [LGHome]EVENT: [LauncherModel.java:1358:startLoader()]startLoader isLaunching=true
09-07 12:00:37.638  3761  3761 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
09-07 12:00:37.638  3761  3761 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 12:00:37.638  3761  3761 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 12:00:37.638  3761  3761 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 12:00:37.638  3761  3761 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
09-07 12:00:37.638  3761  3761 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:00:37.638  3761  3761 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:00:37.638  3761  3761 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
09-07 12:00:37.638  3761  3761 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
09-07 12:00:37.639  1951  2058 I [LGHome]Launcher.Model: [LauncherModel.java:1475:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
09-07 12:00:37.650  1377  1377 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-07 12:00:37.665  1951  1951 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-07 12:00:37.666  1951  1951 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
09-07 12:00:37.666  1951  1951 I Activity: Activity.onPostResume() called 
09-07 12:00:37.675  1951  1951 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
09-07 12:00:37.695  1951  7444 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
09-07 12:00:37.696  1377  1505 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-07 12:00:37.696  1377  1505 D KeyguardModel: createShortcutInfo...
09-07 12:00:37.699  1377  1505 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-07 12:00:37.699  1377  1505 D KeyguardModel: createShortcutInfo...
09-07 12:00:37.705  1377  1505 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 12:00:37.705   943  1051 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
09-07 12:00:37.705   943  1051 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
09-07 12:00:37.706   943  1051 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
09-07 12:00:37.706   943  1051 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
09-07 12:00:37.706   943  1051 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-07 12:00:37.706   943  1051 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@7d2987b,  pkg=WindowManager.LayoutParams
09-07 12:00:37.706   943  1051 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
09-07 12:00:37.709  1377  1377 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-07 12:00:37.709  1377  1377 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-07 12:00:37.710  1377  1377 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
09-07 12:00:37.710  1377  1377 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
09-07 12:00:37.710  1377  1377 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
09-07 12:00:37.710  1377  1377 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
09-07 12:00:37.711  1377  1505 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-07 12:00:37.714   943  1949 D InputDispatcher: Focus entered window: Window{d570433 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
09-07 12:00:37.716  1377  1505 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-07 12:00:37.716  1377  1505 D KeyguardModel: createShortcutInfo...
09-07 12:00:37.720  1377  1505 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 12:00:37.720  1377  1505 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-07 12:00:37.725  1377  1505 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-07 12:00:37.725  1377  1505 D KeyguardModel: createShortcutInfo...
09-07 12:00:37.728  1377  1505 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 12:00:37.728  1377  1505 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-07 12:00:37.730  1377  1505 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-07 12:00:37.730  1377  1505 D KeyguardModel: createShortcutInfo...
09-07 12:00:37.735  1951  1951 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-07 12:00:37.736  1951  1951 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-07 12:00:37.736  1951  1951 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
09-07 12:00:37.740  7426  7426 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 12:00:37.745  7426  7426 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 12:00:37.750  7426  7426 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-07 12:00:37.753  1951  1951 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
09-07 12:00:37.756  1377  1377 D KeyguardModel: handleShortcutListChanged...
09-07 12:00:37.760  1377  1505 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-07 12:00:37.760  1377  1505 D KeyguardModel: createShortcutInfo...
09-07 12:00:37.760  1951  1951 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
09-07 12:00:37.762  1951  1951 I PhoneWindow: [setNavigationBarColor] color=0x 0
09-07 12:00:37.763  1377  1505 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-07 12:00:37.763  1377  1505 D KeyguardModel: createShortcutInfo...
09-07 12:00:37.775   943  1974 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
09-07 12:00:37.776  1377  1505 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 12:00:37.777  1377  1505 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-07 12:00:37.779   943  1974 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6586 uid 10030
09-07 12:00:37.785  1377  1505 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-07 12:00:37.785  1377  1505 D KeyguardModel: createShortcutInfo...
09-07 12:00:37.787  1377  1505 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 12:00:37.787  1377  1505 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-07 12:00:37.788  1377  1505 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-07 12:00:37.788  1377  1505 D KeyguardModel: createShortcutInfo...
09-07 12:00:37.790  1377  1505 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 12:00:37.791  1377  1505 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-07 12:00:37.792  1377  1505 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-07 12:00:37.793  1377  1505 D KeyguardModel: createShortcutInfo...
09-07 12:00:37.799  1377  1377 D KeyguardModel: handleShortcutListChanged...
09-07 12:00:37.822   943   943 I art     : Explicit concurrent mark sweep GC freed 68300(4MB) AllocSpace objects, 15(240KB) LOS objects, 33% free, 23MB/35MB, paused 10.647ms total 328.759ms
09-07 12:00:37.828   943  1062 I art     : WaitForGcToComplete blocked for 292.687ms for cause Explicit
09-07 12:00:37.828  1951  1951 I [LGHome]Launcher.Model: [LauncherModel.java:2270:run()] LauncherModel bind current page shortcut
09-07 12:00:37.839  1951  1951 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-07 12:00:37.872   943  1053 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2c1ab445 u0 com.lge.launcher2/.Launcher t258} time:1531931
09-07 12:00:37.894  1951  1951 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-07 12:00:37.896  1951  1951 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-07 12:00:37.898  1951  1951 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-07 12:00:37.899  1951  1951 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-07 12:00:37.915   943   943 D administrator: Handling package changes for user 0
09-07 12:00:37.954  1951  1951 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-07 12:00:38.013  1951  1951 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-07 12:00:38.014  1951  1951 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
09-07 12:00:38.014  1951  1951 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-07 12:00:38.061  7426  7426 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
09-07 12:00:38.070  1951  1951 W Resources: Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
09-07 12:00:38.077  1951  1951 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
09-07 12:00:38.077  1951  1951 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
09-07 12:00:38.078  1951  1951 W Resources: Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
09-07 12:00:38.092  1951  1951 W Resources: Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
09-07 12:00:38.098  7426  7426 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
09-07 12:00:38.114  1951  1951 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
09-07 12:00:38.114  1951  1951 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
09-07 12:00:38.121  1951  1951 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
09-07 12:00:38.122  1951  1951 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
09-07 12:00:38.122  1951  1951 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
09-07 12:00:38.130   943   943 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-07 12:00:38.130   943   943 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-07 12:00:38.133   943   943 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-07 12:00:38.135  1951  1951 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
09-07 12:00:38.139   943  1352 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
09-07 12:00:38.152  1951  1951 W Resources: Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
09-07 12:00:38.157   943  1062 I art     : Explicit concurrent mark sweep GC freed 6931(407KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.434ms total 329.193ms
09-07 12:00:38.234  1852  1852 D LCardEmulationManager: getHceAppCount hostAppNum : 0
09-07 12:00:38.234  1852  1852 D LCardEmulationManager: getDefaultRoute
09-07 12:00:38.265  7394  7394 D AndroidRuntime: Shutting down VM
09-07 12:00:38.299  1951  1951 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
09-07 12:00:38.365  7426  7426 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
09-07 12:00:38.389  1951  1951 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-07 12:00:38.389  1951  1951 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
09-07 12:00:38.390  1951  1951 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
09-07 12:00:38.390  1951  1951 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-07 12:00:38.407  1951  1951 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-07 12:00:38.408  1951  1951 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
09-07 12:00:38.410  1951  1951 I Choreographer: Skipped 33 frames!  The application may be doing too much work on its main thread.
09-07 12:00:38.410  1951  1951 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-07 12:00:38.413  1951  1951 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-07 12:00:38.415  1951  1951 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
09-07 12:00:38.416  1625  1625 E b       : Unable to connect to the editor to retrieve text... will retry later
09-07 12:00:38.417  1951  1951 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-07 12:00:38.418  1951  1951 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
09-07 12:00:38.419  1951  1951 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
09-07 12:00:38.424  1951  2169 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-07 12:00:38.424  6664  6664 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-07 12:00:38.426  1951  2169 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-07 12:00:38.430  1951  1951 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
09-07 12:00:38.431  1951  1951 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-07 12:00:38.432  1951  1951 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-07 12:00:38.485   943  1919 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7454 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
09-07 12:00:38.486   943  1919 I ActivityManager: Killing 6786:com.android.vending/u0a36 (adj 15): empty #11
09-07 12:00:38.498  1951  1951 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
09-07 12:00:38.525  1951  1951 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-07 12:00:38.525  1951  1951 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-07 12:00:38.528  1951  1951 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-07 12:00:38.542   943  4928 W libprocessgroup: failed to open /acct/uid_10036/pid_6786/cgroup.procs: No such file or directory
09-07 12:00:38.596   943  1062 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7473 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-07 12:00:38.645  1951  1951 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@35bc4f59 time:1532704
09-07 12:00:38.709  1951  1951 I art     : Explicit concurrent mark sweep GC freed 22426(1248KB) AllocSpace objects, 16(2MB) LOS objects, 39% free, 15MB/25MB, paused 1.945ms total 59.192ms
09-07 12:00:38.729   943  2541 I ActivityManager: Killing 6842:com.google.android.apps.plus/u0a86 (adj 15): empty #11

```
