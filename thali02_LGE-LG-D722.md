#### Test 503880190437b9b_thali02_LGE-LG-D722 Logs


```--------- beginning of system
11-17 18:01:19.350   833  2201 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=4975 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
--------- beginning of main
11-17 18:01:19.371   306   306 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 22.079ms
11-17 18:01:19.396   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 21.377ms
11-17 18:01:19.419   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 304us total 21.912ms
11-17 18:01:19.527  4975  4975 D PhoneMonitor: Register our PhoneStateListener
11-17 18:01:19.546   833  2201 I ActivityManager: Killing 4673:com.lge.appbox.client/u0a11 (adj 15): empty #11
,11-17 18:01:19.576   833  2156 W libprocessgroup: failed to open /acct/uid_10011/pid_4673/cgroup.procs: No such file or directory
11-17 18:01:19.585  4975  4975 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
11-17 18:01:19.585  3978  3978 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-17 18:01:19.589  3978  3978 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-17 18:01:19.594  4975  4975 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
11-17 18:01:19.595  3978  4999 I Kids    : [KidAccountFixer] No network connection
11-17 18:01:19.597  2015  2903 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
11-17 18:01:19.599  4975  4975 D TelephonyAutoProfiling: [parse] Load xml
11-17 18:01:19.607  4975  4975 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
11-17 18:01:19.607  4975  4975 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
11-17 18:01:19.616  4975  4975 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
11-17 18:01:19.706   833  1059 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5006 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
11-17 18:01:19.956  5000  5000 D AndroidRuntime: 
11-17 18:01:19.956  5000  5000 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
11-17 18:01:19.965  5000  5000 D AndroidRuntime: CheckJNI is OFF
11-17 18:01:20.003   833   852 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
11-17 18:01:20.101  5006  5037 I Gmail   : getAccountsCursor
11-17 18:01:20.116  2015  2015 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:01:20.134  5006  5006 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
11-17 18:01:20.251   292   354 I ThermalEngine: Sensor:pa_therm0:32000 mC
11-17 18:01:20.252   833  2156 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
11-17 18:01:20.275  5006  5047 I Gmail   : getAccountsCursor
11-17 18:01:20.288  5006  5045 E Gmail   : Error finding the version of the Email provider.....
11-17 18:01:20.288  5006  5045 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
11-17 18:01:20.288  5006  5045 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
11-17 18:01:20.288  5006  5045 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
11-17 18:01:20.288  5006  5045 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
11-17 18:01:20.288  5006  5045 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:01:20.288  5006  5045 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:20.288  5006  5045 E Gmail   : 	at android.os.Looper.loop(Looper.java:135)
11-17 18:01:20.288  5006  5045 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:01:20.288  5006  5045 W EmailMigration: We do not support migrating this version of the Email provider.
11-17 18:01:20.309   833  1635 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5049 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
11-17 18:01:20.349   833  1059 I ActivityManager: Killing 4690:com.android.gallery3d/u0a23 (adj 15): empty #11
11-17 18:01:20.351  2015  2015 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:01:20.387  5000  5000 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-17 18:01:20.416   833  1635 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
11-17 18:01:20.416   833   852 W libprocessgroup: failed to open /acct/uid_10023/pid_4690/cgroup.procs: No such file or directory
11-17 18:01:20.422   833  2205 I ActivityManager: START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
11-17 18:01:20.424  5006  5075 I Gmail   : Observing account changes for notifications
11-17 18:01:20.453  5049  5049 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
11-17 18:01:20.464   833  2205 D ActivityManager: setTaskToReturnTo : TaskRecord{167ac84e #217 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
11-17 18:01:20.465   833  2205 D ActivityManager: setTaskToReturnTo : TaskRecord{167ac84e #217 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
11-17 18:01:20.473  4727  4738 E UEI.SmartControl: file observer is disposed!
11-17 18:01:20.478   833  2205 D WindowStateEx: AppWindowTokenEx init.. 
11-17 18:01:20.493   833   999 D ContextHelper: convertTheme. context->name=com.example.hello themeResourceId=16973833
11-17 18:01:20.505   833  2205 D InputDispatcher: Focus left window: Window{30750788 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
11-17 18:01:20.506  5000  5000 D AndroidRuntime: Shutting down VM
11-17 18:01:20.508   833  1909 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
11-17 18:01:20.514  2015  2015 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:01:20.515  1875  1875 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
11-17 18:01:20.556   833   999 D SplitWindow: check instance of lgWin Window{337f6b67 u0 Starting com.example.hello}
11-17 18:01:20.593   833  1059 I ActivityManager: Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5079 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
11-17 18:01:20.636  1875  1875 I [LGHome]EVENT: [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
11-17 18:01:20.675  1875  1875 I [LGHome]EVENT: [Launcher.java:5214:onStop()]onStop
11-17 18:01:20.702   833   998 D BluetoothManagerService: Message: 20
11-17 18:01:20.702   833   998 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3004605f:true
11-17 18:01:20.716   833   853 I WindowStateAnimator: Starting window displayed
11-17 18:01:20.722   833   996 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
11-17 18:01:20.729   833   996 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
11-17 18:01:20.729   833   996 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
11-17 18:01:20.729   833   996 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:01:20.729   833   996 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@4c213f7,  pkg=WindowManager.LayoutParams
11-17 18:01:20.729   833   996 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,11-17 18:01:20.735  1371  1371 D PhoneStatusBar: setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
11-17 18:01:20.736  1937  1937 I HotwordDetector: Closing mic
11-17 18:01:20.742  1937  2531 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@f69b9a4
11-17 18:01:20.742  1937  2531 V AudioRecord: stop()
11-17 18:01:20.742  1937  2531 D AudioRecord: AudioRecord->stop()
11-17 18:01:20.744   282  1603 V AudioFlinger: RecordHandle::stop()
11-17 18:01:20.744   282  1603 V AudioFlinger: RecordThread::stop
11-17 18:01:20.748  5049  5049 D BluetoothAdapter: 240237269: getState() :  mService = null. Returning STATE_OFF
11-17 18:01:20.748  5049  5049 D BluetoothAdapter: 240237269: getState() :  mService = null. Returning STATE_OFF
11-17 18:01:20.750  1371  1371 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
11-17 18:01:20.750  1371  1371 I [SystemUI]NavigationThemeResource:  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
11-17 18:01:20.750  1371  1371 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
11-17 18:01:20.752  1371  1371 D BarTransitions: draw background and invalidate : color = 15000000
11-17 18:01:20.754  1371  1371 D BarTransitions: draw background and invalidate : color = 15141414
11-17 18:01:20.764   282  1603 V AudioFlinger: Record stopped OK
11-17 18:01:20.766   282  1603 V AudioPolicyManager: stopInput() input 17
11-17 18:01:20.767   282  1603 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
11-17 18:01:20.768   282  1603 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
11-17 18:01:20.768   282  1061 V AudioPolicyService: AudioCommandThread() waking up
11-17 18:01:20.768   282  1061 V AudioPolicyService: AudioCommandThread() processing release audio patch
11-17 18:01:20.768   282  1061 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
11-17 18:01:20.768   282  1061 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
11-17 18:01:20.768   282  1061 V AudioFlinger: ThreadBase::setParameters() routing=0
11-17 18:01:20.768   282  1061 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
11-17 18:01:20.769   282  2574 V AudioFlinger: processConfigEvents_l() remaining events 1
11-17 18:01:20.769   282  2574 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3c4d000
11-17 18:01:20.771   282  2574 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
11-17 18:01:20.796  5079  5079 D ContextHelper: convertTheme. context->name=com.example.hello themeResourceId=16973833
11-17 18:01:20.812   282  2574 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
11-17 18:01:20.812   282  2574 V audio_hw_primary: disable_audio_route: enter: usecase(7)
11-17 18:01:20.812   282  2574 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
11-17 18:01:20.812   282  2574 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-17 18:01:20.813   282  2574 V audio_hw_primary: disable_audio_route: exit
11-17 18:01:20.814   282  2574 E audio_hw_primary: disable_snd_device: enter 144
11-17 18:01:20.814   282  2574 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
11-17 18:01:20.814   282  2574 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
11-17 18:01:20.814  5006  5078 I Gmail   : notifyAccountChanged
11-17 18:01:20.817   282  2574 V audio_hw_primary: stop_input_stream: exit: status(0)
11-17 18:01:20.817   282  2574 V audio_hw_primary: in_standby: exit:  status(0)
11-17 18:01:20.817   282  2574 V AudioFlinger: RecordThread: loop stopping
11-17 18:01:20.817   282  1061 V AudioPolicyService: AudioCommandThread() going to sleep
11-17 18:01:20.817   282  1603 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
11-17 18:01:20.817   282  1603 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
11-17 18:01:20.818   282  1603 V AudioPolicyService: AudioCommandThread() adding update audio patch list
11-17 18:01:20.818   282  1603 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
11-17 18:01:20.818   282  1062 V AudioPolicyService: AudioCommandThread() waking up
11-17 18:01:20.818   282  1062 V AudioPolicyService: AudioCommandThread() processing update audio patch list
11-17 18:01:20.818   282  1062 V AudioPolicyService: AudioCommandThread() going to sleep
11-17 18:01:20.819   282  1603 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
11-17 18:01:20.819   282  1603 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
11-17 18:01:20.819   282  1061 V AudioPolicyService: AudioCommandThread() waking up
11-17 18:01:20.819   282  1061 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
11-17 18:01:20.819   282  1061 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 282
11-17 18:01:20.819   282  1061 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
11-17 18:01:20.819   282  1061 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
11-17 18:01:20.819   282  2574 V AudioFlinger: RecordThread: loop starting
11-17 18:01:20.819   282  2574 V AudioFlinger: processConfigEvents_l() remaining events 1
11-17 18:01:20.819   282  2574 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
11-17 18:01:20.820   282  2574 V audio_hw_primary: in_set_parameters: exit: status(0)
11-17 18:01:20.820   282  2574 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3c4d000
11-17 18:01:20.820   282  2574 V AudioFlinger: RecordThread: loop stopping
11-17 18:01:20.820   282  1061 V AudioPolicyService: AudioCommandThread() going to sleep
11-17 18:01:20.826  1937  2531 V AudioRecord: stop()
11-17 18:01:20.830  5006  5078 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
11-17 18:01:20.833  5006  5097 I Gmail   : getAccountsCursor
11-17 18:01:20.834  1937  2531 V AudioRecord: stop()
11-17 18:01:20.834  1937  2531 V AudioRecord: stop()
11-17 18:01:20.840  2015  2015 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:01:20.844   282  1602 V AudioFlinger: RecordHandle::stop()
11-17 18:01:20.844   282  1602 V AudioFlinger: RecordThread::stop
11-17 18:01:20.844   282  1602 V AudioPolicyManager: releaseInput() 17
11-17 18:01:20.844   282  1602 V AudioPolicyManager: closeInput(17)
11-17 18:01:20.844   282  1602 V AudioFlinger: closeInput() 17
11-17 18:01:20.844   282  1602 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
11-17 18:01:20.844  1937  1971 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
11-17 18:01:20.845   833  1898 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
11-17 18:01:20.845   282  1602 V AudioFlinger: ThreadBase::exit
11-17 18:01:20.845   282  2574 V AudioFlinger: RecordThread: loop starting
11-17 18:01:20.845  1371  1399 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
11-17 18:01:20.845  3114  3130 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
11-17 18:01:20.845   282  2574 V AudioFlinger: RecordThread 0xb3c4d000 exiting
11-17 18:01:20.846   282  1602 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546dd40)
11-17 18:01:20.846   282  1602 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
11-17 18:01:20.846   282  1602 V audio_hw_primary: in_standby: exit:  status(0)
11-17 18:01:20.846  1748  2677 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
11-17 18:01:20.847  2702  3718 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
11-17 18:01:20.847   282  1602 V AudioPolicyService: AudioCommandThread() adding update audio port list
11-17 18:01:20.847   282  1602 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
11-17 18:01:20.847   282  1602 V AudioPolicyManager: releaseInput() exit
11-17 18:01:20.847   282  1062 V AudioPolicyService: AudioCommandThread() waking up
11-17 18:01:20.847   282  1602 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
11-17 18:01:20.847   282  1062 V AudioPolicyService: AudioCommandThread() processing update audio port list
11-17 18:01:20.847   282  1602 V AudioFlinger: removeClient_l() pid 1937, calling pid 282
11-17 18:01:20.847   282  1062 V AudioPolicyService: AudioCommandThread() going to sleep
11-17 18:01:20.847   282  1321 V AudioFlinger: releasing 16 from 1937 for -1
11-17 18:01:20.847   282  1321 V AudioFlinger:  decremented refcount to 0
11-17 18:01:20.847   282  1321 V AudioFlinger: purging stale effects
11-17 18:01:20.851  1937  2541 I HotwordRecognitionRnr: Stopping hotword detection.
11-17 18:01:20.856  1937  2562 I HotwordRecognitionRnr: Hotword detection finished
11-17 18:01:20.861  2015  2015 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:01:20.863  2015  2015 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:01:20.873  5006  5078 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
11-17 18:01:20.893  5006  5078 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
11-17 18:01:20.907  5006  5078 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
11-17 18:01:20.913  5049  5049 V LGMDMManager: Create singleton instance
11-17 18:01:20.936  5079  5079 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
11-17 18:01:21.016  5049  5049 I AudioManager: getMode name:com.lge.qremote
11-17 18:01:21.018  5079  5079 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9349-9353)
11-17 18:01:21.018  5079  5079 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:01:21.033  4727  4751 D UEI.SmartControl: -----IControl: 11
11-17 18:01:21.034  4727  4751 D UEI.SmartControl: File observer start...
11-17 18:01:21.034  4727  4751 E UEI.SmartControl: IR Port is disabled: false
11-17 18:01:21.035  4727  4751 D UEI.SmartControl: Starting file observer...
11-17 18:01:21.036  4727  4751 D UEI.SmartControl: Caller: com.lge.qremote
11-17 18:01:21.039  4727  4751 D UEI.SmartControl: ------------ IControl registerCallback...
11-17 18:01:21.040  4727  4751 I UEI.SmartControl: Registering callback...
11-17 18:01:21.041  4727  4742 D UEI.SmartControl: -----IControl: 19
11-17 18:01:21.042  4727  4742 D UEI.SmartControl: Caller: com.lge.qremote
11-17 18:01:21.043  4727  4742 I UEI.SmartControl: Registering Services Ready callback...
11-17 18:01:21.043  4727  4742 I UEI.SmartControl: Notify client services are ready...
11-17 18:01:21.047  4727  4751 D UEI.SmartControl: -----IControl: 8
11-17 18:01:21.047  4727  4751 D UEI.SmartControl: Caller: com.lge.qremote
11-17 18:01:21.059  5079  5079 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1df2d619}
11-17 18:01:21.061  5079  5079 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:01:21.061  5049  5049 I AudioManager: getMode name:com.lge.qremote
11-17 18:01:21.067  5079  5079 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-17 18:01:21.087  5079  5079 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-17 18:01:21.088  5079  5079 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:01:21.089  5079  5079 E SysUtils: ApplicationContext is null in ApplicationStatus
11-17 18:01:21.114  5079  5103 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
11-17 18:01:21.118   833  1059 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5104 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
11-17 18:01:21.126   833  1059 I ActivityManager: Killing 4709:com.android.contacts/u0a18 (adj 15): empty #11
11-17 18:01:21.129  5006  5037 I Gmail   : getAccountsCursor
11-17 18:01:21.150  5079  5079 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
11-17 18:01:21.160  5079  5079 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-17 18:01:21.161  5079  5079 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-17 18:01:21.164  5079  5079 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
11-17 18:01:21.164  5079  5079 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
11-17 18:01:21.164  5079  5079 I Adreno-EGL: Build Date: 03/02/15 Mon
11-17 18:01:21.164  5079  5079 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
11-17 18:01:21.164  5079  5079 I Adreno-EGL: Remote Branch: 
11-17 18:01:21.164  5079  5079 I Adreno-EGL: Local Patches: 
11-17 18:01:21.164  5079  5079 I Adreno-EGL: Reconstruct Branch: 
11-17 18:01:21.193   833  1782 W libprocessgroup: failed to open /acct/uid_10018/pid_4709/cgroup.procs: No such file or directory
11-17 18:01:21.194  2015  2015 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:01:21.228  5104  5104 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
11-17 18:01:21.297   282  1602 V AudioPolicyService: registerClient() client 0xb3c3cb00, uid 10030
11-17 18:01:21.305   833   998 D BluetoothManagerService: Message: 20
11-17 18:01:21.305   833   998 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d157b5b:true
11-17 18:01:21.307  5079  5132 D BluetoothAdapter: 240237269: getState() :  mService = null. Returning STATE_OFF
11-17 18:01:21.354  4727  4804 D UEI.SmartControl: Internal timer expired: 3
11-17 18:01:21.510  5079  5079 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:01:21.525  5079  5079 W AwContents: onDetachedFromWindow called when already detached. Ignoring
11-17 18:01:21.547  5079  5079 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
11-17 18:01:21.556  5079  5079 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:01:21.556  5079  5079 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:01:21.582  5104  5145 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
11-17 18:01:21.586  5104  5145 I Babel_SMS: MmsConfig.loadMmsSettings
11-17 18:01:21.590  5104  5145 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
11-17 18:01:21.591  5104  5145 I Babel_SMS: MmsConfig.loadFromDatabase
11-17 18:01:21.611  5079  5079 I Activity: Activity.onPostResume() called 
11-17 18:01:21.624  5079  5151 D OpenGLRenderer: Render dirty regions requested: true
11-17 18:01:21.625  5079  5151 I OpenGLRenderer: Initialized EGL, version 1.4
11-17 18:01:21.633  5079  5151 D OpenGLRenderer: Enabling debug mode 0
11-17 18:01:21.642  5104  5145 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
11-17 18:01:21.642  5104  5145 I Babel_SMS: MmsConfig.loadFromResources
11-17 18:01:21.644  5104  5145 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
11-17 18:01:21.644  5104  5145 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
11-17 18:01:21.653  5079  5079 D Atlas   : Validating map...
11-17 18:01:21.659   833  1811 D SplitWindow: check instance of lgWin Window{3953d5e6 u0 com.example.hello/com.example.hello.MainActivity}
11-17 18:01:21.660  5104  5104 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
11-17 18:01:21.660  5104  5104 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
11-17 18:01:21.660  5104  5104 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
11-17 18:01:21.660  5104  5104 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
11-17 18:01:21.660  5104  5104 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
11-17 18:01:21.660  5104  5104 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
11-17 18:01:21.660  5104  5104 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
11-17 18:01:21.660  5104  5104 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
11-17 18:01:21.660  5104  5104 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
11-17 18:01:21.660  5104  5104 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
11-17 18:01:21.660  5104  5104 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
11-17 18:01:21.660  5104  5104 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
11-17 18:01:21.660  5104  5104 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
11-17 18:01:21.660  5104  5104 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
11-17 18:01:21.660  5104  5104 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
11-17 18:01:21.660  5104  5104 D SensorManager: found sensor: Motion Accel, handle=46
11-17 18:01:21.677  5079  5130 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
11-17 18:01:21.704   833  1058 D InputDispatcher: Focus entered window: Window{3953d5e6 u0 com.example.hello/com.example.hello.MainActivity}
11-17 18:01:21.729  5104  5104 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-17 18:01:21.733  5104  5104 I Babel_Crash: startup - clean
11-17 18:01:21.764   833  1059 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
11-17 18:01:21.772   833   999 I ActivityManager: Displayed com.example.hello/.MainActivity: +1s229ms
11-17 18:01:21.774   833   999 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{35a33d6f u0 com.example.hello/.MainActivity t217} time:70107
11-17 18:01:21.780  5079  5079 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3c380345 time:70115
11-17 18:01:21.799  5104  5153 I Babel   : deleted: false for 0
11-17 18:01:21.824  5104  5122 I art     : CheckpointMarkThreadRoots callback created = 0xb042d930
11-17 18:01:21.882  5104  5122 I art     : CheckpointMarkThreadRoots callback created = 0xb042d910
11-17 18:01:21.885  5079  5079 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5079
11-17 18:01:21.919  5079  5079 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
11-17 18:01:21.980  5049  5049 I AudioManager: getMode name:com.lge.qremote
11-17 18:01:22.003  5104  5104 W AudioCapabilities: Unsupported mime audio/x-lg-flac
11-17 18:01:22.007  5104  5104 W AudioCapabilities: Unsupported mime audio/adpcm
11-17 18:01:22.008  5104  5104 W AudioCapabilities: Unsupported mime audio/g726
11-17 18:01:22.010  5104  5104 W AudioCapabilities: Unsupported mime audio/x-ms-wma
11-17 18:01:22.011  5104  5104 W AudioCapabilities: Unsupported mime audio/wma-voice
11-17 18:01:22.013  5104  5104 W VideoCapabilities: Unsupported mime video/mjpg
11-17 18:01:22.019  5104  5104 W VideoCapabilities: Unsupported mime video/theora
11-17 18:01:22.050  5104  5104 W AudioCapabilities: Unsupported mime audio/evrc
11-17 18:01:22.052  5104  5104 W AudioCapabilities: Unsupported mime audio/qcelp
11-17 18:01:22.056  5104  5104 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
11-17 18:01:22.063  5104  5104 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
11-17 18:01:22.065  5104  5104 W AudioCapabilities: Unsupported mime audio/qcelp
11-17 18:01:22.066  5104  5104 W AudioCapabilities: Unsupported mime audio/evrc
11-17 18:01:22.080  5079  5079 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
11-17 18:01:22.083  5104  5104 W VideoCapabilities: Unsupported mime video/mp4v-esdp
11-17 18:01:22.099  5104  5104 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
11-17 18:01:22.108  5104  5104 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
11-17 18:01:22.110  5104  5104 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,11-17 18:01:22.114  5104  5104 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
11-17 18:01:22.116  5079  5136 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
11-17 18:01:22.125  5104  5104 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,11-17 18:01:22.223  5104  5104 I vclib   : onServiceConnected
,11-17 18:01:22.227  5104  5104 W Babel   : Attempted to change video mute state without an active call.
11-17 18:01:22.250  5104  5104 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
11-17 18:01:22.250  5104  5104 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,11-17 18:01:22.341  5104  5104 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,11-17 18:01:22.459  5104  5104 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,11-17 18:01:22.459  5104  5104 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-17 18:01:22.489  5104  5104 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,11-17 18:01:22.532  5104  5167 I NotificationManager: com.google.android.talk: cancel(8) by com.google.android.talk
,11-17 18:01:22.574   833  1829 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5170 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,11-17 18:01:22.603  5079  5155 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426120704
11-17 18:01:22.604  5079  5155 D JX-Cordova: jxcore cordova android initializing
,11-17 18:01:22.680  5170  5170 I AppUp4:AppBoxCP: onCreate
11-17 18:01:22.680  5170  5170 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,11-17 18:01:22.685  5079  5079 W jxcore-log: Initializing JXcore engine
11-17 18:01:22.685  5079  5079 W jxcore-log: JXcore engine is ready
11-17 18:01:22.691  5170  5170 I AppUp4:DB:  setFingerPrint start
11-17 18:01:22.691  5170  5170 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
11-17 18:01:22.694  5079  5079 W jxcore-log: Starting JXcore engine
,11-17 18:01:22.701  5170  5170 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
11-17 18:01:22.701  5170  5170 I AppUp4:DB:  SDK version = 0
11-17 18:01:22.701  5170  5170 I AppUp4:DB:  beforefinger == newfinger no write in DB
11-17 18:01:22.702  5170  5170 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
11-17 18:01:22.720  5170  5170 I AppUp4:CustModeStarterReceiver: onReceive
11-17 18:01:22.720  5170  5170 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,11-17 18:01:22.725  5170  5170 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1431a163
11-17 18:01:22.725  5170  5170 D AppUp4:CustFacade: isCustomizationCompleted : false
11-17 18:01:22.730  5170  5170 D AppUp4:CustFacade: isSimDevice : true
11-17 18:01:22.731  5170  5170 D AppUp4:CustModeStarterReceiver: begin check event
11-17 18:01:22.731  5170  5170 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
11-17 18:01:22.733   833  1867 I ActivityManager: Killing 4759:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,11-17 18:01:22.777  5079  5079 W m.example.hello: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7680]" dev="sockfs" ino=7680 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-17 18:01:22.777  5079  5079 W m.example.hello: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-17 18:01:22.777  5079  5079 W m.example.hello: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5779]" dev="sockfs" ino=5779 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-17 18:01:22.777  5079  5079 W m.example.hello: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
11-17 18:01:22.777  5079  5079 W m.example.hello: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
11-17 18:01:22.777  5079  5079 W m.example.hello: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[19089]" dev="sockfs" ino=19089 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-17 18:01:22.836   833  1909 W libprocessgroup: failed to open /acct/uid_10069/pid_4759/cgroup.procs: No such file or directory
,11-17 18:01:22.884   833  2205 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5189 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,11-17 18:01:22.963  5079  5079 W jxcore-log: Platform android
11-17 18:01:22.963  5079  5079 W jxcore-log: 
,11-17 18:01:22.963  5079  5079 W jxcore-log: Process ARCH arm
11-17 18:01:22.963  5079  5079 W jxcore-log: 
11-17 18:01:22.963  5189  5189 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:01:22.963  5189  5189 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
11-17 18:01:22.964  5189  5189 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
11-17 18:01:23.030  5079  5079 I jxcore-log: JXcore Cordova bridge is ready!
11-17 18:01:23.030  5079  5079 I jxcore-log: 
,11-17 18:01:23.031  5079  5079 W jxcore-log: JXcore engine is started
11-17 18:01:23.090  5079  5079 E jxcore-log: >> LGE-LG-D722
11-17 18:01:23.090  5079  5079 E jxcore-log: 
,11-17 18:01:23.092  5079  5079 I jxcore-log: Total memory 906309632
11-17 18:01:23.092  5079  5079 I jxcore-log: 
11-17 18:01:23.093  5079  5079 I jxcore-log: Free memory 20250624
11-17 18:01:23.093  5079  5079 I jxcore-log: 
11-17 18:01:23.093  5079  5079 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:01:23.093  5079  5079 I jxcore-log: 
11-17 18:01:23.093  5079  5079 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:01:23.093  5079  5079 I jxcore-log: 
11-17 18:01:23.101  5079  5079 I jxcore-log: userPath [ 'www' ]
11-17 18:01:23.101  5079  5079 I jxcore-log: 
11-17 18:01:23.103  5079  5079 I jxcore-log: Size 720 1196
11-17 18:01:23.103  5079  5079 I jxcore-log: 
,11-17 18:01:23.105  5079  5079 I jxcore-log: Screen Brightness 255
11-17 18:01:23.105  5079  5079 I jxcore-log: 
11-17 18:01:23.105  5079  5079 E jxcore-log: Dummy Error Log.
11-17 18:01:23.105  5079  5079 E jxcore-log: 
11-17 18:01:23.117  5189  5189 I AppConfig: Total System Memory = 906309632
,11-17 18:01:23.121  5189  5189 I GalleryUtils: Application Heap = 96 MB
11-17 18:01:23.133  5189  5189 I AppConfig: App Tier : NOT_DEF
,11-17 18:01:23.146  5189  5189 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,11-17 18:01:23.223   833  1059 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5211 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,11-17 18:01:23.224   833  1059 I ActivityManager: Killing 4776:com.lge.eula/1000 (adj 15): empty #11
11-17 18:01:23.255   833  1874 W libprocessgroup: failed to open /acct/uid_1000/pid_4776/cgroup.procs: No such file or directory
,11-17 18:01:23.288  5211  5211 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,11-17 18:01:23.290  5211  5211 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
11-17 18:01:23.290  5211  5211 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
11-17 18:01:23.291  5211  5211 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
11-17 18:01:23.292  5211  5211 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
11-17 18:01:23.419  5211  5211 I SystemConfig: BUILD Country: EU
,11-17 18:01:23.421  5211  5211 I SystemConfig: BUILD Operator: OPEN
,11-17 18:01:23.555   833  1874 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5232 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
11-17 18:01:23.556   833  1874 I ActivityManager: Killing 4826:com.google.android.apps.docs/u0a58 (adj 15): empty #11
,11-17 18:01:23.624  5079  5079 I jxcore-log: getBuffer is called!!!!
11-17 18:01:23.624  5079  5079 I jxcore-log: 
,11-17 18:01:23.668   833  1909 W libprocessgroup: failed to open /acct/uid_10058/pid_4826/cgroup.procs: No such file or directory
,11-17 18:01:23.681  5211  5231 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
11-17 18:01:23.682  5211  5231 I SystemConfig: existFile = false
11-17 18:01:23.682  5211  5231 I SystemConfig: canReadFile = false
11-17 18:01:23.682  5211  5231 I SystemConfig: systemFeature RCS result false
11-17 18:01:23.682  5211  5231 D SystemConfig: refreshRcsSupport() :false
,11-17 18:01:23.693   833  1987 I art     : Explicit concurrent mark sweep GC freed 31438(1587KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 3.550ms total 232.320ms
,11-17 18:01:23.710  5232  5232 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,11-17 18:01:23.736  5232  5232 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
11-17 18:01:23.736  5232  5232 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
11-17 18:01:23.736  5232  5232 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
11-17 18:01:23.736  5232  5232 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
11-17 18:01:23.736  5232  5232 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
11-17 18:01:23.737   833  1898 I ActivityManager: Killing 4863:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,11-17 18:01:23.867   833  1837 W libprocessgroup: failed to open /acct/uid_10086/pid_4863/cgroup.procs: No such file or directory
,11-17 18:01:23.876  3978  5260 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
11-17 18:01:23.919   833  1874 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5264 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,11-17 18:01:23.925  3978  5260 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
11-17 18:01:23.957  3978  4035 I Icing   : updateResources: need to parse f{com.google.android.gms}
,11-17 18:01:24.013  5264  5264 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,11-17 18:01:24.096   833  1017 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
11-17 18:01:24.096   833  1017 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
11-17 18:01:24.096   833  1017 D sensors_hal_Time: tsOffsetIs: Apps: 72430880395; DSPS: 2471874; Offset : -3014544754
,11-17 18:01:24.209   833  2156 I ActivityManager: Killing 4896:com.lge.bnr/1000 (adj 15): empty #11
,11-17 18:01:24.235   833  1874 W libprocessgroup: failed to open /acct/uid_1000/pid_4896/cgroup.procs: No such file or directory
,11-17 18:01:24.253  1937  5297 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,11-17 18:01:24.304   833  2205 I ActivityManager: Killing 4975:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,11-17 18:01:24.315  1937  5297 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 63 ms] updated apps [took 63 ms] 
,11-17 18:01:24.338   833  1898 W libprocessgroup: failed to open /acct/uid_10038/pid_4975/cgroup.procs: No such file or directory
,11-17 18:01:24.353  5049  5049 I AudioManager: getMode name:com.lge.qremote
,11-17 18:01:24.360  5049  5049 I AudioManager: getMode name:com.lge.qremote
11-17 18:01:24.364  5049  5049 I AudioManager: getMode name:com.lge.qremote
11-17 18:01:24.401  5049  5049 I AudioManager: getMode name:com.lge.qremote
,11-17 18:01:24.405  5049  5049 I AudioManager: getMode name:com.lge.qremote
11-17 18:01:24.408  5049  5049 I AudioManager: getMode name:com.lge.qremote
11-17 18:01:24.415  5049  5049 I AudioManager: getMode name:com.lge.qremote
,11-17 18:01:24.419  5049  5049 I AudioManager: getMode name:com.lge.qremote
11-17 18:01:25.009  3978  4016 I CheckinService: Done disabling old GoogleServicesFramework version
,11-17 18:01:25.187  5006  5040 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,11-17 18:01:25.196  3978  3978 I GAv4-SVC: Google Analytics 8.3.01 is starting up.
11-17 18:01:25.256   292   354 I ThermalEngine: Sensor:pa_therm0:32000 mC
,11-17 18:01:27.610   833  1837 I ActivityManager: Killing 5104:com.google.android.talk/u0a61 (adj 15): empty #11
,11-17 18:01:27.645   833  1898 W libprocessgroup: failed to open /acct/uid_10061/pid_5104/cgroup.procs: No such file or directory
,11-17 18:01:28.127   833  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,11-17 18:01:28.132   833  1909 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
11-17 18:01:28.133   833   998 D BluetoothManagerService: Message: 2
11-17 18:01:28.170   833  2201 D WifiServiceImplEx: setWifiEnabled: false pid=5079, uid=10030, package= com.example.hello, App Lable : HelloWorld
,11-17 18:01:28.182   833  2201 D WifiService: setWifiEnabled: false pid=5079, uid=10030
,11-17 18:01:28.186  5079  5079 I jxcore-log: ****TEST TOOK:  5104  ms ****
11-17 18:01:28.186  5079  5079 I jxcore-log: 
11-17 18:01:28.186  5079  5079 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:01:28.186  5079  5079 I jxcore-log: 
11-17 18:01:30.262   292   354 I ThermalEngine: Sensor:pa_therm0:32000 mC
,11-17 18:01:30.655  5335  5335 D AndroidRuntime: 
11-17 18:01:30.655  5335  5335 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,11-17 18:01:30.662  5335  5335 D AndroidRuntime: CheckJNI is OFF
11-17 18:01:30.765  3611  3667 D InitAlarmsService: Clearing and rescheduling alarms.
,11-17 18:01:30.807   833  2156 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5353 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,11-17 18:01:30.906  5353  5353 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,11-17 18:01:30.947  5353  5353 D CalendarProvider2: [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2a2e49f4
,11-17 18:01:30.972  5335  5335 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-17 18:01:30.976  1937  1937 I NotificationManager: com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
11-17 18:01:30.981  5353  5353 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
11-17 18:01:30.987  5353  5353 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@1df2d619(com.android.providers.calendar.CalendarProvider2@2a2e49f4)
,11-17 18:01:31.010  5353  5369 D CalendarProvider2: Scheduling check of next Alarm
,11-17 18:01:31.013  5353  5369 D CalendarProvider2: SCHEDULE_ALARM_REMOVE
11-17 18:01:31.021   833  1635 I ActivityManager: Killing 3611:com.android.calendar/u0a13 (adj 15): empty #11
11-17 18:01:31.081   833   877 I ActivityManager: Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
11-17 18:01:31.081   833   877 I ActivityManager: Killing 5079:com.example.hello/u0a30 (adj 0): stop com.example.hello
,11-17 18:01:31.086   833  1057 W PackageSettings: Skipping PackageSetting{3da8c6e6 com.test.thalitest/10316} due to missing metadata
,11-17 18:01:31.109   833  2201 I WindowState: WIN DEATH: Window{3953d5e6 u0 com.example.hello/com.example.hello.MainActivity}
,11-17 18:01:31.114   833  2201 D InputDispatcher: Focus left window: Window{3953d5e6 u0 com.example.hello/com.example.hello.MainActivity}
11-17 18:01:31.115   833  2201 D InputDispatcher: Window went away: Window{3953d5e6 u0 com.example.hello/com.example.hello.MainActivity}
,11-17 18:01:31.188   833   877 W ActivityManager: Force removing ActivityRecord{35a33d6f u0 com.example.hello/.MainActivity t217}: app died, no saved state
,11-17 18:01:31.209   833  1867 W libprocessgroup: failed to open /acct/uid_10013/pid_3611/cgroup.procs: No such file or directory
11-17 18:01:31.220   833  1059 W ActivityManager: Spurious death for ProcessRecord{143eddce 5079:com.example.hello/u0a30}, curProc for 5079: null
,11-17 18:01:31.220   833  1057 I ActivityManager: Force stopping com.example.hello appid=10030 user=0: pkg removed
,11-17 18:01:31.261  1875  1875 I [LGHome]EVENT: [Launcher.java:5203:onStart()]onStart
,11-17 18:01:31.263  1371  1371 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
11-17 18:01:31.283  1838  1838 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,11-17 18:01:31.287  3416  3416 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.example.hello
11-17 18:01:31.288  3416  3416 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
11-17 18:01:31.288  3416  3416 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
11-17 18:01:31.288  3416  3416 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
11-17 18:01:31.288  3416  3416 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 18:01:31.288  3416  3416 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:01:31.288  3416  3416 W System.err: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:01:31.288  3416  3416 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
11-17 18:01:31.288  3416  3416 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:31.288  3416  3416 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:31.288  3416  3416 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
11-17 18:01:31.288  3416  3416 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
11-17 18:01:31.296  1875  1875 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,11-17 18:01:31.302  1728  2371 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-17 18:01:31.311   833  1286 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-17 18:01:31.336   833   877 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5389 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,11-17 18:01:31.359   306   306 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 22.492ms
,11-17 18:01:31.382   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 22.227ms
,11-17 18:01:31.399  1371  1496 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
11-17 18:01:31.399  1371  1496 D KeyguardModel: createShortcutInfo...
,11-17 18:01:31.407  1371  1371 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
11-17 18:01:31.408   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 497us total 25.422ms
11-17 18:01:31.408  1371  1496 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
11-17 18:01:31.408  1371  1496 D KeyguardModel: createShortcutInfo...
11-17 18:01:31.412  1371  1496 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:01:31.413  1875  1875 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,11-17 18:01:31.414  1371  1496 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
11-17 18:01:31.415  1875  1875 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
11-17 18:01:31.415  1875  1875 I Activity: Activity.onPostResume() called 
11-17 18:01:31.419  1371  1496 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
11-17 18:01:31.419  1371  1496 D KeyguardModel: createShortcutInfo...
11-17 18:01:31.431  1371  1496 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,11-17 18:01:31.435   833   996 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
11-17 18:01:31.435   833   996 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
11-17 18:01:31.435   833   996 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
11-17 18:01:31.435   833   996 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:01:31.436   833   996 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@4c213f7,  pkg=WindowManager.LayoutParams
11-17 18:01:31.436   833   996 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
11-17 18:01:31.436  1371  1496 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:01:31.436  1371  1496 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
11-17 18:01:31.438   833  1058 D InputDispatcher: Focus entered window: Window{30750788 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
11-17 18:01:31.438  1371  1496 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
11-17 18:01:31.438  1371  1496 D KeyguardModel: createShortcutInfo...
11-17 18:01:31.448  1875  5404 W [LGHome]LGWallpaperInfo: [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
11-17 18:01:31.448  1875  5404 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,11-17 18:01:31.452  1371  1496 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:01:31.453  1371  1496 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
11-17 18:01:31.453  1371  1496 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
11-17 18:01:31.456  1875  1875 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
11-17 18:01:31.457  1875  1875 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
11-17 18:01:31.458  1875  1875 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
11-17 18:01:31.462  1875  1875 I [LGHome]EVENT: [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,11-17 18:01:31.465  1371  1496 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:01:31.465  1371  1496 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
11-17 18:01:31.467  1875  1875 I PhoneWindow: [setNavigationBarColor] color=0x 0
11-17 18:01:31.468  1371  1496 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
11-17 18:01:31.468  1371  1496 D KeyguardModel: createShortcutInfo...
11-17 18:01:31.492   833  1874 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,11-17 18:01:31.496   833  1874 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5079 uid 10030
11-17 18:01:31.502  1371  1371 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
11-17 18:01:31.502  1371  1371 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
11-17 18:01:31.506  1371  1371 D KeyguardModel: handleShortcutListChanged...
,11-17 18:01:31.511   833   833 I art     : Explicit concurrent mark sweep GC freed 16287(1091KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/34MB, paused 19.912ms total 266.076ms
11-17 18:01:31.511   833  1057 I art     : WaitForGcToComplete blocked for 256.942ms for cause Explicit
11-17 18:01:31.533  1371  1496 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,11-17 18:01:31.533  1371  1496 D KeyguardModel: createShortcutInfo...
11-17 18:01:31.549  5389  5389 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:01:31.549  5389  5389 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,11-17 18:01:31.551  5389  5389 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
11-17 18:01:31.554   833   996 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
11-17 18:01:31.555   833   996 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
11-17 18:01:31.555   833   996 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
11-17 18:01:31.555   833   996 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:01:31.555   833   996 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@4c213f7,  pkg=WindowManager.LayoutParams
11-17 18:01:31.555   833   996 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
11-17 18:01:31.565  1875  1875 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@208bfb6f time:79901
,11-17 18:01:31.581  1371  1496 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
11-17 18:01:31.582  1371  1496 D KeyguardModel: createShortcutInfo...
,11-17 18:01:31.585  1371  1496 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:01:31.585  1371  1496 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
11-17 18:01:31.588   833   833 D administrator: Handling package changes for user 0
11-17 18:01:31.590  1371  1496 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
11-17 18:01:31.590  1371  1496 D KeyguardModel: createShortcutInfo...
11-17 18:01:31.592  1371  1496 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:01:31.592  1371  1496 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
11-17 18:01:31.593  1371  1496 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
11-17 18:01:31.593  1371  1496 D KeyguardModel: createShortcutInfo...
,11-17 18:01:31.602  1371  1496 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:01:31.602  1371  1496 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
11-17 18:01:31.604  1371  1496 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
11-17 18:01:31.604  1371  1496 D KeyguardModel: createShortcutInfo...
,11-17 18:01:31.610  1371  1371 D KeyguardModel: handleShortcutListChanged...
11-17 18:01:31.625  1875  1875 I art     : Explicit concurrent mark sweep GC freed 4217(255KB) AllocSpace objects, 5(681KB) LOS objects, 39% free, 15MB/25MB, paused 2.117ms total 59.196ms
,11-17 18:01:31.747   833   833 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
11-17 18:01:31.747   833   833 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
11-17 18:01:31.749   833   833 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-17 18:01:31.773   833  1347 D TaskPersister: removeObsoleteFile: deleting file=217_task.xml
,11-17 18:01:31.775  1371  1371 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
11-17 18:01:31.776  1371  1371 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
11-17 18:01:31.776  1371  1371 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
11-17 18:01:31.776  1371  1371 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
11-17 18:01:31.776  5389  5389 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
11-17 18:01:31.784  1937  5409 I HotwordRecognitionRnr: Starting hotword detection.
,11-17 18:01:31.787  1371  1371 D BarTransitions: draw background and invalidate : color = ef000000
11-17 18:01:31.789  1371  1371 D BarTransitions: draw background and invalidate : color = ede3e3e3
11-17 18:01:31.791  1937  5410 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@1e4fdf59
11-17 18:01:31.791  1937  5410 V AudioRecord: set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
11-17 18:01:31.792  1937  5410 V AudioRecord: set(): mSessionId 22
11-17 18:01:31.799   282  1602 V AudioPolicyManager: getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
,11-17 18:01:31.799   282  1602 V AudioPolicyManager: getDeviceForInputSource()input source 1999, device 80000004
11-17 18:01:31.799   282  1602 V AudioPolicyManager: isPlaybackThread 0,isRecordThread 1
11-17 18:01:31.799   282  1602 D audio_hw_primary: adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546dd40)
11-17 18:01:31.799   282  1602 V audio_hw_primary: adev_open_input_stream: exit
11-17 18:01:31.799   282  1602 V AudioFlinger: openInput_l() openInputStream returned input 0xb546dd40, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
11-17 18:01:31.800   282  1602 V AudioFlinger: openInput_l() created record thread: ID 23 thread 0xb42a5000
11-17 18:01:31.800   282  1602 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
11-17 18:01:31.800  1371  1911 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
11-17 18:01:31.800   282  1602 V AudioPolicyService: AudioCommandThread() adding update audio port list
11-17 18:01:31.800   282  1602 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
11-17 18:01:31.800   282  1062 V AudioPolicyService: AudioCommandThread() waking up
11-17 18:01:31.800   282  1062 V AudioPolicyService: AudioCommandThread() processing update audio port list
11-17 18:01:31.801   282  1062 V AudioPolicyService: AudioCommandThread() going to sleep
11-17 18:01:31.801  1937  2359 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
11-17 18:01:31.801  1748  1764 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
11-17 18:01:31.801  2702  2722 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
11-17 18:01:31.801  3114  3129 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
11-17 18:01:31.801   833   853 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
11-17 18:01:31.802   282   282 V AudioFlinger: openRecord() lSessionId: 22 input 23
11-17 18:01:31.805   833   999 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{16a5a74f u0 com.lge.launcher2/.Launcher t216} time:80140
11-17 18:01:31.808   282  5412 I AudioFlinger: AudioFlinger's thread 0xb42a5000 ready to run
11-17 18:01:31.808   282  5412 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
11-17 18:01:31.808   282  5412 V audio_hw_primary: in_standby: exit:  status(0)
11-17 18:01:31.809   282   282 V AudioFlinger: getOrphanEffectChain_l session 22 index -2
11-17 18:01:31.810   282  5412 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
11-17 18:01:31.810   282  5412 V audio_hw_primary: in_standby: exit:  status(0)
11-17 18:01:31.810   282  5412 V AudioFlinger: RecordThread: loop stopping
11-17 18:01:31.813   282   282 V AudioFlinger: acquiring 22 from 1937, for -1
11-17 18:01:31.813   282   282 V AudioFlinger:  added new entry for 22
,11-17 18:01:31.815  1937  5410 V AudioRecord: start, sync event 0 trigger session 0
11-17 18:01:31.815  1937  5410 V AudioRecord: mAudioRecord->start()
11-17 18:01:31.815   282  1303 V AudioFlinger: RecordHandle::start()
11-17 18:01:31.815   282  1303 V AudioFlinger: RecordThread::start event 0, triggerSession 0
11-17 18:01:31.815   282  1303 V AudioPolicyManager: startInput() module primary->input primary(23)
11-17 18:01:31.816   282  1303 V AudioPolicyManager: getDeviceForInputSource()input source 1999, device 80000004
11-17 18:01:31.816   282  1303 V AudioPolicyManager: getNewInputDevice() selected device 80000004
11-17 18:01:31.816   282  1303 V AudioPolicyManager: DeviceVector::refreshTypes() mDeviceTypes 80000004
11-17 18:01:31.816   282  1303 V AudioPolicyManager: DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
11-17 18:01:31.816   282  1303 V AudioPolicyService: AudioCommandThread() adding create patch delay 0
11-17 18:01:31.816   282  1303 V AudioPolicyService: inserting command: 7 at index 0, num commands 0
11-17 18:01:31.816   282  1061 V AudioPolicyService: AudioCommandThread() waking up
11-17 18:01:31.816   282  1061 V AudioPolicyService: AudioCommandThread() processing create audio patch
11-17 18:01:31.816   282  1061 V AudioFlinger::PatchPanel: createAudioPatch() num_sources 1 num_sinks 1 handle 0
11-17 18:01:31.816   282  1061 V AudioFlinger::PatchPanel: createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
11-17 18:01:31.816   282  1061 V AudioFlinger: ThreadBase::setParameters() input_source=6;routing=-2147483644
11-17 18:01:31.816   282  1061 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
11-17 18:01:31.816   282  5412 V AudioFlinger: RecordThread: loop starting
11-17 18:01:31.816   282  5412 V AudioFlinger: processConfigEvents_l() remaining events 1
11-17 18:01:31.816   282  5412 D audio_hw_primary: in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
11-17 18:01:31.816   282  5412 V audio_hw_primary: in_set_parameters: exit: status(0)
11-17 18:01:31.816   282  5412 V AudioFlinger: processConfigEvents_l() DONE thread 0xb42a5000
11-17 18:01:31.816   282  1061 V AudioFlinger::PatchPanel: createAudioPatch() status 0
11-17 18:01:31.816   282  1061 V AudioFlinger::PatchPanel: createAudioPatch() added new patch handle 24 halHandle 0
11-17 18:01:31.816   282  1061 V AudioPolicyService: AudioCommandThread() going to sleep
11-17 18:01:31.817   282  1303 V AudioPolicyManager: setInputDevice() createAudioPatch returned 0 patchHandle 24
11-17 18:01:31.817   282  1303 V AudioPolicyManager: addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
11-17 18:01:31.817   282  1303 V AudioPolicyService: AudioCommandThread() adding update audio patch list
11-17 18:01:31.817   282  1303 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
11-17 18:01:31.818   282  1062 V AudioPolicyService: AudioCommandThread() waking up
11-17 18:01:31.818   282  1062 V AudioPolicyService: AudioCommandThread() processing update audio patch list
11-17 18:01:31.818   282  1062 V AudioPolicyService: AudioCommandThread() going to sleep
11-17 18:01:31.818   282  1303 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
11-17 18:01:31.819   282  1303 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
11-17 18:01:31.819   282  1061 V AudioPolicyService: AudioCommandThread() waking up
11-17 18:01:31.819   282  1061 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=1, io 23
11-17 18:01:31.819  5389  5389 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
11-17 18:01:31.819   282  1061 V AudioFlinger: setParameters(): io 23, keyvalue hotword_active=1, calling pid 282
11-17 18:01:31.819   282  1061 V AudioFlinger: ThreadBase::setParameters() hotword_active=1
11-17 18:01:31.819   282  1061 V AudioFlinger: sendConfigEvent_l() num ,events 1 event 2
11-17 18:01:31.826   282  5412 V AudioFlinger: processConfigEvents_l() remaining events 1
11-17 18:01:31.826   282  5412 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=1
11-17 18:01:31.827   282  5412 V audio_hw_primary: in_set_parameters: exit: status(0)
11-17 18:01:31.827   282  5412 V AudioFlinger: processConfigEvents_l() DONE thread 0xb42a5000
11-17 18:01:31.827   282  1061 V AudioPolicyService: AudioCommandThread() going to sleep
11-17 18:01:31.827   282  1303 V AudioPolicyManager: AudioPolicyManager::startInput() input source = 1999
11-17 18:01:31.833  1937  5410 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@1e4fdf59
11-17 18:01:31.835   833   876 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:01:31.839   282  5412 V msm8974_platform: platform_update_usecase_from_source: input source :6
11-17 18:01:31.839   282  5412 D audio_hw_primary: start_input_stream: enter: stream(0xb546dd40)usecase(7: audio-record)
11-17 18:01:31.839   282  5412 V voice   : voice_check_and_set_incall_rec_usecase: voice call not active
11-17 18:01:31.839   282  5412 V audio_hw_primary: start_input_stream: usecase(7)
11-17 18:01:31.839   282  5412 E audio_hw_primary: select_devices: enter and usecase(7)
11-17 18:01:31.839   282  5412 V msm8974_platform: platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
11-17 18:01:31.839   282  5412 V msm8974_platform: platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
11-17 18:01:31.839   282  5412 V msm8974_platform_lge: LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
11-17 18:01:31.839   282  5412 V audio_hw_lge_primary: LGE_exeption_scenario: enter and out: 0, in: 144
11-17 18:01:31.839   282  5412 D audio_hw_primary: select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
11-17 18:01:31.840   282  5412 E audio_hw_primary: enable_snd_device: enter  144
11-17 18:01:31.840   282  5412 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
11-17 18:01:31.840   282  5412 V audio_hw_primary: enable_snd_device: snd_device(144: lg-vr-handset-mic)
11-17 18:01:31.840   282  5412 V msm8974_platform_lge: LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
11-17 18:01:31.840   282  5412 D ACDB-LOADER: ACDB -> send_audio_cal, acdb_id = 65, path =  1
11-17 18:01:31.840   282  5412 D ACDB-LOADER: ACDB -> send_adm_topology
11-17 18:01:31.840   282  5412 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
11-17 18:01:31.841   282  5412 D ACDB-LOADER: ACDB -> send_asm_topology
11-17 18:01:31.842   282  5412 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
11-17 18:01:31.842   282  5412 D ACDB-LOADER: ACDB -> send_audtable
11-17 18:01:31.842   282  5412 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
11-17 18:01:31.842   282  5412 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_CAL
11-17 18:01:31.842   282  5412 D ACDB-LOADER: ACDB -> send_audvoltable
11-17 18:01:31.842   282  5412 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
11-17 18:01:31.842   282  5412 D         : Failed to fetch the lookup information of the device 00000041 
11-17 18:01:31.842   282  5412 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
11-17 18:01:31.842   282  5412 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
11-17 18:01:31.842   282  5412 D ACDB-LOADER: ACDB -> AUDIO_SET_AFE_CAL
11-17 18:01:31.848   282  5412 V audio_hw_primary: enable_audio_route: enter: usecase(7)
11-17 18:01:31.848   282  5412 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
11-17 18:01:31.848   282  5412 V audio_hw_primary: enable_audio_route: apply mixer and update path: audio-record
11-17 18:01:31.849   282  5412 V audio_hw_primary: enable_audio_route: exit
11-17 18:01:31.849   282  5412 D audio_hw_primary: select_devices: done
11-17 18:01:31.849   282  5412 V audio_hw_primary: start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
11-17 18:01:31.854   282  5412 V audio_hw_primary: start_input_stream: exit
,11-17 18:01:31.863  1937  1937 I art     : Explicit concurrent mark sweep GC freed 1792(119KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/21MB, paused 2.116ms total 110.672ms
11-17 18:01:31.892   833   876 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,11-17 18:01:31.938  1875  1875 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,11-17 18:01:31.941   833  1057 I art     : Explicit concurrent mark sweep GC freed 8552(486KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 5.594ms total 428.523ms
11-17 18:01:31.965  1937  1937 I HotwordWorker: onReady
,11-17 18:01:31.999  5335  5335 D AndroidRuntime: Shutting down VM
,11-17 18:01:32.038  1783  1783 D LCardEmulationManager: getHceAppCount hostAppNum : 0
,11-17 18:01:32.039  1783  1783 D LCardEmulationManager: getDefaultRoute
,11-17 18:01:32.056  5353  5353 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
11-17 18:01:32.058  5353  5353 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
11-17 18:01:32.060   833  2205 I ActivityManager: Killing 5170:com.lge.appbox.client/u0a11 (adj 15): empty #11
11-17 18:01:32.073  5389  5389 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,11-17 18:01:32.087   833  2205 I ActivityManager: Killing 5189:com.android.gallery3d/u0a23 (adj 15): empty #11
,11-17 18:01:32.112   833  2205 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper}
11-17 18:01:32.112   833  2205 W BroadcastQueue: android.os.DeadObjectException
11-17 18:01:32.112   833  2205 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
11-17 18:01:32.112   833  2205 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
11-17 18:01:32.112   833  2205 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
11-17 18:01:32.112   833  2205 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:270)
11-17 18:01:32.112   833  2205 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1002)
11-17 18:01:32.112   833  2205 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16810)
11-17 18:01:32.112   833  2205 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:473)
11-17 18:01:32.112   833  2205 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2625)
11-17 18:01:32.112   833  2205 W BroadcastQueue: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:457)
11-17 18:01:32.112   833  2205 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
11-17 18:01:32.112   833  2205 W libprocessgroup: failed to open /acct/uid_10011/pid_5170/cgroup.procs: No such file or directory
,11-17 18:01:32.171   833  2205 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5417 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
11-17 18:01:32.171   833  1909 W ActivityManager: Spurious death for ProcessRecord{9a751a2 5417:com.lge.appbox.client/u0a11}, curProc for 5170: null
11-17 18:01:32.172   833  1874 W libprocessgroup: failed to open /acct/uid_10023/pid_5189/cgroup.procs: No such file or directory
,11-17 18:01:32.286  5417  5417 I AppUp4:AppBoxCP: onCreate
,11-17 18:01:32.287  5417  5417 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
11-17 18:01:32.302  5417  5417 I AppUp4:DB:  setFingerPrint start
,11-17 18:01:32.303  5417  5417 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
11-17 18:01:32.311  5417  5417 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
11-17 18:01:32.311  5417  5417 I AppUp4:DB:  SDK version = 0
11-17 18:01:32.311  5417  5417 I AppUp4:DB:  beforefinger == newfinger no write in DB
11-17 18:01:32.313  5417  5417 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
11-17 18:01:32.383  5417  5417 D AppUp4:PreloadHelper: added Exclude : com.example.hello
,11-17 18:01:32.420   833  1782 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=5440 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,11-17 18:01:32.421   833  1782 I ActivityManager: Killing 5211:com.android.contacts/u0a18 (adj 15): empty #11
11-17 18:01:32.447   833  1837 W libprocessgroup: failed to open /acct/uid_10018/pid_5211/cgroup.procs: No such file or directory
,11-17 18:01:32.487  5440  5440 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
```
