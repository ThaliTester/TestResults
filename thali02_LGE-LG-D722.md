#### Test 62548124d9c0fd9_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
03-19 12:52:54.156   826  1794 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,--------- beginning of main
03-19 12:52:54.260  4236  4268 I Gmail   : getAccountsCursor
03-19 12:52:54.284  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-19 12:52:54.310  4236  4236 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
03-19 12:52:54.355   826  1821 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-19 12:52:54.371   826  1803 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
03-19 12:52:54.375  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
03-19 12:52:54.375  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
03-19 12:52:54.375  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
03-19 12:52:54.375  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
03-19 12:52:54.375  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
03-19 12:52:54.376  4236  4278 E Gmail   : Error finding the version of the Email provider.....
03-19 12:52:54.376  4236  4278 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-19 12:52:54.376  4236  4278 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
03-19 12:52:54.376  4236  4278 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
03-19 12:52:54.376  4236  4278 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
03-19 12:52:54.376  4236  4278 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-19 12:52:54.376  4236  4278 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 12:52:54.376  4236  4278 E Gmail   : 	at android.os.Looper.loop(Looper.java:135)
03-19 12:52:54.376  4236  4278 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-19 12:52:54.376  4236  4278 W EmailMigration: We do not support migrating this version of the Email provider.
03-19 12:52:54.386   826   846 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-19 12:52:54.395  4236  4281 I Gmail   : getAccountsCursor
03-19 12:52:54.403  4236  4280 I Gmail   : Observing account changes for notifications
03-19 12:52:54.405  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-19 12:52:54.427   486   486 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
03-19 12:52:54.430  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
03-19 12:52:54.431  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
03-19 12:52:54.434  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
03-19 12:52:54.439  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
03-19 12:52:54.440  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-19 12:52:54.442  1804  1956 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
03-19 12:52:54.442  1804  1956 D LEDHandler: Battery Level Remaining: 100%
03-19 12:52:54.442  1804  1956 D LEDHandler: Battery Temp: 288, mChargingStatus=5, mChargingStop=false
03-19 12:52:54.443  4006  4006 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
03-19 12:52:54.443   826  1313 D WifiController: battery changed pluggedType: 2
03-19 12:52:54.443   826   826 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
03-19 12:52:54.443   826   826 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
03-19 12:52:54.445  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
03-19 12:52:54.444  2010  3379 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-19 12:52:54.451   826  1794 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-19 12:52:54.454   826  1773 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-19 12:52:54.457  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
03-19 12:52:54.460  4236  4236 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@4ea27e9 that was originally bound here
03-19 12:52:54.460  4236  4236 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@4ea27e9 that was originally bound here
03-19 12:52:54.460  4236  4236 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
03-19 12:52:54.460  4236  4236 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
03-19 12:52:54.460  4236  4236 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
03-19 12:52:54.460  4236  4236 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
03-19 12:52:54.460  4236  4236 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
03-19 12:52:54.460  4236  4236 E ActivityThread: 	at com.android.emailcommon.service.ak.a(SourceFile:181)
03-19 12:52:54.460  4236  4236 E ActivityThread: 	at com.android.emailcommon.service.ak.e(SourceFile:224)
03-19 12:52:54.460  4236  4236 E ActivityThread: 	at com.android.email.service.n.c(SourceFile:177)
03-19 12:52:54.460  4236  4236 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:198)
03-19 12:52:54.460  4236  4236 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:142)
03-19 12:52:54.460  4236  4236 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
03-19 12:52:54.460  4236  4236 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
03-19 12:52:54.460  4236  4236 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-19 12:52:54.460  4236  4236 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 12:52:54.460  4236  4236 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-19 12:52:54.460  4236  4236 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-19 12:52:54.461   826  1900 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@18ae7d43
03-19 12:52:54.479  4006  4006 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
03-19 12:52:54.480  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
03-19 12:52:54.480  1804  1956 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
03-19 12:52:54.480  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
03-19 12:52:54.481  1804  1956 D LEDHandler: Battery Level Remaining: 100%
03-19 12:52:54.481  1804  1956 D LEDHandler: Battery Temp: 287, mChargingStatus=5, mChargingStop=false
03-19 12:52:54.482   826   826 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
03-19 12:52:54.482   826   826 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
03-19 12:52:54.482   826  1313 D WifiController: battery changed pluggedType: 2
03-19 12:52:54.487  2010  3379 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-19 12:52:54.493  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
03-19 12:52:54.494  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
03-19 12:52:54.494  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
03-19 12:52:54.494  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
03-19 12:52:54.494  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
03-19 12:52:54.494  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
03-19 12:52:54.494  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
03-19 12:52:54.494  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
03-19 12:52:54.496  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
03-19 12:52:54.629   826  1883 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4296 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-19 12:52:54.651  4272  4272 D AndroidRuntime: 
03-19 12:52:54.651  4272  4272 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-19 12:52:54.655  4272  4272 D AndroidRuntime: CheckJNI is OFF
03-19 12:52:54.707  4236  4292 I Gmail   : notifyAccountChanged
03-19 12:52:54.717  4236  4292 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
03-19 12:52:54.739  4236  4292 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
03-19 12:52:54.740   826  1348 I ActivityManager: Killing 3890:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
03-19 12:52:54.764  4236  4292 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
03-19 12:52:54.766  4236  4292 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
03-19 12:52:54.828   826  1845 W libprocessgroup: failed to open /acct/uid_10069/pid_3890/cgroup.procs: No such file or directory
03-19 12:52:55.049  4272  4272 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-19 12:52:55.053  1939  2929 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
03-19 12:52:55.063  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-19 12:52:55.071  4236  4331 I Gmail   : getAccountsCursor
03-19 12:52:55.072   826  1359 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-19 12:52:55.121   826  1359 D ActivityManager: setTaskToReturnTo : TaskRecord{31f9286d #226 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
03-19 12:52:55.123   826  1359 D ActivityManager: setTaskToReturnTo : TaskRecord{31f9286d #226 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
03-19 12:52:55.134   826  1359 D WindowStateEx: AppWindowTokenEx init.. 
03-19 12:52:55.143   826  1023 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
03-19 12:52:55.173   826  1359 D InputDispatcher: Focus left window: Window{e855c98 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
03-19 12:52:55.173  4272  4272 D AndroidRuntime: Shutting down VM
03-19 12:52:55.174  1877  1877 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
03-19 12:52:55.180  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-19 12:52:55.190   826  1023 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
03-19 12:52:55.196  4236  4331 I Gmail   : getAccountsCursor
03-19 12:52:55.198  4296  4296 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
03-19 12:52:55.211   826  1023 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
03-19 12:52:55.211   826  1023 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
03-19 12:52:55.223   826  1023 D SplitWindow: check instance of lgWin Window{27a8f1a1 u0 Starting com.test.thalitest}
03-19 12:52:55.243   826  1875 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4334 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-19 12:52:55.270  1939  2929 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 3096-3101)
03-19 12:52:55.272  1939  2929 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-19 12:52:55.287  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-19 12:52:55.299  1877  1877 I [LGHome]EVENT: [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
03-19 12:52:55.311  1939  2929 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-19 12:52:55.335  1877  1877 I [LGHome]EVENT: [Launcher.java:5214:onStop()]onStop
03-19 12:52:55.350   826   846 I WindowStateAnimator: Starting window displayed
03-19 12:52:55.358   826  1021 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
03-19 12:52:55.369   826  1021 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
,03-19 12:52:55.370  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
03-19 12:52:55.376   826  1021 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
03-19 12:52:55.376   826  1021 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
03-19 12:52:55.376   826  1021 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-19 12:52:55.377   826  1021 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@218d96a,  pkg=WindowManager.LayoutParams
03-19 12:52:55.377   826  1021 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
03-19 12:52:55.379  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
03-19 12:52:55.379  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
03-19 12:52:55.379  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
03-19 12:52:55.383  1939  1939 I HotwordDetector: Closing mic
03-19 12:52:55.384  1939  2604 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@b796642
03-19 12:52:55.385  1939  2604 V AudioRecord: stop()
03-19 12:52:55.385  1939  2604 D AudioRecord: AudioRecord->stop()
03-19 12:52:55.385   282   282 V AudioFlinger: RecordHandle::stop()
03-19 12:52:55.385   282   282 V AudioFlinger: RecordThread::stop
03-19 12:52:55.402   282   282 V AudioFlinger: Record stopped OK
03-19 12:52:55.402   282   282 V AudioPolicyManager: stopInput() input 17
03-19 12:52:55.402   282   282 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
03-19 12:52:55.402   282   282 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
03-19 12:52:55.403   282  1032 V AudioPolicyService: AudioCommandThread() waking up
03-19 12:52:55.403   282  1032 V AudioPolicyService: AudioCommandThread() processing release audio patch
03-19 12:52:55.403   282  1032 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
03-19 12:52:55.403   282  1032 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
03-19 12:52:55.403   282  1032 V AudioFlinger: ThreadBase::setParameters() routing=0
03-19 12:52:55.403   282  1032 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
03-19 12:52:55.408   282  2638 V AudioFlinger: processConfigEvents_l() remaining events 1
03-19 12:52:55.409   282  2638 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3878000
03-19 12:52:55.410   282  2638 D audio_hw_primary: in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
03-19 12:52:55.452   282  2638 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
03-19 12:52:55.452   282  2638 V audio_hw_primary: disable_audio_route: enter: usecase(7)
03-19 12:52:55.452   282  2638 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
03-19 12:52:55.452   282  2638 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-19 12:52:55.452   282  2638 V audio_hw_primary: disable_audio_route: exit
03-19 12:52:55.452   282  2638 E audio_hw_primary: disable_snd_device: enter 144
03-19 12:52:55.452   282  2638 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
03-19 12:52:55.452   282  2638 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
03-19 12:52:55.456   282  2638 V audio_hw_primary: stop_input_stream: exit: status(0)
03-19 12:52:55.456   282  2638 V audio_hw_primary: in_standby: exit:  status(0)
03-19 12:52:55.456   282  2638 V AudioFlinger: RecordThread: loop stopping
03-19 12:52:55.457   282  1032 V AudioPolicyService: AudioCommandThread() going to sleep
03-19 12:52:55.457   282   282 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
03-19 12:52:55.457   282   282 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
03-19 12:52:55.457   282   282 V AudioPolicyService: AudioCommandThread() adding update audio patch list
03-19 12:52:55.457   282   282 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
03-19 12:52:55.457   282  1033 V AudioPolicyService: AudioCommandThread() waking up
03-19 12:52:55.457   282  1033 V AudioPolicyService: AudioCommandThread() processing update audio patch list
03-19 12:52:55.457   282  1033 V AudioPolicyService: AudioCommandThread() going to sleep
03-19 12:52:55.458   282   282 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
03-19 12:52:55.458   282   282 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
03-19 12:52:55.458   282  1032 V AudioPolicyService: AudioCommandThread() waking up
03-19 12:52:55.459   282  1032 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
03-19 12:52:55.459   282  1032 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 282
03-19 12:52:55.459   282  1032 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
03-19 12:52:55.459   282  1032 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
03-19 12:52:55.459   282  2638 V AudioFlinger: RecordThread: loop starting
03-19 12:52:55.459   282  2638 V AudioFlinger: processConfigEvents_l() remaining events 1
03-19 12:52:55.459   282  2638 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
03-19 12:52:55.459   282  2638 V audio_hw_primary: in_set_parameters: exit: status(0)
03-19 12:52:55.459   282  2638 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3878000
03-19 12:52:55.459   282  2638 V AudioFlinger: RecordThread: loop stopping
03-19 12:52:55.460   282  1032 V AudioPolicyService: AudioCommandThread() going to sleep
03-19 12:52:55.474  1939  2604 V AudioRecord: stop()
03-19 12:52:55.477  1939  2604 V AudioRecord: stop()
03-19 12:52:55.477  1939  2604 V AudioRecord: stop()
03-19 12:52:55.479   282  1296 V AudioFlinger: RecordHandle::stop()
03-19 12:52:55.479   282  1296 V AudioFlinger: RecordThread::stop
03-19 12:52:55.479   282  1296 V AudioPolicyManager: releaseInput() 17
03-19 12:52:55.479   282  1296 V AudioPolicyManager: closeInput(17)
03-19 12:52:55.479   282  1296 V AudioFlinger: closeInput() 17
03-19 12:52:55.479   282  1296 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
03-19 12:52:55.480  1750  2691 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
03-19 12:52:55.480   282  1296 V AudioFlinger: ThreadBase::exit
03-19 12:52:55.480   282  2638 V AudioFlinger: RecordThread: loop starting
03-19 12:52:55.480  2083  2099 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
03-19 12:52:55.480   282  2638 V AudioFlinger: RecordThread 0xb3878000 exiting
03-19 12:52:55.480  1939  1964 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
03-19 12:52:55.480  2010  3380 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
03-19 12:52:55.481  1372  2383 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
03-19 12:52:55.481   826  1876 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
03-19 12:52:55.481   282  1296 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546e1a0)
03-19 12:52:55.481  3108  3124 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
03-19 12:52:55.481   282  1296 D audio_hw_primary: in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
03-19 12:52:55.481   282  1296 V audio_hw_primary: in_standby: exit:  status(0)
03-19 12:52:55.481   282  1663 V AudioFlinger: releasing 16 from 1939 for -1
03-19 12:52:55.481   282  1663 V AudioFlinger:  decremented refcount to 0
03-19 12:52:55.481   282  1663 V AudioFlinger: purging stale effects
03-19 12:52:55.481   282  1296 V AudioPolicyService: AudioCommandThread() adding update audio port list
03-19 12:52:55.482   282  1296 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
03-19 12:52:55.482   282  1296 V AudioPolicyManager: releaseInput() exit
03-19 12:52:55.482   282  1033 V AudioPolicyService: AudioCommandThread() waking up
03-19 12:52:55.482   282  1033 V AudioPolicyService: AudioCommandThread() processing update audio port list
03-19 12:52:55.482   282  1033 V AudioPolicyService: AudioCommandThread() going to sleep
03-19 12:52:55.482   282  1296 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
03-19 12:52:55.482  4334  4334 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
03-19 12:52:55.483   282  1296 V AudioFlinger: removeClient_l() pid 1939, calling pid 282
03-19 12:52:55.486  1939  2621 I HotwordRecognitionRnr: Stopping hotword detection.
03-19 12:52:55.487  1939  2629 I HotwordRecognitionRnr: Hotword detection finished
03-19 12:52:55.546  4334  4334 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
03-19 12:52:55.558  1939  2929 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-19 12:52:55.600  4334  4334 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3429-3431)
03-19 12:52:55.601  4334  4334 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-19 12:52:55.630  4296  4296 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(122): No need to run daily hygiene.
03-19 12:52:55.647  4334  4334 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d4dd10d}
03-19 12:52:55.648  4334  4334 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-19 12:52:55.649  4334  4334 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-19 12:52:55.657  4296  4296 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-19 12:52:55.658  4296  4296 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-19 12:52:55.665  4334  4334 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-19 12:52:55.665  4296  4296 I NotificationManager: com.android.vending: cancel(-1050172287) by com.android.vending
03-19 12:52:55.666  4334  4334 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-19 12:52:55.668  4334  4334 E SysUtils: ApplicationContext is null in ApplicationStatus
03-19 12:52:55.683  4334  4386 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
03-19 12:52:55.699  4334  4334 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-19 12:52:55.711  4334  4334 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-19 12:52:55.711  4334  4334 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-19 12:52:55.715  4334  4334 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
03-19 12:52:55.715  4334  4334 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
03-19 12:52:55.715  4334  4334 I Adreno-EGL: Build Date: 03/02/15 Mon
03-19 12:52:55.715  4334  4334 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
03-19 12:52:55.715  4334  4334 I Adreno-EGL: Remote Branch: 
03-19 12:52:55.715  4334  4334 I Adreno-EGL: Local Patches: 
03-19 12:52:55.715  4334  4334 I Adreno-EGL: Reconstruct Branch: 
03-19 12:52:55.739  2718  3375 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is notificationclass=?; selectionArgs[0] is com.google.android.finsky.download.DownloadBroadcastReceiver; sort is null.
03-19 12:52:55.743  2718  3375 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@29e94417 on behalf of 4296
03-19 12:52:55.749  4296  4353 D Volley  : [431] g.b: Cache cleared.
03-19 12:52:55.749  4296  4366 D Volley  : [438] g.b: Cache cleared.
03-19 12:52:55.756  4296  4390 D Ads     : Skipping gmscore version check
03-19 12:52:55.796   294   352 I ThermalEngine: Sensor:pa_therm0:32000 mC
03-19 12:52:55.800   826  1876 I ActivityManager: Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=4391 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
03-19 12:52:55.801   826  1876 I ActivityManager: Killing 3908:com.lge.springcleaning/1000 (adj 15): empty #11
03-19 12:52:55.866   282   282 V AudioPolicyService: registerClient() client 0xb57e93e0, uid 10030
03-19 12:52:55.871   826  1845 W libprocessgroup: failed to open /acct/uid_1000/pid_3908/cgroup.procs: No such file or directory
03-19 12:52:55.878   826  1022 D BluetoothManagerService: Message: 20
03-19 12:52:55.878   826  1022 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3979eb6f:true
03-19 12:52:55.884  2010  2045 D BluetoothAdapterService(214083283): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a5b3841
03-19 12:52:55.898  4296  4296 I Finsky  : [1] com.google.android.finsky.g.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-19 12:52:55.898  4296  4296 I Finsky  : [1] com.google.android.finsky.g.j.run(214): Finished loading 1 libraries.
03-19 12:52:55.921  4391  4391 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
03-19 12:52:55.924  4296  4296 I Finsky  : [1] com.google.android.finsky.b.j.a(273): result=false type=4
03-19 12:52:55.976  4296  4296 I Finsky  : [1] com.google.android.finsky.services.ar.a(1049): Restore complete with 0 success and 0 failed.
03-19 12:52:56.065  4391  4391 E App     : [App][onCreate()] 4.40.23
,03-19 12:52:56.144  4334  4334 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 12:52:56.159  4334  4334 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-19 12:52:56.165  4334  4334 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
03-19 12:52:56.167  4334  4334 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
03-19 12:52:56.168  4334  4334 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
03-19 12:52:56.182  4334  4334 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,03-19 12:52:56.189  4334  4334 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-19 12:52:56.189  4334  4334 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-19 12:52:56.191   826  1286 W ActivityManager: Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
03-19 12:52:56.193   826  1286 V AlarmManager: RTC_WAKEUP set : Alarm{3523950a type 0 when 1457956345452 com.android.providers.contacts} when 1457956345452
03-19 12:52:56.194   826  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{74bb17b type 2 when 59371 com.google.android.talk} when 59371
,03-19 12:52:56.197   826  1286 V AlarmManager: RTC_WAKEUP set : Alarm{2081dff1 type 0 when 1458388376190 com.google.android.gms} when 1458388376190
03-19 12:52:56.258  4334  4334 I Activity: Activity.onPostResume() called 
,03-19 12:52:56.266  4334  4430 D OpenGLRenderer: Render dirty regions requested: true
03-19 12:52:56.266  4334  4430 I OpenGLRenderer: Initialized EGL, version 1.4
03-19 12:52:56.267  2268  4426 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 65 ms
03-19 12:52:56.273  4334  4430 D OpenGLRenderer: Enabling debug mode 0
,03-19 12:52:56.288  4334  4334 D Atlas   : Validating map...
,03-19 12:52:56.293   826  1359 D SplitWindow: check instance of lgWin Window{3ac38a2d u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-19 12:52:56.303  4334  4413 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-19 12:52:56.339   826  1845 D InputDispatcher: Focus entered window: Window{3ac38a2d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-19 12:52:56.421   826  1876 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,03-19 12:52:56.424   826  1023 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s233ms
03-19 12:52:56.424   826  1023 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{22b59ca2 u0 com.test.thalitest/.MainActivity t226} time:64255
03-19 12:52:56.430  4391  4391 D AccountManager: setSyncFrequency
03-19 12:52:56.447  4334  4334 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@206f701f time:64278
,03-19 12:52:56.553  4391  4391 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.qmemoplus.ui.editor.reminder.ReminderMaker.onReceive:14 android.app.ActivityThread.handleReceiver:2663 
,03-19 12:52:56.578  4334  4334 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4334
03-19 12:52:56.578  2899  2899 D WeatherAncestor: 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:52:56
,03-19 12:52:56.583  4391  4437 D ReminderService: [onHandleIntent] action : com.lge.qmemoplus.action.SET_REMINDERS
03-19 12:52:56.583  2899  2899 D UpdateThreadPoolManager: 2 : This is isUpdating : false
03-19 12:52:56.584  2899  2899 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:52:56
03-19 12:52:56.584  4391  4437 D LocationReminderManager: [connect] Request location client connection.
03-19 12:52:56.585  2899  2899 D WeatherService: 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
03-19 12:52:56.587   826  1845 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
03-19 12:52:56.591  2899  2899 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
,03-19 12:52:56.594  2899  2899 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
03-19 12:52:56.594  2899  2899 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
03-19 12:52:56.595  2899  2899 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
03-19 12:52:56.597  2899  2899 D UpdateThreadPoolManager: 2 : This is isUpdating : false
03-19 12:52:56.597  2899  2899 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
03-19 12:52:56.597  2899  2899 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
03-19 12:52:56.636  2899  2899 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
03-19 12:52:56.636  2899  2899 D WeatherTheme: 2 : Fixed theme : optimus
,03-19 12:52:56.641  2899  2899 D WeatherReflect: 2 : Map key string is -2
03-19 12:52:56.645  4391  4437 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.google.android.gms.internal.he.a:-1 com.google.android.gms.internal.hc.connect:-1 com.google.android.gms.location.LocationClient.connect:-1 
03-19 12:52:56.645  2899  2899 D lim     : 2 : time = 12:52
03-19 12:52:56.652  1731  1731 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,03-19 12:52:56.670  2899  2899 I WeatherReflect: Model Name : LG-D722
03-19 12:52:56.683  2899  2899 D WeatherTheme: 2 : exactly same view!
,03-19 12:52:56.687  2899  2899 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
03-19 12:52:56.689   826  2177 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
03-19 12:52:56.689  2899  2899 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
03-19 12:52:56.690  2899  2899 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
03-19 12:52:56.690  2899  2899 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
03-19 12:52:56.699  4391  4391 D LocationReminderManager: location cilent is connected.
,03-19 12:52:56.740   826  1845 I ActivityManager: Killing 3950:com.google.android.configupdater/u0a3 (adj 15): empty #11
,03-19 12:52:56.760  4391  4391 D LocationReminderManager: [removeAllReminders]
,03-19 12:52:56.814  4334  4334 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-19 12:52:56.820   826  1348 W libprocessgroup: failed to open /acct/uid_10003/pid_3950/cgroup.procs: No such file or directory
03-19 12:52:56.843  1731  2467 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-19 12:52:56.846  4391  4391 D LocationReminderManager: [removeAllReminders] statusCode : 1000
03-19 12:52:56.846  4391  4391 D LocationReminderManager: [removeAllReminders] Failed to remove reminder
,03-19 12:52:56.867   826  1875 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=4441 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,03-19 12:52:56.889   309   309 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 22.117ms
,03-19 12:52:56.910   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 326us total 20.214ms
,03-19 12:52:56.934   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 22.304ms
,03-19 12:52:57.029  4441  4441 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
03-19 12:52:57.030  4441  4441 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,03-19 12:52:57.035  4441  4441 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
03-19 12:52:57.040  4441  4441 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
03-19 12:52:57.046  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,03-19 12:52:57.052  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.074  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.074  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
,03-19 12:52:57.076  4441  4462 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
03-19 12:52:57.082  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.082  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.086  4441  4460 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,03-19 12:52:57.103  1731  2558 I art     : Explicit concurrent mark sweep GC freed 17596(1255KB) AllocSpace objects, 19(304KB) LOS objects, 40% free, 13MB/22MB, paused 15.682ms total 158.274ms
,03-19 12:52:57.124   826  1883 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4464 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,03-19 12:52:57.162  1731  2558 W GCoreFlp: No location to return for getLastLocation()
,03-19 12:52:57.163  1731  2558 W GCoreFlp: No location to return for getLastLocation()
03-19 12:52:57.169   826  1359 I ActivityManager: Killing 3985:com.lge.eula/1000 (adj 15): empty #11
,03-19 12:52:57.220   826  2177 W libprocessgroup: failed to open /acct/uid_1000/pid_3985/cgroup.procs: No such file or directory
,03-19 12:52:57.364  4464  4464 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,03-19 12:52:57.401  4334  4434 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1623028992
,03-19 12:52:57.421  4334  4434 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-19 12:52:57.421  4334  4434 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-19 12:52:57.421  4334  4434 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-19 12:52:57.421  4334  4434 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-19 12:52:57.421  4334  4434 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-19 12:52:57.421  4334  4434 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea27e9 added. We now have 1 listener(s)
,03-19 12:52:57.422   826  1876 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-19 12:52:57.427  4334  4434 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
03-19 12:52:57.430  4334  4434 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
03-19 12:52:57.431  4334  4434 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-19 12:52:57.431  4334  4434 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
03-19 12:52:57.439  4334  4434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-19 12:52:57.439  4334  4434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-19 12:52:57.439  4334  4434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-19 12:52:57.439  4334  4434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
03-19 12:52:57.439  4334  4434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-19 12:52:57.439  4334  4434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-19 12:52:57.439  4334  4434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-19 12:52:57.439  4334  4434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-19 12:52:57.439  4334  4434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-19 12:52:57.439  4334  4434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-19 12:52:57.439  4334  4434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-19 12:52:57.439  4334  4434 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a67b9c added. We now have 1 listener(s)
,03-19 12:52:57.440  4334  4434 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-19 12:52:57.454  2010  2056 D BluetoothAdapterService(214083283): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a5b3841
03-19 12:52:57.454  4334  4434 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-19 12:52:57.468  4334  4434 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-19 12:52:57.468  4334  4434 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-19 12:52:57.473  4334  4434 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-19 12:52:57.473   826  1821 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-19 12:52:57.474  4334  4434 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
03-19 12:52:57.478  2010  2056 D BluetoothAdapterService(214083283): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a5b3841
03-19 12:52:57.478  4334  4434 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-19 12:52:57.478  4334  4434 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-19 12:52:57.478  4334  4434 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-19 12:52:57.478  4334  4434 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-19 12:52:57.478  4334  4434 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-19 12:52:57.478  4334  4434 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-19 12:52:57.478  4334  4434 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-19 12:52:57.478  4334  4434 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-19 12:52:57.478  4334  4434 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-19 12:52:57.479  4334  4434 D io.jxcore.node.ConnectivityMonitor: start: OK
03-19 12:52:57.480  4334  4434 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-19 12:52:57.490   826  1022 D BluetoothManagerService: Message: 20
03-19 12:52:57.490   826  1022 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1827c93c:true
03-19 12:52:57.492  2010  3380 D BluetoothAdapterService(214083283): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a5b3841
03-19 12:52:57.494  2010  2045 D BluetoothAdapterService(214083283): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a5b3841
,03-19 12:52:57.619   826  1883 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4487 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-19 12:52:57.649  4334  4334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-19 12:52:57.654  4464  4464 V LGMDMManager: Create singleton instance
03-19 12:52:57.656  4334  4334 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-19 12:52:57.730  4487  4487 D UEI.SmartControl: Quickset Services start...
,03-19 12:52:57.739  4487  4487 I UEI.SmartControl: Manufacture = LGE
03-19 12:52:57.741  4464  4464 I AudioManager: getMode name:com.lge.qremote
03-19 12:52:57.743  4487  4487 D UEI.SmartControl: File observer start...
,03-19 12:52:57.744  4487  4487 E UEI.SmartControl: IR Port is disabled: false
03-19 12:52:57.744  4487  4487 D UEI.SmartControl: Starting file observer...
03-19 12:52:57.744  4487  4487 D UEI.SmartControl: Extracting JNI libs...
03-19 12:52:57.745  4487  4487 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
03-19 12:52:57.750  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.750  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.755  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.755  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
,03-19 12:52:57.761  4464  4464 I AudioManager: getMode name:com.lge.qremote
03-19 12:52:57.778  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.778  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
,03-19 12:52:57.779  4334  4350 I art     : CheckpointMarkThreadRoots callback created = 0xb07f32b0
03-19 12:52:57.784  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.784  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.790  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.790  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.795  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.796  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
,03-19 12:52:57.800  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.800  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.804  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.804  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.809  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.809  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
,03-19 12:52:57.814  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.814  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.818  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.818  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.823  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.827  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
,03-19 12:52:57.831  4334  4350 I art     : CheckpointMarkThreadRoots callback created = 0xb07f3270
03-19 12:52:57.831  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.831  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.837  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.837  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.842  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.842  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.849  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.849  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.854  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,03-19 12:52:57.854  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.858  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.858  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.862  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.862  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.867  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.867  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.873  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.873  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.877  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.877  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.884  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.884  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
,03-19 12:52:57.889  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.889  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.894  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.894  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.900  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.900  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.905  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.905  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.910  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.910  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.913  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.913  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.918  3108  3108 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
03-19 12:52:57.918  3108  3108 V MmsSystemEventReceiver: ANY_DATA_STATE event received: DISCONNECTED
03-19 12:52:57.922  4441  4441 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
03-19 12:52:57.922  4441  4441 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
03-19 12:52:57.923  4441  4441 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
03-19 12:52:57.925  4441  4441 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
03-19 12:52:57.937  4441  4506 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,03-19 12:52:57.938  4441  4507 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
03-19 12:52:57.977   826  1875 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=4508 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,03-19 12:52:58.012   826   961 I ActivityManager: Waited long enough for: ServiceRecord{3ab08f46 u0 com.lge.mlt/.MltMonitorService}
,03-19 12:52:58.032  4487  4487 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
03-19 12:52:58.033  4487  4487 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,03-19 12:52:58.033  4487  4487 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
03-19 12:52:58.086  4508  4508 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-19 12:52:58.086  4508  4508 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
03-19 12:52:58.087  4508  4508 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,03-19 12:52:58.088  4487  4487 I UEI.SmartControl: --- Selecting new region: 2
03-19 12:52:58.089  4508  4508 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
03-19 12:52:58.089  4508  4508 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-19 12:52:58.091  4487  4487 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
03-19 12:52:58.102  4487  4487 D UEI.SmartControl: Platform has CIR...
03-19 12:52:58.103  4487  4487 D UEI.SmartControl: NO CIR support, need to check package...
03-19 12:52:58.104  4487  4487 I UEI.SmartControl: Model: LG-D722 uses JNI
,03-19 12:52:58.107  4487  4487 D UEI.SmartControl: QS Service created
,03-19 12:52:58.149   826  1900 I ActivityManager: Process com.google.android.youtube (pid 4129) has died
,03-19 12:52:58.186  4487  4487 E UEI.SmartControl: QS start get config
,03-19 12:52:58.201  4508  4508 I IndexDatabaseHelper: Using schema version: 115
,03-19 12:52:58.203  4508  4508 I IndexDatabaseHelper: Index is fine
03-19 12:52:58.248  4487  4487 D UEI.SmartControl: Loading JNI Libs...
,03-19 12:52:58.251  4487  4487 D UEI.SmartControl:  configuring local db...
03-19 12:52:58.323   826  1972 I art     : Explicit concurrent mark sweep GC freed 31848(1575KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 2.312ms total 202.478ms
,03-19 12:52:58.361  4508  4508 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,03-19 12:52:58.411  4508  4508 D WiFiOffLoadBroadcast: MCCMNC not supported: null
03-19 12:52:58.459   826  1348 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4527 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,03-19 12:52:58.479  4487  4487 D UEI.SmartControl:  ---- Has DB8: true
,03-19 12:52:58.487  4487  4487 D UEI.SmartControl: QS start statue = true Error code = 0
03-19 12:52:58.487  4487  4487 D UEI.SmartControl: QS version = v2.7.11.1_RC1
03-19 12:52:58.488  4487  4487 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
03-19 12:52:58.493  4487  4487 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
,03-19 12:52:58.509  4334  4485 W jxcore-log: Initializing JXcore engine
,03-19 12:52:58.510  4334  4485 W jxcore-log: JXcore engine is ready
03-19 12:52:58.511  4487  4487 W irrc_jni: IRRCPlayer_nativeInit ++ 
03-19 12:52:58.511  4487  4487 D irrcClient: IrrcClient ++ 
03-19 12:52:58.511  4487  4487 D irrcClient: getIrrcService ++ 
03-19 12:52:58.512  4487  4487 D irrcClient: getIrrcService -- 
03-19 12:52:58.512  4487  4487 D irrcClient: IrrcClient -- 
03-19 12:52:58.512  4487  4487 W irrc_jni: IRRCPlayer_nativeInit -- 
03-19 12:52:58.530  4487  4487 D UEI.SmartControl: Services init done
,03-19 12:52:58.534  4487  4487 D UEI.SmartControl: QS Service init finished
03-19 12:52:58.538  4487  4545 I UEI.SmartControl: Device manager: loading config....
03-19 12:52:58.540  4487  4487 D UEI.SmartControl: QS Service version name: 0.1.73
03-19 12:52:58.541  4487  4487 D UEI.SmartControl: QS Service version code: 1073
03-19 12:52:58.542  4487  4487 D UEI.SmartControl: Service requested: Control
,03-19 12:52:58.549  4487  4545 D UEI.SmartControl: Config is loaded...
03-19 12:52:58.586  4487  4544 D UEI.SmartControl:  ----- QS SDK is ready!!!
03-19 12:52:58.587  4487  4544 I UEI.SmartControl: Notify AllClients services are ready: 0
,03-19 12:52:58.589  4487  4487 D UEI.SmartControl: Request IControl service: devices are loaded...
03-19 12:52:58.592  4487  4487 D UEI.SmartControl: Internal service binding...
03-19 12:52:58.597  4487  4502 D UEI.SmartControl: -----IControl: 11
03-19 12:52:58.598  4487  4502 D UEI.SmartControl: Caller: com.lge.qremote
,03-19 12:52:58.599  4487  4502 D UEI.SmartControl: ------------ IControl registerCallback...
03-19 12:52:58.600  4487  4502 I UEI.SmartControl: Registering callback...
03-19 12:52:58.601  4487  4503 D UEI.SmartControl: -----IControl: 19
03-19 12:52:58.602  4487  4503 D UEI.SmartControl: Caller: com.lge.qremote
03-19 12:52:58.603  4487  4503 I UEI.SmartControl: Registering Services Ready callback...
03-19 12:52:58.604  4487  4503 I UEI.SmartControl: Notify client services are ready...
03-19 12:52:58.607  4487  4502 D UEI.SmartControl: -----IControl: 8
03-19 12:52:58.608  4487  4502 D UEI.SmartControl: Caller: com.lge.qremote
03-19 12:52:58.616   826  1875 I ActivityManager: Killing 4098:com.google.android.talk/u0a61 (adj 15): empty #11
,03-19 12:52:58.622  4485  4485 W Thread-455: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6284]" dev="sockfs" ino=6284 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-19 12:52:58.622  4485  4485 W Thread-455: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-19 12:52:58.622  4485  4485 W Thread-455: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8299]" dev="sockfs" ino=8299 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-19 12:52:58.622  4485  4485 W Thread-455: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
03-19 12:52:58.622  4485  4485 W Thread-455: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
03-19 12:52:58.622  4485  4485 W Thread-455: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[20812]" dev="sockfs" ino=20812 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
03-19 12:52:58.657  4527  4527 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,03-19 12:52:58.662  4334  4485 W jxcore-log: Starting JXcore engine
03-19 12:52:58.729   826  1875 I ActivityManager: Killing 4006:com.lge.bnr/1000 (adj 15): empty #12
,03-19 12:52:58.803  4334  4485 W jxcore-log: Platform android
03-19 12:52:58.803  4334  4485 W jxcore-log: 
,03-19 12:52:58.803  4334  4485 W jxcore-log: Process ARCH arm
03-19 12:52:58.803  4334  4485 W jxcore-log: 
03-19 12:52:58.871   826  1900 W libprocessgroup: failed to open /acct/uid_1000/pid_4006/cgroup.procs: No such file or directory
,03-19 12:52:58.873   826  2177 W libprocessgroup: failed to open /acct/uid_10061/pid_4098/cgroup.procs: No such file or directory
03-19 12:52:58.876  4508  4508 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
03-19 12:52:58.876  4508  4508 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
03-19 12:52:58.876  4508  4508 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
03-19 12:52:58.876  4508  4508 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
03-19 12:52:58.877  4508  4508 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
03-19 12:52:58.894  4508  4508 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,03-19 12:52:58.894  4508  4508 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
03-19 12:52:58.894  4508  4508 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
03-19 12:52:58.895  4508  4508 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
03-19 12:52:58.895  4508  4508 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
03-19 12:52:58.895  4508  4508 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
03-19 12:52:58.900  4508  4508 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
03-19 12:52:58.902  4508  4508 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,03-19 12:52:58.906  4508  4508 D WiFiOffLoadBroadcast: MCCMNC not supported: null
03-19 12:52:58.908  4527  4527 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
03-19 12:52:58.911  4441  4441 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
03-19 12:52:58.911  4441  4441 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
03-19 12:52:58.913  4441  4441 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
03-19 12:52:58.915  4441  4441 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
03-19 12:52:58.918  4508  4508 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,03-19 12:52:58.921  4441  4551 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
03-19 12:52:58.922  4441  4552 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
03-19 12:52:58.924  4508  4508 D WiFiOffLoadBroadcast: MCCMNC not supported: null
03-19 12:52:58.925  4441  4552 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
03-19 12:52:58.939  4527  4527 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,03-19 12:52:58.942  4527  4527 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
03-19 12:52:58.942  4527  4527 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
03-19 12:52:58.961  4464  4464 I AudioManager: getMode name:com.lge.qremote
,03-19 12:52:59.010   826  1348 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4557 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,03-19 12:52:59.012   826  1348 I ActivityManager: Killing 3145:com.android.defcontainer/u0a4 (adj 15): empty #11
03-19 12:52:59.116  4334  4485 I jxcore-log: JXcore Cordova bridge is ready!
03-19 12:52:59.116  4334  4485 I jxcore-log: 
,03-19 12:52:59.116  4334  4485 W jxcore-log: JXcore engine is started
03-19 12:52:59.120   826  1803 W libprocessgroup: failed to open /acct/uid_10004/pid_3145/cgroup.procs: No such file or directory
03-19 12:52:59.120  4334  4434 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
03-19 12:52:59.123  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
03-19 12:52:59.123  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
03-19 12:52:59.123  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
03-19 12:52:59.123  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
03-19 12:52:59.123  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
03-19 12:52:59.124  4334  4334 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
03-19 12:52:59.138  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
03-19 12:52:59.138  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,03-19 12:52:59.138  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
03-19 12:52:59.138  1804  1956 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
03-19 12:52:59.138  1804  1956 D LEDHandler: Battery Level Remaining: 100%
03-19 12:52:59.138  1804  1956 D LEDHandler: Battery Temp: 289, mChargingStatus=5, mChargingStop=false
03-19 12:52:59.139   826   826 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
03-19 12:52:59.140   826   826 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
03-19 12:52:59.140   826  1313 D WifiController: battery changed pluggedType: 2
03-19 12:52:59.140  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
03-19 12:52:59.140  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
03-19 12:52:59.141  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
03-19 12:52:59.141  2010  3379 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-19 12:52:59.157   486   486 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,03-19 12:52:59.302  4557  4557 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,03-19 12:52:59.304  4557  4557 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
03-19 12:52:59.312  4557  4557 V [BNRBootReceiver]: Boot Receiver Return
03-19 12:52:59.314  4557  4557 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
03-19 12:52:59.314  4508  4508 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,03-19 12:52:59.319  4508  4508 D WiFiOffLoadBroadcast: MCCMNC not supported: null
03-19 12:52:59.327  4508  4508 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,03-19 12:52:59.330  4508  4508 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
03-19 12:52:59.333  4508  4508 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
03-19 12:52:59.338  4508  4508 D WiFiOffLoadBroadcast: MCCMNC not supported: null
03-19 12:52:59.356  4508  4508 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,03-19 12:52:59.359  4236  4271 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
03-19 12:52:59.364  4508  4508 D WiFiOffLoadBroadcast: MCCMNC not supported: null
03-19 12:52:59.373  4464  4464 I AudioManager: getMode name:com.lge.qremote
,03-19 12:52:59.375   826  1900 I ActivityManager: Killing 4236:com.google.android.gm/u0a53 (adj 15): empty #11
03-19 12:52:59.511   826  2177 W libprocessgroup: failed to open /acct/uid_10053/pid_4236/cgroup.procs: No such file or directory
,03-19 12:52:59.527  3108  3108 V SmsReceiverService: onStart: #1 mResultCode: -1 = Activity.RESULT_OK
,03-19 12:52:59.528  3108  4583 D MmsConfig: isNotAllowedSms: currentUser:0
03-19 12:52:59.528  3108  4583 D MmsConfig: isNotAllowedSms: UserHandle.myUserId():0
03-19 12:52:59.528  3108  4583 D MmsConfig: isUserMode:false
03-19 12:52:59.528  3108  4583 D SmsReceiverService: handleMessage isUserMode:false
03-19 12:52:59.533  3108  4583 V SmsReceiverService: handleMessage action: com.android.mms.transaction.SEND_MESSAGE error: 0
03-19 12:52:59.537  3108  4583 D SmsReceiverService: [LGE] handleSendMessage Send messages in queue
,03-19 12:52:59.556  1877  1877 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = lge.intent.action.UNREAD_MESSAGES
,03-19 12:52:59.579  1877  2122 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
03-19 12:52:59.579  1877  2122 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
03-19 12:52:59.579  1877  2122 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
,03-19 12:52:59.581  1877  2122 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
03-19 12:52:59.614  4508  4508 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,03-19 12:52:59.620  4508  4508 D WiFiOffLoadBroadcast: MCCMNC not supported: null
03-19 12:52:59.625  4527  4527 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
03-19 12:52:59.625  4527  4527 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
03-19 12:52:59.625  4527  4527 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,03-19 12:52:59.631  4508  4508 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
03-19 12:52:59.634  4508  4508 D WiFiOffLoadBroadcast: MCCMNC not supported: null
03-19 12:52:59.639  4527  4527 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
03-19 12:52:59.639  4527  4527 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
03-19 12:52:59.639  4527  4527 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,03-19 12:52:59.646  4508  4508 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
03-19 12:52:59.649  4508  4508 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,03-19 12:52:59.659  4508  4508 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.hardware.usb.action.USB_STATE
03-19 12:52:59.659  4508  4508 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
03-19 12:52:59.659  4508  4508 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
03-19 12:52:59.659  4508  4508 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
03-19 12:52:59.660  4508  4508 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,03-19 12:52:59.661  4508  4508 D UsbSettingsReceiver: [AUTORUN] onReceive() : getDefaultFunction = ptp_only
03-19 12:52:59.661  4508  4508 D UsbSettingsReceiver: [AUTORUN] onReceive() : USB_FUNCTION_CDROM_STORAGE = false
03-19 12:52:59.661  4508  4508 D UsbSettingsReceiver: [AUTORUN] onReceive() : mDirectAutorun = true
03-19 12:52:59.661  4508  4508 D UsbSettingsReceiver: [AUTORUN] onReceive() : mActivityUsbModeChange = false
03-19 12:52:59.662  4508  4508 D UsbSettingsReceiver: [AUTORUN] onReceive() : mActivityFinish = false
03-19 12:52:59.662  4508  4508 D UsbSettingsReceiver: [AUTORUN] onReceive() : ===== USB Configured =====
03-19 12:52:59.662  4508  4508 D UsbSettingsControl: [AUTORUN] setUsbConnected() : connected=true
03-19 12:52:59.662  4508  4508 D UsbSettingsReceiver: [AUTORUN] onReceive() : checkQmicm = ptp_only,adb
03-19 12:52:59.669  4508  4508 D UsbSettingsReceiver: [AUTORUN] : topPackageName=com.test.thalitest
03-19 12:52:59.669  4508  4508 D UsbSettingsReceiver: [AUTORUN] : topClassName=com.test.thalitest.MainActivity
03-19 12:52:59.682  4508  4508 D UsbSettingsReceiver: [AUTORUN] Not exist com.android.LGSetupWizard
03-19 12:52:59.682  4508  4508 D UsbSettingsReceiver: [AUTORUN] setUsbConnect() : mUsbSettingsRun = false
,03-19 12:52:59.686  4508  4508 D UsbSettingsReceiver: [AUTORUN] startUsbSettings() : deviceProvisioned=1
03-19 12:52:59.695  2718  2718 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-19 12:52:59.698  4527  4527 I PCSuite : [StartReceiver]USB CONNECTED ver UsbManger : ptp_only
03-19 12:52:59.699  4527  4527 I PCSuite : [StartReceiver]isUsbPCSuiteMode : false
03-19 12:52:59.699  4527  4527 D PCSuite : [StartReceiver][checkEUTStatus] eutStatus = 
03-19 12:52:59.699  4527  4527 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
03-19 12:52:59.699  4527  4527 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
03-19 12:52:59.749   826   846 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=4585 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,03-19 12:52:59.965  4585  4585 I DigitalAppWidgetProvider: onReceive: android.intent.action.ALARM_CHANGED
,03-19 12:52:59.969   826  1876 I ActivityManager: Killing 4296:com.android.vending/u0a36 (adj 15): empty #11
03-19 12:53:00.036  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,03-19 12:53:00.038  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
03-19 12:53:00.043  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
03-19 12:53:00.046  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
03-19 12:53:00.047  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
03-19 12:53:00.048  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
,03-19 12:53:00.050  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
03-19 12:53:00.081   826   846 W libprocessgroup: failed to open /acct/uid_10036/pid_4296/cgroup.procs: No such file or directory
03-19 12:53:00.081  2899  2899 D WeatherAncestor: 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:53:0
,03-19 12:53:00.083  2899  2899 D UpdateThreadPoolManager: 2 : This is isUpdating : false
03-19 12:53:00.095  1372  1372 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,03-19 12:53:00.098  1877  1877 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-19 12:53:00.103  1877  1877 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-19 12:53:00.104  1877  1877 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
03-19 12:53:00.104   826  1288 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-19 12:53:00.106  2899  2899 D Weather_cast: 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
03-19 12:53:00.106  2899  2899 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:53:0
03-19 12:53:00.106  2899  2899 D WeatherService: 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
03-19 12:53:00.115  1839  1839 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,03-19 12:53:00.130   826  1803 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
,03-19 12:53:00.133  1372  1372 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
03-19 12:53:00.135  2899  2899 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
03-19 12:53:00.141  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
03-19 12:53:00.141  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
03-19 12:53:00.141  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
03-19 12:53:00.141  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
03-19 12:53:00.141  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
03-19 12:53:00.141  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
03-19 12:53:00.141  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
03-19 12:53:00.141  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
03-19 12:53:00.141  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
,03-19 12:53:00.142  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
03-19 12:53:00.142  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
03-19 12:53:00.142  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
03-19 12:53:00.142  1372  1372 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
03-19 12:53:00.144  3684  3684 D AlertReceiver: onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
03-19 12:53:00.159  2899  2899 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
03-19 12:53:00.159  2899  2899 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,03-19 12:53:00.165  3684  4602 D AlertService: 0 Action = android.intent.action.PROVIDER_CHANGED
03-19 12:53:00.197  2899  2899 D WeatherService: 2 : TimeTick Intent has been received, Time(hour:min:sec) 12:53:0
03-19 12:53:00.197  2899  2899 D WeatherService: 2 : TimeTick Intent And Screen On
03-19 12:53:00.198  2899  2899 D WeatherService: 2 : SDK version : 21
,03-19 12:53:00.199   826  1845 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
03-19 12:53:00.200  2899  2899 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
03-19 12:53:00.202  2899  2899 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
03-19 12:53:00.202  2899  2899 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
03-19 12:53:00.202   826   826 D administrator: Handling package changes for user 0
03-19 12:53:00.204  2899  2899 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
03-19 12:53:00.207  2899  2899 D UpdateThreadPoolManager: 2 : This is isUpdating : false
03-19 12:53:00.207  2899  2899 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
03-19 12:53:00.207  2899  2899 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
03-19 12:53:00.207  2899  2899 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
03-19 12:53:00.208  2899  2899 D WeatherTheme: 2 : Fixed theme : optimus
03-19 12:53:00.214  1785  1800 I art     : CheckpointMarkThreadRoots callback created = 0xaaf24c00
,03-19 12:53:00.217  2899  2899 D WeatherReflect: 2 : Map key string is -2
03-19 12:53:00.220  2899  2899 D lim     : 2 : time = 12:53
03-19 12:53:00.220  2899  2899 I WeatherReflect: Model Name : LG-D722
03-19 12:53:00.220  2899  2899 D WeatherTheme: 2 : Different view - status_min_formatted : 52 != 53
03-19 12:53:00.220  2899  2899 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
03-19 12:53:00.221  3684  3684 E AgendaWidgetManager: [updateWidgets] 
03-19 12:53:00.222  2899  2899 D WeatherReflect: 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
03-19 12:53:00.222  2899  2899 D Theme   : strTheme: com.lge.launcher2.theme.optimus
03-19 12:53:00.222  2899  2899 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
03-19 12:53:00.222  2899  2899 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
03-19 12:53:00.222  2899  2899 D Weather4x2_optimus: currentPackage=com.lge.sizechangable.weather.theme.optimus
03-19 12:53:00.224  3684  3684 D MonthWidgetProvider: [onReceive]
03-19 12:53:00.224  3684  3684 D CalendarWidgetProvider: [onReceive]
03-19 12:53:00.224  3684  3684 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
03-19 12:53:00.245  3684  3684 D CalendarTypeController: [onCreate] mContext.getPackageName() = com.android.calendar
,03-19 12:53:00.256  1785  1800 I art     : CheckpointMarkThreadRoots callback created = 0xb042d690
03-19 12:53:00.259  1877  1877 I [LGHome]Launcher: [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,03-19 12:53:00.261  2899  2899 D Weather4x2_optimus: [[[[[[Theme package!!]]]]]] RemoteViews are created 2
03-19 12:53:00.261  2899  2899 D Weather4x2_optimus: widgetType = 1, orientation = 1
03-19 12:53:00.261  2899  2899 D Weather4x2_optimus: forecast size is 0
03-19 12:53:00.262  2899  2899 D Theme   : strTheme: com.lge.launcher2.theme.optimus
03-19 12:53:00.262  2899  2899 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
03-19 12:53:00.262  2899  2899 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
03-19 12:53:00.262  2899  2899 D Theme   : strTheme: com.lge.launcher2.theme.optimus
03-19 12:53:00.262  2899  2899 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
03-19 12:53:00.262  2899  2899 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
03-19 12:53:00.263  2899  2899 D Theme   : strTheme: com.lge.launcher2.theme.optimus
03-19 12:53:00.263  2899  2899 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
03-19 12:53:00.263  2899  2899 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
03-19 12:53:00.263  2899  2899 I Theme_WeatherAncestor_optimus: WEATHER_CP_ACCU : 
03-19 12:53:00.263  2899  2899 I Theme_WeatherAncestor_optimus: weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
03-19 12:53:00.263  2899  2899 D Theme   : strTheme: com.lge.launcher2.theme.optimus
03-19 12:53:00.263  2899  2899 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
03-19 12:53:00.263  2899  2899 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
03-19 12:53:00.263  2899  2899 D Theme_WeatherAncestor_optimus: setTouchIntent, appWidgetId: 2
03-19 12:53:00.266  2899  2899 D Theme_WeatherAncestor_optimus: url is : null
03-19 12:53:00.269  2899  2899 D Theme   : strTheme: com.lge.launcher2.theme.optimus
03-19 12:53:00.269  2899  2899 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
03-19 12:53:00.269  2899  2899 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
03-19 12:53:00.270  2899  2899 D WeatherAncestor: 2 : update view, appWidgetId: 2
03-19 12:53:00.272  2899  2899 D WeatherService: 2 : TimeTick Intent has been processed, Time(hour:min:sec) 12:53:0
,03-19 12:53:00.287  3684  3684 D WeekWidgetProvider: [onReceive]
03-19 12:53:00.287  3684  3684 D CalendarWidgetProvider: [onReceive]
03-19 12:53:00.287  3684  3684 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,03-19 12:53:00.300  3684  3684 D CalendarTypeController: [onCreate] mContext.getPackageName() = com.android.calendar
,03-19 12:53:00.310  1372  1372 I [SystemUI]SafeModeBroadcastReceiver: onReceive = com.lge.statusbar.bootcompleted
03-19 12:53:00.313  3684  3684 D CalendarWeatherReceiver: Get action=com.lge.calendar.action.WEATHER_SERVICE_START
03-19 12:53:00.327  4557  4557 E MediaScanReceiver: media scanning start or checking
,03-19 12:53:00.380   826  1900 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=4609 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-19 12:53:00.463   826   826 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
03-19 12:53:00.463   826   826 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-19 12:53:00.464   826   826 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-19 12:53:00.472   826   826 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
03-19 12:53:00.492   826   826 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-19 12:53:00.493   826   826 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@267cab71
,03-19 12:53:00.582   826   960 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-19 12:53:00.682  1877  1877 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,03-19 12:53:00.698  1785  1785 D LCardEmulationManager: getHceAppCount hostAppNum : 0
03-19 12:53:00.698  1785  1785 D LCardEmulationManager: getDefaultRoute
,03-19 12:53:00.744   826   961 I ActivityManager: Waited long enough for: ServiceRecord{33b61125 u0 com.android.calendar/.alerts.InitAlarmsService}
,03-19 12:53:00.752   826   960 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
03-19 12:53:00.780  4609  4609 I MusicStore: Database version: 120
,03-19 12:53:00.788  1877  1877 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
03-19 12:53:00.789  1877  1877 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
03-19 12:53:00.801   294   352 I ThermalEngine: Sensor:pa_therm0:32000 mC
,03-19 12:53:00.826  1731  1731 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,03-19 12:53:00.873   826   960 D LocationProviderProxy: applying state to connected service
,03-19 12:53:00.897   246   386 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
03-19 12:53:00.897   246   386 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
03-19 12:53:00.897   246   386 W Vold    : Returning OperationFailed - no handler for errno 0
,03-19 12:53:00.900  4609  4609 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
03-19 12:53:01.016   246   386 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
03-19 12:53:01.016   246   386 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,03-19 12:53:01.016   246   386 W Vold    : Returning OperationFailed - no handler for errno 0
03-19 12:53:01.016  4609  4609 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
03-19 12:53:01.018   246   386 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
03-19 12:53:01.018   246   386 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
03-19 12:53:01.018   246   386 W Vold    : Returning OperationFailed - no handler for errno 0
03-19 12:53:01.019  4609  4609 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
03-19 12:53:01.053  4609  4609 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-19 12:53:01.053  4609  4609 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-19 12:53:01.103  4609  4609 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-19 12:53:01.206  4609  4609 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-19 12:53:01.208  4609  4609 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@391e7c00: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-19 12:53:01.209  4609  4609 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-19 12:53:01.210  4609  4609 D AndroidMusic: GMSCore installation verified
03-19 12:53:01.218  4609  4609 I ConfigStore: Config Database version: 1
,03-19 12:53:01.364  4609  4609 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,03-19 12:53:01.374  4585  4585 D ToneMappingReceiver: Enter doAlarmRingToneUriMapping()
03-19 12:53:01.394  4585  4585 D ToneMappingReceiver: do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
03-19 12:53:01.395  4585  4585 D CommonUtil: Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
,03-19 12:53:01.398  4585  4585 D CommonUtil: getFinededDefaultTone() -> backup ringtone value : null
03-19 12:53:01.398  4585  4585 D CommonUtil: Exit getMatchedBackupTone() value is null
03-19 12:53:01.399  4585  4585 D ToneMappingReceiver: do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
03-19 12:53:01.399  4585  4585 D ToneMappingReceiver: Enter doAlarmRingToneUriMapping(), return value is 0
03-19 12:53:01.399  4585  4585 D ToneMappingReceiver: Alarm Success count is 0
03-19 12:53:01.402  4585  4585 D ToneMappingReceiver: Timer Success count is 0
03-19 12:53:01.407  3684  3684 I MediaScannerReceiver: Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///system/media
,03-19 12:53:01.413  3684  4650 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
03-19 12:53:01.414  3684  4650 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
03-19 12:53:01.416  4557  4557 E MediaScanReceiver: media scanning finished
03-19 12:53:01.424  4557  4557 I com.lge.bnr.receiver.MediaScanReceiver: android.intent.action.MEDIA_SCANNER_FINISHED
,03-19 12:53:01.445  3684  4650 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,03-19 12:53:01.450  3684  4650 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
03-19 12:53:01.454  3684  4650 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
03-19 12:53:01.458  3684  4650 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
03-19 12:53:01.461  3684  4650 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,03-19 12:53:01.473  3684  4650 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
03-19 12:53:01.476  3684  4650 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,03-19 12:53:01.481  3684  4650 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
03-19 12:53:01.488  3684  4650 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,03-19 12:53:01.493  3533  3610 I art     : Explicit concurrent mark sweep GC freed 3047(119KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 572us total 44.760ms
03-19 12:53:01.493  3684  4650 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
03-19 12:53:01.497  4609  4609 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
03-19 12:53:01.497  3684  4650 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
03-19 12:53:01.502  3684  4650 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,03-19 12:53:01.506  3684  4650 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
03-19 12:53:01.510  3684  4650 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
03-19 12:53:01.512  4609  4609 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
03-19 12:53:01.515  3684  4650 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,03-19 12:53:01.523  3684  4650 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
03-19 12:53:01.523  3684  4650 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
03-19 12:53:01.559  3684  4650 I AlertUtils: set default noti to content://media/internal/audio/media/38
,03-19 12:53:01.560  3684  4650 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
03-19 12:53:01.563  4557  4557 E MediaScanReceiver: media scanning start or checking
03-19 12:53:01.571  4609  4628 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
,03-19 12:53:01.575  4585  4585 D ToneMappingReceiver: Enter doAlarmRingToneUriMapping()
03-19 12:53:01.577  4585  4585 D ToneMappingReceiver: do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
03-19 12:53:01.577  4585  4585 D CommonUtil: Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
03-19 12:53:01.577  4585  4585 D CommonUtil: getFinededDefaultTone() -> backup ringtone value : null
03-19 12:53:01.577  4585  4585 D CommonUtil: Exit getMatchedBackupTone() value is null
03-19 12:53:01.577  4585  4585 D ToneMappingReceiver: do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
03-19 12:53:01.577  4585  4585 D ToneMappingReceiver: Enter doAlarmRingToneUriMapping(), return value is 0
03-19 12:53:01.577  4585  4585 D ToneMappingReceiver: Alarm Success count is 0
03-19 12:53:01.587  4585  4585 D ToneMappingReceiver: Timer Success count is 0
,03-19 12:53:01.589   826   846 I ActivityManager: Killing 4391:com.lge.qmemoplus/1000 (adj 15): empty #11
03-19 12:53:01.810   826  1821 W libprocessgroup: failed to open /acct/uid_1000/pid_4391/cgroup.procs: No such file or directory
,03-19 12:53:01.811  3684  3684 I MediaScannerReceiver: Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
03-19 12:53:01.816  3684  4661 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
03-19 12:53:01.816  3684  4661 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
03-19 12:53:01.817  4557  4557 E MediaScanReceiver: media scanning finished
03-19 12:53:01.817  4557  4557 I com.lge.bnr.receiver.MediaScanReceiver: android.intent.action.MEDIA_SCANNER_FINISHED
03-19 12:53:01.835  3684  4661 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,03-19 12:53:01.839  3684  4661 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
03-19 12:53:01.846  3684  4661 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
03-19 12:53:01.850  3684  4661 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,03-19 12:53:01.854  3684  4661 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
03-19 12:53:01.892   826  1803 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=4663 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-19 12:53:02.002  4663  4663 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-19 12:53:02.024   826   843 I art     : Explicit concurrent mark sweep GC freed 22354(1186KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.535ms total 167.645ms
,03-19 12:53:02.028  3684  4661 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
03-19 12:53:02.032  3684  4661 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
03-19 12:53:02.036  3684  4661 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
03-19 12:53:02.040  3684  4661 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,03-19 12:53:02.046  3684  4661 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
03-19 12:53:02.050  3684  4661 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
03-19 12:53:02.056  3684  4661 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,03-19 12:53:02.060  3684  4661 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
03-19 12:53:02.064  3684  4661 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
03-19 12:53:02.067  3684  4661 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,03-19 12:53:02.071  3684  4661 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
03-19 12:53:02.071  3684  4661 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
03-19 12:53:02.074  3684  4661 I AlertUtils: set default noti to content://media/internal/audio/media/38
03-19 12:53:02.074  3684  4661 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
03-19 12:53:02.080  4663  4663 D CalendarProvider2: [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2f35366a
,03-19 12:53:02.102  4663  4663 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
,03-19 12:53:02.105  4663  4663 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@b505e37(com.android.providers.calendar.CalendarProvider2@2f35366a)
03-19 12:53:02.108  4663  4663 D CalendarProviderBroadcastReceiver: Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
03-19 12:53:02.109  4663  4663 D CalendarProviderBroadcastReceiver: [IntentService] WakeLock acquire, start IntentSerivce
03-19 12:53:02.120  4663  4663 D CalendarProvider2: CalendarProviderIntentService.onCreate()
03-19 12:53:02.122  4663  4682 D CalendarProvider2: Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
,03-19 12:53:02.126  4663  4682 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
03-19 12:53:02.167  4663  4682 D CalendarProvider2: [IntentService] Release Lock
,03-19 12:53:02.170  4663  4663 D CalendarProvider2: CalendarProviderIntentService.onDestroy()
03-19 12:53:02.201  4609  4662 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,03-19 12:53:02.205   826   846 I ActivityManager: Killing 4441:com.lge.lgdmsclient/1000 (adj 15): empty #11
03-19 12:53:02.274   826  1794 W libprocessgroup: failed to open /acct/uid_1000/pid_4441/cgroup.procs: No such file or directory
,03-19 12:53:02.290  1731  2558 W GCoreFlp: No location to return for getLastLocation()
03-19 12:53:02.290  1731  4683 W FusedLocationProvider: location=null
,03-19 12:53:02.412   826  1876 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=4688 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,03-19 12:53:02.575  4688  4688 D PhoneMonitor: Register our PhoneStateListener
,03-19 12:53:02.624  1731  4709 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-19 12:53:02.658  4688  4688 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,03-19 12:53:02.663  4688  4688 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
03-19 12:53:02.666  4688  4688 D TelephonyAutoProfiling: [parse] Load xml
03-19 12:53:02.673  4688  4688 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
03-19 12:53:02.673  4688  4688 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,03-19 12:53:02.689  4688  4688 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,03-19 12:53:02.782   826  1845 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4711 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-19 12:53:02.856  4711  4711 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-19 12:53:02.932   826  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{111ebc49 type 2 when 70756 com.google.android.gms} when 70756
,03-19 12:53:03.137   826  1348 I ActivityManager: Process com.android.settings (pid 4508) has died
,03-19 12:53:03.226  4711  4734 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,03-19 12:53:03.229  4711  4734 I Babel_SMS: MmsConfig.loadMmsSettings
03-19 12:53:03.246  4711  4734 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
03-19 12:53:03.246  4711  4734 I Babel_SMS: MmsConfig.loadFromDatabase
,03-19 12:53:03.262   826   961 I ActivityManager: Waited long enough for: ServiceRecord{22c1ca9b u0 com.lge.springcleaning/.service.AppCleanupService}
,03-19 12:53:03.281  4711  4734 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-19 12:53:03.281  4711  4734 I Babel_SMS: MmsConfig.loadFromResources
03-19 12:53:03.288  4711  4734 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
03-19 12:53:03.288  4711  4734 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,03-19 12:53:03.354  4711  4711 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
03-19 12:53:03.354  4711  4711 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
03-19 12:53:03.354  4711  4711 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
03-19 12:53:03.354  4711  4711 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
03-19 12:53:03.354  4711  4711 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
03-19 12:53:03.355  4711  4711 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
03-19 12:53:03.355  4711  4711 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
,03-19 12:53:03.355  4711  4711 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
03-19 12:53:03.355  4711  4711 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
03-19 12:53:03.355  4711  4711 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
03-19 12:53:03.355  4711  4711 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
03-19 12:53:03.355  4711  4711 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
03-19 12:53:03.355  4711  4711 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
03-19 12:53:03.355  4711  4711 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
03-19 12:53:03.355  4711  4711 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
03-19 12:53:03.355  4711  4711 D SensorManager: found sensor: Motion Accel, handle=46
03-19 12:53:03.429  4711  4725 I art     : CheckpointMarkThreadRoots callback created = 0xb042d450
,03-19 12:53:03.468  4711  4725 I art     : CheckpointMarkThreadRoots callback created = 0xb042d420
,03-19 12:53:03.519   826   843 I ActivityManager: Process com.lge.sync (pid 4527) has died
03-19 12:53:03.530  4711  4711 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
03-19 12:53:03.534  4711  4711 I Babel_Crash: startup - clean
,03-19 12:53:03.569  4487  4546 D UEI.SmartControl: Internal timer expired: 1
,03-19 12:53:03.584  4711  4742 I Babel   : deleted: false for 0
,03-19 12:53:03.643  1731  4744 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
03-19 12:53:03.644  1731  4744 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
03-19 12:53:03.644  1731  4744 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
03-19 12:53:03.644  1731  4744 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
03-19 12:53:03.644   278  1064 E BandwidthController: [LG DATA] No such appUid: 10006
03-19 12:53:03.644   278  1064 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,03-19 12:53:03.646   278  4745 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
03-19 12:53:03.646   278  4745 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
03-19 12:53:03.647   278  4745 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
03-19 12:53:03.648   826  1019 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,03-19 12:53:03.667  4711  4711 W AudioCapabilities: Unsupported mime audio/x-lg-flac
03-19 12:53:03.668  4711  4711 W AudioCapabilities: Unsupported mime audio/adpcm
03-19 12:53:03.679  4711  4711 W AudioCapabilities: Unsupported mime audio/g726
,03-19 12:53:03.680  4711  4711 W AudioCapabilities: Unsupported mime audio/x-ms-wma
03-19 12:53:03.681  4711  4711 W AudioCapabilities: Unsupported mime audio/wma-voice
03-19 12:53:03.682  4711  4711 W VideoCapabilities: Unsupported mime video/mjpg
03-19 12:53:03.690  4711  4711 W VideoCapabilities: Unsupported mime video/theora
03-19 12:53:03.719  4711  4711 W AudioCapabilities: Unsupported mime audio/evrc
03-19 12:53:03.720  4711  4711 W AudioCapabilities: Unsupported mime audio/qcelp
03-19 12:53:03.722  4711  4711 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-19 12:53:03.730  4711  4711 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
03-19 12:53:03.732  4711  4711 W AudioCapabilities: Unsupported mime audio/qcelp
03-19 12:53:03.733  4711  4711 W AudioCapabilities: Unsupported mime audio/evrc
03-19 12:53:03.745  4711  4711 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,03-19 12:53:03.760  4711  4711 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-19 12:53:03.767  4711  4711 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-19 12:53:03.769  4711  4711 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-19 12:53:03.773  4711  4711 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-19 12:53:03.778   826  1845 I ActivityManager: Process com.lge.qremote (pid 4464) has died
03-19 12:53:03.779  4711  4711 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-19 12:53:03.780  4487  4487 D UEI.SmartControl: Service.onUnbind: IControl
03-19 12:53:03.780  4487  4487 D UEI.SmartControl: Service.onDestroy
03-19 12:53:03.783  4487  4487 D UEI.SmartControl: Shutdown IRRCPlayer... 
,03-19 12:53:03.790  4487  4487 W irrc_jni: IRRCPlayer_nativeFinalize ++ 
03-19 12:53:03.791  4487  4487 D irrcClient: ~IrrcClient ++ 
03-19 12:53:03.791  4487  4487 D irrcClient: ~IrrcClient -- 
03-19 12:53:03.791  4487  4487 W irrc_jni: IRRCPlayer_nativeFinalize -- 
03-19 12:53:03.791  4487  4487 D UEI.SmartControl: Blaster closed
03-19 12:53:03.791  4487  4487 D UEI.SmartControl: Blaster closed
03-19 12:53:03.791  4487  4487 D UEI.SmartControl: Shut down QS...
03-19 12:53:03.791  4487  4487 D UEI.SmartControl: Stopped file observer...
03-19 12:53:03.796  4487  4487 I UEI.SmartControl: QS lib stop result = true
03-19 12:53:03.797  4487  4487 D UEI.SmartControl: QS shutdown complete
,03-19 12:53:03.827   826  2177 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4747 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,03-19 12:53:03.850   309   309 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 20.905ms
,03-19 12:53:03.871   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 301us total 20.383ms
,03-19 12:53:03.896   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 418us total 24.420ms
,03-19 12:53:03.902  4711  4711 I vclib   : onServiceConnected
03-19 12:53:03.902  4711  4711 W Babel   : Attempted to change video mute state without an active call.
03-19 12:53:03.912  4711  4711 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,03-19 12:53:03.998  4747  4747 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-19 12:53:03.998  4747  4747 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,03-19 12:53:04.000  4747  4747 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
03-19 12:53:04.114  4747  4747 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,03-19 12:53:04.127  4747  4747 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,03-19 12:53:04.262   826  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{30eb23ac type 2 when 72086 com.google.android.gms} when 72086
,03-19 12:53:04.323  4747  4747 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,03-19 12:53:04.369   826  1845 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4773 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,03-19 12:53:04.512   826  1348 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4793 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,03-19 12:53:04.598  4793  4793 I AppUp4:AppBoxCP: onCreate
,03-19 12:53:04.600  4793  4793 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
03-19 12:53:04.609  4793  4793 I AppUp4:DB:  setFingerPrint start
03-19 12:53:04.610  4793  4793 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,03-19 12:53:04.616  4793  4793 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
03-19 12:53:04.617  4793  4793 I AppUp4:DB:  SDK version = 0
03-19 12:53:04.617  4793  4793 I AppUp4:DB:  beforefinger == newfinger no write in DB
03-19 12:53:04.618  4793  4793 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
03-19 12:53:04.631   826  1803 I ActivityManager: Killing 4487:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,03-19 12:53:04.835   826  1875 W libprocessgroup: failed to open /acct/uid_10089/pid_4487/cgroup.procs: No such file or directory
,03-19 12:53:04.916   826   843 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4813 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,03-19 12:53:05.040  4813  4813 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-19 12:53:05.040  4813  4813 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-19 12:53:05.042  4813  4813 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
03-19 12:53:05.172  4813  4813 I AppConfig: Total System Memory = 906309632
,03-19 12:53:05.176  4813  4813 I GalleryUtils: Application Heap = 96 MB
03-19 12:53:05.181  4813  4813 I AppConfig: App Tier : NOT_DEF
03-19 12:53:05.187  4813  4813 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,03-19 12:53:05.248  3684  4602 D AlertService: Beginning updateAlertNotification
,03-19 12:53:05.262   826  1348 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=4838 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
03-19 12:53:05.263   826  1348 I ActivityManager: Killing 4585:com.lge.clock/u0a10 (adj 15): empty #11
03-19 12:53:05.352   826  1821 W libprocessgroup: failed to open /acct/uid_10010/pid_4585/cgroup.procs: No such file or directory
,03-19 12:53:05.369  3684  4602 D AlertService: No fired or scheduled alerts
,03-19 12:53:05.373  3684  4602 I NotificationManager: com.android.calendar: cancel(0) by com.android.calendar
03-19 12:53:05.373  3684  4602 I NotificationManager: com.android.calendar: cancel(1) by com.android.calendar
03-19 12:53:05.373  3684  4602 I NotificationManager: com.android.calendar: cancel(2) by com.android.calendar
03-19 12:53:05.374  3684  4602 I NotificationManager: com.android.calendar: cancel(3) by com.android.calendar
,03-19 12:53:05.374  3684  4602 I NotificationManager: com.android.calendar: cancel(4) by com.android.calendar
03-19 12:53:05.374  3684  4602 I NotificationManager: com.android.calendar: cancel(5) by com.android.calendar
03-19 12:53:05.375  3684  4602 I NotificationManager: com.android.calendar: cancel(6) by com.android.calendar
03-19 12:53:05.375  3684  4602 I NotificationManager: com.android.calendar: cancel(7) by com.android.calendar
03-19 12:53:05.378  3684  4602 I NotificationManager: com.android.calendar: cancel(8) by com.android.calendar
03-19 12:53:05.379  3684  4602 I NotificationManager: com.android.calendar: cancel(9) by com.android.calendar
03-19 12:53:05.385  3684  4602 I NotificationManager: com.android.calendar: cancel(10) by com.android.calendar
03-19 12:53:05.386  3684  4602 I NotificationManager: com.android.calendar: cancel(11) by com.android.calendar
,03-19 12:53:05.387  3684  4602 I NotificationManager: com.android.calendar: cancel(12) by com.android.calendar
03-19 12:53:05.388  3684  4602 I NotificationManager: com.android.calendar: cancel(13) by com.android.calendar
03-19 12:53:05.388  3684  4602 I NotificationManager: com.android.calendar: cancel(14) by com.android.calendar
03-19 12:53:05.389  3684  4602 I NotificationManager: com.android.calendar: cancel(15) by com.android.calendar
03-19 12:53:05.389  3684  4602 I NotificationManager: com.android.calendar: cancel(16) by com.android.calendar
03-19 12:53:05.390  3684  4602 I NotificationManager: com.android.calendar: cancel(17) by com.android.calendar
03-19 12:53:05.390  3684  4602 I NotificationManager: com.android.calendar: cancel(18) by com.android.calendar
03-19 12:53:05.390  3684  4602 I NotificationManager: com.android.calendar: cancel(19) by com.android.calendar
03-19 12:53:05.391  3684  4602 I NotificationManager: com.android.calendar: cancel(20) by com.android.calendar
03-19 12:53:05.441  3684  4602 D AlertService: Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,03-19 12:53:05.460  3684  4602 D AlarmScheduler: No events found starting within 1 week.
,03-19 12:53:05.491  4838  4838 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-19 12:53:05.492  4838  4838 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
03-19 12:53:05.493  4838  4838 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
03-19 12:53:05.496  4838  4838 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
03-19 12:53:05.496  4838  4838 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
03-19 12:53:05.518   826   973 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
03-19 12:53:05.518   826   973 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,03-19 12:53:05.518   826   973 D sensors_hal_Time: tsOffsetIs: Apps: 73348843361; DSPS: 2495057; Offset : -2800463951
,03-19 12:53:05.609  1939  1939 I NotificationManager: com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,03-19 12:53:05.629   826  1794 I ActivityManager: Process com.google.android.music:main (pid 4609) has died
,03-19 12:53:05.695  4838  4838 I SystemConfig: BUILD Country: EU
03-19 12:53:05.695  4838  4838 I SystemConfig: BUILD Operator: OPEN
,03-19 12:53:05.808   294   352 I ThermalEngine: Sensor:pa_therm0:32000 mC
,03-19 12:53:05.816   826  1803 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=4865 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
03-19 12:53:05.867  4838  4863 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
03-19 12:53:05.867  4838  4863 I SystemConfig: existFile = false
03-19 12:53:05.867  4838  4863 I SystemConfig: canReadFile = false
03-19 12:53:05.867  4838  4863 I SystemConfig: systemFeature RCS result false
,03-19 12:53:05.869  4838  4863 D SystemConfig: refreshRcsSupport() :false
,03-19 12:53:05.922  4865  4865 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,03-19 12:53:05.947  4865  4865 I LockScreenSettings: New app installed broadcast received ..
,03-19 12:53:05.951  4865  4865 I LockScreenSettings: Number of installed packages  1
03-19 12:53:05.996   826  1845 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=4882 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
03-19 12:53:05.997   826  1845 I ActivityManager: Killing 4557:com.lge.bnr/1000 (adj 15): empty #11
,03-19 12:53:06.170   826  1875 W libprocessgroup: failed to open /acct/uid_1000/pid_4557/cgroup.procs: No such file or directory
,03-19 12:53:06.259  4882  4882 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
03-19 12:53:06.259  4882  4882 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,03-19 12:53:06.304   826  1875 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=4902 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,03-19 12:53:06.305   826  1875 I ActivityManager: Killing 4663:com.android.providers.calendar/u0a14 (adj 15): empty #11
03-19 12:53:06.400   826  1359 W libprocessgroup: failed to open /acct/uid_10014/pid_4663/cgroup.procs: No such file or directory
,03-19 12:53:06.510  4902  4902 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,03-19 12:53:06.557  4902  4902 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,03-19 12:53:06.557   826  2177 I ActivityManager: Killing 4688:com.google.android.setupwizard/u0a38 (adj 15): empty #11
03-19 12:53:06.640   826  1883 W libprocessgroup: failed to open /acct/uid_10038/pid_4688/cgroup.procs: No such file or directory
,03-19 12:53:06.791  2268  2268 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,03-19 12:53:06.827  2268  4927 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-19 12:53:06.874  2268  4927 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-19 12:53:07.008  2268  4069 I Icing   : Storage manager: low false usage 1.70MB avail 2.37GB capacity 4.06GB
03-19 12:53:07.008  2268  2268 D AsyncTaskServiceImpl: Submit a task: k
,03-19 12:53:07.042  2268  4938 D k       : Processing package: com.test.thalitest
,03-19 12:53:07.065  2268  4938 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
03-19 12:53:07.066  2268  4938 D k       : Found info for package com.test.thalitest in db.
,03-19 12:53:07.121   826  1348 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4944 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,03-19 12:53:07.168  2268  4935 W BaseAppContext: Using Auth Proxy for data requests.
03-19 12:53:07.169  2268  4935 W BaseAppContext: Using Auth Proxy for data requests.
,03-19 12:53:07.178  2268  4935 W BaseAppContext: Using Auth Proxy for data requests.
03-19 12:53:07.178  2268  4929 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
03-19 12:53:07.190  2268  4935 W BaseAppContext: Using Auth Proxy for data requests.
,03-19 12:53:07.216  2268  4935 W BaseAppContext: Using Auth Proxy for data requests.
,03-19 12:53:07.673  2268  4069 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-19 12:53:07.872   826  1794 I art     : Explicit concurrent mark sweep GC freed 22777(1220KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/34MB, paused 3.520ms total 181.319ms
,03-19 12:53:08.045  4944  4944 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-19 12:53:08.045  4944  4944 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-19 12:53:08.045  4944  4944 I GAv4    :   adb logcat -s GAv4
,03-19 12:53:08.069   826  1883 I ActivityManager: Process com.google.android.talk (pid 4711) has died
,03-19 12:53:08.079  4944  4944 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
03-19 12:53:08.107  4944  4944 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-19 12:53:08.119  2268  4069 I Icing   : Internal init done: storage state 0
,03-19 12:53:08.125  4944  4976 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
03-19 12:53:08.164  4944  4944 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,03-19 12:53:08.172  2268  4069 I Icing   : Post-init done
03-19 12:53:08.364   246   386 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
03-19 12:53:08.364   246   386 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
03-19 12:53:08.364   246   386 W Vold    : Returning OperationFailed - no handler for errno 0
,03-19 12:53:08.366  4944  4985 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
03-19 12:53:08.406  4944  4986 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-19 12:53:08.406  4944  4986 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-19 12:53:08.415   826  2177 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4987 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-19 12:53:08.493  4944  4963 I art     : CheckpointMarkThreadRoots callback created = 0xaaeef2b0
,03-19 12:53:08.526  4944  4986 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
03-19 12:53:08.545  4944  4963 I art     : CheckpointMarkThreadRoots callback created = 0xb050c9f0
,03-19 12:53:08.599  4944  4986 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-19 12:53:08.600  4944  4986 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-19 12:53:08.600  4987  4987 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-19 12:53:08.625  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:53:08.889   826  1845 I ActivityManager: Process com.lge.email (pid 4747) has died
,03-19 12:53:09.235   826  1821 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5027 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-19 12:53:09.237  1939  5023 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
03-19 12:53:09.271  2268  4069 I Icing   : Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,03-19 12:53:09.339   826  1359 I ActivityManager: Process com.android.contacts (pid 4838) has died
,03-19 12:53:09.374  2268  4069 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,03-19 12:53:09.392  2268  4069 I Icing   : Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,03-19 12:53:09.507  1939  5023 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 269 ms] updated apps [took 269 ms] 
,03-19 12:53:09.649   826  2177 I ActivityManager: Process com.lge.appbox.client (pid 4793) has died
,03-19 12:53:09.693  5027  5027 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
,03-19 12:53:09.756  2268  5053 W IcingInternalCorpora: getNumBytesRead when not calculated.
,03-19 12:53:09.863  5027  5027 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(122): No need to run daily hygiene.
,03-19 12:53:09.885  5027  5027 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-19 12:53:09.887  5027  5027 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-19 12:53:09.894  5027  5027 I NotificationManager: com.android.vending: cancel(-1050172287) by com.android.vending
,03-19 12:53:09.938  2718  2733 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is notificationclass=?; selectionArgs[0] is com.google.android.finsky.download.DownloadBroadcastReceiver; sort is null.
,03-19 12:53:09.940  2718  2733 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2bdb3004 on behalf of 5027
03-19 12:53:09.947  5027  5027 I NotificationManager: com.android.vending: cancel(1003285959) by com.android.vending
,03-19 12:53:09.970  5027  5027 I Finsky  : [1] com.google.android.finsky.g.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-19 12:53:09.970  5027  5027 I Finsky  : [1] com.google.android.finsky.g.j.run(214): Finished loading 1 libraries.
,03-19 12:53:09.981  5027  5068 D Ads     : Skipping gmscore version check
03-19 12:53:09.982  5027  5027 I Finsky  : [1] com.google.android.finsky.b.j.a(273): result=false type=4
03-19 12:53:09.991  2268  4062 I CheckinService: Done disabling old GoogleServicesFramework version
,03-19 12:53:10.016   826  1900 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5069 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-19 12:53:10.038   309   309 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 321us total 22.544ms
,03-19 12:53:10.061   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 22.096ms
,03-19 12:53:10.083   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 21.765ms
,03-19 12:53:10.110  5027  5027 I Finsky  : [1] com.google.android.finsky.utils.ExternalReferrer.a(4312): Package state data is missing for com.test.thalitest
,03-19 12:53:10.123  5027  5027 I Finsky  : [1] com.google.android.finsky.services.ar.a(1049): Restore complete with 0 success and 0 failed.
,03-19 12:53:10.308   826  1773 I ActivityManager: Process com.android.gallery3d (pid 4813) has died
,03-19 12:53:10.313   826  1803 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-19 12:53:10.385  5069  5091 I Gmail   : getAccountsCursor
,03-19 12:53:10.391  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-19 12:53:10.414  5069  5069 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-19 12:53:10.445   826  1359 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-19 12:53:10.508  5069  5099 E Gmail   : Error finding the version of the Email provider.....
03-19 12:53:10.508  5069  5099 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-19 12:53:10.508  5069  5099 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
03-19 12:53:10.508  5069  5099 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
03-19 12:53:10.508  5069  5099 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
03-19 12:53:10.508  5069  5099 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-19 12:53:10.508  5069  5099 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 12:53:10.508  5069  5099 E Gmail   : 	at android.os.Looper.loop(Looper.java:135)
03-19 12:53:10.508  5069  5099 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-19 12:53:10.508  5069  5099 W EmailMigration: We do not support migrating this version of the Email provider.
,03-19 12:53:10.568  2268  4069 I Icing   : Indexing 0A5267A505F47CB39AEB664724AACA2991DAA8A8 from com.google.android.googlequicksearchbox
,03-19 12:53:10.569   826  1348 I ActivityManager: Process com.lge.lockscreensettings (pid 4865) has died
03-19 12:53:10.571   826  1876 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
03-19 12:53:10.583  5069  5102 I Gmail   : getAccountsCursor
,03-19 12:53:10.587  5069  5101 I Gmail   : Observing account changes for notifications
03-19 12:53:10.619   826  1803 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5104 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-19 12:53:10.620   826  1348 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-19 12:53:10.646  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:53:10.676  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:53:10.710  5104  5104 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-19 12:53:10.734  2268  4069 I Icing   : Indexing done 0A5267A505F47CB39AEB664724AACA2991DAA8A8
,03-19 12:53:10.813   294   352 I ThermalEngine: Sensor:pa_therm0:32000 mC
,03-19 12:53:10.836  5069  5129 I Gmail   : notifyAccountChanged
,03-19 12:53:10.840  5069  5131 I Gmail   : getAccountsCursor
03-19 12:53:10.840  5069  5129 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
03-19 12:53:10.850  5069  5129 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-19 12:53:10.860  5069  5129 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
03-19 12:53:10.860  5069  5129 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-19 12:53:10.919   826  1359 I ActivityManager: Process com.google.android.partnersetup (pid 4773) has died
,03-19 12:53:10.926  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-19 12:53:10.948  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:53:10.950  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-19 12:53:10.972  5104  5137 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-19 12:53:10.972  5104  5137 I Babel_SMS: MmsConfig.loadMmsSettings
03-19 12:53:10.977  5104  5137 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,03-19 12:53:10.977  5104  5137 I Babel_SMS: MmsConfig.loadFromDatabase
,03-19 12:53:11.002  5104  5137 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-19 12:53:11.003  5104  5137 I Babel_SMS: MmsConfig.loadFromResources
03-19 12:53:11.004  5104  5137 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
03-19 12:53:11.005  5104  5137 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
03-19 12:53:11.033  5104  5104 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
03-19 12:53:11.033  5104  5104 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
03-19 12:53:11.033  5104  5104 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
03-19 12:53:11.033  5104  5104 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
03-19 12:53:11.033  5104  5104 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
03-19 12:53:11.033  5104  5104 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
03-19 12:53:11.033  5104  5104 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
03-19 12:53:11.033  5104  5104 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
03-19 12:53:11.033  5104  5104 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
03-19 12:53:11.033  5104  5104 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
03-19 12:53:11.033  5104  5104 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
03-19 12:53:11.033  5104  5104 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
03-19 12:53:11.033  5104  5104 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
03-19 12:53:11.033  5104  5104 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
03-19 12:53:11.033  5104  5104 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
03-19 12:53:11.033  5104  5104 D SensorManager: found sensor: Motion Accel, handle=46
,03-19 12:53:11.056  5069  5091 I Gmail   : getAccountsCursor
,03-19 12:53:11.060  1731  1731 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-19 12:53:11.074  5104  5104 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-19 12:53:11.083  5104  5104 I Babel_Crash: startup - clean
,03-19 12:53:11.108  5104  5140 I Babel   : deleted: false for 0
,03-19 12:53:11.160  5104  5124 I art     : CheckpointMarkThreadRoots callback created = 0xb042d520
,03-19 12:53:11.196  5104  5124 I art     : CheckpointMarkThreadRoots callback created = 0xb042d500
,03-19 12:53:11.259   826  1803 I ActivityManager: Process com.lge.bnr (pid 4902) has died
,03-19 12:53:11.269  1939  1939 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,03-19 12:53:11.279  1750  1750 I PhoneApp: onTrimMemory: 10
03-19 12:53:11.280  1750  1750 I PhoneApp: trim memory
03-19 12:53:11.420   826   843 I art     : Explicit concurrent mark sweep GC freed 18052(844KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.098ms total 144.450ms
,03-19 12:53:11.458   826  1900 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5145 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
03-19 12:53:11.578  5104  5104 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,03-19 12:53:11.581  5104  5104 W AudioCapabilities: Unsupported mime audio/adpcm
03-19 12:53:11.582  5104  5104 W AudioCapabilities: Unsupported mime audio/g726
03-19 12:53:11.583  5104  5104 W AudioCapabilities: Unsupported mime audio/x-ms-wma
03-19 12:53:11.584  5104  5104 W AudioCapabilities: Unsupported mime audio/wma-voice
03-19 12:53:11.585  5104  5104 W VideoCapabilities: Unsupported mime video/mjpg
03-19 12:53:11.589  5104  5104 W VideoCapabilities: Unsupported mime video/theora
,03-19 12:53:11.615  5104  5104 W AudioCapabilities: Unsupported mime audio/evrc
03-19 12:53:11.617  5104  5104 W AudioCapabilities: Unsupported mime audio/qcelp
03-19 12:53:11.619  5104  5104 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-19 12:53:11.627  5104  5104 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-19 12:53:11.628  5104  5104 W AudioCapabilities: Unsupported mime audio/qcelp
03-19 12:53:11.630  5104  5104 W AudioCapabilities: Unsupported mime audio/evrc
03-19 12:53:11.641  5104  5104 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,03-19 12:53:11.645  5145  5145 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
03-19 12:53:11.658  5104  5104 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-19 12:53:11.667  5104  5104 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-19 12:53:11.669  5104  5104 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-19 12:53:11.673  5104  5104 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-19 12:53:11.678  5104  5104 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-19 12:53:11.737   826  1022 D BluetoothManagerService: Message: 20
03-19 12:53:11.737   826  1022 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31a23d:true
,03-19 12:53:11.747  2010  2056 D BluetoothAdapterService(214083283): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a5b3841
03-19 12:53:11.748  2010  3380 D BluetoothAdapterService(214083283): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a5b3841
,03-19 12:53:11.859   826  1803 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5165 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-19 12:53:11.878  5145  5145 V LGMDMManager: Create singleton instance
,03-19 12:53:11.910  5104  5104 I vclib   : onServiceConnected
,03-19 12:53:11.913  5104  5104 W Babel   : Attempted to change video mute state without an active call.
03-19 12:53:11.944  5104  5104 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-19 12:53:11.945  5104  5104 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-19 12:53:11.979  5145  5145 I AudioManager: getMode name:com.lge.qremote
,03-19 12:53:11.985  5165  5165 D UEI.SmartControl: Quickset Services start...
03-19 12:53:11.986  5104  5104 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
03-19 12:53:12.004  5165  5165 I UEI.SmartControl: Manufacture = LGE
03-19 12:53:12.006  5165  5165 D UEI.SmartControl: File observer start...
,03-19 12:53:12.008  5165  5165 E UEI.SmartControl: IR Port is disabled: false
03-19 12:53:12.011  5165  5165 D UEI.SmartControl: Starting file observer...
03-19 12:53:12.011  5165  5165 D UEI.SmartControl: Extracting JNI libs...
03-19 12:53:12.012  5165  5165 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
03-19 12:53:12.039  5145  5145 I AudioManager: getMode name:com.lge.qremote
,03-19 12:53:12.095  5104  5104 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-19 12:53:12.096  5104  5104 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-19 12:53:12.109   826  2177 I ActivityManager: Process com.google.android.apps.docs (pid 4944) has died
,03-19 12:53:12.116  1750  1750 I PhoneApp: onTrimMemory: 10
03-19 12:53:12.116  1750  1750 I PhoneApp: trim memory
03-19 12:53:12.120  1939  1939 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,03-19 12:53:12.131  5145  5145 I AudioManager: getMode name:com.lge.qremote
03-19 12:53:12.144  5104  5104 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,03-19 12:53:12.194  5145  5145 I AudioManager: getMode name:com.lge.qremote
,03-19 12:53:12.198  5145  5145 I AudioManager: getMode name:com.lge.qremote
03-19 12:53:12.203  5145  5145 I AudioManager: getMode name:com.lge.qremote
03-19 12:53:12.232  5104  5187 I NotificationManager: com.google.android.talk: cancel(8) by com.google.android.talk
,03-19 12:53:12.264   826  1876 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5190 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,03-19 12:53:12.273  5165  5165 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
03-19 12:53:12.273  5165  5165 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
03-19 12:53:12.273  5165  5165 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
03-19 12:53:12.313  1939  1939 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,03-19 12:53:12.342  5165  5165 I UEI.SmartControl: --- Selecting new region: 2
03-19 12:53:12.342  5165  5165 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
,03-19 12:53:12.351  5165  5165 D UEI.SmartControl: Platform has CIR...
03-19 12:53:12.353  5165  5165 D UEI.SmartControl: NO CIR support, need to check package...
03-19 12:53:12.354  5165  5165 I UEI.SmartControl: Model: LG-D722 uses JNI
03-19 12:53:12.364  5165  5165 D UEI.SmartControl: QS Service created
,03-19 12:53:12.390  5165  5165 E UEI.SmartControl: QS start get config
,03-19 12:53:12.409  5190  5190 I AppUp4:AppBoxCP: onCreate
,03-19 12:53:12.414  5190  5190 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
03-19 12:53:12.439  5190  5190 I AppUp4:DB:  setFingerPrint start
03-19 12:53:12.439  5190  5190 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,03-19 12:53:12.448  5190  5190 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
03-19 12:53:12.448  5190  5190 I AppUp4:DB:  SDK version = 0
03-19 12:53:12.448  5190  5190 I AppUp4:DB:  beforefinger == newfinger no write in DB
03-19 12:53:12.450  5190  5190 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
03-19 12:53:12.466  5165  5165 D UEI.SmartControl: Loading JNI Libs...
,03-19 12:53:12.468  5165  5165 D UEI.SmartControl:  configuring local db...
03-19 12:53:12.474  5190  5190 I AppUp4:CustModeStarterReceiver: onReceive
03-19 12:53:12.474  5190  5190 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
03-19 12:53:12.478  5190  5190 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d5b78d1
03-19 12:53:12.478  5190  5190 D AppUp4:CustFacade: isCustomizationCompleted : false
,03-19 12:53:12.485  5190  5190 D AppUp4:CustFacade: isSimDevice : true
03-19 12:53:12.486  5190  5190 D AppUp4:CustModeStarterReceiver: begin check event
03-19 12:53:12.486  5190  5190 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
03-19 12:53:12.538   826  1900 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5210 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,03-19 12:53:12.662  5210  5210 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-19 12:53:12.662  5210  5210 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-19 12:53:12.663  5210  5210 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
03-19 12:53:12.700  5165  5165 D UEI.SmartControl:  ---- Has DB8: true
,03-19 12:53:12.708  5165  5165 D UEI.SmartControl: QS start statue = true Error code = 0
03-19 12:53:12.708  5165  5165 D UEI.SmartControl: QS version = v2.7.11.1_RC1
03-19 12:53:12.709  5165  5165 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
03-19 12:53:12.713  5165  5165 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
,03-19 12:53:12.730  5165  5165 W irrc_jni: IRRCPlayer_nativeInit ++ 
03-19 12:53:12.730  5165  5165 D irrcClient: IrrcClient ++ 
03-19 12:53:12.730  5165  5165 D irrcClient: getIrrcService ++ 
,03-19 12:53:12.730  5165  5165 D irrcClient: getIrrcService -- 
03-19 12:53:12.731  5165  5165 D irrcClient: IrrcClient -- 
03-19 12:53:12.731  5165  5165 W irrc_jni: IRRCPlayer_nativeInit -- 
03-19 12:53:12.738  5165  5165 D UEI.SmartControl: Services init done
03-19 12:53:12.740  5165  5165 D UEI.SmartControl: QS Service init finished
03-19 12:53:12.742  5165  5165 D UEI.SmartControl: QS Service version name: 0.1.73
03-19 12:53:12.742  5165  5229 I UEI.SmartControl: Device manager: loading config....
03-19 12:53:12.742  5165  5165 D UEI.SmartControl: QS Service version code: 1073
,03-19 12:53:12.743  5165  5165 D UEI.SmartControl: Service requested: Control
03-19 12:53:12.745  5210  5210 I AppConfig: Total System Memory = 906309632
03-19 12:53:12.748  5165  5229 D UEI.SmartControl: Config is loaded...
03-19 12:53:12.748  5210  5210 I GalleryUtils: Application Heap = 96 MB
03-19 12:53:12.750  5210  5210 I AppConfig: App Tier : NOT_DEF
03-19 12:53:12.754  5165  5228 D UEI.SmartControl:  ----- QS SDK is ready!!!
03-19 12:53:12.755  5165  5228 I UEI.SmartControl: Notify AllClients services are ready: 0
,03-19 12:53:12.757  5210  5210 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
03-19 12:53:12.789  5165  5165 D UEI.SmartControl: Request IControl service: devices are loaded...
,03-19 12:53:12.792  5165  5165 D UEI.SmartControl: Service.onTrimMemory: 10
03-19 12:53:12.796  5165  5165 E UEI.SmartControl: Setup service releasing memory...
03-19 12:53:12.797  5165  5181 D UEI.SmartControl: -----IControl: 11
03-19 12:53:12.798  5165  5181 D UEI.SmartControl: Caller: com.lge.qremote
03-19 12:53:12.799  5165  5181 D UEI.SmartControl: ------------ IControl registerCallback...
03-19 12:53:12.800  5165  5181 I UEI.SmartControl: Registering callback...
03-19 12:53:12.803  5165  5182 D UEI.SmartControl: -----IControl: 19
,03-19 12:53:12.804  5165  5182 D UEI.SmartControl: Caller: com.lge.qremote
03-19 12:53:12.806  5165  5182 I UEI.SmartControl: Registering Services Ready callback...
03-19 12:53:12.807  5165  5182 I UEI.SmartControl: Notify client services are ready...
03-19 12:53:12.809  5165  5181 D UEI.SmartControl: -----IControl: 8
03-19 12:53:12.810  5165  5181 D UEI.SmartControl: Caller: com.lge.qremote
03-19 12:53:12.851   826  1876 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5232 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,03-19 12:53:12.855  5165  5165 I art     : Explicit concurrent mark sweep GC freed 10607(756KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 7MB/9MB, paused 406us total 56.311ms
03-19 12:53:12.855  5165  5165 D UEI.SmartControl: Internal service binding...
,03-19 12:53:12.971  5232  5232 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-19 12:53:12.971  5232  5232 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,03-19 12:53:12.971  5232  5232 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
03-19 12:53:12.972  5232  5232 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
03-19 12:53:12.972  5232  5232 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
03-19 12:53:13.085  5232  5232 I SystemConfig: BUILD Country: EU
03-19 12:53:13.085  5232  5232 I SystemConfig: BUILD Operator: OPEN
,03-19 12:53:13.161  5232  5252 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
03-19 12:53:13.162  5232  5252 I SystemConfig: existFile = false
03-19 12:53:13.162  5232  5252 I SystemConfig: canReadFile = false
03-19 12:53:13.162  5232  5252 I SystemConfig: systemFeature RCS result false
,03-19 12:53:13.162  5232  5252 D SystemConfig: refreshRcsSupport() :false
03-19 12:53:13.196   826  1883 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5254 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,03-19 12:53:13.312  5254  5254 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,03-19 12:53:13.336  5254  5254 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
03-19 12:53:13.336  5254  5254 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
03-19 12:53:13.336  5254  5254 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
03-19 12:53:13.336  5254  5254 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
03-19 12:53:13.336  5254  5254 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,03-19 12:53:13.338   826  1803 I ActivityManager: Killing 4882:com.lge.eula/1000 (adj 15): empty #11
03-19 12:53:13.441   826  1876 W libprocessgroup: failed to open /acct/uid_1000/pid_4882/cgroup.procs: No such file or directory
,03-19 12:53:13.446  2268  4927 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
03-19 12:53:13.449  2268  4927 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
03-19 12:53:13.457  2268  4927 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-19 12:53:13.467  2268  4069 I Icing   : updateResources: need to parse f{com.google.android.gms}
03-19 12:53:13.471  4987  5001 I art     : CheckpointMarkThreadRoots callback created = 0xaaf032d0
,03-19 12:53:13.490  1939  5277 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,03-19 12:53:13.530  4987  5001 I art     : CheckpointMarkThreadRoots callback created = 0xaaf039e0
,03-19 12:53:13.592  1939  5277 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 102 ms] updated apps [took 102 ms] 
,03-19 12:53:13.663  1731  5283 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
03-19 12:53:13.663  1731  5283 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,03-19 12:53:13.669  1731  5283 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
03-19 12:53:13.669  1731  5283 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
03-19 12:53:13.669   278  1064 E BandwidthController: [LG DATA] No such appUid: 10006
03-19 12:53:13.669   278  1064 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
03-19 12:53:13.670   278  5284 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
03-19 12:53:13.670   278  5284 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
03-19 12:53:13.671   278  5284 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
03-19 12:53:13.672   826  1019 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,03-19 12:53:13.686  5145  5145 I AudioManager: getMode name:com.lge.qremote
03-19 12:53:13.691  5145  5145 I AudioManager: getMode name:com.lge.qremote
03-19 12:53:13.717  5145  5145 I AudioManager: getMode name:com.lge.qremote
,03-19 12:53:13.726  5145  5145 I AudioManager: getMode name:com.lge.qremote
03-19 12:53:14.702  2268  4069 I Icing   : Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,03-19 12:53:14.766  2268  4069 I Icing   : Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,03-19 12:53:14.888   826  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3465febf type 2 when 82711 com.google.android.gms} when 82711
,03-19 12:53:14.893  1731  5297 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
03-19 12:53:14.893  1731  5297 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
03-19 12:53:15.457  5069  5094 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-19 12:53:15.816  3684  3746 D InitAlarmsService: Clearing and rescheduling alarms.
,03-19 12:53:15.817   294   352 I ThermalEngine: Sensor:pa_therm0:32000 mC
03-19 12:53:15.871   826   843 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5301 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-19 12:53:15.962  5301  5301 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-19 12:53:16.018  5301  5301 D CalendarProvider2: [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2f35366a
,03-19 12:53:16.037  5301  5301 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
03-19 12:53:16.038  5301  5301 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@b505e37(com.android.providers.calendar.CalendarProvider2@2f35366a)
,03-19 12:53:16.043  5301  5317 D CalendarProvider2: Scheduling check of next Alarm
03-19 12:53:16.045  5301  5317 D CalendarProvider2: SCHEDULE_ALARM_REMOVE
03-19 12:53:16.050   826   846 I ActivityManager: Killing 3684:com.android.calendar/u0a13 (adj 15): empty #11
,03-19 12:53:16.172   826  1845 W libprocessgroup: failed to open /acct/uid_10013/pid_3684/cgroup.procs: No such file or directory
,03-19 12:53:17.088  5301  5301 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-19 12:53:17.095  5301  5301 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
03-19 12:53:17.151   826   961 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5328 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-19 12:53:17.154   826  1359 I ActivityManager: Killing 3533:com.google.process.gapps/u0a6 (adj 15): empty #11
,03-19 12:53:17.277   826  1821 W libprocessgroup: failed to open /acct/uid_10006/pid_3533/cgroup.procs: No such file or directory
03-19 12:53:17.295  5328  5328 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-19 12:53:17.310   826  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{20ed4b42 type 2 when 85135 com.google.android.gms} when 85135
,03-19 12:53:17.345  5328  5328 D CalendarApplication: CalendarApplication.onCreate()
,03-19 12:53:17.359   826  1803 I ActivityManager: Killing 5190:com.lge.appbox.client/u0a11 (adj 15): empty #11
,03-19 12:53:17.378  5328  5328 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
,03-19 12:53:17.380  5328  5328 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@367f2bf8, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@2d5b78d1, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@31684f36, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@b505e37, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@23770fa4, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1d4dd10d, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@2ce228c2, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@cc2a6d3, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@17e78210, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@1f937109, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@142e0f0e, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1306dd2f, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@32aaaf3c, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@187914c5, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@25400e1a, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@22ae1d4b, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@4118328, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2a5b3841, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1740f1e6, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2e3f4327, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@e8fa9d4, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@26e2177d, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@191a4672, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1fd2eac3, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@26278f40, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@17fdae79, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2cc257be, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@206f701f, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@1a965f6c, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1ca1b935, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@2b4831ca, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3924ef3b, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@18400658, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@1541b3b1, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@3d9fa096, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@29e94417, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2bdb3004, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@1c0cd9ed, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@162d3022, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@12340ab3, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@14dd4870, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKe,y$KeyData@4e
03-19 12:53:17.392  5328  5328 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
,03-19 12:53:17.409  5328  5328 D Config  : [init]
,03-19 12:53:17.411  5328  5328 I Config  : LGCalendar ver.4.40.17
03-19 12:53:17.411  5328  5328 I Config  : start check model
03-19 12:53:17.411  5328  5328 I Config  : start check native_ca
03-19 12:53:17.412  5328  5328 I Config  : Config Operator=OPEN, Country=EU
03-19 12:53:17.412  5328  5328 D Config  : [setDefaultValuesToPref]
03-19 12:53:17.412  5328  5328 D Config  : [parseProfiles]
03-19 12:53:17.416  5328  5328 D ProfilesParser: [debug_displayParseInfos] profile.country = null
03-19 12:53:17.416  5328  5328 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
03-19 12:53:17.416  5328  5328 D Config  : [updateProfiletoCountryInfo]
03-19 12:53:17.417  5328  5328 D GeneralPreference: [checkAndMigrateOldPreference]
03-19 12:53:17.460   826   843 W libprocessgroup: failed to open /acct/uid_10011/pid_5190/cgroup.procs: No such file or directory
,03-19 12:53:17.472  5328  5328 D AlertReceiver: onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,03-19 12:53:17.483  5328  5347 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
03-19 12:53:17.542  5328  5347 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,03-19 12:53:17.607  2718  3375 I art     : Explicit concurrent mark sweep GC freed 6362(409KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 400us total 41.699ms
,03-19 12:53:17.619  5328  5347 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
03-19 12:53:17.625  5328  5347 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
03-19 12:53:17.631  5328  5347 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,03-19 12:53:17.636  5328  5347 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
03-19 12:53:17.642  5328  5347 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
03-19 12:53:17.646  5328  5347 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
03-19 12:53:17.650  4334  4485 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-19 12:53:17.650  4334  4485 I jxcore-log: 
,03-19 12:53:17.652  5328  5347 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
03-19 12:53:17.654  4334  4485 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-19 12:53:17.654  4334  4485 I jxcore-log: 
03-19 12:53:17.656  5328  5347 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
03-19 12:53:17.658  2010  2045 D BluetoothAdapterService(214083283): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a5b3841
03-19 12:53:17.659  4334  4485 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-19 12:53:17.659  4334  4485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-19 12:53:17.659  4334  4485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-19 12:53:17.659  4334  4485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-19 12:53:17.659  4334  4485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-19 12:53:17.659  4334  4485 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-19 12:53:17.659  4334  4485 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-19 12:53:17.659  4334  4485 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-19 12:53:17.661  2010  2045 D BluetoothAdapterService(214083283): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a5b3841
,03-19 12:53:17.662  5328  5347 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
03-19 12:53:17.663  4334  4485 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
03-19 12:53:17.666  5328  5347 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
03-19 12:53:17.667  4334  4485 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-19 12:53:17.667  4334  4485 I jxcore-log: 
03-19 12:53:17.669  5328  5347 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
03-19 12:53:17.671  4334  4485 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-19 12:53:17.671  4334  4485 I jxcore-log: 
,03-19 12:53:17.673  5328  5347 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
03-19 12:53:17.678  5328  5347 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
03-19 12:53:17.688  5328  5347 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,03-19 12:53:17.699  5328  5347 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
03-19 12:53:17.703  5328  5347 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
03-19 12:53:17.703  5328  5347 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,03-19 12:53:17.710  5328  5347 I AlertUtils: set default noti to content://media/internal/audio/media/38
03-19 12:53:17.715  5328  5347 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
,03-19 12:53:17.750  5328  5362 W HolidayIntentService: onHandleIntent
03-19 12:53:17.752  5328  5362 D HolidayDataLoader: readJsonAsset : holiday.json
03-19 12:53:17.760  5328  5363 D AlertService: 0 Action = android.intent.action.PROVIDER_CHANGED
,03-19 12:53:17.763  5328  5328 E AgendaWidgetManager: [updateWidgets] 
03-19 12:53:17.767  5328  5328 D MonthWidgetProvider: [onReceive]
03-19 12:53:17.767  5328  5328 D CalendarWidgetProvider: [onReceive]
03-19 12:53:17.767  5328  5328 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
03-19 12:53:17.769  5328  5328 D CalendarTypeController: [onCreate] mContext.getPackageName() = com.android.calendar
03-19 12:53:17.772  5328  5328 D WeekWidgetProvider: [onReceive]
03-19 12:53:17.772  5328  5328 D CalendarWidgetProvider: [onReceive]
03-19 12:53:17.772  5328  5328 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,03-19 12:53:17.776  5328  5328 D CalendarTypeController: [onCreate] mContext.getPackageName() = com.android.calendar
03-19 12:53:17.779  5165  5230 D UEI.SmartControl: Internal timer expired: 1
03-19 12:53:17.783  1731  5365 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
03-19 12:53:17.783  1731  5365 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
03-19 12:53:17.784  1731  5365 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
03-19 12:53:17.784  1731  5365 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
03-19 12:53:17.784   278  1064 E BandwidthController: [LG DATA] No such appUid: 10006
03-19 12:53:17.784   278  1064 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
03-19 12:53:17.784   278  5366 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
03-19 12:53:17.784   278  5366 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
03-19 12:53:17.785   278  5366 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
,03-19 12:53:17.786   826  1019 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
03-19 12:53:17.814  5328  5362 E HolidayIntentService: onHandleIntent:holiday data empty
,03-19 12:53:18.522  4334  4485 I jxcore-log: Unit Test app is loaded
03-19 12:53:18.522  4334  4485 I jxcore-log: 
,03-19 12:53:18.528  4334  4485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
03-19 12:53:18.528  4334  4485 I jxcore-log: 
03-19 12:53:18.536  2010  2045 D BluetoothAdapterService(214083283): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a5b3841
,03-19 12:53:18.536  4334  4485 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
03-19 12:53:18.540  4334  4485 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-19 12:53:18.540  4334  4485 I jxcore-log: 
03-19 12:53:18.542  4334  4485 I jxcore-log: logCallback not set !!!!
03-19 12:53:18.542  4334  4485 I jxcore-log: 
03-19 12:53:18.542  4334  4485 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-19 12:53:18.542  4334  4485 I jxcore-log: 
03-19 12:53:18.549  4334  4334 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-19 12:53:18.951  5373  5373 D AndroidRuntime: 
03-19 12:53:18.951  5373  5373 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-19 12:53:18.964  5373  5373 D AndroidRuntime: CheckJNI is OFF
,03-19 12:53:19.246  5373  5373 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-19 12:53:19.293   826   961 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
03-19 12:53:19.294   826   961 I ActivityManager: Killing 4334:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
,03-19 12:53:19.348   826  1359 I WindowState: WIN DEATH: Window{3ac38a2d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-19 12:53:19.360   826  1359 D InputDispatcher: Focus left window: Window{3ac38a2d u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-19 12:53:19.360   826  1359 D InputDispatcher: Window went away: Window{3ac38a2d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-19 12:53:19.395   826  1049 W PackageSettings: Skipping PackageSetting{31c8dcee com.example.hello/10317} due to missing metadata
,03-19 12:53:19.424   826   961 W ActivityManager: Force removing ActivityRecord{22b59ca2 u0 com.test.thalitest/.MainActivity t226}: app died, no saved state
,03-19 12:53:19.452   826  1845 W ActivityManager: Spurious death for ProcessRecord{38bdbc 4334:com.test.thalitest/u0a30}, curProc for 4334: null
,03-19 12:53:19.455   826  1049 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
,03-19 12:53:19.544  1939  1939 I art     : Explicit concurrent mark sweep GC freed 18980(1494KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/20MB, paused 1.976ms total 76.928ms
,03-19 12:53:19.562  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,03-19 12:53:19.568   826  1288 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-19 12:53:19.570  1839  1839 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
03-19 12:53:19.572  1731  2467 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-19 12:53:19.594  3478  3478 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
03-19 12:53:19.594  3478  3478 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
03-19 12:53:19.594  3478  3478 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
03-19 12:53:19.594  3478  3478 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
03-19 12:53:19.594  3478  3478 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-19 12:53:19.595  3478  3478 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-19 12:53:19.595  3478  3478 W System.err: 	at android.os.Looper.loop(Looper.java:135)
03-19 12:53:19.595  3478  3478 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
03-19 12:53:19.595  3478  3478 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-19 12:53:19.595  3478  3478 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-19 12:53:19.595  3478  3478 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
03-19 12:53:19.595  3478  3478 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,03-19 12:53:19.607  1877  1877 I [LGHome]EVENT: [Launcher.java:5203:onStart()]onStart
03-19 12:53:19.619  2268  2268 I art     : Explicit concurrent mark sweep GC freed 16748(963KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 13MB/18MB, paused 1.568ms total 140.566ms
,03-19 12:53:19.631  1877  1877 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,03-19 12:53:19.646   826   961 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5397 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,03-19 12:53:19.677  1877  1877 I [LGHome]EVENT: [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,03-19 12:53:19.684  1372  1506 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
03-19 12:53:19.684  1372  1506 D KeyguardModel: createShortcutInfo...
03-19 12:53:19.689  1372  1506 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
03-19 12:53:19.689  1372  1506 D KeyguardModel: createShortcutInfo...
,03-19 12:53:19.692  1372  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
03-19 12:53:19.697  1372  1506 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
03-19 12:53:19.699  1372  1506 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
03-19 12:53:19.699  1372  1506 D KeyguardModel: createShortcutInfo...
03-19 12:53:19.700  1372  1372 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
03-19 12:53:19.700  1372  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
03-19 12:53:19.701  1372  1506 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
03-19 12:53:19.702  1877  2002 I [LGHome]Launcher.Model: [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,03-19 12:53:19.705  1372  1506 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
03-19 12:53:19.705  1372  1506 D KeyguardModel: createShortcutInfo...
,03-19 12:53:19.726  1877  1877 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
03-19 12:53:19.727  1372  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
03-19 12:53:19.727  1372  1506 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
03-19 12:53:19.728  1877  1877 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
03-19 12:53:19.728  1877  1877 I Activity: Activity.onPostResume() called 
03-19 12:53:19.728  1372  1506 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
03-19 12:53:19.728  1372  1506 D KeyguardModel: createShortcutInfo...
03-19 12:53:19.748   826  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
03-19 12:53:19.748   826  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,03-19 12:53:19.750   826  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
03-19 12:53:19.750   826  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
03-19 12:53:19.751   278  1064 E BandwidthController: [LG DATA] No such appUid: 1000
03-19 12:53:19.751   278  1064 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
03-19 12:53:19.756  1877  5415 W [LGHome]LGWallpaperInfo: [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
03-19 12:53:19.756  1877  5415 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
03-19 12:53:19.759   278  5416 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
03-19 12:53:19.759   278  5416 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
03-19 12:53:19.759   278  5416 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
03-19 12:53:19.760   826  1019 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
03-19 12:53:19.760   826   826 I art     : Explicit concurrent mark sweep GC freed 20309(1284KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 8.314ms total 237.364ms
,03-19 12:53:19.763   826  1049 I art     : WaitForGcToComplete blocked for 86.266ms for cause Explicit
03-19 12:53:19.787  1372  1372 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
03-19 12:53:19.787  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,03-19 12:53:19.790  1372  1372 D KeyguardModel: handleShortcutListChanged...
03-19 12:53:19.792   826  1348 D InputDispatcher: Focus entered window: Window{e855c98 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
03-19 12:53:19.796   826  1021 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
03-19 12:53:19.797   826  1021 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
03-19 12:53:19.798   826  1021 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
03-19 12:53:19.798   826  1021 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
,03-19 12:53:19.798  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
03-19 12:53:19.799  1372  1506 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
03-19 12:53:19.799  1372  1506 D KeyguardModel: createShortcutInfo...
03-19 12:53:19.799   826  1021 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-19 12:53:19.799   826  1021 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@218d96a,  pkg=WindowManager.LayoutParams
03-19 12:53:19.799   826  1021 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
03-19 12:53:19.803  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
03-19 12:53:19.803  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
03-19 12:53:19.803  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
03-19 12:53:19.810  1372  1506 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
03-19 12:53:19.810  1372  1506 D KeyguardModel: createShortcutInfo...
,03-19 12:53:19.813  1372  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
,03-19 12:53:19.813  1372  1506 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
03-19 12:53:19.814  1877  1877 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-19 12:53:19.814  1877  1877 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-19 12:53:19.814  1877  1877 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
03-19 12:53:19.815  1372  1506 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
03-19 12:53:19.815  1372  1506 D KeyguardModel: createShortcutInfo...
03-19 12:53:19.820  1372  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
03-19 12:53:19.820  1372  1506 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
03-19 12:53:19.821  1372  1506 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
03-19 12:53:19.821  1372  1506 D KeyguardModel: createShortcutInfo...
03-19 12:53:19.823  5397  5397 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-19 12:53:19.823  5397  5397 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,03-19 12:53:19.824  5397  5397 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
03-19 12:53:19.824  1372  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
03-19 12:53:19.824  1372  1506 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
03-19 12:53:19.827  1372  1506 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
03-19 12:53:19.827  1372  1506 D KeyguardModel: createShortcutInfo...
03-19 12:53:19.830  1877  1877 I [LGHome]EVENT: [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
03-19 12:53:19.831   826   826 D administrator: Handling package changes for user 0
03-19 12:53:19.831  1877  1877 I PhoneWindow: [setNavigationBarColor] color=0x 0
03-19 12:53:19.835  1372  1372 D KeyguardModel: handleShortcutListChanged...
,03-19 12:53:19.949   826  1875 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
03-19 12:53:19.951   826  1875 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 4334 uid 10030
,03-19 12:53:20.019  1877  1877 I [LGHome]Launcher.Model: [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,03-19 12:53:20.025  1939  1939 I HotwordDetector: Closing mic
03-19 12:53:20.053  1877  1877 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,03-19 12:53:20.055  1877  1877 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
03-19 12:53:20.056  1877  1877 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
03-19 12:53:20.058  1877  1877 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
03-19 12:53:20.075  1939  2621 I HotwordRecognitionRnr: Stopping hotword detection.
,03-19 12:53:20.096  1877  1877 I [LGHome]Launcher.Model: [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
,03-19 12:53:20.100  1877  2205 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
03-19 12:53:20.100  1877  2205 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
03-19 12:53:20.136  1877  1877 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,03-19 12:53:20.141  1877  1877 I [LGHome]Launcher.Model: [LauncherModel.java:2257:run()] LauncherModel bind current page widget
03-19 12:53:20.142  5397  5397 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
03-19 12:53:20.143   826  1049 I art     : Explicit concurrent mark sweep GC freed 10089(744KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 3.469ms total 379.869ms
03-19 12:53:20.161  5397  5397 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,03-19 12:53:20.184  1877  1877 W Resources: Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
03-19 12:53:20.187  1877  1877 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
03-19 12:53:20.188  1877  1877 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
,03-19 12:53:20.188  1877  1877 W Resources: Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
03-19 12:53:20.193  1877  1877 W Resources: Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
03-19 12:53:20.204  1877  1877 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
03-19 12:53:20.204  1877  1877 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
03-19 12:53:20.207  1877  1877 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
,03-19 12:53:20.208  1877  1877 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
,03-19 12:53:20.208  1877  1877 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
03-19 12:53:20.218  1877  1877 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,03-19 12:53:20.228  1877  1877 W Resources: Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
03-19 12:53:20.240  1785  1785 D LCardEmulationManager: getHceAppCount hostAppNum : 0
03-19 12:53:20.240  1785  1785 D LCardEmulationManager: getDefaultRoute
,03-19 12:53:20.265  5373  5373 D AndroidRuntime: Shutting down VM
,03-19 12:53:20.297   826   826 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,03-19 12:53:20.298   826   826 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-19 12:53:20.300   826   826 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-19 12:53:20.319   826  1049 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=5424 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-19 12:53:20.325   826  1023 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1af70053 u0 com.lge.launcher2/.Launcher t225} time:88155
03-19 12:53:20.326   826  1350 D TaskPersister: removeObsoleteFile: deleting file=226_task.xml
03-19 12:53:20.338   309   309 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 21.267ms
,03-19 12:53:20.360   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 20.377ms
,03-19 12:53:20.379   826   960 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-19 12:53:20.381   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 20.446ms
,03-19 12:53:20.393  1877  1877 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,03-19 12:53:20.431  5397  5397 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,03-19 12:53:20.480   826  1875 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5445 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,03-19 12:53:20.481   826  1875 I ActivityManager: Killing 5210:com.android.gallery3d/u0a23 (adj 15): empty #11
03-19 12:53:20.491  1877  1877 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
03-19 12:53:20.491  1877  1877 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
,03-19 12:53:20.492  1877  1877 I [LGHome]Launcher.Model: [LauncherModel.java:2257:run()] LauncherModel bind current page widget
03-19 12:53:20.503   826   960 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,03-19 12:53:20.505  1877  1877 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
03-19 12:53:20.544  1877  1877 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,03-19 12:53:20.548  1877  1877 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
03-19 12:53:20.550  1877  1877 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
03-19 12:53:20.552  1877  1877 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
03-19 12:53:20.555  1877  1877 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
03-19 12:53:20.559   826  1876 W libprocessgroup: failed to open /acct/uid_10023/pid_5210/cgroup.procs: No such file or directory
,03-19 12:53:20.572   826  1875 I ActivityManager: Killing 5232:com.android.contacts/u0a18 (adj 15): empty #11
,03-19 12:53:20.599  5445  5445 I AppUp4:AppBoxCP: onCreate
,03-19 12:53:20.600  5445  5445 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
03-19 12:53:20.600  1939  5464 I HotwordRecognitionRnr: Starting hotword detection.
03-19 12:53:20.608  5445  5445 I AppUp4:DB:  setFingerPrint start
03-19 12:53:20.608  5445  5445 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
03-19 12:53:20.610  1939  5465 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@983db5f
03-19 12:53:20.611  1877  1877 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,03-19 12:53:20.627  5445  5445 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
03-19 12:53:20.627  5445  5445 I AppUp4:DB:  SDK version = 0
,03-19 12:53:20.628  5445  5445 I AppUp4:DB:  beforefinger == newfinger no write in DB
03-19 12:53:20.630   826  1883 W libprocessgroup: failed to open /acct/uid_10018/pid_5232/cgroup.procs: No such file or directory
03-19 12:53:20.634   826  1875 I ActivityManager: Killing 4987:com.google.android.apps.plus/u0a86 (adj 15): empty #11
03-19 12:53:20.636  5445  5445 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
03-19 12:53:20.637  1939  5465 V AudioRecord: set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
03-19 12:53:20.637  1939  5465 V AudioRecord: set(): mSessionId 23
03-19 12:53:20.645   282  1663 V AudioPolicyManager: getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 23, flags 0
03-19 12:53:20.645   282  1663 V AudioPolicyManager: getDeviceForInputSource()input source 1999, device 80000004
03-19 12:53:20.645   282  1663 V AudioPolicyManager: isPlaybackThread 0,isRecordThread 1
03-19 12:53:20.646   282  1663 D audio_hw_primary: adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546e420)
03-19 12:53:20.646   282  1663 V audio_hw_primary: adev_open_input_stream: exit
03-19 12:53:20.646   282  1663 V AudioFlinger: openInput_l() openInputStream returned input 0xb546e420, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
,03-19 12:53:20.648   282  1663 V AudioFlinger: openInput_l() created record thread: ID 24 thread 0xb3878000
03-19 12:53:20.648   282  1663 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
03-19 12:53:20.648   826  1359 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
03-19 12:53:20.648   282  5467 I AudioFlinger: AudioFlinger's thread 0xb3878000 ready to run
03-19 12:53:20.648   282  5467 D audio_hw_primary: in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
03-19 12:53:20.648   282  5467 V audio_hw_primary: in_standby: exit:  status(0)
03-19 12:53:20.649  2083  2099 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
03-19 12:53:20.649  3108  3124 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
03-19 12:53:20.648  2010  3380 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
03-19 12:53:20.649   282  5467 D audio_hw_primary: in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
03-19 12:53:20.649   282  5467 V audio_hw_primary: in_standby: exit:  status(0)
03-19 12:53:20.650   282  5467 V AudioFlinger: RecordThread: loop stopping
03-19 12:53:20.650  1372  1901 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
03-19 12:53:20.650  1750  1766 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
03-19 12:53:20.650   282  1663 V AudioPolicyService: AudioCommandThread() adding update audio port list
03-19 12:53:20.650  1939  1964 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
03-19 12:53:20.650   282  1663 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
03-19 12:53:20.650   282  1033 V AudioPolicyService: AudioCommandThread() waking up
03-19 12:53:20.650   282  1033 V AudioPolicyService: AudioCommandThread() processing update audio port list
03-19 12:53:20.650   282  1033 V AudioPolicyService: AudioCommandThread() going to sleep
03-19 12:53:20.651   282  1296 V AudioFlinger: openRecord() lSessionId: 23 input 24
03-19 12:53:20.652   282  1296 V AudioFlinger: getOrphanEffectChain_l session 23 index -2
03-19 12:53:20.653   282  1321 V AudioFlinger: acquiring 23 from 1939, for -1
03-19 12:53:20.653   282  1321 V AudioFlinger:  added new entry for 23
03-19 12:53:20.653  5445  5445 E SQLiteLog: (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
03-19 12:53:20.654  1939  5465 V AudioRecord: start, sync event 0 trigger session 0
03-19 12:53:20.654  1939  5465 V AudioRecord: mAudioRecord->start()
03-19 12:53:20.654   282  1663 V AudioFlinger: RecordHandle::start()
03-19 12:53:20.654   282  1663 V AudioFlinger: RecordThread::start event 0, triggerSession 0
03-19 12:53:20.654   282  1663 V AudioPolicyManager: startInput() module primary->input primary(24)
03-19 12:53:20.654   282  1663 V AudioPolicyManager: getDeviceForInputSource()input source 1999, device 80000004
03-19 12:53:20.654   282  1663 V AudioPolicyManager: getNewInputDevice() selected device 80000004
03-19 12:53:20.654   282  1663 V AudioPolicyManager: DeviceVector::refreshTypes() mDeviceTypes 80000004
03-19 12:53:20.654   282  1663 V AudioPolicyManager: DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
03-19 12:53:20.655   282  1663 V AudioPolicyService: AudioCommandThread() adding create patch delay 0
03-19 12:53:20.655   282  1663 V AudioPolicyService: inserting command: 7 at index 0, num commands 0
03-19 12:53:20.655   282  1032 V AudioPolicyService: AudioCommandThread() waking up
03-19 12:53:20.655   282  1032 V AudioPolicyService: AudioCommandThread() processing create audio patch
03-19 12:53:20.655   282  1032 V AudioFlinger::PatchPanel: createAudioPatch() num_sources 1 num_sinks 1 handle 0
03-19 12:53:20.655   282  1032 V AudioFlinger::PatchPanel: createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
03-19 12:53:20.655   282  1032 V AudioFlinger: ThreadBase::setParameters() input_source=6;routing=-2147483644
03-19 12:53:20.655   282  1032 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
03-19 12:53:20.655   282  5467 V AudioFlinger: RecordThrea,d: loop starting
03-19 12:53:20.655   282  5467 V AudioFlinger: processConfigEvents_l() remaining events 1
03-19 12:53:20.655   282  5467 D audio_hw_primary: in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
03-19 12:53:20.655   282  5467 V audio_hw_primary: in_set_parameters: exit: status(0)
03-19 12:53:20.655   282  5467 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3878000
03-19 12:53:20.655   282  1032 V AudioFlinger::PatchPanel: createAudioPatch() status 0
03-19 12:53:20.655   282  1032 V AudioFlinger::PatchPanel: createAudioPatch() added new patch handle 25 halHandle 0
03-19 12:53:20.655   282  1032 V AudioPolicyService: AudioCommandThread() going to sleep
03-19 12:53:20.656   282  1663 V AudioPolicyManager: setInputDevice() createAudioPatch returned 0 patchHandle 25
03-19 12:53:20.656   282  1663 V AudioPolicyManager: addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
03-19 12:53:20.656   282  1663 V AudioPolicyService: AudioCommandThread() adding update audio patch list
03-19 12:53:20.656   282  1663 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
03-19 12:53:20.656   282  1033 V AudioPolicyService: AudioCommandThread() waking up
03-19 12:53:20.656   282  1033 V AudioPolicyService: AudioCommandThread() processing update audio patch list
03-19 12:53:20.656   282  1033 V AudioPolicyService: AudioCommandThread() going to sleep
03-19 12:53:20.657   282  1663 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=1, io 24 ,delay 0
03-19 12:53:20.657   282  1663 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
03-19 12:53:20.657   282  1032 V AudioPolicyService: AudioCommandThread() waking up
03-19 12:53:20.657   282  1032 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=1, io 24
03-19 12:53:20.657   282  1032 V AudioFlinger: setParameters(): io 24, keyvalue hotword_active=1, calling pid 282
03-19 12:53:20.657   282  1032 V AudioFlinger: ThreadBase::setParameters() hotword_active=1
03-19 12:53:20.657   282  1032 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: Error inserting package=com.test.thalitest
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:790)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1581)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1451)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1267)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
03-19 12:53:20.659  5445  5445 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
03-19 12:53:20.665   282  5467 V AudioFlinger: processConfigEvents_l() remaining events 1
03-19 12:53:20.666   282  5467 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=1
03-19 12:53:20.666   282  5467 V audio_hw_primary: in_set_parameters: exit: status(0)
03-19 12:53:20.666   282  5467 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3878000
03-19 12:53:20.666   282  1032 V AudioPolicyService: AudioCommandThread() going to sleep
03-19 12:53:20.666   282  1663 V AudioPolicyManager: AudioPolicyManager::startInput() input source = 1999
03-19 12:53:20.678   282  5467 V msm8974_platform: platform_update_usecase_from_source: input source :6
03-19 12:53:20.678   282  5467 D audio_hw_primary: start_input_stream: enter: stream(0xb546e420)usecase(7: audio-record)
03-19 12:53:20.678   282  5467 V voice   : voice_check_and_set_incall_rec_usecase: voice call not active
03-19 12:53:20.678   282  5467 V audio_hw_primary: start_input_stream: usecase(7)
03-19 12:53:20.678   282  5467 E audio_hw_primary: select_devices: enter and usecase(7)
03-19 12:53:20.678   282  5467 V msm8974_platform: platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
03-19 12:53:20.678   282  5467 V msm8974_platform: platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
03-19 12:53:20.678   282  5467 V msm8974_platform_lge: LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
03-19 12:53:20.678   282  5467 V audio_hw_lge_primary: LGE_exeption_scenario: enter and out: 0, in: 144
03-19 12:53:20.678   282  5467 D audio_hw_primary: select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
03-19 12:53:20.678   282  5467 E audio_hw_primary: enable_snd_device: enter  144
03-19 12:53:20.678   282  5467 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
03-19 12:53:20.678   282  5467 V audio_hw_primary: enable_snd_device: snd_device(144: lg-vr-handset-mic)
03-19 12:53:20.679   282  5467 V msm8974_platform_lge: LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
03-19 12:53:20.680   282  5467 D ACDB-LOADER: ACDB -> send_audio_cal, acdb_id = 65, path =  1
03-19 12:53:20.680   282  5467 D ACDB-LOADER: ACDB -> send_adm_topology
03-19 12:53:20.680   282  5467 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
03-19 12:53:20.681   282  5467 D ACDB-LOADER: ACDB -> send_asm_topology
03-19 12:53:20.681   282  5467 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
03-19 12:53:20.681   282  5467 D ACDB-LOADER: ACDB -> send_audtable
03-19 12:53:20.681   282  5467 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
03-19 12:53:20.681   282  5467 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_CAL
03-19 12:53:20.681   282  5467 D ACDB-LOADER: ACDB -> send_audvoltable
03-19 12:53:20.681   282  5467 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
03-19 12:53:20.681   282  5467 D         : Failed to fetch the lookup information of the device 00000041 
03-19 12:53:20.681   282  5467 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-19 12:53:20.681   282  5467 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
03-19 12:53:20.681   282  5467 D ACDB-LOADER: ACDB -> AUDIO_SET_AFE_CAL
03-19 12:53:20.686   282  5467 V audio_hw_primary: enable_audio_route: enter: usecase(7)
03-19 12:53:20.686   282  5467 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
03-19 12:53:20.686   282  5467 V audio_hw_primary: enable_audio_route: apply mixer and update path: audio-record
03-19 12:53:20.686   282  5467 V audio_hw_primary: enable_audio_route: exit
03-19 12:53:20.686   282  5467 D audio_hw_primary: select_devices: done
03-19 12:53:20.686   282  5467 V audio_hw_primary: start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
03-19 12:53:20.690   282  5467 V audio_hw_primary: start_input_stream: exit
,03-19 12:53:20.697  1877  1877 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
03-19 12:53:20.719  1877  1877 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
03-19 12:53:20.719  1877  1877 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]

```
