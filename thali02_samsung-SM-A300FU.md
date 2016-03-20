#### Test 62548124ece3ba0_thali02_samsung-SM-A300FU Logs


```
--------- beginning of system,
03-20 17:20:26.678  1018  1051 D PowerManagerService: [s] UserActivityState : 2 -> 4
--------- beginning of main
03-20 17:20:26.678  1018  1154 V WindowOrientationListener: WindowOrientationListener disabled
03-20 17:20:26.678  1018  1051 I PowerManagerService: Nap time (uid 1000)...
03-20 17:20:26.678  1018  1154 D SensorService: [SO] activate (ident=0xb9318918, enabled=0)
03-20 17:20:26.678  1018  1051 D PowerManagerService: handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
03-20 17:20:26.678  1018  1154 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-20 17:20:26.678  1018  1051 I PowerManagerService: !@[ps] Screen__Off - 0 :  dream(timeout) (2)
03-20 17:20:26.678  1018  1154 D SensorManager: unregisterListener ::   
03-20 17:20:26.678  1018  1051 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
03-20 17:20:26.678  1018  1051 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
03-20 17:20:26.678  1018  1051 D DisplayPowerController: animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-20 17:20:26.688  1178  2358 D KeyguardViewMediator: onScreenTurnedOff(3)
03-20 17:20:26.678  1018  1051 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
03-20 17:20:26.688  1178  2358 I KeyguardEffectViewController: *** KeyguardEffectView getInstanceIfExists ***
03-20 17:20:26.678  1018  1051 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
03-20 17:20:26.678  1018  1051 D PowerManagerService: SecHardwareInterface.setBatteryADC : false
03-20 17:20:26.688   257   257 I SurfaceFlinger: id=12 createSurf (540x960),-1 flag=20004, DolorFade
03-20 17:20:26.678  1018  1051 D PowerManagerService: handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
03-20 17:20:26.678  1018  1051 D PowerManagerService: handleSandman : startDream(true)
03-20 17:20:26.678  1018  1051 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
03-20 17:20:26.678  1018  1051 I PowerManagerService: Sleeping (uid 1000)...
03-20 17:20:26.678  1018  1051 D PowerManagerService: [s] UserActivityState : 4 -> 0
03-20 17:20:26.688  1178  2358 D KeyguardEffectViewController: changeWallpaperByScreenOff()
03-20 17:20:26.698  4354  4354 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
03-20 17:20:26.708  1178  2358 D KeyguardViewMediator: notifyScreenOffLocked
03-20 17:20:26.708  1018  1051 D PowerManagerService: Excessive delay in ColorFade : createSurface: 31ms
03-20 17:20:26.708  1018  1051 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-20 17:20:26.708  1018  1051 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-20 17:20:26.708  1018  1051 I Adreno-EGL: Build Date: 04/06/15 Mon
03-20 17:20:26.708  1018  1051 I Adreno-EGL: Local Branch: 
03-20 17:20:26.708  1018  1051 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-20 17:20:26.708  1018  1051 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-20 17:20:26.708  1018  1051 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-20 17:20:26.738  1178  2358 D KeyguardViewMediator: timeout : 5000
03-20 17:20:26.758  1178  2358 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1
03-20 17:20:26.758  1178  1178 D KeyguardViewMediator: handleNotifyScreenOff
03-20 17:20:26.768  1178  1178 D VolumePanel: onScreenTurnedOff()
03-20 17:20:26.768  4354  4354 V ActivityThread: updateVisibility : ActivityRecord{3eab91d6 token=android.os.BinderProxy@1d1c213a {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
03-20 17:20:26.768  1178  1178 D VolumePanel: mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
03-20 17:20:26.768  1178  1178 D VolumePanel: mCoverBroadcastReceiver: Screen OFF end
03-20 17:20:26.768  1178  1178 D SecKeyguardClockSingleView: onScreenTurnedOff
03-20 17:20:26.788  1018  1051 D PowerManagerService: Excessive delay in ColorFade : createEglContext: 76ms
03-20 17:20:26.798   257  1040 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (479 us)
03-20 17:20:26.808  1018  1093 E SmartFaceService: onReceive: android.intent.action.SCREEN_ON
03-20 17:20:26.818  1018  1093 W System.err: java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
03-20 17:20:26.818  1018  1093 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-20 17:20:26.818  1018  1093 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-20 17:20:26.818  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-20 17:20:26.818  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
03-20 17:20:26.818  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 17:20:26.818  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 17:20:26.818  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 17:20:26.818  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 17:20:26.818  1018  1093 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-20 17:20:26.818  1018  1093 E SmartFaceService: fail to set sysfs 1
03-20 17:20:26.818  1018  1093 W System.err: 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
03-20 17:20:26.818  1018  1093 W System.err: 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
03-20 17:20:26.818  1018  1093 W System.err: 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
03-20 17:20:26.818  1018  1093 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
03-20 17:20:26.818  1018  1093 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-20 17:20:26.818  1018  1093 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-20 17:20:26.818  1018  1093 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:26.818  1018  1093 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:26.818  1018  1093 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
03-20 17:20:26.818  1018  1093 W System.err: 	at libcore.io.Posix.open(Native Method)
03-20 17:20:26.818  1018  1093 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-20 17:20:26.818  1018  1093 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-20 17:20:26.818  1018  1093 W System.err: 	... 10 more
03-20 17:20:26.828  1018  1051 D PowerManagerService: Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 36ms
03-20 17:20:26.838  1178  1178 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
03-20 17:20:26.848  1018  1018 D InputMethodManagerService: [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
03-20 17:20:26.858  1178  1178 D PanelView: There is/are notification(s) 
03-20 17:20:26.858  1018  1018 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
03-20 17:20:26.868  1018  1105 E MotionRecognitionService:  handler : SCREEN_ON end
03-20 17:20:26.878  1018  1018 D NotificationService: ACTION_SCREEN_ON
03-20 17:20:26.878  1018  1018 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
03-20 17:20:26.878  1018  1018 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
03-20 17:20:26.878  1018  1078 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
03-20 17:20:26.878  1018  1051 D PowerManagerService: Excessive delay in ColorFade : initGLShaders: 40ms
03-20 17:20:26.878  1018  1078 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
03-20 17:20:26.878  1018  1051 D PowerManagerService: Excessive delay in ColorFade prepare: 203ms
03-20 17:20:26.878  1018  1051 D DisplayPowerController: ColorFade: onAnimationStart
03-20 17:20:26.878  1018  1051 D DisplayPowerController: getFinalBrightness : Summary is 255 -> 255
03-20 17:20:26.878  1018  1051 D DisplayPowerController: performScreenOffTransition : no brightness animation
03-20 17:20:26.888   283   684 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
03-20 17:20:26.888   283   684 V voice   : voice_set_parameters: enter: screen_state=on
03-20 17:20:26.888   283   684 V voice   : voice_set_parameters: exit with code(-2)
03-20 17:20:26.888   283   684 V msm8974_platform: platform_set_parameters: enter: screen_state=on
03-20 17:20:26.888   283   684 V msm8974_platform: platform_set_parameters: exit with code(-2)
03-20 17:20:26.888   283   684 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
03-20 17:20:26.888   283   684 V audio_hw_primary: adev_set_parameters: exit
03-20 17:20:26.888  1018  1126 E WifiNative-wlan0: do suspend false
03-20 17:20:26.888  1384  1384 I wpa_supplicant: reset timer : RESET_TIMER 1
03-20 17:20:26.888  1384  1384 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
03-20 17:20:26.888  1384  1384 I wpa_supplicant: P2P: Current p2p state = IDLE
03-20 17:20:26.888  1384  1384 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
03-20 17:20:26.898  1018  1049 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
03-20 17:20:26.898  1018  1049 D IpRemoteDisplayController: Bridge Server is not available
03-20 17:20:26.968  5692  5692 D AndroidRuntime: 
03-20 17:20:26.968  5692  5692 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-20 17:20:26.978  5692  5692 D AndroidRuntime: CheckJNI is OFF
03-20 17:20:26.978  5692  5692 D AndroidRuntime: readGMSProperty: start
03-20 17:20:26.978  1018  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:20:26.978  5692  5692 D AndroidRuntime: readGMSProperty: already setted!!
03-20 17:20:26.978  1018  1487 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4266, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:20:26.978  5692  5692 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-20 17:20:26.978  1018  1487 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:20:26.978  5692  5692 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-20 17:20:26.978  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:20:26.978  5692  5692 D AndroidRuntime: readGMSProperty: end
03-20 17:20:26.978  5692  5692 D AndroidRuntime: addProductProperty: start
03-20 17:20:26.978  1018  1018 I MotionRecognitionService: Plugged
03-20 17:20:26.978  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:20:26.988  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:20:26.988  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:20:26.988  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:20:26.988  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-20 17:20:26.998  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-20 17:20:26.998  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
03-20 17:20:26.998  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:20:26.998  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:20:26.998  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:20:26.998  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:20:26.998  1178  1178 D SViewCoverView: level :100 plugged : 2
03-20 17:20:27.088  1018  1051 D DisplayPowerState: !@ ColorFade entry
03-20 17:20:27.098  1018  1158 D lights  : lcd : 0 +
03-20 17:20:27.088  1018  1051 D DisplayPowerController: ColorFade: onAnimationEnd
03-20 17:20:27.098  1018  1051 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
03-20 17:20:27.098  1018  1051 D DisplayPowerController: performScreenOffTransition : no brightness animation
03-20 17:20:27.108  1018  1158 D lights  : lcd : 0 -
03-20 17:20:27.108  1018  1051 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
03-20 17:20:27.108  1018  5707 D MISC PowerHAL: sysfs_write +: /sys/class/input/event3/device/enabled: 0
03-20 17:20:27.108  1018  1051 D DisplayPowerController: performScreenOffTransition : no brightness animation
03-20 17:20:27.108  1018  5706 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 0
03-20 17:20:27.108  1018  1051 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
03-20 17:20:27.108  1018  5706 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 0
03-20 17:20:27.118  1018  1051 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
03-20 17:20:27.168  1018  5707 D MISC PowerHAL: sysfs_write -: /sys/class/input/event3/device/enabled: 0
03-20 17:20:27.168  1018  1056 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
03-20 17:20:27.168  1018  1056 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
03-20 17:20:27.168  1018  1056 D PowerManagerService-JNI: Excessive delay in MISC setInteractive(false) while turning screen off: 55ms
03-20 17:20:27.168  1018  1056 I QCOM PowerHAL: Got set_interactive hint
03-20 17:20:27.168  1018  1056 D PowerManagerService: Excessive delay in nativeSetInteractive(false): 59ms
03-20 17:20:27.168  1018  1056 D DisplayManagerService: !@display_state: ON -> OFF
03-20 17:20:27.168  1018  1049 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 540 x 960, 60.0 fps, supportedRefreshRates [60.0], density 240, 244.928 x 243.839 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
03-20 17:20:27.178  1018  1018 V ActivityManager: Display changed displayId=0
03-20 17:20:27.178   257   257 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6fbe690
03-20 17:20:27.178   257   257 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
03-20 17:20:27.178   257   257 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
03-20 17:20:27.178   257   257 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
03-20 17:20:27.198  1178  1178 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte level=4
03-20 17:20:27.208  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
03-20 17:20:27.208  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
03-20 17:20:27.208  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
03-20 17:20:27.208  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-20 17:20:27.208  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
03-20 17:20:27.208  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 17:20:27.208  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 17:20:27.208  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 17:20:27.208  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 17:20:27.218  5692  5692 E AffinityControl: AffinityControl: registerfunction enter
03-20 17:20:27.248  5692  5692 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-20 17:20:27.258  1018  1043 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
03-20 17:20:27.258  1018  1542 E PersonaManagerService: inState():  stateMachine is null !!
03-20 17:20:27.258  1018  1018 D PersonaManagerService: ACTION_SCREEN_ON onReceive
03-20 17:20:27.258  1018  1542 I PersonaManagerService: PersonaId don't exist
03-20 17:20:27.258  1018  1542 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-20 17:20:27.268  5692  5692 D AndroidRuntime: Shutting down VM
03-20 17:20:27.268  1018  1541 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-20 17:20:27.268  1018  1063 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
03-20 17:20:27.278  1445  1445 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
03-20 17:20:27.278  1445  5710 D NfcService: call the applyRouting
03-20 17:20:27.288  1445  5710 D NfcService: Discovery configuration equal, not updating.
03-20 17:20:27.288  1445  5710 D NfcService: index : 0
03-20 17:20:27.288  1445  5710 D NfcService: index : 1
03-20 17:20:27.288  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_ON
03-20 17:20:27.288  1741  1741 D accuweather: [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
03-20 17:20:27.288  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
03-20 17:20:27.288  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
03-20 17:20:27.288  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
03-20 17:20:27.298  1018  1545 W ActivityManager: userId = 0, bbcId = -10000
03-20 17:20:27.298  1018  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 17:20:27.298  1018  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
03-20 17:20:27.308  1018  3044 W ActivityManager: userId = 0, bbcId = -10000
03-20 17:20:27.308  1018  3044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-20 17:20:27.308  1018  3044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-20 17:20:27.318  1815  1815 I SamsungIME: getNextShiftState() cursorCapsMode : 0
03-20 17:20:27.338  1018  1018 D LightsService: [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
03-20 17:20:27.338  1018  1018 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
03-20 17:20:27.338  1018  1078 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
03-20 17:20:27.338  1018  1078 E lights  : write_int failed to open -1
03-20 17:20:27.338  1018  1078 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
03-20 17:20:27.338  1018  1018 D BatteryService: turn on LED for charging
03-20 17:20:27.348  1018  2718 D SSRM:n  : SIOP:: AP = 330
03-20 17:20:27.348   288   288 E SMD     : DCD OFF
03-20 17:20:27.348  1018  1093 E SmartFaceService: onReceive: android.intent.action.SCREEN_OFF
03-20 17:20:27.348  1018  1093 W System.err: java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
03-20 17:20:27.348  1018  1093 E SmartFaceService: fail to set sysfs 0
03-20 17:20:27.348  1018  1093 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-20 17:20:27.348  1018  1093 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-20 17:20:27.348  1018  1093 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-20 17:20:27.348  1018  1093 W System.err: 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
03-20 17:20:27.348  1018  1093 W System.err: 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
03-20 17:20:27.348  1018  1093 W System.err: 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
03-20 17:20:27.348  1018  1093 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
03-20 17:20:27.348  1018  1093 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-20 17:20:27.348  1018  1093 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-20 17:20:27.348  1018  1093 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:27.348  1018  1093 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:27.348  1018  1093 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
03-20 17:20:27.348  1018  1093 W System.err: 	at libcore.io.Posix.open(Native Method)
03-20 17:20:27.348  1018  1093 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-20 17:20:27.348  1018  1093 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-20 17:20:27.348  1018  1093 W System.err: 	... 10 more
03-20 17:20:27.358  1773  1773 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-20 17:20:27.358  1773  1773 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-20 17:20:27.368  1773  1773 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-20 17:20:27.368  1178  1178 D PanelView: There is/are notification(s) 
03-20 17:20:27.368  1018  1018 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
03-20 17:20:27.368  1815  1815 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
03-20 17:20:27.368  1018  1105 E MotionRecognitionService:  handler : SCREEN_OFF end 
03-20 17:20:27.378  1018  1018 D NotificationService: ACTION_SCREEN_OFF
03-20 17:20:27.378  1018  1018 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
03-20 17:20:27.378  1018  1018 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=4) set Off
03-20 17:20:27.378  1018  1078 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
03-20 17:20:27.378  1018  1078 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
03-20 17:20:27.378  1773  1773 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-20 17:20:27.378   283   704 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-20 17:20:27.378   283   704 V voice   : voice_set_parameters: enter: screen_state=off
03-20 17:20:27.378   283   704 V voice   : voice_set_parameters: exit with code(-2)
03-20 17:20:27.378   283   704 V msm8974_platform: platform_set_parameters: enter: screen_state=off
03-20 17:20:27.378   283   704 V msm8974_platform: platform_set_parameters: exit with code(-2)
03-20 17:20:27.378   283   704 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
03-20 17:20:27.378   283   704 V audio_hw_primary: adev_set_parameters: exit
03-20 17:20:27.388  1773  1773 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
03-20 17:20:27.388  1018  1126 E WifiNative-wlan0: do suspend true
03-20 17:20:27.388  1773  1773 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
03-20 17:20:27.388  1773  1773 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-20 17:20:27.388  1773  1773 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-20 17:20:27.388  1773  1773 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-20 17:20:27.388  1773  1773 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-20 17:20:27.388  1773  1773 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-20 17:20:27.388  1773  1773 D daemonapp: [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
03-20 17:20:27.388  1773  1773 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-20 17:20:27.398  1018  1049 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
03-20 17:20:27.398  1018  1049 D IpRemoteDisplayController: Bridge Server is not available
03-20 17:20:27.398  1773  1773 D daemonapp: [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
03-20 17:20:27.398  1773  1773 D daemonapp: [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1458512340000
03-20 17:20:27.398  1773  1773 D daemonapp: [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1458490827409
03-20 17:20:27.398  1773  1773 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-20 17:20:27.398  1018  1043 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
03-20 17:20:27.398  1773  1773 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
03-20 17:20:27.398  1018  1018 D PersonaManagerService: ACTION_SCREEN_OFF onReceive
03-20 17:20:27.408  1018  1063 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
03-20 17:20:27.408  1773  1773 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-20 17:20:27.408  1773  1773 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-20 17:20:27.408  1773  1773 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
03-20 17:20:27.408  1773  1773 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-20 17:20:27.408  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
03-20 17:20:27.418  1773  1773 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
03-20 17:20:27.418  1420  1420 V EmergencyMode: [EmergencyStateReceiver] binteractive [false] why[3]
03-20 17:20:27.428   257   530 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
03-20 17:20:27.428   257   257 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
03-20 17:20:27.428  1018  1056 D SurfaceControl: Excessive delay in setPowerMode(): 251ms
03-20 17:20:27.428  1018  1056 D PowerManagerService: Excessive delay in !@display_state: OFF: 257ms
03-20 17:20:27.428   257   530 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
03-20 17:20:27.428   257   530 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
03-20 17:20:27.428  1018  1056 I libsuspend: !@autosuspend_wakeup_count_enable
03-20 17:20:27.428  1018  1056 I libsuspend: !@autosuspend_wakeup_count_enable done
03-20 17:20:27.428  1018  1056 D PowerManagerService: Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 318ms
03-20 17:20:27.428  1445  5714 D NfcService: call the applyRouting
03-20 17:20:27.428  1018  1051 I PowerManagerService: [PWL] Off : 0s ago
03-20 17:20:27.428  1018  1051 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
03-20 17:20:27.428  1018  1051 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
03-20 17:20:27.428  1018  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1794, ws=null) (elapsedTime=43112)
03-20 17:20:27.428  1018  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1794, ws=null) (elapsedTime=26644)
03-20 17:20:27.428  1018  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'NfcService:mRoutingWakeLock' (uid=1027, pid=1445, ws=null) (elapsedTime=2)
03-20 17:20:27.428  1018  1051 I PowerManagerService: [PWL]   PowerManagerService.Broadcasts: ref count=1
03-20 17:20:27.438  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_OFF
03-20 17:20:27.438  1741  1741 D accuweather: [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
03-20 17:20:27.438  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
03-20 17:20:27.438  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
03-20 17:20:27.448  1018  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 17:20:27.448  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
03-20 17:20:27.448  1018  1542 W ActivityManager: userId = 0, bbcId = -10000
03-20 17:20:27.448  1018  1542 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 17:20:27.448  1018  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
03-20 17:20:27.448  1741  1741 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
03-20 17:20:27.468  1773  1783 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
03-20 17:20:27.468  1741  1741 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
03-20 17:20:27.468  1741  1741 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
03-20 17:20:27.468  1741  1741 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
03-20 17:20:27.468  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
03-20 17:20:27.468  1018  1545 W ActivityManager: userId = 0, bbcId = -10000
03-20 17:20:27.468  1018  1545 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-20 17:20:27.468  1018  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-20 17:20:27.468  1773  1790 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
03-20 17:20:27.478  1445  5714 D NfcService: index : 0
03-20 17:20:27.478  1445  5714 D NfcService: index : 1
03-20 17:20:27.488  1900  1900 E LibSecureUISvc: svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
03-20 17:20:27.488  1018  2718 D SSRM:n  : SIOP:: AP = 310
03-20 17:20:27.498  5692  5692 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-20 17:20:27.498  1773  4521 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-20 17:20:27.508  1018  1154 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
03-20 17:20:27.518  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
03-20 17:20:27.518  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
03-20 17:20:27.518  1741  1741 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
03-20 17:20:27.518  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
03-20 17:20:27.518  1018  1079 W ActivityManager: userId = 0, bbcId = -10000
03-20 17:20:27.518  1018  1079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 17:20:27.518  1018  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
03-20 17:20:27.528  1741  1741 D accuweather: [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
03-20 17:20:27.528  1741  1741 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
03-20 17:20:27.528  1741  1741 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
03-20 17:20:27.928  1384  1384 I wpa_supplicant: nl80211: Received scan results (12 BSSes)
03-20 17:20:27.938  1018  1125 D WifiP2pService: InactiveState{ what=147461 }
03-20 17:20:27.938  1018  1125 D WifiP2pService: P2pEnabledState{ what=147461 }
03-20 17:20:27.938  1018  1125 D WifiP2pService: DefaultState{ what=147461 }
03-20 17:20:28.128  1018  2718 D SSRM:a  : DeviceInfo:: 000000000000
03-20 17:20:28.128  1018  2718 D SSRM:a  : SettingsAirViewInfo:: 000000000
03-20 17:20:28.488  1018  1097 V AlarmManager: waitForAlarm result :4
03-20 17:20:28.488  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 17:20:28.488  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 17:20:28.488  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 17:20:28.488  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 17:20:28.508  5717  5717 E Zygote  : MountEmulatedStorage()
03-20 17:20:28.508  5717  5717 E Zygote  : v2
03-20 17:20:28.508  5717  5717 I libpersona: KNOX_SDCARD checking this for 10102
03-20 17:20:28.508  5717  5717 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-20 17:20:28.508  5717  5717 I libpersona: KNOX_SDCARD not a persona
03-20 17:20:28.508  1018  1044 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5717 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
03-20 17:20:28.518  5717  5717 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-20 17:20:28.518  5717  5717 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-20 17:20:28.548  5717  5717 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 17:20:28.548  5717  5717 D ActivityThread: Added TimaKeyStore provider
,03-20 17:20:28.568  5717  5717 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-20 17:20:28.658  1018  1322 E Watchdog: !@Sync 2
,03-20 17:20:28.688  5717  5741 I Babel   : MmsConfig: mnc/mcc: 0/0
,03-20 17:20:28.698  5717  5741 I Babel   : MmsConfig.loadMmsSettings
,03-20 17:20:28.698  5717  5741 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,03-20 17:20:28.698  5717  5741 I Babel   : MmsConfig.loadFromDatabase
,03-20 17:20:28.708  5717  5740 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-20 17:20:28.708  5717  5741 E Babel   : canonicalizeMccMnc: invalid mccmnc 
03-20 17:20:28.708  5717  5741 I Babel   : MmsConfig.loadFromResources
,03-20 17:20:28.708  5717  5741 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
03-20 17:20:28.708  5717  5740 W AudioCapabilities: Unsupported mime audio/evrc
03-20 17:20:28.708  5717  5741 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,03-20 17:20:28.708  5717  5717 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-20 17:20:28.708  5717  5740 W AudioCapabilities: Unsupported mime audio/qcelp
,03-20 17:20:28.718  5717  5740 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-20 17:20:28.718  5717  5740 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-20 17:20:28.718  5717  5740 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-20 17:20:28.718  5717  5740 W AudioCapabilities: Unsupported mime audio/x-ima
,03-20 17:20:28.718  5717  5740 W AudioCapabilities: Unsupported mime audio/qcelp
,03-20 17:20:28.728  5717  5740 W AudioCapabilities: Unsupported mime audio/evrc
,03-20 17:20:28.738  5717  5740 W VideoCapabilities: Unsupported mime video/wvc1
,03-20 17:20:28.738  5717  5740 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-20 17:20:28.748  5717  5740 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,03-20 17:20:28.758  1018  1542 W ActivityManager: userId = 0, bbcId = -10000
03-20 17:20:28.758  5717  5740 W VideoCapabilities: Unsupported mime video/wvc1
,03-20 17:20:28.758  1018  1542 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-20 17:20:28.758  1018  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-20 17:20:28.758  5717  5740 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-20 17:20:28.758  5717  5740 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-20 17:20:28.758  5717  5740 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,03-20 17:20:28.758  5717  5740 W VideoCapabilities: Unsupported mime video/mp43
,03-20 17:20:28.768  5717  5740 W VideoCapabilities: Unsupported mime video/sorenson
,03-20 17:20:28.778  5717  5740 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,03-20 17:20:28.788  5717  5740 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-20 17:20:28.808  1018  1345 I ActivityManager: Killing 4980:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,03-20 17:20:28.838  1018  1758 W ActivityManager: userId = 0, bbcId = -10000
,03-20 17:20:28.838  1018  1758 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-20 17:20:28.838  1018  1758 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-20 17:20:28.858  1018  1043 W libprocessgroup: failed to open /acct/uid_10008/pid_4980/cgroup.procs: No such file or directory
,03-20 17:20:29.368   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:20:29.608  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-20 17:20:30.348   288   288 E SMD     : DCD OFF,
,03-20 17:20:30.368   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:20:31.368   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:20:31.608  1018  1501 W ActivityManager: userId = 0, bbcId = -10000
,03-20 17:20:31.608  1018  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-20 17:20:31.608  1018  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,03-20 17:20:31.608  1018  3043 W ActivityManager: userId = 0, bbcId = -10000
03-20 17:20:31.608  1018  3043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-20 17:20:31.608  1018  3043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 17:20:31.638  1018  1541 W ActivityManager: userId = 0, bbcId = -10000
,03-20 17:20:31.638  1018  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-20 17:20:31.638  1018  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 17:20:31.648  1018  1542 W ActivityManager: userId = 0, bbcId = -10000
,03-20 17:20:31.648  1018  1542 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-20 17:20:31.648  1018  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 17:20:31.668  1018  1541 W ActivityManager: userId = 0, bbcId = -10000
,03-20 17:20:31.668  1018  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-20 17:20:31.668  1018  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 17:20:31.678  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-20 17:20:31.678  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-20 17:20:31.678  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 17:20:31.698  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
03-20 17:20:31.698  1018  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-20 17:20:31.698  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 17:20:31.718  1018  1541 W ActivityManager: userId = 0, bbcId = -10000
,03-20 17:20:31.718  1018  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-20 17:20:31.718  1018  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 17:20:31.738  1018  3043 W ActivityManager: userId = 0, bbcId = -10000
,03-20 17:20:31.738  1018  3043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-20 17:20:31.738  1018  3043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 17:20:31.738  1018  1097 V AlarmManager: waitForAlarm result :4
,03-20 17:20:31.748  1018  3044 W ActivityManager: userId = 0, bbcId = -10000
,03-20 17:20:31.748  1018  3044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-20 17:20:31.748  1018  3044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 17:20:31.748  1178  1178 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,03-20 17:20:31.748  1178  1178 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,03-20 17:20:31.748  1178  1178 V KeyguardEffectViewController: *** Keyguard wallpaper service already unbounded
,03-20 17:20:32.378   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:20:32.438  1018  1051 I PowerManagerService: [PWL] Off : 5s ago
,03-20 17:20:32.438  1018  1051 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
03-20 17:20:32.438  1018  1051 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,03-20 17:20:32.438  1018  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1794, ws=null) (elapsedTime=48115)
,03-20 17:20:32.438  1018  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1794, ws=null) (elapsedTime=31647)
,03-20 17:20:33.358   288   288 E SMD     : DCD OFF
,03-20 17:20:33.378   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:20:34.368   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-20 17:20:34.618  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-20 17:20:36.348   288   288 E SMD     : DCD OFF,
,03-20 17:20:37.028  1018  1758 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:20:37.028  1018  1758 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4277, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:20:37.028  1018  1758 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:20:37.028  1018  1758 D BatteryService: stay LED for charging,
03-20 17:20:37.028  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:20:37.038  1018  1018 I MotionRecognitionService: Plugged,
03-20 17:20:37.038  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:20:37.038  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:20:37.038  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:20:37.038  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:20:37.038  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:20:37.058  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:20:37.058  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:20:37.068  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:20:37.068  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:20:37.068  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:20:37.068  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:20:37.068  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:20:37.518  1018  2718 D SSRM:n  : SIOP:: AP = 310,
,03-20 17:20:39.358   288   288 E SMD     : DCD OFF
,03-20 17:20:39.418  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:39.418  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:39.418  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
03-20 17:20:39.418  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
03-20 17:20:39.418  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:39.418  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-20 17:20:39.418   278  1003 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-20 17:20:39.418   278  1003 D Netd    : getNetworkForDns: using netid 502 for uid 10088
,03-20 17:20:39.608  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-20 17:20:39.788  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:39.788  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:39.788  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
03-20 17:20:39.788  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
03-20 17:20:39.788  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:39.788  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:40.198  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:40.198  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:40.198  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:40.198  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
03-20 17:20:40.198  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,03-20 17:20:40.198  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:40.598  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:40.598  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:40.598  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:40.598  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
03-20 17:20:40.598  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:40.598  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:41.008  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:41.008  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:41.008  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:41.008  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
03-20 17:20:41.008  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:41.008  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:41.408  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:41.408  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:41.408  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false,
03-20 17:20:41.408  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
03-20 17:20:41.408  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:41.408  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:41.808  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:41.808  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:41.808  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:41.808  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
03-20 17:20:41.808  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:41.808  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:41.808   278  1003 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-20 17:20:41.808   278  1003 D Netd    : getNetworkForDns: using netid 502 for uid 10088
,03-20 17:20:42.178  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:42.178  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:42.178  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:42.178  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
03-20 17:20:42.178  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:42.178  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:42.358   288   288 E SMD     : DCD OFF,
,03-20 17:20:42.438  1018  1051 I PowerManagerService: [PWL] Off : 15s ago,
03-20 17:20:42.438  1018  1051 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
03-20 17:20:42.438  1018  1051 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,03-20 17:20:42.438  1018  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1794, ws=null) (elapsedTime=58122)
03-20 17:20:42.438  1018  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1794, ws=null) (elapsedTime=41654)
,03-20 17:20:42.548  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: Error uploading log: ,
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
,03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	,at android.os.Looper.loop(Looper.java:145)
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
,03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167),
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	,at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:42.548  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:42.548  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
03-20 17:20:42.548  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
03-20 17:20:42.548  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false,
03-20 17:20:42.548  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:42.918  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:42.918  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
03-20 17:20:42.918  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
03-20 17:20:42.918  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
03-20 17:20:42.918  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:42.918  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:43.298  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:43.298  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:43.298  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:43.298  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
03-20 17:20:43.298  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:43.298  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:43.708  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:43.708  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:43.708  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:43.708  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
,03-20 17:20:43.708  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,03-20 17:20:43.708  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:44.078  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:44.078  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:44.078  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:44.078  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
,03-20 17:20:44.078  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:44.078  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-20 17:20:44.078   278  1003 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,03-20 17:20:44.078   278  1003 D Netd    : getNetworkForDns: using netid 502 for uid 10088
,03-20 17:20:44.448  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: Error uploading log: ,
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: ,	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173),
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702),
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	,at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:44.448  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
03-20 17:20:44.448  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
03-20 17:20:44.448  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
03-20 17:20:44.448  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:44.448  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:44.608  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-20 17:20:44.828  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:44.828  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:44.828  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:44.828  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
,03-20 17:20:44.828  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,03-20 17:20:44.828  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:45.198  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:45.198  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:45.198  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:45.198  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
,03-20 17:20:45.198  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:45.198  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:45.368   288   288 E SMD     : DCD OFF,
,03-20 17:20:45.648  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:45.648  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:45.648  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:45.648  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
,03-20 17:20:45.648  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,03-20 17:20:45.648  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:46.038  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:46.038  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:46.038  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:46.038  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
,03-20 17:20:46.038  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:46.038  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
,03-20 17:20:46.408  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:46.408  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:46.408  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:46.408  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
,03-20 17:20:46.408  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,03-20 17:20:46.408  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-20 17:20:46.408   278  1003 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-20 17:20:46.408   278  1003 D Netd    : getNetworkForDns: using netid 502 for uid 10088,
,03-20 17:20:46.808  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch(),
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
,03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:46.808  5516  5537 I c,om.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:46.808  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:46.808  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
03-20 17:20:46.808  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
03-20 17:20:46.808  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:46.808  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:47.088  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:20:47.088  1018  1542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:20:47.088  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:20:47.088  1018  1542 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4276, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:20:47.088  1018  1542 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:20:47.088  1018  1542 D BatteryService: stay LED for charging
03-20 17:20:47.088  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:20:47.088  1018  1018 I MotionRecognitionService: Plugged
03-20 17:20:47.088  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:20:47.088  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:20:47.088  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:20:47.108  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:20:47.108  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:20:47.118  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:20:47.118  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:20:47.118  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:20:47.118  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:20:47.118  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:20:47.168  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:47.178  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:47.178  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:47.178  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
,03-20 17:20:47.178  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:47.178  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:47.538  1018  2718 D SSRM:n  : SIOP:: AP = 300
,03-20 17:20:47.578  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:47.578  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:47.588  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:47.588  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
03-20 17:20:47.588  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:47.588  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:47.988  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:47.988  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:47.988  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:47.988  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
,03-20 17:20:47.988  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:47.988  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:48.148   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7efe7c8
03-20 17:20:48.148   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
03-20 17:20:48.148   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
03-20 17:20:48.148   271   327 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1209014984)
,03-20 17:20:48.188   271   327 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504,
03-20 17:20:48.188   271   327 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
03-20 17:20:48.188   271   327 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1209014984) wakelock released: 1, error no: 0
03-20 17:20:48.188   271   327 I rmt_storage: 
,03-20 17:20:48.188   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7efe7c8
,03-20 17:20:48.368   288   288 E SMD     : DCD OFF,
,03-20 17:20:48.368  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: Error uploading log: ,
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129),
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
,03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate,
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: ,	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
,03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	,at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394),
03-20 17:20:48.368  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
03-20 17:20:48.368  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:48.368  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
03-20 17:20:48.368  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,03-20 17:20:48.368  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:48.778  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:48.778  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:48.778  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:48.778  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
,03-20 17:20:48.778  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:48.778  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-20 17:20:48.778   278  1003 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,03-20 17:20:48.778   278  1003 D Netd    : getNetworkForDns: using netid 502 for uid 10088
,03-20 17:20:49.278  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:49.278  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:49.278  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:49.288  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true,
03-20 17:20:49.288  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,03-20 17:20:49.288  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:49.688  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:49.688  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:49.688  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:49.688  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
03-20 17:20:49.688  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:49.688  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:50.058  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:50.058  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:50.058  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:50.058  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
,03-20 17:20:50.058  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,03-20 17:20:50.058  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:50.418  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:50.418  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:50.418  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:50.418  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
,03-20 17:20:50.418  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,03-20 17:20:50.418  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:50.828  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:50.828  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:50.828  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false,
03-20 17:20:50.828  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
03-20 17:20:50.828  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,03-20 17:20:50.828  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:51.198  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:51.198  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:51.198  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:51.198  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
,03-20 17:20:51.198  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:51.198  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:51.198   278  1003 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-20 17:20:51.198   278  1003 D Netd    : getNetworkForDns: using netid 502 for uid 10088
,03-20 17:20:51.368   288   288 E SMD     : DCD OFF,
,03-20 17:20:51.598  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:51.598  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:51.608  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:51.608  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
,03-20 17:20:51.608  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,03-20 17:20:51.608  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:52.008  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:52.008  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:52.008  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:52.008  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
,03-20 17:20:52.008  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:52.008  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:52.408  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:52.408  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:52.408  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:52.408  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true,
03-20 17:20:52.408  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,03-20 17:20:52.408  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:52.778  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:52.778  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:52.778  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:52.778  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
03-20 17:20:52.778  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false,
03-20 17:20:52.778  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:53.178  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:53.178  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:53.178  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:53.178  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
,03-20 17:20:53.178  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:53.178  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-20 17:20:53.588  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:53.588  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:53.588  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isSBSettingEnabled false
,03-20 17:20:53.588  5516  5537 I System.out: Thread-951(ApacheHTTPLog):isShipBuild true
,03-20 17:20:53.588  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-20 17:20:53.588  5516  5537 I System.out: Thread-951(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-20 17:20:53.588   278  1003 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,03-20 17:20:53.588   278  1003 D Netd    : getNetworkForDns: using netid 502 for uid 10088
,03-20 17:20:53.998  5516  5537 I System.out: IntentService[CrashUploaderService] calls detatch()
,03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: Error uploading log: 
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: dbxyzptlk.db240408.I.h: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:424)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:346)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.K.a(panda.py:472)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:129)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.d.a(panda.py:52)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at com.dropbox.android.exception.CrashUploaderService.onHandleIntent(panda.py:33)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: Caused by: javax.net.ssl.SSLPeerUnverifiedException: No peer certificate
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at com.android.org.conscrypt.SSLNullSession.getPeerCertificates(SSLNullSession.java:104)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.conn.ssl.AbstractVerifier.verify(AbstractVerifier.java:93)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.L.Q.createSocket(panda.py:173)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:214)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	at dbxyzptlk.db240408.H.y.a(panda.py:394)
03-20 17:20:53.998  5516  5537 I com.dropbox.android.exception.d: 	... 9 more
,03-20 17:20:53.998  1018  1223 I ActivityManager: Killing 5070:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,03-20 17:20:54.158  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_5070/cgroup.procs: No such file or directory,
,03-20 17:20:54.368   288   288 E SMD     : DCD OFF,
,03-20 17:20:57.138  1018  3044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:20:57.138  1018  3044 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4303, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:20:57.138  1018  3044 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
03-20 17:20:57.138  1018  3044 D BatteryService: stay LED for charging
03-20 17:20:57.138  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-20 17:20:57.148  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:20:57.148  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:20:57.148  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-20 17:20:57.148  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:20:57.148  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:20:57.148  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:20:57.168  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-20 17:20:57.168  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:20:57.168  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:20:57.178  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:20:57.178  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:20:57.178  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
03-20 17:20:57.178  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:20:57.368   288   288 E SMD     : DCD OFF,
,03-20 17:20:57.438  1018  1051 I PowerManagerService: [PWL] Off : 30s ago,
03-20 17:20:57.438  1018  1051 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
03-20 17:20:57.438  1018  1051 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1,
03-20 17:20:57.438  1018  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1794, ws=null) (elapsedTime=56654)
,03-20 17:20:57.488  1018  1097 V AlarmManager: waitForAlarm result :4
,03-20 17:20:57.558  1018  2718 D SSRM:n  : SIOP:: AP = 300,
,03-20 17:20:58.668  1018  1322 E Watchdog: !@Sync 3,
,03-20 17:20:59.368   318   318 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
03-20 17:20:59.368   318   318 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-20 17:20:59.998  1018  1097 V AlarmManager: waitForAlarm result :8
,03-20 17:21:00.278  5449  5449 D FactoryTest: Not factory mode
,03-20 17:21:00.278  5449  5449 D FactoryTest: Not factory mode. isFactoryMode() returend false
,03-20 17:21:00.288  5449  5449 D MTPRx   : DRIVER_TIME_OUT 60s lapsed,
03-20 17:21:00.288  5449  5449 D MTPRx   : still no open session command from host, so toast
03-20 17:21:00.288  5449  5449 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,03-20 17:21:00.288  5449  5449 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:109141,
03-20 17:21:00.288  5449  5449 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
03-20 17:21:00.288  1018  1351 E PersonaManagerService: inState():  stateMachine is null !!
03-20 17:21:00.288  1018  1351 I PersonaManagerService: PersonaId don't exist,
03-20 17:21:00.288  1018  1351 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-20 17:21:00.288  1018  1351 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,03-20 17:21:00.288  1018  1351 W ActivityManager: userId = 0, bbcId = -10000,
,03-20 17:21:00.288  1018  1351 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-20 17:21:00.288  1018  1351 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,03-20 17:21:00.298  1018  1351 W ActivityManager: mDVFSHelper.acquire(),
,03-20 17:21:00.308  1018  1018 V ActivityManager: Display changed displayId=0
,03-20 17:21:00.318  1018  1351 D PersonaManager: isKioskContainerExistOnDevice
,03-20 17:21:00.328  1018  1351 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-20 17:21:00.328  1018  1351 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,03-20 17:21:00.328  1018  1351 D InputDispatcher: Focused application set to: xxxx
03-20 17:21:00.328  1018  1351 D InputDispatcher: Focus left window: 4354
,03-20 17:21:00.328  5449  5449 E MTPRx   : started activity for popup
,03-20 17:21:00.338  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-20 17:21:00.338  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-20 17:21:00.358  5449  5449 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-20 17:21:00.358  5449  5449 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-20 17:21:00.358  5449  5449 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-20 17:21:00.358  5449  5449 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-20 17:21:00.358  5449  5449 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-20 17:21:00.358  5449  5449 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-20 17:21:00.358   288   288 E SMD     : DCD OFF
,03-20 17:21:00.368  5449  5449 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : false
,03-20 17:21:00.398  5449  5449 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,03-20 17:21:00.408  5449  5449 D PhoneWindow: *FMB* installDecor mIsFloating : true
,03-20 17:21:00.408  5449  5449 D PhoneWindow: *FMB* installDecor flags : 8388610
,03-20 17:21:00.418  5449  5776 D OpenGLRenderer: Render dirty regions requested: true
,03-20 17:21:00.428  1018  1758 D ActivityManager: post active user change for 0 fullscreen false record.isFloatingActivity() false
,03-20 17:21:00.428  1018  1758 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-20 17:21:00.428  1018  1758 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-20 17:21:00.428  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-20 17:21:00.428  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
03-20 17:21:00.428  1018  1018 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,03-20 17:21:00.438  5449  5449 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,03-20 17:21:00.438  5449  5449 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-20 17:21:00.468   257   257 I SurfaceFlinger: id=13 createSurf (73x73),1 flag=4, TettingsRec
,03-20 17:21:00.468  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-20 17:21:00.488  1018  1501 D InputDispatcher: Focus entered window: 5449
,03-20 17:21:00.488  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-20 17:21:00.488  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-20 17:21:00.488  5449  5449 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-20 17:21:00.488  5449  5776 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-20 17:21:00.488  5449  5776 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-20 17:21:00.488  5449  5776 I Adreno-EGL: Build Date: 04/06/15 Mon
03-20 17:21:00.488  5449  5776 I Adreno-EGL: Local Branch: 
03-20 17:21:00.488  5449  5776 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-20 17:21:00.488  5449  5776 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-20 17:21:00.488  5449  5776 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-20 17:21:00.488  5449  5776 I OpenGLRenderer: Initialized EGL, version 1.4
,03-20 17:21:00.508  5449  5776 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,03-20 17:21:00.508  5449  5776 D OpenGLRenderer: Enabling debug mode 0
,03-20 17:21:00.528  5449  5449 V ActivityThread: updateVisibility : ActivityRecord{eae792c token=android.os.BinderProxy@97d8d00 {com.android.settings/com.android.settings.SettingsReceiverActivity}} show : true
,03-20 17:21:00.558  5449  5449 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@97d8d00 time:109414
,03-20 17:21:00.568  1018  1049 I ActivityManager: Displayed Component not be shown by security: +247ms (total +266ms)
,03-20 17:21:00.568  1018  1049 W ActivityManager: mDVFSHelper.release()
,03-20 17:21:00.568  1018  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c19ce61 u0 com.android.settings/.SettingsReceiverActivity t58} time:109429
,03-20 17:21:03.368   288   288 E SMD     : DCD OFF
,03-20 17:21:04.368   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:21:04.618  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-20 17:21:05.378   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:21:06.368   288   288 E SMD     : DCD OFF
,03-20 17:21:06.368   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:21:07.188  1018  1546 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:21:07.188  1018  1546 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4286, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:21:07.188  1018  1546 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
03-20 17:21:07.188  1018  1546 D BatteryService: stay LED for charging,
03-20 17:21:07.188  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-20 17:21:07.188  1018  1018 I MotionRecognitionService: Plugged
03-20 17:21:07.188  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
03-20 17:21:07.198  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:21:07.198  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:21:07.198  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:21:07.198  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:21:07.208  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:21:07.218  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:21:07.218  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:21:07.218  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:21:07.228  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:21:07.228  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:21:07.228  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:21:07.378   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:21:07.578  1018  2718 D SSRM:n  : SIOP:: AP = 300
,03-20 17:21:08.378   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:21:09.368   288   288 E SMD     : DCD OFF
,03-20 17:21:09.368   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,03-20 17:21:12.378   288   288 E SMD     : DCD OFF,
,03-20 17:21:14.378   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:21:15.378   288   288 E SMD     : DCD OFF,
03-20 17:21:15.378   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:21:16.378   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:21:17.238  1018  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:21:17.238  1018  1487 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4290, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:21:17.238  1018  1487 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:21:17.238  1018  1487 D BatteryService: stay LED for charging
03-20 17:21:17.238  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:21:17.238  1018  1018 I MotionRecognitionService: Plugged
03-20 17:21:17.238  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:21:17.248  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:21:17.248  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:21:17.248  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-20 17:21:17.248  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:21:17.258  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:21:17.258  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:21:17.268  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:21:17.268  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:21:17.268  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:21:17.268  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:21:17.268  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:21:17.378   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:21:17.438  1018  1051 I PowerManagerService: [PWL] Off : 50s ago
,03-20 17:21:17.598  1018  2718 D SSRM:n  : SIOP:: AP = 290,
,03-20 17:21:18.378   288   288 E SMD     : DCD OFF,
,03-20 17:21:18.378   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:21:19.378   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,03-20 17:21:21.388   288   288 E SMD     : DCD OFF,
,03-20 17:21:24.378   288   288 E SMD     : DCD OFF,
,03-20 17:21:24.618  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-20 17:21:27.288  1018  3044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:21:27.288  1018  3044 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4291, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:21:27.288  1018  3044 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:21:27.288  1018  3044 D BatteryService: stay LED for charging
03-20 17:21:27.288  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:21:27.298  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:21:27.298  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:21:27.298  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:21:27.298  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:21:27.298  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:21:27.298  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:21:27.308  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:21:27.308  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:21:27.318  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
03-20 17:21:27.318  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:21:27.318  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:21:27.318  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:21:27.318  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:21:27.378   288   288 E SMD     : DCD OFF,
,03-20 17:21:27.618  1018  2718 D SSRM:n  : SIOP:: AP = 290
,03-20 17:21:28.668  1018  1322 E Watchdog: !@Sync 4,
,03-20 17:21:29.388   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:21:30.378   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:21:30.378   288   288 E SMD     : DCD OFF,
,03-20 17:21:31.388   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:21:32.378   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:21:33.378   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:21:33.388   288   288 E SMD     : DCD OFF
,03-20 17:21:34.378   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-20 17:21:36.398   288   288 E SMD     : DCD OFF
,03-20 17:21:37.338  1018  1542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:21:37.338  1018  1542 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:21:37.338  1018  1542 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:21:37.338  1018  1542 D BatteryService: stay LED for charging
03-20 17:21:37.338  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:21:37.348  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:21:37.348  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-20 17:21:37.348  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:21:37.348  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:21:37.358  1018  1018 I MotionRecognitionService: Plugged
03-20 17:21:37.358  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:21:37.358  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:21:37.358  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:21:37.368  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:21:37.368  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:21:37.368  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:21:37.368  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:21:37.378  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:21:37.638  1018  2718 D SSRM:n  : SIOP:: AP = 290,
,03-20 17:21:39.398   288   288 E SMD     : DCD OFF
,03-20 17:21:42.398   288   288 E SMD     : DCD OFF
,03-20 17:21:42.458  1018  1051 I PowerManagerService: [PWL] Off : 75s ago
,03-20 17:21:44.618  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-20 17:21:45.398   288   288 E SMD     : DCD OFF
,03-20 17:21:47.388  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:21:47.388  1018  1501 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4293, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:21:47.388  1018  1501 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:21:47.388  1018  1501 D BatteryService: stay LED for charging
03-20 17:21:47.388  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:21:47.398  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:21:47.398  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:21:47.398  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:21:47.398  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:21:47.398  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:21:47.398  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:21:47.408  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:21:47.408  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:21:47.418  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:21:47.428  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:21:47.428  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:21:47.428  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:21:47.428  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:21:47.658  1018  2718 D SSRM:n  : SIOP:: AP = 290,
,03-20 17:21:48.398   288   288 E SMD     : DCD OFF,
,03-20 17:21:49.388   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:21:50.378   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:21:51.388   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:21:51.398   288   288 E SMD     : DCD OFF,
,03-20 17:21:52.378   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:21:53.388   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:21:54.388   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,03-20 17:21:54.408   288   288 E SMD     : DCD OFF,
,03-20 17:21:57.398   288   288 E SMD     : DCD OFF
,03-20 17:21:57.438  1018  1541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:21:57.508  1018  1097 V AlarmManager: waitForAlarm result :4
,03-20 17:21:57.508  1018  1018 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,03-20 17:21:57.508  1018  1018 V AlarmManagerEXT: <AppSync3 Whitelist>,
03-20 17:21:57.518  1018  1018 V AlarmManagerEXT: (AppSync) ### 0 added ###
,03-20 17:21:57.518  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-20 17:21:57.518  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,03-20 17:21:57.528  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,03-20 17:21:57.528  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,03-20 17:21:57.538  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:21:57.538  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK,
03-20 17:21:57.538  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
,03-20 17:21:57.578  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:21:57.588  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:21:57.588  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:21:57.598  1178  1178 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-20 17:21:57.608  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-20 17:21:57.608  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-20 17:21:57.608  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 17:21:57.618  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:21:57.618  1018  3044 W ActivityManager: userId = 0, bbcId = -10000
03-20 17:21:57.618  1018  3044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-20 17:21:57.618  1018  3044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 17:21:57.638  1634  5803 I VacuumService: Vacuum at: now=1458490917656 tag=VacuumService
,03-20 17:21:57.708  1018  2718 D SSRM:n  : SIOP:: AP = 290,
,03-20 17:21:57.718  1018  1223 W ActivityManager: userId = 0, bbcId = -10000
,03-20 17:21:57.718  1018  1223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-20 17:21:57.718  1018  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 17:21:57.728  1018  1758 W ActivityManager: userId = 0, bbcId = -10000
,03-20 17:21:57.728  1018  1758 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-20 17:21:57.728  1018  1758 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 17:21:57.738  1018  1345 W ActivityManager: userId = 0, bbcId = -10000
,03-20 17:21:57.738  1018  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-20 17:21:57.738  1018  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 17:21:58.668  1018  1322 E Watchdog: !@Sync 5
,03-20 17:21:59.998  1018  1097 V AlarmManager: waitForAlarm result :8
,03-20 17:22:00.408   288   288 E SMD     : DCD OFF
,03-20 17:22:03.398   288   288 E SMD     : DCD OFF,
,03-20 17:22:04.618  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-20 17:22:06.418   288   288 E SMD     : DCD OFF
,03-20 17:22:07.488  1018  1351 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:22:07.488  1018  1351 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4295, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
03-20 17:22:07.488  1018  1351 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
03-20 17:22:07.488  1018  1351 D BatteryService: stay LED for charging
03-20 17:22:07.488  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-20 17:22:07.498  1018  1018 I MotionRecognitionService: Plugged
03-20 17:22:07.498  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
,03-20 17:22:07.498  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-20 17:22:07.498  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:22:07.508  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:22:07.508  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:22:07.518  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:22:07.518  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:22:07.538  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:22:07.538  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:22:07.538  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:22:07.538  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:22:07.538  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:22:07.728  1018  2718 D SSRM:n  : SIOP:: AP = 290,
,03-20 17:22:09.418   288   288 E SMD     : DCD OFF,
,03-20 17:22:12.418   288   288 E SMD     : DCD OFF,
,03-20 17:22:12.458  1018  1051 I PowerManagerService: [PWL] Off : 105s ago
,03-20 17:22:14.388   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:22:15.388   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:22:15.418   288   288 E SMD     : DCD OFF,
,03-20 17:22:16.398   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:22:17.388   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:22:17.538  1018  3043 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:22:17.538  1018  3043 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4295, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:22:17.538  1018  3043 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:22:17.538  1018  3043 D BatteryService: stay LED for charging
03-20 17:22:17.538  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:22:17.548  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:22:17.548  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-20 17:22:17.548  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:22:17.548  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-20 17:22:17.558  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:22:17.558  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:22:17.558  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:22:17.558  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:22:17.578  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:22:17.578  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:22:17.578  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:22:17.578  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:22:17.578  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:22:17.758  1018  2718 D SSRM:n  : SIOP:: AP = 280,
,03-20 17:22:18.398   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:22:18.418   288   288 E SMD     : DCD OFF,
,03-20 17:22:19.398   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-20 17:22:21.428   288   288 E SMD     : DCD OFF
,03-20 17:22:24.418   288   288 E SMD     : DCD OFF,
,03-20 17:22:24.618  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-20 17:22:27.428   288   288 E SMD     : DCD OFF,
,03-20 17:22:27.588  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:22:27.798  1018  2718 D SSRM:n  : SIOP:: AP = 270,
,03-20 17:22:28.668  1018  1322 E Watchdog: !@Sync 6,
,03-20 17:22:30.418   288   288 E SMD     : DCD OFF,
,03-20 17:22:33.428   288   288 E SMD     : DCD OFF
,03-20 17:22:36.438   288   288 E SMD     : DCD OFF
,03-20 17:22:37.638  1018  1345 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:22:37.638  1018  1345 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:22:37.638  1018  1345 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:22:37.638  1018  1345 D BatteryService: stay LED for charging,
03-20 17:22:37.638  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:22:37.648  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-20 17:22:37.648  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:22:37.648  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:22:37.658  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-20 17:22:37.658  1018  1018 I MotionRecognitionService: Plugged
03-20 17:22:37.658  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:22:37.658  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:22:37.658  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:22:37.678  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:22:37.678  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:22:37.678  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:22:37.678  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:22:37.678  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:22:37.828  1018  2718 D SSRM:n  : SIOP:: AP = 270,
,03-20 17:22:39.438   288   288 E SMD     : DCD OFF,
,03-20 17:22:42.438   288   288 E SMD     : DCD OFF,
,03-20 17:22:44.388   318   318 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
03-20 17:22:44.388   318   318 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-20 17:22:44.618  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-20 17:22:45.438   288   288 E SMD     : DCD OFF,
,03-20 17:22:47.478  1018  1051 I PowerManagerService: [PWL] Off : 140s ago,
,03-20 17:22:47.688  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-20 17:22:47.868  1018  2718 D SSRM:n  : SIOP:: AP = 270,
,03-20 17:22:48.438   288   288 E SMD     : DCD OFF,
,03-20 17:22:51.448   288   288 E SMD     : DCD OFF
,03-20 17:22:54.398   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:22:54.448   288   288 E SMD     : DCD OFF,
,03-20 17:22:55.398   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:22:56.388   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:22:57.388   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:22:57.448   288   288 E SMD     : DCD OFF,
,03-20 17:22:57.738  1018  1345 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:22:57.748  1018  1345 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4295, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:22:57.748  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:22:57.748  1018  1345 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-20 17:22:57.748  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:22:57.748  1018  1345 D BatteryService: stay LED for charging
03-20 17:22:57.748  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:22:57.748  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:22:57.748  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-20 17:22:57.758  1018  1018 I MotionRecognitionService: Plugged
03-20 17:22:57.758  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:22:57.768  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-20 17:22:57.768  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:22:57.778  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:22:57.778  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:22:57.778  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:22:57.778  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:22:57.778  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:22:57.898  1018  2718 D SSRM:n  : SIOP:: AP = 270,
,03-20 17:22:58.388   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:22:58.668  1018  1322 E Watchdog: !@Sync 7,
,03-20 17:22:59.398   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,03-20 17:23:00.448   288   288 E SMD     : DCD OFF,
,03-20 17:23:03.448   288   288 E SMD     : DCD OFF,
,03-20 17:23:04.388   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:23:04.618  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-20 17:23:05.398   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:23:06.398   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:23:06.448   288   288 E SMD     : DCD OFF
,03-20 17:23:07.408   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:23:07.798  1018  1351 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:23:07.798  1018  1351 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:23:07.798  1018  1351 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:23:07.798  1018  1351 D BatteryService: stay LED for charging
03-20 17:23:07.798  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:23:07.798  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:23:07.798  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:23:07.798  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:23:07.798  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:23:07.798  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:23:07.798  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:23:07.818  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-20 17:23:07.818  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:23:07.828  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:23:07.828  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:23:07.828  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:23:07.828  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:23:07.828  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:23:07.918  1018  2718 D SSRM:n  : SIOP:: AP = 270,
,03-20 17:23:08.398   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:23:09.398   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,03-20 17:23:09.458   288   288 E SMD     : DCD OFF,
,03-20 17:23:12.458   288   288 E SMD     : DCD OFF,
,03-20 17:23:15.458   288   288 E SMD     : DCD OFF,
,03-20 17:23:17.848  1018  3043 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-20 17:23:17.968  1018  2718 D SSRM:n  : SIOP:: AP = 270
,03-20 17:23:18.458   288   288 E SMD     : DCD OFF,
,03-20 17:23:19.408   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:23:20.398   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:23:21.398   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:23:21.458   288   288 E SMD     : DCD OFF
,03-20 17:23:22.398   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:23:23.398   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:23:24.398   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,03-20 17:23:24.468   288   288 E SMD     : DCD OFF
,03-20 17:23:24.618  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-20 17:23:27.468   288   288 E SMD     : DCD OFF,
,03-20 17:23:27.498  1018  1051 I PowerManagerService: [PWL] Off : 180s ago
,03-20 17:23:27.898  1018  1545 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:23:27.898  1018  1545 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4295, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
03-20 17:23:27.898  1018  1545 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-20 17:23:27.898  1018  1545 D BatteryService: stay LED for charging
03-20 17:23:27.898  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-20 17:23:27.908  1018  1018 I MotionRecognitionService: Plugged,
03-20 17:23:27.908  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
,03-20 17:23:27.908  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-20 17:23:27.908  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:23:27.908  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-20 17:23:27.908  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-20 17:23:27.928  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-20 17:23:27.928  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:23:27.938  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
03-20 17:23:27.938  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:23:27.938  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:23:27.938  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:23:27.938  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:23:27.988  1018  2718 D SSRM:n  : SIOP:: AP = 270
,03-20 17:23:28.668  1018  1322 E Watchdog: !@Sync 8
,03-20 17:23:30.458   288   288 E SMD     : DCD OFF
,03-20 17:23:33.468   288   288 E SMD     : DCD OFF
,03-20 17:23:36.478   288   288 E SMD     : DCD OFF
,03-20 17:23:37.948  1018  1345 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:23:37.948  1018  1345 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:23:37.948  1018  1345 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:23:37.948  1018  1345 D BatteryService: stay LED for charging
03-20 17:23:37.948  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:23:37.948  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:23:37.948  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:23:37.958  1018  1018 I MotionRecognitionService: Plugged
03-20 17:23:37.958  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:23:37.958  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:23:37.958  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:23:37.968  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:23:37.968  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:23:37.978  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:23:37.978  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:23:37.978  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:23:37.978  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:23:37.978  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:23:38.008  1018  2718 D SSRM:n  : SIOP:: AP = 270
,03-20 17:23:39.408   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:23:39.468   288   288 E SMD     : DCD OFF
,03-20 17:23:40.408   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:23:41.398   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:23:42.408   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:23:42.478   288   288 E SMD     : DCD OFF
,03-20 17:23:43.408   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:23:44.408   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,03-20 17:23:44.628  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-20 17:23:45.478   288   288 E SMD     : DCD OFF,
,03-20 17:23:47.998  1018  1351 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:23:48.028  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:23:48.478   288   288 E SMD     : DCD OFF,
,03-20 17:23:51.488   288   288 E SMD     : DCD OFF
,03-20 17:23:54.488   288   288 E SMD     : DCD OFF,
,03-20 17:23:57.488   288   288 E SMD     : DCD OFF,
,03-20 17:23:57.768  1018  1097 V AlarmManager: waitForAlarm result :4
,03-20 17:23:57.768  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-20 17:23:57.768  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate,
,03-20 17:23:57.778  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-20 17:23:57.778  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,03-20 17:23:57.788  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:23:57.788  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-20 17:23:57.788  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
,03-20 17:23:57.818  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,03-20 17:23:57.818  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:23:57.828  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:23:57.828  1178  1178 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-20 17:23:57.838  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:23:58.048  1018  1545 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:23:58.048  1018  1545 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4285, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-20 17:23:58.048  1018  1545 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:23:58.048  1018  1545 D BatteryService: stay LED for charging
03-20 17:23:58.048  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:23:58.048  1018  1018 I MotionRecognitionService: Plugged
03-20 17:23:58.058  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:23:58.048  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:23:58.058  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:23:58.058  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:23:58.058  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:23:58.068  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-20 17:23:58.068  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:23:58.068  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
03-20 17:23:58.068  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:23:58.068  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:23:58.068  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:23:58.068  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:23:58.068  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:23:58.668  1018  1322 E Watchdog: !@Sync 9,
,03-20 17:23:59.998  1018  1097 V AlarmManager: waitForAlarm result :8,
,03-20 17:24:00.488   288   288 E SMD     : DCD OFF
,03-20 17:24:03.488   288   288 E SMD     : DCD OFF,
,03-20 17:24:04.418   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:24:04.628  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-20 17:24:05.418   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:24:06.408   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:24:06.498   288   288 E SMD     : DCD OFF,
,03-20 17:24:07.418   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:24:08.098  1018  1541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-20 17:24:08.098  1018  1541 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
03-20 17:24:08.098  1018  1541 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:24:08.098  1018  1541 D BatteryService: stay LED for charging
,03-20 17:24:08.098  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:24:08.108  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:24:08.098  1018  1018 I MotionRecognitionService: Plugged
03-20 17:24:08.108  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:24:08.098  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:24:08.108  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:24:08.108  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:24:08.118  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:24:08.118  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:24:08.118  1018  2718 D SSRM:n  : SIOP:: AP = 270
,03-20 17:24:08.128  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:24:08.128  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:24:08.128  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:24:08.128  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:24:08.128  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:24:08.418   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:24:09.408   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-20 17:24:09.498   288   288 E SMD     : DCD OFF
,03-20 17:24:12.498   288   288 E SMD     : DCD OFF
,03-20 17:24:12.498  1018  1051 I PowerManagerService: [PWL] Off : 225s ago
,03-20 17:24:15.488   288   288 E SMD     : DCD OFF
,03-20 17:24:18.148  1018  1546 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:24:18.178  1018  2718 D SSRM:n  : SIOP:: AP = 270
,03-20 17:24:18.498   288   288 E SMD     : DCD OFF,
,03-20 17:24:21.508   288   288 E SMD     : DCD OFF
,03-20 17:24:24.508   288   288 E SMD     : DCD OFF,
,03-20 17:24:24.628  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-20 17:24:26.428  1018  1088 D TimaService: TIMA: TimaService scheduler is intialized. ,
03-20 17:24:26.428  1018  1088 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
03-20 17:24:26.428  1018  1087 D TimaService: TimaServiceHandler.handleMessage what =1
,03-20 17:24:26.428  1018  1088 I TLC_TIMA_PKM_initialize: initializing...,
03-20 17:24:26.428  1018  1088 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
03-20 17:24:26.428  1018  1088 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
03-20 17:24:26.428  1018  1088 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
03-20 17:24:26.428  1018  1088 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8,
03-20 17:24:26.428  1018  1088 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
03-20 17:24:26.428  1018  1088 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
03-20 17:24:26.438  1018  1088 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
03-20 17:24:26.438  1018  1088 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
03-20 17:24:26.438  1018  1088 D QSEECOMAPI: : App is not loaded in QSEE
,03-20 17:24:26.458  1018  1088 D QSEECOMAPI: : Loaded image: APP id = 9
,03-20 17:24:26.458  1018  1088 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded,
,03-20 17:24:26.468  1018  1088 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,03-20 17:24:27.498   288   288 E SMD     : DCD OFF
,03-20 17:24:28.198  1018  2718 D SSRM:n  : SIOP:: AP = 270
,03-20 17:24:28.198  1018  1541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:24:28.208  1018  1541 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:24:28.208  1018  1541 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-20 17:24:28.208  1018  1541 D BatteryService: stay LED for charging
03-20 17:24:28.208  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:24:28.208  1018  1018 I MotionRecognitionService: Plugged,
03-20 17:24:28.208  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
03-20 17:24:28.208  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:24:28.208  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:24:28.218  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:24:28.218  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:24:28.228  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:24:28.228  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:24:28.238  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:24:28.238  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:24:28.238  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:24:28.238  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:24:28.238  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:24:28.448  1018  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-20 17:24:28.448  1018  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-20 17:24:28.448  1018  1088 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-20 17:24:28.448  1018  1088 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-20 17:24:28.668  1018  1322 E Watchdog: !@Sync 10
,03-20 17:24:30.508   288   288 E SMD     : DCD OFF
,03-20 17:24:33.508   288   288 E SMD     : DCD OFF,
,03-20 17:24:34.418   318   318 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
03-20 17:24:34.418   318   318 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-20 17:24:36.508   288   288 E SMD     : DCD OFF,
,03-20 17:24:38.248  1018  2718 D SSRM:n  : SIOP:: AP = 270
,03-20 17:24:38.268  1018  1758 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-20 17:24:38.268  1018  1758 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:24:38.268  1018  1758 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
03-20 17:24:38.268  1018  1758 D BatteryService: stay LED for charging
03-20 17:24:38.268  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:24:38.268  1018  1018 I MotionRecognitionService: Plugged,
03-20 17:24:38.268  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:24:38.278  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:24:38.278  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:24:38.278  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:24:38.278  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:24:38.288  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:24:38.288  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:24:38.298  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:24:38.298  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:24:38.298  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:24:38.298  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:24:38.298  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:24:39.518   288   288 E SMD     : DCD OFF,
,03-20 17:24:42.518   288   288 E SMD     : DCD OFF,
,03-20 17:24:44.628  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-20 17:24:45.518   288   288 E SMD     : DCD OFF,
,03-20 17:24:48.288  1018  2718 D SSRM:n  : SIOP:: AP = 270
,03-20 17:24:48.318  1018  1542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-20 17:24:48.518   288   288 E SMD     : DCD OFF,
,03-20 17:24:49.418   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:24:50.408   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:24:51.408   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:24:51.518   288   288 E SMD     : DCD OFF,
,03-20 17:24:52.418   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:24:53.418   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:24:54.408   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,03-20 17:24:54.528   288   288 E SMD     : DCD OFF,
,03-20 17:24:57.518   288   288 E SMD     : DCD OFF,
,03-20 17:24:58.328  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:24:58.378  1018  1758 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-20 17:24:58.668  1018  1322 E Watchdog: !@Sync 11
,03-20 17:24:59.418   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:25:00.418   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:25:00.528   288   288 E SMD     : DCD OFF,
,03-20 17:25:01.418   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:25:02.418   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:25:02.528  1018  1051 I PowerManagerService: [PWL] Off : 275s ago,
,03-20 17:25:03.428   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:25:03.528   288   288 E SMD     : DCD OFF,
,03-20 17:25:04.428   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,03-20 17:25:04.628  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-20 17:25:06.528   288   288 E SMD     : DCD OFF
,03-20 17:25:08.388  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:25:08.438  1018  1542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:25:08.438  1018  1542 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4295, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:25:08.438  1018  1542 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-20 17:25:08.438  1018  1542 D BatteryService: stay LED for charging
03-20 17:25:08.438  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:25:08.438  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:25:08.448  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-20 17:25:08.448  1018  1018 I MotionRecognitionService: Plugged
03-20 17:25:08.448  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:25:08.448  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:25:08.448  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-20 17:25:08.458  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:25:08.458  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:25:08.478  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:25:08.478  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:25:08.478  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:25:08.478  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:25:08.478  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:25:09.538   288   288 E SMD     : DCD OFF,
,03-20 17:25:12.528   288   288 E SMD     : DCD OFF,
,03-20 17:25:14.428   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:25:15.418   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:25:15.538   288   288 E SMD     : DCD OFF,
,03-20 17:25:16.418   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:25:17.418   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:25:18.418   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:25:18.428  1018  2718 D SSRM:n  : SIOP:: AP = 270,
,03-20 17:25:18.488  1018  1546 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:25:18.488  1018  1546 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:25:18.488  1018  1546 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:25:18.488  1018  1546 D BatteryService: stay LED for charging
,03-20 17:25:18.488  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:25:18.498  1018  1018 I MotionRecognitionService: Plugged
03-20 17:25:18.498  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:25:18.498  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:25:18.498  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:25:18.498  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:25:18.498  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:25:18.508  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:25:18.508  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:25:18.518  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:25:18.518  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:25:18.528  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:25:18.528  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:25:18.528  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:25:18.528   288   288 E SMD     : DCD OFF,
,03-20 17:25:19.428   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-20 17:25:21.538   288   288 E SMD     : DCD OFF,
,03-20 17:25:24.538   288   288 E SMD     : DCD OFF,
,03-20 17:25:24.618  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-20 17:25:27.538   288   288 E SMD     : DCD OFF
,03-20 17:25:28.468  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:25:28.538  1018  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:25:28.658  1018  1322 E Watchdog: !@Sync 12
,03-20 17:25:30.538   288   288 E SMD     : DCD OFF
,03-20 17:25:33.538   288   288 E SMD     : DCD OFF,
,03-20 17:25:34.428   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:25:35.428   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:25:36.418   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:25:36.538   288   288 E SMD     : DCD OFF,
,03-20 17:25:37.428   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:25:38.428   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:25:38.518  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:25:38.588  1018  1758 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:25:39.428   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-20 17:25:39.538   288   288 E SMD     : DCD OFF,
,03-20 17:25:42.538   288   288 E SMD     : DCD OFF,
,03-20 17:25:44.618  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-20 17:25:45.558   288   288 E SMD     : DCD OFF,
,03-20 17:25:48.558   288   288 E SMD     : DCD OFF,
,03-20 17:25:48.558  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:25:48.638  1018  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:25:51.558   288   288 E SMD     : DCD OFF,
,03-20 17:25:54.558   288   288 E SMD     : DCD OFF,
,03-20 17:25:57.548  1018  1051 I PowerManagerService: [PWL] Off : 330s ago
,03-20 17:25:57.548   288   288 E SMD     : DCD OFF,
,03-20 17:25:58.598  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:25:58.668  1018  1322 E Watchdog: !@Sync 13
,03-20 17:25:58.688  1018  1545 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:25:59.438   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:26:00.428   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:26:00.568   288   288 E SMD     : DCD OFF,
,03-20 17:26:01.438   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:26:02.428   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:26:03.428   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:26:03.568   288   288 E SMD     : DCD OFF,
,03-20 17:26:04.438   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,03-20 17:26:04.628  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-20 17:26:06.558   288   288 E SMD     : DCD OFF
,03-20 17:26:08.648  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:26:08.738  1018  1345 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:26:08.738  1018  1345 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4295, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:26:08.738  1018  1345 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:26:08.738  1018  1345 D BatteryService: stay LED for charging
03-20 17:26:08.738  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:26:08.748  1018  1018 I MotionRecognitionService: Plugged
03-20 17:26:08.748  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:26:08.748  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:26:08.748  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:26:08.748  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:26:08.758  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:26:08.768  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:26:08.768  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:26:08.788  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:26:08.788  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:26:08.788  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:26:08.788  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:26:08.788  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:26:09.558   288   288 E SMD     : DCD OFF,
,03-20 17:26:12.568   288   288 E SMD     : DCD OFF,
,03-20 17:26:15.578   288   288 E SMD     : DCD OFF,
,03-20 17:26:18.578   288   288 E SMD     : DCD OFF,
,03-20 17:26:18.688  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:26:18.798  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:26:18.798  1018  1031 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:26:18.798  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:26:18.798  1018  1031 D BatteryService: stay LED for charging
03-20 17:26:18.798  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:26:18.798  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:26:18.798  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:26:18.798  1018  1018 I MotionRecognitionService: Plugged
03-20 17:26:18.798  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:26:18.798  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:26:18.798  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-20 17:26:18.818  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:26:18.818  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:26:18.828  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:26:18.828  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:26:18.828  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:26:18.828  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:26:18.828  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:26:21.578   288   288 E SMD     : DCD OFF,
,03-20 17:26:24.578   288   288 E SMD     : DCD OFF,
,03-20 17:26:24.618  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-20 17:26:27.578   288   288 E SMD     : DCD OFF,
,03-20 17:26:28.668  1018  1322 E Watchdog: !@Sync 14,
,03-20 17:26:28.738  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:26:28.848  1018  1079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:26:29.438   318   318 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
03-20 17:26:29.438   318   318 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-20 17:26:30.588   288   288 E SMD     : DCD OFF,
,03-20 17:26:33.588   288   288 E SMD     : DCD OFF,
,03-20 17:26:36.588   288   288 E SMD     : DCD OFF
,03-20 17:26:38.788  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:26:38.898  1018  3044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:26:38.898  1018  3044 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4293, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:26:38.898  1018  3044 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-20 17:26:38.898  1018  3044 D BatteryService: stay LED for charging
03-20 17:26:38.898  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:26:38.898  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:26:38.898  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:26:38.908  1018  1018 I MotionRecognitionService: Plugged,
03-20 17:26:38.908  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:26:38.908  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:26:38.908  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:26:38.918  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:26:38.918  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:26:38.928  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:26:38.928  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:26:38.928  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:26:38.928  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:26:38.928  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:26:39.588   288   288 E SMD     : DCD OFF,
,03-20 17:26:42.588   288   288 E SMD     : DCD OFF,
,03-20 17:26:44.628  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-20 17:26:45.598   288   288 E SMD     : DCD OFF,
,03-20 17:26:48.598   288   288 E SMD     : DCD OFF,
,03-20 17:26:48.838  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:26:48.948  1018  1079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:26:48.948  1018  1079 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
03-20 17:26:48.948  1018  1079 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:26:48.948  1018  1079 D BatteryService: stay LED for charging
03-20 17:26:48.948  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:26:48.948  1018  1018 I MotionRecognitionService: Plugged
03-20 17:26:48.948  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:26:48.948  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:26:48.948  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:26:48.958  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:26:48.958  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:26:48.968  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:26:48.968  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:26:48.988  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:26:48.988  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:26:48.988  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:26:48.988  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:26:48.988  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:26:49.438   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:26:50.428   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:26:51.428   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:26:51.598   288   288 E SMD     : DCD OFF,
,03-20 17:26:52.438   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:26:53.438   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:26:54.438   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,03-20 17:26:54.598   288   288 E SMD     : DCD OFF
,03-20 17:26:57.558  1018  1051 I PowerManagerService: [PWL] Off : 390s ago,
,03-20 17:26:57.598   288   288 E SMD     : DCD OFF
,03-20 17:26:58.678  1018  1322 E Watchdog: !@Sync 15,
,03-20 17:26:58.888  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:26:58.998  1018  1545 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:26:58.998  1018  1545 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4295, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:26:58.998  1018  1545 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:26:58.998  1018  1545 D BatteryService: stay LED for charging
03-20 17:26:58.998  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:26:58.998  1018  1018 I MotionRecognitionService: Plugged
03-20 17:26:58.998  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:26:58.998  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:26:58.998  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:26:59.008  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:26:59.008  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:26:59.018  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-20 17:26:59.018  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:26:59.038  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:26:59.038  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:26:59.038  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:26:59.038  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:26:59.038  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:26:59.438   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:26:59.998  1018  1097 V AlarmManager: waitForAlarm result :8
,03-20 17:26:59.998  1018  1097 V AlarmManager: No more alarm at this time.nowELAPSED=468843 batch.start=515526
,03-20 17:27:00.438   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:27:00.608   288   288 E SMD     : DCD OFF,
,03-20 17:27:01.448   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:27:02.438   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:27:03.438   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:27:03.608   288   288 E SMD     : DCD OFF
,03-20 17:27:04.448   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,03-20 17:27:04.628  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-20 17:27:06.608   288   288 E SMD     : DCD OFF,
,03-20 17:27:08.928  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:27:09.048  1018  3043 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:27:09.608   288   288 E SMD     : DCD OFF
,03-20 17:27:12.608   288   288 E SMD     : DCD OFF
,03-20 17:27:14.448   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:27:15.438   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:27:15.608   288   288 E SMD     : DCD OFF
,03-20 17:27:16.448   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:27:17.438   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:27:17.598   315   315 I bootchecker: bootchecker wake up!!
,03-20 17:27:18.448   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:27:18.618   288   288 E SMD     : DCD OFF,
,03-20 17:27:18.968  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:27:19.098  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:27:19.448   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-20 17:27:21.618   288   288 E SMD     : DCD OFF,
,03-20 17:27:24.618   288   288 E SMD     : DCD OFF,
,03-20 17:27:24.638  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-20 17:27:27.618   288   288 E SMD     : DCD OFF,
,03-20 17:27:28.678  1018  1322 E Watchdog: !@Sync 16,
,03-20 17:27:29.018  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:27:29.148  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-20 17:27:30.618   288   288 E SMD     : DCD OFF,
,03-20 17:27:33.618   288   288 E SMD     : DCD OFF,
,03-20 17:27:34.448   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:27:35.448   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:27:36.448   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:27:36.628   288   288 E SMD     : DCD OFF
,03-20 17:27:37.458   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:27:38.448   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:27:39.068  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:27:39.198  1018  1542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:27:39.458   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-20 17:27:39.628   288   288 E SMD     : DCD OFF
,03-20 17:27:42.628   288   288 E SMD     : DCD OFF
,03-20 17:27:44.638  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-20 17:27:45.628   288   288 E SMD     : DCD OFF
,03-20 17:27:46.678  1018  1097 V AlarmManager: waitForAlarm result :4
,03-20 17:27:46.678  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-20 17:27:46.678  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,03-20 17:27:46.698  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-20 17:27:46.698  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,03-20 17:27:46.698  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:27:46.698  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-20 17:27:46.698  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
,03-20 17:27:46.718  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:27:46.718  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:27:46.728  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:27:46.748  1178  1178 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-20 17:27:46.768  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:27:46.838  1634  3815 D GCM     : Message class com.google.e.a.a.h
,03-20 17:27:48.628   288   288 E SMD     : DCD OFF
,03-20 17:27:49.108  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:27:49.248  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:27:51.628   288   288 E SMD     : DCD OFF
,03-20 17:27:54.638   288   288 E SMD     : DCD OFF
,03-20 17:27:57.638   288   288 E SMD     : DCD OFF
,03-20 17:27:58.678  1018  1322 E Watchdog: !@Sync 17,
,03-20 17:27:59.158  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:27:59.298  1018  1542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:27:59.298  1018  1542 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4293, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:27:59.298  1018  1542 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:27:59.298  1018  1542 D BatteryService: stay LED for charging
03-20 17:27:59.298  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:27:59.298  1018  1018 I MotionRecognitionService: Plugged
03-20 17:27:59.298  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:27:59.308  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:27:59.308  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:27:59.308  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:27:59.308  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:27:59.318  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-20 17:27:59.318  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:27:59.328  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:27:59.328  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:27:59.328  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:27:59.328  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:27:59.328  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:27:59.458   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:27:59.998  1018  1097 V AlarmManager: waitForAlarm result :8,
,03-20 17:28:00.458   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:28:00.638   288   288 E SMD     : DCD OFF,
,03-20 17:28:01.458   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:28:02.448   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-20 17:28:02.558  1018  1051 I PowerManagerService: [PWL] Off : 455s ago,
,03-20 17:28:03.458   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 17:28:03.638   288   288 E SMD     : DCD OFF
,03-20 17:28:04.458   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-20 17:28:04.638  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-20 17:28:06.638   288   288 E SMD     : DCD OFF
,03-20 17:28:09.208  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:28:09.348  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:28:09.348  1018  1501 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4291, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
03-20 17:28:09.348  1018  1501 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:28:09.348  1018  1501 D BatteryService: stay LED for charging
03-20 17:28:09.348  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:28:09.358  1018  1018 I MotionRecognitionService: Plugged
03-20 17:28:09.358  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:28:09.358  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:28:09.358  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:28:09.358  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:28:09.358  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:28:09.368  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-20 17:28:09.368  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:28:09.388  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:28:09.388  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:28:09.388  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:28:09.388  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:28:09.388  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:28:09.638   288   288 E SMD     : DCD OFF,
,03-20 17:28:12.648   288   288 E SMD     : DCD OFF,
,03-20 17:28:15.648   288   288 E SMD     : DCD OFF,
,03-20 17:28:18.648   288   288 E SMD     : DCD OFF,
,03-20 17:28:19.258  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:28:19.408  1018  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:28:19.408  1018  1487 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4310, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:28:19.408  1018  1487 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:28:19.408  1018  1487 D BatteryService: stay LED for charging
03-20 17:28:19.408  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:28:19.408  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:28:19.408  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:28:19.408  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:28:19.418  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-20 17:28:19.418  1018  1018 I MotionRecognitionService: Plugged
03-20 17:28:19.418  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:28:19.428  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:28:19.428  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:28:19.438  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:28:19.438  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:28:19.438  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:28:19.438  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:28:19.438  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:28:21.648   288   288 E SMD     : DCD OFF,
,03-20 17:28:24.638  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-20 17:28:24.648   288   288 E SMD     : DCD OFF,
,03-20 17:28:27.658   288   288 E SMD     : DCD OFF,
,03-20 17:28:28.678  1018  1322 E Watchdog: !@Sync 18,
,03-20 17:28:29.308  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:28:29.448   318   318 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
03-20 17:28:29.448   318   318 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-20 17:28:29.458  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:28:29.458  1018  1030 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4312, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-20 17:28:29.458  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:28:29.458  1018  1030 D BatteryService: stay LED for charging
03-20 17:28:29.458  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:28:29.458  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:28:29.458  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:28:29.468  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:28:29.468  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:28:29.468  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:28:29.468  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:28:29.478  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:28:29.478  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:28:29.498  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:28:29.498  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-20 17:28:29.498  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 17:28:29.498  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:28:29.498  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:28:30.658   288   288 E SMD     : DCD OFF,
,03-20 17:28:33.658   288   288 E SMD     : DCD OFF,
,03-20 17:28:36.658   288   288 E SMD     : DCD OFF,
,03-20 17:28:39.358  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:28:39.498  1018  3044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:28:39.508  1018  1078 E lights  : write_int failed to open -1
03-20 17:28:39.498  1018  3044 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4312, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:28:39.498  1018  3044 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-20 17:28:39.498  1018  3044 D LightsService: [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
03-20 17:28:39.508  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:28:39.508  1018  3044 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
03-20 17:28:39.508  1018  3044 D BatteryService: turn on LED for fully charged
03-20 17:28:39.508  1018  1078 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,03-20 17:28:39.508  1018  1078 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
03-20 17:28:39.508  1018  1018 I MotionRecognitionService: Plugged
03-20 17:28:39.508  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:28:39.508  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:28:39.508  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:28:39.508  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:28:39.508  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:28:39.518  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:28:39.518  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:28:39.518  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:28:39.528  1018  1351 D SecContentProvider2: uri = 14 selection = getSealedState
,03-20 17:28:39.528  1018  1351 D SecContentProvider2: mCursor = null
,03-20 17:28:39.538  1018  1223 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,03-20 17:28:39.538  1018  1223 V ApplicationPolicy: isApplicationStateBlocked userId -1 pkgname com.android.systemui
,03-20 17:28:39.538  1018  1018 I ValidateNoPeople: skipping global notification
,03-20 17:28:39.538  1018  1018 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
,03-20 17:28:39.548  1018  1545 D PowerManagerService: [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1178
,03-20 17:28:39.548  1018  1545 I PowerManagerService: !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
03-20 17:28:39.548  1018  1545 I PowerManagerService: Waking up from sleep (uid 10049)...
,03-20 17:28:39.548  1018  1545 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,03-20 17:28:39.548  1018  1154 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@130210d6)
,03-20 17:28:39.548  1178  2405 D KeyguardViewMediator: onScreenTurnedOn, seq = 2
,03-20 17:28:39.548  1178  2405 D KeyguardViewMediator: notifyScreenOnLocked
,03-20 17:28:39.558  1018  1545 D PowerManagerService: [s] UserActivityState : 0 -> 1
,03-20 17:28:39.558  1018  1545 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
03-20 17:28:39.558  1018  1047 D WindowOrientationListener: sensor enabled
03-20 17:28:39.558  1018  1051 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
03-20 17:28:39.558  1018  1047 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-20 17:28:39.558  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:28:39.558  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:28:39.558  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:28:39.558  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:28:39.558  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:28:39.568  1018  1056 I libsuspend: !@autosuspend_wakeup_count_disable
03-20 17:28:39.568  1018  1051 D DisplayPowerController: getFinalBrightness : Summary is 255 -> 255
03-20 17:28:39.568  1018  1056 I libsuspend: !@autosuspend_wakeup_count_disable done
03-20 17:28:39.568  1018  1051 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-20 17:28:39.568  1018  1051 D DisplayPowerController: getFinalBrightness : Summary is 255 -> 255
03-20 17:28:39.568  1018  1051 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-20 17:28:39.568  1018  1056 D DisplayManagerService: !@display_state: OFF -> ON
03-20 17:28:39.568  1018  1047 D SensorService: [SO] changed settle time [1]
03-20 17:28:39.568  1018  1047 D SensorService: [SO] setDelay [66000000]
03-20 17:28:39.568  1018  1047 D SensorService: [SO] activate (ident=0xb9441a70, enabled=1)
03-20 17:28:39.568  1018  1047 D SensorService: [SO] AR_init
03-20 17:28:39.568  1018  1047 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-20 17:28:39.568   257   257 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6fbe690
03-20 17:28:39.568   257   257 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
,03-20 17:28:39.568   257   257 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
,03-20 17:28:39.568   257   257 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
,03-20 17:28:39.578  1018  1047 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
03-20 17:28:39.578  1018  1049 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 540 x 960, 60.0 fps, supportedRefreshRates [60.0], density 240, 244.928 x 243.839 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-20 17:28:39.578  1018  1018 V ActivityManager: Display changed displayId=0
,03-20 17:28:39.608  1018  1154 D PersonaManager: isKioskContainerExistOnDevice
,03-20 17:28:39.618  1178  1178 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,03-20 17:28:39.618  1018  1018 I PalmMotion: [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
03-20 17:28:39.618  1018  1018 I PalmMotion: [PALM] SURFACE_PALM_SWIPE: 1
03-20 17:28:39.618  1018  1018 D PalmMotion: [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
03-20 17:28:39.618  1018  1018 E MotionRecognitionService:   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
03-20 17:28:39.618  1018  1018 D PalmMotion: [PALM] ACCEPTED : [a3ulte_common] PALM_CNT : 2, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
03-20 17:28:39.618  1018  1018 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
,03-20 17:28:39.628  1018  1018 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
03-20 17:28:39.628  1018  1078 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
03-20 17:28:39.628  1018  1078 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,03-20 17:28:39.628  1178  1178 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,03-20 17:28:39.628  1178  1178 D PersonaManager: PersonaID is invalid or persona doesn't exists. : -1
,03-20 17:28:39.638  1018  3044 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-20 17:28:39.638  1178  1178 D PersonaManager: isKioskContainerExistOnDevice
03-20 17:28:39.638  1178  1178 D PersonaManager: isKioskContainerExistOnDevice
03-20 17:28:39.638  1178  1178 I PhoneStatusBar: Icon Only
03-20 17:28:39.638  1178  1178 I StatusBar: Icon Only
,03-20 17:28:39.638  1178  1178 D PanelView: There is/are notification(s) 
03-20 17:28:39.638  1178  1178 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-20 17:28:39.638  1178  1178 D PersonaManager: isKioskContainerExistOnDevice
03-20 17:28:39.638  1178  1178 I PhoneStatusBar: Icon Only
03-20 17:28:39.638  1178  1178 I StatusBar: Icon Only
,03-20 17:28:39.638  1178  1178 D PanelView: There is/are notification(s) 
03-20 17:28:39.638  1178  1178 D PanelView: kidsfalse mQsExpansionEnabled:true
03-20 17:28:39.638  1178  1178 D KeyguardViewMediator: handleNotifyScreenOn
03-20 17:28:39.638  1178  1178 D StatusBarKeyguardViewManager: onScreenTurnedOn()
,03-20 17:28:39.648  1018  2718 D SSRM:a  : DeviceInfo:: 000000000000
,03-20 17:28:39.648  1018  2718 D SSRM:a  : SettingsAirViewInfo:: 000000000
03-20 17:28:39.648  1178  1178 D SecKeyguardClockSingleView: onScreenTurnedOn
03-20 17:28:39.648  1815  1815 D SamsungIME: showDlgMsgBox : false true true
03-20 17:28:39.648  1018  1041 D SensorService: [SO] currT = 568502341000, prevT = 75504850000, diff = 492997491000, [-0.345 0.096 9.941]
03-20 17:28:39.648  1018  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
03-20 17:28:39.648  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:28:39.648  1445  1685 D NfcService: call the applyRouting
03-20 17:28:39.648  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
03-20 17:28:39.648  1018  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-20 17:28:39.648  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-20 17:28:39.648  1018  1351 D ActivityManager: post active user change for 0 fullscreen false record.isFloatingActivity() false
,03-20 17:28:39.648  1018  1351 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-20 17:28:39.648  1018  1351 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-20 17:28:39.648   288   288 E SMD     : DCD OFF
,03-20 17:28:39.658  1178  1178 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte level=4
03-20 17:28:39.658  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
03-20 17:28:39.658  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
03-20 17:28:39.658  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,03-20 17:28:39.658  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-20 17:28:39.658  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
03-20 17:28:39.658  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 17:28:39.658  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 17:28:39.658  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 17:28:39.658  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 17:28:39.658  1178  1178 D StatusBarKeyguardViewManager: callback.onShown()
03-20 17:28:39.658  1018  1079 V KeyguardServiceDelegate: **** SHOWN CALLED ****
03-20 17:28:39.658  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-20 17:28:39.658  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
03-20 17:28:39.658  1018  1018 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
03-20 17:28:39.658  1018  1047 D DisplayPowerController: [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
03-20 17:28:39.658  1018  1051 I DisplayPowerController: Unblocked screen on after 103 ms
03-20 17:28:39.658  1018  1051 D DisplayPowerState: !@ ColorFade exit
,03-20 17:28:39.668   257   451 I SurfaceFlinger: id=12 Removed DolorFade (9/9),
,03-20 17:28:39.668   257  1040 I SurfaceFlinger: id=12 Removed DolorFade (-2/9)
,03-20 17:28:39.668  1018  1051 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
03-20 17:28:39.668  1018  1051 D DisplayPowerController: getFinalBrightness : Summary is 255 -> 255
,03-20 17:28:39.668  1018  1158 D lights  : lcd : 255 +
03-20 17:28:39.668  1018  1051 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-20 17:28:39.668  1018  1158 D lights  : lcd : 255 -
03-20 17:28:39.668  1018  1051 D DisplayPowerController: getFinalBrightness : Summary is 255 -> 255
03-20 17:28:39.668  1018  1758 W ActivityManager: userId = 0, bbcId = -10000
03-20 17:28:39.668  1018  1051 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-20 17:28:39.668  1018  1758 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-20 17:28:39.668  1018  1051 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
03-20 17:28:39.668  1018  1758 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
03-20 17:28:39.668  1018  1051 D PowerManagerService: SecHardwareInterface.setBatteryADC : true
,03-20 17:28:39.668  5449  5449 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@97d8d00 time:568527
,03-20 17:28:39.668  1871  1871 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,03-20 17:28:39.678  1018  1018 D LightsService: [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1018) 
,03-20 17:28:39.678  1018  1018 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
03-20 17:28:39.678  1018  1018 D BatteryService: turn off LED
03-20 17:28:39.678  1018  1078 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
03-20 17:28:39.678  1018  1078 E lights  : write_led_info failed to open -1
03-20 17:28:39.678  1018  1078 E lights  : write_led_info failed to open -1
03-20 17:28:39.678  1018  1078 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
03-20 17:28:39.678  1018  1078 E lights  : write_led_info failed to open -1
03-20 17:28:39.678  1018  1078 E lights  : write_led_info failed to open -1
03-20 17:28:39.678  1018  1078 E lights  : write_led_info failed to open -1
03-20 17:28:39.678  1018  1078 E lights  : write_led_info failed to open -1
03-20 17:28:39.678  1018  1078 E lights  : write_led_info failed to open -1
03-20 17:28:39.678  1018  1078 E lights  : write_led_info failed to open -1
03-20 17:28:39.678  1018  1078 E lights  : write_led_info failed to open -1
,03-20 17:28:39.688  1018  1093 E SmartFaceService: onReceive: android.intent.action.SCREEN_ON
,03-20 17:28:39.688  1018  1093 W System.err: java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
03-20 17:28:39.688  1018  1093 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-20 17:28:39.688  1018  1093 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-20 17:28:39.688  1018  1093 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-20 17:28:39.688  1018  1093 W System.err: 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
03-20 17:28:39.688  1018  1093 W System.err: 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
03-20 17:28:39.688  1018  1093 W System.err: 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
03-20 17:28:39.688  1018  1093 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
03-20 17:28:39.688  1018  1093 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-20 17:28:39.688  1018  1093 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-20 17:28:39.688  1018  1093 E SmartFaceService: fail to set sysfs 1
03-20 17:28:39.688  1018  1093 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:28:39.688  1018  1093 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:28:39.688  1018  1093 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
03-20 17:28:39.688  1018  1093 W System.err: 	at libcore.io.Posix.open(Native Method)
03-20 17:28:39.688  1018  1093 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-20 17:28:39.688  1018  1093 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-20 17:28:39.688  1018  1093 W System.err: 	... 10 more
,03-20 17:28:39.688  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-20 17:28:39.688  1445  1685 D SecNfcJni: RoutingManager::commitRouting
03-20 17:28:39.688  1445  2208 D SecNfcJni: RoutingManager::nfaEeCallback: NFA_EE_UPDATED_EVT
03-20 17:28:39.688  1178  1178 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte level=4
03-20 17:28:39.688  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
03-20 17:28:39.688  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
03-20 17:28:39.688  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,03-20 17:28:39.688  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-20 17:28:39.688  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
03-20 17:28:39.688  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 17:28:39.688  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 17:28:39.688  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 17:28:39.688  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 17:28:39.688  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-20 17:28:39.688  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-20 17:28:39.688  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 17:28:39.698  1178  1178 D BatteryMeterView: onDraw batteryColor : -1
,03-20 17:28:39.698  1445  1685 D NfcService: index : 0
03-20 17:28:39.698  1445  1685 D NfcService: index : 1
03-20 17:28:39.698  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,03-20 17:28:39.708  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-20 17:28:39.708  1018  1351 W ActivityManager: userId = 0, bbcId = -10000
03-20 17:28:39.708  1018  1351 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 17:28:39.708  1018  1351 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,03-20 17:28:39.708  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,03-20 17:28:39.718  1018  1041 D SensorService: [SO] currT = 568571052000, prevT = 75504850000, diff = 493066202000, [-0.345 0.077 9.902]
03-20 17:28:39.718  1018  1041 D SensorService: [SO] -0.345 0.077 9.902
03-20 17:28:39.718  1018  1041 D SensorService: [SO] [100 -> 255]
,03-20 17:28:39.718  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:28:39.718  1018  1018 D InputMethodManagerService: [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,03-20 17:28:39.718  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-20 17:28:39.718  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
03-20 17:28:39.718  1178  1178 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
03-20 17:28:39.718  1178  1178 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-20 17:28:39.728  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
,03-20 17:28:39.728  1018  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-20 17:28:39.728  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 17:28:39.738  1018  1018 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
,03-20 17:28:39.738  1018  1105 E MotionRecognitionService:  handler : SCREEN_ON end
,03-20 17:28:39.748  1178  1178 I StatusBar: Icon Only
,03-20 17:28:39.748  1178  1178 D PanelView: There is/are notification(s) 
,03-20 17:28:39.748  1018  1018 D NotificationService: ACTION_SCREEN_ON
03-20 17:28:39.748  1018  1018 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
03-20 17:28:39.748  1018  1018 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
03-20 17:28:39.758  1018  1078 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
03-20 17:28:39.758  1018  1078 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,03-20 17:28:39.758   283  1014 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,03-20 17:28:39.758   283  1014 V voice   : voice_set_parameters: enter: screen_state=on
03-20 17:28:39.758   283  1014 V voice   : voice_set_parameters: exit with code(-2)
03-20 17:28:39.758   283  1014 V msm8974_platform: platform_set_parameters: enter: screen_state=on
03-20 17:28:39.758   283  1014 V msm8974_platform: platform_set_parameters: exit with code(-2)
03-20 17:28:39.758   283  1014 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
03-20 17:28:39.758   283  1014 V audio_hw_primary: adev_set_parameters: exit
03-20 17:28:39.758  1018  1126 E WifiNative-wlan0: do suspend false
,03-20 17:28:39.768  1018  1049 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
,03-20 17:28:39.768  1018  1049 D IpRemoteDisplayController: Bridge Server is not available
,03-20 17:28:39.768  1018  1043 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,03-20 17:28:39.768  1018  1018 D PersonaManagerService: ACTION_SCREEN_ON onReceive,
03-20 17:28:39.778  1018  1063 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
,03-20 17:28:39.778  1018  1541 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-20 17:28:39.778  1445  1445 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,03-20 17:28:39.788   257   257 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,03-20 17:28:39.788  1018  1056 D SurfaceControl: Excessive delay in setPowerMode(): 221ms
03-20 17:28:39.788   257   530 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,03-20 17:28:39.788   257   530 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
03-20 17:28:39.788  1018  1056 D PowerManagerService: Excessive delay in !@display_state: ON: 222ms
03-20 17:28:39.788   257   530 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
,03-20 17:28:39.788  1384  1384 I wpa_supplicant: reset timer : RESET_TIMER 1
03-20 17:28:39.788  1384  1384 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
03-20 17:28:39.788  1384  1384 I wpa_supplicant: P2P: Current p2p state = IDLE
,03-20 17:28:39.788  1384  1384 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,03-20 17:28:39.788  1018  5976 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 1
,03-20 17:28:39.788  1018  5977 D MISC PowerHAL: sysfs_write +: /sys/class/input/event3/device/enabled: 1
03-20 17:28:39.788  1445  2300 D NfcService: call the applyRouting
,03-20 17:28:39.798  1445  2300 D NfcService: Discovery configuration equal, not updating.
03-20 17:28:39.798  1445  2300 D NfcService: index : 0
03-20 17:28:39.798  1445  2300 D NfcService: index : 1
,03-20 17:28:39.818  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_ON
,03-20 17:28:39.818  1741  1741 D accuweather: [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
03-20 17:28:39.818  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,03-20 17:28:39.818  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,03-20 17:28:39.828  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,03-20 17:28:39.828  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,03-20 17:28:39.828  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,03-20 17:28:39.828  1741  1741 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
03-20 17:28:39.828  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
,03-20 17:28:39.828  1741  1741 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
03-20 17:28:39.828  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,03-20 17:28:39.828  1741  1741 E accuweather: [KK AccuPhone]>>> UIM:1488 [0:0] bTM 17 28
,03-20 17:28:39.828  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:28:39.838  1018  1223 W ActivityManager: userId = 0, bbcId = -10000
,03-20 17:28:39.838  1018  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 17:28:39.838  1018  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,03-20 17:28:39.848  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:28:39.848  1815  1815 I SamsungIME: getNextShiftState() cursorCapsMode : 0
,03-20 17:28:39.858  1741  1741 D accuweather: [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionNETWORK_SET_TIMEZONE
03-20 17:28:39.858  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,03-20 17:28:39.858  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,03-20 17:28:39.858  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,03-20 17:28:39.868  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:28:39.868  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,03-20 17:28:39.868  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
03-20 17:28:39.868  1018  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-20 17:28:39.868  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-20 17:28:39.868  1741  1741 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
03-20 17:28:39.868  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
,03-20 17:28:39.868  1741  1741 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
03-20 17:28:39.868  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,03-20 17:28:39.868  1741  1741 E accuweather: [KK AccuPhone]>>> UIM:1488 [0:0] bTM 17 28
,03-20 17:28:39.898  1018  1154 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,03-20 17:28:39.898  1018  5977 D MISC PowerHAL: sysfs_write -: /sys/class/input/event3/device/enabled: 1
,03-20 17:28:39.898  1018  2718 D SSRM:n  : SIOP:: AP = 290
,03-20 17:28:39.908  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-20 17:28:39.908  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
03-20 17:28:39.908  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 17:28:39.908  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 17:28:39.908  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 17:28:39.908  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 17:28:39.918  1773  1773 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-20 17:28:39.918  1773  1773 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-20 17:28:39.918  1773  1773 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-20 17:28:39.918  1773  1773 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-20 17:28:39.918  1178  1178 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-20 17:28:39.928  1773  1773 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-20 17:28:39.928  1773  1773 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,03-20 17:28:39.928  1773  1773 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-20 17:28:39.928  1773  1773 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-20 17:28:39.928  1773  1773 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,03-20 17:28:39.928  1773  1773 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-20 17:28:39.928  1773  1773 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-20 17:28:39.928  1773  1773 D daemonapp: [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
03-20 17:28:39.928  1773  1773 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-20 17:28:39.938  1773  1773 D daemonapp: [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,03-20 17:28:39.938  1773  1773 D daemonapp: [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1458512340000
,03-20 17:28:39.938  1773  1773 D daemonapp: [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1458491319949
,03-20 17:28:39.938  1773  1773 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-20 17:28:39.938  1773  1773 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-20 17:28:39.948  1018  5976 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 1
,03-20 17:28:39.948  1018  1056 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 1
,03-20 17:28:39.948  1018  1056 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 1
03-20 17:28:39.948  1018  1056 D PowerManagerService-JNI: Excessive delay in MISC setInteractive(true) while turning screen on: 156ms
03-20 17:28:39.948  1018  1056 I QCOM PowerHAL: Got set_interactive hint
,03-20 17:28:39.948  1018  1056 D PowerManagerService: Excessive delay in nativeSetInteractive(true): 159ms
03-20 17:28:39.948  1773  1773 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-20 17:28:39.948  1018  1056 D PowerManagerService: Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 382ms
,03-20 17:28:39.948  1773  1773 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-20 17:28:39.948  1773  1773 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
03-20 17:28:39.948  1018  1155 D lights  : button : 1 +
,03-20 17:28:39.948  1773  1773 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-20 17:28:39.948  1773  1773 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-20 17:28:39.978  1018  1155 D lights  : button : 1 -
,03-20 17:28:39.978  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:28:40.398  1384  1384 I wpa_supplicant: nl80211: Received scan results (12 BSSes)
03-20 17:28:40.398  1018  1125 D WifiP2pService: InactiveState{ what=147461 }
03-20 17:28:40.408  1018  1125 D WifiP2pService: P2pEnabledState{ what=147461 }
03-20 17:28:40.408  1018  1125 D WifiP2pService: DefaultState{ what=147461 }
,03-20 17:28:40.688  1018  2718 D SSRM:a  : DeviceInfo:: 000000000000
,03-20 17:28:40.688  1018  2718 D SSRM:a  : SettingsAirViewInfo:: 000000000
,03-20 17:28:40.778  1018  1041 D SensorService: [SO] -0.345 0.077 9.922
,03-20 17:28:40.908  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-20 17:28:40.908  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
,03-20 17:28:40.908  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 17:28:40.908  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 17:28:40.908  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 17:28:40.918  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 17:28:41.458  1018  1155 D lights  : button : 0 +,
,03-20 17:28:41.478  1018  1155 D lights  : button : 0 -,
,03-20 17:28:42.658   288   288 E SMD     : DCD OFF
,03-20 17:28:44.638  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-20 17:28:45.668   288   288 E SMD     : DCD OFF,
,03-20 17:28:48.668   288   288 E SMD     : DCD OFF,
,03-20 17:28:49.538  1178  1178 D PersonaManager: isKioskContainerExistOnDevice
,03-20 17:28:49.538  1178  1178 D PersonaManager: isKioskContainerExistOnDevice
03-20 17:28:49.538  1178  1178 I PhoneStatusBar: Icon Only
03-20 17:28:49.538  1178  1178 I StatusBar: Icon Only
,03-20 17:28:49.538  1178  1178 D PanelView: There is/are notification(s) 
03-20 17:28:49.538  1178  1178 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-20 17:28:49.618  1178  1178 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-20 17:28:49.688  1018  1079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:28:49.688  1018  1079 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4275, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:28:49.688  1018  1079 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:28:49.688  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:28:49.698  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:28:49.698  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:28:49.698  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:28:49.698  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:28:49.708  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:28:49.708  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:28:49.728  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-20 17:28:49.728  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:28:49.728  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:28:49.728  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:28:49.728  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:28:49.728  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:28:49.728  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:28:49.918  1018  2718 D SSRM:n  : SIOP:: AP = 290
,03-20 17:28:49.958  1384  1384 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,03-20 17:28:51.288  1018  1041 D SensorService: [SO] -0.345 0.096 9.922
,03-20 17:28:51.668   288   288 E SMD     : DCD OFF,
,03-20 17:28:54.018  1384  1384 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-20 17:28:54.458   318   318 I Atfwd_Daemon: Stop the daemon....,
,03-20 17:28:54.668   288   288 E SMD     : DCD OFF,
,03-20 17:28:57.058  1178  1178 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte level=4,
03-20 17:28:57.058  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
03-20 17:28:57.058  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
03-20 17:28:57.058  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
03-20 17:28:57.058  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-20 17:28:57.058  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
03-20 17:28:57.058  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 17:28:57.058  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 17:28:57.058  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 17:28:57.058  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 17:28:57.658   288   288 E SMD     : DCD OFF,
,03-20 17:28:57.988  1384  1384 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-20 17:28:58.668  1018  1322 E Watchdog: !@Sync 19
,03-20 17:28:59.568  1018  1223 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1178 (0x0)
,03-20 17:28:59.668  1384  1384 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-20 17:28:59.748  1018  1545 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:28:59.748  1018  1545 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4272, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:28:59.748  1018  1545 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:28:59.748  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:28:59.748  1018  1018 I MotionRecognitionService: Plugged
03-20 17:28:59.748  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:28:59.748  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:28:59.748  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-20 17:28:59.758  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:28:59.758  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:28:59.768  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-20 17:28:59.768  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:28:59.778  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:28:59.778  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:28:59.778  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:28:59.778  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:28:59.778  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:28:59.928  1018  2718 D SSRM:n  : SIOP:: AP = 290,
,03-20 17:28:59.988  1018  1097 V AlarmManager: waitForAlarm result :8
,03-20 17:28:59.988  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-20 17:28:59.998  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate,
,03-20 17:28:59.998  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-20 17:28:59.998  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,03-20 17:29:00.008  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:29:00.008  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-20 17:29:00.008  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
,03-20 17:29:00.028  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:29:00.048  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:29:00.048  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:29:00.058  1178  1178 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-20 17:29:00.078  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,03-20 17:29:00.088  1741  1741 D accuweather: [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,03-20 17:29:00.088  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
03-20 17:29:00.088  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,03-20 17:29:00.088  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! ,
03-20 17:29:00.088  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
03-20 17:29:00.088  1741  1741 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,03-20 17:29:00.088  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
03-20 17:29:00.088  1741  1741 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
03-20 17:29:00.088  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
03-20 17:29:00.088  1741  1741 E accuweather: [KK AccuPhone]>>> UIM:1488 [0:0] bTM 17 29
,03-20 17:29:00.508  1384  1384 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-20 17:29:00.668   288   288 E SMD     : DCD OFF,
,03-20 17:29:01.798  1018  1041 D SensorService: [SO] -0.326 0.077 9.902,
,03-20 17:29:02.908  1384  1384 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-20 17:29:03.548  1018  1051 D PowerManagerService: [s] UserActivityState : 1 -> 2
,03-20 17:29:03.548  1018  1051 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
03-20 17:29:03.548  1018  1051 D DisplayPowerController: animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-20 17:29:03.548  1018  1051 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-20 17:29:03.558  1018  1158 D lights  : lcd : 246 +
,03-20 17:29:03.568  1018  1158 D lights  : lcd : 246 -
03-20 17:29:03.568  1018  1158 D lights  : lcd : 213 +
,03-20 17:29:03.588  1018  1158 D lights  : lcd : 213 -
,03-20 17:29:03.588  1018  1158 D lights  : lcd : 179 +
,03-20 17:29:03.608  1018  1158 D lights  : lcd : 179 -
,03-20 17:29:03.608  1018  1158 D lights  : lcd : 146 +
,03-20 17:29:03.618  1018  1158 D lights  : lcd : 146 -
,03-20 17:29:03.618  1018  1158 D lights  : lcd : 113 +
,03-20 17:29:03.638  1018  1158 D lights  : lcd : 113 -
,03-20 17:29:03.638  1018  1158 D lights  : lcd : 79 +
,03-20 17:29:03.658  1018  1158 D lights  : lcd : 79 -
,03-20 17:29:03.658  1018  1158 D lights  : lcd : 46 +
,03-20 17:29:03.668   288   288 E SMD     : DCD OFF
,03-20 17:29:03.668  1018  1158 D lights  : lcd : 46 -
03-20 17:29:03.668  1018  1051 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
03-20 17:29:03.668  1018  1158 D lights  : lcd : 15 +
03-20 17:29:03.668  1018  1051 D DisplayPowerController: animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-20 17:29:03.688  1018  1158 D lights  : lcd : 15 -
,03-20 17:29:03.688  1018  1051 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
03-20 17:29:03.688  1018  1051 D DisplayPowerController: animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-20 17:29:03.848  1384  1384 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,03-20 17:29:04.468  1384  1384 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,03-20 17:29:04.638  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-20 17:29:06.678   288   288 E SMD     : DCD OFF
,03-20 17:29:06.758  1384  1384 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,03-20 17:29:07.818  1384  1384 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,03-20 17:29:08.548  1384  1384 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,03-20 17:29:08.648  1384  1384 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,03-20 17:29:09.558  1018  1051 D PowerManagerService: [s] UserActivityState : 2 -> 4
,03-20 17:29:09.558  1018  1051 I PowerManagerService: Nap time (uid 1000)...
03-20 17:29:09.558  1018  1051 D PowerManagerService: handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
03-20 17:29:09.558  1018  1051 I PowerManagerService: !@[ps] Screen__Off - 1 :  dream(timeout) (2)
03-20 17:29:09.558  1018  1051 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-20 17:29:09.558  1018  1051 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
03-20 17:29:09.558  1018  1154 V WindowOrientationListener: WindowOrientationListener disabled
,03-20 17:29:09.558  1018  1154 D SensorService: [SO] activate (ident=0xb9441a70, enabled=0)
03-20 17:29:09.558  1018  1051 D PowerManagerService: SecHardwareInterface.setBatteryADC : false
03-20 17:29:09.558  1018  1154 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-20 17:29:09.558  1018  1051 D PowerManagerService: handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
03-20 17:29:09.558  1018  1051 D PowerManagerService: handleSandman : startDream(true)
,03-20 17:29:09.558  1018  1051 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
03-20 17:29:09.558  1018  1051 I PowerManagerService: Sleeping (uid 1000)...
,03-20 17:29:09.558  1018  1051 D PowerManagerService: [s] UserActivityState : 4 -> 0
03-20 17:29:09.558   257   257 I SurfaceFlinger: id=14 createSurf (540x960),-1 flag=20004, DolorFade
,03-20 17:29:09.568  1018  1154 D SensorManager: unregisterListener ::   
,03-20 17:29:09.578  1018  1051 D PowerManagerService: Excessive delay in ColorFade : createSurface: 15ms
,03-20 17:29:09.578  1178  2358 D KeyguardViewMediator: onScreenTurnedOff(3)
03-20 17:29:09.578  1178  2358 I KeyguardEffectViewController: *** KeyguardEffectView getInstanceIfExists ***
03-20 17:29:09.578  1178  2358 D KeyguardEffectViewController: changeWallpaperByScreenOff()
03-20 17:29:09.578  1178  2358 D KeyguardViewMediator: notifyScreenOffLocked
,03-20 17:29:09.588  1178  2358 D KeyguardViewMediator: timeout : 5000,
,03-20 17:29:09.598  1018  1051 D PowerManagerService: Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 19ms
,03-20 17:29:09.608  5449  5449 V ActivityThread: updateVisibility : ActivityRecord{eae792c token=android.os.BinderProxy@97d8d00 {com.android.settings/com.android.settings.SettingsReceiverActivity}} show : true
,03-20 17:29:09.608  1178  2358 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 2
,03-20 17:29:09.608  1178  1178 D KeyguardViewMediator: handleNotifyScreenOff
03-20 17:29:09.618  1178  1178 D VolumePanel: onScreenTurnedOff()
03-20 17:29:09.618  1178  1178 D VolumePanel: mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,03-20 17:29:09.618  1018  1051 D DisplayPowerController: ColorFade: onAnimationStart
03-20 17:29:09.618  1018  1051 D DisplayPowerController: getFinalBrightness : Summary is 255 -> 255
03-20 17:29:09.618  1018  1051 D DisplayPowerController: performScreenOffTransition : no brightness animation
,03-20 17:29:09.618  1178  1178 D VolumePanel: mCoverBroadcastReceiver: Screen OFF end
,03-20 17:29:09.618  1178  1178 D SecKeyguardClockSingleView: onScreenTurnedOff
,03-20 17:29:09.628  1018  1018 D LightsService: [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
,03-20 17:29:09.628  1018  1018 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
03-20 17:29:09.628  1018  1018 D BatteryService: turn on LED for fully charged
03-20 17:29:09.628  1018  1078 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
03-20 17:29:09.628  1018  1078 E lights  : write_int failed to open -1
03-20 17:29:09.628  1018  1078 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,03-20 17:29:09.638  1018  1093 E SmartFaceService: onReceive: android.intent.action.SCREEN_OFF
,03-20 17:29:09.638  1018  1093 W System.err: java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,03-20 17:29:09.638  1018  1093 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-20 17:29:09.638  1018  1093 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,03-20 17:29:09.638  1018  1093 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-20 17:29:09.638  1018  1093 W System.err: 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
03-20 17:29:09.638  1018  1093 W System.err: 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
,03-20 17:29:09.638  1018  1093 W System.err: 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
03-20 17:29:09.638  1018  1093 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
03-20 17:29:09.638  1018  1093 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-20 17:29:09.638  1018  1093 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,03-20 17:29:09.638  1018  1093 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-20 17:29:09.638  1018  1093 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 17:29:09.638  1018  1093 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
,03-20 17:29:09.638  1018  1093 W System.err: 	at libcore.io.Posix.open(Native Method)
03-20 17:29:09.638  1018  1093 E SmartFaceService: fail to set sysfs 0
03-20 17:29:09.638  1018  1093 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-20 17:29:09.638  1018  1093 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-20 17:29:09.638  1018  1093 W System.err: 	... 10 more
,03-20 17:29:09.648  1178  1178 I StatusBar: Icon Only
,03-20 17:29:09.648  1178  1178 D PanelView: There is/are notification(s) 
,03-20 17:29:09.648  1018  1018 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,03-20 17:29:09.658  1018  1105 E MotionRecognitionService:  handler : SCREEN_OFF end 
,03-20 17:29:09.668   288   288 E SMD     : DCD OFF
,03-20 17:29:09.668  1018  1018 D NotificationService: ACTION_SCREEN_OFF
03-20 17:29:09.668  1018  1018 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
03-20 17:29:09.668  1018  1018 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
03-20 17:29:09.668  1018  1078 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,03-20 17:29:09.678  1018  1078 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,03-20 17:29:09.678  1018  1126 E WifiNative-wlan0: do suspend true
,03-20 17:29:09.678   283   283 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-20 17:29:09.678   283   283 V voice   : voice_set_parameters: enter: screen_state=off
03-20 17:29:09.678   283   283 V voice   : voice_set_parameters: exit with code(-2)
03-20 17:29:09.678   283   283 V msm8974_platform: platform_set_parameters: enter: screen_state=off
03-20 17:29:09.678   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
03-20 17:29:09.678   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
03-20 17:29:09.678   283   283 V audio_hw_primary: adev_set_parameters: exit
,03-20 17:29:09.688  1018  1049 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF,
03-20 17:29:09.688  1018  1049 D IpRemoteDisplayController: Bridge Server is not available
,03-20 17:29:09.688  1178  1178 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-20 17:29:09.698  1018  1043 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,03-20 17:29:09.698  1018  1018 D PersonaManagerService: ACTION_SCREEN_OFF onReceive
,03-20 17:29:09.698  1018  1063 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
,03-20 17:29:09.698  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,03-20 17:29:09.698  1420  1420 V EmergencyMode: [EmergencyStateReceiver] binteractive [false] why[3]
,03-20 17:29:09.708  1445  2661 D NfcService: call the applyRouting
,03-20 17:29:09.718  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_OFF
,03-20 17:29:09.718  1741  1741 D accuweather: [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,03-20 17:29:09.718  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance,
,03-20 17:29:09.728  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
,03-20 17:29:09.728  1018  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-20 17:29:09.728  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,03-20 17:29:09.728  1018  1079 W ActivityManager: userId = 0, bbcId = -10000
,03-20 17:29:09.728  1018  1079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 17:29:09.728  1018  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,03-20 17:29:09.738  1741  1741 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,03-20 17:29:09.748  1773  4521 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,03-20 17:29:09.758  1445  2661 D NfcService: index : 0
03-20 17:29:09.758  1445  2661 D NfcService: index : 1
,03-20 17:29:09.758  1018  1546 W ActivityManager: userId = 0, bbcId = -10000
03-20 17:29:09.758  1018  1546 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-20 17:29:09.758  1018  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 17:29:09.768  1741  1741 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,03-20 17:29:09.768  1741  1741 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,03-20 17:29:09.768  1741  1741 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
03-20 17:29:09.768  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,03-20 17:29:09.778  1900  1900 E LibSecureUISvc: svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,03-20 17:29:09.778  1018  2718 D SSRM:n  : SIOP:: AP = 290
,03-20 17:29:09.778  1773  1790 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-20 17:29:09.788  1018  1154 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,03-20 17:29:09.798  1773  1783 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-20 17:29:09.798  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,03-20 17:29:09.798  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,03-20 17:29:09.798  1741  1741 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
03-20 17:29:09.798  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,03-20 17:29:09.808  1018  1351 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:29:09.808  1018  1351 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4295, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:29:09.808  1018  1351 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:29:09.808  1018  1351 D BatteryService: stay LED for fully charged
03-20 17:29:09.808  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:29:09.808  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-20 17:29:09.808  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 17:29:09.808  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,03-20 17:29:09.818  1018  1018 I MotionRecognitionService: Plugged
03-20 17:29:09.818  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:29:09.818  1741  1741 D accuweather: [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,03-20 17:29:09.818  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:29:09.818  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:29:09.818  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:29:09.818  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:29:09.828  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:29:09.828  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:29:09.838  1741  1741 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,03-20 17:29:09.838  1741  1741 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-20 17:29:09.838  1018  1051 D DisplayPowerState: !@ ColorFade entry
,03-20 17:29:09.838  1018  1051 D DisplayPowerController: ColorFade: onAnimationEnd
,03-20 17:29:09.848  1018  1051 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
,03-20 17:29:09.848  1018  1158 D lights  : lcd : 0 +
,03-20 17:29:09.848  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:29:09.848  1018  1051 D DisplayPowerController: performScreenOffTransition : no brightness animation
,03-20 17:29:09.848  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:29:09.848  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:29:09.848  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:29:09.848  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:29:09.858  1018  1158 D lights  : lcd : 0 -
,03-20 17:29:09.858  1018  5999 D MISC PowerHAL: sysfs_write +: /sys/class/input/event3/device/enabled: 0,
,03-20 17:29:09.858  1018  1051 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
03-20 17:29:09.858  1018  5998 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 0
03-20 17:29:09.858  1018  1051 D DisplayPowerController: performScreenOffTransition : no brightness animation
03-20 17:29:09.858  1018  5998 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 0
03-20 17:29:09.858  1018  1051 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-20 17:29:09.858  1018  1051 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,03-20 17:29:09.908  1018  5999 D MISC PowerHAL: sysfs_write -: /sys/class/input/event3/device/enabled: 0
,03-20 17:29:09.908  1018  1056 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
03-20 17:29:09.908  1018  1056 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
03-20 17:29:09.908  1018  1056 D PowerManagerService-JNI: Excessive delay in MISC setInteractive(false) while turning screen off: 52ms
03-20 17:29:09.908  1018  1056 I QCOM PowerHAL: Got set_interactive hint
,03-20 17:29:09.908  1018  1056 D PowerManagerService: Excessive delay in nativeSetInteractive(false): 54ms
,03-20 17:29:09.908  1018  1056 D DisplayManagerService: !@display_state: ON -> OFF
03-20 17:29:09.908   257   257 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6fbe690
03-20 17:29:09.908  1018  1049 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 540 x 960, 60.0 fps, supportedRefreshRates [60.0], density 240, 244.928 x 243.839 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-20 17:29:09.908   257   257 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
03-20 17:29:09.918  1018  1018 V ActivityManager: Display changed displayId=0
,03-20 17:29:09.918   257   257 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
03-20 17:29:09.918   257   257 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
,03-20 17:29:09.938  1178  1178 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte level=4
,03-20 17:29:09.938  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,03-20 17:29:09.938  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,03-20 17:29:09.938  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,03-20 17:29:09.938  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-20 17:29:09.938  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
03-20 17:29:09.938  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 17:29:09.938  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 17:29:09.938  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 17:29:09.938  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 17:29:10.158   257   257 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,03-20 17:29:10.158   257   530 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-20 17:29:10.158   257   530 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
,03-20 17:29:10.158   257   530 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
,03-20 17:29:10.158  1018  1056 D SurfaceControl: Excessive delay in setPowerMode(): 244ms
,03-20 17:29:10.158  1018  1056 D PowerManagerService: Excessive delay in !@display_state: OFF: 245ms
03-20 17:29:10.158  1018  1056 I libsuspend: !@autosuspend_wakeup_count_enable
,03-20 17:29:10.158  1018  1056 I libsuspend: !@autosuspend_wakeup_count_enable done
,03-20 17:29:10.158  1018  1056 D PowerManagerService: Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 301ms
03-20 17:29:10.158  1018  1051 I PowerManagerService: [PWL] Off : 0s ago
,03-20 17:29:12.678   288   288 E SMD     : DCD OFF
,03-20 17:29:14.588  1018  1097 V AlarmManager: waitForAlarm result :4
,03-20 17:29:14.588  1178  1178 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,03-20 17:29:14.588  1178  1178 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,03-20 17:29:14.588  1178  1178 V KeyguardEffectViewController: *** Keyguard wallpaper service already unbounded
,03-20 17:29:15.158  1018  1051 I PowerManagerService: [PWL] Off : 5s ago
,03-20 17:29:15.678   288   288 E SMD     : DCD OFF,
,03-20 17:29:18.678   288   288 E SMD     : DCD OFF
,03-20 17:29:19.828  1018  2718 D SSRM:n  : SIOP:: AP = 280
,03-20 17:29:19.868  1018  3043 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:29:19.868  1018  3043 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:29:19.868  1018  3043 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:29:19.868  1018  3043 D BatteryService: stay LED for fully charged
03-20 17:29:19.868  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:29:19.868  1018  1018 I MotionRecognitionService: Plugged
03-20 17:29:19.868  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:29:19.878  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:29:19.878  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:29:19.878  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:29:19.878  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:29:19.888  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-20 17:29:19.888  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:29:19.898  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-20 17:29:19.898  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:29:19.898  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:29:19.898  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:29:19.898  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:29:21.688   288   288 E SMD     : DCD OFF,
,03-20 17:29:24.628  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-20 17:29:24.688   288   288 E SMD     : DCD OFF,
,03-20 17:29:25.168  1018  1051 I PowerManagerService: [PWL] Off : 15s ago,
,03-20 17:29:26.428  1018  1088 D TimaService: TIMA: TimaService scheduler is intialized. 
03-20 17:29:26.428  1018  1088 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
03-20 17:29:26.428  1018  1087 D TimaService: TimaServiceHandler.handleMessage what =1
,03-20 17:29:27.268  1018  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-20 17:29:27.268  1018  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-20 17:29:27.268  1018  1088 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-20 17:29:27.268  1018  1088 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-20 17:29:27.688   288   288 E SMD     : DCD OFF
,03-20 17:29:28.678  1018  1322 E Watchdog: !@Sync 20,
,03-20 17:29:29.878  1018  2718 D SSRM:n  : SIOP:: AP = 270
,03-20 17:29:29.928  1018  3044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:29:29.928  1018  3044 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4310, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:29:29.928  1018  3044 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:29:29.928  1018  3044 D BatteryService: stay LED for fully charged
03-20 17:29:29.928  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:29:29.938  1018  1018 I MotionRecognitionService: Plugged,
03-20 17:29:29.938  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:29:29.938  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:29:29.938  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:29:29.948  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:29:29.948  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:29:29.958  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:29:29.958  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:29:29.968  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:29:29.968  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:29:29.968  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:29:29.968  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:29:29.968  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:29:30.688   288   288 E SMD     : DCD OFF
,03-20 17:29:33.688   288   288 E SMD     : DCD OFF
,03-20 17:29:36.688   288   288 E SMD     : DCD OFF
,03-20 17:29:39.698   288   288 E SMD     : DCD OFF
,03-20 17:29:39.758  1018  1097 V AlarmManager: waitForAlarm result :4,
,03-20 17:29:39.898  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:29:39.988  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:29:39.998  1018  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4307, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:29:39.998  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-20 17:29:39.998  1018  1030 D BatteryService: stay LED for fully charged
03-20 17:29:39.998  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:29:39.998  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:29:39.998  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:29:39.998  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:29:39.998  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:29:40.008  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:29:40.008  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:29:40.018  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:29:40.018  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:29:40.038  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:29:40.038  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:29:40.038  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:29:40.038  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:29:40.038  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:29:40.168  1018  1051 I PowerManagerService: [PWL] Off : 30s ago,
,03-20 17:29:42.698   288   288 E SMD     : DCD OFF,
,03-20 17:29:44.628  1018  2730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-20 17:29:45.698   288   288 E SMD     : DCD OFF,
,03-20 17:29:46.638  1018  1758 I ActivityManager: Killing 4865:com.osp.app.signin/u0a36 (adj 15): empty #31
,03-20 17:29:46.768  1018  1043 W libprocessgroup: failed to open /acct/uid_10036/pid_4865/cgroup.procs: No such file or directory
,03-20 17:29:48.698   288   288 E SMD     : DCD OFF
,03-20 17:29:49.948  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:29:50.058  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:29:50.058  1018  1031 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4311, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:29:50.058  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:29:50.058  1018  1031 D BatteryService: stay LED for fully charged
,03-20 17:29:50.058  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:29:50.068  1018  1018 I MotionRecognitionService: Plugged
03-20 17:29:50.068  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:29:50.068  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:29:50.068  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:29:50.068  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-20 17:29:50.068  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:29:50.078  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:29:50.078  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:29:50.088  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:29:50.088  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:29:50.088  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:29:50.098  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:29:50.098  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:29:51.698   288   288 E SMD     : DCD OFF,
,03-20 17:29:54.698   288   288 E SMD     : DCD OFF,
,03-20 17:29:57.708   288   288 E SMD     : DCD OFF,
,03-20 17:29:58.678  1018  1322 E Watchdog: !@Sync 21,
,03-20 17:29:59.998  1018  1097 V AlarmManager: waitForAlarm result :8,
,03-20 17:29:59.998  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:30:00.118  1018  1542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:30:00.118  1018  1542 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4313, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-20 17:30:00.118  1018  1542 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:30:00.118  1018  1542 D BatteryService: stay LED for fully charged
,03-20 17:30:00.118  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:30:00.128  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:30:00.128  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:30:00.128  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:30:00.128  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:30:00.128  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:30:00.128  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:30:00.138  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:30:00.138  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:30:00.148  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:30:00.158  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:30:00.158  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:30:00.158  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:30:00.158  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:30:00.178  1018  1051 I PowerManagerService: [PWL] Off : 50s ago
,03-20 17:30:00.708   288   288 E SMD     : DCD OFF
,03-20 17:30:03.708   288   288 E SMD     : DCD OFF
,03-20 17:30:06.708   288   288 E SMD     : DCD OFF
,03-20 17:30:09.708   288   288 E SMD     : DCD OFF
,03-20 17:30:10.018  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:30:10.178  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:30:10.178  1018  1501 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4315, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:30:10.178  1018  1501 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:30:10.178  1018  1501 D BatteryService: stay LED for fully charged
,03-20 17:30:10.178  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:30:10.188  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:30:10.188  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:30:10.188  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:30:10.188  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:30:10.208  1018  1018 I MotionRecognitionService: Plugged
03-20 17:30:10.208  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:30:10.208  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:30:10.208  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:30:10.218  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:30:10.218  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:30:10.218  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:30:10.218  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:30:10.218  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:30:12.708   288   288 E SMD     : DCD OFF
,03-20 17:30:15.718   288   288 E SMD     : DCD OFF
,03-20 17:30:18.718   288   288 E SMD     : DCD OFF
,03-20 17:30:20.068  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:30:20.238  1018  1545 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:30:20.248  1018  1545 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4313, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:30:20.248  1018  1545 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-20 17:30:20.248  1018  1545 D BatteryService: stay LED for fully charged
03-20 17:30:20.248  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:30:20.248  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:30:20.248  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:30:20.248  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:30:20.248  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:30:20.258  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:30:20.258  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:30:20.268  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:30:20.268  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:30:20.278  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:30:20.278  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:30:20.278  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:30:20.278  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:30:20.278  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:30:21.718   288   288 E SMD     : DCD OFF
,03-20 17:30:24.718   288   288 E SMD     : DCD OFF
,03-20 17:30:25.178  1018  1051 I PowerManagerService: [PWL] Off : 75s ago
,03-20 17:30:27.718   288   288 E SMD     : DCD OFF
,03-20 17:30:28.678  1018  1322 E Watchdog: !@Sync 22
,03-20 17:30:30.118  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:30:30.308  1018  3043 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:30:30.308  1018  3043 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4316, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:30:30.308  1018  3043 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:30:30.308  1018  3043 D BatteryService: stay LED for fully charged
03-20 17:30:30.308  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:30:30.308  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:30:30.308  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:30:30.318  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:30:30.318  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:30:30.328  1018  1018 I MotionRecognitionService: Plugged
03-20 17:30:30.328  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:30:30.328  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:30:30.328  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:30:30.338  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:30:30.338  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:30:30.338  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:30:30.338  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:30:30.338  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:30:30.718   288   288 E SMD     : DCD OFF
,03-20 17:30:33.728   288   288 E SMD     : DCD OFF,
,03-20 17:30:36.718   288   288 E SMD     : DCD OFF,
,03-20 17:30:39.728   288   288 E SMD     : DCD OFF
,03-20 17:30:40.138  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:30:40.358  1018  3044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-20 17:30:42.728   288   288 E SMD     : DCD OFF
,03-20 17:30:45.728   288   288 E SMD     : DCD OFF
,03-20 17:30:48.728   288   288 E SMD     : DCD OFF
,03-20 17:30:50.188  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:30:50.418  1018  1079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:30:50.418  1018  1079 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4317, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:30:50.418  1018  1079 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:30:50.418  1018  1079 D BatteryService: stay LED for fully charged
03-20 17:30:50.418  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:30:50.428  1018  1018 I MotionRecognitionService: Plugged,
03-20 17:30:50.428  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:30:50.428  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:30:50.428  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:30:50.428  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:30:50.428  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-20 17:30:50.438  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:30:50.438  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:30:50.448  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:30:50.448  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:30:50.448  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:30:50.448  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:30:50.448  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:30:51.738   288   288 E SMD     : DCD OFF
,03-20 17:30:54.738   288   288 E SMD     : DCD OFF
,03-20 17:30:55.188  1018  1051 I PowerManagerService: [PWL] Off : 105s ago
,03-20 17:30:57.738   288   288 E SMD     : DCD OFF
,03-20 17:30:58.668  1018  1322 E Watchdog: !@Sync 23,
,03-20 17:31:00.238  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:31:00.478  1018  1545 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:31:00.478  1018  1545 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4317, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:31:00.478  1018  1545 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:31:00.478  1018  1545 D BatteryService: stay LED for fully charged
,03-20 17:31:00.478  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:31:00.488  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:31:00.488  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:31:00.488  1018  1018 I MotionRecognitionService: Plugged
03-20 17:31:00.488  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:31:00.488  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:31:00.488  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:31:00.498  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-20 17:31:00.498  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:31:00.508  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-20 17:31:00.508  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:31:00.508  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:31:00.508  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:31:00.508  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:31:00.738   288   288 E SMD     : DCD OFF
,03-20 17:31:03.738   288   288 E SMD     : DCD OFF,
,03-20 17:31:06.738   288   288 E SMD     : DCD OFF,
,03-20 17:31:09.748   288   288 E SMD     : DCD OFF,
,03-20 17:31:10.258  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:31:10.538  1018  3043 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:31:10.538  1018  3043 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4312, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:31:10.538  1018  3043 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:31:10.538  1018  3043 D BatteryService: stay LED for fully charged
03-20 17:31:10.538  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:31:10.548  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:31:10.548  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:31:10.548  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-20 17:31:10.548  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:31:10.558  1018  1018 I MotionRecognitionService: Plugged
03-20 17:31:10.558  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:31:10.558  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:31:10.558  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:31:10.568  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:31:10.568  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:31:10.568  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:31:10.568  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:31:10.568  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:31:12.748   288   288 E SMD     : DCD OFF
,03-20 17:31:15.748   288   288 E SMD     : DCD OFF
,03-20 17:31:18.748   288   288 E SMD     : DCD OFF
,03-20 17:31:20.278  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:31:20.598  1018  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:31:20.598  1018  1487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4317, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
03-20 17:31:20.598  1018  1487 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:31:20.598  1018  1487 D BatteryService: stay LED for fully charged
03-20 17:31:20.598  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,03-20 17:31:20.608  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-20 17:31:20.608  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-20 17:31:20.618  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:31:20.618  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:31:20.618  1018  1018 I MotionRecognitionService: Plugged
03-20 17:31:20.618  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:31:20.628  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:31:20.628  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:31:20.648  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-20 17:31:20.648  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:31:20.648  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:31:20.648  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:31:20.648  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:31:21.748   288   288 E SMD     : DCD OFF
,03-20 17:31:24.748   288   288 E SMD     : DCD OFF
,03-20 17:31:27.758   288   288 E SMD     : DCD OFF
,03-20 17:31:28.668  1018  1322 E Watchdog: !@Sync 24
,03-20 17:31:30.198  1018  1051 I PowerManagerService: [PWL] Off : 140s ago
,03-20 17:31:30.328  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:31:30.658  1018  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:31:30.658  1018  1223 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:31:30.658  1018  1223 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:31:30.658  1018  1223 D BatteryService: stay LED for fully charged
03-20 17:31:30.658  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:31:30.668  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:31:30.668  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:31:30.668  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:31:30.668  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-20 17:31:30.668  1018  1018 I MotionRecognitionService: Plugged,
03-20 17:31:30.668  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:31:30.678  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:31:30.678  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:31:30.688  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:31:30.688  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:31:30.688  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:31:30.688  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:31:30.688  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:31:30.758   288   288 E SMD     : DCD OFF,
,03-20 17:31:33.758   288   288 E SMD     : DCD OFF,
,03-20 17:31:36.758   288   288 E SMD     : DCD OFF,
,03-20 17:31:39.758   288   288 E SMD     : DCD OFF,
,03-20 17:31:40.348  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:31:40.718  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:31:40.718  1018  1031 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4316, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:31:40.718  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:31:40.718  1018  1031 D BatteryService: stay LED for fully charged
03-20 17:31:40.718  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:31:40.728  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:31:40.728  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:31:40.728  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:31:40.728  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:31:40.728  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:31:40.728  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:31:40.738  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-20 17:31:40.738  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:31:40.748  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:31:40.748  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:31:40.748  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:31:40.748  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:31:40.748  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:31:42.758   288   288 E SMD     : DCD OFF
,03-20 17:31:45.758   288   288 E SMD     : DCD OFF
,03-20 17:31:48.768   288   288 E SMD     : DCD OFF
,03-20 17:31:50.398  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:31:50.778  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:31:50.778  1018  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4317, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:31:50.778  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:31:50.778  1018  1030 D BatteryService: stay LED for fully charged
03-20 17:31:50.778  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:31:50.778  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:31:50.778  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:31:50.778  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:31:50.778  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-20 17:31:50.788  1018  1018 I MotionRecognitionService: Plugged
03-20 17:31:50.788  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:31:50.788  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:31:50.798  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:31:50.808  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:31:50.808  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:31:50.808  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:31:50.808  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:31:50.808  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:31:51.768   288   288 E SMD     : DCD OFF,
,03-20 17:31:54.768   288   288 E SMD     : DCD OFF,
,03-20 17:31:57.768   288   288 E SMD     : DCD OFF,
,03-20 17:31:58.678  1018  1322 E Watchdog: !@Sync 25,
,03-20 17:32:00.448  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:32:00.768   288   288 E SMD     : DCD OFF,
,03-20 17:32:00.838  1018  1351 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-20 17:32:03.768   288   288 E SMD     : DCD OFF
,03-20 17:32:06.778   288   288 E SMD     : DCD OFF,
,03-20 17:32:09.778   288   288 E SMD     : DCD OFF,
,03-20 17:32:10.218  1018  1051 I PowerManagerService: [PWL] Off : 180s ago,
,03-20 17:32:10.468  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:32:10.898  1018  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:32:10.898  1018  1223 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:32:10.898  1018  1223 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:32:10.898  1018  1223 D BatteryService: stay LED for fully charged
03-20 17:32:10.898  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:32:10.908  1018  1018 I MotionRecognitionService: Plugged
03-20 17:32:10.908  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:32:10.908  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:32:10.908  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:32:10.908  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:32:10.908  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:32:10.918  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-20 17:32:10.918  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:32:10.928  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-20 17:32:10.928  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:32:10.928  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:32:10.928  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:32:10.928  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:32:12.778   288   288 E SMD     : DCD OFF,
,03-20 17:32:15.778   288   288 E SMD     : DCD OFF,
,03-20 17:32:18.778   288   288 E SMD     : DCD OFF,
,03-20 17:32:20.528  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:32:20.958  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:32:20.958  1018  1031 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:32:20.958  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:32:20.958  1018  1031 D BatteryService: stay LED for fully charged
03-20 17:32:20.958  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:32:20.958  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:32:20.958  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:32:20.968  1018  1018 I MotionRecognitionService: Plugged
03-20 17:32:20.968  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:32:20.968  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:32:20.968  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:32:20.978  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:32:20.978  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:32:20.988  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:32:20.988  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:32:20.988  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:32:20.988  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:32:20.988  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:32:21.778   288   288 E SMD     : DCD OFF
,03-20 17:32:24.788   288   288 E SMD     : DCD OFF,
,03-20 17:32:27.788   288   288 E SMD     : DCD OFF,
,03-20 17:32:28.678  1018  1322 E Watchdog: !@Sync 26,
,03-20 17:32:28.778  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-20 17:32:28.778  1018  1097 V AlarmManager: waitForAlarm result :8
03-20 17:32:28.778  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,03-20 17:32:28.778  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-20 17:32:28.788  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,03-20 17:32:28.798  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:32:28.798  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-20 17:32:28.798  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
,03-20 17:32:28.808  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:32:28.818  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:32:28.818  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:32:28.838  1178  1178 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-20 17:32:28.858  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:32:30.578  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:32:30.788   288   288 E SMD     : DCD OFF
,03-20 17:32:31.018  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:32:31.018  1018  1031 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4317, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:32:31.018  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:32:31.018  1018  1031 D BatteryService: stay LED for fully charged
03-20 17:32:31.018  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:32:31.028  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:32:31.028  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-20 17:32:31.028  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:32:31.028  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:32:31.028  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:32:31.028  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-20 17:32:31.028  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:32:31.028  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:32:31.028  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-20 17:32:31.038  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:32:31.048  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-20 17:32:31.048  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:32:31.048  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:32:33.778   288   288 E SMD     : DCD OFF,
,03-20 17:32:36.788   288   288 E SMD     : DCD OFF
,03-20 17:32:39.788   288   288 E SMD     : DCD OFF,
,03-20 17:32:40.598  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:32:41.078  1018  1542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:32:41.078  1018  1542 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4313, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:32:41.078  1018  1542 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:32:41.078  1018  1542 D BatteryService: stay LED for fully charged,
03-20 17:32:41.078  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:32:41.078  1018  1018 I MotionRecognitionService: Plugged
03-20 17:32:41.078  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:32:41.088  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:32:41.088  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:32:41.088  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:32:41.088  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:32:41.098  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-20 17:32:41.098  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:32:41.108  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:32:41.108  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:32:41.108  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:32:41.108  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:32:41.108  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:32:42.798   288   288 E SMD     : DCD OFF
,03-20 17:32:45.798   288   288 E SMD     : DCD OFF
,03-20 17:32:48.788   288   288 E SMD     : DCD OFF
,03-20 17:32:50.648  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:32:51.138  1018  1351 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:32:51.138  1018  1351 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:32:51.138  1018  1351 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:32:51.138  1018  1351 D BatteryService: stay LED for fully charged
03-20 17:32:51.138  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:32:51.138  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:32:51.138  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:32:51.138  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:32:51.138  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:32:51.148  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:32:51.148  1018  1018 I MotionRecognitionService: Plugged
03-20 17:32:51.148  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:32:51.148  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:32:51.148  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-20 17:32:51.148  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:32:51.158  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:32:51.158  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:32:51.158  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:32:51.798   288   288 E SMD     : DCD OFF
,03-20 17:32:54.798   288   288 E SMD     : DCD OFF
,03-20 17:32:55.218  1018  1051 I PowerManagerService: [PWL] Off : 225s ago
,03-20 17:32:57.798   288   288 E SMD     : DCD OFF
,03-20 17:32:58.678  1018  1322 E Watchdog: !@Sync 27
,03-20 17:32:59.998  1018  1097 V AlarmManager: waitForAlarm result :8,
,03-20 17:33:00.688  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:33:00.808   288   288 E SMD     : DCD OFF,
,03-20 17:33:01.198  1018  3044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:33:01.198  1018  3044 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:33:01.198  1018  3044 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:33:01.198  1018  3044 D BatteryService: stay LED for fully charged
03-20 17:33:01.198  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:33:01.198  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-20 17:33:01.198  1018  1018 I MotionRecognitionService: Plugged
03-20 17:33:01.198  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:33:01.198  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:33:01.208  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:33:01.208  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:33:01.218  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:33:01.218  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:33:01.238  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:33:01.238  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:33:01.238  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:33:01.238  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:33:01.238  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:33:03.798   288   288 E SMD     : DCD OFF,
,03-20 17:33:06.808   288   288 E SMD     : DCD OFF,
,03-20 17:33:09.808   288   288 E SMD     : DCD OFF,
,03-20 17:33:10.708  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:33:11.258  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:33:11.258  1018  1501 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4315, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:33:11.258  1018  1501 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:33:11.258  1018  1501 D BatteryService: stay LED for fully charged
,03-20 17:33:11.258  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:33:11.258  1018  1018 I MotionRecognitionService: Plugged
03-20 17:33:11.258  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-20 17:33:11.258  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:33:11.258  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-20 17:33:11.268  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:33:11.268  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:33:11.278  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:33:11.278  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:33:11.288  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:33:11.288  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:33:11.288  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:33:11.288  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:33:11.288  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:33:12.808   288   288 E SMD     : DCD OFF,
,03-20 17:33:15.808   288   288 E SMD     : DCD OFF,
,03-20 17:33:18.818   288   288 E SMD     : DCD OFF,
,03-20 17:33:20.748  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:33:21.318  1018  1541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:33:21.318  1018  1541 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:33:21.318  1018  1541 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:33:21.318  1018  1541 D BatteryService: stay LED for fully charged
03-20 17:33:21.318  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:33:21.318  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:33:21.318  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:33:21.318  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:33:21.328  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:33:21.328  1018  1018 I MotionRecognitionService: Plugged
03-20 17:33:21.328  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:33:21.338  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-20 17:33:21.338  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:33:21.358  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:33:21.358  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:33:21.358  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:33:21.358  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:33:21.358  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:33:21.818   288   288 E SMD     : DCD OFF,
,03-20 17:33:24.818   288   288 E SMD     : DCD OFF,
,03-20 17:33:27.818   288   288 E SMD     : DCD OFF,
,03-20 17:33:28.688  1018  1322 E Watchdog: !@Sync 28,
,03-20 17:33:30.798  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:33:30.808   288   288 E SMD     : DCD OFF,
,03-20 17:33:31.368  1018  3043 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:33:33.808   288   288 E SMD     : DCD OFF,
,03-20 17:33:36.828   288   288 E SMD     : DCD OFF,
,03-20 17:33:39.828   288   288 E SMD     : DCD OFF,
,03-20 17:33:40.818  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:33:41.428  1018  3044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:33:41.428  1018  3044 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:33:41.428  1018  3044 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:33:41.428  1018  3044 D BatteryService: stay LED for fully charged,
03-20 17:33:41.428  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:33:41.438  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:33:41.438  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:33:41.438  1018  1018 I MotionRecognitionService: Plugged
03-20 17:33:41.438  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:33:41.438  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-20 17:33:41.438  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:33:41.448  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:33:41.448  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:33:41.458  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:33:41.458  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:33:41.458  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:33:41.458  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:33:41.458  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:33:42.828   288   288 E SMD     : DCD OFF
,03-20 17:33:45.228  1018  1051 I PowerManagerService: [PWL] Off : 275s ago,
,03-20 17:33:45.828   288   288 E SMD     : DCD OFF,
,03-20 17:33:48.828   288   288 E SMD     : DCD OFF,
,03-20 17:33:50.878  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:33:51.488  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:33:51.488  1018  1501 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4317, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:33:51.488  1018  1501 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:33:51.488  1018  1501 D BatteryService: stay LED for fully charged
,03-20 17:33:51.498  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:33:51.498  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:33:51.498  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:33:51.498  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:33:51.498  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:33:51.508  1018  1018 I MotionRecognitionService: Plugged,
03-20 17:33:51.508  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:33:51.518  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:33:51.518  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:33:51.528  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-20 17:33:51.528  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:33:51.528  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:33:51.528  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:33:51.528  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:33:51.828   288   288 E SMD     : DCD OFF
,03-20 17:33:54.828   288   288 E SMD     : DCD OFF
,03-20 17:33:57.838   288   288 E SMD     : DCD OFF
,03-20 17:33:58.688  1018  1322 E Watchdog: !@Sync 29,
,03-20 17:34:00.838   288   288 E SMD     : DCD OFF
,03-20 17:34:00.928  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:34:01.548  1018  1541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-20 17:34:03.838   288   288 E SMD     : DCD OFF
,03-20 17:34:06.838   288   288 E SMD     : DCD OFF,
,03-20 17:34:09.838   288   288 E SMD     : DCD OFF,
,03-20 17:34:10.948  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:34:11.608  1018  1079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-20 17:34:12.838   288   288 E SMD     : DCD OFF
,03-20 17:34:15.848   288   288 E SMD     : DCD OFF,
,03-20 17:34:18.838   288   288 E SMD     : DCD OFF,
,03-20 17:34:20.998  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:34:21.668  1018  1542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:34:21.848   288   288 E SMD     : DCD OFF
,03-20 17:34:24.838   288   288 E SMD     : DCD OFF
,03-20 17:34:26.428  1018  1088 D TimaService: TIMA: TimaService scheduler is intialized. ,
03-20 17:34:26.428  1018  1088 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
03-20 17:34:26.428  1018  1087 D TimaService: TimaServiceHandler.handleMessage what =1
,03-20 17:34:27.838   288   288 E SMD     : DCD OFF
,03-20 17:34:28.378  1018  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-20 17:34:28.378  1018  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-20 17:34:28.398  1018  1088 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-20 17:34:28.398  1018  1088 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-20 17:34:28.688  1018  1322 E Watchdog: !@Sync 30
,03-20 17:34:30.848   288   288 E SMD     : DCD OFF,
,03-20 17:34:31.058  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:34:31.728  1018  1546 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:34:31.728  1018  1546 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:34:31.728  1018  1546 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-20 17:34:31.728  1018  1546 D BatteryService: stay LED for fully charged
03-20 17:34:31.728  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:34:31.728  1018  1018 I MotionRecognitionService: Plugged
03-20 17:34:31.728  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:34:31.738  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:34:31.738  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:34:31.738  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:34:31.738  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:34:31.738  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:34:31.738  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:34:31.758  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-20 17:34:31.758  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:34:31.758  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:34:31.758  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:34:31.758  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:34:33.858   288   288 E SMD     : DCD OFF
,03-20 17:34:36.858   288   288 E SMD     : DCD OFF,
,03-20 17:34:39.858   288   288 E SMD     : DCD OFF,
,03-20 17:34:40.238  1018  1051 I PowerManagerService: [PWL] Off : 330s ago,
,03-20 17:34:41.078  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:34:41.788  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:34:41.788  1018  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:34:41.788  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:34:41.788  1018  1030 D BatteryService: stay LED for fully charged
03-20 17:34:41.788  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:34:41.798  1018  1018 I MotionRecognitionService: Plugged
03-20 17:34:41.798  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:34:41.798  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:34:41.798  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:34:41.798  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:34:41.798  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:34:41.818  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-20 17:34:41.818  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:34:41.828  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:34:41.828  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:34:41.828  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:34:41.828  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:34:41.828  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:34:42.858   288   288 E SMD     : DCD OFF
,03-20 17:34:45.858   288   288 E SMD     : DCD OFF,
,03-20 17:34:48.858   288   288 E SMD     : DCD OFF,
,03-20 17:34:51.128  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:34:51.848  1018  1351 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-20 17:34:51.858   288   288 E SMD     : DCD OFF,
,03-20 17:34:54.858   288   288 E SMD     : DCD OFF,
,03-20 17:34:57.858   288   288 E SMD     : DCD OFF,
,03-20 17:34:58.688  1018  1322 E Watchdog: !@Sync 31,
,03-20 17:35:00.858   288   288 E SMD     : DCD OFF,
,03-20 17:35:01.198  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:35:01.908  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:35:01.908  1018  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-20 17:35:01.908  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:35:01.908  1018  1030 D BatteryService: stay LED for fully charged,
03-20 17:35:01.908  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,03-20 17:35:01.918  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-20 17:35:01.918  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:35:01.918  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-20 17:35:01.918  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-20 17:35:01.928  1018  1018 I MotionRecognitionService: Plugged
03-20 17:35:01.928  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:35:01.928  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-20 17:35:01.928  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:35:01.938  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:35:01.948  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:35:01.948  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:35:01.948  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:35:01.948  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:35:03.868   288   288 E SMD     : DCD OFF,
,03-20 17:35:06.858   288   288 E SMD     : DCD OFF,
,03-20 17:35:09.868   288   288 E SMD     : DCD OFF,
,03-20 17:35:11.208  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:35:11.968  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:35:11.968  1018  1031 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:35:11.968  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:35:11.968  1018  1031 D BatteryService: stay LED for fully charged
03-20 17:35:11.968  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:35:11.968  1018  1018 I MotionRecognitionService: Plugged,
03-20 17:35:11.968  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:35:11.978  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:35:11.978  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:35:11.978  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:35:11.978  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:35:11.988  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:35:11.988  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:35:11.998  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:35:11.998  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:35:11.998  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:35:11.998  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:35:11.998  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:35:12.878   288   288 E SMD     : DCD OFF,
,03-20 17:35:15.868   288   288 E SMD     : DCD OFF
,03-20 17:35:18.878   288   288 E SMD     : DCD OFF
,03-20 17:35:21.268  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:35:21.868   288   288 E SMD     : DCD OFF
,03-20 17:35:22.028  1018  1542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:35:22.028  1018  1542 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:35:22.028  1018  1542 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-20 17:35:22.038  1018  1542 D BatteryService: stay LED for fully charged
03-20 17:35:22.038  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:35:22.038  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:35:22.038  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:35:22.038  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:35:22.038  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:35:22.048  1018  1018 I MotionRecognitionService: Plugged
03-20 17:35:22.048  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:35:22.058  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-20 17:35:22.058  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:35:22.078  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:35:22.078  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:35:22.078  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:35:22.078  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:35:22.078  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:35:24.878   288   288 E SMD     : DCD OFF,
,03-20 17:35:27.878   288   288 E SMD     : DCD OFF,
,03-20 17:35:28.688  1018  1322 E Watchdog: !@Sync 32
,03-20 17:35:30.888   288   288 E SMD     : DCD OFF
,03-20 17:35:31.338  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:35:32.088  1018  1351 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:35:32.088  1018  1351 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:35:32.088  1018  1351 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
03-20 17:35:32.088  1018  1351 D BatteryService: stay LED for fully charged
03-20 17:35:32.088  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:35:32.098  1018  1018 I MotionRecognitionService: Plugged
03-20 17:35:32.098  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:35:32.098  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:35:32.098  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:35:32.098  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:35:32.108  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:35:32.118  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-20 17:35:32.118  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:35:32.128  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:35:32.128  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:35:32.128  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:35:32.128  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:35:32.128  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:35:33.888   288   288 E SMD     : DCD OFF,
,03-20 17:35:36.888   288   288 E SMD     : DCD OFF,
,03-20 17:35:39.888   288   288 E SMD     : DCD OFF,
,03-20 17:35:40.248  1018  1051 I PowerManagerService: [PWL] Off : 390s ago,
,03-20 17:35:41.348  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:35:42.158  1018  1545 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-20 17:35:42.878   288   288 E SMD     : DCD OFF,
,03-20 17:35:45.888   288   288 E SMD     : DCD OFF,
,03-20 17:35:46.828  1018  1097 V AlarmManager: waitForAlarm result :4,
,03-20 17:35:46.838  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-20 17:35:46.838  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,03-20 17:35:46.848  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-20 17:35:46.848  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1,
,03-20 17:35:46.858  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
03-20 17:35:46.858  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-20 17:35:46.858  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
,03-20 17:35:46.878  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:35:46.888  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:35:46.888  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:35:46.908  1178  1178 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-20 17:35:46.928  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-20 17:35:46.998  1634  3815 D GCM     : Message class com.google.e.a.a.h
,03-20 17:35:48.898   288   288 E SMD     : DCD OFF,
,03-20 17:35:51.408  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:35:51.888   288   288 E SMD     : DCD OFF,
,03-20 17:35:52.218  1018  1545 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-20 17:35:54.898   288   288 E SMD     : DCD OFF,
,03-20 17:35:57.898   288   288 E SMD     : DCD OFF,
,03-20 17:35:58.688  1018  1322 E Watchdog: !@Sync 33
,03-20 17:35:59.988  1018  1097 V AlarmManager: waitForAlarm result :8,
,03-20 17:36:00.898   288   288 E SMD     : DCD OFF,
,03-20 17:36:01.458  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:36:02.268  1018  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:36:02.278  1018  1223 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:36:02.278  1018  1223 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:36:02.278  1018  1223 D BatteryService: stay LED for fully charged
03-20 17:36:02.278  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:36:02.278  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:36:02.278  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:36:02.278  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:36:02.278  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:36:02.288  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:36:02.288  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:36:02.288  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:36:02.288  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:36:02.298  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:36:02.308  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:36:02.308  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:36:02.308  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:36:02.308  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:36:03.908   288   288 E SMD     : DCD OFF,
,03-20 17:36:06.908   288   288 E SMD     : DCD OFF,
,03-20 17:36:09.908   288   288 E SMD     : DCD OFF
,03-20 17:36:11.488  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:36:12.328  1018  1542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:36:12.328  1018  1542 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:36:12.328  1018  1542 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:36:12.328  1018  1542 D BatteryService: stay LED for fully charged
,03-20 17:36:12.328  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:36:12.338  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:36:12.338  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:36:12.338  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:36:12.338  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:36:12.348  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:36:12.348  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:36:12.348  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:36:12.348  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:36:12.358  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-20 17:36:12.358  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:36:12.358  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:36:12.358  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:36:12.358  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:36:12.898   288   288 E SMD     : DCD OFF,
,03-20 17:36:15.908   288   288 E SMD     : DCD OFF
,03-20 17:36:18.898   288   288 E SMD     : DCD OFF,
,03-20 17:36:21.538  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:36:21.918   288   288 E SMD     : DCD OFF,
,03-20 17:36:22.388  1018  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:36:22.398  1018  1487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:36:22.398  1018  1487 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:36:22.398  1018  1487 D BatteryService: stay LED for fully charged
,03-20 17:36:22.398  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:36:22.398  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:36:22.398  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:36:22.408  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:36:22.408  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:36:22.408  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:36:22.408  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:36:22.418  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-20 17:36:22.418  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:36:22.428  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:36:22.428  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:36:22.428  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:36:22.428  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:36:22.428  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:36:24.918   288   288 E SMD     : DCD OFF,
,03-20 17:36:27.918   288   288 E SMD     : DCD OFF,
,03-20 17:36:28.678  1018  1322 E Watchdog: !@Sync 34
,03-20 17:36:30.918   288   288 E SMD     : DCD OFF
,03-20 17:36:31.608  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:36:32.458  1018  1345 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:36:32.458  1018  1345 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:36:32.458  1018  1345 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:36:32.458  1018  1345 D BatteryService: stay LED for fully charged
03-20 17:36:32.458  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:36:32.458  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:36:32.458  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:36:32.458  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:36:32.458  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:36:32.458  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:36:32.468  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:36:32.478  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:36:32.478  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:36:32.488  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:36:32.488  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:36:32.488  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:36:32.488  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:36:32.488  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:36:33.918   288   288 E SMD     : DCD OFF,
,03-20 17:36:36.918   288   288 E SMD     : DCD OFF,
,03-20 17:36:39.928   288   288 E SMD     : DCD OFF,
,03-20 17:36:41.628  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:36:42.508  1018  1351 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:36:42.518  1018  1351 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:36:42.518  1018  1351 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:36:42.518  1018  1351 D BatteryService: stay LED for fully charged
03-20 17:36:42.518  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:36:42.518  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:36:42.518  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:36:42.518  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:36:42.518  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:36:42.528  1018  1018 I MotionRecognitionService: Plugged,
03-20 17:36:42.528  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:36:42.528  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:36:42.528  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:36:42.538  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:36:42.538  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:36:42.548  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:36:42.548  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:36:42.548  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:36:42.928   288   288 E SMD     : DCD OFF,
,03-20 17:36:45.248  1018  1051 I PowerManagerService: [PWL] Off : 455s ago,
,03-20 17:36:45.928   288   288 E SMD     : DCD OFF,
,03-20 17:36:48.928   288   288 E SMD     : DCD OFF
,03-20 17:36:51.678  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:36:51.928   288   288 E SMD     : DCD OFF
,03-20 17:36:52.568  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:36:54.928   288   288 E SMD     : DCD OFF
,03-20 17:36:57.938   288   288 E SMD     : DCD OFF,
,03-20 17:36:58.688  1018  1322 E Watchdog: !@Sync 35
,03-20 17:37:00.938   288   288 E SMD     : DCD OFF,
,03-20 17:37:01.748  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:37:02.628  1018  1351 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:37:02.628  1018  1351 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:37:02.628  1018  1351 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:37:02.628  1018  1351 D BatteryService: stay LED for fully charged
03-20 17:37:02.628  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:37:02.638  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:37:02.638  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-20 17:37:02.638  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-20 17:37:02.638  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:37:02.648  1018  1018 I MotionRecognitionService: Plugged,
03-20 17:37:02.648  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:37:02.648  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:37:02.648  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:37:02.658  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:37:02.658  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:37:02.658  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:37:02.658  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:37:02.658  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:37:03.938   288   288 E SMD     : DCD OFF,
,03-20 17:37:06.938   288   288 E SMD     : DCD OFF,
,03-20 17:37:09.938   288   288 E SMD     : DCD OFF,
,03-20 17:37:11.758  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:37:12.688  1018  1546 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:37:12.688  1018  1546 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:37:12.688  1018  1546 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:37:12.688  1018  1546 D BatteryService: stay LED for fully charged
03-20 17:37:12.688  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:37:12.698  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-20 17:37:12.698  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:37:12.698  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-20 17:37:12.698  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:37:12.708  1018  1018 I MotionRecognitionService: Plugged
03-20 17:37:12.708  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:37:12.708  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,03-20 17:37:12.708  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:37:12.728  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,03-20 17:37:12.728  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:37:12.728  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:37:12.728  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:37:12.728  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:37:12.938   288   288 E SMD     : DCD OFF
,03-20 17:37:15.948   288   288 E SMD     : DCD OFF,
,03-20 17:37:18.948   288   288 E SMD     : DCD OFF,
,03-20 17:37:21.818  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:37:21.938   288   288 E SMD     : DCD OFF
,03-20 17:37:22.758  1018  1079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:37:22.758  1018  1079 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:37:22.758  1018  1079 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:37:22.758  1018  1079 D BatteryService: stay LED for fully charged
03-20 17:37:22.758  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:37:22.758  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:37:22.758  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:37:22.758  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:37:22.768  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-20 17:37:22.768  1018  1018 I MotionRecognitionService: Plugged
03-20 17:37:22.768  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:37:22.778  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:37:22.778  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:37:22.788  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:37:22.788  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:37:22.788  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:37:22.788  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:37:22.788  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:37:24.938   288   288 E SMD     : DCD OFF,
,03-20 17:37:27.948   288   288 E SMD     : DCD OFF,
,03-20 17:37:28.688  1018  1322 E Watchdog: !@Sync 36,
,03-20 17:37:30.938   288   288 E SMD     : DCD OFF,
,03-20 17:37:31.878  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:37:32.808  1018  1758 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:37:32.818  1018  1758 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:37:32.818  1018  1758 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:37:32.818  1018  1758 D BatteryService: stay LED for fully charged
,03-20 17:37:32.818  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:37:32.818  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:37:32.818  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:37:32.818  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:37:32.818  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:37:32.828  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:37:32.828  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:37:32.828  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:37:32.838  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:37:32.848  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:37:32.848  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:37:32.848  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:37:32.848  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:37:32.848  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:37:33.948   288   288 E SMD     : DCD OFF,
,03-20 17:37:36.948   288   288 E SMD     : DCD OFF,
,03-20 17:37:39.948   288   288 E SMD     : DCD OFF,
,03-20 17:37:41.898  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:37:42.868  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:37:42.868  1018  1501 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-20 17:37:42.868  1018  1501 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:37:42.868  1018  1501 D BatteryService: stay LED for fully charged
03-20 17:37:42.868  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:37:42.878  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:37:42.878  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:37:42.878  1018  1018 I MotionRecognitionService: Plugged
03-20 17:37:42.878  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:37:42.878  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-20 17:37:42.878  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:37:42.888  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:37:42.888  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:37:42.898  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:37:42.908  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:37:42.908  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:37:42.908  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:37:42.908  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:37:42.948   288   288 E SMD     : DCD OFF
,03-20 17:37:45.948   288   288 E SMD     : DCD OFF
,03-20 17:37:48.948   288   288 E SMD     : DCD OFF,
,03-20 17:37:51.958   288   288 E SMD     : DCD OFF,
03-20 17:37:51.958  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:37:52.928  1018  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:37:52.928  1018  1223 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:37:52.928  1018  1223 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:37:52.928  1018  1223 D BatteryService: stay LED for fully charged
,03-20 17:37:52.928  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:37:52.938  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:37:52.938  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:37:52.938  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:37:52.938  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
03-20 17:37:52.938  1018  1018 I MotionRecognitionService: Plugged
03-20 17:37:52.938  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:37:52.948  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-20 17:37:52.948  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:37:52.958  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:37:52.958  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:37:52.958  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:37:52.958  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:37:52.958  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:37:54.968   288   288 E SMD     : DCD OFF,
,03-20 17:37:55.238  1018  1051 I PowerManagerService: [PWL] Off : 525s ago,
,03-20 17:37:57.968   288   288 E SMD     : DCD OFF,
,03-20 17:37:58.688  1018  1322 E Watchdog: !@Sync 37,
,03-20 17:38:00.968   288   288 E SMD     : DCD OFF,
,03-20 17:38:02.018  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:38:02.988  1018  1542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:38:02.988  1018  1542 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:38:02.988  1018  1542 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:38:02.988  1018  1542 D BatteryService: stay LED for fully charged
03-20 17:38:02.988  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:38:02.998  1018  1018 I MotionRecognitionService: Plugged
03-20 17:38:02.998  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:38:02.998  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:38:02.998  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:38:02.998  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:38:02.998  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:38:03.008  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:38:03.008  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:38:03.018  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:38:03.028  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:38:03.028  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:38:03.028  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:38:03.028  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:38:03.968   288   288 E SMD     : DCD OFF,
,03-20 17:38:06.968   288   288 E SMD     : DCD OFF,
,03-20 17:38:09.968   288   288 E SMD     : DCD OFF,
,03-20 17:38:12.038  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:38:12.978   288   288 E SMD     : DCD OFF,
,03-20 17:38:13.058  1018  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-20 17:38:15.978   288   288 E SMD     : DCD OFF,
,03-20 17:38:18.978   288   288 E SMD     : DCD OFF,
,03-20 17:38:21.978   288   288 E SMD     : DCD OFF,
,03-20 17:38:22.098  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:38:23.108  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:38:24.978   288   288 E SMD     : DCD OFF,
,03-20 17:38:27.978   288   288 E SMD     : DCD OFF,
,03-20 17:38:28.698  1018  1322 E Watchdog: !@Sync 38,
,03-20 17:38:30.988   288   288 E SMD     : DCD OFF,
,03-20 17:38:32.168  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:38:33.178  1018  1758 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:38:33.178  1018  1758 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:38:33.178  1018  1758 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:38:33.178  1018  1758 D BatteryService: stay LED for fully charged,
03-20 17:38:33.178  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:38:33.178  1018  1018 I MotionRecognitionService: Plugged
03-20 17:38:33.178  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:38:33.188  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:38:33.188  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:38:33.188  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:38:33.188  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:38:33.198  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-20 17:38:33.198  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:38:33.218  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-20 17:38:33.218  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:38:33.218  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:38:33.218  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:38:33.218  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:38:33.988   288   288 E SMD     : DCD OFF,
,03-20 17:38:36.978   288   288 E SMD     : DCD OFF,
,03-20 17:38:39.988   288   288 E SMD     : DCD OFF,
,03-20 17:38:42.188  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:38:42.978   288   288 E SMD     : DCD OFF,
,03-20 17:38:43.248  1018  3043 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:38:43.248  1018  3043 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:38:43.248  1018  3043 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:38:43.248  1018  3043 D BatteryService: stay LED for fully charged
03-20 17:38:43.258  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:38:43.258  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:38:43.258  1018  1018 I MotionRecognitionService: Plugged
03-20 17:38:43.258  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:38:43.258  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:38:43.258  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:38:43.258  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:38:43.278  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:38:43.278  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:38:43.288  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:38:43.288  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:38:43.288  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:38:43.288  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:38:43.288  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:38:45.988   288   288 E SMD     : DCD OFF,
,03-20 17:38:48.998   288   288 E SMD     : DCD OFF,
,03-20 17:38:51.998   288   288 E SMD     : DCD OFF,
,03-20 17:38:52.248  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:38:53.318  1018  1541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:38:53.318  1018  1541 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:38:53.318  1018  1541 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:38:53.318  1018  1541 D BatteryService: stay LED for fully charged
,03-20 17:38:53.318  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:38:53.318  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:38:53.328  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:38:53.328  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:38:53.328  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:38:53.328  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:38:53.328  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:38:53.338  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:38:53.348  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:38:53.348  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:38:53.358  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:38:53.358  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:38:53.358  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:38:53.358  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:38:54.998   288   288 E SMD     : DCD OFF,
,03-20 17:38:57.998   288   288 E SMD     : DCD OFF,
,03-20 17:38:58.698  1018  1322 E Watchdog: !@Sync 39
,03-20 17:39:00.998   288   288 E SMD     : DCD OFF
,03-20 17:39:02.308  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:39:03.378  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:39:03.378  1018  1501 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:39:03.378  1018  1501 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:39:03.378  1018  1501 D BatteryService: stay LED for fully charged
03-20 17:39:03.378  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:39:03.378  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:39:03.378  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:39:03.378  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:39:03.378  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-20 17:39:03.388  1018  1018 I MotionRecognitionService: Plugged
03-20 17:39:03.388  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
03-20 17:39:03.388  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-20 17:39:03.388  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:39:03.408  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-20 17:39:03.408  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:39:03.408  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:39:03.408  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:39:03.408  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:39:03.998   288   288 E SMD     : DCD OFF
,03-20 17:39:06.998   288   288 E SMD     : DCD OFF,
,03-20 17:39:09.998   288   288 E SMD     : DCD OFF,
,03-20 17:39:10.258  1018  1051 I PowerManagerService: [PWL] Off : 600s ago,
,03-20 17:39:12.328  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:39:13.008   288   288 E SMD     : DCD OFF,
,03-20 17:39:13.438  1018  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:39:16.008   288   288 E SMD     : DCD OFF
,03-20 17:39:19.008   288   288 E SMD     : DCD OFF,
,03-20 17:39:22.008   288   288 E SMD     : DCD OFF,
,03-20 17:39:22.388  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:39:23.498  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:39:23.498  1018  1501 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:39:23.498  1018  1501 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:39:23.498  1018  1501 D BatteryService: stay LED for fully charged
03-20 17:39:23.498  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:39:23.508  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:39:23.508  1018  1018 I MotionRecognitionService: Plugged
03-20 17:39:23.508  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-20 17:39:23.508  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:39:23.508  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:39:23.508  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:39:23.518  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-20 17:39:23.518  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:39:23.528  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-20 17:39:23.528  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:39:23.528  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:39:23.528  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:39:23.528  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:39:25.008   288   288 E SMD     : DCD OFF
,03-20 17:39:26.388  1018  1043 I UsageStatsService: User[0] Flushing usage stats to disk
,03-20 17:39:26.418  1018  1088 D TimaService: TIMA: TimaService scheduler is intialized. 
,03-20 17:39:26.428  1018  1087 D TimaService: TimaServiceHandler.handleMessage what =1,
03-20 17:39:26.428  1018  1088 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-20 17:39:26.428  1018  1104 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,03-20 17:39:26.428  1018  1104 I ApplicationUsage: Updating Usage Statistics in DB @ 1458491966444
,03-20 17:39:26.438  1018  1104 I ApplicationPolicy: updateDataUsageMap
,03-20 17:39:26.668  1018  1104 I NetworkDataUsageDb: ::getAppControlDB: DB is Created 
,03-20 17:39:26.668  1018  1104 I NetworkDataUsageDb: ::isTableExists: Table exists 
,03-20 17:39:26.698  1018  1104 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1458491966709
,03-20 17:39:27.258  1018  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-20 17:39:27.258  1018  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-20 17:39:27.268  1018  1088 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-20 17:39:27.268  1018  1088 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-20 17:39:28.018   288   288 E SMD     : DCD OFF
,03-20 17:39:28.698  1018  1322 E Watchdog: !@Sync 40,
,03-20 17:39:31.018   288   288 E SMD     : DCD OFF,
,03-20 17:39:32.408  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:39:33.558  1018  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:39:33.558  1018  1223 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:39:33.558  1018  1223 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-20 17:39:33.558  1018  1223 D BatteryService: stay LED for fully charged
03-20 17:39:33.558  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:39:33.568  1018  1018 I MotionRecognitionService: Plugged,
03-20 17:39:33.568  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:39:33.568  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-20 17:39:33.568  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:39:33.578  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:39:33.578  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:39:33.588  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:39:33.588  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:39:33.598  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:39:33.598  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:39:33.598  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:39:33.598  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:39:33.598  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:39:34.018   288   288 E SMD     : DCD OFF
,03-20 17:39:37.018   288   288 E SMD     : DCD OFF,
,03-20 17:39:40.018   288   288 E SMD     : DCD OFF,
,03-20 17:39:42.438  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:39:43.018   288   288 E SMD     : DCD OFF,
,03-20 17:39:43.618  1018  1542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:39:43.618  1018  1542 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:39:43.618  1018  1542 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:39:43.618  1018  1542 D BatteryService: stay LED for fully charged
,03-20 17:39:43.618  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:39:43.628  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-20 17:39:43.628  1018  1018 I MotionRecognitionService: Plugged
03-20 17:39:43.628  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:39:43.628  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:39:43.628  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:39:43.628  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:39:43.638  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:39:43.638  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:39:43.648  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:39:43.648  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:39:43.648  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:39:43.648  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:39:43.648  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:39:46.028   288   288 E SMD     : DCD OFF,
,03-20 17:39:49.028   288   288 E SMD     : DCD OFF,
,03-20 17:39:52.028   288   288 E SMD     : DCD OFF,
,03-20 17:39:52.498  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:39:53.678  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:39:53.678  1018  1031 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:39:53.678  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:39:53.678  1018  1031 D BatteryService: stay LED for fully charged
03-20 17:39:53.678  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:39:53.678  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:39:53.678  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:39:53.688  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:39:53.688  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-20 17:39:53.688  1018  1018 I MotionRecognitionService: Plugged
03-20 17:39:53.688  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:39:53.698  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:39:53.698  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:39:53.708  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:39:53.708  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:39:53.708  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:39:53.708  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:39:53.708  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:39:55.028   288   288 E SMD     : DCD OFF,
,03-20 17:39:58.028   288   288 E SMD     : DCD OFF,
,03-20 17:39:58.698  1018  1322 E Watchdog: !@Sync 41,
,03-20 17:40:01.028   288   288 E SMD     : DCD OFF,
,03-20 17:40:02.558  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:40:03.738  1018  1345 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:40:03.738  1018  1345 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:40:03.738  1018  1345 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:40:03.738  1018  1345 D BatteryService: stay LED for fully charged,
03-20 17:40:03.738  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:40:03.748  1018  1018 I MotionRecognitionService: Plugged
03-20 17:40:03.748  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:40:03.748  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-20 17:40:03.748  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:40:03.748  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-20 17:40:03.748  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:40:03.758  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:40:03.758  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:40:03.768  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:40:03.778  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:40:03.778  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:40:03.778  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:40:03.778  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:40:04.038   288   288 E SMD     : DCD OFF
,03-20 17:40:07.038   288   288 E SMD     : DCD OFF,
,03-20 17:40:10.038   288   288 E SMD     : DCD OFF,
,03-20 17:40:12.578  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:40:13.038   288   288 E SMD     : DCD OFF,
,03-20 17:40:13.798  1018  1351 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:40:13.798  1018  1351 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:40:13.798  1018  1351 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:40:13.798  1018  1351 D BatteryService: stay LED for fully charged
03-20 17:40:13.798  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:40:13.808  1018  1018 I MotionRecognitionService: Plugged
03-20 17:40:13.808  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:40:13.808  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:40:13.808  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:40:13.808  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:40:13.808  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:40:13.818  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:40:13.818  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:40:13.828  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:40:13.828  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:40:13.828  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:40:13.828  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:40:13.828  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:40:16.038   288   288 E SMD     : DCD OFF,
,03-20 17:40:19.038   288   288 E SMD     : DCD OFF,
,03-20 17:40:22.048   288   288 E SMD     : DCD OFF,
,03-20 17:40:22.638  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:40:23.858  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:40:23.858  1018  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:40:23.858  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:40:23.858  1018  1030 D BatteryService: stay LED for fully charged
03-20 17:40:23.858  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:40:23.868  1018  1018 I MotionRecognitionService: Plugged
03-20 17:40:23.868  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:40:23.868  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:40:23.868  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:40:23.868  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:40:23.868  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:40:23.878  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:40:23.888  2629  2815 D HeadsetStateMachine: Disconnected process message: 10,
,03-20 17:40:23.898  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:40:23.898  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:40:23.898  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:40:23.898  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:40:23.898  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:40:25.048   288   288 E SMD     : DCD OFF,
,03-20 17:40:28.048   288   288 E SMD     : DCD OFF,
,03-20 17:40:28.688  1018  1322 E Watchdog: !@Sync 42,
,03-20 17:40:30.268  1018  1051 I PowerManagerService: [PWL] Off : 680s ago,
,03-20 17:40:31.048   288   288 E SMD     : DCD OFF,
,03-20 17:40:32.698  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:40:33.918  1018  1079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:40:33.928  1018  1079 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:40:33.928  1018  1079 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:40:33.928  1018  1079 D BatteryService: stay LED for fully charged
03-20 17:40:33.928  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:40:33.928  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-20 17:40:33.928  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:40:33.928  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:40:33.938  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:40:33.948  1018  1018 I MotionRecognitionService: Plugged
03-20 17:40:33.948  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:40:33.948  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-20 17:40:33.948  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:40:33.968  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:40:33.968  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:40:33.968  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:40:33.968  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:40:33.968  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:40:34.048   288   288 E SMD     : DCD OFF,
,03-20 17:40:37.048   288   288 E SMD     : DCD OFF,
,03-20 17:40:40.058   288   288 E SMD     : DCD OFF,
,03-20 17:40:42.718  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:40:43.058   288   288 E SMD     : DCD OFF,
,03-20 17:40:43.988  1018  1758 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:40:43.988  1018  1758 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:40:43.988  1018  1758 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:40:43.988  1018  1758 D BatteryService: stay LED for fully charged
03-20 17:40:43.988  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:40:43.988  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:40:43.988  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:40:43.998  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:40:43.998  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:40:44.008  1018  1018 I MotionRecognitionService: Plugged
03-20 17:40:44.008  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:40:44.008  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:40:44.008  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:40:44.028  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:40:44.028  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:40:44.028  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:40:44.028  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:40:44.028  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:40:46.058   288   288 E SMD     : DCD OFF
,03-20 17:40:49.058   288   288 E SMD     : DCD OFF,
,03-20 17:40:52.058   288   288 E SMD     : DCD OFF,
,03-20 17:40:52.778  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:40:54.048  1018  3043 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:40:54.048  1018  3043 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:40:54.048  1018  3043 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:40:54.048  1018  3043 D BatteryService: stay LED for fully charged
03-20 17:40:54.048  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:40:54.048  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:40:54.048  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:40:54.058  1018  1018 I MotionRecognitionService: Plugged
03-20 17:40:54.058  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:40:54.058  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:40:54.058  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:40:54.068  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:40:54.068  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:40:54.078  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-20 17:40:54.078  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:40:54.078  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:40:54.078  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:40:54.078  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:40:55.058   288   288 E SMD     : DCD OFF
,03-20 17:40:58.058   288   288 E SMD     : DCD OFF,
,03-20 17:40:58.698  1018  1322 E Watchdog: !@Sync 43
,03-20 17:41:01.058   288   288 E SMD     : DCD OFF,
,03-20 17:41:02.838  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:41:04.058   288   288 E SMD     : DCD OFF
,03-20 17:41:04.108  1018  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:41:04.108  1018  1223 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:41:04.108  1018  1223 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:41:04.108  1018  1223 D BatteryService: stay LED for fully charged
03-20 17:41:04.108  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:41:04.118  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:41:04.118  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:41:04.118  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:41:04.118  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:41:04.128  1018  1018 I MotionRecognitionService: Plugged,
03-20 17:41:04.128  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:41:04.128  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:41:04.128  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:41:04.138  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:41:04.138  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:41:04.138  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:41:04.138  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:41:04.138  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:41:07.058   288   288 E SMD     : DCD OFF,
,03-20 17:41:10.058   288   288 E SMD     : DCD OFF,
,03-20 17:41:12.868  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:41:13.058   288   288 E SMD     : DCD OFF,
,03-20 17:41:14.168  1018  1542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:41:14.168  1018  1542 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:41:14.168  1018  1542 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:41:14.168  1018  1542 D BatteryService: stay LED for fully charged
03-20 17:41:14.168  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:41:14.168  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:41:14.168  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:41:14.168  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:41:14.168  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-20 17:41:14.178  1018  1018 I MotionRecognitionService: Plugged,
03-20 17:41:14.178  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:41:14.188  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-20 17:41:14.188  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:41:14.198  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-20 17:41:14.198  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:41:14.198  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:41:14.198  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:41:14.198  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:41:16.068   288   288 E SMD     : DCD OFF,
,03-20 17:41:19.078   288   288 E SMD     : DCD OFF,
,03-20 17:41:22.078   288   288 E SMD     : DCD OFF,
,03-20 17:41:22.928  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:41:24.228  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-20 17:41:25.078   288   288 E SMD     : DCD OFF
,03-20 17:41:28.078   288   288 E SMD     : DCD OFF,
,03-20 17:41:28.698  1018  1322 E Watchdog: !@Sync 44,
,03-20 17:41:31.078   288   288 E SMD     : DCD OFF,
,03-20 17:41:32.978  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:41:34.068   288   288 E SMD     : DCD OFF,
,03-20 17:41:34.278  1018  1542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:41:34.278  1018  1542 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:41:34.278  1018  1542 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:41:34.278  1018  1542 D BatteryService: stay LED for fully charged
03-20 17:41:34.278  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:41:34.288  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-20 17:41:34.288  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:41:34.288  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:41:34.288  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:41:34.288  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:41:34.298  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:41:34.298  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:41:34.298  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:41:34.308  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:41:34.308  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:41:34.308  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:41:34.308  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:41:34.308  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:41:37.088   288   288 E SMD     : DCD OFF
,03-20 17:41:40.088   288   288 E SMD     : DCD OFF,
,03-20 17:41:43.008  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:41:43.078   288   288 E SMD     : DCD OFF,
,03-20 17:41:44.348  1018  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:41:44.348  1018  1487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:41:44.348  1018  1487 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:41:44.348  1018  1487 D BatteryService: stay LED for fully charged
03-20 17:41:44.348  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:41:44.348  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:41:44.348  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-20 17:41:44.348  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:41:44.348  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-20 17:41:44.358  1018  1018 I MotionRecognitionService: Plugged
03-20 17:41:44.358  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:41:44.368  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-20 17:41:44.368  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:41:44.388  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:41:44.388  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:41:44.388  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:41:44.388  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:41:44.388  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:41:46.088   288   288 E SMD     : DCD OFF,
,03-20 17:41:49.088   288   288 E SMD     : DCD OFF,
,03-20 17:41:52.088   288   288 E SMD     : DCD OFF,
,03-20 17:41:53.058  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:41:54.408  1018  1545 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:41:54.408  1018  1545 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:41:54.408  1018  1545 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-20 17:41:54.408  1018  1545 D BatteryService: stay LED for fully charged
03-20 17:41:54.408  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:41:54.408  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-20 17:41:54.408  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:41:54.418  1018  1018 I MotionRecognitionService: Plugged
03-20 17:41:54.418  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:41:54.418  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:41:54.418  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:41:54.428  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:41:54.428  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:41:54.448  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:41:54.448  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:41:54.448  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:41:54.448  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:41:54.448  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:41:55.098   288   288 E SMD     : DCD OFF
,03-20 17:41:55.268  1018  1051 I PowerManagerService: [PWL] Off : 765s ago
,03-20 17:41:58.098   288   288 E SMD     : DCD OFF
,03-20 17:41:58.698  1018  1322 E Watchdog: !@Sync 45
,03-20 17:42:01.098   288   288 E SMD     : DCD OFF,
,03-20 17:42:03.118  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:42:04.098   288   288 E SMD     : DCD OFF,
,03-20 17:42:04.458  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:42:04.468  1018  1031 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:42:04.468  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:42:04.468  1018  1031 D BatteryService: stay LED for fully charged
03-20 17:42:04.468  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:42:04.468  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-20 17:42:04.468  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:42:04.468  1018  1018 I MotionRecognitionService: Plugged
03-20 17:42:04.468  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:42:04.468  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-20 17:42:04.468  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:42:04.478  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:42:04.478  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:42:04.488  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:42:04.488  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:42:04.488  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:42:04.488  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:42:04.488  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:42:07.098   288   288 E SMD     : DCD OFF,
,03-20 17:42:10.098   288   288 E SMD     : DCD OFF,
,03-20 17:42:13.098   288   288 E SMD     : DCD OFF,
,03-20 17:42:13.148  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:42:14.518  1018  1345 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:42:14.518  1018  1345 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:42:14.518  1018  1345 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
03-20 17:42:14.518  1018  1345 D BatteryService: stay LED for fully charged
03-20 17:42:14.528  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:42:14.518  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:42:14.528  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:42:14.528  1018  1018 I MotionRecognitionService: Plugged
03-20 17:42:14.528  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:42:14.528  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-20 17:42:14.528  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:42:14.548  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:42:14.548  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:42:14.558  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:42:14.558  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:42:14.558  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:42:14.558  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:42:14.558  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:42:16.108   288   288 E SMD     : DCD OFF
,03-20 17:42:19.108   288   288 E SMD     : DCD OFF,
,03-20 17:42:22.108   288   288 E SMD     : DCD OFF,
,03-20 17:42:23.168  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:42:24.578  1018  1351 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:42:25.098   288   288 E SMD     : DCD OFF
,03-20 17:42:28.108   288   288 E SMD     : DCD OFF
,03-20 17:42:28.698  1018  1322 E Watchdog: !@Sync 46
,03-20 17:42:31.108   288   288 E SMD     : DCD OFF
,03-20 17:42:33.228  1018  2718 D SSRM:n  : SIOP:: AP = 260
,03-20 17:42:34.118   288   288 E SMD     : DCD OFF
,03-20 17:42:34.638  1018  1545 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:42:37.118   288   288 E SMD     : DCD OFF
,03-20 17:42:40.118   288   288 E SMD     : DCD OFF,
,03-20 17:42:43.118   288   288 E SMD     : DCD OFF,
,03-20 17:42:43.268  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:42:44.698  1018  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:42:44.698  1018  1223 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:42:44.698  1018  1223 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:42:44.698  1018  1223 D BatteryService: stay LED for fully charged,
03-20 17:42:44.698  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:42:44.708  1018  1018 I MotionRecognitionService: Plugged
,03-20 17:42:44.708  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:42:44.708  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:42:44.708  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:42:44.718  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:42:44.718  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:42:44.728  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:42:44.728  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:42:44.748  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:42:44.748  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:42:44.748  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:42:44.748  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:42:44.748  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:42:46.118   288   288 E SMD     : DCD OFF
,03-20 17:42:49.118   288   288 E SMD     : DCD OFF,
,03-20 17:42:52.128   288   288 E SMD     : DCD OFF,
,03-20 17:42:53.278  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:42:54.758  1018  1542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:42:54.758  1018  1542 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:42:54.758  1018  1542 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:42:54.758  1018  1542 D BatteryService: stay LED for fully charged,
03-20 17:42:54.758  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-20 17:42:54.758  1018  1018 I MotionRecognitionService: Plugged
03-20 17:42:54.768  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:42:54.758  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:42:54.768  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:42:54.768  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-20 17:42:54.768  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:42:54.778  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:42:54.778  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:42:54.788  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:42:54.788  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:42:54.788  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:42:54.788  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:42:54.798  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:42:55.128   288   288 E SMD     : DCD OFF,
,03-20 17:42:58.128   288   288 E SMD     : DCD OFF,
,03-20 17:42:58.698  1018  1322 E Watchdog: !@Sync 47,
,03-20 17:43:01.128   288   288 E SMD     : DCD OFF,
,03-20 17:43:03.338  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:43:04.128   288   288 E SMD     : DCD OFF,
,03-20 17:43:04.818  1018  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-20 17:43:04.818  1018  1487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:43:04.818  1018  1487 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:43:04.818  1018  1487 D BatteryService: stay LED for fully charged
03-20 17:43:04.818  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-20 17:43:04.818  1018  1018 I MotionRecognitionService: Plugged
03-20 17:43:04.818  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:43:04.828  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:43:04.828  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:43:04.828  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:43:04.828  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:43:04.838  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-20 17:43:04.838  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:43:04.848  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-20 17:43:04.848  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:43:04.848  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:43:04.848  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:43:04.848  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:43:07.128   288   288 E SMD     : DCD OFF
,03-20 17:43:10.138   288   288 E SMD     : DCD OFF,
,03-20 17:43:13.138   288   288 E SMD     : DCD OFF,
,03-20 17:43:13.358  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:43:14.878  1018  1545 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:43:14.878  1018  1545 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:43:14.878  1018  1545 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:43:14.878  1018  1545 D BatteryService: stay LED for fully charged
03-20 17:43:14.878  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:43:14.878  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:43:14.878  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-20 17:43:14.878  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:43:14.888  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 17:43:14.888  1018  1018 I MotionRecognitionService: Plugged
03-20 17:43:14.888  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-20 17:43:14.888  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:43:14.888  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:43:14.898  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:43:14.898  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:43:14.898  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:43:14.898  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:43:14.898  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:43:16.138   288   288 E SMD     : DCD OFF,
,03-20 17:43:19.138   288   288 E SMD     : DCD OFF,
,03-20 17:43:22.138   288   288 E SMD     : DCD OFF,
,03-20 17:43:23.418  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:43:24.928  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 17:43:24.938  1018  1031 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-20 17:43:24.938  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:43:24.938  1018  1031 D BatteryService: stay LED for fully charged
,03-20 17:43:24.938  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-20 17:43:24.938  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-20 17:43:24.938  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:43:24.938  1018  1018 I MotionRecognitionService: Plugged
03-20 17:43:24.938  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:43:24.938  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-20 17:43:24.938  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:43:24.948  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:43:24.948  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:43:24.958  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:43:24.958  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:43:24.968  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-20 17:43:24.968  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-20 17:43:24.968  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:43:25.138   288   288 E SMD     : DCD OFF,
,03-20 17:43:25.268  1018  1051 I PowerManagerService: [PWL] Off : 855s ago,
,03-20 17:43:28.138   288   288 E SMD     : DCD OFF,
,03-20 17:43:28.698  1018  1322 E Watchdog: !@Sync 48,
,03-20 17:43:31.138   288   288 E SMD     : DCD OFF,
,03-20 17:43:33.468  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:43:34.148   288   288 E SMD     : DCD OFF,
,03-20 17:43:34.998  1018  1345 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-20 17:43:37.138   288   288 E SMD     : DCD OFF,
,03-20 17:43:40.148   288   288 E SMD     : DCD OFF,
,03-20 17:43:43.148   288   288 E SMD     : DCD OFF,
,03-20 17:43:43.508  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:43:45.058  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-20 17:43:46.148   288   288 E SMD     : DCD OFF,
,03-20 17:43:49.158   288   288 E SMD     : DCD OFF,
,03-20 17:43:52.148   288   288 E SMD     : DCD OFF,
,03-20 17:43:53.578  1018  2718 D SSRM:n  : SIOP:: AP = 260,
,03-20 17:43:55.118  1018  1542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-20 17:43:55.118  1018  1542 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-20 17:43:55.118  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 17:43:55.118  1018  1542 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-20 17:43:55.118  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-20 17:43:55.118  1018  1542 D BatteryService: stay LED for fully charged
03-20 17:43:55.118  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 17:43:55.118  1018  1018 I MotionRecognitionService: Plugged,
03-20 17:43:55.118  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-20 17:43:55.118  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 17:43:55.118  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-20 17:43:55.128  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:43:55.138  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-20 17:43:55.138  2629  2815 D HeadsetStateMachine: Disconnected process message: 10
,03-20 17:43:55.148  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-20 17:43:55.148  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-20 17:43:55.148  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-20 17:43:55.148  1178  1178 D SViewCoverView: level :100 plugged : 2
,03-20 17:43:55.148   288   288 E SMD     : DCD OFF
,03-20 17:43:58.158   288   288 E SMD     : DCD OFF
,TIME-OUT KILL (timeout was 1400000ms),03-20 17:43:58.698  1018  1322 E Watchdog: !@Sync 49
03-20 17:43:58.808  6360  6360 D AndroidRuntime: 
03-20 17:43:58.808  6360  6360 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-20 17:43:58.808  6360  6360 D AndroidRuntime: CheckJNI is OFF
03-20 17:43:58.808  6360  6360 D AndroidRuntime: readGMSProperty: start
03-20 17:43:58.808  6360  6360 D AndroidRuntime: readGMSProperty: already setted!!
03-20 17:43:58.808  6360  6360 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-20 17:43:58.808  6360  6360 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-20 17:43:58.808  6360  6360 D AndroidRuntime: readGMSProperty: end
03-20 17:43:58.808  6360  6360 D AndroidRuntime: addProductProperty: start
03-20 17:43:58.938  6360  6360 E AffinityControl: AffinityControl: registerfunction enter
03-20 17:43:58.968  6360  6360 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
03-20 17:43:58.988  1018  1758 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-20 17:43:58.988  1018  1758 D PackageManager: START PACKAGE DELETE: observer{75711894}
03-20 17:43:58.988  1018  1758 D PackageManager: pkg{<packageName>}
03-20 17:43:58.988  1018  1758 D PackageManager: user{0}
03-20 17:43:58.988  1018  1758 D PackageManager: caller{2000}
03-20 17:43:58.988  1018  1758 D PackageManager: flags{2}
03-20 17:43:58.988  1018  1758 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-20 17:43:58.988  1018  1758 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-20 17:43:58.988  1018  1758 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-20 17:43:58.988  1018  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-20 17:43:58.988  1018  1758 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-20 17:43:58.988  1018  1758 I PackageManager: Package doesn't exist in get block uninstall com.test.thalitest
03-20 17:43:58.988  1018  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-20 17:43:58.988  1018  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-20 17:43:58.998  1018  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
03-20 17:43:58.998  1018  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
03-20 17:43:59.008  1018  1057 W PackageManager: Package named 'com.test.thalitest' doesn't exist.
03-20 17:43:59.168  1018  1057 I art     : Explicit concurrent mark sweep GC freed 24056(2MB) AllocSpace objects, 102(1633KB) LOS objects, 33% free, 21MB/32MB, paused 2.055ms total 160.260ms
03-20 17:43:59.168  1018  1057 D PackageManager: result of delete: -1{75711894}
03-20 17:43:59.168  6360  6360 E Pm      : Failure details: Bundle[{android.content.pm.extra.STATUS=1, android.content.pm.extra.PACKAGE_NAME=com.test.thalitest, android.content.pm.extra.LEGACY_STATUS=-1, android.content.pm.extra.STATUS_MESSAGE=DELETE_FAILED_INTERNAL_ERROR}]
03-20 17:43:59.168  6360  6360 D AndroidRuntime: Shutting down VM
03-20 17:43:59.378  6360  6360 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.

```
