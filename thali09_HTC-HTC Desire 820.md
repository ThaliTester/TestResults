#### Test 506502785223c58_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  914): Waited long enough for: ServiceRecord{43866700 u0 com.htc.htclocationservice/.AutoSettingService}
,--------- beginning of /dev/log/main
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  914): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  914): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  914): doBoolean: SignalStrength 97
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  914):    returned true
E/cutils-trace( 4451): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4451): ====startRecUseTime====
D/htc.customization.log.level( 4451):  is 
W/CustomizationLogLevel( 4451): Level value is invalid, use default level 2
D/CustomizationManager( 4451):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 4451): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4451): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4451): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4451): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4451): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4451): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4451): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4451): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4451): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4451): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4451): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4451): Parsing tag category name = system
I/CustomizationCIDLoader( 4451): Parsing tag category name = application
I/CustomizationCIDLoader( 4451): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4451): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4451): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4451): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4451): Parsing tag category name = Settings
D/CustomizationManager( 4451):  Read CID file spent 0.090 (s)
D/CustomizationManager( 4451):  All configurations done spent 0.090 (s)
W/HtcNativeFlag( 4451): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4451): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4451): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4451): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  914): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  914): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  914): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  914): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  914): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  914): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  914): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4451
D/PMS     (  914): acquireHCC(43f894b0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 914 1000 null
D/PMS     (  914): acquireHCC(43f5c288): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 914 1000 null
W/asset   (  914): Copying FileAsset 0x676cb008 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  914): @test_code: getHtcIntentFlag: 0 obj: 1148905720
I/FeedHostManager( 1274): [onPause]
I/FeedProviderManager( 1274): onPause
I/FeedHostManager( 1274): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@4230dff0
I/SocialFeedProvider( 1274): +onPause
I/SocialFeedProvider( 1274): -onPause
D/PMS     (  914): acquireWL(43f31f20): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 914 1000 null
I/ActivityManager(  914): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4462 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1274): [trimMemory] 20
W/asset   ( 4462): Copying FileAsset 0x5c7cc320 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4462): Binding Chromium to main looper Looper (main, tid 1) {421ee968}
I/LibraryLoader( 4462): Expected native library version number "",actual native library version number ""
I/chromium( 4462): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4462): Initializing chromium process, renderers=0
D/PMS     (  914): acquireWL(43f20fb8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  914): acquireWL(43f20c48): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  914): releaseWL(43f20fb8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  914): java.lang.Throwable: stack dump
D/BluetoothManagerService(  914): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@427fd640:true
W/System.err(  914): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  914): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  914): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  914): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  914): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4462): 1109413120: getState(). Returning 12
I/Adreno-EGL( 4462): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4462): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4462): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4462): Local Branch: 
I/Adreno-EGL( 4462): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4462): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4462):                  aa63bbd948f41d15fc72f585e
W/chromium( 4462): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4462): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4462): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4462): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4462): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4462): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4462): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4462): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4462): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4462): CordovaWebView is running on device made by: HTC
,W/AwContents( 4462): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  914): Disable input method client, pid=1274
,W/ResourceType( 4462): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4462): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@422363b0, mServedView=org.apache.cordova.engine.SystemWebView{421fc018 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  914): Enable input method client, pid=4462
W/XT9_C   ( 1213): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1213): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4462): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  914): Displayed com.test.thalitest/.MainActivity: +280ms
D/PMS     (  914): releaseWL(43f31f20): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4462): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4462): JniHelper::setJavaVM(0x41daf010), pthread_self() = 1662881680
,D/JX-Cordova( 4462): jxcore cordova android initializing
,I/PMS     (  914): Going to sleep due to screen timeout...
,I/SensorManager(  914): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42869bd0
W/SensorService(  914): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  914): disable: get sensor name = CM36282 Light sensor
W/SensorService(  914): pid=914, uid=1000
W/SensorService(  914): Active sensors: size = 2
W/SensorService(  914): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  914): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  914): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42869bd0, eanble = 0, strlen(mName) = 59
W/SensorService(  914): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  914): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4261c4a8
W/SensorService(  914): Listener[1] = com.htc.smartdim.sensor_eye@42e12d78
,W/SensorService(  914): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  914): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  914): Couldn't get kernel wake lock stats
V/LightsService(  914): setLight #2: color=#0
D/qdlights(  914): set_light_buttons_func: on=0 brightness=0
V/LightsService(  914): setLight #0: color=#0
,D/WirelessDisplayService(  914): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  914): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  914): mWirelessDisplayManager is null
,W/PluginManager( 4462): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 18ms. Plugin should use CordovaInterface.getThreadPool().
,D/SurfaceControl(  914): Excessive delay in blankDisplay() while turning screen off: 313ms
,D/NfcService( 1260): ScreenObserver: OFF
,V/KeyguardServiceDelegate(  914): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4477cdc0)
,D/NfcService( 1260): applyRouting - 0
I/IntentController( 1119): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1260): applyRouting -2
,V/KeyguardServiceDelegate(  914): **** SHOWN CALLED ****
D/PMS     (  914): nativeSetInteractive:false
D/PMS     (  914): nativeSetInteractive:false done
D/PMS     (  914): nativeSetAutoSuspend:true
D/PMS     (  914): nativeSetAutoSuspend:true done
D/HABCtrl (  914): TPE algorithm. remove timeout.
I/InputMethodManagerService(  914): screenObserver, isScreenOn=false
D/PMS     (  914): OOBE c monitor 11
I/InputMethodManagerService(  914): Disable input method client, pid=4462
I/InputManager(  914): Cancel all due to getting PMS screen off broadcast
D/PMN     (  914): wakingUp
D/PMS     (  914): acquireWL(423ade68): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1260 1027 null
D/PMS     (  914): releaseWL(423ade68): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  914): No lock screen! windowToken=null
D/WirelessDisplayService(  914): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  914): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  914): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/MtpService( 2362): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/WifiDataStallTracker(  914): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  914): startDataStallAlarm: tag=21115 delay=15s
,D/MtpService( 2362): [MTP][onReceive]-
,D/NfcService( 1260): applyRouting - 0
,D/NfcService( 1260): applyRouting -2
D/PMN     (  914): onScreenOn
D/AlarmManager(  914): ACTION_SCREEN_ON
I/AlarmManager(  914): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  914): [AlarmQueuing] done recovering
I/AlarmManager(  914): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  914): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  914): acquireWL(42ab94d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  914): n_update end
D/PMS     (  914): releaseWL(42ab94d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  914): acquireWL(429c4110): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1260 1027 null
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1779980, pollInterval: 10000
,I/dalvikvm-heap( 4462): Grow heap (frag case) to 11.601MB for 144892-byte allocation
D/WirelessDisplayService(  914): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  914): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  914): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
D/PMS     (  914): releaseWL(429c4110): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  914): batLight: Full, plugged
V/LightsService(  914): setLight #8: color=#c8c800
D/qdlights(  914): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  914): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  914): setLight #8: color=#c800
D/qdlights(  914): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  914): [LedInfo] has indicator attribute
D/qdlights(  914): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  914): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  914): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  914): doBoolean: SET_SCREEN_ON 1
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  914): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  914): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  914): doBoolean: SignalStrength 97
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): SET_SCREEN_ON:On
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1180): getPrivFuncNum +	
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  914):    returned true
D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  914): BroadcastReceiver::onReceive-
I/ActivityManager(  914): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4513 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  914):    returned true
,V/SRS_Proc(  372): ParamSet string: screen_state=on
I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  914): << updateStatus
D/WIFI_ICON( 1119): WifiActivity: 0
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  914): batLight: Full, plugged
V/LightsService(  914): setLight #8: color=#c8c800
D/qdlights(  914): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  914): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  914): setLight #8: color=#c800
D/qdlights(  914): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  914): [LedInfo] has indicator attribute
D/qdlights(  914): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  914): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/dalvikvm-heap( 4462): Grow heap (frag case) to 11.720MB for 217334-byte allocation
,I/ClockThread( 1119): stop update clock
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/dalvikvm-heap( 4462): Grow heap (frag case) to 11.893MB for 325996-byte allocation
,D/WirelessDisplayService(  914): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  914): updateScreenOn: false
,W/ContextImpl( 4513): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,I/dalvikvm-heap( 4462): Grow heap (frag case) to 12.167MB for 488990-byte allocation
,D/SmartSyncUtils( 4513): isEpsOn(), nState = 0
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  914): acquireWL(42cea130): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4513 1000 null
D/PMS     (  914): acquireWL(43f7a818): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): releaseWL(43f7a818): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): acquireWL(42d93518): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(42d93518): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(42cea130): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1775): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1775): onScreenOn: 1450312727438
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1775): onScreenOn: 1450312727438
I/SensorManager(  914): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4261c4a8
W/SensorService(  914): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  914): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  914): pid=914, uid=1000
W/SensorService(  914): Active sensors: size = 2
W/SensorService(  914): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  914): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  914): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4261c4a8, eanble = 0, strlen(mName) = 91
W/SensorService(  914): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  914): Listener[0] = com.htc.smartdim.sensor_eye@42e12d78
,W/SensorService(  914): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  914): goingToSleep
D/PMS     (  914): acquireWL(426eb348): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 914 1000 null
,D/SmartSyncUtils( 4513): getMobilePolicyEnabled, result = true
,D/AutoSetting( 1316): receiver - intent: android.intent.action.USER_PRESENT
W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1316): service - onCreate()
D/WifiDataStallTracker(  914): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  914): stopDataStallAlarm: current tag=21115 mDataStallAlarmIntent=PendingIntent{42504028: PendingIntentRecord{42c3da98 android broadcastIntent}}
,D/AutoSetting( 1316): service - AddressCache: using context: com.htc.Weather
D/WifiNative-wlan0(  914): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  914): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): SET_SCREEN_ON:Off
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1180): getPrivFuncNum +	
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1180): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1180): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  914):    returned true
D/AlarmManager(  914): ACTION_SCREEN_OFF
I/AlarmManager(  914): [AlarmQueuing] screen off now: 
I/AlarmManager(  914): [AlarmQueuing] data connection: true
I/AlarmManager(  914): [AlarmQueuing] wifi connection: true
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
,D/PMS     (  914): acquireWL(42e1e380): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 914 1000 null
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/TetherSettings( 3819): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3819): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3819): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3819): Cust_ConnectToPC   : spcsc>false
D/        ( 3819): Cust_ConnectToPC   : IPT>true
D/        ( 3819): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3819): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3819): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3819): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3819): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/LocationManagerService(  914): request 42981980 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  914): provider request: passive ProviderRequest[ON interval=0]
V/SRS_Proc(  372): ParamSet string: screen_state=off
D/AutoSetting( 1316): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/PSReceiver( 3819): onReceive:android.intent.action.USER_PRESENT
I/dalvikvm-heap( 4462): Grow heap (frag case) to 12.574MB for 733480-byte allocation
W/ContextImpl( 3819): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/NetworkPolicy(  914): updateScreenOn: false
I/SmartNS_PSService( 3819): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3819): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3819):  defaultType:0
D/ContactMessageStore( 1243): start background delete task...
D/ContactMessageStore( 1243): size: 0 , 0
D/ContactMessageStore( 1243): Background delete complete
D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  914): releaseWL(42e1e380): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/ContextImpl( 4513): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4513): isEpsOn(), nState = 0
D/SmartSyncUtils( 4513): getMobilePolicyEnabled, result = true
D/SmartSyncUtils( 4513): isEpsOn(), nState = 0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiService(  914): New client listening to asynchronous messages
W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  914): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42e12d78
W/SensorService(  914): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  914): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  914): pid=914, uid=1000
W/SensorService(  914): Active sensors: size = 1
W/SensorService(  914): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  914): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42e12d78, eanble = 0, strlen(mName) = 36
W/SensorService(  914): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  914): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  914): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  914): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  914): pid=914, uid=1000
W/SensorService(  914): Active sensors: size = 0
W/SensorService(  914): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42e12d78, eanble = 0, strlen(mName) = 36
W/SensorService(  914): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  914): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  914): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42e12d78
E/ActivityThread(  914): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42e13388 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  914): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42e13388 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  914): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  914): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  914): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  914): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  914): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  914): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  914): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  914): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  914): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  914): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  914): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  914): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  914): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  914): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  914): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  914): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  914): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  914): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  914): 	at dalvik.system.NativeStart.main(Native Method)
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] getTotalRam: 1873 Mb
D/PMS     (  914): acquireWL(43a50b28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): releaseWL(43a50b28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): acquireWL(42d59580): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1775): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1775): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1775): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1775): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1775): onScreenOff
D/PMS     (  914): releaseWL(42d59580): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4462): Grow heap (frag case) to 14.021MB for 1650320-byte allocation
,I/dalvikvm-heap( 4462): Grow heap (frag case) to 15.436MB for 2475476-byte allocation
,W/ActivityManager(  914): Activity pause timeout for ActivityRecord{42ba5308 u0 com.test.thalitest/.MainActivity t2}
,I/dalvikvm-heap( 4462): Grow heap (frag case) to 17.444MB for 3713210-byte allocation
,W/CpuWake (  914): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  914): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  914): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  914): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  914): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  914): <<release mCpuPerf_Freq wakelock
D/PMS     (  914): releaseHCC(43f894b0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  914): releaseHCC(43f5c288): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4462): Initializing JXcore engine
,W/jxcore-log( 4462): JXcore engine is ready
,W/jxcore-log( 4462): Starting JXcore engine
,W/jxcore-log( 4462): Platform android
W/jxcore-log( 4462): 
,W/jxcore-log( 4462): Process ARCH arm
W/jxcore-log( 4462): 
,I/jxcore-log( 4462): JXcore Cordova bridge is ready!
I/jxcore-log( 4462): 
,W/jxcore-log( 4462): JXcore engine is started
,I/chromium( 4462): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 4462): Skipped 137 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4462): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4462): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{421fc018 VFEDH.C. .F...... 0,0-720,1134 #64}
D/PMS     (  914): releaseWL(426eb348): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/PMS     (  914): releaseWL(43f20c48): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4462): Toggling radios to true
I/jxcore-log( 4462): 
,D/BluetoothAdapter( 4462): enable(): BT is already enabled..!
,D/WifiManager( 4462): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  914): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  914): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  914): Settings:Agentvalue: 2
W/Settings:Agent(  914): >> traceCallingStack()
W/Settings:Agent(  914): Process.myPid(): 914
W/Settings:Agent(  914): Process.myTid(): 1372
W/Settings:Agent(  914): Process.myUid(): 1000
W/Settings:Agent(  914): 
W/Settings:Agent(  914): 
W/System.err(  914): java.lang.Throwable: stack dump
W/System.err(  914): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  914): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  914): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  914): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  914): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  914): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  914): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  914): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  914): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  914): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  914): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  914): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  914): 
W/Settings:Agent(  914): << traceCallingStack(): 1(ms)
,D/WifiManager( 4462): disconnect: Base Package Name=com.test.thalitest, uid=10389
,D/WifiManager( 4462): reconnect: Base Package Name=com.test.thalitest, uid=10389
,D/WifiNative-wlan0(  914): doBoolean: DISCONNECT
,I/jxcore-log( 4462): Radios toggled
I/jxcore-log( 4462): 
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): TDLS: Tear down peers
I/wpa_supplicant( 1180): wpa_driver_nl80211_disconnect(reason_code=3)
,D/BluetoothManagerService(  914): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  914): setWifiEnabled: true pid=4462, uid=10389
E/WifiService(  914): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  914): isSprintWifiRestricted(): false
I/WifiService(  914): isMdmWifiRestricted(): false
D/WifiSettingsStore(  914): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,D/WifiService(  914): New client listening to asynchronous messages
I/jxcore-log( 4462): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4462): 
I/jxcore-log( 4462): Perf Test app loaded loaded
I/jxcore-log( 4462): 
I/jxcore-log( 4462): check test folder
I/jxcore-log( 4462): 
I/jxcore-log( 4462): found test : ./testFindPeers.js
I/jxcore-log( 4462): 
,I/jxcore-log( 4462): found test : ./testSendData.js
I/jxcore-log( 4462): 
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1180): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1180): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1180): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  914): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  914): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  914): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  914): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  914): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  914): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  914): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  914): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  914): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  914): WifiMonitor:getFreqFromEventString() 2412
,D/WifiMonitor(  914): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1180): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12
D/Tethering(  914): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/Tethering(  914): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb77fdbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1180):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1180): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1180): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_,supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1180): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1180): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  914): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0(  914):    returned true
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiPerfLock(  914): release()
D/WifiStateMachine(  914): PerfLock released for exiting ConnectedState
D/WifiMonitor(  914): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  914): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  914): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/Tethering(  914): interfaceLinkStateChanged wlan0, false
D/Tethering(  914): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Power_Mode_Type mode = 0
I/wpa_supplicant( 1180): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
D/Tethering(  914): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  914):    returned true
,D/WifiNative-wlan0(  914): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/ConnectivityService(  914): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  914): acquireWL(43f2b9f0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 914 1000 null
D/WifiP2pService(  914): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  914): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  914):    returned true
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
D/libc    (  914): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  914): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  914): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/DhcpStateMachine(  914): [RunningState] Stop DHCP
D/WifiNative-wlan0(  914): doBoolean: RECONNECT
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): Fast associate: Old scan results
I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  914): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  914):    returned true
D/WifiMonitor(  914): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiStateMachine(  914): Enter handleNetworkDisconnect
D/libc    (  914): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  914): [NET] getaddrinfo-, SUCCESS
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
,D/WifiDataStallTracker(  914): onReceive: action=android.net.wifi.STATE_CHANGE
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  914): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiNative-wlan0(  914): doBoolean: DRIVER POWERMODE 0
D/WifiDataStallTracker(  914): stopDataStallAlarm: current tag=21116 mDataStallAlarmIntent=null
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Power_Mode_Type mode = 0
I/wpa_supplicant( 1180): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  914):    returned true
D/UsbnetStateTracker(  914): isAvailable+-
D/UsbnetStateTracker(  914): reconnect
,D/UsbnetStateTracker(  914): isAvailable+-
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  914): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  914): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  914): Provision feature enable=false
D/ConnectivityService(  914): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  914): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  914): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/ConnectivityService(  914): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
,D/WISPrService( 3819): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3819): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  914): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  914): Exit handleNetworkDisconnect
D/WifiNative-wlan0(  914): doBoolean: SET pno 1
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): CTRL_IFACE SET 'pno'='1'
D/WifiDataStallTracker(  914): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  914): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/MDST    (  914): default: reconnect()
D/MDST    (  914): default: setTeardownRequested(false)
D/MDST    (  914): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  914): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  914): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  914): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  914): New client listening to asynchronous messages
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiStateTracker(  914): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  914): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  914): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  914): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T],
D/WISPrService( 3819): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3819): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 75,
D/wpa_supplicant( 1180): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-51
D/wpa_supplicant( 1180): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+,
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700',
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-51
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 3
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 1
,I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): selected network = 1
D/wpa_supplicant( 1180): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb77ff4e8  current_ssid=0x0
D/wpa_supplicant( 1180): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1180): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1180): TDLS: TDLS is allowed in the target BSS
,I/wpa_supplicant( 1180): check if in concurrent case
I/wpa_supplicant( 1180): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiNative-wlan0(  914):    returned true
D/WifiStateMachine(  914): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  914): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  914): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiStateMachine(  914): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiStateMachine(  914): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  914): doString: LIST_DONGLES
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/wpa_supplicant( 1180): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1180): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1180): wpa_supplicant_associate, 1795
,D/wpa_supplicant( 1180): RSN: PMKSA cache search - network_ctx=0xb77ff4e8 try_opportunistic=0
D/wpa_supplicant( 1180): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1180): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1180): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1180): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1180): nl80211: Set mode ifindex 22 iftype 2 (STATION)
W/ConnectivityService(  914): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 33 Failed to remove route from default table (No such process)'
,D/ConnectivityService(  914): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1180): nl80211: Unsubscribe mgmt frames handle 0xb77fe718 (mode change)
D/wpa_supplicant( 1180): nl80211: Subscribe to mgmt frames with non-AP handle 0xb77fe718
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb77fe718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb77fe718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb77fe718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb77fe718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb77fe718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb77fe718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb77fe718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb77fe718
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb77fe718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb77fe718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1180):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1180):   * freq=2412
D/wpa_supplicant( 1180):   * Auth Type 0
D/wpa_supplicant( 1180):   * WPA Versions 0x2
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1180): nl80211: Connect request send successfully
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  914): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  914): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  914): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-48
I/wpa_supplicant( 1180): tsf=0000000023150321
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-51
I/wpa_supplicant( 1180): tsf=0000000111296423
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=2
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2427
I/wpa_supplicant( 1180): level=-83
I/wpa_supplicant( 1180): tsf=0000000023150335
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
D/WirelessDisplayService(  914): getDiscoveryDongleList
,V/NativeCrypto( 1375): Read error: ssl=0x660455a0: I/O error during system call, Connection timed out
D/WifiStateMachine(  914): == begin of scan result ==
D/WifiStateMachine(  914): == (3) end of scan result ==
W/ConnectivityService(  914): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  914): handleConnectivityChange: resetting
W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  914): resetConnections(wlan0, 3)
D/WifiStateMachine(  914): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 23150321, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,D/WifiStateMachine(  914): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 2412, timestamp: 111296423, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  914): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2427, timestamp: 23150335, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  914): add 3 to mScanResults
D/WifiNotificationController(  914): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/PMS     (  914): acquireWL(4389b0c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
V/NativeCrypto( 1375): SSL shutdown failed: ssl=0x660455a0: I/O error during system call, Broken pipe
D/WirelessDisplayService(  914): getDiscoveryDongleList
I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
D/libc    (  365): [NET] entry_id:3   entry:0xb8317220  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb8317738  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb8316fd8  removed 
D/libc    (  365): [NET] entry_id:5   entry:0xb83172f8  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb8317428  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb8317860  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb83170e8  removed 
D/libc    (  365): [NET] entry_id:8   entry:0xb83175e0  removed 
D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
D/WifiManager( 1229): getScanResults enter 
D/WifiStateMachine(  914): == begin of scan result ==
D/WifiStateMachine(  914): == (3) end of scan result ==
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/ConnectivityService(  914): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  914): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  914): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  914): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  914): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  914): acquireWL(438d61c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 914 1000 null
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/ConnectivityService(  914): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  914): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WirelessDisplayService(  914): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  914): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  914): startScan Pid: 914 Uid 1000
D/WifiNative-wlan0(  914): doBoolean: SET pno 0
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
D/ConnectivityService(  914): getNetworkInfo networkType=1 called by  (914/1000)
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
,D/ConnectivityService(  914): reportInetCondition for net -1, percentage: 0 by  (1375/10029)
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1180): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  914):    returned true
I//system/bin/ip(  365): RTNETLINK answers: No such process
D/WifiNative-wlan0(  914): doBoolean: SCAN
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1180): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1180): Failed to initiate AP scan
I/wpa_supplicant( 1180): Failed to initiate AP scan, Failed_to_scan_counter:1
D/WifiNative-wlan0(  914):    returned true
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:3
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
D/BatSI   (  914): WIFI scan started for: 450a0300 uid:1000
D/PMS     (  914): releaseWL(438d61c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  914): releaseWL(4389b0c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
,I/chromium( 4462): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/ConnectivityService(  914): mActiveDefaultNetwork: -1
D/ConnectivityService(  914): handleInetConditionChange: no active default network - ignore
,D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1180): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1180): nl80211: Connect event
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1180): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1180): Add randomness: count=7 entropy=1
I/wpa_supplicant( 1180): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1180): TDLS: Remove peers on association
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  914): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1180): EAPOL: enable timer tick
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
D/WifiMonitor(  914): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1180): getPrivFuncNum +	
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
D/Tethering(  914): interfaceLinkStateChanged wlan0, false
D/Tethering(  914): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1180): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/WifiMonitor(  914): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  914): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1180): Get randomness: len=32 entropy=2
D/HTCRequest(  914): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  914): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  914): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  914): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  914): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  914): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  914): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  914): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  914): Enter handleAssociatedWithEvent
D/WifiStateMachine(  914): Associated
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  914): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  914): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  914): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  914): Exit handleAssociatedWithEvent
D/WifiStateMachine(  914): BSSID was changed, update WiFi database
D/Tethering(  914): interfaceLinkStateChanged wlan0, true
D/Tethering(  914): interfaceStatusChanged wlan0, true
,D/WifiApDatabaseHandler(  914): updateConnectedAP...
D/Tethering(  914): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  914): updateConnectedAP...
D/WifiStateMachine(  914): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  914): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  914): This record is existed, only update it...
I/wpa_supplicant( 1180): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiStateMachine(  914): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb77fe9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1180):    addr=c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  914): updateConnectedAP...
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1180): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6effb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1180):    broadcast key
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  914): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1180): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1180): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1180): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1180): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1180): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  914): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
,I/wpa_supplicant( 1180): set send_ind_to_ndc = 0
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state SUCCESS
,D/wpa_supplicant( 1180): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1180): EAPOL authentication completed successfully
I/wpa_supplicant( 1180): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 79
D/Tethering(  914): interfaceLinkStateChanged wlan0, true
D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/Tethering(  914): interfaceStatusChanged wlan0, true
D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  914): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/Tethering(  914): [isWifi] getHotspotEnabled: false
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  914): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  914): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  914): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  914): updateConnectedAP...
,D/WifiStateMachine(  914): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  914): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  914): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  914): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  914): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  914): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiApDatabaseHandler(  914): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  914): This record is existed, only update it...
,D/WifiStateMachine(  914): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  914): updateConnectedAP...
D/ConnectivityService(  914): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  914): Provision feature enable=false
D/ConnectivityService(  914): mActiveDefaultNetwork: -1
,D/WISPrService( 3819): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3819): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  914): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  914): updateConnectedAP...
,D/WifiNative-wlan0(  914): doBoolean: SET pno 0
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  914):    returned true
,D/DhcpStateMachine(  914): [StoppedState] Start DHCP
,D/WifiStateMachine(  914): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  914): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  914):    returned true
,D/WifiNative-wlan0(  914): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: DRIVER POWERMODE 1
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiStateMachine(  914): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  914): acquireWL(43ed5190): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 914 1000 null
,D/WifiStateMachine(  914): handlePreDhcpSetup mBluetoothConnectionActive: false
I/wpa_supplicant( 1180): Power_Mode_Type mode = 1
I/wpa_supplicant( 1180): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1180): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  914):    returned null
E/WifiStateMachine(  914): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  914): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  914):    returned null
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:2
D/WifiP2pService(  914): InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42bdcdc0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  914): P2pEnabledState{ when=-4ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42bdcdc0 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  914): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  914): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  914): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  914): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4557 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  914): getNetworkInfo networkType=1 called by  (914/1000)
,D/GpsLocationProvider(  914): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  914): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTING DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  914): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  914): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  914): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  914): bSetPropertyMultiRAB:false
D/Tethering(  914): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/CaptivePortalTracker(  914): DelayedCaptiveCheckState,
I/Tethering(  914): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
D/CaptivePortalTracker(  914): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  914): NoActiveNetworkState
I/Tethering(  914): ipv4Default null
,I/Tethering(  914): No IPv4 upstream interface, giving up.
,D/Tethering(  914): TetherMasterSM: InitialState processMessage what=3
D/PMS     (  914): acquireWL(4385e7d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 914 1000 null
D/PMS     (  914): releaseWL(4385e7d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/htcCheckinService(  914): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  914): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.backuptransport (1607/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (2165/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.docs (4317/10100)
D/ConnectivityService(  914): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.docs (4317/10100)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (2165/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): CONNECTING
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (2165/10029)
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
,D/libc    (  914): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  914): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  914): [MLHD] enter handleMediaLinkEvent DefaultState
,D/wpa_supplicant( 1180): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1180): EAPOL: disable timer tick
,I/MusicStore( 4557): Database version: 95
,W/ContextImpl( 4557): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4557): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4557): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,D/libc    (  914): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  914): [NET] getaddrinfo-, SUCCESS
D/libc    (  914): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  914): [NET] getaddrinfo-, SUCCESS
D/libc    (  914): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  914): [NET] getaddrinfo-, SUCCESS
D/libc    (  914): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  914): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  914): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  914):    returned true
,D/WifiNative-wlan0(  914): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1180): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  914):    returned true
,D/WifiNative-wlan0(  914): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  914):    returned true
D/WifiStateMachine(  914): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  914): releaseWL(43ed5190): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  914): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  914): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  914): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  914): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  914): doBoolean: SignalStrength 97
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  914):    returned true
,D/WifiStateMachine(  914): gateway: /192.168.1.1
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  914): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1180): getPrivFuncNum +	
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1180): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1180): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  914):    returned true
D/WifiStateMachine(  914): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  914): VerifyingLinkState enter
D/WifiStateMachine(  914): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  914): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  914): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  914): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -51, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/WifiDataStallTracker(  914): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  914): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,W/ContextImpl( 4557): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  914): WAN detection
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
V/NetworkPolicy(  914): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiStateTracker(  914): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  914): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  914): Provision feature enable=false
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  914): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  914): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  914): default: teardown()
D/MDST    (  914): default: setTeardownRequested(true)
,D/MDST    (  914): default: setEnableApn apnType =default , enable=false
,W/ContextImpl( 4557): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/libc    (  914): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  914): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3819): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
D/MDST    (  914): default: setTeardownRequested(true)
D/ConnectivityService(  914): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  914): Unexpected mtu value: android.net.wifi.WifiStateTracker@42afa858
D/ConnectivityService(  914): handleConnectivityChange: netType=1 doReset=false resetMask=0
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  914): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  914): syncGetConfiguredNetworks
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4557, uid=10154, userID:0
D/ConnectivityService(  914): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  914): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  914): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  914): handleConnectivityChange: resetting
D/Nat464Xlat(  914): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  914): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  914): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  914): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  914): sendGeneralBroadcastDelayed, restrictEnable=false
,D/WirelessDisplayService(  914): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  914):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  914): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  914): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  914): acquireWL(447c3bc8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 914 1000 null
,D/ConnectivityService(  914): getNetworkInfo networkType=1 called by  (914/1000)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [1][0][0]
,I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/WifiDisplayAdapter(  914): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  914):     Client/Owner: Client
D/WifiDisplayAdapter(  914):     GroupId: 
D/WifiDisplayAdapter(  914):     Passphrase: 
D/WifiDisplayAdapter(  914):     SessionId: 0
D/WifiDisplayAdapter(  914):     IP Address: }
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
,I/MediaRouter( 4557): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/MediaRouterService(  914): Client com.google.android.music (pid 4557): Registered
D/WifiDisplayAdapter(  914): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  914):     Client/Owner: Client
D/WifiDisplayAdapter(  914):     GroupId: 
D/WifiDisplayAdapter(  914):     Passphrase: 
D/WifiDisplayAdapter(  914):     SessionId: 0
D/WifiDisplayAdapter(  914):     IP Address: }
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.music (4557/10154)
,I/NetworkMonitor( 4557): type=WIFI subType= reason=null isConnected=true
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (2362/10021)
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
I/ActivityManager(  914): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4609 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
D/ConnectivityService(  914): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/PMS     (  914): releaseWL(447c3bc8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/MediaRouter( 4557): getSelectedRoute
,I/NetworkMonitor( 4557): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  914): getNetworkInfo networkType=1 called by com.google.android.music (4557/10154)
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4557, uid=10154, userID:0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/PMS     (  914): acquireWL(43102df0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
,D/Process (  914): killProcessQuiet, pid=3853
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  914): releaseWL(43102df0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  914): Killing 3853:com.htc.mediamanager/u0a34 (adj 15): empty #17
,D/ACRA    ( 4609): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4609): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4609): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4609): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4609): Preparing secondary program dexes.
V/DexLibLoader( 4609): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4609): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4609): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4609): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4609): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4609): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4609): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4609): Dex already copied
D/OdexVerifier( 4609): Odex verification is skipped.
,V/DexLibLoader( 4609): Creating class loader
,V/DexLibLoader( 4609): Finished creating class loader
V/DexLibLoader( 4609): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4609): Dex already copied
D/OdexVerifier( 4609): Odex verification is skipped.
,V/DexLibLoader( 4609): Creating class loader
,V/DexLibLoader( 4609): Finished creating class loader
V/DexLibLoader( 4609): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4609): Dex already copied
,D/OdexVerifier( 4609): Odex verification is skipped.
V/DexLibLoader( 4609): Creating class loader
,V/DexLibLoader( 4609): Finished creating class loader,
V/DexLibLoader( 4609): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar,
V/DexLibLoader( 4609): Dex already copied
D/OdexVerifier( 4609): Odex verification is skipped.
,V/DexLibLoader( 4609): Creating class loader
V/DexLibLoader( 4609): Finished creating class loader
,V/DexLibLoader( 4609): Verifying classes from secondary dexes.
,D/DexLibLoader( 4609): DexLibLoader.ensureDexLoaded took 21 ms,
,I/ActivityManager(  914): Recipient 3853
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4609): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4609): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4609): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4609): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4609): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4609): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4609): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/PMS     (  914): releaseWL(43f2b9f0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  914): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  914): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  914): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  914): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.backuptransport (1607/10029)
,D/CaptivePortalTracker(  914): NoActiveNetworkState
I/NetworkMonitor( 4557): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.htc.musicenhancer (3913/10053)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (2165/10029)
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
D/ConnectivityService(  914): getNetworkInfo networkType=1 called by  (914/1000)
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
D/PMS     (  914): acquireWL(447e3c40): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 914 1000 null
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
D/ConnectivityService(  914): getNetworkInfo networkType=1 called by com.google.android.music (4557/10154)
D/ConnectivityService(  914): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
D/CaptivePortalTracker(  914): DelayedCaptiveCheckState
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
V/Tethering(  914): bSetPropertyMultiRAB:false
D/htcCheckinService(  914): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/Tethering(  914): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/htcCheckinService(  914): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
I/ConnectivityHelper( 1274): [onReceive] WIFI(1): CONNECTED
I/Tethering(  914): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  914): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  914): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  914): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  914): Found interface wlan0
D/Tethering(  914): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.docs (4317/10100)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (2165/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/PMS     (  914): acquireWL(4434c600): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (2165/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.docs (4317/10100)
D/GpsLocationProvider(  914): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  914): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  914): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  914): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  914): releaseWL(4434c600): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  914): releaseWL(447e3c40): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4609): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4609): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4609): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4609): Verify
,D/WifiService(  914): New client listening to asynchronous messages
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4609): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4609): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4609): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  914): killProcessQuiet, pid=4047
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  914): Killing 4047:com.google.android.gm/u0a107 (adj 15): empty #17
,D/AutoSetting( 1316): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  914): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4633 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1316): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1316): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  914): getActiveNetworkInfo called by com.htc.sense.hsp (1316/10055)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.htc.sense.hsp (1316/10055)
D/AutoSetting( 1316): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1316): service - onStartCommand() check timezone in 30000
,W/fb4a(:<default>):UserScope( 4609): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4609): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4609): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4633): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4633): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4633): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4633): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  914): Recipient 4047
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  914): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4647 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  914): killProcessQuiet, pid=4250
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  914): Killing 4250:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.setupwizard (4633/10079)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.setupwizard (4633/10079)
I/ActivityManager(  914): Recipient 4250
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  914): Client connection lost with reason: 4
,D/PMS     (  914): acquireWL(42db4540): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2165 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.setupwizard (4633/10079)
,D/PMS     (  914): acquireWL(42d9ffe8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2165 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2165): Checkin interval check for package: unspecified last checkin: 1450312685679 min interval config: 0 actual interval: 47813
D/PMS     (  914): releaseWL(42db4540): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2165): Checking schedule, now: 1450312733499 next: 1450312715647
,I/CheckinService( 2165): active receiver: enabled
I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2165, uid=10029, userID:0
,I/ActivityManager(  914): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4662 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,I/ActivityManager(  914): Killing 4073:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  914): killProcessQuiet, pid=4073
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/CheckinService( 2165): Preparing to send checkin request
,I/EventLogService( 2165): Accumulating logs since 1450312680070
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (2165/10029)
,E/dalvikvm( 4609): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4609): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,I/CheckinRequestBuilder( 2165): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  914): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2165): Failed to find provider info for com.google.android.wearable.settings
,I/dalvikvm-heap( 4609): Grow heap (frag case) to 9.958MB for 84664-byte allocation
E/dalvikvm( 4609): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4609): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4609): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4609): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4609): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4609): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4609): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4662): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4662): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4662): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4662): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/dalvikvm-heap( 4609): Grow heap (frag case) to 9.970MB for 28144-byte allocation
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 4609): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4609): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4609): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
I/ActivityManager(  914): Recipient 4073
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 4609): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4609): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4609): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4609): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4609): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4609): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
W/ContextImpl( 4662): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4609): Grow heap (frag case) to 10.014MB for 39954-byte allocation
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  914): getNetworkInfo networkType=9 called by com.google.android.gms (2165/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (2165/10029)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [2][0][0]
,V/GLSActivity( 1375): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1375): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm-heap( 4609): Grow heap (frag case) to 10.090MB for 79892-byte allocation
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.magazines (4662/10151)
,V/WebViewChromiumFactoryProvider( 4662): Binding Chromium to main looper Looper (main, tid 1) {421f51b8}
,I/LibraryLoader( 4662): Expected native library version number "",actual native library version number ""
I/chromium( 4662): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4662): Initializing chromium process, renderers=0
,D/PMS     (  914): acquireWL(432b7b40): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  914): acquireWL(4386ff30): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  914): releaseWL(4386ff30): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,E/AudioManagerAndroid( 4662): BLUETOOTH permission is missing!
I/ActivityManager(  914): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4684 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/Adreno-EGL( 4662): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4662): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4662): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4662): Local Branch: 
I/Adreno-EGL( 4662): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4662): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4662):                  aa63bbd948f41d15fc72f585e
,W/dalvikvm( 4684): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4684): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4684): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4684): install
,I/MultiDex( 4684): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/NSApplication( 4662): Starting up...
,I/MultiDex( 4684): loading existing secondary dex files
,I/MultiDex( 4684): load found 3 secondary dex files
,I/MultiDex( 4684): install done
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.magazines (4662/10151)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.magazines (4662/10151)
D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4609): Grow heap (frag case) to 10.276MB for 75760-byte allocation
,D/Process (  914): killProcessQuiet, pid=4285
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.plus (4123/10160)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.plus (4123/10160)
,I/ActivityManager(  914): Killing 4285:com.google.android.partnersetup/u0a32 (adj 15): empty #17
W/dalvikvm( 4684): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 4684): VFY: unable to resolve instance field 36
,W/dalvikvm( 4684): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,V/JNIHelp ( 4684): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  914): Recipient 4285
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (2165/10029)
W/BroadcastQueue(  914): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43941ed0 u0 ReceiverList{4383c278 4609 com.facebook.katana/10027/u0 remote:448c98b8}}
W/BroadcastQueue(  914): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43941ed0 u0 ReceiverList{4383c278 4609 com.facebook.katana/10027/u0 remote:448c98b8}}
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (2165/10029)
W/BroadcastQueue(  914): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{437ebd20 u0 ReceiverList{437c8808 4609 com.facebook.katana/10027/u0 remote:4434a238}}
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (2165/10029)
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  914): getActiveNetworkInfo called by  (2362/10021)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  914): acquireWL(432b98c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(432b98c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1316): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4633): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4633): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ProviderInstaller( 4684): Installed default security provider GmsCore_OpenSSL
D/ConnectivityService(  914): getActiveNetworkInfo called by com.htc.sense.hsp (1316/10055)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.magazines (4662/10151)
D/AutoSetting( 1316): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1316): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1316): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1316): service - onStartCommand() check timezone in 30000
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.htc.sense.hsp (1316/10055)
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.plus (4123/10160)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.plus (4123/10160)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4684): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4684): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2165, uid=10029, userID:0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4123): Grow heap (frag case) to 13.501MB for 1821008-byte allocation
W/dalvikvm( 4684): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4684): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4684): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4684): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4684): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (2165/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (2165/10029)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4609): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4609): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4609): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (2165/10029)
,I/WVCdm   (  372): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  372): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
,D/WearableService( 1229): callingUid 10029, callindPid: 1229
,D/LocationInitializer( 2165): Restart initialization of location
,D/AuthorizationBluetoothService( 1375): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1375): Proximity feature is not enabled.
,E/MDM     ( 1229): [118] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/NativeLibraryUtils( 4684): Install completed successfully. count=14 extracted=0
,V/GLSActivity( 1375): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1229): No location to return for getLastLocation()
,W/FusedLocationProvider( 1229): location=null
D/PMS     (  914): acquireWL(439d9280): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): releaseWL(439d9280): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
,D/WVCdm   (  372): PrepareKeyRequest: nonce=1101058921
,I/WVCdm   (  372): CdmEngine::CloseSession
,W/Settings( 4684): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (4684/10029)
,I/Adreno-EGL( 4684): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4684): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4684): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4684): Local Branch: 
I/Adreno-EGL( 4684): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4684): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4684):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4684): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4684): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4684): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4684): Local Branch: 
I/Adreno-EGL( 4684): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4684): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4684):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4684): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4684): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4684): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4684): Local Branch: 
I/Adreno-EGL( 4684): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4684): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4684):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
D/libc    (  914): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  914): [NET] getaddrinfo-,err=8
D/libc    (  914): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  914): [NET] getaddrinfo-, 1
,D/libc    (  914): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =7e7c +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/WVCdm   (  372): PrepareKeyRequest: nonce=485717022
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  914): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  914): Find DNS Address www.htc.com/23.59.123.86
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/CheckinRequestBuilder( 2165): Classify the device as Phone.
,D/libc    ( 2165): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2165): [NET] getaddrinfo-,err=8
,D/libc    ( 2165): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2165): [NET] getaddrinfo-, 1
,D/libc    ( 2165): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =2575 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 214
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2165): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2165): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2165): [NET] getaddrinfo-,err=8
,D/libc    ( 2165): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2165): [NET] getaddrinfo-,err=8
,D/libc    ( 2165): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2165): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2165): Sending checkin request (12458 bytes)
,I/jxcore-log( 4462): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4462): 
,I/CheckinRequestBuilder( 2165): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  914): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2165): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  914): getNetworkInfo networkType=9 called by com.google.android.gms (2165/10029)
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=15 [19][3][0]
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (2165/10029)
,I/CheckinRequestBuilder( 2165): Classify the device as Phone.
,I/CheckinTask( 2165): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2165): Checking schedule, now: 1450312736027 next: 1450835673019
,I/CheckinService( 2165): active receiver: disabled
I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2165, uid=10029, userID:0
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
,D/CheckinService( 2165): Recording last checkin time for package unspecified as 1450312736363
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
,D/PMS     (  914): releaseWL(42d9ffe8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,W/fb4a(:<default>):UserScope( 4609): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/PMS     (  914): releaseWL(432b7b40): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/fb4a(:<default>):UserScope( 4609): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (2165/10029)
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  914): acquireWL(447ce800): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1375): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1375): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1375): [NET] getaddrinfo-,err=8
D/libc    ( 1375): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1375): [NET] getaddrinfo-, 1
,D/libc    ( 1375): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =418 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
D/PMS     (  914): acquireWL(4398e178): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4557 10154 null
,W/ContextImpl( 4557): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4557, uid=10154, userID:0
,I/MusicLeanback( 4557): Conditions not met for autocaching.
,I/MusicLeanback( 4557): Stop autocaching.
,D/PMS     (  914): releaseWL(4398e178): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 209
D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
W/ContextImpl( 4557): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1375): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1375): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1375): [NET] getaddrinfo-,err=8
,D/libc    ( 1375): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1375): [NET] getaddrinfo-,err=8
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4609): Called registerBroadcastReceiver twice.
,D/PMS     (  914): acquireWL(43d9b1f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1769970, pollInterval: 10000
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
D/PMS     (  914): releaseWL(447ce800): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  914): reportInetCondition for net 1, percentage: 100 by  (1375/10029)
D/ConnectivityService(  914): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  914): handleInetConditionChange: starting a change hold
D/PMS     (  914): releaseWL(43d9b1f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): acquireWL(442eb1c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  914): reportInetCondition for net 1, percentage: 100 by  (1375/10029)
D/ConnectivityService(  914): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  914): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  914): reportInetCondition for net 1, percentage: 100 by  (1375/10029)
D/ConnectivityService(  914): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  914): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
D/PMS     (  914): releaseWL(442eb1c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4609/10027)
,D/AutoSetting( 1316): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1316): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1316): service - requestNLP() NetworkLocationProvider not enabled
,D/WifiStateMachine(  914): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  914): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  914): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  914): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ConnectivityService(  914): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  914): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  914): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,I/GAV2    ( 4662): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  914): acquireWL(441ed1e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=120783, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(441ed1e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1525): service - handleMessage() stop self
,D/AutoSetting( 1525): service - handleMessage() quit looper
,D/AutoSetting( 1525): service - onDestroy() END
,D/Process (  914): killProcessQuiet, pid=4317
,I/ActivityManager(  914): Killing 4317:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  914): killProcessQuiet, pid=4337
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  914): Killing 4337:com.htc.backup/1000 (adj 15): empty #17
I/ActivityManager(  914): Recipient 4317
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  914): Recipient 4337
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  914): Waited long enough for: ServiceRecord{433046f8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/CaptivePortalTracker(  914): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  914): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  914): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  914):   Scheme: "sms"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/ActivityManager(  914): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4756 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1274): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  914):   Scheme: "smsto"
,I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/Launcher( 1274): Deferring update until onResume
D/Launcher( 1274): waitUntilResume // bindAppsUpdated
,I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  914):   Scheme: "mms"
,I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  914):   Scheme: "mmsto"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  914):   Scheme: "sms"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  914):   Scheme: "smsto"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,E/ExternalAccountType( 1341): Unsupported attribute readOnly
,I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  914):   Scheme: "mms"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  914):   Scheme: "mmsto"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,W/SystemReader( 1260): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/Babel   ( 4756): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4756): MmsConfig.loadMmsSettings
,W/dalvikvm( 4756): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4756): VFY: unable to resolve instance field 36
,W/dalvikvm( 4756): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4756): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  914): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4781 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4756, uid=10111, userID:0
,W/Settings( 4756): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 4781): onCreate
I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4756, uid=10111, userID:0
,W/PackageManager(  914): Unable to load service info ResolveInfo{43f045b8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  914): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  914): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  914): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  914): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  914): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  914): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  914): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  914): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  914): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  914): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  914): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  914): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  914): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  914): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  914): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  914): 	at dalvik.system.NativeStart.main(Native Method)
,V/GetPrviateResource( 4781): GetPrviateResource
,V/GetPrviateResource( 4781): GetPrviateResource
I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4756, uid=10111, userID:0
I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4756, uid=10111, userID:0
I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4756, uid=10111, userID:0
I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4756, uid=10111, userID:0
,D/MmsCustomizationProvider( 4781): query uri: content://htc-mms-customization/mms-ua/ua_string
D/PMS     (  914): acquireWL(43f20698): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4756 10111 null
,D/MmsCustomizationProvider( 4781): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/[PluginManager]RegisterService( 1316): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1316): handle notify Blinkfeed plugin client changed
,I/ProviderInstaller( 4756): Installed default security provider GmsCore_OpenSSL
,I/IcingCorporaProvider( 2869): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Babel   ( 4756): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4756): MmsConfig.loadFromDatabase
,E/Babel   ( 4756): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4756): MmsConfig.loadFromResources
I/ActivityManager(  914): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,E/Babel   ( 4756): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4756): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
D/PMS     (  914): acquireWL(42db00b0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4123 10160 null
D/PMS     (  914): acquireWL(42ced680): PARTIAL_WAKE_LOCK  Icing 0x1 2165 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(43f20698): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/dalvikvm-heap( 4123): Grow heap (frag case) to 15.200MB for 1821008-byte allocation
D/PMS     (  914): releaseWL(42db00b0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  914): Resuming delayed broadcast
D/MessageCustFlag( 4781): sense_version=6.0
D/BTAccessoryUtil( 4781): createReceiver
D/BTAccessoryUtil( 4781): registerReceiver return intent = null
D/MessageCustFlag( 4781): sku_id=99
W/SystemReader( 4781): Cannot find message_ambs_application_id, use default value instead
,I/dalvikvm-heap( 4123): Grow heap (frag case) to 16.937MB for 1821008-byte allocation
D/Messaging( 4781): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4781): networkCode: 
,D/MessageCustFlag( 4781): sku_id=99
D/MmsConfig( 4781): SIE smsPri: null
,D/MmsConfig( 4781): networkCode: 
D/HtcTelephonyCapability( 4781): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4781): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4781): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4781): Cannot find qct_8960_interface, use default value instead
,D/Process (  914): killProcessQuiet, pid=4360
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  914): Killing 4360:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/PackageBroadcastService( 2165): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  914): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  914): Recipient 4360
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PackageBroadcastService( 2165): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2165): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  914): Resuming delayed broadcast
,D/Process (  914): killProcessQuiet, pid=3913
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  914): Killing 3913:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  914): Recipient 3913
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/RemoteDisplayProvider(  914): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  914): start
,I/GCoreNlp( 1229): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  914): applying state to connected service
D/PMS     (  914): acquireWL(43293798): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): releaseWL(43293798): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  914): applying state to connected service
D/PMS     (  914): acquireWL(4385fc60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): releaseWL(4385fc60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): acquireWL(4383c2f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): releaseWL(4383c2f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): acquireWL(43f25198): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): releaseWL(43f25198): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2869): UpdateCorporaTask done [took 429 ms] updated apps [took 429 ms] 
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@42283bd0 +
,I/Prism.WidgetManager( 1274): onLoadItems() +
,I/Icing   ( 2165): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2165): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  914): releaseWL(42ced680): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1274): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1274): onLoadItems() -
,I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@42283bd0 -
,D/PhoneApp( 1243): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1243): -- N1 =0
,D/PhoneApp( 1243): -- N2 =0
,D/PhoneApp( 1243): -- N3 =0
,D/Messaging( 4781): mNeedToUpdateDate2 start
,D/MmsConfig( 4781): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4781): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4781): 
D/MmsAsyncWorkHandler( 4781): HM tk = 20001
D/ReportIndicatorCache( 4781): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4781): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@422012a0
,I/Messaging( 4781): mccmnc> 
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/DraftCache( 4781): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4781): [DraftCache/1] refresh
,D/MmsSmsV2Provider( 1243):  phoneType = -1
D/MmsConfig( 4781): networkCode: 
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4781): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/PhoneStorageUtil( 4781): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4781): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4781): createReceiver
,D/Messaging( 4781): mNeedToUpdateDate2: false
,D/MessageCustFlag( 4781): sense_version=6.0
,D/Jerry   ( 4781): start to preload cursor >>>>>>>
,D/TelephUtils( 1243): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
V/MmsProvider( 1243): Update uri=content://mms, match=0
,V/MmsProvider( 1243): selection=st=129 AND m_type!=134
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1243):  phoneType = -1
D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/Messaging( 4781): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4781): TransactionService is going to be woken up.
,V/TransactionService( 4781): 1-Creating TransactionService
V/TransactionService( 4781): onStartCommand: 1
,D/MmsSystemEventReceiver( 4781): unRegisterForConnectionStateChanges
V/TransactionService( 4781): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4781): Loading previous transactions.
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1243): sku_id=99
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/AccFlag ( 1243): device_type: 1
,D/DraftCache( 4781): [DraftCache/475] rebuildCache
D/TransactionService( 4781): Force set service start id to 1
,V/TransactionService( 4781): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4781): unRegisterForConnectionStateChanges
D/TransactionService( 4781): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4781): Destroying TransactionService
D/Messaging( 4781): ViewCache CreatePreload
,D/Messaging( 4781): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 4781): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Cust_MMSMS( 4781): _has_set_default_values_2=true
,D/Messaging( 4781): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/Jerry   ( 1243): URI_DRAFT
,D/DraftCache( 4781): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4781): [DraftCache/475] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4781): 
D/MmsAsyncWorkHandler( 4781): HM tk = 20002
,D/MsgPreferenceUtils( 4781): def_index: 0
,D/MsgPreferenceUtils( 4781): globalIndex = 1
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1243): sku_id=99
,D/MsgPreferenceUtils( 4781): phone state: true
,D/MsgPreferenceUtils( 4781): sd state: false
,D/MsgPreferenceUtils( 4781): vIndex = 0
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1243): sku_id=99
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1759963, pollInterval: 10000
,I/GAV4    ( 4756): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  914): acquireWL(4386b700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  914): releaseWL(4386b700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  914): updateBatteryInfo
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1749960, pollInterval: 10000
,D/PMS     (  914): acquireWL(430b87a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  914): sending alarm PendingIntent{43d8c0c0: PendingIntentRecord{42df27a0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=130787, Int=0
,V/AlarmManager(  914): sending alarm PendingIntent{4389ff68: PendingIntentRecord{431da1b0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=138345, Int=0
,D/PMS     (  914): acquireWL(447ad458): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=8 [12][1][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  914): acquireWL(440e99c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(447ad458): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(440e99c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
,D/PMS     (  914): releaseWL(430b87a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(43a5ce28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
,D/PMS     (  914): releaseWL(43a5ce28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(440417c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
,D/PMS     (  914): acquireWL(43dd4cf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(43f39898): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1229): Vacuum at: now=1450312757811 tag=VacuumService
,D/PMS     (  914): releaseWL(440417c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(43f39898): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(43dd4cf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(43fe53a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
,D/PMS     (  914): releaseWL(43fe53a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(44981f40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
,D/PMS     (  914): releaseWL(44981f40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(439d6680): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
,D/PMS     (  914): releaseWL(439d6680): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(44351d48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{425af118: PendingIntentRecord{423eeca8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142743, Int=0
,D/GpsLocationProvider(  914): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  914): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  914): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  914): acquireWL(432cb6d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 914 1000 null
D/PMS     (  914): releaseWL(44351d48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  914): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  914): [NET] getaddrinfo-,err=8
D/libc    (  914): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  914): [NET] getaddrinfo-, 1
,D/libc    (  914): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =9792 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=243
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  914): [NET] getaddrinfo_proxy-, success
,I/global  (  914): call createSocket() return a new socket.
D/libc    (  914): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  914): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  914): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  914): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  914): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  914):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  914): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/AutoSetting( 1316): service - mHandler: update timezone
,D/AutoSetting( 1525): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1525): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  914): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  914): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1525): service - onCreate()
D/AutoSetting( 1525): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1525): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1595): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1595): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  914): batLight: Full, plugged
V/LightsService(  914): setLight #8: color=#c8c800
D/qdlights(  914): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  914): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  914): setLight #8: color=#c800
D/qdlights(  914): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  914): [LedInfo] has indicator attribute
D/qdlights(  914): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  914): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1525): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1525): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1525): service - mHandler: update timezone
,D/AutoSetting( 1525): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1525): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1525): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1525): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1595): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1595): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{42343078 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 1 7 3 11
,D/AutoSetting( 1316): service - mHandler: update timezone
,D/AutoSetting( 1525): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1525): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  914): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1525): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1525): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1595): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1595): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
W/ActivityManager(  914): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  914): batLight: Full, plugged
V/LightsService(  914): setLight #8: color=#c8c800
D/qdlights(  914): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  914): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  914): setLight #8: color=#c800
D/qdlights(  914): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  914): [LedInfo] has indicator attribute
D/qdlights(  914): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  914): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1525): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1525): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1525): service - mHandler: update timezone
,D/AutoSetting( 1525): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1525): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1525): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1525): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1595): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1595): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1316): service - handleMessage() stop self
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/AutoSetting( 1316): service - handleMessage() quit looper
D/AutoSetting( 1316): service - onDestroy() END
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{425bb068 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 3 8 2 11
,D/PMS     (  914): releaseWL(432cb6d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1739955, pollInterval: 10000
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  914): killProcessQuiet, pid=4304
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  914): Killing 4304:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  914): Recipient 4304
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  914): acquireWL(432be650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{4246c128: PendingIntentRecord{42be78c8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=156786, Int=0
,D/PMS     (  914): acquireWL(4392c978): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 914 1000 null
D/PMS     (  914): releaseWL(432be650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,D/PMS     (  914): acquireWL(43f62760): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
,D/PMS     (  914): releaseWL(4392c978): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  914): releaseWL(43f62760): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1729952, pollInterval: 10000
,I/ActivityManager(  914): Waited long enough for: ServiceRecord{42cd5cc8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1719947, pollInterval: 10000
,D/PMS     (  914): acquireWL(44006ae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(44006ae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  914): updateBatteryInfo
D/PMS     (  914): runPSCheck
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1525): service - handleMessage() stop self
,D/AutoSetting( 1525): service - onDestroy() END
,D/AutoSetting( 1525): service - handleMessage() quit looper
,I/ActivityManager(  914): Killing 4392:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  914): killProcessQuiet, pid=4392
D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  914): Recipient 4392
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1709942, pollInterval: 10000
,D/PMS     (  914): acquireWL(43291888): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=180783, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(43291888): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(4404f6e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{10027}
,V/AlarmManager(  914): sending alarm PendingIntent{43ed2028: PendingIntentRecord{4427fef0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=181244, Int=0
,D/PMS     (  914): releaseWL(4404f6e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1699928, pollInterval: 10000
,D/PMS     (  914): acquireWL(443c0d90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  914): sending alarm PendingIntent{42d55048: PendingIntentRecord{42df27a0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190808, Int=0
,D/PMS     (  914): releaseWL(443c0d90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(43f0a6f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=6 [45][3][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  914): acquireWL(43876b00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(43f0a6f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(43876b00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(43d820f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
,D/PMS     (  914): releaseWL(43d820f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(431e8da0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  914): acquireWL(4341a268): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(431e8da0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1229): Scheduling Phenotype for one-off execution 9950 seconds from now (1450312810620)
,D/GetConfigurationSnapshotOperation( 1229): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1229): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1229): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1229): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1229): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1229): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1229): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  914): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1229): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1229): [NET] getaddrinfo-,err=8
D/libc    ( 1229): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1229): [NET] getaddrinfo-, 1
D/libc    ( 1229): [NET] getaddrinfo_proxy+
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =4a1a +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 186
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1229): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1229): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1229): [NET] getaddrinfo-,err=8
D/libc    ( 1229): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1229): [NET] getaddrinfo-,err=8
,D/PMS     (  914): releaseWL(4341a268): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(438c8898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  914): releaseWL(438c8898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  914): acquireWL(43899360): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
D/HtcPowerSaver(  914): updateBatteryInfo
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
,D/PMS     (  914): releaseWL(43899360): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(447bfe70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [11][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
,D/PMS     (  914): releaseWL(447bfe70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1689914, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1679910, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1669906, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1659901, pollInterval: 10000
,D/PMS     (  914): acquireWL(43efa560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(43efa560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  914): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
,I/HtcPowerSaver(  914): >> updateStatus
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1649898, pollInterval: 10000
,D/PMS     (  914): acquireWL(43d41910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=240783, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(43d41910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1639894, pollInterval: 10000
,D/PMS     (  914): acquireWL(42d73960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(42d73960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  914): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1629879, pollInterval: 10000
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1619873, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1609868, pollInterval: 10000
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1599862, pollInterval: 10000
,D/PMS     (  914): acquireWL(43af37c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/PMS     (  914): releaseWL(43af37c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  914): updateBatteryInfo
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
,I/HtcPowerSaver(  914): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1589856, pollInterval: 10000
,D/PMS     (  914): acquireWL(438978b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=300782, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(438978b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1579851, pollInterval: 10000
,D/PMS     (  914): acquireWL(43f8b2d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(43f8b2d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1569847, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1559841, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1549837, pollInterval: 10000
,I/jxcore-log( 4462): Connected to the server!
I/jxcore-log( 4462): 
,I/chromium( 4462): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1539834, pollInterval: 10000
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 4462): --- start :testFindPeers.js---
I/jxcore-log( 4462): 
,I/jxcore-log( 4462): testFindPeers created [object Object]
I/jxcore-log( 4462): 
,I/jxcore-log( 4462): serverPort is 8876
I/jxcore-log( 4462): 
W/dalvikvm( 4462): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4462): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4462): threadid=1: thread exiting with uncaught exception (group=0x41dc0e30)
,E/ActivityManager(  914): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4462): FATAL EXCEPTION: main
E/AndroidRuntime( 4462): Process: com.test.thalitest, PID: 4462
E/AndroidRuntime( 4462): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4462): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 4462): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 4462): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 4462): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 4462): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 4462): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 4462): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4462): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4462): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4462): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4462): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4462): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4462): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4462): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4462): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4462): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4462): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4462): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  914):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  914): killProcessQuiet, pid=4407
,I/ActivityManager(  914): Killing 4407:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
D/Process ( 4462): killProcess, pid=4462
D/Process ( 4462): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  914): Recipient 4407
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/InputDispatcher(  914): channel '42cf2b80 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  914): channel '42cf2b80 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
I/ActivityManager(  914): Recipient 4462
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  914): Process com.test.thalitest (pid 4462) has died.
,W/InputDispatcher(  914): Attempted to unregister already unregistered input channel '42cf2b80 com.test.thalitest.MainActivity (s)'
I/WindowManager(  914): WINDOW DIED Window{42cf2b80 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  914): Client connection lost with reason: 4
,W/WindowManager(  914): Failed looking up window
W/WindowManager(  914): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@4279c8a8 does not exist
W/WindowManager(  914): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  914): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  914): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  914): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  914): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  914): WIN DEATH: null
,W/Binder  ( 1213): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1213): java.lang.NullPointerException
W/Binder  ( 1213): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1213): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1213): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1213): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  914): Got RemoteException sending setActive(false) notification to pid 4462 uid 10389
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1529819, pollInterval: 10000
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  914): acquireWL(441ffc18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=360783, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1274): Grow heap (frag case) to 12.637MB for 50416-byte allocation
D/PMS     (  914): releaseWL(441ffc18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1519803, pollInterval: 10000
,D/PMS     (  914): acquireWL(43dea7a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(43dea7a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  914): updateBatteryInfo
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1509790, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1499776, pollInterval: 10000
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1489760, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1479746, pollInterval: 10000
,D/PMS     (  914): acquireWL(43769898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
D/UsbnetService(  914): BroadcastReceiver::onReceive+
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  914): updateBatteryInfo
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
D/PMS     (  914): releaseWL(43769898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1469730, pollInterval: 10000
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  914): acquireWL(43029318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=420782, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(43029318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1459712, pollInterval: 10000
,D/PMS     (  914): acquireWL(438ae138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(438ae138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  914): updateBatteryInfo
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1449697, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1439680, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1429665, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1419656, pollInterval: 10000
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1409641, pollInterval: 10000
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  914): acquireWL(43a50ed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=480782, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(43a50ed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1399627, pollInterval: 10000
,D/PMS     (  914): acquireWL(43919e40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  914): releaseWL(43919e40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  914): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1389609, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1379594, pollInterval: 10000
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1369579, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1359564, pollInterval: 10000
,D/PMS     (  914): acquireWL(4389a140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(4389a140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  914): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1349549, pollInterval: 10000
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  914): acquireWL(42db6a90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=540782, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1274): Grow heap (frag case) to 12.637MB for 50416-byte allocation
,D/PMS     (  914): releaseWL(42db6a90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1339535, pollInterval: 10000
,D/PMS     (  914): acquireWL(42e05508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
I/BatteryService(  914): n_update end
D/PMS     (  914): releaseWL(42e05508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  914): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1329518, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1319503, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1309487, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1299473, pollInterval: 10000
,D/PMS     (  914): acquireWL(438cf6c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  914): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  914): releaseWL(438cf6c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1289458, pollInterval: 10000
,D/PMS     (  914): acquireWL(443581d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=600782, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(443581d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1279442, pollInterval: 10000
,D/PMS     (  914): acquireWL(438c05d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
,D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/PMS     (  914): releaseWL(438c05d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  914): updateBatteryInfo
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
,I/HtcPowerSaver(  914): >> updateStatus
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  354): inotify_add_watch failed. (No such file or directory)
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1269427, pollInterval: 10000
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1243): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1243): sku_id=99
D/ContactMessageStore( 1243): start background delete task...
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1259413, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1249397, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1239382, pollInterval: 10000
,D/PMS     (  914): acquireWL(42cb5cd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(42cb5cd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1595): [EventService] reorderNotification, total:1
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 1647): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HtcPowerSaver(  914): updateBatteryInfo
V/NotificationService(  914): batLight: plugged
V/LightsService(  914): setLight #8: color=#c8c800
D/qdlights(  914): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  914): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  914): setLight #8: color=#c80000
D/qdlights(  914): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  914): [LedInfo] has indicator attribute
D/PowerUI ( 1119): closing low battery warning: level=98
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/qdlights(  914): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  914): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
,W/ContextImpl( 4513): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/HtcPowerSaver(  914): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:2 level:98 unsupport:false plugged:true
,D/TetherSettings( 3819): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3819): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3819): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3819): Cust_ConnectToPC   : spcsc>false
D/        ( 3819): Cust_ConnectToPC   : IPT>true
,D/        ( 3819): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3819): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3819): Index of the first 1 = -1
W/Settings( 3819): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3819): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3819): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3819): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3819): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 3819): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/SmartNS_Utility( 3819): [ACC]android_networking:tethering_guard_support=false
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1229367, pollInterval: 10000
,D/PMS     (  914): acquireWL(4477b258): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=660782, Int=0
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(4477b258): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1219348, pollInterval: 10000
,D/PMS     (  914): acquireWL(4434a298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  914): n_update end
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/PMS     (  914): releaseWL(4434a298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  914): updateBatteryInfo
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): closing low battery warning: level=98
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
,I/HtcPowerSaver(  914): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:2 level:98 unsupport:false plugged:true
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1209329, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1199310, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1189294, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1179275, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1169261, pollInterval: 10000
,D/PMS     (  914): acquireWL(43f31548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=720783, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(43f31548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1159248, pollInterval: 10000
,D/PMS     (  914): acquireWL(43f2d2f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  914): releaseWL(43f2d2f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  914): updateBatteryInfo
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=98
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  914): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:2 level:98 unsupport:false plugged:true
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1149234, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1139216, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1129199, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1119182, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1109168, pollInterval: 10000
,D/PMS     (  914): acquireWL(43f1fee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=780782, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(43f1fee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1099153, pollInterval: 10000
,D/PMS     (  914): acquireWL(43efc438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(43efc438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1089139, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1079124, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1069112, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1059094, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1049080, pollInterval: 10000
,D/PMS     (  914): acquireWL(43df3f80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=840783, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(43df3f80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(43d52ee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/HtcPowerSaver(  914): updateBatteryInfo
D/UsbnetService(  914): BroadcastReceiver::onReceive+
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=99
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  914): releaseWL(43d52ee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  914): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:2 level:99 unsupport:false plugged:true
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1039068, pollInterval: 10000
,D/PMS     (  914): acquireWL(438c8898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  914): n_update end
D/PMS     (  914): releaseWL(438c8898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  914): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=99
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
,I/HtcPowerSaver(  914): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:2 level:99 unsupport:false plugged:true
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1029052, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1019037, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1009021, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 999009, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 988989, pollInterval: 10000
,D/PMS     (  914): acquireWL(4379abb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=900782, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(4379abb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(43767730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(43767730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 978973, pollInterval: 10000
,D/PMS     (  914): acquireWL(433c5520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(433c5520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 968957, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 958942, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 948925, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 938910, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 928894, pollInterval: 10000
,D/PMS     (  914): acquireWL(4308aaa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=960783, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(4308aaa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 918878, pollInterval: 10000
,D/PMS     (  914): acquireWL(42e53900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(42e53900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 908863, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 898846, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 888829, pollInterval: 10000
,D/ConnectivityService(  914): Sampling interval elapsed, updating statistics ..
,D/PMS     (  914): acquireWL(42dbe318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{424b4598: PendingIntentRecord{42ac0e40 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=790535, Int=0
,I/ActivityManager(  914): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4901 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  914): sending alarm PendingIntent{42d130c8: PendingIntentRecord{42b5a268 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450312833969, Int=10800000
D/ConnectivityService(  914): Done.
,D/ConnectivityService(  914): Setting timer for 720seconds
,V/AlarmManager(  914): sending alarm PendingIntent{43e24230: PendingIntentRecord{42e8a948 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450313387618, Int=1800000
,V/AlarmManager(  914): sending alarm PendingIntent{42d9fde0: PendingIntentRecord{42d3e2b0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450313554294, Int=900000
,V/AlarmManager(  914): sending alarm PendingIntent{432f05f0: PendingIntentRecord{431be168 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450313627531, Int=0
,D/PMS     (  914): acquireWL(43bed2e0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2165 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4513): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  914): acquireWL(42c07140): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2165 10029 WorkSource{10029 com.google.android.gms},
,D/PMS     (  914): releaseWL(43bed2e0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/PowerUsageService( 4513): call getInstance()
D/SmartSyncUtils( 4513): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4513): MY_DEBUG = false
D/PMS     (  914): acquireWL(4249ad20): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4513 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4513): [updateNmRange] bManual = false
,D/PMS     (  914): releaseWL(42dbe318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
I/EventLogService( 2165): Aggregate from 1450312733559 (log), 1450311587577 (data)
D/SmartSyncScreenOnOffTimeReceiver( 4513): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4513): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4513): SettingOnTime = 1450332000000, randomSettingOnTime = 1450329410000
D/SmartSyncScreenOnOffTimeReceiver( 4513): SettingOffTime = 1450317600000, randomSettingOffTime = 1450318224000
,D/SmartSyncScreenOnOffTimeReceiver( 4513): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4513): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4513): bNightModeTurnOffOnce = false
D/ConnectivityService(  914): getActiveNetworkInfo called by com.htc.aurora (4901/10049)
W/BatSI   (  914): Couldn't get kernel wake lock stats
D/PMS     (  914): releaseWL(4249ad20): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
,D/PMS     (  914): releaseWL(42c07140): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  914): Couldn't get kernel wake lock stats
,W/BatSI   (  914): Couldn't get kernel wake lock stats
,W/BatSI   (  914): Couldn't get kernel wake lock stats
,D/Process (  914): killProcessQuiet, pid=4433
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  914): Killing 4433:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 878820, pollInterval: 10000
,I/ActivityManager(  914): Recipient 4433
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  914): acquireWL(42db9f78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  914): sending alarm PendingIntent{434201d8: PendingIntentRecord{430f5378 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1018108, Int=0
,D/PMS     (  914): acquireWL(42e822e0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(42e822e0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(42db9f78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(43021c68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
,D/ConnectivityService(  914): reportInetCondition for net 1, percentage: 100 by  (1375/10029)
D/ConnectivityService(  914): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  914): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1375/10029)
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360024971
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025234
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025469
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025474
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025484
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027759
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027789
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360030533
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360032086
,D/PMS     (  914): releaseWL(43021c68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 868806, pollInterval: 10000
,D/ConnectivityService(  914): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  914): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  914): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=2 [137][4][0]
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  914): acquireWL(442b8278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1020782, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(442b8278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(43887218): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetPhoneState( 1647): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/PMS     (  914): releaseWL(43887218): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  914): updateBatteryInfo
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/DotMatrix( 1595): [EventService] reorderNotification, total:0
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
V/NotificationService(  914): batLight: Full, plugged
V/LightsService(  914): setLight #8: color=#c8c800
D/qdlights(  914): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  914): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  914): setLight #8: color=#c800
D/qdlights(  914): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  914): [LedInfo] has indicator attribute
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/qdlights(  914): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  914): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
W/ContextImpl( 4513): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  914): << updateStatus
,D/TetherSettings( 3819): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3819): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3819): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3819): Cust_ConnectToPC   : spcsc>false
D/        ( 3819): Cust_ConnectToPC   : IPT>true
D/        ( 3819): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3819): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3819): Index of the first 1 = -1
,W/Settings( 3819): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3819): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3819): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3819): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3819): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 3819): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 858792, pollInterval: 10000
,D/PMS     (  914): acquireWL(431250a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  914): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  914): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  914): releaseWL(431250a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 848775, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 838758, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 828742, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 818724, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 808710, pollInterval: 10000
,D/PMS     (  914): acquireWL(42c98410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1080783, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(42c98410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(4319d620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(4319d620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 798696, pollInterval: 10000
,D/PMS     (  914): acquireWL(43f73de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(43f73de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 788677, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 778661, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 768643, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 758628, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 748611, pollInterval: 10000
,D/PMS     (  914): acquireWL(43f87d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1140783, Int=0
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(43f87d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(44344280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  914): updateBatteryInfo
D/PMS     (  914): releaseWL(44344280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  914): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 738598, pollInterval: 10000
,D/PMS     (  914): acquireWL(43978da0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
,D/UsbnetService(  914): onReceive BATTERY_CHANGED
,D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/PMS     (  914): releaseWL(43978da0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  914): updateBatteryInfo
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 728584, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 718570, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 708556, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 698536, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 688522, pollInterval: 10000
,D/PMS     (  914): acquireWL(438890e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1200783, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(438890e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(43a19550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(43a19550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 678509, pollInterval: 10000
,D/PMS     (  914): acquireWL(4433a280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(4433a280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  354): inotify_add_watch failed. (No such file or directory)
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 668491, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 658477, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 648459, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 638439, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 628421, pollInterval: 10000
,D/PMS     (  914): acquireWL(4339f3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1260783, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(4339f3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 618404, pollInterval: 10000
,D/PMS     (  914): acquireWL(439937b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(439937b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 608389, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 598372, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 588358, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 578341, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 568325, pollInterval: 10000
,D/PMS     (  914): acquireWL(44204c38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1320782, Int=0
,D/PMS     (  914): releaseWL(44204c38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 558312, pollInterval: 10000
,D/PMS     (  914): acquireWL(43e30df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(43e30df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 548296, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 538281, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 528266, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 518250, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 508231, pollInterval: 10000
,D/PMS     (  914): acquireWL(42d74438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1380783, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1274): Grow heap (frag case) to 12.685MB for 50416-byte allocation
D/PMS     (  914): releaseWL(42d74438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 498216, pollInterval: 10000
,D/PMS     (  914): acquireWL(43d82878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(43d82878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 488196, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 478180, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 468166, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 458151, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 448136, pollInterval: 10000
,D/PMS     (  914): acquireWL(42e97170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1440782, Int=0
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(42e97170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 438118, pollInterval: 10000
,D/PMS     (  914): acquireWL(43dc9508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(43dc9508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 428101, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 418087, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 408067, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 398052, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 388037, pollInterval: 10000
,D/PMS     (  914): acquireWL(4392bd68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1500782, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(4392bd68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 378022, pollInterval: 10000
,D/PMS     (  914): acquireWL(44200b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(44200b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 368008, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 357993, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 347979, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 337962, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 327948, pollInterval: 10000
,D/PMS     (  914): acquireWL(43fa4e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1560782, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(43fa4e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 317939, pollInterval: 10000
,D/PMS     (  914): acquireWL(42c6b660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(42c6b660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 307922, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 297906, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 287892, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 277876, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 267861, pollInterval: 10000
,D/PMS     (  914): acquireWL(43928d50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1620782, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(43928d50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 257845, pollInterval: 10000
,D/PMS     (  914): acquireWL(43941b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(43941b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 247831, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 237816, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 227799, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 217783, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 207768, pollInterval: 10000
,D/PMS     (  914): acquireWL(43f545a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1680782, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(43f545a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 197753, pollInterval: 10000
,D/PMS     (  914): acquireWL(433c4a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(433c4a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 187737, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 177722, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 167707, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 157691, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 147676, pollInterval: 10000
,D/PMS     (  914): acquireWL(441ca830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1740782, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(441ca830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 137660, pollInterval: 10000
,D/PMS     (  914): acquireWL(431b3b80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(431b3b80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 127644, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 117628, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 107610, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 97593, pollInterval: 10000
,W/BatSI   (  914): Couldn't get kernel wake lock stats
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 87576, pollInterval: 10000
,D/PMS     (  914): acquireWL(433d21f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1800783, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(433d21f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 77561, pollInterval: 10000
,D/PMS     (  914): acquireWL(43f5e9d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(43f5e9d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  354): inotify_add_watch failed. (No such file or directory)
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 67548, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 57532, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 47518, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 37502, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 27484, pollInterval: 10000
,D/PMS     (  914): acquireWL(433970f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
V/AlarmManager(  914): sending alarm PendingIntent{42a903c8: PendingIntentRecord{42a7e6d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1860783, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  914): Prepared write state in 55ms
,I/ProcessStatsService(  914): Pruning old procstats: /data/system/procstats/state-2015-12-16-12-11-00.bin
,D/PMS     (  914): releaseWL(433970f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 17470, pollInterval: 10000
,D/PMS     (  914): acquireWL(448b04a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(448b04a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 7455, pollInterval: 10000
,D/Finsky  ( 4148): [1] ExperimentsChangeHandler$2.run: Exiting process because of stale process stable experiments
,I/ActivityManager(  914): Recipient 4148
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  914): Process com.android.vending (pid 4148) has died.
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4929): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4929): ====startRecUseTime====
D/htc.customization.log.level( 4929):  is 
W/CustomizationLogLevel( 4929): Level value is invalid, use default level 2
D/CustomizationManager( 4929):  Read ACC file spent 0.126 (s)
D/CIDMapFileReader( 4929): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4929): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4929): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4929): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4929): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4929): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4929): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4929): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4929): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4929): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4929): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4929): Parsing tag category name = system
I/CustomizationCIDLoader( 4929): Parsing tag category name = application
I/CustomizationCIDLoader( 4929): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4929): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4929): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4929): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4929): Parsing tag category name = Settings
D/CustomizationManager( 4929):  Read CID file spent 0.178 (s)
D/CustomizationManager( 4929):  All configurations done spent 0.179 (s)
W/HtcNativeFlag( 4929): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4929): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4929): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4929): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  914): deletePackageAsUser: pkg=com.test.thalitest, pid=4929, uid=2000 user=0
I/ActivityManager(  914): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  914): killProcessQuiet, pid=4557
D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  914): killProcessQuiet, pid=4662
D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  914): Killing 4557:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
I/ActivityManager(  914): Killing 4662:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1803s
D/Process (  914): killProcessQuiet, pid=4647
D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  914): killProcessQuiet, pid=4633
D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  914): Killing 4647:com.android.chrome/u0a96 (adj 15): empty for 1803s
I/ActivityManager(  914): Killing 4633:com.google.android.setupwizard/u0a79 (adj 15): empty for 1803s
I/ActivityManager(  914): Recipient 4647
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  914): Recipient 4633
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  914): Recipient 4662
W/asset   (  914): Copying FileAsset 0x67888cc8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  914): Skipping PackageSetting{429094b0 com.example.hello/10397} due to missing metadata
I/ActivityManager(  914): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/ActivityManager(  914): Recipient 4557
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  914): Client com.google.android.music (pid 4557): Died!
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1595): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1595): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1595): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
W/BroadcastQueue(  914): Failure sending broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
W/BroadcastQueue(  914): android.os.DeadObjectException
W/BroadcastQueue(  914): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  914): 	at android.app.ApplicationThreadProxy.scheduleRegisteredReceiver(ApplicationThreadNative.java:1211)
W/BroadcastQueue(  914): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:454)
W/BroadcastQueue(  914): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:564)
W/BroadcastQueue(  914): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:636)
W/BroadcastQueue(  914): 	at com.android.server.am.BroadcastQueue$1.handleMessage(BroadcastQueue.java:147)
W/BroadcastQueue(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  914): 	at android.os.Looper.loop(Looper.java:157)
W/BroadcastQueue(  914): 	at com.android.server.am.ActivityManagerService$AThread.run(ActivityManagerService.java:2098)
D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  914):   Scheme: "sms"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
W/SQLiteConnectionPool( 2165): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/GeofencerStateMachine( 1229): Ignoring removeGeofence because network location is disabled.
D/PMS     (  914): acquireWL(42c78848): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): releaseWL(42c78848): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  914):   Scheme: "smsto"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
D/VoicemailCleanupService( 1288): Cleaning up data for package: com.test.thalitest
W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/Launcher( 1274): Deferring update until onResume
D/Launcher( 1274): waitUntilResume // bindAppsRemoved
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  914):   Scheme: "mms"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  914):   Scheme: "mmsto"
I/[PluginManager]RegisterService( 1316): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/[PluginManager]RegisterService( 1316): handle notify Blinkfeed plugin client changed
I/InputMethodManagerService(  914): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/Prism.PackageStateRece_( 1274): action: android.intent.action.PACKAGE_REMOVED
W/SystemReader( 1260): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  914):   Scheme: "sms"
I/IcingCorporaProvider( 2869): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  914):   Scheme: "smsto"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
E/ExternalAccountType( 1341): Unsupported attribute readOnly
I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  914):   Scheme: "mms"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  914):   Scheme: "mmsto"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/ActivityManager(  914): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4943 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  914): acquireWL(447b38f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
V/AlarmManager(  914): sending alarm PendingIntent{424b4598: PendingIntentRecord{42ac0e40 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1728354, Int=0
V/AlarmManager(  914): sending alarm PendingIntent{426789d0: PendingIntentRecord{42cd1a58 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1822137, Int=1800000
V/AlarmManager(  914): sending alarm PendingIntent{42e78390: PendingIntentRecord{433a1850 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1857085, Int=0
V/AlarmManager(  914): sending alarm PendingIntent{441d9f00: PendingIntentRecord{430f5378 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1918871, Int=0
V/AlarmManager(  914): sending alarm PendingIntent{42d9fde0: PendingIntentRecord{42d3e2b0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450314454294, Int=900000
D/PMS     (  914): acquireWL(44070d28): PARTIAL_WAKE_LOCK  Icing 0x1 2165 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2869): UpdateCorporaTask done [took 615 ms] updated apps [took 615 ms] 
E/SQLiteDatabase( 4943): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4943): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4943): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4943): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4943): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4943): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4943): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4943): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4943): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4943): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4943): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4943): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4943): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4943): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4943): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4943): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4943): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4943): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4943): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4943): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4943): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4943): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4943): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4943): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4943): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4943): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4943): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4943): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4943): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4943): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4943): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4943): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4943): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4943): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4943): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4943): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4943): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4943): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4943): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4943): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4943): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4943): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4943): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4943): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4943): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4943): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4943): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4943): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4943): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4943): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4943): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4943): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4943): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4943): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4943): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4943): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4943): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4943): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4943): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4943): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4943): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4943): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4943): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4943): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4943): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4943): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4943): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4943): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4943): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4943): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4943): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4943): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4943): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4943): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4943): threadid=11: thread exiting with uncaught exception (group=0x41dc0e30)
E/ActivityManager(  914): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4943): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4943): Process: com.google.android.apps.docs, PID: 4943
E/AndroidRuntime( 4943): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4943): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4943): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4943): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4943): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4943): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4943): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4943): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4943): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4943): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4943): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4943): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4943): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4943): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4943): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  914): Can't write: system_app_crash
E/DropBoxManagerService(  914): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  914): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  914): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  914): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  914): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  914): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  914): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  914): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  914): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  914): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  914): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  914): 	... 5 more
D/Process ( 4943): killProcess, pid=4943
D/Process ( 4943): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  914): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4961 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/JavaBinder(  914): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  914): Recipient 4943
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  914): Process com.google.android.apps.docs (pid 4943) has died.
W/ContextImpl( 4961): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  914): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4974 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4961): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4961): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4961): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4961): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4961): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4961): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4961): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4961): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4961): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4961): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4961): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4961): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4961): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4961): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4961): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4961): threadid=10: thread exiting with uncaught exception (group=0x41dc0e30)
E/AndroidRuntime( 4961): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4961): Process: com.android.keychain, PID: 4961
E/AndroidRuntime( 4961): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4961): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4961): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4961): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4961): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4961): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4961): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4961): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4961): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4961): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4961): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4961): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4961): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4961): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  914): App crashed! Process: com.android.keychain
D/ErrorReport(  914): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4974): getInstance(Context context)
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@42283bd0 +
I/Prism.WidgetManager( 1274): onLoadItems() +
D/Process ( 4961): killProcess, pid=4961
D/Process ( 4961): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  914): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  914): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450314539069.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  914): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  914): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  914): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  914): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  914): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  914): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  914): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  914): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  914): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  914): 	... 4 more
D/AppTag  ( 4974): getInstance(Context context)
D/AppTag  ( 4974): onCreate()
I/ActivityManager(  914): Recipient 4961
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  914): Process com.android.keychain (pid 4961) has died.
W/ActivityManager(  914): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/PMS     (  914): acquireWL(428d7bf8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4123 10160 null
D/PMS     (  914): releaseWL(428d7bf8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  914): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4992 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
W/dalvikvm( 4992): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
I/PackageManager(  914):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4992, uid=10074, userID:0
I/Icing   ( 2165): Indexing 5DDFBB04CEF4FFE894538F4951832FAB899ACA77 from com.google.android.googlequicksearchbox
W/PackageManager(  914): Unable to load service info ResolveInfo{42b75fe0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  914): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  914): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  914): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  914): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  914): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  914): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  914): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  914): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  914): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  914): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  914): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  914): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  914): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  914): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  914): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  914): 	at dalvik.system.NativeStart.main(Native Method)
D/Finsky  ( 4992): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  914): getAllNetworkInfo called by com.android.vending (4992/10074)
E/Icing   ( 2165): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 2165): Could not init tag ds.tag.deleted
W/dalvikvm( 4992): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
W/dalvikvm( 4992): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  914): getAllNetworkInfo called by com.android.vending (4992/10074)
I/Icing   ( 2165): Indexing done 5DDFBB04CEF4FFE894538F4951832FAB899ACA77
D/PMS     (  914): releaseWL(44070d28): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
E/RollingFileStream( 4992): Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".
D/Finsky  ( 4992): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/dalvikvm( 4992): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/Settings( 4992): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4992): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4992): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4992): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4992): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4992): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4992): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:282)
E/SQLiteDatabase( 4992): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:1075)
E/SQLiteDatabase( 4992): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4992): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4992): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4992): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4992): threadid=27: thread exiting with uncaught exception (group=0x41dc0e30)
E/SQLiteDatabase( 4992): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 4992): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4992): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4992): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4992): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 4992): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:370)
E/SQLiteDatabase( 4992): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 4992): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:3082)
E/SQLiteDatabase( 4992): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4992): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4992): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4992): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4992): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4992): 	at java.lang.Thread.run(Thread.java:864)
W/Finsky.CrashDetector( 4992): Failed to write crash file cnt=0, ts=0.
W/Finsky.CrashDetector( 4992): java.io.FileNotFoundException: /data/data/com.android.vending/cache/crash804305: open failed: EROFS (Read-only file system)
W/Finsky.CrashDetector( 4992): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/Finsky.CrashDetector( 4992): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/Finsky.CrashDetector( 4992): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/Finsky.CrashDetector( 4992): 	at com.google.android.finsky.CrashDetector.safeWriteCrashFile(CrashDetector.java:169)
W/Finsky.CrashDetector( 4992): 	at com.google.android.finsky.CrashDetector.uncaughtException(CrashDetector.java:97)
W/Finsky.CrashDetector( 4992): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
W/Finsky.CrashDetector( 4992): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
W/Finsky.CrashDetector( 4992): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/Finsky.CrashDetector( 4992): 	at libcore.io.Posix.open(Native Method)
W/Finsky.CrashDetector( 4992): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/Finsky.CrashDetector( 4992): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/Finsky.CrashDetector( 4992): 	... 6 more
W/dalvikvm( 4992): threadid=28: thread exiting with uncaught exception (group=0x41dc0e30)
E/ActivityManager(  914): App crashed! Process: com.android.vending
W/dalvikvm( 4992): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
E/AndroidRuntime( 4992): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4992): Process: com.android.vending, PID: 4992
E/AndroidRuntime( 4992): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4992): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4992): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4992): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:282)
E/AndroidRuntime( 4992): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:1075)
E/AndroidRuntime( 4992): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4992): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4992): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4992): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4992): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4992): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/Process ( 4992): killProcess, pid=4992
D/Process ( 4992): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.CrashDetector.uncaughtException:100 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  914): Can't write: system_app_crash
E/DropBoxManagerService(  914): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  914): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  914): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  914): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  914): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  914): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  914): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  914): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  914): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  914): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  914): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  914): 	... 5 more
D/PackageBroadcastService( 2165): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2165): Clearing selected account for com.test.thalitest

```
