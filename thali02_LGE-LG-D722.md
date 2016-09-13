#### Test 836273379690449_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
09-13 14:17:56.142  1736  4338 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-13 14:17:57.101  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-13 14:17:57.101  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 14:17:57.101  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-13 14:17:57.517  6422  6422 D AndroidRuntime: 
09-13 14:17:57.517  6422  6422 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 14:17:57.521  6422  6422 D AndroidRuntime: CheckJNI is OFF
09-13 14:17:57.761  6422  6422 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-13 14:17:57.780   861  2355 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 14:17:57.845   861  2355 D ActivityManager: setTaskToReturnTo : TaskRecord{19e5042 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 14:17:57.847   861  2355 D ActivityManager: setTaskToReturnTo : TaskRecord{19e5042 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 14:17:57.871   861  2355 D WindowStateEx: AppWindowTokenEx init.. 
09-13 14:17:57.890   861  1058 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-13 14:17:57.899  1881  1881 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
09-13 14:17:57.908   861  1058 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-13 14:17:57.916   861  2355 D InputDispatcher: Focus left window: Window{2476a87c u0 com.lge.launcher2/com.lge.launcher2.Launcher}
09-13 14:17:57.920  6422  6422 D AndroidRuntime: Shutting down VM
09-13 14:17:57.927   861  1058 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-13 14:17:57.927   861  1058 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-13 14:17:57.963   861  1058 D SplitWindow: check instance of lgWin Window{1169a59a u0 Starting com.test.thalitest}
09-13 14:17:58.008   861  1298 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6442 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-13 14:17:58.059  1881  1881 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
09-13 14:17:58.082  1881  1881 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
09-13 14:17:58.097   861  1819 I WindowStateAnimator: Starting window displayed
09-13 14:17:58.102   861  1056 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
09-13 14:17:58.106   861  1056 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
09-13 14:17:58.108   861  1056 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
09-13 14:17:58.108   861  1056 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
09-13 14:17:58.109   861  1056 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-13 14:17:58.109   861  1056 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@5f53ae,  pkg=WindowManager.LayoutParams
09-13 14:17:58.109   861  1056 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,09-13 14:17:58.113   295   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
09-13 14:17:58.115  1377  1377 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
09-13 14:17:58.117  1377  1377 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
09-13 14:17:58.117  1377  1377 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
09-13 14:17:58.117  1377  1377 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
09-13 14:17:58.150  1959  1959 I HotwordDetector: Closing mic
09-13 14:17:58.166  1959  2558 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@2c2e1d06
09-13 14:17:58.166  1959  2558 V AudioRecord: stop()
09-13 14:17:58.166  1959  2558 D AudioRecord: AudioRecord->stop()
09-13 14:17:58.170   281  1598 V AudioFlinger: RecordHandle::stop()
09-13 14:17:58.170   281  1598 V AudioFlinger: RecordThread::stop
09-13 14:17:58.190   281  1598 V AudioFlinger: Record stopped OK
09-13 14:17:58.191   281  1598 V AudioPolicyManager: stopInput() input 17
09-13 14:17:58.192   281  1598 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
09-13 14:17:58.193   281  1598 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
09-13 14:17:58.193   281  1065 V AudioPolicyService: AudioCommandThread() waking up
09-13 14:17:58.193   281  1065 V AudioPolicyService: AudioCommandThread() processing release audio patch
09-13 14:17:58.193   281  1065 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
09-13 14:17:58.193   281  1065 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
09-13 14:17:58.193   281  1065 V AudioFlinger: ThreadBase::setParameters() routing=0
09-13 14:17:58.193   281  1065 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
09-13 14:17:58.195   281  2582 V AudioFlinger: processConfigEvents_l() remaining events 1
09-13 14:17:58.196   281  2582 V AudioFlinger: processConfigEvents_l() DONE thread 0xb415b000
09-13 14:17:58.200   281  2582 D audio_hw_primary: in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
09-13 14:17:58.245   281  2582 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
09-13 14:17:58.245   281  2582 V audio_hw_primary: disable_audio_route: enter: usecase(7)
09-13 14:17:58.245   281  2582 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
09-13 14:17:58.245   281  2582 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-13 14:17:58.248   281  2582 V audio_hw_primary: disable_audio_route: exit
09-13 14:17:58.248   281  2582 E audio_hw_primary: disable_snd_device: enter 144
09-13 14:17:58.248   281  2582 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
09-13 14:17:58.248   281  2582 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
09-13 14:17:58.251   281  2582 V audio_hw_primary: stop_input_stream: exit: status(0)
09-13 14:17:58.251   281  2582 V audio_hw_primary: in_standby: exit:  status(0)
09-13 14:17:58.251   281  2582 V AudioFlinger: RecordThread: loop stopping
09-13 14:17:58.251   281  1598 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
09-13 14:17:58.251   281  1065 V AudioPolicyService: AudioCommandThread() going to sleep
09-13 14:17:58.251   281  1598 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
09-13 14:17:58.251   281  1598 V AudioPolicyService: AudioCommandThread() adding update audio patch list
09-13 14:17:58.251   281  1598 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
09-13 14:17:58.251   281  1066 V AudioPolicyService: AudioCommandThread() waking up
09-13 14:17:58.252   281  1066 V AudioPolicyService: AudioCommandThread() processing update audio patch list
09-13 14:17:58.252   281  1066 V AudioPolicyService: AudioCommandThread() going to sleep
09-13 14:17:58.252   281  1598 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
09-13 14:17:58.252   281  1598 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
09-13 14:17:58.253   281  1065 V AudioPolicyService: AudioCommandThread() waking up
09-13 14:17:58.253   281  1065 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
09-13 14:17:58.253   281  1065 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 281
09-13 14:17:58.253   281  1065 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
09-13 14:17:58.253   281  1065 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
09-13 14:17:58.253   281  2582 V AudioFlinger: RecordThread: loop starting
09-13 14:17:58.253   281  2582 V AudioFlinger: processConfigEvents_l() remaining events 1
09-13 14:17:58.253   281  2582 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
09-13 14:17:58.253   281  2582 V audio_hw_primary: in_set_parameters: exit: status(0)
09-13 14:17:58.254   281  2582 V AudioFlinger: processConfigEvents_l() DONE thread 0xb415b000
09-13 14:17:58.254   281  2582 V AudioFlinger: RecordThread: loop stopping
09-13 14:17:58.254   281  1065 V AudioPolicyService: AudioCommandThread() going to sleep
09-13 14:17:58.257  1959  2558 V AudioRecord: stop()
09-13 14:17:58.258  1959  2558 V AudioRecord: stop()
09-13 14:17:58.258  1959  2558 V AudioRecord: stop()
09-13 14:17:58.261   281   281 V AudioFlinger: RecordHandle::stop()
09-13 14:17:58.261   281   281 V AudioFlinger: RecordThread::stop
09-13 14:17:58.261   281   281 V AudioPolicyManager: releaseInput() 17
09-13 14:17:58.261   281   281 V AudioPolicyManager: closeInput(17)
09-13 14:17:58.261   281   281 V AudioFlinger: closeInput() 17
09-13 14:17:58.261   281   281 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-13 14:17:58.261   861  1781 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-13 14:17:58.261   281   281 V AudioFlinger: ThreadBase::exit
09-13 14:17:58.261  2879  2895 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-13 14:17:58.261   281  2582 V AudioFlinger: RecordThread: loop starting
09-13 14:17:58.261  2041  3547 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-13 14:17:58.262   281  2582 V AudioFlinger: RecordThread 0xb415b000 exiting
09-13 14:17:58.262  1377  2652 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-13 14:17:58.262  1755  1771 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-13 14:17:58.262  1959  1993 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-13 14:17:58.262  3177  3196 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-13 14:17:58.262   281   281 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb4036520)
09-13 14:17:58.262   281   281 D audio_hw_primary: in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
09-13 14:17:58.262   281   281 V audio_hw_primary: in_standby: exit:  status(0)
09-13 14:17:58.262   281   281 V AudioPolicyService: AudioCommandThread() adding update audio port list
09-13 14:17:58.263   281   281 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
09-13 14:17:58.263   281   281 V AudioPolicyManager: releaseInput() exit
09-13 14:17:58.263   281  1066 V AudioPolicyService: AudioCommandThread() waking up
09-13 14:17:58.263   281   281 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
09-13 14:17:58.263   281  1066 V AudioPolicyService: AudioCommandThread() processing update audio port list
09-13 14:17:58.263   281   281 V AudioFlinger: removeClient_l() pid 1959, calling pid 281
09-13 14:17:58.263   281  1066 V AudioPolicyService: AudioCommandThread() going to sleep
09-13 14:17:58.264   281  1598 V AudioFlinger: releasing 16 from 1959 for -1
09-13 14:17:58.264   281  1598 V AudioFlinger:  decremented refcount to 0
09-13 14:17:58.264   281  1598 V AudioFlinger: purging stale effects
09-13 14:17:58.264  1959  2568 I HotwordRecognitionRnr: Stopping hotword detection.
09-13 14:17:58.270  6442  6442 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-13 14:17:58.275  1959  2571 I HotwordRecognitionRnr: Hotword detection finished
09-13 14:17:58.375  6442  6442 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
09-13 14:17:58.434  6442  6442 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8696-8699)
09-13 14:17:58.435  6442  6442 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 14:17:58.478  6442  6442 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1522c529}
09-13 14:17:58.479  6442  6442 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 14:17:58.479  6442  6442 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 14:17:58.496  6442  6442 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-13 14:17:58.497  6442  6442 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 14:17:58.498  6442  6442 E SysUtils: ApplicationContext is null in ApplicationStatus
09-13 14:17:58.525  6442  6442 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-13 14:17:58.533  6442  6442 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 14:17:58.533  6442  6442 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 14:17:58.534  6442  6442 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 14:17:58.534  6442  6442 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 14:17:58.534  6442  6442 I Adreno-EGL: Build Date: 03/02/15 Mon
09-13 14:17:58.534  6442  6442 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-13 14:17:58.534  6442  6442 I Adreno-EGL: Remote Branch: 
09-13 14:17:58.534  6442  6442 I Adreno-EGL: Local Patches: 
09-13 14:17:58.534  6442  6442 I Adreno-EGL: Reconstruct Branch: 
09-13 14:17:58.612   281  1302 V AudioPolicyService: registerClient() client 0xb4027380, uid 10030
09-13 14:17:58.635   861  1057 D BluetoothManagerService: Message: 20
09-13 14:17:58.640   861  1057 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8b95eb5:true
09-13 14:17:58.645  2041  2059 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:17:58.811  1377  1377 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
09-13 14:17:58.815  1881  1881 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-13 14:17:58.822  1881  1881 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-13 14:17:58.823  1881  1881 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,09-13 14:17:58.830  1844  1844 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
09-13 14:17:58.832   861  1291 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-13 14:17:58.854   861   861 D administrator: Handling package changes for user 0
,09-13 14:17:58.857  6442  6442 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 14:17:58.866   861   992 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6509 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-13 14:17:58.878  1881  1881 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,09-13 14:17:58.881  1377  1377 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-13 14:17:58.889  6442  6442 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-13 14:17:58.890  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
09-13 14:17:58.890  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
09-13 14:17:58.890  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
09-13 14:17:58.890  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
09-13 14:17:58.891  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
09-13 14:17:58.891  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
09-13 14:17:58.891  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
09-13 14:17:58.891  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
09-13 14:17:58.891  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
09-13 14:17:58.891  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
09-13 14:17:58.891  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
,09-13 14:17:58.891  1377  1377 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
09-13 14:17:58.891  1377  1377 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-13 14:17:58.897  6442  6442 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-13 14:17:58.902  6442  6442 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-13 14:17:58.902  6442  6442 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-13 14:17:58.920  6442  6442 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-13 14:17:58.942  6442  6442 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 14:17:58.942  6442  6442 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 14:17:58.992  6509  6509 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-13 14:17:59.006   861   861 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-13 14:17:59.006   861   861 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-13 14:17:59.006   861   861 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,09-13 14:17:59.009   861   861 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
09-13 14:17:59.018   861   861 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
09-13 14:17:59.018   861   861 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3e314fdc
,09-13 14:17:59.046  6442  6442 I Activity: Activity.onPostResume() called 
,09-13 14:17:59.049   861   991 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 14:17:59.086  6442  6531 D OpenGLRenderer: Render dirty regions requested: true
09-13 14:17:59.087  6442  6531 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 14:17:59.099  6442  6531 D OpenGLRenderer: Enabling debug mode 0
,09-13 14:17:59.099  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-13 14:17:59.100  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 14:17:59.100  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-13 14:17:59.116  6442  6442 D Atlas   : Validating map...
,09-13 14:17:59.121   861  1978 D SplitWindow: check instance of lgWin Window{18ea4de0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 14:17:59.138  6442  6489 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-13 14:17:59.171   861  1854 D InputDispatcher: Focus entered window: Window{18ea4de0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 14:17:59.254   861   991 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-13 14:17:59.262   861  1058 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s303ms
09-13 14:17:59.262   861  2355 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
09-13 14:17:59.262   861  1058 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1e87853 u0 com.test.thalitest/.MainActivity t259} time:119527
09-13 14:17:59.292  6442  6442 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3607aa5b time:119556
,09-13 14:17:59.331  1881  1881 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-13 14:17:59.346  1736  1736 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,09-13 14:17:59.426  1790  1790 D LCardEmulationManager: getHceAppCount hostAppNum : 0
09-13 14:17:59.426  1790  1790 D LCardEmulationManager: getDefaultRoute
,09-13 14:17:59.435   861   991 D LocationProviderProxy: applying state to connected service
09-13 14:17:59.478  6442  6442 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6442
,09-13 14:17:59.562  6509  6544 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-13 14:17:59.562  6509  6544 I Babel_SMS: MmsConfig.loadMmsSettings
,09-13 14:17:59.568  6509  6544 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-13 14:17:59.568  6509  6544 I Babel_SMS: MmsConfig.loadFromDatabase
09-13 14:17:59.571  2879  2879 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19955
,09-13 14:17:59.598  6509  6544 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-13 14:17:59.598  6509  6544 I Babel_SMS: MmsConfig.loadFromResources
09-13 14:17:59.600  6509  6544 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-13 14:17:59.600  6509  6544 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-13 14:17:59.639  6509  6509 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
09-13 14:17:59.639  6509  6509 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
09-13 14:17:59.639  6509  6509 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
09-13 14:17:59.639  6509  6509 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
09-13 14:17:59.639  6509  6509 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
09-13 14:17:59.639  6509  6509 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
09-13 14:17:59.640  6509  6509 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
09-13 14:17:59.640  6509  6509 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
09-13 14:17:59.640  6509  6509 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
09-13 14:17:59.640  6509  6509 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
09-13 14:17:59.640  6509  6509 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
09-13 14:17:59.640  6509  6509 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
09-13 14:17:59.640  6509  6509 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
09-13 14:17:59.640  6509  6509 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
09-13 14:17:59.640  6509  6509 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
09-13 14:17:59.640  6509  6509 D SensorManager: found sensor: Motion Accel, handle=46
,09-13 14:17:59.676  6442  6442 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 14:17:59.704  6509  6509 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 14:17:59.708  6509  6509 I Babel_Crash: startup - clean
,09-13 14:17:59.726  6509  6523 I art     : CheckpointMarkThreadRoots callback created = 0xb042d810
,09-13 14:17:59.760   861  1289 V AlarmManager: ELAPSED_WAKEUP set : Alarm{137edc6c type 2 when 120000 com.google.android.gms} when 120000
,09-13 14:17:59.780  6509  6547 I Babel   : deleted: false for 0
,09-13 14:17:59.789  6509  6523 I art     : CheckpointMarkThreadRoots callback created = 0xb042d800
09-13 14:17:59.946  6509  6509 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,09-13 14:17:59.950  6509  6509 W AudioCapabilities: Unsupported mime audio/adpcm
09-13 14:17:59.951  6509  6509 W AudioCapabilities: Unsupported mime audio/g726
09-13 14:17:59.967  6509  6509 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-13 14:17:59.973  6509  6509 W AudioCapabilities: Unsupported mime audio/wma-voice
09-13 14:17:59.982  6509  6509 W VideoCapabilities: Unsupported mime video/mjpg
09-13 14:17:59.983   861  1978 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6550 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-13 14:18:00.000   861  1289 D PowerManagerServiceEx: acquireWakeLockInternal: lock=617577649, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=861
,09-13 14:18:00.012  6509  6509 W VideoCapabilities: Unsupported mime video/theora
,09-13 14:18:00.015  2860  2860 D WeatherService: 2 : TimeTick Intent has been received, Time(hour:min:sec) 14:18:0
09-13 14:18:00.017  2860  2860 D WeatherService: 2 : TimeTick Intent And Screen On
09-13 14:18:00.017  2860  2860 D WeatherService: 2 : SDK version : 21
09-13 14:18:00.020   861  1791 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
09-13 14:18:00.021  2860  2860 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
09-13 14:18:00.024  2860  2860 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
09-13 14:18:00.024  2860  2860 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
09-13 14:18:00.024  2860  2860 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
09-13 14:18:00.027  2860  2860 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 14:18:00.027  2860  2860 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
09-13 14:18:00.027  2860  2860 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
09-13 14:18:00.028  2860  2860 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
09-13 14:18:00.029  2860  2860 D WeatherTheme: 2 : Fixed theme : optimus
,09-13 14:18:00.050  1377  1377 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-13 14:18:00.050  1377  1377 I KeyguardUpdateMonitor: called onTimeUpdated()
09-13 14:18:00.050  2860  2860 D WeatherReflect: 2 : Map key string is -2
,09-13 14:18:00.058  1377  1377 I [SystemUI]Clock: called onTimeUpdated()
09-13 14:18:00.062  1377  1377 I LgeClockWidgetControlView: called onTimeUpdated()
,09-13 14:18:00.062  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-13 14:18:00.064  1377  1377 I [SystemUI]DateView: called onTimeUpdated()
09-13 14:18:00.066  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-13 14:18:00.067  2860  2860 D lim     : 2 : time = 14:18
09-13 14:18:00.071  2860  2860 I WeatherReflect: Model Name : LG-D722
09-13 14:18:00.071  2860  2860 D WeatherTheme: 2 : Different view - status_min_formatted : 17 != 18
09-13 14:18:00.071  2860  2860 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
09-13 14:18:00.073  2860  2860 D WeatherReflect: 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
09-13 14:18:00.089  2860  2860 D Theme   : strTheme: com.lge.launcher2.theme.optimus
09-13 14:18:00.089  2860  2860 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
09-13 14:18:00.090  2860  2860 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
09-13 14:18:00.090  2860  2860 D Weather4x2_optimus: currentPackage=com.lge.sizechangable.weather.theme.optimus
,09-13 14:18:00.106  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-13 14:18:00.106  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 14:18:00.106  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-13 14:18:00.136  2860  2860 D Weather4x2_optimus: [[[[[[Theme package!!]]]]]] RemoteViews are created 2
09-13 14:18:00.137  2860  2860 D Weather4x2_optimus: widgetType = 1, orientation = 1
,09-13 14:18:00.137  2860  2860 D Weather4x2_optimus: forecast size is 0
,09-13 14:18:00.137  2860  2860 D Theme   : strTheme: com.lge.launcher2.theme.optimus
09-13 14:18:00.137  2860  2860 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
09-13 14:18:00.137  2860  2860 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
09-13 14:18:00.138  2860  2860 D Theme   : strTheme: com.lge.launcher2.theme.optimus
09-13 14:18:00.138  2860  2860 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
09-13 14:18:00.138  2860  2860 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
09-13 14:18:00.138  2860  2860 D Theme   : strTheme: com.lge.launcher2.theme.optimus
09-13 14:18:00.138  2860  2860 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
09-13 14:18:00.138  2860  2860 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
09-13 14:18:00.138  2860  2860 I Theme_WeatherAncestor_optimus: WEATHER_CP_ACCU : 
09-13 14:18:00.138  2860  2860 I Theme_WeatherAncestor_optimus: weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
09-13 14:18:00.138  2860  2860 D Theme   : strTheme: com.lge.launcher2.theme.optimus
09-13 14:18:00.138  2860  2860 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
,09-13 14:18:00.138  2860  2860 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
09-13 14:18:00.139  2860  2860 D Theme_WeatherAncestor_optimus: setTouchIntent, appWidgetId: 2
09-13 14:18:00.140  2860  2860 D Theme_WeatherAncestor_optimus: url is : null
09-13 14:18:00.145  6509  6509 W AudioCapabilities: Unsupported mime audio/evrc
09-13 14:18:00.145  2860  2860 D Theme   : strTheme: com.lge.launcher2.theme.optimus
09-13 14:18:00.145  2860  2860 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
09-13 14:18:00.145  2860  2860 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
09-13 14:18:00.146  2860  2860 D WeatherAncestor: 2 : update view, appWidgetId: 2
09-13 14:18:00.149  2860  2860 D WeatherService: 2 : TimeTick Intent has been processed, Time(hour:min:sec) 14:18:0
,09-13 14:18:00.161  6509  6509 W AudioCapabilities: Unsupported mime audio/qcelp
09-13 14:18:00.168   861   861 D PowerManagerServiceEx: releaseWakeLockInternal: lock=617577649 [*alarm*], flags=0x0
,09-13 14:18:00.172  6509  6509 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 14:18:00.217  6509  6509 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-13 14:18:00.218  6509  6509 W AudioCapabilities: Unsupported mime audio/qcelp
,09-13 14:18:00.222  6509  6509 W AudioCapabilities: Unsupported mime audio/evrc
09-13 14:18:00.247  6550  6550 I AppUp4:AppBoxCP: onCreate
,09-13 14:18:00.256  6550  6550 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-13 14:18:00.262  6509  6509 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-13 14:18:00.277  6550  6550 I AppUp4:DB:  setFingerPrint start
09-13 14:18:00.277  6550  6550 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
,09-13 14:18:00.291  6509  6509 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-13 14:18:00.295  6550  6550 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
09-13 14:18:00.295  6550  6550 I AppUp4:DB:  SDK version = 21
09-13 14:18:00.297  6550  6550 I AppUp4:DB:  beforefinger == newfinger no write in DB
,09-13 14:18:00.307  6550  6550 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-13 14:18:00.309  6509  6509 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-13 14:18:00.315  6509  6509 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-13 14:18:00.319  6509  6509 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 14:18:00.324  6550  6550 I AppUp4:CustModeStarterReceiver: onReceive
09-13 14:18:00.324  6550  6550 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
09-13 14:18:00.332  6442  6534 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1639712000
09-13 14:18:00.346  6550  6550 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@149a232d
09-13 14:18:00.346  6550  6550 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 14:18:00.354  6442  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 14:18:00.354  6442  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 14:18:00.354  6442  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 14:18:00.354  6442  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 14:18:00.354  6442  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 14:18:00.354  6550  6550 D AppUp4:CustFacade: isSimDevice : true
09-13 14:18:00.354  6442  6534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b6463c added. We now have 1 listener(s)
,09-13 14:18:00.356  6509  6509 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-13 14:18:00.359  6550  6550 D AppUp4:CustModeStarterReceiver: begin check event
09-13 14:18:00.359  6550  6550 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-13 14:18:00.361   861  1978 I ActivityManager: Killing 6185:com.lge.eula/1000 (adj 15): empty #11
09-13 14:18:00.418  1881  1881 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,09-13 14:18:00.467   861  1835 W libprocessgroup: failed to open /acct/uid_1000/pid_6185/cgroup.procs: No such file or directory
,09-13 14:18:00.534  1881  1881 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-13 14:18:00.536   861  1819 I ActivityManager: Process com.google.android.apps.docs (pid 6213) has died
,09-13 14:18:00.540   861  2173 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:00.548  6442  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,09-13 14:18:00.549  6442  6534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-13 14:18:00.551  6442  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:18:00.551  6442  6534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 14:18:00.558  6442  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 14:18:00.558  6442  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 14:18:00.558  6442  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 14:18:00.558  6442  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
09-13 14:18:00.558  6442  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 14:18:00.558  6442  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 14:18:00.558  6442  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 14:18:00.558  6442  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 14:18:00.558  6442  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 14:18:00.558  6442  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 14:18:00.558  6442  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 14:18:00.558  6442  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 14:18:00.558  6442  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 14:18:00.558  6442  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 14:18:00.558  6442  6534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37c3e04b added. We now have 1 listener(s)
09-13 14:18:00.559  6442  6534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 14:18:00.578  6442  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 14:18:00.578  6442  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 14:18:00.579  6442  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 14:18:00.579  6442  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 14:18:00.579  6442  6534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-13 14:18:00.584   861  2375 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6573 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
09-13 14:18:00.598  6509  6509 I vclib   : onServiceConnected
,09-13 14:18:00.602  6442  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:00.602   861  1819 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:00.603  6442  6534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
09-13 14:18:00.605  6509  6509 W Babel   : Attempted to change video mute state without an active call.
09-13 14:18:00.614  6509  6570 I NotificationManager: com.google.android.talk: cancel(8) by com.google.android.talk
,09-13 14:18:00.619  2041  2061 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:00.621  6442  6534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 14:18:00.621  6442  6534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:00.621  6442  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:00.621  6442  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 14:18:00.621  6442  6534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:00.621  6442  6534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:00.621  6442  6534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:00.621  6442  6534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:00.621  6442  6534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:18:00.621  6442  6534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 14:18:00.621  6442  6534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:00.622  6442  6534 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 14:18:00.626  6442  6442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:00.628  6442  6442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:00.648  6509  6509 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-13 14:18:00.648  6509  6509 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-13 14:18:00.663  6573  6573 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 14:18:00.663  6573  6573 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 14:18:00.664  6573  6573 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,09-13 14:18:00.677  6442  6442 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-13 14:18:00.715  6509  6509 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-13 14:18:00.805  6509  6509 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-13 14:18:00.806  6509  6509 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-13 14:18:00.820  6442  6456 I art     : CheckpointMarkThreadRoots callback created = 0x992773e0
,09-13 14:18:00.849  6509  6509 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
09-13 14:18:00.862  6442  6456 I art     : CheckpointMarkThreadRoots callback created = 0x992773b0
,09-13 14:18:00.891  6573  6573 I AppConfig: Total System Memory = 906309632
,09-13 14:18:00.895  6573  6573 I GalleryUtils: Application Heap = 96 MB
09-13 14:18:00.899  6573  6573 I AppConfig: App Tier : NOT_DEF
09-13 14:18:00.906  6573  6573 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,09-13 14:18:00.981   861  1978 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6595 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,09-13 14:18:01.024   861  2006 I art     : Explicit concurrent mark sweep GC freed 59721(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/35MB, paused 4.296ms total 185.147ms
,09-13 14:18:01.091  6595  6595 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 14:18:01.091  6595  6595 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 14:18:01.091  6595  6595 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-13 14:18:01.093  6595  6595 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-13 14:18:01.094  6595  6595 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 14:18:01.239  6595  6595 I SystemConfig: BUILD Country: EU
09-13 14:18:01.239  6595  6595 I SystemConfig: BUILD Operator: OPEN
,09-13 14:18:01.404   861  1298 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6617 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
09-13 14:18:01.406   861  1298 I ActivityManager: Killing 6102:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,09-13 14:18:01.486   861  1835 W libprocessgroup: failed to open /acct/uid_10086/pid_6102/cgroup.procs: No such file or directory
,09-13 14:18:01.487  6595  6612 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-13 14:18:01.487  6595  6612 I SystemConfig: existFile = false
09-13 14:18:01.487  6595  6612 I SystemConfig: canReadFile = false
09-13 14:18:01.488  6595  6612 I SystemConfig: systemFeature RCS result false
,09-13 14:18:01.488  6595  6612 D SystemConfig: refreshRcsSupport() :false
09-13 14:18:01.522  6617  6617 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-13 14:18:01.552  6617  6617 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-13 14:18:01.552  6617  6617 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-13 14:18:01.552  6617  6617 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-13 14:18:01.552  6617  6617 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-13 14:18:01.552  6617  6617 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,09-13 14:18:01.554   861  1781 I ActivityManager: Killing 6260:com.lge.bnr/1000 (adj 15): empty #11
09-13 14:18:01.587   861  1869 W libprocessgroup: failed to open /acct/uid_1000/pid_6260/cgroup.procs: No such file or directory
,09-13 14:18:01.600  3383  6635 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,09-13 14:18:01.659   861   879 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6636 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-13 14:18:01.681   304   304 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 315us total 24.657ms
,09-13 14:18:01.702  6442  6591 W jxcore-log: Initializing JXcore engine
,09-13 14:18:01.703  6442  6591 W jxcore-log: JXcore engine is ready
09-13 14:18:01.704   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 350us total 21.767ms
09-13 14:18:01.722  3383  6635 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-13 14:18:01.722  3383  6635 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,09-13 14:18:01.727   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 22.827ms
,09-13 14:18:01.768  3383  3689 I Icing   : updateResources: need to parse ozd{com.google.android.gms}
09-13 14:18:01.786  6636  6636 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 14:18:01.842  3383  6663 W IcingInternalCorpora: getNumBytesRead when not calculated.
,09-13 14:18:01.863  6591  6591 W Thread-764: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6263]" dev="sockfs" ino=6263 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-13 14:18:01.863  6591  6591 W Thread-764: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 14:18:01.863  6591  6591 W Thread-764: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5664]" dev="sockfs" ino=5664 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-13 14:18:01.863  6591  6591 W Thread-764: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
09-13 14:18:01.863  6591  6591 W Thread-764: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
09-13 14:18:01.863  6591  6591 W Thread-764: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[30077]" dev="sockfs" ino=30077 scontext=u:r:untrusted_app:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-13 14:18:01.897  6442  6591 W jxcore-log: Starting JXcore engine
,09-13 14:18:01.955  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-13 14:18:01.955  1808  1808 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-13 14:18:01.955  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,09-13 14:18:01.955  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-13 14:18:01.955  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-13 14:18:01.977   490   490 D charger_monitor: init target 500000
,09-13 14:18:02.029   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 14:18:02.029   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 14:18:02.030   861  1319 D WifiController: battery changed pluggedType: 2
,09-13 14:18:02.030   490   490 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-13 14:18:02.031  2041  3542 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 14:18:02.031  1844  1844 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-13 14:18:02.031  1844  1844 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-13 14:18:02.032  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 311
09-13 14:18:02.032  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-13 14:18:02.032  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 311
09-13 14:18:02.032  1808  1992 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-13 14:18:02.032  1808  1992 D LEDHandler: Battery Level Remaining: 100%
09-13 14:18:02.032  1808  1992 D LEDHandler: Battery Temp: 311, mChargingStatus=5, mChargingStop=false
09-13 14:18:02.034  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-13 14:18:02.066  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 311
09-13 14:18:02.066  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-13 14:18:02.066  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 311
09-13 14:18:02.067  1808  1992 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
,09-13 14:18:02.067  1808  1992 D LEDHandler: Battery Level Remaining: 100%
09-13 14:18:02.067  1808  1992 D LEDHandler: Battery Temp: 311, mChargingStatus=5, mChargingStop=false
09-13 14:18:02.068  2041  3542 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 14:18:02.069  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-13 14:18:02.069   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 14:18:02.069   861  1319 D WifiController: battery changed pluggedType: 2
09-13 14:18:02.069   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 14:18:02.069  1844  1844 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-13 14:18:02.069  1844  1844 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-13 14:18:02.106  6442  6591 W jxcore-log: Platform android
09-13 14:18:02.106  6442  6591 W jxcore-log: 
09-13 14:18:02.106  6442  6591 W jxcore-log: Process ARCH arm
09-13 14:18:02.106  6442  6591 W jxcore-log: 
,09-13 14:18:02.107  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-13 14:18:02.108  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 14:18:02.108  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-13 14:18:02.159   861   878 I ActivityManager: Process com.google.android.gms.unstable (pid 6322) has died
,09-13 14:18:02.199  1959  6671 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-13 14:18:02.251  1959  6671 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 52 ms] updated apps [took 52 ms] 
,09-13 14:18:02.419  6442  6591 I jxcore-log: JXcore Cordova bridge is ready!
09-13 14:18:02.419  6442  6591 I jxcore-log: 
09-13 14:18:02.420  6442  6591 W jxcore-log: JXcore engine is started
,09-13 14:18:02.428  6442  6534 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-13 14:18:02.435  6442  6442 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 14:18:02.978  3383  3689 I Icing   : Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,09-13 14:18:03.046  3383  3689 I Icing   : Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,09-13 14:18:03.113  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,09-13 14:18:03.113  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 14:18:03.113  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
09-13 14:18:03.118   295   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
09-13 14:18:03.193   861  1289 V AlarmManager: RTC_WAKEUP set : Alarm{37c92ece type 0 when 1473769083179 com.google.android.googlequicksearchbox} when 1473769083179
,09-13 14:18:05.116  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-13 14:18:05.116  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 14:18:05.116  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-13 14:18:06.834   490   490 D charger_monitor: init target 500000
09-13 14:18:06.834  1808  1808 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-13 14:18:06.839  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-13 14:18:06.839  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-13 14:18:06.839  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-13 14:18:06.839  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-13 14:18:06.874  2041  3542 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 14:18:06.877   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 14:18:06.877   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 14:18:06.877  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 310
09-13 14:18:06.877   861  1319 D WifiController: battery changed pluggedType: 2
09-13 14:18:06.877  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-13 14:18:06.877  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 310
09-13 14:18:06.878  1844  1844 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-13 14:18:06.878  1844  1844 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-13 14:18:06.879  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-13 14:18:06.879  1808  1992 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-13 14:18:06.879  1808  1992 D LEDHandler: Battery Level Remaining: 100%
09-13 14:18:06.879  1808  1992 D LEDHandler: Battery Temp: 310, mChargingStatus=5, mChargingStop=false
09-13 14:18:06.886   490   490 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-13 14:18:08.122   295   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,09-13 14:18:09.122  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-13 14:18:09.122  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 14:18:09.123  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-13 14:18:11.126  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-13 14:18:11.126  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 14:18:11.126  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-13 14:18:12.128  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-13 14:18:12.128  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 14:18:12.128  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-13 14:18:12.301   861  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-13 14:18:12.301   861  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-13 14:18:12.301   861  1006 D sensors_hal_Time: tsOffsetIs: Apps: 132565925892; DSPS: 4435345; Offset : -2800659467
,09-13 14:18:13.127   295   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
,09-13 14:18:13.583   861  1289 V AlarmManager: ELAPSED_WAKEUP set : Alarm{35cd69da type 2 when 133834 com.google.android.gms} when 133834
,09-13 14:18:13.613  1736  1736 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-13 14:18:13.867  1736  1736 I art     : Explicit concurrent mark sweep GC freed 37021(2MB) AllocSpace objects, 20(320KB) LOS objects, 39% free, 14MB/23MB, paused 1.674ms total 101.869ms
,09-13 14:18:13.940  1736  1736 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 14:18:13.953  3383  6720 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,09-13 14:18:13.954  3383  6720 D SchedPeriodicTask: Scheduled AdAttestation task.
09-13 14:18:14.133  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-13 14:18:14.133  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,09-13 14:18:14.133  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-13 14:18:14.355   861  1869 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6729 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,09-13 14:18:14.517  6729  6729 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-13 14:18:14.517  6729  6729 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-13 14:18:14.565  6729  6729 I MultiDex: VM with version 2.1.0 has multidex support
09-13 14:18:14.565  6729  6729 I MultiDex: install
09-13 14:18:14.565  6729  6729 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 14:18:14.604  6729  6729 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-13 14:18:14.671  6729  6729 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-13 14:18:14.672  6729  6729 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2251c27d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-13 14:18:14.673  6729  6729 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-13 14:18:14.674  6729  6729 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
09-13 14:18:14.675  6729  6729 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
,09-13 14:18:14.686  6729  6729 D ChimeraCfgMgr: Reading stored module config
,09-13 14:18:14.815  6729  6743 I art     : Background sticky concurrent mark sweep GC freed 20337(1026KB) AllocSpace objects, 3(133KB) LOS objects, 6% free, 10MB/11MB, paused 8.265ms total 83.696ms
,09-13 14:18:14.825  1736  1736 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=1ca8abff-2eec-4c6a-86e5-235486b681de
09-13 14:18:14.830  6729  6729 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
09-13 14:18:14.830  6729  6729 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-13 14:18:14.855  1736  1736 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 14:18:14.857  1736  1736 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-13 14:18:14.900  6729  6748 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-13 14:18:14.906  6729  6743 I art     : CheckpointMarkThreadRoots callback created = 0xb042d320
09-13 14:18:14.922   281  1302 D WVCdm   : Instantiating CDM.
09-13 14:18:14.924   281   281 I WVCdm   : CdmEngine::OpenSession
,09-13 14:18:14.924   281   281 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
09-13 14:18:14.962  6729  6743 I art     : CheckpointMarkThreadRoots callback created = 0xb042d310
,09-13 14:18:14.979   281   281 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-13 14:18:14.980   281   281 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
09-13 14:18:14.980   281   281 W WVCdm   : L1 library not specified. Falling Back to L3
09-13 14:18:14.991  6729  6743 I art     : Background partial concurrent mark sweep GC freed 1517(245KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 10MB/17MB, paused 14.241ms total 84.381ms
,09-13 14:18:15.069  6729  6744 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-13 14:18:15.069  6729  6744 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-13 14:18:15.070  6729  6744 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-13 14:18:15.070  6729  6744 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-13 14:18:15.071   277  1046 E BandwidthController: [LG DATA] No such appUid: 10006
09-13 14:18:15.071   277  1046 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-13 14:18:15.071   277  6757 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
09-13 14:18:15.071   277  6757 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-13 14:18:15.072   277  6757 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
09-13 14:18:15.072   277  6757 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-13 14:18:15.078   281   281 I WVCdm   : CdmEngine::QueryKeyControlInfo
09-13 14:18:15.080   281  1592 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-13 14:18:15.080   281  1592 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-13 14:18:15.080   281  1592 I WVCdm   : CdmEngine::GenerateKeyRequest
09-13 14:18:15.086   281  1592 D WVCdm   : PrepareKeyRequest: nonce=2456380217
,09-13 14:18:15.112   277  6757 D libc-netbsd: res_queryN name = xxxxx succeed
,09-13 14:18:15.114  6729  6744 I System.out: propertyValue:false
09-13 14:18:15.124  1736  2559 W GCoreFlp: No location to return for getLastLocation()
,09-13 14:18:15.136  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-13 14:18:15.136  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 14:18:15.136  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,09-13 14:18:15.168   245   245 E lowmemorykiller: Error writing /proc/6509/oom_score_adj; errno=22
,09-13 14:18:15.184  6729  6744 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-13 14:18:15.184  6729  6744 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-13 14:18:15.246   861  1869 I ActivityManager: Process com.google.android.talk (pid 6509) has died
,09-13 14:18:15.284  3383  6721 D UdcContextInitService: registered all accounts: true
,09-13 14:18:15.292  1736  2491 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 14:18:15.322  1736  2429 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-13 14:18:15.563   861  2173 I art     : Explicit concurrent mark sweep GC freed 28650(1578KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.311ms total 153.908ms
,09-13 14:18:15.937  6759  6759 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=41 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-13 14:18:16.046  6759  6759 I dex2oat : dex2oat took 108.715ms (threads: 4)
,09-13 14:18:16.070  6729  6744 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 14:18:16.070  6729  6744 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 14:18:16.070  6729  6744 I Adreno-EGL: Build Date: 03/02/15 Mon
09-13 14:18:16.070  6729  6744 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-13 14:18:16.070  6729  6744 I Adreno-EGL: Remote Branch: 
09-13 14:18:16.070  6729  6744 I Adreno-EGL: Local Patches: 
09-13 14:18:16.070  6729  6744 I Adreno-EGL: Reconstruct Branch: 
,09-13 14:18:16.537  6729  6744 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 14:18:16.537  6729  6744 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 14:18:16.537  6729  6744 I Adreno-EGL: Build Date: 03/02/15 Mon
09-13 14:18:16.537  6729  6744 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-13 14:18:16.537  6729  6744 I Adreno-EGL: Remote Branch: 
09-13 14:18:16.537  6729  6744 I Adreno-EGL: Local Patches: 
09-13 14:18:16.537  6729  6744 I Adreno-EGL: Reconstruct Branch: 
,09-13 14:18:16.597  6729  6744 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 14:18:16.597  6729  6744 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 14:18:16.597  6729  6744 I Adreno-EGL: Build Date: 03/02/15 Mon
09-13 14:18:16.597  6729  6744 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-13 14:18:16.597  6729  6744 I Adreno-EGL: Remote Branch: 
09-13 14:18:16.597  6729  6744 I Adreno-EGL: Local Patches: 
09-13 14:18:16.597  6729  6744 I Adreno-EGL: Reconstruct Branch: 
,09-13 14:18:16.812  1736  6723 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-13 14:18:16.812  1736  6723 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-13 14:18:16.812  1736  6723 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-13 14:18:16.812  1736  6723 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,09-13 14:18:16.813   277  1046 E BandwidthController: [LG DATA] No such appUid: 10006
09-13 14:18:16.813   277  1046 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-13 14:18:16.814   277  6774 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
09-13 14:18:16.814   277  6774 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-13 14:18:16.814   277  6774 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
09-13 14:18:16.814   277  6774 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-13 14:18:16.814   277  6774 D libc-netbsd: res_queryN name = xxxxx succeed
09-13 14:18:16.815  1736  6723 I System.out: propertyValue:false
09-13 14:18:16.874  1736  6723 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-13 14:18:16.874  1736  6723 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-13 14:18:17.112  1736  2429 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-13 14:18:17.125  1736  2429 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
09-13 14:18:17.133  1736  2429 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-13 14:18:15.389+0200, stopTime=2016-09-13 14:18:17.126+0200, duration=1737ms
09-13 14:18:17.139  1736  6783 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-13 14:18:17.139  1736  6783 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-13 14:18:17.139  1736  6783 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-13 14:18:17.139  1736  6783 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-13 14:18:17.143   277  1046 E BandwidthController: [LG DATA] No such appUid: 10006
09-13 14:18:17.143   277  1046 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-13 14:18:17.143   277  6785 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
09-13 14:18:17.143   277  6785 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,09-13 14:18:17.143   277  6785 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
09-13 14:18:17.144   277  6785 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-13 14:18:17.144   277  6785 D libc-netbsd: res_queryN name = xxxxx succeed
09-13 14:18:17.145  1736  6783 I System.out: propertyValue:false
,09-13 14:18:17.214  4036  4052 I art     : Explicit concurrent mark sweep GC freed 1959(69KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.159ms total 26.715ms
,09-13 14:18:17.382   281  1598 I WVCdm   : CdmEngine::CloseSession
,09-13 14:18:17.386   281  1598 I WVCdm   : L3 Terminate.
,09-13 14:18:17.644  1736  1736 I art     : Explicit concurrent mark sweep GC freed 53765(3MB) AllocSpace objects, 6(117KB) LOS objects, 39% free, 14MB/24MB, paused 2.077ms total 90.977ms
,09-13 14:18:17.685  1736  2429 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-13 14:18:17.897  1736  6805 E CommitToConfigurationOperation: Malformed snapshot token (size): 
09-13 14:18:17.898  1736  6798 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-13 14:18:17.922  1736  6805 E CommitToConfigurationOperation: Malformed snapshot token (size): 
09-13 14:18:17.923  1736  6798 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-13 14:18:17.945  1736  6805 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-13 14:18:17.946  1736  6798 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
09-13 14:18:17.946  1736  6798 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
09-13 14:18:17.963  1736  6798 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-13 14:18:18.002   861  2375 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 14:18:18.088  1736  6798 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-13 14:18:18.088  1736  6798 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-13 14:18:18.088  1736  6798 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-13 14:18:18.088  1736  6798 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-13 14:18:18.089   277  1046 E BandwidthController: [LG DATA] No such appUid: 10006
09-13 14:18:18.089   277  1046 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-13 14:18:18.089   277  6806 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
09-13 14:18:18.089   277  6806 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-13 14:18:18.089   277  6806 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
09-13 14:18:18.090   277  6806 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-13 14:18:18.090   277  6806 D libc-netbsd: res_queryN name = xxxxx succeed
09-13 14:18:18.095  1736  6798 I System.out: propertyValue:false
09-13 14:18:18.132   295   351 I ThermalEngine: Sensor:pa_therm0:34000 mC
,09-13 14:18:18.405   861  1364 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 14:18:18.647   861  1835 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 14:18:18.940   861  1978 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 14:18:19.180   861   878 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 14:18:19.329  6442  6591 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 14:18:19.329  6442  6591 I jxcore-log: 
,09-13 14:18:19.335  6442  6591 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 14:18:19.335  6442  6591 I jxcore-log: 
09-13 14:18:19.341  2041  2061 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
,09-13 14:18:19.341  6442  6591 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:19.341  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:19.341  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 14:18:19.341  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:19.341  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:19.341  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:19.341  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:19.341  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:18:19.349  2041  2061 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:19.356  6442  6591 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 14:18:19.360  6442  6591 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 14:18:19.360  6442  6591 I jxcore-log: 
,09-13 14:18:19.363  6442  6591 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 14:18:19.363  6442  6591 I jxcore-log: 
09-13 14:18:19.416   861  1835 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 14:18:19.571  1736  2429 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,09-13 14:18:19.639  2879  2879 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,09-13 14:18:19.647  2879  2879 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,09-13 14:18:20.222  6442  6591 I jxcore-log: Unit Test app is loaded
09-13 14:18:20.222  6442  6591 I jxcore-log: 
,09-13 14:18:20.245  6442  6591 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:20.245  6442  6591 I jxcore-log: 
,09-13 14:18:20.256  6442  6442 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 14:18:20.258  6442  6591 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 14:18:20.258  6442  6591 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cfab46b added. We now have 2 listener(s)
09-13 14:18:20.258   861  1791 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:20.260  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-13 14:18:20.260  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:18:20.260  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 14:18:20.260  6442  6591 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 14:18:20.260  6442  6591 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f799bc8 added. We now have 2 listener(s)
09-13 14:18:20.260  6442  6591 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 14:18:20.261  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 14:18:20.264  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:20.267  2041  2061 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:20.267  6442  6591 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:20.267  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:20.267  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 14:18:20.267  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:20.267  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:20.267  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:20.267  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:20.267  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:18:20.268  2041  2061 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:20.268  6442  6591 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:20.269  6442  6591 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:20.270  6442  6442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:20.271  6442  6591 D ExecuteNativeTests: Running unit tests
09-13 14:18:20.271  6442  6442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:20.271  6442  6591 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 14:18:20.271  6442  6591 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29034b86 added. We now have 3 listener(s)
09-13 14:18:20.272   861  2355 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:20.273  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-13 14:18:20.273  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:18:20.274  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 14:18:20.274  6442  6591 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 14:18:20.274  6442  6591 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@270e2c47 added. We now have 3 listener(s)
09-13 14:18:20.274  6442  6591 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 14:18:20.274  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 14:18:20.276  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:20.278  2041  3547 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:20.279  6442  6591 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:20.279  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:20.279  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 14:18:20.279  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:20.279  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:20.279  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:20.279  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:20.279  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:18:20.280  2041  3547 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:20.280  6442  6591 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:20.280  6442  6591 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:20.282  6442  6442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:20.283  6442  6442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:21.149  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-13 14:18:21.149  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 14:18:21.149  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-13 14:18:21.770   861  1819 I ActivityManager: Killing 2879:com.lge.music/u0a28 (adj 15): empty #11
,09-13 14:18:21.790   281   281 V AudioFlinger: 2879 died, releasing its sessions
09-13 14:18:21.790   281   281 V AudioFlinger:  pid 1755 @ 0
09-13 14:18:21.790   281   281 V AudioFlinger:  pid 3177 @ 1
09-13 14:18:21.790   281   281 V AudioFlinger:  pid 3177 @ 2
,09-13 14:18:21.807   861  2173 W libprocessgroup: failed to open /acct/uid_10028/pid_2879/cgroup.procs: No such file or directory
,09-13 14:18:21.928   490   490 D charger_monitor: init target 500000
,09-13 14:18:21.942  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-13 14:18:21.942  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-13 14:18:21.942  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-13 14:18:21.942  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-13 14:18:21.946  1808  1808 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-13 14:18:21.981   490   490 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-13 14:18:22.000  2041  3542 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 14:18:22.003  1844  1844 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-13 14:18:22.003  1844  1844 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-13 14:18:22.005  1808  1992 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-13 14:18:22.005  1808  1992 D LEDHandler: Battery Level Remaining: 100%
09-13 14:18:22.006  1808  1992 D LEDHandler: Battery Temp: 310, mChargingStatus=5, mChargingStop=false
09-13 14:18:22.007  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 310
09-13 14:18:22.007  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-13 14:18:22.008  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 310
09-13 14:18:22.010  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-13 14:18:22.014   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 14:18:22.014   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 14:18:22.017   861  1319 D WifiController: battery changed pluggedType: 2
09-13 14:18:22.110  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 310
09-13 14:18:22.110  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-13 14:18:22.110  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 310
,09-13 14:18:22.112  1844  1844 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-13 14:18:22.112  1844  1844 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-13 14:18:22.114  2041  3542 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 14:18:22.115   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 14:18:22.115   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 14:18:22.115   861  1319 D WifiController: battery changed pluggedType: 2
09-13 14:18:22.116  1808  1992 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-13 14:18:22.116  1808  1992 D LEDHandler: Battery Level Remaining: 100%
09-13 14:18:22.116  1808  1992 D LEDHandler: Battery Temp: 310, mChargingStatus=5, mChargingStop=false
09-13 14:18:22.117  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-13 14:18:23.136   295   351 I ThermalEngine: Sensor:pa_therm0:34000 mC
,09-13 14:18:25.153  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-13 14:18:25.153  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 14:18:25.154  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-13 14:18:25.620   861  1060 I PowerManagerService: ALS enabled for SRE
,09-13 14:18:25.627   861  1060 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (25891 ms ago)
09-13 14:18:25.677   861  1354 D qdlights: set_light_backlight: 254
,09-13 14:18:25.686   861  1354 D qdlights: set_light_backlight: 251
09-13 14:18:25.702   861  1354 D qdlights: set_light_backlight: 248
,09-13 14:18:25.719   861  1354 D qdlights: set_light_backlight: 244
,09-13 14:18:25.736   861  1354 D qdlights: set_light_backlight: 241
,09-13 14:18:25.752   861  1354 D qdlights: set_light_backlight: 238
,09-13 14:18:25.769   861  1354 D qdlights: set_light_backlight: 234
,09-13 14:18:25.786   861  1354 D qdlights: set_light_backlight: 231
,09-13 14:18:25.802   861  1354 D qdlights: set_light_backlight: 228
,09-13 14:18:25.819   861  1354 D qdlights: set_light_backlight: 224
,09-13 14:18:25.836   861  1354 D qdlights: set_light_backlight: 221
,09-13 14:18:25.852   861  1354 D qdlights: set_light_backlight: 218
,09-13 14:18:25.869   861  1354 D qdlights: set_light_backlight: 214
,09-13 14:18:25.886   861  1354 D qdlights: set_light_backlight: 211
,09-13 14:18:25.902   861  1354 D qdlights: set_light_backlight: 208
,09-13 14:18:25.919   861  1354 D qdlights: set_light_backlight: 204
,09-13 14:18:25.936   861  1354 D qdlights: set_light_backlight: 201
,09-13 14:18:25.952   861  1354 D qdlights: set_light_backlight: 198
,09-13 14:18:25.969   861  1354 D qdlights: set_light_backlight: 194
,09-13 14:18:25.986   861  1354 D qdlights: set_light_backlight: 191
09-13 14:18:26.002   861  1354 D qdlights: set_light_backlight: 188
,09-13 14:18:26.019   861  1354 D qdlights: set_light_backlight: 184
,09-13 14:18:26.036   861  1354 D qdlights: set_light_backlight: 181
,09-13 14:18:26.052   861  1354 D qdlights: set_light_backlight: 178
,09-13 14:18:26.069   861  1354 D qdlights: set_light_backlight: 174
,09-13 14:18:26.086   861  1354 D qdlights: set_light_backlight: 171
,09-13 14:18:26.102   861  1354 D qdlights: set_light_backlight: 168
,09-13 14:18:26.119   861  1354 D qdlights: set_light_backlight: 164
,09-13 14:18:26.136   861  1354 D qdlights: set_light_backlight: 161
,09-13 14:18:26.152   861  1354 D qdlights: set_light_backlight: 158
,09-13 14:18:26.169   861  1354 D qdlights: set_light_backlight: 154
,09-13 14:18:26.186   861  1354 D qdlights: set_light_backlight: 151
,09-13 14:18:26.202   861  1354 D qdlights: set_light_backlight: 148
,09-13 14:18:26.219   861  1354 D qdlights: set_light_backlight: 144
,09-13 14:18:26.236   861  1354 D qdlights: set_light_backlight: 141
,09-13 14:18:26.252   861  1354 D qdlights: set_light_backlight: 138
,09-13 14:18:26.269   861  1354 D qdlights: set_light_backlight: 134
,09-13 14:18:26.286   861  1354 D qdlights: set_light_backlight: 131
,09-13 14:18:26.302   861  1354 D qdlights: set_light_backlight: 128
,09-13 14:18:26.319   861  1354 D qdlights: set_light_backlight: 124
,09-13 14:18:26.336   861  1354 D qdlights: set_light_backlight: 121
,09-13 14:18:26.352   861  1354 D qdlights: set_light_backlight: 118
,09-13 14:18:26.369   861  1354 D qdlights: set_light_backlight: 114
,09-13 14:18:26.386   861  1354 D qdlights: set_light_backlight: 111
,09-13 14:18:26.402   861  1354 D qdlights: set_light_backlight: 108
,09-13 14:18:26.419   861  1354 D qdlights: set_light_backlight: 104
,09-13 14:18:26.436   861  1354 D qdlights: set_light_backlight: 101
,09-13 14:18:26.452   861  1354 D qdlights: set_light_backlight: 98
,09-13 14:18:26.469   861  1354 D qdlights: set_light_backlight: 94
,09-13 14:18:26.486   861  1354 D qdlights: set_light_backlight: 91
,09-13 14:18:26.503   861  1354 D qdlights: set_light_backlight: 88
,09-13 14:18:26.519   861  1354 D qdlights: set_light_backlight: 84
,09-13 14:18:26.536   861  1354 D qdlights: set_light_backlight: 81
,09-13 14:18:26.552   861  1354 D qdlights: set_light_backlight: 78
,09-13 14:18:26.569   861  1354 D qdlights: set_light_backlight: 74
,09-13 14:18:26.586   861  1354 D qdlights: set_light_backlight: 71
,09-13 14:18:26.602   861  1354 D qdlights: set_light_backlight: 68
,09-13 14:18:26.619   861  1354 D qdlights: set_light_backlight: 64
,09-13 14:18:26.636   861  1354 D qdlights: set_light_backlight: 61
,09-13 14:18:26.653   861  1354 D qdlights: set_light_backlight: 58
,09-13 14:18:26.669   861  1354 D qdlights: set_light_backlight: 54
,09-13 14:18:26.686   861  1354 D qdlights: set_light_backlight: 51
,09-13 14:18:26.702   861  1354 D qdlights: set_light_backlight: 48
,09-13 14:18:26.719   861  1354 D qdlights: set_light_backlight: 44
,09-13 14:18:26.736   861  1354 D qdlights: set_light_backlight: 41
,09-13 14:18:26.752   861  1354 D qdlights: set_light_backlight: 38
,09-13 14:18:26.769   861  1354 D qdlights: set_light_backlight: 34
,09-13 14:18:26.796   861  1354 D qdlights: set_light_backlight: 31
,09-13 14:18:26.802   861  1354 D qdlights: set_light_backlight: 28
09-13 14:18:26.819   861  1354 D qdlights: set_light_backlight: 24
,09-13 14:18:26.836   861  1354 D qdlights: set_light_backlight: 21
,09-13 14:18:26.853   861  1354 D qdlights: set_light_backlight: 18
,09-13 14:18:26.869   861  1354 D qdlights: set_light_backlight: 14
,09-13 14:18:26.886   861  1354 D qdlights: set_light_backlight: 11
,09-13 14:18:26.903   861  1354 D qdlights: set_light_backlight: 10
,09-13 14:18:28.145   295   351 I ThermalEngine: Sensor:pa_therm0:34000 mC
,09-13 14:18:30.484  6442  6591 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 14:18:30.484  6442  6591 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 added. We now have 4 listener(s)
09-13 14:18:30.484   861  1781 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 14:18:30.486  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-13 14:18:30.486  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:18:30.486  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 14:18:30.487  6442  6591 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 14:18:30.487  6442  6591 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d added. We now have 4 listener(s)
09-13 14:18:30.487  6442  6591 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 14:18:30.487  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 14:18:30.489  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:30.491  2041  2059 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:30.491  6442  6591 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:30.491  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:30.491  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 14:18:30.491  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:30.491  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:30.491  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:30.491  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:30.491  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:18:30.492  2041  2059 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:30.493  6442  6591 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:30.493  6442  6591 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:30.494  6442  6442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:30.496  6442  6442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:30.496  2041  2061 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
,09-13 14:18:30.505  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 14:18:30.505  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:30.505  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:30.505  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:30.505  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:30.517  6442  6591 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-13 14:18:30.517  6442  6591 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 14:18:30.517  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 14:18:30.519  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:30.519  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:30.519  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:30.519  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:30.531  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.531  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.531  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:30.531  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 14:18:30.532  6442  6591 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 removed from the list
09-13 14:18:30.532  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.532  6442  6591 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d removed from the list
09-13 14:18:30.532  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.532  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.538  6442  6591 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-13 14:18:30.539  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.539  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.539  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.539  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 not in the list
09-13 14:18:30.539  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.539  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d not in the list
09-13 14:18:30.539  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.539  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.539  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.544  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 14:18:30.544  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 14:18:30.544  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 14:18:30.544  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 14:18:30.544  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 14:18:30.544  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 14:18:30.544  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 14:18:30.544  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 14:18:30.544  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 14:18:30.544  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 14:18:30.544  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer, name> 21:1110:1110:1110:1110:1110]
09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 14:18:30.545  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.545  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.545  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.545  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 not in the list
09-13 14:18:30.545  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.545  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d not in the list
09-13 14:18:30.545  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.545  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.545  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.546  6442  6591 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 14:18:30.548  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:30.550  2041  2059 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:30.551  6442  6591 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:30.551  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:30.551  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 14:18:30.551  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:30.551  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:30.551  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:30.551  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:30.551  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:18:30.551  2041  2059 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:30.552  6442  6591 D io.jxcore.node.JXcor,eExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:30.552  6442  6591 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:30.553  6442  6442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:30.554  6442  6591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:18:30.554  6442  6591 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 14:18:30.554  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 14:18:30.554  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:30.554  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:18:30.556  6442  6442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:30.567  6442  6591 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 14:18:30.568   861  1835 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 14:18:30.581  2041  2059 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
,09-13 14:18:30.582  2041  3547 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:30.585  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 14:18:30.592  2041  2059 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:30.595  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 14:18:30.597  2041  2061 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:30.598  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 14:18:30.599  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:18:30.599  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:30.601  6442  6591 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 14:18:30.601  6442  6591 I io.jxcore.node.ConnectionHelper: start: OK
09-13 14:18:30.602  6442  6591 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-13 14:18:30.602  6442  6591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 14:18:30.602  6442  6591 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 14:18:30.604  6442  6591 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 14:18:30.604  6442  6591 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-13 14:18:30.604  6442  6591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:18:30.604  6442  6591 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 14:18:30.604  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 14:18:30.604  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:30.604  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:18:30.607  2041  2061 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:30.608  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:18:30.609  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 14:18:30.610  6442  6591 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 14:18:30.610  6442  6591 I io.jxcore.node.ConnectionHelper: start: OK
09-13 14:18:30.611  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.611  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.611  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:30.611  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 not in the list
09-13 14:18:30.611  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 14:18:30.611  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d not in the list
09-13 14:18:30.611  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.611  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.612  6442  6591 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 14:18:30.613  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:30.615  2041  2061 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:30.615  6442  6591 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:30.615  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:30.615  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 14:18:30.615  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:30.615  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:30.615  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:30.615  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:30.615  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:18:30.616  2041  2061 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:30.616  6442  6591 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:30.617  6442  6591 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:30.617  6442  6591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:18:30.617  6442  6591 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 14:18:30.617  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 14:18:30.617  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:30.617  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:18:30.618  6442  6442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:30.620  6442  6442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:30.622  2041  2061 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:30.622  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:18:30.623  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:30.624  6442  6591 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 14:18:30.624  6442  6591 I io.jxcore.node.ConnectionHelper: start: OK
09-13 14:18:30.624  6442  6591 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-13 14:18:30.624  6442  6591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 14:18:30.624  6442  6591 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 14:18:30.627  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.627  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.627  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:30.627  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 not in the list
09-13 14:18:30.627  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.628  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d not in the list
09-13 14:18:30.628  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.628  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.629  6442  6591 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 14:18:30.629  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.629  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.629  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.629  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 not in the list
09-13 14:18:30.629  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.629  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d not in the list
09-13 14:18:30.629  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.629  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.629  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.630  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 14:18:30.630  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.630  6442  6591 W org.thaliproject.p2p.btconnectorlib.interna,l.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.630  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.630  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 not in the list
09-13 14:18:30.630  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.630  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d not in the list
09-13 14:18:30.630  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.630  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.630  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.631  6442  6591 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 14:18:30.631  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.631  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.631  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.631  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 not in the list
09-13 14:18:30.631  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.631  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d not in the list
09-13 14:18:30.631  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.631  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.631  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.632  6442  6591 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 14:18:30.632  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.632  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.632  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.632  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 not in the list
09-13 14:18:30.632  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.632  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d not in the list
09-13 14:18:30.632  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.632  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.632  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.633  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 14:18:30.634  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:30.634  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:30.634  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:30.634  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 14:18:30.635  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:30.635  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:30.635  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:30.635  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 14:18:30.636  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:30.636  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:30.636  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:30.636  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.636  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.636  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.636  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 not in the list
09-13 14:18:30.636  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.636  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d not in the list
09-13 14:18:30.636  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.636  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.636  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.638  6442  6591 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:30.638  6442  6591 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 14:18:30.638  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 14:18:30.643  6442  6591 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:30.644  6442  6591 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 14:18:30.644  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 14:18:30.645  6442  6591 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 14:18:30.645  6442  6591 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 14:18:30.646  6442  6591 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 14:18:30.646  6442  6591 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:30.646  6442  6591 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 14:18:30.646  6442  6591 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 14:18:30.646  6442  6591 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:30.646  6442  6591 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 14:18:30.646  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 14:18:30.655  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 14:18:30.656  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 14:18:30.656  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 14:18:30.657  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 14:18:30.657  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 14:18:30.657  6442  6591 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 14:18:30.657  6442  6591 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:30.657  6442  6591 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 14:18:30.657  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.658  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.658  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.658  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 14:18:30.658  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 not in the list
09-13 14:18:30.658  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.658  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d not in the list
09-13 14:18:30.658  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.658  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.658  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.659  6442  6591 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 14:18:30.659  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.659  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.660  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.660  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 not in the list
09-13 14:18:30.660  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.660  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d not in the list
09-13 14:18:30.660  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.660  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.660  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.660  6442  6591 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 14:18:30.661  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.661  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.661  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.661  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 not in the list
09-13 14:18:30.661  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.661  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d not in the list
09-13 14:18:30.661  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.661  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.661  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.662  6442  6591 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 14:18:30.662  6442  6591 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 14:18:30.662  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 14:18:30.662  6442  6591 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 14:18:30.662  6442  6591 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 14:18:30.662  6442  6591 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 14:18:30.662  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 14:18:30.662  6442  6591 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,09-13 14:18:30.662  6442  6591 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 14:18:30.662  6442  6591 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 14:18:30.662  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 14:18:30.662  6442  6591 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 14:18:30.663  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.663  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.663  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.663  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 not in the list
09-13 14:18:30.663  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.663  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d not in the list
09-13 14:18:30.663  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.663  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.663  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.663  6442  6591 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 14:18:30.665  6442  6839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 861
09-13 14:18:30.666  6442  6838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 861)
09-13 14:18:30.666  6442  6838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 861)
09-13 14:18:30.668  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:30.670  2041  2059 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:30.670  6442  6591 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:30.670  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:30.670  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 14:18:30.670  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:30.670  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:30.670  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:30.670  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:30.670  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:18:30.671  2041  2059 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:30.672  6442  6591 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:30.672  6442  6591 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:30.673  6442  6442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:30.675  6442  6442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:30.675  6442  6591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:18:30.675  6442  6591 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 14:18:30.675  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 14:18:30.675  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:30.675  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:18:30.678  2041  2059 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:30.678  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:18:30.679  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:30.680  6442  6591 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 14:18:30.680  6442  6591 I io.jxcore.node.ConnectionHelper: start: OK
09-13 14:18:30.680  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.680  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.680  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:30.680  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 not in the list
09-13 14:18:30.680  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.680  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d not in the list
09-13 14:18:30.680  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.680  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.682  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.682  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.682  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.682  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 not in the list
09-13 14:18:30.682  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.682  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d not in the list
09-13 14:18:30.682  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.682  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.682  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.684  6442  6591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 14:18:30.684  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:30.685  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 14:18:30.686  6442  6591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 14:18:30.686  6442  6591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 14:18:30.687  6442  6442 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 14:18:30.687  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 14:18:30.687  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 14:18:30.688  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.688  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 14:18:30.688  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 14:18:30.689  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 14:18:30.689  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.689  6442  6591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 14:18:30.690  6442  6442 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 14:18:30.690  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 not in the list
09-13 14:18:30.690  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.690  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 14:18:30.690  6442  6591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 14:18:30.690  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 14:18:30.691  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 14:18:30.692  2041  2061 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:30.692   861  1298 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:30.693  6442  6841 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 14:18:30.696  6442  6591 D BluetoothLeScanner: could not find callback wrapper
09-13 14:18:30.696  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 14:18:30.696  6442  6591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 14:18:30.696  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.696  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:30.697  6442  6591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:18:30.698  6442  6442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:30.698  6442  6442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:30.698  6442  6442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:18:30.699  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d not in the list
09-13 14:18:30.699  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.699  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.699  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.700  6442  6591 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 14:18:30.700  6442  6591 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 14:18:30.700  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 14:18:30.700  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:30.700  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:30.700  6442  6591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:30.701  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.701  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.701  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.701  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 not in the list
09-13 14:18:30.701  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.701  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d not in the list
09-13 14:18:30.701  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.701  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.701  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.703   861  2355 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:30.704   861  1819 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:30.705   861   878 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:30.705  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.705  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.,bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.705  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.705  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 not in the list
09-13 14:18:30.705  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.705  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d not in the list
09-13 14:18:30.705  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.705  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.705  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.706  2041  3547 I bt-btif : BTA_JvCreateRecordByUser
09-13 14:18:30.706  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.706  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.706  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:30.706  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d21aa4 not in the list
09-13 14:18:30.706  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.706  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296b800d not in the list
09-13 14:18:30.707  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.707  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.707  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:30.708  6442  6591 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 14:18:30.708  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 14:18:30.708  6442  6591 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 14:18:30.708  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-13 14:18:30.708  6442  6591 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 14:18:30.708  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 14:18:30.710  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 14:18:30.710  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 14:18:30.710  6442  6591 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 14:18:30.711  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 14:18:30.711  6442  6591 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 14:18:30.711  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 14:18:30.711  6442  6591 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 14:18:30.711  6442  6591 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-13 14:18:30.711  6442  6591 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 14:18:30.712  6442  6591 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 14:18:30.712  6442  6591 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 14:18:30.712  6442  6591 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 14:18:30.712  6442  6591 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-13 14:18:30.712  6442  6591 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 14:18:30.713  2041  3547 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=87 mFd=85
09-13 14:18:30.714  2041  3614 I bt-btif : BTA_JvRfcommStartServer
09-13 14:18:30.717  2041  3685 I bt-btif : BTA_JvDeleteRecord
09-13 14:18:30.717  2041  3685 I bt-btif : BTA_JvRfcommStopServer
,09-13 14:18:30.717  6442  6841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,09-13 14:18:30.717  6442  6841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 14:18:30.717  6442  6841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 14:18:30.718  6442  6442 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 14:18:30.722  6442  6843 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-13 14:18:30.723  6442  6843 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-13 14:18:31.198  6442  6442 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 14:18:31.224  6442  6848 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-13 14:18:31.224  6442  6848 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-13 14:18:31.227  6442  6848 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-13 14:18:31.227  6442  6848 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-13 14:18:31.228   277  1046 E BandwidthController: [LG DATA] No such appUid: 10030
09-13 14:18:31.228   277  1046 D DnsProxyListener: App 10030 tries DNS query. Accept family:0 protocol:0
09-13 14:18:31.228   277  6850 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
09-13 14:18:31.228   277  6850 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-13 14:18:31.229   277  6850 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-13 14:18:31.229   277  6850 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-13 14:18:31.230  6442  6848 I System.out: propertyValue:false
09-13 14:18:31.232  6442  6843 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-13 14:18:31.232  6442  6843 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 14:18:31.232  6442  6843 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:31.233  6442  6848 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-13 14:18:31.233  6442  6848 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 14:18:31.233  6442  6848 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:31.234  6442  6848 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:31.235  6442  6848 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 14:18:31.238  6442  6852 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 915, name: IncomingSocketThread/Receiver)
09-13 14:18:31.238  6442  6852 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 915, thread name: IncomingSocketThread/Receiver)
09-13 14:18:31.238  6442  6852 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 14:18:31.239  6442  6852 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 915, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 14:18:31.244  6442  6843 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:31.245  6442  6843 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 14:18:31.248  6442  6851 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 914, name: IncomingSocketThread/Sender)
09-13 14:18:31.248  6442  6853 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 913, name: OutgoingSocketThread/Sender)
09-13 14:18:31.250  6442  6854 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 916, name: OutgoingSocketThread/Receiver)
09-13 14:18:31.250  6442  6854 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 916, thread name: OutgoingSocketThread/Receiver)
09-13 14:18:31.250  6442  6854 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 14:18:31.250  6442  6854 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 916, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 14:18:31.730  6442  6591 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-13 14:18:31.731  6442  6591 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-13 14:18:31.732  6442  6591 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c570847 Bundle[{}]
09-13 14:18:31.733  6442  6591 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 14:18:31.733  6442  6591 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-13 14:18:31.734  6442  6591 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-13 14:18:31.739  6442  6591 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 14:18:31.740  6442  6591 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 14:18:31.740  6442  6591 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-13 14:18:31.751  6442  6855 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-13 14:18:31.751  6442  6855 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 14:18:32.256  6442  6857 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-13 14:18:32.256  6442  6857 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-13 14:18:32.261  6442  6855 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-13 14:18:32.261  6442  6855 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 14:18:32.261  6442  6855 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:32.261  6442  6855 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:32.261  6442  6855 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 14:18:32.263  6442  6857 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-13 14:18:32.263  6442  6857 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 14:18:32.263  6442  6857 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:32.263  6442  6857 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:32.263  6442  6857 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 14:18:32.266  6442  6860 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 928, name: OutgoingSocketThread/Receiver)
09-13 14:18:32.267  6442  6860 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 928, thread name: OutgoingSocketThread/Receiver)
09-13 14:18:32.267  6442  6860 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 14:18:32.267  6442  6860 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 928, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 14:18:32.269  6442  6859 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 927, name: OutgoingSocketThread/Sender)
,09-13 14:18:32.274  6442  6861 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 929, name: IncomingSocketThread/Sender)
09-13 14:18:32.276  6442  6862 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 930, name: IncomingSocketThread/Receiver)
09-13 14:18:32.276  6442  6862 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 930, thread name: IncomingSocketThread/Receiver)
09-13 14:18:32.276  6442  6862 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 14:18:32.276  6442  6862 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 930, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 14:18:32.302   861  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-13 14:18:32.302   861  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-13 14:18:32.302   861  1006 D sensors_hal_Time: tsOffsetIs: Apps: 152566602297; DSPS: 5090727; Offset : -2800656194
,09-13 14:18:32.622   861  1060 I PowerManagerService: ALS enabled for SRE
09-13 14:18:32.622   861  1060 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (32887 ms ago)
09-13 14:18:32.623   861  1060 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-13 14:18:32.635   861  1060 I PowerManagerService: ALS enabled for SRE
09-13 14:18:32.636   861  1060 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (32900 ms ago)
,09-13 14:18:32.644   861  1060 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
09-13 14:18:32.648   861  1060 I PowerManagerService: Sleeping (uid 1000)...
09-13 14:18:32.648   861  1060 D LPWGController: [updateScreenState] screen on = false
09-13 14:18:32.653   861  1060 D LPWGController: disable proximity sensor
09-13 14:18:32.653   861  1060 D LPWGController: enable proximity sensor
,09-13 14:18:32.668   861  1060 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@12531dab] by com.android.server.power.ProximitySensorListener.enable():120
,09-13 14:18:32.675   861  1060 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
09-13 14:18:32.675   861  1060 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
09-13 14:18:32.675   861  1060 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
09-13 14:18:32.676   861  1060 I sensors_hal_Ctx: activate: handle is 48, enable
09-13 14:18:32.676   861  1060 V sensors_hal_Ctx: activate sensors is 1400000000000
09-13 14:18:32.676   861  1060 D sensors_hal_Thresh: enable: handle=48
09-13 14:18:32.676   861  1060 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
09-13 14:18:32.677   861  1060 D sensors_hal_Util: waitForResponse: timeout=1000
09-13 14:18:32.682   861  1007 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
09-13 14:18:32.682   861  1007 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
,09-13 14:18:32.684   861  1060 D sensors_hal_Thresh: enable: Received response: 0
09-13 14:18:32.685   861  1060 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (32950 ms ago)
09-13 14:18:32.704   861  1060 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 14:18:32.704   861  1060 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 14:18:32.704   861  1060 I Adreno-EGL: Build Date: 03/02/15 Mon
09-13 14:18:32.704   861  1060 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-13 14:18:32.704   861  1060 I Adreno-EGL: Remote Branch: 
09-13 14:18:32.704   861  1060 I Adreno-EGL: Local Patches: 
09-13 14:18:32.704   861  1060 I Adreno-EGL: Reconstruct Branch: 
,09-13 14:18:32.731   248  1294 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1033 us)
,09-13 14:18:32.760  6442  6591 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 939)
09-13 14:18:32.760  6442  6591 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 14:18:32.760  6442  6591 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 940)
09-13 14:18:32.762  6442  6591 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 14:18:32.762  6442  6591 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28d2c44b added. We now have 4 listener(s)
,09-13 14:18:32.773   861  1781 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:32.777  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-13 14:18:32.777  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:18:32.778  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 14:18:32.778  6442  6591 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 14:18:32.778  6442  6591 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368e9e28 added. We now have 4 listener(s)
09-13 14:18:32.778  6442  6591 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 14:18:32.782  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 14:18:32.795  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:32.805  2041  2059 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:32.806  6442  6591 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:32.806  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:32.806  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 14:18:32.806  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:32.806  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:32.806  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:32.806  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:32.806  6442  6591 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:18:32.807  2041  2059 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:32.808  6442  6591 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:32.808  6442  6591 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:32.810  6442  6442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:32.811  6442  6442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:32.812  2041  2061 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:32.813  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:32.813  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:32.813  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:32.813  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 14:18:32.813  6442  6591 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28d2c44b removed from the list
09-13 14:18:32.813  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:32.813  6442  6591 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368e9e28 removed from the list
09-13 14:18:32.813  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:32.813  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:32.815  6442  6591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:18:32.815  6442  6591 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 14:18:32.815  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 14:18:32.815  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:32.815  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 14:18:32.824  6442  6591 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 14:18:32.824   861  1854 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:32.828  2041  2059 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
,09-13 14:18:32.839  2041  3547 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:32.840  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 14:18:32.841  2041  2059 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:32.841  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 14:18:32.843  2041  2061 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
,09-13 14:18:32.846  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:18:32.846  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:32.848  6442  6591 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 14:18:32.909   430   995 I Sensors : sns_pwr.c(273):acquiring wakelock
,09-13 14:18:32.912   861  1007 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
09-13 14:18:32.913   861  1007 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
,09-13 14:18:32.913   861  1007 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
09-13 14:18:32.913   861  1007 D sensors_hal_Thresh: processInd: handle 48, count=1
09-13 14:18:32.913   861  1007 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
09-13 14:18:32.913   861  1007 I sensors_hal_Thresh: processInd : proximity state changed - FAR
09-13 14:18:32.913   861  1052 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
09-13 14:18:32.913   861  1052 D sensors_hal_Ctx: poll: count: 256
09-13 14:18:32.913   861  1052 I sensors_hal_Ctx: poll: released wakelock sensor_ind
09-13 14:18:32.913   861  1052 D sensors_hal_Util: waitForResponse: timeout=0
09-13 14:18:32.914   861  1060 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
09-13 14:18:32.914   861  1060 I LPWGController: current mode = 1  value = 1 1
09-13 14:18:32.915   861  1060 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
09-13 14:18:33.018   861  1060 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,09-13 14:18:33.150   295   351 I ThermalEngine: Sensor:pa_therm0:34000 mC
,09-13 14:18:33.167  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-13 14:18:33.167  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,09-13 14:18:33.167  1377  1377 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-13 14:18:33.255   861  1354 D qdlights: set_light_backlight: 0
,09-13 14:18:33.275   861  1060 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,09-13 14:18:33.281   861  1060 I sensors_hal_Ctx: activate: handle is 46, disable
09-13 14:18:33.281   861  1060 V sensors_hal_Ctx: activate sensors is 1000000000000
09-13 14:18:33.281   861  1060 D sensors_hal_LP2: enable: handle=46
09-13 14:18:33.281   861  1060 D sensors_hal_LP2: enable: Disabling sensor handle=46
09-13 14:18:33.281   861  1060 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
09-13 14:18:33.283   248   248 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
09-13 14:18:33.283   248   248 D qdhwcomposer: hwc_blank: Blanking display: 0
09-13 14:18:33.286   861  1032 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
09-13 14:18:33.286   861  1032 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,09-13 14:18:33.291   861  1058 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
09-13 14:18:33.292   861   861 V ActivityManager: Display changed displayId=0
,09-13 14:18:33.371  1755  1755 D DSDPConnection: Display #0 changed.
09-13 14:18:33.471   248   248 D qdhwcomposer: hwc_blank: Done blanking display: 0
09-13 14:18:33.471   861  1354 D SurfaceControl: Excessive delay in setPowerMode(): 188ms
09-13 14:18:33.473   248   704 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-13 14:18:33.473   861  1354 I QCOM PowerHAL: Got set_interactive hint
,09-13 14:18:33.486  6442  6442 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-13 14:18:33.486  6442  6442 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
09-13 14:18:33.489  1377  2652 D KeyguardViewMediator: onScreenTurnedOff(3)
09-13 14:18:33.495  1337  3499 D SmartCoverViewMediator: onScreenTurnedOff(3)
09-13 14:18:33.504  1337  3499 D SmartCoverViewMediator: notifyScreenOffLocked
,09-13 14:18:33.506  1377  2652 D KeyguardViewMediator: notifyScreenOffLocked
09-13 14:18:33.508  1337  1337 D SmartCoverViewMediator: handleNotifyScreenOFF
09-13 14:18:33.518  6442  6442 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c570847 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2f875a27, 16908290=android.view.AbsSavedState$1@2f875a27}, android:focusedViewId=100}]}]
09-13 14:18:33.518  6442  6442 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-13 14:18:33.518  6442  6442 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 14:18:33.518  6442  6442 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-13 14:18:33.526  1377  2652 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
09-13 14:18:33.526  1377  1377 D KeyguardViewMediator: handleNotifyScreenOff
09-13 14:18:33.556  1377  1377 D ScreenTurnOffBySensor: unregisterProximitySensor
,09-13 14:18:33.566  1377  1377 D StatusBarWindowView: onScreenTurnedOff why = 3
09-13 14:18:33.569   861   861 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
,09-13 14:18:33.578   281  1598 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 861
09-13 14:18:33.578   281  1598 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-13 14:18:33.578   281  1598 V voice   : voice_set_parameters: enter: screen_state=on
09-13 14:18:33.580   281  1598 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
09-13 14:18:33.580   281  1598 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-13 14:18:33.580   281  1598 V voice   : voice_set_parameters: exit with code(0)
09-13 14:18:33.580   281  1598 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
09-13 14:18:33.580   281  1598 V msm8974_platform: platform_set_parameters: enter: screen_state=on
09-13 14:18:33.580   281  1598 V msm8974_platform: platform_set_parameters: exit with code(0)
09-13 14:18:33.580   281  1598 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-13 14:18:33.580   281  1598 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
09-13 14:18:33.581   281  1598 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
09-13 14:18:33.581   281  1598 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-13 14:18:33.585  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
09-13 14:18:33.586   861  1314 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
,09-13 14:18:33.588  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
09-13 14:18:34.228   861   991 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,09-13 14:18:34.232  1844  1844 I QCNEJ   : |CORE| sendScreenState: state:true
09-13 14:18:34.241  1808  1992 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
,09-13 14:18:34.248  1808  1992 D LEDService: stopPatternFlashing()
09-13 14:18:34.250  1808  1992 D qdlights: set_light_notifications: 0,0,0,0,3
09-13 14:18:34.252  1808  1992 I LEDService: getCurrentHighestLGLedRecord : size = 1
09-13 14:18:34.252  1808  1992 D qdlights: set_light_notifications: 0,0,0,0,3
09-13 14:18:34.253  1808  1992 I LEDService: updateLightsLocked : turn off led
09-13 14:18:34.253  1808  1992 D qdlights: set_light_notifications: 0,0,0,0,3
09-13 14:18:34.256  1808  1992 D LEDHandler: RESTART MSG
,09-13 14:18:34.283   861   879 D SplitWindow: check instance of lgWin Window{3a4e3420 u0 SearchPanel}
,09-13 14:18:34.289  1808  1808 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
09-13 14:18:34.290  1808  1808 D Cliptray Service: lockStatus = 0
09-13 14:18:34.300   861  1835 D InputDispatcher: Window went away: Window{31036376 u0 SearchPanel}
,09-13 14:18:34.303  1377  1377 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
09-13 14:18:34.324  1377  1377 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,09-13 14:18:34.333  1790  1790 D LNfcService: action : android.intent.action.SCREEN_ON
,09-13 14:18:34.345  1790  6882 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
09-13 14:18:34.345  1790  6882 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
09-13 14:18:34.346  1790  6882 D LNfcService: isRequireNfcCRouting() return true
09-13 14:18:34.346  1790  6882 D LNfcService: isHCERoutingtoHost() return : true
09-13 14:18:34.346  1790  6882 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
09-13 14:18:34.346  1790  6882 D NfcService: mEnableLPD: true
09-13 14:18:34.346  1790  6882 D NfcService: mEnableReader: false
09-13 14:18:34.346  1790  6882 D NfcService: mEnableHostRouting: true
09-13 14:18:34.346  1790  6882 D NfcService: newParams.techmask= mTechMask: default
09-13 14:18:34.346  1790  6882 D NfcService: mEnableLPD: true
09-13 14:18:34.346  1790  6882 D NfcService: mEnableReader: false
09-13 14:18:34.346  1790  6882 D NfcService: mEnableHostRouting: true
09-13 14:18:34.346  1790  6882 D NfcService: screenState= 3
09-13 14:18:34.346  1790  6882 D NfcService: Discovery configuration equal, not updating.
09-13 14:18:34.355   861   861 D Ulp_jni : JNI:system_update. Event-0
,09-13 14:18:34.373  1755  1755 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,09-13 14:18:34.384   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 14:18:34.384   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 14:18:34.384   861   861 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
09-13 14:18:34.387  2860  2860 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:18:34
,09-13 14:18:34.389  2860  2860 D WeatherService: 2 : ACTION screen on
09-13 14:18:34.391  2860  2860 D WeatherService: 2 : shouldTimeTickRegistered : false
09-13 14:18:34.397  2860  2860 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 14:18:34.397  2860  2860 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:18:34
09-13 14:18:34.405  4142  4142 D AppCleanupService: android.intent.action.SCREEN_ON
,09-13 14:18:34.410   430   443 I Sensors : sns_pwr.c(301):releasing wakelock
,09-13 14:18:34.423   281   281 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 861
09-13 14:18:34.424   281   281 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-13 14:18:34.424   281   281 V voice   : voice_set_parameters: enter: screen_state=off
09-13 14:18:34.424   281   281 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
09-13 14:18:34.424   281   281 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-13 14:18:34.424   281   281 V voice   : voice_set_parameters: exit with code(0)
09-13 14:18:34.424   281   281 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
09-13 14:18:34.424   281   281 V msm8974_platform: platform_set_parameters: enter: screen_state=off
09-13 14:18:34.424   281   281 V msm8974_platform: platform_set_parameters: exit with code(0)
09-13 14:18:34.424   281   281 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-13 14:18:34.424   281   281 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
09-13 14:18:34.424   281   281 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-13 14:18:34.426   861  1319 D WifiController: CMD_SCREEN_OFF 
09-13 14:18:34.426   861  1319 D WifiController: shouldWifiStayAwake TRUE
09-13 14:18:34.428  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
09-13 14:18:34.429   861   991 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
09-13 14:18:34.456  1844  1844 I QCNEJ   : |CORE| sendScreenState: state:false
,09-13 14:18:34.458  1808  1992 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
09-13 14:18:34.458  1808  1992 D LEDService: stopPatternFlashing()
09-13 14:18:34.458  1808  1992 D qdlights: set_light_notifications: 0,0,0,0,3
09-13 14:18:34.460  1808  1992 I LEDService: getCurrentHighestLGLedRecord : size = 1
09-13 14:18:34.460  1808  1992 D qdlights: set_light_notifications: 0,0,0,0,3
09-13 14:18:34.460  1808  1808 D VolumeVibrator: clear
09-13 14:18:34.462  1808  1992 I LEDService: updateLightsLocked : turn on led
09-13 14:18:34.462  1808  1992 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
09-13 14:18:34.462  1808  1992 E LEDService: Can't handle this request of patternId:0
09-13 14:18:34.463  1808  1992 D LEDHandler: RESTART MSG
09-13 14:18:34.468  1808  1808 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,09-13 14:18:34.470  1790  1790 D LNfcService: action : android.intent.action.SCREEN_OFF
09-13 14:18:34.472  1790  2208 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
09-13 14:18:34.489  1881  1881 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,09-13 14:18:34.508  1755  1755 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,09-13 14:18:34.513   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 14:18:34.513   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 14:18:34.514   861   861 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
09-13 14:18:34.515  2860  2860 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:18:34
09-13 14:18:34.515  2860  2860 D WeatherService: 2 : ACTION screen off
09-13 14:18:34.517  2860  2860 D WeatherService: 2 : TimeTick Receiver Unregister
09-13 14:18:34.526   861  1887 I ActivityManager: Process com.android.contacts (pid 6595) has died
,09-13 14:18:34.528  2860  2860 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:18:34
09-13 14:18:34.531  4142  4142 D AppCleanupService: android.intent.action.SCREEN_OFF
09-13 14:18:34.535  4142  6885 D AppCleanupService: AppUsageStatsSaveTask
,09-13 14:18:34.568  1790  2667 E NxpNfcJni: getReconnectState = 0x0
,09-13 14:18:34.570  1790  2208 D LCardEmulationManager: getHceAppCount hostAppNum : 0
09-13 14:18:34.570  1790  2208 D LCardEmulationManager: getDefaultRoute
09-13 14:18:34.571  1790  2208 D LNfcService: isRequireNfcCRouting() return true
09-13 14:18:34.571  1790  2208 D LNfcService: isHCERoutingtoHost() return : true
09-13 14:18:34.571  1790  2208 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
09-13 14:18:34.571  1790  2208 D NfcService: mEnableLPD: true
09-13 14:18:34.571  1790  2208 D NfcService: mEnableReader: false
09-13 14:18:34.571  1790  2208 D NfcService: mEnableHostRouting: true
09-13 14:18:34.571  1790  2208 D NfcService: newParams.techmask= mTechMask: 0
09-13 14:18:34.571  1790  2208 D NfcService: mEnableLPD: true
09-13 14:18:34.571  1790  2208 D NfcService: mEnableReader: false
09-13 14:18:34.571  1790  2208 D NfcService: mEnableHostRouting: true
09-13 14:18:34.571  1790  2208 D NfcService: screenState= 1
09-13 14:18:34.606  1790  2667 E NxpNfcJni: getReconnectState = 0x0
,09-13 14:18:35.848  6442  6591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 14:18:35.848  6442  6591 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 14:18:35.850  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:35.850  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:35.850  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:35.850  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28d2c44b not in the list
09-13 14:18:35.850  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:35.850  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368e9e28 not in the list
09-13 14:18:35.850  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:35.850  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:35.850  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:35.851  6442  6591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:18:35.852  6442  6591 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-13 14:18:35.852  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-13 14:18:35.852  6442  6591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:18:35.852  6442  6591 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 14:18:35.852  6442  6591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 14:18:35.852  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:35.853  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 14:18:35.853  6442  6591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 14:18:35.853  6442  6591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 14:18:35.854  6442  6442 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 14:18:35.855  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 14:18:35.855  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 14:18:35.855  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:35.855  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:18:35.859  2041  2061 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:35.859  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:18:35.860  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:35.860   861  1835 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 14:18:35.862  6442  6591 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 14:18:35.862  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:35.862  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 14:18:35.862  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 14:18:35.862  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 14:18:35.862  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:35.862  6442  6591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 14:18:35.862  6442  6442 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 14:18:35.863  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28d2c44b not in the list
09-13 14:18:35.863  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:35.863  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368e9e28 not in the list
09-13 14:18:35.863  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:35.863  6442  6887 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 14:18:35.863  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:35.863  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:35.864  2041  2059 I bt-btif : BTA_JvCreateRecordByUser
09-13 14:18:35.864  2041  3614 I bt-btif : BTA_JvRfcommStartServer
09-13 14:18:35.864  2041  3685 I bt-btif : BTA_JvDeleteRecord
09-13 14:18:35.864  2041  3685 I bt-btif : BTA_JvRfcommStopServer
09-13 14:18:35.864  6442  6591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:18:35.864  6442  6591 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 14:18:35.864  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 14:18:35.864  6442  6887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 14:18:35.864  6442  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 14:18:35.864  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:35.864  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:18:35.864  6442  6887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 14:18:35.865  6442  6442 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 14:18:35.867  2041  2059 D BluetoothAdapterService(1068211791): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@977319d
09-13 14:18:35.868  6442  6591 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:18:35.868  6442  6591 D org.thaliproject.p2p.btconnectorlib.int,ernal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:35.869  6442  6591 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 14:18:38.154   295   351 I ThermalEngine: Sensor:pa_therm0:34000 mC
,09-13 14:18:38.516  1377  1377 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,09-13 14:18:38.521   861  1289 V AlarmManager: ELAPSED_WAKEUP set : Alarm{27bac79b type 2 when 158768 com.android.systemui} when 158768
,09-13 14:18:38.537  1755  1771 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
09-13 14:18:38.542  1755  1771 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-13 14:18:38.542  1755  1771 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-13 14:18:38.546  1755  1771 V TelecomServiceImpl: getCallState : 0
,09-13 14:18:38.552  1755  2663 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
09-13 14:18:38.553  1755  2663 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-13 14:18:38.553  1755  2663 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-13 14:18:38.554  1377  1377 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
09-13 14:18:38.555  1377  1377 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
09-13 14:18:38.870  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:38.870  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:38.870  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:38.870  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28d2c44b not in the list
09-13 14:18:38.870  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:38.870  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368e9e28 not in the list
09-13 14:18:38.870  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:38.870  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:38.870  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:38.871  6442  6591 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:38.871  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:38.872  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:38.872  6442  6591 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28d2c44b not in the list
09-13 14:18:38.872  6442  6591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:38.872  6442  6591 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368e9e28 not in the list
09-13 14:18:38.872  6442  6591 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:38.872  6442  6591 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:38.872  6442  6591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:38.873  6442  6591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 14:18:38.873  6442  6591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 14:18:38.873  6442  6591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 14:18:38.874  6442  6591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:18:38.874  6442  6591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery,: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 14:18:38.874  6442  6591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 14:18:38.895  6442  6891 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 959, name: My test thread name)
,09-13 14:18:40.894  6442  6591 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 959
09-13 14:18:40.894  6442  6591 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 959, name: My test thread name)
,09-13 14:18:40.900  6442  6892 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 960, name: My test thread name)
09-13 14:18:40.900  6442  6892 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 960, thread name: My test thread name)
09-13 14:18:40.900  6442  6892 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 960, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-13 14:18:40.902  6442  6591 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:40.905  6442  6893 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 964, name: My test thread name)
09-13 14:18:40.912  6442  6893 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 964, thread name: My test thread name): Test exception.
09-13 14:18:40.912  6442  6893 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 964, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-13 14:18:40.918  6442  6591 I jxcore-log: Total number of executed tests:  76
09-13 14:18:40.918  6442  6591 I jxcore-log: 
09-13 14:18:40.919  6442  6591 I jxcore-log: Number of passed tests:  76
09-13 14:18:40.919  6442  6591 I jxcore-log: 
09-13 14:18:40.919  6442  6591 I jxcore-log: Number of failed tests:  0
09-13 14:18:40.919  6442  6591 I jxcore-log: 
09-13 14:18:40.920  6442  6591 I jxcore-log: Number of ignored tests:  0
09-13 14:18:40.920  6442  6591 I jxcore-log: 
09-13 14:18:40.920  6442  6591 I jxcore-log: Total duration:  10438
09-13 14:18:40.920  6442  6591 I jxcore-log: 
09-13 14:18:40.924  6442  6591 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 14:18:40.924  6442  6591 I jxcore-log: 
09-13 14:18:40.927  6442  6591 I jxcore-log: My device name is: LGE-LG-D722
09-13 14:18:40.927  6442  6591 I jxcore-log: 
09-13 14:18:40.930  6442  6591 I jxcore-log: WARN testUtils: myNameCallback not set!
09-13 14:18:40.930  6442  6591 I jxcore-log: 
,09-13 14:18:40.942  6442  6591 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:40.942  6442  6591 I jxcore-log: 
09-13 14:18:40.943  6442  6591 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:40.943  6442  6591 I jxcore-log: 
09-13 14:18:40.944  6442  6591 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:40.944  6442  6591 I jxcore-log: 
09-13 14:18:40.959  6442  6591 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:40.959  6442  6591 I jxcore-log: 
09-13 14:18:40.963  6442  6591 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:40.963  6442  6591 I jxcore-log: 
,09-13 14:18:40.968  6442  6591 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:40.968  6442  6591 I jxcore-log: 
09-13 14:18:40.970  6442  6591 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 14:18:40.970  6442  6591 I jxcore-log: 
09-13 14:18:40.971  6442  6591 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:40.971  6442  6591 I jxcore-log: 
09-13 14:18:41.095  6442  6891 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 959, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,09-13 14:18:41.423  6894  6894 D AndroidRuntime: 
09-13 14:18:41.423  6894  6894 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 14:18:41.428  6894  6894 D AndroidRuntime: CheckJNI is OFF
,09-13 14:18:41.676  6894  6894 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 14:18:41.745   861  2375 I ActivityManager: Process com.android.gallery3d (pid 6573) has died
,09-13 14:18:41.750   861   992 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
09-13 14:18:41.750   861   992 I ActivityManager: Killing 6442:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
09-13 14:18:41.799   861  2355 I WindowState: WIN DEATH: Window{18ea4de0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 14:18:41.805   861  2355 D InputDispatcher: Focus left window: Window{18ea4de0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 14:18:41.805   861  2355 D InputDispatcher: Window went away: Window{18ea4de0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 14:18:41.827   861  1063 W PackageSettings: Skipping PackageSetting{1586e0bb com.example.hello/10317} due to missing metadata
,09-13 14:18:41.952   490   490 D charger_monitor: init target 500000
,09-13 14:18:41.957   490   490 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-13 14:18:41.961   861   992 I ActivityManager:   Force finishing activity ActivityRecord{1e87853 u0 com.test.thalitest/.MainActivity t259}
09-13 14:18:41.974  1755  1755 D DSDPConnection: Display #0 changed.
,09-13 14:18:41.989   861  1978 W ActivityManager: Spurious death for ProcessRecord{103a6738 6442:com.test.thalitest/u0a30}, curProc for 6442: null
,09-13 14:18:41.993   861  1063 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
09-13 14:18:41.996   861  1063 I ActivityManager:   Force finishing activity ActivityRecord{1e87853 u0 com.test.thalitest/.MainActivity t259 f}
09-13 14:18:41.996   861  1063 W ActivityManager: Duplicate finish request for ActivityRecord{1e87853 u0 com.test.thalitest/.MainActivity t259 f}
09-13 14:18:42.046   861   861 V ActivityManager: Display changed displayId=0
,09-13 14:18:42.057  1377  1377 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-13 14:18:42.065   861  1291 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 14:18:42.071  1844  1844 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
09-13 14:18:42.072  1736  2491 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 14:18:42.090  1808  1808 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-13 14:18:42.093  3664  3664 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-13 14:18:42.094  3664  3664 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-13 14:18:42.094  3664  3664 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-13 14:18:42.094  3664  3664 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
09-13 14:18:42.094  3664  3664 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 14:18:42.094  3664  3664 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 14:18:42.094  3664  3664 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 14:18:42.094  3664  3664 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
09-13 14:18:42.094  3664  3664 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 14:18:42.094  3664  3664 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 14:18:42.094  3664  3664 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
09-13 14:18:42.094  3664  3664 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
09-13 14:18:42.096  1959  1959 I art     : Explicit concurrent mark sweep GC freed 2865(259KB) AllocSpace objects, 2(48KB) LOS objects, 40% free, 12MB/20MB, paused 1.712ms total 93.823ms
09-13 14:18:42.098  1844  1844 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-13 14:18:42.098  1844  1844 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-13 14:18:42.103  1808  1992 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-13 14:18:42.104  1808  1992 D LEDHandler: Battery Level Remaining: 100%
09-13 14:18:42.104  1808  1992 D LEDHandler: Battery Temp: 310, mChargingStatus=5, mChargingStop=false
09-13 14:18:42.106  2041  3542 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 14:18:42.129  3383  3383 I art     : Explicit concurrent mark sweep GC freed 3118(151KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 16MB/21MB, paused 1.031ms total 129.343ms
,09-13 14:18:42.155   861   992 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6941 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-13 14:18:42.158  1881  1881 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
09-13 14:18:42.198  1377  1377 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,09-13 14:18:42.201  1881  1881 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
09-13 14:18:42.216  1881  1881 I [LGHome]EVENT: [LauncherModel.java:1358:startLoader()]startLoader isLaunching=true
,09-13 14:18:42.236  1881  2026 I [LGHome]Launcher.Model: [LauncherModel.java:1475:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,09-13 14:18:42.249  1881  1881 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,09-13 14:18:42.251  1881  1881 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
09-13 14:18:42.251  1881  1881 I Activity: Activity.onPostResume() called 
09-13 14:18:42.263   861   861 W art     : Suspending all threads took: 5.138ms
,09-13 14:18:42.275  1881  1881 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
,09-13 14:18:42.277  1377  1506 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 14:18:42.277  1377  1506 D KeyguardModel: createShortcutInfo...
09-13 14:18:42.281  1377  1506 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 14:18:42.281  1377  1506 D KeyguardModel: createShortcutInfo...
09-13 14:18:42.284  1377  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 14:18:42.286  1377  1506 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,09-13 14:18:42.289  1377  1506 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 14:18:42.289  1377  1506 D KeyguardModel: createShortcutInfo...
09-13 14:18:42.295   861   861 I art     : Explicit concurrent mark sweep GC freed 43043(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 15.410ms total 247.321ms
09-13 14:18:42.295  1377  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 14:18:42.296   861  1063 I art     : WaitForGcToComplete blocked for 97.990ms for cause Explicit
09-13 14:18:42.296  1377  1506 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 14:18:42.300  6941  6941 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 14:18:42.301  6941  6941 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 14:18:42.313  6941  6941 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-13 14:18:42.315  1881  6960 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
09-13 14:18:42.316  1377  1506 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 14:18:42.316  1377  1506 D KeyguardModel: createShortcutInfo...
09-13 14:18:42.318  1377  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 14:18:42.318  1377  1506 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 14:18:42.322  1377  1506 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 14:18:42.322  1377  1506 D KeyguardModel: createShortcutInfo...
09-13 14:18:42.331  1377  1377 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-13 14:18:42.331  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-13 14:18:42.331  1377  1377 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-13 14:18:42.331  1377  1377 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-13 14:18:42.331  1377  1377 I [SystemUI]LGPowerUI: On Skip Timer : true
09-13 14:18:42.331  1377  1377 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 310
09-13 14:18:42.332  1377  1377 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,09-13 14:18:42.332  1377  1377 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 310
09-13 14:18:42.335  1377  1377 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-13 14:18:42.336  1377  1377 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-13 14:18:42.337  1377  1377 D KeyguardModel: handleShortcutListChanged...
09-13 14:18:42.345   861  1056 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
09-13 14:18:42.345   861  1056 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,09-13 14:18:42.346  1377  1377 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
09-13 14:18:42.346  1377  1377 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
09-13 14:18:42.346  1377  1377 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
09-13 14:18:42.346  1377  1377 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
09-13 14:18:42.350   861  1056 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
09-13 14:18:42.350   861  1056 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
09-13 14:18:42.350   861  1056 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-13 14:18:42.350   861  1056 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@5f53ae,  pkg=WindowManager.LayoutParams
09-13 14:18:42.350  1377  1506 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 14:18:42.350  1377  1506 D KeyguardModel: createShortcutInfo...
09-13 14:18:42.350   861  1056 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
09-13 14:18:42.351   861  1298 D InputDispatcher: Focus entered window: Window{2476a87c u0 com.lge.launcher2/com.lge.launcher2.Launcher}
09-13 14:18:42.357  1377  1506 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 14:18:42.359  1377  1506 D KeyguardModel: createShortcutInfo...
,09-13 14:18:42.370  1881  1881 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 14:18:42.371  1881  1881 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 14:18:42.371  1881  1881 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
09-13 14:18:42.372  1377  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 14:18:42.372  1377  1506 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,09-13 14:18:42.375  1377  1506 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 14:18:42.375  1377  1506 D KeyguardModel: createShortcutInfo...
09-13 14:18:42.379  1377  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 14:18:42.379  1377  1506 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 14:18:42.381  1377  1506 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 14:18:42.381  1377  1506 D KeyguardModel: createShortcutInfo...
09-13 14:18:42.382  1881  1881 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
09-13 14:18:42.383  1377  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 14:18:42.383  1377  1506 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 14:18:42.385  1377  1506 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 14:18:42.385  1377  1506 D KeyguardModel: createShortcutInfo...
,09-13 14:18:42.389  1881  1881 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
09-13 14:18:42.390  1881  1881 I PhoneWindow: [setNavigationBarColor] color=0x 0
09-13 14:18:42.392  1377  1377 D KeyguardModel: handleShortcutListChanged...
09-13 14:18:42.395   861   861 D administrator: Handling package changes for user 0
09-13 14:18:42.487   861  1854 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,09-13 14:18:42.488   861  1854 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6442 uid 10030
09-13 14:18:42.549  1881  1881 I [LGHome]Launcher.Model: [LauncherModel.java:2270:run()] LauncherModel bind current page shortcut
,09-13 14:18:42.550   861   861 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-13 14:18:42.550   861   861 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 14:18:42.554   861   861 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 14:18:42.559  1881  1881 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-13 14:18:42.563   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 14:18:42.563   861  1355 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
09-13 14:18:42.563   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 14:18:42.563   861  1319 D WifiController: battery changed pluggedType: 2
09-13 14:18:42.573   861  1058 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{8c452b7 u0 com.lge.launcher2/.Launcher t258} time:162838
09-13 14:18:42.587  1881  1881 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-13 14:18:42.589  1881  1881 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,09-13 14:18:42.593  1881  1881 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-13 14:18:42.595  1881  1881 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-13 14:18:42.626   861  1063 I art     : Explicit concurrent mark sweep GC freed 12095(1175KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.359ms total 329.740ms
,09-13 14:18:42.630  1881  1881 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-13 14:18:42.635  6941  6941 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
09-13 14:18:42.657  6941  6941 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,09-13 14:18:42.684  1881  1881 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,09-13 14:18:42.685  1881  1881 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
09-13 14:18:42.685  1881  1881 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-13 14:18:42.731  1881  1881 W Resources: Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
09-13 14:18:42.735  1881  1881 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
09-13 14:18:42.736  1881  1881 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
09-13 14:18:42.737  1881  1881 W Resources: Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
,09-13 14:18:42.741  1881  1881 W Resources: Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
09-13 14:18:42.751  6894  6894 D AndroidRuntime: Shutting down VM
,09-13 14:18:42.753  1881  1881 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
09-13 14:18:42.754  1881  1881 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
09-13 14:18:42.757  1881  1881 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
09-13 14:18:42.758  1881  1881 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
09-13 14:18:42.758  1881  1881 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
,09-13 14:18:42.769  1881  1881 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
09-13 14:18:42.780  1881  1881 W Resources: Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,09-13 14:18:42.791  1790  1790 D LCardEmulationManager: getHceAppCount hostAppNum : 0
09-13 14:18:42.791  1790  1790 D LCardEmulationManager: getDefaultRoute
09-13 14:18:42.811   861   991 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 14:18:42.909  1881  1881 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,09-13 14:18:42.944  6941  6941 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,09-13 14:18:42.952   861   991 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-13 14:18:42.988  6550  6550 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-13 14:18:43.000  1881  1881 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-13 14:18:43.000  1881  1881 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
,09-13 14:18:43.001  1881  1881 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
,09-13 14:18:43.001  1881  1881 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-13 14:18:43.014  1881  1881 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,09-13 14:18:43.016  1881  1881 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
09-13 14:18:43.017  1881  1881 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-13 14:18:43.019  1881  1881 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-13 14:18:43.023  1881  1881 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-13 14:18:43.025  1881  1881 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
09-13 14:18:43.025   861  1063 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6971 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-13 14:18:43.026  1881  1881 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,09-13 14:18:43.028  1881  1881 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
,09-13 14:18:43.031  1881  1881 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
09-13 14:18:43.032  1633  1633 E b       : Unable to connect to the editor to retrieve text... will retry later
09-13 14:18:43.052  1881  1881 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
09-13 14:18:43.053  1881  1881 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-13 14:18:43.053  1881  1881 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,09-13 14:18:43.054  1881  2224 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-13 14:18:43.055  1881  2224 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-13 14:18:43.080   861  1869 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6988 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,09-13 14:18:43.149  1881  1881 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,09-13 14:18:43.159   295   351 I ThermalEngine: Sensor:pa_therm0:33000 mC
09-13 14:18:43.183  1881  1881 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null

```
