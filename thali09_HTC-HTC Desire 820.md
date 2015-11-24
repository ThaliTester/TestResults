#### Test 513350288bfb88c_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/SensorManager(  908): mEventCount = 1050
,E/cutils-trace( 3917): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3917): ====startRecUseTime====
D/htc.customization.log.level( 3917):  is 
W/CustomizationLogLevel( 3917): Level value is invalid, use default level 2
D/CustomizationManager( 3917):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 3917): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3917): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3917): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3917): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3917): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3917): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3917): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3917): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3917): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3917): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3917): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3917): Parsing tag category name = system
I/CustomizationCIDLoader( 3917): Parsing tag category name = application
I/CustomizationCIDLoader( 3917): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3917): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3917): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3917): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3917): Parsing tag category name = Settings
D/CustomizationManager( 3917):  Read CID file spent 0.088 (s)
D/CustomizationManager( 3917):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 3917): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3917): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3917): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3917): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  908): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  908): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3917
D/PMS     (  908): acquireHCC(42121040): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 908 1000 null
D/PMS     (  908): acquireHCC(438598d0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 908 1000 null
W/asset   (  908): Copying FileAsset 0x6f9a0e78 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  908): @test_code: getHtcIntentFlag: 0 obj: 1111899624
I/FeedHostManager( 1248): [onPause]
I/FeedProviderManager( 1248): onPause
I/FeedHostManager( 1248): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c9e698
I/SocialFeedProvider( 1248): +onPause
I/SocialFeedProvider( 1248): -onPause
D/PMS     (  908): acquireWL(42473e88): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 908 1000 null
I/ActivityManager(  908): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3928 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1248): [trimMemory] 20
W/asset   ( 3928): Copying FileAsset 0x5c7d1938 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3928): Binding Chromium to main looper Looper (main, tid 1) {41b5c840}
I/LibraryLoader( 3928): Expected native library version number "",actual native library version number ""
I/chromium( 3928): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3928): Initializing chromium process, renderers=0
D/PMS     (  908): acquireWL(426a1b28): PARTIAL_WAKE_LOCK  AudioMix 0x1 363 1013 null
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  908): java.lang.Throwable: stack dump
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@420ec600:true
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3928): 1102540768: getState(). Returning 12
D/PMS     (  908): releaseWL(426a1b28): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/PMS     (  908): acquireWL(43878868): PARTIAL_WAKE_LOCK  AudioMix 0x1 363 1013 null
I/Adreno-EGL( 3928): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3928): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3928): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3928): Local Branch: 
I/Adreno-EGL( 3928): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3928): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3928):                  aa63bbd948f41d15fc72f585e
W/chromium( 3928): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3928): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3928): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3928): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3928): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3928): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3928): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3928): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3928): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3928): CordovaWebView is running on device made by: HTC
,W/AwContents( 3928): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  908): Disable input method client, pid=1248
,W/ResourceType( 3928): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3928): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ba8690, mServedView=org.apache.cordova.engine.SystemWebView{41b6e2f8 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  908): Enable input method client, pid=3928
W/XT9_C   ( 1186): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1186): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 3928): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  908): Displayed com.test.thalitest/.MainActivity: +266ms
,D/PMS     (  908): releaseWL(42473e88): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/PMS     (  908): acquireWL(4312e398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10074}
,V/AlarmManager(  908): sending alarm PendingIntent{4250e970: PendingIntentRecord{44146208 com.android.vending startService}}, i=null, t=0, cnt=1, w=1448367970955, Int=0
,I/ActivityManager(  908): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3967 uid=10078 gids={50078}
,V/AlarmManager(  908): sending alarm PendingIntent{4246c020: PendingIntentRecord{426f6160 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1448367974946, Int=60000
,D/PMS     (  908): releaseWL(4312e398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 3967): SMSBackupAgentService started
,D/SMSBackup( 3967): Checking restore status
D/SMSBackup( 3967): Restore complete
,D/SMSBackup( 3967): cancelCheckAlarm
,D/SMSBackup( 3967): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023227
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023384
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023504
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023517
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023520
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027345
,D/JsMessageQueue( 3928): Set native->JS mode to OnlineEventsBridgeMode
,D/Finsky  ( 3586): [371] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3586): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  908): killProcessQuiet, pid=2811
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2811:com.android.defcontainer/u0a19 (adj 15): empty #17
,D/jxcore_app_log( 3928): JniHelper::setJavaVM(0x41638048), pthread_self() = 1662586688
,D/JX-Cordova( 3928): jxcore cordova android initializing
,W/dalvikvm( 3928): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/ActivityManager(  908): Recipient 2811
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 3928): Grow heap (frag case) to 11.454MB for 98002-byte allocation
,I/dalvikvm-heap( 3928): Grow heap (frag case) to 11.541MB for 146998-byte allocation
,I/dalvikvm-heap( 3928): Grow heap (frag case) to 11.639MB for 220492-byte allocation
,I/dalvikvm-heap( 3928): Grow heap (frag case) to 11.796MB for 330734-byte allocation
,I/dalvikvm-heap( 3928): Grow heap (frag case) to 12.075MB for 496096-byte allocation
,I/dalvikvm-heap( 3928): Grow heap (frag case) to 13.095MB for 1116206-byte allocation
,I/dalvikvm-heap( 3928): Grow heap (frag case) to 13.948MB for 1674304-byte allocation
,V/LightsService(  908): setLight #0: color=#3d
,V/LightsService(  908): setLight #0: color=#39
,V/LightsService(  908): setLight #0: color=#33
,I/dalvikvm-heap( 3928): Grow heap (frag case) to 15.398MB for 2511452-byte allocation
,V/LightsService(  908): setLight #0: color=#2c
,V/LightsService(  908): setLight #0: color=#25
,V/LightsService(  908): setLight #0: color=#1f
,V/LightsService(  908): setLight #0: color=#18
,V/LightsService(  908): setLight #0: color=#14
,I/dalvikvm-heap( 3928): Grow heap (frag case) to 17.419MB for 3767174-byte allocation
,W/jxcore-log( 3928): Initializing JXcore engine
,W/jxcore-log( 3928): JXcore engine is ready
,W/jxcore-log( 3928): Starting JXcore engine
,W/jxcore-log( 3928): Platform android
W/jxcore-log( 3928): 
,W/jxcore-log( 3928): Process ARCH arm
W/jxcore-log( 3928): 
W/CpuWake (  908): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>release mCpuPerf_Freq wakelock
W/CpuWake (  908): <<release mCpuPerf_Freq wakelock
D/PMS     (  908): releaseHCC(42121040): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  908): releaseHCC(438598d0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/jxcore-log( 3928): JXcore Cordova bridge is ready!
I/jxcore-log( 3928): 
,W/jxcore-log( 3928): JXcore engine is started
,I/chromium( 3928): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3928): Toggling radios to true
I/jxcore-log( 3928): 
,D/BluetoothAdapter( 3928): enable(): BT is already enabled..!
,D/PMS     (  908): releaseWL(43878868): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3928): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): my name is : HTC-HTC Desire 820_PT7320
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): attempting to connect to test coordinator
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): check test folder
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): found test : ./testFindPeers.js
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): found test : ./testReConnect.js
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): found test : ./testSendData.js
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): Test app app.js loaded
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/Choreographer( 3928): Skipped 144 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3928): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/PMS     (  908): Going to sleep due to screen timeout...
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42259708
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = CM36282 Light sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42259708, eanble = 0, strlen(mName) = 59
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@424513f0
W/SensorService(  908): Listener[1] = com.htc.smartdim.sensor_eye@43876788
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  908): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  908): Couldn't get kernel wake lock stats
V/LightsService(  908): setLight #2: color=#0
D/qdlights(  908): set_light_buttons_func: on=0 brightness=0
V/LightsService(  908): setLight #0: color=#0
,D/WirelessDisplayService(  908): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  908): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  908): mWirelessDisplayManager is null
,D/SurfaceControl(  908): Excessive delay in blankDisplay() while turning screen off: 348ms
D/PMS     (  908): nativeSetInteractive:false
D/NfcService( 1233): ScreenObserver: OFF
,D/NfcService( 1233): applyRouting - 0
D/PMS     (  908): nativeSetInteractive:false done
D/PMS     (  908): nativeSetAutoSuspend:true
D/PMS     (  908): nativeSetAutoSuspend:true done
D/HABCtrl (  908): TPE algorithm. remove timeout.
D/PMS     (  908): OOBE c monitor 11
I/InputManager(  908): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  908): screenObserver, isScreenOn=false
I/InputMethodManagerService(  908): Disable input method client, pid=3928
,W/ResourceType( 3928): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3928): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b6e2f8 VFEDH.C. .F...... 0,0-720,1134 #64}
,I/IntentController( 1110): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1233): applyRouting -2
,V/KeyguardServiceDelegate(  908): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4409fba8)
D/PMS     (  908): acquireWL(43c02278): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1233 1027 null
D/PMS     (  908): releaseWL(43c02278): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  908): wakingUp
,V/KeyguardServiceDelegate(  908): **** SHOWN CALLED ****
,D/WirelessDisplayService(  908): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/WindowManager(  908): No lock screen! windowToken=null
D/PMN     (  908): onScreenOn
,D/AlarmManager(  908): ACTION_SCREEN_ON
,W/ActivityManager(  908): Disable JIT of com.htc.bgp
I/AlarmManager(  908): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done recovering
I/AlarmManager(  908): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  908): [AlarmQueuing] done EPS screen off alarm recovering
,I/ClockThread( 1110): stop update clock
,D/MtpService( 1874): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1233): applyRouting - 0
,D/MtpService( 1874): [MTP][onReceive]-
I/ActivityManager(  908): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=3987 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/PMS     (  908): acquireWL(43b2fe00): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1233 1027 null
,D/NfcService( 1233): applyRouting -2
D/PMS     (  908): releaseWL(43b2fe00): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_ON
,D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  908):    returned false
,V/SRS_Proc(  363): ParamSet string: screen_state=on
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  908): updateScreenOn: false
,I/CalendarProvider2( 3987): Created com.android.providers.calendar.CalendarAlarmManager@41b9cc28(com.android.providers.calendar.HtcCalendarProvider@41b84fb0)
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/CalendarProvider2( 3987): wait start:true
D/PMS     (  908): acquireWL(43b64000): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(43b64000): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(4423d5d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4423d5d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1715): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1715): onScreenOn: 1448367983584
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1715): onScreenOn: 1448367983584
D/CalendarProvider2( 3987): wait end:false
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@424513f0
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@424513f0, eanble = 0, strlen(mName) = 91
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  908): Listener[0] = com.htc.smartdim.sensor_eye@43876788
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  908): goingToSleep
D/PMS     (  908): acquireWL(43b1be60): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 908 1000 null
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4008 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/AlarmManager(  908): ACTION_SCREEN_OFF
I/AlarmManager(  908): [AlarmQueuing] screen off now: 
I/AlarmManager(  908): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=19439 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 0
I/AlarmManager(  908): [AlarmQueuing] wifi connection: false
D/PMS     (  908): releaseWL(43b1be60): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/PMS     (  908): acquireWL(436c8c58): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 908 1000 null
,D/WifiNative-wlan0(  908):    returned false
D/PMS     (  908): releaseWL(436c8c58): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  363): ParamSet string: screen_state=off
,D/NetworkPolicy(  908): updateScreenOn: false
,D/ContactMessageStore( 1216): start background delete task...
D/ContactMessageStore( 1216): size: 0 , 0
,D/ContactMessageStore( 1216): Background delete complete
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,W/ContextImpl( 4008): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/PhoneStatusBar( 1110): removeHeadsNotification.gc: 53
,D/PMS     (  908): acquireWL(437ee818): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4008 1000 null
D/SmartSyncUtils( 4008): isEpsOn(), nState = 0
,D/PMS     (  908): releaseWL(437ee818): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4008): getMobilePolicyEnabled, result = true
D/DotMatrix( 1529): [EventService] getTotalRam: 1873 Mb
,D/AutoSetting( 1293): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  908): acquireWL(43b355a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(43b355a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/TetherSettings( 3378): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3378): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3378): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3378): Cust_ConnectToPC   : spcsc>false
D/        ( 3378): Cust_ConnectToPC   : IPT>true
D/        ( 3378): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3378): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3378): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3378): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3378): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1293): service - onCreate()
,D/PMS     (  908): acquireWL(44096f08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,I/PSReceiver( 3378): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1293): service - AddressCache: using context: com.htc.Weather
W/ContextImpl( 3378): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 3378): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 3378): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3378):  defaultType:0
,D/AutoSetting( 1293): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1715): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1715): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1715): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1715): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1715): onScreenOff
I/ActivityManager(  908): Delay finish: com.android.settings/.PSReceiver
D/PMS     (  908): releaseWL(44096f08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Resuming delayed broadcast
D/LocationManagerService(  908): request 42364150 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  908): provider request: passive ProviderRequest[ON interval=0]
,W/ContextImpl( 4008): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4008): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4008): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4008): isEpsOn(), nState = 0
D/WifiService(  908): New client listening to asynchronous messages
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@43876788
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 1
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@43876788, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 0
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@43876788, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@43876788
E/ActivityThread(  908): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@438783c0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@438783c0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  908): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  908): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  908): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  908): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  908): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  908): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  908): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  908): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  908): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  908): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  908): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  908): 	at dalvik.system.NativeStart.main(Native Method)
,I/CalendarProvider2( 3987): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 3987): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/jxcore-log( 3928): BLE advertisement not supported: Build version is 19
I/jxcore-log( 3928): 
,D/ProviderChangeReceiver( 3869): ---------------------------------------------------
,D/ProviderChangeReceiver( 3869): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3869): start to updateAlertNotification!
,W/ContextImpl( 3883): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3869): No fired or scheduled alerts
,D/HtcAlertUtils( 3869): -- cancelReminderNotification --
,D/HtcAlertUtils( 3869): broadcastExistReminder!
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  908): killProcessQuiet, pid=3736
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3736:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3736
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  908): Client connection lost with reason: 4
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/Process (  908): killProcessQuiet, pid=3454
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3454:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3454
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/AutoSetting( 1293): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1293): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1293): service - requestNLP() NetworkLocationProvider not enabled
,D/PMS     (  908): acquireWL(43bdebd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{43b6bda8: PendingIntentRecord{4264a668 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=121748, Int=0
,D/PMS     (  908): releaseWL(43bdebd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43ea3530): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1343/10029)
,D/PMS     (  908): releaseWL(43ea3530): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{43cd0b90 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43690e68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): releaseWL(43690e68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43deff00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43deff00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/AutoSetting( 1293): service - handleMessage() stop self
,D/AutoSetting( 1293): service - handleMessage() quit looper
,D/AutoSetting( 1293): service - onDestroy() END
,D/Process (  908): killProcessQuiet, pid=3636
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3636:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3636
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(4373bb60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,D/GpsLocationProvider(  908): ALARM_XTRA_TIMEOUT
V/AlarmManager(  908): sending alarm PendingIntent{4234d0e8: PendingIntentRecord{42182ec8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140859, Int=0
D/PMS     (  908): acquireWL(439b9670): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  908): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
V/AlarmManager(  908): sending alarm PendingIntent{423db398: PendingIntentRecord{425211b0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141346, Int=0
D/PMS     (  908): releaseWL(439b9670): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,V/AlarmManager(  908): sending alarm PendingIntent{424c8f68: PendingIntentRecord{424cc990 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=142784, Int=0
D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  356): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  356): [NET] get_iface_protocol fail: 
D/libc    (  356): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  356): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  356): [NET] getaddrinfo-,err=7
,D/libc    (  908): [NET] getaddrinfo_proxy-
D/PMS     (  908): releaseWL(4373bb60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43880de8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=147372, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43880de8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/TelephonyReceiver( 1216): switchBindHtcMsgCursor: null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(427283c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(427283c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(432d6df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{4250a938: PendingIntentRecord{4264a668 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=181539, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{424c8f68: PendingIntentRecord{424cc990 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=202811, Int=0
D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  356): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  356): [NET] get_iface_protocol fail: 
D/libc    (  356): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  356): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  356): [NET] getaddrinfo-,err=7
,D/libc    (  908): [NET] getaddrinfo_proxy-
D/PMS     (  908): acquireWL(436d3d40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(432d6df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1343/10029)
,D/PMS     (  908): releaseWL(436d3d40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43bdb2b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=207373, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43bdb2b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(42504e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42504e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43400d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=267372, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43400d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(4386d200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4386d200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43c7adb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=327373, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43c7adb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3586): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3586): [NET] getaddrinfo-,err=8
D/libc    ( 3586): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3586): [NET] getaddrinfo-, 1
,D/libc    ( 3586): [NET] getaddrinfo_proxy+
D/libc    (  356): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  356): [NET] get_iface_protocol fail: 
D/libc    (  356): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  356): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  356): [NET] getaddrinfo-,err=7
,D/libc    ( 3586): [NET] getaddrinfo_proxy-
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(42d04fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42d04fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42d45fc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): releaseWL(42d45fc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43562448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=387373, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43562448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43b75018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43b75018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(4419e500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=447373, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4419e500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(42d39e40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42d39e40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43515560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=507373, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43515560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(439c5b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(439c5b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43288308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=567372, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43288308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(4365a718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4365a718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/ContactMessageStore( 1216): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1216): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1216): sku_id=99
,D/ContactMessageStore( 1216): start background delete task...
,D/ContactMessageStore( 1216): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1216): size: 0 , 0
,D/ContactMessageStore( 1216): Background delete complete
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43917fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=627373, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43917fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3586): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3586): [NET] getaddrinfo-,err=8
D/libc    ( 3586): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3586): [NET] getaddrinfo-, 1
,D/libc    ( 3586): [NET] getaddrinfo_proxy+
D/libc    (  356): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  356): [NET] get_iface_protocol fail: 
D/libc    (  356): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  356): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  356): [NET] getaddrinfo-,err=7
,D/libc    ( 3586): [NET] getaddrinfo_proxy-
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(425eb310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(425eb310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(42793e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=687372, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42793e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(436ecd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(436ecd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(439be908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=747373, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(439be908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(438e23e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(438e23e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(42a9f608): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=807373, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42a9f608): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43718b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43718b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43805588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=867373, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43805588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(4363b370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4363b370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(42d351e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=927373, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42d351e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3586): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3586): [NET] getaddrinfo-,err=8
,D/libc    ( 3586): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3586): [NET] getaddrinfo-, 1
,D/libc    ( 3586): [NET] getaddrinfo_proxy+
D/libc    (  356): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  356): [NET] get_iface_protocol fail: 
D/libc    (  356): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  356): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  356): [NET] getaddrinfo-,err=7
,D/libc    ( 3586): [NET] getaddrinfo_proxy-
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43c334e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43c334e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(426d20a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=987373, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(426d20a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43893bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,D/SmartSyncUtils( 4008): isEpsOn(), nState = 0
V/AlarmManager(  908): sending alarm PendingIntent{42416750: PendingIntentRecord{43bbcd38 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1448368884020, Int=0
,D/PMS     (  908): releaseWL(43893bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43eb1fc0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4008 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4008): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4008): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4008): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4008): SettingOnTime = 1448431200000, randomSettingOnTime = 1448429469000
,D/SmartSyncScreenOnOffTimeReceiver( 4008): SettingOffTime = 1448416800000, randomSettingOffTime = 1448421495000
,D/SmartSyncScreenOnOffTimeReceiver( 4008): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4008): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4008): bNightModeTurnOffOnce = false
,D/PMS     (  908): releaseWL(43eb1fc0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(42d465d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42d465d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43817cc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1047373, Int=0
I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43817cc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43b6e6d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43b6e6d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(440b55a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(440b55a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(42ad55e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1107373, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42ad55e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(4342aaf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4342aaf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(4426d7d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1167372, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4426d7d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(44265c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(44265c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(441f7030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
,I/BatteryService(  908): n_update end
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PMS     (  908): releaseWL(441f7030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(440a9688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1227372, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(440a9688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3586): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3586): [NET] getaddrinfo-,err=8
D/libc    ( 3586): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3586): [NET] getaddrinfo-, 1
,D/libc    ( 3586): [NET] getaddrinfo_proxy+
D/libc    (  356): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  356): [NET] get_iface_protocol fail: 
D/libc    (  356): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  356): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  356): [NET] getaddrinfo-,err=7
,D/libc    ( 3586): [NET] getaddrinfo_proxy-
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43cbdfe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43cbdfe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43c6b848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): releaseWL(43c6b848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43b28f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  908): sending alarm PendingIntent{41e99f10: PendingIntentRecord{4252fa38 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=781826, Int=0
,D/ConnectivityService(  908): Done.
,D/ConnectivityService(  908): Setting timer for 720seconds
,I/ActivityManager(  908): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4060 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  908): sending alarm PendingIntent{42580e68: PendingIntentRecord{425b5828 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1448368083245, Int=10800000
,V/AlarmManager(  908): sending alarm PendingIntent{4243a9b8: PendingIntentRecord{42388750 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1448368803599, Int=900000
,V/AlarmManager(  908): sending alarm PendingIntent{424be670: PendingIntentRecord{43a09830 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1448369149873, Int=1800000
,W/ContextImpl( 4008): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4008): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4008): MY_DEBUG = false
D/PMS     (  908): acquireWL(439b44f0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2085 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(43b28f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): acquireWL(438d2828): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2085 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(439b44f0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/EventLogService( 2085): Aggregate from 1448367349806 (log), 1448367349806 (data)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.aurora (4060/10049)
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023227
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023384
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023504
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023517
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023520
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027345
,D/PMS     (  908): releaseWL(438d2828): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,I/ActivityManager(  908): Killing 3670:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=3670
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Recipient 3670
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(440a4be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1287373, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(440a4be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(436d8b48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/BatteryService(  908): n_update end
D/PMS     (  908): releaseWL(436d8b48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(439999c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(439999c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(4407c350): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1347372, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4407c350): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(438283e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/PMS     (  908): releaseWL(438283e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(441d8828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1407373, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(441d8828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43718de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43718de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(437ff518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(437ff518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(42ad58a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1467372, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42ad58a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(427bd6a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(427bd6a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(439b72b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1527373, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(439b72b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3586): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3586): [NET] getaddrinfo-,err=8
D/libc    ( 3586): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3586): [NET] getaddrinfo-, 1
,D/libc    ( 3586): [NET] getaddrinfo_proxy+
D/libc    (  356): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  356): [NET] get_iface_protocol fail: 
D/libc    (  356): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  356): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  356): [NET] getaddrinfo-,err=7
,D/libc    ( 3586): [NET] getaddrinfo_proxy-
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43bd2f98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PMS     (  908): releaseWL(43bd2f98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(437be7b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1587373, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(437be7b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(42715730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): releaseWL(42715730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,W/ContextImpl( 4008): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,D/TetherSettings( 3378): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3378): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3378): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3378): Cust_ConnectToPC   : spcsc>false
D/        ( 3378): Cust_ConnectToPC   : IPT>true
,D/        ( 3378): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3378): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3378): Index of the first 1 = 3
W/ContextImpl( 3378): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3378): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3378): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3378): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3378): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3378): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
W/ContextImpl( 3378): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(42cacd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42cacd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(42ae3348): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1647373, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42ae3348): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(437e0330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(437e0330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(44091808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(44091808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(439ad580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1707372, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(439ad580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(42aef068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PMS     (  908): releaseWL(42aef068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(432bfea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(432bfea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(426983e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1767372, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(426983e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(434c2208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
,D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(434c2208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(427508a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PMS     (  908): releaseWL(427508a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(42cb3c08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1827373, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  908): Prepared write state in 42ms
,D/PMS     (  908): releaseWL(42cb3c08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  908): Pruning old procstats: /data/system/procstats/state-2015-11-23-22-46-45.bin
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3586): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3586): [NET] getaddrinfo-,err=8
D/libc    ( 3586): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3586): [NET] getaddrinfo-, 1
,D/libc    ( 3586): [NET] getaddrinfo_proxy+
D/libc    (  356): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  356): [NET] get_iface_protocol fail: 
D/libc    (  356): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  356): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  356): [NET] getaddrinfo-,err=7
,D/libc    ( 3586): [NET] getaddrinfo_proxy-
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(43778a50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PMS     (  908): releaseWL(43778a50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  908): killProcessQuiet, pid=3821
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
D/Process (  908): killProcessQuiet, pid=3799
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/ActivityManager(  908): Killing 3821:com.htc.backup/1000 (adj 15): empty for 1800s
I/ActivityManager(  908): Killing 3799:com.google.android.apps.docs/u0a100 (adj 15): empty for 1800s
,D/Process (  908): killProcessQuiet, pid=3768
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/ActivityManager(  908): Killing 3768:com.google.android.partnersetup/u0a32 (adj 15): empty for 1801s
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/ActivityManager(  908): Recipient 3768
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3799
I/ActivityManager(  908): Recipient 3821
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(4408ad60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4408ad60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,D/PMS     (  908): acquireWL(427534b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f004a0: PendingIntentRecord{41b82588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1887372, Int=0
,D/Process (  908): killProcessQuiet, pid=3556
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/Process (  908): killProcessQuiet, pid=3839
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  908): killProcessQuiet, pid=3786
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 3556:com.google.android.apps.plus/u0a160 (adj 15): empty for 1820s
I/ActivityManager(  908): Killing 3839:com.htc.providers.settings:remote/u0a17 (adj 15): empty for 1821s
,I/ActivityManager(  908): Killing 3786:com.htc.cs.dm/u0a98 (adj 15): empty for 1821s
I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,I/ActivityManager(  908): Recipient 3839
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3786
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): releaseWL(427534b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  908): Recipient 3556
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,I/jxcore-log( 3928): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3928): 
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4097): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4097): ====startRecUseTime====
D/htc.customization.log.level( 4097):  is 
W/CustomizationLogLevel( 4097): Level value is invalid, use default level 2
D/CustomizationManager( 4097):  Read ACC file spent 0.104 (s)
D/CIDMapFileReader( 4097): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4097): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4097): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4097): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4097): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4097): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4097): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4097): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4097): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4097): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4097): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4097): Parsing tag category name = system
I/CustomizationCIDLoader( 4097): Parsing tag category name = application
I/CustomizationCIDLoader( 4097): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4097): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4097): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4097): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4097): Parsing tag category name = Settings
D/CustomizationManager( 4097):  Read CID file spent 0.157 (s)
D/CustomizationManager( 4097):  All configurations done spent 0.158 (s)
W/HtcNativeFlag( 4097): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4097): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4097): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4097): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  908): deletePackageAsUser: pkg=com.test.thalitest, pid=4097, uid=2000 user=0
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  908): killProcessQuiet, pid=3928
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  908): Killing 3928:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
W/ActivityManager(  908): handleTopAppChanged(): The previous AP is died unexpectedly.
D/Process (  908): killProcessQuiet, pid=3586
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  908): Killing 3586:com.android.vending/u0a74 (adj 15): empty for 1810s
I/ActivityManager(  908):   Force finishing activity ActivityRecord{42393d10 u0 com.test.thalitest/.MainActivity t2}
I/ActivityManager(  908): Recipient 3586
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  908): Copying FileAsset 0x6b881870 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  908): Skipping PackageSetting{422afcc8 com.example.hello/10396} due to missing metadata
W/InputDispatcher(  908): channel '4265cdf0 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  908): channel '4265cdf0 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  908): Attempted to unregister already unregistered input channel '4265cdf0 com.test.thalitest.MainActivity (s)'
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  908): WIN DEATH: Window{4265cdf0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/WindowManager(  908): WINDOW DIED Window{4265cdf0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/InputMethodManagerService(  908): Got RemoteException sending setActive(false) notification to pid 3928 uid 10389
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
W/Binder  ( 1186): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1186): java.lang.NullPointerException
W/Binder  ( 1186): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1186): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1186): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1186): 	at dalvik.system.NativeStart.run(Native Method)
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1529): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1529): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1529): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/AccTypeManager( 1319): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1200): Ignoring removeGeofence because network location is disabled.
D/PMS     (  908): acquireWL(421861d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  908): releaseWL(421861d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1278): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1233): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/Launcher( 1248): Deferring update until onResume
D/Launcher( 1248): waitUntilResume // bindAppsRemoved
I/PackageManager(  908):   Scheme: "sms"
I/[PluginManager]RegisterService( 1293): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/[PluginManager]RegisterService( 1293): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1248): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
W/AccTypeManager( 1319): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1319): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/IcingCorporaProvider( 2664): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/ActivityManager(  908): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4115 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
E/ExternalAccountType( 1319): Unsupported attribute readOnly
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
D/PhoneApp( 1216): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  908): acquireWL(42601410): PARTIAL_WAKE_LOCK  Icing 0x1 2085 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(42601410): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(41e3a818): PARTIAL_WAKE_LOCK  Icing 0x1 2085 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2664): UpdateCorporaTask done [took 221 ms] updated apps [took 221 ms] 
W/PackageManager(  908): Unable to load service info ResolveInfo{424d16d8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  908): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  908): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  908): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  908): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  908): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  908): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4115): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4115): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4115): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4115): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4115): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4115): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4115): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4115): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4115): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4115): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4115): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4115): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4115): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4115): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4115): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4115): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4115): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4115): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4115): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4115): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4115): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4115): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4115): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4115): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4115): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4115): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4115): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4115): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4115): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4115): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4115): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4115): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4115): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4115): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4115): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4115): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4115): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4115): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4115): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4115): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4115): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4115): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4115): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4115): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4115): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4115): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4115): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4115): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4115): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4115): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4115): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4115): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4115): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4115): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4115): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4115): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4115): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4115): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4115): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4115): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4115): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4115): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4115): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4115): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4115): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4115): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4115): threadid=11: thread exiting with uncaught exception (group=0x41730e30)
E/AndroidRuntime( 4115): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4115): Process: com.google.android.apps.docs, PID: 4115
E/AndroidRuntime( 4115): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4115): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4115): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4115): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4115): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4115): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4115): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4115): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4115): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4115): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4115): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4115): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4115): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4115): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4115): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  908): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
E/SQLiteDatabase( 4115): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4115): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4115): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4115): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4115): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4115): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4115): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4115): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4115): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4115): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4115): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4115): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4115): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4115): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4115): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4115): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4115): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4115): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4115): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4115): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4115): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4115): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4115): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4115): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4115): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4115): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4115): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4115): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4115): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4115): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4115): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4115): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4115): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4115): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4115): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4115): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4115): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4115): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4115): Opened ClientFlag.db in read-only mode
D/Process ( 4115): killProcess, pid=4115
D/Process ( 4115): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/RemoteDisplayProvider(  908): start
I/ActivityManager(  908): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4133 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/AtomicFile(  908): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  908): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager(  908): Recipient 4115
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.google.android.apps.docs (pid 4115) has died.
I/TrimMemoryManager( 1248): [trimMemory] 5
W/ContextImpl( 4133): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  908): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
E/SQLiteDatabase( 4133): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4133): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4133): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4133): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4133): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4133): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4133): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4133): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4133): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4133): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4133): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4133): threadid=10: thread exiting with uncaught exception (group=0x41730e30)
E/ActivityManager(  908): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4133): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4133): Process: com.android.keychain, PID: 4133
E/AndroidRuntime( 4133): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4133): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4133): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4133): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4133): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4133): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4133): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4133): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4133): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4133): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  908): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4133): killProcess, pid=4133
D/Process ( 4133): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  908): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  908): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1448369786552.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  908): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  908): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  908): 	... 4 more
I/ActivityManager(  908): Recipient 4133
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.android.keychain (pid 4133) has died.
W/ActivityManager(  908): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4147 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/AppTag  ( 4147): getInstance(Context context)
D/AppTag  ( 4147): getInstance(Context context)
D/AppTag  ( 4147): onCreate()
I/ActivityManager(  908): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4161 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
D/PMS     (  908): acquireWL(4260b440): PARTIAL_WAKE_LOCK  AsyncService 0x1 4161 10160 null
I/ActivityManager(  908): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 2085): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2085): Clearing selected account for com.test.thalitest
D/Process (  908): killProcessQuiet, pid=3967
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  908): releaseWL(4260b440): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Killing 3967:com.htc.mms.backupagent/u0a78 (adj 15): empty for 1811s
D/ChimeraCfgMgr( 2085): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2085): Module APK com.google.android.play.games already loaded
E/SQLiteDatabase( 4161): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4161): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4161): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4161): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4161): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 4161): 	at del.a(PG:264)
E/SQLiteDatabase( 4161): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4161): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteDatabase( 4161): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4161): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4161): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4161): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4161): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4161): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 4161): 	at del.a(PG:264)
E/SQLiteDatabase( 4161): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4161): 	at java.lang.Thread.run(Thread.java:864)
D/ChimeraCfgMgr( 2085): Loading module com.google.android.gms.games from APK com.google.android.play.games
I/ActivityManager(  908): Recipient 3967
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/EsApplication( 4161): Failed app initialization
E/EsApplication( 4161): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 4161): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 4161): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 4161): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 4161): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 4161): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 4161): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 4161): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 4161): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 4161): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 4161): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 4161): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 4161): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 4161): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 4161): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 4161): 	at del.a(PG:264)
E/EsApplication( 4161): 	at eeq.run(PG:187)
E/EsApplication( 4161): 	at java.lang.Thread.run(Thread.java:864)
D/ChimeraModuleLdr( 2085): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 2085): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2085): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2085): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6d375798
W/dalvikvm( 2085): threadid=32: thread exiting with uncaught exception (group=0x41730e30)
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
W/SQLiteOpenHelper( 2085): Opened metrics.db in read-only mode
E/SQLiteDatabase( 2085): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
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
E/SQLiteDatabase( 2085): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2085): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2085): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2085): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteDatabase( 2085): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2085): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2085): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2085): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/gH_CompatibleDatabase( 2085): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 2085): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
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
E/SQLiteLog( 2085): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 2085): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 2085): threadid=36: thread exiting with uncaught exception (group=0x41730e30)
E/SQLiteOpenHelper( 2085): Couldn't open phenotype.db for writing (will try read-only):
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
E/SQLiteOpenHelper( 2085): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2085): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2085): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2085): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteOpenHelper( 2085): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2085): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2085): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2085): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 2085): Opened phenotype.db in read-only mode
E/ActivityManager(  908): App crashed! Process: com.google.android.gms
E/AndroidRuntime_2_crash( 2085): crash in the same process: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime_2_crash( 2085): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime_2_crash( 2085): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime_2_crash( 2085): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime_2_crash( 2085): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime_2_crash( 2085): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime_2_crash( 2085): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime_2_crash( 2085): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime_2_crash( 2085): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime_2_crash( 2085): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime_2_crash( 2085): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime_2_crash( 2085): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime_2_crash( 2085): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2085): killProcess, pid=2085
D/Process ( 2085): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 2085
I/ActivityManager(  908): Process com.google.android.gms (pid 2085) has died.
D/PMS     (  908): handleWLDeath(41e3a818): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20997ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20995ms
I/ActivityManager(  908): Resuming delayed broadcast
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20990ms
E/SQLiteLog( 1343): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1343): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x62b7a878
W/dalvikvm( 1343): threadid=1: thread exiting with uncaught exception (group=0x41730e30)
E/AndroidRuntime( 1343): FATAL EXCEPTION: main
E/AndroidRuntime( 1343): Process: com.google.process.gapps, PID: 1343
E/AndroidRuntime( 1343): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1343): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1343): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1343): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1343): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1343): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1343): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1343): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1343): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1343): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/An,droidRuntime( 1343): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1343): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1343): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1343): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1343): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1343): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1343): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1343): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1343): 	at com.google.android.gms.gcm.bq.a(SourceFile:310)
E/AndroidRuntime( 1343): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1343): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1343): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1343): 	... 10 more
E/ActivityManager(  908): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
D/Process ( 1343): killProcess, pid=1343
D/Process ( 1343): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  908): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4193 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
D/HtcAmsUtil(  908): isDyingProcess: deadTime=1914577; createTime=21301
D/HtcAmsUtil(  908): isDyingProcess: dying proc:1343:4
I/ActivityManager(  908): remove PR=com.google.android.gsf/.gservices.GservicesProvider dying
I/ActivityManager(  908): Remove died provider record at: com.google.process.gapps(1343)

```
