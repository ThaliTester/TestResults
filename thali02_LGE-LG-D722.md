#### Test 80912877664003a_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-12 09:20:47.001  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-12 09:20:47.564  6651  6651 D AndroidRuntime: 
08-12 09:20:47.564  6651  6651 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 09:20:47.568  6651  6651 D AndroidRuntime: CheckJNI is OFF
08-12 09:20:47.735  2886  2886 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19959
--------- beginning of system
08-12 09:20:47.754   843  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{38889c36 type 2 when 120000 com.google.android.gms} when 120000
08-12 09:20:47.817  6651  6651 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-12 09:20:47.835   843   862 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 09:20:47.894   843   862 D ActivityManager: setTaskToReturnTo : TaskRecord{39872737 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 09:20:47.896   843   862 D ActivityManager: setTaskToReturnTo : TaskRecord{39872737 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 09:20:47.917   843   862 D WindowStateEx: AppWindowTokenEx init.. 
08-12 09:20:47.928   843  1021 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-12 09:20:47.948  1950  1950 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-12 09:20:47.951   843   862 D InputDispatcher: Focus left window: Window{26892138 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-12 09:20:47.952  6651  6651 D AndroidRuntime: Shutting down VM
08-12 09:20:47.955   843  1021 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-12 09:20:47.969   843  1021 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 09:20:47.969   843  1021 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-12 09:20:47.995   843  1021 D SplitWindow: check instance of lgWin Window{62dc62f u0 Starting com.test.thalitest}
08-12 09:20:48.003  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-12 09:20:48.003  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-12 09:20:48.003  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-12 09:20:48.039   843  1885 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6671 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 09:20:48.051  1950  1950 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-12 09:20:48.114  1950  1950 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-12 09:20:48.125  2028  2028 I HotwordDetector: Closing mic
08-12 09:20:48.132   843  1061 I WindowStateAnimator: Starting window displayed
08-12 09:20:48.136  2028  2580 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@3acbdb00
08-12 09:20:48.136  2028  2580 V AudioRecord: stop()
08-12 09:20:48.136  2028  2580 D AudioRecord: AudioRecord->stop()
08-12 09:20:48.137   276  1300 V AudioFlinger: RecordHandle::stop()
08-12 09:20:48.137   276  1300 V AudioFlinger: RecordThread::stop
08-12 09:20:48.140   843  1019 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-12 09:20:48.140   843  1019 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-12 09:20:48.144   843  1019 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-12 09:20:48.144   843  1019 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-12 09:20:48.144   843  1019 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-12 09:20:48.144  1375  1375 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-12 09:20:48.146  1375  1375 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-12 09:20:48.146  1375  1375 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-12 09:20:48.146  1375  1375 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-12 09:20:48.147   843  1019 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@13b35926,  pkg=WindowManager.LayoutParams
08-12 09:20:48.147   843  1019 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-12 09:20:48.150   276  1300 V AudioFlinger: Record stopped OK
08-12 09:20:48.152   276  1300 V AudioPolicyManager: stopInput() input 17
08-12 09:20:48.153   276  1300 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
08-12 09:20:48.153   276  1300 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
08-12 09:20:48.153   276  1063 V AudioPolicyService: AudioCommandThread() waking up
08-12 09:20:48.153   276  1063 V AudioPolicyService: AudioCommandThread() processing release audio patch
08-12 09:20:48.153   276  1063 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
08-12 09:20:48.153   276  1063 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
08-12 09:20:48.153   276  1063 V AudioFlinger: ThreadBase::setParameters() routing=0
08-12 09:20:48.153   276  1063 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-12 09:20:48.155   276  2611 V AudioFlinger: processConfigEvents_l() remaining events 1
08-12 09:20:48.155   276  2611 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3e5a000
08-12 09:20:48.160   276  2611 D audio_hw_primary: in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
,08-12 09:20:48.206   276  2611 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
08-12 09:20:48.206   276  2611 V audio_hw_primary: disable_audio_route: enter: usecase(7)
08-12 09:20:48.206   276  2611 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
08-12 09:20:48.206   276  2611 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-12 09:20:48.209   276  2611 V audio_hw_primary: disable_audio_route: exit
08-12 09:20:48.209   276  2611 E audio_hw_primary: disable_snd_device: enter 144
08-12 09:20:48.209   276  2611 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
08-12 09:20:48.209   276  2611 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
08-12 09:20:48.214   276  2611 V audio_hw_primary: stop_input_stream: exit: status(0)
08-12 09:20:48.214   276  2611 V audio_hw_primary: in_standby: exit:  status(0)
08-12 09:20:48.214   276  2611 V AudioFlinger: RecordThread: loop stopping
08-12 09:20:48.214   276  1063 V AudioPolicyService: AudioCommandThread() going to sleep
08-12 09:20:48.214   276  1300 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
08-12 09:20:48.214   276  1300 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
08-12 09:20:48.214   276  1300 V AudioPolicyService: AudioCommandThread() adding update audio patch list
08-12 09:20:48.214   276  1300 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
08-12 09:20:48.215   276  1064 V AudioPolicyService: AudioCommandThread() waking up
08-12 09:20:48.215   276  1064 V AudioPolicyService: AudioCommandThread() processing update audio patch list
08-12 09:20:48.215   276  1064 V AudioPolicyService: AudioCommandThread() going to sleep
08-12 09:20:48.215   276  1300 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
08-12 09:20:48.215   276  1300 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
08-12 09:20:48.215   276  1063 V AudioPolicyService: AudioCommandThread() waking up
08-12 09:20:48.215   276  1063 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
08-12 09:20:48.215   276  1063 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 276
08-12 09:20:48.216   276  1063 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
08-12 09:20:48.216   276  1063 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-12 09:20:48.216   276  2611 V AudioFlinger: RecordThread: loop starting
08-12 09:20:48.216   276  2611 V AudioFlinger: processConfigEvents_l() remaining events 1
08-12 09:20:48.216   276  2611 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
08-12 09:20:48.216   276  2611 V audio_hw_primary: in_set_parameters: exit: status(0)
08-12 09:20:48.216   276  2611 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3e5a000
08-12 09:20:48.216   276  2611 V AudioFlinger: RecordThread: loop stopping
08-12 09:20:48.216   276  1063 V AudioPolicyService: AudioCommandThread() going to sleep
08-12 09:20:48.223  2028  2580 V AudioRecord: stop()
08-12 09:20:48.224  2028  2580 V AudioRecord: stop()
08-12 09:20:48.224  2028  2580 V AudioRecord: stop()
08-12 09:20:48.225   276  1593 V AudioFlinger: RecordHandle::stop()
08-12 09:20:48.225   276  1593 V AudioFlinger: RecordThread::stop
08-12 09:20:48.225   276  1593 V AudioPolicyManager: releaseInput() 17
08-12 09:20:48.225   276  1593 V AudioPolicyManager: closeInput(17)
08-12 09:20:48.225   276  1593 V AudioFlinger: closeInput() 17
08-12 09:20:48.225   276  1593 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-12 09:20:48.226   276  1593 V AudioFlinger: ThreadBase::exit
08-12 09:20:48.226   276  2611 V AudioFlinger: RecordThread: loop starting
08-12 09:20:48.226  2082  3571 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-12 09:20:48.226   276  2611 V AudioFlinger: RecordThread 0xb3e5a000 exiting
08-12 09:20:48.226   843  1061 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-12 09:20:48.226   276  1593 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546e1a0)
08-12 09:20:48.226   276  1593 D audio_hw_primary: in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
08-12 09:20:48.226  2886  3964 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-12 09:20:48.226   276  1593 V audio_hw_primary: in_standby: exit:  status(0)
08-12 09:20:48.226   276  1593 V AudioPolicyService: AudioCommandThread() adding update audio port list
08-12 09:20:48.226   276  1593 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
08-12 09:20:48.227   276  1064 V AudioPolicyService: AudioCommandThread() waking up
08-12 09:20:48.227   276  1064 V AudioPolicyService: AudioCommandThread() processing update audio port list
08-12 09:20:48.227   276  1064 V AudioPolicyService: AudioCommandThread() going to sleep
08-12 09:20:48.227   276  1593 V AudioPolicyManager: releaseInput() exit
08-12 09:20:48.227  1375  2492 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-12 09:20:48.228  2028  2052 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-12 09:20:48.228  3166  3181 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-12 09:20:48.227  1781  1801 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-12 09:20:48.228   276  1593 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
08-12 09:20:48.228   276  1593 V AudioFlinger: removeClient_l() pid 2028, calling pid 276
08-12 09:20:48.228   276  1593 V AudioFlinger: releasing 16 from 2028 for -1
08-12 09:20:48.228   276  1593 V AudioFlinger:  decremented refcount to 0
08-12 09:20:48.228   276  1593 V AudioFlinger: purging stale effects
08-12 09:20:48.239  2028  2597 I HotwordRecognitionRnr: Hotword detection finished
08-12 09:20:48.241  2028  2593 I HotwordRecognitionRnr: Stopping hotword detection.
08-12 09:20:48.272  6671  6671 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-12 09:20:48.385  6671  6671 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-12 09:20:48.445  6671  6671 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 706-710)
08-12 09:20:48.445  6671  6671 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 09:20:48.490  6671  6671 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {59cb581}
08-12 09:20:48.492  6671  6671 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 09:20:48.505  6671  6671 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 09:20:48.528  6671  6671 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-12 09:20:48.530  6671  6671 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 09:20:48.536  6671  6671 E SysUtils: ApplicationContext is null in ApplicationStatus
08-12 09:20:48.641  6671  6671 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-12 09:20:48.650  6671  6671 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 09:20:48.650  6671  6671 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 09:20:48.651  6671  6671 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 09:20:48.651  6671  6671 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 09:20:48.651  6671  6671 I Adreno-EGL: Build Date: 03/02/15 Mon
08-12 09:20:48.651  6671  6671 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-12 09:20:48.651  6671  6671 I Adreno-EGL: Remote Branch: 
08-12 09:20:48.651  6671  6671 I Adreno-EGL: Local Patches: 
08-12 09:20:48.651  6671  6671 I Adreno-EGL: Reconstruct Branch: 
08-12 09:20:48.661  1375  1375 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
08-12 09:20:48.688  1913  1913 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
08-12 09:20:48.702   843  1289 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-12 09:20:48.715   843   883 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6714 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-12 09:20:48.732  1950  1950 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-12 09:20:48.734  1950  1950 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-12 09:20:48.734  1950  1950 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
08-12 09:20:48.746   306   306 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 389us total 34.506ms
08-12 09:20:48.757   843   843 D administrator: Handling package changes for user 0
08-12 09:20:48.774   306   306 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 385us total 24.514ms
08-12 09:20:48.777   276  1594 V AudioPolicyService: registerClient() client 0xb3d7b0a0, uid 10030
08-12 09:20:48.785  1375  1375 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-12 09:20:48.799   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 24.357ms
08-12 09:20:48.805   843  1020 D BluetoothManagerService: Message: 20
08-12 09:20:48.805   843  1020 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35a312ff:true
08-12 09:20:48.807  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
08-12 09:20:48.807  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
08-12 09:20:48.807  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
08-12 09:20:48.807  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
08-12 09:20:48.807  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
08-12 09:20:48.807  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
08-12 09:20:48.807  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
08-12 09:20:48.807  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
08-12 09:20:48.807  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
08-12 09:20:48.807  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
08-12 09:20:48.808  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
08-12 09:20:48.808  1375  1375 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
08-12 09:20:48.808  1375  1375 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-12 09:20:48.813  2082  2097 D BluetoothAdapterService(66331239): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f66b275
08-12 09:20:48.818  1950  1950 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-12 09:20:48.887  6714  6714 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-12 09:20:48.947   843   843 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-12 09:20:48.947   843   843 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-12 09:20:48.947   843   843 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,08-12 09:20:48.952   843   843 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
08-12 09:20:48.964   843   843 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,08-12 09:20:48.966   843   843 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@4ecacad
08-12 09:20:48.994   843   882 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-12 09:20:49.007  6671  6671 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 09:20:49.022  6671  6671 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 09:20:49.033  6671  6671 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-12 09:20:49.038  6671  6671 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 09:20:49.038  6671  6671 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-12 09:20:49.056  6671  6671 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-12 09:20:49.067  6671  6671 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 09:20:49.067  6671  6671 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 09:20:49.143   843   882 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-12 09:20:49.150  6671  6671 I Activity: Activity.onPostResume() called 
08-12 09:20:49.160  6671  6763 D OpenGLRenderer: Render dirty regions requested: true
08-12 09:20:49.161  6671  6763 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 09:20:49.169  6671  6763 D OpenGLRenderer: Enabling debug mode 0
,08-12 09:20:49.189  6671  6671 D Atlas   : Validating map...
,08-12 09:20:49.195   843  1937 D SplitWindow: check instance of lgWin Window{3ba356bf u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 09:20:49.221  1950  1950 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-12 09:20:49.221  6671  6736 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-12 09:20:49.230  1753  1753 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
08-12 09:20:49.244  6714  6768 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-12 09:20:49.244  6714  6768 I Babel_SMS: MmsConfig.loadMmsSettings
,08-12 09:20:49.258   843  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{34412f53 type 2 when 121507 com.google.android.gms} when 121507
,08-12 09:20:49.260  6714  6768 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
08-12 09:20:49.261  6714  6768 I Babel_SMS: MmsConfig.loadFromDatabase
08-12 09:20:49.271   843  4925 D InputDispatcher: Focus entered window: Window{3ba356bf u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 09:20:49.289  6714  6768 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-12 09:20:49.289  6714  6768 I Babel_SMS: MmsConfig.loadFromResources
08-12 09:20:49.291  6714  6768 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
08-12 09:20:49.292  6714  6768 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
08-12 09:20:49.318  1852  1852 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-12 09:20:49.318  1852  1852 D LCardEmulationManager: getDefaultRoute
,08-12 09:20:49.318   843   882 D LocationProviderProxy: applying state to connected service
,08-12 09:20:49.347   843  2036 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-12 09:20:49.347  6714  6714 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
08-12 09:20:49.347  6714  6714 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
08-12 09:20:49.347  6714  6714 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
08-12 09:20:49.347  6714  6714 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
08-12 09:20:49.347  6714  6714 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
08-12 09:20:49.347  6714  6714 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
08-12 09:20:49.347  6714  6714 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
08-12 09:20:49.348  6714  6714 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
08-12 09:20:49.348  6714  6714 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
08-12 09:20:49.348  6714  6714 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
08-12 09:20:49.348  6714  6714 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
08-12 09:20:49.348  6714  6714 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
08-12 09:20:49.348  6714  6714 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
08-12 09:20:49.348  6714  6714 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
08-12 09:20:49.348  6714  6714 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
08-12 09:20:49.348  6714  6714 D SensorManager: found sensor: Motion Accel, handle=46
,08-12 09:20:49.357   843  1021 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s363ms
08-12 09:20:49.358   843  1021 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3808a4a4 u0 com.test.thalitest/.MainActivity t259} time:121623
08-12 09:20:49.383  6671  6671 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1422edf3 time:121648
,08-12 09:20:49.418  6714  6714 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-12 09:20:49.428  6714  6714 I Babel_Crash: startup - clean
08-12 09:20:49.453  6671  6671 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6671
,08-12 09:20:49.517  6714  6775 I Babel   : deleted: false for 0
,08-12 09:20:49.534  6714  6749 I art     : CheckpointMarkThreadRoots callback created = 0xaaf49980
,08-12 09:20:49.597  6714  6749 I art     : CheckpointMarkThreadRoots callback created = 0xaaf49970
,08-12 09:20:49.695   843  1911 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6779 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-12 09:20:49.754  6714  6714 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,08-12 09:20:49.761  6714  6714 W AudioCapabilities: Unsupported mime audio/adpcm
08-12 09:20:49.762  6714  6714 W AudioCapabilities: Unsupported mime audio/g726
08-12 09:20:49.763  6714  6714 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-12 09:20:49.764  6714  6714 W AudioCapabilities: Unsupported mime audio/wma-voice
08-12 09:20:49.768  6714  6714 W VideoCapabilities: Unsupported mime video/mjpg
,08-12 09:20:49.781  6714  6714 W VideoCapabilities: Unsupported mime video/theora
,08-12 09:20:49.835  6714  6714 W AudioCapabilities: Unsupported mime audio/evrc
,08-12 09:20:49.839  6714  6714 W AudioCapabilities: Unsupported mime audio/qcelp
08-12 09:20:49.845  6714  6714 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-12 09:20:49.862  6714  6714 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-12 09:20:49.863  6714  6714 W AudioCapabilities: Unsupported mime audio/qcelp
08-12 09:20:49.864  6714  6714 W AudioCapabilities: Unsupported mime audio/evrc
08-12 09:20:49.878  6714  6714 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-12 09:20:49.896  6714  6714 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-12 09:20:49.897  6779  6779 I AppUp4:AppBoxCP: onCreate
,08-12 09:20:49.905  6779  6779 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-12 09:20:49.910  6714  6714 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-12 09:20:49.918  6779  6779 I AppUp4:DB:  setFingerPrint start
08-12 09:20:49.919  6779  6779 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
,08-12 09:20:49.928  6714  6714 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-12 09:20:49.930  6779  6779 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
08-12 09:20:49.930  6779  6779 I AppUp4:DB:  SDK version = 21
08-12 09:20:49.930  6779  6779 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-12 09:20:49.932  6779  6779 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-12 09:20:49.932  6714  6714 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-12 09:20:49.944  6714  6714 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-12 09:20:49.954  6779  6779 I AppUp4:CustModeStarterReceiver: onReceive
08-12 09:20:49.954  6779  6779 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,08-12 09:20:49.965  6779  6779 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3413e05
08-12 09:20:49.965  6779  6779 D AppUp4:CustFacade: isCustomizationCompleted : false
08-12 09:20:50.014  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-12 09:20:50.015  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-12 09:20:50.016  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-12 09:20:50.033   843   862 I ActivityManager: Process com.google.android.apps.docs (pid 6444) has died
,08-12 09:20:50.036  6779  6779 D AppUp4:CustFacade: isSimDevice : true
08-12 09:20:50.042  6779  6779 D AppUp4:CustModeStarterReceiver: begin check event
08-12 09:20:50.042  6779  6779 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-12 09:20:50.101   843   861 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6801 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-12 09:20:50.144  6671  6671 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 09:20:50.171   843  1973 I ActivityManager: Process com.google.android.apps.plus (pid 6274) has died
,08-12 09:20:50.231  6714  6714 I vclib   : onServiceConnected
,08-12 09:20:50.233  6714  6714 W Babel   : Attempted to change video mute state without an active call.
08-12 09:20:50.240  6714  6799 I NotificationManager: com.google.android.talk: cancel(8) by com.google.android.talk
08-12 09:20:50.257  6801  6801 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 09:20:50.257  6801  6801 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-12 09:20:50.257  6801  6801 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-12 09:20:50.269  6714  6714 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-12 09:20:50.269  6714  6714 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-12 09:20:50.345  6714  6714 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-12 09:20:50.427  6671  6773 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1631415040
,08-12 09:20:50.430  6714  6714 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-12 09:20:50.431  6714  6714 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-12 09:20:50.456  6671  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 09:20:50.456  6671  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 09:20:50.456  6671  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 09:20:50.456  6671  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 09:20:50.456  6671  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-12 09:20:50.457  6671  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18595074 added. We now have 1 listener(s)
,08-12 09:20:50.460  6801  6801 I AppConfig: Total System Memory = 906309632
08-12 09:20:50.460  6714  6714 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
08-12 09:20:50.463  6801  6801 I GalleryUtils: Application Heap = 96 MB
08-12 09:20:50.472  6801  6801 I AppConfig: App Tier : NOT_DEF
,08-12 09:20:50.477   843  1937 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 09:20:50.483  6671  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
08-12 09:20:50.485  6671  6773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
,08-12 09:20:50.489  6671  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 09:20:50.490  6671  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 09:20:50.492  6801  6801 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-12 09:20:50.507  6671  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 09:20:50.507  6671  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 09:20:50.507  6671  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 09:20:50.507  6671  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-12 09:20:50.507  6671  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 09:20:50.507  6671  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 09:20:50.507  6671  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 09:20:50.507  6671  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 09:20:50.507  6671  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 09:20:50.507  6671  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 09:20:50.507  6671  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 09:20:50.507  6671  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 09:20:50.507  6671  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 09:20:50.507  6671  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 09:20:50.507  6671  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3de339e3 added. We now have 1 listener(s)
08-12 09:20:50.508  6671  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 09:20:50.531  6671  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 09:20:50.531  6671  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 09:20:50.532  6671  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 09:20:50.532  6671  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 09:20:50.532  6671  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 09:20:50.539  6671  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 09:20:50.587   843   862 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6826 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-12 09:20:50.589   843  1880 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 09:20:50.598  6671  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-12 09:20:50.609  2082  2098 D BluetoothAdapterService(66331239): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f66b275
,08-12 09:20:50.613  6671  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-12 09:20:50.615  6671  6773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 09:20:50.615  6671  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 09:20:50.615  6671  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 09:20:50.615  6671  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 09:20:50.615  6671  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 09:20:50.615  6671  6773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 09:20:50.615  6671  6773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 09:20:50.615  6671  6773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 09:20:50.616  6671  6773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 09:20:50.616  6671  6773 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 09:20:50.619  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 09:20:50.621  6671  6773 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 09:20:50.623  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 09:20:50.663  6671  6671 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 09:20:50.666  6826  6826 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 09:20:50.666  6826  6826 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 09:20:50.666  6826  6826 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-12 09:20:50.667  6826  6826 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-12 09:20:50.667  6826  6826 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-12 09:20:50.820  6671  6685 I art     : CheckpointMarkThreadRoots callback created = 0x9a7261e0
,08-12 09:20:50.845  6826  6826 I SystemConfig: BUILD Country: EU
08-12 09:20:50.845  6826  6826 I SystemConfig: BUILD Operator: OPEN
,08-12 09:20:50.862  6671  6685 I art     : CheckpointMarkThreadRoots callback created = 0x9a7261b0
,08-12 09:20:50.891   843  4925 I ActivityManager: Process com.android.vending (pid 6384) has died
08-12 09:20:50.996   843  1880 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6846 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,08-12 09:20:51.045  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-12 09:20:51.045  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-12 09:20:51.045  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-12 09:20:51.056  6826  6844 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-12 09:20:51.057  6826  6844 I SystemConfig: existFile = false
08-12 09:20:51.057  6826  6844 I SystemConfig: canReadFile = false
,08-12 09:20:51.057  6826  6844 I SystemConfig: systemFeature RCS result false
08-12 09:20:51.057  6826  6844 D SystemConfig: refreshRcsSupport() :false
,08-12 09:20:51.098   843  2034 I art     : Explicit concurrent mark sweep GC freed 62944(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/35MB, paused 3.814ms total 210.683ms
,08-12 09:20:51.133  6846  6846 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-12 09:20:51.167  6846  6846 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-12 09:20:51.167  6846  6846 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-12 09:20:51.167  6846  6846 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-12 09:20:51.167  6846  6846 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-12 09:20:51.167  6846  6846 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,08-12 09:20:51.169   843  4925 I ActivityManager: Killing 6363:com.lge.eula/1000 (adj 15): empty #11
08-12 09:20:51.226   843  1973 W libprocessgroup: failed to open /acct/uid_1000/pid_6363/cgroup.procs: No such file or directory
,08-12 09:20:51.238  3343  6864 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,08-12 09:20:51.275   843  1880 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6865 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-12 09:20:51.324  3343  6864 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,08-12 09:20:51.324  3343  6864 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,08-12 09:20:51.360  3343  3700 I Icing   : updateResources: need to parse ozd{com.google.android.gms}
,08-12 09:20:51.428  1753  4926 I art     : Explicit concurrent mark sweep GC freed 36734(2MB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 14MB/24MB, paused 1.729ms total 96.535ms
,08-12 09:20:51.446   292   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
08-12 09:20:51.448  3343  6885 W IcingInternalCorpora: getNumBytesRead when not calculated.
,08-12 09:20:51.522   276  1594 V AudioFlinger: 2886 died, releasing its sessions
08-12 09:20:51.522   276  1594 V AudioFlinger:  pid 1781 @ 0
08-12 09:20:51.522   276  1594 V AudioFlinger:  pid 3166 @ 1
08-12 09:20:51.522   276  1594 V AudioFlinger:  pid 3166 @ 2
08-12 09:20:51.523  6671  6843 W jxcore-log: Initializing JXcore engine
,08-12 09:20:51.526  6671  6843 W jxcore-log: JXcore engine is ready
08-12 09:20:51.555   843  1956 I ActivityManager: Process com.lge.music (pid 2886) has died
,08-12 09:20:51.638  6843  6843 W Thread-789: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8255]" dev="sockfs" ino=8255 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-12 09:20:51.638  6843  6843 W Thread-789: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 09:20:51.638  6843  6843 W Thread-789: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6380]" dev="sockfs" ino=6380 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-12 09:20:51.638  6843  6843 W Thread-789: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-12 09:20:51.638  6843  6843 W Thread-789: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-12 09:20:51.638  6843  6843 W Thread-789: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[31809]" dev="sockfs" ino=31809 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-12 09:20:51.675  6671  6843 W jxcore-log: Starting JXcore engine
,08-12 09:20:51.842  6671  6843 W jxcore-log: Platform android
08-12 09:20:51.842  6671  6843 W jxcore-log: 
,08-12 09:20:51.842  6671  6843 W jxcore-log: Process ARCH arm
08-12 09:20:51.842  6671  6843 W jxcore-log: 
08-12 09:20:51.843  6865  6865 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(225): No need to run daily hygiene.
08-12 09:20:51.863  6865  6865 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-12 09:20:51.864  6865  6865 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-12 09:20:51.870  6865  6865 I NotificationManager: com.android.vending: cancel(-1050172287) by com.android.vending
08-12 09:20:51.900  6865  6865 I Finsky  : [1] com.google.android.finsky.utils.bp.a(177): Enabling bucket experiment: factor=2.000, zeroDelta=0ms, forceNetwork=false
,08-12 09:20:51.903  2767  3296 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is notificationclass=?; selectionArgs[0] is com.google.android.finsky.download.DownloadBroadcastReceiver; sort is null.
08-12 09:20:51.905  2767  3296 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@4e28f55 on behalf of 6865
08-12 09:20:51.942  6865  6909 D Primes  : Crash metric disabled - no startup metric sent.
,08-12 09:20:51.958  6865  6865 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1265): Installer kick - no action, not running yet
08-12 09:20:51.959  6865  6865 I Finsky  : [1] com.google.android.finsky.l.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
08-12 09:20:51.959  6865  6865 I Finsky  : [1] com.google.android.finsky.l.j.run(214): Finished loading 1 libraries.
,08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: com.google.android.gms signature not valid.  Found: 
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: MIIEQzCCAyugAwIBAgIJAMLgh0ZkSjCNMA0GCSqGSIb3DQEBBAUAMHQxCzAJBgNVBAYTAlVTMRMw
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: EQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29n
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: bGUgSW5jLjEQMA4GA1UECxMHQW5kcm9pZDEQMA4GA1UEAxMHQW5kcm9pZDAeFw0wODA4MjEyMzEz
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: MzRaFw0zNjAxMDcyMzEzMzRaMHQxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYw
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: FAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29nbGUgSW5jLjEQMA4GA1UECxMHQW5k
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: cm9pZDEQMA4GA1UEAxMHQW5kcm9pZDCCASAwDQYJKoZIhvcNAQEBBQADggENADCCAQgCggEBAKtW
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: LgDYO6IIrgqWbxJOKdoR8qtW0I9Y4sypEwPpt1TTcvZApxsdyxMJZ2JORland2qSGT2y5b+3JKke
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: dxiLDmpHpDsz2WCbdxgxRczfey5YZnTJ4VZbH0xqWVW/8lGmPav5xVwnIiJS6HXk+BVKZF+JcWjA
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: sb/GEuq/eFdpuzSqeYTcfi6idkyugwfYwXFU1+5fZKUaRKYCwkkFQVfcAs1fXA5V+++FGfvjJ/Cx
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: URaSxaBvGdGDhfXE28LWuT9ozCl5xw4Yq5OGazvV24mZVSoOO0yZ31j7kYvtwYK6NeADwbSxDdJE
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: qO4k//0zOHKrUiGYXtqw/A0LFFtqoZKFjnkCAQOjgdkwgdYwHQYDVR0OBBYEFMd9jMIhF1Ylmn/T
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: gt9r45jk14alMIGmBgNVHSMEgZ4wgZuAFMd9jMIhF1Ylmn/Tgt9r45jk14aloXikdjB0MQswCQYD
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: VQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNTW91bnRhaW4gVmlldzEUMBIG
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: A1UEChMLR29vZ2xlIEluYy4xEDAOBgNVBAsTB0FuZHJvaWQxEDAOBgNVBAMTB0FuZHJvaWSCCQDC
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: 4IdGZEowjTAMBgNVHRMEBTADAQH/MA0GCSqGSIb3DQEBBAUAA4IBAQBt0lLO74UwLDYKqs6Tm8/y
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: zKkEu116FmH4rkaymUIE0P9KaMftGlMexFlaYjzmB2OxZyl6euNXEsQH8gjwyxCUKRJNexBiGcCE
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: yj6z+a1fuHHvkiaai+KL8W1EyNmgjmyy8AW7P+LLlkR+ho5zEHatRbM/YAnqGcFh5iZBqpknHf1S
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: KMXFh4dd239FJ1jWYfbMDMy3NS5CTMQ2XFI1MvcyUTdZPErjQfTbQe3aDQsQcafEQPD+nqActifK
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: Z0Np0IS9L9kR/wbNvyz6ENwPiTrjV2KRkEjH78ZMcUQXg0L3BYHJ3lc69Vs5Ddf9uUGGMYldX3Wf
08-12 09:20:51.971  6865  6911 V GoogleSignatureVerifier: MBEmh/9iFBDAaTCK
08-12 09:20:51.999  6865  6865 I Finsky  : [1] com.google.android.finsky.c.l.a(253): result=false type=4
,08-12 09:20:52.003  1753  1753 D WearableService: callingUid 10006, callindPid: 1753
08-12 09:20:52.010  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-12 09:20:52.010  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-12 09:20:52.010  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-12 09:20:52.046  6865  6865 I Finsky  : [1] com.google.android.finsky.services.bd.a(1075): Restore complete with 0 success and 0 failed.
,08-12 09:20:52.066   843  4925 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6915 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-12 09:20:52.100  6865  6865 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
08-12 09:20:52.101  6865  6865 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
,08-12 09:20:52.133  6671  6843 I jxcore-log: JXcore Cordova bridge is ready!
08-12 09:20:52.133  6671  6843 I jxcore-log: 
08-12 09:20:52.134  6671  6843 W jxcore-log: JXcore engine is started
08-12 09:20:52.138  6671  6773 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-12 09:20:52.144  6671  6671 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 09:20:52.152  6915  6915 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 09:20:52.402   843   861 I ActivityManager: Process com.google.android.gms.unstable (pid 6552) has died
,08-12 09:20:52.438  2028  6942 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-12 09:20:52.483  2028  6942 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 44 ms] updated apps [took 44 ms] 
,08-12 09:20:52.566  1753  1753 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-12 09:20:52.566  1753  1753 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-12 09:20:52.604  3343  3700 I Icing   : Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,08-12 09:20:52.667  3343  3700 I Icing   : Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,08-12 09:20:52.690  1753  4591 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-12 09:20:52.690  1753  4591 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-12 09:20:52.691  1753  4591 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-12 09:20:52.692  1753  4591 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-12 09:20:52.692   270  1053 E BandwidthController: [LG DATA] No such appUid: 10006
08-12 09:20:52.692   270  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-12 09:20:52.692   270  6946 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-12 09:20:52.692   270  6946 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-12 09:20:52.693   270  6946 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-12 09:20:52.693   270  6946 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-12 09:20:52.693   270  6946 D libc-netbsd: res_queryN name = xxxxx succeed
08-12 09:20:52.694  1753  4591 I System.out: propertyValue:false
08-12 09:20:52.766  1753  4591 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-12 09:20:52.766  1753  4591 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-12 09:20:52.970   843  1880 I NotificationManager: android: cancelAsUser(2) by android
,08-12 09:20:52.999  1753  4591 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,08-12 09:20:53.011  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-12 09:20:53.012  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-12 09:20:53.012  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,08-12 09:20:53.093  1753  5914 D GCM     : GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,08-12 09:20:53.107  3343  3700 D NetworkUsageDbReporter: Started reporting usage
,08-12 09:20:53.175   843  1286 V AlarmManager: RTC_WAKEUP set : Alarm{1e5a2057 type 0 when 1470986453166 com.google.android.googlequicksearchbox} when 1470986453166
,08-12 09:20:53.294  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 20926
08-12 09:20:53.294  3343  3700 D NetworkUsageDbReporter: keeping row: 1541
,08-12 09:20:53.295  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1811
08-12 09:20:53.295  3343  3700 D NetworkUsageDbReporter: keeping row: 1532
,08-12 09:20:53.295  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 5926
08-12 09:20:53.295  3343  3700 D NetworkUsageDbReporter: keeping row: 1540
08-12 09:20:53.295  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 2456
08-12 09:20:53.295  3343  3700 D NetworkUsageDbReporter: keeping row: 1539
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 15911
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: keeping row: 1531
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1811
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: keeping row: 1530
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1258
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: keeping row: 1529
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 14691
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: keeping row: 1528
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 3326
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: keeping row: 1527
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 156826
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: keeping row: 1526
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 46882
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: keeping row: 1525
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 6421
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: keeping row: 1524
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 5141
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: keeping row: 1523
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 15850
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: keeping row: 1522
08-12 09:20:53.296  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1554
08-12 09:20:53.297  3343  3700 D NetworkUsageDbReporter: keeping row: 1538
08-12 09:20:53.297  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1074
08-12 09:20:53.297  3343  3700 D NetworkUsageDbReporter: keeping row: 1537
08-12 09:20:53.297  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 3252
08-12 09:20:53.297  3343  3700 D NetworkUsageDbReporter: keeping row: 1536
08-12 09:20:53.297  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1753
08-12 09:20:53.297  3343  3700 D NetworkUsageDbReporter: keeping row: 1535
08-12 09:20:53.297  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 10326
08-12 09:20:53.297  3343  3700 D NetworkUsageDbReporter: keeping row: 1534
08-12 09:20:53.297  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 15794
08-12 09:20:53.297  3343  3700 D NetworkUsageDbReporter: keeping row: 1533
08-12 09:20:53.298  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 68338
08-12 09:20:53.298  3343  3700 D NetworkUsageDbReporter: keeping row: 1520
08-12 09:20:53.298  3343  3700 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 460247
08-12 09:20:53.298  3343  3700 D NetworkUsageDbReporter: keeping row: 1519
08-12 09:20:53.320  3343  3700 D NetworkUsageDbReporter: Finished reporting usage.
,08-12 09:20:54.836  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-12 09:20:54.838  1375  1375 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-12 09:20:54.838  1375  1375 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-12 09:20:54.838  1375  1375 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-12 09:20:54.838  1375  1375 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-12 09:20:54.867  1913  1913 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,08-12 09:20:54.869  1375  1375 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
08-12 09:20:54.869  1375  1375 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-12 09:20:54.870  1375  1375 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
08-12 09:20:54.870  2082  3535 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-12 09:20:54.872   843   843 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 09:20:54.872   843  1314 D WifiController: battery changed pluggedType: 2
08-12 09:20:54.872   843   843 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 09:20:54.872  6489  6489 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-12 09:20:54.874  1913  1913 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-12 09:20:54.874  1876  2053 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-12 09:20:54.875  1876  2053 D LEDHandler: Battery Level Remaining: 100%
08-12 09:20:54.875  1876  2053 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
08-12 09:20:54.878  1375  1375 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-12 09:20:54.883   485   485 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-12 09:20:54.982  6865  6865 I Finsky  : [1] com.google.android.finsky.b.br.run(1195): Not measuring cold start metric.  No activity start found after 3000ms
,08-12 09:20:55.014  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,08-12 09:20:55.014  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-12 09:20:55.014  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-12 09:20:56.017  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-12 09:20:56.017  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-12 09:20:56.017  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-12 09:20:56.451   292   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-12 09:20:57.019  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,08-12 09:20:57.020  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-12 09:20:57.020  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-12 09:20:59.025  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-12 09:20:59.026  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-12 09:20:59.026  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-12 09:20:59.999   843  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=880175859, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=843
,08-12 09:21:00.007  2865  2865 D WeatherService: 2 : TimeTick Intent has been received, Time(hour:min:sec) 9:21:0
08-12 09:21:00.008  2865  2865 D WeatherService: 2 : TimeTick Intent And Screen On
08-12 09:21:00.008  2865  2865 D WeatherService: 2 : SDK version : 21
08-12 09:21:00.009   843  1973 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
08-12 09:21:00.010  2865  2865 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
08-12 09:21:00.010  2865  2865 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
08-12 09:21:00.010  2865  2865 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
08-12 09:21:00.010  2865  2865 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
08-12 09:21:00.012  2865  2865 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-12 09:21:00.012  2865  2865 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
08-12 09:21:00.012  2865  2865 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
08-12 09:21:00.012  2865  2865 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
08-12 09:21:00.013  2865  2865 D WeatherTheme: 2 : Fixed theme : optimus
08-12 09:21:00.017  2865  2865 D WeatherReflect: 2 : Map key string is -2
08-12 09:21:00.020  2865  2865 D lim     : 2 : time = 09:21
,08-12 09:21:00.025  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-12 09:21:00.025  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-12 09:21:00.026  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-12 09:21:00.028  2865  2865 I WeatherReflect: Model Name : LG-D722
08-12 09:21:00.028  2865  2865 D WeatherTheme: 2 : Different view - status_min_formatted : 20 != 21
08-12 09:21:00.028  2865  2865 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
08-12 09:21:00.029  2865  2865 D WeatherReflect: 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
08-12 09:21:00.031  2865  2865 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-12 09:21:00.031  2865  2865 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-12 09:21:00.031  2865  2865 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-12 09:21:00.031  2865  2865 D Weather4x2_optimus: currentPackage=com.lge.sizechangable.weather.theme.optimus
08-12 09:21:00.044  1375  1375 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 09:21:00.044  1375  1375 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 09:21:00.048  1375  1375 I [SystemUI]Clock: called onTimeUpdated()
08-12 09:21:00.050  1375  1375 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 09:21:00.050  1375  1375 I [SystemUI]DateView: called onTimeUpdated()
08-12 09:21:00.051  1375  1375 I [SystemUI]DateView: called onTimeUpdated()
08-12 09:21:00.051  1375  1375 D KeyguardUpdateMonitor: handleTimeUpdate
,08-12 09:21:00.074  2865  2865 D Weather4x2_optimus: [[[[[[Theme package!!]]]]]] RemoteViews are created 2
08-12 09:21:00.074  2865  2865 D Weather4x2_optimus: widgetType = 1, orientation = 1
08-12 09:21:00.074  2865  2865 D Weather4x2_optimus: forecast size is 0
08-12 09:21:00.075  2865  2865 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-12 09:21:00.075  2865  2865 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-12 09:21:00.075  2865  2865 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-12 09:21:00.075  2865  2865 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-12 09:21:00.075  2865  2865 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-12 09:21:00.075  2865  2865 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-12 09:21:00.075  2865  2865 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-12 09:21:00.075  2865  2865 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-12 09:21:00.075  2865  2865 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-12 09:21:00.075  2865  2865 I Theme_WeatherAncestor_optimus: WEATHER_CP_ACCU : 
08-12 09:21:00.075  2865  2865 I Theme_WeatherAncestor_optimus: weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
08-12 09:21:00.076  2865  2865 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-12 09:21:00.076  2865  2865 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-12 09:21:00.076  2865  2865 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-12 09:21:00.076  2865  2865 D Theme_WeatherAncestor_optimus: setTouchIntent, appWidgetId: 2
,08-12 09:21:00.079  2865  2865 D Theme_WeatherAncestor_optimus: url is : null
08-12 09:21:00.081  2865  2865 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-12 09:21:00.081  2865  2865 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-12 09:21:00.081  2865  2865 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-12 09:21:00.082  2865  2865 D WeatherAncestor: 2 : update view, appWidgetId: 2
08-12 09:21:00.085  2865  2865 D WeatherService: 2 : TimeTick Intent has been processed, Time(hour:min:sec) 9:21:0
08-12 09:21:00.095   843   843 D PowerManagerServiceEx: releaseWakeLockInternal: lock=880175859 [*alarm*], flags=0x0
,08-12 09:21:00.213  1950  1950 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,08-12 09:21:00.294  1950  1950 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-12 09:21:00.489   843  1001 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-12 09:21:00.489   843  1001 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-12 09:21:00.489   843  1001 D sensors_hal_Time: tsOffsetIs: Apps: 132754350682; DSPS: 4441471; Offset : -2798914084
,08-12 09:21:01.456   292   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-12 09:21:02.027  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-12 09:21:02.027  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-12 09:21:02.027  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-12 09:21:03.030  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-12 09:21:03.030  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-12 09:21:03.030  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-12 09:21:05.034  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-12 09:21:05.034  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-12 09:21:05.034  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-12 09:21:06.036  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-12 09:21:06.036  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-12 09:21:06.036  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-12 09:21:06.460   292   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-12 09:21:06.664   843  1911 I ActivityManager: Killing 6489:com.lge.bnr/1000 (adj 15): empty #11
,08-12 09:21:06.735   843  1919 W libprocessgroup: failed to open /acct/uid_1000/pid_6489/cgroup.procs: No such file or directory
,08-12 09:21:08.040  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-12 09:21:08.040  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-12 09:21:08.041  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-12 09:21:08.692  6671  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 09:21:08.692  6671  6843 I jxcore-log: 
,08-12 09:21:08.697  6671  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 09:21:08.697  6671  6843 I jxcore-log: 
08-12 09:21:08.702  2082  3571 D BluetoothAdapterService(66331239): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f66b275
08-12 09:21:08.703  6671  6843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 09:21:08.703  6671  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 09:21:08.703  6671  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 09:21:08.703  6671  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 09:21:08.703  6671  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 09:21:08.703  6671  6843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 09:21:08.703  6671  6843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 09:21:08.703  6671  6843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 09:21:08.705  2082  3571 D BluetoothAdapterService(66331239): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f66b275
08-12 09:21:08.706  6671  6843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 09:21:08.709  6671  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 09:21:08.709  6671  6843 I jxcore-log: 
08-12 09:21:08.711  6671  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 09:21:08.711  6671  6843 I jxcore-log: 
08-12 09:21:09.043  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-12 09:21:09.043  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-12 09:21:09.043  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-12 09:21:09.247  6671  6843 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-12 09:21:09.247  6671  6843 I jxcore-log: Failed to execute UT.
08-12 09:21:09.247  6671  6843 I jxcore-log: 
,08-12 09:21:09.247  6671  6843 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 09:21:09.247  6671  6843 I jxcore-log: 
08-12 09:21:09.260  6671  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 09:21:09.260  6671  6843 I jxcore-log: 
,08-12 09:21:09.263  6671  6671 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-12 09:21:09.653  7000  7000 D AndroidRuntime: 
08-12 09:21:09.653  7000  7000 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-12 09:21:09.665  7000  7000 D AndroidRuntime: CheckJNI is OFF
,08-12 09:21:09.966  7000  7000 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 09:21:10.031   843   883 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,08-12 09:21:10.033   843   883 I ActivityManager: Killing 6671:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
08-12 09:21:10.087   843  1998 I WindowState: WIN DEATH: Window{3ba356bf u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 09:21:10.111   843  1998 D InputDispatcher: Focus left window: Window{3ba356bf u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 09:21:10.111   843  1998 D InputDispatcher: Window went away: Window{3ba356bf u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 09:21:10.136   843  1059 W PackageSettings: Skipping PackageSetting{839e053 com.example.hello/10317} due to missing metadata
,08-12 09:21:10.147   843   883 W ActivityManager: Force removing ActivityRecord{3808a4a4 u0 com.test.thalitest/.MainActivity t259}: app died, no saved state
,08-12 09:21:10.188   843  2036 W ActivityManager: Spurious death for ProcessRecord{15f3c3b0 6671:com.test.thalitest/u0a30}, curProc for 6671: null
08-12 09:21:10.193   843  1059 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
,08-12 09:21:10.288  2028  2028 I art     : Explicit concurrent mark sweep GC freed 1712(100KB) AllocSpace objects, 1(24KB) LOS objects, 39% free, 12MB/21MB, paused 2.034ms total 84.378ms
,08-12 09:21:10.295  1375  1375 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-12 09:21:10.302   843  1289 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 09:21:10.333  1913  1913 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,08-12 09:21:10.335  1753  2377 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 09:21:10.377  3343  3343 I art     : Explicit concurrent mark sweep GC freed 32765(1955KB) AllocSpace objects, 13(211KB) LOS objects, 25% free, 16MB/22MB, paused 1.119ms total 165.572ms
,08-12 09:21:10.379   843   883 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7023 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-12 09:21:10.392  3681  3681 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-12 09:21:10.398  1950  1950 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
08-12 09:21:10.406  1375  1375 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-12 09:21:10.410  1375  1504 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 09:21:10.410  1375  1504 D KeyguardModel: createShortcutInfo...
,08-12 09:21:10.417  1375  1504 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 09:21:10.417  1375  1504 D KeyguardModel: createShortcutInfo...
08-12 09:21:10.417  3681  3681 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-12 09:21:10.417  3681  3681 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 09:21:10.417  3681  3681 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-12 09:21:10.417  3681  3681 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 09:21:10.420  1375  1504 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 09:21:10.421  1375  1504 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 09:21:10.422  1375  1504 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 09:21:10.423  1375  1504 D KeyguardModel: createShortcutInfo...
08-12 09:21:10.424  1375  1504 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 09:21:10.425  1375  1504 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 09:21:10.425  3681  3681 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 09:21:10.425  3681  3681 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 09:21:10.426  3681  3681 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-12 09:21:10.426  3681  3681 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 09:21:10.426  3681  3681 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 09:21:10.426  3681  3681 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-12 09:21:10.426  3681  3681 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,08-12 09:21:10.429  1375  1504 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 09:21:10.429  1375  1504 D KeyguardModel: createShortcutInfo...
08-12 09:21:10.434  1375  1504 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 09:21:10.435  1375  1504 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 09:21:10.436  1950  1950 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
08-12 09:21:10.440  1375  1504 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 09:21:10.440  1375  1504 D KeyguardModel: createShortcutInfo...
,08-12 09:21:10.480  1950  1950 I [LGHome]EVENT: [LauncherModel.java:1358:startLoader()]startLoader isLaunching=true
08-12 09:21:10.491   843   843 W art     : Suspending all threads took: 7.421ms
,08-12 09:21:10.494  1950  2060 I [LGHome]Launcher.Model: [LauncherModel.java:1475:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-12 09:21:10.506  1950  1950 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-12 09:21:10.509  1950  1950 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-12 09:21:10.509  1950  1950 I Activity: Activity.onPostResume() called 
,08-12 09:21:10.521   843   843 I art     : Explicit concurrent mark sweep GC freed 36750(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/35MB, paused 14.945ms total 261.994ms
08-12 09:21:10.523   843  1059 I art     : WaitForGcToComplete blocked for 229.459ms for cause Explicit
08-12 09:21:10.548  1375  1375 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 09:21:10.548  1375  1375 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-12 09:21:10.550  1375  1375 D KeyguardModel: handleShortcutListChanged...
,08-12 09:21:10.557  7023  7023 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 09:21:10.557  7023  7023 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 09:21:10.558  7023  7023 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-12 09:21:10.559  1950  7046 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
08-12 09:21:10.568  1375  1504 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 09:21:10.568  1375  1504 D KeyguardModel: createShortcutInfo...
,08-12 09:21:10.572  1375  1504 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 09:21:10.572  1375  1504 D KeyguardModel: createShortcutInfo...
08-12 09:21:10.574  1375  1504 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 09:21:10.574  1375  1504 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 09:21:10.578  1375  1504 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 09:21:10.578  1375  1504 D KeyguardModel: createShortcutInfo...
08-12 09:21:10.580  1375  1504 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 09:21:10.580  1375  1504 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 09:21:10.582  1375  1504 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 09:21:10.582  1375  1504 D KeyguardModel: createShortcutInfo...
,08-12 09:21:10.584  1375  1504 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 09:21:10.584  1375  1504 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 09:21:10.586  1375  1504 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 09:21:10.586  1375  1504 D KeyguardModel: createShortcutInfo...
08-12 09:21:10.586   843  1019 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-12 09:21:10.588   843  1019 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-12 09:21:10.588  1375  1375 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-12 09:21:10.589   843  1019 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-12 09:21:10.589   843  1019 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-12 09:21:10.589   843  1019 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-12 09:21:10.589   843  1019 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@13b35926,  pkg=WindowManager.LayoutParams
08-12 09:21:10.589   843  1019 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-12 09:21:10.590  1375  1375 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-12 09:21:10.590  1375  1375 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-12 09:21:10.590  1375  1375 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-12 09:21:10.590   843  1919 D InputDispatcher: Focus entered window: Window{26892138 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-12 09:21:10.597  1375  1375 D KeyguardModel: handleShortcutListChanged...
,08-12 09:21:10.607  1950  1950 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 09:21:10.607  1950  1950 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 09:21:10.608  1950  1950 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-12 09:21:10.624  1950  1950 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,08-12 09:21:10.625  1950  1950 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-12 09:21:10.657   843  1911 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-12 09:21:10.658   843  1911 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6671 uid 10030
,08-12 09:21:10.672   843   843 D administrator: Handling package changes for user 0
,08-12 09:21:10.724  1950  1950 I [LGHome]Launcher.Model: [LauncherModel.java:2270:run()] LauncherModel bind current page shortcut
,08-12 09:21:10.733  2028  2028 I HotwordDetector: Closing mic
08-12 09:21:10.748  1950  1950 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-12 09:21:10.750  1950  1950 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-12 09:21:10.752  1950  1950 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
,08-12 09:21:10.755  1950  1950 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-12 09:21:10.766  2028  2593 I HotwordRecognitionRnr: Stopping hotword detection.
,08-12 09:21:10.867  1950  1950 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-12 09:21:10.867  1950  1950 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
,08-12 09:21:10.887   843   843 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,08-12 09:21:10.888  7023  7023 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-12 09:21:10.895   843   843 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 09:21:10.916  1950  1950 W Resources: Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,08-12 09:21:10.919  1950  1950 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
08-12 09:21:10.920  1950  1950 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
08-12 09:21:10.921  1950  1950 W Resources: Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
08-12 09:21:10.927  7023  7023 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
08-12 09:21:10.928  1950  1950 W Resources: Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
08-12 09:21:10.929   843   843 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-12 09:21:10.935   843  1351 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
08-12 09:21:10.945  1950  1950 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,08-12 09:21:10.946  1950  1950 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
08-12 09:21:10.948  1950  1950 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
08-12 09:21:10.950  1950  1950 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
08-12 09:21:10.950  1950  1950 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
08-12 09:21:10.957   843  1059 I art     : Explicit concurrent mark sweep GC freed 12815(1169KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 26.929ms total 428.756ms
08-12 09:21:10.962  1950  1950 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
08-12 09:21:10.973  1950  1950 W Resources: Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,08-12 09:21:10.989   843  1021 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3f143363 u0 com.lge.launcher2/.Launcher t258} time:143254
,08-12 09:21:11.046  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-12 09:21:11.046  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-12 09:21:11.046  1375  1375 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-12 09:21:11.099  7000  7000 D AndroidRuntime: Shutting down VM
,08-12 09:21:11.105  1852  1852 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-12 09:21:11.105  1852  1852 D LCardEmulationManager: getDefaultRoute
08-12 09:21:11.111   843   882 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-12 09:21:11.148  1950  1950 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,08-12 09:21:11.162   843  1059 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7055 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-12 09:21:11.218  7023  7023 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-12 09:21:11.239  1950  1950 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-12 09:21:11.239  1950  1950 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
08-12 09:21:11.240  1950  1950 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
08-12 09:21:11.250  6779  6779 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-12 09:21:11.256  1950  1950 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,08-12 09:21:11.260   843   882 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-12 09:21:11.262  1950  1950 I Choreographer: Skipped 31 frames!  The application may be doing too much work on its main thread.
08-12 09:21:11.283  1950  1950 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-12 09:21:11.283  1950  2214 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,08-12 09:21:11.284  1950  2214 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-12 09:21:11.285  1950  1950 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
08-12 09:21:11.287  1950  1950 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-12 09:21:11.288  1950  1950 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
08-12 09:21:11.290  1950  1950 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
08-12 09:21:11.301   843  2561 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7073 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
08-12 09:21:11.302   843  2561 I ActivityManager: Killing 6623:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,08-12 09:21:11.389   843  1641 W libprocessgroup: failed to open /acct/uid_10038/pid_6623/cgroup.procs: No such file or directory
,08-12 09:21:11.397   843  2561 I ActivityManager: Killing 6714:com.google.android.talk/u0a61 (adj 15): empty #11
08-12 09:21:11.426  2028  7093 I HotwordRecognitionRnr: Starting hotword detection.
,08-12 09:21:11.433  2028  7094 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@10791bd4
08-12 09:21:11.437  2028  7094 V AudioRecord: set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
08-12 09:21:11.437  2028  7094 V AudioRecord: set(): mSessionId 23
08-12 09:21:11.451   276   276 V AudioPolicyManager: getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 23, flags 0
08-12 09:21:11.452   276   276 V AudioPolicyManager: getDeviceForInputSource()input source 1999, device 80000004
08-12 09:21:11.452   276   276 V AudioPolicyManager: isPlaybackThread 0,isRecordThread 1
,08-12 09:21:11.453   276   276 D audio_hw_primary: adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546dd40)
08-12 09:21:11.453   276   276 V audio_hw_primary: adev_open_input_stream: exit
08-12 09:21:11.453   276   276 V AudioFlinger: openInput_l() openInputStream returned input 0xb546dd40, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
08-12 09:21:11.456  1950  1950 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
08-12 09:21:11.457   276   276 V AudioFlinger: openInput_l() created record thread: ID 24 thread 0xb3e5a000
08-12 09:21:11.457   276   276 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
08-12 09:21:11.457   843  2036 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
08-12 09:21:11.457   276  7096 I AudioFlinger: AudioFlinger's thread 0xb3e5a000 ready to run
08-12 09:21:11.457   276  7096 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
08-12 09:21:11.457   276  7096 V audio_hw_primary: in_standby: exit:  status(0)
08-12 09:21:11.458   276  7096 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
08-12 09:21:11.458   276  7096 V audio_hw_primary: in_standby: exit:  status(0)
08-12 09:21:11.458   276  7096 V AudioFlinger: RecordThread: loop stopping
08-12 09:21:11.458  1375  1403 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
08-12 09:21:11.458  1781  1801 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
08-12 09:21:11.459  2082  2098 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
08-12 09:21:11.459  2028  2052 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
08-12 09:21:11.459  3166  3181 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
08-12 09:21:11.459   276   276 V AudioPolicyService: AudioCommandThread() adding update audio port list
08-12 09:21:11.459   276   276 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
08-12 09:21:11.459   276  1064 V AudioPolicyService: AudioCommandThread() waking up
08-12 09:21:11.459   276  1064 V AudioPolicyService: AudioCommandThread() processing update audio port list
08-12 09:21:11.459   276  1064 V AudioPolicyService: AudioCommandThread() going to sleep
08-12 09:21:11.460   276  1594 V AudioFlinger: openRecord() lSessionId: 23 input 24
,08-12 09:21:11.461   276  1594 V AudioFlinger: getOrphanEffectChain_l session 23 index -2
08-12 09:21:11.462   276   276 V AudioFlinger: acquiring 23 from 2028, for -1
08-12 09:21:11.462   276   276 V AudioFlinger:  added new entry for 23
08-12 09:21:11.465   292   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
08-12 09:21:11.467  2028  7094 V AudioRecord: start, sync event 0 trigger session 0
08-12 09:21:11.467  2028  7094 V AudioRecord: mAudioRecord->start()
08-12 09:21:11.467   276  1594 V AudioFlinger: RecordHandle::start()
08-12 09:21:11.467   276  1594 V AudioFlinger: RecordThread::start event 0, triggerSession 0
08-12 09:21:11.467   276  1594 V AudioPolicyManager: startInput() module primary->input primary(24)
08-12 09:21:11.467   276  1594 V AudioPolicyManager: getDeviceForInputSource()input source 1999, device 80000004
08-12 09:21:11.468   276  1594 V AudioPolicyManager: getNewInputDevice() selected device 80000004
08-12 09:21:11.468   276  1594 V AudioPolicyManager: DeviceVector::refreshTypes() mDeviceTypes 80000004
08-12 09:21:11.468   276  1594 V AudioPolicyManager: DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
08-12 09:21:11.468   276  1594 V AudioPolicyService: AudioCommandThread() adding create patch delay 0
08-12 09:21:11.468   276  1594 V AudioPolicyService: inserting command: 7 at index 0, num commands 0
08-12 09:21:11.468   276  1063 V AudioPolicyService: AudioCommandThread() waking up
08-12 09:21:11.468   276  1063 V AudioPolicyService: AudioCommandThread() processing create audio patch
08-12 09:21:11.468   276  1063 V AudioFlinger::PatchPanel: createAudioPatch() num_sources 1 num_sinks 1 handle 0
08-12 09:21:11.468   276  1063 V AudioFlinger::PatchPanel: createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
08-12 09:21:11.468   276  1063 V AudioFlinger: ThreadBase::setParameters() input_source=6;routing=-2147483644
08-12 09:21:11.468   276  1063 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-12 09:21:11.468   276  7096 V AudioFlinger: RecordThread: loop starting
08-12 09:21:11.468   276  7096 V AudioFlinger: processConfigEvents_l() remaining events 1
08-12 09:21:11.468   276  7096 D audio_hw_primary: in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
08-12 09:21:11.468   276  7096 V audio_hw_primary: in_set_parameters: exit: status(0)
08-12 09:21:11.468   276  7096 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3e5a000
08-12 09:21:11.468   276  1063 V AudioFlinger::PatchPanel: createAudioPatch() status 0
08-12 09:21:11.469   276  1063 V AudioFlinger::PatchPanel: createAudioPatch() added new patch handle 25 halHandle 0
08-12 09:21:11.469   276  1063 V AudioPolicyService: AudioCommandThread() going to sleep
08-12 09:21:11.469   276  1594 V AudioPolicyManager: setInputDevice() createAudioPatch returned 0 patchHandle 25
08-12 09:21:11.469   276  1594 V AudioPolicyManager: addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
08-12 09:21:11.469   276  1594 V AudioPolicyService: AudioCommandThread() adding update audio patch list
08-12 09:21:11.469   276  1594 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
08-12 09:21:11.469   276  1064 V AudioPolicyService: AudioCommandThread() waking up
08-12 09:21:11.469   276  1064 V AudioPolicyService: AudioCommandThread() processing update audio patch list
08-12 09:21:11.469   276  1064 V AudioPolicyService: AudioCommandThread() going to sleep
08-12 09:21:11.469   276  1594 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=1, io 24 ,delay 0
08-12 09:21:11.470   276  1594 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
08-12 09:21:11.470   276  1063 V AudioPolicyService: AudioCommandThread() waking up
08-12 09:21:11.470   276  1063 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=1, io 24
08-12 09:21:11.470   276  1063 V AudioFlinger: setParameters(): io 24, keyvalue h,otword_active=1, calling pid 276
08-12 09:21:11.470   276  1063 V AudioFlinger: ThreadBase::setParameters() hotword_active=1
08-12 09:21:11.470   276  1063 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-12 09:21:11.479   276  7096 V AudioFlinger: processConfigEvents_l() remaining events 1
08-12 09:21:11.479   276  7096 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=1
08-12 09:21:11.479   276  7096 V audio_hw_primary: in_set_parameters: exit: status(0)
08-12 09:21:11.479   276  7096 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3e5a000
08-12 09:21:11.479   276  1063 V AudioPolicyService: AudioCommandThread() going to sleep
08-12 09:21:11.479   276  1594 V AudioPolicyManager: AudioPolicyManager::startInput() input source = 1999
08-12 09:21:11.485  1950  1950 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-12 09:21:11.486  1950  1950 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-12 09:21:11.486   843  1911 W libprocessgroup: failed to open /acct/uid_10061/pid_6714/cgroup.procs: No such file or directory
08-12 09:21:11.490  2028  7094 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@10791bd4
08-12 09:21:11.491  1950  1950 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-12 09:21:11.493   276  7096 V msm8974_platform: platform_update_usecase_from_source: input source :6
08-12 09:21:11.493   276  7096 D audio_hw_primary: start_input_stream: enter: stream(0xb546dd40)usecase(7: audio-record)
08-12 09:21:11.493   276  7096 V voice   : voice_check_and_set_incall_rec_usecase: voice call not active
08-12 09:21:11.493   276  7096 V audio_hw_primary: start_input_stream: usecase(7)
08-12 09:21:11.493   276  7096 E audio_hw_primary: select_devices: enter and usecase(7)
08-12 09:21:11.494   276  7096 V msm8974_platform: platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
08-12 09:21:11.494   276  7096 V msm8974_platform: platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
08-12 09:21:11.494   276  7096 V msm8974_platform_lge: LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
08-12 09:21:11.494   276  7096 V audio_hw_lge_primary: LGE_exeption_scenario: enter and out: 0, in: 144
08-12 09:21:11.494   276  7096 D audio_hw_primary: select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
08-12 09:21:11.494   276  7096 E audio_hw_primary: enable_snd_device: enter  144
08-12 09:21:11.494   276  7096 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
08-12 09:21:11.494   276  7096 V audio_hw_primary: enable_snd_device: snd_device(144: lg-vr-handset-mic)
08-12 09:21:11.494   276  7096 V msm8974_platform_lge: LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
08-12 09:21:11.495   276  7096 D ACDB-LOADER: ACDB -> send_audio_cal, acdb_id = 65, path =  1
08-12 09:21:11.495   276  7096 D ACDB-LOADER: ACDB -> send_adm_topology
08-12 09:21:11.495   276  7096 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
08-12 09:21:11.497   276  7096 D ACDB-LOADER: ACDB -> send_asm_topology
08-12 09:21:11.497   276  7096 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
08-12 09:21:11.497   276  7096 D ACDB-LOADER: ACDB -> send_audtable
08-12 09:21:11.497   276  7096 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
08-12 09:21:11.497   276  7096 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_CAL
08-12 09:21:11.497   276  7096 D ACDB-LOADER: ACDB -> send_audvoltable
08-12 09:21:11.497   276  7096 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
08-12 09:21:11.497   276  7096 D         : Failed to fetch the lookup information of the device 00000041 
08-12 09:21:11.497   276  7096 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
08-12 09:21:11.497   276  7096 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
08-12 09:21:11.497   276  7096 D ACDB-LOADER: ACDB -> AUDIO_SET_AFE_CAL
08-12 09:21:11.503   276  7096 V audio_hw_primary: enable_audio_route: enter: usecase(7)
08-12 09:21:11.504   276  7096 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
08-12 09:21:11.504   276  7096 V audio_hw_primary: enable_audio_route: apply mixer and update path: audio-record
08-12 09:21:11.505   276  7096 V audio_hw_primary: enable_audio_route: exit
08-12 09:21:11.505   276  7096 D audio_hw_primary: select_devices: done
08-12 09:21:11.505   276  7096 V audio_hw_primary: start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
08-12 09:21:11.509   276  7096 V audio_hw_primary: start_input_stream: exit
,08-12 09:21:11.580  1950  2297 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
08-12 09:21:11.580  1950  2297 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,08-12 09:21:11.586  1950  1950 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@25b8cf17 time:143851
08-12 09:21:11.589  1950  2169 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
08-12 09:21:11.626  2028  2028 I HotwordWorker: onReady

```
