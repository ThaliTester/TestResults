#### Test 50650278d76d9c3_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  906): Waited long enough for: ServiceRecord{42ddb860 u0 com.htc.htclocationservice/.AutoSettingService}
,--------- beginning of /dev/log/main
E/cutils-trace( 4398): Error opening trace file: No such file or directory (2)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/CustomizationManager( 4398): ====startRecUseTime====
D/htc.customization.log.level( 4398):  is 
W/CustomizationLogLevel( 4398): Level value is invalid, use default level 2
D/CustomizationManager( 4398):  Read ACC file spent 0.053 (s)
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4398): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4398): Parsing tag category name = system
I/CustomizationCIDLoader( 4398): Parsing tag category name = application
I/CustomizationCIDLoader( 4398): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4398): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4398): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4398): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4398): Parsing tag category name = Settings
D/CustomizationManager( 4398):  Read CID file spent 0.092 (s)
D/CustomizationManager( 4398):  All configurations done spent 0.092 (s)
W/HtcNativeFlag( 4398): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4398): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4398): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4398): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4398
D/PMS     (  906): acquireHCC(424e1210): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(423f1f28): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x6b4430e8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1113173432
I/FeedHostManager( 1268): [onPause]
I/FeedProviderManager( 1268): onPause
I/FeedHostManager( 1268): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41ca1558
I/SocialFeedProvider( 1268): +onPause
I/SocialFeedProvider( 1268): -onPause
D/PMS     (  906): acquireWL(420a0d80): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4409 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1268): [trimMemory] 20
W/asset   ( 4409): Copying FileAsset 0x5c759408 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4409): Binding Chromium to main looper Looper (main, tid 1) {41ae9a30}
I/LibraryLoader( 4409): Expected native library version number "",actual native library version number ""
I/chromium( 4409): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4409): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(42116cb8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): acquireWL(42032210): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41ce8690:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4409): 1102057672: getState(). Returning 12
D/PMS     (  906): releaseWL(42116cb8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4409): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4409): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4409): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4409): Local Branch: 
I/Adreno-EGL( 4409): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4409): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4409):                  aa63bbd948f41d15fc72f585e
W/chromium( 4409): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4409): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4409): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4409): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4409): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4409): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4409): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4409): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4409): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4409): CordovaWebView is running on device made by: HTC
,W/AwContents( 4409): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1268
,W/ResourceType( 4409): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4409): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b32778, mServedView=org.apache.cordova.engine.SystemWebView{41af83e0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  906): Enable input method client, pid=4409
,W/AwContents( 4409): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +276ms
,D/PMS     (  906): releaseWL(420a0d80): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4409): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4409): JniHelper::setJavaVM(0x415c1048), pthread_self() = 1662503808
D/JX-Cordova( 4409): jxcore cordova android initializing
,I/dalvikvm-heap( 4409): Grow heap (frag case) to 11.556MB for 96598-byte allocation
,I/dalvikvm-heap( 4409): Grow heap (frag case) to 11.605MB for 144892-byte allocation
,I/dalvikvm-heap( 4409): Grow heap (frag case) to 11.716MB for 217334-byte allocation
,I/dalvikvm-heap( 4409): Grow heap (frag case) to 11.893MB for 325996-byte allocation
,I/dalvikvm-heap( 4409): Grow heap (frag case) to 12.167MB for 488990-byte allocation
,I/dalvikvm-heap( 4409): Grow heap (frag case) to 13.174MB for 1100216-byte allocation
,I/dalvikvm-heap( 4409): Grow heap (frag case) to 14.048MB for 1650320-byte allocation
,I/dalvikvm-heap( 4409): Grow heap (frag case) to 15.434MB for 2475476-byte allocation
,I/dalvikvm-heap( 4409): Grow heap (frag case) to 17.453MB for 3713210-byte allocation
,D/PMS     (  906): acquireWL(42408668): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,D/PMS     (  906): releaseWL(42408668): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(425f4740): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,W/jxcore-log( 4409): Initializing JXcore engine
,W/jxcore-log( 4409): JXcore engine is ready
D/PMS     (  906): releaseWL(425f4740): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(4247de58): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,D/PMS     (  906): releaseWL(4247de58): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42fd79f0): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,W/jxcore-log( 4409): Starting JXcore engine
D/PMS     (  906): releaseWL(42fd79f0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
,W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
D/PMS     (  906): releaseHCC(424e1210): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
,D/PMS     (  906): releaseHCC(423f1f28): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4409): Platform android
W/jxcore-log( 4409): 
,W/jxcore-log( 4409): Process ARCH arm
W/jxcore-log( 4409): 
,I/jxcore-log( 4409): JXcore Cordova bridge is ready!
I/jxcore-log( 4409): 
,W/jxcore-log( 4409): JXcore engine is started
,I/chromium( 4409): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): acquireWL(42599ef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{43b41ac8: PendingIntentRecord{42580798 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450463635425, Int=1800000
,D/PMS     (  906): acquireWL(41e54d40): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1222 10028 null
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4457 uid=10077 gids={50077}
,V/AlarmManager(  906): sending alarm PendingIntent{42587bd0: PendingIntentRecord{425f0ec8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450463657668, Int=60000
,D/PMS     (  906): releaseWL(42599ef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): acquireWL(44073348): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1222 10028 null
,I/EventLogService( 1222): Aggregate from 1450463608156 (log), 1450461835364 (data)
D/PMS     (  906): releaseWL(41e54d40): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,D/SMSBackup( 4457): SMSBackupAgentService started
,D/SMSBackup( 4457): Checking restore status
D/SMSBackup( 4457): Restore complete
,D/SMSBackup( 4457): cancelCheckAlarm
,D/SMSBackup( 4457): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3199
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3199:com.android.defcontainer/u0a19 (adj 15): empty #17
D/PMS     (  906): releaseWL(42032210): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  906): releaseWL(44073348): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,I/ActivityManager(  906): Recipient 3199
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 4409): Toggling radios to true
I/jxcore-log( 4409): 
,D/BluetoothAdapter( 4409): enable(): BT is already enabled..!
,D/WifiManager( 4409): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1350
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: true pid=4409, uid=10348
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  906): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
W/Settings:Agent(  906): << traceCallingStack(): 1(ms)
D/WifiManager( 4409): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
D/WifiManager( 4409): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): TDLS: Tear down peers
I/wpa_supplicant( 1136): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4409): Radios toggled
I/jxcore-log( 4409): 
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4409): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4409): 
I/jxcore-log( 4409): Perf Test app loaded loaded
I/jxcore-log( 4409): 
I/Choreographer( 4409): Skipped 80 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4409): check test folder
I/jxcore-log( 4409): 
,I/jxcore-log( 4409): found test : ./testFindPeers.js
I/jxcore-log( 4409): 
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1136): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1136): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1136): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1136): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 1136): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1136): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1136): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1136): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb865bbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1136):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1136): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1136): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1136): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1136): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - EA,P success=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1136): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1136): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1136): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1136): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1136): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1136): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1136): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1136): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1136): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1136): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  906):    returned true
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): Power_Mode_Type mode = 0
I/wpa_supplicant( 1136): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
,D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  906): acquireWL(425bb570): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
,I/jxcore-log( 4409): found test : ./testSendData.js
I/jxcore-log( 4409): 
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  906): [RunningState] Stop DHCP
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): Fast associate: Old scan results
I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
D/WifiNative-wlan0(  906):    returned true
D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiP2pService(  906): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19817 mDataStallAlarmIntent=PendingIntent{425891f8: PendingIntentRecord{424e0118 android broadcastIntent}}
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): Power_Mode_Type mode = 0
I/wpa_supplicant( 1136): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 61
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1839/10178)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  906): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WISPrService( 4189): >>>>>WISPrService start isConnected = false<<<<<
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/UsbnetStateTracker(  906): isAvailable+-
,D/UsbnetStateTracker(  906): reconnect
,D/UsbnetStateTracker(  906): isAvailable+-
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/WifiService(  906): New client listening to asynchronous messages
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
,D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/WISPrService( 4189): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 4189): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4189): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1839/10178)
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  364): [NET] entry_id:5   entry:0xb762ff98  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb7633fd8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb7634248  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb7630190  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb76340e8  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb7634410  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/PMS     (  906): acquireWL(42528d70): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10028 null
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/PMS     (  906): acquireWL(430db840): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(424cdfe8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  906): releaseWL(430db840): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  906):    returned false
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1369/10028)
D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  906): releaseWL(42528d70): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
,D/ConnectivityService(  906): mActiveDefaultNetwork: -1
,D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
,D/PMS     (  906): releaseWL(424cdfe8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/chromium( 4409): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  906): NoActiveNetworkState
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(4402a258): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1436/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4299/10100)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3859/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1888/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1268/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1839/10178)
I/ConnectivityHelper( 1268): [onReceive] WIFI(1): DISCONNECTED,
,I/NetworkMonitor( 3859): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4299/10100)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2427/10021)
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4479 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  906): releaseWL(4402a258): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4479): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4479): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4479): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4479): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4479): Preparing secondary program dexes.
,V/DexLibLoader( 4479): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4479): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4479): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4479): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4479): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4479): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4479): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4479): Dex already copied
D/OdexVerifier( 4479): Odex verification is skipped.
,V/DexLibLoader( 4479): Creating class loader
,V/DexLibLoader( 4479): Finished creating class loader
V/DexLibLoader( 4479): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4479): Dex already copied
D/OdexVerifier( 4479): Odex verification is skipped.
,V/DexLibLoader( 4479): Creating class loader
,V/DexLibLoader( 4479): Finished creating class loader
V/DexLibLoader( 4479): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4479): Dex already copied
D/OdexVerifier( 4479): Odex verification is skipped.
,V/DexLibLoader( 4479): Creating class loader
V/DexLibLoader( 4479): Finished creating class loader
V/DexLibLoader( 4479): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 4479): Dex already copied
D/OdexVerifier( 4479): Odex verification is skipped.
,V/DexLibLoader( 4479): Creating class loader
V/DexLibLoader( 4479): Finished creating class loader
,V/DexLibLoader( 4479): Verifying classes from secondary dexes.
,D/DexLibLoader( 4479): DexLibLoader.ensureDexLoaded took 20 ms
,W/dalvikvm( 4479): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4479): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4479): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4479): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4479): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4479): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4479): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4479): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4479): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-47
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-47
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1136): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-89
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-89
D/wpa_supplicant( 1136): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1136): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1136): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1136): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1136): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1136): Add randomness: count=11 entropy=5
D/wpa_supplicant( 1136): Add randomness: count=12 entropy=6
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-47
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 3
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->b,t_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 1
I/wpa_supplicant( 1136): wpa_s->is_screen_on 1
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): selected network = 1
D/wpa_supplicant( 1136): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb865d4e8  current_ssid=0x0
D/wpa_supplicant( 1136): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1136): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1136): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1136): check if in concurrent case
I/wpa_supplicant( 1136): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1136): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1136): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1136): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1136): RSN: PMKSA cache search - network_ctx=0xb865d4e8 try_opportunistic=0
D/wpa_supplicant( 1136): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1136): RSN: No PMKSA cache entry found
,I/wpa_supplicant( 1136): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1136): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1136): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1136): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1136): nl80211: Unsubscribe mgmt frames handle 0xb865c718 (mode change)
D/wpa_supplicant( 1136): nl80211: Subscribe to mgmt frames with non-AP handle 0xb865c718
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb865c718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb865c718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb865c718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb865c718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb865c718
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb865c718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb865c718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb865c718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb865c718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb865c718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1136):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1136):   * freq=2412
D/wpa_supplicant( 1136):   * Auth Type 0
D/wpa_supplicant( 1136):   * WPA Versions 0x2
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1136): nl80211: Connect request send successfully
D/wpa_supplicant( 1136): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1136): reply (926) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-49
I/wpa_supplicant( 1136): tsf=0000000107181306
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-47
I/wpa_supplicant( 1136): tsf=0000000107181350
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
,I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2427
I/wpa_supplicant( 1136): level=-77
I/wpa_supplicant( 1136): tsf=0000000021611668
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-47
I/wpa_supplicant( 1136): tsf=0000000107181320
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=01ABC
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000107181364
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC4688432
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=5
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2462
I/wpa_supplicant( 1136): level=-89
I/wpa_supplicant( 1136): tsf=0000000107181361
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=6
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2462
I/wpa_supplicant( 1136): level=-89,
I/wpa_supplicant( 1136): tsf=0000000107181368
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC5999698
I/wpa_supplicant( 1136): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 107181306, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 2412, timestamp: 107181350, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 21611668, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -47, frequency: 2412, timestamp: 107181320, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 107181364, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 107181361, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2462, timestamp: 107181368, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 7 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 640a0300 uid:1000
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (7) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,E/FbInjectorInitializer( 4479): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1136): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1136): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1136): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1136): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1136): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1136): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1136): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1136): nl80211: Connect event
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1136): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1136): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1136): Add randomness: count=13 entropy=7
I/wpa_supplicant( 1136): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1136): TDLS: Remove peers on association
D/wpa_supplicant( 1136): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1136): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1136): EAPOL: enable timer tick
D/wpa_supplicant( 1136): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1136): htc_wext_set_keepalive +
I/wpa_supplicant( 1136): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1136): getPrivFuncNum +	
I/wpa_supplicant( 1136): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1136): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1136): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1136): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1136): Get randomness: len=32 entropy=8
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantSt,ateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Associated
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
I/wpa_supplicant( 1136): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb865c9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1136):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1136): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1136): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f74b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1136):    broadcast key
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1136): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1136): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1136): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1136): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1136): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1136): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1136): set send_ind_to_ndc = 0
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1136): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1136): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1136): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1136): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1136): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1136): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1136): EAPOL authentication completed successfully
I/wpa_supplicant( 1136): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1136): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1136): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1136): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/WISPrService( 4189): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4189): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
W/fb4a(:<default>):StaticBindingVerifier( 4479): Verify
D/DhcpStateMachine(  906): [StoppedState] Start DHCP
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): Power_Mode_Type mode = 1
I/wpa_supplicant( 1136): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(42a58ba0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
,D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41b827d0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41b827d0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4479): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4479): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=4240
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4240:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/PMS     (  906): acquireWL(436424d8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1222 10028 null
I/ActivityManager(  906): Recipient 4240
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,D/PMS     (  906): acquireWL(43ba2428): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1222 10028 null
,D/PMS     (  906): releaseWL(436424d8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/GCM     ( 1369): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
D/PMS     (  906): releaseWL(43ba2428): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1414): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4508 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1414/10053)
,D/AutoSetting( 1414): Util - no network available!
,D/AutoSetting( 1414): service - onCreate()
,D/AutoSetting( 1414): service - AddressCache: using context: com.htc.Weather
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1414/10053)
,D/LocationManagerService(  906): request 424fb118 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/AutoSetting( 1414): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1414): service - mHandler: cancel location update
,D/AutoSetting( 1414): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4479): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4479): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4508): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,W/fb4a(:<default>):UserScope( 4479): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/MobileConnectivityChangeReceiver( 4508): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4508): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4508): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4524 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4508/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4508/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4508/10078)
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4479): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4541 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3842
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3842:com.htc.mediamanager/u0a32 (adj 15): empty #17
,E/dalvikvm( 4479): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4479): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4479): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4479): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4479): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4479): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4479): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4479): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4479): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4479): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4479): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4541): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 9.963MB for 84664-byte allocation
,W/dalvikvm( 4479): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4479): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4479): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
E/dalvikvm( 4479): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4479): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4479): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4479): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
W/ContextImpl( 4541): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 4541): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4541): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4541): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 9.978MB for 28144-byte allocation
,I/ActivityManager(  906): Recipient 3842
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 10.017MB for 39954-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 10.093MB for 79892-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4541/10151)
,V/WebViewChromiumFactoryProvider( 4541): Binding Chromium to main looper Looper (main, tid 1) {41af0200}
,I/LibraryLoader( 4541): Expected native library version number "",actual native library version number ""
,I/chromium( 4541): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4541): Initializing chromium process, renderers=0
,D/PMS     (  906): acquireWL(431b6548): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  906): acquireWL(431fa848): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  906): releaseWL(431fa848): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
E/AudioManagerAndroid( 4541): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4541): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4541): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4541): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4541): Local Branch: 
I/Adreno-EGL( 4541): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4541): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4541):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4541): Starting up...
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4541/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4541/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
,D/Process (  906): killProcessQuiet, pid=3998
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3998:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1839/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1839/10178)
,D/GCM     ( 1369): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 10.281MB for 75760-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44019208 u0 ReceiverList{43ff93e8 4479 com.facebook.katana/10026/u0 remote:43fce290}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44019208 u0 ReceiverList{43ff93e8 4479 com.facebook.katana/10026/u0 remote:43fce290}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4315beb8 u0 ReceiverList{4313f568 4479 com.facebook.katana/10026/u0 remote:43111a60}}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
,D/PMS     (  906): acquireWL(431fa410): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1436 10028 null
,D/PMS     (  906): releaseWL(431fa410): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  906): Recipient 3998
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GCoreFlp( 1436): Unknown pending intent to remove.
D/PMS     (  906): acquireWL(44014778): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1436 10028 null
D/PMS     (  906): releaseWL(44014778): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4479): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4479): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/wpa_supplicant( 1136): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1136): EAPOL: disable timer tick
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1136): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  906): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  906): releaseWL(42a58ba0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -47, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19819 delay=15s
,D/WifiWatchdogStateMachine(  906): WAN detection
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1839/10178)
,D/WISPrService( 4189): >>>>>WISPrService start isConnected = true<<<<<
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@42418988
,D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  906): acquireWL(43656ac0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4508/10078)
,I/QuickSettingWifi( 1115): receive.wifiConnect:true wifiAPname:NG700 elapse:0
D/PMS     (  906): acquireWL(43199570): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1222 10028 null
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  906): acquireWL(43201850): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1222 10028 null
D/PMS     (  906): releaseWL(43199570): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
I/CheckinService( 1222): Preparing to send checkin request
,I/EventLogService( 1222): Accumulating logs since 1450463657692
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 1222): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1222): Using GMS GoogleHttpClient
,D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(43656ac0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1222/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1222/10028)
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 1222): awaiting user notification for token
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41b12170 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 7 2 12
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4616 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4616): install
,I/MultiDex( 4616): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4616): loading existing secondary dex files
,I/MultiDex( 4616): load found 1 secondary dex files
,I/MultiDex( 4616): install done
,I/ProviderInstaller( 4616): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1369): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/SensorManager(  906): mEventCount = 1051
,W/dalvikvm( 4409): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4409): threadid=1: thread exiting with uncaught exception (group=0x416b9e30)
,E/AndroidRuntime( 4409): FATAL EXCEPTION: main
E/AndroidRuntime( 4409): Process: com.test.thalitest, PID: 4409
E/AndroidRuntime( 4409): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4409): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4409): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4409): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4409): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4409): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4409): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4409): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4409): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4409): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4409): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4409): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4409): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4409): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4409): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4409): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4409): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4409): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4409): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  906): App crashed! Process: com.test.thalitest
W/ActivityManager(  906):   Force finishing activity com.test.thalitest/.MainActivity
,I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
,D/PMS     (  906): acquireWL(4363f0b8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
,W/asset   (  906): Copying FileAsset 0x6474aed0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,I/Adreno-EGL( 4616): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4616): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4616): Build Date: 08/28/14 Thu,
I/Adreno-EGL( 4616): Local Branch: 
I/Adreno-EGL( 4616): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4616): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4616):                  aa63bbd948f41d15fc72f585e
,D/WIFI_ICON( 1115): WifiActivity: 2
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/PMS     (  906): releaseWL(425bb570): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4508/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1839/10178)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1436/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1888/1000)
D/PMS     (  906): acquireWL(41d2d0e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4299/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3893/10051)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3859/10154)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1268/10075)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/ConnectivityHelper( 1268): [onReceive] WIFI(1): CONNECTED
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/acms    ( 1888): Checking Certificates
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
I/acms    ( 1888): Checking Developer Certificates
I/acms    ( 1888): Checking Application Certificates
I/acms    ( 1888): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1888): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
,I/acms    ( 1888): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1888): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1888): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1888): Updating next query delay: 75600000
I/mlserverapp( 1888): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1888): cancelACMSProgrammedChecks
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4299/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): releaseWL(41d2d0e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/NetworkMonitor( 3859): type=WIFI subType= reason=null isConnected=true
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(425ce988): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/PMS     (  906): releaseWL(425ce988): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2427/10021)
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(4202fe98): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1222 10028 null
D/PMS     (  906): releaseWL(4202fe98): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1369): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  906): BroadcastRSSIForIMS, newrssi =-48 , oldRssi= -200
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/PMS     (  906): acquireWL(4250a880): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1369 10028 null
D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1369): [NET] getaddrinfo-,err=8
D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1369): [NET] getaddrinfo-, 1
D/libc    ( 1369): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =cd08 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,D/AutoSetting( 1414): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4508): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4508): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1414/10053)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4541/10151)
D/AutoSetting( 1414): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1414): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1414): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1414): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1414): service - handleMessage() setting current location null
D/AutoSetting( 1414): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1414): service - onStartCommand() check timezone in 30000
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1414/10053)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1839/10178)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 218
D/libc    (  364): [NET]res_nsend:resplen=79
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1369): [NET] getaddrinfo_proxy-, success
,I/dalvikvm-heap( 4167): Grow heap (frag case) to 13.517MB for 1821008-byte allocation
,W/fb4a(:<default>):UserScope( 4479): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4479): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
,W/Settings( 4616): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
W/ActivityManager(  906): Activity pause timeout for ActivityRecord{41fd3190 u0 com.test.thalitest/.MainActivity t2 f}
,I/FeedHostManager( 1268): [onResume]
,I/FeedProviderManager( 1268): onResume
I/SocialFeedProvider( 1268): +onResume
I/SocialFeedProvider( 1268): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1268): -onResume
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (1268/10075)
,D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1369): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  906): acquireWL(42349b08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
,D/PMS     (  906): releaseWL(42349b08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): releaseWL(4363f0b8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  906): killProcessQuiet, pid=4269
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  906): Killing 4269:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4269
I/Adreno-EGL( 4616): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4616): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4616): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4616): Local Branch: 
I/Adreno-EGL( 4616): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4616): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4616):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4616): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4616): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4616): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4616): Local Branch: 
I/Adreno-EGL( 4616): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4616): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4616):                  aa63bbd948f41d15fc72f585e
,E/fb4a(:<default>):LocalFbBroadcastManager( 4479): Called registerBroadcastReceiver twice.
,D/GCM     ( 1369): Connected
D/PMS     (  906): acquireWL(424ce090): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  906): releaseWL(4250a880): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1369/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/PMS     (  906): releaseWL(424ce090): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/PMS     (  906): acquireWL(433add38): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
,D/GCM     ( 1369): Message class mpf
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1369/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1369/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/PMS     (  906): releaseWL(433add38): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
D/PMS     (  906): acquireWL(43be9fb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
D/PMS     (  906): releaseWL(43be9fb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4616/10028)
,I/CheckinTask( 1222): Sending checkin request (9014 bytes)
D/libc    ( 1222): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1222): [NET] getaddrinfo-, 1
,D/libc    ( 1222): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =e959 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 242
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1222): [NET] getaddrinfo_proxy-, success
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    ( 1222): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420c0f78
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420c0f78, eanble = 0, strlen(mName) = 59
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42073870
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@4230fc40
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  906): mWirelessDisplayManager is null
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,D/PMS     (  906): releaseWL(431b6548): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=4 [21][1][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  906): acquireWL(44005ed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
,D/PMS     (  906): releaseWL(44005ed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 384ms
D/PMS     (  906): nativeSetInteractive:false
,D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
,D/HABCtrl (  906): TPE algorithm. remove timeout.
,D/NfcService( 1253): ScreenObserver: OFF
,D/NfcService( 1253): applyRouting - 0
,D/PMS     (  906): OOBE c monitor 11
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@424a1ad8)
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
,D/NfcService( 1253): applyRouting -2
D/PMN     (  906): wakingUp
D/PMS     (  906): acquireWL(43a3ce68): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
I/WindowManager(  906): No lock screen! windowToken=null
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
I/InputMethodManagerService(  906): Disable input method client, pid=4409
D/PMS     (  906): acquireWL(43fc5160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(43fc5160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  906): releaseWL(43a3ce68): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  906): onScreenOn
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1222/10028)
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/MtpService( 2427): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2427): [MTP][onReceive]-
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/NfcService( 1253): applyRouting - 0
,D/NfcService( 1253): applyRouting -2
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): acquireWL(43491128): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/AutoSetting( 1414): receiver - intent: android.intent.action.USER_PRESENT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1222/10028)
D/PMS     (  906): releaseWL(43491128): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,D/AutoSetting( 1414): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19820 delay=15s
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): SET_SCREEN_ON:On
I/wpa_supplicant( 1136): htc_wext_set_keepalive +
I/wpa_supplicant( 1136): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1136): getPrivFuncNum +	
I/wpa_supplicant( 1136): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1136): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1136): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/TetherSettings( 4189): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4189): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4189): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4189): Cust_ConnectToPC   : spcsc>false
D/        ( 4189): Cust_ConnectToPC   : IPT>true
D/        ( 4189): Cust_ConnectToPC   : Singel_USB>false
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
I/ClockThread( 1115): stop update clock
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,W/Settings( 4189): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WifiNative-wlan0(  906):    returned true
E/SmartNS_Utility( 4189): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4189): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4189): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/PSReceiver( 4189): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 4189): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 4189): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
W/Settings( 4189): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4189):  defaultType:0
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/NetworkPolicy(  906): updateScreenOn: false
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4663 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,D/PMS     (  906): acquireWL(43094e58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1436 10028 null
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1798): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1798): onScreenOn: 1450463665501
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1798): onScreenOn: 1450463665502
,D/PMS     (  906): releaseWL(43094e58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42073870
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42073870, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@4230fc40
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
,D/PMS     (  906): acquireWL(44060758): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
I/FeedHostManager( 1268): [onPause]
I/FeedProviderManager( 1268): onPause
I/FeedHostManager( 1268): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41ca1558
I/SocialFeedProvider( 1268): +onPause
I/SocialFeedProvider( 1268): -onPause
,W/ContextImpl( 4663): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/RemoteViews( 1115): com.google.android.gms (false,0)
D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1222): awaiting user notification for token
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41b12800 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/PMS     (  906): releaseWL(44060758): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19820 mDataStallAlarmIntent=PendingIntent{4232e540: PendingIntentRecord{424e0118 android broadcastIntent}}
,I/RemoteViews.Performance( 1115): com.google.android.gms 2 12 3 12
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/AlarmManager(  906): [AlarmQueuing] data connection: true
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
D/PMS     (  906): acquireWL(437edbe0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
,D/SmartSyncUtils( 4663): isEpsOn(), nState = 0
D/PMS     (  906): acquireWL(440611e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4663 1000 null
,D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
I/CheckinTask( 1222): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
,D/PMS     (  906): releaseWL(440611e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): SET_SCREEN_ON:Off
I/wpa_supplicant( 1136): htc_wext_set_keepalive +
I/wpa_supplicant( 1136): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1136): getPrivFuncNum +	
I/wpa_supplicant( 1136): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1136): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1136): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1136): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1136): htc_wext_set_keepalive - ret = 0
W/GoogleHttpClient( 1222): Unable to close GMS GoogleHttpClient
D/WifiNative-wlan0(  906):    returned true
,D/SmartSyncUtils( 4663): getMobilePolicyEnabled, result = true
D/PMS     (  906): releaseWL(437edbe0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  906): killProcessQuiet, pid=4299
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,V/SRS_Proc(  371): ParamSet string: screen_state=off
I/ActivityManager(  906): Killing 4299:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/ContactMessageStore( 1241): start background delete task...
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [1][0][0]
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
D/NetworkPolicy(  906): updateScreenOn: false
I/ActivityManager(  906): Recipient 4299
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(43201850): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,W/ContextImpl( 4663): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4663): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4663): isEpsOn(), nState = 0
,E/ActivityThread( 1222): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41e19920 that was originally bound here
E/ActivityThread( 1222): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41e19920 that was originally bound here
E/ActivityThread( 1222): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1222): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1222): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1222): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1222): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1222): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1222): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1222): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1222): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1222): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1222): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1222): 	at bks.a(SourceFile:298)
E/ActivityThread( 1222): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1222): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1222): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1222): 	at java.lang.Thread.run(Thread.java:864)
,D/SmartSyncUtils( 4663): getMobilePolicyEnabled, result = true
D/WifiService(  906): New client listening to asynchronous messages
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4230fc40
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4230fc40, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4230fc40, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4230fc40
,E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42310170 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42310170 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  906): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  906): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  906): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  906): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  906): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  906): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  906): 	at dalvik.system.NativeStart.main(Native Method)
D/GCM     ( 1369): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] getTotalRam: 1873 Mb
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1798): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1798): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1798): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1798): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1798): onScreenOff
D/PMS     (  906): acquireWL(4405ac00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1436 10028 null
,D/PMS     (  906): releaseWL(4405ac00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/GCM     ( 1369): GCM config loaded
,D/AutoSetting( 1414): service - mHandler: cancel location update
,D/AutoSetting( 1414): service -           changes count: 0
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =f4ae +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19,
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4,
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/23.59.123.86,
,I/GAV2    ( 4541): Thread[GAThread,5,main]: No campaign data found.
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  906): acquireWL(433d3928): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1436 10028 null
,D/PMS     (  906): acquireWL(43430220): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1436 10028 null
,D/PMS     (  906): releaseWL(433d3928): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): releaseWL(43430220): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/AutoSetting( 1493): service - handleMessage() stop self
,D/AutoSetting( 1493): service - onDestroy() END
,D/AutoSetting( 1493): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4322
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4322:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4322
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=4286,
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4286:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4286
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 10.974MB for 36988-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 11.002MB for 55478-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 11.008MB for 42970-byte allocation
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 11.056MB for 65476-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 11.063MB for 44210-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 11.095MB for 57344-byte allocation
,D/libc    ( 4479): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4479): [NET] getaddrinfo-,err=8
D/libc    ( 4479): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4479): [NET] getaddrinfo-, 1
,D/libc    ( 4479): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =a3ed +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 33
D/libc    (  364): [NET]res_nsend:resplen=93
D/libc    (  364): [NET]res_queryN: exit 3, ancount=3
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4479): [NET] getaddrinfo_proxy-, success
,I/global  ( 4479): call createSocket() return a new socket.
D/libc    ( 4479): [NET] getaddrinfo+,hn 11(0x33312e31332e39),sn(),family 0,flags 4
,D/libc    ( 4479): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4479): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4479): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(44046518): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4479 10026 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 11.225MB for 82882-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 11.242MB for 71804-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4479/10026)
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/ActivityManager(  906): Activity destroy timeout for ActivityRecord{41fd3190 u0 com.test.thalitest/.MainActivity t2 f}
,I/global  ( 4479): I/O error closing connection
I/global  ( 4479): java.net.SocketException: Socket is closed
I/global  ( 4479): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4479): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4479): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4479): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4479): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4479): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4479): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4479): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4479): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4479): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4479): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4479): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4479): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4479): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4479): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4479): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4479): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4479): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4479): Removing a connection that never existed!
D/PMS     (  906): releaseWL(44046518): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43647c48 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(43fab220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(43fab220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43a77850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43a77850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1414): service - mHandler: update timezone
,D/AutoSetting( 1493): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1493): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1493): service - onCreate()
,W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1493): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1493): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1586): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1493): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1493): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1493): service - mHandler: update timezone
,D/AutoSetting( 1493): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1493): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1493): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1493): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e86188 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 3 8 2 11
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(43651568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{423d6490: PendingIntentRecord{425078d0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141191, Int=0
D/PMS     (  906): acquireWL(43650b80): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
V/AlarmManager(  906): sending alarm PendingIntent{425938f0: PendingIntentRecord{424dd628 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141907, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
,D/PMS     (  906): releaseWL(43651568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): acquireWL(4362ac28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =256 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
D/PMS     (  906): releaseWL(4362ac28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1414): service - handleMessage() stop self
,D/AutoSetting( 1414): service - onDestroy() END
,D/AutoSetting( 1414): service - handleMessage() quit looper
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): acquireWL(41ef1d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=146194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41ef1d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): releaseWL(43650b80): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/Process (  906): killProcessQuiet, pid=3893
,I/ActivityManager(  906): Killing 3893:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 3893
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43f69f00 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1493): service - handleMessage() stop self
,D/AutoSetting( 1493): service - onDestroy() END
,D/AutoSetting( 1493): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4340
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Killing 4340:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4340,
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0,
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(4202fb90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(4202fb90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42239638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42239638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(428928c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=206194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428928c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(423eb9a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{4236ad18: PendingIntentRecord{43654db8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=228127, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4705 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{423ae260: PendingIntentRecord{4249e4e0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450463773971, Int=10800000
,D/PMS     (  906): releaseWL(423eb9a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4705/10047)
,D/Process (  906): killProcessQuiet, pid=4357
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4357:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4357
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/PMS     (  906): acquireWL(425eed60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{421f3d10: PendingIntentRecord{43654db8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231734, Int=0
,D/PMS     (  906): releaseWL(425eed60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(422f14f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  906): n_update end
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(422f14f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1),
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(424f49d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424f49d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(425de888): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=266194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425de888): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(41e4a560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41e4a560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43dfa100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43dfa100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(423704a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=326194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(423704a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1369): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1369): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1369): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1369): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1369): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1369): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1369): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1369): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,E/PlayEventLogger( 4131): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4131): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4131): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4131): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4131): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4131): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4131): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4131): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41b05ec0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 14 3 12
,D/libc    ( 4131): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4131): [NET] getaddrinfo-,err=8
D/libc    ( 4131): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4131): [NET] getaddrinfo-, 1
D/libc    ( 4131): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7161 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4131): [NET] getaddrinfo_proxy-, success
I/global  ( 4131): call createSocket() return a new socket.
D/libc    ( 4131): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4131): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4131): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4131): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(440498f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(440498f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(425c9578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=386194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425c9578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/Process ( 4409): killProcess, pid=4409
,D/Process ( 4409): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/InputMethodManagerService(  906): Disable input method client, pid=4409
,I/ActivityManager(  906): Recipient 4409
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  906): WIN DEATH: Window{41b0e9f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  906): Client connection lost with reason: 4
,I/ActivityManager(  906): Process com.test.thalitest (pid 4409) has died.
,D/PMS     (  906): acquireWL(425e1dc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/PMS     (  906): acquireWL(434ca1f8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{41d7dbf0: PendingIntentRecord{424848c8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=410199, Int=0
V/AlarmManager(  906): sending alarm PendingIntent{42d8f908: PendingIntentRecord{4388abd0 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1450463911616, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43fe3308): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(434ca1f8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(43fe3308): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): releaseWL(425e1dc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,W/Uploader( 1222): No account for auth token provided
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1222): [NET] getaddrinfo-, 1
,D/libc    ( 1222): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7bda +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1222): [NET] getaddrinfo_proxy-, success
I/global  ( 1222): call createSocket() return a new socket.
D/libc    ( 1222): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/PMS     (  906): acquireWL(425f7640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{43c09030: PendingIntentRecord{43c040f8 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=411436, Int=300000
,D/PMS     (  906): releaseWL(425f7640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4234d470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4234d470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425cf2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425cf2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(430ddb00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=446194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(430ddb00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(425c4038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425c4038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(425bac58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=506195, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425bac58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(44013358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
I/BatteryService(  906): n_update end
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(44013358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/ContextImpl( 4663): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/TetherSettings( 4189): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4189): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4189): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4189): Cust_ConnectToPC   : spcsc>false
D/        ( 4189): Cust_ConnectToPC   : IPT>true
D/        ( 4189): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4189): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4189): Index of the first 1 = 3
W/Settings( 4189): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4189): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4189): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4189): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4189): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4189): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
D/SmartNS_Utility( 4189): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  906): acquireWL(438a89a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=566195, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(438a89a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(430dbd88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(430dbd88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(425f2cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425f2cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1241): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1241): sku_id=99
D/ContactMessageStore( 1241): start background delete task...
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete,
,D/PMS     (  906): acquireWL(4309dff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=626195, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4309dff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43514dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43514dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
,D/PowerUI ( 1115): closing low battery warning: level=100
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43491728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(43491728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
,D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43f94240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=686194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43f94240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4315c488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{43c09030: PendingIntentRecord{43c040f8 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=711436, Int=300000
,D/PMS     (  906): releaseWL(4315c488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  906): acquireWL(43c08d58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43c08d58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(41afb2c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41afb2c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43f6f740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=746194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43f6f740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44082cc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{41da52d8: PendingIntentRecord{42423140 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785247, Int=0
,D/PMS     (  906): releaseWL(44082cc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): acquireWL(42fe6d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,I/BatteryService(  906): n_update end
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(42fe6d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(44054918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=806195, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(44054918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(433ed080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(433ed080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(436230b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(436230b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4258e9b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=866194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4258e9b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43fa3638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43fa3638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(426161d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426161d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(44085708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=926194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(44085708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43fceb30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43fceb30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4266a508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=986194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4266a508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(440164d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{4358baf0: PendingIntentRecord{424dd7a0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1010725, Int=0
,D/PMS     (  906): acquireWL(4334ee48): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1369 10028 null
V/AlarmManager(  906): sending alarm PendingIntent{42328e40: PendingIntentRecord{4232dd80 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450464494317, Int=900000
,D/PMS     (  906): releaseWL(4334ee48): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,V/AlarmManager(  906): sending alarm PendingIntent{425541d0: PendingIntentRecord{42941ba8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450464565664, Int=0
,D/PMS     (  906): acquireWL(43f9b778): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
,W/ContextImpl( 4663): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4663): call getInstance()
,D/SmartSyncUtils( 4663): isEpsOn(), nState = 0
D/PMS     (  906): releaseWL(43f9b778): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PowerUsageList:PowerUsageHelper( 4663): MY_DEBUG = false
D/PMS     (  906): releaseWL(440164d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(433344f8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4663 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4663): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4663): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 2, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4663): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4663): SettingOnTime = 1450486800000, randomSettingOnTime = 1450483677000
D/SmartSyncScreenOnOffTimeReceiver( 4663): SettingOffTime = 1450483200000, randomSettingOffTime = 1450483200000
D/SmartSyncScreenOnOffTimeReceiver( 4663): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4663): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4663): bNightModeTurnOffOnce = false
,D/PMS     (  906): acquireWL(43640c68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10028 null
W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): releaseWL(433344f8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/GCM     ( 1369): Message class mow
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1369/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1369/10028)
,D/PMS     (  906): acquireWL(43641fb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
,D/PMS     (  906): releaseWL(43640c68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): releaseWL(43641fb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=4 [186][9][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(4406ef30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4406ef30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43fa11b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(43fa11b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4382f5a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1046194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4382f5a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(436b23d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,I/BatteryService(  906): n_update end
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(436b23d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(430daf98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1106194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(430daf98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42ed7ea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(42ed7ea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(424e82b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1166194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(424e82b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(423c06f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(423c06f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(41cd3a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  906): releaseWL(41cd3a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(42d1a518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1226195, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42d1a518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4251ea68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4251ea68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42d5c2c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42d5c2c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(425d9ec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1286194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425d9ec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41f23420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(41f23420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(425ea590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(425ea590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4201ca08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1346194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4201ca08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42631e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1115): closing low battery warning: level=100
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(42631e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(433c57b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(433c57b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425ca980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1406194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425ca980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(430054c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(430054c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/PowerUI ( 1115): closing low battery warning: level=100
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4252cac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4252cac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4234b9b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1466194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4234b9b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426119c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426119c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42d52770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42d52770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4246e530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1526194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4246e530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4249b9d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(4249b9d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus,
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42d4feb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42d4feb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(44076988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1586194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(44076988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4348a5f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4348a5f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(425ad860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425ad860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(434b6298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1646195, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(434b6298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(423c30f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(423c30f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1115): closing low battery warning: level=100
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(435b97d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(435b97d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425b4aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1706194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425b4aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(423f9360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(423f9360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42622648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(42622648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43d2e7f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1766194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43d2e7f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(425ef378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(425ef378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): acquireWL(430cb508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(430cb508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  906): acquireWL(42d60938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1826195, Int=0
,I/ProcessStatsService(  906): Prepared write state in 27ms
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42d60938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2015-12-18-06-48-28.bin
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/PMS     (  906): acquireWL(43b007e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41da52d8: PendingIntentRecord{42423140 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1505274, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42339c90: PendingIntentRecord{424e77b0 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820923, Int=1800000
,D/PMS     (  906): acquireWL(425d7a50): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{42328e40: PendingIntentRecord{4232dd80 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450465394317, Int=900000
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): releaseWL(425d7a50): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/ContextImpl( 4663): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(43b007e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(43b17810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/BatteryService(  906): n_update end
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(43b17810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus,
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4367ad30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4367ad30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  906): killProcessQuiet, pid=4371
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/ActivityManager(  906): Killing 4371:com.android.settings:remote/1000 (adj 15): empty for 1807s
,D/PMS     (  906): acquireWL(425645f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10073}
,V/AlarmManager(  906): sending alarm PendingIntent{43674f40: PendingIntentRecord{4266ca20 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450465435963, Int=0
,D/PMS     (  906): releaseWL(425645f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,I/ActivityManager(  906): Recipient 4371
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4131): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4131): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4131): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4131): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4131): [1] DailyHygiene.reschedule: Scheduling new run in 92 minutes (failures=3)
,D/PMS     (  906): acquireWL(440288a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232c328: PendingIntentRecord{4232b468 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1886194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(440288a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4400f908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10073}
,V/AlarmManager(  906): sending alarm PendingIntent{42656f68: PendingIntentRecord{439659e8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450465451175, Int=0
,D/PMS     (  906): releaseWL(4400f908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4131): [1] 5.onFinished: Installation state replication succeeded.
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4777): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4777): ====startRecUseTime====
D/htc.customization.log.level( 4777):  is 
W/CustomizationLogLevel( 4777): Level value is invalid, use default level 2
D/CustomizationManager( 4777):  Read ACC file spent 0.103 (s)
D/CIDMapFileReader( 4777): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4777): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4777): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4777): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4777): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4777): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4777): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4777): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4777): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4777): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4777): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4777): Parsing tag category name = system
I/CustomizationCIDLoader( 4777): Parsing tag category name = application
I/CustomizationCIDLoader( 4777): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4777): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4777): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4777): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4777): Parsing tag category name = Settings
D/CustomizationManager( 4777):  Read CID file spent 0.155 (s)
D/CustomizationManager( 4777):  All configurations done spent 0.156 (s)
W/HtcNativeFlag( 4777): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4777): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4777): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4777): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4777, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
I/ActivityManager(  906): Killing 4167:com.google.android.apps.plus/u0a160 (adj 15): empty for 1801s
D/Process (  906): killProcessQuiet, pid=4167
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4541
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4524
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Killing 4541:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1801s
I/ActivityManager(  906): Killing 4524:com.android.chrome/u0a96 (adj 15): empty for 1801s
D/Process (  906): killProcessQuiet, pid=4508
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=3859
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4457
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Killing 4508:com.google.android.setupwizard/u0a78 (adj 15): empty for 1801s
I/ActivityManager(  906): Killing 3859:com.google.android.music:main/u0a154 (adj 15): empty for 1801s
I/ActivityManager(  906): Killing 4457:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1807s
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  906): Copying FileAsset 0x6dfa5f10 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  906): Recipient 4508
I/ActivityManager(  906): Recipient 4457
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3859
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.music (pid 3859): Died!
I/ActivityManager(  906): Recipient 4524
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4167
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4541
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  906): Skipping PackageSetting{4226c238 com.example.hello/10356} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
I/acms    ( 1888): Unregistering com.test.thalitest
E/acms    ( 1888): Could not unregister removed application com.test.thalitest
D/DotMatrix( 1586): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1586): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1436): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): acquireWL(430eb530): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1436 10028 null
D/PMS     (  906): releaseWL(430eb530): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/VoicemailCleanupService( 1296): Cleaning up data for package: com.test.thalitest
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/Launcher( 1268): Deferring update until onResume
D/Launcher( 1268): waitUntilResume // bindAppsRemoved
D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/PackageBroadcastService( 1222): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4791 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
E/ExternalAccountType( 1330): Unsupported attribute readOnly
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/MultiDex( 4791): install
I/MultiDex( 4791): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/MultiDex( 4791): loading existing secondary dex files
I/MultiDex( 4791): load found 1 secondary dex files
I/MultiDex( 4791): install done
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4807 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 1222): CP2 sync disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1222, uid=10028, userID:0
I/Icing   ( 1222): doRemovePackageData com.test.thalitest
I/ProviderInstaller( 4791): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  906): acquireWL(43fcc428): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
D/PMS     (  906): releaseWL(43fcc428): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4807): install
I/MultiDex( 4807): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4807): loading existing secondary dex files
I/MultiDex( 4807): load found 1 secondary dex files
I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4807): install done
I/ProviderInstaller( 4807): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1414): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1414): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1268): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2875): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4828 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteDBG( 2875): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63ac2e40
W/dalvikvm( 2875): threadid=14: thread exiting with uncaught exception (group=0x416b9e30)
E/AndroidRuntime( 2875): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2875): Process: com.google.android.googlequicksearchbox:search, PID: 2875
E/AndroidRuntime( 2875): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 2875): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2875): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2875): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
E/AndroidRuntime( 2875): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/AndroidRuntime( 2875): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
E/AndroidRuntime( 2875): 	at cid.d(PG:192)
E/AndroidRuntime( 2875): 	at clo.g(PG:594)
E/AndroidRuntime( 2875): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2875): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2875): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2875): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2875): 	at clr.tL(PG:827)
E/AndroidRuntime( 2875): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2875): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2875): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2875): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2875): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2875): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2875): killProcess, pid=2875
D/Process ( 2875): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
E/SQLiteLog( 4791): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4791): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca25ac0
E/DriveAsyncService( 4791): disk I/O error (code 3850)
E/DriveAsyncService( 4791): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4791): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4791): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4791): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4791): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4791): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4791): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4791): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4791): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4791): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4791): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4791): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4791): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4791): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4791): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 4791): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca25ac0
E/DocListDatabase( 4791): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4791): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4791): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4791): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4791): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4791): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4791): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4791): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4791): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4791): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4791): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4791): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4791): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4791): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4791): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4791): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4791): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4791): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4791): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4791): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4791): threadid=1: thread exiting with uncaught exception (group=0x416b9e30)
E/AndroidRuntime( 4791): FATAL EXCEPTION: main
E/AndroidRuntime( 4791): Process: com.google.android.gms.drive, PID: 4791
E/AndroidRuntime( 4791): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4791): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4791): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4791): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4791): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4791): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4791): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4791): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4791): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4791): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4791): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4791): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4791): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4791): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4791): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4791): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4791): 	... 10 more
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
D/Process ( 4791): killProcess, pid=4791
D/Process ( 4791): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
I/ActivityManager(  906): Recipient 2875
D/MediaRouterService(  906): Client com.google.android.googlequicksearchbox (pid 2875): Died!
I/ActivityManager(  906): Process com.google.android.googlequicksearchbox:search (pid 2875) has died.
D/WifiService(  906): Client connection lost with reason: 4
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4791
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4791) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 10899ms
E/SQLiteDatabase( 4828): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4828): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4828): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4828): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4828): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4828): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4828): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4828): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4828): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4828): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4828): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4828): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4828): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4828): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4828): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4828): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4828): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4828): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4828): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4828): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4828): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4828): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4828): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4828): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4828): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4828): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4828): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4828): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4828): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4828): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4828): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4828): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4828): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4828): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4828): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4828): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4828): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4828): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4828): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4828): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4828): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4828): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4828): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4828): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4828): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4828): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4828): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4828): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4828): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4828): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4828): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4828): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4828): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4828): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4828): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4828): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4828): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4828): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4828): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4828): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4828): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4828): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4828): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4828): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4828): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4828): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4828): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4828): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4828): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4828): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4828): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4828): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4828): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4828): threadid=11: thread exiting with uncaught exception (group=0x416b9e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4828): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4828): Process: com.google.android.apps.docs, PID: 4828
E/AndroidRuntime( 4828): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4828): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4828): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4828): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4828): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4828): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4828): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4828): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4828): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4828): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4828): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4828): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4828): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4828): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4828): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
D/Process ( 4828): killProcess, pid=4828
D/Process ( 4828): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4850 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Recipient 4828
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4828) has died.
W/ContextImpl( 4850): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4864 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4850): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4850): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4850): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4850): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4850): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4850): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4850): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4850): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4850): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4850): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4850): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4850): threadid=10: thread exiting with uncaught exception (group=0x416b9e30)
E/AndroidRuntime( 4850): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4850): Process: com.android.keychain, PID: 4850
E/AndroidRuntime( 4850): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4850): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4850): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4850): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4850): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4850): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4850): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4850): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4850): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4850): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  906): App crashed! Process: com.android.keychain
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1268): loadItems() com.htc.launcher.pageview.WidgetManager@41b7cd30 +
I/Prism.WidgetManager( 1268): onLoadItems() +
D/AppTag  ( 4864): getInstance(Context context)
D/AppTag  ( 4864): getInstance(Context context)
D/Process ( 4850): killProcess, pid=4850
D/Process ( 4850): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/AppTag  ( 4864): onCreate()
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450465467466.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  906): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 4 more
I/ActivityManager(  906): Recipient 4850
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4879 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/ActivityManager(  906): Process com.android.keychain (pid 4850) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20378ms
W/PackageManager(  906): Unable to load service info ResolveInfo{42566300 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4879): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4879): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4879): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4879): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4879): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4879): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4879): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4879): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4879): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4879): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4879): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4879): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4879): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4879): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4879): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4879): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 4879): 	at del.a(PG:264)
E/SQLiteDatabase( 4879): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4879): 	at java.lang.Thread.run(Thread.java:864)
D/PMS     (  906): acquireWL(42a78bf8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4879 10160 null
D/PMS     (  906): releaseWL(42a78bf8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null

```
