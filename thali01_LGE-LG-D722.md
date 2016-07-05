#### Test 75789268eab05ed_thali01_LGE-LG-D722 Logs


```
--------- beginning of main
07-05 11:07:57.934   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 151953453643; DSPS: 5077017; Offset : -2992282264
,--------- beginning of system
07-05 11:07:58.221   862  1055 I PowerManagerService: ALS enabled for SRE
07-05 11:07:58.221   862  1055 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (32240 ms ago)
07-05 11:07:58.221   862  1055 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
07-05 11:07:58.232   862  1055 I PowerManagerService: ALS enabled for SRE
07-05 11:07:58.232   862  1055 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (32251 ms ago)
07-05 11:07:58.235   862  1055 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
07-05 11:07:58.241   862  1055 I PowerManagerService: Sleeping (uid 1000)...
07-05 11:07:58.241   862  1055 D LPWGController: [updateScreenState] screen on = false
07-05 11:07:58.243   862  1055 D LPWGController: disable proximity sensor
07-05 11:07:58.243   862  1055 D LPWGController: enable proximity sensor
07-05 11:07:58.253   862  1055 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@b99f5d] by com.android.server.power.ProximitySensorListener.enable():120
07-05 11:07:58.258   862  1055 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
07-05 11:07:58.258   862  1055 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
07-05 11:07:58.258   862  1055 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
07-05 11:07:58.258   862  1055 I sensors_hal_Ctx: activate: handle is 48, enable
07-05 11:07:58.258   862  1055 V sensors_hal_Ctx: activate sensors is 1400000000000
07-05 11:07:58.258   862  1055 D sensors_hal_Thresh: enable: handle=48
07-05 11:07:58.258   862  1055 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
07-05 11:07:58.258   862  1055 D sensors_hal_Util: waitForResponse: timeout=1000
07-05 11:07:58.265   862  1007 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
07-05 11:07:58.265   862  1007 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
07-05 11:07:58.265   862  1055 D sensors_hal_Thresh: enable: Received response: 0
07-05 11:07:58.268   862  1055 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (32287 ms ago)
07-05 11:07:58.308   862  1055 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-05 11:07:58.308   862  1055 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-05 11:07:58.308   862  1055 I Adreno-EGL: Build Date: 03/02/15 Mon
07-05 11:07:58.308   862  1055 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-05 11:07:58.308   862  1055 I Adreno-EGL: Remote Branch: 
07-05 11:07:58.308   862  1055 I Adreno-EGL: Local Patches: 
07-05 11:07:58.308   862  1055 I Adreno-EGL: Reconstruct Branch: 
07-05 11:07:58.356   244  1059 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (999 us)
07-05 11:07:58.490   422   994 I Sensors : sns_pwr.c(273):acquiring wakelock
07-05 11:07:58.491   862  1007 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
07-05 11:07:58.493   862  1007 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
07-05 11:07:58.493   862  1007 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
07-05 11:07:58.493   862  1007 D sensors_hal_Thresh: processInd: handle 48, count=1
07-05 11:07:58.493   862  1007 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
07-05 11:07:58.493   862  1007 I sensors_hal_Thresh: processInd : proximity state changed - FAR
07-05 11:07:58.493   862  1048 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
07-05 11:07:58.493   862  1048 D sensors_hal_Ctx: poll: count: 256
07-05 11:07:58.493   862  1048 I sensors_hal_Ctx: poll: released wakelock sensor_ind
07-05 11:07:58.493   862  1048 D sensors_hal_Util: waitForResponse: timeout=0
07-05 11:07:58.515  5657  5657 D AndroidRuntime: 
07-05 11:07:58.515  5657  5657 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 11:07:58.521  5657  5657 D AndroidRuntime: CheckJNI is OFF
07-05 11:07:58.556   862  1055 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
07-05 11:07:58.556   862  1055 I LPWGController: current mode = 1  value = 1 1
07-05 11:07:58.557   862  1055 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
07-05 11:07:58.601   862  1055 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
07-05 11:07:58.779  5657  5657 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 11:07:58.802   862  1963 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-05 11:07:58.857   862  1963 D ActivityManager: setTaskToReturnTo : TaskRecord{1cb665a3 #241 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-05 11:07:58.857   862  1963 D ActivityManager: setTaskToReturnTo : TaskRecord{1cb665a3 #241 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-05 11:07:58.869   862  1963 D WindowStateEx: AppWindowTokenEx init.. 
07-05 11:07:58.895   862  1053 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-05 11:07:58.905   862  1963 D InputDispatcher: Focus left window: Window{ce2ee41 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
07-05 11:07:58.906  5657  5657 D AndroidRuntime: Shutting down VM
07-05 11:07:58.911  1946  1946 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
07-05 11:07:58.912   862  1053 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-05 11:07:58.936   862  1053 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-05 11:07:58.936   862  1053 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-05 11:07:58.959   862  1053 D SplitWindow: check instance of lgWin Window{2de0e61b u0 Starting com.test.thalitest}
07-05 11:07:58.973   862  1347 D qdlights: set_light_backlight: 0
07-05 11:07:58.980   862  1055 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
07-05 11:07:58.980   862  1055 I sensors_hal_Ctx: activate: handle is 46, disable
07-05 11:07:58.981   862  1055 V sensors_hal_Ctx: activate sensors is 1000000000000
07-05 11:07:58.981   862  1055 D sensors_hal_LP2: enable: handle=46
07-05 11:07:58.981   862  1055 D sensors_hal_LP2: enable: Disabling sensor handle=46
07-05 11:07:58.981   862  1055 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
07-05 11:07:58.983   244   244 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
07-05 11:07:58.983   244   244 D qdhwcomposer: hwc_blank: Blanking display: 0
07-05 11:07:59.001   862  1973 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5686 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 11:07:59.011   862  1034 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
07-05 11:07:59.011   862  1034 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
07-05 11:07:59.102   290   353 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-05 11:07:59.173   244   684 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
07-05 11:07:59.172   244   244 D qdhwcomposer: hwc_blank: Done blanking display: 0
07-05 11:07:59.174   862  1347 D SurfaceControl: Excessive delay in setPowerMode(): 191ms
07-05 11:07:59.176   862  1347 I QCOM PowerHAL: Got set_interactive hint
07-05 11:07:59.199  1370  2011 D KeyguardViewMediator: onScreenTurnedOff(3)
07-05 11:07:59.205   862  1053 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
07-05 11:07:59.206  1329  1345 D SmartCoverViewMediator: onScreenTurnedOff(3)
07-05 11:07:59.208   862  1051 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
07-05 11:07:59.208  1946  1946 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
07-05 11:07:59.215   862  1051 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
07-05 11:07:59.227  1370  1370 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
07-05 11:07:59.230   862  1051 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
07-05 11:07:59.233   862  1051 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
07-05 11:07:59.233   862  1051 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 11:07:59.233   862  1051 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2bb03f7a,  pkg=WindowManager.LayoutParams
07-05 11:07:59.233   862  1051 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
07-05 11:07:59.234  1329  1345 D SmartCoverViewMediator: notifyScreenOffLocked
07-05 11:07:59.237  1370  1370 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
07-05 11:07:59.237  1370  1370 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
07-05 11:07:59.237  1370  1370 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
07-05 11:07:59.237  1329  1329 D SmartCoverViewMediator: handleNotifyScreenOFF
07-05 11:07:59.238  1370  2011 D KeyguardViewMediator: notifyScreenOffLocked
07-05 11:07:59.285   862  1053 I WindowStateAnimator: Starting window displayed
07-05 11:07:59.292  1787  1787 D DSDPConnection: Display #0 changed.
07-05 11:07:59.347   862   862 V ActivityManager: Display changed displayId=0
07-05 11:07:59.356  1370  2011 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
07-05 11:07:59.358  1370  1370 D KeyguardViewMediator: handleNotifyScreenOff
07-05 11:07:59.393  1370  1370 D ScreenTurnOffBySensor: unregisterProximitySensor
07-05 11:07:59.393  2023  2023 I HotwordDetector: Closing mic
07-05 11:07:59.404  1946  1946 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
07-05 11:07:59.406  1370  1370 D StatusBarWindowView: onScreenTurnedOff why = 3
07-05 11:07:59.416  2023  2613 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@3f91e111
07-05 11:07:59.416  2023  2613 V AudioRecord: stop()
07-05 11:07:59.416  2023  2613 D AudioRecord: AudioRecord->stop()
07-05 11:07:59.416   277  1299 V AudioFlinger: RecordHandle::stop()
07-05 11:07:59.416   277  1299 V AudioFlinger: RecordThread::stop
07-05 11:07:59.430   277  1299 V AudioFlinger: Record stopped OK
07-05 11:07:59.430   277  1299 V AudioPolicyManager: stopInput() input 17
07-05 11:07:59.432   277  1299 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
07-05 11:07:59.432   277  1299 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
07-05 11:07:59.432   277  1063 V AudioPolicyService: AudioCommandThread() waking up
07-05 11:07:59.433   277  1063 V AudioPolicyService: AudioCommandThread() processing release audio patch
07-05 11:07:59.433   277  1063 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
07-05 11:07:59.433   277  1063 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
07-05 11:07:59.433   277  1063 V AudioFlinger: ThreadBase::setParameters() routing=0
07-05 11:07:59.433   277  1063 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
07-05 11:07:59.435   277  2641 V AudioFlinger: processConfigEvents_l() remaining events 1
07-05 11:07:59.437   277  2641 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3c49000
07-05 11:07:59.441   277  2641 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
07-05 11:07:59.447   862   862 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
07-05 11:07:59.450   277   277 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 862
07-05 11:07:59.489   277  2641 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
07-05 11:07:59.489   277  2641 V audio_hw_primary: disable_audio_route: enter: usecase(7)
07-05 11:07:59.489   277  2641 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
07-05 11:07:59.489   277  2641 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-05 11:07:59.491   277  2641 V audio_hw_primary: disable_audio_route: exit
07-05 11:07:59.491   277  2641 E audio_hw_primary: disable_snd_device: enter 144
07-05 11:07:59.491   277  2641 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
07-05 11:07:59.491   277  2641 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
07-05 11:07:59.495   277  2641 V audio_hw_primary: stop_input_stream: exit: status(0)
07-05 11:07:59.495   277  2641 V audio_hw_primary: in_standby: exit:  status(0)
07-05 11:07:59.495   277  2641 V AudioFlinger: RecordThread: loop stopping
07-05 11:07:59.495   277  1063 V AudioPolicyService: AudioCommandThread() going to sleep
07-05 11:07:59.495   277   277 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-05 11:07:59.496   277   277 V voice   : voice_set_parameters: enter: screen_state=on
07-05 11:07:59.496   277   277 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
07-05 11:07:59.496   277   277 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-05 11:07:59.496   277   277 V voice   : voice_set_parameters: exit with code(0)
07-05 11:07:59.496   277   277 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
07-05 11:07:59.496   277   277 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-05 11:07:59.496   277   277 V msm8974_platform: platform_set_parameters: exit with code(0)
07-05 11:07:59.496   277   277 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-05 11:07:59.496   277   277 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
07-05 11:07:59.496   277   277 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
07-05 11:07:59.496   277   277 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-05 11:07:59.496   277  1299 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
07-05 11:07:59.496   277  1299 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
07-05 11:07:59.496   277  1299 V AudioPolicyService: AudioCommandThread() adding update audio patch list
07-05 11:07:59.496   277  1299 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
07-05 11:07:59.496   277  1064 V AudioPolicyService: AudioCommandThread() waking up
07-05 11:07:59.496   277  1064 V AudioPolicyService: AudioCommandThread() processing update audio patch list
07-05 11:07:59.497   277  1064 V AudioPolicyService: AudioCommandThread() going to sleep
07-05 11:07:59.497   277  1299 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
07-05 11:07:59.497   277  1299 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
07-05 11:07:59.498   277  1063 V AudioPolicyService: AudioCommandThread() waking up
07-05 11:07:59.498   277  1063 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
07-05 11:07:59.498   277  1063 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 277
07-05 11:07:59.499   277  1063 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
07-05 11:07:59.499   277  1063 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
07-05 11:07:59.499   277  2641 V AudioFlinger: RecordThread: loop starting
07-05 11:07:59.500   277  2641 V AudioFlinger: processConfigEvents_l() remaining events 1
07-05 11:07:59.500   277  2641 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
07-05 11:07:59.500   277  2641 V audio_hw_primary: in_set_parameters: exit: status(0)
07-05 11:07:59.500   277  2641 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3c49000
07-05 11:07:59.500   277  2641 V AudioFlinger: RecordThread: loop stopping
07-05 11:07:59.501   277  1063 V AudioPolicyService: AudioCommandThread() going to sleep
07-05 11:07:59.506  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:07:59.508  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
07-05 11:07:59.516  2023  2613 V AudioRecord: stop()
07-05 11:07:59.517  2023  2613 V AudioRecord: stop()
07-05 11:07:59.517  2023  2613 V AudioRecord: stop()
07-05 11:07:59.519   277  1612 V AudioFlinger: RecordHandle::stop()
07-05 11:07:59.519   277  1612 V AudioFlinger: RecordThread::stop
07-05 11:07:59.519   277  1612 V AudioPolicyManager: releaseInput() 17
07-05 11:07:59.519   277  1612 V AudioPolicyManager: closeInput(17)
07-05 11:07:59.519   277  1612 V AudioFlinger: closeInput() 17
07-05 11:07:59.519   277  1612 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 11:07:59.519  1370  1412 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 11:07:59.519   277  1612 V AudioFlinger: ThreadBase::exit
07-05 11:07:59.519  2056  2071 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 11:07:59.520  3091  3107 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 11:07:59.520  2075  2096 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 11:07:59.520   277  2641 V AudioFlinger: RecordThread: loop starting
07-05 11:07:59.520  2023  2248 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 11:07:59.520   277  2641 V AudioFlinger: RecordThread 0xb3c49000 exiting
07-05 11:07:59.520   862   881 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 11:07:59.521   277  1612 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546dd40)
07-05 11:07:59.521   277  1612 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
07-05 11:07:59.521   277  1612 V audio_hw_primary: in_standby: exit:  status(0)
07-05 11:07:59.521   277  1612 V AudioPolicyService: AudioCommandThread() adding update audio port list
07-05 11:07:59.521  1787  1814 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 11:07:59.522   277  1612 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
07-05 11:07:59.522   277  1612 V AudioPolicyManager: releaseInput() exit
07-05 11:07:59.522   277  1064 V AudioPolicyService: AudioCommandThread() waking up
07-05 11:07:59.522   277  1064 V AudioPolicyService: AudioCommandThread() processing update audio port list
07-05 11:07:59.522   277   277 V AudioFlinger: releasing 16 from 2023 for -1
07-05 11:07:59.522   277   277 V AudioFlinger:  decremented refcount to 0
07-05 11:07:59.522   277  1612 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
07-05 11:07:59.522   277   277 V AudioFlinger: purging stale effects
07-05 11:07:59.522   277  1612 V AudioFlinger: removeClient_l() pid 2023, calling pid 277
07-05 11:07:59.522   277  1064 V AudioPolicyService: AudioCommandThread() going to sleep
07-05 11:07:59.525  5686  5686 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-05 11:07:59.526  2023  2626 I HotwordRecognitionRnr: Stopping hotword detection.
07-05 11:07:59.532  2023  2632 I HotwordRecognitionRnr: Hotword detection finished
07-05 11:07:59.656  5686  5686 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
07-05 11:07:59.733  5686  5686 I LibraryLoader: Time to load native libraries: 13 ms (timestamps 3739-3752)
07-05 11:07:59.734  5686  5686 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 11:07:59.748   862  1001 W ActivityManager: Activity pause timeout for ActivityRecord{bb320a0 u0 com.test.thalitest/.MainActivity t241}
07-05 11:07:59.762  5686  5686 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {260dd8ff}
07-05 11:07:59.763  5686  5686 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 11:07:59.766  5686  5686 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 11:07:59.782  5686  5686 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 11:07:59.783  5686  5686 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 11:07:59.787  5686  5686 E SysUtils: ApplicationContext is null in ApplicationStatus
07-05 11:07:59.837  5686  5723 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
07-05 11:07:59.855  5686  5686 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-05 11:07:59.861  5686  5686 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 11:07:59.861  5686  5686 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 11:07:59.862  5686  5686 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-05 11:07:59.862  5686  5686 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-05 11:07:59.862  5686  5686 I Adreno-EGL: Build Date: 03/02/15 Mon
07-05 11:07:59.862  5686  5686 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-05 11:07:59.862  5686  5686 I Adreno-EGL: Remote Branch: 
07-05 11:07:59.862  5686  5686 I Adreno-EGL: Local Patches: 
07-05 11:07:59.862  5686  5686 I Adreno-EGL: Reconstruct Branch: 
07-05 11:07:59.937   277  1357 V AudioPolicyService: registerClient() client 0xb551c600, uid 10030
07-05 11:07:59.953   862  1052 D BluetoothManagerService: Message: 20
07-05 11:07:59.954   862  1052 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c9ff1d0:true
07-05 11:07:59.978  2056  3335 D BluetoothAdapterService(326204693): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3dd01d93
07-05 11:07:59.990   422   431 I Sensors : sns_pwr.c(301):releasing wakelock
07-05 11:08:00.001   862  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=376688488, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=862
07-05 11:08:00.075  5686  5686 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 11:08:00.086  5686  5686 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-05 11:08:00.094  5686  5686 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-05 11:08:00.098  5686  5686 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-05 11:08:00.098  5686  5686 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-05 11:08:00.099  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:08:00.099  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:08:00.099  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
07-05 11:08:00.100  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:08:00.100  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:08:00.102  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:08:00.103  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:08:00.113  5686  5686 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
07-05 11:08:00.115   862  1000 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
07-05 11:08:00.122  5686  5686 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 11:08:00.122  5686  5686 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 11:08:00.150   862   881 D SplitWindow: check instance of lgWin Window{3aadb032 u0 SearchPanel}
07-05 11:08:00.167  1909  1909 I QCNEJ   : |CORE| sendScreenState: state:true
07-05 11:08:00.169  1873  2037 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
07-05 11:08:00.169  1873  2037 D LEDService: stopPatternFlashing()
07-05 11:08:00.171  1873  2037 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 11:08:00.173  1873  2037 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-05 11:08:00.173  1873  2037 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 11:08:00.174   862  2111 D InputDispatcher: Window went away: Window{36902e16 u0 SearchPanel}
07-05 11:08:00.174  1873  2037 I LEDService: updateLightsLocked : turn off led
07-05 11:08:00.174  1873  2037 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 11:08:00.175  1370  1370 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
07-05 11:08:00.176  1873  2037 D LEDHandler: RESTART MSG
07-05 11:08:00.194  1370  1370 I LgeClockWidgetControlView: time changed, timezoneChanged : false
07-05 11:08:00.197  5686  5686 I Activity: Activity.onPostResume() called 
07-05 11:08:00.203  1873  1873 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
07-05 11:08:00.203  1873  1873 D Cliptray Service: lockStatus = 0
07-05 11:08:00.205  5686  5748 D OpenGLRenderer: Render dirty regions requested: true
07-05 11:08:00.205  5686  5748 I OpenGLRenderer: Initialized EGL, version 1.4
07-05 11:08:00.206  1855  1855 D LNfcService: action : android.intent.action.SCREEN_ON
07-05 11:08:00.213  1855  5749 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
07-05 11:08:00.213  1855  5749 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
07-05 11:08:00.213  1855  5749 D LNfcService: isRequireNfcCRouting() return true
07-05 11:08:00.213  1855  5749 D LNfcService: isHCERoutingtoHost() return : true
07-05 11:08:00.213  1855  5749 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
07-05 11:08:00.213  1855  5749 D NfcService: mEnableLPD: true
07-05 11:08:00.213  1855  5749 D NfcService: mEnableReader: false
07-05 11:08:00.213  1855  5749 D NfcService: mEnableHostRouting: true
07-05 11:08:00.213  1855  5749 D NfcService: newParams.techmask= mTechMask: default
07-05 11:08:00.213  1855  5749 D NfcService: mEnableLPD: true
07-05 11:08:00.213  1855  5749 D NfcService: mEnableReader: false
07-05 11:08:00.213  1855  5749 D NfcService: mEnableHostRouting: true
07-05 11:08:00.213  1855  5749 D NfcService: screenState= 3
07-05 11:08:00.213  1855  5749 D NfcService: Discovery configuration equal, not updating.
07-05 11:08:00.221  5686  5748 D OpenGLRenderer: Enabling debug mode 0
07-05 11:08:00.228   862   862 D Ulp_jni : JNI:system_update. Event-0
07-05 11:08:00.243  5686  5686 D Atlas   : Validating map...
07-05 11:08:00.249   862  1973 D SplitWindow: check instance of lgWin Window{3829d7e u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 11:08:00.261  1787  1787 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
07-05 11:08:00.275  5686  5735 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-05 11:08:00.289  2829  2829 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:8:0
07-05 11:08:00.291  2829  2829 D WeatherService: 2 : ACTION screen on
07-05 11:08:00.293  2829  2829 D WeatherService: 2 : shouldTimeTickRegistered : false
07-05 11:08:00.299  2829  2829 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-05 11:08:00.299  2829  2829 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:8:0
07-05 11:08:00.311  3959  3959 D AppCleanupService: android.intent.action.SCREEN_ON
07-05 11:08:00.319   862  1915 D InputDispatcher: Focus entered window: Window{3829d7e u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 11:08:00.337  2829  2829 D WeatherService: 2 : TimeTick Intent has been received, Time(hour:min:sec) 11:8:0
07-05 11:08:00.337  2829  2829 D WeatherService: 2 : TimeTick Intent has been processed, Time(hour:min:sec) 11:8:0
07-05 11:08:00.346   862  1376 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
07-05 11:08:00.348   862  1053 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{bb320a0 u0 com.test.thalitest/.MainActivity t241} time:154367
07-05 11:08:00.358   862   862 D PowerManagerServiceEx: releaseWakeLockInternal: lock=376688488 [*alarm*], flags=0x0
07-05 11:08:00.372  5686  5686 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@192a4501 time:154391
07-05 11:08:00.374   277  1612 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 862
07-05 11:08:00.374   277  1612 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
07-05 11:08:00.374   277  1612 V voice   : voice_set_parameters: enter: screen_state=off
07-05 11:08:00.374   277  1612 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
07-05 11:08:00.374   277  1612 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-05 11:08:00.374   277  1612 V voice   : voice_set_parameters: exit with code(0)
07-05 11:08:00.374   277  1612 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
07-05 11:08:00.374   277  1612 V msm8974_platform: platform_set_parameters: enter: screen_state=off
07-05 11:08:00.374   277  1612 V msm8974_platform: platform_set_parameters: exit with code(0)
07-05 11:08:00.374   277  1612 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-05 11:08:00.375   277  1612 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
07-05 11:08:00.375   277  1612 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-05 11:08:00.377   862  1313 D WifiController: CMD_SCREEN_OFF 
07-05 11:08:00.377   862  1313 D WifiController: shouldWifiStayAwake TRUE
07-05 11:08:00.388  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
07-05 11:08:00.389   862  1000 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
07-05 11:08:00.453  5686  5686 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
07-05 11:08:00.460  1632  1632 E b       : Unable to connect to the editor to retrieve text... will retry later
07-05 11:08:00.478  5686  5686 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
07-05 11:08:00.500  5686  5686 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5686
,07-05 11:08:00.583  1909  1909 I QCNEJ   : |CORE| sendScreenState: state:false
,07-05 11:08:00.585  1873  2037 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
07-05 11:08:00.585  1873  2037 D LEDService: stopPatternFlashing()
07-05 11:08:00.585  1873  2037 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 11:08:00.587  1873  2037 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-05 11:08:00.587  1873  2037 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 11:08:00.589  1873  2037 I LEDService: updateLightsLocked : turn on led
07-05 11:08:00.589  1873  2037 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
07-05 11:08:00.589  1873  2037 E LEDService: Can't handle this request of patternId:0
07-05 11:08:00.589  1873  2037 D LEDHandler: RESTART MSG
07-05 11:08:00.590  1873  1873 D VolumeVibrator: clear
07-05 11:08:00.591  1873  1873 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
07-05 11:08:00.592  1855  1855 D LNfcService: action : android.intent.action.SCREEN_OFF
07-05 11:08:00.596  1855  2199 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
,07-05 11:08:00.601  1946  1946 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
07-05 11:08:00.609  1787  1787 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,07-05 11:08:00.615  2829  2829 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 11:8:0
07-05 11:08:00.615  2829  2829 D WeatherService: 2 : ACTION screen off
07-05 11:08:00.615  2829  2829 D WeatherService: 2 : TimeTick Receiver Unregister
07-05 11:08:00.616  2829  2829 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 11:8:0
07-05 11:08:00.619  3959  3959 D AppCleanupService: android.intent.action.SCREEN_OFF
,07-05 11:08:00.622  3959  5769 D AppCleanupService: AppUsageStatsSaveTask
,07-05 11:08:00.662  5686  5686 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 11:08:00.688  1855  2676 E NxpNfcJni: getReconnectState = 0x0
,07-05 11:08:00.692  1855  2199 D LCardEmulationManager: getHceAppCount hostAppNum : 0
07-05 11:08:00.692  1855  2199 D LCardEmulationManager: getDefaultRoute
07-05 11:08:00.692  1855  2199 D LNfcService: isRequireNfcCRouting() return true
07-05 11:08:00.692  1855  2199 D LNfcService: isHCERoutingtoHost() return : true
07-05 11:08:00.692  1855  2199 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
07-05 11:08:00.692  1855  2199 D NfcService: mEnableLPD: true
07-05 11:08:00.692  1855  2199 D NfcService: mEnableReader: false
07-05 11:08:00.692  1855  2199 D NfcService: mEnableHostRouting: true
07-05 11:08:00.692  1855  2199 D NfcService: newParams.techmask= mTechMask: 0
07-05 11:08:00.692  1855  2199 D NfcService: mEnableLPD: true
07-05 11:08:00.692  1855  2199 D NfcService: mEnableReader: false
07-05 11:08:00.692  1855  2199 D NfcService: mEnableHostRouting: true
07-05 11:08:00.692  1855  2199 D NfcService: screenState= 1
07-05 11:08:00.750  1855  2676 E NxpNfcJni: getReconnectState = 0x0
,07-05 11:08:00.923  5686  5686 I chromium: [INFO:CONSOLE(90)] "Uncaught SyntaxError: Unexpected token function", source: file:///android_asset/www/js/thali_main.js (90)
,07-05 11:08:00.979  5686  5758 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426120960
,07-05 11:08:00.997  5686  5758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 11:08:00.997  5686  5758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 11:08:00.997  5686  5758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 11:08:00.997  5686  5758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 11:08:00.997  5686  5758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-05 11:08:00.997  5686  5758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ee729f5 added. We now have 1 listener(s)
07-05 11:08:01.002   862  1641 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-05 11:08:01.009  5686  5758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,07-05 11:08:01.012  5686  5758 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
07-05 11:08:01.014  5686  5758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 11:08:01.014  5686  5758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-05 11:08:01.020  5686  5758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 11:08:01.020  5686  5758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 11:08:01.020  5686  5758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 11:08:01.020  5686  5758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
07-05 11:08:01.020  5686  5758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 11:08:01.020  5686  5758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 11:08:01.020  5686  5758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 11:08:01.020  5686  5758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 11:08:01.020  5686  5758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 11:08:01.020  5686  5758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 11:08:01.020  5686  5758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 11:08:01.021  5686  5758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe5be18 added. We now have 1 listener(s)
07-05 11:08:01.021  5686  5758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-05 11:08:01.029  2056  2072 D BluetoothAdapterService(326204693): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3dd01d93
,07-05 11:08:01.030  5686  5758 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-05 11:08:01.038  5686  5758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-05 11:08:01.038  5686  5758 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-05 11:08:01.040  5686  5758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 11:08:01.041   862  1872 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-05 11:08:01.041  5686  5758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
07-05 11:08:01.047  2056  2072 D BluetoothAdapterService(326204693): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3dd01d93
07-05 11:08:01.048  5686  5758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 11:08:01.048  5686  5758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 11:08:01.048  5686  5758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 11:08:01.048  5686  5758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-05 11:08:01.048  5686  5758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 11:08:01.048  5686  5758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 11:08:01.048  5686  5758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 11:08:01.048  5686  5758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-05 11:08:01.048  5686  5758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 11:08:01.048  5686  5758 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 11:08:01.049  5686  5758 I io.jxcore.node.LifeCycleMonitor: start: OK
07-05 11:08:01.068  5686  5686 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 11:08:01.216  5686  5700 I art     : CheckpointMarkThreadRoots callback created = 0xb0777f70
,07-05 11:08:01.247  5686  5700 I art     : CheckpointMarkThreadRoots callback created = 0xb0777f40
,07-05 11:08:01.769  5686  5778 W jxcore-log: Initializing JXcore engine
07-05 11:08:01.769  5686  5778 W jxcore-log: JXcore engine is ready
,07-05 11:08:01.842  5778  5778 W Thread-659: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6726]" dev="sockfs" ino=6726 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-05 11:08:01.842  5778  5778 W Thread-659: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-05 11:08:01.842  5778  5778 W Thread-659: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7354]" dev="sockfs" ino=7354 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-05 11:08:01.842  5778  5778 W Thread-659: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
07-05 11:08:01.842  5778  5778 W Thread-659: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
07-05 11:08:01.842  5778  5778 W Thread-659: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[27686]" dev="sockfs" ino=27686 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-05 11:08:01.876  5686  5778 W jxcore-log: Starting JXcore engine
,07-05 11:08:02.020  5686  5778 W jxcore-log: Platform android
07-05 11:08:02.020  5686  5778 W jxcore-log: 
,07-05 11:08:02.020  5686  5778 W jxcore-log: Process ARCH arm
07-05 11:08:02.020  5686  5778 W jxcore-log: 
,07-05 11:08:02.297  5686  5778 I jxcore-log: JXcore Cordova bridge is ready!
07-05 11:08:02.297  5686  5778 I jxcore-log: 
07-05 11:08:02.298  5686  5778 W jxcore-log: JXcore engine is started
,07-05 11:08:04.107   290   353 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-05 11:08:04.262   862  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{234e89e2 type 2 when 158270 com.android.systemui} when 158270
,07-05 11:08:04.264  1370  1370 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,07-05 11:08:04.283  1787  2306 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
07-05 11:08:04.290  1787  2306 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-05 11:08:04.290  1787  2306 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-05 11:08:04.291  1787  2306 V TelecomServiceImpl: getCallState : 0
07-05 11:08:04.293  1787  1814 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
07-05 11:08:04.293  1787  1814 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-05 11:08:04.293  1787  1814 D PhoneUtils: getPhoneCount() sPhoneCount = 1
,07-05 11:08:04.297  1370  1370 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
07-05 11:08:04.299  1370  1370 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,07-05 11:08:09.112   290   353 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-05 11:08:14.117   290   353 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-05 11:08:17.936   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:08:17.936   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:08:17.936   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 171955103427; DSPS: 5732432; Offset : -2992311364
,07-05 11:08:19.122   290   353 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-05 11:08:21.605  2376  2804 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 11:08:24.128   290   353 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-05 11:08:25.346   862  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3d3fc173 type 2 when 179346 com.google.android.gms} when 179346
,07-05 11:08:25.362   862  1767 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:08:25.362   862  1767 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 11:08:25.366   862  1767 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:08:25.366   862  1767 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:08:25.367   271  1041 E BandwidthController: [LG DATA] No such appUid: 1000
07-05 11:08:25.367   271  1041 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-05 11:08:25.371   271  5816 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 11:08:25.371   271  5816 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:08:25.371   271  5816 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 11:08:25.372   862  1050 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-05 11:08:29.133   290   353 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-05 11:08:30.628   862  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3b4b01cf type 2 when 184637 com.google.android.gms} when 184637
,07-05 11:08:33.247   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:08:33.250  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:08:33.251  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:08:33.251  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:08:33.251  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:08:33.251  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:08:33.295  2056  3336 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 11:08:33.298  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 11:08:33.298  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 11:08:33.299  1873  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:08:33.299  1873  2037 D LEDHandler: Battery Level Remaining: 100%
07-05 11:08:33.300  1873  2037 D LEDHandler: Battery Temp: 318, mChargingStatus=5, mChargingStop=false
07-05 11:08:33.300  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 318
07-05 11:08:33.301  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:08:33.302  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 318
07-05 11:08:33.304  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:08:33.307   862  1313 D WifiController: battery changed pluggedType: 2
,07-05 11:08:33.313  5518  5518 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 11:08:34.139   290   353 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-05 11:08:34.374   862  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{e97075c type 2 when 188383 com.google.android.gms} when 188383
,07-05 11:08:34.382  2376  5828 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:08:34.382  2376  5828 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 11:08:34.382  2376  5828 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:08:34.382  2376  5828 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:08:34.383   271  1041 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 11:08:34.383   271  1041 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 11:08:34.383   271  5829 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 11:08:34.383   271  5829 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:08:34.384   271  5829 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 11:08:34.389   862  1050 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,07-05 11:08:37.938   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:08:37.938   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:08:37.938   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 191957093629; DSPS: 6387857; Offset : -2992304699
,07-05 11:08:39.144   290   353 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 11:08:44.150   290   353 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 11:08:49.156   290   353 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 11:08:50.636   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:08:50.638  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:08:50.638  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:08:50.638  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:08:50.638  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:08:50.645  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:08:50.680  2056  3336 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 11:08:50.683  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 11:08:50.684  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 11:08:50.685  1873  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:08:50.685  1873  2037 D LEDHandler: Battery Level Remaining: 100%
07-05 11:08:50.685  1873  2037 D LEDHandler: Battery Temp: 318, mChargingStatus=5, mChargingStop=false
07-05 11:08:50.685  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 318
07-05 11:08:50.685  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:08:50.686  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 318
07-05 11:08:50.690   862  1313 D WifiController: battery changed pluggedType: 2
07-05 11:08:50.691  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:08:50.691  5518  5518 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-05 11:08:54.161   290   353 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 11:08:55.358   862  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{7b45a65 type 2 when 209364 com.google.android.gms} when 209364
,07-05 11:08:56.052  2376  2376 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=25684ccd-d17f-4b76-9c40-31e177fcb6c8
,07-05 11:08:56.073  2376  2376 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 11:08:56.075  2376  2376 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 11:08:56.179  2376  2791 W GCoreFlp: No location to return for getLastLocation()
,07-05 11:08:56.220  5364  5832 D UdcContextInitService: registered all accounts: true
,07-05 11:08:56.254  5364  5832 I GAv4-SVC: Google Analytics 9.2.56 is starting up.
,07-05 11:08:56.386   862  1973 I art     : Explicit concurrent mark sweep GC freed 45518(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/34MB, paused 2.694ms total 163.481ms
,07-05 11:08:56.388  2376  2774 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-05 11:08:56.402  2376  2728 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-05 11:08:56.464  2376  2728 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-05 11:08:56.501  2376  2728 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,07-05 11:08:57.939   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:08:57.939   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:08:57.939   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 211958122736; DSPS: 7043250; Offset : -2992282621
,07-05 11:08:58.522  2376  2728 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-05 11:08:58.525  2376  2728 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
07-05 11:08:59.167   290   353 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 11:09:00.038  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:09:00.038  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:09:00.038  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:09:00.043  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:09:00.043  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:09:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:09:00.045  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:09:00.053   862  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=376688488, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=862
,07-05 11:09:00.056   862  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2cbeffa8 type 2 when 214063 android} when 214063
07-05 11:09:00.057   862  1286 V AlarmManager: RTC_WAKEUP set : Alarm{23283ac1 type 0 when 1467709735765 com.google.android.gms} when 1467709735765
07-05 11:09:00.114   862   862 D PowerManagerServiceEx: releaseWakeLockInternal: lock=376688488 [*alarm*], flags=0x0
,07-05 11:09:00.173  5364  5862 I EventLogChimeraService: Aggregate from 1467707935687 (log), 1467707935687 (data)
,07-05 11:09:00.436  5364  5870 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-05 11:09:00.582  2376  2404 I art     : Explicit concurrent mark sweep GC freed 39313(2MB) AllocSpace objects, 26(416KB) LOS objects, 40% free, 14MB/24MB, paused 1.778ms total 127.058ms
,07-05 11:09:00.597  5364  5870 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-05 11:09:04.173   290   353 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 11:09:09.178   290   353 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 11:09:14.184   290   353 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 11:09:17.941   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:09:17.941   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:09:17.941   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 231959643872; DSPS: 7698660; Offset : -2992286920
,07-05 11:09:19.190   290   353 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 11:09:24.196   290   353 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 11:09:29.205   290   353 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 11:09:33.407   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:09:33.416  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:09:33.416  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:09:33.417  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:09:33.417  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:09:33.417  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:09:33.456  2056  3336 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 11:09:33.460  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 11:09:33.460  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 11:09:33.462  1873  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:09:33.462  1873  2037 D LEDHandler: Battery Level Remaining: 100%
07-05 11:09:33.462  1873  2037 D LEDHandler: Battery Temp: 315, mChargingStatus=5, mChargingStop=false
07-05 11:09:33.462  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 315
07-05 11:09:33.462  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:09:33.463  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 315
07-05 11:09:33.468   862  1313 D WifiController: battery changed pluggedType: 2
,07-05 11:09:33.472  5518  5518 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 11:09:33.473  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:09:34.210   290   353 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 11:09:37.942   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:09:37.942   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:09:37.942   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 251960857565; DSPS: 8354060; Offset : -2992294087
,07-05 11:09:39.216   290   353 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 11:09:44.221   290   353 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 11:09:49.226   290   353 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 11:09:54.231   290   353 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 11:09:57.942   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:09:57.943   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:09:57.943   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 271961593599; DSPS: 9009444; Offset : -2992290528
,07-05 11:09:59.237   290   353 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 11:10:00.041  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:10:00.041  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:10:00.041  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:10:00.045  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:10:00.045  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:10:00.046  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:10:00.046  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:10:04.242   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:10:09.248   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:10:14.253   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:10:17.944   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:10:17.944   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:10:17.944   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 291963117758; DSPS: 9664854; Offset : -2992292247
,07-05 11:10:19.259   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:10:24.264   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:10:29.269   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:10:33.566   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:10:33.569  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:10:33.570  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:10:33.570  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:10:33.570  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:10:33.570  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:10:33.608  2056  3336 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 11:10:33.612  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 313
07-05 11:10:33.612  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:10:33.612  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 313
07-05 11:10:33.613  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 11:10:33.613  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 11:10:33.614  1873  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:10:33.615  1873  2037 D LEDHandler: Battery Level Remaining: 100%
07-05 11:10:33.615  1873  2037 D LEDHandler: Battery Temp: 313, mChargingStatus=5, mChargingStop=false
07-05 11:10:33.617  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:10:33.620   862  1313 D WifiController: battery changed pluggedType: 2
,07-05 11:10:33.624  5518  5518 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 11:10:34.275   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:10:37.946   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:10:37.946   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:10:37.946   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 311964730406; DSPS: 10320267; Offset : -2992297265
,07-05 11:10:39.280   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:10:44.286   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:10:49.292   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:10:54.297   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:10:57.946   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:10:57.946   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:10:57.947   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 331965553002; DSPS: 10975654; Offset : -2992300414
,07-05 11:10:58.677   862  1767 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:10:58.677   862  1767 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 11:10:58.677   862  1767 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:10:58.677   862  1767 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-05 11:10:58.687   862  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2bd733b5 type 2 when 332686 com.google.android.gms} when 332686
07-05 11:10:58.689   271  1041 E BandwidthController: [LG DATA] No such appUid: 1000
07-05 11:10:58.689   271  1041 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
,07-05 11:10:58.694   271  5895 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 11:10:58.694   271  5895 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:10:58.695   271  5895 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 11:10:58.696   862  1050 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-05 11:10:58.705  2376  5894 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:10:58.706  2376  5894 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 11:10:58.706  2376  5894 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:10:58.706  2376  5894 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-05 11:10:58.710   271  1041 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 11:10:58.710   271  1041 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 11:10:58.715   271  5896 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 11:10:58.715   271  5896 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:10:58.715   271  5896 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 11:10:58.717   862  1050 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,07-05 11:10:59.302   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:11:00.039  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:11:00.039  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:11:00.039  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:11:00.043  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:11:00.043  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:11:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:11:00.044  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:11:04.308   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:11:07.390   862  3157 I LocationManagerService: remove 278da65a
,07-05 11:11:07.393   862  3157 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
07-05 11:11:07.394   862  3157 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-05 11:11:07.394   862  3157 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-05 11:11:07.395   862  3157 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
07-05 11:11:07.395   862  3157 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,07-05 11:11:09.313   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:11:14.318   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:11:17.948   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:11:17.949   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:11:17.949   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 351967608411; DSPS: 11631081; Offset : -2992288016
,07-05 11:11:19.324   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:11:24.329   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:11:29.335   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:11:30.849  2376  2376 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 11:11:30.861  2376  2376 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 11:11:30.864  2376  2376 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 11:11:30.910   862  2111 I NotificationManager: android: cancelAsUser(2) by android
,07-05 11:11:30.927  4847  4881 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:11:30.928  4847  4881 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 11:11:30.931  4847  4881 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:11:30.931  4847  4881 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:11:30.932   271  1041 E BandwidthController: [LG DATA] No such appUid: 10036
07-05 11:11:30.932   271  1041 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
07-05 11:11:30.933   271  5901 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 11:11:30.933   271  5901 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:11:30.934   271  5901 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 11:11:30.935   862  1050 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-05 11:11:33.734  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,07-05 11:11:33.741   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 11:11:33.741  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:11:33.741  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:11:33.742  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:11:33.742  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:11:33.777  2056  3336 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 11:11:33.780  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 11:11:33.781  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 11:11:33.782  1873  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:11:33.782  1873  2037 D LEDHandler: Battery Level Remaining: 100%
07-05 11:11:33.782  1873  2037 D LEDHandler: Battery Temp: 311, mChargingStatus=5, mChargingStop=false
07-05 11:11:33.783  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 311
07-05 11:11:33.783  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:11:33.783  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 311
07-05 11:11:33.788   862  1313 D WifiController: battery changed pluggedType: 2
,07-05 11:11:33.791  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:11:33.792  5518  5518 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 11:11:34.341   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:11:37.950   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:11:37.950   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:11:37.950   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 371968738299; DSPS: 12286478; Offset : -2992286915
,07-05 11:11:39.346   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:11:44.352   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:11:49.357   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:11:54.363   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:11:57.951   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:11:57.951   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:11:57.951   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 391969952926; DSPS: 12941878; Offset : -2992292861
,07-05 11:11:59.368   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:12:00.038  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:12:00.038  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:12:00.038  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:12:00.042  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:12:00.042  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:12:00.043  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:12:00.043  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:12:04.374   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:12:09.379   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:12:14.385   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:12:17.953   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:12:17.953   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:12:17.953   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 411972016044; DSPS: 13597306; Offset : -2992305172
,07-05 11:12:19.390   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:12:24.395   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:12:29.400   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:12:33.885   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:12:33.888  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:12:33.888  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:12:33.888  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:12:33.888  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:12:33.889  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:12:33.927  2056  3336 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 11:12:33.931  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 310
07-05 11:12:33.931  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:12:33.931  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 310
07-05 11:12:33.932  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 11:12:33.932  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 11:12:33.933  1873  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:12:33.933  1873  2037 D LEDHandler: Battery Level Remaining: 100%
07-05 11:12:33.934  1873  2037 D LEDHandler: Battery Temp: 310, mChargingStatus=5, mChargingStop=false
07-05 11:12:33.938   862  1313 D WifiController: battery changed pluggedType: 2
07-05 11:12:33.941  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,07-05 11:12:33.943  5518  5518 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 11:12:34.406   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:12:37.954   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:12:37.954   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:12:37.954   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 431973137652; DSPS: 14252703; Offset : -2992312610
,07-05 11:12:39.418   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:12:44.424   290   353 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 11:12:49.429   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:12:54.435   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:12:57.955   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:12:57.955   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:12:57.955   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 451974264205; DSPS: 14908099; Offset : -2992284664
,07-05 11:12:59.440   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:13:00.038  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:13:00.038  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:13:00.039  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:13:00.042  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:13:00.043  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:13:00.043  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:13:00.044  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:13:04.445   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:13:09.451   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:13:14.456   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:13:17.957   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:13:17.957   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:13:17.957   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 471976249824; DSPS: 15563524; Offset : -2992282896
,07-05 11:13:19.461   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:13:24.467   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:13:29.472   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:13:34.059   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:13:34.062  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:13:34.062  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:13:34.062  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:13:34.062  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:13:34.065  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:13:34.106  2056  3336 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 11:13:34.110  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 307
07-05 11:13:34.110  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:13:34.110  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 307
07-05 11:13:34.111  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 11:13:34.111  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 11:13:34.113  1873  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:13:34.113  1873  2037 D LEDHandler: Battery Level Remaining: 100%
07-05 11:13:34.113  1873  2037 D LEDHandler: Battery Temp: 307, mChargingStatus=5, mChargingStop=false
07-05 11:13:34.118   862  1313 D WifiController: battery changed pluggedType: 2
,07-05 11:13:34.122  5518  5518 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 11:13:34.123  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:13:34.477   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:13:37.958   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:13:37.958   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:13:37.958   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 491977467160; DSPS: 16218924; Offset : -2992286081
,07-05 11:13:39.483   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:13:44.488   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:13:48.173   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:13:48.177  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:13:48.177  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:13:48.177  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:13:48.177  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:13:48.177  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:13:49.493   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:13:54.499   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:13:57.960   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:13:57.960   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:13:57.960   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 511978664651; DSPS: 16874324; Offset : -2992310907
,07-05 11:13:59.504   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:14:00.040  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:14:00.040  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-05 11:14:00.042  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
07-05 11:14:00.045  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:14:00.045  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:14:00.045  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:14:00.046  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:14:04.509   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:14:09.515   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:14:14.521   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:14:17.961   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:14:17.961   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:14:17.961   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 531979788811; DSPS: 17529720; Offset : -2992284000
,07-05 11:14:19.526   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:14:24.531   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:14:29.537   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:14:34.206   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:14:34.209  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:14:34.216  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:14:34.217  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:14:34.217  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:14:34.217  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:14:34.252  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 11:14:34.252  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,07-05 11:14:34.255  1873  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:14:34.255  1873  2037 D LEDHandler: Battery Level Remaining: 100%
07-05 11:14:34.255  1873  2037 D LEDHandler: Battery Temp: 306, mChargingStatus=5, mChargingStop=false
07-05 11:14:34.256  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 306
07-05 11:14:34.256  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:14:34.256  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 306
07-05 11:14:34.260  2056  3336 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 11:14:34.264   862  1313 D WifiController: battery changed pluggedType: 2
,07-05 11:14:34.268  5518  5518 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 11:14:34.269  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:14:34.542   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:14:37.962   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:14:37.962   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:14:37.962   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 551981199012; DSPS: 18185127; Offset : -2992308126
,07-05 11:14:39.548   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:14:44.553   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:14:49.559   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:14:54.564   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:14:57.963   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:14:57.963   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:14:57.963   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 571982334318; DSPS: 18840524; Offset : -2992301866
,07-05 11:14:59.570   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:15:00.039  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:15:00.039  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:15:00.039  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:15:00.043  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:15:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:15:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:15:00.045  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:15:04.575   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:15:09.581   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:15:14.586   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:15:17.966   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:15:17.966   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:15:17.966   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 591984702799; DSPS: 19495961; Offset : -2992283525
,07-05 11:15:19.591   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:15:24.597   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:15:29.602   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:15:34.369  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:15:34.369  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:15:34.369  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:15:34.369  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 11:15:34.371  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:15:34.372   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 11:15:34.412  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 305
07-05 11:15:34.412  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:15:34.412  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 305
,07-05 11:15:34.415  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 11:15:34.415  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 11:15:34.418  2056  3336 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 11:15:34.420  1873  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:15:34.420  1873  2037 D LEDHandler: Battery Level Remaining: 100%
07-05 11:15:34.420  1873  2037 D LEDHandler: Battery Temp: 305, mChargingStatus=5, mChargingStop=false
07-05 11:15:34.421  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:15:34.426   862  1313 D WifiController: battery changed pluggedType: 2
,07-05 11:15:34.428  5518  5518 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 11:15:34.607   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:15:37.966   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:15:37.966   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:15:37.966   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 611985438103; DSPS: 20151346; Offset : -2992310821
,07-05 11:15:39.612   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:15:44.617   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:15:47.296   862  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=376688488, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=862
,07-05 11:15:47.311   862  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{12a9f4f0 type 2 when 621307 com.google.android.gms} when 621307
,07-05 11:15:47.330   862   862 D PowerManagerServiceEx: releaseWakeLockInternal: lock=376688488 [*alarm*], flags=0x0
,07-05 11:15:47.334  2376  5931 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:15:47.335  2376  5931 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 11:15:47.335  2376  5931 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:15:47.335  2376  5931 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:15:47.336   271  1041 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 11:15:47.336   271  1041 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 11:15:47.338   271  5933 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 11:15:47.338   271  5933 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:15:47.340   271  5933 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 11:15:47.343   862  1050 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,07-05 11:15:49.623   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:15:54.628   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:15:57.968   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:15:57.968   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:15:57.968   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 631986661065; DSPS: 20806746; Offset : -2992308537
,07-05 11:15:59.633   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:16:00.039  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:16:00.039  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:16:00.039  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:16:00.043  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:16:00.043  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:16:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:16:00.045  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:16:04.639   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:16:09.644   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:16:14.649   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:16:17.968   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:16:17.968   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:16:17.968   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 651987403192; DSPS: 21462130; Offset : -2992299013
,07-05 11:16:19.655   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:16:24.660   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:16:29.666   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:16:30.972  2376  2376 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 11:16:30.983  2376  2376 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 11:16:30.984  2376  2376 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 11:16:31.027   862  1963 I NotificationManager: android: cancelAsUser(2) by android
,07-05 11:16:31.034  4847  4881 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:16:31.034  4847  4881 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 11:16:31.034  4847  4881 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:16:31.034  4847  4881 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:16:31.035   271  1041 E BandwidthController: [LG DATA] No such appUid: 10036
07-05 11:16:31.035   271  1041 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
07-05 11:16:31.037   271  5960 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 11:16:31.037   271  5960 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:16:31.037   271  5960 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 11:16:31.038   862  1050 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-05 11:16:34.528  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:16:34.528  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:16:34.528  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:16:34.528  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 11:16:34.530   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 11:16:34.532  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:16:34.572  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 304
07-05 11:16:34.572  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:16:34.572  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 304
,07-05 11:16:34.578  2056  3336 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 11:16:34.578  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 11:16:34.579  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 11:16:34.580  1873  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:16:34.580  1873  2037 D LEDHandler: Battery Level Remaining: 100%
07-05 11:16:34.580  1873  2037 D LEDHandler: Battery Temp: 304, mChargingStatus=5, mChargingStop=false
07-05 11:16:34.582  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:16:34.587   862  1313 D WifiController: battery changed pluggedType: 2
,07-05 11:16:34.592  5518  5518 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 11:16:34.672   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:16:37.969   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:16:37.969   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:16:37.970   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 671988524123; DSPS: 22117527; Offset : -2992307077
,07-05 11:16:39.677   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:16:44.682   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:16:49.688   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:16:54.693   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:16:57.971   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:16:57.971   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:16:57.972   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 691990521199; DSPS: 22772952; Offset : -2992293696
,07-05 11:16:59.699   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:17:00.040  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:17:00.040  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:17:00.040  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:17:00.044  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:17:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:17:00.045  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:17:00.046  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:17:04.704   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:17:09.709   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:17:14.714   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:17:17.973   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:17:17.973   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:17:17.973   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 711992034628; DSPS: 23428362; Offset : -2992306068
,07-05 11:17:19.720   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:17:24.725   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:17:29.731   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:17:34.687   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:17:34.691  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:17:34.691  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:17:34.692  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:17:34.692  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:17:34.692  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:17:34.730  2056  3336 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 11:17:34.734  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 11:17:34.734  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 11:17:34.735  1873  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:17:34.735  1873  2037 D LEDHandler: Battery Level Remaining: 100%
07-05 11:17:34.735  1873  2037 D LEDHandler: Battery Temp: 302, mChargingStatus=5, mChargingStop=false
07-05 11:17:34.736   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
07-05 11:17:34.736  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 302
07-05 11:17:34.736  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:17:34.736  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 302
07-05 11:17:34.742   862  1313 D WifiController: battery changed pluggedType: 2
,07-05 11:17:34.746  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:17:34.747  5518  5518 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 11:17:37.975   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:17:37.975   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:17:37.975   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 731993631027; DSPS: 24083774; Offset : -2992296609
,07-05 11:17:39.741   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:17:44.746   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:17:49.751   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:17:54.757   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:17:57.975   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:17:57.975   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:17:57.975   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 751994465499; DSPS: 24739161; Offset : -2992286397
,07-05 11:17:59.763   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:18:00.040  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:18:00.040  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:18:00.040  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:18:00.044  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:18:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:18:00.045  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:18:00.045  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:18:04.768   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:18:09.774   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:18:14.779   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:18:17.977   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:18:17.977   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:18:17.977   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 771996458564; DSPS: 25394587; Offset : -2992307284
,07-05 11:18:19.784   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:18:24.789   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:18:29.795   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:18:34.800   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:18:34.853   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:18:34.861  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:18:34.861  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:18:34.861  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:18:34.861  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:18:34.862  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:18:34.897  2056  3336 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 11:18:34.900  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 301
07-05 11:18:34.900  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:18:34.901  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 11:18:34.901  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 11:18:34.902  1873  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:18:34.903  1873  2037 D LEDHandler: Battery Level Remaining: 100%
07-05 11:18:34.903  1873  2037 D LEDHandler: Battery Temp: 301, mChargingStatus=5, mChargingStop=false
07-05 11:18:34.903  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 301
07-05 11:18:34.908   862  1313 D WifiController: battery changed pluggedType: 2
,07-05 11:18:34.912  5518  5518 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 11:18:34.913  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:18:37.978   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:18:37.978   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:18:37.978   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 791997188973; DSPS: 26049971; Offset : -2992309194
,07-05 11:18:39.806   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:18:44.811   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:18:49.817   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:18:54.822   290   353 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 11:18:57.980   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:18:57.980   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:18:57.980   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 811999101569; DSPS: 26705393; Offset : -2992288661
,07-05 11:18:59.827   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:19:00.039  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:19:00.039  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:19:00.039  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:19:00.043  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:19:00.043  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:19:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:19:00.045  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:19:04.833   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:19:09.838   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:19:14.843   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:19:17.981   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:19:17.981   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:19:17.981   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 831999834061; DSPS: 27360777; Offset : -2992288644
,07-05 11:19:19.848   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:19:24.854   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:19:29.859   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:19:34.864   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:19:35.006   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:19:35.008  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:19:35.008  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:19:35.015  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:19:35.015  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:19:35.015  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:19:35.051  2056  3336 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 11:19:35.055  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 11:19:35.055  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 11:19:35.057  1873  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:19:35.057  1873  2037 D LEDHandler: Battery Level Remaining: 100%
07-05 11:19:35.057  1873  2037 D LEDHandler: Battery Temp: 300, mChargingStatus=5, mChargingStop=false
07-05 11:19:35.057  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
07-05 11:19:35.057  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:19:35.057  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
07-05 11:19:35.063   862  1313 D WifiController: battery changed pluggedType: 2
07-05 11:19:35.065  5518  5518 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-05 11:19:35.067  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:19:37.983   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:19:37.983   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:19:37.983   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 852001921815; DSPS: 28016206; Offset : -2992306810
,07-05 11:19:39.870   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:19:44.875   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:19:49.880   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:19:54.886   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:19:57.985   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:19:57.985   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:19:57.985   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 872003693056; DSPS: 28671624; Offset : -2992305458
,07-05 11:19:59.891   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:20:00.039  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:20:00.039  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:20:00.039  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:20:00.044  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:20:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:20:00.045  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:20:00.045  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:20:04.896   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:20:09.901   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:20:14.907   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:20:17.987   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:20:17.987   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:20:17.987   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 892006162893; DSPS: 29327065; Offset : -2992307675
,07-05 11:20:19.912   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:20:24.918   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:20:29.923   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:20:34.929   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:20:35.167   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:20:35.170  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:20:35.176  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:20:35.176  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:20:35.176  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:20:35.176  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:20:37.989   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:20:37.989   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:20:37.989   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 912007762468; DSPS: 29982477; Offset : -2992294989
,07-05 11:20:39.934   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:20:44.940   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:20:49.945   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:20:54.950   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:20:57.990   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:20:57.990   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:20:57.990   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 932009173034; DSPS: 30637883; Offset : -2992288206
,07-05 11:20:59.956   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:21:00.039  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:21:00.039  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:21:00.039  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:21:00.044  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:21:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:21:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:21:00.045  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:21:04.962   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:21:09.967   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:21:10.831   862  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=376688488, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=862
,07-05 11:21:10.836   862  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{18e9a787 type 2 when 944842 com.android.bluetooth} when 944842
07-05 11:21:10.955   862   862 D PowerManagerServiceEx: releaseWakeLockInternal: lock=376688488 [*alarm*], flags=0x0
,07-05 11:21:10.980  2056  3392 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
07-05 11:21:10.980  2056  3392 W bt-smp  : Plain text(LSB ~ MSB) = a0 c1 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
,07-05 11:21:10.983  2056  3392 W bt-smp  : Encrypted text(LSB ~ MSB) = 50 8c 4c 54 05 12 00 24 38 a2 ab 8a 2f e7 80 46 
07-05 11:21:10.983  2056  3392 W bt-btm  : Stopping oneshot timer
07-05 11:21:14.972   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:21:17.991   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:21:17.991   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:21:17.991   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 952009910318; DSPS: 31293268; Offset : -2992313678
,07-05 11:21:19.977   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:21:24.983   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:21:29.988   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:21:31.072  2376  2376 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 11:21:31.084  2376  2376 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 11:21:31.087  2376  2376 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 11:21:31.128   862   880 I NotificationManager: android: cancelAsUser(2) by android
,07-05 11:21:31.135  4847  4881 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:21:31.135  4847  4881 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 11:21:31.135  4847  4881 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:21:31.135  4847  4881 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:21:31.137   271  1041 E BandwidthController: [LG DATA] No such appUid: 10036
07-05 11:21:31.137   271  1041 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
07-05 11:21:31.140   271  6000 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 11:21:31.140   271  6000 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-05 11:21:31.149   271  6000 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 11:21:31.150   862  1050 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-05 11:21:34.994   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:21:35.327   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:21:35.330  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:21:35.330  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:21:35.330  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:21:35.337  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:21:35.337  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:21:35.374  2056  3336 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 11:21:35.377  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 11:21:35.377  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 11:21:35.379  1873  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:21:35.379  1873  2037 D LEDHandler: Battery Level Remaining: 100%
07-05 11:21:35.379  1873  2037 D LEDHandler: Battery Temp: 299, mChargingStatus=5, mChargingStop=false
07-05 11:21:35.380  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 299
07-05 11:21:35.380  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:21:35.380  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 299
07-05 11:21:35.382  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:21:35.385   862  1313 D WifiController: battery changed pluggedType: 2
,07-05 11:21:35.389  5518  5518 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 11:21:37.992   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:21:37.992   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:21:37.993   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 972011511925; DSPS: 31948680; Offset : -2992298986
,07-05 11:21:39.999   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:21:45.004   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:21:50.010   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:21:55.015   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:21:57.994   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:21:57.994   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:21:57.994   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 992012844260; DSPS: 32604084; Offset : -2992309580
,07-05 11:22:00.020   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:22:00.039  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:22:00.039  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:22:00.040  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:22:00.043  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:22:00.043  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:22:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:22:00.045  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:22:05.026   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:22:10.032   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:22:15.038   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:22:17.995   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:22:17.995   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:22:17.995   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1012014240868; DSPS: 33259489; Offset : -2992286159
,07-05 11:22:20.043   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:22:25.048   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:22:30.053   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:22:35.059   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:22:35.487   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:22:35.489  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:22:35.490  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:22:35.490  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:22:35.496  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:22:35.496  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:22:35.531  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
,07-05 11:22:35.535  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 11:22:35.536  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:22:35.536  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
07-05 11:22:35.539  2056  3336 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 11:22:35.540  1873  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:22:35.540  1873  2037 D LEDHandler: Battery Level Remaining: 100%
07-05 11:22:35.540  1873  2037 D LEDHandler: Battery Temp: 298, mChargingStatus=5, mChargingStop=false
07-05 11:22:35.543  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,07-05 11:22:35.546  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 11:22:35.551   862  1313 D WifiController: battery changed pluggedType: 2
07-05 11:22:35.551  5518  5518 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 11:22:37.997   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:22:37.997   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:22:37.997   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1032015752161; DSPS: 33914899; Offset : -2992300901
,07-05 11:22:40.065   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:22:45.070   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:22:50.076   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:22:55.081   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:22:57.997   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:22:57.997   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:22:57.997   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1052016478978; DSPS: 34570283; Offset : -2992306219
,07-05 11:23:00.043  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:23:00.044  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:23:00.044  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:23:00.047  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:23:00.047  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:23:00.048  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:23:00.049  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:23:00.087   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:23:05.092   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:23:10.107   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:23:15.112   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:23:17.998   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:23:17.999   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:23:17.999   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1072017619074; DSPS: 35225680; Offset : -2992295326
,07-05 11:23:20.118   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:23:25.123   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:23:30.129   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:23:35.134   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:23:35.647   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:23:35.649  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:23:35.649  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:23:35.650  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:23:35.650  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:23:35.656  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:23:37.999   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:23:37.999   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:23:37.999   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1092018345524; DSPS: 35881064; Offset : -2992301220
,07-05 11:23:40.140   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:23:45.145   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:23:50.150   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:23:55.156   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:23:58.000   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:23:58.000   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:23:58.000   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1112019321037; DSPS: 36536456; Offset : -2992302581
,07-05 11:24:00.038  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:24:00.038  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:24:00.038  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:24:00.042  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:24:00.042  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:24:00.043  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:24:00.044  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:24:00.161   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:24:05.166   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:24:10.171   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:24:15.177   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:24:18.001   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:24:18.001   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:24:18.001   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1132020521187; DSPS: 37191855; Offset : -2992292409
,07-05 11:24:20.182   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:24:25.188   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:24:30.193   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:24:35.198   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:24:35.807   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:24:35.810  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:24:35.810  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:24:35.810  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:24:35.817  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:24:35.817  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:24:35.854  2056  3336 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 11:24:35.857  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
07-05 11:24:35.858  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:24:35.858  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
07-05 11:24:35.859  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 11:24:35.859  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 11:24:35.860  1873  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:24:35.860  1873  2037 D LEDHandler: Battery Level Remaining: 100%
07-05 11:24:35.860  1873  2037 D LEDHandler: Battery Temp: 297, mChargingStatus=5, mChargingStop=false
07-05 11:24:35.865   862  1313 D WifiController: battery changed pluggedType: 2
07-05 11:24:35.867  5518  5518 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-05 11:24:35.870  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:24:38.002   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:24:38.002   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:24:38.002   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1152021338992; DSPS: 37847242; Offset : -2992298735
,07-05 11:24:40.203   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:24:45.209   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:24:50.215   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:24:55.221   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:24:58.003   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:24:58.003   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:24:58.003   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1172022101797; DSPS: 38502627; Offset : -2992298740
,07-05 11:25:00.039  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:25:00.039  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:25:00.039  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:25:00.043  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:25:00.043  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:25:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:25:00.045  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:25:00.226   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:25:05.231   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:25:10.237   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:25:15.243   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:25:18.004   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:25:18.004   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:25:18.004   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1192023141268; DSPS: 39158021; Offset : -2992296918
,07-05 11:25:20.248   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:25:24.499   862  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=376688488, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=862
,07-05 11:25:24.507   862  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3212c5aa type 2 when 1198510 com.google.android.gms} when 1198510
07-05 11:25:24.520   862   862 D PowerManagerServiceEx: releaseWakeLockInternal: lock=376688488 [*alarm*], flags=0x0
,07-05 11:25:24.526  2376  6047 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:25:24.526  2376  6047 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 11:25:24.526  2376  6047 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:25:24.526  2376  6047 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:25:24.527   271  1041 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 11:25:24.527   271  1041 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 11:25:24.530   271  6048 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 11:25:24.530   271  6048 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:25:24.531   271  6048 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 11:25:24.533   862  1050 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,07-05 11:25:25.253   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:25:30.258   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:25:35.263   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:25:35.967   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:25:35.970  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:25:35.970  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:25:35.970  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:25:35.977  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:25:35.970  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:25:38.005   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:25:38.005   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:25:38.005   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1212023858917; DSPS: 39813405; Offset : -2992311508
,07-05 11:25:40.269   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:25:45.274   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:25:49.877   862  1000 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 11:25:50.280   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:25:55.285   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:25:58.006   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:25:58.006   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:25:58.006   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1232024737659; DSPS: 40468794; Offset : -2992317854
,07-05 11:26:00.039  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:26:00.039  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:26:00.039  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:26:00.043  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:26:00.043  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:26:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:26:00.045  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:26:00.290   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:26:05.296   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:26:08.172  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,07-05 11:26:08.176  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:26:08.176  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:26:08.176  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:26:08.176  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:26:08.195   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:26:08.233  2056  3336 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 11:26:08.236  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
07-05 11:26:08.236  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:26:08.236  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
07-05 11:26:08.237  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 11:26:08.238  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 11:26:08.239  1873  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:26:08.239  1873  2037 D LEDHandler: Battery Level Remaining: 100%
07-05 11:26:08.239  1873  2037 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
07-05 11:26:08.241  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:26:08.244   862  1313 D WifiController: battery changed pluggedType: 2
07-05 11:26:08.247  5518  5518 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-05 11:26:10.301   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:26:15.306   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:26:18.007   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:26:18.007   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:26:18.007   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1252025935048; DSPS: 41124193; Offset : -2992310521
,07-05 11:26:20.312   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:26:25.317   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:26:30.323   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:26:31.187  2376  2376 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 11:26:31.199  2376  2376 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 11:26:31.203  2376  2376 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 11:26:31.243   862   880 I NotificationManager: android: cancelAsUser(2) by android
,07-05 11:26:31.251  4847  4881 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:26:31.251  4847  4881 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 11:26:31.251  4847  4881 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:26:31.251  4847  4881 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:26:31.253   271  1041 E BandwidthController: [LG DATA] No such appUid: 10036
07-05 11:26:31.253   271  1041 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
07-05 11:26:31.257   271  6066 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 11:26:31.257   271  6066 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:26:31.258   271  6066 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
,07-05 11:26:31.261   862  1050 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-05 11:26:35.328   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:26:36.128  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:26:36.128  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:26:36.128  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:26:36.128  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 11:26:36.132  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:26:36.132   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 11:26:38.008   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:26:38.008   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:26:38.008   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1272026692644; DSPS: 41779578; Offset : -2992316073
,07-05 11:26:40.333   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:26:45.339   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:26:50.344   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:26:55.350   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:26:58.009   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:26:58.009   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:26:58.009   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1292027782688; DSPS: 42434973; Offset : -2992294117
,07-05 11:27:00.040  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:27:00.040  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:27:00.040  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:27:00.044  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:27:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:27:00.045  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:27:00.045  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:27:00.355   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:27:05.361   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:27:10.366   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:27:15.372   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:27:18.009   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:27:18.009   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:27:18.009   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1312028487889; DSPS: 43090356; Offset : -2992290665
,07-05 11:27:20.377   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:27:25.383   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:27:30.388   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:27:35.393   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:27:36.288   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:27:36.291  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:27:36.291  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:27:36.291  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:27:36.297  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:27:36.297  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:27:38.010   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:27:38.010   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:27:38.010   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1332029363661; DSPS: 43745745; Offset : -2992300058
,07-05 11:27:40.398   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:27:45.404   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:27:50.409   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:27:55.415   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:27:58.011   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:27:58.011   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:27:58.011   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1352030498655; DSPS: 44401142; Offset : -2992294190
,07-05 11:28:00.039  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:28:00.039  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:28:00.039  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:28:00.043  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:28:00.043  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:28:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:28:00.044  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:28:00.420   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:28:05.426   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:28:10.431   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:28:15.436   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:28:18.012   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:28:18.012   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:28:18.012   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1372031194845; DSPS: 45056525; Offset : -2992299773
,07-05 11:28:20.442   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:28:25.447   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:28:30.453   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:28:35.458   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:28:36.447  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:28:36.447  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:28:36.447  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:28:36.448  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 11:28:36.450   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 11:28:36.451  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:28:36.489  2056  3336 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 11:28:36.493  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
07-05 11:28:36.493  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 11:28:36.493  1370  1370 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
07-05 11:28:36.494  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 11:28:36.494  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 11:28:36.496  1873  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 11:28:36.496  1873  2037 D LEDHandler: Battery Level Remaining: 100%
07-05 11:28:36.496  1873  2037 D LEDHandler: Battery Temp: 295, mChargingStatus=5, mChargingStop=false
07-05 11:28:36.501   862  1313 D WifiController: battery changed pluggedType: 2
07-05 11:28:36.503  1370  1370 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,07-05 11:28:36.505  5518  5518 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 11:28:38.013   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:28:38.013   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:28:38.013   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1392031877807; DSPS: 45711908; Offset : -2992318923
,07-05 11:28:40.464   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:28:45.469   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:28:50.475   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:28:55.480   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:28:58.014   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:28:58.014   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:28:58.014   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1412033163320; DSPS: 46367309; Offset : -2992284580
,07-05 11:29:00.039  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:29:00.039  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:29:00.039  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:29:00.044  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:29:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:29:00.045  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:29:00.045  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:29:00.485   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:29:05.491   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:29:10.496   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:29:15.502   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:29:18.015   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:29:18.015   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:29:18.015   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1432033934510; DSPS: 47022695; Offset : -2992306743
,07-05 11:29:20.507   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:29:25.513   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:29:30.519   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:29:35.524   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:29:36.607   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:29:36.610  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:29:36.610  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:29:36.610  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:29:36.617  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:29:36.611  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:29:38.016   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:29:38.016   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:29:38.016   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1452034619450; DSPS: 47678077; Offset : -2992293320
,07-05 11:29:40.529   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:29:45.535   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:29:50.540   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:29:55.545   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:29:58.016   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:29:58.016   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:29:58.016   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1472035319026; DSPS: 48333460; Offset : -2992295725
,07-05 11:30:00.039  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:30:00.039  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:30:00.039  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:30:00.044  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:30:00.044  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:30:00.045  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:30:00.045  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:30:00.551   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:30:05.557   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:30:10.562   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:30:15.567   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:30:18.017   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:30:18.017   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:30:18.017   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1492036024226; DSPS: 48988843; Offset : -2992292326
,07-05 11:30:20.572   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:30:25.577   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:30:30.583   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:30:35.588   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:30:36.767   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 11:30:36.769  1370  1370 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 11:30:36.770  1370  1370 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 11:30:36.770  1370  1370 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 11:30:36.770  1370  1370 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 11:30:36.776  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 11:30:38.018   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:30:38.018   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:30:38.018   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1512036785468; DSPS: 49644228; Offset : -2992294179
,07-05 11:30:40.593   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:30:45.599   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:30:50.605   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:30:55.610   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:30:58.019   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:30:58.019   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:30:58.019   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1532037974576; DSPS: 50299627; Offset : -2992295126
,07-05 11:31:00.040  1370  1370 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 11:31:00.040  1370  1370 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 11:31:00.040  1370  1370 I [SystemUI]Clock: called onTimeUpdated()
,07-05 11:31:00.045  1370  1370 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 11:31:00.045  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:31:00.045  1370  1370 I [SystemUI]DateView: called onTimeUpdated()
07-05 11:31:00.046  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:31:00.616   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:31:05.621   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:31:10.627   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:31:15.632   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:31:18.020   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 11:31:18.020   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 11:31:18.020   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1552038672224; DSPS: 50955010; Offset : -2992299383
,07-05 11:31:20.637   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:31:25.642   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 11:31:29.604   862  1055 D LPWGController: LPWG WAKEUP isScreenOn = false, TimeAfterSleep = 1411362
,07-05 11:31:29.611   862  1055 I PowerManagerService: Waking up from sleep (uid 1000)...
07-05 11:31:29.615   862   862 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@36058149)
07-05 11:31:29.616  1370  1824 D KeyguardViewMediator: onScreenTurnedOn, seq = 2
07-05 11:31:29.616  1370  1824 D KeyguardViewMediator: notifyScreenOnLocked
07-05 11:31:29.617   862  1055 D LPWGController: [updateScreenState] screen on = true
07-05 11:31:29.617   862  1055 D LPWGController: disable proximity sensor
07-05 11:31:29.618  1370  1370 D KeyguardModel: mReceiver, received action: com.lge.android.intent.action.ACTION_KNOCK_ON, sendingUserId:-1
07-05 11:31:29.618  1370  1370 D KeyguardModel: LGIntent.ACTION_KNOCK_ON
,07-05 11:31:29.621  1855  1855 D LNfcService: action : android.intent.action.USER_PRESENT
07-05 11:31:29.623   862   862 V SmartCoverServiceDelegate: onScreenTurnedOn()
07-05 11:31:29.624  1329  3295 D SmartCoverViewMediator: onScreenTurnedOn, seq = 0
07-05 11:31:29.624  1329  3295 D SmartCoverViewMediator: notifyScreenOnLocked
07-05 11:31:29.625  1329  1329 D SmartCoverViewMediator: handleNotifyScreenOn
07-05 11:31:29.631  1370  1370 D KeyguardViewMediator: handleNotifyScreenOn
,07-05 11:31:29.634  2829  2829 D WeatherAncestor: 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 11:31:29
07-05 11:31:29.639   862  1055 I SensorManager: removeAllSensors() [Sensor: LGE Proximity Sensor] by com.android.server.power.ProximitySensorListener.disable():130
07-05 11:31:29.639   862  1055 I sensors_hal_Ctx: activate: handle is 48, disable
07-05 11:31:29.639   862  1055 V sensors_hal_Ctx: All sensors stop, stop the time_service.
07-05 11:31:29.639   862  1055 D sensors_hal_Time: send stop time_service command
07-05 11:31:29.639   862  1055 D sensors_hal_Util: waitForResponse: timeout=1000
07-05 11:31:29.640   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 1
07-05 11:31:29.640   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 0, txn Id 1
07-05 11:31:29.640   862  1055 V sensors_hal_Ctx: activate sensors is 0
07-05 11:31:29.640   862  1055 D sensors_hal_Thresh: enable: handle=48
07-05 11:31:29.640   862  1055 D sensors_hal_Thresh: enable: Disabling sensor handle=48
07-05 11:31:29.640   862  1055 I sensors_hal_SAM: sendCancel:sensor(android.sensor.proximity) Sending cancel to svc no:21
07-05 11:31:29.641   862  1055 I PowerManagerService: ALS enabled for SRE
07-05 11:31:29.641   862  1055 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=120000 (1443660 ms ago)
07-05 11:31:29.641   862  1055 D LPWGController: disable proximity sensor
07-05 11:31:29.642   862  1007 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 0, txn Id 69
07-05 11:31:29.642   862  1007 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_DISABLE/CANCEL_RESP_V01
07-05 11:31:29.644  1855  2429 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
07-05 11:31:29.644  1873  2037 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
,07-05 11:31:29.653   862  2111 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-05 11:31:29.654  1787  1787 D DSDPConnection: Display #0 changed.
,07-05 11:31:29.668  1873  2037 V LEDService: startInternal : pkg=KnockOn, recordId=0 : LGLedRecord{3368133a flags=2 patternId=2 color=0 priority=2 recordId=0 pkg=KnockOn infinite=true mExceptional=false mNativeNotification=false whichLedPlay=1 patternFilePath=null}
,07-05 11:31:29.668  1873  2037 D LEDService: stopPatternFlashing()
07-05 11:31:29.668  1873  2037 I LEDService: getCurrentHighestLGLedRecord : size = 2
07-05 11:31:29.668  1873  2037 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 11:31:29.670  1873  2037 I LEDService: updateLightsLocked : turn on led
07-05 11:31:29.671  5686  5686 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-05 11:31:29.674  5686  5686 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-05 11:31:29.677  1873  2037 I LEDService: getCurrentHighestLGLedRecord() start. size = 2
07-05 11:31:29.679  5686  5686 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-05 11:31:29.679  5686  5686 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,07-05 11:31:29.683  5686  5686 I Activity: Activity.onPostResume() called 
07-05 11:31:29.687  2829  2829 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-05 11:31:29.688  2829  2829 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 11:31:29
07-05 11:31:29.688  1873  6122 D qdlights: set_light_notifications: 2,ff00ffff,500,0,1
07-05 11:31:29.688  1873  6122 D qdlights: [Current] = 255, R = 0, G = 255, B = 255, rgb = 0x00ff0000
07-05 11:31:29.690  2829  2829 D WeatherService: 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
07-05 11:31:29.696   862  1915 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
,07-05 11:31:29.717  2829  2829 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
07-05 11:31:29.720  2829  2829 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
07-05 11:31:29.720  2829  2829 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
07-05 11:31:29.720  2829  2829 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
07-05 11:31:29.724  2376  2376 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.trustagent.UserPresentBroadcastReceiver }.
,07-05 11:31:29.729  1855  2676 E NxpNfcJni: getReconnectState = 0x0
07-05 11:31:29.729  5686  5686 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@192a4501 time:1563748
07-05 11:31:29.735  2829  2829 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-05 11:31:29.736  2829  2829 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
07-05 11:31:29.736  2829  2829 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
07-05 11:31:29.737  2829  2829 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
07-05 11:31:29.737  2829  2829 D WeatherTheme: 2 : Fixed theme : optimus
07-05 11:31:29.742   862   862 V ActivityManager: Display changed displayId=0
07-05 11:31:29.743   862   862 D PowerManagerServiceEx: acquireWakeLockInternal: lock=376688488, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=862
,07-05 11:31:29.746  1855  2429 D LCardEmulationManager: getHceAppCount hostAppNum : 0
07-05 11:31:29.746  1855  2429 D LCardEmulationManager: getDefaultRoute
07-05 11:31:29.746  1855  2429 D LNfcService: isRequireNfcCRouting() return true
07-05 11:31:29.746  1855  2429 D LNfcService: isHCERoutingtoHost() return : true
,07-05 11:31:29.747  1855  2429 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: 0
07-05 11:31:29.747  1855  2429 D NfcService: mEnableLPD: true
07-05 11:31:29.747  1855  2429 D NfcService: mEnableReader: false
07-05 11:31:29.747  1855  2429 D NfcService: mEnableHostRouting: true
07-05 11:31:29.747  1855  2429 D NfcService: newParams.techmask= mTechMask: default
07-05 11:31:29.747  1855  2429 D NfcService: mEnableLPD: true
07-05 11:31:29.747  1855  2429 D NfcService: mEnableReader: false
07-05 11:31:29.747  1855  2429 D NfcService: mEnableHostRouting: true
07-05 11:31:29.747  1855  2429 D NfcService: screenState= 3
07-05 11:31:29.747  1855  2429 E NxpNfcJni: nfcManager_enableDiscovery:UICC_LISTEN_MASK=0x0199;
07-05 11:31:29.747  2829  2829 D WeatherReflect: 2 : Map key string is -2
07-05 11:31:29.748   862   862 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
07-05 11:31:29.750  2829  2829 D lim     : 2 : time = 11:31
07-05 11:31:29.751  2829  2829 I WeatherReflect: Model Name : LG-D722
07-05 11:31:29.751  2829  2829 D WeatherTheme: 2 : Different view - status_min_formatted : 07 != 31
07-05 11:31:29.751  2829  2829 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
07-05 11:31:29.753  2829  2829 D WeatherReflect: 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
07-05 11:31:29.753  2829  2829 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-05 11:31:29.753  2829  2829 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-05 11:31:29.753  2829  2829 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-05 11:31:29.753  2829  2829 D Weather4x2_optimus: currentPackage=com.lge.sizechangable.weather.theme.optimus
07-05 11:31:29.753   277  1612 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 862
07-05 11:31:29.754   277  1612 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-05 11:31:29.754   277  1612 V voice   : voice_set_parameters: enter: screen_state=on
07-05 11:31:29.754   277  1612 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
07-05 11:31:29.754   277  1612 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-05 11:31:29.754   277  1612 V voice   : voice_set_parameters: exit with code(0)
07-05 11:31:29.754   277  1612 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
07-05 11:31:29.754   277  1612 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-05 11:31:29.754   277  1612 V msm8974_platform: platform_set_parameters: exit with code(0)
07-05 11:31:29.754   277  1612 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-05 11:31:29.754   277  1612 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
07-05 11:31:29.754   277  1612 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
07-05 11:31:29.754   277  1612 V audio_hw_primary: adev_set_parameters: exit with code(0)
,07-05 11:31:29.759  1370  1370 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:31:29.760  1370  1370 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
07-05 11:31:29.780  2829  2829 D Weather4x2_optimus: [[[[[[Theme package!!]]]]]] RemoteViews are created 2
07-05 11:31:29.780  2829  2829 D Weather4x2_optimus: widgetType = 1, orientation = 1
,07-05 11:31:29.781  2829  2829 D Weather4x2_optimus: forecast size is 0
07-05 11:31:29.781  2829  2829 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-05 11:31:29.781   862  1055 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
07-05 11:31:29.781  2829  2829 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-05 11:31:29.781  2829  2829 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-05 11:31:29.781  2829  2829 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-05 11:31:29.781  2829  2829 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-05 11:31:29.781  2829  2829 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-05 11:31:29.781  2829  2829 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-05 11:31:29.781  2829  2829 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-05 11:31:29.781  2829  2829 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-05 11:31:29.782  2829  2829 I Theme_WeatherAncestor_optimus: WEATHER_CP_ACCU : 
07-05 11:31:29.782  2829  2829 I Theme_WeatherAncestor_optimus: weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
07-05 11:31:29.782  2829  2829 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-05 11:31:29.782  2829  2829 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-05 11:31:29.782  2829  2829 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-05 11:31:29.782  2829  2829 D Theme_WeatherAncestor_optimus: setTouchIntent, appWidgetId: 2
07-05 11:31:29.783  2829  2829 D Theme_WeatherAncestor_optimus: url is : null
,07-05 11:31:29.785  2829  2829 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-05 11:31:29.785  2829  2829 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-05 11:31:29.785  2829  2829 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-05 11:31:29.786  2829  2829 D WeatherAncestor: 2 : update view, appWidgetId: 2
07-05 11:31:29.788  2829  2829 D WeatherService: 2 : TimeTick Receiver Register
07-05 11:31:29.789   862  1055 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
07-05 11:31:29.790   862   880 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
07-05 11:31:29.790  2829  2829 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
07-05 11:31:29.791   862  1055 I SensorManager: registerListenerImpl() [Sensor: Motion Accel, Rate: 66667, SensorEventListener: com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@26a29883] by com.android.internal.policy.impl.WindowOrientationListener.enable():143
07-05 11:31:29.791  2829  2829 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
07-05 11:31:29.791  2829  2829 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
07-05 11:31:29.791   862  1055 I sensors_hal_Ctx: batch: handle:46 flags:0x0 period_ns 66667000, timeout 0
07-05 11:31:29.791   862  1055 D sensors_hal_SAM: batch:sensor(com.qti.sensor.motion_accel) handle:46 flags:0x0 period_ns:66667000 timeout:0
07-05 11:31:29.792   862  1055 D sensors_hal_SAM: batch:sensor(com.qti.sensor.motion_accel) handle:46 freq:1 report_rate:1 max:1.000000 min:0.000000
07-05 11:31:29.792   862  1055 I sensors_hal_Ctx: activate: handle is 46, enable
07-05 11:31:29.792   862  1055 D sensors_hal_Util: waitForResponse: timeout=1000
07-05 11:31:29.792   862  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 1
07-05 11:31:29.792   862  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 2, txn Id 1
07-05 11:31:29.792   862  1006 D sensors_hal_Time: tsOffsetIs: Apps: 1563811698626; DSPS: 51340788; Offset : -2992284173
07-05 11:31:29.793   862  1055 V sensors_hal_Ctx: activate sensors is 400000000000
07-05 11:31:29.793   862  1055 D sensors_hal_LP2: enable: handle=46
07-05 11:31:29.793   862  1055 I sensors_hal_SAM: sendEnableReq:sensor(com.qti.sensor.motion_accel) Sending enable to svc no:49
07-05 11:31:29.794   862  1055 D sensors_hal_Util: waitForResponse: timeout=1000
07-05 11:31:29.795   422   885 I Sensors : sns_sam_dep.c(465):Algo b76018ca Generating dependent req 83777081
07-05 11:31:29.796   422   885 I Sensors : sns_sam_dep.c(465):Algo b76018ca Generating dependent req f54afd3e
07-05 11:31:29.797   862  1034 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 2, txn Id 0
07-05 11:31:29.797   862  1034 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_ENABLE_RESP_V01
,07-05 11:31:29.797   862  1055 D sensors_hal_LP2: enable: Received response: 0
07-05 11:31:29.800   862  1055 D LPWGController: sendResult : 1
07-05 11:31:29.801   862  1347 I QCOM PowerHAL: Got set_interactive hint
07-05 11:31:29.802   244   244 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6082000
07-05 11:31:29.802   244   244 D qdhwcomposer: hwc_blank: Unblanking display: 0
07-05 11:31:29.804   862  1053 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
07-05 11:31:29.805   862   862 V ActivityManager: Display changed displayId=0
07-05 11:31:29.808  1787  1787 D DSDPConnection: Display #0 changed.
,07-05 11:31:29.875  1370  1370 I [SystemUI]StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 20 0 -73 -65 -120 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0 0 0 0 0 level=5
,07-05 11:31:29.880  1370  1370 D TelephonyIcons: updateDataType sub=0, type=0, inetCondition=0 showAtLeast3G=false show4GforLte=true hspaDistinguishable=true
07-05 11:31:29.880  1370  1370 D TelephonyIcons: data type item name: array/telephony_data_type_sim1
07-05 11:31:29.889  1370  1370 D TelephonyIcons: data type item id: 2131230724
07-05 11:31:29.892  1370  1370 D TelephonyIcons: updateDataType mSelectedDataTypeIcon[0]=0, mSelectedDataActivityIndex=0
07-05 11:31:29.892  1370  1370 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,07-05 11:31:29.896  1370  1370 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
07-05 11:31:29.901  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-05 11:31:29.903  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,07-05 11:31:29.912  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
07-05 11:31:29.913  1787  1787 D PhoneInterfaceManager: [PhoneIntfMgr] mSigLevel = 5
07-05 11:31:29.917  1787  1787 D PhoneInterfaceManager: [PhoneIntfMgr] mSigLevel = 5
,07-05 11:31:29.928  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-05 11:31:29.928  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 11:31:29.928  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
07-05 11:31:29.930  1370  1370 I [SystemUI]StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 20 0 -73 -65 -120 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0 0 0 0 0 level=5
07-05 11:31:29.930  1370  1370 D TelephonyIcons: updateDataType sub=0, type=0, inetCondition=0 showAtLeast3G=false show4GforLte=true hspaDistinguishable=true
07-05 11:31:29.930  1370  1370 D TelephonyIcons: data type item name: array/telephony_data_type_sim1
07-05 11:31:29.930  1370  1370 D TelephonyIcons: data type item id: 2131230724
07-05 11:31:29.931  1370  1370 D TelephonyIcons: updateDataType mSelectedDataTypeIcon[0]=0, mSelectedDataActivityIndex=0
07-05 11:31:29.931  1370  1370 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-05 11:31:29.932  1370  1370 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
07-05 11:31:29.934  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-05 11:31:29.934  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 11:31:29.934  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
07-05 11:31:29.938  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-05 11:31:29.938  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 11:31:29.938  1370  1370 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
07-05 11:31:30.004   244   684 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
07-05 11:31:30.004   244   244 D qdhwcomposer: hwc_blank: Done unblanking display: 0
07-05 11:31:30.004   862  1347 D SurfaceControl: Excessive delay in setPowerMode(): 203ms
,07-05 11:31:30.020   862  1055 I DisplayPowerController: Unblocked screen on after 233 ms
,07-05 11:31:30.029   862  1055 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
07-05 11:31:30.042   862  1347 D qdlights: set_light_backlight: 255
,07-05 11:31:30.075  1946  1946 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,07-05 11:31:30.167  1946  1946 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,07-05 11:31:30.195  1873  6122 D qdlights: set_light_notifications: 2,f700f7f7,10,0,1
07-05 11:31:30.195  1873  6122 D qdlights: [Current] = 247, R = 0, G = 247, B = 247, rgb = 0x00f70000
,07-05 11:31:30.208  1873  6122 D qdlights: set_light_notifications: 2,ef00efef,10,0,1
07-05 11:31:30.208  1873  6122 D qdlights: [Current] = 239, R = 0, G = 239, B = 239, rgb = 0x00ef0000
,07-05 11:31:30.222  1873  6122 D qdlights: set_light_notifications: 2,e700e7e7,10,0,1
07-05 11:31:30.222  1873  6122 D qdlights: [Current] = 231, R = 0, G = 231, B = 231, rgb = 0x00e70000
,07-05 11:31:30.235  1873  6122 D qdlights: set_light_notifications: 2,df00dfdf,10,0,1
07-05 11:31:30.235  1873  6122 D qdlights: [Current] = 223, R = 0, G = 223, B = 223, rgb = 0x00df0000
07-05 11:31:30.248  1873  6122 D qdlights: set_light_notifications: 2,d700d7d7,10,0,1
07-05 11:31:30.248  1873  6122 D qdlights: [Current] = 215, R = 0, G = 215, B = 215, rgb = 0x00d70000
,07-05 11:31:30.251   862  1034 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 49, msg Id 5, txn Id 0
07-05 11:31:30.251   862  1034 D sensors_hal_LP2: processInd: SNS_SAM_EVENT_GATED_SENSOR_REPORT_IND_V01
07-05 11:31:30.251   862  1034 D sensors_hal_LP2: processInd: Samples_len=1 Items=1 max_reports_per_index=1
07-05 11:31:30.251   862  1034 V sensors_hal_LP2: processInd: X: -0.058823 Y: 0.106125 Z: 9.740341 
07-05 11:31:30.251   862  1048 D sensors_hal_Ctx: poll:polldata:1, sensor:46, type:499898101, x:-0.058823 y:0.106125 z:9.740341
07-05 11:31:30.251   862  1048 D sensors_hal_Ctx: poll: count: 256
07-05 11:31:30.251   862  1048 D sensors_hal_Util: waitForResponse: timeout=0
07-05 11:31:30.262  1873  6122 D qdlights: set_light_notifications: 2,cf00cfcf,10,0,1
07-05 11:31:30.262  1873  6122 D qdlights: [Current] = 207, R = 0, G = 207, B = 207, rgb = 0x00cf0000
,07-05 11:31:30.275  1873  6122 D qdlights: set_light_notifications: 2,c700c7c7,10,0,1
07-05 11:31:30.275  1873  6122 D qdlights: [Current] = 199, R = 0, G = 199, B = 199, rgb = 0x00c70000
,07-05 11:31:30.288  1873  6122 D qdlights: set_light_notifications: 2,bf00bfbf,10,0,1
07-05 11:31:30.288  1873  6122 D qdlights: [Current] = 191, R = 0, G = 191, B = 191, rgb = 0x00bf0000
,07-05 11:31:30.301  1873  6122 D qdlights: set_light_notifications: 2,b700b7b7,10,0,1
07-05 11:31:30.301  1873  6122 D qdlights: [Current] = 183, R = 0, G = 183, B = 183, rgb = 0x00b70000
,07-05 11:31:30.314  1873  6122 D qdlights: set_light_notifications: 2,af00afaf,10,0,1
07-05 11:31:30.314  1873  6122 D qdlights: [Current] = 175, R = 0, G = 175, B = 175, rgb = 0x00af0000
,07-05 11:31:30.328  1873  6122 D qdlights: set_light_notifications: 2,a200a2a2,10,0,1
07-05 11:31:30.328  1873  6122 D qdlights: [Current] = 162, R = 0, G = 162, B = 162, rgb = 0x00a20000
07-05 11:31:30.341  1873  6122 D qdlights: set_light_notifications: 2,97009797,10,0,1
07-05 11:31:30.341  1873  6122 D qdlights: [Current] = 151, R = 0, G = 151, B = 151, rgb = 0x00970000
,07-05 11:31:30.353  1873  6122 D qdlights: set_light_notifications: 2,8c008c8c,10,0,1
07-05 11:31:30.353  1873  6122 D qdlights: [Current] = 140, R = 0, G = 140, B = 140, rgb = 0x008c0000
,07-05 11:31:30.366  1873  6122 D qdlights: set_light_notifications: 2,81008181,10,0,1
07-05 11:31:30.366  1873  6122 D qdlights: [Current] = 129, R = 0, G = 129, B = 129, rgb = 0x00810000
,07-05 11:31:30.379  1873  6122 D qdlights: set_light_notifications: 2,76007676,10,0,1
07-05 11:31:30.379  1873  6122 D qdlights: [Current] = 118, R = 0, G = 118, B = 118, rgb = 0x00760000
,07-05 11:31:30.392  1873  6122 D qdlights: set_light_notifications: 2,6b006b6b,10,0,1
07-05 11:31:30.392  1873  6122 D qdlights: [Current] = 107, R = 0, G = 107, B = 107, rgb = 0x006b0000
,07-05 11:31:30.405  1873  6122 D qdlights: set_light_notifications: 2,60006060,10,0,1
07-05 11:31:30.405  1873  6122 D qdlights: [Current] = 96, R = 0, G = 96, B = 96, rgb = 0x00600000
07-05 11:31:30.417  1873  6122 D qdlights: set_light_notifications: 2,55005555,10,0,1
07-05 11:31:30.417  1873  6122 D qdlights: [Current] = 85, R = 0, G = 85, B = 85, rgb = 0x00550000
,07-05 11:31:30.430  1873  6122 D qdlights: set_light_notifications: 2,4a004a4a,10,0,1
07-05 11:31:30.430  1873  6122 D qdlights: [Current] = 74, R = 0, G = 74, B = 74, rgb = 0x004a0000
07-05 11:31:30.442  1873  6122 D qdlights: set_light_notifications: 2,3f003f3f,10,0,1
07-05 11:31:30.442  1873  6122 D qdlights: [Current] = 63, R = 0, G = 63, B = 63, rgb = 0x003f0000
,07-05 11:31:30.455  1873  6122 D qdlights: set_light_notifications: 2,35003636,10,0,1
07-05 11:31:30.455  1873  6122 D qdlights: [Current] = 53, R = 0, G = 54, B = 54, rgb = 0x00350000
,07-05 11:31:30.468  1873  6122 D qdlights: set_light_notifications: 2,30003131,10,0,1
07-05 11:31:30.468  1873  6122 D qdlights: [Current] = 48, R = 0, G = 49, B = 49, rgb = 0x00300000
,07-05 11:31:30.481  1873  6122 D qdlights: set_light_notifications: 2,2b002c2c,10,0,1
07-05 11:31:30.481  1873  6122 D qdlights: [Current] = 43, R = 0, G = 44, B = 44, rgb = 0x002b0000
07-05 11:31:30.493  1873  6122 D qdlights: set_light_notifications: 2,26002727,10,0,1
,07-05 11:31:30.494  1873  6122 D qdlights: [Current] = 38, R = 0, G = 39, B = 39, rgb = 0x00260000
07-05 11:31:30.506  1873  6122 D qdlights: set_light_notifications: 2,21002222,10,0,1
07-05 11:31:30.507  1873  6122 D qdlights: [Current] = 33, R = 0, G = 34, B = 34, rgb = 0x00210000
,TIME-OUT KILL (timeout was 1400000ms),07-05 11:31:30.519  1873  6122 D qdlights: set_light_notifications: 2,1c001d1d,10,0,1
07-05 11:31:30.519  1873  6122 D qdlights: [Current] = 28, R = 0, G = 29, B = 29, rgb = 0x001c0000
07-05 11:31:30.532  1873  6122 D qdlights: set_light_notifications: 2,17001818,10,0,1
07-05 11:31:30.532  1873  6122 D qdlights: [Current] = 23, R = 0, G = 24, B = 24, rgb = 0x00170000
07-05 11:31:30.545  1873  6122 D qdlights: set_light_notifications: 2,12001313,10,0,1
07-05 11:31:30.545  1873  6122 D qdlights: [Current] = 18, R = 0, G = 19, B = 19, rgb = 0x00120000
07-05 11:31:30.557  1873  6122 D qdlights: set_light_notifications: 2,d000e0e,10,0,1
07-05 11:31:30.557  1873  6122 D qdlights: [Current] = 13, R = 0, G = 14, B = 14, rgb = 0x000d0000
07-05 11:31:30.570  1873  6122 D qdlights: set_light_notifications: 2,8000909,10,0,1
07-05 11:31:30.570  1873  6122 D qdlights: [Current] = 8, R = 0, G = 9, B = 9, rgb = 0x00080000
07-05 11:31:30.583  1873  2037 D LEDService: stopPatternFlashing()
07-05 11:31:30.583  1873  2037 D qdlights: set_light_notifications: 0,0,0,0,1
07-05 11:31:30.585  1873  2037 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-05 11:31:30.585  1873  2037 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 11:31:30.586  1873  2037 I LEDService: updateLightsLocked : turn on led
07-05 11:31:30.586  1873  2037 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
07-05 11:31:30.586  1873  2037 E LEDService: Can't handle this request of patternId:0
07-05 11:31:30.647   290   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
07-05 11:31:30.849  6149  6149 D AndroidRuntime: 
07-05 11:31:30.849  6149  6149 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 11:31:30.858  6149  6149 D AndroidRuntime: CheckJNI is OFF
07-05 11:31:31.021   422   885 I Sensors : sns_sam_dep.c(465):Algo b76018ca Generating dependent req 83777081
07-05 11:31:31.124  6149  6149 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-05 11:31:31.186   862  1001 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
07-05 11:31:31.186   862  1001 I ActivityManager: Killing 5686:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
07-05 11:31:31.217   862  1641 I WindowState: WIN DEATH: Window{3829d7e u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 11:31:31.227   862  1641 D InputDispatcher: Focus left window: Window{3829d7e u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 11:31:31.227   862  1641 D InputDispatcher: Window went away: Window{3829d7e u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 11:31:31.301   862  1001 W ActivityManager: Force removing ActivityRecord{bb320a0 u0 com.test.thalitest/.MainActivity t241}: app died, no saved state
07-05 11:31:31.314   862  1060 W PackageSettings: Skipping PackageSetting{3a86e986 com.example.hello/10317} due to missing metadata
07-05 11:31:31.358   862   862 V ActivityManager: Display changed displayId=0
07-05 11:31:31.361  1787  1787 D DSDPConnection: Display #0 changed.
07-05 11:31:31.372   862  2111 W ActivityManager: Spurious death for ProcessRecord{10660103 5686:com.test.thalitest/u0a30}, curProc for 5686: null
07-05 11:31:31.378   862  1060 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
07-05 11:31:31.445  1946  1946 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
07-05 11:31:31.451  2376  2376 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 11:31:31.461  1370  1370 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
07-05 11:31:31.464   862  1288 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-05 11:31:31.468  1909  1909 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
07-05 11:31:31.469  2023  2023 I art     : Explicit concurrent mark sweep GC freed 1660(102KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 12MB/20MB, paused 1.451ms total 79.981ms
07-05 11:31:31.472  1946  1946 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
07-05 11:31:31.476  3444  3444 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-05 11:31:31.480  3444  3444 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-05 11:31:31.483  3444  3444 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
07-05 11:31:31.483  3444  3444 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
07-05 11:31:31.483  3444  3444 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 11:31:31.483  3444  3444 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 11:31:31.484  3444  3444 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-05 11:31:31.484  3444  3444 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
07-05 11:31:31.484  3444  3444 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 11:31:31.484  3444  3444 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 11:31:31.484  3444  3444 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
07-05 11:31:31.484  3444  3444 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
07-05 11:31:31.524   862  1001 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6177 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
07-05 11:31:31.539  5364  5364 I art     : Explicit concurrent mark sweep GC freed 21558(1440KB) AllocSpace objects, 9(144KB) LOS objects, 24% free, 14MB/19MB, paused 933us total 127.104ms
07-05 11:31:31.554  2376  2774 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-05 11:31:31.564  1370  1370 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
07-05 11:31:31.594  1370  1511 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-05 11:31:31.594  1370  1511 D KeyguardModel: createShortcutInfo...
07-05 11:31:31.620  1370  1511 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-05 11:31:31.620  1370  1511 D KeyguardModel: createShortcutInfo...
07-05 11:31:31.628  1370  1511 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 11:31:31.628  1370  1511 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-05 11:31:31.630  1946  1946 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
07-05 11:31:31.654  1946  1946 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
07-05 11:31:31.654  1946  1946 I Activity: Activity.onPostResume() called 
07-05 11:31:31.656   862  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:31:31.656   862  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 11:31:31.656   862  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:31:31.657   862  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:31:31.657   271  1041 E BandwidthController: [LG DATA] No such appUid: 1000
07-05 11:31:31.657   271  1041 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-05 11:31:31.657   271  6196 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 11:31:31.658   271  6196 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:31:31.658   271  6196 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 11:31:31.659   862  1050 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-05 11:31:31.659  1370  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 11:31:31.659  1370  1511 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-05 11:31:31.661  1370  1511 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-05 11:31:31.661  1370  1511 D KeyguardModel: createShortcutInfo...
07-05 11:31:31.665  1370  1370 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
07-05 11:31:31.665  1370  1370 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
07-05 11:31:31.666   862   862 I art     : Explicit concurrent mark sweep GC freed 42928(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 16.339ms total 236.355ms
07-05 11:31:31.667   862  1060 I art     : WaitForGcToComplete blocked for 108.289ms for cause Explicit
07-05 11:31:31.681  1370  1511 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-05 11:31:31.682  1370  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 11:31:31.682  1370  1511 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-05 11:31:31.686  1946  6197 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
07-05 11:31:31.686  1370  1511 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-05 11:31:31.686  1370  1511 D KeyguardModel: createShortcutInfo...
07-05 11:31:31.694   862  1051 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
07-05 11:31:31.694  1370  1511 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 11:31:31.694  1370  1511 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-05 11:31:31.695  1370  1511 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-05 11:31:31.696   862  1051 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
07-05 11:31:31.697   862  1051 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
07-05 11:31:31.697   862  1051 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
07-05 11:31:31.697   862  1051 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 11:31:31.697   862  1051 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2bb03f7a,  pkg=WindowManager.LayoutParams
07-05 11:31:31.697   862  1051 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
07-05 11:31:31.698  1370  1370 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
07-05 11:31:31.698  1370  1370 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
07-05 11:31:31.698  1370  1370 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
07-05 11:31:31.698  1370  1370 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
07-05 11:31:31.699  1370  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 11:31:31.699  1370  1511 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-05 11:31:31.706   862  1641 D InputDispatcher: Focus entered window: Window{ce2ee41 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
07-05 11:31:31.718  1370  1511 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-05 11:31:31.718  1370  1511 D KeyguardModel: createShortcutInfo...
07-05 11:31:31.726  1370  1370 D KeyguardModel: handleShortcutListChanged...
07-05 11:31:31.728  1946  1946 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-05 11:31:31.730  1946  1946 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-05 11:31:31.730  1946  1946 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
07-05 11:31:31.737  1370  1511 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-05 11:31:31.737  1370  1511 D KeyguardModel: createShortcutInfo...
07-05 11:31:31.739  1370  1511 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-05 11:31:31.739  1370  1511 D KeyguardModel: createShortcutInfo...
07-05 11:31:31.740  1370  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 11:31:31.741  1370  1511 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-05 11:31:31.743  1370  1511 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-05 11:31:31.743  1370  1511 D KeyguardModel: createShortcutInfo...
07-05 11:31:31.744  1946  1946 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
07-05 11:31:31.745  1946  1946 I PhoneWindow: [setNavigationBarColor] color=0x 0
07-05 11:31:31.745  1370  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 11:31:31.746  1370  1511 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-05 11:31:31.747  1370  1511 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-05 11:31:31.747  1370  1511 D KeyguardModel: createShortcutInfo...
07-05 11:31:31.748  1370  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 11:31:31.748  1370  1511 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-05 11:31:31.750  1370  1511 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-05 11:31:31.750  1370  1511 D KeyguardModel: createShortcutInfo...
07-05 11:31:31.752   862   881 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
07-05 11:31:31.754   862   881 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5686 uid 10030
07-05 11:31:31.754   862   862 D administrator: Handling package changes for user 0
07-05 11:31:31.758  6177  6177 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 11:31:31.758  6177  6177 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-05 11:31:31.759  6177  6177 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-05 11:31:31.767  1370  1370 D KeyguardModel: handleShortcutListChanged...
07-05 11:31:31.845  2023  6200 I HotwordRecognitionRnr: Starting hotword detection.
07-05 11:31:31.851  2023  6201 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@f868c58
07-05 11:31:31.853  2023  6201 V AudioRecord: set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
07-05 11:31:31.853  2023  6201 V AudioRecord: set(): mSessionId 23
07-05 11:31:31.855   277   277 V AudioPolicyManager: getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 23, flags 0
07-05 11:31:31.855   277   277 V AudioPolicyManager: getDeviceForInputSource()input source 1999, device 80000004
07-05 11:31:31.855   277   277 V AudioPolicyManager: isPlaybackThread 0,isRecordThread 1
07-05 11:31:31.855   277   277 D audio_hw_primary: adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546de80)
07-05 11:31:31.855   277   277 V audio_hw_primary: adev_open_input_stream: exit
07-05 11:31:31.856   277   277 V AudioFlinger: openInput_l() openInputStream returned input 0xb546de80, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
07-05 11:31:31.857   277   277 V AudioFlinger: openInput_l() created record thread: ID 24 thread 0xb3c49000
07-05 11:31:31.858   277  6203 I AudioFlinger: AudioFlinger's thread 0xb3c49000 ready to run
07-05 11:31:31.858   277  6203 D audio_hw_primary: in_standby: enter: stream (0xb546de80) usecase(7: audio-record)
07-05 11:31:31.858   277  6203 V audio_hw_primary: in_standby: exit:  status(0)
07-05 11:31:31.860   277  6203 D audio_hw_primary: in_standby: enter: stream (0xb546de80) usecase(7: audio-record)
07-05 11:31:31.860   277  6203 V audio_hw_primary: in_standby: exit:  status(0)
07-05 11:31:31.860   277  6203 V AudioFlinger: RecordThread: loop stopping
07-05 11:31:31.861   277   277 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
07-05 11:31:31.861  1787  2307 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
07-05 11:31:31.861   862  5492 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
07-05 11:31:31.861  2023  2045 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
07-05 11:31:31.861   277   277 V AudioPolicyService: AudioCommandThread() adding update audio port list
07-05 11:31:31.861   277   277 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
07-05 11:31:31.861  2056  2072 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
07-05 11:31:31.861   277  1064 V AudioPolicyService: AudioCommandThread() waking up
07-05 11:31:31.861   277  1064 V AudioPolicyService: AudioCommandThread() processing update audio port list
07-05 11:31:31.861  3091  3107 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
07-05 11:31:31.862   277  1064 V AudioPolicyService: AudioCommandThread() going to sleep
07-05 11:31:31.862  1370  2414 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
07-05 11:31:31.862  2075  2096 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
07-05 11:31:31.862  1946  1946 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@39b60f45 time:1565882
07-05 11:31:31.873   277  1612 V AudioFlinger: openRecord() lSessionId: 23 input 24
07-05 11:31:31.874   277  1612 V AudioFlinger: getOrphanEffectChain_l session 23 index -2
07-05 11:31:31.876   277   277 V AudioFlinger: acquiring 23 from 2023, for -1
07-05 11:31:31.876   277   277 V AudioFlinger:  added new entry for 23
07-05 11:31:31.877  2023  6201 V AudioRecord: start, sync event 0 trigger session 0
07-05 11:31:31.877  2023  6201 V AudioRecord: mAudioRecord->start()
07-05 11:31:31.883   277  1612 V AudioFlinger: RecordHandle::start()
07-05 11:31:31.883   277  1612 V AudioFlinger: RecordThread::start event 0, triggerSession 0
07-05 11:31:31.883   277  1612 V AudioPolicyManager: startInput() module primary->input primary(24)
07-05 11:31:31.883   277  1612 V AudioPolicyManager: getDeviceForInputSource()input source 1999, device 80000004
07-05 11:31:31.883   277  1612 V AudioPolicyManager: getNewInputDevice() selected device 80000004
07-05 11:31:31.883   277  1612 V AudioPolicyManager: DeviceVector::refreshTypes() mDeviceTypes 80000004
07-05 11:31:31.883   277  1612 V AudioPolicyManager: DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
07-05 11:31:31.884   277  1612 V AudioPolicyService: AudioCommandThread() adding create patch delay 0
07-05 11:31:31.884   277  1612 V AudioPolicyService: inserting command: 7 at index 0, num commands 0
07-05 11:31:31.884   277  1063 V AudioPolicyService: AudioCommandThread() waking up
07-05 11:31:31.884   277  1063 V AudioPolicyService: AudioCommandThread() processing create audio patch
07-05 11:31:31.884   277  1063 V AudioFlinger::PatchPanel: createAudioPatch() num_sources 1 num_sinks 1 handle 0
07-05 11:31:31.884   277  1063 V AudioFlinger::PatchPanel: createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
07-05 11:31:31.884   277  1063 V AudioFlinger: ThreadBase::setParameters() input_source=6;routing=-2147483644
07-05 11:31:31.884   277  1063 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
07-05 11:31:31.884   277  6203 V AudioFlinger: RecordThread: loop starting
07-05 11:31:31.884   277  6203 V AudioFlinger: processConfigEvents_l() remaining events 1
07-05 11:31:31.884   277  6203 D audio_hw_primary: in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
07-05 11:31:31.885   277  6203 V audio_hw_primary: in_set_parameters: exit: status(0)
07-05 11:31:31.885   277  6203 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3c49000
07-05 11:31:31.885   277  1063 V AudioFlinger::PatchPanel: createAudioPatch() status 0
07-05 11:31:31.885   277  1063 V AudioFlinger::PatchPanel: createAudioPatch() added new patch handle 25 halHandle 0
07-05 11:31:31.885   277  1063 V AudioPolicyService: AudioCommandThread() going to sleep
07-05 11:31:31.885   277  1612 V AudioPolicyManager: setInputDevice() createAudioPatch returned 0 patchHandle 25
07-05 11:31:31.885   277  1612 V AudioPolicyManager: addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
07-05 11:31:31.885   277  1612 V AudioPolicyService: AudioCommandThread() adding update audio patch list
07-05 11:31:31.885   277  1612 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
07-05 11:31:31.885   277  1064 V AudioPolicyService: AudioCommandThread() waking up
07-05 11:31:31.885   277  1064 V AudioPolicyService: AudioCommandThread() processing update audio patch list
07-05 11:31:31.885   277  1064 V AudioPolicyService: AudioCommandThread() going to sleep
07-05 11:31:31.886   277  1612 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=1, io 24 ,delay 0
07-05 11:31:31.886   277  1612 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
07-05 11:31:31.886   277  1063 V AudioPolicyService: AudioCommandThread() waking up
07-05 11:31:31.886   277  1063 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=1, io 24
07-05 11:31:31.886   277  1063 V AudioFlinger: setParameters(): io 24, keyvalue hotword_active=1, calling pid 277
07-05 11:31:31.886   277  1063 V AudioFlinger: ThreadBase::setParameters() hotword_active=1
07-05 11:31:31.886   277  1063 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
07-05 11:31:31.896   277  6203 V AudioFlinger: processConfigEvents_l() remaining events 1
07-05 11:31:31.896   277  6203 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=1
07-05 11:31:31.896   277  6203 V audio_hw_primary: in_set_parameters: exit: status(0)
07-05 11:31:31.896   277  6203 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3c49000
07-05 11:31:31.896   277  1063 V AudioPolicyService: AudioCommandThread() going to sleep
07-05 11:31:31.897   277  1612 V AudioPolicyManager: AudioPolicyManager::startInput() input source = 1999
07-05 11:31:31.904  2023  6201 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@f868c58
07-05 11:31:31.906  1946  1946 I art     : Explicit concurrent mark sweep GC freed 7719(435KB) AllocSpace objects, 4(645KB) LOS objects, 40% free, 15MB/25MB, paused 1.380ms total 42.983ms
07-05 11:31:31.907   277  6203 V msm8974_platform: platform_update_usecase_from_source: input source :6
07-05 11:31:31.907   277  6203 D audio_hw_primary: start_input_stream: enter: stream(0xb546de80)usecase(7: audio-record)
07-05 11:31:31.907   277  6203 V voice   : voice_check_and_set_incall_rec_usecase: voice call not active
07-05 11:31:31.907   277  6203 V audio_hw_primary: start_input_stream: usecase(7)
07-05 11:31:31.908   277  6203 E audio_hw_primary: select_devices: enter and usecase(7)
07-05 11:31:31.908   277  6203 V msm8974_platform: platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
07-05 11:31:31.908   277  6203 V msm8974_platform: platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
07-05 11:31:31.908   277  6203 V msm8974_platform_lge: LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
07-05 11:31:31.908   277  6203 V audio_hw_lge_primary: LGE_exeption_scenario: enter and out: 0, in: 144
07-05 11:31:31.908   277  6203 D audio_hw_primary: select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
07-05 11:31:31.909   277  6203 E audio_hw_primary: enable_snd_device: enter  144
07-05 11:31:31.909   277  6203 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
07-05 11:31:31.909   277  6203 V audio_hw_primary: enable_snd_device: snd_device(144: lg-vr-handset-mic)
07-05 11:31:31.909   277  6203 V msm8974_platform_lge: LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
07-05 11:31:31.909   277  6203 D ACDB-LOADER: ACDB -> send_audio_cal, acdb_id = 65, path =  1
07-05 11:31:31.909   277  6203 D ACDB-LOADER: ACDB -> send_adm_topology
07-05 11:31:31.909   277  6203 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
07-05 11:31:31.910   277  6203 D ACDB-LOADER: ACDB -> send_asm_topology
07-05 11:31:31.911   277  6203 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
07-05 11:31:31.911   277  6203 D ACDB-LOADER: ACDB -> send_audtable
07-05 11:31:31.911   277  6203 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
07-05 11:31:31.911   277  6203 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_CAL
07-05 11:31:31.911   277  6203 D ACDB-LOADER: ACDB -> send_audvoltable
07-05 11:31:31.911   277  6203 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
07-05 11:31:31.911   277  6203 D         : Failed to fetch the lookup information of the device 00000041 
07-05 11:31:31.911   277  6203 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
07-05 11:31:31.911   277  6203 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
07-05 11:31:31.911   277  6203 D ACDB-LOADER: ACDB -> AUDIO_SET_AFE_CAL
07-05 11:31:31.916   277  6203 V audio_hw_primary: enable_audio_route: enter: usecase(7)
07-05 11:31:31.916   277  6203 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
07-05 11:31:31.916   277  6203 V audio_hw_primary: enable_audio_route: apply mixer and update path: audio-record
07-05 11:31:31.917   277  6203 V audio_hw_primary: enable_audio_route: exit
07-05 11:31:31.917   277  6203 D audio_hw_primary: select_devices: done
07-05 11:31:31.917   277  6203 V audio_hw_primary: start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
07-05 11:31:31.924   277  6203 V audio_hw_primary: start_input_stream: exit
07-05 11:31:31.983   862   862 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
07-05 11:31:31.983   862   862 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-05 11:31:31.987   862   862 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-05 11:31:31.995   862  1348 D TaskPersister: removeObsoleteFile: deleting file=241_task.xml
07-05 11:31:32.004  2376  2376 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 11:31:32.011  2376  2376 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 11:31:32.034  2023  2023 I HotwordWorker: onReady
07-05 11:31:32.047   862  1915 I NotificationManager: android: cancelAsUser(2) by android
07-05 11:31:32.058  4847  4881 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:31:32.058  4847  4881 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 11:31:32.058  4847  4881 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 11:31:32.058  4847  4881 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:31:32.059   271  1041 E BandwidthController: [LG DATA] No such appUid: 10036
07-05 11:31:32.059   271  1041 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
07-05 11:31:32.061   271  6205 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 11:31:32.061   271  6205 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 11:31:32.061   271  6205 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 11:31:32.062   862  1050 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-05 11:31:32.086  6177  6177 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
07-05 11:31:32.109  6177  6177 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
07-05 11:31:32.130   862  1053 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2466530a u0 com.lge.launcher2/.Launcher t240} time:1566150
07-05 11:31:32.135   862  1060 I art     : Explicit concurrent mark sweep GC freed 14758(2020KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.970ms total 467.127ms
07-05 11:31:32.144  1855  1855 D LCardEmulationManager: getHceAppCount hostAppNum : 0
07-05 11:31:32.145  1855  1855 D LCardEmulationManager: getDefaultRoute
07-05 11:31:32.253   862  1000 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
07-05 11:31:32.256  6149  6149 D AndroidRuntime: Shutting down VM
07-05 11:31:32.263   862  1915 D SplitWindow: check instance of lgWin Window{6fc7604 u0 SearchPanel}
07-05 11:31:32.280   862  1934 D InputDispatcher: Window went away: Window{3aadb032 u0 SearchPanel}
07-05 11:31:32.311   862  1060 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6210 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
07-05 11:31:32.321  1909  1909 I QCNEJ   : |CORE| sendScreenState: state:true
07-05 11:31:32.322  1873  2037 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
07-05 11:31:32.322  1873  2037 D LEDService: stopPatternFlashing()
07-05 11:31:32.322  1873  2037 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 11:31:32.323  1370  1370 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
07-05 11:31:32.324  1873  2037 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-05 11:31:32.324  1873  2037 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 11:31:32.325  1873  2037 I LEDService: updateLightsLocked : turn off led
07-05 11:31:32.325  1873  2037 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 11:31:32.328  1873  2037 D LEDHandler: RESTART MSG
07-05 11:31:32.337  6177  6177 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
07-05 11:31:32.349  1370  1370 I LgeClockWidgetControlView: time changed, timezoneChanged : false
07-05 11:31:32.376   862  1963 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6227 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
07-05 11:31:32.376   862  1963 I ActivityManager: Killing 5347:com.lge.eula/1000 (adj 15): empty #11
07-05 11:31:32.415   862  2032 W libprocessgroup: failed to open /acct/uid_1000/pid_5347/cgroup.procs: No such file or directory
07-05 11:31:32.424  1873  1873 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
07-05 11:31:32.424  1873  1873 D Cliptray Service: lockStatus = 0
07-05 11:31:32.426  1855  1855 D LNfcService: action : android.intent.action.SCREEN_ON
07-05 11:31:32.427   862   862 D Ulp_jni : JNI:system_update. Event-0
07-05 11:31:32.431  1855  2661 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
07-05 11:31:32.431  1855  2661 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
07-05 11:31:32.431  1855  2661 D LNfcService: isRequireNfcCRouting() return true
07-05 11:31:32.431  1855  2661 D LNfcService: isHCERoutingtoHost() return : true
07-05 11:31:32.431  1855  2661 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
07-05 11:31:32.431  1855  2661 D NfcService: mEnableLPD: true
07-05 11:31:32.431  1855  2661 D NfcService: mEnableReader: false
07-05 11:31:32.431  1855  2661 D NfcService: mEnableHostRouting: true
07-05 11:31:32.431  1855  2661 D NfcService: newParams.techmask= mTechMask: default
07-05 11:31:32.431  1855  2661 D NfcService: mEnableLPD: true
07-05 11:31:32.431  1855  2661 D NfcService: mEnableReader: false
07-05 11:31:32.431  1855  2661 D NfcService: mEnableHostRouting: true
07-05 11:31:32.431  1855  2661 D NfcService: screenState= 3
07-05 11:31:32.431  1855  2661 D NfcService: Discovery configuration equal, not updating.
07-05 11:31:32.433  1787  1787 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
07-05 11:31:32.439  2829  2829 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:31:32
07-05 11:31:32.439  2829  2829 D WeatherService: 2 : ACTION screen on
07-05 11:31:32.440   862   881 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
07-05 11:31:32.440  2829  2829 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
07-05 11:31:32.441  2829  2829 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
07-05 11:31:32.441  2829  2829 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
07-05 11:31:32.441  2829  2829 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
07-05 11:31:32.443  2829  2829 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-05 11:31:32.443  2829  2829 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
07-05 11:31:32.443  2829  2829 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
07-05 11:31:32.444  2829  2829 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
07-05 11:31:32.444  2829  2829 D WeatherTheme: 2 : Fixed theme : optimus
07-05 11:31:32.447  2829  2829 D WeatherReflect: 2 : Map key string is -2
07-05 11:31:32.448  2829  2829 D lim     : 2 : time = 11:31
07-05 11:31:32.449  2829  2829 I WeatherReflect: Model Name : LG-D722
07-05 11:31:32.449  2829  2829 D WeatherTheme: 2 : exactly same view!
07-05 11:31:32.449  2829  2829 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
07-05 11:31:32.449  2829  2829 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-05 11:31:32.449  2829  2829 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:31:32
07-05 11:31:32.452  3959  3959 D AppCleanupService: android.intent.action.SCREEN_ON
07-05 11:31:32.464  6227  6227 I AppUp4:AppBoxCP: onCreate
07-05 11:31:32.464  6227  6227 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
07-05 11:31:32.475   862  1934 I ActivityManager: Killing 5420:com.google.android.apps.docs/u0a58 (adj 15): empty #11
07-05 11:31:32.478  6227  6227 I AppUp4:DB:  setFingerPrint start
07-05 11:31:32.479  6227  6227 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
07-05 11:31:32.491  6227  6227 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
07-05 11:31:32.491  6227  6227 I AppUp4:DB:  SDK version = 21
07-05 11:31:32.491  6227  6227 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-05 11:31:32.514   862  1000 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 11:31:32.521   862   862 D PowerManagerServiceEx: releaseWakeLockInternal: lock=376688488 [*alarm*], flags=0x0
07-05 11:31:32.523   862  1854 W libprocessgroup: failed to open /acct/uid_10058/pid_5420/cgroup.procs: No such file or directory
07-05 11:31:32.524  6227  6227 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-05 11:31:32.596  6227  6227 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
07-05 11:31:32.641   862  2032 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6249 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
07-05 11:31:32.642   862  2032 I ActivityManager: Killing 5485:com.google.android.apps.plus/u0a86 (adj 15): empty #11
07-05 11:31:32.662   862  1000 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
07-05 11:31:32.681   862  2008 W libprocessgroup: failed to open /acct/uid_10086/pid_5485/cgroup.procs: No such file or directory

```
