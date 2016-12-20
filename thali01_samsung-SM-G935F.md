#### Test 98694118431693a_thali01_samsung-SM-G935F Logs


```
--------- beginning of system
12-20 11:53:17.901  3509  6576 D SSRM:n  : SIOP:: AP = 320, PST = 377 (W:10), CP = 274, CUR = 6, LCD = 105
,--------- beginning of main
12-20 11:53:18.481  9533  9533 I FIPS_bssl: FIPS approved mode (1) | 9533 | app_process
12-20 11:53:18.481  9533  9533 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
12-20 11:53:18.491  9533  9533 D AndroidRuntime: CheckJNI is OFF
12-20 11:53:18.491  9533  9533 D AndroidRuntime: readGMSProperty: start
12-20 11:53:18.491  9533  9533 D AndroidRuntime: readGMSProperty: already setted!!
12-20 11:53:18.491  9533  9533 D AndroidRuntime: propertySet: couldn't set property (it is from app)
12-20 11:53:18.491  9533  9533 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
12-20 11:53:18.491  9533  9533 D AndroidRuntime: readGMSProperty: end
12-20 11:53:18.491  9533  9533 D AndroidRuntime: addProductProperty: start
12-20 11:53:18.511  9533  9533 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
12-20 11:53:18.541  9533  9533 I Radio-JNI: register_android_hardware_Radio DONE
12-20 11:53:18.541  9533  9533 E AffinityControl: AffinityControl: registerfunction enter
12-20 11:53:18.551  9533  9533 D AndroidRuntime: Calling main entry com.android.commands.am.Am
12-20 11:53:18.581  9533  9533 D AndroidRuntime: Shutting down VM
,12-20 11:53:19.381  3509  3791 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-20 11:53:19.391  3509  3791 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4345, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:53:19.391  3509  3791 D BatteryService: online:4, current avg:51, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:153
12-20 11:53:19.391  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:53:19.391  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:53:19.391  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:53:19.391  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:53:19.391  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:53:19.401  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:53:19.401  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-20 11:53:19.401  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:53:19.401  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:53:19.401  3960  3960 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
12-20 11:53:19.401  3960  3960 D PowerUI.Notification: There is no change about charging status, so return!
,12-20 11:53:19.411  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:53:19.411  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-20 11:53:19.411  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:53:19.421  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:53:19.431  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-20 11:53:19.431  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-20 11:53:20.061  3509  3836 V AlarmManager: Expired Alarm result :4
,12-20 11:53:20.071  3509  3593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{da710c7 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6fe7727 4355:com.google.android.gms.persistent/u0a21}
,12-20 11:53:20.101  3509  4434 V AlarmManager:  remove PendingIntent] PendingIntent{967ae1d: PendingIntentRecord{34ce2ab com.google.android.gms broadcastIntent}}
,12-20 11:53:20.151  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: true, uidstate: 3, mProxSensorScreenOff: false
,12-20 11:53:20.161  4194  4205 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.googlequicksearchbox,id=10436,extra=Bundle[mParcelledData.dataSize=84]
12-20 11:53:20.161  4194  4194 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.googlequicksearchbox}]
12-20 11:53:20.161  4194  4194 I PeopleStripeService: PeopleNotificationReceiver:3
,12-20 11:53:20.161  4194  4194 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
12-20 11:53:20.161  4194  4194 I PeopleDataManager: removeNotification
12-20 11:53:20.161  4194  4194 I NotificationParser: getNotiType:com.google.android.googlequicksearchbox,null
12-20 11:53:20.161  4194  4194 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.googlequicksearchbox,isEdgeNotification=false,key=null,removeAll=false
12-20 11:53:20.161  4194  4194 D PeopleDataManager: removeNotiInfo =null
,12-20 11:53:20.211  3509  4486 V AlarmManager:  remove PendingIntent] PendingIntent{3943bde: PendingIntentRecord{34ce2ab com.google.android.gms broadcastIntent}}
,12-20 11:53:20.371  4355  9552 I VacuumService: Vacuum at: now=1482231200388 tag=VacuumService
,12-20 11:53:20.461  3509  3791 V AlarmManager:  remove PendingIntent] PendingIntent{62f83d5: PendingIntentRecord{34ce2ab com.google.android.gms broadcastIntent}}
,12-20 11:53:24.661  3509  6631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-20 11:53:27.951  3509  6576 D SSRM:n  : SIOP:: AP = 310, PST = 358 (W:10), CP = 271, CUR = 51, LCD = 105
,12-20 11:53:29.431  3509  4092 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-20 11:53:29.431  3509  4092 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4347, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:53:29.431  3509  4092 D BatteryService: online:4, current avg:114, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:119
12-20 11:53:29.431  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:53:29.441  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:53:29.441  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:53:29.441  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:53:29.441  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:53:29.451  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:53:29.451  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-20 11:53:29.451  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:53:29.451  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:53:29.451  3960  3960 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,12-20 11:53:29.451  3960  3960 D PowerUI.Notification: There is no change about charging status, so return!
,12-20 11:53:29.481  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:53:29.481  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:53:29.481  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:53:29.491  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:53:29.491  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
12-20 11:53:29.491  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-20 11:53:33.981  3509  3619 D PowerManagerService: [s] UserActivityState : 1 -> 2
12-20 11:53:33.981  3509  3619 D PowerManagerService: mDisplayReady: false
12-20 11:53:33.981  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:53:33.981  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:53:33.981  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:53:33.981  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:53:33.981  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:53:33.981  3509  3619 D PowerManagerService: mDisplayReady: true
,12-20 11:53:33.991  3509  3927 D lights  : lcd : 101 +
,12-20 11:53:34.001  3509  3927 D lights  : lcd : 101 -
,12-20 11:53:34.001  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:53:34.001  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:53:34.001  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
,12-20 11:53:34.001  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:53:34.011  3509  3927 D lights  : lcd : 93 +
,12-20 11:53:34.011  3509  3927 D lights  : lcd : 93 -
,12-20 11:53:34.011  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:53:34.011  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,12-20 11:53:34.011  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:53:34.011  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:53:34.031  3509  3927 D lights  : lcd : 84 +
12-20 11:53:34.031  3509  3927 D lights  : lcd : 84 -
12-20 11:53:34.031  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:53:34.031  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:53:34.031  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:53:34.031  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:53:34.041  3509  3927 D lights  : lcd : 76 +
,12-20 11:53:34.051  3509  3927 D lights  : lcd : 76 -
,12-20 11:53:34.051  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:53:34.051  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:53:34.051  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:53:34.051  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:53:34.061  3509  3927 D lights  : lcd : 68 +
,12-20 11:53:34.061  3509  3927 D lights  : lcd : 68 -
,12-20 11:53:34.061  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:53:34.061  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:53:34.061  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
,12-20 11:53:34.061  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:53:34.081  3509  3927 D lights  : lcd : 59 +
,12-20 11:53:34.081  3509  3927 D lights  : lcd : 59 -
,12-20 11:53:34.081  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:53:34.081  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,12-20 11:53:34.081  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:53:34.081  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:53:34.091  3509  3927 D lights  : lcd : 57 +
,12-20 11:53:34.091  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:53:34.091  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:53:34.091  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:53:34.091  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:53:34.101  3509  3927 D lights  : lcd : 57 -
,12-20 11:53:34.101  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:53:34.101  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:53:34.101  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
,12-20 11:53:34.101  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:53:38.001  3509  6576 D SSRM:n  : SIOP:: AP = 310, PST = 339 (W:10), CP = 268, CUR = 114, LCD = 57
,12-20 11:53:39.491  3509  3530 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-20 11:53:39.491  3509  3530 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4351, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:53:39.491  3509  3530 D BatteryService: online:4, current avg:149, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:203
12-20 11:53:39.491  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:53:39.501  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:53:39.501  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:53:39.501  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:53:39.501  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:53:39.501  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:53:39.511  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-20 11:53:39.511  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:53:39.511  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:53:39.511  3960  3960 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,12-20 11:53:39.511  3960  3960 D PowerUI.Notification: There is no change about charging status, so return!
,12-20 11:53:39.521  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-20 11:53:39.521  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:53:39.531  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-20 11:53:39.531  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:53:39.531  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:53:39.551  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,12-20 11:53:39.991  3509  3619 D PowerManagerService: [s] UserActivityState : 2 -> 4
,12-20 11:53:39.991  3509  3619 I PowerManagerService: Nap time (uid 1000)...
12-20 11:53:39.991  3509  3619 D InputManager-JNI: setInteractive(false)
,12-20 11:53:39.991  3509  3619 D PowerManagerService: handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
12-20 11:53:39.991  3509  3619 I PowerManagerService: !@[ps] Screen__Off - 1 :  dream(timeout) (2)
,12-20 11:53:39.991  3960  4430 D KeyguardViewMediator: onStartedGoingToSleep(3)
,12-20 11:53:39.991  3509  3619 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
12-20 11:53:39.991  3018  3018 I SurfaceFlinger: id=21 createSurf (1440x2560),2 flag=404, DolorFade
,12-20 11:53:39.991  3509  3619 D PowerManagerService: mDisplayReady: false
12-20 11:53:39.991  3509  3924 D NetworkPolicy: onScreenStateChanged, state: false, reason: 3
12-20 11:53:39.991  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=1
,12-20 11:53:39.991  3509  3619 D ColorFade: prepare: mode=4
,12-20 11:53:39.991  3509  3619 D PowerManagerUtil: Excessive delay in ColorFade : createSurface: 13ms
12-20 11:53:40.001  7178  7178 D SamsungIME: IMPL finishInput
12-20 11:53:40.001  7178  7178 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
12-20 11:53:40.001  7178  7178 D SamsungIME: saveAndClear +
12-20 11:53:40.001  7178  7178 D SamsungIME: saveAndClear -
,12-20 11:53:40.001  3509  3619 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1,
,12-20 11:53:40.001  3509  3619 D PowerManagerUtil: Excessive delay in ColorFade : createEglSurface: 10ms
,12-20 11:53:40.011  7178  7178 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,12-20 11:53:40.021  3960  4430 E KeyguardViewMediator: lockAfterTimeout = 5000 policyTimeout = 0
,12-20 11:53:40.021  3960  4430 D KeyguardViewMediator: timeout : 5000
,12-20 11:53:40.031  3960  4430 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 2
,12-20 11:53:40.031  3960  4430 D KeyguardViewMediator: notifyStartedGoingToSleep
12-20 11:53:40.031  3960  3960 V KeyguardFingerPrint: updateFingerprintListeningState(false)
,12-20 11:53:40.031  3960  3960 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
,12-20 11:53:40.031  3960  3960 V KeyguardUpdateMonitor: stopListeningForFingerprint()
12-20 11:53:40.031  3960  3960 D KeyguardViewMediator: handleNotifyStartedGoingToSleep
,12-20 11:53:40.051  3509  3619 D libEGL  : eglInitialize EGLDisplay = 0x7f9693e778
,12-20 11:53:40.051  3509  3619 D libEGL  : eglTerminate EGLDisplay = 0x7f9693e8e8
,12-20 11:53:40.061  3509  3619 D ColorFade: ColorFade is ready
12-20 11:53:40.061  3509  3619 D DisplayPowerController: ColorFade: onAnimationStart
12-20 11:53:40.061  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:53:40.061  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 105 -> 105
,12-20 11:53:40.091  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:53:40.111  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:53:40.121  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:53:40.361  3509  3619 D DisplayPowerState: !@ [0] ColorFade entry
12-20 11:53:40.361  3509  3619 D PowerManagerService: [input device light] onColorFadeExit(false)
12-20 11:53:40.371  3509  3619 D DisplayPowerController: ColorFade: onAnimationEnd
,12-20 11:53:40.371  3509  3927 D lights  : lcd : 0 +
12-20 11:53:40.371  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=1
,12-20 11:53:40.371  3509  3619 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_* -> REPORTED_TO_POLICY_SCREEN_OFF.
,12-20 11:53:40.381  4328  4328 D Launcher: onPause, Launcher: 188281550
,12-20 11:53:40.381  4328  4328 D Launcher.HomeView: onPause
,12-20 11:53:40.381  4328  4328 D Launcher.Workspace: exitWidgetResizeMode. isClearResizeFrame is false
,12-20 11:53:40.391  3509  3927 D lights  : lcd : 0 -
,12-20 11:53:40.501  3509  3619 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@a2f52d0, Service = Auto Rotation, used = 0
12-20 11:53:40.511  3509  3619 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for AUTO_ROTATION
12-20 11:53:40.511  3509  3619 V CAE     : stop(ContextProvider.java:155)
,12-20 11:53:40.511  3509  3619 V CAE     : clear(AutoRotationRunner.java:182)
12-20 11:53:40.511  3509  3619 V CAE     : disable(AutoRotationRunner.java:171)
12-20 11:53:40.511  3509  3619 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 7, 0, 0,
12-20 11:53:40.511  3509  3619 D SensorHubManager: SendSensorHubData: send data = -78, 7, 0, 0
,12-20 11:53:40.511  3182  7712 D Sensorhubs: sendContextData: -78, 7, 0, 0
,12-20 11:53:40.521  4328  4328 V ActivityThread: updateVisibility : ActivityRecord{2719980 token=android.os.BinderProxy@72d1b85 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
,12-20 11:53:40.521  4328  4328 D Launcher.HomeView: onStop
,12-20 11:53:40.521  4328  4328 D capture : ----destroy
,12-20 11:53:40.531  3509  3619 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
12-20 11:53:40.531  3509  3619 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:53:40.531  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
,12-20 11:53:40.541  3509  3619 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:53:40.541  3509  3619 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,12-20 11:53:40.541  3509  3619 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
12-20 11:53:40.541  3509  3619 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
12-20 11:53:40.541  3509  3619 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER(1)
12-20 11:53:40.541  3509  3619 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@5a8a4b8, Service : AUTO_BRIGHTNESS(1)
12-20 11:53:40.541  3509  3619 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
12-20 11:53:40.541  3509  3619 D SContextService: 	.unregisterCallback : 3, client=
12-20 11:53:40.541  3509  3619 D SContextService: ===== SContext Service List =====
12-20 11:53:40.541  3509  3619 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@94e6291, Service : Auto Brightness
12-20 11:53:40.541  3509  3619 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@b62dce, Service : Activity Tracker
12-20 11:53:40.541  3509  3619 D SContextManager:   .unregisterListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@8adcaff, service=Auto Rotation
12-20 11:53:40.541  3509  3619 V KeyguardServiceDelegate: onScreenTurnedOff()
12-20 11:53:40.541  3960  3977 D KeyguardViewMediator: notifyScreenTurnedOff
12-20 11:53:40.541  3960  3960 D KeyguardViewMediator: handleNotifyScreenTurnedOff
12-20 11:53:40.541  3960  3960 D vol.SecVolumeDialog: onScreenTurnedOff()
12-20 11:53:40.541  3960  3960 D vol.SecVolumeDialog: dismissH reason: 4
12-20 11:53:40.541  3960  3960 D vol.SecVolumeDialog: dismissH : false
,12-20 11:53:40.551  3509  3619 D DisplayPowerController: mWindowManagerPolicy.screenTurnedOff(0)
,12-20 11:53:40.551  3509  3926 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@94e6291, Service = Auto Brightness, used = 0
12-20 11:53:40.551  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
,12-20 11:53:40.551  3509  3926 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for AUTO_BRIGHTNESS
12-20 11:53:40.551  3509  3619 D PowerManagerUtil: fileWriteInt to /sys/class/tcon/tcon/auto_br, 0
12-20 11:53:40.551  3509  3926 V CAE     : stop(ContextProvider.java:155)
,12-20 11:53:40.551  3509  3619 D PowerManagerUtil: fileWriteInt to /sys/class/backlight/panel/auto_brightness, 0
12-20 11:53:40.551  3509  3926 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : unregisterListenerRunnable
,12-20 11:53:40.551  3509  3595 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 com.android.server.policy.sec.SamsungPhoneWindowManager$22.run:4527 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:158 
12-20 11:53:40.551  3509  3926 V CAE     : clear(AutoBrightnessRunner.java:297)
,12-20 11:53:40.551  3509  3926 V CAE     : disable(AutoBrightnessRunner.java:286)
12-20 11:53:40.551  4748  4748 I AODService: onStartCommand : action : com.samsung.android.app.aodservice.intent.action.AOD_SCREEN_OFF
12-20 11:53:40.551  3509  3619 D PowerManagerUtil: fileWriteInt to /sys/class/mdnie/mdnie/auto_brightness, 0
12-20 11:53:40.551  4748  4748 I AODService: onCreate cause: [12-20 11:51:46.639][AOD:true, NightClock:false]<com.samsung.android.app.aodservice.intent.action.AOD_SCREEN_ON> (when Screen on ...)
,12-20 11:53:40.551  3509  3619 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
12-20 11:53:40.551  3509  3926 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 48, 0, 0,
12-20 11:53:40.551  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
12-20 11:53:40.551  3509  3926 D SensorHubManager: SendSensorHubData: send data = -78, 48, 0, 0
12-20 11:53:40.551  3509  3619 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:53:40.551  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=1
12-20 11:53:40.551  3182  3182 D Sensorhubs: sendContextData: -78, 48, 0, 0
,12-20 11:53:40.551  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
12-20 11:53:40.551  3509  9565 D MISC PowerHAL: sysfs_write +: /sys/class/input/event0/device/enabled: 0
12-20 11:53:40.551  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
12-20 11:53:40.551  3509  3619 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:53:40.561  3509  9566 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 0
12-20 11:53:40.561  3509  9565 D MISC PowerHAL: sysfs_write -: /sys/class/input/event0/device/enabled: 0
12-20 11:53:40.561  3509  3626 D DisplayManagerService: !@display_state: ON -> OFF brightness: 0 -> 0
12-20 11:53:40.561  3509  9566 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 0
12-20 11:53:40.561  3509  3615 I DisplayManagerService: Display device changed state: "Wbudowany ekran", OFF
12-20 11:53:40.561  3509  3626 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
12-20 11:53:40.561  3509  3615 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", OFF
12-20 11:53:40.561  3509  3626 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,12-20 11:53:40.571  3018  3018 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7fa9d43c00
,12-20 11:53:40.571  3018  3018 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(0)
,12-20 11:53:40.581  3509  3926 D CAE     : getFaultDetectionResult(AutoBrightnessRunner.java:311) - true
,12-20 11:53:40.581  3509  3926 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:53:40.601  3960  3960 D ImageWallpaper: onVisibilityChanged:false
,12-20 11:53:40.601  6319  6319 E CocktailBarPositionManager: Window direction: 0
12-20 11:53:40.601  6319  6319 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-20 11:53:40.601  3960  3960 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
12-20 11:53:40.601  3960  3960 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
12-20 11:53:40.601  3960  3960 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,12-20 11:53:40.601  3509  3926 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:53:40.601  3509  3926 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,12-20 11:53:40.601  3509  3926 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
,12-20 11:53:40.601  3509  3926 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
12-20 11:53:40.601  3509  3926 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER(1)
,12-20 11:53:40.601  3509  3926 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for AUTO_BRIGHTNESS
12-20 11:53:40.601  3509  3926 D SContextService: 	.unregisterCallback : 2, client=
12-20 11:53:40.601  3509  3926 D SContextService: ===== SContext Service List =====
12-20 11:53:40.601  3509  3926 D PowerManagerUtil: Excessive delay in SensorHubAutoBrightnessEnabled::unregisterListener done: 46ms
12-20 11:53:40.601  3509  3926 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@b62dce, Service : Activity Tracker
12-20 11:53:40.601  3509  3926 D SContextManager:   .unregisterListener : listener = com.android.server.display.AutomaticBrightnessController$6@d74e31, service=Auto Brightness
,12-20 11:53:40.601  3509  4485 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,12-20 11:53:40.601  3509  4333 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
12-20 11:53:40.601  4748  4748 D ScoverManager: registerListener
,12-20 11:53:40.601  3509  4002 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,12-20 11:53:40.611  3509  4334 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
12-20 11:53:40.611  3509  4334 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@405e8b6, pid : 4748, uid : 10000, type : 1
,12-20 11:53:40.611  4748  9567 D AODService: onCreate register mSContextListener : com.samsung.android.app.aodservice.AODService$7@de2fb91
,12-20 11:53:40.611  3509  3531 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,12-20 11:53:40.611  3509  4007 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:53:40.611  3509  4007 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 4, 0, 0, 0, 1, 2,
12-20 11:53:40.611  3509  4007 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 4, 0, 0, 0, 1, 2
12-20 11:53:40.611  3509  3791 I Sensors : Light old sensor_state 0, new sensor_state : 512 en : 1
12-20 11:53:40.611  3182  3222 D Sensorhubs: sendContextData: -63, 23, 56, 4, 0, 0, 0, 1, 2
,12-20 11:53:40.621  4748  4748 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
12-20 11:53:40.621  4748  4748 D AODService: registerBatteryReceiver
,12-20 11:53:40.621  4748  4748 D BatteryController: saveBatteryData : level[100], status[2]
,12-20 11:53:40.621  4748  4748 D AODService: Cover coverOpen[true], isBlackListCover(type)[false]
12-20 11:53:40.621  4748  4748 D AODService.ClockTimer: ClockTimer:start : true
,12-20 11:53:40.631  3509  4007 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-20 11:53:40.631  3509  4007 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:53:40.631  3509  4007 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:53:40.631  3509  4007 V CAE     : start(ContextProvider.java:128)
,12-20 11:53:40.631  3509  4007 V CAE     : clear(DevicePhysicalContextMonitorRunner.java:497)
12-20 11:53:40.631  4748  4748 D AODService.ClockTimer: observe start aod
12-20 11:53:40.631  4748  4748 D AODService.ClockTimer: notifyWakeUp
,12-20 11:53:40.631  3509  4007 V CAE     : enable(DevicePhysicalContextMonitorRunner.java:471)
12-20 11:53:40.631  3509  4007 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 56, 0, 10, 53, 40,
12-20 11:53:40.631  3509  4007 D SensorHubManager: SendSensorHubData: send data = -79, 56, 0, 10, 53, 40
12-20 11:53:40.631  3182  7712 D Sensorhubs: sendContextData: -79, 56, 0, 10, 53, 40
,12-20 11:53:40.641  4748  4748 V BatteryController: getBatteryLevel[100.0], batteryStatus[2]
,12-20 11:53:40.641  3509  3531 D SettingsProvider: isChangeAllowed() : name = aod_show_state
,12-20 11:53:40.641  3509  3531 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
12-20 11:53:40.641  3509  3531 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,12-20 11:53:40.641  3509  3531 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
12-20 11:53:40.641  3509  4007 D CAE     : getFaultDetectionResult(DevicePhysicalContextMonitorRunner.java:521) - true
,12-20 11:53:40.641  3509  3531 D SettingsProvider: selectionArgs: false
12-20 11:53:40.641  3509  4007 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
12-20 11:53:40.641  3509  3531 D SettingsProvider: selectionArgs: 10000
12-20 11:53:40.641  3509  3531 D SettingsProvider: ret = -1
,12-20 11:53:40.641  4748  4748 E SettingsUtils: setAODShowState  config = 1
,12-20 11:53:40.641  4748  4748 D AlpmModeManager: setFirstStartALPM() initialize value
12-20 11:53:40.641  4748  4748 D AODService: createWindow
,12-20 11:53:40.651  4748  4748 I AODUpdatePositionController: initPosition : X[1], Y[341] Rect(-50, 0 - 50, 920)
,12-20 11:53:40.651  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,12-20 11:53:40.651  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:53:40.651  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,12-20 11:53:40.651  3509  4007 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:53:40.651  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,12-20 11:53:40.651  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:53:40.651  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:53:40.651  3509  4007 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
12-20 11:53:40.651  3509  4007 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
12-20 11:53:40.651  3509  4007 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,12-20 11:53:40.651  3509  4007 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER(1)
,12-20 11:53:40.651  3509  4007 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@cebf089, Service : DEVICE_PHYSICAL_CONTEXT_MONITOR(1)
12-20 11:53:40.651  3509  4007 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:53:40.661  3509  4007 D SContextService: 	.registerCallback : 2, client=
,12-20 11:53:40.661  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:53:40.661  3509  4007 D SContextService: ===== SContext Service List =====
12-20 11:53:40.661  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:53:40.661  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:53:40.661  3509  4007 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@b62dce, Service : Activity Tracker
12-20 11:53:40.661  3509  4007 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@6b5588e, Service : Device Physical Context Monitor
12-20 11:53:40.661  4748  9567 D SContextManager:   .registerListener : listener = com.samsung.android.app.aodservice.AODService$7@de2fb91, service=Device Physical Context Monitor
,12-20 11:53:40.661  3509  4334 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:53:40.661  4748  4748 I DefaultClockView: composeDefaultClockView: Selected clock = 0
12-20 11:53:40.661  3509  4334 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 1, 2, 88,
12-20 11:53:40.661  3509  4334 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 1, 2, 88
,12-20 11:53:40.661  3182  3182 D Sensorhubs: sendContextData: -63, 23, 56, 3, 1, 2, 88
,12-20 11:53:40.661  3509  4334 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,12-20 11:53:40.661  3509  4334 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-20 11:53:40.671  3509  4436 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-20 11:53:40.671  3509  4436 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 2, 0, 3,
12-20 11:53:40.671  3509  4436 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 2, 0, 3
12-20 11:53:40.671  3182  3222 D Sensorhubs: sendContextData: -63, 23, 56, 3, 2, 0, 3
12-20 11:53:40.671  4748  4748 D BatteryMeterView: BatteryMeterView 
12-20 11:53:40.671  3509  4436 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-20 11:53:40.671  3509  4436 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-20 11:53:40.671  3509  4092 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-20 11:53:40.671  3509  4092 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 3, 0, 60,
12-20 11:53:40.671  3509  4092 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 3, 0, 60
,12-20 11:53:40.671  3182  7712 D Sensorhubs: sendContextData: -63, 23, 56, 3, 3, 0, 60
12-20 11:53:40.681  3509  4092 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-20 11:53:40.681  3509  4092 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:53:40.681  3509  4977 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:53:40.681  3509  4977 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 4, 0, 1,
12-20 11:53:40.681  3509  4977 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 4, 0, 1
12-20 11:53:40.681  3182  3182 D Sensorhubs: sendContextData: -63, 23, 56, 3, 4, 0, 1
,12-20 11:53:40.681  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:53:40.681  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:53:40.681  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,12-20 11:53:40.681  3509  4977 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-20 11:53:40.681  3509  4977 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:53:40.681  4748  4748 D DefaultClockView: LocalTime Pattern : HH:mm
,12-20 11:53:40.691  3509  3531 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-20 11:53:40.691  3509  3531 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 4, 0, 0, 0, 110, 1,
12-20 11:53:40.691  3509  3531 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 4, 0, 0, 0, 110, 1
,12-20 11:53:40.691  3182  3222 D Sensorhubs: sendContextData: -63, 23, 56, 4, 0, 0, 0, 110, 1
12-20 11:53:40.691  4748  4748 I AODUpdatePositionController: updatePosition: start current clock, Current X[1] Current Y[341] NewPositionTimer[60]
,12-20 11:53:40.691  4748  4748 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 11:53 time02: null ampm: null
,12-20 11:53:40.691  3509  3531 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,12-20 11:53:40.691  3509  3531 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:53:40.691  3509  4334 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:53:40.691  3509  4334 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 4, 0, 0, 0, 17, 2,
,12-20 11:53:40.691  3509  4334 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 4, 0, 0, 0, 17, 2
,12-20 11:53:40.691  3182  7712 D Sensorhubs: sendContextData: -63, 23, 56, 4, 0, 0, 0, 17, 2
,12-20 11:53:40.701  4748  4748 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,12-20 11:53:40.701  3509  4334 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-20 11:53:40.701  4748  4748 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
12-20 11:53:40.701  3509  4334 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:53:40.701  4748  4748 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:wt., 20 gru 11:53
12-20 11:53:40.701  4748  4748 D DefaultClockView: show
,12-20 11:53:40.701  4748  4748 D ViewRootImpl: #1 mView = com.samsung.android.app.aodservice.nightclock.DefaultClockView{f2c065 V.E...... ......ID 0,0-0,0}
,12-20 11:53:40.701  3509  4977 D ISSUE_DEBUG: InputChannelName : 15ed4bc AOD
,12-20 11:53:40.701  3509  3595 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{15ed4bc u0 d0 AOD}
12-20 11:53:40.701  3509  4977 D InputDispatcher: Focus left window: 4328
12-20 11:53:40.701  3509  4977 D InputDispatcher: Focus entered window: 4748
12-20 11:53:40.701  3960  3960 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
12-20 11:53:40.701  3509  3615 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3509 uid:1000
12-20 11:53:40.711  3509  3615 D PointerIcon: setMouseCustomIcon IconType is same.101
,12-20 11:53:40.741  8550  8580 D BadgeProvider: query, [selection] : null
,12-20 11:53:40.741  4748  4748 D AODMissedEventController: [com.android.contacts] badgeCount : 0, [com.android.mms] badgeCount : 0
,12-20 11:53:40.741  4748  4748 I AODService.ClockTimer: startAlarm : TICK
,12-20 11:53:40.741  3509  4092 V AlarmManager: Add whitelist package alarm :PendingIntent{f9a0c45: PendingIntentRecord{cb26099 com.samsung.android.app.aodservice broadcastIntent}}
,12-20 11:53:40.751  3509  3626 D SurfaceControl: Excessive delay in setPowerMode(): 187ms
,12-20 11:53:40.751  3509  3626 D PowerManagerUtil: Excessive delay in !@display_state: OFF: 188ms
12-20 11:53:40.751  3509  3626 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 192ms
12-20 11:53:40.751  4748  4748 I AODService.ClockTimer: startAlarm : SLEEP,
12-20 11:53:40.751  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=1
12-20 11:53:40.751  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable
12-20 11:53:40.751  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
,12-20 11:53:40.751  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable done
12-20 11:53:40.751  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
12-20 11:53:40.751  4748  4748 V AODService.ClockTimer: AOD Trigger: next AOD WAKEUP time is 9:0
12-20 11:53:40.751  3509  3619 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:53:40.751  3509  3924 D PersonaManagerService: onfinishedGoingToSleep why = 3
12-20 11:53:40.751  3509  3619 I PowerManagerService: [PWL] Off : 0s ago
12-20 11:53:40.751  3960  4906 D KeyguardViewMediator: onFinishedGoingToSleep(3)
,12-20 11:53:40.751  3509  3619 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
12-20 11:53:40.751  3960  4906 D KeyguardViewMediator: notifyFinishedGoingToSleep
12-20 11:53:40.751  3509  3619 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
12-20 11:53:40.751  3960  3960 D KeyguardViewMediator: handleNotifyFinishedGoingToSleep
12-20 11:53:40.751  3509  3619 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AlwaysOnDisplay_EnsureWorkingTime' (uid=10000, pid=4748, ws=null) (elapsedTime=139)
12-20 11:53:40.751  3960  3960 D KeyguardEffectViewController: onScreenTurnedOff
12-20 11:53:40.751  3509  3619 I PowerManagerService: [PWL]   PowerManagerService.Display: ref count=2
12-20 11:53:40.751  3960  3960 D KeyguardEffectViewController: ## mBackgroundView.onPause()
12-20 11:53:40.751  3509  3619 I PowerManagerService: [PWL]     mUserActivitySummary : 0x4
12-20 11:53:40.751  3960  3960 D KeyguardEffectViewLayered: onPause()
12-20 11:53:40.751  3509  3619 I PowerManagerService: [PWL]     mDisplayReady : false
,12-20 11:53:40.751  3509  3631 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
12-20 11:53:40.751  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=1
12-20 11:53:40.751  4748  4748 D AODService.ClockTimer: startAlarm is canceled. triggerAtMillis = -1, currentTime = 1482231220767
12-20 11:53:40.751  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
12-20 11:53:40.751  4748  4748 I AODService.ClockTimer: stopAlarm : WAKEUP
12-20 11:53:40.751  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
12-20 11:53:40.751  3960  3960 D SecKeyguardStatusView: onFinishedGoingToSleep() why=3
12-20 11:53:40.751  3509  3619 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:53:40.751  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,12-20 11:53:40.751  3509  3619 D PowerManagerService: mDisplayReady: true
12-20 11:53:40.751  3509  3619 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
12-20 11:53:40.751  3509  3619 D PowerManagerService: handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
12-20 11:53:40.751  3509  3619 D PowerManagerService: handleSandman : startDream(true)
12-20 11:53:40.751  3509  3619 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
12-20 11:53:40.751  3509  3619 I PowerManagerService: Sleeping (uid 1000)...
12-20 11:53:40.751  3509  3619 D PowerManagerService: [s] UserActivityState : 4 -> 0
12-20 11:53:40.751  3509  3619 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,12-20 11:53:40.761  3509  4333 V AlarmManager:  remove PendingIntent] PendingIntent{6b26f9a: PendingIntentRecord{d5689d1 com.samsung.android.app.aodservice broadcastIntent}}
,12-20 11:53:40.761  3960  3960 V KeyguardFingerPrint: updateFingerprintListeningState(false)
,12-20 11:53:40.761  3960  3960 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
,12-20 11:53:40.761  3960  3960 V KeyguardUpdateMonitor: stopListeningForFingerprint()
12-20 11:53:40.761  4748  4748 D BatteryController: saveBatteryData : level[100], status[2]
,12-20 11:53:40.771  3018  3018 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, BOD
,12-20 11:53:40.771  3509  4441 V WindowOrientationListener: setCurrentAppOrientation :5
12-20 11:53:40.771  3509  4441 V WindowManager: rotationForOrientationLw(orient=5, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,12-20 11:53:40.771  3509  3509 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 3509) 
,12-20 11:53:40.781  3509  3509 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=5) set On
,12-20 11:53:40.781  3509  3509 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
12-20 11:53:40.781  3509  3509 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
,12-20 11:53:40.781  3509  3625 D LightsService: [SvcLED]  onSensorChanged::light value = 22
12-20 11:53:40.781  3509  3509 D BatteryService: turn on LED for charging
12-20 11:53:40.781  3509  3625 D SensorManager: unregisterListener ::   
12-20 11:53:40.781  3509  3625 I LightsService: fileWriteInt : /sys/class/sec/led/led_lowpower  value : 0
,12-20 11:53:40.781  3509  3625 D lights  : led_pattern : 1 +
,12-20 11:53:40.781  3509  3625 D lights  : led_pattern : 1 -
,12-20 11:53:40.781  3509  3625 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
12-20 11:53:40.781  3509  3625 V AlarmManager:  remove PendingIntent] PendingIntent{4ecf248: PendingIntentRecord{45ac606 android broadcastIntent}}
,12-20 11:53:40.791  4748  7100 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,12-20 11:53:40.801  3509  3615 V WindowAnimator: hide by NightClock Window{421530f u0 d0 StatusBar}
,12-20 11:53:40.801  3509  3615 V WindowAnimator: hide by NightClock Window{9ce7bae u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
,12-20 11:53:40.811  3509  4486 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,12-20 11:53:40.821  7178  7178 D SamsungIME: IMPL finishInput
12-20 11:53:40.821  7178  7178 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
12-20 11:53:40.821  7178  7178 D SamsungIME: saveAndClear +
12-20 11:53:40.821  3509  4487 W InputMethodManagerService: Starting input on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@b7b659c (uid=10069 pid=4328)
12-20 11:53:40.821  7178  7178 D SamsungIME: saveAndClear -
,12-20 11:53:40.821  7178  7178 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,12-20 11:53:40.821  3509  3509 I CAE     : handleMessage(CaPowerManager.java:182) - AP_SLEEP
,12-20 11:53:40.821  3509  3509 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_SLEEP
,12-20 11:53:40.821  3509  3509 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -46, 0,
12-20 11:53:40.821  3509  3509 D SensorHubManager: SendSensorHubData: send data = -76, 13, -46, 0
12-20 11:53:40.821  3182  3182 D Sensorhubs: sendContextData: -76, 13, -46, 0
,12-20 11:53:40.821  3509  3509 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 10, 53, 40,
12-20 11:53:40.821  3509  3509 D SensorHubManager: SendSensorHubData: send data = -63, 14, 10, 53, 40
12-20 11:53:40.821  3182  3222 D Sensorhubs: sendContextData: -63, 14, 10, 53, 40
,12-20 11:53:40.831  4748  4748 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,12-20 11:53:40.831  3509  3509 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,12-20 11:53:40.831  4748  4748 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,12-20 11:53:40.841  3509  3842 D MotionRecognitionService: Screen off setAccIntStatus 
,12-20 11:53:40.841  3509  3530 V WindowStateAnimator: Finishing drawing window Window{15ed4bc u0 d0 AOD}: mDrawState=DRAW_PENDING
12-20 11:53:40.841  3509  3842 E MotionRecognitionService:  handler : SCREEN_OFF end 
,12-20 11:53:40.851  3960  3960 D PanelView: updateQsState
12-20 11:53:40.851  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
12-20 11:53:40.851  3960  3960 D KeyguardCircleAffordanceView: setPreviewView: mRight=false,preview=null
12-20 11:53:40.851  3960  3960 D KeyguardCircleAffordanceView: setPreviewView: mRight=true,preview=null
12-20 11:53:40.851  3960  3960 D KeyguardSwipeHelper: reset()
12-20 11:53:40.851  3960  3960 D KeyguardUnlockEventHandler: reset()
12-20 11:53:40.851  3960  3960 D KeyguardSwipeHelper: resetChildViewVI()
,12-20 11:53:40.851  3509  3815 I Sensors : #>LightSensor r=13 g=10 b=8 c=29 atime=245 again=64 lux=22
,12-20 11:53:40.861  3509  3509 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_OFF
,12-20 11:53:40.881  3509  3593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{316a0cb u-1 com.samsung.settings.action.directaccess.CLOSE_DIALOG qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c83b918 8954:com.samsung.android.SettingsReceiver/1000}
,12-20 11:53:40.891  3509  3509 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
12-20 11:53:40.891  3509  3509 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
12-20 11:53:40.891  3509  3509 D UcmService: notifyChangeToPlugin event 16
12-20 11:53:40.891  3509  3509 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
,12-20 11:53:40.891  3509  3509 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
,12-20 11:53:40.891  3509  3509 D UcmService: notifying to unmanaged plugin
12-20 11:53:40.891  4378  4418 E ucsBai_agentService: notifyChange NOT SUPPORTED
12-20 11:53:40.891  3509  3509 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
12-20 11:53:40.891  3509  3509 D UcmService: agentService status-0
12-20 11:53:40.891  3509  3509 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.ese:eSE Credential Storage Package name = com.samsung.ucs.agent.ese
12-20 11:53:40.891  3509  3509 D UcmService: notifying to managed plugin
12-20 11:53:40.891  3509  3509 D UcmService: checkIfNotify: Valid userid - 0
12-20 11:53:40.891  3509  3509 D PolicyManager: PolicyManager.isStorageEnabled() for userId = 0
12-20 11:53:40.891  3509  3509 D UniversalCredentialManagerService: checkCallerPermissionFor is called for method-isCredentialStorageManagedAsUser
12-20 11:53:40.891  3509  3509 D UniversalCredentialManagerService: isCredentialStorageManagedAsUser is called....
12-20 11:53:40.891  3509  3509 D PolicyManager: PolicyManager.isStorageEnabled() result = false
12-20 11:53:40.891  3509  3509 D UcmService: agentService com.samsung.ucs.agent.ese:eSE Credential Storage not notified
12-20 11:53:40.891  3509  3509 D UcmService: agentService status-0
12-20 11:53:40.891  3509  3509 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
12-20 11:53:40.891  3509  3509 D UcmService: notifying to unmanaged plugin
,12-20 11:53:40.891  4396  4424 D BootAgentService: notifyChange eventId-16
12-20 11:53:40.891  3509  3509 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
12-20 11:53:40.891  3509  3509 D UcmService: agentService status--1
12-20 11:53:40.891  3509  3509 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,12-20 11:53:40.911  3509  3509 I WifiTrafficPoller: evaluateTrafficStatsPolling
,12-20 11:53:40.921  3509  3881 D WifiStateMachine: handleScreenStateChanged, screen off, set scan interval as max value  !!!
12-20 11:53:40.921  3509  3881 D WifiNative-wlan0: callSECApiVoid - ID [19]
,12-20 11:53:40.921  4152  4152 I wpa_supplicant: set PERIODIC_SCAN_INTERVAL_MAX to 128sec !!!
12-20 11:53:40.921  3509  3509 D NotificationService: ACTION_SCREEN_OFF
12-20 11:53:40.921  3509  3509 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3509) 
12-20 11:53:40.921  3509  3509 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=6) set Off
,12-20 11:53:40.921  3509  3509 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
12-20 11:53:40.921  3509  3509 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
12-20 11:53:40.921  3509  3509 D EdgeLight: Turning off
12-20 11:53:40.921  3509  3625 D LightsService: [SvcLED]  onSensorChanged::light value = 22
12-20 11:53:40.921  3509  3625 D SensorManager: unregisterListener ::   
12-20 11:53:40.921  3509  3625 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
12-20 11:53:40.921  3509  3881 E WifiNative-wlan0: do suspend true
12-20 11:53:40.921  3509  3625 V AlarmManager:  remove PendingIntent] PendingIntent{4ecf248: PendingIntentRecord{45ac606 android broadcastIntent}}
,12-20 11:53:40.931  4194  4204 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=112]
,12-20 11:53:40.931  3175  3175 D audio_hw_primary: adev_set_parameters: enter: kvpairs: screen_state=off
12-20 11:53:40.931  4194  4194 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.people.package_name=android, samsung.people.notification_type=led_indicator}]
12-20 11:53:40.931  4194  4194 I PeopleStripeService: PeopleNotificationReceiver:3
,12-20 11:53:40.931  4194  4194 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
,12-20 11:53:40.931  4194  4194 I PeopleDataManager: removeNotification
12-20 11:53:40.931  4194  4194 I NotificationParser: getNotiType:android,led_indicator
12-20 11:53:40.931  4194  4194 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=true,key=null,removeAll=false
12-20 11:53:40.931  4194  4194 D PeopleDataManager: removeNotiInfo =null
,12-20 11:53:40.951  3509  3509 I MdnieScenarioControlService: action  :  android.intent.action.SCREEN_OFF
,12-20 11:53:40.951  3509  3509 I FingerprintService: onReceive: android.intent.action.SCREEN_OFF
,12-20 11:53:40.961  3509  3509 I BackgroundCompactionService: Schedule Type1 BGCompaction
,12-20 11:53:40.961  3509  3509 D WifiService: ACTION_SCREEN_OFF, mSContextManager.unregisterListener !!
,12-20 11:53:40.961  3509  3509 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@b62dce, Service = Activity Tracker, used = 0
12-20 11:53:40.961  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155651
12-20 11:53:40.961  3509  3509 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for ACTIVITY_TRACKER
12-20 11:53:40.961  3509  3509 V CAE     : stop(ContextProvider.java:155)
,12-20 11:53:40.961  3509  3509 V CAE     : clear(ActivityTrackerRunner.java:108)
,12-20 11:53:40.961  3509  3509 V CAE     : disable(ActivityTrackerRunner.java:96)
,12-20 11:53:40.971  3509  3509 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 26, 0, 0, 0, 0, 0, 0, 0, 0,
,12-20 11:53:40.971  3509  3509 D SensorHubManager: SendSensorHubData: send data = -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
12-20 11:53:40.971  3182  7712 D Sensorhubs: sendContextData: -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
,12-20 11:53:40.981  3509  3509 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
12-20 11:53:40.981  3509  3509 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:53:40.991  3509  3509 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:53:40.991  3509  3509 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,12-20 11:53:40.991  3509  3509 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
12-20 11:53:40.991  3509  3509 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
12-20 11:53:40.991  3509  3509 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@cebf089, Service : DEVICE_PHYSICAL_CONTEXT_MONITOR(1)
12-20 11:53:40.991  3509  3509 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for ACTIVITY_TRACKER
12-20 11:53:40.991  3509  3509 D SContextService: 	.unregisterCallback : 2, client=
,12-20 11:53:40.991  3509  3509 D SContextService: ===== SContext Service List =====
12-20 11:53:40.991  3509  3509 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@6b5588e, Service : Device Physical Context Monitor
12-20 11:53:40.991  3509  3509 D SContextManager:   .unregisterListener : listener = com.android.server.wifi.WifiServiceImpl$11@e41d2c9, service=Activity Tracker
,12-20 11:53:41.001  3509  3615 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
,12-20 11:53:41.001  3509  3615 D IpRemoteDisplayController: Bridge Server is not available
,12-20 11:53:41.011  3509  3509 D NetworkPolicy: mScreenReceiver: ACTION_SCREEN_OFF, extra: 3
,12-20 11:53:41.011  3509  3879 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 3
12-20 11:53:41.011  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10009, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
,12-20 11:53:41.011  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
,12-20 11:53:41.021  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10065, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
,12-20 11:53:41.021  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10072, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
,12-20 11:53:41.041  3509  3815 I Sensors : #>LightSensor r=13 g=10 b=8 c=30 atime=245 again=64 lux=24
12-20 11:53:41.041  3509  3589 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,12-20 11:53:41.051  4253  4253 D FusedLocationReceiver: BroadcastReceiver : ACTION_SCREEN_OFF
,12-20 11:53:41.061  4304  9570 D NfcService: call the applyRouting
,12-20 11:53:41.071  3960  4176 D NetworkController.MobileSignalController(0/2147483643): onDataActivity: direction=0
,12-20 11:53:41.091  4328  4328 D Launcher.Workspace: exitWidgetResizeMode. isClearResizeFrame is false
,12-20 11:53:41.141  5257  5257 D BtGatt.GattService: LCD turned off
,12-20 11:53:41.141  5257  5430 D BtGatt.ScanManager: handleLcdOffIntent
12-20 11:53:41.141  5257  5430 D BtGatt.ScanManager: handleLcdOffIntent : thresholdScanValue is = 10 mLastConfiguredScanValue =0
,12-20 11:53:41.191  4607  9571 D MdnsClient: Multicast lock held. Releasing
,12-20 11:53:41.211  3509  3815 I Sensors : #>LightSensor r=13 g=9 b=8 c=29 atime=245 again=64 lux=22
,12-20 11:53:41.211  6319  6319 D CocktailBarUiController: ACTION_SCREEN_OFF
12-20 11:53:41.211  6319  6319 D AbstractCocktailPanelView: setPanelVisible: CocktailPortraitRemotePanelViewfalse will be hiden: 3
12-20 11:53:41.211  6319  6319 D CocktailBarPanelVisibilityManager: updateActivePanelView:  vis=false screenOn=false onTransit=false -hide: 3 current Active: 3
,12-20 11:53:41.211  6319  6319 E AbstractCocktailPanelView: notifyPanelVisibilityChanged: visibility not changed 2 id: 3
12-20 11:53:41.221  6319  6319 I TrayVisibilityController: handleMessage : msg.what = 1
,12-20 11:53:41.221  6319  6319 I Utils   : isCurrentUser current = 0, ownerId = 0
12-20 11:53:41.221  6319  6319 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
12-20 11:53:41.221  6319  6319 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 1
,12-20 11:53:41.221  6319  6319 D TrayStateController: putInputRect mDynamicInputRegion=188281550@LastEvent=t=1482231188813Rect(8, 0 - 64, 588),Rect=Rect(0, 0 - 0, 0)
12-20 11:53:41.221  4194  4194 D PeopleStripeService: ACTION_SCREEN_OFF
,12-20 11:53:41.221  4194  4194 D PeopleStripeManager: requestCloseCircleViews()
12-20 11:53:41.221  4194  4194 I CircleImageSaveLayout: hideImageSaveLayout()
12-20 11:53:41.221  4194  4194 D CircleImageSaveLayout: releaseWakeLock()
12-20 11:53:41.221  4194  4194 D SweepImageListView: hide
12-20 11:53:41.221  4194  4194 D SweepImageListView: setAdapter mAdapter =null:159137937
12-20 11:53:41.221  4194  4194 I PeopleEdgeCommContainer: hideEffectView() 
,12-20 11:53:41.221  4194  4194 I CirclePokingManager: stopParticleEffectView  mParticleEffectView-null
12-20 11:53:41.221  4194  4194 I PeopleDataManager: deleteMarkedCircleEvent : people = null
12-20 11:53:41.221  4194  4194 I PeopleEdgeCommContainer: setPeopleChannelShowStatus false
12-20 11:53:41.221  4194  4194 I PeopleStripeWindow: updateWindowParam : minimize=true,mLastMinimized=true,color0 blur true
,12-20 11:53:41.231  6319  6319 D TrayStateController: setUiState: 0 --> 2
12-20 11:53:41.231  3509  3905 I AbsCocktailBarStatePolicy: handleMessage: entry what = 1
,12-20 11:53:41.231  4194  4194 D PeopleStripeVisibilityController: setEmoHistory enable=false
,12-20 11:53:41.231  4194  4194 I PeopleStripeVisibilityController: getComputedTrayVisible : keyguardState = 1
12-20 11:53:41.231  4194  4194 I PeopleStripeVisibilityController: isVisibleByAlwaysOn : mState = 1
12-20 11:53:41.231  4194  4194 E PeopleStripeProcessMonitor: getTopActivity : MultiWindowFacade.taskList = []
,12-20 11:53:41.231  4194  4194 I PeopleStripeProcessMonitor: isPeopleStripeTask packageName = com.sec.android.app.launcher 0
,12-20 11:53:41.231  4194  4194 E PeopleStripeProcessMonitor: getTopActivity : MultiWindowFacade.taskList = []
,12-20 11:53:41.241  4194  4194 I PeopleStripeVisibilityController: updateStripeVisible : State 1 visible = 1
,12-20 11:53:41.241  4194  4194 I PeopleStripeManager: isExistVisibleHandler false
,12-20 11:53:41.241  4194  4194 I PeopleStripeManager: showStripe Not exist noti handler.
12-20 11:53:41.241  4194  4194 I PeopleStripeManager: hideStripe
12-20 11:53:41.241  4194  4194 D PeopleStripeManager: onVisibilityChanged : 2
12-20 11:53:41.241  4194  4194 D PeopleStripeVisibilityController: setHiddenEdgePanel enable=true
12-20 11:53:41.241  4194  4194 I PeopleStripeVisibilityController: updateStripeVisible : State 1028 visible = 2
12-20 11:53:41.241  4194  4194 I PeopleStripeManager: hideStripe
,12-20 11:53:41.251  3509  6576 D SSRM:n  : SIOP:: AP = 310, PST = 324 (W:10), CP = 267, CUR = 149, LCD = 0
,12-20 11:53:41.251  3018  3028 D libEGL  : eglTerminate EGLDisplay = 0x7fa9ac0e78
,12-20 11:53:41.261  3018  3028 I SurfaceFlinger: id=20 Removed DocktailBar (8/12)
,12-20 11:53:41.261  3018  3018 D libEGL  : eglTerminate EGLDisplay = 0x7fff7e5bd8
,12-20 11:53:41.271  3509  3509 I SurveyLogManager: mDeviceInfo.mScreen = false
,12-20 11:53:41.271  6319  6319 D CocktailBarUiController: onCocktailBarStateChanged: flag=0x1 vis=2 bgType=0 showTimeout=-1 activate=true
,12-20 11:53:41.271  3509  6576 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-20 11:53:41.291  7178  7178 E SamsungIME: invoke(): method is null
,12-20 11:53:41.311  8617  8655 I SystemBroadcastReceiver: [#CMH#] Received broadcast 
12-20 11:53:41.311  8617  8655 I PolicyManager: [#CMH#] onReceive action = EVENT_SCREEN_OFF
12-20 11:53:41.311  8617  8655 I SystemBroadcastReceiver: [#CMH#] onReceive completed 
,12-20 11:53:41.321  8428  8428 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDA0E41DE4F26DD020CF7906DED0A6ECA9F]}
,12-20 11:53:41.321  8428  8428 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB71D02215B774510884CB3BFD0FBDB0EDC]}
,12-20 11:53:41.331  8428  8428 D [WeatherWidget(1240)]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-20 11:53:41.331  4748  4748 I AlpmModeManager: startAlpmMode : state  = IDLE
12-20 11:53:41.331  4748  4748 I AlpmModeManager: handleUnblankDisplay: state  = IDLE
12-20 11:53:41.331  4748  4748 V AlpmModeManager: handleUnblankDisplay: setDoze [DISPLAY_STATE_DOZE]
,12-20 11:53:41.331  4748  4748 D AlpmModeManager: getLastAlpmHlpmBright : HighNit[true], AlpmHlpm[1], NitMode[[ALPM]_60NIT_ON]
12-20 11:53:41.331  3509  4334 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = 3, screenState = 3, Brightness = 0, wakefulness = false
12-20 11:53:41.331  4748  4748 I AlpmModeManager: handleUnblankDisplay: AlpmModeManager wakeLock [ACQUIRE]
12-20 11:53:41.331  3509  4334 D PowerManagerService: [s] UserActivityState : 0 -> 4
,12-20 11:53:41.331  3509  4436 D PowerManagerService: [api] acquire WakeLock flags=0x40 tag=AlpmModeManager uid=10000 pid=4748
12-20 11:53:41.331  3509  4436 I libsuspend: !@autosuspend_wakeup_count_disable
12-20 11:53:41.331  3509  4436 D PowerManagerService: mDisplayReady: false
12-20 11:53:41.331  3509  4436 I libsuspend: !@autosuspend_wakeup_count_disable done
12-20 11:53:41.331  3509  4436 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-20 11:53:41.331  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-20 11:53:41.331  3509  3619 D DisplayPowerState: !@ [0] ColorFade exit
12-20 11:53:41.331  3509  3619 D PowerManagerService: [input device light] onColorFadeExit(true)
,12-20 11:53:41.331  3018  3028 D libEGL  : eglTerminate EGLDisplay = 0x7fa9ac0e78
12-20 11:53:41.331  3018  3028 D libEGL  : eglTerminate EGLDisplay = 0x7fa9ac0e78
,12-20 11:53:41.331  3018  4572 I SurfaceFlinger: id=21 Removed DolorFade (9/11)
,12-20 11:53:41.341  3018  4509 I SurfaceFlinger: id=21 Removed DolorFade (-2/11)
12-20 11:53:41.341  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-20 11:53:41.341  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:53:41.341  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:53:41.341  3509  3619 D DisplayPowerState: Requesting new screen state: [0] state=DOZE, backlight (By colorFade)=0
12-20 11:53:41.341  3509  3927 D DisplayPowerState: Updating screen state [0]: state=DOZE, backlight (by ColorFade)=0
12-20 11:53:41.341  3509  3626 D DisplayManagerService: !@display_state: OFF -> DOZE brightness: 0 -> 0
12-20 11:53:41.341  3509  3924 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
12-20 11:53:41.341  3509  3615 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-20 11:53:41.341  3509  3615 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,12-20 11:53:41.341  3018  3018 D libEGL  : eglTerminate EGLDisplay = 0x7fff7e5bd8
,12-20 11:53:41.351  3018  3018 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa9d43c00,
12-20 11:53:41.351  3018  3018 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,12-20 11:53:41.361  3509  9572 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,12-20 11:53:41.361  6319  6319 E CocktailBarPositionManager: Window direction: 0
12-20 11:53:41.361  6319  6319 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-20 11:53:41.361  8428  8428 D [WeatherWidget(1240)]  WeatherService: {[44BE909F148A112BE24DB9207B7094FCDA9342562AE17780A60BEC6E95DC6F0D]}
,12-20 11:53:41.371  3509  4007 I ActivityManager: Killing 8645:com.wssyncmldm/1000 (adj 15): DHA:empty #33
,12-20 11:53:41.371  3509  9572 D BluetoothAdapter: STATE_ON
,12-20 11:53:41.371  3509  4334 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:53:41.381  3509  3791 V AlarmManager:  remove PendingIntent] PendingIntent{737eb66: PendingIntentRecord{69adb7d com.android.bluetooth broadcastIntent}}
,12-20 11:53:41.391  3509  4441 V AlarmManager:  remove PendingIntent] PendingIntent{36c7ea7: PendingIntentRecord{69adb7d com.android.bluetooth broadcastIntent}}
,12-20 11:53:41.391  3509  3927 D lights  : lcd : 1 +
12-20 11:53:41.391  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-20 11:53:41.391  3509  3927 D lights  : lcd : 1 -
12-20 11:53:41.391  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-20 11:53:41.391  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:53:41.391  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:53:41.401  3509  4002 V AlarmManager:  remove PendingIntent] PendingIntent{ff2ff54: PendingIntentRecord{69adb7d com.android.bluetooth broadcastIntent}}
,12-20 11:53:41.411  3509  4436 D ActivityManager: cleanUpApplicationRecord -- 8645
,12-20 11:53:41.411  3509  4436 D ActivityManager: isAutoRunBlockedApp:: com.wssyncmldm, Auto Run ON
12-20 11:53:41.411  3509  4342 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:53:41.421  3509  4434 V WindowStateAnimator: Finishing drawing window Window{9ce7bae u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: mDrawState=HAS_DRAWN
,12-20 11:53:41.421  3509  9572 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,12-20 11:53:41.431  4748  4748 D DefaultClockView: Start AOD Enter Animation
,12-20 11:53:41.431  3509  4441 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:53:41.441  3509  4333 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:53:41.461  3509  9572 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,12-20 11:53:41.461  3509  9572 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,12-20 11:53:41.511  4060  4060 D Recents : onTaskStackChanged
,12-20 11:53:41.541  4194  4194 I PeopleStripeManager: isExistVisibleHandler false
,12-20 11:53:41.541  4194  4194 I PeopleStripeManager: hideStripe
,12-20 11:53:41.571  3509  9572 I BatteryStatsDumper: Writing to database completed
,12-20 11:53:41.581  3509  3626 D SurfaceControl: Excessive delay in setPowerMode(): 238ms
12-20 11:53:41.581  3509  3626 D PowerManagerUtil: Excessive delay in !@display_state: DOZE: 239ms
12-20 11:53:41.581  3509  3626 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 239ms
12-20 11:53:41.581  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-20 11:53:41.581  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable
12-20 11:53:41.581  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-20 11:53:41.581  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable done
12-20 11:53:41.581  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-20 11:53:41.581  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:53:41.581  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-20 11:53:41.581  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-20 11:53:41.581  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:53:41.581  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:53:41.581  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,12-20 11:53:41.581  3509  3619 D PowerManagerService: mDisplayReady: true
12-20 11:53:41.581  3509  3619 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
12-20 11:53:41.581  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-20 11:53:41.581  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,12-20 11:53:41.581  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:53:41.581  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:53:41.591  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:53:41.591  4748  4748 I AlpmModeManager: handleAlpmModeOn: state  = UNBLANK
,12-20 11:53:41.601  3509  3509 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509 (0x0)
,12-20 11:53:41.601  3509  3791 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:53:41.601  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:53:41.611  3509  3530 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:53:41.621  3509  4434 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:53:41.651  4748  4748 D DefaultClockView: End AOD Enter Animation : ForceStopAnimation : false
,12-20 11:53:41.651  4748  4748 D AODService: : state = Start AOD mode!!
12-20 11:53:41.651  3509  4333 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:53:41.681  4748  4748 D BatteryMeterView: onDraw batteryColor : -986896
,12-20 11:53:41.691  3509  4977 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:53:41.841  3509  3509 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509 (0x0)
,12-20 11:53:41.961  4748  4748 I AlpmModeManager: handleBlankDisplay: current state [ALPM_ON] to [ALPM_STATE_BLANK]
,12-20 11:53:41.961  4748  4748 V AlpmModeManager: handleBlankDisplay: setDoze [DISPLAY_STATE_DOZE_SUSPEND] Keep bright
12-20 11:53:41.961  3509  4007 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
12-20 11:53:41.961  3509  4007 I libsuspend: !@autosuspend_wakeup_count_disable
12-20 11:53:41.961  3509  4007 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
12-20 11:53:41.961  3509  4007 I libsuspend: !@autosuspend_wakeup_count_disable done
,12-20 11:53:41.961  3509  4007 D PowerManagerService: mDisplayReady: false
12-20 11:53:41.961  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-20 11:53:41.961  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-20 11:53:41.961  3509  4007 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,12-20 11:53:41.961  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:53:41.961  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:53:41.961  3509  3626 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
12-20 11:53:41.961  3509  3615 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
,12-20 11:53:41.961  3509  3615 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-20 11:53:41.961  3018  3018 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa9d43c00
,12-20 11:53:41.961  3018  3018 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,12-20 11:53:41.991  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=4
,12-20 11:53:41.991  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-20 11:53:41.991  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable
,12-20 11:53:41.991  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:53:41.991  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable done
12-20 11:53:41.991  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:53:41.991  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-20 11:53:41.991  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-20 11:53:41.991  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:53:41.991  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:53:41.991  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:53:41.991  3509  3619 D PowerManagerService: mDisplayReady: true
12-20 11:53:41.991  3509  3619 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-20 11:53:42.001  6319  6319 E CocktailBarPositionManager: Window direction: 0
12-20 11:53:42.001  6319  6319 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-20 11:53:44.671  3509  6631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-20 11:53:45.031  3509  3836 V AlarmManager: Expired Alarm result :4
,12-20 11:53:45.031  3960  3960 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,12-20 11:53:45.051  3960  3960 D FactoryTest: checkAutomationTestOption() : option=0
,12-20 11:53:45.051  3960  3960 D FactoryTest: checkAutomationTestOption() : mode_screenlock=0
,12-20 11:53:45.051  3960  3960 D KeyguardViewMediator: doKeyguard: showing the lock screen
12-20 11:53:45.051  3960  3960 D KeyguardViewMediator: showLocked
12-20 11:53:45.051  3960  3960 D KeyguardViewMediator: handleShow
,12-20 11:53:45.051  3960  3960 E KeyguardViewMediator: setShowingLocked mShowing = true
12-20 11:53:45.061  3960  3960 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
12-20 11:53:45.061  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:53:45.061  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
12-20 11:53:45.061  3960  3960 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
12-20 11:53:45.061  3960  3960 D KeyguardEffectViewController: setKeyguardShowing = true
12-20 11:53:45.061  3960  3960 D KeyguardEffectViewController: mShowing=true, mOccluded=false, mKeyguardFadingAway=false, match_parent=false
12-20 11:53:45.061  3960  3960 D StatusBarKeyguardViewManager: showBouncerOrKeyguard
12-20 11:53:45.071  3960  3960 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.KeyguardHostView$1@6791890
12-20 11:53:45.071  3960  3960 V KeyguardUpdateMonitor: *** unregister callback for null
12-20 11:53:45.081  3960  3960 D KeyguardSecurityPolicyUtils: MDM is not enabled...
12-20 11:53:45.081  3960  3960 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.KeyguardSecurityContainer$1@66b8589
12-20 11:53:45.081  3960  3960 V KeyguardUpdateMonitor: *** unregister callback for null
,12-20 11:53:45.101  3960  3960 D KeyguardSecurityModel: getSecurityMode( getActivePasswordQuality = 0 , currentuser = 0
,12-20 11:53:45.101  3960  3960 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=false)
12-20 11:53:45.101  3960  3960 D KeyguardSecurityView: showSecurityScreen(None)
,12-20 11:53:45.101  3960  3960 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
12-20 11:53:45.101  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:53:45.101  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
12-20 11:53:45.101  3960  3960 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
,12-20 11:53:45.111  3960  3960 D KeyguardSecurityModel: getSecurityMode( getActivePasswordQuality = 0 , currentuser = 0
,12-20 11:53:45.111  3960  3960 D PhoneStatusBar: showKeyguard
12-20 11:53:45.111  3960  3960 D PhoneStatusBar: setBarState: state - 1
12-20 11:53:45.111  3960  3960 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
12-20 11:53:45.111  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:53:45.111  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
,12-20 11:53:45.111  3960  3960 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
12-20 11:53:45.111  3960  3960 I PhoneStatusBar: updateKeyguardState 0 to 1
,12-20 11:53:45.121  3960  3960 D PanelView: updateQsState
,12-20 11:53:45.121  3960  3960 D KeyguardSwipeHelper: reset()
,12-20 11:53:45.121  3960  3960 D KeyguardUnlockEventHandler: reset()
12-20 11:53:45.121  3960  3960 D KeyguardSwipeHelper: resetChildViewVI()
,12-20 11:53:45.121  3960  3960 D StatusBar: LSSN:1
,12-20 11:53:45.121  3960  3960 E LSO     : LSO Service is not yet ready!!!
,12-20 11:53:45.131  3960  3960 D PanelView: setKeyguardBottomAreaVisibility() prevState=0, newState - 1 goingToShade - false
,12-20 11:53:45.131  3960  3960 D PhoneStatusBar/KeyguardBottomAreaView: updateCameraVisibility isCameraDisabledByDpm=false
,12-20 11:53:45.131  3960  3960 V KeyguardBottomAreaShortcutView: updateLeftPreview
,12-20 11:53:45.131  3960  3960 V KeyguardBottomAreaShortcutView: updateRightPreview
12-20 11:53:45.131  3960  4150 V KeyguardBottomAreaShortcutView: updateLeftPreview - mLeftAffordanceView
12-20 11:53:45.131  3960  3960 D KeyguardCircleAffordanceView: setPreviewView: mRight=false,preview=android.widget.RelativeLayout{1c33fdc I.E...... ......ID 0,0-1440,2560}
,12-20 11:53:45.161  3960  4150 V PreviewInflater: switching default dialer action
,12-20 11:53:45.171  3960  3960 D KeyguardCircleAffordanceView: setPreviewView: mRight=true,preview=android.widget.AbsoluteLayout{dbf68e5 I.E...... ......ID 0,0-1440,2560}
,12-20 11:53:45.201  3960  4150 V KeyguardBottomAreaShortcutView: updateRightPreview - mRightAffordanceView
12-20 11:53:45.201  3960  4150 D ShortcutManager: th = 1 is camera package
,12-20 11:53:45.211  3960  3960 D PanelView: updateQsState
,12-20 11:53:45.211  3960  4150 V PreviewInflater: switching default camera action
,12-20 11:53:45.221  3960  3960 D NotificationStackScrollLayout:  scroll range should be extended : 884
,12-20 11:53:45.221  3960  3960 D KeyguardSecurityModel: getSecurityMode( getActivePasswordQuality = 0 , currentuser = 0
,12-20 11:53:45.221  3960  3960 D PhoneStatusBar: Make expanded visible: expanded visible=false
12-20 11:53:45.221  3960  3960 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
12-20 11:53:45.221  3960  3960 D PhoneStatusBar: adjustDisableFlags:false, false, true, false, false, 1
12-20 11:53:45.221  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:53:45.221  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : true keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
12-20 11:53:45.221  3960  3960 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
,12-20 11:53:45.221  3960  3960 D PhoneStatusBar: disable: < expand ICONS* alerts SYSTEM_INFO* back home recent clock search quick_settings >
,12-20 11:53:45.231  6319  6319 I TrayVisibilityController: TrayStateVisibilityReceiver action :com.samsung.systemui.statusbar.ANIMATING
,12-20 11:53:45.231  3960  3960 D PhoneStatusBar: Make expanded visible: expanded visible=true
12-20 11:53:45.231  3960  3960 D StatusBar.BrightnessController: setListening  = true
,12-20 11:53:45.231  3960  3960 D KeyguardEffectViewLayered: reset()
12-20 11:53:45.231  3960  3960 D KeyguardEffectViewLayered: init()
12-20 11:53:45.231  3960  3960 D KeyguardEffectViewLayered: mViewWidth = 1440, mViewHeight = 96
12-20 11:53:45.231  3960  3960 D KeyguardEffectViewLayered: mBitmapImageList size = 3
12-20 11:53:45.231  3960  3960 D KeyguardEffectViewLayered: DENSITY = 1.0
,12-20 11:53:45.231  3960  3960 D PhoneStatusBar/KeyguardBottomAreaView: updateCameraVisibility isCameraDisabledByDpm=false
,12-20 11:53:45.231  3960  3960 D KeyguardViewBase: show()
,12-20 11:53:45.241  3960  3960 D KeyguardSecurityModel: getSecurityMode( getActivePasswordQuality = 0 , currentuser = 0
12-20 11:53:45.241  3960  3960 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=false)
,12-20 11:53:45.241  3960  3960 D KeyguardSecurityView: showSecurityScreen(None)
,12-20 11:53:45.241  3960  3960 D KeyguardUpdateMonitor: onKeyguardVisibilityChanged(true)
,12-20 11:53:45.251  3960  3960 V KeyguardFingerPrint: updateFingerprintListeningState(false)
12-20 11:53:45.251  3960  3960 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
,12-20 11:53:45.251  3960  3960 V KeyguardUpdateMonitor: stopListeningForFingerprint()
,12-20 11:53:45.251  3960  3960 D KeyguardViewMediator: adjustStatusBarLocked: mShowing=true mOccluded=false isSecure=false --> flags=0x3200000
,12-20 11:53:45.251  3509  4342 D StatusBarManagerService: manageDisableList userId=0 what=0x3200000 pkg=com.android.systemui
,12-20 11:53:45.261  3509  4487 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 133703
,12-20 11:53:45.261  3960  3960 D KeyguardViewMediator: onSdpLocked :: Inside...
12-20 11:53:45.261  3960  3960 D KeyguardViewMediator: isPwdChangeRequested :: false
12-20 11:53:45.261  3960  3960 D KeyguardViewMediator: onSdpLocked :: Lock SDP for User 0
,12-20 11:53:45.261  3960  3960 V KeyguardDisplayManager: show (false)
,12-20 11:53:45.261  3509  4334 E SdpServiceKeeper: isLicensed {pid:3960 uid:10065 userid:0 doPkg:null}
,12-20 11:53:45.261  3509  4334 E SdpServiceKeeper: System app. Skip license activation
,12-20 11:53:45.261  3509  4485 E SdpServiceKeeper: isLicensed {pid:3960 uid:10065 userid:0 doPkg:null}
,12-20 11:53:45.261  3509  4485 E SdpServiceKeeper: System app. Skip license activation
,12-20 11:53:45.261  3509  4002 D SdpManagerService: lockInternal 0
12-20 11:53:45.271  3509  4002 E SDP.CRYPTO:     On Locked OK, id 0
12-20 11:53:45.271  3509  4002 D SdpManagerService: clearCachedMasterKey (CMK) 0
12-20 11:53:45.271  3509  4002 E SdpManagerService: sendBroadcastAsUser(INTENT_SDP_STATE_CHANGED, state:1)
,12-20 11:53:45.271  3960  9574 D KeyguardViewMediator: lockSdp :: Lock SDP Successful...!
,12-20 11:53:45.281  3509  3593 V BroadcastQueue: [foreground] Process cur broadcast BroadcastRecord{2350df9 u0 com.sec.sdp.SDP_STATE_CHANGED qIdx=2}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{56c7d71 9501:com.sec.android.app.sbrowser/u0a141}
,12-20 11:53:45.281  3509  4486 E SdpServiceKeeper: isLicensed {pid:9501 uid:10141 userid:0 doPkg:null}
,12-20 11:53:45.281  3509  4486 E SdpServiceKeeper: White listed. Skip license activation
,12-20 11:53:45.281  9501  9501 E SdpStateChangedReceiver: com.sec.enterprise.knox.sdp.exception.SdpEngineNotExistsException
12-20 11:53:45.291  3018  3028 D libEGL  : eglTerminate EGLDisplay = 0x7fa9ac0e78
12-20 11:53:45.291  3018  3028 D libEGL  : eglTerminate EGLDisplay = 0x7fa9ac0e78
,12-20 11:53:45.291  3960  4161 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,12-20 11:53:45.291  3960  3960 D KeyguardEffectViewController: onLayoutChange() v: com.android.keyguard.effect.EffectBehindView{eefe3f3 I.E...... ......ID 0,0-1440,2560 #7f0e0330 app:id/keyguard_effect_behind}, bottom : 2560, oldBottom : 96
12-20 11:53:45.291  3960  3960 D KeyguardEffectViewController: mShowing=true, mOccluded=false, mKeyguardFadingAway=false, match_parent=true
,12-20 11:53:45.291  3960  3960 D NotificationStackScrollLayout:  scroll range should be extended : 884
,12-20 11:53:45.291  3960  3960 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
12-20 11:53:45.301  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:53:45.301  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : true keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
12-20 11:53:45.301  3960  3960 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
,12-20 11:53:45.401  3509  4180 E Watchdog: !@Sync 4 [12-20 11:53:45.420]
,12-20 11:53:45.441  3509  4002 V WindowStateAnimator: Finishing drawing window Window{421530f u0 d0 StatusBar}: mDrawState=DRAW_PENDING
,12-20 11:53:45.441  3960  3960 D KeyguardCircleAffordanceView: setPreviewView: mRight=false,preview=android.widget.RelativeLayout{aff2dbc I.E...... ......ID 0,0-0,0}
12-20 11:53:45.441  3960  3960 V KeyguardBottomAreaShortcutView: mLeftAffordanceView preview = android.widget.RelativeLayout{aff2dbc I.E...... ......ID 0,0-0,0}
12-20 11:53:45.441  3960  3960 D KeyguardCircleAffordanceView: setPreviewView: mRight=true,preview=android.widget.AbsoluteLayout{9fdf145 I.E...... ......ID 0,0-0,0}
12-20 11:53:45.441  3960  3960 V KeyguardBottomAreaShortcutView: mRightAffordanceView preview = android.widget.AbsoluteLayout{9fdf145 I.E...... ......ID 0,0-0,0}
12-20 11:53:45.441  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
12-20 11:53:45.441  3960  3960 D KeyguardUpdateMonitor: handleKeyguardReset
12-20 11:53:45.441  3960  3960 V KeyguardFingerPrint: updateFingerprintListeningState(false)
12-20 11:53:45.451  3018  3018 D libEGL  : eglTerminate EGLDisplay = 0x7fff7e5b48
,12-20 11:53:45.451  3960  3960 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
12-20 11:53:45.451  3960  3960 V KeyguardUpdateMonitor: stopListeningForFingerprint()
,12-20 11:53:45.451  3960  3960 D PhoneStatusBar: adjustDisableFlags:false, false, true, false, false, 1
,12-20 11:53:45.451  3960  3960 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO back HOME* RECENT* clock SEARCH* quick_settings >
,12-20 11:53:45.451  3960  3960 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,12-20 11:53:45.491  3960  3960 D KeyguardEffectViewController: onLayoutChange() v: com.android.keyguard.effect.EffectBehindView{eefe3f3 V.E...... ......I. 0,0-1440,2560 #7f0e0330 app:id/keyguard_effect_behind}, bottom : 2560, oldBottom : 2560
,12-20 11:53:45.521  3509  4342 V WindowStateAnimator: Finishing drawing window Window{421530f u0 d0 StatusBar}: mDrawState=READY_TO_SHOW
,12-20 11:53:45.531  3960  3960 D Recents : handleProxyCall type=3
,12-20 11:53:45.531  4060  4060 D Recents : handleProxyCall type=3
,12-20 11:53:45.541  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:53:45.581  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:53:46.571  4383  4489 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-20 11:53:46.571  4383  4489 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-20 11:53:49.561  3509  4487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-20 11:53:49.571  3509  4487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:53:49.571  3509  4487 D BatteryService: online:4, current avg:165, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:214
12-20 11:53:49.571  3509  4487 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3509) 
,12-20 11:53:49.571  3509  4487 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=5) set On
,12-20 11:53:49.571  3509  4487 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,12-20 11:53:49.571  3509  4487 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
12-20 11:53:49.571  3509  3625 D LightsService: [SvcLED]  onSensorChanged::light value = 24
,12-20 11:53:49.571  3509  4487 D BatteryService: turn on LED for fully charged
,12-20 11:53:49.571  3509  3625 D SensorManager: unregisterListener ::   
,12-20 11:53:49.571  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
12-20 11:53:49.571  3509  3625 D lights  : led_pattern : 5 +
,12-20 11:53:49.581  3509  3625 D lights  : led_pattern : 5 -
,12-20 11:53:49.581  3509  3509 I MotionRecognitionService: Plugged
12-20 11:53:49.581  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:53:49.581  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,12-20 11:53:49.581  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
12-20 11:53:49.581  3509  3625 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
12-20 11:53:49.581  3509  3625 V AlarmManager:  remove PendingIntent] PendingIntent{4ecf248: PendingIntentRecord{45ac606 android broadcastIntent}}
,12-20 11:53:49.581  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:53:49.591  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-20 11:53:49.591  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:53:49.591  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
12-20 11:53:49.591  3960  3960 D PowerUI.Notification: dismissChargingNotification()
,12-20 11:53:49.601  3509  3509 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3509) 
,12-20 11:53:49.601  3509  3509 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=6) set Off
,12-20 11:53:49.601  5298  5298 D CommonServiceConfiguration: getStringValueSetting
12-20 11:53:49.601  3509  3509 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,12-20 11:53:49.601  3509  3509 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
12-20 11:53:49.601  3509  3509 D EdgeLight: Turning off
,12-20 11:53:49.601  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:53:49.601  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:53:49.611  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:53:49.611  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:53:49.621  4181  4193 D CatchNotificationsService: onNotificationRemoved
12-20 11:53:49.621  4181  4193 D CatchNotificationsService: Notification removed
,12-20 11:53:49.621  3960  3960 D PhoneStatusBar: removeNotification key=-1|com.android.systemui|2131624021|charging_state|10065 old=StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=2131624021 tag=charging_state score=-20 key=-1|com.android.systemui|2131624021|charging_state|10065: Notification(pri=-2 contentView=com.android.systemui/0x10900a3 vibrate=null sound=null defaults=0x0 flags=0xa color=0xff7792a9 category=sys vis=PUBLIC secFlags=0x0 secPriority=0))
12-20 11:53:49.621  3960  3960 D PhoneStatusBar: setAreThereNotifications: N=1 any=true clearable=false
,12-20 11:53:49.621  4194  4911 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=112]
,12-20 11:53:49.621  4194  4194 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.people.package_name=android, samsung.people.notification_type=led_indicator}]
12-20 11:53:49.621  4194  4194 I PeopleStripeService: PeopleNotificationReceiver:3
,12-20 11:53:49.621  4194  4194 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
12-20 11:53:49.621  4194  4194 I PeopleDataManager: removeNotification
12-20 11:53:49.621  4194  4194 I NotificationParser: getNotiType:android,led_indicator
,12-20 11:53:49.621  4194  4194 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=true,key=null,removeAll=false
12-20 11:53:49.621  4194  4194 D PeopleDataManager: removeNotiInfo =null
,12-20 11:53:49.621  5298  5298 D BatteryMonitor: new battery level: 100
12-20 11:53:49.621  4194  4205 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.android.systemui,id=2131624021,extra=Bundle[mParcelledData.dataSize=84]
,12-20 11:53:49.621  4194  4194 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=2131624021, samsung.notification.type=normal, samsung.people.package_name=com.android.systemui}]
12-20 11:53:49.621  4194  4194 I PeopleStripeService: PeopleNotificationReceiver:3
,12-20 11:53:49.621  4194  4194 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
12-20 11:53:49.621  4194  4194 I PeopleDataManager: removeNotification
,12-20 11:53:49.621  4194  4194 I NotificationParser: getNotiType:com.android.systemui,null
12-20 11:53:49.631  4194  4194 D PeopleDataManager: removeNotiInfo: id =2131624021,packageName=com.android.systemui,isEdgeNotification=false,key=null,removeAll=false
,12-20 11:53:49.631  4194  4194 D PeopleDataManager: removeNotiInfo =null
12-20 11:53:49.631  6319  6319 I CocktailBarUiController: onUpdateCocktail: 2
12-20 11:53:49.631  6319  6319 I CocktailBarPanelManager: updatePanelItem: updateContainedPanel - 2
12-20 11:53:49.631  6319  6319 D CatchNotificationsView: setData
,12-20 11:53:49.631  6319  6319 D CatchNotificationsView: Notification removed
12-20 11:53:49.631  6319  6319 D CatchNotificationsView: No notifications left to remove
12-20 11:53:49.631  6319  6319 D CatchNotificationsView: makeNoNotificationsPanel
,12-20 11:53:49.631  6319  6319 W ResourcesManager: getTopLevelResources: /system/priv-app/AppsEdgePanel/AppsEdgePanel.apk / 1.0 running in com.samsung.android.app.cocktailbarservice rsrc of package com.samsung.android.app.appsedge
,12-20 11:53:49.631  6319  6319 W ResourcesManager: getTopLevelResources: /system/priv-app/AppsEdgePanel/AppsEdgePanel.apk / 1.0 running in com.samsung.android.app.cocktailbarservice rsrc of package com.samsung.android.app.appsedge
12-20 11:53:49.631  4748  4748 D BatteryController: saveBatteryData : level[100], status[5]
12-20 11:53:49.631  4748  4748 D AODService: Received intent, service updating android.intent.action.BATTERY_CHANGED
12-20 11:53:49.631  6319  6319 D PanelDescriptionView: updateHelpView: Apps edge2130903041 --> 2130903041 helpview reapplied:0
12-20 11:53:49.631  3509  4007 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
12-20 11:53:49.631  3509  4007 I libsuspend: !@autosuspend_wakeup_count_disable
12-20 11:53:49.631  3509  4007 D PowerManagerService: mDisplayReady: false
12-20 11:53:49.631  3509  4007 I libsuspend: !@autosuspend_wakeup_count_disable done
12-20 11:53:49.631  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-20 11:53:49.631  3509  3625 D SensorManager: unregisterListener ::   
12-20 11:53:49.631  3509  4007 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-20 11:53:49.631  6319  6319 D CocktailBarUiController: postUpdatePanel: 257
12-20 11:53:49.631  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-20 11:53:49.631  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:53:49.631  3509  3625 D LightsService: [SvcLED]  onSensorChanged::light value = 24
12-20 11:53:49.631  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:53:49.631  6319  6319 W ResourcesManager: getTopLevelResources: /system/priv-app/AppsEdgePanel/AppsEdgePanel.apk / 1.0 running in com.samsung.android.app.cocktailbarservice rsrc of package com.samsung.android.app.appsedge
,12-20 11:53:49.631  3509  3625 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
12-20 11:53:49.631  3509  3625 V AlarmManager:  remove PendingIntent] PendingIntent{4ecf248: PendingIntentRecord{45ac606 android broadcastIntent}}
12-20 11:53:49.641  3509  3626 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
12-20 11:53:49.641  3509  3615 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-20 11:53:49.641  3509  3615 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
12-20 11:53:49.641  4748  4748 D BatteryMeterView: onDraw batteryColor : -986896
12-20 11:53:49.651  3018  3018 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa9d43c00
12-20 11:53:49.651  3018  3018 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
12-20 11:53:49.661  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
,12-20 11:53:49.661  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-20 11:53:49.661  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-20 11:53:49.671  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable
12-20 11:53:49.661  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:53:49.671  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable done
12-20 11:53:49.671  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-20 11:53:49.671  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,12-20 11:53:49.671  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:53:49.671  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:53:49.671  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:53:49.671  3509  3619 D PowerManagerService: mDisplayReady: true
12-20 11:53:49.671  3509  3619 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-20 11:53:49.671  6319  6319 E CocktailBarPositionManager: Window direction: 0
,12-20 11:53:49.671  6319  6319 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-20 11:53:49.781  3509  3509 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509 (0x0)
,12-20 11:53:49.791  3509  3509 I libsuspend: !@autosuspend_wakeup_count_disable
12-20 11:53:49.791  3509  3509 D PowerManagerService: mDisplayReady: false
12-20 11:53:49.791  3509  3509 I libsuspend: !@autosuspend_wakeup_count_disable done
12-20 11:53:49.791  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-20 11:53:49.791  3509  3509 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,12-20 11:53:49.791  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-20 11:53:49.791  3018  3018 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa9d43c00
12-20 11:53:49.791  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:53:49.791  3018  3018 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,12-20 11:53:49.791  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:53:49.791  3509  3626 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
12-20 11:53:49.791  3509  3615 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
,12-20 11:53:49.791  3509  3615 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-20 11:53:49.821  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-20 11:53:49.821  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-20 11:53:49.821  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:53:49.821  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable
12-20 11:53:49.821  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:53:49.821  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable done
12-20 11:53:49.821  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-20 11:53:49.821  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
,12-20 11:53:49.821  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:53:49.821  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:53:49.821  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:53:49.821  3509  3619 D PowerManagerService: mDisplayReady: true
,12-20 11:53:49.821  3509  3619 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-20 11:53:49.841  6319  6319 E CocktailBarPositionManager: Window direction: 0
12-20 11:53:49.841  6319  6319 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-20 11:53:51.281  3509  6576 D SSRM:n  : SIOP:: AP = 310, PST = 317 (W:14), CP = 266, CUR = 165, LCD = 1
,12-20 11:53:53.141  3509  3850 D InputReader: Input event(5): value=1 when=141580384000
12-20 11:53:53.141  3509  3850 D InputReader: !@notifyKey(172), action=0
12-20 11:53:53.141  3509  3850 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=0, interactive=false
,12-20 11:53:53.141  3509  3850 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1144000  uid : 1000  pid : 3509  pkgName : WAKEUP_BOOSTER@34
,12-20 11:53:53.151  3509  3850 E SamsungWindowManager: mCoreNumLockHelper.acquire
12-20 11:53:53.151  3509  3850 D CustomFrequencyManagerService: requestCPUCore:: CPUCore value is not in the permitted range. CoreNum = 2
12-20 11:53:53.151  3509  3850 D InputManager-JNI: setInteractive(true)
12-20 11:53:53.151  3509  3850 D PowerManagerService: [api] [s] wakeUpWithReason (uid: 1000 pid: 3509) eventTime = 141580 event = 1
12-20 11:53:53.151  3509  3850 I PowerManagerService: !@[ps] Screen__On  - 2 :  wakeUpWithReason: 1 (uid: 1000 pid: 3509) (1)
12-20 11:53:53.151  3509  3850 I PowerManagerService: Waking up from dozing (uid 1000)...
12-20 11:53:53.151  3509  3850 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,12-20 11:53:53.151  3509  3850 I libsuspend: !@autosuspend_wakeup_count_disable
12-20 11:53:53.151  3509  3924 D NetworkPolicy: onScreenStateChanged, state: true, reason: 2
12-20 11:53:53.151  3509  3850 I libsuspend: !@autosuspend_wakeup_count_disable done
12-20 11:53:53.151  3509  3850 D PowerManagerService: [s] UserActivityState : 4 -> 1
12-20 11:53:53.151  3509  3850 D InputManager-JNI: !@handleInterceptActions(172), action=0, wmActions=0
12-20 11:53:53.151  3509  3850 D PowerManagerService: mDisplayReady: false
12-20 11:53:53.151  3509  3850 D InputManager-JNI: Disable repeat for home key when device wake up
12-20 11:53:53.151  3509  3850 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-20 11:53:53.151  3509  3924 V KeyguardServiceDelegate: onStartedWakingUp()
12-20 11:53:53.151  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:53:53.151  3509  3619 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@2d8b1b)
12-20 11:53:53.151  3509  3619 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_OFF -> REPORTED_TO_POLICY_SCREEN_TURNING_ON.
12-20 11:53:53.151  3509  3619 D DisplayPowerController: mWindowManagerPolicy.screenTurningOn(mPendingScreenOnUnblocker, 0)
12-20 11:53:53.151  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:53:53.151  3509  3619 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
12-20 11:53:53.151  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:53:53.151  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
12-20 11:53:53.151  3960  4906 D KeyguardViewMediator: onStartedWakingUp, seq = 3
12-20 11:53:53.151  3509  3926 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : registerListenerRunnable
12-20 11:53:53.151  3960  4906 D KeyguardViewMediator: notifyStartedWakingUp
,12-20 11:53:53.151  3960  3960 D KeyguardViewMediator: handleNotifyWakingUp
12-20 11:53:53.151  3960  3960 D PhoneStatusBar: onUnlockHintStarted isSmartLock = false, isInSecureByLockTimeout=false
12-20 11:53:53.151  3509  3626 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> ON brightness: 1 -> 1
12-20 11:53:53.151  3960  4906 D KeyguardViewMediator: notifyScreenOn
,12-20 11:53:53.151  3509  3926 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for AUTO_BRIGHTNESS
12-20 11:53:53.151  3509  3615 I DisplayManagerService: Display device changed state: "Wbudowany ekran", ON
12-20 11:53:53.151  3509  3615 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", ON
12-20 11:53:53.151  3018  3018 D SurfaceFlinger: Set power mode=2, type=0 flinger=0x7fa9d43c00
12-20 11:53:53.151  3018  3018 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(2)
12-20 11:53:53.151  3509  3926 I CAE     : setPropertyValue(AutoBrightnessRunner.java:129) - Mode = 0
12-20 11:53:53.151  3509  3926 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 48, 1, 0,
12-20 11:53:53.151  3509  3926 D SensorHubManager: SendSensorHubData: send data = -63, 23, 48, 1, 0
,12-20 11:53:53.161  3182  3182 D Sensorhubs: sendContextData: -63, 23, 48, 1, 0
,12-20 11:53:53.171  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:53:53.171  3509  3619 V KeyguardServiceDelegate: onScreenTurnedOn()
12-20 11:53:53.171  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:53:53.171  3509  9579 D MISC PowerHAL: sysfs_write +: /sys/class/input/event0/device/enabled: 1
12-20 11:53:53.171  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:53:53.171  3509  9580 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 1
12-20 11:53:53.171  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
12-20 11:53:53.171  3509  9579 D MISC PowerHAL: sysfs_write -: /sys/class/input/event0/device/enabled: 1
12-20 11:53:53.171  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:53:53.171  3509  9580 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 1
12-20 11:53:53.171  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:53:53.171  3509  3626 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 1
12-20 11:53:53.171  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:53:53.171  3509  3626 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 1
12-20 11:53:53.171  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
12-20 11:53:53.171  3509  3925 D lights  : button : 1 +
12-20 11:53:53.171  3509  3619 D DisplayPowerController: [M OS] 0 Notify policy about screen turned on.
12-20 11:53:53.171  3509  3925 D lights  : button : 1 -
12-20 11:53:53.171  3509  3619 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_TURNING_ON -> REPORTED_TO_POLICY_SCREEN_ON.
12-20 11:53:53.171  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:53:53.171  3960  3979 D KeyguardViewMediator: notifyScreenTurnedOn
12-20 11:53:53.171  3509  3619 D PowerManagerService: mDisplayReady: true
12-20 11:53:53.171  3509  3595 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 com.android.server.policy.sec.SamsungPhoneWindowManager$22.run:4527 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:158 
,12-20 11:53:53.171  3509  3926 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-20 11:53:53.171  3509  3926 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for AUTO_BRIGHTNESS
12-20 11:53:53.171  3509  3926 D SContext.CaeProvider: setAttribute() : 0
,12-20 11:53:53.171  3509  3926 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for AUTO_BRIGHTNESS
12-20 11:53:53.171  3509  3926 V CAE     : start(ContextProvider.java:128)
,12-20 11:53:53.171  6319  6319 E CocktailBarPositionManager: Window direction: 0
12-20 11:53:53.171  6319  6319 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
12-20 11:53:53.171  3509  3926 V CAE     : clear(AutoBrightnessRunner.java:297)
12-20 11:53:53.181  3509  3926 V CAE     : enable(AutoBrightnessRunner.java:256)
12-20 11:53:53.181  3509  3926 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 48, 0,
12-20 11:53:53.181  3509  3926 D SensorHubManager: SendSensorHubData: send data = -79, 48, 0
,12-20 11:53:53.181  3182  3222 D Sensorhubs: sendContextData: -79, 48, 0
,12-20 11:53:53.181  3509  3615 I WindowManager: finishPostLayoutPolicyLw : mNightClock.hideLw by screenTurnedOn
,12-20 11:53:53.181  3509  3615 V WindowOrientationListener: setCurrentAppOrientation :1
12-20 11:53:53.181  3509  3615 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,12-20 11:53:53.191  3509  3926 D CAE     : getFaultDetectionResult(AutoBrightnessRunner.java:311) - true
,12-20 11:53:53.191  3509  3926 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:53:53.191  3509  3509 D LightsService: [api] [SvcLED] turnOff:: id = 5 (uid: 1000 pid: 3509) 
,12-20 11:53:53.191  3509  3509 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=5) set Off
12-20 11:53:53.191  3509  3509 D BatteryService: turn off LED
12-20 11:53:53.191  3509  3625 D LightsService: [SvcLED] handleForcedSvcLEDTask()
12-20 11:53:53.191  3509  3625 I LightsService: fileWriteInt : /sys/class/sec/led/led_lowpower  value : 1
12-20 11:53:53.191  3509  3625 D lights  : led_pattern : 0 +
,12-20 11:53:53.191  3509  3615 D InputDispatcher: Focus left window: 4748
12-20 11:53:53.191  3509  3615 D PowerManagerService: [api] setUserActivityTimeoutOverrideFromWindowManagerInternal: timeoutMillis: 10000
12-20 11:53:53.191  3509  3615 D InputDispatcher: Focus entered window: 3960
12-20 11:53:53.191  3509  3615 D PowerManagerService: [s] getScreenOffTimeoutLocked: 30000 -> 10000
,12-20 11:53:53.191  3509  3615 D PowerManagerService: [api] setScreenDimDurationOverrideFromWindowManagerInternal: timeoutMillis: 0
,12-20 11:53:53.191  3509  3625 D lights  : led_pattern : 0 -
12-20 11:53:53.191  3509  3625 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,12-20 11:53:53.201  3509  3926 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:53:53.201  3509  3926 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
12-20 11:53:53.201  3509  3926 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
,12-20 11:53:53.201  3509  4342 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:StatusBar uid=1000 pid=3509
12-20 11:53:53.201  3509  3926 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
12-20 11:53:53.201  3509  3615 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3509 uid:1000
12-20 11:53:53.201  3509  3615 D PointerIcon: setMouseCustomIcon IconType is same.101
,12-20 11:53:53.201  3509  3926 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@cebf089, Service : DEVICE_PHYSICAL_CONTEXT_MONITOR(1)
12-20 11:53:53.201  3509  3926 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@f989b9f, Service : AUTO_BRIGHTNESS(1)
,12-20 11:53:53.201  3509  3926 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for AUTO_BRIGHTNESS
12-20 11:53:53.201  3509  3926 D SContextService: 	.registerCallback : 2, client=
12-20 11:53:53.201  3509  3926 D SContextService: ===== SContext Service List =====
12-20 11:53:53.201  3509  3926 D PowerManagerUtil: Excessive delay in SensorHubAutoBrightnessEnabled::registerListener done: 57ms
12-20 11:53:53.201  3509  3926 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@6b5588e, Service : Device Physical Context Monitor
12-20 11:53:53.201  3509  3926 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@f5ee4ec, Service : Auto Brightness
12-20 11:53:53.201  3509  3926 D SContextManager:   .registerListener : listener = com.android.server.display.AutomaticBrightnessController$6@d74e31, service=Auto Brightness
12-20 11:53:53.201  3960  3960 V KeyguardFingerPrint: updateFingerprintListeningState(false)
12-20 11:53:53.211  3960  3960 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
12-20 11:53:53.211  3960  3960 V KeyguardUpdateMonitor: stopListeningForFingerprint()
,12-20 11:53:53.211  3509  3595 V WindowManager: MSG_REQUEST_TRAVERSAL_BY_PWM
,12-20 11:53:53.211  4748  4748 I AODService: onStartCommand : action : com.samsung.android.app.aodservice.intent.action.AOD_SCREEN_ON
12-20 11:53:53.211  3509  3595 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{421530f u0 d0 StatusBar}
12-20 11:53:53.211  4748  4748 I AODService: onCreate cause: [12-20 11:51:46.639][AOD:true, NightClock:false]<com.samsung.android.app.aodservice.intent.action.AOD_SCREEN_ON> (when Screen on ...)
,12-20 11:53:53.211  3960  3960 D KeyguardViewMediator: handleNotifyScreenTurningOn
,12-20 11:53:53.211  3960  3960 D KeyguardEffectViewController: onScreenTurningOn
12-20 11:53:53.211  3960  3960 D KeyguardEffectViewController: ## mBackgroundView.onResume()
12-20 11:53:53.211  3960  3960 D KeyguardEffectViewLayered: onResume()
,12-20 11:53:53.231  4748  4748 I AlpmModeManager: stopAlpmMode: state  = BLANK
12-20 11:53:53.231  4748  4748 I AlpmModeManager: handleAlpmModeOff: state  = BLANK
12-20 11:53:53.231  4748  4748 I AlpmModeManager: handleAlpmModeOff: AlpmModeManager wakeLock [RELEASE]
,12-20 11:53:53.231  3509  4092 D PowerManagerService: [api] release WakeLock flags=0x40 tag=AlpmModeManager uid=10000 pid=4748 (0x0)
,12-20 11:53:53.231  4748  4748 V AlpmModeManager: handleAlpmModeOff: setDozeOverrideFromAod DISPLAY_STATE_UNKNOWN
12-20 11:53:53.231  3960  3960 D KeyguardViewMediator: IKeyguardDrawnCallback.onDrawn()
12-20 11:53:53.231  3509  4333 V KeyguardServiceDelegate: **** SHOWN CALLED ****
12-20 11:53:53.231  3509  3595 V WindowManager: MSG_REQUEST_TRAVERSAL_BY_PWM
,12-20 11:53:53.231  3509  4485 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 0, Brightness = 0, wakefulness = true
12-20 11:53:53.231  3509  4485 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
12-20 11:53:53.231  4748  4748 D AODService.ClockTimer: stop
12-20 11:53:53.231  3509  3595 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,12-20 11:53:53.231  3509  3595 I CAE     : setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
,12-20 11:53:53.241  3509  3595 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-20 11:53:53.241  3509  3509 I CAE     : handleMessage(CaPowerManager.java:188) - AP_WAKEUP
12-20 11:53:53.241  3509  3509 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_WAKEUP
12-20 11:53:53.241  3509  3595 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
12-20 11:53:53.241  3509  3595 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for AUTO_ROTATION
12-20 11:53:53.241  3509  3509 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -47, 0,
,12-20 11:53:53.241  3509  3509 D SensorHubManager: SendSensorHubData: send data = -76, 13, -47, 0
12-20 11:53:53.241  3509  3595 V CAE     : start(ContextProvider.java:128)
12-20 11:53:53.241  3182  7712 D Sensorhubs: sendContextData: -76, 13, -47, 0
,12-20 11:53:53.241  4748  4748 I AODService.ClockTimer: stopAlarm : TICK
12-20 11:53:53.241  3509  3595 V CAE     : clear(AutoRotationRunner.java:182)
12-20 11:53:53.241  3509  3595 V CAE     : enable(AutoRotationRunner.java:158)
12-20 11:53:53.241  3509  3509 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
12-20 11:53:53.241  3509  3595 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 7, 0, 0,
12-20 11:53:53.241  3509  3595 D SensorHubManager: SendSensorHubData: send data = -79, 7, 0, 0
12-20 11:53:53.241  3960  3960 D KeyguardViewMediator: handleNotifyScreenTurnedOn
,12-20 11:53:53.241  3182  3182 D Sensorhubs: sendContextData: -79, 7, 0, 0
12-20 11:53:53.241  3509  4486 V AlarmManager:  remove PendingIntent] PendingIntent{faf90b5: PendingIntentRecord{cb26099 com.samsung.android.app.aodservice broadcastIntent}}
,12-20 11:53:53.241  4748  4748 I AODService.ClockTimer: stopAlarm : SLEEP
,12-20 11:53:53.241  3509  3595 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
12-20 11:53:53.241  3509  3595 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
12-20 11:53:53.241  3960  3960 D SecKeyguardStatusView: onScreenTurnedOn()
12-20 11:53:53.241  3509  4092 V AlarmManager:  remove PendingIntent] PendingIntent{cd5f34a: PendingIntentRecord{4e596cd com.samsung.android.app.aodservice broadcastIntent}}
,12-20 11:53:53.241  4748  4748 I AODService.ClockTimer: stopAlarm : WAKEUP
,12-20 11:53:53.251  3960  3960 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
12-20 11:53:53.251  3509  3842 E MotionRecognitionService:  handler : SCREEN_ON end
,12-20 11:53:53.251  3509  3595 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:53:53.261  3509  3850 D InputReader: Input event(5): value=0 when=141700169000
12-20 11:53:53.261  3509  3850 D InputReader: !@notifyKey(172), action=1
12-20 11:53:53.261  3509  3850 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=1, interactive=true
,12-20 11:53:53.261  3509  4977 V AlarmManager:  remove PendingIntent] PendingIntent{c7552bb: PendingIntentRecord{d5689d1 com.samsung.android.app.aodservice broadcastIntent}}
12-20 11:53:53.261  3509  3595 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
12-20 11:53:53.261  3509  3595 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
,12-20 11:53:53.261  3509  3595 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
12-20 11:53:53.261  3509  3595 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@cebf089, Service : DEVICE_PHYSICAL_CONTEXT_MONITOR(1)
12-20 11:53:53.261  3509  3595 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@f989b9f, Service : AUTO_BRIGHTNESS(1)
12-20 11:53:53.261  3509  3595 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@4cb63d8, Service : AUTO_ROTATION(1)
,12-20 11:53:53.261  3509  3595 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for AUTO_ROTATION
12-20 11:53:53.261  3509  3595 D SContextService: 	.registerCallback : 3, client=
12-20 11:53:53.261  3509  3595 D SContextService: ===== SContext Service List =====
12-20 11:53:53.261  3509  3595 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@6b5588e, Service : Device Physical Context Monitor
12-20 11:53:53.261  3509  3595 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@f5ee4ec, Service : Auto Brightness
12-20 11:53:53.261  3509  3595 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4158331, Service : Auto Rotation
12-20 11:53:53.261  3509  3595 D SContextManager:   .registerListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@8adcaff, service=Auto Rotation
,12-20 11:53:53.261  3509  4487 D SettingsProvider: isChangeAllowed() : name = aod_show_state
12-20 11:53:53.261  3509  4487 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
12-20 11:53:53.261  3509  4487 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
12-20 11:53:53.261  3509  3850 D InputManager-JNI: !@handleInterceptActions(172), action=1, wmActions=1
12-20 11:53:53.261  3509  4487 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
12-20 11:53:53.261  3509  4487 D SettingsProvider: selectionArgs: false
,12-20 11:53:53.261  3509  4487 D SettingsProvider: selectionArgs: 10000
12-20 11:53:53.261  3509  4487 D SettingsProvider: ret = -1
,12-20 11:53:53.261  3509  3509 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_ON
,12-20 11:53:53.261  4748  4748 E SettingsUtils: setAODShowState  config = 0
12-20 11:53:53.261  4748  4748 D ScoverManager: unregisterListener
12-20 11:53:53.261  3509  4486 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,12-20 11:53:53.261  3509  3849 D VoIPInterfaceManager: isVoIPRinging()...
12-20 11:53:53.261  3509  3849 I WindowManager: Ignoring HOME; down is not pressed.
12-20 11:53:53.261  3509  3849 D VoIPInterfaceManager: isVoIPRunningAndDeregi()...
12-20 11:53:53.261  3509  4434 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
12-20 11:53:53.261  3509  3849 D VoIPInterfaceManager: Not exist call session
12-20 11:53:53.261  3509  4434 D CoverManager.StateNotifier: unregisterCallback : binder = android.os.BinderProxy@405e8b6, pid : 4748, uid : 10000
,12-20 11:53:53.261  3509  3791 I Sensors : Light old sensor_state 512, new sensor_state : 0 en : 0
,12-20 11:53:53.271  3509  3509 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
12-20 11:53:53.271  3509  3509 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
,12-20 11:53:53.271  3509  3509 D UcmService: notifyChangeToPlugin event 15
12-20 11:53:53.271  3509  3509 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
12-20 11:53:53.271  3509  3509 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
12-20 11:53:53.271  3509  3509 D UcmService: notifying to unmanaged plugin
12-20 11:53:53.271  4378  4418 E ucsBai_agentService: notifyChange NOT SUPPORTED
12-20 11:53:53.271  3509  3509 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
12-20 11:53:53.271  3509  3509 D UcmService: agentService status-0
12-20 11:53:53.271  3509  3509 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.ese:eSE Credential Storage Package name = com.samsung.ucs.agent.ese
12-20 11:53:53.271  3509  3509 D UcmService: notifying to managed plugin
12-20 11:53:53.271  3509  3509 D UcmService: checkIfNotify: Valid userid - 0
12-20 11:53:53.271  4748  4748 D SensorManager: unregisterListener ::   
,12-20 11:53:53.271  3509  3509 D PolicyManager: PolicyManager.isStorageEnabled() for userId = 0
12-20 11:53:53.271  3509  3509 D UniversalCredentialManagerService: checkCallerPermissionFor is called for method-isCredentialStorageManagedAsUser
12-20 11:53:53.271  3509  3509 D UniversalCredentialManagerService: isCredentialStorageManagedAsUser is called....
12-20 11:53:53.271  3509  3509 D PolicyManager: PolicyManager.isStorageEnabled() result = false
12-20 11:53:53.271  3509  3509 D UcmService: agentService com.samsung.ucs.agent.ese:eSE Credential Storage not notified
12-20 11:53:53.271  3509  3509 D UcmService: agentService status-0
12-20 11:53:53.271  3509  3509 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
12-20 11:53:53.271  3509  3509 D UcmService: notifying to unmanaged plugin
,12-20 11:53:53.271  4396  4424 D BootAgentService: notifyChange eventId-15
12-20 11:53:53.271  3509  3509 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
12-20 11:53:53.271  3509  3509 D UcmService: agentService status--1
12-20 11:53:53.271  3509  3509 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
12-20 11:53:53.271  4748  4748 I AlpmModeManager: handleUnblankDisplay: state  = ALPM_OFF
12-20 11:53:53.271  3509  4342 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@6b5588e, Service = Device Physical Context Monitor, used = 0
,12-20 11:53:53.271  3509  4342 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:53:53.271  3509  4342 V CAE     : stop(ContextProvider.java:155)
,12-20 11:53:53.271  3509  4342 V CAE     : clear(DevicePhysicalContextMonitorRunner.java:497)
,12-20 11:53:53.271  3509  4342 V CAE     : disable(DevicePhysicalContextMonitorRunner.java:486)
,12-20 11:53:53.271  3509  4342 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 56, 0, 0,
12-20 11:53:53.271  3509  4342 D SensorHubManager: SendSensorHubData: send data = -78, 56, 0, 0
12-20 11:53:53.271  3182  3222 D Sensorhubs: sendContextData: -78, 56, 0, 0
,12-20 11:53:53.281  3509  4342 D CAE     : getFaultDetectionResult(DevicePhysicalContextMonitorRunner.java:521) - true
,12-20 11:53:53.281  3509  4342 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:53:53.281  3509  3509 I WifiTrafficPoller: evaluateTrafficStatsPolling
,12-20 11:53:53.291  3509  4342 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:53:53.291  3509  4342 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
12-20 11:53:53.291  3509  4342 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
,12-20 11:53:53.291  3509  4342 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
12-20 11:53:53.291  3509  4342 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@f989b9f, Service : AUTO_BRIGHTNESS(1)
12-20 11:53:53.291  3509  4342 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@4cb63d8, Service : AUTO_ROTATION(1)
,12-20 11:53:53.291  3509  4342 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:53:53.291  3509  3881 D WifiStateMachine: handleScreenStateChanged, screen on, start periodic scan !!!
,12-20 11:53:53.291  3509  3881 D WifiNative-wlan0: callSECApiBoolean - ID [11]
12-20 11:53:53.291  4152  4152 I wpa_supplicant: STOP_PERIODIC_SCAN command
,12-20 11:53:53.291  3509  4342 D SContextService: 	.unregisterCallback : 3, client=
12-20 11:53:53.291  3509  4342 D SContextService: ===== SContext Service List =====
12-20 11:53:53.291  3509  4342 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@f5ee4ec, Service : Auto Brightness
12-20 11:53:53.291  3509  4342 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4158331, Service : Auto Rotation
12-20 11:53:53.291  4748  9583 D SContextManager:   .unregisterListener : listener = com.samsung.android.app.aodservice.AODService$7@de2fb91, service=Device Physical Context Monitor
,12-20 11:53:53.291  3509  3509 D NotificationService: ACTION_SCREEN_ON
,12-20 11:53:53.301  3509  3509 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3509) 
12-20 11:53:53.301  3509  3509 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=6) set Off
12-20 11:53:53.301  3509  3509 D EdgeLight: Turning off
12-20 11:53:53.301  3509  3625 D LightsService: [SvcLED] handleForcedSvcLEDTask()
12-20 11:53:53.301  3509  3625 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,12-20 11:53:53.301  3175  3878 D audio_hw_primary: adev_set_parameters: enter: kvpairs: screen_state=on
,12-20 11:53:53.301  4194  4204 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=112]
12-20 11:53:53.301  4194  4194 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.people.package_name=android, samsung.people.notification_type=led_indicator}]
12-20 11:53:53.301  4194  4194 I PeopleStripeService: PeopleNotificationReceiver:3
,12-20 11:53:53.301  4194  4194 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
12-20 11:53:53.301  4194  4194 I PeopleDataManager: removeNotification
12-20 11:53:53.301  4194  4194 I NotificationParser: getNotiType:android,led_indicator
,12-20 11:53:53.301  4194  4194 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=true,key=null,removeAll=false
12-20 11:53:53.301  4194  4194 D PeopleDataManager: removeNotiInfo =null
,12-20 11:53:53.311  3509  3509 V AlarmManager:  remove PendingIntent] PendingIntent{ac7d00c: PendingIntentRecord{dbf6d55 android broadcastIntent}}
,12-20 11:53:53.321  3509  3509 I MdnieScenarioControlService: action  :  android.intent.action.SCREEN_ON
,12-20 11:53:53.321  3509  3509 I MdnieScenarioControlService: mGameModeLauncher : false
12-20 11:53:53.321  3509  3509 I MdnieScenarioControlService: setUIMode
,12-20 11:53:53.321  3509  3881 E WifiNative-wlan0: do suspend false
,12-20 11:53:53.341  3509  3509 D WifiService: ACTION_SCREEN_ON, checkSensorStatus !!
12-20 11:53:53.341  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155650
12-20 11:53:53.341  3509  3884 V AlarmManager:  remove PendingIntent] PendingIntent{47c8c36: PendingIntentRecord{d7614a4 android broadcastIntent}}
,12-20 11:53:53.341  3509  3509 E SContext.CaeProvider: setAttribute() : attribute is null!
12-20 11:53:53.341  3509  3509 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for ACTIVITY_TRACKER
,12-20 11:53:53.341  3509  3509 V CAE     : start(ContextProvider.java:128)
,12-20 11:53:53.341  3509  3881 D WifiStateMachine: analyze kernel wifi wakelock 
12-20 11:53:53.341  3509  3509 V CAE     : clear(ActivityTrackerRunner.java:108)
12-20 11:53:53.341  3509  3881 D WifiStateMachine: file not found /proc/wakelocks
,12-20 11:53:53.341  3509  3509 V CAE     : enable(ActivityTrackerRunner.java:84)
12-20 11:53:53.341  3509  3509 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 10, 53, 53,
12-20 11:53:53.341  3509  3509 D SensorHubManager: SendSensorHubData: send data = -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 10, 53, 53
,12-20 11:53:53.341  3182  7712 D Sensorhubs: sendContextData: -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 10, 53, 53
,12-20 11:53:53.341  3182  3221 D Sensorhubs: readContextData: 1, 1, 48, 0, 0, 0, 107, 0, 0, 0, 24
,12-20 11:53:53.351  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(11) = 1, 1, 48, 0, 0, 0, 107, 0, 0, 0, 24
12-20 11:53:53.351  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :11], AP_WAKEUP
12-20 11:53:53.351  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 11
12-20 11:53:53.351  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 48, 0, 0, 0, 107, 0, 0, 0, 24,
12-20 11:53:53.351  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= AUTO_BRIGHTNESS =================
,12-20 11:53:53.351  3509  3838 I CAE     : display(ContextProvider.java:391) - Candela=[107], AmbientLux=[24]
12-20 11:53:53.351  3509  3509 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
12-20 11:53:53.351  3509  3926 D AutomaticBrightnessController: [DAB] onSensorHubChanged : 1st lux = 24.0, 1st candela = 107.0
12-20 11:53:53.351  3509  3841 D SContextService: updateSContext() : event = Auto Brightness
12-20 11:53:53.351  3509  3926 D AutomaticBrightnessController: [DAB] updateAutoBrightnessSEC : 107(106.717804)    0.0 < 24.0 < 225.0 (0.0)
12-20 11:53:53.351  3509  3509 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
12-20 11:53:53.351  3509  3926 D AutomaticBrightnessController: mCallbacks.updateBrightness()
12-20 11:53:53.351  3509  3926 D PowerManagerUtil: fileWriteInt to /sys/class/tcon/tcon/auto_br, 1
12-20 11:53:53.351  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
,12-20 11:53:53.351  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:53:53.351  3509  3619 D PowerManagerUtil: fileWriteInt to /sys/class/lcd/panel/lux, 24
12-20 11:53:53.351  3509  3619 D PowerManagerUtil: fileWriteInt to /sys/class/backlight/panel/auto_brightness, 2
,12-20 11:53:53.351  3509  3619 D PowerManagerUtil: fileWriteInt to /sys/class/mdnie/mdnie/auto_brightness, 2
12-20 11:53:53.351  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 107 -> 107
12-20 11:53:53.351  3509  3619 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
,12-20 11:53:53.351  3509  3619 D DisplayPowerController: Tracking Direct to etc : 107
12-20 11:53:53.351  3509  3619 D DisplayPowerController: Animating brightness: target=107, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:53:53.351  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:53:53.351  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:53:53.351  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 107 -> 107
,12-20 11:53:53.351  3509  3619 D DisplayPowerController: Animating brightness: target=107, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:53:53.351  3509  3927 D lights  : lcd : 107 +
,12-20 11:53:53.361  3509  3509 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:53:53.361  3509  3509 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,12-20 11:53:53.371  3509  3509 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
,12-20 11:53:53.371  3509  3509 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
12-20 11:53:53.371  3509  3509 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER(1)
12-20 11:53:53.371  3509  3509 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@f989b9f, Service : AUTO_BRIGHTNESS(1)
12-20 11:53:53.371  3509  3509 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@4cb63d8, Service : AUTO_ROTATION(1)
12-20 11:53:53.371  3509  3509 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for ACTIVITY_TRACKER
12-20 11:53:53.371  3509  3509 D SContextService: 	.registerCallback : 3, client=
12-20 11:53:53.371  3509  3509 D SContextService: ===== SContext Service List =====
12-20 11:53:53.371  3509  3509 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@f5ee4ec, Service : Auto Brightness
12-20 11:53:53.371  3509  3509 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4158331, Service : Auto Rotation
12-20 11:53:53.371  3509  3509 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@89c5f97, Service : Activity Tracker
12-20 11:53:53.371  3509  3509 D SContextManager:   .registerListener : listener = com.android.server.wifi.WifiServiceImpl$11@407fa16, service=Activity Tracker
12-20 11:53:53.371  3509  3509 W CAE     : getContextInfo(ContextAwareService.java:457) - [getContext 01] Mutex is locked for ACTIVITY_TRACKER_CURRENT_INFO
,12-20 11:53:53.371  3509  3509 V CAE     : enable(ActivityTrackerCurrentInfoRunner.java:178)
12-20 11:53:53.371  3509  3509 V CAE     : clear(ActivityTrackerCurrentInfoRunner.java:202)
,12-20 11:53:53.371  3509  3509 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 26, 1, 0,
12-20 11:53:53.371  3509  3509 D SensorHubManager: SendSensorHubData: send data = -72, 26, 1, 0
12-20 11:53:53.371  3182  3182 D Sensorhubs: sendContextData: -72, 26, 1, 0
,12-20 11:53:53.371  3509  3509 D CAE     : getFaultDetectionResult(ActivityTrackerCurrentInfoRunner.java:214) - true
,12-20 11:53:53.371  3509  3509 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:53:53.381  3509  3509 W CAE     : getContextInfo(ContextAwareService.java:511) - [getContext 02] Mutex is unlocked for ACTIVITY_TRACKER_CURRENT_INFO
12-20 11:53:53.381  3509  3509 D SContextService: requestToUpdate() : service = Activity Tracker
,12-20 11:53:53.381  3509  3509 D SContextManager:   .requestToUpdate : listener = com.android.server.wifi.WifiServiceImpl$11@407fa16, service=Activity Tracker
12-20 11:53:53.391  3509  3927 D lights  : lcd : 107 -
12-20 11:53:53.391  3509  3927 D DisplayPowerState: Tracking!!: 107
,12-20 11:53:53.391  3509  3927 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
12-20 11:53:53.391  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:53:53.391  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:53:53.391  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 107 -> 107
12-20 11:53:53.391  3509  3619 D DisplayPowerController: Animating brightness: target=107, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:53:53.391  3509  3509 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:StatusBar uid=1000 pid=3509 (0x0)
,12-20 11:53:53.391  3960  3960 V StatusBar.BrightnessController: BRIGHTNESS_PMS_MARKER_SCREEN changed
,12-20 11:53:53.391  3509  3615 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
12-20 11:53:53.391  3509  3615 D IpRemoteDisplayController: Bridge Server is not available
,12-20 11:53:53.391  3960  3960 V StatusBar.BrightnessController: updateSlider = 107
,12-20 11:53:53.391  3509  3879 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 1
,12-20 11:53:53.401  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10009, mScreenOn: true, uidstate: 0, mProxSensorScreenOff: false
12-20 11:53:53.401  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: true, uidstate: 3, mProxSensorScreenOff: false
,12-20 11:53:53.401  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10065, mScreenOn: true, uidstate: 0, mProxSensorScreenOff: false
12-20 11:53:53.401  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10072, mScreenOn: true, uidstate: 3, mProxSensorScreenOff: false
,12-20 11:53:53.401  3182  3221 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, 86, -92, -78, -1, 0
,12-20 11:53:53.401  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, 86, -92, -78, -1, 0
12-20 11:53:53.411  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
12-20 11:53:53.411  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
12-20 11:53:53.411  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, 86, -92, -78, -1, 0,
,12-20 11:53:53.411  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
12-20 11:53:53.411  3509  3838 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[-1], TimeStamp=[1482231232690]
12-20 11:53:53.411  3509  3841 D SContextService: updateSContext() : event = Activity Tracker
12-20 11:53:53.411  3509  3509 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
,12-20 11:53:53.411  3509  3589 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,12-20 11:53:53.411  3960  3960 I ViewCaptureUtil: Capture the lockscreen
,12-20 11:53:53.421  4253  4253 D FusedLocationReceiver: BroadcastReceiver : ACTION_SCREEN_ON
,12-20 11:53:53.421  3509  3509 D PersonaManagerService: ACTION_SCREEN_ON onReceive
,12-20 11:53:53.421  3509  3631 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
,12-20 11:53:53.421  3182  3221 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, 86, -91, 2, 0, 2
,12-20 11:53:53.421  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, 86, -91, 2, 0, 2
12-20 11:53:53.421  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
12-20 11:53:53.421  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
12-20 11:53:53.421  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, 86, -91, 2, 0, 2,
12-20 11:53:53.421  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
,12-20 11:53:53.421  3509  3838 I CAE     : display(ContextProvider.java:391) - Accuracy=[2], OperationMode=[0], ActivityType=[0], TimeStamp=[1482231232770]
12-20 11:53:53.421  3509  3841 D SContextService: updateSContext() : event = Activity Tracker
12-20 11:53:53.421  3509  4334 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,12-20 11:53:53.421  4304  4304 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_LOCKED by isKeyguardLocked()
,12-20 11:53:53.431  4304  9585 D NfcService: call the applyRouting
,12-20 11:53:53.431  3509  3509 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
12-20 11:53:53.431  3509  3509 D WifiStateMachine: setWifiScanMove bMove = 0
12-20 11:53:53.431  3509  3509 D WifiService: ACTIVITY_STATUS_UNKNOWN 
12-20 11:53:53.431  3509  3509 I WifiStateMachine: not vehicle, sendMessageDelayed CMD_SET_SCAN_MOVE with 0
12-20 11:53:53.431  3509  3509 D WifiService: setWifiScanWithSensor bMove = 0
,12-20 11:53:53.431  3509  3881 I WifiStateMachine: DriverStartedState :: CMD_SET_SCAN_MOVE(0) 
,12-20 11:53:53.431  4152  4152 I wpa_supplicant: @@wpa_supplicant_set_scan_move : set [0]
,12-20 11:53:53.431  3960  4176 D NetworkController.MobileSignalController(0/2147483643): onDataActivity: direction=0
,12-20 11:53:53.431  4748  4748 D AODService: dismissWindow
,12-20 11:53:53.431  4748  4748 D DefaultClockView:  dismiss
,12-20 11:53:53.441  3018  3030 D libEGL  : eglTerminate EGLDisplay = 0x7fa983ee78
12-20 11:53:53.441  3018  3030 D libEGL  : eglTerminate EGLDisplay = 0x7fa983ee78
,12-20 11:53:53.441  4748  4748 D ViewRootImpl: #3 mView = null
,12-20 11:53:53.441  3018  3028 I SurfaceFlinger: id=22 Removed BOD (8/10)
,12-20 11:53:53.441  3018  3112 I SurfaceFlinger: id=22 Removed BOD (-2/10)
,12-20 11:53:53.441  3018  3018 D libEGL  : eglTerminate EGLDisplay = 0x7fff7e5bd8
,12-20 11:53:53.451  3509  3509 V AlarmManager:  remove PendingIntent] PendingIntent{ada74ef: PendingIntentRecord{147b977 android broadcastIntent}}
,12-20 11:53:53.461  5257  5257 D BtGatt.GattService: LCD turned on
,12-20 11:53:53.461  5257  5430 D BtGatt.ScanManager: handleLcdOnIntent
12-20 11:53:53.461  5257  5430 D BtGatt.ScanManager: handleLcdOnIntent
12-20 11:53:53.461  5257  5430 D BtGatt.ScanManager: ClientIf = 0
,12-20 11:53:53.471  6319  6319 D CocktailBarUiController: ACTION_SCREEN_ON
12-20 11:53:53.471  6319  6319 D AbstractCocktailPanelView: setPanelVisible: CocktailPortraitRemotePanelViewfalse will be hiden: 3
12-20 11:53:53.471  6319  6319 D CocktailBarPanelVisibilityManager: updateActivePanelView:  vis=false screenOn=true onTransit=false -hide: 3 current Active: 3
,12-20 11:53:53.471  6319  6319 E AbstractCocktailPanelView: notifyPanelVisibilityChanged: visibility not changed 2 id: 3
12-20 11:53:53.471  6319  6319 I TrayVisibilityController: handleMessage : msg.what = 1
,12-20 11:53:53.471  6319  6319 I Utils   : isCurrentUser current = 0, ownerId = 0
12-20 11:53:53.471  6319  6319 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 2
12-20 11:53:53.471  6319  6319 I TrayVisibilityController: updateTrayVisible : State : 2 visible = 1 mCurrentVisible = 2
,12-20 11:53:53.471  6319  6319 D TrayStateController: putInputRect mDynamicInputRegion=188281550@LastEvent=t=1482231188813Rect(8, 0 - 64, 588),Rect=Rect(0, 0 - 0, 0)
12-20 11:53:53.471  6319  6319 D TrayStateController: putInputRect mDynamicInputRegion=188281550@LastEvent=t=1482231188813Rect(8, 0 - 64, 588),Rect=Rect(8, 0 - 64, 588)
12-20 11:53:53.471  6319  6319 D TrayStateTrigger: getTriggerMaginOnTop retY=550 h=2560 t=258 trigger=292 getTriggerPosition=1
12-20 11:53:53.471  4194  4194 D PeopleStripeService: ACTION_SCREEN_ON
12-20 11:53:53.471  3509  4342 D PowerManagerService: [api] setButtonBrightnessLimit: 255
,12-20 11:53:53.471  6319  6319 D TrayStateController: setUiState: 2 --> 0
12-20 11:53:53.471  3509  3905 I AbsCocktailBarStatePolicy: handleMessage: entry what = 1
12-20 11:53:53.471  4194  4194 D PeopleStripeManager: onVisibilityChanged : 1
12-20 11:53:53.471  4194  4194 D PeopleStripeVisibilityController: setHiddenEdgePanel enable=false
,12-20 11:53:53.481  4194  4194 I PeopleStripeVisibilityController: isAllowPrivateNotifications : allowPrivateNotifications = true
12-20 11:53:53.481  4194  4194 I PeopleStripeVisibilityController: isShowNotification : showNotification = true
12-20 11:53:53.481  4194  4194 I PeopleStripeVisibilityController: getComputedTrayVisible : keyguardState = 2
12-20 11:53:53.481  4194  4194 I PeopleStripeVisibilityController: updateStripeVisible : State 2 visible = 1
12-20 11:53:53.481  4194  4194 I PeopleStripeManager: isExistVisibleHandler false
12-20 11:53:53.481  4194  4194 I PeopleStripeManager: showStripe Not exist noti handler.
,12-20 11:53:53.481  3018  3018 I SurfaceFlinger: id=23 createSurf (64x588),1 flag=4, DocktailBar
,12-20 11:53:53.481  6319  6352 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [64x588]-format:1
,12-20 11:53:53.481  3509  6576 D SSRM:n  : SIOP:: AP = 310, PST = 312 (W:14), CP = 266, CUR = 165, LCD = 107
,12-20 11:53:53.481  6319  6319 D CocktailBarUiController: onCocktailBarStateChanged: flag=0x1 vis=1 bgType=0 showTimeout=-1 activate=true
,12-20 11:53:53.491  3509  3509 I SurveyLogManager: mDeviceInfo.mScreen = true
,12-20 11:53:53.501  3509  6576 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-20 11:53:53.501  3509  4002 V WindowStateAnimator: Finishing drawing window Window{ae806aa u0 d0 com.samsung.android.app.cocktailbarservice/com.samsung.android.app.cocktailbarservice.CocktailBarService}: mDrawState=DRAW_PENDING
,12-20 11:53:53.501  7178  7178 E SamsungIME: invoke(): method is null
,12-20 11:53:53.511  3509  3593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{90e216d u-1 com.samsung.ssrm.SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4887832 8428:com.sec.android.daemonapp/u0a166}
,12-20 11:53:53.511  8428  8428 D [WeatherWidget(1240)]  AutoRefreshReceiver: {[43EB1C024052B99D53E991930172379618B5A73E0169704C31B2E0FEC15ABF0DB061C2705E75ED5606D9FFD69F6B37E13822B2991EFA2872858E1E2BB615A6BC25C1BB37530DE4B9994E9888EE083816]}
12-20 11:53:53.511  8428  8428 D [WeatherWidget(1240)]  AutoRefresh: {[8FD2E506F874D7163C71C5FD167729A3F1524692913D8374891649955E8C59A90C19ED8315B58731AC2FE7582D4006FA]}
,12-20 11:53:53.511  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:53:53.521  8617  8655 I SystemBroadcastReceiver: [#CMH#] Received broadcast 
12-20 11:53:53.521  8617  8655 I PolicyManager: [#CMH#] onReceive action = EVENT_SCREEN_ON
12-20 11:53:53.521  8617  8655 I SystemBroadcastReceiver: [#CMH#] onReceive completed 
,12-20 11:53:53.521  3509  4007 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{90e216d u-1 com.samsung.ssrm.SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4887832 8428:com.sec.android.daemonapp/u0a166}
,12-20 11:53:53.521  8428  8428 D [WeatherWidget(1240)]  WeatherScreenReceiver: {[AE44B1CAE710C9799F38EE823B33FC6FDEAF5CF1F84C7C2D7C42190D3C2DE6A81416E92586372C9712C4D2BD025FBC09C229D81C93196B2AA28F22D563A30C15]}
,12-20 11:53:53.531  8428  8428 D [WeatherWidget(1240)]  WidgetCount: {[65C2FDBB08E09D2E8E78BEFE0D618279BC32024A311F60279E75A9FD2AD8BED1]}
,12-20 11:53:53.531  8428  8428 D [WeatherWidget(1240)]  WidgetCount: {[51D05FFECDA2C35BD99FAAEAA7B9A301F0BE9CFAFD994C3F7B3209384CC66988]}
12-20 11:53:53.531  8428  8428 D [WeatherWidget(1240)]  WidgetCount: {[6CEC719F0A07787F8C223B192FCD4687C55ED1AD256D01CA79B528F9A8936DA2AEE8FCF34DEAE62C4F0012DD0AEA3C4D450DA911871FFB9B1B25866B258CE216]}
,12-20 11:53:53.531  3509  3924 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,12-20 11:53:53.541  8428  8428 D [WeatherWidget(1240)]  WeatherService: {[F5837F4AEE74F4A0BE2DA219DB84933556419BA8B2FB7B09497D41D0C5E6D922]}
,12-20 11:53:53.541  8428  8428 D [WeatherWidget(1240)]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
12-20 11:53:53.541  8428  8428 D [WeatherWidget(1240)]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A000F9D574DD3C1B95D41EAB42ECFF02F3D72C391A0A68B1B0C567090769101B3139122E72F130C4410562206878681E44]}
,12-20 11:53:53.541  3509  4486 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bbd5e33 u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4887832 8428:com.sec.android.daemonapp/u0a166}
,12-20 11:53:53.541  8428  8428 D [WeatherWidget(1240)]  WeatherService: {[CC14338CDEB270B60D640F786827F117E88F4AEED272A832A59FE0C979EA04C9BE0E3A339EA914F65899C47723B17899]}
,12-20 11:53:53.541  8428  8428 D [WeatherWidget(1240)]  WeatherAppWidget: {[9C41A2EAFAAB2EF4F8363256C22FE8ADC05C1B1077ADBDFCD26E0DD65F89F33B4FE17DC1B474497D31FC899B742F59FC7E2530D44AA0E0C337CE79DB8742B2E258F6CB339704D31C42A8D7DC7C423413771689541177F15128C5082E60F137378548A4A3E3BC46E58400842019503B6A49C8E5B66CD635265353D3A3BD633961]}
12-20 11:53:53.541  8428  8428 D [WeatherWidget(1240)]  : {[AA0F1FFBE590A9EFC37054BD5EE30C3F13AAEFB0C1D46CFF1BAA5F3C6AC68B331A2EF1B485217118DBE54FFA6A88B711AC7C94EA741B05F20DACF9DE9722647F]}
,12-20 11:53:53.541  8428  8428 D [WeatherWidget(1240)]  WeatherAppWidget: {[9C41A2EAFAAB2EF4F8363256C22FE8ADC94DE00B25794211F94C1928DF937E6B475EC9A5D52E6E8AB8C5E9065071E1EA]}
,12-20 11:53:53.551  3509  4487 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bbd5e33 u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4887832 8428:com.sec.android.daemonapp/u0a166}
,12-20 11:53:53.551  8428  8428 D [WeatherWidget(1240)]  WeatherAppWidget2x1: {[9C41A2EAFAAB2EF4F8363256C22FE8AD1E8C40D052B00F217143F036334087D4E6A20622B7C5BAFDDAD05806F64279CFB58ACC644B946D1D44C1CB1343E9933E78640F20943B210E98A310C2B6492635456F7A98A5575530AC106B72D841268FE4ABD25C67426FA9138DA38B471E495644FE77123B7000FBE859923F0050324E]}
12-20 11:53:53.551  8428  8428 D [WeatherWidget(1240)]  : {[60E0DA3EB75B6AC8E852DC6D590E8782BC8A388398CF80A085FDDBC5F835D3B9]}
12-20 11:53:53.551  8428  8428 D [WeatherWidget(1240)]  : {[474171746BF601005A4D7D98B25C76B809703E254FE098232F11662B7CFA9306AAA83BB048A13628F045F41D951A5325AE3AF9B32C6D1DD1DC31B963A62AF276362FB0436AF461E46827C6999B8AF63FE3E53B8E7C650FB4537EBF1D6F8067C948D7C1C54AB097190AFAAEFD34E60697]}
,12-20 11:53:53.551  3509  4487 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bbd5e33 u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4887832 8428:com.sec.android.daemonapp/u0a166}
,12-20 11:53:53.551  8428  8428 D [WeatherWidget(1240)]  EasyWeatherAppWidget: {[48948B2BE5213A6D5B0C9B7747497512D204533BF333E4D2CEAD653C68E1B222E4748640A665E8FB625C2496224988A01822F94E1D5511EDA528C1BE4CAEABD1D9C6A4F90F6430CF4A4F5AB6F2AF9127520AD0A30D99495D03E7BBCB8D48F747F2FF12B441DB9FDD66804D1185ECF265D727A94D84DA9FC743DD76C54F03F188]}
12-20 11:53:53.551  8428  8428 D [WeatherWidget(1240)]  : {[AA0F1FFBE590A9EFC37054BD5EE30C3F13AAEFB0C1D46CFF1BAA5F3C6AC68B331A2EF1B485217118DBE54FFA6A88B711AC7C94EA741B05F20DACF9DE9722647F]}
,12-20 11:53:53.551  8428  8428 D [WeatherWidget(1240)]  EasyWeatherAppWidget: {[48948B2BE5213A6D5B0C9B774749751274237807901AA8393F0A8526192EEF19F2D7E71ABBE368E57B1937778E7A2758BD22312FFA1C721753FCFDC0AD054D98]}
,12-20 11:53:53.571  6319  6319 D TrayStateTrigger: showTriggerView
,12-20 11:53:53.591  3509  9586 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,12-20 11:53:53.591  3509  9586 D BluetoothAdapter: STATE_ON
,12-20 11:53:53.591  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:53:53.601  3509  3531 V AlarmManager:  remove PendingIntent] PendingIntent{ee5aa8f: PendingIntentRecord{69adb7d com.android.bluetooth broadcastIntent}}
,12-20 11:53:53.601  3509  3530 V AlarmManager:  remove PendingIntent] PendingIntent{b5b611c: PendingIntentRecord{69adb7d com.android.bluetooth broadcastIntent}}
,12-20 11:53:53.611  3509  4486 V AlarmManager:  remove PendingIntent] PendingIntent{5271125: PendingIntentRecord{69adb7d com.android.bluetooth broadcastIntent}}
,12-20 11:53:53.641  3509  9586 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,12-20 11:53:53.661  3509  9586 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,12-20 11:53:53.671  3509  9586 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,12-20 11:53:53.751  3509  9586 I BatteryStatsDumper: Writing to database completed
,12-20 11:53:53.791  3182  3221 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, 86, -90, 106, 0, 1
,12-20 11:53:53.791  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, 86, -90, 106, 0, 1
12-20 11:53:53.791  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
12-20 11:53:53.791  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
12-20 11:53:53.791  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, 86, -90, 106, 0, 1,
,12-20 11:53:53.791  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
12-20 11:53:53.791  3509  3838 I CAE     : display(ContextProvider.java:391) - Accuracy=[1], OperationMode=[0], ActivityType=[0], TimeStamp=[1482231233130]
,12-20 11:53:53.791  3509  3841 D SContextService: updateSContext() : event = Activity Tracker
12-20 11:53:53.791  3509  3509 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
12-20 11:53:53.791  3509  3509 D WifiService: ACTIVITY_STATUS_UNKNOWN 
,12-20 11:53:53.891  3509  3850 D InputReader: Input event(4): value=1 when=142330190000
12-20 11:53:53.891  3509  3850 D InputReader: Input event(4): value=1 when=142330190000
12-20 11:53:53.891  3509  3850 I InputReader: Touch event's action is 0x0 (deviceType=0) [pCnt=1, s=0.3 ] when=142330190000
,12-20 11:53:53.891  3509  3850 D InputReader: lastThreadEndTime = 141705091859, currentThreadStartTime = 141705094936, diff = 0
12-20 11:53:53.891  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x0, toolType: 1
12-20 11:53:53.891  3960  3960 D ViewRootImpl: ViewPostImeInputStage processPointer 0
,12-20 11:53:53.891  3509  4002 D SecContentProvider: query(), uri = 17 selection = isStatusBarExpansionallowedAsUser
,12-20 11:53:53.891  3960  3960 D KeyguardSwipeHelper: event=MotionEvent { action=ACTION_DOWN, actionButton=0, id[0]=0, x[0]=689.7656, y[0]=2147.5, toolType[0]=TOOL_TYPE_FINGER, buttonState=0, metaState=0, flags=0x0, edgeFlags=0x0, pointerCount=1, historySize=0, eventTime=142330, downTime=142330, deviceId=4, source=0x1002 }
12-20 11:53:53.891  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
12-20 11:53:53.891  3960  3960 D KeyguardSwipeHelper: onUnlockViewPressed()
,12-20 11:53:53.911  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:53:53.911  3509  4434 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 142353
,12-20 11:53:53.921  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:53:53.931  3509  4441 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 142369
,12-20 11:53:53.941  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:53:53.941  3509  3791 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 142386
,12-20 11:53:53.961  3509  3836 V AlarmManager: Expired Alarm result :8
,12-20 11:53:53.961  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:53:53.961  3509  4486 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 142404
,12-20 11:53:53.971  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:53:53.981  3509  4436 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 142419
,12-20 11:53:53.981  3509  3509 I BackgroundCompactionService: onStart. jobID=801
12-20 11:53:53.981  3509  3509 I BackgroundCompactionService: compact_exception
12-20 11:53:53.981  3509  3509 I BackgroundCompactionService: onStart done. jobID=801
,12-20 11:53:53.991  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:53:53.991  3509  4333 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 142436
,12-20 11:53:54.001  3509  3850 D InputReader: Input event(4): value=0 when=142447067000
,12-20 11:53:54.001  3509  3850 D InputReader: Input event(4): value=0 when=142447067000
12-20 11:53:54.001  3509  3850 I InputReader: Touch event's action is 0x1 (deviceType=0) [pCnt=1, s=] when=142447067000
12-20 11:53:54.001  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x1, toolType: 1
12-20 11:53:54.001  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
12-20 11:53:54.001  3509  6576 D GameManagerService: identifyGamePackage. com.sec.android.app.launcher
,12-20 11:53:54.001  3509  6576 D GameManagerService: identifyForegroundApp. com.sec.android.app.launcher
12-20 11:53:54.001  3509  4485 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 142448
12-20 11:53:54.001  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
12-20 11:53:54.001  3509  6576 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
12-20 11:53:54.001  3960  3960 D ViewRootImpl: ViewPostImeInputStage processPointer 1
12-20 11:53:54.001  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:53:54.001  3960  3960 D KeyguardSwipeHelper: event=MotionEvent { action=ACTION_UP, actionButton=0, id[0]=0, x[0]=759.375, y[0]=1233.125, toolType[0]=TOOL_TYPE_FINGER, buttonState=0, metaState=0, flags=0x0, edgeFlags=0x0, pointerCount=1, historySize=0, eventTime=142447, downTime=142330, deviceId=4, source=0x1002 }
12-20 11:53:54.001  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
12-20 11:53:54.001  3960  3960 D KeyguardSwipeHelper: onUnlockViewReleased()
12-20 11:53:54.001  3960  3960 D KeyguardUnlockEventHandler: ACTION_UP mDistance: 916.600785511337
12-20 11:53:54.001  3509  4977 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 142449
12-20 11:53:54.001  3960  3960 D KeyguardEffectViewLayered: handleUnlock()
12-20 11:53:54.011  3960  3960 D KeyguardUnlockEventHandler: launch() - mIsKeyguardDismissing=false, isDeviceInteractive=true
12-20 11:53:54.011  3960  3960 D KeyguardSwipeHelper: onUnlockExecuted() mUnlockExecuted=false, mUnlockViewPressed=false
12-20 11:53:54.011  3960  3960 D KeyguardSwipeHelper: startAnimationAndUnlock() alpha=0.0, wallpaperType=1
,12-20 11:53:54.011  3960  3960 D PanelView: callback makeExpandedInvisible executed
12-20 11:53:54.011  3960  3960 D PhoneStatusBar: makeExpandedInvisible: mExpandedVisible=true, state = 1
,12-20 11:53:54.011  3960  3960 D PanelView: updateQsState
12-20 11:53:54.011  3960  3960 D KeyguardSwipeHelper: reset()
12-20 11:53:54.011  3960  3960 D KeyguardUnlockEventHandler: reset()
12-20 11:53:54.011  3960  3960 D KeyguardSwipeHelper: resetChildViewVI()
12-20 11:53:54.011  3960  3960 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
12-20 11:53:54.011  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,12-20 11:53:54.011  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : true keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
12-20 11:53:54.011  3960  3960 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
,12-20 11:53:54.011  6319  6319 I TrayVisibilityController: TrayStateVisibilityReceiver action :com.samsung.systemui.statusbar.COLLAPSED
,12-20 11:53:54.011  3960  3960 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
12-20 11:53:54.011  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:53:54.011  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
12-20 11:53:54.011  3960  3960 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
,12-20 11:53:54.011  3960  3960 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
12-20 11:53:54.011  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:53:54.011  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
12-20 11:53:54.011  3960  3960 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
12-20 11:53:54.011  3960  3960 D StatusBarKeyguardViewManager: showBouncer
12-20 11:53:54.011  3960  3960 D KeyguardSecurityView: showNextSecurityScreenOrFinish(false)
,12-20 11:53:54.021  3960  3960 D KeyguardSecurityModel: getSecurityMode( getActivePasswordQuality = 0 , currentuser = 0
12-20 11:53:54.021  3960  3960 D KeyguardViewBase: finish mViewMediatorCallback.keyguardDone
,12-20 11:53:54.021  3960  3960 D KeyguardViewMediator: keyguardDone(true)
12-20 11:53:54.021  3960  3960 D KeyguardFingerPrint: reportSuccessfulStrongAuthUnlockAttempt()
,12-20 11:53:54.021  3960  3960 D PhoneStatusBar: adjustDisableFlags:false, false, false, false, true, 1
,12-20 11:53:54.021  3960  3960 D KeyguardUnlockEventHandler: mIsMultiTouch false
12-20 11:53:54.021  3960  3960 D KeyguardViewMediator: handleKeyguardDone
,12-20 11:53:54.021  3960  3960 D KeyguardViewMediator: onSdpUnlocked :: Inside...
12-20 11:53:54.021  3960  3960 D KeyguardViewMediator: isPwdChangeRequested :: false
,12-20 11:53:54.021  3960  3960 D KeyguardViewMediator: onSdpUnlocked :: Active quality = 0
,12-20 11:53:54.021  3960  3960 D KeyguardViewMediator: onSdpUnlocked :: Unlock SDP for User 0
12-20 11:53:54.021  3960  3960 D KeyguardViewMediator: handleHide
,12-20 11:53:54.031  4328  4328 D Launcher: onRestart, Launcher: 188281550
,12-20 11:53:54.031  3509  4436 E SdpServiceKeeper: isLicensed {pid:3960 uid:10065 userid:0 doPkg:null}
12-20 11:53:54.031  3509  4436 E SdpServiceKeeper: System app. Skip license activation
,12-20 11:53:54.031  3509  4487 E SdpServiceKeeper: isLicensed {pid:3960 uid:10065 userid:0 doPkg:null}
12-20 11:53:54.031  3509  4487 E SdpServiceKeeper: System app. Skip license activation
12-20 11:53:54.031  4328  4328 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.sec.android.app.clockpackage
,12-20 11:53:54.041  4328  4328 D ResourcesManager: For user 0 new overlays fetched Null
,12-20 11:53:54.041  3509  3509 D GameManagerService: NotifyRunnable. pkg: com.sec.android.app.launcher, type: 4, isMinimized: false, isTunableApp: false
,12-20 11:53:54.041  6319  6329 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.sec.android.app.launcher/com.android.launcher2.Launcher} Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10800000 cmp=com.sec.android.app.launcher/.activities.LauncherActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,12-20 11:53:54.051  4328  4328 D ApplicationPackageManager: we has com.sec.android.app.clockpackage class. reuse it 
,12-20 11:53:54.051  3509  3593 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.sec.android.app.launcher
12-20 11:53:54.051  4328  4328 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.sec.android.app.clockpackage
,12-20 11:53:54.061  3960  3960 D KeyguardViewMediator: Calling keyguardGoingAway of WindowManager
12-20 11:53:54.061  3509  4007 D SdpManagerService: unlock :: Internal... 0
12-20 11:53:54.061  3509  4007 D SdpManagerService: SecureUnlock :: User : 0, Type : 1
,12-20 11:53:54.071  3509  4007 D SdpManagerService: SecureUnlock :: Quality for user 0 = 0
,12-20 11:53:54.071  3509  4007 D SdpManagerService: SecureUnlock :: Very low security level found...!!! 0
12-20 11:53:54.071  3509  4007 D SdpManagerService: unlock :: onDeviceUnLocked from TIMA 0
12-20 11:53:54.071  3509  4007 I TLC_TZ_KEYSTORE: : TZ_KEYSTORE_fips_initialize
12-20 11:53:54.071  3509  4007 D TimaService: TIMA3: FipsKeyStore3_init
12-20 11:53:54.071  3509  4007 I TLC_TZ_KEYSTORE: : creating new keystore context...
12-20 11:53:54.071  3509  4007 D TimaService: TIMA: in getTimaVersion
12-20 11:53:54.071  3509  4007 I TLC_TZ_KEYSTORE: : initializing ccm context...
12-20 11:53:54.071  3509  4007 I TLC_TZ_KEYSTORE: : root = 0, root_strlen = 1
12-20 11:53:54.071  3509  4007 I TLC_TZ_KEYSTORE: : process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:53:54.071  3509  4007 I TZ: mc_tlc_communication: input max_sendmsg_size = 1080
12-20 11:53:54.071  3509  4007 I TZ: mc_tlc_communication: input max_recvmsg_size = 1080
12-20 11:53:54.071  3509  4007 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-20 11:53:54.071  3509  4007 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:53:54.071  3509  4007 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 1088
12-20 11:53:54.071  3509  4007 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 1088
12-20 11:53:54.071  3509  4007 I TZ: mc_tlc_communication: device_id = 0x0
12-20 11:53:54.071  3509  4007 I TZ: mc_tlc_communication: tlc_open() was called
12-20 11:53:54.071  3509  4007 I TZ: mc_tlc_communication: Opening MobiCore device
,12-20 11:53:54.071  3509  4007 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
12-20 11:53:54.071  3509  4007 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-20 11:53:54.071  3509  4007 I TZ: mc_tlc_communication: Opening the session
12-20 11:53:54.071  3960  3960 D KeyguardViewMediator: handleStartKeyguardExitAnimation
,12-20 11:53:54.081  3960  3960 W AudioTrack: AUDIO_OUTPUT_FLAG_FAST denied by client; transfer 4, track 44100 Hz, output 48000 Hz
,12-20 11:53:54.081  3175  3660 W AudioPolicyIntefaceImpl: Skipped to add effects on session 26
12-20 11:53:54.081  3175  3660 I APM::AudioPolicyManager: startOutput() output 4, stream 1, session 26
,12-20 11:53:54.081  3175  3651 D audio_hw_primary: out_set_parameters: enter: kvpairs: routing=2
,12-20 11:53:54.081  3175  3651 D AudioFlinger: setCurDevice() 0x2
,12-20 11:53:54.081  3960  3960 E KeyguardViewMediator: setShowingLocked mShowing = false
,12-20 11:53:54.081  3960  3960 D StatusBar-Window: fnf=true sanc=false, kni=false, sbf=false
,12-20 11:53:54.081  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,12-20 11:53:54.081  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : false panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
12-20 11:53:54.081  3960  3960 D CoverUI : applyHeight h = 96, oc = false, fa = false, ac = false, sc = false
,12-20 11:53:54.081  3960  3960 D StatusBar-Window: fnf=true sanc=false, kni=false, sbf=false
12-20 11:53:54.081  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:53:54.081  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : false panelVisible : false keyguardFadingAway : true bouncerShowing : false headsUpShowing : false
12-20 11:53:54.081  3960  3960 D CoverUI : applyHeight h = -1, oc = false, fa = true, ac = false, sc = false
12-20 11:53:54.081  3960  3960 D KeyguardEffectViewController: setKeyguardFadingAway = true
12-20 11:53:54.081  3960  3960 D KeyguardEffectViewController: mShowing=true, mOccluded=false, mKeyguardFadingAway=true, match_parent=true
12-20 11:53:54.081  3960  3960 D KeyguardEffectViewController: setKeyguardShowing = false
,12-20 11:53:54.081  3960  3960 D KeyguardEffectViewController: mShowing=false, mOccluded=false, mKeyguardFadingAway=true, match_parent=true
12-20 11:53:54.081  3960  3960 V KeyguardUpdateMonitor: *** unregister callback for com.android.keyguard.KeyguardSecurityContainer$1@66b8589
12-20 11:53:54.091  3960  3960 D KeyguardUpdateMonitor: onKeyguardVisibilityChanged(false)
12-20 11:53:54.091  3509  4007 I TZ: mc_tlc_communication: tlc_open() succeeded
12-20 11:53:54.091  3509  4007 I TLC_TZ_KEYSTORE: : ctx = 0x7f8204fca0, comm = 0x7f7e72a340, sendmsg = 0x7f958fa000, recvmsg = 0x7f958fa440
12-20 11:53:54.091  3509  4007 I TZ_init: : TZ_init: fips_init_TLC sending initialization request...
12-20 11:53:54.091  3509  4007 I TZ_init: : TZ_init: sending initialization request...
,12-20 11:53:54.091  4328  4328 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.android.calendar
,12-20 11:53:54.091  3175  3651 I AudioMixer: create resampler src 44100, 2, dst 48000, 2
12-20 11:53:54.091  3175  3651 D SoundAliveResampler: [SoundAliveResampler] Init+++
,12-20 11:53:54.091  3175  3651 V audio_hw_primary: start_output_stream+, out->device : 00000002 , out->type = 1
12-20 11:53:54.091  4328  4328 D ResourcesManager: For user 0 new overlays fetched Null
,12-20 11:53:54.091  3960  3960 V KeyguardFingerPrint: updateFingerprintListeningState(false)
,12-20 11:53:54.091  3960  3960 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
12-20 11:53:54.091  3960  3960 V KeyguardUpdateMonitor: stopListeningForFingerprint()
,12-20 11:53:54.101  4328  4328 D ApplicationPackageManager: we has com.android.calendar class. reuse it 
,12-20 11:53:54.101  3960  3960 D KeyguardViewMediator: adjustStatusBarLocked: mShowing=false mOccluded=false isSecure=false --> flags=0x0
12-20 11:53:54.101  4328  4328 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.android.calendar
12-20 11:53:54.101  3509  3791 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=com.android.systemui
,12-20 11:53:54.101  3509  4007 I TZ_init: : TZ_init: successful initialization
,12-20 11:53:54.101  3509  4007 I TLC_TZ_KEYSTORE: fips_self_test: : TZ_KEYSTORE_fips_self_test_START...
,12-20 11:53:54.101  3960  3960 D KeyguardFingerPrint: setDisableFingerPrintBySecurityDialog( false )
,12-20 11:53:54.101  3960  3960 D WallpaperService: updateSurface:[forceRelayout]false[redrawNeeded]false
,12-20 11:53:54.101  3509  3509 E MotionRecognitionService:   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
12-20 11:53:54.101  3960  3960 D ImageWallpaper: onVisibilityChanged:true
12-20 11:53:54.101  4328  4328 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:53:54.101  4328  4328 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:53:54.101  3509  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
12-20 11:53:54.101  4328  4328 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:53:54.101  3509  4007 I TLC_TZ_KEYSTORE: fips_self_test: : TZ_KEYSTORE_fips_self_test_END...
12-20 11:53:54.101  3509  4007 E TLC_TZ_KEYSTORE: : Self Test Succeded
12-20 11:53:54.101  3509  4007 I TZ: mc_tlc_communication: tlc_close() was called
12-20 11:53:54.101  3509  4007 I TZ: mc_tlc_communication: Closing the session
12-20 11:53:54.101  3960  3960 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
12-20 11:53:54.101  3960  3960 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
12-20 11:53:54.101  3960  3960 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,12-20 11:53:54.101  3960  3960 D PhoneStatusBar: makeExpandedInvisible: mExpandedVisible=false, state = 1
12-20 11:53:54.101  3509  3509 D ResourcesManager: For user 0 new overlays fetched Null
,12-20 11:53:54.101  3509  4007 I TZ: mc_tlc_communication: Freeing message buffer
12-20 11:53:54.111  3509  4007 I TZ: mc_tlc_communication: Closing MobiCore device
12-20 11:53:54.111  3509  4007 I TeeDriverClient: driver client closed [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:113]
12-20 11:53:54.111  3509  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
12-20 11:53:54.111  3509  4007 I TZ: mc_tlc_communication: tlc_close() succeeded
12-20 11:53:54.111  3509  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
12-20 11:53:54.111  3509  4007 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
,12-20 11:53:54.111  3509  4007 D TimaHelper: getTimaStatus() - Tima Status : 0
12-20 11:53:54.111  3509  4007 D TimaHelper: checkTimaStatus() - Version FIPS3.0, Status0, Validation : true
,12-20 11:53:54.111  3509  4007 I TLC_TZ_KEYSTORE: : TZ_KEYSTORE_fips_initialize
,12-20 11:53:54.111  3509  4007 D TimaService: TIMA3: FipsKeyStore3_init
12-20 11:53:54.111  3509  4007 I TLC_TZ_KEYSTORE: : creating new keystore context...
12-20 11:53:54.111  3509  4007 D TimaService: TIMA: in getTimaVersion
12-20 11:53:54.111  3509  4007 I TLC_TZ_KEYSTORE: : initializing ccm context...
12-20 11:53:54.111  3509  3595 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{9ce7bae u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
12-20 11:53:54.111  3509  4007 I TLC_TZ_KEYSTORE: : root = 0, root_strlen = 1
12-20 11:53:54.111  3509  3509 D ResourcesManager: For user 0 new overlays fetched Null
,12-20 11:53:54.111  3509  4007 I TLC_TZ_KEYSTORE: : process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:53:54.111  3509  4007 I TZ: mc_tlc_communication: input max_sendmsg_size = 1080
12-20 11:53:54.111  3509  4007 I TZ: mc_tlc_communication: input max_recvmsg_size = 1080
12-20 11:53:54.111  3509  4007 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-20 11:53:54.111  3509  4007 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:53:54.111  3509  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
12-20 11:53:54.111  3509  4007 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 1088
12-20 11:53:54.111  3509  3509 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
12-20 11:53:54.111  3509  4007 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 1088
12-20 11:53:54.111  3509  4007 I TZ: mc_tlc_communication: device_id = 0x0
12-20 11:53:54.111  3509  4007 I TZ: mc_tlc_communication: tlc_open() was called
12-20 11:53:54.111  3509  4007 I TZ: mc_tlc_communication: Opening MobiCore device
,12-20 11:53:54.111  3509  4007 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
12-20 11:53:54.111  3509  4007 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-20 11:53:54.111  3509  4007 I TZ: mc_tlc_communication: Opening the session
,12-20 11:53:54.111  3509  3509 D ResourcesManager: For user 0 new overlays fetched Null
12-20 11:53:54.111  3509  3509 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
12-20 11:53:54.111  3509  4441 D InputDispatcher: Focus left window: 3960
,12-20 11:53:54.111  3509  3509 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
12-20 11:53:54.111  3509  4441 D InputDispatcher: Focus entered window: 4328
12-20 11:53:54.111  3509  4441 D PowerManagerService: [api] setUserActivityTimeoutOverrideFromWindowManagerInternal: timeoutMillis: -1
12-20 11:53:54.111  3509  4441 D PowerManagerService: [s] getScreenOffTimeoutLocked: 10000 -> 30000
12-20 11:53:54.111  3509  4441 D PowerManagerService: [api] setScreenDimDurationOverrideFromWindowManagerInternal: timeoutMillis: -1
,12-20 11:53:54.111  3509  3509 D ResourcesManager: For user 0 new overlays fetched Null
,12-20 11:53:54.111  3509  3509 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
12-20 11:53:54.111  3509  3509 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.USER_PRESENT
12-20 11:53:54.111  3509  3509 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3509) 
12-20 11:53:54.111  3509  3615 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3509 uid:1000
12-20 11:53:54.111  3509  3509 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=6) set Off
,12-20 11:53:54.111  3509  3615 D PointerIcon: setMouseCustomIcon IconType is same.101
12-20 11:53:54.111  3509  3625 D LightsService: [SvcLED] handleForcedSvcLEDTask()
12-20 11:53:54.111  3509  3509 D UsbDeviceManager: Keyguard Lock/Unlock
12-20 11:53:54.121  3509  3509 D SecContentProvider: query(), uri = 18 selection = isUsbMediaPlayerAvailable
12-20 11:53:54.111  3509  3509 D UsbDeviceManager: updateUsbNotification : mConnected = true, mConfigured = true, mCurrentFunctions = mtp,adb
,12-20 11:53:54.111  3509  3625 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
12-20 11:53:54.121  3509  3509 D UsbDeviceManager: mps exists
,12-20 11:53:54.121  3509  4002 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,12-20 11:53:54.121  3509  3509 D UsbDeviceManager: isUsb30Enabled: read '/sys/class/android_usb/android0/bcdUSB', state = 0200
,12-20 11:53:54.121  3182  3221 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, 86, -89, -65, 0, 0
,12-20 11:53:54.131  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, 86, -89, -65, 0, 0
12-20 11:53:54.131  3509  3509 D UsbDeviceManager: updateUsbNotification : cancel id = 17040367, title = Przesył. plików multimed. przez USB
12-20 11:53:54.131  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
12-20 11:53:54.131  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
12-20 11:53:54.131  3509  4007 I TZ: mc_tlc_communication: tlc_open() succeeded
12-20 11:53:54.131  3509  4007 I TLC_TZ_KEYSTORE: : ctx = 0x7f8204fca0, comm = 0x7f7e72a340, sendmsg = 0x7f958fa000, recvmsg = 0x7f958fa440
12-20 11:53:54.131  3509  4007 I TZ_init: : TZ_init: fips_init_TLC sending initialization request...
12-20 11:53:54.131  3509  4007 I TZ_init: : TZ_init: sending initialization request...
12-20 11:53:54.131  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, 86, -89, -65, 0, 0,
,12-20 11:53:54.131  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
,12-20 11:53:54.131  3509  3838 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[0], TimeStamp=[1482231233471]
12-20 11:53:54.131  3509  4334 V AlarmManager:  remove PendingIntent] PendingIntent{bbcfcd9: PendingIntentRecord{3680e5b com.google.android.gms broadcastIntent}}
12-20 11:53:54.131  3509  3509 D UsbDeviceManager: updateUsbNotification : isKeyguardShowingAndNotOccluded = false, isKeyguardSecure = false, mBootCompleted = true
12-20 11:53:54.131  3509  3841 D SContextService: updateSContext() : event = Activity Tracker
,12-20 11:53:54.131  4304  9590 D NfcService: call the applyRouting
12-20 11:53:54.131  3960  3960 D PhoneStatusBar: disable: < expand icons* alerts system_info* back home* recent* clock search* quick_settings >
,12-20 11:53:54.131  6319  6319 I TrayVisibilityController: UserPresentBroadcastReceiver : action = android.intent.action.USER_PRESENT
,12-20 11:53:54.131  4194  4194 I PeopleStripeVisibilityController: UserPresentBroadcastReceiver : action = android.intent.action.USER_PRESENT
,12-20 11:53:54.131  7178  7178 E SamsungIME: invoke(): method is null
12-20 11:53:54.131  7178  7178 D SamsungIME: showDlgMsgBox : false true true
,12-20 11:53:54.131  6673  6673 E MtpService: In MTPAPP onReceive:android.intent.action.USER_PRESENT
12-20 11:53:54.131  6673  6673 E MtpService: Inside ACTION_USER_PRESENT:android.intent.action.USER_PRESENT
,12-20 11:53:54.141  3509  3593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d57f69e u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6fe7727 4355:com.google.android.gms.persistent/u0a21}
,12-20 11:53:54.141  3509  4007 I TZ_init: : TZ_init: successful initialization
12-20 11:53:54.141  3509  4007 I TLC_TZ_KEYSTORE: fips_self_test: : TZ_KEYSTORE_fips_self_test_START...
,12-20 11:53:54.141  4328  4328 D Launcher: onStart, Launcher: 188281550
12-20 11:53:54.141  4328  4328 D Launcher.HomeView: onStart
,12-20 11:53:54.141  3509  4007 I TLC_TZ_KEYSTORE: fips_self_test: : TZ_KEYSTORE_fips_self_test_END...
12-20 11:53:54.141  3509  4007 E TLC_TZ_KEYSTORE: : Self Test Succeded
12-20 11:53:54.141  3509  4007 I TZ: mc_tlc_communication: tlc_close() was called
12-20 11:53:54.141  3509  4007 I TZ: mc_tlc_communication: Closing the session
12-20 11:53:54.141  3509  3509 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = android,userId = -1
12-20 11:53:54.151  3509  3509 D UsbDeviceManager: updateUsbNotification : notify id = 17040367, title = Przesył. plików multimed. przez USB
12-20 11:53:54.151  3509  3509 I MdnieScenarioControlService: action  :  android.intent.action.USER_PRESENT
12-20 11:53:54.151  3509  4007 I TZ: mc_tlc_communication: Freeing message buffer
12-20 11:53:54.151  3509  4007 I TZ: mc_tlc_communication: Closing MobiCore device
12-20 11:53:54.151  3509  4007 I TeeDriverClient: driver client closed [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:113]
12-20 11:53:54.151  3509  4007 I TZ: mc_tlc_communication: tlc_close() succeeded
12-20 11:53:54.151  3509  4007 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
12-20 11:53:54.151  3509  4007 I         : CCM JNI: In get_ccm_version
12-20 11:53:54.151  3509  4007 I TZ_CCM_C_Initialize: : DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
12-20 11:53:54.151  3509  4007 I TZ_CCM_C_Initialize: : pInitArgs 0x7f902e0508 has not called C_Init before.
12-20 11:53:54.151  3509  4007 I TZ_CCM_C_Initialize: : &ctx = 0x7faae772a0
12-20 11:53:54.151  3509  4007 I TLC_TZ_CCM: : creating new ccm context...
12-20 11:53:54.151  3509  4007 I TLC_TZ_CCM: : initializing ccm context...
12-20 11:53:54.151  3509  4007 I TLC_TZ_CCM: : root = 0, root_strlen = 1
12-20 11:53:54.151  3509  4007 I TLC_TZ_CCM: : process = ffffffff000000000000000000000012, process_strlen = 32
12-20 11:53:54.151  3509  4007 I TZ: client_server_communication: input max_sendmsg_size = 19420
12-20 11:53:54.151  3509  4007 I TZ: client_server_communication: input max_recvmsg_size = 19420
12-20 11:53:54.151  3509  4007 I TZ: client_server_communication: root = 0, root_len = 1
12-20 11:53:54.151  3509  4007 I TZ: client_server_communication: process = ffffffff000000000000000000000012, process_strlen = 32
12-20 11:53:54.151  3509  4007 I TZ: client_server_communication: aligned max_sendmsg_size = 19456
12-20 11:53:54.151  3509  4007 I TZ: client_server_communication: aligned max_recvmsg_size = 19456
12-20 11:53:54.151  3509  4007 I TZ: client_server_communication: Client_Server_Open was called
12-20 11:53:54.151  4328  4328 D Launcher: onResume, Launcher: 188281550
12-20 11:53:54.151  3829  3829 I TLC_SERVER: BnTLCServer::onTransact(1598968902) 16
12-20 11:53:54.151  3829  3829 I TLC_SERVER: Unknown
12-20 11:53:54.151  3509  4007 I TZ: client_server_communication: IClientServer::IClientServer()
12-20 11:53:54.151  3509  4434 D SettingsProvider: isChangeAllowed() : name = kids_home_mode
12-20 11:53:54.151  3509  4007 I TZ: client_server_communication: BpClientServer::BpClientServer()
12-20 11:53:54.151  3509  4434 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
12-20 11:53:54.151  3829  3848 I TLC_SERVER: BnTLCServer::onTransact(0) 16
,12-20 11:53:54.151  3509  4434 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
12-20 11:53:54.151  3829  3848 I TLC_SERVER: OPENSWCONN
12-20 11:53:54.151  3509  4434 D SettingsProvider: selectionArgs: false
12-20 11:53:54.151  3829  3848 I TZ: mc_tlc_communication: input max_sendmsg_size = 19420
12-20 11:53:54.151  3509  4434 D SettingsProvider: selectionArgs: 10069
12-20 11:53:54.151  3829  3848 I TZ: mc_tlc_communication: input max_recvmsg_size = 19420
12-20 11:53:54.151  3509  4434 D SettingsProvider: ret = -1
12-20 11:53:54.151  3829  3848 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-20 11:53:54.151  3509  4441 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d57f69e u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6fe7727 4355:com.google.android.gms.persistent/u0a21}
12-20 11:53:54.151  3829  3848 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000012, process_strlen = 32
12-20 11:53:54.151  3509  4434 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
12-20 11:53:54.151  3829  3848 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 19456
12-20 11:53:54.151  3829  3848 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 19456
12-20 11:53:54.151  3829  3848 I TZ: mc_tlc_communication: device_id = 0x0
12-20 11:53:54.151  3829  3848 I TZ: mc_tlc_communication: tlc_open() was called
12-20 11:53:54.151  3829  3848 I TZ: mc_tlc_communication: Opening MobiCore device
12-20 11:53:54.151  3829  3848 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
12-20 11:53:54.151  3829  3848 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-20 11:53:54.151  3829  3848 I TZ: mc_tlc_communication: Opening the session
12-20 11:53:54.151  4328  4328 D Launcher.HomeView: onResume
12-20 11:53:54.151  4328  4328 D capture : ---------checkFileExist land
12-20 11:53:54.151  4328  4328 D capture : currentOrientation: 1 mMainHomeScreenshot: true mMainHomeScreenshotLand: true
12-20 11:53:54.161  4355  4355 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }.
12-20 11:53:54.161  3509  3509 D MdnieScenarioControlService:  packageName : com.sec.android.app.launcher    className : com.sec.android.app.launcher.activities.LauncherActivity
12-20 11:53:54.161  3509  3509 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
12-20 11:53:54.161  3509  3904 I MdnieScenarioControlService: mGameModeLauncher : false
12-20 11:53:54.161  3509  3509 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
12-20 11:53:54.161  3509  3509 D UcmService: notifyChangeToPlugin event 16
12-20 11:53:54.161  3509  3509 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
12-20 11:53:54.161  3509  3509 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
12-20 11:53:54.161  3509  3509 D UcmService: notifying to unmanaged plugin
12-20 11:53:54.161  4378  4411 E ucsBai_agentService: notifyChange NOT SUPPORTED
12-20 11:53:54.161  3509  3509 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
12-20 11:53:54.161  3509  3509 D UcmService: agentService status-0
12-20 11:53:54.161  3509  3509 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.ese:eSE Credential Storage Package name = com.samsung.ucs.agent.ese
12-20 11:53:54.161  3509  3509 D UcmService: notifying to managed plugin
12-20 11:53:54.161  3509  3509 D UcmService: checkIfNotify: Valid userid - 0
12-20 11:53:54.161  3509  3509 D PolicyManager: PolicyManager.isStorageEnabled() for userId = 0
12-20 11:53:54.161  3509  3509 D UniversalCredentialManagerService: checkCallerPermissionFor is called for method-isCredentialStorageManagedAsUser
12-20 11:53:54.161  3509  3509 D UniversalCredentialManagerService: isCredentialStorageManagedAsUser is called....
12-20 11:53:54.161  4328  4328 D MenuAppsGridFragment: onResume
12-20 11:53:54.161  4328  4328 D MenuAppsGridFragment: changeState: (new)NORMAL(old)NORMAL(force)false
12-20 11:53:54.161  3509  3509 D PolicyManager: PolicyManager.isStorageEnabled() result = false
12-20 11:53:54.161  3509  3509 D UcmService: agentService com.samsung.ucs.agent.ese:eSE Credential Storage not notified
12-20 11:53:54.161  3509  3509 D UcmService: agentService status-0
12-20 11:53:54.161  3509  3509 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
12-20 11:53:54.161  3509  3509 D UcmService: notifying to unmanaged plugin
12-20 11:53:54.161  3509  3904 I MdnieScenarioControlService: setUIMode
12-20 11:53:54.171  4396  4419 D BootAgentService: notifyChange eventId-16
12-20 11:53:54.171  3175  3651 D audio_hw_primary: start_output_stream (0xf112d6c0) out->pcm_device:6 out->config.rate:48000 out->config.format:0 out->period_size:240
12-20 11:53:54.171  3175  3651 D audio_hw_primary: start_output_stream (0xf112d6c0) out->config.rate:48000 out->config.format:0 out->period_size:240
12-20 11:53:54.171  3175  3651 V audio_hw_primary: select_devices output_scenario:0 input_scenario:-1 out_snd_device 0x2 in_snd_device:0x0
12-20 11:53:54.171  3175  3651 I audio_route: 
12-20 11:53:54.171  3175  3651 I audio_route: > audio_route_reset :
12-20 11:53:54.171  3509  3509 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
12-20 11:53:54.171  3509  3509 D UcmService: agentService status--1
12-20 11:53:54.171  3509  3509 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3509) 
12-20 11:53:54.171  3509  3509 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
12-20 11:53:54.171  3175  3651 I audio_route: 
12-20 11:53:54.171  3175  3651 I audio_route: > audio_route_apply_path : "media-speaker"
12-20 11:53:54.171  3509  3509 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=6) set Off
12-20 11:53:54.171  3509  3509 D EdgeLight: Turning off
12-20 11:53:54.171  3509  3625 D LightsService: [SvcLED] handleForcedSvcLEDTask()
12-20 11:53:54.171  3509  3509 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
12-20 11:53:54.171  3509  3509 D WifiService: ACTIVITY_STATUS_UNKNOWN 
12-20 11:53:54.171  3509  3509 I PalmMotion: [PALM] SURFACE_MOTION_ENGINE: 1 SURFACE_PALM_TOUCH: 1
12-20 11:53:54.171  3509  3625 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
12-20 11:53:54.171  3509  3509 I PalmMotion: [PALM] SURFACE_PALM_SWIPE: 1
12-20 11:53:54.171  3509  3509 D PalmMotion: [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
12-20 11:53:54.171  3509  3509 D PalmMotion: [PALM] ACCEPTED : [hero2lte] PALM_CNT : 2, M_TOUCH : 50.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
12-20 11:53:54.171  3509  3509 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1144000  uid : 1000  pid : 3509  tag : WAKEUP_BOOSTER@34
12-20 11:53:54.171  3509  4333 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d57f69e u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6fe7727 4355:com.google.android.gms.persistent/u0a21}
12-20 11:53:54.171  3509  3791 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() true
12-20 11:53:54.171  3509  3791 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
12-20 11:53:54.171  3509  3791 D KnoxTimeoutHandler: post home show event for user 0
12-20 11:53:54.171  3509  3791 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
12-20 11:53:54.181  3509  3530 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
12-20 11:53:54.181  7178  7178 D SamsungIME: IMPL finishInput
12-20 11:53:54.181  7178  7178 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
12-20 11:53:54.181  7178  7178 D SamsungIME: saveAndClear +
12-20 11:53:54.181  7178  7178 D SamsungIME: saveAndClear -
12-20 11:53:54.181  7178  7178 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,12-20 11:53:54.191  4328  4328 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@72d1b85 time:142631
12-20 11:53:54.191  3829  3848 I TZ: mc_tlc_communication: tlc_open() succeeded
12-20 11:53:54.191  3509  4007 I TZ: client_server_communication: OpenSWConn(CCM) is successful
12-20 11:53:54.191  3509  4007 I TZ: client_server_communication: Client_Server_Open succeeded, serverName = CCM
12-20 11:53:54.191  3509  4007 I TZ_CCM_C_Initialize: : ctx = 0x7f8204fca0, comm = 0x7f7e72a340, sendmsg = 0x7f8e10b000, recvmsg = 0x7f8e10fc00
12-20 11:53:54.191  3509  4007 I TZ_init: : TZ_init: sending initialization request...
12-20 11:53:54.191  3509  4007 E TZ: client_server_communication: comm_request(0x7f7e72a340) pImpl->serverName : CCM 
12-20 11:53:54.191  3509  4007 E TZ: client_server_communication: comm_request(0x7f7e72a340) <IClientServer>pImpl->sconn : 0x7f821bf700 
12-20 11:53:54.191  3509  4007 E TZ: client_server_communication: comm_request(0x7f7e72a340) <IClientServer>pImpl->sconn->getInterfaceDescriptor() : CCM 
12-20 11:53:54.191  3509  4007 I TZ: client_server_communication: Cmd id = 2, len = 19456
12-20 11:53:54.191  3509  4007 I TZ: client_server_communication: Calling Communicate()
12-20 11:53:54.191  3829  3829 I TLC_SERVER: BnTLCServer::onTransact(2) 16
12-20 11:53:54.191  3829  3829 I TLC_SERVER: COMM
12-20 11:53:54.191  3509  3509 D MARsPolicyManager: NotificationListenerService OngoingNotificationRemoved : android
12-20 11:53:54.191  3509  3509 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
12-20 11:53:54.191  3509  3509 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
12-20 11:53:54.191  3509  3509 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
12-20 11:53:54.201  4181  4192 D CatchNotificationsService: onNotificationRemoved
12-20 11:53:54.201  4181  4192 D CatchNotificationsService: Notification removed
12-20 11:53:54.201  4194  4911 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=112]
12-20 11:53:54.201  4194  4194 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.people.package_name=android, samsung.people.notification_type=led_indicator}]
12-20 11:53:54.201  4194  4194 I PeopleStripeService: PeopleNotificationReceiver:3
12-20 11:53:54.201  4194  4194 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
12-20 11:53:54.201  4194  4194 I PeopleDataManager: removeNotification
12-20 11:53:54.201  4194  4194 I NotificationParser: getNotiType:android,led_indicator
12-20 11:53:54.201  4194  4194 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=true,key=null,removeAll=false
12-20 11:53:54.201  4194  4194 D PeopleDataManager: removeNotiInfo =null
12-20 11:53:54.201  3509  3509 I KnoxTimeoutHandler: Shared devices show user statefalse
12-20 11:53:54.201  4194  4911 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17040367,extra=Bundle[mParcelledData.dataSize=84]
12-20 11:53:54.201  4194  4194 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17040367, samsung.notification.type=normal, samsung.people.package_name=android}]
12-20 11:53:54.201  3509  3509 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in null rsrc of package android
12-20 11:53:54.201  4194  4194 I PeopleStripeService: PeopleNotificationReceiver:3
12-20 11:53:54.201  3509  3509 D MARsPolicyManager: NotificationListenerService OngoingNotificationPosted : android
12-20 11:53:54.201  4194  4194 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
12-20 11:53:54.201  4194  4194 I PeopleDataManager: removeNotification
12-20 11:53:54.201  4194  4194 I NotificationParser: getNotiType:android,null
12-20 11:53:54.201  4194  4194 D PeopleDataManager: removeNotiInfo: id =17040367,packageName=android,isEdgeNotification=false,key=null,removeAll=false
12-20 11:53:54.201  4194  4194 D PeopleDataManager: removeNotiInfo =null
12-20 11:53:54.201  6319  6319 I CocktailBarUiController: onUpdateCocktail: 2
12-20 11:53:54.201  6319  6319 I CocktailBarPanelManager: updatePanelItem: updateContainedPanel - 2
12-20 11:53:54.201  6319  6319 D CatchNotificationsView: setData
12-20 11:53:54.201  6319  6319 D CatchNotificationsView: Notification removed
12-20 11:53:54.201  6319  6319 D CatchNotificationsView: No notifications left to remove
12-20 11:53:54.201  6319  6319 D CatchNotificationsView: makeNoNotificationsPanel
12-20 11:53:54.201  3509  4486 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d57f69e u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8a82cf8 9251:com.samsung.android.sm/1000}
12-20 11:53:54.201  6319  6319 W ResourcesManager: getTopLevelResources: /system/priv-app/AppsEdgePanel/AppsEdgePanel.apk / 1.0 running in com.samsung.android.app.cocktailbarservice rsrc of package com.samsung.android.app.appsedge
12-20 11:53:54.211  3960  3960 D PhoneStatusBar: removeNotification key=-1|android|17040367|null|1000 old=StatusBarNotification(pkg=android user=UserHandle{-1} id=17040367 tag=null score=-20 key=-1|android|17040367|null|1000: Notification(pri=-2 contentView=android/0x10900a3 vibrate=null sound=null tick defaults=0x0 flags=0x2 color=0xff7792a9 vis=PUBLIC secFlags=0x0 secPriority=0))
12-20 11:53:54.211  6319  6319 W ResourcesManager: getTopLevelResources: /system/priv-app/AppsEdgePanel/AppsEdgePanel.apk / 1.0 running in com.samsung.android.app.cocktailbarservice rsrc of package com.samsung.android.app.appsedge
12-20 11:53:54.211  3960  3960 D PhoneStatusBar: setAreThereNotifications: N=0 any=false clearable=false
12-20 11:53:54.211  6319  6319 D PanelDescriptionView: updateHelpView: Apps edge2130903041 --> 2130903041 helpview reapplied:0
12-20 11:53:54.211  3960  3960 D PhoneStatusBar: hideKeyguard: state - 1, leaveOpen: false
12-20 11:53:54.211  3960  3960 D PhoneStatusBar: setBarState: state - 0
12-20 11:53:54.211  3960  3960 D StatusBar-Window: fnf=true sanc=false, kni=false, sbf=false
12-20 11:53:54.211  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:53:54.211  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : false panelVisible : false keyguardFadingAway : true bouncerShowing : false headsUpShowing : false
12-20 11:53:54.211  3960  3960 D CoverUI : applyHeight h = -1, oc = false, fa = true, ac = false, sc = false
12-20 11:53:54.211  3960  3960 I PhoneStatusBar: updateKeyguardState 1 to 0
12-20 11:53:54.211  4181  4192 D CatchNotificationsService: onNotificationPosted
12-20 11:53:54.211  6319  6319 W ResourcesManager: getTopLevelResources: /system/priv-app/AppsEdgePanel/AppsEdgePanel.apk / 1.0 running in com.samsung.android.app.cocktailbarservice rsrc of package com.samsung.android.app.appsedge
12-20 11:53:54.211  6319  6319 D CocktailBarUiController: postUpdatePanel: 257
,12-20 11:53:54.231  8550  8561 D BadgeProvider: query, [selection] : null
,12-20 11:53:54.231  3960  3960 D PanelView: setKeyguardBottomAreaVisibility() prevState=1, newState - 0 goingToShade - false
,12-20 11:53:54.231  3960  3960 D PanelView: updateQsState
,12-20 11:53:54.231  4181  4192 D CatchNotificationsSupportedAppsDBHelper: isDisabled value : false
12-20 11:53:54.231  4181  4192 D CatchNotificationsSupportedAppsDBHelper: isPackageSupported value : false
12-20 11:53:54.231  4181  4192 D CatchNotificationsService: Notification from package is not supported
,12-20 11:53:54.241  3960  3960 D KeyguardSecurityModel: getSecurityMode( getActivePasswordQuality = 0 , currentuser = 0
,12-20 11:53:54.241  3960  3960 D StatusBar-Window: fnf=true sanc=false, kni=false, sbf=false
12-20 11:53:54.241  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:53:54.241  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : false panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
12-20 11:53:54.241  3960  3960 D CoverUI : applyHeight h = 96, oc = false, fa = false, ac = false, sc = false
12-20 11:53:54.241  3960  3960 D KeyguardEffectViewController: setKeyguardFadingAway = false
12-20 11:53:54.241  3960  3960 D KeyguardEffectViewController: mShowing=false, mOccluded=false, mKeyguardFadingAway=false, match_parent=true
12-20 11:53:54.241  3960  3960 D KeyguardEffectViewController: ## mBackgroundView.onPause()
12-20 11:53:54.241  3960  3960 D KeyguardEffectViewLayered: onPause()
,12-20 11:53:54.261  3960  4234 D BluetoothTile: handleUpdateState :  supported = true, enabled = true, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,12-20 11:53:54.261  3960  4234 D AirplaneModeTile: getQSTileMultiState 1
,12-20 11:53:54.261  3960  4234 D FlashlightTile: handleUpdateState :  MultiState[visible=true,icon=ResourceIcon[resId=0x7f020363],label=Latarka,contentDescription=Latarka Przycisk Wył.,dualLabelContentDescription=null,autoMirrorDrawable=false,secondaryLabel=null,textTruncate=true,value=2,bgValue=0] arg : null
,12-20 11:53:54.261  3960  4234 D HotspotTile: handleUpdateState :mState.value =  2, 2
,12-20 11:53:54.261  3960  4234 D PersonalModeTile: getMState state = 2
,12-20 11:53:54.271  3960  4234 D AodTile :  ExclusiveFeature getCount = 0
,12-20 11:53:54.271  3960  4234 D AodTile : handleUpdateState :  MultiState[visible=true,icon=ResourceIcon[resId=0x7f020367],label=Always On
12-20 11:53:54.271  3960  4234 D AodTile : Display,contentDescription=Always On Display Przycisk Wł.,dualLabelContentDescription=null,autoMirrorDrawable=false,secondaryLabel=null,textTruncate=false,value=1,bgValue=0] arg : null
,12-20 11:53:54.271  3018  4572 D libEGL  : eglTerminate EGLDisplay = 0x7fa22ffe78
12-20 11:53:54.271  3018  4572 D libEGL  : eglTerminate EGLDisplay = 0x7fa22ffe78
,12-20 11:53:54.271  3960  4161 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x96]-format:1
12-20 11:53:54.271  3960  3960 D KeyguardEffectViewController: onLayoutChange() v: com.android.keyguard.effect.EffectBehindView{eefe3f3 I.E...... ......ID 0,0-1440,96 #7f0e0330 app:id/keyguard_effect_behind}, bottom : 96, oldBottom : 2560
12-20 11:53:54.271  3960  3960 D KeyguardEffectViewController: mShowing=false, mOccluded=false, mKeyguardFadingAway=false, match_parent=false
12-20 11:53:54.271  3960  3960 W View    : requestLayout() improperly called by com.android.systemui.qs.QSContainer{c359d8d V.E...... ......ID 0,464-1440,1212 #7f0e01c1 app:id/quick_settings_container} during layout: running second layout pass
12-20 11:53:54.271  3960  3960 I ViewRootImpl: requestLayout is already in process
,12-20 11:53:54.291  3175  3651 V audio_hw_primary: select_devices() output_route "media-speaker" 
12-20 11:53:54.291  3175  3651 I audio_route: 
12-20 11:53:54.291  3175  3651 I audio_route: > audio_route_apply_path : "gain-media-speaker"
,12-20 11:53:54.291  3175  3651 V audio_hw_primary: select_devices() output_gain "gain-media-speaker" 
12-20 11:53:54.291  3175  3651 I audio_route: 
12-20 11:53:54.291  3175  3651 I audio_route: > audio_route_update_mixer : +
12-20 11:53:54.291  3175  3651 I audio_route: > audio_route_update_mixer : changed(0) -
12-20 11:53:54.291  3175  3651 I audio_hw_primary: select_devices - 
12-20 11:53:54.291  3175  3651 V audio_hw_primary: start_output_stream-
,12-20 11:53:54.301  3509  4007 I TZ_init: : TZ_init: successful initialization
12-20 11:53:54.301  3509  4007 I TLC_TZ_COMMON: key_db_init: : Exercising TZ_DB_INIT in TLC
12-20 11:53:54.301  3509  4007 E TZ: client_server_communication: comm_request(0x7f7e72a340) pImpl->serverName : CCM 
12-20 11:53:54.301  3509  4007 E TZ: client_server_communication: comm_request(0x7f7e72a340) <IClientServer>pImpl->sconn : 0x7f821bf700 
12-20 11:53:54.301  3509  4007 E TZ: client_server_communication: comm_request(0x7f7e72a340) <IClientServer>pImpl->sconn->getInterfaceDescriptor() : CCM 
12-20 11:53:54.301  3509  4007 I TZ: client_server_communication: Cmd id = 17, len = 19456
12-20 11:53:54.301  3509  4007 I TZ: client_server_communication: Calling Communicate()
12-20 11:53:54.301  3829  3848 I TLC_SERVER: BnTLCServer::onTransact(2) 16
12-20 11:53:54.301  3829  3848 I TLC_SERVER: COMM
,12-20 11:53:54.311  3509  4007 I TZ_COMMON: tlc_key_db_util: : DB Operation suceeded
12-20 11:53:54.311  3509  4007 E TZ: client_server_communication: comm_request(0x7f7e72a340) pImpl->serverName : CCM 
12-20 11:53:54.311  3509  4007 E TZ: client_server_communication: comm_request(0x7f7e72a340) <IClientServer>pImpl->sconn : 0x7f821bf700 
12-20 11:53:54.311  3509  4007 E TZ: client_server_communication: comm_request(0x7f7e72a340) <IClientServer>pImpl->sconn->getInterfaceDescriptor() : CCM 
12-20 11:53:54.311  3509  4007 I TZ: client_server_communication: Cmd id = 46, len = 19456
12-20 11:53:54.311  3509  4007 I TZ: client_server_communication: Calling Communicate()
12-20 11:53:54.311  3829  3829 I TLC_SERVER: BnTLCServer::onTransact(2) 16
12-20 11:53:54.311  3829  3829 I TLC_SERVER: COMM
,12-20 11:53:54.311  3960  3960 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,12-20 11:53:54.321  3960  3960 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,12-20 11:53:54.321  3960  3960 D NotificationStackScrollLayout:  scroll range should be extended : 1588
,12-20 11:53:54.321  3960  3960 D PhoneStatusBar: setAreThereNotifications: N=1 any=true clearable=false
12-20 11:53:54.321  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:53:54.321  3018  3018 D libEGL  : eglTerminate EGLDisplay = 0x7fff7e5b48
,12-20 11:53:54.321  3509  4007 I TZ_CCM_C_Finalize: : DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
12-20 11:53:54.321  3509  4007 E TZ: client_server_communication: comm_request(0x7f7e72a340) pImpl->serverName : CCM 
12-20 11:53:54.321  3509  4007 E TZ: client_server_communication: comm_request(0x7f7e72a340) <IClientServer>pImpl->sconn : 0x7f821bf700 
12-20 11:53:54.321  3509  4007 E TZ: client_server_communication: comm_request(0x7f7e72a340) <IClientServer>pImpl->sconn->getInterfaceDescriptor() : CCM 
12-20 11:53:54.321  3509  4007 I TZ: client_server_communication: Cmd id = 41, len = 19456
12-20 11:53:54.321  3509  4007 I TZ: client_server_communication: Calling Communicate()
12-20 11:53:54.321  3829  3848 I TLC_SERVER: BnTLCServer::onTransact(2) 16
12-20 11:53:54.321  3829  3848 I TLC_SERVER: COMM
,12-20 11:53:54.331  3960  3960 D NotificationStackScrollLayout:  scroll range should be extended : 1588
12-20 11:53:54.331  3960  3960 D NotificationStackScrollLayout:  scroll range should be extended : 1588
12-20 11:53:54.331  3960  3960 D NotificationStackScrollLayout:  scroll range should be extended : 1588
12-20 11:53:54.331  3960  3960 D NotificationStackScrollLayout:  scroll range should be extended : 1588
,12-20 11:53:54.331  3509  4007 I TZ: client_server_communication: Client_Server_Close was called
,12-20 11:53:54.331  3829  3829 I TLC_SERVER: BnTLCServer::onTransact(1) 16
12-20 11:53:54.331  3829  3829 I TLC_SERVER: CLOSESWCONN
12-20 11:53:54.331  3829  3829 I TZ: mc_tlc_communication: tlc_close() was called
12-20 11:53:54.331  3829  3829 I TZ: mc_tlc_communication: Closing the session
,12-20 11:53:54.331  3829  3829 I TZ: mc_tlc_communication: Freeing message buffer
,12-20 11:53:54.331  3829  3829 I TZ: mc_tlc_communication: Closing MobiCore device
12-20 11:53:54.331  3829  3829 I TeeDriverClient: driver client closed [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:113]
12-20 11:53:54.331  3829  3829 I TZ: mc_tlc_communication: tlc_close() succeeded
12-20 11:53:54.331  3509  4007 I TZ: client_server_communication: Client_Server_Close succeeded
12-20 11:53:54.331  3509  4007 I TZ: client_server_communication: IClientServer::~IClientServer()
,12-20 11:53:54.331  3509  4007 I FipsTimaKeyStore: CCM is available on this device
12-20 11:53:54.331  3509  4007 D TimaService: TIMA3: FipsKeyStore3_exist
,12-20 11:53:54.331  3509  4007 I FipsTimaKeyStore: CCM is NOT enabled for this user
12-20 11:53:54.331  3509  4007 D TimaService: TIMA: in getTimaVersion
12-20 11:53:54.331  3509  4007 I         : TimaKeyStore: tima_KeyStore3_exist_JNI
12-20 11:53:54.331  3509  4007 I         : TimaKeyStore: callingUid is 1000
12-20 11:53:54.331  3509  4007 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_encrypt_filename()
,12-20 11:53:54.331  3509  4007 I TLC_TZ_KEYSTORE: : creating new keystore context...
12-20 11:53:54.331  3509  4007 I TLC_TZ_KEYSTORE: : initializing ccm context...
12-20 11:53:54.331  3509  4007 I TLC_TZ_KEYSTORE: : root = 0, root_strlen = 1
12-20 11:53:54.331  3509  4007 I TLC_TZ_KEYSTORE: : process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:53:54.331  3509  4007 I TZ: mc_tlc_communication: input max_sendmsg_size = 1080
12-20 11:53:54.331  3509  4007 I TZ: mc_tlc_communication: input max_recvmsg_size = 1080
12-20 11:53:54.331  3509  4007 I TZ: mc_tlc_communication: root = 0, root_len = 1
,12-20 11:53:54.331  3509  4007 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:53:54.331  3509  4007 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 1088
12-20 11:53:54.331  3509  4007 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 1088
12-20 11:53:54.331  3509  4007 I TZ: mc_tlc_communication: device_id = 0x0
12-20 11:53:54.331  3509  4007 I TZ: mc_tlc_communication: tlc_open() was called
12-20 11:53:54.331  3509  4007 I TZ: mc_tlc_communication: Opening MobiCore device
12-20 11:53:54.331  3509  4007 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
,12-20 11:53:54.331  3509  4007 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-20 11:53:54.331  3509  4007 I TZ: mc_tlc_communication: Opening the session
,12-20 11:53:54.341  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:53:54.351  3509  4007 I TZ: mc_tlc_communication: tlc_open() succeeded
,12-20 11:53:54.351  3509  4007 I TLC_TZ_KEYSTORE: : ctx = 0x7f8204fca0, comm = 0x7f7e72a340, sendmsg = 0x7f958fa000, recvmsg = 0x7f958fa440
12-20 11:53:54.351  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ_COMMON: Get_filename - allow_hashing: 0
12-20 11:53:54.351  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ GetFN : priv_data.in_filename: 1000_KS_SKEY_PersonaPwdResetToken0, len: 34
12-20 11:53:54.351  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ CCM : priv_data.in_fn_len: 34
12-20 11:53:54.351  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ GetFN : Starting
,12-20 11:53:54.361  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:53:54.361  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ GetFN : enc filename: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
,12-20 11:53:54.361  3509  4007 I TZ: mc_tlc_communication: tlc_close() was called
12-20 11:53:54.361  3509  4007 I TZ: mc_tlc_communication: Closing the session
,12-20 11:53:54.361  3509  4007 I TZ: mc_tlc_communication: Freeing message buffer
,12-20 11:53:54.361  3509  4007 I TZ: mc_tlc_communication: Closing MobiCore device
12-20 11:53:54.361  3509  4007 I TeeDriverClient: driver client closed [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:113]
12-20 11:53:54.361  3509  4007 I TZ: mc_tlc_communication: tlc_close() succeeded
12-20 11:53:54.361  3509  4007 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
12-20 11:53:54.361  3509  4007 D TimaService: TIMA3: FipsKeyStore3_exist
12-20 11:53:54.361  3509  4007 I         : TimaKeyStore: encryptFilename : filename is: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
12-20 11:53:54.361  3509  4007 D TimaService: TIMA: in getTimaVersion
12-20 11:53:54.361  3509  4007 I         : TimaKeyStore: /data/misc/fips_tima_keystore/user_0/057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E exists
12-20 11:53:54.361  3509  4007 I         : TimaKeyStore: tima_KeyStore3_exist_JNI
,12-20 11:53:54.361  3509  4007 I         : TimaKeyStore: callingUid is 1000
12-20 11:53:54.361  3509  4007 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_encrypt_filename()
12-20 11:53:54.361  3509  4007 I TLC_TZ_KEYSTORE: : creating new keystore context...
12-20 11:53:54.361  3509  4007 I TLC_TZ_KEYSTORE: : initializing ccm context...
12-20 11:53:54.361  3509  4007 I TLC_TZ_KEYSTORE: : root = 0, root_strlen = 1
12-20 11:53:54.361  3509  4007 I TLC_TZ_KEYSTORE: : process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:53:54.361  3509  4007 I TZ: mc_tlc_communication: input max_sendmsg_size = 1080
12-20 11:53:54.361  3509  4007 I TZ: mc_tlc_communication: input max_recvmsg_size = 1080
12-20 11:53:54.361  3509  4007 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-20 11:53:54.361  3509  4007 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:53:54.361  3509  4007 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 1088
12-20 11:53:54.361  3509  4007 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 1088
,12-20 11:53:54.361  3509  4007 I TZ: mc_tlc_communication: device_id = 0x0
12-20 11:53:54.361  3509  4007 I TZ: mc_tlc_communication: tlc_open() was called
12-20 11:53:54.361  3509  4007 I TZ: mc_tlc_communication: Opening MobiCore device
12-20 11:53:54.361  3509  4007 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
12-20 11:53:54.361  3509  4007 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-20 11:53:54.361  3509  4007 I TZ: mc_tlc_communication: Opening the session
,12-20 11:53:54.381  3509  4007 I TZ: mc_tlc_communication: tlc_open() succeeded
12-20 11:53:54.381  3509  4007 I TLC_TZ_KEYSTORE: : ctx = 0x7f8204fca0, comm = 0x7f7e72a340, sendmsg = 0x7f958fa000, recvmsg = 0x7f958fa440
,12-20 11:53:54.381  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ_COMMON: Get_filename - allow_hashing: 0
12-20 11:53:54.381  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ GetFN : priv_data.in_filename: 1000_KS_SKEY_PersonaPwdResetToken0, len: 34
12-20 11:53:54.381  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ CCM : priv_data.in_fn_len: 34
12-20 11:53:54.381  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ GetFN : Starting
,12-20 11:53:54.391  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ GetFN : enc filename: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
,12-20 11:53:54.391  3509  4007 I TZ: mc_tlc_communication: tlc_close() was called
12-20 11:53:54.391  3509  4007 I TZ: mc_tlc_communication: Closing the session
,12-20 11:53:54.391  3509  4007 I TZ: mc_tlc_communication: Freeing message buffer
,12-20 11:53:54.391  3509  4007 I TZ: mc_tlc_communication: Closing MobiCore device
12-20 11:53:54.391  3509  4007 I TeeDriverClient: driver client closed [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:113]
12-20 11:53:54.391  3509  4007 I TZ: mc_tlc_communication: tlc_close() succeeded
12-20 11:53:54.391  3509  4007 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
12-20 11:53:54.391  3509  4007 I         : TimaKeyStore: encryptFilename : filename is: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
12-20 11:53:54.391  3509  4007 I         : TimaKeyStore: /data/misc/fips_tima_keystore/user_0/057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E exists
,12-20 11:53:54.401  3509  4007 I         : TimaKeyStore: tima_KeyStore3_exist_JNI
,12-20 11:53:54.401  3509  4007 D TimaService: TIMA3: FipsKeyStore3_exist
12-20 11:53:54.401  3509  4007 I         : TimaKeyStore: callingUid is 1000
12-20 11:53:54.401  3509  4007 D TimaService: TIMA: in getTimaVersion
12-20 11:53:54.401  3509  4007 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_encrypt_filename()
12-20 11:53:54.401  3509  4007 I TLC_TZ_KEYSTORE: : creating new keystore context...
12-20 11:53:54.401  3509  4007 I TLC_TZ_KEYSTORE: : initializing ccm context...
12-20 11:53:54.401  3509  4007 I TLC_TZ_KEYSTORE: : root = 0, root_strlen = 1
12-20 11:53:54.401  3509  4007 I TLC_TZ_KEYSTORE: : process = ffffffff000000000000000000000013, process_strlen = 32
,12-20 11:53:54.401  3509  4007 I TZ: mc_tlc_communication: input max_sendmsg_size = 1080
12-20 11:53:54.401  3509  4007 I TZ: mc_tlc_communication: input max_recvmsg_size = 1080
12-20 11:53:54.401  3509  4007 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-20 11:53:54.401  3509  4007 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:53:54.401  3509  4007 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 1088
12-20 11:53:54.401  3509  4007 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 1088
12-20 11:53:54.401  3509  4007 I TZ: mc_tlc_communication: device_id = 0x0
12-20 11:53:54.401  3509  4007 I TZ: mc_tlc_communication: tlc_open() was called
,12-20 11:53:54.401  3509  4007 I TZ: mc_tlc_communication: Opening MobiCore device
12-20 11:53:54.401  3509  4007 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
12-20 11:53:54.401  3509  4007 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-20 11:53:54.401  3509  4007 I TZ: mc_tlc_communication: Opening the session
,12-20 11:53:54.421  3509  4007 I TZ: mc_tlc_communication: tlc_open() succeeded
,12-20 11:53:54.421  3509  4007 I TLC_TZ_KEYSTORE: : ctx = 0x7f8204fca0, comm = 0x7f7e72a340, sendmsg = 0x7f958fa000, recvmsg = 0x7f958fa440
12-20 11:53:54.421  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ_COMMON: Get_filename - allow_hashing: 0
12-20 11:53:54.421  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ GetFN : priv_data.in_filename: 1000_KS_SKEY_PersonaPwdResetToken0, len: 34
12-20 11:53:54.421  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ CCM : priv_data.in_fn_len: 34
12-20 11:53:54.421  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ GetFN : Starting
,12-20 11:53:54.431  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ GetFN : enc filename: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
,12-20 11:53:54.431  3509  4007 I TZ: mc_tlc_communication: tlc_close() was called
12-20 11:53:54.431  3509  4007 I TZ: mc_tlc_communication: Closing the session
,12-20 11:53:54.431  3182  3221 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, 86, -88, -18, 1, 0
,12-20 11:53:54.431  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, 86, -88, -18, 1, 0
12-20 11:53:54.431  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
12-20 11:53:54.431  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
12-20 11:53:54.431  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, 86, -88, -18, 1, 0,
12-20 11:53:54.431  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
12-20 11:53:54.431  3509  3838 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[1], TimeStamp=[1482231233774]
12-20 11:53:54.431  3509  4007 I TZ: mc_tlc_communication: Freeing message buffer
12-20 11:53:54.431  3509  4007 I TZ: mc_tlc_communication: Closing MobiCore device
12-20 11:53:54.431  3509  4007 I TeeDriverClient: driver client closed [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:113]
12-20 11:53:54.431  3509  4007 D TimaService: TIMA3: FipsKeyStore3_exist
12-20 11:53:54.431  3509  4007 I TZ: mc_tlc_communication: tlc_close() succeeded
12-20 11:53:54.431  3509  4007 D TimaService: TIMA: in getTimaVersion
12-20 11:53:54.431  3509  4007 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
12-20 11:53:54.431  3509  4007 I         : TimaKeyStore: encryptFilename : filename is: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
12-20 11:53:54.431  3509  4007 I         : TimaKeyStore: /data/misc/fips_tima_keystore/user_0/057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E exists
,12-20 11:53:54.431  3509  4007 I         : TimaKeyStore: tima_KeyStore3_exist_JNI
12-20 11:53:54.431  3509  3509 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
12-20 11:53:54.431  3509  4007 I         : TimaKeyStore: callingUid is 1000
12-20 11:53:54.431  3509  3509 D WifiService: ACTIVITY_STATUS_STATIONARY 
12-20 11:53:54.431  3509  4007 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_encrypt_filename()
12-20 11:53:54.431  3509  4007 I TLC_TZ_KEYSTORE: : creating new keystore context...
12-20 11:53:54.431  3509  3841 D SContextService: updateSContext() : event = Activity Tracker
12-20 11:53:54.431  3509  4007 I TLC_TZ_KEYSTORE: : initializing ccm context...
12-20 11:53:54.431  3509  4007 I TLC_TZ_KEYSTORE: : root = 0, root_strlen = 1
12-20 11:53:54.431  6319  6319 I TrayVisibilityController: handleMessage : msg.what = 1
12-20 11:53:54.431  3509  4007 I TLC_TZ_KEYSTORE: : process = ffffffff000000000000000000000013, process_strlen = 32
,12-20 11:53:54.431  3509  4007 I TZ: mc_tlc_communication: input max_sendmsg_size = 1080
12-20 11:53:54.431  3509  4007 I TZ: mc_tlc_communication: input max_recvmsg_size = 1080
12-20 11:53:54.431  3509  4007 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-20 11:53:54.431  3509  4007 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:53:54.431  3509  4007 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 1088
12-20 11:53:54.431  3509  4007 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 1088
12-20 11:53:54.431  3509  4007 I TZ: mc_tlc_communication: device_id = 0x0
,12-20 11:53:54.431  3509  4007 I TZ: mc_tlc_communication: tlc_open() was called
12-20 11:53:54.431  3509  4007 I TZ: mc_tlc_communication: Opening MobiCore device
12-20 11:53:54.431  3509  4007 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
12-20 11:53:54.431  3509  4007 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-20 11:53:54.431  3509  4007 I TZ: mc_tlc_communication: Opening the session
12-20 11:53:54.431  6319  6319 I Utils   : isCurrentUser current = 0, ownerId = 0
12-20 11:53:54.431  6319  6319 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 1
,12-20 11:53:54.431  6319  6319 I TrayVisibilityController: updateTrayVisible : State : 1 visible = 1 mCurrentVisible = 1
12-20 11:53:54.431  4194  4194 I PeopleStripeVisibilityController: handleMessage : msg.what = 1
12-20 11:53:54.431  4194  4194 I PeopleStripeVisibilityController: getComputedTrayVisible : keyguardState = 1
12-20 11:53:54.431  4194  4194 I PeopleStripeVisibilityController: isVisibleByAlwaysOn : mState = 1
12-20 11:53:54.431  6319  6319 D TrayStateController: onNotifyUpdateTray: 0 to need to visible? true
12-20 11:53:54.431  4194  4194 I PeopleStripeProcessMonitor: isPeopleStripeTask packageName = com.sec.android.app.launcher 0
,12-20 11:53:54.441  4194  4194 I PeopleStripeVisibilityController: updateStripeVisible : State 1 visible = 1
12-20 11:53:54.441  4194  4194 I PeopleStripeManager: isExistVisibleHandler false
12-20 11:53:54.441  4194  4194 I PeopleStripeManager: showStripe Not exist noti handler.
,12-20 11:53:54.451  3509  4007 I TZ: mc_tlc_communication: tlc_open() succeeded
,12-20 11:53:54.451  3509  4007 I TLC_TZ_KEYSTORE: : ctx = 0x7f8204fca0, comm = 0x7f7e72a340, sendmsg = 0x7f958fa000, recvmsg = 0x7f958fa440
12-20 11:53:54.451  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ_COMMON: Get_filename - allow_hashing: 0
12-20 11:53:54.451  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ GetFN : priv_data.in_filename: 1000_KS_SKEY_PersonaPwdResetToken0, len: 34
12-20 11:53:54.451  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ CCM : priv_data.in_fn_len: 34
12-20 11:53:54.451  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ GetFN : Starting
,12-20 11:53:54.461  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ GetFN : enc filename: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
12-20 11:53:54.461  3509  4007 I TZ: mc_tlc_communication: tlc_close() was called
,12-20 11:53:54.461  3509  4007 I TZ: mc_tlc_communication: Closing the session
,12-20 11:53:54.461  3509  4007 D TimaService: TIMA3: FipsKeyStore3_get
12-20 11:53:54.461  3509  4007 I TZ: mc_tlc_communication: Freeing message buffer
12-20 11:53:54.461  3509  4007 D TimaService: TIMA: in getTimaVersion
12-20 11:53:54.461  3509  4007 I TZ: mc_tlc_communication: Closing MobiCore device
12-20 11:53:54.461  3509  4007 I TeeDriverClient: driver client closed [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:113]
12-20 11:53:54.461  3509  4007 I TZ: mc_tlc_communication: tlc_close() succeeded
12-20 11:53:54.461  3509  4007 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
12-20 11:53:54.461  3509  4007 I         : TimaKeyStore: encryptFilename : filename is: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
,12-20 11:53:54.461  3509  4007 I         : TimaKeyStore: /data/misc/fips_tima_keystore/user_0/057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E exists
12-20 11:53:54.461  3509  4007 I         : TimaKeyStore: tima_KeyStore3_get_JNI
12-20 11:53:54.461  3509  4007 I         : TimaKeyStore: callingUid is 1000
12-20 11:53:54.461  3509  4007 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_encrypt_filename()
12-20 11:53:54.461  3509  4007 I TLC_TZ_KEYSTORE: : creating new keystore context...
12-20 11:53:54.461  3509  4007 I TLC_TZ_KEYSTORE: : initializing ccm context...
12-20 11:53:54.461  3509  4007 I TLC_TZ_KEYSTORE: : root = 0, root_strlen = 1
,12-20 11:53:54.461  3509  4007 I TLC_TZ_KEYSTORE: : process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:53:54.461  3509  4007 I TZ: mc_tlc_communication: input max_sendmsg_size = 1080
12-20 11:53:54.461  3509  4007 I TZ: mc_tlc_communication: input max_recvmsg_size = 1080
12-20 11:53:54.461  3509  4007 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-20 11:53:54.461  3509  4007 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:53:54.461  3509  4007 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 1088
12-20 11:53:54.461  3509  4007 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 1088
12-20 11:53:54.461  3509  4007 I TZ: mc_tlc_communication: device_id = 0x0
,12-20 11:53:54.461  3509  4007 I TZ: mc_tlc_communication: tlc_open() was called
12-20 11:53:54.461  3509  4007 I TZ: mc_tlc_communication: Opening MobiCore device
12-20 11:53:54.461  3509  4007 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
12-20 11:53:54.461  3509  4007 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-20 11:53:54.461  3509  4007 I TZ: mc_tlc_communication: Opening the session
,12-20 11:53:54.481  3509  4007 I TZ: mc_tlc_communication: tlc_open() succeeded
12-20 11:53:54.481  3509  4007 I TLC_TZ_KEYSTORE: : ctx = 0x7f8204fca0, comm = 0x7f7e72a340, sendmsg = 0x7f958fa000, recvmsg = 0x7f958fa440
12-20 11:53:54.481  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ_COMMON: Get_filename - allow_hashing: 0
,12-20 11:53:54.481  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ GetFN : priv_data.in_filename: 1000_KS_SKEY_PersonaPwdResetToken0, len: 34
12-20 11:53:54.481  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ CCM : priv_data.in_fn_len: 34
12-20 11:53:54.481  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ GetFN : Starting
,12-20 11:53:54.491  3509  4007 I TLC_TZ_COMMON: get_filename: : TZ GetFN : enc filename: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
,12-20 11:53:54.491  3509  4007 I TZ: mc_tlc_communication: tlc_close() was called
12-20 11:53:54.491  3509  4007 I TZ: mc_tlc_communication: Closing the session
12-20 11:53:54.491  4607  9600 D MdnsClient: #acquireLock. Multicast lock not held. Acquiring
,12-20 11:53:54.501  3509  4333 E BatteryStatsImpl: Wifi multicast lock enabled by UID  = 10021
,12-20 11:53:54.501  3509  4007 I TZ: mc_tlc_communication: Freeing message buffer
12-20 11:53:54.501  3509  4007 I TZ: mc_tlc_communication: Closing MobiCore device
12-20 11:53:54.501  3509  4007 I TeeDriverClient: driver client closed [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:113]
12-20 11:53:54.501  3509  4007 I TZ: mc_tlc_communication: tlc_close() succeeded
12-20 11:53:54.501  3509  4007 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
12-20 11:53:54.501  3509  4007 I         : TimaKeyStore: encryptFilename : filename is: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
12-20 11:53:54.501  3509  4007 I TLC_TZ_KEYSTORE: : TZ_KEYSTORE_fips_unwrap_key
12-20 11:53:54.501  3509  4007 I TLC_TZ_KEYSTORE: : creating new keystore context...
12-20 11:53:54.501  3509  4007 I TLC_TZ_KEYSTORE: : initializing ccm context...
12-20 11:53:54.501  3509  4007 I TLC_TZ_KEYSTORE: : root = 0, root_strlen = 1
12-20 11:53:54.501  3509  4007 I TLC_TZ_KEYSTORE: : process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:53:54.501  3509  4007 I TZ: mc_tlc_communication: input max_sendmsg_size = 1080
12-20 11:53:54.501  3509  4007 I TZ: mc_tlc_communication: input max_recvmsg_size = 1080
12-20 11:53:54.501  3509  4007 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-20 11:53:54.501  3509  4007 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:53:54.501  3509  4007 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 1088
12-20 11:53:54.501  3509  4007 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 1088
12-20 11:53:54.501  3509  4007 I TZ: mc_tlc_communication: device_id = 0x0
12-20 11:53:54.501  3509  4007 I TZ: mc_tlc_communication: tlc_open() was called
12-20 11:53:54.501  3509  4007 I TZ: mc_tlc_communication: Opening MobiCore device
12-20 11:53:54.501  3509  4007 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
12-20 11:53:54.501  3509  4007 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-20 11:53:54.501  3509  4007 I TZ: mc_tlc_communication: Opening the session
,12-20 11:53:54.521  3509  4007 I TZ: mc_tlc_communication: tlc_open() succeeded
12-20 11:53:54.521  3509  4007 I TLC_TZ_KEYSTORE: : ctx = 0x7f8204fca0, comm = 0x7f7e72a340, sendmsg = 0x7f958fa000, recvmsg = 0x7f958fa440
12-20 11:53:54.521  3509  4007 I TLC_TZ_KEYSTORE: unwrap_key: : TZ_KEYSTORE_fips_unwrap_key_TLC...
12-20 11:53:54.521  3509  4007 I TLC_TZ_KEYSTORE: unwrap_key: : TZ_KEYSTORE_unwrap_key_START...
,12-20 11:53:54.541  3509  4007 I TLC_TZ_KEYSTORE: unwrap_key: : TZ_KEYSTORE_unwrap_key_END...
12-20 11:53:54.541  3509  4007 I TZ: mc_tlc_communication: tlc_close() was called
12-20 11:53:54.541  3509  4007 I TZ: mc_tlc_communication: Closing the session
,12-20 11:53:54.541  3509  4007 I TZ: mc_tlc_communication: Freeing message buffer
12-20 11:53:54.541  3509  4007 I TZ: mc_tlc_communication: Closing MobiCore device
12-20 11:53:54.541  3509  4007 I TeeDriverClient: driver client closed [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:113]
12-20 11:53:54.541  3509  4007 I TZ: mc_tlc_communication: tlc_close() succeeded
12-20 11:53:54.541  3509  4007 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
12-20 11:53:54.541  3509  4007 I         : TimaKeyStore: returning bytearray
12-20 11:53:54.541  3509  4007 D TimaHelper: Found key : PersonaPwdResetToken0 from TIMA keystore
12-20 11:53:54.541  3509  4007 I KeyManagementUtil: retrieveCMK :: Inside
12-20 11:53:54.541  3509  4007 D KeyManagementUtil: verifyKEK :: Inside
12-20 11:53:54.541  3509  4007 D KeyManagementUtil: SND -> {keymanagement_cmd verify_kek}
,12-20 11:53:54.541  3198  3293 D SDP_JNI_SKMM2:  [sdp] CALL - VerifyKEK..... 
12-20 11:53:54.541  3198  3293 D SDP_JNI_SKMM2: verifyKEK ..... 
12-20 11:53:54.541  3198  3293 D SDP_JNI_SKMM2: verifyKEK :: id=0, type=MDM
,12-20 11:53:54.541  3198  3293 E SDP_DAEMON_SKMM2: int __read_payload(int, void*, size_t)(size:660)
,12-20 11:53:54.551  3198  3293 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
,12-20 11:53:54.551  3198  3293 D SKMM_v2.0_Mobicore_Helper: Try Trustlet Open Session
,12-20 11:53:54.571  3198  3293 I SDP_DAEMON_SKMM2: Initialized Successfully(0)
,12-20 11:53:54.571  3198  3293 I SDP_DAEMON_SKMM2: security.mdpp(Ready)
12-20 11:53:54.571  3198  3293 I SDP_DAEMON_SKMM2: security.mdpp.mass(skmm)
,12-20 11:53:54.581  3175  3540 I APM::AudioPolicyManager: stopOutput() output 4, stream 1, session 26
,12-20 11:53:54.631  3198  3293 D SKMM_v2.0_Mobicore_Helper: Send Trustlet TCI Message
,12-20 11:53:54.641  3198  3293 I TeeDriverClient: driver client closed [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:113]
,12-20 11:53:54.641  3198  3293 D SDP_JNI_SKMM2: verifyKEK ..... End
12-20 11:53:54.641  3509  3859 D KeyManagementUtil: RCV <-
12-20 11:53:54.641  3509  4007 D KeyManagementUtil: RMV <-
12-20 11:53:54.641  3509  4007 D KeyManagementUtil: event called.
12-20 11:53:54.641  3509  4007 D SdpManagerService: cacheMasterKey :: 0
,12-20 11:53:54.641  3509  4007 E SDP.CRYPTO: 
12-20 11:53:54.641  3509  4007 E SDP.CRYPTO: int sdp_drv_on_unlocked(int, const char*, int)(0)
12-20 11:53:54.641  3509  4007 E SDP.CRYPTO: Rpri loaded
12-20 11:53:54.641  3509  4007 E SDP.CRYPTO: Dpri loaded
12-20 11:53:54.641  3509  4007 E SDP.CRYPTO: No hash for ECDH verification.. need to migrate?? 
12-20 11:53:54.641  3509  4007 E SDP.CRYPTO: EDpri loaded
12-20 11:53:54.641  3509  4007 E SDP.CRYPTO: sym loaded
12-20 11:53:54.641  3509  4007 E SDP.CRYPTO:     On User Unlock OK, id 0
,12-20 11:53:54.641  3509  4007 E SdpManagerService: sendBroadcastAsUser(INTENT_SDP_STATE_CHANGED, state:2)
,12-20 11:53:54.641  3960  9587 D KeyguardViewMediator: unlockSdp :: Unlock SDP Successful..!
,12-20 11:53:54.651  3509  3593 V BroadcastQueue: [foreground] Process cur broadcast BroadcastRecord{f106e11 u0 com.sec.sdp.SDP_STATE_CHANGED qIdx=2}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{56c7d71 9501:com.sec.android.app.sbrowser/u0a141}
,12-20 11:53:54.651  3509  3531 E SdpServiceKeeper: isLicensed {pid:9501 uid:10141 userid:0 doPkg:null}
12-20 11:53:54.651  3509  3531 E SdpServiceKeeper: White listed. Skip license activation
,12-20 11:53:54.651  9501  9501 E SdpStateChangedReceiver: com.sec.enterprise.knox.sdp.exception.SdpEngineNotExistsException
,12-20 11:53:54.671  3509  3925 D lights  : button : 0 +
,12-20 11:53:54.701  3509  3925 D lights  : button : 0 -
,12-20 11:53:54.741  3960  3960 V KeyguardDisplayManager: hide (true)
,12-20 11:53:54.981  3182  3221 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, 86, -85, 16, 1, 1
,12-20 11:53:54.981  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, 86, -85, 16, 1, 1
,12-20 11:53:54.981  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
12-20 11:53:54.981  3509  3509 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
12-20 11:53:54.981  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
12-20 11:53:54.981  3509  3509 D WifiService: ACTIVITY_STATUS_STATIONARY 
12-20 11:53:54.981  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, 86, -85, 16, 1, 1,
12-20 11:53:54.981  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
12-20 11:53:54.981  3509  3838 I CAE     : display(ContextProvider.java:391) - Accuracy=[1], OperationMode=[0], ActivityType=[1], TimeStamp=[1482231234320]
12-20 11:53:54.981  3509  3841 D SContextService: updateSContext() : event = Activity Tracker
,12-20 11:53:54.981  3509  3850 D InputReader: Input event(4): value=1 when=143426257000
,12-20 11:53:54.981  3509  3850 D InputReader: Input event(4): value=1 when=143426257000
12-20 11:53:54.981  3509  3850 I InputReader: Touch event's action is 0x0 (deviceType=0) [pCnt=1, s=0.4 ] when=143426257000
12-20 11:53:54.981  3509  3850 D InputReader: lastThreadEndTime = 142447304897, currentThreadStartTime = 142447308666, diff = 0
,12-20 11:53:54.981  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x4, toolType: 1
12-20 11:53:54.981  3509  3849 I InputDispatcher: Delivering touch to (4328): action: 0x0, toolType: 1
12-20 11:53:54.981  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x0, toolType: 1
12-20 11:53:54.981  4328  4328 D ViewRootImpl: ViewPostImeInputStage processPointer 0
,12-20 11:53:54.991  3509  4092 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3509  pkgName : com.sec.android.app.launcher@1
,12-20 11:53:55.021  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:53:55.021  3960  3960 V PanelView: touch re-enable
,12-20 11:53:55.041  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:53:55.051  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=1, mIsPageMoving=true
,12-20 11:53:55.161  3509  3850 D InputReader: Input event(4): value=0 when=143600295000
12-20 11:53:55.161  3509  3850 D InputReader: Input event(4): value=0 when=143600295000
12-20 11:53:55.161  3509  3850 I InputReader: Touch event's action is 0x1 (deviceType=0) [pCnt=1, s=] when=143600295000
12-20 11:53:55.161  3509  3849 I InputDispatcher: Delivering touch to (4328): action: 0x1, toolType: 1
12-20 11:53:55.161  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x1, toolType: 1
,12-20 11:53:55.161  4328  4328 D ViewRootImpl: ViewPostImeInputStage processPointer 1
12-20 11:53:55.161  3509  6576 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
12-20 11:53:55.161  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:53:55.161  3509  6576 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
12-20 11:53:55.161  3509  3531 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3509  tag : com.sec.android.app.launcher@1
,12-20 11:53:55.161  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:53:55.521  8617  8673 I ReschedulableTimer: [#CMH#] ReschedulableTimer started 
,12-20 11:53:56.281  3509  3509 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:53:57.171  4328  4328 D capture : canCapture isWorkspaceLocked() = false isVisible : false
12-20 11:53:57.171  4328  4328 D capture : canCapture mWorkspace.getState()() = NORMAL isTouchActive : false isPageMoving : false
,12-20 11:53:57.511  3175  3651 I audio_hw_primary: do_out_standby +
,12-20 11:53:57.521  3175  3651 D audio_hw_primary: output_devices devices:0
12-20 11:53:57.521  3175  3651 D audio_hw_primary: output_devices devices:0
12-20 11:53:57.521  3175  3651 V audio_hw_primary: select_devices output_scenario:-1 input_scenario:-1 out_snd_device 0x0 in_snd_device:0x0
12-20 11:53:57.521  3175  3651 I audio_hw_primary: set_spk_rx_mute mute(1), rx val=0
12-20 11:53:57.521  3175  3651 I audio_route: 
12-20 11:53:57.521  3175  3651 I audio_route: > audio_route_reset :
,12-20 11:53:57.521  3175  3651 I audio_route: 
12-20 11:53:57.521  3175  3651 I audio_route: > audio_route_update_mixer : +
,12-20 11:53:57.561  3175  3651 I audio_route: > audio_route_update_mixer : changed(2) -
,12-20 11:53:57.561  3175  3651 I audio_hw_primary: select_devices - 
12-20 11:53:57.561  3175  3651 I audio_hw_primary: do_out_standby -
,12-20 11:53:59.621  3509  3531 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-20 11:53:59.621  3509  3531 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:53:59.621  3509  3531 D BatteryService: online:4, current avg:116, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:97
12-20 11:53:59.621  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:53:59.621  3509  3509 I MotionRecognitionService: Plugged
12-20 11:53:59.621  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:53:59.621  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:53:59.621  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:53:59.621  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:53:59.621  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-20 11:53:59.631  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:53:59.631  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:53:59.641  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:53:59.641  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:53:59.651  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:53:59.651  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:53:59.651  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:53:59.671  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:53:59.991  3509  3836 V AlarmManager: Expired Alarm result :8
,12-20 11:53:59.991  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-20 11:53:59.991  3960  3960 D KeyguardUpdateMonitor: handleTimeUpdate
,12-20 11:54:00.011  3960  3960 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-20 11:54:00.101  3960  3960 D DateView: received broadcast android.intent.action.TIME_TICK
,12-20 11:54:00.131  8428  8428 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-20 11:54:00.131  8428  8428 D [WeatherWidget(1240)]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-20 11:54:00.131  8428  8428 D [WeatherWidget(1240)]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-20 11:54:00.141  8428  8428 D [WeatherWidget(1240)]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,12-20 11:54:00.141  8428  8428 D [WeatherWidget(1240)]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A000F9D574DD3C1B95D41EAB42ECFF02F3D72C391A0A68B1B0C567090769101B3139122E72F130C4410562206878681E44]}
,12-20 11:54:00.141  8428  8428 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-20 11:54:03.511  3509  6576 D SSRM:n  : SIOP:: AP = 310, PST = 311 (W:14), CP = 267, CUR = 116, LCD = 107
,12-20 11:54:03.521  3509  4333 D WifiService: startScan by pid=4607, uid=10021
,12-20 11:54:03.521  3509  3881 I WifiScanController: location is disabled
,12-20 11:54:03.521  3509  3881 D WifiStateMachine: CMD_START_SCAN : scanLog.mLast - 1482231243538, scanLog.mStartTimeForBigdata - 1482231133491
,12-20 11:54:03.531  4152  4152 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,12-20 11:54:03.531  4152  4152 I wpa_supplicant: P2P: Current p2p state = IDLE
,12-20 11:54:03.621  4152  4152 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,12-20 11:54:04.481  3167  3639 D Netd    : Iface wlan0 link up
12-20 11:54:04.481  4152  4152 I wpa_supplicant: nl80211: Received scan results (14 BSSes)
,12-20 11:54:04.481  3509  3599 D Tethering: interfaceLinkStateChanged wlan0, true
12-20 11:54:04.481  3509  3599 D Tethering: interfaceStatusChanged wlan0, true
,12-20 11:54:04.481  5298  5308 D PdnController: Interface Changed wlan0 link up
,12-20 11:54:04.491  3509  3880 D WifiP2pService: InactiveState{ what=147461 }
,12-20 11:54:04.491  3509  3880 D WifiP2pService: P2pEnabledState{ what=147461 }
,12-20 11:54:04.491  3509  3880 D WifiP2pService: DefaultState{ what=147461 }
,12-20 11:54:04.541  3509  3509 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,12-20 11:54:04.561  3509  3593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81df213 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{72a2686 3960:com.android.systemui/u0a65}
,12-20 11:54:04.671  3509  6631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-20 11:54:08.541  3509  3593 I ActivityManager: Waited long enough for: ServiceRecord{81a1a2 u0 com.sec.android.daemonapp/.appservice.WeatherService}
,12-20 11:54:09.661  3509  4342 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-20 11:54:09.671  3509  4342 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4349, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:54:09.671  3509  4342 D BatteryService: online:4, current avg:137, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:137
12-20 11:54:09.671  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:54:09.671  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:54:09.671  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:54:09.671  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:54:09.671  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:54:09.681  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:54:09.681  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-20 11:54:09.681  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:54:09.681  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:54:09.691  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:54:09.701  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:54:09.701  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:54:09.701  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:54:09.711  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:54:09.731  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:54:12.071  3509  3836 V AlarmManager: Expired Alarm result :4
,12-20 11:54:12.081  3509  3593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{53d434e u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6fe7727 4355:com.google.android.gms.persistent/u0a21}
,12-20 11:54:12.111  9610  9610 E Zygote  : v2
,12-20 11:54:12.111  9610  9610 I libpersona: KNOX_SDCARD checking this for 1000
12-20 11:54:12.111  9610  9610 I libpersona: KNOX_SDCARD not a persona
,12-20 11:54:12.121  9610  9610 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,12-20 11:54:12.121  3509  3836 I ActivityManager: Start proc 9610:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
12-20 11:54:12.121  9610  9610 E Zygote  : accessInfo : 0
,12-20 11:54:12.131  3509  4334 V AlarmManager:  remove PendingIntent] PendingIntent{1eb9c6f: PendingIntentRecord{34ce2ab com.google.android.gms broadcastIntent}}
,12-20 11:54:12.161  9610  9610 D TimaKeyStoreProvider: TimaSignature is unavailable
12-20 11:54:12.161  9610  9610 D ActivityThread: Added TimaKeyStore provider
,12-20 11:54:12.191  9610  9610 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,12-20 11:54:12.191  9610  9610 D RelationGraph: garbageCollect()
,12-20 11:54:12.201  9610  9610 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package com.mobeam.barcodeService
,12-20 11:54:12.201  3509  3530 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,12-20 11:54:12.201  9610  9610 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-20 11:54:12.201  9610  9610 D ResourcesManager: For user 0 new overlays fetched Null
,12-20 11:54:12.211  9610  9610 I InjectionManager: Inside getClassLibPath caller 
,12-20 11:54:12.221  4607  9622 D UdcContextInitService: registered all accounts: true
,12-20 11:54:12.221  9610  9610 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm64
12-20 11:54:12.231  9610  9610 D InjectionManager: InjectionManager
12-20 11:54:12.231  9610  9610 D InjectionManager: fillFeatureStoreMap com.mobeam.barcodeService
,12-20 11:54:12.231  9610  9610 I InjectionManager: Constructor com.mobeam.barcodeService, Feature store :{}
12-20 11:54:12.231  9610  9610 I InjectionManager: featureStore :{}
,12-20 11:54:12.321  3509  4977 V AlarmManager:  remove PendingIntent] PendingIntent{bae465a: PendingIntentRecord{34ce2ab com.google.android.gms broadcastIntent}}
,12-20 11:54:12.641  4355  9626 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,12-20 11:54:12.641  4355  9626 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,12-20 11:54:12.961  4355  9626 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-20 11:54:12.961  4355  9626 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,12-20 11:54:12.961  3167  3642 D EnterpriseController: netId is 0
12-20 11:54:12.961  3167  3642 D Netd    : getNetworkForDns: using netid 502 for uid 10021
,12-20 11:54:13.031  4355  9626 I qtaguid : Tagging socket 64 with tag 3000120100000000{805310977,0} uid -1, pid: 4355, getuid(): 10021
,12-20 11:54:13.071  4355  9626 I qtaguid : Tagging socket 68 with tag 3000120100000000{805310977,0} uid -1, pid: 4355, getuid(): 10021
,12-20 11:54:13.341  4355  9626 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-20 11:54:13.341  4355  9626 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-20 11:54:13.341  4355  9626 I qtaguid : Tagging socket 64 with tag 3000120100000000{805310977,0} uid -1, pid: 4355, getuid(): 10021
,12-20 11:54:13.531  3509  6576 D SSRM:n  : SIOP:: AP = 310, PST = 310 (W:14), CP = 265, CUR = 137, LCD = 107
,12-20 11:54:13.661  4355  4364 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@eeedad5)
,12-20 11:54:13.661  4355  9626 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-20 11:54:13.661  4355  9626 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-20 11:54:13.671  4355  9626 I qtaguid : Tagging socket 64 with tag 3000120100000000{805310977,0} uid -1, pid: 4355, getuid(): 10021
,12-20 11:54:14.961  4355  9626 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-20 11:54:14.961  4355  9626 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-20 11:54:14.961  4355  9626 I qtaguid : Tagging socket 64 with tag 3000120100000000{805310977,0} uid -1, pid: 4355, getuid(): 10021
,12-20 11:54:15.091  4355  9626 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-20 11:54:15.091  4355  9626 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-20 11:54:15.091  4355  9626 I qtaguid : Tagging socket 64 with tag 3000120100000000{805310977,0} uid -1, pid: 4355, getuid(): 10021
,12-20 11:54:15.221  4355  9626 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-20 11:54:15.221  4355  9626 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-20 11:54:15.221  4355  9626 I qtaguid : Tagging socket 64 with tag 3000120100000000{805310977,0} uid -1, pid: 4355, getuid(): 10021
,12-20 11:54:15.401  3509  4333 V AlarmManager:  remove PendingIntent] PendingIntent{6cb2980: PendingIntentRecord{34ce2ab com.google.android.gms broadcastIntent}}
,12-20 11:54:15.411  3509  4180 E Watchdog: !@Sync 5 [12-20 11:54:15.421]
,12-20 11:54:18.991  3509  3619 D PowerManagerService: [s] UserActivityState : 1 -> 2
12-20 11:54:18.991  3509  3619 D PowerManagerService: mDisplayReady: false
12-20 11:54:18.991  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:18.991  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:54:18.991  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:54:18.991  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:54:18.991  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:54:18.991  3509  3619 D PowerManagerService: mDisplayReady: true
,12-20 11:54:18.991  3509  3927 D lights  : lcd : 104 +
,12-20 11:54:19.001  3509  3927 D lights  : lcd : 104 -
,12-20 11:54:19.001  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:19.001  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,12-20 11:54:19.001  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:54:19.001  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:54:19.011  3509  3927 D lights  : lcd : 96 +
,12-20 11:54:19.011  3509  3927 D lights  : lcd : 96 -
,12-20 11:54:19.011  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
,12-20 11:54:19.021  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:54:19.021  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
,12-20 11:54:19.021  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:54:19.031  3509  3927 D lights  : lcd : 88 +
,12-20 11:54:19.031  3509  3927 D lights  : lcd : 88 -
,12-20 11:54:19.031  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:19.031  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,12-20 11:54:19.031  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:54:19.031  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:54:19.041  3509  3927 D lights  : lcd : 79 +
,12-20 11:54:19.051  3509  3927 D lights  : lcd : 79 -
,12-20 11:54:19.051  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:19.051  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:54:19.051  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
,12-20 11:54:19.051  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:54:19.061  3509  3927 D lights  : lcd : 71 +
,12-20 11:54:19.061  3509  3927 D lights  : lcd : 71 -
,12-20 11:54:19.061  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:19.061  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:54:19.061  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
,12-20 11:54:19.061  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:54:19.081  3509  3927 D lights  : lcd : 63 +
,12-20 11:54:19.081  3509  3927 D lights  : lcd : 63 -
,12-20 11:54:19.081  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:19.081  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,12-20 11:54:19.081  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:54:19.081  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:54:19.091  3509  3927 D lights  : lcd : 57 +
,12-20 11:54:19.091  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:19.091  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:54:19.091  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:54:19.091  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:54:19.101  3509  3927 D lights  : lcd : 57 -
,12-20 11:54:19.101  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:19.101  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,12-20 11:54:19.101  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:54:19.101  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:54:19.731  3509  4485 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-20 11:54:19.731  3509  4485 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:54:19.731  3509  4485 D BatteryService: online:4, current avg:136, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:206
12-20 11:54:19.731  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:54:19.731  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:54:19.731  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:54:19.731  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,12-20 11:54:19.731  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:54:19.741  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:54:19.741  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-20 11:54:19.741  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:54:19.741  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:54:19.761  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:54:19.771  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:54:19.771  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
12-20 11:54:19.771  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:54:19.781  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:54:19.781  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:54:20.061  3509  3850 D InputReader: Input event(4): value=1 when=168498730000
,12-20 11:54:20.061  3509  3850 D InputReader: Input event(4): value=1 when=168498730000
12-20 11:54:20.061  3509  3850 I InputReader: Touch event's action is 0x0 (deviceType=0) [pCnt=1, s=0.5 ] when=168498730000
12-20 11:54:20.061  3509  3850 D InputReader: lastThreadEndTime = 163851974613, currentThreadStartTime = 163851981036, diff = 0
12-20 11:54:20.061  3509  3849 D PowerManagerService: [s] UserActivityState : 2 -> 1
12-20 11:54:20.061  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x4, toolType: 1
12-20 11:54:20.061  3509  3849 D PowerManagerService: mDisplayReady: false
12-20 11:54:20.061  3509  3849 I InputDispatcher: Delivering touch to (4328): action: 0x0, toolType: 1
12-20 11:54:20.061  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x0, toolType: 1
12-20 11:54:20.061  4328  4328 D ViewRootImpl: ViewPostImeInputStage processPointer 0
12-20 11:54:20.061  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:20.061  3509  3927 D lights  : lcd : 107 +
,12-20 11:54:20.061  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:54:20.061  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 107 -> 107
12-20 11:54:20.061  3509  3619 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
12-20 11:54:20.061  3509  3619 D DisplayPowerController: Tracking Direct to etc : 107
12-20 11:54:20.061  3509  3619 D DisplayPowerController: Animating brightness: target=107, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:54:20.061  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:20.061  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:54:20.061  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 107 -> 107
12-20 11:54:20.061  3509  3619 D DisplayPowerController: Animating brightness: target=107, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:54:20.061  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:54:20.061  3509  3619 D PowerManagerService: mDisplayReady: true
,12-20 11:54:20.061  3509  4487 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3509  pkgName : com.sec.android.app.launcher@1
,12-20 11:54:20.061  3509  3927 D lights  : lcd : 107 -
12-20 11:54:20.061  3509  3927 D DisplayPowerState: Tracking!!: 107
12-20 11:54:20.061  3509  3927 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
,12-20 11:54:20.061  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:20.061  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:54:20.061  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 107 -> 107
12-20 11:54:20.061  3509  3619 D DisplayPowerController: Animating brightness: target=107, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:54:20.091  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:54:20.101  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:54:20.121  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:54:20.141  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=2, mIsPageMoving=true
,12-20 11:54:20.151  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=1, mIsPageMoving=true
,12-20 11:54:20.531  3509  3850 D InputReader: Input event(4): value=0 when=168974398000
12-20 11:54:20.531  3509  3850 D InputReader: Input event(4): value=0 when=168974398000
12-20 11:54:20.531  3509  3850 I InputReader: Touch event's action is 0x1 (deviceType=0) [pCnt=1, s=] when=168974398000
12-20 11:54:20.531  3509  3849 I InputDispatcher: Delivering touch to (4328): action: 0x1, toolType: 1
12-20 11:54:20.531  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x1, toolType: 1
,12-20 11:54:20.531  4328  4328 D ViewRootImpl: ViewPostImeInputStage processPointer 1
12-20 11:54:20.531  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
12-20 11:54:20.531  3509  3531 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3509  tag : com.sec.android.app.launcher@1
,12-20 11:54:20.531  3509  6576 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
12-20 11:54:20.531  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:54:21.431  3509  3509 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:54:23.571  3509  6576 D SSRM:n  : SIOP:: AP = 310, PST = 310 (W:14), CP = 264, CUR = 136, LCD = 107
,12-20 11:54:24.671  3509  6631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-20 11:54:29.611  3509  3836 V AlarmManager: Expired Alarm result :4
,12-20 11:54:29.781  3509  4486 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-20 11:54:29.781  3509  4486 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4350, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:54:29.781  3509  4486 D BatteryService: online:4, current avg:144, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:130
12-20 11:54:29.791  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:54:29.791  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:54:29.791  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:54:29.791  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:54:29.791  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:54:29.801  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:54:29.801  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-20 11:54:29.801  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
12-20 11:54:29.801  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:54:29.811  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:54:29.821  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:54:29.821  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:54:29.831  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:54:29.831  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:54:29.841  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:54:32.601  3509  6577 W ResourcesManager: getTopLevelResources: /system/priv-app/TouchWizHome_2016/TouchWizHome_2016.apk / 1.0 running in null rsrc of package com.sec.android.app.launcher
,12-20 11:54:32.631  9646  9646 E Zygote  : v2
12-20 11:54:32.631  9646  9646 I libpersona: KNOX_SDCARD checking this for 1000
12-20 11:54:32.631  9646  9646 I libpersona: KNOX_SDCARD not a persona
,12-20 11:54:32.631  9646  9646 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,12-20 11:54:32.641  9646  9646 E Zygote  : accessInfo : 0
,12-20 11:54:32.641  3509  6577 I ActivityManager: Start proc 9646:com.samsung.android.sm.provider/1000 for content provider com.samsung.android.sm.provider/com.samsung.android.sm.database.lowpowercontext.LowpowerContextProvider
,12-20 11:54:32.671  9646  9646 D TimaKeyStoreProvider: TimaSignature is unavailable
12-20 11:54:32.671  9646  9646 D ActivityThread: Added TimaKeyStore provider
,12-20 11:54:32.701  9646  9646 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-20 11:54:32.701  9646  9646 D RelationGraph: garbageCollect()
,12-20 11:54:32.701  9646  9646 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManagerProvider/SmartManagerProvider.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.samsung.android.sm.provider
,12-20 11:54:32.701  3509  4334 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-20 11:54:32.701  9646  9646 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
12-20 11:54:32.701  9646  9646 D ResourcesManager: For user 0 new overlays fetched Null
,12-20 11:54:32.711  9646  9646 I InjectionManager: Inside getClassLibPath caller 
,12-20 11:54:32.721  9646  9646 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManagerProvider/lib/arm64
,12-20 11:54:32.741  9646  9646 D InjectionManager: InjectionManager
12-20 11:54:32.741  9646  9646 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm.provider
,12-20 11:54:32.741  9646  9646 I InjectionManager: Constructor com.samsung.android.sm.provider, Feature store :{}
12-20 11:54:32.741  9646  9646 I InjectionManager: featureStore :{}
,12-20 11:54:32.751  3509  3509 I ActivityManager: Killing 9071:com.google.android.apps.photos/u0a135 (adj 15): DHA:empty #33
,12-20 11:54:32.781  3509  4487 D ActivityManager: cleanUpApplicationRecord -- 9071
,12-20 11:54:32.781  3509  4487 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,12-20 11:54:32.851  3509  6577 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,12-20 11:54:32.861  3509  3593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{699b27b u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f4a898 9646:com.samsung.android.sm.provider/1000}
,12-20 11:54:32.901  3509  6577 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,12-20 11:54:32.921  3509  3593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6d0acd6 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f4a898 9646:com.samsung.android.sm.provider/1000}
,12-20 11:54:33.601  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 310 (W:14), CP = 263, CUR = 144, LCD = 107
,12-20 11:54:34.861  3509  3850 D InputReader: Input event(4): value=1 when=183292181000
12-20 11:54:34.861  3509  3850 D InputReader: Input event(4): value=1 when=183292181000
12-20 11:54:34.861  3509  3850 I InputReader: Touch event's action is 0x0 (deviceType=0) [pCnt=1, s=0.6 ] when=183292181000
12-20 11:54:34.861  3509  3850 D InputReader: lastThreadEndTime = 168974612840, currentThreadStartTime = 168974615917, diff = 0
12-20 11:54:34.861  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x4, toolType: 1
12-20 11:54:34.861  3509  3849 I InputDispatcher: Delivering touch to (4328): action: 0x0, toolType: 1
12-20 11:54:34.861  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x0, toolType: 1
12-20 11:54:34.861  4328  4328 D ViewRootImpl: ViewPostImeInputStage processPointer 0
,12-20 11:54:34.861  3509  4007 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3509  pkgName : com.sec.android.app.launcher@1
,12-20 11:54:34.871  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:54:34.891  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:54:34.911  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:54:34.921  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=2, mIsPageMoving=true
,12-20 11:54:34.941  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=1, mIsPageMoving=true
,12-20 11:54:35.151  3509  3850 D InputReader: Input event(4): value=0 when=183592511000
12-20 11:54:35.151  3509  3850 D InputReader: Input event(4): value=0 when=183592511000
12-20 11:54:35.151  3509  3850 I InputReader: Touch event's action is 0x1 (deviceType=0) [pCnt=1, s=] when=183592511000
12-20 11:54:35.151  3509  3849 I InputDispatcher: Delivering touch to (4328): action: 0x1, toolType: 1
12-20 11:54:35.151  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x1, toolType: 1
,12-20 11:54:35.151  4328  4328 D ViewRootImpl: ViewPostImeInputStage processPointer 1
12-20 11:54:35.151  3509  4092 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3509  tag : com.sec.android.app.launcher@1
,12-20 11:54:35.151  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:54:35.151  3509  6576 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
12-20 11:54:35.151  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:54:35.711  3509  3509 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:54:39.841  3509  4436 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-20 11:54:39.841  3509  4436 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:54:39.841  3509  4436 D BatteryService: online:4, current avg:142, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:146
12-20 11:54:39.841  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:54:39.851  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:54:39.851  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:54:39.851  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:54:39.851  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:54:39.861  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:54:39.861  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-20 11:54:39.861  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:54:39.861  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:54:39.871  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:54:39.881  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:54:39.881  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-20 11:54:39.881  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:54:39.891  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:54:39.911  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:54:43.631  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 308 (W:14), CP = 263, CUR = 142, LCD = 107
,12-20 11:54:44.681  3509  6631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-20 11:54:45.421  3509  4180 E Watchdog: !@Sync 6 [12-20 11:54:45.423]
,12-20 11:54:46.681  4383  4489 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-20 11:54:46.681  4383  4489 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-20 11:54:46.771  4383  4489 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 1Kb duration : 91ms lastUpdatedAfter : 126178ms
,12-20 11:54:49.901  3509  3530 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-20 11:54:49.901  3509  3530 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:54:49.901  3509  3530 D BatteryService: online:4, current avg:155, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:151
12-20 11:54:49.901  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:54:49.911  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:54:49.911  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:54:49.911  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:54:49.911  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:54:49.921  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:54:49.921  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-20 11:54:49.921  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
12-20 11:54:49.921  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:54:49.941  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:54:49.941  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:54:49.951  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:54:49.951  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:54:49.971  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:54:49.971  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:54:53.671  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 307 (W:14), CP = 262, CUR = 155, LCD = 107
,12-20 11:54:58.871  3509  3619 D PowerManagerService: [s] UserActivityState : 1 -> 2
12-20 11:54:58.871  3509  3619 D PowerManagerService: mDisplayReady: false
12-20 11:54:58.871  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:58.871  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:54:58.871  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:54:58.871  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:54:58.871  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:54:58.871  3509  3619 D PowerManagerService: mDisplayReady: true
,12-20 11:54:58.871  3509  3927 D lights  : lcd : 105 +
,12-20 11:54:58.871  3509  3927 D lights  : lcd : 105 -
,12-20 11:54:58.871  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:58.871  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:54:58.871  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:54:58.871  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:54:58.881  3509  3927 D lights  : lcd : 97 +
,12-20 11:54:58.881  3509  3927 D lights  : lcd : 97 -
,12-20 11:54:58.881  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:58.881  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:54:58.881  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:54:58.881  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:54:58.901  3509  3927 D lights  : lcd : 89 +
,12-20 11:54:58.901  3509  3927 D lights  : lcd : 89 -
,12-20 11:54:58.901  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:58.901  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,12-20 11:54:58.901  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:54:58.901  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:54:58.911  3509  3927 D lights  : lcd : 80 +
,12-20 11:54:58.921  3509  3927 D lights  : lcd : 80 -
,12-20 11:54:58.921  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:58.921  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:54:58.921  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:54:58.921  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:54:58.931  3509  3927 D lights  : lcd : 72 +
,12-20 11:54:58.931  3509  3927 D lights  : lcd : 72 -
,12-20 11:54:58.931  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:58.931  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:54:58.931  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
,12-20 11:54:58.931  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:54:58.951  3509  3927 D lights  : lcd : 64 +
,12-20 11:54:58.951  3509  3927 D lights  : lcd : 64 -
,12-20 11:54:58.951  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:58.951  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:54:58.951  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:54:58.951  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:54:58.961  3509  3927 D lights  : lcd : 57 +
,12-20 11:54:58.961  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:58.961  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:54:58.961  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:54:58.961  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:54:58.971  3509  3927 D lights  : lcd : 57 -
,12-20 11:54:58.971  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:54:58.971  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:54:58.971  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
,12-20 11:54:58.971  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:54:59.961  3509  4342 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-20 11:54:59.961  3509  4342 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:54:59.961  3509  4342 D BatteryService: online:4, current avg:157, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:162
12-20 11:54:59.961  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:54:59.961  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:54:59.961  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:54:59.961  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:54:59.961  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:54:59.971  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:54:59.971  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-20 11:54:59.971  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
12-20 11:54:59.971  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:54:59.981  3509  3836 V AlarmManager: Expired Alarm result :8
,12-20 11:54:59.981  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:54:59.991  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:55:00.001  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-20 11:55:00.001  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:55:00.011  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:55:00.031  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-20 11:55:00.031  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-20 11:55:00.031  3960  3960 D KeyguardUpdateMonitor: handleTimeUpdate
,12-20 11:55:00.031  3960  3960 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-20 11:55:00.081  3960  3960 D DateView: received broadcast android.intent.action.TIME_TICK
,12-20 11:55:00.101  8428  8428 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-20 11:55:00.101  8428  8428 D [WeatherWidget(1240)]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-20 11:55:00.101  8428  8428 D [WeatherWidget(1240)]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-20 11:55:00.101  8428  8428 D [WeatherWidget(1240)]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,12-20 11:55:00.111  8428  8428 D [WeatherWidget(1240)]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A000F9D574DD3C1B95D41EAB42ECFF02F3D72C391A0A68B1B0C567090769101B3139122E72F130C4410562206878681E44]}
,12-20 11:55:00.111  8428  8428 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-20 11:55:00.381  3509  3850 D InputReader: Input event(4): value=1 when=208821610000
12-20 11:55:00.381  3509  3850 D InputReader: Input event(4): value=1 when=208821610000
12-20 11:55:00.381  3509  3850 I InputReader: Touch event's action is 0x0 (deviceType=0) [pCnt=1, s=0.7 ] when=208821610000
12-20 11:55:00.381  3509  3850 D InputReader: lastThreadEndTime = 193852920745, currentThreadStartTime = 193852931130, diff = 0
12-20 11:55:00.381  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x4, toolType: 1
12-20 11:55:00.381  3509  3849 I InputDispatcher: Delivering touch to (4328): action: 0x0, toolType: 1
12-20 11:55:00.381  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x0, toolType: 1
12-20 11:55:00.381  3509  3849 D PowerManagerService: [s] UserActivityState : 2 -> 1
12-20 11:55:00.381  4328  4328 D ViewRootImpl: ViewPostImeInputStage processPointer 0
12-20 11:55:00.381  3509  3849 D PowerManagerService: mDisplayReady: false
,12-20 11:55:00.381  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:55:00.381  3509  3927 D lights  : lcd : 107 +
12-20 11:55:00.381  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:55:00.381  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 107 -> 107
12-20 11:55:00.381  3509  3619 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
12-20 11:55:00.381  3509  3619 D DisplayPowerController: Tracking Direct to etc : 107
12-20 11:55:00.381  3509  3619 D DisplayPowerController: Animating brightness: target=107, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:55:00.381  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:55:00.381  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:55:00.381  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 107 -> 107
12-20 11:55:00.381  3509  3619 D DisplayPowerController: Animating brightness: target=107, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:55:00.381  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:55:00.381  3509  3619 D PowerManagerService: mDisplayReady: true
12-20 11:55:00.381  3509  3791 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3509  pkgName : com.sec.android.app.launcher@1
,12-20 11:55:00.391  3509  3927 D lights  : lcd : 107 -
,12-20 11:55:00.391  3509  3927 D DisplayPowerState: Tracking!!: 107
12-20 11:55:00.391  3509  3927 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
12-20 11:55:00.391  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:55:00.391  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:55:00.391  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 107 -> 107
12-20 11:55:00.391  3509  3619 D DisplayPowerController: Animating brightness: target=107, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:55:00.411  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:55:00.421  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:55:00.441  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:55:00.461  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=1, mIsPageMoving=true
,12-20 11:55:00.521  3509  3850 D InputReader: Input event(4): value=0 when=208962944000
12-20 11:55:00.521  3509  3850 D InputReader: Input event(4): value=0 when=208962944000
12-20 11:55:00.521  3509  3850 I InputReader: Touch event's action is 0x1 (deviceType=0) [pCnt=1, s=] when=208962944000
12-20 11:55:00.521  3509  3849 I InputDispatcher: Delivering touch to (4328): action: 0x1, toolType: 1
12-20 11:55:00.521  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x1, toolType: 1
,12-20 11:55:00.521  4328  4328 D ViewRootImpl: ViewPostImeInputStage processPointer 1
12-20 11:55:00.521  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
12-20 11:55:00.521  3509  6576 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
12-20 11:55:00.521  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
12-20 11:55:00.521  3509  4342 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3509  tag : com.sec.android.app.launcher@1
,12-20 11:55:01.571  3509  3509 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:55:03.701  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 307 (W:14), CP = 261, CUR = 157, LCD = 107
,12-20 11:55:04.681  3509  6631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-20 11:55:10.021  3509  4002 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-20 11:55:10.021  3509  4002 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:55:10.021  3509  4002 D BatteryService: online:4, current avg:157, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:210
12-20 11:55:10.021  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:55:10.031  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:55:10.031  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:55:10.031  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:55:10.031  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:55:10.031  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:55:10.041  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-20 11:55:10.041  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:55:10.041  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:55:10.061  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:55:10.061  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:55:10.061  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:55:10.071  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:55:10.081  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:55:10.081  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:55:13.741  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 306 (W:14), CP = 261, CUR = 157, LCD = 107
,12-20 11:55:13.881  3509  3521 I art     : Background sticky concurrent mark sweep GC freed 158219(10MB) AllocSpace objects, 105(2MB) LOS objects, 27% free, 36MB/51MB, paused 3.191ms total 136.115ms
,12-20 11:55:15.421  3509  4180 E Watchdog: !@Sync 7 [12-20 11:55:15.424]
,12-20 11:55:20.081  3509  4333 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-20 11:55:20.081  3509  4333 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4352, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:55:20.081  3509  4333 D BatteryService: online:4, current avg:160, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:182
12-20 11:55:20.081  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:55:20.081  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:55:20.081  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:55:20.081  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:55:20.081  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:55:20.091  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:55:20.091  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-20 11:55:20.091  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
12-20 11:55:20.101  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:55:20.111  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:55:20.111  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:55:20.121  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:55:20.121  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:55:20.121  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:55:20.141  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:55:23.781  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 305 (W:14), CP = 260, CUR = 160, LCD = 107
,12-20 11:55:24.391  3509  3619 D PowerManagerService: [s] UserActivityState : 1 -> 2
12-20 11:55:24.391  3509  3619 D PowerManagerService: mDisplayReady: false
12-20 11:55:24.391  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:55:24.391  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:55:24.391  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:55:24.391  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:55:24.391  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:55:24.391  3509  3619 D PowerManagerService: mDisplayReady: true
,12-20 11:55:24.411  3509  3927 D lights  : lcd : 98 +
,12-20 11:55:24.411  3509  3927 D lights  : lcd : 98 -
,12-20 11:55:24.411  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:55:24.411  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:55:24.411  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:55:24.411  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:55:24.421  3509  3927 D lights  : lcd : 90 +
,12-20 11:55:24.421  3509  3927 D lights  : lcd : 90 -
,12-20 11:55:24.421  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
,12-20 11:55:24.421  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:55:24.421  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:55:24.421  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:55:24.431  3509  3927 D lights  : lcd : 82 +
,12-20 11:55:24.441  3509  3927 D lights  : lcd : 82 -
,12-20 11:55:24.441  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:55:24.441  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,12-20 11:55:24.441  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:55:24.441  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:55:24.451  3509  3927 D lights  : lcd : 74 +
,12-20 11:55:24.451  3509  3927 D lights  : lcd : 74 -
,12-20 11:55:24.451  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:55:24.451  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,12-20 11:55:24.451  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:55:24.451  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:55:24.471  3509  3927 D lights  : lcd : 65 +
,12-20 11:55:24.471  3509  3927 D lights  : lcd : 65 -
,12-20 11:55:24.471  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:55:24.481  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:55:24.481  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:55:24.481  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:55:24.481  3509  3927 D lights  : lcd : 57 +
,12-20 11:55:24.481  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:55:24.481  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:55:24.481  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
,12-20 11:55:24.481  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:55:24.491  3509  3927 D lights  : lcd : 57 -
12-20 11:55:24.491  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:55:24.491  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,12-20 11:55:24.491  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:55:24.491  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:55:24.671  3509  6631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-20 11:55:26.251  3509  3850 D InputReader: Input event(4): value=1 when=234689741000
12-20 11:55:26.251  3509  3850 D InputReader: Input event(4): value=1 when=234689741000
12-20 11:55:26.251  3509  3850 I InputReader: Touch event's action is 0x0 (deviceType=0) [pCnt=1, s=0.8 ] when=234689741000
12-20 11:55:26.251  3509  3850 D InputReader: lastThreadEndTime = 223854810147, currentThreadStartTime = 223854821762, diff = 0
12-20 11:55:26.251  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x4, toolType: 1
12-20 11:55:26.251  3509  3849 I InputDispatcher: Delivering touch to (4328): action: 0x0, toolType: 1
12-20 11:55:26.251  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x0, toolType: 1
12-20 11:55:26.251  3509  3849 D PowerManagerService: [s] UserActivityState : 2 -> 1
12-20 11:55:26.251  3509  3849 D PowerManagerService: mDisplayReady: false
,12-20 11:55:26.251  4328  4328 D ViewRootImpl: ViewPostImeInputStage processPointer 0
12-20 11:55:26.251  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:55:26.251  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:55:26.251  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 107 -> 107
12-20 11:55:26.251  3509  3927 D lights  : lcd : 107 +
12-20 11:55:26.251  3509  3619 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
12-20 11:55:26.251  3509  3619 D DisplayPowerController: Tracking Direct to etc : 107
12-20 11:55:26.251  3509  3619 D DisplayPowerController: Animating brightness: target=107, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:55:26.251  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:55:26.251  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:55:26.251  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 107 -> 107
12-20 11:55:26.251  3509  3619 D DisplayPowerController: Animating brightness: target=107, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:55:26.251  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:55:26.251  3509  3619 D PowerManagerService: mDisplayReady: true
,12-20 11:55:26.251  3509  4487 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3509  pkgName : com.sec.android.app.launcher@1
,12-20 11:55:26.251  3509  3927 D lights  : lcd : 107 -
,12-20 11:55:26.251  3509  3927 D DisplayPowerState: Tracking!!: 107
12-20 11:55:26.261  3509  3927 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
12-20 11:55:26.261  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:55:26.261  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:55:26.261  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 107 -> 107
12-20 11:55:26.261  3509  3619 D DisplayPowerController: Animating brightness: target=107, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:55:26.271  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:55:26.291  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:55:26.311  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:55:26.321  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:55:26.341  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=1, mIsPageMoving=true
,12-20 11:55:26.461  3509  3850 D InputReader: Input event(4): value=0 when=234904657000
12-20 11:55:26.461  3509  3850 D InputReader: Input event(4): value=0 when=234904657000
12-20 11:55:26.461  3509  3850 I InputReader: Touch event's action is 0x1 (deviceType=0) [pCnt=1, s=] when=234904657000
,12-20 11:55:26.461  3509  3849 I InputDispatcher: Delivering touch to (4328): action: 0x1, toolType: 1
12-20 11:55:26.461  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x1, toolType: 1
12-20 11:55:26.461  4328  4328 D ViewRootImpl: ViewPostImeInputStage processPointer 1
,12-20 11:55:26.461  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
12-20 11:55:26.461  3509  3530 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3509  tag : com.sec.android.app.launcher@1
12-20 11:55:26.461  3509  6576 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:55:26.461  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:55:27.301  3509  3509 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:55:30.131  3509  4486 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-20 11:55:30.131  3509  4486 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:55:30.131  3509  4486 D BatteryService: online:4, current avg:150, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:170
12-20 11:55:30.141  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:55:30.141  3509  3509 I MotionRecognitionService: Plugged
12-20 11:55:30.141  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:55:30.141  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:55:30.141  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:55:30.151  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:55:30.151  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-20 11:55:30.151  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:55:30.151  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:55:30.161  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:55:30.171  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:55:30.181  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:55:30.181  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:55:30.181  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:55:30.191  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:55:33.811  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 305 (W:14), CP = 260, CUR = 150, LCD = 107
,12-20 11:55:40.191  3509  4977 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-20 11:55:40.201  3509  4977 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:55:40.201  3509  4977 D BatteryService: online:4, current avg:151, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:113
12-20 11:55:40.201  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:55:40.201  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:55:40.201  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:55:40.201  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:55:40.201  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:55:40.211  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:55:40.211  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-20 11:55:40.211  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:55:40.211  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:55:40.241  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:55:40.241  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-20 11:55:40.241  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:55:40.251  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:55:40.251  5298  5298 D BatteryMonitor: new battery level: 100
12-20 11:55:40.251  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:55:43.841  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 304 (W:14), CP = 259, CUR = 151, LCD = 107
,12-20 11:55:44.671  3509  6631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-20 11:55:45.151  3509  3850 D InputReader: Input event(4): value=1 when=253582060000
12-20 11:55:45.151  3509  3850 D InputReader: Input event(4): value=1 when=253582060000
12-20 11:55:45.151  3509  3850 I InputReader: Touch event's action is 0x0 (deviceType=0) [pCnt=1, s=0.9 ] when=253582060000
12-20 11:55:45.151  3509  3850 D InputReader: lastThreadEndTime = 234904874369, currentThreadStartTime = 234904877754, diff = 0
,12-20 11:55:45.151  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x4, toolType: 1
12-20 11:55:45.151  3509  3849 I InputDispatcher: Delivering touch to (4328): action: 0x0, toolType: 1
12-20 11:55:45.151  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x0, toolType: 1
12-20 11:55:45.151  4328  4328 D ViewRootImpl: ViewPostImeInputStage processPointer 0
,12-20 11:55:45.151  3509  4434 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3509  pkgName : com.sec.android.app.launcher@1
,12-20 11:55:45.171  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:55:45.181  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:55:45.201  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:55:45.221  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:55:45.231  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=2, mIsPageMoving=true
,12-20 11:55:45.251  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=1, mIsPageMoving=true
,12-20 11:55:45.411  3509  4180 E Watchdog: !@Sync 8 [12-20 11:55:45.426]
,12-20 11:55:45.411  3509  3850 D InputReader: Input event(4): value=0 when=253856132000
12-20 11:55:45.411  3509  3850 D InputReader: Input event(4): value=0 when=253856132000
12-20 11:55:45.411  3509  3850 I InputReader: Touch event's action is 0x1 (deviceType=0) [pCnt=1, s=] when=253856132000
,12-20 11:55:45.411  3509  3849 I InputDispatcher: Delivering touch to (4328): action: 0x1, toolType: 1
12-20 11:55:45.411  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x1, toolType: 1
12-20 11:55:45.411  4328  4328 D ViewRootImpl: ViewPostImeInputStage processPointer 1
12-20 11:55:45.411  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
12-20 11:55:45.411  3509  6576 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
12-20 11:55:45.411  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
12-20 11:55:45.411  3509  4486 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3509  tag : com.sec.android.app.launcher@1
,12-20 11:55:46.021  3509  3509 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:55:46.881  4383  4489 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-20 11:55:46.881  4383  4489 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-20 11:55:50.251  3509  4977 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-20 11:55:50.251  3509  4977 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:55:50.251  3509  4977 D BatteryService: online:4, current avg:143, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:160
12-20 11:55:50.261  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:55:50.261  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:55:50.261  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:55:50.261  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:55:50.261  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:55:50.271  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:55:50.271  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-20 11:55:50.271  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:55:50.271  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:55:50.291  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:55:50.291  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:55:50.291  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:55:50.301  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:55:50.321  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-20 11:55:50.321  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:55:53.861  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 303 (W:14), CP = 259, CUR = 143, LCD = 107
,12-20 11:55:54.171  4355  5830 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,12-20 11:55:59.981  3509  3836 V AlarmManager: Expired Alarm result :8
,12-20 11:55:59.991  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-20 11:55:59.991  3960  3960 D KeyguardUpdateMonitor: handleTimeUpdate
,12-20 11:56:00.011  3960  3960 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-20 11:56:00.071  3960  3960 D DateView: received broadcast android.intent.action.TIME_TICK
,12-20 11:56:00.091  8428  8428 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-20 11:56:00.091  8428  8428 D [WeatherWidget(1240)]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-20 11:56:00.091  8428  8428 D [WeatherWidget(1240)]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-20 11:56:00.101  8428  8428 D [WeatherWidget(1240)]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,12-20 11:56:00.101  8428  8428 D [WeatherWidget(1240)]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A000F9D574DD3C1B95D41EAB42ECFF02F3D72C391A0A68B1B0C567090769101B3139122E72F130C4410562206878681E44]}
12-20 11:56:00.101  8428  8428 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-20 11:56:00.311  3509  4436 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-20 11:56:00.311  3509  4436 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:56:00.311  3509  4436 D BatteryService: online:4, current avg:143, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:166
12-20 11:56:00.311  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:56:00.321  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:56:00.321  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:56:00.321  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:56:00.321  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:56:00.321  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:56:00.331  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-20 11:56:00.331  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:56:00.331  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:56:00.351  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:56:00.351  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:56:00.351  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:56:00.361  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:56:00.371  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:56:00.381  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:56:03.901  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 302 (W:14), CP = 259, CUR = 143, LCD = 107
,12-20 11:56:04.671  3509  6631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-20 11:56:09.161  3509  3619 D PowerManagerService: [s] UserActivityState : 1 -> 2
12-20 11:56:09.161  3509  3619 D PowerManagerService: mDisplayReady: false
12-20 11:56:09.161  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:09.161  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:09.161  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:56:09.161  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:56:09.161  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:56:09.161  3509  3619 D PowerManagerService: mDisplayReady: true
,12-20 11:56:09.161  3509  3927 D lights  : lcd : 106 +
,12-20 11:56:09.161  3509  3927 D lights  : lcd : 106 -
,12-20 11:56:09.161  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:09.161  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:09.161  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:56:09.161  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:09.171  3509  3927 D lights  : lcd : 98 +
,12-20 11:56:09.171  3509  3927 D lights  : lcd : 98 -
,12-20 11:56:09.171  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:09.171  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:09.171  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:56:09.171  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:09.191  3509  3927 D lights  : lcd : 89 +
,12-20 11:56:09.191  3509  3927 D lights  : lcd : 89 -
,12-20 11:56:09.191  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:09.191  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,12-20 11:56:09.191  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:56:09.191  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:09.201  3509  3927 D lights  : lcd : 81 +
,12-20 11:56:09.211  3509  3927 D lights  : lcd : 81 -
,12-20 11:56:09.211  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:09.211  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:09.211  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:56:09.211  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:09.221  3509  3927 D lights  : lcd : 73 +
,12-20 11:56:09.221  3509  3927 D lights  : lcd : 73 -
,12-20 11:56:09.221  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:09.221  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:09.221  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
,12-20 11:56:09.221  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:09.231  3509  3927 D lights  : lcd : 64 +
,12-20 11:56:09.241  3509  3927 D lights  : lcd : 64 -
,12-20 11:56:09.241  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:09.241  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:09.241  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:56:09.241  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:09.251  3509  3927 D lights  : lcd : 57 +
,12-20 11:56:09.251  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:09.251  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:09.251  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:56:09.251  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:09.261  3509  3927 D lights  : lcd : 57 -
,12-20 11:56:09.261  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:09.261  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:09.261  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:56:09.261  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:10.371  3509  4486 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-20 11:56:10.371  3509  4486 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:56:10.371  3509  4486 D BatteryService: online:4, current avg:142, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:146
12-20 11:56:10.371  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:56:10.381  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:56:10.381  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:56:10.381  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:56:10.381  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:56:10.381  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:56:10.391  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-20 11:56:10.391  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
12-20 11:56:10.391  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:56:10.401  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:56:10.411  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:56:10.411  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:56:10.421  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:56:10.431  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:56:10.431  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:56:13.941  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 302 (W:14), CP = 259, CUR = 142, LCD = 57
,12-20 11:56:15.141  3509  3619 D PowerManagerService: [s] UserActivityState : 2 -> 4
12-20 11:56:15.141  3509  3619 I PowerManagerService: Nap time (uid 1000)...
12-20 11:56:15.141  3509  3619 D InputManager-JNI: setInteractive(false)
12-20 11:56:15.141  3509  3619 D PowerManagerService: handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
12-20 11:56:15.141  3509  3619 I PowerManagerService: !@[ps] Screen__Off - 2 :  dream(timeout) (2)
,12-20 11:56:15.141  3509  3619 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
12-20 11:56:15.141  3509  3619 D PowerManagerService: mDisplayReady: false
12-20 11:56:15.141  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=1
12-20 11:56:15.141  3509  3619 D ColorFade: prepare: mode=4
12-20 11:56:15.151  3960  3977 D KeyguardViewMediator: onStartedGoingToSleep(3)
12-20 11:56:15.151  3018  3018 I SurfaceFlinger: id=24 createSurf (1440x2560),2 flag=404, DolorFade
12-20 11:56:15.151  3509  3924 D NetworkPolicy: onScreenStateChanged, state: false, reason: 3
,12-20 11:56:15.161  3509  3619 D PowerManagerUtil: Excessive delay in ColorFade : createSurface: 10ms,
,12-20 11:56:15.161  3509  3619 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,12-20 11:56:15.161  7178  7178 D SamsungIME: IMPL finishInput
,12-20 11:56:15.171  7178  7178 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
,12-20 11:56:15.171  7178  7178 D SamsungIME: saveAndClear +
12-20 11:56:15.171  7178  7178 D SamsungIME: saveAndClear -
,12-20 11:56:15.171  7178  7178 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,12-20 11:56:15.181  3960  3977 E KeyguardViewMediator: lockAfterTimeout = 5000 policyTimeout = 0
,12-20 11:56:15.191  3960  3977 D KeyguardViewMediator: timeout : 5000
,12-20 11:56:15.191  3960  3977 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 3
12-20 11:56:15.191  3960  3977 D KeyguardViewMediator: notifyStartedGoingToSleep
12-20 11:56:15.191  3960  3960 V KeyguardFingerPrint: updateFingerprintListeningState(false)
,12-20 11:56:15.191  3960  3960 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
12-20 11:56:15.191  3960  3960 V KeyguardUpdateMonitor: stopListeningForFingerprint()
,12-20 11:56:15.191  3960  3960 D KeyguardViewMediator: handleNotifyStartedGoingToSleep
,12-20 11:56:15.211  3509  3619 D libEGL  : eglInitialize EGLDisplay = 0x7f9693e778
,12-20 11:56:15.211  3509  3619 D libEGL  : eglTerminate EGLDisplay = 0x7f9693e8e8
,12-20 11:56:15.221  3509  3619 D ColorFade: ColorFade is ready
,12-20 11:56:15.221  3509  3619 D DisplayPowerController: ColorFade: onAnimationStart
12-20 11:56:15.221  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:15.221  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 107 -> 107
,12-20 11:56:15.241  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:56:15.251  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:56:15.271  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:56:15.411  3509  4180 E Watchdog: !@Sync 9 [12-20 11:56:15.427]
,12-20 11:56:15.511  3509  3619 D DisplayPowerState: !@ [0] ColorFade entry
12-20 11:56:15.511  3509  3619 D PowerManagerService: [input device light] onColorFadeExit(false)
,12-20 11:56:15.511  3509  3619 D DisplayPowerController: ColorFade: onAnimationEnd
,12-20 11:56:15.521  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=1
12-20 11:56:15.521  3509  3927 D lights  : lcd : 0 +
12-20 11:56:15.521  3509  3619 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_* -> REPORTED_TO_POLICY_SCREEN_OFF.
,12-20 11:56:15.521  4328  4328 D Launcher: onPause, Launcher: 188281550
12-20 11:56:15.521  4328  4328 D Launcher.HomeView: onPause
12-20 11:56:15.521  4328  4328 D Launcher.Workspace: exitWidgetResizeMode. isClearResizeFrame is false
,12-20 11:56:15.531  3509  3927 D lights  : lcd : 0 -
,12-20 11:56:15.611  3509  3619 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@4158331, Service = Auto Rotation, used = 0
,12-20 11:56:15.611  3509  3619 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for AUTO_ROTATION
,12-20 11:56:15.621  3509  3619 V CAE     : stop(ContextProvider.java:155)
,12-20 11:56:15.621  3509  3619 V CAE     : clear(AutoRotationRunner.java:182)
12-20 11:56:15.621  4328  4328 V ActivityThread: updateVisibility : ActivityRecord{2719980 token=android.os.BinderProxy@72d1b85 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
12-20 11:56:15.621  4328  4328 D Launcher.HomeView: onStop
,12-20 11:56:15.621  4328  4328 D capture : ----destroy
12-20 11:56:15.621  3509  3619 V CAE     : disable(AutoRotationRunner.java:171)
12-20 11:56:15.621  3509  3619 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 7, 0, 0,
12-20 11:56:15.621  3509  3619 D SensorHubManager: SendSensorHubData: send data = -78, 7, 0, 0
12-20 11:56:15.621  3182  3222 D Sensorhubs: sendContextData: -78, 7, 0, 0
,12-20 11:56:15.631  3509  3619 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,12-20 11:56:15.631  3509  3619 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:56:15.641  3509  3619 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:56:15.641  3509  3619 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
12-20 11:56:15.641  3509  3619 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
,12-20 11:56:15.641  3509  3619 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
12-20 11:56:15.641  3509  3619 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER(1)
12-20 11:56:15.641  3509  3619 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@f989b9f, Service : AUTO_BRIGHTNESS(1)
,12-20 11:56:15.641  3509  3619 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
12-20 11:56:15.641  3509  3619 D SContextService: 	.unregisterCallback : 3, client=
12-20 11:56:15.641  3509  3619 D SContextService: ===== SContext Service List =====
12-20 11:56:15.641  3509  3619 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@f5ee4ec, Service : Auto Brightness
12-20 11:56:15.641  3509  3619 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@89c5f97, Service : Activity Tracker
12-20 11:56:15.641  3509  3619 D SContextManager:   .unregisterListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@8adcaff, service=Auto Rotation
12-20 11:56:15.641  3509  3619 V KeyguardServiceDelegate: onScreenTurnedOff()
12-20 11:56:15.641  3960  4430 D KeyguardViewMediator: notifyScreenTurnedOff
,12-20 11:56:15.651  3960  3960 D KeyguardViewMediator: handleNotifyScreenTurnedOff
12-20 11:56:15.651  3960  3960 D vol.SecVolumeDialog: onScreenTurnedOff()
12-20 11:56:15.651  3960  3960 D vol.SecVolumeDialog: dismissH reason: 4
12-20 11:56:15.651  3960  3960 D vol.SecVolumeDialog: dismissH : false
,12-20 11:56:15.651  3509  3619 D DisplayPowerController: mWindowManagerPolicy.screenTurnedOff(0)
,12-20 11:56:15.651  3509  3926 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@f5ee4ec, Service = Auto Brightness, used = 0
12-20 11:56:15.651  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
12-20 11:56:15.651  3509  3619 D PowerManagerUtil: fileWriteInt to /sys/class/tcon/tcon/auto_br, 0
12-20 11:56:15.651  3509  3926 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for AUTO_BRIGHTNESS
12-20 11:56:15.651  3509  3926 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : unregisterListenerRunnable
12-20 11:56:15.651  3509  3619 D PowerManagerUtil: fileWriteInt to /sys/class/backlight/panel/auto_brightness, 0
,12-20 11:56:15.651  3509  3595 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 com.android.server.policy.sec.SamsungPhoneWindowManager$22.run:4527 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:158 
12-20 11:56:15.651  3509  3926 V CAE     : stop(ContextProvider.java:155)
12-20 11:56:15.651  4748  4748 I AODService: onStartCommand : action : com.samsung.android.app.aodservice.intent.action.AOD_SCREEN_OFF
12-20 11:56:15.651  4748  4748 I AODService: onCreate cause: [12-20 11:51:46.639][AOD:true, NightClock:false]<com.samsung.android.app.aodservice.intent.action.AOD_SCREEN_ON> (when Screen on ...)
,12-20 11:56:15.651  3509  3926 V CAE     : clear(AutoBrightnessRunner.java:297)
,12-20 11:56:15.651  3509  3926 V CAE     : disable(AutoBrightnessRunner.java:286)
,12-20 11:56:15.661  3509  3619 D PowerManagerUtil: fileWriteInt to /sys/class/mdnie/mdnie/auto_brightness, 0
12-20 11:56:15.661  3509  3926 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 48, 0, 0,
,12-20 11:56:15.661  3509  3619 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
12-20 11:56:15.661  3509  3926 D SensorHubManager: SendSensorHubData: send data = -78, 48, 0, 0
,12-20 11:56:15.661  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
12-20 11:56:15.661  3182  7712 D Sensorhubs: sendContextData: -78, 48, 0, 0
12-20 11:56:15.661  3509  3619 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:15.661  3509  9703 D MISC PowerHAL: sysfs_write +: /sys/class/input/event0/device/enabled: 0
12-20 11:56:15.661  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=1
12-20 11:56:15.661  3509  9704 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 0
12-20 11:56:15.661  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
12-20 11:56:15.661  3509  9703 D MISC PowerHAL: sysfs_write -: /sys/class/input/event0/device/enabled: 0
12-20 11:56:15.661  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
12-20 11:56:15.661  3509  9704 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 0
12-20 11:56:15.661  3509  3619 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:56:15.661  3509  3626 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
12-20 11:56:15.661  3509  3626 D DisplayManagerService: !@display_state: ON -> OFF brightness: 0 -> 0
12-20 11:56:15.661  3509  3626 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
12-20 11:56:15.661  3509  3615 I DisplayManagerService: Display device changed state: "Wbudowany ekran", OFF
,12-20 11:56:15.661  3509  3615 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", OFF
12-20 11:56:15.661  3018  3018 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7fa9d43c00
12-20 11:56:15.661  3018  3018 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(0)
,12-20 11:56:15.691  3960  3960 D ImageWallpaper: onVisibilityChanged:false
,12-20 11:56:15.691  3509  3926 D CAE     : getFaultDetectionResult(AutoBrightnessRunner.java:311) - true
,12-20 11:56:15.691  3509  3926 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:56:15.691  3960  3960 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
12-20 11:56:15.691  3960  3960 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
12-20 11:56:15.691  3960  3960 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,12-20 11:56:15.691  6319  6319 E CocktailBarPositionManager: Window direction: 0
12-20 11:56:15.691  6319  6319 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-20 11:56:15.711  3509  3531 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
12-20 11:56:15.711  3509  3926 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:56:15.711  3509  4436 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
12-20 11:56:15.711  4748  4748 D ScoverManager: registerListener
12-20 11:56:15.711  3509  4007 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,12-20 11:56:15.711  3509  4002 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
12-20 11:56:15.711  3509  3926 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
12-20 11:56:15.711  3509  4002 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@35080ae, pid : 4748, uid : 10000, type : 1
12-20 11:56:15.711  3509  3926 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
,12-20 11:56:15.721  3509  3926 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,12-20 11:56:15.721  3509  3926 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER(1)
,12-20 11:56:15.721  3509  3926 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for AUTO_BRIGHTNESS
12-20 11:56:15.721  3509  3926 D SContextService: 	.unregisterCallback : 2, client=
12-20 11:56:15.721  3509  3926 D SContextService: ===== SContext Service List =====
12-20 11:56:15.721  3509  3926 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@89c5f97, Service : Activity Tracker
,12-20 11:56:15.721  3509  3926 D SContextManager:   .unregisterListener : listener = com.android.server.display.AutomaticBrightnessController$6@d74e31, service=Auto Brightness
12-20 11:56:15.721  3509  3926 D PowerManagerUtil: Excessive delay in SensorHubAutoBrightnessEnabled::unregisterListener done: 57ms
,12-20 11:56:15.721  3509  4434 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
12-20 11:56:15.721  4748  9705 D AODService: onCreate register mSContextListener : com.samsung.android.app.aodservice.AODService$7@de2fb91
,12-20 11:56:15.721  3509  3530 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-20 11:56:15.721  3509  4092 I Sensors : Light old sensor_state 0, new sensor_state : 512 en : 1
12-20 11:56:15.721  3509  3530 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 4, 0, 0, 0, 1, 2,
12-20 11:56:15.721  3509  3530 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 4, 0, 0, 0, 1, 2
,12-20 11:56:15.721  3182  3182 D Sensorhubs: sendContextData: -63, 23, 56, 4, 0, 0, 0, 1, 2
,12-20 11:56:15.721  4748  4748 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
12-20 11:56:15.721  4748  4748 D AODService: registerBatteryReceiver
,12-20 11:56:15.731  4748  4748 D BatteryController: saveBatteryData : level[100], status[5]
,12-20 11:56:15.731  4748  4748 D AODService: Cover coverOpen[true], isBlackListCover(type)[false]
,12-20 11:56:15.731  4748  4748 D AODService.ClockTimer: ClockTimer:start : true
12-20 11:56:15.731  3509  3530 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-20 11:56:15.731  3509  3530 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-20 11:56:15.731  3509  3530 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:56:15.731  3509  3530 V CAE     : start(ContextProvider.java:128)
12-20 11:56:15.731  4748  4748 D AODService.ClockTimer: observe start aod
12-20 11:56:15.731  4748  4748 D AODService.ClockTimer: notifyWakeUp
12-20 11:56:15.731  3509  3530 V CAE     : clear(DevicePhysicalContextMonitorRunner.java:497)
,12-20 11:56:15.731  3509  3530 V CAE     : enable(DevicePhysicalContextMonitorRunner.java:471)
,12-20 11:56:15.731  3509  3530 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 56, 0, 10, 56, 15,
12-20 11:56:15.731  3509  3530 D SensorHubManager: SendSensorHubData: send data = -79, 56, 0, 10, 56, 15
12-20 11:56:15.731  3182  3222 D Sensorhubs: sendContextData: -79, 56, 0, 10, 56, 15
,12-20 11:56:15.741  3509  3530 D CAE     : getFaultDetectionResult(DevicePhysicalContextMonitorRunner.java:521) - true
,12-20 11:56:15.741  3509  3530 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:56:15.741  4748  4748 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
,12-20 11:56:15.741  3509  4434 D SettingsProvider: isChangeAllowed() : name = aod_show_state
,12-20 11:56:15.741  3509  4434 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
12-20 11:56:15.741  3509  4434 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
12-20 11:56:15.741  3509  4434 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
12-20 11:56:15.741  3509  4434 D SettingsProvider: selectionArgs: false
12-20 11:56:15.741  3509  4434 D SettingsProvider: selectionArgs: 10000
,12-20 11:56:15.741  3509  4434 D SettingsProvider: ret = -1
,12-20 11:56:15.741  4748  4748 E SettingsUtils: setAODShowState  config = 1
12-20 11:56:15.741  4748  4748 D AlpmModeManager: setFirstStartALPM() initialize value
,12-20 11:56:15.751  4748  4748 D AODService: createWindow
,12-20 11:56:15.751  3509  3530 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:56:15.751  3509  3530 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,12-20 11:56:15.751  3509  3530 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
,12-20 11:56:15.751  4748  4748 I AODUpdatePositionController: initPosition : X[0], Y[87] Rect(-50, 0 - 50, 920)
,12-20 11:56:15.751  3509  3530 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
12-20 11:56:15.751  3509  3530 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER(1)
12-20 11:56:15.751  3509  3530 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6fe5061, Service : DEVICE_PHYSICAL_CONTEXT_MONITOR(1)
12-20 11:56:15.751  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:56:15.751  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:56:15.751  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:56:15.751  3509  3530 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-20 11:56:15.761  3509  3530 D SContextService: 	.registerCallback : 2, client=
12-20 11:56:15.761  3509  3530 D SContextService: ===== SContext Service List =====
12-20 11:56:15.761  3509  3530 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@89c5f97, Service : Activity Tracker
12-20 11:56:15.761  3509  3530 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@2cbf786, Service : Device Physical Context Monitor
,12-20 11:56:15.761  4748  9705 D SContextManager:   .registerListener : listener = com.samsung.android.app.aodservice.AODService$7@de2fb91, service=Device Physical Context Monitor
,12-20 11:56:15.761  3509  4441 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:56:15.761  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:56:15.761  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:56:15.761  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:56:15.761  3509  4441 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 1, 2, 88,
,12-20 11:56:15.761  3509  4441 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 1, 2, 88
12-20 11:56:15.761  3182  7712 D Sensorhubs: sendContextData: -63, 23, 56, 3, 1, 2, 88
,12-20 11:56:15.761  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,12-20 11:56:15.761  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:56:15.761  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,12-20 11:56:15.771  4748  4748 I DefaultClockView: composeDefaultClockView: Selected clock = 0
,12-20 11:56:15.771  3509  4441 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,12-20 11:56:15.771  3509  4441 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:56:15.771  3509  4342 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:56:15.771  3509  4342 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 2, 0, 3,
12-20 11:56:15.781  3509  4342 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 2, 0, 3
,12-20 11:56:15.781  3182  3182 D Sensorhubs: sendContextData: -63, 23, 56, 3, 2, 0, 3
,12-20 11:56:15.781  4748  4748 D BatteryMeterView: BatteryMeterView 
,12-20 11:56:15.781  3509  4342 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-20 11:56:15.781  3509  4342 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:56:15.781  3509  4002 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:56:15.781  3509  4002 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 3, 0, 60,
12-20 11:56:15.781  3509  4002 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 3, 0, 60
12-20 11:56:15.781  3182  3222 D Sensorhubs: sendContextData: -63, 23, 56, 3, 3, 0, 60
,12-20 11:56:15.791  3509  4002 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,12-20 11:56:15.791  3509  4002 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:56:15.791  3509  4487 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:56:15.791  3509  4487 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 4, 0, 1,
12-20 11:56:15.791  3509  4487 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 4, 0, 1
12-20 11:56:15.791  3182  7712 D Sensorhubs: sendContextData: -63, 23, 56, 3, 4, 0, 1
,12-20 11:56:15.791  3509  4487 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-20 11:56:15.791  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:56:15.791  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:56:15.791  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:56:15.801  3509  4487 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:56:15.801  3509  4334 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:56:15.801  3509  4334 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 4, 0, 0, 0, 110, 1,
12-20 11:56:15.801  3509  4334 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 4, 0, 0, 0, 110, 1
12-20 11:56:15.801  3182  3182 D Sensorhubs: sendContextData: -63, 23, 56, 4, 0, 0, 0, 110, 1
,12-20 11:56:15.801  4748  4748 D DefaultClockView: LocalTime Pattern : HH:mm
,12-20 11:56:15.801  4748  4748 I AODUpdatePositionController: updatePosition: start current clock, Current X[0] Current Y[87] NewPositionTimer[60]
,12-20 11:56:15.801  3509  4334 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-20 11:56:15.801  3509  4334 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-20 11:56:15.801  4748  4748 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 11:56 time02: null ampm: null
,12-20 11:56:15.801  3509  4977 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:56:15.811  3509  4977 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 4, 0, 0, 0, 17, 2,
12-20 11:56:15.811  3509  4977 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 4, 0, 0, 0, 17, 2
12-20 11:56:15.811  3182  3222 D Sensorhubs: sendContextData: -63, 23, 56, 4, 0, 0, 0, 17, 2
,12-20 11:56:15.811  3509  4977 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,12-20 11:56:15.811  3509  4977 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:56:15.811  4748  4748 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,12-20 11:56:15.821  4748  4748 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
12-20 11:56:15.821  4748  4748 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:wt., 20 gru 11:56
12-20 11:56:15.821  4748  4748 D DefaultClockView: show
,12-20 11:56:15.821  4748  4748 D ViewRootImpl: #1 mView = com.samsung.android.app.aodservice.nightclock.DefaultClockView{4a1f2bf V.E...... ......ID 0,0-0,0}
,12-20 11:56:15.831  3509  3626 D SurfaceControl: Excessive delay in setPowerMode(): 168ms
,12-20 11:56:15.831  3509  4487 D ISSUE_DEBUG: InputChannelName : b373874 AOD
12-20 11:56:15.831  3509  3626 D PowerManagerUtil: Excessive delay in !@display_state: OFF: 169ms
12-20 11:56:15.831  3509  3626 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 172ms
12-20 11:56:15.831  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=1
,12-20 11:56:15.831  3509  4487 D InputDispatcher: Focus left window: 4328
,12-20 11:56:15.831  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
12-20 11:56:15.831  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable
12-20 11:56:15.831  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
12-20 11:56:15.831  3509  4487 D InputDispatcher: Focus entered window: 4748
12-20 11:56:15.831  3509  3619 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:56:15.831  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable done
12-20 11:56:15.831  3509  3619 I PowerManagerService: [PWL] Off : 0s ago
12-20 11:56:15.831  3960  3960 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,12-20 11:56:15.831  3509  3619 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,12-20 11:56:15.831  3509  3615 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3509 uid:1000
,12-20 11:56:15.831  3509  3619 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
12-20 11:56:15.831  3509  3615 D PointerIcon: setMouseCustomIcon IconType is same.101
12-20 11:56:15.831  3509  3619 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AlwaysOnDisplay_EnsureWorkingTime' (uid=10000, pid=4748, ws=null) (elapsedTime=119)
12-20 11:56:15.831  3509  3924 D PersonaManagerService: onfinishedGoingToSleep why = 3
12-20 11:56:15.831  3509  3619 I PowerManagerService: [PWL]   PowerManagerService.Display: ref count=2
,12-20 11:56:15.831  3960  3979 D KeyguardViewMediator: onFinishedGoingToSleep(3)
12-20 11:56:15.831  3509  3619 I PowerManagerService: [PWL]     mUserActivitySummary : 0x4
12-20 11:56:15.831  3960  3979 D KeyguardViewMediator: notifyFinishedGoingToSleep
12-20 11:56:15.831  3509  3595 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{b373874 u0 d0 AOD}
12-20 11:56:15.831  3960  3960 D KeyguardViewMediator: handleNotifyFinishedGoingToSleep
12-20 11:56:15.831  3509  3619 I PowerManagerService: [PWL]     mDisplayReady : false
12-20 11:56:15.831  3509  3631 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
,12-20 11:56:15.831  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=1
12-20 11:56:15.831  3960  3960 D KeyguardEffectViewController: onScreenTurnedOff
12-20 11:56:15.831  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
12-20 11:56:15.831  3960  3960 D KeyguardEffectViewController: ## mBackgroundView.onPause()
12-20 11:56:15.831  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
12-20 11:56:15.831  3960  3960 D KeyguardEffectViewLayered: onPause()
,12-20 11:56:15.831  3509  3619 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:56:15.831  3960  3960 D SecKeyguardStatusView: onFinishedGoingToSleep() why=3
12-20 11:56:15.831  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:56:15.831  3960  3960 V KeyguardFingerPrint: updateFingerprintListeningState(false)
12-20 11:56:15.831  3509  3619 D PowerManagerService: mDisplayReady: true
12-20 11:56:15.831  3509  3619 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-20 11:56:15.841  3960  3960 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
12-20 11:56:15.831  3509  3619 D PowerManagerService: handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
12-20 11:56:15.841  3960  3960 V KeyguardUpdateMonitor: stopListeningForFingerprint()
12-20 11:56:15.831  3509  3619 D PowerManagerService: handleSandman : startDream(true)
12-20 11:56:15.831  3509  3619 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
12-20 11:56:15.831  3509  3619 I PowerManagerService: Sleeping (uid 1000)...
,12-20 11:56:15.831  3509  3619 D PowerManagerService: [s] UserActivityState : 4 -> 0
12-20 11:56:15.831  3509  3619 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,12-20 11:56:15.851  3509  3509 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3509) 
,12-20 11:56:15.861  3509  3509 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=5) set On
,12-20 11:56:15.861  3509  3509 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
12-20 11:56:15.861  3509  3625 D LightsService: [SvcLED]  onSensorChanged::light value = 24
12-20 11:56:15.861  3509  3509 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
12-20 11:56:15.861  3509  3509 D BatteryService: turn on LED for fully charged
12-20 11:56:15.861  3509  3625 D SensorManager: unregisterListener ::   
12-20 11:56:15.861  3509  3625 I LightsService: fileWriteInt : /sys/class/sec/led/led_lowpower  value : 0
,12-20 11:56:15.861  3509  3625 D lights  : led_pattern : 5 +
,12-20 11:56:15.861  3509  3625 D lights  : led_pattern : 5 -
,12-20 11:56:15.861  3509  3625 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
12-20 11:56:15.861  3509  3625 V AlarmManager:  remove PendingIntent] PendingIntent{4ecf248: PendingIntentRecord{45ac606 android broadcastIntent}}
,12-20 11:56:15.891  8550  8578 D BadgeProvider: query, [selection] : null
,12-20 11:56:15.901  3509  3509 I CAE     : handleMessage(CaPowerManager.java:182) - AP_SLEEP
,12-20 11:56:15.901  3509  3509 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_SLEEP
,12-20 11:56:15.911  3509  3509 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -46, 0,
12-20 11:56:15.911  3509  3509 D SensorHubManager: SendSensorHubData: send data = -76, 13, -46, 0
12-20 11:56:15.911  3182  7712 D Sensorhubs: sendContextData: -76, 13, -46, 0
,12-20 11:56:15.911  3509  3509 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 10, 56, 15,
12-20 11:56:15.911  3509  3509 D SensorHubManager: SendSensorHubData: send data = -63, 14, 10, 56, 15
,12-20 11:56:15.911  3182  3182 D Sensorhubs: sendContextData: -63, 14, 10, 56, 15
12-20 11:56:15.911  4748  4748 D AODMissedEventController: [com.android.contacts] badgeCount : 0, [com.android.mms] badgeCount : 0
,12-20 11:56:15.911  4748  4748 I AODService.ClockTimer: startAlarm : TICK
,12-20 11:56:15.911  3509  3791 V AlarmManager: Add whitelist package alarm :PendingIntent{76e919d: PendingIntentRecord{cb26099 com.samsung.android.app.aodservice broadcastIntent}}
,12-20 11:56:15.911  4748  4748 I AODService.ClockTimer: startAlarm : SLEEP
,12-20 11:56:15.911  4748  4748 V AODService.ClockTimer: AOD Trigger: next AOD WAKEUP time is 9:0
,12-20 11:56:15.911  4748  4748 D AODService.ClockTimer: startAlarm is canceled. triggerAtMillis = -1, currentTime = 1482231375930
12-20 11:56:15.911  4748  4748 I AODService.ClockTimer: stopAlarm : WAKEUP
,12-20 11:56:15.911  3509  4334 V AlarmManager:  remove PendingIntent] PendingIntent{6e00612: PendingIntentRecord{d5689d1 com.samsung.android.app.aodservice broadcastIntent}}
,12-20 11:56:15.921  4748  4748 D BatteryController: saveBatteryData : level[100], status[5]
12-20 11:56:15.921  3509  3509 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,12-20 11:56:15.921  3509  3815 I Sensors : #>LightSensor r=13 g=10 b=8 c=30 atime=245 again=64 lux=24
,12-20 11:56:15.921  3018  3018 I SurfaceFlinger: id=25 createSurf (1x1),1 flag=404, BOD
,12-20 11:56:15.921  3509  3842 D MotionRecognitionService: Screen off setAccIntStatus 
12-20 11:56:15.921  3509  3842 E MotionRecognitionService:  handler : SCREEN_OFF end 
,12-20 11:56:15.931  3509  3530 V WindowOrientationListener: setCurrentAppOrientation :5
,12-20 11:56:15.931  3509  3530 V WindowManager: rotationForOrientationLw(orient=5, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,12-20 11:56:15.951  3509  3593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{32841e3 u-1 com.samsung.settings.action.directaccess.CLOSE_DIALOG qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c83b918 8954:com.samsung.android.SettingsReceiver/1000}
,12-20 11:56:15.951  4748  7100 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,12-20 11:56:15.951  3509  4485 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,12-20 11:56:15.961  3509  3509 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_OFF
,12-20 11:56:15.971  3509  4334 W InputMethodManagerService: Starting input on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@b7b659c (uid=10069 pid=4328)
,12-20 11:56:15.971  7178  7178 D SamsungIME: IMPL finishInput
12-20 11:56:15.971  7178  7178 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
12-20 11:56:15.971  7178  7178 D SamsungIME: saveAndClear +
12-20 11:56:15.971  7178  7178 D SamsungIME: saveAndClear -
,12-20 11:56:15.971  7178  7178 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,12-20 11:56:15.971  3509  3615 V WindowAnimator: hide by NightClock Window{421530f u0 d0 StatusBar}
12-20 11:56:15.971  3509  3615 V WindowAnimator: hide by NightClock Window{9ce7bae u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
,12-20 11:56:15.981  3509  3509 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
,12-20 11:56:15.981  3509  3509 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
12-20 11:56:15.981  3509  3509 D UcmService: notifyChangeToPlugin event 16
12-20 11:56:15.981  3509  3509 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
,12-20 11:56:15.981  3509  3509 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
12-20 11:56:15.981  3509  3509 D UcmService: notifying to unmanaged plugin
12-20 11:56:15.981  4378  4411 E ucsBai_agentService: notifyChange NOT SUPPORTED
12-20 11:56:15.981  3509  3509 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
12-20 11:56:15.981  3509  3509 D UcmService: agentService status-0
12-20 11:56:15.981  3509  3509 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.ese:eSE Credential Storage Package name = com.samsung.ucs.agent.ese
12-20 11:56:15.981  3509  3509 D UcmService: notifying to managed plugin
12-20 11:56:15.981  3509  3509 D UcmService: checkIfNotify: Valid userid - 0
12-20 11:56:15.981  3509  3509 D PolicyManager: PolicyManager.isStorageEnabled() for userId = 0
,12-20 11:56:15.981  3509  3509 D UniversalCredentialManagerService: checkCallerPermissionFor is called for method-isCredentialStorageManagedAsUser
12-20 11:56:15.981  3509  3509 D UniversalCredentialManagerService: isCredentialStorageManagedAsUser is called....
12-20 11:56:15.991  3509  3509 D PolicyManager: PolicyManager.isStorageEnabled() result = false
12-20 11:56:15.991  3509  3509 D UcmService: agentService com.samsung.ucs.agent.ese:eSE Credential Storage not notified
12-20 11:56:15.991  3509  3509 D UcmService: agentService status-0
12-20 11:56:15.991  3509  3509 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
12-20 11:56:15.991  3509  3509 D UcmService: notifying to unmanaged plugin
12-20 11:56:15.991  4396  4419 D BootAgentService: notifyChange eventId-16
12-20 11:56:15.991  3509  3509 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
12-20 11:56:15.991  3509  3509 D UcmService: agentService status--1
12-20 11:56:15.991  3509  3509 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,12-20 11:56:15.991  4748  4748 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,12-20 11:56:15.991  4748  4748 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,12-20 11:56:16.001  3509  4007 V WindowStateAnimator: Finishing drawing window Window{b373874 u0 d0 AOD}: mDrawState=DRAW_PENDING
,12-20 11:56:16.011  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:56:16.011  3509  3509 I WifiTrafficPoller: evaluateTrafficStatsPolling
,12-20 11:56:16.011  3960  3960 D PanelView: updateQsState
,12-20 11:56:16.011  3960  3960 D KeyguardCircleAffordanceView: setPreviewView: mRight=false,preview=null
12-20 11:56:16.011  3960  3960 D KeyguardCircleAffordanceView: setPreviewView: mRight=true,preview=null
,12-20 11:56:16.011  3960  3960 D KeyguardSwipeHelper: reset()
12-20 11:56:16.011  3960  3960 D KeyguardUnlockEventHandler: reset()
12-20 11:56:16.011  3960  3960 D KeyguardSwipeHelper: resetChildViewVI()
,12-20 11:56:16.021  3509  3881 D WifiStateMachine: handleScreenStateChanged, screen off, set scan interval as max value  !!!
12-20 11:56:16.021  3509  3881 D WifiNative-wlan0: callSECApiVoid - ID [19]
,12-20 11:56:16.021  4152  4152 I wpa_supplicant: set PERIODIC_SCAN_INTERVAL_MAX to 128sec !!!
,12-20 11:56:16.031  3509  3881 E WifiNative-wlan0: do suspend true
,12-20 11:56:16.031  3509  3509 D NotificationService: ACTION_SCREEN_OFF
12-20 11:56:16.031  3509  3509 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3509) 
,12-20 11:56:16.031  3509  3509 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=6) set Off
12-20 11:56:16.031  3509  3509 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
12-20 11:56:16.031  3509  3509 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
12-20 11:56:16.031  3509  3509 D EdgeLight: Turning off
12-20 11:56:16.031  3509  3625 D LightsService: [SvcLED]  onSensorChanged::light value = 24
,12-20 11:56:16.031  3509  3625 D SensorManager: unregisterListener ::   
,12-20 11:56:16.041  3509  3625 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
12-20 11:56:16.041  3509  3625 V AlarmManager:  remove PendingIntent] PendingIntent{4ecf248: PendingIntentRecord{45ac606 android broadcastIntent}}
,12-20 11:56:16.041  4194  4911 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=112]
,12-20 11:56:16.041  3175  3877 D audio_hw_primary: adev_set_parameters: enter: kvpairs: screen_state=off
12-20 11:56:16.041  4194  4194 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.people.package_name=android, samsung.people.notification_type=led_indicator}]
12-20 11:56:16.041  4194  4194 I PeopleStripeService: PeopleNotificationReceiver:3
,12-20 11:56:16.041  4194  4194 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
12-20 11:56:16.041  4194  4194 I PeopleDataManager: removeNotification
,12-20 11:56:16.041  4194  4194 I NotificationParser: getNotiType:android,led_indicator
12-20 11:56:16.041  4194  4194 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=true,key=null,removeAll=false
12-20 11:56:16.041  4194  4194 D PeopleDataManager: removeNotiInfo =null
,12-20 11:56:16.061  3509  3509 I MdnieScenarioControlService: action  :  android.intent.action.SCREEN_OFF
,12-20 11:56:16.071  3509  3509 I FingerprintService: onReceive: android.intent.action.SCREEN_OFF
,12-20 11:56:16.071  3509  3509 I BackgroundCompactionService: Schedule Type1 BGCompaction
,12-20 11:56:16.081  3509  3509 D WifiService: ACTION_SCREEN_OFF, mSContextManager.unregisterListener !!
12-20 11:56:16.081  3509  3509 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@89c5f97, Service = Activity Tracker, used = 0
,12-20 11:56:16.081  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155651
12-20 11:56:16.081  3509  3509 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for ACTIVITY_TRACKER
12-20 11:56:16.081  3509  3509 V CAE     : stop(ContextProvider.java:155)
,12-20 11:56:16.081  3509  3509 V CAE     : clear(ActivityTrackerRunner.java:108)
12-20 11:56:16.081  3509  3509 V CAE     : disable(ActivityTrackerRunner.java:96)
,12-20 11:56:16.081  3509  3509 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 26, 0, 0, 0, 0, 0, 0, 0, 0,
12-20 11:56:16.081  3509  3509 D SensorHubManager: SendSensorHubData: send data = -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
,12-20 11:56:16.081  3182  3222 D Sensorhubs: sendContextData: -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
,12-20 11:56:16.091  3509  3509 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,12-20 11:56:16.091  3509  3509 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:56:16.101  3509  3815 I Sensors : #>LightSensor r=13 g=10 b=8 c=30 atime=245 again=64 lux=24
,12-20 11:56:16.101  3509  3509 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:56:16.111  3509  3509 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,12-20 11:56:16.111  3509  3509 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
12-20 11:56:16.111  3509  3509 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
12-20 11:56:16.111  3509  3509 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6fe5061, Service : DEVICE_PHYSICAL_CONTEXT_MONITOR(1)
,12-20 11:56:16.111  3509  3509 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for ACTIVITY_TRACKER
12-20 11:56:16.111  3509  3509 D SContextService: 	.unregisterCallback : 2, client=
12-20 11:56:16.111  3509  3509 D SContextService: ===== SContext Service List =====
,12-20 11:56:16.111  3509  3509 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@2cbf786, Service : Device Physical Context Monitor
12-20 11:56:16.111  3509  3509 D SContextManager:   .unregisterListener : listener = com.android.server.wifi.WifiServiceImpl$11@407fa16, service=Activity Tracker
,12-20 11:56:16.121  3509  3615 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
,12-20 11:56:16.121  3509  3615 D IpRemoteDisplayController: Bridge Server is not available
,12-20 11:56:16.131  3509  3509 D NetworkPolicy: mScreenReceiver: ACTION_SCREEN_OFF, extra: 3
,12-20 11:56:16.131  3509  3879 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 3
12-20 11:56:16.131  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10009, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
12-20 11:56:16.131  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
,12-20 11:56:16.131  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10065, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
12-20 11:56:16.131  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10072, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
,12-20 11:56:16.161  3509  3589 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,12-20 11:56:16.171  4253  4253 D FusedLocationReceiver: BroadcastReceiver : ACTION_SCREEN_OFF
,12-20 11:56:16.181  4304  9708 D NfcService: call the applyRouting
,12-20 11:56:16.191  3960  4176 D NetworkController.MobileSignalController(0/2147483643): onDataActivity: direction=0
,12-20 11:56:16.211  4328  4328 D Launcher.Workspace: exitWidgetResizeMode. isClearResizeFrame is false
,12-20 11:56:16.261  5257  5257 D BtGatt.GattService: LCD turned off
,12-20 11:56:16.271  5257  5430 D BtGatt.ScanManager: handleLcdOffIntent
12-20 11:56:16.271  5257  5430 D BtGatt.ScanManager: handleLcdOffIntent : thresholdScanValue is = 10 mLastConfiguredScanValue =0
,12-20 11:56:16.281  3509  3815 I Sensors : #>LightSensor r=13 g=10 b=8 c=29 atime=245 again=64 lux=22
,12-20 11:56:16.321  4607  9709 D MdnsClient: Multicast lock held. Releasing
,12-20 11:56:16.351  6319  6319 D CocktailBarUiController: ACTION_SCREEN_OFF
12-20 11:56:16.351  6319  6319 D AbstractCocktailPanelView: setPanelVisible: CocktailPortraitRemotePanelViewfalse will be hiden: 3
12-20 11:56:16.351  6319  6319 D CocktailBarPanelVisibilityManager: updateActivePanelView:  vis=false screenOn=false onTransit=false -hide: 3 current Active: 3
12-20 11:56:16.351  6319  6319 E AbstractCocktailPanelView: notifyPanelVisibilityChanged: visibility not changed 2 id: 3
12-20 11:56:16.351  6319  6319 I TrayVisibilityController: handleMessage : msg.what = 1
,12-20 11:56:16.351  6319  6319 I Utils   : isCurrentUser current = 0, ownerId = 0
,12-20 11:56:16.351  6319  6319 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
12-20 11:56:16.351  6319  6319 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 1
12-20 11:56:16.351  4194  4194 D PeopleStripeService: ACTION_SCREEN_OFF
12-20 11:56:16.351  4194  4194 D PeopleStripeManager: requestCloseCircleViews(),
,12-20 11:56:16.351  4194  4194 I CircleImageSaveLayout: hideImageSaveLayout()
12-20 11:56:16.351  4194  4194 D CircleImageSaveLayout: releaseWakeLock()
12-20 11:56:16.351  3509  3905 I AbsCocktailBarStatePolicy: handleMessage: entry what = 1
12-20 11:56:16.351  4194  4194 D SweepImageListView: hide
12-20 11:56:16.351  4194  4194 D SweepImageListView: setAdapter mAdapter =null:159137937
12-20 11:56:16.351  4194  4194 I PeopleEdgeCommContainer: hideEffectView() 
12-20 11:56:16.351  4194  4194 I CirclePokingManager: stopParticleEffectView  mParticleEffectView-null
,12-20 11:56:16.351  4194  4194 I PeopleDataManager: deleteMarkedCircleEvent : people = null
12-20 11:56:16.351  4194  4194 I PeopleEdgeCommContainer: setPeopleChannelShowStatus false
12-20 11:56:16.351  6319  6319 D TrayStateController: putInputRect mDynamicInputRegion=188281550@LastEvent=t=1482231234239Rect(8, 0 - 64, 588),Rect=Rect(0, 0 - 0, 0)
12-20 11:56:16.351  4194  4194 I PeopleStripeWindow: updateWindowParam : minimize=true,mLastMinimized=true,color0 blur true
12-20 11:56:16.361  6319  6319 D TrayStateController: setUiState: 0 --> 2
,12-20 11:56:16.361  4194  4194 D PeopleStripeVisibilityController: setEmoHistory enable=false
,12-20 11:56:16.361  4194  4194 I PeopleStripeVisibilityController: getComputedTrayVisible : keyguardState = 1
12-20 11:56:16.361  4194  4194 I PeopleStripeVisibilityController: isVisibleByAlwaysOn : mState = 1
12-20 11:56:16.361  4194  4194 E PeopleStripeProcessMonitor: getTopActivity : MultiWindowFacade.taskList = []
,12-20 11:56:16.361  4194  4194 I PeopleStripeProcessMonitor: isPeopleStripeTask packageName = com.sec.android.app.launcher 0
,12-20 11:56:16.361  4194  4194 E PeopleStripeProcessMonitor: getTopActivity : MultiWindowFacade.taskList = []
,12-20 11:56:16.361  4194  4194 I PeopleStripeVisibilityController: updateStripeVisible : State 1 visible = 1
,12-20 11:56:16.361  4194  4194 I PeopleStripeManager: isExistVisibleHandler false
12-20 11:56:16.361  4194  4194 I PeopleStripeManager: showStripe Not exist noti handler.
12-20 11:56:16.361  4194  4194 I PeopleStripeManager: hideStripe
,12-20 11:56:16.371  4194  4194 D PeopleStripeManager: onVisibilityChanged : 2
,12-20 11:56:16.371  4194  4194 D PeopleStripeVisibilityController: setHiddenEdgePanel enable=true
12-20 11:56:16.371  4194  4194 I PeopleStripeVisibilityController: updateStripeVisible : State 1028 visible = 2
12-20 11:56:16.371  4194  4194 I PeopleStripeManager: hideStripe
,12-20 11:56:16.371  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 301 (W:14), CP = 259, CUR = 142, LCD = 0
,12-20 11:56:16.381  3018  3030 D libEGL  : eglTerminate EGLDisplay = 0x7fa983ee78
,12-20 11:56:16.381  3018  4509 I SurfaceFlinger: id=23 Removed DocktailBar (8/12)
,12-20 11:56:16.381  3018  4572 I SurfaceFlinger: id=23 Removed DocktailBar (-2/12)
,12-20 11:56:16.391  3018  3018 D libEGL  : eglTerminate EGLDisplay = 0x7fff7e5bd8
,12-20 11:56:16.401  6319  6319 D CocktailBarUiController: onCocktailBarStateChanged: flag=0x1 vis=2 bgType=0 showTimeout=-1 activate=true
,12-20 11:56:16.401  3509  3509 I SurveyLogManager: mDeviceInfo.mScreen = false
,12-20 11:56:16.401  3509  6576 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-20 11:56:16.421  7178  7178 E SamsungIME: invoke(): method is null
,12-20 11:56:16.441  8617  8655 I SystemBroadcastReceiver: [#CMH#] Received broadcast 
12-20 11:56:16.441  8617  8655 I PolicyManager: [#CMH#] onReceive action = EVENT_SCREEN_OFF
12-20 11:56:16.441  8617  8655 I SystemBroadcastReceiver: [#CMH#] onReceive completed 
,12-20 11:56:16.451  8428  8428 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDA0E41DE4F26DD020CF7906DED0A6ECA9F]}
,12-20 11:56:16.451  8428  8428 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB71D02215B774510884CB3BFD0FBDB0EDC]}
,12-20 11:56:16.451  8428  8428 D [WeatherWidget(1240)]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-20 11:56:16.461  4748  4748 I AlpmModeManager: startAlpmMode : state  = IDLE
,12-20 11:56:16.461  4748  4748 I AlpmModeManager: handleUnblankDisplay: state  = IDLE
12-20 11:56:16.461  4748  4748 V AlpmModeManager: handleUnblankDisplay: setDoze [DISPLAY_STATE_DOZE]
12-20 11:56:16.461  4748  4748 D AlpmModeManager: getLastAlpmHlpmBright : HighNit[true], AlpmHlpm[1], NitMode[[ALPM]_60NIT_ON]
,12-20 11:56:16.461  3509  3791 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = 3, screenState = 3, Brightness = 0, wakefulness = false
12-20 11:56:16.461  3509  3791 D PowerManagerService: [s] UserActivityState : 0 -> 4
12-20 11:56:16.461  4748  4748 I AlpmModeManager: handleUnblankDisplay: AlpmModeManager wakeLock [ACQUIRE]
,12-20 11:56:16.461  3509  3530 D PowerManagerService: [api] acquire WakeLock flags=0x40 tag=AlpmModeManager uid=10000 pid=4748
12-20 11:56:16.461  3509  3530 I libsuspend: !@autosuspend_wakeup_count_disable
12-20 11:56:16.461  3509  3530 D PowerManagerService: mDisplayReady: false
12-20 11:56:16.461  3509  3530 I libsuspend: !@autosuspend_wakeup_count_disable done
12-20 11:56:16.461  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-20 11:56:16.461  3509  3619 D DisplayPowerState: !@ [0] ColorFade exit
12-20 11:56:16.461  3509  3619 D PowerManagerService: [input device light] onColorFadeExit(true)
12-20 11:56:16.461  3509  3530 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,12-20 11:56:16.471  3018  4572 D libEGL  : eglTerminate EGLDisplay = 0x7fa22ffe78
,12-20 11:56:16.471  3018  4572 D libEGL  : eglTerminate EGLDisplay = 0x7fa22ffe78
,12-20 11:56:16.471  3509  3924 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,12-20 11:56:16.471  3018  3028 I SurfaceFlinger: id=24 Removed DolorFade (9/11)
,12-20 11:56:16.471  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-20 11:56:16.471  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:56:16.471  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:56:16.471  3509  3619 D DisplayPowerState: Requesting new screen state: [0] state=DOZE, backlight (By colorFade)=0
12-20 11:56:16.471  3509  3927 D DisplayPowerState: Updating screen state [0]: state=DOZE, backlight (by ColorFade)=0
12-20 11:56:16.471  3509  3626 D DisplayManagerService: !@display_state: OFF -> DOZE brightness: 0 -> 0
12-20 11:56:16.471  3509  3615 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-20 11:56:16.471  3509  3615 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
12-20 11:56:16.481  3018  3018 D libEGL  : eglTerminate EGLDisplay = 0x7fff7e5bd8
,12-20 11:56:16.491  3509  9710 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,12-20 11:56:16.491  3018  3018 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa9d43c00
12-20 11:56:16.491  3018  3018 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,12-20 11:56:16.501  3509  3927 D lights  : lcd : 1 +
12-20 11:56:16.501  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-20 11:56:16.501  3509  3927 D lights  : lcd : 1 -
12-20 11:56:16.501  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-20 11:56:16.501  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:56:16.501  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:16.501  8428  8428 D [WeatherWidget(1240)]  WeatherService: {[44BE909F148A112BE24DB9207B7094FCDA9342562AE17780A60BEC6E95DC6F0D]}
,12-20 11:56:16.511  6319  6319 E CocktailBarPositionManager: Window direction: 0
12-20 11:56:16.511  6319  6319 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-20 11:56:16.511  3509  4333 I ActivityManager: Killing 9098:com.sec.android.app.sns3/u0a41 (adj 15): DHA:empty #33
,12-20 11:56:16.521  3509  4436 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
12-20 11:56:16.521  3509  9710 D BluetoothAdapter: STATE_ON
,12-20 11:56:16.541  3509  4007 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:56:16.541  3509  4436 V AlarmManager:  remove PendingIntent] PendingIntent{eb4715e: PendingIntentRecord{7271bfe com.android.bluetooth broadcastIntent}}
,12-20 11:56:16.551  3509  4333 V AlarmManager:  remove PendingIntent] PendingIntent{a13193f: PendingIntentRecord{7271bfe com.android.bluetooth broadcastIntent}}
,12-20 11:56:16.551  3509  4977 V WindowStateAnimator: Finishing drawing window Window{9ce7bae u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: mDrawState=HAS_DRAWN
,12-20 11:56:16.561  3509  3531 D ActivityManager: cleanUpApplicationRecord -- 9098
,12-20 11:56:16.561  3509  3531 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.sns3, Auto Run ON
,12-20 11:56:16.561  4748  4748 D DefaultClockView: Start AOD Enter Animation
,12-20 11:56:16.561  3509  4334 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:56:16.581  3509  4007 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:56:16.591  3509  9710 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,12-20 11:56:16.611  4060  4060 D Recents : onTaskStackChanged
,12-20 11:56:16.621  3509  9710 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,12-20 11:56:16.631  3509  9710 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,12-20 11:56:16.661  4194  4194 I PeopleStripeManager: isExistVisibleHandler false
,12-20 11:56:16.661  4194  4194 I PeopleStripeManager: hideStripe
,12-20 11:56:16.711  3509  3626 D SurfaceControl: Excessive delay in setPowerMode(): 241ms
,12-20 11:56:16.711  3509  3626 D PowerManagerUtil: Excessive delay in !@display_state: DOZE: 242ms
12-20 11:56:16.721  3509  3626 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 243ms
,12-20 11:56:16.721  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-20 11:56:16.721  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable
12-20 11:56:16.721  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-20 11:56:16.721  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
12-20 11:56:16.721  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:56:16.721  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable done
12-20 11:56:16.721  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:56:16.721  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-20 11:56:16.721  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-20 11:56:16.721  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:56:16.721  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:56:16.721  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-20 11:56:16.721  4748  4748 I AlpmModeManager: handleAlpmModeOn: state  = UNBLANK
12-20 11:56:16.721  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-20 11:56:16.721  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:56:16.721  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:56:16.721  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:56:16.721  3509  3619 D PowerManagerService: mDisplayReady: true
,12-20 11:56:16.721  3509  3619 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-20 11:56:16.731  3509  4334 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:56:16.731  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:56:16.741  3509  4342 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:56:16.741  3509  9710 I BatteryStatsDumper: Writing to database completed
,12-20 11:56:16.751  3509  4487 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:56:16.791  4748  4748 D DefaultClockView: End AOD Enter Animation : ForceStopAnimation : false
,12-20 11:56:16.791  4748  4748 D AODService: : state = Start AOD mode!!
12-20 11:56:16.791  3509  4007 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:56:16.821  4748  4748 D BatteryMeterView: onDraw batteryColor : -986896
,12-20 11:56:16.831  3509  4436 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:56:16.981  3509  3509 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509 (0x0)
,12-20 11:56:17.101  4748  4748 I AlpmModeManager: handleBlankDisplay: current state [ALPM_ON] to [ALPM_STATE_BLANK]
,12-20 11:56:17.101  4748  4748 V AlpmModeManager: handleBlankDisplay: setDoze [DISPLAY_STATE_DOZE_SUSPEND] Keep bright
12-20 11:56:17.101  3509  3791 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
12-20 11:56:17.101  3509  3791 I libsuspend: !@autosuspend_wakeup_count_disable
12-20 11:56:17.101  3509  3791 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,12-20 11:56:17.101  3509  3791 I libsuspend: !@autosuspend_wakeup_count_disable done
12-20 11:56:17.101  3509  3791 D PowerManagerService: mDisplayReady: false
12-20 11:56:17.101  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-20 11:56:17.101  3509  3791 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-20 11:56:17.101  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
,12-20 11:56:17.101  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:56:17.101  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:56:17.101  3509  3626 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
12-20 11:56:17.101  3509  3615 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
,12-20 11:56:17.101  3018  3018 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa9d43c00
12-20 11:56:17.101  3509  3615 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
12-20 11:56:17.101  3018  3018 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,12-20 11:56:17.131  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=4
,12-20 11:56:17.131  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-20 11:56:17.131  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-20 11:56:17.131  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable
12-20 11:56:17.131  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:56:17.131  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable done
,12-20 11:56:17.131  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-20 11:56:17.131  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-20 11:56:17.131  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-20 11:56:17.131  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:56:17.131  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:56:17.131  3509  3619 D PowerManagerService: mDisplayReady: true
12-20 11:56:17.131  3509  3619 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-20 11:56:17.141  6319  6319 E CocktailBarPositionManager: Window direction: 0
12-20 11:56:17.141  6319  6319 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-20 11:56:17.461  3509  6577 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,12-20 11:56:17.471  3509  3593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{18d220c u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f4a898 9646:com.samsung.android.sm.provider/1000}
,12-20 11:56:17.511  3509  3850 D InputReader: Input event(5): value=1 when=285950330000
,12-20 11:56:17.511  3509  3850 D InputReader: !@notifyKey(172), action=0
12-20 11:56:17.511  3509  3850 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=0, interactive=false
,12-20 11:56:17.511  3509  3850 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1144000  uid : 1000  pid : 3509  pkgName : WAKEUP_BOOSTER@34
,12-20 11:56:17.511  3509  3850 E SamsungWindowManager: mCoreNumLockHelper.acquire
12-20 11:56:17.511  3509  3850 D InputManager-JNI: setInteractive(true)
12-20 11:56:17.511  3509  3850 D CustomFrequencyManagerService: requestCPUCore:: CPUCore value is not in the permitted range. CoreNum = 2
12-20 11:56:17.511  3509  3850 D PowerManagerService: [api] [s] wakeUpWithReason (uid: 1000 pid: 3509) eventTime = 285950 event = 1
12-20 11:56:17.511  3509  3850 I PowerManagerService: !@[ps] Screen__On  - 3 :  wakeUpWithReason: 1 (uid: 1000 pid: 3509) (1)
,12-20 11:56:17.511  3509  3850 I PowerManagerService: Waking up from dozing (uid 1000)...
12-20 11:56:17.511  3509  3850 I libsuspend: !@autosuspend_wakeup_count_disable
12-20 11:56:17.511  3509  3850 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
12-20 11:56:17.511  3509  3850 I libsuspend: !@autosuspend_wakeup_count_disable done
12-20 11:56:17.511  3509  3924 D NetworkPolicy: onScreenStateChanged, state: true, reason: 2
12-20 11:56:17.511  3509  3850 D InputManager-JNI: !@handleInterceptActions(172), action=0, wmActions=0
12-20 11:56:17.511  3509  3850 D PowerManagerService: [s] UserActivityState : 4 -> 1
12-20 11:56:17.511  3509  3850 D InputManager-JNI: Disable repeat for home key when device wake up
12-20 11:56:17.511  3509  3850 D PowerManagerService: mDisplayReady: false
12-20 11:56:17.511  3509  3924 V KeyguardServiceDelegate: onStartedWakingUp()
12-20 11:56:17.511  3509  3850 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-20 11:56:17.511  3960  3979 D KeyguardViewMediator: onStartedWakingUp, seq = 4
12-20 11:56:17.511  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:17.511  3960  3979 D KeyguardViewMediator: notifyStartedWakingUp
12-20 11:56:17.511  3509  3619 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_OFF -> REPORTED_TO_POLICY_SCREEN_TURNING_ON.
12-20 11:56:17.511  3960  3960 D KeyguardViewMediator: handleNotifyWakingUp
12-20 11:56:17.511  3960  3960 D PhoneStatusBar: onUnlockHintStarted isSmartLock = false, isInSecureByLockTimeout=false
12-20 11:56:17.511  3960  3960 V KeyguardFingerPrint: updateFingerprintListeningState(false)
,12-20 11:56:17.521  3960  3960 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
12-20 11:56:17.521  3960  3960 V KeyguardUpdateMonitor: stopListeningForFingerprint()
,12-20 11:56:17.521  4328  4328 D Launcher: onRestart, Launcher: 188281550
,12-20 11:56:17.521  3509  3509 D GameManagerService: NotifyRunnable. pkg: com.sec.android.app.launcher, type: 4, isMinimized: false, isTunableApp: false
,12-20 11:56:17.541  6319  6319 E CocktailBarPositionManager: Window direction: 0
12-20 11:56:17.541  6319  6319 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-20 11:56:17.551  4328  4328 D ApplicationPackageManager: we has com.sec.android.app.clockpackage class. reuse it 
,12-20 11:56:17.551  4328  4328 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.sec.android.app.clockpackage
,12-20 11:56:17.561  3509  3619 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@2d8b1b)
12-20 11:56:17.561  3509  3619 D DisplayPowerController: mWindowManagerPolicy.screenTurningOn(mPendingScreenOnUnblocker, 0)
12-20 11:56:17.561  3960  3977 D KeyguardViewMediator: notifyScreenOn
12-20 11:56:17.561  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:17.561  3509  3619 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
,12-20 11:56:17.561  3509  3926 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for AUTO_BRIGHTNESS
12-20 11:56:17.561  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:56:17.561  3509  3926 I CAE     : setPropertyValue(AutoBrightnessRunner.java:129) - Mode = 0
12-20 11:56:17.561  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
12-20 11:56:17.561  3509  3926 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 48, 1, 0,
12-20 11:56:17.561  3509  3926 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : registerListenerRunnable
12-20 11:56:17.561  3509  3926 D SensorHubManager: SendSensorHubData: send data = -63, 23, 48, 1, 0
12-20 11:56:17.561  3509  3593 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.sec.android.app.launcher
12-20 11:56:17.561  3509  3626 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> ON brightness: 1 -> 1
,12-20 11:56:17.561  3182  7712 D Sensorhubs: sendContextData: -63, 23, 48, 1, 0
,12-20 11:56:17.571  3018  3018 D SurfaceFlinger: Set power mode=2, type=0 flinger=0x7fa9d43c00
,12-20 11:56:17.571  3018  3018 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(2)
,12-20 11:56:17.571  3960  3960 D KeyguardViewMediator: handleNotifyScreenTurningOn
,12-20 11:56:17.571  3960  3960 D KeyguardEffectViewController: onScreenTurningOn
12-20 11:56:17.571  3509  3615 I DisplayManagerService: Display device changed state: "Wbudowany ekran", ON
,12-20 11:56:17.571  3509  3615 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", ON
,12-20 11:56:17.581  3509  9715 D MISC PowerHAL: sysfs_write +: /sys/class/input/event0/device/enabled: 1
12-20 11:56:17.581  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:17.581  3509  9715 D MISC PowerHAL: sysfs_write -: /sys/class/input/event0/device/enabled: 1
12-20 11:56:17.581  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:17.581  3509  9716 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 1
12-20 11:56:17.581  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:56:17.581  3509  3619 V KeyguardServiceDelegate: onScreenTurnedOn()
12-20 11:56:17.581  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
12-20 11:56:17.581  3509  9716 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 1
12-20 11:56:17.581  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:17.581  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,12-20 11:56:17.581  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:56:17.581  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
12-20 11:56:17.581  3509  3619 D DisplayPowerController: [M OS] 0 Notify policy about screen turned on.
12-20 11:56:17.581  3509  3619 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_TURNING_ON -> REPORTED_TO_POLICY_SCREEN_ON.
12-20 11:56:17.581  3509  3626 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 1
12-20 11:56:17.581  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:56:17.581  3509  3626 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 1
12-20 11:56:17.581  3509  3619 D PowerManagerService: mDisplayReady: true
12-20 11:56:17.581  3509  3595 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 com.android.server.policy.sec.SamsungPhoneWindowManager$22.run:4527 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:158 
12-20 11:56:17.581  3509  3925 D lights  : button : 1 +
12-20 11:56:17.581  3509  3925 D lights  : button : 1 -
,12-20 11:56:17.581  3960  4430 D KeyguardViewMediator: notifyScreenTurnedOn
12-20 11:56:17.581  3509  3926 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-20 11:56:17.581  3509  3926 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for AUTO_BRIGHTNESS
12-20 11:56:17.581  3509  3926 D SContext.CaeProvider: setAttribute() : 0
12-20 11:56:17.581  3509  3926 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for AUTO_BRIGHTNESS
12-20 11:56:17.581  3509  3926 V CAE     : start(ContextProvider.java:128)
12-20 11:56:17.581  3509  3926 V CAE     : clear(AutoBrightnessRunner.java:297)
12-20 11:56:17.581  3509  3926 V CAE     : enable(AutoBrightnessRunner.java:256)
12-20 11:56:17.581  3509  3926 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 48, 0,
12-20 11:56:17.581  3509  3926 D SensorHubManager: SendSensorHubData: send data = -79, 48, 0
,12-20 11:56:17.591  3182  3182 D Sensorhubs: sendContextData: -79, 48, 0
,12-20 11:56:17.591  6319  6319 E CocktailBarPositionManager: Window direction: 0
12-20 11:56:17.591  6319  6319 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-20 11:56:17.591  3509  3926 D CAE     : getFaultDetectionResult(AutoBrightnessRunner.java:311) - true
12-20 11:56:17.591  3509  3595 V WindowManager: MSG_REQUEST_TRAVERSAL_BY_PWM
,12-20 11:56:17.591  3509  3926 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:56:17.591  4328  4328 D ApplicationPackageManager: we has com.android.calendar class. reuse it 
12-20 11:56:17.591  3509  3615 V WindowOrientationListener: setCurrentAppOrientation :1
12-20 11:56:17.591  3509  3615 I WindowManager: finishPostLayoutPolicyLw : mNightClock.hideLw by screenTurnedOn
12-20 11:56:17.591  3509  3615 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
12-20 11:56:17.591  4748  4748 I AODService: onStartCommand : action : com.samsung.android.app.aodservice.intent.action.AOD_SCREEN_ON
12-20 11:56:17.591  4748  4748 I AODService: onCreate cause: [12-20 11:51:46.639][AOD:true, NightClock:false]<com.samsung.android.app.aodservice.intent.action.AOD_SCREEN_ON> (when Screen on ...)
,12-20 11:56:17.601  3960  3960 D KeyguardViewMediator: IKeyguardDrawnCallback.onDrawn()
,12-20 11:56:17.601  3509  4485 V KeyguardServiceDelegate: **** SHOWN CALLED ****
12-20 11:56:17.601  4328  4328 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.android.calendar
,12-20 11:56:17.601  4328  4328 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,12-20 11:56:17.601  4328  4328 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:56:17.601  4328  4328 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,12-20 11:56:17.601  3960  3960 D KeyguardViewMediator: handleNotifyScreenTurnedOn
12-20 11:56:17.601  3509  3615 D InputDispatcher: Focus left window: 4748
,12-20 11:56:17.601  3509  3509 D LightsService: [api] [SvcLED] turnOff:: id = 5 (uid: 1000 pid: 3509) 
12-20 11:56:17.601  3509  3509 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=5) set Off
12-20 11:56:17.601  3509  3625 D lights  : led_pattern : 0 +
12-20 11:56:17.601  3509  3509 D BatteryService: turn off LED
12-20 11:56:17.601  3509  3625 D LightsService: [SvcLED] handleForcedSvcLEDTask()
12-20 11:56:17.601  3509  3625 I LightsService: fileWriteInt : /sys/class/sec/led/led_lowpower  value : 1
,12-20 11:56:17.601  3960  3960 D SecKeyguardStatusView: onScreenTurnedOn()
,12-20 11:56:17.611  3509  3926 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
12-20 11:56:17.611  3509  3625 D lights  : led_pattern : 0 -
12-20 11:56:17.611  3509  3625 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,12-20 11:56:17.611  3509  3926 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,12-20 11:56:17.611  3509  3926 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
12-20 11:56:17.611  3509  3926 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
12-20 11:56:17.611  3509  3926 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6fe5061, Service : DEVICE_PHYSICAL_CONTEXT_MONITOR(1)
12-20 11:56:17.611  3509  3926 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@d2456a, Service : AUTO_BRIGHTNESS(1)
12-20 11:56:17.611  3509  3926 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for AUTO_BRIGHTNESS
12-20 11:56:17.611  3509  3926 D SContextService: 	.registerCallback : 2, client=
12-20 11:56:17.611  3509  3926 D SContextService: ===== SContext Service List =====
12-20 11:56:17.611  3509  3926 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@2cbf786, Service : Device Physical Context Monitor
12-20 11:56:17.611  3509  3926 D PowerManagerUtil: Excessive delay in SensorHubAutoBrightnessEnabled::registerListener done: 47ms
,12-20 11:56:17.611  3509  3926 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4aa0a5b, Service : Auto Brightness
12-20 11:56:17.611  3509  3926 D SContextManager:   .registerListener : listener = com.android.server.display.AutomaticBrightnessController$6@d74e31, service=Auto Brightness
,12-20 11:56:17.611  4748  4748 I AlpmModeManager: stopAlpmMode: state  = BLANK
12-20 11:56:17.611  4748  4748 I AlpmModeManager: handleAlpmModeOff: state  = BLANK
,12-20 11:56:17.611  4748  4748 I AlpmModeManager: handleAlpmModeOff: AlpmModeManager wakeLock [RELEASE]
12-20 11:56:17.611  3509  3791 D PowerManagerService: [api] release WakeLock flags=0x40 tag=AlpmModeManager uid=10000 pid=4748 (0x0)
,12-20 11:56:17.611  4748  4748 V AlpmModeManager: handleAlpmModeOff: setDozeOverrideFromAod DISPLAY_STATE_UNKNOWN
,12-20 11:56:17.611  3509  4092 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 0, Brightness = 0, wakefulness = true
12-20 11:56:17.611  3509  4092 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,12-20 11:56:17.611  4748  4748 D AODService.ClockTimer: stop
12-20 11:56:17.611  3509  3595 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{9ce7bae u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
,12-20 11:56:17.621  3509  3615 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3509 uid:1000
,12-20 11:56:17.621  3509  3615 D PointerIcon: setMouseCustomIcon IconType is same.101
,12-20 11:56:17.621  3960  3960 D WallpaperService: updateSurface:[forceRelayout]false[redrawNeeded]false
,12-20 11:56:17.621  3960  3960 D ImageWallpaper: onVisibilityChanged:true
12-20 11:56:17.621  3960  3960 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
12-20 11:56:17.621  3960  3960 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
12-20 11:56:17.621  3960  3960 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
12-20 11:56:17.621  4748  4748 I AODService.ClockTimer: stopAlarm : TICK
12-20 11:56:17.621  4328  4328 D Launcher: onStart, Launcher: 188281550
,12-20 11:56:17.621  4328  4328 D Launcher.HomeView: onStart
,12-20 11:56:17.621  4748  4748 I AODService.ClockTimer: stopAlarm : SLEEP
,12-20 11:56:17.621  3509  4007 V AlarmManager:  remove PendingIntent] PendingIntent{b6b13d1: PendingIntentRecord{cb26099 com.samsung.android.app.aodservice broadcastIntent}}
12-20 11:56:17.621  3509  3615 D InputDispatcher: Focus entered window: 4328
12-20 11:56:17.621  3509  4092 V AlarmManager:  remove PendingIntent] PendingIntent{1474e36: PendingIntentRecord{4e596cd com.samsung.android.app.aodservice broadcastIntent}}
12-20 11:56:17.621  4748  4748 I AODService.ClockTimer: stopAlarm : WAKEUP
12-20 11:56:17.621  3509  3615 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3509 uid:1000
12-20 11:56:17.621  3509  3615 D PointerIcon: setMouseCustomIcon IconType is same.101
,12-20 11:56:17.631  4328  4328 D Launcher: onResume, Launcher: 188281550
,12-20 11:56:17.631  3960  3960 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
,12-20 11:56:17.631  3509  4436 V AlarmManager:  remove PendingIntent] PendingIntent{8f4f137: PendingIntentRecord{d5689d1 com.samsung.android.app.aodservice broadcastIntent}}
12-20 11:56:17.631  3509  4334 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
12-20 11:56:17.631  3509  4334 D SettingsProvider: isChangeAllowed() : name = kids_home_mode
12-20 11:56:17.631  3509  4334 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
12-20 11:56:17.631  3509  4334 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
12-20 11:56:17.631  3509  4334 D SettingsProvider: selectionArgs: false
12-20 11:56:17.631  3509  4334 D SettingsProvider: selectionArgs: 10069
,12-20 11:56:17.641  3509  3850 D InputReader: Input event(5): value=0 when=286080126000
,12-20 11:56:17.641  3509  3850 D InputReader: !@notifyKey(172), action=1
12-20 11:56:17.641  3509  4333 D SettingsProvider: isChangeAllowed() : name = aod_show_state
12-20 11:56:17.641  3509  3850 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=1, interactive=true
12-20 11:56:17.641  3509  4333 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
12-20 11:56:17.641  3509  4333 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
12-20 11:56:17.641  3509  4333 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
12-20 11:56:17.641  3509  4333 D SettingsProvider: selectionArgs: false
12-20 11:56:17.641  3509  4333 D SettingsProvider: selectionArgs: 10000
12-20 11:56:17.641  3509  4334 D SettingsProvider: ret = -1
,12-20 11:56:17.641  3509  3595 V WindowManager: MSG_REQUEST_TRAVERSAL_BY_PWM
12-20 11:56:17.641  3509  3850 D InputManager-JNI: !@handleInterceptActions(172), action=1, wmActions=1
12-20 11:56:17.641  3509  4333 D SettingsProvider: ret = -1
,12-20 11:56:17.641  3509  3595 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for AUTO_ROTATION
12-20 11:56:17.641  3509  3595 I CAE     : setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
,12-20 11:56:17.641  3509  3595 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-20 11:56:17.641  3509  3595 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
12-20 11:56:17.641  3509  3595 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for AUTO_ROTATION
,12-20 11:56:17.641  4748  4748 E SettingsUtils: setAODShowState  config = 0
12-20 11:56:17.641  4748  4748 D ScoverManager: unregisterListener
12-20 11:56:17.641  3509  3595 V CAE     : start(ContextProvider.java:128)
,12-20 11:56:17.641  3509  4002 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
12-20 11:56:17.641  3509  3849 D VoIPInterfaceManager: isVoIPRinging()...
12-20 11:56:17.641  3509  3849 I WindowManager: Ignoring HOME; down is not pressed.
12-20 11:56:17.641  3509  3849 D VoIPInterfaceManager: isVoIPRunningAndDeregi()...
12-20 11:56:17.641  3509  3595 V CAE     : clear(AutoRotationRunner.java:182)
12-20 11:56:17.641  3509  3849 D VoIPInterfaceManager: Not exist call session
12-20 11:56:17.641  3509  3595 V CAE     : enable(AutoRotationRunner.java:158)
12-20 11:56:17.641  3509  3530 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
12-20 11:56:17.641  3509  3530 D CoverManager.StateNotifier: unregisterCallback : binder = android.os.BinderProxy@35080ae, pid : 4748, uid : 10000
,12-20 11:56:17.641  3509  3595 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 7, 0, 0,
12-20 11:56:17.641  3509  3595 D SensorHubManager: SendSensorHubData: send data = -79, 7, 0, 0
12-20 11:56:17.641  3509  4487 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity uid=1000 pid=3509
12-20 11:56:17.641  3182  3222 D Sensorhubs: sendContextData: -79, 7, 0, 0
12-20 11:56:17.641  3509  4441 I Sensors : Light old sensor_state 512, new sensor_state : 0 en : 0
12-20 11:56:17.641  4328  4328 D Launcher.HomeView: onResume
,12-20 11:56:17.641  4328  4328 D capture : ---------checkFileExist land
12-20 11:56:17.641  4328  4328 D capture : currentOrientation: 1 mMainHomeScreenshot: true mMainHomeScreenshotLand: true
,12-20 11:56:17.651  3509  3509 I CAE     : handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,12-20 11:56:17.651  4328  4328 D MenuAppsGridFragment: onResume
12-20 11:56:17.651  4328  4328 D MenuAppsGridFragment: changeState: (new)NORMAL(old)NORMAL(force)false
12-20 11:56:17.651  3509  3509 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_WAKEUP
12-20 11:56:17.651  3509  3509 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -47, 0,
,12-20 11:56:17.651  3509  3509 D SensorHubManager: SendSensorHubData: send data = -76, 13, -47, 0
12-20 11:56:17.651  3509  3595 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
12-20 11:56:17.651  3509  4334 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() true
12-20 11:56:17.651  3509  3595 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
12-20 11:56:17.651  3509  4334 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
12-20 11:56:17.651  3182  7712 D Sensorhubs: sendContextData: -76, 13, -47, 0
12-20 11:56:17.651  3509  4334 D KnoxTimeoutHandler: post home show event for user 0
12-20 11:56:17.651  3509  4334 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,12-20 11:56:17.651  3509  3531 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,12-20 11:56:17.661  4748  4748 D SensorManager: unregisterListener ::   
,12-20 11:56:17.661  3509  3509 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
,12-20 11:56:17.661  3509  3595 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:56:17.661  3509  3509 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
12-20 11:56:17.661  3509  3509 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
12-20 11:56:17.661  3509  3509 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,12-20 11:56:17.661  7178  7178 D SamsungIME: IMPL finishInput
12-20 11:56:17.661  3509  3842 E MotionRecognitionService:  handler : SCREEN_ON end
12-20 11:56:17.661  7178  7178 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
12-20 11:56:17.661  7178  7178 D SamsungIME: saveAndClear +
12-20 11:56:17.661  3509  3595 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
12-20 11:56:17.661  7178  7178 D SamsungIME: saveAndClear -
12-20 11:56:17.661  3509  3595 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
12-20 11:56:17.661  4748  4748 I AlpmModeManager: handleUnblankDisplay: state  = ALPM_OFF
12-20 11:56:17.661  3509  3595 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
12-20 11:56:17.661  3509  3595 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6fe5061, Service : DEVICE_PHYSICAL_CONTEXT_MONITOR(1)
12-20 11:56:17.661  3509  3595 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@d2456a, Service : AUTO_BRIGHTNESS(1)
,12-20 11:56:17.661  3509  3509 I KnoxTimeoutHandler: Shared devices show user statefalse
12-20 11:56:17.671  3509  3595 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@c3c1c0d, Service : AUTO_ROTATION(1)
12-20 11:56:17.671  3509  3595 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for AUTO_ROTATION
12-20 11:56:17.671  3509  3595 D SContextService: 	.registerCallback : 3, client=
12-20 11:56:17.671  7178  7178 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
12-20 11:56:17.671  3509  3595 D SContextService: ===== SContext Service List =====
12-20 11:56:17.671  3509  3595 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@2cbf786, Service : Device Physical Context Monitor
12-20 11:56:17.671  3509  3595 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4aa0a5b, Service : Auto Brightness
12-20 11:56:17.671  3509  3595 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@53217c2, Service : Auto Rotation
12-20 11:56:17.671  3509  3595 D SContextManager:   .registerListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@8adcaff, service=Auto Rotation
12-20 11:56:17.671  3509  4436 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@2cbf786, Service = Device Physical Context Monitor, used = 0
12-20 11:56:17.671  3509  4436 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:56:17.671  3509  4436 V CAE     : stop(ContextProvider.java:155)
12-20 11:56:17.671  3509  4436 V CAE     : clear(DevicePhysicalContextMonitorRunner.java:497)
,12-20 11:56:17.671  3509  4436 V CAE     : disable(DevicePhysicalContextMonitorRunner.java:486)
,12-20 11:56:17.671  3509  4436 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 56, 0, 0,
12-20 11:56:17.671  3509  4436 D SensorHubManager: SendSensorHubData: send data = -78, 56, 0, 0
12-20 11:56:17.671  3182  3182 D Sensorhubs: sendContextData: -78, 56, 0, 0
,12-20 11:56:17.671  3509  3509 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_ON
12-20 11:56:17.671  4328  4328 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@72d1b85 time:286116
,12-20 11:56:17.671  3509  4436 D CAE     : getFaultDetectionResult(DevicePhysicalContextMonitorRunner.java:521) - true
,12-20 11:56:17.681  3509  4436 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:56:17.681  3509  3509 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
12-20 11:56:17.681  3509  3509 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
12-20 11:56:17.681  3509  3509 D UcmService: notifyChangeToPlugin event 16
,12-20 11:56:17.681  3509  3509 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
12-20 11:56:17.681  3509  3509 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
12-20 11:56:17.681  3509  3509 D UcmService: notifying to unmanaged plugin
12-20 11:56:17.681  4378  4418 E ucsBai_agentService: notifyChange NOT SUPPORTED
12-20 11:56:17.681  3509  3509 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
12-20 11:56:17.681  3509  3509 D UcmService: agentService status-0
12-20 11:56:17.681  3509  3509 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.ese:eSE Credential Storage Package name = com.samsung.ucs.agent.ese
12-20 11:56:17.681  3509  3509 D UcmService: notifying to managed plugin
12-20 11:56:17.681  3509  3509 D UcmService: checkIfNotify: Valid userid - 0
12-20 11:56:17.681  3509  3509 D PolicyManager: PolicyManager.isStorageEnabled() for userId = 0
12-20 11:56:17.681  3509  3509 D UniversalCredentialManagerService: checkCallerPermissionFor is called for method-isCredentialStorageManagedAsUser
12-20 11:56:17.681  3509  3509 D UniversalCredentialManagerService: isCredentialStorageManagedAsUser is called....
12-20 11:56:17.681  3509  3509 D PolicyManager: PolicyManager.isStorageEnabled() result = false
12-20 11:56:17.681  3509  3509 D UcmService: agentService com.samsung.ucs.agent.ese:eSE Credential Storage not notified
12-20 11:56:17.681  3509  3509 D UcmService: agentService status-0
12-20 11:56:17.681  3509  3509 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
12-20 11:56:17.681  3509  3509 D UcmService: notifying to unmanaged plugin
12-20 11:56:17.681  4396  4424 D BootAgentService: notifyChange eventId-16
12-20 11:56:17.681  3509  3509 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
12-20 11:56:17.681  3509  3509 D UcmService: agentService status--1
12-20 11:56:17.681  3509  3509 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,12-20 11:56:17.691  3509  4436 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:56:17.691  3509  4436 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,12-20 11:56:17.691  3509  4436 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
12-20 11:56:17.691  3509  4436 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,12-20 11:56:17.691  3509  4436 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@d2456a, Service : AUTO_BRIGHTNESS(1)
12-20 11:56:17.691  3509  4436 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@c3c1c0d, Service : AUTO_ROTATION(1)
,12-20 11:56:17.691  3509  4436 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-20 11:56:17.691  3509  4436 D SContextService: 	.unregisterCallback : 3, client=
12-20 11:56:17.691  3509  4436 D SContextService: ===== SContext Service List =====
12-20 11:56:17.691  3509  4436 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4aa0a5b, Service : Auto Brightness
12-20 11:56:17.691  3509  4436 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@53217c2, Service : Auto Rotation
12-20 11:56:17.691  4748  9719 D SContextManager:   .unregisterListener : listener = com.samsung.android.app.aodservice.AODService$7@de2fb91, service=Device Physical Context Monitor
,12-20 11:56:17.691  3509  3509 I WifiTrafficPoller: evaluateTrafficStatsPolling
,12-20 11:56:17.701  3509  3881 D WifiStateMachine: handleScreenStateChanged, screen on, start periodic scan !!!
,12-20 11:56:17.701  3509  3881 D WifiNative-wlan0: callSECApiBoolean - ID [11]
12-20 11:56:17.701  4152  4152 I wpa_supplicant: STOP_PERIODIC_SCAN command
,12-20 11:56:17.701  3509  3509 D NotificationService: ACTION_SCREEN_ON
,12-20 11:56:17.701  3509  3509 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3509) 
12-20 11:56:17.701  3509  3509 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=6) set Off
12-20 11:56:17.701  3509  3509 D EdgeLight: Turning off
12-20 11:56:17.701  3509  3625 D LightsService: [SvcLED] handleForcedSvcLEDTask()
12-20 11:56:17.701  3509  3625 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,12-20 11:56:17.711  4194  4205 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=112]
12-20 11:56:17.711  3175  4780 D audio_hw_primary: adev_set_parameters: enter: kvpairs: screen_state=on
12-20 11:56:17.711  4194  4194 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.people.package_name=android, samsung.people.notification_type=led_indicator}]
12-20 11:56:17.711  4194  4194 I PeopleStripeService: PeopleNotificationReceiver:3
,12-20 11:56:17.711  4194  4194 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
12-20 11:56:17.711  4194  4194 I PeopleDataManager: removeNotification
12-20 11:56:17.711  4194  4194 I NotificationParser: getNotiType:android,led_indicator
12-20 11:56:17.711  4194  4194 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=true,key=null,removeAll=false
12-20 11:56:17.711  4194  4194 D PeopleDataManager: removeNotiInfo =null
,12-20 11:56:17.711  3509  3509 V AlarmManager:  remove PendingIntent] PendingIntent{ac7d00c: PendingIntentRecord{dbf6d55 android broadcastIntent}}
,12-20 11:56:17.721  3182  3221 D Sensorhubs: readContextData: 1, 1, 48, 0, 0, 0, 105, 0, 0, 0, 22
,12-20 11:56:17.721  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(11) = 1, 1, 48, 0, 0, 0, 105, 0, 0, 0, 22
12-20 11:56:17.721  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :11], AP_WAKEUP
12-20 11:56:17.721  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 11
12-20 11:56:17.721  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 48, 0, 0, 0, 105, 0, 0, 0, 22,
,12-20 11:56:17.721  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= AUTO_BRIGHTNESS =================
12-20 11:56:17.721  3509  3838 I CAE     : display(ContextProvider.java:391) - Candela=[105], AmbientLux=[22]
12-20 11:56:17.721  3509  3841 D SContextService: updateSContext() : event = Auto Brightness
12-20 11:56:17.721  3509  3926 D AutomaticBrightnessController: [DAB] onSensorHubChanged : 1st lux = 22.0, 1st candela = 105.0
12-20 11:56:17.721  3509  3926 D AutomaticBrightnessController: [DAB] updateAutoBrightnessSEC : 105(104.65822)    0.0 < 22.0 < 201.0 (0.0)
12-20 11:56:17.721  3509  3926 D AutomaticBrightnessController: mCallbacks.updateBrightness()
12-20 11:56:17.721  3509  3926 D PowerManagerUtil: fileWriteInt to /sys/class/tcon/tcon/auto_br, 1
12-20 11:56:17.721  3509  3926 D PowerManagerUtil: fileWriteInt to /sys/class/lcd/panel/lux, 22
12-20 11:56:17.721  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:17.721  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:17.721  3509  3926 D PowerManagerUtil: fileWriteInt to /sys/class/backlight/panel/auto_brightness, 2
12-20 11:56:17.721  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 105 -> 105
12-20 11:56:17.721  3509  3619 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
,12-20 11:56:17.731  3509  3619 D DisplayPowerController: Tracking Direct to etc : 105
,12-20 11:56:17.731  3509  3927 D lights  : lcd : 105 +
12-20 11:56:17.731  3509  3619 D DisplayPowerController: Animating brightness: target=105, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:56:17.731  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:17.731  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:17.731  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 105 -> 105
12-20 11:56:17.731  3509  3619 D DisplayPowerController: Animating brightness: target=105, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:17.731  3509  3881 E WifiNative-wlan0: do suspend false
,12-20 11:56:17.741  3509  3509 I MdnieScenarioControlService: action  :  android.intent.action.SCREEN_ON
12-20 11:56:17.741  3509  3509 I MdnieScenarioControlService: mGameModeLauncher : false
,12-20 11:56:17.741  3960  3960 V StatusBar.BrightnessController: BRIGHTNESS_PMS_MARKER_SCREEN changed
12-20 11:56:17.741  3960  3960 V StatusBar.BrightnessController: updateSlider = 105
,12-20 11:56:17.741  3509  3926 D PowerManagerUtil: fileWriteInt to /sys/class/mdnie/mdnie/auto_brightness, 2
,12-20 11:56:17.751  3509  3881 D WifiStateMachine: analyze kernel wifi wakelock 
,12-20 11:56:17.751  3509  3881 D WifiStateMachine: file not found /proc/wakelocks
,12-20 11:56:17.761  3509  3927 D lights  : lcd : 105 -
,12-20 11:56:17.761  3509  3927 D DisplayPowerState: Tracking!!: 105
12-20 11:56:17.761  3509  3927 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
12-20 11:56:17.761  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:17.761  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:17.761  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 105 -> 105
12-20 11:56:17.761  3509  3619 D DisplayPowerController: Animating brightness: target=105, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:17.771  3960  3960 V PanelView: too small height - windowHeight = 0
,12-20 11:56:17.781  3509  3509 I MdnieScenarioControlService: setUIMode
,12-20 11:56:17.791  3509  3509 D WifiService: ACTION_SCREEN_ON, checkSensorStatus !!
,12-20 11:56:17.791  3509  3509 E SContext.CaeProvider: setAttribute() : attribute is null!
12-20 11:56:17.791  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155650
12-20 11:56:17.791  3509  3884 V AlarmManager:  remove PendingIntent] PendingIntent{47c8c36: PendingIntentRecord{d7614a4 android broadcastIntent}}
12-20 11:56:17.791  3509  3509 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for ACTIVITY_TRACKER
12-20 11:56:17.791  3509  3509 V CAE     : start(ContextProvider.java:128)
,12-20 11:56:17.791  3509  3509 V CAE     : clear(ActivityTrackerRunner.java:108)
,12-20 11:56:17.791  3509  3509 V CAE     : enable(ActivityTrackerRunner.java:84)
,12-20 11:56:17.791  3509  3509 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 10, 56, 17,
12-20 11:56:17.791  3509  3509 D SensorHubManager: SendSensorHubData: send data = -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 10, 56, 17
12-20 11:56:17.791  3182  3222 D Sensorhubs: sendContextData: -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 10, 56, 17
,12-20 11:56:17.801  3509  3509 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,12-20 11:56:17.801  3509  3509 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:56:17.811  3509  3509 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:56:17.811  3509  3509 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,12-20 11:56:17.811  3509  3509 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
12-20 11:56:17.811  3509  3509 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
12-20 11:56:17.811  3509  3509 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER(1)
,12-20 11:56:17.811  3509  3509 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@d2456a, Service : AUTO_BRIGHTNESS(1)
12-20 11:56:17.811  3509  3509 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@c3c1c0d, Service : AUTO_ROTATION(1)
12-20 11:56:17.811  3509  3509 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for ACTIVITY_TRACKER
12-20 11:56:17.811  3509  3509 D SContextService: 	.registerCallback : 3, client=
12-20 11:56:17.811  3509  3509 D SContextService: ===== SContext Service List =====
12-20 11:56:17.811  3509  3509 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4aa0a5b, Service : Auto Brightness
12-20 11:56:17.811  3509  3509 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@53217c2, Service : Auto Rotation
12-20 11:56:17.811  3509  3509 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4768910, Service : Activity Tracker
,12-20 11:56:17.811  3509  3509 D SContextManager:   .registerListener : listener = com.android.server.wifi.WifiServiceImpl$11@b9d69d3, service=Activity Tracker
12-20 11:56:17.811  3509  3509 W CAE     : getContextInfo(ContextAwareService.java:457) - [getContext 01] Mutex is locked for ACTIVITY_TRACKER_CURRENT_INFO
,12-20 11:56:17.811  3509  3509 V CAE     : enable(ActivityTrackerCurrentInfoRunner.java:178)
12-20 11:56:17.811  4748  4748 D AODService: dismissWindow
12-20 11:56:17.811  3509  3509 V CAE     : clear(ActivityTrackerCurrentInfoRunner.java:202)
12-20 11:56:17.821  4748  4748 D DefaultClockView:  dismiss
12-20 11:56:17.821  3509  3509 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 26, 1, 0,
12-20 11:56:17.821  3509  3509 D SensorHubManager: SendSensorHubData: send data = -72, 26, 1, 0
12-20 11:56:17.821  3182  7712 D Sensorhubs: sendContextData: -72, 26, 1, 0
,12-20 11:56:17.821  3509  3509 D CAE     : getFaultDetectionResult(ActivityTrackerCurrentInfoRunner.java:214) - true
,12-20 11:56:17.821  3018  3030 D libEGL  : eglTerminate EGLDisplay = 0x7fa983ee78
12-20 11:56:17.821  3018  3030 D libEGL  : eglTerminate EGLDisplay = 0x7fa983ee78
12-20 11:56:17.821  3509  3509 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:56:17.821  4748  4748 D ViewRootImpl: #3 mView = null
,12-20 11:56:17.821  3018  3028 I SurfaceFlinger: id=25 Removed BOD (8/10)
12-20 11:56:17.821  3018  3112 I SurfaceFlinger: id=25 Removed BOD (-2/10)
,12-20 11:56:17.831  3018  3018 D libEGL  : eglTerminate EGLDisplay = 0x7fff7e5bd8
,12-20 11:56:17.831  3509  3509 W CAE     : getContextInfo(ContextAwareService.java:511) - [getContext 02] Mutex is unlocked for ACTIVITY_TRACKER_CURRENT_INFO
12-20 11:56:17.831  3509  3509 D SContextService: requestToUpdate() : service = Activity Tracker
12-20 11:56:17.831  3509  3509 D SContextManager:   .requestToUpdate : listener = com.android.server.wifi.WifiServiceImpl$11@b9d69d3, service=Activity Tracker
,12-20 11:56:17.841  3182  3221 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, 88, -39, 33, 0, 2
,12-20 11:56:17.841  3509  3509 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity uid=1000 pid=3509 (0x0)
12-20 11:56:17.841  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, 88, -39, 33, 0, 2
,12-20 11:56:17.841  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
12-20 11:56:17.841  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
12-20 11:56:17.841  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, 88, -39, 33, 0, 2,
,12-20 11:56:17.841  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
12-20 11:56:17.841  3509  3838 I CAE     : display(ContextProvider.java:391) - Accuracy=[2], OperationMode=[0], ActivityType=[0], TimeStamp=[1482231377185]
,12-20 11:56:17.841  3509  3841 D SContextService: updateSContext() : event = Activity Tracker
,12-20 11:56:17.841  3509  3615 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
12-20 11:56:17.841  3509  3615 D IpRemoteDisplayController: Bridge Server is not available
,12-20 11:56:17.851  3509  3509 D WifiStateMachine: setWifiScanMove bMove = 0
,12-20 11:56:17.851  3509  3509 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
,12-20 11:56:17.851  3509  3509 I WifiStateMachine: not vehicle, sendMessageDelayed CMD_SET_SCAN_MOVE with 0
12-20 11:56:17.851  3509  3509 D WifiService: ACTIVITY_STATUS_UNKNOWN 
12-20 11:56:17.851  3509  3881 I WifiStateMachine: DriverStartedState :: CMD_SET_SCAN_MOVE(0) 
12-20 11:56:17.851  3509  3509 D WifiService: setWifiScanWithSensor bMove = 0
12-20 11:56:17.851  4152  4152 I wpa_supplicant: @@wpa_supplicant_set_scan_move : set [0]
,12-20 11:56:17.851  3509  3879 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 1
12-20 11:56:17.851  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10009, mScreenOn: true, uidstate: 0, mProxSensorScreenOff: false
,12-20 11:56:17.851  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: true, uidstate: 3, mProxSensorScreenOff: false
12-20 11:56:17.851  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10065, mScreenOn: true, uidstate: 0, mProxSensorScreenOff: false
12-20 11:56:17.861  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10072, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
12-20 11:56:17.861  3509  3589 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,12-20 11:56:17.871  4253  4253 D FusedLocationReceiver: BroadcastReceiver : ACTION_SCREEN_ON
,12-20 11:56:17.871  3509  3509 D PersonaManagerService: ACTION_SCREEN_ON onReceive
,12-20 11:56:17.871  3509  3631 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
,12-20 11:56:17.881  3509  4007 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,12-20 11:56:17.881  4304  4304 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,12-20 11:56:17.881  4304  4559 D NfcService: call the applyRouting
,12-20 11:56:17.891  3960  4176 D NetworkController.MobileSignalController(0/2147483643): onDataActivity: direction=0
,12-20 11:56:17.901  3182  3221 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, 88, -39, 94, 0, 2
12-20 11:56:17.901  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, 88, -39, 94, 0, 2
,12-20 11:56:17.901  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
12-20 11:56:17.901  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
,12-20 11:56:17.901  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, 88, -39, 94, 0, 2,
12-20 11:56:17.901  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
,12-20 11:56:17.901  3509  3838 I CAE     : display(ContextProvider.java:391) - Accuracy=[2], OperationMode=[0], ActivityType=[0], TimeStamp=[1482231377246]
12-20 11:56:17.901  3509  3841 D SContextService: updateSContext() : event = Activity Tracker
12-20 11:56:17.901  3509  3509 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
12-20 11:56:17.901  3509  3509 D WifiService: ACTIVITY_STATUS_UNKNOWN 
,12-20 11:56:17.921  3509  3509 V AlarmManager:  remove PendingIntent] PendingIntent{ada74ef: PendingIntentRecord{147b977 android broadcastIntent}}
,12-20 11:56:17.921  5257  5257 D BtGatt.GattService: LCD turned on
12-20 11:56:17.921  5257  5430 D BtGatt.ScanManager: handleLcdOnIntent
12-20 11:56:17.921  5257  5430 D BtGatt.ScanManager: handleLcdOnIntent
12-20 11:56:17.921  5257  5430 D BtGatt.ScanManager: ClientIf = 0
,12-20 11:56:17.941  3509  3530 V AlarmManager:  remove PendingIntent] PendingIntent{69b6c09: PendingIntentRecord{3680e5b com.google.android.gms broadcastIntent}}
,12-20 11:56:17.951  6319  6319 D CocktailBarUiController: ACTION_SCREEN_ON
,12-20 11:56:17.951  6319  6319 D AbstractCocktailPanelView: setPanelVisible: CocktailPortraitRemotePanelViewfalse will be hiden: 3
12-20 11:56:17.951  6319  6319 D CocktailBarPanelVisibilityManager: updateActivePanelView:  vis=false screenOn=true onTransit=false -hide: 3 current Active: 3
12-20 11:56:17.951  6319  6319 E AbstractCocktailPanelView: notifyPanelVisibilityChanged: visibility not changed 2 id: 3
12-20 11:56:17.951  6319  6319 I TrayVisibilityController: handleMessage : msg.what = 1
,12-20 11:56:17.951  6319  6319 I Utils   : isCurrentUser current = 0, ownerId = 0
,12-20 11:56:17.951  6319  6319 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 1
12-20 11:56:17.951  6319  6319 I TrayVisibilityController: updateTrayVisible : State : 1 visible = 1 mCurrentVisible = 2
,12-20 11:56:17.951  4194  4194 D PeopleStripeService: ACTION_SCREEN_ON
12-20 11:56:17.951  6319  6319 D TrayStateController: putInputRect mDynamicInputRegion=188281550@LastEvent=t=1482231234239Rect(8, 0 - 64, 588),Rect=Rect(0, 0 - 0, 0)
12-20 11:56:17.951  6319  6319 D TrayStateController: putInputRect mDynamicInputRegion=188281550@LastEvent=t=1482231234239Rect(8, 0 - 64, 588),Rect=Rect(8, 0 - 64, 588)
12-20 11:56:17.951  6319  6319 D TrayStateTrigger: getTriggerMaginOnTop retY=550 h=2560 t=258 trigger=292 getTriggerPosition=1
12-20 11:56:17.951  3509  4441 D PowerManagerService: [api] setButtonBrightnessLimit: 255
,12-20 11:56:17.951  3509  3905 I AbsCocktailBarStatePolicy: handleMessage: entry what = 1
,12-20 11:56:17.951  4194  4194 D PeopleStripeManager: onVisibilityChanged : 1
12-20 11:56:17.951  4194  4194 D PeopleStripeVisibilityController: setHiddenEdgePanel enable=false
,12-20 11:56:17.951  6319  6319 D TrayStateController: setUiState: 2 --> 0
12-20 11:56:17.961  4194  4194 I PeopleStripeVisibilityController: getComputedTrayVisible : keyguardState = 1
12-20 11:56:17.961  4194  4194 I PeopleStripeVisibilityController: isVisibleByAlwaysOn : mState = 1
,12-20 11:56:17.961  4194  4194 I PeopleStripeProcessMonitor: isPeopleStripeTask packageName = com.sec.android.app.launcher 0
,12-20 11:56:17.961  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 259, CUR = 142, LCD = 105
,12-20 11:56:17.971  4194  4194 I PeopleStripeVisibilityController: updateStripeVisible : State 1 visible = 1
,12-20 11:56:17.971  4194  4194 I PeopleStripeManager: isExistVisibleHandler false
12-20 11:56:17.971  4194  4194 I PeopleStripeManager: showStripe Not exist noti handler.
,12-20 11:56:17.971  3018  3018 I SurfaceFlinger: id=26 createSurf (64x588),1 flag=4, DocktailBar
,12-20 11:56:17.971  6319  6352 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [64x588]-format:1
,12-20 11:56:17.981  6319  6319 D CocktailBarUiController: onCocktailBarStateChanged: flag=0x1 vis=1 bgType=0 showTimeout=-1 activate=true
,12-20 11:56:17.981  3509  3509 I SurveyLogManager: mDeviceInfo.mScreen = true
,12-20 11:56:17.981  3509  6576 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-20 11:56:17.991  3509  4342 V WindowStateAnimator: Finishing drawing window Window{ae806aa u0 d0 com.samsung.android.app.cocktailbarservice/com.samsung.android.app.cocktailbarservice.CocktailBarService}: mDrawState=DRAW_PENDING
,12-20 11:56:17.991  3509  3593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84ad02f u-1 com.samsung.ssrm.SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4887832 8428:com.sec.android.daemonapp/u0a166}
,12-20 11:56:18.001  8428  8428 D [WeatherWidget(1240)]  AutoRefreshReceiver: {[43EB1C024052B99D53E991930172379618B5A73E0169704C31B2E0FEC15ABF0DB061C2705E75ED5606D9FFD69F6B37E13822B2991EFA2872858E1E2BB615A6BC25C1BB37530DE4B9994E9888EE083816]}
,12-20 11:56:18.001  8428  8428 D [WeatherWidget(1240)]  AutoRefresh: {[8FD2E506F874D7163C71C5FD167729A3F1524692913D8374891649955E8C59A90C19ED8315B58731AC2FE7582D4006FA]}
,12-20 11:56:18.001  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
12-20 11:56:18.001  7178  7178 E SamsungIME: invoke(): method is null
,12-20 11:56:18.011  3509  4434 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84ad02f u-1 com.samsung.ssrm.SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4887832 8428:com.sec.android.daemonapp/u0a166}
,12-20 11:56:18.011  8428  8428 D [WeatherWidget(1240)]  WeatherScreenReceiver: {[AE44B1CAE710C9799F38EE823B33FC6FDEAF5CF1F84C7C2D7C42190D3C2DE6A81416E92586372C9712C4D2BD025FBC09C229D81C93196B2AA28F22D563A30C15]}
,12-20 11:56:18.011  8428  8428 D [WeatherWidget(1240)]  WidgetCount: {[65C2FDBB08E09D2E8E78BEFE0D618279BC32024A311F60279E75A9FD2AD8BED1]}
,12-20 11:56:18.011  8428  8428 D [WeatherWidget(1240)]  WidgetCount: {[51D05FFECDA2C35BD99FAAEAA7B9A301F0BE9CFAFD994C3F7B3209384CC66988]}
12-20 11:56:18.011  8428  8428 D [WeatherWidget(1240)]  WidgetCount: {[6CEC719F0A07787F8C223B192FCD4687C55ED1AD256D01CA79B528F9A8936DA2AEE8FCF34DEAE62C4F0012DD0AEA3C4D450DA911871FFB9B1B25866B258CE216]}
,12-20 11:56:18.031  8617  8655 I SystemBroadcastReceiver: [#CMH#] Received broadcast 
12-20 11:56:18.031  8617  8655 I PolicyManager: [#CMH#] onReceive action = EVENT_SCREEN_ON
12-20 11:56:18.031  8617  8655 I SystemBroadcastReceiver: [#CMH#] onReceive completed 
,12-20 11:56:18.031  3509  3924 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,12-20 11:56:18.031  8428  8428 D [WeatherWidget(1240)]  WeatherService: {[F5837F4AEE74F4A0BE2DA219DB84933556419BA8B2FB7B09497D41D0C5E6D922]}
,12-20 11:56:18.031  8428  8428 D [WeatherWidget(1240)]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
12-20 11:56:18.031  8428  8428 D [WeatherWidget(1240)]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A000F9D574DD3C1B95D41EAB42ECFF02F3D72C391A0A68B1B0C567090769101B3139122E72F130C4410562206878681E44]}
,12-20 11:56:18.041  8428  8428 D [WeatherWidget(1240)]  WeatherService: {[CC14338CDEB270B60D640F786827F117E88F4AEED272A832A59FE0C979EA04C9BE0E3A339EA914F65899C47723B17899]}
,12-20 11:56:18.041  3509  4434 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{49a6a28 u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4887832 8428:com.sec.android.daemonapp/u0a166}
,12-20 11:56:18.041  8428  8428 D [WeatherWidget(1240)]  WeatherAppWidget: {[9C41A2EAFAAB2EF4F8363256C22FE8ADC05C1B1077ADBDFCD26E0DD65F89F33B4FE17DC1B474497D31FC899B742F59FC7E2530D44AA0E0C337CE79DB8742B2E258F6CB339704D31C42A8D7DC7C423413771689541177F15128C5082E60F137378548A4A3E3BC46E58400842019503B6A49C8E5B66CD635265353D3A3BD633961]}
,12-20 11:56:18.041  8428  8428 D [WeatherWidget(1240)]  : {[AA0F1FFBE590A9EFC37054BD5EE30C3F13AAEFB0C1D46CFF1BAA5F3C6AC68B331A2EF1B485217118DBE54FFA6A88B711AC7C94EA741B05F20DACF9DE9722647F]}
12-20 11:56:18.041  8428  8428 D [WeatherWidget(1240)]  WeatherAppWidget: {[9C41A2EAFAAB2EF4F8363256C22FE8ADC94DE00B25794211F94C1928DF937E6B475EC9A5D52E6E8AB8C5E9065071E1EA]}
,12-20 11:56:18.051  3509  4486 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{49a6a28 u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4887832 8428:com.sec.android.daemonapp/u0a166}
,12-20 11:56:18.051  8428  8428 D [WeatherWidget(1240)]  WeatherAppWidget2x1: {[9C41A2EAFAAB2EF4F8363256C22FE8AD1E8C40D052B00F217143F036334087D4E6A20622B7C5BAFDDAD05806F64279CFB58ACC644B946D1D44C1CB1343E9933E78640F20943B210E98A310C2B6492635456F7A98A5575530AC106B72D841268FE4ABD25C67426FA9138DA38B471E495644FE77123B7000FBE859923F0050324E]}
,12-20 11:56:18.051  6319  6319 D TrayStateTrigger: showTriggerView
12-20 11:56:18.051  8428  8428 D [WeatherWidget(1240)]  : {[60E0DA3EB75B6AC8E852DC6D590E8782BC8A388398CF80A085FDDBC5F835D3B9]}
,12-20 11:56:18.051  8428  8428 D [WeatherWidget(1240)]  : {[474171746BF601005A4D7D98B25C76B809703E254FE098232F11662B7CFA9306AAA83BB048A13628F045F41D951A5325AE3AF9B32C6D1DD1DC31B963A62AF276362FB0436AF461E46827C6999B8AF63FE3E53B8E7C650FB4537EBF1D6F8067C948D7C1C54AB097190AFAAEFD34E60697]}
,12-20 11:56:18.061  3509  4486 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{49a6a28 u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4887832 8428:com.sec.android.daemonapp/u0a166}
,12-20 11:56:18.061  8428  8428 D [WeatherWidget(1240)]  EasyWeatherAppWidget: {[48948B2BE5213A6D5B0C9B7747497512D204533BF333E4D2CEAD653C68E1B222E4748640A665E8FB625C2496224988A01822F94E1D5511EDA528C1BE4CAEABD1D9C6A4F90F6430CF4A4F5AB6F2AF9127520AD0A30D99495D03E7BBCB8D48F747F2FF12B441DB9FDD66804D1185ECF265D727A94D84DA9FC743DD76C54F03F188]}
,12-20 11:56:18.061  8428  8428 D [WeatherWidget(1240)]  : {[AA0F1FFBE590A9EFC37054BD5EE30C3F13AAEFB0C1D46CFF1BAA5F3C6AC68B331A2EF1B485217118DBE54FFA6A88B711AC7C94EA741B05F20DACF9DE9722647F]}
12-20 11:56:18.061  8428  8428 D [WeatherWidget(1240)]  EasyWeatherAppWidget: {[48948B2BE5213A6D5B0C9B774749751274237807901AA8393F0A8526192EEF19F2D7E71ABBE368E57B1937778E7A2758BD22312FFA1C721753FCFDC0AD054D98]}
,12-20 11:56:18.081  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:56:18.201  3182  3221 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, 88, -38, -118, 0, 1
,12-20 11:56:18.201  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, 88, -38, -118, 0, 1
12-20 11:56:18.201  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
,12-20 11:56:18.201  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
12-20 11:56:18.201  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, 88, -38, -118, 0, 1,
,12-20 11:56:18.201  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
12-20 11:56:18.201  3509  3838 I CAE     : display(ContextProvider.java:391) - Accuracy=[1], OperationMode=[0], ActivityType=[0], TimeStamp=[1482231377546]
,12-20 11:56:18.201  3509  3841 D SContextService: updateSContext() : event = Activity Tracker
12-20 11:56:18.201  3509  3509 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
12-20 11:56:18.201  3509  3509 D WifiService: ACTIVITY_STATUS_UNKNOWN 
,12-20 11:56:18.511  3509  3509 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1144000  uid : 1000  pid : 3509  tag : WAKEUP_BOOSTER@34
,12-20 11:56:18.571  3182  3221 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, 88, -37, -14, 0, 0
,12-20 11:56:18.571  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, 88, -37, -14, 0, 0
12-20 11:56:18.571  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
,12-20 11:56:18.571  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
12-20 11:56:18.571  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, 88, -37, -14, 0, 0,
,12-20 11:56:18.571  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
,12-20 11:56:18.571  3509  3838 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[0], TimeStamp=[1482231377906]
,12-20 11:56:18.571  3509  3841 D SContextService: updateSContext() : event = Activity Tracker
12-20 11:56:18.571  3509  3509 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
12-20 11:56:18.571  3509  3509 D WifiService: ACTIVITY_STATUS_UNKNOWN 
,12-20 11:56:18.871  3182  3221 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, 88, -35, 31, 1, 0
,12-20 11:56:18.871  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, 88, -35, 31, 1, 0
12-20 11:56:18.871  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
,12-20 11:56:18.871  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
12-20 11:56:18.871  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, 88, -35, 31, 1, 0,
,12-20 11:56:18.871  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
,12-20 11:56:18.871  3509  3838 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[1], TimeStamp=[1482231378207]
,12-20 11:56:18.871  3509  3841 D SContextService: updateSContext() : event = Activity Tracker
12-20 11:56:18.871  3509  3509 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
12-20 11:56:18.871  3509  3509 D WifiService: ACTIVITY_STATUS_STATIONARY 
,12-20 11:56:18.981  4607  9722 D MdnsClient: #acquireLock. Multicast lock not held. Acquiring
,12-20 11:56:18.981  3509  3791 E BatteryStatsImpl: Wifi multicast lock enabled by UID  = 10021
,12-20 11:56:19.091  3509  3925 D lights  : button : 0 +
,12-20 11:56:19.111  3509  3925 D lights  : button : 0 -
,12-20 11:56:19.401  3182  3221 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, 88, -33, 59, 1, 1
,12-20 11:56:19.401  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, 88, -33, 59, 1, 1
12-20 11:56:19.411  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
,12-20 11:56:19.411  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
12-20 11:56:19.411  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, 88, -33, 59, 1, 1,
,12-20 11:56:19.411  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
,12-20 11:56:19.411  3509  3838 I CAE     : display(ContextProvider.java:391) - Accuracy=[1], OperationMode=[0], ActivityType=[1], TimeStamp=[1482231378747]
,12-20 11:56:19.411  3509  3841 D SContextService: updateSContext() : event = Activity Tracker
12-20 11:56:19.411  3509  3509 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
12-20 11:56:19.411  3509  3509 D WifiService: ACTIVITY_STATUS_STATIONARY 
,12-20 11:56:20.041  8617  8673 I ReschedulableTimer: [#CMH#] ReschedulableTimer started 
,12-20 11:56:20.201  3509  3836 V AlarmManager: Expired Alarm result :4
,12-20 11:56:20.201  3960  3960 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 3, mDelayedShowingSequence = 4
,12-20 11:56:20.431  3509  4485 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-20 11:56:20.431  3509  4485 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:56:20.431  3509  4485 D BatteryService: online:4, current avg:120, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:186
12-20 11:56:20.431  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:56:20.431  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:56:20.431  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:56:20.441  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:56:20.441  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:56:20.441  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:56:20.441  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-20 11:56:20.451  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
12-20 11:56:20.451  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:56:20.461  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:56:20.481  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:56:20.481  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
12-20 11:56:20.481  5298  5298 D BatteryMonitor: new battery level: 100
12-20 11:56:20.481  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-20 11:56:20.481  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:56:20.661  4328  4328 D capture : canCapture isWorkspaceLocked() = false isVisible : false
12-20 11:56:20.661  4328  4328 D capture : canCapture mWorkspace.getState()() = NORMAL isTouchActive : false isPageMoving : false
,12-20 11:56:24.681  3509  6631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-20 11:56:27.991  3509  4007 D WifiService: startScan by pid=4607, uid=10021
,12-20 11:56:27.991  3509  3881 I WifiScanController: location is disabled
,12-20 11:56:27.991  3509  3881 D WifiStateMachine: CMD_START_SCAN : scanLog.mLast - 1482231388006, scanLog.mStartTimeForBigdata - 1482231133491
,12-20 11:56:27.991  4152  4152 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
12-20 11:56:27.991  4152  4152 I wpa_supplicant: P2P: Current p2p state = IDLE
,12-20 11:56:28.031  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 259, CUR = 120, LCD = 105
,12-20 11:56:28.031  4152  4152 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,12-20 11:56:28.901  3167  3639 D Netd    : Iface wlan0 link up
,12-20 11:56:28.901  4152  4152 I wpa_supplicant: nl80211: Received scan results (16 BSSes)
12-20 11:56:28.901  3509  3599 D Tethering: interfaceLinkStateChanged wlan0, true
12-20 11:56:28.901  3509  3599 D Tethering: interfaceStatusChanged wlan0, true
,12-20 11:56:28.911  5298  7587 D PdnController: Interface Changed wlan0 link up
,12-20 11:56:28.911  3509  3880 D WifiP2pService: InactiveState{ what=147461 }
,12-20 11:56:28.911  3509  3880 D WifiP2pService: P2pEnabledState{ what=147461 }
,12-20 11:56:28.911  3509  3880 D WifiP2pService: DefaultState{ what=147461 }
,12-20 11:56:28.951  3509  3509 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,12-20 11:56:28.971  3509  3593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8646dc3 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{72a2686 3960:com.android.systemui/u0a65}
,12-20 11:56:29.081  3509  3836 V AlarmManager: Expired Alarm result :8
,12-20 11:56:29.121  3509  3509 I BackgroundCompactionService: onStart. jobID=801
12-20 11:56:29.121  3509  3509 I BackgroundCompactionService: compact_exception
12-20 11:56:29.121  3509  3509 I BackgroundCompactionService: onStart done. jobID=801
,12-20 11:56:30.481  3509  4007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-20 11:56:30.481  3509  4007 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:56:30.481  3509  4007 D BatteryService: online:4, current avg:123, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:124
12-20 11:56:30.481  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:56:30.491  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:56:30.491  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:56:30.491  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:56:30.491  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:56:30.491  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:56:30.501  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-20 11:56:30.501  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
12-20 11:56:30.501  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:56:30.511  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:56:30.511  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:56:30.521  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:56:30.521  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:56:30.521  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:56:30.541  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:56:33.031  3509  3593 I ActivityManager: Waited long enough for: ServiceRecord{6a3263c u0 com.sec.android.daemonapp/.appservice.WeatherService}
,12-20 11:56:33.211  3509  3850 D InputReader: Input event(4): value=1 when=301649779000
12-20 11:56:33.211  3509  3850 D InputReader: Input event(4): value=1 when=301649779000
12-20 11:56:33.211  3509  3850 I InputReader: Touch event's action is 0x0 (deviceType=0) [pCnt=1, s=0.10 ] when=301649779000
12-20 11:56:33.211  3509  3850 D InputReader: lastThreadEndTime = 286082432294, currentThreadStartTime = 286082435564, diff = 0
12-20 11:56:33.211  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x4, toolType: 1
12-20 11:56:33.211  3509  3849 I InputDispatcher: Delivering touch to (4328): action: 0x0, toolType: 1
12-20 11:56:33.211  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x0, toolType: 1
12-20 11:56:33.211  4328  4328 D ViewRootImpl: ViewPostImeInputStage processPointer 0
,12-20 11:56:33.211  3509  3791 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3509  pkgName : com.sec.android.app.launcher@1
,12-20 11:56:33.221  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:56:33.241  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:56:33.261  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:56:33.271  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=2, mIsPageMoving=true
,12-20 11:56:33.291  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=1, mIsPageMoving=true
,12-20 11:56:33.371  3509  3850 D InputReader: Input event(4): value=0 when=301815130000
,12-20 11:56:33.371  3509  3850 D InputReader: Input event(4): value=0 when=301815130000
12-20 11:56:33.371  3509  3850 I InputReader: Touch event's action is 0x1 (deviceType=0) [pCnt=1, s=] when=301815130000
12-20 11:56:33.371  3509  3849 I InputDispatcher: Delivering touch to (4328): action: 0x1, toolType: 1
12-20 11:56:33.371  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x1, toolType: 1
12-20 11:56:33.371  4328  4328 D ViewRootImpl: ViewPostImeInputStage processPointer 1
,12-20 11:56:33.371  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
12-20 11:56:33.371  3509  6576 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
12-20 11:56:33.371  3509  4485 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3509  tag : com.sec.android.app.launcher@1
,12-20 11:56:33.371  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:56:34.321  3509  3509 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:56:38.071  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 259, CUR = 123, LCD = 105
,12-20 11:56:40.541  3509  4434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-20 11:56:40.541  3509  4434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:56:40.541  3509  4434 D BatteryService: online:4, current avg:128, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:143
12-20 11:56:40.541  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:56:40.551  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:56:40.551  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:56:40.551  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:56:40.551  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:56:40.551  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:56:40.561  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-20 11:56:40.561  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:56:40.561  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:56:40.571  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:56:40.581  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:56:40.581  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:56:40.581  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:56:40.601  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-20 11:56:40.601  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:56:42.861  3509  3828 D TimaService: TIMA: TimaService scheduler is intialized. 
12-20 11:56:42.861  3509  3828 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
12-20 11:56:42.861  3509  3827 D TimaService: TimaServiceHandler.handleMessage what =1
,12-20 11:56:42.861  3509  3828 I TLC_TIMA_PKM_initialize: initializing...
12-20 11:56:42.861  3509  3828 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
12-20 11:56:42.861  3509  3828 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
12-20 11:56:42.861  3509  3828 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
12-20 11:56:42.861  3509  3828 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
12-20 11:56:42.861  3509  3828 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-20 11:56:42.861  3509  3828 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
12-20 11:56:42.861  3509  3828 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
12-20 11:56:42.861  3509  3828 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
12-20 11:56:42.861  3509  3828 I TZ: mc_tlc_communication: device_id = 0x0
12-20 11:56:42.861  3509  3828 I TZ: mc_tlc_communication: tlc_open() was called
12-20 11:56:42.861  3509  3828 I TZ: mc_tlc_communication: Opening MobiCore device
12-20 11:56:42.861  3509  3828 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
12-20 11:56:42.861  3509  3828 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,12-20 11:56:42.871  3509  3828 I TZ: mc_tlc_communication: Opening the session
,12-20 11:56:42.911  3509  3828 I TZ: mc_tlc_communication: tlc_open() succeeded
12-20 11:56:42.911  3509  3828 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info1
,12-20 11:56:42.941  3509  3828 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info2
,12-20 11:56:42.951  3509  3828 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info3
,12-20 11:56:42.951  3509  3828 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info4
,12-20 11:56:42.961  3509  3828 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,12-20 11:56:44.681  3509  6631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-20 11:56:45.201  3509  3836 V AlarmManager: Expired Alarm result :4
,12-20 11:56:45.211  4152  4152 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
12-20 11:56:45.211  4152  4152 I wpa_supplicant: P2P: Current p2p state = IDLE
,12-20 11:56:45.221  4152  4152 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,12-20 11:56:45.411  3509  4180 E Watchdog: !@Sync 10 [12-20 11:56:45.428]
,12-20 11:56:46.581  3509  3828 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
12-20 11:56:46.581  3509  3828 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,12-20 11:56:46.581  3509  3828 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,12-20 11:56:46.591  3509  3828 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,12-20 11:56:46.981  4383  4489 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-20 11:56:46.981  4383  4489 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-20 11:56:48.131  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 259, CUR = 128, LCD = 105
,12-20 11:56:49.181  3167  3639 D Netd    : Iface wlan0 link up
,12-20 11:56:49.181  4152  4152 I wpa_supplicant: nl80211: Received scan results (21 BSSes)
12-20 11:56:49.181  3509  3599 D Tethering: interfaceLinkStateChanged wlan0, true
12-20 11:56:49.181  3509  3599 D Tethering: interfaceStatusChanged wlan0, true
,12-20 11:56:49.181  5298  5308 D PdnController: Interface Changed wlan0 link up
12-20 11:56:49.181  4152  4152 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,12-20 11:56:49.191  3509  3880 D WifiP2pService: InactiveState{ what=147461 }
,12-20 11:56:49.191  3509  3880 D WifiP2pService: P2pEnabledState{ what=147461 }
12-20 11:56:49.191  3509  3880 D WifiP2pService: DefaultState{ what=147461 }
,12-20 11:56:49.231  3509  3509 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,12-20 11:56:49.251  3509  3593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c03d23b u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{72a2686 3960:com.android.systemui/u0a65}
,12-20 11:56:50.611  3509  4436 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-20 11:56:50.611  3509  4436 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:56:50.611  3509  4436 D BatteryService: online:4, current avg:111, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:123
12-20 11:56:50.611  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:56:50.611  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:56:50.621  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:56:50.621  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:56:50.621  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:56:50.621  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:56:50.621  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-20 11:56:50.631  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:56:50.631  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:56:50.631  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:56:50.641  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:56:50.651  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:56:50.651  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
12-20 11:56:50.651  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:56:50.661  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:56:52.561  3509  3836 V AlarmManager: Expired Alarm result :4
,12-20 11:56:57.221  3509  3619 D PowerManagerService: [s] UserActivityState : 1 -> 2
12-20 11:56:57.221  3509  3619 D PowerManagerService: mDisplayReady: false
12-20 11:56:57.221  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:57.221  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:57.221  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:56:57.221  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:56:57.221  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:56:57.221  3509  3619 D PowerManagerService: mDisplayReady: true
,12-20 11:56:57.231  3509  3927 D lights  : lcd : 97 +
,12-20 11:56:57.241  3509  3927 D lights  : lcd : 97 -
,12-20 11:56:57.241  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:57.241  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:57.241  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:56:57.241  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:57.251  3509  3927 D lights  : lcd : 88 +
,12-20 11:56:57.251  3509  3927 D lights  : lcd : 88 -
,12-20 11:56:57.251  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:57.251  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:57.251  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
,12-20 11:56:57.251  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:57.261  3509  3927 D lights  : lcd : 80 +
,12-20 11:56:57.261  3509  3927 D lights  : lcd : 80 -
,12-20 11:56:57.271  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:57.271  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:57.271  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:56:57.271  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:57.281  3509  3927 D lights  : lcd : 72 +
,12-20 11:56:57.291  3509  3927 D lights  : lcd : 72 -
,12-20 11:56:57.291  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:57.291  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:57.291  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:56:57.291  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:57.301  3509  3927 D lights  : lcd : 64 +
,12-20 11:56:57.301  3509  3927 D lights  : lcd : 64 -
,12-20 11:56:57.301  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:57.301  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,12-20 11:56:57.301  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:56:57.301  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:57.311  3509  3927 D lights  : lcd : 57 +
,12-20 11:56:57.311  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:57.311  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:57.311  3509  3927 D lights  : lcd : 57 -
12-20 11:56:57.311  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:56:57.311  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:57.321  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:57.321  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:57.321  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:56:57.321  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:58.181  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 259, CUR = 111, LCD = 57
,12-20 11:56:58.861  3509  3850 D InputReader: Input event(4): value=1 when=327302318000
12-20 11:56:58.861  3509  3850 D InputReader: Input event(4): value=1 when=327302318000
12-20 11:56:58.861  3509  3850 I InputReader: Touch event's action is 0x0 (deviceType=0) [pCnt=1, s=0.11 ] when=327302318000
12-20 11:56:58.861  3509  3850 D InputReader: lastThreadEndTime = 313858932121, currentThreadStartTime = 313858942890, diff = 0
,12-20 11:56:58.861  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x4, toolType: 1
12-20 11:56:58.861  3509  3849 I InputDispatcher: Delivering touch to (4328): action: 0x0, toolType: 1
12-20 11:56:58.861  3509  3849 D PowerManagerService: [s] UserActivityState : 2 -> 1
12-20 11:56:58.861  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x0, toolType: 1
12-20 11:56:58.861  3509  3849 D PowerManagerService: mDisplayReady: false
,12-20 11:56:58.861  4328  4328 D ViewRootImpl: ViewPostImeInputStage processPointer 0
12-20 11:56:58.861  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:58.861  3509  3927 D lights  : lcd : 105 +
12-20 11:56:58.861  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:58.861  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 105 -> 105
12-20 11:56:58.861  3509  3619 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
12-20 11:56:58.861  3509  3619 D DisplayPowerController: Tracking Direct to etc : 105
12-20 11:56:58.861  3509  3619 D DisplayPowerController: Animating brightness: target=105, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:56:58.861  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:58.861  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:58.861  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 105 -> 105
12-20 11:56:58.861  3509  3619 D DisplayPowerController: Animating brightness: target=105, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:56:58.861  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:56:58.861  3509  3619 D PowerManagerService: mDisplayReady: true
,12-20 11:56:58.861  3509  4342 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3509  pkgName : com.sec.android.app.launcher@1
,12-20 11:56:58.871  3509  3927 D lights  : lcd : 105 -
12-20 11:56:58.871  3509  3927 D DisplayPowerState: Tracking!!: 105
12-20 11:56:58.871  3509  3927 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
,12-20 11:56:58.871  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:56:58.871  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:56:58.871  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 105 -> 105
12-20 11:56:58.871  3509  3619 D DisplayPowerController: Animating brightness: target=105, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:56:58.891  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:56:58.901  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:56:58.921  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:56:58.941  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:56:58.951  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:56:58.971  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:56:58.991  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=0, mIsPageMoving=false
,12-20 11:56:59.001  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=1, mIsPageMoving=true
,12-20 11:56:59.071  3509  3850 D InputReader: Input event(4): value=0 when=327517772000
12-20 11:56:59.071  3509  3850 D InputReader: Input event(4): value=0 when=327517772000
12-20 11:56:59.071  3509  3850 I InputReader: Touch event's action is 0x1 (deviceType=0) [pCnt=1, s=] when=327517772000
,12-20 11:56:59.071  3509  3849 I InputDispatcher: Delivering touch to (4328): action: 0x1, toolType: 1
12-20 11:56:59.071  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x1, toolType: 1
12-20 11:56:59.071  4328  4328 D ViewRootImpl: ViewPostImeInputStage processPointer 1
12-20 11:56:59.071  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
12-20 11:56:59.071  3509  6576 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
12-20 11:56:59.071  3509  4486 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3509  tag : com.sec.android.app.launcher@1
,12-20 11:56:59.081  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:56:59.991  3509  3836 V AlarmManager: Expired Alarm result :8
,12-20 11:56:59.991  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-20 11:56:59.991  3960  3960 D KeyguardUpdateMonitor: handleTimeUpdate
,12-20 11:57:00.001  3960  3960 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-20 11:57:00.041  3960  3960 D DateView: received broadcast android.intent.action.TIME_TICK
,12-20 11:57:00.061  8428  8428 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-20 11:57:00.061  8428  8428 D [WeatherWidget(1240)]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-20 11:57:00.061  8428  8428 D [WeatherWidget(1240)]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-20 11:57:00.061  8428  8428 D [WeatherWidget(1240)]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
12-20 11:57:00.061  8428  8428 D [WeatherWidget(1240)]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A000F9D574DD3C1B95D41EAB42ECFF02F3D72C391A0A68B1B0C567090769101B3139122E72F130C4410562206878681E44]}
,12-20 11:57:00.061  8428  8428 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-20 11:57:00.131  3509  3509 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:57:00.661  3509  4436 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-20 11:57:00.661  3509  4436 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:57:00.661  3509  4436 D BatteryService: online:4, current avg:112, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:168
12-20 11:57:00.661  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:57:00.661  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:57:00.661  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:57:00.661  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:57:00.661  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:57:00.671  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:57:00.671  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-20 11:57:00.671  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:57:00.671  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:57:00.681  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:57:00.691  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:57:00.691  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:57:00.691  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:57:00.701  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:57:00.721  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:57:04.691  3509  6631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-20 11:57:08.241  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 259, CUR = 112, LCD = 105
,12-20 11:57:10.711  3509  4487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-20 11:57:10.711  3509  4487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:57:10.711  3509  4487 D BatteryService: online:4, current avg:129, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:97
12-20 11:57:10.711  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:57:10.721  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:57:10.721  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:57:10.721  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:57:10.721  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:57:10.731  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:57:10.731  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-20 11:57:10.731  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:57:10.731  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:57:10.751  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:57:10.751  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:57:10.751  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:57:10.761  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:57:10.781  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-20 11:57:10.781  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:57:15.421  3509  4180 E Watchdog: !@Sync 11 [12-20 11:57:15.430]
,12-20 11:57:16.601  9319  9362 W PlayEventLogger: No account for auth token provided
,12-20 11:57:16.611  9319  9362 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-20 11:57:16.611  9319  9362 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,12-20 11:57:16.621  3167  3642 D EnterpriseController: netId is 0
12-20 11:57:16.621  3167  3642 D Netd    : getNetworkForDns: using netid 502 for uid 10035
,12-20 11:57:18.271  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 258, CUR = 129, LCD = 105
,12-20 11:57:20.771  3509  4002 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-20 11:57:20.771  3509  4002 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:57:20.771  3509  4002 D BatteryService: online:4, current avg:132, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:142
12-20 11:57:20.781  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:57:20.781  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:57:20.781  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:57:20.781  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:57:20.781  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:57:20.791  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:57:20.791  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-20 11:57:20.791  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:57:20.791  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:57:20.811  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:57:20.821  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-20 11:57:20.821  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:57:20.821  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:57:20.831  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-20 11:57:20.831  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:57:22.871  3509  3619 D PowerManagerService: [s] UserActivityState : 1 -> 2
12-20 11:57:22.871  3509  3619 D PowerManagerService: mDisplayReady: false
12-20 11:57:22.871  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:57:22.871  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:57:22.871  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:57:22.871  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:57:22.871  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:57:22.871  3509  3619 D PowerManagerService: mDisplayReady: true
,12-20 11:57:22.891  3509  3927 D lights  : lcd : 98 +
,12-20 11:57:22.891  3509  3927 D lights  : lcd : 98 -
,12-20 11:57:22.891  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:57:22.891  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:57:22.891  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:57:22.891  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:22.891  3509  3927 D lights  : lcd : 90 +
,12-20 11:57:22.901  3509  3927 D lights  : lcd : 90 -
,12-20 11:57:22.901  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:57:22.901  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:57:22.901  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:57:22.901  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:22.911  3509  3927 D lights  : lcd : 81 +
,12-20 11:57:22.911  3509  3927 D lights  : lcd : 81 -
,12-20 11:57:22.911  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:57:22.911  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,12-20 11:57:22.911  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:57:22.911  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:22.931  3509  3927 D lights  : lcd : 73 +
,12-20 11:57:22.931  3509  3927 D lights  : lcd : 73 -
,12-20 11:57:22.941  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:57:22.941  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:57:22.941  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:57:22.941  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:22.941  3509  3927 D lights  : lcd : 65 +
,12-20 11:57:22.951  3509  3927 D lights  : lcd : 65 -
,12-20 11:57:22.951  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:57:22.951  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:57:22.951  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
,12-20 11:57:22.951  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:22.961  3509  3927 D lights  : lcd : 57 +
12-20 11:57:22.961  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:57:22.961  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:57:22.961  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:57:22.961  3509  3927 D lights  : lcd : 57 -
12-20 11:57:22.961  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:22.961  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
,12-20 11:57:22.961  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:57:22.961  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
,12-20 11:57:22.961  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:24.681  3509  6631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-20 11:57:27.201  3509  3850 D InputReader: Input event(4): value=1 when=355639997000
12-20 11:57:27.201  3509  3850 D InputReader: Input event(4): value=1 when=355639997000
12-20 11:57:27.201  3509  3850 I InputReader: Touch event's action is 0x0 (deviceType=0) [pCnt=1, s=0.12 ] when=355639997000
12-20 11:57:27.201  3509  3850 D InputReader: lastThreadEndTime = 343860586945, currentThreadStartTime = 343860600676, diff = 0
,12-20 11:57:27.201  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x4, toolType: 1
12-20 11:57:27.201  3509  3849 I InputDispatcher: Delivering touch to (4328): action: 0x0, toolType: 1
12-20 11:57:27.201  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x0, toolType: 1
12-20 11:57:27.201  3509  3849 D PowerManagerService: [s] UserActivityState : 2 -> 1
12-20 11:57:27.201  3509  3849 D PowerManagerService: mDisplayReady: false
12-20 11:57:27.201  4328  4328 D ViewRootImpl: ViewPostImeInputStage processPointer 0
12-20 11:57:27.201  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:57:27.201  3509  3927 D lights  : lcd : 105 +
12-20 11:57:27.201  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:57:27.201  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 105 -> 105
12-20 11:57:27.201  3509  3619 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
12-20 11:57:27.201  3509  3619 D DisplayPowerController: Tracking Direct to etc : 105
12-20 11:57:27.201  3509  3619 D DisplayPowerController: Animating brightness: target=105, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:57:27.201  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:57:27.201  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:57:27.201  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 105 -> 105
12-20 11:57:27.201  3509  3619 D DisplayPowerController: Animating brightness: target=105, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:57:27.201  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:57:27.201  3509  3619 D PowerManagerService: mDisplayReady: true
,12-20 11:57:27.201  3509  4007 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3509  pkgName : com.sec.android.app.launcher@1
,12-20 11:57:27.211  3509  3927 D lights  : lcd : 105 -
12-20 11:57:27.211  3509  3927 D DisplayPowerState: Tracking!!: 105
,12-20 11:57:27.211  3509  3927 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
12-20 11:57:27.211  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:57:27.211  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:57:27.211  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 105 -> 105
12-20 11:57:27.211  3509  3619 D DisplayPowerController: Animating brightness: target=105, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:27.221  4328  4328 I Launcher.PagedView: determineScrollingStart : mTouchState=1, mIsPageMoving=true
,12-20 11:57:27.321  3509  3850 D InputReader: Input event(4): value=0 when=355764847000
12-20 11:57:27.321  3509  3850 D InputReader: Input event(4): value=0 when=355764847000
,12-20 11:57:27.321  3509  3850 I InputReader: Touch event's action is 0x1 (deviceType=0) [pCnt=1, s=] when=355764847000
,12-20 11:57:27.321  3509  3849 I InputDispatcher: Delivering touch to (4328): action: 0x1, toolType: 1
12-20 11:57:27.321  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x1, toolType: 1
12-20 11:57:27.321  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
12-20 11:57:27.321  4328  4328 D ViewRootImpl: ViewPostImeInputStage processPointer 1
12-20 11:57:27.321  3509  6576 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
12-20 11:57:27.321  3509  3791 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3509  tag : com.sec.android.app.launcher@1
,12-20 11:57:27.331  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:57:28.291  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 258, CUR = 132, LCD = 105
,12-20 11:57:28.391  3509  3509 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:57:30.831  3509  4007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-20 11:57:30.831  3509  4007 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:57:30.831  3509  4007 D BatteryService: online:4, current avg:124, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:139
12-20 11:57:30.831  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:57:30.841  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:57:30.841  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:57:30.841  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:57:30.841  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:57:30.851  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:57:30.851  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-20 11:57:30.851  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
12-20 11:57:30.851  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:57:30.861  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:57:30.871  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:57:30.881  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:57:30.881  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:57:30.881  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:57:30.891  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:57:38.341  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 258, CUR = 124, LCD = 105
,12-20 11:57:40.891  3509  4002 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-20 11:57:40.891  3509  4002 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4355, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:57:40.891  3509  4002 D BatteryService: online:4, current avg:130, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:124
12-20 11:57:40.891  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:57:40.901  3509  3509 I MotionRecognitionService: Plugged
12-20 11:57:40.901  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:57:40.901  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:57:40.901  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:57:40.901  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:57:40.911  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-20 11:57:40.911  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
12-20 11:57:40.911  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:57:40.921  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:57:40.931  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:57:40.931  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:57:40.941  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:57:40.951  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-20 11:57:40.951  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:57:44.681  3509  6631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-20 11:57:45.421  3509  4180 E Watchdog: !@Sync 12 [12-20 11:57:45.432]
,12-20 11:57:47.021  4383  4489 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-20 11:57:47.021  4383  4489 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-20 11:57:47.091  4383  4489 E ContactsProvider_EventLog: Flush buffer to file cnt : 3 size : 0Kb duration : 73ms lastUpdatedAfter : 180317ms
,12-20 11:57:48.401  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 258, CUR = 130, LCD = 105
,12-20 11:57:50.961  3509  4002 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-20 11:57:50.961  3509  4002 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:57:50.961  3509  4002 D BatteryService: online:4, current avg:128, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:128
12-20 11:57:50.961  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:57:50.961  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:57:50.971  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:57:50.971  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:57:50.971  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:57:50.971  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:57:50.971  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-20 11:57:50.971  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
12-20 11:57:50.981  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:57:50.991  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:57:51.001  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:57:51.001  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:57:51.011  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:57:51.021  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:57:51.031  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:57:51.201  3509  3619 D PowerManagerService: [s] UserActivityState : 1 -> 2
,12-20 11:57:51.201  3509  3619 D PowerManagerService: mDisplayReady: false
12-20 11:57:51.201  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:57:51.201  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:57:51.201  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:57:51.201  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:57:51.201  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,12-20 11:57:51.201  3509  3619 D PowerManagerService: mDisplayReady: true
,12-20 11:57:51.221  3509  3927 D lights  : lcd : 97 +
,12-20 11:57:51.221  3509  3927 D lights  : lcd : 97 -
,12-20 11:57:51.221  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:57:51.221  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:57:51.221  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:57:51.221  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:51.231  3509  3927 D lights  : lcd : 88 +
,12-20 11:57:51.231  3509  3927 D lights  : lcd : 88 -
,12-20 11:57:51.231  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
,12-20 11:57:51.251  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:57:51.251  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:57:51.251  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:51.261  3509  3927 D lights  : lcd : 80 +
,12-20 11:57:51.261  3509  3927 D lights  : lcd : 80 -
,12-20 11:57:51.261  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
,12-20 11:57:51.261  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:57:51.261  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:57:51.261  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:51.271  3509  3927 D lights  : lcd : 72 +
,12-20 11:57:51.281  3509  3927 D lights  : lcd : 72 -
,12-20 11:57:51.281  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
,12-20 11:57:51.281  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:57:51.281  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:57:51.281  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:51.281  3509  3927 D lights  : lcd : 63 +
,12-20 11:57:51.291  3509  3927 D lights  : lcd : 63 -
,12-20 11:57:51.291  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:57:51.291  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:57:51.291  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:57:51.291  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:51.301  3509  3927 D lights  : lcd : 57 +
,12-20 11:57:51.301  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:57:51.301  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,12-20 11:57:51.301  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:57:51.301  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:57:51.301  3509  3927 D lights  : lcd : 57 -
,12-20 11:57:51.311  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:57:51.311  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:57:51.311  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
12-20 11:57:51.311  3509  3619 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:57.211  3509  3619 D PowerManagerService: [s] UserActivityState : 2 -> 4
12-20 11:57:57.211  3509  3619 I PowerManagerService: Nap time (uid 1000)...
12-20 11:57:57.211  3509  3619 D InputManager-JNI: setInteractive(false)
12-20 11:57:57.211  3509  3619 D PowerManagerService: handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
12-20 11:57:57.211  3509  3619 I PowerManagerService: !@[ps] Screen__Off - 3 :  dream(timeout) (2)
12-20 11:57:57.211  3509  3619 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
12-20 11:57:57.211  3509  3924 D NetworkPolicy: onScreenStateChanged, state: false, reason: 3
12-20 11:57:57.211  3960  4906 D KeyguardViewMediator: onStartedGoingToSleep(3)
12-20 11:57:57.211  3509  3619 D PowerManagerService: mDisplayReady: false
12-20 11:57:57.211  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=1
12-20 11:57:57.211  3509  3619 D ColorFade: prepare: mode=4
,12-20 11:57:57.211  3018  3018 I SurfaceFlinger: id=27 createSurf (1440x2560),2 flag=404, DolorFade
,12-20 11:57:57.211  3509  3619 D PowerManagerUtil: Excessive delay in ColorFade : createSurface: 10ms
12-20 11:57:57.211  7178  7178 D SamsungIME: IMPL finishInput
,12-20 11:57:57.211  7178  7178 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
12-20 11:57:57.211  7178  7178 D SamsungIME: saveAndClear +
12-20 11:57:57.211  7178  7178 D SamsungIME: saveAndClear -
,12-20 11:57:57.221  3509  3619 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,12-20 11:57:57.221  7178  7178 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,12-20 11:57:57.231  3960  4906 E KeyguardViewMediator: lockAfterTimeout = 5000 policyTimeout = 0
,12-20 11:57:57.241  3960  4906 D KeyguardViewMediator: timeout : 5000
,12-20 11:57:57.241  3960  4906 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 4
,12-20 11:57:57.241  3960  4906 D KeyguardViewMediator: notifyStartedGoingToSleep
12-20 11:57:57.241  3960  3960 V KeyguardFingerPrint: updateFingerprintListeningState(false)
12-20 11:57:57.241  3960  3960 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
12-20 11:57:57.241  3960  3960 V KeyguardUpdateMonitor: stopListeningForFingerprint()
,12-20 11:57:57.241  3960  3960 D KeyguardViewMediator: handleNotifyStartedGoingToSleep
,12-20 11:57:57.271  3509  3619 D libEGL  : eglInitialize EGLDisplay = 0x7f9693e778
,12-20 11:57:57.271  3509  3619 D libEGL  : eglTerminate EGLDisplay = 0x7f9693e8e8
,12-20 11:57:57.281  3509  3619 D ColorFade: ColorFade is ready
,12-20 11:57:57.281  3509  3619 D DisplayPowerController: ColorFade: onAnimationStart
12-20 11:57:57.281  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:57:57.281  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 105 -> 105
,12-20 11:57:57.311  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:57:57.331  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:57:57.341  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:57:57.581  3509  3619 D DisplayPowerState: !@ [0] ColorFade entry
12-20 11:57:57.581  3509  3619 D PowerManagerService: [input device light] onColorFadeExit(false)
12-20 11:57:57.581  3509  3619 D DisplayPowerController: ColorFade: onAnimationEnd
,12-20 11:57:57.581  3509  3927 D lights  : lcd : 0 +
12-20 11:57:57.581  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=1
12-20 11:57:57.581  3509  3619 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_* -> REPORTED_TO_POLICY_SCREEN_OFF.
,12-20 11:57:57.591  6319  6329 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.sec.android.app.launcher/com.android.launcher2.Launcher}
,12-20 11:57:57.591  4328  4328 D Launcher: onPause, Launcher: 188281550
12-20 11:57:57.591  4328  4328 D Launcher.HomeView: onPause
12-20 11:57:57.591  4328  4328 D Launcher.Workspace: exitWidgetResizeMode. isClearResizeFrame is false
,12-20 11:57:57.601  3509  3927 D lights  : lcd : 0 -
,12-20 11:57:57.641  3509  3619 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@53217c2, Service = Auto Rotation, used = 0
,12-20 11:57:57.641  3509  3619 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for AUTO_ROTATION
,12-20 11:57:57.641  3509  3619 V CAE     : stop(ContextProvider.java:155)
,12-20 11:57:57.641  4328  4328 V ActivityThread: updateVisibility : ActivityRecord{2719980 token=android.os.BinderProxy@72d1b85 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
12-20 11:57:57.641  4328  4328 D Launcher.HomeView: onStop
12-20 11:57:57.641  4328  4328 D capture : ----destroy
,12-20 11:57:57.651  3509  3619 V CAE     : clear(AutoRotationRunner.java:182)
,12-20 11:57:57.651  3509  3619 V CAE     : disable(AutoRotationRunner.java:171)
12-20 11:57:57.651  3509  3619 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 7, 0, 0,
,12-20 11:57:57.651  3509  3619 D SensorHubManager: SendSensorHubData: send data = -78, 7, 0, 0
12-20 11:57:57.651  3182  3182 D Sensorhubs: sendContextData: -78, 7, 0, 0
,12-20 11:57:57.661  3509  3619 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,12-20 11:57:57.661  3509  3619 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:57:57.671  3509  3619 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:57:57.681  3509  3619 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,12-20 11:57:57.681  3509  3619 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
12-20 11:57:57.681  3509  3619 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,12-20 11:57:57.681  3509  3619 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER(1)
,12-20 11:57:57.681  3509  3619 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@d2456a, Service : AUTO_BRIGHTNESS(1)
12-20 11:57:57.681  3509  3619 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
12-20 11:57:57.681  3509  3619 D SContextService: 	.unregisterCallback : 3, client=
12-20 11:57:57.681  3509  3619 D SContextService: ===== SContext Service List =====
12-20 11:57:57.681  3509  3619 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4aa0a5b, Service : Auto Brightness
,12-20 11:57:57.681  3509  3619 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4768910, Service : Activity Tracker
12-20 11:57:57.681  3509  3619 D SContextManager:   .unregisterListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@8adcaff, service=Auto Rotation
12-20 11:57:57.681  3509  3619 V KeyguardServiceDelegate: onScreenTurnedOff()
12-20 11:57:57.681  3960  3977 D KeyguardViewMediator: notifyScreenTurnedOff
12-20 11:57:57.681  3960  3960 D KeyguardViewMediator: handleNotifyScreenTurnedOff
12-20 11:57:57.691  3960  3960 D vol.SecVolumeDialog: onScreenTurnedOff()
12-20 11:57:57.691  3960  3960 D vol.SecVolumeDialog: dismissH reason: 4
12-20 11:57:57.691  3960  3960 D vol.SecVolumeDialog: dismissH : false
,12-20 11:57:57.691  3509  3619 D DisplayPowerController: mWindowManagerPolicy.screenTurnedOff(0)
12-20 11:57:57.691  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
12-20 11:57:57.691  3509  3926 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@4aa0a5b, Service = Auto Brightness, used = 0
12-20 11:57:57.691  3509  3619 D PowerManagerUtil: fileWriteInt to /sys/class/tcon/tcon/auto_br, 0
12-20 11:57:57.691  3509  3926 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for AUTO_BRIGHTNESS
12-20 11:57:57.691  3509  3926 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : unregisterListenerRunnable
12-20 11:57:57.691  3509  3595 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 com.android.server.policy.sec.SamsungPhoneWindowManager$22.run:4527 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:158 
12-20 11:57:57.691  3509  3619 D PowerManagerUtil: fileWriteInt to /sys/class/backlight/panel/auto_brightness, 0
12-20 11:57:57.691  4748  4748 I AODService: onStartCommand : action : com.samsung.android.app.aodservice.intent.action.AOD_SCREEN_OFF
12-20 11:57:57.691  4748  4748 I AODService: onCreate cause: [12-20 11:51:46.639][AOD:true, NightClock:false]<com.samsung.android.app.aodservice.intent.action.AOD_SCREEN_ON> (when Screen on ...)
12-20 11:57:57.691  3509  3926 V CAE     : stop(ContextProvider.java:155)
12-20 11:57:57.691  3509  3926 V CAE     : clear(AutoBrightnessRunner.java:297)
12-20 11:57:57.691  3509  3926 V CAE     : disable(AutoBrightnessRunner.java:286)
,12-20 11:57:57.691  3509  3926 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 48, 0, 0,
12-20 11:57:57.691  3509  3619 D PowerManagerUtil: fileWriteInt to /sys/class/mdnie/mdnie/auto_brightness, 0
12-20 11:57:57.691  3509  3926 D SensorHubManager: SendSensorHubData: send data = -78, 48, 0, 0
12-20 11:57:57.691  3182  3222 D Sensorhubs: sendContextData: -78, 48, 0, 0
12-20 11:57:57.691  3509  3619 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
12-20 11:57:57.691  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
12-20 11:57:57.691  3509  3619 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:57.691  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=1
12-20 11:57:57.691  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
12-20 11:57:57.691  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
12-20 11:57:57.691  3509  3619 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:57.701  3509  9778 D MISC PowerHAL: sysfs_write +: /sys/class/input/event0/device/enabled: 0
12-20 11:57:57.701  3509  9779 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 0
,12-20 11:57:57.701  3509  9778 D MISC PowerHAL: sysfs_write -: /sys/class/input/event0/device/enabled: 0
12-20 11:57:57.701  3509  9779 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 0
12-20 11:57:57.701  3509  3626 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
12-20 11:57:57.701  3509  3626 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
12-20 11:57:57.701  3509  3626 D DisplayManagerService: !@display_state: ON -> OFF brightness: 0 -> 0
,12-20 11:57:57.701  3509  3615 I DisplayManagerService: Display device changed state: "Wbudowany ekran", OFF
12-20 11:57:57.701  3018  3018 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7fa9d43c00
12-20 11:57:57.701  3509  3615 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", OFF
12-20 11:57:57.701  3018  3018 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(0)
,12-20 11:57:57.711  3509  3926 D CAE     : getFaultDetectionResult(AutoBrightnessRunner.java:311) - true
12-20 11:57:57.711  3509  3926 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:57:57.711  3960  3960 D ImageWallpaper: onVisibilityChanged:false
,12-20 11:57:57.721  3960  3960 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
,12-20 11:57:57.721  3960  3960 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
12-20 11:57:57.721  3960  3960 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,12-20 11:57:57.731  6319  6319 E CocktailBarPositionManager: Window direction: 0
12-20 11:57:57.731  6319  6319 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-20 11:57:57.731  3509  3926 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:57:57.731  3509  3926 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,12-20 11:57:57.731  3509  3926 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
12-20 11:57:57.741  3509  3926 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,12-20 11:57:57.741  3509  3926 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER(1)
12-20 11:57:57.741  3509  3926 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for AUTO_BRIGHTNESS
12-20 11:57:57.741  3509  3926 D SContextService: 	.unregisterCallback : 2, client=
12-20 11:57:57.741  3509  3926 D SContextService: ===== SContext Service List =====
,12-20 11:57:57.741  3509  3926 D PowerManagerUtil: Excessive delay in SensorHubAutoBrightnessEnabled::unregisterListener done: 49ms
12-20 11:57:57.741  3509  3926 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4768910, Service : Activity Tracker
12-20 11:57:57.741  3509  3926 D SContextManager:   .unregisterListener : listener = com.android.server.display.AutomaticBrightnessController$6@d74e31, service=Auto Brightness
,12-20 11:57:57.741  3509  4441 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,12-20 11:57:57.741  3509  4342 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
12-20 11:57:57.741  4748  4748 D ScoverManager: registerListener
12-20 11:57:57.741  3509  4002 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,12-20 11:57:57.741  3509  4434 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
12-20 11:57:57.741  3509  4434 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@fac4db3, pid : 4748, uid : 10000, type : 1
,12-20 11:57:57.751  4748  9780 D AODService: onCreate register mSContextListener : com.samsung.android.app.aodservice.AODService$7@de2fb91
,12-20 11:57:57.751  3509  3530 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,12-20 11:57:57.751  3509  4333 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-20 11:57:57.751  3509  4333 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 4, 0, 0, 0, 1, 2,
12-20 11:57:57.751  3509  4333 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 4, 0, 0, 0, 1, 2
,12-20 11:57:57.751  3182  7712 D Sensorhubs: sendContextData: -63, 23, 56, 4, 0, 0, 0, 1, 2
12-20 11:57:57.751  3509  4092 I Sensors : Light old sensor_state 0, new sensor_state : 512 en : 1
,12-20 11:57:57.761  3509  4333 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,12-20 11:57:57.761  3509  4333 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-20 11:57:57.761  3509  4333 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:57:57.761  3509  4333 V CAE     : start(ContextProvider.java:128)
,12-20 11:57:57.771  4748  4748 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
12-20 11:57:57.771  4748  4748 D AODService: registerBatteryReceiver
,12-20 11:57:57.771  3509  4333 V CAE     : clear(DevicePhysicalContextMonitorRunner.java:497)
12-20 11:57:57.771  3509  4333 V CAE     : enable(DevicePhysicalContextMonitorRunner.java:471)
,12-20 11:57:57.771  3509  4333 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 56, 0, 10, 57, 57,
12-20 11:57:57.771  3509  4333 D SensorHubManager: SendSensorHubData: send data = -79, 56, 0, 10, 57, 57
,12-20 11:57:57.771  4748  4748 D BatteryController: saveBatteryData : level[100], status[5]
12-20 11:57:57.771  4748  4748 D AODService: Cover coverOpen[true], isBlackListCover(type)[false]
12-20 11:57:57.771  4748  4748 D AODService.ClockTimer: ClockTimer:start : true
12-20 11:57:57.771  3182  3182 D Sensorhubs: sendContextData: -79, 56, 0, 10, 57, 57
,12-20 11:57:57.771  3509  4333 D CAE     : getFaultDetectionResult(DevicePhysicalContextMonitorRunner.java:521) - true
,12-20 11:57:57.771  4748  4748 D AODService.ClockTimer: observe start aod
12-20 11:57:57.771  4748  4748 D AODService.ClockTimer: notifyWakeUp
12-20 11:57:57.771  3509  4333 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:57:57.781  4748  4748 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
,12-20 11:57:57.781  3509  4007 D SettingsProvider: isChangeAllowed() : name = aod_show_state
12-20 11:57:57.781  3509  4007 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
12-20 11:57:57.781  3509  4007 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
12-20 11:57:57.781  3509  4007 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
12-20 11:57:57.781  3509  4007 D SettingsProvider: selectionArgs: false
12-20 11:57:57.781  3509  4007 D SettingsProvider: selectionArgs: 10000
12-20 11:57:57.781  3509  4007 D SettingsProvider: ret = -1
,12-20 11:57:57.781  4748  4748 E SettingsUtils: setAODShowState  config = 1
12-20 11:57:57.781  4748  4748 D AlpmModeManager: setFirstStartALPM() initialize value
,12-20 11:57:57.781  4748  4748 D AODService: createWindow
,12-20 11:57:57.791  3509  4333 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:57:57.791  3509  4333 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,12-20 11:57:57.791  3509  4333 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
12-20 11:57:57.791  3509  4333 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
12-20 11:57:57.791  4748  4748 I AODUpdatePositionController: initPosition : X[-10], Y[889] Rect(-50, 0 - 50, 920)
12-20 11:57:57.791  3509  4333 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER(1)
,12-20 11:57:57.791  3509  4333 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@14af07a, Service : DEVICE_PHYSICAL_CONTEXT_MONITOR(1)
12-20 11:57:57.791  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:57:57.791  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:57:57.791  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:57:57.791  3509  4333 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:57:57.791  3509  4333 D SContextService: 	.registerCallback : 2, client=
12-20 11:57:57.791  3509  4333 D SContextService: ===== SContext Service List =====
12-20 11:57:57.791  3509  4333 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4768910, Service : Activity Tracker
12-20 11:57:57.791  3509  4333 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@a89c02b, Service : Device Physical Context Monitor
12-20 11:57:57.791  4748  9780 D SContextManager:   .registerListener : listener = com.samsung.android.app.aodservice.AODService$7@de2fb91, service=Device Physical Context Monitor
,12-20 11:57:57.791  3509  4977 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:57:57.791  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:57:57.791  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:57:57.791  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:57:57.791  3509  4977 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 1, 2, 88,
12-20 11:57:57.791  3509  4977 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 1, 2, 88
12-20 11:57:57.791  3182  3222 D Sensorhubs: sendContextData: -63, 23, 56, 3, 1, 2, 88
12-20 11:57:57.801  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,12-20 11:57:57.801  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:57:57.801  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,12-20 11:57:57.801  4748  4748 I DefaultClockView: composeDefaultClockView: Selected clock = 0
,12-20 11:57:57.801  3509  4977 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,12-20 11:57:57.801  3509  4977 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:57:57.811  3509  4436 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:57:57.811  3509  4436 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 2, 0, 3,
12-20 11:57:57.811  3509  4436 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 2, 0, 3
12-20 11:57:57.811  3182  7712 D Sensorhubs: sendContextData: -63, 23, 56, 3, 2, 0, 3
,12-20 11:57:57.811  3509  3521 I art     : Background sticky concurrent mark sweep GC freed 134671(9MB) AllocSpace objects, 118(2MB) LOS objects, 25% free, 38MB/51MB, paused 3.800ms total 101.104ms
,12-20 11:57:57.811  4748  4748 D BatteryMeterView: BatteryMeterView 
12-20 11:57:57.811  3509  4436 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-20 11:57:57.811  3509  4436 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:57:57.811  3509  4485 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:57:57.811  3509  4485 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 3, 0, 60,
12-20 11:57:57.811  3509  4485 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 3, 0, 60
12-20 11:57:57.811  3182  3182 D Sensorhubs: sendContextData: -63, 23, 56, 3, 3, 0, 60
,12-20 11:57:57.821  3509  4485 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,12-20 11:57:57.821  3509  4485 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:57:57.821  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:57:57.821  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:57:57.821  4748  4748 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:57:57.821  3509  3530 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:57:57.821  3509  3530 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 3, 4, 0, 1,
12-20 11:57:57.821  3509  3530 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 3, 4, 0, 1
12-20 11:57:57.821  3182  3222 D Sensorhubs: sendContextData: -63, 23, 56, 3, 4, 0, 1
,12-20 11:57:57.821  4748  4748 D DefaultClockView: LocalTime Pattern : HH:mm
,12-20 11:57:57.821  4748  4748 I AODUpdatePositionController: updatePosition: start current clock, Current X[-10] Current Y[889] NewPositionTimer[60]
12-20 11:57:57.821  3509  3530 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-20 11:57:57.831  3509  3530 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:57:57.831  4748  4748 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 11:57 time02: null ampm: null
,12-20 11:57:57.831  3509  3791 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:57:57.831  3509  3791 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 4, 0, 0, 0, 110, 1,
12-20 11:57:57.831  3509  3791 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 4, 0, 0, 0, 110, 1
12-20 11:57:57.831  3182  7712 D Sensorhubs: sendContextData: -63, 23, 56, 4, 0, 0, 0, 110, 1
,12-20 11:57:57.841  4748  4748 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,12-20 11:57:57.841  4748  4748 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
12-20 11:57:57.841  4748  4748 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:wt., 20 gru 11:57
12-20 11:57:57.841  4748  4748 D DefaultClockView: show
,12-20 11:57:57.841  3509  3791 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-20 11:57:57.841  3509  3791 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:57:57.841  4748  4748 D ViewRootImpl: #1 mView = com.samsung.android.app.aodservice.nightclock.DefaultClockView{43ba989 V.E...... ......ID 0,0-0,0}
12-20 11:57:57.841  3509  4092 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:57:57.841  3509  4092 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 56, 4, 0, 0, 0, 17, 2,
12-20 11:57:57.841  3509  4092 D SensorHubManager: SendSensorHubData: send data = -63, 23, 56, 4, 0, 0, 0, 17, 2
12-20 11:57:57.841  3182  3182 D Sensorhubs: sendContextData: -63, 23, 56, 4, 0, 0, 0, 17, 2
,12-20 11:57:57.841  3509  4002 D ISSUE_DEBUG: InputChannelName : 52bc621 AOD
,12-20 11:57:57.841  3509  4002 D InputDispatcher: Focus left window: 4328
12-20 11:57:57.841  3509  3595 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{52bc621 u0 d0 AOD}
,12-20 11:57:57.841  3509  4002 D InputDispatcher: Focus entered window: 4748
12-20 11:57:57.841  3960  3960 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
12-20 11:57:57.851  3509  3615 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3509 uid:1000
12-20 11:57:57.851  3509  3615 D PointerIcon: setMouseCustomIcon IconType is same.101
12-20 11:57:57.851  3509  4092 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
12-20 11:57:57.851  3509  4092 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:57:57.871  3509  3626 D SurfaceControl: Excessive delay in setPowerMode(): 167ms
12-20 11:57:57.871  3509  3626 D PowerManagerUtil: Excessive delay in !@display_state: OFF: 168ms
12-20 11:57:57.871  3509  3626 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 171ms
12-20 11:57:57.871  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=1
12-20 11:57:57.871  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
12-20 11:57:57.871  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
12-20 11:57:57.871  3509  3619 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:57:57.871  3509  3619 I PowerManagerService: [PWL] Off : 0s ago
12-20 11:57:57.871  3509  3619 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
12-20 11:57:57.871  3509  3619 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
12-20 11:57:57.871  3509  3619 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AlwaysOnDisplay_EnsureWorkingTime' (uid=10000, pid=4748, ws=null) (elapsedTime=118)
12-20 11:57:57.871  3509  3619 I PowerManagerService: [PWL]   PowerManagerService.Display: ref count=2
12-20 11:57:57.871  3509  3619 I PowerManagerService: [PWL]     mUserActivitySummary : 0x4
12-20 11:57:57.871  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable
12-20 11:57:57.871  3509  3619 I PowerManagerService: [PWL]     mDisplayReady : false
12-20 11:57:57.871  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable done
12-20 11:57:57.871  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=1
12-20 11:57:57.871  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
12-20 11:57:57.871  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
,12-20 11:57:57.871  3509  3619 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:57:57.871  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:57:57.871  3509  3619 D PowerManagerService: mDisplayReady: true
12-20 11:57:57.871  3509  3619 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
12-20 11:57:57.871  3509  3619 D PowerManagerService: handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
12-20 11:57:57.871  3509  3619 D PowerManagerService: handleSandman : startDream(true)
12-20 11:57:57.871  3509  3619 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
12-20 11:57:57.871  3509  3619 I PowerManagerService: Sleeping (uid 1000)...
,12-20 11:57:57.871  3509  3619 D PowerManagerService: [s] UserActivityState : 4 -> 0
12-20 11:57:57.871  3509  3619 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,12-20 11:57:57.881  3509  3924 D PersonaManagerService: onfinishedGoingToSleep why = 3
,12-20 11:57:57.881  3960  4432 D KeyguardViewMediator: onFinishedGoingToSleep(3)
12-20 11:57:57.881  3960  4432 D KeyguardViewMediator: notifyFinishedGoingToSleep
12-20 11:57:57.881  3509  3631 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
12-20 11:57:57.881  3960  3960 D KeyguardViewMediator: handleNotifyFinishedGoingToSleep
12-20 11:57:57.881  3960  3960 D KeyguardEffectViewController: onScreenTurnedOff
12-20 11:57:57.881  3960  3960 D KeyguardEffectViewController: ## mBackgroundView.onPause()
12-20 11:57:57.881  3960  3960 D KeyguardEffectViewLayered: onPause()
12-20 11:57:57.881  3960  3960 D SecKeyguardStatusView: onFinishedGoingToSleep() why=3
,12-20 11:57:57.881  3960  3960 V KeyguardFingerPrint: updateFingerprintListeningState(false)
,12-20 11:57:57.881  3960  3960 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
,12-20 11:57:57.881  3960  3960 V KeyguardUpdateMonitor: stopListeningForFingerprint()
,12-20 11:57:57.881  8550  8578 D BadgeProvider: query, [selection] : null
,12-20 11:57:57.891  3509  3509 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3509) 
,12-20 11:57:57.891  3509  3509 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=5) set On
,12-20 11:57:57.891  3509  3509 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
12-20 11:57:57.901  3509  3625 D LightsService: [SvcLED]  onSensorChanged::light value = 24
12-20 11:57:57.901  3509  3509 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
12-20 11:57:57.901  3509  3625 D SensorManager: unregisterListener ::   
,12-20 11:57:57.901  3509  3625 I LightsService: fileWriteInt : /sys/class/sec/led/led_lowpower  value : 0
12-20 11:57:57.901  3509  3625 D lights  : led_pattern : 5 +
12-20 11:57:57.901  3509  3509 D BatteryService: turn on LED for fully charged
,12-20 11:57:57.901  3509  3625 D lights  : led_pattern : 5 -
,12-20 11:57:57.901  3509  3625 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
12-20 11:57:57.901  3509  3625 V AlarmManager:  remove PendingIntent] PendingIntent{4ecf248: PendingIntentRecord{45ac606 android broadcastIntent}}
,12-20 11:57:57.901  4748  4748 D AODMissedEventController: [com.android.contacts] badgeCount : 0, [com.android.mms] badgeCount : 0
,12-20 11:57:57.911  4748  4748 I AODService.ClockTimer: startAlarm : TICK
,12-20 11:57:57.911  3509  4002 V AlarmManager: Add whitelist package alarm :PendingIntent{8879a46: PendingIntentRecord{cb26099 com.samsung.android.app.aodservice broadcastIntent}}
,12-20 11:57:57.921  4748  4748 I AODService.ClockTimer: startAlarm : SLEEP
,12-20 11:57:57.921  4748  4748 V AODService.ClockTimer: AOD Trigger: next AOD WAKEUP time is 9:0
,12-20 11:57:57.921  4748  4748 D AODService.ClockTimer: startAlarm is canceled. triggerAtMillis = -1, currentTime = 1482231477937
12-20 11:57:57.921  4748  4748 I AODService.ClockTimer: stopAlarm : WAKEUP
,12-20 11:57:57.921  3509  4333 V AlarmManager:  remove PendingIntent] PendingIntent{ae23407: PendingIntentRecord{d5689d1 com.samsung.android.app.aodservice broadcastIntent}}
12-20 11:57:57.921  4748  4748 D BatteryController: saveBatteryData : level[100], status[5]
,12-20 11:57:57.931  3018  3018 I SurfaceFlinger: id=28 createSurf (1x1),1 flag=404, BOD
,12-20 11:57:57.931  3509  3509 I CAE     : handleMessage(CaPowerManager.java:182) - AP_SLEEP
12-20 11:57:57.931  3509  4487 V WindowOrientationListener: setCurrentAppOrientation :5
,12-20 11:57:57.931  3509  3509 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_SLEEP
12-20 11:57:57.931  3509  4487 V WindowManager: rotationForOrientationLw(orient=5, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
12-20 11:57:57.931  3509  3509 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -46, 0,
12-20 11:57:57.931  3509  3509 D SensorHubManager: SendSensorHubData: send data = -76, 13, -46, 0
,12-20 11:57:57.931  3182  3222 D Sensorhubs: sendContextData: -76, 13, -46, 0
,12-20 11:57:57.931  3509  3509 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 10, 57, 57,
12-20 11:57:57.931  3509  3509 D SensorHubManager: SendSensorHubData: send data = -63, 14, 10, 57, 57
12-20 11:57:57.931  3182  7712 D Sensorhubs: sendContextData: -63, 14, 10, 57, 57
,12-20 11:57:57.941  3509  3509 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,12-20 11:57:57.941  4748  7100 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,12-20 11:57:57.951  3509  4441 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,12-20 11:57:57.951  3509  3842 D MotionRecognitionService: Screen off setAccIntStatus 
,12-20 11:57:57.951  3509  3842 E MotionRecognitionService:  handler : SCREEN_OFF end 
12-20 11:57:57.951  7178  7178 D SamsungIME: IMPL finishInput
12-20 11:57:57.951  7178  7178 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
12-20 11:57:57.951  7178  7178 D SamsungIME: saveAndClear +
12-20 11:57:57.951  7178  7178 D SamsungIME: saveAndClear -
12-20 11:57:57.951  3509  4002 W InputMethodManagerService: Starting input on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@b7b659c (uid=10069 pid=4328)
,12-20 11:57:57.951  7178  7178 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,12-20 11:57:57.961  3509  3815 I Sensors : #>LightSensor r=13 g=9 b=7 c=29 atime=245 again=64 lux=22
,12-20 11:57:57.961  3509  3615 V WindowAnimator: hide by NightClock Window{421530f u0 d0 StatusBar}
,12-20 11:57:57.961  3509  3615 V WindowAnimator: hide by NightClock Window{9ce7bae u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
,12-20 11:57:57.971  4748  4748 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,12-20 11:57:57.971  4748  4748 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,12-20 11:57:57.981  3509  4092 V WindowStateAnimator: Finishing drawing window Window{52bc621 u0 d0 AOD}: mDrawState=DRAW_PENDING
,12-20 11:57:57.991  3509  3509 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_OFF
,12-20 11:57:57.991  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:57:57.991  3960  3960 D PanelView: updateQsState
12-20 11:57:57.991  3960  3960 D KeyguardSwipeHelper: reset()
12-20 11:57:57.991  3960  3960 D KeyguardUnlockEventHandler: reset()
12-20 11:57:57.991  3960  3960 D KeyguardSwipeHelper: resetChildViewVI()
,12-20 11:57:58.001  3509  3593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2947934 u-1 com.samsung.settings.action.directaccess.CLOSE_DIALOG qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c83b918 8954:com.samsung.android.SettingsReceiver/1000}
,12-20 11:57:58.011  3509  3509 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
12-20 11:57:58.011  3509  3509 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
12-20 11:57:58.011  3509  3509 D UcmService: notifyChangeToPlugin event 16
12-20 11:57:58.011  3509  3509 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
12-20 11:57:58.011  3509  3509 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
12-20 11:57:58.011  3509  3509 D UcmService: notifying to unmanaged plugin
,12-20 11:57:58.011  4378  4418 E ucsBai_agentService: notifyChange NOT SUPPORTED
12-20 11:57:58.011  3509  3509 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
12-20 11:57:58.011  3509  3509 D UcmService: agentService status-0
12-20 11:57:58.011  3509  3509 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.ese:eSE Credential Storage Package name = com.samsung.ucs.agent.ese
12-20 11:57:58.011  3509  3509 D UcmService: notifying to managed plugin
12-20 11:57:58.011  3509  3509 D UcmService: checkIfNotify: Valid userid - 0
12-20 11:57:58.011  3509  3509 D PolicyManager: PolicyManager.isStorageEnabled() for userId = 0
12-20 11:57:58.011  3509  3509 D UniversalCredentialManagerService: checkCallerPermissionFor is called for method-isCredentialStorageManagedAsUser
12-20 11:57:58.011  3509  3509 D UniversalCredentialManagerService: isCredentialStorageManagedAsUser is called....
,12-20 11:57:58.011  3509  3509 D PolicyManager: PolicyManager.isStorageEnabled() result = false
12-20 11:57:58.011  3509  3509 D UcmService: agentService com.samsung.ucs.agent.ese:eSE Credential Storage not notified
12-20 11:57:58.011  3509  3509 D UcmService: agentService status-0
12-20 11:57:58.011  3509  3509 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
12-20 11:57:58.011  3509  3509 D UcmService: notifying to unmanaged plugin
,12-20 11:57:58.011  4396  4424 D BootAgentService: notifyChange eventId-16
12-20 11:57:58.011  3509  3509 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
12-20 11:57:58.011  3509  3509 D UcmService: agentService status--1
12-20 11:57:58.011  3509  3509 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,12-20 11:57:58.031  3509  3509 I WifiTrafficPoller: evaluateTrafficStatsPolling
,12-20 11:57:58.041  3509  3881 D WifiStateMachine: handleScreenStateChanged, screen off, set scan interval as max value  !!!
12-20 11:57:58.041  3509  3881 D WifiNative-wlan0: callSECApiVoid - ID [19]
,12-20 11:57:58.051  4152  4152 I wpa_supplicant: set PERIODIC_SCAN_INTERVAL_MAX to 128sec !!!
,12-20 11:57:58.051  3509  3509 D NotificationService: ACTION_SCREEN_OFF
,12-20 11:57:58.051  3509  3509 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3509) 
12-20 11:57:58.051  3509  3509 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=6) set Off
12-20 11:57:58.051  3509  3881 E WifiNative-wlan0: do suspend true
,12-20 11:57:58.051  3509  3509 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
12-20 11:57:58.051  3509  3509 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
12-20 11:57:58.051  3509  3625 D LightsService: [SvcLED]  onSensorChanged::light value = 22
12-20 11:57:58.051  3509  3509 D EdgeLight: Turning off
,12-20 11:57:58.061  3509  3625 D SensorManager: unregisterListener ::   
,12-20 11:57:58.061  3509  3625 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,12-20 11:57:58.061  3509  3625 V AlarmManager:  remove PendingIntent] PendingIntent{4ecf248: PendingIntentRecord{45ac606 android broadcastIntent}}
,12-20 11:57:58.061  4194  4204 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=112]
12-20 11:57:58.061  4194  4194 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.people.package_name=android, samsung.people.notification_type=led_indicator}]
,12-20 11:57:58.061  4194  4194 I PeopleStripeService: PeopleNotificationReceiver:3
12-20 11:57:58.081  3175  3878 D audio_hw_primary: adev_set_parameters: enter: kvpairs: screen_state=off
,12-20 11:57:58.081  4194  4194 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
,12-20 11:57:58.081  4194  4194 I PeopleDataManager: removeNotification
12-20 11:57:58.081  4194  4194 I NotificationParser: getNotiType:android,led_indicator
12-20 11:57:58.081  4194  4194 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=true,key=null,removeAll=false
12-20 11:57:58.081  4194  4194 D PeopleDataManager: removeNotiInfo =null
,12-20 11:57:58.091  3509  3509 I MdnieScenarioControlService: action  :  android.intent.action.SCREEN_OFF
,12-20 11:57:58.091  3509  3509 I FingerprintService: onReceive: android.intent.action.SCREEN_OFF
,12-20 11:57:58.101  3509  3509 I BackgroundCompactionService: Schedule Type1 BGCompaction
,12-20 11:57:58.101  3509  3509 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@4768910, Service = Activity Tracker, used = 0
12-20 11:57:58.101  3509  3509 D WifiService: ACTION_SCREEN_OFF, mSContextManager.unregisterListener !!
,12-20 11:57:58.101  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155651
12-20 11:57:58.101  3509  3509 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for ACTIVITY_TRACKER
12-20 11:57:58.101  3509  3509 V CAE     : stop(ContextProvider.java:155)
,12-20 11:57:58.101  3509  3509 V CAE     : clear(ActivityTrackerRunner.java:108)
12-20 11:57:58.101  3509  3509 V CAE     : disable(ActivityTrackerRunner.java:96)
,12-20 11:57:58.111  3509  3509 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 26, 0, 0, 0, 0, 0, 0, 0, 0,
,12-20 11:57:58.111  3509  3509 D SensorHubManager: SendSensorHubData: send data = -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
12-20 11:57:58.111  3182  3182 D Sensorhubs: sendContextData: -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
,12-20 11:57:58.121  3509  3509 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,12-20 11:57:58.121  3509  3509 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:57:58.131  3509  3509 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:57:58.131  3509  3509 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,12-20 11:57:58.131  3509  3509 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
12-20 11:57:58.131  3509  3509 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
12-20 11:57:58.131  3509  3509 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@14af07a, Service : DEVICE_PHYSICAL_CONTEXT_MONITOR(1)
12-20 11:57:58.131  3509  3509 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for ACTIVITY_TRACKER
12-20 11:57:58.131  3509  3509 D SContextService: 	.unregisterCallback : 2, client=
,12-20 11:57:58.131  3509  3509 D SContextService: ===== SContext Service List =====
12-20 11:57:58.131  3509  3509 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@a89c02b, Service : Device Physical Context Monitor
12-20 11:57:58.131  3509  3509 D SContextManager:   .unregisterListener : listener = com.android.server.wifi.WifiServiceImpl$11@b9d69d3, service=Activity Tracker
,12-20 11:57:58.141  3509  3815 I Sensors : #>LightSensor r=13 g=9 b=8 c=29 atime=245 again=64 lux=22
,12-20 11:57:58.141  3509  3615 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
,12-20 11:57:58.141  3509  3615 D IpRemoteDisplayController: Bridge Server is not available
,12-20 11:57:58.151  3509  3509 D NetworkPolicy: mScreenReceiver: ACTION_SCREEN_OFF, extra: 3
,12-20 11:57:58.151  3509  3879 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 3
12-20 11:57:58.151  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10009, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
12-20 11:57:58.151  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
12-20 11:57:58.151  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10065, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
,12-20 11:57:58.151  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10072, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
,12-20 11:57:58.161  3509  3589 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,12-20 11:57:58.181  4253  4253 D FusedLocationReceiver: BroadcastReceiver : ACTION_SCREEN_OFF
,12-20 11:57:58.191  4304  7219 D NfcService: call the applyRouting
,12-20 11:57:58.211  3960  4176 D NetworkController.MobileSignalController(0/2147483643): onDataActivity: direction=0
,12-20 11:57:58.231  4328  4328 D Launcher.Workspace: exitWidgetResizeMode. isClearResizeFrame is false
,12-20 11:57:58.281  5257  5257 D BtGatt.GattService: LCD turned off
12-20 11:57:58.281  5257  5430 D BtGatt.ScanManager: handleLcdOffIntent
12-20 11:57:58.281  5257  5430 D BtGatt.ScanManager: handleLcdOffIntent : thresholdScanValue is = 10 mLastConfiguredScanValue =0
,12-20 11:57:58.311  4607  9784 D MdnsClient: Multicast lock held. Releasing
,12-20 11:57:58.321  3509  3815 I Sensors : #>LightSensor r=12 g=9 b=7 c=29 atime=245 again=64 lux=24
,12-20 11:57:58.341  6319  6319 D CocktailBarUiController: ACTION_SCREEN_OFF
12-20 11:57:58.341  6319  6319 D AbstractCocktailPanelView: setPanelVisible: CocktailPortraitRemotePanelViewfalse will be hiden: 3
12-20 11:57:58.341  6319  6319 D CocktailBarPanelVisibilityManager: updateActivePanelView:  vis=false screenOn=false onTransit=false -hide: 3 current Active: 3
,12-20 11:57:58.341  6319  6319 E AbstractCocktailPanelView: notifyPanelVisibilityChanged: visibility not changed 2 id: 3
12-20 11:57:58.341  6319  6319 I TrayVisibilityController: handleMessage : msg.what = 1
,12-20 11:57:58.351  6319  6319 I Utils   : isCurrentUser current = 0, ownerId = 0
12-20 11:57:58.351  6319  6319 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
12-20 11:57:58.351  6319  6319 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 1
,12-20 11:57:58.351  6319  6319 D TrayStateController: putInputRect mDynamicInputRegion=188281550@LastEvent=t=1482231378082Rect(8, 0 - 64, 588),Rect=Rect(0, 0 - 0, 0)
,12-20 11:57:58.351  4194  4194 D PeopleStripeService: ACTION_SCREEN_OFF
12-20 11:57:58.351  4194  4194 D PeopleStripeManager: requestCloseCircleViews()
12-20 11:57:58.351  4194  4194 I CircleImageSaveLayout: hideImageSaveLayout()
,12-20 11:57:58.351  4194  4194 D CircleImageSaveLayout: releaseWakeLock()
12-20 11:57:58.351  4194  4194 D SweepImageListView: hide
12-20 11:57:58.351  4194  4194 D SweepImageListView: setAdapter mAdapter =null:159137937
,12-20 11:57:58.351  4194  4194 I PeopleEdgeCommContainer: hideEffectView() 
,12-20 11:57:58.351  4194  4194 I CirclePokingManager: stopParticleEffectView  mParticleEffectView-null
12-20 11:57:58.351  3509  3905 I AbsCocktailBarStatePolicy: handleMessage: entry what = 1
12-20 11:57:58.351  4194  4194 I PeopleDataManager: deleteMarkedCircleEvent : people = null
12-20 11:57:58.351  4194  4194 I PeopleEdgeCommContainer: setPeopleChannelShowStatus false
12-20 11:57:58.351  4194  4194 I PeopleStripeWindow: updateWindowParam : minimize=true,mLastMinimized=true,color0 blur true
12-20 11:57:58.351  6319  6319 D TrayStateController: setUiState: 0 --> 2
,12-20 11:57:58.361  4194  4194 D PeopleStripeVisibilityController: setEmoHistory enable=false
,12-20 11:57:58.361  4194  4194 I PeopleStripeVisibilityController: getComputedTrayVisible : keyguardState = 1
12-20 11:57:58.361  4194  4194 I PeopleStripeVisibilityController: isVisibleByAlwaysOn : mState = 1
12-20 11:57:58.361  4194  4194 E PeopleStripeProcessMonitor: getTopActivity : MultiWindowFacade.taskList = []
,12-20 11:57:58.361  4194  4194 I PeopleStripeProcessMonitor: isPeopleStripeTask packageName = com.sec.android.app.launcher 0
,12-20 11:57:58.361  4194  4194 E PeopleStripeProcessMonitor: getTopActivity : MultiWindowFacade.taskList = []
,12-20 11:57:58.361  4194  4194 I PeopleStripeVisibilityController: updateStripeVisible : State 1 visible = 1
12-20 11:57:58.361  4194  4194 I PeopleStripeManager: isExistVisibleHandler false
12-20 11:57:58.361  4194  4194 I PeopleStripeManager: showStripe Not exist noti handler.
12-20 11:57:58.361  4194  4194 I PeopleStripeManager: hideStripe
,12-20 11:57:58.361  4194  4194 D PeopleStripeManager: onVisibilityChanged : 2
,12-20 11:57:58.361  4194  4194 D PeopleStripeVisibilityController: setHiddenEdgePanel enable=true
12-20 11:57:58.361  4194  4194 I PeopleStripeVisibilityController: updateStripeVisible : State 1028 visible = 2
12-20 11:57:58.361  4194  4194 I PeopleStripeManager: hideStripe
,12-20 11:57:58.371  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 258, CUR = 128, LCD = 0
,12-20 11:57:58.381  3018  3030 D libEGL  : eglTerminate EGLDisplay = 0x7fa983ee78
,12-20 11:57:58.381  3018  3030 I SurfaceFlinger: id=26 Removed DocktailBar (8/12)
,12-20 11:57:58.381  3018  3112 I SurfaceFlinger: id=26 Removed DocktailBar (-2/12)
,12-20 11:57:58.391  3509  3509 I SurveyLogManager: mDeviceInfo.mScreen = false
,12-20 11:57:58.391  6319  6319 D CocktailBarUiController: onCocktailBarStateChanged: flag=0x1 vis=2 bgType=0 showTimeout=-1 activate=true
,12-20 11:57:58.391  3509  6576 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-20 11:57:58.401  3018  3018 D libEGL  : eglTerminate EGLDisplay = 0x7fff7e5bd8
,12-20 11:57:58.411  7178  7178 E SamsungIME: invoke(): method is null
,12-20 11:57:58.431  8617  8655 I SystemBroadcastReceiver: [#CMH#] Received broadcast 
12-20 11:57:58.431  8617  8655 I PolicyManager: [#CMH#] onReceive action = EVENT_SCREEN_OFF
12-20 11:57:58.431  8617  8655 I SystemBroadcastReceiver: [#CMH#] onReceive completed 
,12-20 11:57:58.441  8428  8428 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDA0E41DE4F26DD020CF7906DED0A6ECA9F]}
,12-20 11:57:58.441  8428  8428 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB71D02215B774510884CB3BFD0FBDB0EDC]}
,12-20 11:57:58.441  8428  8428 D [WeatherWidget(1240)]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-20 11:57:58.451  3509  3924 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,12-20 11:57:58.461  8428  8428 D [WeatherWidget(1240)]  WeatherService: {[44BE909F148A112BE24DB9207B7094FCDA9342562AE17780A60BEC6E95DC6F0D]}
,12-20 11:57:58.471  4748  4748 I AlpmModeManager: startAlpmMode : state  = IDLE
,12-20 11:57:58.471  4748  4748 I AlpmModeManager: handleUnblankDisplay: state  = IDLE
12-20 11:57:58.471  4748  4748 V AlpmModeManager: handleUnblankDisplay: setDoze [DISPLAY_STATE_DOZE]
12-20 11:57:58.471  4748  4748 D AlpmModeManager: getLastAlpmHlpmBright : HighNit[true], AlpmHlpm[1], NitMode[[ALPM]_60NIT_ON]
,12-20 11:57:58.471  3509  4977 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = 3, screenState = 3, Brightness = 0, wakefulness = false
12-20 11:57:58.471  3509  4977 D PowerManagerService: [s] UserActivityState : 0 -> 4
12-20 11:57:58.471  4748  4748 I AlpmModeManager: handleUnblankDisplay: AlpmModeManager wakeLock [ACQUIRE]
,12-20 11:57:58.471  3509  3791 D PowerManagerService: [api] acquire WakeLock flags=0x40 tag=AlpmModeManager uid=10000 pid=4748
12-20 11:57:58.471  3509  3791 I libsuspend: !@autosuspend_wakeup_count_disable
12-20 11:57:58.471  3509  3791 D PowerManagerService: mDisplayReady: false
12-20 11:57:58.471  3509  3791 I libsuspend: !@autosuspend_wakeup_count_disable done
12-20 11:57:58.471  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-20 11:57:58.471  3509  3791 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,12-20 11:57:58.471  3509  3619 D DisplayPowerState: !@ [0] ColorFade exit
12-20 11:57:58.471  3509  3619 D PowerManagerService: [input device light] onColorFadeExit(true)
,12-20 11:57:58.471  3018  3030 D libEGL  : eglTerminate EGLDisplay = 0x7fa983ee78
12-20 11:57:58.471  3018  3030 D libEGL  : eglTerminate EGLDisplay = 0x7fa983ee78
,12-20 11:57:58.481  3018  3028 I SurfaceFlinger: id=27 Removed DolorFade (9/11)
,12-20 11:57:58.481  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-20 11:57:58.481  3509  9785 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,12-20 11:57:58.481  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:57:58.481  3018  4509 I SurfaceFlinger: id=27 Removed DolorFade (-2/11)
12-20 11:57:58.481  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:57:58.481  3018  3018 D libEGL  : eglTerminate EGLDisplay = 0x7fff7e5bd8
12-20 11:57:58.481  3509  3619 D DisplayPowerState: Requesting new screen state: [0] state=DOZE, backlight (By colorFade)=0
12-20 11:57:58.481  3509  9785 D BluetoothAdapter: STATE_ON
,12-20 11:57:58.481  3509  3927 D DisplayPowerState: Updating screen state [0]: state=DOZE, backlight (by ColorFade)=0
12-20 11:57:58.481  3509  3626 D DisplayManagerService: !@display_state: OFF -> DOZE brightness: 0 -> 0
12-20 11:57:58.481  3509  3615 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
12-20 11:57:58.481  3509  3615 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,12-20 11:57:58.491  3509  3927 D lights  : lcd : 1 +
12-20 11:57:58.491  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-20 11:57:58.491  3509  3927 D lights  : lcd : 1 -
12-20 11:57:58.491  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-20 11:57:58.491  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:57:58.491  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:58.491  3018  3018 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa9d43c00
12-20 11:57:58.491  3018  3018 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,12-20 11:57:58.501  6319  6319 E CocktailBarPositionManager: Window direction: 0
12-20 11:57:58.501  6319  6319 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-20 11:57:58.501  3509  4487 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:57:58.511  3509  4002 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:57:58.521  3509  4007 V AlarmManager:  remove PendingIntent] PendingIntent{16409a3: PendingIntentRecord{d3aceb1 com.android.bluetooth broadcastIntent}}
,12-20 11:57:58.521  3509  4486 V AlarmManager:  remove PendingIntent] PendingIntent{999f4a0: PendingIntentRecord{d3aceb1 com.android.bluetooth broadcastIntent}}
,12-20 11:57:58.531  4748  4748 D DefaultClockView: Start AOD Enter Animation
,12-20 11:57:58.531  3509  3531 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:57:58.541  3509  3530 V WindowStateAnimator: Finishing drawing window Window{9ce7bae u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: mDrawState=HAS_DRAWN
,12-20 11:57:58.551  3509  4333 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:57:58.551  3509  9785 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,12-20 11:57:58.591  3509  9785 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,12-20 11:57:58.601  3509  9785 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,12-20 11:57:58.641  4060  4060 D Recents : onTaskStackChanged
,12-20 11:57:58.661  4194  4194 I PeopleStripeManager: isExistVisibleHandler false
,12-20 11:57:58.661  4194  4194 I PeopleStripeManager: hideStripe
,12-20 11:57:58.691  3509  9785 I BatteryStatsDumper: Writing to database completed
,12-20 11:57:58.701  3509  3509 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509 (0x0)
,12-20 11:57:58.721  3509  3626 D SurfaceControl: Excessive delay in setPowerMode(): 237ms
,12-20 11:57:58.731  3509  3626 D PowerManagerUtil: Excessive delay in !@display_state: DOZE: 238ms
12-20 11:57:58.731  3509  3626 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 239ms
12-20 11:57:58.731  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-20 11:57:58.731  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable
12-20 11:57:58.731  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,12-20 11:57:58.731  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable done
12-20 11:57:58.731  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:57:58.731  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
12-20 11:57:58.731  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:58.731  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-20 11:57:58.731  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,12-20 11:57:58.731  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:57:58.731  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:57:58.731  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:57:58.731  3509  3619 D PowerManagerService: mDisplayReady: true
12-20 11:57:58.731  3509  3619 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-20 11:57:58.741  3509  4092 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:57:58.741  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:57:58.741  4748  4748 I AlpmModeManager: handleAlpmModeOn: state  = UNBLANK
12-20 11:57:58.741  4748  4748 D DefaultClockView: End AOD Enter Animation : ForceStopAnimation : false
12-20 11:57:58.741  4748  4748 D AODService: : state = Start AOD mode!!
,12-20 11:57:58.741  3509  3530 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:57:58.751  4748  4748 D BatteryMeterView: onDraw batteryColor : -986896
,12-20 11:57:58.761  3509  4436 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:57:58.911  3509  3509 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509 (0x0)
,12-20 11:57:59.051  4748  4748 I AlpmModeManager: handleBlankDisplay: current state [ALPM_ON] to [ALPM_STATE_BLANK]
,12-20 11:57:59.051  4748  4748 V AlpmModeManager: handleBlankDisplay: setDoze [DISPLAY_STATE_DOZE_SUSPEND] Keep bright
12-20 11:57:59.051  3509  4441 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
12-20 11:57:59.051  3509  4441 I libsuspend: !@autosuspend_wakeup_count_disable
,12-20 11:57:59.051  3509  4441 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
12-20 11:57:59.051  3509  4441 I libsuspend: !@autosuspend_wakeup_count_disable done
,12-20 11:57:59.051  3509  4441 D PowerManagerService: mDisplayReady: false
12-20 11:57:59.051  3018  3018 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa9d43c00
12-20 11:57:59.051  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-20 11:57:59.051  3018  3018 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,12-20 11:57:59.051  3509  4441 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-20 11:57:59.051  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-20 11:57:59.051  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:57:59.051  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:59.051  3509  3626 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1,
12-20 11:57:59.051  3509  3615 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
12-20 11:57:59.051  3509  3615 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-20 11:57:59.071  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-20 11:57:59.071  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-20 11:57:59.071  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:57:59.071  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable
12-20 11:57:59.071  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:57:59.071  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable done
12-20 11:57:59.071  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-20 11:57:59.071  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-20 11:57:59.071  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:57:59.071  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:57:59.071  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:57:59.071  3509  3619 D PowerManagerService: mDisplayReady: true
,12-20 11:57:59.071  3509  3619 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-20 11:57:59.091  6319  6319 E CocktailBarPositionManager: Window direction: 0
12-20 11:57:59.091  6319  6319 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-20 11:57:59.451  3509  6577 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,12-20 11:57:59.461  3509  3593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2d61859 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f4a898 9646:com.samsung.android.sm.provider/1000}
,12-20 11:57:59.991  3509  3836 V AlarmManager: Expired Alarm result :8
,12-20 11:58:00.911  3509  3836 V AlarmManager: Expired Alarm result :4
,12-20 11:58:00.911  3509  3836 V AlarmManager: Send whitelist package alarm :PendingIntent{8879a46: PendingIntentRecord{cb26099 com.samsung.android.app.aodservice broadcastIntent}}
,12-20 11:58:00.911  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,12-20 11:58:00.921  3960  3960 D KeyguardUpdateMonitor: handleTimeUpdate
,12-20 11:58:00.931  3960  3960 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-20 11:58:01.031  3960  3960 D DateView: received broadcast android.intent.action.TIME_TICK
,12-20 11:58:01.061  4748  4748 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
12-20 11:58:01.061  4748  4748 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
,12-20 11:58:01.061  3509  4977 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:58:01.061  3509  4977 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
12-20 11:58:01.061  3509  4977 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
12-20 11:58:01.061  3509  4977 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
12-20 11:58:01.071  3182  3222 D Sensorhubs: sendContextData: -72, 56, 1, 1
,12-20 11:58:01.071  3509  4977 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,12-20 11:58:01.071  3509  4977 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-20 11:58:01.071  3509  4977 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
12-20 11:58:01.081  4748  4748 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@de2fb91, service=Device Physical Context Monitor
12-20 11:58:01.081  4748  4748 I AlpmModeManager: startAlpmMode : state  = BLANK
12-20 11:58:01.081  4748  4748 D DefaultClockView: Window showed. Time views updating
,12-20 11:58:01.081  3509  4434 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
12-20 11:58:01.081  3509  4434 I libsuspend: !@autosuspend_wakeup_count_disable
,12-20 11:58:01.081  3509  4434 D PowerManagerService: mDisplayReady: false
,12-20 11:58:01.081  3509  4434 I libsuspend: !@autosuspend_wakeup_count_disable done
12-20 11:58:01.081  3509  4434 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,12-20 11:58:01.081  4748  4748 D AODUpdatePositionController: updatePosition: direction[2] updatePosition: X[-10] Y[888] NewPositionTimer[59]
12-20 11:58:01.081  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
,12-20 11:58:01.081  4748  4748 D DefaultClockView: LocalTime Pattern : HH:mm
12-20 11:58:01.081  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-20 11:58:01.081  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-20 11:58:01.081  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:58:01.081  3509  3626 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
12-20 11:58:01.081  3509  3615 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
,12-20 11:58:01.081  3509  3615 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
12-20 11:58:01.081  4748  4748 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 11:58 time02: null ampm: null
,12-20 11:58:01.081  3018  3018 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa9d43c00
12-20 11:58:01.081  3018  3018 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,12-20 11:58:01.091  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-20 11:58:01.091  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-20 11:58:01.091  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:58:01.091  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable
12-20 11:58:01.091  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:58:01.091  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable done
12-20 11:58:01.091  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=3
12-20 11:58:01.091  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
12-20 11:58:01.091  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:58:01.091  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:58:01.091  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:58:01.091  3509  3619 D PowerManagerService: mDisplayReady: true
12-20 11:58:01.091  3509  3619 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-20 11:58:01.101  6319  6319 E CocktailBarPositionManager: Window direction: 0
12-20 11:58:01.101  6319  6319 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-20 11:58:01.101  4748  4748 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,12-20 11:58:01.101  4748  4748 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
,12-20 11:58:01.101  4748  4748 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:wt., 20 gru 11:58
,12-20 11:58:01.101  4748  4748 I AODService.ClockTimer: startAlarm : TICK
12-20 11:58:01.101  3509  4436 V AlarmManager: Add whitelist package alarm :PendingIntent{cc6e115: PendingIntentRecord{cb26099 com.samsung.android.app.aodservice broadcastIntent}}
,12-20 11:58:01.101  4748  4748 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
,12-20 11:58:01.101  4748  4748 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
12-20 11:58:01.101  3509  4092 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
12-20 11:58:01.101  3509  4092 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,12-20 11:58:01.101  3509  4002 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:58:01.111  4748  4748 D DefaultClockView: RootView invalidate()
,12-20 11:58:01.111  3509  4485 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509
,12-20 11:58:01.141  3182  3221 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
,12-20 11:58:01.141  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
,12-20 11:58:01.141  3509  3838 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 10, 58, 1,
12-20 11:58:01.141  3509  3838 D SensorHubManager: SendSensorHubData: send data = -63, 14, 10, 58, 1
12-20 11:58:01.141  3182  7712 D Sensorhubs: sendContextData: -63, 14, 10, 58, 1
,12-20 11:58:01.141  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
,12-20 11:58:01.141  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
12-20 11:58:01.141  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
,12-20 11:58:01.141  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
12-20 11:58:01.141  3509  3838 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
,12-20 11:58:01.141  3509  3841 D SContextService: updateSContext() : event = Device Physical Context Monitor
,12-20 11:58:01.141  4748  4748 I AODService: onSContextChanged: AODScreenShown state is already true
,12-20 11:58:01.271  3509  3509 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3509 (0x0)
,12-20 11:58:01.271  3509  3509 I libsuspend: !@autosuspend_wakeup_count_disable
12-20 11:58:01.271  3509  3509 D PowerManagerService: mDisplayReady: false
12-20 11:58:01.271  3509  3509 I libsuspend: !@autosuspend_wakeup_count_disable done
,12-20 11:58:01.271  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-20 11:58:01.271  3509  3509 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-20 11:58:01.271  3018  3018 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa9d43c00
12-20 11:58:01.271  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-20 11:58:01.271  3018  3018 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,12-20 11:58:01.271  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:58:01.271  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:58:01.271  3509  3626 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
12-20 11:58:01.271  3509  3615 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
,12-20 11:58:01.271  3509  3615 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,12-20 11:58:01.301  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-20 11:58:01.301  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-20 11:58:01.301  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:58:01.301  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable
12-20 11:58:01.301  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:58:01.301  3509  3619 I libsuspend: !@autosuspend_wakeup_count_enable done
12-20 11:58:01.301  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=4
12-20 11:58:01.301  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
12-20 11:58:01.301  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,12-20 11:58:01.301  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:58:01.301  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:58:01.301  3509  3619 D PowerManagerService: mDisplayReady: true
,12-20 11:58:01.301  3509  3619 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,12-20 11:58:01.311  6319  6319 E CocktailBarPositionManager: Window direction: 0
12-20 11:58:01.311  6319  6319 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-20 11:58:02.251  3509  3836 V AlarmManager: Expired Alarm result :4
,12-20 11:58:02.251  3960  3960 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 4, mDelayedShowingSequence = 4
,12-20 11:58:02.261  3960  3960 D FactoryTest: checkAutomationTestOption() : option=0
,12-20 11:58:02.261  3960  3960 D FactoryTest: checkAutomationTestOption() : mode_screenlock=0
,12-20 11:58:02.261  3960  3960 D KeyguardViewMediator: doKeyguard: showing the lock screen
12-20 11:58:02.261  3960  3960 D KeyguardViewMediator: showLocked
,12-20 11:58:02.271  3960  3960 D KeyguardViewMediator: handleShow
,12-20 11:58:02.271  3960  3960 E KeyguardViewMediator: setShowingLocked mShowing = true
,12-20 11:58:02.271  3960  3960 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
12-20 11:58:02.271  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,12-20 11:58:02.271  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
12-20 11:58:02.271  3960  3960 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
,12-20 11:58:02.281  3960  3960 D KeyguardEffectViewController: setKeyguardShowing = true
,12-20 11:58:02.281  3960  3960 D KeyguardEffectViewController: mShowing=true, mOccluded=false, mKeyguardFadingAway=false, match_parent=false
12-20 11:58:02.281  3960  3960 D StatusBarKeyguardViewManager: showBouncerOrKeyguard
,12-20 11:58:02.291  3960  3960 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.KeyguardHostView$1@928eb05
,12-20 11:58:02.291  3960  3960 V KeyguardUpdateMonitor: *** unregister callback for null
,12-20 11:58:02.291  3960  3960 D KeyguardSecurityPolicyUtils: MDM is not enabled...
,12-20 11:58:02.291  3960  3960 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.KeyguardSecurityContainer$1@8e5c75a
12-20 11:58:02.291  3960  3960 V KeyguardUpdateMonitor: *** unregister callback for null
,12-20 11:58:02.301  3960  3960 D KeyguardSecurityModel: getSecurityMode( getActivePasswordQuality = 0 , currentuser = 0
,12-20 11:58:02.301  3960  3960 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=false)
12-20 11:58:02.301  3960  3960 D KeyguardSecurityView: showSecurityScreen(None)
12-20 11:58:02.301  3960  3960 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
,12-20 11:58:02.301  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:58:02.301  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
12-20 11:58:02.301  3960  3960 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
,12-20 11:58:02.311  3960  3960 D KeyguardSecurityModel: getSecurityMode( getActivePasswordQuality = 0 , currentuser = 0
,12-20 11:58:02.311  3960  3960 D PhoneStatusBar: showKeyguard
12-20 11:58:02.311  3960  3960 D PhoneStatusBar: setBarState: state - 1
12-20 11:58:02.311  3960  3960 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
12-20 11:58:02.311  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:58:02.311  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
12-20 11:58:02.311  3960  3960 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
,12-20 11:58:02.311  3960  3960 I PhoneStatusBar: updateKeyguardState 0 to 1
,12-20 11:58:02.321  3960  3960 D PanelView: updateQsState
,12-20 11:58:02.321  3960  3960 D KeyguardSwipeHelper: reset()
12-20 11:58:02.321  3960  3960 D KeyguardUnlockEventHandler: reset()
12-20 11:58:02.321  3960  3960 D KeyguardSwipeHelper: resetChildViewVI()
,12-20 11:58:02.321  3960  3960 D StatusBar: LSSN:1
,12-20 11:58:02.321  3960  3960 E LSO     : LSO Service is not yet ready!!!
,12-20 11:58:02.321  3960  3960 D PanelView: setKeyguardBottomAreaVisibility() prevState=0, newState - 1 goingToShade - false
,12-20 11:58:02.331  3960  3960 D PhoneStatusBar/KeyguardBottomAreaView: updateCameraVisibility isCameraDisabledByDpm=false
,12-20 11:58:02.331  3960  3960 V KeyguardBottomAreaShortcutView: updateLeftPreview
,12-20 11:58:02.331  3960  3960 V KeyguardBottomAreaShortcutView: updateRightPreview
12-20 11:58:02.331  3960  4175 V KeyguardBottomAreaShortcutView: updateLeftPreview - mLeftAffordanceView
,12-20 11:58:02.331  3960  3960 D KeyguardCircleAffordanceView: setPreviewView: mRight=false,preview=android.widget.RelativeLayout{aff2dbc I.E...... ......ID 0,0-1440,2560}
,12-20 11:58:02.341  3960  4175 V PreviewInflater: switching default dialer action
,12-20 11:58:02.381  3960  3960 D KeyguardCircleAffordanceView: setPreviewView: mRight=true,preview=android.widget.AbsoluteLayout{9fdf145 I.E...... ......ID 0,0-1440,2560}
,12-20 11:58:02.391  3960  4175 V KeyguardBottomAreaShortcutView: updateRightPreview - mRightAffordanceView
12-20 11:58:02.391  3960  4175 D ShortcutManager: th = 1 is camera package
,12-20 11:58:02.391  3960  3960 D PanelView: updateQsState
,12-20 11:58:02.401  3960  3960 D NotificationStackScrollLayout:  scroll range should be extended : 884
,12-20 11:58:02.401  3960  4175 V PreviewInflater: switching default camera action
,12-20 11:58:02.411  3960  3960 D KeyguardSecurityModel: getSecurityMode( getActivePasswordQuality = 0 , currentuser = 0
,12-20 11:58:02.411  3960  3960 D PhoneStatusBar: Make expanded visible: expanded visible=false
12-20 11:58:02.411  3960  3960 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
12-20 11:58:02.411  3960  3960 D PhoneStatusBar: adjustDisableFlags:false, false, true, false, false, 1
12-20 11:58:02.411  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:58:02.411  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : true keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
12-20 11:58:02.411  3960  3960 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
,12-20 11:58:02.411  3960  3960 D PhoneStatusBar: disable: < expand ICONS* alerts SYSTEM_INFO* back home recent clock search quick_settings >
,12-20 11:58:02.421  3960  3960 D PhoneStatusBar: Make expanded visible: expanded visible=true
12-20 11:58:02.421  6319  6319 I TrayVisibilityController: TrayStateVisibilityReceiver action :com.samsung.systemui.statusbar.ANIMATING
12-20 11:58:02.421  3960  3960 D StatusBar.BrightnessController: setListening  = true
,12-20 11:58:02.421  3960  3960 D KeyguardEffectViewLayered: reset()
12-20 11:58:02.421  3960  3960 D KeyguardEffectViewLayered: init()
12-20 11:58:02.421  3960  3960 D KeyguardEffectViewLayered: mViewWidth = 1440, mViewHeight = 96
12-20 11:58:02.421  3960  3960 D KeyguardEffectViewLayered: mBitmapImageList size = 3
12-20 11:58:02.421  3960  3960 D KeyguardEffectViewLayered: DENSITY = 1.0
,12-20 11:58:02.421  3960  3960 D PhoneStatusBar/KeyguardBottomAreaView: updateCameraVisibility isCameraDisabledByDpm=false
12-20 11:58:02.421  3960  3960 D KeyguardViewBase: show()
,12-20 11:58:02.431  3960  3960 D KeyguardSecurityModel: getSecurityMode( getActivePasswordQuality = 0 , currentuser = 0
12-20 11:58:02.431  3960  3960 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=false)
12-20 11:58:02.431  3960  3960 D KeyguardSecurityView: showSecurityScreen(None)
,12-20 11:58:02.431  3960  3960 D KeyguardUpdateMonitor: onKeyguardVisibilityChanged(true)
,12-20 11:58:02.441  3960  3960 V KeyguardFingerPrint: updateFingerprintListeningState(false)
,12-20 11:58:02.441  3960  3960 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
12-20 11:58:02.441  3960  3960 V KeyguardUpdateMonitor: stopListeningForFingerprint()
,12-20 11:58:02.451  3960  3960 D KeyguardViewMediator: adjustStatusBarLocked: mShowing=true mOccluded=false isSecure=false --> flags=0x3200000
,12-20 11:58:02.451  3509  4333 D StatusBarManagerService: manageDisableList userId=0 what=0x3200000 pkg=com.android.systemui
,12-20 11:58:02.451  3509  4434 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 390894
,12-20 11:58:02.451  3960  3960 D KeyguardViewMediator: onSdpLocked :: Inside...
,12-20 11:58:02.451  3960  3960 D KeyguardViewMediator: isPwdChangeRequested :: false
12-20 11:58:02.451  3960  3960 D KeyguardViewMediator: onSdpLocked :: Lock SDP for User 0
,12-20 11:58:02.451  3960  3960 V KeyguardDisplayManager: show (false)
,12-20 11:58:02.451  3509  3530 E SdpServiceKeeper: isLicensed {pid:3960 uid:10065 userid:0 doPkg:null}
,12-20 11:58:02.451  3509  3530 E SdpServiceKeeper: System app. Skip license activation
,12-20 11:58:02.461  3509  4436 E SdpServiceKeeper: isLicensed {pid:3960 uid:10065 userid:0 doPkg:null}
12-20 11:58:02.461  3509  4436 E SdpServiceKeeper: System app. Skip license activation
,12-20 11:58:02.461  3509  4977 D SdpManagerService: lockInternal 0
,12-20 11:58:02.461  3509  4977 E SDP.CRYPTO:     On Locked OK, id 0
12-20 11:58:02.461  3509  4977 D SdpManagerService: clearCachedMasterKey (CMK) 0
12-20 11:58:02.461  3509  4977 E SdpManagerService: sendBroadcastAsUser(INTENT_SDP_STATE_CHANGED, state:1)
,12-20 11:58:02.461  3960  9787 D KeyguardViewMediator: lockSdp :: Lock SDP Successful...!
,12-20 11:58:02.471  3509  3593 V BroadcastQueue: [foreground] Process cur broadcast BroadcastRecord{d9120f6 u0 com.sec.sdp.SDP_STATE_CHANGED qIdx=2}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{56c7d71 9501:com.sec.android.app.sbrowser/u0a141}
,12-20 11:58:02.471  3509  4487 E SdpServiceKeeper: isLicensed {pid:9501 uid:10141 userid:0 doPkg:null}
12-20 11:58:02.471  3509  4487 E SdpServiceKeeper: White listed. Skip license activation
,12-20 11:58:02.471  9501  9501 E SdpStateChangedReceiver: com.sec.enterprise.knox.sdp.exception.SdpEngineNotExistsException
,12-20 11:58:02.481  3018  3112 D libEGL  : eglTerminate EGLDisplay = 0x7fa33fee78
12-20 11:58:02.481  3018  3112 D libEGL  : eglTerminate EGLDisplay = 0x7fa33fee78
,12-20 11:58:02.481  3960  4161 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,12-20 11:58:02.481  3960  3960 D KeyguardEffectViewController: onLayoutChange() v: com.android.keyguard.effect.EffectBehindView{eefe3f3 I.E...... ......ID 0,0-1440,2560 #7f0e0330 app:id/keyguard_effect_behind}, bottom : 2560, oldBottom : 96
12-20 11:58:02.481  3960  3960 D KeyguardEffectViewController: mShowing=true, mOccluded=false, mKeyguardFadingAway=false, match_parent=true
,12-20 11:58:02.481  3960  3960 D NotificationStackScrollLayout:  scroll range should be extended : 884
,12-20 11:58:02.491  3960  3960 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
12-20 11:58:02.491  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:58:02.491  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : true keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
12-20 11:58:02.491  3960  3960 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
,12-20 11:58:02.611  3509  3530 V WindowStateAnimator: Finishing drawing window Window{421530f u0 d0 StatusBar}: mDrawState=DRAW_PENDING
,12-20 11:58:02.611  3960  3960 D KeyguardCircleAffordanceView: setPreviewView: mRight=false,preview=android.widget.RelativeLayout{efafe68 I.E...... ......ID 0,0-0,0}
12-20 11:58:02.611  3960  3960 V KeyguardBottomAreaShortcutView: mLeftAffordanceView preview = android.widget.RelativeLayout{efafe68 I.E...... ......ID 0,0-0,0}
12-20 11:58:02.611  3960  3960 D KeyguardCircleAffordanceView: setPreviewView: mRight=true,preview=android.widget.AbsoluteLayout{6d23281 I.E...... ......ID 0,0-0,0}
12-20 11:58:02.611  3960  3960 V KeyguardBottomAreaShortcutView: mRightAffordanceView preview = android.widget.AbsoluteLayout{6d23281 I.E...... ......ID 0,0-0,0}
12-20 11:58:02.611  3960  3960 D KeyguardUpdateMonitor: handleKeyguardReset
12-20 11:58:02.611  3960  3960 V KeyguardFingerPrint: updateFingerprintListeningState(false)
,12-20 11:58:02.621  3960  3960 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
,12-20 11:58:02.621  3960  3960 V KeyguardUpdateMonitor: stopListeningForFingerprint()
,12-20 11:58:02.621  3960  3960 D PhoneStatusBar: adjustDisableFlags:false, false, true, false, false, 1
,12-20 11:58:02.621  3960  3960 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO back HOME* RECENT* clock SEARCH* quick_settings >
,12-20 11:58:02.621  3960  3960 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,12-20 11:58:02.641  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:58:02.641  3018  3018 D libEGL  : eglTerminate EGLDisplay = 0x7fff7e5b48
,12-20 11:58:02.661  3960  3960 D KeyguardEffectViewController: onLayoutChange() v: com.android.keyguard.effect.EffectBehindView{eefe3f3 V.E...... ......I. 0,0-1440,2560 #7f0e0330 app:id/keyguard_effect_behind}, bottom : 2560, oldBottom : 2560
,12-20 11:58:02.691  3509  4007 V WindowStateAnimator: Finishing drawing window Window{421530f u0 d0 StatusBar}: mDrawState=READY_TO_SHOW
,12-20 11:58:02.691  3960  3960 D Recents : handleProxyCall type=3
,12-20 11:58:02.691  4060  4060 D Recents : handleProxyCall type=3
,12-20 11:58:02.701  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:58:02.741  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:58:04.681  3509  6631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-20 11:58:08.421  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 258, CUR = 128, LCD = 1
,12-20 11:58:10.991  3509  3850 D InputReader: Input event(5): value=1 when=399430481000
12-20 11:58:10.991  3509  3850 D InputReader: !@notifyKey(172), action=0
12-20 11:58:10.991  3509  3850 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=0, interactive=false
,12-20 11:58:10.991  3509  3850 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1144000  uid : 1000  pid : 3509  pkgName : WAKEUP_BOOSTER@34
,12-20 11:58:11.001  3509  3850 E SamsungWindowManager: mCoreNumLockHelper.acquire
12-20 11:58:11.001  3509  3850 D CustomFrequencyManagerService: requestCPUCore:: CPUCore value is not in the permitted range. CoreNum = 2
12-20 11:58:11.001  3509  3850 D InputManager-JNI: setInteractive(true)
12-20 11:58:11.001  3509  3850 D PowerManagerService: [api] [s] wakeUpWithReason (uid: 1000 pid: 3509) eventTime = 399430 event = 1
12-20 11:58:11.001  3509  3850 I PowerManagerService: !@[ps] Screen__On  - 4 :  wakeUpWithReason: 1 (uid: 1000 pid: 3509) (1)
12-20 11:58:11.001  3509  3850 I PowerManagerService: Waking up from dozing (uid 1000)...
12-20 11:58:11.001  3509  3850 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
12-20 11:58:11.001  3509  3850 D PowerManagerService: [s] UserActivityState : 4 -> 1
12-20 11:58:11.001  3509  3850 I libsuspend: !@autosuspend_wakeup_count_disable
12-20 11:58:11.001  3509  3924 D NetworkPolicy: onScreenStateChanged, state: true, reason: 2
12-20 11:58:11.001  3509  3850 I libsuspend: !@autosuspend_wakeup_count_disable done
12-20 11:58:11.001  3509  3850 D PowerManagerService: mDisplayReady: false
12-20 11:58:11.001  3509  3850 D InputManager-JNI: !@handleInterceptActions(172), action=0, wmActions=0
12-20 11:58:11.001  3509  3850 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
12-20 11:58:11.001  3509  3850 D InputManager-JNI: Disable repeat for home key when device wake up
12-20 11:58:11.001  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:58:11.001  3509  3619 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_OFF -> REPORTED_TO_POLICY_SCREEN_TURNING_ON.
12-20 11:58:11.001  3509  3924 V KeyguardServiceDelegate: onStartedWakingUp()
,12-20 11:58:11.001  3509  3619 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@2d8b1b)
12-20 11:58:11.001  3960  4430 D KeyguardViewMediator: onStartedWakingUp, seq = 5
12-20 11:58:11.001  3509  3619 D DisplayPowerController: mWindowManagerPolicy.screenTurningOn(mPendingScreenOnUnblocker, 0)
12-20 11:58:11.001  3960  4430 D KeyguardViewMediator: notifyStartedWakingUp
12-20 11:58:11.001  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:58:11.001  3960  3960 D KeyguardViewMediator: handleNotifyWakingUp
12-20 11:58:11.001  3509  3619 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
12-20 11:58:11.001  3960  3960 D PhoneStatusBar: onUnlockHintStarted isSmartLock = false, isInSecureByLockTimeout=false
12-20 11:58:11.001  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:58:11.001  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
12-20 11:58:11.001  3509  3926 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : registerListenerRunnable
12-20 11:58:11.001  3509  3926 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for AUTO_BRIGHTNESS
12-20 11:58:11.001  3960  4430 D KeyguardViewMediator: notifyScreenOn
,12-20 11:58:11.001  3509  3926 I CAE     : setPropertyValue(AutoBrightnessRunner.java:129) - Mode = 0
12-20 11:58:11.001  3509  3626 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> ON brightness: 1 -> 1
12-20 11:58:11.001  3509  3926 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 48, 1, 0,
12-20 11:58:11.001  3509  3926 D SensorHubManager: SendSensorHubData: send data = -63, 23, 48, 1, 0
,12-20 11:58:11.001  3018  3018 D SurfaceFlinger: Set power mode=2, type=0 flinger=0x7fa9d43c00
12-20 11:58:11.001  3509  3615 I DisplayManagerService: Display device changed state: "Wbudowany ekran", ON
12-20 11:58:11.001  3018  3018 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(2)
12-20 11:58:11.001  3509  3615 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", ON
,12-20 11:58:11.001  3182  3182 D Sensorhubs: sendContextData: -63, 23, 48, 1, 0
12-20 11:58:11.011  3960  3960 V KeyguardFingerPrint: updateFingerprintListeningState(false)
,12-20 11:58:11.011  3960  3960 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
12-20 11:58:11.011  3960  3960 V KeyguardUpdateMonitor: stopListeningForFingerprint()
,12-20 11:58:11.021  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:58:11.021  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:58:11.021  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:58:11.021  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
12-20 11:58:11.021  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:58:11.021  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:58:11.021  3509  9790 D MISC PowerHAL: sysfs_write +: /sys/class/input/event0/device/enabled: 1
12-20 11:58:11.021  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
12-20 11:58:11.021  3509  9790 D MISC PowerHAL: sysfs_write -: /sys/class/input/event0/device/enabled: 1
12-20 11:58:11.021  3509  3619 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
12-20 11:58:11.021  3509  3619 V KeyguardServiceDelegate: onScreenTurnedOn()
12-20 11:58:11.021  3509  3619 D DisplayPowerController: [M OS] 0 Notify policy about screen turned on.
12-20 11:58:11.021  3509  9791 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 1
12-20 11:58:11.021  3509  3619 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_TURNING_ON -> REPORTED_TO_POLICY_SCREEN_ON.
,12-20 11:58:11.021  3509  3619 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
12-20 11:58:11.021  3509  9791 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 1
12-20 11:58:11.021  3509  3619 D PowerManagerService: mDisplayReady: true
12-20 11:58:11.021  3509  3626 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 1
12-20 11:58:11.021  3509  3595 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 com.android.server.policy.sec.SamsungPhoneWindowManager$22.run:4527 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:158 
,12-20 11:58:11.021  3509  3626 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 1
12-20 11:58:11.021  3509  3925 D lights  : button : 1 +
12-20 11:58:11.021  3509  3925 D lights  : button : 1 -
12-20 11:58:11.031  3509  3926 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,12-20 11:58:11.031  3960  3977 D KeyguardViewMediator: notifyScreenTurnedOn
12-20 11:58:11.031  3509  3926 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for AUTO_BRIGHTNESS
12-20 11:58:11.031  3509  3926 D SContext.CaeProvider: setAttribute() : 0
12-20 11:58:11.031  3509  3926 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for AUTO_BRIGHTNESS
12-20 11:58:11.031  3509  3926 V CAE     : start(ContextProvider.java:128)
,12-20 11:58:11.031  3509  3926 V CAE     : clear(AutoBrightnessRunner.java:297)
12-20 11:58:11.031  3509  3926 V CAE     : enable(AutoBrightnessRunner.java:256)
12-20 11:58:11.031  3509  3926 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 48, 0,
12-20 11:58:11.031  3509  3926 D SensorHubManager: SendSensorHubData: send data = -79, 48, 0
,12-20 11:58:11.031  3509  3615 I WindowManager: finishPostLayoutPolicyLw : mNightClock.hideLw by screenTurnedOn
12-20 11:58:11.031  3509  3615 V WindowOrientationListener: setCurrentAppOrientation :1
12-20 11:58:11.031  3509  3615 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,12-20 11:58:11.031  6319  6319 E CocktailBarPositionManager: Window direction: 0
12-20 11:58:11.031  6319  6319 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
12-20 11:58:11.031  3182  3222 D Sensorhubs: sendContextData: -79, 48, 0
,12-20 11:58:11.041  3509  3926 D CAE     : getFaultDetectionResult(AutoBrightnessRunner.java:311) - true
,12-20 11:58:11.041  3509  3926 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:58:11.041  3509  3509 D LightsService: [api] [SvcLED] turnOff:: id = 5 (uid: 1000 pid: 3509) 
,12-20 11:58:11.041  3509  3615 D InputDispatcher: Focus left window: 4748
,12-20 11:58:11.041  3509  3509 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=5) set Off
12-20 11:58:11.041  3509  3615 D InputDispatcher: Focus entered window: 3960
12-20 11:58:11.041  3509  3509 D BatteryService: turn off LED
12-20 11:58:11.041  3509  3625 D lights  : led_pattern : 0 +
12-20 11:58:11.041  3509  3625 D LightsService: [SvcLED] handleForcedSvcLEDTask()
12-20 11:58:11.041  4748  4748 I AODService: onStartCommand : action : com.samsung.android.app.aodservice.intent.action.AOD_SCREEN_ON
12-20 11:58:11.041  3509  3625 I LightsService: fileWriteInt : /sys/class/sec/led/led_lowpower  value : 1
12-20 11:58:11.041  4748  4748 I AODService: onCreate cause: [12-20 11:51:46.639][AOD:true, NightClock:false]<com.samsung.android.app.aodservice.intent.action.AOD_SCREEN_ON> (when Screen on ...)
,12-20 11:58:11.041  3509  3595 V WindowManager: MSG_REQUEST_TRAVERSAL_BY_PWM
12-20 11:58:11.041  3509  3615 D PowerManagerService: [api] setUserActivityTimeoutOverrideFromWindowManagerInternal: timeoutMillis: 10000
12-20 11:58:11.041  3509  3615 D PowerManagerService: [s] getScreenOffTimeoutLocked: 30000 -> 10000
12-20 11:58:11.041  3509  3615 D PowerManagerService: [api] setScreenDimDurationOverrideFromWindowManagerInternal: timeoutMillis: 0
,12-20 11:58:11.041  3509  3625 D lights  : led_pattern : 0 -
12-20 11:58:11.041  3509  3625 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,12-20 11:58:11.051  3509  3926 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:58:11.051  3509  3595 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{421530f u0 d0 StatusBar}
12-20 11:58:11.051  3509  3926 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
12-20 11:58:11.051  3509  3926 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
,12-20 11:58:11.051  3509  3926 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
12-20 11:58:11.051  3509  3926 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@14af07a, Service : DEVICE_PHYSICAL_CONTEXT_MONITOR(1)
12-20 11:58:11.051  3509  3926 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@9e29764, Service : AUTO_BRIGHTNESS(1)
12-20 11:58:11.051  3509  3926 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for AUTO_BRIGHTNESS
12-20 11:58:11.051  3509  3926 D SContextService: 	.registerCallback : 2, client=
12-20 11:58:11.051  3509  3926 D SContextService: ===== SContext Service List =====
12-20 11:58:11.051  3509  3926 D PowerManagerUtil: Excessive delay in SensorHubAutoBrightnessEnabled::registerListener done: 52ms
12-20 11:58:11.051  3509  3926 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@a89c02b, Service : Device Physical Context Monitor
12-20 11:58:11.051  3509  3926 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@af31dcd, Service : Auto Brightness
12-20 11:58:11.051  3509  3926 D SContextManager:   .registerListener : listener = com.android.server.display.AutomaticBrightnessController$6@d74e31, service=Auto Brightness
12-20 11:58:11.051  3509  3615 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3509 uid:1000
12-20 11:58:11.051  3509  3615 D PointerIcon: setMouseCustomIcon IconType is same.101
12-20 11:58:11.051  3960  3960 D KeyguardViewMediator: handleNotifyScreenTurningOn
12-20 11:58:11.051  3960  3960 D KeyguardEffectViewController: onScreenTurningOn
12-20 11:58:11.051  3960  3960 D KeyguardEffectViewController: ## mBackgroundView.onResume()
12-20 11:58:11.051  3960  3960 D KeyguardEffectViewLayered: onResume()
12-20 11:58:11.051  4748  4748 I AlpmModeManager: stopAlpmMode: state  = BLANK
12-20 11:58:11.051  4748  4748 I AlpmModeManager: handleAlpmModeOff: state  = BLANK
12-20 11:58:11.051  4748  4748 I AlpmModeManager: handleAlpmModeOff: AlpmModeManager wakeLock [RELEASE]
,12-20 11:58:11.061  3509  4333 D PowerManagerService: [api] release WakeLock flags=0x40 tag=AlpmModeManager uid=10000 pid=4748 (0x0)
12-20 11:58:11.061  4748  4748 V AlpmModeManager: handleAlpmModeOff: setDozeOverrideFromAod DISPLAY_STATE_UNKNOWN
12-20 11:58:11.061  3509  4434 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 0, Brightness = 0, wakefulness = true
12-20 11:58:11.061  3509  4434 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,12-20 11:58:11.061  4748  4748 D AODService.ClockTimer: stop
,12-20 11:58:11.061  4748  4748 I AODService.ClockTimer: stopAlarm : TICK
,12-20 11:58:11.061  3509  4342 V AlarmManager:  remove PendingIntent] PendingIntent{6265682: PendingIntentRecord{cb26099 com.samsung.android.app.aodservice broadcastIntent}}
12-20 11:58:11.061  4748  4748 I AODService.ClockTimer: stopAlarm : SLEEP
12-20 11:58:11.061  3960  3960 D KeyguardViewMediator: IKeyguardDrawnCallback.onDrawn()
,12-20 11:58:11.061  3509  4334 V AlarmManager:  remove PendingIntent] PendingIntent{73aa193: PendingIntentRecord{4e596cd com.samsung.android.app.aodservice broadcastIntent}}
12-20 11:58:11.061  3509  3530 V KeyguardServiceDelegate: **** SHOWN CALLED ****
12-20 11:58:11.061  4748  4748 I AODService.ClockTimer: stopAlarm : WAKEUP
12-20 11:58:11.061  3509  3595 V WindowManager: MSG_REQUEST_TRAVERSAL_BY_PWM
12-20 11:58:11.061  3509  3595 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,12-20 11:58:11.061  3509  3791 V AlarmManager:  remove PendingIntent] PendingIntent{be3c5d0: PendingIntentRecord{d5689d1 com.samsung.android.app.aodservice broadcastIntent}}
12-20 11:58:11.071  3509  3595 I CAE     : setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
12-20 11:58:11.071  3960  3960 D KeyguardViewMediator: handleNotifyScreenTurnedOn
12-20 11:58:11.071  3509  3595 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,12-20 11:58:11.071  3509  3595 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
12-20 11:58:11.071  3509  4092 D SettingsProvider: isChangeAllowed() : name = aod_show_state
12-20 11:58:11.071  3509  4092 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
12-20 11:58:11.071  3509  4092 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
12-20 11:58:11.071  3509  3595 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for AUTO_ROTATION
12-20 11:58:11.071  3509  4092 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
12-20 11:58:11.071  3509  4092 D SettingsProvider: selectionArgs: false
,12-20 11:58:11.071  3509  4092 D SettingsProvider: selectionArgs: 10000
12-20 11:58:11.071  3509  3595 V CAE     : start(ContextProvider.java:128)
12-20 11:58:11.071  3509  4092 D SettingsProvider: ret = -1
,12-20 11:58:11.071  3509  3595 V CAE     : clear(AutoRotationRunner.java:182)
12-20 11:58:11.071  3509  3595 V CAE     : enable(AutoRotationRunner.java:158)
12-20 11:58:11.071  4748  4748 E SettingsUtils: setAODShowState  config = 0
12-20 11:58:11.071  4748  4748 D ScoverManager: unregisterListener
,12-20 11:58:11.071  3509  3595 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 7, 0, 0,
12-20 11:58:11.071  3509  3595 D SensorHubManager: SendSensorHubData: send data = -79, 7, 0, 0
12-20 11:58:11.071  3509  4977 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
12-20 11:58:11.071  3182  7712 D Sensorhubs: sendContextData: -79, 7, 0, 0
12-20 11:58:11.071  3509  4436 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
12-20 11:58:11.071  3509  4436 D CoverManager.StateNotifier: unregisterCallback : binder = android.os.BinderProxy@fac4db3, pid : 4748, uid : 10000
,12-20 11:58:11.071  3509  4434 I Sensors : Light old sensor_state 512, new sensor_state : 0 en : 0
,12-20 11:58:11.071  3960  3960 D SecKeyguardStatusView: onScreenTurnedOn()
,12-20 11:58:11.071  3960  3960 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
,12-20 11:58:11.081  3509  3509 I CAE     : handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,12-20 11:58:11.081  3509  3509 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_WAKEUP
12-20 11:58:11.081  3509  3595 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
12-20 11:58:11.081  3509  3509 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -47, 0,
12-20 11:58:11.081  3509  3509 D SensorHubManager: SendSensorHubData: send data = -76, 13, -47, 0
12-20 11:58:11.081  3509  3595 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:58:11.081  3182  3182 D Sensorhubs: sendContextData: -76, 13, -47, 0
,12-20 11:58:11.081  3509  3509 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
,12-20 11:58:11.081  4748  4748 D SensorManager: unregisterListener ::   
,12-20 11:58:11.091  3509  3842 E MotionRecognitionService:  handler : SCREEN_ON end
12-20 11:58:11.091  4748  4748 I AlpmModeManager: handleUnblankDisplay: state  = ALPM_OFF
,12-20 11:58:11.091  3509  3595 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:58:11.091  3509  3595 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,12-20 11:58:11.091  3509  3595 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
12-20 11:58:11.091  3509  3595 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
12-20 11:58:11.091  3509  3595 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@14af07a, Service : DEVICE_PHYSICAL_CONTEXT_MONITOR(1)
12-20 11:58:11.091  3509  3595 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@9e29764, Service : AUTO_BRIGHTNESS(1)
,12-20 11:58:11.091  3509  3595 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6e758ce, Service : AUTO_ROTATION(1)
,12-20 11:58:11.091  3509  3595 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for AUTO_ROTATION
12-20 11:58:11.091  3509  3509 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_ON
12-20 11:58:11.091  3509  3595 D SContextService: 	.registerCallback : 3, client=
12-20 11:58:11.091  3509  3595 D SContextService: ===== SContext Service List =====
12-20 11:58:11.091  3509  3595 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@a89c02b, Service : Device Physical Context Monitor
12-20 11:58:11.091  3509  3595 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@af31dcd, Service : Auto Brightness
12-20 11:58:11.091  3509  3595 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@ae3c3ef, Service : Auto Rotation
12-20 11:58:11.091  3509  3595 D SContextManager:   .registerListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@8adcaff, service=Auto Rotation
12-20 11:58:11.091  3509  4007 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@a89c02b, Service = Device Physical Context Monitor, used = 0
12-20 11:58:11.091  3509  4007 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
12-20 11:58:11.101  3509  4007 V CAE     : stop(ContextProvider.java:155)
,12-20 11:58:11.101  3509  4007 V CAE     : clear(DevicePhysicalContextMonitorRunner.java:497)
,12-20 11:58:11.101  3509  4007 V CAE     : disable(DevicePhysicalContextMonitorRunner.java:486)
12-20 11:58:11.101  3509  3836 V AlarmManager: Expired Alarm result :8
12-20 11:58:11.101  3509  4007 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 56, 0, 0,
12-20 11:58:11.101  3509  4007 D SensorHubManager: SendSensorHubData: send data = -78, 56, 0, 0
12-20 11:58:11.101  3182  3222 D Sensorhubs: sendContextData: -78, 56, 0, 0
,12-20 11:58:11.101  3509  4007 D CAE     : getFaultDetectionResult(DevicePhysicalContextMonitorRunner.java:521) - true
,12-20 11:58:11.101  3509  4007 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:58:11.101  3509  3509 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
,12-20 11:58:11.101  3509  3509 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
12-20 11:58:11.101  3509  3509 D UcmService: notifyChangeToPlugin event 15
12-20 11:58:11.101  3509  3509 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
12-20 11:58:11.101  3509  3509 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
12-20 11:58:11.101  3509  3509 D UcmService: notifying to unmanaged plugin
12-20 11:58:11.101  4378  4418 E ucsBai_agentService: notifyChange NOT SUPPORTED
12-20 11:58:11.101  3509  3509 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
12-20 11:58:11.101  3509  3509 D UcmService: agentService status-0
12-20 11:58:11.101  3509  3509 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.ese:eSE Credential Storage Package name = com.samsung.ucs.agent.ese
12-20 11:58:11.101  3509  3509 D UcmService: notifying to managed plugin
,12-20 11:58:11.101  3509  3509 D UcmService: checkIfNotify: Valid userid - 0
12-20 11:58:11.101  3509  3509 D PolicyManager: PolicyManager.isStorageEnabled() for userId = 0
12-20 11:58:11.101  3509  3509 D UniversalCredentialManagerService: checkCallerPermissionFor is called for method-isCredentialStorageManagedAsUser
12-20 11:58:11.101  3509  3509 D UniversalCredentialManagerService: isCredentialStorageManagedAsUser is called....
12-20 11:58:11.111  3509  3509 D PolicyManager: PolicyManager.isStorageEnabled() result = false
12-20 11:58:11.111  3509  3509 D UcmService: agentService com.samsung.ucs.agent.ese:eSE Credential Storage not notified
12-20 11:58:11.111  3509  3509 D UcmService: agentService status-0
12-20 11:58:11.111  3509  3509 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
12-20 11:58:11.111  3509  3509 D UcmService: notifying to unmanaged plugin
12-20 11:58:11.111  4396  4424 D BootAgentService: notifyChange eventId-15
,12-20 11:58:11.111  3509  3509 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
12-20 11:58:11.111  3509  3509 D UcmService: agentService status--1
12-20 11:58:11.111  3509  3509 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,12-20 11:58:11.111  3509  4007 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,12-20 11:58:11.111  3509  4007 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,12-20 11:58:11.111  3509  4007 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
12-20 11:58:11.111  3509  4007 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
12-20 11:58:11.111  3509  4007 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@9e29764, Service : AUTO_BRIGHTNESS(1)
12-20 11:58:11.111  3509  4007 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6e758ce, Service : AUTO_ROTATION(1)
12-20 11:58:11.111  3509  4007 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,12-20 11:58:11.111  3509  4007 D SContextService: 	.unregisterCallback : 3, client=
12-20 11:58:11.111  3509  4007 D SContextService: ===== SContext Service List =====
12-20 11:58:11.111  3509  4007 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@af31dcd, Service : Auto Brightness
12-20 11:58:11.111  3509  4007 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@ae3c3ef, Service : Auto Rotation
12-20 11:58:11.111  4748  9796 D SContextManager:   .unregisterListener : listener = com.samsung.android.app.aodservice.AODService$7@de2fb91, service=Device Physical Context Monitor
,12-20 11:58:11.131  3509  3509 I WifiTrafficPoller: evaluateTrafficStatsPolling
,12-20 11:58:11.141  3509  3881 D WifiStateMachine: handleScreenStateChanged, screen on, start periodic scan !!!
,12-20 11:58:11.141  3509  3881 D WifiNative-wlan0: callSECApiBoolean - ID [11]
12-20 11:58:11.141  4152  4152 I wpa_supplicant: STOP_PERIODIC_SCAN command
,12-20 11:58:11.151  3509  3850 D InputReader: Input event(5): value=0 when=399590138000
12-20 11:58:11.151  3509  3850 D InputReader: !@notifyKey(172), action=1
12-20 11:58:11.151  3509  3850 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=1, interactive=true
,12-20 11:58:11.151  3509  3850 D InputManager-JNI: !@handleInterceptActions(172), action=1, wmActions=1
,12-20 11:58:11.151  3509  3849 D VoIPInterfaceManager: isVoIPRinging()...
,12-20 11:58:11.151  3509  3849 I WindowManager: Ignoring HOME; down is not pressed.
12-20 11:58:11.151  3509  3849 D VoIPInterfaceManager: isVoIPRunningAndDeregi()...
12-20 11:58:11.151  3509  3849 D VoIPInterfaceManager: Not exist call session
12-20 11:58:11.151  3509  3509 D NotificationService: ACTION_SCREEN_ON
12-20 11:58:11.151  3509  3509 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3509) 
12-20 11:58:11.151  3509  3509 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=6) set Off
,12-20 11:58:11.151  3509  3509 D EdgeLight: Turning off
12-20 11:58:11.151  3509  3625 D LightsService: [SvcLED] handleForcedSvcLEDTask()
12-20 11:58:11.151  3509  3625 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,12-20 11:58:11.161  4194  4205 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=112]
12-20 11:58:11.161  3175  3660 D audio_hw_primary: adev_set_parameters: enter: kvpairs: screen_state=on
12-20 11:58:11.161  4194  4194 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.people.package_name=android, samsung.people.notification_type=led_indicator}]
12-20 11:58:11.161  4194  4194 I PeopleStripeService: PeopleNotificationReceiver:3
,12-20 11:58:11.161  4194  4194 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
,12-20 11:58:11.161  4194  4194 I PeopleDataManager: removeNotification
12-20 11:58:11.161  4194  4194 I NotificationParser: getNotiType:android,led_indicator
12-20 11:58:11.161  4194  4194 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=true,key=null,removeAll=false
12-20 11:58:11.161  4194  4194 D PeopleDataManager: removeNotiInfo =null
,12-20 11:58:11.171  3509  3509 I BackgroundCompactionService: onStart. jobID=801
,12-20 11:58:11.171  3509  3509 I BackgroundCompactionService: onStart done. jobID=801
12-20 11:58:11.171  3509  3509 V AlarmManager:  remove PendingIntent] PendingIntent{ac7d00c: PendingIntentRecord{dbf6d55 android broadcastIntent}}
,12-20 11:58:11.171  3509  9797 I BackgroundCompactionService: Execute BGCompaction (type1). (1 times)
,12-20 11:58:11.171  3509  9797 I BackgroundCompactionService: compact_memory command done
12-20 11:58:11.181  3509  3881 E WifiNative-wlan0: do suspend false
,12-20 11:58:11.201  3509  3881 D WifiStateMachine: analyze kernel wifi wakelock 
12-20 11:58:11.201  3509  3881 D WifiStateMachine: file not found /proc/wakelocks
,12-20 11:58:11.201  3509  3509 I MdnieScenarioControlService: action  :  android.intent.action.SCREEN_ON
,12-20 11:58:11.201  3509  3509 I MdnieScenarioControlService: mGameModeLauncher : false
,12-20 11:58:11.221  3509  3509 I MdnieScenarioControlService: setUIMode
,12-20 11:58:11.221  3182  3221 D Sensorhubs: readContextData: 1, 1, 48, 0, 0, 0, 105, 0, 0, 0, 22
,12-20 11:58:11.221  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(11) = 1, 1, 48, 0, 0, 0, 105, 0, 0, 0, 22
,12-20 11:58:11.231  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :11], AP_WAKEUP
,12-20 11:58:11.231  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 11
12-20 11:58:11.231  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 48, 0, 0, 0, 105, 0, 0, 0, 22,
12-20 11:58:11.231  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= AUTO_BRIGHTNESS =================
,12-20 11:58:11.231  3509  3838 I CAE     : display(ContextProvider.java:391) - Candela=[105], AmbientLux=[22]
,12-20 11:58:11.231  3509  3841 D SContextService: updateSContext() : event = Auto Brightness
12-20 11:58:11.231  3509  3926 D AutomaticBrightnessController: [DAB] onSensorHubChanged : 1st lux = 22.0, 1st candela = 105.0
12-20 11:58:11.231  3509  3926 D AutomaticBrightnessController: [DAB] updateAutoBrightnessSEC : 105(104.65822)    0.0 < 22.0 < 201.0 (0.0)
,12-20 11:58:11.231  3509  3926 D AutomaticBrightnessController: mCallbacks.updateBrightness()
12-20 11:58:11.231  3509  3926 D PowerManagerUtil: fileWriteInt to /sys/class/tcon/tcon/auto_br, 1
12-20 11:58:11.231  3509  3927 D lights  : lcd : 105 +
12-20 11:58:11.231  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:58:11.231  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:58:11.231  3509  3926 D PowerManagerUtil: fileWriteInt to /sys/class/backlight/panel/auto_brightness, 2
,12-20 11:58:11.231  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 105 -> 105
12-20 11:58:11.231  3509  3619 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
12-20 11:58:11.231  3509  3619 D DisplayPowerController: Tracking Direct to etc : 105
12-20 11:58:11.231  3509  3619 D DisplayPowerController: Animating brightness: target=105, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
12-20 11:58:11.231  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:58:11.231  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:58:11.231  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 105 -> 105
12-20 11:58:11.231  3509  3619 D DisplayPowerController: Animating brightness: target=105, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:58:11.231  3509  3926 D PowerManagerUtil: fileWriteInt to /sys/class/mdnie/mdnie/auto_brightness, 2
,12-20 11:58:11.231  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155650
12-20 11:58:11.231  3509  3509 D WifiService: ACTION_SCREEN_ON, checkSensorStatus !!
12-20 11:58:11.231  3509  3509 E SContext.CaeProvider: setAttribute() : attribute is null!
12-20 11:58:11.231  3509  3884 V AlarmManager:  remove PendingIntent] PendingIntent{47c8c36: PendingIntentRecord{d7614a4 android broadcastIntent}}
12-20 11:58:11.231  3509  3509 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for ACTIVITY_TRACKER
,12-20 11:58:11.241  3509  3509 V CAE     : start(ContextProvider.java:128)
,12-20 11:58:11.241  3509  3509 V CAE     : clear(ActivityTrackerRunner.java:108)
12-20 11:58:11.241  3509  3509 V CAE     : enable(ActivityTrackerRunner.java:84)
,12-20 11:58:11.241  3509  3509 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 10, 58, 11,
12-20 11:58:11.241  3509  3509 D SensorHubManager: SendSensorHubData: send data = -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 10, 58, 11
,12-20 11:58:11.241  3182  7712 D Sensorhubs: sendContextData: -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 10, 58, 11
,12-20 11:58:11.251  3509  3509 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,12-20 11:58:11.251  3509  3509 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,12-20 11:58:11.251  3509  3927 D lights  : lcd : 105 -
12-20 11:58:11.251  3509  3927 D DisplayPowerState: Tracking!!: 105
12-20 11:58:11.251  3509  3927 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
,12-20 11:58:11.251  3509  3619 D DisplayPowerController: animateScreenStateChange[0]: target=2
12-20 11:58:11.251  3509  3619 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
12-20 11:58:11.251  3509  3619 D DisplayPowerController: getFinalBrightness : Summary is 105 -> 105
12-20 11:58:11.251  3509  3619 D DisplayPowerController: Animating brightness: target=105, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,12-20 11:58:11.251  3960  3960 I ViewCaptureUtil: Capture the lockscreen
,12-20 11:58:11.261  4748  4748 D AODService: dismissWindow
,12-20 11:58:11.261  3509  3509 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
12-20 11:58:11.261  4748  4748 D DefaultClockView:  dismiss
,12-20 11:58:11.261  3509  3509 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
12-20 11:58:11.261  3509  3509 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
,12-20 11:58:11.261  3509  3509 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
12-20 11:58:11.261  3509  3509 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6bd2fd3, Service : ACTIVITY_TRACKER(1)
12-20 11:58:11.261  3509  3509 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@9e29764, Service : AUTO_BRIGHTNESS(1)
,12-20 11:58:11.261  3509  3509 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@6e758ce, Service : AUTO_ROTATION(1)
12-20 11:58:11.261  3509  3509 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for ACTIVITY_TRACKER
12-20 11:58:11.261  3509  3509 D SContextService: 	.registerCallback : 3, client=
12-20 11:58:11.261  3509  3509 D SContextService: ===== SContext Service List =====
12-20 11:58:11.261  3509  3509 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@af31dcd, Service : Auto Brightness
,12-20 11:58:11.261  3509  3509 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@ae3c3ef, Service : Auto Rotation
12-20 11:58:11.261  3509  3509 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@27a41e7, Service : Activity Tracker
12-20 11:58:11.261  3509  3509 D SContextManager:   .registerListener : listener = com.android.server.wifi.WifiServiceImpl$11@321b3a6, service=Activity Tracker
12-20 11:58:11.261  3509  3509 W CAE     : getContextInfo(ContextAwareService.java:457) - [getContext 01] Mutex is locked for ACTIVITY_TRACKER_CURRENT_INFO
12-20 11:58:11.261  3509  3509 V CAE     : enable(ActivityTrackerCurrentInfoRunner.java:178)
,12-20 11:58:11.261  3509  3509 V CAE     : clear(ActivityTrackerCurrentInfoRunner.java:202)
12-20 11:58:11.261  3509  3509 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 26, 1, 0,
,12-20 11:58:11.261  3509  3509 D SensorHubManager: SendSensorHubData: send data = -72, 26, 1, 0
12-20 11:58:11.261  3182  3182 D Sensorhubs: sendContextData: -72, 26, 1, 0
,12-20 11:58:11.271  3018  4509 D libEGL  : eglTerminate EGLDisplay = 0x7fa23fee78
12-20 11:58:11.271  3018  4509 D libEGL  : eglTerminate EGLDisplay = 0x7fa23fee78
,12-20 11:58:11.271  4748  4748 D ViewRootImpl: #3 mView = null
,12-20 11:58:11.271  3509  3509 D CAE     : getFaultDetectionResult(ActivityTrackerCurrentInfoRunner.java:214) - true
12-20 11:58:11.271  3509  3509 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
12-20 11:58:11.271  3018  3112 I SurfaceFlinger: id=28 Removed BOD (8/10)
12-20 11:58:11.271  3018  4509 I SurfaceFlinger: id=28 Removed BOD (-2/10)
,12-20 11:58:11.271  3018  3018 D libEGL  : eglTerminate EGLDisplay = 0x7fff7e5bd8
,12-20 11:58:11.281  3182  3221 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, 90, -108, 64, 0, 2
,12-20 11:58:11.281  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, 90, -108, 64, 0, 2
12-20 11:58:11.281  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
,12-20 11:58:11.281  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
12-20 11:58:11.281  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, 90, -108, 64, 0, 2,
12-20 11:58:11.281  3509  3509 W CAE     : getContextInfo(ContextAwareService.java:511) - [getContext 02] Mutex is unlocked for ACTIVITY_TRACKER_CURRENT_INFO
12-20 11:58:11.281  3509  3509 D SContextService: requestToUpdate() : service = Activity Tracker
12-20 11:58:11.281  3509  3509 D SContextManager:   .requestToUpdate : listener = com.android.server.wifi.WifiServiceImpl$11@321b3a6, service=Activity Tracker
,12-20 11:58:11.281  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
,12-20 11:58:11.281  3509  3838 I CAE     : display(ContextProvider.java:391) - Accuracy=[2], OperationMode=[0], ActivityType=[0], TimeStamp=[1482231490624]
12-20 11:58:11.281  3509  3841 D SContextService: updateSContext() : event = Activity Tracker
,12-20 11:58:11.291  3509  3615 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
,12-20 11:58:11.291  3509  3615 D IpRemoteDisplayController: Bridge Server is not available
,12-20 11:58:11.291  3509  3509 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
,12-20 11:58:11.291  3509  3509 D WifiStateMachine: setWifiScanMove bMove = 0
12-20 11:58:11.291  3509  3509 D WifiService: ACTIVITY_STATUS_UNKNOWN 
12-20 11:58:11.291  3509  3509 I WifiStateMachine: not vehicle, sendMessageDelayed CMD_SET_SCAN_MOVE with 0
12-20 11:58:11.291  3509  3509 D WifiService: setWifiScanWithSensor bMove = 0
12-20 11:58:11.291  3509  3881 I WifiStateMachine: DriverStartedState :: CMD_SET_SCAN_MOVE(0) 
,12-20 11:58:11.291  4152  4152 I wpa_supplicant: @@wpa_supplicant_set_scan_move : set [0]
,12-20 11:58:11.301  3509  3879 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 1
,12-20 11:58:11.301  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10009, mScreenOn: true, uidstate: 0, mProxSensorScreenOff: false
12-20 11:58:11.301  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: true, uidstate: 3, mProxSensorScreenOff: false
12-20 11:58:11.301  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10065, mScreenOn: true, uidstate: 0, mProxSensorScreenOff: false
12-20 11:58:11.301  3509  3879 D NetworkPolicy: isUidForegroundLocked: 10072, mScreenOn: true, uidstate: 3, mProxSensorScreenOff: false
,12-20 11:58:11.301  3509  3589 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,12-20 11:58:11.311  4253  4253 D FusedLocationReceiver: BroadcastReceiver : ACTION_SCREEN_ON
,12-20 11:58:11.311  3509  3509 D PersonaManagerService: ACTION_SCREEN_ON onReceive
,12-20 11:58:11.311  3509  3631 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
,12-20 11:58:11.321  3509  4002 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,12-20 11:58:11.321  4304  4304 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_LOCKED by isKeyguardLocked()
,12-20 11:58:11.321  4304  7816 D NfcService: call the applyRouting
,12-20 11:58:11.331  3960  4176 D NetworkController.MobileSignalController(0/2147483643): onDataActivity: direction=0
,12-20 11:58:11.341  3182  3221 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, 90, -108, 124, 0, 2
,12-20 11:58:11.341  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, 90, -108, 124, 0, 2
12-20 11:58:11.341  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
12-20 11:58:11.341  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
,12-20 11:58:11.341  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, 90, -108, 124, 0, 2,
,12-20 11:58:11.341  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
12-20 11:58:11.341  3509  3838 I CAE     : display(ContextProvider.java:391) - Accuracy=[2], OperationMode=[0], ActivityType=[0], TimeStamp=[1482231490684]
,12-20 11:58:11.341  3509  3841 D SContextService: updateSContext() : event = Activity Tracker
12-20 11:58:11.341  3509  3509 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
12-20 11:58:11.341  3509  3509 D WifiService: ACTIVITY_STATUS_UNKNOWN 
,12-20 11:58:11.361  3509  3509 V AlarmManager:  remove PendingIntent] PendingIntent{ada74ef: PendingIntentRecord{147b977 android broadcastIntent}}
,12-20 11:58:11.361  5257  5257 D BtGatt.GattService: LCD turned on
,12-20 11:58:11.361  5257  5430 D BtGatt.ScanManager: handleLcdOnIntent
12-20 11:58:11.361  5257  5430 D BtGatt.ScanManager: handleLcdOnIntent
12-20 11:58:11.361  5257  5430 D BtGatt.ScanManager: ClientIf = 0
,12-20 11:58:11.381  6319  6319 D CocktailBarUiController: ACTION_SCREEN_ON
12-20 11:58:11.381  6319  6319 D AbstractCocktailPanelView: setPanelVisible: CocktailPortraitRemotePanelViewfalse will be hiden: 3
12-20 11:58:11.381  6319  6319 D CocktailBarPanelVisibilityManager: updateActivePanelView:  vis=false screenOn=true onTransit=false -hide: 3 current Active: 3
,12-20 11:58:11.381  6319  6319 E AbstractCocktailPanelView: notifyPanelVisibilityChanged: visibility not changed 2 id: 3
12-20 11:58:11.381  6319  6319 I TrayVisibilityController: handleMessage : msg.what = 1
,12-20 11:58:11.391  6319  6319 I Utils   : isCurrentUser current = 0, ownerId = 0
,12-20 11:58:11.391  6319  6319 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 2
12-20 11:58:11.391  6319  6319 I TrayVisibilityController: updateTrayVisible : State : 2 visible = 1 mCurrentVisible = 2
12-20 11:58:11.391  6319  6319 D TrayStateController: putInputRect mDynamicInputRegion=188281550@LastEvent=t=1482231378082Rect(8, 0 - 64, 588),Rect=Rect(0, 0 - 0, 0)
12-20 11:58:11.391  6319  6319 D TrayStateController: putInputRect mDynamicInputRegion=188281550@LastEvent=t=1482231378082Rect(8, 0 - 64, 588),Rect=Rect(8, 0 - 64, 588)
12-20 11:58:11.391  4194  4194 D PeopleStripeService: ACTION_SCREEN_ON
12-20 11:58:11.391  6319  6319 D TrayStateTrigger: getTriggerMaginOnTop retY=550 h=2560 t=258 trigger=292 getTriggerPosition=1
,12-20 11:58:11.391  3509  4002 D PowerManagerService: [api] setButtonBrightnessLimit: 255
12-20 11:58:11.391  3509  3905 I AbsCocktailBarStatePolicy: handleMessage: entry what = 1
,12-20 11:58:11.391  6319  6319 D TrayStateController: setUiState: 2 --> 0
,12-20 11:58:11.391  4194  4194 D PeopleStripeManager: onVisibilityChanged : 1
,12-20 11:58:11.391  4194  4194 D PeopleStripeVisibilityController: setHiddenEdgePanel enable=false
,12-20 11:58:11.391  3018  3018 I SurfaceFlinger: id=29 createSurf (64x588),1 flag=4, DocktailBar
,12-20 11:58:11.401  4194  4194 I PeopleStripeVisibilityController: isAllowPrivateNotifications : allowPrivateNotifications = true
,12-20 11:58:11.401  4194  4194 I PeopleStripeVisibilityController: isShowNotification : showNotification = true
,12-20 11:58:11.401  4194  4194 I PeopleStripeVisibilityController: getComputedTrayVisible : keyguardState = 2
12-20 11:58:11.401  4194  4194 I PeopleStripeVisibilityController: updateStripeVisible : State 2 visible = 1
12-20 11:58:11.401  4194  4194 I PeopleStripeManager: isExistVisibleHandler false
12-20 11:58:11.401  4194  4194 I PeopleStripeManager: showStripe Not exist noti handler.
,12-20 11:58:11.401  6319  6352 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [64x588]-format:1
,12-20 11:58:11.411  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 258, CUR = 128, LCD = 105
,12-20 11:58:11.421  6319  6319 D CocktailBarUiController: onCocktailBarStateChanged: flag=0x1 vis=1 bgType=0 showTimeout=-1 activate=true
,12-20 11:58:11.421  3509  6576 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-20 11:58:11.431  3509  3509 I SurveyLogManager: mDeviceInfo.mScreen = true
,12-20 11:58:11.431  3509  3593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dcca194 u-1 com.samsung.ssrm.SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4887832 8428:com.sec.android.daemonapp/u0a166}
,12-20 11:58:11.431  8428  8428 D [WeatherWidget(1240)]  AutoRefreshReceiver: {[43EB1C024052B99D53E991930172379618B5A73E0169704C31B2E0FEC15ABF0DB061C2705E75ED5606D9FFD69F6B37E13822B2991EFA2872858E1E2BB615A6BC25C1BB37530DE4B9994E9888EE083816]}
,12-20 11:58:11.441  8428  8428 D [WeatherWidget(1240)]  AutoRefresh: {[8FD2E506F874D7163C71C5FD167729A3F1524692913D8374891649955E8C59A90C19ED8315B58731AC2FE7582D4006FA]}
,12-20 11:58:11.441  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:58:11.441  3509  4002 V WindowStateAnimator: Finishing drawing window Window{ae806aa u0 d0 com.samsung.android.app.cocktailbarservice/com.samsung.android.app.cocktailbarservice.CocktailBarService}: mDrawState=DRAW_PENDING
,12-20 11:58:11.451  7178  7178 E SamsungIME: invoke(): method is null
,12-20 11:58:11.461  3509  4441 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dcca194 u-1 com.samsung.ssrm.SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4887832 8428:com.sec.android.daemonapp/u0a166}
,12-20 11:58:11.461  8428  8428 D [WeatherWidget(1240)]  WeatherScreenReceiver: {[AE44B1CAE710C9799F38EE823B33FC6FDEAF5CF1F84C7C2D7C42190D3C2DE6A81416E92586372C9712C4D2BD025FBC09C229D81C93196B2AA28F22D563A30C15]}
,12-20 11:58:11.461  8428  8428 D [WeatherWidget(1240)]  WidgetCount: {[65C2FDBB08E09D2E8E78BEFE0D618279BC32024A311F60279E75A9FD2AD8BED1]}
,12-20 11:58:11.461  8428  8428 D [WeatherWidget(1240)]  WidgetCount: {[51D05FFECDA2C35BD99FAAEAA7B9A301F0BE9CFAFD994C3F7B3209384CC66988]}
12-20 11:58:11.461  8428  8428 D [WeatherWidget(1240)]  WidgetCount: {[6CEC719F0A07787F8C223B192FCD4687C55ED1AD256D01CA79B528F9A8936DA2AEE8FCF34DEAE62C4F0012DD0AEA3C4D450DA911871FFB9B1B25866B258CE216]}
,12-20 11:58:11.481  8617  8655 I SystemBroadcastReceiver: [#CMH#] Received broadcast 
12-20 11:58:11.481  8617  8655 I PolicyManager: [#CMH#] onReceive action = EVENT_SCREEN_ON
12-20 11:58:11.481  8617  8655 I SystemBroadcastReceiver: [#CMH#] onReceive completed 
,12-20 11:58:11.491  3509  3924 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,12-20 11:58:11.491  6319  6319 D TrayStateTrigger: showTriggerView
12-20 11:58:11.491  8428  8428 D [WeatherWidget(1240)]  WeatherService: {[F5837F4AEE74F4A0BE2DA219DB84933556419BA8B2FB7B09497D41D0C5E6D922]}
,12-20 11:58:11.491  8428  8428 D [WeatherWidget(1240)]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
12-20 11:58:11.491  8428  8428 D [WeatherWidget(1240)]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A000F9D574DD3C1B95D41EAB42ECFF02F3D72C391A0A68B1B0C567090769101B3139122E72F130C4410562206878681E44]}
,12-20 11:58:11.501  8428  8428 D [WeatherWidget(1240)]  WeatherService: {[CC14338CDEB270B60D640F786827F117E88F4AEED272A832A59FE0C979EA04C9BE0E3A339EA914F65899C47723B17899]}
,12-20 11:58:11.511  3509  4441 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ef2b739 u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4887832 8428:com.sec.android.daemonapp/u0a166}
,12-20 11:58:11.511  8428  8428 D [WeatherWidget(1240)]  WeatherAppWidget: {[9C41A2EAFAAB2EF4F8363256C22FE8ADC05C1B1077ADBDFCD26E0DD65F89F33B4FE17DC1B474497D31FC899B742F59FC7E2530D44AA0E0C337CE79DB8742B2E258F6CB339704D31C42A8D7DC7C423413771689541177F15128C5082E60F137378548A4A3E3BC46E58400842019503B6A49C8E5B66CD635265353D3A3BD633961]}
12-20 11:58:11.511  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:58:11.511  8428  8428 D [WeatherWidget(1240)]  : {[AA0F1FFBE590A9EFC37054BD5EE30C3F13AAEFB0C1D46CFF1BAA5F3C6AC68B331A2EF1B485217118DBE54FFA6A88B711AC7C94EA741B05F20DACF9DE9722647F]}
12-20 11:58:11.511  8428  8428 D [WeatherWidget(1240)]  WeatherAppWidget: {[9C41A2EAFAAB2EF4F8363256C22FE8ADC94DE00B25794211F94C1928DF937E6B475EC9A5D52E6E8AB8C5E9065071E1EA]}
,12-20 11:58:11.521  3509  9800 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
12-20 11:58:11.521  3509  4441 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ef2b739 u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4887832 8428:com.sec.android.daemonapp/u0a166}
,12-20 11:58:11.521  8428  8428 D [WeatherWidget(1240)]  WeatherAppWidget2x1: {[9C41A2EAFAAB2EF4F8363256C22FE8AD1E8C40D052B00F217143F036334087D4E6A20622B7C5BAFDDAD05806F64279CFB58ACC644B946D1D44C1CB1343E9933E78640F20943B210E98A310C2B6492635456F7A98A5575530AC106B72D841268FE4ABD25C67426FA9138DA38B471E495644FE77123B7000FBE859923F0050324E]}
,12-20 11:58:11.521  3509  9800 D BluetoothAdapter: STATE_ON
,12-20 11:58:11.521  8428  8428 D [WeatherWidget(1240)]  : {[60E0DA3EB75B6AC8E852DC6D590E8782BC8A388398CF80A085FDDBC5F835D3B9]}
12-20 11:58:11.521  8428  8428 D [WeatherWidget(1240)]  : {[474171746BF601005A4D7D98B25C76B809703E254FE098232F11662B7CFA9306AAA83BB048A13628F045F41D951A5325AE3AF9B32C6D1DD1DC31B963A62AF276362FB0436AF461E46827C6999B8AF63FE3E53B8E7C650FB4537EBF1D6F8067C948D7C1C54AB097190AFAAEFD34E60697]}
,12-20 11:58:11.521  3509  4007 V AlarmManager:  remove PendingIntent] PendingIntent{41917e: PendingIntentRecord{d3aceb1 com.android.bluetooth broadcastIntent}}
,12-20 11:58:11.531  3509  4441 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ef2b739 u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4887832 8428:com.sec.android.daemonapp/u0a166}
,12-20 11:58:11.531  8428  8428 D [WeatherWidget(1240)]  EasyWeatherAppWidget: {[48948B2BE5213A6D5B0C9B7747497512D204533BF333E4D2CEAD653C68E1B222E4748640A665E8FB625C2496224988A01822F94E1D5511EDA528C1BE4CAEABD1D9C6A4F90F6430CF4A4F5AB6F2AF9127520AD0A30D99495D03E7BBCB8D48F747F2FF12B441DB9FDD66804D1185ECF265D727A94D84DA9FC743DD76C54F03F188]}
,12-20 11:58:11.531  8428  8428 D [WeatherWidget(1240)]  : {[AA0F1FFBE590A9EFC37054BD5EE30C3F13AAEFB0C1D46CFF1BAA5F3C6AC68B331A2EF1B485217118DBE54FFA6A88B711AC7C94EA741B05F20DACF9DE9722647F]}
12-20 11:58:11.531  8428  8428 D [WeatherWidget(1240)]  EasyWeatherAppWidget: {[48948B2BE5213A6D5B0C9B774749751274237807901AA8393F0A8526192EEF19F2D7E71ABBE368E57B1937778E7A2758BD22312FFA1C721753FCFDC0AD054D98]}
,12-20 11:58:11.541  3509  4487 V AlarmManager:  remove PendingIntent] PendingIntent{bb386df: PendingIntentRecord{d3aceb1 com.android.bluetooth broadcastIntent}}
,12-20 11:58:11.541  3509  4342 V AlarmManager:  remove PendingIntent] PendingIntent{e028f2c: PendingIntentRecord{d3aceb1 com.android.bluetooth broadcastIntent}}
,12-20 11:58:11.561  3509  9800 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,12-20 11:58:11.591  3509  9800 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,12-20 11:58:11.591  3509  9800 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,12-20 11:58:11.641  3182  3221 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, 90, -107, -88, 0, 1
,12-20 11:58:11.641  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, 90, -107, -88, 0, 1
12-20 11:58:11.641  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
12-20 11:58:11.641  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
12-20 11:58:11.641  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, 90, -107, -88, 0, 1,
12-20 11:58:11.641  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
12-20 11:58:11.641  3509  3838 I CAE     : display(ContextProvider.java:391) - Accuracy=[1], OperationMode=[0], ActivityType=[0], TimeStamp=[1482231490984]
12-20 11:58:11.641  3509  3841 D SContextService: updateSContext() : event = Activity Tracker
,12-20 11:58:11.641  3509  3509 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
12-20 11:58:11.641  3509  3509 D WifiService: ACTIVITY_STATUS_UNKNOWN 
,12-20 11:58:11.681  3509  9800 I BatteryStatsDumper: Writing to database completed
,12-20 11:58:12.011  3182  3221 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, 90, -105, 16, 0, 0
12-20 11:58:12.011  3509  3509 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1144000  uid : 1000  pid : 3509  tag : WAKEUP_BOOSTER@34
,12-20 11:58:12.011  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, 90, -105, 16, 0, 0
12-20 11:58:12.011  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
12-20 11:58:12.011  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
12-20 11:58:12.011  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, 90, -105, 16, 0, 0,
12-20 11:58:12.011  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
12-20 11:58:12.011  3509  3838 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[0], TimeStamp=[1482231491344]
12-20 11:58:12.011  3509  3841 D SContextService: updateSContext() : event = Activity Tracker
,12-20 11:58:12.011  3509  3509 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
12-20 11:58:12.011  3509  3509 D WifiService: ACTIVITY_STATUS_UNKNOWN 
,12-20 11:58:12.081  3167  3638 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,12-20 11:58:12.091  3509  3850 D InputReader: Input event(4): value=1 when=400533508000
12-20 11:58:12.091  3509  3850 D InputReader: Input event(4): value=1 when=400533508000
12-20 11:58:12.091  3509  3850 I InputReader: Touch event's action is 0x0 (deviceType=0) [pCnt=1, s=0.13 ] when=400533508000
12-20 11:58:12.091  3509  3850 D InputReader: lastThreadEndTime = 399591391521, currentThreadStartTime = 399591395598, diff = 0
12-20 11:58:12.091  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x0, toolType: 1
,12-20 11:58:12.091  3960  3960 D ViewRootImpl: ViewPostImeInputStage processPointer 0
,12-20 11:58:12.091  3509  4977 D SecContentProvider: query(), uri = 17 selection = isStatusBarExpansionallowedAsUser
,12-20 11:58:12.101  3960  3960 D KeyguardSwipeHelper: event=MotionEvent { action=ACTION_DOWN, actionButton=0, id[0]=0, x[0]=634.9219, y[0]=2278.125, toolType[0]=TOOL_TYPE_FINGER, buttonState=0, metaState=0, flags=0x0, edgeFlags=0x0, pointerCount=1, historySize=0, eventTime=400533, downTime=400533, deviceId=4, source=0x1002 }
12-20 11:58:12.101  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
12-20 11:58:12.101  3960  3960 D KeyguardSwipeHelper: onUnlockViewPressed()
,12-20 11:58:12.101  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:58:12.101  3509  4333 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 400548
,12-20 11:58:12.121  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:58:12.121  3509  4441 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 400564
,12-20 11:58:12.141  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:58:12.141  3509  4436 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 400581
,12-20 11:58:12.151  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:58:12.151  3509  4487 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 400598
,12-20 11:58:12.171  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:58:12.171  3509  3531 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 400614
,12-20 11:58:12.191  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
12-20 11:58:12.191  3509  4485 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 400631
,12-20 11:58:12.201  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:58:12.201  3509  4342 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 400647
,12-20 11:58:12.221  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:58:12.221  3509  4002 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 400664
,12-20 11:58:12.241  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:58:12.241  3509  3791 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 400681
,12-20 11:58:12.251  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:58:12.251  3509  4977 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 400697
,12-20 11:58:12.271  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:58:12.271  3509  3530 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 400714
,12-20 11:58:12.291  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:58:12.291  3509  4007 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 400731
,12-20 11:58:12.301  3182  3221 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, 90, -104, 59, 1, 0
,12-20 11:58:12.301  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, 90, -104, 59, 1, 0
12-20 11:58:12.301  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
12-20 11:58:12.301  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
,12-20 11:58:12.301  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, 90, -104, 59, 1, 0,
,12-20 11:58:12.301  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
12-20 11:58:12.301  3509  3838 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[1], TimeStamp=[1482231491643]
,12-20 11:58:12.301  3509  3841 D SContextService: updateSContext() : event = Activity Tracker
12-20 11:58:12.301  3509  3509 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
12-20 11:58:12.301  3509  3509 D WifiService: ACTIVITY_STATUS_STATIONARY 
,12-20 11:58:12.301  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:58:12.311  3509  4486 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 400749
,12-20 11:58:12.321  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:58:12.321  3509  4092 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 400764
,12-20 11:58:12.341  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,12-20 11:58:12.341  3509  4334 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 400780
,12-20 11:58:12.351  3509  3850 D InputReader: Input event(4): value=0 when=400790665000
,12-20 11:58:12.351  3509  3850 D InputReader: Input event(4): value=0 when=400790665000
12-20 11:58:12.351  3509  3850 I InputReader: Touch event's action is 0x1 (deviceType=0) [pCnt=1, s=] when=400790665000
,12-20 11:58:12.351  3509  3849 I InputDispatcher: Delivering touch to (3960): action: 0x1, toolType: 1
,12-20 11:58:12.351  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
12-20 11:58:12.351  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
12-20 11:58:12.351  3509  4333 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 400792
12-20 11:58:12.351  3960  3960 D ViewRootImpl: ViewPostImeInputStage processPointer 1
12-20 11:58:12.351  3509  6576 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
12-20 11:58:12.351  3960  3960 D KeyguardSwipeHelper: event=MotionEvent { action=ACTION_UP, actionButton=0, id[0]=0, x[0]=873.28125, y[0]=1129.375, toolType[0]=TOOL_TYPE_FINGER, buttonState=0, metaState=0, flags=0x0, edgeFlags=0x0, pointerCount=1, historySize=0, eventTime=400790, downTime=400533, deviceId=4, source=0x1002 }
12-20 11:58:12.351  3509  6576 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  pkgName : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:58:12.351  3960  3960 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
12-20 11:58:12.351  3960  3960 D KeyguardSwipeHelper: onUnlockViewReleased()
12-20 11:58:12.351  3960  3960 D KeyguardUnlockEventHandler: ACTION_UP mDistance: 1172.4111906664828
12-20 11:58:12.351  3960  3960 D KeyguardEffectViewLayered: handleUnlock()
12-20 11:58:12.351  3509  4434 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10065 pid: 3960) eventTime = 400794
,12-20 11:58:12.351  3960  3960 D KeyguardUnlockEventHandler: launch() - mIsKeyguardDismissing=false, isDeviceInteractive=true
,12-20 11:58:12.351  3960  3960 D KeyguardSwipeHelper: onUnlockExecuted() mUnlockExecuted=false, mUnlockViewPressed=false
12-20 11:58:12.351  3960  3960 D KeyguardSwipeHelper: startAnimationAndUnlock() alpha=0.0, wallpaperType=1
12-20 11:58:12.351  3960  3960 D PanelView: callback makeExpandedInvisible executed
12-20 11:58:12.351  3960  3960 D PhoneStatusBar: makeExpandedInvisible: mExpandedVisible=true, state = 1
12-20 11:58:12.351  3960  3960 D PanelView: updateQsState
12-20 11:58:12.351  3960  3960 D KeyguardSwipeHelper: reset()
12-20 11:58:12.351  3960  3960 D KeyguardUnlockEventHandler: reset()
12-20 11:58:12.351  3960  3960 D KeyguardSwipeHelper: resetChildViewVI()
12-20 11:58:12.351  3960  3960 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
12-20 11:58:12.351  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:58:12.351  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : true keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
12-20 11:58:12.351  3960  3960 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
,12-20 11:58:12.361  6319  6319 I TrayVisibilityController: TrayStateVisibilityReceiver action :com.samsung.systemui.statusbar.COLLAPSED
,12-20 11:58:12.361  3960  3960 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
,12-20 11:58:12.361  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:58:12.361  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
12-20 11:58:12.361  3960  3960 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
12-20 11:58:12.361  3960  3960 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
12-20 11:58:12.361  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:58:12.361  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : true panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
12-20 11:58:12.361  3960  3960 D CoverUI : applyHeight h = -1, oc = true, fa = false, ac = false, sc = false
12-20 11:58:12.361  3960  3960 D StatusBarKeyguardViewManager: showBouncer
12-20 11:58:12.361  3960  3960 D KeyguardSecurityView: showNextSecurityScreenOrFinish(false)
,12-20 11:58:12.361  3960  3960 D KeyguardSecurityModel: getSecurityMode( getActivePasswordQuality = 0 , currentuser = 0
,12-20 11:58:12.361  3960  3960 D KeyguardViewBase: finish mViewMediatorCallback.keyguardDone
12-20 11:58:12.371  3960  3960 D KeyguardViewMediator: keyguardDone(true)
12-20 11:58:12.371  3960  3960 D KeyguardFingerPrint: reportSuccessfulStrongAuthUnlockAttempt()
,12-20 11:58:12.381  3960  3960 D PhoneStatusBar: adjustDisableFlags:false, false, false, false, true, 1
,12-20 11:58:12.381  3960  3960 D KeyguardUnlockEventHandler: mIsMultiTouch false
12-20 11:58:12.381  3960  3960 D KeyguardViewMediator: handleKeyguardDone
12-20 11:58:12.381  3960  3960 D KeyguardViewMediator: onSdpUnlocked :: Inside...
12-20 11:58:12.381  3960  3960 D KeyguardViewMediator: isPwdChangeRequested :: false
,12-20 11:58:12.391  3960  3960 D KeyguardViewMediator: onSdpUnlocked :: Active quality = 0
12-20 11:58:12.391  3960  3960 D KeyguardViewMediator: onSdpUnlocked :: Unlock SDP for User 0
,12-20 11:58:12.391  3960  3960 D KeyguardViewMediator: handleHide
,12-20 11:58:12.391  4328  4328 D Launcher: onRestart, Launcher: 188281550
,12-20 11:58:12.391  3509  3791 E SdpServiceKeeper: isLicensed {pid:3960 uid:10065 userid:0 doPkg:null}
12-20 11:58:12.391  3509  3791 E SdpServiceKeeper: System app. Skip license activation
,12-20 11:58:12.401  3509  3531 E SdpServiceKeeper: isLicensed {pid:3960 uid:10065 userid:0 doPkg:null}
12-20 11:58:12.401  3509  3531 E SdpServiceKeeper: System app. Skip license activation
,12-20 11:58:12.401  4328  4328 D ApplicationPackageManager: we has com.sec.android.app.clockpackage class. reuse it 
,12-20 11:58:12.401  4328  4328 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.sec.android.app.clockpackage
,12-20 11:58:12.431  6319  6319 E CocktailBarPositionManager: Window direction: 0
12-20 11:58:12.431  6319  6319 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,12-20 11:58:12.441  6319  6329 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.sec.android.app.launcher/com.android.launcher2.Launcher} Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10800000 cmp=com.sec.android.app.launcher/.activities.LauncherActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
12-20 11:58:12.441  3509  3509 D GameManagerService: NotifyRunnable. pkg: com.sec.android.app.launcher, type: 4, isMinimized: false, isTunableApp: false
,12-20 11:58:12.441  4328  4328 D ApplicationPackageManager: we has com.android.calendar class. reuse it 
,12-20 11:58:12.441  4328  4328 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.android.calendar
,12-20 11:58:12.441  4328  4328 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:58:12.441  4328  4328 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
12-20 11:58:12.441  4328  4328 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,12-20 11:58:12.451  3960  3960 D KeyguardViewMediator: Calling keyguardGoingAway of WindowManager
,12-20 11:58:12.451  3509  4434 D SdpManagerService: unlock :: Internal... 0
12-20 11:58:12.451  3509  4434 D SdpManagerService: SecureUnlock :: User : 0, Type : 1
12-20 11:58:12.461  3509  3593 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.sec.android.app.launcher
12-20 11:58:12.461  4607  9802 D MdnsClient: #acquireLock. Multicast lock not held. Acquiring
,12-20 11:58:12.461  3509  4485 E BatteryStatsImpl: Wifi multicast lock enabled by UID  = 10021
12-20 11:58:12.461  3509  4434 D SdpManagerService: SecureUnlock :: Quality for user 0 = 0
12-20 11:58:12.461  3509  4434 D TimaService: TIMA3: FipsKeyStore3_init
12-20 11:58:12.461  3509  4434 D SdpManagerService: SecureUnlock :: Very low security level found...!!! 0
12-20 11:58:12.461  3509  4434 D TimaService: TIMA: in getTimaVersion
12-20 11:58:12.461  3509  4434 D SdpManagerService: unlock :: onDeviceUnLocked from TIMA 0
12-20 11:58:12.461  3167  3638 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
12-20 11:58:12.461  3509  4434 I TLC_TZ_KEYSTORE: : TZ_KEYSTORE_fips_initialize
12-20 11:58:12.461  3509  4434 I TLC_TZ_KEYSTORE: : creating new keystore context...
12-20 11:58:12.461  3509  4434 I TLC_TZ_KEYSTORE: : initializing ccm context...
12-20 11:58:12.461  3509  4434 I TLC_TZ_KEYSTORE: : root = 0, root_strlen = 1
12-20 11:58:12.461  3509  4434 I TLC_TZ_KEYSTORE: : process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:58:12.461  3509  4434 I TZ: mc_tlc_communication: input max_sendmsg_size = 1080
12-20 11:58:12.461  3509  4434 I TZ: mc_tlc_communication: input max_recvmsg_size = 1080
12-20 11:58:12.461  3509  4434 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-20 11:58:12.461  3509  4434 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:58:12.461  3509  4434 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 1088
12-20 11:58:12.461  3509  4434 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 1088
12-20 11:58:12.461  3509  4434 I TZ: mc_tlc_communication: device_id = 0x0
12-20 11:58:12.461  3509  4434 I TZ: mc_tlc_communication: tlc_open() was called
12-20 11:58:12.461  3509  4434 I TZ: mc_tlc_communication: Opening MobiCore device
12-20 11:58:12.461  3509  4434 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-20 11:58:12.461  3509  4434 I TZ: mc_tlc_communication: Opening the session
12-20 11:58:12.471  4328  4328 D Launcher: onStart, Launcher: 188281550
12-20 11:58:12.471  4328  4328 D Launcher.HomeView: onStart
12-20 11:58:12.471  3960  3960 D KeyguardViewMediator: handleStartKeyguardExitAnimation
,12-20 11:58:12.471  3960  3960 W AudioTrack: AUDIO_OUTPUT_FLAG_FAST denied by client; transfer 4, track 44100 Hz, output 48000 Hz
12-20 11:58:12.471  4328  4328 D Launcher: onResume, Launcher: 188281550
,12-20 11:58:12.471  3509  3791 D SettingsProvider: isChangeAllowed() : name = kids_home_mode
12-20 11:58:12.471  3509  3791 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
12-20 11:58:12.471  3509  3791 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
12-20 11:58:12.471  3509  3791 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
12-20 11:58:12.471  3509  3791 D SettingsProvider: selectionArgs: false
12-20 11:58:12.471  3509  3791 D SettingsProvider: selectionArgs: 10069
,12-20 11:58:12.481  3509  3791 D SettingsProvider: ret = -1
,12-20 11:58:12.481  3175  3175 W AudioPolicyIntefaceImpl: Skipped to add effects on session 27
,12-20 11:58:12.481  3175  3175 I APM::AudioPolicyManager: startOutput() output 4, stream 1, session 27
12-20 11:58:12.481  4328  4328 D Launcher.HomeView: onResume
,12-20 11:58:12.481  3175  3651 D audio_hw_primary: out_set_parameters: enter: kvpairs: routing=2
12-20 11:58:12.481  3175  3651 D AudioFlinger: setCurDevice() 0x2
,12-20 11:58:12.481  3509  4434 I TZ: mc_tlc_communication: tlc_open() succeeded
12-20 11:58:12.481  3509  4434 I TLC_TZ_KEYSTORE: : ctx = 0x7f811eda40, comm = 0x7f7e72a7f0, sendmsg = 0x7f958fa000, recvmsg = 0x7f958fa440
,12-20 11:58:12.481  3509  4434 I TZ_init: : TZ_init: fips_init_TLC sending initialization request...
12-20 11:58:12.481  3509  4434 I TZ_init: : TZ_init: sending initialization request...
12-20 11:58:12.481  3960  3960 E KeyguardViewMediator: setShowingLocked mShowing = false
12-20 11:58:12.481  4328  4328 D capture : ---------checkFileExist land
12-20 11:58:12.481  4328  4328 D capture : currentOrientation: 1 mMainHomeScreenshot: true mMainHomeScreenshotLand: true
,12-20 11:58:12.491  3960  3960 D StatusBar-Window: fnf=true sanc=false, kni=false, sbf=false
,12-20 11:58:12.491  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:58:12.491  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : false panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
12-20 11:58:12.491  3960  3960 D CoverUI : applyHeight h = 96, oc = false, fa = false, ac = false, sc = false
12-20 11:58:12.491  3960  3960 D StatusBar-Window: fnf=true sanc=false, kni=false, sbf=false
12-20 11:58:12.491  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:58:12.491  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : false panelVisible : false keyguardFadingAway : true bouncerShowing : false headsUpShowing : false
12-20 11:58:12.491  3960  3960 D CoverUI : applyHeight h = -1, oc = false, fa = true, ac = false, sc = false
12-20 11:58:12.491  3960  3960 D KeyguardEffectViewController: setKeyguardFadingAway = true
,12-20 11:58:12.491  3960  3960 D KeyguardEffectViewController: mShowing=true, mOccluded=false, mKeyguardFadingAway=true, match_parent=true
12-20 11:58:12.491  3960  3960 D KeyguardEffectViewController: setKeyguardShowing = false
12-20 11:58:12.491  3960  3960 D KeyguardEffectViewController: mShowing=false, mOccluded=false, mKeyguardFadingAway=true, match_parent=true
12-20 11:58:12.491  3960  3960 V KeyguardUpdateMonitor: *** unregister callback for com.android.keyguard.KeyguardSecurityContainer$1@8e5c75a
,12-20 11:58:12.491  3960  3960 D KeyguardUpdateMonitor: onKeyguardVisibilityChanged(false)
,12-20 11:58:12.491  3175  3651 I AudioMixer: create resampler src 44100, 2, dst 48000, 2
12-20 11:58:12.491  3175  3651 D SoundAliveResampler: [SoundAliveResampler] Init+++
12-20 11:58:12.491  3175  3651 V audio_hw_primary: start_output_stream+, out->device : 00000002 , out->type = 1
,12-20 11:58:12.491  4328  4328 D MenuAppsGridFragment: onResume
12-20 11:58:12.491  4328  4328 D MenuAppsGridFragment: changeState: (new)NORMAL(old)NORMAL(force)false
,12-20 11:58:12.491  3509  4007 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() true
12-20 11:58:12.491  3509  4007 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
12-20 11:58:12.491  3509  4007 D KnoxTimeoutHandler: post home show event for user 0
12-20 11:58:12.491  3509  4007 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
12-20 11:58:12.491  3509  3509 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
12-20 11:58:12.491  3509  3509 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
12-20 11:58:12.491  3509  3509 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,12-20 11:58:12.501  3509  3509 I KnoxTimeoutHandler: Shared devices show user statefalse
,12-20 11:58:12.501  3509  4434 I TZ_init: : TZ_init: successful initialization
,12-20 11:58:12.501  3509  4434 I TLC_TZ_KEYSTORE: fips_self_test: : TZ_KEYSTORE_fips_self_test_START...
12-20 11:58:12.501  4328  4328 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@72d1b85 time:400943
,12-20 11:58:12.501  3960  3960 V KeyguardFingerPrint: updateFingerprintListeningState(false)
12-20 11:58:12.501  3960  3960 D KeyguardFingerPrint: shouldListenForFingerprint ( FingerPrint is not enabled. ) 
12-20 11:58:12.501  3960  3960 V KeyguardUpdateMonitor: stopListeningForFingerprint()
,12-20 11:58:12.501  3509  4434 I TLC_TZ_KEYSTORE: fips_self_test: : TZ_KEYSTORE_fips_self_test_END...
12-20 11:58:12.501  3509  4434 E TLC_TZ_KEYSTORE: : Self Test Succeded
12-20 11:58:12.501  3509  4434 I TZ: mc_tlc_communication: tlc_close() was called
,12-20 11:58:12.501  3509  4434 I TZ: mc_tlc_communication: Closing the session
,12-20 11:58:12.501  3509  4434 I TZ: mc_tlc_communication: Freeing message buffer
12-20 11:58:12.501  3509  4434 I TZ: mc_tlc_communication: Closing MobiCore device
,12-20 11:58:12.501  3509  4434 I TZ: mc_tlc_communication: tlc_close() succeeded
12-20 11:58:12.501  3509  4434 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
12-20 11:58:12.501  3509  4434 D TimaHelper: getTimaStatus() - Tima Status : 0
12-20 11:58:12.501  3509  4434 D TimaHelper: checkTimaStatus() - Version FIPS3.0, Status0, Validation : true
12-20 11:58:12.501  3509  4434 D TimaService: TIMA3: FipsKeyStore3_init
12-20 11:58:12.501  3509  4434 I TLC_TZ_KEYSTORE: : TZ_KEYSTORE_fips_initialize
12-20 11:58:12.501  3509  4434 D TimaService: TIMA: in getTimaVersion
12-20 11:58:12.501  3509  4434 I TLC_TZ_KEYSTORE: : creating new keystore context...
12-20 11:58:12.501  3509  4434 I TLC_TZ_KEYSTORE: : initializing ccm context...
,12-20 11:58:12.501  3509  4434 I TLC_TZ_KEYSTORE: : root = 0, root_strlen = 1
12-20 11:58:12.501  3509  4434 I TLC_TZ_KEYSTORE: : process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:58:12.501  3509  4434 I TZ: mc_tlc_communication: input max_sendmsg_size = 1080
12-20 11:58:12.501  3509  4434 I TZ: mc_tlc_communication: input max_recvmsg_size = 1080
12-20 11:58:12.501  3509  4434 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-20 11:58:12.501  3509  4434 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:58:12.501  3509  4434 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 1088
12-20 11:58:12.501  3509  4434 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 1088
12-20 11:58:12.501  3509  4434 I TZ: mc_tlc_communication: device_id = 0x0
12-20 11:58:12.501  3509  4434 I TZ: mc_tlc_communication: tlc_open() was called
,12-20 11:58:12.501  3509  4434 I TZ: mc_tlc_communication: Opening MobiCore device
12-20 11:58:12.501  3509  4434 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-20 11:58:12.501  3509  4434 I TZ: mc_tlc_communication: Opening the session
,12-20 11:58:12.511  3960  3960 D KeyguardViewMediator: adjustStatusBarLocked: mShowing=false mOccluded=false isSecure=false --> flags=0x0
,12-20 11:58:12.511  3509  3791 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=com.android.systemui
,12-20 11:58:12.511  3960  3960 D KeyguardFingerPrint: setDisableFingerPrintBySecurityDialog( false )
,12-20 11:58:12.511  3509  3509 E MotionRecognitionService:   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
12-20 11:58:12.511  3509  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,12-20 11:58:12.511  3960  3960 D WallpaperService: updateSurface:[forceRelayout]false[redrawNeeded]false
12-20 11:58:12.511  3960  3960 D ImageWallpaper: onVisibilityChanged:true
,12-20 11:58:12.511  3960  3960 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
12-20 11:58:12.511  3960  3960 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
12-20 11:58:12.511  3509  3509 D ResourcesManager: For user 0 new overlays fetched Null
12-20 11:58:12.511  3960  3960 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
12-20 11:58:12.511  3509  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,12-20 11:58:12.511  3509  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
,12-20 11:58:12.521  3509  3509 D ResourcesManager: For user 0 new overlays fetched Null
,12-20 11:58:12.521  3960  3960 D PhoneStatusBar: makeExpandedInvisible: mExpandedVisible=false, state = 1
12-20 11:58:12.521  3509  3509 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
12-20 11:58:12.521  3509  3509 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
,12-20 11:58:12.521  3509  3509 D ResourcesManager: For user 0 new overlays fetched Null
,12-20 11:58:12.521  3509  3509 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
,12-20 11:58:12.521  3509  3509 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
,12-20 11:58:12.521  3509  3595 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{9ce7bae u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
12-20 11:58:12.521  3509  3509 D ResourcesManager: For user 0 new overlays fetched Null
12-20 11:58:12.521  3509  4434 I TZ: mc_tlc_communication: tlc_open() succeeded
12-20 11:58:12.521  3509  3509 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
12-20 11:58:12.521  3509  4434 I TLC_TZ_KEYSTORE: : ctx = 0x7f811eda40, comm = 0x7f7e72a7f0, sendmsg = 0x7f958fa000, recvmsg = 0x7f958fa440
,12-20 11:58:12.521  3509  4434 I TZ_init: : TZ_init: fips_init_TLC sending initialization request...
12-20 11:58:12.521  3509  4434 I TZ_init: : TZ_init: sending initialization request...
12-20 11:58:12.521  3509  3509 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.USER_PRESENT
12-20 11:58:12.521  3509  3509 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3509) 
,12-20 11:58:12.521  3509  3530 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
12-20 11:58:12.521  3509  3509 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=6) set Off
12-20 11:58:12.521  3509  3625 D LightsService: [SvcLED] handleForcedSvcLEDTask()
12-20 11:58:12.521  3509  3509 D UsbDeviceManager: Keyguard Lock/Unlock
,12-20 11:58:12.521  3509  3509 D UsbDeviceManager: updateUsbNotification : mConnected = true, mConfigured = true, mCurrentFunctions = mtp,adb
12-20 11:58:12.521  3509  3625 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
12-20 11:58:12.521  3509  3509 D UsbDeviceManager: mps exists
,12-20 11:58:12.521  3509  3509 D SecContentProvider: query(), uri = 18 selection = isUsbMediaPlayerAvailable
,12-20 11:58:12.531  3509  3925 D lights  : button : 0 +
12-20 11:58:12.531  3509  4441 D InputDispatcher: Focus left window: 3960
12-20 11:58:12.531  3509  4441 D InputDispatcher: Focus entered window: 4328
12-20 11:58:12.531  3509  4441 D PowerManagerService: [api] setUserActivityTimeoutOverrideFromWindowManagerInternal: timeoutMillis: -1
12-20 11:58:12.531  3509  4441 D PowerManagerService: [s] getScreenOffTimeoutLocked: 10000 -> 30000
12-20 11:58:12.531  3509  4441 D PowerManagerService: [api] setScreenDimDurationOverrideFromWindowManagerInternal: timeoutMillis: -1
,12-20 11:58:12.531  3509  3509 D UsbDeviceManager: isUsb30Enabled: read '/sys/class/android_usb/android0/bcdUSB', state = 0200
,12-20 11:58:12.531  3509  3509 D UsbDeviceManager: updateUsbNotification : cancel id = 17040367, title = Przesył. plików multimed. przez USB
12-20 11:58:12.531  3509  4334 V AlarmManager:  remove PendingIntent] PendingIntent{14172d7: PendingIntentRecord{3680e5b com.google.android.gms broadcastIntent}}
,12-20 11:58:12.531  3509  3615 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3509 uid:1000
12-20 11:58:12.531  3509  3615 D PointerIcon: setMouseCustomIcon IconType is same.101
,12-20 11:58:12.531  6319  6319 I TrayVisibilityController: UserPresentBroadcastReceiver : action = android.intent.action.USER_PRESENT
,12-20 11:58:12.531  3509  4007 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,12-20 11:58:12.541  3509  4434 I TZ_init: : TZ_init: successful initialization
12-20 11:58:12.541  3509  4434 I TLC_TZ_KEYSTORE: fips_self_test: : TZ_KEYSTORE_fips_self_test_START...
,12-20 11:58:12.541  3509  3509 D UsbDeviceManager: updateUsbNotification : isKeyguardShowingAndNotOccluded = false, isKeyguardSecure = false, mBootCompleted = true
,12-20 11:58:12.541  4304  9480 D NfcService: call the applyRouting
,12-20 11:58:12.541  4194  4194 I PeopleStripeVisibilityController: UserPresentBroadcastReceiver : action = android.intent.action.USER_PRESENT
12-20 11:58:12.541  3509  4434 I TLC_TZ_KEYSTORE: fips_self_test: : TZ_KEYSTORE_fips_self_test_END...
12-20 11:58:12.541  3509  4434 E TLC_TZ_KEYSTORE: : Self Test Succeded
12-20 11:58:12.541  3509  4434 I TZ: mc_tlc_communication: tlc_close() was called
12-20 11:58:12.541  3509  4434 I TZ: mc_tlc_communication: Closing the session
,12-20 11:58:12.541  7178  7178 D SamsungIME: IMPL finishInput
12-20 11:58:12.541  7178  7178 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
12-20 11:58:12.541  7178  7178 D SamsungIME: saveAndClear +
12-20 11:58:12.541  7178  7178 D SamsungIME: saveAndClear -
,12-20 11:58:12.541  3509  4434 I TZ: mc_tlc_communication: Freeing message buffer
12-20 11:58:12.541  3509  4434 I TZ: mc_tlc_communication: Closing MobiCore device
12-20 11:58:12.541  3509  4434 I TZ: mc_tlc_communication: tlc_close() succeeded
12-20 11:58:12.541  3509  4434 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
,12-20 11:58:12.541  7178  7178 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,12-20 11:58:12.541  3509  4434 I         : CCM JNI: In get_ccm_version
12-20 11:58:12.541  3509  4434 I TZ_CCM_C_Initialize: : DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
12-20 11:58:12.541  3509  4434 I TZ_CCM_C_Initialize: : pInitArgs 0x7f8e43e508 has not called C_Init before.
12-20 11:58:12.541  3509  4434 I TZ_CCM_C_Initialize: : &ctx = 0x7faae772a0
12-20 11:58:12.541  3509  4434 I TLC_TZ_CCM: : creating new ccm context...
12-20 11:58:12.541  3509  4434 I TLC_TZ_CCM: : initializing ccm context...
12-20 11:58:12.541  3509  4434 I TLC_TZ_CCM: : root = 0, root_strlen = 1
12-20 11:58:12.541  3509  4434 I TLC_TZ_CCM: : process = ffffffff000000000000000000000012, process_strlen = 32
12-20 11:58:12.541  3509  4434 I TZ: client_server_communication: input max_sendmsg_size = 19420
12-20 11:58:12.541  3509  4434 I TZ: client_server_communication: input max_recvmsg_size = 19420
,12-20 11:58:12.541  3509  4434 I TZ: client_server_communication: root = 0, root_len = 1
12-20 11:58:12.541  3509  4434 I TZ: client_server_communication: process = ffffffff000000000000000000000012, process_strlen = 32
12-20 11:58:12.541  3960  3960 D PhoneStatusBar: disable: < expand icons* alerts system_info* back home* recent* clock search* quick_settings >
12-20 11:58:12.541  3509  4434 I TZ: client_server_communication: aligned max_sendmsg_size = 19456
12-20 11:58:12.541  3509  4434 I TZ: client_server_communication: aligned max_recvmsg_size = 19456
12-20 11:58:12.541  3509  4434 I TZ: client_server_communication: Client_Server_Open was called
12-20 11:58:12.541  7178  7178 E SamsungIME: invoke(): method is null
12-20 11:58:12.541  7178  7178 D SamsungIME: showDlgMsgBox : false true true
12-20 11:58:12.541  6673  6673 E MtpService: In MTPAPP onReceive:android.intent.action.USER_PRESENT
12-20 11:58:12.541  6673  6673 E MtpService: Inside ACTION_USER_PRESENT:android.intent.action.USER_PRESENT
,12-20 11:58:12.541  3829  3848 I TLC_SERVER: BnTLCServer::onTransact(1598968902) 16
12-20 11:58:12.541  3829  3848 I TLC_SERVER: Unknown
,12-20 11:58:12.541  3509  4434 I TZ: client_server_communication: IClientServer::IClientServer()
12-20 11:58:12.541  3509  4434 I TZ: client_server_communication: BpClientServer::BpClientServer()
12-20 11:58:12.541  3829  3829 I TLC_SERVER: BnTLCServer::onTransact(0) 16
12-20 11:58:12.541  3829  3829 I TLC_SERVER: OPENSWCONN
,12-20 11:58:12.551  3829  3829 I TZ: mc_tlc_communication: input max_sendmsg_size = 19420
12-20 11:58:12.551  3829  3829 I TZ: mc_tlc_communication: input max_recvmsg_size = 19420
12-20 11:58:12.551  3829  3829 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-20 11:58:12.551  3829  3829 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000012, process_strlen = 32
12-20 11:58:12.551  3829  3829 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 19456
12-20 11:58:12.551  3829  3829 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 19456
12-20 11:58:12.551  3829  3829 I TZ: mc_tlc_communication: device_id = 0x0
12-20 11:58:12.551  3829  3829 I TZ: mc_tlc_communication: tlc_open() was called
12-20 11:58:12.551  3829  3829 I TZ: mc_tlc_communication: Opening MobiCore device
12-20 11:58:12.551  3829  3829 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
12-20 11:58:12.551  3829  3829 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-20 11:58:12.551  3829  3829 I TZ: mc_tlc_communication: Opening the session
,12-20 11:58:12.551  3509  3593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{32597c4 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6fe7727 4355:com.google.android.gms.persistent/u0a21}
,12-20 11:58:12.551  3509  3509 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = android,userId = -1
,12-20 11:58:12.551  3509  3509 D UsbDeviceManager: updateUsbNotification : notify id = 17040367, title = Przesył. plików multimed. przez USB
12-20 11:58:12.551  3509  3509 I MdnieScenarioControlService: action  :  android.intent.action.USER_PRESENT
,12-20 11:58:12.561  3509  3925 D lights  : button : 0 -
,12-20 11:58:12.561  3175  3651 D audio_hw_primary: start_output_stream (0xf112d6c0) out->pcm_device:6 out->config.rate:48000 out->config.format:0 out->period_size:240
12-20 11:58:12.561  3175  3651 D audio_hw_primary: start_output_stream (0xf112d6c0) out->config.rate:48000 out->config.format:0 out->period_size:240
12-20 11:58:12.561  3175  3651 V audio_hw_primary: select_devices output_scenario:0 input_scenario:-1 out_snd_device 0x2 in_snd_device:0x0
12-20 11:58:12.561  3175  3651 I audio_route: 
12-20 11:58:12.561  3175  3651 I audio_route: > audio_route_reset :
12-20 11:58:12.561  3175  3651 I audio_route: 
12-20 11:58:12.561  3175  3651 I audio_route: > audio_route_apply_path : "media-speaker"
,12-20 11:58:12.561  3509  4342 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{32597c4 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6fe7727 4355:com.google.android.gms.persistent/u0a21}
,12-20 11:58:12.561  3509  3509 D MdnieScenarioControlService:  packageName : com.sec.android.app.launcher    className : com.sec.android.app.launcher.activities.LauncherActivity
12-20 11:58:12.561  3509  3509 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
12-20 11:58:12.561  3509  3509 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
12-20 11:58:12.561  3509  3904 I MdnieScenarioControlService: mGameModeLauncher : false,
12-20 11:58:12.561  3509  3509 D UcmService: notifyChangeToPlugin event 16
12-20 11:58:12.561  3509  3509 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
12-20 11:58:12.561  3509  3904 I MdnieScenarioControlService: setUIMode
12-20 11:58:12.561  3509  3509 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
12-20 11:58:12.561  3509  3509 D UcmService: notifying to unmanaged plugin
,12-20 11:58:12.561  4378  4418 E ucsBai_agentService: notifyChange NOT SUPPORTED
12-20 11:58:12.561  3509  3509 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
12-20 11:58:12.561  3509  3509 D UcmService: agentService status-0
12-20 11:58:12.561  3509  3509 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.ese:eSE Credential Storage Package name = com.samsung.ucs.agent.ese
12-20 11:58:12.561  3509  3509 D UcmService: notifying to managed plugin
12-20 11:58:12.561  3509  3509 D UcmService: checkIfNotify: Valid userid - 0
12-20 11:58:12.561  3509  3509 D PolicyManager: PolicyManager.isStorageEnabled() for userId = 0
12-20 11:58:12.561  3509  3509 D UniversalCredentialManagerService: checkCallerPermissionFor is called for method-isCredentialStorageManagedAsUser
12-20 11:58:12.561  3509  3509 D UniversalCredentialManagerService: isCredentialStorageManagedAsUser is called....
12-20 11:58:12.561  4355  4355 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }.
12-20 11:58:12.561  3509  3509 D PolicyManager: PolicyManager.isStorageEnabled() result = false
12-20 11:58:12.561  3509  3509 D UcmService: agentService com.samsung.ucs.agent.ese:eSE Credential Storage not notified
12-20 11:58:12.561  3509  3509 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3509) 
12-20 11:58:12.561  3509  3509 D UcmService: agentService status-0
12-20 11:58:12.561  3509  3509 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
12-20 11:58:12.561  3509  3509 D UcmService: notifying to unmanaged plugin
,12-20 11:58:12.561  4396  4424 D BootAgentService: notifyChange eventId-16
12-20 11:58:12.561  3509  3509 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=6) set Off
12-20 11:58:12.561  3509  3509 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
12-20 11:58:12.561  3509  3625 D LightsService: [SvcLED] handleForcedSvcLEDTask()
12-20 11:58:12.561  3509  3509 D UcmService: agentService status--1
12-20 11:58:12.561  3509  3625 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
12-20 11:58:12.561  3509  3509 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
12-20 11:58:12.561  3509  3509 D EdgeLight: Turning off
12-20 11:58:12.561  3509  3509 I PalmMotion: [PALM] SURFACE_MOTION_ENGINE: 1 SURFACE_PALM_TOUCH: 1
12-20 11:58:12.561  3509  3509 I PalmMotion: [PALM] SURFACE_PALM_SWIPE: 1
,12-20 11:58:12.561  3509  3509 D PalmMotion: [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
12-20 11:58:12.561  3509  3509 D PalmMotion: [PALM] ACCEPTED : [hero2lte] PALM_CNT : 2, M_TOUCH : 50.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
,12-20 11:58:12.571  3509  3509 D MARsPolicyManager: NotificationListenerService OngoingNotificationRemoved : android
,12-20 11:58:12.571  3509  3509 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in null rsrc of package android
,12-20 11:58:12.571  3509  3509 D MARsPolicyManager: NotificationListenerService OngoingNotificationPosted : android
,12-20 11:58:12.571  4181  4912 D CatchNotificationsService: onNotificationRemoved
12-20 11:58:12.571  4181  4912 D CatchNotificationsService: Notification removed
,12-20 11:58:12.571  4194  4911 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=112]
12-20 11:58:12.571  4194  4194 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.people.package_name=android, samsung.people.notification_type=led_indicator}]
,12-20 11:58:12.581  4194  4194 I PeopleStripeService: PeopleNotificationReceiver:3
12-20 11:58:12.581  4194  4194 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
12-20 11:58:12.581  4194  4194 I PeopleDataManager: removeNotification
12-20 11:58:12.581  4194  4194 I NotificationParser: getNotiType:android,led_indicator
12-20 11:58:12.581  4194  4194 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=true,key=null,removeAll=false
12-20 11:58:12.581  4194  4194 D PeopleDataManager: removeNotiInfo =null
,12-20 11:58:12.581  3960  3960 D PhoneStatusBar: removeNotification key=-1|android|17040367|null|1000 old=StatusBarNotification(pkg=android user=UserHandle{-1} id=17040367 tag=null score=-20 key=-1|android|17040367|null|1000: Notification(pri=-2 contentView=android/0x10900a3 vibrate=null sound=null tick defaults=0x0 flags=0x2 color=0xff7792a9 vis=PUBLIC secFlags=0x0 secPriority=0))
12-20 11:58:12.581  3960  3960 D PhoneStatusBar: setAreThereNotifications: N=0 any=false clearable=false
12-20 11:58:12.581  4194  4911 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17040367,extra=Bundle[mParcelledData.dataSize=84]
,12-20 11:58:12.581  4194  4194 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17040367, samsung.notification.type=normal, samsung.people.package_name=android}]
12-20 11:58:12.581  4194  4194 I PeopleStripeService: PeopleNotificationReceiver:3
,12-20 11:58:12.581  4194  4194 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
12-20 11:58:12.581  4194  4194 I PeopleDataManager: removeNotification
12-20 11:58:12.581  4194  4194 I NotificationParser: getNotiType:android,null
12-20 11:58:12.581  4194  4194 D PeopleDataManager: removeNotiInfo: id =17040367,packageName=android,isEdgeNotification=false,key=null,removeAll=false
12-20 11:58:12.581  4194  4194 D PeopleDataManager: removeNotiInfo =null
,12-20 11:58:12.581  3829  3829 I TZ: mc_tlc_communication: tlc_open() succeeded
,12-20 11:58:12.581  3509  4434 I TZ: client_server_communication: OpenSWConn(CCM) is successful
12-20 11:58:12.581  3509  4434 I TZ: client_server_communication: Client_Server_Open succeeded, serverName = CCM
12-20 11:58:12.581  3509  4434 I TZ_CCM_C_Initialize: : ctx = 0x7f811eda40, comm = 0x7f7e72a7f0, sendmsg = 0x7f897f5000, recvmsg = 0x7f897f9c00
,12-20 11:58:12.581  3509  4434 I TZ_init: : TZ_init: sending initialization request...
12-20 11:58:12.581  3509  4434 E TZ: client_server_communication: comm_request(0x7f7e72a7f0) pImpl->serverName : CCM 
12-20 11:58:12.581  3509  4434 E TZ: client_server_communication: comm_request(0x7f7e72a7f0) <IClientServer>pImpl->sconn : 0x7f811feb40 
12-20 11:58:12.581  3509  4434 E TZ: client_server_communication: comm_request(0x7f7e72a7f0) <IClientServer>pImpl->sconn->getInterfaceDescriptor() : CCM 
12-20 11:58:12.581  3509  4434 I TZ: client_server_communication: Cmd id = 2, len = 19456
12-20 11:58:12.581  3509  4434 I TZ: client_server_communication: Calling Communicate()
12-20 11:58:12.581  6319  6319 I CocktailBarUiController: onUpdateCocktail: 2
12-20 11:58:12.581  6319  6319 I CocktailBarPanelManager: updatePanelItem: updateContainedPanel - 2
12-20 11:58:12.581  6319  6319 D CatchNotificationsView: setData
12-20 11:58:12.581  6319  6319 D CatchNotificationsView: Notification removed
12-20 11:58:12.581  6319  6319 D CatchNotificationsView: No notifications left to remove
,12-20 11:58:12.581  6319  6319 D CatchNotificationsView: makeNoNotificationsPanel
12-20 11:58:12.581  3829  3848 I TLC_SERVER: BnTLCServer::onTransact(2) 16
12-20 11:58:12.581  3829  3848 I TLC_SERVER: COMM
,12-20 11:58:12.581  6319  6319 W ResourcesManager: getTopLevelResources: /system/priv-app/AppsEdgePanel/AppsEdgePanel.apk / 1.0 running in com.samsung.android.app.cocktailbarservice rsrc of package com.samsung.android.app.appsedge
,12-20 11:58:12.581  6319  6319 W ResourcesManager: getTopLevelResources: /system/priv-app/AppsEdgePanel/AppsEdgePanel.apk / 1.0 running in com.samsung.android.app.cocktailbarservice rsrc of package com.samsung.android.app.appsedge
12-20 11:58:12.581  6319  6319 D PanelDescriptionView: updateHelpView: Apps edge2130903041 --> 2130903041 helpview reapplied:0
,12-20 11:58:12.591  3509  4334 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{32597c4 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6fe7727 4355:com.google.android.gms.persistent/u0a21}
,12-20 11:58:12.591  6319  6319 W ResourcesManager: getTopLevelResources: /system/priv-app/AppsEdgePanel/AppsEdgePanel.apk / 1.0 running in com.samsung.android.app.cocktailbarservice rsrc of package com.samsung.android.app.appsedge
12-20 11:58:12.591  6319  6319 D CocktailBarUiController: postUpdatePanel: 257
,12-20 11:58:12.591  4181  4912 D CatchNotificationsService: onNotificationPosted
,12-20 11:58:12.601  3960  3960 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,12-20 11:58:12.601  3509  4334 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{32597c4 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8a82cf8 9251:com.samsung.android.sm/1000}
,12-20 11:58:12.611  3960  3960 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,12-20 11:58:12.631  8550  8578 D BadgeProvider: query, [selection] : null
,12-20 11:58:12.631  3960  3960 D PhoneStatusBar: setAreThereNotifications: N=1 any=true clearable=false
,12-20 11:58:12.631  3960  3960 D PhoneStatusBar: hideKeyguard: state - 1, leaveOpen: false
12-20 11:58:12.631  3960  3960 D PhoneStatusBar: setBarState: state - 0
12-20 11:58:12.631  3960  3960 D StatusBar-Window: fnf=true sanc=false, kni=false, sbf=false
12-20 11:58:12.631  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:58:12.631  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : false panelVisible : false keyguardFadingAway : true bouncerShowing : false headsUpShowing : false
12-20 11:58:12.631  3960  3960 D CoverUI : applyHeight h = -1, oc = false, fa = true, ac = false, sc = false
12-20 11:58:12.631  3960  3960 I PhoneStatusBar: updateKeyguardState 1 to 0
,12-20 11:58:12.641  3960  3960 D PanelView: setKeyguardBottomAreaVisibility() prevState=1, newState - 0 goingToShade - false
,12-20 11:58:12.641  3960  3960 D PanelView: updateQsState
12-20 11:58:12.641  4181  4912 D CatchNotificationsSupportedAppsDBHelper: isDisabled value : false
12-20 11:58:12.641  4181  4912 D CatchNotificationsSupportedAppsDBHelper: isPackageSupported value : false
12-20 11:58:12.641  4181  4912 D CatchNotificationsService: Notification from package is not supported
,12-20 11:58:12.651  3960  3960 D KeyguardSecurityModel: getSecurityMode( getActivePasswordQuality = 0 , currentuser = 0
,12-20 11:58:12.651  3960  3960 D StatusBar-Window: fnf=true sanc=false, kni=false, sbf=false
12-20 11:58:12.651  3960  3960 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
12-20 11:58:12.651  3960  3960 D StatusBarWindowManager: forceCollapsed : false isKeyguardShowingAndNotOccluded() : false panelVisible : false keyguardFadingAway : false bouncerShowing : false headsUpShowing : false
12-20 11:58:12.651  3960  3960 D CoverUI : applyHeight h = 96, oc = false, fa = false, ac = false, sc = false
12-20 11:58:12.651  3960  3960 D KeyguardEffectViewController: setKeyguardFadingAway = false
12-20 11:58:12.651  3960  3960 D KeyguardEffectViewController: mShowing=false, mOccluded=false, mKeyguardFadingAway=false, match_parent=true
12-20 11:58:12.651  3960  3960 D KeyguardEffectViewController: ## mBackgroundView.onPause()
12-20 11:58:12.651  3960  3960 D KeyguardEffectViewLayered: onPause()
,12-20 11:58:12.651  3960  4234 D BluetoothTile: handleUpdateState :  supported = true, enabled = true, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,12-20 11:58:12.651  3960  4234 D AirplaneModeTile: getQSTileMultiState 1
,12-20 11:58:12.651  3960  4234 D FlashlightTile: handleUpdateState :  MultiState[visible=true,icon=ResourceIcon[resId=0x7f020363],label=Latarka,contentDescription=Latarka Przycisk Wył.,dualLabelContentDescription=null,autoMirrorDrawable=false,secondaryLabel=null,textTruncate=true,value=2,bgValue=0] arg : null
,12-20 11:58:12.661  3960  4234 D HotspotTile: handleUpdateState :mState.value =  2, 2
,12-20 11:58:12.661  3960  4234 D PersonalModeTile: getMState state = 2
,12-20 11:58:12.661  3960  4234 D AodTile :  ExclusiveFeature getCount = 0
,12-20 11:58:12.661  3960  4234 D AodTile : handleUpdateState :  MultiState[visible=true,icon=ResourceIcon[resId=0x7f020367],label=Always On
12-20 11:58:12.661  3960  4234 D AodTile : Display,contentDescription=Always On Display Przycisk Wł.,dualLabelContentDescription=null,autoMirrorDrawable=false,secondaryLabel=null,textTruncate=false,value=1,bgValue=0] arg : null
,12-20 11:58:12.681  3175  3651 V audio_hw_primary: select_devices() output_route "media-speaker" 
12-20 11:58:12.681  3175  3651 I audio_route: 
12-20 11:58:12.681  3175  3651 I audio_route: > audio_route_apply_path : "gain-media-speaker"
12-20 11:58:12.681  3175  3651 V audio_hw_primary: select_devices() output_gain "gain-media-speaker" 
12-20 11:58:12.681  3175  3651 I audio_route: 
12-20 11:58:12.681  3175  3651 I audio_route: > audio_route_update_mixer : +
12-20 11:58:12.681  3175  3651 I audio_route: > audio_route_update_mixer : changed(0) -
12-20 11:58:12.681  3175  3651 I audio_hw_primary: select_devices - 
12-20 11:58:12.681  3018  3028 D libEGL  : eglTerminate EGLDisplay = 0x7fa9ac0e78
12-20 11:58:12.681  3175  3651 V audio_hw_primary: start_output_stream-
12-20 11:58:12.681  3018  3028 D libEGL  : eglTerminate EGLDisplay = 0x7fa9ac0e78
,12-20 11:58:12.681  3960  4161 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x96]-format:1
,12-20 11:58:12.681  3960  3960 D KeyguardEffectViewController: onLayoutChange() v: com.android.keyguard.effect.EffectBehindView{eefe3f3 I.E...... ......ID 0,0-1440,96 #7f0e0330 app:id/keyguard_effect_behind}, bottom : 96, oldBottom : 2560
12-20 11:58:12.681  3960  3960 D KeyguardEffectViewController: mShowing=false, mOccluded=false, mKeyguardFadingAway=false, match_parent=false
,12-20 11:58:12.681  3960  3960 W View    : requestLayout() improperly called by com.android.systemui.qs.QSContainer{c359d8d V.E...... ......ID 0,464-1440,1212 #7f0e01c1 app:id/quick_settings_container} during layout: running second layout pass
12-20 11:58:12.681  3960  3960 I ViewRootImpl: requestLayout is already in process
,12-20 11:58:12.701  3509  4434 I TZ_init: : TZ_init: successful initialization
12-20 11:58:12.701  3509  4434 I TLC_TZ_COMMON: key_db_init: : Exercising TZ_DB_INIT in TLC
12-20 11:58:12.701  3509  4434 E TZ: client_server_communication: comm_request(0x7f7e72a7f0) pImpl->serverName : CCM 
12-20 11:58:12.701  3509  4434 E TZ: client_server_communication: comm_request(0x7f7e72a7f0) <IClientServer>pImpl->sconn : 0x7f811feb40 
12-20 11:58:12.701  3509  4434 E TZ: client_server_communication: comm_request(0x7f7e72a7f0) <IClientServer>pImpl->sconn->getInterfaceDescriptor() : CCM 
12-20 11:58:12.701  3509  4434 I TZ: client_server_communication: Cmd id = 17, len = 19456
12-20 11:58:12.701  3509  4434 I TZ: client_server_communication: Calling Communicate()
,12-20 11:58:12.711  3829  3829 I TLC_SERVER: BnTLCServer::onTransact(2) 16
12-20 11:58:12.711  3829  3829 I TLC_SERVER: COMM
,12-20 11:58:12.721  3509  4434 I TZ_COMMON: tlc_key_db_util: : DB Operation suceeded
,12-20 11:58:12.721  3509  4434 E TZ: client_server_communication: comm_request(0x7f7e72a7f0) pImpl->serverName : CCM 
12-20 11:58:12.721  3509  4434 E TZ: client_server_communication: comm_request(0x7f7e72a7f0) <IClientServer>pImpl->sconn : 0x7f811feb40 
12-20 11:58:12.721  3509  4434 E TZ: client_server_communication: comm_request(0x7f7e72a7f0) <IClientServer>pImpl->sconn->getInterfaceDescriptor() : CCM 
12-20 11:58:12.721  3509  4434 I TZ: client_server_communication: Cmd id = 46, len = 19456
12-20 11:58:12.721  3509  4434 I TZ: client_server_communication: Calling Communicate()
12-20 11:58:12.721  3829  3848 I TLC_SERVER: BnTLCServer::onTransact(2) 16
12-20 11:58:12.721  3829  3848 I TLC_SERVER: COMM
,12-20 11:58:12.731  3509  4434 I TZ_CCM_C_Finalize: : DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
,12-20 11:58:12.731  3509  4434 E TZ: client_server_communication: comm_request(0x7f7e72a7f0) pImpl->serverName : CCM 
12-20 11:58:12.731  3509  4434 E TZ: client_server_communication: comm_request(0x7f7e72a7f0) <IClientServer>pImpl->sconn : 0x7f811feb40 
12-20 11:58:12.731  3509  4434 E TZ: client_server_communication: comm_request(0x7f7e72a7f0) <IClientServer>pImpl->sconn->getInterfaceDescriptor() : CCM 
12-20 11:58:12.731  3509  4434 I TZ: client_server_communication: Cmd id = 41, len = 19456
12-20 11:58:12.731  3509  4434 I TZ: client_server_communication: Calling Communicate()
12-20 11:58:12.731  3829  3829 I TLC_SERVER: BnTLCServer::onTransact(2) 16
12-20 11:58:12.731  3829  3829 I TLC_SERVER: COMM
,12-20 11:58:12.731  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:58:12.731  3018  3018 D libEGL  : eglTerminate EGLDisplay = 0x7fff7e5b48
,12-20 11:58:12.741  3509  4434 I TZ: client_server_communication: Client_Server_Close was called
,12-20 11:58:12.741  3829  3848 I TLC_SERVER: BnTLCServer::onTransact(1) 16
12-20 11:58:12.741  3829  3848 I TLC_SERVER: CLOSESWCONN
12-20 11:58:12.741  3829  3848 I TZ: mc_tlc_communication: tlc_close() was called
12-20 11:58:12.741  3829  3848 I TZ: mc_tlc_communication: Closing the session
,12-20 11:58:12.741  3829  3848 I TZ: mc_tlc_communication: Freeing message buffer
,12-20 11:58:12.741  3829  3848 I TZ: mc_tlc_communication: Closing MobiCore device
,12-20 11:58:12.741  3829  3848 I TeeDriverClient: driver client closed [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:113]
,12-20 11:58:12.741  3509  4434 D TimaService: TIMA3: FipsKeyStore3_exist
12-20 11:58:12.741  3829  3848 I TZ: mc_tlc_communication: tlc_close() succeeded
12-20 11:58:12.741  3509  4434 D TimaService: TIMA: in getTimaVersion
12-20 11:58:12.741  3509  4434 I TZ: client_server_communication: Client_Server_Close succeeded
12-20 11:58:12.741  3509  4434 I TZ: client_server_communication: IClientServer::~IClientServer()
12-20 11:58:12.741  3509  4434 I FipsTimaKeyStore: CCM is available on this device
12-20 11:58:12.741  3509  4434 I FipsTimaKeyStore: CCM is NOT enabled for this user
12-20 11:58:12.741  3509  4434 I         : TimaKeyStore: tima_KeyStore3_exist_JNI
12-20 11:58:12.741  3509  4434 I         : TimaKeyStore: callingUid is 1000
12-20 11:58:12.751  3509  4434 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_encrypt_filename()
12-20 11:58:12.751  3509  4434 I TLC_TZ_KEYSTORE: : creating new keystore context...
12-20 11:58:12.751  3509  4434 I TLC_TZ_KEYSTORE: : initializing ccm context...
12-20 11:58:12.751  3509  4434 I TLC_TZ_KEYSTORE: : root = 0, root_strlen = 1
12-20 11:58:12.751  3509  4434 I TLC_TZ_KEYSTORE: : process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:58:12.751  3509  4434 I TZ: mc_tlc_communication: input max_sendmsg_size = 1080
12-20 11:58:12.751  3509  4434 I TZ: mc_tlc_communication: input max_recvmsg_size = 1080
12-20 11:58:12.751  3509  4434 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-20 11:58:12.751  3509  4434 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:58:12.751  3509  4434 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 1088
12-20 11:58:12.751  3509  4434 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 1088
12-20 11:58:12.751  3509  4434 I TZ: mc_tlc_communication: device_id = 0x0
12-20 11:58:12.751  3509  4434 I TZ: mc_tlc_communication: tlc_open() was called
12-20 11:58:12.751  3509  4434 I TZ: mc_tlc_communication: Opening MobiCore device
12-20 11:58:12.751  3509  4434 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-20 11:58:12.751  3509  4434 I TZ: mc_tlc_communication: Opening the session
12-20 11:58:12.751  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:58:12.761  3509  4434 I TZ: mc_tlc_communication: tlc_open() succeeded
,12-20 11:58:12.761  3509  4434 I TLC_TZ_KEYSTORE: : ctx = 0x7f811eda40, comm = 0x7f7e72a7f0, sendmsg = 0x7f958fa000, recvmsg = 0x7f958fa440
12-20 11:58:12.761  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ_COMMON: Get_filename - allow_hashing: 0
12-20 11:58:12.761  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ GetFN : priv_data.in_filename: 1000_KS_SKEY_PersonaPwdResetToken0, len: 34
12-20 11:58:12.761  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ CCM : priv_data.in_fn_len: 34
12-20 11:58:12.761  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ GetFN : Starting
,12-20 11:58:12.771  3018  3018 D libEGL  : eglInitialize EGLDisplay = 0x7fff7e5ab8
,12-20 11:58:12.771  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ GetFN : enc filename: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
,12-20 11:58:12.771  3509  4434 I TZ: mc_tlc_communication: tlc_close() was called
12-20 11:58:12.771  3509  4434 I TZ: mc_tlc_communication: Closing the session
,12-20 11:58:12.781  3509  4434 I TZ: mc_tlc_communication: Freeing message buffer
12-20 11:58:12.781  3509  4434 I TZ: mc_tlc_communication: Closing MobiCore device
12-20 11:58:12.781  3509  4434 I TZ: mc_tlc_communication: tlc_close() succeeded
12-20 11:58:12.781  3509  4434 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
12-20 11:58:12.781  3509  4434 D TimaService: TIMA3: FipsKeyStore3_exist
12-20 11:58:12.781  3509  4434 I         : TimaKeyStore: encryptFilename : filename is: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
12-20 11:58:12.781  3509  4434 D TimaService: TIMA: in getTimaVersion
,12-20 11:58:12.781  3509  4434 I         : TimaKeyStore: /data/misc/fips_tima_keystore/user_0/057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E exists
12-20 11:58:12.781  3509  4434 I         : TimaKeyStore: tima_KeyStore3_exist_JNI
12-20 11:58:12.781  3509  4434 I         : TimaKeyStore: callingUid is 1000
12-20 11:58:12.781  3509  4434 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_encrypt_filename()
12-20 11:58:12.781  3509  4434 I TLC_TZ_KEYSTORE: : creating new keystore context...
12-20 11:58:12.781  3509  4434 I TLC_TZ_KEYSTORE: : initializing ccm context...
12-20 11:58:12.781  3509  4434 I TLC_TZ_KEYSTORE: : root = 0, root_strlen = 1
12-20 11:58:12.781  3509  4434 I TLC_TZ_KEYSTORE: : process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:58:12.781  3509  4434 I TZ: mc_tlc_communication: input max_sendmsg_size = 1080
12-20 11:58:12.781  3509  4434 I TZ: mc_tlc_communication: input max_recvmsg_size = 1080
12-20 11:58:12.781  3509  4434 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-20 11:58:12.781  3509  4434 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:58:12.781  3509  4434 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 1088
12-20 11:58:12.781  3509  4434 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 1088
,12-20 11:58:12.781  3509  4434 I TZ: mc_tlc_communication: device_id = 0x0
12-20 11:58:12.781  3509  4434 I TZ: mc_tlc_communication: tlc_open() was called
12-20 11:58:12.781  3509  4434 I TZ: mc_tlc_communication: Opening MobiCore device
12-20 11:58:12.781  3509  4434 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-20 11:58:12.781  3509  4434 I TZ: mc_tlc_communication: Opening the session
,12-20 11:58:12.791  3509  4434 I TZ: mc_tlc_communication: tlc_open() succeeded
,12-20 11:58:12.791  3509  4434 I TLC_TZ_KEYSTORE: : ctx = 0x7f811eda40, comm = 0x7f7e72a7f0, sendmsg = 0x7f958fa000, recvmsg = 0x7f958fa440
12-20 11:58:12.791  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ_COMMON: Get_filename - allow_hashing: 0
12-20 11:58:12.791  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ GetFN : priv_data.in_filename: 1000_KS_SKEY_PersonaPwdResetToken0, len: 34
12-20 11:58:12.791  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ CCM : priv_data.in_fn_len: 34
12-20 11:58:12.791  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ GetFN : Starting
,12-20 11:58:12.801  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ GetFN : enc filename: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
,12-20 11:58:12.801  3509  4434 I TZ: mc_tlc_communication: tlc_close() was called
12-20 11:58:12.801  3509  4434 I TZ: mc_tlc_communication: Closing the session
,12-20 11:58:12.811  3509  4434 I TZ: mc_tlc_communication: Freeing message buffer
,12-20 11:58:12.811  3509  4434 I TZ: mc_tlc_communication: Closing MobiCore device
12-20 11:58:12.811  3509  4434 I TZ: mc_tlc_communication: tlc_close() succeeded
12-20 11:58:12.811  3509  4434 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
12-20 11:58:12.811  3509  4434 I         : TimaKeyStore: encryptFilename : filename is: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
12-20 11:58:12.811  3509  4434 I         : TimaKeyStore: /data/misc/fips_tima_keystore/user_0/057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E exists
,12-20 11:58:12.811  3509  4434 I         : TimaKeyStore: tima_KeyStore3_exist_JNI
,12-20 11:58:12.811  3509  4434 D TimaService: TIMA3: FipsKeyStore3_exist
12-20 11:58:12.811  3509  4434 I         : TimaKeyStore: callingUid is 1000
12-20 11:58:12.811  3509  4434 D TimaService: TIMA: in getTimaVersion
12-20 11:58:12.811  3509  4434 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_encrypt_filename()
12-20 11:58:12.811  3509  4434 I TLC_TZ_KEYSTORE: : creating new keystore context...
12-20 11:58:12.811  3509  4434 I TLC_TZ_KEYSTORE: : initializing ccm context...
12-20 11:58:12.811  3509  4434 I TLC_TZ_KEYSTORE: : root = 0, root_strlen = 1
12-20 11:58:12.811  3509  4434 I TLC_TZ_KEYSTORE: : process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:58:12.811  3509  4434 I TZ: mc_tlc_communication: input max_sendmsg_size = 1080
12-20 11:58:12.811  3509  4434 I TZ: mc_tlc_communication: input max_recvmsg_size = 1080
,12-20 11:58:12.811  3509  4434 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-20 11:58:12.811  3509  4434 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:58:12.811  3509  4434 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 1088
12-20 11:58:12.811  3509  4434 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 1088
12-20 11:58:12.811  3509  4434 I TZ: mc_tlc_communication: device_id = 0x0
12-20 11:58:12.811  3509  4434 I TZ: mc_tlc_communication: tlc_open() was called
12-20 11:58:12.811  3509  4434 I TZ: mc_tlc_communication: Opening MobiCore device
,12-20 11:58:12.811  3509  4434 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-20 11:58:12.811  3509  4434 I TZ: mc_tlc_communication: Opening the session
,12-20 11:58:12.821  3182  3221 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, 90, -102, 72, 1, 1
,12-20 11:58:12.821  3509  3839 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, 90, -102, 72, 1, 1
12-20 11:58:12.821  3509  3838 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
12-20 11:58:12.821  3509  3838 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
12-20 11:58:12.821  3509  3838 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, 90, -102, 72, 1, 1,
12-20 11:58:12.821  3509  3838 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
12-20 11:58:12.821  3509  3838 I CAE     : display(ContextProvider.java:391) - Accuracy=[1], OperationMode=[0], ActivityType=[1], TimeStamp=[1482231492168]
,12-20 11:58:12.831  3509  3841 D SContextService: updateSContext() : event = Activity Tracker
12-20 11:58:12.831  3509  3509 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
,12-20 11:58:12.831  3509  3509 D WifiService: ACTIVITY_STATUS_STATIONARY 
12-20 11:58:12.831  3509  4434 I TZ: mc_tlc_communication: tlc_open() succeeded
12-20 11:58:12.831  3509  4434 I TLC_TZ_KEYSTORE: : ctx = 0x7f811eda40, comm = 0x7f7e72a7f0, sendmsg = 0x7f958fa000, recvmsg = 0x7f958fa440
,12-20 11:58:12.831  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ_COMMON: Get_filename - allow_hashing: 0
12-20 11:58:12.831  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ GetFN : priv_data.in_filename: 1000_KS_SKEY_PersonaPwdResetToken0, len: 34
12-20 11:58:12.831  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ CCM : priv_data.in_fn_len: 34
12-20 11:58:12.831  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ GetFN : Starting
,12-20 11:58:12.831  6319  6319 I TrayVisibilityController: handleMessage : msg.what = 1
,12-20 11:58:12.831  6319  6319 I Utils   : isCurrentUser current = 0, ownerId = 0
,12-20 11:58:12.831  6319  6319 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 1
12-20 11:58:12.831  6319  6319 I TrayVisibilityController: updateTrayVisible : State : 1 visible = 1 mCurrentVisible = 1
12-20 11:58:12.831  6319  6319 D TrayStateController: onNotifyUpdateTray: 0 to need to visible? true
,12-20 11:58:12.831  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ GetFN : enc filename: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
,12-20 11:58:12.831  3509  4434 I TZ: mc_tlc_communication: tlc_close() was called
12-20 11:58:12.831  3509  4434 I TZ: mc_tlc_communication: Closing the session
,12-20 11:58:12.841  3509  4434 I TZ: mc_tlc_communication: Freeing message buffer
,12-20 11:58:12.841  3509  4434 I TZ: mc_tlc_communication: Closing MobiCore device
12-20 11:58:12.841  3509  4434 D TimaService: TIMA3: FipsKeyStore3_exist
12-20 11:58:12.841  3509  4434 I TZ: mc_tlc_communication: tlc_close() succeeded
12-20 11:58:12.841  3509  4434 D TimaService: TIMA: in getTimaVersion
12-20 11:58:12.841  3509  4434 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
12-20 11:58:12.841  3509  4434 I         : TimaKeyStore: encryptFilename : filename is: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
12-20 11:58:12.841  3509  4434 I         : TimaKeyStore: /data/misc/fips_tima_keystore/user_0/057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E exists
12-20 11:58:12.841  3509  4434 I         : TimaKeyStore: tima_KeyStore3_exist_JNI
12-20 11:58:12.841  3509  4434 I         : TimaKeyStore: callingUid is 1000
12-20 11:58:12.841  3509  4434 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_encrypt_filename()
12-20 11:58:12.841  3509  4434 I TLC_TZ_KEYSTORE: : creating new keystore context...
12-20 11:58:12.841  3509  4434 I TLC_TZ_KEYSTORE: : initializing ccm context...
,12-20 11:58:12.841  3509  4434 I TLC_TZ_KEYSTORE: : root = 0, root_strlen = 1
12-20 11:58:12.841  3509  4434 I TLC_TZ_KEYSTORE: : process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:58:12.841  3509  4434 I TZ: mc_tlc_communication: input max_sendmsg_size = 1080
12-20 11:58:12.841  3509  4434 I TZ: mc_tlc_communication: input max_recvmsg_size = 1080
12-20 11:58:12.841  3509  4434 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-20 11:58:12.841  3509  4434 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:58:12.841  3509  4434 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 1088
12-20 11:58:12.841  3509  4434 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 1088
12-20 11:58:12.841  3509  4434 I TZ: mc_tlc_communication: device_id = 0x0
12-20 11:58:12.841  3509  4434 I TZ: mc_tlc_communication: tlc_open() was called
,12-20 11:58:12.841  3509  4434 I TZ: mc_tlc_communication: Opening MobiCore device
12-20 11:58:12.841  3509  4434 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-20 11:58:12.841  3509  4434 I TZ: mc_tlc_communication: Opening the session
,12-20 11:58:12.841  4194  4194 I PeopleStripeVisibilityController: handleMessage : msg.what = 1
12-20 11:58:12.841  4194  4194 I PeopleStripeVisibilityController: getComputedTrayVisible : keyguardState = 1
12-20 11:58:12.841  4194  4194 I PeopleStripeVisibilityController: isVisibleByAlwaysOn : mState = 1
,12-20 11:58:12.841  4194  4194 I PeopleStripeProcessMonitor: isPeopleStripeTask packageName = com.sec.android.app.launcher 0
,12-20 11:58:12.841  4194  4194 I PeopleStripeVisibilityController: updateStripeVisible : State 1 visible = 1
12-20 11:58:12.841  4194  4194 I PeopleStripeManager: isExistVisibleHandler false
12-20 11:58:12.841  4194  4194 I PeopleStripeManager: showStripe Not exist noti handler.
,12-20 11:58:12.851  3509  4434 I TZ: mc_tlc_communication: tlc_open() succeeded
,12-20 11:58:12.851  3509  4434 I TLC_TZ_KEYSTORE: : ctx = 0x7f811eda40, comm = 0x7f7e72a7f0, sendmsg = 0x7f958fa000, recvmsg = 0x7f958fa440
12-20 11:58:12.851  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ_COMMON: Get_filename - allow_hashing: 0
12-20 11:58:12.851  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ GetFN : priv_data.in_filename: 1000_KS_SKEY_PersonaPwdResetToken0, len: 34
12-20 11:58:12.851  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ CCM : priv_data.in_fn_len: 34
12-20 11:58:12.851  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ GetFN : Starting
,12-20 11:58:12.861  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ GetFN : enc filename: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
,12-20 11:58:12.861  3509  4434 I TZ: mc_tlc_communication: tlc_close() was called
12-20 11:58:12.861  3509  4434 I TZ: mc_tlc_communication: Closing the session
,12-20 11:58:12.871  3509  4434 I TZ: mc_tlc_communication: Freeing message buffer
,12-20 11:58:12.871  3509  4434 I TZ: mc_tlc_communication: Closing MobiCore device
12-20 11:58:12.871  3509  4434 I TZ: mc_tlc_communication: tlc_close() succeeded
12-20 11:58:12.871  3509  4434 D TimaService: TIMA3: FipsKeyStore3_get
12-20 11:58:12.871  3509  4434 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
12-20 11:58:12.871  3509  4434 D TimaService: TIMA: in getTimaVersion
12-20 11:58:12.871  3509  4434 I         : TimaKeyStore: encryptFilename : filename is: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
12-20 11:58:12.871  3509  4434 I         : TimaKeyStore: /data/misc/fips_tima_keystore/user_0/057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E exists
,12-20 11:58:12.871  3509  4434 I         : TimaKeyStore: tima_KeyStore3_get_JNI
12-20 11:58:12.871  3509  4434 I         : TimaKeyStore: callingUid is 1000
12-20 11:58:12.871  3509  4434 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_encrypt_filename()
12-20 11:58:12.871  3509  4434 I TLC_TZ_KEYSTORE: : creating new keystore context...
12-20 11:58:12.871  3509  4434 I TLC_TZ_KEYSTORE: : initializing ccm context...
12-20 11:58:12.871  3509  4434 I TLC_TZ_KEYSTORE: : root = 0, root_strlen = 1
12-20 11:58:12.871  3509  4434 I TLC_TZ_KEYSTORE: : process = ffffffff000000000000000000000013, process_strlen = 32
,12-20 11:58:12.871  3509  4434 I TZ: mc_tlc_communication: input max_sendmsg_size = 1080
12-20 11:58:12.871  3509  4434 I TZ: mc_tlc_communication: input max_recvmsg_size = 1080
12-20 11:58:12.871  3509  4434 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-20 11:58:12.871  3509  4434 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:58:12.871  3509  4434 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 1088
12-20 11:58:12.871  3509  4434 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 1088
12-20 11:58:12.871  3509  4434 I TZ: mc_tlc_communication: device_id = 0x0
12-20 11:58:12.871  3509  4434 I TZ: mc_tlc_communication: tlc_open() was called
,12-20 11:58:12.871  3509  4434 I TZ: mc_tlc_communication: Opening MobiCore device
12-20 11:58:12.871  3509  4434 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-20 11:58:12.871  3509  4434 I TZ: mc_tlc_communication: Opening the session
,12-20 11:58:12.891  3509  4434 I TZ: mc_tlc_communication: tlc_open() succeeded
,12-20 11:58:12.891  3509  4434 I TLC_TZ_KEYSTORE: : ctx = 0x7f811eda40, comm = 0x7f7e72a7f0, sendmsg = 0x7f958fa000, recvmsg = 0x7f958fa440
12-20 11:58:12.891  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ_COMMON: Get_filename - allow_hashing: 0
12-20 11:58:12.891  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ GetFN : priv_data.in_filename: 1000_KS_SKEY_PersonaPwdResetToken0, len: 34
12-20 11:58:12.891  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ CCM : priv_data.in_fn_len: 34
12-20 11:58:12.891  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ GetFN : Starting
,12-20 11:58:12.901  3509  4434 I TLC_TZ_COMMON: get_filename: : TZ GetFN : enc filename: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
,12-20 11:58:12.901  3509  4434 I TZ: mc_tlc_communication: tlc_close() was called
12-20 11:58:12.901  3509  4434 I TZ: mc_tlc_communication: Closing the session
,12-20 11:58:12.901  3509  4434 I TZ: mc_tlc_communication: Freeing message buffer
,12-20 11:58:12.901  3509  4434 I TZ: mc_tlc_communication: Closing MobiCore device
,12-20 11:58:12.901  3509  4434 I TZ: mc_tlc_communication: tlc_close() succeeded
,12-20 11:58:12.901  3509  4434 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
,12-20 11:58:12.901  3509  4434 I         : TimaKeyStore: encryptFilename : filename is: 057571D50A77E8E7D8C4159850B2DC87150CE858D8DD6EF02D5A463D82E2AEC0D2CA255037E60A2498841E142829E0FB3DD4ED6071717481986EA5DD2E19118E
12-20 11:58:12.901  3509  4434 I TLC_TZ_KEYSTORE: : TZ_KEYSTORE_fips_unwrap_key
12-20 11:58:12.901  3509  4434 I TLC_TZ_KEYSTORE: : creating new keystore context...
12-20 11:58:12.901  3509  4434 I TLC_TZ_KEYSTORE: : initializing ccm context...
12-20 11:58:12.901  3509  4434 I TLC_TZ_KEYSTORE: : root = 0, root_strlen = 1
12-20 11:58:12.901  3509  4434 I TLC_TZ_KEYSTORE: : process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:58:12.901  3509  4434 I TZ: mc_tlc_communication: input max_sendmsg_size = 1080
12-20 11:58:12.901  3509  4434 I TZ: mc_tlc_communication: input max_recvmsg_size = 1080
12-20 11:58:12.901  3509  4434 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-20 11:58:12.901  3509  4434 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000013, process_strlen = 32
12-20 11:58:12.901  3509  4434 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 1088
12-20 11:58:12.901  3509  4434 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 1088
,12-20 11:58:12.901  3509  4434 I TZ: mc_tlc_communication: device_id = 0x0
12-20 11:58:12.901  3509  4434 I TZ: mc_tlc_communication: tlc_open() was called
12-20 11:58:12.901  3509  4434 I TZ: mc_tlc_communication: Opening MobiCore device
12-20 11:58:12.901  3509  4434 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-20 11:58:12.901  3509  4434 I TZ: mc_tlc_communication: Opening the session
,12-20 11:58:12.921  3509  4434 I TZ: mc_tlc_communication: tlc_open() succeeded
,12-20 11:58:12.921  3509  4434 I TLC_TZ_KEYSTORE: : ctx = 0x7f811eda40, comm = 0x7f7e72a7f0, sendmsg = 0x7f958fa000, recvmsg = 0x7f958fa440
12-20 11:58:12.921  3509  4434 I TLC_TZ_KEYSTORE: unwrap_key: : TZ_KEYSTORE_fips_unwrap_key_TLC...
12-20 11:58:12.921  3509  4434 I TLC_TZ_KEYSTORE: unwrap_key: : TZ_KEYSTORE_unwrap_key_START...
,12-20 11:58:12.941  3509  4434 I TLC_TZ_KEYSTORE: unwrap_key: : TZ_KEYSTORE_unwrap_key_END...
12-20 11:58:12.941  3509  4434 I TZ: mc_tlc_communication: tlc_close() was called
12-20 11:58:12.941  3509  4434 I TZ: mc_tlc_communication: Closing the session
,12-20 11:58:12.941  3509  4434 I TZ: mc_tlc_communication: Freeing message buffer
12-20 11:58:12.941  3509  4434 I TZ: mc_tlc_communication: Closing MobiCore device
12-20 11:58:12.941  3509  4434 I TZ: mc_tlc_communication: tlc_close() succeeded
12-20 11:58:12.941  3509  4434 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
12-20 11:58:12.941  3509  4434 I         : TimaKeyStore: returning bytearray
12-20 11:58:12.941  3509  4434 D TimaHelper: Found key : PersonaPwdResetToken0 from TIMA keystore
12-20 11:58:12.941  3509  4434 I KeyManagementUtil: retrieveCMK :: Inside
,12-20 11:58:12.941  3509  4434 D KeyManagementUtil: verifyKEK :: Inside
12-20 11:58:12.941  3509  4434 D KeyManagementUtil: SND -> {keymanagement_cmd verify_kek}
12-20 11:58:12.941  3198  3293 D SDP_JNI_SKMM2:  [sdp] CALL - VerifyKEK..... 
12-20 11:58:12.941  3198  3293 D SDP_JNI_SKMM2: verifyKEK ..... 
12-20 11:58:12.941  3198  3293 D SDP_JNI_SKMM2: verifyKEK :: id=0, type=MDM
12-20 11:58:12.941  3198  3293 E SDP_DAEMON_SKMM2: int __read_payload(int, void*, size_t)(size:660)
,12-20 11:58:12.951  3198  3293 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
,12-20 11:58:12.951  3198  3293 D SKMM_v2.0_Mobicore_Helper: Try Trustlet Open Session
,12-20 11:58:12.971  3175  3540 I APM::AudioPolicyManager: stopOutput() output 4, stream 1, session 27
,12-20 11:58:12.971  3198  3293 I SDP_DAEMON_SKMM2: Initialized Successfully(0)
12-20 11:58:12.971  3198  3293 I SDP_DAEMON_SKMM2: security.mdpp(Ready)
12-20 11:58:12.971  3198  3293 I SDP_DAEMON_SKMM2: security.mdpp.mass(skmm)
,12-20 11:58:13.031  3198  3293 D SKMM_v2.0_Mobicore_Helper: Send Trustlet TCI Message
,12-20 11:58:13.041  3198  3293 I TeeDriverClient: driver client closed [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:113]
,12-20 11:58:13.041  3198  3293 D SDP_JNI_SKMM2: verifyKEK ..... End
12-20 11:58:13.041  3509  3859 D KeyManagementUtil: RCV <-
12-20 11:58:13.041  3509  4434 D KeyManagementUtil: RMV <-
12-20 11:58:13.041  3509  4434 D KeyManagementUtil: event called.
,12-20 11:58:13.041  3509  4434 D SdpManagerService: cacheMasterKey :: 0
12-20 11:58:13.041  3509  4434 E SDP.CRYPTO: 
12-20 11:58:13.041  3509  4434 E SDP.CRYPTO: int sdp_drv_on_unlocked(int, const char*, int)(0)
12-20 11:58:13.041  3509  4434 E SDP.CRYPTO: Rpri loaded
12-20 11:58:13.041  3509  4434 E SDP.CRYPTO: Dpri loaded
12-20 11:58:13.041  3509  4434 E SDP.CRYPTO: No hash for ECDH verification.. need to migrate?? 
12-20 11:58:13.041  3509  4434 E SDP.CRYPTO: EDpri loaded
12-20 11:58:13.041  3509  4434 E SDP.CRYPTO: sym loaded
12-20 11:58:13.041  3509  4434 E SDP.CRYPTO:     On User Unlock OK, id 0
12-20 11:58:13.041  3509  4434 E SdpManagerService: sendBroadcastAsUser(INTENT_SDP_STATE_CHANGED, state:2)
,12-20 11:58:13.041  3960  9803 D KeyguardViewMediator: unlockSdp :: Unlock SDP Successful..!
,12-20 11:58:13.051  3509  3593 V BroadcastQueue: [foreground] Process cur broadcast BroadcastRecord{45e1b5c u0 com.sec.sdp.SDP_STATE_CHANGED qIdx=2}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{56c7d71 9501:com.sec.android.app.sbrowser/u0a141}
,12-20 11:58:13.051  3509  4333 E SdpServiceKeeper: isLicensed {pid:9501 uid:10141 userid:0 doPkg:null}
12-20 11:58:13.051  3509  4333 E SdpServiceKeeper: White listed. Skip license activation
,12-20 11:58:13.051  9501  9501 E SdpStateChangedReceiver: com.sec.enterprise.knox.sdp.exception.SdpEngineNotExistsException
,12-20 11:58:13.131  3509  3509 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 728000  uid : 1000  pid : 3509  tag : GESTURE_DETECTED@CPU_MIN@36
,12-20 11:58:13.171  3960  3960 V KeyguardDisplayManager: hide (true)
,12-20 11:58:13.381  3960  3960 V PanelView: touch re-enable
,12-20 11:58:13.481  8617  8673 I ReschedulableTimer: [#CMH#] ReschedulableTimer started 
,12-20 11:58:15.421  3509  4180 E Watchdog: !@Sync 13 [12-20 11:58:15.434]
,12-20 11:58:15.491  4328  4328 D capture : canCapture isWorkspaceLocked() = false isVisible : false
12-20 11:58:15.491  4328  4328 D capture : canCapture mWorkspace.getState()() = NORMAL isTouchActive : false isPageMoving : false
,12-20 11:58:15.891  3175  3651 I audio_hw_primary: do_out_standby +
,12-20 11:58:15.921  3175  3651 D audio_hw_primary: output_devices devices:0
,12-20 11:58:15.921  3175  3651 D audio_hw_primary: output_devices devices:0
12-20 11:58:15.921  3175  3651 V audio_hw_primary: select_devices output_scenario:-1 input_scenario:-1 out_snd_device 0x0 in_snd_device:0x0
12-20 11:58:15.921  3175  3651 I audio_hw_primary: set_spk_rx_mute mute(1), rx val=0
12-20 11:58:15.921  3175  3651 I audio_route: 
12-20 11:58:15.921  3175  3651 I audio_route: > audio_route_reset :
12-20 11:58:15.921  3175  3651 I audio_route: 
12-20 11:58:15.921  3175  3651 I audio_route: > audio_route_update_mixer : +
,12-20 11:58:15.961  3175  3651 I audio_route: > audio_route_update_mixer : changed(2) -
,12-20 11:58:15.961  3175  3651 I audio_hw_primary: select_devices - 
12-20 11:58:15.961  3175  3651 I audio_hw_primary: do_out_standby -
,12-20 11:58:21.011  3509  3530 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-20 11:58:21.011  3509  3530 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4350, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-20 11:58:21.011  3509  3530 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-20 11:58:21.011  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-20 11:58:21.021  3509  3509 I MotionRecognitionService: Plugged
,12-20 11:58:21.021  3509  3509 D MotionRecognitionService:   cableConnection= 1
12-20 11:58:21.021  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-20 11:58:21.021  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,12-20 11:58:21.021  3509  3884 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-20 11:58:21.021  3960  3960 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-20 11:58:21.021  3960  3960 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-20 11:58:21.031  3960  3960 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-20 11:58:21.041  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:58:21.051  5298  5298 D CommonServiceConfiguration: getStringValueSetting
,12-20 11:58:21.051  5257  5257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-20 11:58:21.051  5257  5533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-20 11:58:21.061  3960  3960 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-20 11:58:21.071  5298  5298 D BatteryMonitor: new battery level: 100
,12-20 11:58:21.421  3509  6576 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 260, LCD = 105
,12-20 11:58:21.431  3509  4485 D WifiService: startScan by pid=4607, uid=10021
,12-20 11:58:21.431  3509  3881 I WifiScanController: location is disabled
,12-20 11:58:21.441  3509  3881 D WifiStateMachine: CMD_START_SCAN : scanLog.mLast - 1482231501451, scanLog.mStartTimeForBigdata - 1482231133491
,12-20 11:58:21.441  4152  4152 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
12-20 11:58:21.441  4152  4152 I wpa_supplicant: P2P: Current p2p state = IDLE
,12-20 11:58:21.451  4152  4152 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds

```
