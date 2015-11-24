#### Test 513350282ff9e94_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/HtcModeClient( 1484): handler message = 4011
E/HtcModeClient( 1484): Check connection and retry 12 times. Stop service and kill this process.
D/HtcModeClient( 1484): Don't start project servcice
D/HtcModeClient( 1484): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 1484): connectState: CONNECTION_READY = false
D/SilentMusic( 1484): call stop
D/HtcModeClient( 1484): close connection
W/HtcModeClient( 1484): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 1484): read the terminate packet, so break
D/Process (  909): killProcessQuiet, pid=1484
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
--------- beginning of /dev/log/system
I/ActivityManager(  909): Killing 1484:com.htc.bgp/u0a14 (adj 15): empty #17
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 1484
,E/cutils-trace( 3925): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3925): ====startRecUseTime====
D/htc.customization.log.level( 3925):  is 
W/CustomizationLogLevel( 3925): Level value is invalid, use default level 2
D/CustomizationManager( 3925):  Read ACC file spent 0.059 (s)
D/CIDMapFileReader( 3925): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3925): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3925): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3925): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3925): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3925): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3925): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3925): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3925): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3925): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3925): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3925): Parsing tag category name = system
I/CustomizationCIDLoader( 3925): Parsing tag category name = application
I/CustomizationCIDLoader( 3925): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3925): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3925): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3925): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3925): Parsing tag category name = Settings
D/CustomizationManager( 3925):  Read CID file spent 0.098 (s)
D/CustomizationManager( 3925):  All configurations done spent 0.099 (s)
W/HtcNativeFlag( 3925): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3925): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3925): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3925): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  909): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  909): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3925
D/PMS     (  909): acquireHCC(43cc0800): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 909 1000 null
D/PMS     (  909): acquireHCC(42ea8300): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 909 1000 null
I/Intent  (  909): @test_code: getHtcIntentFlag: 0 obj: 1122169752
I/FeedHostManager( 1247): [onPause]
I/FeedProviderManager( 1247): onPause
I/FeedHostManager( 1247): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@423d4990
I/SocialFeedProvider( 1247): +onPause
I/SocialFeedProvider( 1247): -onPause
D/PMS     (  909): acquireWL(443dfaf8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 909 1000 null
I/ActivityManager(  909): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3936 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1247): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3936): Binding Chromium to main looper Looper (main, tid 1) {422ead88}
I/LibraryLoader( 3936): Expected native library version number "",actual native library version number ""
I/chromium( 3936): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3936): Initializing chromium process, renderers=0
D/PMS     (  909): acquireWL(4394e3a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  909): acquireWL(43cffdb8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  909): java.lang.Throwable: stack dump
D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42dc9c18:true
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3936): 1110446176: getState(). Returning 12
D/PMS     (  909): releaseWL(4394e3a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3936): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3936): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3936): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3936): Local Branch: 
I/Adreno-EGL( 3936): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3936): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3936):                  aa63bbd948f41d15fc72f585e
W/chromium( 3936): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3936): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3936): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3936): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3936): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3936): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3936): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3936): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3936): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3936): CordovaWebView is running on device made by: HTC
,W/AwContents( 3936): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  909): Disable input method client, pid=1247
,W/ResourceType( 3936): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManagerService(  909): Enable input method client, pid=3936
I/InputMethodManager( 3936): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@42332710, mServedView=org.apache.cordova.engine.SystemWebView{422f8378 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1185): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1185): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 3936): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  909): Displayed com.test.thalitest/.MainActivity: +288ms
,D/PMS     (  909): releaseWL(443dfaf8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3936): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3936): JniHelper::setJavaVM(0x41ea9010), pthread_self() = 1662271552
,D/JX-Cordova( 3936): jxcore cordova android initializing
,W/dalvikvm( 3936): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 3936): Grow heap (frag case) to 11.453MB for 98002-byte allocation
,I/dalvikvm-heap( 3936): Grow heap (frag case) to 11.529MB for 146998-byte allocation
,I/dalvikvm-heap( 3936): Grow heap (frag case) to 11.651MB for 220492-byte allocation
,I/dalvikvm-heap( 3936): Grow heap (frag case) to 11.830MB for 330734-byte allocation
,I/dalvikvm-heap( 3936): Grow heap (frag case) to 12.094MB for 496096-byte allocation
,I/dalvikvm-heap( 3936): Grow heap (frag case) to 13.102MB for 1116206-byte allocation
,I/dalvikvm-heap( 3936): Grow heap (frag case) to 14.025MB for 1674304-byte allocation
,I/dalvikvm-heap( 3936): Grow heap (frag case) to 15.400MB for 2511452-byte allocation
,W/CpuWake (  909): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  909): <<release mCpuPerf_Freq wakelock
D/PMS     (  909): releaseHCC(43cc0800): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  909): releaseHCC(42ea8300): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 3936): Grow heap (frag case) to 17.526MB for 3767174-byte allocation
,W/jxcore-log( 3936): Initializing JXcore engine
W/jxcore-log( 3936): JXcore engine is ready
,W/jxcore-log( 3936): Starting JXcore engine
,W/jxcore-log( 3936): Platform android
W/jxcore-log( 3936): 
,W/jxcore-log( 3936): Process ARCH arm
W/jxcore-log( 3936): 
,D/PMS     (  909): releaseWL(43cffdb8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 3936): JXcore Cordova bridge is ready!
I/jxcore-log( 3936): 
,W/jxcore-log( 3936): JXcore engine is started
,I/chromium( 3936): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 3936): Skipped 154 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3936): Toggling radios to true
I/jxcore-log( 3936): 
,D/BluetoothAdapter( 3936): enable(): BT is already enabled..!
,I/SensorManager(  909): mEventCount = 1050
,V/LightsService(  909): setLight #0: color=#3e
,V/LightsService(  909): setLight #0: color=#3a
,V/LightsService(  909): setLight #0: color=#34
,V/LightsService(  909): setLight #0: color=#2d
,V/LightsService(  909): setLight #0: color=#26
,V/LightsService(  909): setLight #0: color=#20
,V/LightsService(  909): setLight #0: color=#19
,V/LightsService(  909): setLight #0: color=#14
,D/BluetoothManagerService(  909): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3936): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): my name is : HTC-HTC Desire 820_PT4477
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): attempting to connect to test coordinator
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): check test folder
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): found test : ./testFindPeers.js
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): found test : ./testReConnect.js
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): found test : ./testSendData.js
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): Test app app.js loaded
I/jxcore-log( 3936): 
,I/Choreographer( 3936): Skipped 147 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/chromium( 3936): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/PMS     (  909): acquireWL(43d06b30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10074}
,V/AlarmManager(  909): sending alarm PendingIntent{42e48558: PendingIntentRecord{42d2c958 com.android.vending startService}}, i=null, t=0, cnt=1, w=1448365584057, Int=0
,I/ActivityManager(  909): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3980 uid=10078 gids={50078}
,V/AlarmManager(  909): sending alarm PendingIntent{42cdc188: PendingIntentRecord{42e05ae0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1448365589401, Int=60000
,D/PMS     (  909): releaseWL(43d06b30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 3980): SMSBackupAgentService started
,D/SMSBackup( 3980): Checking restore status
,D/SMSBackup( 3980): Restore complete
,D/SMSBackup( 3980): cancelCheckAlarm
,D/SMSBackup( 3980): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360022820
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023329
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023437
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023449
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023455
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027344
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/Finsky  ( 3596): [371] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3596): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  909): killProcessQuiet, pid=3679
,I/ActivityManager(  909): Killing 3679:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  909): Recipient 3679
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): BLE advertisement not supported: Build version is 19
I/jxcore-log( 3936): 
,I/PMS     (  909): Going to sleep due to screen timeout...
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42989f80
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Light sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42989f80, eanble = 0, strlen(mName) = 59
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  909): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42ba3fa8
W/SensorService(  909): Listener[1] = com.htc.smartdim.sensor_eye@42e26e68
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  909): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  909): Couldn't get kernel wake lock stats
,V/LightsService(  909): setLight #2: color=#0
D/qdlights(  909): set_light_buttons_func: on=0 brightness=0
V/LightsService(  909): setLight #0: color=#0
,W/PMS     (  909): mWirelessDisplayManager is null
D/WirelessDisplayService(  909): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/SurfaceControl(  909): Excessive delay in blankDisplay() while turning screen off: 320ms
D/PMS     (  909): nativeSetInteractive:false
,D/PMS     (  909): nativeSetInteractive:false done
,D/PMS     (  909): nativeSetAutoSuspend:true
,D/PMS     (  909): nativeSetAutoSuspend:true done
,D/HABCtrl (  909): TPE algorithm. remove timeout.
D/PMS     (  909): OOBE c monitor 11
,I/InputManager(  909): Cancel all due to getting PMS screen off broadcast
,V/KeyguardServiceDelegate(  909): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@44144488)
,D/NfcService( 1232): ScreenObserver: OFF
,D/NfcService( 1232): applyRouting - 0
I/InputMethodManagerService(  909): screenObserver, isScreenOn=false
I/InputMethodManagerService(  909): Disable input method client, pid=3936
D/PMN     (  909): wakingUp
,D/NfcService( 1232): applyRouting -2
W/ResourceType( 3936): No package identifier when getting name for resource number 0x00000064,
,I/InputMethodManager( 3936): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{422f8378 VFEDH.C. .F...... 0,0-720,1134 #64}
,I/IntentController( 1108): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  909): acquireWL(44531078): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
D/PMS     (  909): releaseWL(44531078): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  909): **** SHOWN CALLED ****
I/WindowManager(  909): No lock screen! windowToken=null
D/PMS     (  909): acquireWL(42e1eef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMN     (  909): onScreenOn
D/PMS     (  909): releaseWL(42e1eef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/MtpService( 1874): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1232): applyRouting - 0
,D/MtpService( 1874): [MTP][onReceive]-
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/NfcService( 1232): applyRouting -2
D/PMS     (  909): acquireWL(44899eb0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
,D/AutoSetting( 1295): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  909): releaseWL(44899eb0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,D/AutoSetting( 1295): service - onCreate()
D/WirelessDisplayService(  909): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/TetherSettings( 3387): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3387): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3387): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3387): Cust_ConnectToPC   : spcsc>false
D/        ( 3387): Cust_ConnectToPC   : IPT>true
D/        ( 3387): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3387): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3387): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3387): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3387): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3387): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1295): service - AddressCache: using context: com.htc.Weather
,I/ClockThread( 1108): stop update clock
D/AlarmManager(  909): ACTION_SCREEN_ON
I/AlarmManager(  909): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done recovering
I/AlarmManager(  909): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done EPS screen off alarm recovering
W/ContextImpl( 3387): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_ON
,D/AutoSetting( 1295): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/SmartNS_PSService( 3387): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3387): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3387):  defaultType:0
D/LocationManagerService(  909): request 42a309d0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  909): provider request: passive ProviderRequest[ON interval=0]
,D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  909):    returned false
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  909): updateScreenOn: false
,W/ActivityManager(  909): Disable JIT of com.htc.bgp
,I/ActivityManager(  909): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4001 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  909): acquireWL(44383790): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(44383790): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(44401090): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(44401090): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1712): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1712): onScreenOn: 1448365594812
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1712): onScreenOn: 1448365594812
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42ba3fa8
,W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42ba3fa8, eanble = 0, strlen(mName) = 91
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  909): Listener[0] = com.htc.smartdim.sensor_eye@42e26e68
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  909): goingToSleep
D/PMS     (  909): acquireWL(442dda18): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 909 1000 null
,D/AlarmManager(  909): ACTION_SCREEN_OFF
I/AlarmManager(  909): [AlarmQueuing] screen off now: 
I/AlarmManager(  909): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=19485 mDataStallAlarmIntent=null
I/AlarmManager(  909): [AlarmQueuing] wifi connection: false
D/PMS     (  909): releaseWL(442dda18): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  909):    returned false
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  909): acquireWL(43e25c50): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 909 1000 null
D/PMS     (  909): releaseWL(43e25c50): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/ContactMessageStore( 1216): start background delete task...
,I/CalendarProvider2( 4001): Created com.android.providers.calendar.CalendarAlarmManager@42326d58(com.android.providers.calendar.HtcCalendarProvider@4230f0e0)
D/ContactMessageStore( 1216): size: 0 , 0
,D/ContactMessageStore( 1216): Background delete complete
,D/NetworkPolicy(  909): updateScreenOn: false
D/CalendarProvider2( 4001): wait start:true
,D/CalendarProvider2( 4001): wait end:false
,I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4021 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] getTotalRam: 1873 Mb
D/PMS     (  909): acquireWL(43972e00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43972e00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(42e7da68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4021): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1712): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1712): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1712): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1712): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1712): onScreenOff
D/PMS     (  909): releaseWL(42e7da68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4021): isEpsOn(), nState = 0
,D/PMS     (  909): acquireWL(443bf320): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4021 1000 null
D/AutoSetting( 1295): service - mHandler: cancel location update
D/AutoSetting( 1295): service -           changes count: 0
,D/PMS     (  909): releaseWL(443bf320): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4021): getMobilePolicyEnabled, result = true
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4021): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4021): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4021): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4021): isEpsOn(), nState = 0
D/WifiService(  909): New client listening to asynchronous messages
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42e26e68
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 1
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42e26e68, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Proximity sensor
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 0
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42e26e68, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42e26e68
E/ActivityThread(  909): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42edd760 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42edd760 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  909): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  909): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  909): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  909): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  909): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  909): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  909): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  909): 	at dalvik.system.NativeStart.main(Native Method)
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/CalendarProvider2( 4001): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4001): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 3874): ---------------------------------------------------
,D/ProviderChangeReceiver( 3874): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3874): start to updateAlertNotification!
,W/ContextImpl( 3888): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3874): No fired or scheduled alerts
,D/HtcAlertUtils( 3874): -- cancelReminderNotification --
,D/HtcAlertUtils( 3874): broadcastExistReminder!
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  909): killProcessQuiet, pid=3748
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3748:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3748
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/Process (  909): killProcessQuiet, pid=3461
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3461:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3461
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{444430b0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  909): acquireWL(43c120a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  909): sending alarm PendingIntent{42c79ad0: PendingIntentRecord{42cbd9e8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122193, Int=0
,D/PMS     (  909): releaseWL(43c120a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43ba71a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1335/10029)
,D/PMS     (  909): releaseWL(43ba71a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(422e0c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(422e0c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43cf8058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=132422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43cf8058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1295): service - handleMessage() stop self
,D/AutoSetting( 1295): service - onDestroy() END
,D/Process (  909): killProcessQuiet, pid=3779
,D/AutoSetting( 1295): service - handleMessage() quit looper
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3779:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/ActivityManager(  909): Recipient 3779
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(43c9f718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  909): sending alarm PendingIntent{42d95620: PendingIntentRecord{42c5a330 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137483, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{42ad6f18: PendingIntentRecord{42a7d6f0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140902, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{42ab45a0: PendingIntentRecord{42d6b8d0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=140932, Int=0
,D/GpsLocationProvider(  909): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  909): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  909): acquireWL(42e711a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
,D/PMS     (  909): releaseWL(42e711a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/libc    (  909): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-,err=8
,D/libc    (  909): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  909): [NET] getaddrinfo_proxy-
D/PMS     (  909): releaseWL(43c9f718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(43964768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(43964768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/TelephonyReceiver( 1216): switchBindHtcMsgCursor: null
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(42e6fbd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(42e6fbd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43f18048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=192422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43f18048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(42dc4ab8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  909): sending alarm PendingIntent{42eb0308: PendingIntentRecord{42cbd9e8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=181800, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{42ab45a0: PendingIntentRecord{42d6b8d0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=201119, Int=0
,D/PMS     (  909): acquireWL(4452b5c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(42dc4ab8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  909): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  909): [NET] getaddrinfo-, 1
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1335/10029)
D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    (  909): [NET] getaddrinfo_proxy-
,D/PMS     (  909): releaseWL(4452b5c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(4428f088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(4428f088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(42e701d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(42e701d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43e86538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=252422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43e86538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(42e3d920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42e3d920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,D/PowerUI ( 1108): closing low battery warning: level=100
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(42f0ea68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42f0ea68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43ceb7a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=312422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43ceb7a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3596): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3596): [NET] getaddrinfo-,err=8
D/libc    ( 3596): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3596): [NET] getaddrinfo-, 1
,D/libc    ( 3596): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3596): [NET] getaddrinfo_proxy-
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(43cf9880): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43cf9880): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43bd1380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=372422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43bd1380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(44458358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(44458358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(43955ee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43955ee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43e89e58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=432422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43e89e58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(43cb9090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43cb9090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43a83ed0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=492422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43a83ed0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(4394bb80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(4394bb80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(4314f3d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4314f3d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43f73228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=552422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43f73228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(439c21a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): releaseWL(439c21a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(444262d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(444262d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
,D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  909): acquireWL(438de5f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=612422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(438de5f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/ContactMessageStore( 1216): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1216): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1216): sku_id=99
,D/ContactMessageStore( 1216): start background delete task...
,D/ContactMessageStore( 1216): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1216): size: 0 , 0
,D/ContactMessageStore( 1216): Background delete complete
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/Process (  909): killProcessQuiet, pid=3801
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3801:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3801
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(43d1f9f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
,D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(43d1f9f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3596): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3596): [NET] getaddrinfo-,err=8
,D/libc    ( 3596): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3596): [NET] getaddrinfo-, 1
,D/libc    ( 3596): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3596): [NET] getaddrinfo_proxy-
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(449f9c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(449f9c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(449a66b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=672422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(449a66b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(449086c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(449086c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/PowerUI ( 1108): closing low battery warning: level=100
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4464d4f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=732422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4464d4f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(44543ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(44543ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(44537060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(44537060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(44527340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=792422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(44527340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(44472390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(44472390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(44400ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(44400ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(443d3148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=852422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(443d3148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(443cb258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
,D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/HeadsetPhoneState( 1564): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderNotification, total:1
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
V/NotificationService(  909): batLight: plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
D/PowerUI ( 1108): closing low battery warning: level=97
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/LightsService(  909): setLight #8: color=#c80000
D/qdlights(  909): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/PMS     (  909): releaseWL(443cb258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,97,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/ContextImpl( 4021): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3387): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3387): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3387): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3387): Cust_ConnectToPC   : spcsc>false
,D/        ( 3387): Cust_ConnectToPC   : IPT>true
,D/        ( 3387): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3387): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3387): Index of the first 1 = -1
,I/BatteryController( 1108): status:2 level:97 unsupport:false plugged:true
W/ContextImpl( 3387): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3387): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3387): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3387): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3387): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3387): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/SmartNS_Utility( 3387): [ACC]android_networking:tethering_guard_support=false
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(43f722d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/PMS     (  909): releaseWL(43f722d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/PowerUI ( 1108): closing low battery warning: level=97
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,97,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:2 level:97 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43e25ce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=912422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43e25ce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(43df37e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43df37e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=98
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:2 level:98 unsupport:false plugged:true
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(43c98af8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43c98af8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/PowerUI ( 1108): closing low battery warning: level=98
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:2 level:98 unsupport:false plugged:true
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3596): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3596): [NET] getaddrinfo-,err=8
D/libc    ( 3596): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3596): [NET] getaddrinfo-, 1
,D/libc    ( 3596): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3596): [NET] getaddrinfo_proxy-
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(43785638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43785638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42e44148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=972422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42e44148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(427d8358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,D/ConnectivityService(  909): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  909): sending alarm PendingIntent{4258a940: PendingIntentRecord{42cb7c68 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=783323, Int=0
,D/ConnectivityService(  909): Done.
,D/ConnectivityService(  909): Setting timer for 720seconds
,I/ActivityManager(  909): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4072 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  909): sending alarm PendingIntent{42da78b8: PendingIntentRecord{42db3100 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1448365697963, Int=10800000
,D/Finsky  ( 3596): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  909): sending alarm PendingIntent{42d336c8: PendingIntentRecord{43be3f00 com.android.vending startService}}, i=null, t=0, cnt=1, w=1448366184469, Int=0
V/AlarmManager(  909): sending alarm PendingIntent{42ca49f0: PendingIntentRecord{42c045b0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1448366418292, Int=900000
V/AlarmManager(  909): sending alarm PendingIntent{42d83400: PendingIntentRecord{44401c30 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1448366495114, Int=0
W/ContextImpl( 4021): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  909): getActiveNetworkInfo called by com.android.vending (3596/10074)
,D/PowerUsageService( 4021): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4021): MY_DEBUG = false
,D/SmartSyncUtils( 4021): isEpsOn(), nState = 0
,D/PMS     (  909): releaseWL(427d8358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/PMS     (  909): acquireWL(43aa7fd0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4021 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4021): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4021): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4021): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4021): SettingOnTime = 1448431200000, randomSettingOnTime = 1448427749000
,D/SmartSyncScreenOnOffTimeReceiver( 4021): SettingOffTime = 1448416800000, randomSettingOffTime = 1448423157000
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SmartSyncScreenOnOffTimeReceiver( 4021): bDayMode = false
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.aurora (4072/10049)
D/SmartSyncScreenOnOffTimeReceiver( 4021): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4021): bNightModeTurnOffOnce = false
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  909): releaseWL(43aa7fd0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/libc    ( 3596): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3596): [NET] getaddrinfo-,err=8
D/libc    ( 3596): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3596): [NET] getaddrinfo-, 1
,D/libc    ( 3596): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3596): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3596): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  909): getActiveNetworkInfo called by com.android.vending (3596/10074)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.android.vending (3596/10074)
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/libc    ( 3596): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3596): [NET] getaddrinfo-,err=8
D/libc    ( 3596): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3596): [NET] getaddrinfo-, 1
,D/libc    ( 3596): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3596): [NET] getaddrinfo_proxy-
D/ConnectivityService(  909): getActiveNetworkInfo called by com.android.vending (3596/10074)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.android.vending (3596/10074)
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3596): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3596): [NET] getaddrinfo-,err=8
,D/libc    ( 3596): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3596): [NET] getaddrinfo-, 1
D/libc    ( 3596): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3596): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3596): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  909): getActiveNetworkInfo called by com.android.vending (3596/10074)
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.android.vending (3596/10074)
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3596): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3596): [NET] getaddrinfo-,err=8
D/libc    ( 3596): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3596): [NET] getaddrinfo-, 1
,D/libc    ( 3596): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3596): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3596): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3596): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 3596): [1] DailyHygiene.access$600: Logging device features
D/ConnectivityService(  909): getActiveNetworkInfo called by com.android.vending (3596/10074)
,D/Finsky  ( 3596): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
D/PMS     (  909): acquireWL(4443c270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10074}
V/AlarmManager(  909): sending alarm PendingIntent{4296d980: PendingIntentRecord{42cad6e0 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1448366496128, Int=0
,D/DeviceConnectionService( 1199): client connected with version: 8296000
D/PMS     (  909): acquireWL(43989088): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 3596 10074 null
,D/Finsky  ( 3596): [386] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/PMS     (  909): releaseWL(4443c270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 3596): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
D/ConnectivityService(  909): getActiveNetworkInfo called by com.android.vending (3596/10074)
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3596): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3596): [NET] getaddrinfo-,err=8
D/libc    ( 3596): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3596): [NET] getaddrinfo-, 1
,D/libc    ( 3596): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3596): [NET] getaddrinfo_proxy-
D/PMS     (  909): releaseWL(43989088): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/Process (  909): killProcessQuiet, pid=3819
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3819:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3819
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(43c37698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10074}
,V/AlarmManager(  909): sending alarm PendingIntent{43d1fa20: PendingIntentRecord{42d2c958 com.android.vending startService}}, i=null, t=0, cnt=1, w=1448366510459, Int=0
,D/PMS     (  909): releaseWL(43c37698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 3596): [371] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3596): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(43cadba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43cadba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43bfb2a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1032422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43bfb2a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(4452d988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4452d988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(44548948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1092422, Int=0
I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(44548948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(448380d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/PowerUI ( 1108): closing low battery warning: level=99
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  909): updateBatteryInfo
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  909): releaseWL(448380d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:2 level:99 unsupport:false plugged:true
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(43f97608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43f97608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(442a6898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1152422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(442a6898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(43caa318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43caa318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  909): acquireWL(4393b6e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1212422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4393b6e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3596): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3596): [NET] getaddrinfo-,err=8
,D/libc    ( 3596): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3596): [NET] getaddrinfo-, 1
,D/libc    ( 3596): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 3596): [NET] getaddrinfo_proxy-
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(42faf840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42faf840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(4446f730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1272422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4446f730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(44195b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/HeadsetPhoneState( 1564): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/DotMatrix( 1529): [EventService] reorderNotification, total:0
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/HtcPowerSaver(  909): updateBatteryInfo
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  909): releaseWL(44195b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/ContextImpl( 4021): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3387): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3387): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3387): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3387): Cust_ConnectToPC   : spcsc>false
,D/        ( 3387): Cust_ConnectToPC   : IPT>true
,D/        ( 3387): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3387): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3387): Index of the first 1 = -1
W/ContextImpl( 3387): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3387): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3387): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3387): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3387): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3387): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(4483b918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4483b918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43c4af48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1332422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43c4af48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(43e753b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43e753b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43c8a6f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1392422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43c8a6f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(447abfe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(447abfe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43be0d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1452422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43be0d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(43f13f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(43f13f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(443756b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(443756b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42e95300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1512422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42e95300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3596): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3596): [NET] getaddrinfo-,err=8
D/libc    ( 3596): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3596): [NET] getaddrinfo-, 1
,D/libc    ( 3596): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3596): [NET] getaddrinfo_proxy-
,D/PMS     (  909): acquireWL(44386308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(44386308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(42eaeee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42eaeee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(44477888): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1572422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(44477888): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(43fedfc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43fedfc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(43cbc788): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1632422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43cbc788): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(42e69908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42e69908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(42dedde8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1692422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42dedde8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(439f2560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(439f2560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(440449c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1752422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(440449c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/PMS     (  909): acquireWL(4452c510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(4452c510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(43998890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43998890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1108): closing low battery warning: level=100
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(443871c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1812422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(443871c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/ProcessStatsService(  909): Prepared write state in 35ms
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3596): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3596): [NET] getaddrinfo-,err=8
,D/libc    ( 3596): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3596): [NET] getaddrinfo-, 1
,D/libc    ( 3596): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3596): [NET] getaddrinfo_proxy-
,I/ProcessStatsService(  909): Pruning old procstats: /data/system/procstats/state-2015-11-23-20-21-20.bin
,D/PMS     (  909): acquireWL(4483b150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4483b150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(448373a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,D/ConnectivityService(  909): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  909): sending alarm PendingIntent{4258a940: PendingIntentRecord{42cb7c68 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1727551, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{42782990: PendingIntentRecord{42de9b40 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820414, Int=1800000
,D/PMS     (  909): acquireWL(44830de0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
,V/AlarmManager(  909): sending alarm PendingIntent{4380ff48: PendingIntentRecord{4339ef20 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1849907, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{42cc42c0: PendingIntentRecord{42d9e480 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1861991, Int=0
V/AlarmManager(  909): sending alarm PendingIntent{43eb0440: PendingIntentRecord{441d65d8 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1448366862557, Int=1800000
,V/AlarmManager(  909): sending alarm PendingIntent{42ca49f0: PendingIntentRecord{42c045b0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1448367318292, Int=900000
,D/ConnectivityService(  909): Done.
,D/ConnectivityService(  909): Setting timer for 720seconds
,D/PMS     (  909): releaseWL(44830de0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/LocationManagerService(  909): getAllProviders()=[passive, gps, network]
,D/PMS     (  909): acquireWL(44444fc0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2085 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.checkin.EventLogService$Receiver
,D/PMS     (  909): acquireWL(44427580): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2085 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(44444fc0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2085/10029)
,I/EventLogService( 2085): Aggregate from 1448365062492 (log), 1448365062492 (data)
I/ActivityManager(  909): Resuming delayed broadcast
,W/ContextImpl( 4021): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  909): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/dalvikvm( 1335): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/libc    ( 1335): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1335): [NET] getaddrinfo-,err=8
D/libc    ( 1335): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1335): [NET] getaddrinfo-, 1
,D/libc    ( 1335): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 1335): [NET] getaddrinfo_proxy-
W/SocketClient(  363): write error (Broken pipe)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360022820
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023329
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023437
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023449
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023455
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027344
,I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): releaseWL(448373a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/PMS     (  909): releaseWL(44427580): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/Process (  909): killProcessQuiet, pid=3646
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3646:com.google.android.gm/u0a107 (adj 15): empty for 1800s
,D/Process (  909): killProcessQuiet, pid=3421
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  909): killProcessQuiet, pid=3846
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  909): killProcessQuiet, pid=3439
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  909): killProcessQuiet, pid=3566
I/ActivityManager(  909): Killing 3421:com.htc.mediamanager/u0a34 (adj 15): empty for 1800s
I/ActivityManager(  909): Killing 3846:com.nero.android.htc.sync/u0a8 (adj 15): empty for 1800s
I/ActivityManager(  909): Killing 3439:com.google.android.music:main/u0a154 (adj 15): empty for 1801s
,I/ActivityManager(  909): Killing 3566:com.google.android.apps.plus/u0a160 (adj 15): empty for 1801s
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  909): killProcessQuiet, pid=3766
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3766:com.htc.cs.dm/u0a98 (adj 15): empty for 1801s
,I/ActivityManager(  909): Recipient 3421
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 3439
D/MediaRouterService(  909): Client com.google.android.music (pid 3439): Died!
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 3766
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 3846
D/WifiService(  909): Client connection lost with reason: 4
I/ActivityManager(  909): Recipient 3566
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3646
,D/PMS     (  909): acquireWL(44003ff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(44003ff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,D/PMS     (  909): acquireWL(43c28250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{426546a8: PendingIntentRecord{42c43fb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1872422, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43c28250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,I/jxcore-log( 3936): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3936): 
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4127): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4127): ====startRecUseTime====
D/htc.customization.log.level( 4127):  is 
W/CustomizationLogLevel( 4127): Level value is invalid, use default level 2
D/CustomizationManager( 4127):  Read ACC file spent 0.102 (s)
D/CIDMapFileReader( 4127): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4127): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4127): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4127): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4127): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4127): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4127): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4127): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4127): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4127): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4127): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4127): Parsing tag category name = system
I/CustomizationCIDLoader( 4127): Parsing tag category name = application
I/CustomizationCIDLoader( 4127): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4127): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4127): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4127): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4127): Parsing tag category name = Settings
D/CustomizationManager( 4127):  Read CID file spent 0.151 (s)
D/CustomizationManager( 4127):  All configurations done spent 0.151 (s)
W/HtcNativeFlag( 4127): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4127): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4127): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4127): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  909): deletePackageAsUser: pkg=com.test.thalitest, pid=4127, uid=2000 user=0
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  909): killProcessQuiet, pid=3936
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  909): Killing 3936:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
W/ActivityManager(  909): handleTopAppChanged(): The previous AP is died unexpectedly.
D/Process (  909): killProcessQuiet, pid=3980
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  909): Killing 3980:com.htc.mms.backupagent/u0a78 (adj 15): empty for 1804s
I/ActivityManager(  909):   Force finishing activity ActivityRecord{4447e5f8 u0 com.test.thalitest/.MainActivity t2}
I/ActivityManager(  909): Recipient 3980
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  909): Skipping PackageSetting{429e4ac8 com.example.hello/10396} due to missing metadata
E/JavaBinder(  909): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  909): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1185): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
W/InputMethodManagerService(  909): Got RemoteException sending setActive(false) notification to pid 3936 uid 10389
W/InputDispatcher(  909): channel '42e64bb0 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  909): channel '42e64bb0 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  909): Attempted to unregister already unregistered input channel '42e64bb0 com.test.thalitest.MainActivity (s)'
I/WindowManager(  909): WINDOW DIED Window{42e64bb0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/WindowManager(  909): Failed looking up window
W/WindowManager(  909): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@42da52c8 does not exist
W/WindowManager(  909): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  909): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  909): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  909): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  909): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  909): WIN DEATH: null
D/DotMatrix( 1529): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1529): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1529): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:false
D/AccTypeManager( 1319): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  909): acquireWL(43f97a20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
W/GeofencerStateMachine( 1199): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
D/VoicemailCleanupService( 1262): Cleaning up data for package: com.test.thalitest
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
D/PMS     (  909): releaseWL(43f97a20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
W/AccTypeManager( 1319): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1319): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/[PluginManager]RegisterService( 1295): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1295): handle notify Blinkfeed plugin client changed
I/InputMethodManagerService(  909): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Launcher( 1247): Deferring update until onResume
D/Launcher( 1247): waitUntilResume // bindAppsRemoved
D/Prism.PackageStateRece_( 1247): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
E/ExternalAccountType( 1319): Unsupported attribute readOnly
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/IcingCorporaProvider( 2663): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/ActivityManager(  909): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4144 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
D/PhoneApp( 1216): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  909): acquireWL(42adace8): PARTIAL_WAKE_LOCK  Icing 0x1 2085 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2663): UpdateCorporaTask done [took 185 ms] updated apps [took 184 ms] 
W/PackageManager(  909): Unable to load service info ResolveInfo{42c5a780 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4144): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4144): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4144): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4144): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4144): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4144): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4144): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4144): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4144): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4144): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4144): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4144): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4144): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4144): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4144): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4144): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4144): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4144): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4144): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4144): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4144): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4144): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4144): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4144): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4144): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4144): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4144): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4144): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4144): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4144): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4144): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4144): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4144): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4144): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4144): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4144): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4144): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4144): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4144): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4144): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4144): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4144): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4144): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4144): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4144): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4144): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4144): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4144): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4144): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4144): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4144): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4144): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4144): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4144): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4144): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4144): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4144): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4144): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4144): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4144): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4144): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4144): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4144): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4144): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4144): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4144): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4144): threadid=11: thread exiting with uncaught exception (group=0x41ebae30)
E/ActivityManager(  909): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4144): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4144): Process: com.google.android.apps.docs, PID: 4144
E/AndroidRuntime( 4144): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4144): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4144): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4144): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4144): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4144): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4144): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4144): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4144): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4144): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4144): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4144): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4144): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4144): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4144): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4144): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4144): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4144): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4144): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
E/SQLiteDatabase( 4144): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4144): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4144): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4144): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4144): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4144): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4144): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4144): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4144): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4144): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4144): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4144): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4144): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4144): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4144): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4144): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4144): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4144): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4144): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4144): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4144): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4144): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4144): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4144): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4144): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4144): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4144): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4144): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4144): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4144): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4144): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4144): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4144): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4144): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4144): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4144): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4144): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4144): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4144): Opened ClientFlag.db in read-only mode
D/Process ( 4144): killProcess, pid=4144
D/Process ( 4144): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  909): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4162 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  909): Recipient 4144
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.google.android.apps.docs (pid 4144) has died.
I/TrimMemoryManager( 1247): [trimMemory] 5
D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  909): start
W/ContextImpl( 4162): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  909): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
E/SQLiteDatabase( 4162): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4162): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4162): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4162): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4162): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4162): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4162): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4162): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4162): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4162): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4162): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4162): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4162): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4162): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4162): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4162): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4162): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4162): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4162): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4162): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4162): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4162): threadid=10: thread exiting with uncaught exception (group=0x41ebae30)
E/ActivityManager(  909): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4162): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4162): Process: com.android.keychain, PID: 4162
E/AndroidRuntime( 4162): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4162): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4162): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4162): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4162): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4162): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4162): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4162): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4162): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4162): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4162): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4162): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4162): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4162): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4162): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4162): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4162): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4162): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4162): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4162): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4162): killProcess, pid=4162
D/Process ( 4162): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1448367394742.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  909): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  909): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  909): 	... 4 more
I/ActivityManager(  909): Recipient 4162
I/ActivityManager(  909): Process com.android.keychain (pid 4162) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager(  909): Resuming delayed broadcast
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4177 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/AppTag  ( 4177): getInstance(Context context)
D/AppTag  ( 4177): getInstance(Context context)
D/AppTag  ( 4177): onCreate()
I/ActivityManager(  909): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4191 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/ActivityManager(  909): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 2085): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2085): Clearing selected account for com.test.thalitest
D/PMS     (  909): acquireWL(4430e948): PARTIAL_WAKE_LOCK  AsyncService 0x1 4191 10160 null
D/PMS     (  909): releaseWL(4430e948): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  909): Resuming delayed broadcast
D/ChimeraCfgMgr( 2085): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2085): Module APK com.google.android.play.games already loaded
E/SQLiteDatabase( 4191): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4191): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4191): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4191): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4191): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 4191): 	at del.a(PG:264)
E/SQLiteDatabase( 4191): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4191): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteDatabase( 4191): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4191): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4191): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4191): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4191): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 4191): 	at del.a(PG:264)
E/SQLiteDatabase( 4191): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4191): 	at java.lang.Thread.run(Thread.java:864)
E/EsApplication( 4191): Failed app initialization
E/EsApplication( 4191): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 4191): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 4191): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 4191): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 4191): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 4191): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 4191): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 4191): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 4191): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 4191): 	at del.a(PG:264)
E/EsApplication( 4191): 	at eeq.run(PG:187)
E/EsApplication( 4191): 	at java.lang.Thread.run(Thread.java:864)
D/ChimeraCfgMgr( 2085): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2085): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 2085): Removing dialog suppression flag for package com.test.thalitest
I/ActivityManager(  909): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 2085): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2085): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x65282008
W/dalvikvm( 2085): threadid=32: thread exiting with uncaught exception (group=0x41ebae30)
E/AndroidRuntime( 2085): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2085): Process: com.google.android.gms, PID: 2085
E/AndroidRuntime( 2085): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2085): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2085): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2085): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2085): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2085): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2085): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2085): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2085): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2085): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2085): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2085): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2085): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3143)
E/AndroidRuntime( 2085): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2085): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:978)
E/AndroidRuntime( 2085): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2085): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2085): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2085): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteDatabase( 2085): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2085): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2085): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2085): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2085): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2085): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2085): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2085): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2085): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2085): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2085): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2085): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2085): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2085): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2085): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2085): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2085): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 2085): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2085): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2085): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2085): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2085): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2085): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  909): App crashed! Process: com.google.android.gms
E/SQLiteOpenHelper( 2085): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2085): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2085): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2085): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2085): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2085): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2085): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2085): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2085): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2085): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2085): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2085): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2085): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2085): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2085): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2085): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2085): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2085): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2085): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2085): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2085): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2085): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2085): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2085): killProcess, pid=2085
D/Process ( 2085): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 2085
I/ActivityManager(  909): Process com.google.android.gms (pid 2085) has died.
D/PMS     (  909): handleWLDeath(42adace8): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20999ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20999ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20998ms
I/ActivityManager(  909): Resuming delayed broadcast
D/Process (  909): killProcessQuiet, pid=4001
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 4001:com.htc.bgp/u0a14 (adj 15): empty for 1800s
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20994ms
E/SQLiteLog( 1335): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1335): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x5ca71d50
I/ActivityManager(  909): Recipient 4001
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/dalvikvm( 1335): threadid=1: thread exiting with uncaught exception (group=0x41ebae30)
E/ActivityManager(  909): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1335): FATAL EXCEPTION: main
E/AndroidRuntime( 1335): Process: com.google.process.gapps, PID: 1335
E/AndroidRuntime( 1335): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1335): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1335): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1335): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1335): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1335): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1335): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1335): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1335): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1335): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1335): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1335): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1335): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1335): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1335): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1335): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1335): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1335): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1335): 	at com.google.android.gms.gcm.bq.a(SourceFile:310)
E/AndroidRuntime( 1335): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1335): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1335): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1335): 	... 10 more
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
D/Process ( 1335): killProcess, pid=1335
D/Process ( 1335): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
W/dalvikvm( 3596): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
I/ActivityManager(  909): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4222 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4222): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4222 dbg=false s=true
I/DeviceManagement( 4222): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4222): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4222): WorkflowService: Starting workflow service
I/DeviceManagement( 4222): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@42317d40] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4222): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4222): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4222): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4222): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  909): Recipient 1335
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  909): Client connection lost with reason: 4
I/DeviceManagement( 4222): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4222): SessionStateController: Checking invariants...
I/ActivityManager(  909): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4238 uid=10099 gids={50099, 3003, 5012}
I/ActivityManager(  909): Process com.google.process.gapps (pid 1335) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20866ms
D/Documents( 4238): Loading roots for com.android.providers.downloads.documents
E/SQLiteDatabase( 4238): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4238): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4238): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4238): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4238): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4238): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4238): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4238): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4238): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4238): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4238): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4238): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4238): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4238): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4238): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4238): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4238): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4238): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4238): 	at android.content.Conten,tResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4238): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4238): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4238): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4238): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4238): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4238): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4238): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4238): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4238): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4238): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4238): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4238): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4238): threadid=1: thread exiting with uncaught exception (group=0x41ebae30)
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@4237cd38 +
I/Prism.WidgetManager( 1247): onLoadItems() +
E/AndroidRuntime( 4238): FATAL EXCEPTION: main
E/AndroidRuntime( 4238): Process: com.android.documentsui, PID: 4238
E/AndroidRuntime( 4238): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4238): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4238): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4238): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4238): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4238): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4238): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4238): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4238): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4238): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4238): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4238): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4238): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4238): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4238): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4238): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4238): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4238): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4238): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4238): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4238): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4238): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4238): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4238): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4238): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4238): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4238): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4238): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4238): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4238): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4238): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4238): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4238): 	... 10 more
D/Documents( 4238): Loading roots for com.android.externalstorage.documents
I/ActivityManager(  909): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4251 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
E/ActivityManager(  909): App crashed! Process: com.android.documentsui
W/AtomicFile(  909): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
W/AppWidgetServiceImpl(  909): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1448367395437.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  909): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  909): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  909): 	... 4 more
E/SQLiteDatabase( 4222): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4222): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4222): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4222): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4222): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4222): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4222): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4222): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4222): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4222): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4222): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4222): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4222): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4222): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4222): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4222): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4222): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4222): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4222): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4222): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4222): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4222): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4222): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4222): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4222): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4222): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4222): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4222): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4222): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4222): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4222): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4222): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4222): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4222): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4222): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4222): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4222): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4222): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel
```
