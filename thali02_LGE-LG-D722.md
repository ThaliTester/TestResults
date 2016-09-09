#### Test 836273375fe617f_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
09-09 13:41:00.663  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
09-09 13:41:01.126   293   354 I ThermalEngine: Sensor:pa_therm0:38000 mC
,09-09 13:41:01.439  6482  6482 D AndroidRuntime: 
09-09 13:41:01.439  6482  6482 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 13:41:01.443  6482  6482 D AndroidRuntime: CheckJNI is OFF
09-09 13:41:01.661  6482  6482 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-09 13:41:01.681   838  1801 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 13:41:01.745   838  1801 D ActivityManager: setTaskToReturnTo : TaskRecord{9e2a50 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-09 13:41:01.748   838  1801 D ActivityManager: setTaskToReturnTo : TaskRecord{9e2a50 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-09 13:41:01.771   838  1801 D WindowStateEx: AppWindowTokenEx init.. 
09-09 13:41:01.799   838  1018 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-09 13:41:01.810   838  1801 D InputDispatcher: Focus left window: Window{3e2805f8 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
09-09 13:41:01.818  1874  1874 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
09-09 13:41:01.819  6482  6482 D AndroidRuntime: Shutting down VM
09-09 13:41:01.823   838  1018 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-09 13:41:01.840   838  1018 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-09 13:41:01.840   838  1018 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-09 13:41:01.858   838  1018 D SplitWindow: check instance of lgWin Window{1f6cf368 u0 Starting com.test.thalitest}
09-09 13:41:01.886   838  1775 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6502 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-09 13:41:01.914  1874  1874 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
09-09 13:41:01.968  1874  1874 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
09-09 13:41:01.970   838  1864 I WindowStateAnimator: Starting window displayed
09-09 13:41:01.978   838  1016 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
09-09 13:41:01.982   838  1016 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
09-09 13:41:01.987   838  1016 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
09-09 13:41:01.987   838  1016 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
09-09 13:41:01.987   838  1016 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-09 13:41:01.991   838  1016 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1685e527,  pkg=WindowManager.LayoutParams
09-09 13:41:01.991   838  1016 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
09-09 13:41:02.004  1375  1375 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
09-09 13:41:02.007  1375  1375 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
09-09 13:41:02.007  1375  1375 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
09-09 13:41:02.007  1375  1375 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
09-09 13:41:02.017  1949  1949 I HotwordDetector: Closing mic
,09-09 13:41:02.027  1949  2563 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@3462bcf9
09-09 13:41:02.027  1949  2563 V AudioRecord: stop()
09-09 13:41:02.027  1949  2563 D AudioRecord: AudioRecord->stop()
09-09 13:41:02.028   280  1296 V AudioFlinger: RecordHandle::stop()
09-09 13:41:02.028   280  1296 V AudioFlinger: RecordThread::stop
09-09 13:41:02.043   280  1296 V AudioFlinger: Record stopped OK
09-09 13:41:02.045   280  1296 V AudioPolicyManager: stopInput() input 17
09-09 13:41:02.050   280  1296 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
09-09 13:41:02.050   280  1296 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
09-09 13:41:02.050   280  1062 V AudioPolicyService: AudioCommandThread() waking up
09-09 13:41:02.050   280  1062 V AudioPolicyService: AudioCommandThread() processing release audio patch
09-09 13:41:02.050   280  1062 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
09-09 13:41:02.050   280  1062 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
09-09 13:41:02.050   280  1062 V AudioFlinger: ThreadBase::setParameters() routing=0
09-09 13:41:02.053   280  2578 D audio_hw_primary: in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
09-09 13:41:02.098   280  2578 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
09-09 13:41:02.098   280  2578 V audio_hw_primary: disable_audio_route: enter: usecase(7)
09-09 13:41:02.098   280  2578 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
09-09 13:41:02.098   280  2578 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-09 13:41:02.106   280  2578 V audio_hw_primary: disable_audio_route: exit
09-09 13:41:02.106   280  2578 E audio_hw_primary: disable_snd_device: enter 144
09-09 13:41:02.106   280  2578 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
09-09 13:41:02.106   280  2578 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
09-09 13:41:02.109   280  2578 V audio_hw_primary: stop_input_stream: exit: status(0)
09-09 13:41:02.109   280  2578 V audio_hw_primary: in_standby: exit:  status(0)
09-09 13:41:02.110   280  2578 V AudioFlinger: RecordThread: loop stopping
09-09 13:41:02.110   280  1062 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
09-09 13:41:02.110   280  2578 V AudioFlinger: RecordThread: loop starting
09-09 13:41:02.110   280  2578 V AudioFlinger: processConfigEvents_l() remaining events 1
09-09 13:41:02.110   280  2578 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3871000
09-09 13:41:02.110   280  2578 V AudioFlinger: RecordThread: loop stopping
09-09 13:41:02.110   280  1062 V AudioPolicyService: AudioCommandThread() going to sleep
09-09 13:41:02.110   280  1296 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
09-09 13:41:02.111   280  1296 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
09-09 13:41:02.111   280  1296 V AudioPolicyService: AudioCommandThread() adding update audio patch list
09-09 13:41:02.111   280  1296 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
09-09 13:41:02.111   280  1063 V AudioPolicyService: AudioCommandThread() waking up
09-09 13:41:02.111   280  1063 V AudioPolicyService: AudioCommandThread() processing update audio patch list
09-09 13:41:02.111   280  1063 V AudioPolicyService: AudioCommandThread() going to sleep
09-09 13:41:02.112   280  1296 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
09-09 13:41:02.112   280  1296 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
09-09 13:41:02.112   280  1062 V AudioPolicyService: AudioCommandThread() waking up
09-09 13:41:02.112   280  1062 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
09-09 13:41:02.112   280  1062 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 280
09-09 13:41:02.112   280  1062 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
09-09 13:41:02.112   280  1062 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
09-09 13:41:02.112   280  2578 V AudioFlinger: RecordThread: loop starting
09-09 13:41:02.112   280  2578 V AudioFlinger: processConfigEvents_l() remaining events 1
09-09 13:41:02.112   280  2578 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
09-09 13:41:02.112   280  2578 V audio_hw_primary: in_set_parameters: exit: status(0)
09-09 13:41:02.112   280  2578 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3871000
09-09 13:41:02.113   280  2578 V AudioFlinger: RecordThread: loop stopping
09-09 13:41:02.113   280  1062 V AudioPolicyService: AudioCommandThread() going to sleep
09-09 13:41:02.115  1949  2563 V AudioRecord: stop()
09-09 13:41:02.116  1949  2563 V AudioRecord: stop()
09-09 13:41:02.116  1949  2563 V AudioRecord: stop()
09-09 13:41:02.117   280  1599 V AudioFlinger: RecordHandle::stop()
09-09 13:41:02.117   280  1599 V AudioFlinger: RecordThread::stop
09-09 13:41:02.117   280  1599 V AudioPolicyManager: releaseInput() 17
09-09 13:41:02.117   280  1599 V AudioPolicyManager: closeInput(17)
09-09 13:41:02.117   280  1599 V AudioFlinger: closeInput() 17
09-09 13:41:02.117   280  1599 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-09 13:41:02.117   838  1775 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-09 13:41:02.117   280  1599 V AudioFlinger: ThreadBase::exit
09-09 13:41:02.117  1748  2672 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-09 13:41:02.117   280  2578 V AudioFlinger: RecordThread: loop starting
09-09 13:41:02.117  2880  2895 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-09 13:41:02.118   280  2578 V AudioFlinger: RecordThread 0xb3871000 exiting
09-09 13:41:02.118  3150  3165 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-09 13:41:02.118   280  1599 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546e1a0)
09-09 13:41:02.118   280  1599 D audio_hw_primary: in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
09-09 13:41:02.118   280  1599 V audio_hw_primary: in_standby: exit:  status(0)
09-09 13:41:02.118   280  1599 V AudioPolicyService: AudioCommandThread() adding update audio port list
09-09 13:41:02.118   280  1599 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
09-09 13:41:02.118   280  1599 V AudioPolicyManager: releaseInput() exit
09-09 13:41:02.118   280  1063 V AudioPolicyService: AudioCommandThread() waking up
09-09 13:41:02.118   280  1063 V AudioPolicyService: AudioCommandThread() processing update audio port list
09-09 13:41:02.118   280  1599 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
09-09 13:41:02.118   280  1599 V AudioFlinger: removeClient_l() pid 1949, calling pid 280
09-09 13:41:02.119   280  1063 V AudioPolicyService: AudioCommandThread() going to sleep
09-09 13:41:02.119  2007  3522 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-09 13:41:02.119  1375  2662 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-09 13:41:02.119  1949  1988 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-09 13:41:02.120   280  1296 V AudioFlinger: releasing 16 from 1949 for -1
09-09 13:41:02.120   280  1296 V AudioFlinger:  decremented refcount to 0
09-09 13:41:02.120   280  1296 V AudioFlinger: purging stale effects
09-09 13:41:02.124  1949  2571 I HotwordRecognitionRnr: Stopping hotword detection.
09-09 13:41:02.128  1949  2574 I HotwordRecognitionRnr: Hotword detection finished
09-09 13:41:02.139  6502  6502 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-09 13:41:02.246  6502  6502 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
09-09 13:41:02.307  6502  6502 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9462-9465)
09-09 13:41:02.308  6502  6502 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:41:02.350  6502  6502 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3c5f2e40}
09-09 13:41:02.352  6502  6502 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:41:02.352  6502  6502 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 13:41:02.368  1874  1874 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-09 13:41:02.373  1375  1375 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
09-09 13:41:02.373  6502  6502 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 13:41:02.374  6502  6502 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:41:02.376  1874  1874 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-09 13:41:02.376  1874  1874 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
09-09 13:41:02.376  6502  6502 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 13:41:02.381  1837  1837 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
09-09 13:41:02.386   838  1286 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-09 13:41:02.401  1874  1874 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-09 13:41:02.404  2880  2880 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19963
09-09 13:41:02.410   838   892 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6538 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-09 13:41:02.419   838   838 D administrator: Handling package changes for user 0
09-09 13:41:02.423  1375  1375 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-09 13:41:02.439  6502  6502 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-09 13:41:02.443  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
09-09 13:41:02.443  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
09-09 13:41:02.444  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
09-09 13:41:02.444  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
09-09 13:41:02.444  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
09-09 13:41:02.444  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
09-09 13:41:02.444  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
09-09 13:41:02.444  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
09-09 13:41:02.444  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
09-09 13:41:02.444  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
09-09 13:41:02.444  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
09-09 13:41:02.444  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
09-09 13:41:02.444  1375  1375 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-09 13:41:02.454  6502  6502 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:41:02.454  6502  6502 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:41:02.455  6502  6502 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:02.455  6502  6502 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:02.455  6502  6502 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:41:02.455  6502  6502 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:41:02.455  6502  6502 I Adreno-EGL: Remote Branch: 
09-09 13:41:02.455  6502  6502 I Adreno-EGL: Local Patches: 
09-09 13:41:02.455  6502  6502 I Adreno-EGL: Reconstruct Branch: 
09-09 13:41:02.529  6538  6538 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 13:41:02.560   280  1599 V AudioPolicyService: registerClient() client 0xb4027880, uid 10030
09-09 13:41:02.572   838  1017 D BluetoothManagerService: Message: 20
09-09 13:41:02.572   838  1017 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a80062f:true
09-09 13:41:02.587  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:02.723   838   838 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-09 13:41:02.724   838   838 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-09 13:41:02.724   838   838 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
09-09 13:41:02.731   838   838 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
09-09 13:41:02.746  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:02.747  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:02.747  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-09 13:41:02.750   838   838 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
09-09 13:41:02.750   838   838 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1eccaaa5
09-09 13:41:02.776   838   890 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:02.859   838  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{dbc92a0 type 2 when 120000 com.google.android.gms} when 120000
,09-09 13:41:02.887  6502  6502 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:41:02.898   838   890 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-09 13:41:02.906  6502  6502 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 13:41:02.925  6502  6502 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,09-09 13:41:02.933  6502  6502 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-09 13:41:02.933  6502  6502 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-09 13:41:02.933  1784  1784 D LCardEmulationManager: getHceAppCount hostAppNum : 0
09-09 13:41:02.933  1784  1784 D LCardEmulationManager: getDefaultRoute
09-09 13:41:02.947  1874  1874 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-09 13:41:02.959  6502  6502 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-09 13:41:02.964  1730  1730 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
09-09 13:41:02.972  6502  6502 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:41:02.972  6502  6502 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:41:02.992   838   890 D LocationProviderProxy: applying state to connected service
,09-09 13:41:03.017  6538  6580 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-09 13:41:03.018  6538  6580 I Babel_SMS: MmsConfig.loadMmsSettings
,09-09 13:41:03.022  6538  6580 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-09 13:41:03.022  6538  6580 I Babel_SMS: MmsConfig.loadFromDatabase
09-09 13:41:03.047  6502  6502 I Activity: Activity.onPostResume() called 
,09-09 13:41:03.061  6502  6584 D OpenGLRenderer: Render dirty regions requested: true
,09-09 13:41:03.062  6502  6584 I OpenGLRenderer: Initialized EGL, version 1.4
09-09 13:41:03.070  6502  6584 D OpenGLRenderer: Enabling debug mode 0
,09-09 13:41:03.078  6538  6580 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-09 13:41:03.078  6538  6580 I Babel_SMS: MmsConfig.loadFromResources
09-09 13:41:03.086  6538  6580 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-09 13:41:03.087  6538  6580 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,09-09 13:41:03.092  6502  6502 D Atlas   : Validating map...
09-09 13:41:03.098   838   866 D SplitWindow: check instance of lgWin Window{2977fa3d u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 13:41:03.109  6502  6562 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-09 13:41:03.116  6538  6538 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
09-09 13:41:03.116  6538  6538 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
09-09 13:41:03.117  6538  6538 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
09-09 13:41:03.117  6538  6538 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
09-09 13:41:03.117  6538  6538 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
09-09 13:41:03.117  6538  6538 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
09-09 13:41:03.117  6538  6538 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
09-09 13:41:03.117  6538  6538 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
09-09 13:41:03.117  6538  6538 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
09-09 13:41:03.117  6538  6538 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
09-09 13:41:03.117  6538  6538 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
09-09 13:41:03.117  6538  6538 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
09-09 13:41:03.117  6538  6538 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
09-09 13:41:03.118  6538  6538 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
09-09 13:41:03.118  6538  6538 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
09-09 13:41:03.118  6538  6538 D SensorManager: found sensor: Motion Accel, handle=46
09-09 13:41:03.147   838   867 D InputDispatcher: Focus entered window: Window{2977fa3d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 13:41:03.180  6538  6538 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:03.184  6538  6538 I Babel_Crash: startup - clean
09-09 13:41:03.212   838  1359 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,09-09 13:41:03.218   838  1018 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s372ms
09-09 13:41:03.220   838  1018 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3e1c9449 u0 com.test.thalitest/.MainActivity t259} time:120377
09-09 13:41:03.227  6538  6554 I art     : CheckpointMarkThreadRoots callback created = 0xaaf3e4b0
,09-09 13:41:03.243  6502  6502 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@5d3087a time:120401
,09-09 13:41:03.255  6538  6587 I Babel   : deleted: false for 0
,09-09 13:41:03.267  6538  6554 I art     : CheckpointMarkThreadRoots callback created = 0xaaf3e4a0
09-09 13:41:03.408  6502  6502 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6502
,09-09 13:41:03.413  6538  6538 W AudioCapabilities: Unsupported mime audio/x-lg-flac
09-09 13:41:03.418  6538  6538 W AudioCapabilities: Unsupported mime audio/adpcm
09-09 13:41:03.420  6538  6538 W AudioCapabilities: Unsupported mime audio/g726
09-09 13:41:03.421  6538  6538 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-09 13:41:03.424  6538  6538 W AudioCapabilities: Unsupported mime audio/wma-voice
09-09 13:41:03.427  6538  6538 W VideoCapabilities: Unsupported mime video/mjpg
,09-09 13:41:03.437   838  1864 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6592 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
09-09 13:41:03.469  6538  6538 W VideoCapabilities: Unsupported mime video/theora
,09-09 13:41:03.520  6538  6538 W AudioCapabilities: Unsupported mime audio/evrc
,09-09 13:41:03.522  6538  6538 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 13:41:03.523  6538  6538 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:41:03.536  6538  6538 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,09-09 13:41:03.540  6538  6538 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 13:41:03.541  6538  6538 W AudioCapabilities: Unsupported mime audio/evrc
09-09 13:41:03.567  6538  6538 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-09 13:41:03.590  6592  6592 I AppUp4:AppBoxCP: onCreate
,09-09 13:41:03.598  6538  6538 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-09 13:41:03.604  6592  6592 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-09 13:41:03.617  6538  6538 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:41:03.619  6538  6538 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:41:03.620  6502  6502 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 13:41:03.621  6592  6592 I AppUp4:DB:  setFingerPrint start
09-09 13:41:03.621  6592  6592 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
09-09 13:41:03.624  6538  6538 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:41:03.630  6538  6538 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:41:03.636  6592  6592 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
09-09 13:41:03.636  6592  6592 I AppUp4:DB:  SDK version = 21
09-09 13:41:03.637  6592  6592 I AppUp4:DB:  beforefinger == newfinger no write in DB
,09-09 13:41:03.641  6592  6592 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-09 13:41:03.669  6592  6592 I AppUp4:CustModeStarterReceiver: onReceive
,09-09 13:41:03.669  6592  6592 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,09-09 13:41:03.674  6592  6592 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@43b58d4
09-09 13:41:03.674  6592  6592 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:41:03.682  6592  6592 D AppUp4:CustFacade: isSimDevice : true
,09-09 13:41:03.689  6592  6592 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:41:03.689  6592  6592 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-09 13:41:03.691   838  1864 I ActivityManager: Killing 6205:com.lge.eula/1000 (adj 15): empty #11
09-09 13:41:03.764   838  1775 W libprocessgroup: failed to open /acct/uid_1000/pid_6205/cgroup.procs: No such file or directory
,09-09 13:41:03.817   838  1899 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6616 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-09 13:41:03.860  6538  6538 I vclib   : onServiceConnected
,09-09 13:41:03.867  6538  6538 W Babel   : Attempted to change video mute state without an active call.
09-09 13:41:03.874  6538  6612 I NotificationManager: com.google.android.talk: cancel(8) by com.google.android.talk
,09-09 13:41:03.901  6538  6538 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 13:41:03.901  6538  6538 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 13:41:03.921  6616  6616 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:41:03.922  6616  6616 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 13:41:03.922  6616  6616 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,09-09 13:41:03.991  6538  6538 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 13:41:04.146  6538  6538 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-09 13:41:04.147  6538  6538 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-09 13:41:04.162  6538  6538 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,09-09 13:41:04.208  6502  6589 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1631420160
,09-09 13:41:04.227  6616  6616 I AppConfig: Total System Memory = 906309632
,09-09 13:41:04.233  6616  6616 I GalleryUtils: Application Heap = 96 MB
09-09 13:41:04.238  6616  6616 I AppConfig: App Tier : NOT_DEF
09-09 13:41:04.241  6502  6589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 13:41:04.241  6502  6589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 13:41:04.241  6502  6589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 13:41:04.241  6502  6589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 13:41:04.241  6502  6589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 13:41:04.241  6502  6589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36d054ff added. We now have 1 listener(s)
09-09 13:41:04.251  6616  6616 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-09 13:41:04.252   838  1880 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 13:41:04.261  6502  6589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
09-09 13:41:04.263  6502  6589 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-09 13:41:04.265  6502  6589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:04.266  6502  6589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:04.275  6502  6589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 13:41:04.275  6502  6589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 13:41:04.275  6502  6589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 13:41:04.275  6502  6589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
09-09 13:41:04.275  6502  6589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 13:41:04.275  6502  6589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 13:41:04.275  6502  6589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 13:41:04.275  6502  6589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 13:41:04.275  6502  6589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 13:41:04.275  6502  6589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 13:41:04.275  6502  6589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 13:41:04.275  6502  6589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 13:41:04.275  6502  6589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 13:41:04.275  6502  6589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 13:41:04.275  6502  6589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@273e842a added. We now have 1 listener(s)
,09-09 13:41:04.276  6502  6589 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:04.310  6502  6589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:04.310  6502  6589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-09 13:41:04.312  6502  6589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 13:41:04.312  6502  6589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 13:41:04.312  6502  6589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-09 13:41:04.343   838  1801 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6640 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,09-09 13:41:04.344   838  1801 I ActivityManager: Killing 6270:com.google.android.apps.docs/u0a58 (adj 15): empty #11
09-09 13:41:04.367   301   301 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 319us total 23.800ms
,09-09 13:41:04.391   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 325us total 23.178ms
,09-09 13:41:04.415   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 23.494ms
,09-09 13:41:04.436  6502  6589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:04.441   838  1899 W libprocessgroup: failed to open /acct/uid_10058/pid_6270/cgroup.procs: No such file or directory
09-09 13:41:04.443   838   866 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:04.446  6502  6589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
,09-09 13:41:04.458  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:04.460  6502  6589 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-09 13:41:04.462  6640  6640 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:41:04.462  6502  6589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:04.462  6502  6589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:04.462  6502  6589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:04.462  6502  6589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:04.462  6502  6589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:04.462  6502  6589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:04.462  6502  6589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:04.462  6502  6589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:04.462  6640  6640 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:41:04.462  6640  6640 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-09 13:41:04.464  6502  6589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 13:41:04.464  6502  6589 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:04.464  6640  6640 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-09 13:41:04.464  6640  6640 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 13:41:04.467  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:04.468  6502  6589 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 13:41:04.469  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:04.511  6502  6502 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 13:41:04.628  6640  6640 I SystemConfig: BUILD Country: EU
09-09 13:41:04.628  6640  6640 I SystemConfig: BUILD Operator: OPEN
,09-09 13:41:04.640  6502  6516 I art     : CheckpointMarkThreadRoots callback created = 0x986e9080
09-09 13:41:04.681  6502  6516 I art     : CheckpointMarkThreadRoots callback created = 0x986e9050
,09-09 13:41:04.771   838  2176 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6660 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
09-09 13:41:04.772   838  2176 I ActivityManager: Killing 6106:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,09-09 13:41:04.895   838  1783 W libprocessgroup: failed to open /acct/uid_10086/pid_6106/cgroup.procs: No such file or directory
,09-09 13:41:04.922  6640  6658 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-09 13:41:04.922  6640  6658 I SystemConfig: existFile = false
09-09 13:41:04.922  6640  6658 I SystemConfig: canReadFile = false
,09-09 13:41:04.922  6640  6658 I SystemConfig: systemFeature RCS result false
09-09 13:41:04.923  6640  6658 D SystemConfig: refreshRcsSupport() :false
09-09 13:41:04.942   838  1987 I art     : Explicit concurrent mark sweep GC freed 61488(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 9.562ms total 204.453ms
,09-09 13:41:04.954  6660  6660 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-09 13:41:04.986  6660  6660 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-09 13:41:04.986  6660  6660 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,09-09 13:41:04.986  6660  6660 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-09 13:41:04.986  6660  6660 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-09 13:41:04.987  6660  6660 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-09 13:41:04.988   838  1844 I ActivityManager: Killing 6314:com.lge.bnr/1000 (adj 15): empty #11
09-09 13:41:05.065   838  1819 W libprocessgroup: failed to open /acct/uid_1000/pid_6314/cgroup.procs: No such file or directory
,09-09 13:41:05.072  1375  1375 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-09 13:41:05.072  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-09 13:41:05.075  1375  1375 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-09 13:41:05.077  1375  1375 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-09 13:41:05.077  1375  1375 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-09 13:41:05.084  3382  6679 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-09 13:41:05.093  3382  6679 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-09 13:41:05.093  3382  6679 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,09-09 13:41:05.118  3382  3636 I Icing   : updateResources: need to parse ozd{com.google.android.gms}
,09-09 13:41:05.145   489   489 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-09 13:41:05.174   838   866 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6684 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:05.186  1375  1375 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 344
09-09 13:41:05.186  1375  1375 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,09-09 13:41:05.187  2007  3528 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-09 13:41:05.188  1375  1375 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 344
09-09 13:41:05.190  1802  1971 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-09 13:41:05.190  1802  1971 D LEDHandler: Battery Level Remaining: 100%
09-09 13:41:05.190  1802  1971 D LEDHandler: Battery Temp: 344, mChargingStatus=5, mChargingStop=false
09-09 13:41:05.194  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-09 13:41:05.196  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-09 13:41:05.199   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:05.199   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:05.202  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-09 13:41:05.202  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,09-09 13:41:05.203   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:05.203   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:05.205   838  1311 D WifiController: battery changed pluggedType: 2
09-09 13:41:05.205   838  1311 D WifiController: battery changed pluggedType: 2
09-09 13:41:05.205  2007  3528 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-09 13:41:05.206  1802  1971 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-09 13:41:05.206  1802  1971 D LEDHandler: Battery Level Remaining: 100%
09-09 13:41:05.206  1802  1971 D LEDHandler: Battery Temp: 343, mChargingStatus=5, mChargingStop=false
09-09 13:41:05.210  1375  1375 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-09 13:41:05.212  1375  1375 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 343
09-09 13:41:05.212  1375  1375 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-09 13:41:05.212  1375  1375 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 343
09-09 13:41:05.215  1375  1375 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-09 13:41:05.255  3382  6699 W IcingInternalCorpora: getNumBytesRead when not calculated.
,09-09 13:41:05.272  6684  6684 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:05.419  1730  5651 I art     : Explicit concurrent mark sweep GC freed 32971(2MB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 14MB/23MB, paused 2.431ms total 120.704ms
,09-09 13:41:05.494  6502  6657 W jxcore-log: Initializing JXcore engine
,09-09 13:41:05.495  6502  6657 W jxcore-log: JXcore engine is ready
,09-09 13:41:05.616  1949  6710 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-09 13:41:05.620   280  1296 V AudioFlinger: 2880 died, releasing its sessions
09-09 13:41:05.620   280  1296 V AudioFlinger:  pid 1748 @ 0
09-09 13:41:05.620   280  1296 V AudioFlinger:  pid 3150 @ 1
09-09 13:41:05.620   280  1296 V AudioFlinger:  pid 3150 @ 2
09-09 13:41:05.628  6657  6657 W Thread-775: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6336]" dev="sockfs" ino=6336 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-09 13:41:05.628  6657  6657 W Thread-775: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-09 13:41:05.628  6657  6657 W Thread-775: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7436]" dev="sockfs" ino=7436 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-09 13:41:05.628  6657  6657 W Thread-775: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
09-09 13:41:05.628  6657  6657 W Thread-775: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
09-09 13:41:05.628  6657  6657 W Thread-775: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[31055]" dev="sockfs" ino=31055 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-09 13:41:05.662  6502  6657 W jxcore-log: Starting JXcore engine
,09-09 13:41:05.676  1949  6710 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 60 ms] updated apps [took 60 ms] 
09-09 13:41:05.682   838  1347 I ActivityManager: Process com.lge.music (pid 2880) has died
,09-09 13:41:05.808  6502  6657 W jxcore-log: Platform android
09-09 13:41:05.808  6502  6657 W jxcore-log: 
09-09 13:41:05.808  6502  6657 W jxcore-log: Process ARCH arm
09-09 13:41:05.808  6502  6657 W jxcore-log: 
,09-09 13:41:06.101  6502  6657 I jxcore-log: JXcore Cordova bridge is ready!
09-09 13:41:06.101  6502  6657 I jxcore-log: 
09-09 13:41:06.102  6502  6657 W jxcore-log: JXcore engine is started
,09-09 13:41:06.114  6502  6589 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 13:41:06.117  6502  6502 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-09 13:41:06.131   293   354 I ThermalEngine: Sensor:pa_therm0:38000 mC
,09-09 13:41:06.340  3382  3636 I Icing   : Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,09-09 13:41:06.401  3382  3636 I Icing   : Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,09-09 13:41:07.042   838  1844 I ActivityManager: Process com.google.android.gms.unstable (pid 6379) has died
,09-09 13:41:07.061   838  1284 V AlarmManager: RTC_WAKEUP set : Alarm{3dab9945 type 0 when 1473421267057 com.google.android.googlequicksearchbox} when 1473421267057
,09-09 13:41:09.943  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-09 13:41:09.947  1375  1375 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-09 13:41:09.947  1375  1375 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-09 13:41:09.947  1375  1375 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-09 13:41:09.947  1375  1375 I [SystemUI]LGPowerUI: On Skip Timer : true
09-09 13:41:09.987  1375  1375 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 341
,09-09 13:41:09.987  1375  1375 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-09 13:41:09.988  1375  1375 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 341
,09-09 13:41:09.990   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:09.990   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:09.991   838  1311 D WifiController: battery changed pluggedType: 2
09-09 13:41:09.993  2007  3528 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-09 13:41:09.994  1802  1971 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-09 13:41:09.994  1802  1971 D LEDHandler: Battery Level Remaining: 100%
09-09 13:41:09.994  1802  1971 D LEDHandler: Battery Temp: 341, mChargingStatus=5, mChargingStop=false
09-09 13:41:09.995  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-09 13:41:09.995  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-09 13:41:09.996   489   489 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-09 13:41:09.996  1375  1375 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-09 13:41:11.136   293   354 I ThermalEngine: Sensor:pa_therm0:38000 mC
,09-09 13:41:11.758  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:11.759  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:11.759  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,09-09 13:41:12.759  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:12.759  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:12.759  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-09 13:41:13.761  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:13.761  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:13.761  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-09 13:41:14.763  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,09-09 13:41:14.763  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:14.763  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:15.173   838  1028 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-09 13:41:15.173   838  1028 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-09 13:41:15.173   838  1028 D sensors_hal_Time: tsOffsetIs: Apps: 132330950267; DSPS: 4434358; Offset : -3004105884
,09-09 13:41:15.764  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:15.765  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:15.765  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,09-09 13:41:16.140   293   354 I ThermalEngine: Sensor:pa_therm0:38000 mC
,09-09 13:41:16.442   838  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{d7184c1 type 2 when 133590 com.google.android.gms} when 133590
,09-09 13:41:16.472  1730  1730 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-09 13:41:16.682  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:41:16.709  3382  6750 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,09-09 13:41:16.709  3382  6750 D SchedPeriodicTask: Scheduled AdAttestation task.
09-09 13:41:16.766  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:16.767  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:16.767  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-09 13:41:17.233   838  1899 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6765 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,09-09 13:41:17.283   243   243 E lowmemorykiller: Error opening /proc/6538/oom_score_adj; errno=2
,09-09 13:41:17.322   838  1880 I ActivityManager: Process com.google.android.talk (pid 6538) has died
,09-09 13:41:17.356  6765  6765 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 13:41:17.357  6765  6765 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 13:41:17.413  6765  6765 I MultiDex: VM with version 2.1.0 has multidex support
09-09 13:41:17.413  6765  6765 I MultiDex: install
09-09 13:41:17.413  6765  6765 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-09 13:41:17.466  6765  6765 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 13:41:17.528  6765  6765 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-09 13:41:17.528  6765  6765 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1eefef64: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-09 13:41:17.529  6765  6765 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-09 13:41:17.531  6765  6765 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
09-09 13:41:17.531  6765  6765 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
09-09 13:41:17.545  6765  6765 D ChimeraCfgMgr: Reading stored module config
,09-09 13:41:17.657  6765  6780 I art     : Background sticky concurrent mark sweep GC freed 20245(1017KB) AllocSpace objects, 2(32KB) LOS objects, 6% free, 10MB/11MB, paused 13.856ms total 72.951ms
,09-09 13:41:17.689  1730  1730 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=c99a6701-aec8-4687-bec1-8092748aa472
,09-09 13:41:17.712  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:41:17.714  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-09 13:41:17.722  6765  6765 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
09-09 13:41:17.722  6765  6765 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
09-09 13:41:17.724  6765  6780 I art     : CheckpointMarkThreadRoots callback created = 0xb042d370
,09-09 13:41:17.742  6765  6786 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-09 13:41:17.754  6765  6780 I art     : CheckpointMarkThreadRoots callback created = 0xb042d360
,09-09 13:41:17.821   280  1322 D WVCdm   : Instantiating CDM.
,09-09 13:41:17.822   280   280 I WVCdm   : CdmEngine::OpenSession
09-09 13:41:17.822   280   280 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
09-09 13:41:17.872   280   280 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
09-09 13:41:17.873   280   280 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
09-09 13:41:17.873   280   280 W WVCdm   : L1 library not specified. Falling Back to L3
,09-09 13:41:17.927  6765  6782 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:17.927  6765  6782 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:41:17.927  6765  6782 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:17.927  6765  6782 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:17.928   276  1008 E BandwidthController: [LG DATA] No such appUid: 10006
09-09 13:41:17.928   276  1008 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-09 13:41:17.928   276  6793 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
09-09 13:41:17.928   276  6793 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:17.929   276  6793 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
09-09 13:41:17.929   276  6793 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:41:17.934  1730  2585 W GCoreFlp: No location to return for getLastLocation()
09-09 13:41:17.961   276  6793 D libc-netbsd: res_queryN name = xxxxx succeed
,09-09 13:41:17.962   280   280 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-09 13:41:17.962  6765  6782 I System.out: propertyValue:false
09-09 13:41:17.964   280  1599 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-09 13:41:17.964   280  1599 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-09 13:41:17.964   280  1599 I WVCdm   : CdmEngine::GenerateKeyRequest
09-09 13:41:17.972   280  1599 D WVCdm   : PrepareKeyRequest: nonce=3224060500
09-09 13:41:17.986  3382  6755 D UdcContextInitService: registered all accounts: true
,09-09 13:41:17.997  1730  2541 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 13:41:18.019  6765  6782 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:18.019  6765  6782 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:41:18.036  1730  2518 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-09 13:41:18.770  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:18.770  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:18.770  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,09-09 13:41:19.012  6798  6798 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=41 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-09 13:41:19.149  6798  6798 I dex2oat : dex2oat took 133.687ms (threads: 4)
,09-09 13:41:19.192  6765  6782 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:19.192  6765  6782 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:19.192  6765  6782 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:41:19.192  6765  6782 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:41:19.192  6765  6782 I Adreno-EGL: Remote Branch: 
09-09 13:41:19.192  6765  6782 I Adreno-EGL: Local Patches: 
09-09 13:41:19.192  6765  6782 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:41:19.303   838  1783 I ActivityManager: Process com.android.gallery3d (pid 6616) has died
,09-09 13:41:19.361  6765  6782 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:19.361  6765  6782 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:19.361  6765  6782 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:41:19.361  6765  6782 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:41:19.361  6765  6782 I Adreno-EGL: Remote Branch: 
09-09 13:41:19.361  6765  6782 I Adreno-EGL: Local Patches: 
09-09 13:41:19.361  6765  6782 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:41:19.421  6765  6782 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:19.421  6765  6782 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:19.421  6765  6782 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:41:19.421  6765  6782 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:41:19.421  6765  6782 I Adreno-EGL: Remote Branch: 
09-09 13:41:19.421  6765  6782 I Adreno-EGL: Local Patches: 
09-09 13:41:19.421  6765  6782 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:41:19.594  1730  6757 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:19.594  1730  6757 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:19.594  1730  6757 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:19.594  1730  6757 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:19.595   276  1008 E BandwidthController: [LG DATA] No such appUid: 10006
09-09 13:41:19.595   276  1008 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-09 13:41:19.595   276  6810 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
09-09 13:41:19.595   276  6810 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:19.596   276  6810 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
09-09 13:41:19.596   276  6810 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:41:19.596   276  6810 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:41:19.597  1730  6757 I System.out: propertyValue:false
,09-09 13:41:19.648  1730  6757 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:19.648  1730  6757 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:41:19.926  1730  6757 I art     : Explicit concurrent mark sweep GC freed 50856(2MB) AllocSpace objects, 16(254KB) LOS objects, 40% free, 14MB/24MB, paused 13.617ms total 121.597ms
,09-09 13:41:20.062  1730  2518 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:41:20.070  1730  2518 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
09-09 13:41:20.073  1730  2518 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-09 13:41:18.141+0200, stopTime=2016-09-09 13:41:20.071+0200, duration=1930ms
,09-09 13:41:20.123  3984  4180 I art     : Explicit concurrent mark sweep GC freed 1990(70KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.015ms total 27.438ms
,09-09 13:41:20.127   838  1801 I art     : Explicit concurrent mark sweep GC freed 29809(1649KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 9.111ms total 184.848ms
,09-09 13:41:20.175  1730  6824 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:20.176  1730  6824 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:20.176  1730  6824 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:20.176  1730  6824 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:20.177   276  1008 E BandwidthController: [LG DATA] No such appUid: 10006
09-09 13:41:20.177   276  1008 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-09 13:41:20.177   276  6827 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
09-09 13:41:20.177   276  6827 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:20.177   276  6827 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
09-09 13:41:20.177   276  6827 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:41:20.178   276  6827 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:41:20.180  1730  6824 I System.out: propertyValue:false
,09-09 13:41:20.317   280  1296 I WVCdm   : CdmEngine::CloseSession
,09-09 13:41:20.322   280  1296 I WVCdm   : L3 Terminate.
09-09 13:41:20.568  1730  2518 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-09 13:41:20.748  1730  6834 E CommitToConfigurationOperation: Malformed snapshot token (size): 
09-09 13:41:20.750  1730  6832 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-09 13:41:20.775  1730  6834 E CommitToConfigurationOperation: Malformed snapshot token (size): 
09-09 13:41:20.776  1730  6832 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-09 13:41:20.801  1730  6834 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-09 13:41:20.802  1730  6832 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-09 13:41:20.802  1730  6832 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
09-09 13:41:20.806  1730  6832 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
09-09 13:41:20.845   838  2110 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:41:20.912  1730  6832 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:20.912  1730  6832 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:41:20.912  1730  6832 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:20.912  1730  6832 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:20.912   276  1008 E BandwidthController: [LG DATA] No such appUid: 10006
09-09 13:41:20.912   276  1008 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-09 13:41:20.913   276  6835 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
09-09 13:41:20.913   276  6835 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:20.913   276  6835 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
09-09 13:41:20.914   276  6835 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:41:20.914   276  6835 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:41:20.915  1730  6832 I System.out: propertyValue:false
09-09 13:41:21.145   293   354 I ThermalEngine: Sensor:pa_therm0:38000 mC
,09-09 13:41:21.219   838  1819 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:41:21.447   838  1924 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:41:21.681   838  2110 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:41:21.899   838   867 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:41:22.493  1730  2518 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,09-09 13:41:22.716  6502  6657 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 13:41:22.716  6502  6657 I jxcore-log: 
,09-09 13:41:22.720  6502  6657 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 13:41:22.720  6502  6657 I jxcore-log: 
09-09 13:41:22.724  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:22.725  6502  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:22.725  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:22.725  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:22.725  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:22.725  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:22.725  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:22.725  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:22.725  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:22.732  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
,09-09 13:41:22.733  6502  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:22.740  6502  6657 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 13:41:22.740  6502  6657 I jxcore-log: 
09-09 13:41:22.742  6502  6657 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 13:41:22.742  6502  6657 I jxcore-log: 
09-09 13:41:23.567  6502  6657 I jxcore-log: Unit Test app is loaded
09-09 13:41:23.567  6502  6657 I jxcore-log: 
,09-09 13:41:23.592  6502  6657 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:23.592  6502  6657 I jxcore-log: 
,09-09 13:41:23.602  6502  6502 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-09 13:41:23.608  6502  6657 D executeNativeTests: Running unit tests
,09-09 13:41:23.609  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:23.609  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa07f1f added. We now have 2 listener(s)
09-09 13:41:23.609   838  1359 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:23.612  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-09 13:41:23.612  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:23.612  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:23.612  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:23.612  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e0bc26c added. We now have 2 listener(s)
09-09 13:41:23.612  6502  6657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:23.613  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:23.614  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:23.616  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:23.617  6502  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:23.617  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:23.617  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:23.617  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:23.617  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:23.617  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:23.617  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:23.617  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:23.618  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:23.618  6502  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:23.618  6502  6657 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:23.619  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:23.621  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:23.781  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,09-09 13:41:23.781  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:23.782  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:26.151   293   354 I ThermalEngine: Sensor:pa_therm0:38000 mC
,09-09 13:41:28.656   838  1034 I PowerManagerService: ALS enabled for SRE
,09-09 13:41:28.661   838  1034 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (25820 ms ago)
09-09 13:41:28.742   838  1348 D qdlights: set_light_backlight: 253
,09-09 13:41:28.746   838  1348 D qdlights: set_light_backlight: 249
09-09 13:41:28.763   838  1348 D qdlights: set_light_backlight: 246
,09-09 13:41:28.780   838  1348 D qdlights: set_light_backlight: 243
,09-09 13:41:28.797   838  1348 D qdlights: set_light_backlight: 239
,09-09 13:41:28.813   838  1348 D qdlights: set_light_backlight: 236
,09-09 13:41:28.830   838  1348 D qdlights: set_light_backlight: 233
,09-09 13:41:28.847   838  1348 D qdlights: set_light_backlight: 229
,09-09 13:41:28.863   838  1348 D qdlights: set_light_backlight: 226
,09-09 13:41:28.879   838  1348 D qdlights: set_light_backlight: 223
,09-09 13:41:28.897   838  1348 D qdlights: set_light_backlight: 219
,09-09 13:41:28.913   838  1348 D qdlights: set_light_backlight: 216
,09-09 13:41:28.930   838  1348 D qdlights: set_light_backlight: 213
,09-09 13:41:28.946   838  1348 D qdlights: set_light_backlight: 209
,09-09 13:41:28.963   838  1348 D qdlights: set_light_backlight: 206
,09-09 13:41:28.981   838  1348 D qdlights: set_light_backlight: 203
,09-09 13:41:28.997   838  1348 D qdlights: set_light_backlight: 199
,09-09 13:41:29.013   838  1348 D qdlights: set_light_backlight: 196
,09-09 13:41:29.030   838  1348 D qdlights: set_light_backlight: 193
,09-09 13:41:29.047   838  1348 D qdlights: set_light_backlight: 189
,09-09 13:41:29.063   838  1348 D qdlights: set_light_backlight: 186
,09-09 13:41:29.080   838  1348 D qdlights: set_light_backlight: 183
,09-09 13:41:29.097   838  1348 D qdlights: set_light_backlight: 179
,09-09 13:41:29.113   838  1348 D qdlights: set_light_backlight: 176
,09-09 13:41:29.130   838  1348 D qdlights: set_light_backlight: 173
,09-09 13:41:29.147   838  1348 D qdlights: set_light_backlight: 169
,09-09 13:41:29.163   838  1348 D qdlights: set_light_backlight: 166
,09-09 13:41:29.180   838  1348 D qdlights: set_light_backlight: 163
,09-09 13:41:29.197   838  1348 D qdlights: set_light_backlight: 159
,09-09 13:41:29.213   838  1348 D qdlights: set_light_backlight: 156
,09-09 13:41:29.230   838  1348 D qdlights: set_light_backlight: 153
,09-09 13:41:29.247   838  1348 D qdlights: set_light_backlight: 149
,09-09 13:41:29.263   838  1348 D qdlights: set_light_backlight: 146
,09-09 13:41:29.280   838  1348 D qdlights: set_light_backlight: 143
,09-09 13:41:29.297   838  1348 D qdlights: set_light_backlight: 139
,09-09 13:41:29.313   838  1348 D qdlights: set_light_backlight: 136
,09-09 13:41:29.330   838  1348 D qdlights: set_light_backlight: 133
,09-09 13:41:29.347   838  1348 D qdlights: set_light_backlight: 129
,09-09 13:41:29.363   838  1348 D qdlights: set_light_backlight: 126
,09-09 13:41:29.380   838  1348 D qdlights: set_light_backlight: 123
,09-09 13:41:29.397   838  1348 D qdlights: set_light_backlight: 119
,09-09 13:41:29.413   838  1348 D qdlights: set_light_backlight: 116
,09-09 13:41:29.430   838  1348 D qdlights: set_light_backlight: 113
,09-09 13:41:29.447   838  1348 D qdlights: set_light_backlight: 109
,09-09 13:41:29.463   838  1348 D qdlights: set_light_backlight: 106
,09-09 13:41:29.480   838  1348 D qdlights: set_light_backlight: 103
,09-09 13:41:29.497   838  1348 D qdlights: set_light_backlight: 99
,09-09 13:41:29.513   838  1348 D qdlights: set_light_backlight: 96
,09-09 13:41:29.530   838  1348 D qdlights: set_light_backlight: 93
,09-09 13:41:29.547   838  1348 D qdlights: set_light_backlight: 89
,09-09 13:41:29.563   838  1348 D qdlights: set_light_backlight: 86
,09-09 13:41:29.580   838  1348 D qdlights: set_light_backlight: 83
,09-09 13:41:29.596   838  1348 D qdlights: set_light_backlight: 79
,09-09 13:41:29.613   838  1348 D qdlights: set_light_backlight: 76
,09-09 13:41:29.629   838  1348 D qdlights: set_light_backlight: 73
,09-09 13:41:29.646   838  1348 D qdlights: set_light_backlight: 69
,09-09 13:41:29.663   838  1348 D qdlights: set_light_backlight: 66
,09-09 13:41:29.679   838  1348 D qdlights: set_light_backlight: 63
,09-09 13:41:29.696   838  1348 D qdlights: set_light_backlight: 59
,09-09 13:41:29.712   838  1348 D qdlights: set_light_backlight: 56
,09-09 13:41:29.729   838  1348 D qdlights: set_light_backlight: 53
,09-09 13:41:29.746   838  1348 D qdlights: set_light_backlight: 49
,09-09 13:41:29.763   838  1348 D qdlights: set_light_backlight: 46
,09-09 13:41:29.779   838  1348 D qdlights: set_light_backlight: 43
,09-09 13:41:29.796   838  1348 D qdlights: set_light_backlight: 39
,09-09 13:41:29.813   838  1348 D qdlights: set_light_backlight: 36
,09-09 13:41:29.829   838  1348 D qdlights: set_light_backlight: 33
,09-09 13:41:29.846   838  1348 D qdlights: set_light_backlight: 29
,09-09 13:41:29.863   838  1348 D qdlights: set_light_backlight: 26
,09-09 13:41:29.879   838  1348 D qdlights: set_light_backlight: 23
,09-09 13:41:29.896   838  1348 D qdlights: set_light_backlight: 19
,09-09 13:41:29.913   838  1348 D qdlights: set_light_backlight: 16
,09-09 13:41:29.929   838  1348 D qdlights: set_light_backlight: 13
,09-09 13:41:29.947   838  1348 D qdlights: set_light_backlight: 10
,09-09 13:41:31.156   293   354 I ThermalEngine: Sensor:pa_therm0:38000 mC
,09-09 13:41:33.833  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:33.834  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a added. We now have 3 listener(s)
,09-09 13:41:33.834   838  1880 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:33.836  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-09 13:41:33.836  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:33.836  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:33.836  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:33.836  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b added. We now have 3 listener(s)
09-09 13:41:33.836  6502  6657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:33.837  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:33.839  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:33.840  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:33.841  6502  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:33.841  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:33.841  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:33.841  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:33.841  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:33.841  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:33.841  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:33.841  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:33.842  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:33.842  6502  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:33.842  6502  6657 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:33.844  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:33.845  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:33.846  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:33.855  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:41:33.856  6502  6657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:33.856  6502  6657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:33.856  6502  6657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:41:33.862  6502  6657 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-09 13:41:33.862  6502  6657 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 13:41:33.862  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:41:33.862  6502  6657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:33.862  6502  6657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:33.862  6502  6657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:33.867  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:33.867  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:33.867  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:33.868  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:33.868  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a removed from the list
09-09 13:41:33.868  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:33.868  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b removed from the list
09-09 13:41:33.868  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:33.868  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:33.877  6502  6657 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-09 13:41:33.877  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:33.877  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:33.877  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:33.878  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a not in the list
09-09 13:41:33.878  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:33.878  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b not in the list
09-09 13:41:33.878  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:33.878  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:33.878  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.Co,nnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:41:33.884  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:41:33.885  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:41:33.885  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:41:33.885  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:41:33.885  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:41:33.885  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-09 13:41:33.885  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:41:33.885  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:33.885  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:33.885  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:33.885  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a not in the list
09-09 13:41:33.885  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:33.885  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b not in the list
,09-09 13:41:33.885  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:33.885  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:33.885  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:33.886  6502  6657 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 13:41:33.887  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:33.889  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:33.890  6502  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:33.890  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:33.890  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:33.890  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:33.890  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:33.890  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:33.890  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:33.890  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:33.891  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
,09-09 13:41:33.892  6502  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-09 13:41:33.892  6502  6657 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:33.893  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:33.895  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:33.896  6502  6657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:41:33.896  6502  6657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:41:33.897  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:41:33.897  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:33.897  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:33.906  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:41:33.906   838  1801 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 13:41:33.918  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
,09-09 13:41:33.919  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:33.923  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:41:33.930  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
,09-09 13:41:33.932  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 13:41:33.934  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:33.935  6502  6657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-09 13:41:33.936  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:33.937  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:33.939  6502  6657 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-09 13:41:33.939  6502  6657 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:41:33.940  6502  6657 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-09 13:41:33.940  6502  6657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:41:33.941  6502  6657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:41:33.942  6502  6657 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 13:41:33.944  6502  6657 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-09 13:41:33.944  6502  6657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:33.944  6502  6657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:41:33.944  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:41:33.944  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:33.944  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:33.947  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:33.947  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:33.947  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:33.948  6502  6657 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:41:33.948  6502  6657 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:41:33.949  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:33.949  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:33.949  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:33.949  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a not in the list
,09-09 13:41:33.949  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:33.949  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b not in the list
09-09 13:41:33.949  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:33.949  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:33.950  6502  6657 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 13:41:33.951  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:33.953  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:33.953  6502  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:33.953  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:33.953  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:33.953  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:33.953  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:33.953  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:33.953  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:33.953  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:33.954  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:33.954  6502  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:33.955  6502  6657 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:33.957  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:33.958  6502  6657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:33.958  6502  6657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:41:33.958  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:41:33.958  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:33.958  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:33.958  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:33.961  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:33.961  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:33.962  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:33.963  6502  6657 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:41:33.963  6502  6657 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:41:33.963  6502  6657 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-09 13:41:33.963  6502  6657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:41:33.963  6502  6657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:41:33.966  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:33.966  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:33.966  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:33.967  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a not in the list
09-09 13:41:33.967  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:33.967  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b not in the list
09-09 13:41:33.967  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:33.967  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:33.968  6502  6657 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 13:41:33.968  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:33.968  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:33.968  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:33.968  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a not in the list
09-09 13:41:33.968  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:33.968  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b not in the list
09-09 13:41:33.968  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:33.968  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:33.968  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:33.969  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:41:33.969  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:33.969  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:33.969  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:33.970  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a not in the list
09-09 13:41:33.970  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:33.970  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b not in the list
09-09 13:41:33.970  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:33.970  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:33.970  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:33.970  6502  6657 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 13:41:33.971  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:33.971  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:33.971  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:33.971  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a not in the list
09-09 13:41:33.971  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:33.971  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b not in the list
09-09 13:41:33.971  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:33.971  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetooth,Manager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:33.971  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:33.972  6502  6657 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 13:41:33.972  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:33.972  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:33.972  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:33.972  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a not in the list
09-09 13:41:33.972  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:33.972  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b not in the list
09-09 13:41:33.972  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:33.972  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:33.972  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:33.972  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:41:33.974  6502  6657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:33.974  6502  6657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:33.974  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:41:33.974  6502  6657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:33.974  6502  6657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:33.975  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:41:33.975  6502  6657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:33.975  6502  6657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:33.975  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:33.975  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:33.975  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:33.975  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a not in the list
09-09 13:41:33.975  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:33.975  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b not in the list
09-09 13:41:33.975  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:33.975  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:33.975  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:33.976  6502  6657 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:33.976  6502  6657 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:41:33.976  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 13:41:33.979  6502  6657 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:33.979  6502  6657 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:41:33.980  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:41:33.981  6502  6657 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 13:41:33.981  6502  6657 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:41:33.981  6502  6657 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 13:41:33.981  6502  6657 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:33.981  6502  6657 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:41:33.981  6502  6657 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 13:41:33.981  6502  6657 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:33.981  6502  6657 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:41:33.981  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 13:41:34.001  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 13:41:34.003  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 13:41:34.003  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 13:41:34.006  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 13:41:34.006  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 13:41:34.006  6502  6657 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 13:41:34.006  6502  6657 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:34.006  6502  6657 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 13:41:34.007  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:34.007  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.007  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.007  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 13:41:34.008  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a not in the list
09-09 13:41:34.008  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:34.008  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b not in the list
09-09 13:41:34.008  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:34.008  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.008  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.009  6502  6657 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 13:41:34.009  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:34.009  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.009  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.009  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a not in the list
09-09 13:41:34.009  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:34.009  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b not in the list
09-09 13:41:34.009  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:34.009  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.009  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.010  6502  6657 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 13:41:34.010  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:34.010  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.010  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.010  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a not in the list
09-09 13:41:34.010  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:34.011  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b not in the list
09-09 13:41:34.011  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:34.011  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.011  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.011  6502  6657 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 13:41:34.011  6502  6657 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 13:41:34.013  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:41:34.013  6502  6657 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 13:41:34.013  6502  6657 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:41:34.013  6502  6657 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 13:41:34.013  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-09 13:41:34.015  6502  6657 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 13:41:34.017  6502  6876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 872
09-09 13:41:34.017  6502  6657 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:41:34.017  6502  6657 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:41:34.017  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:41:34.017  6502  6657 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 13:41:34.019  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:34.019  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.019  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.019  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a not in the list
09-09 13:41:34.019  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:34.019  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b not in the list
09-09 13:41:34.019  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:34.019  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.019  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.020  6502  6875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 872)
09-09 13:41:34.020  6502  6875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 872)
09-09 13:41:34.021  6502  6657 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 13:41:34.022  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:34.025  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:34.026  6502  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:34.026  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:34.026  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:34.026  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:34.026  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:34.026  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:34.026  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:34.026  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:34.028  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:34.029  6502  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:34.029  6502  6657 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:34.030  6502  6657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:34.030  6502  6657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:41:34.030  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:41:34.030  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:34.030  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:34.031  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:34.032  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:34.034  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:34.034  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:34.035  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:34.036  6502  6657 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:41:34.036  6502  6657 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:41:34.036  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:34.036  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.036  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:34.036  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a not in the list
09-09 13:41:34.037  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:34.037  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b not in the list
09-09 13:41:34.037  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:34.037  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.039  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:34.040  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.040  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.040  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a not in the list
09-09 13:41:34.040  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:34.040  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b not in the list
09-09 13:41:34.040  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:34.040  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.040  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.041  6502  6657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:34.042  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:34.042  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:41:34.043  6502  6657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:41:34.043  6502  6657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:41:34.044  6502  6502 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:41:34.044  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:34.044  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:41:34.045  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:34.045  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:34.045  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:34.046  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:41:34.046  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.046  6502  6657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:34.046  6502  6502 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:41:34.046  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a not in the list
09-09 13:41:34.046  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:34.046  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:34.046  6502  6657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:34.046  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:34.047  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:41:34.050  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:34.050   838  1819 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:34.052  6502  6878 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:41:34.054  6502  6657 D BluetoothLeScanner: could not find callback wrapper
09-09 13:41:34.054  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:41:34.054  6502  6657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:41:34.054  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.054  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.056  6502  6657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:34.056  6502  6502 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:34.056  6502  6502 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:34.056  6502  6502 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:34.057  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b not in the list
09-09 13:41:34.057  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:34.057  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.057  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.058  6502  6657 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 13:41:34.058  6502  6657 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 13:41:34.058  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:41:34.058  6502  6657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:34.058  6502  6657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:34.059  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:34.059  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:34.059  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.059  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a not in the list
09-09 13:41:34.059  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:34.059  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b not in the list
09-09 13:41:34.059  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:34.059  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.059  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.060   838  1347 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:34.063   838  1359 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:34.064   838  2176 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:34.064  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:34.064  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.064  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.064  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a not in the list
09-09 13:41:34.064  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:34.064  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b not in the list
09-09 13:41:34.064  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:34.064  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.064  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.066  2007  2056 I bt-btif : BTA_JvCreateRecordByUser
09-09 13:41:34.066  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:34.066  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.066  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.066  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d88fc7a not in the list
09-09 13:41:34.066  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:34.066  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309cdc2b not in the list
09-09 13:41:34.066  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:34.067  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.067  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager,: release: 2 listener(s) left
09-09 13:41:34.068  6502  6657 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 13:41:34.068  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:41:34.068  6502  6657 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 13:41:34.068  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:41:34.068  6502  6657 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 13:41:34.068  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:41:34.070  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:41:34.070  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 13:41:34.070  6502  6657 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 13:41:34.070  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:41:34.071  6502  6657 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 13:41:34.071  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:41:34.071  6502  6657 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 13:41:34.071  6502  6657 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 13:41:34.071  6502  6657 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-09 13:41:34.071  6502  6657 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 13:41:34.072  6502  6657 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 13:41:34.072  6502  6657 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 13:41:34.072  6502  6657 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 13:41:34.072  6502  6657 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 13:41:34.075  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:34.075  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37581459 added. We now have 3 listener(s)
09-09 13:41:34.075   838  1783 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:34.079  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-09 13:41:34.079  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:34.079  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:34.079  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:34.079  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c89f81e added. We now have 3 listener(s)
09-09 13:41:34.079  6502  6657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:34.080  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:34.080  2007  2056 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=87 mFd=85
09-09 13:41:34.080  2007  3608 I bt-btif : BTA_JvRfcommStartServer
09-09 13:41:34.082  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:34.084  2007  3670 I bt-btif : BTA_JvDeleteRecord
09-09 13:41:34.084  2007  3670 I bt-btif : BTA_JvRfcommStopServer
09-09 13:41:34.085  6502  6878 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:34.085  6502  6878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:41:34.085  6502  6878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:41:34.086  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:34.087  6502  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:34.087  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:34.087  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:34.087  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:34.087  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:34.087  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:34.087  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:34.087  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:34.087  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:34.088  6502  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:34.088  6502  6657 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:34.089  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:34.091  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:34.091  6502  6502 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:41:34.092  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:34.097  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:34.097  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.097  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:34.097  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:34.097  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37581459 removed from the list
09-09 13:41:34.097  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:34.097  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c89f81e removed from the list
09-09 13:41:34.097  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:34.097  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:34.102  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:34.102  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26b0e6cc added. We now have 3 listener(s)
09-09 13:41:34.103   838  2176 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:34.105  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-09 13:41:34.105  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:34.105  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:34.105  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:34.105  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d6c9d15 added. We now have 3 listener(s)
09-09 13:41:34.105  6502  6657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:34.105  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:34.107  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:34.109  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:34.110  6502  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:34.110  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:34.110  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:34.110  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:34.110  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:34.110  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:34.110  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:34.110  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:34.110  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:34.111  6502  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:34.111  6502  6657 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:34.111  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:34.112  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:34.112  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:34.112  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:34.112  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26b0e6cc removed from the list
09-0,9 13:41:34.112  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:34.112  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d6c9d15 removed from the list
09-09 13:41:34.112  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:34.116  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:34.117  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:34.117  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:34.118  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:34.118  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d31261b added. We now have 3 listener(s)
09-09 13:41:34.119   838  2110 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:34.121  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-09 13:41:34.121  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:34.121  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:34.121  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:34.121  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b6ba3b8 added. We now have 3 listener(s)
09-09 13:41:34.121  6502  6657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:34.121  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:34.123  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:34.125  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
,09-09 13:41:34.127  6502  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:34.127  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:34.127  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:34.127  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:34.127  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:34.127  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:34.127  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:34.127  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:34.128  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:34.129  6502  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:34.129  6502  6657 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:34.131  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:34.132  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:34.134   838  2110 D WifiServiceImplEx: setWifiEnabled: false pid=6502, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
09-09 13:41:34.138   838  2110 D WifiService: setWifiEnabled: false pid=6502, uid=10030
,09-09 13:41:34.170   838  1306 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 13:41:34.173   838   838 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-09 13:41:34.174   838   838 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:41:34.175   838  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:41:34.177   838   838 D Ulp_jni : JNI:system_update. Event-4
09-09 13:41:34.195   838  1305 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:34.196   838  1305 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:34.201   838  2931 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:34.210   276  1013 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:41:34.213   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 7
09-09 13:41:34.236  1730  4303 V NativeCrypto: Read error: ssl=0xaaf5ec00: I/O error during system call, Connection timed out
,09-09 13:41:34.239  1730  4303 V NativeCrypto: SSL shutdown failed: ssl=0xaaf5ec00: I/O error during system call, Broken pipe
09-09 13:41:34.240   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 10
09-09 13:41:34.242   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 7
09-09 13:41:34.243   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:34.243   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:34.247   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:34.247   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:34.254  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,09-09 13:41:34.255   838  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 13:41:34.256   838  1312 D ConnectivityService: ignoring duplicate network state non-change
09-09 13:41:34.260   838  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-09 13:41:34.263   838   838 D WifiHS20: hidePasspointNotification off =false
09-09 13:41:34.263   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:34.264   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:34.264   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:41:34.266  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:41:34.268  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:34.259 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:34.269  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:41:34.271   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:34.271   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:34.276  1730  4303 E GCM     : Wifi connection closed with errorCode 20
09-09 13:41:34.278   838  1775 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
09-09 13:41:34.279  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:34.279  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:34.279  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:34.280   838  2927 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:34.280   838  2927 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:34.281   838  2927 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,09-09 13:41:34.286  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:34.291  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:34.291  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
,09-09 13:41:34.298  1802  2131 D WifiServiceExtension: isInternetCheckAvailable return false
09-09 13:41:34.316   838   892 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6893 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-09 13:41:34.319   838   838 D WifiHS20: hidePasspointNotification off =false
09-09 13:41:34.319   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:34.319   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:34.319   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:41:34.325   838   838 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 13:41:34.325   838  1328 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:34.326   838  1305 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:34.326   838  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:34.327   838   838 D RttService: SCAN_AVAILABLE : 1
09-09 13:41:34.328   838  1329 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:34.333   838  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 13:41:34.333  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:34.334  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:34.334 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:34.335  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:41:34.335  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:34.337   838  1305 D LGWifiP2pService: P2pDisablingState
09-09 13:41:34.337  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:34.338  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:34.338  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:34.338  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:34.338  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:34.338  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:34.339  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
,09-09 13:41:34.342  1802  1802 D WfdsService: WifiP2pState is changed : false
09-09 13:41:34.344  1802  2129 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-09 13:41:34.346  1802  2129 D WfdsJNI : doCommand: P2P_STOP_FIND
09-09 13:41:34.350   838  1305 D LGWifiP2pService: P2pDisablingState{ when=-20ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:34.350   838  1305 D LGWifiP2pService: p2p socket connection lost
,09-09 13:41:34.350   838  1305 D LGWifiP2pService: P2pDisabledState
09-09 13:41:34.350  1802  2129 D WfdsService: Set the WFDS Monitor: false
09-09 13:41:34.351   838  1305 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:34.351   838  1305 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:34.365  1802  2129 D WfdsMonitor: WFDS Monitor is stopped
09-09 13:41:34.365  1802  2834 D CtrlSupplicant: Received on exit socket, terminate
,09-09 13:41:34.365  1802  2834 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-09 13:41:34.367  1802  2129 D WfdsService: STATE : WfdsDisabledState - enter
09-09 13:41:34.367  1802  2129 D WfdsService: WFDS: Scanner is paused
09-09 13:41:34.367  1802  2129 D WfdsDiscoveryStore: Clear Discovery Method Map: ScanAlwaysMode false
09-09 13:41:34.368  1802  2834 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-09 13:41:34.368  1802  2834 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-09 13:41:34.369  1802  2127 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-09 13:41:34.376   276  1013 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:41:34.377   838  1312 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-09 13:41:34.377   838  1312 D DSQN    : disableDataServiceNotify
09-09 13:41:34.379   838  1312 D DSQN    : stop dsqn bin
,09-09 13:41:34.385   838   838 D WifiHS20: hidePasspointNotification off =false
09-09 13:41:34.386  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:34.386   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:34.386   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:34.386   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:41:34.386  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:34.387  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:34.386 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:34.387  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:41:34.389  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:34.389  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:34.389 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:34.389  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:41:34.391  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:34.391  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:34.391  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:34.391  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:34.391  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:34.391  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:34.392   838   838 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
,09-09 13:41:34.395   838   838 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:34.396   838   838 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-09 13:41:34.396  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:34.396  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:34.396  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:34.396  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:34.396  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-09 13:41:34.397  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:34.397  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:34.397  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:34.397  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:34.397  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:34.397  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:34.397  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:34.397  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:34.398  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:34.399  6502  6502 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:34.401  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:34.402  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:34.402  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:34.402  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:34.402  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:34.402  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:34.402  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:34.402  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:34.402  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:34.403  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:34.403   838  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-09 13:41:34.404   838  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:34.404  6502  6502 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi,: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:34.404   838  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:34.408  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:34.409  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:34.409  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:34.409  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:34.409  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:34.409  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:34.409  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:34.409  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:34.409  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:34.410  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:34.411  6502  6502 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:34.414   838  1312 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:34.414   838  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:34.414  1375  1728 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 13:41:34.415   838  1312 D ConnectivityService: sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:34.415   838  1312 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-09 13:41:34.415   838  2927 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:34.415   838  2927 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:34.415   838  2927 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-09 13:41:34.416  3382  3629 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-09 13:41:34.418   838  1312 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-09 13:41:34.419   838  1312 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-09 13:41:34.419   838  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:41:34.419   838  1312 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:34.419   838  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:41:34.420   838  1304 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 13:41:34.421   838  1312 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:34.422  1837  1837 W QCNEJ   : |CORE| No family connected
09-09 13:41:34.422   838  1312 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:34.422   838  1312 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:34.423   838  1304 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 13:41:34.423   838  1017 D Tethering: MasterInitialState.processMessage what=3
09-09 13:41:34.423   838  1017 D Tethering: MasterInitialState.processMessage what=3
09-09 13:41:34.424   838  1306 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:34.424   838  1306 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:34.424   838  1312 D NetworkManagementService: Removing idletimer
09-09 13:41:34.425  1837  1837 W QCNEJ   : |CORE| No family connected
09-09 13:41:34.425  1837  1837 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
09-09 13:41:34.427  1837  1837 I QCNEJ   : |CORE| sendDefaultNwMsg: default = -1
,09-09 13:41:34.431   838  2931 D DhcpStateMachine: StoppedState
09-09 13:41:34.431   838  2931 D DhcpStateMachine: StoppedState{ when=-79ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:34.438   838  1312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:34.441  1748  1748 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:34.448  1748  1748 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
09-09 13:41:34.459  1375  1375 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-09 13:41:34.465  1375  1375 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
09-09 13:41:34.467  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:34.467  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:34.467  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:34.468  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:34.468  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:34.468  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:34.480  1375  1375 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:41:34.481  1375  1375 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
,09-09 13:41:34.482   276  1006 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
09-09 13:41:34.483   276  1006 I Netd    : M: Get netlink event, ifname: p2p0 action: 5
09-09 13:41:34.483   276  1006 I Netd    : M: Get netlink event, ifname: p2p0 action: 10
09-09 13:41:34.484  2665  2665 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-09 13:41:34.484  2665  2665 I wpa_supplicant: monitor socket send errors count : 1
09-09 13:41:34.484  2665  2665 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1802-2\x00 that cannot receive messages
09-09 13:41:34.484   276  1006 I Netd    : M: Get netlink event, ifname: p2p0 action: 7
09-09 13:41:34.484   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:34.485   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:34.485  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:34.485  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:34.485  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:34.487  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:34.487  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:34.487  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:34.499  2665  2665 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 13:41:34.501  2665  2665 W wpa_supplicant: USIM:  scard_deinit function
09-09 13:41:34.509   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:34.509   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:41:34.509   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:34.509   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:41:34.557  6502  6502 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:41:34.586  6893  6893 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:34.587  6893  6893 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-09 13:41:34.587  6893  6893 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:41:34.588  6893  6893 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 13:41:34.589  6893  6893 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-09 13:41:34.592   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:41:34.602   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 5
,09-09 13:41:34.603  2665  2665 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-09 13:41:34.603   838  1017 D Tethering: InitialState.processMessage what=4
09-09 13:41:34.607   838  1017 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-09 13:41:34.660   838  1801 D WifiServiceImplEx: setWifiEnabled: true pid=6502, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
,09-09 13:41:34.666   838  1801 D WifiService: setWifiEnabled: true pid=6502, uid=10030
09-09 13:41:34.674   838  1311 D WifiController: WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 492ms
,09-09 13:41:34.674   838   838 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:41:34.674   838   838 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:41:34.674   838   838 D Ulp_jni : JNI:system_update. Event-4
09-09 13:41:34.695  6893  6893 I IndexDatabaseHelper: Using schema version: 115
,09-09 13:41:34.698  6893  6893 I IndexDatabaseHelper: Index is fine
09-09 13:41:34.707   838  1306 D WifiOffDelayIfNotUsed: stopMonitoring
09-09 13:41:34.707  1802  1802 D WfdsService: Supplicant Connection state is changed : false
09-09 13:41:34.707  1802  2129 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-09 13:41:34.707  1802  2129 D WfdsService: Set the WFDS Monitor: false
09-09 13:41:34.707  1802  2129 D WfdsMonitor: WFDS Monitor is stopped
09-09 13:41:34.711  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:34.711  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:34.711 DNS addrs= 0.0.0.0, 0.0.0.0, 
,09-09 13:41:34.711  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:41:34.712   838   838 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-09 13:41:34.713   838  1310 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-09 13:41:34.713   838  1310 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-09 13:41:34.714  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:34.716  1730  2622 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:34.716  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:34.716  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:34.716  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:34.716  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:34.716  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:34.716  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:34.716  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:34.716  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:34.716  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:34.716  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:34.717  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:34.717  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-09 13:41:34.718  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:34.719  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:34.719  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:34.719  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:34.719  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:34.719  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:34.719  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:34.719  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:34.719  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:34.721  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:34.721  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:34.721  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:34.721  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple adverti,sement supported: NOT_SUPPORTED
09-09 13:41:34.721  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:34.721  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:34.721  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:34.721  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:34.721  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:34.840  6893  6893 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:34.879  6893  6893 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:41:34.944   838  1924 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6918 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-09 13:41:35.002   838  1801 I ActivityManager: Process com.android.contacts (pid 6640) has died
,09-09 13:41:35.078  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-09 13:41:35.081  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:41:35.081  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:41:35.126   838  1347 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6941 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-09 13:41:35.172   838  1311 D WifiController: DEFERRED_TOGGLE handled
,09-09 13:41:35.173   838  1306 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-09 13:41:35.174   838  1306 E WifiHW  : Wifi MAC Address = a0:39:f7:70:12:80
09-09 13:41:35.175   838  1028 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-09 13:41:35.175   838  1028 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-09 13:41:35.175   838  1028 D sensors_hal_Time: tsOffsetIs: Apps: 152332634894; DSPS: 5089773; Offset : -3004100349
09-09 13:41:35.175   838  1306 E WifiHW  : wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
09-09 13:41:35.175   838  1306 E WifiHW  : band=b
09-09 13:41:35.175   838  1306 E WifiHW  : ": cur_etheraddr=a0:39:f7:70:12:80
09-09 13:41:35.176   276  1013 D SoftapController: Softap fwReload - Ok
09-09 13:41:35.177   838  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:35.177   838  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:35.177   276  1013 D CommandListener: Setting iface cfg
09-09 13:41:35.177   276  1013 D CommandListener: Trying to bring down wlan0
09-09 13:41:35.178   276  1013 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:41:35.180   838  1306 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-09 13:41:35.199  6941  6941 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 13:41:35.217  6959  6959 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 13:41:35.274  6959  6959 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 13:41:35.274  6959  6959 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-09 13:41:35.281   838  1306 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-09 13:41:35.283  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:35.283  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:35.283 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:35.283  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,09-09 13:41:35.285  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:35.286   838   838 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-09 13:41:35.287  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:35.288  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:35.290  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:35.290  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:35.290  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:35.290  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-09 13:41:35.296   838  1017 D BluetoothManagerService: Message: 20
,09-09 13:41:35.296   838  1017 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10cda455:true
,09-09 13:41:35.305  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:35.306  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:35.455   838  1819 I ActivityManager: Process com.android.vending (pid 6229) has died
,09-09 13:41:35.460  6893  6893 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:41:35.463  6893  6893 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:35.467  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 13:41:35.467  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:41:35.467  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:35.532   838  1347 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6963 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-09 13:41:35.589  6963  6963 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 13:41:35.646   838  1034 I PowerManagerService: ALS enabled for SRE
09-09 13:41:35.646   838  1034 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (32804 ms ago)
09-09 13:41:35.647   838  1034 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-09 13:41:35.661   838  1034 I PowerManagerService: ALS enabled for SRE
09-09 13:41:35.661   838  1034 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (32819 ms ago)
,09-09 13:41:35.706   838  1034 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,09-09 13:41:35.710   838  1034 I PowerManagerService: Sleeping (uid 1000)...
09-09 13:41:35.710   838  1034 D LPWGController: [updateScreenState] screen on = false
09-09 13:41:35.712   838  1034 D LPWGController: disable proximity sensor
09-09 13:41:35.712   838  1034 D LPWGController: enable proximity sensor
09-09 13:41:35.720   838  1034 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@189130d1] by com.android.server.power.ProximitySensorListener.enable():120
,09-09 13:41:35.726   838  1034 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
09-09 13:41:35.726   838  1034 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
09-09 13:41:35.726   838  1034 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
09-09 13:41:35.726   838  1034 I sensors_hal_Ctx: activate: handle is 48, enable
09-09 13:41:35.727   838  1034 V sensors_hal_Ctx: activate sensors is 1400000000000
09-09 13:41:35.727   838  1034 D sensors_hal_Thresh: enable: handle=48
09-09 13:41:35.727   838  1034 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
09-09 13:41:35.727   838  1034 D sensors_hal_Util: waitForResponse: timeout=1000
09-09 13:41:35.731   838  1029 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,09-09 13:41:35.732   838  1029 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
09-09 13:41:35.732   838  1034 D sensors_hal_Thresh: enable: Received response: 0
09-09 13:41:35.732   838  1034 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (32890 ms ago)
09-09 13:41:35.749   838  1034 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:35.749   838  1034 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:35.749   838  1034 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:41:35.749   838  1034 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:41:35.749   838  1034 I Adreno-EGL: Remote Branch: 
09-09 13:41:35.749   838  1034 I Adreno-EGL: Local Patches: 
09-09 13:41:35.749   838  1034 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:41:35.782   246   266 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1452 us)
,09-09 13:41:35.960   427  1020 I Sensors : sns_pwr.c(273):acquiring wakelock
09-09 13:41:35.960   838  1029 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,09-09 13:41:35.961   838  1029 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
09-09 13:41:35.961   838  1029 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
09-09 13:41:35.961   838  1029 D sensors_hal_Thresh: processInd: handle 48, count=1
09-09 13:41:35.961   838  1029 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
09-09 13:41:35.961   838  1029 I sensors_hal_Thresh: processInd : proximity state changed - FAR
09-09 13:41:35.961   838  1057 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
09-09 13:41:35.961   838  1057 D sensors_hal_Ctx: poll: count: 256
09-09 13:41:35.962   838  1057 I sensors_hal_Ctx: poll: released wakelock sensor_ind
09-09 13:41:35.962   838  1057 D sensors_hal_Util: waitForResponse: timeout=0
09-09 13:41:35.963   838  1034 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
09-09 13:41:35.963   838  1034 I LPWGController: current mode = 1  value = 1 1
09-09 13:41:35.964   838  1034 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
09-09 13:41:36.010  6963  7003 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-09 13:41:36.010  6963  7003 I Babel_SMS: MmsConfig.loadMmsSettings
,09-09 13:41:36.017  6963  7003 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-09 13:41:36.018  6963  7003 I Babel_SMS: MmsConfig.loadFromDatabase
,09-09 13:41:36.038  6963  7003 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-09 13:41:36.038  6963  7003 I Babel_SMS: MmsConfig.loadFromResources
09-09 13:41:36.040  6963  7003 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-09 13:41:36.040  6963  7003 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-09 13:41:36.067   838  1034 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,09-09 13:41:36.117  6963  6963 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
09-09 13:41:36.117  6963  6963 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
09-09 13:41:36.117  6963  6963 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
09-09 13:41:36.118  6963  6963 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
09-09 13:41:36.118  6963  6963 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
09-09 13:41:36.118  6963  6963 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
09-09 13:41:36.118  6963  6963 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
09-09 13:41:36.118  6963  6963 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
09-09 13:41:36.118  6963  6963 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
09-09 13:41:36.118  6963  6963 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
09-09 13:41:36.118  6963  6963 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
09-09 13:41:36.118  6963  6963 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
09-09 13:41:36.118  6963  6963 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
09-09 13:41:36.118  6963  6963 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
09-09 13:41:36.118  6963  6963 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
09-09 13:41:36.118  6963  6963 D SensorManager: found sensor: Motion Accel, handle=46
,09-09 13:41:36.140   838  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1bb0670e type 2 when 153288 com.google.android.gms} when 153288
,09-09 13:41:36.142  6963  6977 I art     : CheckpointMarkThreadRoots callback created = 0xb042d870
09-09 13:41:36.160   293   354 I ThermalEngine: Sensor:pa_therm0:38000 mC
,09-09 13:41:36.176  6963  6977 I art     : CheckpointMarkThreadRoots callback created = 0xb042d860
,09-09 13:41:36.188   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,09-09 13:41:36.188   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,09-09 13:41:36.194   838  1017 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 13:41:36.202  6963  6963 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:36.205  6963  6963 I Babel_Crash: startup - clean
,09-09 13:41:36.255  6963  7007 I Babel   : deleted: false for 0
,09-09 13:41:36.270  6959  6959 E wpa_supplicant: USIM:  scard_init function
09-09 13:41:36.272  6959  6959 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 13:41:36.274   276  1006 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
09-09 13:41:36.274   276  1006 I Netd    : M: Get netlink event, ifname: p2p0 action: 9
09-09 13:41:36.275   276  1006 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
09-09 13:41:36.275   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:36.275   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:36.316  6959  6959 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-09 13:41:36.317   838  1348 D qdlights: set_light_backlight: 0
,09-09 13:41:36.332  6893  6893 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:41:36.334   838  1034 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
09-09 13:41:36.334   838  1034 I sensors_hal_Ctx: activate: handle is 46, disable
09-09 13:41:36.334   838  1034 V sensors_hal_Ctx: activate sensors is 1000000000000
09-09 13:41:36.334   838  1034 D sensors_hal_LP2: enable: handle=46
09-09 13:41:36.334   838  1034 D sensors_hal_LP2: enable: Disabling sensor handle=46
09-09 13:41:36.334   838  1034 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
09-09 13:41:36.339   246   246 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
09-09 13:41:36.339   246   246 D qdhwcomposer: hwc_blank: Blanking display: 0
09-09 13:41:36.339  6893  6893 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:41:36.340  6959  6959 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-09 13:41:36.342   838  1306 D WifiStateMachine: MAC Addr from driver = a0:39:f7:70:12:80
09-09 13:41:36.343   838  1306 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-09 13:41:36.344   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.344   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.344   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.344   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.344   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:41:36.344   838  1018 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
09-09 13:41:36.348   838   838 V ActivityManager: Display changed displayId=0
09-09 13:41:36.355  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:36.358  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:36.357 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:36.358  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:41:36.359   838   838 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-09 13:41:36.359   838  1310 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-09 13:41:36.359   838   838 E WifiServerServiceExt: sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
09-09 13:41:36.371  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 13:41:36.371  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:41:36.372  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:41:36.378  1748  1748 D DSDPConnection: Display #0 changed.
09-09 13:41:36.379  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:36.379  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:36.379  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:36.380  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:36.380  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-09 13:41:36.380  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:36.380  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:36.380  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:36.380  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:36.380  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:36.380  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:36.380  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:36.380  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:36.382  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:36.383  6502  6502 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:36.388  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:36.389  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:36.389  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:36.389  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:36.389  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:36.389  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:36.389  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:36.389  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:36.389  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:36.390  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:36.391  6502  6502 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:36.391  6893  6893 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:36.392   838  1306 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-09 13:41:36.392  6963  6963 W AudioCapabilities: Unsupported mime audio/x-lg-flac
09-09 13:41:36.393   838  1306 D WifiStateMachine: enableVerboseLogging : level 2
09-09 13:41:36.394  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:36.394  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:36.394  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:36.394  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:36.394  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:36.394  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:36.394  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:36.394  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:36.394  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:36.396  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:36.397  6963  6963 W AudioCapabilities: Unsupported mime audio/adpcm
09-09 13:41:36.397  6502  6502 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:36.399  1802  1802 D WfdsService: Supplicant Connection state is changed : true
09-09 13:41:36.399  1802  2129 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-09 13:41:36.400  1802  2129 D WfdsService: Set the WFDS Monitor: true
09-09 13:41:36.400  1802  2129 D WfdsMonitor: WfdsMonitorThread create
09-09 13:41:36.400   838  1306 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:41:36.400  1802  2129 D WfdsMonitor: WFDS Monitor is created and started
09-09 13:41:36.400  1802  2129 D WfdsService: WiFi: Supplicant connection re-established
09-09 13:41:36.400   838  1306 D WifiNative-HAL: Setting external_sim to 1
09-09 13:41:36.401   838  1306 I WifiNative-HAL: startHal
09-09 13:41:36.401   838  1306 D wifi    : setting scan oui 0xb050a3a0
09-09 13:41:36.401  1802  7012 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-09 13:41:36.401   838  1306 D WifiHAL : Sending mac address OUI
09-09 13:41:36.401   838  1306 E WifiHAL : failed to set scanning mac OUI; result = -95
09-09 13:41:36.401   838  1306 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:41:36.401   838  1306 I WifiNative-HAL: startHal
09-09 13:41:36.401   838  1306 D wifi    : setting scan oui 0xb050a3a0
09-09 13:41:36.401   838  1306 D WifiHAL : Sending mac address OUI
09-09 13:41:36.402   838  1306 E WifiHAL : failed to set scanning mac OUI; result = -95
09-09 13:41:36.402  1802  7012 E CtrlSupplicant: Succeed to open control connection
09-09 13:41:36.402   838  1053 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
09-09 13:41:36.403   838  1053 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
09-09 13:41:36.403  1802  7012 E CtrlSupplicant: Succeed to open monitor connection
09-09 13:41:36.403  1802  7012 D WfdsMonitor: Supplicant connection established
09-09 13:41:36.403  1802  2129 D WfdsService: Connected to the supplicant for wfds
09-09 13:41:36.404  6893  6893 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:36.405  6963  6963 W AudioCapabilities: Unsupported mime audio/g726
09-09 13:41:36.407  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:41:36.410   838  1305 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.411   838  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:36.412   838  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:36.412  6963  6963 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-09 13:41:36.412   276  1013 D CommandListener: Setting iface cfg
09-09 13:41:36.412   276  1013 D CommandListener: Trying to bring up p2p0
09-09 13:41:36.413   838  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 13:41:36.413   838  1305 D LGWifiP2pService: P2pEnablingState
09-09 13:41:36.413   838  1305 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.413   838  1305 D LGWifiP2pService: P2p socket connection successful
09-09 13:41:36.413   838  1305 D LGWifiP2pService: P2pEnabledState
09-09 13:41:36.414   838   838 D WifiScanningService: SCAN_AVAILABLE : 3
09-09 13:41:36.414   838   838 D RttService: SCAN_AVAILABLE : 3
09-09 13:41:36.414   838  1305 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-09 13:41:36.414   838  1305 D LGWifiP2pService: before postfix = G3s-1
09-09 13:41:36.414   838  1305 D WifiServerServiceExt: postfix byte check : 5
09-09 13:41:36.414   838  1305 D LGWifiP2pService: after postfix = G3s-1
09-09 13:41:36.414   838  1328 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.414   838  1328 I WifiNative-HAL: startHal
09-09 13:41:36.414   838  1329 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.415   838  1328 D wifi    : getting scan capabilities on interface[0] = 0xb050a3a0
09-09 13:41:36.415   838  1328 D WifiHAL : Creating message to get scan capablities; iface = 24
09-09 13:41:36.415   838  1328 D wifi    : failed to get capabilities : -95
09-09 13:41:36.415   838  1328 E WifiScanningService: could not get scan capabilities
09-09 13:41:36.416   838  1305 D WifiNative-HAL: p2pGetDeviceAddress
09-09 13:41:36.416   838  1305 D WifiNative-HAL: p2pGetDeviceAddress returning a2:39:f7:70:12:80
09-09 13:41:36.416   838  1305 D LGWifiP2pService: DeviceAddress: a2:39:f7:70:12:80
09-09 13:41:36.417  6963  6963 W AudioCapabilities: Unsupported mime audio/wma-voice
09-09 13:41:36.419  1802  1802 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-09 13:41:36.419  1802  1802 D WfdsService: Update P2p Interface State: 3
09-09 13:41:36.420  6963  6963 W VideoCapabilities: Unsupported mime video/mjpg
,09-09 13:41:36.423   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:36.423   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.423   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 13:41:36.424  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:36.424  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:36.424  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:36.424 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:36.424  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:41:36.426  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:36.426   838  1306 I WifiServerServiceExt: set CMD_ADD_DEFAULT_PROFILE
09-09 13:41:36.426  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:36.426  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:36.426  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:36.426  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:36.426  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:36.427   838  1306 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-09 13:41:36.435  6893  6893 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:36.435  6893  6893 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 13:41:36.435  6893  6893 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 13:41:36.435  6893  6893 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 13:41:36.436  6963  6963 W VideoCapabilities: Unsupported mime video/theora
,09-09 13:41:36.442  6893  6893 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 13:41:36.460  6959  6959 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,09-09 13:41:36.461   838  1306 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-09 13:41:36.461  6959  6959 E wpa_supplicant: disconnect_rssi_lvl: -100
09-09 13:41:36.461   838  1305 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-09 13:41:36.462   838  1305 D LGWifiP2pService: sending p2p connection changed broadcast
09-09 13:41:36.462   838  1305 D LGWifiP2pService: InactiveState
09-09 13:41:36.462   838  1305 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.462   838  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.462   838  1305 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.462   838  1305 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.463   838  1305 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.463   838  1305 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:36.463   838   838 E WifiServerServiceExt: No p2p device connected
09-09 13:41:36.463   838  1306 I WifiServerServiceExt: set CMD_SET_FRAMEWORK_AUTO_JOIN 0
09-09 13:41:36.463  6959  6959 E wpa_supplicant: wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
09-09 13:41:36.464  1802  1802 D WfdsService: WifiP2pState is changed : true
09-09 13:41:36.464  1802  1802 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-09 13:41:36.464  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
09-09 13:41:36.464  1802  2129 D WfdsService: Receive the WFDS_ENABLE Method
09-09 13:41:36.464  1802  2129 D WfdsService: Set the WFDS Monitor: true
09-09 13:41:36.464  1802  2129 D WfdsService: Connected to the supplicant for wfds
09-09 13:41:36.464  1802  2129 D WfdsJNI : doCommand: WFDS_SET TRUE
09-09 13:41:36.464  6959  6959 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-09 13:41:36.464  1802  2129 D WfdsJNI : doCommand: WFDS_CLEAR_PD_INFO
09-09 13:41:36.465  6959  6959 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
09-09 13:41:36.465  1802  2129 D WfdsJNI : wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
09-09 13:41:36.465  1802  2129 D WfdsService: selectPreferredScanChannel [6]
09-09 13:41:36.465  1802  2129 D WfdsService: STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
09-09 13:41:36.465  1802  1802 D WfdsService: isConnected: false
09-09 13:41:36.466  6963  6963 W AudioCapabilities: Unsupported mime audio/evrc
09-09 13:41:36.466   838  1306 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
09-09 13:41:36.467  6963  6963 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 13:41:36.468   838  1305 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.468   838  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.468   838  1305 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.468   838  1305 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.468   838  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.468   838  1305 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.468  6963  6963 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:41:36.468  1802  1802 D WfdsService: GroupInfoAvailable: mGroupInfo is null
09-09 13:41:36.469  1802  2129 W WfdsService: DefaultState - msg [9441285] is not handled
09-09 13:41:36.478  6963  6963 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-09 13:41:36.479  6963  6963 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 13:41:36.480  6963  6963 W AudioCapabilities: Unsupported mime audio/evrc
,09-09 13:41:36.482  6893  6893 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 13:41:36.482  6893  6893 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-09 13:41:36.482  6893  6893 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 13:41:36.483  6893  6893 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 13:41:36.483  6893  6893 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 13:41:36.483  6893  6893 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-09 13:41:36.485  6893  6893 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 13:41:36.485  6959  6959 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 13:41:36.487  6959  6959 I wpa_supplicant: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2437 MHz)
09-09 13:41:36.501  6963  6963 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-09 13:41:36.522   838  1844 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7015 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
09-09 13:41:36.525   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.526   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.526   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 13:41:36.526   838   838 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:36.526   838   838 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 13:41:36.532   838   838 D LocSvc_java: onReceive
09-09 13:41:36.532   246   246 D qdhwcomposer: hwc_blank: Done blanking display: 0
09-09 13:41:36.533   246   695 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
09-09 13:41:36.533   838  1348 D SurfaceControl: Excessive delay in setPowerMode(): 194ms
09-09 13:41:36.533   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:36.533   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.533   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 13:41:36.534   838  1348 I QCOM PowerHAL: Got set_interactive hint
09-09 13:41:36.535   838   838 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:36.535   838   838 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 13:41:36.536   838   838 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:36.536   838   838 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-09 13:41:36.545  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:36.545  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:36.546  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:36.545 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:36.546  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:41:36.546  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,09-09 13:41:36.546  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:36.546 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:36.547  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-09 13:41:36.548  1375  1898 D KeyguardViewMediator: onScreenTurnedOff(3)
09-09 13:41:36.550  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:36.550  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:36.551  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:36.551  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:36.551  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:36.551  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:36.551  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:36.552  6502  6502 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-09 13:41:36.552  6502  6502 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
09-09 13:41:36.556  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:36.556  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:36.556  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:36.556  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:36.556  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:36.556  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:36.562  1375  1898 D KeyguardViewMediator: notifyScreenOffLocked
,09-09 13:41:36.563  1330  1345 D SmartCoverViewMediator: onScreenTurnedOff(3)
09-09 13:41:36.571  6963  6963 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-09 13:41:36.575  6959  6959 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 13:41:36.580   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:41:36.580   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:41:36.580   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:41:36.582  1330  1345 D SmartCoverViewMediator: notifyScreenOffLocked
09-09 13:41:36.583  1330  1330 D SmartCoverViewMediator: handleNotifyScreenOFF
09-09 13:41:36.596  6963  6963 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:41:36.602  6959  6959 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:41:36.602  6959  6959 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 13:41:36.603   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:41:36.604  6502  6502 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@31c5b796 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3deeecf6, 16908290=android.view.AbsSavedState$1@3deeecf6}, android:focusedViewId=100}]}]
09-09 13:41:36.604  6502  6502 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-09 13:41:36.604  6502  6502 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 13:41:36.605  6502  6502 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-09 13:41:36.606  6963  6963 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:41:36.610  6963  6963 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:41:36.615  1375  1898 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
09-09 13:41:36.616  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:36.616  1375  1375 D KeyguardViewMediator: handleNotifyScreenOff
09-09 13:41:36.616  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:36.616 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:36.616  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-09 13:41:36.617   838   838 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:36.617   838   838 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-09 13:41:36.618  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:36.619  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:36.619 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:36.619  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-09 13:41:36.621   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.621   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.621   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 13:41:36.621   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.621   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.621   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-09 13:41:36.626   838   838 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
,09-09 13:41:36.630  6963  6963 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:41:36.631   280  1322 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 838
09-09 13:41:36.632   280  1322 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-09 13:41:36.632   280  1322 V voice   : voice_set_parameters: enter: screen_state=on
09-09 13:41:36.633   280  1322 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
09-09 13:41:36.633   280  1322 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-09 13:41:36.633   280  1322 V voice   : voice_set_parameters: exit with code(0)
09-09 13:41:36.633   280  1322 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
09-09 13:41:36.633   280  1322 V msm8974_platform: platform_set_parameters: enter: screen_state=on
09-09 13:41:36.634   280  1322 V msm8974_platform: platform_set_parameters: exit with code(0)
09-09 13:41:36.634   280  1322 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-09 13:41:36.634   280  1322 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
09-09 13:41:36.634   280  1322 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
09-09 13:41:36.634   280  1322 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-09 13:41:36.635   838  1306 I WifiServiceExtension: setVHTCapabilityType  : false
09-09 13:41:36.638  6963  6963 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.638  1375  1375 D ScreenTurnOffBySensor: unregisterProximitySensor
09-09 13:41:36.638  6963  6963 I vclib   : onServiceConnected
,09-09 13:41:36.639  6963  6963 W Babel   : Attempted to change video mute state without an active call.
09-09 13:41:36.640  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:36.643  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:36.644  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:36.644  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:36.644  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:36.644  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:36.644  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:36.645  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:36.647  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:36.648  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:36.648  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:36.648  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:36.648  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:36.648  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:36.651   838  1306 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-09 13:41:36.652   838  1306 I WifiServerServiceExt: setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
09-09 13:41:36.652   838  1306 I WifiServiceExtension: setSecurityType  : 2
,09-09 13:41:36.655  1375  1375 D StatusBarWindowView: onScreenTurnedOff why = 3
09-09 13:41:36.660  1375  1375 D KeyguardUpdateMonitor: handleTimeUpdate
09-09 13:41:36.666  6963  6963 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
09-09 13:41:36.667  1375  1375 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
,09-09 13:41:36.670  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:36.672  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:36.673  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:36.673  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:36.673 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:36.673  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:36.673  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-09 13:41:36.673  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:36.674  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:36.674  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:36.674  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:36.674  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:36.674  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:36.674 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:36.674  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:36.674  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-09 13:41:36.675   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.675   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.675   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 13:41:36.675   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.675   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.675   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 13:41:36.676  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,09-09 13:41:36.676  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:36.677  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:36.677  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:36.677  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:36.677  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:36.677   838   890 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
09-09 13:41:36.681   838  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-09 13:41:36.681   838  1312 D ConnectivityService: Got NetworkAgent Messenger
09-09 13:41:36.681   838  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 13:41:36.682   838  1312 D ConnectivityService: NetworkAgent connected
09-09 13:41:36.684  1802  1818 D WifiServiceExtension: isInternetCheckAvailable return false
09-09 13:41:36.684  1837  1837 I QCNEJ   : |CORE| sendScreenState: state:true
09-09 13:41:36.685   838  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:41:36.703   838  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:41:36.706  6502  6657 D BluetoothAdapter: enable(): BT is already enabled..!
09-09 13:41:36.718  1802  1971 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
,09-09 13:41:36.721   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 9
09-09 13:41:36.722   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:36.722   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:36.722  1802  1971 D LEDService: stopPatternFlashing()
09-09 13:41:36.722   838  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:36.722   838  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:36.723   276  1013 D CommandListener: Setting iface cfg
09-09 13:41:36.723  1802  1971 D qdlights: set_light_notifications: 0,0,0,0,3
09-09 13:41:36.725  1802  1971 I LEDService: getCurrentHighestLGLedRecord : size = 1
09-09 13:41:36.725  1802  1971 D qdlights: set_light_notifications: 0,0,0,0,3
09-09 13:41:36.726   838  1306 E WifiStateMachine: Start Dhcp Watchdog 2
09-09 13:41:36.726  1802  1971 I LEDService: updateLightsLocked : turn off led
09-09 13:41:36.727  1802  1971 D qdlights: set_light_notifications: 0,0,0,0,3
09-09 13:41:36.728   838  7034 D DhcpStateMachine: StoppedState
09-09 13:41:36.728   838  7034 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.728   838   838 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:36.728   838   838 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-09 13:41:36.728  1802  1971 D LEDHandler: RESTART MSG
09-09 13:41:36.729   838   838 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:36.729   838   838 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-09 13:41:36.731   838  7034 D DhcpStateMachine: WaitBeforeStartState
,09-09 13:41:36.732   838  1306 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
09-09 13:41:36.741  1837  1837 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
09-09 13:41:36.742  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-53 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:36.742 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:36.745   838  1312 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 13:41:36.747   838   838 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-09 13:41:36.747   838   838 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 13:41:36.762  7015  7015 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:41:36.763  7015  7015 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-09 13:41:36.767  7015  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:41:36.771  7015  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:41:36.774   838  1783 D SplitWindow: check instance of lgWin Window{390245a0 u0 SearchPanel}
09-09 13:41:36.775  6893  6893 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:36.780  1802  1802 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
09-09 13:41:36.780  6893  6893 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:36.782  1802  1802 D Cliptray Service: lockStatus = 0
09-09 13:41:36.783  6918  6918 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-09 13:41:36.783  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:41:36.783  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:36.788  7015  7036 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:41:36.790  7015  7036 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-09 13:41:36.796  6893  6893 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:36.797  7015  7035 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:41:36.798   838  1880 D InputDispatcher: Window went away: Window{1a9589d3 u0 SearchPanel}
09-09 13:41:36.803  6893  6893 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:41:36.804  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:36.805  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:36.805  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:36.805  1375  1375 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
09-09 13:41:36.806  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:36.807   838  1844 I ActivityManager: Killing 6444:com.google.android.setupwizard/u0a38 (adj 15): empty #11
09-09 13:41:36.832   838  1306 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-09 13:41:36.832   838  1306 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 13:41:36.832   838  1306 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 13:41:36.832   838  1305 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@30ee9559 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.832   838  1305 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@30ee9559 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.833   838  7034 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.833   838  7034 D DhcpStateMachine: DHCP Start wake lock is acquired.
,09-09 13:41:36.835   276  1013 D CommandListener: Setting iface cfg
,09-09 13:41:36.836   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
09-09 13:41:36.836   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:36.836   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:36.838   276  1013 D CommandListener: Trying to bring up wlan0
09-09 13:41:36.839   838  1306 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-09 13:41:36.843   838   866 W libprocessgroup: failed to open /acct/uid_10038/pid_6444/cgroup.procs: No such file or directory
09-09 13:41:36.844  1375  1375 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,09-09 13:41:36.849  1784  1784 D LNfcService: action : android.intent.action.SCREEN_ON
09-09 13:41:36.857   838   838 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:36.857   838   838 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 13:41:36.859   838  1312 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 13:41:36.860   838  1305 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.860   838  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:36.864  1784  7039 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
09-09 13:41:36.864  1784  7039 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
09-09 13:41:36.864  1784  7039 D LNfcService: isRequireNfcCRouting() return true
09-09 13:41:36.865  1784  7039 D LNfcService: isHCERoutingtoHost() return : true
09-09 13:41:36.865  1784  7039 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
09-09 13:41:36.865  1784  7039 D NfcService: mEnableLPD: true
09-09 13:41:36.865  1784  7039 D NfcService: mEnableReader: false
09-09 13:41:36.865  1784  7039 D NfcService: mEnableHostRouting: true
09-09 13:41:36.865  1784  7039 D NfcService: newParams.techmask= mTechMask: default
09-09 13:41:36.865  1784  7039 D NfcService: mEnableLPD: true
09-09 13:41:36.865  1784  7039 D NfcService: mEnableReader: false
09-09 13:41:36.865  1784  7039 D NfcService: mEnableHostRouting: true
09-09 13:41:36.865  1784  7039 D NfcService: screenState= 3
09-09 13:41:36.865  1784  7039 D NfcService: Discovery configuration equal, not updating.
09-09 13:41:36.868   838  1312 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 13:41:36.868   838  1306 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 13:41:36.868   838   838 D Ulp_jni : JNI:system_update. Event-0
09-09 13:41:36.869   838  1312 D ConnectivityService: ignoring duplicate network state non-change
09-09 13:41:36.874  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:36.875   838  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 13:41:36.875  1802  1817 D WifiServiceExtension: isInternetCheckAvailable return false
09-09 13:41:36.875   838  1312 D ConnectivityService: Adding iface wlan0 to network 101
09-09 13:41:36.875   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.876   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.876   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 13:41:36.876  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-53 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:36.876 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:41:36.876  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.109 ipV6Addr=
,09-09 13:41:36.879  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:36.881   838  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 13:41:36.882  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:36.884  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:36.885  1802  2131 D WifiServiceExtension: isInternetCheckAvailable return false
09-09 13:41:36.885  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:36.885  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:36.886  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:36.886  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
,09-09 13:41:36.887  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:36.888  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-53 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:36.888 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:41:36.888  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.109 ipV6Addr=
09-09 13:41:36.891   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.891   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.891   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 13:41:36.898   838   838 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 13:41:36.902   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.902   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.902   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 13:41:36.903  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,09-09 13:41:36.904  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:36.905  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:36.905 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:41:36.905  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.109 ipV6Addr=
09-09 13:41:36.907   838   838 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 13:41:36.910  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:36.910  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:36.910  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:36.910  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:36.910  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:36.911  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:36.911  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:36.913   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.913   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:36.913   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 13:41:36.913  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:36.913  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:36.913  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-09 13:41:36.913  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:36.913 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:41:36.913  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.109 ipV6Addr=
09-09 13:41:36.914  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 13:41:36.916  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:36.916  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSi,gnalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:36.916  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-09 13:41:36.917  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:36.918  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:36.918  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
,09-09 13:41:36.919  1748  1748 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
09-09 13:41:36.920  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:36.921  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:36.921  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
09-09 13:41:36.922  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 13:41:36.924   838  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 13:41:36.924   838  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-09 13:41:36.924  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:36.924  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:36.924  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
09-09 13:41:36.925  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:36.925   276  1013 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:41:36.925   276  1013 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:36.925   276  1013 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:41:36.925   276  1013 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:36.925  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:36.925  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:36.926   838  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-09 13:41:36.926   276  1013 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:41:36.926   276  1013 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:36.926   276  1013 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:41:36.926   276  1013 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:36.927   276  1013 E Netd    : netlink response contains error (File exists)
09-09 13:41:36.927   838  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-09 13:41:36.928   276  1013 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:41:36.928   276  1013 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:36.928   838  1312 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-09 13:41:36.928   838  1312 D ConnectivityServ,ice: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-09 13:41:36.929   838  1312 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-09 13:41:36.929   838  1312 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:36.929   838  1312 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:36.929   276  1013 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
09-09 13:41:36.929   276  1013 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:36.930   838  1312 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 13:41:36.930   838  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 13:41:36.930   838  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-09 13:41:36.930   838  1312 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-09 13:41:36.930   838  1312 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:36.930   838  1312 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:36.930   838  1312 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:41:36.930   838  1312 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:36.930   838  1312 D ConnectivityService:     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
09-09 13:41:36.932   838  7032 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.932   838  7032 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-09 13:41:36.932   838  7032 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.935   838  1312 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:36.935   838  1312 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-09 13:41:36.935   838  1312 D ConnectivityService: currentScore = 0, newScore = 20
09-09 13:41:36.935   838  1312 D ConnectivityService:    accepting network in place of null
09-09 13:41:36.935   838  1312 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:36.936   838  1306 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:36.937   838  1306 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:36.937   838  1312 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,09-09 13:41:36.937   838  1312 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 13:41:36.938   838  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:41:36.938  1748  1748 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:36.940  1748  1748 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
09-09 13:41:36.941   838  1312 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:36.941   838  1312 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-09 13:41:36.942   838  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-09 13:41:36.942   838  1017 D Tethering: MasterInitialState.processMessage what=3
09-09 13:41:36.942  1837  1837 W QCNEJ   : |CORE| No family connected
09-09 13:41:36.942  1837  1837 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
09-09 13:41:36.943   838  1312 D ConnectivityService: validation of new default Network = false
09-09 13:41:36.943   838  1312 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-09 13:41:36.943   838  1312 D DSQN    : enableDataServiceNotify 
09-09 13:41:36.943   838  1312 D DSQN    : start dsqn bin
09-09 13:41:36.945  1837  1837 I QCNEJ   : |CORE| sendDefaultNwMsg: default = 1
,09-09 13:41:36.960  1375  1375 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-09 13:41:36.962  1375  1375 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
09-09 13:41:36.967  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:36.967  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:36.967  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
09-09 13:41:36.969   838  1312 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-09 13:41:36.969   838  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:36.969   838  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:36.970   838  1312 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:36.970   838  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:36.970   838  1312 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:36.970  1375  1728 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:41:36.972  3382  3629 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:41:36.971  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:36.973  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:36.975   838  7032 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] Start DNSResolver start to wait
09-09 13:41:36.976  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
09-09 13:41:36.977   838  7045 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wait 500ms before dns check
09-09 13:41:36.985  7044  7044 I DSQN    : DSQN samuel.seo ver 141203
09-09 13:41:36.985  7044  7044 E DSQN    : DSQN sock connect success to lgdatalistenerd
,09-09 13:41:36.992  7044  7044 I DSQN    : created command queue thread
09-09 13:41:36.992  7044  7044 I DSQN    : Interface wlan0 address 192.168.1.109 0xc0a8016d
09-09 13:41:36.992  7044  7044 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a8016d
09-09 13:41:37.012   838  1801 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7048 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:37.017   838  1304 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-09 13:41:37.025  2863  2863 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:41:37
,09-09 13:41:37.028  2863  2863 D WeatherService: 2 : ACTION screen on
09-09 13:41:37.030  2863  2863 D WeatherService: 2 : shouldTimeTickRegistered : false
09-09 13:41:37.034   838  7034 D DhcpStateMachine: DHCPV4 request on wlan0
09-09 13:41:37.035   838  7034 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-09 13:41:37.035   838  7034 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-09 13:41:37.037  6941  6941 V LGMDMManager: Create singleton instance
,09-09 13:41:37.043  2863  2863 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 13:41:37.044  2863  2863 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:41:37
09-09 13:41:37.052  7063  7063 I dhcpcd  : version 5.5.6 starting
09-09 13:41:37.053  4083  4083 D AppCleanupService: android.intent.action.SCREEN_ON
09-09 13:41:37.054  7063  7063 E dhcpcd  : get_duid: Read-only file system
,09-09 13:41:37.075   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:37.076   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:37.076   838   838 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
09-09 13:41:37.089   280   280 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 838
09-09 13:41:37.089   280   280 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-09 13:41:37.089   280   280 V voice   : voice_set_parameters: enter: screen_state=off
09-09 13:41:37.089   280   280 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
09-09 13:41:37.089   280   280 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-09 13:41:37.089   280   280 V voice   : voice_set_parameters: exit with code(0)
09-09 13:41:37.089   280   280 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
09-09 13:41:37.089   280   280 V msm8974_platform: platform_set_parameters: enter: screen_state=off
09-09 13:41:37.089   280   280 V msm8974_platform: platform_set_parameters: exit with code(0)
09-09 13:41:37.089   280   280 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-09 13:41:37.089   280   280 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
09-09 13:41:37.089   280   280 V audio_hw_primary: adev_set_parameters: exit with code(0)
,09-09 13:41:37.092   838  1311 D WifiController: CMD_SCREEN_OFF 
09-09 13:41:37.092   838  1311 D WifiController: shouldWifiStayAwake TRUE
09-09 13:41:37.098  1375  1375 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
09-09 13:41:37.099   838   890 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
09-09 13:41:37.128  7048  7048 D UEI.SmartControl: Quickset Services start...
,09-09 13:41:37.135  7048  7048 I UEI.SmartControl: Manufacture = LGE
09-09 13:41:37.135  1837  1837 I QCNEJ   : |CORE| sendScreenState: state:false
09-09 13:41:37.136  1802  1971 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
09-09 13:41:37.136  1802  1971 D LEDService: stopPatternFlashing()
09-09 13:41:37.136  1802  1971 D qdlights: set_light_notifications: 0,0,0,0,3
09-09 13:41:37.137  7048  7048 D UEI.SmartControl: File observer start...
09-09 13:41:37.138  1802  1971 I LEDService: getCurrentHighestLGLedRecord : size = 1
09-09 13:41:37.138  1802  1971 D qdlights: set_light_notifications: 0,0,0,0,3
09-09 13:41:37.139  7048  7048 E UEI.SmartControl: IR Port is disabled: false
09-09 13:41:37.139  7048  7048 D UEI.SmartControl: Starting file observer...
09-09 13:41:37.139  7048  7048 D UEI.SmartControl: Extracting JNI libs...
09-09 13:41:37.140  1802  1802 D VolumeVibrator: clear
09-09 13:41:37.140  7048  7048 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-09 13:41:37.141  7063  7063 I dhcpcd  : wlan0: rebinding lease of 192.168.1.109
09-09 13:41:37.141  1802  1971 I LEDService: updateLightsLocked : turn on led
09-09 13:41:37.141  1802  1971 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
09-09 13:41:37.141  1802  1971 E LEDService: Can't handle this request of patternId:0
09-09 13:41:37.142  1802  1971 D LEDHandler: RESTART MSG
,09-09 13:41:37.144  6941  6941 I AudioManager: getMode name:com.lge.qremote
09-09 13:41:37.145  1802  1802 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
09-09 13:41:37.146  1784  1784 D LNfcService: action : android.intent.action.SCREEN_OFF
09-09 13:41:37.151  1784  2203 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
09-09 13:41:37.152  7063  7063 I dhcpcd  : wlan0: acknowledged 192.168.1.109 from 192.168.1.1
09-09 13:41:37.162  6893  6893 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:37.166  1730  7074 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:37.166  1730  7074 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:37.171  6893  6893 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:37.174  1730  7074 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,09-09 13:41:37.174  1730  7074 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:37.174   276  1008 E BandwidthController: [LG DATA] No such appUid: 10006
09-09 13:41:37.174   276  1008 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-09 13:41:37.174   276  7075 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
09-09 13:41:37.175   276  7075 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:37.175  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:37.175   276  7075 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
09-09 13:41:37.175   276  7075 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:41:37.182  7063  7063 I dhcpcd  : wlan0: leased 192.168.1.109 for 172800 seconds
09-09 13:41:37.184  1874  1874 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
09-09 13:41:37.186  7015  7015 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:41:37.187  7015  7015 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-09 13:41:37.206  7015  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,09-09 13:41:37.209  7015  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:41:37.216  1748  1748 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
09-09 13:41:37.217  6893  6893 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:41:37.218   276  7075 D libc-netbsd: res_queryN name = xxxxx succeed
,09-09 13:41:37.219  1730  7074 I System.out: propertyValue:false
,09-09 13:41:37.223  7015  7078 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:41:37.225  2863  2863 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:41:37
09-09 13:41:37.225  2863  2863 D WeatherService: 2 : ACTION screen off
09-09 13:41:37.227  2863  2863 D WeatherService: 2 : TimeTick Receiver Unregister
09-09 13:41:37.228  2863  2863 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:41:37
09-09 13:41:37.229  6893  6893 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:37.231  7015  7080 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:41:37.231  7015  7080 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:41:37.235  7015  7078 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,09-09 13:41:37.238  4083  4083 D AppCleanupService: android.intent.action.SCREEN_OFF
,09-09 13:41:37.244  4083  7085 D AppCleanupService: AppUsageStatsSaveTask
09-09 13:41:37.257  7015  7078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:41:37.258  1784  2687 E NxpNfcJni: getReconnectState = 0x0
,09-09 13:41:37.261  7044  7046 I DSQN    : first global connection report this to start monitoring at DSQM.
09-09 13:41:37.261  7044  7046 I DSQN    : restart monitoring
09-09 13:41:37.263  7044  7087 I DSQN    : dsqn report finish
09-09 13:41:37.263   276  1012 D LGDataListener: argv[0]=dsqncommand
09-09 13:41:37.263   276  1012 D LGDataListener: argv[1]=wlan0
09-09 13:41:37.263   276  1012 D LGDataListener: argv[2]=1
09-09 13:41:37.263   276  1012 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-09 13:41:37.264   838  1015 D DSQN    : DSQM DsqnNotification wlan0  1
09-09 13:41:37.264   838  1015 D DSQN    : start to monitor internet connection
09-09 13:41:37.275  1784  2203 D LCardEmulationManager: getHceAppCount hostAppNum : 0
09-09 13:41:37.275  1784  2203 D LCardEmulationManager: getDefaultRoute
09-09 13:41:37.275  1784  2203 D LNfcService: isRequireNfcCRouting() return true
09-09 13:41:37.276  1784  2203 D LNfcService: isHCERoutingtoHost() return : true
09-09 13:41:37.276  1784  2203 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
09-09 13:41:37.276  1784  2203 D NfcService: mEnableLPD: true
09-09 13:41:37.276  1784  2203 D NfcService: mEnableReader: false
09-09 13:41:37.276  1784  2203 D NfcService: mEnableHostRouting: true
09-09 13:41:37.276  1784  2203 D NfcService: newParams.techmask= mTechMask: 0
09-09 13:41:37.276  1784  2203 D NfcService: mEnableLPD: true
09-09 13:41:37.276  1784  2203 D NfcService: mEnableReader: false
09-09 13:41:37.276  1784  2203 D NfcService: mEnableHostRouting: true
,09-09 13:41:37.276  1784  2203 D NfcService: screenState= 1
09-09 13:41:37.289  7015  7015 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
09-09 13:41:37.290  7015  7015 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
09-09 13:41:37.290  7015  7015 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:41:37.293  7015  7015 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,09-09 13:41:37.295  1730  7074 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:37.295  1730  7074 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:41:37.305  7015  7015 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
09-09 13:41:37.331   838  1844 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7093 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
09-09 13:41:37.333  1784  2687 E NxpNfcJni: getReconnectState = 0x0
,09-09 13:41:37.345   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:37.346   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:37.346   838   838 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
,09-09 13:41:37.419   838  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:37.421   838  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:37.422   838   890 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:37.423  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
09-09 13:41:37.430  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
,09-09 13:41:37.431  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:37.431  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:37.431  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:37.431  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:37.431  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:37.431  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:37.431  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:37.431  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:37.432  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:37.433  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
09-09 13:41:37.433  6502  6502 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:37.436   838   838 D LocSvc_java: onReceive
09-09 13:41:37.436   838   838 D LocSvc_java: got connectivity action
09-09 13:41:37.437  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:37.437  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:37.437  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:37.437  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:37.437  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:37.437  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:37.437  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:37.437  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:37.437  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:37.438  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:37.440  6502  6502 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:37.442   838   838 D LocSvc_java: broadcast - no network connections
09-09 13:41:37.442   838   838 D LocSvc_java: Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
09-09 13:41:37.442   838   838 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 13:41:37.443   838   838 D LocSvc_java: onReceive
09-09 13:41:37.443   838   838 D LocSvc_java: got connectivity action
09-09 13:41:37.443   838   838 D LocSvc_java: broadcast - no network connections
09-09 13:41:37.443   838   838 D LocSvc_java: Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
09-09 13:41:37.443   838   838 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 13:41:37.445  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:37.446  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:37.446  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:37.446  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:37.446  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:37.446  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:37.446  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:37.446  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:37.446  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:37.447  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:37.448  6502  6502 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:37.442   838   890 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:37.452  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:37.452   838   890 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:37.453   838   838 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:41:37.453  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:37.453   838   838 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:41:37.453   838   838 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:41:37.453   838   838 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:41:37.453   838   838 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:41:37.453   838   838 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:41:37.455  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:37.460   427   436 I Sensors : sns_pwr.c(301):releasing wakelock
,09-09 13:41:37.477   838   890 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 13:41:37.477   838  7045 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver start dns
09-09 13:41:37.478   838  7045 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:37.478   838  7045 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:37.484   838  7045 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
09-09 13:41:37.484   838  7045 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:37.484   276  1008 E BandwidthController: [LG DATA] No such appUid: 1000
09-09 13:41:37.484   276  1008 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-09 13:41:37.484   276  7121 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
09-09 13:41:37.485   276  7121 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:37.485   276  7121 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
09-09 13:41:37.486   276  7121 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,09-09 13:41:37.527   276  7121 D libc-netbsd: res_queryN name = xxxxx succeed
,09-09 13:41:37.528   838  7045 I System.out: propertyValue:false
,09-09 13:41:37.528   838  7045 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver end dns
09-09 13:41:37.530   838  7032 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 13:41:37.538   838  7032 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:37.538   838  7032 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:37.556   838  1783 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@362279f6)
,09-09 13:41:37.565   838  1312 D ConnectivityService: dumpNetworkRequest
09-09 13:41:37.566   838  1312 D ConnectivityService:     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-09 13:41:37.566   838  1312 D ConnectivityService:     Requests:
09-09 13:41:37.567   838  1312 D ConnectivityService:         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:37.567   838  1312 D ConnectivityService:         NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:37.567   838  1312 D ConnectivityService:         NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:37.567   838  1312 D ConnectivityService:     Lingered:
09-09 13:41:37.567   838  1312 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:37.568   838  1312 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:37.570   838  1312 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:41:37.572   838  1844 I ActivityManager: Process com.google.android.gms (pid 3382) has died
09-09 13:41:37.583  7093  7093 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 13:41:37.583  7093  7093 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-09 13:41:37.587   838  7032 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:41:37 GMT], X-Android-Received-Millis=[1473421297587], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473421297561]}
09-09 13:41:37.587   838  7032 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 13:41:37.588  1802  2131 D WifiServiceExtension: isInternetCheckAvailable return false
09-09 13:41:37.588   838  7032 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wifi && isInternetCheckAvailable is false
09-09 13:41:37.589   838  7032 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-09 13:41:37.589   838  1312 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-09 13:41:37.589   838  1312 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-09 13:41:37.589   838  1312 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:37.589   838  1312 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:37.589   838  1312 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:41:37.589   838  1312 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-09 13:41:37.589   838  1312 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-09 13:41:37.589   838  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:37.589   838  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:37.589   838   838 D WifiDataContinuityService: sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
09-09 13:41:37.590   838  1312 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:37.590   838  1312 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:37.590   838  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 13:41:37.591  1375  1728 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:41:37.591  1748  1748 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:37.591   838  1306 I WifiServerServiceExt: set CMD_CAPTIVE_CHECK_COMPLETED
09-09 13:41:37.591  1748  1748 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
09-09 13:41:37.592   838  1306 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:37.592   838  1306 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:37.595  7093  7093 V [BNRBootReceiver]: Boot Receiver Return
09-09 13:41:37.595  7093  7093 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-09 13:41:37.598  6893  6893 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:37.604  6893  6893 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:37.609  1375  1375 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:41:37.610  1375  1375 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
09-09 13:41:37.612  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:37.612  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:37.612  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
,09-09 13:41:37.614  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:37.614  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:37.614  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
09-09 13:41:37.617  6893  6893 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-09 13:41:37.619  6893  6893 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-09 13:41:37.621  6893  6893 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:37.624  6893  6893 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:37.633  6893  6893 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:37.637   838  7034 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:37.637   838  7034 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:37.637   838  7034 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:37.637   838  7034 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:37.637   838  7034 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,09-09 13:41:37.637   838  7034 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:37.637   838  7034 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:37.637   838  7034 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:37.637   838  7034 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-09 13:41:37.639   838  7034 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 4
09-09 13:41:37.639   838  7034 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 13:41:37.639   838  7034 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:37.639   838  7034 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:37.640   838  7034 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.109
09-09 13:41:37.640   838  7034 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-09 13:41:37.640   838  7034 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 13:41:37.640   838  7034 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-09 13:41:37.640   838  7034 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-09 13:41:37.640   838  7034 D DhcpStateMachine: RunningState
09-09 13:41:37.641  6893  6893 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:37.649  6893  6893 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:37.654  6893  6893 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:37.662  6893  6893 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:37.666  6893  6893 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:37.675  6893  6893 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:37.679  6893  6893 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:37.688  6893  6893 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:37.693  6893  6893 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:37.703  7048  7048 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-09 13:41:37.704  7048  7048 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-09 13:41:37.704  7048  7048 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-09 13:41:37.710  6893  6893 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:41:37.714  6893  6893 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:37.723  6893  6893 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:37.728  6893  6893 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:37.732  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-09 13:41:37.735  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:41:37.740  7048  7048 I UEI.SmartControl: --- Selecting new region: 2
09-09 13:41:37.741  7048  7048 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
09-09 13:41:37.743  6893  6893 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:41:37.743  7048  7048 D UEI.SmartControl: Platform has CIR...
09-09 13:41:37.744  7048  7048 D UEI.SmartControl: NO CIR support, need to check package...
09-09 13:41:37.745  7048  7048 I UEI.SmartControl: Model: LG-D722 uses JNI
09-09 13:41:37.746  6893  6893 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:37.748  7048  7048 D UEI.SmartControl: QS Service created
,09-09 13:41:37.751  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-09 13:41:37.752  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:37.775  7048  7048 E UEI.SmartControl: QS start get config
,09-09 13:41:37.801   838  1775 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7124 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:37.823   301   301 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 21.054ms
09-09 13:41:37.829  7048  7048 D UEI.SmartControl: Loading JNI Libs...
,09-09 13:41:37.832  7048  7048 D UEI.SmartControl:  configuring local db...
09-09 13:41:37.844   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.436ms
,09-09 13:41:37.867   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 22.781ms
,09-09 13:41:37.912   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
09-09 13:41:37.912   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,09-09 13:41:37.912   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:41:37.918   838  1312 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-09 13:41:37.918   838  1312 D ConnectivityService: identical MTU - not setting
09-09 13:41:37.918   838  1312 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 13:41:37.918   838  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 13:41:37.919   838  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:37.919   838  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:37.919   838  1312 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:37.919   838  1312 D ConnectivityService: Wi-Fi IP changed. Lp difference / No Route difference
09-09 13:41:37.919   838  1312 D DSQN    : enableDataServiceNotify 
09-09 13:41:37.919   838  1312 D DSQN    : start dsqn bin
09-09 13:41:37.919  1837  1837 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
09-09 13:41:37.920  1375  1728 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-09 13:41:37.920  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:37.92 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:41:37.948   838  1312 D DSQN    : dsqn is running restart
,09-09 13:41:37.971   838  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 13:41:37.974  7141  7141 I DSQN    : DSQN samuel.seo ver 141203
09-09 13:41:37.974  7141  7141 E DSQN    : DSQN sock connect success to lgdatalistenerd
09-09 13:41:37.974  7141  7141 I DSQN    : created command queue thread
09-09 13:41:37.974  7141  7141 I DSQN    : Interface wlan0 address 192.168.1.109 0xc0a8016d
09-09 13:41:37.974  7141  7141 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a8016d
09-09 13:41:38.002   276  1006 I Netd    : M: Get netlink event, ifname: p2p0 action: 6
,09-09 13:41:38.002   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:38.002   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:38.051  7048  7048 D UEI.SmartControl:  ---- Has DB8: true
,09-09 13:41:38.059  7048  7048 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 13:41:38.060  7048  7048 D UEI.SmartControl: QS version = v2.7.11.1_RC1
09-09 13:41:38.061  7048  7048 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
09-09 13:41:38.064  7048  7048 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
,09-09 13:41:38.093  7048  7048 W irrc_jni: IRRCPlayer_nativeInit ++ 
09-09 13:41:38.094  7048  7048 D irrcClient: IrrcClient ++ 
09-09 13:41:38.094  7048  7048 D irrcClient: getIrrcService ++ 
09-09 13:41:38.094  7048  7048 D irrcClient: getIrrcService -- 
09-09 13:41:38.094  7048  7048 D irrcClient: IrrcClient -- 
09-09 13:41:38.094  7048  7048 W irrc_jni: IRRCPlayer_nativeInit -- 
,09-09 13:41:38.104  7048  7048 D UEI.SmartControl: Services init done
09-09 13:41:38.108  7048  7148 I UEI.SmartControl: Device manager: loading config....
,09-09 13:41:38.109  7048  7048 D UEI.SmartControl: QS Service init finished
09-09 13:41:38.110  7048  7048 D UEI.SmartControl: QS Service version name: 0.1.73
09-09 13:41:38.111  7048  7048 D UEI.SmartControl: QS Service version code: 1073
09-09 13:41:38.112  7048  7048 D UEI.SmartControl: Service requested: Control
09-09 13:41:38.114  7048  7148 D UEI.SmartControl: Config is loaded...
09-09 13:41:38.140  7124  7124 I MusicStore: Database version: 120
,09-09 13:41:38.152  7048  7147 D UEI.SmartControl:  ----- QS SDK is ready!!!
,09-09 13:41:38.153  7048  7147 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 13:41:38.163  7048  7048 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-09 13:41:38.165  7048  7048 D UEI.SmartControl: Internal service binding...
09-09 13:41:38.166  7048  7064 D UEI.SmartControl: -----IControl: 11
09-09 13:41:38.167  7048  7064 D UEI.SmartControl: Caller: com.lge.qremote
09-09 13:41:38.167  7048  7064 D UEI.SmartControl: ------------ IControl registerCallback...
09-09 13:41:38.168  7048  7064 I UEI.SmartControl: Registering callback...
09-09 13:41:38.169  7048  7065 D UEI.SmartControl: -----IControl: 19
09-09 13:41:38.170  7048  7065 D UEI.SmartControl: Caller: com.lge.qremote
09-09 13:41:38.171  7048  7065 I UEI.SmartControl: Registering Services Ready callback...
09-09 13:41:38.172  7048  7065 I UEI.SmartControl: Notify client services are ready...
09-09 13:41:38.174  7048  7064 D UEI.SmartControl: -----IControl: 8
,09-09 13:41:38.175  7048  7064 D UEI.SmartControl: Caller: com.lge.qremote
09-09 13:41:38.181   838  1775 I ActivityManager: Killing 6660:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
09-09 13:41:38.202   838  1775 I ActivityManager: Killing 6592:com.lge.appbox.client/u0a11 (adj 15): empty #12
,09-09 13:41:38.222   838  1801 W libprocessgroup: failed to open /acct/uid_10069/pid_6660/cgroup.procs: No such file or directory
,09-09 13:41:38.225   838  1844 W libprocessgroup: failed to open /acct/uid_10011/pid_6592/cgroup.procs: No such file or directory
09-09 13:41:38.250   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,09-09 13:41:38.250   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-09 13:41:38.250   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:38.254  7124  7124 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-09 13:41:38.368   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:38.368   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,09-09 13:41:38.368   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:38.369  7124  7124 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-09 13:41:38.371   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:38.371   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-09 13:41:38.371   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:38.375  7124  7124 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-09 13:41:38.407  7124  7124 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 13:41:38.407  7124  7124 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 13:41:38.456  7124  7124 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 13:41:38.531  7124  7138 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3f0
,09-09 13:41:38.538  7124  7124 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-09 13:41:38.539  7124  7124 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38c1ee2e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-09 13:41:38.540  7124  7124 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-09 13:41:38.540  7124  7124 D AndroidMusic: GMSCore installation verified
09-09 13:41:38.549  7124  7124 I ConfigStore: Config Database version: 1
,09-09 13:41:38.555  7124  7138 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3d0
,09-09 13:41:38.663  7124  7124 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-09 13:41:38.671  7124  7124 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
09-09 13:41:38.680  7124  7124 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 13:41:38.713   838  2176 I ActivityManager: Process com.google.android.gms.unstable (pid 6765) has died
,09-09 13:41:38.737  7124  7124 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 13:41:38.770   838  1924 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7165 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-09 13:41:38.796  7124  7124 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,09-09 13:41:38.837   838  1899 I ActivityManager: Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=7183 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,09-09 13:41:38.852  7124  7124 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:41:38.886  7165  7165 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:41:38.889  7165  7165 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:41:38.892  7165  7165 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-09 13:41:39.056   838  1880 I art     : Explicit concurrent mark sweep GC freed 112509(5MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/35MB, paused 2.314ms total 174.206ms
,09-09 13:41:39.079  7165  7165 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-09 13:41:39.084  7183  7183 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 13:41:39.085  7183  7183 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-09 13:41:39.097  7165  7165 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,09-09 13:41:39.134  7183  7183 I MultiDex: VM with version 2.1.0 has multidex support
09-09 13:41:39.134  7183  7183 I MultiDex: install
09-09 13:41:39.134  7183  7183 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-09 13:41:39.222   838  1347 I ActivityManager: Process com.google.android.talk (pid 6963) has died
,09-09 13:41:39.352   838  1305 D LGWifiP2pService: InactiveState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:39.352   838  1305 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:39.352   838  1305 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:39.360  7183  7183 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
09-09 13:41:39.392  7165  7165 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-09 13:41:39.416  7015  7015 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:39.416  7015  7015 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-09 13:41:39.417  7015  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:41:39.420  7183  7183 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-09 13:41:39.421  7183  7183 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@17d34a18: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-09 13:41:39.421  7183  7183 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-09 13:41:39.422  7015  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:41:39.429  7183  7183 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
,09-09 13:41:39.430  7183  7183 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
09-09 13:41:39.433  7015  7221 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:41:39.436  7015  7221 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-09 13:41:39.438  7015  7222 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:39.438  7015  7222 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:41:39.444  7165  7165 I HubEmail: JNI_OnLoad()
09-09 13:41:39.444  7165  7165 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:41:39.444  7165  7165 I HubEmail: registerNatives()
09-09 13:41:39.444  7165  7165 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:41:39.444  7165  7165 I HubEmail: registerNativeMethods()
09-09 13:41:39.444  7165  7165 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:41:39.444  7165  7165 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-09 13:41:39.472   838  1783 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7224 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-09 13:41:39.475  7165  7223 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:39.475  7015  7221 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,09-09 13:41:39.487  7015  7015 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,09-09 13:41:39.487  7015  7015 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
09-09 13:41:39.488  7015  7015 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:41:39.490  7015  7015 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:41:39.495  7015  7015 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
09-09 13:41:39.519  7183  7183 D ChimeraCfgMgr: Reading stored module config
,09-09 13:41:39.579   838   867 I ActivityManager: Killing 6684:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,09-09 13:41:39.597  7224  7224 I AppUp4:AppBoxCP: onCreate
,09-09 13:41:39.600  7224  7224 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-09 13:41:39.611  7224  7224 I AppUp4:DB:  setFingerPrint start
,09-09 13:41:39.611  7224  7224 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
09-09 13:41:39.620  7224  7224 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
09-09 13:41:39.620  7224  7224 I AppUp4:DB:  SDK version = 21
09-09 13:41:39.620  7224  7224 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-09 13:41:39.632   838  1880 W libprocessgroup: failed to open /acct/uid_10086/pid_6684/cgroup.procs: No such file or directory
,09-09 13:41:39.636  7224  7224 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-09 13:41:39.639  7124  7152 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
,09-09 13:41:39.640  7224  7224 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 13:41:39.640  7224  7224 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:39.642  7224  7224 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 13:41:39.642  7224  7224 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 13:41:39.646  7224  7224 I AppUp4:CustModeStarterReceiver: onReceive
09-09 13:41:39.646  7224  7224 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:39.650  7224  7224 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@19b9a5c3
09-09 13:41:39.650  7224  7224 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:41:39.655  7224  7224 D AppUp4:CustFacade: isSimDevice : true
09-09 13:41:39.656  7224  7224 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:41:39.657  7224  7224 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-09 13:41:39.658  7224  7224 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-09 13:41:39.660  7224  7247 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-09 13:41:39.660  7224  7247 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-09 13:41:39.660  7224  7247 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,09-09 13:41:39.662   838  1899 I ActivityManager: Killing 7093:com.lge.bnr/1000 (adj 15): empty #11
09-09 13:41:39.700  7183  7236 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-09 13:41:39.713   838  1359 W libprocessgroup: failed to open /acct/uid_1000/pid_7093/cgroup.procs: No such file or directory
,09-09 13:41:39.725  3150  3150 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 13:41:39.725  3150  3150 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:39.726  3150  3150 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-09 13:41:39.760   838  1347 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7250 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,09-09 13:41:39.881  7250  7250 D PhoneMonitor: Register our PhoneStateListener
,09-09 13:41:39.896  7250  7250 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-09 13:41:39.897  7250  7250 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 13:41:39.899   838  1864 I ActivityManager: Killing 6893:com.android.settings/1000 (adj 15): empty #11
09-09 13:41:39.900   838  1307 V WifiInternetCheck: Single check msg out of sync, ignoring.
09-09 13:41:39.916   838  2176 W libprocessgroup: failed to open /acct/uid_1000/pid_6893/cgroup.procs: No such file or directory
,09-09 13:41:39.927  2720  2720 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:39.933  7250  7250 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-09 13:41:39.939  2720  2720 V DownloadManager: DownloadService onCreate
09-09 13:41:39.941  7250  7250 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-09 13:41:39.941  2720  7273 I DownloadManager: in removeSpuriousFiles
,09-09 13:41:39.942   838  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:39.944  7250  7250 D TelephonyAutoProfiling: [parse] Load xml
09-09 13:41:39.949  2720  2720 I NotificationManager: com.android.providers.downloads: cancelAll by com.android.providers.downloads
09-09 13:41:39.954  7250  7250 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-09 13:41:39.954  2720  7273 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-09 13:41:39.955  7250  7250 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
09-09 13:41:39.958  2720  7273 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@127195cd on behalf of 2720
,09-09 13:41:39.965  7250  7250 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-09 13:41:39.973  2720  7273 I DownloadManager: in trimDatabase
09-09 13:41:39.973  2720  7273 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,09-09 13:41:39.979   838  1899 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7276 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-09 13:41:39.982   838   838 D LocSvc_java: onReceive
09-09 13:41:39.982   838   838 D LocSvc_java: got connectivity action
09-09 13:41:39.982   838   890 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:39.982   838   838 D LocSvc_java: Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
09-09 13:41:39.982   838   838 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-09 13:41:39.982   838   838 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:41:39.982   838   838 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:41:39.982   838   838 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:41:39.985  2720  2720 V DownloadManager: DownloadService onStartCommand
,09-09 13:41:39.998  7183  7201 I art     : CheckpointMarkThreadRoots callback created = 0xb042d380
09-09 13:41:39.999   838   890 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:40.004  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
09-09 13:41:40.007  7124  7124 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-09 13:41:40.008  2720  7273 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@6e9dd0 on behalf of 2720
,09-09 13:41:40.010  2720  7274 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-09 13:41:40.011  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:40.013  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:40.017  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:40.019  2720  7274 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@20ec1c9 on behalf of 2720
,09-09 13:41:40.037  7183  7201 I art     : CheckpointMarkThreadRoots callback created = 0xb042d370
,09-09 13:41:40.088  2720  2720 V DownloadManager: DownloadService onDestroy
,09-09 13:41:40.118  7183  7300 I CheckinService: Disabling old GoogleServicesFramework version
,09-09 13:41:40.130  2863  2863 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:41:40
09-09 13:41:40.132  2863  2863 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-09 13:41:40.132  2863  2863 D WeatherAncestor: connectivity changed - connection : true
09-09 13:41:40.132  2863  2863 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 13:41:40.132  2863  2863 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:41:40
09-09 13:41:40.133  2863  2863 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:40.135  2863  2863 D WeatherService: 2 : shouldTimeTickRegistered : false
09-09 13:41:40.212  7183  7305 I iu.SyncManager: SYNC; picasa accounts
09-09 13:41:40.214  7183  7301 I CheckinChimeraService: Checking schedule, now: 1473421300214 next: 1473421288860
,09-09 13:41:40.223  7183  7301 I CheckinChimeraService: active receiver: enabled
,09-09 13:41:40.243  7183  7301 I CheckinChimeraService: Preparing to send checkin request
,09-09 13:41:40.249  7183  7301 I EventLogChimeraService: Accumulating logs since 1473421252349
09-09 13:41:40.265  7183  7183 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-09 13:41:40.273  7183  7183 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-09 13:41:40.290  7183  7305 I iu.UploadsManager: num queued entries: 0
09-09 13:41:40.292  7183  7305 I iu.UploadsManager: num updated entries: 0
,09-09 13:41:40.294  7183  7305 I iu.SyncManager: NEXT; no task
09-09 13:41:40.366   838  1924 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7313 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-09 13:41:40.437  7183  7307 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
,09-09 13:41:40.491  7313  7313 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 13:41:40.614  7183  7301 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,09-09 13:41:40.618  7183  7301 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,09-09 13:41:40.763  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-09 13:41:40.764  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:41:40.779  7313  7340 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-09 13:41:40.779  7313  7340 I Babel_SMS: MmsConfig.loadMmsSettings
,09-09 13:41:40.783  7313  7340 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-09 13:41:40.783  7313  7340 I Babel_SMS: MmsConfig.loadFromDatabase
,09-09 13:41:40.804  7313  7340 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-09 13:41:40.804  7313  7340 I Babel_SMS: MmsConfig.loadFromResources
09-09 13:41:40.811  7313  7340 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-09 13:41:40.812  7313  7340 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-09 13:41:40.860  7313  7313 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
09-09 13:41:40.860  7313  7313 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
09-09 13:41:40.860  7313  7313 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
09-09 13:41:40.861  7313  7313 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
09-09 13:41:40.861  7313  7313 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
09-09 13:41:40.861  7313  7313 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
09-09 13:41:40.861  7313  7313 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
09-09 13:41:40.861  7313  7313 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
09-09 13:41:40.861  7313  7313 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
09-09 13:41:40.861  7313  7313 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
09-09 13:41:40.861  7313  7313 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
09-09 13:41:40.861  7313  7313 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
09-09 13:41:40.861  7313  7313 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
09-09 13:41:40.861  7313  7313 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
09-09 13:41:40.861  7313  7313 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
09-09 13:41:40.861  7313  7313 D SensorManager: found sensor: Motion Accel, handle=46
,09-09 13:41:40.912  7313  7328 I art     : CheckpointMarkThreadRoots callback created = 0xb042d4d0
,09-09 13:41:40.925   838   867 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7348 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,09-09 13:41:40.925  7313  7313 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:40.940  7313  7328 I art     : CheckpointMarkThreadRoots callback created = 0xb042d4b0
,09-09 13:41:40.954  7313  7313 I Babel_Crash: startup - clean
,09-09 13:41:41.006  7313  7357 I Babel   : deleted: false for 0
09-09 13:41:41.010  7348  7348 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 13:41:41.010  7348  7348 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 13:41:41.063  7313  7313 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,09-09 13:41:41.067  7348  7348 I MultiDex: VM with version 2.1.0 has multidex support
09-09 13:41:41.067  7348  7348 I MultiDex: install
09-09 13:41:41.067  7348  7348 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-09 13:41:41.069  7313  7313 W AudioCapabilities: Unsupported mime audio/adpcm
09-09 13:41:41.070  7313  7313 W AudioCapabilities: Unsupported mime audio/g726
09-09 13:41:41.071  7313  7313 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-09 13:41:41.072  7313  7313 W AudioCapabilities: Unsupported mime audio/wma-voice
09-09 13:41:41.074  7313  7313 W VideoCapabilities: Unsupported mime video/mjpg
,09-09 13:41:41.087  7313  7313 W VideoCapabilities: Unsupported mime video/theora
09-09 13:41:41.094   838  1819 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7370 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:41.133  7348  7348 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 13:41:41.165   293   354 I ThermalEngine: Sensor:pa_therm0:38000 mC
09-09 13:41:41.166  7313  7313 W AudioCapabilities: Unsupported mime audio/evrc
09-09 13:41:41.167  7313  7313 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 13:41:41.168  7313  7313 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:41:41.177  7313  7313 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-09 13:41:41.178  7313  7313 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 13:41:41.179  7313  7313 W AudioCapabilities: Unsupported mime audio/evrc
09-09 13:41:41.203  7313  7313 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-09 13:41:41.218  7348  7348 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-09 13:41:41.218  7348  7348 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1eefef64: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-09 13:41:41.219  7313  7313 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-09 13:41:41.219  7348  7348 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-09 13:41:41.221  7348  7348 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
,09-09 13:41:41.221  7348  7348 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
09-09 13:41:41.230  7313  7313 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:41:41.232  7313  7313 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:41:41.236  7313  7313 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:41:41.240  7348  7348 D ChimeraCfgMgr: Reading stored module config
09-09 13:41:41.242  7313  7313 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:41:41.251  7313  7313 I vclib   : onServiceConnected
09-09 13:41:41.252  7313  7313 W Babel   : Attempted to change video mute state without an active call.
09-09 13:41:41.274  7313  7313 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,09-09 13:41:41.304  7313  7388 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:41.304  7313  7388 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:41:41.306  7313  7388 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:41.306  7313  7388 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:41.306   276  1008 E BandwidthController: [LG DATA] No such appUid: 10061
09-09 13:41:41.306   276  1008 D DnsProxyListener: App 10061 tries DNS query. Accept family:0 protocol:0
09-09 13:41:41.307   276  7391 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
09-09 13:41:41.307   276  7391 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:41.308   276  7391 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
09-09 13:41:41.308   276  7391 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:41:41.308   276  7391 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:41:41.309  7313  7388 I System.out: propertyValue:false
09-09 13:41:41.351  7141  7142 I DSQN    : first global connection report this to start monitoring at DSQM.
,09-09 13:41:41.358  7141  7142 I DSQN    : restart monitoring
09-09 13:41:41.362   276  1012 D LGDataListener: argv[0]=dsqncommand
09-09 13:41:41.362   276  1012 D LGDataListener: argv[1]=wlan0
09-09 13:41:41.362   276  1012 D LGDataListener: argv[2]=1
09-09 13:41:41.362   276  1012 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-09 13:41:41.362  7141  7392 I DSQN    : dsqn report finish
09-09 13:41:41.363   838  1015 D DSQN    : DSQM DsqnNotification wlan0  1
09-09 13:41:41.363   838  1015 D DSQN    : start to monitor internet connection
09-09 13:41:41.419  7348  7348 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
09-09 13:41:41.420  7348  7348 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-09 13:41:41.420  7313  7388 I Babel   : connection state changed from UNKNOWN to CONNECTED
09-09 13:41:41.441  7348  7387 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-09 13:41:41.464   838  2110 I ActivityManager: Killing 7048:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,09-09 13:41:41.470  7348  7364 I art     : CheckpointMarkThreadRoots callback created = 0xb042d370
09-09 13:41:41.481  6941  6941 W System.err: android.os.DeadObjectException
,09-09 13:41:41.494  6941  6941 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,09-09 13:41:41.494  6941  6941 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,09-09 13:41:41.495  6941  6941 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-09 13:41:41.495  6941  6941 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
09-09 13:41:41.495  6941  6941 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
09-09 13:41:41.495  6941  6941 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
09-09 13:41:41.495  6941  6941 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:41.495  6941  6941 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:41.495  6941  6941 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:41:41.495  6941  6941 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
09-09 13:41:41.495  6941  6941 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:41.495  6941  6941 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:41.495  6941  6941 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
09-09 13:41:41.495  6941  6941 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
09-09 13:41:41.496  6941  6941 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-09 13:41:41.496  6941  6941 W System.err: android.os.DeadObjectException
09-09 13:41:41.496  6941  6941 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 13:41:41.496  6941  6941 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 13:41:41.496  6941  6941 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-09 13:41:41.496  6941  6941 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
09-09 13:41:41.496  6941  6941 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
09-09 13:41:41.496  6941  6941 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
09-09 13:41:41.496  6941  6941 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:41.496  6941  6941 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:41.496  6941  6941 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:41:41.496  6941  6941 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
09-09 13:41:41.496  6941  6941 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:41.496  6941  6941 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:41.496  6941  6941 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
09-09 13:41:41.497  6941  6941 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
09-09 13:41:41.497  6941  6941 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-09 13:41:41.497  7348  7364 I art     : CheckpointMarkThreadRoots callback created = 0xb042d360
09-09 13:41:41.612   838  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:41.612   838  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:41:41.614   838  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:41.614   838  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:41.615   276  1008 E BandwidthController: [LG DATA] No such appUid: 1000
09-09 13:41:41.615   276  1008 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-09 13:41:41.615   276  7399 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
09-09 13:41:41.615   276  7399 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:41.615   276  7399 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
09-09 13:41:41.616   276  7399 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:41:41.675   838   867 W libprocessgroup: failed to open /acct/uid_10089/pid_7048/cgroup.procs: No such file or directory
09-09 13:41:41.675   838   867 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,09-09 13:41:41.677   838  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{ef28613 type 2 when 158732 com.android.systemui} when 158732
09-09 13:41:41.693   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:41.693   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 13:41:41.693   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:41.695  7370  7400 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-09 13:41:41.698   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:41.699   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:41:41.699   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:41.699  7370  7400 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 13:41:41.708   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:41.708   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,09-09 13:41:41.708   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:41.713  7370  7404 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-09 13:41:41.720  6502  7033 E io.jxcore.node.ConnectivityMonitorTest: BT state didn't change after 5s!
09-09 13:41:41.720  7370  7370 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 13:41:41.720  7370  7370 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 13:41:41.720  7370  7370 I GAv4    :   adb logcat -s GAv4
09-09 13:41:41.722   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:41.722   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:41:41.722   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:41.723  7370  7404 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 13:41:41.730   838  1347 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7406 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:41:41.732   838   867 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:41.735   838   867 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@a39e74e mBinding = false
,09-09 13:41:41.748   838  1017 D BluetoothManagerService: Message: 2
,09-09 13:41:41.749   838   838 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:41:41.749   838   838 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:41:41.749   838   838 D Ulp_jni : JNI:system_update. Event-4
09-09 13:41:41.751  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:41.754   838  1017 D BluetoothManagerService: Sending off request.
09-09 13:41:41.758  2007  3522 D BluetoothAdapterService(490245822): disable() called...
,09-09 13:41:41.762  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:41.763  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:41.763  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:41.766  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:41.768  2007  2155 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-09 13:41:41.770  2007  2155 D BluetoothAdapterProperties: Setting state to 13
09-09 13:41:41.771  2007  2155 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 13:41:41.771  2007  2155 D BluetoothAdapterService(490245822): updateAdapterState() - Broadcasting state to 1 receivers.
09-09 13:41:41.784  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:41.784  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:41.785  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:41.785  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:41.785  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d31261b removed from the list
09-09 13:41:41.785  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:41.785  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b6ba3b8 removed from the list
09-09 13:41:41.785  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:41.785  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:41.785  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:41.787  2007  2155 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 13:41:41.790  7370  7370 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:41:41.800  2007  2155 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-09 13:41:41.800   280  1599 D WVCdm   : Instantiating CDM.
09-09 13:41:41.801   280  1322 I WVCdm   : CdmEngine::OpenSession
09-09 13:41:41.801   280  1322 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
09-09 13:41:41.806  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:41.806  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@273208f7 added. We now have 3 listener(s)
,09-09 13:41:41.808   838  1347 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:41.811  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
,09-09 13:41:41.812  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:41.812  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:41.812  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:41.812  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15134364 added. We now have 3 listener(s)
09-09 13:41:41.812  6502  6657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:41.813  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:41.817  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:41.817  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:41.818  2007  2164 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
09-09 13:41:41.818   838  1017 D BluetoothManagerService: Message: 60
09-09 13:41:41.818   838  1017 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,09-09 13:41:41.818   838  1017 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-09 13:41:41.821  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:41.821  6502  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:41.821  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:41.821  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:41.821  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:41.821  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:41.821  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:41.821  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:41.821  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:41.824  2007  2164 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:41:41.824  2007  2155 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-09 13:41:41.824  2007  2155 I bt-btif : BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
09-09 13:41:41.824  2007  2155 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-09 13:41:41.825  2007  2155 D bt-btif : btsock_ctrl_hci_cleanup(L202): poll handle:4
09-09 13:41:41.825  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:41.826  2007  2155 I bt-btif : BTA_JvDeleteRecord
09-09 13:41:41.826  2007  2155 I bt-btif : BTA_JvRfcommStopServer
09-09 13:41:41.826  2007  2155 I bt-btif : BTA_JvDeleteRecord
09-09 13:41:41.826  2007  2155 I bt-btif : BTA_JvRfcommStopServer
09-09 13:41:41.827  6502  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:41.827  6502  6657 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:41.827  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:41.827  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:41.827  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:41.827  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:41.827  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@273208f7 removed from the list
09-09 13:41:41.827  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:41.827  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15134364 removed from the list
09-09 13:41:41.827  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:41.827  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:41.829  2007  2007 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:41.829  2007  2007 D BluetoothMapService: STATE_TURNING_OFF
,09-09 13:41:41.834  1802  1802 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:41.849  2007  3608 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-09 13:41:41.859  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
,09-09 13:41:41.865  2007  2155 D IOP_DB_BT: db_close: nbr users 0
09-09 13:41:41.865  2007  2155 D IOP_DB_BT: db_close: free database
09-09 13:41:41.865  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:41.867  2007  3608 W bt-obex : Ignore event 10 in state 1
09-09 13:41:41.867  2007  3608 W bt-obex : Ignore event 10 in state 1
09-09 13:41:41.868  2007  2164 E bt-btif : btif_hf_upstreams_evt: wrong handle = 18022 
09-09 13:41:41.868  2007  2164 I bt-btif : HAL bt_op_callbacks->ops_state_cb
09-09 13:41:41.868  2007  2164 D BluetoothOPPServiceJni: ops_state_cb(L223):  ops_state_cb state:3
09-09 13:41:41.868  2007  2007 V BluetoothMapService: Handler(): got msg=4
09-09 13:41:41.869  2007  3608 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 13:41:41.869  2007  2007 D BluetoothMapService: MAP Service closeService in
09-09 13:41:41.869  2007  2164 D OppService: onOpsStateChange() :3
09-09 13:41:41.869  2007  2007 D BluetoothMapMasInstance: MAP Service shutdown
09-09 13:41:41.870  2007  2155 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L300): in, key:Adapter, value:BluezMigrationDone
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L343): out, key:Adapter, value:BluezMigrationDone
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L300): in, key:Adapter, value:Address
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L343): out, key:Adapter, value:Address
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L344): out, value:f8:95:c7:87:85:54
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L300): in, key:Adapter, value:Name
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L343): out, key:Adapter, value:Name
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L344): out, value:G3s-1
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
09-09 13:41:41.870  2007  2155 D btif_config_util: enum_config(L344): out, value:��8�\�婓��n�ScanMode,
09-09 13:41:41.871  2007  2155 D btif_config_util: enum_config(L300): in, key:Adapter, value:ScanMode
09-09 13:41:41.871  2007  2155 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
09-09 13:41:41.871  2007  2155 D btif_config_util: enum_config(L343): out, key:Adapter, value:ScanMode
09-09 13:41:41.871  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.871  2007  2155 D btif_config_util: enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
09-09 13:41:41.871  2007  2155 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
09-09 13:41:41.871  2007  2155 D btif_config_util: enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
09-09 13:41:41.871  2007  2155 D btif_config_util: enum_config(L344): out, value:x
09-09 13:41:41.871  2007  2155 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
09-09 13:41:41.871  2007  2155 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
09-09 13:41:41.871  2007  2155 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
09-09 13:41:41.871  2007  2155 D btif_config_util: enum_config(L344): out, value:s!WE�(E��00:0F:F6
,09-09 13:41:41.871  2007  2155 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
09-09 13:41:41.871  2007  2155 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
09-09 13:41:41.871  2007  2155 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
09-09 13:41:41.871  2007  2155 D btif_config_util: enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
09-09 13:41:41.871  2007  2155 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
09-09 13:41:41.871  2007  2155 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L344): out, value:BMW,Audi,Parrot,Car
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L344): out, value:00:0F:F6
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L344): out, value:�
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
09,-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
09-09 13:41:41.874  2007  2155 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L344): out, value:HTC Desire 820
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
09-09 13:41:41.875,  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L344): out, value:$
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L344): out, value:Galaxy S6-1
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
09-09 13:41:41.875  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L344): out, value:�
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L344): out, value:A5-1
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
,09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
09-09 13:41:41.876  2007  2155 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L344): out, value:#
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L344): out, value:Nexus 6
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
09-09 13:41:41.877  2007  2155 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L344): out, value:�
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L344): out, value:XT1072
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
09-09 13:41:41.878  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
09-09 13:41:41.878  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L344): out, value:a
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L344): out, value:S5-1
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Service
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Service, value type:string
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Service
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Manufacturer
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Manufacturer, value type:int
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Manufacturer
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.879  2007  2155 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpVer
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpVer, value type:int
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpVer
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpSubVer
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpSubVer, value type:int
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpSubVer
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L344): out, value:	a
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Name
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Name, value type:string
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Name
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L344): out, value:G4-1
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevClass
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevClass, value type:int
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevClass
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevType
09-09 13:41:41.880   838   892 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7433 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevType, value type:int
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevType
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:JustWorks
09-09 13:41:41.880  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:JustWorks, value type:int
09-09 13:41:41.882  2007  3674 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-09 13:41:41.882  2007  3674 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:41:41.882  2007  3674 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-09 13:41:41.882  2007  3674 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-09 13:41:41.882  2007  3674 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-09 13:41:41.882  2007  3674 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-09 13:41:41.882  2007  3674 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-09 13:41:41.882  2007  3674 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-09 13:41:41.884  2007  3684 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:41:41.881  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.884  2007  2155 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Service
09-09 13:41:41.884  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:41.884  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c94e282 added. We now have 3 listener(s)
09-09 13:41:41.884   276  7399 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:41:41.885   838  1307 I System.out: propertyValue:false
09-09 13:41:41.885  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Service, value type:string
09-09 13:41:41.885  2007  2155 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Service
09-09 13:41:41.885  2007  2155 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-09 13:41:41.885  2007  2155 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
09-09 13:41:41.885  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
09-09 13:41:41.885  2007  2155 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
09-09 13:41:41.885  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.885  2007  2155 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
09-09 13:41:41.885  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
09-09 13:41:41.885  2007  2155 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
09-09 13:41:41.885  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.885  2007  2155 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer
09-09 13:41:41.885  2007  2007 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L344): out, value:�
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L344): out, value:Thali Test (Galaxy A3)
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
09-09 13:41:41.886  2007  2007 V BluetoothMapService: MAP Service closeService out
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:JustWorks, value type:int
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:GlobalTrust
09-09 13:41:41.886  2007  2007 D OppService: Recieved MESSAGE_OPS_DISABLE
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Manufacturer
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Manufacturer, value type:int
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpVer, value type:int
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpSubVer, value type:int
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L344): out, value:A
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Name
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L344): out, value:Thali Test's G2
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevClass, value type:int
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:41:41.886  2007  2155 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevType
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:JustWorks
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:GlobalTrust, value type:int
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Service
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Manufacturer
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Manufacturer, value type:int
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpVer
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpVer, value type:int
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpVer
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.887  2007  2155 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpSubVer
09-09 13:41:41.887   838  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:41.887   838  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:41.888   838  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:41.888   838  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:41.888   276  1008 E BandwidthController: [LG DATA] No such appUid: 1000
09-09 13:41:41.888   276  1008 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-09 13:41:41.888   276  7440 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
09-09 13:41:41.888   276  7440 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:41.889   276  7440 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
09-09 13:41:41.889   276  7440 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:41:41.890   276  7440 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:41:41.890  2007  2155 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpVer
09-09 13:41:41.890  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpVer, value type:int
09-09 13:41:41.890  2007  2155 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpVer
09-09 13:41:41.890  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.890  2007  2155 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpSubVer
09-09 13:41:41.890  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpSubVer, value type:int
09-09 13:41:41.890  2007  2155 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpSubVer
09-09 13:41:41.890  2007  2155 D btif_config_util: enum_config(L344): out, value:"
09-09 13:41:41.890  2007  2155 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Name
09-09 13:41:41.890  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Name, value type:string
09-09 13:41:41.890  2007  2155 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Name
09-09 13:41:41.890  2007  2155 D btif_config_util: enum_config(L344): out, value:Note4-1
09-09 13:41:41.890  2007  2155 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevClass
09-09 13:41:41.890  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevClass, value type:int
09-09 13:41:41.890  2007  2155 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevClass
09-09 13:41:41.890  2007  2155 D btif_config_util: enum_config(L344): out, value:Z
09-09 13:41:41.890  2007  2155 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevType
09-09 13:41:41.890  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevType, value type:int
09-09 13:41:41.890  2007  2155 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevType
09-09 13:41:41.891  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.891  2007  2155 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:JustWorks
09-09 13:41:41.891  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:JustWorks, value type:int
09-09 13:41:41.891  2007  2155 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:JustWorks
09-09 13:41:41.891  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.891  2007  2155 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:GlobalTrust
09-09 13:41:41.891  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:GlobalTrust, value type:int
09-09 13:41:41.891  2007  2155 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:GlobalTrust
09-09 13:41:41.891  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.891  2007  2155 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Service
09-09 13:41:41.891  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Service, value type:string
09-09 13:41:41.894  2007  2155 D btif_config_util: enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpVer
09-09 13:41:41.894  2007  2155 D btif_config_util: enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpSubVer
09-09 13:41:41.894  2007  2155 D btif_config_util: enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpSubVer
09-09 13:41:41.895  2007  2155 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:JustWorks
09-09 13:41:41.895  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.896  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:DevClass, value type:int
09-09 13:41:41.896  2007  2155 D btif_config_util: enum_config(L344): out, value:Galaxy S5-2
09-09 13:41:41.896  2007  2155 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpVer, value type:int
09-09 13:41:41.897  2007  2155 D btif_config_util: enum_config(L343): out, key:00:00:00:00:5a:ad, value:JustWorks
09-09 13:41:41.897  2007  2155 D btif_config_util: enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:Name
09-09 13:41:41.897  2007  2155 D btif_config_util: enum_config(L344): out, value:
09-09 13:41:41.897  2007  2155 D btif_config_util: enum_config(L300): in, key:00:00:00:00:41:9e, value:DevType
09-09 13:41:41.904   280  1322 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
09-09 13:41:41.905   280  1322 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
09-09 13:41:41.905   280  1322 W WVCdm   : L1 library not specified. Falling Back to L3
09-09 13:41:41.931   838   867 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:41.938  7370  7370 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
09-09 13:41:41.947   838  1308 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
09-09 13:41:41.953  7406  7406 D UEI.SmartControl: Quickset Services start...
,09-09 13:41:41.955  7406  7406 I UEI.SmartControl: Manufacture = LGE
09-09 13:41:41.957  7406  7406 D UEI.SmartControl: File observer start...
09-09 13:41:41.965  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-09 13:41:41.965  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:41.965  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:41.965  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:41.966  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1af43d93 added. We now have 3 listener(s)
09-09 13:41:41.966  6502  6657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:41.969  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:41.969  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:41.982  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:41.983  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:41:41.986  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:41.986  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:41.986  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:41.986  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:41.986  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:41.986  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:41.986  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:41.986  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:41.986  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:41.987  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:41.987  6502  6502 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:41.990  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:41.990  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:41.990  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:41.990  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:41.990  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:41.990  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:41.990  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:41.990  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:41.990  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:41.990  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:41.991  6502  6502 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:41.992  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:41.994  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:42.002  7406  7406 E UEI.SmartControl: IR Port is disabled: false
,09-09 13:41:42.003  7406  7406 D UEI.SmartControl: Starting file observer...
09-09 13:41:42.003  7406  7406 D UEI.SmartControl: Extracting JNI libs...
09-09 13:41:42.004  7406  7406 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-09 13:41:42.010  6502  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:42.010  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:42.010  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:42.010  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:42.010  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:42.010  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:42.010  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:42.010  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:42.011  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:42.011  6502  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:42.011  6502  6657 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:42.013   838   866 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:42.013   838   866 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@a39e74e mBinding = false
09-09 13:41:42.015   838  1017 D BluetoothManagerService: Message: 2
09-09 13:41:42.015   838  1017 D BluetoothManagerService: Sending off request.
09-09 13:41:42.015  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:42.016  2007  3522 D BluetoothAdapterService(490245822): disable() called...
09-09 13:41:42.016  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:42.016  2007  3522 D BluetoothAdapterService: disable() : BT State is not STATE_ON. Can't disable BT
09-09 13:41:42.017   838  1017 E BluetoothManagerService: IBluetooth.disable() returned false
09-09 13:41:42.019  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:42.021  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:42.043  6502  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:42.044   838  1864 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:42.044   838  1864 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@a39e74e mBinding = false
,09-09 13:41:42.055   838  1017 D BluetoothManagerService: Message: 1
,09-09 13:41:42.055   838  1017 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@a39e74e
09-09 13:41:42.057   838   838 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:41:42.057   838   838 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:41:42.057   838   838 D Ulp_jni : JNI:system_update. Event-4
09-09 13:41:42.074  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:42.074  2007  2038 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-09 13:41:42.075   838  1017 E BluetoothManagerService: IBluetooth.enable() returned false
,09-09 13:41:42.086  7370  7447 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
09-09 13:41:42.096   280  1322 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-09 13:41:42.099   280   280 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-09 13:41:42.099   280   280 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-09 13:41:42.099   280   280 I WVCdm   : CdmEngine::GenerateKeyRequest
09-09 13:41:42.118   280   280 D WVCdm   : PrepareKeyRequest: nonce=245712198
,09-09 13:41:42.124  3984  4180 I art     : Explicit concurrent mark sweep GC freed 1854(69KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 908us total 57.286ms
09-09 13:41:42.232   838  1864 I ActivityManager: Process com.google.android.music:main (pid 7124) has died
,09-09 13:41:42.318  7433  7433 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:41:42.318  7433  7433 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-09 13:41:42.318  7433  7433 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 13:41:42.319  7433  7433 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-09 13:41:42.319  7433  7433 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-09 13:41:42.452  7433  7433 I IndexDatabaseHelper: Using schema version: 115
,09-09 13:41:42.455  7433  7433 I IndexDatabaseHelper: Index is fine
,09-09 13:41:42.515  7406  7406 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-09 13:41:42.516  7406  7406 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-09 13:41:42.516  7406  7406 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-09 13:41:42.606  7406  7406 I UEI.SmartControl: --- Selecting new region: 2
,09-09 13:41:42.607  7406  7406 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
,09-09 13:41:42.615  7406  7406 D UEI.SmartControl: Platform has CIR...
09-09 13:41:42.616  7406  7406 D UEI.SmartControl: NO CIR support, need to check package...
09-09 13:41:42.617  7406  7406 I UEI.SmartControl: Model: LG-D722 uses JNI
09-09 13:41:42.625  7406  7406 D UEI.SmartControl: QS Service created
,09-09 13:41:42.664   838  1844 I art     : Explicit concurrent mark sweep GC freed 28118(1471KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 7.015ms total 172.244ms
,09-09 13:41:42.706  7406  7406 E UEI.SmartControl: QS start get config
,09-09 13:41:42.722  7477  7477 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=37 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-09 13:41:42.785  7406  7406 D UEI.SmartControl: Loading JNI Libs...
,09-09 13:41:42.788  7406  7406 D UEI.SmartControl:  configuring local db...
09-09 13:41:42.853  7433  7433 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-09 13:41:42.864  7370  7370 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
09-09 13:41:42.869  2007  3608 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:41:42.869  2007  3628 W bt_userial: select_read return size <=0:0, exiting userial_read_thread
09-09 13:41:42.869  2007  3608 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:41:42.870  2007  3608 W bt-btif : ag scb idx 1 not allocated
,09-09 13:41:42.870  2007  3608 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 13:41:42.870  2007  3608 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:41:42.870  2007  3608 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:41:42.870  2007  3608 W bt-btif : ag scb idx 1 not allocated
09-09 13:41:42.870  2007  3608 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 13:41:42.870  2007  3608 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 13:41:42.870  2007  3608 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 13:41:42.870  2007  3610 D bt_hwcfg: hw_epilog_process
09-09 13:41:42.870  2007  2164 I bt_userial_vendor: device fd = 67 close
,09-09 13:41:42.872   838  1899 I ActivityManager: Process com.lge.qremote (pid 6941) has died
09-09 13:41:42.878  2007  2007 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 13:41:42.879  2007  2007 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:42.879  2007  2007 V BluetoothPbapReceiver: ***********state = 13
09-09 13:41:42.880  2007  2007 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-09 13:41:42.882  2007  2007 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:42.882  2007  2007 V BluetoothPbapService: state: 13
09-09 13:41:42.882  2007  2007 V BluetoothPbapService: Pbap Service closeService in
09-09 13:41:42.884  2007  2164 E bt_vendor: [BTUI] Proto is enabled. Set Proto disable!!
,09-09 13:41:42.885  2007  2007 V BluetoothPbapService: successfully stopped pbap service
09-09 13:41:42.885  2007  2007 V BluetoothPbapService: Pbap Service closeService out
09-09 13:41:42.885  2007  2007 V BluetoothPbapService: Pbap Service onDestroy
09-09 13:41:42.885  2007  2007 V BluetoothPbapService: Pbap Service closeService in
09-09 13:41:42.885  2007  2007 V BluetoothPbapService: Pbap Service closeService out
09-09 13:41:42.885  2007  2007 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-09 13:41:42.894   838  1017 D BluetoothManagerService: Message: 20
,09-09 13:41:42.894   838  1017 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b6f24ae:true
09-09 13:41:42.910  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
,09-09 13:41:42.930   838  1017 D BluetoothManagerService: Message: 30
,09-09 13:41:42.934   838  1017 D BluetoothManagerService: Message: 30
09-09 13:41:42.936  7433  7433 D LocalBluetoothProfileManager: Adding local MAP profile
09-09 13:41:42.951  7433  7433 D BluetoothMap: Create BluetoothMap proxy object
,09-09 13:41:42.951   838  1017 D BluetoothManagerService: Message: 30
09-09 13:41:42.957   838  1017 D BluetoothManagerService: Message: 30
09-09 13:41:42.959  7433  7433 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-09 13:41:42.970  7433  7433 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,09-09 13:41:42.983  7477  7477 I dex2oat : dex2oat took 258.596ms (threads: 4)
,09-09 13:41:42.990  2007  2164 I GKI_LINUX: GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
09-09 13:41:42.991  2007  3608 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-09 13:41:42.991  2007  2164 I GKI_LINUX: GKI_destroy_task(): task [BTU] terminated
09-09 13:41:42.992  2007  2164 I bt-btif : HAL bt_hal_cbacks->adapter_state_changed_cb
09-09 13:41:42.992  2007  2155 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-09 13:41:42.993  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:42.993  2007  2155 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 13:41:42.993  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:42.993  2007  2155 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 13:41:43.003  7348  7366 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:43.003  7348  7366 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:43.003  7348  7366 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:41:43.003  7348  7366 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:41:43.003  7348  7366 I Adreno-EGL: Remote Branch: 
09-09 13:41:43.003  7348  7366 I Adreno-EGL: Local Patches: 
09-09 13:41:43.003  7348  7366 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:41:43.005  2007  2155 D BtSettings.ProfileConfig: Unable to read settings
09-09 13:41:43.005  2007  2155 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-09 13:41:43.005  2007  2155 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
09-09 13:41:43.005  2007  2155 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
09-09 13:41:43.005  2007  2155 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
09-09 13:41:43.005  2007  2155 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
09-09 13:41:43.005  2007  2155 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
09-09 13:41:43.005  2007  2155 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
09-09 13:41:43.005  2007  2155 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
09-09 13:41:43.005  2007  2155 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
09-09 13:41:43.005  2007  2155 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:43.005  2007  2155 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:41:43.005  2007  2155 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 13:41:43.006  2007  2155 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-09 13:41:43.006  2007  2155 D BluetoothAdapterService(490245822): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
09-09 13:41:43.009  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:43.009  2007  2155 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 13:41:43.009  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:43.009  2007  2155 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 13:41:43.009  2007  2155 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-09 13:41:43.009  2007  2155 D BluetoothAdapterService(490245822): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
09-09 13:41:43.011  2007  2007 D HeadsetService: Received stop request...Stopping profile...
09-09 13:41:43.012  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:43.012  2007  2155 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-09 13:41:43.012  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:43.012  2007  2155 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:41:43.012  2007  2155 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-09 13:41:43.012  2007  2155 D BluetoothAdapterService(490245822): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
09-09 13:41:43.015  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:43.015  2007  2155 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-09 13:41:43.015  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:43.015  2007  2155 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 13:41:43.018  2007  2155 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.Hea,lthService
09-09 13:41:43.018  2007  2155 D BluetoothAdapterService(490245822): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
,09-09 13:41:43.019  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:43.019  2007  2155 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-09 13:41:43.019  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:43.019  2007  2155 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 13:41:43.020  2007  2007 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 13:41:43.021  2007  3528 D HeadsetStateMachine: Exit Disconnected: -1
09-09 13:41:43.021  2007  2155 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-09 13:41:43.021  2007  2155 D BluetoothAdapterService(490245822): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
09-09 13:41:43.022  2007  2007 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 13:41:43.023  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:43.023  2007  2155 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-09 13:41:43.023  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:43.023  2007  2155 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-09 13:41:43.023  2007  2155 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-09 13:41:43.024  2007  2155 D BluetoothAdapterService(490245822): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
09-09 13:41:43.024  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:43.025  2007  2155 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 13:41:43.025  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:43.025  2007  2155 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:41:43.026  2007  2155 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-09 13:41:43.026  2007  2155 D BluetoothAdapterService(490245822): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
09-09 13:41:43.027  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:43.027  2007  2155 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-09 13:41:43.027  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:43.027  2007  2155 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 13:41:43.027  2007  2155 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-09 13:41:43.027  2007  2155 D BluetoothAdapterService(490245822): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
09-09 13:41:43.028  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:43.028  2007  2155 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
09-09 13:41:43.028  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:43.028  2007  2155 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
09-09 13:41:43.029  2007  2155 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.ftp.FTPService
09-09 13:41:43.029  2007  2155 D BluetoothAdapterService(490245822): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
09-09 13:41:43.030  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:43.030  2007  2007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d388ebe
09-09, 13:41:43.030  2007  2155 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
09-09 13:41:43.030  2007  2155 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-09 13:41:43.030  2007  2155 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
,09-09 13:41:43.032  2007  2155 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.opp.OppService
09-09 13:41:43.032  2007  2155 D BluetoothAdapterService(490245822): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
09-09 13:41:43.033   838   838 D BluetoothHeadset: Proxy object disconnected
09-09 13:41:43.033  1748  1748 D BluetoothHeadset: Proxy object disconnected
09-09 13:41:43.036   838   838 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-09 13:41:43.036  2007  2155 D BluetoothAdapterState: Stopping profile services that were post enabled
09-09 13:41:43.037  2007  2007 D A2dpService: Received stop request...Stopping profile...
09-09 13:41:43.039  1748  1748 D BluetoothHeadset: Proxy object disconnected
09-09 13:41:43.040  2007  3569 D A2dpStateMachine: Exit Disconnected: -1
,09-09 13:41:43.042  1748  1748 D BluetoothHeadset: Proxy object disconnected
09-09 13:41:43.047  7433  7433 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
09-09 13:41:43.050  7433  7433 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-09 13:41:43.053  2007  2007 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-09 13:41:43.053  2007  2007 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-09 13:41:43.055  2007  2007 D LGBluetoothPowerControlManager: [BTUI] terminate
09-09 13:41:43.062  7370  7370 I LibraryLoader: Time to load native libraries: 12 ms (timestamps 208-220)
09-09 13:41:43.062  7370  7370 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:41:43.064   838  1017 D BluetoothManagerService: Message: 31
09-09 13:41:43.065  2007  2007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d388ebe
09-09 13:41:43.066   838   838 D BluetoothA2dp: Proxy object disconnected
09-09 13:41:43.066   838   838 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-09 13:41:43.067  7433  7433 D DockEventReceiver: finishStartingService: stopping service
09-09 13:41:43.067  2007  2007 D HidService: Received stop request...Stopping profile...
09-09 13:41:43.067  2007  2007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d388ebe
09-09 13:41:43.068  2007  2007 D HealthService: Received stop request...Stopping profile...
09-09 13:41:43.068  2007  2007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d388ebe
09-09 13:41:43.070  2007  2007 D PanService: Received stop request...Stopping profile...
09-09 13:41:43.070  2007  2007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d388ebe
09-09 13:41:43.073  2007  2007 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 13:41:43.074  2007  2007 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 13:41:43.074  2007  2007 D BtGatt.GattService: stop()
09-09 13:41:43.074  2007  2007 D BtGatt.AdvertiseManager: advertise clients cleared
09-09 13:41:43.075  2007  2007 D LGBluetoothGattAdapter: [BTUI] LGBluetoothGattAdapter cleanup
09-09 13:41:43.075  2007  2007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d388ebe
09-09 13:41:43.077  2007  2007 D BluetoothMapService: Received stop request...Stopping profile...
09-09 13:41:43.077  2007  2007 D BluetoothMapService: stop()
,09-09 13:41:43.079  2007  2007 D BluetoothMapEmailAppObserver: deinitObservers()
09-09 13:41:43.079  2007  2007 D BluetoothMapEmailAppObserver: removeReceiver()
09-09 13:41:43.081  2007  2007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d388ebe
09-09 13:41:43.085  7433  7433 D BluetoothInputDevice: Proxy object connected
09-09 13:41:43.088  7433  7433 D HidProfile: Bluetooth service connected
09-09 13:41:43.088  2007  2007 D SapService: Received stop request...Stopping profile...
,09-09 13:41:43.088  2007  2007 D SapService: Stopping Bluetooth SapService
,09-09 13:41:43.088  2007  2007 D LGBluetoothSapAdapter: [BTUI] LGBluetoothSapAdapter cleanup
09-09 13:41:43.088  2007  2007 D LGBluetoothSapManager: [BTUI] terminateSapManager
09-09 13:41:43.089  2007  2007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d388ebe
09-09 13:41:43.090  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:43.091  2007  2007 D **BluetoothFTPService: Received stop request...Stopping profile...
09-09 13:41:43.091  2007  2007 D **BluetoothFTPService: Stopping Bluetooth FTP Service
09-09 13:41:43.091  2007  2007 V BluetoothFTPServiceJni: closeFtpServerNative
09-09 13:41:43.092  7433  7433 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:41:43.092  2007  2007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d388ebe
09-09 13:41:43.093  7433  7433 D PanProfile: Bluetooth service connected
09-09 13:41:43.093  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - Message: 1
09-09 13:41:43.093  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-09 13:41:43.093  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,09-09 13:41:43.093  2007  2007 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:41:43.094  2007  2007 D BluetoothAdapterState: isTurningOffRadio()=false
09-09 13:41:43.094  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:41:43.094  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-09 13:41:43.095  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:43.095  7433  7433 D BluetoothMap: Proxy object connected
09-09 13:41:43.096  7433  7433 D MapProfile: Bluetooth service connected
09-09 13:41:43.096  7433  7433 D BluetoothMap: getConnectedDevices()
09-09 13:41:43.097  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:43.097  7433  7433 D BluetoothMap: Bluetooth is Not enabled
09-09 13:41:43.097  7433  7433 D BluetoothInputDevice: Proxy object disconnected
09-09 13:41:43.097  7433  7433 D HidProfile: Bluetooth service disconnected
09-09 13:41:43.097  7433  7433 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 13:41:43.097  7433  7433 D PanProfile: Bluetooth service disconnected
09-09 13:41:43.097  7433  7433 D BluetoothMap: Proxy object disconnected
09-09 13:41:43.097  7433  7433 D MapProfile: Bluetooth service disconnected
09-09 13:41:43.097  1748  1748 D LgeBluetoothSimManager: [BTUI] SAP_DISABLE_EVT
09-09 13:41:43.098  7433  7433 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-09 13:41:43.099  7433  7433 I NotificationManager: com.android.settings: cancel(17301632) by com.android.settings
09-09 13:41:43.099  2007  2007 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-09 13:41:43.099  2007  2007 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.099  2007  2007 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.100  7433  7433 I NotificationManager: com.android.settings: cancel(-1000001) by com.android.settings
09-09 13:41:43.100  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.100  7433  7433 I NotificationManager: com.android.settings: cancel(-1000011) by com.android.settings
09-09 13:41:43.101  7433  7433 I NotificationManager: com.android.settings: cancel(-1000021) by com.android.settings
09-09 13:41:43.101  2007  2007 D HeadsetStateMachine: Unbinding service...
09-09 13:41:43.101  7433  7433 I NotificationManager: com.android.settings: cancel(-1000031) by com.android.settings
09-09 13:41:43.102  7433  7433 I NotificationManager: com.android.settings: cancel(-1000041) by com.android.settings
09-09 13:41:43.102  2007  2007 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 13:41:43.102  2007  2007 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 13:41:43.102  2007  2007 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 13:41:43.102  2007  2007 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 13:41:43.102  2007  2007 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 13:41:43.102  2007  2007 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 13:41:43.102  2007  2007 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 13:41:43.103  2007  2007 D **OppService: Received stop request...Stopping profile...
09-09 13:41:43.103  2007  2007 D OppService: Stopping Bluetooth OppService
09-09 13:41:43.103  2007  2007 D OppService: cleanup OPP Service
09-09 13:41:43.103  2007  2007 W BluetoothOPPServiceJni: Cleaning up Bluetooth Opp Interface...
09-09 13:41:43.103  2007  2007 ,W BluetoothOPPServiceJni: Cleaning up Bluetooth OPP callback object
09-09 13:41:43.104  2007  2007 D OppService: remove callbacks and handler
09-09 13:41:43.104  2007  2007 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-09 13:41:43.104  2007  2007 D OppService: cleanup done
,09-09 13:41:43.104  2007  2007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d388ebe
09-09 13:41:43.105  7433  7433 D BluetoothPermissionRequest: onReceive
09-09 13:41:43.106  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - Message: 1
09-09 13:41:43.107  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-09 13:41:43.107  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-09 13:41:43.107  2007  2007 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:41:43.107  2007  2007 D BluetoothAdapterState: isTurningOffRadio()=false
09-09 13:41:43.107  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:41:43.107  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-09 13:41:43.107  2007  2007 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-09 13:41:43.107  2007  2007 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.107  2007  2007 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.107  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.107  2007  2007 I BluetoothA2dpServiceJni: cleanupNative
09-09 13:41:43.107  2007  2007 I GKI_LINUX: GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
09-09 13:41:43.107  2007  3668 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-09 13:41:43.108  2007  2007 I GKI_LINUX: GKI_destroy_task(): task [A2DP-MEDIA] terminated
09-09 13:41:43.109  7433  7433 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-09 13:41:43.109  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - Message: 1
09-09 13:41:43.109  7433  7433 I NotificationManager: com.android.settings: cancel(17301632) by com.android.settings
09-09 13:41:43.109  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-09 13:41:43.109  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-09 13:41:43.109  2007  2007 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:41:43.109  2007  2007 D BluetoothAdapterState: isTurningOffRadio()=false
09-09 13:41:43.109  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:41:43.109  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-09 13:41:43.109  2007  2007 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-09 13:41:43.110  2007  2007 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.110  2007  2007 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.110  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.110  7433  7433 I NotificationManager: com.android.settings: cancel(-1000001) by com.android.settings
09-09 13:41:43.111  7433  7433 I NotificationManager: com.android.settings: cancel(-1000011) by com.android.settings
09-09 13:41:43.112  2007  2007 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 13:41:43.112  2007  2007 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 13:41:43.113  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - Messag,e: 1
09-09 13:41:43.113  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-09 13:41:43.113  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-09 13:41:43.113  2007  2007 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:41:43.113  2007  2007 D BluetoothAdapterState: isTurningOffRadio()=false
09-09 13:41:43.113  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:41:43.113  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-09 13:41:43.113  2007  2007 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-09 13:41:43.113  2007  2007 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.113  2007  2007 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.113  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.113  2007  2007 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 13:41:43.113  2007  2007 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 13:41:43.113  2007  2007 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 13:41:43.113  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - Message: 1
09-09 13:41:43.113  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-09 13:41:43.113  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-09 13:41:43.113  2007  2007 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:41:43.113  2007  2007 D BluetoothAdapterState: isTurningOffRadio()=false
09-09 13:41:43.113  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:41:43.114  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-09 13:41:43.114  2007  2007 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-09 13:41:43.114  2007  2007 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.114  2007  2007 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.114  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.114  2007  2007 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 13:41:43.114  2007  2007 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 13:41:43.115  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - Message: 1
09-09 13:41:43.115  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,09-09 13:41:43.115  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
09-09 13:41:43.115  2007  2007 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:41:43.115  2007  2007 D BluetoothAdapterState: isTurningOffRadio()=false
09-09 13:41:43.115  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:41:43.115  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-09 13:41:43.115  2007  2007 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-09 13:41:43.115  2007  2007 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.115  2007  2007 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.115  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.115  2007  2007 V BluetoothMapService: Handler(): got msg=4
09-09 13:41:43.115  2007  2007 D BluetoothMapService: MAP Service closeService in
,09-09 13:41:43.115  2007  2007 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 13:41:43.116  2007  2007 V BluetoothMapService: MAP Service closeService out
09-09 13:41:43.116  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - Message: 1
09-09 13:41:43.116  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-09 13:41:43.116  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-09 13:41:43.116  2007  2007 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:41:43.116  2007  2007 D BluetoothAdapterState: isTurningOffRadio()=false
09-09 13:41:43.116  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:41:43.116  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
,09-09 13:41:43.116  2007  2007 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-09 13:41:43.116  2007  2007 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.116  2007  2007 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.116  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.116  2007  2007 D BluetoothMapService: cleanup()
09-09 13:41:43.116  2007  2007 D BluetoothMapService: MAP Service closeService in
09-09 13:41:43.116  2007  2007 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 13:41:43.116  2007  2007 V BluetoothMapService: MAP Service closeService out
,09-09 13:41:43.116  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - Message: 1
09-09 13:41:43.116  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-09 13:41:43.116  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-09 13:41:43.116  2007  2007 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:41:43.116  2007  2007 D BluetoothAdapterState: isTurningOffRadio()=false
09-09 13:41:43.116  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:41:43.116  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-09 13:41:43.116  2007  2007 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
,09-09 13:41:43.117  2007  2007 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.117  2007  2007 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.117  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.117  2007  2007 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
09-09 13:41:43.117  2007  2007 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
09-09 13:41:43.117  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - Message: 1
09-09 13:41:43.117  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,09-09 13:41:43.117  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
09-09 13:41:43.117  2007  2007 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:41:43.117  2007  2007 D BluetoothAdapterState: isTurningOffRadio()=false,
09-09 13:41:43.117  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:41:43.117  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
,09-09 13:41:43.117  2007  2007 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-09 13:41:43.117  2007  2007 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.117  2007  2007 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.117  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-09 13:41:43.117  2007  2007 D BluetoothFTPService: cleanup FTP Service
09-09 13:41:43.117  2007  2007 V BluetoothFTPServiceJni: closeFtpServerNative
09-09 13:41:43.117  2007  2007 V BluetoothFTPServiceJni: cleanupNative
,09-09 13:41:43.117  2007  2007 W BluetoothFTPServiceJni: Cleaning up Bluetooth FTP Server Interface...
09-09 13:41:43.117  2007  2007 W BluetoothFTPServiceJni: Cleaning up Bluetooth FTP callback object
09-09 13:41:43.117  2007  2007 D BluetoothFTPService: BluetoothFtpBinder.cleanup()
09-09 13:41:43.118  2007  2007 D BluetoothFTPService: cleanup done
09-09 13:41:43.118  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - Message: 1
09-09 13:41:43.118  2007  2007 D BluetoothAdapterService(490245822): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-09 13:41:43.118  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
,09-09 13:41:43.118  2007  2007 D BluetoothAdapterState: isTurningOnRadio()=false
09-09 13:41:43.118  2007  2007 D BluetoothAdapterState: isTurningOffRadio()=false
09-09 13:41:43.118  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-09 13:41:43.118  2007  2007 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-09 13:41:43.118  2007  2007 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-09 13:41:43.118  2007  2007 D BluetoothAdapterService(490245822): onProfileServiceStateChange() - All profile services stopped...
09-09 13:41:43.118  2007  2007 D OppService: cleanup OPP Service
,09-09 13:41:43.118  2007  2007 D OppService: remove callbacks and handler
09-09 13:41:43.118  2007  2007 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-09 13:41:43.118  2007  2007 D OppService: cleanup done
09-09 13:41:43.118  2007  2155 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-09 13:41:43.118  2007  2155 D BluetoothAdapterProperties: Setting state to 10
09-09 13:41:43.118  2007  2155 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 13:41:43.118  2007  2155 D BluetoothAdapterService(490245822): updateAdapterState() - Broadcasting state to 1 receivers.
09-09 13:41:43.119   838  1017 D BluetoothManagerService: Message: 60
,09-09 13:41:43.120   838  1017 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-09 13:41:43.120   838  1017 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-09 13:41:43.120  2007  2155 I BluetoothAdapterState: Entering OffState
09-09 13:41:43.125  7370  7370 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2cdff994}
09-09 13:41:43.125  7370  7370 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:41:43.126  7370  7370 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 13:41:43.126  1748  2579 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:41:43.132  7433  7433 I NotificationManager: com.android.settings: cancel(-1000021) by com.android.settings
,09-09 13:41:43.132  7433  7433 I NotificationManager: com.android.settings: cancel(-1000031) by com.android.settings
09-09 13:41:43.133  7433  7433 I NotificationManager: com.android.settings: cancel(-1000041) by com.android.settings
09-09 13:41:43.133  7433  7433 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-09 13:41:43.154  7370  7370 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 13:41:43.155  7370  7370 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:41:43.158  7370  7370 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 13:41:43.182  7370  7370 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 13:41:43.186  7406  7406 D UEI.SmartControl:  ---- Has DB8: true
09-09 13:41:43.191  7370  7370 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:41:43.191  7370  7370 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 13:41:43.193  7370  7370 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:43.193  7370  7370 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:43.193  7370  7370 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:41:43.193  7370  7370 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:41:43.193  7370  7370 I Adreno-EGL: Remote Branch: 
09-09 13:41:43.193  7370  7370 I Adreno-EGL: Local Patches: 
09-09 13:41:43.193  7370  7370 I Adreno-EGL: Reconstruct Branch: 
09-09 13:41:43.194  7406  7406 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 13:41:43.194  7406  7406 D UEI.SmartControl: QS version = v2.7.11.1_RC1
09-09 13:41:43.195  7406  7406 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
09-09 13:41:43.202  7406  7406 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
09-09 13:41:43.209   280  1322 I WVCdm   : CdmEngine::OpenSession
,09-09 13:41:43.212   838  1359 I ActivityManager: Process com.lge.sync (pid 6918) has died
09-09 13:41:43.214  7433  7454 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 13:41:43.215   838  1017 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:41:43.215  7433  7453 D BluetoothPan: onBluetoothStateChange on: false
09-09 13:41:43.215  1748  1763 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:41:43.216  7433  7454 D BluetoothMap: onBluetoothStateChange: up=false
09-09 13:41:43.216  1748  1764 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:41:43.217  7433  7453 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 13:41:43.219   838  1017 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:41:43.219   838  1017 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,09-09 13:41:43.225  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:43.226  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:43.226  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:43.226  7433  7433 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 13:41:43.227  1802  1802 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:43.228  1802  1998 D LGBluetoothAPIService: Message: 2
09-09 13:41:43.228  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:43.229  1802  1998 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3438b185 mBinding = false
09-09 13:41:43.230  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
09-09 13:41:43.230  1375  1375 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
09-09 13:41:43.230  1802  1998 D LGBluetoothAPIService: Sending unbind request.
09-09 13:41:43.231  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:43.233  7433  7433 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-09 13:41:43.233  7433  7433 D LGBluetoothEventManager: [BTUI] clear device connection state
09-09 13:41:43.235  2007  2007 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,09-09 13:41:43.235  2007  2007 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-09 13:41:43.235  2007  2007 I NotificationManager: com.android.bluetooth: cancel(-1) by com.android.bluetooth
09-09 13:41:43.236  2007  2007 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-09 13:41:43.236  2007  2007 I NotificationManager: com.android.bluetooth: cancel(-1) by com.android.bluetooth
09-09 13:41:43.236  2007  2007 D LGBluetoothAPIServer: [BTUI] onUnbind()
09-09 13:41:43.237  2007  2007 D LGBluetoothAPIServer: [BTUI] cleanup() done
09-09 13:41:43.237  2007  2007 D LGBluetoothAPIServer: [BTUI] onDestroy()
09-09 13:41:43.237  2007  2038 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:43.238  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:43.245  2007  2007 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 13:41:43.248  2007  2007 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:43.297   838  1801 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7510 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
09-09 13:41:43.317  7406  7406 W irrc_jni: IRRCPlayer_nativeInit ++ 
09-09 13:41:43.317  7406  7406 D irrcClient: IrrcClient ++ 
09-09 13:41:43.317  7406  7406 D irrcClient: getIrrcService ++ 
09-09 13:41:43.318  7406  7406 D irrcClient: getIrrcService -- 
09-09 13:41:43.319  7406  7406 D irrcClient: IrrcClient -- 
09-09 13:41:43.319  7406  7406 W irrc_jni: IRRCPlayer_nativeInit -- 
,09-09 13:41:43.321   301   301 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 301us total 22.628ms
09-09 13:41:43.343   301   301 I art     : Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 302us total 21.892ms
,09-09 13:41:43.364   280  1599 V AudioPolicyService: registerClient() client 0xb3827b40, uid 10079
09-09 13:41:43.365   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 21.191ms
,09-09 13:41:43.369  7370  7509 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 13:41:43.383  7406  7406 D UEI.SmartControl: Services init done
09-09 13:41:43.384  7370  7370 I NSApplication: Starting up...
,09-09 13:41:43.391  7406  7535 I UEI.SmartControl: Device manager: loading config....
09-09 13:41:43.397  7406  7406 D UEI.SmartControl: QS Service init finished
,09-09 13:41:43.404  7406  7406 D UEI.SmartControl: QS Service version name: 0.1.73
09-09 13:41:43.405  7406  7406 D UEI.SmartControl: QS Service version code: 1073
09-09 13:41:43.406  7406  7406 D UEI.SmartControl: Service requested: Control
09-09 13:41:43.408  7406  7535 D UEI.SmartControl: Config is loaded...
09-09 13:41:43.426  7510  7510 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 13:41:43.432  7406  7534 D UEI.SmartControl:  ----- QS SDK is ready!!!
09-09 13:41:43.433  7406  7534 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 13:41:43.446   838  1899 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7537 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:43.452  7406  7406 D UEI.SmartControl: Request IControl service: devices are loaded...
09-09 13:41:43.559  7406  7406 D UEI.SmartControl: Service.onUnbind: IControl
09-09 13:41:43.560  7406  7406 D UEI.SmartControl: Service.onDestroy
,09-09 13:41:43.562  7406  7406 D UEI.SmartControl: Shutdown IRRCPlayer... 
09-09 13:41:43.564  1730  1730 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-09 13:41:43.569  1730  1730 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-09 13:41:43.570  7406  7406 W irrc_jni: IRRCPlayer_nativeFinalize ++ 
09-09 13:41:43.570  7406  7406 D irrcClient: ~IrrcClient ++ 
09-09 13:41:43.570  7406  7406 D irrcClient: ~IrrcClient -- 
09-09 13:41:43.570  7406  7406 W irrc_jni: IRRCPlayer_nativeFinalize -- 
09-09 13:41:43.570  7406  7406 D UEI.SmartControl: Blaster closed
09-09 13:41:43.570  7406  7406 D UEI.SmartControl: Blaster closed
09-09 13:41:43.571  7406  7406 D UEI.SmartControl: Shut down QS...
09-09 13:41:43.573  7406  7406 D UEI.SmartControl: Stopped file observer...
,09-09 13:41:43.581  7433  7433 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 13:41:43.582  7406  7406 I UEI.SmartControl: QS lib stop result = true
09-09 13:41:43.583  7406  7406 D UEI.SmartControl: QS shutdown complete
09-09 13:41:43.584  7406  7406 D UEI.SmartControl: QS Service created
09-09 13:41:43.584  2007  2007 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 13:41:43.585  2007  2007 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:43.585  2007  2007 V BluetoothPbapReceiver: ***********state = 10
09-09 13:41:43.585  7433  7433 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:41:43.599  7406  7406 E UEI.SmartControl: QS start get config
09-09 13:41:43.619  7406  7406 D UEI.SmartControl:  configuring local db...
,09-09 13:41:43.642   838  2176 I ActivityManager: Process com.lge.email (pid 7165) has died
,09-09 13:41:43.644  7433  7433 D BluetoothPermissionRequest: onReceive
09-09 13:41:43.651  7433  7433 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-09 13:41:43.652  7433  7433 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-09 13:41:43.660  2007  2007 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-09 13:41:43.661  2007  2007 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:43.668  7510  7510 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
09-09 13:41:43.672  1730  1730 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 13:41:43.680  1730  7556 D EasyUnlockInitService: Handling intent for initializer IntentService.
09-09 13:41:43.681  1730  1730 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-09 13:41:43.717  7183  7183 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
09-09 13:41:43.717  7183  7183 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-09 13:41:43.861  7406  7406 D UEI.SmartControl:  ---- Has DB8: true
,09-09 13:41:43.867  7406  7406 D UEI.SmartControl: QS start statue = true Error code = 0
,09-09 13:41:43.867  7406  7406 D UEI.SmartControl: QS version = v2.7.11.1_RC1
09-09 13:41:43.867  7406  7406 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
09-09 13:41:43.868  7406  7406 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
09-09 13:41:43.868  7406  7406 W irrc_jni: IRRCPlayer_nativeInit ++ 
09-09 13:41:43.868  7406  7406 D irrcClient: IrrcClient ++ 
09-09 13:41:43.868  7406  7406 D irrcClient: getIrrcService ++ 
09-09 13:41:43.868  7406  7406 D irrcClient: getIrrcService -- 
09-09 13:41:43.868  7406  7406 D irrcClient: IrrcClient -- 
09-09 13:41:43.868  7406  7406 W irrc_jni: IRRCPlayer_nativeInit -- 
09-09 13:41:43.869  7183  7559 D edo     : Opening database auth.proximity.permit_store...
09-09 13:41:43.869  7406  7406 D UEI.SmartControl: Services init done
09-09 13:41:43.872  1730  7556 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-09 13:41:43.873  7406  7561 I UEI.SmartControl: Device manager: loading config....
09-09 13:41:43.877  7406  7406 D UEI.SmartControl: QS Service init finished
09-09 13:41:43.878  7406  7406 D UEI.SmartControl: QS Service version name: 0.1.73
09-09 13:41:43.878  7406  7406 D UEI.SmartControl: QS Service version code: 1073
09-09 13:41:43.878  7406  7406 D UEI.SmartControl: Service requested: Control
09-09 13:41:43.879  7406  7561 D UEI.SmartControl: Config is loaded...
09-09 13:41:43.921  7406  7560 D UEI.SmartControl:  ----- QS SDK is ready!!!
09-09 13:41:43.922  7406  7560 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 13:41:43.922  7406  7406 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-09 13:41:43.964   838  1880 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7564 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:43.966   838  1783 I ActivityManager: Killing 7015:com.lge.lgdmsclient/1000 (adj 15): empty #11
,09-09 13:41:44.102   838  1844 W libprocessgroup: failed to open /acct/uid_1000/pid_7015/cgroup.procs: No such file or directory
,09-09 13:41:44.105  7406  7406 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@1d388ebe that was originally bound here
09-09 13:41:44.105  7406  7406 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@1d388ebe that was originally bound here
09-09 13:41:44.105  7406  7406 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
09-09 13:41:44.105  7406  7406 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
09-09 13:41:44.105  7406  7406 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
09-09 13:41:44.105  7406  7406 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
09-09 13:41:44.105  7406  7406 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
09-09 13:41:44.105  7406  7406 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
09-09 13:41:44.105  7406  7406 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
09-09 13:41:44.105  7406  7406 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
09-09 13:41:44.105  7406  7406 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
09-09 13:41:44.105  7406  7406 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
09-09 13:41:44.105  7406  7406 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
09-09 13:41:44.105  7406  7406 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:44.105  7406  7406 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:41:44.105  7406  7406 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
09-09 13:41:44.105  7406  7406 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:44.105  7406  7406 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:44.105  7406  7406 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
09-09 13:41:44.105  7406  7406 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,09-09 13:41:44.108  7406  7406 D UEI.SmartControl: Internal service binding...
09-09 13:41:44.231  7564  7564 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:44.531   280  1296 I WVCdm   : CdmEngine::CloseSession
,09-09 13:41:44.600   280  1322 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-09 13:41:44.601   838  1775 I ActivityManager: Killing 7224:com.lge.appbox.client/u0a11 (adj 15): empty #11
09-09 13:41:44.602   280  1296 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-09 13:41:44.602   280  1296 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-09 13:41:44.602   280  1296 I WVCdm   : CdmEngine::GenerateKeyRequest
09-09 13:41:44.607   280  1296 D WVCdm   : PrepareKeyRequest: nonce=3530278652
09-09 13:41:44.703   838  1880 W libprocessgroup: failed to open /acct/uid_10011/pid_7224/cgroup.procs: No such file or directory
,09-09 13:41:44.764   838  1359 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7593 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:44.957  7593  7593 I MusicStore: Database version: 120
,09-09 13:41:45.005   838  1284 V AlarmManager: RTC_WAKEUP set : Alarm{16899abe type 0 when 1473421305003 com.google.android.googlequicksearchbox} when 1473421305003
,09-09 13:41:45.079   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:45.079   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-09 13:41:45.079   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:45.080  7593  7593 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,09-09 13:41:45.210   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,09-09 13:41:45.210   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,09-09 13:41:45.210   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:45.210  7593  7593 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-09 13:41:45.213   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:45.213   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-09 13:41:45.213   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:45.213  7593  7593 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-09 13:41:45.253  7593  7593 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 13:41:45.254  7593  7593 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 13:41:45.297  7593  7593 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 13:41:45.383  7593  7593 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-09 13:41:45.384  7593  7593 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38c1ee2e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-09 13:41:45.384  7593  7593 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-09 13:41:45.385  7593  7593 D AndroidMusic: GMSCore installation verified
09-09 13:41:45.397  7593  7593 I ConfigStore: Config Database version: 1
,09-09 13:41:45.492   838  1844 I ActivityManager: Process com.google.android.talk (pid 7313) has died
,09-09 13:41:45.522  7593  7607 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3f0
,09-09 13:41:45.555  7593  7607 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3d0
,09-09 13:41:45.582  7593  7593 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-09 13:41:45.590  7593  7593 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
09-09 13:41:45.598  7593  7593 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 13:41:45.634  7593  7593 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 13:41:45.678   838  2176 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7627 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-09 13:41:45.740  7593  7593 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,09-09 13:41:45.748  7593  7593 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
09-09 13:41:45.807  7627  7627 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:41:45.807  7627  7627 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 13:41:45.813  7627  7627 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 13:41:45.822  7593  7612 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
,09-09 13:41:45.886  7627  7627 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-09 13:41:45.897  7627  7627 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,09-09 13:41:46.044  7627  7627 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-09 13:41:46.090   838  1801 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7655 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-09 13:41:46.170   293   354 I ThermalEngine: Sensor:pa_therm0:38000 mC
,09-09 13:41:46.194  7627  7627 I HubEmail: JNI_OnLoad()
09-09 13:41:46.194  7627  7627 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:41:46.194  7627  7627 I HubEmail: registerNatives()
09-09 13:41:46.194  7627  7627 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:41:46.194  7627  7627 I HubEmail: registerNativeMethods()
09-09 13:41:46.194  7627  7627 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:41:46.195  7627  7627 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-09 13:41:46.204  7627  7674 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:46.212   838   866 I ActivityManager: Killing 7250:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,09-09 13:41:46.315   838  2110 W libprocessgroup: failed to open /acct/uid_10038/pid_7250/cgroup.procs: No such file or directory
09-09 13:41:46.386  7655  7655 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:46.386  7655  7655 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:41:46.389  7655  7655 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:41:46.392  7655  7655 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:41:46.399  7655  7677 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:46.401  7655  7677 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-09 13:41:46.415  7655  7676 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-09 13:41:46.419  7655  7676 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-09 13:41:46.444   838  1347 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7682 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-09 13:41:46.449  7655  7676 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:41:46.487  7655  7655 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,09-09 13:41:46.488  7655  7655 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
09-09 13:41:46.488  7655  7655 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:41:46.490  7655  7655 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,09-09 13:41:46.514  7655  7655 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
09-09 13:41:46.526   838  1775 I ActivityManager: Killing 7276:com.lge.drmservice/u0a51 (adj 15): empty #11
,09-09 13:41:46.550  7682  7682 I AppUp4:AppBoxCP: onCreate
09-09 13:41:46.550  7682  7682 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-09 13:41:46.559  7682  7682 I AppUp4:DB:  setFingerPrint start
09-09 13:41:46.560  7682  7682 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
09-09 13:41:46.566  7682  7682 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
09-09 13:41:46.566  7682  7682 I AppUp4:DB:  SDK version = 21
,09-09 13:41:46.566  7682  7682 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-09 13:41:46.612   838  1347 W libprocessgroup: failed to open /acct/uid_10051/pid_7276/cgroup.procs: No such file or directory
,09-09 13:41:46.614  7682  7682 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-09 13:41:46.615  7682  7682 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 13:41:46.616  7682  7682 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:46.617  7682  7682 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 13:41:46.617  7682  7682 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 13:41:46.621  7682  7682 I AppUp4:CustModeStarterReceiver: onReceive
09-09 13:41:46.621  7682  7682 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:46.625  7682  7682 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@19b9a5c3
,09-09 13:41:46.625  7682  7682 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:41:46.631  7682  7682 D AppUp4:CustFacade: isSimDevice : true
09-09 13:41:46.632  7682  7682 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:41:46.633  7682  7682 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-09 13:41:46.633  7682  7682 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-09 13:41:46.633  7682  7699 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-09 13:41:46.633  7682  7699 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-09 13:41:46.634  7682  7699 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-09 13:41:46.635   838   867 I ActivityManager: Killing 7370:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
09-09 13:41:46.638   280   280 I WVCdm   : CdmEngine::CloseSession
,09-09 13:41:46.642   280   280 I WVCdm   : L3 Terminate.
09-09 13:41:46.741   838  2110 W libprocessgroup: failed to open /acct/uid_10079/pid_7370/cgroup.procs: No such file or directory
,09-09 13:41:46.742  3150  3150 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-09 13:41:46.742  3150  3150 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:46.742  3150  3150 I LgeMiscReceiver: networkInfo.isConnected() = false
09-09 13:41:46.787   838  1819 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7702 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,09-09 13:41:46.865  7406  7420 E UEI.SmartControl: file observer is disposed!
,09-09 13:41:46.873  7702  7702 D PhoneMonitor: Register our PhoneStateListener
09-09 13:41:46.885  7702  7702 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 13:41:46.886  7702  7702 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 13:41:46.887   838  1775 I ActivityManager: Killing 7406:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,09-09 13:41:46.913   838  1783 W libprocessgroup: failed to open /acct/uid_10089/pid_7406/cgroup.procs: No such file or directory
,09-09 13:41:46.914  2720  2720 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:46.918  2720  2720 V DownloadManager: DownloadService onCreate
09-09 13:41:46.922  2720  7721 I DownloadManager: in removeSpuriousFiles
09-09 13:41:46.922  2720  2720 I NotificationManager: com.android.providers.downloads: cancelAll by com.android.providers.downloads
09-09 13:41:46.925  2720  7721 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,09-09 13:41:46.929  2720  7721 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@10e7c6fc on behalf of 2720
09-09 13:41:46.933  2720  7721 I DownloadManager: in trimDatabase
09-09 13:41:46.933  2720  7721 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-09 13:41:46.942  2720  7721 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3438b185 on behalf of 2720
,09-09 13:41:46.955  7702  7702 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-09 13:41:46.956  7702  7702 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-09 13:41:46.956  7702  7702 D TelephonyAutoProfiling: [parse] Load xml
,09-09 13:41:46.960  7702  7702 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-09 13:41:46.960  7702  7702 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
09-09 13:41:46.964   838  1359 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7728 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-09 13:41:46.967  2720  2720 V DownloadManager: DownloadService onStartCommand
,09-09 13:41:46.979  7702  7702 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-09 13:41:46.983  2720  7722 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-09 13:41:46.984  2720  7722 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3a10e80b on behalf of 2720
,09-09 13:41:47.052  2720  2720 V DownloadManager: DownloadService onDestroy
,09-09 13:41:47.056   838  1359 I ActivityManager: Killing 7537:com.android.chrome/u0a48 (adj 15): empty #11
09-09 13:41:47.073  6502  7457 E io.jxcore.node.ConnectivityMonitorTest: BT is not enabled after 5s!
,09-09 13:41:47.078  6502  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:47.120  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:47.120  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:47.120  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:47.120  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:47.120  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c94e282 removed from the list
09-09 13:41:47.120  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:47.120  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1af43d93 removed from the list
09-09 13:41:47.120  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:47.120  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:47.143   838  1347 W libprocessgroup: failed to open /acct/uid_10048/pid_7537/cgroup.procs: No such file or directory
,09-09 13:41:47.167  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:47.168  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c19c5c9 added. We now have 3 listener(s)
,09-09 13:41:47.168   838  2176 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:47.171  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-09 13:41:47.171  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:47.171  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:47.171  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:47.171  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b2a4ce added. We now have 3 listener(s)
09-09 13:41:47.171  6502  6657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:47.172  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:47.174  2863  2863 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:41:47
09-09 13:41:47.174  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:47.176  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:47.176  6502  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:47.176  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:47.176  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:47.176  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:47.176  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:47.176  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:47.176  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:47.176  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:47.176  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:47.176  6502  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:47.176  2863  2863 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 13:41:47.177  6502  6657 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:47.177  2863  2863 D WeatherAncestor: connectivity changed - connection : true
09-09 13:41:47.177  2863  2863 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 13:41:47.177  2863  2863 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:41:47
09-09 13:41:47.177   838  1864 D WifiServiceImplEx: setWifiEnabled: false pid=6502, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
09-09 13:41:47.178   838  1864 D WifiService: setWifiEnabled: false pid=6502, uid=10030
09-09 13:41:47.178  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:47.180  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:47.183  2863  2863 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:47.183  2863  2863 D WeatherService: 2 : shouldTimeTickRegistered : false
09-09 13:41:47.192   838   838 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:41:47.192   838   838 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:41:47.192   838   838 D Ulp_jni : JNI:system_update. Event-4
,09-09 13:41:47.194   838  1306 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 13:41:47.195   838  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:41:47.211   838  1305 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:47.211   838  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:47.225   838  7034 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:47.225   276  1013 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:41:47.226   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 7
,09-09 13:41:47.247   838  1924 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7752 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-09 13:41:47.258   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:47.258   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:41:47.258   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 10
09-09 13:41:47.260   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 7
09-09 13:41:47.260  1730  7116 V NativeCrypto: Read error: ssl=0xb06f3a00: I/O error during system call, Connection timed out
09-09 13:41:47.262   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:47.262   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:47.262   838  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 13:41:47.262   838  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-09 13:41:47.266   838   838 D WifiHS20: hidePasspointNotification off =false
09-09 13:41:47.266   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:47.266   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:47.266   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:41:47.269   838   838 D WifiHS20: hidePasspointNotification off =false
,09-09 13:41:47.270   838  1305 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:47.270   838  1305 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:47.271   838  1305 D LGWifiP2pService: P2pDisablingState
09-09 13:41:47.271   838  1305 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:47.271   838  1305 D LGWifiP2pService: p2p socket connection lost
09-09 13:41:47.271   838  1305 D LGWifiP2pService: P2pDisabledState
09-09 13:41:47.274   838  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 13:41:47.276   838  1305 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:47.276   838  1305 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:47.279   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:47.280   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:47.280   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:41:47.280   838   838 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 13:41:47.280   838   838 D RttService: SCAN_AVAILABLE : 1
09-09 13:41:47.281   838  1329 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:47.281   838  1328 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:47.289   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:47.289   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:47.293  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:47.294  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:47.294 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:47.294  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:41:47.295  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:47.295  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:47.295 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:47.295  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:41:47.295  1802  1802 D WfdsService: WifiP2pState is changed : false
09-09 13:41:47.296  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:47.297  1802  2129 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-09 13:41:47.297  1802  2129 D WfdsJNI : doCommand: P2P_STOP_FIND
09-09 13:41:47.298  1802  2129 D WfdsService: Set the WFDS Monitor: false
,09-09 13:41:47.323   276  1013 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:41:47.324   838  1312 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-09 13:41:47.325   838  1312 D DSQN    : disableDataServiceNotify
09-09 13:41:47.325   838  1312 D DSQN    : stop dsqn bin
09-09 13:41:47.327  1802  2129 D WfdsMonitor: WFDS Monitor is stopped
09-09 13:41:47.327  1802  7012 D CtrlSupplicant: Received on exit socket, terminate
09-09 13:41:47.327  1802  7012 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-09 13:41:47.327  1802  2129 D WfdsService: STATE : WfdsDisabledState - enter
09-09 13:41:47.327  1802  2129 D WfdsService: WFDS: Scanner is paused
09-09 13:41:47.327  1802  2129 D WfdsDiscoveryStore: Clear Discovery Method Map: ScanAlwaysMode false
09-09 13:41:47.328  1802  2127 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-09 13:41:47.328  1802  7012 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-09 13:41:47.328  1802  7012 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-09 13:41:47.330   838   838 D WifiHS20: hidePasspointNotification off =false
09-09 13:41:47.331   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:47.331   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:47.331   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:41:47.332  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:47.332  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:47.332 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:47.332  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:41:47.332  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:47.333  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:47.333  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-09 13:41:47.334  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:47.334  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:47.334  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:47.334  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:47.335  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:47.336  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:47.335 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:47.336  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,09-09 13:41:47.341   838   838 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-09 13:41:47.343   838   838 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:47.343   838   838 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-09 13:41:47.344  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:47.344  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:47.344  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:47.344  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:47.344  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:47.344  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:47.344  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:47.344  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:47.344  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:47.344  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:47.344  6502  6502 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:47.346  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:47.346  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:47.347  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-09 13:41:47.347  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:47.347  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:47.347  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:47.347  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
09-09 13:41:47.347  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:47.348  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:47.348  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:47.348  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:47.348  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:47.348  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:47.348  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:47.348  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:47.348  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connect,ed/connecting to active network: false
09-09 13:41:47.348  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:47.349  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:41:47.349  6502  6502 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:47.350  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,09-09 13:41:47.351  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:47.351   838  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-09 13:41:47.351  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-09 13:41:47.351   838  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:47.351   838  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:47.351  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:47.351  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:47.351  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:47.351   838  1312 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:47.356  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:47.356  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:47.356  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:47.356  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:47.356  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:47.356  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:47.356  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:47.356  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:47.356  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:47.356  1375  1728 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 13:41:47.357  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:47.357  6502  6502 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:47.357   838  7032 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:47.357   838  7032 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:47.357   838  7032 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-09 13:41:47.358  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:47.358  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivity,IconId=(null)
09-09 13:41:47.358  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
09-09 13:41:47.358  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-09 13:41:47.360   838  1312 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-09 13:41:47.361   838  1312 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-09 13:41:47.361   838  1312 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 13:41:47.361   838  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:41:47.361   838  1312 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:47.361   838  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:41:47.361   838  1304 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 13:41:47.362   838  1017 D Tethering: MasterInitialState.processMessage what=3
09-09 13:41:47.362  1837  1837 W QCNEJ   : |CORE| No family connected
09-09 13:41:47.363   838  1304 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 13:41:47.363   838  1312 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:47.363   838  1017 D Tethering: MasterInitialState.processMessage what=3
09-09 13:41:47.363   838  1312 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:47.363   838  1312 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:41:47.365  1748  1748 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:47.365  1837  1837 W QCNEJ   : |CORE| No family connected
09-09 13:41:47.365  1748  1748 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
09-09 13:41:47.365  1837  1837 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
09-09 13:41:47.366   838  1306 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:47.366   838  1306 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:47.366   838  1312 D NetworkManagementService: Removing idletimer
09-09 13:41:47.366   838  1312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:47.368  1837  1837 I QCNEJ   : |CORE| sendDefaultNwMsg: default = -1
09-09 13:41:47.373   838  1312 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-09 13:41:47.382  1375  1375 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-09 13:41:47.387  1375  1375 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
09-09 13:41:47.389  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:47.389  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:47.389  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
09-09 13:41:47.391  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:47.391  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:47.391  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
09-09 13:41:47.405  1375  1375 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:41:47.406  1375  1375 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
,09-09 13:41:47.408  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:47.408  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:47.408  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
09-09 13:41:47.412  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:47.412  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:47.412  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
09-09 13:41:47.432   276  1006 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
,09-09 13:41:47.433   276  1006 I Netd    : M: Get netlink event, ifname: p2p0 action: 5
09-09 13:41:47.434  6959  6959 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-09 13:41:47.434  6959  6959 I wpa_supplicant: monitor socket send errors count : 1
09-09 13:41:47.434  6959  6959 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1802-4\x00 that cannot receive messages
09-09 13:41:47.435   276  1006 I Netd    : M: Get netlink event, ifname: p2p0 action: 10
09-09 13:41:47.435   276  1006 I Netd    : M: Get netlink event, ifname: p2p0 action: 7
09-09 13:41:47.436   838  7034 D DhcpStateMachine: StoppedState
09-09 13:41:47.436   838  7034 D DhcpStateMachine: StoppedState{ when=-154ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:47.436   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:47.436   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:47.450  6959  6959 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 13:41:47.452  6959  6959 W wpa_supplicant: USIM:  scard_deinit function
09-09 13:41:47.468   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:41:47.468   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:41:47.469   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:47.469   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:41:47.501   838  1783 I art     : Explicit concurrent mark sweep GC freed 36977(1691KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.075ms total 209.736ms
,09-09 13:41:47.503  1730  7116 V NativeCrypto: SSL shutdown failed: ssl=0xb06f3a00: I/O error during system call, Broken pipe
,09-09 13:41:47.512  1730  7116 E GCM     : Wifi connection closed with errorCode 20
,09-09 13:41:47.526  7752  7752 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 13:41:47.542   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,09-09 13:41:47.552   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 5
09-09 13:41:47.553  6959  6959 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-09 13:41:47.553   838  1017 D Tethering: InitialState.processMessage what=4
09-09 13:41:47.556   838  1017 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-09 13:41:47.649  7348  7366 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:47.649  7348  7366 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:47.649  7348  7366 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:41:47.649  7348  7366 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:41:47.649  7348  7366 I Adreno-EGL: Remote Branch: 
09-09 13:41:47.649  7348  7366 I Adreno-EGL: Local Patches: 
09-09 13:41:47.649  7348  7366 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:41:47.655   838  1306 D WifiOffDelayIfNotUsed: stopMonitoring
09-09 13:41:47.656  1802  1802 D WfdsService: Supplicant Connection state is changed : false
09-09 13:41:47.656  1802  2129 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-09 13:41:47.656  1802  2129 D WfdsService: Set the WFDS Monitor: false
09-09 13:41:47.656  1802  2129 D WfdsMonitor: WFDS Monitor is stopped
09-09 13:41:47.658  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:47.658  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:47.658 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:47.658  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:41:47.658   838   838 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-09 13:41:47.659   838  1310 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-09 13:41:47.659   838  1310 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-09 13:41:47.659  1730  2622 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:47.661  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:47.661  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:47.661  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
09-09 13:41:47.661  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-09 13:41:47.661  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:41:47.661  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:47.661  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:47.661  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:47.661  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:47.661  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:47.661  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:47.661  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:47.661  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:47.663  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:47.663  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:47.663  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:47.663  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:47.663  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:47.663  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:47.663  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:47.663  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:47.663  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:47.665  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:47.665  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:47.665  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:47.665  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:47.665  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:47.665  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:47.665  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:47.665  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:47.665  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:47.694  6502  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:47.696   838  1880 D WifiServiceImplEx: setWifiEnabled: true pid=6502, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
09-09 13:41:47.696   838  1880 D WifiService: setWifiEnabled: true pid=6502, uid=10030
09-09 13:41:47.706   838   838 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:41:47.706   838   838 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:41:47.706   838   838 D Ulp_jni : JNI:system_update. Event-4
09-09 13:41:47.707   838  1311 D WifiController: WifiController msg { when=-2ms what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 484ms
09-09 13:41:47.718  7348  7366 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:47.718  7348  7366 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:47.718  7348  7366 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:41:47.718  7348  7366 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:41:47.718  7348  7366 I Adreno-EGL: Remote Branch: 
09-09 13:41:47.718  7348  7366 I Adreno-EGL: Local Patches: 
09-09 13:41:47.718  7348  7366 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:41:47.742  7752  7788 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-09 13:41:47.743  7752  7788 I Babel_SMS: MmsConfig.loadMmsSettings
,09-09 13:41:47.750  7752  7788 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-09 13:41:47.750  7752  7788 I Babel_SMS: MmsConfig.loadFromDatabase
,09-09 13:41:47.776  7752  7788 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-09 13:41:47.776  7752  7788 I Babel_SMS: MmsConfig.loadFromResources
09-09 13:41:47.809  7752  7788 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-09 13:41:47.810  7752  7788 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-09 13:41:47.845  7752  7752 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
09-09 13:41:47.845  7752  7752 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
09-09 13:41:47.845  7752  7752 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
09-09 13:41:47.845  7752  7752 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
09-09 13:41:47.845  7752  7752 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
09-09 13:41:47.845  7752  7752 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
09-09 13:41:47.845  7752  7752 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
09-09 13:41:47.845  7752  7752 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
09-09 13:41:47.845  7752  7752 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
09-09 13:41:47.845  7752  7752 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
09-09 13:41:47.845  7752  7752 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
09-09 13:41:47.845  7752  7752 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
09-09 13:41:47.845  7752  7752 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
09-09 13:41:47.845  7752  7752 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
09-09 13:41:47.845  7752  7752 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
09-09 13:41:47.845  7752  7752 D SensorManager: found sensor: Motion Accel, handle=46
,09-09 13:41:47.884  7752  7770 I art     : CheckpointMarkThreadRoots callback created = 0xaaf572c0
,09-09 13:41:47.899  7183  7301 I CheckinUtil: Classify the device as Phone.
,09-09 13:41:47.904  7752  7752 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:47.906  7752  7752 I Babel_Crash: startup - clean
09-09 13:41:47.934  7752  7770 I art     : CheckpointMarkThreadRoots callback created = 0xaaf572b0
,09-09 13:41:47.956  7752  7793 I Babel   : deleted: false for 0
,09-09 13:41:47.977  7183  7301 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:47.978  7183  7301 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:41:47.980  7183  7301 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:47.980  7183  7301 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:47.980   276  1008 E BandwidthController: [LG DATA] No such appUid: 10006
09-09 13:41:47.980   276  1008 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-09 13:41:47.981   276  7796 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
09-09 13:41:47.981   276  7796 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:47.981   276  7796 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
09-09 13:41:47.982   838  1015 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-09 13:41:47.984  7183  7301 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-09 13:41:47.994  7183  7301 I CheckinChimeraService: Checking schedule, now: 1473421307994 next: 1473421317984
09-09 13:41:47.994  7183  7301 I CheckinChimeraService: active receiver: disabled
,09-09 13:41:48.053   838  1864 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7798 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:48.055  7183  7797 I CheckinChimeraService: Checking schedule, now: 1473421308055 next: 1473421317984
09-09 13:41:48.055  7183  7797 I CheckinChimeraService: active receiver: disabled
,09-09 13:41:48.160  7752  7752 W AudioCapabilities: Unsupported mime audio/x-lg-flac
09-09 13:41:48.162  7752  7752 W AudioCapabilities: Unsupported mime audio/adpcm
09-09 13:41:48.163  7752  7752 W AudioCapabilities: Unsupported mime audio/g726
09-09 13:41:48.164  7752  7752 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-09 13:41:48.170  7752  7752 W AudioCapabilities: Unsupported mime audio/wma-voice
09-09 13:41:48.173  7752  7752 W VideoCapabilities: Unsupported mime video/mjpg
09-09 13:41:48.175  7752  7752 W VideoCapabilities: Unsupported mime video/theora
,09-09 13:41:48.196   838  1311 D WifiController: DEFERRED_TOGGLE handled
,09-09 13:41:48.197   838  1306 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-09 13:41:48.198   838  1306 E WifiHW  : Wifi MAC Address = a0:39:f7:70:12:80
09-09 13:41:48.198   838  1306 E WifiHW  : wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
09-09 13:41:48.198   838  1306 E WifiHW  : band=b
09-09 13:41:48.198   838  1306 E WifiHW  : ": cur_etheraddr=a0:39:f7:70:12:80
09-09 13:41:48.199   276  1013 D SoftapController: Softap fwReload - Ok
09-09 13:41:48.200   838  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:48.200   838  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:48.201   276  1013 D CommandListener: Setting iface cfg
09-09 13:41:48.201   276  1013 D CommandListener: Trying to bring down wlan0
09-09 13:41:48.201   276  1013 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:41:48.202  7752  7752 W AudioCapabilities: Unsupported mime audio/evrc
09-09 13:41:48.205   838  1306 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-09 13:41:48.209  7752  7752 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 13:41:48.211  7752  7752 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:41:48.213   838  1306 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-09 13:41:48.214   838  1306 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
09-09 13:41:48.219  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:48.219   838   838 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-09 13:41:48.220  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:48.221  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:48.22 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:48.221  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:41:48.221  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:48.225  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:48.225  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:48.225  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:48.226  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
09-09 13:41:48.226  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-09 13:41:48.229  7752  7752 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-09 13:41:48.230  7752  7752 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 13:41:48.231  7752  7752 W AudioCapabilities: Unsupported mime audio/evrc
09-09 13:41:48.248  7815  7815 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 13:41:48.256  7752  7752 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-09 13:41:48.280  7752  7752 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 13:41:48.287  7752  7752 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:41:48.289  7752  7752 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:41:48.293  7752  7752 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:41:48.298  7752  7752 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:41:48.299  7815  7815 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 13:41:48.300  7815  7815 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-09 13:41:48.310  7752  7752 I vclib   : onServiceConnected
09-09 13:41:48.311  7752  7752 W Babel   : Attempted to change video mute state without an active call.
,09-09 13:41:48.316  7752  7818 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
09-09 13:41:48.323   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:48.323   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 13:41:48.323   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:48.324  7798  7820 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-09 13:41:48.328   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:48.328   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:41:48.328   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:48.330  7752  7752 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
09-09 13:41:48.330  7798  7820 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 13:41:48.331   838  1347 I ActivityManager: Killing 7433:com.android.settings/1000 (adj 15): empty #11
09-09 13:41:48.348  7798  7798 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 13:41:48.348  7798  7798 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 13:41:48.348  7798  7798 I GAv4    :   adb logcat -s GAv4
,09-09 13:41:48.353   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:48.353   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 13:41:48.353   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:48.353  7798  7821 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-09 13:41:48.356   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:48.356   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:41:48.356   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:48.356  7798  7821 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 13:41:48.426   838   866 W libprocessgroup: failed to open /acct/uid_1000/pid_7433/cgroup.procs: No such file or directory
,09-09 13:41:48.429  7798  7798 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
09-09 13:41:48.459  7798  7798 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:41:48.463  7798  7823 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:41:48.702  7798  7798 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,09-09 13:41:48.740  7798  7798 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5896-5898)
,09-09 13:41:48.740  7798  7798 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 13:41:48.746  7798  7798 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2cbf4ba6}
,09-09 13:41:48.747  7798  7798 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:41:48.747  7798  7798 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 13:41:48.761  7798  7798 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 13:41:48.762  7798  7798 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:41:48.764  7798  7798 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 13:41:49.189   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:41:49.189   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,09-09 13:41:49.197   838  1017 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 13:41:49.212  7798  7798 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-09 13:41:49.217  7798  7798 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:41:49.217  7798  7798 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 13:41:49.218  7798  7798 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:49.218  7798  7798 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:49.218  7798  7798 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:41:49.218  7798  7798 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:41:49.218  7798  7798 I Adreno-EGL: Remote Branch: 
09-09 13:41:49.218  7798  7798 I Adreno-EGL: Local Patches: 
09-09 13:41:49.218  7798  7798 I Adreno-EGL: Reconstruct Branch: 
09-09 13:41:49.229  7815  7815 E wpa_supplicant: USIM:  scard_init function
,09-09 13:41:49.232  7815  7815 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 13:41:49.233   276  1006 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
09-09 13:41:49.234   276  1006 I Netd    : M: Get netlink event, ifname: p2p0 action: 9
09-09 13:41:49.235   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:49.235   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:49.235   276  1006 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
09-09 13:41:49.265  7815  7815 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-09 13:41:49.276   838  1306 D WifiStateMachine: MAC Addr from driver = a0:39:f7:70:12:80
09-09 13:41:49.276   838  1306 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-09 13:41:49.277   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.277   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.277   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.277   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.277   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,09-09 13:41:49.283   838   838 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-09 13:41:49.283   838  1310 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-09 13:41:49.283   838   838 E WifiServerServiceExt: sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
09-09 13:41:49.285  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:49.285  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:49.285  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:49.285  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:49.285  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:49.285  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:49.285  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:49.285  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:49.285  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:49.281  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:49.286  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:49.286  6502  6502 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:49.286  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:49.286 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:49.286  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:41:49.299  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:49.299  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:49.299  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-09 13:41:49.299  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-09 13:41:49.301  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:49.301  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:49.301  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:49.301  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:49.301  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:49.301  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:49.301  6502  6502 V io.jxcore.node.Connectiv,ityMonitor:     - BSSID name: null
09-09 13:41:49.301  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:49.301  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:49.301  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:49.302  6502  6502 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:49.306  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:49.307  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:49.307  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:49.307  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:49.307  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:49.307  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:49.307  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:49.307  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:49.307  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:49.307  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:49.307  6502  6502 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:49.308   838  1306 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-09 13:41:49.309  7815  7815 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-09 13:41:49.310   838  1306 D WifiStateMachine: enableVerboseLogging : level 2
09-09 13:41:49.312   280  1322 V AudioPolicyService: registerClient() client 0xb4027900, uid 10079
09-09 13:41:49.312  7798  7858 W AudioManagerAndroid: Requires BLUETOOTH permission
09-09 13:41:49.314  1802  1802 D WfdsService: Supplicant Connection state is changed : true
09-09 13:41:49.314  1802  2129 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
,09-09 13:41:49.314  1802  2129 D WfdsService: Set the WFDS Monitor: true
09-09 13:41:49.314  1802  2129 D WfdsMonitor: WfdsMonitorThread create
09-09 13:41:49.314  1802  2129 D WfdsMonitor: WFDS Monitor is created and started
09-09 13:41:49.315  1802  2129 D WfdsService: WiFi: Supplicant connection re-established
09-09 13:41:49.315   838  1306 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:41:49.316   838  1306 D WifiNative-HAL: Setting external_sim to 1
09-09 13:41:49.317   838  1306 I WifiNative-HAL: startHal
09-09 13:41:49.318  1802  7860 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-09 13:41:49.318   838  1306 D wifi    : setting scan oui 0xb050a3a0
09-09 13:41:49.318   838  1306 D WifiHAL : Sending mac address OUI
09-09 13:41:49.318   838  1306 E WifiHAL : failed to set scanning mac OUI; result = -95
09-09 13:41:49.318   838  1306 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:41:49.319   838  1306 I WifiNative-HAL: startHal
09-09 13:41:49.319   838  1306 D wifi    : setting scan oui 0xb050a3a0
09-09 13:41:49.319   838  1306 D WifiHAL : Sending mac address OUI
09-09 13:41:49.319   838  1306 E WifiHAL : failed to set scanning mac OUI; result = -95
09-09 13:41:49.320  1802  7860 E CtrlSupplicant: Succeed to open control connection
09-09 13:41:49.320  1802  7860 E CtrlSupplicant: Succeed to open monitor connection
09-09 13:41:49.321  1802  7860 D WfdsMonitor: Supplicant connection established
09-09 13:41:49.322  7752  7752 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.324  1802  2129 D WfdsService: Connected to the supplicant for wfds
09-09 13:41:49.338  7798  7798 I NSApplication: Starting up...
,09-09 13:41:49.342   838  1305 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.343   838   838 D WifiScanningService: SCAN_AVAILABLE : 3
09-09 13:41:49.343   838   838 D RttService: SCAN_AVAILABLE : 3
09-09 13:41:49.344   838  1328 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.344   838  1328 I WifiNative-HAL: startHal
09-09 13:41:49.344   838  1328 D wifi    : getting scan capabilities on interface[0] = 0xb050a3a0
09-09 13:41:49.344   838  1328 D WifiHAL : Creating message to get scan capablities; iface = 24
09-09 13:41:49.344   838  1328 D wifi    : failed to get capabilities : -95
09-09 13:41:49.344   838  1328 E WifiScanningService: could not get scan capabilities
09-09 13:41:49.344   838  1329 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.344   838  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:49.345   838  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:49.345   276  1013 D CommandListener: Setting iface cfg
09-09 13:41:49.345   276  1013 D CommandListener: Trying to bring up p2p0
09-09 13:41:49.345   838  1306 I WifiServerServiceExt: set CMD_ADD_DEFAULT_PROFILE
09-09 13:41:49.345   838  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 13:41:49.345   838  1305 D LGWifiP2pService: P2pEnablingState
09-09 13:41:49.345   838  1305 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.345   838  1305 D LGWifiP2pService: P2p socket connection successful
09-09 13:41:49.345   838  1305 D LGWifiP2pService: P2pEnabledState
09-09 13:41:49.346   838  1306 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-09 13:41:49.346   838  1305 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-09 13:41:49.346   838  1305 D LGWifiP2pService: before postfix = G3s-1
09-09 13:41:49.346  7815  7815 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-09 13:41:49.348   838  1306 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-09 13:41:49.348  7815  7815 E wpa_supplicant: disconnect_rssi_lvl: -100
09-09 13:41:49.350   838  1305 D WifiServerServiceExt: postfix byte check : 5
09-09 13:41:49.350   838  1305 D LGWifiP2pService: after postfix = G3s-1
09-09 13:41:49.350   838  1306 I WifiServerServiceExt: set CMD_SET_FRAMEWORK_AUTO_JOIN 0
09-09 13:41:49.351  7815  7815 E wpa_supplicant: wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
,09-09 13:41:49.353   838  1305 D WifiNative-HAL: p2pGetDeviceAddress
09-09 13:41:49.354   838  1305 D WifiNative-HAL: p2pGetDeviceAddress returning a2:39:f7:70:12:80
,09-09 13:41:49.356   838  1305 D LGWifiP2pService: DeviceAddress: a2:39:f7:70:12:80
09-09 13:41:49.362   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.362   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.362   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 13:41:49.363  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:49.364  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:49.367  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:49.367  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:49.367  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-09 13:41:49.367  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:49.367  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:49.367  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:49.368  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:49.363 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:49.368  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,09-09 13:41:49.370   838  1306 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
09-09 13:41:49.372  1802  1802 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-09 13:41:49.372  1802  1802 D WfdsService: Update P2p Interface State: 3
09-09 13:41:49.384   838  1305 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,09-09 13:41:49.408  7815  7815 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,09-09 13:41:49.410  7815  7815 I wpa_supplicant: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2437 MHz)
,09-09 13:41:49.413   838  1775 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7874 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:41:49.435   301   301 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 20.959ms
,09-09 13:41:49.443   838  1775 I ActivityManager: Killing 7593:com.google.android.music:main/u0a81 (adj 15): empty #11
09-09 13:41:49.458   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 22.763ms
,09-09 13:41:49.480   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 22.102ms
,09-09 13:41:49.497   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:41:49.497   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:41:49.497   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,09-09 13:41:49.498  7815  7815 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-09 13:41:49.529  7815  7815 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:41:49.529  7815  7815 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-09 13:41:49.530   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-09 13:41:49.562   838  1775 I ActivityManager: Killing 7564:com.google.android.apps.plus/u0a86 (adj 15): empty #12
,09-09 13:41:49.592   838  1775 I ActivityManager: Killing 7510:com.lge.settings.easy/1000 (adj 15): empty #13
,09-09 13:41:49.607   838  1305 D LGWifiP2pService: sending p2p connection changed broadcast
09-09 13:41:49.607   838  1305 D LGWifiP2pService: InactiveState
09-09 13:41:49.607   838  2110 W libprocessgroup: failed to open /acct/uid_10081/pid_7593/cgroup.procs: No such file or directory
,09-09 13:41:49.607   838  1305 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.607   838  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.607   838  1305 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.607   838  1305 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.607   838  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.607   838  1305 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.608   838   838 E WifiServerServiceExt: No p2p device connected
09-09 13:41:49.613   838  1819 W libprocessgroup: failed to open /acct/uid_10086/pid_7564/cgroup.procs: No such file or directory
09-09 13:41:49.614   838  1801 W libprocessgroup: failed to open /acct/uid_1000/pid_7510/cgroup.procs: No such file or directory
09-09 13:41:49.616  1802  1802 D WfdsService: WifiP2pState is changed : true
09-09 13:41:49.616  1802  2129 D WfdsService: Receive the WFDS_ENABLE Method
09-09 13:41:49.616  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
09-09 13:41:49.616  1802  2129 D WfdsService: Set the WFDS Monitor: true
09-09 13:41:49.616  1802  2129 D WfdsService: Connected to the supplicant for wfds
09-09 13:41:49.616  1802  2129 D WfdsJNI : doCommand: WFDS_SET TRUE
09-09 13:41:49.617  7815  7815 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-09 13:41:49.617  1802  1802 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-09 13:41:49.617  1802  2129 D WfdsJNI : doCommand: WFDS_CLEAR_PD_INFO
09-09 13:41:49.617  7815  7815 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
09-09 13:41:49.617  1802  2129 D WfdsJNI : wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
09-09 13:41:49.617  1802  2129 D WfdsService: selectPreferredScanChannel [6]
09-09 13:41:49.617  1802  2129 D WfdsService: STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
09-09 13:41:49.617  1802  1802 D WfdsService: isConnected: false
09-09 13:41:49.618   838  1305 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.618   838  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.618   838  1305 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.618   838  1305 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.618   838  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:49.618   838  1305 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.620  1802  1802 D WfdsService: GroupInfoAvailable: mGroupInfo is null
09-09 13:41:49.620  1802  2129 W WfdsService: DefaultState - msg [9441285] is not handled
09-09 13:41:49.620  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:49.621  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:49.621 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:49.621  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-09 13:41:49.621   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.621   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.621   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 13:41:49.622  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:49.623   838   838 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:49.624   838   838 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 13:41:49.625  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:49.625  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:49.625  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-09 13:41:49.625  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:49.625  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:49.625  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:49.629   838   838 D LocSvc_java: onReceive
09-09 13:41:49.631  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:41:49.631   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.632   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.632   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 13:41:49.632  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:49.632  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:49.632 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:49.632  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-09 13:41:49.637  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:49.637  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:49.637  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:49.637  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-09 13:41:49.638  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:49.637 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:49.638  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:49.638  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-09 13:41:49.638  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:49.638  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:49.638  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:49.639  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:49.639   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.639   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.639   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 13:41:49.639   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.639   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.639   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-09 13:41:49.640  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:49.64 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:49.640  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 sta,tus=0 ipV4Addr= ipV6Addr=
09-09 13:41:49.640   838  1306 I WifiServiceExtension: setVHTCapabilityType  : false
09-09 13:41:49.642  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:49.643  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:49.643  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-09 13:41:49.643  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:49.643  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:49.643  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:49.643  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:41:49.648  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:49.648  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:49.648  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-09 13:41:49.648  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:49.648  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:49.648  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:49.653   838  1306 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-09 13:41:49.653   838  1306 I WifiServerServiceExt: setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
09-09 13:41:49.653   838  1306 I WifiServiceExtension: setSecurityType  : 2
09-09 13:41:49.663  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:49.664  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:41:49.665  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:49.665 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:49.665   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.665  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-09 13:41:49.665   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.665  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:49.665   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 13:41:49.665   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.665   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.665   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 13:41:49.667  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:49.667 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:49.667  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-09 13:41:49.668  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:49.668  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:49.668  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-09 13:41:49.668  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:49.668  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:49.668  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:49.669  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:49.671  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:49.671  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:49.671  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-09 13:41:49.671  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:49.671  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:49.671,  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:49.677   838  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-09 13:41:49.677   838  1312 D ConnectivityService: Got NetworkAgent Messenger
09-09 13:41:49.677   838  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 13:41:49.677   838  1312 D ConnectivityService: NetworkAgent connected
,09-09 13:41:49.680  1802  2131 D WifiServiceExtension: isInternetCheckAvailable return false
09-09 13:41:49.681   838  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:41:49.690   838  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:41:49.700   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 9
09-09 13:41:49.700   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:49.700   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:49.701   838  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:49.701   838  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:49.701   276  1013 D CommandListener: Setting iface cfg
09-09 13:41:49.706   838  7895 D DhcpStateMachine: StoppedState
09-09 13:41:49.706   838  1306 E WifiStateMachine: Start Dhcp Watchdog 3
09-09 13:41:49.706   838  7895 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.706   838  7895 D DhcpStateMachine: WaitBeforeStartState
,09-09 13:41:49.710   838   838 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:49.710   838   838 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 13:41:49.711   838   838 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:49.711   838   838 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-09 13:41:49.711   838   838 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:49.712   838   838 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-09 13:41:49.712   838   838 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:49.712   838   838 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-09 13:41:49.713   838   838 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:49.713   838   838 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-09 13:41:49.713  6502  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:49.713  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:49.713  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:49.713  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:49.713  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:49.713  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c19c5c9 removed from the list
09-09 13:41:49.713  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:49.713  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b2a4ce removed from the list
09-09 13:41:49.713  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:49.713  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:49.719  1837  1837 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,09-09 13:41:49.722  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-52 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:49.721 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-09 13:41:49.723  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:49.723  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:49.723  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-09 13:41:49.723   838  1312 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 13:41:49.726  6502  7896 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-09 13:41:49.726  6502  7896 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-09 13:41:49.777   838  1775 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7899 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-09 13:41:49.778   838  1775 I ActivityManager: Killing 7627:com.lge.email/u0a21 (adj 15): empty #11
,09-09 13:41:49.814   838  1306 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-09 13:41:49.814   838  1306 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 13:41:49.814   838  1305 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@366d3877 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:49.814   838  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@366d3877 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:49.814   838  7895 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.814   838  7895 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-09 13:41:49.817   838  1306 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 13:41:49.817   276  1013 D CommandListener: Setting iface cfg
09-09 13:41:49.818   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
09-09 13:41:49.819   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:49.819   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:49.820   276  1013 D CommandListener: Trying to bring up wlan0
09-09 13:41:49.822   838  1864 W libprocessgroup: failed to open /acct/uid_10021/pid_7627/cgroup.procs: No such file or directory
09-09 13:41:49.822   838  1306 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-09 13:41:49.827   838   838 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:41:49.827   838   838 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,09-09 13:41:49.830   838  1312 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 13:41:49.831   838  1305 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.831   838  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.841  7899  7899 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:49.842   838  1312 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 13:41:49.843   838  1306 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 13:41:49.843   838  1312 D ConnectivityService: ignoring duplicate network state non-change
09-09 13:41:49.845  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:49.847  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-52 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:49.846 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:41:49.847   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.847   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.847  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.109 ipV6Addr=
09-09 13:41:49.847  1802  1818 D WifiServiceExtension: isInternetCheckAvailable return false
09-09 13:41:49.847   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 13:41:49.847  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:49.848   838  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 13:41:49.849   838  1312 D ConnectivityService: Adding iface wlan0 to network 102
09-09 13:41:49.850  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:49.850  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:49.850  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-09 13:41:49.851  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:49.851  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:49.851  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:49.852  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:49.852  1802  1817 D WifiServiceExtension: isInternetCheckAvailable return false
09-09 13:41:49.853  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-52 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:49.853 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:41:49.853  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.109 ipV6Addr=
,09-09 13:41:49.854  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:41:49.857   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.857   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.857   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 13:41:49.858  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-09 13:41:49.859  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:49.859  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-09 13:41:49.859  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:49.859  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:49.860  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-52 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:49.86 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:41:49.860  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.109 ipV6Addr=
09-09 13:41:49.861  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:49.861  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:49.861   838   838 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 13:41:49.862   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.862   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.862   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 13:41:49.863  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 13:41:49.865   838   838 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 13:41:49.865  1837  1837 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-09 13:41:49.866   838  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 13:41:49.869   838   838 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:49.869   838   838 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:49.869   838   838 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 13:41:49.869  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:49.870  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:49.870  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
09-09 13:41:49.870  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:49.871  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:49.871  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
09-09 13:41:49.871  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-52 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:49.871 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:41:49.871  1837  1837 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.109 ipV6Addr=
09-09 13:41:49.872  1375  1375 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 13:41:49.874  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:49.874  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:49.874  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
09-09 13:41:49.874  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-09 13:41:49.875  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-09 13:41:49.875  1375  1375 I [SystemUI]QuickSettingsHandler: Remote
,09-09 13:41:49.887   838  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 13:41:49.887   838  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-09 13:41:49.888   276  1013 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:41:49.888   276  1013 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:49.888   276  1013 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:41:49.888   276  1013 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:49.889   838  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-09 13:41:49.890   276  1013 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:41:49.890   276  1013 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:49.890   276  1013 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:41:49.890   276  1013 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:41:49.890   276  1013 E Netd    : netlink response contains error (File exists)
09-09 13:41:49.891   838  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-09 13:41:49.891   276  1013 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:41:49.891   276  1013 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:49.892   838  1312 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-09 13:41:49.892   838  1312 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-09 13:41:49.892   838  1312 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-09 13:41:49.892   838  1312 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:49.892   838  1312 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:49.892   276  1013 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
09-09 13:41:49.892   276  1013 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:49.893   838  1312 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 13:41:49.893   838  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 13:41:49.893   838  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-09 13:41:49.893   838  1312 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-09 13:41:49.893   838  7892 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.893   838  1312 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:49.893   838  7892 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-09 13:41:49.893   838  1312 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:49.893   838  1312 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:41:49.893   838  7892 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:49.893   838  1312 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:49.894   838  1312 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-09 13:41:49.894   838  1312 D ConnectivityService: currentScore = 0, newScore = 20
09-09 13:41:49.894   838  1312 D ConnectivityService:    accepting network in place of null
09-09 13:41:49.894   838  1312 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:49.894   838  1306 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:49.895   838  1306 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 13:41:49.895  1748  1748 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:49.895  1748  1748 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
09-09 13:41:49.898   838  1312 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 13:41:49.898   838  1312 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-09 13:41:49.898   838  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:41:49.899   838  1312 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:49.899   838  1312 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-09 13:41:49.900   838  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-09 13:41:49.901   838  1312 D ConnectivityService: validation of new default Network = false
09-09 13:41:49.902   838  1312 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-09 13:41:49.902   838  1312 D DSQN    : enableDataServiceNotify 
09-09 13:41:49.902   838  1312 D DSQN    : start dsqn bin
09-09 13:41:49.902   838  1017 D Tethering: MasterInitialState.processMessage what=3
09-09 13:41:49.903  1837  1837 W QCNEJ   : |CORE| No family connected
09-09 13:41:49.903  1837  1837 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
09-09 13:41:49.905  1837  1837 I QCNEJ   : |CORE| sendDefaultNwMsg: default = 1
09-09 13:41:49.905   838  7892 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] Start DNSResolver start to wait
,09-09 13:41:49.906   838  7918 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wait 500ms before dns check
09-09 13:41:49.923   838  1304 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-09 13:41:49.926   838  1312 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-09 13:41:49.926   838  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:49.926   838  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:49.926   838  1312 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:49.927  1375  1728 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:41:49.929  1375  1375 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:41:49.930  1375  1375 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
09-09 13:41:49.932  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:49.932  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:49.932  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
09-09 13:41:49.934  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:49.934  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:49.934  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
09-09 13:41:49.940  7920  7920 I DSQN    : DSQN samuel.seo ver 141203
09-09 13:41:49.940  7920  7920 E DSQN    : DSQN sock connect success to lgdatalistenerd
09-09 13:41:49.940  7920  7920 I DSQN    : created command queue thread
,09-09 13:41:49.940  7920  7920 I DSQN    : Interface wlan0 address 192.168.1.109 0xc0a8016d
09-09 13:41:49.940  7920  7920 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a8016d
09-09 13:41:49.941  7183  7919 I CheckinChimeraService: Checking schedule, now: 1473421309941 next: 1473421288860
09-09 13:41:49.941  7183  7919 I CheckinChimeraService: active receiver: enabled
,09-09 13:41:49.955  7183  7919 I CheckinChimeraService: Preparing to send checkin request
,09-09 13:41:49.956  7183  7919 I EventLogChimeraService: Accumulating logs since 1473421300510
09-09 13:41:49.989  7183  7919 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,09-09 13:41:49.991  7183  7919 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
09-09 13:41:50.016   838  7895 D DhcpStateMachine: DHCPV4 request on wlan0
,09-09 13:41:50.017   838  7895 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,09-09 13:41:50.017   838  7895 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-09 13:41:50.030  7926  7926 I dhcpcd  : version 5.5.6 starting
,09-09 13:41:50.032  7926  7926 E dhcpcd  : get_duid: Read-only file system
,09-09 13:41:50.094  7926  7926 I dhcpcd  : wlan0: rebinding lease of 192.168.1.109
,09-09 13:41:50.120  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-09 13:41:50.120  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:41:50.134  7926  7926 I dhcpcd  : wlan0: acknowledged 192.168.1.109 from 192.168.1.1
,09-09 13:41:50.146  7926  7926 I dhcpcd  : wlan0: leased 192.168.1.109 for 172800 seconds
,09-09 13:41:50.212   280  1322 I WVCdm   : CdmEngine::OpenSession
09-09 13:41:50.212   280  1322 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
,09-09 13:41:50.229  6502  7948 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:50.229  6502  7948 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:50.229  6502  7948 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:50.229  6502  7948 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:50.229   276  1008 E BandwidthController: [LG DATA] No such appUid: 10030
09-09 13:41:50.229   276  1008 D DnsProxyListener: App 10030 tries DNS query. Accept family:0 protocol:0
,09-09 13:41:50.236   276  7951 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-09 13:41:50.236   276  7951 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:50.236   276  7951 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-09 13:41:50.236   276  7951 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:50.237  6502  7948 I System.out: propertyValue:false
09-09 13:41:50.240  6502  7896 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-09 13:41:50.240  6502  7896 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:41:50.240  6502  7948 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-09 13:41:50.240  6502  7948 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:41:50.241   280  1322 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
09-09 13:41:50.241   280  1322 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
09-09 13:41:50.241   280  1322 W WVCdm   : L1 library not specified. Falling Back to L3
09-09 13:41:50.244  6502  7948 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:41:50.244  6502  7896 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:50.249  6502  7896 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:50.249  6502  7896 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-09 13:41:50.250  6502  7948 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:50.250  6502  7948 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-09 13:41:50.264  6502  7955 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 934, name: OutgoingSocketThread/Receiver)
09-09 13:41:50.265  6502  7954 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 932, name: OutgoingSocketThread/Sender)
09-09 13:41:50.265  6502  7957 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 935, name: IncomingSocketThread/Receiver)
09-09 13:41:50.265  6502  7956 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 933, name: IncomingSocketThread/Sender)
,09-09 13:41:50.267  6502  7955 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 934, thread name: OutgoingSocketThread/Receiver)
09-09 13:41:50.267  6502  7955 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:41:50.268  6502  7955 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 934, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-09 13:41:50.268  6502  7957 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 935, thread name: IncomingSocketThread/Receiver)
09-09 13:41:50.268  6502  7957 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:41:50.268  6502  7957 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 935, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-09 13:41:50.293  1375  1375 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-09 13:41:50.297  1375  1375 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-09 13:41:50.309  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
09-09 13:41:50.309  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,09-09 13:41:50.312  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
09-09 13:41:50.312  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
09-09 13:41:50.313  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
09-09 13:41:50.313  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
09-09 13:41:50.314  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
09-09 13:41:50.314  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
09-09 13:41:50.314  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
09-09 13:41:50.314  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
09-09 13:41:50.314  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
09-09 13:41:50.314  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
09-09 13:41:50.314  1375  1375 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-09 13:41:50.332  1837  1837 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,09-09 13:41:50.335   838  1286 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-09 13:41:50.352  1874  1874 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-09 13:41:50.360  1874  1874 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-09 13:41:50.361   838  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:50.363   838  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:50.364  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
09-09 13:41:50.369  1874  1874 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,09-09 13:41:50.375   280  1322 I WVCdm   : CdmEngine::QueryKeyControlInfo
09-09 13:41:50.377  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:50.378  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:50.378  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:50.378  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:50.378  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:50.378  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:50.378  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:50.378  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:50.378  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:50.379  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:50.379  6502  6502 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:50.379   280   280 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-09 13:41:50.379   280   280 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-09 13:41:50.379   280   280 I WVCdm   : CdmEngine::GenerateKeyRequest
,09-09 13:41:50.385   280   280 D WVCdm   : PrepareKeyRequest: nonce=4002109087
09-09 13:41:50.386  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:50.386  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:50.386  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:50.386  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:50.386  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:50.386  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:50.386  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:50.386  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:50.386  6502  6502 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:50.387  6502  6502 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:50.387  6502  6502 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:50.406   838  7918 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver start dns
09-09 13:41:50.407   838  7918 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,09-09 13:41:50.407   838  7918 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:50.407   838  7918 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=102; mark=0
09-09 13:41:50.407   838  7918 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:50.407   276  1008 E BandwidthController: [LG DATA] No such appUid: 1000
09-09 13:41:50.408   276  1008 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-09 13:41:50.412   276  7967 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=983142
09-09 13:41:50.412   276  7967 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:50.412   276  7967 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-09 13:41:50.413   276  7967 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,09-09 13:41:50.420   838  7895 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:50.421   838  7895 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:50.421   838  1819 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7968 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-09 13:41:50.421   838  7895 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:50.421   838  7895 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:50.421   838  7895 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:50.421   838  7895 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:50.421   838  7895 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:50.421   838  7895 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:50.421   838  7895 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-09 13:41:50.424   838  7895 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 4
09-09 13:41:50.424   838  7895 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 13:41:50.424   838  7895 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:50.424   838  7895 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:50.424   838  7895 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.109
09-09 13:41:50.424   838  7895 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-09 13:41:50.424   838  7895 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 13:41:50.424   838  7895 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-09 13:41:50.424   838  7895 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-09 13:41:50.425   838  7895 D DhcpStateMachine: RunningState
09-09 13:41:50.443  1874  1874 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,09-09 13:41:50.463  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
,09-09 13:41:50.468   276  7967 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:41:50.468   838   838 D administrator: Handling package changes for user 0
09-09 13:41:50.469   838  7918 I System.out: propertyValue:false
09-09 13:41:50.469   838  7918 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver end dns
09-09 13:41:50.469  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:50.471   838  7892 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 13:41:50.473  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:50.477   838  7892 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:50.477   838  7892 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:41:50.504  7920  7921 I DSQN    : first global connection report this to start monitoring at DSQM.
09-09 13:41:50.504  7920  7921 I DSQN    : restart monitoring
09-09 13:41:50.505   276  1012 D LGDataListener: argv[0]=dsqncommand
09-09 13:41:50.505   276  1012 D LGDataListener: argv[1]=wlan0
09-09 13:41:50.505   276  1012 D LGDataListener: argv[2]=1
09-09 13:41:50.505   276  1012 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-09 13:41:50.505  7920  7986 I DSQN    : dsqn report finish
09-09 13:41:50.506   838  1015 D DSQN    : DSQM DsqnNotification wlan0  1
09-09 13:41:50.506   838  1015 D DSQN    : start to monitor internet connection
09-09 13:41:50.532   838  7892 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:41:50 GMT], X-Android-Received-Millis=[1473421310531], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473421310504]}
09-09 13:41:50.532   838  7892 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 13:41:50.533  1802  2131 D WifiServiceExtension: isInternetCheckAvailable return false
09-09 13:41:50.533   838  7892 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wifi && isInternetCheckAvailable is false
09-09 13:41:50.533   838  7892 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-09 13:41:50.534   838  1312 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-09 13:41:50.534   838  1312 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-09 13:41:50.534   838  1312 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:50.534   838  1312 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:50.534   838  1312 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:41:50.534   838  1312 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-09 13:41:50.534   838  1312 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-09 13:41:50.534   838  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:50.534   838  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:50.535   838  1312 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-09 13:41:50.542   276  1006 I Netd    : M: Get netlink event, ifname: p2p0 action: 6
09-09 13:41:50.542   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:50.542   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:50.545   838  1312 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:50.545   838  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 13:41:50.545   838  1306 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:50.545   838  1306 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:50.547  1748  1748 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:41:50.548  1375  1728 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:41:50.549  1748  1748 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
09-09 13:41:50.564  1375  1375 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:41:50.565  1375  1375 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
09-09 13:41:50.566  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:50.566  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:50.566  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
09-09 13:41:50.568  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:50.568  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:50.568  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
09-09 13:41:50.572  7968  7968 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 13:41:50.738  6502  6657 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-09 13:41:50.739  6502  6657 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-09 13:41:50.740  6502  6657 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@31c5b796 Bundle[{}]
09-09 13:41:50.741  6502  6657 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 13:41:50.741  6502  6657 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-09 13:41:50.741  6502  6657 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-09 13:41:50.742  6502  6657 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 13:41:50.743  6502  6657 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-09 13:41:50.744  6502  6657 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 13:41:50.758  6502  7988 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-09 13:41:50.758  6502  7988 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-09 13:41:50.762  6502  7990 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:50.763  6502  7990 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:50.764  6502  7988 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-09 13:41:50.764  6502  7988 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:41:50.764  6502  7988 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:50.765  6502  7988 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:50.765  6502  7988 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-09 13:41:50.765  6502  7990 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-09 13:41:50.765  6502  7990 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:41:50.766  6502  7990 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:41:50.767  6502  7992 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 946, name: OutgoingSocketThread/Sender)
09-09 13:41:50.768  6502  7990 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:50.769  6502  7993 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 947, name: OutgoingSocketThread/Receiver)
09-09 13:41:50.769  6502  7993 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 947, thread name: OutgoingSocketThread/Receiver)
09-09 13:41:50.769  6502  7993 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:41:50.770  6502  7990 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-09 13:41:50.769  6502  7993 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 947, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-09 13:41:50.774  6502  7994 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 948, name: IncomingSocketThread/Sender)
09-09 13:41:50.776  6502  7995 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 949, name: IncomingSocketThread/Receiver)
09-09 13:41:50.779  6502  6657 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 958)
09-09 13:41:50.780  6502  6657 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 13:41:50.780  6502  6657 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 959)
09-09 13:41:50.782  6502  7995 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 949, thread name: IncomingSocketThread/Receiver)
09-09 13:41:50.782  6502  7995 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:41:50.782  6502  7995 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 949, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-09 13:41:50.784  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:50.785  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15a19afc added. We now have 3 listener(s)
,09-09 13:41:50.791   838  1359 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:41:50.800   838  1017 D BluetoothManagerService: Message: 20
09-09 13:41:50.800   838  1017 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d7b0010:true
09-09 13:41:50.802  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-09 13:41:50.802  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:50.802  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:50.802  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:50.802  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@deff585 added. We now have 3 listener(s)
09-09 13:41:50.802  6502  6657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:50.802  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:50.804  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:50.807  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:50.807  6502  6657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:50.807  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:50.807  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:41:50.807  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:50.807  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:50.807  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:50.807  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:50.807  6502  6657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:50.808  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:50.808  6502  6657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:50.808  6502  6657 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:50.809  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:50.809  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:50.810  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:50.811  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:50.811  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:50.811  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:50.811  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:50.811  6502  6657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15a19afc removed from the list
09-09 13:41:50.811  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:50.811  6502  6657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@deff585 removed from the list
09-09 13:41:50.811  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:50.811  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:50.812  6502  6657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:50.812  6502  6657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:41:50.812  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:41:50.812  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:50.812  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:50.815  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:50.815  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:50.816  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,09-09 13:41:50.817  6502  6657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-09 13:41:50.818  6502  6657 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:41:50.818  6502  6502 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-09 13:41:50.824   838   838 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-09 13:41:50.824   838   838 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-09 13:41:50.824   838   838 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
09-09 13:41:50.828   838   838 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
09-09 13:41:50.838   838   838 D LocSvc_java: onReceive
09-09 13:41:50.838   838   838 D LocSvc_java: got connectivity action
09-09 13:41:50.838   838   838 D LocSvc_java: broadcast - no network connections
09-09 13:41:50.838   838   838 D LocSvc_java: Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
09-09 13:41:50.838   838   838 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 13:41:50.839   838   838 D LocSvc_java: onReceive
09-09 13:41:50.839   838   838 D LocSvc_java: got connectivity action
09-09 13:41:50.839   838   838 D LocSvc_java: broadcast - no network connections
09-09 13:41:50.839   838   838 D LocSvc_java: Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
09-09 13:41:50.839   838   838 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 13:41:50.839   838   838 D WifiDataContinuityService: sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
09-09 13:41:50.839   838   838 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:41:50.839   838   838 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:41:50.839   838   838 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:41:50.839   838   838 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:41:50.839   838   838 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:41:50.839   838   838 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:41:50.841   838  1306 I WifiServerServiceExt: set CMD_CAPTIVE_CHECK_COMPLETED
,09-09 13:41:50.856   838   838 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
09-09 13:41:50.858   838   838 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1f8f3fca
,09-09 13:41:50.896  7348  7478 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:50.896  7348  7478 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:50.896  7348  7478 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:41:50.896  7348  7478 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:41:50.896  7348  7478 I Adreno-EGL: Remote Branch: 
09-09 13:41:50.896  7348  7478 I Adreno-EGL: Local Patches: 
09-09 13:41:50.896  7348  7478 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:41:50.926   838  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-09 13:41:50.953   838   890 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:50.981   280  1599 I WVCdm   : CdmEngine::OpenSession
09-09 13:41:50.984   838  1359 I ActivityManager: Process com.lge.appbox.client (pid 7682) has died
,09-09 13:41:51.033   838  1864 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7999 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:51.062  7968  7968 V LGMDMManager: Create singleton instance
,09-09 13:41:51.114   838   890 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-09 13:41:51.140  7968  7968 I AudioManager: getMode name:com.lge.qremote
,09-09 13:41:51.162   838  1347 I ActivityManager: Process com.google.android.setupwizard (pid 7702) has died
,09-09 13:41:51.174   293   354 I ThermalEngine: Sensor:pa_therm0:38000 mC
09-09 13:41:51.192   276  1006 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
,09-09 13:41:51.193   838  1015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:51.193   838  1015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:51.197   838  1312 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-09 13:41:51.197   838  1312 D ConnectivityService: identical MTU - not setting
09-09 13:41:51.197   838  1312 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 13:41:51.197   838  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 13:41:51.197   838  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:51.197   838  1312 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:51.198   838  1312 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:41:51.198   838  1312 D ConnectivityService: Wi-Fi IP changed. Lp difference / No Route difference
09-09 13:41:51.198   838  1312 D DSQN    : enableDataServiceNotify 
09-09 13:41:51.198   838  1312 D DSQN    : start dsqn bin
09-09 13:41:51.199  1375  1728 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-09 13:41:51.207   838  1924 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8017 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:51.210   838  1312 D DSQN    : dsqn is running restart
09-09 13:41:51.228  8023  8023 I DSQN    : DSQN samuel.seo ver 141203
09-09 13:41:51.228  8023  8023 E DSQN    : DSQN sock connect success to lgdatalistenerd
,09-09 13:41:51.228  8023  8023 I DSQN    : created command queue thread
09-09 13:41:51.228  8023  8023 I DSQN    : Interface wlan0 address 192.168.1.109 0xc0a8016d
09-09 13:41:51.228  8023  8023 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a8016d
09-09 13:41:51.239   838   890 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:51.240   838   890 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:51.242  1837  1837 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
09-09 13:41:51.243  1874  1874 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-09 13:41:51.246  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-52 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:51.246 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:41:51.248   838   890 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:51.248   838   890 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:51.254  1730  1730 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
09-09 13:41:51.257  7999  7999 D UEI.SmartControl: Quickset Services start...
,09-09 13:41:51.264  7999  7999 I UEI.SmartControl: Manufacture = LGE
,09-09 13:41:51.266  7999  7999 D UEI.SmartControl: File observer start...
09-09 13:41:51.272  7999  7999 E UEI.SmartControl: IR Port is disabled: false
,09-09 13:41:51.272  7999  7999 D UEI.SmartControl: Starting file observer...
09-09 13:41:51.272  7999  7999 D UEI.SmartControl: Extracting JNI libs...
09-09 13:41:51.273  7999  7999 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-09 13:41:51.292   838  1775 I ActivityManager: Process com.lge.lgdmsclient (pid 7655) has died
,09-09 13:41:51.313   838   890 D LocationProviderProxy: applying state to connected service
,09-09 13:41:51.319  6502  6502 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-09 13:41:51.404  8017  8017 I MusicStore: Database version: 120
,09-09 13:41:51.451   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:51.451   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,09-09 13:41:51.451   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:51.451  8017  8017 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,09-09 13:41:51.455  7999  7999 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-09 13:41:51.456  7999  7999 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-09 13:41:51.456  7999  7999 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-09 13:41:51.504  7999  7999 I UEI.SmartControl: --- Selecting new region: 2
,09-09 13:41:51.505  7999  7999 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
09-09 13:41:51.513  7999  7999 D UEI.SmartControl: Platform has CIR...
09-09 13:41:51.514  7999  7999 D UEI.SmartControl: NO CIR support, need to check package...
09-09 13:41:51.515  7999  7999 I UEI.SmartControl: Model: LG-D722 uses JNI
09-09 13:41:51.518  7999  7999 D UEI.SmartControl: QS Service created
,09-09 13:41:51.543  7999  7999 E UEI.SmartControl: QS start get config
,09-09 13:41:51.573   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:51.573   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-09 13:41:51.573   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:51.573  8017  8017 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,09-09 13:41:51.575   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:51.576   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-09 13:41:51.576   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:51.576  8017  8017 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-09 13:41:51.603  7999  7999 D UEI.SmartControl: Loading JNI Libs...
,09-09 13:41:51.607  7999  7999 D UEI.SmartControl:  configuring local db...
09-09 13:41:51.610  8017  8017 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 13:41:51.610  8017  8017 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-09 13:41:51.658  8017  8017 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 13:41:51.735  8017  8017 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-09 13:41:51.736  8017  8017 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38c1ee2e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-09 13:41:51.737  8017  8017 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-09 13:41:51.737  8017  8017 D AndroidMusic: GMSCore installation verified
09-09 13:41:51.742  8017  8017 I ConfigStore: Config Database version: 1
,09-09 13:41:51.828  7999  7999 D UEI.SmartControl:  ---- Has DB8: true
,09-09 13:41:51.835  7999  7999 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 13:41:51.836  7999  7999 D UEI.SmartControl: QS version = v2.7.11.1_RC1
09-09 13:41:51.837  7999  7999 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
09-09 13:41:51.840  7999  7999 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
09-09 13:41:51.912   838   867 I art     : Explicit concurrent mark sweep GC freed 77621(3MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 2.144ms total 154.052ms
,09-09 13:41:51.958  7999  7999 W irrc_jni: IRRCPlayer_nativeInit ++ 
09-09 13:41:51.958  7999  7999 D irrcClient: IrrcClient ++ 
09-09 13:41:51.958  7999  7999 D irrcClient: getIrrcService ++ 
,09-09 13:41:51.960  7999  7999 D irrcClient: getIrrcService -- 
09-09 13:41:51.960  7999  7999 D irrcClient: IrrcClient -- 
09-09 13:41:51.960  7999  7999 W irrc_jni: IRRCPlayer_nativeInit -- 
09-09 13:41:51.969  7999  7999 D UEI.SmartControl: Services init done
09-09 13:41:51.970  7999  8046 I UEI.SmartControl: Device manager: loading config....
,09-09 13:41:51.973  7999  7999 D UEI.SmartControl: QS Service init finished
09-09 13:41:51.975  7999  7999 D UEI.SmartControl: QS Service version name: 0.1.73
09-09 13:41:51.976  7999  7999 D UEI.SmartControl: QS Service version code: 1073
09-09 13:41:51.977  7999  7999 D UEI.SmartControl: Service requested: Control
09-09 13:41:51.981  7999  8046 D UEI.SmartControl: Config is loaded...
09-09 13:41:52.019  8017  8034 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3f0
,09-09 13:41:52.019  7999  8045 D UEI.SmartControl:  ----- QS SDK is ready!!!
09-09 13:41:52.020  7999  8045 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 13:41:52.027  7999  7999 D UEI.SmartControl: Request IControl service: devices are loaded...
09-09 13:41:52.029  7999  7999 D UEI.SmartControl: Internal service binding...
09-09 13:41:52.030  7999  8014 D UEI.SmartControl: -----IControl: 11
09-09 13:41:52.031  7999  8014 D UEI.SmartControl: Caller: com.lge.qremote
09-09 13:41:52.031  7999  8014 D UEI.SmartControl: ------------ IControl registerCallback...
09-09 13:41:52.032  7999  8014 I UEI.SmartControl: Registering callback...
09-09 13:41:52.034  7999  8015 D UEI.SmartControl: -----IControl: 19
09-09 13:41:52.036  7999  8015 D UEI.SmartControl: Caller: com.lge.qremote
09-09 13:41:52.036  7999  8015 I UEI.SmartControl: Registering Services Ready callback...
09-09 13:41:52.037  7999  8015 I UEI.SmartControl: Notify client services are ready...
09-09 13:41:52.039  7999  8014 D UEI.SmartControl: -----IControl: 8
09-09 13:41:52.040  7999  8014 D UEI.SmartControl: Caller: com.lge.qremote
09-09 13:41:52.043  8017  8017 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-09 13:41:52.050  8017  8034 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3d0
09-09 13:41:52.059  8017  8017 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-09 13:41:52.072   243   243 E lowmemorykiller: Error opening /proc/7798/oom_score_adj; errno=2
,09-09 13:41:52.083  8017  8017 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 13:41:52.102   838  1801 I ActivityManager: Process com.google.android.apps.magazines (pid 7798) has died
09-09 13:41:52.124  8017  8017 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 13:41:52.165   838  1924 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8052 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-09 13:41:52.201  8017  8017 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,09-09 13:41:52.211  8017  8017 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:41:52.247  8017  8040 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
,09-09 13:41:52.250  8052  8052 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:41:52.250  8052  8052 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:41:52.251  8052  8052 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 13:41:52.272   838  1305 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:52.272   838  1305 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:52.272   838  1305 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:52.310  8052  8052 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-09 13:41:52.321  8052  8052 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,09-09 13:41:52.447  8052  8052 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-09 13:41:52.495   838  1844 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=8078 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-09 13:41:52.596  8052  8052 I HubEmail: JNI_OnLoad()
09-09 13:41:52.596  8052  8052 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:41:52.596  8052  8052 I HubEmail: registerNatives()
09-09 13:41:52.596  8052  8052 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:41:52.596  8052  8052 I HubEmail: registerNativeMethods()
09-09 13:41:52.596  8052  8052 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:41:52.597  8052  8052 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-09 13:41:52.622  8052  8093 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:52.672  8078  8078 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:52.673  8078  8078 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:41:52.675  8078  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:41:52.678  8078  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,09-09 13:41:52.708  8078  8101 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:52.709   280  1296 I WVCdm   : CdmEngine::CloseSession
09-09 13:41:52.710  8078  8101 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:41:52.710  8078  8100 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:41:52.714  8078  8100 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-09 13:41:52.723   838  1801 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=8109 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-09 13:41:52.766   280  1599 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-09 13:41:52.769  1837  1837 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
09-09 13:41:52.771   280  1296 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-09 13:41:52.771   280  1296 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-09 13:41:52.771   280  1296 I WVCdm   : CdmEngine::GenerateKeyRequest
09-09 13:41:52.771  1837  1837 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-52 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-09 13:41:52.771 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-09 13:41:52.773  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-09 13:41:52.773  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-09 13:41:52.773  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
09-09 13:41:52.776  8078  8100 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:41:52.777   280  1296 D WVCdm   : PrepareKeyRequest: nonce=353601701
09-09 13:41:52.780  8078  8078 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
09-09 13:41:52.780  8078  8078 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
09-09 13:41:52.781  8078  8078 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,09-09 13:41:52.784  8078  8078 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:41:52.788  8078  8078 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,09-09 13:41:52.827  8109  8109 I AppUp4:AppBoxCP: onCreate
09-09 13:41:52.828  8109  8109 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-09 13:41:52.836  8109  8109 I AppUp4:DB:  setFingerPrint start
09-09 13:41:52.836  8109  8109 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
09-09 13:41:52.846  8109  8109 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
09-09 13:41:52.847  8109  8109 I AppUp4:DB:  SDK version = 21
09-09 13:41:52.847  8109  8109 I AppUp4:DB:  beforefinger == newfinger no write in DB
,09-09 13:41:52.848  8109  8109 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-09 13:41:52.849  8109  8109 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 13:41:52.849  8109  8109 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:52.851  8109  8109 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 13:41:52.851  8109  8109 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 13:41:52.855  8109  8109 I AppUp4:CustModeStarterReceiver: onReceive
09-09 13:41:52.855  8109  8109 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:52.859  8109  8109 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@19b9a5c3
09-09 13:41:52.859  8109  8109 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:41:52.861   838  1307 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-09 13:41:52.864  8109  8109 D AppUp4:CustFacade: isSimDevice : true
09-09 13:41:52.865  8109  8109 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:41:52.865  8109  8109 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-09 13:41:52.866  8109  8109 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-09 13:41:52.866  8109  8126 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-09 13:41:52.866  8109  8126 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-09 13:41:52.866  8109  8126 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-09 13:41:52.867   838  1775 I ActivityManager: Killing 7728:com.lge.drmservice/u0a51 (adj 15): empty #11
09-09 13:41:52.900   838  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:53.094   838  1924 W libprocessgroup: failed to open /acct/uid_10051/pid_7728/cgroup.procs: No such file or directory
09-09 13:41:53.094  3150  3150 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 13:41:53.094  3150  3150 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:53.095  3150  3150 I LgeMiscReceiver: networkInfo.isConnected() = true
,09-09 13:41:53.105   838   838 D LocSvc_java: onReceive
,09-09 13:41:53.105   838   838 D LocSvc_java: got connectivity action
09-09 13:41:53.105   838   838 D LocSvc_java: Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
09-09 13:41:53.105   838   838 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-09 13:41:53.106   838   838 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:41:53.106   838   838 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:41:53.106   838   838 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:41:53.111  1375  1375 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
,09-09 13:41:53.125  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:53.126  6502  6502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:53.128  8017  8017 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-09 13:41:53.137  3150  3150 D PhoneState: setPdpRejectCasuse : false
09-09 13:41:53.142   838   890 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:53.160   838   890 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:53.205   838  1783 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8139 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,09-09 13:41:53.311  8139  8139 D PhoneMonitor: Register our PhoneStateListener
,09-09 13:41:53.323  8139  8139 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 13:41:53.324  8139  8139 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-09 13:41:53.325   838  1347 I ActivityManager: Killing 7874:com.android.chrome/u0a48 (adj 15): empty #11
,09-09 13:41:53.341  8139  8139 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-09 13:41:53.342  8139  8139 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-09 13:41:53.342  8139  8139 D TelephonyAutoProfiling: [parse] Load xml
09-09 13:41:53.344  8139  8139 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-09 13:41:53.344  8139  8139 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,09-09 13:41:53.350  8139  8139 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-09 13:41:53.475   838  1924 W libprocessgroup: failed to open /acct/uid_10048/pid_7874/cgroup.procs: No such file or directory
,09-09 13:41:53.480  2720  2720 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:53.483  2720  2720 V DownloadManager: DownloadService onCreate
09-09 13:41:53.487  2720  8160 I DownloadManager: in removeSpuriousFiles
09-09 13:41:53.488  2720  8160 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-09 13:41:53.490  2720  2720 I NotificationManager: com.android.providers.downloads: cancelAll by com.android.providers.downloads
09-09 13:41:53.490  2720  8160 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3d57e101 on behalf of 2720
09-09 13:41:53.494  2720  8160 I DownloadManager: in trimDatabase
09-09 13:41:53.494  2720  8160 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-09 13:41:53.495  2720  8160 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2cbf4ba6 on behalf of 2720
,09-09 13:41:53.527   838  2110 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8163 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-09 13:41:53.528  2720  2720 V DownloadManager: DownloadService onStartCommand
,09-09 13:41:53.604  2720  8161 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,09-09 13:41:53.606  2720  8161 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@35e08c3d on behalf of 2720
,09-09 13:41:53.652  2720  2720 V DownloadManager: DownloadService onDestroy
09-09 13:41:53.667   838  1801 I ActivityManager: Killing 7899:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,09-09 13:41:53.803   838  1844 W libprocessgroup: failed to open /acct/uid_10086/pid_7899/cgroup.procs: No such file or directory
,09-09 13:41:53.806  2863  2863 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:41:53
09-09 13:41:53.808  2863  2863 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 13:41:53.808  2863  2863 D WeatherAncestor: connectivity changed - connection : true
09-09 13:41:53.808  2863  2863 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 13:41:53.809  2863  2863 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:41:53
09-09 13:41:53.809  2863  2863 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:53.810  2863  2863 D WeatherService: 2 : shouldTimeTickRegistered : false
09-09 13:41:53.818  6502  6657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:41:53.818  6502  6657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 13:41:53.821  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:53.821  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:53.821  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:53.821  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15a19afc not in the list
09-09 13:41:53.821  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:53.821  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:53.821  6502  6657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:53.821  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:53.822  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:53.822  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:53.823  6502  6657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:53.823  6502  6502 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:53.823  6502  6502 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:53.823  6502  6502 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:53.824  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@deff585 not in the list
09-09 13:41:53.824  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:53.824  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:53.824  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:53.825  6502  6657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:53.826  6502  6657 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-09 13:41:53.826  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-09 13:41:53.826  6502  6657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:53.826  6502  6657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:41:53.826  6502  6657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:53.826  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:53.827  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
09-09 13:41:53.828  6502  6657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
09-09 13:41:53.828  6502  6657 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Fai,led to start the connection manager (Bluetooth connection listener)
09-09 13:41:53.828  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:41:53.828  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:53.828  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:53.829  6502  6502 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
09-09 13:41:53.832  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,09-09 13:41:53.838  6502  6657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-09 13:41:53.838  6502  6657 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:41:53.839  6502  6502 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-09 13:41:53.839  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:53.839  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:53.839  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:53.839  6502  6657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
09-09 13:41:53.840  6502  6502 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:41:53.840  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15a19afc not in the list
09-09 13:41:53.840  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:53.840  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:53.840  6502  6657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:53.840  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:53.840  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:53.850  7752  8181 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:53.851  7752  8181 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:41:53.851  7752  8181 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,09-09 13:41:53.851  7752  8181 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:53.852   276  1008 E BandwidthController: [LG DATA] No such appUid: 10061
09-09 13:41:53.852   276  1008 D DnsProxyListener: App 10061 tries DNS query. Accept family:0 protocol:0
09-09 13:41:53.852   276  8183 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-09 13:41:53.852   276  8183 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:53.853   276  8183 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-09 13:41:53.853   276  8183 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:41:53.853   276  8183 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:41:53.854  7752  8181 I System.out: propertyValue:false
09-09 13:41:53.885  8023  8024 I DSQN    : first global connection report this to start monitoring at DSQM.
09-09 13:41:53.885  8023  8024 I DSQN    : restart monitoring
,09-09 13:41:53.888  8023  8188 I DSQN    : dsqn report finish
09-09 13:41:53.888   276  1012 D LGDataListener: argv[0]=dsqncommand
09-09 13:41:53.888   276  1012 D LGDataListener: argv[1]=wlan0
09-09 13:41:53.888   276  1012 D LGDataListener: argv[2]=1
09-09 13:41:53.888   276  1012 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-09 13:41:53.889   838  2176 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8184 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:41:53.889   838  1015 D DSQN    : DSQM DsqnNotification wlan0  1
09-09 13:41:53.889   838  1015 D DSQN    : start to monitor internet connection
09-09 13:41:53.890  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:53.913  7752  8181 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 13:41:53.918  6502  6657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:53.918  6502  6502 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:53.918  6502  6502 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:53.918  6502  6502 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:53.918  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@deff585 not in the list
09-09 13:41:53.918  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:53.918  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:53.918  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:53.919  6502  6657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:53.919  6502  6657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:41:53.919  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:41:53.919  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:53.919  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:53.922  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-09 13:41:53.923  6502  6657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-09 13:41:53.923  6502  6657 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:41:53.923  6502  6502 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-09 13:41:54.057   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:54.057   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,09-09 13:41:54.057   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:54.059  8184  8205 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-09 13:41:54.064   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:54.064   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:41:54.064   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:54.065  8184  8205 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 13:41:54.072   838  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:54.072   838  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:41:54.074  8184  8184 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 13:41:54.074  8184  8184 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 13:41:54.074  8184  8184 I GAv4    :   adb logcat -s GAv4
09-09 13:41:54.075   838  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:54.075   838  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:54.075   276  1008 E BandwidthController: [LG DATA] No such appUid: 1000
09-09 13:41:54.075   276  1008 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-09 13:41:54.075   276  8211 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-09 13:41:54.075   276  8211 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:54.076   276  8211 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-09 13:41:54.076   276  8211 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:41:54.084   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:54.084   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 13:41:54.084   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:54.089  8184  8212 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-09 13:41:54.092   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:41:54.092   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:41:54.092   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:41:54.092  8184  8212 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 13:41:54.095  8184  8184 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
09-09 13:41:54.127  8184  8184 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:41:54.132  8184  8213 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
09-09 13:41:54.325  8184  8184 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,09-09 13:41:54.355  8184  8184 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1511-1513)
,09-09 13:41:54.355  8184  8184 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:41:54.361  8184  8184 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2cdff994}
09-09 13:41:54.362  8184  8184 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:41:54.362  8184  8184 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 13:41:54.376  8184  8184 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 13:41:54.377  8184  8184 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:41:54.379   276  8211 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:41:54.380   838  1307 I System.out: propertyValue:false
09-09 13:41:54.382  8184  8184 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 13:41:54.389   838  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:54.389   838  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:54.390   838  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:54.390   838  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:54.390   276  1008 E BandwidthController: [LG DATA] No such appUid: 1000
09-09 13:41:54.390   276  1008 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
,09-09 13:41:54.391   276  8236 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-09 13:41:54.391   276  8236 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:54.392   276  8236 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-09 13:41:54.392   276  8236 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-09 13:41:54.393   276  8236 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:41:54.393   838  1308 I System.out: propertyValue:false
09-09 13:41:54.403  8184  8184 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-09 13:41:54.408  8184  8184 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:41:54.408  8184  8184 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:41:54.409  8184  8184 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:54.409  8184  8184 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:54.409  8184  8184 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:41:54.409  8184  8184 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:41:54.409  8184  8184 I Adreno-EGL: Remote Branch: 
09-09 13:41:54.409  8184  8184 I Adreno-EGL: Local Patches: 
09-09 13:41:54.409  8184  8184 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:41:54.424  6502  6502 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:41:54.443   838  1308 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,09-09 13:41:54.490   280   280 V AudioPolicyService: registerClient() client 0xb40275a0, uid 10079
,09-09 13:41:54.492  8184  8247 W AudioManagerAndroid: Requires BLUETOOTH permission
09-09 13:41:54.493  8184  8184 I NSApplication: Starting up...
09-09 13:41:54.537   838  1899 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8252 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:54.542   838  1899 I ActivityManager: Killing 7968:com.lge.qremote/u0a106 (adj 15): empty #11
09-09 13:41:54.561   301   301 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 24.226ms
,09-09 13:41:54.590   301   301 I art     : Explicit concurrent mark sweep GC freed 7(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 28.264ms
,09-09 13:41:54.611   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 20.682ms
,09-09 13:41:54.652   838  1844 W libprocessgroup: failed to open /acct/uid_10106/pid_7968/cgroup.procs: No such file or directory
,09-09 13:41:54.657   838  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{edc709e type 2 when 171756 com.google.android.gms} when 171756
,09-09 13:41:54.771   838  1819 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8277 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-09 13:41:54.772   838  1819 I ActivityManager: Killing 7999:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,09-09 13:41:54.869   280  1322 I WVCdm   : CdmEngine::CloseSession
,09-09 13:41:54.876   280  1322 I WVCdm   : L3 Terminate.
09-09 13:41:54.883  7348  7478 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:54.883  7348  7478 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:54.883  7348  7478 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:41:54.883  7348  7478 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:41:54.883  7348  7478 I Adreno-EGL: Remote Branch: 
09-09 13:41:54.883  7348  7478 I Adreno-EGL: Local Patches: 
09-09 13:41:54.883  7348  7478 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:41:54.941  7348  7478 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:41:54.941  7348  7478 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:41:54.941  7348  7478 I Adreno-EGL: Build Date: 03/02/15 Mon
09-09 13:41:54.941  7348  7478 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-09 13:41:54.941  7348  7478 I Adreno-EGL: Remote Branch: 
09-09 13:41:54.941  7348  7478 I Adreno-EGL: Local Patches: 
09-09 13:41:54.941  7348  7478 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:41:55.028   838  1899 W libprocessgroup: failed to open /acct/uid_10089/pid_7999/cgroup.procs: No such file or directory
,09-09 13:41:55.051  8277  8277 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:55.147  7183  7919 I CheckinUtil: Classify the device as Phone.
,09-09 13:41:55.175   838  1028 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-09 13:41:55.175   838  1028 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-09 13:41:55.175   838  1028 D sensors_hal_Time: tsOffsetIs: Apps: 172333473012; DSPS: 5745161; Offset : -3004116254
,09-09 13:41:55.240  3984  5484 I art     : Explicit concurrent mark sweep GC freed 2904(113KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 429us total 45.680ms
,09-09 13:41:55.258  7183  7919 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:55.258  7183  7919 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-09 13:41:55.259  7183  7919 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:55.259  7183  7919 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:55.259   276  1008 E BandwidthController: [LG DATA] No such appUid: 10006
09-09 13:41:55.259   276  1008 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-09 13:41:55.260   276  8313 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-09 13:41:55.260   276  8313 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-09 13:41:55.260   276  8313 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-09 13:41:55.261   276  8313 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,09-09 13:41:55.287   838  1864 I ActivityManager: Killing 8017:com.google.android.music:main/u0a81 (adj 15): empty #11
,09-09 13:41:55.300   276  8313 D libc-netbsd: res_queryN name = xxxxx succeed
09-09 13:41:55.302  7183  7919 I System.out: propertyValue:false
,09-09 13:41:55.363   838  2110 W libprocessgroup: failed to open /acct/uid_10081/pid_8017/cgroup.procs: No such file or directory
,09-09 13:41:55.394  7183  7919 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-09 13:41:55.394  7183  7919 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-09 13:41:55.395  1375  1375 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,09-09 13:41:55.442  1748  1764 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
09-09 13:41:55.447  1748  1764 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-09 13:41:55.447  1748  1764 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-09 13:41:55.455  1748  1764 V TelecomServiceImpl: getCallState : 0
,09-09 13:41:55.456  1748  2579 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
09-09 13:41:55.456  1748  2579 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-09 13:41:55.456  1748  2579 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-09 13:41:55.463  1375  1375 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
09-09 13:41:55.464  1375  1375 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
09-09 13:41:55.492  7183  7919 I CheckinTask: Sending checkin request (11391 bytes)
,09-09 13:41:55.508   838  1844 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=8318 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-09 13:41:55.556  8318  8318 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 13:41:55.599   838  1017 D BluetoothManagerService: Message: 20
09-09 13:41:55.599   838  1017 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29aff650:true
,09-09 13:41:55.605  2007  2056 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:55.605  2007  3522 D BluetoothAdapterService(490245822): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7509f04
09-09 13:41:55.654   838  1347 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=8339 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-09 13:41:55.873  8339  8339 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:41:55.874  8339  8339 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-09 13:41:55.874  8339  8339 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:41:55.875  8339  8339 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 13:41:55.875  8339  8339 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 13:41:55.937  8339  8339 I IndexDatabaseHelper: Using schema version: 115
,09-09 13:41:55.940  8339  8339 I IndexDatabaseHelper: Index is fine
09-09 13:41:56.041  7183  7919 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,09-09 13:41:56.042  7183  7919 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
09-09 13:41:56.114  8339  8339 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:56.179   293   354 I ThermalEngine: Sensor:pa_therm0:38000 mC
09-09 13:41:56.182  8339  8339 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:41:56.242   838  1775 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8362 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-09 13:41:56.310   838  1347 I art     : Explicit concurrent mark sweep GC freed 29571(1439KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.382ms total 149.953ms
09-09 13:41:56.328   838  1819 I ActivityManager: Killing 8052:com.lge.email/u0a21 (adj 15): empty #11
,09-09 13:41:56.363   838  1347 W libprocessgroup: failed to open /acct/uid_10021/pid_8052/cgroup.procs: No such file or directory
,09-09 13:41:56.369  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-09 13:41:56.369  1730  1730 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-09 13:41:56.370  8362  8362 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 13:41:56.378  8362  8362 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-09 13:41:56.378  8362  8362 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:56.380   838  1924 I ActivityManager: Killing 8078:com.lge.lgdmsclient/1000 (adj 15): empty #11
09-09 13:41:56.403   838  1801 W libprocessgroup: failed to open /acct/uid_1000/pid_8078/cgroup.procs: No such file or directory
,09-09 13:41:56.423  8339  8339 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:56.428  8339  8339 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:56.431  7183  7919 I CheckinUtil: Classify the device as Phone.
09-09 13:41:56.433  8362  8362 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 13:41:56.433  8362  8362 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:41:56.433  8362  8362 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:56.438  8339  8339 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:56.443  8339  8339 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:41:56.448  8362  8362 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 13:41:56.449  8362  8362 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:41:56.449  8362  8362 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:56.453  8339  8339 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:56.459  8339  8339 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:56.461  8362  8362 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:41:56.466  7183  7919 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,09-09 13:41:56.471  7183  7919 I CheckinChimeraService: Checking schedule, now: 1473421316471 next: 1473948565466
09-09 13:41:56.471  7183  7919 I CheckinChimeraService: active receiver: disabled
,09-09 13:41:56.499  8339  8339 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-09 13:41:56.500  8339  8339 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 13:41:56.500  8339  8339 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 13:41:56.500  8339  8339 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-09 13:41:56.504  7183  8387 I CheckinChimeraService: Checking schedule, now: 1473421316503 next: 1473948565466
09-09 13:41:56.504  7183  8387 I CheckinChimeraService: active receiver: disabled
09-09 13:41:56.504  8339  8339 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 13:41:56.513  7183  7183 D CheckinChimeraService: Recording last checkin time for package unspecified as 1473421316513
,09-09 13:41:56.536  8339  8339 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,09-09 13:41:56.536  8339  8339 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-09 13:41:56.536  8339  8339 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 13:41:56.536  8339  8339 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 13:41:56.536  8339  8339 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 13:41:56.536  8339  8339 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-09 13:41:56.537   838  1899 I ActivityManager: Killing 8109:com.lge.appbox.client/u0a11 (adj 15): empty #11
09-09 13:41:56.537  8339  8339 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-09 13:41:56.552   838  1819 W libprocessgroup: failed to open /acct/uid_10011/pid_8109/cgroup.procs: No such file or directory
,09-09 13:41:56.587   838  1899 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=8391 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
09-09 13:41:56.588   838  1899 I ActivityManager: Killing 8139:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,09-09 13:41:56.622   838  1924 W libprocessgroup: failed to open /acct/uid_10038/pid_8139/cgroup.procs: No such file or directory
,09-09 13:41:56.664  8391  8391 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:41:56.664  8391  8391 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-09 13:41:56.666  8391  8391 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:41:56.669  8391  8391 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:41:56.672  8339  8339 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:56.675  8339  8339 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:56.678  8362  8362 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-09 13:41:56.678  8362  8362 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:41:56.678  8362  8362 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:41:56.685  8391  8408 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:41:56.690  8391  8408 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,09-09 13:41:56.699  8391  8408 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:41:56.722  8391  8409 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:41:56.722  8391  8409 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:41:56.723  8391  8391 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
09-09 13:41:56.724  8391  8391 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
09-09 13:41:56.724  8391  8391 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,09-09 13:41:56.726  8391  8391 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:41:56.731  8391  8391 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,09-09 13:41:56.747   838  1864 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8414 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
09-09 13:41:56.756   838  1819 I ActivityManager: Killing 8163:com.lge.drmservice/u0a51 (adj 15): empty #11
09-09 13:41:56.798   838  2176 W libprocessgroup: failed to open /acct/uid_10051/pid_8163/cgroup.procs: No such file or directory
,09-09 13:41:56.856  8414  8414 D PhoneMonitor: Register our PhoneStateListener
,09-09 13:41:56.878  8414  8414 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,09-09 13:41:56.879  8414  8414 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-09 13:41:56.880  8414  8414 D TelephonyAutoProfiling: [parse] Load xml
09-09 13:41:56.883  8414  8414 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-09 13:41:56.883  8414  8414 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,09-09 13:41:56.890  8414  8414 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-09 13:41:56.924  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:56.924  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:56.924  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:56.924  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15a19afc not in the list
09-09 13:41:56.924  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:56.924  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:56.924  6502  6657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:56.924  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:56.924  6502  6657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:56.925  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:56.926  6502  6657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:56.926  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@deff585 not in the list
09-09 13:41:56.926  6502  6502 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:56.926  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:56.926  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:56.926  6502  6502 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:56.926  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:56.926  6502  6502 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:56.928  6502  6657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:56.928  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:56.928  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:56.928  6502  6657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15a19afc not in the list
09-09 13:41:56.928  6502  6657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:56.928  6502  6657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@deff585 not in the list
09-09 13:41:56.928  6502  6657 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:56.928  6502  6657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:56.928  6502  6657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:56.941  6502  6657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 13:41:56.941  6502  6657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 13:41:56.946  6502  6657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:56.946  6502  6657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:56.946  6502  6657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:41:56.946  6502  6657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 13:41:56.960  7183  7183 D GCM     : COMPAT: Enabling multi user even though supportsMultipleUsers=false
,09-09 13:41:56.973  6502  8437 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 977, name: My test thread name)
,09-09 13:41:56.974  7183  7183 D GCM     : COMPAT: Multi user ser=0 current=0
,09-09 13:41:56.989  1730  5332 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-09 13:41:57.002  7183  8438 I CheckinChimeraService: Checking schedule, now: 1473421317002 next: 1473421346466
09-09 13:41:57.003  7183  8438 I CheckinChimeraService: active receiver: disabled
,09-09 13:41:57.062  8339  8339 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:57.069  8339  8339 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:57.071  8362  8362 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:57.081  8339  8339 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:57.086  8339  8339 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:57.088  8362  8362 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:41:57.089   838  1880 I ActivityManager: Killing 8184:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
09-09 13:41:57.144   838  1347 W libprocessgroup: failed to open /acct/uid_10079/pid_8184/cgroup.procs: No such file or directory
,09-09 13:41:57.153  8391  8391 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:41:57.153  8391  8391 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:41:57.155  8391  8391 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-09 13:41:57.157  8391  8391 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,09-09 13:41:57.161  8339  8339 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:57.164  8391  8440 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:41:57.165  8339  8339 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:57.169  8391  8441 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:41:57.169  8391  8441 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-09 13:41:57.173  8391  8440 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-09 13:41:57.209   838  1801 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8442 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,09-09 13:41:57.213  8391  8440 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:41:57.218  8391  8391 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
09-09 13:41:57.221  8391  8391 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
09-09 13:41:57.222  8391  8391 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,09-09 13:41:57.224  8391  8391 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:41:57.232  8391  8391 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,09-09 13:41:57.345  8442  8442 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 13:41:57.345  8442  8442 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-09 13:41:57.354  8442  8442 V [BNRBootReceiver]: Boot Receiver Return
,09-09 13:41:57.357  8442  8442 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-09 13:41:57.357  8339  8339 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:57.361  8339  8339 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:57.367   838  1801 I ActivityManager: Killing 8252:com.android.chrome/u0a48 (adj 15): empty #11
09-09 13:41:57.383   838  1924 W libprocessgroup: failed to open /acct/uid_10048/pid_8252/cgroup.procs: No such file or directory
,09-09 13:41:57.387  8339  8339 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-09 13:41:57.389  8339  8339 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-09 13:41:57.390  8339  8339 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:41:57.393  8339  8339 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:57.400  8339  8339 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:57.404  8339  8339 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:57.413  8339  8339 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:57.417  8339  8339 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:57.425  8339  8339 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:57.426  6502  6502 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-09 13:41:57.429  8339  8339 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:57.437  8339  8339 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:57.441  8339  8339 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:57.450  8339  8339 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:57.455  8339  8339 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:57.467  8339  8339 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:57.471  8339  8339 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:57.479  8339  8339 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:57.484  8339  8339 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:57.489  8362  8362 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-09 13:41:57.492  8362  8362 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:41:57.499  8339  8339 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:41:57.502  8339  8339 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:41:57.509  8362  8362 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-09 13:41:57.510  8362  8362 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:41:57.595   838  2110 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8469 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-09 13:41:57.616  7752  8467 I NotificationManager: com.google.android.talk: cancel(8) by com.google.android.talk
,09-09 13:41:57.645  7752  7752 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 13:41:57.646  7752  7752 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-09 13:41:57.675  8469  8469 I AppUp4:AppBoxCP: onCreate
,09-09 13:41:57.676  8469  8469 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-09 13:41:57.684  8469  8469 I AppUp4:DB:  setFingerPrint start
09-09 13:41:57.684  8469  8469 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
09-09 13:41:57.690  8469  8469 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
09-09 13:41:57.690  8469  8469 I AppUp4:DB:  SDK version = 21
09-09 13:41:57.690  8469  8469 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-09 13:41:57.692  8469  8469 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,09-09 13:41:57.705  8469  8469 I AppUp4:CustModeStarterReceiver: onReceive
09-09 13:41:57.705  8469  8469 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
09-09 13:41:57.709  8469  8469 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@43b58d4
09-09 13:41:57.709  8469  8469 D AppUp4:CustFacade: isCustomizationCompleted : false
,09-09 13:41:57.716  8469  8469 D AppUp4:CustFacade: isSimDevice : true
09-09 13:41:57.716  8469  8469 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:41:57.717  8469  8469 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-09 13:41:57.744  7752  7752 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 13:41:57.780   838   866 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8495 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-09 13:41:57.813  7752  7752 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-09 13:41:57.815  7752  7752 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-09 13:41:57.848  8495  8495 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:57.849  8495  8495 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 13:41:57.850  8495  8495 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-09 13:41:57.964  8495  8495 I AppConfig: Total System Memory = 906309632
,09-09 13:41:57.966  8495  8495 I GalleryUtils: Application Heap = 96 MB
,09-09 13:41:57.971  8495  8495 I AppConfig: App Tier : NOT_DEF
09-09 13:41:57.977  8495  8495 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,09-09 13:41:58.051   838  1783 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8515 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,09-09 13:41:58.052   838  1783 I ActivityManager: Killing 8277:com.google.android.apps.plus/u0a86 (adj 15): empty #11
09-09 13:41:58.092   838  2110 W libprocessgroup: failed to open /acct/uid_10086/pid_8277/cgroup.procs: No such file or directory
,09-09 13:41:58.117   838  1284 V AlarmManager: RTC_WAKEUP set : Alarm{6ec7aae type 0 when 1473421318114 com.google.android.googlequicksearchbox} when 1473421318114
,09-09 13:41:58.143  8515  8515 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:41:58.143  8515  8515 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 13:41:58.147  8515  8515 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-09 13:41:58.149  8515  8515 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-09 13:41:58.149  8515  8515 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 13:41:58.265  8515  8515 I SystemConfig: BUILD Country: EU
09-09 13:41:58.265  8515  8515 I SystemConfig: BUILD Operator: OPEN
,09-09 13:41:58.382   838   867 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8541 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
09-09 13:41:58.382   838   867 I ActivityManager: Killing 8414:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,09-09 13:41:58.400   301   301 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 23.023ms
,09-09 13:41:58.422   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.373ms
,09-09 13:41:58.443   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 339us total 20.728ms
,09-09 13:41:58.453   838  1924 W libprocessgroup: failed to open /acct/uid_10038/pid_8414/cgroup.procs: No such file or directory
,09-09 13:41:58.462  8515  8539 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-09 13:41:58.462  8515  8539 I SystemConfig: existFile = false
09-09 13:41:58.462  8515  8539 I SystemConfig: canReadFile = false
09-09 13:41:58.462  8515  8539 I SystemConfig: systemFeature RCS result false
09-09 13:41:58.462  8515  8539 D SystemConfig: refreshRcsSupport() :false
09-09 13:41:58.487  8541  8541 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-09 13:41:58.510  8541  8541 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,09-09 13:41:58.510  8541  8541 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-09 13:41:58.510  8541  8541 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-09 13:41:58.510  8541  8541 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-09 13:41:58.510  8541  8541 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,09-09 13:41:58.513   838  2176 I ActivityManager: Killing 7348:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
09-09 13:41:58.542   838  1359 W libprocessgroup: failed to open /acct/uid_10006/pid_7348/cgroup.procs: No such file or directory
09-09 13:41:58.543   838  1359 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.droidguard.DroidGuardService in 1000ms
,09-09 13:41:58.585  7183  8559 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,09-09 13:41:58.600   838  1864 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8560 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:58.679  7183  8559 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,09-09 13:41:58.682  7183  8559 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-09 13:41:58.773  7183  8598 I Icing   : Storage manager: low false usage 2.00MB avail 2.42GB capacity 4.06GB
,09-09 13:41:58.905  7183  8598 E Icing   : Array storage bad crc 3982882812 vs 821933520
09-09 13:41:58.909  7183  8598 E Icing   : Array storage bad crc 198712985 vs 339441540
,09-09 13:41:58.919  7183  8598 E Icing   : Array storage bad crc 3163432917 vs 1803453346
09-09 13:41:58.919  7183  8598 E Icing   : Trie mmap suffix failed
09-09 13:41:58.945  7183  8603 W IcingInternalCorpora: getNumBytesRead when not calculated.
,09-09 13:41:58.967  7183  8598 W Icing   : Docstore bad crc 0x23d7dd68 vs 0xea2f2261
,09-09 13:41:58.972  6502  6657 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 977
09-09 13:41:58.972  6502  6657 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 977, name: My test thread name)
09-09 13:41:58.975  6502  8607 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 978, name: My test thread name)
09-09 13:41:58.975  6502  8607 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 978, thread name: My test thread name)
09-09 13:41:58.975  6502  8607 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 978, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-09 13:41:58.976  6502  6657 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:58.985  6502  8608 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 982, name: My test thread name)
,09-09 13:41:58.987  6502  8608 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 982, thread name: My test thread name): Test exception.
09-09 13:41:58.988  6502  8608 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 982, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-09 13:41:59.004  6502  6657 E com.test.thalitest.ThaliTestRunner: testIsBluetoothEnabled(io.jxcore.node.ConnectivityMonitorTest)
09-09 13:41:59.004  6502  6657 E com.test.thalitest.ThaliTestRunner: Returns proper state of BT when switched on
09-09 13:41:59.004  6502  6657 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-09 13:41:59.004  6502  6657 E com.test.thalitest.ThaliTestRunner:      but: was <false>
,09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: Returns proper state of BT when switched on
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner:      but: was <false>
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testIsBluetoothEnabled(ConnectivityMonitorTest.java:325)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.Thali,TestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:74)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$1.Receiver(RegisterExecuteUT.java:26)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.OutgoingSocketThreadTest)
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-09 13:41:59.021  6502  6657 E com.test.thalitest.ThaliTestRunner:      but: was ""
,09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner:      but: was ""
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.OutgoingSocketThreadTest.testRun(OutgoingSocketThreadTest.java:174)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09,-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:74)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$1.Receiver(RegisterExecuteUT.java:26)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: testExecuteStopOperation(io.jxcore.node.StartStopOperationHandlerTest)
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: mDiscoveryManager1 state should be NOT_STARTED
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner: Expected: is <NOT_STARTED>
09-09 13:41:59.023  6502  6657 E com.test.thalitest.ThaliTestRunner:      but: was <WAITING_FOR_SERVICES_TO_BE_ENABLED>
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: mDiscoveryManager1 state should be NOT_STARTED
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: Expected: is <NOT_STARTED>
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner:      but: was <WAITING_FOR_SERVICES_TO_BE_ENABLED>
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StartStopOperationHandlerTest.testExecuteStopOperation(S,tartStopOperationHandlerTest.java:203)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:74)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$1.Receiver(RegisterExecuteUT.java:26)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-09 13:41:59.024  6502  6657 E com.test.thalitest.ThaliTestRunner: testCheckCurrentOperationStatus(io.jxcore.node.StartStopOperationHandlerTest)
09-09 13:41:59.045  6502  6657 I jxcore-log: Failed to execute UT.
09-09 13:41:59.045  6502  6657 I jxcore-log: 
09-09 13:41:59.048  6502  6657 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
09-09 13:41:59.048  6502  6657 I jxcore-log: 
--------- beginning of crash
09-09 13:41:59.050  6502  6657 E AndroidRuntime: FATAL EXCEPTION: Thread-775
09-09 13:41:59.050  6502  6657 E AndroidRuntime: Process: com.test.thalitest, PID: 6502
09-09 13:41:59.050  6502  6657 E AndroidRuntime: java.lang.NullPointerException: println needs a message
09-09 13:41:59.050  6502  6657 E AndroidRuntime: 	at android.util.Log.println_native(Native Method)
09-09 13:41:59.050  6502  6657 E AndroidRuntime: 	at android.util.Log.e(Log.java:232)
09-09 13:41:59.050  6502  6657 E AndroidRuntime: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:78)
09-09 13:41:59.050  6502  6657 E AndroidRuntime: 	at com.test.thalitest.RegisterExecuteUT$1.Receiver(RegisterExecuteUT.java:26)
09-09 13:41:59.050  6502  6657 E AndroidRuntime: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-09 13:41:59.050  6502  6657 E AndroidRuntime: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-09 13:41:59.050  6502  6657 E AndroidRuntime: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-09 13:41:59.050  6502  6657 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:59.050  6502  6657 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:59.050  6502  6657 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:41:59.050  6502  6657 E AndroidRuntime: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
,09-09 13:41:59.105   838  1819 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
09-09 13:41:59.109  7183  8598 I Icing   : Scored 8 usage reports, missing_corpora 0 update_failed 8
09-09 13:41:59.118   838  1819 D InputDispatcher: Focus left window: Window{2977fa3d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 13:41:59.124  7183  8598 E Icing   : Array storage bad crc 2024692317 vs 0
,09-09 13:41:59.124  7183  8598 E Icing   : Trie mmap node failed
09-09 13:41:59.133  6502  6657 I Process : Sending signal. PID: 6502 SIG: 9
,09-09 13:41:59.184   838  1783 I WindowState: WIN DEATH: Window{2977fa3d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 13:41:59.198   838  1783 D InputDispatcher: Window went away: Window{2977fa3d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 13:41:59.302   838   867 I ActivityManager: Process com.test.thalitest (pid 6502) has died
,09-09 13:41:59.323   838   838 V ActivityManager: Display changed displayId=0
,09-09 13:41:59.331  1748  1748 D DSDPConnection: Display #0 changed.
,09-09 13:41:59.414  1874  1874 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
,09-09 13:41:59.490  8560  8560 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(225): No need to run daily hygiene.
09-09 13:41:59.491  1874  1874 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,09-09 13:41:59.507  1874  1874 I [LGHome]EVENT: [LauncherModel.java:1358:startLoader()]startLoader isLaunching=true
,09-09 13:41:59.514  1874  1994 I [LGHome]Launcher.Model: [LauncherModel.java:1475:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-09 13:41:59.524  1874  1874 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-09 13:41:59.526  1874  1874 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
,09-09 13:41:59.529  1874  1874 I Activity: Activity.onPostResume() called 
09-09 13:41:59.549  8560  8560 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-09 13:41:59.552  8560  8560 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-09 13:41:59.568  8560  8560 I NotificationManager: com.android.vending: cancel(-1050172287) by com.android.vending
,09-09 13:41:59.589   838   892 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8637 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,09-09 13:41:59.592  1874  1874 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
,09-09 13:41:59.617  1874  8649 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
09-09 13:41:59.626   838  1016 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
,09-09 13:41:59.628   838  1016 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
09-09 13:41:59.633   838  1801 D InputDispatcher: Focus entered window: Window{3e2805f8 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
09-09 13:41:59.639  1375  1375 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
,09-09 13:41:59.642   838  1016 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
,09-09 13:41:59.642  1375  1375 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
09-09 13:41:59.642  1375  1375 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
09-09 13:41:59.642  1375  1375 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
09-09 13:41:59.642   838  1016 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
09-09 13:41:59.642   838  1016 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-09 13:41:59.644   838  1016 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1685e527,  pkg=WindowManager.LayoutParams
09-09 13:41:59.644   838  1016 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,09-09 13:41:59.685  8560  8560 I Finsky  : [1] com.google.android.finsky.utils.bp.a(177): Enabling bucket experiment: factor=2.000, zeroDelta=0ms, forceNetwork=false
,09-09 13:41:59.691  1874  1874 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
,09-09 13:41:59.699  8637  8637 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 13:41:59.699  8637  8637 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-09 13:41:59.705  8614  8614 D AndroidRuntime: 
09-09 13:41:59.705  8614  8614 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-09 13:41:59.716  1874  1874 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
09-09 13:41:59.717  1874  1874 I PhoneWindow: [setNavigationBarColor] color=0x 0
09-09 13:41:59.733  8560  8560 I Finsky  : [1] com.google.android.finsky.l.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,09-09 13:41:59.734   838  1783 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,09-09 13:41:59.734  8560  8560 I Finsky  : [1] com.google.android.finsky.l.j.run(214): Finished loading 1 libraries.
09-09 13:41:59.738  8614  8614 D AndroidRuntime: CheckJNI is OFF
09-09 13:41:59.742  8560  8560 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1265): Installer kick - no action, not running yet
09-09 13:41:59.743   838  1783 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6502 uid 10030
09-09 13:41:59.779  2720  2744 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is notificationclass=?; selectionArgs[0] is com.google.android.finsky.download.DownloadBroadcastReceiver; sort is null.
,09-09 13:41:59.782  2720  2744 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@39ec4d83 on behalf of 8560
09-09 13:41:59.783  8637  8637 I MultiDex: VM with version 2.1.0 has multidex support
09-09 13:41:59.784  8637  8637 I MultiDex: install
09-09 13:41:59.784  8637  8637 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-09 13:41:59.814  1874  1874 I [LGHome]Launcher.Model: [LauncherModel.java:2270:run()] LauncherModel bind current page shortcut
,09-09 13:41:59.825  1874  1874 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-09 13:41:59.839   838  1018 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{10298dd u0 com.lge.launcher2/.Launcher t258} time:176997
,09-09 13:41:59.853  1874  1874 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,09-09 13:41:59.857  1874  1874 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-09 13:41:59.859  1874  1874 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-09 13:41:59.861  1874  1874 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: com.google.android.gms signature not valid.  Found: 
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: MIIEQzCCAyugAwIBAgIJAMLgh0ZkSjCNMA0GCSqGSIb3DQEBBAUAMHQxCzAJBgNVBAYTAlVTMRMw
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: EQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29n
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: bGUgSW5jLjEQMA4GA1UECxMHQW5kcm9pZDEQMA4GA1UEAxMHQW5kcm9pZDAeFw0wODA4MjEyMzEz
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: MzRaFw0zNjAxMDcyMzEzMzRaMHQxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYw
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: FAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29nbGUgSW5jLjEQMA4GA1UECxMHQW5k
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: cm9pZDEQMA4GA1UEAxMHQW5kcm9pZDCCASAwDQYJKoZIhvcNAQEBBQADggENADCCAQgCggEBAKtW
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: LgDYO6IIrgqWbxJOKdoR8qtW0I9Y4sypEwPpt1TTcvZApxsdyxMJZ2JORland2qSGT2y5b+3JKke
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: dxiLDmpHpDsz2WCbdxgxRczfey5YZnTJ4VZbH0xqWVW/8lGmPav5xVwnIiJS6HXk+BVKZF+JcWjA
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: sb/GEuq/eFdpuzSqeYTcfi6idkyugwfYwXFU1+5fZKUaRKYCwkkFQVfcAs1fXA5V+++FGfvjJ/Cx
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: URaSxaBvGdGDhfXE28LWuT9ozCl5xw4Yq5OGazvV24mZVSoOO0yZ31j7kYvtwYK6NeADwbSxDdJE
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: qO4k//0zOHKrUiGYXtqw/A0LFFtqoZKFjnkCAQOjgdkwgdYwHQYDVR0OBBYEFMd9jMIhF1Ylmn/T
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: gt9r45jk14alMIGmBgNVHSMEgZ4wgZuAFMd9jMIhF1Ylmn/Tgt9r45jk14aloXikdjB0MQswCQYD
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: VQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNTW91bnRhaW4gVmlldzEUMBIG
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: A1UEChMLR29vZ2xlIEluYy4xEDAOBgNVBAsTB0FuZHJvaWQxEDAOBgNVBAMTB0FuZHJvaWSCCQDC
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: 4IdGZEowjTAMBgNVHRMEBTADAQH/MA0GCSqGSIb3DQEBBAUAA4IBAQBt0lLO74UwLDYKqs6Tm8/y
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: zKkEu116FmH4rkaymUIE0P9KaMftGlMexFlaYjzmB2OxZyl6euNXEsQH8gjwyxCUKRJNexBiGcCE
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: yj6z+a1fuHHvkiaai+KL8W1EyNmgjmyy8AW7P+LLlkR+ho5zEHatRbM/YAnqGcFh5iZBqpknHf1S
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: KMXFh4dd239FJ1jWYfbMDMy3NS5CTMQ2XFI1MvcyUTdZPErjQfTbQe3aDQsQcafEQPD+nqActifK
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: Z0Np0IS9L9kR/wbNvyz6ENwPiTrjV2KRkEjH78ZMcUQXg0L3BYHJ3lc69Vs5Ddf9uUGGMYldX3Wf
09-09 13:41:59.870  8560  8662 V GoogleSignatureVerifier: MBEmh/9iFBDAaTCK
,09-09 13:41:59.910  1874  1874 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,09-09 13:41:59.913  8637  8637 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
09-09 13:41:59.928  1730  1730 D WearableService: callingUid 10006, callindPid: 1730
,09-09 13:41:59.967  1874  1874 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-09 13:41:59.968  1874  1874 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
09-09 13:41:59.968  1874  1874 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,09-09 13:41:59.972   838  2110 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8678 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-09 13:42:00.010  8560  8560 I Finsky  : [1] com.google.android.finsky.c.l.a(253): result=false type=4
09-09 13:42:00.010  8637  8637 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-09 13:42:00.010  8637  8637 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1eefef64: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-09 13:42:00.011  8637  8637 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-09 13:42:00.013  1874  1874 W Resources: Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
09-09 13:42:00.014  8637  8637 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
09-09 13:42:00.016  1874  1874 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
09-09 13:42:00.017  1874  1874 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
09-09 13:42:00.018  1874  1874 W Resources: Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
09-09 13:42:00.022  1874  1874 W Resources: Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
09-09 13:42:00.032  1874  1874 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
09-09 13:42:00.032  1874  1874 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
09-09 13:42:00.036  1874  1874 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
,09-09 13:42:00.037  1874  1874 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
09-09 13:42:00.038  1874  1874 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
09-09 13:42:00.046  8637  8637 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
09-09 13:42:00.048  1874  1874 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
09-09 13:42:00.059  1874  1874 W Resources: Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,09-09 13:42:00.069  7183  8598 W Icing   : Error while loading LangUtil; unable to load BreakIntoWordsV2: undefined symbol: IcingExtBreakIntoWordsV2
09-09 13:42:00.079  1375  1375 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-09 13:42:00.079  1375  1375 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-09 13:42:00.081  1375  1375 I [SystemUI]Clock: called onTimeUpdated()
09-09 13:42:00.082  1375  1375 I LgeClockWidgetControlView: called onTimeUpdated()
09-09 13:42:00.083  1375  1375 I [SystemUI]DateView: called onTimeUpdated()
09-09 13:42:00.084  1375  1375 I [SystemUI]DateView: called onTimeUpdated()
09-09 13:42:00.085  1375  1375 D KeyguardUpdateMonitor: handleTimeUpdate
09-09 13:42:00.093  8637  8637 D ChimeraCfgMgr: Reading stored module config
,09-09 13:42:00.109  8560  8560 I Finsky  : [1] com.google.android.finsky.services.bd.a(1075): Restore complete with 0 success and 0 failed.
,09-09 13:42:00.115  8614  8614 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-09 13:42:00.128  8678  8678 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:42:00.150  7183  8598 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1
09-09 13:42:00.150  7183  8598 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
,09-09 13:42:00.159  8560  8560 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
09-09 13:42:00.160  8560  8560 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
09-09 13:42:00.189   838   892 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,09-09 13:42:00.210  7183  7300 I CheckinService: Done disabling old GoogleServicesFramework version
,09-09 13:42:00.227  7183  8598 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
,09-09 13:42:00.231  7183  8598 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000006@DynamiteModulesA_GmsCore_prodlmp_xhdpi_release.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000006/DynamiteModulesA_GmsCore_prodlmp_xhdpi_release.apk': Failed to open oat filename for reading: No such file or directory
09-09 13:42:00.233  7183  8598 D ChimeraFileApk: Classloading successful. Optimized code found.
09-09 13:42:00.236  7183  8598 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
09-09 13:42:00.239  1874  1874 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,09-09 13:42:00.267  8637  8637 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
09-09 13:42:00.267  8637  8637 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-09 13:42:00.290  8637  8695 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-09 13:42:00.323   838  1819 I ActivityManager: Killing 8391:com.lge.lgdmsclient/1000 (adj 15): empty #11
,09-09 13:42:00.327  1874  1874 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-09 13:42:00.327  1874  1874 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
09-09 13:42:00.328  1874  1874 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
09-09 13:42:00.328  1874  1874 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-09 13:42:00.348  7183  8598 D GoogleCertificatesImpl: Fetched 163 Google release certificates
,09-09 13:42:00.394   838  1060 W PackageSettings: Skipping PackageSetting{3e09c45a com.example.hello/10317} due to missing metadata
,09-09 13:42:00.397   838  2110 W libprocessgroup: failed to open /acct/uid_1000/pid_8391/cgroup.procs: No such file or directory
,09-09 13:42:00.432   838  1060 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
,09-09 13:42:00.473  1375  1375 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,09-09 13:42:00.477  1730  2541 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 13:42:00.478  3648  3648 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-09 13:42:00.478  3648  3648 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-09 13:42:00.479  3648  3648 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-09 13:42:00.479  3648  3648 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
09-09 13:42:00.479  3648  3648 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:42:00.479  3648  3648 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:42:00.479  3648  3648 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:42:00.479  3648  3648 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
09-09 13:42:00.479  3648  3648 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:42:00.479  3648  3648 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:42:00.479  3648  3648 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
09-09 13:42:00.479  3648  3648 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
09-09 13:42:00.483  1837  1837 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
09-09 13:42:00.483  1375  1375 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-09 13:42:00.485  1874  1874 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-09 13:42:00.487   838  1286 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-09 13:42:00.488  1874  1874 I Choreographer: Skipped 38 frames!  The application may be doing too much work on its main thread.
09-09 13:42:00.489  1874  1874 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
09-09 13:42:00.491  1874  1874 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-09 13:42:00.492  1874  1874 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-09 13:42:00.492  1874  1874 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
09-09 13:42:00.493  1874  1874 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,09-09 13:42:00.497  1874  1874 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-09 13:42:00.499  1874  1874 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
09-09 13:42:00.501  1874  1874 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-09 13:42:00.503  1874  1874 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
09-09 13:42:00.505  1874  1874 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
09-09 13:42:00.509  1874  2223 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-09 13:42:00.509  1874  2223 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-09 13:42:00.514  1874  1874 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-09 13:42:00.514  1874  1874 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,09-09 13:42:00.515  1621  1621 E b       : Unable to connect to the editor to retrieve text... will retry later
09-09 13:42:00.533  1949  1949 I art     : Explicit concurrent mark sweep GC freed 4112(320KB) AllocSpace objects, 5(119KB) LOS objects, 40% free, 12MB/20MB, paused 3.081ms total 98.039ms
,09-09 13:42:00.612   838   838 D administrator: Handling package changes for user 0
,09-09 13:42:00.618  1874  1874 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
09-09 13:42:00.639  1375  1375 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,09-09 13:42:00.644  1375  1375 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-09 13:42:00.659  1874  1874 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-09 13:42:00.660  1874  1874 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,09-09 13:42:00.663  1874  1874 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-09 13:42:00.665  1375  1515 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-09 13:42:00.665  1375  1515 D KeyguardModel: createShortcutInfo...
09-09 13:42:00.670  1375  1515 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-09 13:42:00.670  1375  1515 D KeyguardModel: createShortcutInfo...
09-09 13:42:00.672  1375  1515 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:42:00.679  1375  1515 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,09-09 13:42:00.680  1375  1515 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-09 13:42:00.680  1375  1515 D KeyguardModel: createShortcutInfo...
09-09 13:42:00.682  1375  1515 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:42:00.682  1375  1515 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-09 13:42:00.685  1375  1515 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-09 13:42:00.685  1375  1515 D KeyguardModel: createShortcutInfo...
09-09 13:42:00.687  1375  1515 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:42:00.687  1375  1515 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-09 13:42:00.688  1375  1515 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-09 13:42:00.688  1375  1515 D KeyguardModel: createShortcutInfo...
09-09 13:42:00.705  7183  8598 I Icing   : updateResources: need to parse ozd{com.google.android.gms}
,09-09 13:42:00.705  1375  1375 D KeyguardModel: handleShortcutListChanged...
09-09 13:42:00.708  1375  1515 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-09 13:42:00.708  1375  1515 D KeyguardModel: createShortcutInfo...
09-09 13:42:00.711  1375  1515 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-09 13:42:00.711  1375  1515 D KeyguardModel: createShortcutInfo...
09-09 13:42:00.713  1375  1515 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:42:00.713  1375  1515 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-09 13:42:00.714  1375  1515 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-09 13:42:00.714  1375  1515 D KeyguardModel: createShortcutInfo...
09-09 13:42:00.715  1375  1515 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:42:00.716  1375  1515 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-09 13:42:00.719  1375  1515 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-09 13:42:00.719  1375  1515 D KeyguardModel: createShortcutInfo...
,09-09 13:42:00.723  1375  1515 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:42:00.724  1375  1515 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-09 13:42:00.724  1874  1874 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@38c1ee2e time:177882
09-09 13:42:00.728  1375  1515 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-09 13:42:00.728  1375  1515 D KeyguardModel: createShortcutInfo...
,09-09 13:42:00.737  1375  1375 D KeyguardModel: handleShortcutListChanged...
09-09 13:42:00.760  1949  8712 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-09 13:42:00.807  1874  1874 I art     : Explicit concurrent mark sweep GC freed 23307(1276KB) AllocSpace objects, 20(2MB) LOS objects, 40% free, 15MB/25MB, paused 2.908ms total 81.515ms
,09-09 13:42:00.811   838  1775 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8713 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:42:00.853   838  1844 I ActivityManager: Killing 8442:com.lge.bnr/1000 (adj 15): empty #11
,09-09 13:42:00.912  1949  8712 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 150 ms] updated apps [took 150 ms] 
,09-09 13:42:00.950   838   866 W libprocessgroup: failed to open /acct/uid_1000/pid_8442/cgroup.procs: No such file or directory
09-09 13:42:00.970  1874  1874 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,09-09 13:42:00.992   838  1060 I art     : Explicit concurrent mark sweep GC freed 49365(3MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/35MB, paused 9.020ms total 438.687ms
,09-09 13:42:00.995   838  1880 I art     : WaitForGcToComplete blocked for 23.063ms for cause Explicit
09-09 13:42:01.011   838   838 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,09-09 13:42:01.013   838   838 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-09 13:42:01.017   838   838 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 13:42:01.033   838  1349 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
,09-09 13:42:01.086  8614  8614 D AndroidRuntime: Shutting down VM
,09-09 13:42:01.104  1784  1784 D LCardEmulationManager: getHceAppCount hostAppNum : 0
09-09 13:42:01.104  1784  1784 D LCardEmulationManager: getDefaultRoute
,09-09 13:42:01.169   838  1880 I art     : Explicit concurrent mark sweep GC freed 4819(245KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.524ms total 172.818ms
,09-09 13:42:01.184   293   354 I ThermalEngine: Sensor:pa_therm0:38000 mC
,09-09 13:42:01.205  7183  8598 I Icing   : Internal init done: storage state 0
,09-09 13:42:01.270  7183  8598 I Icing   : 22 corpora need re-polling
,09-09 13:42:01.283  8713  8713 I MusicStore: Database version: 120
,09-09 13:42:01.318  7183  8598 I Icing   : Post-init done
,09-09 13:42:01.361   838  1060 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8738 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-09 13:42:01.403   245   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:42:01.403   245   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-09 13:42:01.403   245   343 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:42:01.405  8713  8713 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-09 13:42:01.435   838   890 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:42:01.509  8560  8633 E PlayCommon: [1067] com.google.android.play.a.k.run(1259): Failed to save PlayMetalog: java.io.FileNotFoundException: /data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com.metalog/play_metalog.log: open failed: EROFS (Read-only file system)
,09-09 13:42:01.510  8560  8633 E PlayCommon: [1067] com.google.android.play.a.k.run(1265): Failed to save LogsUploadAttempt: java.io.FileNotFoundException: /data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com.metalog/logs_upload_attempt.log: open failed: EROFS (Read-only file system)
,09-09 13:42:01.516  1874  2557 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-09 13:42:01.517  1874  2557 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-09 13:42:01.525  1874  2557 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
09-09 13:42:01.527  1730  1746 I art     : Explicit concurrent mark sweep GC freed 49847(3MB) AllocSpace objects, 32(535KB) LOS objects, 40% free, 15MB/25MB, paused 1.550ms total 120.329ms
09-09 13:42:01.527  1874  2557 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0

```
